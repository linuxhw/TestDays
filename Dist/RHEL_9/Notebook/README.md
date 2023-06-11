RHEL 9 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for RHEL 9.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 34

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo   | ThinkPad P17 Gen 2i 20YU... | [49ecdacd71](https://linux-hardware.org/?probe=49ecdacd71) | May 14, 2023 |
| HP       | EliteBook 855 G7 Noteboo... | [6e086ec096](https://linux-hardware.org/?probe=6e086ec096) | May 07, 2023 |
| Lenovo   | ThinkBook 14-IIL 20SL       | [5938e62d47](https://linux-hardware.org/?probe=5938e62d47) | Apr 17, 2023 |
| Dell     | Precision 7510              | [f68123c20a](https://linux-hardware.org/?probe=f68123c20a) | Apr 13, 2023 |
| Lenovo   | ThinkPad X1 Nano Gen 2 2... | [de656b2182](https://linux-hardware.org/?probe=de656b2182) | Apr 06, 2023 |
| HP       | ProBook 640 G2              | [9439371137](https://linux-hardware.org/?probe=9439371137) | Mar 18, 2023 |
| HP       | ProBook 640 G2              | [c968526666](https://linux-hardware.org/?probe=c968526666) | Mar 18, 2023 |
| ASUSTek  | VivoBook_ASUSLaptop X515... | [bc39bd2ce5](https://linux-hardware.org/?probe=bc39bd2ce5) | Mar 17, 2023 |
| Lenovo   | ThinkPad L14 Gen 3 21C2S... | [6772403b62](https://linux-hardware.org/?probe=6772403b62) | Feb 20, 2023 |
| Dell     | Precision 7560              | [7ed10eebe9](https://linux-hardware.org/?probe=7ed10eebe9) | Feb 16, 2023 |
| MSI      | GP75 Leopard 9SD            | [1f2a5b1def](https://linux-hardware.org/?probe=1f2a5b1def) | Feb 11, 2023 |
| Dell     | Latitude 9420               | [3fd325486b](https://linux-hardware.org/?probe=3fd325486b) | Jan 18, 2023 |
| Dell     | Latitude 3410               | [0a4720ef85](https://linux-hardware.org/?probe=0a4720ef85) | Jan 02, 2023 |
| MSI      | GE72VR 7RF                  | [f5384e68dd](https://linux-hardware.org/?probe=f5384e68dd) | Dec 16, 2022 |
| Lenovo   | ThinkPad X1 Nano Gen 2 2... | [7c17c479b7](https://linux-hardware.org/?probe=7c17c479b7) | Dec 03, 2022 |
| HP       | Laptop 14s-dk0xxx           | [c1d2a02024](https://linux-hardware.org/?probe=c1d2a02024) | Nov 30, 2022 |
| Dell     | Latitude E7450              | [1fba71c904](https://linux-hardware.org/?probe=1fba71c904) | Nov 15, 2022 |
| Lenovo   | ThinkPad X220 4291WSH       | [00e77b8815](https://linux-hardware.org/?probe=00e77b8815) | Oct 26, 2022 |
| Lenovo   | ThinkPad X220 4291WSH       | [94d1c333ac](https://linux-hardware.org/?probe=94d1c333ac) | Oct 26, 2022 |
| ASUSTek  | Z450LA                      | [ba00eb6516](https://linux-hardware.org/?probe=ba00eb6516) | Oct 18, 2022 |
| ASUSTek  | Z450LA                      | [6042d84470](https://linux-hardware.org/?probe=6042d84470) | Oct 17, 2022 |
| HP       | 340S G7                     | [7baf4edd11](https://linux-hardware.org/?probe=7baf4edd11) | Oct 09, 2022 |
| Razer    | Blade 15 Mid 2019-Base      | [c1457e4e02](https://linux-hardware.org/?probe=c1457e4e02) | Sep 21, 2022 |
| Dell     | Precision 7510              | [cd8482ea72](https://linux-hardware.org/?probe=cd8482ea72) | Aug 08, 2022 |
| Dell     | Inspiron 5559               | [aaaaef108a](https://linux-hardware.org/?probe=aaaaef108a) | Jul 03, 2022 |
| Lenovo   | ThinkPad E14 20RA001MMZ     | [4bf795762d](https://linux-hardware.org/?probe=4bf795762d) | Jul 02, 2022 |
| Lenovo   | ThinkPad Edge E431 62771... | [ef8cc06070](https://linux-hardware.org/?probe=ef8cc06070) | Jun 09, 2022 |
| ASUSTek  | TUF Gaming Z690-PLUS WIF... | [48c983a184](https://linux-hardware.org/?probe=48c983a184) | May 15, 2022 |
| Dell     | XPS 17 9710                 | [919abd9078](https://linux-hardware.org/?probe=919abd9078) | May 13, 2022 |
| Dell     | XPS 17 9710                 | [15bc7f6757](https://linux-hardware.org/?probe=15bc7f6757) | May 13, 2022 |
| Lenovo   | ThinkBook 13s-IWL 20R9      | [604488642b](https://linux-hardware.org/?probe=604488642b) | Apr 25, 2022 |
| Samsung  | 730QCJ/730QCR               | [24b05b96d7](https://linux-hardware.org/?probe=24b05b96d7) | Jan 19, 2022 |
| HP       | Pavilion Gaming Laptop 1... | [b6b4df52d0](https://linux-hardware.org/?probe=b6b4df52d0) | Dec 25, 2021 |
| Gigabyte | AERO 15 KD                  | [cfa38b921a](https://linux-hardware.org/?probe=cfa38b921a) | Nov 22, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.x86_64  | 4         | 15.38%  |
| 5.14.0-70.5.1.el9_0.x86_64   | 3         | 11.54%  |
| 5.14.0-70.26.1.el9_0.x86_64  | 3         | 11.54%  |
| 5.14.0-162.23.1.el9_1.x86_64 | 3         | 11.54%  |
| 5.14.0-162.12.1.el9_1.x86_64 | 3         | 11.54%  |
| 5.14.0-70.17.1.el9_0.x86_64  | 2         | 7.69%   |
| 5.14.0-70.13.1.el9_0.x86_64  | 2         | 7.69%   |
| 5.14.0-162.18.1.el9_1.x86_64 | 2         | 7.69%   |
| 5.14.0-70.30.1.el9_0.x86_64  | 1         | 3.85%   |
| 5.14.0-39.el9.x86_64         | 1         | 3.85%   |
| 5.14.0-284.11.1.el9_2.x86_64 | 1         | 3.85%   |
| 5.14.0-1.7.1.el9.x86_64      | 1         | 3.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 25        | 100%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 25        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 25        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 24        | 96%     |
| GNOME Classic | 1         | 4%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 18        | 72%     |
| X11     | 7         | 28%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 16        | 64%     |
| GDM     | 9         | 36%     |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 21        | 84%     |
| pt_BR | 2         | 8%      |
| en_GB | 2         | 8%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 25        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 24        | 96%     |
| Ext4 | 1         | 4%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 16        | 64%     |
| GPT     | 9         | 36%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 23        | 92%     |
| Yes       | 2         | 8%      |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 22        | 88%     |
| Yes       | 3         | 12%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 7         | 28%     |
| Dell                | 6         | 24%     |
| Hewlett-Packard     | 4         | 16%     |
| ASUSTek Computer    | 3         | 12%     |
| MSI                 | 2         | 8%      |
| Samsung Electronics | 1         | 4%      |
| Razer               | 1         | 4%      |
| Gigabyte Technology | 1         | 4%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Samsung 730QCJ/730QCR                    | 1         | 4%      |
| Razer Blade 15 Mid 2019-Base             | 1         | 4%      |
| MSI GP75 Leopard 9SD                     | 1         | 4%      |
| MSI GE72VR 7RF                           | 1         | 4%      |
| Lenovo ThinkPad X1 Nano Gen 2 21E80012US | 1         | 4%      |
| Lenovo ThinkPad P17 Gen 2i 20YU002KUS    | 1         | 4%      |
| Lenovo ThinkPad L14 Gen 3 21C2S1EE00     | 1         | 4%      |
| Lenovo ThinkPad Edge E431 62771L7        | 1         | 4%      |
| Lenovo ThinkPad E14 20RA001MMZ           | 1         | 4%      |
| Lenovo ThinkBook 14-IIL 20SL             | 1         | 4%      |
| Lenovo ThinkBook 13s-IWL 20R9            | 1         | 4%      |
| HP ProBook 640 G2                        | 1         | 4%      |
| HP Laptop 14s-dk0xxx                     | 1         | 4%      |
| HP EliteBook 855 G7 Notebook PC          | 1         | 4%      |
| HP 340S G7                               | 1         | 4%      |
| Gigabyte AERO 15 KD                      | 1         | 4%      |
| Dell XPS 17 9710                         | 1         | 4%      |
| Dell Precision 7560                      | 1         | 4%      |
| Dell Precision 7510                      | 1         | 4%      |
| Dell Latitude E7450                      | 1         | 4%      |
| Dell Latitude 3410                       | 1         | 4%      |
| Dell Inspiron 5559                       | 1         | 4%      |
| ASUS Z450LA                              | 1         | 4%      |
| ASUS VivoBook_ASUSLaptop X515MA_A516MA   | 1         | 4%      |
| ASUS TUF Gaming Z690-PLUS WIFI D4        | 1         | 4%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo ThinkPad  | 5         | 20%     |
| Lenovo ThinkBook | 2         | 8%      |
| Dell Precision   | 2         | 8%      |
| Dell Latitude    | 2         | 8%      |
| Samsung 730QCJ   | 1         | 4%      |
| Razer Blade      | 1         | 4%      |
| MSI GP75         | 1         | 4%      |
| MSI GE72VR       | 1         | 4%      |
| HP ProBook       | 1         | 4%      |
| HP Laptop        | 1         | 4%      |
| HP EliteBook     | 1         | 4%      |
| HP 340S          | 1         | 4%      |
| Gigabyte AERO    | 1         | 4%      |
| Dell XPS         | 1         | 4%      |
| Dell Inspiron    | 1         | 4%      |
| ASUS Z450LA      | 1         | 4%      |
| ASUS VivoBook    | 1         | 4%      |
| ASUS TUF         | 1         | 4%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 7         | 28%     |
| 2021 | 5         | 20%     |
| 2020 | 4         | 16%     |
| 2015 | 3         | 12%     |
| 2022 | 2         | 8%      |
| 2017 | 1         | 4%      |
| 2016 | 1         | 4%      |
| 2014 | 1         | 4%      |
| 2013 | 1         | 4%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 25        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 20        | 76.92%  |
| Enabled  | 6         | 23.08%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 25        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 12        | 48%     |
| 4.01-8.0    | 5         | 20%     |
| 32.01-64.0  | 3         | 12%     |
| 64.01-256.0 | 3         | 12%     |
| 3.01-4.0    | 2         | 8%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 9         | 34.62%  |
| 4.01-8.0  | 7         | 26.92%  |
| 3.01-4.0  | 4         | 15.38%  |
| 8.01-16.0 | 4         | 15.38%  |
| 1.01-2.0  | 2         | 7.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 16        | 61.54%  |
| 2      | 8         | 30.77%  |
| 3      | 2         | 7.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 21        | 84%     |
| Yes       | 4         | 16%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 76%     |
| No        | 6         | 24%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 88.46%  |
| No        | 3         | 11.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 9         | 36%     |
| Turkey      | 2         | 8%      |
| India       | 2         | 8%      |
| Chile       | 2         | 8%      |
| Brazil      | 2         | 8%      |
| UK          | 1         | 4%      |
| Switzerland | 1         | 4%      |
| Sri Lanka   | 1         | 4%      |
| Norway      | 1         | 4%      |
| Jordan      | 1         | 4%      |
| Indonesia   | 1         | 4%      |
| Guatemala   | 1         | 4%      |
| Finland     | 1         | 4%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Santiago       | 2         | 7.69%   |
| Whiteley       | 1         | 3.85%   |
| Stratham       | 1         | 3.85%   |
| Skien          | 1         | 3.85%   |
| Sao Paulo      | 1         | 3.85%   |
| Saint Paul     | 1         | 3.85%   |
| Providence     | 1         | 3.85%   |
| Prairieville   | 1         | 3.85%   |
| Piracicaba     | 1         | 3.85%   |
| New Delhi      | 1         | 3.85%   |
| Maltepe        | 1         | 3.85%   |
| Kolkata        | 1         | 3.85%   |
| Houston        | 1         | 3.85%   |
| Helsinki       | 1         | 3.85%   |
| Guatemala City | 1         | 3.85%   |
| Fort Collins   | 1         | 3.85%   |
| Denizli        | 1         | 3.85%   |
| Corona         | 1         | 3.85%   |
| Colombo        | 1         | 3.85%   |
| Christiansburg | 1         | 3.85%   |
| Bern           | 1         | 3.85%   |
| Bay Shore      | 1         | 3.85%   |
| Bandung        | 1         | 3.85%   |
| Baltimore      | 1         | 3.85%   |
| Amman          | 1         | 3.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 9      | 21.62%  |
| Sandisk             | 4         | 4      | 10.81%  |
| Toshiba             | 3         | 3      | 8.11%   |
| KIOXIA              | 3         | 4      | 8.11%   |
| SK hynix            | 2         | 2      | 5.41%   |
| Seagate             | 2         | 2      | 5.41%   |
| Micron Technology   | 2         | 2      | 5.41%   |
| Intel               | 2         | 3      | 5.41%   |
| WDC                 | 1         | 1      | 2.7%    |
| SSSTC               | 1         | 1      | 2.7%    |
| SABRENT             | 1         | 1      | 2.7%    |
| Plextor             | 1         | 1      | 2.7%    |
| Phison              | 1         | 1      | 2.7%    |
| Kingston            | 1         | 1      | 2.7%    |
| KingSpec            | 1         | 1      | 2.7%    |
| HGST                | 1         | 1      | 2.7%    |
| Golden              | 1         | 1      | 2.7%    |
| China               | 1         | 1      | 2.7%    |
| A-DATA Technology   | 1         | 1      | 2.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB     | 2         | 5.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 2         | 5.26%   |
| KIOXIA KBG5AZNT1T02 LA 1TB                          | 2         | 5.26%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 1         | 2.63%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 2.63%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 2.63%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 2.63%   |
| SSSTC CL1-3D512-Q11 NVMe 512GB                      | 1         | 2.63%   |
| SK hynix SHGP31-1000GM 1TB                          | 1         | 2.63%   |
| SK hynix NVMe SSD Drive 1024GB                      | 1         | 2.63%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 2.63%   |
| Seagate Backup+ Hub BK 6TB                          | 1         | 2.63%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 256GB    | 1         | 2.63%   |
| SanDisk NVMe SSD Drive 1TB                          | 1         | 2.63%   |
| Samsung SSD 980 1TB                                 | 1         | 2.63%   |
| Samsung SSD 883 DCT 960GB                           | 1         | 2.63%   |
| Samsung NVMe SSD Drive 2TB                          | 1         | 2.63%   |
| Samsung NVMe SSD Drive 1TB                          | 1         | 2.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 1         | 2.63%   |
| Samsung MZALQ256HAJD-000L2 256GB                    | 1         | 2.63%   |
| Samsung MZ7LN256HAJQ-000L7 256GB SSD                | 1         | 2.63%   |
| SABRENT Disk 14TB                                   | 1         | 2.63%   |
| Plextor PX-128S1G 128GB SSD                         | 1         | 2.63%   |
| Phison NVMe SSD Drive 960GB                         | 1         | 2.63%   |
| Micron MTFDHBA256TCK-1AS1AABHA 256GB                | 1         | 2.63%   |
| Micron 2450_MTFDKBA256TFK 256GB                     | 1         | 2.63%   |
| KIOXIA NVMe SSD Drive 512GB                         | 1         | 2.63%   |
| Kingston NVMe SSD Drive 2TB                         | 1         | 2.63%   |
| KingSpec NT-256 256GB SSD                           | 1         | 2.63%   |
| Intel SSDSC2BA800G4R 800GB                          | 1         | 2.63%   |
| Intel NVMe SSD Drive 512GB                          | 1         | 2.63%   |
| HGST HTS721010A9E630 1TB                            | 1         | 2.63%   |
| Golden MEMORY-1TB                                   | 1         | 2.63%   |
| China SSD 960GB                                     | 1         | 2.63%   |
| A-DATA IM2P33F3A NVMe 256GB                         | 1         | 2.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 42.86%  |
| Seagate | 2         | 2      | 28.57%  |
| WDC     | 1         | 1      | 14.29%  |
| HGST    | 1         | 1      | 14.29%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 28.57%  |
| SABRENT             | 1         | 1      | 14.29%  |
| Plextor             | 1         | 1      | 14.29%  |
| KingSpec            | 1         | 1      | 14.29%  |
| Intel               | 1         | 2      | 14.29%  |
| China               | 1         | 1      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 20        | 24     | 58.82%  |
| HDD     | 7         | 7      | 20.59%  |
| SSD     | 6         | 8      | 17.65%  |
| Unknown | 1         | 1      | 2.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 20        | 24     | 60.61%  |
| SATA | 11        | 14     | 33.33%  |
| SAS  | 2         | 2      | 6.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 7         | 8      | 53.85%  |
| 0.01-0.5   | 4         | 5      | 30.77%  |
| 10.01-20.0 | 1         | 1      | 7.69%   |
| 4.01-10.0  | 1         | 1      | 7.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 8         | 30.77%  |
| 251-500        | 5         | 19.23%  |
| 501-1000       | 5         | 19.23%  |
| 1001-2000      | 4         | 15.38%  |
| 51-100         | 2         | 7.69%   |
| More than 3000 | 1         | 3.85%   |
| Unknown        | 1         | 3.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 8         | 30.77%  |
| 21-50     | 7         | 26.92%  |
| 51-100    | 4         | 15.38%  |
| 251-500   | 3         | 11.54%  |
| 101-250   | 2         | 7.69%   |
| 1001-2000 | 1         | 3.85%   |
| Unknown   | 1         | 3.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                      | Notebooks | Drives | Percent |
|----------------------------|-----------|--------|---------|
| Intel SSDSC2BA800G4R 800GB | 1         | 2      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| Intel  | 1         | 2      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 2      | 100%    |

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
| Detected | 17        | 25     | 62.96%  |
| Works    | 9         | 13     | 33.33%  |
| Malfunc  | 1         | 2      | 3.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 17        | 44.74%  |
| Samsung Electronics         | 6         | 15.79%  |
| SanDisk                     | 4         | 10.53%  |
| KIOXIA                      | 3         | 7.89%   |
| SK hynix                    | 2         | 5.26%   |
| Micron Technology           | 2         | 5.26%   |
| Phison Electronics          | 1         | 2.63%   |
| Kingston Technology Company | 1         | 2.63%   |
| AMD                         | 1         | 2.63%   |
| ADATA Technology            | 1         | 2.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 3         | 7.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 3         | 7.69%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                | 2         | 5.13%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                     | 2         | 5.13%   |
| Samsung NVMe SSD Controller 980                                               | 2         | 5.13%   |
| Micron NVMe Storage Controller                                                | 2         | 5.13%   |
| KIOXIA Non-Volatile memory controller                                         | 2         | 5.13%   |
| Intel Volume Management Device NVMe RAID Controller                           | 2         | 5.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 2         | 5.13%   |
| Intel Comet Lake SATA AHCI Controller                                         | 2         | 5.13%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 1         | 2.56%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 1         | 2.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 1         | 2.56%   |
| Phison E12 NVMe Controller                                                    | 1         | 2.56%   |
| KIOXIA NVMe SSD Controller BG4                                                | 1         | 2.56%   |
| Kingston Company Company Non-Volatile memory controller                       | 1         | 2.56%   |
| Intel SSD 660P Series                                                         | 1         | 2.56%   |
| Intel SATA Controller [RAID mode]                                             | 1         | 2.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 2.56%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                 | 1         | 2.56%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 1         | 2.56%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 1         | 2.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 1         | 2.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 1         | 2.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 1         | 2.56%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 1         | 2.56%   |
| ADATA Non-Volatile memory controller                                          | 1         | 2.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 19        | 51.35%  |
| SATA | 12        | 32.43%  |
| RAID | 6         | 16.22%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 23        | 92%     |
| AMD    | 2         | 8%      |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 8%      |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 8%      |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 8%      |
| Intel Xeon W-11855M CPU @ 3.20GHz             | 1         | 4%      |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 4%      |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 4%      |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 4%      |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 4%      |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 4%      |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 4%      |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 4%      |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 4%      |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 4%      |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 4%      |
| Intel 12th Gen Core i9-12900K                 | 1         | 4%      |
| Intel 12th Gen Core i7-1260P                  | 1         | 4%      |
| Intel 12th Gen Core i5-1235U                  | 1         | 4%      |
| Intel 11th Gen Core i9-11950H @ 2.60GHz       | 1         | 4%      |
| Intel 11th Gen Core i9-11900H @ 2.50GHz       | 1         | 4%      |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 4%      |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 1         | 4%      |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 4%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 7         | 28%     |
| Intel Core i5   | 7         | 28%     |
| Other           | 6         | 24%     |
| Intel Xeon      | 1         | 4%      |
| Intel Core i3   | 1         | 4%      |
| Intel Celeron   | 1         | 4%      |
| AMD Ryzen 7 PRO | 1         | 4%      |
| AMD Ryzen 5     | 1         | 4%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 9         | 36%     |
| 2      | 6         | 24%     |
| 8      | 5         | 20%     |
| 6      | 3         | 12%     |
| 12     | 1         | 4%      |
| 10     | 1         | 4%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 25        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 23        | 92%     |
| 1      | 2         | 8%      |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 25        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 4         | 16%     |
| 0x806d1    | 4         | 16%     |
| 0x706e5    | 2         | 8%      |
| 0x406e3    | 2         | 8%      |
| 0x906ed    | 1         | 4%      |
| 0x906ea    | 1         | 4%      |
| 0x906e9    | 1         | 4%      |
| 0x906a4    | 1         | 4%      |
| 0x906a3    | 1         | 4%      |
| 0x90672    | 1         | 4%      |
| 0x706a8    | 1         | 4%      |
| 0x506e3    | 1         | 4%      |
| 0x40651    | 1         | 4%      |
| 0x306d4    | 1         | 4%      |
| 0x306a9    | 1         | 4%      |
| 0x08600106 | 1         | 4%      |
| 0x08108109 | 1         | 4%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 7         | 28%     |
| Icelake          | 6         | 24%     |
| Skylake          | 3         | 12%     |
| Alderlake Hybrid | 3         | 12%     |
| Zen+             | 1         | 4%      |
| Zen 2            | 1         | 4%      |
| IvyBridge        | 1         | 4%      |
| Haswell          | 1         | 4%      |
| Goldmont plus    | 1         | 4%      |
| Broadwell        | 1         | 4%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 20        | 62.5%   |
| Nvidia | 8         | 25%     |
| AMD    | 4         | 12.5%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 9.38%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 2         | 6.25%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 2         | 6.25%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 2         | 6.25%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 6.25%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 6.25%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 6.25%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                            | 1         | 3.13%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 1         | 3.13%   |
| Nvidia GA104GLM [RTX A5000 Mobile]                                            | 1         | 3.13%   |
| Nvidia GA102 [GeForce RTX 3090]                                               | 1         | 3.13%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 3.13%   |
| Intel HD Graphics 630                                                         | 1         | 3.13%   |
| Intel HD Graphics 5500                                                        | 1         | 3.13%   |
| Intel HD Graphics 530                                                         | 1         | 3.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 3.13%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 3.13%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                   | 1         | 3.13%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 1         | 3.13%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 1         | 3.13%   |
| AMD Venus XTX [Radeon HD 8890M / R9 M275X/M375X]                              | 1         | 3.13%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 1         | 3.13%   |
| AMD Renoir                                                                    | 1         | 3.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 3.13%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 13        | 52%     |
| Intel + Nvidia | 5         | 20%     |
| 1 x Nvidia     | 3         | 12%     |
| Intel + AMD    | 2         | 8%      |
| 1 x AMD        | 2         | 8%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 20        | 80%     |
| Proprietary | 4         | 16%     |
| Unknown     | 1         | 4%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 60%     |
| 5.01-6.0   | 3         | 12%     |
| 1.01-2.0   | 3         | 12%     |
| 2.01-3.0   | 1         | 4%      |
| 16.01-24.0 | 1         | 4%      |
| 8.01-16.0  | 1         | 4%      |
| 0.01-0.5   | 1         | 4%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| BOE                  | 8         | 25%     |
| Chimei Innolux       | 5         | 15.63%  |
| LG Display           | 3         | 9.38%   |
| Sharp                | 2         | 6.25%   |
| Samsung Electronics  | 2         | 6.25%   |
| Lenovo               | 2         | 6.25%   |
| Goldstar             | 2         | 6.25%   |
| AU Optronics         | 2         | 6.25%   |
| Hewlett-Packard      | 1         | 3.13%   |
| Gigabyte Technology  | 1         | 3.13%   |
| Dell                 | 1         | 3.13%   |
| CSO                  | 1         | 3.13%   |
| BOE Technology Group | 1         | 3.13%   |
| ASUSTek Computer     | 1         | 3.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP1518 1920x1200 366x229mm 17.0-inch               | 1         | 3.03%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 1         | 3.03%   |
| Samsung Electronics S24E450 SAM0C9B 1920x1080 521x293mm 23.5-inch     | 1         | 3.03%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 3.03%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch          | 1         | 3.03%   |
| LG Display LCD Monitor LGD0613 1920x1080 309x174mm 14.0-inch          | 1         | 3.03%   |
| LG Display LCD Monitor LGD0486 1920x1080 309x174mm 14.0-inch          | 1         | 3.03%   |
| Lenovo LEN P24h-20 LEN61F4 2560x1440 527x296mm 23.8-inch              | 1         | 3.03%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch            | 1         | 3.03%   |
| Lenovo LEN LT2323pwA LEN0BD0 1920x1080 510x287mm 23.0-inch            | 1         | 3.03%   |
| Hewlett-Packard LCD Monitor Pavilion32                                | 1         | 3.03%   |
| Goldstar LG UltraFine GSM5B11                                         | 1         | 3.03%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                | 1         | 3.03%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 1         | 3.03%   |
| Dell P2419HC DELA11D 1920x1080 527x296mm 23.8-inch                    | 1         | 3.03%   |
| CSO LCD Monitor CSO1303 2160x1350 280x175mm 13.0-inch                 | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN1760 1920x1080 381x214mm 17.2-inch      | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch      | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 1         | 3.03%   |
| BOE Technology Group LCD Monitor 5120x1440                            | 1         | 3.03%   |
| BOE LCD Monitor BOE0A62 1920x1080 309x174mm 14.0-inch                 | 1         | 3.03%   |
| BOE LCD Monitor BOE08FA 1920x1080 294x165mm 13.3-inch                 | 1         | 3.03%   |
| BOE LCD Monitor BOE07D7 1920x1080 294x165mm 13.3-inch                 | 1         | 3.03%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 1         | 3.03%   |
| BOE LCD Monitor BOE07C6 1366x768 309x173mm 13.9-inch                  | 1         | 3.03%   |
| BOE LCD Monitor BOE06F2 1920x1080 309x173mm 13.9-inch                 | 1         | 3.03%   |
| BOE LCD Monitor BOE069A 1366x768 309x173mm 13.9-inch                  | 1         | 3.03%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                  | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch         | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 1         | 3.03%   |
| ASUSTek Computer MZ27AQ AUS27AC 2560x1440 597x336mm 27.0-inch         | 1         | 3.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 14        | 46.67%  |
| 1366x768 (WXGA)   | 5         | 16.67%  |
| 3840x2160 (4K)    | 3         | 10%     |
| 2560x1440 (QHD)   | 3         | 10%     |
| Unknown           | 2         | 6.67%   |
| 5120x1440         | 1         | 3.33%   |
| 2160x1350         | 1         | 3.33%   |
| 1920x1200 (WUXGA) | 1         | 3.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 11        | 35.48%  |
| 15      | 5         | 16.13%  |
| 17      | 3         | 9.68%   |
| 14      | 3         | 9.68%   |
| 27      | 2         | 6.45%   |
| 24      | 2         | 6.45%   |
| 23      | 2         | 6.45%   |
| 72      | 1         | 3.23%   |
| 31      | 1         | 3.23%   |
| Unknown | 1         | 3.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 16        | 53.33%  |
| 501-600     | 5         | 16.67%  |
| 351-400     | 3         | 10%     |
| 201-300     | 3         | 10%     |
| 601-700     | 1         | 3.33%   |
| 1501-2000   | 1         | 3.33%   |
| Unknown     | 1         | 3.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 21        | 84%     |
| 16/10   | 3         | 12%     |
| Unknown | 1         | 4%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 11        | 35.48%  |
| 101-110        | 5         | 16.13%  |
| 71-80          | 3         | 9.68%   |
| 201-250        | 3         | 9.68%   |
| 121-130        | 3         | 9.68%   |
| 301-350        | 2         | 6.45%   |
| More than 1000 | 1         | 3.23%   |
| 351-500        | 1         | 3.23%   |
| 251-300        | 1         | 3.23%   |
| Unknown        | 1         | 3.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 12        | 42.86%  |
| 101-120       | 6         | 21.43%  |
| 161-240       | 4         | 14.29%  |
| 51-100        | 3         | 10.71%  |
| More than 240 | 2         | 7.14%   |
| Unknown       | 1         | 3.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 19        | 73.08%  |
| 2     | 5         | 19.23%  |
| 5     | 1         | 3.85%   |
| 4     | 1         | 3.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 61.11%  |
| Realtek Semiconductor | 12        | 33.33%  |
| Qualcomm Atheros      | 2         | 5.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 13.04%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 6.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 6.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 4.35%   |
| Intel Wireless 8260                                               | 2         | 4.35%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 4.35%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 4.35%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 4.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 4.35%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 4.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.17%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 2.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 2.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.17%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 2.17%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 2.17%   |
| Intel Wireless 7265                                               | 1         | 2.17%   |
| Intel Wireless 3160                                               | 1         | 2.17%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 2.17%   |
| Intel Ethernet Controller I225-V                                  | 1         | 2.17%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 2.17%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.17%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.17%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.17%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 2.17%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 2.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 2.17%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 2.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 2.17%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 1         | 2.17%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 88%     |
| Realtek Semiconductor | 3         | 12%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Comet Lake PCH-LP CNVi WiFi                        | 3         | 12%     |
| Intel Wireless 8260                                      | 2         | 8%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                   | 2         | 8%      |
| Intel Wi-Fi 6 AX200                                      | 2         | 8%      |
| Intel Ice Lake-LP PCH CNVi WiFi                          | 2         | 8%      |
| Intel Cannon Lake PCH CNVi WiFi                          | 2         | 8%      |
| Intel Alder Lake-P PCH CNVi WiFi                         | 2         | 8%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter | 1         | 4%      |
| Realtek RTL8723DE Wireless Network Adapter               | 1         | 4%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter          | 1         | 4%      |
| Intel Wireless 7265                                      | 1         | 4%      |
| Intel Wireless 3160                                      | 1         | 4%      |
| Intel Tiger Lake PCH CNVi WiFi                           | 1         | 4%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]         | 1         | 4%      |
| Intel Centrino Wireless-N 2230                           | 1         | 4%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                 | 1         | 4%      |
| Intel Alder Lake-S PCH CNVi WiFi                         | 1         | 4%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 11        | 55%     |
| Intel                 | 7         | 35%     |
| Qualcomm Atheros      | 2         | 10%     |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 28.57%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 14.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 9.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 4.76%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 4.76%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 4.76%   |
| Intel Ethernet Controller I225-V                                  | 1         | 4.76%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 4.76%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 4.76%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 4.76%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 4.76%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 4.76%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 4.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 25        | 56.82%  |
| Ethernet | 19        | 43.18%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 20        | 71.43%  |
| Ethernet | 8         | 28.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 18        | 72%     |
| 1     | 7         | 28%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 19        | 76%     |
| Yes  | 6         | 24%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 83.33%  |
| Realtek Semiconductor | 2         | 8.33%   |
| IMC Networks          | 1         | 4.17%   |
| Broadcom              | 1         | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                          | 5         | 20.83%  |
| Intel Bluetooth wireless interface             | 4         | 16.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 4         | 16.67%  |
| Intel AX210 Bluetooth                          | 2         | 8.33%   |
| Intel AX200 Bluetooth                          | 2         | 8.33%   |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 4.17%   |
| Realtek Bluetooth Radio                        | 1         | 4.17%   |
| Intel Wireless-AC 3168 Bluetooth               | 1         | 4.17%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 4.17%   |
| Intel Bluetooth Device                         | 1         | 4.17%   |
| IMC Networks Bluetooth Radio                   | 1         | 4.17%   |
| Broadcom BCM2045B (BDC-2.1)                    | 1         | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 54.76%  |
| Nvidia                | 8         | 19.05%  |
| Texas Instruments     | 3         | 7.14%   |
| AMD                   | 3         | 7.14%   |
| Sony                  | 1         | 2.38%   |
| Realtek Semiconductor | 1         | 2.38%   |
| LG Electronics        | 1         | 2.38%   |
| Hewlett-Packard       | 1         | 2.38%   |
| Corsair               | 1         | 2.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-H HD Audio Controller                                  | 4         | 8.7%    |
| Intel Comet Lake PCH-LP cAVS                                            | 3         | 6.52%   |
| Texas Instruments PCM2902 Audio Codec                                   | 2         | 4.35%   |
| Nvidia TU116 High Definition Audio Controller                           | 2         | 4.35%   |
| Nvidia GA106 High Definition Audio Controller                           | 2         | 4.35%   |
| Intel Sunrise Point-LP HD Audio                                         | 2         | 4.35%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller               | 2         | 4.35%   |
| Intel Cannon Lake PCH cAVS                                              | 2         | 4.35%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                 | 2         | 4.35%   |
| AMD Family 17h/19h HD Audio Controller                                  | 2         | 4.35%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                       | 1         | 2.17%   |
| Sony DualSense wireless controller (PS5)                                | 1         | 2.17%   |
| Realtek Semiconductor USB Audio                                         | 1         | 2.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 1         | 2.17%   |
| Nvidia GP106 High Definition Audio Controller                           | 1         | 2.17%   |
| Nvidia GA104 High Definition Audio Controller                           | 1         | 2.17%   |
| Nvidia GA102 High Definition Audio Controller                           | 1         | 2.17%   |
| LG Electronics USB Audio                                                | 1         | 2.17%   |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 1         | 2.17%   |
| Intel Haswell-ULT HD Audio Controller                                   | 1         | 2.17%   |
| Intel CM238 HD Audio Controller                                         | 1         | 2.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio            | 1         | 2.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                  | 1         | 2.17%   |
| Intel Broadwell-U Audio Controller                                      | 1         | 2.17%   |
| Intel Alder Lake-S HD Audio Controller                                  | 1         | 2.17%   |
| Intel 8 Series HD Audio Controller                                      | 1         | 2.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 1         | 2.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 1         | 2.17%   |
| Hewlett-Packard USB Audio                                               | 1         | 2.17%   |
| Corsair HS65 SURROUND                                                   | 1         | 2.17%   |
| AMD Renoir Radeon High Definition Audio Controller                      | 1         | 2.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                     | 1         | 2.17%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 1         | 2.17%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 3         | 37.5%   |
| SK hynix            | 2         | 25%     |
| Kingston            | 2         | 25%     |
| Smart               | 1         | 12.5%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s        | 1         | 11.11%  |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 11.11%  |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s      | 1         | 11.11%  |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 11.11%  |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 11.11%  |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 11.11%  |
| Samsung RAM K3LK7K7@BM-BGCP 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 11.11%  |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s        | 1         | 11.11%  |
| Kingston RAM 9905744-108.A00G 16GB SODIMM DDR4 3200MT/s      | 1         | 11.11%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 6         | 75%     |
| LPDDR5 | 1         | 12.5%   |
| DDR3   | 1         | 12.5%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 7         | 87.5%   |
| Row Of Chips | 1         | 12.5%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 4         | 44.44%  |
| 16384 | 3         | 33.33%  |
| 4096  | 1         | 11.11%  |
| 2048  | 1         | 11.11%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 2         | 22.22%  |
| 2667  | 2         | 22.22%  |
| 2133  | 2         | 22.22%  |
| 6400  | 1         | 11.11%  |
| 2400  | 1         | 11.11%  |
| 1600  | 1         | 11.11%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Seiko Epson L3210 Series | 1         | 100%    |

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
| Chicony Electronics                    | 5         | 20%     |
| IMC Networks                           | 3         | 12%     |
| Sunplus Innovation Technology          | 2         | 8%      |
| Syntek                                 | 1         | 4%      |
| Suyin                                  | 1         | 4%      |
| Sonix Technology                       | 1         | 4%      |
| Shenzhen Kingcome Optoelectronic       | 1         | 4%      |
| Remo Tech                              | 1         | 4%      |
| Realtek Semiconductor                  | 1         | 4%      |
| Quanta                                 | 1         | 4%      |
| Microsoft                              | 1         | 4%      |
| Microdia                               | 1         | 4%      |
| Luxvisions Innotech Limited            | 1         | 4%      |
| Lite-On Technology                     | 1         | 4%      |
| LG Electronics                         | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) | 1         | 4%      |
| Bison Electronics                      | 1         | 4%      |
| Acer                                   | 1         | 4%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                   | 2         | 8%      |
| Chicony Integrated Camera                                      | 2         | 8%      |
| Syntek Integrated Camera                                       | 1         | 4%      |
| Suyin Integrated_Webcam_HD                                     | 1         | 4%      |
| Sonix USB2.0 HD UVC WebCam                                     | 1         | 4%      |
| Shenzhen Kingcome Optoelectronic 720p HD Camera                | 1         | 4%      |
| Remo Tech OBSBOT Tiny 4K                                       | 1         | 4%      |
| Realtek Integrated_Webcam_HD                                   | 1         | 4%      |
| Quanta HP TrueVision HD Camera                                 | 1         | 4%      |
| Microsoft LifeCam VX-2000                                      | 1         | 4%      |
| Microdia Integrated_Webcam_HD                                  | 1         | 4%      |
| Luxvisions Innotech Limited Integrated RGB Camera              | 1         | 4%      |
| Lite-On HP HD Camera                                           | 1         | 4%      |
| LG LG UltraFine Display Camera                                 | 1         | 4%      |
| IMC Networks USB2.0 HD UVC WebCam                              | 1         | 4%      |
| IMC Networks USB Camera                                        | 1         | 4%      |
| IMC Networks Integrated Camera                                 | 1         | 4%      |
| Chicony USB2.0 VGA UVC WebCam                                  | 1         | 4%      |
| Chicony HP HD Camera                                           | 1         | 4%      |
| Chicony HD Webcam                                              | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 4%      |
| Bison BisonCam, NB Pro                                         | 1         | 4%      |
| Acer Integrated Camera                                         | 1         | 4%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 3         | 42.86%  |
| Shenzhen Goodix Technology | 2         | 28.57%  |
| Validity Sensors           | 1         | 14.29%  |
| Samsung Electronics        | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 2         | 28.57%  |
| Shenzhen Goodix  FingerPrint Device                       | 2         | 28.57%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 14.29%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 14.29%  |
| Samsung Fingerprint Sensor Device - 730B                  | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Broadcom 5880                                  | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 15        | 60%     |
| 1     | 9         | 36%     |
| 2     | 1         | 4%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 7         | 53.85%  |
| Multimedia controller | 3         | 23.08%  |
| Graphics card         | 2         | 15.38%  |
| Card reader           | 1         | 7.69%   |

