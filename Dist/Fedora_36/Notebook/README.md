Fedora 36 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 36.

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

Total: 25

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [4c0c1422e7](https://linux-hardware.org/?probe=4c0c1422e7) | Mar 31, 2022 |
| Lenovo        | ThinkPad X260 20F5S0HK1J    | [a83d3cbe5f](https://linux-hardware.org/?probe=a83d3cbe5f) | Mar 31, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [cc95f0e3ab](https://linux-hardware.org/?probe=cc95f0e3ab) | Mar 31, 2022 |
| VALE          | Notebook Slim S132          | [138a4f1d68](https://linux-hardware.org/?probe=138a4f1d68) | Mar 31, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | [05c02cbe41](https://linux-hardware.org/?probe=05c02cbe41) | Mar 31, 2022 |
| Avell High... | B.ON                        | [697fc1d4ec](https://linux-hardware.org/?probe=697fc1d4ec) | Mar 29, 2022 |
| Framework     | Laptop                      | [a22656afee](https://linux-hardware.org/?probe=a22656afee) | Mar 28, 2022 |
| Dell          | XPS 17 9710                 | [461d175c44](https://linux-hardware.org/?probe=461d175c44) | Mar 28, 2022 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [16ac712c84](https://linux-hardware.org/?probe=16ac712c84) | Mar 24, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [1b57f1f410](https://linux-hardware.org/?probe=1b57f1f410) | Mar 13, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [917a6b65a8](https://linux-hardware.org/?probe=917a6b65a8) | Mar 10, 2022 |
| Sony          | VGN-FW21E                   | [930ce5581f](https://linux-hardware.org/?probe=930ce5581f) | Feb 25, 2022 |
| Unknown       | Unknown                     | [033354ee53](https://linux-hardware.org/?probe=033354ee53) | Jan 02, 2022 |
| Unknown       | Unknown                     | [809200ad60](https://linux-hardware.org/?probe=809200ad60) | Jan 02, 2022 |
| Unknown       | Unknown                     | [ea795a97e1](https://linux-hardware.org/?probe=ea795a97e1) | Dec 26, 2021 |
| Unknown       | Unknown                     | [2b26e185d0](https://linux-hardware.org/?probe=2b26e185d0) | Dec 06, 2021 |
| Unknown       | Unknown                     | [f09a7c7125](https://linux-hardware.org/?probe=f09a7c7125) | Dec 06, 2021 |
| Positivo      | CHT12CP                     | [53054c8f7a](https://linux-hardware.org/?probe=53054c8f7a) | Nov 20, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | [1734da4566](https://linux-hardware.org/?probe=1734da4566) | Nov 13, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [2da0673527](https://linux-hardware.org/?probe=2da0673527) | Nov 01, 2021 |
| Notebook      | PCx0Dx                      | [b1a527acdc](https://linux-hardware.org/?probe=b1a527acdc) | Oct 11, 2021 |
| Notebook      | PCx0Dx                      | [90d4556fdf](https://linux-hardware.org/?probe=90d4556fdf) | Oct 11, 2021 |
| Unknown       | Unknown                     | [af4bbffabf](https://linux-hardware.org/?probe=af4bbffabf) | Sep 27, 2021 |
| Unknown       | Unknown                     | [81fd834473](https://linux-hardware.org/?probe=81fd834473) | Sep 26, 2021 |
| HP            | ProBook 4740s               | [77b2eed991](https://linux-hardware.org/?probe=77b2eed991) | Sep 22, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                       | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| 5.17.1-300.fc36.x86_64                                        | 5         | 26.32%  |
| 5.17.0-0.rc7.116.fc36.x86_64                                  | 3         | 15.79%  |
| 5.17.0-300.fc36.x86_64                                        | 2         | 10.53%  |
| 5.17.0-0.rc5.102.fc36.x86_64                                  | 2         | 10.53%  |
| 5.16.0-0.rc7.20211231git4f3d93c6eaff.52.vanilla.1.fc36.x86_64 | 1         | 5.26%   |
| 5.15.0-0.rc7.20211028git1fc596a56b33.56.fc36.x86_64           | 1         | 5.26%   |
| 5.15.0-0.rc4.20211008git1da38549dd64.36.fc36.x86_64           | 1         | 5.26%   |
| 5.15.0-0.rc2.20210923git58e2cf5d7946.21.vanilla.1.fc36.x86_64 | 1         | 5.26%   |
| 5.15.0-0.rc2.18.fc36.x86_64                                   | 1         | 5.26%   |
| 5.14.14-300.fc35.x86_64                                       | 1         | 5.26%   |
| 5.14.10-300.fc35.x86_64                                       | 1         | 5.26%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17.0  | 7         | 36.84%  |
| 5.17.1  | 5         | 26.32%  |
| 5.15.0  | 4         | 21.05%  |
| 5.16.0  | 1         | 5.26%   |
| 5.14.14 | 1         | 5.26%   |
| 5.14.10 | 1         | 5.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17    | 12        | 63.16%  |
| 5.15    | 4         | 21.05%  |
| 5.14    | 2         | 10.53%  |
| 5.16    | 1         | 5.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 18        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GNOME   | 14        | 73.68%  |
| KDE5    | 3         | 15.79%  |
| Unknown | 2         | 10.53%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 13        | 72.22%  |
| X11     | 4         | 22.22%  |
| Unknown | 1         | 5.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 8         | 44.44%  |
| Unknown | 6         | 33.33%  |
| SDDM    | 3         | 16.67%  |
| LightDM | 1         | 5.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 9         | 50%     |
| pl_PL | 2         | 11.11%  |
| en_GB | 2         | 11.11%  |
| de_DE | 2         | 11.11%  |
| pt_PT | 1         | 5.56%   |
| pt_BR | 1         | 5.56%   |
| hr_HR | 1         | 5.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 16        | 88.89%  |
| BIOS | 2         | 11.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 13        | 72.22%  |
| Ext4  | 5         | 27.78%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 11        | 57.89%  |
| Unknown | 7         | 36.84%  |
| MBR     | 1         | 5.26%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 16        | 88.89%  |
| Yes       | 2         | 11.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 11        | 61.11%  |
| Yes       | 7         | 38.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 7         | 38.89%  |
| Hewlett-Packard        | 2         | 11.11%  |
| VALE                   | 1         | 5.56%   |
| Sony                   | 1         | 5.56%   |
| Positivo               | 1         | 5.56%   |
| Notebook               | 1         | 5.56%   |
| Framework              | 1         | 5.56%   |
| Dell                   | 1         | 5.56%   |
| Avell High Performance | 1         | 5.56%   |
| ASUSTek Computer       | 1         | 5.56%   |
| Unknown                | 1         | 5.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| VALE Notebook Slim S132                     | 1         | 5.56%   |
| Sony VGN-FW21E                              | 1         | 5.56%   |
| Positivo CHT12CP                            | 1         | 5.56%   |
| Notebook PCx0Dx                             | 1         | 5.56%   |
| Lenovo ThinkPad X260 20F5S0HK1J             | 1         | 5.56%   |
| Lenovo ThinkPad P15 Gen 1 20STS0J500        | 1         | 5.56%   |
| Lenovo ThinkPad L13 Gen 2 20VJS0HB00        | 1         | 5.56%   |
| Lenovo ThinkBook 15 G2 ITL 20VE             | 1         | 5.56%   |
| Lenovo ThinkBook 14 G3 ACL 21A2             | 1         | 5.56%   |
| Lenovo IdeaPadFlex 14 20308                 | 1         | 5.56%   |
| Lenovo IdeaPad 530S-14ARR 81H1              | 1         | 5.56%   |
| HP ZBook Fury 15 G7 Mobile Workstation      | 1         | 5.56%   |
| HP ProBook 4740s                            | 1         | 5.56%   |
| Framework Laptop                            | 1         | 5.56%   |
| Dell XPS 17 9710                            | 1         | 5.56%   |
| Avell High Performance B.ON                 | 1         | 5.56%   |
| ASUS ROG Zephyrus Duo 15 SE GX551QS_GX551QS | 1         | 5.56%   |
| Unknown                                     | 1         | 5.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 3         | 16.67%  |
| Lenovo ThinkBook            | 2         | 11.11%  |
| VALE Notebook               | 1         | 5.56%   |
| Sony VGN-FW21E              | 1         | 5.56%   |
| Positivo CHT12CP            | 1         | 5.56%   |
| Notebook PCx0Dx             | 1         | 5.56%   |
| Lenovo IdeaPadFlex          | 1         | 5.56%   |
| Lenovo IdeaPad              | 1         | 5.56%   |
| HP ZBook                    | 1         | 5.56%   |
| HP ProBook                  | 1         | 5.56%   |
| Framework Laptop            | 1         | 5.56%   |
| Dell XPS                    | 1         | 5.56%   |
| Avell High Performance B.ON | 1         | 5.56%   |
| ASUS ROG                    | 1         | 5.56%   |
| Unknown                     | 1         | 5.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 7         | 38.89%  |
| 2020 | 4         | 22.22%  |
| 2018 | 2         | 11.11%  |
| 2017 | 1         | 5.56%   |
| 2016 | 1         | 5.56%   |
| 2013 | 1         | 5.56%   |
| 2012 | 1         | 5.56%   |
| 2008 | 1         | 5.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 18        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 13        | 72.22%  |
| Enabled  | 5         | 27.78%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 18        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 5         | 27.78%  |
| 3.01-4.0    | 5         | 27.78%  |
| 8.01-16.0   | 3         | 16.67%  |
| 4.01-8.0    | 2         | 11.11%  |
| 16.01-24.0  | 2         | 11.11%  |
| 64.01-256.0 | 1         | 5.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 3.01-4.0 | 8         | 42.11%  |
| 2.01-3.0 | 7         | 36.84%  |
| 4.01-8.0 | 4         | 21.05%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 13        | 68.42%  |
| 2      | 4         | 21.05%  |
| 3      | 2         | 10.53%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 16        | 88.89%  |
| Yes       | 2         | 11.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 12        | 66.67%  |
| No        | 6         | 33.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 17        | 94.44%  |
| No        | 1         | 5.56%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 14        | 77.78%  |
| No        | 4         | 22.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| UK         | 4         | 22.22%  |
| USA        | 2         | 11.11%  |
| Poland     | 2         | 11.11%  |
| Brazil     | 2         | 11.11%  |
| Uzbekistan | 1         | 5.56%   |
| Turkey     | 1         | 5.56%   |
| Romania    | 1         | 5.56%   |
| Norway     | 1         | 5.56%   |
| Latvia     | 1         | 5.56%   |
| Germany    | 1         | 5.56%   |
| Croatia    | 1         | 5.56%   |
| Austria    | 1         | 5.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Zagreb                    | 1         | 5.56%   |
| Warsaw                    | 1         | 5.56%   |
| Warrington                | 1         | 5.56%   |
| Vegarshei                 | 1         | 5.56%   |
| Trzciel                   | 1         | 5.56%   |
| Tashkent                  | 1         | 5.56%   |
| Solihull                  | 1         | 5.56%   |
| Sao Paulo                 | 1         | 5.56%   |
| Riga                      | 1         | 5.56%   |
| Newport                   | 1         | 5.56%   |
| Kasten bei Boeheimkirchen | 1         | 5.56%   |
| Joinville                 | 1         | 5.56%   |
| Istanbul                  | 1         | 5.56%   |
| Halstead                  | 1         | 5.56%   |
| Fort Collins              | 1         | 5.56%   |
| Bucharest                 | 1         | 5.56%   |
| Berlin                    | 1         | 5.56%   |
| Beaverton                 | 1         | 5.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 7      | 21.74%  |
| WDC                 | 2         | 2      | 8.7%    |
| Unknown             | 2         | 4      | 8.7%    |
| Kingston            | 2         | 4      | 8.7%    |
| Transcend           | 1         | 1      | 4.35%   |
| Toshiba             | 1         | 1      | 4.35%   |
| SK Hynix            | 1         | 1      | 4.35%   |
| Seagate             | 1         | 1      | 4.35%   |
| SanDisk             | 1         | 1      | 4.35%   |
| PNY                 | 1         | 2      | 4.35%   |
| Leven               | 1         | 1      | 4.35%   |
| KIOXIA              | 1         | 1      | 4.35%   |
| Hitachi             | 1         | 1      | 4.35%   |
| Fujitsu             | 1         | 1      | 4.35%   |
| A-DATA Technology   | 1         | 1      | 4.35%   |
| Unknown             | 1         | 1      | 4.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 1TB           | 2         | 8.33%   |
| WDC WDS500G1X0E-00AFY0 500GB         | 1         | 4.17%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 1         | 4.17%   |
| Unknown MMC64G  64GB                 | 1         | 4.17%   |
| Unknown MMC Card  64GB               | 1         | 4.17%   |
| Transcend TS240GMTS420S 240GB SSD    | 1         | 4.17%   |
| Toshiba NVMe SSD Drive 512GB         | 1         | 4.17%   |
| SK Hynix HFM256GDHTNG-8310A 256GB    | 1         | 4.17%   |
| Seagate Expansion 320GB              | 1         | 4.17%   |
| SanDisk DF4032  32GB                 | 1         | 4.17%   |
| Samsung SSD 860 EVO 250GB            | 1         | 4.17%   |
| Samsung NVMe SSD Drive 500GB         | 1         | 4.17%   |
| Samsung NVMe SSD Drive 1024GB        | 1         | 4.17%   |
| Samsung MZALQ512HBLU-00BL2 512GB     | 1         | 4.17%   |
| PNY CS3040 4TB SSD                   | 1         | 4.17%   |
| Leven JAJS600M256C 256GB             | 1         | 4.17%   |
| KIOXIA KXG60ZNV1T02 1TB              | 1         | 4.17%   |
| Kingston SUV500MS240G 240GB SSD      | 1         | 4.17%   |
| Kingston SA400S37960G 960GB SSD      | 1         | 4.17%   |
| Hitachi HTS543232A7A384 320GB        | 1         | 4.17%   |
| Fujitsu MJA2500BH G1 500GB           | 1         | 4.17%   |
| A-DATA IM2P33F8ABR1-256GB            | 1         | 4.17%   |
| Unknown                              | 1         | 4.17%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 33.33%  |
| Hitachi | 1         | 1      | 33.33%  |
| Fujitsu | 1         | 1      | 33.33%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 2         | 4      | 40%     |
| Transcend           | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| Leven               | 1         | 1      | 20%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 11        | 14     | 50%     |
| MMC  | 4         | 6      | 18.18%  |
| SSD  | 4         | 7      | 18.18%  |
| HDD  | 3         | 3      | 13.64%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 11        | 14     | 50%     |
| SATA | 6         | 9      | 27.27%  |
| MMC  | 4         | 6      | 18.18%  |
| SAS  | 1         | 1      | 4.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 5         | 9      | 83.33%  |
| 0.51-1.0   | 1         | 1      | 16.67%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 5         | 27.78%  |
| 101-250    | 4         | 22.22%  |
| 251-500    | 3         | 16.67%  |
| 1001-2000  | 2         | 11.11%  |
| 501-1000   | 2         | 11.11%  |
| 51-100     | 2         | 11.11%  |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 10        | 55.56%  |
| 51-100   | 4         | 22.22%  |
| 21-50    | 2         | 11.11%  |
| 251-500  | 1         | 5.56%   |
| 501-1000 | 1         | 5.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                      | Notebooks | Drives | Percent |
|----------------------------|-----------|--------|---------|
| Fujitsu MJA2500BH G1 500GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Fujitsu | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Fujitsu | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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
| Detected | 10        | 18     | 47.62%  |
| Works    | 10        | 11     | 47.62%  |
| Malfunc  | 1         | 1      | 4.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 9         | 42.86%  |
| Samsung Electronics          | 4         | 19.05%  |
| Toshiba America Info Systems | 2         | 9.52%   |
| Sandisk                      | 2         | 9.52%   |
| SK Hynix                     | 1         | 4.76%   |
| Phison Electronics           | 1         | 4.76%   |
| AMD                          | 1         | 4.76%   |
| ADATA Technology             | 1         | 4.76%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Toshiba America Info Systems XG6 NVMe SSD Controller                     | 2         | 8.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                            | 2         | 8.7%    |
| Samsung NVMe SSD Controller 980                                          | 2         | 8.7%    |
| Intel Volume Management Device NVMe RAID Controller                      | 2         | 8.7%    |
| SK Hynix BC501 NVMe Solid State Drive                                    | 1         | 4.35%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                               | 1         | 4.35%   |
| Sandisk Non-Volatile memory controller                                   | 1         | 4.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                           | 1         | 4.35%   |
| Phison E16 PCIe4 NVMe Controller                                         | 1         | 4.35%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                          | 1         | 4.35%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                       | 1         | 4.35%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                   | 1         | 4.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller | 1         | 4.35%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]    | 1         | 4.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                             | 1         | 4.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]         | 1         | 4.35%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                     | 1         | 4.35%   |
| AMD FCH SATA Controller [AHCI mode]                                      | 1         | 4.35%   |
| ADATA Non-Volatile memory controller                                     | 1         | 4.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 11        | 50%     |
| SATA | 9         | 40.91%  |
| RAID | 2         | 9.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 15        | 83.33%  |
| AMD    | 3         | 16.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 16.67%  |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 5.56%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 5.56%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 5.56%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 5.56%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 5.56%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 5.56%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 1         | 5.56%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 5.56%   |
| Intel Celeron CPU J3455 @ 1.50GHz             | 1         | 5.56%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 5.56%   |
| Intel 11th Gen Core i9-11900H @ 2.50GHz       | 1         | 5.56%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 5.56%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1         | 5.56%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 5.56%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 5.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Other            | 5         | 27.78%  |
| Intel Core i7    | 4         | 22.22%  |
| Intel Celeron    | 2         | 11.11%  |
| Intel Pentium    | 1         | 5.56%   |
| Intel Core i5    | 1         | 5.56%   |
| Intel Core 2 Duo | 1         | 5.56%   |
| Intel Atom       | 1         | 5.56%   |
| AMD Ryzen 9      | 1         | 5.56%   |
| AMD Ryzen 7      | 1         | 5.56%   |
| AMD Ryzen 5      | 1         | 5.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 8         | 44.44%  |
| 8      | 5         | 27.78%  |
| 2      | 4         | 22.22%  |
| 6      | 1         | 5.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 18        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 13        | 72.22%  |
| 1      | 5         | 27.78%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 18        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 4         | 22.22%  |
| 0xa0652    | 3         | 16.67%  |
| 0x806d1    | 1         | 5.56%   |
| 0x706a8    | 1         | 5.56%   |
| 0x506c9    | 1         | 5.56%   |
| 0x406e3    | 1         | 5.56%   |
| 0x406c4    | 1         | 5.56%   |
| 0x40651    | 1         | 5.56%   |
| 0x306a9    | 1         | 5.56%   |
| 0x10676    | 1         | 5.56%   |
| 0x0a50000c | 1         | 5.56%   |
| 0x08608103 | 1         | 5.56%   |
| 0x0810100b | 1         | 5.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| TigerLake     | 4         | 22.22%  |
| CometLake     | 3         | 16.67%  |
| Zen 3         | 1         | 5.56%   |
| Zen           | 1         | 5.56%   |
| Skylake       | 1         | 5.56%   |
| Silvermont    | 1         | 5.56%   |
| Penryn        | 1         | 5.56%   |
| IvyBridge     | 1         | 5.56%   |
| Icelake       | 1         | 5.56%   |
| Haswell       | 1         | 5.56%   |
| Goldmont plus | 1         | 5.56%   |
| Goldmont      | 1         | 5.56%   |
| Unknown       | 1         | 5.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 14        | 58.33%  |
| Nvidia | 5         | 20.83%  |
| AMD    | 5         | 20.83%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 16.67%  |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 12.5%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 2         | 8.33%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 8.33%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 1         | 4.17%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 4.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 4.17%   |
| Intel HD Graphics 500                                                                    | 1         | 4.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 4.17%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 4.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 4.17%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 4.17%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 4.17%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 1         | 4.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 4.17%   |
| AMD Lucienne                                                                             | 1         | 4.17%   |
| AMD Cezanne                                                                              | 1         | 4.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 9         | 50%     |
| Intel + Nvidia | 4         | 22.22%  |
| 1 x AMD        | 3         | 16.67%  |
| Intel + AMD    | 1         | 5.56%   |
| AMD + Nvidia   | 1         | 5.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 16        | 84.21%  |
| Proprietary | 2         | 10.53%  |
| Unknown     | 1         | 5.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 11        | 61.11%  |
| 0.01-0.5   | 3         | 16.67%  |
| 3.01-4.0   | 2         | 11.11%  |
| 1.01-2.0   | 2         | 11.11%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| BOE                  | 4         | 22.22%  |
| LG Display           | 3         | 16.67%  |
| Sharp                | 2         | 11.11%  |
| InfoVision           | 2         | 11.11%  |
| Chimei Innolux       | 2         | 11.11%  |
| AU Optronics         | 2         | 11.11%  |
| Ancor Communications | 2         | 11.11%  |
| Samsung Electronics  | 1         | 5.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch              | 1         | 5.26%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch              | 1         | 5.26%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch    | 1         | 5.26%   |
| Samsung Electronics LCD Monitor SEC3554 1600x900 382x215mm 17.3-inch | 1         | 5.26%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch         | 1         | 5.26%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch         | 1         | 5.26%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch          | 1         | 5.26%   |
| InfoVision LCD Monitor IVO3D40 1920x1080 344x194mm 15.5-inch         | 1         | 5.26%   |
| InfoVision LCD Monitor IVO0536 1920x1080 294x165mm 13.3-inch         | 1         | 5.26%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch     | 1         | 5.26%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch     | 1         | 5.26%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 1         | 5.26%   |
| BOE LCD Monitor BOE0922 1920x550                                     | 1         | 5.26%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                | 1         | 5.26%   |
| BOE LCD Monitor BOE08F5 1920x1080 344x194mm 15.5-inch                | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch        | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO103C 1366x768 309x173mm 13.9-inch        | 1         | 5.26%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch     | 1         | 5.26%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch     | 1         | 5.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 11        | 61.11%  |
| 1366x768 (WXGA) | 3         | 16.67%  |
| 3840x2400       | 1         | 5.56%   |
| 2256x1504       | 1         | 5.56%   |
| 1920x550        | 1         | 5.56%   |
| 1600x900 (HD+)  | 1         | 5.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 6         | 31.58%  |
| 13      | 4         | 21.05%  |
| 24      | 2         | 10.53%  |
| 17      | 2         | 10.53%  |
| 23      | 1         | 5.26%   |
| 14      | 1         | 5.26%   |
| 12      | 1         | 5.26%   |
| 11      | 1         | 5.26%   |
| Unknown | 1         | 5.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 9         | 47.37%  |
| 201-300     | 4         | 21.05%  |
| 501-600     | 3         | 15.79%  |
| 351-400     | 2         | 10.53%  |
| Unknown     | 1         | 5.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 14        | 82.35%  |
| 32/9  | 1         | 5.88%   |
| 3/2   | 1         | 5.88%   |
| 16/10 | 1         | 5.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 6         | 31.58%  |
| 81-90          | 4         | 21.05%  |
| 201-250        | 3         | 15.79%  |
| 121-130        | 2         | 10.53%  |
| 71-80          | 1         | 5.26%   |
| 61-70          | 1         | 5.26%   |
| 51-60          | 1         | 5.26%   |
| Unknown        | 1         | 5.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 10        | 52.63%  |
| 51-100        | 3         | 15.79%  |
| 161-240       | 2         | 10.53%  |
| 101-120       | 2         | 10.53%  |
| More than 240 | 1         | 5.26%   |
| Unknown       | 1         | 5.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 14        | 73.68%  |
| 2     | 3         | 15.79%  |
| 0     | 2         | 10.53%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 14        | 53.85%  |
| Realtek Semiconductor    | 8         | 30.77%  |
| Qualcomm Atheros         | 2         | 7.69%   |
| Marvell Technology Group | 1         | 3.85%   |
| Belkin Components        | 1         | 3.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 6         | 18.75%  |
| Intel Wi-Fi 6 AX201                                                | 3         | 9.38%   |
| Intel Comet Lake PCH CNVi WiFi                                     | 3         | 9.38%   |
| Intel Wi-Fi 6 AX200                                                | 2         | 6.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 1         | 3.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 1         | 3.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 1         | 3.13%   |
| Realtek 802.11n                                                    | 1         | 3.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 1         | 3.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 1         | 3.13%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller            | 1         | 3.13%   |
| Intel Wireless 8260                                                | 1         | 3.13%   |
| Intel Wireless 7260                                                | 1         | 3.13%   |
| Intel Wireless 3165                                                | 1         | 3.13%   |
| Intel WiFi Link 5100                                               | 1         | 3.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 1         | 3.13%   |
| Intel Tiger Lake PCH CNVi WiFi                                     | 1         | 3.13%   |
| Intel Ethernet Connection I219-LM                                  | 1         | 3.13%   |
| Intel Ethernet Connection (13) I219-V                              | 1         | 3.13%   |
| Intel Ethernet Connection (11) I219-LM                             | 1         | 3.13%   |
| Intel Ethernet Connection (10) I219-LM                             | 1         | 3.13%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B] | 1         | 3.13%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 14        | 73.68%  |
| Realtek Semiconductor | 2         | 10.53%  |
| Qualcomm Atheros      | 2         | 10.53%  |
| Belkin Components     | 1         | 5.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                | 3         | 15.79%  |
| Intel Comet Lake PCH CNVi WiFi                                     | 3         | 15.79%  |
| Intel Wi-Fi 6 AX200                                                | 2         | 10.53%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 1         | 5.26%   |
| Realtek 802.11n                                                    | 1         | 5.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 1         | 5.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 1         | 5.26%   |
| Intel Wireless 8260                                                | 1         | 5.26%   |
| Intel Wireless 7260                                                | 1         | 5.26%   |
| Intel Wireless 3165                                                | 1         | 5.26%   |
| Intel WiFi Link 5100                                               | 1         | 5.26%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 1         | 5.26%   |
| Intel Tiger Lake PCH CNVi WiFi                                     | 1         | 5.26%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B] | 1         | 5.26%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 7         | 58.33%  |
| Intel                    | 4         | 33.33%  |
| Marvell Technology Group | 1         | 8.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 46.15%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 7.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 7.69%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 7.69%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 7.69%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 7.69%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 7.69%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 7.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 17        | 58.62%  |
| Ethernet | 12        | 41.38%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 16        | 80%     |
| Ethernet | 4         | 20%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 12        | 66.67%  |
| 1     | 5         | 27.78%  |
| 0     | 1         | 5.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 11        | 61.11%  |
| Yes  | 7         | 38.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 78.57%  |
| Qualcomm Atheros Communications | 2         | 14.29%  |
| Realtek Semiconductor           | 1         | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                          | 6         | 42.86%  |
| Intel Bluetooth wireless interface             | 2         | 14.29%  |
| Intel AX200 Bluetooth                          | 2         | 14.29%  |
| Realtek Bluetooth Radio                        | 1         | 7.14%   |
| Qualcomm Atheros  Bluetooth Device             | 1         | 7.14%   |
| Qualcomm Atheros Bluetooth USB Host Controller | 1         | 7.14%   |
| Intel AX210 Bluetooth                          | 1         | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 14        | 53.85%  |
| Nvidia              | 5         | 19.23%  |
| AMD                 | 4         | 15.38%  |
| Texas Instruments   | 1         | 3.85%   |
| Plantronics         | 1         | 3.85%   |
| C-Media Electronics | 1         | 3.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 4         | 13.79%  |
| Intel Comet Lake PCH cAVS                                           | 3         | 10.34%  |
| AMD Family 17h/19h HD Audio Controller                              | 3         | 10.34%  |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 2         | 6.9%    |
| Nvidia Audio device                                                 | 2         | 6.9%    |
| Texas Instruments PCM2903B Audio CODEC                              | 1         | 3.45%   |
| Plantronics Blackwire 325.1                                         | 1         | 3.45%   |
| Nvidia GA104 High Definition Audio Controller                       | 1         | 3.45%   |
| Intel Tiger Lake-H HD Audio Controller                              | 1         | 3.45%   |
| Intel Sunrise Point-LP HD Audio                                     | 1         | 3.45%   |
| Intel Haswell-ULT HD Audio Controller                               | 1         | 3.45%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 1         | 3.45%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster   | 1         | 3.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                      | 1         | 3.45%   |
| Intel 8 Series HD Audio Controller                                  | 1         | 3.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 1         | 3.45%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                   | 1         | 3.45%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                | 1         | 3.45%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 1         | 3.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 1         | 3.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 5         | 33.33%  |
| SK Hynix            | 3         | 20%     |
| Unknown (ABCD)      | 2         | 13.33%  |
| Unknown             | 2         | 13.33%  |
| Silicon Power       | 1         | 6.67%   |
| Micron Technology   | 1         | 6.67%   |
| Crucial             | 1         | 6.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 13.33%  |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                         | 1         | 6.67%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 1         | 6.67%   |
| SK Hynix RAM Module 32GB SODIMM DDR4 2667MT/s                       | 1         | 6.67%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 6.67%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 6.67%   |
| Silicon Power RAM SP016GBSFU266B02 16GB SODIMM DDR4 2667MT/s        | 1         | 6.67%   |
| Samsung RAM M474A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 1         | 6.67%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 1         | 6.67%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 1         | 6.67%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 6.67%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 1         | 6.67%   |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s         | 1         | 6.67%   |
| Crucial RAM CT32G4SFD832A.C16FB 32GB SODIMM DDR4 3200MT/s           | 1         | 6.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 7         | 58.33%  |
| LPDDR4 | 3         | 25%     |
| DDR3   | 1         | 8.33%   |
| DDR2   | 1         | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 11        | 84.62%  |
| Row Of Chips | 2         | 15.38%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 4         | 30.77%  |
| 32768 | 3         | 23.08%  |
| 8192  | 3         | 23.08%  |
| 2048  | 2         | 15.38%  |
| 16384 | 1         | 7.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 4         | 30.77%  |
| 2667    | 2         | 15.38%  |
| 2400    | 2         | 15.38%  |
| 4267    | 1         | 7.69%   |
| 3266    | 1         | 7.69%   |
| 2133    | 1         | 7.69%   |
| 1066    | 1         | 7.69%   |
| Unknown | 1         | 7.69%   |

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


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Syntek                      | 2         | 14.29%  |
| IMC Networks                | 2         | 14.29%  |
| Chicony Electronics         | 2         | 14.29%  |
| USB Camera                  | 1         | 7.14%   |
| Ricoh                       | 1         | 7.14%   |
| Primax Electronics          | 1         | 7.14%   |
| Microdia                    | 1         | 7.14%   |
| Luxvisions Innotech Limited | 1         | 7.14%   |
| Lite-On Technology          | 1         | 7.14%   |
| Alcor Micro                 | 1         | 7.14%   |
| Acer                        | 1         | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera           | 2         | 14.29%  |
| Chicony Integrated Camera                | 2         | 14.29%  |
| USB Camera USB Camera                    | 1         | 7.14%   |
| Syntek Lenovo EasyCamera                 | 1         | 7.14%   |
| Syntek Integrated Camera                 | 1         | 7.14%   |
| Ricoh Sony Vaio Integrated Webcam        | 1         | 7.14%   |
| Primax HP HD Webcam [Fixed]              | 1         | 7.14%   |
| Microdia Integrated_Webcam_HD            | 1         | 7.14%   |
| Luxvisions Innotech Limited HP HD Camera | 1         | 7.14%   |
| Lite-On Integrated Camera                | 1         | 7.14%   |
| Alcor Micro USB 2.0 PC cam               | 1         | 7.14%   |
| Acer BisonCam,NB Pro                     | 1         | 7.14%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 3         | 60%     |
| Validity Sensors           | 1         | 20%     |
| Shenzhen Goodix Technology | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 20%     |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 20%     |
| Shenzhen Goodix  FingerPrint Device                       | 1         | 20%     |
| Unknown                                                   | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 8         | 42.11%  |
| 0     | 7         | 36.84%  |
| 3     | 2         | 10.53%  |
| 2     | 2         | 10.53%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 5         | 33.33%  |
| Graphics card         | 4         | 26.67%  |
| Multimedia controller | 3         | 20%     |
| Sound                 | 1         | 6.67%   |
| Net/wireless          | 1         | 6.67%   |
| Card reader           | 1         | 6.67%   |

