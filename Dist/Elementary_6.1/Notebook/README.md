Elementary 6.1 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Elementary 6.1.

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
| HP            | EliteBook 8460p             | [f215102713](https://linux-hardware.org/?probe=f215102713) | Dec 31, 2021 |
| Notebook      | P65xHP                      | [37db5af302](https://linux-hardware.org/?probe=37db5af302) | Dec 31, 2021 |
| HP            | EliteBook 8460p             | [e060f00ff8](https://linux-hardware.org/?probe=e060f00ff8) | Dec 31, 2021 |
| Notebook      | P65xHP                      | [fc81fedcf3](https://linux-hardware.org/?probe=fc81fedcf3) | Dec 31, 2021 |
| Teclast       | F7                          | [44bba02dee](https://linux-hardware.org/?probe=44bba02dee) | Dec 31, 2021 |
| Wortmann      | 1220729_1470271             | [018071ac3e](https://linux-hardware.org/?probe=018071ac3e) | Dec 30, 2021 |
| Acer          | Aspire 7750G                | [3a24dba335](https://linux-hardware.org/?probe=3a24dba335) | Dec 28, 2021 |
| Acer          | Aspire 7750G                | [516cb4e250](https://linux-hardware.org/?probe=516cb4e250) | Dec 28, 2021 |
| ASUSTek       | X555UB                      | [e0844450ac](https://linux-hardware.org/?probe=e0844450ac) | Dec 28, 2021 |
| Dell          | Latitude 3580               | [f243f4c09e](https://linux-hardware.org/?probe=f243f4c09e) | Dec 27, 2021 |
| Lenovo        | ThinkPad T430 23501M2       | [2645817d64](https://linux-hardware.org/?probe=2645817d64) | Dec 26, 2021 |
| HP            | EliteBook 850 G2            | [a71c970cbf](https://linux-hardware.org/?probe=a71c970cbf) | Dec 25, 2021 |
| Apple         | MacBookAir7,2               | [99bea5df6c](https://linux-hardware.org/?probe=99bea5df6c) | Dec 25, 2021 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [80c8feb8bf](https://linux-hardware.org/?probe=80c8feb8bf) | Dec 25, 2021 |
| Dell          | Inspiron N5050              | [211b723554](https://linux-hardware.org/?probe=211b723554) | Dec 24, 2021 |
| LG Electro... | A410-G.BC51P1               | [b231405a63](https://linux-hardware.org/?probe=b231405a63) | Dec 24, 2021 |
| Acer          | TravelMate 5760             | [71526c7767](https://linux-hardware.org/?probe=71526c7767) | Dec 23, 2021 |
| Lenovo        | Flex 2-14D 20376            | [d950a63316](https://linux-hardware.org/?probe=d950a63316) | Dec 23, 2021 |
| Dell          | Inspiron 3542               | [277f97ef07](https://linux-hardware.org/?probe=277f97ef07) | Dec 23, 2021 |
| Dell          | XPS 13 9343                 | [dfbdb618f1](https://linux-hardware.org/?probe=dfbdb618f1) | Dec 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [f74c2da103](https://linux-hardware.org/?probe=f74c2da103) | Dec 22, 2021 |
| Dell          | Precision M3800             | [ed44d9ac8c](https://linux-hardware.org/?probe=ed44d9ac8c) | Dec 21, 2021 |
| Apple         | MacBookAir6,1               | [b2e3490378](https://linux-hardware.org/?probe=b2e3490378) | Dec 21, 2021 |
| Dell          | Precision M6500             | [931f365c60](https://linux-hardware.org/?probe=931f365c60) | Dec 20, 2021 |
| Dell          | Inspiron 5555               | [09d45f017d](https://linux-hardware.org/?probe=09d45f017d) | Dec 18, 2021 |
| Lenovo        | V14-ADA 82C6                | [a45f76da28](https://linux-hardware.org/?probe=a45f76da28) | Dec 17, 2021 |
| ASUSTek       | UX410UAK                    | [39dcbe0f57](https://linux-hardware.org/?probe=39dcbe0f57) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | [2d2ed2143e](https://linux-hardware.org/?probe=2d2ed2143e) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | [2390550c49](https://linux-hardware.org/?probe=2390550c49) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | [661e7dae0c](https://linux-hardware.org/?probe=661e7dae0c) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | [b682cee818](https://linux-hardware.org/?probe=b682cee818) | Dec 15, 2021 |
| Apple         | MacBook5,2                  | [5dcbdab7ca](https://linux-hardware.org/?probe=5dcbdab7ca) | Dec 15, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.11.0-43-generic | 22        | 84.62%  |
| 5.11.0-41-generic | 3         | 11.54%  |
| 5.8.0-50-generic  | 1         | 3.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 25        | 96.15%  |
| 5.8.0   | 1         | 3.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 25        | 96.15%  |
| 5.8     | 1         | 3.85%   |

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


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Pantheon | 26        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 26        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 21        | 80.77%  |
| LightDM | 5         | 19.23%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 14        | 53.85%  |
| pt_BR | 3         | 11.54%  |
| de_DE | 3         | 11.54%  |
| pl_PL | 2         | 7.69%   |
| en_GB | 2         | 7.69%   |
| fr_FR | 1         | 3.85%   |
| es_ES | 1         | 3.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 18        | 69.23%  |
| BIOS | 8         | 30.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 25        | 96.15%  |
| Overlay | 1         | 3.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 22        | 84.62%  |
| GPT     | 4         | 15.38%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 92.31%  |
| Yes       | 2         | 7.69%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 92.31%  |
| Yes       | 2         | 7.69%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Dell             | 7         | 26.92%  |
| Apple            | 4         | 15.38%  |
| Lenovo           | 3         | 11.54%  |
| ASUSTek Computer | 3         | 11.54%  |
| Hewlett-Packard  | 2         | 7.69%   |
| Acer             | 2         | 7.69%   |
| Wortmann AG      | 1         | 3.85%   |
| Teclast          | 1         | 3.85%   |
| Notebook         | 1         | 3.85%   |
| Monster          | 1         | 3.85%   |
| LG Electronics   | 1         | 3.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Wortmann AG 1220729_1470271            | 1         | 3.85%   |
| Teclast F7                             | 1         | 3.85%   |
| Notebook P65xHP                        | 1         | 3.85%   |
| Monster MARKUT M7 V1.x                 | 1         | 3.85%   |
| LG A410-G.BC51P1                       | 1         | 3.85%   |
| Lenovo ThinkPad T430 23501M2           | 1         | 3.85%   |
| Lenovo IdeaPad 320-14AST 80XU          | 1         | 3.85%   |
| Lenovo Flex 2-14D 20376                | 1         | 3.85%   |
| HP EliteBook 850 G2                    | 1         | 3.85%   |
| HP EliteBook 8460p                     | 1         | 3.85%   |
| Dell XPS 13 9343                       | 1         | 3.85%   |
| Dell Precision M6500                   | 1         | 3.85%   |
| Dell Precision M3800                   | 1         | 3.85%   |
| Dell Latitude 3580                     | 1         | 3.85%   |
| Dell Inspiron N5050                    | 1         | 3.85%   |
| Dell Inspiron 5555                     | 1         | 3.85%   |
| Dell Inspiron 3542                     | 1         | 3.85%   |
| ASUS X555UB                            | 1         | 3.85%   |
| ASUS VivoBook_ASUSLaptop X512FA_A512FA | 1         | 3.85%   |
| ASUS UX410UAK                          | 1         | 3.85%   |
| Apple MacBookAir7,2                    | 1         | 3.85%   |
| Apple MacBookAir6,1                    | 1         | 3.85%   |
| Apple MacBook5,2                       | 1         | 3.85%   |
| Apple MacBook4,1                       | 1         | 3.85%   |
| Acer TravelMate 5760                   | 1         | 3.85%   |
| Acer Aspire 7750G                      | 1         | 3.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell Inspiron       | 3         | 11.54%  |
| HP EliteBook        | 2         | 7.69%   |
| Dell Precision      | 2         | 7.69%   |
| Wortmann AG 1220729 | 1         | 3.85%   |
| Teclast F7          | 1         | 3.85%   |
| Notebook P65xHP     | 1         | 3.85%   |
| Monster MARKUT      | 1         | 3.85%   |
| LG A410-G.BC51P1    | 1         | 3.85%   |
| Lenovo ThinkPad     | 1         | 3.85%   |
| Lenovo IdeaPad      | 1         | 3.85%   |
| Lenovo Flex         | 1         | 3.85%   |
| Dell XPS            | 1         | 3.85%   |
| Dell Latitude       | 1         | 3.85%   |
| ASUS X555UB         | 1         | 3.85%   |
| ASUS VivoBook       | 1         | 3.85%   |
| ASUS UX410UAK       | 1         | 3.85%   |
| Apple MacBookAir7   | 1         | 3.85%   |
| Apple MacBookAir6   | 1         | 3.85%   |
| Apple MacBook5      | 1         | 3.85%   |
| Apple MacBook4      | 1         | 3.85%   |
| Acer TravelMate     | 1         | 3.85%   |
| Acer Aspire         | 1         | 3.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 5         | 19.23%  |
| 2011 | 4         | 15.38%  |
| 2020 | 3         | 11.54%  |
| 2018 | 3         | 11.54%  |
| 2016 | 2         | 7.69%   |
| 2015 | 2         | 7.69%   |
| 2021 | 1         | 3.85%   |
| 2017 | 1         | 3.85%   |
| 2014 | 1         | 3.85%   |
| 2013 | 1         | 3.85%   |
| 2012 | 1         | 3.85%   |
| 2009 | 1         | 3.85%   |
| 2008 | 1         | 3.85%   |

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
| Disabled | 26        | 100%    |

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


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 13        | 50%     |
| 3.01-4.0    | 5         | 19.23%  |
| 16.01-24.0  | 3         | 11.54%  |
| 8.01-16.0   | 3         | 11.54%  |
| 64.01-256.0 | 1         | 3.85%   |
| 1.01-2.0    | 1         | 3.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 13        | 50%     |
| 1.01-2.0  | 6         | 23.08%  |
| 3.01-4.0  | 3         | 11.54%  |
| 0.51-1.0  | 2         | 7.69%   |
| 4.01-8.0  | 1         | 3.85%   |
| 8.01-16.0 | 1         | 3.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 16        | 61.54%  |
| 2      | 7         | 26.92%  |
| 3      | 2         | 7.69%   |
| 5      | 1         | 3.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 17        | 65.38%  |
| Yes       | 9         | 34.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 69.23%  |
| No        | 8         | 30.77%  |

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
| Brazil      | 4         | 15.38%  |
| USA         | 3         | 11.54%  |
| Germany     | 3         | 11.54%  |
| Poland      | 2         | 7.69%   |
| India       | 2         | 7.69%   |
| Ukraine     | 1         | 3.85%   |
| Turkey      | 1         | 3.85%   |
| Sweden      | 1         | 3.85%   |
| Romania     | 1         | 3.85%   |
| Portugal    | 1         | 3.85%   |
| Netherlands | 1         | 3.85%   |
| Mexico      | 1         | 3.85%   |
| Italy       | 1         | 3.85%   |
| Indonesia   | 1         | 3.85%   |
| Guyana      | 1         | 3.85%   |
| France      | 1         | 3.85%   |
| Australia   | 1         | 3.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Wroclaw                | 1         | 3.85%   |
| Wriedel                | 1         | 3.85%   |
| Vinnytsia              | 1         | 3.85%   |
| Tecuci                 | 1         | 3.85%   |
| Sydney                 | 1         | 3.85%   |
| Soliera                | 1         | 3.85%   |
| S??o Paulo             | 1         | 3.85%   |
| S??o Bernardo do Campo | 1         | 3.85%   |
| San Antonio            | 1         | 3.85%   |
| Saltsjoe-Boo           | 1         | 3.85%   |
| Porto                  | 1         | 3.85%   |
| Osasco                 | 1         | 3.85%   |
| Montm?�dy              | 1         | 3.85%   |
| Jember                 | 1         | 3.85%   |
| Hudson                 | 1         | 3.85%   |
| Gliwice                | 1         | 3.85%   |
| Georgetown             | 1         | 3.85%   |
| Erkrath                | 1         | 3.85%   |
| Cuernavaca             | 1         | 3.85%   |
| Chalfont               | 1         | 3.85%   |
| Cabo Frio              | 1         | 3.85%   |
| Bengaluru              | 1         | 3.85%   |
| Bad Friedrichshall     | 1         | 3.85%   |
| Antalya                | 1         | 3.85%   |
| Alphen aan den Rijn    | 1         | 3.85%   |
| Ahmedabad              | 1         | 3.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 10     | 16.22%  |
| WDC                 | 5         | 5      | 13.51%  |
| Seagate             | 5         | 5      | 13.51%  |
| Crucial             | 3         | 3      | 8.11%   |
| Kingston            | 2         | 2      | 5.41%   |
| Hitachi             | 2         | 2      | 5.41%   |
| Teclast             | 1         | 1      | 2.7%    |
| Silicon Motion      | 1         | 1      | 2.7%    |
| SanDisk             | 1         | 1      | 2.7%    |
| SABRENT             | 1         | 1      | 2.7%    |
| Micron Technology   | 1         | 1      | 2.7%    |
| LITEON              | 1         | 1      | 2.7%    |
| KIOXIA              | 1         | 1      | 2.7%    |
| KingSpec            | 1         | 1      | 2.7%    |
| HGST                | 1         | 1      | 2.7%    |
| Fujitsu             | 1         | 1      | 2.7%    |
| China               | 1         | 1      | 2.7%    |
| Apple               | 1         | 1      | 2.7%    |
| A-DATA Technology   | 1         | 1      | 2.7%    |
| Unknown             | 1         | 1      | 2.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD5000LPVX-75V0TT0 500GB            | 2         | 5.13%   |
| Seagate ST1000LM035-1RK172 1TB          | 2         | 5.13%   |
| WDC WD7500BPVT-22A1YT0 752GB            | 1         | 2.56%   |
| WDC WD5000BPVT-22HXZT1 500GB            | 1         | 2.56%   |
| WDC WD20SPZX-22UA7T0 2TB                | 1         | 2.56%   |
| Teclast 128GB NS550-2242 SSD            | 1         | 2.56%   |
| Silicon Motion NVMe SSD Drive 120GB     | 1         | 2.56%   |
| Seagate ST9500325AS 500GB               | 1         | 2.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 2.56%   |
| Seagate Expansion Desk 5TB              | 1         | 2.56%   |
| SanDisk SD8SNAT128G1002 128GB SSD       | 1         | 2.56%   |
| Samsung SSD SM841 mSATA 512GB           | 1         | 2.56%   |
| Samsung SSD 950 PRO 512GB               | 1         | 2.56%   |
| Samsung SSD 850 EVO 2TB                 | 1         | 2.56%   |
| Samsung SSD 850 EVO 250GB               | 1         | 2.56%   |
| Samsung SSD 850 EVO 1TB                 | 1         | 2.56%   |
| Samsung PSSD T7 Touch 2TB               | 1         | 2.56%   |
| Samsung Portable SSD T5 500GB           | 1         | 2.56%   |
| Samsung MZMPA064HMDR-00000 64GB SSD     | 1         | 2.56%   |
| SABRENT Disk 500GB                      | 1         | 2.56%   |
| Micron 1100_MTFDDAK256TBN 256GB SSD     | 1         | 2.56%   |
| LITEON L8H-256V2G-11 M.2 2280 256GB SSD | 1         | 2.56%   |
| KIOXIA NVMe SSD Drive 256GB             | 1         | 2.56%   |
| Kingston SA400S37240G 240GB SSD         | 1         | 2.56%   |
| Kingston RBUSNS8180DS3128GJ 128GB SSD   | 1         | 2.56%   |
| KingSpec P4-120 120GB                   | 1         | 2.56%   |
| Hitachi HTS725032A7E630 320GB           | 1         | 2.56%   |
| Hitachi HTS543212L9SA02 120GB           | 1         | 2.56%   |
| HGST HTS545050A7E380 500GB              | 1         | 2.56%   |
| Fujitsu MHY2250BH 250GB                 | 1         | 2.56%   |
| Crucial CT120BX300SSD1 120GB            | 1         | 2.56%   |
| Crucial CT1050MX300SSD4 1050GB          | 1         | 2.56%   |
| Crucial CT1000MX500SSD1 1TB             | 1         | 2.56%   |
| China SSD 240GB                         | 1         | 2.56%   |
| Apple SSD SM0128G 121GB                 | 1         | 2.56%   |
| A-DATA SU650 120GB SSD                  | 1         | 2.56%   |
| Unknown                                 | 1         | 2.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 33.33%  |
| Seagate | 5         | 5      | 33.33%  |
| Hitachi | 2         | 2      | 13.33%  |
| SABRENT | 1         | 1      | 6.67%   |
| HGST    | 1         | 1      | 6.67%   |
| Fujitsu | 1         | 1      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 8      | 30%     |
| Crucial             | 3         | 3      | 15%     |
| Kingston            | 2         | 2      | 10%     |
| Teclast             | 1         | 1      | 5%      |
| SanDisk             | 1         | 1      | 5%      |
| Micron Technology   | 1         | 1      | 5%      |
| LITEON              | 1         | 1      | 5%      |
| KingSpec            | 1         | 1      | 5%      |
| China               | 1         | 1      | 5%      |
| Apple               | 1         | 1      | 5%      |
| A-DATA Technology   | 1         | 1      | 5%      |
| Unknown             | 1         | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 18        | 22     | 50%     |
| HDD  | 15        | 15     | 41.67%  |
| NVMe | 3         | 4      | 8.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 25        | 33     | 80.65%  |
| SAS  | 3         | 4      | 9.68%   |
| NVMe | 3         | 4      | 9.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 20        | 24     | 66.67%  |
| 0.51-1.0   | 7         | 7      | 23.33%  |
| 1.01-2.0   | 2         | 5      | 6.67%   |
| 4.01-10.0  | 1         | 1      | 3.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 12        | 46.15%  |
| 251-500        | 6         | 23.08%  |
| 1001-2000      | 3         | 11.54%  |
| 501-1000       | 3         | 11.54%  |
| More than 3000 | 1         | 3.85%   |
| 51-100         | 1         | 3.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 11        | 42.31%  |
| 21-50     | 6         | 23.08%  |
| 51-100    | 4         | 15.38%  |
| 501-1000  | 3         | 11.54%  |
| 2001-3000 | 1         | 3.85%   |
| 101-250   | 1         | 3.85%   |

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
| Detected | 24        | 33     | 85.71%  |
| Works    | 4         | 8      | 14.29%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 20        | 74.07%  |
| AMD                 | 3         | 11.11%  |
| Samsung Electronics | 2         | 7.41%   |
| Silicon Motion      | 1         | 3.7%    |
| Nvidia              | 1         | 3.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 14.29%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 10.71%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 10.71%  |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 7.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 7.14%   |
| Silicon Motion Non-Volatile memory controller                                  | 1         | 3.57%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 3.57%   |
| Samsung Electronics SATA controller                                            | 1         | 3.57%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 3.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 3.57%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 3.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 3.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 3.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 3.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 3.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 3.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 3.57%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 3.57%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 3.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 23        | 82.14%  |
| RAID | 2         | 7.14%   |
| NVMe | 2         | 7.14%   |
| IDE  | 1         | 3.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 23        | 88.46%  |
| AMD    | 3         | 11.54%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz            | 2         | 7.69%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz           | 1         | 3.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz            | 1         | 3.85%   |
| Intel Core i7-6700K CPU @ 4.00GHz            | 1         | 3.85%   |
| Intel Core i7-5500U CPU @ 2.40GHz            | 1         | 3.85%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz           | 1         | 3.85%   |
| Intel Core i7-2670QM CPU @ 2.20GHz           | 1         | 3.85%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz            | 1         | 3.85%   |
| Intel Core i5-5300U CPU @ 2.30GHz            | 1         | 3.85%   |
| Intel Core i5-5250U CPU @ 1.60GHz            | 1         | 3.85%   |
| Intel Core i5-4260U CPU @ 1.40GHz            | 1         | 3.85%   |
| Intel Core i5-3320M CPU @ 2.60GHz            | 1         | 3.85%   |
| Intel Core i5-2520M CPU @ 2.50GHz            | 1         | 3.85%   |
| Intel Core i5-2450M CPU @ 2.50GHz            | 1         | 3.85%   |
| Intel Core i3-8145U CPU @ 2.10GHz            | 1         | 3.85%   |
| Intel Core i3-4005U CPU @ 1.70GHz            | 1         | 3.85%   |
| Intel Core i3-2330M CPU @ 2.20GHz            | 1         | 3.85%   |
| Intel Core i3-10110U CPU @ 2.10GHz           | 1         | 3.85%   |
| Intel Core i3 CPU M 390 @ 2.67GHz            | 1         | 3.85%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz         | 1         | 3.85%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz         | 1         | 3.85%   |
| Intel Celeron CPU N3450 @ 1.10GHz            | 1         | 3.85%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 3.85%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics  | 1         | 3.85%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics  | 1         | 3.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 8         | 30.77%  |
| Intel Core i7    | 7         | 26.92%  |
| Intel Core i3    | 5         | 19.23%  |
| Intel Core 2 Duo | 2         | 7.69%   |
| Other            | 1         | 3.85%   |
| Intel Celeron    | 1         | 3.85%   |
| AMD A8           | 1         | 3.85%   |
| AMD A6           | 1         | 3.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 18        | 69.23%  |
| 4      | 8         | 30.77%  |

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
| 2      | 20        | 76.92%  |
| 1      | 6         | 23.08%  |

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
| 0x206a7    | 4         | 15.38%  |
| 0x306d4    | 3         | 11.54%  |
| 0x406e3    | 2         | 7.69%   |
| 0x40651    | 2         | 7.69%   |
| 0x906e9    | 1         | 3.85%   |
| 0x806ec    | 1         | 3.85%   |
| 0x806eb    | 1         | 3.85%   |
| 0x806e9    | 1         | 3.85%   |
| 0x506e3    | 1         | 3.85%   |
| 0x506c9    | 1         | 3.85%   |
| 0x306c3    | 1         | 3.85%   |
| 0x306a9    | 1         | 3.85%   |
| 0x106e5    | 1         | 3.85%   |
| 0x1067a    | 1         | 3.85%   |
| 0x10676    | 1         | 3.85%   |
| 0x07030105 | 1         | 3.85%   |
| 0x07030104 | 1         | 3.85%   |
| 0x06006704 | 1         | 3.85%   |
| Unknown    | 1         | 3.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| SandyBridge | 4         | 15.38%  |
| KabyLake    | 4         | 15.38%  |
| Skylake     | 3         | 11.54%  |
| Haswell     | 3         | 11.54%  |
| Broadwell   | 3         | 11.54%  |
| Puma        | 2         | 7.69%   |
| Penryn      | 2         | 7.69%   |
| Westmere    | 1         | 3.85%   |
| Nehalem     | 1         | 3.85%   |
| IvyBridge   | 1         | 3.85%   |
| Goldmont    | 1         | 3.85%   |
| Excavator   | 1         | 3.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 20        | 68.97%  |
| Nvidia | 5         | 17.24%  |
| AMD    | 4         | 13.79%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 13.33%  |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 6.67%   |
| Intel HD Graphics 5500                                                    | 2         | 6.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 6.67%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 2         | 6.67%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 1         | 3.33%   |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 3.33%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 3.33%   |
| Nvidia GK107GLM [Quadro K1100M]                                           | 1         | 3.33%   |
| Nvidia C79 [GeForce 9400M G]                                              | 1         | 3.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 3.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 1         | 3.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 1         | 3.33%   |
| Intel HD Graphics 630                                                     | 1         | 3.33%   |
| Intel HD Graphics 620                                                     | 1         | 3.33%   |
| Intel HD Graphics 6000                                                    | 1         | 3.33%   |
| Intel HD Graphics 500                                                     | 1         | 3.33%   |
| Intel Core Processor Integrated Graphics Controller                       | 1         | 3.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 3.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1         | 3.33%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 1         | 3.33%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1         | 3.33%   |
| AMD Broadway XT [Mobility Radeon HD 5870]                                 | 1         | 3.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 17        | 65.38%  |
| 1 x AMD        | 4         | 15.38%  |
| Intel + Nvidia | 3         | 11.54%  |
| 1 x Nvidia     | 2         | 7.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 24        | 92.31%  |
| Proprietary | 2         | 7.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 65.38%  |
| 0.51-1.0   | 4         | 15.38%  |
| 1.01-2.0   | 3         | 11.54%  |
| 5.01-6.0   | 1         | 3.85%   |
| 0.01-0.5   | 1         | 3.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 5         | 17.24%  |
| AU Optronics        | 5         | 17.24%  |
| Chimei Innolux      | 4         | 13.79%  |
| Apple               | 4         | 13.79%  |
| Sharp               | 3         | 10.34%  |
| Samsung Electronics | 3         | 10.34%  |
| BOE                 | 3         | 10.34%  |
| Hewlett-Packard     | 1         | 3.45%   |
| Goldstar            | 1         | 3.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Sharp PN-K321 SHP21DD 3840x2160                                      | 1         | 3.45%   |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch              | 1         | 3.45%   |
| Sharp LCD Monitor SHP1421 3200x1800 294x165mm 13.3-inch              | 1         | 3.45%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch    | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SDC280F 1366x768 344x193mm 15.5-inch | 1         | 3.45%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch         | 1         | 3.45%   |
| LG Display LCD Monitor LGD046C 1920x1080 380x210mm 17.1-inch         | 1         | 3.45%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch          | 1         | 3.45%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 1         | 3.45%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 1         | 3.45%   |
| Hewlett-Packard V196bz HWP323E 1366x768 410x230mm 18.5-inch          | 1         | 3.45%   |
| Goldstar E2442 GSM58C6 1920x1080 531x299mm 24.0-inch                 | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch      | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch     | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch      | 1         | 3.45%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 1         | 3.45%   |
| BOE LCD Monitor BOE079A 1920x1080 309x173mm 13.9-inch                | 1         | 3.45%   |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                 | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch        | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO35ED 1920x1080 344x193mm 15.5-inch       | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch        | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch        | 1         | 3.45%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 1         | 3.45%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 1         | 3.45%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 1         | 3.45%   |
| Apple Color LCD APP9C5B 1280x800 290x180mm 13.4-inch                 | 1         | 3.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 12        | 42.86%  |
| 1920x1080 (FHD)  | 7         | 25%     |
| 3840x2160 (4K)   | 3         | 10.71%  |
| 1600x900 (HD+)   | 2         | 7.14%   |
| 1280x800 (WXGA)  | 2         | 7.14%   |
| 3200x1800 (QHD+) | 1         | 3.57%   |
| 1440x900 (WXGA+) | 1         | 3.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 11        | 37.93%  |
| 13      | 7         | 24.14%  |
| 14      | 4         | 13.79%  |
| 17      | 2         | 6.9%    |
| 31      | 1         | 3.45%   |
| 24      | 1         | 3.45%   |
| 18      | 1         | 3.45%   |
| 11      | 1         | 3.45%   |
| Unknown | 1         | 3.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 18        | 62.07%  |
| 201-300     | 5         | 17.24%  |
| 351-400     | 2         | 6.9%    |
| 601-700     | 1         | 3.45%   |
| 501-600     | 1         | 3.45%   |
| 401-500     | 1         | 3.45%   |
| Unknown     | 1         | 3.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 22        | 88%     |
| 16/10 | 3         | 12%     |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 11        | 37.93%  |
| 81-90          | 9         | 31.03%  |
| 71-80          | 2         | 6.9%    |
| 121-130        | 2         | 6.9%    |
| 51-60          | 1         | 3.45%   |
| 351-500        | 1         | 3.45%   |
| 201-250        | 1         | 3.45%   |
| 141-150        | 1         | 3.45%   |
| Unknown        | 1         | 3.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 13        | 44.83%  |
| 121-160       | 11        | 37.93%  |
| More than 240 | 2         | 6.9%    |
| 51-100        | 2         | 6.9%    |
| Unknown       | 1         | 3.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 22        | 84.62%  |
| 2     | 4         | 15.38%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 12        | 29.27%  |
| Realtek Semiconductor    | 9         | 21.95%  |
| Qualcomm Atheros         | 9         | 21.95%  |
| Broadcom                 | 5         | 12.2%   |
| Broadcom Limited         | 2         | 4.88%   |
| TP-Link                  | 1         | 2.44%   |
| Ralink                   | 1         | 2.44%   |
| Nvidia                   | 1         | 2.44%   |
| Marvell Technology Group | 1         | 2.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 13.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 6.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 6.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 4.44%   |
| Intel Wireless 8265 / 8275                                        | 2         | 4.44%   |
| Intel Wireless 8260                                               | 2         | 4.44%   |
| Intel Wireless 3165                                               | 2         | 4.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 4.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4.44%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 2         | 4.44%   |
| Broadcom BCM43227 802.11b/g/n                                     | 2         | 4.44%   |
| TP-Link 802.11n NIC                                               | 1         | 2.22%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 2.22%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 2.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 2.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 2.22%   |
| Nvidia MCP79 Ethernet                                             | 1         | 2.22%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 2.22%   |
| Intel Wireless 7265                                               | 1         | 2.22%   |
| Intel Wireless 7260                                               | 1         | 2.22%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 2.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 2.22%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 1         | 2.22%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 1         | 2.22%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 1         | 2.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 2.22%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 12        | 44.44%  |
| Qualcomm Atheros | 6         | 22.22%  |
| Broadcom         | 5         | 18.52%  |
| Broadcom Limited | 2         | 7.41%   |
| TP-Link          | 1         | 3.7%    |
| Ralink           | 1         | 3.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 11.11%  |
| Intel Wireless 8265 / 8275                                     | 2         | 7.41%   |
| Intel Wireless 8260                                            | 2         | 7.41%   |
| Intel Wireless 3165                                            | 2         | 7.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 7.41%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 2         | 7.41%   |
| Broadcom BCM43227 802.11b/g/n                                  | 2         | 7.41%   |
| TP-Link 802.11n NIC                                            | 1         | 3.7%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 3.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 3.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 3.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 3.7%    |
| Intel Wireless 7265                                            | 1         | 3.7%    |
| Intel Wireless 7260                                            | 1         | 3.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 3.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 3.7%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1         | 3.7%    |
| Broadcom BCM4321 802.11a/b/g/n                                 | 1         | 3.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 3.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 9         | 50%     |
| Qualcomm Atheros         | 3         | 16.67%  |
| Intel                    | 3         | 16.67%  |
| Nvidia                   | 1         | 5.56%   |
| Marvell Technology Group | 1         | 5.56%   |
| Broadcom                 | 1         | 5.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 33.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 16.67%  |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 11.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 11.11%  |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 5.56%   |
| Nvidia MCP79 Ethernet                                             | 1         | 5.56%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 5.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 5.56%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 1         | 5.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 59.09%  |
| Ethernet | 18        | 40.91%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 61.9%   |
| Ethernet | 16        | 38.1%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 18        | 69.23%  |
| 1     | 8         | 30.77%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| Yes  | 14        | 53.85%  |
| No   | 12        | 46.15%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 10        | 41.67%  |
| Qualcomm Atheros Communications | 5         | 20.83%  |
| Apple                           | 4         | 16.67%  |
| IMC Networks                    | 1         | 4.17%   |
| Hewlett-Packard                 | 1         | 4.17%   |
| Foxconn / Hon Hai               | 1         | 4.17%   |
| Cambridge Silicon Radio         | 1         | 4.17%   |
| Broadcom                        | 1         | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 6         | 25%     |
| Intel Bluetooth wireless interface                  | 4         | 16.67%  |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 8.33%   |
| Apple Bluetooth USB Host Controller                 | 2         | 8.33%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 4.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 4.17%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 4.17%   |
| IMC Networks Bluetooth Device                       | 1         | 4.17%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 4.17%   |
| Foxconn / Hon Hai Acer Module                       | 1         | 4.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.17%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 4.17%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 4.17%   |
| Apple Bluetooth HCI                                 | 1         | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel             | 22        | 73.33%  |
| AMD               | 4         | 13.33%  |
| Nvidia            | 3         | 10%     |
| Texas Instruments | 1         | 3.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 10.26%  |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 7.69%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 7.69%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 7.69%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 5.13%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 5.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 5.13%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 5.13%   |
| AMD FCH Azalia Controller                                                  | 2         | 5.13%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 2.56%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 2.56%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 2.56%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 2.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 2.56%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 2.56%   |
| Intel CM238 HD Audio Controller                                            | 1         | 2.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 2.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 2.56%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 2.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 2.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 2.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 2.56%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 1         | 2.56%   |
| AMD High Definition Audio Controller                                       | 1         | 2.56%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 2.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 50%     |
| SK Hynix            | 1         | 25%     |
| G.Skill             | 1         | 25%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT851S6AMR6R-PB 4096MB Chip DDR3 1600MT/s   | 1         | 25%     |
| Samsung RAM Module 2048MB SODIMM DDR3 1600MT/s            | 1         | 25%     |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s     | 1         | 25%     |
| G.Skill RAM F4-2666C18-16GRS 16384MB SODIMM DDR4 2667MT/s | 1         | 25%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| DDR4 | 2         | 50%     |
| DDR3 | 2         | 50%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 3         | 75%     |
| Chip   | 1         | 25%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 16384 | 1         | 25%     |
| 8192  | 1         | 25%     |
| 4096  | 1         | 25%     |
| 2048  | 1         | 25%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 2         | 50%     |
| 2667  | 1         | 25%     |
| 2133  | 1         | 25%     |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Notebooks | Percent |
|---------------------------|-----------|---------|
| Canon PIXMA MG2500 Series | 1         | 100%    |

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
| Realtek Semiconductor                  | 6         | 27.27%  |
| Chicony Electronics                    | 4         | 18.18%  |
| Alcor Micro                            | 3         | 13.64%  |
| IMC Networks                           | 2         | 9.09%   |
| Acer                                   | 2         | 9.09%   |
| Suyin                                  | 1         | 4.55%   |
| Ricoh                                  | 1         | 4.55%   |
| Microdia                               | 1         | 4.55%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 4.55%   |
| Apple                                  | 1         | 4.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                             | 2         | 9.09%   |
| Alcor Micro Acer Integrated Webcam                                       | 2         | 9.09%   |
| Suyin Integrated_Webcam_HD                                               | 1         | 4.55%   |
| Ricoh Dell Laptop Integrated Webcam                                      | 1         | 4.55%   |
| Realtek USB2.0 VGA UVC WebCam                                            | 1         | 4.55%   |
| Realtek USB2.0 HD UVC WebCam                                             | 1         | 4.55%   |
| Realtek LG Webcam                                                        | 1         | 4.55%   |
| Realtek Integrated Webcam                                                | 1         | 4.55%   |
| Microdia Integrated_Webcam_HD                                            | 1         | 4.55%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 1         | 4.55%   |
| IMC Networks EasyCamera                                                  | 1         | 4.55%   |
| Chicony USB2.0 Camera                                                    | 1         | 4.55%   |
| Chicony USB 2.0 Camera                                                   | 1         | 4.55%   |
| Chicony thinkpad t430s camera                                            | 1         | 4.55%   |
| Chicony Integrated HP HD Webcam                                          | 1         | 4.55%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 4.55%   |
| Apple Built-in iSight [Micron]                                           | 1         | 4.55%   |
| Alcor Micro USB 2.0 PC Camera                                            | 1         | 4.55%   |
| Acer Lenovo EasyCamera                                                   | 1         | 4.55%   |
| Acer BisonCam, NB Pro                                                    | 1         | 4.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| LighTuning Technology | 2         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| LighTuning ES603 Swipe Fingerprint Sensor | 2         | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Lenovo   | 1         | 50%     |
| Broadcom | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader            | 1         | 50%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 20        | 76.92%  |
| 1     | 6         | 23.08%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Multimedia controller | 2         | 33.33%  |
| Fingerprint reader    | 2         | 33.33%  |
| Chipcard              | 2         | 33.33%  |

