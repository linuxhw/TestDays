LMDE 5 - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for LMDE 5.

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

Total: 32

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Dell     | 0XR1GT A00                  | [0d72ab6a71](https://linux-hardware.org/?probe=0d72ab6a71) | Jun 24, 2022 |
| Lenovo   | 3731 NOK                    | [efd1e69f79](https://linux-hardware.org/?probe=efd1e69f79) | Jun 09, 2022 |
| Lenovo   | 3731 NOK                    | [1da6b9f6c0](https://linux-hardware.org/?probe=1da6b9f6c0) | Jun 09, 2022 |
| Dell     | 0XR1GT A00                  | [8c3fd28612](https://linux-hardware.org/?probe=8c3fd28612) | Jun 08, 2022 |
| MSI      | MPG Z390 GAMING PRO CARB... | [6f8785bd56](https://linux-hardware.org/?probe=6f8785bd56) | May 30, 2022 |
| Lenovo   | MAHOBAY                     | [ba204646ba](https://linux-hardware.org/?probe=ba204646ba) | May 25, 2022 |
| Acer     | Seawolf                     | [dccbcb7ef3](https://linux-hardware.org/?probe=dccbcb7ef3) | May 25, 2022 |
| Intel    | DQ77MK AAG39642-400         | [f694bcfbc5](https://linux-hardware.org/?probe=f694bcfbc5) | May 21, 2022 |
| MSI      | X470 GAMING PLUS MAX        | [63950495b3](https://linux-hardware.org/?probe=63950495b3) | May 15, 2022 |
| MSI      | 970A-G43 PLUS               | [399deea7b9](https://linux-hardware.org/?probe=399deea7b9) | May 15, 2022 |
| Gigabyte | Z68A-D3H-B3                 | [1441dfb79e](https://linux-hardware.org/?probe=1441dfb79e) | May 07, 2022 |
| HP       | 158B                        | [a613debdee](https://linux-hardware.org/?probe=a613debdee) | May 06, 2022 |
| HP       | 158B                        | [21f9c188f3](https://linux-hardware.org/?probe=21f9c188f3) | May 06, 2022 |
| HP       | 339A                        | [d58b95ebb1](https://linux-hardware.org/?probe=d58b95ebb1) | May 05, 2022 |
| Gigabyte | H110M-S2H-CF                | [c45a37ce5d](https://linux-hardware.org/?probe=c45a37ce5d) | May 01, 2022 |
| ASUSTek  | PRIME H610M-A D4            | [e9376d24f0](https://linux-hardware.org/?probe=e9376d24f0) | Apr 29, 2022 |
| ASRock   | A320M-DGS                   | [b7df060840](https://linux-hardware.org/?probe=b7df060840) | Apr 19, 2022 |
| ASRock   | A320M-DGS                   | [70fe08376f](https://linux-hardware.org/?probe=70fe08376f) | Apr 19, 2022 |
| Dell     | 0CU568 A00                  | [b544c48421](https://linux-hardware.org/?probe=b544c48421) | Apr 19, 2022 |
| Dell     | 0CU568 A00                  | [84f7029c22](https://linux-hardware.org/?probe=84f7029c22) | Apr 19, 2022 |
| ASUSTek  | PRIME B350M-A               | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| ASUSTek  | PRIME B350M-A               | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| MSI      | Z170A GAMING M5             | [8f2e10cbf3](https://linux-hardware.org/?probe=8f2e10cbf3) | Apr 12, 2022 |
| Lenovo   | 312A SDK0J40697 WIN 3305... | [2a33f087e6](https://linux-hardware.org/?probe=2a33f087e6) | Apr 11, 2022 |
| Lenovo   | 312A SDK0J40697 WIN 3305... | [05b9ec80c6](https://linux-hardware.org/?probe=05b9ec80c6) | Apr 11, 2022 |
| Acer     | WG43M                       | [c7cb6ee141](https://linux-hardware.org/?probe=c7cb6ee141) | Apr 08, 2022 |
| ASUSTek  | P5G41T-M LX3                | [28371c08c2](https://linux-hardware.org/?probe=28371c08c2) | Apr 08, 2022 |
| MSI      | X470 GAMING PLUS MAX        | [9f1a76acb8](https://linux-hardware.org/?probe=9f1a76acb8) | Apr 06, 2022 |
| MSI      | X470 GAMING PLUS MAX        | [18a4ba3137](https://linux-hardware.org/?probe=18a4ba3137) | Apr 06, 2022 |
| ASUSTek  | P6T                         | [5ed6ed355f](https://linux-hardware.org/?probe=5ed6ed355f) | Apr 04, 2022 |
| ASUSTek  | PRIME H510M-D               | [1e0a28c8f3](https://linux-hardware.org/?probe=1e0a28c8f3) | Mar 28, 2022 |
| HP       | 0AE8h C                     | [d3980b5b59](https://linux-hardware.org/?probe=d3980b5b59) | Mar 14, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Desktops | Percent |
|-----------------|----------|---------|
| 5.10.0-14-amd64 | 10       | 41.67%  |
| 5.10.0-13-amd64 | 10       | 41.67%  |
| 5.10.0-12-amd64 | 3        | 12.5%   |
| 5.10.0-13-686   | 1        | 4.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 23       | 100%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 23       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 22       | 95.65%  |
| i686   | 1        | 4.35%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| X-Cinnamon | 20       | 86.96%  |
| XFCE       | 1        | 4.35%   |
| MATE       | 1        | 4.35%   |
| Cinnamon   | 1        | 4.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 23       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 15       | 65.22%  |
| LightDM | 8        | 34.78%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 9        | 39.13%  |
| ru_RU | 2        | 8.7%    |
| es_ES | 2        | 8.7%    |
| en_GB | 2        | 8.7%    |
| de_DE | 2        | 8.7%    |
| pt_BR | 1        | 4.35%   |
| it_IT | 1        | 4.35%   |
| fr_CA | 1        | 4.35%   |
| en_CA | 1        | 4.35%   |
| en_AU | 1        | 4.35%   |
| ar_EG | 1        | 4.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 12       | 52.17%  |
| EFI  | 11       | 47.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 22       | 95.65%  |
| Tmpfs | 1        | 4.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 15       | 65.22%  |
| GPT     | 5        | 21.74%  |
| MBR     | 3        | 13.04%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 86.96%  |
| Yes       | 3        | 13.04%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 82.61%  |
| Yes       | 4        | 17.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 5        | 21.74%  |
| MSI                 | 4        | 17.39%  |
| Lenovo              | 3        | 13.04%  |
| Hewlett-Packard     | 3        | 13.04%  |
| Gigabyte Technology | 2        | 8.7%    |
| Dell                | 2        | 8.7%    |
| Acer                | 2        | 8.7%    |
| Intel               | 1        | 4.35%   |
| ASRock              | 1        | 4.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| MSI MS-7B79                         | 1        | 4.35%   |
| MSI MS-7B17                         | 1        | 4.35%   |
| MSI MS-7977                         | 1        | 4.35%   |
| MSI MS-7974                         | 1        | 4.35%   |
| Lenovo V55t-15ARE 11KJ0036TX        | 1        | 4.35%   |
| Lenovo ThinkCentre M92p 3238E9U     | 1        | 4.35%   |
| Lenovo ThinkCentre M720s 10SUS9KW00 | 1        | 4.35%   |
| Intel DQ77MK AAG39642-400           | 1        | 4.35%   |
| HP Z820 Workstation                 | 1        | 4.35%   |
| HP Z600 Workstation                 | 1        | 4.35%   |
| HP Compaq Pro 6300 SFF              | 1        | 4.35%   |
| Gigabyte Z68A-D3H-B3                | 1        | 4.35%   |
| Gigabyte H110M-S2H                  | 1        | 4.35%   |
| Dell XPS A2010                      | 1        | 4.35%   |
| Dell Inspiron 660                   | 1        | 4.35%   |
| ASUS PRIME H610M-A D4               | 1        | 4.35%   |
| ASUS PRIME H510M-D                  | 1        | 4.35%   |
| ASUS PRIME B350M-A                  | 1        | 4.35%   |
| ASUS P6T                            | 1        | 4.35%   |
| ASUS P5G41T-M LX3                   | 1        | 4.35%   |
| ASRock A320M-DGS                    | 1        | 4.35%   |
| Acer Veriton L6610G                 | 1        | 4.35%   |
| Acer Aspire X3910                   | 1        | 4.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 3        | 13.04%  |
| Lenovo ThinkCentre   | 2        | 8.7%    |
| MSI MS-7B79          | 1        | 4.35%   |
| MSI MS-7B17          | 1        | 4.35%   |
| MSI MS-7977          | 1        | 4.35%   |
| MSI MS-7974          | 1        | 4.35%   |
| Lenovo V55t-15ARE    | 1        | 4.35%   |
| Intel DQ77MK         | 1        | 4.35%   |
| HP Z820              | 1        | 4.35%   |
| HP Z600              | 1        | 4.35%   |
| HP Compaq            | 1        | 4.35%   |
| Gigabyte Z68A-D3H-B3 | 1        | 4.35%   |
| Gigabyte H110M-S2H   | 1        | 4.35%   |
| Dell XPS             | 1        | 4.35%   |
| Dell Inspiron        | 1        | 4.35%   |
| ASUS P6T             | 1        | 4.35%   |
| ASUS P5G41T-M        | 1        | 4.35%   |
| ASRock A320M-DGS     | 1        | 4.35%   |
| Acer Veriton         | 1        | 4.35%   |
| Acer Aspire          | 1        | 4.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 4        | 17.39%  |
| 2018 | 3        | 13.04%  |
| 2021 | 2        | 8.7%    |
| 2019 | 2        | 8.7%    |
| 2017 | 2        | 8.7%    |
| 2015 | 2        | 8.7%    |
| 2009 | 2        | 8.7%    |
| 2020 | 1        | 4.35%   |
| 2016 | 1        | 4.35%   |
| 2011 | 1        | 4.35%   |
| 2010 | 1        | 4.35%   |
| 2008 | 1        | 4.35%   |
| 2007 | 1        | 4.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 23       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 23       | 95.83%  |
| Enabled  | 1        | 4.17%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 23       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 7        | 29.17%  |
| 16.01-24.0 | 6        | 25%     |
| 32.01-64.0 | 4        | 16.67%  |
| 24.01-32.0 | 2        | 8.33%   |
| 1.01-2.0   | 2        | 8.33%   |
| 8.01-16.0  | 2        | 8.33%   |
| 3.01-4.0   | 1        | 4.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 2.01-3.0 | 10       | 43.48%  |
| 3.01-4.0 | 5        | 21.74%  |
| 1.01-2.0 | 5        | 21.74%  |
| 0.51-1.0 | 2        | 8.7%    |
| 4.01-8.0 | 1        | 4.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 11       | 47.83%  |
| 3      | 5        | 21.74%  |
| 4      | 3        | 13.04%  |
| 2      | 3        | 13.04%  |
| 6      | 1        | 4.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 12       | 52.17%  |
| No        | 11       | 47.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 23       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 12       | 52.17%  |
| No        | 11       | 47.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 78.26%  |
| Yes       | 5        | 21.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 4        | 17.39%  |
| UK        | 2        | 8.7%    |
| Spain     | 2        | 8.7%    |
| Russia    | 2        | 8.7%    |
| Canada    | 2        | 8.7%    |
| Australia | 2        | 8.7%    |
| Venezuela | 1        | 4.35%   |
| Turkey    | 1        | 4.35%   |
| Sweden    | 1        | 4.35%   |
| Mexico    | 1        | 4.35%   |
| Latvia    | 1        | 4.35%   |
| Italy     | 1        | 4.35%   |
| Germany   | 1        | 4.35%   |
| France    | 1        | 4.35%   |
| Brazil    | 1        | 4.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Melbourne                | 2        | 8.7%    |
| Vincennes                | 1        | 4.35%   |
| Vicente Guerrero         | 1        | 4.35%   |
| Trieste                  | 1        | 4.35%   |
| Toledo                   | 1        | 4.35%   |
| Stockbridge              | 1        | 4.35%   |
| Spruce Grove             | 1        | 4.35%   |
| Sant Feliu de Llobregat  | 1        | 4.35%   |
| San Antonio de Los Altos | 1        | 4.35%   |
| Riga                     | 1        | 4.35%   |
| Prestatyn                | 1        | 4.35%   |
| Porto Alegre             | 1        | 4.35%   |
| National City            | 1        | 4.35%   |
| Moscow                   | 1        | 4.35%   |
| Montreal                 | 1        | 4.35%   |
| Madrid                   | 1        | 4.35%   |
| Hamburg                  | 1        | 4.35%   |
| Detroit                  | 1        | 4.35%   |
| Birmingham               | 1        | 4.35%   |
| Arkhangelsk              | 1        | 4.35%   |
| AElvdalen                | 1        | 4.35%   |
| Adapazarı               | 1        | 4.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 15     | 18.42%  |
| Seagate             | 7        | 9      | 18.42%  |
| Samsung Electronics | 5        | 6      | 13.16%  |
| Kingston            | 4        | 4      | 10.53%  |
| Hitachi             | 3        | 4      | 7.89%   |
| Crucial             | 3        | 3      | 7.89%   |
| Toshiba             | 2        | 2      | 5.26%   |
| Transcend           | 1        | 2      | 2.63%   |
| SK hynix            | 1        | 1      | 2.63%   |
| SanDisk             | 1        | 1      | 2.63%   |
| OCZ-VERTEX          | 1        | 1      | 2.63%   |
| Intel               | 1        | 1      | 2.63%   |
| Hewlett-Packard     | 1        | 1      | 2.63%   |
| A-DATA Technology   | 1        | 1      | 2.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB        | 2        | 4.65%   |
| Samsung SSD 850 EVO 250GB             | 2        | 4.65%   |
| Kingston SA400S37240G 240GB SSD       | 2        | 4.65%   |
| Crucial CT480BX500SSD1 480GB          | 2        | 4.65%   |
| WDC WD60EZAZ-00ZGHB0 6TB              | 1        | 2.33%   |
| WDC WD5000AAKX-75U6AA0 500GB          | 1        | 2.33%   |
| WDC WD3200AAJS-22B4A0 320GB           | 1        | 2.33%   |
| WDC WD30EFRX-68EUZN0 3TB              | 1        | 2.33%   |
| WDC WD3003FZEX-00Z4SA0 3TB            | 1        | 2.33%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1        | 2.33%   |
| WDC WD10EFRX-68JCSN0 1TB              | 1        | 2.33%   |
| WDC WD10EFRX-68FYTN0 1TB              | 1        | 2.33%   |
| WDC WD10EAVS-00D7B0 1TB               | 1        | 2.33%   |
| WDC WD1003FZEX-00MK2A0 1TB            | 1        | 2.33%   |
| Transcend TS480GSSD220S 480GB         | 1        | 2.33%   |
| Transcend TS240GSSD220S 240GB         | 1        | 2.33%   |
| Toshiba MK3275GSX 320GB               | 1        | 2.33%   |
| Toshiba DT01ACA050 500GB              | 1        | 2.33%   |
| SK hynix HFS256G32MND-3310A 256GB SSD | 1        | 2.33%   |
| Seagate ST500LT012-1DG142 500GB       | 1        | 2.33%   |
| Seagate ST3500312CS 500GB             | 1        | 2.33%   |
| Seagate ST3250318AS 250GB             | 1        | 2.33%   |
| Seagate ST2000LM007-1R8174 2TB        | 1        | 2.33%   |
| Seagate ST1000LM048-2E7172 1TB        | 1        | 2.33%   |
| Seagate ST1000DM003-1CH162 1TB        | 1        | 2.33%   |
| SanDisk SDSSDA240G 240GB              | 1        | 2.33%   |
| Samsung SSD 970 EVO Plus 1TB          | 1        | 2.33%   |
| Samsung NVMe SSD Drive 1TB            | 1        | 2.33%   |
| Samsung MZMTE128HMGR-000MV 128GB SSD  | 1        | 2.33%   |
| OCZ-VERTEX PLUS R2 128GB SSD          | 1        | 2.33%   |
| Kingston SUV400S37120G 120GB SSD      | 1        | 2.33%   |
| Kingston SA400S37120G 120GB SSD       | 1        | 2.33%   |
| Intel SSDPEKKW256G7 256GB             | 1        | 2.33%   |
| Hitachi HDT725025VLA380 250GB         | 1        | 2.33%   |
| Hitachi HDS5C1032CLA382 320GB         | 1        | 2.33%   |
| Hitachi HDP725050GLA360 500GB         | 1        | 2.33%   |
| HP SSD S700 250GB                     | 1        | 2.33%   |
| Crucial CT525MX300SSD1 528GB          | 1        | 2.33%   |
| A-DATA SU650 120GB SSD                | 1        | 2.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 7        | 15     | 36.84%  |
| Seagate | 7        | 9      | 36.84%  |
| Hitachi | 3        | 4      | 15.79%  |
| Toshiba | 2        | 2      | 10.53%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 4        | 4      | 25%     |
| Samsung Electronics | 3        | 3      | 18.75%  |
| Crucial             | 3        | 3      | 18.75%  |
| Transcend           | 1        | 2      | 6.25%   |
| SK hynix            | 1        | 1      | 6.25%   |
| SanDisk             | 1        | 1      | 6.25%   |
| OCZ-VERTEX          | 1        | 1      | 6.25%   |
| Hewlett-Packard     | 1        | 1      | 6.25%   |
| A-DATA Technology   | 1        | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 16       | 30     | 48.48%  |
| SSD  | 14       | 17     | 42.42%  |
| NVMe | 3        | 4      | 9.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 23       | 47     | 88.46%  |
| NVMe | 3        | 4      | 11.54%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 18       | 27     | 62.07%  |
| 0.51-1.0   | 5        | 10     | 17.24%  |
| 1.01-2.0   | 3        | 4      | 10.34%  |
| 2.01-3.0   | 2        | 5      | 6.9%    |
| 4.01-10.0  | 1        | 1      | 3.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 6        | 26.09%  |
| 101-250        | 5        | 21.74%  |
| 1001-2000      | 3        | 13.04%  |
| More than 3000 | 2        | 8.7%    |
| 1-20           | 2        | 8.7%    |
| 501-1000       | 2        | 8.7%    |
| 51-100         | 2        | 8.7%    |
| 2001-3000      | 1        | 4.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 9        | 37.5%   |
| 21-50     | 4        | 16.67%  |
| 101-250   | 3        | 12.5%   |
| 51-100    | 3        | 12.5%   |
| 1001-2000 | 2        | 8.33%   |
| 501-1000  | 2        | 8.33%   |
| 251-500   | 1        | 4.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB | 1        | 1      | 50%     |
| Seagate ST3250318AS 250GB       | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 2      | 100%    |

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
| Detected | 15       | 31     | 60%     |
| Works    | 8        | 18     | 32%     |
| Malfunc  | 2        | 2      | 8%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 19       | 65.52%  |
| AMD                 | 5        | 17.24%  |
| Samsung Electronics | 2        | 6.9%    |
| JMicron Technology  | 1        | 3.45%   |
| Broadcom / LSI      | 1        | 3.45%   |
| ASMedia Technology  | 1        | 3.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 10.53%  |
| AMD FCH SATA Controller [AHCI mode]                                                     | 3        | 7.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 5.26%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 5.26%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 5.26%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 5.26%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 2.63%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1        | 2.63%   |
| Intel SSD 600P Series                                                                   | 1        | 2.63%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 2.63%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 2.63%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 2.63%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 2.63%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 2.63%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 2.63%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 2.63%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 2.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 1        | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 2.63%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 2.63%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1        | 2.63%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 2.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 2.63%   |
| AMD FCH SATA Controller D                                                               | 1        | 2.63%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 2.63%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 2.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 19       | 61.29%  |
| IDE  | 6        | 19.35%  |
| NVMe | 3        | 9.68%   |
| RAID | 2        | 6.45%   |
| SAS  | 1        | 3.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 18       | 78.26%  |
| AMD    | 5        | 21.74%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 8.7%    |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 8.7%    |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1        | 4.35%   |
| Intel Xeon CPU X5570 @ 2.93GHz              | 1        | 4.35%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 1        | 4.35%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 1        | 4.35%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 4.35%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 4.35%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 4.35%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 4.35%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 4.35%   |
| Intel Core i5-3470S CPU @ 2.90GHz           | 1        | 4.35%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 4.35%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 4.35%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 1        | 4.35%   |
| Intel 12th Gen Core i3-12100F               | 1        | 4.35%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 1        | 4.35%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 1        | 4.35%   |
| AMD Ryzen 5 3350G with Radeon Vega Graphics | 1        | 4.35%   |
| AMD FX-4300 Quad-Core Processor             | 1        | 4.35%   |
| AMD Athlon 220GE with Radeon Vega Graphics  | 1        | 4.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 5        | 21.74%  |
| Intel Core i5           | 4        | 17.39%  |
| Intel Xeon              | 3        | 13.04%  |
| Intel Pentium Dual-Core | 2        | 8.7%    |
| Intel Pentium           | 2        | 8.7%    |
| AMD Ryzen 5             | 2        | 8.7%    |
| Other                   | 1        | 4.35%   |
| Intel Core 2 Duo        | 1        | 4.35%   |
| AMD Ryzen 7             | 1        | 4.35%   |
| AMD FX                  | 1        | 4.35%   |
| AMD Athlon              | 1        | 4.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 9        | 39.13%  |
| 2      | 7        | 30.43%  |
| 8      | 3        | 13.04%  |
| 6      | 3        | 13.04%  |
| 16     | 1        | 4.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 21       | 91.3%   |
| 2      | 2        | 8.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 13       | 56.52%  |
| 1      | 10       | 43.48%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 23       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x206a7    | 3        | 13.04%  |
| 0x506e3    | 2        | 8.7%    |
| 0x306a9    | 2        | 8.7%    |
| 0x1067a    | 2        | 8.7%    |
| 0x08108109 | 2        | 8.7%    |
| 0xa0653    | 1        | 4.35%   |
| 0x906ed    | 1        | 4.35%   |
| 0x906ea    | 1        | 4.35%   |
| 0x90675    | 1        | 4.35%   |
| 0x6fd      | 1        | 4.35%   |
| 0x206d7    | 1        | 4.35%   |
| 0x206c2    | 1        | 4.35%   |
| 0x106a5    | 1        | 4.35%   |
| 0x0810100b | 1        | 4.35%   |
| 0x08001137 | 1        | 4.35%   |
| 0x06000852 | 1        | 4.35%   |
| Unknown    | 1        | 4.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| SandyBridge | 4        | 17.39%  |
| IvyBridge   | 3        | 13.04%  |
| Zen+        | 2        | 8.7%    |
| Zen         | 2        | 8.7%    |
| Skylake     | 2        | 8.7%    |
| Penryn      | 2        | 8.7%    |
| KabyLake    | 2        | 8.7%    |
| Westmere    | 1        | 4.35%   |
| Piledriver  | 1        | 4.35%   |
| Nehalem     | 1        | 4.35%   |
| Core        | 1        | 4.35%   |
| CometLake   | 1        | 4.35%   |
| Unknown     | 1        | 4.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 14       | 56%     |
| Intel  | 6        | 24%     |
| AMD    | 5        | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Nvidia GT218 [GeForce 210]                                                | 3        | 11.54%  |
| Nvidia GK208B [GeForce GT 730]                                            | 2        | 7.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2        | 7.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2        | 7.69%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                     | 1        | 3.85%   |
| Nvidia GP108 [GeForce GT 1030]                                            | 1        | 3.85%   |
| Nvidia GM204 [GeForce GTX 970]                                            | 1        | 3.85%   |
| Nvidia GM107GL [Quadro K620]                                              | 1        | 3.85%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                         | 1        | 3.85%   |
| Nvidia GK208B [GeForce GT 710]                                            | 1        | 3.85%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                         | 1        | 3.85%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                         | 1        | 3.85%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                         | 1        | 3.85%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 1        | 3.85%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                  | 1        | 3.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 1        | 3.85%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                    | 1        | 3.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 1        | 3.85%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]     | 1        | 3.85%   |
| AMD Lexa XT [Radeon PRO WX 3200]                                          | 1        | 3.85%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                            | 1        | 3.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 14       | 58.33%  |
| 1 x Intel    | 5        | 20.83%  |
| 1 x AMD      | 3        | 12.5%   |
| 2 x AMD      | 1        | 4.17%   |
| AMD + Nvidia | 1        | 4.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 18       | 78.26%  |
| Proprietary | 3        | 13.04%  |
| Unknown     | 2        | 8.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 8        | 34.78%  |
| Unknown    | 7        | 30.43%  |
| 3.01-4.0   | 4        | 17.39%  |
| 0.51-1.0   | 3        | 13.04%  |
| 0.01-0.5   | 1        | 4.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 4        | 18.18%  |
| Philips              | 3        | 13.64%  |
| Ancor Communications | 3        | 13.64%  |
| Acer                 | 3        | 13.64%  |
| Hewlett-Packard      | 2        | 9.09%   |
| ___                  | 1        | 4.55%   |
| Unknown              | 1        | 4.55%   |
| Medion               | 1        | 4.55%   |
| Lenovo               | 1        | 4.55%   |
| Dell                 | 1        | 4.55%   |
| BenQ                 | 1        | 4.55%   |
| ASUSTek Computer     | 1        | 4.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ___ LCD TV ___0101 1360x768                                           | 1        | 4.17%   |
| Unknown LCDTV14 0101 1360x768 1600x900mm 72.3-inch                    | 1        | 4.17%   |
| Samsung Electronics SyncMaster SAM0259 1280x1024 380x300mm 19.1-inch  | 1        | 4.17%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch    | 1        | 4.17%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 1        | 4.17%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch    | 1        | 4.17%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch             | 1        | 4.17%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch               | 1        | 4.17%   |
| Philips LCD Monitor PHL 242V8 1920x1080                               | 1        | 4.17%   |
| Medion MD20328 MED3942 1600x900 462x272mm 21.1-inch                   | 1        | 4.17%   |
| Lenovo C24-20 LEN62A8 1920x1080 527x296mm 23.8-inch                   | 1        | 4.17%   |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch           | 1        | 4.17%   |
| Hewlett-Packard E232 HWP327B 1920x1080 509x286mm 23.0-inch            | 1        | 4.17%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch            | 1        | 4.17%   |
| Hewlett-Packard E232 HWP3279 1920x1080 510x290mm 23.1-inch            | 1        | 4.17%   |
| Dell 2007WFP DELA019 1680x1050 434x270mm 20.1-inch                    | 1        | 4.17%   |
| BenQ GL2750H BNQ78AD 1920x1080 598x336mm 27.0-inch                    | 1        | 4.17%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch          | 1        | 4.17%   |
| Ancor Communications VW246 ACI24F2 1920x1080 531x299mm 24.0-inch      | 1        | 4.17%   |
| Ancor Communications VE228 ACI22FA 1920x1080 480x270mm 21.7-inch      | 1        | 4.17%   |
| Ancor Communications ASUS MX299 ACI2931 2560x1080 673x284mm 28.8-inch | 1        | 4.17%   |
| Acer V203HV ACR01D3 1600x900 443x249mm 20.0-inch                      | 1        | 4.17%   |
| Acer P223W ACR000E 1680x1050 474x296mm 22.0-inch                      | 1        | 4.17%   |
| Acer LCD Monitor S240HL 1920x1080                                     | 1        | 4.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 12       | 60%     |
| 1600x900 (HD+)     | 3        | 15%     |
| 1680x1050 (WSXGA+) | 2        | 10%     |
| 2560x1440 (QHD)    | 1        | 5%      |
| 2560x1080          | 1        | 5%      |
| 1280x1024 (SXGA)   | 1        | 5%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 5        | 22.73%  |
| 23      | 3        | 13.64%  |
| 21      | 3        | 13.64%  |
| 20      | 3        | 13.64%  |
| Unknown | 2        | 9.09%   |
| 72      | 1        | 4.55%   |
| 32      | 1        | 4.55%   |
| 28      | 1        | 4.55%   |
| 27      | 1        | 4.55%   |
| 22      | 1        | 4.55%   |
| 19      | 1        | 4.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 9        | 42.86%  |
| 401-500     | 6        | 28.57%  |
| Unknown     | 2        | 9.52%   |
| 701-800     | 1        | 4.76%   |
| 601-700     | 1        | 4.76%   |
| 351-400     | 1        | 4.76%   |
| 1501-2000   | 1        | 4.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 14       | 70%     |
| 16/10   | 2        | 10%     |
| Unknown | 2        | 10%     |
| 5/4     | 1        | 5%      |
| 21/9    | 1        | 5%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 10       | 47.62%  |
| 151-200        | 4        | 19.05%  |
| 251-300        | 2        | 9.52%   |
| Unknown        | 2        | 9.52%   |
| More than 1000 | 1        | 4.76%   |
| 351-500        | 1        | 4.76%   |
| 301-350        | 1        | 4.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 16       | 76.19%  |
| 101-120 | 2        | 9.52%   |
| Unknown | 2        | 9.52%   |
| 1-50    | 1        | 4.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 19       | 82.61%  |
| 3     | 2        | 8.7%    |
| 2     | 1        | 4.35%   |
| 0     | 1        | 4.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 12       | 36.36%  |
| Realtek Semiconductor | 11       | 33.33%  |
| Qualcomm Atheros      | 3        | 9.09%   |
| Ralink Technology     | 2        | 6.06%   |
| Broadcom              | 2        | 6.06%   |
| Samsung Electronics   | 1        | 3.03%   |
| Mercucys              | 1        | 3.03%   |
| Belkin Components     | 1        | 3.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 9        | 20.93%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 5        | 11.63%  |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 4.65%   |
| Intel Ethernet Connection (7) I219-V                                                          | 2        | 4.65%   |
| Intel 82574L Gigabit Network Connection                                                       | 2        | 4.65%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 1        | 2.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 2.33%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 2.33%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 2.33%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1        | 2.33%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 2.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1        | 2.33%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 2.33%   |
| Realtek 802.11ac NIC                                                                          | 1        | 2.33%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 1        | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 2.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1        | 2.33%   |
| Mercucys MW300UM RTL8192EU wifi                                                               | 1        | 2.33%   |
| Intel Wi-Fi 6 AX200                                                                           | 1        | 2.33%   |
| Intel I210 Gigabit Fiber Network Connection                                                   | 1        | 2.33%   |
| Intel Ethernet Connection (17) I219-V                                                         | 1        | 2.33%   |
| Intel Ethernet Connection (14) I219-V                                                         | 1        | 2.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 2.33%   |
| Intel 82567V-2 Gigabit Network Connection                                                     | 1        | 2.33%   |
| Intel 82566DC-2 Gigabit Network Connection                                                    | 1        | 2.33%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                                             | 1        | 2.33%   |
| Broadcom BCM4321 802.11a/b/g/n                                                                | 1        | 2.33%   |
| Belkin Components F9L1101v2 802.11abgn Wireless Adapter [Realtek RTL8192DU]                   | 1        | 2.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 46.67%  |
| Ralink Technology     | 2        | 13.33%  |
| Intel                 | 2        | 13.33%  |
| Qualcomm Atheros      | 1        | 6.67%   |
| Mercucys              | 1        | 6.67%   |
| Broadcom              | 1        | 6.67%   |
| Belkin Components     | 1        | 6.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 12.5%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 6.25%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 6.25%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 6.25%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1        | 6.25%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 6.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1        | 6.25%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 6.25%   |
| Realtek 802.11ac NIC                                                                          | 1        | 6.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 6.25%   |
| Mercucys MW300UM RTL8192EU wifi                                                               | 1        | 6.25%   |
| Intel Wi-Fi 6 AX200                                                                           | 1        | 6.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 6.25%   |
| Broadcom BCM4321 802.11a/b/g/n                                                                | 1        | 6.25%   |
| Belkin Components F9L1101v2 802.11abgn Wireless Adapter [Realtek RTL8192DU]                   | 1        | 6.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 11       | 45.83%  |
| Realtek Semiconductor | 9        | 37.5%   |
| Qualcomm Atheros      | 2        | 8.33%   |
| Samsung Electronics   | 1        | 4.17%   |
| Broadcom              | 1        | 4.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9        | 33.33%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 18.52%  |
| Intel Ethernet Connection (7) I219-V                              | 2        | 7.41%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 7.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 3.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 3.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 3.7%    |
| Intel I210 Gigabit Fiber Network Connection                       | 1        | 3.7%    |
| Intel Ethernet Connection (17) I219-V                             | 1        | 3.7%    |
| Intel Ethernet Connection (14) I219-V                             | 1        | 3.7%    |
| Intel 82567V-2 Gigabit Network Connection                         | 1        | 3.7%    |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 3.7%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 3.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 23       | 65.71%  |
| WiFi     | 12       | 34.29%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 18       | 72%     |
| WiFi     | 7        | 28%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 15       | 65.22%  |
| 2     | 8        | 34.78%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 20       | 83.33%  |
| Yes  | 4        | 16.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 2        | 33.33%  |
| Cambridge Silicon Radio | 2        | 33.33%  |
| Realtek Semiconductor   | 1        | 16.67%  |
| Dell                    | 1        | 16.67%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 33.33%  |
| Realtek Bluetooth Radio                             | 1        | 16.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 16.67%  |
| Intel AX200 Bluetooth                               | 1        | 16.67%  |
| Dell BT Mini-Receiver                               | 1        | 16.67%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 17       | 43.59%  |
| Nvidia              | 14       | 35.9%   |
| AMD                 | 6        | 15.38%  |
| C-Media Electronics | 2        | 5.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 9.09%   |
| Nvidia High Definition Audio Controller                                    | 3        | 6.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 6.82%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 6.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3        | 6.82%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3        | 6.82%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 4.55%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 4.55%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 4.55%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 4.55%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 2.27%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 2.27%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 2.27%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 2.27%   |
| Nvidia GF116 High Definition Audio Controller                              | 1        | 2.27%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 2.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 2.27%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 2.27%   |
| Intel Audio device                                                         | 1        | 2.27%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 2.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 2.27%   |
| C-Media Electronics REIYIN Audio                                           | 1        | 2.27%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                        | 1        | 2.27%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 2.27%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 2.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 2.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 2        | 20%     |
| Micron Technology   | 2        | 20%     |
| Unknown             | 1        | 10%     |
| Nanya Technology    | 1        | 10%     |
| G.Skill             | 1        | 10%     |
| Crucial             | 1        | 10%     |
| Corsair             | 1        | 10%     |
| A-DATA Technology   | 1        | 10%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM 1333MT/s                  | 1        | 10%     |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s | 1        | 10%     |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s  | 1        | 10%     |
| Nanya RAM NT1GT64U8HB0BY-3C 1GB DIMM DDR2 667MT/s     | 1        | 10%     |
| Micron RAM 18JSF1G72PZ-1G9E1 8GB DIMM DDR3 1866MT/s   | 1        | 10%     |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s  | 1        | 10%     |
| G.Skill RAM F4-3000C16-16GVRB 16GB DIMM DDR4 3200MT/s | 1        | 10%     |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s | 1        | 10%     |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s | 1        | 10%     |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3400MT/s           | 1        | 10%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 4        | 44.44%  |
| DDR4    | 3        | 33.33%  |
| SDRAM   | 1        | 11.11%  |
| Unknown | 1        | 11.11%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 8        | 88.89%  |
| SODIMM | 1        | 11.11%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 2        | 22.22%  |
| 8192  | 2        | 22.22%  |
| 4096  | 2        | 22.22%  |
| 32768 | 1        | 11.11%  |
| 2048  | 1        | 11.11%  |
| 1024  | 1        | 11.11%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 3        | 33.33%  |
| 3400  | 1        | 11.11%  |
| 3200  | 1        | 11.11%  |
| 2667  | 1        | 11.11%  |
| 1866  | 1        | 11.11%  |
| 1333  | 1        | 11.11%  |
| 667   | 1        | 11.11%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Konica Minolta     | 1        | 33.33%  |
| Hewlett-Packard    | 1        | 33.33%  |
| Brother Industries | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                 | Desktops | Percent |
|-----------------------|----------|---------|
| Konica Minolta 185    | 1        | 33.33%  |
| HP OfficeJet Pro 8730 | 1        | 33.33%  |
| Brother MFC-L2685DW   | 1        | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 110 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 2        | 33.33%  |
| OmniVision Technologies | 1        | 16.67%  |
| MacroSilicon            | 1        | 16.67%  |
| Creative Technology     | 1        | 16.67%  |
| ARC International       | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| OmniVision Integrated Webcam for Dell XPS 2010 | 1        | 16.67%  |
| MacroSilicon MiraBox Capture                   | 1        | 16.67%  |
| Logitech Webcam C925e                          | 1        | 16.67%  |
| Logitech Webcam C210                           | 1        | 16.67%  |
| Creative Live! Cam Sync HD [VF0770]            | 1        | 16.67%  |
| ARC International Camera                       | 1        | 16.67%  |

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
| 0     | 16       | 66.67%  |
| 1     | 7        | 29.17%  |
| 2     | 1        | 4.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 5        | 55.56%  |
| Graphics card         | 2        | 22.22%  |
| Multimedia controller | 1        | 11.11%  |
| Camera                | 1        | 11.11%  |

