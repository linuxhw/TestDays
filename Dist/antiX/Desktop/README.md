antiX - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for antiX.

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

Total: 12

| Vendor   | Model                    | Probe                                                      | Date         |
|----------|--------------------------|------------------------------------------------------------|--------------|
| Unknown  | K8NF3-VSTA               | [f2ea6e0d83](https://linux-hardware.org/?probe=f2ea6e0d83) | Jun 24, 2022 |
| MSI      | B560M PRO-VDH WIFI [CEC] | [8654086b85](https://linux-hardware.org/?probe=8654086b85) | Jun 20, 2022 |
| Gigabyte | F2A85XM-D3H              | [cf20f6e233](https://linux-hardware.org/?probe=cf20f6e233) | Mar 09, 2022 |
| Gigabyte | 945GCMX-S2               | [54149177a7](https://linux-hardware.org/?probe=54149177a7) | Feb 12, 2022 |
| Unknown  | NF-CK804                 | [dc6287d017](https://linux-hardware.org/?probe=dc6287d017) | Jan 05, 2022 |
| ASUSTek  | A8R-MVP                  | [43a7b44e3f](https://linux-hardware.org/?probe=43a7b44e3f) | Mar 27, 2021 |
| ASUSTek  | M2N-MX SE Plus           | [a8985150bd](https://linux-hardware.org/?probe=a8985150bd) | Feb 08, 2021 |
| ASRock   | H81M-ITX                 | [7b2d6774c8](https://linux-hardware.org/?probe=7b2d6774c8) | Feb 05, 2021 |
| HP       | 3641h                    | [f918637d53](https://linux-hardware.org/?probe=f918637d53) | Jul 29, 2020 |
| Unknown  | Unknown                  | [7653370d96](https://linux-hardware.org/?probe=7653370d96) | Dec 16, 2019 |
| ASUSTek  | P5KPL/1600               | [8ba4b22f71](https://linux-hardware.org/?probe=8ba4b22f71) | Oct 22, 2019 |
| Lenovo   | ThinkCentre M91p 4480B9U | [e68917ee9f](https://linux-hardware.org/?probe=e68917ee9f) | Nov 04, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| antiX 21       | 3        | 30%     |
| antiX 19.2     | 2        | 20%     |
| antiX 17.4.1   | 2        | 20%     |
| antiX 21-runit | 1        | 10%     |
| antiX 17.1     | 1        | 10%     |
| antiX 15       | 1        | 10%     |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| antiX | 10       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 4.9.160-antix.2-486-smp     | 2        | 20%     |
| 4.9.0-279-antix.1-amd64-smp | 2        | 20%     |
| 5.10.88-antix.1-amd64-smp   | 1        | 10%     |
| 5.10.57-antix.1-amd64-smp   | 1        | 10%     |
| 4.9.87-antix.1-amd64-smp    | 1        | 10%     |
| 4.9.212-antix.1-amd64-smp   | 1        | 10%     |
| 4.9.212-antix.1-486-smp     | 1        | 10%     |
| 4.9.0-279-antix.1-486-smp   | 1        | 10%     |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.9.0   | 3        | 30%     |
| 4.9.212 | 2        | 20%     |
| 4.9.160 | 2        | 20%     |
| 5.10.88 | 1        | 10%     |
| 5.10.57 | 1        | 10%     |
| 4.9.87  | 1        | 10%     |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.9     | 8        | 80%     |
| 5.10    | 2        | 20%     |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 6        | 60%     |
| i686   | 4        | 40%     |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Unknown      | 5        | 50%     |
| icewm        | 2        | 20%     |
| XFCE         | 1        | 10%     |
| jwm          | 1        | 10%     |
| herbstluftwm | 1        | 10%     |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 9        | 90%     |
| Tty  | 1        | 10%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SLiM    | 5        | 50%     |
| Unknown | 3        | 30%     |
| SLIMSKI | 1        | 10%     |
| LightDM | 1        | 10%     |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 4        | 40%     |
| Unknown | 3        | 30%     |
| pl_PL   | 2        | 20%     |
| sk_SK   | 1        | 10%     |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 9        | 90%     |
| EFI  | 1        | 10%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 8        | 80%     |
| Overlay | 2        | 20%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 9        | 90%     |
| Unknown | 1        | 10%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 7        | 70%     |
| Yes       | 3        | 30%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 8        | 80%     |
| Yes       | 2        | 20%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 3        | 30%     |
| Gigabyte Technology | 2        | 20%     |
| ASUSTek Computer    | 2        | 20%     |
| MSI                 | 1        | 10%     |
| Lenovo              | 1        | 10%     |
| Hewlett-Packard     | 1        | 10%     |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 3        | 30%     |
| MSI US Desktop                  | 1        | 10%     |
| Lenovo ThinkCentre M91p 4480B9U | 1        | 10%     |
| HP t5740                        | 1        | 10%     |
| Gigabyte F2A85XM-D3H            | 1        | 10%     |
| Gigabyte 945GCMX-S2             | 1        | 10%     |
| ASUS P5KPL/1600                 | 1        | 10%     |
| ASUS A8R-MVP                    | 1        | 10%     |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Unknown              | 3        | 30%     |
| MSI US               | 1        | 10%     |
| Lenovo ThinkCentre   | 1        | 10%     |
| HP t5740             | 1        | 10%     |
| Gigabyte F2A85XM-D3H | 1        | 10%     |
| Gigabyte 945GCMX-S2  | 1        | 10%     |
| ASUS P5KPL           | 1        | 10%     |
| ASUS A8R-MVP         | 1        | 10%     |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2008    | 2        | 20%     |
| 2007    | 2        | 20%     |
| 2021    | 1        | 10%     |
| 2012    | 1        | 10%     |
| 2011    | 1        | 10%     |
| 2009    | 1        | 10%     |
| 2005    | 1        | 10%     |
| Unknown | 1        | 10%     |

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


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 2        | 20%     |
| 1.01-2.0   | 2        | 20%     |
| 4.01-8.0   | 1        | 10%     |
| 32.01-64.0 | 1        | 10%     |
| 3.01-4.0   | 1        | 10%     |
| 16.01-24.0 | 1        | 10%     |
| 0.51-1.0   | 1        | 10%     |
| 0.01-0.5   | 1        | 10%     |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 5        | 50%     |
| 1.01-2.0 | 2        | 20%     |
| 4.01-8.0 | 1        | 10%     |
| 2.01-3.0 | 1        | 10%     |
| 0.51-1.0 | 1        | 10%     |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 6        | 60%     |
| 3      | 2        | 20%     |
| 2      | 1        | 10%     |
| 0      | 1        | 10%     |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 6        | 60%     |
| No        | 4        | 40%     |

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
| No        | 8        | 80%     |
| Yes       | 2        | 20%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 90%     |
| Yes       | 1        | 10%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| USA      | 3        | 30%     |
| Poland   | 2        | 20%     |
| Slovakia | 1        | 10%     |
| Russia   | 1        | 10%     |
| Greece   | 1        | 10%     |
| Germany  | 1        | 10%     |
| France   | 1        | 10%     |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Zagnansk          | 1        | 10%     |
| Violes            | 1        | 10%     |
| Otwock            | 1        | 10%     |
| Mason             | 1        | 10%     |
| Kazan’          | 1        | 10%     |
| Houston           | 1        | 10%     |
| Heraklion         | 1        | 10%     |
| Frankfurt am Main | 1        | 10%     |
| Bratislava        | 1        | 10%     |
| Boulder           | 1        | 10%     |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 3      | 25%     |
| Seagate             | 3        | 3      | 25%     |
| Samsung Electronics | 3        | 4      | 25%     |
| Unknown             | 1        | 1      | 8.33%   |
| SanDisk             | 1        | 1      | 8.33%   |
| Hitachi             | 1        | 2      | 8.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| WDC WD800JB-00ETA0 80GB         | 1        | 7.69%   |
| WDC WD205BA 21GB                | 1        | 7.69%   |
| WDC WD1600AAJS-00PSA0 160GB     | 1        | 7.69%   |
| Unknown 2GB ATA Flash Disk      | 1        | 7.69%   |
| Seagate ST500DM002-1BD142 500GB | 1        | 7.69%   |
| Seagate ST3320620AS 320GB       | 1        | 7.69%   |
| Seagate ST3320413CS 320GB       | 1        | 7.69%   |
| SanDisk sandisk120 120GB SSD    | 1        | 7.69%   |
| Samsung SSD 850 EVO 120GB       | 1        | 7.69%   |
| Samsung HD250HJ 250GB           | 1        | 7.69%   |
| Samsung HD160JJ 160GB           | 1        | 7.69%   |
| Samsung HD080HJ/ 80GB           | 1        | 7.69%   |
| Hitachi HTS723232A7A364 320GB   | 1        | 7.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 3      | 30%     |
| Seagate             | 3        | 3      | 30%     |
| Samsung Electronics | 2        | 3      | 20%     |
| Unknown             | 1        | 1      | 10%     |
| Hitachi             | 1        | 2      | 10%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SanDisk             | 1        | 1      | 50%     |
| Samsung Electronics | 1        | 1      | 50%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 8        | 12     | 80%     |
| SSD  | 2        | 2      | 20%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 9        | 14     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 9        | 14     | 100%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 4        | 40%     |
| 21-50      | 2        | 20%     |
| 1-20       | 2        | 20%     |
| 51-100     | 2        | 20%     |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 8        | 80%     |
| 21-50   | 1        | 10%     |
| 101-250 | 1        | 10%     |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD800JB-00ETA0 80GB         | 1        | 1      | 16.67%  |
| WDC WD205BA 21GB                | 1        | 1      | 16.67%  |
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 16.67%  |
| Seagate ST3320620AS 320GB       | 1        | 1      | 16.67%  |
| Seagate ST3320413CS 320GB       | 1        | 1      | 16.67%  |
| SanDisk sandisk120 120GB SSD    | 1        | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 50%     |
| WDC     | 2        | 2      | 33.33%  |
| SanDisk | 1        | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 60%     |
| WDC     | 2        | 2      | 40%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 5      | 83.33%  |
| SSD  | 1        | 1      | 16.67%  |

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
| Malfunc  | 6        | 6      | 60%     |
| Works    | 3        | 6      | 30%     |
| Detected | 1        | 2      | 10%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Intel              | 6        | 50%     |
| Nvidia             | 2        | 16.67%  |
| ASMedia Technology | 2        | 16.67%  |
| ULi Electronics    | 1        | 8.33%   |
| AMD                | 1        | 8.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 2        | 11.76%  |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 2        | 11.76%  |
| ASMedia ASM1062 Serial ATA Controller                                         | 2        | 11.76%  |
| ULi ULi M5288 SATA                                                            | 1        | 5.88%   |
| ULi M5229 IDE                                                                 | 1        | 5.88%   |
| Nvidia nForce3 Serial ATA Controller                                          | 1        | 5.88%   |
| Nvidia CK8S Parallel ATA Controller (v2.5)                                    | 1        | 5.88%   |
| Nvidia CK804 Serial ATA Controller                                            | 1        | 5.88%   |
| Nvidia CK804 IDE                                                              | 1        | 5.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]          | 1        | 5.88%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                 | 1        | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 1        | 5.88%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 1        | 5.88%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 1        | 5.88%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 7        | 58.33%  |
| SATA | 5        | 41.67%  |

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


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Intel Xeon CPU L5410 @ 2.33GHz             | 1        | 10%     |
| Intel Pentium II (Deschutes)               | 1        | 10%     |
| Intel Pentium Dual CPU E2180 @ 2.00GHz     | 1        | 10%     |
| Intel Core i5-2400 CPU @ 3.10GHz           | 1        | 10%     |
| Intel Atom CPU N280 @ 1.66GHz              | 1        | 10%     |
| Intel 11th Gen Core i5-11400F @ 2.60GHz    | 1        | 10%     |
| AMD Sempron Processor 3000+                | 1        | 10%     |
| AMD Athlon 64 X2 Dual Core Processor 4600+ | 1        | 10%     |
| AMD Athlon 64 Processor 3200+              | 1        | 10%     |
| AMD A6-5400K APU with Radeon HD Graphics   | 1        | 10%     |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Other              | 1        | 10%     |
| Intel Xeon         | 1        | 10%     |
| Intel Pentium Dual | 1        | 10%     |
| Intel Pentium      | 1        | 10%     |
| Intel Core i5      | 1        | 10%     |
| Intel Atom         | 1        | 10%     |
| AMD Sempron        | 1        | 10%     |
| AMD Athlon 64 X2   | 1        | 10%     |
| AMD Athlon 64      | 1        | 10%     |
| AMD A6             | 1        | 10%     |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 5        | 50%     |
| 4      | 2        | 20%     |
| 2      | 2        | 20%     |
| 6      | 1        | 10%     |

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
| 1      | 7        | 70%     |
| 2      | 3        | 30%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 8        | 80%     |
| 32-bit         | 2        | 20%     |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 3        | 30%     |
| 0xa0671    | 1        | 10%     |
| 0x6fd      | 1        | 10%     |
| 0x652      | 1        | 10%     |
| 0x206a7    | 1        | 10%     |
| 0x106c2    | 1        | 10%     |
| 0x10676    | 1        | 10%     |
| 0x06001116 | 1        | 10%     |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| K8 Hammer   | 3        | 30%     |
| Unknown     | 2        | 20%     |
| SandyBridge | 1        | 10%     |
| Piledriver  | 1        | 10%     |
| Penryn      | 1        | 10%     |
| Core        | 1        | 10%     |
| Bonnell     | 1        | 10%     |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 4        | 40%     |
| Nvidia | 3        | 30%     |
| Intel  | 3        | 30%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 1        | 7.69%   |
| Nvidia GF108 [GeForce GT 630]                                             | 1        | 7.69%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                       | 1        | 7.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1        | 7.69%   |
| Intel 82945G/GZ Integrated Graphics Controller                            | 1        | 7.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1        | 7.69%   |
| AMD RV516 [Radeon X1300/X1550 Series] (Secondary)                         | 1        | 7.69%   |
| AMD RV516 [Radeon X1300/X1550 Series]                                     | 1        | 7.69%   |
| AMD RV515 [Radeon X1300/X1550]                                            | 1        | 7.69%   |
| AMD RV515 [Radeon X1300/X1550 Series] (Secondary)                         | 1        | 7.69%   |
| AMD RV280 [Radeon 9200 PRO] (Secondary)                                   | 1        | 7.69%   |
| AMD RV280 [Radeon 9200 PRO / 9250]                                        | 1        | 7.69%   |
| AMD Rage 3 [3D Rage PRO AGP 2X]                                           | 1        | 7.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 2 x AMD    | 3        | 30%     |
| 1 x Nvidia | 3        | 30%     |
| 1 x Intel  | 3        | 30%     |
| 1 x AMD    | 1        | 10%     |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 6        | 60%     |
| Unknown     | 3        | 30%     |
| Proprietary | 1        | 10%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 4        | 40%     |
| Unknown    | 4        | 40%     |
| 1.01-2.0   | 2        | 20%     |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Acer                | 3        | 60%     |
| Vizio               | 1        | 20%     |
| Samsung Electronics | 1        | 20%     |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Vizio E28h-C1 VIZ1002 1360x768 610x350mm 27.7-inch                   | 1        | 20%     |
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch | 1        | 20%     |
| Acer VG220Q ACR06D8 1920x1080 476x268mm 21.5-inch                    | 1        | 20%     |
| Acer V243H ACR00A3 1920x1080 530x290mm 23.8-inch                     | 1        | 20%     |
| Acer S271HL ACR02CA 1920x1080 598x336mm 27.0-inch                    | 1        | 20%     |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Desktops | Percent |
|-----------------|----------|---------|
| 1920x1080 (FHD) | 3        | 60%     |
| 1600x1200       | 1        | 20%     |
| 1366x768 (WXGA) | 1        | 20%     |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 21     | 2        | 40%     |
| 38     | 1        | 20%     |
| 27     | 1        | 20%     |
| 24     | 1        | 20%     |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 2        | 40%     |
| 401-500     | 2        | 40%     |
| 801-900     | 1        | 20%     |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 4        | 80%     |
| 4/3   | 1        | 20%     |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 3        | 60%     |
| 301-350        | 1        | 20%     |
| 501-1000       | 1        | 20%     |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 3        | 60%     |
| 1-50    | 1        | 20%     |
| 101-120 | 1        | 20%     |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 6        | 60%     |
| 0     | 4        | 40%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 7        | 46.67%  |
| Nvidia                          | 2        | 13.33%  |
| Intel                           | 2        | 13.33%  |
| Qualcomm Atheros Communications | 1        | 6.67%   |
| Marvell Technology Group        | 1        | 6.67%   |
| LSI                             | 1        | 6.67%   |
| Broadcom                        | 1        | 6.67%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 2        | 12.5%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 12.5%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 1        | 6.25%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 6.25%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 6.25%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1        | 6.25%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 6.25%   |
| Nvidia CK8S Ethernet Controller                                               | 1        | 6.25%   |
| Nvidia CK804 Ethernet Controller                                              | 1        | 6.25%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 1        | 6.25%   |
| LSI 56k WinModem                                                              | 1        | 6.25%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1        | 6.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 1        | 6.25%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 1        | 6.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 1        | 33.33%  |
| Qualcomm Atheros Communications | 1        | 33.33%  |
| Intel                           | 1        | 33.33%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 1        | 33.33%  |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 33.33%  |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1        | 33.33%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 7        | 58.33%  |
| Nvidia                   | 2        | 16.67%  |
| Marvell Technology Group | 1        | 8.33%   |
| Intel                    | 1        | 8.33%   |
| Broadcom                 | 1        | 8.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 16.67%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 16.67%  |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 8.33%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 8.33%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1        | 8.33%   |
| Nvidia CK8S Ethernet Controller                                   | 1        | 8.33%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 8.33%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 8.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 8.33%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 8.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 10       | 76.92%  |
| WiFi     | 2        | 15.38%  |
| Modem    | 1        | 7.69%   |

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
| 2     | 3        | 30%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 10       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1        | 100%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Bluetooth Device | 1        | 100%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 4        | 30.77%  |
| Nvidia              | 3        | 23.08%  |
| Creative Labs       | 2        | 15.38%  |
| ULi Electronics     | 1        | 7.69%   |
| Ensoniq             | 1        | 7.69%   |
| C-Media Electronics | 1        | 7.69%   |
| AMD                 | 1        | 7.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| ULi Electronics HD Audio Controller                                        | 1        | 7.69%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 7.69%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 7.69%   |
| Nvidia CK804 AC'97 Audio Controller                                        | 1        | 7.69%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 7.69%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 7.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 7.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 7.69%   |
| Ensoniq ES1371/ES1373 / Creative Labs CT2518                               | 1        | 7.69%   |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                          | 1        | 7.69%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1        | 7.69%   |
| C-Media Electronics CM6501                                                 | 1        | 7.69%   |
| AMD FCH Azalia Controller                                                  | 1        | 7.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 5        | 50%     |
| Kingston            | 2        | 20%     |
| Samsung Electronics | 1        | 10%     |
| Patriot             | 1        | 10%     |
| Corsair             | 1        | 10%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 512MB DIMM DDR 400MT/s              | 1        | 9.09%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s              | 1        | 9.09%   |
| Unknown RAM Module 512MB DIMM                          | 1        | 9.09%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                | 1        | 9.09%   |
| Unknown RAM Module 1GB DIMM 667MT/s                    | 1        | 9.09%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s            | 1        | 9.09%   |
| Samsung RAM M378B5673FH0 2GB DIMM DDR3 667MT/s         | 1        | 9.09%   |
| Patriot RAM PSD34G1600L2S 4GB SODIMM DDR3 1600MT/s     | 1        | 9.09%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s  | 1        | 9.09%   |
| Kingston RAM 99U5402-060.A 2GB DIMM DDR3 1333MT/s      | 1        | 9.09%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s | 1        | 9.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 3        | 33.33%  |
| DDR     | 2        | 22.22%  |
| Unknown | 2        | 22.22%  |
| DDR4    | 1        | 11.11%  |
| DDR2    | 1        | 11.11%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 8        | 88.89%  |
| SODIMM | 1        | 11.11%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 1024  | 3        | 30%     |
| 512   | 3        | 30%     |
| 4096  | 2        | 20%     |
| 16384 | 1        | 10%     |
| 2048  | 1        | 10%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 667     | 3        | 30%     |
| 1600    | 2        | 20%     |
| 3200    | 1        | 10%     |
| 1333    | 1        | 10%     |
| 400     | 1        | 10%     |
| 333     | 1        | 10%     |
| Unknown | 1        | 10%     |

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
| 0     | 7        | 70%     |
| 2     | 2        | 20%     |
| 3     | 1        | 10%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 3        | 42.86%  |
| Communication controller | 2        | 28.57%  |
| Net/ethernet             | 1        | 14.29%  |
| Modem                    | 1        | 14.29%  |

