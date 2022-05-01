Q4OS - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for Q4OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Q4OS/Desktop/README.md) and [notebooks](/Dist/Q4OS/Notebook/README.md).

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

Total: 39

| Vendor        | Model                   | Form-Factor | Probe                                                      | Date         |
|---------------|-------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 330-15IGM 81D1  | Notebook    | [8cdcd8d130](https://linux-hardware.org/?probe=8cdcd8d130) | Apr 08, 2022 |
| Acer          | AO751h                  | Notebook    | [23737182d1](https://linux-hardware.org/?probe=23737182d1) | Mar 21, 2022 |
| AMI           | Intel                   | Notebook    | [6d581b03a6](https://linux-hardware.org/?probe=6d581b03a6) | Mar 19, 2022 |
| ASUSTek       | X540YA                  | Notebook    | [0cd3840828](https://linux-hardware.org/?probe=0cd3840828) | Mar 14, 2022 |
| Visual Lan... | Premier 10              | Notebook    | [64450e11a3](https://linux-hardware.org/?probe=64450e11a3) | Feb 04, 2022 |
| HP            | Presario CQ56           | Notebook    | [8d03d80424](https://linux-hardware.org/?probe=8d03d80424) | Jan 14, 2022 |
| HP            | Presario CQ56           | Notebook    | [a0bc0364a8](https://linux-hardware.org/?probe=a0bc0364a8) | Jan 08, 2022 |
| Compaq        | 07E4h                   | Desktop     | [535804dbc6](https://linux-hardware.org/?probe=535804dbc6) | Jan 05, 2022 |
| MSI           | U210                    | Notebook    | [24eb05a4d9](https://linux-hardware.org/?probe=24eb05a4d9) | Dec 29, 2021 |
| Toshiba       | Satellite C660          | Notebook    | [b159811d48](https://linux-hardware.org/?probe=b159811d48) | Dec 12, 2021 |
| Toshiba       | Satellite C660          | Notebook    | [2197770fd0](https://linux-hardware.org/?probe=2197770fd0) | Dec 12, 2021 |
| ASUSTek       | T12Eg                   | Notebook    | [115e8b584f](https://linux-hardware.org/?probe=115e8b584f) | Dec 11, 2021 |
| Toshiba       | Satellite C660          | Notebook    | [64521297e2](https://linux-hardware.org/?probe=64521297e2) | Dec 07, 2021 |
| Toshiba       | Satellite C660          | Notebook    | [b6a5bb8982](https://linux-hardware.org/?probe=b6a5bb8982) | Dec 06, 2021 |
| Gigabyte      | XP-M5S661GX             | Desktop     | [c452e6bdf7](https://linux-hardware.org/?probe=c452e6bdf7) | Nov 27, 2021 |
| Phoenix/Si... | M720SR                  | Notebook    | [f92c7e8c3e](https://linux-hardware.org/?probe=f92c7e8c3e) | Oct 09, 2021 |
| HP            | Laptop 15s-fq2xxx       | Notebook    | [cfa6202518](https://linux-hardware.org/?probe=cfa6202518) | Sep 14, 2021 |
| HP            | Laptop 15s-fq2xxx       | Notebook    | [726c3230ef](https://linux-hardware.org/?probe=726c3230ef) | Sep 14, 2021 |
| Chuwi         | GemiBook Pro            | Notebook    | [ebe8d67a10](https://linux-hardware.org/?probe=ebe8d67a10) | Sep 04, 2021 |
| TECO Elect... | TR53A0                  | Desktop     | [4ab721c7f7](https://linux-hardware.org/?probe=4ab721c7f7) | Aug 19, 2021 |
| HP            | ProBook 450 G2          | Notebook    | [dbba9b9771](https://linux-hardware.org/?probe=dbba9b9771) | Jul 30, 2021 |
| JVC           | J3N                     | Notebook    | [f8da57e850](https://linux-hardware.org/?probe=f8da57e850) | Jul 09, 2021 |
| MSI           | B550-A PRO              | Desktop     | [546cf15192](https://linux-hardware.org/?probe=546cf15192) | Jun 16, 2021 |
| MSI           | GF615M-P33 V2           | Desktop     | [6f22f99f9f](https://linux-hardware.org/?probe=6f22f99f9f) | May 14, 2021 |
| HP            | ProBook 6550b           | Notebook    | [b192718656](https://linux-hardware.org/?probe=b192718656) | Mar 13, 2021 |
| HP            | 2000                    | Notebook    | [736561e497](https://linux-hardware.org/?probe=736561e497) | Mar 07, 2021 |
| ASRock        | G41M-VS3                | Desktop     | [75cb33cf5e](https://linux-hardware.org/?probe=75cb33cf5e) | Feb 25, 2021 |
| ASRock        | G41M-VS3                | Desktop     | [6a77858cd4](https://linux-hardware.org/?probe=6a77858cd4) | Feb 25, 2021 |
| ASUSTek       | A6JC                    | Notebook    | [b04f51dd1c](https://linux-hardware.org/?probe=b04f51dd1c) | Jan 29, 2021 |
| ASUSTek       | A6JC                    | Notebook    | [097dd7f151](https://linux-hardware.org/?probe=097dd7f151) | Jan 29, 2021 |
| Lenovo        | ThinkPad 11e 20DAS0PS00 | Notebook    | [2d618b7420](https://linux-hardware.org/?probe=2d618b7420) | Dec 14, 2020 |
| Packard Be... | EasyNote LM81           | Notebook    | [d6b0c23c18](https://linux-hardware.org/?probe=d6b0c23c18) | Nov 23, 2020 |
| Qilive        | QW19141AMSP             | Notebook    | [b8f3486ae1](https://linux-hardware.org/?probe=b8f3486ae1) | Aug 27, 2020 |
| HP            | OmniBook PC             | Notebook    | [5e33febbc1](https://linux-hardware.org/?probe=5e33febbc1) | Jul 10, 2020 |
| Unknown       | MEDION                  | Notebook    | [6a06a14f6a](https://linux-hardware.org/?probe=6a06a14f6a) | May 07, 2020 |
| TrekStor      | SurfTab wintron 7.0     | Tablet      | [464706154e](https://linux-hardware.org/?probe=464706154e) | Jun 26, 2019 |
| TrekStor      | SurfTab wintron 7.0     | Tablet      | [db63ea2d00](https://linux-hardware.org/?probe=db63ea2d00) | Jun 19, 2019 |
| TrekStor      | SurfTab wintron 7.0     | Tablet      | [9e530b2e21](https://linux-hardware.org/?probe=9e530b2e21) | Jun 18, 2019 |
| Philco        | 14I                     | Notebook    | [bf4c449b31](https://linux-hardware.org/?probe=bf4c449b31) | Apr 14, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Q4OS 4      | 10        | 31.25%  |
| Q4OS 3.14.2 | 4         | 12.5%   |
| Q4OS 3      | 3         | 9.38%   |
| Q4OS 4.5.3  | 2         | 6.25%   |
| Q4OS 3.15.1 | 2         | 6.25%   |
| Q4OS 3.12.1 | 2         | 6.25%   |
| Q4OS 2.7.3  | 2         | 6.25%   |
| Q4OS 2.7.2  | 2         | 6.25%   |
| Q4OS 4.3.2  | 1         | 3.13%   |
| Q4OS 4.0.0  | 1         | 3.13%   |
| Q4OS 3.15.2 | 1         | 3.13%   |
| Q4OS 3.11.4 | 1         | 3.13%   |
| Q4OS 2      | 1         | 3.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Q4OS | 32        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 4.19.0-17-amd64        | 4         | 12.5%   |
| 5.10.0-12-amd64        | 3         | 9.38%   |
| 5.10.0-8-amd64         | 2         | 6.25%   |
| 5.10.0-10-686-pae      | 2         | 6.25%   |
| 5.9.0-5-amd64          | 1         | 3.13%   |
| 5.6.0-1-amd64          | 1         | 3.13%   |
| 5.10.0-9-amd64         | 1         | 3.13%   |
| 5.10.0-9-686-pae       | 1         | 3.13%   |
| 5.10.0-8-686-pae       | 1         | 3.13%   |
| 5.10.0-12-686-pae      | 1         | 3.13%   |
| 5.10.0-11-686-pae      | 1         | 3.13%   |
| 4.9.0-9-686-pae        | 1         | 3.13%   |
| 4.9.0-8-amd64          | 1         | 3.13%   |
| 4.9.0-14-686-pae       | 1         | 3.13%   |
| 4.9.0-12-686-pae       | 1         | 3.13%   |
| 4.19.0-6-amd64         | 1         | 3.13%   |
| 4.19.0-17-686-pae      | 1         | 3.13%   |
| 4.19.0-17-686          | 1         | 3.13%   |
| 4.19.0-16-amd64        | 1         | 3.13%   |
| 4.19.0-16-686          | 1         | 3.13%   |
| 4.19.0-14-amd64        | 1         | 3.13%   |
| 4.19.0-13-amd64        | 1         | 3.13%   |
| 4.19.0-12-amd64        | 1         | 3.13%   |
| 4.19.0-10-amd64        | 1         | 3.13%   |
| 4.19.0-0.bpo.5-686-pae | 1         | 3.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19.0  | 14        | 43.75%  |
| 5.10.0  | 12        | 37.5%   |
| 4.9.0   | 4         | 12.5%   |
| 5.9.0   | 1         | 3.13%   |
| 5.6.0   | 1         | 3.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19    | 14        | 43.75%  |
| 5.10    | 12        | 37.5%   |
| 4.9     | 4         | 12.5%   |
| 5.9     | 1         | 3.13%   |
| 5.6     | 1         | 3.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 19        | 59.38%  |
| i686   | 13        | 40.63%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| trinity | 17        | 53.13%  |
| KDE5    | 14        | 43.75%  |
| KDE     | 1         | 3.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 31        | 96.88%  |
| Tty  | 1         | 3.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| TDM  | 17        | 53.13%  |
| SDDM | 15        | 46.88%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 14        | 43.75%  |
| Unknown | 3         | 9.38%   |
| fr_FR   | 2         | 6.25%   |
| es_ES   | 2         | 6.25%   |
| en_GB   | 2         | 6.25%   |
| de_DE   | 2         | 6.25%   |
| sl_SI   | 1         | 3.13%   |
| pl_PL   | 1         | 3.13%   |
| es_VE   | 1         | 3.13%   |
| es_AR   | 1         | 3.13%   |
| en_ZA   | 1         | 3.13%   |
| en_SG   | 1         | 3.13%   |
| C       | 1         | 3.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 19        | 59.38%  |
| EFI  | 13        | 40.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 29        | 90.63%  |
| Overlay | 3         | 9.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 18        | 56.25%  |
| GPT     | 13        | 40.63%  |
| Unknown | 1         | 3.13%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 26        | 81.25%  |
| Yes       | 6         | 18.75%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 19        | 59.38%  |
| Yes       | 13        | 40.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 6         | 18.75%  |
| MSI                         | 3         | 9.38%   |
| ASUSTek Computer            | 3         | 9.38%   |
| TrekStor                    | 2         | 6.25%   |
| Toshiba                     | 2         | 6.25%   |
| Lenovo                      | 2         | 6.25%   |
| Visual Land                 | 1         | 3.13%   |
| TECO Electric and Machinery | 1         | 3.13%   |
| Qilive                      | 1         | 3.13%   |
| Phoenix/SiS                 | 1         | 3.13%   |
| Philco                      | 1         | 3.13%   |
| Packard Bell                | 1         | 3.13%   |
| JVC                         | 1         | 3.13%   |
| Gigabyte Technology         | 1         | 3.13%   |
| Compaq                      | 1         | 3.13%   |
| Chuwi                       | 1         | 3.13%   |
| ASRock                      | 1         | 3.13%   |
| AMI                         | 1         | 3.13%   |
| Acer                        | 1         | 3.13%   |
| Unknown                     | 1         | 3.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| TrekStor SurfTab wintron 7.0           | 2         | 6.25%   |
| Toshiba Satellite C660                 | 2         | 6.25%   |
| Visual Land Premier 10                 | 1         | 3.13%   |
| TECO Electric and Machinery FUTRO S400 | 1         | 3.13%   |
| Qilive QW19141AMSP                     | 1         | 3.13%   |
| Phoenix/SiS M720SR                     | 1         | 3.13%   |
| Philco 14I                             | 1         | 3.13%   |
| Packard Bell EasyNote LM81             | 1         | 3.13%   |
| MSI U210                               | 1         | 3.13%   |
| MSI MS-7C56                            | 1         | 3.13%   |
| MSI MS-7597                            | 1         | 3.13%   |
| Lenovo ThinkPad 11e 20DAS0PS00         | 1         | 3.13%   |
| Lenovo IdeaPad 330-15IGM 81D1          | 1         | 3.13%   |
| JVC J3N                                | 1         | 3.13%   |
| HP ProBook 6550b                       | 1         | 3.13%   |
| HP ProBook 450 G2                      | 1         | 3.13%   |
| HP Presario CQ56                       | 1         | 3.13%   |
| HP OmniBook PC                         | 1         | 3.13%   |
| HP Laptop 15s-fq2xxx                   | 1         | 3.13%   |
| HP 2000                                | 1         | 3.13%   |
| Gigabyte XP-M5S661GX                   | 1         | 3.13%   |
| Compaq Evo D510 SFF                    | 1         | 3.13%   |
| Chuwi GemiBook Pro                     | 1         | 3.13%   |
| ASUS X540YA                            | 1         | 3.13%   |
| ASUS T12Eg                             | 1         | 3.13%   |
| ASUS A6JC                              | 1         | 3.13%   |
| ASRock G41M-VS3                        | 1         | 3.13%   |
| AMI Intel                              | 1         | 3.13%   |
| Acer AO751h                            | 1         | 3.13%   |
| Unknown                                | 1         | 3.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| TrekStor SurfTab                  | 2         | 6.25%   |
| Toshiba Satellite                 | 2         | 6.25%   |
| HP ProBook                        | 2         | 6.25%   |
| Visual Land Premier               | 1         | 3.13%   |
| TECO Electric and Machinery FUTRO | 1         | 3.13%   |
| Qilive QW19141AMSP                | 1         | 3.13%   |
| Phoenix/SiS M720SR                | 1         | 3.13%   |
| Philco 14I                        | 1         | 3.13%   |
| Packard Bell EasyNote             | 1         | 3.13%   |
| MSI U210                          | 1         | 3.13%   |
| MSI MS-7C56                       | 1         | 3.13%   |
| MSI MS-7597                       | 1         | 3.13%   |
| Lenovo ThinkPad                   | 1         | 3.13%   |
| Lenovo IdeaPad                    | 1         | 3.13%   |
| JVC J3N                           | 1         | 3.13%   |
| HP Presario                       | 1         | 3.13%   |
| HP OmniBook                       | 1         | 3.13%   |
| HP Laptop                         | 1         | 3.13%   |
| HP 2000                           | 1         | 3.13%   |
| Gigabyte XP-M5S661GX              | 1         | 3.13%   |
| Compaq Evo                        | 1         | 3.13%   |
| Chuwi GemiBook                    | 1         | 3.13%   |
| ASUS X540YA                       | 1         | 3.13%   |
| ASUS T12Eg                        | 1         | 3.13%   |
| ASUS A6JC                         | 1         | 3.13%   |
| ASRock G41M-VS3                   | 1         | 3.13%   |
| AMI Intel                         | 1         | 3.13%   |
| Acer AO751h                       | 1         | 3.13%   |
| Unknown                           | 1         | 3.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2010    | 6         | 18.75%  |
| 2020    | 4         | 12.5%   |
| 2015    | 3         | 9.38%   |
| 2014    | 2         | 6.25%   |
| 2011    | 2         | 6.25%   |
| 2009    | 2         | 6.25%   |
| Unknown | 2         | 6.25%   |
| 2019    | 1         | 3.13%   |
| 2018    | 1         | 3.13%   |
| 2017    | 1         | 3.13%   |
| 2016    | 1         | 3.13%   |
| 2012    | 1         | 3.13%   |
| 2008    | 1         | 3.13%   |
| 2007    | 1         | 3.13%   |
| 2006    | 1         | 3.13%   |
| 2005    | 1         | 3.13%   |
| 2004    | 1         | 3.13%   |
| 2002    | 1         | 3.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 24        | 75%     |
| Desktop  | 6         | 18.75%  |
| Tablet   | 2         | 6.25%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 31        | 96.88%  |
| Enabled  | 1         | 3.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 32        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 8         | 25%     |
| 0.51-1.0    | 6         | 18.75%  |
| 2.01-3.0    | 5         | 15.63%  |
| 1.01-2.0    | 5         | 15.63%  |
| 4.01-8.0    | 4         | 12.5%   |
| 0.01-0.5    | 2         | 6.25%   |
| 64.01-256.0 | 1         | 3.13%   |
| 16.01-24.0  | 1         | 3.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 11        | 34.38%  |
| 0.51-1.0  | 10        | 31.25%  |
| 0.01-0.5  | 5         | 15.63%  |
| 2.01-3.0  | 4         | 12.5%   |
| 3.01-4.0  | 1         | 3.13%   |
| 8.01-16.0 | 1         | 3.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 24        | 75%     |
| 2      | 5         | 15.63%  |
| 3      | 3         | 9.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 17        | 53.13%  |
| Yes       | 15        | 46.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 87.5%   |
| No        | 4         | 12.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 68.75%  |
| No        | 10        | 31.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 20        | 62.5%   |
| Yes       | 12        | 37.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 4         | 12.5%   |
| Kenya        | 3         | 9.38%   |
| UK           | 2         | 6.25%   |
| Switzerland  | 2         | 6.25%   |
| Spain        | 2         | 6.25%   |
| Romania      | 2         | 6.25%   |
| Poland       | 2         | 6.25%   |
| Germany      | 2         | 6.25%   |
| France       | 2         | 6.25%   |
| Venezuela    | 1         | 3.13%   |
| South Africa | 1         | 3.13%   |
| Slovenia     | 1         | 3.13%   |
| Singapore    | 1         | 3.13%   |
| Saudi Arabia | 1         | 3.13%   |
| Qatar        | 1         | 3.13%   |
| Netherlands  | 1         | 3.13%   |
| Italy        | 1         | 3.13%   |
| Brazil       | 1         | 3.13%   |
| Belarus      | 1         | 3.13%   |
| Argentina    | 1         | 3.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Nairobi               | 3         | 9.38%   |
| Zurich                | 2         | 6.25%   |
| Swindon               | 2         | 6.25%   |
| Rostock               | 2         | 6.25%   |
| Drobeta-Turnu Severin | 2         | 6.25%   |
| Wygledy               | 1         | 3.13%   |
| Tellico Plains        | 1         | 3.13%   |
| Someren               | 1         | 3.13%   |
| Singapore             | 1         | 3.13%   |
| Posadas               | 1         | 3.13%   |
| Moirans               | 1         | 3.13%   |
| Mogilev               | 1         | 3.13%   |
| Mestre                | 1         | 3.13%   |
| Mesa                  | 1         | 3.13%   |
| Londrina              | 1         | 3.13%   |
| Ljubljana             | 1         | 3.13%   |
| Las Vegas             | 1         | 3.13%   |
| Katowice              | 1         | 3.13%   |
| Johannesburg          | 1         | 3.13%   |
| Grand Junction        | 1         | 3.13%   |
| GijГіn              | 1         | 3.13%   |
| Doha                  | 1         | 3.13%   |
| Dammam                | 1         | 3.13%   |
| Boulogne-sur-Mer      | 1         | 3.13%   |
| Barcelona             | 1         | 3.13%   |
| Agua Salada           | 1         | 3.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 16.22%  |
| Unknown             | 5         | 5      | 13.51%  |
| Seagate             | 5         | 6      | 13.51%  |
| SanDisk             | 3         | 3      | 8.11%   |
| Samsung Electronics | 3         | 3      | 8.11%   |
| Hitachi             | 3         | 3      | 8.11%   |
| KESU                | 2         | 2      | 5.41%   |
| HGST                | 2         | 2      | 5.41%   |
| China               | 2         | 2      | 5.41%   |
| Unknown (CF)        | 1         | 1      | 2.7%    |
| Toshiba             | 1         | 1      | 2.7%    |
| MAXTOR              | 1         | 1      | 2.7%    |
| Kingston            | 1         | 1      | 2.7%    |
| Fujitsu             | 1         | 1      | 2.7%    |
| A-DATA Technology   | 1         | 1      | 2.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown NCard  16GB                  | 2         | 5.26%   |
| KESU USB 3.1 128GB                   | 2         | 5.26%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 2.63%   |
| WDC WD400BD-23JMC0 40GB              | 1         | 2.63%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 2.63%   |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 2.63%   |
| WDC WD1600AAJS-00L7A0 160GB          | 1         | 2.63%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 2.63%   |
| Unknown USDU1  32GB                  | 1         | 2.63%   |
| Unknown SLD64G  64GB                 | 1         | 2.63%   |
| Unknown 064G38  64GB                 | 1         | 2.63%   |
| Unknown (CF) Card 8GB SSD            | 1         | 2.63%   |
| Toshiba MK8025GAS 80GB               | 1         | 2.63%   |
| Seagate ST9120822AS 120GB            | 1         | 2.63%   |
| Seagate ST8000DM004-2CX188 8TB       | 1         | 2.63%   |
| Seagate ST3160815AS 160GB            | 1         | 2.63%   |
| Seagate ST3160812AS 160GB            | 1         | 2.63%   |
| Seagate ST310211A 10GB               | 1         | 2.63%   |
| Seagate Backup+ SL 1TB               | 1         | 2.63%   |
| SanDisk SDSSDA120G 120GB             | 1         | 2.63%   |
| SanDisk SDCFX-032G SSD               | 1         | 2.63%   |
| SanDisk SD8SN8U1T001122 1024GB SSD   | 1         | 2.63%   |
| Samsung SSD 850 EVO 250GB            | 1         | 2.63%   |
| Samsung HD081GJ 80GB                 | 1         | 2.63%   |
| Samsung AWMB3R  16GB                 | 1         | 2.63%   |
| MAXTOR 6Y080L0 82GB                  | 1         | 2.63%   |
| Kingston SV300S37A60G 64GB SSD       | 1         | 2.63%   |
| Hitachi HTS545032B9A300 320GB        | 1         | 2.63%   |
| Hitachi HTS543225L9SA00 250GB        | 1         | 2.63%   |
| Hitachi DK23CA-20 20GB               | 1         | 2.63%   |
| HGST HTS725050A7E630 500GB           | 1         | 2.63%   |
| HGST HTS541075A9E680 752GB           | 1         | 2.63%   |
| Fujitsu MHY2080BH 80GB               | 1         | 2.63%   |
| China SSD128GBS800                   | 1         | 2.63%   |
| China SATA SSD 240GB                 | 1         | 2.63%   |
| A-DATA SU630 240GB SSD               | 1         | 2.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 23.53%  |
| Seagate             | 4         | 5      | 23.53%  |
| Hitachi             | 3         | 3      | 17.65%  |
| HGST                | 2         | 2      | 11.76%  |
| Toshiba             | 1         | 1      | 5.88%   |
| Samsung Electronics | 1         | 1      | 5.88%   |
| MAXTOR              | 1         | 1      | 5.88%   |
| Fujitsu             | 1         | 1      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 3         | 3      | 30%     |
| China               | 2         | 2      | 20%     |
| WDC                 | 1         | 1      | 10%     |
| Unknown (CF)        | 1         | 1      | 10%     |
| Samsung Electronics | 1         | 1      | 10%     |
| Kingston            | 1         | 1      | 10%     |
| A-DATA Technology   | 1         | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 15        | 18     | 44.12%  |
| SSD     | 9         | 10     | 26.47%  |
| MMC     | 6         | 6      | 17.65%  |
| Unknown | 3         | 3      | 8.82%   |
| NVMe    | 1         | 1      | 2.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 23        | 28     | 69.7%   |
| MMC  | 6         | 6      | 18.18%  |
| SAS  | 3         | 3      | 9.09%   |
| NVMe | 1         | 1      | 3.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 21        | 25     | 87.5%   |
| 1.01-2.0   | 1         | 1      | 4.17%   |
| 4.01-10.0  | 1         | 1      | 4.17%   |
| 0.51-1.0   | 1         | 1      | 4.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 9         | 28.13%  |
| 51-100         | 7         | 21.88%  |
| 21-50          | 5         | 15.63%  |
| 101-250        | 4         | 12.5%   |
| 251-500        | 3         | 9.38%   |
| More than 3000 | 1         | 3.13%   |
| 1001-2000      | 1         | 3.13%   |
| 501-1000       | 1         | 3.13%   |
| Unknown        | 1         | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 23        | 71.88%  |
| 21-50          | 5         | 15.63%  |
| More than 3000 | 1         | 3.13%   |
| 251-500        | 1         | 3.13%   |
| 501-1000       | 1         | 3.13%   |
| Unknown        | 1         | 3.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD400BD-23JMC0 40GB       | 1         | 1      | 10%     |
| WDC WD2500BEVT-60A23T0 250GB  | 1         | 1      | 10%     |
| Seagate ST9120822AS 120GB     | 1         | 1      | 10%     |
| MAXTOR 6Y080L0 82GB           | 1         | 1      | 10%     |
| Hitachi HTS545032B9A300 320GB | 1         | 1      | 10%     |
| Hitachi HTS543225L9SA00 250GB | 1         | 1      | 10%     |
| Hitachi DK23CA-20 20GB        | 1         | 1      | 10%     |
| HGST HTS725050A7E630 500GB    | 1         | 1      | 10%     |
| HGST HTS541075A9E680 752GB    | 1         | 1      | 10%     |
| Fujitsu MHY2080BH 80GB        | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 3         | 3      | 30%     |
| WDC     | 2         | 2      | 20%     |
| HGST    | 2         | 2      | 20%     |
| Seagate | 1         | 1      | 10%     |
| MAXTOR  | 1         | 1      | 10%     |
| Fujitsu | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 3         | 3      | 30%     |
| WDC     | 2         | 2      | 20%     |
| HGST    | 2         | 2      | 20%     |
| Seagate | 1         | 1      | 10%     |
| MAXTOR  | 1         | 1      | 10%     |
| Fujitsu | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 10     | 100%    |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 14        | 18     | 42.42%  |
| Malfunc  | 10        | 10     | 30.3%   |
| Detected | 9         | 10     | 27.27%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 17        | 58.62%  |
| AMD                              | 7         | 24.14%  |
| Silicon Integrated Systems [SiS] | 3         | 10.34%  |
| Sandisk                          | 1         | 3.45%   |
| Nvidia                           | 1         | 3.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                          | 4         | 11.11%  |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                         | 3         | 8.33%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 3         | 8.33%   |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 2         | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 2         | 5.56%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                  | 1         | 2.78%   |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS]    | 1         | 2.78%   |
| Sandisk WD Blue SN550 NVMe SSD                                               | 1         | 2.78%   |
| Nvidia MCP61 SATA Controller                                                 | 1         | 2.78%   |
| Nvidia MCP61 IDE                                                             | 1         | 2.78%   |
| Intel Volume Management Device NVMe RAID Controller                          | 1         | 2.78%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                   | 1         | 2.78%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                            | 1         | 2.78%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 1         | 2.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 1         | 2.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                 | 1         | 2.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 1         | 2.78%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                       | 1         | 2.78%   |
| Intel 82801DB (ICH4) IDE Controller                                          | 1         | 2.78%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                | 1         | 2.78%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 2.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 1         | 2.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                             | 1         | 2.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 1         | 2.78%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                         | 1         | 2.78%   |
| AMD SB600 Non-Raid-5 SATA                                                    | 1         | 2.78%   |
| AMD 500 Series Chipset SATA Controller                                       | 1         | 2.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 16        | 51.61%  |
| IDE  | 12        | 38.71%  |
| RAID | 2         | 6.45%   |
| NVMe | 1         | 3.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 23        | 71.88%  |
| AMD    | 9         | 28.13%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom CPU Z3735G @ 1.33GHz               | 3         | 9.38%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 6.25%   |
| Intel Pentium M processor 1000MHz             | 1         | 3.13%   |
| Intel Pentium III (Coppermine)                | 1         | 3.13%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 3.13%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 1         | 3.13%   |
| Intel Pentium 4 CPU 3.00GHz                   | 1         | 3.13%   |
| Intel Pentium 4 CPU 2.00GHz                   | 1         | 3.13%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 3.13%   |
| Intel Core i5 CPU M 450 @ 2.40GHz             | 1         | 3.13%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 1         | 3.13%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz          | 1         | 3.13%   |
| Intel Core 2 CPU T5500 @ 1.66GHz              | 1         | 3.13%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 3.13%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 3.13%   |
| Intel Celeron J4115 CPU @ 1.80GHz             | 1         | 3.13%   |
| Intel Celeron CPU N2940 @ 1.83GHz             | 1         | 3.13%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 1         | 3.13%   |
| Intel Atom CPU Z520 @ 1.33GHz                 | 1         | 3.13%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 3.13%   |
| AMD V120 Processor                            | 1         | 3.13%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 1         | 3.13%   |
| AMD E-300 APU with Radeon HD Graphics         | 1         | 3.13%   |
| AMD C-70 APU with Radeon HD Graphics          | 1         | 3.13%   |
| AMD Athlon Processor                          | 1         | 3.13%   |
| AMD Athlon Neo Processor MV-40                | 1         | 3.13%   |
| AMD Athlon II X2 250 Processor                | 1         | 3.13%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 1         | 3.13%   |
| AMD A4-9120e RADEON R3, 4 COMPUTE CORES 2C+2G | 1         | 3.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 5         | 15.63%  |
| Intel Celeron           | 4         | 12.5%   |
| Intel Pentium Dual-Core | 2         | 6.25%   |
| Intel Pentium 4         | 2         | 6.25%   |
| Intel Core i5           | 2         | 6.25%   |
| Intel Core i3           | 2         | 6.25%   |
| Intel Core 2 Duo        | 2         | 6.25%   |
| Other                   | 1         | 3.13%   |
| Intel Pentium M         | 1         | 3.13%   |
| Intel Pentium III       | 1         | 3.13%   |
| Intel Core 2            | 1         | 3.13%   |
| AMD V120                | 1         | 3.13%   |
| AMD Ryzen 7             | 1         | 3.13%   |
| AMD E                   | 1         | 3.13%   |
| AMD C-70                | 1         | 3.13%   |
| AMD Athlon Neo          | 1         | 3.13%   |
| AMD Athlon II X2        | 1         | 3.13%   |
| AMD Athlon              | 1         | 3.13%   |
| AMD A8                  | 1         | 3.13%   |
| AMD A4                  | 1         | 3.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 14        | 43.75%  |
| 4      | 9         | 28.13%  |
| 1      | 8         | 25%     |
| 8      | 1         | 3.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 32        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 24        | 75%     |
| 2      | 8         | 25%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 27        | 84.38%  |
| 32-bit         | 5         | 15.63%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x30678    | 4         | 12.5%   |
| Unknown    | 4         | 12.5%   |
| 0x706a1    | 2         | 6.25%   |
| 0x6fd      | 2         | 6.25%   |
| 0x206a7    | 2         | 6.25%   |
| 0x1067a    | 2         | 6.25%   |
| 0x010000c8 | 2         | 6.25%   |
| 0xf49      | 1         | 3.13%   |
| 0xf27      | 1         | 3.13%   |
| 0x806c1    | 1         | 3.13%   |
| 0x706a8    | 1         | 3.13%   |
| 0x6f6      | 1         | 3.13%   |
| 0x695      | 1         | 3.13%   |
| 0x68a      | 1         | 3.13%   |
| 0x40651    | 1         | 3.13%   |
| 0x20655    | 1         | 3.13%   |
| 0x0800820d | 1         | 3.13%   |
| 0x07030106 | 1         | 3.13%   |
| 0x06006705 | 1         | 3.13%   |
| 0x05000119 | 1         | 3.13%   |
| 0x0500010d | 1         | 3.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 5         | 15.63%  |
| Goldmont plus | 3         | 9.38%   |
| Core          | 3         | 9.38%   |
| SandyBridge   | 2         | 6.25%   |
| Penryn        | 2         | 6.25%   |
| P6            | 2         | 6.25%   |
| NetBurst      | 2         | 6.25%   |
| K10           | 2         | 6.25%   |
| Bobcat        | 2         | 6.25%   |
| Zen+          | 1         | 3.13%   |
| Westmere      | 1         | 3.13%   |
| TigerLake     | 1         | 3.13%   |
| Puma          | 1         | 3.13%   |
| K8 Hammer     | 1         | 3.13%   |
| K6            | 1         | 3.13%   |
| Haswell       | 1         | 3.13%   |
| Excavator     | 1         | 3.13%   |
| Bonnell       | 1         | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 18        | 54.55%  |
| AMD                              | 8         | 24.24%  |
| Silicon Integrated Systems [SiS] | 3         | 9.09%   |
| Nvidia                           | 3         | 9.09%   |
| S3 Graphics                      | 1         | 3.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 4         | 11.76%  |
| Intel GeminiLake [UHD Graphics 600]                                                        | 3         | 8.82%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 2         | 5.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 2         | 5.88%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 1         | 2.94%   |
| S3 Graphics 86C270-294 [SavageIX-MV]                                                       | 1         | 2.94%   |
| Nvidia GM206 [GeForce GTX 960]                                                             | 1         | 2.94%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                              | 1         | 2.94%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                    | 1         | 2.94%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 1         | 2.94%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 1         | 2.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 1         | 2.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 1         | 2.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 1         | 2.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 1         | 2.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 1         | 2.94%   |
| Intel 82852/855GM Integrated Graphics Device                                               | 1         | 2.94%   |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device                         | 1         | 2.94%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 1         | 2.94%   |
| AMD Wrestler [Radeon HD 7290]                                                              | 1         | 2.94%   |
| AMD Wrestler [Radeon HD 6310]                                                              | 1         | 2.94%   |
| AMD Topaz PRO [Radeon R5 M255]                                                             | 1         | 2.94%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 1         | 2.94%   |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                               | 1         | 2.94%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                  | 1         | 2.94%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                  | 1         | 2.94%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                        | 1         | 2.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 16        | 50%     |
| 1 x AMD         | 7         | 21.88%  |
| 1 x SiS         | 3         | 9.38%   |
| 1 x Nvidia      | 3         | 9.38%   |
| Other           | 1         | 3.13%   |
| 1 x S3 Graphics | 1         | 3.13%   |
| Intel + AMD     | 1         | 3.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 26        | 81.25%  |
| Unknown     | 4         | 12.5%   |
| Proprietary | 2         | 6.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 20        | 62.5%   |
| 0.01-0.5   | 9         | 28.13%  |
| 1.01-2.0   | 3         | 9.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 5         | 17.86%  |
| Chimei Innolux      | 5         | 17.86%  |
| AU Optronics        | 5         | 17.86%  |
| LG Display          | 3         | 10.71%  |
| Hewlett-Packard     | 2         | 7.14%   |
| ViewSonic           | 1         | 3.57%   |
| VIE                 | 1         | 3.57%   |
| Orion               | 1         | 3.57%   |
| HannStar            | 1         | 3.57%   |
| Goldstar            | 1         | 3.57%   |
| Dell                | 1         | 3.57%   |
| CPT                 | 1         | 3.57%   |
| BOE                 | 1         | 3.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 7.14%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch               | 1         | 3.57%   |
| VIE S20W VIE2080 1600x900 440x250mm 19.9-inch                           | 1         | 3.57%   |
| Samsung Electronics S24B20/S24B30 SAM09ED 1920x1080 521x293mm 23.5-inch | 1         | 3.57%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch     | 1         | 3.57%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 1         | 3.57%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch    | 1         | 3.57%   |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 1020x570mm 46.0-inch  | 1         | 3.57%   |
| Orion ORION ORN120A 1920x540                                            | 1         | 3.57%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch             | 1         | 3.57%   |
| Hewlett-Packard Z24i HWP3100 1920x1200 518x324mm 24.1-inch              | 1         | 3.57%   |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch               | 1         | 3.57%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                | 1         | 3.57%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                    | 1         | 3.57%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                        | 1         | 3.57%   |
| CPT LCD Monitor CPT13B1 1280x800 330x210mm 15.4-inch                    | 1         | 3.57%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch        | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch         | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch         | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 1         | 3.57%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                    | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch          | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 256x144mm 11.6-inch          | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch           | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch           | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch           | 1         | 3.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 9         | 32.14%  |
| 1920x1080 (FHD)    | 7         | 25%     |
| 1600x900 (HD+)     | 5         | 17.86%  |
| 1280x800 (WXGA)    | 2         | 7.14%   |
| 3840x2160 (4K)     | 1         | 3.57%   |
| 2160x1440          | 1         | 3.57%   |
| 1920x540           | 1         | 3.57%   |
| 1920x1200 (WUXGA)  | 1         | 3.57%   |
| 1680x1050 (WSXGA+) | 1         | 3.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 10        | 35.71%  |
| 23      | 2         | 7.14%   |
| 13      | 2         | 7.14%   |
| 11      | 2         | 7.14%   |
| 46      | 1         | 3.57%   |
| 40      | 1         | 3.57%   |
| 31      | 1         | 3.57%   |
| 24      | 1         | 3.57%   |
| 22      | 1         | 3.57%   |
| 20      | 1         | 3.57%   |
| 19      | 1         | 3.57%   |
| 18      | 1         | 3.57%   |
| 17      | 1         | 3.57%   |
| 14      | 1         | 3.57%   |
| 12      | 1         | 3.57%   |
| Unknown | 1         | 3.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 12        | 42.86%  |
| 201-300     | 4         | 14.29%  |
| 501-600     | 3         | 10.71%  |
| 401-500     | 3         | 10.71%  |
| 351-400     | 2         | 7.14%   |
| 801-900     | 1         | 3.57%   |
| 601-700     | 1         | 3.57%   |
| 1001-1500   | 1         | 3.57%   |
| Unknown     | 1         | 3.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 19        | 76%     |
| 16/10 | 4         | 16%     |
| 32/9  | 1         | 4%      |
| 3/2   | 1         | 4%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 10        | 35.71%  |
| 81-90          | 3         | 10.71%  |
| 201-250        | 3         | 10.71%  |
| 51-60          | 2         | 7.14%   |
| 151-200        | 2         | 7.14%   |
| 501-1000       | 2         | 7.14%   |
| 61-70          | 1         | 3.57%   |
| 351-500        | 1         | 3.57%   |
| 251-300        | 1         | 3.57%   |
| 141-150        | 1         | 3.57%   |
| 121-130        | 1         | 3.57%   |
| Unknown        | 1         | 3.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 10        | 35.71%  |
| 51-100  | 9         | 32.14%  |
| 121-160 | 5         | 17.86%  |
| 161-240 | 2         | 7.14%   |
| 1-50    | 1         | 3.57%   |
| Unknown | 1         | 3.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 27        | 84.38%  |
| 2     | 2         | 6.25%   |
| 0     | 2         | 6.25%   |
| 3     | 1         | 3.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 21        | 41.18%  |
| Qualcomm Atheros                 | 10        | 19.61%  |
| Intel                            | 8         | 15.69%  |
| Silicon Integrated Systems [SiS] | 2         | 3.92%   |
| Samsung Electronics              | 2         | 3.92%   |
| Broadcom                         | 2         | 3.92%   |
| Xiaomi                           | 1         | 1.96%   |
| Motorola PCS                     | 1         | 1.96%   |
| LG Electronics                   | 1         | 1.96%   |
| JMicron Technology               | 1         | 1.96%   |
| IBM                              | 1         | 1.96%   |
| Accton Technology                | 1         | 1.96%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 7         | 12.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 6         | 11.11%  |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 5.56%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 3.7%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 2         | 3.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 3.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 3.7%    |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 1.85%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet               | 1         | 1.85%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.85%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 1.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 1.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 1.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 1.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 1.85%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1         | 1.85%   |
| Motorola PCS moto g(30)                                                 | 1         | 1.85%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                     | 1         | 1.85%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 1.85%   |
| Intel Wireless 3165                                                     | 1         | 1.85%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 1.85%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 1.85%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.85%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 1         | 1.85%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                      | 1         | 1.85%   |
| Intel 82577LC Gigabit Network Connection                                | 1         | 1.85%   |
| IBM Winnipeg PCI-X Host Bridge                                          | 1         | 1.85%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 1         | 1.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 1.85%   |
| Accton EN-1216 Ethernet Adapter                                         | 1         | 1.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 10        | 45.45%  |
| Intel                 | 6         | 27.27%  |
| Realtek Semiconductor | 5         | 22.73%  |
| Broadcom              | 1         | 4.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 13.64%  |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 9.09%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 9.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 4.55%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 4.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 4.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 4.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 4.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 4.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 4.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 4.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 4.55%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1         | 4.55%   |
| Intel Wireless 3165                                                     | 1         | 4.55%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 4.55%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 4.55%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 4.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 4.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 17        | 56.67%  |
| Silicon Integrated Systems [SiS] | 2         | 6.67%   |
| Samsung Electronics              | 2         | 6.67%   |
| Intel                            | 2         | 6.67%   |
| Xiaomi                           | 1         | 3.33%   |
| Qualcomm Atheros                 | 1         | 3.33%   |
| Motorola PCS                     | 1         | 3.33%   |
| LG Electronics                   | 1         | 3.33%   |
| JMicron Technology               | 1         | 3.33%   |
| Broadcom                         | 1         | 3.33%   |
| Accton Technology                | 1         | 3.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 23.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 20%     |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 6.67%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 6.67%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 3.33%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 3.33%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 3.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 3.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 3.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 3.33%   |
| Motorola PCS moto g(30)                                           | 1         | 3.33%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)               | 1         | 3.33%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 3.33%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                | 1         | 3.33%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 3.33%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 3.33%   |
| Accton EN-1216 Ethernet Adapter                                   | 1         | 3.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 28        | 53.85%  |
| WiFi     | 22        | 42.31%  |
| Modem    | 1         | 1.92%   |
| Unknown  | 1         | 1.92%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 22        | 52.38%  |
| WiFi     | 20        | 47.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 17        | 53.13%  |
| 1     | 11        | 34.38%  |
| 0     | 4         | 12.5%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 30        | 93.75%  |
| Yes  | 2         | 6.25%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros Communications | 4         | 33.33%  |
| Intel                           | 3         | 25%     |
| Realtek Semiconductor           | 2         | 16.67%  |
| Hewlett-Packard                 | 1         | 8.33%   |
| Cambridge Silicon Radio         | 1         | 8.33%   |
| ASUSTek Computer                | 1         | 8.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 25%     |
| Realtek Bluetooth Radio                             | 2         | 16.67%  |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 8.33%   |
| Intel Bluetooth wireless interface                  | 1         | 8.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 8.33%   |
| Intel AX200 Bluetooth                               | 1         | 8.33%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 8.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 8.33%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 8.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 16        | 55.17%  |
| AMD                              | 8         | 27.59%  |
| Silicon Integrated Systems [SiS] | 2         | 6.9%    |
| Nvidia                           | 2         | 6.9%    |
| ESS Technology                   | 1         | 3.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 8.33%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 8.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 5.56%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 5.56%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 5.56%   |
| AMD FCH Azalia Controller                                                  | 2         | 5.56%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller            | 1         | 2.78%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 2.78%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 2.78%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 2.78%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1         | 2.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 2.78%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 2.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 2.78%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 2.78%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 2.78%   |
| ESS Technology ES1988 Allegro-1                                            | 1         | 2.78%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 2.78%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 2.78%   |
| AMD RS690 HDMI Audio [Radeon Xpress 1200 Series]                           | 1         | 2.78%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 2.78%   |
| AMD High Definition Audio Controller                                       | 1         | 2.78%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 2.78%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 2.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 14        | 45.16%  |
| Samsung Electronics | 5         | 16.13%  |
| SK Hynix            | 4         | 12.9%   |
| Unknown (ABCD)      | 2         | 6.45%   |
| Kingston            | 2         | 6.45%   |
| Transcend           | 1         | 3.23%   |
| Team                | 1         | 3.23%   |
| Elpida              | 1         | 3.23%   |
| A-DATA Technology   | 1         | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 3         | 9.09%   |
| Unknown RAM Module 1024MB DIMM DDR3 1333MT/s                     | 2         | 6.06%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 2         | 6.06%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 2         | 6.06%   |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 3.03%   |
| Unknown RAM Module 512MB DIMM 400MT/s                            | 1         | 3.03%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 3.03%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 3.03%   |
| Unknown RAM Module 256MB SODIMM SDRAM                            | 1         | 3.03%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 3.03%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1066MT/s                    | 1         | 3.03%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 3.03%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 3.03%   |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                        | 1         | 3.03%   |
| Transcend RAM Module 1GB DIMM SDRAM 266MT/s                      | 1         | 3.03%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s              | 1         | 3.03%   |
| SK Hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 1         | 3.03%   |
| SK Hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 800MT/s         | 1         | 3.03%   |
| SK Hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 3.03%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2400MT/s        | 1         | 3.03%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1334MT/s         | 1         | 3.03%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 3.03%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 3.03%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 1         | 3.03%   |
| Kingston RAM HP32D4S2S1ME-4 4GB SODIMM DDR4 3200MT/s             | 1         | 3.03%   |
| Kingston RAM 99U5428-041.A01G 4GB SODIMM DDR3 1067MT/s           | 1         | 3.03%   |
| Elpida RAM EBJ10UE8BDS0-AE-F 1GB SODIMM DDR3 1067MT/s            | 1         | 3.03%   |
| A-DATA RAM AM1U16BC2P1-B1AH 2GB SODIMM DDR3 4199MT/s             | 1         | 3.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 11        | 36.67%  |
| SDRAM   | 6         | 20%     |
| DDR4    | 4         | 13.33%  |
| DDR2    | 4         | 13.33%  |
| LPDDR4  | 2         | 6.67%   |
| Unknown | 2         | 6.67%   |
| DRAM    | 1         | 3.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 21        | 70%     |
| DIMM   | 9         | 30%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 11        | 34.38%  |
| 2048  | 10        | 31.25%  |
| 1024  | 6         | 18.75%  |
| 512   | 3         | 9.38%   |
| 16384 | 1         | 3.13%   |
| 256   | 1         | 3.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 8         | 25.81%  |
| 1333    | 4         | 12.9%   |
| 2400    | 3         | 9.68%   |
| 1600    | 3         | 9.68%   |
| 1334    | 3         | 9.68%   |
| 1067    | 2         | 6.45%   |
| 4199    | 1         | 3.23%   |
| 3600    | 1         | 3.23%   |
| 3266    | 1         | 3.23%   |
| 3200    | 1         | 3.23%   |
| 1066    | 1         | 3.23%   |
| 800     | 1         | 3.23%   |
| 400     | 1         | 3.23%   |
| 266     | 1         | 3.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Brother HL-1110 series | 1         | 100%    |

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


| Vendor                                 | Computers | Percent |
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


| Model                                                       | Computers | Percent |
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


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 25        | 78.13%  |
| 1     | 4         | 12.5%   |
| 2     | 3         | 9.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 5         | 50%     |
| Fingerprint reader       | 2         | 20%     |
| Network                  | 1         | 10%     |
| Flash memory             | 1         | 10%     |
| Communication controller | 1         | 10%     |

