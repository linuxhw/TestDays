Alpine - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Alpine.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 22

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | Z490I AORUS ULTRA           | [908edb3724](https://linux-hardware.org/?probe=908edb3724) | Jan 27, 2022 |
| Dell          | 02YRK5 A02                  | [58c2ed388b](https://linux-hardware.org/?probe=58c2ed388b) | Dec 02, 2021 |
| HP            | 21B4 A01                    | [98accc83e4](https://linux-hardware.org/?probe=98accc83e4) | Nov 11, 2021 |
| Dell          | 0T10XW A00                  | [585636f7fe](https://linux-hardware.org/?probe=585636f7fe) | Sep 08, 2021 |
| Shuttle       | FS81                        | [9a98a31681](https://linux-hardware.org/?probe=9a98a31681) | Sep 06, 2021 |
| Dell          | 0VRWRC A00                  | [37a6ad6e02](https://linux-hardware.org/?probe=37a6ad6e02) | Apr 09, 2021 |
| ASUSTek       | P8H67-V                     | [89edd8b343](https://linux-hardware.org/?probe=89edd8b343) | Mar 17, 2021 |
| HP            | ProLiant MicroServer Gen... | [af637820c2](https://linux-hardware.org/?probe=af637820c2) | Feb 12, 2021 |
| VIA Techno... | KM266APro-835               | [1334ad3f74](https://linux-hardware.org/?probe=1334ad3f74) | Dec 22, 2020 |
| Fujitsu       | D2779 S26361-D2779-A1       | [07795a357a](https://linux-hardware.org/?probe=07795a357a) | Oct 09, 2020 |
| Dell          | 0PU052                      | [9a31999f07](https://linux-hardware.org/?probe=9a31999f07) | Aug 31, 2020 |
| ASUSTek       | TS10                        | [71d7f6e110](https://linux-hardware.org/?probe=71d7f6e110) | Aug 20, 2020 |
| VIA Techno... | KM266APro-835               | [25ec3d44ff](https://linux-hardware.org/?probe=25ec3d44ff) | Aug 16, 2020 |
| Gigabyte      | Z490I AORUS ULTRA           | [58dce1215c](https://linux-hardware.org/?probe=58dce1215c) | Aug 13, 2020 |
| ASUSTek       | PRIME H370M-PLUS            | [0c50242cc5](https://linux-hardware.org/?probe=0c50242cc5) | Aug 09, 2020 |
| ASRock        | J3455M                      | [05f9d5c3b4](https://linux-hardware.org/?probe=05f9d5c3b4) | Aug 06, 2020 |
| ASRock        | J3455M                      | [a838270927](https://linux-hardware.org/?probe=a838270927) | Jul 03, 2020 |
| eMachines     | EL1352G                     | [4513d2931f](https://linux-hardware.org/?probe=4513d2931f) | Jul 03, 2020 |
| eMachines     | EL1352G                     | [4b26717c89](https://linux-hardware.org/?probe=4b26717c89) | Jul 03, 2020 |
| ASRock        | J3455M                      | [3719f96b60](https://linux-hardware.org/?probe=3719f96b60) | Jul 03, 2020 |
| Unknown       | i855GM/E-ITE8712            | [7b9cbd816b](https://linux-hardware.org/?probe=7b9cbd816b) | Dec 27, 2019 |
| ASRock        | D1800B-ITX                  | [f962d4bbf9](https://linux-hardware.org/?probe=f962d4bbf9) | Dec 22, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Alpine 3.12.0               | 5        | 27.78%  |
| Alpine 3.13.0_alpha20200626 | 3        | 16.67%  |
| Alpine 3.11.2               | 2        | 11.11%  |
| Alpine 3.8.4                | 1        | 5.56%   |
| Alpine 3.15.0               | 1        | 5.56%   |
| Alpine 3.14.2               | 1        | 5.56%   |
| Alpine 3.13.6               | 1        | 5.56%   |
| Alpine 3.13.2               | 1        | 5.56%   |
| Alpine 3.13.1               | 1        | 5.56%   |
| Alpine 3.13.0_alpha20201218 | 1        | 5.56%   |
| Alpine 3.12.3               | 1        | 5.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Alpine | 17       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.4.43-1-lts      | 5        | 27.78%  |
| 5.8.0             | 1        | 5.56%   |
| 5.4.84-0-lts      | 1        | 5.56%   |
| 5.4.6-0-lts       | 1        | 5.56%   |
| 5.4.58-0-lts      | 1        | 5.56%   |
| 5.4.57-0-lts      | 1        | 5.56%   |
| 5.15.17-0-lts     | 1        | 5.56%   |
| 5.10.81           | 1        | 5.56%   |
| 5.10.61-0-lts     | 1        | 5.56%   |
| 5.10.16-0-lts     | 1        | 5.56%   |
| 5.10.12-0-lts     | 1        | 5.56%   |
| 5.10.1-0-lts      | 1        | 5.56%   |
| 4.14.89-0-vanilla | 1        | 5.56%   |
| 3.10.105          | 1        | 5.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.43   | 5        | 27.78%  |
| 5.8.0    | 1        | 5.56%   |
| 5.4.84   | 1        | 5.56%   |
| 5.4.6    | 1        | 5.56%   |
| 5.4.58   | 1        | 5.56%   |
| 5.4.57   | 1        | 5.56%   |
| 5.15.17  | 1        | 5.56%   |
| 5.10.81  | 1        | 5.56%   |
| 5.10.61  | 1        | 5.56%   |
| 5.10.16  | 1        | 5.56%   |
| 5.10.12  | 1        | 5.56%   |
| 5.10.1   | 1        | 5.56%   |
| 4.14.89  | 1        | 5.56%   |
| 3.10.105 | 1        | 5.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 9        | 50%     |
| 5.10    | 5        | 27.78%  |
| 5.8     | 1        | 5.56%   |
| 5.15    | 1        | 5.56%   |
| 4.14    | 1        | 5.56%   |
| 3.10    | 1        | 5.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 15       | 88.24%  |
| i686   | 2        | 11.76%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 15       | 88.24%  |
| XFCE    | 1        | 5.88%   |
| i3      | 1        | 5.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 12       | 70.59%  |
| X11     | 5        | 29.41%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 16       | 94.12%  |
| LightDM | 1        | 5.88%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| C       | 9        | 52.94%  |
| Unknown | 8        | 47.06%  |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 14       | 82.35%  |
| EFI  | 3        | 17.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 14       | 82.35%  |
| Tmpfs   | 1        | 5.88%   |
| Btrfs   | 1        | 5.88%   |
| Unknown | 1        | 5.88%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 8        | 44.44%  |
| GPT     | 6        | 33.33%  |
| MBR     | 4        | 22.22%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 82.35%  |
| Yes       | 3        | 17.65%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 88.24%  |
| Yes       | 2        | 11.76%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 4        | 23.53%  |
| ASUSTek Computer    | 3        | 17.65%  |
| Gigabyte Technology | 2        | 11.76%  |
| ASRock              | 2        | 11.76%  |
| VIA Technologies    | 1        | 5.88%   |
| Shuttle             | 1        | 5.88%   |
| Hewlett-Packard     | 1        | 5.88%   |
| Fujitsu             | 1        | 5.88%   |
| eMachines           | 1        | 5.88%   |
| Unknown             | 1        | 5.88%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Gigabyte Z490I AORUS ULTRA   | 2        | 11.76%  |
| VIA KM266APro-835            | 1        | 5.88%   |
| Shuttle DS81D                | 1        | 5.88%   |
| HP ProLiant MicroServer Gen8 | 1        | 5.88%   |
| Fujitsu PRIMERGY TX100 S2    | 1        | 5.88%   |
| eMachines EL1352G            | 1        | 5.88%   |
| Dell OptiPlex 755            | 1        | 5.88%   |
| Dell OptiPlex 3020M          | 1        | 5.88%   |
| Dell OptiPlex 3010           | 1        | 5.88%   |
| Dell Inspiron 3647           | 1        | 5.88%   |
| ASUS TS10                    | 1        | 5.88%   |
| ASUS PRIME H370M-PLUS        | 1        | 5.88%   |
| ASUS P8H67-V                 | 1        | 5.88%   |
| ASRock J3455M                | 1        | 5.88%   |
| ASRock D1800B-ITX            | 1        | 5.88%   |
| Unknown                      | 1        | 5.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Dell OptiPlex     | 3        | 17.65%  |
| Gigabyte Z490I    | 2        | 11.76%  |
| VIA KM266APro-835 | 1        | 5.88%   |
| Shuttle DS81D     | 1        | 5.88%   |
| HP ProLiant       | 1        | 5.88%   |
| Fujitsu PRIMERGY  | 1        | 5.88%   |
| eMachines EL1352G | 1        | 5.88%   |
| Dell Inspiron     | 1        | 5.88%   |
| ASUS TS10         | 1        | 5.88%   |
| ASUS PRIME        | 1        | 5.88%   |
| ASUS P8H67-V      | 1        | 5.88%   |
| ASRock J3455M     | 1        | 5.88%   |
| ASRock D1800B-ITX | 1        | 5.88%   |
| Unknown           | 1        | 5.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2014 | 4        | 23.53%  |
| 2020 | 2        | 11.76%  |
| 2010 | 2        | 11.76%  |
| 2018 | 1        | 5.88%   |
| 2017 | 1        | 5.88%   |
| 2016 | 1        | 5.88%   |
| 2013 | 1        | 5.88%   |
| 2012 | 1        | 5.88%   |
| 2011 | 1        | 5.88%   |
| 2009 | 1        | 5.88%   |
| 2007 | 1        | 5.88%   |
| 2004 | 1        | 5.88%   |

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
| 8.01-16.0  | 5        | 27.78%  |
| 3.01-4.0   | 4        | 22.22%  |
| 32.01-64.0 | 2        | 11.11%  |
| 16.01-24.0 | 2        | 11.11%  |
| 0.51-1.0   | 2        | 11.11%  |
| 4.01-8.0   | 1        | 5.56%   |
| 1.01-2.0   | 1        | 5.56%   |
| 0.01-0.5   | 1        | 5.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 7        | 41.18%  |
| 1.01-2.0  | 3        | 17.65%  |
| 3.01-4.0  | 2        | 11.76%  |
| 0.51-1.0  | 2        | 11.76%  |
| 4.01-8.0  | 1        | 5.88%   |
| 8.01-16.0 | 1        | 5.88%   |
| Unknown   | 1        | 5.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 7        | 41.18%  |
| 2      | 4        | 23.53%  |
| 4      | 3        | 17.65%  |
| 3      | 3        | 17.65%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 82.35%  |
| Yes       | 3        | 17.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 16       | 94.12%  |
| No        | 1        | 5.88%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 76.47%  |
| Yes       | 4        | 23.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 82.35%  |
| Yes       | 3        | 17.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 3        | 17.65%  |
| Russia      | 2        | 11.76%  |
| Norway      | 2        | 11.76%  |
| Ukraine     | 1        | 5.88%   |
| UK          | 1        | 5.88%   |
| Switzerland | 1        | 5.88%   |
| Sweden      | 1        | 5.88%   |
| Spain       | 1        | 5.88%   |
| Pakistan    | 1        | 5.88%   |
| Indonesia   | 1        | 5.88%   |
| Guatemala   | 1        | 5.88%   |
| Germany     | 1        | 5.88%   |
| Austria     | 1        | 5.88%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Desktops | Percent |
|--------------------|----------|---------|
| St Petersburg      | 2        | 11.76%  |
| Manitowoc          | 2        | 11.76%  |
| As                 | 2        | 11.76%  |
| Zurich             | 1        | 5.88%   |
| Sant Pere de Ribes | 1        | 5.88%   |
| Sankt PГ¶lten    | 1        | 5.88%   |
| Redwood City       | 1        | 5.88%   |
| Munich             | 1        | 5.88%   |
| Lahore             | 1        | 5.88%   |
| Kharkiv            | 1        | 5.88%   |
| Jember             | 1        | 5.88%   |
| Guatemala City     | 1        | 5.88%   |
| Barrow in Furness  | 1        | 5.88%   |
| Bandhagen          | 1        | 5.88%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 10     | 20%     |
| Samsung Electronics | 5        | 11     | 20%     |
| WDC                 | 2        | 2      | 8%      |
| HGST                | 2        | 2      | 8%      |
| Unknown             | 1        | 1      | 4%      |
| Transcend           | 1        | 1      | 4%      |
| Toshiba             | 1        | 1      | 4%      |
| SK Hynix            | 1        | 1      | 4%      |
| SanDisk             | 1        | 1      | 4%      |
| LITEON              | 1        | 1      | 4%      |
| Lexar               | 1        | 1      | 4%      |
| Intel               | 1        | 2      | 4%      |
| Hitachi             | 1        | 1      | 4%      |
| Crucial             | 1        | 4      | 4%      |
| A-DATA Technology   | 1        | 1      | 4%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Samsung SSD 960 EVO 500GB             | 2        | 6.9%    |
| WDC WD20EZRZ-00Z 2TB                  | 1        | 3.45%   |
| WDC WD10JPVX-75JC3T0 1TB              | 1        | 3.45%   |
| Unknown MMC Card  32GB                | 1        | 3.45%   |
| Transcend SSD 1GB                     | 1        | 3.45%   |
| Toshiba MK3252GS 320GB                | 1        | 3.45%   |
| SK Hynix SC300 M.2 2280 256 256GB SSD | 1        | 3.45%   |
| Seagate ST4000VN008-2DR1 4TB          | 1        | 3.45%   |
| Seagate ST380815AS 80GB               | 1        | 3.45%   |
| Seagate ST3500418AS 500GB             | 1        | 3.45%   |
| Seagate ST2000DL001-9VT1 2TB          | 1        | 3.45%   |
| Seagate ST1000LM048-2E71 1TB          | 1        | 3.45%   |
| SanDisk SDSA6MM 16GB SSD              | 1        | 3.45%   |
| Samsung SSD 970 EVO Plus 1TB          | 1        | 3.45%   |
| Samsung SSD 970 EVO 250GB             | 1        | 3.45%   |
| Samsung SSD 870 EVO 1TB               | 1        | 3.45%   |
| Samsung SSD 850 EVO 500GB             | 1        | 3.45%   |
| Samsung SSD 750 EVO 250GB             | 1        | 3.45%   |
| Samsung SP0411N 40GB                  | 1        | 3.45%   |
| LITEON CV3-CE128 128GB SSD            | 1        | 3.45%   |
| Lexar 256GB SSD                       | 1        | 3.45%   |
| Intel SSDSC2BW24 240GB                | 1        | 3.45%   |
| Intel SSDSC2BB24 240GB                | 1        | 3.45%   |
| Hitachi HDS72105 500GB                | 1        | 3.45%   |
| HGST HTS541010B7 1TB                  | 1        | 3.45%   |
| HGST HDN728080AL 8TB                  | 1        | 3.45%   |
| Crucial CT120BX500SSD1 120GB          | 1        | 3.45%   |
| A-DATA SU750 256GB SSD                | 1        | 3.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 10     | 41.67%  |
| WDC                 | 2        | 2      | 16.67%  |
| HGST                | 2        | 2      | 16.67%  |
| Toshiba             | 1        | 1      | 8.33%   |
| Samsung Electronics | 1        | 2      | 8.33%   |
| Hitachi             | 1        | 1      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 5      | 27.27%  |
| Transcend           | 1        | 1      | 9.09%   |
| SK Hynix            | 1        | 1      | 9.09%   |
| SanDisk             | 1        | 1      | 9.09%   |
| LITEON              | 1        | 1      | 9.09%   |
| Lexar               | 1        | 1      | 9.09%   |
| Intel               | 1        | 2      | 9.09%   |
| Crucial             | 1        | 4      | 9.09%   |
| A-DATA Technology   | 1        | 1      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 10       | 17     | 41.67%  |
| HDD  | 10       | 18     | 41.67%  |
| NVMe | 3        | 4      | 12.5%   |
| MMC  | 1        | 1      | 4.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 16       | 33     | 76.19%  |
| NVMe | 3        | 4      | 14.29%  |
| SAS  | 1        | 2      | 4.76%   |
| MMC  | 1        | 1      | 4.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 14       | 22     | 70%     |
| 0.51-1.0   | 3        | 5      | 15%     |
| 3.01-4.0   | 1        | 4      | 5%      |
| 1.01-2.0   | 1        | 3      | 5%      |
| 4.01-10.0  | 1        | 1      | 5%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 6        | 35.29%  |
| 21-50      | 4        | 23.53%  |
| 1-20       | 3        | 17.65%  |
| 2001-3000  | 2        | 11.76%  |
| 251-500    | 1        | 5.88%   |
| 101-250    | 1        | 5.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 9        | 52.94%  |
| Unknown | 6        | 35.29%  |
| 251-500 | 1        | 5.88%   |
| 51-100  | 1        | 5.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Toshiba MK3252GS 320GB           | 1        | 1      | 33.33%  |
| SanDisk SDSA6MM 16GB SSD         | 1        | 1      | 33.33%  |
| Samsung Electronics SP0411N 40GB | 1        | 2      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Toshiba             | 1        | 1      | 33.33%  |
| SanDisk             | 1        | 1      | 33.33%  |
| Samsung Electronics | 1        | 2      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Toshiba             | 1        | 1      | 50%     |
| Samsung Electronics | 1        | 2      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 3      | 66.67%  |
| SSD  | 1        | 1      | 33.33%  |

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
| Works    | 13       | 33     | 72.22%  |
| Malfunc  | 3        | 4      | 16.67%  |
| Detected | 2        | 3      | 11.11%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 14       | 63.64%  |
| Samsung Electronics       | 3        | 13.64%  |
| VIA Technologies          | 1        | 4.55%   |
| Nvidia                    | 1        | 4.55%   |
| LSI Logic / Symbios Logic | 1        | 4.55%   |
| ASMedia Technology        | 1        | 4.55%   |
| Adaptec                   | 1        | 4.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3        | 12%     |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2        | 8%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 8%      |
| Intel Comet Lake SATA AHCI Controller                                          | 2        | 8%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 8%      |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1        | 4%      |
| Nvidia MCP61 SATA Controller                                                   | 1        | 4%      |
| Nvidia MCP61 IDE                                                               | 1        | 4%      |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 1        | 4%      |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1        | 4%      |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 4%      |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1        | 4%      |
| Intel 82Q35 Express PT IDER Controller                                         | 1        | 4%      |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 1        | 4%      |
| Intel 82801DB (ICH4) IDE Controller                                            | 1        | 4%      |
| Intel 6 Series/C200 Series Desktop SATA RAID Controller                        | 1        | 4%      |
| Intel 5 Series/3400 Series Chipset SATA RAID Controller                        | 1        | 4%      |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 4%      |
| Adaptec Series 6 - 6G SAS/PCIe 2                                               | 1        | 4%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 11       | 50%     |
| IDE  | 4        | 18.18%  |
| RAID | 3        | 13.64%  |
| NVMe | 3        | 13.64%  |
| SAS  | 1        | 4.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 15       | 88.24%  |
| AMD    | 2        | 11.76%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Core i9-10900 CPU @ 2.80GHz      | 2        | 11.76%  |
| Intel Xeon CPU X3430 @ 2.40GHz         | 1        | 5.88%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz | 1        | 5.88%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 1        | 5.88%   |
| Intel Core i5-4590T CPU @ 2.00GHz      | 1        | 5.88%   |
| Intel Core i5-3450 CPU @ 3.10GHz       | 1        | 5.88%   |
| Intel Core i3-4150 CPU @ 3.50GHz       | 1        | 5.88%   |
| Intel Core i3-3220T CPU @ 2.80GHz      | 1        | 5.88%   |
| Intel Core i3-2100 CPU @ 3.10GHz       | 1        | 5.88%   |
| Intel Celeron M processor 1.00GHz      | 1        | 5.88%   |
| Intel Celeron CPU J3455 @ 1.50GHz      | 1        | 5.88%   |
| Intel Celeron CPU J1800 @ 2.41GHz      | 1        | 5.88%   |
| Intel Celeron CPU G1850 @ 2.90GHz      | 1        | 5.88%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz      | 1        | 5.88%   |
| AMD Sempron 145 Processor              | 1        | 5.88%   |
| AMD Mobile Duron processor             | 1        | 5.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 3        | 17.65%  |
| Intel Core i3      | 3        | 17.65%  |
| Intel Celeron      | 3        | 17.65%  |
| Intel Core i9      | 2        | 11.76%  |
| Other              | 1        | 5.88%   |
| Intel Xeon         | 1        | 5.88%   |
| Intel Pentium Dual | 1        | 5.88%   |
| Intel Celeron M    | 1        | 5.88%   |
| Intel Atom         | 1        | 5.88%   |
| AMD Sempron        | 1        | 5.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 6        | 35.29%  |
| 4      | 5        | 29.41%  |
| 1      | 3        | 17.65%  |
| 10     | 2        | 11.76%  |
| 6      | 1        | 5.88%   |

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
| 1      | 12       | 70.59%  |
| 2      | 5        | 29.41%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 8        | 47.06%  |
| Unknown        | 7        | 41.18%  |
| 32-bit         | 2        | 11.76%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 7        | 38.89%  |
| 0x306a9    | 2        | 11.11%  |
| 0xa0655    | 1        | 5.56%   |
| 0x906ea    | 1        | 5.56%   |
| 0x6fd      | 1        | 5.56%   |
| 0x6d8      | 1        | 5.56%   |
| 0x506c9    | 1        | 5.56%   |
| 0x406c4    | 1        | 5.56%   |
| 0x306c3    | 1        | 5.56%   |
| 0x106e5    | 1        | 5.56%   |
| 0x010000b6 | 1        | 5.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 3        | 17.65%  |
| Silvermont  | 2        | 11.76%  |
| IvyBridge   | 2        | 11.76%  |
| CometLake   | 2        | 11.76%  |
| SandyBridge | 1        | 5.88%   |
| P6          | 1        | 5.88%   |
| Nehalem     | 1        | 5.88%   |
| KabyLake    | 1        | 5.88%   |
| K6          | 1        | 5.88%   |
| K10         | 1        | 5.88%   |
| Goldmont    | 1        | 5.88%   |
| Core        | 1        | 5.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 13       | 76.47%  |
| VIA Technologies           | 1        | 5.88%   |
| Nvidia                     | 1        | 5.88%   |
| Matrox Electronics Systems | 1        | 5.88%   |
| AMD                        | 1        | 5.88%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2        | 11.76%  |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 11.76%  |
| VIA Technologies KM400/KN400/P4M800 [S3 UniChrome]                                       | 1        | 5.88%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1        | 5.88%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1        | 5.88%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 5.88%   |
| Intel HD Graphics 500                                                                    | 1        | 5.88%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1        | 5.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 5.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1        | 5.88%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1        | 5.88%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1        | 5.88%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1        | 5.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 5.88%   |
| AMD ES1000                                                                               | 1        | 5.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 13       | 76.47%  |
| 1 x VIA    | 1        | 5.88%   |
| 1 x Nvidia | 1        | 5.88%   |
| 1 x Matrox | 1        | 5.88%   |
| 1 x AMD    | 1        | 5.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 13       | 76.47%  |
| Unknown | 4        | 23.53%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 82.35%  |
| 0.01-0.5   | 2        | 11.76%  |
| 1.01-2.0   | 1        | 5.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 2        | 20%     |
| Dell                | 2        | 20%     |
| AOC                 | 2        | 20%     |
| ViewSonic           | 1        | 10%     |
| Goldstar            | 1        | 10%     |
| BenQ                | 1        | 10%     |
| Acer                | 1        | 10%     |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch | 2        | 20%     |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch         | 1        | 10%     |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch          | 1        | 10%     |
| Dell P2311H DEL4066 1920x1080 509x286mm 23.0-inch                | 1        | 10%     |
| Dell E172FP DELA00A 1280x1024 338x270mm 17.0-inch                | 1        | 10%     |
| BenQ BL2405 BNQ8016 1920x1080 531x298mm 24.0-inch                | 1        | 10%     |
| AOC 718Swag-1 AOCC750 1440x900 367x230mm 17.1-inch               | 1        | 10%     |
| AOC 2476WM AOC2476 1920x1080 521x293mm 23.5-inch                 | 1        | 10%     |
| Acer SA220Q ACR057D 1920x1080 476x268mm 21.5-inch                | 1        | 10%     |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 4        | 40%     |
| 3440x1440          | 2        | 20%     |
| 3840x2160 (4K)     | 1        | 10%     |
| 1680x1050 (WSXGA+) | 1        | 10%     |
| 1440x900 (WXGA+)   | 1        | 10%     |
| 1280x1024 (SXGA)   | 1        | 10%     |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 34     | 2        | 20%     |
| 23     | 2        | 20%     |
| 17     | 2        | 20%     |
| 27     | 1        | 10%     |
| 24     | 1        | 10%     |
| 21     | 1        | 10%     |
| 20     | 1        | 10%     |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 4        | 40%     |
| 701-800     | 2        | 20%     |
| 401-500     | 2        | 20%     |
| 351-400     | 1        | 10%     |
| 301-350     | 1        | 10%     |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 5        | 55.56%  |
| 21/9  | 2        | 22.22%  |
| 5/4   | 1        | 11.11%  |
| 16/10 | 1        | 11.11%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 3        | 30%     |
| 351-500        | 2        | 20%     |
| 151-200        | 2        | 20%     |
| 301-350        | 1        | 10%     |
| 141-150        | 1        | 10%     |
| 131-140        | 1        | 10%     |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 5        | 55.56%  |
| 1-50    | 2        | 22.22%  |
| 161-240 | 1        | 11.11%  |
| 101-120 | 1        | 11.11%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10       | 58.82%  |
| 0     | 7        | 41.18%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 8        | 36.36%  |
| Intel                 | 5        | 22.73%  |
| Qualcomm Atheros      | 2        | 9.09%   |
| Broadcom              | 2        | 9.09%   |
| Xiaomi                | 1        | 4.55%   |
| VIA Technologies      | 1        | 4.55%   |
| Qualcomm              | 1        | 4.55%   |
| Nvidia                | 1        | 4.55%   |
| D-Link System         | 1        | 4.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7        | 29.17%  |
| Intel Ethernet Controller I225-V                                  | 2        | 8.33%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2        | 8.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 4.17%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 4.17%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 4.17%   |
| Qualcomm Redmi Note 7                                             | 1        | 4.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1        | 4.17%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 4.17%   |
| Nvidia MCP61 Ethernet                                             | 1        | 4.17%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 4.17%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 4.17%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 4.17%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 4.17%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1        | 4.17%   |
| Broadcom BCM43227 802.11b/g/n                                     | 1        | 4.17%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 2        | 50%     |
| Qualcomm Atheros | 1        | 25%     |
| Broadcom         | 1        | 25%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Comet Lake PCH CNVi WiFi                             | 2        | 50%     |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1        | 25%     |
| Broadcom BCM43227 802.11b/g/n                              | 1        | 25%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 8        | 40%     |
| Intel                 | 5        | 25%     |
| Xiaomi                | 1        | 5%      |
| VIA Technologies      | 1        | 5%      |
| Qualcomm Atheros      | 1        | 5%      |
| Qualcomm              | 1        | 5%      |
| Nvidia                | 1        | 5%      |
| D-Link System         | 1        | 5%      |
| Broadcom              | 1        | 5%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7        | 35%     |
| Intel Ethernet Controller I225-V                                  | 2        | 10%     |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 5%      |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 5%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 5%      |
| Qualcomm Redmi Note 7                                             | 1        | 5%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 5%      |
| Nvidia MCP61 Ethernet                                             | 1        | 5%      |
| Intel Ethernet Connection (7) I219-V                              | 1        | 5%      |
| Intel 82578DM Gigabit Network Connection                          | 1        | 5%      |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 5%      |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 5%      |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1        | 5%      |

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
| Ethernet | 15       | 88.24%  |
| WiFi     | 2        | 11.76%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10       | 58.82%  |
| 2     | 5        | 29.41%  |
| 4     | 1        | 5.88%   |
| 3     | 1        | 5.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 15       | 88.24%  |
| Yes  | 2        | 11.76%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 2        | 66.67%  |
| IMC Networks | 1        | 33.33%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel AX201 Bluetooth         | 2        | 66.67%  |
| IMC Networks Bluetooth Device | 1        | 33.33%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 12       | 85.71%  |
| VIA Technologies | 1        | 7.14%   |
| Nvidia           | 1        | 7.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 17.65%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 17.65%  |
| Intel Comet Lake PCH cAVS                                                  | 2        | 11.76%  |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1        | 5.88%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 5.88%   |
| Intel USB PnP Sound Device                                                 | 1        | 5.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1        | 5.88%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 5.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1        | 5.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 5.88%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 1        | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 5.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 5        | 21.74%  |
| SK Hynix            | 5        | 21.74%  |
| Crucial             | 5        | 21.74%  |
| Samsung Electronics | 1        | 4.35%   |
| Qimonda             | 1        | 4.35%   |
| Micron Technology   | 1        | 4.35%   |
| Kingston            | 1        | 4.35%   |
| Hewlett-Packard     | 1        | 4.35%   |
| Elpida              | 1        | 4.35%   |
| Corsair             | 1        | 4.35%   |
| Cors                | 1        | 4.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s  | 2        | 8%      |
| Unknown RAM Module 512MB DIMM                             | 1        | 4%      |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                 | 1        | 4%      |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s              | 1        | 4%      |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s              | 1        | 4%      |
| Unknown RAM Module 128MB DIMM                             | 1        | 4%      |
| Unknown RAM Module 1024MB DIMM SDRAM                      | 1        | 4%      |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s      | 1        | 4%      |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s      | 1        | 4%      |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s | 1        | 4%      |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s | 1        | 4%      |
| SK Hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s   | 1        | 4%      |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s       | 1        | 4%      |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s       | 1        | 4%      |
| Qimonda RAM 64T128020HU3SB 1024MB DIMM DDR2 667MT/s       | 1        | 4%      |
| Micron RAM 8KTF51264AZ-1G9P1 4GB DIMM DDR3 1866MT/s       | 1        | 4%      |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s     | 1        | 4%      |
| HP RAM Module 4GB DIMM DDR3 1600MT/s                      | 1        | 4%      |
| Elpida RAM EBE10UE8ACWA-6E-E 1GB DIMM DDR2 667MT/s        | 1        | 4%      |
| Crucial RAM CT25664BA160B.C16F 2GB DIMM DDR3 1600MT/s     | 1        | 4%      |
| Crucial RAM CT102464BA160B.M16 8GB DIMM DDR3 1600MT/s     | 1        | 4%      |
| Crucial RAM BLS8G4D240FSEK.8FBD 8192MB DIMM DDR4 2400MT/s | 1        | 4%      |
| Corsair RAM Module 8192MB DIMM DDR3 1333MT/s              | 1        | 4%      |
| Cors RAM CMX16GX3M2A1333C9 8192MB DIMM DDR3 1333MT/s      | 1        | 4%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 11       | 64.71%  |
| DDR4    | 3        | 17.65%  |
| SDRAM   | 1        | 5.88%   |
| DDR2    | 1        | 5.88%   |
| Unknown | 1        | 5.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 15       | 88.24%  |
| SODIMM | 2        | 11.76%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 6        | 31.58%  |
| 4096  | 4        | 21.05%  |
| 2048  | 3        | 15.79%  |
| 16384 | 2        | 10.53%  |
| 1024  | 2        | 10.53%  |
| 512   | 1        | 5.26%   |
| 128   | 1        | 5.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 9        | 47.37%  |
| 3600    | 2        | 10.53%  |
| 1333    | 2        | 10.53%  |
| Unknown | 2        | 10.53%  |
| 2400    | 1        | 5.26%   |
| 1866    | 1        | 5.26%   |
| 1800    | 1        | 5.26%   |
| 667     | 1        | 5.26%   |

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

Zero info for selected period =(

Camera Model
------------

Camera device models

Zero info for selected period =(

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
| 0     | 12       | 70.59%  |
| 1     | 4        | 23.53%  |
| 5     | 1        | 5.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 4        | 50%     |
| Sound                    | 1        | 12.5%   |
| Net/wireless             | 1        | 12.5%   |
| Net/ethernet             | 1        | 12.5%   |
| Communication controller | 1        | 12.5%   |

