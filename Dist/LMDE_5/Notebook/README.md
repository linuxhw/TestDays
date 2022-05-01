LMDE 5 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

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

Total: 40

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Presario C500 (GF581UA#A... | [0e01914db4](https://linux-hardware.org/?probe=0e01914db4) | Apr 30, 2022 |
| HP            | EliteBook 840 G1            | [53bceed0aa](https://linux-hardware.org/?probe=53bceed0aa) | Apr 29, 2022 |
| Acer          | AOD270                      | [d0fae524f9](https://linux-hardware.org/?probe=d0fae524f9) | Apr 29, 2022 |
| Acer          | AOD270                      | [44d897bc15](https://linux-hardware.org/?probe=44d897bc15) | Apr 29, 2022 |
| Acer          | Aspire E5-553G              | [00a648bda6](https://linux-hardware.org/?probe=00a648bda6) | Apr 28, 2022 |
| Acer          | Aspire E5-553G              | [4646f6cd23](https://linux-hardware.org/?probe=4646f6cd23) | Apr 28, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [ff8e46a260](https://linux-hardware.org/?probe=ff8e46a260) | Apr 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [0a6534997e](https://linux-hardware.org/?probe=0a6534997e) | Apr 27, 2022 |
| Apple         | MacBookPro14,1              | [ce4f3d8ec8](https://linux-hardware.org/?probe=ce4f3d8ec8) | Apr 24, 2022 |
| Dixonsxp      | Unknown                     | [65e40dacf4](https://linux-hardware.org/?probe=65e40dacf4) | Apr 20, 2022 |
| Toshiba       | Satellite L455              | [7f0bad47af](https://linux-hardware.org/?probe=7f0bad47af) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | [3a0c54144d](https://linux-hardware.org/?probe=3a0c54144d) | Apr 19, 2022 |
| Dell          | 0X574R                      | [6da5c2339f](https://linux-hardware.org/?probe=6da5c2339f) | Apr 18, 2022 |
| HP            | 14                          | [71f296bd93](https://linux-hardware.org/?probe=71f296bd93) | Apr 17, 2022 |
| Dell          | Latitude 3410               | [78396d572c](https://linux-hardware.org/?probe=78396d572c) | Apr 15, 2022 |
| ASUSTek       | N61Jv                       | [959c5f2238](https://linux-hardware.org/?probe=959c5f2238) | Apr 14, 2022 |
| Acer          | AOA110                      | [cba10fc182](https://linux-hardware.org/?probe=cba10fc182) | Apr 13, 2022 |
| Howard Com... | R7X                         | [e0f3701b1b](https://linux-hardware.org/?probe=e0f3701b1b) | Apr 12, 2022 |
| Howard Com... | R7X                         | [5885bbaa90](https://linux-hardware.org/?probe=5885bbaa90) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [4d5998459b](https://linux-hardware.org/?probe=4d5998459b) | Apr 09, 2022 |
| HP            | Presario C500 (RY512EA#A... | [4ef049d490](https://linux-hardware.org/?probe=4ef049d490) | Apr 09, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | [613d6e7d3c](https://linux-hardware.org/?probe=613d6e7d3c) | Apr 07, 2022 |
| Dell          | Latitude 5511               | [2cb0a3e451](https://linux-hardware.org/?probe=2cb0a3e451) | Apr 06, 2022 |
| Dell          | Precision 7520              | [7404842400](https://linux-hardware.org/?probe=7404842400) | Apr 05, 2022 |
| LincPlus      | LINNCPLUS P1                | [22406313dc](https://linux-hardware.org/?probe=22406313dc) | Apr 02, 2022 |
| Toshiba       | Satellite L455              | [699e7d272d](https://linux-hardware.org/?probe=699e7d272d) | Apr 02, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [387b77f172](https://linux-hardware.org/?probe=387b77f172) | Apr 01, 2022 |
| HP            | ProBook 6570b               | [0609df27fa](https://linux-hardware.org/?probe=0609df27fa) | Mar 31, 2022 |
| Packard Be... | DOT S                       | [85e7386152](https://linux-hardware.org/?probe=85e7386152) | Mar 28, 2022 |
| Packard Be... | DOT S                       | [edef12b9d5](https://linux-hardware.org/?probe=edef12b9d5) | Mar 28, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [b2e70b8251](https://linux-hardware.org/?probe=b2e70b8251) | Mar 28, 2022 |
| Toshiba       | Satellite L455              | [9213736f1c](https://linux-hardware.org/?probe=9213736f1c) | Mar 27, 2022 |
| Dell          | Latitude E6400              | [01815a09bb](https://linux-hardware.org/?probe=01815a09bb) | Mar 27, 2022 |
| Toshiba       | Satellite L455              | [90334cf68d](https://linux-hardware.org/?probe=90334cf68d) | Mar 26, 2022 |
| Dell          | Precision M4400             | [5172327d82](https://linux-hardware.org/?probe=5172327d82) | Mar 25, 2022 |
| Medion        | E6220                       | [e739ef27a1](https://linux-hardware.org/?probe=e739ef27a1) | Mar 24, 2022 |
| Acer          | Aspire 7745G                | [3f4c13ee47](https://linux-hardware.org/?probe=3f4c13ee47) | Mar 23, 2022 |
| HP            | 255 G7 Notebook PC          | [f8561c65dc](https://linux-hardware.org/?probe=f8561c65dc) | Mar 21, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 5.10.0-13-amd64      | 13        | 44.83%  |
| 5.10.0-12-amd64      | 10        | 34.48%  |
| 5.10.0-13-686        | 4         | 13.79%  |
| 5.16.0-0.bpo.3-amd64 | 1         | 3.45%   |
| 5.15.0-0.bpo.3-amd64 | 1         | 3.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 26        | 92.86%  |
| 5.16.0  | 1         | 3.57%   |
| 5.15.0  | 1         | 3.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 26        | 92.86%  |
| 5.16    | 1         | 3.57%   |
| 5.15    | 1         | 3.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 24        | 85.71%  |
| i686   | 4         | 14.29%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| X-Cinnamon | 27        | 96.43%  |
| Cinnamon   | 1         | 3.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 28        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 18        | 64.29%  |
| LightDM | 10        | 35.71%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 15        | 53.57%  |
| en_GB | 2         | 7.14%   |
| ru_RU | 1         | 3.57%   |
| pt_BR | 1         | 3.57%   |
| pl_PL | 1         | 3.57%   |
| nl_AW | 1         | 3.57%   |
| ko_KR | 1         | 3.57%   |
| it_IT | 1         | 3.57%   |
| fr_FR | 1         | 3.57%   |
| es_PE | 1         | 3.57%   |
| es_MX | 1         | 3.57%   |
| en_CA | 1         | 3.57%   |
| de_DE | 1         | 3.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 15        | 53.57%  |
| BIOS | 13        | 46.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 25        | 89.29%  |
| Overlay | 3         | 10.71%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 18        | 64.29%  |
| GPT     | 8         | 28.57%  |
| MBR     | 2         | 7.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 26        | 92.86%  |
| Yes       | 2         | 7.14%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 25        | 89.29%  |
| Yes       | 3         | 10.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Dell             | 8         | 28.57%  |
| Hewlett-Packard  | 7         | 25%     |
| Acer             | 4         | 14.29%  |
| Toshiba          | 1         | 3.57%   |
| Packard Bell     | 1         | 3.57%   |
| Medion           | 1         | 3.57%   |
| LincPlus         | 1         | 3.57%   |
| Lenovo           | 1         | 3.57%   |
| Howard Computers | 1         | 3.57%   |
| Dixonsxp         | 1         | 3.57%   |
| ASUSTek Computer | 1         | 3.57%   |
| Apple            | 1         | 3.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Dell Latitude E6400            | 2         | 7.14%   |
| Toshiba Satellite L455         | 1         | 3.57%   |
| Packard Bell DOT S             | 1         | 3.57%   |
| Medion E6220                   | 1         | 3.57%   |
| LincPlus LINNCPLUS P1          | 1         | 3.57%   |
| Lenovo IdeaPad 3 14ALC6 82KT   | 1         | 3.57%   |
| Howard Computers R7X           | 1         | 3.57%   |
| HP ProBook 6570b               | 1         | 3.57%   |
| HP ProBook 450 G8 Notebook PC  | 1         | 3.57%   |
| HP Presario C500 (GF581UA#ABA) | 1         | 3.57%   |
| HP Pavilion Laptop 15-eh1xxx   | 1         | 3.57%   |
| HP EliteBook 840 G1            | 1         | 3.57%   |
| HP 255 G7 Notebook PC          | 1         | 3.57%   |
| HP 14                          | 1         | 3.57%   |
| Dell Vostro 3500               | 1         | 3.57%   |
| Dell Precision M4400           | 1         | 3.57%   |
| Dell Precision 7520            | 1         | 3.57%   |
| Dell Latitude 5511             | 1         | 3.57%   |
| Dell Latitude 3410             | 1         | 3.57%   |
| Dell Inspiron 14 5410 2-in-1   | 1         | 3.57%   |
| ASUS N61Jv                     | 1         | 3.57%   |
| Apple MacBookPro14,1           | 1         | 3.57%   |
| Acer Aspire E5-553G            | 1         | 3.57%   |
| Acer Aspire 7745G              | 1         | 3.57%   |
| Acer AOD270                    | 1         | 3.57%   |
| Acer AOA110                    | 1         | 3.57%   |
| Unknown                        | 1         | 3.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Dell Latitude        | 4         | 14.29%  |
| HP ProBook           | 2         | 7.14%   |
| Dell Precision       | 2         | 7.14%   |
| Acer Aspire          | 2         | 7.14%   |
| Toshiba Satellite    | 1         | 3.57%   |
| Packard Bell DOT     | 1         | 3.57%   |
| Medion E6220         | 1         | 3.57%   |
| LincPlus LINNCPLUS   | 1         | 3.57%   |
| Lenovo IdeaPad       | 1         | 3.57%   |
| Howard Computers R7X | 1         | 3.57%   |
| HP Presario          | 1         | 3.57%   |
| HP Pavilion          | 1         | 3.57%   |
| HP EliteBook         | 1         | 3.57%   |
| HP 255               | 1         | 3.57%   |
| HP 14                | 1         | 3.57%   |
| Dell Vostro          | 1         | 3.57%   |
| Dell Inspiron        | 1         | 3.57%   |
| ASUS N61Jv           | 1         | 3.57%   |
| Apple MacBookPro14   | 1         | 3.57%   |
| Acer AOD270          | 1         | 3.57%   |
| Acer AOA110          | 1         | 3.57%   |
| Unknown              | 1         | 3.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 4         | 14.29%  |
| 2020 | 4         | 14.29%  |
| 2013 | 4         | 14.29%  |
| 2010 | 4         | 14.29%  |
| 2017 | 2         | 7.14%   |
| 2012 | 2         | 7.14%   |
| 2008 | 2         | 7.14%   |
| 2007 | 2         | 7.14%   |
| 2018 | 1         | 3.57%   |
| 2016 | 1         | 3.57%   |
| 2011 | 1         | 3.57%   |
| 2009 | 1         | 3.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 28        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 27        | 96.43%  |
| Enabled  | 1         | 3.57%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 28        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 11        | 39.29%  |
| 4.01-8.0   | 5         | 17.86%  |
| 8.01-16.0  | 4         | 14.29%  |
| 1.01-2.0   | 3         | 10.71%  |
| 2.01-3.0   | 2         | 7.14%   |
| 16.01-24.0 | 2         | 7.14%   |
| 32.01-64.0 | 1         | 3.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 13        | 44.83%  |
| 2.01-3.0 | 8         | 27.59%  |
| 0.51-1.0 | 4         | 13.79%  |
| 3.01-4.0 | 3         | 10.34%  |
| 4.01-8.0 | 1         | 3.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 22        | 78.57%  |
| 2      | 5         | 17.86%  |
| 4      | 1         | 3.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 18        | 64.29%  |
| Yes       | 10        | 35.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 82.14%  |
| No        | 5         | 17.86%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 96.43%  |
| No        | 1         | 3.57%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 16        | 57.14%  |
| No        | 12        | 42.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 8         | 28.57%  |
| UK          | 3         | 10.71%  |
| Germany     | 2         | 7.14%   |
| France      | 2         | 7.14%   |
| Canada      | 2         | 7.14%   |
| South Korea | 1         | 3.57%   |
| Russia      | 1         | 3.57%   |
| Romania     | 1         | 3.57%   |
| Poland      | 1         | 3.57%   |
| Peru        | 1         | 3.57%   |
| Mexico      | 1         | 3.57%   |
| Kenya       | 1         | 3.57%   |
| Italy       | 1         | 3.57%   |
| Brazil      | 1         | 3.57%   |
| Belgium     | 1         | 3.57%   |
| Austria     | 1         | 3.57%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Veurne         | 1         | 3.57%   |
| Vaslui         | 1         | 3.57%   |
| Uiwang         | 1         | 3.57%   |
| Tipton         | 1         | 3.57%   |
| Spearfish      | 1         | 3.57%   |
| Scarborough    | 1         | 3.57%   |
| Rochester      | 1         | 3.57%   |
| Nairobi        | 1         | 3.57%   |
| Murphy         | 1         | 3.57%   |
| Moscow         | 1         | 3.57%   |
| Mieuxce        | 1         | 3.57%   |
| Marrero        | 1         | 3.57%   |
| Mannheim       | 1         | 3.57%   |
| Limoges        | 1         | 3.57%   |
| Lima           | 1         | 3.57%   |
| Lebanon        | 1         | 3.57%   |
| Lawrenceville  | 1         | 3.57%   |
| Knurow         | 1         | 3.57%   |
| Hollister      | 1         | 3.57%   |
| Hallwang       | 1         | 3.57%   |
| Glasgow        | 1         | 3.57%   |
| Darlington     | 1         | 3.57%   |
| Ciudad Juárez | 1         | 3.57%   |
| Chicago        | 1         | 3.57%   |
| Brescia        | 1         | 3.57%   |
| Belém         | 1         | 3.57%   |
| Amhertsburg    | 1         | 3.57%   |
| Aachen         | 1         | 3.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 5         | 5      | 14.71%  |
| Seagate                        | 5         | 5      | 14.71%  |
| Samsung Electronics            | 4         | 4      | 11.76%  |
| Kingston                       | 2         | 2      | 5.88%   |
| Hitachi                        | 2         | 2      | 5.88%   |
| Unknown                        | 1         | 1      | 2.94%   |
| Toshiba                        | 1         | 1      | 2.94%   |
| Solid State Storage Technology | 1         | 1      | 2.94%   |
| SK Hynix                       | 1         | 1      | 2.94%   |
| SanDisk                        | 1         | 1      | 2.94%   |
| SABRENT                        | 1         | 1      | 2.94%   |
| Phison                         | 1         | 1      | 2.94%   |
| Oyen                           | 1         | 1      | 2.94%   |
| Micron/Crucial Technology      | 1         | 1      | 2.94%   |
| LITEON                         | 1         | 1      | 2.94%   |
| KingSpec                       | 1         | 1      | 2.94%   |
| Intel                          | 1         | 1      | 2.94%   |
| HGST                           | 1         | 1      | 2.94%   |
| China                          | 1         | 2      | 2.94%   |
| Apple                          | 1         | 2      | 2.94%   |
| Acer                           | 1         | 1      | 2.94%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB          | 2         | 5.71%   |
| WDC WDBNCE5000PNC 500GB SSD              | 1         | 2.86%   |
| WDC WD5000BPVX-00JC3T0 500GB             | 1         | 2.86%   |
| WDC WD3200BPVT-22JJ5T0 320GB             | 1         | 2.86%   |
| WDC WD30 EFRX-68EUZN0 3TB                | 1         | 2.86%   |
| WDC PC SN530 NVMe 256GB                  | 1         | 2.86%   |
| Unknown Biwin  64GB                      | 1         | 2.86%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 2.86%   |
| Solid State Storage NVMe SSD Drive 256GB | 1         | 2.86%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB  | 1         | 2.86%   |
| Seagate ST9160412ASG 160GB               | 1         | 2.86%   |
| Seagate ST320LM001 HN-M320MBB 320GB      | 1         | 2.86%   |
| Seagate ST2000LX001-1RG174 2TB           | 1         | 2.86%   |
| SanDisk SSD PLUS 480GB                   | 1         | 2.86%   |
| Samsung SSD 980 1TB                      | 1         | 2.86%   |
| Samsung SSD 970 EVO Plus 1TB             | 1         | 2.86%   |
| Samsung SSD 850 EVO 120GB                | 1         | 2.86%   |
| Samsung NVMe SSD Drive 256GB             | 1         | 2.86%   |
| SABRENT Disk 1TB                         | 1         | 2.86%   |
| Phison ES 512GB                          | 1         | 2.86%   |
| Oyen MiniPro E31 5TB                     | 1         | 2.86%   |
| Micron/Crucial NVMe SSD Drive 2TB        | 1         | 2.86%   |
| LITEON CV3-CE256-11 SATA 256GB SSD       | 1         | 2.86%   |
| Kingston SA400S37240G 240GB SSD          | 1         | 2.86%   |
| Kingston SA400M8240G 240GB SSD           | 1         | 2.86%   |
| KingSpec MT-128 128GB                    | 1         | 2.86%   |
| Intel SSDSCKKF256G8 SATA 256GB           | 1         | 2.86%   |
| Hitachi HTS547575A9E384 752GB            | 1         | 2.86%   |
| Hitachi HTS541680J9SA00 80GB             | 1         | 2.86%   |
| HGST HTS725050A7E630 500GB               | 1         | 2.86%   |
| China SATA SSD 256GB                     | 1         | 2.86%   |
| Apple NVMe SSD Drive 8KB                 | 1         | 2.86%   |
| Apple NVMe SSD Drive 121GB               | 1         | 2.86%   |
| Acer SSD SA100 480GB                     | 1         | 2.86%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 38.46%  |
| WDC     | 3         | 3      | 23.08%  |
| Hitachi | 2         | 2      | 15.38%  |
| Toshiba | 1         | 1      | 7.69%   |
| SABRENT | 1         | 1      | 7.69%   |
| HGST    | 1         | 1      | 7.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 2         | 2      | 20%     |
| WDC                 | 1         | 1      | 10%     |
| SanDisk             | 1         | 1      | 10%     |
| Samsung Electronics | 1         | 1      | 10%     |
| LITEON              | 1         | 1      | 10%     |
| KingSpec            | 1         | 1      | 10%     |
| Intel               | 1         | 1      | 10%     |
| China               | 1         | 2      | 10%     |
| Acer                | 1         | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 11        | 13     | 35.48%  |
| NVMe    | 9         | 10     | 29.03%  |
| SSD     | 9         | 11     | 29.03%  |
| MMC     | 1         | 1      | 3.23%   |
| Unknown | 1         | 1      | 3.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 20        | 22     | 64.52%  |
| NVMe | 9         | 10     | 29.03%  |
| SAS  | 1         | 3      | 3.23%   |
| MMC  | 1         | 1      | 3.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 17        | 19     | 77.27%  |
| 0.51-1.0   | 3         | 3      | 13.64%  |
| 2.01-3.0   | 1         | 1      | 4.55%   |
| 1.01-2.0   | 1         | 1      | 4.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 9         | 32.14%  |
| 101-250        | 6         | 21.43%  |
| 1-20           | 3         | 10.71%  |
| 501-1000       | 3         | 10.71%  |
| 51-100         | 3         | 10.71%  |
| 21-50          | 2         | 7.14%   |
| More than 3000 | 1         | 3.57%   |
| 1001-2000      | 1         | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 20        | 68.97%  |
| 21-50     | 5         | 17.24%  |
| 251-500   | 1         | 3.45%   |
| 2001-3000 | 1         | 3.45%   |
| 101-250   | 1         | 3.45%   |
| 51-100    | 1         | 3.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Phison ES 512GB                | 1         | 1      | 33.33%  |
| Intel SSDSCKKF256G8 SATA 256GB | 1         | 1      | 33.33%  |
| Hitachi HTS547575A9E384 752GB  | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Phison  | 1         | 1      | 33.33%  |
| Intel   | 1         | 1      | 33.33%  |
| Hitachi | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1         | 1      | 33.33%  |
| SSD  | 1         | 1      | 33.33%  |
| HDD  | 1         | 1      | 33.33%  |

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
| Detected | 19        | 24     | 61.29%  |
| Works    | 9         | 9      | 29.03%  |
| Malfunc  | 3         | 3      | 9.68%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 21        | 60%     |
| AMD                            | 5         | 14.29%  |
| Samsung Electronics            | 3         | 8.57%   |
| Solid State Storage Technology | 1         | 2.86%   |
| SK Hynix                       | 1         | 2.86%   |
| Sandisk                        | 1         | 2.86%   |
| Phison Electronics             | 1         | 2.86%   |
| Micron/Crucial Technology      | 1         | 2.86%   |
| Apple                          | 1         | 2.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 4         | 10.26%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 3         | 7.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                | 3         | 7.69%   |
| Samsung NVMe SSD Controller 980                                               | 2         | 5.13%   |
| Intel Volume Management Device NVMe RAID Controller                           | 2         | 5.13%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 2         | 5.13%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                | 2         | 5.13%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 2         | 5.13%   |
| Solid State Storage Non-Volatile memory controller                            | 1         | 2.56%   |
| SK Hynix BC511                                                                | 1         | 2.56%   |
| Sandisk Non-Volatile memory controller                                        | 1         | 2.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 1         | 2.56%   |
| Phison PS5013 E13 NVMe Controller                                             | 1         | 2.56%   |
| Micron/Crucial NVMe Controller                                                | 1         | 2.56%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                               | 1         | 2.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 2.56%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                              | 1         | 2.56%   |
| Intel Comet Lake SATA AHCI Controller                                         | 1         | 2.56%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 1         | 2.56%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                        | 1         | 2.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 1         | 2.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 1         | 2.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 1         | 2.56%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 1         | 2.56%   |
| Apple S3X NVMe Controller                                                     | 1         | 2.56%   |
| AMD IXP SB4x0 Serial ATA Controller                                           | 1         | 2.56%   |
| AMD IXP SB4x0 IDE Controller                                                  | 1         | 2.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 20        | 52.63%  |
| NVMe | 9         | 23.68%  |
| RAID | 5         | 13.16%  |
| IDE  | 4         | 10.53%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 23        | 82.14%  |
| AMD    | 5         | 17.86%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Atom CPU N2600 @ 1.60GHz                  | 2         | 7.14%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 2         | 7.14%   |
| Intel Pentium CPU P6000 @ 1.87GHz               | 1         | 3.57%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz              | 1         | 3.57%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz               | 1         | 3.57%   |
| Intel Core i5-7360U CPU @ 2.30GHz               | 1         | 3.57%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 1         | 3.57%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 1         | 3.57%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 1         | 3.57%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 1         | 3.57%   |
| Intel Core i3 CPU M 330 @ 2.13GHz               | 1         | 3.57%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz            | 1         | 3.57%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz            | 1         | 3.57%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz            | 1         | 3.57%   |
| Intel Core 2 Duo CPU E8235 @ 2.80GHz            | 1         | 3.57%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 1         | 3.57%   |
| Intel Celeron M CPU 520 @ 1.60GHz               | 1         | 3.57%   |
| Intel Celeron M CPU 440 @ 1.86GHz               | 1         | 3.57%   |
| Intel Celeron CPU N2815 @ 1.86GHz               | 1         | 3.57%   |
| Intel Atom CPU N270 @ 1.60GHz                   | 1         | 3.57%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz         | 1         | 3.57%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 1         | 3.57%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 1         | 3.57%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 1         | 3.57%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx   | 1         | 3.57%   |
| AMD A10-9600P RADEON R5, 10 COMPUTE CORES 4C+6G | 1         | 3.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 4         | 14.29%  |
| Intel Core 2 Duo | 4         | 14.29%  |
| Other            | 3         | 10.71%  |
| Intel Atom       | 3         | 10.71%  |
| Intel Core i7    | 2         | 7.14%   |
| Intel Core i3    | 2         | 7.14%   |
| Intel Celeron M  | 2         | 7.14%   |
| Intel Celeron    | 2         | 7.14%   |
| AMD Ryzen 7      | 2         | 7.14%   |
| Intel Pentium    | 1         | 3.57%   |
| AMD Ryzen 5      | 1         | 3.57%   |
| AMD Ryzen 3      | 1         | 3.57%   |
| AMD A10          | 1         | 3.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 16        | 57.14%  |
| 4      | 6         | 21.43%  |
| 1      | 3         | 10.71%  |
| 8      | 2         | 7.14%   |
| 6      | 1         | 3.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 28        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 19        | 67.86%  |
| 1      | 9         | 32.14%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 25        | 89.29%  |
| 32-bit         | 3         | 10.71%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 3         | 10.71%  |
| 0x30661    | 2         | 7.14%   |
| 0x20652    | 2         | 7.14%   |
| 0x1067a    | 2         | 7.14%   |
| 0x08608103 | 2         | 7.14%   |
| 0xa0652    | 1         | 3.57%   |
| 0x806ec    | 1         | 3.57%   |
| 0x806e9    | 1         | 3.57%   |
| 0x706a8    | 1         | 3.57%   |
| 0x6fd      | 1         | 3.57%   |
| 0x6f6      | 1         | 3.57%   |
| 0x6ec      | 1         | 3.57%   |
| 0x506e3    | 1         | 3.57%   |
| 0x40651    | 1         | 3.57%   |
| 0x306a9    | 1         | 3.57%   |
| 0x30673    | 1         | 3.57%   |
| 0x106e5    | 1         | 3.57%   |
| 0x106c2    | 1         | 3.57%   |
| 0x10676    | 1         | 3.57%   |
| 0x08600103 | 1         | 3.57%   |
| 0x08108109 | 1         | 3.57%   |
| 0x0600611a | 1         | 3.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| TigerLake     | 3         | 10.71%  |
| Penryn        | 3         | 10.71%  |
| Bonnell       | 3         | 10.71%  |
| Westmere      | 2         | 7.14%   |
| KabyLake      | 2         | 7.14%   |
| Core          | 2         | 7.14%   |
| Unknown       | 2         | 7.14%   |
| Zen+          | 1         | 3.57%   |
| Zen 2         | 1         | 3.57%   |
| Skylake       | 1         | 3.57%   |
| Silvermont    | 1         | 3.57%   |
| P6            | 1         | 3.57%   |
| Nehalem       | 1         | 3.57%   |
| IvyBridge     | 1         | 3.57%   |
| Haswell       | 1         | 3.57%   |
| Goldmont plus | 1         | 3.57%   |
| Excavator     | 1         | 3.57%   |
| CometLake     | 1         | 3.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 18        | 60%     |
| AMD    | 7         | 23.33%  |
| Nvidia | 5         | 16.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Nvidia G98M [Quadro NVS 160M]                                                         | 2         | 6.06%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 2         | 6.06%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 2         | 6.06%   |
| Intel Core Processor Integrated Graphics Controller                                   | 2         | 6.06%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                       | 2         | 6.06%   |
| AMD Lucienne                                                                          | 2         | 6.06%   |
| Nvidia GT216M [GeForce GT 325M]                                                       | 1         | 3.03%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                 | 1         | 3.03%   |
| Nvidia G96GLM [Quadro FX 1700M]                                                       | 1         | 3.03%   |
| Intel Tiger Lake UHD Graphics                                                         | 1         | 3.03%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                            | 1         | 3.03%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller             | 1         | 3.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 3.03%   |
| Intel Iris Plus Graphics 640                                                          | 1         | 3.03%   |
| Intel HD Graphics 530                                                                 | 1         | 3.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 1         | 3.03%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 1         | 3.03%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 1         | 3.03%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 1         | 3.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 1         | 3.03%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 1         | 3.03%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 1         | 3.03%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 3.03%   |
| AMD Renoir                                                                            | 1         | 3.03%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                              | 1         | 3.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 1         | 3.03%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                              | 1         | 3.03%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 16        | 57.14%  |
| 1 x AMD        | 6         | 21.43%  |
| 1 x Nvidia     | 3         | 10.71%  |
| Intel + Nvidia | 2         | 7.14%   |
| 2 x AMD        | 1         | 3.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver | Notebooks | Percent |
|--------|-----------|---------|
| Free   | 28        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 57.14%  |
| 0.01-0.5   | 6         | 21.43%  |
| 0.51-1.0   | 3         | 10.71%  |
| 1.01-2.0   | 2         | 7.14%   |
| 3.01-4.0   | 1         | 3.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 9         | 27.27%  |
| Samsung Electronics     | 3         | 9.09%   |
| LG Display              | 3         | 9.09%   |
| BOE                     | 3         | 9.09%   |
| PANDA                   | 2         | 6.06%   |
| LG Philips              | 2         | 6.06%   |
| Dell                    | 2         | 6.06%   |
| Chimei Innolux          | 2         | 6.06%   |
| Sharp                   | 1         | 3.03%   |
| Quanta Display          | 1         | 3.03%   |
| Planar                  | 1         | 3.03%   |
| HannStar                | 1         | 3.03%   |
| Goldstar                | 1         | 3.03%   |
| Chi Mei Optoelectronics | 1         | 3.03%   |
| Apple                   | 1         | 3.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch              | 2         | 5.88%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                  | 1         | 2.94%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 331x207mm 15.4-inch    | 1         | 2.94%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 1         | 2.94%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 1         | 2.94%   |
| Quanta Display LCD Monitor QDS004B 1280x800 331x207mm 15.4-inch          | 1         | 2.94%   |
| Planar PLL2210W PLN2210 1920x1080 476x268mm 21.5-inch                    | 1         | 2.94%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 1         | 2.94%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                  | 1         | 2.94%   |
| LG Display LCD Monitor LGD069C 1920x1080 309x174mm 14.0-inch             | 1         | 2.94%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch             | 1         | 2.94%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch             | 1         | 2.94%   |
| HannStar HSD160PHW1 HSD0640 1366x768 353x199mm 16.0-inch                 | 1         | 2.94%   |
| Goldstar MX278M GSM57BF 1920x1080 598x336mm 27.0-inch                    | 1         | 2.94%   |
| Dell U2415 DELA0B8 1920x1200 518x324mm 24.1-inch                         | 1         | 2.94%   |
| Dell S2721D DELA199 2560x1440 597x336mm 27.0-inch                        | 1         | 2.94%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                        | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch          | 1         | 2.94%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 222x125mm 10.0-inch | 1         | 2.94%   |
| BOE LCD Monitor BOE07C6 1366x768 309x173mm 13.9-inch                     | 1         | 2.94%   |
| BOE LCD Monitor BOE0713 1920x1080 344x193mm 15.5-inch                    | 1         | 2.94%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO32EC 1366x768 344x193mm 15.5-inch            | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO26ED 1920x1080 344x194mm 15.5-inch           | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch            | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO12EC 1366x768 344x193mm 15.5-inch            | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch             | 1         | 2.94%   |
| Apple Color LCD APPA034 2880x1800 286x179mm 13.3-inch                    | 1         | 2.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 11        | 36.67%  |
| 1366x768 (WXGA)   | 7         | 23.33%  |
| 1024x600          | 3         | 10%     |
| 1920x1200 (WUXGA) | 2         | 6.67%   |
| 1440x900 (WXGA+)  | 2         | 6.67%   |
| 1280x800 (WXGA)   | 2         | 6.67%   |
| 2880x1800         | 1         | 3.33%   |
| 2560x1440 (QHD)   | 1         | 3.33%   |
| 1600x900 (HD+)    | 1         | 3.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 13        | 38.24%  |
| 14     | 5         | 14.71%  |
| 13     | 4         | 11.76%  |
| 27     | 3         | 8.82%   |
| 21     | 2         | 5.88%   |
| 17     | 2         | 5.88%   |
| 10     | 2         | 5.88%   |
| 24     | 1         | 2.94%   |
| 16     | 1         | 2.94%   |
| 8      | 1         | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 20        | 60.61%  |
| 201-300     | 4         | 12.12%  |
| 501-600     | 3         | 9.09%   |
| 351-400     | 3         | 9.09%   |
| 401-500     | 2         | 6.06%   |
| 101-200     | 1         | 3.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 22        | 75.86%  |
| 16/10 | 7         | 24.14%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 14        | 41.18%  |
| 81-90          | 7         | 20.59%  |
| 301-350        | 3         | 8.82%   |
| 71-80          | 2         | 5.88%   |
| 41-50          | 2         | 5.88%   |
| 201-250        | 2         | 5.88%   |
| 1-40           | 1         | 2.94%   |
| 251-300        | 1         | 2.94%   |
| 131-140        | 1         | 2.94%   |
| 121-130        | 1         | 2.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 14        | 41.18%  |
| 101-120       | 12        | 35.29%  |
| 51-100        | 6         | 17.65%  |
| More than 240 | 1         | 2.94%   |
| 161-240       | 1         | 2.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 24        | 85.71%  |
| 2     | 3         | 10.71%  |
| 3     | 1         | 3.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 18        | 41.86%  |
| Intel                         | 10        | 23.26%  |
| Qualcomm Atheros              | 6         | 13.95%  |
| Broadcom                      | 6         | 13.95%  |
| Ralink Technology             | 1         | 2.33%   |
| Ralink                        | 1         | 2.33%   |
| OnePlus Technology (Shenzhen) | 1         | 2.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 10.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 7.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 5.26%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 5.26%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 3.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 3.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 3.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 3.51%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 3.51%   |
| Intel Ultimate N WiFi Link 5300                                   | 2         | 3.51%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 3.51%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 1.75%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 1.75%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1         | 1.75%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.75%   |
| Realtek RTL8187B Wireless Adapter                                 | 1         | 1.75%   |
| Realtek 802.11ac NIC                                              | 1         | 1.75%   |
| Ralink RT5372 Wireless Adapter                                    | 1         | 1.75%   |
| Ralink RT2561/RT61 rev B 802.11g                                  | 1         | 1.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 1.75%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 1.75%   |
| OnePlus (Shenzhen) AC2001                                         | 1         | 1.75%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.75%   |
| Intel Wireless 7260                                               | 1         | 1.75%   |
| Intel WiFi Link 5100                                              | 1         | 1.75%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.75%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.75%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.75%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.75%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.75%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.75%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.75%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                | 1         | 1.75%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 1         | 1.75%   |
| Broadcom BCM43225 802.11b/g/n                                     | 1         | 1.75%   |
| Broadcom BCM4311 802.11b/g WLAN                                   | 1         | 1.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 9         | 31.03%  |
| Realtek Semiconductor | 8         | 27.59%  |
| Broadcom              | 6         | 20.69%  |
| Qualcomm Atheros      | 4         | 13.79%  |
| Ralink Technology     | 1         | 3.45%   |
| Ralink                | 1         | 3.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 9.38%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 6.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 6.25%   |
| Intel Ultimate N WiFi Link 5300                                | 2         | 6.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 6.25%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 3.13%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 3.13%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1         | 3.13%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 3.13%   |
| Realtek RTL8187B Wireless Adapter                              | 1         | 3.13%   |
| Realtek 802.11ac NIC                                           | 1         | 3.13%   |
| Ralink RT5372 Wireless Adapter                                 | 1         | 3.13%   |
| Ralink RT2561/RT61 rev B 802.11g                               | 1         | 3.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 3.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 3.13%   |
| Intel Wireless 8265 / 8275                                     | 1         | 3.13%   |
| Intel Wireless 7260                                            | 1         | 3.13%   |
| Intel WiFi Link 5100                                           | 1         | 3.13%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 3.13%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 3.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 3.13%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 3.13%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter             | 1         | 3.13%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 3.13%   |
| Broadcom BCM43225 802.11b/g/n                                  | 1         | 3.13%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 1         | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 14        | 56%     |
| Intel                         | 7         | 28%     |
| Qualcomm Atheros              | 3         | 12%     |
| OnePlus Technology (Shenzhen) | 1         | 4%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 24%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 16%     |
| Intel 82567LM Gigabit Network Connection                          | 3         | 12%     |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 8%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 8%      |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 8%      |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 4%      |
| OnePlus (Shenzhen) AC2001                                         | 1         | 4%      |
| Intel Ethernet Connection I218-LM                                 | 1         | 4%      |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 4%      |
| Intel Ethernet Connection (11) I219-V                             | 1         | 4%      |
| Intel 82579V Gigabit Network Connection                           | 1         | 4%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 54%     |
| Ethernet | 23        | 46%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 19        | 67.86%  |
| Ethernet | 9         | 32.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 20        | 71.43%  |
| 1     | 7         | 25%     |
| 0     | 1         | 3.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 19        | 67.86%  |
| Yes  | 9         | 32.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 6         | 37.5%   |
| Realtek Semiconductor           | 4         | 25%     |
| Dell                            | 2         | 12.5%   |
| Qualcomm Atheros Communications | 1         | 6.25%   |
| Lite-On Technology              | 1         | 6.25%   |
| Foxconn / Hon Hai               | 1         | 6.25%   |
| Broadcom                        | 1         | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                 | 3         | 18.75%  |
| Intel Bluetooth Device                  | 3         | 18.75%  |
| Intel Bluetooth wireless interface      | 2         | 12.5%   |
| Dell Wireless 370 Bluetooth Mini-card   | 2         | 12.5%   |
| Realtek  Bluetooth 4.2 Adapter          | 1         | 6.25%   |
| Qualcomm Atheros  Bluetooth Device      | 1         | 6.25%   |
| Lite-On Bluetooth Device                | 1         | 6.25%   |
| Intel AX200 Bluetooth                   | 1         | 6.25%   |
| Foxconn / Hon Hai Acer Bluetooth module | 1         | 6.25%   |
| Broadcom HP Portable SoftSailing        | 1         | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 61.11%  |
| AMD                   | 7         | 19.44%  |
| Texas Instruments     | 2         | 5.56%   |
| Nvidia                | 2         | 5.56%   |
| Realtek Semiconductor | 1         | 2.78%   |
| GN Netcom             | 1         | 2.78%   |
| Audioengine           | 1         | 2.78%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 9.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 9.52%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 9.52%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 7.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 7.14%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 7.14%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                          | 1         | 2.38%   |
| Texas Instruments PCM2702 16-bit stereo audio DAC                          | 1         | 2.38%   |
| Realtek Semiconductor USB Audio                                            | 1         | 2.38%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 2.38%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 2.38%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 2.38%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.38%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 2.38%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 2.38%   |
| Intel CM238 HD Audio Controller                                            | 1         | 2.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 2.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 2.38%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 2.38%   |
| GN Netcom Jabra EVOLVE 20 MS                                               | 1         | 2.38%   |
| Audioengine D1 24-bit DAC                                                  | 1         | 2.38%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 2.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 2.38%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 2.38%   |
| AMD IXP SB4x0 High Definition Audio Controller                             | 1         | 2.38%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 2.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 3         | 30%     |
| SK Hynix            | 2         | 20%     |
| A-DATA Technology   | 2         | 20%     |
| Unknown (ABCD)      | 1         | 10%     |
| Nanya Technology    | 1         | 10%     |
| Kingston            | 1         | 10%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 1         | 9.09%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 9.09%   |
| SK Hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 9.09%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 9.09%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 9.09%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 9.09%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 1         | 9.09%   |
| Nanya RAM NT2GT64U8HD0BN-AD 2GB SODIMM DDR2 2048MT/s             | 1         | 9.09%   |
| Kingston RAM KMKYF9-MIB 8192MB SODIMM DDR4 2400MT/s              | 1         | 9.09%   |
| A-DATA RAM Module 8GB SODIMM DDR4 1200MT/s                       | 1         | 9.09%   |
| A-DATA RAM AO1P32NC8T1-BBVS 8192MB SODIMM DDR4 3200MT/s          | 1         | 9.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 7         | 70%     |
| SDRAM  | 2         | 20%     |
| LPDDR4 | 1         | 10%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 10        | 90.91%  |
| Row Of Chips | 1         | 9.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 8192 | 7         | 63.64%  |
| 4096 | 2         | 18.18%  |
| 2048 | 2         | 18.18%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 5         | 50%     |
| 2400  | 2         | 20%     |
| 4199  | 1         | 10%     |
| 2048  | 1         | 10%     |
| 1200  | 1         | 10%     |

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
| Microdia                               | 5         | 23.81%  |
| Chicony Electronics                    | 5         | 23.81%  |
| Suyin                                  | 2         | 9.52%   |
| Sunplus Innovation Technology          | 2         | 9.52%   |
| Luxvisions Innotech Limited            | 2         | 9.52%   |
| IMC Networks                           | 2         | 9.52%   |
| Realtek Semiconductor                  | 1         | 4.76%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 4.76%   |
| ALi                                    | 1         | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                        | 5         | 23.81%  |
| Chicony HP Truevision HD camera                      | 2         | 9.52%   |
| Chicony HD WebCam                                    | 2         | 9.52%   |
| Suyin Acer CrystalEye Webcam                         | 1         | 4.76%   |
| Suyin 1.3M HD WebCam                                 | 1         | 4.76%   |
| Sunplus Aukey-PC-LM1E Camera                         | 1         | 4.76%   |
| Sunplus 1.3M HD WebCam                               | 1         | 4.76%   |
| Realtek Integrated Camera 2M                         | 1         | 4.76%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 4.76%   |
| Luxvisions Innotech Limited HP HD Camera             | 1         | 4.76%   |
| IMC Networks Integrated Camera                       | 1         | 4.76%   |
| IMC Networks 2M Integrated Webcam                    | 1         | 4.76%   |
| Chicony Integrated HP HD Webcam                      | 1         | 4.76%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam  | 1         | 4.76%   |
| ALi Gateway Webcam                                   | 1         | 4.76%   |

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


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 1         | 50%     |
| Validity Sensors VFS491                    | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 5         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 3         | 60%     |
| Broadcom 5880                                  | 1         | 20%     |
| Broadcom 58200                                 | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 17        | 58.62%  |
| 1     | 11        | 37.93%  |
| 2     | 1         | 3.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Chipcard              | 5         | 35.71%  |
| Multimedia controller | 4         | 28.57%  |
| Net/wireless          | 3         | 21.43%  |
| Fingerprint reader    | 2         | 14.29%  |

