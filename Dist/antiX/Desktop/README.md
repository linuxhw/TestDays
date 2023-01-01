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

Total: 16

| Vendor   | Model                    | Probe                                                      | Date         |
|----------|--------------------------|------------------------------------------------------------|--------------|
| Intel    | D525MW AAE93082-401      | [a225baa8a4](https://linux-hardware.org/?probe=a225baa8a4) | Aug 05, 2022 |
| Biostar  | G31-M7 TE                | [df98c1834c](https://linux-hardware.org/?probe=df98c1834c) | Jul 23, 2022 |
| Dell     | 0F428D A00               | [fb8a6009f7](https://linux-hardware.org/?probe=fb8a6009f7) | Jul 16, 2022 |
| MSI      | B560M PRO-VDH WIFI [CEC] | [af73739875](https://linux-hardware.org/?probe=af73739875) | Jul 14, 2022 |
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
| antiX 21       | 7        | 50%     |
| antiX 19.2     | 2        | 14.29%  |
| antiX 17.4.1   | 2        | 14.29%  |
| antiX 21-runit | 1        | 7.14%   |
| antiX 17.1     | 1        | 7.14%   |
| antiX 15       | 1        | 7.14%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| antiX | 14       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.10.57-antix.1-amd64-smp   | 4        | 28.57%  |
| 4.9.0-279-antix.1-amd64-smp | 3        | 21.43%  |
| 4.9.160-antix.2-486-smp     | 2        | 14.29%  |
| 5.10.88-antix.1-amd64-smp   | 1        | 7.14%   |
| 4.9.87-antix.1-amd64-smp    | 1        | 7.14%   |
| 4.9.212-antix.1-amd64-smp   | 1        | 7.14%   |
| 4.9.212-antix.1-486-smp     | 1        | 7.14%   |
| 4.9.0-279-antix.1-486-smp   | 1        | 7.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.57 | 4        | 28.57%  |
| 4.9.0   | 4        | 28.57%  |
| 4.9.212 | 2        | 14.29%  |
| 4.9.160 | 2        | 14.29%  |
| 5.10.88 | 1        | 7.14%   |
| 4.9.87  | 1        | 7.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.9     | 9        | 64.29%  |
| 5.10    | 5        | 35.71%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 10       | 71.43%  |
| i686   | 4        | 28.57%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Unknown      | 6        | 42.86%  |
| icewm        | 5        | 35.71%  |
| XFCE         | 1        | 7.14%   |
| jwm          | 1        | 7.14%   |
| herbstluftwm | 1        | 7.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 13       | 92.86%  |
| Tty  | 1        | 7.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 6        | 42.86%  |
| SLiM    | 5        | 35.71%  |
| SLIMSKI | 2        | 14.29%  |
| LightDM | 1        | 7.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 5        | 35.71%  |
| Unknown | 3        | 21.43%  |
| pl_PL   | 2        | 14.29%  |
| sk_SK   | 1        | 7.14%   |
| pt_BR   | 1        | 7.14%   |
| es_AR   | 1        | 7.14%   |
| en_GB   | 1        | 7.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 12       | 85.71%  |
| EFI  | 2        | 14.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 12       | 85.71%  |
| Overlay | 2        | 14.29%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 11       | 78.57%  |
| GPT     | 2        | 14.29%  |
| Unknown | 1        | 7.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 71.43%  |
| Yes       | 4        | 28.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 71.43%  |
| Yes       | 4        | 28.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 3        | 21.43%  |
| MSI                 | 2        | 14.29%  |
| Gigabyte Technology | 2        | 14.29%  |
| ASUSTek Computer    | 2        | 14.29%  |
| Lenovo              | 1        | 7.14%   |
| Intel               | 1        | 7.14%   |
| Hewlett-Packard     | 1        | 7.14%   |
| Dell                | 1        | 7.14%   |
| Biostar             | 1        | 7.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 3        | 21.43%  |
| MSI US Desktop                  | 2        | 14.29%  |
| Lenovo ThinkCentre M91p 4480B9U | 1        | 7.14%   |
| Intel D525MW AAE93082-401       | 1        | 7.14%   |
| HP t5740                        | 1        | 7.14%   |
| Gigabyte F2A85XM-D3H            | 1        | 7.14%   |
| Gigabyte 945GCMX-S2             | 1        | 7.14%   |
| Dell OptiPlex 960               | 1        | 7.14%   |
| Biostar G31-M7 TE               | 1        | 7.14%   |
| ASUS P5KPL/1600                 | 1        | 7.14%   |
| ASUS A8R-MVP                    | 1        | 7.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Unknown              | 3        | 21.43%  |
| MSI US               | 2        | 14.29%  |
| Lenovo ThinkCentre   | 1        | 7.14%   |
| Intel D525MW         | 1        | 7.14%   |
| HP t5740             | 1        | 7.14%   |
| Gigabyte F2A85XM-D3H | 1        | 7.14%   |
| Gigabyte 945GCMX-S2  | 1        | 7.14%   |
| Dell OptiPlex        | 1        | 7.14%   |
| Biostar G31-M7       | 1        | 7.14%   |
| ASUS P5KPL           | 1        | 7.14%   |
| ASUS A8R-MVP         | 1        | 7.14%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2008    | 3        | 21.43%  |
| 2021    | 2        | 14.29%  |
| 2011    | 2        | 14.29%  |
| 2009    | 2        | 14.29%  |
| 2007    | 2        | 14.29%  |
| 2012    | 1        | 7.14%   |
| 2005    | 1        | 7.14%   |
| Unknown | 1        | 7.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 14       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 14       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 14       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 3        | 21.43%  |
| 4.01-8.0   | 2        | 14.29%  |
| 32.01-64.0 | 2        | 14.29%  |
| 3.01-4.0   | 2        | 14.29%  |
| 2.01-3.0   | 2        | 14.29%  |
| 16.01-24.0 | 1        | 7.14%   |
| 0.51-1.0   | 1        | 7.14%   |
| 0.01-0.5   | 1        | 7.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.51-1.0 | 5        | 35.71%  |
| 0.01-0.5 | 5        | 35.71%  |
| 1.01-2.0 | 2        | 14.29%  |
| 4.01-8.0 | 1        | 7.14%   |
| 2.01-3.0 | 1        | 7.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 8        | 57.14%  |
| 3      | 3        | 21.43%  |
| 4      | 1        | 7.14%   |
| 2      | 1        | 7.14%   |
| 0      | 1        | 7.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 8        | 57.14%  |
| Yes       | 6        | 42.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 14       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 71.43%  |
| Yes       | 4        | 28.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 78.57%  |
| Yes       | 3        | 21.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 4        | 28.57%  |
| Poland    | 2        | 14.29%  |
| UK        | 1        | 7.14%   |
| Slovakia  | 1        | 7.14%   |
| Russia    | 1        | 7.14%   |
| Greece    | 1        | 7.14%   |
| Germany   | 1        | 7.14%   |
| France    | 1        | 7.14%   |
| Brazil    | 1        | 7.14%   |
| Argentina | 1        | 7.14%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Zagnansk          | 1        | 7.14%   |
| Violes            | 1        | 7.14%   |
| Otwock            | 1        | 7.14%   |
| Nova Londrina     | 1        | 7.14%   |
| Mason             | 1        | 7.14%   |
| Maidstone         | 1        | 7.14%   |
| Kazan’          | 1        | 7.14%   |
| Houston           | 1        | 7.14%   |
| Heraklion         | 1        | 7.14%   |
| Frankfurt am Main | 1        | 7.14%   |
| Covington         | 1        | 7.14%   |
| Buenos Aires      | 1        | 7.14%   |
| Bratislava        | 1        | 7.14%   |
| Boulder           | 1        | 7.14%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 6      | 25%     |
| Seagate             | 4        | 4      | 20%     |
| Samsung Electronics | 4        | 5      | 20%     |
| Unknown             | 1        | 1      | 5%      |
| Toshiba             | 1        | 1      | 5%      |
| SanDisk             | 1        | 1      | 5%      |
| Maxtor              | 1        | 1      | 5%      |
| Hitachi             | 1        | 2      | 5%      |
| Crucial             | 1        | 1      | 5%      |
| BHT                 | 1        | 1      | 5%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| WDC WD800JB-00ETA0 80GB           | 1        | 4.55%   |
| WDC WD800AAJS-75M0A0 80GB         | 1        | 4.55%   |
| WDC WD205BA 21GB                  | 1        | 4.55%   |
| WDC WD2003FZEX-00Z4SA0 2TB        | 1        | 4.55%   |
| WDC WD1600AAJS-00PSA0 160GB       | 1        | 4.55%   |
| WDC WD10SPZX-80Z10T2 1TB          | 1        | 4.55%   |
| Unknown 2GB ATA Flash Disk        | 1        | 4.55%   |
| Toshiba MQ01ABD050V -63 500GB     | 1        | 4.55%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 4.55%   |
| Seagate ST3320620AS 320GB         | 1        | 4.55%   |
| Seagate ST3320413CS 320GB         | 1        | 4.55%   |
| Seagate ST1000DM010-2EP102 1TB    | 1        | 4.55%   |
| SanDisk sandisk120 120GB SSD      | 1        | 4.55%   |
| Samsung SSD 850 EVO 120GB         | 1        | 4.55%   |
| Samsung HD250HJ 250GB             | 1        | 4.55%   |
| Samsung HD162GJ 160GB             | 1        | 4.55%   |
| Samsung HD160JJ/ 160GB            | 1        | 4.55%   |
| Samsung HD080HJ/ 80GB             | 1        | 4.55%   |
| Maxtor Z1 SSD 240GB               | 1        | 4.55%   |
| Hitachi HTS723232A7A364 320GB     | 1        | 4.55%   |
| Crucial CT500MX500SSD1 500GB      | 1        | 4.55%   |
| BHT WR202F0032G 670270F5 32GB SSD | 1        | 4.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 6      | 33.33%  |
| Seagate             | 4        | 4      | 26.67%  |
| Samsung Electronics | 3        | 4      | 20%     |
| Unknown             | 1        | 1      | 6.67%   |
| Toshiba             | 1        | 1      | 6.67%   |
| Hitachi             | 1        | 2      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SanDisk             | 1        | 1      | 20%     |
| Samsung Electronics | 1        | 1      | 20%     |
| Maxtor              | 1        | 1      | 20%     |
| Crucial             | 1        | 1      | 20%     |
| BHT                 | 1        | 1      | 20%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 11       | 18     | 68.75%  |
| SSD  | 5        | 5      | 31.25%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 13       | 23     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 13       | 20     | 81.25%  |
| 0.51-1.0   | 2        | 2      | 12.5%   |
| 1.01-2.0   | 1        | 1      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 5        | 35.71%  |
| 21-50      | 2        | 14.29%  |
| 1-20       | 2        | 14.29%  |
| 51-100     | 2        | 14.29%  |
| 251-500    | 1        | 7.14%   |
| 1001-2000  | 1        | 7.14%   |
| 501-1000   | 1        | 7.14%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 11       | 78.57%  |
| 21-50    | 1        | 7.14%   |
| 101-250  | 1        | 7.14%   |
| 501-1000 | 1        | 7.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD800JB-00ETA0 80GB         | 1        | 1      | 14.29%  |
| WDC WD800AAJS-75M0A0 80GB       | 1        | 1      | 14.29%  |
| WDC WD205BA 21GB                | 1        | 1      | 14.29%  |
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 14.29%  |
| Seagate ST3320620AS 320GB       | 1        | 1      | 14.29%  |
| Seagate ST3320413CS 320GB       | 1        | 1      | 14.29%  |
| SanDisk sandisk120 120GB SSD    | 1        | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 42.86%  |
| Seagate | 3        | 3      | 42.86%  |
| SanDisk | 1        | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 50%     |
| Seagate | 3        | 3      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 6        | 6      | 85.71%  |
| SSD  | 1        | 1      | 14.29%  |

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
| Malfunc  | 7        | 7      | 43.75%  |
| Works    | 7        | 13     | 43.75%  |
| Detected | 2        | 3      | 12.5%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Intel              | 10       | 58.82%  |
| ASMedia Technology | 3        | 17.65%  |
| Nvidia             | 2        | 11.76%  |
| ULi Electronics    | 1        | 5.88%   |
| AMD                | 1        | 5.88%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 3        | 12.5%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 3        | 12.5%   |
| ASMedia ASM1062 Serial ATA Controller                                         | 3        | 12.5%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 2        | 8.33%   |
| ULi ULi M5288 SATA                                                            | 1        | 4.17%   |
| ULi M5229 IDE                                                                 | 1        | 4.17%   |
| Nvidia nForce3 Serial ATA Controller                                          | 1        | 4.17%   |
| Nvidia CK8S Parallel ATA Controller (v2.5)                                    | 1        | 4.17%   |
| Nvidia CK804 Serial ATA Controller                                            | 1        | 4.17%   |
| Nvidia CK804 IDE                                                              | 1        | 4.17%   |
| Intel SATA Controller [RAID mode]                                             | 1        | 4.17%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 1        | 4.17%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]          | 1        | 4.17%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                 | 1        | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 1        | 4.17%   |
| Intel 4 Series Chipset PT IDER Controller                                     | 1        | 4.17%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 1        | 4.17%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 9        | 52.94%  |
| SATA | 7        | 41.18%  |
| RAID | 1        | 5.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 10       | 71.43%  |
| AMD    | 4        | 28.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel 11th Gen Core i5-11400F @ 2.60GHz     | 2        | 14.29%  |
| Intel Xeon CPU L5410 @ 2.33GHz              | 1        | 7.14%   |
| Intel Pentium II (Deschutes)                | 1        | 7.14%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 7.14%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 7.14%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 7.14%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 7.14%   |
| Intel Atom CPU N280 @ 1.66GHz               | 1        | 7.14%   |
| Intel Atom CPU D525 @ 1.80GHz               | 1        | 7.14%   |
| AMD Sempron Processor 3000+                 | 1        | 7.14%   |
| AMD Athlon 64 X2 Dual Core Processor 4600+  | 1        | 7.14%   |
| AMD Athlon 64 Processor 3200+               | 1        | 7.14%   |
| AMD A6-5400K APU with Radeon HD Graphics    | 1        | 7.14%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Other                   | 2        | 14.29%  |
| Intel Atom              | 2        | 14.29%  |
| Intel Xeon              | 1        | 7.14%   |
| Intel Pentium Dual-Core | 1        | 7.14%   |
| Intel Pentium Dual      | 1        | 7.14%   |
| Intel Pentium           | 1        | 7.14%   |
| Intel Core i5           | 1        | 7.14%   |
| Intel Core 2 Quad       | 1        | 7.14%   |
| AMD Sempron             | 1        | 7.14%   |
| AMD Athlon 64 X2        | 1        | 7.14%   |
| AMD Athlon 64           | 1        | 7.14%   |
| AMD A6                  | 1        | 7.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 5        | 35.71%  |
| 2      | 4        | 28.57%  |
| 4      | 3        | 21.43%  |
| 6      | 2        | 14.29%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 14       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 9        | 64.29%  |
| 2      | 5        | 35.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 12       | 85.71%  |
| 32-bit         | 2        | 14.29%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 3        | 21.43%  |
| 0xa0671    | 2        | 14.29%  |
| 0x1067a    | 2        | 14.29%  |
| 0x6fd      | 1        | 7.14%   |
| 0x652      | 1        | 7.14%   |
| 0x206a7    | 1        | 7.14%   |
| 0x106ca    | 1        | 7.14%   |
| 0x106c2    | 1        | 7.14%   |
| 0x10676    | 1        | 7.14%   |
| 0x06001116 | 1        | 7.14%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Penryn      | 3        | 21.43%  |
| K8 Hammer   | 3        | 21.43%  |
| Unknown     | 3        | 21.43%  |
| Bonnell     | 2        | 14.29%  |
| SandyBridge | 1        | 7.14%   |
| Piledriver  | 1        | 7.14%   |
| Core        | 1        | 7.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 5        | 35.71%  |
| AMD    | 5        | 35.71%  |
| Intel  | 4        | 28.57%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 2        | 11.76%  |
| Nvidia GF119 [GeForce GT 520]                                             | 1        | 5.88%   |
| Nvidia GF108 [GeForce GT 630]                                             | 1        | 5.88%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                       | 1        | 5.88%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1        | 5.88%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 1        | 5.88%   |
| Intel 82945G/GZ Integrated Graphics Controller                            | 1        | 5.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1        | 5.88%   |
| AMD RV516 [Radeon X1300/X1550 Series] (Secondary)                         | 1        | 5.88%   |
| AMD RV516 [Radeon X1300/X1550 Series]                                     | 1        | 5.88%   |
| AMD RV515 [Radeon X1300/X1550]                                            | 1        | 5.88%   |
| AMD RV515 [Radeon X1300/X1550 Series] (Secondary)                         | 1        | 5.88%   |
| AMD RV280 [Radeon 9200 PRO] (Secondary)                                   | 1        | 5.88%   |
| AMD RV280 [Radeon 9200 PRO / 9250]                                        | 1        | 5.88%   |
| AMD Rage 3 [3D Rage PRO AGP 2X]                                           | 1        | 5.88%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                          | 1        | 5.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 5        | 35.71%  |
| 1 x Intel  | 4        | 28.57%  |
| 2 x AMD    | 3        | 21.43%  |
| 1 x AMD    | 2        | 14.29%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 9        | 64.29%  |
| Unknown     | 3        | 21.43%  |
| Proprietary | 2        | 14.29%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 5        | 35.71%  |
| Unknown    | 5        | 35.71%  |
| 1.01-2.0   | 2        | 14.29%  |
| 5.01-6.0   | 1        | 7.14%   |
| 0.51-1.0   | 1        | 7.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Acer                | 3        | 37.5%   |
| Goldstar            | 2        | 25%     |
| Vizio               | 1        | 12.5%   |
| Samsung Electronics | 1        | 12.5%   |
| Dell                | 1        | 12.5%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Vizio E280i-B1 VIZ1002 1360x768 607x345mm 27.5-inch                  | 1        | 12.5%   |
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch | 1        | 12.5%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch             | 1        | 12.5%   |
| Goldstar M198WA GSM4B36 1440x900 410x260mm 19.1-inch                 | 1        | 12.5%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                     | 1        | 12.5%   |
| Acer VG220Q ACR06D8 1920x1080 476x268mm 21.5-inch                    | 1        | 12.5%   |
| Acer V243H ACR00A3 1920x1080 531x298mm 24.0-inch                     | 1        | 12.5%   |
| Acer S271HL ACR02CA 1920x1080 598x336mm 27.0-inch                    | 1        | 12.5%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 3        | 37.5%   |
| 1366x768 (WXGA)  | 2        | 25%     |
| 2560x1080        | 1        | 12.5%   |
| 1600x1200        | 1        | 12.5%   |
| 1440x900 (WXGA+) | 1        | 12.5%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 21     | 2        | 25%     |
| 38     | 1        | 12.5%   |
| 34     | 1        | 12.5%   |
| 27     | 1        | 12.5%   |
| 24     | 1        | 12.5%   |
| 19     | 1        | 12.5%   |
| 18     | 1        | 12.5%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 4        | 50%     |
| 501-600     | 2        | 25%     |
| 801-900     | 1        | 12.5%   |
| 701-800     | 1        | 12.5%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 5        | 62.5%   |
| 4/3   | 1        | 12.5%   |
| 21/9  | 1        | 12.5%   |
| 16/10 | 1        | 12.5%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 3        | 37.5%   |
| 351-500        | 1        | 12.5%   |
| 301-350        | 1        | 12.5%   |
| 151-200        | 1        | 12.5%   |
| 141-150        | 1        | 12.5%   |
| 501-1000       | 1        | 12.5%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 6        | 75%     |
| 1-50    | 1        | 12.5%   |
| 101-120 | 1        | 12.5%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10       | 71.43%  |
| 0     | 4        | 28.57%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 10       | 47.62%  |
| Intel                           | 4        | 19.05%  |
| Nvidia                          | 2        | 9.52%   |
| Ralink Technology               | 1        | 4.76%   |
| Qualcomm Atheros Communications | 1        | 4.76%   |
| Marvell Technology Group        | 1        | 4.76%   |
| LSI                             | 1        | 4.76%   |
| Broadcom                        | 1        | 4.76%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2        | 8.7%    |
| Realtek RTL8125 2.5GbE Controller                                             | 2        | 8.7%    |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 2        | 8.7%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 2        | 8.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 8.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2        | 8.7%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 4.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1        | 4.35%   |
| Ralink RT5370 Wireless Adapter                                                | 1        | 4.35%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 4.35%   |
| Nvidia CK8S Ethernet Controller                                               | 1        | 4.35%   |
| Nvidia CK804 Ethernet Controller                                              | 1        | 4.35%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 1        | 4.35%   |
| LSI 56k WinModem                                                              | 1        | 4.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 1        | 4.35%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 4.35%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 1        | 4.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 2        | 33.33%  |
| Intel                           | 2        | 33.33%  |
| Ralink Technology               | 1        | 16.67%  |
| Qualcomm Atheros Communications | 1        | 16.67%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2        | 33.33%  |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2        | 33.33%  |
| Ralink RT5370 Wireless Adapter                                                | 1        | 16.67%  |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 16.67%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 10       | 62.5%   |
| Nvidia                   | 2        | 12.5%   |
| Intel                    | 2        | 12.5%   |
| Marvell Technology Group | 1        | 6.25%   |
| Broadcom                 | 1        | 6.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 12.5%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2        | 12.5%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 12.5%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 12.5%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 6.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 6.25%   |
| Nvidia CK8S Ethernet Controller                                   | 1        | 6.25%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 6.25%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 6.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 6.25%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 6.25%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 6.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 14       | 73.68%  |
| WiFi     | 4        | 21.05%  |
| Modem    | 1        | 5.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 12       | 75%     |
| WiFi     | 4        | 25%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10       | 71.43%  |
| 2     | 4        | 28.57%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 14       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 2        | 66.67%  |
| Cambridge Silicon Radio | 1        | 33.33%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX201 Bluetooth                               | 2        | 66.67%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 33.33%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 8        | 40%     |
| Nvidia              | 5        | 25%     |
| Creative Labs       | 2        | 10%     |
| AMD                 | 2        | 10%     |
| ULi Electronics     | 1        | 5%      |
| Ensoniq             | 1        | 5%      |
| C-Media Electronics | 1        | 5%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 15%     |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 10%     |
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 10%     |
| ULi Electronics HD Audio Controller                                        | 1        | 5%      |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 5%      |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 5%      |
| Nvidia CK804 AC'97 Audio Controller                                        | 1        | 5%      |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 5%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 5%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 5%      |
| Ensoniq ES1371/ES1373 / Creative Labs CT2518                               | 1        | 5%      |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                          | 1        | 5%      |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1        | 5%      |
| C-Media Electronics CM6501                                                 | 1        | 5%      |
| AMD FCH Azalia Controller                                                  | 1        | 5%      |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 5%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 7        | 46.67%  |
| Kingston            | 2        | 13.33%  |
| Corsair             | 2        | 13.33%  |
| Smart               | 1        | 6.67%   |
| Samsung Electronics | 1        | 6.67%   |
| Patriot             | 1        | 6.67%   |
| Kllisre             | 1        | 6.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Corsair RAM CMK32GX4M2E3200C16 16384MB DIMM DDR4 3200MT/s | 2        | 11.76%  |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                 | 1        | 5.88%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                 | 1        | 5.88%   |
| Unknown RAM Module 512MB DIMM                             | 1        | 5.88%   |
| Unknown RAM Module 2GB DIMM SDRAM                         | 1        | 5.88%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                  | 1        | 5.88%   |
| Unknown RAM Module 1GB DIMM SDRAM                         | 1        | 5.88%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                   | 1        | 5.88%   |
| Unknown RAM Module 1GB DIMM 667MT/s                       | 1        | 5.88%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s               | 1        | 5.88%   |
| Smart RAM SG564568FG8N6KFSQR 2GB DIMM DDR2 800MT/s        | 1        | 5.88%   |
| Samsung RAM M378B5673FH0 2GB DIMM DDR3 667MT/s            | 1        | 5.88%   |
| Patriot RAM PSD34G1600L2S 4GB SODIMM DDR3 1600MT/s        | 1        | 5.88%   |
| Kllisre RAM DDR2 2G 2GB DIMM DDR2 800MT/s                 | 1        | 5.88%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s     | 1        | 5.88%   |
| Kingston RAM 99U5402-060.A 2GB DIMM DDR3 1333MT/s         | 1        | 5.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 4        | 30.77%  |
| DDR4    | 2        | 15.38%  |
| DDR2    | 2        | 15.38%  |
| DDR     | 2        | 15.38%  |
| Unknown | 2        | 15.38%  |
| SDRAM   | 1        | 7.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 12       | 92.31%  |
| SODIMM | 1        | 7.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 4        | 26.67%  |
| 1024  | 4        | 26.67%  |
| 512   | 3        | 20%     |
| 16384 | 2        | 13.33%  |
| 4096  | 2        | 13.33%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 667     | 3        | 21.43%  |
| 3200    | 2        | 14.29%  |
| 1600    | 2        | 14.29%  |
| 800     | 2        | 14.29%  |
| Unknown | 2        | 14.29%  |
| 1333    | 1        | 7.14%   |
| 400     | 1        | 7.14%   |
| 333     | 1        | 7.14%   |

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
| 0     | 11       | 78.57%  |
| 2     | 2        | 14.29%  |
| 3     | 1        | 7.14%   |

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

