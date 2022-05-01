Alpine - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Alpine.

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

Total: 23

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | Z97-K                       | [53cba6b4f8](https://linux-hardware.org/?probe=53cba6b4f8) | Apr 14, 2022 |
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
| Alpine 3.12.0               | 5        | 26.32%  |
| Alpine 3.13.0_alpha20200626 | 3        | 15.79%  |
| Alpine 3.11.2               | 2        | 10.53%  |
| Alpine 3.8.4                | 1        | 5.26%   |
| Alpine 3.16.0_alpha20220328 | 1        | 5.26%   |
| Alpine 3.15.0               | 1        | 5.26%   |
| Alpine 3.14.2               | 1        | 5.26%   |
| Alpine 3.13.6               | 1        | 5.26%   |
| Alpine 3.13.2               | 1        | 5.26%   |
| Alpine 3.13.1               | 1        | 5.26%   |
| Alpine 3.13.0_alpha20201218 | 1        | 5.26%   |
| Alpine 3.12.3               | 1        | 5.26%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Alpine | 18       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.4.43-1-lts      | 5        | 26.32%  |
| 5.8.0             | 1        | 5.26%   |
| 5.4.84-0-lts      | 1        | 5.26%   |
| 5.4.6-0-lts       | 1        | 5.26%   |
| 5.4.58-0-lts      | 1        | 5.26%   |
| 5.4.57-0-lts      | 1        | 5.26%   |
| 5.17.3-0-edge     | 1        | 5.26%   |
| 5.15.17-0-lts     | 1        | 5.26%   |
| 5.10.81           | 1        | 5.26%   |
| 5.10.61-0-lts     | 1        | 5.26%   |
| 5.10.16-0-lts     | 1        | 5.26%   |
| 5.10.12-0-lts     | 1        | 5.26%   |
| 5.10.1-0-lts      | 1        | 5.26%   |
| 4.14.89-0-vanilla | 1        | 5.26%   |
| 3.10.105          | 1        | 5.26%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.43   | 5        | 26.32%  |
| 5.8.0    | 1        | 5.26%   |
| 5.4.84   | 1        | 5.26%   |
| 5.4.6    | 1        | 5.26%   |
| 5.4.58   | 1        | 5.26%   |
| 5.4.57   | 1        | 5.26%   |
| 5.17.3   | 1        | 5.26%   |
| 5.15.17  | 1        | 5.26%   |
| 5.10.81  | 1        | 5.26%   |
| 5.10.61  | 1        | 5.26%   |
| 5.10.16  | 1        | 5.26%   |
| 5.10.12  | 1        | 5.26%   |
| 5.10.1   | 1        | 5.26%   |
| 4.14.89  | 1        | 5.26%   |
| 3.10.105 | 1        | 5.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 9        | 47.37%  |
| 5.10    | 5        | 26.32%  |
| 5.8     | 1        | 5.26%   |
| 5.17    | 1        | 5.26%   |
| 5.15    | 1        | 5.26%   |
| 4.14    | 1        | 5.26%   |
| 3.10    | 1        | 5.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 16       | 88.89%  |
| i686   | 2        | 11.11%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 15       | 83.33%  |
| XFCE    | 1        | 5.56%   |
| sway    | 1        | 5.56%   |
| i3      | 1        | 5.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 12       | 66.67%  |
| X11     | 5        | 27.78%  |
| Wayland | 1        | 5.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 17       | 94.44%  |
| LightDM | 1        | 5.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| C       | 9        | 50%     |
| Unknown | 8        | 44.44%  |
| en_US   | 1        | 5.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 14       | 77.78%  |
| EFI  | 4        | 22.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 15       | 83.33%  |
| Tmpfs   | 1        | 5.56%   |
| Btrfs   | 1        | 5.56%   |
| Unknown | 1        | 5.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 8        | 42.11%  |
| GPT     | 7        | 36.84%  |
| MBR     | 4        | 21.05%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 83.33%  |
| Yes       | 3        | 16.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 88.89%  |
| Yes       | 2        | 11.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 4        | 22.22%  |
| ASUSTek Computer    | 4        | 22.22%  |
| Gigabyte Technology | 2        | 11.11%  |
| ASRock              | 2        | 11.11%  |
| VIA Technologies    | 1        | 5.56%   |
| Shuttle             | 1        | 5.56%   |
| Hewlett-Packard     | 1        | 5.56%   |
| Fujitsu             | 1        | 5.56%   |
| eMachines           | 1        | 5.56%   |
| Unknown             | 1        | 5.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Gigabyte Z490I AORUS ULTRA   | 2        | 11.11%  |
| VIA KM266APro-835            | 1        | 5.56%   |
| Shuttle DS81D                | 1        | 5.56%   |
| HP ProLiant MicroServer Gen8 | 1        | 5.56%   |
| Fujitsu PRIMERGY TX100 S2    | 1        | 5.56%   |
| eMachines EL1352G            | 1        | 5.56%   |
| Dell OptiPlex 755            | 1        | 5.56%   |
| Dell OptiPlex 3020M          | 1        | 5.56%   |
| Dell OptiPlex 3010           | 1        | 5.56%   |
| Dell Inspiron 3647           | 1        | 5.56%   |
| ASUS TS10                    | 1        | 5.56%   |
| ASUS PRIME H370M-PLUS        | 1        | 5.56%   |
| ASUS P8H67-V                 | 1        | 5.56%   |
| ASUS All Series              | 1        | 5.56%   |
| ASRock J3455M                | 1        | 5.56%   |
| ASRock D1800B-ITX            | 1        | 5.56%   |
| Unknown                      | 1        | 5.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Dell OptiPlex     | 3        | 16.67%  |
| Gigabyte Z490I    | 2        | 11.11%  |
| VIA KM266APro-835 | 1        | 5.56%   |
| Shuttle DS81D     | 1        | 5.56%   |
| HP ProLiant       | 1        | 5.56%   |
| Fujitsu PRIMERGY  | 1        | 5.56%   |
| eMachines EL1352G | 1        | 5.56%   |
| Dell Inspiron     | 1        | 5.56%   |
| ASUS TS10         | 1        | 5.56%   |
| ASUS PRIME        | 1        | 5.56%   |
| ASUS P8H67-V      | 1        | 5.56%   |
| ASUS All          | 1        | 5.56%   |
| ASRock J3455M     | 1        | 5.56%   |
| ASRock D1800B-ITX | 1        | 5.56%   |
| Unknown           | 1        | 5.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2014 | 5        | 27.78%  |
| 2010 | 3        | 16.67%  |
| 2020 | 2        | 11.11%  |
| 2018 | 1        | 5.56%   |
| 2017 | 1        | 5.56%   |
| 2016 | 1        | 5.56%   |
| 2013 | 1        | 5.56%   |
| 2012 | 1        | 5.56%   |
| 2009 | 1        | 5.56%   |
| 2007 | 1        | 5.56%   |
| 2004 | 1        | 5.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 18       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 18       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 18       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 8.01-16.0  | 5        | 26.32%  |
| 3.01-4.0   | 4        | 21.05%  |
| 16.01-24.0 | 3        | 15.79%  |
| 32.01-64.0 | 2        | 10.53%  |
| 0.51-1.0   | 2        | 10.53%  |
| 4.01-8.0   | 1        | 5.26%   |
| 1.01-2.0   | 1        | 5.26%   |
| 0.01-0.5   | 1        | 5.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.01-0.5  | 7        | 38.89%  |
| 1.01-2.0  | 4        | 22.22%  |
| 3.01-4.0  | 2        | 11.11%  |
| 0.51-1.0  | 2        | 11.11%  |
| 4.01-8.0  | 1        | 5.56%   |
| 8.01-16.0 | 1        | 5.56%   |
| Unknown   | 1        | 5.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 7        | 38.89%  |
| 3      | 4        | 22.22%  |
| 2      | 4        | 22.22%  |
| 4      | 3        | 16.67%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 83.33%  |
| Yes       | 3        | 16.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 17       | 94.44%  |
| No        | 1        | 5.56%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 77.78%  |
| Yes       | 4        | 22.22%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 77.78%  |
| Yes       | 4        | 22.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 3        | 16.67%  |
| Sweden      | 2        | 11.11%  |
| Russia      | 2        | 11.11%  |
| Norway      | 2        | 11.11%  |
| Ukraine     | 1        | 5.56%   |
| UK          | 1        | 5.56%   |
| Switzerland | 1        | 5.56%   |
| Spain       | 1        | 5.56%   |
| Pakistan    | 1        | 5.56%   |
| Indonesia   | 1        | 5.56%   |
| Guatemala   | 1        | 5.56%   |
| Germany     | 1        | 5.56%   |
| Austria     | 1        | 5.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Desktops | Percent |
|--------------------|----------|---------|
| St Petersburg      | 2        | 11.11%  |
| Manitowoc          | 2        | 11.11%  |
| As                 | 2        | 11.11%  |
| Zurich             | 1        | 5.56%   |
| Stockholm          | 1        | 5.56%   |
| Sant Pere de Ribes | 1        | 5.56%   |
| Sankt PГ¶lten    | 1        | 5.56%   |
| Redwood City       | 1        | 5.56%   |
| Munich             | 1        | 5.56%   |
| Lahore             | 1        | 5.56%   |
| Kharkiv            | 1        | 5.56%   |
| Jember             | 1        | 5.56%   |
| Guatemala City     | 1        | 5.56%   |
| Barrow in Furness  | 1        | 5.56%   |
| Bandhagen          | 1        | 5.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 11     | 21.43%  |
| Samsung Electronics | 5        | 11     | 17.86%  |
| WDC                 | 3        | 3      | 10.71%  |
| Intel               | 2        | 3      | 7.14%   |
| HGST                | 2        | 2      | 7.14%   |
| Unknown             | 1        | 1      | 3.57%   |
| Transcend           | 1        | 1      | 3.57%   |
| Toshiba             | 1        | 1      | 3.57%   |
| SK Hynix            | 1        | 1      | 3.57%   |
| SanDisk             | 1        | 1      | 3.57%   |
| LITEON              | 1        | 1      | 3.57%   |
| Lexar               | 1        | 1      | 3.57%   |
| Hitachi             | 1        | 1      | 3.57%   |
| Crucial             | 1        | 4      | 3.57%   |
| A-DATA Technology   | 1        | 1      | 3.57%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Samsung SSD 960 EVO 500GB             | 2        | 6.25%   |
| WDC WD20EZRZ-00Z 2TB                  | 1        | 3.13%   |
| WDC WD10JPVX-75JC3T0 1TB              | 1        | 3.13%   |
| WDC WD10EZEX-21M2NA0 1TB              | 1        | 3.13%   |
| Unknown MMC Card  32GB                | 1        | 3.13%   |
| Transcend SSD 1GB                     | 1        | 3.13%   |
| Toshiba MK3252GS 320GB                | 1        | 3.13%   |
| SK Hynix SC300 M.2 2280 256 256GB SSD | 1        | 3.13%   |
| Seagate ST4000VN008-2DR1 4TB          | 1        | 3.13%   |
| Seagate ST380815AS 80GB               | 1        | 3.13%   |
| Seagate ST3500418AS 500GB             | 1        | 3.13%   |
| Seagate ST2000DL001-9VT1 2TB          | 1        | 3.13%   |
| Seagate ST1000LM048-2E71 1TB          | 1        | 3.13%   |
| Seagate ST1000DM010-2EP102 1TB        | 1        | 3.13%   |
| SanDisk SDSA6MM 16GB SSD              | 1        | 3.13%   |
| Samsung SSD 970 EVO Plus 1TB          | 1        | 3.13%   |
| Samsung SSD 970 EVO 250GB             | 1        | 3.13%   |
| Samsung SSD 870 EVO 1TB               | 1        | 3.13%   |
| Samsung SSD 850 EVO 500GB             | 1        | 3.13%   |
| Samsung SSD 750 EVO 250GB             | 1        | 3.13%   |
| Samsung SP0411N 34GB                  | 1        | 3.13%   |
| LITEON CV3-CE128 128GB SSD            | 1        | 3.13%   |
| Lexar 256GB SSD                       | 1        | 3.13%   |
| Intel SSDSC2BW24 240GB                | 1        | 3.13%   |
| Intel SSDSC2BW120A4 120GB             | 1        | 3.13%   |
| Intel SSDSC2BB24 240GB                | 1        | 3.13%   |
| Hitachi HDS72105 500GB                | 1        | 3.13%   |
| HGST HTS541010B7 1TB                  | 1        | 3.13%   |
| HGST HDN728080AL 8TB                  | 1        | 3.13%   |
| Crucial CT120BX500SSD1 120GB          | 1        | 3.13%   |
| A-DATA SU750 256GB SSD                | 1        | 3.13%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 11     | 42.86%  |
| WDC                 | 3        | 3      | 21.43%  |
| HGST                | 2        | 2      | 14.29%  |
| Toshiba             | 1        | 1      | 7.14%   |
| Samsung Electronics | 1        | 2      | 7.14%   |
| Hitachi             | 1        | 1      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 5      | 25%     |
| Intel               | 2        | 3      | 16.67%  |
| Transcend           | 1        | 1      | 8.33%   |
| SK Hynix            | 1        | 1      | 8.33%   |
| SanDisk             | 1        | 1      | 8.33%   |
| LITEON              | 1        | 1      | 8.33%   |
| Lexar               | 1        | 1      | 8.33%   |
| Crucial             | 1        | 4      | 8.33%   |
| A-DATA Technology   | 1        | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 11       | 18     | 42.31%  |
| HDD  | 11       | 20     | 42.31%  |
| NVMe | 3        | 4      | 11.54%  |
| MMC  | 1        | 1      | 3.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 17       | 36     | 77.27%  |
| NVMe | 3        | 4      | 13.64%  |
| SAS  | 1        | 2      | 4.55%   |
| MMC  | 1        | 1      | 4.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 15       | 23     | 68.18%  |
| 0.51-1.0   | 4        | 7      | 18.18%  |
| 3.01-4.0   | 1        | 4      | 4.55%   |
| 1.01-2.0   | 1        | 3      | 4.55%   |
| 4.01-10.0  | 1        | 1      | 4.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 6        | 33.33%  |
| 21-50      | 4        | 22.22%  |
| 1-20       | 3        | 16.67%  |
| 2001-3000  | 2        | 11.11%  |
| 251-500    | 1        | 5.56%   |
| 101-250    | 1        | 5.56%   |
| 1001-2000  | 1        | 5.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 9        | 50%     |
| Unknown   | 6        | 33.33%  |
| 251-500   | 1        | 5.56%   |
| 1001-2000 | 1        | 5.56%   |
| 51-100    | 1        | 5.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Toshiba MK3252GS 320GB           | 1        | 1      | 33.33%  |
| SanDisk SDSA6MM 16GB SSD         | 1        | 1      | 33.33%  |
| Samsung Electronics SP0411N 34GB | 1        | 2      | 33.33%  |

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
| Works    | 14       | 36     | 73.68%  |
| Malfunc  | 3        | 4      | 15.79%  |
| Detected | 2        | 3      | 10.53%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 15       | 65.22%  |
| Samsung Electronics       | 3        | 13.04%  |
| VIA Technologies          | 1        | 4.35%   |
| Nvidia                    | 1        | 4.35%   |
| LSI Logic / Symbios Logic | 1        | 4.35%   |
| ASMedia Technology        | 1        | 4.35%   |
| Adaptec                   | 1        | 4.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3        | 11.54%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2        | 7.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 7.69%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2        | 7.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 7.69%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1        | 3.85%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 3.85%   |
| Nvidia MCP61 IDE                                                               | 1        | 3.85%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 1        | 3.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1        | 3.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 3.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1        | 3.85%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1        | 3.85%   |
| Intel 82Q35 Express PT IDER Controller                                         | 1        | 3.85%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 1        | 3.85%   |
| Intel 82801DB (ICH4) IDE Controller                                            | 1        | 3.85%   |
| Intel 6 Series/C200 Series Desktop SATA RAID Controller                        | 1        | 3.85%   |
| Intel 5 Series/3400 Series Chipset SATA RAID Controller                        | 1        | 3.85%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 3.85%   |
| Adaptec Series 6 - 6G SAS/PCIe 2                                               | 1        | 3.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 12       | 52.17%  |
| IDE  | 4        | 17.39%  |
| RAID | 3        | 13.04%  |
| NVMe | 3        | 13.04%  |
| SAS  | 1        | 4.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 16       | 88.89%  |
| AMD    | 2        | 11.11%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Core i9-10900 CPU @ 2.80GHz      | 2        | 11.11%  |
| Intel Xeon CPU X3430 @ 2.40GHz         | 1        | 5.56%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz | 1        | 5.56%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 1        | 5.56%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 1        | 5.56%   |
| Intel Core i5-4590T CPU @ 2.00GHz      | 1        | 5.56%   |
| Intel Core i5-3450 CPU @ 3.10GHz       | 1        | 5.56%   |
| Intel Core i3-4150 CPU @ 3.50GHz       | 1        | 5.56%   |
| Intel Core i3-3220T CPU @ 2.80GHz      | 1        | 5.56%   |
| Intel Core i3-2100 CPU @ 3.10GHz       | 1        | 5.56%   |
| Intel Celeron M processor 1.00GHz      | 1        | 5.56%   |
| Intel Celeron CPU J3455 @ 1.50GHz      | 1        | 5.56%   |
| Intel Celeron CPU J1800 @ 2.41GHz      | 1        | 5.56%   |
| Intel Celeron CPU G1850 @ 2.90GHz      | 1        | 5.56%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz      | 1        | 5.56%   |
| AMD Sempron 145 Processor              | 1        | 5.56%   |
| AMD Mobile Duron processor             | 1        | 5.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 3        | 16.67%  |
| Intel Core i3      | 3        | 16.67%  |
| Intel Celeron      | 3        | 16.67%  |
| Intel Core i9      | 2        | 11.11%  |
| Other              | 1        | 5.56%   |
| Intel Xeon         | 1        | 5.56%   |
| Intel Pentium Dual | 1        | 5.56%   |
| Intel Core i7      | 1        | 5.56%   |
| Intel Celeron M    | 1        | 5.56%   |
| Intel Atom         | 1        | 5.56%   |
| AMD Sempron        | 1        | 5.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 6        | 33.33%  |
| 2      | 6        | 33.33%  |
| 1      | 3        | 16.67%  |
| 10     | 2        | 11.11%  |
| 6      | 1        | 5.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 18       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 12       | 66.67%  |
| 2      | 6        | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 9        | 50%     |
| Unknown        | 7        | 38.89%  |
| 32-bit         | 2        | 11.11%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 7        | 36.84%  |
| 0x306c3    | 2        | 10.53%  |
| 0x306a9    | 2        | 10.53%  |
| 0xa0655    | 1        | 5.26%   |
| 0x906ea    | 1        | 5.26%   |
| 0x6fd      | 1        | 5.26%   |
| 0x6d8      | 1        | 5.26%   |
| 0x506c9    | 1        | 5.26%   |
| 0x406c4    | 1        | 5.26%   |
| 0x106e5    | 1        | 5.26%   |
| 0x010000b6 | 1        | 5.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 4        | 22.22%  |
| Silvermont  | 2        | 11.11%  |
| IvyBridge   | 2        | 11.11%  |
| CometLake   | 2        | 11.11%  |
| SandyBridge | 1        | 5.56%   |
| P6          | 1        | 5.56%   |
| Nehalem     | 1        | 5.56%   |
| KabyLake    | 1        | 5.56%   |
| K6          | 1        | 5.56%   |
| K10         | 1        | 5.56%   |
| Goldmont    | 1        | 5.56%   |
| Core        | 1        | 5.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 14       | 73.68%  |
| AMD                        | 2        | 10.53%  |
| VIA Technologies           | 1        | 5.26%   |
| Nvidia                     | 1        | 5.26%   |
| Matrox Electronics Systems | 1        | 5.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3        | 15.79%  |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 10.53%  |
| VIA Technologies KM400/KN400/P4M800 [S3 UniChrome]                                       | 1        | 5.26%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1        | 5.26%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1        | 5.26%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 5.26%   |
| Intel HD Graphics 500                                                                    | 1        | 5.26%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1        | 5.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 5.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1        | 5.26%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1        | 5.26%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1        | 5.26%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1        | 5.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 5.26%   |
| AMD ES1000                                                                               | 1        | 5.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1        | 5.26%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 13       | 72.22%  |
| 1 x AMD    | 2        | 11.11%  |
| 1 x VIA    | 1        | 5.56%   |
| 1 x Nvidia | 1        | 5.56%   |
| 1 x Matrox | 1        | 5.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 14       | 77.78%  |
| Unknown | 4        | 22.22%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 77.78%  |
| 0.01-0.5   | 2        | 11.11%  |
| 7.01-8.0   | 1        | 5.56%   |
| 1.01-2.0   | 1        | 5.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 3        | 23.08%  |
| AOC                 | 3        | 23.08%  |
| Dell                | 2        | 15.38%  |
| ViewSonic           | 1        | 7.69%   |
| Mi                  | 1        | 7.69%   |
| Goldstar            | 1        | 7.69%   |
| BenQ                | 1        | 7.69%   |
| Acer                | 1        | 7.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch      | 2        | 14.29%  |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch              | 1        | 7.14%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1        | 7.14%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch | 1        | 7.14%   |
| Mi Monitor XMI2701 2560x1440 597x335mm 27.0-inch                      | 1        | 7.14%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 1        | 7.14%   |
| Dell P2311H DEL4066 1920x1080 510x290mm 23.1-inch                     | 1        | 7.14%   |
| Dell E172FP DELA00A 1280x1024 338x270mm 17.0-inch                     | 1        | 7.14%   |
| BenQ BL2405 BNQ8016 1920x1080 531x298mm 24.0-inch                     | 1        | 7.14%   |
| AOC 718Swag-1 AOCC750 1440x900 367x230mm 17.1-inch                    | 1        | 7.14%   |
| AOC 2476WM AOC2476 1920x1080 521x293mm 23.5-inch                      | 1        | 7.14%   |
| AOC 2269WM AOC2269 1920x1080 480x270mm 21.7-inch                      | 1        | 7.14%   |
| Acer SA220Q ACR057D 1920x1080 476x268mm 21.5-inch                     | 1        | 7.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 5        | 38.46%  |
| 3440x1440          | 2        | 15.38%  |
| 1280x1024 (SXGA)   | 2        | 15.38%  |
| 3840x2160 (4K)     | 1        | 7.69%   |
| 2560x1440 (QHD)    | 1        | 7.69%   |
| 1680x1050 (WSXGA+) | 1        | 7.69%   |
| 1440x900 (WXGA+)   | 1        | 7.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 34     | 2        | 14.29%  |
| 27     | 2        | 14.29%  |
| 23     | 2        | 14.29%  |
| 21     | 2        | 14.29%  |
| 17     | 2        | 14.29%  |
| 54     | 1        | 7.14%   |
| 24     | 1        | 7.14%   |
| 20     | 1        | 7.14%   |
| 19     | 1        | 7.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 5        | 35.71%  |
| 401-500     | 3        | 21.43%  |
| 701-800     | 2        | 14.29%  |
| 351-400     | 2        | 14.29%  |
| 301-350     | 1        | 7.14%   |
| 1001-1500   | 1        | 7.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 6        | 54.55%  |
| 5/4   | 2        | 18.18%  |
| 21/9  | 2        | 18.18%  |
| 16/10 | 1        | 9.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 4        | 28.57%  |
| 151-200        | 3        | 21.43%  |
| 351-500        | 2        | 14.29%  |
| 301-350        | 2        | 14.29%  |
| More than 1000 | 1        | 7.14%   |
| 141-150        | 1        | 7.14%   |
| 131-140        | 1        | 7.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 6        | 50%     |
| 1-50    | 3        | 25%     |
| 101-120 | 2        | 16.67%  |
| 161-240 | 1        | 8.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10       | 55.56%  |
| 0     | 7        | 38.89%  |
| 4     | 1        | 5.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 9        | 39.13%  |
| Intel                 | 5        | 21.74%  |
| Qualcomm Atheros      | 2        | 8.7%    |
| Broadcom              | 2        | 8.7%    |
| Xiaomi                | 1        | 4.35%   |
| VIA Technologies      | 1        | 4.35%   |
| Qualcomm              | 1        | 4.35%   |
| Nvidia                | 1        | 4.35%   |
| D-Link System         | 1        | 4.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8        | 32%     |
| Intel Ethernet Controller I225-V                                  | 2        | 8%      |
| Intel Comet Lake PCH CNVi WiFi                                    | 2        | 8%      |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 4%      |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 4%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 4%      |
| Qualcomm Mobile Router                                            | 1        | 4%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1        | 4%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 4%      |
| Nvidia MCP61 Ethernet                                             | 1        | 4%      |
| Intel Ethernet Connection (7) I219-V                              | 1        | 4%      |
| Intel 82578DM Gigabit Network Connection                          | 1        | 4%      |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 4%      |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 4%      |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1        | 4%      |
| Broadcom BCM43227 802.11b/g/n                                     | 1        | 4%      |

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
| Realtek Semiconductor | 9        | 42.86%  |
| Intel                 | 5        | 23.81%  |
| Xiaomi                | 1        | 4.76%   |
| VIA Technologies      | 1        | 4.76%   |
| Qualcomm Atheros      | 1        | 4.76%   |
| Qualcomm              | 1        | 4.76%   |
| Nvidia                | 1        | 4.76%   |
| D-Link System         | 1        | 4.76%   |
| Broadcom              | 1        | 4.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8        | 38.1%   |
| Intel Ethernet Controller I225-V                                  | 2        | 9.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 4.76%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 4.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 4.76%   |
| Qualcomm Mobile Router                                            | 1        | 4.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 4.76%   |
| Nvidia MCP61 Ethernet                                             | 1        | 4.76%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 4.76%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 4.76%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 4.76%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 4.76%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1        | 4.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 17       | 80.95%  |
| WiFi     | 4        | 19.05%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 16       | 88.89%  |
| WiFi     | 2        | 11.11%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 11       | 61.11%  |
| 2     | 5        | 27.78%  |
| 4     | 1        | 5.56%   |
| 3     | 1        | 5.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 16       | 88.89%  |
| Yes  | 2        | 11.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 2        | 50%     |
| IMC Networks            | 1        | 25%     |
| Cambridge Silicon Radio | 1        | 25%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth Device                              | 2        | 50%     |
| IMC Networks Bluetooth Device                       | 1        | 25%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 25%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 13       | 76.47%  |
| VIA Technologies                     | 1        | 5.88%   |
| Thesycon Systemsoftware & Consulting | 1        | 5.88%   |
| Nvidia                               | 1        | 5.88%   |
| AMD                                  | 1        | 5.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 19.05%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 14.29%  |
| Intel Comet Lake PCH cAVS                                                  | 2        | 9.52%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1        | 4.76%   |
| Thesycon Systemsoftware & Consulting D10s                                  | 1        | 4.76%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 4.76%   |
| Intel USB PnP Sound Device                                                 | 1        | 4.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1        | 4.76%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 4.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1        | 4.76%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 4.76%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 4.76%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 1        | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 4.76%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 4.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 5        | 20%     |
| SK Hynix            | 5        | 20%     |
| Crucial             | 5        | 20%     |
| Kingston            | 2        | 8%      |
| Samsung Electronics | 1        | 4%      |
| Qimonda             | 1        | 4%      |
| Patriot             | 1        | 4%      |
| Micron Technology   | 1        | 4%      |
| Hewlett-Packard     | 1        | 4%      |
| Elpida              | 1        | 4%      |
| Corsair             | 1        | 4%      |
| Cors                | 1        | 4%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s  | 2        | 7.14%   |
| Unknown RAM Module 512MB DIMM                             | 1        | 3.57%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                 | 1        | 3.57%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s              | 1        | 3.57%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s              | 1        | 3.57%   |
| Unknown RAM Module 128MB DIMM                             | 1        | 3.57%   |
| Unknown RAM Module 1024MB DIMM SDRAM                      | 1        | 3.57%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s   | 1        | 3.57%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s      | 1        | 3.57%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s | 1        | 3.57%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1        | 3.57%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s      | 1        | 3.57%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s       | 1        | 3.57%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s       | 1        | 3.57%   |
| Qimonda RAM 64T128020HU3SB 1024MB DIMM DDR2 667MT/s       | 1        | 3.57%   |
| Patriot RAM PSD38G16002 8192MB DIMM DDR3 1600MT/s         | 1        | 3.57%   |
| Micron RAM 8KTF51264AZ-1G9P1 4GB DIMM DDR3 1866MT/s       | 1        | 3.57%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s       | 1        | 3.57%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s     | 1        | 3.57%   |
| Kingston RAM 9905595-005.A00LF 2GB DIMM DDR3 1600MT/s     | 1        | 3.57%   |
| HP RAM Module 4GB DIMM DDR3 1600MT/s                      | 1        | 3.57%   |
| Elpida RAM EBE10UE8ACWA-6E-E 1GB DIMM DDR2 667MT/s        | 1        | 3.57%   |
| Crucial RAM CT25664BA160B.C16F 2GB DIMM DDR3 1600MT/s     | 1        | 3.57%   |
| Crucial RAM CT102464BA160B.M16 8192MB DIMM 1600MT/s       | 1        | 3.57%   |
| Crucial RAM BLS8G4D240FSEK.8FBD 8192MB DIMM DDR4 2400MT/s | 1        | 3.57%   |
| Corsair RAM Module 8192MB DIMM DDR3 1333MT/s              | 1        | 3.57%   |
| Cors RAM CMX16GX3M2A1333C9 8192MB DIMM DDR3 1333MT/s      | 1        | 3.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 12       | 66.67%  |
| DDR4    | 3        | 16.67%  |
| SDRAM   | 1        | 5.56%   |
| DDR2    | 1        | 5.56%   |
| Unknown | 1        | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 16       | 88.89%  |
| SODIMM | 2        | 11.11%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 7        | 33.33%  |
| 4096  | 4        | 19.05%  |
| 2048  | 4        | 19.05%  |
| 16384 | 2        | 9.52%   |
| 1024  | 2        | 9.52%   |
| 512   | 1        | 4.76%   |
| 128   | 1        | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 10       | 47.62%  |
| 3600    | 2        | 9.52%   |
| 1333    | 2        | 9.52%   |
| Unknown | 2        | 9.52%   |
| 2400    | 1        | 4.76%   |
| 2133    | 1        | 4.76%   |
| 1866    | 1        | 4.76%   |
| 1800    | 1        | 4.76%   |
| 667     | 1        | 4.76%   |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Z-Star Microelectronics | 1        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Z-Star A4 TECH USB2.0 PC Camera J | 1        | 100%    |

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
| 0     | 13       | 72.22%  |
| 1     | 4        | 22.22%  |
| 5     | 1        | 5.56%   |

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

