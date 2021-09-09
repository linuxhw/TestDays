Elementary 6 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Elementary 6.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=elementary-6

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

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo    | ThinkPad X201 3249CTO       | [7b3432fcf6](https://linux-hardware.org/?probe=7b3432fcf6) | Sep 08, 2021 |
| HP        | Laptop 14-dq1xxx            | [0614925ee7](https://linux-hardware.org/?probe=0614925ee7) | Sep 08, 2021 |
| Gateway   | NV54 Series                 | [fcf57528ed](https://linux-hardware.org/?probe=fcf57528ed) | Sep 08, 2021 |
| Sony      | Serie VJC14                 | [27828e1dfb](https://linux-hardware.org/?probe=27828e1dfb) | Sep 07, 2021 |
| Sony      | Serie VJC14                 | [4c1200e7cf](https://linux-hardware.org/?probe=4c1200e7cf) | Sep 07, 2021 |
| Lenovo    | V330-15IKB 81AX             | [797db05baf](https://linux-hardware.org/?probe=797db05baf) | Sep 06, 2021 |
| HP        | Laptop 15-bs1xx             | [91ecd39f66](https://linux-hardware.org/?probe=91ecd39f66) | Sep 05, 2021 |
| Medion    | AKOYA THE TOUCH 10          | [d49d62a2f5](https://linux-hardware.org/?probe=d49d62a2f5) | Sep 04, 2021 |
| Apple     | MacBookPro8,1               | [da332ba09e](https://linux-hardware.org/?probe=da332ba09e) | Sep 01, 2021 |
| HP        | EliteBook Folio 9470m       | [adbb6a690a](https://linux-hardware.org/?probe=adbb6a690a) | Sep 01, 2021 |
| Dell      | Latitude 3580               | [2befbbba9e](https://linux-hardware.org/?probe=2befbbba9e) | Aug 31, 2021 |
| HP        | Pavilion g6                 | [7dba3c201c](https://linux-hardware.org/?probe=7dba3c201c) | Aug 31, 2021 |
| HP        | Pavilion Aero Laptop 13-... | [48c720456a](https://linux-hardware.org/?probe=48c720456a) | Aug 30, 2021 |
| HP        | ProBook 4320s               | [94f189cea1](https://linux-hardware.org/?probe=94f189cea1) | Aug 29, 2021 |
| eMachines | G525                        | [d64e29475f](https://linux-hardware.org/?probe=d64e29475f) | Aug 29, 2021 |
| Lenovo    | ThinkPad X201 3249CTO       | [0a9bdb4827](https://linux-hardware.org/?probe=0a9bdb4827) | Aug 27, 2021 |
| Acer      | Aspire A515-51G             | [df0d3e8ac4](https://linux-hardware.org/?probe=df0d3e8ac4) | Aug 26, 2021 |
| HP        | Laptop 15-bs0xx             | [fae546f5cb](https://linux-hardware.org/?probe=fae546f5cb) | Aug 20, 2021 |
| Apple     | MacBookPro9,1               | [e9bec90506](https://linux-hardware.org/?probe=e9bec90506) | Aug 19, 2021 |
| Acer      | Aspire F5-573G              | [9d7628068c](https://linux-hardware.org/?probe=9d7628068c) | Aug 19, 2021 |
| Dell      | XPS L321X                   | [34d7fb6cbb](https://linux-hardware.org/?probe=34d7fb6cbb) | Aug 18, 2021 |
| HP        | ProBook 450 G8 Notebook ... | [f30480d463](https://linux-hardware.org/?probe=f30480d463) | Aug 17, 2021 |
| HP        | Notebook                    | [a3058005e3](https://linux-hardware.org/?probe=a3058005e3) | Aug 16, 2021 |
| HP        | Notebook                    | [7800ef9623](https://linux-hardware.org/?probe=7800ef9623) | Aug 16, 2021 |
| Lenovo    | IdeaPad 330-15IKB 81FE      | [fa6c69671f](https://linux-hardware.org/?probe=fa6c69671f) | Aug 16, 2021 |
| Apple     | MacBookPro9,1               | [a6b2c12401](https://linux-hardware.org/?probe=a6b2c12401) | Aug 14, 2021 |
| Dell      | Precision 5760              | [824e5e7dad](https://linux-hardware.org/?probe=824e5e7dad) | Aug 14, 2021 |
| Acer      | Aspire A514-54              | [dcfc87a32f](https://linux-hardware.org/?probe=dcfc87a32f) | Aug 14, 2021 |
| Acer      | Aspire A514-54              | [e354646c04](https://linux-hardware.org/?probe=e354646c04) | Aug 13, 2021 |
| HP        | Pavilion Gaming Laptop 1... | [4e6f050b43](https://linux-hardware.org/?probe=4e6f050b43) | Aug 10, 2021 |
| Toshiba   | Satellite L500              | [76a8d2c20a](https://linux-hardware.org/?probe=76a8d2c20a) | Jul 29, 2021 |
| Google    | Cave                        | [e2617f0c2d](https://linux-hardware.org/?probe=e2617f0c2d) | Jul 25, 2021 |
| Toshiba   | Satellite L500              | [7124417642](https://linux-hardware.org/?probe=7124417642) | Jul 22, 2021 |
| HP        | Stream Laptop 14-cb1xxx     | [0447155931](https://linux-hardware.org/?probe=0447155931) | Jul 02, 2021 |
| Acer      | Swift SF314-55G             | [c371b46cbe](https://linux-hardware.org/?probe=c371b46cbe) | Jun 30, 2021 |
| Acer      | Swift SF315-41              | [8df5e13fc0](https://linux-hardware.org/?probe=8df5e13fc0) | Jun 18, 2021 |
| Acer      | Swift SF314-55G             | [4e5cf8aa1e](https://linux-hardware.org/?probe=4e5cf8aa1e) | Jun 13, 2021 |
| Acer      | ConceptD CN315-71P          | [5ecea84320](https://linux-hardware.org/?probe=5ecea84320) | May 15, 2021 |
| Apple     | MacBookPro8,2               | [e87a073ae8](https://linux-hardware.org/?probe=e87a073ae8) | Mar 18, 2021 |
| HP        | EliteBook 840 G3            | [1e31858e51](https://linux-hardware.org/?probe=1e31858e51) | Mar 09, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.11.0-27-generic     | 16        | 48.48%  |
| 5.11.0-25-generic     | 10        | 30.3%   |
| 5.8.0-55-generic      | 2         | 6.06%   |
| 5.8.0-63-generic      | 1         | 3.03%   |
| 5.8.0-53-generic      | 1         | 3.03%   |
| 5.8.0-50-generic      | 1         | 3.03%   |
| 5.8.0-44-generic      | 1         | 3.03%   |
| 5.11.0-051100-generic | 1         | 3.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 27        | 81.82%  |
| 5.8.0   | 6         | 18.18%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 27        | 81.82%  |
| 5.8     | 6         | 18.18%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 33        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Pantheon   | 27        | 81.82%  |
| Unknown    | 4         | 12.12%  |
| X-Cinnamon | 1         | 3.03%   |
| GNOME      | 1         | 3.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 33        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 25        | 75.76%  |
| TDM     | 4         | 12.12%  |
| LightDM | 2         | 6.06%   |
| GDM     | 2         | 6.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 18        | 54.55%  |
| es_ES | 3         | 9.09%   |
| zh_CN | 2         | 6.06%   |
| pt_BR | 2         | 6.06%   |
| en_CA | 2         | 6.06%   |
| de_DE | 2         | 6.06%   |
| ru_RU | 1         | 3.03%   |
| fr_FR | 1         | 3.03%   |
| en_GB | 1         | 3.03%   |
| en_AU | 1         | 3.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 19        | 57.58%  |
| BIOS | 14        | 42.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 30        | 90.91%  |
| Overlay | 2         | 6.06%   |
| Btrfs   | 1         | 3.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 25        | 75.76%  |
| GPT     | 6         | 18.18%  |
| MBR     | 2         | 6.06%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 32        | 96.97%  |
| Yes       | 1         | 3.03%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 30        | 90.91%  |
| Yes       | 3         | 9.09%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 12        | 36.36%  |
| Acer            | 6         | 18.18%  |
| Apple           | 4         | 12.12%  |
| Lenovo          | 3         | 9.09%   |
| Dell            | 3         | 9.09%   |
| Toshiba         | 1         | 3.03%   |
| Sony            | 1         | 3.03%   |
| Medion          | 1         | 3.03%   |
| Gateway         | 1         | 3.03%   |
| eMachines       | 1         | 3.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Apple MacBookPro9,1                 | 2         | 6.06%   |
| Toshiba Satellite L500              | 1         | 3.03%   |
| Sony Serie VJC14                    | 1         | 3.03%   |
| Medion AKOYA THE TOUCH 10           | 1         | 3.03%   |
| Lenovo V330-15IKB 81AX              | 1         | 3.03%   |
| Lenovo ThinkPad X201 3249CTO        | 1         | 3.03%   |
| Lenovo IdeaPad 330-15IKB 81FE       | 1         | 3.03%   |
| HP Stream Laptop 14-cb1xxx          | 1         | 3.03%   |
| HP ProBook 450 G8 Notebook PC       | 1         | 3.03%   |
| HP ProBook 4320s                    | 1         | 3.03%   |
| HP Pavilion Gaming Laptop 15-ec0xxx | 1         | 3.03%   |
| HP Pavilion g6                      | 1         | 3.03%   |
| HP Pavilion Aero Laptop 13-be0xxx   | 1         | 3.03%   |
| HP Notebook                         | 1         | 3.03%   |
| HP Laptop 15-bs1xx                  | 1         | 3.03%   |
| HP Laptop 15-bs0xx                  | 1         | 3.03%   |
| HP Laptop 14-dq1xxx                 | 1         | 3.03%   |
| HP EliteBook Folio 9470m            | 1         | 3.03%   |
| HP EliteBook 840 G3                 | 1         | 3.03%   |
| Gateway NV54 Series                 | 1         | 3.03%   |
| eMachines G525                      | 1         | 3.03%   |
| Dell XPS L321X                      | 1         | 3.03%   |
| Dell Precision 5760                 | 1         | 3.03%   |
| Dell Latitude 3580                  | 1         | 3.03%   |
| Apple MacBookPro8,2                 | 1         | 3.03%   |
| Apple MacBookPro8,1                 | 1         | 3.03%   |
| Acer Swift SF315-41                 | 1         | 3.03%   |
| Acer Swift SF314-55G                | 1         | 3.03%   |
| Acer ConceptD CN315-71P             | 1         | 3.03%   |
| Acer Aspire F5-573G                 | 1         | 3.03%   |
| Acer Aspire A515-51G                | 1         | 3.03%   |
| Acer Aspire A514-54                 | 1         | 3.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| HP Pavilion       | 3         | 9.09%   |
| HP Laptop         | 3         | 9.09%   |
| Acer Aspire       | 3         | 9.09%   |
| HP ProBook        | 2         | 6.06%   |
| HP EliteBook      | 2         | 6.06%   |
| Apple MacBookPro9 | 2         | 6.06%   |
| Apple MacBookPro8 | 2         | 6.06%   |
| Acer Swift        | 2         | 6.06%   |
| Toshiba Satellite | 1         | 3.03%   |
| Sony Serie        | 1         | 3.03%   |
| Medion AKOYA      | 1         | 3.03%   |
| Lenovo V330-15IKB | 1         | 3.03%   |
| Lenovo ThinkPad   | 1         | 3.03%   |
| Lenovo IdeaPad    | 1         | 3.03%   |
| HP Stream         | 1         | 3.03%   |
| HP Notebook       | 1         | 3.03%   |
| Gateway NV54      | 1         | 3.03%   |
| eMachines G525    | 1         | 3.03%   |
| Dell XPS          | 1         | 3.03%   |
| Dell Precision    | 1         | 3.03%   |
| Dell Latitude     | 1         | 3.03%   |
| Acer ConceptD     | 1         | 3.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 8         | 24.24%  |
| 2019 | 5         | 15.15%  |
| 2018 | 5         | 15.15%  |
| 2020 | 3         | 9.09%   |
| 2010 | 3         | 9.09%   |
| 2017 | 2         | 6.06%   |
| 2013 | 2         | 6.06%   |
| 2012 | 2         | 6.06%   |
| 2015 | 1         | 3.03%   |
| 2014 | 1         | 3.03%   |
| 2009 | 1         | 3.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 33        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 25        | 75.76%  |
| Enabled  | 8         | 24.24%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 33        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 11        | 33.33%  |
| 3.01-4.0   | 8         | 24.24%  |
| 16.01-24.0 | 7         | 21.21%  |
| 32.01-64.0 | 3         | 9.09%   |
| 8.01-16.0  | 3         | 9.09%   |
| 1.01-2.0   | 1         | 3.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 12        | 35.29%  |
| 1.01-2.0 | 12        | 35.29%  |
| 4.01-8.0 | 5         | 14.71%  |
| 3.01-4.0 | 5         | 14.71%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 24        | 72.73%  |
| 2      | 8         | 24.24%  |
| 3      | 1         | 3.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 72.73%  |
| Yes       | 9         | 27.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 81.82%  |
| No        | 6         | 18.18%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 96.97%  |
| No        | 1         | 3.03%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 88.24%  |
| No        | 4         | 11.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 6         | 18.18%  |
| India       | 5         | 15.15%  |
| Germany     | 2         | 6.06%   |
| Canada      | 2         | 6.06%   |
| Brazil      | 2         | 6.06%   |
| Argentina   | 2         | 6.06%   |
| UK          | 1         | 3.03%   |
| Serbia      | 1         | 3.03%   |
| Russia      | 1         | 3.03%   |
| Netherlands | 1         | 3.03%   |
| Myanmar     | 1         | 3.03%   |
| Mexico      | 1         | 3.03%   |
| Kazakhstan  | 1         | 3.03%   |
| Japan       | 1         | 3.03%   |
| Guyana      | 1         | 3.03%   |
| Guatemala   | 1         | 3.03%   |
| France      | 1         | 3.03%   |
| China       | 1         | 3.03%   |
| Belgium     | 1         | 3.03%   |
| Australia   | 1         | 3.03%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Vernon           | 1         | 2.94%   |
| Toledo           | 1         | 2.94%   |
| Tokyo            | 1         | 2.94%   |
| Thousand Oaks    | 1         | 2.94%   |
| Stevenage        | 1         | 2.94%   |
| Sinop            | 1         | 2.94%   |
| S??o Pedro       | 1         | 2.94%   |
| Santa Monica     | 1         | 2.94%   |
| Sakai            | 1         | 2.94%   |
| Sacramento       | 1         | 2.94%   |
| Quer?©taro City  | 1         | 2.94%   |
| Perth            | 1         | 2.94%   |
| Peekskill        | 1         | 2.94%   |
| Patna            | 1         | 2.94%   |
| Paris            | 1         | 2.94%   |
| Naaldwijk        | 1         | 2.94%   |
| Moscow           | 1         | 2.94%   |
| Montreal         | 1         | 2.94%   |
| Monheim am Rhein | 1         | 2.94%   |
| Mandalay         | 1         | 2.94%   |
| Lucknow          | 1         | 2.94%   |
| Len?«nskoe       | 1         | 2.94%   |
| Lanaken          | 1         | 2.94%   |
| Kovin            | 1         | 2.94%   |
| Koraput          | 1         | 2.94%   |
| Jalandhar        | 1         | 2.94%   |
| Hollern          | 1         | 2.94%   |
| Guatemala City   | 1         | 2.94%   |
| Georgetown       | 1         | 2.94%   |
| Chattanooga      | 1         | 2.94%   |
| C??rdoba         | 1         | 2.94%   |
| Buenos Aires     | 1         | 2.94%   |
| Bhopal           | 1         | 2.94%   |
| Beijing          | 1         | 2.94%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 10        | 11     | 23.26%  |
| Seagate                   | 5         | 6      | 11.63%  |
| Samsung Electronics       | 5         | 5      | 11.63%  |
| Toshiba                   | 3         | 3      | 6.98%   |
| Hitachi                   | 3         | 3      | 6.98%   |
| Crucial                   | 3         | 3      | 6.98%   |
| Unknown                   | 2         | 2      | 4.65%   |
| Sandisk                   | 2         | 2      | 4.65%   |
| Kingston                  | 2         | 2      | 4.65%   |
| SK Hynix                  | 1         | 1      | 2.33%   |
| Phison                    | 1         | 1      | 2.33%   |
| Micron/Crucial Technology | 1         | 1      | 2.33%   |
| Micron Technology         | 1         | 1      | 2.33%   |
| Mercury                   | 1         | 1      | 2.33%   |
| LITEONIT                  | 1         | 1      | 2.33%   |
| Gigabyte Technology       | 1         | 1      | 2.33%   |
| CLOVER                    | 1         | 1      | 2.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| WDC WD10SPZX-21Z10T0 1TB                 | 2         | 4.55%   |
| Seagate ST1000LM035-1RK172 1TB           | 2         | 4.55%   |
| WDC WDS500G2B0A-00SM50 500GB SSD         | 1         | 2.27%   |
| WDC WD20SPZX-21UA7T0 2TB                 | 1         | 2.27%   |
| WDC WD10SPZX-24Z10T0 1TB                 | 1         | 2.27%   |
| WDC WD10SPZX-22Z10T1 1TB                 | 1         | 2.27%   |
| WDC WD10JPVX-60JC3T1 1TB                 | 1         | 2.27%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 2.27%   |
| WDC PC SN720 SDAPNTW-256G-1014 256GB     | 1         | 2.27%   |
| WDC PC SN530 SDBPNPZ-256G-1114 256GB     | 1         | 2.27%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB     | 1         | 2.27%   |
| Unknown xD/SD/M.S.                       | 1         | 2.27%   |
| Unknown TA2964  64GB                     | 1         | 2.27%   |
| Toshiba MQ01ABD100V -63 1TB              | 1         | 2.27%   |
| Toshiba MQ01ABD100 1TB                   | 1         | 2.27%   |
| Toshiba MK5065GSXF 500GB                 | 1         | 2.27%   |
| SK Hynix NVMe SSD Drive 512GB            | 1         | 2.27%   |
| Seagate ST9250315AS 250GB                | 1         | 2.27%   |
| Seagate ST1000LM049-2GH172 1TB           | 1         | 2.27%   |
| Seagate ST1000LM048-2E7172 1TB           | 1         | 2.27%   |
| SanDisk SDSSDA480G 480GB                 | 1         | 2.27%   |
| Sandisk NVMe SSD Drive 256GB             | 1         | 2.27%   |
| Samsung SSD 860 EVO 2TB                  | 1         | 2.27%   |
| Samsung SSD 860 EVO 250GB                | 1         | 2.27%   |
| Samsung NVMe SSD Drive 256GB             | 1         | 2.27%   |
| Samsung MZNLN128HAHQ-000H1 128GB SSD     | 1         | 2.27%   |
| Samsung HM321HI 320GB                    | 1         | 2.27%   |
| Phison NVMe SSD Drive 2TB                | 1         | 2.27%   |
| Micron/Crucial NVMe SSD Drive 500GB      | 1         | 2.27%   |
| Micron NVMe SSD Drive 512GB              | 1         | 2.27%   |
| Mercury Electra 3G SSD                   | 1         | 2.27%   |
| LITEONIT LMT-256M3M 256GB SSD            | 1         | 2.27%   |
| Kingston SA400S37240G 240GB SSD          | 1         | 2.27%   |
| Kingston SA400S37120G 120GB SSD          | 1         | 2.27%   |
| Hitachi HTS725025A9A364 250GB            | 1         | 2.27%   |
| Hitachi HTS545050B9A300 500GB            | 1         | 2.27%   |
| Hitachi HTS542512K9SA00 120GB            | 1         | 2.27%   |
| Gigabyte GP-GSM2NE3100TNTD 1TB           | 1         | 2.27%   |
| Crucial CT500MX500SSD4 500GB             | 1         | 2.27%   |
| Crucial CT480BX500SSD1 480GB             | 1         | 2.27%   |
| Crucial CT120BX500SSD1 120GB             | 1         | 2.27%   |
| CLOVER CN-M640MBB G267M8B640G7W122 640GB | 1         | 2.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 7      | 36.84%  |
| Seagate             | 5         | 6      | 26.32%  |
| Toshiba             | 3         | 3      | 15.79%  |
| Hitachi             | 3         | 3      | 15.79%  |
| Samsung Electronics | 1         | 1      | 5.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 25%     |
| Crucial             | 3         | 3      | 25%     |
| Kingston            | 2         | 2      | 16.67%  |
| WDC                 | 1         | 1      | 8.33%   |
| SanDisk             | 1         | 1      | 8.33%   |
| Mercury             | 1         | 1      | 8.33%   |
| LITEONIT            | 1         | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 19        | 20     | 46.34%  |
| SSD     | 11        | 12     | 26.83%  |
| NVMe    | 8         | 10     | 19.51%  |
| Unknown | 2         | 2      | 4.88%   |
| MMC     | 1         | 1      | 2.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 27        | 33     | 72.97%  |
| NVMe | 8         | 10     | 21.62%  |
| SAS  | 1         | 1      | 2.7%    |
| MMC  | 1         | 1      | 2.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 15        | 18     | 51.72%  |
| 0.51-1.0   | 12        | 12     | 41.38%  |
| 1.01-2.0   | 2         | 2      | 6.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 12        | 36.36%  |
| 251-500    | 8         | 24.24%  |
| 1001-2000  | 4         | 12.12%  |
| 501-1000   | 4         | 12.12%  |
| 51-100     | 3         | 9.09%   |
| 2001-3000  | 1         | 3.03%   |
| 1-20       | 1         | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 20        | 60.61%  |
| 51-100    | 4         | 12.12%  |
| 21-50     | 3         | 9.09%   |
| 251-500   | 2         | 6.06%   |
| 1001-2000 | 2         | 6.06%   |
| 101-250   | 1         | 3.03%   |
| 501-1000  | 1         | 3.03%   |

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
| Detected | 27        | 35     | 79.41%  |
| Works    | 7         | 10     | 20.59%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 28        | 68.29%  |
| Sandisk                   | 4         | 9.76%   |
| AMD                       | 3         | 7.32%   |
| Phison Electronics        | 2         | 4.88%   |
| SK Hynix                  | 1         | 2.44%   |
| Samsung Electronics       | 1         | 2.44%   |
| Micron/Crucial Technology | 1         | 2.44%   |
| Micron Technology         | 1         | 2.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 8         | 19.05%  |
| Intel Volume Management Device NVMe RAID Controller                                    | 3         | 7.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 3         | 7.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 3         | 7.14%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 2         | 4.76%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 2         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 2         | 4.76%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 4.76%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 2         | 4.76%   |
| SK Hynix NVMe SSD Controller                                                           | 1         | 2.38%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 1         | 2.38%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 1         | 2.38%   |
| Samsung NVMe Controller                                                                | 1         | 2.38%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 2.38%   |
| Phison E12 NVMe Controller                                                             | 1         | 2.38%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                        | 1         | 2.38%   |
| Micron Non-Volatile memory controller                                                  | 1         | 2.38%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 1         | 2.38%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 2.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 2.38%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 2.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 2.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 2.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 23        | 57.5%   |
| NVMe | 8         | 20%     |
| RAID | 6         | 15%     |
| IDE  | 3         | 7.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 29        | 87.88%  |
| AMD    | 4         | 12.12%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 2         | 6.06%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 6.06%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 6.06%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 6.06%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 6.06%   |
| Intel Xeon W-11855M CPU @ 3.20GHz             | 1         | 3.03%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 3.03%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 3.03%   |
| Intel Core i7-3687U CPU @ 2.10GHz             | 1         | 3.03%   |
| Intel Core i7-3615QM CPU @ 2.30GHz            | 1         | 3.03%   |
| Intel Core i7-2637M CPU @ 1.70GHz             | 1         | 3.03%   |
| Intel Core i7-2635QM CPU @ 2.00GHz            | 1         | 3.03%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 3.03%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 3.03%   |
| Intel Core i5-2435M CPU @ 2.40GHz             | 1         | 3.03%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz            | 1         | 3.03%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 3.03%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 1         | 3.03%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz          | 1         | 3.03%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 3.03%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 3.03%   |
| Intel Celeron CPU N2807 @ 1.58GHz             | 1         | 3.03%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 3.03%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 3.03%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 1         | 3.03%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 3.03%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 3.03%   |
| AMD Phenom II N660 Dual-Core Processor        | 1         | 3.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 11        | 33.33%  |
| Intel Core i7           | 8         | 24.24%  |
| Intel Celeron           | 3         | 9.09%   |
| AMD Ryzen 5             | 3         | 9.09%   |
| Other                   | 2         | 6.06%   |
| Intel Pentium Dual-Core | 2         | 6.06%   |
| Intel Xeon              | 1         | 3.03%   |
| Intel Core i3           | 1         | 3.03%   |
| Intel Core 2 Duo        | 1         | 3.03%   |
| AMD Phenom II           | 1         | 3.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 18        | 54.55%  |
| 4      | 12        | 36.36%  |
| 6      | 3         | 9.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 33        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 26        | 78.79%  |
| 1      | 7         | 21.21%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 33        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 6         | 18.18%  |
| 0x806ea    | 3         | 9.09%   |
| 0x306a9    | 3         | 9.09%   |
| 0x806e9    | 2         | 6.06%   |
| 0x806c1    | 2         | 6.06%   |
| 0x406e3    | 2         | 6.06%   |
| 0x206a7    | 2         | 6.06%   |
| 0x20652    | 2         | 6.06%   |
| 0x1067a    | 2         | 6.06%   |
| 0x806eb    | 1         | 3.03%   |
| 0x706e5    | 1         | 3.03%   |
| 0x706a8    | 1         | 3.03%   |
| 0x6fd      | 1         | 3.03%   |
| 0x406c3    | 1         | 3.03%   |
| 0x30678    | 1         | 3.03%   |
| 0x0a50000c | 1         | 3.03%   |
| 0x08101007 | 1         | 3.03%   |
| 0x010000c8 | 1         | 3.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 8         | 24.24%  |
| Skylake       | 3         | 9.09%   |
| SandyBridge   | 3         | 9.09%   |
| IvyBridge     | 3         | 9.09%   |
| Westmere      | 2         | 6.06%   |
| TigerLake     | 2         | 6.06%   |
| Silvermont    | 2         | 6.06%   |
| Penryn        | 2         | 6.06%   |
| Zen+          | 1         | 3.03%   |
| Zen 3         | 1         | 3.03%   |
| Zen           | 1         | 3.03%   |
| K10           | 1         | 3.03%   |
| IceLake       | 1         | 3.03%   |
| Goldmont plus | 1         | 3.03%   |
| Core          | 1         | 3.03%   |
| Unknown       | 1         | 3.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 28        | 66.67%  |
| Nvidia | 9         | 21.43%  |
| AMD    | 5         | 11.9%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 4         | 9.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 6.98%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 6.98%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 6.98%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 4.65%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 2         | 4.65%   |
| Intel HD Graphics 620                                                                    | 2         | 4.65%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 4.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 4.65%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 4.65%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 2.33%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 2.33%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 2.33%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 2.33%   |
| Nvidia GA104GLM [RTX A3000 Mobile]                                                       | 1         | 2.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 2.33%   |
| Intel VGA compatible controller                                                          | 1         | 2.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 2.33%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 2.33%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 1         | 2.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 2.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 2.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 2.33%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 2.33%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 2.33%   |
| AMD Picasso                                                                              | 1         | 2.33%   |
| AMD Cezanne                                                                              | 1         | 2.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 20        | 60.61%  |
| Intel + Nvidia | 8         | 24.24%  |
| 1 x AMD        | 3         | 9.09%   |
| 2 x AMD        | 1         | 3.03%   |
| AMD + Nvidia   | 1         | 3.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 28        | 84.85%  |
| Proprietary | 5         | 15.15%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 81.82%  |
| 0.01-0.5   | 3         | 9.09%   |
| 0.51-1.0   | 2         | 6.06%   |
| 3.01-4.0   | 1         | 3.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 11        | 31.43%  |
| LG Display              | 5         | 14.29%  |
| BOE                     | 5         | 14.29%  |
| Apple                   | 4         | 11.43%  |
| Samsung Electronics     | 3         | 8.57%   |
| AU Optronics            | 3         | 8.57%   |
| Sharp                   | 1         | 2.86%   |
| Lenovo                  | 1         | 2.86%   |
| Goldstar                | 1         | 2.86%   |
| Chi Mei Optoelectronics | 1         | 2.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                     | 2         | 5.71%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch     | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SDC4E42 1366x768 309x174mm 14.0-inch     | 1         | 2.86%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 598x336mm 27.0-inch        | 1         | 2.86%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch            | 1         | 2.86%   |
| LG Display LCD Monitor LGD06AD 2560x1600 286x179mm 13.3-inch             | 1         | 2.86%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch             | 1         | 2.86%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 1         | 2.86%   |
| LG Display LCD Monitor LGD022C 1366x768 294x166mm 13.3-inch              | 1         | 2.86%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 2.86%   |
| Goldstar MP59HT GSM5B44 1920x1080 480x270mm 21.7-inch                    | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15E0 1920x1080 344x193mm 15.5-inch         | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch         | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch         | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN1514 1920x1080 344x193mm 15.5-inch         | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch         | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN1477 1366x768 309x174mm 14.0-inch          | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN1338 1366x768 293x164mm 13.2-inch          | 1         | 2.86%   |
| Chi Mei Optoelectronics LCD Monitor CMO1711 1600x900 382x215mm 17.3-inch | 1         | 2.86%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                    | 1         | 2.86%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 1         | 2.86%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 1         | 2.86%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 1         | 2.86%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO413D 1920x1080 309x173mm 13.9-inch           | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO12D4 1280x800 216x135mm 10.0-inch            | 1         | 2.86%   |
| Apple Color LCD APP9CC7 1280x800 290x180mm 13.4-inch                     | 1         | 2.86%   |
| Apple Color LCD APP9CB7 1680x1050 331x207mm 15.4-inch                    | 1         | 2.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 13        | 39.39%  |
| 1920x1080 (FHD)    | 11        | 33.33%  |
| 1280x800 (WXGA)    | 3         | 9.09%   |
| 1440x900 (WXGA+)   | 2         | 6.06%   |
| 3840x2400          | 1         | 3.03%   |
| 2560x1600          | 1         | 3.03%   |
| 1680x1050 (WSXGA+) | 1         | 3.03%   |
| 1600x900 (HD+)     | 1         | 3.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 17        | 48.57%  |
| 13     | 9         | 25.71%  |
| 14     | 3         | 8.57%   |
| 17     | 2         | 5.71%   |
| 27     | 1         | 2.86%   |
| 21     | 1         | 2.86%   |
| 12     | 1         | 2.86%   |
| 10     | 1         | 2.86%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 24        | 68.57%  |
| 201-300     | 6         | 17.14%  |
| 351-400     | 3         | 8.57%   |
| 501-600     | 1         | 2.86%   |
| 401-500     | 1         | 2.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 25        | 75.76%  |
| 16/10 | 7         | 21.21%  |
| 3/2   | 1         | 3.03%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 17        | 48.57%  |
| 81-90          | 9         | 25.71%  |
| 71-80          | 3         | 8.57%   |
| 61-70          | 1         | 2.86%   |
| 41-50          | 1         | 2.86%   |
| 301-350        | 1         | 2.86%   |
| 201-250        | 1         | 2.86%   |
| 131-140        | 1         | 2.86%   |
| 121-130        | 1         | 2.86%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 17        | 48.57%  |
| 121-160       | 14        | 40%     |
| 51-100        | 2         | 5.71%   |
| More than 240 | 1         | 2.86%   |
| 161-240       | 1         | 2.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 32        | 96.97%  |
| 3     | 1         | 3.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 21        | 38.18%  |
| Intel                 | 14        | 25.45%  |
| Broadcom              | 7         | 12.73%  |
| Qualcomm Atheros      | 6         | 10.91%  |
| MediaTek              | 2         | 3.64%   |
| Samsung Electronics   | 1         | 1.82%   |
| realme                | 1         | 1.82%   |
| Qualcomm              | 1         | 1.82%   |
| NEC Computers         | 1         | 1.82%   |
| DisplayLink           | 1         | 1.82%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 21.21%  |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 6.06%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 4         | 6.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 4.55%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 3.03%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 2         | 3.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 3.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 3.03%   |
| Intel Wireless 3165                                               | 2         | 3.03%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 3.03%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.52%   |
| realme SDM665-IDP _SN:18689828                                    | 1         | 1.52%   |
| Qualcomm Redmi Note 8T                                            | 1         | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.52%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1         | 1.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.52%   |
| NEC Computers WiMAX Mobile Router                                 | 1         | 1.52%   |
| MediaTek Titan                                                    | 1         | 1.52%   |
| MEDIATEK Network controller                                       | 1         | 1.52%   |
| Intel Wireless 8260                                               | 1         | 1.52%   |
| Intel Wireless 3160                                               | 1         | 1.52%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.52%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 1.52%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.52%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.52%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 1.52%   |
| Intel Centrino Advanced-N 6235                                    | 1         | 1.52%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 1         | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 1.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.52%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.52%   |
| DisplayLink USB3.0 5K Graphic Docking                             | 1         | 1.52%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.52%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.52%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 1         | 1.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 39.39%  |
| Realtek Semiconductor | 7         | 21.21%  |
| Qualcomm Atheros      | 6         | 18.18%  |
| Broadcom              | 6         | 18.18%  |
| MEDIATEK              | 1         | 3.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom BCM4331 802.11a/b/g/n                             | 4         | 12.12%  |
| Realtek RTL8723DE Wireless Network Adapter                 | 2         | 6.06%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 2         | 6.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 2         | 6.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 6.06%   |
| Intel Wireless 3165                                        | 2         | 6.06%   |
| Intel Wi-Fi 6 AX200                                        | 2         | 6.06%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter   | 1         | 3.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 3.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 3.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 3.03%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 1         | 3.03%   |
| MEDIATEK Network controller                                | 1         | 3.03%   |
| Intel Wireless 8260                                        | 1         | 3.03%   |
| Intel Wireless 3160                                        | 1         | 3.03%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 3.03%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 1         | 3.03%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1         | 3.03%   |
| Intel Centrino Wireless-N 2230                             | 1         | 3.03%   |
| Intel Centrino Advanced-N 6235                             | 1         | 3.03%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]              | 1         | 3.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 1         | 3.03%   |
| Broadcom BCM43142 802.11b/g/n                              | 1         | 3.03%   |
| Broadcom BCM4312 802.11b/g LP-PHY                          | 1         | 3.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 18        | 56.25%  |
| Broadcom              | 5         | 15.63%  |
| Intel                 | 3         | 9.38%   |
| Samsung Electronics   | 1         | 3.13%   |
| realme                | 1         | 3.13%   |
| Qualcomm Atheros      | 1         | 3.13%   |
| Qualcomm              | 1         | 3.13%   |
| MediaTek              | 1         | 3.13%   |
| DisplayLink           | 1         | 3.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 43.75%  |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 12.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 9.38%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 3.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 3.13%   |
| realme SDM665-IDP _SN:18689828                                    | 1         | 3.13%   |
| Qualcomm Redmi Note 8T                                            | 1         | 3.13%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 3.13%   |
| MediaTek Titan                                                    | 1         | 3.13%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 3.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 3.13%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 3.13%   |
| DisplayLink USB3.0 5K Graphic Docking                             | 1         | 3.13%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 3.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 32        | 53.33%  |
| Ethernet | 27        | 45%     |
| Unknown  | 1         | 1.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 28        | 53.85%  |
| Ethernet | 24        | 46.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 25        | 75.76%  |
| 1     | 8         | 24.24%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 26        | 78.79%  |
| Yes  | 7         | 21.21%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 44.83%  |
| Realtek Semiconductor           | 5         | 17.24%  |
| Lite-On Technology              | 4         | 13.79%  |
| Apple                           | 4         | 13.79%  |
| Qualcomm Atheros Communications | 1         | 3.45%   |
| Foxconn / Hon Hai               | 1         | 3.45%   |
| Broadcom                        | 1         | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                           | 8         | 27.59%  |
| Realtek  Bluetooth 4.2 Adapter                   | 3         | 10.34%  |
| Realtek Bluetooth Radio                          | 2         | 6.9%    |
| Intel Centrino Bluetooth Wireless Transceiver    | 2         | 6.9%    |
| Apple Bluetooth USB Host Controller              | 2         | 6.9%    |
| Apple Bluetooth Host Controller                  | 2         | 6.9%    |
| Qualcomm Atheros  Bluetooth Device               | 1         | 3.45%   |
| Lite-On Wireless_Device                          | 1         | 3.45%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 1         | 3.45%   |
| Lite-On Qualcomm Atheros Bluetooth               | 1         | 3.45%   |
| Lite-On Bluetooth Device                         | 1         | 3.45%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 3.45%   |
| Intel Bluetooth wireless interface               | 1         | 3.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 1         | 3.45%   |
| Foxconn / Hon Hai Bluetooth Device               | 1         | 3.45%   |
| Broadcom BCM43142A0 Bluetooth 4.0                | 1         | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 29        | 70.73%  |
| Nvidia | 6         | 14.63%  |
| AMD    | 5         | 12.2%   |
| TEAC   | 1         | 2.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 20.45%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 6.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 6.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 6.82%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 3         | 6.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 4.55%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 4.55%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 4.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 4.55%   |
| TEAC TASCAM iXR                                                                                   | 1         | 2.27%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 2.27%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 2.27%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 2.27%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 2.27%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 2.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 2.27%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 2.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 2.27%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 2.27%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 2.27%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 2.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 2.27%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 2.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 5         | 27.78%  |
| Micron Technology   | 4         | 22.22%  |
| SK Hynix            | 2         | 11.11%  |
| Kingston            | 2         | 11.11%  |
| Crucial             | 2         | 11.11%  |
| Toshiba             | 1         | 5.56%   |
| Ramaxel Technology  | 1         | 5.56%   |
| Qimonda             | 1         | 5.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s        | 2         | 10.53%  |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s      | 2         | 10.53%  |
| Toshiba RAM 8HTF12864HDY-800G1 4GB SODIMM 1066MT/s            | 1         | 5.26%   |
| Toshiba RAM 64T128020EDL2.5C2 4GB SODIMM 1066MT/s             | 1         | 5.26%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                | 1         | 5.26%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s      | 1         | 5.26%   |
| Samsung RAM M4 70T5663EH3-CF7 2048MB SODIMM DDR2 2048MT/s     | 1         | 5.26%   |
| Ramaxel RAM RMSA3310NA86H9F-2666 4GB SODIMM DDR4 2667MT/s     | 1         | 5.26%   |
| Qimonda RAM 64T256020EDL2.5C2 2048MB SODIMM DDR2 2048MT/s     | 1         | 5.26%   |
| Micron RAM MT41K256M16LY 2GB SODIMM DDR3 1600MT/s             | 1         | 5.26%   |
| Micron RAM 4ATF51264HZ-2G6E3 4GB SODIMM DDR4 2667MT/s         | 1         | 5.26%   |
| Micron RAM 16JSF25664HZ-1G4F1 2GB SODIMM DDR3 1334MT/s        | 1         | 5.26%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16384MB SODIMM DDR4 3200MT/s     | 1         | 5.26%   |
| Kingston RAM 9905700-070.A01G 16GB SODIMM DDR4 2667MT/s       | 1         | 5.26%   |
| Kingston RAM 9905700-026.A00G 8GB SODIMM DDR4 2667MT/s        | 1         | 5.26%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s    | 1         | 5.26%   |
| Crucial RAM CT16G4SFD824A.C16FDD 16384MB SODIMM DDR4 2400MT/s | 1         | 5.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR4  | 8         | 66.67%  |
| DDR3  | 2         | 16.67%  |
| SDRAM | 1         | 8.33%   |
| DDR2  | 1         | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 12        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 7         | 50%     |
| 16384 | 3         | 21.43%  |
| 2048  | 3         | 21.43%  |
| 8192  | 1         | 7.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 7         | 46.67%  |
| 3200  | 2         | 13.33%  |
| 2400  | 1         | 6.67%   |
| 2133  | 1         | 6.67%   |
| 2048  | 1         | 6.67%   |
| 1600  | 1         | 6.67%   |
| 1334  | 1         | 6.67%   |
| 1066  | 1         | 6.67%   |

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
| Chicony Electronics                    | 6         | 20.69%  |
| Apple                                  | 5         | 17.24%  |
| Quanta                                 | 4         | 13.79%  |
| Cheng Uei Precision Industry (Foxlink) | 3         | 10.34%  |
| Suyin                                  | 2         | 6.9%    |
| Luxvisions Innotech Limited            | 2         | 6.9%    |
| webcam                                 | 1         | 3.45%   |
| Syntek                                 | 1         | 3.45%   |
| Sunplus Innovation Technology          | 1         | 3.45%   |
| Realtek Semiconductor                  | 1         | 3.45%   |
| Primax Electronics                     | 1         | 3.45%   |
| Importek                               | 1         | 3.45%   |
| Acer                                   | 1         | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Apple FaceTime HD Camera                                        | 4         | 13.79%  |
| Suyin Acer/HP Integrated Webcam [CN0314]                        | 2         | 6.9%    |
| Quanta HP TrueVision HD Camera                                  | 2         | 6.9%    |
| Chicony HD WebCam                                               | 2         | 6.9%    |
| webcam webcam                                                   | 1         | 3.45%   |
| Syntek EasyCamera                                               | 1         | 3.45%   |
| Sunplus Laptop_Integrated_Webcam_1.3M                           | 1         | 3.45%   |
| Realtek HD WebCam                                               | 1         | 3.45%   |
| Quanta HP Webcam                                                | 1         | 3.45%   |
| Quanta HD User Facing                                           | 1         | 3.45%   |
| Primax Villem                                                   | 1         | 3.45%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 1         | 3.45%   |
| Luxvisions Innotech Limited HP HD Camera                        | 1         | 3.45%   |
| Importek Webcam HD                                              | 1         | 3.45%   |
| Chicony HP Webcam                                               | 1         | 3.45%   |
| Chicony HP Integrated Webcam                                    | 1         | 3.45%   |
| Chicony HP HD Webcam [Fixed]                                    | 1         | 3.45%   |
| Chicony HD User Facing                                          | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera             | 1         | 3.45%   |
| Apple iPhone 5/5C/5S/6/SE                                       | 1         | 3.45%   |
| Acer Integrated Camera                                          | 1         | 3.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| LighTuning Technology | 3         | 60%     |
| Validity Sensors      | 1         | 20%     |
| Synaptics             | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| LighTuning EgisTec Touch Fingerprint Sensor | 3         | 60%     |
| Validity Sensors VFS495 Fingerprint Reader  | 1         | 20%     |
| Synaptics  WBDI                             | 1         | 20%     |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 22        | 66.67%  |
| 1     | 9         | 27.27%  |
| 2     | 2         | 6.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 5         | 35.71%  |
| Net/wireless          | 4         | 28.57%  |
| Graphics card         | 3         | 21.43%  |
| Sound                 | 1         | 7.14%   |
| Multimedia controller | 1         | 7.14%   |

