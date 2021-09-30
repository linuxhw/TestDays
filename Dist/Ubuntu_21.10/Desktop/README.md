Ubuntu 21.10 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 21.10.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=ubuntu-21.10

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

| Vendor   | Model                    | Probe                                                      | Date         |
|----------|--------------------------|------------------------------------------------------------|--------------|
| Gigabyte | B550 AORUS ELITE V2      | [b6f82cf92b](https://linux-hardware.org/?probe=b6f82cf92b) | Sep 30, 2021 |
| Intel    | DG41WV AAE90316-103      | [0055a963ef](https://linux-hardware.org/?probe=0055a963ef) | Sep 30, 2021 |
| ASUSTek  | A68HM-PLUS               | [8ea8e6afe8](https://linux-hardware.org/?probe=8ea8e6afe8) | Sep 30, 2021 |
| ASRock   | 990FX Extreme4           | [9c631b51b1](https://linux-hardware.org/?probe=9c631b51b1) | Sep 28, 2021 |
| Gigabyte | H81M-D2V                 | [e8749db36a](https://linux-hardware.org/?probe=e8749db36a) | Sep 27, 2021 |
| Gigabyte | H81M-D2V                 | [aa1a6086e7](https://linux-hardware.org/?probe=aa1a6086e7) | Sep 27, 2021 |
| Gigabyte | H81M-D2V                 | [b05cdb0bab](https://linux-hardware.org/?probe=b05cdb0bab) | Sep 26, 2021 |
| ASRock   | X399M Taichi             | [eba541c6b9](https://linux-hardware.org/?probe=eba541c6b9) | Sep 25, 2021 |
| Gigabyte | H81M-S                   | [357f7466e6](https://linux-hardware.org/?probe=357f7466e6) | Sep 25, 2021 |
| ASRock   | Z390M Pro4               | [138ae00012](https://linux-hardware.org/?probe=138ae00012) | Sep 23, 2021 |
| Medion   | B360H4-EM V1.0           | [1985156471](https://linux-hardware.org/?probe=1985156471) | Sep 19, 2021 |
| Gigabyte | B85M-D3H                 | [9de4382874](https://linux-hardware.org/?probe=9de4382874) | Sep 15, 2021 |
| HP       | 3032h                    | [3fad749d1a](https://linux-hardware.org/?probe=3fad749d1a) | Sep 12, 2021 |
| Huanan   | X99 F8D V2.2             | [c080ec772f](https://linux-hardware.org/?probe=c080ec772f) | Sep 03, 2021 |
| Huanan   | X99 F8D V2.2             | [30fe8d6bb3](https://linux-hardware.org/?probe=30fe8d6bb3) | Aug 26, 2021 |
| ASUSTek  | ROG ZENITH II EXTREME    | [1a371ea24e](https://linux-hardware.org/?probe=1a371ea24e) | Aug 16, 2021 |
| Fujitsu  | D3400-B2 S26361-D3400-B2 | [067c79a9fe](https://linux-hardware.org/?probe=067c79a9fe) | Aug 13, 2021 |
| MSI      | MAG B550M MORTAR         | [912b2a77a2](https://linux-hardware.org/?probe=912b2a77a2) | Aug 05, 2021 |
| Huanan   | X99 F8D V2.2             | [74e4c61bbf](https://linux-hardware.org/?probe=74e4c61bbf) | Jul 23, 2021 |
| Huanan   | X99 F8D V2.2             | [02ad72fb54](https://linux-hardware.org/?probe=02ad72fb54) | Jul 21, 2021 |
| Gigabyte | F2A55M-HD2               | [6a69f09403](https://linux-hardware.org/?probe=6a69f09403) | Jul 15, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.13.0-16-generic           | 8        | 47.06%  |
| 5.13.0-14-generic           | 3        | 17.65%  |
| 5.13.0-12-generic           | 2        | 11.76%  |
| 5.14.0-051400rc7-lowlatency | 1        | 5.88%   |
| 5.13.0-17-generic           | 1        | 5.88%   |
| 5.13.0-051300-generic       | 1        | 5.88%   |
| 5.11.0-20-generic           | 1        | 5.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.0  | 15       | 88.24%  |
| 5.14.0  | 1        | 5.88%   |
| 5.11.0  | 1        | 5.88%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13    | 15       | 88.24%  |
| 5.14    | 1        | 5.88%   |
| 5.11    | 1        | 5.88%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 16       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 14       | 82.35%  |
| Unknown    | 2        | 11.76%  |
| X-Cinnamon | 1        | 5.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 8        | 47.06%  |
| X11     | 6        | 35.29%  |
| Tty     | 2        | 11.76%  |
| Unknown | 1        | 5.88%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM3    | 6        | 37.5%   |
| Unknown | 6        | 37.5%   |
| GDM     | 4        | 25%     |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 6        | 37.5%   |
| de_DE | 3        | 18.75%  |
| en_GB | 2        | 12.5%   |
| sv_SE | 1        | 6.25%   |
| ru_UA | 1        | 6.25%   |
| es_MX | 1        | 6.25%   |
| es_AR | 1        | 6.25%   |
| en_IN | 1        | 6.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 12       | 75%     |
| EFI  | 4        | 25%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 15       | 93.75%  |
| Btrfs | 1        | 6.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 12       | 75%     |
| GPT     | 4        | 25%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 68.75%  |
| Yes       | 5        | 31.25%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 9        | 56.25%  |
| No        | 7        | 43.75%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 5        | 31.25%  |
| ASRock              | 3        | 18.75%  |
| ASUSTek Computer    | 2        | 12.5%   |
| MSI                 | 1        | 6.25%   |
| Medion              | 1        | 6.25%   |
| Intel               | 1        | 6.25%   |
| Huanan              | 1        | 6.25%   |
| Hewlett-Packard     | 1        | 6.25%   |
| Fujitsu             | 1        | 6.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| MSI MS-7C94                            | 1        | 6.25%   |
| Medion X87085                          | 1        | 6.25%   |
| Intel DG41WV AAE90316-103              | 1        | 6.25%   |
| Huanan X99 F8D V2.2                    | 1        | 6.25%   |
| HP Compaq dc7900 Convertible Minitower | 1        | 6.25%   |
| Gigabyte H81M-S                        | 1        | 6.25%   |
| Gigabyte H81M-D2V                      | 1        | 6.25%   |
| Gigabyte F2A55M-HD2                    | 1        | 6.25%   |
| Gigabyte B85M-D3H                      | 1        | 6.25%   |
| Gigabyte B550 AORUS ELITE V2           | 1        | 6.25%   |
| Fujitsu S1100F                         | 1        | 6.25%   |
| ASUS ROG ZENITH II EXTREME             | 1        | 6.25%   |
| ASUS A68HM-PLUS                        | 1        | 6.25%   |
| ASRock Z390M Pro4                      | 1        | 6.25%   |
| ASRock X399M Taichi                    | 1        | 6.25%   |
| ASRock 990FX Extreme4                  | 1        | 6.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI MS-7C94         | 1        | 6.25%   |
| Medion X87085       | 1        | 6.25%   |
| Intel DG41WV        | 1        | 6.25%   |
| Huanan X99          | 1        | 6.25%   |
| HP Compaq           | 1        | 6.25%   |
| Gigabyte H81M-S     | 1        | 6.25%   |
| Gigabyte H81M-D2V   | 1        | 6.25%   |
| Gigabyte F2A55M-HD2 | 1        | 6.25%   |
| Gigabyte B85M-D3H   | 1        | 6.25%   |
| Gigabyte B550       | 1        | 6.25%   |
| Fujitsu S1100F      | 1        | 6.25%   |
| ASUS ROG            | 1        | 6.25%   |
| ASUS A68HM-PLUS     | 1        | 6.25%   |
| ASRock Z390M        | 1        | 6.25%   |
| ASRock X399M        | 1        | 6.25%   |
| ASRock 990FX        | 1        | 6.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 4        | 25%     |
| 2019 | 3        | 18.75%  |
| 2015 | 3        | 18.75%  |
| 2014 | 2        | 12.5%   |
| 2017 | 1        | 6.25%   |
| 2016 | 1        | 6.25%   |
| 2013 | 1        | 6.25%   |
| 2010 | 1        | 6.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 16       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 16       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 16       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 4        | 23.53%  |
| 3.01-4.0    | 3        | 17.65%  |
| 8.01-16.0   | 3        | 17.65%  |
| 32.01-64.0  | 2        | 11.76%  |
| 64.01-256.0 | 2        | 11.76%  |
| 16.01-24.0  | 2        | 11.76%  |
| 24.01-32.0  | 1        | 5.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 6        | 35.29%  |
| 2.01-3.0  | 5        | 29.41%  |
| 3.01-4.0  | 3        | 17.65%  |
| 4.01-8.0  | 2        | 11.76%  |
| 8.01-16.0 | 1        | 5.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 6        | 37.5%   |
| 5      | 3        | 18.75%  |
| 2      | 3        | 18.75%  |
| 3      | 2        | 12.5%   |
| 6      | 1        | 6.25%   |
| 4      | 1        | 6.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 56.25%  |
| Yes       | 7        | 43.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 16       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 75%     |
| Yes       | 4        | 25%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 62.5%   |
| Yes       | 6        | 37.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Germany   | 4        | 25%     |
| Ukraine   | 2        | 12.5%   |
| USA       | 1        | 6.25%   |
| UK        | 1        | 6.25%   |
| Sweden    | 1        | 6.25%   |
| Malaysia  | 1        | 6.25%   |
| Lithuania | 1        | 6.25%   |
| India     | 1        | 6.25%   |
| Denmark   | 1        | 6.25%   |
| Chile     | 1        | 6.25%   |
| Brazil    | 1        | 6.25%   |
| Argentina | 1        | 6.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Wittlich      | 3        | 18.75%  |
| Uppsala       | 1        | 6.25%   |
| Trakai        | 1        | 6.25%   |
| Rosario       | 1        | 6.25%   |
| Pitrufquen    | 1        | 6.25%   |
| Petaling Jaya | 1        | 6.25%   |
| Osasco        | 1        | 6.25%   |
| Oleksandriya  | 1        | 6.25%   |
| Leiston       | 1        | 6.25%   |
| Kyiv          | 1        | 6.25%   |
| Esbjerg       | 1        | 6.25%   |
| Dallas        | 1        | 6.25%   |
| Chennai       | 1        | 6.25%   |
| Bad Wildungen | 1        | 6.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 12     | 27.27%  |
| WDC                 | 5        | 9      | 15.15%  |
| Seagate             | 3        | 4      | 9.09%   |
| Toshiba             | 2        | 3      | 6.06%   |
| SanDisk             | 2        | 2      | 6.06%   |
| KIOXIA-EXCERIA      | 2        | 2      | 6.06%   |
| Kingston            | 2        | 4      | 6.06%   |
| Silicon Motion      | 1        | 3      | 3.03%   |
| PNY                 | 1        | 1      | 3.03%   |
| Phison              | 1        | 1      | 3.03%   |
| Hitachi             | 1        | 1      | 3.03%   |
| Hewlett-Packard     | 1        | 1      | 3.03%   |
| GOODRAM             | 1        | 2      | 3.03%   |
| Crucial             | 1        | 2      | 3.03%   |
| China               | 1        | 1      | 3.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung SSD 870 EVO 250GB           | 2        | 5.41%   |
| Samsung SSD 850 EVO 120GB           | 2        | 5.41%   |
| KIOXIA-EXCERIA SATA SSD 480GB       | 2        | 5.41%   |
| WDC WD80EZAZ-11TDBA0 8TB            | 1        | 2.7%    |
| WDC WD3200AAKS-00V6A0 320GB         | 1        | 2.7%    |
| WDC WD3200AAJS-56B4A0 320GB         | 1        | 2.7%    |
| WDC WD20EZRX-00D8PB0 2TB            | 1        | 2.7%    |
| WDC WD10EZEX-00MFCA0 1TB            | 1        | 2.7%    |
| Toshiba HDWL120 2TB                 | 1        | 2.7%    |
| Toshiba HDWD240 4TB                 | 1        | 2.7%    |
| Silicon Motion NVMe SSD Drive 256GB | 1        | 2.7%    |
| Seagate ST3250310AS 250GB           | 1        | 2.7%    |
| Seagate ST320DM000-1BD14C 320GB     | 1        | 2.7%    |
| Seagate ST1000DM003-9YN162 1TB      | 1        | 2.7%    |
| Seagate BUP Slim BK 1TB             | 1        | 2.7%    |
| SanDisk Ultra II 480GB SSD          | 1        | 2.7%    |
| SanDisk SD8SNAT256G1002 256GB SSD   | 1        | 2.7%    |
| Samsung SSD 980 PRO 500GB           | 1        | 2.7%    |
| Samsung SSD 980 PRO 2TB             | 1        | 2.7%    |
| Samsung SSD 860 EVO 500GB           | 1        | 2.7%    |
| Samsung SSD 650 120GB               | 1        | 2.7%    |
| Samsung MZVPW256HEGL-000H1 256GB    | 1        | 2.7%    |
| Samsung HD320KJ 320GB               | 1        | 2.7%    |
| Samsung HD103SJ 1TB                 | 1        | 2.7%    |
| PNY CS900 240GB SSD                 | 1        | 2.7%    |
| Phison NVMe SSD Drive 1024GB        | 1        | 2.7%    |
| Kingston SHFS37A120G 120GB SSD      | 1        | 2.7%    |
| Kingston SA400S37240G 240GB SSD     | 1        | 2.7%    |
| Hitachi HTS543212L9SA00 120GB       | 1        | 2.7%    |
| HP FB160C4081 160GB                 | 1        | 2.7%    |
| GOODRAM SSDPR-PX500-512-80 512GB    | 1        | 2.7%    |
| Crucial CT480BX500SSD1 480GB        | 1        | 2.7%    |
| Crucial CT120BX500SSD1 120GB        | 1        | 2.7%    |
| China SATA SSD 240GB                | 1        | 2.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 9      | 35.71%  |
| Seagate             | 3        | 4      | 21.43%  |
| Toshiba             | 2        | 3      | 14.29%  |
| Samsung Electronics | 2        | 2      | 14.29%  |
| Hitachi             | 1        | 1      | 7.14%   |
| Hewlett-Packard     | 1        | 1      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 6      | 35.71%  |
| SanDisk             | 2        | 2      | 14.29%  |
| KIOXIA-EXCERIA      | 2        | 2      | 14.29%  |
| Kingston            | 2        | 4      | 14.29%  |
| PNY                 | 1        | 1      | 7.14%   |
| Crucial             | 1        | 2      | 7.14%   |
| China               | 1        | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 10       | 18     | 40%     |
| HDD  | 9        | 20     | 36%     |
| NVMe | 6        | 10     | 24%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 14       | 37     | 66.67%  |
| NVMe | 6        | 10     | 28.57%  |
| SAS  | 1        | 1      | 4.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 13       | 25     | 65%     |
| 0.51-1.0   | 3        | 4      | 15%     |
| 1.01-2.0   | 2        | 2      | 10%     |
| 3.01-4.0   | 1        | 2      | 5%      |
| 4.01-10.0  | 1        | 5      | 5%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 8        | 50%     |
| 251-500    | 4        | 25%     |
| 1001-2000  | 2        | 12.5%   |
| 1-20       | 1        | 6.25%   |
| 51-100     | 1        | 6.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 101-250   | 5        | 31.25%  |
| 1-20      | 4        | 25%     |
| 21-50     | 3        | 18.75%  |
| 51-100    | 2        | 12.5%   |
| 1001-2000 | 1        | 6.25%   |
| 501-1000  | 1        | 6.25%   |

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
| Detected | 12       | 28     | 70.59%  |
| Works    | 5        | 20     | 29.41%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 9        | 34.62%  |
| AMD                          | 7        | 26.92%  |
| Samsung Electronics          | 3        | 11.54%  |
| Silicon Motion               | 2        | 7.69%   |
| Shenzhen Longsys Electronics | 1        | 3.85%   |
| Phison Electronics           | 1        | 3.85%   |
| Marvell Technology Group     | 1        | 3.85%   |
| LSI Logic / Symbios Logic    | 1        | 3.85%   |
| ASMedia Technology           | 1        | 3.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3        | 10.34%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 3        | 10.34%  |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2        | 6.9%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 6.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 6.9%    |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                       | 2        | 6.9%    |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                               | 1        | 3.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 3.45%   |
| Phison E12 NVMe Controller                                                     | 1        | 3.45%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                        | 1        | 3.45%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                 | 1        | 3.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 3.45%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 3.45%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1        | 3.45%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1        | 3.45%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 3.45%   |
| AMD X399 Series Chipset SATA Controller                                        | 1        | 3.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1        | 3.45%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1        | 3.45%   |
| AMD FCH SATA Controller [IDE mode]                                             | 1        | 3.45%   |
| AMD FCH IDE Controller                                                         | 1        | 3.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 15       | 60%     |
| NVMe | 6        | 24%     |
| IDE  | 3        | 12%     |
| SCSI | 1        | 4%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 9        | 56.25%  |
| AMD    | 7        | 43.75%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i5-4570 CPU @ 3.20GHz               | 2        | 12.5%   |
| Intel Xeon CPU E5-2690 v4 @ 2.60GHz            | 1        | 6.25%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz    | 1        | 6.25%   |
| Intel Core i7-9700 CPU @ 3.00GHz               | 1        | 6.25%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 1        | 6.25%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1        | 6.25%   |
| Intel Core i3-4150 CPU @ 3.50GHz               | 1        | 6.25%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 1        | 6.25%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor | 1        | 6.25%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 1        | 6.25%   |
| AMD Ryzen 7 5700G with Radeon Graphics         | 1        | 6.25%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1        | 6.25%   |
| AMD FX-6100 Six-Core Processor                 | 1        | 6.25%   |
| AMD A8-6600K APU with Radeon HD Graphics       | 1        | 6.25%   |
| AMD A4-4000 APU with Radeon HD Graphics        | 1        | 6.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 3        | 18.75%  |
| Intel Core i7           | 2        | 12.5%   |
| AMD Ryzen Threadripper  | 2        | 12.5%   |
| Intel Xeon              | 1        | 6.25%   |
| Intel Pentium Dual-Core | 1        | 6.25%   |
| Intel Core i3           | 1        | 6.25%   |
| Intel Core 2 Duo        | 1        | 6.25%   |
| AMD Ryzen 7             | 1        | 6.25%   |
| AMD Ryzen 5             | 1        | 6.25%   |
| AMD FX                  | 1        | 6.25%   |
| AMD A8                  | 1        | 6.25%   |
| AMD A4                  | 1        | 6.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 4        | 25%     |
| 4      | 3        | 18.75%  |
| 8      | 2        | 12.5%   |
| 6      | 2        | 12.5%   |
| 32     | 1        | 6.25%   |
| 28     | 1        | 6.25%   |
| 12     | 1        | 6.25%   |
| 3      | 1        | 6.25%   |
| 1      | 1        | 6.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 15       | 93.75%  |
| 2      | 1        | 6.25%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 10       | 62.5%   |
| 1      | 6        | 37.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 16       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 13       | 81.25%  |
| 0x906ea    | 1        | 6.25%   |
| 0x906e9    | 1        | 6.25%   |
| 0x08001137 | 1        | 6.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KabyLake   | 3        | 18.75%  |
| Haswell    | 3        | 18.75%  |
| Zen 3      | 2        | 12.5%   |
| Piledriver | 2        | 12.5%   |
| Penryn     | 2        | 12.5%   |
| Zen 2      | 1        | 6.25%   |
| Zen        | 1        | 6.25%   |
| Bulldozer  | 1        | 6.25%   |
| Broadwell  | 1        | 6.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 7        | 38.89%  |
| Intel  | 6        | 33.33%  |
| AMD    | 5        | 27.78%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 10%     |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 5%      |
| Nvidia NV44 [GeForce 6200 LE]                                               | 1        | 5%      |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 5%      |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 5%      |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 5%      |
| Nvidia GK104 [GeForce GTX 680]                                              | 1        | 5%      |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 5%      |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 5%      |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 5%      |
| Intel HD Graphics 630                                                       | 1        | 5%      |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 5%      |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 5%      |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 5%      |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 1        | 5%      |
| AMD Richland [Radeon HD 8570D]                                              | 1        | 5%      |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 5%      |
| AMD Cezanne                                                                 | 1        | 5%      |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 1        | 5%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 5        | 31.25%  |
| 1 x Intel      | 4        | 25%     |
| 1 x Nvidia     | 3        | 18.75%  |
| 2 x Nvidia     | 2        | 12.5%   |
| Intel + Nvidia | 2        | 12.5%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 12       | 75%     |
| Proprietary | 3        | 18.75%  |
| Unknown     | 1        | 6.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 12       | 75%     |
| 1.01-2.0   | 3        | 18.75%  |
| 7.01-8.0   | 1        | 6.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 3        | 18.75%  |
| Samsung Electronics | 2        | 12.5%   |
| Lenovo              | 2        | 12.5%   |
| BenQ                | 2        | 12.5%   |
| SKY                 | 1        | 6.25%   |
| Packard Bell        | 1        | 6.25%   |
| MStar               | 1        | 6.25%   |
| LG Electronics      | 1        | 6.25%   |
| Goldstar            | 1        | 6.25%   |
| ASUSTek Computer    | 1        | 6.25%   |
| AOC                 | 1        | 6.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| BenQ GL2580 BNQ78E5 1920x1080 544x303mm 24.5-inch                   | 2        | 11.11%  |
| SKY TV-monitor SKY0001 1920x1080 697x392mm 31.5-inch                | 1        | 5.56%   |
| Samsung Electronics U24E590 SAM0CD2 3840x2160 521x293mm 23.5-inch   | 1        | 5.56%   |
| Samsung Electronics SMS19A450 SAM0848 1280x1024 376x301mm 19.0-inch | 1        | 5.56%   |
| Packard Bell Viseo 160W PKB00D0 1366x768 344x193mm 15.5-inch        | 1        | 5.56%   |
| MStar TV_MONITOR MST0030 1440x900 1150x650mm 52.0-inch              | 1        | 5.56%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                   | 1        | 5.56%   |
| LG Electronics LCD Monitor LG ULTRAWIDE                             | 1        | 5.56%   |
| Lenovo P27q-20 LEN61EA 2560x1440 609x349mm 27.6-inch                | 1        | 5.56%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch            | 1        | 5.56%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 1        | 5.56%   |
| Dell S2721DGF DEL41DB 2560x1440 597x336mm 27.0-inch                 | 1        | 5.56%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                 | 1        | 5.56%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                   | 1        | 5.56%   |
| Dell LCD Monitor P2419H 4480x1080                                   | 1        | 5.56%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch        | 1        | 5.56%   |
| AOC 2050 AOC2050 1600x900 443x249mm 20.0-inch                       | 1        | 5.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 3840x2160 (4K)   | 4        | 23.53%  |
| 1920x1080 (FHD)  | 4        | 23.53%  |
| 2560x1440 (QHD)  | 3        | 17.65%  |
| 4480x1080        | 1        | 5.88%   |
| 2560x1080        | 1        | 5.88%   |
| 1600x900 (HD+)   | 1        | 5.88%   |
| 1366x768 (WXGA)  | 1        | 5.88%   |
| 1280x1024 (SXGA) | 1        | 5.88%   |
| Unknown          | 1        | 5.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 3        | 21.43%  |
| 24      | 3        | 21.43%  |
| 52      | 1        | 7.14%   |
| 40      | 1        | 7.14%   |
| 23      | 1        | 7.14%   |
| 21      | 1        | 7.14%   |
| 20      | 1        | 7.14%   |
| 19      | 1        | 7.14%   |
| 15      | 1        | 7.14%   |
| Unknown | 1        | 7.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 6        | 40%     |
| 601-700     | 2        | 13.33%  |
| 401-500     | 2        | 13.33%  |
| 801-900     | 1        | 6.67%   |
| 351-400     | 1        | 6.67%   |
| 301-350     | 1        | 6.67%   |
| 1001-1500   | 1        | 6.67%   |
| Unknown     | 1        | 6.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 12       | 85.71%  |
| 5/4     | 1        | 7.14%   |
| Unknown | 1        | 7.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 3        | 21.43%  |
| 201-250        | 3        | 21.43%  |
| 251-300        | 2        | 14.29%  |
| 151-200        | 2        | 14.29%  |
| More than 1000 | 1        | 7.14%   |
| 101-110        | 1        | 7.14%   |
| 501-1000       | 1        | 7.14%   |
| Unknown        | 1        | 7.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 5        | 33.33%  |
| 101-120 | 4        | 26.67%  |
| 1-50    | 2        | 13.33%  |
| 121-160 | 2        | 13.33%  |
| 161-240 | 1        | 6.67%   |
| Unknown | 1        | 6.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 14       | 82.35%  |
| 3     | 1        | 5.88%   |
| 2     | 1        | 5.88%   |
| 0     | 1        | 5.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 12       | 57.14%  |
| Intel                 | 4        | 19.05%  |
| Broadcom              | 2        | 9.52%   |
| Aquantia              | 2        | 9.52%   |
| TP-Link               | 1        | 4.76%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9        | 39.13%  |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 8.7%    |
| Intel I211 Gigabit Network Connection                             | 2        | 8.7%    |
| TP-Link Archer T4U ver.3                                          | 1        | 4.35%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 4.35%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 4.35%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 4.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 4.35%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 4.35%   |
| Broadcom Network controller                                       | 1        | 4.35%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 4.35%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 4.35%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 4.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Intel    | 2        | 50%     |
| TP-Link  | 1        | 25%     |
| Broadcom | 1        | 25%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| TP-Link Archer T4U ver.3                         | 1        | 25%     |
| Intel Wi-Fi 6 AX200                              | 1        | 25%     |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak] | 1        | 25%     |
| Broadcom Network controller                      | 1        | 25%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 12       | 63.16%  |
| Intel                 | 4        | 21.05%  |
| Aquantia              | 2        | 10.53%  |
| Broadcom              | 1        | 5.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9        | 47.37%  |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 10.53%  |
| Intel I211 Gigabit Network Connection                             | 2        | 10.53%  |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 5.26%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 5.26%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 5.26%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 5.26%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 5.26%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 5.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 16       | 80%     |
| WiFi     | 4        | 20%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 13       | 81.25%  |
| WiFi     | 3        | 18.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10       | 62.5%   |
| 2     | 3        | 18.75%  |
| 3     | 2        | 12.5%   |
| 5     | 1        | 6.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 10       | 62.5%   |
| Yes  | 6        | 37.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Realtek Semiconductor   | 2        | 40%     |
| Cambridge Silicon Radio | 2        | 40%     |
| Intel                   | 1        | 20%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Realtek Bluetooth Radio                             | 2        | 40%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 40%     |
| Intel AX200 Bluetooth                               | 1        | 20%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 9        | 33.33%  |
| Nvidia              | 6        | 22.22%  |
| AMD                 | 6        | 22.22%  |
| XMOS                | 1        | 3.7%    |
| Logitech            | 1        | 3.7%    |
| GN Netcom           | 1        | 3.7%    |
| Creative Technology | 1        | 3.7%    |
| C-Media Electronics | 1        | 3.7%    |
| ASUSTek Computer    | 1        | 3.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 3        | 8.57%   |
| Intel Cannon Lake PCH cAVS                                                        | 2        | 5.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 2        | 5.71%   |
| AMD Trinity HDMI Audio Controller                                                 | 2        | 5.71%   |
| AMD FCH Azalia Controller                                                         | 2        | 5.71%   |
| XMOS HIFI DSD                                                                     | 1        | 2.86%   |
| Nvidia TU104 HD Audio Controller                                                  | 1        | 2.86%   |
| Nvidia High Definition Audio Controller                                           | 1        | 2.86%   |
| Nvidia GP108 High Definition Audio Controller                                     | 1        | 2.86%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1        | 2.86%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 2.86%   |
| Nvidia GF108 High Definition Audio Controller                                     | 1        | 2.86%   |
| Nvidia GA102 High Definition Audio Controller                                     | 1        | 2.86%   |
| Logitech H600 [Wireless Headset]                                                  | 1        | 2.86%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 1        | 2.86%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 1        | 2.86%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 1        | 2.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 1        | 2.86%   |
| GN Netcom Jabra EVOLVE Link MS                                                    | 1        | 2.86%   |
| Creative Technology SoundBlaster Audigy 2 NX                                      | 1        | 2.86%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 1        | 2.86%   |
| ASUSTek Computer USB Audio                                                        | 1        | 2.86%   |
| AMD Starship/Matisse HD Audio Controller                                          | 1        | 2.86%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1        | 2.86%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 1        | 2.86%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 1        | 2.86%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1        | 2.86%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 2.86%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 1        | 2.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 2        | 28.57%  |
| Kingston            | 2        | 28.57%  |
| Unknown             | 1        | 14.29%  |
| Team                | 1        | 14.29%  |
| Crucial             | 1        | 14.29%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s              | 1        | 14.29%  |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s     | 1        | 14.29%  |
| Samsung RAM M471A1K43CB1-CTD 8GB DIMM DDR4 2667MT/s    | 1        | 14.29%  |
| Samsung RAM M378A1K43BB2-CRC 8GB DIMM DDR4 3400MT/s    | 1        | 14.29%  |
| Kingston RAM KHX3600C18D4/32GX 32GB DIMM DDR4 3600MT/s | 1        | 14.29%  |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s   | 1        | 14.29%  |
| Crucial RAM BL8G36C16U4B.M8FE1 8GB DIMM DDR4 3733MT/s  | 1        | 14.29%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 6        | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 6        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 4        | 66.67%  |
| 32768 | 1        | 16.67%  |
| 16384 | 1        | 16.67%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3733  | 1        | 16.67%  |
| 3600  | 1        | 16.67%  |
| 3533  | 1        | 16.67%  |
| 3400  | 1        | 16.67%  |
| 3000  | 1        | 16.67%  |
| 2667  | 1        | 16.67%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 3        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung M283x Series    | 2        | 66.67%  |
| Samsung SCX-3400 Series | 1        | 33.33%  |

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


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Logitech | 2        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                 | Desktops | Percent |
|-----------------------|----------|---------|
| Logitech Webcam C930e | 2        | 100%    |

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
| 0     | 13       | 81.25%  |
| 1     | 2        | 12.5%   |
| 2     | 1        | 6.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Unassigned class | 1        | 33.33%  |
| Sound            | 1        | 33.33%  |
| Graphics card    | 1        | 33.33%  |

