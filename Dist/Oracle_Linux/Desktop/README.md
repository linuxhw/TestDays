Oracle Linux - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Oracle Linux.

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

Total: 22

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek  | SABERTOOTH 990FX R3.0       | [b63af8760f](https://linux-hardware.org/?probe=b63af8760f) | Oct 03, 2023 |
| ASUSTek  | SABERTOOTH 990FX R3.0       | [5ac9728fe0](https://linux-hardware.org/?probe=5ac9728fe0) | Oct 01, 2023 |
| Cisco    | WAVE-694-K9 A0              | [26b9c3adb7](https://linux-hardware.org/?probe=26b9c3adb7) | Jun 27, 2023 |
| ASRock   | Z68 Extreme3 Gen3           | [7849965aa1](https://linux-hardware.org/?probe=7849965aa1) | Jun 11, 2023 |
| HP       | 1589                        | [c905464231](https://linux-hardware.org/?probe=c905464231) | May 11, 2023 |
| Gigabyte | H81M-S2PV                   | [ac856abadc](https://linux-hardware.org/?probe=ac856abadc) | Mar 21, 2023 |
| ASUSTek  | PRIME B560M-A AC            | [d4cc718e46](https://linux-hardware.org/?probe=d4cc718e46) | Nov 29, 2022 |
| Dell     | 0DC48C A02                  | [9292e820c5](https://linux-hardware.org/?probe=9292e820c5) | Sep 27, 2022 |
| ASUSTek  | H81M-A                      | [a37e952875](https://linux-hardware.org/?probe=a37e952875) | Sep 04, 2022 |
| Dell     | 073Y7Y A00                  | [3bed97b23e](https://linux-hardware.org/?probe=3bed97b23e) | Jul 21, 2022 |
| MSI      | Z77A-G43                    | [909e3e3c2e](https://linux-hardware.org/?probe=909e3e3c2e) | Jun 29, 2022 |
| ASUSTek  | P8H67                       | [b194dad4cf](https://linux-hardware.org/?probe=b194dad4cf) | Jun 25, 2022 |
| Dell     | 0C522T A03                  | [3dc84dc8ff](https://linux-hardware.org/?probe=3dc84dc8ff) | Mar 24, 2022 |
| Gigabyte | Z490 AORUS ELITE AC         | [978ae6f2cb](https://linux-hardware.org/?probe=978ae6f2cb) | May 02, 2021 |
| Gigabyte | X99-Designare EX-CF         | [5195396549](https://linux-hardware.org/?probe=5195396549) | Mar 06, 2021 |
| ASUSTek  | G11CD                       | [13961e12a8](https://linux-hardware.org/?probe=13961e12a8) | Feb 01, 2021 |
| HP       | 158B                        | [5e6b9531d7](https://linux-hardware.org/?probe=5e6b9531d7) | Feb 01, 2021 |
| Dell     | PowerEdge FC630             | [bcd33a41f0](https://linux-hardware.org/?probe=bcd33a41f0) | Jan 25, 2021 |
| Gigabyte | X470 AORUS ULTRA GAMING-... | [71628a95b6](https://linux-hardware.org/?probe=71628a95b6) | Jan 13, 2021 |
| Foxconn  | 2ADA                        | [809e03aea5](https://linux-hardware.org/?probe=809e03aea5) | Dec 24, 2020 |
| ASUSTek  | G11CD                       | [d9d0f8fdf2](https://linux-hardware.org/?probe=d9d0f8fdf2) | Dec 20, 2020 |
| Dell     | 0C96W1 A01                  | [b5c14107bb](https://linux-hardware.org/?probe=b5c14107bb) | Feb 12, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Oracle Linux 8.3 | 6        | 30%     |
| Oracle Linux 8.6 | 4        | 20%     |
| Oracle Linux 9.2 | 3        | 15%     |
| Oracle Linux 8.7 | 2        | 10%     |
| Oracle Linux 9.0 | 1        | 5%      |
| Oracle Linux 8.5 | 1        | 5%      |
| Oracle Linux 8.4 | 1        | 5%      |
| Oracle Linux 7.7 | 1        | 5%      |
| Oracle Linux 7.4 | 1        | 5%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Oracle Linux | 20       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Desktops | Percent |
|------------------------------------|----------|---------|
| 5.4.17-2036.102.0.2.el8uek.x86_64  | 2        | 9.52%   |
| 5.4.17-2036.101.2.el8uek.x86_64    | 2        | 9.52%   |
| 5.4.17-2136.313.6.el8uek.x86_64    | 1        | 4.76%   |
| 5.4.17-2136.310.7.1.el8uek.x86_64  | 1        | 4.76%   |
| 5.4.17-2136.308.9.el8uek.x86_64    | 1        | 4.76%   |
| 5.4.17-2136.307.3.1.el8uek.x86_64  | 1        | 4.76%   |
| 5.4.17-2136.300.7.el8uek.x86_64    | 1        | 4.76%   |
| 5.4.17-2102.202.5.el8uek.x86_64    | 1        | 4.76%   |
| 5.4.17-2102.200.13.el8uek.x86_64   | 1        | 4.76%   |
| 5.4.17-2036.100.6.1.el8uek.x86_64  | 1        | 4.76%   |
| 5.4.11-1.el7.elrepo.x86_64         | 1        | 4.76%   |
| 5.15.0-2.52.3.el9uek.x86_64        | 1        | 4.76%   |
| 5.15.0-105.125.6.2.2.el9uek.x86_64 | 1        | 4.76%   |
| 5.15.0-102.110.5.1.el9uek.x86_64   | 1        | 4.76%   |
| 5.15.0-101.103.2.1.el9uek.x86_64   | 1        | 4.76%   |
| 5.15.0-100.96.32.el8uek.x86_64     | 1        | 4.76%   |
| 4.18.0-372.16.1.0.2.el8_6.x86_64   | 1        | 4.76%   |
| 4.18.0-240.15.1.el8_3.x86_64       | 1        | 4.76%   |
| 3.10.0-693.11.6.el7.x86_64         | 1        | 4.76%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.17  | 11       | 55%     |
| 5.15.0  | 5        | 25%     |
| 4.18.0  | 2        | 10%     |
| 5.4.11  | 1        | 5%      |
| 3.10.0  | 1        | 5%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 12       | 60%     |
| 5.15    | 5        | 25%     |
| 4.18    | 2        | 10%     |
| 3.10    | 1        | 5%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 20       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 14       | 70%     |
| Unknown       | 4        | 20%     |
| KDE5          | 1        | 5%      |
| GNOME Classic | 1        | 5%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 11       | 55%     |
| X11     | 6        | 30%     |
| Unknown | 3        | 15%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 14       | 70%     |
| GDM     | 4        | 20%     |
| TDM     | 1        | 5%      |
| SDDM    | 1        | 5%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 10       | 50%     |
| it_IT      | 2        | 10%     |
| en_GB      | 2        | 10%     |
| ru_RU      | 1        | 5%      |
| pl_PL      | 1        | 5%      |
| en_US.UTF8 | 1        | 5%      |
| en_IN      | 1        | 5%      |
| de_DE      | 1        | 5%      |
| Unknown    | 1        | 5%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 12       | 60%     |
| EFI  | 8        | 40%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 17       | 85%     |
| Ext4 | 2        | 10%     |
| Zfs  | 1        | 5%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 11       | 55%     |
| MBR     | 5        | 25%     |
| GPT     | 4        | 20%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 90%     |
| Yes       | 2        | 10%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 5        | 25%     |
| ASUSTek Computer    | 5        | 25%     |
| Gigabyte Technology | 4        | 20%     |
| Hewlett-Packard     | 2        | 10%     |
| MSI                 | 1        | 5%      |
| Foxconn             | 1        | 5%      |
| Cisco               | 1        | 5%      |
| ASRock              | 1        | 5%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| MSI MS-7758                      | 1        | 5%      |
| HP Z820 Workstation              | 1        | 5%      |
| HP Z420 Workstation              | 1        | 5%      |
| Gigabyte Z490 AORUS ELITE AC     | 1        | 5%      |
| Gigabyte X99-Designare EX-CF     | 1        | 5%      |
| Gigabyte X470 AORUS ULTRA GAMING | 1        | 5%      |
| Gigabyte H81M-S2PV               | 1        | 5%      |
| Foxconn p6-2400el                | 1        | 5%      |
| Dell PowerEdge FC630             | 1        | 5%      |
| Dell OptiPlex 980                | 1        | 5%      |
| Dell OptiPlex 7090               | 1        | 5%      |
| Dell OptiPlex 7060               | 1        | 5%      |
| Dell OptiPlex 5000               | 1        | 5%      |
| Cisco WAVE-694-K9                | 1        | 5%      |
| ASUS SABERTOOTH 990FX R3.0       | 1        | 5%      |
| ASUS PRIME B560M-A AC            | 1        | 5%      |
| ASUS P8H67                       | 1        | 5%      |
| ASUS G11CD                       | 1        | 5%      |
| ASUS All Series                  | 1        | 5%      |
| ASRock Z68 Extreme3 Gen3         | 1        | 5%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 4        | 20%     |
| MSI MS-7758            | 1        | 5%      |
| HP Z820                | 1        | 5%      |
| HP Z420                | 1        | 5%      |
| Gigabyte Z490          | 1        | 5%      |
| Gigabyte X99-Designare | 1        | 5%      |
| Gigabyte X470          | 1        | 5%      |
| Gigabyte H81M-S2PV     | 1        | 5%      |
| Foxconn p6-2400el      | 1        | 5%      |
| Dell PowerEdge         | 1        | 5%      |
| Cisco WAVE-694-K9      | 1        | 5%      |
| ASUS SABERTOOTH        | 1        | 5%      |
| ASUS PRIME             | 1        | 5%      |
| ASUS P8H67             | 1        | 5%      |
| ASUS G11CD             | 1        | 5%      |
| ASUS All               | 1        | 5%      |
| ASRock Z68             | 1        | 5%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 5        | 25%     |
| 2018 | 3        | 15%     |
| 2016 | 3        | 15%     |
| 2021 | 2        | 10%     |
| 2010 | 2        | 10%     |
| 2022 | 1        | 5%      |
| 2020 | 1        | 5%      |
| 2014 | 1        | 5%      |
| 2013 | 1        | 5%      |
| 2011 | 1        | 5%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 20       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 20       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 20       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 5        | 25%     |
| 64.01-256.0     | 4        | 20%     |
| 4.01-8.0        | 3        | 15%     |
| 32.01-64.0      | 2        | 10%     |
| 16.01-24.0      | 2        | 10%     |
| More than 256.0 | 1        | 5%      |
| 3.01-4.0        | 1        | 5%      |
| 24.01-32.0      | 1        | 5%      |
| 1.01-2.0        | 1        | 5%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 5        | 23.81%  |
| 2.01-3.0   | 5        | 23.81%  |
| 3.01-4.0   | 3        | 14.29%  |
| 1.01-2.0   | 3        | 14.29%  |
| 8.01-16.0  | 2        | 9.52%   |
| 16.01-24.0 | 1        | 4.76%   |
| 0.51-1.0   | 1        | 4.76%   |
| 0.01-0.5   | 1        | 4.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 8        | 40%     |
| 2      | 6        | 30%     |
| 3      | 3        | 15%     |
| 6      | 1        | 5%      |
| 5      | 1        | 5%      |
| 4      | 1        | 5%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 65%     |
| Yes       | 7        | 35%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 19       | 95%     |
| No        | 1        | 5%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 65%     |
| Yes       | 7        | 35%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 65%     |
| Yes       | 7        | 35%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 4        | 20%     |
| Germany   | 4        | 20%     |
| Russia    | 2        | 10%     |
| Italy     | 2        | 10%     |
| UK        | 1        | 5%      |
| Slovakia  | 1        | 5%      |
| Romania   | 1        | 5%      |
| Poland    | 1        | 5%      |
| India     | 1        | 5%      |
| Finland   | 1        | 5%      |
| Bolivia   | 1        | 5%      |
| Australia | 1        | 5%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Zavar           | 1        | 4.76%   |
| Weaverville     | 1        | 4.76%   |
| Warsaw          | 1        | 4.76%   |
| Veliky Novgorod | 1        | 4.76%   |
| Stuttgart       | 1        | 4.76%   |
| Santa Cruz      | 1        | 4.76%   |
| Riverside       | 1        | 4.76%   |
| Reading         | 1        | 4.76%   |
| Petersberg      | 1        | 4.76%   |
| Perugia         | 1        | 4.76%   |
| Parker          | 1        | 4.76%   |
| Neunkirchen     | 1        | 4.76%   |
| Moscow          | 1        | 4.76%   |
| Helsinki        | 1        | 4.76%   |
| Glendale        | 1        | 4.76%   |
| Bucharest       | 1        | 4.76%   |
| Berlin          | 1        | 4.76%   |
| Bengaluru       | 1        | 4.76%   |
| Asheville       | 1        | 4.76%   |
| Albairate       | 1        | 4.76%   |
| Adelaide        | 1        | 4.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 47     | 29.03%  |
| Samsung Electronics | 5        | 8      | 16.13%  |
| WDC                 | 4        | 5      | 12.9%   |
| Toshiba             | 3        | 3      | 9.68%   |
| Kingston            | 2        | 3      | 6.45%   |
| Crucial             | 2        | 2      | 6.45%   |
| SK hynix            | 1        | 1      | 3.23%   |
| SanDisk             | 1        | 3      | 3.23%   |
| Phison Electronics  | 1        | 1      | 3.23%   |
| Phison              | 1        | 1      | 3.23%   |
| Intel               | 1        | 1      | 3.23%   |
| Hewlett-Packard     | 1        | 1      | 3.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB                    | 2        | 5.26%   |
| Kingston SA400S37240G 240GB SSD                   | 2        | 5.26%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 1        | 2.63%   |
| WDC WD3200BEKT-08PVMT1 320GB                      | 1        | 2.63%   |
| WDC WD1600YS-23SHB0 160GB                         | 1        | 2.63%   |
| WDC WD10EZEX-60M2NA0 1TB                          | 1        | 2.63%   |
| Toshiba NVMe SSD Drive 512GB                      | 1        | 2.63%   |
| Toshiba MG04ACA200E 2TB                           | 1        | 2.63%   |
| Toshiba DT01ACA050 500GB                          | 1        | 2.63%   |
| SK hynix PC801 NVMe 512GB                         | 1        | 2.63%   |
| Seagate ST8000VN004-2M2101 8TB                    | 1        | 2.63%   |
| Seagate ST3750528AS 752GB                         | 1        | 2.63%   |
| Seagate ST3500414CS 500GB                         | 1        | 2.63%   |
| Seagate ST2000NX0253 2TB                          | 1        | 2.63%   |
| Seagate ST2000DM001-1ER164 2TB                    | 1        | 2.63%   |
| Seagate ST1000VX000-1ES162 1TB                    | 1        | 2.63%   |
| Seagate ST1000NX0423 1TB                          | 1        | 2.63%   |
| Seagate ST1000LX015-1U7172 1TB                    | 1        | 2.63%   |
| Seagate ST1000LM010-9YH146 1TB                    | 1        | 2.63%   |
| SanDisk SSD PLUS 2000GB                           | 1        | 2.63%   |
| SanDisk SDSSDH32000G 2TB                          | 1        | 2.63%   |
| Samsung SSD PM830 2.5 7mm 256GB                   | 1        | 2.63%   |
| Samsung SSD 960 EVO 250GB                         | 1        | 2.63%   |
| Samsung SSD 860 EVO 500GB                         | 1        | 2.63%   |
| Samsung SSD 860 EVO 250GB                         | 1        | 2.63%   |
| Samsung SSD 850 EVO 2TB                           | 1        | 2.63%   |
| Samsung SSD 840 PRO Series 256GB                  | 1        | 2.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 1        | 2.63%   |
| Samsung HD502IJ 500GB                             | 1        | 2.63%   |
| Phison NVMe SSD Drive 1TB                         | 1        | 2.63%   |
| Phison E12 NVMe Controller 1TB                    | 1        | 2.63%   |
| Kingston SUV400S37240G 240GB SSD                  | 1        | 2.63%   |
| Intel SSDSA2CW080G3 80GB                          | 1        | 2.63%   |
| HP SSD S700 120GB                                 | 1        | 2.63%   |
| Crucial CT500MX500SSD1 500GB                      | 1        | 2.63%   |
| Crucial CT2050MX300SSD1 2TB                       | 1        | 2.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 47     | 60%     |
| WDC                 | 3        | 4      | 20%     |
| Toshiba             | 2        | 2      | 13.33%  |
| Samsung Electronics | 1        | 1      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 5      | 33.33%  |
| Kingston            | 2        | 3      | 16.67%  |
| Crucial             | 2        | 2      | 16.67%  |
| WDC                 | 1        | 1      | 8.33%   |
| SanDisk             | 1        | 3      | 8.33%   |
| Intel               | 1        | 1      | 8.33%   |
| Hewlett-Packard     | 1        | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 13       | 54     | 44.83%  |
| SSD  | 10       | 16     | 34.48%  |
| NVMe | 6        | 6      | 20.69%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 19       | 70     | 76%     |
| NVMe | 6        | 6      | 24%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 12       | 17     | 50%     |
| 1.01-2.0   | 6        | 44     | 25%     |
| 0.51-1.0   | 5        | 7      | 20.83%  |
| 4.01-10.0  | 1        | 2      | 4.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 7        | 35%     |
| 101-250        | 3        | 15%     |
| 1001-2000      | 3        | 15%     |
| 501-1000       | 3        | 15%     |
| More than 3000 | 1        | 5%      |
| 21-50          | 1        | 5%      |
| 2001-3000      | 1        | 5%      |
| Unknown        | 1        | 5%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 6        | 30%     |
| 101-250        | 6        | 30%     |
| 1-20           | 5        | 25%     |
| More than 3000 | 1        | 5%      |
| 51-100         | 1        | 5%      |
| Unknown        | 1        | 5%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| Hewlett-Packard SSD S700 120GB | 1        | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| Hewlett-Packard | 1        | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 1        | 1      | 100%    |

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
| Detected | 11       | 27     | 55%     |
| Works    | 8        | 48     | 40%     |
| Malfunc  | 1        | 1      | 5%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 18       | 62.07%  |
| Samsung Electronics          | 2        | 6.9%    |
| Phison Electronics           | 2        | 6.9%    |
| Broadcom / LSI               | 2        | 6.9%    |
| AMD                          | 2        | 6.9%    |
| VIA Technologies             | 1        | 3.45%   |
| Toshiba America Info Systems | 1        | 3.45%   |
| SK hynix                     | 1        | 3.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Phison E12 NVMe Controller                                                              | 2        | 5.13%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 5.13%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 5.13%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 5.13%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2        | 5.13%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2        | 5.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 5.13%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 5.13%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 5.13%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 5.13%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 2.56%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 1        | 2.56%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                      | 1        | 2.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 2.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 2.56%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 2.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 2.56%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 2.56%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 2.56%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 2.56%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 2.56%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 2.56%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1        | 2.56%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                            | 1        | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 2.56%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 1        | 2.56%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 2.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 15       | 46.88%  |
| NVMe | 6        | 18.75%  |
| IDE  | 5        | 15.63%  |
| RAID | 4        | 12.5%   |
| SAS  | 2        | 6.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 18       | 90%     |
| AMD    | 2        | 10%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Xeon CPU X3450 @ 2.67GHz         | 1        | 5%      |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz    | 1        | 5%      |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz    | 1        | 5%      |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz    | 1        | 5%      |
| Intel Pentium CPU G3240 @ 3.10GHz      | 1        | 5%      |
| Intel Pentium CPU G2020 @ 2.90GHz      | 1        | 5%      |
| Intel Core i9-10900K CPU @ 3.70GHz     | 1        | 5%      |
| Intel Core i7-8700 CPU @ 3.20GHz       | 1        | 5%      |
| Intel Core i7-6800K CPU @ 3.40GHz      | 1        | 5%      |
| Intel Core i7-6700 CPU @ 3.40GHz       | 1        | 5%      |
| Intel Core i7-3770 CPU @ 3.40GHz       | 1        | 5%      |
| Intel Core i7-2600 CPU @ 3.40GHz       | 1        | 5%      |
| Intel Core i7-10700K CPU @ 3.80GHz     | 1        | 5%      |
| Intel Core i5-4460 CPU @ 3.20GHz       | 1        | 5%      |
| Intel Core i5-10500 CPU @ 3.10GHz      | 1        | 5%      |
| Intel Core i3-2120 CPU @ 3.30GHz       | 1        | 5%      |
| Intel Core i3 CPU 550 @ 3.20GHz        | 1        | 5%      |
| Intel 12th Gen Core i7-12700           | 1        | 5%      |
| AMD Ryzen 7 2700X Eight-Core Processor | 1        | 5%      |
| AMD FX-8350 Eight-Core Processor       | 1        | 5%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| Intel Core i7 | 6        | 30%     |
| Intel Xeon    | 4        | 20%     |
| Intel Pentium | 2        | 10%     |
| Intel Core i5 | 2        | 10%     |
| Intel Core i3 | 2        | 10%     |
| Other         | 1        | 5%      |
| Intel Core i9 | 1        | 5%      |
| AMD Ryzen 7   | 1        | 5%      |
| AMD FX        | 1        | 5%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 6        | 30%     |
| 2      | 4        | 20%     |
| 6      | 3        | 15%     |
| 16     | 2        | 10%     |
| 10     | 2        | 10%     |
| 8      | 2        | 10%     |
| 12     | 1        | 5%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 18       | 90%     |
| 2      | 2        | 10%     |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 17       | 85%     |
| 1      | 3        | 15%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 20       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 3        | 15%     |
| 0xa0655    | 2        | 10%     |
| 0x306e4    | 2        | 10%     |
| 0x306c3    | 2        | 10%     |
| 0x306a9    | 2        | 10%     |
| 0x206a7    | 2        | 10%     |
| 0xa0653    | 1        | 5%      |
| 0x906ea    | 1        | 5%      |
| 0x506e3    | 1        | 5%      |
| 0x406f1    | 1        | 5%      |
| 0x20655    | 1        | 5%      |
| 0x106e5    | 1        | 5%      |
| 0x0800820d | 1        | 5%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| IvyBridge   | 4        | 20%     |
| CometLake   | 3        | 15%     |
| SandyBridge | 2        | 10%     |
| Haswell     | 2        | 10%     |
| Broadwell   | 2        | 10%     |
| Zen+        | 1        | 5%      |
| Westmere    | 1        | 5%      |
| Skylake     | 1        | 5%      |
| Piledriver  | 1        | 5%      |
| Nehalem     | 1        | 5%      |
| KabyLake    | 1        | 5%      |
| Unknown     | 1        | 5%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 10       | 41.67%  |
| Intel                      | 10       | 41.67%  |
| AMD                        | 3        | 12.5%   |
| Matrox Electronics Systems | 1        | 4.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 12.5%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 8.33%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 4.17%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 4.17%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 4.17%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 1        | 4.17%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 4.17%   |
| Nvidia GK110GL [Quadro K6000]                                               | 1        | 4.17%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 4.17%   |
| Nvidia GF110GL [Tesla C2050 / C2075]                                        | 1        | 4.17%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 1        | 4.17%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 4.17%   |
| Matrox Electronics Systems G200eR2                                          | 1        | 4.17%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 4.17%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 4.17%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 4.17%   |
| Intel AlderLake-S GT1                                                       | 1        | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 4.17%   |
| AMD Turks [Radeon HD 7600 Series]                                           | 1        | 4.17%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 4.17%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 4.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 7        | 35%     |
| 1 x Intel      | 7        | 35%     |
| AMD + Nvidia   | 2        | 10%     |
| Other          | 1        | 5%      |
| 1 x Matrox     | 1        | 5%      |
| Intel + Nvidia | 1        | 5%      |
| 1 x AMD        | 1        | 5%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 15       | 75%     |
| Unknown     | 3        | 15%     |
| Proprietary | 2        | 10%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 12       | 60%     |
| 3.01-4.0   | 4        | 20%     |
| 1.01-2.0   | 2        | 10%     |
| 5.01-6.0   | 1        | 5%      |
| 8.01-16.0  | 1        | 5%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 4        | 20%     |
| Hewlett-Packard     | 3        | 15%     |
| Dell                | 3        | 15%     |
| Vizio               | 1        | 5%      |
| Viotek              | 1        | 5%      |
| SAC                 | 1        | 5%      |
| Packard Bell        | 1        | 5%      |
| Goldstar            | 1        | 5%      |
| GameMax             | 1        | 5%      |
| Fujitsu Siemens     | 1        | 5%      |
| Eizo                | 1        | 5%      |
| BenQ                | 1        | 5%      |
| ASUSTek Computer    | 1        | 5%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Vizio V705-H3 VIZ1039 3840x2160 1538x865mm 69.5-inch                | 1        | 4.55%   |
| Viotek SUW49C VTK4900 3840x1080 1196x336mm 48.9-inch                | 1        | 4.55%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch | 1        | 4.55%   |
| Samsung Electronics S27D391 SAM0B89 1920x1080 598x336mm 27.0-inch   | 1        | 4.55%   |
| Samsung Electronics S27D391 SAM0B88 1920x1080 598x336mm 27.0-inch   | 1        | 4.55%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch   | 1        | 4.55%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch   | 1        | 4.55%   |
| Samsung Electronics LCD Monitor S24C650                             | 1        | 4.55%   |
| SAC DM-MONB2205 SAC952D 1920x1080 450x270mm 20.7-inch               | 1        | 4.55%   |
| Packard Bell Viseo223DX PKB037A 1920x1080 477x268mm 21.5-inch       | 1        | 4.55%   |
| Hewlett-Packard ZR24w HWP2869 1920x1200 546x352mm 25.6-inch         | 1        | 4.55%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch          | 1        | 4.55%   |
| Hewlett-Packard E273q HPN3474 2560x1440 597x336mm 27.0-inch         | 1        | 4.55%   |
| Goldstar E2240 GSM57A3 1920x1080 477x268mm 21.5-inch                | 1        | 4.55%   |
| GameMax HDMI-DA GMX0001 1920x540                                    | 1        | 4.55%   |
| Fujitsu Siemens B22W-5 ECO FUS07C4 1680x1050 474x296mm 22.0-inch    | 1        | 4.55%   |
| Eizo EV2460 ENC3129 1920x1080 528x297mm 23.9-inch                   | 1        | 4.55%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                   | 1        | 4.55%   |
| Dell LCD Monitor U2415 3840x1200                                    | 1        | 4.55%   |
| Dell LCD Monitor DEL0001 1280x1024                                  | 1        | 4.55%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                   | 1        | 4.55%   |
| ASUSTek Computer PA248QV AUS2400 1920x1200 520x320mm 24.0-inch      | 1        | 4.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 8        | 42.11%  |
| 1920x1200 (WUXGA)  | 2        | 10.53%  |
| 3840x2160 (4K)     | 1        | 5.26%   |
| 3840x1200          | 1        | 5.26%   |
| 3840x1080          | 1        | 5.26%   |
| 2560x1440 (QHD)    | 1        | 5.26%   |
| 1920x540           | 1        | 5.26%   |
| 1680x1050 (WSXGA+) | 1        | 5.26%   |
| 1360x768           | 1        | 5.26%   |
| 1280x1024 (SXGA)   | 1        | 5.26%   |
| Unknown            | 1        | 5.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 4        | 20%     |
| 21      | 4        | 20%     |
| Unknown | 3        | 15%     |
| 27      | 2        | 10%     |
| 23      | 2        | 10%     |
| 69      | 1        | 5%      |
| 48      | 1        | 5%      |
| 25      | 1        | 5%      |
| 22      | 1        | 5%      |
| 18      | 1        | 5%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 8        | 44.44%  |
| 401-500     | 5        | 27.78%  |
| Unknown     | 3        | 16.67%  |
| 1501-2000   | 1        | 5.56%   |
| 1001-1500   | 1        | 5.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 11       | 61.11%  |
| 16/10   | 3        | 16.67%  |
| 32/9    | 2        | 11.11%  |
| 5/4     | 1        | 5.56%   |
| Unknown | 1        | 5.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 7        | 38.89%  |
| Unknown        | 3        | 16.67%  |
| 301-350        | 2        | 11.11%  |
| 251-300        | 2        | 11.11%  |
| More than 1000 | 1        | 5.56%   |
| 151-200        | 1        | 5.56%   |
| 141-150        | 1        | 5.56%   |
| 501-1000       | 1        | 5.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 11       | 57.89%  |
| 101-120 | 5        | 26.32%  |
| Unknown | 3        | 15.79%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 12       | 60%     |
| 2     | 3        | 15%     |
| 0     | 3        | 15%     |
| 3     | 2        | 10%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 12       | 44.44%  |
| Realtek Semiconductor | 9        | 33.33%  |
| Broadcom              | 2        | 7.41%   |
| Qualcomm Atheros      | 1        | 3.7%    |
| QLogic                | 1        | 3.7%    |
| Mellanox Technologies | 1        | 3.7%    |
| ASUSTek Computer      | 1        | 3.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6        | 18.75%  |
| Intel I211 Gigabit Network Connection                             | 3        | 9.38%   |
| Intel Wireless 8260                                               | 2        | 6.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 6.25%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 6.25%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 3.13%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1        | 3.13%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 3.13%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1        | 3.13%   |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller          | 1        | 3.13%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 1        | 3.13%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1        | 3.13%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 3.13%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 3.13%   |
| Intel Ethernet Connection (17) I219-LM                            | 1        | 3.13%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 3.13%   |
| Intel Ethernet Connection (14) I219-LM                            | 1        | 3.13%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1        | 3.13%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 3.13%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1        | 3.13%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1        | 3.13%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]         | 1        | 3.13%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 4        | 50%     |
| Realtek Semiconductor | 2        | 25%     |
| Qualcomm Atheros      | 1        | 12.5%   |
| ASUSTek Computer      | 1        | 12.5%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wireless 8260                                            | 2        | 25%     |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1        | 12.5%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1        | 12.5%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 12.5%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1        | 12.5%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1        | 12.5%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]      | 1        | 12.5%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 11       | 50%     |
| Realtek Semiconductor | 7        | 31.82%  |
| Broadcom              | 2        | 9.09%   |
| QLogic                | 1        | 4.55%   |
| Mellanox Technologies | 1        | 4.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6        | 25%     |
| Intel I211 Gigabit Network Connection                             | 3        | 12.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 8.33%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 8.33%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 4.17%   |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller          | 1        | 4.17%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 1        | 4.17%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 4.17%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 4.17%   |
| Intel Ethernet Connection (17) I219-LM                            | 1        | 4.17%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 4.17%   |
| Intel Ethernet Connection (14) I219-LM                            | 1        | 4.17%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 4.17%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1        | 4.17%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1        | 4.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 19       | 73.08%  |
| WiFi     | 7        | 26.92%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 18       | 85.71%  |
| WiFi     | 3        | 14.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 9        | 45%     |
| 1     | 9        | 45%     |
| 4     | 1        | 5%      |
| 3     | 1        | 5%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 18       | 90%     |
| Yes  | 2        | 10%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 4        | 50%     |
| ASUSTek Computer | 2        | 25%     |
| IMC Networks     | 1        | 12.5%   |
| Broadcom         | 1        | 12.5%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface             | 2        | 25%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 2        | 25%     |
| ASUS Broadcom BCM20702A0 Bluetooth             | 2        | 25%     |
| IMC Networks Bluetooth Radio                   | 1        | 12.5%   |
| Broadcom BCM20702A0 Bluetooth 4.0              | 1        | 12.5%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 15       | 46.88%  |
| Nvidia                 | 9        | 28.13%  |
| AMD                    | 4        | 12.5%   |
| M-Audio                | 1        | 3.13%   |
| GN Netcom              | 1        | 3.13%   |
| C-Media Electronics    | 1        | 3.13%   |
| AKAI Professional M.I. | 1        | 3.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 8.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 5.56%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 2        | 5.56%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 5.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 5.56%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 2.78%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 2.78%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 2.78%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 2.78%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 2.78%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 2.78%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 2.78%   |
| Nvidia GF110 High Definition Audio Controller                              | 1        | 2.78%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 2.78%   |
| M-Audio AIR HUB                                                            | 1        | 2.78%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 2.78%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 2.78%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 2.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 2.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 2.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 2.78%   |
| GN Netcom Jabra EVOLVE LINK                                                | 1        | 2.78%   |
| C-Media Electronics TONOR TC30 Audio Device                                | 1        | 2.78%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 2.78%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 2.78%   |
| AMD Navi 10 HDMI Audio                                                     | 1        | 2.78%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 2.78%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 2.78%   |
| AKAI Professional M.I. MPK mini 3                                          | 1        | 2.78%   |
| AKAI Professional M.I. FL STUDIO FIRE                                      | 1        | 2.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Micron Technology   | 3        | 37.5%   |
| Kingston            | 2        | 25%     |
| Unigen              | 1        | 12.5%   |
| Samsung Electronics | 1        | 12.5%   |
| Crucial             | 1        | 12.5%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unigen RAM Module 4GB DIMM DDR3 1333MT/s                  | 1        | 9.09%   |
| Samsung RAM M393B2G70BH0-YH9 16GB DIMM DDR3 1333MT/s      | 1        | 9.09%   |
| Micron RAM 8ATF1G64AZ-2G3H1 8GB DIMM DDR4 2448MT/s        | 1        | 9.09%   |
| Micron RAM 8ATF1G64AZ-2G3E1 8192MB DIMM DDR4 2400MT/s     | 1        | 9.09%   |
| Micron RAM 8ATF1G64AZ-2G3B1 8GB DIMM DDR4 2448MT/s        | 1        | 9.09%   |
| Micron RAM 4ATF1G64AZ-3G2F1 8GB DIMM DDR4 3200MT/s        | 1        | 9.09%   |
| Micron RAM 18ASF2G72PDZ-2G3B1 16GB DIMM DDR4 2400MT/s     | 1        | 9.09%   |
| Kingston RAM KTW149-ELF 1GB DIMM DDR3 1333MT/s            | 1        | 9.09%   |
| Kingston RAM 9905471-006.A00LF 4096MB DIMM DDR3 1333MT/s  | 1        | 9.09%   |
| Kingston RAM 9905403-892.A00LF 8GB DIMM DDR3 1333MT/s     | 1        | 9.09%   |
| Crucial RAM BLE8G4D34AEEAK.K8FB 8192MB DIMM DDR4 3466MT/s | 1        | 9.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 4        | 50%     |
| DDR3 | 4        | 50%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 8        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 4        | 44.44%  |
| 16384 | 2        | 22.22%  |
| 4096  | 2        | 22.22%  |
| 1024  | 1        | 11.11%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1333  | 4        | 44.44%  |
| 2400  | 2        | 22.22%  |
| 3466  | 1        | 11.11%  |
| 3200  | 1        | 11.11%  |
| 2448  | 1        | 11.11%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Samsung ML-1660 Series | 1        | 100%    |

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
| Microdia | 1        | 50%     |
| Logitech | 1        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| Microdia Webcam Vitade AF | 1        | 50%     |
| Logitech Webcam C270      | 1        | 50%     |

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
| 0     | 15       | 75%     |
| 2     | 3        | 15%     |
| 1     | 2        | 10%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Unassigned class         | 2        | 28.57%  |
| Graphics card            | 2        | 28.57%  |
| Net/wireless             | 1        | 14.29%  |
| Communication controller | 1        | 14.29%  |
| Bluetooth                | 1        | 14.29%  |

