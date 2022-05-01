Q4OS - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for Q4OS.

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

Total: 29

| Vendor        | Model                   | Probe                                                      | Date         |
|---------------|-------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 330-15IGM 81D1  | [8cdcd8d130](https://linux-hardware.org/?probe=8cdcd8d130) | Apr 08, 2022 |
| Acer          | AO751h                  | [23737182d1](https://linux-hardware.org/?probe=23737182d1) | Mar 21, 2022 |
| AMI           | Intel                   | [6d581b03a6](https://linux-hardware.org/?probe=6d581b03a6) | Mar 19, 2022 |
| ASUSTek       | X540YA                  | [0cd3840828](https://linux-hardware.org/?probe=0cd3840828) | Mar 14, 2022 |
| Visual Lan... | Premier 10              | [64450e11a3](https://linux-hardware.org/?probe=64450e11a3) | Feb 04, 2022 |
| HP            | Presario CQ56           | [8d03d80424](https://linux-hardware.org/?probe=8d03d80424) | Jan 14, 2022 |
| HP            | Presario CQ56           | [a0bc0364a8](https://linux-hardware.org/?probe=a0bc0364a8) | Jan 08, 2022 |
| MSI           | U210                    | [24eb05a4d9](https://linux-hardware.org/?probe=24eb05a4d9) | Dec 29, 2021 |
| Toshiba       | Satellite C660          | [b159811d48](https://linux-hardware.org/?probe=b159811d48) | Dec 12, 2021 |
| Toshiba       | Satellite C660          | [2197770fd0](https://linux-hardware.org/?probe=2197770fd0) | Dec 12, 2021 |
| ASUSTek       | T12Eg                   | [115e8b584f](https://linux-hardware.org/?probe=115e8b584f) | Dec 11, 2021 |
| Toshiba       | Satellite C660          | [64521297e2](https://linux-hardware.org/?probe=64521297e2) | Dec 07, 2021 |
| Toshiba       | Satellite C660          | [b6a5bb8982](https://linux-hardware.org/?probe=b6a5bb8982) | Dec 06, 2021 |
| Phoenix/Si... | M720SR                  | [f92c7e8c3e](https://linux-hardware.org/?probe=f92c7e8c3e) | Oct 09, 2021 |
| HP            | Laptop 15s-fq2xxx       | [cfa6202518](https://linux-hardware.org/?probe=cfa6202518) | Sep 14, 2021 |
| HP            | Laptop 15s-fq2xxx       | [726c3230ef](https://linux-hardware.org/?probe=726c3230ef) | Sep 14, 2021 |
| Chuwi         | GemiBook Pro            | [ebe8d67a10](https://linux-hardware.org/?probe=ebe8d67a10) | Sep 04, 2021 |
| HP            | ProBook 450 G2          | [dbba9b9771](https://linux-hardware.org/?probe=dbba9b9771) | Jul 30, 2021 |
| JVC           | J3N                     | [f8da57e850](https://linux-hardware.org/?probe=f8da57e850) | Jul 09, 2021 |
| HP            | ProBook 6550b           | [b192718656](https://linux-hardware.org/?probe=b192718656) | Mar 13, 2021 |
| HP            | 2000                    | [736561e497](https://linux-hardware.org/?probe=736561e497) | Mar 07, 2021 |
| ASUSTek       | A6JC                    | [b04f51dd1c](https://linux-hardware.org/?probe=b04f51dd1c) | Jan 29, 2021 |
| ASUSTek       | A6JC                    | [097dd7f151](https://linux-hardware.org/?probe=097dd7f151) | Jan 29, 2021 |
| Lenovo        | ThinkPad 11e 20DAS0PS00 | [2d618b7420](https://linux-hardware.org/?probe=2d618b7420) | Dec 14, 2020 |
| Packard Be... | EasyNote LM81           | [d6b0c23c18](https://linux-hardware.org/?probe=d6b0c23c18) | Nov 23, 2020 |
| Qilive        | QW19141AMSP             | [b8f3486ae1](https://linux-hardware.org/?probe=b8f3486ae1) | Aug 27, 2020 |
| HP            | OmniBook PC             | [5e33febbc1](https://linux-hardware.org/?probe=5e33febbc1) | Jul 10, 2020 |
| Unknown       | MEDION                  | [6a06a14f6a](https://linux-hardware.org/?probe=6a06a14f6a) | May 07, 2020 |
| Philco        | 14I                     | [bf4c449b31](https://linux-hardware.org/?probe=bf4c449b31) | Apr 14, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Q4OS 4      | 8         | 33.33%  |
| Q4OS 3      | 3         | 12.5%   |
| Q4OS 4.5.3  | 2         | 8.33%   |
| Q4OS 3.15.1 | 2         | 8.33%   |
| Q4OS 3.12.1 | 2         | 8.33%   |
| Q4OS 4.3.2  | 1         | 4.17%   |
| Q4OS 4.0.0  | 1         | 4.17%   |
| Q4OS 3.14.2 | 1         | 4.17%   |
| Q4OS 3.11.4 | 1         | 4.17%   |
| Q4OS 2.7.3  | 1         | 4.17%   |
| Q4OS 2.7.2  | 1         | 4.17%   |
| Q4OS 2      | 1         | 4.17%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Q4OS | 24        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 4.19.0-17-amd64   | 4         | 16.67%  |
| 5.10.0-12-amd64   | 3         | 12.5%   |
| 5.10.0-8-amd64    | 2         | 8.33%   |
| 5.9.0-5-amd64     | 1         | 4.17%   |
| 5.6.0-1-amd64     | 1         | 4.17%   |
| 5.10.0-9-amd64    | 1         | 4.17%   |
| 5.10.0-8-686-pae  | 1         | 4.17%   |
| 5.10.0-12-686-pae | 1         | 4.17%   |
| 5.10.0-11-686-pae | 1         | 4.17%   |
| 5.10.0-10-686-pae | 1         | 4.17%   |
| 4.9.0-8-amd64     | 1         | 4.17%   |
| 4.9.0-14-686-pae  | 1         | 4.17%   |
| 4.9.0-12-686-pae  | 1         | 4.17%   |
| 4.19.0-17-686     | 1         | 4.17%   |
| 4.19.0-14-amd64   | 1         | 4.17%   |
| 4.19.0-13-amd64   | 1         | 4.17%   |
| 4.19.0-12-amd64   | 1         | 4.17%   |
| 4.19.0-10-amd64   | 1         | 4.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 10        | 41.67%  |
| 4.19.0  | 9         | 37.5%   |
| 4.9.0   | 3         | 12.5%   |
| 5.9.0   | 1         | 4.17%   |
| 5.6.0   | 1         | 4.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 10        | 41.67%  |
| 4.19    | 9         | 37.5%   |
| 4.9     | 3         | 12.5%   |
| 5.9     | 1         | 4.17%   |
| 5.6     | 1         | 4.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 17        | 70.83%  |
| i686   | 7         | 29.17%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| KDE5    | 13        | 54.17%  |
| trinity | 10        | 41.67%  |
| KDE     | 1         | 4.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 23        | 95.83%  |
| Tty  | 1         | 4.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SDDM | 14        | 58.33%  |
| TDM  | 10        | 41.67%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 12        | 50%     |
| es_ES   | 2         | 8.33%   |
| en_GB   | 2         | 8.33%   |
| sl_SI   | 1         | 4.17%   |
| pl_PL   | 1         | 4.17%   |
| fr_FR   | 1         | 4.17%   |
| es_VE   | 1         | 4.17%   |
| en_SG   | 1         | 4.17%   |
| de_DE   | 1         | 4.17%   |
| C       | 1         | 4.17%   |
| Unknown | 1         | 4.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 14        | 58.33%  |
| EFI  | 10        | 41.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 21        | 87.5%   |
| Overlay | 3         | 12.5%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 13        | 54.17%  |
| GPT     | 10        | 41.67%  |
| Unknown | 1         | 4.17%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 19        | 79.17%  |
| Yes       | 5         | 20.83%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 16        | 66.67%  |
| Yes       | 8         | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 6         | 25%     |
| ASUSTek Computer | 3         | 12.5%   |
| Toshiba          | 2         | 8.33%   |
| Lenovo           | 2         | 8.33%   |
| Visual Land      | 1         | 4.17%   |
| Qilive           | 1         | 4.17%   |
| Phoenix/SiS      | 1         | 4.17%   |
| Philco           | 1         | 4.17%   |
| Packard Bell     | 1         | 4.17%   |
| MSI              | 1         | 4.17%   |
| JVC              | 1         | 4.17%   |
| Chuwi            | 1         | 4.17%   |
| AMI              | 1         | 4.17%   |
| Acer             | 1         | 4.17%   |
| Unknown          | 1         | 4.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Toshiba Satellite C660         | 2         | 8.33%   |
| Visual Land Premier 10         | 1         | 4.17%   |
| Qilive QW19141AMSP             | 1         | 4.17%   |
| Phoenix/SiS M720SR             | 1         | 4.17%   |
| Philco 14I                     | 1         | 4.17%   |
| Packard Bell EasyNote LM81     | 1         | 4.17%   |
| MSI U210                       | 1         | 4.17%   |
| Lenovo ThinkPad 11e 20DAS0PS00 | 1         | 4.17%   |
| Lenovo IdeaPad 330-15IGM 81D1  | 1         | 4.17%   |
| JVC J3N                        | 1         | 4.17%   |
| HP ProBook 6550b               | 1         | 4.17%   |
| HP ProBook 450 G2              | 1         | 4.17%   |
| HP Presario CQ56               | 1         | 4.17%   |
| HP OmniBook PC                 | 1         | 4.17%   |
| HP Laptop 15s-fq2xxx           | 1         | 4.17%   |
| HP 2000                        | 1         | 4.17%   |
| Chuwi GemiBook Pro             | 1         | 4.17%   |
| ASUS X540YA                    | 1         | 4.17%   |
| ASUS T12Eg                     | 1         | 4.17%   |
| ASUS A6JC                      | 1         | 4.17%   |
| AMI Intel                      | 1         | 4.17%   |
| Acer AO751h                    | 1         | 4.17%   |
| Unknown                        | 1         | 4.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Toshiba Satellite     | 2         | 8.33%   |
| HP ProBook            | 2         | 8.33%   |
| Visual Land Premier   | 1         | 4.17%   |
| Qilive QW19141AMSP    | 1         | 4.17%   |
| Phoenix/SiS M720SR    | 1         | 4.17%   |
| Philco 14I            | 1         | 4.17%   |
| Packard Bell EasyNote | 1         | 4.17%   |
| MSI U210              | 1         | 4.17%   |
| Lenovo ThinkPad       | 1         | 4.17%   |
| Lenovo IdeaPad        | 1         | 4.17%   |
| JVC J3N               | 1         | 4.17%   |
| HP Presario           | 1         | 4.17%   |
| HP OmniBook           | 1         | 4.17%   |
| HP Laptop             | 1         | 4.17%   |
| HP 2000               | 1         | 4.17%   |
| Chuwi GemiBook        | 1         | 4.17%   |
| ASUS X540YA           | 1         | 4.17%   |
| ASUS T12Eg            | 1         | 4.17%   |
| ASUS A6JC             | 1         | 4.17%   |
| AMI Intel             | 1         | 4.17%   |
| Acer AO751h           | 1         | 4.17%   |
| Unknown               | 1         | 4.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2010    | 5         | 20.83%  |
| 2020    | 3         | 12.5%   |
| 2014    | 2         | 8.33%   |
| 2009    | 2         | 8.33%   |
| Unknown | 2         | 8.33%   |
| 2019    | 1         | 4.17%   |
| 2018    | 1         | 4.17%   |
| 2017    | 1         | 4.17%   |
| 2016    | 1         | 4.17%   |
| 2015    | 1         | 4.17%   |
| 2012    | 1         | 4.17%   |
| 2011    | 1         | 4.17%   |
| 2007    | 1         | 4.17%   |
| 2006    | 1         | 4.17%   |
| 2004    | 1         | 4.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 24        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 23        | 95.83%  |
| Enabled  | 1         | 4.17%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 24        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 8         | 33.33%  |
| 4.01-8.0   | 4         | 16.67%  |
| 1.01-2.0   | 4         | 16.67%  |
| 2.01-3.0   | 3         | 12.5%   |
| 0.51-1.0   | 3         | 12.5%   |
| 16.01-24.0 | 1         | 4.17%   |
| 0.01-0.5   | 1         | 4.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 11        | 45.83%  |
| 0.51-1.0 | 6         | 25%     |
| 2.01-3.0 | 4         | 16.67%  |
| 0.01-0.5 | 2         | 8.33%   |
| 3.01-4.0 | 1         | 4.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 19        | 79.17%  |
| 2      | 4         | 16.67%  |
| 3      | 1         | 4.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 13        | 54.17%  |
| No        | 11        | 45.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 83.33%  |
| No        | 4         | 16.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 87.5%   |
| No        | 3         | 12.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 13        | 54.17%  |
| Yes       | 11        | 45.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 3         | 12.5%   |
| Kenya        | 3         | 12.5%   |
| UK           | 2         | 8.33%   |
| Spain        | 2         | 8.33%   |
| Romania      | 2         | 8.33%   |
| Poland       | 2         | 8.33%   |
| Venezuela    | 1         | 4.17%   |
| Slovenia     | 1         | 4.17%   |
| Singapore    | 1         | 4.17%   |
| Saudi Arabia | 1         | 4.17%   |
| Qatar        | 1         | 4.17%   |
| Italy        | 1         | 4.17%   |
| Germany      | 1         | 4.17%   |
| France       | 1         | 4.17%   |
| Brazil       | 1         | 4.17%   |
| Belarus      | 1         | 4.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Nairobi               | 3         | 12.5%   |
| Swindon               | 2         | 8.33%   |
| Drobeta-Turnu Severin | 2         | 8.33%   |
| Wygledy               | 1         | 4.17%   |
| Tellico Plains        | 1         | 4.17%   |
| Singapore             | 1         | 4.17%   |
| Rostock               | 1         | 4.17%   |
| Moirans               | 1         | 4.17%   |
| Mogilev               | 1         | 4.17%   |
| Mestre                | 1         | 4.17%   |
| Mesa                  | 1         | 4.17%   |
| Londrina              | 1         | 4.17%   |
| Ljubljana             | 1         | 4.17%   |
| Las Vegas             | 1         | 4.17%   |
| Katowice              | 1         | 4.17%   |
| GijГіn              | 1         | 4.17%   |
| Doha                  | 1         | 4.17%   |
| Dammam                | 1         | 4.17%   |
| Barcelona             | 1         | 4.17%   |
| Agua Salada           | 1         | 4.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 12%     |
| Unknown             | 3         | 3      | 12%     |
| Hitachi             | 3         | 3      | 12%     |
| Seagate             | 2         | 2      | 8%      |
| SanDisk             | 2         | 2      | 8%      |
| Samsung Electronics | 2         | 2      | 8%      |
| KESU                | 2         | 2      | 8%      |
| HGST                | 2         | 2      | 8%      |
| China               | 2         | 2      | 8%      |
| Toshiba             | 1         | 1      | 4%      |
| Kingston            | 1         | 1      | 4%      |
| Fujitsu             | 1         | 1      | 4%      |
| A-DATA Technology   | 1         | 1      | 4%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| KESU USB 3.1 128GB                   | 2         | 8%      |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 4%      |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 4%      |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 4%      |
| Unknown USDU1  32GB                  | 1         | 4%      |
| Unknown SLD64G  64GB                 | 1         | 4%      |
| Unknown 064G38  64GB                 | 1         | 4%      |
| Toshiba MK8025GAS 80GB               | 1         | 4%      |
| Seagate ST9120822AS 120GB            | 1         | 4%      |
| Seagate Backup+ SL 1TB               | 1         | 4%      |
| SanDisk SDCFX-032G SSD               | 1         | 4%      |
| SanDisk SD8SN8U1T001122 1024GB SSD   | 1         | 4%      |
| Samsung SSD 850 EVO 250GB            | 1         | 4%      |
| Samsung AWMB3R  16GB                 | 1         | 4%      |
| Kingston SV300S37A60G 64GB SSD       | 1         | 4%      |
| Hitachi HTS545032B9A300 320GB        | 1         | 4%      |
| Hitachi HTS543225L9SA00 250GB        | 1         | 4%      |
| Hitachi DK23CA-20 20GB               | 1         | 4%      |
| HGST HTS725050A7E630 500GB           | 1         | 4%      |
| HGST HTS541075A9E680 752GB           | 1         | 4%      |
| Fujitsu MHY2080BH 80GB               | 1         | 4%      |
| China SSD128GBS800                   | 1         | 4%      |
| China SATA SSD 240GB                 | 1         | 4%      |
| A-DATA SU630 240GB SSD               | 1         | 4%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 3         | 3      | 30%     |
| WDC     | 2         | 2      | 20%     |
| HGST    | 2         | 2      | 20%     |
| Toshiba | 1         | 1      | 10%     |
| Seagate | 1         | 1      | 10%     |
| Fujitsu | 1         | 1      | 10%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 2         | 2      | 28.57%  |
| China               | 2         | 2      | 28.57%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Kingston            | 1         | 1      | 14.29%  |
| A-DATA Technology   | 1         | 1      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 10        | 10     | 40%     |
| SSD     | 7         | 7      | 28%     |
| MMC     | 4         | 4      | 16%     |
| Unknown | 3         | 3      | 12%     |
| NVMe    | 1         | 1      | 4%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 17        | 17     | 68%     |
| MMC  | 4         | 4      | 16%     |
| SAS  | 3         | 3      | 12%     |
| NVMe | 1         | 1      | 4%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 15        | 15     | 88.24%  |
| 1.01-2.0   | 1         | 1      | 5.88%   |
| 0.51-1.0   | 1         | 1      | 5.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 5         | 20.83%  |
| 51-100     | 5         | 20.83%  |
| 21-50      | 4         | 16.67%  |
| 101-250    | 4         | 16.67%  |
| 251-500    | 3         | 12.5%   |
| 1001-2000  | 1         | 4.17%   |
| 501-1000   | 1         | 4.17%   |
| Unknown    | 1         | 4.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 17        | 70.83%  |
| 21-50    | 4         | 16.67%  |
| 251-500  | 1         | 4.17%   |
| 501-1000 | 1         | 4.17%   |
| Unknown  | 1         | 4.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-60A23T0 250GB  | 1         | 1      | 12.5%   |
| Seagate ST9120822AS 120GB     | 1         | 1      | 12.5%   |
| Hitachi HTS545032B9A300 320GB | 1         | 1      | 12.5%   |
| Hitachi HTS543225L9SA00 250GB | 1         | 1      | 12.5%   |
| Hitachi DK23CA-20 20GB        | 1         | 1      | 12.5%   |
| HGST HTS725050A7E630 500GB    | 1         | 1      | 12.5%   |
| HGST HTS541075A9E680 752GB    | 1         | 1      | 12.5%   |
| Fujitsu MHY2080BH 80GB        | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 3         | 3      | 37.5%   |
| HGST    | 2         | 2      | 25%     |
| WDC     | 1         | 1      | 12.5%   |
| Seagate | 1         | 1      | 12.5%   |
| Fujitsu | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 3         | 3      | 37.5%   |
| HGST    | 2         | 2      | 25%     |
| WDC     | 1         | 1      | 12.5%   |
| Seagate | 1         | 1      | 12.5%   |
| Fujitsu | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 8      | 100%    |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 9         | 9      | 37.5%   |
| Malfunc  | 8         | 8      | 33.33%  |
| Detected | 7         | 8      | 29.17%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 15        | 65.22%  |
| AMD                              | 6         | 26.09%  |
| Silicon Integrated Systems [SiS] | 1         | 4.35%   |
| Sandisk                          | 1         | 4.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 3         | 11.54%  |
| AMD FCH SATA Controller [AHCI mode]                                          | 3         | 11.54%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 2         | 7.69%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                  | 1         | 3.85%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                         | 1         | 3.85%   |
| Sandisk WD Blue SN550 NVMe SSD                                               | 1         | 3.85%   |
| Intel Volume Management Device NVMe RAID Controller                          | 1         | 3.85%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                   | 1         | 3.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 1         | 3.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 1         | 3.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                 | 1         | 3.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 1         | 3.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 1         | 3.85%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                       | 1         | 3.85%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                | 1         | 3.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 3.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 1         | 3.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                             | 1         | 3.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 1         | 3.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                         | 1         | 3.85%   |
| AMD SB600 Non-Raid-5 SATA                                                    | 1         | 3.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 15        | 62.5%   |
| IDE  | 7         | 29.17%  |
| RAID | 1         | 4.17%   |
| NVMe | 1         | 4.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 18        | 75%     |
| AMD    | 6         | 25%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 8.33%   |
| Intel Pentium M processor 1000MHz             | 1         | 4.17%   |
| Intel Pentium III (Coppermine)                | 1         | 4.17%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 4.17%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 4.17%   |
| Intel Core i5 CPU M 450 @ 2.40GHz             | 1         | 4.17%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 1         | 4.17%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz          | 1         | 4.17%   |
| Intel Core 2 CPU T5500 @ 1.66GHz              | 1         | 4.17%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 4.17%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 4.17%   |
| Intel Celeron J4115 CPU @ 1.80GHz             | 1         | 4.17%   |
| Intel Celeron CPU N2940 @ 1.83GHz             | 1         | 4.17%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 1         | 4.17%   |
| Intel Atom CPU Z520 @ 1.33GHz                 | 1         | 4.17%   |
| Intel Atom CPU Z3735G @ 1.33GHz               | 1         | 4.17%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 4.17%   |
| AMD V120 Processor                            | 1         | 4.17%   |
| AMD E-300 APU with Radeon HD Graphics         | 1         | 4.17%   |
| AMD C-70 APU with Radeon HD Graphics          | 1         | 4.17%   |
| AMD Athlon Neo Processor MV-40                | 1         | 4.17%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 1         | 4.17%   |
| AMD A4-9120e RADEON R3, 4 COMPUTE CORES 2C+2G | 1         | 4.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 4         | 16.67%  |
| Intel Atom              | 3         | 12.5%   |
| Intel Core i5           | 2         | 8.33%   |
| Intel Core i3           | 2         | 8.33%   |
| Intel Core 2 Duo        | 2         | 8.33%   |
| Other                   | 1         | 4.17%   |
| Intel Pentium M         | 1         | 4.17%   |
| Intel Pentium III       | 1         | 4.17%   |
| Intel Pentium Dual-Core | 1         | 4.17%   |
| Intel Core 2            | 1         | 4.17%   |
| AMD V120                | 1         | 4.17%   |
| AMD E                   | 1         | 4.17%   |
| AMD C-70                | 1         | 4.17%   |
| AMD Athlon Neo          | 1         | 4.17%   |
| AMD A8                  | 1         | 4.17%   |
| AMD A4                  | 1         | 4.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 12        | 50%     |
| 4      | 7         | 29.17%  |
| 1      | 5         | 20.83%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 24        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 18        | 75%     |
| 2      | 6         | 25%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 21        | 87.5%   |
| 32-bit         | 3         | 12.5%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3         | 12.5%   |
| 0x706a1    | 2         | 8.33%   |
| 0x6fd      | 2         | 8.33%   |
| 0x30678    | 2         | 8.33%   |
| 0x206a7    | 2         | 8.33%   |
| 0x806c1    | 1         | 4.17%   |
| 0x706a8    | 1         | 4.17%   |
| 0x6f6      | 1         | 4.17%   |
| 0x695      | 1         | 4.17%   |
| 0x68a      | 1         | 4.17%   |
| 0x40651    | 1         | 4.17%   |
| 0x20655    | 1         | 4.17%   |
| 0x1067a    | 1         | 4.17%   |
| 0x07030106 | 1         | 4.17%   |
| 0x06006705 | 1         | 4.17%   |
| 0x05000119 | 1         | 4.17%   |
| 0x0500010d | 1         | 4.17%   |
| 0x010000c8 | 1         | 4.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Silvermont    | 3         | 12.5%   |
| Goldmont plus | 3         | 12.5%   |
| Core          | 3         | 12.5%   |
| SandyBridge   | 2         | 8.33%   |
| P6            | 2         | 8.33%   |
| Bobcat        | 2         | 8.33%   |
| Westmere      | 1         | 4.17%   |
| TigerLake     | 1         | 4.17%   |
| Puma          | 1         | 4.17%   |
| Penryn        | 1         | 4.17%   |
| K8 Hammer     | 1         | 4.17%   |
| K10           | 1         | 4.17%   |
| Haswell       | 1         | 4.17%   |
| Excavator     | 1         | 4.17%   |
| Bonnell       | 1         | 4.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 14        | 56%     |
| AMD                              | 8         | 32%     |
| Silicon Integrated Systems [SiS] | 1         | 4%      |
| S3 Graphics                      | 1         | 4%      |
| Nvidia                           | 1         | 4%      |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 11.54%  |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 7.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 7.69%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 3.85%   |
| S3 Graphics 86C270-294 [SavageIX-MV]                                                     | 1         | 3.85%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                            | 1         | 3.85%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                      | 1         | 3.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 3.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 3.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 3.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 3.85%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 3.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 3.85%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1         | 3.85%   |
| AMD Wrestler [Radeon HD 7290]                                                            | 1         | 3.85%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 3.85%   |
| AMD Topaz PRO [Radeon R5 M255]                                                           | 1         | 3.85%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 3.85%   |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                             | 1         | 3.85%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 3.85%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                | 1         | 3.85%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 3.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 12        | 50%     |
| 1 x AMD         | 7         | 29.17%  |
| Other           | 1         | 4.17%   |
| 1 x SiS         | 1         | 4.17%   |
| 1 x S3 Graphics | 1         | 4.17%   |
| 1 x Nvidia      | 1         | 4.17%   |
| Intel + AMD     | 1         | 4.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 21        | 87.5%   |
| Unknown     | 2         | 8.33%   |
| Proprietary | 1         | 4.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 62.5%   |
| 0.01-0.5   | 8         | 33.33%  |
| 1.01-2.0   | 1         | 4.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 5         | 22.73%  |
| AU Optronics        | 5         | 22.73%  |
| Samsung Electronics | 4         | 18.18%  |
| LG Display          | 3         | 13.64%  |
| Hewlett-Packard     | 1         | 4.55%   |
| HannStar            | 1         | 4.55%   |
| Dell                | 1         | 4.55%   |
| CPT                 | 1         | 4.55%   |
| BOE                 | 1         | 4.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 2         | 9.09%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch    | 1         | 4.55%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch   | 1         | 4.55%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch   | 1         | 4.55%   |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 1020x570mm 46.0-inch | 1         | 4.55%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch            | 1         | 4.55%   |
| Hewlett-Packard Z24i HWP3100 1920x1200 518x324mm 24.1-inch             | 1         | 4.55%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch               | 1         | 4.55%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                       | 1         | 4.55%   |
| CPT LCD Monitor CPT13B1 1280x800 330x210mm 15.4-inch                   | 1         | 4.55%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch       | 1         | 4.55%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 1         | 4.55%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch        | 1         | 4.55%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch        | 1         | 4.55%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 1         | 4.55%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                   | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch         | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 256x144mm 11.6-inch         | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch          | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch          | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch          | 1         | 4.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 9         | 40.91%  |
| 1920x1080 (FHD)   | 6         | 27.27%  |
| 1600x900 (HD+)    | 3         | 13.64%  |
| 1280x800 (WXGA)   | 2         | 9.09%   |
| 2160x1440         | 1         | 4.55%   |
| 1920x1200 (WUXGA) | 1         | 4.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 10        | 45.45%  |
| 13     | 2         | 9.09%   |
| 11     | 2         | 9.09%   |
| 46     | 1         | 4.55%   |
| 40     | 1         | 4.55%   |
| 24     | 1         | 4.55%   |
| 23     | 1         | 4.55%   |
| 18     | 1         | 4.55%   |
| 17     | 1         | 4.55%   |
| 14     | 1         | 4.55%   |
| 12     | 1         | 4.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 12        | 54.55%  |
| 201-300     | 4         | 18.18%  |
| 501-600     | 2         | 9.09%   |
| 351-400     | 2         | 9.09%   |
| 801-900     | 1         | 4.55%   |
| 1001-1500   | 1         | 4.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 16        | 80%     |
| 16/10 | 3         | 15%     |
| 3/2   | 1         | 5%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 10        | 45.45%  |
| 81-90          | 3         | 13.64%  |
| 51-60          | 2         | 9.09%   |
| 501-1000       | 2         | 9.09%   |
| 61-70          | 1         | 4.55%   |
| 251-300        | 1         | 4.55%   |
| 201-250        | 1         | 4.55%   |
| 141-150        | 1         | 4.55%   |
| 121-130        | 1         | 4.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 10        | 45.45%  |
| 51-100  | 5         | 22.73%  |
| 121-160 | 4         | 18.18%  |
| 161-240 | 2         | 9.09%   |
| 1-50    | 1         | 4.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 21        | 87.5%   |
| 2     | 2         | 8.33%   |
| 0     | 1         | 4.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 17        | 41.46%  |
| Qualcomm Atheros                 | 9         | 21.95%  |
| Intel                            | 7         | 17.07%  |
| Broadcom                         | 2         | 4.88%   |
| Xiaomi                           | 1         | 2.44%   |
| Silicon Integrated Systems [SiS] | 1         | 2.44%   |
| Motorola PCS                     | 1         | 2.44%   |
| LG Electronics                   | 1         | 2.44%   |
| JMicron Technology               | 1         | 2.44%   |
| Accton Technology                | 1         | 2.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 6         | 13.95%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 5         | 11.63%  |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 6.98%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 4.65%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 4.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 2.33%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 2.33%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 2.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 2.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 2.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 2.33%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 1         | 2.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 2.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 2.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 2.33%   |
| Motorola PCS moto g(30)                                                 | 1         | 2.33%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                     | 1         | 2.33%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 2.33%   |
| Intel Wireless 3165                                                     | 1         | 2.33%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 2.33%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 2.33%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 2.33%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 1         | 2.33%   |
| Intel 82577LC Gigabit Network Connection                                | 1         | 2.33%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 1         | 2.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 2.33%   |
| Accton EN-1216 Ethernet Adapter                                         | 1         | 2.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 9         | 42.86%  |
| Intel                 | 6         | 28.57%  |
| Realtek Semiconductor | 5         | 23.81%  |
| Broadcom              | 1         | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 14.29%  |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 9.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 9.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 4.76%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 4.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 4.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 4.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 4.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 4.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 4.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 4.76%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 4.76%   |
| Intel Wireless 3165                                                     | 1         | 4.76%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 4.76%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 4.76%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 4.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 4.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 13        | 61.9%   |
| Xiaomi                           | 1         | 4.76%   |
| Silicon Integrated Systems [SiS] | 1         | 4.76%   |
| Motorola PCS                     | 1         | 4.76%   |
| LG Electronics                   | 1         | 4.76%   |
| JMicron Technology               | 1         | 4.76%   |
| Intel                            | 1         | 4.76%   |
| Broadcom                         | 1         | 4.76%   |
| Accton Technology                | 1         | 4.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 28.57%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 23.81%  |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 4.76%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 4.76%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 4.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 4.76%   |
| Motorola PCS moto g(30)                                           | 1         | 4.76%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)               | 1         | 4.76%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 4.76%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 4.76%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 4.76%   |
| Accton EN-1216 Ethernet Adapter                                   | 1         | 4.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 21        | 50%     |
| Ethernet | 20        | 47.62%  |
| Modem    | 1         | 2.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 19        | 54.29%  |
| Ethernet | 16        | 45.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 15        | 62.5%   |
| 1     | 7         | 29.17%  |
| 0     | 2         | 8.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 23        | 95.83%  |
| Yes  | 1         | 4.17%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros Communications | 4         | 36.36%  |
| Intel                           | 3         | 27.27%  |
| Realtek Semiconductor           | 2         | 18.18%  |
| Hewlett-Packard                 | 1         | 9.09%   |
| ASUSTek Computer                | 1         | 9.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR3011 Bluetooth              | 3         | 27.27%  |
| Realtek Bluetooth Radio                        | 2         | 18.18%  |
| Qualcomm Atheros  Bluetooth Device             | 1         | 9.09%   |
| Intel Bluetooth wireless interface             | 1         | 9.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 9.09%   |
| Intel AX200 Bluetooth                          | 1         | 9.09%   |
| HP Broadcom 2070 Bluetooth Combo               | 1         | 9.09%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter          | 1         | 9.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 14        | 60.87%  |
| AMD                              | 7         | 30.43%  |
| Silicon Integrated Systems [SiS] | 1         | 4.35%   |
| ESS Technology                   | 1         | 4.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 10%     |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 10%     |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 6.67%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 6.67%   |
| AMD FCH Azalia Controller                                                  | 2         | 6.67%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 3.33%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1         | 3.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 3.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 3.33%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 3.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 3.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 3.33%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 3.33%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 1         | 3.33%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 3.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 3.33%   |
| ESS Technology ES1988 Allegro-1                                            | 1         | 3.33%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 3.33%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 3.33%   |
| AMD RS690 HDMI Audio [Radeon Xpress 1200 Series]                           | 1         | 3.33%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 3.33%   |
| AMD High Definition Audio Controller                                       | 1         | 3.33%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 3.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 8         | 34.78%  |
| Samsung Electronics | 5         | 21.74%  |
| SK Hynix            | 4         | 17.39%  |
| Unknown (ABCD)      | 2         | 8.7%    |
| Kingston            | 2         | 8.7%    |
| Elpida              | 1         | 4.35%   |
| A-DATA Technology   | 1         | 4.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 3         | 12%     |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 2         | 8%      |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 2         | 8%      |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 4%      |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 4%      |
| Unknown RAM Module 256MB SODIMM SDRAM                            | 1         | 4%      |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 4%      |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 4%      |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                        | 1         | 4%      |
| SK Hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 1         | 4%      |
| SK Hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 800MT/s         | 1         | 4%      |
| SK Hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 4%      |
| SK Hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2400MT/s        | 1         | 4%      |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1334MT/s         | 1         | 4%      |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 4%      |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 4%      |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 1         | 4%      |
| Kingston RAM HP32D4S2S1ME-4 4GB SODIMM DDR4 3200MT/s             | 1         | 4%      |
| Kingston RAM 99U5428-041.A01G 4GB SODIMM DDR3 1067MT/s           | 1         | 4%      |
| Elpida RAM EBJ10UE8BDS0-AE-F 1GB SODIMM DDR3 1067MT/s            | 1         | 4%      |
| A-DATA RAM AM1U16BC2P1-B1AH 2GB SODIMM DDR3 4199MT/s             | 1         | 4%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 9         | 40.91%  |
| DDR2   | 4         | 18.18%  |
| SDRAM  | 3         | 13.64%  |
| DDR4   | 3         | 13.64%  |
| LPDDR4 | 2         | 9.09%   |
| DRAM   | 1         | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 21        | 95.45%  |
| DIMM   | 1         | 4.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 11        | 45.83%  |
| 2048 | 8         | 33.33%  |
| 1024 | 3         | 12.5%   |
| 512  | 1         | 4.17%   |
| 256  | 1         | 4.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 6         | 26.09%  |
| 2400    | 3         | 13.04%  |
| 1600    | 3         | 13.04%  |
| 1334    | 3         | 13.04%  |
| 1333    | 2         | 8.7%    |
| 1067    | 2         | 8.7%    |
| 4199    | 1         | 4.35%   |
| 3266    | 1         | 4.35%   |
| 3200    | 1         | 4.35%   |
| 800     | 1         | 4.35%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Microdia                               | 2         | 16.67%  |
| Chicony Electronics                    | 2         | 16.67%  |
| Acer                                   | 2         | 16.67%  |
| Suyin                                  | 1         | 8.33%   |
| Silicon Motion                         | 1         | 8.33%   |
| Realtek Semiconductor                  | 1         | 8.33%   |
| IMC Networks                           | 1         | 8.33%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 8.33%   |
| Alcor Micro                            | 1         | 8.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 8.33%   |
| Silicon Motion 300k Pixel Camera                            | 1         | 8.33%   |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 8.33%   |
| Microdia Webcam Vitade AF                                   | 1         | 8.33%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 8.33%   |
| IMC Networks HP TrueVision HD Camera                        | 1         | 8.33%   |
| Chicony Integrated Camera                                   | 1         | 8.33%   |
| Chicony HP HD Webcam                                        | 1         | 8.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 1         | 8.33%   |
| Alcor Micro USB 2.0 Web Camera                              | 1         | 8.33%   |
| Acer USB Camera                                             | 1         | 8.33%   |
| Acer EasyCamera                                             | 1         | 8.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 1         | 50%     |
| Validity Sensors VFS451 Fingerprint Reader | 1         | 50%     |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 20        | 83.33%  |
| 2     | 2         | 8.33%   |
| 1     | 2         | 8.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 2         | 33.33%  |
| Fingerprint reader       | 2         | 33.33%  |
| Flash memory             | 1         | 16.67%  |
| Communication controller | 1         | 16.67%  |

