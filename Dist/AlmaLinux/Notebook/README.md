AlmaLinux - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for AlmaLinux.

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

Total: 28

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
| Toshiba | Satellite L50-C             | [b3e0ff9849](https://linux-hardware.org/?probe=b3e0ff9849) | Nov 01, 2022 |
| Acer    | TMP453-MG                   | [4d36d13ea9](https://linux-hardware.org/?probe=4d36d13ea9) | Oct 01, 2022 |
| Acer    | TravelMate 5735Z            | [b920fce554](https://linux-hardware.org/?probe=b920fce554) | Sep 17, 2022 |
| HP      | Falco                       | [5fa86b77d6](https://linux-hardware.org/?probe=5fa86b77d6) | Sep 17, 2022 |
| HP      | Laptop 15-ef1xxx            | [c01403937e](https://linux-hardware.org/?probe=c01403937e) | Sep 08, 2022 |
| HP      | ENVY dv6                    | [e7bc07047b](https://linux-hardware.org/?probe=e7bc07047b) | Aug 24, 2022 |
| HP      | Laptop 17-cp0xxx            | [82b34535ae](https://linux-hardware.org/?probe=82b34535ae) | Jul 06, 2022 |
| HP      | EliteBook 8470p             | [d6adb170de](https://linux-hardware.org/?probe=d6adb170de) | Jun 25, 2022 |
| Google  | Kohaku                      | [f43841c5e0](https://linux-hardware.org/?probe=f43841c5e0) | Jun 08, 2022 |
| Google  | Kohaku                      | [740a608274](https://linux-hardware.org/?probe=740a608274) | Jun 08, 2022 |
| Lenovo  | ThinkPad T440s 20ARS32P0... | [100b65a86d](https://linux-hardware.org/?probe=100b65a86d) | Jun 04, 2022 |
| Lenovo  | ThinkBook 13s-IWL 20R9      | [2fecc1fd76](https://linux-hardware.org/?probe=2fecc1fd76) | Apr 20, 2022 |
| Lenovo  | ThinkPad T14 Gen 1 20S1S... | [5ac68bc542](https://linux-hardware.org/?probe=5ac68bc542) | Mar 16, 2022 |
| Intel   | powered classmate PC        | [0585f5b715](https://linux-hardware.org/?probe=0585f5b715) | Dec 12, 2021 |
| Intel   | powered classmate PC        | [9416f348e4](https://linux-hardware.org/?probe=9416f348e4) | Dec 12, 2021 |
| Dell    | Inspiron 3185               | [53ac57fbea](https://linux-hardware.org/?probe=53ac57fbea) | Oct 26, 2021 |
| Dell    | Inspiron 3185               | [2c9cec7881](https://linux-hardware.org/?probe=2c9cec7881) | Oct 01, 2021 |
| Lenovo  | Yoga 2 13 20344             | [1a59499d3a](https://linux-hardware.org/?probe=1a59499d3a) | Sep 29, 2021 |
| Lenovo  | IdeaPad S145-15IWL 81MV     | [95a2b3a95d](https://linux-hardware.org/?probe=95a2b3a95d) | Aug 27, 2021 |
| HP      | EliteBook 8570w             | [37e72494a5](https://linux-hardware.org/?probe=37e72494a5) | Jul 29, 2021 |
| ASUSTek | ASUS EXPERTBOOK B9450FA_... | [cdf0f4017c](https://linux-hardware.org/?probe=cdf0f4017c) | Jul 16, 2021 |
| Lenovo  | IdeaPad Slim 1-14AST-05 ... | [9044b57593](https://linux-hardware.org/?probe=9044b57593) | Jul 11, 2021 |
| Lenovo  | Legion 5 15IMH05H 81Y6      | [21a6135eda](https://linux-hardware.org/?probe=21a6135eda) | Jun 16, 2021 |
| Dell    | Inspiron 3185               | [84fa76eb2f](https://linux-hardware.org/?probe=84fa76eb2f) | Apr 20, 2021 |
| Dell    | Inspiron 3185               | [d49edb76fa](https://linux-hardware.org/?probe=d49edb76fa) | Apr 15, 2021 |
| Dell    | Inspiron 3185               | [15b8da5bc1](https://linux-hardware.org/?probe=15b8da5bc1) | Apr 14, 2021 |
| Lenovo  | IdeaPad Slim 1-14AST-05 ... | [f0791eb42d](https://linux-hardware.org/?probe=f0791eb42d) | Mar 30, 2021 |
| Lenovo  | IdeaPad 330-15ARR 81D2      | [8810309035](https://linux-hardware.org/?probe=8810309035) | Mar 24, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| AlmaLinux 9.0 | 5         | 25%     |
| AlmaLinux 8.6 | 5         | 25%     |
| AlmaLinux 8.4 | 5         | 25%     |
| AlmaLinux 8.3 | 3         | 15%     |
| AlmaLinux 8.5 | 2         | 10%     |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| AlmaLinux | 20        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.14.0-70.22.1.el9_0.x86_64  | 2         | 10%     |
| 4.18.0-372.26.1.el8_6.x86_64 | 2         | 10%     |
| 4.18.0-305.7.1.el8_4.x86_64  | 2         | 10%     |
| 4.18.0-240.15.1.el8_3.x86_64 | 2         | 10%     |
| 5.4.175-1.el8.elrepo.x86_64  | 1         | 5%      |
| 5.14.0-70.26.1.el9_0.x86_64  | 1         | 5%      |
| 5.14.0-70.17.1.el9_0.x86_64  | 1         | 5%      |
| 5.14.0-70.13.1.el9_0.x86_64  | 1         | 5%      |
| 4.18.0-372.9.1.el8.x86_64    | 1         | 5%      |
| 4.18.0-372.19.1.el8_6.x86_64 | 1         | 5%      |
| 4.18.0-348.2.1.el8_5.x86_64  | 1         | 5%      |
| 4.18.0-348.12.2.el8_5.x86_64 | 1         | 5%      |
| 4.18.0-305.el8.x86_64        | 1         | 5%      |
| 4.18.0-305.3.1.el8_4.x86_64  | 1         | 5%      |
| 4.18.0-305.12.1.el8_4.x86_64 | 1         | 5%      |
| 4.18.0-240.22.1.el8_3.x86_64 | 1         | 5%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.0  | 14        | 70%     |
| 5.14.0  | 5         | 25%     |
| 5.4.175 | 1         | 5%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 14        | 70%     |
| 5.14    | 5         | 25%     |
| 5.4     | 1         | 5%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 20        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| GNOME | 16        | 80%     |
| MATE  | 2         | 10%     |
| XFCE  | 1         | 5%      |
| KDE5  | 1         | 5%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 12        | 60%     |
| X11     | 8         | 40%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 9         | 45%     |
| GDM     | 8         | 40%     |
| LightDM | 2         | 10%     |
| SDDM    | 1         | 5%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 12        | 60%     |
| de_DE | 4         | 20%     |
| fr_FR | 2         | 10%     |
| es_VE | 1         | 5%      |
| es_ES | 1         | 5%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 13        | 65%     |
| BIOS | 7         | 35%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 16        | 80%     |
| Ext4 | 4         | 20%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 10        | 50%     |
| Unknown | 8         | 40%     |
| MBR     | 2         | 10%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 17        | 85%     |
| Yes       | 3         | 15%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 16        | 80%     |
| Yes       | 4         | 20%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 7         | 35%     |
| Hewlett-Packard  | 6         | 30%     |
| Acer             | 2         | 10%     |
| Toshiba          | 1         | 5%      |
| Intel            | 1         | 5%      |
| Google           | 1         | 5%      |
| Dell             | 1         | 5%      |
| ASUSTek Computer | 1         | 5%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba Satellite L50-C              | 1         | 5%      |
| Lenovo Yoga 2 13 20344               | 1         | 5%      |
| Lenovo ThinkPad T440s 20ARS32P00     | 1         | 5%      |
| Lenovo ThinkPad T14 Gen 1 20S1S39Q00 | 1         | 5%      |
| Lenovo Legion 5 15IMH05H 81Y6        | 1         | 5%      |
| Lenovo IdeaPad Slim 1-14AST-05 81VS  | 1         | 5%      |
| Lenovo IdeaPad S145-15IWL 81MV       | 1         | 5%      |
| Lenovo IdeaPad 330-15ARR 81D2        | 1         | 5%      |
| Intel powered classmate PC           | 1         | 5%      |
| HP Laptop 17-cp0xxx                  | 1         | 5%      |
| HP Laptop 15-ef1xxx                  | 1         | 5%      |
| HP Falco                             | 1         | 5%      |
| HP ENVY dv6                          | 1         | 5%      |
| HP EliteBook 8570w                   | 1         | 5%      |
| HP EliteBook 8470p                   | 1         | 5%      |
| Google Kohaku                        | 1         | 5%      |
| Dell Inspiron 3185                   | 1         | 5%      |
| ASUS ASUS EXPERTBOOK B9450FA_B9450FA | 1         | 5%      |
| Acer TravelMate 5735Z                | 1         | 5%      |
| Acer TMP453-MG                       | 1         | 5%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo IdeaPad    | 3         | 15%     |
| Lenovo ThinkPad   | 2         | 10%     |
| HP Laptop         | 2         | 10%     |
| HP EliteBook      | 2         | 10%     |
| Toshiba Satellite | 1         | 5%      |
| Lenovo Yoga       | 1         | 5%      |
| Lenovo Legion     | 1         | 5%      |
| Intel powered     | 1         | 5%      |
| HP Falco          | 1         | 5%      |
| HP ENVY           | 1         | 5%      |
| Google Kohaku     | 1         | 5%      |
| Dell Inspiron     | 1         | 5%      |
| ASUS ASUS         | 1         | 5%      |
| Acer TravelMate   | 1         | 5%      |
| Acer TMP453-MG    | 1         | 5%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 3         | 15%     |
| 2019 | 3         | 15%     |
| 2012 | 3         | 15%     |
| 2018 | 2         | 10%     |
| 2014 | 2         | 10%     |
| 2011 | 2         | 10%     |
| 2022 | 1         | 5%      |
| 2021 | 1         | 5%      |
| 2015 | 1         | 5%      |
| 2013 | 1         | 5%      |
| 2010 | 1         | 5%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 20        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 16        | 80%     |
| Enabled  | 4         | 20%     |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 18        | 90%     |
| Yes  | 2         | 10%     |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 9         | 45%     |
| 3.01-4.0   | 3         | 15%     |
| 16.01-24.0 | 3         | 15%     |
| 8.01-16.0  | 3         | 15%     |
| 1.01-2.0   | 2         | 10%     |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 7         | 33.33%  |
| 2.01-3.0 | 5         | 23.81%  |
| 4.01-8.0 | 4         | 19.05%  |
| 3.01-4.0 | 3         | 14.29%  |
| 0.51-1.0 | 2         | 9.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 11        | 55%     |
| 2      | 7         | 35%     |
| 3      | 1         | 5%      |
| 0      | 1         | 5%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 15        | 75%     |
| Yes       | 5         | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 75%     |
| No        | 5         | 25%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 90%     |
| No        | 2         | 10%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 5         | 25%     |
| Germany      | 5         | 25%     |
| France       | 3         | 15%     |
| Spain        | 2         | 10%     |
| Venezuela    | 1         | 5%      |
| Sweden       | 1         | 5%      |
| South Africa | 1         | 5%      |
| Pakistan     | 1         | 5%      |
| India        | 1         | 5%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Queens        | 2         | 10%     |
| Hamburg       | 2         | 10%     |
| Uppsala       | 1         | 5%      |
| Parla         | 1         | 5%      |
| Paris         | 1         | 5%      |
| Mangalore     | 1         | 5%      |
| Lille         | 1         | 5%      |
| Land O' Lakes | 1         | 5%      |
| Lahore        | 1         | 5%      |
| Kennewick     | 1         | 5%      |
| Johannesburg  | 1         | 5%      |
| Guglingen     | 1         | 5%      |
| Guanare       | 1         | 5%      |
| Essen         | 1         | 5%      |
| Castelginest  | 1         | 5%      |
| Berlin        | 1         | 5%      |
| Barcelona     | 1         | 5%      |
| Austin        | 1         | 5%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 19.23%  |
| Samsung Electronics | 3         | 3      | 11.54%  |
| LITEONIT            | 2         | 2      | 7.69%   |
| Unknown             | 1         | 1      | 3.85%   |
| Union Memory        | 1         | 1      | 3.85%   |
| Toshiba             | 1         | 1      | 3.85%   |
| SSSTC               | 1         | 1      | 3.85%   |
| SK hynix            | 1         | 1      | 3.85%   |
| Seagate             | 1         | 1      | 3.85%   |
| Micron Technology   | 1         | 1      | 3.85%   |
| Kingston            | 1         | 1      | 3.85%   |
| Intel               | 1         | 1      | 3.85%   |
| Hitachi             | 1         | 1      | 3.85%   |
| HGST                | 1         | 1      | 3.85%   |
| EMTEC               | 1         | 2      | 3.85%   |
| Dell                | 1         | 2      | 3.85%   |
| China               | 1         | 1      | 3.85%   |
| ASMT                | 1         | 2      | 3.85%   |
| A-DATA Technology   | 1         | 1      | 3.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD10SPZX-24Z10 1TB                  | 2         | 7.69%   |
| WDC WD5000LPCX-21VHAT0 500GB            | 1         | 3.85%   |
| WDC WD10SPZX-60Z10T1 1TB                | 1         | 3.85%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB    | 1         | 3.85%   |
| Unknown SD/MMC/MS PRO 1TB               | 1         | 3.85%   |
| Union Memory UMIS RPITJ512VME2OWD 512GB | 1         | 3.85%   |
| Toshiba MK6475GSX 640GB                 | 1         | 3.85%   |
| SSSTC CL1-3D256 256GB                   | 1         | 3.85%   |
| SK hynix NVMe SSD Drive 256GB           | 1         | 3.85%   |
| Seagate ST250LM004 HN-M250MBB 250GB     | 1         | 3.85%   |
| Samsung SSD PM810 FDE 2.5 256GB         | 1         | 3.85%   |
| Samsung MZVLQ512HALU-00000 512GB        | 1         | 3.85%   |
| Samsung MZVLQ128HBHQ-000H1 128GB        | 1         | 3.85%   |
| Micron MTFDDAK256MAM-1K12 256GB SSD     | 1         | 3.85%   |
| LITEONIT LSS-16L6G-HP 16GB SSD          | 1         | 3.85%   |
| LITEONIT LGT-128M6G 128GB SSD           | 1         | 3.85%   |
| Kingston SA400S37240G 240GB SSD         | 1         | 3.85%   |
| Intel SSDSC2KF128G8L 128GB              | 1         | 3.85%   |
| Hitachi HTS545032B9A300 320GB           | 1         | 3.85%   |
| HGST HTS541010A9E680 1TB                | 1         | 3.85%   |
| EMTEC X200 256GB                        | 1         | 3.85%   |
| Dell WR202KD032G E70290F5 32GB          | 1         | 3.85%   |
| China SATA SSD 120GB                    | 1         | 3.85%   |
| ASMT 2105 250GB SSD                     | 1         | 3.85%   |
| A-DATA AXNS381E-256GM-B 256GB SSD       | 1         | 3.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 44.44%  |
| Unknown | 1         | 1      | 11.11%  |
| Toshiba | 1         | 1      | 11.11%  |
| Seagate | 1         | 1      | 11.11%  |
| Hitachi | 1         | 1      | 11.11%  |
| HGST    | 1         | 1      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| LITEONIT            | 2         | 2      | 20%     |
| Samsung Electronics | 1         | 1      | 10%     |
| Micron Technology   | 1         | 1      | 10%     |
| Kingston            | 1         | 1      | 10%     |
| Intel               | 1         | 1      | 10%     |
| Dell                | 1         | 2      | 10%     |
| China               | 1         | 1      | 10%     |
| ASMT                | 1         | 2      | 10%     |
| A-DATA Technology   | 1         | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 9         | 12     | 36%     |
| HDD     | 9         | 9      | 36%     |
| NVMe    | 6         | 6      | 24%     |
| Unknown | 1         | 2      | 4%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 15        | 18     | 65.22%  |
| NVMe | 6         | 6      | 26.09%  |
| SAS  | 2         | 5      | 8.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 12        | 15     | 66.67%  |
| 0.51-1.0   | 6         | 6      | 33.33%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 9         | 45%     |
| 251-500    | 5         | 25%     |
| 21-50      | 2         | 10%     |
| 501-1000   | 2         | 10%     |
| 1001-2000  | 1         | 5%      |
| 1-20       | 1         | 5%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 10        | 47.62%  |
| 21-50   | 7         | 33.33%  |
| 101-250 | 2         | 9.52%   |
| 251-500 | 1         | 4.76%   |
| 51-100  | 1         | 4.76%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| LITEONIT LSS-16L6G-HP 16GB SSD | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| LITEONIT | 1         | 1      | 100%    |

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
| SSD  | 1         | 1      | 100%    |

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
| Works    | 10        | 12     | 50%     |
| Detected | 9         | 16     | 45%     |
| Malfunc  | 1         | 1      | 5%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 13        | 54.17%  |
| AMD                            | 4         | 16.67%  |
| Union Memory (Shenzhen)        | 2         | 8.33%   |
| Samsung Electronics            | 2         | 8.33%   |
| Solid State Storage Technology | 1         | 4.17%   |
| SK hynix                       | 1         | 4.17%   |
| SanDisk                        | 1         | 4.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                   | 4         | 16.67%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                          | 3         | 12.5%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]      | 3         | 12.5%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                | 2         | 8.33%   |
| Samsung NVMe SSD Controller 980                                       | 2         | 8.33%   |
| Solid State Storage Non-Volatile memory controller                    | 1         | 4.17%   |
| SK hynix BC511                                                        | 1         | 4.17%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                            | 1         | 4.17%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                    | 1         | 4.17%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                    | 1         | 4.17%   |
| Intel Comet Lake SATA AHCI Controller                                 | 1         | 4.17%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                     | 1         | 4.17%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode] | 1         | 4.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                        | 1         | 4.17%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                  | 1         | 4.17%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 16        | 66.67%  |
| NVMe | 7         | 29.17%  |
| RAID | 1         | 4.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 15        | 75%     |
| AMD    | 5         | 25%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 15%     |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 5%      |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 5%      |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 5%      |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 5%      |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 5%      |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 5%      |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 5%      |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 5%      |
| Intel Core i3-8145U CPU @ 2.10GHz             | 1         | 5%      |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 5%      |
| Intel Celeron 2955U @ 1.40GHz                 | 1         | 5%      |
| Intel Atom CPU N455 @ 1.66GHz                 | 1         | 5%      |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 5%      |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 5%      |
| AMD Ryzen 3 3250U with Radeon Graphics        | 1         | 5%      |
| AMD A9-9420e RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 5%      |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G | 1         | 5%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 6         | 30%     |
| Intel Core i7           | 4         | 20%     |
| Intel Core i3           | 2         | 10%     |
| Other                   | 1         | 5%      |
| Intel Pentium Dual-Core | 1         | 5%      |
| Intel Celeron           | 1         | 5%      |
| Intel Atom              | 1         | 5%      |
| AMD Ryzen 7             | 1         | 5%      |
| AMD Ryzen 5             | 1         | 5%      |
| AMD Ryzen 3             | 1         | 5%      |
| AMD A6                  | 1         | 5%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 11        | 55%     |
| 4      | 6         | 30%     |
| 8      | 1         | 5%      |
| 6      | 1         | 5%      |
| 1      | 1         | 5%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 20        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 16        | 80%     |
| 1      | 4         | 20%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 20        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 4         | 20%     |
| 0x306a9    | 4         | 20%     |
| 0x40651    | 3         | 15%     |
| 0xa0652    | 1         | 5%      |
| 0x406e3    | 1         | 5%      |
| 0x106ca    | 1         | 5%      |
| 0x1067a    | 1         | 5%      |
| 0x08608103 | 1         | 5%      |
| 0x08108109 | 1         | 5%      |
| 0x0810100b | 1         | 5%      |
| 0x06006705 | 1         | 5%      |
| 0x06006704 | 1         | 5%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KabyLake  | 4         | 20%     |
| IvyBridge | 4         | 20%     |
| Haswell   | 3         | 15%     |
| Excavator | 2         | 10%     |
| Zen+      | 1         | 5%      |
| Zen       | 1         | 5%      |
| Skylake   | 1         | 5%      |
| Penryn    | 1         | 5%      |
| CometLake | 1         | 5%      |
| Bonnell   | 1         | 5%      |
| Unknown   | 1         | 5%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 13        | 59.09%  |
| AMD    | 5         | 22.73%  |
| Nvidia | 4         | 18.18%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                        | 3         | 13.64%  |
| Intel CometLake-U GT2 [UHD Graphics]                                    | 3         | 13.64%  |
| Intel 3rd Gen Core processor Graphics Controller                        | 2         | 9.09%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                | 2         | 9.09%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                              | 1         | 4.55%   |
| Nvidia GM108M [GeForce 930M]                                            | 1         | 4.55%   |
| Nvidia GK107GLM [Quadro K1000M]                                         | 1         | 4.55%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                       | 1         | 4.55%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                              | 1         | 4.55%   |
| Intel Skylake GT2 [HD Graphics 520]                                     | 1         | 4.55%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller            | 1         | 4.55%   |
| Intel CometLake-H GT2 [UHD Graphics]                                    | 1         | 4.55%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller | 1         | 4.55%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]        | 1         | 4.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]    | 1         | 4.55%   |
| AMD Lucienne                                                            | 1         | 4.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 11        | 55%     |
| 1 x AMD        | 5         | 25%     |
| 1 x Nvidia     | 2         | 10%     |
| Intel + Nvidia | 2         | 10%     |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 18        | 90%     |
| Proprietary | 2         | 10%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 12        | 60%     |
| 0.01-0.5   | 4         | 20%     |
| 1.01-2.0   | 3         | 15%     |
| 5.01-6.0   | 1         | 5%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 6         | 26.09%  |
| LG Display              | 5         | 21.74%  |
| Samsung Electronics     | 3         | 13.04%  |
| BOE                     | 2         | 8.7%    |
| Sharp                   | 1         | 4.35%   |
| Seiki                   | 1         | 4.35%   |
| PANDA                   | 1         | 4.35%   |
| InfoVision              | 1         | 4.35%   |
| Chimei Innolux          | 1         | 4.35%   |
| Chi Mei Optoelectronics | 1         | 4.35%   |
| BenQ                    | 1         | 4.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Sharp LC-32LB480U SHP3263 1920x1080 698x392mm 31.5-inch                  | 1         | 4.35%   |
| Seiki SC32HT04 SEK1366 1366x768 700x390mm 31.5-inch                      | 1         | 4.35%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 1         | 4.35%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch    | 1         | 4.35%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch     | 1         | 4.35%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 1         | 4.35%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 1         | 4.35%   |
| LG Display LCD Monitor LGD042D 1920x1080 290x170mm 13.2-inch             | 1         | 4.35%   |
| LG Display LCD Monitor LGD034A 1366x768 345x194mm 15.6-inch              | 1         | 4.35%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch              | 1         | 4.35%   |
| LG Display LCD Monitor LGD02A5 1366x768 345x194mm 15.6-inch              | 1         | 4.35%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 1         | 4.35%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 310x170mm 13.9-inch          | 1         | 4.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 1         | 4.35%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 1         | 4.35%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch                    | 1         | 4.35%   |
| BenQ GL2450 BNQ78A5 1920x1080 531x298mm 24.0-inch                        | 1         | 4.35%   |
| AU Optronics LCD Monitor AUOF992 1920x1080 382x215mm 17.3-inch           | 1         | 4.35%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch           | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch           | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO13ED 1920x1080 344x193mm 15.5-inch           | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch            | 1         | 4.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 14        | 60.87%  |
| 1366x768 (WXGA) | 7         | 30.43%  |
| 3840x2160 (4K)  | 2         | 8.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 10        | 43.48%  |
| 14     | 6         | 26.09%  |
| 31     | 2         | 8.7%    |
| 13     | 2         | 8.7%    |
| 24     | 1         | 4.35%   |
| 17     | 1         | 4.35%   |
| 11     | 1         | 4.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 16        | 69.57%  |
| 201-300     | 3         | 13.04%  |
| 601-700     | 2         | 8.7%    |
| 501-600     | 1         | 4.35%   |
| 351-400     | 1         | 4.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 20        | 100%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 10        | 43.48%  |
| 81-90          | 6         | 26.09%  |
| 71-80          | 2         | 8.7%    |
| 351-500        | 2         | 8.7%    |
| 51-60          | 1         | 4.35%   |
| 201-250        | 1         | 4.35%   |
| 121-130        | 1         | 4.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 11        | 47.83%  |
| 101-120       | 4         | 17.39%  |
| 51-100        | 4         | 17.39%  |
| More than 240 | 2         | 8.7%    |
| 1-50          | 1         | 4.35%   |
| 161-240       | 1         | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 17        | 85%     |
| 2     | 3         | 15%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 10        | 34.48%  |
| Realtek Semiconductor | 7         | 24.14%  |
| Qualcomm Atheros      | 5         | 17.24%  |
| Broadcom Limited      | 2         | 6.9%    |
| TP-Link               | 1         | 3.45%   |
| Sierra Wireless       | 1         | 3.45%   |
| Samsung Electronics   | 1         | 3.45%   |
| MediaTek              | 1         | 3.45%   |
| Broadcom              | 1         | 3.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 10.81%  |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 8.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 5.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 5.41%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 5.41%   |
| Intel Wireless 7260                                               | 2         | 5.41%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 5.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 5.41%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 2.7%    |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 2.7%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 2.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.7%    |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 2.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 2.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 2.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.7%    |
| MediaTek moto e(7) power                                          | 1         | 2.7%    |
| Intel Wireless 3165                                               | 1         | 2.7%    |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.7%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 2.7%    |
| Intel Centrino Wireless-N 2230                                    | 1         | 2.7%    |
| Intel Centrino Ultimate-N 6300                                    | 1         | 2.7%    |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 2.7%    |
| Broadcom Limited BCM43224 802.11a/b/g/n                           | 1         | 2.7%    |
| Broadcom BCM43225 802.11b/g/n                                     | 1         | 2.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 9         | 42.86%  |
| Qualcomm Atheros      | 5         | 23.81%  |
| Realtek Semiconductor | 4         | 19.05%  |
| Sierra Wireless       | 1         | 4.76%   |
| Broadcom Limited      | 1         | 4.76%   |
| Broadcom              | 1         | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Comet Lake PCH-LP CNVi WiFi                          | 3         | 14.29%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 2         | 9.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 9.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2         | 9.52%   |
| Intel Wireless 7260                                        | 2         | 9.52%   |
| Sierra Wireless EM7345 4G LTE                              | 1         | 4.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 4.76%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 1         | 4.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 4.76%   |
| Intel Wireless 3165                                        | 1         | 4.76%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 4.76%   |
| Intel Centrino Wireless-N 2230                             | 1         | 4.76%   |
| Intel Centrino Ultimate-N 6300                             | 1         | 4.76%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                    | 1         | 4.76%   |
| Broadcom BCM43225 802.11b/g/n                              | 1         | 4.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 6         | 37.5%   |
| Intel                 | 5         | 31.25%  |
| TP-Link               | 1         | 6.25%   |
| Samsung Electronics   | 1         | 6.25%   |
| Qualcomm Atheros      | 1         | 6.25%   |
| MediaTek              | 1         | 6.25%   |
| Broadcom Limited      | 1         | 6.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 25%     |
| Intel Ethernet Connection (10) I219-V                             | 2         | 12.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 12.5%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 6.25%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 6.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 6.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 6.25%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 6.25%   |
| MediaTek moto e(7) power                                          | 1         | 6.25%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 6.25%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 6.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 20        | 57.14%  |
| Ethernet | 15        | 42.86%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 14        | 60.87%  |
| Ethernet | 9         | 39.13%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 12        | 60%     |
| 1     | 8         | 40%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 15        | 75%     |
| Yes  | 5         | 25%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 8         | 44.44%  |
| Qualcomm Atheros Communications | 4         | 22.22%  |
| Realtek Semiconductor           | 3         | 16.67%  |
| Foxconn / Hon Hai               | 1         | 5.56%   |
| Cambridge Silicon Radio         | 1         | 5.56%   |
| Broadcom                        | 1         | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                  | 4         | 22.22%  |
| Intel AX201 Bluetooth                               | 4         | 22.22%  |
| Realtek Bluetooth Radio                             | 3         | 16.67%  |
| Intel Bluetooth wireless interface                  | 3         | 16.67%  |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 5.56%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 5.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 5.56%   |
| Broadcom HP Portable SoftSailing                    | 1         | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 15        | 57.69%  |
| AMD                  | 5         | 19.23%  |
| Nvidia               | 3         | 11.54%  |
| C-Media Electronics  | 2         | 7.69%   |
| Conrad Electronic SE | 1         | 3.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 4         | 11.76%  |
| Intel Haswell-ULT HD Audio Controller                               | 3         | 8.82%   |
| Intel Comet Lake PCH-LP cAVS                                        | 3         | 8.82%   |
| Intel 8 Series HD Audio Controller                                  | 3         | 8.82%   |
| AMD Family 17h/19h HD Audio Controller                              | 3         | 8.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 2         | 5.88%   |
| AMD High Definition Audio Controller                                | 2         | 5.88%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                    | 2         | 5.88%   |
| Nvidia TU116 High Definition Audio Controller                       | 1         | 2.94%   |
| Nvidia GK107 HDMI Audio Controller                                  | 1         | 2.94%   |
| Nvidia GF108 High Definition Audio Controller                       | 1         | 2.94%   |
| Intel Sunrise Point-LP HD Audio                                     | 1         | 2.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller             | 1         | 2.94%   |
| Intel Comet Lake PCH cAVS                                           | 1         | 2.94%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 1         | 2.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                      | 1         | 2.94%   |
| Conrad Electronic SE MIDI Cable UA0037                              | 1         | 2.94%   |
| C-Media Electronics USB PnP Sound Device                            | 1         | 2.94%   |
| C-Media Electronics CM106 Like Sound Device                         | 1         | 2.94%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 1         | 2.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 28.57%  |
| SK hynix            | 3         | 21.43%  |
| Micron Technology   | 2         | 14.29%  |
| Kingston            | 2         | 14.29%  |
| Unknown             | 1         | 7.14%   |
| Timetec             | 1         | 7.14%   |
| Elpida              | 1         | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 6.25%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                             | 1         | 6.25%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 6.25%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s                    | 1         | 6.25%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s              | 1         | 6.25%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s          | 1         | 6.25%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 6.25%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s                       | 1         | 6.25%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 6.25%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 1         | 6.25%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s                     | 1         | 6.25%   |
| Micron RAM 4ATF51264HZ-2G6E3 4GB SODIMM DDR4 2667MT/s                     | 1         | 6.25%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s                      | 1         | 6.25%   |
| Kingston RAM 787878787878787878787878787878787878 2GB SODIMM DDR2 667MT/s | 1         | 6.25%   |
| Kingston RAM 272727272727272727272727272727272727 2GB SODIMM DDR2 667MT/s | 1         | 6.25%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s                     | 1         | 6.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 4         | 36.36%  |
| DDR3   | 4         | 36.36%  |
| LPDDR3 | 2         | 18.18%  |
| DDR2   | 1         | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 8         | 72.73%  |
| Row Of Chips | 3         | 27.27%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 7         | 58.33%  |
| 8192  | 3         | 25%     |
| 16384 | 1         | 8.33%   |
| 2048  | 1         | 8.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 4         | 30.77%  |
| 3200  | 3         | 23.08%  |
| 2133  | 2         | 15.38%  |
| 2667  | 1         | 7.69%   |
| 1866  | 1         | 7.69%   |
| 1333  | 1         | 7.69%   |
| 667   | 1         | 7.69%   |

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
| Chicony Electronics                    | 8         | 40%     |
| IMC Networks                           | 4         | 20%     |
| Suyin                                  | 2         | 10%     |
| Acer                                   | 2         | 10%     |
| Realtek Semiconductor                  | 1         | 5%      |
| Microdia                               | 1         | 5%      |
| Luxvisions Innotech Limited            | 1         | 5%      |
| Cheng Uei Precision Industry (Foxlink) | 1         | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                  | 3         | 14.29%  |
| Chicony Integrated HP HD Webcam                                 | 2         | 9.52%   |
| Chicony HP Truevision HD                                        | 2         | 9.52%   |
| Suyin HD WebCam                                                 | 1         | 4.76%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)     | 1         | 4.76%   |
| Realtek EasyCamera                                              | 1         | 4.76%   |
| Microdia Integrated_Webcam_HD                                   | 1         | 4.76%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 1         | 4.76%   |
| IMC Networks USB2.0 HD IR UVC WebCam                            | 1         | 4.76%   |
| Chicony TOSHIBA Web Camera - HD                                 | 1         | 4.76%   |
| Chicony Lenovo EasyCamera                                       | 1         | 4.76%   |
| Chicony EasyCamera                                              | 1         | 4.76%   |
| Chicony 8M Camera                                               | 1         | 4.76%   |
| Chicony 720p HD Camera                                          | 1         | 4.76%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera | 1         | 4.76%   |
| Acer USB Camera                                                 | 1         | 4.76%   |
| Acer Integrated Camera                                          | 1         | 4.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 4         | 80%     |
| Elan Microelectronics | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS491                      | 2         | 40%     |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 20%     |
| Validity Sensors Fingerprint scanner         | 1         | 20%     |
| Elan ELAN:ARM-M4                             | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 14        | 70%     |
| 1     | 4         | 20%     |
| 2     | 2         | 10%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 5         | 62.5%   |
| Net/wireless          | 1         | 12.5%   |
| Multimedia controller | 1         | 12.5%   |
| Chipcard              | 1         | 12.5%   |

