Trisquel - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for Trisquel.

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

Total: 19

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire XC-885 V:1.1         | [eebd657892](https://linux-hardware.org/?probe=eebd657892) | Jul 27, 2023 |
| Unknown       | Unknown                     | [c5824f9cae](https://linux-hardware.org/?probe=c5824f9cae) | Apr 25, 2023 |
| Apple         | Mac-F221BEC8                | [89a021b8f6](https://linux-hardware.org/?probe=89a021b8f6) | Dec 15, 2022 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [08a8ad598f](https://linux-hardware.org/?probe=08a8ad598f) | Sep 23, 2022 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [8e620e891f](https://linux-hardware.org/?probe=8e620e891f) | Sep 23, 2022 |
| Packard Be... | IMEDIA S1300                | [4b8f3feaa7](https://linux-hardware.org/?probe=4b8f3feaa7) | Aug 25, 2022 |
| Dell          | 0WMJ54 A01                  | [7682000c35](https://linux-hardware.org/?probe=7682000c35) | Jul 30, 2022 |
| Dell          | 0WMJ54 A01                  | [fc499e7600](https://linux-hardware.org/?probe=fc499e7600) | Jul 27, 2022 |
| ASUSTek       | P8H61                       | [0145453c1a](https://linux-hardware.org/?probe=0145453c1a) | May 27, 2022 |
| Fujitsu Si... | D2840-A1 S26361-D2840-A1    | [a9d7621b8d](https://linux-hardware.org/?probe=a9d7621b8d) | May 26, 2022 |
| MSI           | Z97 GAMING 5                | [92fd051a13](https://linux-hardware.org/?probe=92fd051a13) | May 15, 2022 |
| HP            | 8299                        | [7a54bfae05](https://linux-hardware.org/?probe=7a54bfae05) | Apr 28, 2022 |
| MSI           | Z97 GAMING 5                | [f41f324f01](https://linux-hardware.org/?probe=f41f324f01) | Apr 25, 2022 |
| ASUSTek       | A55BM-PLUS                  | [53753f59d3](https://linux-hardware.org/?probe=53753f59d3) | Feb 13, 2022 |
| Dell          | 0M859N A00                  | [89cf2685e2](https://linux-hardware.org/?probe=89cf2685e2) | Nov 01, 2021 |
| Gigabyte      | M68MT-D3P                   | [49fde2499f](https://linux-hardware.org/?probe=49fde2499f) | Jul 18, 2020 |
| Gigabyte      | M68MT-D3P                   | [5ea27e2813](https://linux-hardware.org/?probe=5ea27e2813) | Jul 18, 2020 |
| ECS           | H61H2-M2                    | [add4f52268](https://linux-hardware.org/?probe=add4f52268) | Mar 06, 2019 |
| ECS           | H61H2-M2                    | [f9376ff405](https://linux-hardware.org/?probe=f9376ff405) | May 03, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| Trisquel 10.0.1 | 8        | 61.54%  |
| Trisquel 11.0   | 2        | 15.38%  |
| Trisquel 9.0    | 1        | 7.69%   |
| Trisquel 8.0    | 1        | 7.69%   |
| Trisquel 10.0   | 1        | 7.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Trisquel | 13       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Desktops | Percent |
|--------------------|----------|---------|
| 5.4.0-113-generic  | 2        | 14.29%  |
| 5.4.0-109-generic  | 2        | 14.29%  |
| 5.4.0-96-generic   | 1        | 7.14%   |
| 5.4.0-135-generic  | 1        | 7.14%   |
| 5.4.0-126-generic  | 1        | 7.14%   |
| 5.4.0-125-generic  | 1        | 7.14%   |
| 5.4.0-122-generic  | 1        | 7.14%   |
| 5.4.0-110-generic  | 1        | 7.14%   |
| 5.15.0-78-generic  | 1        | 7.14%   |
| 5.10.177-gnu1      | 1        | 7.14%   |
| 4.4.0-119-generic  | 1        | 7.14%   |
| 4.15.0-108-generic | 1        | 7.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.0    | 9        | 69.23%  |
| 5.15.0   | 1        | 7.69%   |
| 5.10.177 | 1        | 7.69%   |
| 4.4.0    | 1        | 7.69%   |
| 4.15.0   | 1        | 7.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 9        | 69.23%  |
| 5.15    | 1        | 7.69%   |
| 5.10    | 1        | 7.69%   |
| 4.4     | 1        | 7.69%   |
| 4.15    | 1        | 7.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 12       | 92.31%  |
| armv7l | 1        | 7.69%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| MATE    | 11       | 84.62%  |
| default | 1        | 7.69%   |
| Unknown | 1        | 7.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 12       | 92.31%  |
| Unknown | 1        | 7.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 10       | 76.92%  |
| Unknown | 2        | 15.38%  |
| TDM     | 1        | 7.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| fr_FR   | 4        | 30.77%  |
| en_US   | 4        | 30.77%  |
| ru_RU   | 2        | 15.38%  |
| en_CA   | 1        | 7.69%   |
| C       | 1        | 7.69%   |
| Unknown | 1        | 7.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 7        | 53.85%  |
| BIOS | 6        | 46.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 12       | 92.31%  |
| Unknown | 1        | 7.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 11       | 84.62%  |
| MBR     | 1        | 7.69%   |
| Unknown | 1        | 7.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 78.57%  |
| Yes       | 3        | 21.43%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 76.92%  |
| Yes       | 3        | 23.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 2        | 15.38%  |
| Packard Bell        | 1        | 7.69%   |
| MSI                 | 1        | 7.69%   |
| Huanan              | 1        | 7.69%   |
| Hewlett-Packard     | 1        | 7.69%   |
| Gigabyte Technology | 1        | 7.69%   |
| Fujitsu Siemens     | 1        | 7.69%   |
| ECS                 | 1        | 7.69%   |
| Dell                | 1        | 7.69%   |
| Apple               | 1        | 7.69%   |
| Acer                | 1        | 7.69%   |
| Unknown             | 1        | 7.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                  | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Packard Bell IMEDIA S1300                                             | 1        | 7.69%   |
| MSI MS-7917                                                           | 1        | 7.69%   |
| Huanan X79 INTEL (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V2.49P | 1        | 7.69%   |
| HP EliteDesk 800 G3 SFF                                               | 1        | 7.69%   |
| Gigabyte M68MT-D3P                                                    | 1        | 7.69%   |
| Fujitsu Siemens ESPRIMO EDITION P2540                                 | 1        | 7.69%   |
| ECS H61H2-M2                                                          | 1        | 7.69%   |
| Dell OptiPlex 3020                                                    | 1        | 7.69%   |
| ASUS P8H61                                                            | 1        | 7.69%   |
| ASUS A55BM-PLUS                                                       | 1        | 7.69%   |
| Apple MacPro5,1                                                       | 1        | 7.69%   |
| Acer Aspire XC-885                                                    | 1        | 7.69%   |
| Unknown                                                               | 1        | 7.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Packard Bell IMEDIA     | 1        | 7.69%   |
| MSI MS-7917             | 1        | 7.69%   |
| Huanan X79              | 1        | 7.69%   |
| HP EliteDesk            | 1        | 7.69%   |
| Gigabyte M68MT-D3P      | 1        | 7.69%   |
| Fujitsu Siemens ESPRIMO | 1        | 7.69%   |
| ECS H61H2-M2            | 1        | 7.69%   |
| Dell OptiPlex           | 1        | 7.69%   |
| ASUS P8H61              | 1        | 7.69%   |
| ASUS A55BM-PLUS         | 1        | 7.69%   |
| Apple MacPro5           | 1        | 7.69%   |
| Acer Aspire             | 1        | 7.69%   |
| Unknown                 | 1        | 7.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2010    | 3        | 23.08%  |
| 2018    | 2        | 15.38%  |
| 2014    | 2        | 15.38%  |
| 2011    | 2        | 15.38%  |
| 2017    | 1        | 7.69%   |
| 2013    | 1        | 7.69%   |
| 2008    | 1        | 7.69%   |
| Unknown | 1        | 7.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 13       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 13       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 13       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 8.01-16.0  | 5        | 38.46%  |
| 16.01-24.0 | 3        | 23.08%  |
| 32.01-64.0 | 2        | 15.38%  |
| 4.01-8.0   | 1        | 7.69%   |
| 3.01-4.0   | 1        | 7.69%   |
| 0.51-1.0   | 1        | 7.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 6        | 42.86%  |
| 2.01-3.0 | 3        | 21.43%  |
| 0.01-0.5 | 2        | 14.29%  |
| 4.01-8.0 | 1        | 7.14%   |
| 3.01-4.0 | 1        | 7.14%   |
| 0.51-1.0 | 1        | 7.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 10       | 76.92%  |
| 2      | 3        | 23.08%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 9        | 69.23%  |
| No        | 4        | 30.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 13       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 8        | 57.14%  |
| Yes       | 6        | 42.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 92.31%  |
| Yes       | 1        | 7.69%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| France  | 4        | 30.77%  |
| USA     | 3        | 23.08%  |
| Russia  | 2        | 15.38%  |
| Ukraine | 1        | 7.69%   |
| Spain   | 1        | 7.69%   |
| China   | 1        | 7.69%   |
| Canada  | 1        | 7.69%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Corbeil-Essonnes         | 3        | 23.08%  |
| Lincoln                  | 2        | 15.38%  |
| Vienne-le-Chateau        | 1        | 7.69%   |
| Rivne                    | 1        | 7.69%   |
| Petropavlovsk-Kamchatsky | 1        | 7.69%   |
| Oviedo                   | 1        | 7.69%   |
| Ottawa                   | 1        | 7.69%   |
| Omaha                    | 1        | 7.69%   |
| Moscow                   | 1        | 7.69%   |
| Guangzhou                | 1        | 7.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 6      | 33.33%  |
| Samsung Electronics | 2        | 2      | 13.33%  |
| WDC                 | 1        | 1      | 6.67%   |
| Unknown             | 1        | 1      | 6.67%   |
| Toshiba             | 1        | 1      | 6.67%   |
| Silicon Motion      | 1        | 2      | 6.67%   |
| NFHK                | 1        | 1      | 6.67%   |
| Kingston            | 1        | 1      | 6.67%   |
| China               | 1        | 1      | 6.67%   |
| Apacer              | 1        | 1      | 6.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 2        | 12.5%   |
| Seagate ST1000DM010-2EP102 1TB   | 2        | 12.5%   |
| WDC WD3200AAKX-221CA1 320GB      | 1        | 6.25%   |
| Unknown SA32G  32GB              | 1        | 6.25%   |
| Toshiba DT01ACA100 1TB           | 1        | 6.25%   |
| Silicon Motion MS10 1TB          | 1        | 6.25%   |
| Seagate ST31000524AS 1TB         | 1        | 6.25%   |
| Seagate ST1000DM003-9YN162 1TB   | 1        | 6.25%   |
| Samsung SSD 860 EVO 500GB        | 1        | 6.25%   |
| Samsung MZVLW256HEHP-000H1 256GB | 1        | 6.25%   |
| NFHK USB 3.0 120GB               | 1        | 6.25%   |
| Kingston SA400S37240G 240GB SSD  | 1        | 6.25%   |
| China SSD 512GB                  | 1        | 6.25%   |
| Apacer AS340 480GB SSD           | 1        | 6.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 5        | 6      | 71.43%  |
| WDC     | 1        | 1      | 14.29%  |
| Toshiba | 1        | 1      | 14.29%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 1      | 25%     |
| Kingston            | 1        | 1      | 25%     |
| China               | 1        | 1      | 25%     |
| Apacer              | 1        | 1      | 25%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 7        | 8      | 46.67%  |
| SSD     | 4        | 4      | 26.67%  |
| NVMe    | 2        | 3      | 13.33%  |
| MMC     | 1        | 1      | 6.67%   |
| Unknown | 1        | 1      | 6.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 10       | 12     | 71.43%  |
| NVMe | 2        | 3      | 14.29%  |
| SAS  | 1        | 1      | 7.14%   |
| MMC  | 1        | 1      | 7.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.51-1.0   | 6        | 6      | 50%     |
| 0.01-0.5   | 6        | 6      | 50%     |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 501-1000   | 4        | 30.77%  |
| 251-500    | 3        | 23.08%  |
| 101-250    | 3        | 23.08%  |
| 2001-3000  | 1        | 7.69%   |
| 1-20       | 1        | 7.69%   |
| 51-100     | 1        | 7.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 8        | 57.14%  |
| 21-50    | 4        | 28.57%  |
| 501-1000 | 1        | 7.14%   |
| 51-100   | 1        | 7.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB | 2        | 2      | 100%    |

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
| Works    | 10       | 11     | 71.43%  |
| Detected | 2        | 4      | 14.29%  |
| Malfunc  | 2        | 2      | 14.29%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 9        | 64.29%  |
| Nvidia              | 2        | 14.29%  |
| Silicon Motion      | 1        | 7.14%   |
| Samsung Electronics | 1        | 7.14%   |
| AMD                 | 1        | 7.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Nvidia MCP61 SATA Controller                                                            | 2        | 11.76%  |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 11.76%  |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 11.76%  |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 1        | 5.88%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 5.88%   |
| Nvidia MCP61 IDE                                                                        | 1        | 5.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 5.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 5.88%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 5.88%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 5.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1        | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 5.88%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 5.88%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 1        | 5.88%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 7        | 50%     |
| IDE  | 5        | 35.71%  |
| NVMe | 2        | 14.29%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 9        | 69.23%  |
| AMD    | 3        | 23.08%  |
| ARM    | 1        | 7.69%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 15.38%  |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1        | 7.69%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 7.69%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 7.69%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 7.69%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 7.69%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 7.69%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1        | 7.69%   |
| ARM Allwinner sun8i Family Processor        | 1        | 7.69%   |
| AMD Phenom II X4 955 Processor              | 1        | 7.69%   |
| AMD Athlon II X2 215 Processor              | 1        | 7.69%   |
| AMD A4-5300 APU with Radeon HD Graphics     | 1        | 7.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 3        | 23.08%  |
| Intel Xeon              | 2        | 15.38%  |
| Intel Core i3           | 2        | 15.38%  |
| Intel Pentium Dual-Core | 1        | 7.69%   |
| Intel Core i7           | 1        | 7.69%   |
| ARM Allwinner           | 1        | 7.69%   |
| AMD Phenom II X4        | 1        | 7.69%   |
| AMD Athlon II X2        | 1        | 7.69%   |
| AMD A4                  | 1        | 7.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 7        | 53.85%  |
| 2      | 3        | 23.08%  |
| 8      | 2        | 15.38%  |
| 1      | 1        | 7.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 12       | 92.31%  |
| 2      | 1        | 7.69%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 8        | 61.54%  |
| 2      | 5        | 38.46%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 12       | 92.31%  |
| Unknown        | 1        | 7.69%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 2        | 15.38%  |
| 0x906eb    | 1        | 7.69%   |
| 0x906e9    | 1        | 7.69%   |
| 0x306a9    | 1        | 7.69%   |
| 0x206d7    | 1        | 7.69%   |
| 0x206c2    | 1        | 7.69%   |
| 0x206a7    | 1        | 7.69%   |
| 0x1067a    | 1        | 7.69%   |
| 0x06001119 | 1        | 7.69%   |
| 0x010000c8 | 1        | 7.69%   |
| 0x010000b7 | 1        | 7.69%   |
| Unknown    | 1        | 7.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| SandyBridge | 2        | 15.38%  |
| KabyLake    | 2        | 15.38%  |
| K10         | 2        | 15.38%  |
| Haswell     | 2        | 15.38%  |
| Westmere    | 1        | 7.69%   |
| Piledriver  | 1        | 7.69%   |
| Penryn      | 1        | 7.69%   |
| IvyBridge   | 1        | 7.69%   |
| Unknown     | 1        | 7.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 9        | 69.23%  |
| Intel  | 3        | 23.08%  |
| AMD    | 1        | 7.69%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GT218 [GeForce 210]                                                  | 2        | 15.38%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 15.38%  |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 7.69%   |
| Nvidia GP107GL [Quadro P600]                                                | 1        | 7.69%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 7.69%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 7.69%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 7.69%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 7.69%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1        | 7.69%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 7.69%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 1        | 7.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 8        | 61.54%  |
| 1 x Intel      | 2        | 15.38%  |
| Other          | 1        | 7.69%   |
| Intel + Nvidia | 1        | 7.69%   |
| 1 x AMD        | 1        | 7.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 11       | 84.62%  |
| Unknown | 2        | 15.38%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 4        | 30.77%  |
| 0.51-1.0   | 3        | 23.08%  |
| 0.01-0.5   | 3        | 23.08%  |
| 1.01-2.0   | 2        | 15.38%  |
| 7.01-8.0   | 1        | 7.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Iiyama               | 3        | 23.08%  |
| Acer                 | 3        | 23.08%  |
| Samsung Electronics  | 2        | 15.38%  |
| Dell                 | 2        | 15.38%  |
| Plain Tree Systems   | 1        | 7.69%   |
| Philips              | 1        | 7.69%   |
| Ancor Communications | 1        | 7.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Iiyama PLE2283H IVM562E 1920x1080 477x268mm 21.5-inch                 | 3        | 23.08%  |
| Samsung Electronics SyncMaster SAM0216 1280x1024 338x270mm 17.0-inch  | 1        | 7.69%   |
| Samsung Electronics SMC27A550U SAM07F6 1920x1080 598x336mm 27.0-inch  | 1        | 7.69%   |
| Plain Tree Systems Monitor PTS076D 1280x1024 376x301mm 19.0-inch      | 1        | 7.69%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1        | 7.69%   |
| Dell E151FPp DEL7006 1024x768 300x230mm 14.9-inch                     | 1        | 7.69%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                       | 1        | 7.69%   |
| Ancor Communications ASUS VS229 ACI22D3 1920x1080 475x267mm 21.5-inch | 1        | 7.69%   |
| Acer KG251Q ACR0591 1920x1080 544x303mm 24.5-inch                     | 1        | 7.69%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                     | 1        | 7.69%   |
| Acer H236HL ACR0318 1920x1080 509x286mm 23.0-inch                     | 1        | 7.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 9        | 75%     |
| 1440x900 (WXGA+) | 1        | 8.33%   |
| 1280x1024 (SXGA) | 1        | 8.33%   |
| 1024x768 (XGA)   | 1        | 8.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 23     | 5        | 38.46%  |
| 24     | 2        | 15.38%  |
| 19     | 2        | 15.38%  |
| 27     | 1        | 7.69%   |
| 21     | 1        | 7.69%   |
| 17     | 1        | 7.69%   |
| 15     | 1        | 7.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 8        | 66.67%  |
| 401-500     | 2        | 16.67%  |
| 351-400     | 1        | 8.33%   |
| 301-350     | 1        | 8.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 9        | 75%     |
| 5/4   | 1        | 8.33%   |
| 4/3   | 1        | 8.33%   |
| 16/10 | 1        | 8.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 7        | 53.85%  |
| 151-200        | 2        | 15.38%  |
| 301-350        | 1        | 7.69%   |
| 251-300        | 1        | 7.69%   |
| 141-150        | 1        | 7.69%   |
| 101-110        | 1        | 7.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 10       | 90.91%  |
| 101-120 | 1        | 9.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 12       | 85.71%  |
| 3     | 1        | 7.14%   |
| 0     | 1        | 7.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 36.84%  |
| Qualcomm Atheros      | 3        | 15.79%  |
| Ralink Technology     | 2        | 10.53%  |
| Nvidia                | 2        | 10.53%  |
| Intel                 | 2        | 10.53%  |
| Broadcom              | 2        | 10.53%  |
| Qualcomm              | 1        | 5.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 5        | 26.32%  |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 2        | 10.53%  |
| Nvidia MCP61 Ethernet                                               | 2        | 10.53%  |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1        | 5.26%   |
| Ralink MT7601U Wireless Adapter                                     | 1        | 5.26%   |
| Qualcomm Fairphone 4 5G                                             | 1        | 5.26%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 1        | 5.26%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 1        | 5.26%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg] | 1        | 5.26%   |
| Intel Ethernet Connection (5) I219-LM                               | 1        | 5.26%   |
| Intel 82574L Gigabit Network Connection                             | 1        | 5.26%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                     | 1        | 5.26%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller              | 1        | 5.26%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 2        | 33.33%  |
| Ralink Technology     | 2        | 33.33%  |
| Qualcomm Atheros      | 1        | 16.67%  |
| Broadcom              | 1        | 16.67%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 2        | 33.33%  |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1        | 16.67%  |
| Ralink MT7601U Wireless Adapter                                     | 1        | 16.67%  |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg] | 1        | 16.67%  |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller              | 1        | 16.67%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 5        | 38.46%  |
| Qualcomm Atheros      | 2        | 15.38%  |
| Nvidia                | 2        | 15.38%  |
| Intel                 | 2        | 15.38%  |
| Qualcomm              | 1        | 7.69%   |
| Broadcom              | 1        | 7.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5        | 38.46%  |
| Nvidia MCP61 Ethernet                                             | 2        | 15.38%  |
| Qualcomm Fairphone 4 5G                                           | 1        | 7.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 7.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 7.69%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 7.69%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 7.69%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1        | 7.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 13       | 68.42%  |
| WiFi     | 6        | 31.58%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 11       | 84.62%  |
| WiFi     | 2        | 15.38%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10       | 76.92%  |
| 3     | 1        | 7.69%   |
| 2     | 1        | 7.69%   |
| 0     | 1        | 7.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 10       | 76.92%  |
| Yes  | 3        | 23.08%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Apple  | 1        | 100%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Apple Built-in Bluetooth 2.0+EDR HCI | 1        | 100%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor        | Desktops | Percent |
|---------------|----------|---------|
| Intel         | 9        | 47.37%  |
| Nvidia        | 8        | 42.11%  |
| Creative Labs | 1        | 5.26%   |
| AMD           | 1        | 5.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Nvidia High Definition Audio Controller                                    | 3        | 13.64%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 13.64%  |
| Nvidia MCP61 High Definition Audio                                         | 2        | 9.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 9.09%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 4.55%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 4.55%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 4.55%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 4.55%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 4.55%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 4.55%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 4.55%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 4.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1        | 4.55%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 4.55%   |
| Creative Labs CA0110 [Sound Blaster X-Fi Xtreme Audio]                     | 1        | 4.55%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 1        | 4.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 3        | 23.08%  |
| Unknown             | 2        | 15.38%  |
| SK hynix            | 2        | 15.38%  |
| Micron Technology   | 2        | 15.38%  |
| PNY                 | 1        | 7.69%   |
| Kingston            | 1        | 7.69%   |
| GOODRAM             | 1        | 7.69%   |
| G.Skill             | 1        | 7.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                              | 1        | 7.69%   |
| Unknown RAM 3634543235363032304555322E3543322020 2048MB DIMM DDR2 800MT/s | 1        | 7.69%   |
| SK hynix RAM Module 1024MB DIMM DDR3 1066MT/s                             | 1        | 7.69%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s                      | 1        | 7.69%   |
| Samsung RAM Module 4096MB DIMM DDR4 2400MT/s                              | 1        | 7.69%   |
| Samsung RAM Module 4096MB DIMM DDR3 1066MT/s                              | 1        | 7.69%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s                       | 1        | 7.69%   |
| PNY RAM Module 4096MB DIMM DDR3 1066MT/s                                  | 1        | 7.69%   |
| Micron RAM Module 2048MB DIMM DDR3 1066MT/s                               | 1        | 7.69%   |
| Micron RAM 36JSF1G72PZ-1 8192MB DIMM DDR3 1866MT/s                        | 1        | 7.69%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s                     | 1        | 7.69%   |
| GOODRAM RAM GY1600D364L9/4G 4GB DIMM DDR3 1333MT/s                        | 1        | 7.69%   |
| G.Skill RAM F3-2400C11-8GXM 8GB DIMM DDR3 2400MT/s                        | 1        | 7.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR3 | 8        | 80%     |
| DDR4 | 1        | 10%     |
| DDR2 | 1        | 10%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 10       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 4096 | 7        | 58.33%  |
| 8192 | 2        | 16.67%  |
| 2048 | 2        | 16.67%  |
| 1024 | 1        | 8.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 3        | 27.27%  |
| 2400  | 2        | 18.18%  |
| 1066  | 2        | 18.18%  |
| 2133  | 1        | 9.09%   |
| 1866  | 1        | 9.09%   |
| 1333  | 1        | 9.09%   |
| 800   | 1        | 9.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| HP Deskjet 3510 series | 1        | 100%    |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Sunplus Innovation Technology | 1        | 50%     |
| Logitech                      | 1        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Sunplus ZET USB WEBCAM  | 1        | 50%     |
| Logitech C505 HD Webcam | 1        | 50%     |

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
| 0     | 11       | 78.57%  |
| 1     | 3        | 21.43%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Net/wireless  | 1        | 50%     |
| Graphics card | 1        | 50%     |

