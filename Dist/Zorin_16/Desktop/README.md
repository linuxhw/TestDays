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
| Gigabyte | A320M-S2H-CF                | [6ed5f8c32b](https://linux-hardware.org/?probe=6ed5f8c32b) | Aug 27, 2021 |
| ASRock   | Z390 Phantom Gaming 4-IB    | [b01269fbc1](https://linux-hardware.org/?probe=b01269fbc1) | Aug 27, 2021 |
| Lenovo   | SHARKBAY SDK0E50510 WIN     | [51661e959e](https://linux-hardware.org/?probe=51661e959e) | Aug 26, 2021 |
| Lenovo   | SHARKBAY SDK0E50510 WIN     | [3a7eb89cd8](https://linux-hardware.org/?probe=3a7eb89cd8) | Aug 25, 2021 |
| HP       | 802E                        | [3ee51e8a56](https://linux-hardware.org/?probe=3ee51e8a56) | Aug 25, 2021 |
| ASUSTek  | P8Z77-V LX                  | [314859d762](https://linux-hardware.org/?probe=314859d762) | Aug 25, 2021 |
| ASUSTek  | P8Z77-V LX                  | [faaf8bc158](https://linux-hardware.org/?probe=faaf8bc158) | Aug 25, 2021 |
| Dell     | 088DT1 A01                  | [8620323354](https://linux-hardware.org/?probe=8620323354) | Aug 25, 2021 |
| Dell     | 0TP406                      | [72a3d9ac12](https://linux-hardware.org/?probe=72a3d9ac12) | Aug 25, 2021 |
| HP       | 2B4B                        | [4c5411522b](https://linux-hardware.org/?probe=4c5411522b) | Aug 25, 2021 |
| Gigabyte | B85M-D3H                    | [906a3e006c](https://linux-hardware.org/?probe=906a3e006c) | Aug 24, 2021 |
| Gigabyte | B85M-D3H                    | [9f369218ff](https://linux-hardware.org/?probe=9f369218ff) | Aug 24, 2021 |
| ASUSTek  | P8Z77-V LE                  | [a720e3326a](https://linux-hardware.org/?probe=a720e3326a) | Aug 23, 2021 |
| MSI      | B450M PRO-M2 MAX            | [e6f053c5be](https://linux-hardware.org/?probe=e6f053c5be) | Aug 22, 2021 |
| ASUSTek  | ROG STRIX Z490-E GAMING     | [15175b4f4f](https://linux-hardware.org/?probe=15175b4f4f) | Aug 22, 2021 |
| ASUSTek  | ROG STRIX Z490-E GAMING     | [02ccc1eb70](https://linux-hardware.org/?probe=02ccc1eb70) | Aug 22, 2021 |
| ASUSTek  | M5A97 R2.0                  | [372a125910](https://linux-hardware.org/?probe=372a125910) | Aug 22, 2021 |
| Lenovo   | Board                       | [b4e9579228](https://linux-hardware.org/?probe=b4e9579228) | Aug 21, 2021 |
| Lenovo   | Board                       | [12088eed17](https://linux-hardware.org/?probe=12088eed17) | Aug 21, 2021 |
| MSI      | B450M PRO-M2 MAX            | [68c6a2734b](https://linux-hardware.org/?probe=68c6a2734b) | Aug 21, 2021 |
| Intel    | DB75EN AAG39650-303         | [4bbb9f60f9](https://linux-hardware.org/?probe=4bbb9f60f9) | Aug 20, 2021 |
| Fujitsu  | D3220-A1 S26361-D3220-A1    | [63cbb9e7fd](https://linux-hardware.org/?probe=63cbb9e7fd) | Aug 19, 2021 |
| MSI      | Z97 XPOWER AC               | [c68138439d](https://linux-hardware.org/?probe=c68138439d) | Aug 19, 2021 |
| ASUSTek  | M5A78L-M/USB3               | [d78450d852](https://linux-hardware.org/?probe=d78450d852) | Aug 19, 2021 |
| Acer     | Aspire XC-605G              | [8bb6f8ef72](https://linux-hardware.org/?probe=8bb6f8ef72) | Aug 18, 2021 |
| ASUSTek  | B85M-G R2.0                 | [daf6bf889f](https://linux-hardware.org/?probe=daf6bf889f) | Aug 18, 2021 |
| MSI      | Z270-A PRO                  | [3be5b7f90e](https://linux-hardware.org/?probe=3be5b7f90e) | Aug 18, 2021 |
| Gigabyte | B550M DS3H                  | [4b687b4c17](https://linux-hardware.org/?probe=4b687b4c17) | Aug 16, 2021 |
| ASUSTek  | Z97-C                       | [97b71d18de](https://linux-hardware.org/?probe=97b71d18de) | Aug 16, 2021 |
| ASUSTek  | Z97-C                       | [06872ddde7](https://linux-hardware.org/?probe=06872ddde7) | Aug 16, 2021 |
| ASUSTek  | Z97-C                       | [a1f448c1f6](https://linux-hardware.org/?probe=a1f448c1f6) | Aug 15, 2021 |
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
| 5.11.0-27-generic | 22       | 43.14%  |
| 5.8.0-53-generic  | 7        | 13.73%  |
| 5.8.0-55-generic  | 5        | 9.8%    |
| 5.8.0-50-generic  | 5        | 9.8%    |
| 5.8.0-59-generic  | 3        | 5.88%   |
| 5.8.0-49-generic  | 3        | 5.88%   |
| 5.11.0-25-generic | 3        | 5.88%   |
| 5.8.0-63-generic  | 2        | 3.92%   |
| 5.8.0-45-generic  | 1        | 1.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.8.0   | 25       | 50%     |
| 5.11.0  | 25       | 50%     |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.8     | 25       | 50%     |
| 5.11    | 25       | 50%     |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 49       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| GNOME    | 48       | 96%     |
| XFCE     | 1        | 2%      |
| Cinnamon | 1        | 2%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 49       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 47       | 95.92%  |
| TDM     | 1        | 2.04%   |
| GDM     | 1        | 2.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 22       | 44.9%   |
| de_DE | 7        | 14.29%  |
| pt_BR | 6        | 12.24%  |
| es_ES | 3        | 6.12%   |
| pl_PL | 2        | 4.08%   |
| en_GB | 2        | 4.08%   |
| nl_NL | 1        | 2.04%   |
| nl_BE | 1        | 2.04%   |
| hu_HU | 1        | 2.04%   |
| es_PE | 1        | 2.04%   |
| es_MX | 1        | 2.04%   |
| en_ZA | 1        | 2.04%   |
| en_SG | 1        | 2.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 28       | 57.14%  |
| BIOS | 21       | 42.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 47       | 95.92%  |
| Overlay | 2        | 4.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 47       | 95.92%  |
| MBR     | 1        | 2.04%   |
| GPT     | 1        | 2.04%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 94%     |
| Yes       | 3        | 6%      |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 42       | 85.71%  |
| Yes       | 7        | 14.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 17       | 34.69%  |
| Gigabyte Technology | 8        | 16.33%  |
| Lenovo              | 5        | 10.2%   |
| MSI                 | 4        | 8.16%   |
| Hewlett-Packard     | 4        | 8.16%   |
| Dell                | 4        | 8.16%   |
| ASRock              | 2        | 4.08%   |
| Pegatron            | 1        | 2.04%   |
| Intel               | 1        | 2.04%   |
| Fujitsu             | 1        | 2.04%   |
| Biostar             | 1        | 2.04%   |
| Acer                | 1        | 2.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| ASUS All Series                         | 3        | 6.12%   |
| Dell OptiPlex 990                       | 2        | 4.08%   |
| ASUS M5A78L-M/USB3                      | 2        | 4.08%   |
| Pegatron NE502AV-ABA a6750t             | 1        | 2.04%   |
| MSI Pro 3515 Series                     | 1        | 2.04%   |
| MSI MS-7B84                             | 1        | 2.04%   |
| MSI MS-7A71                             | 1        | 2.04%   |
| MSI MS-7914                             | 1        | 2.04%   |
| Lenovo ThinkCentre M83 MT-M 10AJ-0003MB | 1        | 2.04%   |
| Lenovo ThinkCentre M78 10BTA00ELM       | 1        | 2.04%   |
| Lenovo SHARKBAY SDK0E50510 WIN          | 1        | 2.04%   |
| Lenovo IdeaCentre 510S-08IKL 90GB004RUS | 1        | 2.04%   |
| Lenovo Board                            | 1        | 2.04%   |
| Intel DB75EN AAG39650-303               | 1        | 2.04%   |
| HP Z240 SFF Workstation                 | 1        | 2.04%   |
| HP Z1 Entry Tower G5                    | 1        | 2.04%   |
| HP 870-158ng                            | 1        | 2.04%   |
| HP 290 G2 MT Business PC                | 1        | 2.04%   |
| Gigabyte Komputer OPTIMUS               | 1        | 2.04%   |
| Gigabyte H61M-USB3-B3                   | 1        | 2.04%   |
| Gigabyte B85M-D3H                       | 1        | 2.04%   |
| Gigabyte B85-HD3                        | 1        | 2.04%   |
| Gigabyte B550M H                        | 1        | 2.04%   |
| Gigabyte B550M DS3H                     | 1        | 2.04%   |
| Gigabyte B450 AORUS ELITE               | 1        | 2.04%   |
| Gigabyte A320M-S2H                      | 1        | 2.04%   |
| Fujitsu ESPRIMO P520                    | 1        | 2.04%   |
| Dell XPS420                             | 1        | 2.04%   |
| Dell Inspiron 3847                      | 1        | 2.04%   |
| Biostar A320MH                          | 1        | 2.04%   |
| ASUS UNLOCK INSTALL                     | 1        | 2.04%   |
| ASUS ROG STRIX Z490-E GAMING            | 1        | 2.04%   |
| ASUS PRIME X570-PRO                     | 1        | 2.04%   |
| ASUS PRIME X570-P                       | 1        | 2.04%   |
| ASUS PRIME B450M-GAMING/BR              | 1        | 2.04%   |
| ASUS P8Z77-V LX                         | 1        | 2.04%   |
| ASUS P8Z77-V LE                         | 1        | 2.04%   |
| ASUS P8H61-M LE                         | 1        | 2.04%   |
| ASUS P5K                                | 1        | 2.04%   |
| ASUS M5A97 R2.0                         | 1        | 2.04%   |
| ASUS M5A97 LE R2.0                      | 1        | 2.04%   |
| ASUS M4A88TD-V EVO/USB3                 | 1        | 2.04%   |
| ASRock Z390 Phantom Gaming 4-IB         | 1        | 2.04%   |
| ASRock 990FX Extreme6                   | 1        | 2.04%   |
| Acer Aspire XC-605G                     | 1        | 2.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS PRIME            | 3        | 6.12%   |
| ASUS All              | 3        | 6.12%   |
| Lenovo ThinkCentre    | 2        | 4.08%   |
| Gigabyte B550M        | 2        | 4.08%   |
| Dell OptiPlex         | 2        | 4.08%   |
| ASUS P8Z77-V          | 2        | 4.08%   |
| ASUS M5A97            | 2        | 4.08%   |
| ASUS M5A78L-M         | 2        | 4.08%   |
| Pegatron NE502AV-ABA  | 1        | 2.04%   |
| MSI Pro               | 1        | 2.04%   |
| MSI MS-7B84           | 1        | 2.04%   |
| MSI MS-7A71           | 1        | 2.04%   |
| MSI MS-7914           | 1        | 2.04%   |
| Lenovo SHARKBAY       | 1        | 2.04%   |
| Lenovo IdeaCentre     | 1        | 2.04%   |
| Lenovo Board          | 1        | 2.04%   |
| Intel DB75EN          | 1        | 2.04%   |
| HP Z240               | 1        | 2.04%   |
| HP Z1                 | 1        | 2.04%   |
| HP 870-158ng          | 1        | 2.04%   |
| HP 290                | 1        | 2.04%   |
| Gigabyte Komputer     | 1        | 2.04%   |
| Gigabyte H61M-USB3-B3 | 1        | 2.04%   |
| Gigabyte B85M-D3H     | 1        | 2.04%   |
| Gigabyte B85-HD3      | 1        | 2.04%   |
| Gigabyte B450         | 1        | 2.04%   |
| Gigabyte A320M-S2H    | 1        | 2.04%   |
| Fujitsu ESPRIMO       | 1        | 2.04%   |
| Dell XPS420           | 1        | 2.04%   |
| Dell Inspiron         | 1        | 2.04%   |
| Biostar A320MH        | 1        | 2.04%   |
| ASUS UNLOCK           | 1        | 2.04%   |
| ASUS ROG              | 1        | 2.04%   |
| ASUS P8H61-M          | 1        | 2.04%   |
| ASUS P5K              | 1        | 2.04%   |
| ASUS M4A88TD-V        | 1        | 2.04%   |
| ASRock Z390           | 1        | 2.04%   |
| ASRock 990FX          | 1        | 2.04%   |
| Acer Aspire           | 1        | 2.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2014 | 8        | 16.33%  |
| 2021 | 6        | 12.24%  |
| 2020 | 6        | 12.24%  |
| 2018 | 5        | 10.2%   |
| 2015 | 5        | 10.2%   |
| 2019 | 4        | 8.16%   |
| 2016 | 3        | 6.12%   |
| 2012 | 3        | 6.12%   |
| 2013 | 2        | 4.08%   |
| 2009 | 2        | 4.08%   |
| 2017 | 1        | 2.04%   |
| 2011 | 1        | 2.04%   |
| 2010 | 1        | 2.04%   |
| 2008 | 1        | 2.04%   |
| 2007 | 1        | 2.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 49       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 45       | 91.84%  |
| Enabled  | 4        | 8.16%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 49       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 16       | 31.37%  |
| 16.01-24.0  | 13       | 25.49%  |
| 4.01-8.0    | 8        | 15.69%  |
| 32.01-64.0  | 8        | 15.69%  |
| 3.01-4.0    | 4        | 7.84%   |
| 64.01-256.0 | 1        | 1.96%   |
| 1.01-2.0    | 1        | 1.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 27       | 52.94%  |
| 2.01-3.0 | 15       | 29.41%  |
| 4.01-8.0 | 4        | 7.84%   |
| 3.01-4.0 | 4        | 7.84%   |
| 0.51-1.0 | 1        | 1.96%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 15       | 30.61%  |
| 2      | 14       | 28.57%  |
| 3      | 8        | 16.33%  |
| 4      | 7        | 14.29%  |
| 5      | 3        | 6.12%   |
| 8      | 1        | 2.04%   |
| 0      | 1        | 2.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 32       | 65.31%  |
| No        | 17       | 34.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 49       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 59.18%  |
| Yes       | 20       | 40.82%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 69.39%  |
| Yes       | 15       | 30.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 16       | 32.65%  |
| Germany      | 8        | 16.33%  |
| Brazil       | 6        | 12.24%  |
| Spain        | 3        | 6.12%   |
| UK           | 2        | 4.08%   |
| Poland       | 2        | 4.08%   |
| Taiwan       | 1        | 2.04%   |
| Switzerland  | 1        | 2.04%   |
| South Africa | 1        | 2.04%   |
| Peru         | 1        | 2.04%   |
| Netherlands  | 1        | 2.04%   |
| Mexico       | 1        | 2.04%   |
| Malaysia     | 1        | 2.04%   |
| Hungary      | 1        | 2.04%   |
| Denmark      | 1        | 2.04%   |
| Canada       | 1        | 2.04%   |
| Belgium      | 1        | 2.04%   |
| Australia    | 1        | 2.04%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Zurich                 | 1        | 2.04%   |
| Xalapa                 | 1        | 2.04%   |
| Vespasiano             | 1        | 2.04%   |
| Vancouver              | 1        | 2.04%   |
| Trujillo               | 1        | 2.04%   |
| São Bernardo do Campo | 1        | 2.04%   |
| Szombathely            | 1        | 2.04%   |
| Santa Cruz de Tenerife | 1        | 2.04%   |
| Sacramento             | 1        | 2.04%   |
| Rio de Janeiro         | 1        | 2.04%   |
| Porto Seguro           | 1        | 2.04%   |
| Pascoag                | 1        | 2.04%   |
| Palm Coast             | 1        | 2.04%   |
| Oscoda                 | 1        | 2.04%   |
| Oak Creek              | 1        | 2.04%   |
| Niter??i               | 1        | 2.04%   |
| Miami                  | 1        | 2.04%   |
| Mentor                 | 1        | 2.04%   |
| Melbourne              | 1        | 2.04%   |
| Ludwigsburg            | 1        | 2.04%   |
| Laziska Gorne          | 1        | 2.04%   |
| Kuala Lumpur           | 1        | 2.04%   |
| Johannesburg           | 1        | 2.04%   |
| Idaho Falls            | 1        | 2.04%   |
| Helensburgh            | 1        | 2.04%   |
| Hamburg                | 1        | 2.04%   |
| Griesheim              | 1        | 2.04%   |
| Ghent                  | 1        | 2.04%   |
| Gdynia                 | 1        | 2.04%   |
| Fort Worth             | 1        | 2.04%   |
| Emmendingen            | 1        | 2.04%   |
| Duluth                 | 1        | 2.04%   |
| Delaware               | 1        | 2.04%   |
| Copenhagen             | 1        | 2.04%   |
| Contagem               | 1        | 2.04%   |
| Cologne                | 1        | 2.04%   |
| Chipiona               | 1        | 2.04%   |
| Chiayi City            | 1        | 2.04%   |
| Charlottesville        | 1        | 2.04%   |
| Carlsbad               | 1        | 2.04%   |
| Carlisle               | 1        | 2.04%   |
| Borna                  | 1        | 2.04%   |
| Bedum                  | 1        | 2.04%   |
| Beacon                 | 1        | 2.04%   |
| Baltimore              | 1        | 2.04%   |
| Bad Mergentheim        | 1        | 2.04%   |
| Augsburg               | 1        | 2.04%   |
| Arlington              | 1        | 2.04%   |
| Aldaia                 | 1        | 2.04%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 21       | 30     | 21.65%  |
| WDC                       | 20       | 28     | 20.62%  |
| Samsung Electronics       | 11       | 16     | 11.34%  |
| Kingston                  | 10       | 11     | 10.31%  |
| SanDisk                   | 8        | 11     | 8.25%   |
| Toshiba                   | 4        | 4      | 4.12%   |
| Unknown                   | 2        | 3      | 2.06%   |
| Silicon Motion            | 2        | 4      | 2.06%   |
| Phison                    | 2        | 2      | 2.06%   |
| Micron/Crucial Technology | 2        | 2      | 2.06%   |
| XPG                       | 1        | 1      | 1.03%   |
| Patriot                   | 1        | 1      | 1.03%   |
| OCZ                       | 1        | 1      | 1.03%   |
| Maxtor                    | 1        | 1      | 1.03%   |
| Lexar                     | 1        | 1      | 1.03%   |
| KIOXIA-EXCERIA            | 1        | 1      | 1.03%   |
| KingFast                  | 1        | 1      | 1.03%   |
| JMicron                   | 1        | 1      | 1.03%   |
| Intenso                   | 1        | 1      | 1.03%   |
| Hitachi                   | 1        | 2      | 1.03%   |
| Hewlett-Packard           | 1        | 1      | 1.03%   |
| Crucial                   | 1        | 2      | 1.03%   |
| China                     | 1        | 1      | 1.03%   |
| Apacer                    | 1        | 1      | 1.03%   |
| A-DATA Technology         | 1        | 1      | 1.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB                    | 3        | 2.59%   |
| Seagate ST500DM002-1BD142 500GB             | 3        | 2.59%   |
| Seagate ST1000DM010-2EP102 1TB              | 3        | 2.59%   |
| Kingston SA400S37240G 240GB SSD             | 3        | 2.59%   |
| WDC WD10EZEX-60M2NA0 1TB                    | 2        | 1.72%   |
| Unknown SD/MMC/MS PRO 64GB                  | 2        | 1.72%   |
| Silicon Motion NVMe SSD Drive 128GB         | 2        | 1.72%   |
| Seagate ST500LM012 HN-M500MBB 500GB         | 2        | 1.72%   |
| Seagate ST2000DM001-9YN164 2TB              | 2        | 1.72%   |
| Samsung NVMe SSD Drive 500GB                | 2        | 1.72%   |
| Phison NVMe SSD Drive 1TB                   | 2        | 1.72%   |
| Kingston SV300S37A240G 240GB SSD            | 2        | 1.72%   |
| Kingston SV300S37A120G 120GB SSD            | 2        | 1.72%   |
| Kingston SA400S37120G 120GB SSD             | 2        | 1.72%   |
| XPG NVMe SSD Drive 1024GB                   | 1        | 0.86%   |
| WDC WDS250G2B0A-00SM50 250GB SSD            | 1        | 0.86%   |
| WDC WDS240G2G0A-00JH30 240GB SSD            | 1        | 0.86%   |
| WDC WD7500AARS-00Y5B1 752GB                 | 1        | 0.86%   |
| WDC WD5000AAKX-08U6AA0 500GB                | 1        | 0.86%   |
| WDC WD5000AAKS-00YGA0 500GB                 | 1        | 0.86%   |
| WDC WD5000AADS-00S9B0 500GB                 | 1        | 0.86%   |
| WDC WD40EZAZ-00SF3B0 4TB                    | 1        | 0.86%   |
| WDC WD3200BUCT-63TWBY0 320GB                | 1        | 0.86%   |
| WDC WD30EZRX-00D8PB0 3TB                    | 1        | 0.86%   |
| WDC WD20EZRX-00D8PB0 2TB                    | 1        | 0.86%   |
| WDC WD20EURX-61T0FY0 2TB                    | 1        | 0.86%   |
| WDC WD20EFRX-68EUZN0 2TB                    | 1        | 0.86%   |
| WDC WD1600AAJS-75M0A0 160GB                 | 1        | 0.86%   |
| WDC WD1600AAJS-22PSA0 160GB                 | 1        | 0.86%   |
| WDC WD10EZEX-75M2NA0 1TB                    | 1        | 0.86%   |
| WDC WD10EZEX-21M2NA0 1TB                    | 1        | 0.86%   |
| WDC WD10EZEX-08M2NA0 1TB                    | 1        | 0.86%   |
| WDC WD10EZEX-00KUWA0 1TB                    | 1        | 0.86%   |
| WDC WD10EURX-63FH1Y0 1TB                    | 1        | 0.86%   |
| WDC WD1002FAEX-00Y9A0 1TB                   | 1        | 0.86%   |
| Toshiba MQ01ABD032V -63 320GB               | 1        | 0.86%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD         | 1        | 0.86%   |
| Toshiba HDWD110 1TB                         | 1        | 0.86%   |
| Toshiba DT01ACA300 3TB                      | 1        | 0.86%   |
| Silicon Motion NVME SSD 128GB               | 1        | 0.86%   |
| Seagate ST6000DM003-2CY186 6TB              | 1        | 0.86%   |
| Seagate ST4000DM004-2CV104 4TB              | 1        | 0.86%   |
| Seagate ST4000DM000-1F2168 4TB              | 1        | 0.86%   |
| Seagate ST380811AS 80GB                     | 1        | 0.86%   |
| Seagate ST3500620AS 500GB                   | 1        | 0.86%   |
| Seagate ST3500418AS 500GB                   | 1        | 0.86%   |
| Seagate ST3320820AS 320GB                   | 1        | 0.86%   |
| Seagate ST3160815AS 160GB                   | 1        | 0.86%   |
| Seagate ST31500341AS 1TB                    | 1        | 0.86%   |
| Seagate ST2000LM015-2E8174 2TB              | 1        | 0.86%   |
| Seagate ST2000DM008-2FR102 2TB              | 1        | 0.86%   |
| Seagate ST2000DM001-1CH164 2TB              | 1        | 0.86%   |
| Seagate ST1000VM002-1CT162 1TB              | 1        | 0.86%   |
| Seagate ST1000LM010-9YH146 1TB              | 1        | 0.86%   |
| Seagate ST1000DM003-9YN162 1TB              | 1        | 0.86%   |
| Seagate ST1000DM003-1SB102 1TB              | 1        | 0.86%   |
| Seagate ST1000DM003-1ER162 1TB              | 1        | 0.86%   |
| Seagate ST1000DM003-1CH162 1TB              | 1        | 0.86%   |
| Seagate M3 2TB                              | 1        | 0.86%   |
| Seagate BarraCuda 120 SSD ZA1000CM10003 1TB | 1        | 0.86%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 21       | 28     | 42%     |
| WDC                 | 20       | 26     | 40%     |
| Toshiba             | 3        | 3      | 6%      |
| Samsung Electronics | 3        | 3      | 6%      |
| Maxtor              | 1        | 1      | 2%      |
| Hitachi             | 1        | 2      | 2%      |
| Hewlett-Packard     | 1        | 1      | 2%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 9        | 10     | 26.47%  |
| Samsung Electronics | 7        | 9      | 20.59%  |
| SanDisk             | 6        | 8      | 17.65%  |
| WDC                 | 2        | 2      | 5.88%   |
| Seagate             | 1        | 1      | 2.94%   |
| Patriot             | 1        | 1      | 2.94%   |
| OCZ                 | 1        | 1      | 2.94%   |
| Lexar               | 1        | 1      | 2.94%   |
| KIOXIA-EXCERIA      | 1        | 1      | 2.94%   |
| Intenso             | 1        | 1      | 2.94%   |
| Crucial             | 1        | 2      | 2.94%   |
| China               | 1        | 1      | 2.94%   |
| Apacer              | 1        | 1      | 2.94%   |
| A-DATA Technology   | 1        | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 38       | 64     | 46.34%  |
| SSD     | 27       | 40     | 32.93%  |
| NVMe    | 12       | 18     | 14.63%  |
| Unknown | 5        | 6      | 6.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 45       | 106    | 75%     |
| NVMe | 12       | 18     | 20%     |
| SAS  | 3        | 4      | 5%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 33       | 50     | 46.48%  |
| 0.51-1.0   | 25       | 36     | 35.21%  |
| 1.01-2.0   | 8        | 12     | 11.27%  |
| 3.01-4.0   | 3        | 3      | 4.23%   |
| 2.01-3.0   | 1        | 2      | 1.41%   |
| 4.01-10.0  | 1        | 1      | 1.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 13       | 26.53%  |
| 251-500        | 9        | 18.37%  |
| 1001-2000      | 6        | 12.24%  |
| 501-1000       | 6        | 12.24%  |
| 51-100         | 6        | 12.24%  |
| 2001-3000      | 3        | 6.12%   |
| 1-20           | 3        | 6.12%   |
| More than 3000 | 2        | 4.08%   |
| 21-50          | 1        | 2.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 21       | 41.18%  |
| 21-50          | 9        | 17.65%  |
| 51-100         | 8        | 15.69%  |
| 101-250        | 5        | 9.8%    |
| 501-1000       | 3        | 5.88%   |
| More than 3000 | 2        | 3.92%   |
| 1001-2000      | 2        | 3.92%   |
| 251-500        | 1        | 1.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| WDC WD10EZEX-21M2NA0 1TB | 1        | 2      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 2      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 1        | 2      | 100%    |

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
| Detected | 47       | 123    | 92.16%  |
| Works    | 3        | 3      | 5.88%   |
| Malfunc  | 1        | 2      | 1.96%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 32       | 46.38%  |
| AMD                          | 17       | 24.64%  |
| Silicon Motion               | 2        | 2.9%    |
| Silicon Image                | 2        | 2.9%    |
| Sandisk                      | 2        | 2.9%    |
| Samsung Electronics          | 2        | 2.9%    |
| Phison Electronics           | 2        | 2.9%    |
| Micron/Crucial Technology    | 2        | 2.9%    |
| ASMedia Technology           | 2        | 2.9%    |
| VIA Technologies             | 1        | 1.45%   |
| Toshiba America Info Systems | 1        | 1.45%   |
| Marvell Technology Group     | 1        | 1.45%   |
| Kingston Technology Company  | 1        | 1.45%   |
| JMicron Technology           | 1        | 1.45%   |
| ADATA Technology             | 1        | 1.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 9.88%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 8        | 9.88%   |
| Intel SATA Controller [RAID mode]                                                       | 5        | 6.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 4.94%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 4.94%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 3.7%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 3.7%    |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 3.7%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 2.47%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 2.47%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 2.47%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 2.47%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 2.47%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 2.47%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 2        | 2.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 2.47%   |
| AMD FCH SATA Controller D                                                               | 2        | 2.47%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 1.23%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1        | 1.23%   |
| Silicon Image SiI 3512 [SATALink/SATARaid] Serial ATA Controller                        | 1        | 1.23%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                        | 1        | 1.23%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 1.23%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 1.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 1.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 1.23%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 1.23%   |
| Micron/Crucial NVMe Controller                                                          | 1        | 1.23%   |
| Marvell Group 88SE9120 SATA 6Gb/s Controller                                            | 1        | 1.23%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 1        | 1.23%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 1.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 1.23%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 1.23%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 1.23%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 1        | 1.23%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 1.23%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 1.23%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 1.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 39       | 58.21%  |
| NVMe | 12       | 17.91%  |
| IDE  | 9        | 13.43%  |
| RAID | 7        | 10.45%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 32       | 65.31%  |
| AMD    | 17       | 34.69%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 6.12%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 4.08%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 2        | 4.08%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 4.08%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 4.08%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 4.08%   |
| AMD FX-8320E Eight-Core Processor           | 2        | 4.08%   |
| Intel Xeon CPU X3220 @ 2.40GHz              | 1        | 2.04%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 2.04%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 2.04%   |
| Intel Core i9-10900K CPU @ 3.70GHz          | 1        | 2.04%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 2.04%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 2.04%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 2.04%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1        | 2.04%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 2.04%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 1        | 2.04%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 2.04%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 2.04%   |
| Intel Core i5-4430 CPU @ 3.00GHz            | 1        | 2.04%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1        | 2.04%   |
| Intel Core i5-2500S CPU @ 2.70GHz           | 1        | 2.04%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 2.04%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 2.04%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 2.04%   |
| Intel Core i3-4360T CPU @ 3.20GHz           | 1        | 2.04%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 2.04%   |
| Intel Core i3-3225 CPU @ 3.30GHz            | 1        | 2.04%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1        | 2.04%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 1        | 2.04%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 1        | 2.04%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 1        | 2.04%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 1        | 2.04%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 1        | 2.04%   |
| AMD Ryzen 3 1200 Quad-Core Processor        | 1        | 2.04%   |
| AMD Phenom II X4 965 Processor              | 1        | 2.04%   |
| AMD FX-9590 Eight-Core Processor            | 1        | 2.04%   |
| AMD FX-6350 Six-Core Processor              | 1        | 2.04%   |
| AMD FX-6300 Six-Core Processor              | 1        | 2.04%   |
| AMD A6-5400K APU with Radeon HD Graphics    | 1        | 2.04%   |
| AMD A6-5400B APU with Radeon HD Graphics    | 1        | 2.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 10       | 20.41%  |
| Intel Core i7           | 8        | 16.33%  |
| Intel Core i3           | 8        | 16.33%  |
| AMD FX                  | 5        | 10.2%   |
| AMD Ryzen 7             | 3        | 6.12%   |
| AMD Ryzen 3             | 3        | 6.12%   |
| Intel Core 2 Quad       | 2        | 4.08%   |
| AMD Ryzen 5             | 2        | 4.08%   |
| AMD A6                  | 2        | 4.08%   |
| Intel Xeon              | 1        | 2.04%   |
| Intel Pentium Dual-Core | 1        | 2.04%   |
| Intel Pentium Dual      | 1        | 2.04%   |
| Intel Core i9           | 1        | 2.04%   |
| AMD Ryzen 9             | 1        | 2.04%   |
| AMD Phenom II X4        | 1        | 2.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 29       | 59.18%  |
| 2      | 8        | 16.33%  |
| 8      | 4        | 8.16%   |
| 6      | 2        | 4.08%   |
| 3      | 2        | 4.08%   |
| 1      | 2        | 4.08%   |
| 12     | 1        | 2.04%   |
| 10     | 1        | 2.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 49       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 27       | 55.1%   |
| 1      | 22       | 44.9%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 49       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 11       | 22.45%  |
| 0x06000852 | 5        | 10.2%   |
| 0x206a7    | 4        | 8.16%   |
| 0x6fb      | 3        | 6.12%   |
| 0x506e3    | 3        | 6.12%   |
| 0x306a9    | 3        | 6.12%   |
| 0x08701021 | 3        | 6.12%   |
| 0x906eb    | 2        | 4.08%   |
| 0x0800820d | 2        | 4.08%   |
| 0x06001119 | 2        | 4.08%   |
| Unknown    | 2        | 4.08%   |
| 0xa0655    | 1        | 2.04%   |
| 0x906ec    | 1        | 2.04%   |
| 0x6fd      | 1        | 2.04%   |
| 0x1067a    | 1        | 2.04%   |
| 0x08701013 | 1        | 2.04%   |
| 0x08108109 | 1        | 2.04%   |
| 0x08101016 | 1        | 2.04%   |
| 0x08001138 | 1        | 2.04%   |
| 0x010000c8 | 1        | 2.04%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 11       | 22.45%  |
| Piledriver  | 7        | 14.29%  |
| SandyBridge | 5        | 10.2%   |
| Zen 2       | 4        | 8.16%   |
| KabyLake    | 4        | 8.16%   |
| Core        | 4        | 8.16%   |
| Zen+        | 3        | 6.12%   |
| Skylake     | 3        | 6.12%   |
| IvyBridge   | 3        | 6.12%   |
| Zen         | 2        | 4.08%   |
| Penryn      | 1        | 2.04%   |
| K10         | 1        | 2.04%   |
| CometLake   | 1        | 2.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 21       | 39.62%  |
| Intel  | 17       | 32.08%  |
| AMD    | 15       | 28.3%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6        | 11.11%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 5.56%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 5.56%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 5.56%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 3.7%    |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 3.7%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 3.7%    |
| AMD Trinity 2 [Radeon HD 7540D]                                             | 2        | 3.7%    |
| AMD RS780L [Radeon 3000]                                                    | 2        | 3.7%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 3.7%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.85%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 1.85%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 1.85%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.85%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.85%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.85%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.85%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.85%   |
| Nvidia GM107GL [Quadro K1200]                                               | 1        | 1.85%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.85%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.85%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 1.85%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1        | 1.85%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.85%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 1.85%   |
| Nvidia GA106 [GeForce RTX 3060]                                             | 1        | 1.85%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 1.85%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.85%   |
| Intel HD Graphics 630                                                       | 1        | 1.85%   |
| Intel HD Graphics 530                                                       | 1        | 1.85%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.85%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 1        | 1.85%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.85%   |
| AMD RS880 [Radeon HD 4250]                                                  | 1        | 1.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.85%   |
| AMD Picasso                                                                 | 1        | 1.85%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 1.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 21       | 42%     |
| 1 x AMD    | 15       | 30%     |
| 1 x Intel  | 13       | 26%     |
| 2 x AMD    | 1        | 2%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 32       | 65.31%  |
| Proprietary | 17       | 34.69%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 15       | 30.61%  |
| 1.01-2.0   | 11       | 22.45%  |
| 3.01-4.0   | 5        | 10.2%   |
| 0.01-0.5   | 5        | 10.2%   |
| 7.01-8.0   | 4        | 8.16%   |
| 0.51-1.0   | 4        | 8.16%   |
| 5.01-6.0   | 3        | 6.12%   |
| 2.01-3.0   | 1        | 2.04%   |
| 16.01-24.0 | 1        | 2.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 10       | 19.23%  |
| Acer                 | 6        | 11.54%  |
| Philips              | 4        | 7.69%   |
| Goldstar             | 4        | 7.69%   |
| AOC                  | 4        | 7.69%   |
| Hewlett-Packard      | 3        | 5.77%   |
| Vizio                | 2        | 3.85%   |
| NEC Computers        | 2        | 3.85%   |
| Lenovo               | 2        | 3.85%   |
| Dell                 | 2        | 3.85%   |
| Ancor Communications | 2        | 3.85%   |
| Xiaomi               | 1        | 1.92%   |
| ViewSonic            | 1        | 1.92%   |
| Unknown              | 1        | 1.92%   |
| Sony                 | 1        | 1.92%   |
| Sceptre Tech         | 1        | 1.92%   |
| LG Electronics       | 1        | 1.92%   |
| Iiyama               | 1        | 1.92%   |
| Gigabyte Technology  | 1        | 1.92%   |
| Gateway              | 1        | 1.92%   |
| Fujitsu Siemens      | 1        | 1.92%   |
| AUS                  | 1        | 1.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Xiaomi Mi TV XMD00E2 3840x2160 800x450mm 36.1-inch                     | 1        | 1.85%   |
| Vizio VO37LFHDTV10A VIZ0043 1920x1080 820x460mm 37.0-inch              | 1        | 1.85%   |
| Vizio E241i-A1 VIZ1005 1920x1080 521x293mm 23.5-inch                   | 1        | 1.85%   |
| ViewSonic LCD Monitor VA2256 Series 1920x1080                          | 1        | 1.85%   |
| Unknown LCD Monitor LHC TE-3125 1920x1080                              | 1        | 1.85%   |
| Sony TV *00 SNYA405 3840x2160 952x535mm 43.0-inch                      | 1        | 1.85%   |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                 | 1        | 1.85%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch      | 1        | 1.85%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch      | 1        | 1.85%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch      | 1        | 1.85%   |
| Samsung Electronics S27R35A SAM7126 1920x1080 598x336mm 27.0-inch      | 1        | 1.85%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch      | 1        | 1.85%   |
| Samsung Electronics LCD Monitor SAM0C3C 1920x1080 700x390mm 31.5-inch  | 1        | 1.85%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 1        | 1.85%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 1020x570mm 46.0-inch | 1        | 1.85%   |
| Samsung Electronics LCD Monitor C27R50x 1920x1080                      | 1        | 1.85%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1190x340mm 48.7-inch     | 1        | 1.85%   |
| Philips PHL 278E9Q PHLC17F 1920x1080 598x336mm 27.0-inch               | 1        | 1.85%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                | 1        | 1.85%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1        | 1.85%   |
| Philips LCD Monitor 240B 1920x1200                                     | 1        | 1.85%   |
| NEC Computers LCD Monitor E231W 3840x1080                              | 1        | 1.85%   |
| NEC Computers LCD Monitor E231W                                        | 1        | 1.85%   |
| NEC Computers EA244WMi NEC68D7 1920x1080 520x320mm 24.0-inch           | 1        | 1.85%   |
| LG Electronics LCD Monitor EW224 1920x1080                             | 1        | 1.85%   |
| Lenovo LEN T23i-10 LEN61AB 1920x1080 509x286mm 23.0-inch               | 1        | 1.85%   |
| Lenovo D22-20 LEN66AD 1920x1080 477x268mm 21.5-inch                    | 1        | 1.85%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                  | 1        | 1.85%   |
| Hewlett-Packard w17e HWP26E0 1440x900 408x255mm 18.9-inch              | 1        | 1.85%   |
| Hewlett-Packard LCD Monitor w1907 3120x1050                            | 1        | 1.85%   |
| Hewlett-Packard Compaq WF1907 HWP26A5 1440x900 408x255mm 18.9-inch     | 1        | 1.85%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch            | 1        | 1.85%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                    | 1        | 1.85%   |
| Goldstar LCD Monitor GSM580C 1680x1050 510x290mm 23.1-inch             | 1        | 1.85%   |
| Goldstar L1950SQ GSM4AD3 1280x1024 376x301mm 19.0-inch                 | 1        | 1.85%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 1        | 1.85%   |
| Gigabyte Technology G34WQC GBT3400 3440x1440 797x334mm 34.0-inch       | 1        | 1.85%   |
| Gateway VX930 GWY232D 1600x1200 350x262mm 17.2-inch                    | 1        | 1.85%   |
| Fujitsu Siemens LSL 3260W FUS07AE 1920x1200 550x344mm 25.5-inch        | 1        | 1.85%   |
| Dell S2715H DEL40BA 1920x1080 598x336mm 27.0-inch                      | 1        | 1.85%   |
| Dell LCD Monitor E228WFP                                               | 1        | 1.85%   |
| AUS LCD Monitor ASUS VP247 1920x1080                                   | 1        | 1.85%   |
| AOC LCD Monitor 24B1W 1920x1080                                        | 1        | 1.85%   |
| AOC LCD Monitor 2269W 1920x1080                                        | 1        | 1.85%   |
| AOC AG323FWG3R3 AOC3230 1920x1080 698x393mm 31.5-inch                  | 1        | 1.85%   |
| AOC AG273QS8R4 AOC2730 2560x1440 600x340mm 27.2-inch                   | 1        | 1.85%   |
| Ancor Communications VW22A ACI22E3 1680x1050 473x296mm 22.0-inch       | 1        | 1.85%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 1        | 1.85%   |
| Acer V206WQL ACR045D 1440x900 419x262mm 19.5-inch                      | 1        | 1.85%   |
| Acer LCD Monitor V246HL 1920x1080                                      | 1        | 1.85%   |
| Acer LCD Monitor SA270 1920x1080                                       | 1        | 1.85%   |
| Acer LCD Monitor S271HL 1920x1080                                      | 1        | 1.85%   |
| Acer LCD Monitor AL1912 1280x1024                                      | 1        | 1.85%   |
| Acer K202HQL ACR03E0 1600x900 432x240mm 19.5-inch                      | 1        | 1.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 27       | 54%     |
| 3840x2160 (4K)     | 6        | 12%     |
| 3840x1080          | 2        | 4%      |
| 1920x1200 (WUXGA)  | 2        | 4%      |
| 1680x1050 (WSXGA+) | 2        | 4%      |
| 1280x1024 (SXGA)   | 2        | 4%      |
| Unknown            | 2        | 4%      |
| 3440x1440          | 1        | 2%      |
| 3120x1050          | 1        | 2%      |
| 2560x1440 (QHD)    | 1        | 2%      |
| 1600x900 (HD+)     | 1        | 2%      |
| 1600x1200          | 1        | 2%      |
| 1440x900 (WXGA+)   | 1        | 2%      |
| 1366x768 (WXGA)    | 1        | 2%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 14       | 27.45%  |
| 27      | 6        | 11.76%  |
| 31      | 5        | 9.8%    |
| 23      | 4        | 7.84%   |
| 21      | 4        | 7.84%   |
| 24      | 3        | 5.88%   |
| 19      | 3        | 5.88%   |
| 48      | 2        | 3.92%   |
| 22      | 2        | 3.92%   |
| 46      | 1        | 1.96%   |
| 43      | 1        | 1.96%   |
| 41      | 1        | 1.96%   |
| 36      | 1        | 1.96%   |
| 34      | 1        | 1.96%   |
| 25      | 1        | 1.96%   |
| 18      | 1        | 1.96%   |
| 17      | 1        | 1.96%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 14       | 29.17%  |
| 501-600     | 11       | 22.92%  |
| 401-500     | 8        | 16.67%  |
| 601-700     | 6        | 12.5%   |
| 1001-1500   | 3        | 6.25%   |
| 701-800     | 2        | 4.17%   |
| 901-1000    | 2        | 4.17%   |
| 351-400     | 1        | 2.08%   |
| 301-350     | 1        | 2.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 23       | 50%     |
| Unknown | 14       | 30.43%  |
| 16/10   | 5        | 10.87%  |
| 5/4     | 1        | 2.17%   |
| 4/3     | 1        | 2.17%   |
| 32/9    | 1        | 2.17%   |
| 21/9    | 1        | 2.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 14       | 28%     |
| 201-250        | 11       | 22%     |
| 351-500        | 6        | 12%     |
| 301-350        | 6        | 12%     |
| 501-1000       | 5        | 10%     |
| 151-200        | 4        | 8%      |
| 251-300        | 2        | 4%      |
| More than 1000 | 1        | 2%      |
| 141-150        | 1        | 2%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 20       | 41.67%  |
| Unknown | 14       | 29.17%  |
| 101-120 | 7        | 14.58%  |
| 121-160 | 4        | 8.33%   |
| 1-50    | 3        | 6.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 43       | 86%     |
| 2     | 7        | 14%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 33       | 45.83%  |
| Intel                    | 18       | 25%     |
| Qualcomm Atheros         | 6        | 8.33%   |
| TP-Link                  | 3        | 4.17%   |
| Ralink                   | 3        | 4.17%   |
| Ralink Technology        | 2        | 2.78%   |
| Samsung Electronics      | 1        | 1.39%   |
| NetGear                  | 1        | 1.39%   |
| Motorola PCS             | 1        | 1.39%   |
| Marvell Technology Group | 1        | 1.39%   |
| Edimax Technology        | 1        | 1.39%   |
| DisplayLink              | 1        | 1.39%   |
| D-Link System            | 1        | 1.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27       | 35.06%  |
| Intel Ethernet Connection (2) I218-V                              | 3        | 3.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 2.6%    |
| Realtek 802.11ac NIC                                              | 2        | 2.6%    |
| Ralink MT7601U Wireless Adapter                                   | 2        | 2.6%    |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 2.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 2.6%    |
| TP-Link Archer T4U ver.3                                          | 1        | 1.3%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 1.3%    |
| TP-Link 802.11ac WLAN Adapter                                     | 1        | 1.3%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 1.3%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 1.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 1.3%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.3%    |
| Ralink RT5592 PCIe Wireless Network Adapter                       | 1        | 1.3%    |
| Ralink RT2600 802.11 MIMO                                         | 1        | 1.3%    |
| Ralink RT2561/RT61 802.11g PCI                                    | 1        | 1.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 1.3%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 1.3%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 1.3%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.3%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1        | 1.3%    |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 1        | 1.3%    |
| Motorola PCS moto g(30)                                           | 1        | 1.3%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.3%    |
| Intel Wireless-AC 9260                                            | 1        | 1.3%    |
| Intel Wi-Fi 6 AX200                                               | 1        | 1.3%    |
| Intel I211 Gigabit Network Connection                             | 1        | 1.3%    |
| Intel I210 Gigabit Network Connection                             | 1        | 1.3%    |
| Intel Ethernet Controller I225-V                                  | 1        | 1.3%    |
| Intel Ethernet Connection I217-V                                  | 1        | 1.3%    |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.3%    |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.3%    |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.3%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1        | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 1        | 1.3%    |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.3%    |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 1.3%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]    | 1        | 1.3%    |
| DisplayLink USB 3.0 Dual Video Dock                               | 1        | 1.3%    |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 1.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 6        | 26.09%  |
| Realtek Semiconductor | 4        | 17.39%  |
| TP-Link               | 3        | 13.04%  |
| Ralink                | 3        | 13.04%  |
| Qualcomm Atheros      | 3        | 13.04%  |
| Ralink Technology     | 2        | 8.7%    |
| NetGear               | 1        | 4.35%   |
| Edimax Technology     | 1        | 4.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek 802.11ac NIC                                           | 2        | 8.7%    |
| Ralink MT7601U Wireless Adapter                                | 2        | 8.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2        | 8.7%    |
| TP-Link Archer T4U ver.3                                       | 1        | 4.35%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1        | 4.35%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1        | 4.35%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1        | 4.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1        | 4.35%   |
| Ralink RT5592 PCIe Wireless Network Adapter                    | 1        | 4.35%   |
| Ralink RT2600 802.11 MIMO                                      | 1        | 4.35%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 1        | 4.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1        | 4.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1        | 4.35%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1        | 4.35%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 1        | 4.35%   |
| Intel Wireless-AC 9260                                         | 1        | 4.35%   |
| Intel Wi-Fi 6 AX200                                            | 1        | 4.35%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1        | 4.35%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1        | 4.35%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1        | 4.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 30       | 56.6%   |
| Intel                    | 15       | 28.3%   |
| Qualcomm Atheros         | 3        | 5.66%   |
| Samsung Electronics      | 1        | 1.89%   |
| Motorola PCS             | 1        | 1.89%   |
| Marvell Technology Group | 1        | 1.89%   |
| DisplayLink              | 1        | 1.89%   |
| D-Link System            | 1        | 1.89%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27       | 50%     |
| Intel Ethernet Connection (2) I218-V                              | 3        | 5.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 3.7%    |
| Intel Ethernet Connection I217-LM                                 | 2        | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 3.7%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 1.85%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.85%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1        | 1.85%   |
| Motorola PCS moto g(30)                                           | 1        | 1.85%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.85%   |
| Intel I211 Gigabit Network Connection                             | 1        | 1.85%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.85%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.85%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.85%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.85%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.85%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.85%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.85%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 1.85%   |
| DisplayLink USB 3.0 Dual Video Dock                               | 1        | 1.85%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 1.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 49       | 71.01%  |
| WiFi     | 20       | 28.99%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 49       | 75.38%  |
| WiFi     | 16       | 24.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 36       | 73.47%  |
| 2     | 12       | 24.49%  |
| 3     | 1        | 2.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 30       | 60%     |
| Yes  | 20       | 40%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 5        | 31.25%  |
| Cambridge Silicon Radio         | 3        | 18.75%  |
| Realtek Semiconductor           | 2        | 12.5%   |
| Qualcomm Atheros Communications | 2        | 12.5%   |
| Lite-On Technology              | 1        | 6.25%   |
| Dell                            | 1        | 6.25%   |
| Broadcom                        | 1        | 6.25%   |
| ASUSTek Computer                | 1        | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 18.75%  |
| Realtek Bluetooth Radio                             | 2        | 12.5%   |
| Intel Bluetooth Device                              | 2        | 12.5%   |
| Qualcomm Atheros Bluetooth                          | 1        | 6.25%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 6.25%   |
| Lite-On Bluetooth Device                            | 1        | 6.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 6.25%   |
| Intel Bluetooth wireless interface                  | 1        | 6.25%   |
| Intel AX200 Bluetooth                               | 1        | 6.25%   |
| Dell BT Mini-Receiver                               | 1        | 6.25%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 6.25%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 31       | 37.35%  |
| Nvidia            | 21       | 25.3%   |
| AMD               | 21       | 25.3%   |
| Creative Labs     | 2        | 2.41%   |
| XMOS              | 1        | 1.2%    |
| Texas Instruments | 1        | 1.2%    |
| Razer USA         | 1        | 1.2%    |
| Numark            | 1        | 1.2%    |
| Logitech          | 1        | 1.2%    |
| Klipsch Audio     | 1        | 1.2%    |
| JMTek             | 1        | 1.2%    |
| GN Netcom         | 1        | 1.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7        | 7.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7        | 7.07%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 6.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5        | 5.05%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 4.04%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 4.04%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 3.03%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 3.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 3.03%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 3.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 3.03%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 3.03%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 2.02%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 2.02%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 2.02%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 2.02%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 2.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 2.02%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 2        | 2.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 2.02%   |
| AMD FCH Azalia Controller                                                  | 2        | 2.02%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 2        | 2.02%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 2.02%   |
| XMOS Gustard USB Audio 2.0                                                 | 1        | 1.01%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                          | 1        | 1.01%   |
| Razer USA Razer USB Sound Card                                             | 1        | 1.01%   |
| Razer USA Razer Seiren Mini                                                | 1        | 1.01%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 1.01%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.01%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 1.01%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1.01%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 1.01%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 1.01%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 1.01%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 1.01%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 1.01%   |
| Nvidia Audio device                                                        | 1        | 1.01%   |
| Numark MixTrack Pro                                                        | 1        | 1.01%   |
| Logitech H600 [Wireless Headset]                                           | 1        | 1.01%   |
| Klipsch Audio Klipsch KG-200 Headphones                                    | 1        | 1.01%   |
| JMTek USB PnP Audio Device                                                 | 1        | 1.01%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 1.01%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 1.01%   |
| GN Netcom Jabra Link 370                                                   | 1        | 1.01%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 1        | 1.01%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                 | 1        | 1.01%   |
| AMD Trinity HDMI Audio Controller                                          | 1        | 1.01%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1        | 1.01%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2        | 50%     |
| Team    | 1        | 25%     |
| Corsair | 1        | 25%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM TM44D18UD04MU-NUK 4096MB DIMM DDR4 2400MT/s | 1        | 16.67%  |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s               | 1        | 16.67%  |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 1        | 16.67%  |
| Unknown RAM 04S2400CL17A 4096MB DIMM DDR4 2400MT/s      | 1        | 16.67%  |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s      | 1        | 16.67%  |
| Corsair RAM CMW64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s  | 1        | 16.67%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 3        | 75%     |
| Unknown | 1        | 25%     |

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


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 2        | 40%     |
| 4096  | 2        | 40%     |
| 32768 | 1        | 20%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 1        | 25%     |
| 2667  | 1        | 25%     |
| 2400  | 1        | 25%     |
| 1333  | 1        | 25%     |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 2        | 66.67%  |
| Samsung Electronics | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Samsung SCX-3400 Series         | 1        | 33.33%  |
| HP OfficeJet 4650 series        | 1        | 33.33%  |
| HP LaserJet Professional P1102w | 1        | 33.33%  |

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
| Razer USA        | 1        | 25%     |
| Microsoft        | 1        | 25%     |
| Logitech         | 1        | 25%     |
| Jieli Technology | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Razer USA Razer Kiyo                 | 1        | 25%     |
| Microsoft Microsoft?� LifeCam Cinema | 1        | 25%     |
| Logitech HD Pro Webcam C920          | 1        | 25%     |
| Jieli USB PHY 2.0                    | 1        | 25%     |

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
| 0     | 44       | 89.8%   |
| 1     | 5        | 10.2%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type         | Desktops | Percent |
|--------------|----------|---------|
| Net/wireless | 5        | 100%    |

