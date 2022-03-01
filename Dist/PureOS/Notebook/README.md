PureOS - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for PureOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 15-3567            | [c8723d2dd9](https://linux-hardware.org/?probe=c8723d2dd9) | Feb 21, 2022 |
| Dell          | Inspiron 15-3567            | [45529bb469](https://linux-hardware.org/?probe=45529bb469) | Feb 21, 2022 |
| Lenovo        | ThinkPad T540p 20BFS23T0... | [c49acb0edf](https://linux-hardware.org/?probe=c49acb0edf) | Feb 21, 2022 |
| Lenovo        | ThinkPad T540p 20BFS23T0... | [6f13abc9eb](https://linux-hardware.org/?probe=6f13abc9eb) | Feb 21, 2022 |
| Acer          | Aspire E5-553G              | [1f5badca6e](https://linux-hardware.org/?probe=1f5badca6e) | Feb 06, 2022 |
| Lenovo        | ThinkPad E480 20KN003SUS    | [ad043b077a](https://linux-hardware.org/?probe=ad043b077a) | Nov 25, 2021 |
| Apple         | MacBookPro14,2              | [5f4d435f0d](https://linux-hardware.org/?probe=5f4d435f0d) | Nov 24, 2021 |
| Purism        | Librem 14                   | [68e8f5b427](https://linux-hardware.org/?probe=68e8f5b427) | Sep 27, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [077ff209de](https://linux-hardware.org/?probe=077ff209de) | Aug 18, 2021 |
| Purism        | Librem 14                   | [295a2a1392](https://linux-hardware.org/?probe=295a2a1392) | Jul 15, 2021 |
| Purism        | Librem 14                   | [49d9b561c6](https://linux-hardware.org/?probe=49d9b561c6) | Jul 15, 2021 |
| Toshiba       | Satellite L500D             | [b830927060](https://linux-hardware.org/?probe=b830927060) | Jul 04, 2021 |
| Dell          | XPS 13 9370                 | [c8937f439d](https://linux-hardware.org/?probe=c8937f439d) | Jun 09, 2021 |
| Purism        | Librem 14                   | [0c18b37b73](https://linux-hardware.org/?probe=0c18b37b73) | Jun 01, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [79c01fbf3a](https://linux-hardware.org/?probe=79c01fbf3a) | Oct 28, 2020 |
| Unknown       | Unknown                     | [c24817ee80](https://linux-hardware.org/?probe=c24817ee80) | Sep 15, 2020 |
| Unknown       | Purism Librem 5             | [2c6b84a04f](https://linux-hardware.org/?probe=2c6b84a04f) | Jul 23, 2020 |
| HP            | Pavilion g6                 | [eb23d17143](https://linux-hardware.org/?probe=eb23d17143) | Jul 15, 2020 |
| Lenovo        | ThinkPad T440 20B60044RT    | [db8ba33d45](https://linux-hardware.org/?probe=db8ba33d45) | Jun 02, 2020 |
| Purism        | Librem 15 v4                | [d9f38d66c3](https://linux-hardware.org/?probe=d9f38d66c3) | Apr 29, 2020 |
| Notebook      | P17SM                       | [730c65e65d](https://linux-hardware.org/?probe=730c65e65d) | Apr 22, 2020 |
| Purism        | Librem 15 v4                | [6e5f1119b7](https://linux-hardware.org/?probe=6e5f1119b7) | Apr 10, 2020 |
| Purism        | Librem 15 v3                | [a43311f999](https://linux-hardware.org/?probe=a43311f999) | Dec 18, 2019 |
| Purism        | Librem 13 v4                | [6d7a537e86](https://linux-hardware.org/?probe=6d7a537e86) | Nov 15, 2019 |
| Dell          | Inspiron 5547               | [689dfea547](https://linux-hardware.org/?probe=689dfea547) | Oct 25, 2019 |
| Purism        | Librem 13 v4                | [6d7c18d329](https://linux-hardware.org/?probe=6d7c18d329) | Oct 18, 2019 |
| Lenovo        | G505s 20255                 | [bce345b263](https://linux-hardware.org/?probe=bce345b263) | Aug 30, 2019 |
| Purism        | Librem 13 v2                | [3e70a8dff1](https://linux-hardware.org/?probe=3e70a8dff1) | Jul 13, 2019 |
| Purism        | Librem 15 v3                | [02e23b6024](https://linux-hardware.org/?probe=02e23b6024) | May 21, 2018 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Notebooks | Percent |
|----------------------------------|-----------|---------|
| 4.19.0-5-amd64                   | 8         | 36.36%  |
| 5.10.0-8-amd64                   | 3         | 13.64%  |
| 5.7.0-1-librem5                  | 2         | 9.09%   |
| 5.10.0-7-amd64                   | 2         | 9.09%   |
| 5.10.0-11-amd64                  | 2         | 9.09%   |
| 5.7.0-0.38-1-pinebookpro-hwaccel | 1         | 4.55%   |
| 5.10.0-9-amd64                   | 1         | 4.55%   |
| 5.10.0-6-amd64                   | 1         | 4.55%   |
| 4.19.0-14-amd64                  | 1         | 4.55%   |
| 4.16.0-1-amd64                   | 1         | 4.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 9         | 40.91%  |
| 4.19.0  | 9         | 40.91%  |
| 5.7.0   | 3         | 13.64%  |
| 4.16.0  | 1         | 4.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 9         | 40.91%  |
| 4.19    | 9         | 40.91%  |
| 5.7     | 3         | 13.64%  |
| 4.16    | 1         | 4.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 18        | 85.71%  |
| aarch64 | 3         | 14.29%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 16        | 72.73%  |
| Unknown         | 4         | 18.18%  |
| KDE5            | 1         | 4.55%   |
| GNOME Flashback | 1         | 4.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 14        | 63.64%  |
| Unknown | 4         | 18.18%  |
| X11     | 2         | 9.09%   |
| Tty     | 2         | 9.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 14        | 66.67%  |
| GDM     | 7         | 33.33%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 13        | 56.52%  |
| Unknown | 4         | 17.39%  |
| de_DE   | 2         | 8.7%    |
| zh_CN   | 1         | 4.35%   |
| pt_PT   | 1         | 4.35%   |
| it_IT   | 1         | 4.35%   |
| en_GB   | 1         | 4.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 19        | 90.48%  |
| EFI  | 2         | 9.52%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 18        | 85.71%  |
| Unknown | 2         | 9.52%   |
| Ext2    | 1         | 4.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 12        | 57.14%  |
| MBR     | 7         | 33.33%  |
| GPT     | 2         | 9.52%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 17        | 80.95%  |
| Yes       | 4         | 19.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 20        | 95.24%  |
| Yes       | 1         | 4.76%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Purism            | 7         | 33.33%  |
| Lenovo            | 4         | 19.05%  |
| Dell              | 3         | 14.29%  |
| Unknown           | 2         | 9.52%   |
| Toshiba           | 1         | 4.76%   |
| Pine Microsystems | 1         | 4.76%   |
| Notebook          | 1         | 4.76%   |
| Hewlett-Packard   | 1         | 4.76%   |
| Apple             | 1         | 4.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Purism Librem 14                      | 3         | 14.29%  |
| Unknown                               | 2         | 9.52%   |
| Toshiba Satellite L500D               | 1         | 4.76%   |
| Purism Librem 15 v4                   | 1         | 4.76%   |
| Purism Librem 15 v3                   | 1         | 4.76%   |
| Purism Librem 13 v4                   | 1         | 4.76%   |
| Purism Librem 13 v2                   | 1         | 4.76%   |
| Pine Microsystems Pine64 Pinebook Pro | 1         | 4.76%   |
| Notebook P17SM                        | 1         | 4.76%   |
| Lenovo ThinkPad T540p 20BFS23T00      | 1         | 4.76%   |
| Lenovo ThinkPad T440 20B60044RT       | 1         | 4.76%   |
| Lenovo ThinkPad E480 20KN003SUS       | 1         | 4.76%   |
| Lenovo ThinkPad 13 2nd Gen 20J2S00G00 | 1         | 4.76%   |
| HP Pavilion g6                        | 1         | 4.76%   |
| Dell XPS 13 9370                      | 1         | 4.76%   |
| Dell Inspiron 5547                    | 1         | 4.76%   |
| Dell Inspiron 15-3567                 | 1         | 4.76%   |
| Apple MacBookPro14,2                  | 1         | 4.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Purism Librem            | 7         | 33.33%  |
| Lenovo ThinkPad          | 4         | 19.05%  |
| Dell Inspiron            | 2         | 9.52%   |
| Unknown                  | 2         | 9.52%   |
| Toshiba Satellite        | 1         | 4.76%   |
| Pine Microsystems Pine64 | 1         | 4.76%   |
| Notebook P17SM           | 1         | 4.76%   |
| HP Pavilion              | 1         | 4.76%   |
| Dell XPS                 | 1         | 4.76%   |
| Apple MacBookPro14       | 1         | 4.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2017    | 4         | 19.05%  |
| Unknown | 4         | 19.05%  |
| 2013    | 3         | 14.29%  |
| 2021    | 2         | 9.52%   |
| 2019    | 2         | 9.52%   |
| 2018    | 2         | 9.52%   |
| 2016    | 1         | 4.76%   |
| 2014    | 1         | 4.76%   |
| 2011    | 1         | 4.76%   |
| 2009    | 1         | 4.76%   |

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
| Disabled | 21        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 14        | 66.67%  |
| Yes  | 7         | 33.33%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 16.01-24.0 | 7         | 33.33%  |
| 4.01-8.0   | 4         | 19.05%  |
| 32.01-64.0 | 3         | 14.29%  |
| 3.01-4.0   | 2         | 9.52%   |
| 2.01-3.0   | 2         | 9.52%   |
| 8.01-16.0  | 2         | 9.52%   |
| 24.01-32.0 | 1         | 4.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 3.01-4.0  | 8         | 34.78%  |
| 2.01-3.0  | 7         | 30.43%  |
| 1.01-2.0  | 4         | 17.39%  |
| 4.01-8.0  | 2         | 8.7%    |
| 8.01-16.0 | 1         | 4.35%   |
| 0.51-1.0  | 1         | 4.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 14        | 66.67%  |
| 2      | 7         | 33.33%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 17        | 80.95%  |
| Yes       | 4         | 19.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 14        | 66.67%  |
| No        | 7         | 33.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 17        | 80.95%  |
| No        | 4         | 19.05%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 14        | 66.67%  |
| No        | 7         | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| USA                    | 5         | 21.74%  |
| Germany                | 3         | 13.04%  |
| Canada                 | 3         | 13.04%  |
| UK                     | 2         | 8.7%    |
| Turkey                 | 1         | 4.35%   |
| South Africa           | 1         | 4.35%   |
| Portugal               | 1         | 4.35%   |
| Poland                 | 1         | 4.35%   |
| Italy                  | 1         | 4.35%   |
| France                 | 1         | 4.35%   |
| China                  | 1         | 4.35%   |
| Brazil                 | 1         | 4.35%   |
| Bosnia and Herzegovina | 1         | 4.35%   |
| Australia              | 1         | 4.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Xi'an         | 1         | 4.35%   |
| Windsor       | 1         | 4.35%   |
| Warsaw        | 1         | 4.35%   |
| Viadanica     | 1         | 4.35%   |
| Vancouver     | 1         | 4.35%   |
| Tupa          | 1         | 4.35%   |
| Thorpe Hamlet | 1         | 4.35%   |
| Stuttgart     | 1         | 4.35%   |
| Seattle       | 1         | 4.35%   |
| Paris         | 1         | 4.35%   |
| New York      | 1         | 4.35%   |
| Nashville     | 1         | 4.35%   |
| Montreal      | 1         | 4.35%   |
| Lottstetten   | 1         | 4.35%   |
| London        | 1         | 4.35%   |
| Istanbul      | 1         | 4.35%   |
| GuimarÃ£es  | 1         | 4.35%   |
| East Malvern  | 1         | 4.35%   |
| Cape Town     | 1         | 4.35%   |
| Big Sky       | 1         | 4.35%   |
| Berlin        | 1         | 4.35%   |
| Banja Luka    | 1         | 4.35%   |
| Avon          | 1         | 4.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 12     | 29.63%  |
| Unknown             | 3         | 3      | 11.11%  |
| Seagate             | 3         | 3      | 11.11%  |
| Crucial             | 2         | 3      | 7.41%   |
| WDC                 | 1         | 1      | 3.7%    |
| Toshiba             | 1         | 1      | 3.7%    |
| SanDisk             | 1         | 1      | 3.7%    |
| PLEXTOR             | 1         | 1      | 3.7%    |
| Phison              | 1         | 1      | 3.7%    |
| Mushkin             | 1         | 1      | 3.7%    |
| Hitachi             | 1         | 1      | 3.7%    |
| HGST                | 1         | 1      | 3.7%    |
| BIWIN               | 1         | 1      | 3.7%    |
| Apple               | 1         | 2      | 3.7%    |
| ADATA Technology    | 1         | 1      | 3.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM048-2E7172 1TB      | 2         | 6.9%    |
| WDC WDS100T2B0C-00PXH0 1TB          | 1         | 3.45%   |
| Unknown MMC Card  32GB              | 1         | 3.45%   |
| Unknown DA4128  128GB               | 1         | 3.45%   |
| Unknown 032G32  32GB                | 1         | 3.45%   |
| Toshiba NVMe SSD Drive 512GB        | 1         | 3.45%   |
| Seagate NVMe SSD Drive 2TB          | 1         | 3.45%   |
| SanDisk SDSSDH3500G 500GB           | 1         | 3.45%   |
| Samsung SSD 970 PRO 1TB             | 1         | 3.45%   |
| Samsung SSD 970 EVO 250GB           | 1         | 3.45%   |
| Samsung SSD 960 EVO 500GB           | 1         | 3.45%   |
| Samsung SSD 960 EVO 250GB           | 1         | 3.45%   |
| Samsung SSD 860 EVO 500GB           | 1         | 3.45%   |
| Samsung SSD 860 EVO 250GB           | 1         | 3.45%   |
| Samsung SSD 860 EVO 1TB             | 1         | 3.45%   |
| Samsung SSD 850 EVO 500GB           | 1         | 3.45%   |
| Samsung SSD 850 EVO 250GB           | 1         | 3.45%   |
| PLEXTOR PX-1TM6Pro 1024GB SSD       | 1         | 3.45%   |
| Phison PM8512GPTCB4B8TF-E13T4 512GB | 1         | 3.45%   |
| Mushkin MKNSSDRE250GB-LT            | 1         | 3.45%   |
| Hitachi HTS545050A7E380 500GB       | 1         | 3.45%   |
| HGST HTS545050B7E660 500GB          | 1         | 3.45%   |
| Crucial CT250MX500SSD4 250GB        | 1         | 3.45%   |
| Crucial CT2000MX500SSD1 2TB         | 1         | 3.45%   |
| BIWIN SSD 120GB                     | 1         | 3.45%   |
| Apple NVMe SSD Drive 8KB            | 1         | 3.45%   |
| Apple NVMe SSD Drive 256GB          | 1         | 3.45%   |
| ADATA NVMe SSD Drive 512GB          | 1         | 3.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 50%     |
| Hitachi | 1         | 1      | 25%     |
| HGST    | 1         | 1      | 25%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 8      | 50%     |
| Crucial             | 2         | 3      | 16.67%  |
| SanDisk             | 1         | 1      | 8.33%   |
| PLEXTOR             | 1         | 1      | 8.33%   |
| Mushkin             | 1         | 1      | 8.33%   |
| BIWIN               | 1         | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 10        | 15     | 38.46%  |
| NVMe | 9         | 11     | 34.62%  |
| HDD  | 4         | 4      | 15.38%  |
| MMC  | 3         | 3      | 11.54%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 12        | 18     | 48%     |
| NVMe | 9         | 11     | 36%     |
| MMC  | 3         | 3      | 12%     |
| SAS  | 1         | 1      | 4%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 8         | 14     | 61.54%  |
| 0.51-1.0   | 3         | 3      | 23.08%  |
| 1.01-2.0   | 2         | 2      | 15.38%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 9         | 42.86%  |
| 251-500    | 2         | 9.52%   |
| 21-50      | 2         | 9.52%   |
| 101-250    | 2         | 9.52%   |
| 501-1000   | 2         | 9.52%   |
| Unknown    | 2         | 9.52%   |
| 1001-2000  | 1         | 4.76%   |
| 51-100     | 1         | 4.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 12        | 57.14%  |
| 21-50    | 3         | 14.29%  |
| 501-1000 | 2         | 9.52%   |
| Unknown  | 2         | 9.52%   |
| 251-500  | 1         | 4.76%   |
| 51-100   | 1         | 4.76%   |

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
| Detected | 14        | 22     | 66.67%  |
| Works    | 7         | 11     | 33.33%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 11        | 52.38%  |
| Samsung Electronics          | 3         | 14.29%  |
| Toshiba America Info Systems | 1         | 4.76%   |
| Seagate Technology           | 1         | 4.76%   |
| Sandisk                      | 1         | 4.76%   |
| Phison Electronics           | 1         | 4.76%   |
| Apple                        | 1         | 4.76%   |
| AMD                          | 1         | 4.76%   |
| ADATA Technology             | 1         | 4.76%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 28.57%  |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 9.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 9.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 9.52%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 4.76%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 4.76%   |
| Sandisk Non-Volatile memory controller                                         | 1         | 4.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 4.76%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 4.76%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 4.76%   |
| Apple S3X NVMe Controller                                                      | 1         | 4.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 4.76%   |
| ADATA Non-Volatile memory controller                                           | 1         | 4.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 12        | 57.14%  |
| NVMe | 9         | 42.86%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 17        | 80.95%  |
| ARM    | 3         | 14.29%  |
| AMD    | 1         | 4.76%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz   | 3         | 14.29%  |
| Intel Core i7-10710U CPU @ 1.10GHz  | 3         | 14.29%  |
| ARM Processor                       | 3         | 14.29%  |
| Intel Core i7-6500U CPU @ 2.50GHz   | 2         | 9.52%   |
| Intel Core i5-7200U CPU @ 2.50GHz   | 2         | 9.52%   |
| Intel Core i7-8550U CPU @ 1.80GHz   | 1         | 4.76%   |
| Intel Core i7-7567U CPU @ 3.50GHz   | 1         | 4.76%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz  | 1         | 4.76%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz  | 1         | 4.76%   |
| Intel Core i7-4510U CPU @ 2.00GHz   | 1         | 4.76%   |
| Intel Core i3-4010U CPU @ 1.70GHz   | 1         | 4.76%   |
| Intel Core i3-3120M CPU @ 2.50GHz   | 1         | 4.76%   |
| AMD Turion II Dual-Core Mobile M520 | 1         | 4.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 13        | 61.9%   |
| Other                   | 3         | 14.29%  |
| Intel Core i5           | 2         | 9.52%   |
| Intel Core i3           | 2         | 9.52%   |
| AMD Turion II Dual-Core | 1         | 4.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 12        | 57.14%  |
| 4      | 6         | 28.57%  |
| 6      | 3         | 14.29%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 21        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 17        | 80.95%  |
| 1      | 4         | 19.05%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 18        | 81.82%  |
| Unknown        | 4         | 18.18%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 15        | 71.43%  |
| 0xa0660 | 2         | 9.52%   |
| 0x406e3 | 2         | 9.52%   |
| 0x806e9 | 1         | 4.76%   |
| 0x40651 | 1         | 4.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KabyLake  | 7         | 33.33%  |
| Haswell   | 4         | 19.05%  |
| CometLake | 3         | 14.29%  |
| Unknown   | 3         | 14.29%  |
| Skylake   | 2         | 9.52%   |
| K10       | 1         | 4.76%   |
| IvyBridge | 1         | 4.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 17        | 77.27%  |
| AMD    | 3         | 13.64%  |
| Nvidia | 2         | 9.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                 | 5         | 22.73%  |
| Intel Comet Lake UHD Graphics                                                         | 3         | 13.64%  |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 9.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 9.09%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 2         | 9.09%   |
| Nvidia GK208M [GeForce GT 730M]                                                       | 1         | 4.55%   |
| Nvidia GK104M [GeForce GTX 870M]                                                      | 1         | 4.55%   |
| Intel UHD Graphics 620                                                                | 1         | 4.55%   |
| Intel Iris Plus Graphics 650                                                          | 1         | 4.55%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 1         | 4.55%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 4.55%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 1         | 4.55%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                             | 1         | 4.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 13        | 61.9%   |
| Other          | 3         | 14.29%  |
| Intel + Nvidia | 2         | 9.52%   |
| Intel + AMD    | 2         | 9.52%   |
| 1 x AMD        | 1         | 4.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 17        | 80.95%  |
| Unknown | 4         | 19.05%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 4         | 16.67%  |
| BOE                     | 4         | 16.67%  |
| LG Display              | 3         | 12.5%   |
| Chimei Innolux          | 3         | 12.5%   |
| AU Optronics            | 2         | 8.33%   |
| Unknown                 | 1         | 4.17%   |
| Sharp                   | 1         | 4.17%   |
| Lenovo                  | 1         | 4.17%   |
| Goldstar                | 1         | 4.17%   |
| Chi Mei Optoelectronics | 1         | 4.17%   |
| BenQ                    | 1         | 4.17%   |
| Apple                   | 1         | 4.17%   |
| Acer                    | 1         | 4.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch     | 2         | 8.33%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 2         | 8.33%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 1         | 4.17%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                   | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch      | 1         | 4.17%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 1         | 4.17%   |
| LG Display LCD Monitor LGD053B 1920x1080 294x165mm 13.3-inch              | 1         | 4.17%   |
| LG Display LCD Monitor LGD03F0 1366x768 310x174mm 14.0-inch               | 1         | 4.17%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch               | 1         | 4.17%   |
| Lenovo LEN Y44w-10 LEN65EA 3840x1200 1052x329mm 43.4-inch                 | 1         | 4.17%   |
| Goldstar IPS231 GSM5817 1920x1080 510x290mm 23.1-inch                     | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 1         | 4.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 4.17%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 1         | 4.17%   |
| BOE LCD Monitor BOE06C2 1366x768 344x194mm 15.5-inch                      | 1         | 4.17%   |
| BOE LCD Monitor BOE06BE 1920x1080 294x165mm 13.3-inch                     | 1         | 4.17%   |
| BOE LCD Monitor BOE0641 1920x1080 344x193mm 15.5-inch                     | 1         | 4.17%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                         | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO713C 1366x768 309x173mm 13.9-inch             | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 344x193mm 15.5-inch            | 1         | 4.17%   |
| Apple Color LCD APPA034 2880x1800 286x179mm 13.3-inch                     | 1         | 4.17%   |
| Acer H236HL ACR0318 1920x1080 509x286mm 23.0-inch                         | 1         | 4.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 10        | 47.62%  |
| 1366x768 (WXGA) | 5         | 23.81%  |
| 3840x2160 (4K)  | 3         | 14.29%  |
| 3840x1200       | 1         | 4.76%   |
| 2880x1800       | 1         | 4.76%   |
| 2288x1287       | 1         | 4.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 8         | 33.33%  |
| 13     | 7         | 29.17%  |
| 23     | 2         | 8.33%   |
| 14     | 2         | 8.33%   |
| 142    | 1         | 4.17%   |
| 43     | 1         | 4.17%   |
| 27     | 1         | 4.17%   |
| 24     | 1         | 4.17%   |
| 17     | 1         | 4.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 11        | 47.83%  |
| 501-600        | 4         | 17.39%  |
| 201-300        | 4         | 17.39%  |
| 351-400        | 2         | 8.7%    |
| More than 2000 | 1         | 4.35%   |
| 1001-1500      | 1         | 4.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 16        | 84.21%  |
| 3.20  | 1         | 5.26%   |
| 16/10 | 1         | 5.26%   |
| 1.00  | 1         | 5.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 8         | 33.33%  |
| 81-90          | 5         | 20.83%  |
| 71-80          | 4         | 16.67%  |
| 201-250        | 3         | 12.5%   |
| More than 1000 | 1         | 4.17%   |
| 301-350        | 1         | 4.17%   |
| 121-130        | 1         | 4.17%   |
| 501-1000       | 1         | 4.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 7         | 29.17%  |
| 51-100        | 6         | 25%     |
| More than 240 | 4         | 16.67%  |
| 101-120       | 4         | 16.67%  |
| 161-240       | 2         | 8.33%   |
| 1-50          | 1         | 4.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 14        | 66.67%  |
| 2     | 4         | 19.05%  |
| 0     | 2         | 9.52%   |
| 3     | 1         | 4.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 11        | 37.93%  |
| Qualcomm Atheros      | 10        | 34.48%  |
| Intel                 | 3         | 10.34%  |
| ASIX Electronics      | 2         | 6.9%    |
| Ralink                | 1         | 3.45%   |
| MediaTek              | 1         | 3.45%   |
| Broadcom              | 1         | 3.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 8         | 23.53%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 14.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 11.76%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 5.88%   |
| Intel Wireless 7260                                               | 2         | 5.88%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 5.88%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 2.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 2.94%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 2.94%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 2.94%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1         | 2.94%   |
| MediaTek WiFi                                                     | 1         | 2.94%   |
| Intel Wireless 8265 / 8275                                        | 1         | 2.94%   |
| Intel Ethernet Connection I218-V                                  | 1         | 2.94%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.94%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.94%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 2.94%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 10        | 50%     |
| Realtek Semiconductor | 4         | 20%     |
| Intel                 | 3         | 15%     |
| Ralink                | 1         | 5%      |
| MediaTek              | 1         | 5%      |
| Broadcom              | 1         | 5%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 8         | 40%     |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 2         | 10%     |
| Intel Wireless 7260                                        | 2         | 10%     |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1         | 5%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 5%      |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter    | 1         | 5%      |
| Realtek RTL8191SEvB Wireless LAN Controller                | 1         | 5%      |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter     | 1         | 5%      |
| MediaTek WiFi                                              | 1         | 5%      |
| Intel Wireless 8265 / 8275                                 | 1         | 5%      |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                | 1         | 5%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 9         | 64.29%  |
| Intel                 | 3         | 21.43%  |
| ASIX Electronics      | 2         | 14.29%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 35.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 28.57%  |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 14.29%  |
| Intel Ethernet Connection I218-V                                  | 1         | 7.14%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 7.14%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 7.14%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 17        | 56.67%  |
| Ethernet | 13        | 43.33%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 13        | 52%     |
| WiFi     | 12        | 48%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 12        | 57.14%  |
| 1     | 5         | 23.81%  |
| 0     | 4         | 19.05%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 17        | 80.95%  |
| Yes  | 4         | 19.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Lite-On Technology              | 4         | 26.67%  |
| Foxconn / Hon Hai               | 3         | 20%     |
| Qualcomm Atheros Communications | 2         | 13.33%  |
| Intel                           | 2         | 13.33%  |
| Realtek Semiconductor           | 1         | 6.67%   |
| Qualcomm Atheros                | 1         | 6.67%   |
| Cambridge Silicon Radio         | 1         | 6.67%   |
| ASUSTek Computer                | 1         | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 26.67%  |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 20%     |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 13.33%  |
| Realtek Bluetooth Radio                             | 1         | 6.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 6.67%   |
| Intel Bluetooth wireless interface                  | 1         | 6.67%   |
| Intel Bluetooth Device                              | 1         | 6.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 6.67%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Intel    | 17        | 77.27%  |
| XMOS     | 1         | 4.55%   |
| Shure    | 1         | 4.55%   |
| M-Audio  | 1         | 4.55%   |
| Logitech | 1         | 4.55%   |
| AMD      | 1         | 4.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                     | 9         | 34.62%  |
| Intel Comet Lake PCH-LP cAVS                                        | 3         | 11.54%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 2         | 7.69%   |
| Intel Haswell-ULT HD Audio Controller                               | 2         | 7.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 2         | 7.69%   |
| Intel 8 Series HD Audio Controller                                  | 2         | 7.69%   |
| XMOS xCORE USB Audio 2.0                                            | 1         | 3.85%   |
| Shure MV5                                                           | 1         | 3.85%   |
| M-Audio M-Audio Fast Track MKII                                     | 1         | 3.85%   |
| Logitech Headset H340                                               | 1         | 3.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 1         | 3.85%   |
| AMD SBx00 Azalia (Intel HDA)                                        | 1         | 3.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Crucial             | 3         | 37.5%   |
| SK Hynix            | 2         | 25%     |
| Unknown             | 1         | 12.5%   |
| Toshiba             | 1         | 12.5%   |
| Samsung Electronics | 1         | 12.5%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 16384MB 2133MT/s                        | 1         | 11.11%  |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s         | 1         | 11.11%  |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s          | 1         | 11.11%  |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s  | 1         | 11.11%  |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s  | 1         | 11.11%  |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s     | 1         | 11.11%  |
| Crucial RAM CT4G4SFS8213.C8FBD1 4GB SODIMM DDR4 2133MT/s   | 1         | 11.11%  |
| Crucial RAM CT16G4SFD824A.M16FRS 16GB SODIMM DDR4 2400MT/s | 1         | 11.11%  |
| Crucial RAM CT16G4S24AM.M16FE 16GB SODIMM DDR4 2400MT/s    | 1         | 11.11%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 4         | 57.14%  |
| DDR3    | 1         | 14.29%  |
| DDR2    | 1         | 14.29%  |
| Unknown | 1         | 14.29%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SODIMM  | 6         | 85.71%  |
| Unknown | 1         | 14.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 16384 | 3         | 37.5%   |
| 8192  | 2         | 25%     |
| 4096  | 2         | 25%     |
| 32768 | 1         | 12.5%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 2         | 25%     |
| 2400  | 2         | 25%     |
| 2133  | 2         | 25%     |
| 1600  | 1         | 12.5%   |
| 1066  | 1         | 12.5%   |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 3         | 21.43%  |
| Acer                          | 3         | 21.43%  |
| Sunplus Innovation Technology | 2         | 14.29%  |
| Alcor Micro                   | 2         | 14.29%  |
| Microdia                      | 1         | 7.14%   |
| Lite-On Technology            | 1         | 7.14%   |
| Chicony Electronics           | 1         | 7.14%   |
| Apple                         | 1         | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Alcor Micro HD WebCam                 | 2         | 13.33%  |
| Sunplus Integrated_Webcam_HD          | 1         | 6.67%   |
| Sunplus Integrated Camera             | 1         | 6.67%   |
| Realtek Integrated_Webcam_HD          | 1         | 6.67%   |
| Realtek Integrated Webcam             | 1         | 6.67%   |
| Realtek HP Truevision HD              | 1         | 6.67%   |
| Microdia HP Integrated Webcam         | 1         | 6.67%   |
| Lite-On Integrated Camera             | 1         | 6.67%   |
| Chicony USB2.0 UVC WebCam             | 1         | 6.67%   |
| Apple iPhone 5/5C/5S/6/SE             | 1         | 6.67%   |
| Apple iBridge                         | 1         | 6.67%   |
| Acer SunplusIT Integrated Camera      | 1         | 6.67%   |
| Acer SunplusIT INC. Integrated Camera | 1         | 6.67%   |
| Acer BisonCam, NB Pro                 | 1         | 6.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 2         | 50%     |
| Synaptics             | 1         | 25%     |
| LighTuning Technology | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor     | 2         | 50%     |
| Synaptics Metallica MOH Touch Fingerprint Reader | 1         | 25%     |
| LighTuning ES603 Swipe Fingerprint Sensor        | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Purism, SPC | 2         | 50%     |
| Clay Logic  | 1         | 25%     |
| Alcor Micro | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Purism, SPC Librem Key              | 2         | 50%     |
| Clay Logic Nitrokey Pro             | 1         | 25%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 9         | 42.86%  |
| 0     | 8         | 38.1%   |
| 2     | 2         | 9.52%   |
| 4     | 1         | 4.76%   |
| 3     | 1         | 4.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Bluetooth             | 5         | 25%     |
| Net/wireless          | 4         | 20%     |
| Graphics card         | 4         | 20%     |
| Fingerprint reader    | 4         | 20%     |
| Multimedia controller | 1         | 5%      |
| Chipcard              | 1         | 5%      |
| Camera                | 1         | 5%      |

