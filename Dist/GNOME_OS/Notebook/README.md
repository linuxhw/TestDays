GNOME OS - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for GNOME OS.

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

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo  | ThinkPad Edge E531 68851... | [54269ad944](https://linux-hardware.org/?probe=54269ad944) | Feb 18, 2022 |
| Gateway | NE71B                       | [ac3dc96ccf](https://linux-hardware.org/?probe=ac3dc96ccf) | Feb 02, 2022 |
| HP      | Laptop 14-dk1xxx            | [c604eec754](https://linux-hardware.org/?probe=c604eec754) | Jan 27, 2022 |
| Chuwi   | HeroBook                    | [67990dbe7f](https://linux-hardware.org/?probe=67990dbe7f) | Jan 19, 2022 |
| Lenovo  | Yoga Slim 7 14ARE05 82A2    | [594815bb9d](https://linux-hardware.org/?probe=594815bb9d) | Oct 17, 2021 |
| ASUSTek | X555LD                      | [2560d8b5a0](https://linux-hardware.org/?probe=2560d8b5a0) | Sep 27, 2021 |
| Lenovo  | IdeaPad S340-14API 81NB     | [c248e4551a](https://linux-hardware.org/?probe=c248e4551a) | Sep 25, 2021 |
| HP      | Pavilion Notebook           | [835f183d57](https://linux-hardware.org/?probe=835f183d57) | Sep 17, 2021 |
| Lenovo  | IdeaPad S145-15IWL 81S9     | [35c20c8cde](https://linux-hardware.org/?probe=35c20c8cde) | Aug 30, 2021 |
| HP      | Pavilion Gaming Laptop 1... | [5a54384297](https://linux-hardware.org/?probe=5a54384297) | Aug 11, 2021 |
| HP      | ProBook 430 G3              | [c3acaeb030](https://linux-hardware.org/?probe=c3acaeb030) | Apr 26, 2021 |
| HP      | ProBook 430 G3              | [de3298645e](https://linux-hardware.org/?probe=de3298645e) | Apr 26, 2021 |
| Toshiba | Satellite C55-A-1F5         | [d7b4bf2642](https://linux-hardware.org/?probe=d7b4bf2642) | Apr 15, 2021 |
| Toshiba | Satellite C55-A-1F5         | [aa32e3693a](https://linux-hardware.org/?probe=aa32e3693a) | Apr 14, 2021 |
| HP      | Pavilion 17                 | [220bf859f8](https://linux-hardware.org/?probe=220bf859f8) | Mar 28, 2021 |
| HP      | Pavilion 17                 | [a5a6941b23](https://linux-hardware.org/?probe=a5a6941b23) | Mar 28, 2021 |
| Dell    | Latitude 7490               | [ce86510d2b](https://linux-hardware.org/?probe=ce86510d2b) | Mar 28, 2021 |
| Dell    | Inspiron 3542               | [517406f8b6](https://linux-hardware.org/?probe=517406f8b6) | Mar 21, 2021 |
| Unknown | Unknown                     | [1c5ed732c5](https://linux-hardware.org/?probe=1c5ed732c5) | Mar 01, 2021 |
| Dell    | Precision M6800             | [95fa029c09](https://linux-hardware.org/?probe=95fa029c09) | Jan 14, 2021 |
| Dell    | Inspiron 5566               | [a3fd17119a](https://linux-hardware.org/?probe=a3fd17119a) | Nov 03, 2020 |
| HP      | Pavilion 17                 | [edc8ed595b](https://linux-hardware.org/?probe=edc8ed595b) | Oct 12, 2020 |
| ASUSTek | E202SA                      | [a226259559](https://linux-hardware.org/?probe=a226259559) | Sep 24, 2020 |
| Acer    | ChiefRiver Platform         | [23e2162b8e](https://linux-hardware.org/?probe=23e2162b8e) | Sep 20, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.7.14  | 5         | 25%     |
| 5.14.18 | 4         | 20%     |
| 5.11.2  | 3         | 15%     |
| 5.13.9  | 2         | 10%     |
| 5.13.8  | 2         | 10%     |
| 5.11.10 | 2         | 10%     |
| 5.14.4  | 1         | 5%      |
| 5.14.11 | 1         | 5%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.7.14  | 5         | 25%     |
| 5.14.18 | 4         | 20%     |
| 5.11.2  | 3         | 15%     |
| 5.13.9  | 2         | 10%     |
| 5.13.8  | 2         | 10%     |
| 5.11.10 | 2         | 10%     |
| 5.14.4  | 1         | 5%      |
| 5.14.11 | 1         | 5%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 6         | 30%     |
| 5.7     | 5         | 25%     |
| 5.11    | 5         | 25%     |
| 5.13    | 4         | 20%     |

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


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GNOME   | 19        | 95%     |
| Unknown | 1         | 5%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 19        | 95%     |
| Unknown | 1         | 5%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 20        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 10        | 50%     |
| ru_RU | 3         | 15%     |
| fr_FR | 3         | 15%     |
| sk_SK | 1         | 5%      |
| pt_BR | 1         | 5%      |
| hu_HU | 1         | 5%      |
| es_ES | 1         | 5%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 20        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ext4 | 20        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 19        | 95%     |
| GPT     | 1         | 5%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 20        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 20        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 6         | 30%     |
| Lenovo           | 4         | 20%     |
| Dell             | 4         | 20%     |
| ASUSTek Computer | 2         | 10%     |
| Toshiba          | 1         | 5%      |
| Gateway          | 1         | 5%      |
| Chuwi            | 1         | 5%      |
| Acer             | 1         | 5%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| HP Pavilion 17                      | 2         | 10%     |
| Toshiba Satellite C55-A-1F5         | 1         | 5%      |
| Lenovo Yoga Slim 7 14ARE05 82A2     | 1         | 5%      |
| Lenovo ThinkPad Edge E531 68851P6   | 1         | 5%      |
| Lenovo IdeaPad S340-14API 81NB      | 1         | 5%      |
| Lenovo IdeaPad S145-15IWL 81S9      | 1         | 5%      |
| HP ProBook 430 G3                   | 1         | 5%      |
| HP Pavilion Notebook                | 1         | 5%      |
| HP Pavilion Gaming Laptop 15-ec0xxx | 1         | 5%      |
| HP Laptop 14-dk1xxx                 | 1         | 5%      |
| Gateway NE71B                       | 1         | 5%      |
| Dell Precision M6800                | 1         | 5%      |
| Dell Latitude 7490                  | 1         | 5%      |
| Dell Inspiron 5566                  | 1         | 5%      |
| Dell Inspiron 3542                  | 1         | 5%      |
| Chuwi HeroBook                      | 1         | 5%      |
| ASUS X555LD                         | 1         | 5%      |
| ASUS E202SA                         | 1         | 5%      |
| Acer ChiefRiver Platform            | 1         | 5%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| HP Pavilion       | 4         | 20%     |
| Lenovo IdeaPad    | 2         | 10%     |
| Dell Inspiron     | 2         | 10%     |
| Toshiba Satellite | 1         | 5%      |
| Lenovo Yoga       | 1         | 5%      |
| Lenovo ThinkPad   | 1         | 5%      |
| HP ProBook        | 1         | 5%      |
| HP Laptop         | 1         | 5%      |
| Gateway NE71B     | 1         | 5%      |
| Dell Precision    | 1         | 5%      |
| Dell Latitude     | 1         | 5%      |
| Chuwi HeroBook    | 1         | 5%      |
| ASUS X555LD       | 1         | 5%      |
| ASUS E202SA       | 1         | 5%      |
| Acer ChiefRiver   | 1         | 5%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 5         | 25%     |
| 2013 | 5         | 25%     |
| 2014 | 3         | 15%     |
| 2015 | 2         | 10%     |
| 2020 | 1         | 5%      |
| 2018 | 1         | 5%      |
| 2017 | 1         | 5%      |
| 2016 | 1         | 5%      |
| 2012 | 1         | 5%      |

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
| Disabled | 20        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 20        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 12        | 60%     |
| 3.01-4.0   | 4         | 20%     |
| 8.01-16.0  | 3         | 15%     |
| 1.01-2.0   | 1         | 5%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 16        | 80%     |
| 2.01-3.0 | 2         | 10%     |
| 4.01-8.0 | 1         | 5%      |
| 0.51-1.0 | 1         | 5%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 19        | 95%     |
| 2      | 1         | 5%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 12        | 60%     |
| Yes       | 8         | 40%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 17        | 85%     |
| No        | 3         | 15%     |

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
| Yes       | 16        | 80%     |
| No        | 4         | 20%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 4         | 20%     |
| France      | 3         | 15%     |
| Ukraine     | 2         | 10%     |
| Brazil      | 2         | 10%     |
| UAE         | 1         | 5%      |
| Slovakia    | 1         | 5%      |
| Serbia      | 1         | 5%      |
| Russia      | 1         | 5%      |
| Greece      | 1         | 5%      |
| Finland     | 1         | 5%      |
| El Salvador | 1         | 5%      |
| Chile       | 1         | 5%      |
| Canada      | 1         | 5%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Vancouver         | 1         | 5%      |
| Uruguaiana        | 1         | 5%      |
| Talence           | 1         | 5%      |
| Sobral            | 1         | 5%      |
| Skydra            | 1         | 5%      |
| Santiago          | 1         | 5%      |
| Pori              | 1         | 5%      |
| Novi Sad          | 1         | 5%      |
| Millers Creek     | 1         | 5%      |
| Mariupol          | 1         | 5%      |
| Levis             | 1         | 5%      |
| Lehighton         | 1         | 5%      |
| Kyiv              | 1         | 5%      |
| Krasnoyarsk       | 1         | 5%      |
| Grandview         | 1         | 5%      |
| Castelnau-le-Lez  | 1         | 5%      |
| Bratislava        | 1         | 5%      |
| Antiguo Cuscatlan | 1         | 5%      |
| Abu Dhabi         | 1         | 5%      |
| Abbeville         | 1         | 5%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 23.81%  |
| Seagate             | 3         | 3      | 14.29%  |
| Kingston            | 2         | 2      | 9.52%   |
| HGST                | 2         | 2      | 9.52%   |
| Transcend           | 1         | 1      | 4.76%   |
| Toshiba             | 1         | 1      | 4.76%   |
| SSSTC               | 1         | 1      | 4.76%   |
| SK Hynix            | 1         | 1      | 4.76%   |
| SanDisk             | 1         | 1      | 4.76%   |
| Samsung Electronics | 1         | 1      | 4.76%   |
| Intel               | 1         | 1      | 4.76%   |
| HECTRON             | 1         | 1      | 4.76%   |
| Crucial             | 1         | 1      | 4.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD          | 1         | 4.76%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 4.76%   |
| WDC WD5000LPVX-08V0TT5 500GB              | 1         | 4.76%   |
| WDC WD3200LPVX-08V0TT5 320GB              | 1         | 4.76%   |
| WDC WD10SPZX-24Z10 1TB                    | 1         | 4.76%   |
| Transcend TS64GMTS400 64GB SSD            | 1         | 4.76%   |
| Toshiba MQ01ABD032 320GB                  | 1         | 4.76%   |
| SSSTC CVB-8D128-HP 128GB                  | 1         | 4.76%   |
| SK Hynix SKHynix_HFS512GD9TNG-L3A0B 512GB | 1         | 4.76%   |
| Seagate ST9500325AS 500GB                 | 1         | 4.76%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 1         | 4.76%   |
| Seagate ST1000LM035-1RK172 1TB            | 1         | 4.76%   |
| SanDisk SD8SN8U512G1002 512GB SSD         | 1         | 4.76%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB    | 1         | 4.76%   |
| Kingston SHFS37A120G 120GB SSD            | 1         | 4.76%   |
| Kingston SA400S37120G 120GB SSD           | 1         | 4.76%   |
| Intel SSDSCKKF256G8 SATA 256GB            | 1         | 4.76%   |
| HGST HTS541010A9E680 1TB                  | 1         | 4.76%   |
| HGST HTS541010A7E630 1TB                  | 1         | 4.76%   |
| HECTRON HECX1-60G                         | 1         | 4.76%   |
| Crucial CT240BX500SSD1 240GB              | 1         | 4.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 40%     |
| Seagate | 3         | 3      | 30%     |
| HGST    | 2         | 2      | 20%     |
| Toshiba | 1         | 1      | 10%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor    | Notebooks | Drives | Percent |
|-----------|-----------|--------|---------|
| Kingston  | 2         | 2      | 25%     |
| WDC       | 1         | 1      | 12.5%   |
| Transcend | 1         | 1      | 12.5%   |
| SSSTC     | 1         | 1      | 12.5%   |
| SanDisk   | 1         | 1      | 12.5%   |
| Intel     | 1         | 1      | 12.5%   |
| Crucial   | 1         | 1      | 12.5%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 10        | 10     | 47.62%  |
| SSD     | 8         | 8      | 38.1%   |
| NVMe    | 2         | 2      | 9.52%   |
| Unknown | 1         | 1      | 4.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 18        | 19     | 90%     |
| NVMe | 2         | 2      | 10%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 12        | 13     | 70.59%  |
| 0.51-1.0   | 5         | 5      | 29.41%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 7         | 35%     |
| 101-250    | 7         | 35%     |
| 501-1000   | 4         | 20%     |
| 51-100     | 2         | 10%     |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 17        | 85%     |
| 21-50   | 3         | 15%     |

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
| Detected | 19        | 20     | 95%     |
| Works    | 1         | 1      | 5%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 12        | 60%     |
| AMD                 | 6         | 30%     |
| SK Hynix            | 1         | 5%      |
| Samsung Electronics | 1         | 5%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 6         | 28.57%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 14.29%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 3         | 14.29%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 9.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 9.52%   |
| SK Hynix Non-Volatile memory controller                                          | 1         | 4.76%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 4.76%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 4.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 4.76%   |
| AMD FCH IDE Controller                                                           | 1         | 4.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 18        | 85.71%  |
| NVMe | 2         | 9.52%   |
| IDE  | 1         | 4.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 12        | 60%     |
| AMD    | 8         | 40%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 10%     |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 5%      |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 5%      |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 5%      |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 5%      |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 5%      |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 5%      |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 5%      |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 5%      |
| Intel Celeron 2957U @ 1.40GHz                 | 1         | 5%      |
| Intel Atom x5-E8000 CPU @ 1.04GHz             | 1         | 5%      |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 5%      |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 5%      |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 5%      |
| AMD E1-1200 APU with Radeon HD Graphics       | 1         | 5%      |
| AMD Athlon Silver 3050U with Radeon Graphics  | 1         | 5%      |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 1         | 5%      |
| AMD A8-5550M APU with Radeon HD Graphics      | 1         | 5%      |
| AMD A10-5745M APU with Radeon HD Graphics     | 1         | 5%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Intel Core i5 | 4         | 20%     |
| Intel Core i3 | 4         | 20%     |
| Intel Celeron | 2         | 10%     |
| AMD Ryzen 5   | 2         | 10%     |
| AMD A8        | 2         | 10%     |
| Intel Core i7 | 1         | 5%      |
| Intel Atom    | 1         | 5%      |
| AMD Ryzen 7   | 1         | 5%      |
| AMD E1        | 1         | 5%      |
| AMD Athlon    | 1         | 5%      |
| AMD A10       | 1         | 5%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 13        | 65%     |
| 4      | 6         | 30%     |
| 8      | 1         | 5%      |

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
| 2      | 13        | 65%     |
| 1      | 7         | 35%     |

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
| 0x306a9    | 3         | 15%     |
| 0x08108109 | 3         | 15%     |
| 0x406e3    | 2         | 10%     |
| 0x40651    | 2         | 10%     |
| 0x06001119 | 2         | 10%     |
| 0x806ec    | 1         | 5%      |
| 0x806ea    | 1         | 5%      |
| 0x406c4    | 1         | 5%      |
| 0x406c3    | 1         | 5%      |
| 0x306c3    | 1         | 5%      |
| 0x08600106 | 1         | 5%      |
| 0x07030105 | 1         | 5%      |
| 0x0500010d | 1         | 5%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Zen+       | 3         | 15%     |
| IvyBridge  | 3         | 15%     |
| Haswell    | 3         | 15%     |
| Skylake    | 2         | 10%     |
| Silvermont | 2         | 10%     |
| Piledriver | 2         | 10%     |
| KabyLake   | 2         | 10%     |
| Zen 2      | 1         | 5%      |
| Puma       | 1         | 5%      |
| Bobcat     | 1         | 5%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 12        | 48%     |
| AMD    | 9         | 36%     |
| Nvidia | 4         | 16%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 11.11%  |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 11.11%  |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 7.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 7.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 7.41%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 7.41%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 3.7%    |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 3.7%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 3.7%    |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 3.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 3.7%    |
| Intel UHD Graphics 620                                                                   | 1         | 3.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 3.7%    |
| AMD Wrestler [Radeon HD 7310]                                                            | 1         | 3.7%    |
| AMD Saturn XT [FirePro M6100]                                                            | 1         | 3.7%    |
| AMD Richland [Radeon HD 8610G]                                                           | 1         | 3.7%    |
| AMD Richland [Radeon HD 8550G]                                                           | 1         | 3.7%    |
| AMD Renoir                                                                               | 1         | 3.7%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 3.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 8         | 40%     |
| 1 x AMD        | 5         | 25%     |
| Intel + Nvidia | 3         | 15%     |
| 2 x AMD        | 2         | 10%     |
| Intel + AMD    | 1         | 5%      |
| AMD + Nvidia   | 1         | 5%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver | Notebooks | Percent |
|--------|-----------|---------|
| Free   | 20        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 8         | 40%     |
| 0.51-1.0   | 5         | 25%     |
| 1.01-2.0   | 3         | 15%     |
| 0.01-0.5   | 3         | 15%     |
| 2.01-3.0   | 1         | 5%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 6         | 28.57%  |
| LG Display          | 5         | 23.81%  |
| Chimei Innolux      | 3         | 14.29%  |
| BOE                 | 3         | 14.29%  |
| Samsung Electronics | 2         | 9.52%   |
| InfoVision          | 1         | 4.76%   |
| Dell                | 1         | 4.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch | 1         | 4.76%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 382x215mm 17.3-inch | 1         | 4.76%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch         | 1         | 4.76%   |
| LG Display LCD Monitor LGD04B3 1920x1080 350x190mm 15.7-inch         | 1         | 4.76%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch          | 1         | 4.76%   |
| LG Display LCD Monitor LGD0372 1600x900 382x215mm 17.3-inch          | 1         | 4.76%   |
| LG Display LCD Monitor LGD02DA 1920x1080 380x220mm 17.3-inch         | 1         | 4.76%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 1         | 4.76%   |
| Dell P2421D DELD0FF 2560x1440 527x296mm 23.8-inch                    | 1         | 4.76%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 1         | 4.76%   |
| Chimei Innolux LCD Monitor CMN15BB 1920x1080 344x194mm 15.5-inch     | 1         | 4.76%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch      | 1         | 4.76%   |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                 | 1         | 4.76%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 1         | 4.76%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                 | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch       | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO233C 1366x768 309x173mm 13.9-inch        | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO223D 1920x1080 309x174mm 14.0-inch       | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO162C 1366x768 293x164mm 13.2-inch        | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch        | 1         | 4.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1366x768 (WXGA) | 9         | 42.86%  |
| 1920x1080 (FHD) | 8         | 38.1%   |
| 1600x900 (HD+)  | 3         | 14.29%  |
| 2560x1440 (QHD) | 1         | 4.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 7         | 33.33%  |
| 14     | 5         | 23.81%  |
| 17     | 4         | 19.05%  |
| 13     | 3         | 14.29%  |
| 24     | 1         | 4.76%   |
| 11     | 1         | 4.76%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 14        | 66.67%  |
| 351-400     | 4         | 19.05%  |
| 201-300     | 2         | 9.52%   |
| 501-600     | 1         | 4.76%   |

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
| 81-90          | 7         | 33.33%  |
| 101-110        | 7         | 33.33%  |
| 121-130        | 4         | 19.05%  |
| 71-80          | 1         | 4.76%   |
| 51-60          | 1         | 4.76%   |
| 201-250        | 1         | 4.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 10        | 47.62%  |
| 101-120 | 10        | 47.62%  |
| 51-100  | 1         | 4.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 19        | 95%     |
| 2     | 1         | 5%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 13        | 41.94%  |
| Qualcomm Atheros      | 7         | 22.58%  |
| Intel                 | 6         | 19.35%  |
| Broadcom Limited      | 2         | 6.45%   |
| TP-Link               | 1         | 3.23%   |
| Google                | 1         | 3.23%   |
| Broadcom              | 1         | 3.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 15.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 13.16%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 7.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 5.26%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 2.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.63%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.63%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 2.63%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 2.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 2.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 2.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 2.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 2.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 2.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.63%   |
| Intel Wireless 3165                                               | 1         | 2.63%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 2.63%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.63%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.63%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 2.63%   |
| Intel Centrino Wireless-N 105                                     | 1         | 2.63%   |
| Google Pixel 6                                                    | 1         | 2.63%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 1         | 2.63%   |
| Broadcom Limited BCM43142 802.11b/g/n                             | 1         | 2.63%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 2.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 7         | 35%     |
| Qualcomm Atheros      | 6         | 30%     |
| Intel                 | 4         | 20%     |
| Broadcom Limited      | 2         | 10%     |
| Broadcom              | 1         | 5%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 3         | 15%     |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 2         | 10%     |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 5%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 5%      |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 1         | 5%      |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                 | 1         | 5%      |
| Realtek RTL8188EE Wireless Network Adapter                 | 1         | 5%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1         | 5%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 5%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 1         | 5%      |
| Intel Wireless 3165                                        | 1         | 5%      |
| Intel Wi-Fi 6 AX200                                        | 1         | 5%      |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1         | 5%      |
| Intel Centrino Wireless-N 105                              | 1         | 5%      |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter | 1         | 5%      |
| Broadcom Limited BCM43142 802.11b/g/n                      | 1         | 5%      |
| Broadcom BCM43142 802.11b/g/n                              | 1         | 5%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 12        | 66.67%  |
| Qualcomm Atheros      | 2         | 11.11%  |
| Intel                 | 2         | 11.11%  |
| TP-Link               | 1         | 5.56%   |
| Google                | 1         | 5.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 33.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 27.78%  |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 5.56%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 5.56%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 5.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 5.56%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 5.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 5.56%   |
| Google Pixel 6                                                    | 1         | 5.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 20        | 54.05%  |
| Ethernet | 17        | 45.95%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 15        | 62.5%   |
| WiFi     | 9         | 37.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 15        | 75%     |
| 1     | 4         | 20%     |
| 0     | 1         | 5%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 17        | 85%     |
| Yes  | 3         | 15%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 5         | 31.25%  |
| Qualcomm Atheros Communications | 4         | 25%     |
| Intel                           | 3         | 18.75%  |
| Lite-On Technology              | 2         | 12.5%   |
| Toshiba                         | 1         | 6.25%   |
| Dell                            | 1         | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                      | 3         | 18.75%  |
| Qualcomm Atheros  Bluetooth Device           | 3         | 18.75%  |
| Lite-On Broadcom BCM43142A0 Bluetooth Device | 2         | 12.5%   |
| Intel Bluetooth wireless interface           | 2         | 12.5%   |
| Toshiba Bluetooth Device                     | 1         | 6.25%   |
| Realtek RTL8821A Bluetooth                   | 1         | 6.25%   |
| Realtek  Bluetooth 4.2 Adapter               | 1         | 6.25%   |
| Qualcomm Atheros AR9462 Bluetooth            | 1         | 6.25%   |
| Intel AX200 Bluetooth                        | 1         | 6.25%   |
| Dell Broadcom BCM20702A0 Bluetooth           | 1         | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 12        | 52.17%  |
| AMD    | 9         | 39.13%  |
| Nvidia | 2         | 8.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH Azalia Controller                                                                         | 4         | 12.12%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 12.12%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 9.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 9.09%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 6.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 6.06%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 6.06%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 6.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 6.06%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 3.03%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 3.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 3.03%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 3.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 3.03%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 3.03%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                                | 1         | 3.03%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 3.03%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 3.03%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Micron Technology | 1         | 100%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Micron RAM MT53E1G32D4NQ-046WTE 8GB Row Of Chips LPDDR4 4266MT/s | 1         | 100%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| LPDDR4 | 1         | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Row Of Chips | 1         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 8192 | 1         | 100%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 4266  | 1         | 100%    |

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
| Suyin                                  | 3         | 15.79%  |
| Realtek Semiconductor                  | 3         | 15.79%  |
| Sunplus Innovation Technology          | 2         | 10.53%  |
| Microdia                               | 2         | 10.53%  |
| Syntek                                 | 1         | 5.26%   |
| Logitech                               | 1         | 5.26%   |
| IMC Networks                           | 1         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Suyin HP Truevision HD                           | 3         | 15.79%  |
| Realtek USB Camera                               | 2         | 10.53%  |
| Chicony Integrated Camera                        | 2         | 10.53%  |
| Syntek Integrated Camera                         | 1         | 5.26%   |
| Sunplus Integrated_Webcam_HD                     | 1         | 5.26%   |
| Sunplus HD WebCam                                | 1         | 5.26%   |
| Realtek Integrated Camera                        | 1         | 5.26%   |
| Microdia Integrated_Webcam_HD                    | 1         | 5.26%   |
| Microdia Integrated Webcam HD                    | 1         | 5.26%   |
| Logitech Webcam C270                             | 1         | 5.26%   |
| IMC Networks HP TrueVision HD Camera             | 1         | 5.26%   |
| Chicony USB2.0 VGA UVC WebCam                    | 1         | 5.26%   |
| Chicony TOSHIBA Web Camera - HD                  | 1         | 5.26%   |
| Chicony HP HD Camera                             | 1         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 1         | 5.26%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 1         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader | 1         | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 8         | 40%     |
| 2     | 5         | 25%     |
| 4     | 3         | 15%     |
| 3     | 3         | 15%     |
| 0     | 1         | 5%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 11        | 28.21%  |
| Communication controller | 10        | 25.64%  |
| Multimedia controller    | 4         | 10.26%  |
| Card reader              | 4         | 10.26%  |
| Bluetooth                | 3         | 7.69%   |
| Net/ethernet             | 2         | 5.13%   |
| Graphics card            | 2         | 5.13%   |
| Storage/ide              | 1         | 2.56%   |
| Fingerprint reader       | 1         | 2.56%   |
| Chipcard                 | 1         | 2.56%   |

