Fedora 35 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Fedora 35.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=fedora-35

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

| Vendor   | Model                   | Probe                                                      | Date         |
|----------|-------------------------|------------------------------------------------------------|--------------|
| Gigabyte | Z170-D3H-CF             | [103d2198a4](https://linux-hardware.org/?probe=103d2198a4) | Sep 30, 2021 |
| Gigabyte | Z170-D3H-CF             | [b6f5c877d4](https://linux-hardware.org/?probe=b6f5c877d4) | Sep 29, 2021 |
| Gigabyte | H81M-S2H                | [b8c27bd56c](https://linux-hardware.org/?probe=b8c27bd56c) | Sep 28, 2021 |
| ASRock   | B450M-HDV R4.0          | [2f771e8271](https://linux-hardware.org/?probe=2f771e8271) | Sep 24, 2021 |
| ASUSTek  | TUF GAMING B550M-PLUS   | [e75373a634](https://linux-hardware.org/?probe=e75373a634) | Sep 23, 2021 |
| ASUSTek  | ROG STRIX B360-I GAMING | [3875512e39](https://linux-hardware.org/?probe=3875512e39) | Sep 14, 2021 |
| ASUSTek  | ROG STRIX B360-I GAMING | [4fb9ed180b](https://linux-hardware.org/?probe=4fb9ed180b) | Sep 14, 2021 |
| Dell     | 0WMJ54 A01              | [3231b34d4d](https://linux-hardware.org/?probe=3231b34d4d) | Aug 24, 2021 |
| Dell     | 0WMJ54 A01              | [a94ad8a323](https://linux-hardware.org/?probe=a94ad8a323) | Aug 22, 2021 |
| HP       | 8055                    | [29f5b9a7ab](https://linux-hardware.org/?probe=29f5b9a7ab) | Aug 12, 2021 |
| Dell     | 0KC9NP A01              | [142e0703fb](https://linux-hardware.org/?probe=142e0703fb) | Aug 12, 2021 |
| Dell     | 0KC9NP A01              | [f48bc9ac9d](https://linux-hardware.org/?probe=f48bc9ac9d) | Aug 07, 2021 |
| ASUSTek  | Maximus V FORMULA       | [466ef3bd27](https://linux-hardware.org/?probe=466ef3bd27) | Jul 29, 2021 |
| Dell     | 0KC9NP A01              | [7dcd16d3fd](https://linux-hardware.org/?probe=7dcd16d3fd) | Jul 14, 2021 |
| Dell     | 0KC9NP A01              | [eedd464065](https://linux-hardware.org/?probe=eedd464065) | Jul 14, 2021 |
| Dell     | 0KC9NP A01              | [8d1e68aad0](https://linux-hardware.org/?probe=8d1e68aad0) | Jul 07, 2021 |
| Dell     | 0KC9NP A01              | [852a8a103d](https://linux-hardware.org/?probe=852a8a103d) | Jul 04, 2021 |
| Dell     | 0KC9NP A01              | [3a0ca9b90c](https://linux-hardware.org/?probe=3a0ca9b90c) | Jul 01, 2021 |
| Dell     | 0KC9NP A01              | [3ed1ee1f81](https://linux-hardware.org/?probe=3ed1ee1f81) | Jun 25, 2021 |
| Dell     | 0KC9NP A01              | [f611d9ec88](https://linux-hardware.org/?probe=f611d9ec88) | Jun 23, 2021 |
| ASUSTek  | Maximus V FORMULA       | [95ba18d5da](https://linux-hardware.org/?probe=95ba18d5da) | Jun 23, 2021 |
| Dell     | 0KC9NP A01              | [511e8019e0](https://linux-hardware.org/?probe=511e8019e0) | Jun 19, 2021 |
| Dell     | 0KC9NP A01              | [6687380bd7](https://linux-hardware.org/?probe=6687380bd7) | Jun 18, 2021 |
| Gigabyte | F2A88XN-WIFI            | [c22e6d8669](https://linux-hardware.org/?probe=c22e6d8669) | May 25, 2021 |
| ASUSTek  | Maximus V FORMULA       | [3e15dd7136](https://linux-hardware.org/?probe=3e15dd7136) | May 19, 2021 |
| ECS      | MCP61M-M3               | [2e5b21af19](https://linux-hardware.org/?probe=2e5b21af19) | Apr 17, 2021 |
| ASUSTek  | PRIME X570-PRO          | [3f7cbcea74](https://linux-hardware.org/?probe=3f7cbcea74) | Apr 14, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                             | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| 5.12.0-0.rc7.189.fc35.x86_64                        | 2        | 13.33%  |
| 5.14.8-lqx1.0.fc35.x86_64                           | 1        | 6.67%   |
| 5.14.7-300.fc35.x86_64                              | 1        | 6.67%   |
| 5.14.6-300.fc35.x86_64                              | 1        | 6.67%   |
| 5.14.1-300.fc35.x86_64                              | 1        | 6.67%   |
| 5.14.0-60.fc35.x86_64                               | 1        | 6.67%   |
| 5.14.0-0.rc6.46.fc35.x86_64                         | 1        | 6.67%   |
| 5.13.7-200.fc34.x86_64                              | 1        | 6.67%   |
| 5.13.0-58.fc35.x86_64                               | 1        | 6.67%   |
| 5.13.0-0.rc7.20210623git0c18f29aae7c.53.fc35.x86_64 | 1        | 6.67%   |
| 5.13.0-0.rc6.45.fc35.x86_64                         | 1        | 6.67%   |
| 5.13.0-0.rc2.20210521git79a106fc6585.22.fc35.x86_64 | 1        | 6.67%   |
| 5.13.0-0.rc2.19.fc35.x86_64                         | 1        | 6.67%   |
| 5.13.0-0.rc1.13.fc35.x86_64                         | 1        | 6.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.0  | 3        | 25%     |
| 5.14.0  | 2        | 16.67%  |
| 5.12.0  | 2        | 16.67%  |
| 5.14.8  | 1        | 8.33%   |
| 5.14.7  | 1        | 8.33%   |
| 5.14.6  | 1        | 8.33%   |
| 5.14.1  | 1        | 8.33%   |
| 5.13.7  | 1        | 8.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14    | 6        | 50%     |
| 5.13    | 4        | 33.33%  |
| 5.12    | 2        | 16.67%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 12       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GNOME   | 7        | 58.33%  |
| KDE     | 2        | 16.67%  |
| Unknown | 2        | 16.67%  |
| MATE    | 1        | 8.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 7        | 58.33%  |
| X11     | 2        | 16.67%  |
| Tty     | 2        | 16.67%  |
| Unknown | 1        | 8.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 7        | 58.33%  |
| GDM     | 4        | 33.33%  |
| LightDM | 1        | 8.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 7        | 58.33%  |
| ru_RU | 1        | 8.33%   |
| pt_BR | 1        | 8.33%   |
| es_CL | 1        | 8.33%   |
| en_GB | 1        | 8.33%   |
| en_CA | 1        | 8.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 9        | 75%     |
| BIOS | 3        | 25%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 7        | 58.33%  |
| Ext4  | 4        | 33.33%  |
| Xfs   | 1        | 8.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 6        | 46.15%  |
| Unknown | 5        | 38.46%  |
| MBR     | 2        | 15.38%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 69.23%  |
| Yes       | 4        | 30.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 69.23%  |
| Yes       | 4        | 30.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 4        | 33.33%  |
| Gigabyte Technology | 3        | 25%     |
| Dell                | 2        | 16.67%  |
| Hewlett-Packard     | 1        | 8.33%   |
| ECS                 | 1        | 8.33%   |
| ASRock              | 1        | 8.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| HP EliteDesk 800 G2 DM 35W   | 1        | 8.33%   |
| Gigabyte Z170-D3H            | 1        | 8.33%   |
| Gigabyte H81M-S2H            | 1        | 8.33%   |
| Gigabyte F2A88XN-WIFI        | 1        | 8.33%   |
| ECS MCP61M-M3                | 1        | 8.33%   |
| Dell OptiPlex 9020           | 1        | 8.33%   |
| Dell OptiPlex 3020           | 1        | 8.33%   |
| ASUS TUF GAMING B550M-PLUS   | 1        | 8.33%   |
| ASUS ROG STRIX B360-I GAMING | 1        | 8.33%   |
| ASUS PRIME X570-PRO          | 1        | 8.33%   |
| ASUS Maximus V FORMULA       | 1        | 8.33%   |
| ASRock B450M-HDV R4.0        | 1        | 8.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 2        | 16.67%  |
| HP EliteDesk          | 1        | 8.33%   |
| Gigabyte Z170-D3H     | 1        | 8.33%   |
| Gigabyte H81M-S2H     | 1        | 8.33%   |
| Gigabyte F2A88XN-WIFI | 1        | 8.33%   |
| ECS MCP61M-M3         | 1        | 8.33%   |
| ASUS TUF              | 1        | 8.33%   |
| ASUS ROG              | 1        | 8.33%   |
| ASUS PRIME            | 1        | 8.33%   |
| ASUS Maximus          | 1        | 8.33%   |
| ASRock B450M-HDV      | 1        | 8.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 4        | 33.33%  |
| 2015 | 3        | 25%     |
| 2021 | 1        | 8.33%   |
| 2020 | 1        | 8.33%   |
| 2019 | 1        | 8.33%   |
| 2013 | 1        | 8.33%   |
| 2010 | 1        | 8.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 12       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 11       | 91.67%  |
| Enabled  | 1        | 8.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 12       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 16.01-24.0 | 7        | 58.33%  |
| 8.01-16.0  | 2        | 16.67%  |
| 4.01-8.0   | 1        | 8.33%   |
| 32.01-64.0 | 1        | 8.33%   |
| 3.01-4.0   | 1        | 8.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 2.01-3.0 | 6        | 42.86%  |
| 3.01-4.0 | 3        | 21.43%  |
| 1.01-2.0 | 2        | 14.29%  |
| 4.01-8.0 | 1        | 7.14%   |
| 0.51-1.0 | 1        | 7.14%   |
| 0.01-0.5 | 1        | 7.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 5        | 41.67%  |
| 1      | 5        | 41.67%  |
| 4      | 1        | 8.33%   |
| 3      | 1        | 8.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 8        | 66.67%  |
| Yes       | 4        | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 12       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 7        | 58.33%  |
| No        | 5        | 41.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 7        | 58.33%  |
| Yes       | 5        | 41.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 3        | 25%     |
| Brazil      | 2        | 16.67%  |
| Turkey      | 1        | 8.33%   |
| Switzerland | 1        | 8.33%   |
| Spain       | 1        | 8.33%   |
| Hong Kong   | 1        | 8.33%   |
| Chile       | 1        | 8.33%   |
| Canada      | 1        | 8.33%   |
| Belarus     | 1        | 8.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City       | Desktops | Percent |
|------------|----------|---------|
| Zurich     | 1        | 8.33%   |
| Vancouver  | 1        | 8.33%   |
| Owatonna   | 1        | 8.33%   |
| Minsk      | 1        | 8.33%   |
| Laurel     | 1        | 8.33%   |
| La Florida | 1        | 8.33%   |
| Kwu Tung   | 1        | 8.33%   |
| Ja?�n      | 1        | 8.33%   |
| Istanbul   | 1        | 8.33%   |
| Guarapuava | 1        | 8.33%   |
| Goi??nia   | 1        | 8.33%   |
| Atlanta    | 1        | 8.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 11     | 35%     |
| WDC                 | 4        | 6      | 20%     |
| Seagate             | 3        | 8      | 15%     |
| Toshiba             | 2        | 2      | 10%     |
| SUNEAST             | 1        | 1      | 5%      |
| SABRENT             | 1        | 1      | 5%      |
| Kingston            | 1        | 1      | 5%      |
| Crucial             | 1        | 1      | 5%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 4.76%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 1        | 4.76%   |
| WDC WD30EZRX-00MMMB0 3TB         | 1        | 4.76%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1        | 4.76%   |
| Toshiba MQ01ABD050 500GB         | 1        | 4.76%   |
| Toshiba MG05ACA800E 8TB          | 1        | 4.76%   |
| SUNEAST SSD SE800 256GB          | 1        | 4.76%   |
| Seagate ST500DM002-1BD142 500GB  | 1        | 4.76%   |
| Seagate ST3500630AS 500GB        | 1        | 4.76%   |
| Seagate ST3000DM001-1CH166 3TB   | 1        | 4.76%   |
| Seagate ST2000DM008-2FR102 2TB   | 1        | 4.76%   |
| Samsung SSD 970 EVO Plus 500GB   | 1        | 4.76%   |
| Samsung SSD 970 EVO 500GB        | 1        | 4.76%   |
| Samsung SSD 860 EVO 500GB        | 1        | 4.76%   |
| Samsung SSD 860 EVO 250GB        | 1        | 4.76%   |
| Samsung SSD 860 EVO 1TB          | 1        | 4.76%   |
| Samsung SSD 840 EVO 250GB        | 1        | 4.76%   |
| Samsung NVMe SSD Drive 500GB     | 1        | 4.76%   |
| SABRENT ASM1153E 512GB           | 1        | 4.76%   |
| Kingston SA400S37480G 480GB SSD  | 1        | 4.76%   |
| Crucial CT1024MX200SSD1 1TB      | 1        | 4.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 8      | 42.86%  |
| WDC     | 2        | 4      | 28.57%  |
| Toshiba | 2        | 2      | 28.57%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 7      | 40%     |
| WDC                 | 2        | 2      | 20%     |
| SUNEAST             | 1        | 1      | 10%     |
| SABRENT             | 1        | 1      | 10%     |
| Kingston            | 1        | 1      | 10%     |
| Crucial             | 1        | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 8        | 13     | 47.06%  |
| HDD  | 6        | 14     | 35.29%  |
| NVMe | 3        | 4      | 17.65%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 10       | 26     | 71.43%  |
| NVMe | 3        | 4      | 21.43%  |
| SAS  | 1        | 1      | 7.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 6        | 14     | 42.86%  |
| 0.51-1.0   | 4        | 4      | 28.57%  |
| 1.01-2.0   | 2        | 2      | 14.29%  |
| 2.01-3.0   | 1        | 6      | 7.14%   |
| 4.01-10.0  | 1        | 1      | 7.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 4        | 30.77%  |
| 501-1000   | 3        | 23.08%  |
| 1001-2000  | 2        | 15.38%  |
| 251-500    | 1        | 7.69%   |
| 2001-3000  | 1        | 7.69%   |
| 1-20       | 1        | 7.69%   |
| 51-100     | 1        | 7.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 5        | 38.46%  |
| 251-500   | 2        | 15.38%  |
| 21-50     | 2        | 15.38%  |
| 501-1000  | 2        | 15.38%  |
| 1001-2000 | 1        | 7.69%   |
| 51-100    | 1        | 7.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD30EZRX-00MMMB0 3TB        | 1        | 1      | 33.33%  |
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 33.33%  |
| Seagate ST3500630AS 500GB       | 1        | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 66.67%  |
| WDC     | 1        | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 66.67%  |
| WDC     | 1        | 1      | 33.33%  |

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
| Works    | 8        | 11     | 50%     |
| Detected | 6        | 17     | 37.5%   |
| Malfunc  | 2        | 3      | 12.5%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 7        | 43.75%  |
| AMD                 | 4        | 25%     |
| Samsung Electronics | 3        | 18.75%  |
| Nvidia              | 1        | 6.25%   |
| ASMedia Technology  | 1        | 6.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3        | 16.67%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3        | 16.67%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 3        | 16.67%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 11.11%  |
| Nvidia MCP61 SATA Controller                                                   | 1        | 5.56%   |
| Nvidia MCP61 IDE                                                               | 1        | 5.56%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 5.56%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1        | 5.56%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 5.56%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                       | 1        | 5.56%   |
| AMD 400 Series Chipset SATA Controller                                         | 1        | 5.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 11       | 73.33%  |
| NVMe | 3        | 20%     |
| IDE  | 1        | 6.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 7        | 58.33%  |
| AMD    | 5        | 41.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i7-8700 CPU @ 3.20GHz                | 1        | 8.33%   |
| Intel Core i7-3770K CPU @ 3.50GHz               | 1        | 8.33%   |
| Intel Core i5-6500T CPU @ 2.50GHz               | 1        | 8.33%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1        | 8.33%   |
| Intel Core i5-4590S CPU @ 3.00GHz               | 1        | 8.33%   |
| Intel Core i5-4590 CPU @ 3.30GHz                | 1        | 8.33%   |
| Intel Core i5-4460 CPU @ 3.20GHz                | 1        | 8.33%   |
| AMD Ryzen 5 3600X 6-Core Processor              | 1        | 8.33%   |
| AMD Ryzen 5 3600 6-Core Processor               | 1        | 8.33%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 1        | 8.33%   |
| AMD Athlon II X2 250 Processor                  | 1        | 8.33%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1        | 8.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| Intel Core i5    | 5        | 41.67%  |
| AMD Ryzen 5      | 3        | 25%     |
| Intel Core i7    | 2        | 16.67%  |
| AMD Athlon II X2 | 1        | 8.33%   |
| AMD A10          | 1        | 8.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 6        | 50%     |
| 6      | 4        | 33.33%  |
| 2      | 2        | 16.67%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 12       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 6        | 50%     |
| 1      | 6        | 50%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 12       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x506e3    | 2        | 16.67%  |
| 0x306c3    | 2        | 16.67%  |
| 0x08701021 | 2        | 16.67%  |
| 0x906ea    | 1        | 8.33%   |
| 0x306a9    | 1        | 8.33%   |
| 0x08008206 | 1        | 8.33%   |
| 0x06003106 | 1        | 8.33%   |
| 0x010000b6 | 1        | 8.33%   |
| Unknown    | 1        | 8.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 3        | 25%     |
| Zen 2       | 2        | 16.67%  |
| Skylake     | 2        | 16.67%  |
| Zen+        | 1        | 8.33%   |
| Steamroller | 1        | 8.33%   |
| KabyLake    | 1        | 8.33%   |
| K10         | 1        | 8.33%   |
| IvyBridge   | 1        | 8.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 5        | 38.46%  |
| Nvidia | 4        | 30.77%  |
| Intel  | 4        | 30.77%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 15.38%  |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 7.69%   |
| Nvidia GP107 [GeForce GTX 1050 3GB]                                         | 1        | 7.69%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 1        | 7.69%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 1        | 7.69%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 7.69%   |
| Intel HD Graphics 530                                                       | 1        | 7.69%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 1        | 7.69%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 7.69%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 1        | 7.69%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 7.69%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 7.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x AMD    | 5        | 41.67%  |
| 1 x Nvidia | 4        | 33.33%  |
| 1 x Intel  | 3        | 25%     |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 9        | 75%     |
| Proprietary | 3        | 25%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 7        | 53.85%  |
| 3.01-4.0   | 2        | 15.38%  |
| 0.51-1.0   | 2        | 15.38%  |
| 1.01-2.0   | 1        | 7.69%   |
| 0.01-0.5   | 1        | 7.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Hewlett-Packard      | 2        | 22.22%  |
| Goldstar             | 2        | 22.22%  |
| AOC                  | 2        | 22.22%  |
| Lenovo               | 1        | 11.11%  |
| Dell                 | 1        | 11.11%  |
| Ancor Communications | 1        | 11.11%  |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Lenovo D24-20 LEN66AE 1920x1080 527x296mm 23.8-inch                    | 1        | 11.11%  |
| Hewlett-Packard ZR2740w HWP2957 2560x1440 597x336mm 27.0-inch          | 1        | 11.11%  |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch              | 1        | 11.11%  |
| Goldstar W2442 GSM56D9 1680x1050 530x300mm 24.0-inch                   | 1        | 11.11%  |
| Goldstar M2280A GSM57EC 1920x1080 476x268mm 21.5-inch                  | 1        | 11.11%  |
| Dell AW2518HF DELA102 1920x1080 544x303mm 24.5-inch                    | 1        | 11.11%  |
| AOC LE22H037 AOC2207 1920x1080 480x270mm 21.7-inch                     | 1        | 11.11%  |
| AOC 2220W AOC2220 1920x1080 477x268mm 21.5-inch                        | 1        | 11.11%  |
| Ancor Communications ASUS VW266H ACI26A4 1920x1200 550x340mm 25.5-inch | 1        | 11.11%  |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 6        | 75%     |
| 2560x1440 (QHD)   | 1        | 12.5%   |
| 1920x1200 (WUXGA) | 1        | 12.5%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 24     | 3        | 33.33%  |
| 21     | 3        | 33.33%  |
| 27     | 1        | 11.11%  |
| 25     | 1        | 11.11%  |
| 23     | 1        | 11.11%  |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 5        | 62.5%   |
| 401-500     | 3        | 37.5%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 7        | 87.5%   |
| 16/10 | 1        | 12.5%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 3        | 37.5%   |
| 251-300        | 2        | 25%     |
| 151-200        | 2        | 25%     |
| 301-350        | 1        | 12.5%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 101-120 | 4        | 50%     |
| 51-100  | 4        | 50%     |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10       | 83.33%  |
| 2     | 1        | 8.33%   |
| 0     | 1        | 8.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 9        | 50%     |
| Realtek Semiconductor | 5        | 27.78%  |
| TP-Link               | 1        | 5.56%   |
| Ralink Technology     | 1        | 5.56%   |
| Nvidia                | 1        | 5.56%   |
| Broadcom              | 1        | 5.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4        | 21.05%  |
| Intel Wi-Fi 6 AX200                                               | 2        | 10.53%  |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 5.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 5.26%   |
| Ralink RT5370 Wireless Adapter                                    | 1        | 5.26%   |
| Nvidia MCP61 Ethernet                                             | 1        | 5.26%   |
| Intel I211 Gigabit Network Connection                             | 1        | 5.26%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 5.26%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 5.26%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 5.26%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 5.26%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 1        | 5.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1        | 5.26%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 5.26%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 1        | 5.26%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 4        | 57.14%  |
| TP-Link           | 1        | 14.29%  |
| Ralink Technology | 1        | 14.29%  |
| Broadcom          | 1        | 14.29%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                           | 2        | 28.57%  |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]   | 1        | 14.29%  |
| Ralink RT5370 Wireless Adapter                | 1        | 14.29%  |
| Intel Centrino Wireless-N 1030 [Rainbow Peak] | 1        | 14.29%  |
| Intel Cannon Lake PCH CNVi WiFi               | 1        | 14.29%  |
| Broadcom BCM43228 802.11a/b/g/n               | 1        | 14.29%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 6        | 50%     |
| Realtek Semiconductor | 5        | 41.67%  |
| Nvidia                | 1        | 8.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4        | 33.33%  |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 8.33%   |
| Nvidia MCP61 Ethernet                                             | 1        | 8.33%   |
| Intel I211 Gigabit Network Connection                             | 1        | 8.33%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 8.33%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 8.33%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 8.33%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 8.33%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 8.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 12       | 63.16%  |
| WiFi     | 7        | 36.84%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 11       | 68.75%  |
| WiFi     | 5        | 31.25%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 7        | 58.33%  |
| 2     | 5        | 41.67%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 8        | 66.67%  |
| Yes  | 4        | 33.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 4        | 66.67%  |
| Cambridge Silicon Radio | 1        | 16.67%  |
| ASUSTek Computer        | 1        | 16.67%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 2        | 33.33%  |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1        | 16.67%  |
| Intel Bluetooth Device                              | 1        | 16.67%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 16.67%  |
| ASUS BCM20702A0                                     | 1        | 16.67%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 6        | 28.57%  |
| AMD                 | 6        | 28.57%  |
| Nvidia              | 5        | 23.81%  |
| C-Media Electronics | 3        | 14.29%  |
| Creative Labs       | 1        | 4.76%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 2        | 7.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 2        | 7.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 2        | 7.69%   |
| C-Media Electronics USB Audio Device                                | 2        | 7.69%   |
| AMD Starship/Matisse HD Audio Controller                            | 2        | 7.69%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]        | 2        | 7.69%   |
| Nvidia TU106 High Definition Audio Controller                       | 1        | 3.85%   |
| Nvidia MCP61 High Definition Audio                                  | 1        | 3.85%   |
| Nvidia GP107GL High Definition Audio Controller                     | 1        | 3.85%   |
| Nvidia GK104 HDMI Audio Controller                                  | 1        | 3.85%   |
| Nvidia GF106 High Definition Audio Controller                       | 1        | 3.85%   |
| Intel Cannon Lake PCH cAVS                                          | 1        | 3.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 1        | 3.85%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                  | 1        | 3.85%   |
| C-Media Electronics Audio Adapter                                   | 1        | 3.85%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]           | 1        | 3.85%   |
| AMD Kaveri HDMI/DP Audio Controller                                 | 1        | 3.85%   |
| AMD FCH Azalia Controller                                           | 1        | 3.85%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 1        | 3.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 1        | 3.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 3        | 33.33%  |
| Samsung Electronics | 2        | 22.22%  |
| Micron Technology   | 2        | 22.22%  |
| Crucial             | 2        | 22.22%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s              | 1        | 10%     |
| Samsung RAM M378B1G73QH0-CK0 8192MB DIMM DDR3 1600MT/s   | 1        | 10%     |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 1        | 10%     |
| Micron RAM 16ATF2G64AZ-2G1B1 16GB DIMM DDR4 2133MT/s     | 1        | 10%     |
| Crucial RAM CT8G4SFS824A.C8FBR1 8GB SODIMM DDR4 2400MT/s | 1        | 10%     |
| Crucial RAM BL8G30C15U4B.M8FE 8GB DIMM DDR4 3000MT/s     | 1        | 10%     |
| Corsair RAM VS2GB1333D4 2048MB DIMM DDR3 1600MT/s        | 1        | 10%     |
| Corsair RAM VS2GB1333D3 2048MB DIMM DDR3 1333MT/s        | 1        | 10%     |
| Corsair RAM CMZ32GX3M4X1866C10 8GB DIMM DDR3 1333MT/s    | 1        | 10%     |
| Corsair RAM CMK16GX4M2A2666C16 8192MB DIMM DDR4 3200MT/s | 1        | 10%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 4        | 50%     |
| DDR3 | 4        | 50%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 7        | 87.5%   |
| SODIMM | 1        | 12.5%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 5        | 55.56%  |
| 4096  | 2        | 22.22%  |
| 16384 | 1        | 11.11%  |
| 2048  | 1        | 11.11%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 3        | 30%     |
| 2133  | 2        | 20%     |
| 1333  | 2        | 20%     |
| 3200  | 1        | 10%     |
| 3000  | 1        | 10%     |
| 2400  | 1        | 10%     |

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


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Logitech | 3        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech QuickCam Pro 9000  | 1        | 33.33%  |
| Logitech HD Webcam C615     | 1        | 33.33%  |
| Logitech HD Pro Webcam C920 | 1        | 33.33%  |

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
| 0     | 12       | 100%    |

Unsupported Device Types
------------------------

Types of unsupported devices

Zero info for selected period =(

