Kylin - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for Kylin.

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

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo    | ThinkPad X1 Extreme Gen ... | [80b6536a46](https://linux-hardware.org/?probe=80b6536a46) | Jun 28, 2023 |
| HUAWEI    | MACH-WX9                    | [016268562d](https://linux-hardware.org/?probe=016268562d) | Jun 21, 2023 |
| HUAWEI    | MACH-WX9                    | [25bc3b1533](https://linux-hardware.org/?probe=25bc3b1533) | Jun 21, 2023 |
| Dell      | Inspiron 5468               | [b16aeda09e](https://linux-hardware.org/?probe=b16aeda09e) | Jun 02, 2023 |
| Lenovo    | ThinkPad X200 74574AC       | [e770387a34](https://linux-hardware.org/?probe=e770387a34) | May 25, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop K550... | [cacfc4dacd](https://linux-hardware.org/?probe=cacfc4dacd) | May 16, 2023 |
| HP        | ZHAN 99 Mobile Workstati... | [3dcc7ab043](https://linux-hardware.org/?probe=3dcc7ab043) | Apr 12, 2023 |
| Lenovo    | Legion Y9000P IAH7H 82RF    | [30d91acf27](https://linux-hardware.org/?probe=30d91acf27) | Mar 07, 2023 |
| Lenovo    | Legion Y9000P IAH7H 82RF    | [97925534c2](https://linux-hardware.org/?probe=97925534c2) | Mar 02, 2023 |
| Lenovo    | ThinkPad X1 Carbon Gen 1... | [cc10e54ab9](https://linux-hardware.org/?probe=cc10e54ab9) | Feb 20, 2023 |
| Lenovo    | XiaoXinPro 14ACH 2021 82... | [29326a6340](https://linux-hardware.org/?probe=29326a6340) | Feb 11, 2023 |
| Lenovo    | ThinkPad T480s 20L7A00HH... | [801c1bad94](https://linux-hardware.org/?probe=801c1bad94) | Jan 02, 2023 |
| THTF      | CR F860-T1                  | [9f0a52783f](https://linux-hardware.org/?probe=9f0a52783f) | Oct 27, 2022 |
| HUAWEI    | L410 KLVU-WDU0              | [00edb23106](https://linux-hardware.org/?probe=00edb23106) | Oct 07, 2022 |
| GreatWall | Unknown                     | [12ee24a7c7](https://linux-hardware.org/?probe=12ee24a7c7) | Sep 20, 2022 |
| Timi      | TM1612                      | [fe85c2d733](https://linux-hardware.org/?probe=fe85c2d733) | Feb 05, 2022 |
| Lenovo    | ThinkPad X13 Gen 1 20T2A... | [0c261084db](https://linux-hardware.org/?probe=0c261084db) | Oct 16, 2021 |
| HP        | EliteBook 840 G7 Noteboo... | [ebe2901cc8](https://linux-hardware.org/?probe=ebe2901cc8) | Apr 30, 2021 |
| Lenovo    | IdeaPad 710S-13ISK 80SW     | [55b2402c28](https://linux-hardware.org/?probe=55b2402c28) | Feb 25, 2021 |
| Lenovo    | IdeaPad 710S-13ISK 80SW     | [44013b0bb4](https://linux-hardware.org/?probe=44013b0bb4) | Feb 23, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Kylin V10   | 15        | 88.24%  |
| Kylin V10.1 | 2         | 11.76%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Kylin | 17        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.19.0-32-generic       | 3         | 17.65%  |
| 5.4.18-35-generic       | 2         | 11.76%  |
| 5.4.18-15-generic       | 2         | 11.76%  |
| 6.2.0-23-generic        | 1         | 5.88%   |
| 6.2.0-21-generic        | 1         | 5.88%   |
| 5.4.18-27-generic       | 1         | 5.88%   |
| 5.19.0-45-generic       | 1         | 5.88%   |
| 5.19.0-41-generic       | 1         | 5.88%   |
| 5.15.0-73-generic       | 1         | 5.88%   |
| 5.15.0-69-generic       | 1         | 5.88%   |
| 5.10.0-20-amd64         | 1         | 5.88%   |
| 5.10.0-0.bpo.9-rt-amd64 | 1         | 5.88%   |
| 4.19.71-14-kr990        | 1         | 5.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.18  | 5         | 29.41%  |
| 5.19.0  | 5         | 29.41%  |
| 6.2.0   | 2         | 11.76%  |
| 5.15.0  | 2         | 11.76%  |
| 5.10.0  | 2         | 11.76%  |
| 4.19.71 | 1         | 5.88%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 5         | 29.41%  |
| 5.19    | 5         | 29.41%  |
| 6.2     | 2         | 11.76%  |
| 5.15    | 2         | 11.76%  |
| 5.10    | 2         | 11.76%  |
| 4.19    | 1         | 5.88%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 14        | 82.35%  |
| aarch64 | 3         | 17.65%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| GNOME | 9         | 52.94%  |
| UKUI  | 6         | 35.29%  |
| XFCE  | 1         | 5.88%   |
| KDE5  | 1         | 5.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 12        | 70.59%  |
| Wayland | 5         | 29.41%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM3    | 8         | 47.06%  |
| LightDM | 5         | 29.41%  |
| TDM     | 2         | 11.76%  |
| SDDM    | 1         | 5.88%   |
| GDM     | 1         | 5.88%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| zh_CN | 14        | 82.35%  |
| en_US | 3         | 17.65%  |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 14        | 82.35%  |
| BIOS | 3         | 17.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 16        | 94.12%  |
| Tmpfs | 1         | 5.88%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 16        | 94.12%  |
| MBR  | 1         | 5.88%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 13        | 76.47%  |
| Yes       | 4         | 23.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 10        | 58.82%  |
| Yes       | 7         | 41.18%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 8         | 47.06%  |
| HUAWEI           | 2         | 11.76%  |
| Hewlett-Packard  | 2         | 11.76%  |
| Timi             | 1         | 5.88%   |
| THTF             | 1         | 5.88%   |
| GreatWall        | 1         | 5.88%   |
| Dell             | 1         | 5.88%   |
| ASUSTek Computer | 1         | 5.88%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Timi TM1612                                  | 1         | 5.88%   |
| THTF CR F860-T1                              | 1         | 5.88%   |
| Lenovo XiaoXinPro 14ACH 2021 82MS            | 1         | 5.88%   |
| Lenovo ThinkPad X200 74574AC                 | 1         | 5.88%   |
| Lenovo ThinkPad X13 Gen 1 20T2A003CD         | 1         | 5.88%   |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y6S00400 | 1         | 5.88%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBA002CD  | 1         | 5.88%   |
| Lenovo ThinkPad T480s 20L7A00HHK             | 1         | 5.88%   |
| Lenovo Legion Y9000P IAH7H 82RF              | 1         | 5.88%   |
| Lenovo IdeaPad 710S-13ISK 80SW               | 1         | 5.88%   |
| HUAWEI MACH-WX9                              | 1         | 5.88%   |
| HUAWEI L410 KLVU-WDU0                        | 1         | 5.88%   |
| HP ZHAN 99 Mobile Workstation G3             | 1         | 5.88%   |
| HP EliteBook 840 G7 Notebook PC              | 1         | 5.88%   |
| Dell Inspiron 5468                           | 1         | 5.88%   |
| ASUS VivoBook_ASUSLaptop K5504VA_K5504VA     | 1         | 5.88%   |
| Unknown                                      | 1         | 5.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 5         | 29.41%  |
| Timi TM1612       | 1         | 5.88%   |
| THTF CR           | 1         | 5.88%   |
| Lenovo XiaoXinPro | 1         | 5.88%   |
| Lenovo Legion     | 1         | 5.88%   |
| Lenovo IdeaPad    | 1         | 5.88%   |
| HUAWEI MACH-WX9   | 1         | 5.88%   |
| HUAWEI L410       | 1         | 5.88%   |
| HP ZHAN           | 1         | 5.88%   |
| HP EliteBook      | 1         | 5.88%   |
| Dell Inspiron     | 1         | 5.88%   |
| ASUS VivoBook     | 1         | 5.88%   |
| Unknown           | 1         | 5.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 4         | 23.53%  |
| 2022    | 3         | 17.65%  |
| 2016    | 3         | 17.65%  |
| 2020    | 2         | 11.76%  |
| 2018    | 2         | 11.76%  |
| 2014    | 1         | 5.88%   |
| 2008    | 1         | 5.88%   |
| Unknown | 1         | 5.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 17        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 16        | 94.12%  |
| Enabled  | 1         | 5.88%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 17        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 6         | 35.29%  |
| 4.01-8.0    | 4         | 23.53%  |
| 3.01-4.0    | 3         | 17.65%  |
| 16.01-24.0  | 3         | 17.65%  |
| 64.01-256.0 | 1         | 5.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 3.01-4.0  | 5         | 29.41%  |
| 2.01-3.0  | 5         | 29.41%  |
| 1.01-2.0  | 3         | 17.65%  |
| 8.01-16.0 | 2         | 11.76%  |
| 4.01-8.0  | 1         | 5.88%   |
| 0.51-1.0  | 1         | 5.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 13        | 76.47%  |
| 2      | 2         | 11.76%  |
| 4      | 1         | 5.88%   |
| 3      | 1         | 5.88%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 16        | 94.12%  |
| Yes       | 1         | 5.88%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 10        | 58.82%  |
| No        | 7         | 41.18%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 88.24%  |
| No        | 2         | 11.76%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 88.24%  |
| No        | 2         | 11.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| China     | 14        | 82.35%  |
| Hong Kong | 3         | 17.65%  |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City       | Notebooks | Percent |
|------------|-----------|---------|
| Tianjin    | 2         | 11.76%  |
| Shenzhen   | 2         | 11.76%  |
| Jinrongjie | 2         | 11.76%  |
| Central    | 2         | 11.76%  |
| Xi'an      | 1         | 5.88%   |
| Shizishan  | 1         | 5.88%   |
| Putuo      | 1         | 5.88%   |
| Mong Kok   | 1         | 5.88%   |
| Harbin     | 1         | 5.88%   |
| Haidian    | 1         | 5.88%   |
| Changsha   | 1         | 5.88%   |
| Chancheng  | 1         | 5.88%   |
| Beijing    | 1         | 5.88%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 12     | 42.86%  |
| Toshiba             | 2         | 2      | 9.52%   |
| Micron Technology   | 2         | 2      | 9.52%   |
| ZX1 1TB             | 1         | 1      | 4.76%   |
| WDC                 | 1         | 1      | 4.76%   |
| Unknown             | 1         | 1      | 4.76%   |
| SK hynix            | 1         | 1      | 4.76%   |
| Phison              | 1         | 1      | 4.76%   |
| Lenovo              | 1         | 1      | 4.76%   |
| Kingchuxing         | 1         | 1      | 4.76%   |
| Hewlett-Packard     | 1         | 1      | 4.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 2         | 9.09%   |
| ZX1 1TB Disk 1TB                                    | 1         | 4.55%   |
| WDC PC SN530 SDBPNPZ-512G-1014 512GB                | 1         | 4.55%   |
| Unknown NVMe SSD Drive 256GB                        | 1         | 4.55%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 4.55%   |
| Toshiba KXG60ZNV512G KIOXIA 512GB                   | 1         | 4.55%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB              | 1         | 4.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 1         | 4.55%   |
| Samsung MZVLW256HEHP-000L2 256GB                    | 1         | 4.55%   |
| Samsung MZVLB512HBJQ-000L7 512GB                    | 1         | 4.55%   |
| Samsung MZVLB512HAJQ-00000 512GB                    | 1         | 4.55%   |
| Samsung MZVL2512HCJQ-00BL7 512GB                    | 1         | 4.55%   |
| Samsung MZNTY128HDHP-00000 128GB SSD                | 1         | 4.55%   |
| Samsung KLUFG8RHDA-B2D1 512GB                       | 1         | 4.55%   |
| Samsung KLUFG8RHDA-B2D1 1GB                         | 1         | 4.55%   |
| Phison ThinkPlus ST8000 PCI-E M.2 256G              | 1         | 4.55%   |
| Micron MTFDKBA512TFH 512GB                          | 1         | 4.55%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                       | 1         | 4.55%   |
| Lenovo SSD SL500 240G                               | 1         | 4.55%   |
| Kingchuxing SSD 128GB                               | 1         | 4.55%   |
| HP SSD EX950 1TB                                    | 1         | 4.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 5      | 50%     |
| Lenovo              | 1         | 1      | 25%     |
| Kingchuxing         | 1         | 1      | 25%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 13        | 15     | 68.42%  |
| SSD     | 4         | 7      | 21.05%  |
| HDD     | 1         | 1      | 5.26%   |
| Unknown | 1         | 1      | 5.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 13        | 15     | 68.42%  |
| SATA | 5         | 8      | 26.32%  |
| SAS  | 1         | 1      | 5.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4         | 6      | 66.67%  |
| 0.51-1.0   | 2         | 2      | 33.33%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 8         | 47.06%  |
| 501-1000   | 3         | 17.65%  |
| 51-100     | 3         | 17.65%  |
| 101-250    | 2         | 11.76%  |
| 1001-2000  | 1         | 5.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 5         | 29.41%  |
| 21-50    | 4         | 23.53%  |
| 101-250  | 3         | 17.65%  |
| 51-100   | 3         | 17.65%  |
| 251-500  | 1         | 5.88%   |
| 501-1000 | 1         | 5.88%   |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 12        | 13     | 70.59%  |
| Detected | 5         | 11     | 29.41%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Samsung Electronics             | 7         | 33.33%  |
| Intel                           | 5         | 23.81%  |
| Micron Technology               | 2         | 9.52%   |
| Toshiba America Info Systems    | 1         | 4.76%   |
| SK hynix                        | 1         | 4.76%   |
| Silicon Motion                  | 1         | 4.76%   |
| SanDisk                         | 1         | 4.76%   |
| Phison Electronics              | 1         | 4.76%   |
| Hefei DATANG Storage Technology | 1         | 4.76%   |
| AMD                             | 1         | 4.76%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                         | 3         | 13.64%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                        | 3         | 13.64%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                    | 3         | 13.64%  |
| Toshiba America Info Systems XG6 NVMe SSD Controller                  | 1         | 4.55%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                  | 1         | 4.55%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                         | 1         | 4.55%   |
| SanDisk WD Blue SN550 NVMe SSD                                        | 1         | 4.55%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                         | 1         | 4.55%   |
| Phison PS5013 E13 NVMe Controller                                     | 1         | 4.55%   |
| Micron NVMe Storage Controller                                        | 1         | 4.55%   |
| Micron 2450 NVMe SSD (DRAM-less)                                      | 1         | 4.55%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation | 1         | 4.55%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                      | 1         | 4.55%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode] | 1         | 4.55%   |
| Hefei DATANG Storage NVMe SSD Controller 300A                         | 1         | 4.55%   |
| AMD FCH SATA Controller [AHCI mode]                                   | 1         | 4.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 13        | 65%     |
| SATA | 5         | 25%     |
| RAID | 1         | 5%      |
| IDE  | 1         | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 12        | 70.59%  |
| Phytium | 2         | 11.76%  |
| AMD     | 2         | 11.76%  |
| ARM     | 1         | 5.88%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 11.76%  |
| Phytium FT-2000/4                       | 1         | 5.88%   |
| Phytium D2000/8 E8C                     | 1         | 5.88%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz        | 1         | 5.88%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 5.88%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 1         | 5.88%   |
| Intel Core i7-6560U CPU @ 2.20GHz       | 1         | 5.88%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 1         | 5.88%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz    | 1         | 5.88%   |
| Intel 13th Gen Core i9-13900H           | 1         | 5.88%   |
| Intel 12th Gen Core i7-12700H           | 1         | 5.88%   |
| Intel 12th Gen Core i5-1240P            | 1         | 5.88%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 1         | 5.88%   |
| ARM Processor                           | 1         | 5.88%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 1         | 5.88%   |
| AMD Ryzen 5 5600H with Radeon Graphics  | 1         | 5.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Other            | 7         | 41.18%  |
| Intel Core i7    | 3         | 17.65%  |
| Intel Core i5    | 3         | 17.65%  |
| Intel Core m3    | 1         | 5.88%   |
| Intel Core 2 Duo | 1         | 5.88%   |
| AMD Ryzen 7      | 1         | 5.88%   |
| AMD Ryzen 5      | 1         | 5.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 5         | 29.41%  |
| 2      | 4         | 23.53%  |
| 8      | 3         | 17.65%  |
| 14     | 2         | 11.76%  |
| 6      | 2         | 11.76%  |
| 12     | 1         | 5.88%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 16        | 94.12%  |
| 3      | 1         | 5.88%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 12        | 70.59%  |
| 1      | 5         | 29.41%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 17        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 7         | 41.18%  |
| 0x806ec    | 2         | 11.76%  |
| 0x406e3    | 2         | 11.76%  |
| 0x906a3    | 1         | 5.88%   |
| 0x806ea    | 1         | 5.88%   |
| 0x806e9    | 1         | 5.88%   |
| 0x1067a    | 1         | 5.88%   |
| 0x0a50000d | 1         | 5.88%   |
| 0x0a50000b | 1         | 5.88%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 5         | 29.41%  |
| Unknown          | 5         | 29.41%  |
| Zen 3            | 2         | 11.76%  |
| Skylake          | 2         | 11.76%  |
| Alderlake Hybrid | 2         | 11.76%  |
| Penryn           | 1         | 5.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 12        | 57.14%  |
| AMD    | 5         | 23.81%  |
| Nvidia | 4         | 19.05%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 2         | 9.52%   |
| Intel UHD Graphics 620                                                                | 2         | 9.52%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 9.52%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 2         | 9.52%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                  | 2         | 9.52%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 2         | 9.52%   |
| Nvidia TU117GLM [T600 Mobile]                                                         | 1         | 4.76%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 4.76%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 1         | 4.76%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 1         | 4.76%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 4.76%   |
| Intel Iris Graphics 540                                                               | 1         | 4.76%   |
| Intel HD Graphics 620                                                                 | 1         | 4.76%   |
| Intel HD Graphics 515                                                                 | 1         | 4.76%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 4.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 8         | 47.06%  |
| Intel + Nvidia | 3         | 17.65%  |
| 1 x AMD        | 3         | 17.65%  |
| Other          | 1         | 5.88%   |
| Intel + AMD    | 1         | 5.88%   |
| AMD + Nvidia   | 1         | 5.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 14        | 82.35%  |
| Proprietary | 2         | 11.76%  |
| Unknown     | 1         | 5.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 12        | 70.59%  |
| 1.01-2.0   | 4         | 23.53%  |
| 0.01-0.5   | 1         | 5.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 5         | 22.73%  |
| LG Display          | 3         | 13.64%  |
| Chimei Innolux      | 3         | 13.64%  |
| Lenovo              | 2         | 9.09%   |
| CSO                 | 2         | 9.09%   |
| AOC                 | 2         | 9.09%   |
| Xiaomi              | 1         | 4.55%   |
| Samsung Electronics | 1         | 4.55%   |
| KIG                 | 1         | 4.55%   |
| JDI                 | 1         | 4.55%   |
| Dell                | 1         | 4.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Xiaomi Mi TV XMD004A 1920x1080 708x398mm 32.0-inch                    | 1         | 4.55%   |
| Samsung Electronics LCD Monitor SDC4180 2880x1620 344x194mm 15.5-inch | 1         | 4.55%   |
| LG Display LCD Monitor LGD06AA 3840x2400 344x215mm 16.0-inch          | 1         | 4.55%   |
| LG Display LCD Monitor LGD060A 1920x1080 294x165mm 13.3-inch          | 1         | 4.55%   |
| LG Display LCD Monitor LGD04EF 1920x1080 294x165mm 13.3-inch          | 1         | 4.55%   |
| Lenovo X24i-10 LEN61AA 1920x1080 527x296mm 23.8-inch                  | 1         | 4.55%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch               | 1         | 4.55%   |
| KIG KKTV KIG2700 1920x1080 598x336mm 27.0-inch                        | 1         | 4.55%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 1         | 4.55%   |
| Dell P2717H DEL40F7 1920x1080 598x336mm 27.0-inch                     | 1         | 4.55%   |
| CSO LCD Monitor CSO1612 2560x1600 345x215mm 16.0-inch                 | 1         | 4.55%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                 | 1         | 4.55%   |
| Chimei Innolux LCD Monitor CMN153A 1920x1080 344x193mm 15.5-inch      | 1         | 4.55%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 1         | 4.55%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch      | 1         | 4.55%   |
| BOE LCD Monitor BOE0AC9 2240x1400 302x189mm 14.0-inch                 | 1         | 4.55%   |
| BOE LCD Monitor BOE08DA 1920x1080 309x174mm 14.0-inch                 | 1         | 4.55%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                 | 1         | 4.55%   |
| BOE LCD Monitor BOE06B6 1366x768 309x173mm 13.9-inch                  | 1         | 4.55%   |
| BOE LCD Monitor BOE0691 1920x1080 280x165mm 12.8-inch                 | 1         | 4.55%   |
| AOC Q27B3MA AOC2703 2560x1440 597x336mm 27.0-inch                     | 1         | 4.55%   |
| AOC 23E1WX AOC2301 1920x1080 488x297mm 22.5-inch                      | 1         | 4.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 10        | 50%     |
| 3840x2160 (4K)  | 2         | 10%     |
| 3840x2400       | 1         | 5%      |
| 3000x2000       | 1         | 5%      |
| 2880x1800       | 1         | 5%      |
| 2880x1620       | 1         | 5%      |
| 2560x1600       | 1         | 5%      |
| 2240x1400       | 1         | 5%      |
| 1366x768 (WXGA) | 1         | 5%      |
| 1280x800 (WXGA) | 1         | 5%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 6         | 27.27%  |
| 14     | 4         | 18.18%  |
| 27     | 3         | 13.64%  |
| 16     | 2         | 9.09%   |
| 15     | 2         | 9.09%   |
| 12     | 2         | 9.09%   |
| 65     | 1         | 4.55%   |
| 23     | 1         | 4.55%   |
| 22     | 1         | 4.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 11        | 50%     |
| 201-300     | 5         | 22.73%  |
| 501-600     | 4         | 18.18%  |
| 401-500     | 1         | 4.55%   |
| 1001-1500   | 1         | 4.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 12        | 66.67%  |
| 16/10 | 5         | 27.78%  |
| 3/2   | 1         | 5.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 8         | 36.36%  |
| 71-80          | 3         | 13.64%  |
| 301-350        | 3         | 13.64%  |
| 201-250        | 2         | 9.09%   |
| 111-120        | 2         | 9.09%   |
| 101-110        | 2         | 9.09%   |
| More than 1000 | 1         | 4.55%   |
| 61-70          | 1         | 4.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 161-240       | 6         | 28.57%  |
| 121-160       | 6         | 28.57%  |
| 51-100        | 4         | 19.05%  |
| More than 240 | 3         | 14.29%  |
| 1-50          | 1         | 4.76%   |
| 101-120       | 1         | 4.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 10        | 58.82%  |
| 2     | 6         | 35.29%  |
| 0     | 1         | 5.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 11        | 45.83%  |
| Realtek Semiconductor      | 8         | 33.33%  |
| Quectel Wireless Solutions | 1         | 4.17%   |
| MediaTek                   | 1         | 4.17%   |
| ICS Advent                 | 1         | 4.17%   |
| Huawei Technologies        | 1         | 4.17%   |
| ASIX Electronics           | 1         | 4.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 13.79%  |
| Intel Wireless 8265 / 8275                                        | 2         | 6.9%    |
| Intel Wireless 8260                                               | 2         | 6.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 6.9%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 6.9%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 3.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 3.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 3.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 3.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 3.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 3.45%   |
| Quectel Wireless Solutions Quectel EM05-CE                        | 1         | 3.45%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 3.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 3.45%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 3.45%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 3.45%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 3.45%   |
| Intel Alder Lake-U CNVi: Wireless-AC                              | 1         | 3.45%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 3.45%   |
| ICS Advent 10/100M LAN                                            | 1         | 3.45%   |
| Huawei Network controller                                         | 1         | 3.45%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 3.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 11        | 68.75%  |
| Realtek Semiconductor      | 3         | 18.75%  |
| Quectel Wireless Solutions | 1         | 6.25%   |
| MediaTek                   | 1         | 6.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                    | 2         | 12.5%   |
| Intel Wireless 8260                                           | 2         | 12.5%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 12.5%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 2         | 12.5%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 6.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 6.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 6.25%   |
| Quectel Wireless Solutions Quectel EM05-CE                    | 1         | 6.25%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 6.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 1         | 6.25%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection       | 1         | 6.25%   |
| Intel Alder Lake-U CNVi: Wireless-AC                          | 1         | 6.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 7         | 58.33%  |
| Intel                 | 3         | 25%     |
| ICS Advent            | 1         | 8.33%   |
| ASIX Electronics      | 1         | 8.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 33.33%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 8.33%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 8.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 8.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 8.33%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 8.33%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 8.33%   |
| ICS Advent 10/100M LAN                                            | 1         | 8.33%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 8.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 15        | 57.69%  |
| Ethernet | 10        | 38.46%  |
| Unknown  | 1         | 3.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 13        | 72.22%  |
| Ethernet | 5         | 27.78%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 10        | 58.82%  |
| 2     | 7         | 41.18%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 14        | 82.35%  |
| Yes  | 3         | 17.65%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 10        | 66.67%  |
| Realtek Semiconductor           | 1         | 6.67%   |
| Qualcomm Atheros Communications | 1         | 6.67%   |
| IMC Networks                    | 1         | 6.67%   |
| Foxconn / Hon Hai               | 1         | 6.67%   |
| Broadcom                        | 1         | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 4         | 26.67%  |
| Intel Bluetooth Device                             | 3         | 20%     |
| Intel AX201 Bluetooth                              | 2         | 13.33%  |
| Realtek Bluetooth Radio                            | 1         | 6.67%   |
| Qualcomm Atheros  Bluetooth Device                 | 1         | 6.67%   |
| Intel AX210 Bluetooth                              | 1         | 6.67%   |
| IMC Networks Bluetooth Radio                       | 1         | 6.67%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter       | 1         | 6.67%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 12        | 63.16%  |
| AMD    | 4         | 21.05%  |
| Nvidia | 3         | 15.79%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                | 5         | 25%     |
| Nvidia GA106 High Definition Audio Controller                  | 2         | 10%     |
| Intel Comet Lake PCH-LP cAVS                                   | 2         | 10%     |
| Intel Alder Lake PCH-P High Definition Audio Controller        | 2         | 10%     |
| AMD Family 17h/19h HD Audio Controller                         | 2         | 10%     |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]   | 2         | 10%     |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller | 1         | 5%      |
| Intel Tiger Lake-H HD Audio Controller                         | 1         | 5%      |
| Intel Alder Lake-U cAVS (Audio, Voice, Speech)                 | 1         | 5%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                 | 1         | 5%      |
| AMD Renoir Radeon High Definition Audio Controller             | 1         | 5%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 28.57%  |
| Micron Technology   | 4         | 28.57%  |
| SK hynix            | 3         | 21.43%  |
| UNILC               | 1         | 7.14%   |
| Nanya Technology    | 1         | 7.14%   |
| Elpida              | 1         | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| UNILC RAM 6478545886 8192MB SODIMM DDR4 2400MT/s                 | 1         | 6.67%   |
| SK hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                | 1         | 6.67%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 6.67%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 6.67%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 6.67%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 1         | 6.67%   |
| Samsung RAM Module 2048MB SODIMM LPDDR3 1867MT/s                 | 1         | 6.67%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 6.67%   |
| Samsung RAM K3UH7H70AM 8192MB Row Of Chips LPDDR4 4266MT/s       | 1         | 6.67%   |
| Nanya RAM M2N2G64CB8HA5N-BE 2GB SODIMM 1066MT/s                  | 1         | 6.67%   |
| Micron RAM MT62F1G32D4DR-031 2GB Row Of Chips LPDDR5 6400MT/s    | 1         | 6.67%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 6.67%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 6.67%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 6.67%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s            | 1         | 6.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 6         | 40%     |
| LPDDR3  | 3         | 20%     |
| LPDDR5  | 2         | 13.33%  |
| LPDDR4  | 2         | 13.33%  |
| DDR3    | 1         | 6.67%   |
| Unknown | 1         | 6.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 8         | 61.54%  |
| Row Of Chips | 5         | 38.46%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 8192 | 8         | 61.54%  |
| 2048 | 3         | 23.08%  |
| 4096 | 2         | 15.38%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 3         | 21.43%  |
| 6400  | 2         | 14.29%  |
| 3200  | 2         | 14.29%  |
| 1867  | 2         | 14.29%  |
| 4266  | 1         | 7.14%   |
| 2400  | 1         | 7.14%   |
| 2133  | 1         | 7.14%   |
| 1067  | 1         | 7.14%   |
| 1066  | 1         | 7.14%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 5         | 31.25%  |
| IMC Networks                           | 3         | 18.75%  |
| Unknown (0000034083)                   | 1         | 6.25%   |
| Sonix Technology                       | 1         | 6.25%   |
| Realtek Semiconductor                  | 1         | 6.25%   |
| Microdia                               | 1         | 6.25%   |
| Luxvisions Innotech Limited            | 1         | 6.25%   |
| Lenovo                                 | 1         | 6.25%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 6.25%   |
| BL012030059711690428                   | 1         | 6.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                      | 2         | 12.5%   |
| Unknown (0000034083) HD Camera                      | 1         | 6.25%   |
| Sonix USB2.0 FHD UVC WebCam                         | 1         | 6.25%   |
| Realtek Integrated_Webcam_HD                        | 1         | 6.25%   |
| Microdia USB2.0 Camera                              | 1         | 6.25%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 6.25%   |
| Lenovo Integrated Webcam                            | 1         | 6.25%   |
| IMC Networks Integrated RGB Camera                  | 1         | 6.25%   |
| Chicony XiaoMi USB 2.0 Webcam                       | 1         | 6.25%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 6.25%   |
| Chicony Integrated Camera                           | 1         | 6.25%   |
| Chicony HP HD Camera                                | 1         | 6.25%   |
| Chicony EasyCamera                                  | 1         | 6.25%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 1         | 6.25%   |
| BL012030059711690428 Integrated Camera              | 1         | 6.25%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Synaptics | 4         | 80%     |
| AuthenTec | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics UWP WBDI Device                                 | 1         | 20%     |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 20%     |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 20%     |
| AuthenTec AES2810                                         | 1         | 20%     |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 9         | 52.94%  |
| 1     | 7         | 41.18%  |
| 2     | 1         | 5.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 5         | 55.56%  |
| Graphics card         | 2         | 22.22%  |
| Multimedia controller | 1         | 11.11%  |
| Camera                | 1         | 11.11%  |

