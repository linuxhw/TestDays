Slackware 15.0 - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Slackware 15.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Slackware_15.0/Desktop/README.md) and [notebooks](/Dist/Slackware_15.0/Notebook/README.md).

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

Total: 35

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME Z390-A                | Desktop     | [5307aba2c3](https://linux-hardware.org/?probe=5307aba2c3) | Mar 30, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [c8289cd264](https://linux-hardware.org/?probe=c8289cd264) | Mar 26, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [5c6b1616fa](https://linux-hardware.org/?probe=5c6b1616fa) | Mar 21, 2022 |
| Acer          | FMCP7A-ION-LE               | Desktop     | [bbce73c6d6](https://linux-hardware.org/?probe=bbce73c6d6) | Mar 14, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [5f36bc3969](https://linux-hardware.org/?probe=5f36bc3969) | Mar 12, 2022 |
| ASRock        | H270 Pro4                   | Desktop     | [ae79ca8557](https://linux-hardware.org/?probe=ae79ca8557) | Mar 12, 2022 |
| HP            | 86F3 00100                  | All in one  | [7de0381db8](https://linux-hardware.org/?probe=7de0381db8) | Mar 11, 2022 |
| Lenovo        | ThinkPad X230 2325P38       | Notebook    | [1a0cab737b](https://linux-hardware.org/?probe=1a0cab737b) | Mar 10, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [0b0c1aca1b](https://linux-hardware.org/?probe=0b0c1aca1b) | Mar 10, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c7825c54fc](https://linux-hardware.org/?probe=c7825c54fc) | Mar 10, 2022 |
| Framework     | Laptop                      | Notebook    | [ae37705198](https://linux-hardware.org/?probe=ae37705198) | Mar 10, 2022 |
| Dell          | 068NXX A00                  | Server      | [85004f427a](https://linux-hardware.org/?probe=85004f427a) | Mar 09, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [bc59b862f4](https://linux-hardware.org/?probe=bc59b862f4) | Mar 02, 2022 |
| TYAN Compu... | S7012                       | Server      | [fec98b51da](https://linux-hardware.org/?probe=fec98b51da) | Feb 27, 2022 |
| TYAN Compu... | S7012                       | Server      | [81a490184b](https://linux-hardware.org/?probe=81a490184b) | Feb 26, 2022 |
| Biostar       | X470GTA                     | Desktop     | [8d400b49f8](https://linux-hardware.org/?probe=8d400b49f8) | Feb 13, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [8ce0419468](https://linux-hardware.org/?probe=8ce0419468) | Feb 13, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [dda6a57223](https://linux-hardware.org/?probe=dda6a57223) | Feb 07, 2022 |
| HP            | 212B                        | Desktop     | [353b0dde99](https://linux-hardware.org/?probe=353b0dde99) | Jan 29, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [85543358d3](https://linux-hardware.org/?probe=85543358d3) | Jan 14, 2022 |
| Dynabook      | P1-C7MP-BL                  | Notebook    | [268f94787e](https://linux-hardware.org/?probe=268f94787e) | Jan 14, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [25d668ee95](https://linux-hardware.org/?probe=25d668ee95) | Jan 10, 2022 |
| MSI           | H61M-P31                    | Desktop     | [58651bba67](https://linux-hardware.org/?probe=58651bba67) | Dec 07, 2021 |
| HP            | Laptop 15-bs1xx             | Notebook    | [b6c9f34c4c](https://linux-hardware.org/?probe=b6c9f34c4c) | Dec 07, 2021 |
| System76      | Oryx Pro                    | Notebook    | [3cd05d02a8](https://linux-hardware.org/?probe=3cd05d02a8) | Oct 27, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [b7df25ba5d](https://linux-hardware.org/?probe=b7df25ba5d) | Oct 25, 2021 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [64e5ee1691](https://linux-hardware.org/?probe=64e5ee1691) | Oct 13, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [17d37c5316](https://linux-hardware.org/?probe=17d37c5316) | Oct 12, 2021 |
| MSI           | Modern 14 B11MO             | Notebook    | [e8f13facfd](https://linux-hardware.org/?probe=e8f13facfd) | Oct 03, 2021 |
| MSI           | Modern 14 B11MO             | Notebook    | [9f5c2e0fde](https://linux-hardware.org/?probe=9f5c2e0fde) | Sep 27, 2021 |
| Dell          | Inspiron 15-3552            | Notebook    | [f76339b0af](https://linux-hardware.org/?probe=f76339b0af) | Aug 31, 2021 |
| HP            | 245 G7 Notebook PC          | Notebook    | [c0806e4955](https://linux-hardware.org/?probe=c0806e4955) | Aug 23, 2021 |
| HP            | 245 G7 Notebook PC          | Notebook    | [c409287d23](https://linux-hardware.org/?probe=c409287d23) | Aug 23, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [4c196e1abd](https://linux-hardware.org/?probe=4c196e1abd) | Aug 18, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [53a1179121](https://linux-hardware.org/?probe=53a1179121) | Aug 12, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.19           | 6         | 20%     |
| 5.16.13           | 2         | 6.67%   |
| 5.15.27           | 2         | 6.67%   |
| 5.17.0-custom     | 1         | 3.33%   |
| 5.16.9-joe1       | 1         | 3.33%   |
| 5.16.12           | 1         | 3.33%   |
| 5.16.11           | 1         | 3.33%   |
| 5.15.6            | 1         | 3.33%   |
| 5.15.21-hardened1 | 1         | 3.33%   |
| 5.15.14           | 1         | 3.33%   |
| 5.15.1            | 1         | 3.33%   |
| 5.14.9            | 1         | 3.33%   |
| 5.14.8            | 1         | 3.33%   |
| 5.14.15-Unraid    | 1         | 3.33%   |
| 5.14.15           | 1         | 3.33%   |
| 5.14.11           | 1         | 3.33%   |
| 5.14.10           | 1         | 3.33%   |
| 5.14.0            | 1         | 3.33%   |
| 5.13.8            | 1         | 3.33%   |
| 5.13.5            | 1         | 3.33%   |
| 5.13.12           | 1         | 3.33%   |
| 5.13.11           | 1         | 3.33%   |
| 5.10.91           | 1         | 3.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.19 | 6         | 20%     |
| 5.16.13 | 2         | 6.67%   |
| 5.15.27 | 2         | 6.67%   |
| 5.14.15 | 2         | 6.67%   |
| 5.17.0  | 1         | 3.33%   |
| 5.16.9  | 1         | 3.33%   |
| 5.16.12 | 1         | 3.33%   |
| 5.16.11 | 1         | 3.33%   |
| 5.15.6  | 1         | 3.33%   |
| 5.15.21 | 1         | 3.33%   |
| 5.15.14 | 1         | 3.33%   |
| 5.15.1  | 1         | 3.33%   |
| 5.14.9  | 1         | 3.33%   |
| 5.14.8  | 1         | 3.33%   |
| 5.14.11 | 1         | 3.33%   |
| 5.14.10 | 1         | 3.33%   |
| 5.14.0  | 1         | 3.33%   |
| 5.13.8  | 1         | 3.33%   |
| 5.13.5  | 1         | 3.33%   |
| 5.13.12 | 1         | 3.33%   |
| 5.13.11 | 1         | 3.33%   |
| 5.10.91 | 1         | 3.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 12        | 41.38%  |
| 5.14    | 6         | 20.69%  |
| 5.16    | 5         | 17.24%  |
| 5.13    | 4         | 13.79%  |
| 5.17    | 1         | 3.45%   |
| 5.10    | 1         | 3.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 29        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| KDE5    | 14        | 46.67%  |
| XFCE    | 7         | 23.33%  |
| Unknown | 5         | 16.67%  |
| GNOME   | 2         | 6.67%   |
| KDE     | 1         | 3.33%   |
| FVWM    | 1         | 3.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 15        | 48.39%  |
| Tty     | 13        | 41.94%  |
| Wayland | 2         | 6.45%   |
| Unknown | 1         | 3.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 15        | 51.72%  |
| Unknown | 7         | 24.14%  |
| XDM     | 5         | 17.24%  |
| LightDM | 2         | 6.9%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 23        | 79.31%  |
| Unknown     | 2         | 6.9%    |
| pt_BR       | 1         | 3.45%   |
| it_IT       | 1         | 3.45%   |
| es_ES.UTF8  | 1         | 3.45%   |
| en_US.ASCII | 1         | 3.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 18        | 62.07%  |
| BIOS | 11        | 37.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 22        | 75.86%  |
| Btrfs | 3         | 10.34%  |
| Xfs   | 2         | 6.9%    |
| Zfs   | 1         | 3.45%   |
| F2fs  | 1         | 3.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 23        | 76.67%  |
| MBR     | 4         | 13.33%  |
| Unknown | 3         | 10%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 22        | 73.33%  |
| Yes       | 8         | 26.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 23        | 79.31%  |
| Yes       | 6         | 20.69%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 6         | 20.69%  |
| MSI              | 5         | 17.24%  |
| Lenovo           | 3         | 10.34%  |
| Dell             | 3         | 10.34%  |
| ASUSTek Computer | 3         | 10.34%  |
| Apple            | 2         | 6.9%    |
| TYAN Computer    | 1         | 3.45%   |
| System76         | 1         | 3.45%   |
| Framework        | 1         | 3.45%   |
| Dynabook         | 1         | 3.45%   |
| Biostar          | 1         | 3.45%   |
| ASRock           | 1         | 3.45%   |
| Acer             | 1         | 3.45%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| TYAN S7012                            | 1         | 3.45%   |
| System76 Oryx Pro                     | 1         | 3.45%   |
| MSI MS-7C52                           | 1         | 3.45%   |
| MSI MS-7C02                           | 1         | 3.45%   |
| MSI MS-7788                           | 1         | 3.45%   |
| MSI MS-7529                           | 1         | 3.45%   |
| MSI Modern 14 B11MO                   | 1         | 3.45%   |
| Lenovo ThinkPad X230 2325P38          | 1         | 3.45%   |
| Lenovo ThinkPad Edge E530c 336669G    | 1         | 3.45%   |
| Lenovo H50-05 90BH001WIX              | 1         | 3.45%   |
| HP Z440 Workstation                   | 1         | 3.45%   |
| HP Pavilion Gaming Laptop 16-a0xxx    | 1         | 3.45%   |
| HP Laptop 15-bs1xx                    | 1         | 3.45%   |
| HP EliteBook 840 G5                   | 1         | 3.45%   |
| HP 245 G7 Notebook PC                 | 1         | 3.45%   |
| HP 205 G4 22 All-in-One PC            | 1         | 3.45%   |
| Framework Laptop                      | 1         | 3.45%   |
| Dynabook P1-C7MP-BL                   | 1         | 3.45%   |
| Dell Vostro 3500                      | 1         | 3.45%   |
| Dell PowerEdge R6515                  | 1         | 3.45%   |
| Dell Inspiron 15-3552                 | 1         | 3.45%   |
| Biostar X470GTA                       | 1         | 3.45%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 1         | 3.45%   |
| ASUS PRIME Z390-A                     | 1         | 3.45%   |
| ASUS All Series                       | 1         | 3.45%   |
| ASRock H270 Pro4                      | 1         | 3.45%   |
| Apple Macmini6,2                      | 1         | 3.45%   |
| Apple iMac7,1                         | 1         | 3.45%   |
| Acer Aspire R3610                     | 1         | 3.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 2         | 6.9%    |
| TYAN S7012          | 1         | 3.45%   |
| System76 Oryx       | 1         | 3.45%   |
| MSI MS-7C52         | 1         | 3.45%   |
| MSI MS-7C02         | 1         | 3.45%   |
| MSI MS-7788         | 1         | 3.45%   |
| MSI MS-7529         | 1         | 3.45%   |
| MSI Modern          | 1         | 3.45%   |
| Lenovo H50-05       | 1         | 3.45%   |
| HP Z440             | 1         | 3.45%   |
| HP Pavilion         | 1         | 3.45%   |
| HP Laptop           | 1         | 3.45%   |
| HP EliteBook        | 1         | 3.45%   |
| HP 245              | 1         | 3.45%   |
| HP 205              | 1         | 3.45%   |
| Framework Laptop    | 1         | 3.45%   |
| Dynabook P1-C7MP-BL | 1         | 3.45%   |
| Dell Vostro         | 1         | 3.45%   |
| Dell PowerEdge      | 1         | 3.45%   |
| Dell Inspiron       | 1         | 3.45%   |
| Biostar X470GTA     | 1         | 3.45%   |
| ASUS ROG            | 1         | 3.45%   |
| ASUS PRIME          | 1         | 3.45%   |
| ASUS All            | 1         | 3.45%   |
| ASRock H270         | 1         | 3.45%   |
| Apple Macmini6      | 1         | 3.45%   |
| Apple iMac7         | 1         | 3.45%   |
| Acer Aspire         | 1         | 3.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 5         | 17.24%  |
| 2020 | 4         | 13.79%  |
| 2019 | 3         | 10.34%  |
| 2015 | 3         | 10.34%  |
| 2018 | 2         | 6.9%    |
| 2017 | 2         | 6.9%    |
| 2012 | 2         | 6.9%    |
| 2011 | 2         | 6.9%    |
| 2009 | 2         | 6.9%    |
| 2016 | 1         | 3.45%   |
| 2014 | 1         | 3.45%   |
| 2010 | 1         | 3.45%   |
| 2007 | 1         | 3.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 13        | 44.83%  |
| Desktop    | 11        | 37.93%  |
| All in one | 2         | 6.9%    |
| Server     | 2         | 6.9%    |
| Mini pc    | 1         | 3.45%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 29        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 27        | 93.1%   |
| Yes  | 2         | 6.9%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 7         | 24.14%  |
| 16.01-24.0  | 7         | 24.14%  |
| 4.01-8.0    | 5         | 17.24%  |
| 32.01-64.0  | 3         | 10.34%  |
| 64.01-256.0 | 3         | 10.34%  |
| 8.01-16.0   | 3         | 10.34%  |
| 1.01-2.0    | 1         | 3.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 8         | 25.81%  |
| 1.01-2.0   | 8         | 25.81%  |
| 0.51-1.0   | 6         | 19.35%  |
| 2.01-3.0   | 4         | 12.9%   |
| 0.01-0.5   | 2         | 6.45%   |
| 32.01-64.0 | 1         | 3.23%   |
| 3.01-4.0   | 1         | 3.23%   |
| 16.01-24.0 | 1         | 3.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 15        | 51.72%  |
| 2      | 5         | 17.24%  |
| 4      | 4         | 13.79%  |
| 3      | 3         | 10.34%  |
| 6      | 1         | 3.45%   |
| 5      | 1         | 3.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 18        | 62.07%  |
| Yes       | 11        | 37.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 86.21%  |
| No        | 4         | 13.79%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 68.97%  |
| No        | 9         | 31.03%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 62.07%  |
| No        | 11        | 37.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 9         | 31.03%  |
| South Africa | 3         | 10.34%  |
| Italy        | 3         | 10.34%  |
| Spain        | 2         | 6.9%    |
| Japan        | 2         | 6.9%    |
| Greece       | 2         | 6.9%    |
| Brazil       | 2         | 6.9%    |
| UK           | 1         | 3.45%   |
| Switzerland  | 1         | 3.45%   |
| Sweden       | 1         | 3.45%   |
| Serbia       | 1         | 3.45%   |
| Netherlands  | 1         | 3.45%   |
| Mexico       | 1         | 3.45%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City         | Computers | Percent |
|--------------|-----------|---------|
| Musashino    | 2         | 6.9%    |
| Chania       | 2         | 6.9%    |
| Cape Town    | 2         | 6.9%    |
| Verona       | 1         | 3.45%   |
| SkÃ¶vde    | 1         | 3.45%   |
| Saint Paul   | 1         | 3.45%   |
| Rome         | 1         | 3.45%   |
| Reno         | 1         | 3.45%   |
| Porto Alegre | 1         | 3.45%   |
| Plainwell    | 1         | 3.45%   |
| Naaldwijk    | 1         | 3.45%   |
| Milwaukee    | 1         | 3.45%   |
| Mexico City  | 1         | 3.45%   |
| Mead         | 1         | 3.45%   |
| McKinney     | 1         | 3.45%   |
| Liebefeld    | 1         | 3.45%   |
| League City  | 1         | 3.45%   |
| Johannesburg | 1         | 3.45%   |
| Granada      | 1         | 3.45%   |
| Frosinone    | 1         | 3.45%   |
| Fortaleza    | 1         | 3.45%   |
| Chicago      | 1         | 3.45%   |
| Belgrade     | 1         | 3.45%   |
| Belfast      | 1         | 3.45%   |
| Algeciras    | 1         | 3.45%   |
| Abingdon     | 1         | 3.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 13     | 22.92%  |
| Seagate             | 8         | 13     | 16.67%  |
| WDC                 | 7         | 9      | 14.58%  |
| Toshiba             | 4         | 6      | 8.33%   |
| Kingston            | 3         | 4      | 6.25%   |
| Hitachi             | 3         | 3      | 6.25%   |
| Crucial             | 2         | 2      | 4.17%   |
| SanDisk             | 1         | 1      | 2.08%   |
| Patriot             | 1         | 1      | 2.08%   |
| JMicron             | 1         | 1      | 2.08%   |
| Intenso             | 1         | 1      | 2.08%   |
| HGST                | 1         | 1      | 2.08%   |
| Hewlett-Packard     | 1         | 2      | 2.08%   |
| GOODRAM             | 1         | 1      | 2.08%   |
| Gigabyte Technology | 1         | 1      | 2.08%   |
| External            | 1         | 1      | 2.08%   |
| Apple               | 1         | 1      | 2.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| WDC WD10SPZX-60Z10T0 1TB             | 2         | 3.77%   |
| WDC WD5000AAKX-22ERMA0 500GB         | 1         | 1.89%   |
| WDC WD3200AAJS-65B4A0 320GB          | 1         | 1.89%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 1.89%   |
| WDC WD20EFRX-68EUZN0 2TB             | 1         | 1.89%   |
| WDC WD10JPVT-08A1YT2 1TB             | 1         | 1.89%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB   | 1         | 1.89%   |
| Toshiba MQ04ABF100 1TB               | 1         | 1.89%   |
| Toshiba MQ01ABF050 500GB             | 1         | 1.89%   |
| Toshiba HDWD240 4TB                  | 1         | 1.89%   |
| Toshiba DT01ACA300 3TB               | 1         | 1.89%   |
| Seagate ST4000DM000-1F2168 4TB       | 1         | 1.89%   |
| Seagate ST380011A 80GB               | 1         | 1.89%   |
| Seagate ST3500630AS 500GB            | 1         | 1.89%   |
| Seagate ST3250820AS Q 250GB          | 1         | 1.89%   |
| Seagate ST3000VX006-1HH166 3TB       | 1         | 1.89%   |
| Seagate ST2000DM008-2FR102 2TB       | 1         | 1.89%   |
| Seagate ST1000NM004A-2MN130 1TB      | 1         | 1.89%   |
| Seagate ST1000DM010-2EP102 1TB       | 1         | 1.89%   |
| Seagate ST1000DM003-1SB102 1TB       | 1         | 1.89%   |
| Seagate Expansion Desk 4TB           | 1         | 1.89%   |
| SanDisk SDSSDA240G 240GB             | 1         | 1.89%   |
| Samsung SSD 980 PRO 500GB            | 1         | 1.89%   |
| Samsung SSD 970 EVO Plus 500GB       | 1         | 1.89%   |
| Samsung SSD 970 EVO Plus 1TB         | 1         | 1.89%   |
| Samsung SSD 970 EVO 250GB            | 1         | 1.89%   |
| Samsung SSD 860 QVO 2TB              | 1         | 1.89%   |
| Samsung SSD 860 EVO 500GB            | 1         | 1.89%   |
| Samsung SSD 860 500GB                | 1         | 1.89%   |
| Samsung SSD 840 Series 250GB         | 1         | 1.89%   |
| Samsung NVMe SSD Drive 256GB         | 1         | 1.89%   |
| Samsung MZVLQ512HALU-000H1 512GB     | 1         | 1.89%   |
| Samsung MZVKW512HMJP-000H1 512GB     | 1         | 1.89%   |
| Samsung MZHPV512HDGL-00000 512GB SSD | 1         | 1.89%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD | 1         | 1.89%   |
| Patriot Burst Elite 120GB SSD        | 1         | 1.89%   |
| Kingston SUV400S37240G 240GB SSD     | 1         | 1.89%   |
| Kingston SM2280S3G2120G 120GB SSD    | 1         | 1.89%   |
| Kingston SA400S37120G 120GB SSD      | 1         | 1.89%   |
| JMicron Generic 2TB                  | 1         | 1.89%   |
| Intenso SSD SATAIII 512GB            | 1         | 1.89%   |
| Hitachi HUA723030ALA640 3TB          | 1         | 1.89%   |
| Hitachi HTS545025B9A300 250GB        | 1         | 1.89%   |
| Hitachi HDS721016CLA382 160GB        | 1         | 1.89%   |
| HGST HUH728080ALE600 8TB             | 1         | 1.89%   |
| HP SSD EX950 2TB                     | 1         | 1.89%   |
| GOODRAM SSDPR-CX400-256-G2 256GB     | 1         | 1.89%   |
| Gigabyte GP-ASM2NE6100TTTD 1TB       | 1         | 1.89%   |
| External USB3.0 500GB                | 1         | 1.89%   |
| Crucial CT500P2SSD8 500GB            | 1         | 1.89%   |
| Crucial CT500MX500SSD1 500GB         | 1         | 1.89%   |
| Apple SSD SM256E 256GB               | 1         | 1.89%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 13     | 36.36%  |
| WDC     | 6         | 8      | 27.27%  |
| Toshiba | 4         | 6      | 18.18%  |
| Hitachi | 3         | 3      | 13.64%  |
| HGST    | 1         | 1      | 4.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 6      | 33.33%  |
| Kingston            | 3         | 4      | 20%     |
| SanDisk             | 1         | 1      | 6.67%   |
| Patriot             | 1         | 1      | 6.67%   |
| JMicron             | 1         | 1      | 6.67%   |
| Intenso             | 1         | 1      | 6.67%   |
| GOODRAM             | 1         | 1      | 6.67%   |
| Crucial             | 1         | 1      | 6.67%   |
| Apple               | 1         | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 31     | 41.46%  |
| SSD  | 13        | 17     | 31.71%  |
| NVMe | 11        | 13     | 26.83%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 23        | 46     | 63.89%  |
| NVMe | 10        | 12     | 27.78%  |
| SAS  | 3         | 3      | 8.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 17        | 21     | 48.57%  |
| 0.51-1.0   | 9         | 12     | 25.71%  |
| 1.01-2.0   | 4         | 6      | 11.43%  |
| 3.01-4.0   | 3         | 3      | 8.57%   |
| 2.01-3.0   | 1         | 5      | 2.86%   |
| 4.01-10.0  | 1         | 1      | 2.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 9         | 30%     |
| 101-250        | 6         | 20%     |
| 501-1000       | 6         | 20%     |
| 1001-2000      | 3         | 10%     |
| Unknown        | 2         | 6.67%   |
| More than 3000 | 1         | 3.33%   |
| 2001-3000      | 1         | 3.33%   |
| 1-20           | 1         | 3.33%   |
| 51-100         | 1         | 3.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 9         | 31.03%  |
| 21-50          | 6         | 20.69%  |
| 251-500        | 5         | 17.24%  |
| 1-20           | 4         | 13.79%  |
| Unknown        | 2         | 6.9%    |
| More than 3000 | 1         | 3.45%   |
| 501-1000       | 1         | 3.45%   |
| 51-100         | 1         | 3.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-22ERMA0 500GB   | 1         | 1      | 12.5%   |
| WDC WD3200AAJS-65B4A0 320GB    | 1         | 1      | 12.5%   |
| WDC WD20EFRX-68EUZN0 2TB       | 1         | 2      | 12.5%   |
| Seagate ST380011A 80GB         | 1         | 1      | 12.5%   |
| Seagate ST3500630AS 500GB      | 1         | 1      | 12.5%   |
| Seagate ST3000VX006-1HH166 3TB | 1         | 1      | 12.5%   |
| Hitachi HUA723030ALA640 3TB    | 1         | 1      | 12.5%   |
| Hitachi HDS721016CLA382 160GB  | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 4      | 37.5%   |
| Seagate | 3         | 3      | 37.5%   |
| Hitachi | 2         | 2      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 4      | 37.5%   |
| Seagate | 3         | 3      | 37.5%   |
| Hitachi | 2         | 2      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 9      | 100%    |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 25        | 44     | 69.44%  |
| Malfunc  | 6         | 9      | 16.67%  |
| Detected | 5         | 8      | 13.89%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 15        | 39.47%  |
| AMD                       | 8         | 21.05%  |
| Samsung Electronics       | 7         | 18.42%  |
| Sandisk                   | 1         | 2.63%   |
| Phison Electronics        | 1         | 2.63%   |
| Nvidia                    | 1         | 2.63%   |
| Micron/Crucial Technology | 1         | 2.63%   |
| Broadcom / LSI            | 1         | 2.63%   |
| Biwin Storage Technology  | 1         | 2.63%   |
| ASMedia Technology        | 1         | 2.63%   |
| Adaptec                   | 1         | 2.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 7         | 15.22%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3         | 6.52%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 6.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 4.35%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 4.35%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2         | 4.35%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2         | 4.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 4.35%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1         | 2.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 2.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 2.17%   |
| Samsung Electronics SATA controller                                                     | 1         | 2.17%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 2.17%   |
| Nvidia MCP79 AHCI Controller                                                            | 1         | 2.17%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1         | 2.17%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1         | 2.17%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1         | 2.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 1         | 2.17%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1         | 2.17%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1         | 2.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 1         | 2.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1         | 2.17%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1         | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 2.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1         | 2.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1         | 2.17%   |
| Broadcom / LSI SAS1068E PCI-Express Fusion-MPT SAS                                      | 1         | 2.17%   |
| Biwin Storage Non-Volatile memory controller                                            | 1         | 2.17%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1         | 2.17%   |
| Adaptec SCSI storage controller                                                         | 1         | 2.17%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 20        | 52.63%  |
| NVMe | 10        | 26.32%  |
| IDE  | 4         | 10.53%  |
| RAID | 2         | 5.26%   |
| SCSI | 2         | 5.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 21        | 72.41%  |
| AMD    | 8         | 27.59%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Xeon CPU X5680 @ 3.33GHz                | 1         | 3.45%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz           | 1         | 3.45%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz           | 1         | 3.45%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 3.45%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 3.45%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 3.45%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 3.45%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 3.45%   |
| Intel Core i5-8600K CPU @ 3.60GHz             | 1         | 3.45%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 3.45%   |
| Intel Core i5-3330 CPU @ 3.00GHz              | 1         | 3.45%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 3.45%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 3.45%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 3.45%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 3.45%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 1         | 3.45%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 3.45%   |
| Intel Atom CPU 330 @ 1.60GHz                  | 1         | 3.45%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 3.45%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 3.45%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 3.45%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 1         | 3.45%   |
| AMD Ryzen 9 4900HS with Radeon Graphics       | 1         | 3.45%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 1         | 3.45%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 1         | 3.45%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 3.45%   |
| AMD EPYC 7232P 8-Core Processor               | 1         | 3.45%   |
| AMD Athlon Silver 3050U with Radeon Graphics  | 1         | 3.45%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 1         | 3.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 5         | 17.24%  |
| Intel Core i5    | 5         | 17.24%  |
| Other            | 3         | 10.34%  |
| Intel Xeon       | 3         | 10.34%  |
| Intel Core 2 Duo | 2         | 6.9%    |
| AMD Ryzen 9      | 2         | 6.9%    |
| AMD Ryzen 7      | 2         | 6.9%    |
| Intel Core i3    | 1         | 3.45%   |
| Intel Celeron    | 1         | 3.45%   |
| Intel Atom       | 1         | 3.45%   |
| AMD Ryzen 5      | 1         | 3.45%   |
| AMD EPYC         | 1         | 3.45%   |
| AMD Athlon       | 1         | 3.45%   |
| AMD A8           | 1         | 3.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 9         | 31.03%  |
| 2      | 9         | 31.03%  |
| 8      | 6         | 20.69%  |
| 16     | 1         | 3.45%   |
| 14     | 1         | 3.45%   |
| 12     | 1         | 3.45%   |
| 10     | 1         | 3.45%   |
| 6      | 1         | 3.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 28        | 96.55%  |
| 2      | 1         | 3.45%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 22        | 75.86%  |
| 1      | 7         | 24.14%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 29        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 4         | 13.79%  |
| Unknown    | 4         | 13.79%  |
| 0x806c1    | 2         | 6.9%    |
| 0x306f2    | 2         | 6.9%    |
| 0x08108109 | 2         | 6.9%    |
| 0xa0652    | 1         | 3.45%   |
| 0x906ea    | 1         | 3.45%   |
| 0x906e9    | 1         | 3.45%   |
| 0x806ea    | 1         | 3.45%   |
| 0x806d1    | 1         | 3.45%   |
| 0x6fa      | 1         | 3.45%   |
| 0x406c4    | 1         | 3.45%   |
| 0x306d4    | 1         | 3.45%   |
| 0x206c2    | 1         | 3.45%   |
| 0x106c2    | 1         | 3.45%   |
| 0x1067a    | 1         | 3.45%   |
| 0x0a201016 | 1         | 3.45%   |
| 0x08701021 | 1         | 3.45%   |
| 0x0830104d | 1         | 3.45%   |
| 0x07030105 | 1         | 3.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Zen 2      | 4         | 13.79%  |
| KabyLake   | 4         | 13.79%  |
| IvyBridge  | 4         | 13.79%  |
| Zen+       | 2         | 6.9%    |
| Westmere   | 2         | 6.9%    |
| TigerLake  | 2         | 6.9%    |
| Haswell    | 2         | 6.9%    |
| Zen 3      | 1         | 3.45%   |
| Silvermont | 1         | 3.45%   |
| Puma       | 1         | 3.45%   |
| Penryn     | 1         | 3.45%   |
| Icelake    | 1         | 3.45%   |
| Core       | 1         | 3.45%   |
| CometLake  | 1         | 3.45%   |
| Broadwell  | 1         | 3.45%   |
| Bonnell    | 1         | 3.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 14        | 41.18%  |
| AMD                        | 11        | 32.35%  |
| Nvidia                     | 8         | 23.53%  |
| Matrox Electronics Systems | 1         | 2.94%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 8.82%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 5.88%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 5.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 5.88%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2         | 5.88%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 5.88%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 2.94%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 2.94%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 2.94%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 1         | 2.94%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 2.94%   |
| Nvidia C79 [ION]                                                                         | 1         | 2.94%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 1         | 2.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 2.94%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.94%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 2.94%   |
| Intel HD Graphics 5500                                                                   | 1         | 2.94%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.94%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 2.94%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 2.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.94%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1         | 2.94%   |
| AMD RV610/M74 [Mobility Radeon HD 2400 XT]                                               | 1         | 2.94%   |
| AMD Renoir                                                                               | 1         | 2.94%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 1         | 2.94%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1         | 2.94%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                                     | 1         | 2.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 10        | 34.48%  |
| 1 x AMD        | 10        | 34.48%  |
| Intel + Nvidia | 4         | 13.79%  |
| 1 x Nvidia     | 3         | 10.34%  |
| 1 x Matrox     | 1         | 3.45%   |
| AMD + Nvidia   | 1         | 3.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 27        | 93.1%   |
| Proprietary | 2         | 6.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 51.72%  |
| 7.01-8.0   | 3         | 10.34%  |
| 0.01-0.5   | 3         | 10.34%  |
| 5.01-6.0   | 2         | 6.9%    |
| 1.01-2.0   | 2         | 6.9%    |
| 8.01-16.0  | 2         | 6.9%    |
| 0.51-1.0   | 2         | 6.9%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 5         | 14.71%  |
| BOE                  | 5         | 14.71%  |
| LG Display           | 3         | 8.82%   |
| Hewlett-Packard      | 3         | 8.82%   |
| Ancor Communications | 3         | 8.82%   |
| BenQ                 | 2         | 5.88%   |
| Wacom                | 1         | 2.94%   |
| UGD                  | 1         | 2.94%   |
| Sony                 | 1         | 2.94%   |
| Sharp                | 1         | 2.94%   |
| PANDA                | 1         | 2.94%   |
| Lenovo               | 1         | 2.94%   |
| IOD                  | 1         | 2.94%   |
| Iiyama               | 1         | 2.94%   |
| Dell                 | 1         | 2.94%   |
| Chimei Innolux       | 1         | 2.94%   |
| AU Optronics         | 1         | 2.94%   |
| Apple                | 1         | 2.94%   |
| Acer                 | 1         | 2.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch              | 1         | 2.86%   |
| UGD LCD Monitor UGD1302 1920x1080 290x160mm 13.0-inch                 | 1         | 2.86%   |
| Sony TV SNY8102 1360x768 1600x900mm 72.3-inch                         | 1         | 2.86%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 2.86%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 2.86%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch  | 1         | 2.86%   |
| Samsung Electronics SMS27A650 SAM082D 1920x1080 600x340mm 27.2-inch   | 1         | 2.86%   |
| Samsung Electronics SM2333T SAM0736 1920x1080 510x290mm 23.1-inch     | 1         | 2.86%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 2.86%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 2.86%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch          | 1         | 2.86%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch          | 1         | 2.86%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch           | 1         | 2.86%   |
| Lenovo LEN L171 LEN24C9 1280x1024 337x270mm 17.0-inch                 | 1         | 2.86%   |
| IOD LCD-GL211X IOD151D 1920x1080 458x258mm 20.7-inch                  | 1         | 2.86%   |
| Iiyama PL2783Q IVM661F 2560x1440 600x340mm 27.2-inch                  | 1         | 2.86%   |
| Hewlett-Packard ALL-in-One HPN4021 1920x1080 476x268mm 21.5-inch      | 1         | 2.86%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 1         | 2.86%   |
| Hewlett-Packard 27m HPN3579 1920x1080 598x336mm 27.0-inch             | 1         | 2.86%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 1         | 2.86%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 1         | 2.86%   |
| BOE LCD Monitor BOE08F6 1920x1080 355x200mm 16.0-inch                 | 1         | 2.86%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 1         | 2.86%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 1         | 2.86%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                  | 1         | 2.86%   |
| BenQ VZ2770H BNQ7B3C 1920x1080 598x336mm 27.0-inch                    | 1         | 2.86%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 1         | 2.86%   |
| Apple Color LCD APP9C6A 1680x1050 433x270mm 20.1-inch                 | 1         | 2.86%   |
| Ancor Communications ROG PG348Q ACI3433 3440x1440 800x340mm 34.2-inch | 1         | 2.86%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 480x270mm 21.7-inch | 1         | 2.86%   |
| Ancor Communications ASUS MG28U ACI28A7 3840x2160 621x341mm 27.9-inch | 1         | 2.86%   |
| Acer AL1714 ACRAD18 1280x1024 338x270mm 17.0-inch                     | 1         | 2.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 16        | 50%     |
| 1366x768 (WXGA)    | 6         | 18.75%  |
| 1360x768           | 2         | 6.25%   |
| 1280x1024 (SXGA)   | 2         | 6.25%   |
| 3840x2160 (4K)     | 1         | 3.13%   |
| 3440x1440          | 1         | 3.13%   |
| 2560x1440 (QHD)    | 1         | 3.13%   |
| 2256x1504          | 1         | 3.13%   |
| 1680x1050 (WSXGA+) | 1         | 3.13%   |
| 1600x1200          | 1         | 3.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 6         | 17.65%  |
| 27     | 5         | 14.71%  |
| 21     | 4         | 11.76%  |
| 20     | 3         | 8.82%   |
| 14     | 3         | 8.82%   |
| 13     | 3         | 8.82%   |
| 24     | 2         | 5.88%   |
| 17     | 2         | 5.88%   |
| 72     | 1         | 2.94%   |
| 34     | 1         | 2.94%   |
| 23     | 1         | 2.94%   |
| 18     | 1         | 2.94%   |
| 16     | 1         | 2.94%   |
| 12     | 1         | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 12        | 36.36%  |
| 501-600     | 7         | 21.21%  |
| 401-500     | 7         | 21.21%  |
| 201-300     | 3         | 9.09%   |
| 701-800     | 1         | 3.03%   |
| 601-700     | 1         | 3.03%   |
| 351-400     | 1         | 3.03%   |
| 1501-2000   | 1         | 3.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 22        | 75.86%  |
| 5/4   | 2         | 6.9%    |
| 16/10 | 2         | 6.9%    |
| 4/3   | 1         | 3.45%   |
| 3/2   | 1         | 3.45%   |
| 21/9  | 1         | 3.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 7         | 21.21%  |
| 81-90          | 5         | 15.15%  |
| 301-350        | 5         | 15.15%  |
| 201-250        | 4         | 12.12%  |
| 151-200        | 4         | 12.12%  |
| 141-150        | 3         | 9.09%   |
| More than 1000 | 1         | 3.03%   |
| 71-80          | 1         | 3.03%   |
| 61-70          | 1         | 3.03%   |
| 351-500        | 1         | 3.03%   |
| 251-300        | 1         | 3.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 12        | 35.29%  |
| 51-100  | 11        | 32.35%  |
| 121-160 | 8         | 23.53%  |
| 161-240 | 2         | 5.88%   |
| 1-50    | 1         | 2.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 22        | 75.86%  |
| 2     | 3         | 10.34%  |
| 0     | 2         | 6.9%    |
| 4     | 1         | 3.45%   |
| 3     | 1         | 3.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 14        | 36.84%  |
| Intel                    | 14        | 36.84%  |
| Broadcom                 | 3         | 7.89%   |
| Broadcom Limited         | 2         | 5.26%   |
| Ralink Technology        | 1         | 2.63%   |
| Ralink                   | 1         | 2.63%   |
| Qualcomm Atheros         | 1         | 2.63%   |
| Nvidia                   | 1         | 2.63%   |
| Marvell Technology Group | 1         | 2.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 23.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 6.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 4.26%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 4.26%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 2.13%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 2.13%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 2.13%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1         | 2.13%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 2.13%   |
| Nvidia MCP79 Ethernet                                             | 1         | 2.13%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 2.13%   |
| Intel Wireless-AC 9260                                            | 1         | 2.13%   |
| Intel Wireless 8265 / 8275                                        | 1         | 2.13%   |
| Intel Wireless 3165                                               | 1         | 2.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 2.13%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 2.13%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 2.13%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 2.13%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.13%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 2.13%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 2.13%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 2.13%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 2.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 2.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.13%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 2.13%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 2.13%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 2.13%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1         | 2.13%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1         | 2.13%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                           | 1         | 2.13%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 1         | 2.13%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 1         | 2.13%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 10        | 50%     |
| Realtek Semiconductor | 4         | 20%     |
| Broadcom              | 2         | 10%     |
| Ralink Technology     | 1         | 5%      |
| Ralink                | 1         | 5%      |
| Qualcomm Atheros      | 1         | 5%      |
| Broadcom Limited      | 1         | 5%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 10%     |
| Intel Wi-Fi 6 AX200                                            | 2         | 10%     |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 5%      |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 5%      |
| Ralink MT7601U Wireless Adapter                                | 1         | 5%      |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1         | 5%      |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 5%      |
| Intel Wireless-AC 9260                                         | 1         | 5%      |
| Intel Wireless 8265 / 8275                                     | 1         | 5%      |
| Intel Wireless 3165                                            | 1         | 5%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 5%      |
| Intel Wi-Fi 6 AX201                                            | 1         | 5%      |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 5%      |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 5%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1         | 5%      |
| Broadcom Limited BCM43228 802.11a/b/g/n                        | 1         | 5%      |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 5%      |
| Broadcom BCM4321 802.11a/b/g/n                                 | 1         | 5%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 14        | 53.85%  |
| Intel                    | 7         | 26.92%  |
| Broadcom                 | 2         | 7.69%   |
| Nvidia                   | 1         | 3.85%   |
| Marvell Technology Group | 1         | 3.85%   |
| Broadcom Limited         | 1         | 3.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 40.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 11.11%  |
| Nvidia MCP79 Ethernet                                             | 1         | 3.7%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 3.7%    |
| Intel Ethernet Connection (7) I219-V                              | 1         | 3.7%    |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 3.7%    |
| Intel Ethernet Connection (2) I219-V                              | 1         | 3.7%    |
| Intel Ethernet Connection (2) I218-V                              | 1         | 3.7%    |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 3.7%    |
| Intel 82576 Gigabit Network Connection                            | 1         | 3.7%    |
| Intel 82574L Gigabit Network Connection                           | 1         | 3.7%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 3.7%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1         | 3.7%    |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1         | 3.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 25        | 55.56%  |
| WiFi     | 20        | 44.44%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 18        | 56.25%  |
| WiFi     | 14        | 43.75%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 15        | 51.72%  |
| 1     | 12        | 41.38%  |
| 4     | 1         | 3.45%   |
| 3     | 1         | 3.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 25        | 86.21%  |
| Yes  | 4         | 13.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 9         | 50%     |
| Realtek Semiconductor   | 3         | 16.67%  |
| Cambridge Silicon Radio | 2         | 11.11%  |
| Broadcom                | 2         | 11.11%  |
| Apple                   | 2         | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 16.67%  |
| Intel AX201 Bluetooth                               | 3         | 16.67%  |
| Intel Bluetooth wireless interface                  | 2         | 11.11%  |
| Intel AX200 Bluetooth                               | 2         | 11.11%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 11.11%  |
| Intel Bluetooth Device                              | 1         | 5.56%   |
| Intel AX210 Bluetooth                               | 1         | 5.56%   |
| Broadcom BCM20702A0                                 | 1         | 5.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 5.56%   |
| Apple Bluetooth USB Host Controller                 | 1         | 5.56%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 16        | 39.02%  |
| AMD                    | 10        | 24.39%  |
| Nvidia                 | 8         | 19.51%  |
| Creative Labs          | 3         | 7.32%   |
| C-Media Electronics    | 2         | 4.88%   |
| Generalplus Technology | 1         | 2.44%   |
| ASUSTek Computer       | 1         | 2.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 6.12%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 6.12%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 6.12%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 4.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 4.08%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 2         | 4.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 4.08%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 4.08%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 4.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 2.04%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 2.04%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 2.04%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 2.04%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 2.04%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 2.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 2.04%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 2.04%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1         | 2.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 2.04%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 2.04%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 2.04%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 2.04%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 2.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.04%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 2.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 2.04%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 2.04%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]                         | 1         | 2.04%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                                     | 1         | 2.04%   |
| C-Media Electronics CM6631A Audio Processor                                                       | 1         | 2.04%   |
| ASUSTek Computer XONAR SOUND CARD                                                                 | 1         | 2.04%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 2.04%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 2.04%   |
| AMD FCH Azalia Controller                                                                         | 1         | 2.04%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 2.04%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 2.04%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 6         | 20%     |
| SK Hynix            | 5         | 16.67%  |
| Samsung Electronics | 5         | 16.67%  |
| Crucial             | 3         | 10%     |
| Micron Technology   | 2         | 6.67%   |
| A-DATA Technology   | 2         | 6.67%   |
| Unknown             | 1         | 3.33%   |
| Team                | 1         | 3.33%   |
| Strontium           | 1         | 3.33%   |
| Neo Forza           | 1         | 3.33%   |
| GOODRAM             | 1         | 3.33%   |
| G.Skill             | 1         | 3.33%   |
| Essencore Limited   | 1         | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                                 | 1         | 2.86%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s                   | 1         | 2.86%   |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s                | 1         | 2.86%   |
| SK Hynix RAM HMT41GV7BMR4A-H9 16GB DIMM 1333MT/s                     | 1         | 2.86%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s               | 1         | 2.86%   |
| SK Hynix RAM HMT31GR7BFR4A-H9 16GB DIMM 1333MT/s                     | 1         | 2.86%   |
| SK Hynix RAM HMT125R7BFR8C-H9 4GB DIMM 1333MT/s                      | 1         | 2.86%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s            | 1         | 2.86%   |
| SK Hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s               | 1         | 2.86%   |
| SK Hynix RAM HMA81GR7CJR8N-XN 8192MB DIMM DDR4 3200MT/s              | 1         | 2.86%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s                | 1         | 2.86%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                | 1         | 2.86%   |
| Samsung RAM M393A2G40DB0-CPB 16GB RIMM DDR4 2133MT/s                 | 1         | 2.86%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s                  | 1         | 2.86%   |
| Samsung RAM M393A1G43EB1-CRC 8GB DIMM DDR4 2400MT/s                  | 1         | 2.86%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s                  | 1         | 2.86%   |
| Neo Forza RAM NMSO480E82-3200E 8GB SODIMM DDR4 3200MT/s              | 1         | 2.86%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                 | 1         | 2.86%   |
| Micron RAM 16KTF51264HZ-1G4 4096MB SODIMM DDR3 701MT/s               | 1         | 2.86%   |
| Kingston RAM Module 8192MB SODIMM DDR3 1600MT/s                      | 1         | 2.86%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.86%   |
| Kingston RAM KHX3333C16D4/8GX 8GB DIMM DDR4 3800MT/s                 | 1         | 2.86%   |
| Kingston RAM ACR128X64D2S800C6 1GB SODIMM DDR2 800MT/s               | 1         | 2.86%   |
| Kingston RAM 9905712-007.A00G 16384MB SODIMM DDR4 2400MT/s           | 1         | 2.86%   |
| Kingston RAM 9905711-032.A00G 8GB SODIMM DDR4 2667MT/s               | 1         | 2.86%   |
| Kingston RAM 9905703-011.A00G 16GB SODIMM DDR4 2400MT/s              | 1         | 2.86%   |
| GOODRAM RAM GR2400S464L17S/4G 4096MB SODIMM DDR4 2400MT/s            | 1         | 2.86%   |
| G.Skill RAM F4-3200C16-16GTZSW 16384MB DIMM DDR4 3200MT/s            | 1         | 2.86%   |
| Essencore Limited RAM KD4AGSA8M-26N1900 16384MB SODIMM DDR4 2667MT/s | 1         | 2.86%   |
| Crucial RAM Module 2048MB SODIMM DDR2 667MT/s                        | 1         | 2.86%   |
| Crucial RAM BLS4G4D240FSB.8FBD2 4GB DIMM DDR4 2400MT/s               | 1         | 2.86%   |
| Crucial RAM BLS4G4D240FSB.8FBD 4GB DIMM DDR4 2400MT/s                | 1         | 2.86%   |
| Crucial RAM BL8G32C16S4B.8FE 8GB SODIMM DDR4 2667MT/s                | 1         | 2.86%   |
| A-DATA RAM Module 4096MB DIMM DDR3 1333MT/s                          | 1         | 2.86%   |
| A-DATA RAM AO1L16BC4R1-BX7S 4096MB SODIMM DDR3 1600MT/s              | 1         | 2.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 15        | 55.56%  |
| DDR3    | 8         | 29.63%  |
| DDR2    | 2         | 7.41%   |
| SDRAM   | 1         | 3.7%    |
| Unknown | 1         | 3.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 15        | 57.69%  |
| DIMM   | 10        | 38.46%  |
| RIMM   | 1         | 3.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 11        | 39.29%  |
| 8192  | 8         | 28.57%  |
| 16384 | 5         | 17.86%  |
| 2048  | 2         | 7.14%   |
| 32768 | 1         | 3.57%   |
| 1024  | 1         | 3.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 7         | 25%     |
| 1600    | 6         | 21.43%  |
| 2400    | 4         | 14.29%  |
| 2667    | 3         | 10.71%  |
| 1333    | 2         | 7.14%   |
| 3800    | 1         | 3.57%   |
| 2133    | 1         | 3.57%   |
| 800     | 1         | 3.57%   |
| 701     | 1         | 3.57%   |
| 667     | 1         | 3.57%   |
| Unknown | 1         | 3.57%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| QinHeng Electronics | 1         | 25%     |
| Hewlett-Packard     | 1         | 25%     |
| Dell                | 1         | 25%     |
| Canon               | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| QinHeng CH340S               | 1         | 25%     |
| HP OfficeJet Pro 9010 series | 1         | 25%     |
| Dell 2330d Laser Printer     | 1         | 25%     |
| Canon CanoScan LiDE 300      | 1         | 25%     |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 4         | 23.53%  |
| Acer                                   | 3         | 17.65%  |
| Microdia                               | 2         | 11.76%  |
| Logitech                               | 2         | 11.76%  |
| Cheng Uei Precision Industry (Foxlink) | 2         | 11.76%  |
| Samsung Electronics                    | 1         | 5.88%   |
| Realtek Semiconductor                  | 1         | 5.88%   |
| Quanta                                 | 1         | 5.88%   |
| Apple                                  | 1         | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung Galaxy series, misc. (MTP mode)                        | 1         | 5.88%   |
| Realtek Laptop Camera                                          | 1         | 5.88%   |
| Quanta HP Webcam                                               | 1         | 5.88%   |
| Microdia Laptop_Integrated_Webcam_2M                           | 1         | 5.88%   |
| Microdia Integrated Webcam                                     | 1         | 5.88%   |
| Logitech QuickCam Pro 9000                                     | 1         | 5.88%   |
| Logitech C922 Pro Stream Webcam                                | 1         | 5.88%   |
| Chicony Web Camera - FHD                                       | 1         | 5.88%   |
| Chicony Integrated Camera [ThinkPad]                           | 1         | 5.88%   |
| Chicony HP TrueVision HD Camera                                | 1         | 5.88%   |
| Chicony HP HD Camera                                           | 1         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) HP 5M Camera            | 1         | 5.88%   |
| Apple Built-in iSight                                          | 1         | 5.88%   |
| Acer ThinkPad Integrated Camera                                | 1         | 5.88%   |
| Acer HD Webcam                                                 | 1         | 5.88%   |
| Acer BisonCam,NB Pro                                           | 1         | 5.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 1         | 50%     |
| Synaptics        | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS300 Fingerprint Reader | 1         | 50%     |
| Unknown                                    | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 21        | 72.41%  |
| 1     | 7         | 24.14%  |
| 3     | 1         | 3.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Unassigned class         | 2         | 20%     |
| Fingerprint reader       | 2         | 20%     |
| Sound                    | 1         | 10%     |
| Multimedia controller    | 1         | 10%     |
| Graphics card            | 1         | 10%     |
| Communication controller | 1         | 10%     |
| Chipcard                 | 1         | 10%     |
| Bluetooth                | 1         | 10%     |

