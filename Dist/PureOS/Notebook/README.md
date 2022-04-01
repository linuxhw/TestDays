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

Total: 30

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Nitro AN515-43              | [e1386a38c7](https://linux-hardware.org/?probe=e1386a38c7) | Mar 20, 2022 |
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

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| PureOS 9.0  | 8         | 34.78%  |
| PureOS 10.0 | 6         | 26.09%  |
| PureOS 10   | 5         | 21.74%  |
| PureOS 9    | 2         | 8.7%    |
| PureOS 8    | 2         | 8.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| PureOS | 22        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Notebooks | Percent |
|----------------------------------|-----------|---------|
| 4.19.0-5-amd64                   | 8         | 34.78%  |
| 5.10.0-8-amd64                   | 3         | 13.04%  |
| 5.7.0-1-librem5                  | 2         | 8.7%    |
| 5.10.0-7-amd64                   | 2         | 8.7%    |
| 5.10.0-11-amd64                  | 2         | 8.7%    |
| 5.7.0-0.38-1-pinebookpro-hwaccel | 1         | 4.35%   |
| 5.10.0-9-amd64                   | 1         | 4.35%   |
| 5.10.0-6-amd64                   | 1         | 4.35%   |
| 5.10.0-12-amd64                  | 1         | 4.35%   |
| 4.19.0-14-amd64                  | 1         | 4.35%   |
| 4.16.0-1-amd64                   | 1         | 4.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 10        | 43.48%  |
| 4.19.0  | 9         | 39.13%  |
| 5.7.0   | 3         | 13.04%  |
| 4.16.0  | 1         | 4.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 10        | 43.48%  |
| 4.19    | 9         | 39.13%  |
| 5.7     | 3         | 13.04%  |
| 4.16    | 1         | 4.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 19        | 86.36%  |
| aarch64 | 3         | 13.64%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 17        | 73.91%  |
| Unknown         | 4         | 17.39%  |
| KDE5            | 1         | 4.35%   |
| GNOME Flashback | 1         | 4.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 15        | 65.22%  |
| Unknown | 4         | 17.39%  |
| X11     | 2         | 8.7%    |
| Tty     | 2         | 8.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 14        | 63.64%  |
| GDM     | 8         | 36.36%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 13        | 54.17%  |
| Unknown | 4         | 16.67%  |
| de_DE   | 2         | 8.33%   |
| zh_CN   | 1         | 4.17%   |
| pt_PT   | 1         | 4.17%   |
| it_IT   | 1         | 4.17%   |
| es_CR   | 1         | 4.17%   |
| en_GB   | 1         | 4.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 19        | 86.36%  |
| EFI  | 3         | 13.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 19        | 86.36%  |
| Unknown | 2         | 9.09%   |
| Ext2    | 1         | 4.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 12        | 54.55%  |
| MBR     | 7         | 31.82%  |
| GPT     | 3         | 13.64%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 17        | 77.27%  |
| Yes       | 5         | 22.73%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 20        | 90.91%  |
| Yes       | 2         | 9.09%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Purism            | 7         | 31.82%  |
| Lenovo            | 4         | 18.18%  |
| Dell              | 3         | 13.64%  |
| Unknown           | 2         | 9.09%   |
| Toshiba           | 1         | 4.55%   |
| Pine Microsystems | 1         | 4.55%   |
| Notebook          | 1         | 4.55%   |
| Hewlett-Packard   | 1         | 4.55%   |
| Apple             | 1         | 4.55%   |
| Acer              | 1         | 4.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Purism Librem 14                      | 3         | 13.64%  |
| Unknown                               | 2         | 9.09%   |
| Toshiba Satellite L500D               | 1         | 4.55%   |
| Purism Librem 15 v4                   | 1         | 4.55%   |
| Purism Librem 15 v3                   | 1         | 4.55%   |
| Purism Librem 13 v4                   | 1         | 4.55%   |
| Purism Librem 13 v2                   | 1         | 4.55%   |
| Pine Microsystems Pine64 Pinebook Pro | 1         | 4.55%   |
| Notebook P17SM                        | 1         | 4.55%   |
| Lenovo ThinkPad T540p 20BFS23T00      | 1         | 4.55%   |
| Lenovo ThinkPad T440 20B60044RT       | 1         | 4.55%   |
| Lenovo ThinkPad E480 20KN003SUS       | 1         | 4.55%   |
| Lenovo ThinkPad 13 2nd Gen 20J2S00G00 | 1         | 4.55%   |
| HP Pavilion g6                        | 1         | 4.55%   |
| Dell XPS 13 9370                      | 1         | 4.55%   |
| Dell Inspiron 5547                    | 1         | 4.55%   |
| Dell Inspiron 15-3567                 | 1         | 4.55%   |
| Apple MacBookPro14,2                  | 1         | 4.55%   |
| Acer Nitro AN515-43                   | 1         | 4.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Purism Librem            | 7         | 31.82%  |
| Lenovo ThinkPad          | 4         | 18.18%  |
| Dell Inspiron            | 2         | 9.09%   |
| Unknown                  | 2         | 9.09%   |
| Toshiba Satellite        | 1         | 4.55%   |
| Pine Microsystems Pine64 | 1         | 4.55%   |
| Notebook P17SM           | 1         | 4.55%   |
| HP Pavilion              | 1         | 4.55%   |
| Dell XPS                 | 1         | 4.55%   |
| Apple MacBookPro14       | 1         | 4.55%   |
| Acer Nitro               | 1         | 4.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2017    | 4         | 18.18%  |
| Unknown | 4         | 18.18%  |
| 2019    | 3         | 13.64%  |
| 2013    | 3         | 13.64%  |
| 2021    | 2         | 9.09%   |
| 2018    | 2         | 9.09%   |
| 2016    | 1         | 4.55%   |
| 2014    | 1         | 4.55%   |
| 2011    | 1         | 4.55%   |
| 2009    | 1         | 4.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 22        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 22        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 15        | 68.18%  |
| Yes  | 7         | 31.82%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 16.01-24.0 | 7         | 31.82%  |
| 4.01-8.0   | 4         | 18.18%  |
| 32.01-64.0 | 3         | 13.64%  |
| 8.01-16.0  | 3         | 13.64%  |
| 3.01-4.0   | 2         | 9.09%   |
| 2.01-3.0   | 2         | 9.09%   |
| 24.01-32.0 | 1         | 4.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 3.01-4.0  | 8         | 33.33%  |
| 2.01-3.0  | 7         | 29.17%  |
| 1.01-2.0  | 4         | 16.67%  |
| 4.01-8.0  | 3         | 12.5%   |
| 8.01-16.0 | 1         | 4.17%   |
| 0.51-1.0  | 1         | 4.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 14        | 63.64%  |
| 2      | 8         | 36.36%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 18        | 81.82%  |
| Yes       | 4         | 18.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 68.18%  |
| No        | 7         | 31.82%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 81.82%  |
| No        | 4         | 18.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 68.18%  |
| No        | 7         | 31.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| USA                    | 5         | 20.83%  |
| Germany                | 3         | 12.5%   |
| Canada                 | 3         | 12.5%   |
| UK                     | 2         | 8.33%   |
| Turkey                 | 1         | 4.17%   |
| South Africa           | 1         | 4.17%   |
| Portugal               | 1         | 4.17%   |
| Poland                 | 1         | 4.17%   |
| Italy                  | 1         | 4.17%   |
| France                 | 1         | 4.17%   |
| Costa Rica             | 1         | 4.17%   |
| China                  | 1         | 4.17%   |
| Brazil                 | 1         | 4.17%   |
| Bosnia and Herzegovina | 1         | 4.17%   |
| Australia              | 1         | 4.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Xi'an         | 1         | 4.17%   |
| Windsor       | 1         | 4.17%   |
| Warsaw        | 1         | 4.17%   |
| Viadanica     | 1         | 4.17%   |
| Vancouver     | 1         | 4.17%   |
| Tupa          | 1         | 4.17%   |
| Thorpe Hamlet | 1         | 4.17%   |
| Stuttgart     | 1         | 4.17%   |
| Seattle       | 1         | 4.17%   |
| San Jose      | 1         | 4.17%   |
| Paris         | 1         | 4.17%   |
| New York      | 1         | 4.17%   |
| Nashville     | 1         | 4.17%   |
| Montreal      | 1         | 4.17%   |
| Lottstetten   | 1         | 4.17%   |
| London        | 1         | 4.17%   |
| Istanbul      | 1         | 4.17%   |
| GuimarÃ£es  | 1         | 4.17%   |
| East Malvern  | 1         | 4.17%   |
| Cape Town     | 1         | 4.17%   |
| Big Sky       | 1         | 4.17%   |
| Berlin        | 1         | 4.17%   |
| Banja Luka    | 1         | 4.17%   |
| Avon          | 1         | 4.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 12     | 27.59%  |
| Unknown             | 3         | 3      | 10.34%  |
| Seagate             | 3         | 3      | 10.34%  |
| Crucial             | 2         | 3      | 6.9%    |
| WDC                 | 1         | 1      | 3.45%   |
| Toshiba             | 1         | 1      | 3.45%   |
| SanDisk             | 1         | 1      | 3.45%   |
| PLEXTOR             | 1         | 1      | 3.45%   |
| Phison              | 1         | 1      | 3.45%   |
| Mushkin             | 1         | 1      | 3.45%   |
| JMicron             | 1         | 1      | 3.45%   |
| Intel               | 1         | 1      | 3.45%   |
| Hitachi             | 1         | 1      | 3.45%   |
| HGST                | 1         | 1      | 3.45%   |
| BIWIN               | 1         | 1      | 3.45%   |
| Apple               | 1         | 2      | 3.45%   |
| ADATA Technology    | 1         | 1      | 3.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM048-2E7172 1TB      | 2         | 6.45%   |
| WDC WDS100T2B0C-00PXH0 1TB          | 1         | 3.23%   |
| Unknown MMC Card  32GB              | 1         | 3.23%   |
| Unknown DA4128  128GB               | 1         | 3.23%   |
| Unknown 032G32  32GB                | 1         | 3.23%   |
| Toshiba NVMe SSD Drive 512GB        | 1         | 3.23%   |
| Seagate NVMe SSD Drive 2TB          | 1         | 3.23%   |
| SanDisk SDSSDH3500G 500GB           | 1         | 3.23%   |
| Samsung SSD 970 PRO 1TB             | 1         | 3.23%   |
| Samsung SSD 970 EVO 250GB           | 1         | 3.23%   |
| Samsung SSD 960 EVO 500GB           | 1         | 3.23%   |
| Samsung SSD 960 EVO 250GB           | 1         | 3.23%   |
| Samsung SSD 860 EVO 500GB           | 1         | 3.23%   |
| Samsung SSD 860 EVO 250GB           | 1         | 3.23%   |
| Samsung SSD 860 EVO 1TB             | 1         | 3.23%   |
| Samsung SSD 850 EVO 500GB           | 1         | 3.23%   |
| Samsung SSD 850 EVO 250GB           | 1         | 3.23%   |
| PLEXTOR PX-1TM6Pro 1024GB SSD       | 1         | 3.23%   |
| Phison PM8512GPTCB4B8TF-E13T4 512GB | 1         | 3.23%   |
| Mushkin MKNSSDRE250GB-LT            | 1         | 3.23%   |
| JMicron Generic 2TB                 | 1         | 3.23%   |
| Intel SSDSC2BF180A4H 180GB          | 1         | 3.23%   |
| Hitachi HTS545050A7E380 500GB       | 1         | 3.23%   |
| HGST HTS545050B7E660 500GB          | 1         | 3.23%   |
| Crucial CT250MX500SSD4 250GB        | 1         | 3.23%   |
| Crucial CT2000MX500SSD1 2TB         | 1         | 3.23%   |
| BIWIN SSD 120GB                     | 1         | 3.23%   |
| Apple NVMe SSD Drive 8KB            | 1         | 3.23%   |
| Apple NVMe SSD Drive 256GB          | 1         | 3.23%   |
| ADATA NVMe SSD Drive 512GB          | 1         | 3.23%   |

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
| Samsung Electronics | 6         | 8      | 42.86%  |
| Crucial             | 2         | 3      | 14.29%  |
| SanDisk             | 1         | 1      | 7.14%   |
| PLEXTOR             | 1         | 1      | 7.14%   |
| Mushkin             | 1         | 1      | 7.14%   |
| JMicron             | 1         | 1      | 7.14%   |
| Intel               | 1         | 1      | 7.14%   |
| BIWIN               | 1         | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 11        | 17     | 40.74%  |
| NVMe | 9         | 11     | 33.33%  |
| HDD  | 4         | 4      | 14.81%  |
| MMC  | 3         | 3      | 11.11%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 13        | 19     | 48.15%  |
| NVMe | 9         | 11     | 33.33%  |
| MMC  | 3         | 3      | 11.11%  |
| SAS  | 2         | 2      | 7.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 9         | 15     | 60%     |
| 1.01-2.0   | 3         | 3      | 20%     |
| 0.51-1.0   | 3         | 3      | 20%     |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 9         | 40.91%  |
| 251-500    | 2         | 9.09%   |
| 21-50      | 2         | 9.09%   |
| 101-250    | 2         | 9.09%   |
| 501-1000   | 2         | 9.09%   |
| Unknown    | 2         | 9.09%   |
| 2001-3000  | 1         | 4.55%   |
| 1001-2000  | 1         | 4.55%   |
| 51-100     | 1         | 4.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 12        | 54.55%  |
| 21-50    | 3         | 13.64%  |
| 501-1000 | 3         | 13.64%  |
| Unknown  | 2         | 9.09%   |
| 251-500  | 1         | 4.55%   |
| 51-100   | 1         | 4.55%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                      | Notebooks | Drives | Percent |
|----------------------------|-----------|--------|---------|
| Intel SSDSC2BF180A4H 180GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| Intel  | 1         | 1      | 100%    |

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
| Detected | 15        | 23     | 65.22%  |
| Works    | 7         | 11     | 30.43%  |
| Malfunc  | 1         | 1      | 4.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 11        | 50%     |
| Samsung Electronics          | 3         | 13.64%  |
| AMD                          | 2         | 9.09%   |
| Toshiba America Info Systems | 1         | 4.55%   |
| Seagate Technology           | 1         | 4.55%   |
| Sandisk                      | 1         | 4.55%   |
| Phison Electronics           | 1         | 4.55%   |
| Apple                        | 1         | 4.55%   |
| ADATA Technology             | 1         | 4.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 27.27%  |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 9.09%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 9.09%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 9.09%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 4.55%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 4.55%   |
| Sandisk Non-Volatile memory controller                                         | 1         | 4.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 4.55%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 4.55%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 4.55%   |
| Apple S3X NVMe Controller                                                      | 1         | 4.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 4.55%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 1         | 4.55%   |
| ADATA Non-Volatile memory controller                                           | 1         | 4.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 13        | 59.09%  |
| NVMe | 9         | 40.91%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 17        | 77.27%  |
| ARM    | 3         | 13.64%  |
| AMD    | 2         | 9.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 13.64%  |
| Intel Core i7-10710U CPU @ 1.10GHz            | 3         | 13.64%  |
| ARM Processor                                 | 3         | 13.64%  |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 9.09%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 9.09%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 4.55%   |
| Intel Core i7-7567U CPU @ 3.50GHz             | 1         | 4.55%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 1         | 4.55%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 4.55%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 4.55%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 4.55%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 1         | 4.55%   |
| AMD Turion II Dual-Core Mobile M520           | 1         | 4.55%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 4.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 13        | 59.09%  |
| Other                   | 3         | 13.64%  |
| Intel Core i5           | 2         | 9.09%   |
| Intel Core i3           | 2         | 9.09%   |
| AMD Turion II Dual-Core | 1         | 4.55%   |
| AMD Ryzen 5             | 1         | 4.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 12        | 54.55%  |
| 4      | 7         | 31.82%  |
| 6      | 3         | 13.64%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 22        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 18        | 81.82%  |
| 1      | 4         | 18.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 19        | 82.61%  |
| Unknown        | 4         | 17.39%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 68.18%  |
| 0xa0660    | 2         | 9.09%   |
| 0x406e3    | 2         | 9.09%   |
| 0x806e9    | 1         | 4.55%   |
| 0x40651    | 1         | 4.55%   |
| 0x08108109 | 1         | 4.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KabyLake  | 7         | 31.82%  |
| Haswell   | 4         | 18.18%  |
| CometLake | 3         | 13.64%  |
| Unknown   | 3         | 13.64%  |
| Skylake   | 2         | 9.09%   |
| Zen+      | 1         | 4.55%   |
| K10       | 1         | 4.55%   |
| IvyBridge | 1         | 4.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 17        | 73.91%  |
| AMD    | 4         | 17.39%  |
| Nvidia | 2         | 8.7%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                 | 5         | 20.83%  |
| Intel Comet Lake UHD Graphics                                                         | 3         | 12.5%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 8.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 8.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 2         | 8.33%   |
| Nvidia GK208M [GeForce GT 730M]                                                       | 1         | 4.17%   |
| Nvidia GK104M [GeForce GTX 870M]                                                      | 1         | 4.17%   |
| Intel UHD Graphics 620                                                                | 1         | 4.17%   |
| Intel Iris Plus Graphics 650                                                          | 1         | 4.17%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 1         | 4.17%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 4.17%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 1         | 4.17%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                             | 1         | 4.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 1         | 4.17%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                   | 1         | 4.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 13        | 59.09%  |
| Other          | 3         | 13.64%  |
| Intel + Nvidia | 2         | 9.09%   |
| Intel + AMD    | 2         | 9.09%   |
| 2 x AMD        | 1         | 4.55%   |
| 1 x AMD        | 1         | 4.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 18        | 81.82%  |
| Unknown | 4         | 18.18%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 95.45%  |
| 3.01-4.0   | 1         | 4.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 4         | 15.38%  |
| LG Display              | 4         | 15.38%  |
| BOE                     | 4         | 15.38%  |
| Chimei Innolux          | 3         | 11.54%  |
| AU Optronics            | 2         | 7.69%   |
| Unknown                 | 1         | 3.85%   |
| Sharp                   | 1         | 3.85%   |
| Lenovo                  | 1         | 3.85%   |
| Goldstar                | 1         | 3.85%   |
| Chi Mei Optoelectronics | 1         | 3.85%   |
| BenQ                    | 1         | 3.85%   |
| ASUSTek Computer        | 1         | 3.85%   |
| Apple                   | 1         | 3.85%   |
| Acer                    | 1         | 3.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch     | 2         | 7.69%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 2         | 7.69%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 1         | 3.85%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                   | 1         | 3.85%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch      | 1         | 3.85%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 1         | 3.85%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch              | 1         | 3.85%   |
| LG Display LCD Monitor LGD053B 1920x1080 294x165mm 13.3-inch              | 1         | 3.85%   |
| LG Display LCD Monitor LGD03F0 1366x768 310x174mm 14.0-inch               | 1         | 3.85%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch               | 1         | 3.85%   |
| Lenovo LEN Y44w-10 LEN65EA 3840x1200 1052x329mm 43.4-inch                 | 1         | 3.85%   |
| Goldstar IPS231 GSM5817 1920x1080 510x290mm 23.1-inch                     | 1         | 3.85%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 1         | 3.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 3.85%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 1         | 3.85%   |
| BOE LCD Monitor BOE06C2 1366x768 344x194mm 15.5-inch                      | 1         | 3.85%   |
| BOE LCD Monitor BOE06BE 1920x1080 294x165mm 13.3-inch                     | 1         | 3.85%   |
| BOE LCD Monitor BOE0641 1920x1080 344x193mm 15.5-inch                     | 1         | 3.85%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                         | 1         | 3.85%   |
| AU Optronics LCD Monitor AUO713C 1366x768 309x173mm 13.9-inch             | 1         | 3.85%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 344x193mm 15.5-inch            | 1         | 3.85%   |
| ASUSTek Computer VP249 AUS24AF 1920x1080 527x296mm 23.8-inch              | 1         | 3.85%   |
| Apple Color LCD APPA034 2880x1800 286x179mm 13.3-inch                     | 1         | 3.85%   |
| Acer H236HL ACR0318 1920x1080 509x286mm 23.0-inch                         | 1         | 3.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 11        | 50%     |
| 1366x768 (WXGA) | 5         | 22.73%  |
| 3840x2160 (4K)  | 3         | 13.64%  |
| 3840x1200       | 1         | 4.55%   |
| 2880x1800       | 1         | 4.55%   |
| 2288x1287       | 1         | 4.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 9         | 34.62%  |
| 13     | 7         | 26.92%  |
| 24     | 2         | 7.69%   |
| 23     | 2         | 7.69%   |
| 14     | 2         | 7.69%   |
| 142    | 1         | 3.85%   |
| 43     | 1         | 3.85%   |
| 27     | 1         | 3.85%   |
| 17     | 1         | 3.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 12        | 48%     |
| 501-600        | 5         | 20%     |
| 201-300        | 4         | 16%     |
| 351-400        | 2         | 8%      |
| More than 2000 | 1         | 4%      |
| 1001-1500      | 1         | 4%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 17        | 85%     |
| 3.20  | 1         | 5%      |
| 16/10 | 1         | 5%      |
| 1.00  | 1         | 5%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 9         | 34.62%  |
| 81-90          | 5         | 19.23%  |
| 71-80          | 4         | 15.38%  |
| 201-250        | 4         | 15.38%  |
| More than 1000 | 1         | 3.85%   |
| 301-350        | 1         | 3.85%   |
| 121-130        | 1         | 3.85%   |
| 501-1000       | 1         | 3.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 8         | 30.77%  |
| 51-100        | 7         | 26.92%  |
| More than 240 | 4         | 15.38%  |
| 101-120       | 4         | 15.38%  |
| 161-240       | 2         | 7.69%   |
| 1-50          | 1         | 3.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 14        | 63.64%  |
| 2     | 5         | 22.73%  |
| 0     | 2         | 9.09%   |
| 3     | 1         | 4.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 12        | 38.71%  |
| Qualcomm Atheros      | 10        | 32.26%  |
| Intel                 | 4         | 12.9%   |
| ASIX Electronics      | 2         | 6.45%   |
| Ralink                | 1         | 3.23%   |
| MediaTek              | 1         | 3.23%   |
| Broadcom              | 1         | 3.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 8         | 21.62%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 16.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 10.81%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 5.41%   |
| Intel Wireless 7260                                               | 2         | 5.41%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 5.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 2.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 2.7%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 2.7%    |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 2.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.7%    |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1         | 2.7%    |
| MediaTek WiFi                                                     | 1         | 2.7%    |
| Intel Wireless 8265 / 8275                                        | 1         | 2.7%    |
| Intel Wireless 7265                                               | 1         | 2.7%    |
| Intel Ethernet Connection I218-V                                  | 1         | 2.7%    |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.7%    |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.7%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 2.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 10        | 47.62%  |
| Realtek Semiconductor | 4         | 19.05%  |
| Intel                 | 4         | 19.05%  |
| Ralink                | 1         | 4.76%   |
| MediaTek              | 1         | 4.76%   |
| Broadcom              | 1         | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 8         | 38.1%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 2         | 9.52%   |
| Intel Wireless 7260                                        | 2         | 9.52%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1         | 4.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 4.76%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter    | 1         | 4.76%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 1         | 4.76%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter     | 1         | 4.76%   |
| MediaTek WiFi                                              | 1         | 4.76%   |
| Intel Wireless 8265 / 8275                                 | 1         | 4.76%   |
| Intel Wireless 7265                                        | 1         | 4.76%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                | 1         | 4.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 10        | 66.67%  |
| Intel                 | 3         | 20%     |
| ASIX Electronics      | 2         | 13.33%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 37.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 25%     |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 12.5%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 6.25%   |
| Intel Ethernet Connection I218-V                                  | 1         | 6.25%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 6.25%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 6.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 18        | 56.25%  |
| Ethernet | 14        | 43.75%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 14        | 51.85%  |
| WiFi     | 13        | 48.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 13        | 59.09%  |
| 1     | 5         | 22.73%  |
| 0     | 4         | 18.18%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 18        | 81.82%  |
| Yes  | 4         | 18.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Lite-On Technology              | 4         | 25%     |
| Qualcomm Atheros Communications | 3         | 18.75%  |
| Intel                           | 3         | 18.75%  |
| Foxconn / Hon Hai               | 3         | 18.75%  |
| Realtek Semiconductor           | 1         | 6.25%   |
| Cambridge Silicon Radio         | 1         | 6.25%   |
| ASUSTek Computer                | 1         | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 25%     |
| Intel Bluetooth wireless interface                  | 3         | 18.75%  |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 18.75%  |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 12.5%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 6.25%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 6.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 6.25%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Intel    | 17        | 73.91%  |
| AMD      | 2         | 8.7%    |
| XMOS     | 1         | 4.35%   |
| Shure    | 1         | 4.35%   |
| M-Audio  | 1         | 4.35%   |
| Logitech | 1         | 4.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                     | 9         | 32.14%  |
| Intel Comet Lake PCH-LP cAVS                                        | 3         | 10.71%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 2         | 7.14%   |
| Intel Haswell-ULT HD Audio Controller                               | 2         | 7.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 2         | 7.14%   |
| Intel 8 Series HD Audio Controller                                  | 2         | 7.14%   |
| XMOS xCORE USB Audio 2.0                                            | 1         | 3.57%   |
| Shure MV5                                                           | 1         | 3.57%   |
| M-Audio M-Audio Fast Track MKII                                     | 1         | 3.57%   |
| Logitech Headset H340                                               | 1         | 3.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 1         | 3.57%   |
| AMD SBx00 Azalia (Intel HDA)                                        | 1         | 3.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 1         | 3.57%   |
| AMD Family 17h/19h HD Audio Controller                              | 1         | 3.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 3         | 33.33%  |
| Crucial             | 3         | 33.33%  |
| Unknown             | 1         | 11.11%  |
| Toshiba             | 1         | 11.11%  |
| Samsung Electronics | 1         | 11.11%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 16384MB 2133MT/s                        | 1         | 9.09%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s         | 1         | 9.09%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s          | 1         | 9.09%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s  | 1         | 9.09%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s  | 1         | 9.09%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s  | 1         | 9.09%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s     | 1         | 9.09%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s     | 1         | 9.09%   |
| Crucial RAM CT4G4SFS8213.C8FBD1 4GB SODIMM DDR4 2133MT/s   | 1         | 9.09%   |
| Crucial RAM CT16G4SFD824A.M16FRS 16GB SODIMM DDR4 2400MT/s | 1         | 9.09%   |
| Crucial RAM CT16G4S24AM.M16FE 16GB SODIMM DDR4 2400MT/s    | 1         | 9.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 5         | 62.5%   |
| DDR3    | 1         | 12.5%   |
| DDR2    | 1         | 12.5%   |
| Unknown | 1         | 12.5%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SODIMM  | 7         | 87.5%   |
| Unknown | 1         | 12.5%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 16384 | 3         | 30%     |
| 8192  | 3         | 30%     |
| 4096  | 3         | 30%     |
| 32768 | 1         | 10%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 3         | 33.33%  |
| 2400  | 2         | 22.22%  |
| 2133  | 2         | 22.22%  |
| 1600  | 1         | 11.11%  |
| 1066  | 1         | 11.11%  |

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
| Realtek Semiconductor         | 3         | 20%     |
| Acer                          | 3         | 20%     |
| Sunplus Innovation Technology | 2         | 13.33%  |
| Chicony Electronics           | 2         | 13.33%  |
| Alcor Micro                   | 2         | 13.33%  |
| Microdia                      | 1         | 6.67%   |
| Lite-On Technology            | 1         | 6.67%   |
| Apple                         | 1         | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Alcor Micro HD WebCam                 | 2         | 12.5%   |
| Sunplus Integrated_Webcam_HD          | 1         | 6.25%   |
| Sunplus Integrated Camera             | 1         | 6.25%   |
| Realtek Integrated_Webcam_HD          | 1         | 6.25%   |
| Realtek Integrated Webcam             | 1         | 6.25%   |
| Realtek HP Truevision HD              | 1         | 6.25%   |
| Microdia HP Integrated Webcam         | 1         | 6.25%   |
| Lite-On Integrated Camera             | 1         | 6.25%   |
| Chicony USB2.0 UVC WebCam             | 1         | 6.25%   |
| Chicony HD User Facing                | 1         | 6.25%   |
| Apple iPhone 5/5C/5S/6/SE             | 1         | 6.25%   |
| Apple iBridge                         | 1         | 6.25%   |
| Acer SunplusIT Integrated Camera      | 1         | 6.25%   |
| Acer SunplusIT INC. Integrated Camera | 1         | 6.25%   |
| Acer BisonCam, NB Pro                 | 1         | 6.25%   |

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
| 1     | 9         | 40.91%  |
| 0     | 9         | 40.91%  |
| 2     | 2         | 9.09%   |
| 4     | 1         | 4.55%   |
| 3     | 1         | 4.55%   |

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

