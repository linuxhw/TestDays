Archcraft - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Archcraft.

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

Total: 24

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek  | TUF Gaming B550M-E          | [518e259c3c](https://linux-hardware.org/?probe=518e259c3c) | Dec 23, 2023 |
| HP       | 18E4                        | [db6b92644b](https://linux-hardware.org/?probe=db6b92644b) | Dec 12, 2023 |
| Lenovo   | 3706 SDK0J40700 WIN 3258... | [82b916eb4a](https://linux-hardware.org/?probe=82b916eb4a) | Nov 24, 2023 |
| Dell     | 0KP561                      | [90055b146d](https://linux-hardware.org/?probe=90055b146d) | Sep 06, 2023 |
| ASUSTek  | K30BF_M32BF_A_F_K31BF_6     | [08d5b71848](https://linux-hardware.org/?probe=08d5b71848) | Jul 22, 2023 |
| Gigabyte | B650 AORUS ELITE AX         | [e59862f167](https://linux-hardware.org/?probe=e59862f167) | Jul 05, 2023 |
| Lenovo   | Win8 Pro DPK TPG            | [0efc49ca3a](https://linux-hardware.org/?probe=0efc49ca3a) | Jun 28, 2023 |
| Lenovo   | Win8 Pro DPK TPG            | [72514911c8](https://linux-hardware.org/?probe=72514911c8) | Jun 28, 2023 |
| MSI      | A320M-A PRO                 | [09b5be9c77](https://linux-hardware.org/?probe=09b5be9c77) | Jun 24, 2023 |
| ASUSTek  | P8H61-M LX R2.0             | [558c031517](https://linux-hardware.org/?probe=558c031517) | Jun 16, 2023 |
| ASRock   | B550M Pro4                  | [8529d01687](https://linux-hardware.org/?probe=8529d01687) | May 27, 2023 |
| ASRock   | B550M Pro4                  | [8301ca5155](https://linux-hardware.org/?probe=8301ca5155) | May 27, 2023 |
| ASUSTek  | PRIME X470-PRO              | [f9df27503f](https://linux-hardware.org/?probe=f9df27503f) | Feb 03, 2023 |
| ASUSTek  | H110M-E/M.2                 | [82584d7e83](https://linux-hardware.org/?probe=82584d7e83) | Dec 20, 2022 |
| ASUSTek  | H110M-E/M.2                 | [fb73fb5efc](https://linux-hardware.org/?probe=fb73fb5efc) | Oct 18, 2022 |
| ASUSTek  | H110M-E/M.2                 | [77fd87ca91](https://linux-hardware.org/?probe=77fd87ca91) | Oct 18, 2022 |
| Gigabyte | B550I AORUS PRO AX          | [704da5b600](https://linux-hardware.org/?probe=704da5b600) | Oct 07, 2022 |
| Gigabyte | F2A68HM-DS2                 | [98e8df2d3d](https://linux-hardware.org/?probe=98e8df2d3d) | Sep 21, 2022 |
| Lenovo   | 3111 SDK0J40705 WIN 3425... | [543fe6b6a7](https://linux-hardware.org/?probe=543fe6b6a7) | Aug 07, 2022 |
| MSI      | MAG B550 TOMAHAWK           | [bede15789b](https://linux-hardware.org/?probe=bede15789b) | Jun 02, 2022 |
| ECS      | G31T-M                      | [3820396d91](https://linux-hardware.org/?probe=3820396d91) | Jan 29, 2022 |
| ASRock   | H97M Pro4                   | [232f2dad91](https://linux-hardware.org/?probe=232f2dad91) | Dec 15, 2021 |
| ASUSTek  | ROG DOMINUS EXTREME         | [0adc8fc04d](https://linux-hardware.org/?probe=0adc8fc04d) | Oct 12, 2021 |
| ASUSTek  | ROG DOMINUS EXTREME         | [b977489e9c](https://linux-hardware.org/?probe=b977489e9c) | Oct 12, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Archcraft Rolling | 16       | 84.21%  |
| Archcraft         | 3        | 15.79%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Archcraft | 19       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 6.3.9-arch1-1         | 2        | 10%     |
| 5.19.13-arch1-1       | 2        | 10%     |
| 6.6.7-arch1-1         | 1        | 5%      |
| 6.6.6-arch1-1         | 1        | 5%      |
| 6.6.1-arch1-1         | 1        | 5%      |
| 6.4.4-zen1-1-zen      | 1        | 5%      |
| 6.4.12-arch1-1        | 1        | 5%      |
| 6.4.1-arch2-1         | 1        | 5%      |
| 6.3.8-arch1-1         | 1        | 5%      |
| 6.3.4-arch1-1         | 1        | 5%      |
| 6.1.9-x64v1-xanmod1-1 | 1        | 5%      |
| 6.0.12-arch1-1        | 1        | 5%      |
| 5.19.9-arch1-1        | 1        | 5%      |
| 5.18.16-arch1-1       | 1        | 5%      |
| 5.18.0-arch1-1        | 1        | 5%      |
| 5.16.3-arch1-1        | 1        | 5%      |
| 5.15.7-zen1-1-zen     | 1        | 5%      |
| 5.14.10-arch1-1       | 1        | 5%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.3.9   | 2        | 10%     |
| 5.19.13 | 2        | 10%     |
| 6.6.7   | 1        | 5%      |
| 6.6.6   | 1        | 5%      |
| 6.6.1   | 1        | 5%      |
| 6.4.4   | 1        | 5%      |
| 6.4.12  | 1        | 5%      |
| 6.4.1   | 1        | 5%      |
| 6.3.8   | 1        | 5%      |
| 6.3.4   | 1        | 5%      |
| 6.1.9   | 1        | 5%      |
| 6.0.12  | 1        | 5%      |
| 5.19.9  | 1        | 5%      |
| 5.18.16 | 1        | 5%      |
| 5.18.0  | 1        | 5%      |
| 5.16.3  | 1        | 5%      |
| 5.15.7  | 1        | 5%      |
| 5.14.10 | 1        | 5%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.3     | 4        | 20%     |
| 6.6     | 3        | 15%     |
| 6.4     | 3        | 15%     |
| 5.19    | 3        | 15%     |
| 5.18    | 2        | 10%     |
| 6.1     | 1        | 5%      |
| 6.0     | 1        | 5%      |
| 5.16    | 1        | 5%      |
| 5.15    | 1        | 5%      |
| 5.14    | 1        | 5%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 19       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| openbox | 6        | 31.58%  |
| XFCE    | 5        | 26.32%  |
| bspwm   | 3        | 15.79%  |
| KDE5    | 2        | 10.53%  |
| qtile   | 1        | 5.26%   |
| awesome | 1        | 5.26%   |
| Unknown | 1        | 5.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 16       | 84.21%  |
| Wayland | 2        | 10.53%  |
| Unknown | 1        | 5.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 14       | 73.68%  |
| Unknown | 3        | 15.79%  |
| LightDM | 2        | 10.53%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 14       | 73.68%  |
| en_GB | 2        | 10.53%  |
| pt_BR | 1        | 5.26%   |
| es_MX | 1        | 5.26%   |
| en_IN | 1        | 5.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 12       | 63.16%  |
| BIOS | 7        | 36.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 13       | 68.42%  |
| Btrfs | 4        | 21.05%  |
| Xfs   | 2        | 10.53%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 15       | 78.95%  |
| Unknown | 3        | 15.79%  |
| MBR     | 1        | 5.26%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 78.95%  |
| Yes       | 4        | 21.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 57.89%  |
| Yes       | 8        | 42.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 6        | 31.58%  |
| Lenovo              | 3        | 15.79%  |
| Gigabyte Technology | 3        | 15.79%  |
| MSI                 | 2        | 10.53%  |
| ASRock              | 2        | 10.53%  |
| Hewlett-Packard     | 1        | 5.26%   |
| ECS                 | 1        | 5.26%   |
| Dell                | 1        | 5.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| MSI MS-7C91                             | 1        | 5.26%   |
| MSI MS-7C51                             | 1        | 5.26%   |
| Lenovo ThinkCentre M710q 10MR0047US     | 1        | 5.26%   |
| Lenovo ThinkCentre Edge72 3484HPU       | 1        | 5.26%   |
| Lenovo IdeaCentre 510A-15ARR 90J00061US | 1        | 5.26%   |
| HP EliteDesk 800 G1 TWR                 | 1        | 5.26%   |
| Gigabyte F2A68HM-DS2                    | 1        | 5.26%   |
| Gigabyte B650 AORUS ELITE AX            | 1        | 5.26%   |
| Gigabyte B550I AORUS PRO AX             | 1        | 5.26%   |
| ECS G31T-M                              | 1        | 5.26%   |
| Dell OptiPlex 330                       | 1        | 5.26%   |
| ASUS TUF Gaming B550M-E                 | 1        | 5.26%   |
| ASUS ROG DOMINUS EXTREME                | 1        | 5.26%   |
| ASUS PRIME X470-PRO                     | 1        | 5.26%   |
| ASUS P8H61-M LX R2.0                    | 1        | 5.26%   |
| ASUS K30BF_M32BF_A_F_K31BF_6            | 1        | 5.26%   |
| ASUS H110M-E/M.2                        | 1        | 5.26%   |
| ASRock H97M Pro4                        | 1        | 5.26%   |
| ASRock B550M Pro4                       | 1        | 5.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Lenovo ThinkCentre   | 2        | 10.53%  |
| MSI MS-7C91          | 1        | 5.26%   |
| MSI MS-7C51          | 1        | 5.26%   |
| Lenovo IdeaCentre    | 1        | 5.26%   |
| HP EliteDesk         | 1        | 5.26%   |
| Gigabyte F2A68HM-DS2 | 1        | 5.26%   |
| Gigabyte B650        | 1        | 5.26%   |
| Gigabyte B550I       | 1        | 5.26%   |
| ECS G31T-M           | 1        | 5.26%   |
| Dell OptiPlex        | 1        | 5.26%   |
| ASUS TUF             | 1        | 5.26%   |
| ASUS ROG             | 1        | 5.26%   |
| ASUS PRIME           | 1        | 5.26%   |
| ASUS P8H61-M         | 1        | 5.26%   |
| ASUS K30BF           | 1        | 5.26%   |
| ASUS H110M-E         | 1        | 5.26%   |
| ASRock H97M          | 1        | 5.26%   |
| ASRock B550M         | 1        | 5.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 4        | 21.05%  |
| 2019 | 2        | 10.53%  |
| 2014 | 2        | 10.53%  |
| 2012 | 2        | 10.53%  |
| 2007 | 2        | 10.53%  |
| 2022 | 1        | 5.26%   |
| 2021 | 1        | 5.26%   |
| 2018 | 1        | 5.26%   |
| 2017 | 1        | 5.26%   |
| 2016 | 1        | 5.26%   |
| 2015 | 1        | 5.26%   |
| 2013 | 1        | 5.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 19       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 19       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 19       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 5        | 26.32%  |
| 32.01-64.0  | 4        | 21.05%  |
| 16.01-24.0  | 3        | 15.79%  |
| 8.01-16.0   | 3        | 15.79%  |
| 3.01-4.0    | 2        | 10.53%  |
| 2.01-3.0    | 1        | 5.26%   |
| 64.01-256.0 | 1        | 5.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 3.01-4.0  | 5        | 25%     |
| 2.01-3.0  | 4        | 20%     |
| 1.01-2.0  | 4        | 20%     |
| 4.01-8.0  | 3        | 15%     |
| 8.01-16.0 | 3        | 15%     |
| 0.51-1.0  | 1        | 5%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 6        | 31.58%  |
| 2      | 5        | 26.32%  |
| 3      | 3        | 15.79%  |
| 5      | 2        | 10.53%  |
| 4      | 2        | 10.53%  |
| 7      | 1        | 5.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 84.21%  |
| Yes       | 3        | 15.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 19       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 52.63%  |
| Yes       | 9        | 47.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 63.16%  |
| Yes       | 7        | 36.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| USA      | 7        | 36.84%  |
| UK       | 2        | 10.53%  |
| Mexico   | 2        | 10.53%  |
| Brazil   | 2        | 10.53%  |
| Thailand | 1        | 5.26%   |
| Slovakia | 1        | 5.26%   |
| Poland   | 1        | 5.26%   |
| India    | 1        | 5.26%   |
| Hungary  | 1        | 5.26%   |
| Czechia  | 1        | 5.26%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Tábor                | 1        | 5.26%   |
| Sparta                | 1        | 5.26%   |
| Paulista              | 1        | 5.26%   |
| Osasco                | 1        | 5.26%   |
| Milton Keynes         | 1        | 5.26%   |
| Mesa                  | 1        | 5.26%   |
| Manchester            | 1        | 5.26%   |
| Guadalajara           | 1        | 5.26%   |
| Gdansk                | 1        | 5.26%   |
| Frisco                | 1        | 5.26%   |
| Dallas                | 1        | 5.26%   |
| Ciudad Nezahualcoyotl | 1        | 5.26%   |
| Čadca                | 1        | 5.26%   |
| Budapest              | 1        | 5.26%   |
| Brookville            | 1        | 5.26%   |
| Bengaluru             | 1        | 5.26%   |
| Bangkok               | 1        | 5.26%   |
| Atlanta               | 1        | 5.26%   |
| Abilene               | 1        | 5.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 6        | 8      | 14.63%  |
| Seagate                   | 6        | 10     | 14.63%  |
| Sandisk                   | 4        | 5      | 9.76%   |
| Samsung Electronics       | 4        | 4      | 9.76%   |
| Hitachi                   | 3        | 3      | 7.32%   |
| Toshiba                   | 2        | 2      | 4.88%   |
| Phison Electronics        | 2        | 2      | 4.88%   |
| Kingston                  | 2        | 2      | 4.88%   |
| Intel                     | 2        | 5      | 4.88%   |
| A-DATA Technology         | 2        | 3      | 4.88%   |
| SUNEAST                   | 1        | 1      | 2.44%   |
| ROG                       | 1        | 1      | 2.44%   |
| Patriot                   | 1        | 1      | 2.44%   |
| Micron/Crucial Technology | 1        | 1      | 2.44%   |
| Crucial                   | 1        | 1      | 2.44%   |
| China                     | 1        | 2      | 2.44%   |
| Apacer                    | 1        | 1      | 2.44%   |
| Unknown                   | 1        | 1      | 2.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 3        | 6.52%   |
| WDC WD5000AAKX-75U6AA0 500GB                        | 1        | 2.17%   |
| WDC WD5000AAKX-60U6AA0 500GB                        | 1        | 2.17%   |
| WDC WD5000AAKX-08U6AA0 500GB                        | 1        | 2.17%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1        | 2.17%   |
| WDC WD20 EARX-00PASB0 2TB                           | 1        | 2.17%   |
| WDC WD10EZEX-22RKKA0 1TB                            | 1        | 2.17%   |
| WDC WD10EZEX-21M2NA0 1TB                            | 1        | 2.17%   |
| WDC WD10EARS-00MVWB0 1TB                            | 1        | 2.17%   |
| Toshiba DT01ACA200 2TB                              | 1        | 2.17%   |
| Toshiba DT01ACA100 1TB                              | 1        | 2.17%   |
| SUNEAST SSD SE800 128GB                             | 1        | 2.17%   |
| Seagate ST6000DM003-2CY186 6TB                      | 1        | 2.17%   |
| Seagate ST3500410AS 500GB                           | 1        | 2.17%   |
| Seagate ST320LM001 HN-M320MBB 320GB                 | 1        | 2.17%   |
| Seagate ST3160815AS 160GB                           | 1        | 2.17%   |
| Seagate ST31500341AS 1TB                            | 1        | 2.17%   |
| Seagate ST2000DM 008-2FR102 2TB                     | 1        | 2.17%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1        | 2.17%   |
| Seagate Expansion Desk 8TB                          | 1        | 2.17%   |
| Sandisk WD_BLACK SN770 1TB                          | 1        | 2.17%   |
| Sandisk WD Green SN350 500GB 2G0C                   | 1        | 2.17%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 1        | 2.17%   |
| SanDisk SSD PLUS 240 GB                             | 1        | 2.17%   |
| SanDisk SDSSDA240G 240GB                            | 1        | 2.17%   |
| Samsung SSD 970 EVO Plus 1TB                        | 1        | 2.17%   |
| ROG ESD-S1C 1024GB                                  | 1        | 2.17%   |
| Phison E16 PCIe4 NVMe Controller 2TB                | 1        | 2.17%   |
| Phison E12 NVMe Controller 1TB                      | 1        | 2.17%   |
| Patriot Burst 120GB SSD                             | 1        | 2.17%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                 | 1        | 2.17%   |
| Kingston SFYRS500G 500GB                            | 1        | 2.17%   |
| Kingston SA400M8240G 240GB SSD                      | 1        | 2.17%   |
| Intel SSDSC2KW256G8 256GB                           | 1        | 2.17%   |
| Intel SSDPE21D480GA 480GB                           | 1        | 2.17%   |
| Hitachi HTS547550A9E384 500GB                       | 1        | 2.17%   |
| Hitachi HTS545050A7E380 500GB                       | 1        | 2.17%   |
| Hitachi HDS721010CLA332 1TB                         | 1        | 2.17%   |
| Crucial M4-CT064M4SSD2 64GB                         | 1        | 2.17%   |
| China SATA SSD 512GB                                | 1        | 2.17%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 6        | 8      | 35.29%  |
| Seagate | 6        | 10     | 35.29%  |
| Hitachi | 3        | 3      | 17.65%  |
| Toshiba | 2        | 2      | 11.76%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| SanDisk           | 2        | 2      | 16.67%  |
| A-DATA Technology | 2        | 3      | 16.67%  |
| SUNEAST           | 1        | 1      | 8.33%   |
| Patriot           | 1        | 1      | 8.33%   |
| Kingston          | 1        | 1      | 8.33%   |
| Intel             | 1        | 1      | 8.33%   |
| Crucial           | 1        | 1      | 8.33%   |
| China             | 1        | 2      | 8.33%   |
| Apacer            | 1        | 1      | 8.33%   |
| Unknown           | 1        | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 10       | 23     | 35.71%  |
| NVMe    | 9        | 15     | 32.14%  |
| SSD     | 8        | 14     | 28.57%  |
| Unknown | 1        | 1      | 3.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 14       | 33     | 53.85%  |
| NVMe | 9        | 15     | 34.62%  |
| SAS  | 3        | 5      | 11.54%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 12       | 21     | 54.55%  |
| 0.51-1.0   | 6        | 11     | 27.27%  |
| 1.01-2.0   | 2        | 3      | 9.09%   |
| 4.01-10.0  | 2        | 2      | 9.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 5        | 26.32%  |
| 251-500        | 4        | 21.05%  |
| 1001-2000      | 4        | 21.05%  |
| 501-1000       | 2        | 10.53%  |
| More than 3000 | 1        | 5.26%   |
| 2001-3000      | 1        | 5.26%   |
| 51-100         | 1        | 5.26%   |
| Unknown        | 1        | 5.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 4        | 21.05%  |
| 1-20           | 4        | 21.05%  |
| 21-50          | 3        | 15.79%  |
| 251-500        | 2        | 10.53%  |
| 51-100         | 2        | 10.53%  |
| More than 3000 | 1        | 5.26%   |
| 1001-2000      | 1        | 5.26%   |
| 501-1000       | 1        | 5.26%   |
| Unknown        | 1        | 5.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Desktops | Drives | Percent |
|-------------------------------|----------|--------|---------|
| WDC WD5000AAKX-75U6AA0 500GB  | 1        | 1      | 25%     |
| WDC WD5000AAKX-60U6AA0 500GB  | 1        | 1      | 25%     |
| WDC WD10EARS-00MVWB0 1TB      | 1        | 1      | 25%     |
| Hitachi HTS547550A9E384 500GB | 1        | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 75%     |
| Hitachi | 1        | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 75%     |
| Hitachi | 1        | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 4      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST3500410AS 500GB | 1        | 2      | 50%     |
| Seagate ST31500341AS 1TB  | 1        | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 4      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 15       | 35     | 62.5%   |
| Detected | 5        | 10     | 20.83%  |
| Malfunc  | 3        | 4      | 12.5%   |
| Failed   | 1        | 4      | 4.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 10       | 33.33%  |
| Intel                       | 9        | 30%     |
| Samsung Electronics         | 4        | 13.33%  |
| SanDisk                     | 2        | 6.67%   |
| Phison Electronics          | 2        | 6.67%   |
| Micron/Crucial Technology   | 1        | 3.33%   |
| Kingston Technology Company | 1        | 3.33%   |
| ASMedia Technology          | 1        | 3.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 5        | 13.51%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4        | 10.81%  |
| AMD 500 Series Chipset SATA Controller                                         | 4        | 10.81%  |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2        | 5.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 5.41%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 1        | 2.7%    |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1        | 2.7%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 1        | 2.7%    |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 2.7%    |
| Phison E12 NVMe Controller                                                     | 1        | 2.7%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1        | 2.7%    |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                             | 1        | 2.7%    |
| Intel Volume Management Device NVMe RAID Controller                            | 1        | 2.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 2.7%    |
| Intel Optane SSD 900P Series                                                   | 1        | 2.7%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 2.7%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1        | 2.7%    |
| Intel C620 Series Chipset Family IDE Redirection                               | 1        | 2.7%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1        | 2.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 2.7%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1        | 2.7%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 2.7%    |
| AMD FCH SATA Controller [IDE mode]                                             | 1        | 2.7%    |
| AMD FCH SATA Controller D                                                      | 1        | 2.7%    |
| AMD 400 Series Chipset SATA Controller                                         | 1        | 2.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 18       | 58.06%  |
| NVMe | 9        | 29.03%  |
| IDE  | 3        | 9.68%   |
| RAID | 1        | 3.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 10       | 52.63%  |
| Intel  | 9        | 47.37%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor              | 2        | 10.53%  |
| AMD A10-7800 Radeon R7, 12 Compute Cores 4C+8G | 2        | 10.53%  |
| Intel Xeon W-3175X CPU @ 3.10GHz               | 1        | 5.26%   |
| Intel Core i7-2600K CPU @ 3.40GHz              | 1        | 5.26%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1        | 5.26%   |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1        | 5.26%   |
| Intel Core i5-4690K CPU @ 3.50GHz              | 1        | 5.26%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 5.26%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 1        | 5.26%   |
| Intel Core 2 Duo CPU E4600 @ 2.40GHz           | 1        | 5.26%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz           | 1        | 5.26%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 5.26%   |
| AMD Ryzen 7 7700X 8-Core Processor             | 1        | 5.26%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1        | 5.26%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1        | 5.26%   |
| AMD Ryzen 5 4600G with Radeon Graphics         | 1        | 5.26%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics    | 1        | 5.26%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| AMD Ryzen 5      | 5        | 26.32%  |
| Intel Core i5    | 4        | 21.05%  |
| Intel Core 2 Duo | 2        | 10.53%  |
| AMD Ryzen 7      | 2        | 10.53%  |
| AMD A10          | 2        | 10.53%  |
| Intel Xeon       | 1        | 5.26%   |
| Intel Core i7    | 1        | 5.26%   |
| Intel Core i3    | 1        | 5.26%   |
| AMD Ryzen 9      | 1        | 5.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 6        | 31.58%  |
| 2      | 5        | 26.32%  |
| 6      | 4        | 21.05%  |
| 8      | 2        | 10.53%  |
| 28     | 1        | 5.26%   |
| 12     | 1        | 5.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 19       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 13       | 68.42%  |
| 1      | 6        | 31.58%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 19       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 7        | 36.84%  |
| 0x906e9    | 1        | 5.26%   |
| 0x6fd      | 1        | 5.26%   |
| 0x506e3    | 1        | 5.26%   |
| 0x50654    | 1        | 5.26%   |
| 0x306c3    | 1        | 5.26%   |
| 0x0a601203 | 1        | 5.26%   |
| 0x0a201016 | 1        | 5.26%   |
| 0x0a201009 | 1        | 5.26%   |
| 0x08701030 | 1        | 5.26%   |
| 0x08701021 | 1        | 5.26%   |
| 0x08108102 | 1        | 5.26%   |
| 0x06003106 | 1        | 5.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 2       | 3        | 15.79%  |
| Zen+        | 2        | 10.53%  |
| Zen 3       | 2        | 10.53%  |
| Steamroller | 2        | 10.53%  |
| Skylake     | 2        | 10.53%  |
| Haswell     | 2        | 10.53%  |
| Core        | 2        | 10.53%  |
| SandyBridge | 1        | 5.26%   |
| KabyLake    | 1        | 5.26%   |
| IvyBridge   | 1        | 5.26%   |
| Unknown     | 1        | 5.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 10       | 45.45%  |
| Nvidia | 7        | 31.82%  |
| Intel  | 5        | 22.73%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 12%     |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 8%      |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 8%      |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 4%      |
| Nvidia TU102 [TITAN RTX]                                                    | 1        | 4%      |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 4%      |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 4%      |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 4%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 4%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 4%      |
| Intel HD Graphics 630                                                       | 1        | 4%      |
| Intel HD Graphics 530                                                       | 1        | 4%      |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 4%      |
| AMD RV710 [Radeon HD 4350/4550]                                             | 1        | 4%      |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 1        | 4%      |
| AMD Raphael                                                                 | 1        | 4%      |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                  | 1        | 4%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 4%      |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 1        | 4%      |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                    | 1        | 4%      |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1        | 4%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 6        | 31.58%  |
| 1 x Nvidia     | 5        | 26.32%  |
| 2 x AMD        | 3        | 15.79%  |
| 1 x Intel      | 2        | 10.53%  |
| 2 x Intel      | 1        | 5.26%   |
| Intel + Nvidia | 1        | 5.26%   |
| AMD + Nvidia   | 1        | 5.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 14       | 70%     |
| Proprietary | 6        | 30%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 6        | 30%     |
| 7.01-8.0   | 4        | 20%     |
| 1.01-2.0   | 3        | 15%     |
| 16.01-24.0 | 2        | 10%     |
| 0.51-1.0   | 2        | 10%     |
| 5.01-6.0   | 1        | 5%      |
| 3.01-4.0   | 1        | 5%      |
| 8.01-16.0  | 1        | 5%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 4        | 17.39%  |
| Samsung Electronics  | 3        | 13.04%  |
| Goldstar             | 3        | 13.04%  |
| Ancor Communications | 3        | 13.04%  |
| Acer                 | 2        | 8.7%    |
| Toshiba              | 1        | 4.35%   |
| Roku                 | 1        | 4.35%   |
| Lenovo               | 1        | 4.35%   |
| Hewlett-Packard      | 1        | 4.35%   |
| BenQ                 | 1        | 4.35%   |
| ASUSTek Computer     | 1        | 4.35%   |
| AGO                  | 1        | 4.35%   |
| Unknown              | 1        | 4.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Toshiba TV TSB0206 1920x1080 890x500mm 40.2-inch                      | 1        | 3.85%   |
| Samsung Electronics LS24AG32x SAM71DA 1920x1080 527x296mm 23.8-inch   | 1        | 3.85%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 1        | 3.85%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 3.85%   |
| Roku TV RKU8518 1920x1080 698x392mm 31.5-inch                         | 1        | 3.85%   |
| Lenovo P24h-10 LEN61AE 2560x1440 527x296mm 23.8-inch                  | 1        | 3.85%   |
| Hewlett-Packard V320 HPN3363 1920x1080 698x393mm 31.5-inch            | 1        | 3.85%   |
| Goldstar L1742 GSM449C 1280x1024 338x270mm 17.0-inch                  | 1        | 3.85%   |
| Goldstar HDR WFHD GSM5BB9 2560x1080 798x334mm 34.1-inch               | 1        | 3.85%   |
| Goldstar FULL HD GSM5BFB 1920x1080 480x270mm 21.7-inch                | 1        | 3.85%   |
| Dell SE2417HG DELD08E 1920x1080 521x293mm 23.5-inch                   | 1        | 3.85%   |
| Dell SE2417HG DELD08D 1920x1080 521x293mm 23.5-inch                   | 1        | 3.85%   |
| Dell S2421NX DEL41FB 1920x1080 527x296mm 23.8-inch                    | 1        | 3.85%   |
| Dell S2240T DELA094 1920x1080 477x268mm 21.5-inch                     | 1        | 3.85%   |
| Dell E198WFP DELF005 1440x900 408x255mm 18.9-inch                     | 1        | 3.85%   |
| BenQ BL3200 BNQ8017 2560x1440 708x398mm 32.0-inch                     | 1        | 3.85%   |
| ASUSTek Computer ROG PG65UQ AUS65A1 3840x2160 1430x800mm 64.5-inch    | 1        | 3.85%   |
| Ancor Communications ROG PG348Q ACI3433 3440x1440 798x335mm 34.1-inch | 1        | 3.85%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 480x270mm 21.7-inch | 1        | 3.85%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch | 1        | 3.85%   |
| AGO LCD Monitor AGO0001 1920x1080 300x230mm 14.9-inch                 | 1        | 3.85%   |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch                 | 1        | 3.85%   |
| Acer XF251Q ACR0624 1920x1080 544x303mm 24.5-inch                     | 1        | 3.85%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                     | 1        | 3.85%   |
| Acer G235H ACR0120 1920x1080 521x293mm 23.5-inch                      | 1        | 3.85%   |
| Unknown                                                               | 1        | 3.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 11       | 50%     |
| 2560x1440 (QHD)  | 3        | 13.64%  |
| 3840x2160 (4K)   | 1        | 4.55%   |
| 3840x1080        | 1        | 4.55%   |
| 3440x1440        | 1        | 4.55%   |
| 3200x1080        | 1        | 4.55%   |
| 2560x1080        | 1        | 4.55%   |
| 1440x900 (WXGA+) | 1        | 4.55%   |
| 1280x1024 (SXGA) | 1        | 4.55%   |
| Unknown          | 1        | 4.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 5        | 20%     |
| 23      | 3        | 12%     |
| 21      | 3        | 12%     |
| 34      | 2        | 8%      |
| 31      | 2        | 8%      |
| 74      | 1        | 4%      |
| 64      | 1        | 4%      |
| 48      | 1        | 4%      |
| 32      | 1        | 4%      |
| 27      | 1        | 4%      |
| 19      | 1        | 4%      |
| 17      | 1        | 4%      |
| 14      | 1        | 4%      |
| 12      | 1        | 4%      |
| Unknown | 1        | 4%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 8        | 34.78%  |
| 401-500     | 4        | 17.39%  |
| 701-800     | 3        | 13.04%  |
| 601-700     | 2        | 8.7%    |
| 1001-1500   | 2        | 8.7%    |
| 301-350     | 1        | 4.35%   |
| 201-300     | 1        | 4.35%   |
| 1501-2000   | 1        | 4.35%   |
| Unknown     | 1        | 4.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 13       | 61.9%   |
| 21/9    | 2        | 9.52%   |
| 16/10   | 2        | 9.52%   |
| 5/4     | 1        | 4.76%   |
| 4/3     | 1        | 4.76%   |
| 32/9    | 1        | 4.76%   |
| Unknown | 1        | 4.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 8        | 33.33%  |
| 351-500        | 5        | 20.83%  |
| More than 1000 | 2        | 8.33%   |
| 151-200        | 2        | 8.33%   |
| 71-80          | 1        | 4.17%   |
| 301-350        | 1        | 4.17%   |
| 251-300        | 1        | 4.17%   |
| 141-150        | 1        | 4.17%   |
| 101-110        | 1        | 4.17%   |
| 501-1000       | 1        | 4.17%   |
| Unknown        | 1        | 4.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 14       | 60.87%  |
| 101-120 | 4        | 17.39%  |
| 121-160 | 2        | 8.7%    |
| 1-50    | 1        | 4.35%   |
| 161-240 | 1        | 4.35%   |
| Unknown | 1        | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 12       | 63.16%  |
| 2     | 6        | 31.58%  |
| 3     | 1        | 5.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 14       | 58.33%  |
| Intel                 | 6        | 25%     |
| Ralink Technology     | 1        | 4.17%   |
| MediaTek              | 1        | 4.17%   |
| Broadcom Limited      | 1        | 4.17%   |
| Aquantia              | 1        | 4.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10       | 30.3%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 9.09%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2        | 6.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 3.03%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 3.03%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 3.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 3.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 3.03%   |
| Realtek 802.11ac NIC                                              | 1        | 3.03%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 3.03%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1        | 3.03%   |
| Intel Wireless-AC 9260                                            | 1        | 3.03%   |
| Intel Wireless 8265 / 8275                                        | 1        | 3.03%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 3.03%   |
| Intel I211 Gigabit Network Connection                             | 1        | 3.03%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 3.03%   |
| Intel Ethernet Connection (3) I219-LM                             | 1        | 3.03%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 3.03%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 3.03%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 1        | 3.03%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 3.03%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 4        | 44.44%  |
| Intel                 | 3        | 33.33%  |
| Ralink Technology     | 1        | 11.11%  |
| MediaTek              | 1        | 11.11%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 2        | 20%     |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1        | 10%     |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 1        | 10%     |
| Realtek 802.11ac NIC                                          | 1        | 10%     |
| Ralink MT7601U Wireless Adapter                               | 1        | 10%     |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 1        | 10%     |
| Intel Wireless-AC 9260                                        | 1        | 10%     |
| Intel Wireless 8265 / 8275                                    | 1        | 10%     |
| Intel Wi-Fi 6 AX200                                           | 1        | 10%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 13       | 65%     |
| Intel                 | 5        | 25%     |
| Broadcom Limited      | 1        | 5%      |
| Aquantia              | 1        | 5%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10       | 43.48%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 13.04%  |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 4.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 4.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 4.35%   |
| Intel I211 Gigabit Network Connection                             | 1        | 4.35%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 4.35%   |
| Intel Ethernet Connection (3) I219-LM                             | 1        | 4.35%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 4.35%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 4.35%   |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 1        | 4.35%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 4.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 19       | 67.86%  |
| WiFi     | 9        | 32.14%  |

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
| 1     | 10       | 52.63%  |
| 2     | 8        | 42.11%  |
| 3     | 1        | 5.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 12       | 63.16%  |
| Yes  | 7        | 36.84%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 3        | 42.86%  |
| Realtek Semiconductor   | 1        | 14.29%  |
| MediaTek                | 1        | 14.29%  |
| IMC Networks            | 1        | 14.29%  |
| Cambridge Silicon Radio | 1        | 14.29%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Realtek Bluetooth Radio                             | 1        | 14.29%  |
| MediaTek Wireless_Device                            | 1        | 14.29%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 14.29%  |
| Intel Bluetooth wireless interface                  | 1        | 14.29%  |
| Intel AX200 Bluetooth                               | 1        | 14.29%  |
| IMC Networks Bluetooth Radio                        | 1        | 14.29%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 14.29%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| AMD                 | 13       | 32.5%   |
| Intel               | 9        | 22.5%   |
| Nvidia              | 7        | 17.5%   |
| Logitech            | 3        | 7.5%    |
| C-Media Electronics | 2        | 5%      |
| Texas Instruments   | 1        | 2.5%    |
| Oculus VR           | 1        | 2.5%    |
| Kingston Technology | 1        | 2.5%    |
| JMTek               | 1        | 2.5%    |
| DCMT Technology     | 1        | 2.5%    |
| Blue Microphones    | 1        | 2.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 4        | 7.84%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3        | 5.88%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 5.88%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 3.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 3.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 3.92%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 3.92%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 2        | 3.92%   |
| AMD FCH Azalia Controller                                                  | 2        | 3.92%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 1.96%   |
| Oculus VR Rift CV1 Audio                                                   | 1        | 1.96%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 1.96%   |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 1.96%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 1.96%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1.96%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 1.96%   |
| Logitech Logitech USB Microphone                                           | 1        | 1.96%   |
| Logitech H390 headset with microphone                                      | 1        | 1.96%   |
| Logitech G432 Gaming Headset                                               | 1        | 1.96%   |
| Kingston Technology HyperX QuadCast                                        | 1        | 1.96%   |
| JMTek USB PnP Audio Device                                                 | 1        | 1.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 1.96%   |
| Intel Lewisburg MROM 0                                                     | 1        | 1.96%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 1.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1        | 1.96%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 1.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 1.96%   |
| DCMT Technology USB Condenser Microphone                                   | 1        | 1.96%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1        | 1.96%   |
| C-Media Electronics Antlion USB adapter                                    | 1        | 1.96%   |
| Blue Microphones Yeti Nano                                                 | 1        | 1.96%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1        | 1.96%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 1.96%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1        | 1.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 1.96%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 1        | 1.96%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1        | 1.96%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 1.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 4        | 22.22%  |
| Unknown             | 2        | 11.11%  |
| Crucial             | 2        | 11.11%  |
| Corsair             | 2        | 11.11%  |
| A-DATA Technology   | 2        | 11.11%  |
| Team                | 1        | 5.56%   |
| SK hynix            | 1        | 5.56%   |
| Samsung Electronics | 1        | 5.56%   |
| Ramaxel Technology  | 1        | 5.56%   |
| Micron Technology   | 1        | 5.56%   |
| G.Skill             | 1        | 5.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 5%      |
| Unknown RAM Module 2GB DIMM SDRAM                       | 1        | 5%      |
| Unknown RAM Module 1GB DIMM SDRAM                       | 1        | 5%      |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3800MT/s     | 1        | 5%      |
| SK hynix RAM HYMP512U64CP8-S6 1GB DIMM DDR2 800MT/s     | 1        | 5%      |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s   | 1        | 5%      |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s   | 1        | 5%      |
| Ramaxel RAM RMUA5120ME86H9F-2666 4GB DIMM DDR4 2667MT/s | 1        | 5%      |
| Micron RAM F6451U64F9333G 4096MB DIMM DDR3 1333MT/s     | 1        | 5%      |
| Kingston RAM KF552C40-8 8GB DIMM DDR5 4800MT/s          | 1        | 5%      |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3800MT/s   | 1        | 5%      |
| Kingston RAM KF3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s  | 1        | 5%      |
| Kingston RAM 9905402-532.A00LF 4GB DIMM DDR3 1600MT/s   | 1        | 5%      |
| G.Skill RAM F4-3000C16-8GTZR 8GB DIMM DDR4 3200MT/s     | 1        | 5%      |
| Crucial RAM CT51264BA1339.M16F 4GB DIMM DDR3 1333MT/s   | 1        | 5%      |
| Crucial RAM BL8G36C16U4B.M8FE1 8GB DIMM DDR4 3733MT/s   | 1        | 5%      |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s   | 1        | 5%      |
| Corsair RAM CMT16GX4M2K4266C19 8GB DIMM DDR4 2133MT/s   | 1        | 5%      |
| A-DATA RAM Module 8GB DIMM DDR4 2133MT/s                | 1        | 5%      |
| A-DATA RAM DDR4 3600 2OZ 8GB DIMM DDR4 2667MT/s         | 1        | 5%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 9        | 56.25%  |
| DDR3  | 4        | 25%     |
| SDRAM | 1        | 6.25%   |
| DDR5  | 1        | 6.25%   |
| DDR2  | 1        | 6.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 15       | 93.75%  |
| SODIMM | 1        | 6.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 9        | 50%     |
| 4096  | 3        | 16.67%  |
| 2048  | 2        | 11.11%  |
| 1024  | 2        | 11.11%  |
| 32768 | 1        | 5.56%   |
| 16384 | 1        | 5.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 2667    | 3        | 16.67%  |
| 1600    | 3        | 16.67%  |
| 3800    | 2        | 11.11%  |
| 2133    | 2        | 11.11%  |
| 49926   | 1        | 5.56%   |
| 4800    | 1        | 5.56%   |
| 3733    | 1        | 5.56%   |
| 3600    | 1        | 5.56%   |
| 3200    | 1        | 5.56%   |
| 1333    | 1        | 5.56%   |
| 800     | 1        | 5.56%   |
| Unknown | 1        | 5.56%   |

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
| HP DeskJet 4720 series | 1        | 100%    |

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


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Samsung Electronics    | 1        | 33.33%  |
| Logitech               | 1        | 33.33%  |
| Generalplus Technology | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode) | 1        | 33.33%  |
| Logitech HD Pro Webcam C920             | 1        | 33.33%  |
| Generalplus WEB CAM                     | 1        | 33.33%  |

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
| 0     | 17       | 89.47%  |
| 2     | 1        | 5.26%   |
| 1     | 1        | 5.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Unassigned class | 1        | 50%     |
| Graphics card    | 1        | 50%     |

