LMDE 5 - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for LMDE 5.

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

Total: 64

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Acer      | Aspire XC-1660G V:1.1       | [f7f5368662](https://linux-hardware.org/?probe=f7f5368662) | Sep 28, 2022 |
| Acer      | Aspire XC-1660G V:1.1       | [fb983c65ac](https://linux-hardware.org/?probe=fb983c65ac) | Sep 28, 2022 |
| Dell      | 082WXT A01                  | [7b1ea76e92](https://linux-hardware.org/?probe=7b1ea76e92) | Sep 26, 2022 |
| Dell      | 082WXT A01                  | [7c4445ad04](https://linux-hardware.org/?probe=7c4445ad04) | Sep 26, 2022 |
| Gateway   | DX4870                      | [fd5b76e786](https://linux-hardware.org/?probe=fd5b76e786) | Sep 22, 2022 |
| Digiboard | NM70-TI                     | [84e21c8253](https://linux-hardware.org/?probe=84e21c8253) | Sep 21, 2022 |
| Dell      | 0XC837                      | [94ad27e346](https://linux-hardware.org/?probe=94ad27e346) | Sep 19, 2022 |
| MSI       | B360M MORTAR                | [cdcff8c15d](https://linux-hardware.org/?probe=cdcff8c15d) | Sep 18, 2022 |
| ASUSTek   | PRIME H610M-E D4            | [b8f2004ea5](https://linux-hardware.org/?probe=b8f2004ea5) | Sep 10, 2022 |
| Dell      | 0FJ030                      | [bf789b5c5f](https://linux-hardware.org/?probe=bf789b5c5f) | Sep 10, 2022 |
| MSI       | B450I GAMING PLUS AC        | [acbb191061](https://linux-hardware.org/?probe=acbb191061) | Sep 09, 2022 |
| Pegatron  | 2A9Eh                       | [2c7b59f70b](https://linux-hardware.org/?probe=2c7b59f70b) | Sep 08, 2022 |
| ASUSTek   | P8H77-V                     | [c92f578a36](https://linux-hardware.org/?probe=c92f578a36) | Sep 07, 2022 |
| ASUSTek   | ROG CROSSHAIR VIII HERO     | [9842cac1de](https://linux-hardware.org/?probe=9842cac1de) | Sep 04, 2022 |
| eMachines | EL1352G                     | [2547a277f7](https://linux-hardware.org/?probe=2547a277f7) | Sep 04, 2022 |
| ASUSTek   | P5K-E                       | [632cd1e47d](https://linux-hardware.org/?probe=632cd1e47d) | Sep 03, 2022 |
| Dell      | 042P49 A00                  | [31efc1e75f](https://linux-hardware.org/?probe=31efc1e75f) | Sep 01, 2022 |
| ASUSTek   | P5QPL-AM                    | [38e6481a65](https://linux-hardware.org/?probe=38e6481a65) | Aug 30, 2022 |
| Gigabyte  | B450M DS3H-CF               | [afde42fb41](https://linux-hardware.org/?probe=afde42fb41) | Aug 28, 2022 |
| Gigabyte  | B450M DS3H-CF               | [6c1db95864](https://linux-hardware.org/?probe=6c1db95864) | Aug 28, 2022 |
| MSI       | Z170A GAMING PRO            | [f86bc78c33](https://linux-hardware.org/?probe=f86bc78c33) | Aug 27, 2022 |
| MSI       | B85I                        | [454972a062](https://linux-hardware.org/?probe=454972a062) | Aug 19, 2022 |
| Gigabyte  | H97-Gaming 3                | [2d464fc182](https://linux-hardware.org/?probe=2d464fc182) | Aug 10, 2022 |
| Gigabyte  | B85M-DS3H-A                 | [527a0607d8](https://linux-hardware.org/?probe=527a0607d8) | Aug 08, 2022 |
| ASRock    | H61M-DGS                    | [683cd6273f](https://linux-hardware.org/?probe=683cd6273f) | Jul 30, 2022 |
| Gigabyte  | B450 AORUS M                | [fdaa3bac93](https://linux-hardware.org/?probe=fdaa3bac93) | Jul 20, 2022 |
| Gigabyte  | B450 AORUS M                | [aca8d98967](https://linux-hardware.org/?probe=aca8d98967) | Jul 18, 2022 |
| HP        | 8433 11                     | [85ecad964d](https://linux-hardware.org/?probe=85ecad964d) | Jul 17, 2022 |
| HP        | 8433 11                     | [7f6ec63dc8](https://linux-hardware.org/?probe=7f6ec63dc8) | Jul 17, 2022 |
| ASUSTek   | BM6820_BM6620_BP6320-8      | [8d8c845646](https://linux-hardware.org/?probe=8d8c845646) | Jul 17, 2022 |
| Gigabyte  | B450 AORUS M                | [12e48a7c0a](https://linux-hardware.org/?probe=12e48a7c0a) | Jul 06, 2022 |
| ASUSTek   | P8H77-M PRO                 | [efc2332724](https://linux-hardware.org/?probe=efc2332724) | Jul 02, 2022 |
| Dell      | 0XR1GT A00                  | [0d72ab6a71](https://linux-hardware.org/?probe=0d72ab6a71) | Jun 24, 2022 |
| Lenovo    | 3731 NOK                    | [efd1e69f79](https://linux-hardware.org/?probe=efd1e69f79) | Jun 09, 2022 |
| Lenovo    | 3731 NOK                    | [1da6b9f6c0](https://linux-hardware.org/?probe=1da6b9f6c0) | Jun 09, 2022 |
| Dell      | 0XR1GT A00                  | [8c3fd28612](https://linux-hardware.org/?probe=8c3fd28612) | Jun 08, 2022 |
| MSI       | MPG Z390 GAMING PRO CARB... | [6f8785bd56](https://linux-hardware.org/?probe=6f8785bd56) | May 30, 2022 |
| Lenovo    | MAHOBAY                     | [ba204646ba](https://linux-hardware.org/?probe=ba204646ba) | May 25, 2022 |
| Acer      | Seawolf                     | [dccbcb7ef3](https://linux-hardware.org/?probe=dccbcb7ef3) | May 25, 2022 |
| Intel     | DQ77MK AAG39642-400         | [f694bcfbc5](https://linux-hardware.org/?probe=f694bcfbc5) | May 21, 2022 |
| MSI       | X470 GAMING PLUS MAX        | [63950495b3](https://linux-hardware.org/?probe=63950495b3) | May 15, 2022 |
| MSI       | 970A-G43 PLUS               | [399deea7b9](https://linux-hardware.org/?probe=399deea7b9) | May 15, 2022 |
| Gigabyte  | Z68A-D3H-B3                 | [1441dfb79e](https://linux-hardware.org/?probe=1441dfb79e) | May 07, 2022 |
| HP        | 158B                        | [a613debdee](https://linux-hardware.org/?probe=a613debdee) | May 06, 2022 |
| HP        | 158B                        | [21f9c188f3](https://linux-hardware.org/?probe=21f9c188f3) | May 06, 2022 |
| HP        | 339A                        | [d58b95ebb1](https://linux-hardware.org/?probe=d58b95ebb1) | May 05, 2022 |
| Gigabyte  | H110M-S2H-CF                | [c45a37ce5d](https://linux-hardware.org/?probe=c45a37ce5d) | May 01, 2022 |
| ASUSTek   | PRIME H610M-A D4            | [e9376d24f0](https://linux-hardware.org/?probe=e9376d24f0) | Apr 29, 2022 |
| ASRock    | A320M-DGS                   | [b7df060840](https://linux-hardware.org/?probe=b7df060840) | Apr 19, 2022 |
| ASRock    | A320M-DGS                   | [70fe08376f](https://linux-hardware.org/?probe=70fe08376f) | Apr 19, 2022 |
| Dell      | 0CU568 A00                  | [b544c48421](https://linux-hardware.org/?probe=b544c48421) | Apr 19, 2022 |
| Dell      | 0CU568 A00                  | [84f7029c22](https://linux-hardware.org/?probe=84f7029c22) | Apr 19, 2022 |
| ASUSTek   | PRIME B350M-A               | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| ASUSTek   | PRIME B350M-A               | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| MSI       | Z170A GAMING M5             | [8f2e10cbf3](https://linux-hardware.org/?probe=8f2e10cbf3) | Apr 12, 2022 |
| Lenovo    | 312A SDK0J40697 WIN 3305... | [2a33f087e6](https://linux-hardware.org/?probe=2a33f087e6) | Apr 11, 2022 |
| Lenovo    | 312A SDK0J40697 WIN 3305... | [05b9ec80c6](https://linux-hardware.org/?probe=05b9ec80c6) | Apr 11, 2022 |
| Acer      | WG43M                       | [c7cb6ee141](https://linux-hardware.org/?probe=c7cb6ee141) | Apr 08, 2022 |
| ASUSTek   | P5G41T-M LX3                | [28371c08c2](https://linux-hardware.org/?probe=28371c08c2) | Apr 08, 2022 |
| MSI       | X470 GAMING PLUS MAX        | [9f1a76acb8](https://linux-hardware.org/?probe=9f1a76acb8) | Apr 06, 2022 |
| MSI       | X470 GAMING PLUS MAX        | [18a4ba3137](https://linux-hardware.org/?probe=18a4ba3137) | Apr 06, 2022 |
| ASUSTek   | P6T                         | [5ed6ed355f](https://linux-hardware.org/?probe=5ed6ed355f) | Apr 04, 2022 |
| ASUSTek   | PRIME H510M-D               | [1e0a28c8f3](https://linux-hardware.org/?probe=1e0a28c8f3) | Mar 28, 2022 |
| HP        | 0AE8h C                     | [d3980b5b59](https://linux-hardware.org/?probe=d3980b5b59) | Mar 14, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Desktops | Percent |
|-----------------|----------|---------|
| 5.10.0-17-amd64 | 11       | 22.45%  |
| 5.10.0-14-amd64 | 10       | 20.41%  |
| 5.10.0-13-amd64 | 10       | 20.41%  |
| 5.10.0-12-amd64 | 9        | 18.37%  |
| 5.10.0-18-amd64 | 4        | 8.16%   |
| 5.10.0-16-amd64 | 2        | 4.08%   |
| 5.10.0-15-amd64 | 2        | 4.08%   |
| 5.10.0-13-686   | 1        | 2.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 48       | 100%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 48       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 47       | 97.92%  |
| i686   | 1        | 2.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| X-Cinnamon | 44       | 91.67%  |
| Cinnamon   | 2        | 4.17%   |
| XFCE       | 1        | 2.08%   |
| MATE       | 1        | 2.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 48       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 34       | 70.83%  |
| LightDM | 14       | 29.17%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 19       | 39.58%  |
| ru_RU | 4        | 8.33%   |
| pt_BR | 4        | 8.33%   |
| fr_FR | 3        | 6.25%   |
| de_DE | 3        | 6.25%   |
| pl_PL | 2        | 4.17%   |
| it_IT | 2        | 4.17%   |
| es_ES | 2        | 4.17%   |
| en_GB | 2        | 4.17%   |
| sv_SE | 1        | 2.08%   |
| it_CH | 1        | 2.08%   |
| fr_CA | 1        | 2.08%   |
| es_NI | 1        | 2.08%   |
| en_CA | 1        | 2.08%   |
| en_AU | 1        | 2.08%   |
| ar_EG | 1        | 2.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 26       | 54.17%  |
| EFI  | 22       | 45.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 44       | 91.67%  |
| Tmpfs   | 2        | 4.17%   |
| Overlay | 1        | 2.08%   |
| Btrfs   | 1        | 2.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 35       | 72.92%  |
| GPT     | 8        | 16.67%  |
| MBR     | 5        | 10.42%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 44       | 91.67%  |
| Yes       | 4        | 8.33%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 43       | 89.58%  |
| Yes       | 5        | 10.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 12       | 25%     |
| MSI                 | 8        | 16.67%  |
| Dell                | 6        | 12.5%   |
| Gigabyte Technology | 5        | 10.42%  |
| Hewlett-Packard     | 4        | 8.33%   |
| Lenovo              | 3        | 6.25%   |
| Acer                | 3        | 6.25%   |
| ASRock              | 2        | 4.17%   |
| Pegatron            | 1        | 2.08%   |
| Intel               | 1        | 2.08%   |
| Gateway             | 1        | 2.08%   |
| eMachines           | 1        | 2.08%   |
| Digiboard           | 1        | 2.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Pegatron Pro 3015 Microtower PC     | 1        | 2.08%   |
| MSI MS-7B79                         | 1        | 2.08%   |
| MSI MS-7B23                         | 1        | 2.08%   |
| MSI MS-7B17                         | 1        | 2.08%   |
| MSI MS-7A40                         | 1        | 2.08%   |
| MSI MS-7984                         | 1        | 2.08%   |
| MSI MS-7977                         | 1        | 2.08%   |
| MSI MS-7974                         | 1        | 2.08%   |
| MSI MS-7851                         | 1        | 2.08%   |
| Lenovo V55t-15ARE 11KJ0036TX        | 1        | 2.08%   |
| Lenovo ThinkCentre M92p 3238E9U     | 1        | 2.08%   |
| Lenovo ThinkCentre M720s 10SUS9KW00 | 1        | 2.08%   |
| Intel DQ77MK AAG39642-400           | 1        | 2.08%   |
| HP Z820 Workstation                 | 1        | 2.08%   |
| HP Z600 Workstation                 | 1        | 2.08%   |
| HP Pavilion Desktop 590-p0xxx       | 1        | 2.08%   |
| HP Compaq Pro 6300 SFF              | 1        | 2.08%   |
| Gigabyte Z68A-D3H-B3                | 1        | 2.08%   |
| Gigabyte H110M-S2H                  | 1        | 2.08%   |
| Gigabyte B85M-DS3H-A                | 1        | 2.08%   |
| Gigabyte B450M DS3H                 | 1        | 2.08%   |
| Gigabyte B450 AORUS M               | 1        | 2.08%   |
| Gateway DX4870                      | 1        | 2.08%   |
| eMachines EL1352G                   | 1        | 2.08%   |
| Digiboard NM70-TI                   | 1        | 2.08%   |
| Dell XPS A2010                      | 1        | 2.08%   |
| Dell Precision WorkStation 670      | 1        | 2.08%   |
| Dell Precision T7600                | 1        | 2.08%   |
| Dell OptiPlex 3010                  | 1        | 2.08%   |
| Dell Inspiron 660                   | 1        | 2.08%   |
| Dell DXP051                         | 1        | 2.08%   |
| ASUS ROG CROSSHAIR VIII HERO        | 1        | 2.08%   |
| ASUS PRIME H610M-E D4               | 1        | 2.08%   |
| ASUS PRIME H610M-A D4               | 1        | 2.08%   |
| ASUS PRIME H510M-D                  | 1        | 2.08%   |
| ASUS PRIME B350M-A                  | 1        | 2.08%   |
| ASUS P8H77-V                        | 1        | 2.08%   |
| ASUS P8H77-M PRO                    | 1        | 2.08%   |
| ASUS P6T                            | 1        | 2.08%   |
| ASUS P5QPL-AM                       | 1        | 2.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 4        | 8.33%   |
| Lenovo ThinkCentre   | 2        | 4.17%   |
| Dell Precision       | 2        | 4.17%   |
| Acer Aspire          | 2        | 4.17%   |
| Pegatron Pro         | 1        | 2.08%   |
| MSI MS-7B79          | 1        | 2.08%   |
| MSI MS-7B23          | 1        | 2.08%   |
| MSI MS-7B17          | 1        | 2.08%   |
| MSI MS-7A40          | 1        | 2.08%   |
| MSI MS-7984          | 1        | 2.08%   |
| MSI MS-7977          | 1        | 2.08%   |
| MSI MS-7974          | 1        | 2.08%   |
| MSI MS-7851          | 1        | 2.08%   |
| Lenovo V55t-15ARE    | 1        | 2.08%   |
| Intel DQ77MK         | 1        | 2.08%   |
| HP Z820              | 1        | 2.08%   |
| HP Z600              | 1        | 2.08%   |
| HP Pavilion          | 1        | 2.08%   |
| HP Compaq            | 1        | 2.08%   |
| Gigabyte Z68A-D3H-B3 | 1        | 2.08%   |
| Gigabyte H110M-S2H   | 1        | 2.08%   |
| Gigabyte B85M-DS3H-A | 1        | 2.08%   |
| Gigabyte B450M       | 1        | 2.08%   |
| Gigabyte B450        | 1        | 2.08%   |
| Gateway DX4870       | 1        | 2.08%   |
| eMachines EL1352G    | 1        | 2.08%   |
| Digiboard NM70-TI    | 1        | 2.08%   |
| Dell XPS             | 1        | 2.08%   |
| Dell OptiPlex        | 1        | 2.08%   |
| Dell Inspiron        | 1        | 2.08%   |
| Dell DXP051          | 1        | 2.08%   |
| ASUS ROG             | 1        | 2.08%   |
| ASUS P8H77-V         | 1        | 2.08%   |
| ASUS P8H77-M         | 1        | 2.08%   |
| ASUS P6T             | 1        | 2.08%   |
| ASUS P5QPL-AM        | 1        | 2.08%   |
| ASUS P5K-E           | 1        | 2.08%   |
| ASUS P5G41T-M        | 1        | 2.08%   |
| ASUS BM6820          | 1        | 2.08%   |
| ASRock H61M-DGS      | 1        | 2.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 9        | 18.75%  |
| 2018 | 8        | 16.67%  |
| 2015 | 5        | 10.42%  |
| 2021 | 3        | 6.25%   |
| 2017 | 3        | 6.25%   |
| 2010 | 3        | 6.25%   |
| 2009 | 3        | 6.25%   |
| 2022 | 2        | 4.17%   |
| 2019 | 2        | 4.17%   |
| 2013 | 2        | 4.17%   |
| 2007 | 2        | 4.17%   |
| 2006 | 2        | 4.17%   |
| 2020 | 1        | 2.08%   |
| 2016 | 1        | 2.08%   |
| 2011 | 1        | 2.08%   |
| 2008 | 1        | 2.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 48       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 48       | 97.96%  |
| Enabled  | 1        | 2.04%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 48       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 11       | 22.45%  |
| 16.01-24.0  | 10       | 20.41%  |
| 8.01-16.0   | 9        | 18.37%  |
| 32.01-64.0  | 6        | 12.24%  |
| 3.01-4.0    | 6        | 12.24%  |
| 24.01-32.0  | 3        | 6.12%   |
| 1.01-2.0    | 3        | 6.12%   |
| 64.01-256.0 | 1        | 2.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 18       | 37.5%   |
| 2.01-3.0  | 14       | 29.17%  |
| 4.01-8.0  | 7        | 14.58%  |
| 3.01-4.0  | 6        | 12.5%   |
| 0.51-1.0  | 2        | 4.17%   |
| 8.01-16.0 | 1        | 2.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 21       | 43.75%  |
| 3      | 11       | 22.92%  |
| 2      | 8        | 16.67%  |
| 4      | 5        | 10.42%  |
| 5      | 2        | 4.17%   |
| 6      | 1        | 2.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 24       | 50%     |
| No        | 24       | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 48       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 56.25%  |
| Yes       | 21       | 43.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 75%     |
| Yes       | 12       | 25%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 12       | 25%     |
| Brazil    | 5        | 10.42%  |
| Russia    | 4        | 8.33%   |
| Italy     | 4        | 8.33%   |
| France    | 4        | 8.33%   |
| UK        | 2        | 4.17%   |
| Sweden    | 2        | 4.17%   |
| Spain     | 2        | 4.17%   |
| Poland    | 2        | 4.17%   |
| Germany   | 2        | 4.17%   |
| Canada    | 2        | 4.17%   |
| Australia | 2        | 4.17%   |
| Venezuela | 1        | 2.08%   |
| Turkey    | 1        | 2.08%   |
| Nicaragua | 1        | 2.08%   |
| Mexico    | 1        | 2.08%   |
| Latvia    | 1        | 2.08%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Melbourne                | 2        | 4.17%   |
| Volta Redonda            | 1        | 2.08%   |
| Vitória da Conquista    | 1        | 2.08%   |
| Vincennes                | 1        | 2.08%   |
| Vicente Guerrero         | 1        | 2.08%   |
| Trieste                  | 1        | 2.08%   |
| Tolyatti                 | 1        | 2.08%   |
| Toledo                   | 1        | 2.08%   |
| Toccoa                   | 1        | 2.08%   |
| Tacoma                   | 1        | 2.08%   |
| Stockbridge              | 1        | 2.08%   |
| Spruce Grove             | 1        | 2.08%   |
| Sollentuna               | 1        | 2.08%   |
| Sant Feliu de Llobregat  | 1        | 2.08%   |
| San Antonio de Los Altos | 1        | 2.08%   |
| San Antonio              | 1        | 2.08%   |
| Rome                     | 1        | 2.08%   |
| Riga                     | 1        | 2.08%   |
| Reynoldsburg             | 1        | 2.08%   |
| Rennes                   | 1        | 2.08%   |
| Queensbury               | 1        | 2.08%   |
| Prestatyn                | 1        | 2.08%   |
| Porto Uniao              | 1        | 2.08%   |
| Porto Alegre             | 1        | 2.08%   |
| Piaseczno                | 1        | 2.08%   |
| Orekhovo-Zuyevo          | 1        | 2.08%   |
| North Manchester         | 1        | 2.08%   |
| National City            | 1        | 2.08%   |
| Naples                   | 1        | 2.08%   |
| Moscow                   | 1        | 2.08%   |
| Montreal                 | 1        | 2.08%   |
| Milan                    | 1        | 2.08%   |
| Managua                  | 1        | 2.08%   |
| Madrid                   | 1        | 2.08%   |
| Krakow                   | 1        | 2.08%   |
| Hamburg                  | 1        | 2.08%   |
| Frankfurt am Main        | 1        | 2.08%   |
| Farmington               | 1        | 2.08%   |
| Detroit                  | 1        | 2.08%   |
| Cournonterral            | 1        | 2.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 24     | 19.23%  |
| Seagate             | 14       | 18     | 17.95%  |
| Samsung Electronics | 12       | 20     | 15.38%  |
| Crucial             | 6        | 6      | 7.69%   |
| Toshiba             | 5        | 5      | 6.41%   |
| Kingston            | 5        | 5      | 6.41%   |
| SanDisk             | 4        | 4      | 5.13%   |
| Hitachi             | 4        | 5      | 5.13%   |
| A-DATA Technology   | 2        | 2      | 2.56%   |
| XrayDisk            | 1        | 2      | 1.28%   |
| Transcend           | 1        | 2      | 1.28%   |
| SK hynix            | 1        | 1      | 1.28%   |
| OCZ-VERTEX          | 1        | 1      | 1.28%   |
| Netac               | 1        | 1      | 1.28%   |
| Intel               | 1        | 1      | 1.28%   |
| Hewlett-Packard     | 1        | 1      | 1.28%   |
| GOODRAM             | 1        | 1      | 1.28%   |
| China               | 1        | 1      | 1.28%   |
| ASMedia             | 1        | 1      | 1.28%   |
| 2.5''               | 1        | 1      | 1.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB             | 4        | 4.3%    |
| Crucial CT480BX500SSD1 480GB          | 3        | 3.23%   |
| WDC WD10EZEX-08WN4A0 1TB              | 2        | 2.15%   |
| Seagate ST2000DM008-2FR102 2TB        | 2        | 2.15%   |
| Seagate ST1000DM003-1CH162 1TB        | 2        | 2.15%   |
| Samsung SSD 850 EVO 500GB             | 2        | 2.15%   |
| Samsung NVMe SSD Drive 500GB          | 2        | 2.15%   |
| Samsung NVMe SSD Drive 250GB          | 2        | 2.15%   |
| Kingston SA400S37240G 240GB SSD       | 2        | 2.15%   |
| XrayDisk 480GB                        | 1        | 1.08%   |
| XrayDisk 1TB                          | 1        | 1.08%   |
| WDC WD60EZAZ-00ZGHB0 6TB              | 1        | 1.08%   |
| WDC WD5000AZLX-08K2TA0 500GB          | 1        | 1.08%   |
| WDC WD5000AAKX-75U6AA0 500GB          | 1        | 1.08%   |
| WDC WD5000AAKX-22ERMA0 500GB          | 1        | 1.08%   |
| WDC WD40EZAZ-00SF3B0 4TB              | 1        | 1.08%   |
| WDC WD3200AAJS-22B4A0 320GB           | 1        | 1.08%   |
| WDC WD30EFRX-68EUZN0 3TB              | 1        | 1.08%   |
| WDC WD3003FZEX-00Z4SA0 3TB            | 1        | 1.08%   |
| WDC WD20SPZX-00UA7T0 2TB              | 1        | 1.08%   |
| WDC WD1600HLHX-60JJPV1 160GB          | 1        | 1.08%   |
| WDC WD1600AAJS-07PSA0 160GB           | 1        | 1.08%   |
| WDC WD10EZEX-22BN5A0 1TB              | 1        | 1.08%   |
| WDC WD10EFRX-68JCSN0 1TB              | 1        | 1.08%   |
| WDC WD10EFRX-68FYTN0 1TB              | 1        | 1.08%   |
| WDC WD10EAVS-00D7B0 1TB               | 1        | 1.08%   |
| WDC WD1003FZEX-00MK2A0 1TB            | 1        | 1.08%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 1        | 1.08%   |
| Transcend TS480GSSD220S 480GB         | 1        | 1.08%   |
| Transcend TS240GSSD220S 240GB         | 1        | 1.08%   |
| Toshiba THNSNJ128GCSU 128GB SSD       | 1        | 1.08%   |
| Toshiba MK3275GSX 320GB               | 1        | 1.08%   |
| Toshiba HDWD110 1TB                   | 1        | 1.08%   |
| Toshiba DT01ACA200 2TB                | 1        | 1.08%   |
| Toshiba DT01ACA050 500GB              | 1        | 1.08%   |
| SK hynix HFS256G32MND-3310A 256GB SSD | 1        | 1.08%   |
| Seagate ST500LT012-1DG142 500GB       | 1        | 1.08%   |
| Seagate ST3500418AS 500GB             | 1        | 1.08%   |
| Seagate ST3500312CS 500GB             | 1        | 1.08%   |
| Seagate ST3320620NS 320GB             | 1        | 1.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 24     | 37.5%   |
| Seagate             | 14       | 18     | 35%     |
| Toshiba             | 4        | 4      | 10%     |
| Hitachi             | 4        | 5      | 10%     |
| Samsung Electronics | 2        | 2      | 5%      |
| ASMedia             | 1        | 1      | 2.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 10     | 22.58%  |
| Crucial             | 6        | 6      | 19.35%  |
| Kingston            | 4        | 4      | 12.9%   |
| SanDisk             | 3        | 3      | 9.68%   |
| A-DATA Technology   | 2        | 2      | 6.45%   |
| Transcend           | 1        | 2      | 3.23%   |
| Toshiba             | 1        | 1      | 3.23%   |
| SK hynix            | 1        | 1      | 3.23%   |
| OCZ-VERTEX          | 1        | 1      | 3.23%   |
| Netac               | 1        | 1      | 3.23%   |
| Hewlett-Packard     | 1        | 1      | 3.23%   |
| GOODRAM             | 1        | 1      | 3.23%   |
| China               | 1        | 1      | 3.23%   |
| 2.5''               | 1        | 1      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 35       | 54     | 48.61%  |
| SSD     | 28       | 35     | 38.89%  |
| NVMe    | 8        | 11     | 11.11%  |
| Unknown | 1        | 2      | 1.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 47       | 88     | 82.46%  |
| NVMe | 8        | 11     | 14.04%  |
| SAS  | 2        | 3      | 3.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 39       | 56     | 62.9%   |
| 0.51-1.0   | 13       | 19     | 20.97%  |
| 1.01-2.0   | 6        | 7      | 9.68%   |
| 2.01-3.0   | 2        | 5      | 3.23%   |
| 3.01-4.0   | 1        | 1      | 1.61%   |
| 4.01-10.0  | 1        | 1      | 1.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 12       | 25%     |
| 101-250        | 10       | 20.83%  |
| 1001-2000      | 10       | 20.83%  |
| 501-1000       | 5        | 10.42%  |
| 2001-3000      | 3        | 6.25%   |
| 1-20           | 3        | 6.25%   |
| More than 3000 | 2        | 4.17%   |
| 51-100         | 2        | 4.17%   |
| 21-50          | 1        | 2.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 19       | 38.78%  |
| 21-50     | 8        | 16.33%  |
| 251-500   | 6        | 12.24%  |
| 501-1000  | 5        | 10.2%   |
| 1001-2000 | 4        | 8.16%   |
| 51-100    | 4        | 8.16%   |
| 101-250   | 3        | 6.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB | 1        | 1      | 50%     |
| Seagate ST3250318AS 250GB       | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 2      | 100%    |

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
| Detected | 36       | 74     | 70.59%  |
| Works    | 13       | 26     | 25.49%  |
| Malfunc  | 2        | 2      | 3.92%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 37       | 57.81%  |
| AMD                         | 10       | 15.63%  |
| Samsung Electronics         | 5        | 7.81%   |
| Nvidia                      | 2        | 3.13%   |
| JMicron Technology          | 2        | 3.13%   |
| Broadcom / LSI              | 2        | 3.13%   |
| ASMedia Technology          | 2        | 3.13%   |
| SanDisk                     | 1        | 1.56%   |
| Marvell Technology Group    | 1        | 1.56%   |
| LSI Logic / Symbios Logic   | 1        | 1.56%   |
| Kingston Technology Company | 1        | 1.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 7        | 8.33%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 7.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 4.76%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 4.76%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 3.57%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 3.57%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 3.57%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 2.38%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2        | 2.38%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 2.38%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 2.38%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 2.38%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 2.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 2.38%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 2.38%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 2.38%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 2.38%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 1.19%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.19%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 1.19%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 1        | 1.19%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 1.19%   |
| Nvidia MCP61 IDE                                                                        | 1        | 1.19%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                   | 1        | 1.19%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2008 [Falcon]                                    | 1        | 1.19%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1        | 1.19%   |
| Intel SSD 600P Series                                                                   | 1        | 1.19%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1        | 1.19%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 1.19%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 1.19%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 1.19%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 1.19%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.19%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.19%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 1        | 1.19%   |
| Intel 82801EB (ICH5) SATA Controller                                                    | 1        | 1.19%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1        | 1.19%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 40       | 59.7%   |
| IDE  | 13       | 19.4%   |
| NVMe | 8        | 11.94%  |
| RAID | 4        | 5.97%   |
| SAS  | 1        | 1.49%   |
| SCSI | 1        | 1.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 36       | 75%     |
| AMD    | 12       | 25%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 6.25%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 2        | 4.17%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 4.17%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 2        | 4.17%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2        | 4.17%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 4.17%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 4.17%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 4.17%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1        | 2.08%   |
| Intel Xeon CPU X5570 @ 2.93GHz              | 1        | 2.08%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1        | 2.08%   |
| Intel Xeon CPU 3.40GHz                      | 1        | 2.08%   |
| Intel Pentium Gold G7400                    | 1        | 2.08%   |
| Intel Pentium D CPU 3.40GHz                 | 1        | 2.08%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 2.08%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 2.08%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 2.08%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1        | 2.08%   |
| Intel Core i5-3470S CPU @ 2.90GHz           | 1        | 2.08%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 1        | 2.08%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 2.08%   |
| Intel Core i3-4340 CPU @ 3.60GHz            | 1        | 2.08%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 2.08%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 2.08%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 1        | 2.08%   |
| Intel Core 2 CPU 4300 @ 1.80GHz             | 1        | 2.08%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 1        | 2.08%   |
| Intel 12th Gen Core i3-12100F               | 1        | 2.08%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 1        | 2.08%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 1        | 2.08%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 1        | 2.08%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 1        | 2.08%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 1        | 2.08%   |
| AMD Ryzen 5 3350G with Radeon Vega Graphics | 1        | 2.08%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 1        | 2.08%   |
| AMD FX-4300 Quad-Core Processor             | 1        | 2.08%   |
| AMD Athlon II X2 220 Processor              | 1        | 2.08%   |
| AMD Athlon II X2 215 Processor              | 1        | 2.08%   |
| AMD Athlon 220GE with Radeon Vega Graphics  | 1        | 2.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 8        | 16.67%  |
| Intel Core i7           | 7        | 14.58%  |
| Intel Xeon              | 6        | 12.5%   |
| Intel Pentium           | 3        | 6.25%   |
| AMD Ryzen 5             | 3        | 6.25%   |
| AMD Ryzen 3             | 3        | 6.25%   |
| Other                   | 2        | 4.17%   |
| Intel Pentium Dual-Core | 2        | 4.17%   |
| Intel Core i3           | 2        | 4.17%   |
| AMD Ryzen 7             | 2        | 4.17%   |
| AMD Athlon II X2        | 2        | 4.17%   |
| Intel Pentium Gold      | 1        | 2.08%   |
| Intel Pentium D         | 1        | 2.08%   |
| Intel Core 2 Quad       | 1        | 2.08%   |
| Intel Core 2 Duo        | 1        | 2.08%   |
| Intel Core 2            | 1        | 2.08%   |
| Intel Celeron           | 1        | 2.08%   |
| AMD FX                  | 1        | 2.08%   |
| AMD Athlon              | 1        | 2.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 19       | 39.58%  |
| 2      | 17       | 35.42%  |
| 8      | 5        | 10.42%  |
| 6      | 5        | 10.42%  |
| 16     | 2        | 4.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 44       | 91.67%  |
| 2      | 4        | 8.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 25       | 52.08%  |
| 2      | 23       | 47.92%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 48       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306a9    | 7        | 14.58%  |
| 0x206a7    | 5        | 10.42%  |
| 0x506e3    | 3        | 6.25%   |
| 0x1067a    | 3        | 6.25%   |
| 0x08108109 | 3        | 6.25%   |
| 0x906ed    | 2        | 4.17%   |
| 0x90675    | 2        | 4.17%   |
| 0x306c3    | 2        | 4.17%   |
| 0x206d7    | 2        | 4.17%   |
| 0x08101016 | 2        | 4.17%   |
| Unknown    | 2        | 4.17%   |
| 0xf65      | 1        | 2.08%   |
| 0xf43      | 1        | 2.08%   |
| 0xa0671    | 1        | 2.08%   |
| 0xa0653    | 1        | 2.08%   |
| 0x906ea    | 1        | 2.08%   |
| 0x6fd      | 1        | 2.08%   |
| 0x6f2      | 1        | 2.08%   |
| 0x206c2    | 1        | 2.08%   |
| 0x106a5    | 1        | 2.08%   |
| 0x0a50000b | 1        | 2.08%   |
| 0x08701021 | 1        | 2.08%   |
| 0x0810100b | 1        | 2.08%   |
| 0x08001137 | 1        | 2.08%   |
| 0x06000852 | 1        | 2.08%   |
| 0x010000c8 | 1        | 2.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| IvyBridge   | 8        | 16.67%  |
| SandyBridge | 7        | 14.58%  |
| Zen         | 4        | 8.33%   |
| Zen+        | 3        | 6.25%   |
| Skylake     | 3        | 6.25%   |
| Penryn      | 3        | 6.25%   |
| KabyLake    | 3        | 6.25%   |
| Unknown     | 3        | 6.25%   |
| NetBurst    | 2        | 4.17%   |
| K10         | 2        | 4.17%   |
| Haswell     | 2        | 4.17%   |
| Core        | 2        | 4.17%   |
| Zen 3       | 1        | 2.08%   |
| Zen 2       | 1        | 2.08%   |
| Westmere    | 1        | 2.08%   |
| Piledriver  | 1        | 2.08%   |
| Nehalem     | 1        | 2.08%   |
| CometLake   | 1        | 2.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 30       | 56.6%   |
| Intel  | 14       | 26.42%  |
| AMD    | 9        | 16.98%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GT218 [GeForce 210]                                                  | 4        | 7.41%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 7.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 7.41%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 5.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 5.56%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 5.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 5.56%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 3.7%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 3.7%    |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 3.7%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.85%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.85%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 1.85%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 1.85%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.85%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.85%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 1.85%   |
| Nvidia GF119 [NVS 310]                                                      | 1        | 1.85%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.85%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 1.85%   |
| Nvidia G92 [GeForce 8800 GT]                                                | 1        | 1.85%   |
| Nvidia G72 [GeForce 7300 LE]                                                | 1        | 1.85%   |
| Nvidia C78 [GeForce 9100]                                                   | 1        | 1.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 1.85%   |
| Intel VGA compatible controller                                             | 1        | 1.85%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 1.85%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.85%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 1.85%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.85%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 1        | 1.85%   |
| AMD Lexa XT [Radeon PRO WX 3200]                                            | 1        | 1.85%   |
| AMD Cezanne                                                                 | 1        | 1.85%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 1.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 27       | 55.1%   |
| 1 x Intel      | 12       | 24.49%  |
| 1 x AMD        | 5        | 10.2%   |
| AMD + Nvidia   | 3        | 6.12%   |
| 2 x AMD        | 1        | 2.04%   |
| Intel + Nvidia | 1        | 2.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 30       | 62.5%   |
| Proprietary | 12       | 25%     |
| Unknown     | 6        | 12.5%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 17       | 35.42%  |
| 1.01-2.0   | 11       | 22.92%  |
| 3.01-4.0   | 8        | 16.67%  |
| 0.01-0.5   | 7        | 14.58%  |
| 0.51-1.0   | 4        | 8.33%   |
| 5.01-6.0   | 1        | 2.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 7        | 17.5%   |
| BenQ                 | 6        | 15%     |
| Philips              | 3        | 7.5%    |
| Goldstar             | 3        | 7.5%    |
| Dell                 | 3        | 7.5%    |
| Ancor Communications | 3        | 7.5%    |
| Acer                 | 3        | 7.5%    |
| Unknown              | 2        | 5%      |
| Hewlett-Packard      | 2        | 5%      |
| AOC                  | 2        | 5%      |
| ___                  | 1        | 2.5%    |
| PLN                  | 1        | 2.5%    |
| Medion               | 1        | 2.5%    |
| Lenovo               | 1        | 2.5%    |
| Iiyama               | 1        | 2.5%    |
| ASUSTek Computer     | 1        | 2.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ___ LCDTV16 ___0101 1920x1080                                         | 1        | 2.33%   |
| Unknown LCDTV14 0101 1360x768 1600x900mm 72.3-inch                    | 1        | 2.33%   |
| Unknown LCD Monitor SAMSUNG 1366x768                                  | 1        | 2.33%   |
| Samsung Electronics SyncMaster SAM0259 1280x1024 380x300mm 19.1-inch  | 1        | 2.33%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch    | 1        | 2.33%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 1        | 2.33%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1        | 2.33%   |
| Samsung Electronics LCD Monitor SMBX2331 1920x1080                    | 1        | 2.33%   |
| Samsung Electronics LCD Monitor S27R65 3840x1080                      | 1        | 2.33%   |
| Samsung Electronics LCD Monitor S27R65                                | 1        | 2.33%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch    | 1        | 2.33%   |
| PLN LCD Monitor PXL2790MW 1920x1080                                   | 1        | 2.33%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch             | 1        | 2.33%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch               | 1        | 2.33%   |
| Philips LCD Monitor PHL 242V8 1920x1080                               | 1        | 2.33%   |
| Medion MD20328 MED3942 1600x900 462x272mm 21.1-inch                   | 1        | 2.33%   |
| Lenovo C24-20 LEN62A8 1920x1080 527x296mm 23.8-inch                   | 1        | 2.33%   |
| Iiyama PL2792H IVM664F 1920x1080 600x340mm 27.2-inch                  | 1        | 2.33%   |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch           | 1        | 2.33%   |
| Hewlett-Packard E232 HWP327B 1920x1080 509x286mm 23.0-inch            | 1        | 2.33%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch            | 1        | 2.33%   |
| Hewlett-Packard E232 HWP3279 1920x1080 509x286mm 23.0-inch            | 1        | 2.33%   |
| Goldstar ULTRAWIDE GSM7770 2560x1080 798x334mm 34.1-inch              | 1        | 2.33%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 1        | 2.33%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 600x340mm 27.2-inch                | 1        | 2.33%   |
| Dell E228WFP DELD015 1680x1050 473x296mm 22.0-inch                    | 1        | 2.33%   |
| Dell E178WFP DELD016 1440x900 370x230mm 17.2-inch                     | 1        | 2.33%   |
| Dell 2007WFP DELA019 1680x1050 434x270mm 20.1-inch                    | 1        | 2.33%   |
| BenQ PD2500Q BNQ802A 2560x1440 550x310mm 24.9-inch                    | 1        | 2.33%   |
| BenQ LCD Monitor ZOWIE XL LCD 1920x1080                               | 1        | 2.33%   |
| BenQ LCD Monitor XL2411Z 1920x1080                                    | 1        | 2.33%   |
| BenQ GW2280 BNQ78E8 1920x1080 480x270mm 21.7-inch                     | 1        | 2.33%   |
| BenQ GL2750H BNQ78AD 1920x1080 598x336mm 27.0-inch                    | 1        | 2.33%   |
| BenQ EW277HDR BNQ7948 1920x1080 598x336mm 27.0-inch                   | 1        | 2.33%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch          | 1        | 2.33%   |
| AOC LCD Monitor 2251w 1920x1080                                       | 1        | 2.33%   |
| AOC 1943W AOC1943 1366x768 410x230mm 18.5-inch                        | 1        | 2.33%   |
| Ancor Communications VW246 ACI24F2 1920x1080 531x299mm 24.0-inch      | 1        | 2.33%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch      | 1        | 2.33%   |
| Ancor Communications ASUS MX299 ACI2931 2560x1080 673x284mm 28.8-inch | 1        | 2.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 20       | 54.05%  |
| 1680x1050 (WSXGA+) | 4        | 10.81%  |
| 1600x900 (HD+)     | 3        | 8.11%   |
| 2560x1440 (QHD)    | 2        | 5.41%   |
| 2560x1080          | 2        | 5.41%   |
| 1366x768 (WXGA)    | 2        | 5.41%   |
| 3840x1080          | 1        | 2.7%    |
| 1440x900 (WXGA+)   | 1        | 2.7%    |
| 1280x1024 (SXGA)   | 1        | 2.7%    |
| Unknown            | 1        | 2.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 10       | 25.64%  |
| 24      | 5        | 12.82%  |
| 21      | 5        | 12.82%  |
| 27      | 3        | 7.69%   |
| 23      | 3        | 7.69%   |
| 20      | 3        | 7.69%   |
| 22      | 2        | 5.13%   |
| 72      | 1        | 2.56%   |
| 34      | 1        | 2.56%   |
| 32      | 1        | 2.56%   |
| 28      | 1        | 2.56%   |
| 25      | 1        | 2.56%   |
| 19      | 1        | 2.56%   |
| 18      | 1        | 2.56%   |
| 17      | 1        | 2.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 11       | 29.73%  |
| 401-500     | 10       | 27.03%  |
| Unknown     | 10       | 27.03%  |
| 701-800     | 2        | 5.41%   |
| 351-400     | 2        | 5.41%   |
| 601-700     | 1        | 2.7%    |
| 1501-2000   | 1        | 2.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 19       | 52.78%  |
| Unknown | 10       | 27.78%  |
| 16/10   | 4        | 11.11%  |
| 21/9    | 2        | 5.56%   |
| 5/4     | 1        | 2.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 13       | 34.21%  |
| Unknown        | 10       | 26.32%  |
| 151-200        | 4        | 10.53%  |
| 301-350        | 3        | 7.89%   |
| 251-300        | 3        | 7.89%   |
| 351-500        | 2        | 5.26%   |
| More than 1000 | 1        | 2.63%   |
| 141-150        | 1        | 2.63%   |
| 131-140        | 1        | 2.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 21       | 56.76%  |
| Unknown | 10       | 27.03%  |
| 101-120 | 5        | 13.51%  |
| 1-50    | 1        | 2.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 37       | 77.08%  |
| 0     | 5        | 10.42%  |
| 2     | 4        | 8.33%   |
| 3     | 2        | 4.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 27       | 39.13%  |
| Intel                    | 22       | 31.88%  |
| Qualcomm Atheros         | 6        | 8.7%    |
| Samsung Electronics      | 2        | 2.9%    |
| Ralink Technology        | 2        | 2.9%    |
| Nvidia                   | 2        | 2.9%    |
| Broadcom                 | 2        | 2.9%    |
| TP-Link                  | 1        | 1.45%   |
| NetGear                  | 1        | 1.45%   |
| Mercucys                 | 1        | 1.45%   |
| Marvell Technology Group | 1        | 1.45%   |
| Huawei Technologies      | 1        | 1.45%   |
| Belkin Components        | 1        | 1.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 21       | 25.93%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 6        | 7.41%   |
| Intel Ethernet Connection (7) I219-V                                                          | 3        | 3.7%    |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 2        | 2.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2        | 2.47%   |
| Realtek 802.11ac NIC                                                                          | 2        | 2.47%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 2.47%   |
| Intel 82579V Gigabit Network Connection                                                       | 2        | 2.47%   |
| Intel 82574L Gigabit Network Connection                                                       | 2        | 2.47%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 1.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.23%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.23%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 1.23%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1        | 1.23%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 1.23%   |
| Realtek RTL8187 Wireless Adapter                                                              | 1        | 1.23%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 1        | 1.23%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 1        | 1.23%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.23%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 1        | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 1.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 1.23%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                                      | 1        | 1.23%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1        | 1.23%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                                | 1        | 1.23%   |
| Nvidia MCP77 Ethernet                                                                         | 1        | 1.23%   |
| Nvidia MCP61 Ethernet                                                                         | 1        | 1.23%   |
| NetGear A6150                                                                                 | 1        | 1.23%   |
| Mercucys MW300UM RTL8192EU wifi                                                               | 1        | 1.23%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                       | 1        | 1.23%   |
| Intel Wireless-AC 9260                                                                        | 1        | 1.23%   |
| Intel Wi-Fi 6 AX200                                                                           | 1        | 1.23%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 1        | 1.23%   |
| Intel I211 Gigabit Network Connection                                                         | 1        | 1.23%   |
| Intel I210 Gigabit Fiber Network Connection                                                   | 1        | 1.23%   |
| Intel Ethernet Connection (2) I219-V                                                          | 1        | 1.23%   |
| Intel Ethernet Connection (17) I219-V                                                         | 1        | 1.23%   |
| Intel Ethernet Connection (14) I219-V                                                         | 1        | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 1.23%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 10       | 41.67%  |
| Intel                 | 5        | 20.83%  |
| Ralink Technology     | 2        | 8.33%   |
| Qualcomm Atheros      | 2        | 8.33%   |
| TP-Link               | 1        | 4.17%   |
| NetGear               | 1        | 4.17%   |
| Mercucys              | 1        | 4.17%   |
| Broadcom              | 1        | 4.17%   |
| Belkin Components     | 1        | 4.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2        | 8%      |
| Realtek 802.11ac NIC                                                                          | 2        | 8%      |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 8%      |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 4%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 4%      |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 4%      |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 4%      |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1        | 4%      |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 4%      |
| Realtek RTL8187 Wireless Adapter                                                              | 1        | 4%      |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 4%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 4%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 4%      |
| NetGear A6150                                                                                 | 1        | 4%      |
| Mercucys MW300UM RTL8192EU wifi                                                               | 1        | 4%      |
| Intel Wireless-AC 9260                                                                        | 1        | 4%      |
| Intel Wi-Fi 6 AX200                                                                           | 1        | 4%      |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 1        | 4%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 4%      |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 4%      |
| Broadcom BCM4321 802.11a/b/g/n                                                                | 1        | 4%      |
| Belkin Components F9L1101v2 802.11abgn Wireless Adapter [Realtek RTL8192DU]                   | 1        | 4%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 23       | 43.4%   |
| Intel                    | 19       | 35.85%  |
| Qualcomm Atheros         | 4        | 7.55%   |
| Samsung Electronics      | 2        | 3.77%   |
| Nvidia                   | 2        | 3.77%   |
| Marvell Technology Group | 1        | 1.89%   |
| Huawei Technologies      | 1        | 1.89%   |
| Broadcom                 | 1        | 1.89%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21       | 37.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 10.71%  |
| Intel Ethernet Connection (7) I219-V                              | 3        | 5.36%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 3.57%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 3.57%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 3.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.79%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.79%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.79%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 1.79%   |
| Nvidia MCP77 Ethernet                                             | 1        | 1.79%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.79%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.79%   |
| Intel I211 Gigabit Network Connection                             | 1        | 1.79%   |
| Intel I210 Gigabit Fiber Network Connection                       | 1        | 1.79%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.79%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 1.79%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.79%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1        | 1.79%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1        | 1.79%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 1.79%   |
| Intel 82545GM Gigabit Ethernet Controller                         | 1        | 1.79%   |
| Huawei YAL-L21                                                    | 1        | 1.79%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 48       | 69.57%  |
| WiFi     | 21       | 30.43%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 39       | 78%     |
| WiFi     | 11       | 22%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 33       | 68.75%  |
| 2     | 15       | 31.25%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 40       | 81.63%  |
| Yes  | 9        | 18.37%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 5        | 38.46%  |
| Cambridge Silicon Radio | 3        | 23.08%  |
| Realtek Semiconductor   | 2        | 15.38%  |
| Lite-On Technology      | 1        | 7.69%   |
| Dell                    | 1        | 7.69%   |
| Broadcom                | 1        | 7.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 23.08%  |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 7.69%   |
| Realtek Bluetooth Radio                             | 1        | 7.69%   |
| Lite-On Bluetooth Device                            | 1        | 7.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 7.69%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 7.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 7.69%   |
| Intel AX201 Bluetooth                               | 1        | 7.69%   |
| Intel AX200 Bluetooth                               | 1        | 7.69%   |
| Dell BT Mini-Receiver                               | 1        | 7.69%   |
| Broadcom BCM92045B3 ROM                             | 1        | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 34       | 44.74%  |
| Nvidia              | 28       | 36.84%  |
| AMD                 | 11       | 14.47%  |
| C-Media Electronics | 2        | 2.63%   |
| JMTek               | 1        | 1.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8        | 9.2%    |
| AMD Family 17h/19h HD Audio Controller                                     | 7        | 8.05%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6        | 6.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6        | 6.9%    |
| Nvidia High Definition Audio Controller                                    | 5        | 5.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 4.6%    |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 3.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 3.45%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 3.45%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 3.45%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 2.3%    |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 2.3%    |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 2.3%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 2.3%    |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 2.3%    |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 2.3%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2        | 2.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 2.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 2.3%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 2.3%    |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 1        | 1.15%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1.15%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 1.15%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 1.15%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 1.15%   |
| Nvidia GF116 High Definition Audio Controller                              | 1        | 1.15%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 1.15%   |
| JMTek USB PnP Audio Device                                                 | 1        | 1.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 1.15%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 1.15%   |
| Intel Audio device                                                         | 1        | 1.15%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                       | 1        | 1.15%   |
| C-Media Electronics REIYIN Audio                                           | 1        | 1.15%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                        | 1        | 1.15%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1        | 1.15%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 1.15%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 1.15%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 1.15%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 1.15%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 4        | 25%     |
| Unknown             | 2        | 12.5%   |
| Micron Technology   | 2        | 12.5%   |
| Smart               | 1        | 6.25%   |
| SK hynix            | 1        | 6.25%   |
| Nanya Technology    | 1        | 6.25%   |
| Kingston            | 1        | 6.25%   |
| G.Skill             | 1        | 6.25%   |
| Crucial             | 1        | 6.25%   |
| Corsair             | 1        | 6.25%   |
| A-DATA Technology   | 1        | 6.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                 | 1        | 5.88%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 1        | 5.88%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s    | 1        | 5.88%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2666MT/s     | 1        | 5.88%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 1        | 5.88%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s    | 1        | 5.88%   |
| Samsung RAM M393B1G70QH0-CMA 8GB DIMM DDR3 1600MT/s      | 1        | 5.88%   |
| Samsung RAM M393B1G70BH0-YK0 8GB DIMM DDR3 1600MT/s      | 1        | 5.88%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s     | 1        | 5.88%   |
| Nanya RAM NT1GT64U8HB0BY-3C 1GB DIMM DDR2 667MT/s        | 1        | 5.88%   |
| Micron RAM 18JSF1G72PZ-1G9E1 8GB DIMM DDR3 1866MT/s      | 1        | 5.88%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s     | 1        | 5.88%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 1        | 5.88%   |
| G.Skill RAM F4-3000C16-16GVRB 16GB DIMM DDR4 3200MT/s    | 1        | 5.88%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s    | 1        | 5.88%   |
| Corsair RAM CMZ16GX3M2A1600C10 8192MB DIMM DDR3 1600MT/s | 1        | 5.88%   |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3400MT/s             | 1        | 5.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 6        | 42.86%  |
| DDR4    | 5        | 35.71%  |
| SDRAM   | 1        | 7.14%   |
| DDR2    | 1        | 7.14%   |
| Unknown | 1        | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 12       | 85.71%  |
| SODIMM | 2        | 14.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 5        | 35.71%  |
| 4096  | 3        | 21.43%  |
| 16384 | 2        | 14.29%  |
| 2048  | 2        | 14.29%  |
| 32768 | 1        | 7.14%   |
| 1024  | 1        | 7.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 5        | 33.33%  |
| 667   | 2        | 13.33%  |
| 3600  | 1        | 6.67%   |
| 3400  | 1        | 6.67%   |
| 3200  | 1        | 6.67%   |
| 2667  | 1        | 6.67%   |
| 2666  | 1        | 6.67%   |
| 1866  | 1        | 6.67%   |
| 1334  | 1        | 6.67%   |
| 1333  | 1        | 6.67%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Konica Minolta     | 1        | 33.33%  |
| Hewlett-Packard    | 1        | 33.33%  |
| Brother Industries | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                 | Desktops | Percent |
|-----------------------|----------|---------|
| Konica Minolta 185    | 1        | 33.33%  |
| HP OfficeJet Pro 8730 | 1        | 33.33%  |
| Brother MFC-L2685DW   | 1        | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 110 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 4        | 36.36%  |
| Z-Star Microelectronics | 1        | 9.09%   |
| Pixart Imaging          | 1        | 9.09%   |
| OmniVision Technologies | 1        | 9.09%   |
| MacroSilicon            | 1        | 9.09%   |
| Creative Technology     | 1        | 9.09%   |
| ARC International       | 1        | 9.09%   |
| Alcor Micro             | 1        | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Z-Star Venus USB2.0 Camera                     | 1        | 9.09%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro           | 1        | 9.09%   |
| OmniVision Integrated Webcam for Dell XPS 2010 | 1        | 9.09%   |
| MacroSilicon USB Video                         | 1        | 9.09%   |
| Logitech Webcam C925e                          | 1        | 9.09%   |
| Logitech Webcam C270                           | 1        | 9.09%   |
| Logitech Webcam C210                           | 1        | 9.09%   |
| Logitech Logi Webcam C920e                     | 1        | 9.09%   |
| Creative Live! Cam Sync HD [VF0770]            | 1        | 9.09%   |
| ARC International Camera                       | 1        | 9.09%   |
| Alcor Micro USB 2.0 PC Camera                  | 1        | 9.09%   |

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
| 0     | 33       | 67.35%  |
| 1     | 15       | 30.61%  |
| 2     | 1        | 2.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Graphics card         | 8        | 47.06%  |
| Net/wireless          | 6        | 35.29%  |
| Unassigned class      | 1        | 5.88%   |
| Multimedia controller | 1        | 5.88%   |
| Camera                | 1        | 5.88%   |

