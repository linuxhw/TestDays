Slackware 15.0 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Slackware 15.0.

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

Total: 27

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| MSI       | Modern 14 B10MW             | [b9cde08864](https://linux-hardware.org/?probe=b9cde08864) | Jul 25, 2022 |
| Sony      | SVE1713A1EW                 | [c3a65d695d](https://linux-hardware.org/?probe=c3a65d695d) | May 10, 2022 |
| Lenovo    | ThinkPad X1 Carbon 5th 2... | [f837aaeb12](https://linux-hardware.org/?probe=f837aaeb12) | May 08, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [bd2dda1d8a](https://linux-hardware.org/?probe=bd2dda1d8a) | Apr 29, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [cfc9c5dbf7](https://linux-hardware.org/?probe=cfc9c5dbf7) | Apr 29, 2022 |
| MSI       | GP76 Leopard 11UG           | [aebd373a66](https://linux-hardware.org/?probe=aebd373a66) | Apr 12, 2022 |
| MSI       | GE76 Raider 11UE            | [3072e065a3](https://linux-hardware.org/?probe=3072e065a3) | Apr 12, 2022 |
| Notebook  | X170KM-G                    | [4ecba03d19](https://linux-hardware.org/?probe=4ecba03d19) | Apr 11, 2022 |
| Dell      | Latitude 3520               | [4398aa2a03](https://linux-hardware.org/?probe=4398aa2a03) | Apr 06, 2022 |
| HP        | ProBook 6570b               | [cf1305eacc](https://linux-hardware.org/?probe=cf1305eacc) | Apr 06, 2022 |
| Lenovo    | IdeaPad 310-15ISK 80SM      | [d406cb4819](https://linux-hardware.org/?probe=d406cb4819) | Apr 05, 2022 |
| Dell      | Precision M4700             | [ab99532bd5](https://linux-hardware.org/?probe=ab99532bd5) | Apr 04, 2022 |
| Lenovo    | ThinkPad X230 2325P38       | [1a0cab737b](https://linux-hardware.org/?probe=1a0cab737b) | Mar 10, 2022 |
| ASUSTek   | ROG Zephyrus G14 GA401IV... | [0b0c1aca1b](https://linux-hardware.org/?probe=0b0c1aca1b) | Mar 10, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [c7825c54fc](https://linux-hardware.org/?probe=c7825c54fc) | Mar 10, 2022 |
| Framework | Laptop                      | [ae37705198](https://linux-hardware.org/?probe=ae37705198) | Mar 10, 2022 |
| Lenovo    | ThinkPad Edge E530c 3366... | [8ce0419468](https://linux-hardware.org/?probe=8ce0419468) | Feb 13, 2022 |
| Dynabook  | P1-C7MP-BL                  | [268f94787e](https://linux-hardware.org/?probe=268f94787e) | Jan 14, 2022 |
| HP        | Laptop 15-bs1xx             | [b6c9f34c4c](https://linux-hardware.org/?probe=b6c9f34c4c) | Dec 07, 2021 |
| System76  | Oryx Pro                    | [3cd05d02a8](https://linux-hardware.org/?probe=3cd05d02a8) | Oct 27, 2021 |
| MSI       | Modern 14 B11MO             | [e8f13facfd](https://linux-hardware.org/?probe=e8f13facfd) | Oct 03, 2021 |
| MSI       | Modern 14 B11MO             | [9f5c2e0fde](https://linux-hardware.org/?probe=9f5c2e0fde) | Sep 27, 2021 |
| Dell      | Inspiron 15-3552            | [f76339b0af](https://linux-hardware.org/?probe=f76339b0af) | Aug 31, 2021 |
| HP        | 245 G7 Notebook PC          | [c0806e4955](https://linux-hardware.org/?probe=c0806e4955) | Aug 23, 2021 |
| HP        | 245 G7 Notebook PC          | [c409287d23](https://linux-hardware.org/?probe=c409287d23) | Aug 23, 2021 |
| HP        | EliteBook 840 G5            | [4c196e1abd](https://linux-hardware.org/?probe=4c196e1abd) | Aug 18, 2021 |
| Dell      | Vostro 3500                 | [53a1179121](https://linux-hardware.org/?probe=53a1179121) | Aug 12, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version     | Notebooks | Percent |
|-------------|-----------|---------|
| 5.15.19     | 6         | 24%     |
| 5.17.1      | 2         | 8%      |
| 5.13.8      | 2         | 8%      |
| 5.17.5      | 1         | 4%      |
| 5.17.2      | 1         | 4%      |
| 5.16.9-joe1 | 1         | 4%      |
| 5.16.12     | 1         | 4%      |
| 5.15.37.a   | 1         | 4%      |
| 5.15.33.kjh | 1         | 4%      |
| 5.15.27     | 1         | 4%      |
| 5.15.1      | 1         | 4%      |
| 5.14.9      | 1         | 4%      |
| 5.14.8      | 1         | 4%      |
| 5.14.10     | 1         | 4%      |
| 5.14.0      | 1         | 4%      |
| 5.13.5      | 1         | 4%      |
| 5.13.11     | 1         | 4%      |
| 5.10.91     | 1         | 4%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.19 | 6         | 24%     |
| 5.17.1  | 2         | 8%      |
| 5.13.8  | 2         | 8%      |
| 5.17.5  | 1         | 4%      |
| 5.17.2  | 1         | 4%      |
| 5.16.9  | 1         | 4%      |
| 5.16.12 | 1         | 4%      |
| 5.15.37 | 1         | 4%      |
| 5.15.33 | 1         | 4%      |
| 5.15.27 | 1         | 4%      |
| 5.15.1  | 1         | 4%      |
| 5.14.9  | 1         | 4%      |
| 5.14.8  | 1         | 4%      |
| 5.14.10 | 1         | 4%      |
| 5.14.0  | 1         | 4%      |
| 5.13.5  | 1         | 4%      |
| 5.13.11 | 1         | 4%      |
| 5.10.91 | 1         | 4%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 10        | 41.67%  |
| 5.17    | 4         | 16.67%  |
| 5.13    | 4         | 16.67%  |
| 5.14    | 3         | 12.5%   |
| 5.16    | 2         | 8.33%   |
| 5.10    | 1         | 4.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 24        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KDE5      | 13        | 54.17%  |
| XFCE      | 5         | 20.83%  |
| Unknown   | 3         | 12.5%   |
| xwmconfig | 1         | 4.17%   |
| MATE      | 1         | 4.17%   |
| KDE       | 1         | 4.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 15        | 60%     |
| Tty     | 8         | 32%     |
| Wayland | 2         | 8%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 16        | 66.67%  |
| Unknown | 5         | 20.83%  |
| XDM     | 3         | 12.5%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 19        | 79.17%  |
| fr_FR | 2         | 8.33%   |
| ru_RU | 1         | 4.17%   |
| pt_BR | 1         | 4.17%   |
| de_DE | 1         | 4.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 15        | 62.5%   |
| BIOS | 9         | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 19        | 79.17%  |
| Btrfs   | 3         | 12.5%   |
| Overlay | 2         | 8.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 17        | 70.83%  |
| MBR     | 5         | 20.83%  |
| Unknown | 2         | 8.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 20        | 80%     |
| Yes       | 5         | 20%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 13        | 54.17%  |
| No        | 11        | 45.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 6         | 25%     |
| MSI              | 4         | 16.67%  |
| Lenovo           | 4         | 16.67%  |
| Dell             | 4         | 16.67%  |
| System76         | 1         | 4.17%   |
| Sony             | 1         | 4.17%   |
| Notebook         | 1         | 4.17%   |
| Framework        | 1         | 4.17%   |
| Dynabook         | 1         | 4.17%   |
| ASUSTek Computer | 1         | 4.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| System76 Oryx Pro                        | 1         | 4.17%   |
| Sony SVE1713A1EW                         | 1         | 4.17%   |
| Notebook X170KM-G                        | 1         | 4.17%   |
| MSI Modern 14 B11MO                      | 1         | 4.17%   |
| MSI Modern 14 B10MW                      | 1         | 4.17%   |
| MSI GP76 Leopard 11UG                    | 1         | 4.17%   |
| MSI GE76 Raider 11UE                     | 1         | 4.17%   |
| Lenovo ThinkPad X230 2325P38             | 1         | 4.17%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04300 | 1         | 4.17%   |
| Lenovo ThinkPad Edge E530c 336669G       | 1         | 4.17%   |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 4.17%   |
| HP ProBook 6570b                         | 1         | 4.17%   |
| HP Pavilion Gaming Laptop 16-a0xxx       | 1         | 4.17%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 1         | 4.17%   |
| HP Laptop 15-bs1xx                       | 1         | 4.17%   |
| HP EliteBook 840 G5                      | 1         | 4.17%   |
| HP 245 G7 Notebook PC                    | 1         | 4.17%   |
| Framework Laptop                         | 1         | 4.17%   |
| Dynabook P1-C7MP-BL                      | 1         | 4.17%   |
| Dell Vostro 3500                         | 1         | 4.17%   |
| Dell Precision M4700                     | 1         | 4.17%   |
| Dell Latitude 3520                       | 1         | 4.17%   |
| Dell Inspiron 15-3552                    | 1         | 4.17%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV    | 1         | 4.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 3         | 12.5%   |
| MSI Modern          | 2         | 8.33%   |
| HP Pavilion         | 2         | 8.33%   |
| System76 Oryx       | 1         | 4.17%   |
| Sony SVE1713A1EW    | 1         | 4.17%   |
| Notebook X170KM-G   | 1         | 4.17%   |
| MSI GP76            | 1         | 4.17%   |
| MSI GE76            | 1         | 4.17%   |
| Lenovo IdeaPad      | 1         | 4.17%   |
| HP ProBook          | 1         | 4.17%   |
| HP Laptop           | 1         | 4.17%   |
| HP EliteBook        | 1         | 4.17%   |
| HP 245              | 1         | 4.17%   |
| Framework Laptop    | 1         | 4.17%   |
| Dynabook P1-C7MP-BL | 1         | 4.17%   |
| Dell Vostro         | 1         | 4.17%   |
| Dell Precision      | 1         | 4.17%   |
| Dell Latitude       | 1         | 4.17%   |
| Dell Inspiron       | 1         | 4.17%   |
| ASUS ROG            | 1         | 4.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 6         | 25%     |
| 2020 | 6         | 25%     |
| 2012 | 5         | 20.83%  |
| 2017 | 2         | 8.33%   |
| 2019 | 1         | 4.17%   |
| 2018 | 1         | 4.17%   |
| 2016 | 1         | 4.17%   |
| 2015 | 1         | 4.17%   |
| 2010 | 1         | 4.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 24        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 24        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 22        | 91.67%  |
| Yes  | 2         | 8.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 6         | 25%     |
| 4.01-8.0    | 5         | 20.83%  |
| 3.01-4.0    | 5         | 20.83%  |
| 16.01-24.0  | 4         | 16.67%  |
| 32.01-64.0  | 2         | 8.33%   |
| 24.01-32.0  | 1         | 4.17%   |
| 64.01-256.0 | 1         | 4.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 8         | 32%     |
| 1.01-2.0   | 8         | 32%     |
| 4.01-8.0   | 6         | 24%     |
| 16.01-24.0 | 1         | 4%      |
| 0.51-1.0   | 1         | 4%      |
| 0.01-0.5   | 1         | 4%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 17        | 70.83%  |
| 2      | 6         | 25%     |
| 4      | 1         | 4.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 18        | 75%     |
| Yes       | 6         | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 79.17%  |
| No        | 5         | 20.83%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 95.83%  |
| No        | 1         | 4.17%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 7         | 29.17%  |
| Kazakhstan   | 3         | 12.5%   |
| South Africa | 2         | 8.33%   |
| Japan        | 2         | 8.33%   |
| France       | 2         | 8.33%   |
| Sweden       | 1         | 4.17%   |
| Spain        | 1         | 4.17%   |
| Serbia       | 1         | 4.17%   |
| Portugal     | 1         | 4.17%   |
| Mexico       | 1         | 4.17%   |
| Germany      | 1         | 4.17%   |
| Canada       | 1         | 4.17%   |
| Brazil       | 1         | 4.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ust-Kamenogorsk   | 2         | 8.33%   |
| Tsukuba           | 1         | 4.17%   |
| Skövde           | 1         | 4.17%   |
| Round Rock        | 1         | 4.17%   |
| Reno              | 1         | 4.17%   |
| Plainwell         | 1         | 4.17%   |
| Ōtsu             | 1         | 4.17%   |
| Oberstreit        | 1         | 4.17%   |
| Montreal          | 1         | 4.17%   |
| Mexico City       | 1         | 4.17%   |
| McKinney          | 1         | 4.17%   |
| Luxeuil-les-Bains | 1         | 4.17%   |
| Lisbon            | 1         | 4.17%   |
| League City       | 1         | 4.17%   |
| Karaganda         | 1         | 4.17%   |
| Johannesburg      | 1         | 4.17%   |
| Hayward           | 1         | 4.17%   |
| Fortaleza         | 1         | 4.17%   |
| Chessy            | 1         | 4.17%   |
| Cape Town         | 1         | 4.17%   |
| Belgrade          | 1         | 4.17%   |
| Algeciras         | 1         | 4.17%   |
| Abingdon          | 1         | 4.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 12     | 27.59%  |
| WDC                 | 4         | 4      | 13.79%  |
| Toshiba             | 2         | 2      | 6.9%    |
| SK hynix            | 2         | 2      | 6.9%    |
| SanDisk             | 2         | 2      | 6.9%    |
| HGST                | 2         | 2      | 6.9%    |
| Seagate             | 1         | 1      | 3.45%   |
| Plextor             | 1         | 1      | 3.45%   |
| Micron Technology   | 1         | 1      | 3.45%   |
| KIOXIA              | 1         | 1      | 3.45%   |
| Kingston            | 1         | 1      | 3.45%   |
| Intel               | 1         | 1      | 3.45%   |
| Hewlett-Packard     | 1         | 2      | 3.45%   |
| Gigabyte Technology | 1         | 1      | 3.45%   |
| Crucial             | 1         | 1      | 3.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD10SPZX-60Z10T0 1TB                | 2         | 6.25%   |
| WDC WD10JPVT-08A1YT2 1TB                | 1         | 3.13%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB      | 1         | 3.13%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 3.13%   |
| Toshiba MQ01ABF050 500GB                | 1         | 3.13%   |
| SK hynix HFM001TD3JX013N 1TB            | 1         | 3.13%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB | 1         | 3.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 3.13%   |
| SanDisk Ultra II 960GB SSD              | 1         | 3.13%   |
| SanDisk SDSSDA240G 240GB                | 1         | 3.13%   |
| Samsung SSD 980 PRO 500GB               | 1         | 3.13%   |
| Samsung SSD 980 PRO 2TB                 | 1         | 3.13%   |
| Samsung SSD 970 EVO Plus 2TB            | 1         | 3.13%   |
| Samsung SSD 970 EVO 2TB                 | 1         | 3.13%   |
| Samsung SSD 870 EVO 1TB                 | 1         | 3.13%   |
| Samsung SSD 860 EVO mSATA 500GB         | 1         | 3.13%   |
| Samsung NVMe SSD Drive 256GB            | 1         | 3.13%   |
| Samsung MZVLQ512HALU-000H1 512GB        | 1         | 3.13%   |
| Samsung MZVL21T0HCLR-00B00 1TB          | 1         | 3.13%   |
| Samsung MZVKW512HMJP-000H1 512GB        | 1         | 3.13%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD    | 1         | 3.13%   |
| Plextor PX-128M6S 128GB SSD             | 1         | 3.13%   |
| Micron 2210_MTFDHBA512QFD 512GB         | 1         | 3.13%   |
| KIOXIA KBG40ZNS256G NVMe 256GB          | 1         | 3.13%   |
| Kingston SUV400S37240G 240GB SSD        | 1         | 3.13%   |
| Intel SSDPEKKF256G7L 256GB              | 1         | 3.13%   |
| HGST HTS725050A7E630 500GB              | 1         | 3.13%   |
| HGST HTS545050A7E380 500GB              | 1         | 3.13%   |
| HP SSD EX950 2TB                        | 1         | 3.13%   |
| Gigabyte GP-GSTFS31240GNTD 240GB        | 1         | 3.13%   |
| Crucial CT500P2SSD8 500GB               | 1         | 3.13%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 37.5%   |
| Toshiba | 2         | 2      | 25%     |
| HGST    | 2         | 2      | 25%     |
| Seagate | 1         | 1      | 12.5%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 2         | 2      | 28.57%  |
| Samsung Electronics | 2         | 3      | 28.57%  |
| Plextor             | 1         | 1      | 14.29%  |
| Kingston            | 1         | 1      | 14.29%  |
| Gigabyte Technology | 1         | 1      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 14        | 18     | 48.28%  |
| HDD  | 8         | 8      | 27.59%  |
| SSD  | 7         | 8      | 24.14%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 14        | 18     | 51.85%  |
| SATA | 13        | 16     | 48.15%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 8         | 9      | 53.33%  |
| 0.51-1.0   | 7         | 7      | 46.67%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 8         | 33.33%  |
| 251-500        | 5         | 20.83%  |
| 101-250        | 5         | 20.83%  |
| 1001-2000      | 3         | 12.5%   |
| 1-20           | 2         | 8.33%   |
| More than 3000 | 1         | 4.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 101-250   | 8         | 33.33%  |
| 251-500   | 5         | 20.83%  |
| 1-20      | 4         | 16.67%  |
| 21-50     | 3         | 12.5%   |
| 501-1000  | 2         | 8.33%   |
| 1001-2000 | 1         | 4.17%   |
| 51-100    | 1         | 4.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 870 EVO 1TB | 1         | 1      | 25%     |
| Plextor PX-128M6S 128GB SSD         | 1         | 1      | 25%     |
| HGST HTS725050A7E630 500GB          | 1         | 1      | 25%     |
| HGST HTS545050A7E380 500GB          | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 2         | 2      | 50%     |
| Samsung Electronics | 1         | 1      | 25%     |
| Plextor             | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| HGST   | 2         | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 2      | 50%     |
| HDD  | 2         | 2      | 50%     |

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
| Works    | 21        | 27     | 77.78%  |
| Malfunc  | 4         | 4      | 14.81%  |
| Detected | 2         | 3      | 7.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 14        | 46.67%  |
| Samsung Electronics       | 6         | 20%     |
| AMD                       | 3         | 10%     |
| SK hynix                  | 2         | 6.67%   |
| SanDisk                   | 1         | 3.33%   |
| Micron/Crucial Technology | 1         | 3.33%   |
| Micron Technology         | 1         | 3.33%   |
| KIOXIA                    | 1         | 3.33%   |
| Biwin Storage Technology  | 1         | 3.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 12.9%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 9.68%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 9.68%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 9.68%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 6.45%   |
| SK hynix Gold P31 SSD                                                            | 1         | 3.23%   |
| SK hynix BC511                                                                   | 1         | 3.23%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 3.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 3.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 3.23%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 3.23%   |
| Micron Non-Volatile memory controller                                            | 1         | 3.23%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 3.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 3.23%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 3.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1         | 3.23%   |
| Intel SSD 600P Series                                                            | 1         | 3.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 3.23%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1         | 3.23%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 3.23%   |
| Biwin Storage Non-Volatile memory controller                                     | 1         | 3.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 14        | 46.67%  |
| SATA | 13        | 43.33%  |
| RAID | 3         | 10%     |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 21        | 87.5%   |
| AMD    | 3         | 12.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 12.5%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 8.33%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 4.17%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 4.17%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 4.17%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 4.17%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 4.17%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 4.17%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 4.17%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 4.17%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 4.17%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 4.17%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 4.17%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 4.17%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 4.17%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 4.17%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz       | 1         | 4.17%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 4.17%   |
| AMD Ryzen 9 4900HS with Radeon Graphics       | 1         | 4.17%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 4.17%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 4.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Other         | 7         | 29.17%  |
| Intel Core i7 | 6         | 25%     |
| Intel Core i5 | 5         | 20.83%  |
| AMD Ryzen 5   | 2         | 8.33%   |
| Intel Pentium | 1         | 4.17%   |
| Intel Core i3 | 1         | 4.17%   |
| Intel Celeron | 1         | 4.17%   |
| AMD Ryzen 9   | 1         | 4.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 9         | 37.5%   |
| 4      | 8         | 33.33%  |
| 8      | 6         | 25%     |
| 6      | 1         | 4.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 24        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 22        | 91.67%  |
| 1      | 2         | 8.33%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 24        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306a9    | 5         | 20.83%  |
| Unknown    | 4         | 16.67%  |
| 0x806d1    | 3         | 12.5%   |
| 0x806c1    | 3         | 12.5%   |
| 0xa0671    | 1         | 4.17%   |
| 0xa0652    | 1         | 4.17%   |
| 0x806ec    | 1         | 4.17%   |
| 0x806ea    | 1         | 4.17%   |
| 0x406e3    | 1         | 4.17%   |
| 0x406c4    | 1         | 4.17%   |
| 0x306d4    | 1         | 4.17%   |
| 0x08600106 | 1         | 4.17%   |
| 0x08108109 | 1         | 4.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| IvyBridge  | 5         | 20.83%  |
| KabyLake   | 4         | 16.67%  |
| Icelake    | 4         | 16.67%  |
| TigerLake  | 3         | 12.5%   |
| Zen 2      | 2         | 8.33%   |
| Zen+       | 1         | 4.17%   |
| Westmere   | 1         | 4.17%   |
| Skylake    | 1         | 4.17%   |
| Silvermont | 1         | 4.17%   |
| CometLake  | 1         | 4.17%   |
| Broadwell  | 1         | 4.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 16        | 53.33%  |
| Nvidia | 8         | 26.67%  |
| AMD    | 6         | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 10%     |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 10%     |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 6.67%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 6.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 6.67%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 6.67%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 6.67%   |
| AMD Renoir                                                                               | 2         | 6.67%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 3.33%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 3.33%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 3.33%   |
| Intel UHD Graphics 620                                                                   | 1         | 3.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 3.33%   |
| Intel HD Graphics 620                                                                    | 1         | 3.33%   |
| Intel HD Graphics 5500                                                                   | 1         | 3.33%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 3.33%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 3.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 3.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 3.33%   |
| AMD Chelsea XT GL [FirePro M4000]                                                        | 1         | 3.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 12        | 50%     |
| 1 x AMD        | 5         | 20.83%  |
| Intel + Nvidia | 4         | 16.67%  |
| 1 x Nvidia     | 2         | 8.33%   |
| AMD + Nvidia   | 1         | 4.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 21        | 87.5%   |
| Proprietary | 3         | 12.5%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 62.5%   |
| 0.51-1.0   | 3         | 12.5%   |
| 7.01-8.0   | 2         | 8.33%   |
| 0.01-0.5   | 2         | 8.33%   |
| 5.01-6.0   | 1         | 4.17%   |
| 1.01-2.0   | 1         | 4.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 8         | 29.63%  |
| LG Display          | 5         | 18.52%  |
| AU Optronics        | 4         | 14.81%  |
| Sharp               | 2         | 7.41%   |
| Hewlett-Packard     | 2         | 7.41%   |
| Chimei Innolux      | 2         | 7.41%   |
| Sony                | 1         | 3.7%    |
| Samsung Electronics | 1         | 3.7%    |
| PANDA               | 1         | 3.7%    |
| Dell                | 1         | 3.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Sony TV SNY8102 1360x768 1600x900mm 72.3-inch                        | 1         | 3.7%    |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch              | 1         | 3.7%    |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 1         | 3.7%    |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch | 1         | 3.7%    |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch              | 1         | 3.7%    |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch         | 1         | 3.7%    |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch         | 1         | 3.7%    |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch         | 1         | 3.7%    |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch          | 1         | 3.7%    |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch          | 1         | 3.7%    |
| Hewlett-Packard P223 HPN3392 1920x1080 477x268mm 21.5-inch           | 1         | 3.7%    |
| Hewlett-Packard 27m HPN3579 1920x1080 598x336mm 27.0-inch            | 1         | 3.7%    |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                     | 1         | 3.7%    |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch     | 1         | 3.7%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 1         | 3.7%    |
| BOE LCD Monitor BOE0A85 1920x1080 344x194mm 15.5-inch                | 1         | 3.7%    |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 1         | 3.7%    |
| BOE LCD Monitor BOE08F6 1920x1080 355x200mm 16.0-inch                | 1         | 3.7%    |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                | 1         | 3.7%    |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                | 1         | 3.7%    |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 1         | 3.7%    |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 1         | 3.7%    |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 1         | 3.7%    |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch       | 1         | 3.7%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch       | 1         | 3.7%    |
| AU Optronics LCD Monitor AUO309B 3840x2160 381x214mm 17.2-inch       | 1         | 3.7%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 1         | 3.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 14        | 56%     |
| 1366x768 (WXGA) | 7         | 28%     |
| 3840x2160 (4K)  | 1         | 4%      |
| 2256x1504       | 1         | 4%      |
| 1600x900 (HD+)  | 1         | 4%      |
| 1360x768        | 1         | 4%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 11        | 40.74%  |
| 13     | 4         | 14.81%  |
| 17     | 3         | 11.11%  |
| 14     | 3         | 11.11%  |
| 72     | 1         | 3.7%    |
| 27     | 1         | 3.7%    |
| 24     | 1         | 3.7%    |
| 21     | 1         | 3.7%    |
| 16     | 1         | 3.7%    |
| 12     | 1         | 3.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 62.96%  |
| 351-400     | 4         | 14.81%  |
| 501-600     | 2         | 7.41%   |
| 201-300     | 2         | 7.41%   |
| 401-500     | 1         | 3.7%    |
| 1501-2000   | 1         | 3.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 22        | 91.67%  |
| 3/2   | 1         | 4.17%   |
| 16/10 | 1         | 4.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 44.44%  |
| 81-90          | 7         | 25.93%  |
| 121-130        | 3         | 11.11%  |
| More than 1000 | 1         | 3.7%    |
| 61-70          | 1         | 3.7%    |
| 301-350        | 1         | 3.7%    |
| 251-300        | 1         | 3.7%    |
| 151-200        | 1         | 3.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 14        | 53.85%  |
| 101-120       | 7         | 26.92%  |
| 51-100        | 2         | 7.69%   |
| More than 240 | 1         | 3.85%   |
| 1-50          | 1         | 3.85%   |
| 161-240       | 1         | 3.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 20        | 83.33%  |
| 2     | 4         | 16.67%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 18        | 50%     |
| Realtek Semiconductor | 14        | 38.89%  |
| Ralink Technology     | 1         | 2.78%   |
| Qualcomm Atheros      | 1         | 2.78%   |
| Hewlett-Packard       | 1         | 2.78%   |
| Broadcom Limited      | 1         | 2.78%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 24.44%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 6.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 6.67%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 4.44%   |
| Intel Wireless 8265 / 8275                                        | 2         | 4.44%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 4.44%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 4.44%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 4.44%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 4.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 4.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.22%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 2.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.22%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.22%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 2.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 2.22%   |
| Intel Wireless 3165                                               | 1         | 2.22%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 2.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 2.22%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 2.22%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 2.22%   |
| HP hs2350 HSPA+ MobileBroadband                                   | 1         | 2.22%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                           | 1         | 2.22%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 18        | 75%     |
| Realtek Semiconductor | 3         | 12.5%   |
| Ralink Technology     | 1         | 4.17%   |
| Qualcomm Atheros      | 1         | 4.17%   |
| Broadcom Limited      | 1         | 4.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                   | 3         | 12.5%   |
| Intel Wireless 8265 / 8275                               | 2         | 8.33%   |
| Intel Wi-Fi 6 AX201                                      | 2         | 8.33%   |
| Intel Wi-Fi 6 AX200                                      | 2         | 8.33%   |
| Intel Tiger Lake PCH CNVi WiFi                           | 2         | 8.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]             | 2         | 8.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter | 1         | 4.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter | 1         | 4.17%   |
| Realtek RTL8723DE Wireless Network Adapter               | 1         | 4.17%   |
| Ralink MT7601U Wireless Adapter                          | 1         | 4.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter         | 1         | 4.17%   |
| Intel Wireless 3165                                      | 1         | 4.17%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth          | 1         | 4.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                        | 1         | 4.17%   |
| Intel Comet Lake PCH CNVi WiFi                           | 1         | 4.17%   |
| Intel Centrino Ultimate-N 6300                           | 1         | 4.17%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                  | 1         | 4.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 14        | 73.68%  |
| Intel                 | 5         | 26.32%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 55%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 15%     |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 10%     |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 10%     |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 5%      |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 5%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 24        | 54.55%  |
| Ethernet | 19        | 43.18%  |
| Modem    | 1         | 2.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 21        | 77.78%  |
| Ethernet | 6         | 22.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 18        | 75%     |
| 1     | 6         | 25%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 22        | 91.67%  |
| Yes  | 2         | 8.33%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 15        | 65.22%  |
| Broadcom              | 4         | 17.39%  |
| Realtek Semiconductor | 3         | 13.04%  |
| Foxconn / Hon Hai     | 1         | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                           | 5         | 21.74%  |
| Intel Bluetooth wireless interface              | 4         | 17.39%  |
| Intel AX210 Bluetooth                           | 3         | 13.04%  |
| Realtek  Bluetooth 4.2 Adapter                  | 2         | 8.7%    |
| Intel AX200 Bluetooth                           | 2         | 8.7%    |
| Realtek Bluetooth Radio                         | 1         | 4.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)  | 1         | 4.35%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller | 1         | 4.35%   |
| Broadcom HP Portable SoftSailing                | 1         | 4.35%   |
| Broadcom BCM20702A0 Bluetooth 4.0               | 1         | 4.35%   |
| Broadcom BCM20702A0                             | 1         | 4.35%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]      | 1         | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 21        | 58.33%  |
| Nvidia              | 8         | 22.22%  |
| AMD                 | 6         | 16.67%  |
| C-Media Electronics | 1         | 2.78%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 12.82%  |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 10.26%  |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 7.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 7.69%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 7.69%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 7.69%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 5.13%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 5.13%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 5.13%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 2.56%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 2.56%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 2.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 2.56%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 2.56%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 2.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 2.56%   |
| C-Media Electronics CM6631A Audio Processor                                                       | 1         | 2.56%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 2.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 2.56%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 2.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 6         | 23.08%  |
| Kingston            | 5         | 19.23%  |
| Samsung Electronics | 4         | 15.38%  |
| Micron Technology   | 3         | 11.54%  |
| Crucial             | 3         | 11.54%  |
| Neo Forza           | 1         | 3.85%   |
| Nanya Technology    | 1         | 3.85%   |
| Essencore Limited   | 1         | 3.85%   |
| Corsair             | 1         | 3.85%   |
| A-DATA Technology   | 1         | 3.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s               | 1         | 3.57%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s               | 1         | 3.57%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s               | 1         | 3.57%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s               | 1         | 3.57%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s               | 1         | 3.57%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s               | 1         | 3.57%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8192MB Row Of Chips LPDDR3 1867MT/s  | 1         | 3.57%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s                | 1         | 3.57%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s                | 1         | 3.57%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                | 1         | 3.57%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s                | 1         | 3.57%   |
| Neo Forza RAM NMSO480E82-3200E 8GB SODIMM DDR4 3200MT/s              | 1         | 3.57%   |
| Nanya RAM NT4GC64C88B1NS-DI 4096MB SODIMM DDR3 1600MT/s              | 1         | 3.57%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                 | 1         | 3.57%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                 | 1         | 3.57%   |
| Micron RAM 16KTF51264HZ-1G4 4096MB SODIMM DDR3 701MT/s               | 1         | 3.57%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                     | 1         | 3.57%   |
| Kingston RAM KKRVFX-MIE 8192MB SODIMM DDR4 3200MT/s                  | 1         | 3.57%   |
| Kingston RAM CL15-15-15 D4-2133 4096MB SODIMM DDR4 2133MT/s          | 1         | 3.57%   |
| Kingston RAM 9905712-007.A00G 16384MB SODIMM DDR4 2400MT/s           | 1         | 3.57%   |
| Kingston RAM 9905711-032.A00G 8192MB SODIMM DDR4 2667MT/s            | 1         | 3.57%   |
| Kingston RAM 9905703-011.A00G 16GB SODIMM DDR4 2400MT/s              | 1         | 3.57%   |
| Essencore Limited RAM KD4AGSA8M-26N1900 16384MB SODIMM DDR4 2667MT/s | 1         | 3.57%   |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s            | 1         | 3.57%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s              | 1         | 3.57%   |
| Crucial RAM BL8G32C16S4B.8FE 8GB SODIMM DDR4 2667MT/s                | 1         | 3.57%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s            | 1         | 3.57%   |
| A-DATA RAM AO1L16BC4R1-BX7S 4096MB SODIMM DDR3 1600MT/s              | 1         | 3.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 14        | 63.64%  |
| DDR3   | 7         | 31.82%  |
| LPDDR3 | 1         | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 21        | 95.45%  |
| Row Of Chips | 1         | 4.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 12        | 46.15%  |
| 4096  | 10        | 38.46%  |
| 16384 | 3         | 11.54%  |
| 32768 | 1         | 3.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 8         | 32%     |
| 1600  | 7         | 28%     |
| 2667  | 4         | 16%     |
| 2400  | 2         | 8%      |
| 2133  | 1         | 4%      |
| 1867  | 1         | 4%      |
| 1333  | 1         | 4%      |
| 701   | 1         | 4%      |

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
| Acer                                   | 7         | 28%     |
| Chicony Electronics                    | 6         | 24%     |
| Microdia                               | 4         | 16%     |
| Realtek Semiconductor                  | 2         | 8%      |
| Syntek                                 | 1         | 4%      |
| Samsung Electronics                    | 1         | 4%      |
| Quanta                                 | 1         | 4%      |
| Luxvisions Innotech Limited            | 1         | 4%      |
| Logitech                               | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) | 1         | 4%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Acer HD Webcam                                                 | 3         | 12%     |
| Acer BisonCam,NB Pro                                           | 2         | 8%      |
| Syntek USB2.0 Camera                                           | 1         | 4%      |
| Samsung Galaxy A5 (MTP)                                        | 1         | 4%      |
| Realtek Laptop Camera                                          | 1         | 4%      |
| Realtek EasyCamera                                             | 1         | 4%      |
| Quanta HP Webcam                                               | 1         | 4%      |
| Microdia Laptop_Integrated_Webcam_2M                           | 1         | 4%      |
| Microdia Integrated_Webcam_HD                                  | 1         | 4%      |
| Microdia Integrated Webcam                                     | 1         | 4%      |
| Microdia Dell Integrated HD Webcam                             | 1         | 4%      |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 1         | 4%      |
| Logitech C920 PRO HD Webcam                                    | 1         | 4%      |
| Chicony Web Camera - FHD                                       | 1         | 4%      |
| Chicony Integrated Camera [ThinkPad]                           | 1         | 4%      |
| Chicony Integrated Camera                                      | 1         | 4%      |
| Chicony HP TrueVision HD Camera                                | 1         | 4%      |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 4%      |
| Chicony HP HD Camera                                           | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 4%      |
| Acer ThinkPad Integrated Camera                                | 1         | 4%      |
| Acer Integrated Camera                                         | 1         | 4%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 50%     |
| Synaptics        | 2         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 2         | 50%     |
| Validity Sensors VFS300 Fingerprint Reader | 1         | 25%     |
| Validity Sensors Synaptics WBDI            | 1         | 25%     |

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
| 0     | 16        | 66.67%  |
| 1     | 7         | 29.17%  |
| 2     | 1         | 4.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 4         | 44.44%  |
| Multimedia controller | 2         | 22.22%  |
| Net/wireless          | 1         | 11.11%  |
| Graphics card         | 1         | 11.11%  |
| Bluetooth             | 1         | 11.11%  |

