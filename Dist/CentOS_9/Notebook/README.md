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

Total: 33

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
| Dell    | Precision 5520              | [47f7336949](https://linux-hardware.org/?probe=47f7336949) | Jan 30, 2024 |
| Dell    | G5 5505                     | [fd284cda8a](https://linux-hardware.org/?probe=fd284cda8a) | Jan 04, 2024 |
| Samsung | 355V4C/356V4C/3445VC/354... | [ecc33f393d](https://linux-hardware.org/?probe=ecc33f393d) | Nov 22, 2023 |
| Dell    | Vostro 5402                 | [f23d8804a7](https://linux-hardware.org/?probe=f23d8804a7) | Oct 11, 2023 |
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
| 5.14.0-86.el9.x86_64      | 2         | 7.41%   |
| 5.14.0-134.el9.x86_64     | 2         | 7.41%   |
| 6.1.8-1.el9.elrepo.x86_64 | 1         | 3.7%    |
| 6.1.1                     | 1         | 3.7%    |
| 5.14.0-78.el9.x86_64      | 1         | 3.7%    |
| 5.14.0-71.el9.x86_64      | 1         | 3.7%    |
| 5.14.0-66.el9.x86_64      | 1         | 3.7%    |
| 5.14.0-52.el9.x86_64      | 1         | 3.7%    |
| 5.14.0-44.el9.x86_64      | 1         | 3.7%    |
| 5.14.0-410.el9.x86_64     | 1         | 3.7%    |
| 5.14.0-402.el9.x86_64     | 1         | 3.7%    |
| 5.14.0-383.el9.x86_64     | 1         | 3.7%    |
| 5.14.0-373.el9.x86_64     | 1         | 3.7%    |
| 5.14.0-350.el9.x86_64     | 1         | 3.7%    |
| 5.14.0-299.el9.x86_64     | 1         | 3.7%    |
| 5.14.0-282.el9.x86_64     | 1         | 3.7%    |
| 5.14.0-226.el9.x86_64     | 1         | 3.7%    |
| 5.14.0-214.el9.x86_64     | 1         | 3.7%    |
| 5.14.0-202.el9.x86_64     | 1         | 3.7%    |
| 5.14.0-183.el9.x86_64     | 1         | 3.7%    |
| 5.14.0-171.el9.x86_64     | 1         | 3.7%    |
| 5.14.0-163.el9.x86_64     | 1         | 3.7%    |
| 5.14.0-148.el9.x86_64     | 1         | 3.7%    |
| 5.14.0-12.el9.x86_64      | 1         | 3.7%    |
| 5.14.0-105.el9.x86_64     | 1         | 3.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 25        | 92.59%  |
| 6.1.8   | 1         | 3.7%    |
| 6.1.1   | 1         | 3.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 25        | 92.59%  |
| 6.1     | 2         | 7.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 26        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GNOME   | 24        | 92.31%  |
| KDE5    | 1         | 3.85%   |
| Unknown | 1         | 3.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 19        | 73.08%  |
| X11     | 6         | 23.08%  |
| Tty     | 1         | 3.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 13        | 50%     |
| GDM     | 11        | 42.31%  |
| SDDM    | 1         | 3.85%   |
| LightDM | 1         | 3.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 17        | 65.38%  |
| ru_RU | 3         | 11.54%  |
| zh_CN | 1         | 3.85%   |
| pt_BR | 1         | 3.85%   |
| it_IT | 1         | 3.85%   |
| fr_FR | 1         | 3.85%   |
| en_IN | 1         | 3.85%   |
| de_DE | 1         | 3.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 20        | 76.92%  |
| BIOS | 6         | 23.08%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 25        | 96.15%  |
| Ext4 | 1         | 3.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 11        | 42.31%  |
| GPT     | 10        | 38.46%  |
| MBR     | 5         | 19.23%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 22        | 84.62%  |
| Yes       | 4         | 15.38%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 18        | 69.23%  |
| Yes       | 8         | 30.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 10        | 38.46%  |
| Hewlett-Packard     | 3         | 11.54%  |
| Dell                | 3         | 11.54%  |
| Acer                | 3         | 11.54%  |
| Timi                | 2         | 7.69%   |
| ASUSTek Computer    | 2         | 7.69%   |
| Samsung Electronics | 1         | 3.85%   |
| Razer               | 1         | 3.85%   |
| MSI                 | 1         | 3.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Timi RedmiBook 16                    | 1         | 3.85%   |
| Timi Mi NoteBook Horizon Edition 14  | 1         | 3.85%   |
| Samsung 355V4C/356V4C/3445VC/3545VC  | 1         | 3.85%   |
| Razer Blade 15 (2022) - RZ09-0421    | 1         | 3.85%   |
| MSI Katana GF76 12UE                 | 1         | 3.85%   |
| Lenovo Yoga S740-14IIL 81RS          | 1         | 3.85%   |
| Lenovo V15 G2 ITL 82KB               | 1         | 3.85%   |
| Lenovo ThinkPad T460s 20FAS5WX00     | 1         | 3.85%   |
| Lenovo ThinkPad T430 2349DG5         | 1         | 3.85%   |
| Lenovo ThinkPad T430 2347DE9         | 1         | 3.85%   |
| Lenovo ThinkPad L14 Gen 1 20U5S0NT00 | 1         | 3.85%   |
| Lenovo Legion 5P 15IMH05H 82AW       | 1         | 3.85%   |
| Lenovo IdeaPad S145-15IWL 81S9       | 1         | 3.85%   |
| Lenovo G580 20150                    | 1         | 3.85%   |
| Lenovo G410 20237                    | 1         | 3.85%   |
| HP Pavilion Gaming Laptop 15-ec0xxx  | 1         | 3.85%   |
| HP EliteBook 840 G3                  | 1         | 3.85%   |
| HP EliteBook 840 G1                  | 1         | 3.85%   |
| Dell Vostro 5402                     | 1         | 3.85%   |
| Dell Precision 5520                  | 1         | 3.85%   |
| Dell G5 5505                         | 1         | 3.85%   |
| ASUS Q550LF                          | 1         | 3.85%   |
| ASUS N751JK                          | 1         | 3.85%   |
| Acer Swift SF314-512                 | 1         | 3.85%   |
| Acer Aspire E1-570G                  | 1         | 3.85%   |
| Acer Aspire 5740                     | 1         | 3.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Lenovo ThinkPad | 4         | 15.38%  |
| HP EliteBook    | 2         | 7.69%   |
| Acer Aspire     | 2         | 7.69%   |
| Timi RedmiBook  | 1         | 3.85%   |
| Timi Mi         | 1         | 3.85%   |
| Samsung 355V4C  | 1         | 3.85%   |
| Razer Blade     | 1         | 3.85%   |
| MSI Katana      | 1         | 3.85%   |
| Lenovo Yoga     | 1         | 3.85%   |
| Lenovo V15      | 1         | 3.85%   |
| Lenovo Legion   | 1         | 3.85%   |
| Lenovo IdeaPad  | 1         | 3.85%   |
| Lenovo G580     | 1         | 3.85%   |
| Lenovo G410     | 1         | 3.85%   |
| HP Pavilion     | 1         | 3.85%   |
| Dell Vostro     | 1         | 3.85%   |
| Dell Precision  | 1         | 3.85%   |
| Dell G5         | 1         | 3.85%   |
| ASUS Q550LF     | 1         | 3.85%   |
| ASUS N751JK     | 1         | 3.85%   |
| Acer Swift      | 1         | 3.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 6         | 23.08%  |
| 2013 | 5         | 19.23%  |
| 2019 | 3         | 11.54%  |
| 2012 | 3         | 11.54%  |
| 2022 | 2         | 7.69%   |
| 2021 | 2         | 7.69%   |
| 2016 | 2         | 7.69%   |
| 2017 | 1         | 3.85%   |
| 2014 | 1         | 3.85%   |
| 2009 | 1         | 3.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 26        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 24        | 92.31%  |
| Enabled  | 2         | 7.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 26        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 11        | 42.31%  |
| 8.01-16.0  | 7         | 26.92%  |
| 32.01-64.0 | 5         | 19.23%  |
| 3.01-4.0   | 2         | 7.69%   |
| 24.01-32.0 | 1         | 3.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 12        | 46.15%  |
| 4.01-8.0   | 6         | 23.08%  |
| 3.01-4.0   | 4         | 15.38%  |
| 1.01-2.0   | 2         | 7.69%   |
| 16.01-24.0 | 1         | 3.85%   |
| 0.51-1.0   | 1         | 3.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 18        | 69.23%  |
| 2      | 7         | 26.92%  |
| 3      | 1         | 3.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 19        | 73.08%  |
| Yes       | 7         | 26.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 76.92%  |
| No        | 6         | 23.08%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 100%    |

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
| USA         | 4         | 15.38%  |
| Italy       | 2         | 7.69%   |
| Germany     | 2         | 7.69%   |
| China       | 2         | 7.69%   |
| Canada      | 2         | 7.69%   |
| Uzbekistan  | 1         | 3.85%   |
| Ukraine     | 1         | 3.85%   |
| Switzerland | 1         | 3.85%   |
| Russia      | 1         | 3.85%   |
| Poland      | 1         | 3.85%   |
| Netherlands | 1         | 3.85%   |
| Kazakhstan  | 1         | 3.85%   |
| India       | 1         | 3.85%   |
| France      | 1         | 3.85%   |
| Finland     | 1         | 3.85%   |
| Colombia    | 1         | 3.85%   |
| Chile       | 1         | 3.85%   |
| Brazil      | 1         | 3.85%   |
| Argentina   | 1         | 3.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Beijing        | 2         | 7.41%   |
| Vicenza        | 1         | 3.7%    |
| Tashkent       | 1         | 3.7%    |
| Soest          | 1         | 3.7%    |
| Schemmerhofen  | 1         | 3.7%    |
| Sanford        | 1         | 3.7%    |
| Ruda Śląska  | 1         | 3.7%    |
| Ribeirao Preto | 1         | 3.7%    |
| Quitman        | 1         | 3.7%    |
| Puente Alto    | 1         | 3.7%    |
| Persan         | 1         | 3.7%    |
| Mumbai         | 1         | 3.7%    |
| Moscow         | 1         | 3.7%    |
| L'Isle-Adam    | 1         | 3.7%    |
| Kramatorsk     | 1         | 3.7%    |
| Helsinki       | 1         | 3.7%    |
| Don Torcuato   | 1         | 3.7%    |
| Bristow        | 1         | 3.7%    |
| Bogotá        | 1         | 3.7%    |
| Birmensdorf    | 1         | 3.7%    |
| Berlin         | 1         | 3.7%    |
| Battle Creek   | 1         | 3.7%    |
| Barrie         | 1         | 3.7%    |
| Almaty         | 1         | 3.7%    |
| Airdrie        | 1         | 3.7%    |
| Adelfia        | 1         | 3.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 9      | 20.59%  |
| SK hynix            | 4         | 4      | 11.76%  |
| Seagate             | 3         | 3      | 8.82%   |
| Micron Technology   | 3         | 3      | 8.82%   |
| Kingston            | 3         | 4      | 8.82%   |
| HGST                | 3         | 4      | 8.82%   |
| WDC                 | 2         | 2      | 5.88%   |
| Intel               | 2         | 2      | 5.88%   |
| Unknown             | 1         | 1      | 2.94%   |
| Union Memory        | 1         | 1      | 2.94%   |
| Toshiba             | 1         | 1      | 2.94%   |
| SPCC                | 1         | 1      | 2.94%   |
| LITEON              | 1         | 1      | 2.94%   |
| Hjwdz               | 1         | 1      | 2.94%   |
| Hewlett-Packard     | 1         | 1      | 2.94%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| SK hynix BC511 256GB                               | 2         | 5.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 2         | 5.71%   |
| Samsung MZNLH512HALU-00000 512GB SSD               | 2         | 5.71%   |
| Micron 2450_MTFDKBA512TFK 512GB                    | 2         | 5.71%   |
| WDC WD6400BEVT-22A0RT0 640GB                       | 1         | 2.86%   |
| WDC WD5000LPLX-60ZNTT1 500GB                       | 1         | 2.86%   |
| Unknown MMC Card  7GB                              | 1         | 2.86%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB            | 1         | 2.86%   |
| Toshiba MQ04ABF100 1TB                             | 1         | 2.86%   |
| SPCC Solid State Disk 120GB                        | 1         | 2.86%   |
| SK hynix NVMe SSD Drive 256GB                      | 1         | 2.86%   |
| SK hynix BC501 NVMe 256GB                          | 1         | 2.86%   |
| Seagate ST500LT012-9WS142 500GB                    | 1         | 2.86%   |
| Seagate ST1000LM035-1RK172 1TB                     | 1         | 2.86%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 1         | 2.86%   |
| Samsung PSSD T7 1TB                                | 1         | 2.86%   |
| Samsung NVMe SSD Drive 1TB                         | 1         | 2.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 1         | 2.86%   |
| Samsung MZALQ512HALU-000L2 512GB                   | 1         | 2.86%   |
| Micron 2200S NVMe 512GB                            | 1         | 2.86%   |
| LITEON IT LST-32S9G-HP 32GB SSD                    | 1         | 2.86%   |
| Kingston SH103S3240G 240GB SSD                     | 1         | 2.86%   |
| Kingston SA400S37240G 240GB SSD                    | 1         | 2.86%   |
| Kingston RBU-SC100S37128GD 128GB SSD               | 1         | 2.86%   |
| Intel SSDSCKKF256H6L 256GB                         | 1         | 2.86%   |
| Intel SSDPEKNW512G8L 512GB                         | 1         | 2.86%   |
| Hjwdz MS2160 8MB                                   | 1         | 2.86%   |
| HGST HTS725032A7E630 320GB                         | 1         | 2.86%   |
| HGST HTS721010A9E630 1TB                           | 1         | 2.86%   |
| HGST HTS541010A9E680 1TB                           | 1         | 2.86%   |
| HP SSD S700 500GB                                  | 1         | 2.86%   |

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
| Samsung Electronics | 3         | 4      | 30%     |
| Kingston            | 3         | 4      | 30%     |
| SPCC                | 1         | 1      | 10%     |
| LITEON              | 1         | 1      | 10%     |
| Intel               | 1         | 1      | 10%     |
| Hewlett-Packard     | 1         | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 12        | 14     | 37.5%   |
| SSD     | 9         | 12     | 28.13%  |
| HDD     | 9         | 10     | 28.13%  |
| MMC     | 1         | 1      | 3.13%   |
| Unknown | 1         | 1      | 3.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 16        | 20     | 51.61%  |
| NVMe | 12        | 14     | 38.71%  |
| SAS  | 2         | 3      | 6.45%   |
| MMC  | 1         | 1      | 3.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 10        | 11     | 55.56%  |
| 0.51-1.0   | 8         | 11     | 44.44%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 11        | 40.74%  |
| 251-500    | 8         | 29.63%  |
| 501-1000   | 4         | 14.81%  |
| 1001-2000  | 2         | 7.41%   |
| 2001-3000  | 1         | 3.7%    |
| 51-100     | 1         | 3.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 15        | 55.56%  |
| 101-250   | 5         | 18.52%  |
| 251-500   | 3         | 11.11%  |
| 21-50     | 2         | 7.41%   |
| 1001-2000 | 1         | 3.7%    |
| 51-100    | 1         | 3.7%    |

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
| Works    | 13        | 17     | 48.15%  |
| Detected | 12        | 19     | 44.44%  |
| Malfunc  | 2         | 2      | 7.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 18        | 56.25%  |
| SK hynix                | 4         | 12.5%   |
| Samsung Electronics     | 4         | 12.5%   |
| Micron Technology       | 3         | 9.38%   |
| AMD                     | 2         | 6.25%   |
| Union Memory (Shenzhen) | 1         | 3.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 11.43%  |
| SK hynix BC511 NVMe SSD                                                        | 2         | 5.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 5.71%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2         | 5.71%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 5.71%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 5.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 5.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 5.71%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 5.71%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 5.71%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                          | 1         | 2.86%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 2.86%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 2.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 2.86%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 1         | 2.86%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 2.86%   |
| Intel SSD 660P Series                                                          | 1         | 2.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 2.86%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 2.86%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 2.86%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 1         | 2.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 2.86%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 2.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 19        | 57.58%  |
| NVMe | 12        | 36.36%  |
| RAID | 2         | 6.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 21        | 80.77%  |
| AMD    | 5         | 19.23%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 3.85%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 3.85%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 3.85%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 3.85%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 3.85%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 3.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 3.85%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 3.85%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 3.85%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 3.85%   |
| Intel Core i5-3380M CPU @ 2.90GHz             | 1         | 3.85%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 3.85%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 3.85%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 3.85%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 1         | 3.85%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 3.85%   |
| Intel 12th Gen Core i7-12800H                 | 1         | 3.85%   |
| Intel 12th Gen Core i7-12700H                 | 1         | 3.85%   |
| Intel 12th Gen Core i7-1260P                  | 1         | 3.85%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 3.85%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 3.85%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 3.85%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 3.85%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 3.85%   |
| AMD Ryzen 3 PRO 4450U with Radeon Graphics    | 1         | 3.85%   |
| AMD A10-4600M APU with Radeon HD Graphics     | 1         | 3.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i5   | 9         | 34.62%  |
| Intel Core i7   | 6         | 23.08%  |
| Other           | 5         | 19.23%  |
| AMD Ryzen 5     | 2         | 7.69%   |
| Intel Core i3   | 1         | 3.85%   |
| AMD Ryzen 7     | 1         | 3.85%   |
| AMD Ryzen 3 PRO | 1         | 3.85%   |
| AMD A10         | 1         | 3.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 11        | 42.31%  |
| 4      | 9         | 34.62%  |
| 14     | 2         | 7.69%   |
| 6      | 2         | 7.69%   |
| 12     | 1         | 3.85%   |
| 8      | 1         | 3.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 26        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 24        | 92.31%  |
| 1      | 2         | 7.69%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 26        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306a9    | 4         | 15.38%  |
| Unknown    | 4         | 15.38%  |
| 0x906a3    | 3         | 11.54%  |
| 0x08600106 | 3         | 11.54%  |
| 0x806ec    | 2         | 7.69%   |
| 0x406e3    | 2         | 7.69%   |
| 0x40651    | 2         | 7.69%   |
| 0x306c3    | 2         | 7.69%   |
| 0xa0652    | 1         | 3.85%   |
| 0x706e5    | 1         | 3.85%   |
| 0x20652    | 1         | 3.85%   |
| 0x06001119 | 1         | 3.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| IvyBridge        | 4         | 15.38%  |
| Haswell          | 4         | 15.38%  |
| Zen 2            | 3         | 11.54%  |
| KabyLake         | 3         | 11.54%  |
| Alderlake Hybrid | 3         | 11.54%  |
| TigerLake        | 2         | 7.69%   |
| Skylake          | 2         | 7.69%   |
| Zen+             | 1         | 3.85%   |
| Westmere         | 1         | 3.85%   |
| Piledriver       | 1         | 3.85%   |
| IceLake          | 1         | 3.85%   |
| CometLake        | 1         | 3.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 19        | 48.72%  |
| Nvidia | 13        | 33.33%  |
| AMD    | 7         | 17.95%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                     | 4         | 10%     |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                            | 3         | 7.5%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]        | 3         | 7.5%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 2         | 5%      |
| Intel Skylake GT2 [HD Graphics 520]                                  | 2         | 5%      |
| Intel Haswell-ULT Integrated Graphics Controller                     | 2         | 5%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller          | 2         | 5%      |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                      | 1         | 2.5%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                              | 1         | 2.5%    |
| Nvidia GP108M [GeForce MX330]                                        | 1         | 2.5%    |
| Nvidia GP108M [GeForce MX250]                                        | 1         | 2.5%    |
| Nvidia GP107M [GeForce MX350]                                        | 1         | 2.5%    |
| Nvidia GM108M [GeForce MX110]                                        | 1         | 2.5%    |
| Nvidia GM107M [GeForce GTX 850M]                                     | 1         | 2.5%    |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                | 1         | 2.5%    |
| Nvidia GK208M [GeForce GT 740M]                                      | 1         | 2.5%    |
| Nvidia GK107M [GeForce GT 745M]                                      | 1         | 2.5%    |
| Nvidia GF108M [NVS 5400M]                                            | 1         | 2.5%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                      | 1         | 2.5%    |
| Nvidia GA103M [GeForce RTX 3080 Ti Mobile]                           | 1         | 2.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                           | 1         | 2.5%    |
| Intel Iris Plus Graphics G7                                          | 1         | 2.5%    |
| Intel HD Graphics 630                                                | 1         | 2.5%    |
| Intel CometLake-U GT2 [UHD Graphics]                                 | 1         | 2.5%    |
| AMD Trinity [Radeon HD 7660G]                                        | 1         | 2.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 1         | 2.5%    |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                         | 1         | 2.5%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]              | 1         | 2.5%    |
| AMD Mars [Radeon HD 8730M]                                           | 1         | 2.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 11        | 42.31%  |
| 1 x Intel      | 7         | 26.92%  |
| 1 x AMD        | 4         | 15.38%  |
| 2 x AMD        | 1         | 3.85%   |
| 1 x Nvidia     | 1         | 3.85%   |
| Intel + AMD    | 1         | 3.85%   |
| AMD + Nvidia   | 1         | 3.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 23        | 88.46%  |
| Proprietary | 2         | 7.69%   |
| Unknown     | 1         | 3.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 11        | 40.74%  |
| 1.01-2.0   | 5         | 18.52%  |
| 0.01-0.5   | 4         | 14.81%  |
| 5.01-6.0   | 2         | 7.41%   |
| 3.01-4.0   | 2         | 7.41%   |
| 0.51-1.0   | 2         | 7.41%   |
| 8.01-16.0  | 1         | 3.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 8         | 25.81%  |
| Chimei Innolux          | 5         | 16.13%  |
| AU Optronics            | 4         | 12.9%   |
| Samsung Electronics     | 2         | 6.45%   |
| BOE                     | 2         | 6.45%   |
| TMX                     | 1         | 3.23%   |
| SKY                     | 1         | 3.23%   |
| Sharp                   | 1         | 3.23%   |
| PANDA                   | 1         | 3.23%   |
| Hewlett-Packard         | 1         | 3.23%   |
| Goldstar                | 1         | 3.23%   |
| Dell                    | 1         | 3.23%   |
| Chi Mei Optoelectronics | 1         | 3.23%   |
| CHD                     | 1         | 3.23%   |
| Acer                    | 1         | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch                  | 1         | 3.23%   |
| SKY 22X1-M225F SKY2150 1920x1080 476x268mm 21.5-inch                     | 1         | 3.23%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 1         | 3.23%   |
| Samsung Electronics SMT22A350 SAM07A7 1920x1080 477x268mm 21.5-inch      | 1         | 3.23%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 1         | 3.23%   |
| PANDA LCD Monitor NCP0052 1920x1080 309x174mm 14.0-inch                  | 1         | 3.23%   |
| LG Display LCD Monitor LGD068A 1920x1080 309x174mm 14.0-inch             | 1         | 3.23%   |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch             | 1         | 3.23%   |
| LG Display LCD Monitor LGD05E4 1920x1080 344x194mm 15.5-inch             | 1         | 3.23%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 1         | 3.23%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch             | 1         | 3.23%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch              | 1         | 3.23%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 1         | 3.23%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch              | 1         | 3.23%   |
| Hewlett-Packard L185x HWP298C 1366x768 410x230mm 18.5-inch               | 1         | 3.23%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 1         | 3.23%   |
| Dell P2214H DELA098 1920x1080 477x268mm 21.5-inch                        | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN1608 1920x1080 355x199mm 16.0-inch         | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch         | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch          | 1         | 3.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 1         | 3.23%   |
| CHD 24VCF CHD0240 1920x1080 368x207mm 16.6-inch                          | 1         | 3.23%   |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                    | 1         | 3.23%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO5A3D 1920x1080 309x174mm 14.0-inch           | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch           | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO0BA2 2560x1440 309x174mm 14.0-inch           | 1         | 3.23%   |
| Acer KA272 A ACR079A 1920x1080 598x336mm 27.0-inch                       | 1         | 3.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 15        | 55.56%  |
| 1366x768 (WXGA) | 7         | 25.93%  |
| 1600x900 (HD+)  | 2         | 7.41%   |
| 3840x2160 (4K)  | 1         | 3.7%    |
| 3200x2000       | 1         | 3.7%    |
| 2560x1440 (QHD) | 1         | 3.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 11        | 35.48%  |
| 14     | 10        | 32.26%  |
| 21     | 3         | 9.68%   |
| 27     | 1         | 3.23%   |
| 24     | 1         | 3.23%   |
| 23     | 1         | 3.23%   |
| 18     | 1         | 3.23%   |
| 17     | 1         | 3.23%   |
| 16     | 1         | 3.23%   |
| 13     | 1         | 3.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 22        | 73.33%  |
| 401-500     | 4         | 13.33%  |
| 501-600     | 2         | 6.67%   |
| 351-400     | 2         | 6.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 23        | 95.83%  |
| 16/10 | 1         | 4.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 11        | 36.67%  |
| 101-110        | 11        | 36.67%  |
| 201-250        | 3         | 10%     |
| 301-350        | 1         | 3.33%   |
| 151-200        | 1         | 3.33%   |
| 141-150        | 1         | 3.33%   |
| 121-130        | 1         | 3.33%   |
| 111-120        | 1         | 3.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 16        | 53.33%  |
| 101-120       | 8         | 26.67%  |
| 51-100        | 4         | 13.33%  |
| More than 240 | 1         | 3.33%   |
| 161-240       | 1         | 3.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 18        | 69.23%  |
| 2     | 5         | 19.23%  |
| 0     | 2         | 7.69%   |
| 3     | 1         | 3.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 17        | 42.5%   |
| Realtek Semiconductor             | 10        | 25%     |
| Qualcomm Atheros                  | 7         | 17.5%   |
| Broadcom                          | 3         | 7.5%    |
| Xiaomi                            | 1         | 2.5%    |
| Ericsson Business Mobile Networks | 1         | 2.5%    |
| ASUSTek Computer                  | 1         | 2.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 10        | 20.83%  |
| Intel Wireless 7260                                                    | 3         | 6.25%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 3         | 6.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 4.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 2         | 4.17%   |
| Intel Wireless 8260                                                    | 2         | 4.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 2         | 4.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 4.17%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 2.08%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1         | 2.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1         | 2.08%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 2.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 1         | 2.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 1         | 2.08%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 2.08%   |
| Intel Wireless 8265 / 8275                                             | 1         | 2.08%   |
| Intel Wi-Fi 6 AX201                                                    | 1         | 2.08%   |
| Intel Wi-Fi 6 AX200                                                    | 1         | 2.08%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 1         | 2.08%   |
| Intel Ethernet Connection I219-V                                       | 1         | 2.08%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 2.08%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 2.08%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 1         | 2.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 1         | 2.08%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 1         | 2.08%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module     | 1         | 2.08%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 1         | 2.08%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 2.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 1         | 2.08%   |
| ASUS 802.11ac NIC                                                      | 1         | 2.08%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 17        | 62.96%  |
| Qualcomm Atheros      | 6         | 22.22%  |
| Realtek Semiconductor | 2         | 7.41%   |
| Broadcom              | 1         | 3.7%    |
| ASUSTek Computer      | 1         | 3.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 3         | 11.11%  |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 11.11%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 7.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 7.41%   |
| Intel Wireless 8260                                            | 2         | 7.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 7.41%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 3.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 3.7%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 3.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 3.7%    |
| Intel Wireless 8265 / 8275                                     | 1         | 3.7%    |
| Intel Wi-Fi 6 AX201                                            | 1         | 3.7%    |
| Intel Wi-Fi 6 AX200                                            | 1         | 3.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 3.7%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 3.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 3.7%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 3.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 3.7%    |
| ASUS 802.11ac NIC                                              | 1         | 3.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 10        | 50%     |
| Intel                 | 5         | 25%     |
| Qualcomm Atheros      | 2         | 10%     |
| Broadcom              | 2         | 10%     |
| Xiaomi                | 1         | 5%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 10        | 50%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 10%     |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 5%      |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 5%      |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 5%      |
| Intel Ethernet Connection I219-V                                       | 1         | 5%      |
| Intel Ethernet Connection I219-LM                                      | 1         | 5%      |
| Intel Ethernet Connection I218-LM                                      | 1         | 5%      |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 1         | 5%      |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 5%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 56.52%  |
| Ethernet | 19        | 41.3%   |
| Modem    | 1         | 2.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 22        | 88%     |
| Ethernet | 3         | 12%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 19        | 73.08%  |
| 1     | 7         | 26.92%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 19        | 73.08%  |
| Yes  | 7         | 26.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 60.87%  |
| Qualcomm Atheros Communications | 3         | 13.04%  |
| Realtek Semiconductor           | 2         | 8.7%    |
| Lite-On Technology              | 2         | 8.7%    |
| Broadcom                        | 2         | 8.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 7         | 30.43%  |
| Realtek Bluetooth Radio                        | 2         | 8.7%    |
| Intel Bluetooth Device                         | 2         | 8.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 2         | 8.7%    |
| Intel AX201 Bluetooth                          | 2         | 8.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 2         | 8.7%    |
| Qualcomm Atheros  Bluetooth Device             | 1         | 4.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 1         | 4.35%   |
| Qualcomm Atheros AR3011 Bluetooth              | 1         | 4.35%   |
| Lite-On Bluetooth Device                       | 1         | 4.35%   |
| Lite-On Atheros AR3012 Bluetooth               | 1         | 4.35%   |
| Intel AX200 Bluetooth                          | 1         | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 20        | 60.61%  |
| AMD    | 7         | 21.21%  |
| Nvidia | 5         | 15.15%  |
| JBL    | 1         | 3.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 4         | 9.52%   |
| AMD Family 17h/19h HD Audio Controller                                  | 4         | 9.52%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                 | 3         | 7.14%   |
| AMD Renoir Radeon High Definition Audio Controller                      | 3         | 7.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 2         | 4.76%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 2         | 4.76%   |
| Intel Haswell-ULT HD Audio Controller                                   | 2         | 4.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 2         | 4.76%   |
| Intel 8 Series HD Audio Controller                                      | 2         | 4.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 1         | 2.38%   |
| Nvidia TU106 High Definition Audio Controller                           | 1         | 2.38%   |
| Nvidia GF108 High Definition Audio Controller                           | 1         | 2.38%   |
| Nvidia GA106 High Definition Audio Controller                           | 1         | 2.38%   |
| Nvidia Audio device                                                     | 1         | 2.38%   |
| JBL Quantum 600                                                         | 1         | 2.38%   |
| Intel Sunrise Point-LP HD Audio                                         | 1         | 2.38%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller               | 1         | 2.38%   |
| Intel Comet Lake PCH-LP cAVS                                            | 1         | 2.38%   |
| Intel Comet Lake PCH cAVS                                               | 1         | 2.38%   |
| Intel CM238 HD Audio Controller                                         | 1         | 2.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                  | 1         | 2.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                | 1         | 2.38%   |
| AMD Trinity HDMI Audio Controller                                       | 1         | 2.38%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 1         | 2.38%   |
| AMD Navi 10 HDMI Audio                                                  | 1         | 2.38%   |
| AMD FCH Azalia Controller                                               | 1         | 2.38%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                  | 1         | 2.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 44.44%  |
| SK hynix            | 3         | 16.67%  |
| Smart Brazil        | 1         | 5.56%   |
| SHARETRONIC         | 1         | 5.56%   |
| Kingston            | 1         | 5.56%   |
| G.Skill             | 1         | 5.56%   |
| Crucial             | 1         | 5.56%   |
| Corsair             | 1         | 5.56%   |
| A-DATA Technology   | 1         | 5.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s | 1         | 5.26%   |
| SK hynix RAM HMT125S6BFR8C-G7 2048MB SODIMM DDR3 1067MT/s    | 1         | 5.26%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 5.26%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 1         | 5.26%   |
| SHARETRONIC RAM Module 4GB SODIMM DDR3 800MT/s               | 1         | 5.26%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 5.26%   |
| Samsung RAM M474A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s       | 1         | 5.26%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 1         | 5.26%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 5.26%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s     | 1         | 5.26%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 5.26%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 1         | 5.26%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 5.26%   |
| Samsung RAM K4UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s | 1         | 5.26%   |
| Kingston RAM 9905417-083.A00G 4GB SODIMM DDR3 1600MT/s       | 1         | 5.26%   |
| G.Skill RAM F3-1600C9-8GRSL 8GB SODIMM DDR3 1600MT/s         | 1         | 5.26%   |
| Crucial RAM CT16G4SFRA32A.M16FR 16GB SODIMM DDR4 3200MT/s    | 1         | 5.26%   |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s      | 1         | 5.26%   |
| A-DATA RAM Module 32GB SODIMM DDR4 3200MT/s                  | 1         | 5.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 8         | 53.33%  |
| DDR3   | 6         | 40%     |
| LPDDR4 | 1         | 6.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 13        | 86.67%  |
| Row Of Chips | 2         | 13.33%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 8         | 47.06%  |
| 4096  | 4         | 23.53%  |
| 16384 | 3         | 17.65%  |
| 32768 | 1         | 5.88%   |
| 2048  | 1         | 5.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 4         | 23.53%  |
| 1600  | 4         | 23.53%  |
| 2667  | 3         | 17.65%  |
| 4267  | 1         | 5.88%   |
| 2400  | 1         | 5.88%   |
| 2133  | 1         | 5.88%   |
| 1334  | 1         | 5.88%   |
| 1067  | 1         | 5.88%   |
| 800   | 1         | 5.88%   |

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
| Chicony Electronics                    | 5         | 21.74%  |
| IMC Networks                           | 3         | 13.04%  |
| Bison Electronics                      | 3         | 13.04%  |
| Syntek                                 | 2         | 8.7%    |
| Realtek Semiconductor                  | 2         | 8.7%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 8.7%    |
| Sunplus Innovation Technology          | 1         | 4.35%   |
| Silicon Motion                         | 1         | 4.35%   |
| Microdia                               | 1         | 4.35%   |
| Luxvisions Innotech Limited            | 1         | 4.35%   |
| Apple                                  | 1         | 4.35%   |
| Acer                                   | 1         | 4.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                            | 2         | 8.7%    |
| Sunplus Integrated_Webcam_HD                        | 1         | 4.35%   |
| Silicon Motion WebCam SC-13HDL11939N                | 1         | 4.35%   |
| Realtek Lenovo EasyCamera                           | 1         | 4.35%   |
| Realtek Integrated_Webcam_HD                        | 1         | 4.35%   |
| Microdia Integrated_Webcam_HD                       | 1         | 4.35%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 4.35%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 4.35%   |
| IMC Networks Integrated RGB Camera                  | 1         | 4.35%   |
| IMC Networks Integrated Camera                      | 1         | 4.35%   |
| Chicony Thinkpad T430 camera                        | 1         | 4.35%   |
| Chicony Integrated Camera                           | 1         | 4.35%   |
| Chicony HD WebCam (Asus N-series)                   | 1         | 4.35%   |
| Chicony HD WebCam                                   | 1         | 4.35%   |
| Chicony Acer CrystalEye Webcam                      | 1         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 4.35%   |
| Bison Lenovo Integrated Webcam                      | 1         | 4.35%   |
| Bison Integrated Camera                             | 1         | 4.35%   |
| Bison HD Webcam                                     | 1         | 4.35%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 1         | 4.35%   |
| Acer Integrated Camera                              | 1         | 4.35%   |

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
| 0     | 17        | 62.96%  |
| 1     | 7         | 25.93%  |
| 2     | 3         | 11.11%  |

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

