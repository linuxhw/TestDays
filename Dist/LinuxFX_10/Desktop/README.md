LinuxFX 10 - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for LinuxFX 10.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=windowsfx-10

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

| Vendor   | Model              | Probe                                                      | Date         |
|----------|--------------------|------------------------------------------------------------|--------------|
| PCWare   | IPMH61R2           | [62d2476431](https://linux-hardware.org/?probe=62d2476431) | Sep 27, 2021 |
| Gigabyte | X570 UD            | [e1777d09cb](https://linux-hardware.org/?probe=e1777d09cb) | Sep 10, 2021 |
| MSI      | A88XI AC           | [1306310e52](https://linux-hardware.org/?probe=1306310e52) | Aug 02, 2021 |
| MSI      | A88XI AC           | [ebdf5c76be](https://linux-hardware.org/?probe=ebdf5c76be) | Aug 02, 2021 |
| ASRock   | B450M Steel Legend | [42869f7bb5](https://linux-hardware.org/?probe=42869f7bb5) | Jun 20, 2021 |
| ASRock   | N68-GE3 UCC        | [f2a9721ca5](https://linux-hardware.org/?probe=f2a9721ca5) | Feb 25, 2021 |
| Gigabyte | G31M-S2C           | [95c9698f2b](https://linux-hardware.org/?probe=95c9698f2b) | Feb 24, 2021 |
| ASRock   | ConRoe1333-D667    | [54121172b8](https://linux-hardware.org/?probe=54121172b8) | Jan 31, 2021 |
| MSI      | B450M PRO-M2 MAX   | [ecbdfd2c54](https://linux-hardware.org/?probe=ecbdfd2c54) | Jan 17, 2021 |
| HP       | 2B1E               | [940750f549](https://linux-hardware.org/?probe=940750f549) | Jan 05, 2021 |
| ASUSTek  | P8Z68-V LE         | [356c40c60b](https://linux-hardware.org/?probe=356c40c60b) | Dec 27, 2020 |
| ASUSTek  | H87-PRO            | [e2287834ae](https://linux-hardware.org/?probe=e2287834ae) | Dec 10, 2020 |
| ASUSTek  | H87-PRO            | [17bd61ae55](https://linux-hardware.org/?probe=17bd61ae55) | Dec 09, 2020 |
| Gigabyte | B450 AORUS M       | [8e3b4356b7](https://linux-hardware.org/?probe=8e3b4356b7) | Dec 03, 2020 |
| Dell     | 0V6D8J A00         | [5b4385cd10](https://linux-hardware.org/?probe=5b4385cd10) | Nov 09, 2020 |
| Dell     | 0V6D8J A00         | [13e1111610](https://linux-hardware.org/?probe=13e1111610) | Nov 09, 2020 |
| Acer     | Aspire TC-105      | [0ee92155a3](https://linux-hardware.org/?probe=0ee92155a3) | Nov 04, 2020 |
| ECS      | A780GM-A           | [cf03b0c26b](https://linux-hardware.org/?probe=cf03b0c26b) | Nov 04, 2020 |
| Gigabyte | 970A-DS3P          | [c5a0f02633](https://linux-hardware.org/?probe=c5a0f02633) | Jul 24, 2020 |
| Dell     | 0Y644J A02         | [96f0709424](https://linux-hardware.org/?probe=96f0709424) | Jul 16, 2020 |
| Gigabyte | B85M-D3H           | [ab9fa86313](https://linux-hardware.org/?probe=ab9fa86313) | Jul 16, 2020 |
| Intel    | B75                | [dc59852769](https://linux-hardware.org/?probe=dc59852769) | Jul 11, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.4.0-52-generic            | 6        | 35.29%  |
| 5.4.0-72-generic            | 3        | 17.65%  |
| 5.6.15-windowsfx-10-generic | 2        | 11.76%  |
| 5.4.0-56-generic            | 2        | 11.76%  |
| 5.7.8-windowsfx-generic     | 1        | 5.88%   |
| 5.7.15-050715-generic       | 1        | 5.88%   |
| 5.5.19-050519-generic       | 1        | 5.88%   |
| 5.4.0-65-generic            | 1        | 5.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 12       | 70.59%  |
| 5.6.15  | 2        | 11.76%  |
| 5.7.8   | 1        | 5.88%   |
| 5.7.15  | 1        | 5.88%   |
| 5.5.19  | 1        | 5.88%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 12       | 70.59%  |
| 5.7     | 2        | 11.76%  |
| 5.6     | 2        | 11.76%  |
| 5.5     | 1        | 5.88%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 17       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| X-Cinnamon | 11       | 64.71%  |
| KDE        | 5        | 29.41%  |
| Unknown    | 1        | 5.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 17       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 11       | 64.71%  |
| SDDM    | 3        | 17.65%  |
| LightDM | 3        | 17.65%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| pt_BR | 5        | 29.41%  |
| en_US | 4        | 23.53%  |
| de_DE | 2        | 11.76%  |
| C     | 2        | 11.76%  |
| sv_SE | 1        | 5.88%   |
| sr_RS | 1        | 5.88%   |
| fr_CA | 1        | 5.88%   |
| en_IN | 1        | 5.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 11       | 64.71%  |
| EFI  | 6        | 35.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 16       | 94.12%  |
| Overlay | 1        | 5.88%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 15       | 88.24%  |
| MBR     | 2        | 11.76%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 76.47%  |
| Yes       | 4        | 23.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 64.71%  |
| Yes       | 6        | 35.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 4        | 23.53%  |
| ASRock              | 3        | 17.65%  |
| MSI                 | 2        | 11.76%  |
| Dell                | 2        | 11.76%  |
| ASUSTek Computer    | 2        | 11.76%  |
| PCWare              | 1        | 5.88%   |
| Intel               | 1        | 5.88%   |
| Hewlett-Packard     | 1        | 5.88%   |
| ECS                 | 1        | 5.88%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| PCWare IPMH61R2           | 1        | 5.88%   |
| MSI MS-7B84               | 1        | 5.88%   |
| MSI MS-7913               | 1        | 5.88%   |
| Intel B75                 | 1        | 5.88%   |
| HP 202 G2 MT              | 1        | 5.88%   |
| Gigabyte X570 UD          | 1        | 5.88%   |
| Gigabyte G31M-ES2C        | 1        | 5.88%   |
| Gigabyte B450 AORUS M     | 1        | 5.88%   |
| Gigabyte 970A-DS3P        | 1        | 5.88%   |
| ECS A780GM-A              | 1        | 5.88%   |
| Dell OptiPlex 360         | 1        | 5.88%   |
| Dell Inspiron 3646        | 1        | 5.88%   |
| ASUS P8Z68-V LE           | 1        | 5.88%   |
| ASUS All Series           | 1        | 5.88%   |
| ASRock N68-GE3 UCC        | 1        | 5.88%   |
| ASRock ConRoe1333-D667    | 1        | 5.88%   |
| ASRock B450M Steel Legend | 1        | 5.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| PCWare IPMH61R2        | 1        | 5.88%   |
| MSI MS-7B84            | 1        | 5.88%   |
| MSI MS-7913            | 1        | 5.88%   |
| Intel B75              | 1        | 5.88%   |
| HP 202                 | 1        | 5.88%   |
| Gigabyte X570          | 1        | 5.88%   |
| Gigabyte G31M-ES2C     | 1        | 5.88%   |
| Gigabyte B450          | 1        | 5.88%   |
| Gigabyte 970A-DS3P     | 1        | 5.88%   |
| ECS A780GM-A           | 1        | 5.88%   |
| Dell OptiPlex          | 1        | 5.88%   |
| Dell Inspiron          | 1        | 5.88%   |
| ASUS P8Z68-V           | 1        | 5.88%   |
| ASUS All               | 1        | 5.88%   |
| ASRock N68-GE3         | 1        | 5.88%   |
| ASRock ConRoe1333-D667 | 1        | 5.88%   |
| ASRock B450M           | 1        | 5.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2009 | 3        | 17.65%  |
| 2020 | 2        | 11.76%  |
| 2019 | 2        | 11.76%  |
| 2014 | 2        | 11.76%  |
| 2010 | 2        | 11.76%  |
| 2021 | 1        | 5.88%   |
| 2018 | 1        | 5.88%   |
| 2016 | 1        | 5.88%   |
| 2015 | 1        | 5.88%   |
| 2012 | 1        | 5.88%   |
| 2011 | 1        | 5.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 17       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 17       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 17       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 6        | 35.29%  |
| 16.01-24.0 | 5        | 29.41%  |
| 8.01-16.0  | 3        | 17.65%  |
| 32.01-64.0 | 2        | 11.76%  |
| 1.01-2.0   | 1        | 5.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 7        | 41.18%  |
| 1.01-2.0  | 7        | 41.18%  |
| 4.01-8.0  | 1        | 5.88%   |
| 3.01-4.0  | 1        | 5.88%   |
| 8.01-16.0 | 1        | 5.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 7        | 41.18%  |
| 2      | 6        | 35.29%  |
| 3      | 3        | 17.65%  |
| 4      | 1        | 5.88%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 70.59%  |
| Yes       | 5        | 29.41%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 17       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 58.82%  |
| Yes       | 7        | 41.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 76.47%  |
| Yes       | 4        | 23.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Brazil       | 5        | 29.41%  |
| USA          | 4        | 23.53%  |
| Germany      | 2        | 11.76%  |
| Sweden       | 1        | 5.88%   |
| South Africa | 1        | 5.88%   |
| Serbia       | 1        | 5.88%   |
| India        | 1        | 5.88%   |
| Croatia      | 1        | 5.88%   |
| Canada       | 1        | 5.88%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Curitiba        | 2        | 11.76%  |
| Zagreb          | 1        | 5.88%   |
| Taboao da Serra | 1        | 5.88%   |
| Stockholm       | 1        | 5.88%   |
| Rio de Janeiro  | 1        | 5.88%   |
| Port Elizabeth  | 1        | 5.88%   |
| North Lewisburg | 1        | 5.88%   |
| Moreno Valley   | 1        | 5.88%   |
| Montreal        | 1        | 5.88%   |
| Karlsruhe       | 1        | 5.88%   |
| Douglas         | 1        | 5.88%   |
| Castroville     | 1        | 5.88%   |
| Bonn            | 1        | 5.88%   |
| Bhopal          | 1        | 5.88%   |
| Belo Horizonte  | 1        | 5.88%   |
| Belgrade        | 1        | 5.88%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 8      | 27.59%  |
| Hitachi             | 3        | 3      | 10.34%  |
| Toshiba             | 2        | 2      | 6.9%    |
| Samsung Electronics | 2        | 3      | 6.9%    |
| Kingston            | 2        | 3      | 6.9%    |
| XPG                 | 1        | 1      | 3.45%   |
| TO Exter            | 1        | 1      | 3.45%   |
| Seagate             | 1        | 2      | 3.45%   |
| SanDisk             | 1        | 1      | 3.45%   |
| PNY                 | 1        | 1      | 3.45%   |
| Phison              | 1        | 1      | 3.45%   |
| OCZ                 | 1        | 1      | 3.45%   |
| Mushkin             | 1        | 1      | 3.45%   |
| MAXTOR              | 1        | 1      | 3.45%   |
| Hewlett-Packard     | 1        | 1      | 3.45%   |
| China               | 1        | 1      | 3.45%   |
| ASMT109x            | 1        | 1      | 3.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| XPG GAMMIX S11 Pro 512GB           | 1        | 3.23%   |
| WDC WD5000AAKX-001CA0 500GB        | 1        | 3.23%   |
| WDC WD5000AACS-00G8B1 500GB        | 1        | 3.23%   |
| WDC WD400JD-55MSA1 40GB            | 1        | 3.23%   |
| WDC WD2500BEVS-22UST0 250GB        | 1        | 3.23%   |
| WDC WD20EZRX-00D8PB0 2TB           | 1        | 3.23%   |
| WDC WD10EZEX-08WN4A0 1TB           | 1        | 3.23%   |
| WDC WD10EARX-00N0YB0 1TB           | 1        | 3.23%   |
| WDC WD1003FZEX-00MK2A0 1TB         | 1        | 3.23%   |
| Toshiba MQ01ACF050 500GB           | 1        | 3.23%   |
| Toshiba MQ01ABD050 500GB           | 1        | 3.23%   |
| TO Exter nal USB 3.0 4TB           | 1        | 3.23%   |
| Seagate ST500LX012-SSHD-8GB        | 1        | 3.23%   |
| Seagate ST500DM002-1BD142 500GB    | 1        | 3.23%   |
| SanDisk SD9SN8W256G1002 256GB SSD  | 1        | 3.23%   |
| Samsung HD501LJ 500GB              | 1        | 3.23%   |
| Samsung HD321KJ 320GB              | 1        | 3.23%   |
| Samsung HD161HJ 41R0186LEN 160GB   | 1        | 3.23%   |
| PNY SSD2SC240G1SA754D117-443 240GB | 1        | 3.23%   |
| Phison NVMe SSD Drive 1TB          | 1        | 3.23%   |
| OCZ ARC100 240GB SSD               | 1        | 3.23%   |
| Mushkin MKNSSDSR250GB              | 1        | 3.23%   |
| MAXTOR STM3160215AS 160GB          | 1        | 3.23%   |
| Kingston SV300S37A120G 120GB SSD   | 1        | 3.23%   |
| Kingston SA400S37480G 480GB SSD    | 1        | 3.23%   |
| Hitachi HUS724040ALE641 4TB        | 1        | 3.23%   |
| Hitachi HDT721032SLA360 320GB      | 1        | 3.23%   |
| Hitachi HDS725050KLA360 500GB      | 1        | 3.23%   |
| HP SSD S700 500GB                  | 1        | 3.23%   |
| China SATA SSD 120GB               | 1        | 3.23%   |
| ASMT109x Config 100MB              | 1        | 3.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 8      | 42.11%  |
| Hitachi             | 3        | 3      | 15.79%  |
| Toshiba             | 2        | 2      | 10.53%  |
| Samsung Electronics | 2        | 3      | 10.53%  |
| TO Exter            | 1        | 1      | 5.26%   |
| Seagate             | 1        | 2      | 5.26%   |
| MAXTOR              | 1        | 1      | 5.26%   |
| ASMT109x            | 1        | 1      | 5.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| Kingston        | 2        | 3      | 25%     |
| SanDisk         | 1        | 1      | 12.5%   |
| PNY             | 1        | 1      | 12.5%   |
| OCZ             | 1        | 1      | 12.5%   |
| Mushkin         | 1        | 1      | 12.5%   |
| Hewlett-Packard | 1        | 1      | 12.5%   |
| China           | 1        | 1      | 12.5%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 14       | 21     | 60.87%  |
| SSD  | 7        | 9      | 30.43%  |
| NVMe | 2        | 2      | 8.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 16       | 29     | 84.21%  |
| NVMe | 2        | 2      | 10.53%  |
| SAS  | 1        | 1      | 5.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 15       | 24     | 71.43%  |
| 0.51-1.0   | 3        | 3      | 14.29%  |
| 3.01-4.0   | 2        | 2      | 9.52%   |
| 1.01-2.0   | 1        | 1      | 4.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 251-500    | 5        | 29.41%  |
| 101-250    | 5        | 29.41%  |
| 51-100     | 3        | 17.65%  |
| 21-50      | 2        | 11.76%  |
| 1-20       | 1        | 5.88%   |
| 501-1000   | 1        | 5.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 10       | 58.82%  |
| 21-50   | 2        | 11.76%  |
| 101-250 | 2        | 11.76%  |
| 51-100  | 2        | 11.76%  |
| 251-500 | 1        | 5.88%   |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 16       | 29     | 88.89%  |
| Works    | 2        | 3      | 11.11%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Intel              | 9        | 45%     |
| AMD                | 7        | 35%     |
| Phison Electronics | 1        | 5%      |
| Nvidia             | 1        | 5%      |
| ASMedia Technology | 1        | 5%      |
| ADATA Technology   | 1        | 5%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 5        | 17.24%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 10.34%  |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 10.34%  |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 6.9%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 6.9%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 6.9%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 3.45%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 3.45%   |
| Nvidia MCP61 IDE                                                                        | 1        | 3.45%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 3.45%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 3.45%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 3.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 3.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 3.45%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 3.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 12       | 57.14%  |
| IDE  | 7        | 33.33%  |
| NVMe | 2        | 9.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 9        | 52.94%  |
| AMD    | 8        | 47.06%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 5.88%   |
| Intel Pentium CPU J2900 @ 2.41GHz           | 1        | 5.88%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1        | 5.88%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 5.88%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 5.88%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 5.88%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1        | 5.88%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 5.88%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 1        | 5.88%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1        | 5.88%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 1        | 5.88%   |
| AMD Ryzen 5 3600 6-Core Processor           | 1        | 5.88%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 1        | 5.88%   |
| AMD Phenom 9650 Quad-Core Processor         | 1        | 5.88%   |
| AMD FX-6300 Six-Core Processor              | 1        | 5.88%   |
| AMD Athlon II X2 260 Processor              | 1        | 5.88%   |
| AMD A8-6600K APU with Radeon HD Graphics    | 1        | 5.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Pentium      | 2        | 11.76%  |
| Intel Core i7      | 2        | 11.76%  |
| Intel Core 2 Duo   | 2        | 11.76%  |
| Intel Pentium Dual | 1        | 5.88%   |
| Intel Core i5      | 1        | 5.88%   |
| Intel Core i3      | 1        | 5.88%   |
| AMD Ryzen 9        | 1        | 5.88%   |
| AMD Ryzen 7        | 1        | 5.88%   |
| AMD Ryzen 5        | 1        | 5.88%   |
| AMD Ryzen 3        | 1        | 5.88%   |
| AMD Phenom         | 1        | 5.88%   |
| AMD FX             | 1        | 5.88%   |
| AMD Athlon II X2   | 1        | 5.88%   |
| AMD A8             | 1        | 5.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 7        | 41.18%  |
| 4      | 6        | 35.29%  |
| 12     | 1        | 5.88%   |
| 8      | 1        | 5.88%   |
| 6      | 1        | 5.88%   |
| 3      | 1        | 5.88%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 17       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 9        | 52.94%  |
| 2      | 8        | 47.06%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 17       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 5        | 29.41%  |
| 0x6fd      | 2        | 11.76%  |
| 0x306c3    | 2        | 11.76%  |
| 0x206a7    | 2        | 11.76%  |
| 0x306a9    | 1        | 5.88%   |
| 0x30678    | 1        | 5.88%   |
| 0x08701013 | 1        | 5.88%   |
| 0x08108109 | 1        | 5.88%   |
| 0x010000c8 | 1        | 5.88%   |
| 0x01000095 | 1        | 5.88%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 2       | 3        | 17.65%  |
| SandyBridge | 2        | 11.76%  |
| Piledriver  | 2        | 11.76%  |
| K10         | 2        | 11.76%  |
| Haswell     | 2        | 11.76%  |
| Core        | 2        | 11.76%  |
| Zen+        | 1        | 5.88%   |
| Silvermont  | 1        | 5.88%   |
| Penryn      | 1        | 5.88%   |
| IvyBridge   | 1        | 5.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 8        | 44.44%  |
| Intel  | 5        | 27.78%  |
| AMD    | 5        | 27.78%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 11.11%  |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 5.56%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 5.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 5.56%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 5.56%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                       | 1        | 5.56%   |
| Nvidia GF110 [GeForce GTX 580]                                              | 1        | 5.56%   |
| Nvidia GF110 [GeForce GTX 570]                                              | 1        | 5.56%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 5.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1        | 5.56%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 5.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 5.56%   |
| AMD RV610 [Radeon HD 2400 PRO]                                              | 1        | 5.56%   |
| AMD Richland [Radeon HD 8570D]                                              | 1        | 5.56%   |
| AMD Picasso                                                                 | 1        | 5.56%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 5.56%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 5.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 8        | 47.06%  |
| 1 x AMD    | 5        | 29.41%  |
| 1 x Intel  | 4        | 23.53%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 13       | 76.47%  |
| Unknown     | 3        | 17.65%  |
| Proprietary | 1        | 5.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 9        | 52.94%  |
| 1.01-2.0   | 3        | 17.65%  |
| 3.01-4.0   | 2        | 11.76%  |
| 0.01-0.5   | 2        | 11.76%  |
| 0.51-1.0   | 1        | 5.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Goldstar            | 5        | 35.71%  |
| Samsung Electronics | 2        | 14.29%  |
| Acer                | 2        | 14.29%  |
| ViewSonic           | 1        | 7.14%   |
| Sceptre Tech        | 1        | 7.14%   |
| Philips             | 1        | 7.14%   |
| Hewlett-Packard     | 1        | 7.14%   |
| BenQ                | 1        | 7.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                | 2        | 12.5%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch          | 1        | 6.25%   |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch             | 1        | 6.25%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch  | 1        | 6.25%   |
| Samsung Electronics SMBX2331 SAM076F 1920x1080 510x290mm 23.1-inch | 1        | 6.25%   |
| Philips 200V4 PHLC0BF 1600x900 432x240mm 19.5-inch                 | 1        | 6.25%   |
| Hewlett-Packard LE1851w HWP2840 1366x768 413x234mm 18.7-inch       | 1        | 6.25%   |
| Goldstar W2243 GSM56FF 1920x1080 477x268mm 21.5-inch               | 1        | 6.25%   |
| Goldstar W1953 GSM4BA6 1360x768 406x229mm 18.4-inch                | 1        | 6.25%   |
| Goldstar E2441 GSM581F 1920x1080 531x299mm 24.0-inch               | 1        | 6.25%   |
| BenQ LCD Monitor GL951A 2880x900                                   | 1        | 6.25%   |
| BenQ LCD Monitor GL951A                                            | 1        | 6.25%   |
| BenQ GL951A BNQ7897 1440x900 408x255mm 18.9-inch                   | 1        | 6.25%   |
| Acer V226WL ACR0339 1680x1050 474x296mm 22.0-inch                  | 1        | 6.25%   |
| Acer G226HQL ACR02EA 1920x1080 480x270mm 21.7-inch                 | 1        | 6.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 5        | 31.25%  |
| 1600x900 (HD+)     | 3        | 18.75%  |
| 3840x2160 (4K)     | 1        | 6.25%   |
| 2880x900           | 1        | 6.25%   |
| 2560x1440 (QHD)    | 1        | 6.25%   |
| 1680x1050 (WSXGA+) | 1        | 6.25%   |
| 1440x900 (WXGA+)   | 1        | 6.25%   |
| 1366x768 (WXGA)    | 1        | 6.25%   |
| 1360x768           | 1        | 6.25%   |
| Unknown            | 1        | 6.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 31      | 2        | 13.33%  |
| 21      | 2        | 13.33%  |
| 20      | 2        | 13.33%  |
| 19      | 2        | 13.33%  |
| 18      | 2        | 13.33%  |
| 27      | 1        | 6.67%   |
| 24      | 1        | 6.67%   |
| 23      | 1        | 6.67%   |
| 22      | 1        | 6.67%   |
| Unknown | 1        | 6.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 9        | 60%     |
| 601-700     | 3        | 20%     |
| 501-600     | 2        | 13.33%  |
| Unknown     | 1        | 6.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 12       | 80%     |
| 16/10   | 2        | 13.33%  |
| Unknown | 1        | 6.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 5        | 33.33%  |
| 151-200        | 4        | 26.67%  |
| 351-500        | 2        | 13.33%  |
| 141-150        | 2        | 13.33%  |
| 301-350        | 1        | 6.67%   |
| Unknown        | 1        | 6.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 11       | 73.33%  |
| 101-120 | 2        | 13.33%  |
| 121-160 | 1        | 6.67%   |
| Unknown | 1        | 6.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 14       | 82.35%  |
| 0     | 2        | 11.76%  |
| 2     | 1        | 5.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 15       | 65.22%  |
| TP-Link               | 2        | 8.7%    |
| Qualcomm Atheros      | 2        | 8.7%    |
| Qualcomm              | 1        | 4.35%   |
| Nvidia                | 1        | 4.35%   |
| Intel                 | 1        | 4.35%   |
| Broadcom              | 1        | 4.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13       | 48.15%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 7.41%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                             | 1        | 3.7%    |
| TP-Link Archer T4U ver.3                                          | 1        | 3.7%    |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter              | 1        | 3.7%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 3.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 3.7%    |
| Realtek 802.11ac NIC                                              | 1        | 3.7%    |
| Qualcomm SM8250-APOLLO _SN:B760817D                               | 1        | 3.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 3.7%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 1        | 3.7%    |
| Nvidia MCP61 Ethernet                                             | 1        | 3.7%    |
| Intel Wireless 7260                                               | 1        | 3.7%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1        | 3.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 4        | 44.44%  |
| TP-Link               | 2        | 22.22%  |
| Qualcomm Atheros      | 2        | 22.22%  |
| Intel                 | 1        | 11.11%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| TP-Link TL-WN821N Version 5 RTL8192EU                      | 1        | 11.11%  |
| TP-Link Archer T4U ver.3                                   | 1        | 11.11%  |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter       | 1        | 11.11%  |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 1        | 11.11%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 1        | 11.11%  |
| Realtek 802.11ac NIC                                       | 1        | 11.11%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1        | 11.11%  |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter | 1        | 11.11%  |
| Intel Wireless 7260                                        | 1        | 11.11%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 15       | 83.33%  |
| Qualcomm              | 1        | 5.56%   |
| Nvidia                | 1        | 5.56%   |
| Broadcom              | 1        | 5.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13       | 72.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 11.11%  |
| Qualcomm SM8250-APOLLO _SN:B760817D                               | 1        | 5.56%   |
| Nvidia MCP61 Ethernet                                             | 1        | 5.56%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1        | 5.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 17       | 68%     |
| WiFi     | 8        | 32%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 15       | 78.95%  |
| WiFi     | 4        | 21.05%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 12       | 70.59%  |
| 2     | 5        | 29.41%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 17       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 2        | 50%     |
| Qualcomm Atheros Communications | 1        | 25%     |
| Integrated System Solution      | 1        | 25%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 2        | 50%     |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 25%     |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 25%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 9        | 30%     |
| AMD                 | 9        | 30%     |
| Nvidia              | 8        | 26.67%  |
| Texas Instruments   | 1        | 3.33%   |
| Creative Labs       | 1        | 3.33%   |
| Corsair             | 1        | 3.33%   |
| C-Media Electronics | 1        | 3.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 8.82%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 8.82%   |
| Nvidia GF110 High Definition Audio Controller                              | 2        | 5.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 5.88%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 5.88%   |
| Texas Instruments PCM2900 Audio Codec                                      | 1        | 2.94%   |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 2.94%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 2.94%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 2.94%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 2.94%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 2.94%   |
| Nvidia GF116 High Definition Audio Controller                              | 1        | 2.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 2.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1        | 2.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 2.94%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                 | 1        | 2.94%   |
| Corsair VOID PRO Surround USB Adapter                                      | 1        | 2.94%   |
| C-Media Electronics Audio Adapter                                          | 1        | 2.94%   |
| AMD Trinity HDMI Audio Controller                                          | 1        | 2.94%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]          | 1        | 2.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 2.94%   |
| AMD FCH Azalia Controller                                                  | 1        | 2.94%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 1        | 2.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 2.94%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 2.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Corsair  | 3        | 60%     |
| Kingston | 1        | 20%     |
| G.Skill  | 1        | 20%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KHX2400C11D3/8GX 8192MB DIMM DDR3 2400MT/s  | 1        | 20%     |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3200MT/s   | 1        | 20%     |
| Corsair RAM CMY8GX3M2C1600C9 4096MB DIMM DDR3 1600MT/s   | 1        | 20%     |
| Corsair RAM CMW16GX4M2C3200C16 8192MB DIMM DDR4 3266MT/s | 1        | 20%     |
| Corsair RAM CML16GX3M2A1600C10 8192MB DIMM DDR3 1600MT/s | 1        | 20%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 2        | 50%     |
| DDR3 | 2        | 50%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 4        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 8192 | 3        | 75%     |
| 4096 | 1        | 25%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 2        | 40%     |
| 3266  | 1        | 20%     |
| 3200  | 1        | 20%     |
| 2400  | 1        | 20%     |

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


| Model            | Desktops | Percent |
|------------------|----------|---------|
| HP LaserJet 3052 | 1        | 100%    |

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


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Microsoft | 1        | 33.33%  |
| Microdia  | 1        | 33.33%  |
| Logitech  | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Microsoft LifeCam HD-3000  | 1        | 33.33%  |
| Microdia USB 2.0 Camera    | 1        | 33.33%  |
| Logitech QuickCam Pro 9000 | 1        | 33.33%  |

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
| 0     | 11       | 64.71%  |
| 1     | 6        | 35.29%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Net/wireless  | 4        | 57.14%  |
| Graphics card | 3        | 42.86%  |

