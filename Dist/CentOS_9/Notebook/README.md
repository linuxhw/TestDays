CentOS 9 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for CentOS 9.

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

Total: 29

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo  | V15 G2 ITL 82KB             | [dfcebaef82](https://linux-hardware.org/?probe=dfcebaef82) | Aug 09, 2023 |
| Lenovo  | Legion 5P 15IMH05H 82AW     | [61408603be](https://linux-hardware.org/?probe=61408603be) | Apr 21, 2023 |
| ASUSTek | N751JK                      | [d148f91b52](https://linux-hardware.org/?probe=d148f91b52) | Mar 15, 2023 |
| ASUSTek | Q550LF                      | [793bf0d1d8](https://linux-hardware.org/?probe=793bf0d1d8) | Mar 06, 2023 |
| ASUSTek | N751JK                      | [a67a4d078f](https://linux-hardware.org/?probe=a67a4d078f) | Jan 21, 2023 |
| ASUSTek | N751JK                      | [259556fd6f](https://linux-hardware.org/?probe=259556fd6f) | Jan 11, 2023 |
| Razer   | Blade 15 (2022) - RZ09-0... | [b9522e3683](https://linux-hardware.org/?probe=b9522e3683) | Jan 02, 2023 |
| Lenovo  | ThinkPad T430 2347DE9       | [7b4305ce5a](https://linux-hardware.org/?probe=7b4305ce5a) | Dec 27, 2022 |
| Lenovo  | ThinkPad T430 2347DE9       | [afc91c5da0](https://linux-hardware.org/?probe=afc91c5da0) | Dec 24, 2022 |
| Acer    | Swift SF314-512             | [b2aac5194c](https://linux-hardware.org/?probe=b2aac5194c) | Dec 06, 2022 |
| Lenovo  | IdeaPad S145-15IWL 81S9     | [b981adc21a](https://linux-hardware.org/?probe=b981adc21a) | Nov 07, 2022 |
| Lenovo  | Yoga S740-14IIL 81RS        | [8bd50f112b](https://linux-hardware.org/?probe=8bd50f112b) | Oct 15, 2022 |
| Lenovo  | Yoga S740-14IIL 81RS        | [88497baf29](https://linux-hardware.org/?probe=88497baf29) | Oct 15, 2022 |
| Acer    | Aspire E1-570G              | [2293724ae2](https://linux-hardware.org/?probe=2293724ae2) | Sep 19, 2022 |
| Acer    | Aspire E1-570G              | [09db514840](https://linux-hardware.org/?probe=09db514840) | Sep 19, 2022 |
| Lenovo  | ThinkPad T430 2349DG5       | [740898521d](https://linux-hardware.org/?probe=740898521d) | Aug 27, 2022 |
| Timi    | Mi NoteBook Horizon Edit... | [52a0cb298b](https://linux-hardware.org/?probe=52a0cb298b) | Aug 09, 2022 |
| Lenovo  | G410 20237                  | [daea3239f0](https://linux-hardware.org/?probe=daea3239f0) | Aug 05, 2022 |
| HP      | Pavilion Gaming Laptop 1... | [29f2cd44d5](https://linux-hardware.org/?probe=29f2cd44d5) | Jun 11, 2022 |
| HP      | ProBook 470 G2              | [9a331b90a5](https://linux-hardware.org/?probe=9a331b90a5) | May 19, 2022 |
| HP      | ProBook 470 G2              | [4c3a3b2de2](https://linux-hardware.org/?probe=4c3a3b2de2) | May 17, 2022 |
| MSI     | Katana GF76 12UE            | [460e78b93a](https://linux-hardware.org/?probe=460e78b93a) | May 15, 2022 |
| HP      | EliteBook 840 G3            | [a7fb96d9aa](https://linux-hardware.org/?probe=a7fb96d9aa) | May 13, 2022 |
| Lenovo  | ThinkPad L14 Gen 1 20U5S... | [228ec1a5f7](https://linux-hardware.org/?probe=228ec1a5f7) | Apr 24, 2022 |
| Timi    | RedmiBook 16                | [bef46c5065](https://linux-hardware.org/?probe=bef46c5065) | Mar 20, 2022 |
| Lenovo  | G580 20150                  | [1f84b1e42d](https://linux-hardware.org/?probe=1f84b1e42d) | Mar 11, 2022 |
| Lenovo  | ThinkPad T460s 20FAS5WX0... | [6fa180d5fa](https://linux-hardware.org/?probe=6fa180d5fa) | Feb 06, 2022 |
| HP      | EliteBook 840 G1            | [cf90d5430c](https://linux-hardware.org/?probe=cf90d5430c) | Feb 04, 2022 |
| Acer    | Aspire 5740                 | [0c661cb2d6](https://linux-hardware.org/?probe=0c661cb2d6) | Nov 12, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 5.14.0-86.el9.x86_64      | 2         | 8.7%    |
| 5.14.0-134.el9.x86_64     | 2         | 8.7%    |
| 6.1.8-1.el9.elrepo.x86_64 | 1         | 4.35%   |
| 6.1.1                     | 1         | 4.35%   |
| 5.14.0-78.el9.x86_64      | 1         | 4.35%   |
| 5.14.0-71.el9.x86_64      | 1         | 4.35%   |
| 5.14.0-66.el9.x86_64      | 1         | 4.35%   |
| 5.14.0-52.el9.x86_64      | 1         | 4.35%   |
| 5.14.0-44.el9.x86_64      | 1         | 4.35%   |
| 5.14.0-350.el9.x86_64     | 1         | 4.35%   |
| 5.14.0-299.el9.x86_64     | 1         | 4.35%   |
| 5.14.0-282.el9.x86_64     | 1         | 4.35%   |
| 5.14.0-226.el9.x86_64     | 1         | 4.35%   |
| 5.14.0-214.el9.x86_64     | 1         | 4.35%   |
| 5.14.0-202.el9.x86_64     | 1         | 4.35%   |
| 5.14.0-183.el9.x86_64     | 1         | 4.35%   |
| 5.14.0-171.el9.x86_64     | 1         | 4.35%   |
| 5.14.0-163.el9.x86_64     | 1         | 4.35%   |
| 5.14.0-148.el9.x86_64     | 1         | 4.35%   |
| 5.14.0-12.el9.x86_64      | 1         | 4.35%   |
| 5.14.0-105.el9.x86_64     | 1         | 4.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 21        | 91.3%   |
| 6.1.8   | 1         | 4.35%   |
| 6.1.1   | 1         | 4.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 21        | 91.3%   |
| 6.1     | 2         | 8.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 22        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GNOME   | 20        | 90.91%  |
| KDE5    | 1         | 4.55%   |
| Unknown | 1         | 4.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 17        | 77.27%  |
| X11     | 4         | 18.18%  |
| Tty     | 1         | 4.55%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 12        | 54.55%  |
| GDM     | 8         | 36.36%  |
| SDDM    | 1         | 4.55%   |
| LightDM | 1         | 4.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 14        | 63.64%  |
| ru_RU | 2         | 9.09%   |
| zh_CN | 1         | 4.55%   |
| pt_BR | 1         | 4.55%   |
| it_IT | 1         | 4.55%   |
| fr_FR | 1         | 4.55%   |
| en_IN | 1         | 4.55%   |
| de_DE | 1         | 4.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 16        | 72.73%  |
| BIOS | 6         | 27.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 21        | 95.45%  |
| Ext4 | 1         | 4.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 10        | 45.45%  |
| GPT     | 7         | 31.82%  |
| MBR     | 5         | 22.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 19        | 86.36%  |
| Yes       | 3         | 13.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 15        | 68.18%  |
| Yes       | 7         | 31.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 10        | 45.45%  |
| Hewlett-Packard  | 3         | 13.64%  |
| Acer             | 3         | 13.64%  |
| Timi             | 2         | 9.09%   |
| ASUSTek Computer | 2         | 9.09%   |
| Razer            | 1         | 4.55%   |
| MSI              | 1         | 4.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Timi RedmiBook 16                    | 1         | 4.55%   |
| Timi Mi NoteBook Horizon Edition 14  | 1         | 4.55%   |
| Razer Blade 15 (2022) - RZ09-0421    | 1         | 4.55%   |
| MSI Katana GF76 12UE                 | 1         | 4.55%   |
| Lenovo Yoga S740-14IIL 81RS          | 1         | 4.55%   |
| Lenovo V15 G2 ITL 82KB               | 1         | 4.55%   |
| Lenovo ThinkPad T460s 20FAS5WX00     | 1         | 4.55%   |
| Lenovo ThinkPad T430 2349DG5         | 1         | 4.55%   |
| Lenovo ThinkPad T430 2347DE9         | 1         | 4.55%   |
| Lenovo ThinkPad L14 Gen 1 20U5S0NT00 | 1         | 4.55%   |
| Lenovo Legion 5P 15IMH05H 82AW       | 1         | 4.55%   |
| Lenovo IdeaPad S145-15IWL 81S9       | 1         | 4.55%   |
| Lenovo G580 20150                    | 1         | 4.55%   |
| Lenovo G410 20237                    | 1         | 4.55%   |
| HP Pavilion Gaming Laptop 15-ec0xxx  | 1         | 4.55%   |
| HP EliteBook 840 G3                  | 1         | 4.55%   |
| HP EliteBook 840 G1                  | 1         | 4.55%   |
| ASUS Q550LF                          | 1         | 4.55%   |
| ASUS N751JK                          | 1         | 4.55%   |
| Acer Swift SF314-512                 | 1         | 4.55%   |
| Acer Aspire E1-570G                  | 1         | 4.55%   |
| Acer Aspire 5740                     | 1         | 4.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Lenovo ThinkPad | 4         | 18.18%  |
| HP EliteBook    | 2         | 9.09%   |
| Acer Aspire     | 2         | 9.09%   |
| Timi RedmiBook  | 1         | 4.55%   |
| Timi Mi         | 1         | 4.55%   |
| Razer Blade     | 1         | 4.55%   |
| MSI Katana      | 1         | 4.55%   |
| Lenovo Yoga     | 1         | 4.55%   |
| Lenovo V15      | 1         | 4.55%   |
| Lenovo Legion   | 1         | 4.55%   |
| Lenovo IdeaPad  | 1         | 4.55%   |
| Lenovo G580     | 1         | 4.55%   |
| Lenovo G410     | 1         | 4.55%   |
| HP Pavilion     | 1         | 4.55%   |
| ASUS Q550LF     | 1         | 4.55%   |
| ASUS N751JK     | 1         | 4.55%   |
| Acer Swift      | 1         | 4.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 4         | 18.18%  |
| 2013 | 4         | 18.18%  |
| 2019 | 3         | 13.64%  |
| 2012 | 3         | 13.64%  |
| 2022 | 2         | 9.09%   |
| 2021 | 2         | 9.09%   |
| 2016 | 2         | 9.09%   |
| 2014 | 1         | 4.55%   |
| 2009 | 1         | 4.55%   |

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
| Disabled | 20        | 90.91%  |
| Enabled  | 2         | 9.09%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 22        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 10        | 45.45%  |
| 8.01-16.0  | 6         | 27.27%  |
| 32.01-64.0 | 4         | 18.18%  |
| 3.01-4.0   | 2         | 9.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 11        | 50%     |
| 4.01-8.0 | 5         | 22.73%  |
| 3.01-4.0 | 3         | 13.64%  |
| 1.01-2.0 | 2         | 9.09%   |
| 0.51-1.0 | 1         | 4.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 14        | 63.64%  |
| 2      | 7         | 31.82%  |
| 3      | 1         | 4.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 16        | 72.73%  |
| Yes       | 6         | 27.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 17        | 77.27%  |
| No        | 5         | 22.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 86.36%  |
| No        | 3         | 13.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 3         | 13.64%  |
| Germany     | 2         | 9.09%   |
| China       | 2         | 9.09%   |
| Canada      | 2         | 9.09%   |
| Uzbekistan  | 1         | 4.55%   |
| Ukraine     | 1         | 4.55%   |
| Switzerland | 1         | 4.55%   |
| Poland      | 1         | 4.55%   |
| Netherlands | 1         | 4.55%   |
| Kazakhstan  | 1         | 4.55%   |
| Italy       | 1         | 4.55%   |
| India       | 1         | 4.55%   |
| France      | 1         | 4.55%   |
| Finland     | 1         | 4.55%   |
| Colombia    | 1         | 4.55%   |
| Chile       | 1         | 4.55%   |
| Brazil      | 1         | 4.55%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Beijing        | 2         | 8.7%    |
| Tashkent       | 1         | 4.35%   |
| Soest          | 1         | 4.35%   |
| Schemmerhofen  | 1         | 4.35%   |
| Ruda Śląska  | 1         | 4.35%   |
| Ribeirao Preto | 1         | 4.35%   |
| Quitman        | 1         | 4.35%   |
| Puente Alto    | 1         | 4.35%   |
| Persan         | 1         | 4.35%   |
| Mumbai         | 1         | 4.35%   |
| L'Isle-Adam    | 1         | 4.35%   |
| Kramatorsk     | 1         | 4.35%   |
| Helsinki       | 1         | 4.35%   |
| Bristow        | 1         | 4.35%   |
| Bogotá        | 1         | 4.35%   |
| Birmensdorf    | 1         | 4.35%   |
| Berlin         | 1         | 4.35%   |
| Battle Creek   | 1         | 4.35%   |
| Barrie         | 1         | 4.35%   |
| Almaty         | 1         | 4.35%   |
| Airdrie        | 1         | 4.35%   |
| Adelfia        | 1         | 4.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 9      | 23.33%  |
| Seagate             | 3         | 3      | 10%     |
| Kingston            | 3         | 4      | 10%     |
| HGST                | 3         | 4      | 10%     |
| WDC                 | 2         | 2      | 6.67%   |
| SK hynix            | 2         | 2      | 6.67%   |
| Micron Technology   | 2         | 2      | 6.67%   |
| Intel               | 2         | 2      | 6.67%   |
| Unknown             | 1         | 1      | 3.33%   |
| Union Memory        | 1         | 1      | 3.33%   |
| Toshiba             | 1         | 1      | 3.33%   |
| LITEON              | 1         | 1      | 3.33%   |
| Hjwdz               | 1         | 1      | 3.33%   |
| Hewlett-Packard     | 1         | 1      | 3.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 2         | 6.45%   |
| Samsung MZNLH512HALU-00000 512GB SSD                | 2         | 6.45%   |
| Micron 2450_MTFDKBA512TFK 512GB                     | 2         | 6.45%   |
| WDC WD6400BEVT-22A0RT0 640GB                        | 1         | 3.23%   |
| WDC WD5000LPLX-60ZNTT1 500GB                        | 1         | 3.23%   |
| Unknown MMC Card  7GB                               | 1         | 3.23%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB             | 1         | 3.23%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 3.23%   |
| SK hynix NVMe SSD Drive 256GB                       | 1         | 3.23%   |
| SK hynix BC501 NVMe 256GB                           | 1         | 3.23%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 3.23%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 3.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 3.23%   |
| Samsung PSSD T7 1TB                                 | 1         | 3.23%   |
| Samsung NVMe SSD Drive 1TB                          | 1         | 3.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 1         | 3.23%   |
| Samsung MZALQ512HALU-000L2 512GB                    | 1         | 3.23%   |
| LITEON IT LST-32S9G-HP 32GB SSD                     | 1         | 3.23%   |
| Kingston SH103S3240G 240GB SSD                      | 1         | 3.23%   |
| Kingston SA400S37240G 240GB SSD                     | 1         | 3.23%   |
| Kingston RBU-SC100S37128GD 128GB SSD                | 1         | 3.23%   |
| Intel SSDSCKKF256H6L 256GB                          | 1         | 3.23%   |
| Intel SSDPEKNW512G8L 512GB                          | 1         | 3.23%   |
| Hjwdz MS2160 8MB                                    | 1         | 3.23%   |
| HGST HTS725032A7E630 320GB                          | 1         | 3.23%   |
| HGST HTS721010A9E630 1TB                            | 1         | 3.23%   |
| HGST HTS541010A9E680 1TB                            | 1         | 3.23%   |
| HP SSD S700 500GB                                   | 1         | 3.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 33.33%  |
| HGST    | 3         | 4      | 33.33%  |
| WDC     | 2         | 2      | 22.22%  |
| Toshiba | 1         | 1      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 4      | 33.33%  |
| Kingston            | 3         | 4      | 33.33%  |
| LITEON              | 1         | 1      | 11.11%  |
| Intel               | 1         | 1      | 11.11%  |
| Hewlett-Packard     | 1         | 1      | 11.11%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 9         | 11     | 32.14%  |
| HDD     | 9         | 10     | 32.14%  |
| SSD     | 8         | 11     | 28.57%  |
| MMC     | 1         | 1      | 3.57%   |
| Unknown | 1         | 1      | 3.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 15        | 19     | 55.56%  |
| NVMe | 9         | 11     | 33.33%  |
| SAS  | 2         | 3      | 7.41%   |
| MMC  | 1         | 1      | 3.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 9         | 10     | 52.94%  |
| 0.51-1.0   | 8         | 11     | 47.06%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 9         | 39.13%  |
| 251-500    | 7         | 30.43%  |
| 501-1000   | 4         | 17.39%  |
| 1001-2000  | 2         | 8.7%    |
| 2001-3000  | 1         | 4.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 13        | 56.52%  |
| 101-250   | 4         | 17.39%  |
| 251-500   | 3         | 13.04%  |
| 21-50     | 1         | 4.35%   |
| 1001-2000 | 1         | 4.35%   |
| 51-100    | 1         | 4.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD5000LPLX-60ZNTT1 500GB    | 1         | 1      | 50%     |
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 100%    |

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
| Detected | 11        | 18     | 47.83%  |
| Works    | 10        | 14     | 43.48%  |
| Malfunc  | 2         | 2      | 8.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 17        | 62.96%  |
| Samsung Electronics     | 4         | 14.81%  |
| SK hynix                | 2         | 7.41%   |
| Micron Technology       | 2         | 7.41%   |
| Union Memory (Shenzhen) | 1         | 3.7%    |
| AMD                     | 1         | 3.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 13.33%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 6.67%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 6.67%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 6.67%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 6.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 6.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 6.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 6.67%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                          | 1         | 3.33%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 3.33%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 3.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 3.33%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 3.33%   |
| Intel SSD 660P Series                                                          | 1         | 3.33%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 3.33%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 3.33%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 1         | 3.33%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 3.33%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 3.33%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 1         | 3.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 17        | 60.71%  |
| NVMe | 9         | 32.14%  |
| RAID | 2         | 7.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 19        | 86.36%  |
| AMD    | 3         | 13.64%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 4.55%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 4.55%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 4.55%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 4.55%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 4.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 4.55%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 4.55%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 4.55%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 4.55%   |
| Intel Core i5-3380M CPU @ 2.90GHz             | 1         | 4.55%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 4.55%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 4.55%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 4.55%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 1         | 4.55%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 4.55%   |
| Intel 12th Gen Core i7-12800H                 | 1         | 4.55%   |
| Intel 12th Gen Core i7-12700H                 | 1         | 4.55%   |
| Intel 12th Gen Core i7-1260P                  | 1         | 4.55%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 4.55%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 4.55%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 4.55%   |
| AMD Ryzen 3 PRO 4450U with Radeon Graphics    | 1         | 4.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i5   | 9         | 40.91%  |
| Intel Core i7   | 5         | 22.73%  |
| Other           | 4         | 18.18%  |
| AMD Ryzen 5     | 2         | 9.09%   |
| Intel Core i3   | 1         | 4.55%   |
| AMD Ryzen 3 PRO | 1         | 4.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 10        | 45.45%  |
| 4      | 7         | 31.82%  |
| 14     | 2         | 9.09%   |
| 6      | 2         | 9.09%   |
| 12     | 1         | 4.55%   |

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
| 2      | 20        | 90.91%  |
| 1      | 2         | 9.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 22        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306a9    | 4         | 18.18%  |
| 0x906a3    | 3         | 13.64%  |
| 0x806ec    | 2         | 9.09%   |
| 0x406e3    | 2         | 9.09%   |
| 0x40651    | 2         | 9.09%   |
| 0x306c3    | 2         | 9.09%   |
| 0x08600106 | 2         | 9.09%   |
| Unknown    | 2         | 9.09%   |
| 0xa0652    | 1         | 4.55%   |
| 0x706e5    | 1         | 4.55%   |
| 0x20652    | 1         | 4.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| IvyBridge        | 4         | 18.18%  |
| Haswell          | 4         | 18.18%  |
| Alderlake Hybrid | 3         | 13.64%  |
| Zen 2            | 2         | 9.09%   |
| Skylake          | 2         | 9.09%   |
| KabyLake         | 2         | 9.09%   |
| Zen+             | 1         | 4.55%   |
| Westmere         | 1         | 4.55%   |
| TigerLake        | 1         | 4.55%   |
| IceLake          | 1         | 4.55%   |
| CometLake        | 1         | 4.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 17        | 51.52%  |
| Nvidia | 11        | 33.33%  |
| AMD    | 5         | 15.15%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                     | 4         | 12.12%  |
| Intel Alder Lake-P Integrated Graphics Controller                    | 3         | 9.09%   |
| Intel Skylake GT2 [HD Graphics 520]                                  | 2         | 6.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                     | 2         | 6.06%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller          | 2         | 6.06%   |
| AMD Renoir                                                           | 2         | 6.06%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                      | 1         | 3.03%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                              | 1         | 3.03%   |
| Nvidia GP108M [GeForce MX250]                                        | 1         | 3.03%   |
| Nvidia GP107M [GeForce MX350]                                        | 1         | 3.03%   |
| Nvidia GM108M [GeForce MX110]                                        | 1         | 3.03%   |
| Nvidia GM107M [GeForce GTX 850M]                                     | 1         | 3.03%   |
| Nvidia GK208M [GeForce GT 740M]                                      | 1         | 3.03%   |
| Nvidia GK107M [GeForce GT 745M]                                      | 1         | 3.03%   |
| Nvidia GF108M [NVS 5400M]                                            | 1         | 3.03%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                      | 1         | 3.03%   |
| Nvidia GA103M [GeForce RTX 3080 Ti Mobile]                           | 1         | 3.03%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                           | 1         | 3.03%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 1         | 3.03%   |
| Intel Iris Plus Graphics G7                                          | 1         | 3.03%   |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 1         | 3.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 1         | 3.03%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                         | 1         | 3.03%   |
| AMD Mars [Radeon HD 8730M]                                           | 1         | 3.03%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 9         | 40.91%  |
| 1 x Intel      | 7         | 31.82%  |
| 1 x AMD        | 3         | 13.64%  |
| 1 x Nvidia     | 1         | 4.55%   |
| Intel + AMD    | 1         | 4.55%   |
| AMD + Nvidia   | 1         | 4.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 19        | 86.36%  |
| Proprietary | 2         | 9.09%   |
| Unknown     | 1         | 4.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 11        | 47.83%  |
| 1.01-2.0   | 4         | 17.39%  |
| 0.01-0.5   | 3         | 13.04%  |
| 0.51-1.0   | 2         | 8.7%    |
| 5.01-6.0   | 1         | 4.35%   |
| 3.01-4.0   | 1         | 4.35%   |
| 8.01-16.0  | 1         | 4.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 6         | 24%     |
| Chimei Innolux      | 5         | 20%     |
| AU Optronics        | 4         | 16%     |
| Samsung Electronics | 2         | 8%      |
| BOE                 | 2         | 8%      |
| TMX                 | 1         | 4%      |
| SKY                 | 1         | 4%      |
| PANDA               | 1         | 4%      |
| Hewlett-Packard     | 1         | 4%      |
| CHD                 | 1         | 4%      |
| Acer                | 1         | 4%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 1         | 4%      |
| SKY 22X1-M225F SKY2150 1920x1080 476x268mm 21.5-inch                  | 1         | 4%      |
| Samsung Electronics SMT22A350 SAM07A7 1920x1080 477x268mm 21.5-inch   | 1         | 4%      |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 1         | 4%      |
| PANDA LCD Monitor NCP0052 1920x1080 309x174mm 14.0-inch               | 1         | 4%      |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch          | 1         | 4%      |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 4%      |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch          | 1         | 4%      |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch           | 1         | 4%      |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 1         | 4%      |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 1         | 4%      |
| Hewlett-Packard L185x HWP298C 1366x768 410x230mm 18.5-inch            | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN1608 1920x1080 355x199mm 16.0-inch      | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch       | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch      | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch       | 1         | 4%      |
| CHD PMO S241-IFC CHD0240 1920x1080 530x300mm 24.0-inch                | 1         | 4%      |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                 | 1         | 4%      |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 1         | 4%      |
| AU Optronics LCD Monitor AUO5A3D 1920x1080 309x174mm 14.0-inch        | 1         | 4%      |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch        | 1         | 4%      |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 1         | 4%      |
| AU Optronics LCD Monitor AUO0BA2 2560x1440 309x174mm 14.0-inch        | 1         | 4%      |
| Acer KA272 A ACR079A 1920x1080 598x336mm 27.0-inch                    | 1         | 4%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 12        | 54.55%  |
| 1366x768 (WXGA) | 6         | 27.27%  |
| 1600x900 (HD+)  | 2         | 9.09%   |
| 3200x2000       | 1         | 4.55%   |
| 2560x1440 (QHD) | 1         | 4.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 14     | 9         | 36%     |
| 15     | 8         | 32%     |
| 27     | 1         | 4%      |
| 24     | 1         | 4%      |
| 23     | 1         | 4%      |
| 21     | 1         | 4%      |
| 18     | 1         | 4%      |
| 17     | 1         | 4%      |
| 16     | 1         | 4%      |
| 13     | 1         | 4%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 18        | 75%     |
| 501-600     | 2         | 8.33%   |
| 401-500     | 2         | 8.33%   |
| 351-400     | 2         | 8.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 19        | 95%     |
| 16/10 | 1         | 5%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 10        | 41.67%  |
| 101-110        | 8         | 33.33%  |
| 301-350        | 1         | 4.17%   |
| 201-250        | 1         | 4.17%   |
| 151-200        | 1         | 4.17%   |
| 141-150        | 1         | 4.17%   |
| 121-130        | 1         | 4.17%   |
| 111-120        | 1         | 4.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 13        | 54.17%  |
| 101-120       | 6         | 25%     |
| 51-100        | 3         | 12.5%   |
| More than 240 | 1         | 4.17%   |
| 161-240       | 1         | 4.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 16        | 72.73%  |
| 2     | 3         | 13.64%  |
| 0     | 2         | 9.09%   |
| 3     | 1         | 4.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 15        | 45.45%  |
| Realtek Semiconductor             | 7         | 21.21%  |
| Qualcomm Atheros                  | 5         | 15.15%  |
| Broadcom                          | 3         | 9.09%   |
| Xiaomi                            | 1         | 3.03%   |
| Ericsson Business Mobile Networks | 1         | 3.03%   |
| ASUSTek Computer                  | 1         | 3.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 7         | 17.07%  |
| Intel Wireless 7260                                                | 3         | 7.32%   |
| Intel Alder Lake-P PCH CNVi WiFi                                   | 3         | 7.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 2         | 4.88%   |
| Intel Wireless 8260                                                | 2         | 4.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 2         | 4.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 2         | 4.88%   |
| Xiaomi Mi/Redmi series (RNDIS)                                     | 1         | 2.44%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter           | 1         | 2.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 1         | 2.44%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                             | 1         | 2.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 1         | 2.44%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)     | 1         | 2.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                              | 1         | 2.44%   |
| Intel Wi-Fi 6 AX201                                                | 1         | 2.44%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                    | 1         | 2.44%   |
| Intel Ethernet Connection I219-V                                   | 1         | 2.44%   |
| Intel Ethernet Connection I219-LM                                  | 1         | 2.44%   |
| Intel Ethernet Connection I218-LM                                  | 1         | 2.44%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                    | 1         | 2.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 1         | 2.44%   |
| Intel Comet Lake PCH CNVi WiFi                                     | 1         | 2.44%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module | 1         | 2.44%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                  | 1         | 2.44%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                    | 1         | 2.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                | 1         | 2.44%   |
| ASUS 802.11ac NIC                                                  | 1         | 2.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 15        | 65.22%  |
| Qualcomm Atheros      | 4         | 17.39%  |
| Realtek Semiconductor | 2         | 8.7%    |
| Broadcom              | 1         | 4.35%   |
| ASUSTek Computer      | 1         | 4.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 3         | 13.04%  |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 13.04%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 8.7%    |
| Intel Wireless 8260                                            | 2         | 8.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 8.7%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 4.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 4.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 4.35%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 4.35%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 4.35%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 4.35%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 4.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 4.35%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 4.35%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 4.35%   |
| ASUS 802.11ac NIC                                              | 1         | 4.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 7         | 41.18%  |
| Intel                 | 5         | 29.41%  |
| Qualcomm Atheros      | 2         | 11.76%  |
| Broadcom              | 2         | 11.76%  |
| Xiaomi                | 1         | 5.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 41.18%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 11.76%  |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 5.88%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 5.88%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 5.88%   |
| Intel Ethernet Connection I219-V                                  | 1         | 5.88%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 5.88%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 5.88%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 5.88%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 5.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 22        | 56.41%  |
| Ethernet | 16        | 41.03%  |
| Modem    | 1         | 2.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 18        | 85.71%  |
| Ethernet | 3         | 14.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 16        | 72.73%  |
| 1     | 6         | 27.27%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 16        | 72.73%  |
| Yes  | 6         | 27.27%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 63.16%  |
| Realtek Semiconductor           | 2         | 10.53%  |
| Lite-On Technology              | 2         | 10.53%  |
| Broadcom                        | 2         | 10.53%  |
| Qualcomm Atheros Communications | 1         | 5.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 6         | 31.58%  |
| Realtek Bluetooth Radio                        | 2         | 10.53%  |
| Intel Bluetooth Device                         | 2         | 10.53%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 2         | 10.53%  |
| Intel AX201 Bluetooth                          | 2         | 10.53%  |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 2         | 10.53%  |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 1         | 5.26%   |
| Lite-On Bluetooth Device                       | 1         | 5.26%   |
| Lite-On Atheros AR3012 Bluetooth               | 1         | 5.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 18        | 64.29%  |
| Nvidia | 5         | 17.86%  |
| AMD    | 5         | 17.86%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 4         | 11.76%  |
| Intel Alder Lake PCH-P High Definition Audio Controller                 | 3         | 8.82%   |
| AMD Family 17h/19h HD Audio Controller                                  | 3         | 8.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 2         | 5.88%   |
| Intel Haswell-ULT HD Audio Controller                                   | 2         | 5.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 2         | 5.88%   |
| Intel 8 Series HD Audio Controller                                      | 2         | 5.88%   |
| AMD Renoir Radeon High Definition Audio Controller                      | 2         | 5.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 1         | 2.94%   |
| Nvidia TU106 High Definition Audio Controller                           | 1         | 2.94%   |
| Nvidia GF108 High Definition Audio Controller                           | 1         | 2.94%   |
| Nvidia GA106 High Definition Audio Controller                           | 1         | 2.94%   |
| Nvidia Audio device                                                     | 1         | 2.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 1         | 2.94%   |
| Intel Sunrise Point-LP HD Audio                                         | 1         | 2.94%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller               | 1         | 2.94%   |
| Intel Comet Lake PCH-LP cAVS                                            | 1         | 2.94%   |
| Intel Comet Lake PCH cAVS                                               | 1         | 2.94%   |
| Intel Cannon Point-LP High Definition Audio Controller                  | 1         | 2.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                | 1         | 2.94%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 1         | 2.94%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                  | 1         | 2.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 42.86%  |
| SK hynix            | 2         | 14.29%  |
| Smart Brazil        | 1         | 7.14%   |
| SHARETRONIC         | 1         | 7.14%   |
| Kingston            | 1         | 7.14%   |
| G.Skill             | 1         | 7.14%   |
| Corsair             | 1         | 7.14%   |
| A-DATA Technology   | 1         | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s | 1         | 7.14%   |
| SK hynix RAM HMT125S6BFR8C-G7 2048MB SODIMM DDR3 1067MT/s    | 1         | 7.14%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 7.14%   |
| SHARETRONIC RAM Module 4GB SODIMM DDR3 800MT/s               | 1         | 7.14%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 7.14%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 1         | 7.14%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 7.14%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 1         | 7.14%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 7.14%   |
| Samsung RAM K4UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s | 1         | 7.14%   |
| Kingston RAM 9905417-083.A00G 4GB SODIMM DDR3 1600MT/s       | 1         | 7.14%   |
| G.Skill RAM F3-1600C9-8GRSL 8GB SODIMM DDR3 1600MT/s         | 1         | 7.14%   |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s      | 1         | 7.14%   |
| A-DATA RAM Module 32GB SODIMM DDR4 3200MT/s                  | 1         | 7.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 6         | 50%     |
| DDR3   | 5         | 41.67%  |
| LPDDR4 | 1         | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 10        | 83.33%  |
| Row Of Chips | 2         | 16.67%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 7         | 53.85%  |
| 4096  | 3         | 23.08%  |
| 32768 | 1         | 7.69%   |
| 16384 | 1         | 7.69%   |
| 2048  | 1         | 7.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 3         | 25%     |
| 1600  | 3         | 25%     |
| 2667  | 2         | 16.67%  |
| 4267  | 1         | 8.33%   |
| 2133  | 1         | 8.33%   |
| 1067  | 1         | 8.33%   |
| 800   | 1         | 8.33%   |

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
| Chicony Electronics                    | 5         | 26.32%  |
| IMC Networks                           | 3         | 15.79%  |
| Bison Electronics                      | 3         | 15.79%  |
| Syntek                                 | 2         | 10.53%  |
| Cheng Uei Precision Industry (Foxlink) | 2         | 10.53%  |
| Realtek Semiconductor                  | 1         | 5.26%   |
| Luxvisions Innotech Limited            | 1         | 5.26%   |
| Apple                                  | 1         | 5.26%   |
| Acer                                   | 1         | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                            | 2         | 10.53%  |
| Realtek Lenovo EasyCamera                           | 1         | 5.26%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 5.26%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 5.26%   |
| IMC Networks Integrated RGB Camera                  | 1         | 5.26%   |
| IMC Networks Integrated Camera                      | 1         | 5.26%   |
| Chicony Thinkpad T430 camera                        | 1         | 5.26%   |
| Chicony Integrated Camera                           | 1         | 5.26%   |
| Chicony HD WebCam (Asus N-series)                   | 1         | 5.26%   |
| Chicony HD WebCam                                   | 1         | 5.26%   |
| Chicony Acer CrystalEye Webcam                      | 1         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 5.26%   |
| Bison Lenovo Integrated Webcam                      | 1         | 5.26%   |
| Bison Integrated Camera                             | 1         | 5.26%   |
| Bison HD Webcam                                     | 1         | 5.26%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 1         | 5.26%   |
| Acer Integrated Camera                              | 1         | 5.26%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 50%     |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Upek   | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 13        | 56.52%  |
| 1     | 7         | 30.43%  |
| 2     | 3         | 13.04%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 4         | 36.36%  |
| Multimedia controller | 3         | 27.27%  |
| Fingerprint reader    | 2         | 18.18%  |
| Net/wireless          | 1         | 9.09%   |
| Chipcard              | 1         | 9.09%   |

