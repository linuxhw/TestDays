Gentoo 2.8 - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Gentoo 2.8.

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

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte | Z590 UD                     | [a5242ed058](https://linux-hardware.org/?probe=a5242ed058) | Feb 26, 2022 |
| Gigabyte | Z590 UD                     | [06d8d67698](https://linux-hardware.org/?probe=06d8d67698) | Feb 24, 2022 |
| Gigabyte | Z590 UD                     | [071dd25266](https://linux-hardware.org/?probe=071dd25266) | Feb 24, 2022 |
| ASUSTek  | ROG CROSSHAIR VIII DARK ... | [5836ccecc2](https://linux-hardware.org/?probe=5836ccecc2) | Feb 10, 2022 |
| Gigabyte | Z490 UD                     | [b571c22d4f](https://linux-hardware.org/?probe=b571c22d4f) | Feb 04, 2022 |
| MSI      | MPG B550 GAMING PLUS        | [d424a8e145](https://linux-hardware.org/?probe=d424a8e145) | Feb 01, 2022 |
| MSI      | MPG B550 GAMING PLUS        | [89dbe92caf](https://linux-hardware.org/?probe=89dbe92caf) | Feb 01, 2022 |
| ASRock   | AB350M Pro4                 | [6b7cf2d570](https://linux-hardware.org/?probe=6b7cf2d570) | Jan 27, 2022 |
| Gigabyte | B450M S2H                   | [656da02110](https://linux-hardware.org/?probe=656da02110) | Jan 24, 2022 |
| Gigabyte | B450M S2H                   | [1721bed3e1](https://linux-hardware.org/?probe=1721bed3e1) | Jan 24, 2022 |
| Gigabyte | Z490 UD                     | [eac4639ad2](https://linux-hardware.org/?probe=eac4639ad2) | Jan 22, 2022 |
| ASRock   | X370 Gaming X               | [e233d7c495](https://linux-hardware.org/?probe=e233d7c495) | Jan 09, 2022 |
| EVGA     | Z390 DARK                   | [7672395a1c](https://linux-hardware.org/?probe=7672395a1c) | Dec 24, 2021 |
| ASUSTek  | P5LD2-Deluxe                | [a2ee48eeb1](https://linux-hardware.org/?probe=a2ee48eeb1) | Dec 16, 2021 |
| MSI      | MPG Z690 EDGE WIFI DDR4     | [b92f432637](https://linux-hardware.org/?probe=b92f432637) | Dec 07, 2021 |
| MSI      | MPG Z690 EDGE WIFI DDR4     | [d8f50aaa2e](https://linux-hardware.org/?probe=d8f50aaa2e) | Dec 07, 2021 |
| ASUSTek  | TUF B450-PLUS GAMING        | [6649bea1f8](https://linux-hardware.org/?probe=6649bea1f8) | Dec 04, 2021 |
| ASUSTek  | TUF B450-PLUS GAMING        | [723e2a158a](https://linux-hardware.org/?probe=723e2a158a) | Dec 03, 2021 |
| ASRock   | H110M-HDV R3.0              | [e155882ffa](https://linux-hardware.org/?probe=e155882ffa) | Dec 02, 2021 |
| ASUSTek  | ROG STRIX X570-E GAMING     | [e2c087b9c7](https://linux-hardware.org/?probe=e2c087b9c7) | Nov 21, 2021 |
| ASUSTek  | PRIME X570-P                | [eafa22145d](https://linux-hardware.org/?probe=eafa22145d) | Nov 15, 2021 |
| ASUSTek  | TUF GAMING B550-PLUS        | [2900821ed3](https://linux-hardware.org/?probe=2900821ed3) | Nov 14, 2021 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [4cfb74fb42](https://linux-hardware.org/?probe=4cfb74fb42) | Nov 14, 2021 |
| ASUSTek  | ROG ZENITH II EXTREME       | [6f308039a8](https://linux-hardware.org/?probe=6f308039a8) | Nov 06, 2021 |
| MSI      | H110M PRO-D                 | [cb3dcdd186](https://linux-hardware.org/?probe=cb3dcdd186) | Nov 02, 2021 |
| MSI      | H110M PRO-D                 | [b53420c26a](https://linux-hardware.org/?probe=b53420c26a) | Nov 02, 2021 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [161865edb0](https://linux-hardware.org/?probe=161865edb0) | Oct 30, 2021 |
| ASUSTek  | ROG STRIX B550-F GAMING     | [a4806aa50f](https://linux-hardware.org/?probe=a4806aa50f) | Oct 30, 2021 |
| ASUSTek  | Z170-A                      | [aea7d9561e](https://linux-hardware.org/?probe=aea7d9561e) | Oct 29, 2021 |
| ASRock   | X370 Gaming X               | [0f4ae74d8e](https://linux-hardware.org/?probe=0f4ae74d8e) | Oct 29, 2021 |
| ASRock   | X370 Gaming X               | [f3f75352e4](https://linux-hardware.org/?probe=f3f75352e4) | Oct 29, 2021 |
| ASUSTek  | ROG CROSSHAIR VIII HERO     | [e9cc487951](https://linux-hardware.org/?probe=e9cc487951) | Oct 28, 2021 |
| ASUSTek  | ROG CROSSHAIR VIII HERO     | [cb6d9e548b](https://linux-hardware.org/?probe=cb6d9e548b) | Oct 26, 2021 |
| Gigabyte | X570 AORUS MASTER           | [58e3f9c07f](https://linux-hardware.org/?probe=58e3f9c07f) | Oct 23, 2021 |
| ASUSTek  | ROG CROSSHAIR VIII HERO     | [eb02a6d4d5](https://linux-hardware.org/?probe=eb02a6d4d5) | Oct 20, 2021 |
| ASRock   | X370 Killer SLI/ac          | [2e4c1c4527](https://linux-hardware.org/?probe=2e4c1c4527) | Oct 17, 2021 |
| Gigabyte | Z87X-UD3H-CF                | [9901023f19](https://linux-hardware.org/?probe=9901023f19) | Oct 03, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.15.10-gentoo               | 3        | 11.54%  |
| 5.14.12-gentoo               | 2        | 7.69%   |
| 6.0.0-Phaco-g8f10ff49057f    | 1        | 3.85%   |
| 5.16.7-tkg-cacule            | 1        | 3.85%   |
| 5.16.5-gentoo-dist           | 1        | 3.85%   |
| 5.16.4-gentoo                | 1        | 3.85%   |
| 5.16.2-gentoo                | 1        | 3.85%   |
| 5.16.10-gentoo-x86_64        | 1        | 3.85%   |
| 5.15.6-gentoo                | 1        | 3.85%   |
| 5.15.4-gentoo-deimos         | 1        | 3.85%   |
| 5.15.2-gentoo20210917        | 1        | 3.85%   |
| 5.15.2-gentoo-x86_64         | 1        | 3.85%   |
| 5.15.16-gentoo-dist          | 1        | 3.85%   |
| 5.15.1-gentoo-x86_64         | 1        | 3.85%   |
| 5.15.0-gentoo-x86_64         | 1        | 3.85%   |
| 5.14.6                       | 1        | 3.85%   |
| 5.14.15-gentoo20210917       | 1        | 3.85%   |
| 5.14.14-gentoo-x86_64        | 1        | 3.85%   |
| 5.14.14-gentoo               | 1        | 3.85%   |
| 5.14.13-gentoo               | 1        | 3.85%   |
| 5.14.11-zen1                 | 1        | 3.85%   |
| 5.10.84-gentoo-112-overlayfs | 1        | 3.85%   |
| 5.10.74-gentoo-x86_64        | 1        | 3.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.10 | 3        | 11.54%  |
| 5.15.2  | 2        | 7.69%   |
| 5.14.14 | 2        | 7.69%   |
| 5.14.12 | 2        | 7.69%   |
| 6.0.0   | 1        | 3.85%   |
| 5.16.7  | 1        | 3.85%   |
| 5.16.5  | 1        | 3.85%   |
| 5.16.4  | 1        | 3.85%   |
| 5.16.2  | 1        | 3.85%   |
| 5.16.10 | 1        | 3.85%   |
| 5.15.6  | 1        | 3.85%   |
| 5.15.4  | 1        | 3.85%   |
| 5.15.16 | 1        | 3.85%   |
| 5.15.1  | 1        | 3.85%   |
| 5.15.0  | 1        | 3.85%   |
| 5.14.6  | 1        | 3.85%   |
| 5.14.15 | 1        | 3.85%   |
| 5.14.13 | 1        | 3.85%   |
| 5.14.11 | 1        | 3.85%   |
| 5.10.84 | 1        | 3.85%   |
| 5.10.74 | 1        | 3.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 10       | 38.46%  |
| 5.14    | 8        | 30.77%  |
| 5.16    | 5        | 19.23%  |
| 5.10    | 2        | 7.69%   |
| 6.0     | 1        | 3.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 23       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDE5    | 13       | 54.17%  |
| GNOME   | 4        | 16.67%  |
| Unknown | 4        | 16.67%  |
| XFCE    | 2        | 8.33%   |
| LXQt    | 1        | 4.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 12       | 50%     |
| Wayland | 6        | 25%     |
| Tty     | 5        | 20.83%  |
| Unknown | 1        | 4.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 11       | 45.83%  |
| Unknown | 10       | 41.67%  |
| GDM     | 3        | 12.5%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 6        | 26.09%  |
| en_GB   | 6        | 26.09%  |
| ru_RU   | 2        | 8.7%    |
| pl_PL   | 2        | 8.7%    |
| sl_SI   | 1        | 4.35%   |
| fr_FR   | 1        | 4.35%   |
| es_ES   | 1        | 4.35%   |
| el_GR   | 1        | 4.35%   |
| de_DE   | 1        | 4.35%   |
| de_CH   | 1        | 4.35%   |
| Unknown | 1        | 4.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 19       | 79.17%  |
| BIOS | 5        | 20.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 12       | 52.17%  |
| Btrfs | 8        | 34.78%  |
| F2fs  | 2        | 8.7%    |
| Zfs   | 1        | 4.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 21       | 87.5%   |
| Unknown | 3        | 12.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 52.17%  |
| Yes       | 11       | 47.83%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 65.22%  |
| Yes       | 8        | 34.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 10       | 43.48%  |
| Gigabyte Technology | 5        | 21.74%  |
| ASRock              | 4        | 17.39%  |
| MSI                 | 3        | 13.04%  |
| EVGA                | 1        | 4.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| MSI MS-7D31                       | 1        | 4.35%   |
| MSI MS-7C56                       | 1        | 4.35%   |
| MSI MS-7996                       | 1        | 4.35%   |
| Gigabyte Z87X-UD3H                | 1        | 4.35%   |
| Gigabyte Z590 UD                  | 1        | 4.35%   |
| Gigabyte Z490 UD                  | 1        | 4.35%   |
| Gigabyte X570 AORUS MASTER        | 1        | 4.35%   |
| Gigabyte B450M S2H                | 1        | 4.35%   |
| EVGA Z390 DARK                    | 1        | 4.35%   |
| ASUS Z170-A                       | 1        | 4.35%   |
| ASUS TUF GAMING B550-PLUS         | 1        | 4.35%   |
| ASUS TUF B450-PLUS GAMING         | 1        | 4.35%   |
| ASUS ROG ZENITH II EXTREME        | 1        | 4.35%   |
| ASUS ROG STRIX X570-E GAMING      | 1        | 4.35%   |
| ASUS ROG STRIX B550-F GAMING      | 1        | 4.35%   |
| ASUS ROG CROSSHAIR VIII HERO      | 1        | 4.35%   |
| ASUS ROG CROSSHAIR VIII DARK HERO | 1        | 4.35%   |
| ASUS PRIME X570-P                 | 1        | 4.35%   |
| ASUS P5LD2-Deluxe                 | 1        | 4.35%   |
| ASRock X370 Killer SLI/ac         | 1        | 4.35%   |
| ASRock X370 Gaming X              | 1        | 4.35%   |
| ASRock H110M-HDV R3.0             | 1        | 4.35%   |
| ASRock AB350M Pro4                | 1        | 4.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS ROG           | 5        | 21.74%  |
| ASUS TUF           | 2        | 8.7%    |
| ASRock X370        | 2        | 8.7%    |
| MSI MS-7D31        | 1        | 4.35%   |
| MSI MS-7C56        | 1        | 4.35%   |
| MSI MS-7996        | 1        | 4.35%   |
| Gigabyte Z87X-UD3H | 1        | 4.35%   |
| Gigabyte Z590      | 1        | 4.35%   |
| Gigabyte Z490      | 1        | 4.35%   |
| Gigabyte X570      | 1        | 4.35%   |
| Gigabyte B450M     | 1        | 4.35%   |
| EVGA Z390          | 1        | 4.35%   |
| ASUS Z170-A        | 1        | 4.35%   |
| ASUS PRIME         | 1        | 4.35%   |
| ASUS P5LD2-Deluxe  | 1        | 4.35%   |
| ASRock H110M-HDV   | 1        | 4.35%   |
| ASRock AB350M      | 1        | 4.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 5        | 21.74%  |
| 2019 | 4        | 17.39%  |
| 2021 | 3        | 13.04%  |
| 2017 | 3        | 13.04%  |
| 2018 | 2        | 8.7%    |
| 2016 | 2        | 8.7%    |
| 2022 | 1        | 4.35%   |
| 2015 | 1        | 4.35%   |
| 2013 | 1        | 4.35%   |
| 2005 | 1        | 4.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 23       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 22       | 95.65%  |
| Enabled  | 1        | 4.35%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 23       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 10       | 43.48%  |
| 64.01-256.0 | 7        | 30.43%  |
| 16.01-24.0  | 3        | 13.04%  |
| 24.01-32.0  | 2        | 8.7%    |
| 2.01-3.0    | 1        | 4.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 8        | 33.33%  |
| 1.01-2.0   | 4        | 16.67%  |
| 8.01-16.0  | 4        | 16.67%  |
| 3.01-4.0   | 2        | 8.33%   |
| 2.01-3.0   | 2        | 8.33%   |
| 16.01-24.0 | 2        | 8.33%   |
| 24.01-32.0 | 1        | 4.17%   |
| 0.51-1.0   | 1        | 4.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 3      | 8        | 33.33%  |
| 5      | 4        | 16.67%  |
| 4      | 4        | 16.67%  |
| 2      | 3        | 12.5%   |
| 1      | 3        | 12.5%   |
| 7      | 1        | 4.17%   |
| 6      | 1        | 4.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 86.96%  |
| Yes       | 3        | 13.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 22       | 95.65%  |
| No        | 1        | 4.35%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 56.52%  |
| Yes       | 10       | 43.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 14       | 58.33%  |
| No        | 10       | 41.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 4        | 17.39%  |
| Poland      | 4        | 17.39%  |
| Russia      | 3        | 13.04%  |
| UK          | 2        | 8.7%    |
| Germany     | 2        | 8.7%    |
| Switzerland | 1        | 4.35%   |
| Spain       | 1        | 4.35%   |
| Slovenia    | 1        | 4.35%   |
| Mexico      | 1        | 4.35%   |
| Greece      | 1        | 4.35%   |
| France      | 1        | 4.35%   |
| Czechia     | 1        | 4.35%   |
| Bangladesh  | 1        | 4.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Swansea           | 2        | 8.33%   |
| Zurich            | 1        | 4.17%   |
| Vigo              | 1        | 4.17%   |
| Ufa               | 1        | 4.17%   |
| Svobodnyy         | 1        | 4.17%   |
| RzeszÃ³w        | 1        | 4.17%   |
| Redmond           | 1        | 4.17%   |
| Prague            | 1        | 4.17%   |
| Orange            | 1        | 4.17%   |
| Moscow            | 1        | 4.17%   |
| Morcenx           | 1        | 4.17%   |
| Monroe            | 1        | 4.17%   |
| Laziska Gorne     | 1        | 4.17%   |
| Kulmbach          | 1        | 4.17%   |
| Krakow            | 1        | 4.17%   |
| IvanÄna Gorica | 1        | 4.17%   |
| Glen Ellyn        | 1        | 4.17%   |
| Essen             | 1        | 4.17%   |
| Dhaka             | 1        | 4.17%   |
| Ciudad JuÃ¡rez  | 1        | 4.17%   |
| Cieszyn           | 1        | 4.17%   |
| Blagoveshchensk   | 1        | 4.17%   |
| Athens            | 1        | 4.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 26     | 26.79%  |
| Samsung Electronics | 12       | 21     | 21.43%  |
| Seagate             | 6        | 9      | 10.71%  |
| Toshiba             | 3        | 3      | 5.36%   |
| Hitachi             | 3        | 4      | 5.36%   |
| SanDisk             | 2        | 3      | 3.57%   |
| Intel               | 2        | 3      | 3.57%   |
| Crucial             | 2        | 6      | 3.57%   |
| Corsair             | 2        | 2      | 3.57%   |
| Team                | 1        | 2      | 1.79%   |
| PLEXTOR             | 1        | 2      | 1.79%   |
| Phison              | 1        | 1      | 1.79%   |
| OCZ-VERTEX          | 1        | 1      | 1.79%   |
| KIOXIA-EXCERIA      | 1        | 1      | 1.79%   |
| Kingston            | 1        | 1      | 1.79%   |
| Kingchuxing         | 1        | 2      | 1.79%   |
| GOODRAM             | 1        | 1      | 1.79%   |
| A-DATA Technology   | 1        | 1      | 1.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| WDC WD30EFRX-68EUZN0 3TB                   | 2        | 2.74%   |
| Toshiba DT01ACA100 1TB                     | 2        | 2.74%   |
| Samsung SSD 970 EVO Plus 250GB             | 2        | 2.74%   |
| WDC WDS500G2X0C-00L350 500GB               | 1        | 1.37%   |
| WDC WDS500G2B0B-00YS70 500GB SSD           | 1        | 1.37%   |
| WDC WDS500G2B0A-00SM50 500GB SSD           | 1        | 1.37%   |
| WDC WDS240G2G0A 240GB SSD                  | 1        | 1.37%   |
| WDC WD8003FFBX-68B9AN0 8TB                 | 1        | 1.37%   |
| WDC WD60EZRX-00MVLB1 6TB                   | 1        | 1.37%   |
| WDC WD60EFRX-68L0BN1 6TB                   | 1        | 1.37%   |
| WDC WD5000AZLX-00JKKA0 500GB               | 1        | 1.37%   |
| WDC WD30EFRX-68AX9N0 3TB                   | 1        | 1.37%   |
| WDC WD20EZRX-00D8PB0 2TB                   | 1        | 1.37%   |
| WDC WD20EFRX-68EUZN0 2TB                   | 1        | 1.37%   |
| WDC WD10PURX-64E5EY0 1TB                   | 1        | 1.37%   |
| WDC WD10EZEX-60WN4A1 1TB                   | 1        | 1.37%   |
| WDC WD10EZEX-22M                           | 1        | 1.37%   |
| WDC WD10EZEX-08WN4A0 1TB                   | 1        | 1.37%   |
| WDC WD10EZEX-08M2NA0 1TB                   | 1        | 1.37%   |
| WDC WD10EARS-00MVWB0 1TB                   | 1        | 1.37%   |
| WDC WD10EADS-00L5B1 1TB                    | 1        | 1.37%   |
| WDC WD1002FBYS-18W8B0 1TB                  | 1        | 1.37%   |
| Toshiba THNSN5512GPUK NVMe 512GB           | 1        | 1.37%   |
| Team TM8FP2240G 240GB                      | 1        | 1.37%   |
| Seagate ST8000DM004-2CX188 8TB             | 1        | 1.37%   |
| Seagate ST4000DM005-2DP166 4TB             | 1        | 1.37%   |
| Seagate ST4000DM004-2CV104 4TB             | 1        | 1.37%   |
| Seagate ST3500630AS 500GB                  | 1        | 1.37%   |
| Seagate ST3250318AS 250GB                  | 1        | 1.37%   |
| Seagate ST3160023AS 160GB                  | 1        | 1.37%   |
| Seagate ST2000DM001-1ER164 2TB             | 1        | 1.37%   |
| Seagate FireCuda 520 SSD ZP2000GM30002 2TB | 1        | 1.37%   |
| SanDisk SSD PLUS 1000GB                    | 1        | 1.37%   |
| SanDisk SDSSDHII480G 480GB                 | 1        | 1.37%   |
| Samsung SSD 980 PRO 1TB                    | 1        | 1.37%   |
| Samsung SSD 980 1TB                        | 1        | 1.37%   |
| Samsung SSD 970 PRO 512GB                  | 1        | 1.37%   |
| Samsung SSD 970 EVO Plus 2TB               | 1        | 1.37%   |
| Samsung SSD 970 EVO Plus 1TB               | 1        | 1.37%   |
| Samsung SSD 970 EVO 500GB                  | 1        | 1.37%   |
| Samsung SSD 860 QVO 4TB                    | 1        | 1.37%   |
| Samsung SSD 860 PRO 1TB                    | 1        | 1.37%   |
| Samsung SSD 860 EVO 2TB                    | 1        | 1.37%   |
| Samsung SSD 850 PRO 256GB                  | 1        | 1.37%   |
| Samsung SSD 850 EVO 500GB                  | 1        | 1.37%   |
| Samsung SSD 840 PRO Series 128GB           | 1        | 1.37%   |
| Samsung Portable SSD T3 250GB              | 1        | 1.37%   |
| Samsung NVMe SSD Drive 512GB               | 1        | 1.37%   |
| Samsung NVMe SSD Drive 500GB               | 1        | 1.37%   |
| Samsung NVMe SSD Drive 1TB                 | 1        | 1.37%   |
| Samsung MZVL22T0HBLB-00B00 2TB             | 1        | 1.37%   |
| PLEXTOR PX-1TM9PG + 1TB                    | 1        | 1.37%   |
| Phison Sabrent Rocket 4.0 1TB              | 1        | 1.37%   |
| OCZ-VERTEX PLUS R2 247GB SSD               | 1        | 1.37%   |
| KIOXIA-EXCERIA PLUS G2 SSD 500GB           | 1        | 1.37%   |
| Kingston SHSS37A240G 240GB SSD             | 1        | 1.37%   |
| Kingchuxing 512GB                          | 1        | 1.37%   |
| Intel SSDSC2BB120G4 120GB                  | 1        | 1.37%   |
| Intel SSDPEKKW512G8 512GB                  | 1        | 1.37%   |
| Hitachi HUA721010KLA330 1TB                | 1        | 1.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 13       | 22     | 56.52%  |
| Seagate | 5        | 8      | 21.74%  |
| Hitachi | 3        | 4      | 13.04%  |
| Toshiba | 2        | 2      | 8.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 8      | 38.89%  |
| WDC                 | 3        | 3      | 16.67%  |
| SanDisk             | 2        | 3      | 11.11%  |
| OCZ-VERTEX          | 1        | 1      | 5.56%   |
| Kingston            | 1        | 1      | 5.56%   |
| Intel               | 1        | 1      | 5.56%   |
| GOODRAM             | 1        | 1      | 5.56%   |
| Crucial             | 1        | 4      | 5.56%   |
| Corsair             | 1        | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 17       | 23     | 35.42%  |
| NVMe | 16       | 30     | 33.33%  |
| HDD  | 15       | 36     | 31.25%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 22       | 59     | 57.89%  |
| NVMe | 16       | 30     | 42.11%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 12       | 17     | 34.29%  |
| 0.51-1.0   | 11       | 18     | 31.43%  |
| 1.01-2.0   | 6        | 9      | 17.14%  |
| 3.01-4.0   | 2        | 4      | 5.71%   |
| 2.01-3.0   | 2        | 5      | 5.71%   |
| 4.01-10.0  | 2        | 6      | 5.71%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 6        | 25%     |
| More than 3000 | 4        | 16.67%  |
| 251-500        | 4        | 16.67%  |
| 1001-2000      | 4        | 16.67%  |
| 1-20           | 2        | 8.33%   |
| 2001-3000      | 1        | 4.17%   |
| 101-250        | 1        | 4.17%   |
| 51-100         | 1        | 4.17%   |
| Unknown        | 1        | 4.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 7        | 29.17%  |
| More than 3000 | 3        | 12.5%   |
| 1-20           | 3        | 12.5%   |
| 501-1000       | 3        | 12.5%   |
| 1001-2000      | 2        | 8.33%   |
| 51-100         | 2        | 8.33%   |
| 21-50          | 1        | 4.17%   |
| 2001-3000      | 1        | 4.17%   |
| 101-250        | 1        | 4.17%   |
| Unknown        | 1        | 4.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                        | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC WD60EFRX-68L0BN1 6TB     | 1        | 3      | 11.11%  |
| WDC WD30EFRX-68AX9N0 3TB     | 1        | 2      | 11.11%  |
| WDC WD20EZRX-00D8PB0 2TB     | 1        | 1      | 11.11%  |
| WDC WD1002FBYS-18W8B0 1TB    | 1        | 1      | 11.11%  |
| Seagate ST3160023AS 160GB    | 1        | 1      | 11.11%  |
| SanDisk SSD PLUS 1000GB      | 1        | 1      | 11.11%  |
| Hitachi HUA721010KLA330 1TB  | 1        | 1      | 11.11%  |
| Hitachi HDS722020ALA330 2TB  | 1        | 2      | 11.11%  |
| Crucial CT525MX300SSD1 528GB | 1        | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 4        | 7      | 44.44%  |
| Hitachi | 2        | 3      | 22.22%  |
| Seagate | 1        | 1      | 11.11%  |
| SanDisk | 1        | 1      | 11.11%  |
| Crucial | 1        | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 4        | 7      | 57.14%  |
| Hitachi | 2        | 3      | 28.57%  |
| Seagate | 1        | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 11     | 71.43%  |
| SSD  | 2        | 2      | 28.57%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 21       | 67     | 65.63%  |
| Malfunc  | 7        | 13     | 21.88%  |
| Detected | 3        | 8      | 9.38%   |
| Failed   | 1        | 1      | 3.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| AMD                            | 14       | 29.17%  |
| Samsung Electronics            | 9        | 18.75%  |
| Intel                          | 9        | 18.75%  |
| Phison Electronics             | 3        | 6.25%   |
| ASMedia Technology             | 3        | 6.25%   |
| Toshiba America Info Systems   | 1        | 2.08%   |
| Solid State Storage Technology | 1        | 2.08%   |
| Silicon Motion                 | 1        | 2.08%   |
| Silicon Image                  | 1        | 2.08%   |
| Seagate Technology             | 1        | 2.08%   |
| Sandisk                        | 1        | 2.08%   |
| Micron/Crucial Technology      | 1        | 2.08%   |
| Marvell Technology Group       | 1        | 2.08%   |
| KIOXIA                         | 1        | 2.08%   |
| ADATA Technology               | 1        | 2.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 11       | 20%     |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7        | 12.73%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3        | 5.45%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3        | 5.45%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                       | 3        | 5.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 3.64%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 3.64%   |
| AMD X370 Series Chipset SATA Controller                                        | 2        | 3.64%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 3.64%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1        | 1.82%   |
| Solid State Storage Non-Volatile memory controller                             | 1        | 1.82%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 1.82%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 1.82%   |
| Seagate FireCuda 520 SSD                                                       | 1        | 1.82%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1        | 1.82%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 1.82%   |
| Phison E7 NVMe Controller                                                      | 1        | 1.82%   |
| Micron/Crucial NVMe Controller                                                 | 1        | 1.82%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 1.82%   |
| KIOXIA Non-Volatile memory controller                                          | 1        | 1.82%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1        | 1.82%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 1.82%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1        | 1.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 1.82%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1        | 1.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 1.82%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 1.82%   |
| AMD 300 Series Chipset SATA Controller                                         | 1        | 1.82%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1        | 1.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 22       | 55%     |
| NVMe | 16       | 40%     |
| RAID | 1        | 2.5%    |
| IDE  | 1        | 2.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 14       | 60.87%  |
| Intel  | 9        | 39.13%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 9 3950X 16-Core Processor            | 3        | 13.04%  |
| AMD Ryzen 5 1600 Six-Core Processor            | 2        | 8.7%    |
| Intel Pentium 4 CPU 3.20GHz                    | 1        | 4.35%   |
| Intel Core i9-9900K CPU @ 3.60GHz              | 1        | 4.35%   |
| Intel Core i7-6700K CPU @ 4.00GHz              | 1        | 4.35%   |
| Intel Core i7-10700F CPU @ 2.90GHz             | 1        | 4.35%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1        | 4.35%   |
| Intel Core i5-6400 CPU @ 2.70GHz               | 1        | 4.35%   |
| Intel Core i5-4670K CPU @ 3.40GHz              | 1        | 4.35%   |
| Intel 12th Gen Core i7-12700K                  | 1        | 4.35%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz        | 1        | 4.35%   |
| AMD Ryzen Threadripper 3960X 24-Core Processor | 1        | 4.35%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 1        | 4.35%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 4.35%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 1        | 4.35%   |
| AMD Ryzen 7 PRO 5750G with Radeon Graphics     | 1        | 4.35%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 1        | 4.35%   |
| AMD Ryzen 7 1700X Eight-Core Processor         | 1        | 4.35%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1        | 4.35%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 1        | 4.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 9            | 6        | 26.09%  |
| AMD Ryzen 5            | 4        | 17.39%  |
| Intel Core i5          | 3        | 13.04%  |
| Other                  | 2        | 8.7%    |
| Intel Core i7          | 2        | 8.7%    |
| AMD Ryzen 7            | 2        | 8.7%    |
| Intel Pentium 4        | 1        | 4.35%   |
| Intel Core i9          | 1        | 4.35%   |
| AMD Ryzen Threadripper | 1        | 4.35%   |
| AMD Ryzen 7 PRO        | 1        | 4.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 8      | 6        | 26.09%  |
| 16     | 4        | 17.39%  |
| 6      | 4        | 17.39%  |
| 4      | 4        | 17.39%  |
| 12     | 3        | 13.04%  |
| 24     | 1        | 4.35%   |
| 1      | 1        | 4.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 23       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 20       | 86.96%  |
| 1      | 3        | 13.04%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 23       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x08701021 | 4        | 17.39%  |
| Unknown    | 4        | 17.39%  |
| 0x08001138 | 3        | 13.04%  |
| 0x0a201016 | 2        | 8.7%    |
| 0xf43      | 1        | 4.35%   |
| 0xa0671    | 1        | 4.35%   |
| 0xa0655    | 1        | 4.35%   |
| 0x906ed    | 1        | 4.35%   |
| 0x906e9    | 1        | 4.35%   |
| 0x90672    | 1        | 4.35%   |
| 0x506e3    | 1        | 4.35%   |
| 0x0a50000b | 1        | 4.35%   |
| 0x08301039 | 1        | 4.35%   |
| 0x0800820d | 1        | 4.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 7        | 30.43%  |
| Zen 3            | 3        | 13.04%  |
| Zen              | 3        | 13.04%  |
| Skylake          | 2        | 8.7%    |
| KabyLake         | 2        | 8.7%    |
| Zen+             | 1        | 4.35%   |
| NetBurst         | 1        | 4.35%   |
| Icelake          | 1        | 4.35%   |
| Haswell          | 1        | 4.35%   |
| CometLake        | 1        | 4.35%   |
| Alderlake Hybrid | 1        | 4.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 12       | 46.15%  |
| Nvidia | 10       | 38.46%  |
| Intel  | 4        | 15.38%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]             | 5        | 18.52%  |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                      | 3        | 11.11%  |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                           | 2        | 7.41%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                 | 2        | 7.41%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                               | 1        | 3.7%    |
| Nvidia TU116 [GeForce GTX 1650]                                     | 1        | 3.7%    |
| Nvidia GP108 [GeForce GT 1030]                                      | 1        | 3.7%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                  | 1        | 3.7%    |
| Nvidia GM206 [GeForce GTX 960]                                      | 1        | 3.7%    |
| Nvidia GM204 [GeForce GTX 970]                                      | 1        | 3.7%    |
| Intel HD Graphics 630                                               | 1        | 3.7%    |
| Intel HD Graphics 530                                               | 1        | 3.7%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                           | 1        | 3.7%    |
| Intel AlderLake-S GT1                                               | 1        | 3.7%    |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                            | 1        | 3.7%    |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                      | 1        | 3.7%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT / 6800M]                        | 1        | 3.7%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                      | 1        | 3.7%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X] | 1        | 3.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 9        | 39.13%  |
| 1 x Nvidia     | 7        | 30.43%  |
| 1 x Intel      | 2        | 8.7%    |
| AMD + Nvidia   | 2        | 8.7%    |
| Other          | 1        | 4.35%   |
| 2 x AMD        | 1        | 4.35%   |
| Intel + Nvidia | 1        | 4.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 13       | 56.52%  |
| Proprietary | 8        | 34.78%  |
| Unknown     | 2        | 8.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 8        | 33.33%  |
| 8.01-16.0  | 6        | 25%     |
| 3.01-4.0   | 4        | 16.67%  |
| 7.01-8.0   | 3        | 12.5%   |
| 5.01-6.0   | 1        | 4.17%   |
| 1.01-2.0   | 1        | 4.17%   |
| 0.51-1.0   | 1        | 4.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 4        | 12.9%   |
| Hewlett-Packard         | 2        | 6.45%   |
| Goldstar                | 2        | 6.45%   |
| Dell                    | 2        | 6.45%   |
| BenQ                    | 2        | 6.45%   |
| ASUSTek Computer        | 2        | 6.45%   |
| AOC                     | 2        | 6.45%   |
| Acer                    | 2        | 6.45%   |
| Valve                   | 1        | 3.23%   |
| Toshiba                 | 1        | 3.23%   |
| NEC Computers           | 1        | 3.23%   |
| MStar                   | 1        | 3.23%   |
| Mi                      | 1        | 3.23%   |
| Lenovo                  | 1        | 3.23%   |
| Iiyama                  | 1        | 3.23%   |
| HannStar                | 1        | 3.23%   |
| Gigabyte Technology     | 1        | 3.23%   |
| Gateway                 | 1        | 3.23%   |
| Chi Mei Optoelectronics | 1        | 3.23%   |
| Belinea                 | 1        | 3.23%   |
| Ancor Communications    | 1        | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Valve Index HMD VLV91A8                                                | 1        | 2.94%   |
| Toshiba PA3552 TOS501C 1680x1050 433x270mm 20.1-inch                   | 1        | 2.94%   |
| Samsung Electronics SMS27A850 SAM083D 2560x1440 518x324mm 24.1-inch    | 1        | 2.94%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch      | 1        | 2.94%   |
| Samsung Electronics LF24T450F SAM7096 1920x1080 527x296mm 23.8-inch    | 1        | 2.94%   |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1196x336mm 48.9-inch     | 1        | 2.94%   |
| NEC Computers EA274WMi NEC6960 2560x1440 597x336mm 27.0-inch           | 1        | 2.94%   |
| MStar DP MST2380 2560x1440 597x336mm 27.0-inch                         | 1        | 2.94%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                       | 1        | 2.94%   |
| Lenovo P24h-10 LEN61AE 2560x1440 527x296mm 23.8-inch                   | 1        | 2.94%   |
| Iiyama PL2792Q IVM6630 2560x1440 600x340mm 27.2-inch                   | 1        | 2.94%   |
| Hewlett-Packard LV1561w HWP2837 1366x768 344x194mm 15.5-inch           | 1        | 2.94%   |
| Hewlett-Packard LP2475w HWP26F9 1920x1200 546x352mm 25.6-inch          | 1        | 2.94%   |
| Hewlett-Packard 22fw HPN3541 1920x1080 476x268mm 21.5-inch             | 1        | 2.94%   |
| HannStar JC198D HSD0CC6 1280x1024 376x301mm 19.0-inch                  | 1        | 2.94%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch               | 1        | 2.94%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 1        | 2.94%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 1        | 2.94%   |
| Gigabyte Technology AORUS AD27QD GBT2701 2560x1440 609x355mm 27.8-inch | 1        | 2.94%   |
| Gateway FPD1765 GWY06E9 1280x1024 338x270mm 17.0-inch                  | 1        | 2.94%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                      | 1        | 2.94%   |
| Dell U2515H DELD070 2560x1440 553x311mm 25.0-inch                      | 1        | 2.94%   |
| Dell S3221QS DELD107 3840x2160 697x392mm 31.5-inch                     | 1        | 2.94%   |
| Chi Mei Optoelectronics CMC 19AW CMO2198 1440x900 408x255mm 18.9-inch  | 1        | 2.94%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                     | 1        | 2.94%   |
| BenQ E2200HD BNQ790C 1920x1080 477x268mm 21.5-inch                     | 1        | 2.94%   |
| Belinea Belinea101735 MAX06B2 1280x1024 338x270mm 17.0-inch            | 1        | 2.94%   |
| ASUSTek Computer XG27WQ AUS2724 2560x1440 597x336mm 27.0-inch          | 1        | 2.94%   |
| ASUSTek Computer VG27A AUS2723 2560x1440 597x336mm 27.0-inch           | 1        | 2.94%   |
| AOC 2437 AOC2437 1920x1080 521x293mm 23.5-inch                         | 1        | 2.94%   |
| AOC 2269WM AOC2269 1920x1080 480x270mm 21.7-inch                       | 1        | 2.94%   |
| Ancor Communications VN279 ACI27A4 1920x1080 597x336mm 27.0-inch       | 1        | 2.94%   |
| Acer VG270U P ACR06CF 2560x1440 597x336mm 27.0-inch                    | 1        | 2.94%   |
| Acer K272HUL ACR03DD 2560x1440 597x336mm 27.0-inch                     | 1        | 2.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 2560x1440 (QHD)    | 11       | 34.38%  |
| 1920x1080 (FHD)    | 7        | 21.88%  |
| 3840x2160 (4K)     | 3        | 9.38%   |
| 3440x1440          | 2        | 6.25%   |
| 1280x1024 (SXGA)   | 2        | 6.25%   |
| 3840x1080          | 1        | 3.13%   |
| 2560x1080          | 1        | 3.13%   |
| 1920x1200 (WUXGA)  | 1        | 3.13%   |
| 1680x1050 (WSXGA+) | 1        | 3.13%   |
| 1440x900 (WXGA+)   | 1        | 3.13%   |
| 1366x768 (WXGA)    | 1        | 3.13%   |
| Unknown            | 1        | 3.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 10       | 30.3%   |
| 23      | 4        | 12.12%  |
| 34      | 3        | 9.09%   |
| 25      | 2        | 6.06%   |
| 24      | 2        | 6.06%   |
| 21      | 2        | 6.06%   |
| 19      | 2        | 6.06%   |
| 17      | 2        | 6.06%   |
| 49      | 1        | 3.03%   |
| 31      | 1        | 3.03%   |
| 28      | 1        | 3.03%   |
| 20      | 1        | 3.03%   |
| 15      | 1        | 3.03%   |
| Unknown | 1        | 3.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 14       | 46.67%  |
| 401-500     | 4        | 13.33%  |
| 701-800     | 3        | 10%     |
| 601-700     | 3        | 10%     |
| 301-350     | 3        | 10%     |
| 351-400     | 1        | 3.33%   |
| 1001-1500   | 1        | 3.33%   |
| Unknown     | 1        | 3.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 17       | 60.71%  |
| 16/10   | 4        | 14.29%  |
| 21/9    | 3        | 10.71%  |
| 5/4     | 2        | 7.14%   |
| 32/9    | 1        | 3.57%   |
| Unknown | 1        | 3.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 10       | 31.25%  |
| 201-250        | 6        | 18.75%  |
| 351-500        | 5        | 15.63%  |
| 251-300        | 3        | 9.38%   |
| 151-200        | 3        | 9.38%   |
| 141-150        | 2        | 6.25%   |
| 101-110        | 1        | 3.13%   |
| 501-1000       | 1        | 3.13%   |
| Unknown        | 1        | 3.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 101-120 | 13       | 44.83%  |
| 51-100  | 11       | 37.93%  |
| 121-160 | 2        | 6.9%    |
| 1-50    | 1        | 3.45%   |
| 161-240 | 1        | 3.45%   |
| Unknown | 1        | 3.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 11       | 47.83%  |
| 2     | 8        | 34.78%  |
| 0     | 2        | 8.7%    |
| 4     | 1        | 4.35%   |
| 3     | 1        | 4.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 13       | 38.24%  |
| Intel                    | 13       | 38.24%  |
| Aquantia                 | 3        | 8.82%   |
| Raspberry Pi             | 1        | 2.94%   |
| Ralink Technology        | 1        | 2.94%   |
| Qualcomm Atheros         | 1        | 2.94%   |
| Microsoft                | 1        | 2.94%   |
| Marvell Technology Group | 1        | 2.94%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7        | 16.67%  |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 11.9%   |
| Intel I211 Gigabit Network Connection                             | 5        | 11.9%   |
| Intel Wi-Fi 6 AX200                                               | 4        | 9.52%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 7.14%   |
| Intel Ethernet Controller I225-V                                  | 2        | 4.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 2.38%   |
| Raspberry Pi Pico                                                 | 1        | 2.38%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 2.38%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 2.38%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 1        | 2.38%   |
| Microsoft XBOX ACC                                                | 1        | 2.38%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 2.38%   |
| Intel Wireless-AC 9260                                            | 1        | 2.38%   |
| Intel I210 Gigabit Network Connection                             | 1        | 2.38%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                  | 1        | 2.38%   |
| Intel Ethernet Connection I217-V                                  | 1        | 2.38%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 2.38%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 2.38%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 2.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1        | 2.38%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 1        | 2.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 8        | 72.73%  |
| Ralink Technology | 1        | 9.09%   |
| Qualcomm Atheros  | 1        | 9.09%   |
| Microsoft         | 1        | 9.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 4        | 33.33%  |
| Ralink RT2870/RT3070 Wireless Adapter                      | 1        | 8.33%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter           | 1        | 8.33%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter | 1        | 8.33%   |
| Microsoft XBOX ACC                                         | 1        | 8.33%   |
| Intel Wireless-AC 9260                                     | 1        | 8.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1        | 8.33%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 1        | 8.33%   |
| Intel Alder Lake-S PCH CNVi WiFi                           | 1        | 8.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 13       | 46.43%  |
| Intel                    | 11       | 39.29%  |
| Aquantia                 | 3        | 10.71%  |
| Marvell Technology Group | 1        | 3.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7        | 24.14%  |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 17.24%  |
| Intel I211 Gigabit Network Connection                             | 5        | 17.24%  |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 10.34%  |
| Intel Ethernet Controller I225-V                                  | 2        | 6.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 3.45%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 3.45%   |
| Intel I210 Gigabit Network Connection                             | 1        | 3.45%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                  | 1        | 3.45%   |
| Intel Ethernet Connection I217-V                                  | 1        | 3.45%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 3.45%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 3.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 22       | 66.67%  |
| WiFi     | 10       | 30.3%   |
| Modem    | 1        | 3.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 20       | 80%     |
| WiFi     | 5        | 20%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10       | 43.48%  |
| 2     | 7        | 30.43%  |
| 3     | 5        | 21.74%  |
| 0     | 1        | 4.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 17       | 73.91%  |
| Yes  | 6        | 26.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 9        | 64.29%  |
| Cambridge Silicon Radio | 3        | 21.43%  |
| Realtek Semiconductor   | 1        | 7.14%   |
| ASUSTek Computer        | 1        | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 5        | 35.71%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 21.43%  |
| Realtek Bluetooth Radio                             | 1        | 7.14%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 7.14%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 7.14%   |
| Intel Bluetooth Device                              | 1        | 7.14%   |
| Intel AX201 Bluetooth                               | 1        | 7.14%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 17       | 33.33%  |
| Nvidia                               | 9        | 17.65%  |
| Intel                                | 8        | 15.69%  |
| Thesycon Systemsoftware & Consulting | 2        | 3.92%   |
| Logitech                             | 2        | 3.92%   |
| Creative Labs                        | 2        | 3.92%   |
| C-Media Electronics                  | 2        | 3.92%   |
| ASUSTek Computer                     | 2        | 3.92%   |
| Yamaha                               | 1        | 1.96%   |
| Valve Software                       | 1        | 1.96%   |
| SteelSeries ApS                      | 1        | 1.96%   |
| SAVITECH                             | 1        | 1.96%   |
| RODE Microphones                     | 1        | 1.96%   |
| Creative Technology                  | 1        | 1.96%   |
| AudioQuest                           | 1        | 1.96%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                | 8        | 13.11%  |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]              | 5        | 8.2%    |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]               | 4        | 6.56%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 4        | 6.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 3        | 4.92%   |
| Thesycon Systemsoftware & Consulting E30                                | 2        | 3.28%   |
| Nvidia TU102 High Definition Audio Controller                           | 2        | 3.28%   |
| Nvidia GP106 High Definition Audio Controller                           | 2        | 3.28%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]           | 2        | 3.28%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]            | 2        | 3.28%   |
| Yamaha Steinberg UR22mkII                                               | 1        | 1.64%   |
| Valve Software Valve VR Radio & HMD Mic                                 | 1        | 1.64%   |
| SteelSeries ApS Arctis 7 wireless adapter                               | 1        | 1.64%   |
| SAVITECH SA9023 audio controller                                        | 1        | 1.64%   |
| RODE Microphones RODE VideoMic NTG                                      | 1        | 1.64%   |
| Nvidia TU116 High Definition Audio Controller                           | 1        | 1.64%   |
| Nvidia GP108 High Definition Audio Controller                           | 1        | 1.64%   |
| Nvidia GP102 HDMI Audio Controller                                      | 1        | 1.64%   |
| Nvidia GM206 High Definition Audio Controller                           | 1        | 1.64%   |
| Nvidia GM204 High Definition Audio Controller                           | 1        | 1.64%   |
| Logitech Z-5 Speakers                                                   | 1        | 1.64%   |
| Logitech Yeti X                                                         | 1        | 1.64%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 1        | 1.64%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                 | 1        | 1.64%   |
| Intel Comet Lake PCH cAVS                                               | 1        | 1.64%   |
| Intel Cannon Lake PCH cAVS                                              | 1        | 1.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 1        | 1.64%   |
| Creative Technology Sound BlasterX G6                                   | 1        | 1.64%   |
| C-Media Electronics USB Advanced Audio Device                           | 1        | 1.64%   |
| C-Media Electronics CM108 Audio Controller                              | 1        | 1.64%   |
| AudioQuest SDAC                                                         | 1        | 1.64%   |
| ASUSTek Computer Xonar U1 Audio Station                                 | 1        | 1.64%   |
| ASUSTek Computer USB Audio                                              | 1        | 1.64%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                              | 1        | 1.64%   |
| AMD Renoir Radeon High Definition Audio Controller                      | 1        | 1.64%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 1        | 1.64%   |
| AMD Family 17h/19h HD Audio Controller                                  | 1        | 1.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 7        | 29.17%  |
| G.Skill             | 6        | 25%     |
| Kingston            | 5        | 20.83%  |
| Unknown             | 1        | 4.17%   |
| Team                | 1        | 4.17%   |
| Samsung Electronics | 1        | 4.17%   |
| Patriot             | 1        | 4.17%   |
| Corsair             | 1        | 4.17%   |
| A-DATA Technology   | 1        | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Unknown RAM Module 512MB DIMM SDRAM                         | 1        | 3.7%    |
| Unknown RAM Module 1GB DIMM SDRAM                           | 1        | 3.7%    |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s          | 1        | 3.7%    |
| Samsung RAM M378A2G43MX3-CTD 16GB DIMM DDR4 2666MT/s        | 1        | 3.7%    |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s          | 1        | 3.7%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s        | 1        | 3.7%    |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s      | 1        | 3.7%    |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s         | 1        | 3.7%    |
| Kingston RAM KF3200C16D4/16GX 16384MB DIMM DDR4 3200MT/s    | 1        | 3.7%    |
| Kingston RAM 9905625-062.A00G 8GB DIMM DDR4 2133MT/s        | 1        | 3.7%    |
| G.Skill RAM F4-3600C17-16GTZR 16GB DIMM DDR4 3666MT/s       | 1        | 3.7%    |
| G.Skill RAM F4-3600C17-16GTZKW 16GB DIMM DDR4 3600MT/s      | 1        | 3.7%    |
| G.Skill RAM F4-3600C16-8GTZN 8GB DIMM DDR4 3666MT/s         | 1        | 3.7%    |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s       | 1        | 3.7%    |
| G.Skill RAM F4-3000C15-8GVRB 8GB DIMM DDR4 2133MT/s         | 1        | 3.7%    |
| G.Skill RAM F3-14900CL9-4GBSR 4GB DIMM DDR3 1800MT/s        | 1        | 3.7%    |
| Crucial RAM CT8G4DFD824A.C16FF 8GB DIMM DDR4 2733MT/s       | 1        | 3.7%    |
| Crucial RAM CT8G4DFD824A.C16FBD1 8GB DIMM DDR4 2400MT/s     | 1        | 3.7%    |
| Crucial RAM CT16G4DFD8213.C16FAD 16GB DIMM DDR4 2133MT/s    | 1        | 3.7%    |
| Crucial RAM BLS4G4D26BFSE.8FE 4GB DIMM DDR4 2667MT/s        | 1        | 3.7%    |
| Crucial RAM BL32G36C16U4B.M16FB1 32GB DIMM DDR4             | 1        | 3.7%    |
| Crucial RAM BL32G32C16U4B.M16FB1 32GB DIMM DDR4 3200MT/s    | 1        | 3.7%    |
| Crucial RAM BL16G36C16U4RL.M8FB1 16GB DIMM DDR4 4000MT/s    | 1        | 3.7%    |
| Crucial RAM BL16G32C16U4B.M16FE1 16384MB DIMM DDR4 3200MT/s | 1        | 3.7%    |
| Crucial RAM BL16G32C16U4B.M16FE 16GB DIMM DDR4 3200MT/s     | 1        | 3.7%    |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s      | 1        | 3.7%    |
| A-DATA RAM DDR4 3000 2OZ 8GB DIMM DDR4 3000MT/s             | 1        | 3.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 19       | 90.48%  |
| SDRAM | 1        | 4.76%   |
| DDR3  | 1        | 4.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 21       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 12       | 48%     |
| 8192  | 6        | 24%     |
| 32768 | 3        | 12%     |
| 4096  | 2        | 8%      |
| 1024  | 1        | 4%      |
| 512   | 1        | 4%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3600    | 4        | 16%     |
| 3200    | 4        | 16%     |
| 2133    | 4        | 16%     |
| 3666    | 2        | 8%      |
| 4000    | 1        | 4%      |
| 3866    | 1        | 4%      |
| 3533    | 1        | 4%      |
| 3400    | 1        | 4%      |
| 3000    | 1        | 4%      |
| 2733    | 1        | 4%      |
| 2667    | 1        | 4%      |
| 2666    | 1        | 4%      |
| 2400    | 1        | 4%      |
| 1800    | 1        | 4%      |
| Unknown | 1        | 4%      |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 4        | 50%     |
| Valve Software                | 1        | 12.5%   |
| Sunplus Innovation Technology | 1        | 12.5%   |
| Generalplus Technology        | 1        | 12.5%   |
| Creative Technology           | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Valve Software 3D Camera          | 1        | 12.5%   |
| Sunplus Full HD webcam            | 1        | 12.5%   |
| Logitech Webcam C270              | 1        | 12.5%   |
| Logitech StreamCam                | 1        | 12.5%   |
| Logitech QuickCam Orbit/Sphere AF | 1        | 12.5%   |
| Logitech BRIO Ultra HD Webcam     | 1        | 12.5%   |
| Generalplus GENERAL WEBCAM        | 1        | 12.5%   |
| Creative Live! Cam Sync 1080p     | 1        | 12.5%   |

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
| 0     | 17       | 70.83%  |
| 1     | 5        | 20.83%  |
| 4     | 1        | 4.17%   |
| 2     | 1        | 4.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 5        | 50%     |
| Net/wireless             | 1        | 10%     |
| Modem                    | 1        | 10%     |
| Graphics card            | 1        | 10%     |
| Camera                   | 1        | 10%     |
| Bluetooth                | 1        | 10%     |

