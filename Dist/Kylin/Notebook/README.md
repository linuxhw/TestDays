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

Total: 24

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Apple     | MacBookPro12,1              | [4a1def29d3](https://linux-hardware.org/?probe=4a1def29d3) | Aug 09, 2023 |
| ASUSTek   | UX31LA                      | [0695e3bb09](https://linux-hardware.org/?probe=0695e3bb09) | Aug 08, 2023 |
| HUAWEI    | QingYun L420 KLVV-W5821     | [e3227788f6](https://linux-hardware.org/?probe=e3227788f6) | Jul 08, 2023 |
| Lenovo    | ThinkBook 16 G5+ ARP 21J... | [211f5e5cf1](https://linux-hardware.org/?probe=211f5e5cf1) | Jul 02, 2023 |
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
| Kylin V10   | 19        | 90.48%  |
| Kylin V10.1 | 2         | 9.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Kylin | 21        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.19.0-32-generic       | 3         | 14.29%  |
| 5.4.18-35-generic       | 2         | 9.52%   |
| 5.4.18-15-generic       | 2         | 9.52%   |
| 5.19.0-45-generic       | 2         | 9.52%   |
| 6.2.0-23-generic        | 1         | 4.76%   |
| 6.2.0-21-generic        | 1         | 4.76%   |
| 5.4.96-7-kr9a0          | 1         | 4.76%   |
| 5.4.18-27-generic       | 1         | 4.76%   |
| 5.4.0-155-generic       | 1         | 4.76%   |
| 5.19.0-41-generic       | 1         | 4.76%   |
| 5.15.0-73-generic       | 1         | 4.76%   |
| 5.15.0-69-generic       | 1         | 4.76%   |
| 5.10.0-23-amd64         | 1         | 4.76%   |
| 5.10.0-20-amd64         | 1         | 4.76%   |
| 5.10.0-0.bpo.9-rt-amd64 | 1         | 4.76%   |
| 4.19.71-14-kr990        | 1         | 4.76%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19.0  | 6         | 28.57%  |
| 5.4.18  | 5         | 23.81%  |
| 5.10.0  | 3         | 14.29%  |
| 6.2.0   | 2         | 9.52%   |
| 5.15.0  | 2         | 9.52%   |
| 5.4.96  | 1         | 4.76%   |
| 5.4.0   | 1         | 4.76%   |
| 4.19.71 | 1         | 4.76%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 7         | 33.33%  |
| 5.19    | 6         | 28.57%  |
| 5.10    | 3         | 14.29%  |
| 6.2     | 2         | 9.52%   |
| 5.15    | 2         | 9.52%   |
| 4.19    | 1         | 4.76%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 17        | 80.95%  |
| aarch64 | 4         | 19.05%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 11        | 52.38%  |
| UKUI       | 7         | 33.33%  |
| XFCE       | 1         | 4.76%   |
| X-Cinnamon | 1         | 4.76%   |
| KDE5       | 1         | 4.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 15        | 71.43%  |
| Wayland | 6         | 28.57%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM3    | 10        | 47.62%  |
| LightDM | 7         | 33.33%  |
| TDM     | 2         | 9.52%   |
| SDDM    | 1         | 4.76%   |
| GDM     | 1         | 4.76%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| zh_CN | 16        | 76.19%  |
| en_US | 4         | 19.05%  |
| en_HK | 1         | 4.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 17        | 80.95%  |
| BIOS | 4         | 19.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 19        | 90.48%  |
| Tmpfs   | 1         | 4.76%   |
| Overlay | 1         | 4.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 20        | 95.24%  |
| MBR  | 1         | 4.76%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 16        | 76.19%  |
| Yes       | 5         | 23.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 13        | 61.9%   |
| Yes       | 8         | 38.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 9         | 42.86%  |
| HUAWEI           | 3         | 14.29%  |
| Hewlett-Packard  | 2         | 9.52%   |
| ASUSTek Computer | 2         | 9.52%   |
| Timi             | 1         | 4.76%   |
| THTF             | 1         | 4.76%   |
| GreatWall        | 1         | 4.76%   |
| Dell             | 1         | 4.76%   |
| Apple            | 1         | 4.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Timi TM1612                                  | 1         | 4.76%   |
| THTF CR F860-T1                              | 1         | 4.76%   |
| Lenovo XiaoXinPro 14ACH 2021 82MS            | 1         | 4.76%   |
| Lenovo ThinkPad X200 74574AC                 | 1         | 4.76%   |
| Lenovo ThinkPad X13 Gen 1 20T2A003CD         | 1         | 4.76%   |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y6S00400 | 1         | 4.76%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBA002CD  | 1         | 4.76%   |
| Lenovo ThinkPad T480s 20L7A00HHK             | 1         | 4.76%   |
| Lenovo ThinkBook 16 G5+ ARP 21J0             | 1         | 4.76%   |
| Lenovo Legion Y9000P IAH7H 82RF              | 1         | 4.76%   |
| Lenovo IdeaPad 710S-13ISK 80SW               | 1         | 4.76%   |
| HUAWEI QingYun L420 KLVV-W5821               | 1         | 4.76%   |
| HUAWEI MACH-WX9                              | 1         | 4.76%   |
| HUAWEI L410 KLVU-WDU0                        | 1         | 4.76%   |
| HP ZHAN 99 Mobile Workstation G3             | 1         | 4.76%   |
| HP EliteBook 840 G7 Notebook PC              | 1         | 4.76%   |
| Dell Inspiron 5468                           | 1         | 4.76%   |
| ASUS VivoBook_ASUSLaptop K5504VA_K5504VA     | 1         | 4.76%   |
| ASUS UX31LA                                  | 1         | 4.76%   |
| Apple MacBookPro12,1                         | 1         | 4.76%   |
| Unknown                                      | 1         | 4.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 5         | 23.81%  |
| Timi TM1612        | 1         | 4.76%   |
| THTF CR            | 1         | 4.76%   |
| Lenovo XiaoXinPro  | 1         | 4.76%   |
| Lenovo ThinkBook   | 1         | 4.76%   |
| Lenovo Legion      | 1         | 4.76%   |
| Lenovo IdeaPad     | 1         | 4.76%   |
| HUAWEI QingYun     | 1         | 4.76%   |
| HUAWEI MACH-WX9    | 1         | 4.76%   |
| HUAWEI L410        | 1         | 4.76%   |
| HP ZHAN            | 1         | 4.76%   |
| HP EliteBook       | 1         | 4.76%   |
| Dell Inspiron      | 1         | 4.76%   |
| ASUS VivoBook      | 1         | 4.76%   |
| ASUS UX31LA        | 1         | 4.76%   |
| Apple MacBookPro12 | 1         | 4.76%   |
| Unknown            | 1         | 4.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 5         | 23.81%  |
| 2022    | 4         | 19.05%  |
| 2016    | 3         | 14.29%  |
| 2018    | 2         | 9.52%   |
| 2014    | 2         | 9.52%   |
| 2020    | 1         | 4.76%   |
| 2015    | 1         | 4.76%   |
| 2012    | 1         | 4.76%   |
| 2008    | 1         | 4.76%   |
| Unknown | 1         | 4.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 21        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 19        | 90.48%  |
| Enabled  | 2         | 9.52%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 21        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 6         | 28.57%  |
| 8.01-16.0   | 6         | 28.57%  |
| 3.01-4.0    | 4         | 19.05%  |
| 16.01-24.0  | 3         | 14.29%  |
| 24.01-32.0  | 1         | 4.76%   |
| 64.01-256.0 | 1         | 4.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 3.01-4.0  | 7         | 33.33%  |
| 2.01-3.0  | 5         | 23.81%  |
| 1.01-2.0  | 4         | 19.05%  |
| 4.01-8.0  | 2         | 9.52%   |
| 8.01-16.0 | 2         | 9.52%   |
| 0.51-1.0  | 1         | 4.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 16        | 76.19%  |
| 4      | 2         | 9.52%   |
| 2      | 2         | 9.52%   |
| 3      | 1         | 4.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 20        | 95.24%  |
| Yes       | 1         | 4.76%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 13        | 61.9%   |
| No        | 8         | 38.1%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 85.71%  |
| No        | 3         | 14.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 85.71%  |
| No        | 3         | 14.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| China     | 17        | 80.95%  |
| Hong Kong | 3         | 14.29%  |
| Taiwan    | 1         | 4.76%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City       | Notebooks | Percent |
|------------|-----------|---------|
| Tianjin    | 2         | 9.52%   |
| Shenzhen   | 2         | 9.52%   |
| Jinrongjie | 2         | 9.52%   |
| Central    | 2         | 9.52%   |
| Zhongshan  | 1         | 4.76%   |
| Xiaolou    | 1         | 4.76%   |
| Xi'an      | 1         | 4.76%   |
| Shizishan  | 1         | 4.76%   |
| Shanghai   | 1         | 4.76%   |
| Putuo      | 1         | 4.76%   |
| Mong Kok   | 1         | 4.76%   |
| Harbin     | 1         | 4.76%   |
| Haidian    | 1         | 4.76%   |
| Changsha   | 1         | 4.76%   |
| Chancheng  | 1         | 4.76%   |
| Beijing    | 1         | 4.76%   |
| Banqiao    | 1         | 4.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 12     | 36%     |
| Micron Technology   | 3         | 3      | 12%     |
| Toshiba             | 2         | 2      | 8%      |
| ZX1 1TB             | 1         | 1      | 4%      |
| WDC                 | 1         | 1      | 4%      |
| Unknown             | 1         | 1      | 4%      |
| SK hynix            | 1         | 1      | 4%      |
| SanDisk             | 1         | 1      | 4%      |
| Phison              | 1         | 1      | 4%      |
| Lenovo              | 1         | 1      | 4%      |
| Kingchuxing         | 1         | 1      | 4%      |
| HISI                | 1         | 4      | 4%      |
| Hewlett-Packard     | 1         | 1      | 4%      |
| Apple               | 1         | 1      | 4%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 2         | 7.69%   |
| Micron MTFDKBA512TFH 512GB                            | 2         | 7.69%   |
| ZX1 1TB Disk 1TB                                      | 1         | 3.85%   |
| WDC PC SN530 SDBPNPZ-512G-1014 512GB                  | 1         | 3.85%   |
| Unknown NVMe SSD Drive 256GB                          | 1         | 3.85%   |
| Toshiba MQ01ABD100 1TB                                | 1         | 3.85%   |
| Toshiba KXG60ZNV512G KIOXIA 512GB                     | 1         | 3.85%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB                | 1         | 3.85%   |
| SanDisk SD6SP1M256G1102 256GB SSD                     | 1         | 3.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 1         | 3.85%   |
| Samsung MZVLW256HEHP-000L2 256GB                      | 1         | 3.85%   |
| Samsung MZVLB512HBJQ-000L7 512GB                      | 1         | 3.85%   |
| Samsung MZVLB512HAJQ-00000 512GB                      | 1         | 3.85%   |
| Samsung MZVL2512HCJQ-00BL7 512GB                      | 1         | 3.85%   |
| Samsung MZNTY128HDHP-00000 128GB SSD                  | 1         | 3.85%   |
| Samsung KLUFG8RHDA-B2D1 512GB                         | 1         | 3.85%   |
| Samsung KLUFG8RHDA-B2D1 1GB                           | 1         | 3.85%   |
| Phison ThinkPlus ST8000 PCI-E M.2 256G                | 1         | 3.85%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                         | 1         | 3.85%   |
| Lenovo SSD SL500 240G                                 | 1         | 3.85%   |
| Kingchuxing SSD 128GB                                 | 1         | 3.85%   |
| HISI THR920GFCV100HAE 256GB                           | 1         | 3.85%   |
| HP SSD EX950 1TB                                      | 1         | 3.85%   |
| Apple SSD SM0256G 256GB                               | 1         | 3.85%   |

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
| Samsung Electronics | 2         | 5      | 28.57%  |
| SanDisk             | 1         | 1      | 14.29%  |
| Lenovo              | 1         | 1      | 14.29%  |
| Kingchuxing         | 1         | 1      | 14.29%  |
| HISI                | 1         | 4      | 14.29%  |
| Apple               | 1         | 1      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 14        | 16     | 60.87%  |
| SSD     | 7         | 13     | 30.43%  |
| HDD     | 1         | 1      | 4.35%   |
| Unknown | 1         | 1      | 4.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 14        | 16     | 60.87%  |
| SATA | 8         | 14     | 34.78%  |
| SAS  | 1         | 1      | 4.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 7         | 12     | 77.78%  |
| 0.51-1.0   | 2         | 2      | 22.22%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 9         | 42.86%  |
| 101-250    | 4         | 19.05%  |
| 51-100     | 4         | 19.05%  |
| 501-1000   | 3         | 14.29%  |
| 1001-2000  | 1         | 4.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 21-50    | 5         | 23.81%  |
| 1-20     | 5         | 23.81%  |
| 51-100   | 5         | 23.81%  |
| 101-250  | 3         | 14.29%  |
| 251-500  | 2         | 9.52%   |
| 501-1000 | 1         | 4.76%   |

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
| Works    | 15        | 16     | 71.43%  |
| Detected | 6         | 15     | 28.57%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Samsung Electronics             | 8         | 33.33%  |
| Intel                           | 6         | 25%     |
| Micron Technology               | 3         | 12.5%   |
| Toshiba America Info Systems    | 1         | 4.17%   |
| SK hynix                        | 1         | 4.17%   |
| Silicon Motion                  | 1         | 4.17%   |
| SanDisk                         | 1         | 4.17%   |
| Phison Electronics              | 1         | 4.17%   |
| Hefei DATANG Storage Technology | 1         | 4.17%   |
| AMD                             | 1         | 4.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                         | 3         | 12%     |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                        | 3         | 12%     |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                    | 3         | 12%     |
| Micron 3400 NVMe SSD [Hendrix]                                        | 2         | 8%      |
| Toshiba America Info Systems XG6 NVMe SSD Controller                  | 1         | 4%      |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                  | 1         | 4%      |
| Silicon Motion SM2262/SM2262EN SSD Controller                         | 1         | 4%      |
| SanDisk WD Blue SN550 NVMe SSD                                        | 1         | 4%      |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)            | 1         | 4%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                         | 1         | 4%      |
| Phison PS5013 E13 NVMe Controller                                     | 1         | 4%      |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                           | 1         | 4%      |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation | 1         | 4%      |
| Intel Mobile 4 Series Chipset PT IDER Controller                      | 1         | 4%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode] | 1         | 4%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                          | 1         | 4%      |
| Hefei DATANG Storage NVMe SSD Controller 300A                         | 1         | 4%      |
| AMD FCH SATA Controller [AHCI mode]                                   | 1         | 4%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 14        | 60.87%  |
| SATA | 7         | 30.43%  |
| RAID | 1         | 4.35%   |
| IDE  | 1         | 4.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 14        | 66.67%  |
| AMD     | 3         | 14.29%  |
| Phytium | 2         | 9.52%   |
| ARM     | 2         | 9.52%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 9.52%   |
| ARM Processor                           | 2         | 9.52%   |
| Phytium FT-2000/4                       | 1         | 4.76%   |
| Phytium D2000/8 E8C                     | 1         | 4.76%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz        | 1         | 4.76%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 4.76%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 1         | 4.76%   |
| Intel Core i7-6560U CPU @ 2.20GHz       | 1         | 4.76%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 1         | 4.76%   |
| Intel Core i5-5257U CPU @ 2.70GHz       | 1         | 4.76%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 1         | 4.76%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz    | 1         | 4.76%   |
| Intel 13th Gen Core i9-13900H           | 1         | 4.76%   |
| Intel 12th Gen Core i7-12700H           | 1         | 4.76%   |
| Intel 12th Gen Core i5-1240P            | 1         | 4.76%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 1         | 4.76%   |
| AMD Ryzen 7 7735H with Radeon Graphics  | 1         | 4.76%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 1         | 4.76%   |
| AMD Ryzen 5 5600H with Radeon Graphics  | 1         | 4.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Other            | 8         | 38.1%   |
| Intel Core i5    | 5         | 23.81%  |
| Intel Core i7    | 3         | 14.29%  |
| AMD Ryzen 7      | 2         | 9.52%   |
| Intel Core m3    | 1         | 4.76%   |
| Intel Core 2 Duo | 1         | 4.76%   |
| AMD Ryzen 5      | 1         | 4.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 6         | 28.57%  |
| 4      | 5         | 23.81%  |
| 8      | 4         | 19.05%  |
| 6      | 3         | 14.29%  |
| 14     | 2         | 9.52%   |
| 12     | 1         | 4.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 19        | 90.48%  |
| 3      | 2         | 9.52%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 15        | 71.43%  |
| 1      | 6         | 28.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 21        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 8         | 38.1%   |
| 0x806ec    | 2         | 9.52%   |
| 0x406e3    | 2         | 9.52%   |
| 0x906a3    | 1         | 4.76%   |
| 0x806ea    | 1         | 4.76%   |
| 0x806e9    | 1         | 4.76%   |
| 0x40651    | 1         | 4.76%   |
| 0x306d4    | 1         | 4.76%   |
| 0x1067a    | 1         | 4.76%   |
| 0x0a50000d | 1         | 4.76%   |
| 0x0a50000b | 1         | 4.76%   |
| 0x0a404102 | 1         | 4.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 7         | 33.33%  |
| KabyLake         | 5         | 23.81%  |
| Zen 3            | 2         | 9.52%   |
| Skylake          | 2         | 9.52%   |
| Alderlake Hybrid | 2         | 9.52%   |
| Penryn           | 1         | 4.76%   |
| Haswell          | 1         | 4.76%   |
| Broadwell        | 1         | 4.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 14        | 58.33%  |
| AMD    | 6         | 25%     |
| Nvidia | 4         | 16.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 2         | 8.33%   |
| Intel UHD Graphics 620                                                                | 2         | 8.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 8.33%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 2         | 8.33%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                  | 2         | 8.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 2         | 8.33%   |
| Nvidia TU117GLM [T600 Mobile]                                                         | 1         | 4.17%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 4.17%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 1         | 4.17%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 1         | 4.17%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 4.17%   |
| Intel Iris Graphics 6100                                                              | 1         | 4.17%   |
| Intel Iris Graphics 540                                                               | 1         | 4.17%   |
| Intel HD Graphics 620                                                                 | 1         | 4.17%   |
| Intel HD Graphics 515                                                                 | 1         | 4.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 1         | 4.17%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 4.17%   |
| AMD Rembrandt [Radeon 680M]                                                           | 1         | 4.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 10        | 47.62%  |
| 1 x AMD        | 4         | 19.05%  |
| Intel + Nvidia | 3         | 14.29%  |
| Other          | 2         | 9.52%   |
| Intel + AMD    | 1         | 4.76%   |
| AMD + Nvidia   | 1         | 4.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 17        | 80.95%  |
| Proprietary | 2         | 9.52%   |
| Unknown     | 2         | 9.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 71.43%  |
| 1.01-2.0   | 4         | 19.05%  |
| 3.01-4.0   | 1         | 4.76%   |
| 0.01-0.5   | 1         | 4.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 6         | 24%     |
| LG Display          | 3         | 12%     |
| Chimei Innolux      | 3         | 12%     |
| Lenovo              | 2         | 8%      |
| CSO                 | 2         | 8%      |
| AOC                 | 2         | 8%      |
| Xiaomi              | 1         | 4%      |
| Samsung Electronics | 1         | 4%      |
| KIG                 | 1         | 4%      |
| JDI                 | 1         | 4%      |
| Dell                | 1         | 4%      |
| CPT                 | 1         | 4%      |
| Apple               | 1         | 4%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Xiaomi Mi TV XMD004A 1920x1080 890x500mm 40.2-inch                    | 1         | 4%      |
| Samsung Electronics LCD Monitor SDC4180 2880x1620 344x194mm 15.5-inch | 1         | 4%      |
| LG Display LCD Monitor LGD06AA 3840x2400 344x215mm 16.0-inch          | 1         | 4%      |
| LG Display LCD Monitor LGD060A 1920x1080 294x165mm 13.3-inch          | 1         | 4%      |
| LG Display LCD Monitor LGD04EF 1920x1080 294x165mm 13.3-inch          | 1         | 4%      |
| Lenovo X24i-10 LEN61AA 1920x1080 527x296mm 23.8-inch                  | 1         | 4%      |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch               | 1         | 4%      |
| KIG KKTV KIG2700 1920x1080 598x336mm 27.0-inch                        | 1         | 4%      |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 1         | 4%      |
| Dell P2717H DEL40F7 1920x1080 598x336mm 27.0-inch                     | 1         | 4%      |
| CSO LCD Monitor CSO1612 2560x1600 345x215mm 16.0-inch                 | 1         | 4%      |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                 | 1         | 4%      |
| CPT LCD Monitor CPT17DB 1600x900 293x164mm 13.2-inch                  | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN153A 1920x1080 344x193mm 15.5-inch      | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch      | 1         | 4%      |
| BOE LCD Monitor BOE0AC9 2240x1400 302x189mm 14.0-inch                 | 1         | 4%      |
| BOE LCD Monitor BOE0AC1 2560x1600 344x215mm 16.0-inch                 | 1         | 4%      |
| BOE LCD Monitor BOE08DA 1920x1080 309x174mm 14.0-inch                 | 1         | 4%      |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                 | 1         | 4%      |
| BOE LCD Monitor BOE06B6 1366x768 309x173mm 13.9-inch                  | 1         | 4%      |
| BOE LCD Monitor BOE0691 1920x1080 280x165mm 12.8-inch                 | 1         | 4%      |
| Apple Color LCD APPA02A 2560x1600 286x179mm 13.3-inch                 | 1         | 4%      |
| AOC Q27B3MA AOC2703 2560x1440 597x336mm 27.0-inch                     | 1         | 4%      |
| AOC 23E1WX AOC2301 1920x1080 488x297mm 22.5-inch                      | 1         | 4%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 10        | 43.48%  |
| 2560x1600       | 3         | 13.04%  |
| 3840x2160 (4K)  | 2         | 8.7%    |
| 3840x2400       | 1         | 4.35%   |
| 3000x2000       | 1         | 4.35%   |
| 2880x1800       | 1         | 4.35%   |
| 2880x1620       | 1         | 4.35%   |
| 2240x1400       | 1         | 4.35%   |
| 1600x900 (HD+)  | 1         | 4.35%   |
| 1366x768 (WXGA) | 1         | 4.35%   |
| 1280x800 (WXGA) | 1         | 4.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 8         | 32%     |
| 14     | 4         | 16%     |
| 27     | 3         | 12%     |
| 16     | 3         | 12%     |
| 15     | 2         | 8%      |
| 12     | 2         | 8%      |
| 65     | 1         | 4%      |
| 23     | 1         | 4%      |
| 22     | 1         | 4%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 12        | 48%     |
| 201-300     | 7         | 28%     |
| 501-600     | 4         | 16%     |
| 401-500     | 1         | 4%      |
| 1001-1500   | 1         | 4%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 13        | 61.9%   |
| 16/10 | 7         | 33.33%  |
| 3/2   | 1         | 4.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 9         | 36%     |
| 71-80          | 4         | 16%     |
| 301-350        | 3         | 12%     |
| 111-120        | 3         | 12%     |
| 201-250        | 2         | 8%      |
| 101-110        | 2         | 8%      |
| More than 1000 | 1         | 4%      |
| 61-70          | 1         | 4%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 161-240       | 8         | 33.33%  |
| 121-160       | 7         | 29.17%  |
| 51-100        | 4         | 16.67%  |
| More than 240 | 3         | 12.5%   |
| 1-50          | 1         | 4.17%   |
| 101-120       | 1         | 4.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 13        | 61.9%   |
| 2     | 6         | 28.57%  |
| 0     | 2         | 9.52%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 12        | 38.71%  |
| Realtek Semiconductor      | 11        | 35.48%  |
| MediaTek                   | 2         | 6.45%   |
| Huawei Technologies        | 2         | 6.45%   |
| Quectel Wireless Solutions | 1         | 3.23%   |
| ICS Advent                 | 1         | 3.23%   |
| Broadcom                   | 1         | 3.23%   |
| ASIX Electronics           | 1         | 3.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 16.67%  |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 5.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 5.56%   |
| Intel Wireless 8265 / 8275                                        | 2         | 5.56%   |
| Intel Wireless 8260                                               | 2         | 5.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 5.56%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 5.56%   |
| Huawei Network controller                                         | 2         | 5.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 2.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 2.78%   |
| Quectel Wireless Solutions Quectel EM05-CE                        | 1         | 2.78%   |
| Intel Wireless 7260                                               | 1         | 2.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 2.78%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 1         | 2.78%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 2.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.78%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 2.78%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.78%   |
| ICS Advent USB 10/100 LAN                                         | 1         | 2.78%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 2.78%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 12        | 63.16%  |
| Realtek Semiconductor      | 3         | 15.79%  |
| MediaTek                   | 2         | 10.53%  |
| Quectel Wireless Solutions | 1         | 5.26%   |
| Broadcom                   | 1         | 5.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 10.53%  |
| Intel Wireless 8265 / 8275                                    | 2         | 10.53%  |
| Intel Wireless 8260                                           | 2         | 10.53%  |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 10.53%  |
| Intel Alder Lake-P PCH CNVi WiFi                              | 2         | 10.53%  |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 5.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 5.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 5.26%   |
| Quectel Wireless Solutions Quectel EM05-CE                    | 1         | 5.26%   |
| Intel Wireless 7260                                           | 1         | 5.26%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 1         | 5.26%   |
| Intel Raptor Lake PCH CNVi WiFi                               | 1         | 5.26%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection       | 1         | 5.26%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 1         | 5.26%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 10        | 66.67%  |
| Intel                 | 3         | 20%     |
| ICS Advent            | 1         | 6.67%   |
| ASIX Electronics      | 1         | 6.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 40%     |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 13.33%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 6.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 6.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 6.67%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 6.67%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 6.67%   |
| ICS Advent USB 10/100 LAN                                         | 1         | 6.67%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 6.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 18        | 54.55%  |
| Ethernet | 13        | 39.39%  |
| Unknown  | 2         | 6.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 16        | 72.73%  |
| Ethernet | 6         | 27.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 12        | 57.14%  |
| 2     | 9         | 42.86%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 18        | 85.71%  |
| Yes  | 3         | 14.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 61.11%  |
| Foxconn / Hon Hai               | 2         | 11.11%  |
| Realtek Semiconductor           | 1         | 5.56%   |
| Qualcomm Atheros Communications | 1         | 5.56%   |
| IMC Networks                    | 1         | 5.56%   |
| Broadcom                        | 1         | 5.56%   |
| Apple                           | 1         | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 5         | 27.78%  |
| Intel Bluetooth Device                             | 3         | 16.67%  |
| Intel AX201 Bluetooth                              | 2         | 11.11%  |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter       | 2         | 11.11%  |
| Realtek Bluetooth Radio                            | 1         | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                 | 1         | 5.56%   |
| Intel AX210 Bluetooth                              | 1         | 5.56%   |
| IMC Networks Bluetooth Radio                       | 1         | 5.56%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 5.56%   |
| Apple Bluetooth Host Controller                    | 1         | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 14        | 63.64%  |
| AMD    | 5         | 22.73%  |
| Nvidia | 3         | 13.64%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                | 5         | 19.23%  |
| AMD Family 17h/19h HD Audio Controller                         | 3         | 11.54%  |
| Nvidia GA106 High Definition Audio Controller                  | 2         | 7.69%   |
| Intel Comet Lake PCH-LP cAVS                                   | 2         | 7.69%   |
| Intel Alder Lake PCH-P High Definition Audio Controller        | 2         | 7.69%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]   | 2         | 7.69%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller | 1         | 3.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller        | 1         | 3.85%   |
| Intel Tiger Lake-H HD Audio Controller                         | 1         | 3.85%   |
| Intel Raptor Lake-P/U/H cAVS                                   | 1         | 3.85%   |
| Intel Haswell-ULT HD Audio Controller                          | 1         | 3.85%   |
| Intel Broadwell-U Audio Controller                             | 1         | 3.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                 | 1         | 3.85%   |
| Intel 8 Series HD Audio Controller                             | 1         | 3.85%   |
| AMD Renoir Radeon High Definition Audio Controller             | 1         | 3.85%   |
| AMD Rembrandt Radeon High Definition Audio Controller          | 1         | 3.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 5         | 27.78%  |
| Micron Technology   | 5         | 27.78%  |
| Samsung Electronics | 4         | 22.22%  |
| Elpida              | 2         | 11.11%  |
| UNILC               | 1         | 5.56%   |
| Nanya Technology    | 1         | 5.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| UNILC RAM 6478545886 8192MB SODIMM DDR4 2400MT/s                 | 1         | 5.26%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s                     | 1         | 5.26%   |
| SK hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                | 1         | 5.26%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 5.26%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 5.26%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 5.26%   |
| SK hynix RAM H9HKNNNFBMBUDR 8192MB Row Of Chips LPDDR4 4266MT/s  | 1         | 5.26%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 1         | 5.26%   |
| Samsung RAM Module 2048MB SODIMM LPDDR3 1867MT/s                 | 1         | 5.26%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 5.26%   |
| Samsung RAM K3UH7H70AM 8192MB Row Of Chips LPDDR4 4266MT/s       | 1         | 5.26%   |
| Nanya RAM M2N2G64CB8HA5N-BE 2GB SODIMM 1066MT/s                  | 1         | 5.26%   |
| Micron RAM MT62F2G32D8DR-031 WT 8GB Row Of Chips 6400MT/s        | 1         | 5.26%   |
| Micron RAM MT62F1G32D4DR-031 2GB Row Of Chips LPDDR5 6400MT/s    | 1         | 5.26%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 5.26%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 5.26%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 5.26%   |
| Elpida RAM Module 2048MB SODIMM DDR3 1600MT/s                    | 1         | 5.26%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM 1067MT/s                 | 1         | 5.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 6         | 31.58%  |
| LPDDR5  | 3         | 15.79%  |
| LPDDR4  | 3         | 15.79%  |
| LPDDR3  | 3         | 15.79%  |
| DDR3    | 3         | 15.79%  |
| Unknown | 1         | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 10        | 58.82%  |
| Row Of Chips | 7         | 41.18%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 8192 | 11        | 64.71%  |
| 4096 | 3         | 17.65%  |
| 2048 | 3         | 17.65%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 6400  | 3         | 16.67%  |
| 2667  | 3         | 16.67%  |
| 1867  | 3         | 16.67%  |
| 4266  | 2         | 11.11%  |
| 3200  | 2         | 11.11%  |
| 2400  | 1         | 5.56%   |
| 2133  | 1         | 5.56%   |
| 1600  | 1         | 5.56%   |
| 1067  | 1         | 5.56%   |
| 1066  | 1         | 5.56%   |

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
| Chicony Electronics                    | 6         | 31.58%  |
| IMC Networks                           | 3         | 15.79%  |
| Unknown (0000066029)                   | 2         | 10.53%  |
| Syntek                                 | 1         | 5.26%   |
| Sonix Technology                       | 1         | 5.26%   |
| Realtek Semiconductor                  | 1         | 5.26%   |
| Microdia                               | 1         | 5.26%   |
| Luxvisions Innotech Limited            | 1         | 5.26%   |
| Lenovo                                 | 1         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 5.26%   |
| BL012030059711690428                   | 1         | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown (0000066029) HD Camera                      | 2         | 10.53%  |
| IMC Networks Integrated Camera                      | 2         | 10.53%  |
| Syntek Integrated Camera                            | 1         | 5.26%   |
| Sonix USB2.0 FHD UVC WebCam                         | 1         | 5.26%   |
| Realtek Integrated_Webcam_HD                        | 1         | 5.26%   |
| Microdia USB2.0 Camera                              | 1         | 5.26%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 5.26%   |
| Lenovo Integrated Webcam                            | 1         | 5.26%   |
| IMC Networks Integrated RGB Camera                  | 1         | 5.26%   |
| Chicony XiaoMi USB 2.0 Webcam                       | 1         | 5.26%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 5.26%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 5.26%   |
| Chicony Integrated Camera                           | 1         | 5.26%   |
| Chicony HP HD Camera                                | 1         | 5.26%   |
| Chicony EasyCamera                                  | 1         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 1         | 5.26%   |
| BL012030059711690428 Integrated Camera              | 1         | 5.26%   |

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
| 0     | 12        | 57.14%  |
| 1     | 7         | 33.33%  |
| 2     | 2         | 9.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 5         | 45.45%  |
| Graphics card         | 3         | 27.27%  |
| Multimedia controller | 2         | 18.18%  |
| Camera                | 1         | 9.09%   |

