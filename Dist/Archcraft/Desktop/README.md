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

Total: 18

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Archcraft Rolling | 11       | 84.62%  |
| Archcraft         | 2        | 15.38%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Archcraft | 13       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 6.3.9-arch1-1         | 2        | 14.29%  |
| 5.19.13-arch1-1       | 2        | 14.29%  |
| 6.3.8-arch1-1         | 1        | 7.14%   |
| 6.3.4-arch1-1         | 1        | 7.14%   |
| 6.1.9-x64v1-xanmod1-1 | 1        | 7.14%   |
| 6.0.12-arch1-1        | 1        | 7.14%   |
| 5.19.9-arch1-1        | 1        | 7.14%   |
| 5.18.16-arch1-1       | 1        | 7.14%   |
| 5.18.0-arch1-1        | 1        | 7.14%   |
| 5.16.3-arch1-1        | 1        | 7.14%   |
| 5.15.7-zen1-1-zen     | 1        | 7.14%   |
| 5.14.10-arch1-1       | 1        | 7.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.3.9   | 2        | 14.29%  |
| 5.19.13 | 2        | 14.29%  |
| 6.3.8   | 1        | 7.14%   |
| 6.3.4   | 1        | 7.14%   |
| 6.1.9   | 1        | 7.14%   |
| 6.0.12  | 1        | 7.14%   |
| 5.19.9  | 1        | 7.14%   |
| 5.18.16 | 1        | 7.14%   |
| 5.18.0  | 1        | 7.14%   |
| 5.16.3  | 1        | 7.14%   |
| 5.15.7  | 1        | 7.14%   |
| 5.14.10 | 1        | 7.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.3     | 4        | 28.57%  |
| 5.19    | 3        | 21.43%  |
| 5.18    | 2        | 14.29%  |
| 6.1     | 1        | 7.14%   |
| 6.0     | 1        | 7.14%   |
| 5.16    | 1        | 7.14%   |
| 5.15    | 1        | 7.14%   |
| 5.14    | 1        | 7.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 13       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| openbox | 5        | 38.46%  |
| bspwm   | 3        | 23.08%  |
| XFCE    | 2        | 15.38%  |
| qtile   | 1        | 7.69%   |
| KDE5    | 1        | 7.69%   |
| Unknown | 1        | 7.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 12       | 92.31%  |
| Wayland | 1        | 7.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 10       | 76.92%  |
| Unknown | 2        | 15.38%  |
| LightDM | 1        | 7.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 9        | 69.23%  |
| en_GB | 2        | 15.38%  |
| pt_BR | 1        | 7.69%   |
| es_MX | 1        | 7.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 8        | 61.54%  |
| BIOS | 5        | 38.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 8        | 61.54%  |
| Btrfs | 4        | 30.77%  |
| Xfs   | 1        | 7.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 10       | 76.92%  |
| Unknown | 2        | 15.38%  |
| MBR     | 1        | 7.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 76.92%  |
| Yes       | 3        | 23.08%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 7        | 53.85%  |
| No        | 6        | 46.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 4        | 30.77%  |
| MSI                 | 2        | 15.38%  |
| Lenovo              | 2        | 15.38%  |
| Gigabyte Technology | 2        | 15.38%  |
| ASRock              | 2        | 15.38%  |
| ECS                 | 1        | 7.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| MSI MS-7C91                         | 1        | 7.69%   |
| MSI MS-7C51                         | 1        | 7.69%   |
| Lenovo ThinkCentre M710q 10MR0047US | 1        | 7.69%   |
| Lenovo ThinkCentre Edge72 3484HPU   | 1        | 7.69%   |
| Gigabyte F2A68HM-DS2                | 1        | 7.69%   |
| Gigabyte B550I AORUS PRO AX         | 1        | 7.69%   |
| ECS G31T-M                          | 1        | 7.69%   |
| ASUS ROG DOMINUS EXTREME            | 1        | 7.69%   |
| ASUS PRIME X470-PRO                 | 1        | 7.69%   |
| ASUS P8H61-M LX R2.0                | 1        | 7.69%   |
| ASUS H110M-E/M.2                    | 1        | 7.69%   |
| ASRock H97M Pro4                    | 1        | 7.69%   |
| ASRock B550M Pro4                   | 1        | 7.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Lenovo ThinkCentre   | 2        | 15.38%  |
| MSI MS-7C91          | 1        | 7.69%   |
| MSI MS-7C51          | 1        | 7.69%   |
| Gigabyte F2A68HM-DS2 | 1        | 7.69%   |
| Gigabyte B550I       | 1        | 7.69%   |
| ECS G31T-M           | 1        | 7.69%   |
| ASUS ROG             | 1        | 7.69%   |
| ASUS PRIME           | 1        | 7.69%   |
| ASUS P8H61-M         | 1        | 7.69%   |
| ASUS H110M-E         | 1        | 7.69%   |
| ASRock H97M          | 1        | 7.69%   |
| ASRock B550M         | 1        | 7.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 3        | 23.08%  |
| 2019 | 2        | 15.38%  |
| 2014 | 2        | 15.38%  |
| 2012 | 2        | 15.38%  |
| 2018 | 1        | 7.69%   |
| 2017 | 1        | 7.69%   |
| 2016 | 1        | 7.69%   |
| 2007 | 1        | 7.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 13       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 13       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 13       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 4        | 30.77%  |
| 32.01-64.0  | 4        | 30.77%  |
| 3.01-4.0    | 2        | 15.38%  |
| 64.01-256.0 | 1        | 7.69%   |
| 16.01-24.0  | 1        | 7.69%   |
| 8.01-16.0   | 1        | 7.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 3.01-4.0  | 5        | 35.71%  |
| 2.01-3.0  | 3        | 21.43%  |
| 1.01-2.0  | 3        | 21.43%  |
| 4.01-8.0  | 2        | 14.29%  |
| 8.01-16.0 | 1        | 7.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 4        | 30.77%  |
| 1      | 3        | 23.08%  |
| 5      | 2        | 15.38%  |
| 4      | 2        | 15.38%  |
| 3      | 2        | 15.38%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 92.31%  |
| Yes       | 1        | 7.69%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 13       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 7        | 53.85%  |
| Yes       | 6        | 46.15%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 69.23%  |
| Yes       | 4        | 30.77%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| USA      | 4        | 30.77%  |
| UK       | 2        | 15.38%  |
| Brazil   | 2        | 15.38%  |
| Slovakia | 1        | 7.69%   |
| Poland   | 1        | 7.69%   |
| Mexico   | 1        | 7.69%   |
| Hungary  | 1        | 7.69%   |
| Czechia  | 1        | 7.69%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Tábor        | 1        | 7.69%   |
| Paulista      | 1        | 7.69%   |
| Osasco        | 1        | 7.69%   |
| Milton Keynes | 1        | 7.69%   |
| Manchester    | 1        | 7.69%   |
| Guadalajara   | 1        | 7.69%   |
| Gdansk        | 1        | 7.69%   |
| Frisco        | 1        | 7.69%   |
| Dallas        | 1        | 7.69%   |
| Čadca        | 1        | 7.69%   |
| Budapest      | 1        | 7.69%   |
| Atlanta       | 1        | 7.69%   |
| Abilene       | 1        | 7.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 5      | 16.67%  |
| Seagate             | 4        | 7      | 13.33%  |
| Samsung Electronics | 3        | 3      | 10%     |
| Sandisk             | 2        | 2      | 6.67%   |
| Phison Electronics  | 2        | 2      | 6.67%   |
| Kingston            | 2        | 2      | 6.67%   |
| Intel               | 2        | 5      | 6.67%   |
| Hitachi             | 2        | 2      | 6.67%   |
| Toshiba             | 1        | 1      | 3.33%   |
| ROG                 | 1        | 1      | 3.33%   |
| Patriot             | 1        | 1      | 3.33%   |
| Crucial             | 1        | 1      | 3.33%   |
| China               | 1        | 2      | 3.33%   |
| Apacer              | 1        | 1      | 3.33%   |
| A-DATA Technology   | 1        | 2      | 3.33%   |
| Unknown             | 1        | 1      | 3.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 2        | 6.45%   |
| WDC WD5000AAKX-75U6AA0 500GB                        | 1        | 3.23%   |
| WDC WD5000AAKX-60U6AA0 500GB                        | 1        | 3.23%   |
| WDC WD5000AAKX-08U6AA0 500GB                        | 1        | 3.23%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1        | 3.23%   |
| WDC WD10EZEX-22RKKA0 1TB                            | 1        | 3.23%   |
| Toshiba DT01ACA200 2TB                              | 1        | 3.23%   |
| Seagate ST6000DM003-2CY186 6TB                      | 1        | 3.23%   |
| Seagate ST3500410AS 500GB                           | 1        | 3.23%   |
| Seagate ST320LM001 HN-M320MBB 320GB                 | 1        | 3.23%   |
| Seagate ST31500341AS 1TB                            | 1        | 3.23%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1        | 3.23%   |
| Sandisk WD_BLACK SN770 1TB                          | 1        | 3.23%   |
| SanDisk SDSSDA240G 240GB                            | 1        | 3.23%   |
| Samsung SSD 970 EVO Plus 1TB                        | 1        | 3.23%   |
| ROG ESD-S1C 1TB                                     | 1        | 3.23%   |
| Phison E16 PCIe4 NVMe Controller 1TB                | 1        | 3.23%   |
| Phison E12 NVMe Controller 1TB                      | 1        | 3.23%   |
| Patriot Burst 120GB SSD                             | 1        | 3.23%   |
| Kingston SFYRS500G 500GB                            | 1        | 3.23%   |
| Kingston SA400M8240G 240GB SSD                      | 1        | 3.23%   |
| Intel SSDSC2KW256G8 256GB                           | 1        | 3.23%   |
| Intel SSDPE21D480GA 480GB                           | 1        | 3.23%   |
| Hitachi HTS547550A9E384 500GB                       | 1        | 3.23%   |
| Hitachi HTS545050A7E380 500GB                       | 1        | 3.23%   |
| Crucial M4-CT064M4SSD2 64GB                         | 1        | 3.23%   |
| China SATA SSD 512GB                                | 1        | 3.23%   |
| Apacer AS350 128GB SSD                              | 1        | 3.23%   |
| A-DATA SU650 240GB SSD                              | 1        | 3.23%   |
| Unknown                                             | 1        | 3.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 5        | 5      | 41.67%  |
| Seagate | 4        | 7      | 33.33%  |
| Hitachi | 2        | 2      | 16.67%  |
| Toshiba | 1        | 1      | 8.33%   |

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
| HDD     | 8        | 15     | 36.36%  |
| SSD     | 7        | 11     | 31.82%  |
| NVMe    | 6        | 11     | 27.27%  |
| Unknown | 1        | 1      | 4.55%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 11       | 26     | 61.11%  |
| NVMe | 6        | 11     | 33.33%  |
| SAS  | 1        | 1      | 5.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 10       | 18     | 62.5%   |
| 0.51-1.0   | 4        | 6      | 25%     |
| 1.01-2.0   | 1        | 1      | 6.25%   |
| 4.01-10.0  | 1        | 1      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1001-2000  | 4        | 30.77%  |
| 101-250    | 3        | 23.08%  |
| 251-500    | 2        | 15.38%  |
| 501-1000   | 2        | 15.38%  |
| 2001-3000  | 1        | 7.69%   |
| Unknown    | 1        | 7.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 101-250   | 3        | 23.08%  |
| 251-500   | 2        | 15.38%  |
| 1-20      | 2        | 15.38%  |
| 51-100    | 2        | 15.38%  |
| 21-50     | 1        | 7.69%   |
| 1001-2000 | 1        | 7.69%   |
| 501-1000  | 1        | 7.69%   |
| Unknown   | 1        | 7.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Desktops | Drives | Percent |
|-------------------------------|----------|--------|---------|
| WDC WD5000AAKX-75U6AA0 500GB  | 1        | 1      | 33.33%  |
| WDC WD5000AAKX-60U6AA0 500GB  | 1        | 1      | 33.33%  |
| Hitachi HTS547550A9E384 500GB | 1        | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 2      | 66.67%  |
| Hitachi | 1        | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 2      | 66.67%  |
| Hitachi | 1        | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 3      | 100%    |

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
| Works    | 10       | 27     | 62.5%   |
| Detected | 3        | 4      | 18.75%  |
| Malfunc  | 2        | 3      | 12.5%   |
| Failed   | 1        | 4      | 6.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 7        | 33.33%  |
| AMD                         | 6        | 28.57%  |
| Samsung Electronics         | 3        | 14.29%  |
| Phison Electronics          | 2        | 9.52%   |
| SanDisk                     | 1        | 4.76%   |
| Kingston Technology Company | 1        | 4.76%   |
| ASMedia Technology          | 1        | 4.76%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 3        | 11.54%  |
| AMD 500 Series Chipset SATA Controller                                        | 3        | 11.54%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2        | 7.69%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 2        | 7.69%   |
| SanDisk WD Black SN770 NVMe SSD                                               | 1        | 3.85%   |
| Phison E16 PCIe4 NVMe Controller                                              | 1        | 3.85%   |
| Phison E12 NVMe Controller                                                    | 1        | 3.85%   |
| Kingston Company FURY Renegade NVMe SSD                                       | 1        | 3.85%   |
| Intel Volume Management Device NVMe RAID Controller                           | 1        | 3.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1        | 3.85%   |
| Intel Optane SSD 900P Series                                                  | 1        | 3.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 1        | 3.85%   |
| Intel C620 Series Chipset Family IDE Redirection                              | 1        | 3.85%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                     | 1        | 3.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 1        | 3.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 1        | 3.85%   |
| ASMedia ASM1062 Serial ATA Controller                                         | 1        | 3.85%   |
| AMD FCH SATA Controller [IDE mode]                                            | 1        | 3.85%   |
| AMD FCH SATA Controller D                                                     | 1        | 3.85%   |
| AMD 400 Series Chipset SATA Controller                                        | 1        | 3.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 12       | 57.14%  |
| NVMe | 6        | 28.57%  |
| IDE  | 2        | 9.52%   |
| RAID | 1        | 4.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 7        | 53.85%  |
| AMD    | 6        | 46.15%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Xeon W-3175X CPU @ 3.10GHz               | 1        | 7.69%   |
| Intel Core i7-2600K CPU @ 3.40GHz              | 1        | 7.69%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1        | 7.69%   |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1        | 7.69%   |
| Intel Core i5-4690K CPU @ 3.50GHz              | 1        | 7.69%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 1        | 7.69%   |
| Intel Core 2 Duo CPU E4600 @ 2.40GHz           | 1        | 7.69%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 7.69%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1        | 7.69%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1        | 7.69%   |
| AMD Ryzen 5 4600G with Radeon Graphics         | 1        | 7.69%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1        | 7.69%   |
| AMD A10-7800 Radeon R7, 12 Compute Cores 4C+8G | 1        | 7.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| Intel Core i5    | 3        | 23.08%  |
| AMD Ryzen 5      | 3        | 23.08%  |
| Intel Xeon       | 1        | 7.69%   |
| Intel Core i7    | 1        | 7.69%   |
| Intel Core i3    | 1        | 7.69%   |
| Intel Core 2 Duo | 1        | 7.69%   |
| AMD Ryzen 9      | 1        | 7.69%   |
| AMD Ryzen 7      | 1        | 7.69%   |
| AMD A10          | 1        | 7.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 4        | 30.77%  |
| 6      | 3        | 23.08%  |
| 2      | 3        | 23.08%  |
| 28     | 1        | 7.69%   |
| 12     | 1        | 7.69%   |
| 8      | 1        | 7.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 13       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 9        | 69.23%  |
| 1      | 4        | 30.77%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 13       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 5        | 38.46%  |
| 0x906e9    | 1        | 7.69%   |
| 0x6fd      | 1        | 7.69%   |
| 0x506e3    | 1        | 7.69%   |
| 0x50654    | 1        | 7.69%   |
| 0x306c3    | 1        | 7.69%   |
| 0x0a201016 | 1        | 7.69%   |
| 0x0a201009 | 1        | 7.69%   |
| 0x08701021 | 1        | 7.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 3       | 2        | 15.38%  |
| Zen 2       | 2        | 15.38%  |
| Skylake     | 2        | 15.38%  |
| Zen+        | 1        | 7.69%   |
| Steamroller | 1        | 7.69%   |
| SandyBridge | 1        | 7.69%   |
| KabyLake    | 1        | 7.69%   |
| IvyBridge   | 1        | 7.69%   |
| Haswell     | 1        | 7.69%   |
| Core        | 1        | 7.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 6        | 40%     |
| AMD    | 6        | 40%     |
| Intel  | 3        | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Nvidia GP107 [GeForce GTX 1050 Ti]                                    | 2        | 12.5%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]               | 2        | 12.5%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                 | 1        | 6.25%   |
| Nvidia TU102 [TITAN RTX]                                              | 1        | 6.25%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                   | 1        | 6.25%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                        | 1        | 6.25%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller      | 1        | 6.25%   |
| Intel HD Graphics 630                                                 | 1        | 6.25%   |
| Intel HD Graphics 530                                                 | 1        | 6.25%   |
| AMD RV710 [Radeon HD 4350/4550]                                       | 1        | 6.25%   |
| AMD Renoir                                                            | 1        | 6.25%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]            | 1        | 6.25%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM] | 1        | 6.25%   |
| AMD Kaveri [Radeon R7 Graphics]                                       | 1        | 6.25%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 4        | 30.77%  |
| 1 x AMD        | 4        | 30.77%  |
| 1 x Intel      | 2        | 15.38%  |
| 2 x AMD        | 1        | 7.69%   |
| Intel + Nvidia | 1        | 7.69%   |
| AMD + Nvidia   | 1        | 7.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 9        | 64.29%  |
| Proprietary | 5        | 35.71%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 5        | 35.71%  |
| 7.01-8.0   | 3        | 21.43%  |
| 5.01-6.0   | 1        | 7.14%   |
| 3.01-4.0   | 1        | 7.14%   |
| 16.01-24.0 | 1        | 7.14%   |
| 1.01-2.0   | 1        | 7.14%   |
| 8.01-16.0  | 1        | 7.14%   |
| 0.51-1.0   | 1        | 7.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 2        | 13.33%  |
| Dell                 | 2        | 13.33%  |
| Ancor Communications | 2        | 13.33%  |
| Toshiba              | 1        | 6.67%   |
| Samsung Electronics  | 1        | 6.67%   |
| Lenovo               | 1        | 6.67%   |
| Hewlett-Packard      | 1        | 6.67%   |
| BenQ                 | 1        | 6.67%   |
| ASUSTek Computer     | 1        | 6.67%   |
| AGO                  | 1        | 6.67%   |
| Acer                 | 1        | 6.67%   |
| Unknown              | 1        | 6.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                      | 1        | 5.88%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 5.88%   |
| Lenovo P24h-10 LEN61AE 2560x1440 530x300mm 24.0-inch                  | 1        | 5.88%   |
| Hewlett-Packard V320 HPN3363 1920x1080 698x393mm 31.5-inch            | 1        | 5.88%   |
| Goldstar L1742 GSM449C 1280x1024 338x270mm 17.0-inch                  | 1        | 5.88%   |
| Goldstar FULL HD GSM5BFB 1920x1080 480x270mm 21.7-inch                | 1        | 5.88%   |
| Dell SE2417HG DELD08E 1920x1080 521x293mm 23.5-inch                   | 1        | 5.88%   |
| Dell SE2417HG DELD08D 1920x1080 520x290mm 23.4-inch                   | 1        | 5.88%   |
| Dell S2421NX DEL41FB 1920x1080 527x296mm 23.8-inch                    | 1        | 5.88%   |
| BenQ BL3200 BNQ8017 2560x1440 708x398mm 32.0-inch                     | 1        | 5.88%   |
| ASUSTek Computer ROG PG65UQ AUS65A1 3840x2160 1430x800mm 64.5-inch    | 1        | 5.88%   |
| Ancor Communications ROG PG348Q ACI3433 3440x1440 797x333mm 34.0-inch | 1        | 5.88%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 1        | 5.88%   |
| AGO LCD Monitor AGO0001 1920x1080 300x230mm 14.9-inch                 | 1        | 5.88%   |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch                 | 1        | 5.88%   |
| Acer XF251Q ACR0624 1920x1080 544x303mm 24.5-inch                     | 1        | 5.88%   |
| Unknown                                                               | 1        | 5.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 7        | 50%     |
| 2560x1440 (QHD)  | 2        | 14.29%  |
| 3840x2160 (4K)   | 1        | 7.14%   |
| 3440x1440        | 1        | 7.14%   |
| 3200x1080        | 1        | 7.14%   |
| 1280x1024 (SXGA) | 1        | 7.14%   |
| Unknown          | 1        | 7.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 3        | 18.75%  |
| 23      | 2        | 12.5%   |
| 21      | 2        | 12.5%   |
| 74      | 1        | 6.25%   |
| 64      | 1        | 6.25%   |
| 34      | 1        | 6.25%   |
| 32      | 1        | 6.25%   |
| 31      | 1        | 6.25%   |
| 17      | 1        | 6.25%   |
| 14      | 1        | 6.25%   |
| 12      | 1        | 6.25%   |
| Unknown | 1        | 6.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 5        | 33.33%  |
| 701-800     | 2        | 13.33%  |
| 401-500     | 2        | 13.33%  |
| 601-700     | 1        | 6.67%   |
| 301-350     | 1        | 6.67%   |
| 201-300     | 1        | 6.67%   |
| 1501-2000   | 1        | 6.67%   |
| 1001-1500   | 1        | 6.67%   |
| Unknown     | 1        | 6.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 9        | 64.29%  |
| 5/4     | 1        | 7.14%   |
| 4/3     | 1        | 7.14%   |
| 21/9    | 1        | 7.14%   |
| 16/10   | 1        | 7.14%   |
| Unknown | 1        | 7.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 6        | 37.5%   |
| 351-500        | 3        | 18.75%  |
| More than 1000 | 2        | 12.5%   |
| 71-80          | 1        | 6.25%   |
| 251-300        | 1        | 6.25%   |
| 141-150        | 1        | 6.25%   |
| 101-110        | 1        | 6.25%   |
| Unknown        | 1        | 6.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 8        | 50%     |
| 101-120 | 3        | 18.75%  |
| 121-160 | 2        | 12.5%   |
| 1-50    | 1        | 6.25%   |
| 161-240 | 1        | 6.25%   |
| Unknown | 1        | 6.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 8        | 61.54%  |
| 2     | 5        | 38.46%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 10       | 58.82%  |
| Intel                 | 5        | 29.41%  |
| Ralink Technology     | 1        | 5.88%   |
| Aquantia              | 1        | 5.88%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7        | 30.43%  |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 8.7%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 4.35%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 4.35%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 4.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 4.35%   |
| Realtek 802.11ac NIC                                              | 1        | 4.35%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 4.35%   |
| Intel Wireless-AC 9260                                            | 1        | 4.35%   |
| Intel Wireless 8265 / 8275                                        | 1        | 4.35%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 4.35%   |
| Intel I211 Gigabit Network Connection                             | 1        | 4.35%   |
| Intel Ethernet Connection (3) I219-LM                             | 1        | 4.35%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 4.35%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 4.35%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 4.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 3        | 50%     |
| Realtek Semiconductor | 2        | 33.33%  |
| Ralink Technology     | 1        | 16.67%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter | 1        | 14.29%  |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter               | 1        | 14.29%  |
| Realtek 802.11ac NIC                                     | 1        | 14.29%  |
| Ralink MT7601U Wireless Adapter                          | 1        | 14.29%  |
| Intel Wireless-AC 9260                                   | 1        | 14.29%  |
| Intel Wireless 8265 / 8275                               | 1        | 14.29%  |
| Intel Wi-Fi 6 AX200                                      | 1        | 14.29%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 9        | 64.29%  |
| Intel                 | 4        | 28.57%  |
| Aquantia              | 1        | 7.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7        | 43.75%  |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 12.5%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 6.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 6.25%   |
| Intel I211 Gigabit Network Connection                             | 1        | 6.25%   |
| Intel Ethernet Connection (3) I219-LM                             | 1        | 6.25%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 6.25%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 6.25%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 6.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 13       | 68.42%  |
| WiFi     | 6        | 31.58%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 10       | 76.92%  |
| WiFi     | 3        | 23.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 7        | 53.85%  |
| 2     | 5        | 38.46%  |
| 3     | 1        | 7.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 9        | 69.23%  |
| Yes  | 4        | 30.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 3        | 75%     |
| Cambridge Silicon Radio | 1        | 25%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 25%     |
| Intel Bluetooth wireless interface                  | 1        | 25%     |
| Intel AX200 Bluetooth                               | 1        | 25%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 25%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| AMD                 | 9        | 31.03%  |
| Intel               | 7        | 24.14%  |
| Nvidia              | 6        | 20.69%  |
| Logitech            | 2        | 6.9%    |
| C-Media Electronics | 2        | 6.9%    |
| Texas Instruments   | 1        | 3.45%   |
| Oculus VR           | 1        | 3.45%   |
| Kingston Technology | 1        | 3.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 9.09%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 6.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 6.06%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 6.06%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 6.06%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 3.03%   |
| Oculus VR Rift CV1 Audio                                                   | 1        | 3.03%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 3.03%   |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 3.03%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 3.03%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 3.03%   |
| Logitech H390 headset with microphone                                      | 1        | 3.03%   |
| Logitech G432 Gaming Headset                                               | 1        | 3.03%   |
| Kingston Technology HyperX QuadCast                                        | 1        | 3.03%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 3.03%   |
| Intel Lewisburg MROM 0                                                     | 1        | 3.03%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 3.03%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 3.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 3.03%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1        | 3.03%   |
| C-Media Electronics Antlion USB adapter                                    | 1        | 3.03%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1        | 3.03%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 3.03%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1        | 3.03%   |
| AMD FCH Azalia Controller                                                  | 1        | 3.03%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 3.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 3.03%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 2        | 15.38%  |
| Crucial             | 2        | 15.38%  |
| Corsair             | 2        | 15.38%  |
| A-DATA Technology   | 2        | 15.38%  |
| Unknown             | 1        | 7.69%   |
| Team                | 1        | 7.69%   |
| Samsung Electronics | 1        | 7.69%   |
| Micron Technology   | 1        | 7.69%   |
| G.Skill             | 1        | 7.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                     | 1        | 7.14%   |
| Unknown RAM Module 1GB DIMM SDRAM                     | 1        | 7.14%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s    | 1        | 7.14%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s | 1        | 7.14%   |
| Micron RAM F6451U64F9333G 4GB DIMM DDR3 1333MT/s      | 1        | 7.14%   |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3600MT/s | 1        | 7.14%   |
| Kingston RAM 9905402-532.A00LF 4GB DIMM DDR3 1600MT/s | 1        | 7.14%   |
| G.Skill RAM F4-3000C16-8GTZR 8GB DIMM DDR4 3200MT/s   | 1        | 7.14%   |
| Crucial RAM CT51264BA1339.M16F 4GB DIMM DDR3 1333MT/s | 1        | 7.14%   |
| Crucial RAM BL8G36C16U4B.M8FE1 8GB DIMM DDR4 3733MT/s | 1        | 7.14%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s | 1        | 7.14%   |
| Corsair RAM CMT16GX4M2K4266C19 8GB DIMM DDR4 2133MT/s | 1        | 7.14%   |
| A-DATA RAM Module 8GB DIMM DDR4 2133MT/s              | 1        | 7.14%   |
| A-DATA RAM DDR4 3600 2OZ 8GB DIMM DDR4 2667MT/s       | 1        | 7.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 7        | 63.64%  |
| DDR3  | 3        | 27.27%  |
| SDRAM | 1        | 9.09%   |

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
| 8192  | 6        | 50%     |
| 4096  | 2        | 16.67%  |
| 32768 | 1        | 8.33%   |
| 16384 | 1        | 8.33%   |
| 2048  | 1        | 8.33%   |
| 1024  | 1        | 8.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 2667    | 2        | 16.67%  |
| 2133    | 2        | 16.67%  |
| 1600    | 2        | 16.67%  |
| 3800    | 1        | 8.33%   |
| 3733    | 1        | 8.33%   |
| 3600    | 1        | 8.33%   |
| 3200    | 1        | 8.33%   |
| 1333    | 1        | 8.33%   |
| Unknown | 1        | 8.33%   |

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
| 0     | 11       | 84.62%  |
| 2     | 1        | 7.69%   |
| 1     | 1        | 7.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Unassigned class | 1        | 50%     |
| Graphics card    | 1        | 50%     |

