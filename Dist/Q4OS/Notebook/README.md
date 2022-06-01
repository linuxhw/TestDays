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

Total: 32

| Vendor        | Model                   | Probe                                                      | Date         |
|---------------|-------------------------|------------------------------------------------------------|--------------|
| HP            | 250 G5 Notebook PC      | [0e5792fc9f](https://linux-hardware.org/?probe=0e5792fc9f) | May 15, 2022 |
| ASUSTek       | A6U                     | [4a8ad00e5e](https://linux-hardware.org/?probe=4a8ad00e5e) | May 12, 2022 |
| Toshiba       | Satellite Pro L500      | [5b72ea9a47](https://linux-hardware.org/?probe=5b72ea9a47) | May 02, 2022 |
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
| Medion        | Unknown                 | [6a06a14f6a](https://linux-hardware.org/?probe=6a06a14f6a) | May 07, 2020 |
| Philco        | 14I                     | [bf4c449b31](https://linux-hardware.org/?probe=bf4c449b31) | Apr 14, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Q4OS 4 | 14        | 51.85%  |
| Q4OS 3 | 10        | 37.04%  |
| Q4OS 2 | 3         | 11.11%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Q4OS | 27        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 4.19.0-17-amd64   | 4         | 14.81%  |
| 5.10.0-12-amd64   | 3         | 11.11%  |
| 5.10.0-8-amd64    | 2         | 7.41%   |
| 5.9.0-5-amd64     | 1         | 3.7%    |
| 5.6.0-1-amd64     | 1         | 3.7%    |
| 5.10.0-9-amd64    | 1         | 3.7%    |
| 5.10.0-8-686-pae  | 1         | 3.7%    |
| 5.10.0-14-686-pae | 1         | 3.7%    |
| 5.10.0-13-amd64   | 1         | 3.7%    |
| 5.10.0-12-686-pae | 1         | 3.7%    |
| 5.10.0-11-686-pae | 1         | 3.7%    |
| 5.10.0-10-686-pae | 1         | 3.7%    |
| 4.9.0-8-amd64     | 1         | 3.7%    |
| 4.9.0-14-686-pae  | 1         | 3.7%    |
| 4.9.0-12-686-pae  | 1         | 3.7%    |
| 4.19.0-20-amd64   | 1         | 3.7%    |
| 4.19.0-17-686     | 1         | 3.7%    |
| 4.19.0-14-amd64   | 1         | 3.7%    |
| 4.19.0-13-amd64   | 1         | 3.7%    |
| 4.19.0-12-amd64   | 1         | 3.7%    |
| 4.19.0-10-amd64   | 1         | 3.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 12        | 44.44%  |
| 4.19.0  | 10        | 37.04%  |
| 4.9.0   | 3         | 11.11%  |
| 5.9.0   | 1         | 3.7%    |
| 5.6.0   | 1         | 3.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 12        | 44.44%  |
| 4.19    | 10        | 37.04%  |
| 4.9     | 3         | 11.11%  |
| 5.9     | 1         | 3.7%    |
| 5.6     | 1         | 3.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 19        | 70.37%  |
| i686   | 8         | 29.63%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| KDE5    | 15        | 55.56%  |
| trinity | 11        | 40.74%  |
| KDE     | 1         | 3.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 26        | 96.3%   |
| Tty  | 1         | 3.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SDDM | 16        | 59.26%  |
| TDM  | 11        | 40.74%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 12        | 44.44%  |
| es_ES   | 2         | 7.41%   |
| en_GB   | 2         | 7.41%   |
| sv_SE   | 1         | 3.7%    |
| sl_SI   | 1         | 3.7%    |
| ru_RU   | 1         | 3.7%    |
| pl_PL   | 1         | 3.7%    |
| it_IT   | 1         | 3.7%    |
| fr_FR   | 1         | 3.7%    |
| es_VE   | 1         | 3.7%    |
| en_SG   | 1         | 3.7%    |
| de_DE   | 1         | 3.7%    |
| C       | 1         | 3.7%    |
| Unknown | 1         | 3.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 16        | 59.26%  |
| EFI  | 11        | 40.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 24        | 88.89%  |
| Overlay | 3         | 11.11%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 15        | 55.56%  |
| GPT     | 11        | 40.74%  |
| Unknown | 1         | 3.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 22        | 81.48%  |
| Yes       | 5         | 18.52%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 18        | 66.67%  |
| Yes       | 9         | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 7         | 25.93%  |
| ASUSTek Computer | 4         | 14.81%  |
| Toshiba          | 3         | 11.11%  |
| Lenovo           | 2         | 7.41%   |
| Visual Land      | 1         | 3.7%    |
| Qilive           | 1         | 3.7%    |
| Phoenix/SiS      | 1         | 3.7%    |
| Philco           | 1         | 3.7%    |
| Packard Bell     | 1         | 3.7%    |
| MSI              | 1         | 3.7%    |
| Medion           | 1         | 3.7%    |
| JVC              | 1         | 3.7%    |
| Chuwi            | 1         | 3.7%    |
| AMI              | 1         | 3.7%    |
| Acer             | 1         | 3.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Toshiba Satellite C660         | 2         | 7.41%   |
| Visual Land Premier 10         | 1         | 3.7%    |
| Toshiba Satellite Pro L500     | 1         | 3.7%    |
| Qilive QW19141AMSP             | 1         | 3.7%    |
| Phoenix/SiS M720SR             | 1         | 3.7%    |
| Philco 14I                     | 1         | 3.7%    |
| Packard Bell EasyNote LM81     | 1         | 3.7%    |
| MSI U210                       | 1         | 3.7%    |
| Lenovo ThinkPad 11e 20DAS0PS00 | 1         | 3.7%    |
| Lenovo IdeaPad 330-15IGM 81D1  | 1         | 3.7%    |
| JVC J3N                        | 1         | 3.7%    |
| HP ProBook 6550b               | 1         | 3.7%    |
| HP ProBook 450 G2              | 1         | 3.7%    |
| HP Presario CQ56               | 1         | 3.7%    |
| HP OmniBook PC                 | 1         | 3.7%    |
| HP Laptop 15s-fq2xxx           | 1         | 3.7%    |
| HP 250 G5 Notebook PC          | 1         | 3.7%    |
| HP 2000                        | 1         | 3.7%    |
| Chuwi GemiBook Pro             | 1         | 3.7%    |
| ASUS X540YA                    | 1         | 3.7%    |
| ASUS T12Eg                     | 1         | 3.7%    |
| ASUS A6U                       | 1         | 3.7%    |
| ASUS A6JC                      | 1         | 3.7%    |
| AMI Intel                      | 1         | 3.7%    |
| Acer AO751h                    | 1         | 3.7%    |
| Unknown                        | 1         | 3.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Toshiba Satellite     | 3         | 11.11%  |
| HP ProBook            | 2         | 7.41%   |
| Visual Land Premier   | 1         | 3.7%    |
| Qilive QW19141AMSP    | 1         | 3.7%    |
| Phoenix/SiS M720SR    | 1         | 3.7%    |
| Philco 14I            | 1         | 3.7%    |
| Packard Bell EasyNote | 1         | 3.7%    |
| MSI U210              | 1         | 3.7%    |
| Lenovo ThinkPad       | 1         | 3.7%    |
| Lenovo IdeaPad        | 1         | 3.7%    |
| JVC J3N               | 1         | 3.7%    |
| HP Presario           | 1         | 3.7%    |
| HP OmniBook           | 1         | 3.7%    |
| HP Laptop             | 1         | 3.7%    |
| HP 250                | 1         | 3.7%    |
| HP 2000               | 1         | 3.7%    |
| Chuwi GemiBook        | 1         | 3.7%    |
| ASUS X540YA           | 1         | 3.7%    |
| ASUS T12Eg            | 1         | 3.7%    |
| ASUS A6U              | 1         | 3.7%    |
| ASUS A6JC             | 1         | 3.7%    |
| AMI Intel             | 1         | 3.7%    |
| Acer AO751h           | 1         | 3.7%    |
| Unknown               | 1         | 3.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2010    | 5         | 18.52%  |
| 2020    | 3         | 11.11%  |
| 2009    | 3         | 11.11%  |
| 2016    | 2         | 7.41%   |
| 2014    | 2         | 7.41%   |
| Unknown | 2         | 7.41%   |
| 2019    | 1         | 3.7%    |
| 2018    | 1         | 3.7%    |
| 2017    | 1         | 3.7%    |
| 2015    | 1         | 3.7%    |
| 2012    | 1         | 3.7%    |
| 2011    | 1         | 3.7%    |
| 2007    | 1         | 3.7%    |
| 2006    | 1         | 3.7%    |
| 2005    | 1         | 3.7%    |
| 2004    | 1         | 3.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 27        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 25        | 92.59%  |
| Enabled  | 2         | 7.41%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 27        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 9         | 33.33%  |
| 4.01-8.0   | 5         | 18.52%  |
| 1.01-2.0   | 5         | 18.52%  |
| 2.01-3.0   | 3         | 11.11%  |
| 0.51-1.0   | 3         | 11.11%  |
| 16.01-24.0 | 1         | 3.7%    |
| 0.01-0.5   | 1         | 3.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 13        | 48.15%  |
| 0.51-1.0 | 7         | 25.93%  |
| 2.01-3.0 | 4         | 14.81%  |
| 0.01-0.5 | 2         | 7.41%   |
| 3.01-4.0 | 1         | 3.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 21        | 77.78%  |
| 2      | 5         | 18.52%  |
| 3      | 1         | 3.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 55.56%  |
| No        | 12        | 44.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 85.19%  |
| No        | 4         | 14.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 88.89%  |
| No        | 3         | 11.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 14        | 51.85%  |
| Yes       | 13        | 48.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 3         | 11.11%  |
| Kenya        | 3         | 11.11%  |
| UK           | 2         | 7.41%   |
| Spain        | 2         | 7.41%   |
| Romania      | 2         | 7.41%   |
| Poland       | 2         | 7.41%   |
| Italy        | 2         | 7.41%   |
| Venezuela    | 1         | 3.7%    |
| Sweden       | 1         | 3.7%    |
| Slovenia     | 1         | 3.7%    |
| Singapore    | 1         | 3.7%    |
| Saudi Arabia | 1         | 3.7%    |
| Russia       | 1         | 3.7%    |
| Qatar        | 1         | 3.7%    |
| Germany      | 1         | 3.7%    |
| France       | 1         | 3.7%    |
| Brazil       | 1         | 3.7%    |
| Belarus      | 1         | 3.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Nairobi               | 3         | 11.11%  |
| Swindon               | 2         | 7.41%   |
| Drobeta-Turnu Severin | 2         | 7.41%   |
| Tranas                | 1         | 3.7%    |
| Tellico Plains        | 1         | 3.7%    |
| Sosnowiec             | 1         | 3.7%    |
| Singapore             | 1         | 3.7%    |
| Salsomaggiore Terme   | 1         | 3.7%    |
| Rostock               | 1         | 3.7%    |
| Puerto Cumarebo       | 1         | 3.7%    |
| Moscow                | 1         | 3.7%    |
| Moirans               | 1         | 3.7%    |
| Mogilev               | 1         | 3.7%    |
| Mesa                  | 1         | 3.7%    |
| Londrina              | 1         | 3.7%    |
| Ljubljana             | 1         | 3.7%    |
| Las Vegas             | 1         | 3.7%    |
| Klaudyn               | 1         | 3.7%    |
| Gijón                | 1         | 3.7%    |
| Doha                  | 1         | 3.7%    |
| Dammam                | 1         | 3.7%    |
| Calvecchia            | 1         | 3.7%    |
| Barcelona             | 1         | 3.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 13.79%  |
| Unknown             | 4         | 4      | 13.79%  |
| Samsung Electronics | 3         | 3      | 10.34%  |
| Hitachi             | 3         | 3      | 10.34%  |
| Seagate             | 2         | 2      | 6.9%    |
| SanDisk             | 2         | 2      | 6.9%    |
| KESU                | 2         | 2      | 6.9%    |
| HGST                | 2         | 2      | 6.9%    |
| China               | 2         | 2      | 6.9%    |
| Toshiba             | 1         | 1      | 3.45%   |
| Kingston            | 1         | 1      | 3.45%   |
| Fujitsu             | 1         | 1      | 3.45%   |
| A-DATA Technology   | 1         | 1      | 3.45%   |
| Unknown             | 1         | 1      | 3.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB            | 2         | 6.9%    |
| KESU USB 3.1 128GB                   | 2         | 6.9%    |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 3.45%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 3.45%   |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 3.45%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 3.45%   |
| Unknown USDU1  32GB                  | 1         | 3.45%   |
| Unknown SLD64G  64GB                 | 1         | 3.45%   |
| Unknown SD/MMC/MS PRO 999GB          | 1         | 3.45%   |
| Unknown 064G38  64GB                 | 1         | 3.45%   |
| Toshiba MK8025GAS 80GB               | 1         | 3.45%   |
| Seagate ST9120822AS 120GB            | 1         | 3.45%   |
| Seagate Backup+ SL 1TB               | 1         | 3.45%   |
| SanDisk SDCFX-032G SSD               | 1         | 3.45%   |
| SanDisk SD8SN8U1T001122 1024GB SSD   | 1         | 3.45%   |
| Samsung AWMB3R  16GB                 | 1         | 3.45%   |
| Kingston SV300S37A60G 64GB SSD       | 1         | 3.45%   |
| Hitachi HTS545032B9A300 320GB        | 1         | 3.45%   |
| Hitachi HTS543225L9SA00 250GB        | 1         | 3.45%   |
| Hitachi DK23CA-20 20GB               | 1         | 3.45%   |
| HGST HTS725050A7E630 500GB           | 1         | 3.45%   |
| HGST HTS541075A9E680 752GB           | 1         | 3.45%   |
| Fujitsu MHY2080BH 80GB               | 1         | 3.45%   |
| China SSD128GBS800                   | 1         | 3.45%   |
| China SATA SSD 240GB                 | 1         | 3.45%   |
| A-DATA SU630 240GB SSD               | 1         | 3.45%   |
| Unknown                              | 1         | 3.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 25%     |
| Hitachi | 3         | 3      | 25%     |
| HGST    | 2         | 2      | 16.67%  |
| Unknown | 1         | 1      | 8.33%   |
| Toshiba | 1         | 1      | 8.33%   |
| Seagate | 1         | 1      | 8.33%   |
| Fujitsu | 1         | 1      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 2         | 2      | 22.22%  |
| Samsung Electronics | 2         | 2      | 22.22%  |
| China               | 2         | 2      | 22.22%  |
| Kingston            | 1         | 1      | 11.11%  |
| A-DATA Technology   | 1         | 1      | 11.11%  |
| Unknown             | 1         | 1      | 11.11%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 11        | 12     | 39.29%  |
| SSD     | 9         | 9      | 32.14%  |
| MMC     | 4         | 4      | 14.29%  |
| Unknown | 3         | 3      | 10.71%  |
| NVMe    | 1         | 1      | 3.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 20        | 20     | 68.97%  |
| SAS  | 4         | 4      | 13.79%  |
| MMC  | 4         | 4      | 13.79%  |
| NVMe | 1         | 1      | 3.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 18        | 18     | 85.71%  |
| 0.51-1.0   | 2         | 2      | 9.52%   |
| 1.01-2.0   | 1         | 1      | 4.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 51-100     | 6         | 22.22%  |
| 101-250    | 5         | 18.52%  |
| 1-20       | 5         | 18.52%  |
| 21-50      | 4         | 14.81%  |
| 251-500    | 3         | 11.11%  |
| 501-1000   | 2         | 7.41%   |
| 1001-2000  | 1         | 3.7%    |
| Unknown    | 1         | 3.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 19        | 70.37%  |
| 21-50    | 4         | 14.81%  |
| 251-500  | 2         | 7.41%   |
| 501-1000 | 1         | 3.7%    |
| Unknown  | 1         | 3.7%    |

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
| Works    | 12        | 12     | 42.86%  |
| Detected | 8         | 9      | 28.57%  |
| Malfunc  | 8         | 8      | 28.57%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 17        | 65.38%  |
| AMD                              | 6         | 23.08%  |
| Silicon Integrated Systems [SiS] | 2         | 7.69%   |
| Sandisk                          | 1         | 3.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 10.34%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 10.34%  |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 2         | 6.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 6.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 6.9%    |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 3.45%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1         | 3.45%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 3.45%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 1         | 3.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 3.45%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 3.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 3.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 3.45%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 3.45%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 1         | 3.45%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 1         | 3.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 3.45%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 3.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 3.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 3.45%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 3.45%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 3.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 17        | 62.96%  |
| IDE  | 8         | 29.63%  |
| RAID | 1         | 3.7%    |
| NVMe | 1         | 3.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 20        | 74.07%  |
| AMD    | 7         | 25.93%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 7.41%   |
| Intel Pentium M processor 1000MHz             | 1         | 3.7%    |
| Intel Pentium III (Coppermine)                | 1         | 3.7%    |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 3.7%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 3.7%    |
| Intel Core i5 CPU M 450 @ 2.40GHz             | 1         | 3.7%    |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 1         | 3.7%    |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz          | 1         | 3.7%    |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz          | 1         | 3.7%    |
| Intel Core 2 CPU T5500 @ 1.66GHz              | 1         | 3.7%    |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 3.7%    |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 3.7%    |
| Intel Celeron J4115 CPU @ 1.80GHz             | 1         | 3.7%    |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 3.7%    |
| Intel Celeron CPU N2940 @ 1.83GHz             | 1         | 3.7%    |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 1         | 3.7%    |
| Intel Atom CPU Z520 @ 1.33GHz                 | 1         | 3.7%    |
| Intel Atom CPU Z3735G @ 1.33GHz               | 1         | 3.7%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 3.7%    |
| AMD V120 Processor                            | 1         | 3.7%    |
| AMD Mobile Sempron Processor 3000+            | 1         | 3.7%    |
| AMD E-300 APU with Radeon HD Graphics         | 1         | 3.7%    |
| AMD C-70 APU with Radeon HD Graphics          | 1         | 3.7%    |
| AMD Athlon Neo Processor MV-40                | 1         | 3.7%    |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 1         | 3.7%    |
| AMD A4-9120e RADEON R3, 4 COMPUTE CORES 2C+2G | 1         | 3.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 5         | 18.52%  |
| Intel Core 2 Duo        | 3         | 11.11%  |
| Intel Atom              | 3         | 11.11%  |
| Intel Core i5           | 2         | 7.41%   |
| Intel Core i3           | 2         | 7.41%   |
| Other                   | 1         | 3.7%    |
| Intel Pentium M         | 1         | 3.7%    |
| Intel Pentium III       | 1         | 3.7%    |
| Intel Pentium Dual-Core | 1         | 3.7%    |
| Intel Core 2            | 1         | 3.7%    |
| AMD V120                | 1         | 3.7%    |
| AMD Mobile Sempron      | 1         | 3.7%    |
| AMD E                   | 1         | 3.7%    |
| AMD C-70                | 1         | 3.7%    |
| AMD Athlon Neo          | 1         | 3.7%    |
| AMD A8                  | 1         | 3.7%    |
| AMD A4                  | 1         | 3.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 14        | 51.85%  |
| 4      | 7         | 25.93%  |
| 1      | 6         | 22.22%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 27        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 21        | 77.78%  |
| 2      | 6         | 22.22%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 23        | 85.19%  |
| 32-bit         | 4         | 14.81%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4         | 14.81%  |
| 0x706a1    | 2         | 7.41%   |
| 0x6fd      | 2         | 7.41%   |
| 0x30678    | 2         | 7.41%   |
| 0x206a7    | 2         | 7.41%   |
| 0x1067a    | 2         | 7.41%   |
| 0x806c1    | 1         | 3.7%    |
| 0x706a8    | 1         | 3.7%    |
| 0x6f6      | 1         | 3.7%    |
| 0x695      | 1         | 3.7%    |
| 0x68a      | 1         | 3.7%    |
| 0x406c4    | 1         | 3.7%    |
| 0x40651    | 1         | 3.7%    |
| 0x20655    | 1         | 3.7%    |
| 0x07030106 | 1         | 3.7%    |
| 0x06006705 | 1         | 3.7%    |
| 0x05000119 | 1         | 3.7%    |
| 0x0500010d | 1         | 3.7%    |
| 0x010000c8 | 1         | 3.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Silvermont    | 4         | 14.81%  |
| Goldmont plus | 3         | 11.11%  |
| Core          | 3         | 11.11%  |
| SandyBridge   | 2         | 7.41%   |
| Penryn        | 2         | 7.41%   |
| P6            | 2         | 7.41%   |
| K8 Hammer     | 2         | 7.41%   |
| Bobcat        | 2         | 7.41%   |
| Westmere      | 1         | 3.7%    |
| TigerLake     | 1         | 3.7%    |
| Puma          | 1         | 3.7%    |
| K10           | 1         | 3.7%    |
| Haswell       | 1         | 3.7%    |
| Excavator     | 1         | 3.7%    |
| Bonnell       | 1         | 3.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 15        | 53.57%  |
| AMD                              | 9         | 32.14%  |
| Silicon Integrated Systems [SiS] | 2         | 7.14%   |
| S3 Graphics                      | 1         | 3.57%   |
| Nvidia                           | 1         | 3.57%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Notebooks | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel GeminiLake [UHD Graphics 600]                                                        | 3         | 10.34%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 2         | 6.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 2         | 6.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 2         | 6.9%    |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 1         | 3.45%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 1         | 3.45%   |
| S3 Graphics 86C270-294 [SavageIX-MV]                                                       | 1         | 3.45%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                              | 1         | 3.45%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 1         | 3.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 1         | 3.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 1         | 3.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 1         | 3.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 1         | 3.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 1         | 3.45%   |
| Intel 82852/855GM Integrated Graphics Device                                               | 1         | 3.45%   |
| AMD Wrestler [Radeon HD 7290]                                                              | 1         | 3.45%   |
| AMD Wrestler [Radeon HD 6310]                                                              | 1         | 3.45%   |
| AMD Topaz PRO [Radeon R5 M255]                                                             | 1         | 3.45%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 1         | 3.45%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                          | 1         | 3.45%   |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                               | 1         | 3.45%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                  | 1         | 3.45%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                  | 1         | 3.45%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                        | 1         | 3.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 13        | 48.15%  |
| 1 x AMD         | 8         | 29.63%  |
| 1 x SiS         | 2         | 7.41%   |
| Other           | 1         | 3.7%    |
| 1 x S3 Graphics | 1         | 3.7%    |
| 1 x Nvidia      | 1         | 3.7%    |
| Intel + AMD     | 1         | 3.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 23        | 85.19%  |
| Unknown     | 3         | 11.11%  |
| Proprietary | 1         | 3.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 62.96%  |
| 0.01-0.5   | 9         | 33.33%  |
| 1.01-2.0   | 1         | 3.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 6         | 25%     |
| AU Optronics        | 6         | 25%     |
| Samsung Electronics | 4         | 16.67%  |
| LG Display          | 3         | 12.5%   |
| Hewlett-Packard     | 1         | 4.17%   |
| HannStar            | 1         | 4.17%   |
| Dell                | 1         | 4.17%   |
| CPT                 | 1         | 4.17%   |
| BOE                 | 1         | 4.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 2         | 8.33%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch    | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch   | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch   | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 1020x570mm 46.0-inch | 1         | 4.17%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch            | 1         | 4.17%   |
| Hewlett-Packard Z24i HWP3100 1920x1200 518x324mm 24.1-inch             | 1         | 4.17%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch               | 1         | 4.17%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                       | 1         | 4.17%   |
| CPT LCD Monitor CPT13B1 1280x800 330x210mm 15.4-inch                   | 1         | 4.17%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch       | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch        | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch        | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch        | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 1         | 4.17%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                   | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch         | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 256x144mm 11.6-inch         | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch          | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch          | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch          | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO12EC 1366x768 344x193mm 15.5-inch          | 1         | 4.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 11        | 45.83%  |
| 1920x1080 (FHD)   | 6         | 25%     |
| 1600x900 (HD+)    | 3         | 12.5%   |
| 1280x800 (WXGA)   | 2         | 8.33%   |
| 2160x1440         | 1         | 4.17%   |
| 1920x1200 (WUXGA) | 1         | 4.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 12        | 50%     |
| 13     | 2         | 8.33%   |
| 11     | 2         | 8.33%   |
| 46     | 1         | 4.17%   |
| 40     | 1         | 4.17%   |
| 24     | 1         | 4.17%   |
| 23     | 1         | 4.17%   |
| 18     | 1         | 4.17%   |
| 17     | 1         | 4.17%   |
| 14     | 1         | 4.17%   |
| 12     | 1         | 4.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 14        | 58.33%  |
| 201-300     | 4         | 16.67%  |
| 501-600     | 2         | 8.33%   |
| 351-400     | 2         | 8.33%   |
| 801-900     | 1         | 4.17%   |
| 1001-1500   | 1         | 4.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 18        | 81.82%  |
| 16/10 | 3         | 13.64%  |
| 3/2   | 1         | 4.55%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 50%     |
| 81-90          | 3         | 12.5%   |
| 51-60          | 2         | 8.33%   |
| 501-1000       | 2         | 8.33%   |
| 61-70          | 1         | 4.17%   |
| 251-300        | 1         | 4.17%   |
| 201-250        | 1         | 4.17%   |
| 141-150        | 1         | 4.17%   |
| 121-130        | 1         | 4.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 12        | 50%     |
| 51-100  | 5         | 20.83%  |
| 121-160 | 4         | 16.67%  |
| 161-240 | 2         | 8.33%   |
| 1-50    | 1         | 4.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 23        | 85.19%  |
| 2     | 2         | 7.41%   |
| 0     | 2         | 7.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 20        | 42.55%  |
| Qualcomm Atheros                 | 10        | 21.28%  |
| Intel                            | 7         | 14.89%  |
| Silicon Integrated Systems [SiS] | 2         | 4.26%   |
| Broadcom                         | 2         | 4.26%   |
| Xiaomi                           | 1         | 2.13%   |
| Motorola PCS                     | 1         | 2.13%   |
| LG Electronics                   | 1         | 2.13%   |
| JMicron Technology               | 1         | 2.13%   |
| Broadcom Limited                 | 1         | 2.13%   |
| Accton Technology                | 1         | 2.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 7         | 14%     |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 6         | 12%     |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 3         | 6%      |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 3         | 6%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 2         | 4%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                       | 2         | 4%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 2         | 4%      |
| Xiaomi Mi/Redmi series (RNDIS)                                              | 1         | 2%      |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                     | 1         | 2%      |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter               | 1         | 2%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 2%      |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                  | 1         | 2%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 2%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 2%      |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                  | 1         | 2%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 2%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1         | 2%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1         | 2%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 2%      |
| Motorola PCS moto g(6) play                                                 | 1         | 2%      |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                         | 1         | 2%      |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                      | 1         | 2%      |
| Intel Wireless 3165                                                         | 1         | 2%      |
| Intel Wi-Fi 6 AX200                                                         | 1         | 2%      |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                    | 1         | 2%      |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 2%      |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller           | 1         | 2%      |
| Intel 82577LC Gigabit Network Connection                                    | 1         | 2%      |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                             | 1         | 2%      |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1         | 2%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 2%      |
| Accton EN-1216 Ethernet Adapter                                             | 1         | 2%      |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 10        | 41.67%  |
| Realtek Semiconductor | 6         | 25%     |
| Intel                 | 6         | 25%     |
| Broadcom Limited      | 1         | 4.17%   |
| Broadcom              | 1         | 4.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 3         | 12.5%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 3         | 12.5%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 2         | 8.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 2         | 8.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 4.17%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                  | 1         | 4.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 4.17%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 4.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 4.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1         | 4.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1         | 4.17%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 4.17%   |
| Intel Wireless 3165                                                         | 1         | 4.17%   |
| Intel Wi-Fi 6 AX200                                                         | 1         | 4.17%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                    | 1         | 4.17%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 4.17%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1         | 4.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 4.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 16        | 66.67%  |
| Xiaomi                           | 1         | 4.17%   |
| Silicon Integrated Systems [SiS] | 1         | 4.17%   |
| Motorola PCS                     | 1         | 4.17%   |
| LG Electronics                   | 1         | 4.17%   |
| JMicron Technology               | 1         | 4.17%   |
| Intel                            | 1         | 4.17%   |
| Broadcom                         | 1         | 4.17%   |
| Accton Technology                | 1         | 4.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 29.17%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 25%     |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 8.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 4.17%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 4.17%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 4.17%   |
| Motorola PCS moto g(6) play                                       | 1         | 4.17%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)               | 1         | 4.17%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 4.17%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 4.17%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 4.17%   |
| Accton EN-1216 Ethernet Adapter                                   | 1         | 4.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 24        | 48.98%  |
| Ethernet | 23        | 46.94%  |
| Modem    | 2         | 4.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 16        | 59.26%  |
| Ethernet | 11        | 40.74%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 18        | 66.67%  |
| 1     | 7         | 25.93%  |
| 0     | 2         | 7.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 26        | 96.3%   |
| Yes  | 1         | 3.7%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros Communications | 4         | 30.77%  |
| Realtek Semiconductor           | 3         | 23.08%  |
| Intel                           | 3         | 23.08%  |
| Toshiba                         | 1         | 7.69%   |
| Hewlett-Packard                 | 1         | 7.69%   |
| ASUSTek Computer                | 1         | 7.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                        | 3         | 23.08%  |
| Qualcomm Atheros AR3011 Bluetooth              | 3         | 23.08%  |
| Toshiba Askey for                              | 1         | 7.69%   |
| Qualcomm Atheros  Bluetooth Device             | 1         | 7.69%   |
| Intel Bluetooth wireless interface             | 1         | 7.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 7.69%   |
| Intel AX200 Bluetooth                          | 1         | 7.69%   |
| HP Broadcom 2070 Bluetooth Combo               | 1         | 7.69%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter          | 1         | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 16        | 59.26%  |
| AMD                              | 8         | 29.63%  |
| Silicon Integrated Systems [SiS] | 2         | 7.41%   |
| ESS Technology                   | 1         | 3.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 8.82%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 8.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 5.88%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 5.88%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 5.88%   |
| AMD FCH Azalia Controller                                                                         | 2         | 5.88%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 1         | 2.94%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 2.94%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 2.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 2.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 2.94%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 2.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 2.94%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2.94%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 2.94%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 2.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 2.94%   |
| ESS Technology ES1988 Allegro-1                                                                   | 1         | 2.94%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 2.94%   |
| AMD RS690 HDMI Audio [Radeon Xpress 1200 Series]                                                  | 1         | 2.94%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 2.94%   |
| AMD High Definition Audio Controller                                                              | 1         | 2.94%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 2.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 9         | 34.62%  |
| Samsung Electronics | 6         | 23.08%  |
| SK Hynix            | 4         | 15.38%  |
| Unknown (ABCD)      | 2         | 7.69%   |
| Kingston            | 2         | 7.69%   |
| Toshiba             | 1         | 3.85%   |
| Elpida              | 1         | 3.85%   |
| A-DATA Technology   | 1         | 3.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                             | 3         | 10.34%  |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s | 2         | 6.9%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 2         | 6.9%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 6.9%    |
| Unknown RAM Module 512MB SODIMM SDRAM                          | 1         | 3.45%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                 | 1         | 3.45%   |
| Unknown RAM Module 256MB SODIMM SDRAM                          | 1         | 3.45%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 1         | 3.45%   |
| Unknown RAM Module 1GB SODIMM DRAM                             | 1         | 3.45%   |
| Unknown RAM Module 1GB SODIMM DDR 266MT/s                      | 1         | 3.45%   |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                      | 1         | 3.45%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s             | 1         | 3.45%   |
| Toshiba RAM 64T128020EDL2.5C2 4GB SODIMM 1066MT/s              | 1         | 3.45%   |
| SK Hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                | 1         | 3.45%   |
| SK Hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 800MT/s       | 1         | 3.45%   |
| SK Hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 3.45%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2400MT/s      | 1         | 3.45%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s          | 1         | 3.45%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 3.45%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 1         | 3.45%   |
| Kingston RAM HP32D4S2S1ME-4 4GB SODIMM DDR4 3200MT/s           | 1         | 3.45%   |
| Kingston RAM 99U5428-041.A01G 4GB SODIMM DDR3 1067MT/s         | 1         | 3.45%   |
| Elpida RAM EBJ10UE8BDS0-AE-F 1GB SODIMM DDR3 1067MT/s          | 1         | 3.45%   |
| A-DATA RAM AM1U16BC2P1-B1AH 2GB SODIMM DDR3 4199MT/s           | 1         | 3.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 10        | 40%     |
| DDR2   | 5         | 20%     |
| SDRAM  | 3         | 12%     |
| DDR4   | 3         | 12%     |
| LPDDR4 | 2         | 8%      |
| DRAM   | 1         | 4%      |
| DDR    | 1         | 4%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 24        | 96%     |
| DIMM   | 1         | 4%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 13        | 48.15%  |
| 2048 | 8         | 29.63%  |
| 1024 | 4         | 14.81%  |
| 512  | 1         | 3.7%    |
| 256  | 1         | 3.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 6         | 23.08%  |
| 1600    | 4         | 15.38%  |
| 2400    | 3         | 11.54%  |
| 1334    | 3         | 11.54%  |
| 1333    | 2         | 7.69%   |
| 1067    | 2         | 7.69%   |
| 4199    | 1         | 3.85%   |
| 3266    | 1         | 3.85%   |
| 3200    | 1         | 3.85%   |
| 1066    | 1         | 3.85%   |
| 800     | 1         | 3.85%   |
| 266     | 1         | 3.85%   |

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
| Chicony Electronics                    | 4         | 26.67%  |
| Microdia                               | 2         | 13.33%  |
| Acer                                   | 2         | 13.33%  |
| Suyin                                  | 1         | 6.67%   |
| Silicon Motion                         | 1         | 6.67%   |
| Realtek Semiconductor                  | 1         | 6.67%   |
| IMC Networks                           | 1         | 6.67%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 6.67%   |
| ALi                                    | 1         | 6.67%   |
| Alcor Micro                            | 1         | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 6.67%   |
| Silicon Motion 300k Pixel Camera                            | 1         | 6.67%   |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 6.67%   |
| Microdia Webcam Vitade AF                                   | 1         | 6.67%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 6.67%   |
| IMC Networks HP TrueVision HD Camera                        | 1         | 6.67%   |
| Chicony USB2.0 UVC WebCam                                   | 1         | 6.67%   |
| Chicony Integrated Camera                                   | 1         | 6.67%   |
| Chicony HP Webcam                                           | 1         | 6.67%   |
| Chicony HP HD Webcam                                        | 1         | 6.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 1         | 6.67%   |
| ALi M5603 Video Camera Controller                           | 1         | 6.67%   |
| Alcor Micro SHUNCCM2MP                                      | 1         | 6.67%   |
| Acer USB Camera                                             | 1         | 6.67%   |
| Acer EasyCamera                                             | 1         | 6.67%   |

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
| 0     | 22        | 81.48%  |
| 2     | 3         | 11.11%  |
| 1     | 2         | 7.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 3         | 37.5%   |
| Fingerprint reader       | 2         | 25%     |
| Flash memory             | 1         | 12.5%   |
| Communication controller | 1         | 12.5%   |
| Camera                   | 1         | 12.5%   |

