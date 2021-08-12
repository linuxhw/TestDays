Zorin 16 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for Zorin 16 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=zorin-16

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

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek  | PRIME X570-PRO              | [fb7eb46b29](https://linux-hardware.org/?probe=fb7eb46b29) | Aug 11, 2021 |
| ASUSTek  | SABERTOOTH Z97 MARK 1       | [fb8a0b07d1](https://linux-hardware.org/?probe=fb8a0b07d1) | Aug 10, 2021 |
| ASUSTek  | M5A97 LE R2.0               | [4d9eaaf5a8](https://linux-hardware.org/?probe=4d9eaaf5a8) | Aug 09, 2021 |
| Gigabyte | B550M H                     | [b26c567912](https://linux-hardware.org/?probe=b26c567912) | Aug 03, 2021 |
| ASUSTek  | M5A78L-M/USB3               | [9c841a04d6](https://linux-hardware.org/?probe=9c841a04d6) | Aug 01, 2021 |
| Gigabyte | H61M-USB3-B3                | [3c2020fbb6](https://linux-hardware.org/?probe=3c2020fbb6) | Jul 30, 2021 |
| Gigabyte | H61M-USB3-B3                | [b3bbc6d937](https://linux-hardware.org/?probe=b3bbc6d937) | Jul 30, 2021 |
| Dell     | 0V8WGR A00                  | [2cf38ffd15](https://linux-hardware.org/?probe=2cf38ffd15) | Jul 14, 2021 |
| ASUSTek  | P8H61-M LE                  | [b0270beb17](https://linux-hardware.org/?probe=b0270beb17) | Jul 11, 2021 |
| ASUSTek  | P8H61-M LE                  | [896e6feb8a](https://linux-hardware.org/?probe=896e6feb8a) | Jul 11, 2021 |
| Lenovo   | 36C5 SDK0J40700 WIN 3258... | [20bf622c31](https://linux-hardware.org/?probe=20bf622c31) | Jun 25, 2021 |
| ASUSTek  | PRIME B450M-GAMING/BR       | [35605881d6](https://linux-hardware.org/?probe=35605881d6) | Jun 23, 2021 |
| MSI      | 2AE0                        | [bce75d51cd](https://linux-hardware.org/?probe=bce75d51cd) | Jun 23, 2021 |
| MSI      | 2AE0                        | [0412c710eb](https://linux-hardware.org/?probe=0412c710eb) | Jun 22, 2021 |
| ASUSTek  | PRIME B450M-GAMING/BR       | [b9d86eb932](https://linux-hardware.org/?probe=b9d86eb932) | Jun 17, 2021 |
| ASUSTek  | PRIME B450M-GAMING/BR       | [71de5617aa](https://linux-hardware.org/?probe=71de5617aa) | Jun 17, 2021 |
| ASUSTek  | PRIME X570-P                | [bca1e1b92f](https://linux-hardware.org/?probe=bca1e1b92f) | Jun 16, 2021 |
| ASUSTek  | PRIME X570-P                | [b3f6c76103](https://linux-hardware.org/?probe=b3f6c76103) | Jun 16, 2021 |
| Gigabyte | B85-HD3                     | [c73931b3ff](https://linux-hardware.org/?probe=c73931b3ff) | Jun 13, 2021 |
| HP       | 843C                        | [ccff6e4f39](https://linux-hardware.org/?probe=ccff6e4f39) | Jun 08, 2021 |
| ASRock   | 990FX Extreme6              | [fc3b27abac](https://linux-hardware.org/?probe=fc3b27abac) | Jun 03, 2021 |
| HP       | 8591                        | [6f71430d88](https://linux-hardware.org/?probe=6f71430d88) | Jun 01, 2021 |
| HP       | 8591                        | [fc12c57885](https://linux-hardware.org/?probe=fc12c57885) | Jun 01, 2021 |
| ASRock   | 990FX Extreme6              | [0a228b18c1](https://linux-hardware.org/?probe=0a228b18c1) | May 30, 2021 |
| ASUSTek  | PRIME B450M-GAMING/BR       | [0144616bb9](https://linux-hardware.org/?probe=0144616bb9) | May 27, 2021 |
| Gigabyte | 945GCM-S2L                  | [9890da0efd](https://linux-hardware.org/?probe=9890da0efd) | May 27, 2021 |
| Gigabyte | 945GCM-S2L                  | [61e1972b06](https://linux-hardware.org/?probe=61e1972b06) | May 27, 2021 |
| Lenovo   | SHARKBAY 0B98401 PRO        | [887dbc1614](https://linux-hardware.org/?probe=887dbc1614) | May 24, 2021 |
| Biostar  | A320MH                      | [db3a18e1c3](https://linux-hardware.org/?probe=db3a18e1c3) | May 23, 2021 |
| Biostar  | A320MH                      | [ccb22fc057](https://linux-hardware.org/?probe=ccb22fc057) | May 23, 2021 |
| Lenovo   | SHARKBAY 0B98401 PRO        | [0c314899c1](https://linux-hardware.org/?probe=0c314899c1) | May 23, 2021 |
| ASUSTek  | PRIME B450M-GAMING/BR       | [c41eec9cd3](https://linux-hardware.org/?probe=c41eec9cd3) | May 21, 2021 |
| ASUSTek  | PRIME B450M-GAMING/BR       | [ca773b28ee](https://linux-hardware.org/?probe=ca773b28ee) | May 19, 2021 |
| ASUSTek  | P8H61-I R2.0                | [c641f2aee4](https://linux-hardware.org/?probe=c641f2aee4) | May 16, 2021 |
| ASUSTek  | P8H61-I R2.0                | [500443b449](https://linux-hardware.org/?probe=500443b449) | May 16, 2021 |
| Lenovo   | Annapurna CRB NOK           | [7d4224df3f](https://linux-hardware.org/?probe=7d4224df3f) | May 13, 2021 |
| Lenovo   | Annapurna CRB NOK           | [adef2ac504](https://linux-hardware.org/?probe=adef2ac504) | May 13, 2021 |
| Dell     | 06D7TR A00                  | [1ccb5b0600](https://linux-hardware.org/?probe=1ccb5b0600) | May 01, 2021 |
| Pegatron | Benicia                     | [df847c36d5](https://linux-hardware.org/?probe=df847c36d5) | Apr 25, 2021 |
| Gigabyte | B450 AORUS ELITE            | [7f46cdb7ab](https://linux-hardware.org/?probe=7f46cdb7ab) | Apr 24, 2021 |
| ASUSTek  | M4A88TD-V EVO/USB3          | [b00e95f3db](https://linux-hardware.org/?probe=b00e95f3db) | Apr 22, 2021 |
| ASUSTek  | P5K                         | [0149b6c450](https://linux-hardware.org/?probe=0149b6c450) | Apr 22, 2021 |
| Dell     | 0PGKWF A02                  | [f963717b2c](https://linux-hardware.org/?probe=f963717b2c) | Apr 18, 2021 |
| Acer     | Aspire XC-605G              | [79d3d3a05e](https://linux-hardware.org/?probe=79d3d3a05e) | Mar 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.8.0-53-generic  | 7        | 25%     |
| 5.8.0-55-generic  | 5        | 17.86%  |
| 5.8.0-50-generic  | 5        | 17.86%  |
| 5.8.0-59-generic  | 3        | 10.71%  |
| 5.8.0-49-generic  | 3        | 10.71%  |
| 5.8.0-63-generic  | 2        | 7.14%   |
| 5.11.0-25-generic | 2        | 7.14%   |
| 5.8.0-45-generic  | 1        | 3.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.8.0   | 25       | 92.59%  |
| 5.11.0  | 2        | 7.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.8     | 25       | 92.59%  |
| 5.11    | 2        | 7.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 27       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| GNOME    | 26       | 96.3%   |
| Cinnamon | 1        | 3.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 27       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 25       | 92.59%  |
| TDM     | 1        | 3.7%    |
| GDM     | 1        | 3.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 14       | 51.85%  |
| pt_BR | 4        | 14.81%  |
| de_DE | 3        | 11.11%  |
| pl_PL | 1        | 3.7%    |
| nl_NL | 1        | 3.7%    |
| nl_BE | 1        | 3.7%    |
| es_PE | 1        | 3.7%    |
| es_MX | 1        | 3.7%    |
| es_ES | 1        | 3.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 14       | 51.85%  |
| EFI  | 13       | 48.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 26       | 96.3%   |
| Overlay | 1        | 3.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 25       | 92.59%  |
| MBR     | 1        | 3.7%    |
| GPT     | 1        | 3.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 26       | 96.3%   |
| Yes       | 1        | 3.7%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 85.19%  |
| Yes       | 4        | 14.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 10       | 37.04%  |
| Gigabyte Technology | 5        | 18.52%  |
| Lenovo              | 3        | 11.11%  |
| Hewlett-Packard     | 2        | 7.41%   |
| Dell                | 2        | 7.41%   |
| Pegatron            | 1        | 3.7%    |
| MSI                 | 1        | 3.7%    |
| Biostar             | 1        | 3.7%    |
| ASRock              | 1        | 3.7%    |
| Acer                | 1        | 3.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Dell OptiPlex 990                       | 2        | 7.41%   |
| Pegatron NE502AV-ABA a6750t             | 1        | 3.7%    |
| MSI Pro 3515 Series                     | 1        | 3.7%    |
| Lenovo ThinkCentre M83 MT-M 10AJ-0003MB | 1        | 3.7%    |
| Lenovo ThinkCentre M78 10BTA00ELM       | 1        | 3.7%    |
| Lenovo IdeaCentre 510S-08IKL 90GB004RUS | 1        | 3.7%    |
| HP Z1 Entry Tower G5                    | 1        | 3.7%    |
| HP 290 G2 MT Business PC                | 1        | 3.7%    |
| Gigabyte Komputer OPTIMUS               | 1        | 3.7%    |
| Gigabyte H61M-USB3-B3                   | 1        | 3.7%    |
| Gigabyte B85-HD3                        | 1        | 3.7%    |
| Gigabyte B550M H                        | 1        | 3.7%    |
| Gigabyte B450 AORUS ELITE               | 1        | 3.7%    |
| Biostar A320MH                          | 1        | 3.7%    |
| ASUS UNLOCK INSTALL                     | 1        | 3.7%    |
| ASUS PRIME X570-PRO                     | 1        | 3.7%    |
| ASUS PRIME X570-P                       | 1        | 3.7%    |
| ASUS PRIME B450M-GAMING/BR              | 1        | 3.7%    |
| ASUS P8H61-M LE                         | 1        | 3.7%    |
| ASUS P5K                                | 1        | 3.7%    |
| ASUS M5A97 LE R2.0                      | 1        | 3.7%    |
| ASUS M5A78L-M/USB3                      | 1        | 3.7%    |
| ASUS M4A88TD-V EVO/USB3                 | 1        | 3.7%    |
| ASUS All Series                         | 1        | 3.7%    |
| ASRock 990FX Extreme6                   | 1        | 3.7%    |
| Acer Aspire XC-605G                     | 1        | 3.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS PRIME            | 3        | 11.11%  |
| Lenovo ThinkCentre    | 2        | 7.41%   |
| Dell OptiPlex         | 2        | 7.41%   |
| Pegatron NE502AV-ABA  | 1        | 3.7%    |
| MSI Pro               | 1        | 3.7%    |
| Lenovo IdeaCentre     | 1        | 3.7%    |
| HP Z1                 | 1        | 3.7%    |
| HP 290                | 1        | 3.7%    |
| Gigabyte Komputer     | 1        | 3.7%    |
| Gigabyte H61M-USB3-B3 | 1        | 3.7%    |
| Gigabyte B85-HD3      | 1        | 3.7%    |
| Gigabyte B550M        | 1        | 3.7%    |
| Gigabyte B450         | 1        | 3.7%    |
| Biostar A320MH        | 1        | 3.7%    |
| ASUS UNLOCK           | 1        | 3.7%    |
| ASUS P8H61-M          | 1        | 3.7%    |
| ASUS P5K              | 1        | 3.7%    |
| ASUS M5A97            | 1        | 3.7%    |
| ASUS M5A78L-M         | 1        | 3.7%    |
| ASUS M4A88TD-V        | 1        | 3.7%    |
| ASUS All              | 1        | 3.7%    |
| ASRock 990FX          | 1        | 3.7%    |
| Acer Aspire           | 1        | 3.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 5        | 18.52%  |
| 2014 | 4        | 14.81%  |
| 2021 | 3        | 11.11%  |
| 2018 | 3        | 11.11%  |
| 2019 | 2        | 7.41%   |
| 2015 | 2        | 7.41%   |
| 2013 | 2        | 7.41%   |
| 2016 | 1        | 3.7%    |
| 2011 | 1        | 3.7%    |
| 2010 | 1        | 3.7%    |
| 2009 | 1        | 3.7%    |
| 2008 | 1        | 3.7%    |
| 2007 | 1        | 3.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 27       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 25       | 92.59%  |
| Enabled  | 2        | 7.41%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 27       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 8.01-16.0  | 9        | 32.14%  |
| 16.01-24.0 | 8        | 28.57%  |
| 4.01-8.0   | 4        | 14.29%  |
| 32.01-64.0 | 3        | 10.71%  |
| 3.01-4.0   | 3        | 10.71%  |
| 1.01-2.0   | 1        | 3.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 15       | 53.57%  |
| 2.01-3.0 | 8        | 28.57%  |
| 4.01-8.0 | 2        | 7.14%   |
| 3.01-4.0 | 2        | 7.14%   |
| 0.51-1.0 | 1        | 3.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 11       | 40.74%  |
| 2      | 8        | 29.63%  |
| 3      | 4        | 14.81%  |
| 4      | 2        | 7.41%   |
| 5      | 1        | 3.7%    |
| 0      | 1        | 3.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 22       | 81.48%  |
| No        | 5        | 18.52%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 27       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 62.96%  |
| Yes       | 10       | 37.04%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 74.07%  |
| Yes       | 7        | 25.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 12       | 44.44%  |
| Brazil      | 4        | 14.81%  |
| Germany     | 3        | 11.11%  |
| Spain       | 1        | 3.7%    |
| Poland      | 1        | 3.7%    |
| Peru        | 1        | 3.7%    |
| Netherlands | 1        | 3.7%    |
| Mexico      | 1        | 3.7%    |
| Denmark     | 1        | 3.7%    |
| Belgium     | 1        | 3.7%    |
| Australia   | 1        | 3.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Xalapa                 | 1        | 3.7%    |
| Vespasiano             | 1        | 3.7%    |
| Trujillo               | 1        | 3.7%    |
| São Bernardo do Campo | 1        | 3.7%    |
| Sacramento             | 1        | 3.7%    |
| Rio de Janeiro         | 1        | 3.7%    |
| Pascoag                | 1        | 3.7%    |
| Palm Coast             | 1        | 3.7%    |
| Oscoda                 | 1        | 3.7%    |
| Oak Creek              | 1        | 3.7%    |
| Mentor                 | 1        | 3.7%    |
| Melbourne              | 1        | 3.7%    |
| Ludwigsburg            | 1        | 3.7%    |
| Idaho Falls            | 1        | 3.7%    |
| Hamburg                | 1        | 3.7%    |
| Ghent                  | 1        | 3.7%    |
| Gdynia                 | 1        | 3.7%    |
| Fort Worth             | 1        | 3.7%    |
| Copenhagen             | 1        | 3.7%    |
| Contagem               | 1        | 3.7%    |
| Charlottesville        | 1        | 3.7%    |
| Bedum                  | 1        | 3.7%    |
| Beacon                 | 1        | 3.7%    |
| Baltimore              | 1        | 3.7%    |
| Bad Mergentheim        | 1        | 3.7%    |
| Arlington              | 1        | 3.7%    |
| Aldaia                 | 1        | 3.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 11       | 16     | 25%     |
| Seagate                   | 7        | 9      | 15.91%  |
| Samsung Electronics       | 6        | 9      | 13.64%  |
| Kingston                  | 4        | 5      | 9.09%   |
| Sandisk                   | 3        | 5      | 6.82%   |
| Toshiba                   | 2        | 2      | 4.55%   |
| Phison                    | 2        | 2      | 4.55%   |
| Unknown                   | 1        | 1      | 2.27%   |
| Silicon Motion            | 1        | 3      | 2.27%   |
| Micron/Crucial Technology | 1        | 1      | 2.27%   |
| Maxtor                    | 1        | 1      | 2.27%   |
| Lexar                     | 1        | 1      | 2.27%   |
| KingFast                  | 1        | 1      | 2.27%   |
| JMicron                   | 1        | 1      | 2.27%   |
| Hewlett-Packard           | 1        | 1      | 2.27%   |
| A-DATA Technology         | 1        | 1      | 2.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB            | 2        | 3.92%   |
| Phison NVMe SSD Drive 1TB           | 2        | 3.92%   |
| WDC WDS250G2B0A-00SM50 250GB SSD    | 1        | 1.96%   |
| WDC WD5000AAKX-08U6AA0 500GB        | 1        | 1.96%   |
| WDC WD5000AAKS-00YGA0 500GB         | 1        | 1.96%   |
| WDC WD40EZAZ-00SF3B0 4TB            | 1        | 1.96%   |
| WDC WD3200BUCT-63TWBY0 320GB        | 1        | 1.96%   |
| WDC WD30EZRX-00D8PB0 3TB            | 1        | 1.96%   |
| WDC WD20EURX-61T0FY0 2TB            | 1        | 1.96%   |
| WDC WD10EZEX-60M2NA0 1TB            | 1        | 1.96%   |
| WDC WD10EZEX-21M2NA0 1TB            | 1        | 1.96%   |
| WDC WD10EZEX-08M2NA0 1TB            | 1        | 1.96%   |
| WDC WD10EZEX-00KUWA0 1TB            | 1        | 1.96%   |
| WDC WD10EURX-63FH1Y0 1TB            | 1        | 1.96%   |
| Unknown SD/MMC/MS PRO 16GB          | 1        | 1.96%   |
| Toshiba HDWD110 1TB                 | 1        | 1.96%   |
| Toshiba DT01ACA300 3TB              | 1        | 1.96%   |
| Silicon Motion NVMe SSD Drive 128GB | 1        | 1.96%   |
| Silicon Motion NVME SSD 128GB       | 1        | 1.96%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1        | 1.96%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1.96%   |
| Seagate ST4000DM004-2CV104 4TB      | 1        | 1.96%   |
| Seagate ST380811AS 80GB             | 1        | 1.96%   |
| Seagate ST31500341AS 1TB            | 1        | 1.96%   |
| Seagate ST1000VM002-1CT162 1TB      | 1        | 1.96%   |
| Seagate ST1000LM010-9YH146 1TB      | 1        | 1.96%   |
| Seagate ST1000DM010-2EP102 1TB      | 1        | 1.96%   |
| Seagate ST1000DM003-1CH162 1TB      | 1        | 1.96%   |
| SanDisk SSD PLUS 240GB              | 1        | 1.96%   |
| SanDisk SDSSDA120G 120GB            | 1        | 1.96%   |
| Sandisk NVMe SSD Drive 250GB        | 1        | 1.96%   |
| Samsung SSD 870 QVO 1TB             | 1        | 1.96%   |
| Samsung SSD 860 EVO 500GB           | 1        | 1.96%   |
| Samsung SSD 840 EVO 250GB           | 1        | 1.96%   |
| Samsung SSD 840 EVO 120GB           | 1        | 1.96%   |
| Samsung NVMe SSD Drive 500GB        | 1        | 1.96%   |
| Samsung HD502HJ 500GB               | 1        | 1.96%   |
| Samsung HD103UJ 1TB                 | 1        | 1.96%   |
| Micron/Crucial NVMe SSD Drive 1TB   | 1        | 1.96%   |
| Maxtor 6L250R0 256GB                | 1        | 1.96%   |
| Lexar 256GB SSD                     | 1        | 1.96%   |
| Kingston SV300S37A120G 120GB SSD    | 1        | 1.96%   |
| Kingston SA400S37240G 240GB SSD     | 1        | 1.96%   |
| Kingston SA400S37120G 120GB SSD     | 1        | 1.96%   |
| Kingston NVMe SSD Drive 480GB       | 1        | 1.96%   |
| KingFast 240GB                      | 1        | 1.96%   |
| JMicron Corp. 250GB                 | 1        | 1.96%   |
| HP MB2000GCWDA 2TB                  | 1        | 1.96%   |
| A-DATA SU750 256GB SSD              | 1        | 1.96%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 11       | 15     | 45.83%  |
| Seagate             | 7        | 9      | 29.17%  |
| Toshiba             | 2        | 2      | 8.33%   |
| Samsung Electronics | 2        | 2      | 8.33%   |
| Maxtor              | 1        | 1      | 4.17%   |
| Hewlett-Packard     | 1        | 1      | 4.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 5      | 33.33%  |
| Kingston            | 3        | 4      | 25%     |
| SanDisk             | 2        | 3      | 16.67%  |
| WDC                 | 1        | 1      | 8.33%   |
| Lexar               | 1        | 1      | 8.33%   |
| A-DATA Technology   | 1        | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 19       | 30     | 48.72%  |
| SSD     | 11       | 15     | 28.21%  |
| NVMe    | 6        | 11     | 15.38%  |
| Unknown | 3        | 3      | 7.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 24       | 47     | 77.42%  |
| NVMe | 6        | 11     | 19.35%  |
| SAS  | 1        | 1      | 3.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 15       | 22     | 46.88%  |
| 0.51-1.0   | 12       | 17     | 37.5%   |
| 3.01-4.0   | 2        | 2      | 6.25%   |
| 1.01-2.0   | 2        | 2      | 6.25%   |
| 2.01-3.0   | 1        | 2      | 3.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 7        | 25.93%  |
| 251-500        | 5        | 18.52%  |
| 501-1000       | 4        | 14.81%  |
| 1-20           | 3        | 11.11%  |
| More than 3000 | 2        | 7.41%   |
| 2001-3000      | 2        | 7.41%   |
| 51-100         | 2        | 7.41%   |
| 21-50          | 1        | 3.7%    |
| 1001-2000      | 1        | 3.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 14       | 50%     |
| 51-100         | 4        | 14.29%  |
| 21-50          | 3        | 10.71%  |
| 101-250        | 3        | 10.71%  |
| More than 3000 | 2        | 7.14%   |
| 251-500        | 1        | 3.57%   |
| 1001-2000      | 1        | 3.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| WDC WD10EZEX-21M2NA0 1TB | 1        | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 1        | 1      | 100%    |

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
| Detected | 25       | 56     | 89.29%  |
| Works    | 2        | 2      | 7.14%   |
| Malfunc  | 1        | 1      | 3.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 15       | 40.54%  |
| AMD                         | 12       | 32.43%  |
| Phison Electronics          | 2        | 5.41%   |
| VIA Technologies            | 1        | 2.7%    |
| Silicon Motion              | 1        | 2.7%    |
| Sandisk                     | 1        | 2.7%    |
| Samsung Electronics         | 1        | 2.7%    |
| Micron/Crucial Technology   | 1        | 2.7%    |
| Kingston Technology Company | 1        | 2.7%    |
| JMicron Technology          | 1        | 2.7%    |
| ASMedia Technology          | 1        | 2.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 6        | 13.33%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 6.67%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 6.67%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 4.44%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 4.44%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 4.44%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 4.44%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 4.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 4.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 4.44%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 4.44%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 2.22%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 2.22%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 2.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 2.22%   |
| Micron/Crucial NVMe Controller                                                          | 1        | 2.22%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 1        | 2.22%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 2.22%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 2.22%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 2.22%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 2.22%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 1        | 2.22%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 2.22%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 2.22%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 2.22%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 1        | 2.22%   |
| AMD FCH SATA Controller D                                                               | 1        | 2.22%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 21       | 58.33%  |
| IDE  | 7        | 19.44%  |
| NVMe | 6        | 16.67%  |
| RAID | 2        | 5.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 15       | 55.56%  |
| AMD    | 12       | 44.44%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i3-8100 CPU @ 3.60GHz            | 2        | 7.41%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 7.41%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 3.7%    |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 3.7%    |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 3.7%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 3.7%    |
| Intel Core i5-4430 CPU @ 3.00GHz            | 1        | 3.7%    |
| Intel Core i5-2500S CPU @ 2.70GHz           | 1        | 3.7%    |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 3.7%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 3.7%    |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 3.7%    |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 3.7%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 1        | 3.7%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 1        | 3.7%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 1        | 3.7%    |
| AMD Ryzen 7 2700X Eight-Core Processor      | 1        | 3.7%    |
| AMD Ryzen 7 2700 Eight-Core Processor       | 1        | 3.7%    |
| AMD Ryzen 5 3600 6-Core Processor           | 1        | 3.7%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 1        | 3.7%    |
| AMD Phenom II X4 965 Processor              | 1        | 3.7%    |
| AMD FX-9590 Eight-Core Processor            | 1        | 3.7%    |
| AMD FX-8320E Eight-Core Processor           | 1        | 3.7%    |
| AMD FX-6350 Six-Core Processor              | 1        | 3.7%    |
| AMD A6-5400K APU with Radeon HD Graphics    | 1        | 3.7%    |
| AMD A6-5400B APU with Radeon HD Graphics    | 1        | 3.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i3           | 6        | 22.22%  |
| Intel Core i5           | 4        | 14.81%  |
| AMD Ryzen 7             | 3        | 11.11%  |
| AMD FX                  | 3        | 11.11%  |
| Intel Core i7           | 2        | 7.41%   |
| AMD A6                  | 2        | 7.41%   |
| Intel Pentium Dual-Core | 1        | 3.7%    |
| Intel Pentium Dual      | 1        | 3.7%    |
| Intel Core 2 Quad       | 1        | 3.7%    |
| AMD Ryzen 9             | 1        | 3.7%    |
| AMD Ryzen 5             | 1        | 3.7%    |
| AMD Ryzen 3             | 1        | 3.7%    |
| AMD Phenom II X4        | 1        | 3.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 13       | 48.15%  |
| 2      | 6        | 22.22%  |
| 8      | 3        | 11.11%  |
| 1      | 2        | 7.41%   |
| 12     | 1        | 3.7%    |
| 6      | 1        | 3.7%    |
| 3      | 1        | 3.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 27       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 16       | 59.26%  |
| 1      | 11       | 40.74%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 27       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 4        | 14.81%  |
| 0x206a7    | 4        | 14.81%  |
| 0x06000852 | 3        | 11.11%  |
| 0x906eb    | 2        | 7.41%   |
| 0x08701021 | 2        | 7.41%   |
| 0x0800820d | 2        | 7.41%   |
| 0x06001119 | 2        | 7.41%   |
| Unknown    | 2        | 7.41%   |
| 0x6fd      | 1        | 3.7%    |
| 0x6fb      | 1        | 3.7%    |
| 0x1067a    | 1        | 3.7%    |
| 0x08701013 | 1        | 3.7%    |
| 0x08101016 | 1        | 3.7%    |
| 0x010000c8 | 1        | 3.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| SandyBridge | 5        | 18.52%  |
| Piledriver  | 5        | 18.52%  |
| Haswell     | 4        | 14.81%  |
| Zen 2       | 3        | 11.11%  |
| KabyLake    | 3        | 11.11%  |
| Zen+        | 2        | 7.41%   |
| Core        | 2        | 7.41%   |
| Zen         | 1        | 3.7%    |
| Penryn      | 1        | 3.7%    |
| K10         | 1        | 3.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 11       | 39.29%  |
| Intel  | 10       | 35.71%  |
| AMD    | 7        | 25%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 10.34%  |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 6.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 6.9%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 6.9%    |
| AMD Trinity 2 [Radeon HD 7540D]                                             | 2        | 6.9%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 6.9%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 3.45%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 3.45%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 3.45%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 3.45%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 3.45%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 3.45%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 3.45%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 3.45%   |
| Nvidia GA106 [GeForce RTX 3060]                                             | 1        | 3.45%   |
| Intel HD Graphics 630                                                       | 1        | 3.45%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 1        | 3.45%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 3.45%   |
| AMD RS880 [Radeon HD 4250]                                                  | 1        | 3.45%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 3.45%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 3.45%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 3.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 11       | 39.29%  |
| 1 x Intel  | 9        | 32.14%  |
| 1 x AMD    | 7        | 25%     |
| 2 x AMD    | 1        | 3.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 19       | 70.37%  |
| Proprietary | 8        | 29.63%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10       | 37.04%  |
| 1.01-2.0   | 5        | 18.52%  |
| 5.01-6.0   | 3        | 11.11%  |
| 0.01-0.5   | 3        | 11.11%  |
| 3.01-4.0   | 2        | 7.41%   |
| 0.51-1.0   | 2        | 7.41%   |
| 7.01-8.0   | 1        | 3.7%    |
| 2.01-3.0   | 1        | 3.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 5        | 17.86%  |
| Philips             | 3        | 10.71%  |
| Vizio               | 2        | 7.14%   |
| Lenovo              | 2        | 7.14%   |
| Hewlett-Packard     | 2        | 7.14%   |
| Goldstar            | 2        | 7.14%   |
| AOC                 | 2        | 7.14%   |
| Acer                | 2        | 7.14%   |
| ViewSonic           | 1        | 3.57%   |
| Unknown             | 1        | 3.57%   |
| Sceptre Tech        | 1        | 3.57%   |
| LG Electronics      | 1        | 3.57%   |
| Gigabyte Technology | 1        | 3.57%   |
| Gateway             | 1        | 3.57%   |
| Dell                | 1        | 3.57%   |
| AUS                 | 1        | 3.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Vizio VO37LFHDTV10A VIZ0043 1920x1080 820x460mm 37.0-inch              | 1        | 3.45%   |
| Vizio E241i-A1 VIZ1005 1920x1080 521x293mm 23.5-inch                   | 1        | 3.45%   |
| ViewSonic LCD Monitor VA2256 Series 1920x1080                          | 1        | 3.45%   |
| Unknown LCD Monitor LHC TE-3125 1920x1080                              | 1        | 3.45%   |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                 | 1        | 3.45%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch      | 1        | 3.45%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch      | 1        | 3.45%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 1        | 3.45%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 1020x570mm 46.0-inch | 1        | 3.45%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1190x340mm 48.7-inch     | 1        | 3.45%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                | 1        | 3.45%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1        | 3.45%   |
| Philips LCD Monitor 240B 1920x1200                                     | 1        | 3.45%   |
| LG Electronics LCD Monitor EW224 1920x1080                             | 1        | 3.45%   |
| Lenovo LEN T23i-10 LEN61AB 1920x1080 509x286mm 23.0-inch               | 1        | 3.45%   |
| Lenovo D22-20 LEN66AD 1920x1080 477x268mm 21.5-inch                    | 1        | 3.45%   |
| Hewlett-Packard w17e HWP26E0 1440x900 408x255mm 18.9-inch              | 1        | 3.45%   |
| Hewlett-Packard Compaq WF1907 HWP26A5 1440x900 408x255mm 18.9-inch     | 1        | 3.45%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch            | 1        | 3.45%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                    | 1        | 3.45%   |
| Goldstar LCD Monitor GSM580C 1680x1050 510x290mm 23.1-inch             | 1        | 3.45%   |
| Gigabyte Technology G34WQC GBT3400 3440x1440 797x334mm 34.0-inch       | 1        | 3.45%   |
| Gateway VX930 GWY232D 1600x1200 350x262mm 17.2-inch                    | 1        | 3.45%   |
| Dell S2715H DEL40BA 1920x1080 598x336mm 27.0-inch                      | 1        | 3.45%   |
| AUS LCD Monitor ASUS VP247 1920x1080                                   | 1        | 3.45%   |
| AOC LCD Monitor 2269W 1920x1080                                        | 1        | 3.45%   |
| AOC AG323FWG3R3 AOC3230 1920x1080 698x393mm 31.5-inch                  | 1        | 3.45%   |
| Acer LCD Monitor S271HL 1920x1080                                      | 1        | 3.45%   |
| Acer K202HQL ACR03E0 1600x900 432x240mm 19.5-inch                      | 1        | 3.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 18       | 66.67%  |
| 3840x2160 (4K)     | 2        | 7.41%   |
| 3840x1080          | 1        | 3.7%    |
| 3440x1440          | 1        | 3.7%    |
| 1920x1200 (WUXGA)  | 1        | 3.7%    |
| 1680x1050 (WSXGA+) | 1        | 3.7%    |
| 1600x900 (HD+)     | 1        | 3.7%    |
| 1600x1200          | 1        | 3.7%    |
| 1440x900 (WXGA+)   | 1        | 3.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 7        | 25%     |
| 31      | 4        | 14.29%  |
| 23      | 3        | 10.71%  |
| 48      | 2        | 7.14%   |
| 27      | 2        | 7.14%   |
| 21      | 2        | 7.14%   |
| 46      | 1        | 3.57%   |
| 41      | 1        | 3.57%   |
| 34      | 1        | 3.57%   |
| 24      | 1        | 3.57%   |
| 22      | 1        | 3.57%   |
| 19      | 1        | 3.57%   |
| 18      | 1        | 3.57%   |
| 17      | 1        | 3.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 7        | 25.93%  |
| 501-600     | 5        | 18.52%  |
| 401-500     | 5        | 18.52%  |
| 601-700     | 4        | 14.81%  |
| 1001-1500   | 3        | 11.11%  |
| 701-800     | 1        | 3.7%    |
| 301-350     | 1        | 3.7%    |
| 901-1000    | 1        | 3.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 14       | 53.85%  |
| Unknown | 7        | 26.92%  |
| 16/10   | 2        | 7.69%   |
| 4/3     | 1        | 3.85%   |
| 32/9    | 1        | 3.85%   |
| 21/9    | 1        | 3.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 7        | 25%     |
| 201-250        | 6        | 21.43%  |
| 351-500        | 5        | 17.86%  |
| 151-200        | 3        | 10.71%  |
| 501-1000       | 3        | 10.71%  |
| 301-350        | 2        | 7.14%   |
| More than 1000 | 1        | 3.57%   |
| 141-150        | 1        | 3.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 13       | 46.43%  |
| Unknown | 7        | 25%     |
| 101-120 | 4        | 14.29%  |
| 1-50    | 2        | 7.14%   |
| 121-160 | 2        | 7.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 25       | 92.59%  |
| 2     | 2        | 7.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 20       | 51.28%  |
| Intel                 | 8        | 20.51%  |
| Qualcomm Atheros      | 5        | 12.82%  |
| TP-Link               | 1        | 2.56%   |
| Samsung Electronics   | 1        | 2.56%   |
| Ralink Technology     | 1        | 2.56%   |
| Ralink                | 1        | 2.56%   |
| NetGear               | 1        | 2.56%   |
| D-Link System         | 1        | 2.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16       | 39.02%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 4.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 4.88%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 2.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 2.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 2.44%   |
| Realtek 802.11ac NIC                                              | 1        | 2.44%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 2.44%   |
| Ralink RT2600 802.11 MIMO                                         | 1        | 2.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 2.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 2.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 2.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 2.44%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1        | 2.44%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 1        | 2.44%   |
| Intel Wireless-AC 9260                                            | 1        | 2.44%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 2.44%   |
| Intel I211 Gigabit Network Connection                             | 1        | 2.44%   |
| Intel I210 Gigabit Network Connection                             | 1        | 2.44%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 2.44%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 2.44%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 2.44%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1        | 2.44%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 2.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 3        | 27.27%  |
| Realtek Semiconductor | 2        | 18.18%  |
| Qualcomm Atheros      | 2        | 18.18%  |
| TP-Link               | 1        | 9.09%   |
| Ralink Technology     | 1        | 9.09%   |
| Ralink                | 1        | 9.09%   |
| NetGear               | 1        | 9.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| TP-Link Archer T3U [Realtek RTL8812BU]                      | 1        | 9.09%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter         | 1        | 9.09%   |
| Realtek 802.11ac NIC                                        | 1        | 9.09%   |
| Ralink MT7601U Wireless Adapter                             | 1        | 9.09%   |
| Ralink RT2600 802.11 MIMO                                   | 1        | 9.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter            | 1        | 9.09%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter            | 1        | 9.09%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU] | 1        | 9.09%   |
| Intel Wireless-AC 9260                                      | 1        | 9.09%   |
| Intel Wi-Fi 6 AX200                                         | 1        | 9.09%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth             | 1        | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 18       | 62.07%  |
| Intel                 | 6        | 20.69%  |
| Qualcomm Atheros      | 3        | 10.34%  |
| Samsung Electronics   | 1        | 3.45%   |
| D-Link System         | 1        | 3.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16       | 53.33%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 6.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 6.67%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 3.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 3.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 3.33%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1        | 3.33%   |
| Intel I211 Gigabit Network Connection                             | 1        | 3.33%   |
| Intel I210 Gigabit Network Connection                             | 1        | 3.33%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 3.33%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 3.33%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 3.33%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 3.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 27       | 72.97%  |
| WiFi     | 10       | 27.03%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 27       | 77.14%  |
| WiFi     | 8        | 22.86%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 20       | 74.07%  |
| 2     | 6        | 22.22%  |
| 3     | 1        | 3.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 16       | 57.14%  |
| Yes  | 12       | 42.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 3        | 42.86%  |
| Cambridge Silicon Radio         | 2        | 28.57%  |
| Qualcomm Atheros Communications | 1        | 14.29%  |
| Lite-On Technology              | 1        | 14.29%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 28.57%  |
| Qualcomm Atheros Bluetooth                          | 1        | 14.29%  |
| Lite-On Bluetooth Device                            | 1        | 14.29%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 14.29%  |
| Intel Bluetooth wireless interface                  | 1        | 14.29%  |
| Intel AX200 Bluetooth                               | 1        | 14.29%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor        | Desktops | Percent |
|---------------|----------|---------|
| Intel         | 15       | 35.71%  |
| Nvidia        | 11       | 26.19%  |
| AMD           | 11       | 26.19%  |
| Creative Labs | 2        | 4.76%   |
| Numark        | 1        | 2.38%   |
| Klipsch Audio | 1        | 2.38%   |
| JMTek         | 1        | 2.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5        | 9.8%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 7.84%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 5.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 5.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 5.88%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 3.92%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 3.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2        | 3.92%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 3.92%   |
| AMD FCH Azalia Controller                                                  | 2        | 3.92%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 3.92%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 3.92%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 1.96%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 1.96%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.96%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 1.96%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 1.96%   |
| Nvidia Audio device                                                        | 1        | 1.96%   |
| Numark MixTrack Pro                                                        | 1        | 1.96%   |
| Klipsch Audio Klipsch KG-200 Headphones                                    | 1        | 1.96%   |
| JMTek USB PnP Audio Device                                                 | 1        | 1.96%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 1.96%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 1.96%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 1        | 1.96%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                 | 1        | 1.96%   |
| AMD Trinity HDMI Audio Controller                                          | 1        | 1.96%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1        | 1.96%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 1        | 1.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 1.96%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 1        | 1.96%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 1.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2        | 66.67%  |
| Team    | 1        | 33.33%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM TM44D18UD04MU-NUK 4096MB DIMM DDR4 2400MT/s | 1        | 20%     |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s               | 1        | 20%     |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 1        | 20%     |
| Unknown RAM 04S2400CL17A 4096MB DIMM DDR4 2400MT/s      | 1        | 20%     |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s      | 1        | 20%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 2        | 66.67%  |
| Unknown | 1        | 33.33%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 3        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 8192 | 2        | 50%     |
| 4096 | 2        | 50%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2667  | 1        | 33.33%  |
| 2400  | 1        | 33.33%  |
| 1333  | 1        | 33.33%  |

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


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Microsoft        | 1        | 50%     |
| Jieli Technology | 1        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Microsoft MicrosoftÂ LifeCam Cinema | 1        | 50%     |
| Jieli USB PHY 2.0                    | 1        | 50%     |

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
| 0     | 24       | 88.89%  |
| 1     | 3        | 11.11%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type         | Desktops | Percent |
|--------------|----------|---------|
| Net/wireless | 3        | 100%    |

