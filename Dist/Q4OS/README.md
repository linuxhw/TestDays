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

Total: 43

| Vendor        | Model                   | Form-Factor | Probe                                                      | Date         |
|---------------|-------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 250 G5 Notebook PC      | Notebook    | [0e5792fc9f](https://linux-hardware.org/?probe=0e5792fc9f) | May 15, 2022 |
| ASRock        | H61M-HVS                | Desktop     | [a9ee15a4d2](https://linux-hardware.org/?probe=a9ee15a4d2) | May 13, 2022 |
| ASUSTek       | A6U                     | Notebook    | [4a8ad00e5e](https://linux-hardware.org/?probe=4a8ad00e5e) | May 12, 2022 |
| Toshiba       | Satellite Pro L500      | Notebook    | [5b72ea9a47](https://linux-hardware.org/?probe=5b72ea9a47) | May 02, 2022 |
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
| Medion        | Unknown                 | Notebook    | [6a06a14f6a](https://linux-hardware.org/?probe=6a06a14f6a) | May 07, 2020 |
| TrekStor      | SurfTab wintron 7.0     | Tablet      | [464706154e](https://linux-hardware.org/?probe=464706154e) | Jun 26, 2019 |
| TrekStor      | SurfTab wintron 7.0     | Tablet      | [db63ea2d00](https://linux-hardware.org/?probe=db63ea2d00) | Jun 19, 2019 |
| TrekStor      | SurfTab wintron 7.0     | Tablet      | [9e530b2e21](https://linux-hardware.org/?probe=9e530b2e21) | Jun 18, 2019 |
| Philco        | 14I                     | Notebook    | [bf4c449b31](https://linux-hardware.org/?probe=bf4c449b31) | Apr 14, 2019 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Q4OS 4 | 17        | 47.22%  |
| Q4OS 3 | 14        | 38.89%  |
| Q4OS 2 | 5         | 13.89%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Q4OS | 36        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 4.19.0-17-amd64        | 4         | 11.11%  |
| 5.10.0-12-amd64        | 3         | 8.33%   |
| 5.10.0-8-amd64         | 2         | 5.56%   |
| 5.10.0-10-686-pae      | 2         | 5.56%   |
| 5.9.0-5-amd64          | 1         | 2.78%   |
| 5.6.0-1-amd64          | 1         | 2.78%   |
| 5.10.0-9-amd64         | 1         | 2.78%   |
| 5.10.0-9-686-pae       | 1         | 2.78%   |
| 5.10.0-8-686-pae       | 1         | 2.78%   |
| 5.10.0-14-amd64        | 1         | 2.78%   |
| 5.10.0-14-686-pae      | 1         | 2.78%   |
| 5.10.0-13-amd64        | 1         | 2.78%   |
| 5.10.0-12-686-pae      | 1         | 2.78%   |
| 5.10.0-11-686-pae      | 1         | 2.78%   |
| 4.9.0-9-686-pae        | 1         | 2.78%   |
| 4.9.0-8-amd64          | 1         | 2.78%   |
| 4.9.0-14-686-pae       | 1         | 2.78%   |
| 4.9.0-12-686-pae       | 1         | 2.78%   |
| 4.19.0-6-amd64         | 1         | 2.78%   |
| 4.19.0-20-amd64        | 1         | 2.78%   |
| 4.19.0-17-686-pae      | 1         | 2.78%   |
| 4.19.0-17-686          | 1         | 2.78%   |
| 4.19.0-16-amd64        | 1         | 2.78%   |
| 4.19.0-16-686          | 1         | 2.78%   |
| 4.19.0-14-amd64        | 1         | 2.78%   |
| 4.19.0-13-amd64        | 1         | 2.78%   |
| 4.19.0-12-amd64        | 1         | 2.78%   |
| 4.19.0-10-amd64        | 1         | 2.78%   |
| 4.19.0-0.bpo.5-686-pae | 1         | 2.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 15        | 41.67%  |
| 4.19.0  | 15        | 41.67%  |
| 4.9.0   | 4         | 11.11%  |
| 5.9.0   | 1         | 2.78%   |
| 5.6.0   | 1         | 2.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 15        | 41.67%  |
| 4.19    | 15        | 41.67%  |
| 4.9     | 4         | 11.11%  |
| 5.9     | 1         | 2.78%   |
| 5.6     | 1         | 2.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 22        | 61.11%  |
| i686   | 14        | 38.89%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Trinity | 18        | 50%     |
| KDE5    | 17        | 47.22%  |
| KDE     | 1         | 2.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 35        | 97.22%  |
| Tty  | 1         | 2.78%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| TDM  | 18        | 50%     |
| SDDM | 18        | 50%     |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 14        | 38.89%  |
| Unknown | 3         | 8.33%   |
| fr_FR   | 2         | 5.56%   |
| es_ES   | 2         | 5.56%   |
| en_GB   | 2         | 5.56%   |
| de_DE   | 2         | 5.56%   |
| sv_SE   | 1         | 2.78%   |
| sl_SI   | 1         | 2.78%   |
| ru_RU   | 1         | 2.78%   |
| pt_BR   | 1         | 2.78%   |
| pl_PL   | 1         | 2.78%   |
| it_IT   | 1         | 2.78%   |
| es_VE   | 1         | 2.78%   |
| es_AR   | 1         | 2.78%   |
| en_ZA   | 1         | 2.78%   |
| en_SG   | 1         | 2.78%   |
| C       | 1         | 2.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 22        | 61.11%  |
| EFI  | 14        | 38.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 33        | 91.67%  |
| Overlay | 3         | 8.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 20        | 55.56%  |
| GPT     | 15        | 41.67%  |
| Unknown | 1         | 2.78%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 30        | 83.33%  |
| Yes       | 6         | 16.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 21        | 58.33%  |
| Yes       | 15        | 41.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 7         | 19.44%  |
| ASUSTek Computer            | 4         | 11.11%  |
| Toshiba                     | 3         | 8.33%   |
| MSI                         | 3         | 8.33%   |
| TrekStor                    | 2         | 5.56%   |
| Lenovo                      | 2         | 5.56%   |
| ASRock                      | 2         | 5.56%   |
| Visual Land                 | 1         | 2.78%   |
| TECO Electric and Machinery | 1         | 2.78%   |
| Qilive                      | 1         | 2.78%   |
| Phoenix/SiS                 | 1         | 2.78%   |
| Philco                      | 1         | 2.78%   |
| Packard Bell                | 1         | 2.78%   |
| Medion                      | 1         | 2.78%   |
| JVC                         | 1         | 2.78%   |
| Gigabyte Technology         | 1         | 2.78%   |
| Compaq                      | 1         | 2.78%   |
| Chuwi                       | 1         | 2.78%   |
| AMI                         | 1         | 2.78%   |
| Acer                        | 1         | 2.78%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| TrekStor SurfTab wintron 7.0           | 2         | 5.56%   |
| Toshiba Satellite C660                 | 2         | 5.56%   |
| Visual Land Premier 10                 | 1         | 2.78%   |
| Toshiba Satellite Pro L500             | 1         | 2.78%   |
| TECO Electric and Machinery FUTRO S400 | 1         | 2.78%   |
| Qilive QW19141AMSP                     | 1         | 2.78%   |
| Phoenix/SiS M720SR                     | 1         | 2.78%   |
| Philco 14I                             | 1         | 2.78%   |
| Packard Bell EasyNote LM81             | 1         | 2.78%   |
| MSI U210                               | 1         | 2.78%   |
| MSI MS-7C56                            | 1         | 2.78%   |
| MSI MS-7597                            | 1         | 2.78%   |
| Lenovo ThinkPad 11e 20DAS0PS00         | 1         | 2.78%   |
| Lenovo IdeaPad 330-15IGM 81D1          | 1         | 2.78%   |
| JVC J3N                                | 1         | 2.78%   |
| HP ProBook 6550b                       | 1         | 2.78%   |
| HP ProBook 450 G2                      | 1         | 2.78%   |
| HP Presario CQ56                       | 1         | 2.78%   |
| HP OmniBook PC                         | 1         | 2.78%   |
| HP Laptop 15s-fq2xxx                   | 1         | 2.78%   |
| HP 250 G5 Notebook PC                  | 1         | 2.78%   |
| HP 2000                                | 1         | 2.78%   |
| Gigabyte XP-M5S661GX                   | 1         | 2.78%   |
| Compaq Evo D510 SFF                    | 1         | 2.78%   |
| Chuwi GemiBook Pro                     | 1         | 2.78%   |
| ASUS X540YA                            | 1         | 2.78%   |
| ASUS T12Eg                             | 1         | 2.78%   |
| ASUS A6U                               | 1         | 2.78%   |
| ASUS A6JC                              | 1         | 2.78%   |
| ASRock H61M-HVS                        | 1         | 2.78%   |
| ASRock G41M-VS3                        | 1         | 2.78%   |
| AMI Intel                              | 1         | 2.78%   |
| Acer AO751h                            | 1         | 2.78%   |
| Unknown                                | 1         | 2.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Toshiba Satellite                 | 3         | 8.33%   |
| TrekStor SurfTab                  | 2         | 5.56%   |
| HP ProBook                        | 2         | 5.56%   |
| Visual Land Premier               | 1         | 2.78%   |
| TECO Electric and Machinery FUTRO | 1         | 2.78%   |
| Qilive QW19141AMSP                | 1         | 2.78%   |
| Phoenix/SiS M720SR                | 1         | 2.78%   |
| Philco 14I                        | 1         | 2.78%   |
| Packard Bell EasyNote             | 1         | 2.78%   |
| MSI U210                          | 1         | 2.78%   |
| MSI MS-7C56                       | 1         | 2.78%   |
| MSI MS-7597                       | 1         | 2.78%   |
| Lenovo ThinkPad                   | 1         | 2.78%   |
| Lenovo IdeaPad                    | 1         | 2.78%   |
| JVC J3N                           | 1         | 2.78%   |
| HP Presario                       | 1         | 2.78%   |
| HP OmniBook                       | 1         | 2.78%   |
| HP Laptop                         | 1         | 2.78%   |
| HP 250                            | 1         | 2.78%   |
| HP 2000                           | 1         | 2.78%   |
| Gigabyte XP-M5S661GX              | 1         | 2.78%   |
| Compaq Evo                        | 1         | 2.78%   |
| Chuwi GemiBook                    | 1         | 2.78%   |
| ASUS X540YA                       | 1         | 2.78%   |
| ASUS T12Eg                        | 1         | 2.78%   |
| ASUS A6U                          | 1         | 2.78%   |
| ASUS A6JC                         | 1         | 2.78%   |
| ASRock H61M-HVS                   | 1         | 2.78%   |
| ASRock G41M-VS3                   | 1         | 2.78%   |
| AMI Intel                         | 1         | 2.78%   |
| Acer AO751h                       | 1         | 2.78%   |
| Unknown                           | 1         | 2.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2010    | 6         | 16.67%  |
| 2020    | 4         | 11.11%  |
| 2015    | 3         | 8.33%   |
| 2011    | 3         | 8.33%   |
| 2009    | 3         | 8.33%   |
| 2016    | 2         | 5.56%   |
| 2014    | 2         | 5.56%   |
| 2005    | 2         | 5.56%   |
| Unknown | 2         | 5.56%   |
| 2019    | 1         | 2.78%   |
| 2018    | 1         | 2.78%   |
| 2017    | 1         | 2.78%   |
| 2012    | 1         | 2.78%   |
| 2008    | 1         | 2.78%   |
| 2007    | 1         | 2.78%   |
| 2006    | 1         | 2.78%   |
| 2004    | 1         | 2.78%   |
| 2002    | 1         | 2.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 27        | 75%     |
| Desktop  | 7         | 19.44%  |
| Tablet   | 2         | 5.56%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 34        | 94.44%  |
| Enabled  | 2         | 5.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 36        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 9         | 25%     |
| 1.01-2.0    | 6         | 16.67%  |
| 0.51-1.0    | 6         | 16.67%  |
| 4.01-8.0    | 5         | 13.89%  |
| 2.01-3.0    | 5         | 13.89%  |
| 16.01-24.0  | 2         | 5.56%   |
| 0.01-0.5    | 2         | 5.56%   |
| 64.01-256.0 | 1         | 2.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 13        | 36.11%  |
| 0.51-1.0  | 11        | 30.56%  |
| 2.01-3.0  | 5         | 13.89%  |
| 0.01-0.5  | 5         | 13.89%  |
| 3.01-4.0  | 1         | 2.78%   |
| 8.01-16.0 | 1         | 2.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 26        | 72.22%  |
| 2      | 6         | 16.67%  |
| 3      | 4         | 11.11%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 50%     |
| No        | 18        | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 88.89%  |
| No        | 4         | 11.11%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 69.44%  |
| No        | 11        | 30.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 22        | 61.11%  |
| Yes       | 14        | 38.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 4         | 11.11%  |
| Kenya        | 3         | 8.33%   |
| UK           | 2         | 5.56%   |
| Switzerland  | 2         | 5.56%   |
| Spain        | 2         | 5.56%   |
| Romania      | 2         | 5.56%   |
| Poland       | 2         | 5.56%   |
| Italy        | 2         | 5.56%   |
| Germany      | 2         | 5.56%   |
| France       | 2         | 5.56%   |
| Brazil       | 2         | 5.56%   |
| Venezuela    | 1         | 2.78%   |
| Sweden       | 1         | 2.78%   |
| South Africa | 1         | 2.78%   |
| Slovenia     | 1         | 2.78%   |
| Singapore    | 1         | 2.78%   |
| Saudi Arabia | 1         | 2.78%   |
| Russia       | 1         | 2.78%   |
| Qatar        | 1         | 2.78%   |
| Netherlands  | 1         | 2.78%   |
| Belarus      | 1         | 2.78%   |
| Argentina    | 1         | 2.78%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Nairobi               | 3         | 8.33%   |
| Zurich                | 2         | 5.56%   |
| Swindon               | 2         | 5.56%   |
| Rostock               | 2         | 5.56%   |
| Drobeta-Turnu Severin | 2         | 5.56%   |
| Tranas                | 1         | 2.78%   |
| The Hague             | 1         | 2.78%   |
| Tellico Plains        | 1         | 2.78%   |
| Sosnowiec             | 1         | 2.78%   |
| Singapore             | 1         | 2.78%   |
| Salsomaggiore Terme   | 1         | 2.78%   |
| Puerto Cumarebo       | 1         | 2.78%   |
| Posadas               | 1         | 2.78%   |
| Moscow                | 1         | 2.78%   |
| Moirans               | 1         | 2.78%   |
| Mogilev               | 1         | 2.78%   |
| Mesa                  | 1         | 2.78%   |
| Londrina              | 1         | 2.78%   |
| Ljubljana             | 1         | 2.78%   |
| Las Vegas             | 1         | 2.78%   |
| Klaudyn               | 1         | 2.78%   |
| Johannesburg          | 1         | 2.78%   |
| Guarulhos             | 1         | 2.78%   |
| Grand Junction        | 1         | 2.78%   |
| Gijón                | 1         | 2.78%   |
| Doha                  | 1         | 2.78%   |
| Dammam                | 1         | 2.78%   |
| Calvecchia            | 1         | 2.78%   |
| Boulogne-sur-Mer      | 1         | 2.78%   |
| Barcelona             | 1         | 2.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 7      | 16.28%  |
| Unknown             | 6         | 6      | 13.95%  |
| Seagate             | 6         | 7      | 13.95%  |
| Samsung Electronics | 4         | 4      | 9.3%    |
| SanDisk             | 3         | 3      | 6.98%   |
| Hitachi             | 3         | 3      | 6.98%   |
| China               | 3         | 4      | 6.98%   |
| KESU                | 2         | 2      | 4.65%   |
| HGST                | 2         | 2      | 4.65%   |
| Unknown (CF)        | 1         | 1      | 2.33%   |
| Toshiba             | 1         | 1      | 2.33%   |
| MAXTOR              | 1         | 1      | 2.33%   |
| Kingston            | 1         | 1      | 2.33%   |
| Fujitsu             | 1         | 1      | 2.33%   |
| A-DATA Technology   | 1         | 1      | 2.33%   |
| Unknown             | 1         | 1      | 2.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown NCard  16GB                  | 2         | 4.44%   |
| Samsung SSD 850 EVO 250GB            | 2         | 4.44%   |
| KESU USB 3.1 128GB                   | 2         | 4.44%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 2.22%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 2.22%   |
| WDC WD400BD-23JMC0 40GB              | 1         | 2.22%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 2.22%   |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 2.22%   |
| WDC WD1600AAJS-00L7A0 160GB          | 1         | 2.22%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 2.22%   |
| Unknown USDU1  32GB                  | 1         | 2.22%   |
| Unknown SLD64G  64GB                 | 1         | 2.22%   |
| Unknown SD/MMC/MS PRO 999GB          | 1         | 2.22%   |
| Unknown 064G38  64GB                 | 1         | 2.22%   |
| Unknown (CF) Card 8GB SSD            | 1         | 2.22%   |
| Toshiba MK8025GAS 80GB               | 1         | 2.22%   |
| Seagate ST9120822AS 120GB            | 1         | 2.22%   |
| Seagate ST8000DM004-2CX188 8TB       | 1         | 2.22%   |
| Seagate ST3160815AS 160GB            | 1         | 2.22%   |
| Seagate ST3160812AS 160GB            | 1         | 2.22%   |
| Seagate ST310211A 10GB               | 1         | 2.22%   |
| Seagate ST1000DM003-1ER162 1TB       | 1         | 2.22%   |
| Seagate Backup+ SL 1TB               | 1         | 2.22%   |
| SanDisk SDSSDA120G 120GB             | 1         | 2.22%   |
| SanDisk SDCFX-032G SSD               | 1         | 2.22%   |
| SanDisk SD8SN8U1T001122 1024GB SSD   | 1         | 2.22%   |
| Samsung HD081GJ 80GB                 | 1         | 2.22%   |
| Samsung AWMB3R  16GB                 | 1         | 2.22%   |
| MAXTOR 6Y080L0 82GB                  | 1         | 2.22%   |
| Kingston SV300S37A60G 64GB SSD       | 1         | 2.22%   |
| Hitachi HTS545032B9A300 320GB        | 1         | 2.22%   |
| Hitachi HTS543225L9SA00 250GB        | 1         | 2.22%   |
| Hitachi DK23CA-20 20GB               | 1         | 2.22%   |
| HGST HTS725050A7E630 500GB           | 1         | 2.22%   |
| HGST HTS541075A9E680 752GB           | 1         | 2.22%   |
| Fujitsu MHY2080BH 80GB               | 1         | 2.22%   |
| China SSD128GBS800                   | 1         | 2.22%   |
| China SSD 256GB                      | 1         | 2.22%   |
| China SSD 120GB                      | 1         | 2.22%   |
| China SATA SSD 240GB                 | 1         | 2.22%   |
| A-DATA SU630 240GB SSD               | 1         | 2.22%   |
| Unknown                              | 1         | 2.22%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 25%     |
| Seagate             | 5         | 6      | 25%     |
| Hitachi             | 3         | 3      | 15%     |
| HGST                | 2         | 2      | 10%     |
| Unknown             | 1         | 1      | 5%      |
| Toshiba             | 1         | 1      | 5%      |
| Samsung Electronics | 1         | 1      | 5%      |
| MAXTOR              | 1         | 1      | 5%      |
| Fujitsu             | 1         | 1      | 5%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 3         | 3      | 23.08%  |
| China               | 3         | 4      | 23.08%  |
| Samsung Electronics | 2         | 2      | 15.38%  |
| WDC                 | 1         | 1      | 7.69%   |
| Unknown (CF)        | 1         | 1      | 7.69%   |
| Kingston            | 1         | 1      | 7.69%   |
| A-DATA Technology   | 1         | 1      | 7.69%   |
| Unknown             | 1         | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 17        | 21     | 43.59%  |
| SSD     | 12        | 14     | 30.77%  |
| MMC     | 6         | 6      | 15.38%  |
| Unknown | 3         | 3      | 7.69%   |
| NVMe    | 1         | 1      | 2.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 27        | 34     | 71.05%  |
| MMC  | 6         | 6      | 15.79%  |
| SAS  | 4         | 4      | 10.53%  |
| NVMe | 1         | 1      | 2.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 25        | 30     | 83.33%  |
| 0.51-1.0   | 3         | 3      | 10%     |
| 1.01-2.0   | 1         | 1      | 3.33%   |
| 4.01-10.0  | 1         | 1      | 3.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 9         | 25%     |
| 51-100         | 8         | 22.22%  |
| 21-50          | 5         | 13.89%  |
| 101-250        | 5         | 13.89%  |
| 251-500        | 3         | 8.33%   |
| 1001-2000      | 2         | 5.56%   |
| 501-1000       | 2         | 5.56%   |
| More than 3000 | 1         | 2.78%   |
| Unknown        | 1         | 2.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 25        | 69.44%  |
| 21-50          | 5         | 13.89%  |
| 251-500        | 2         | 5.56%   |
| 501-1000       | 2         | 5.56%   |
| More than 3000 | 1         | 2.78%   |
| Unknown        | 1         | 2.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 18        | 24     | 47.37%  |
| Detected | 10        | 11     | 26.32%  |
| Malfunc  | 10        | 10     | 26.32%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 20        | 60.61%  |
| AMD                              | 7         | 21.21%  |
| Silicon Integrated Systems [SiS] | 4         | 12.12%  |
| Sandisk                          | 1         | 3.03%   |
| Nvidia                           | 1         | 3.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 4         | 10%     |
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 10%     |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 7.5%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 5%      |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 5%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 5%      |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 2.5%    |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS]        | 1         | 2.5%    |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1         | 2.5%    |
| Nvidia MCP61 SATA Controller                                                     | 1         | 2.5%    |
| Nvidia MCP61 IDE                                                                 | 1         | 2.5%    |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 2.5%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 1         | 2.5%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 2.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 2.5%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 2.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 2.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 2.5%    |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 1         | 2.5%    |
| Intel 82801DB (ICH4) IDE Controller                                              | 1         | 2.5%    |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 1         | 2.5%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1         | 2.5%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 2.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 2.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 2.5%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 2.5%    |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 2.5%    |
| AMD 500 Series Chipset SATA Controller                                           | 1         | 2.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 19        | 54.29%  |
| IDE  | 13        | 37.14%  |
| RAID | 2         | 5.71%   |
| NVMe | 1         | 2.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 26        | 72.22%  |
| AMD    | 10        | 27.78%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom CPU Z3735G @ 1.33GHz               | 3         | 8.33%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 5.56%   |
| Intel Pentium M processor 1000MHz             | 1         | 2.78%   |
| Intel Pentium III (Coppermine)                | 1         | 2.78%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 2.78%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 1         | 2.78%   |
| Intel Pentium 4 CPU 3.00GHz                   | 1         | 2.78%   |
| Intel Pentium 4 CPU 2.00GHz                   | 1         | 2.78%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 1         | 2.78%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 2.78%   |
| Intel Core i5 CPU M 450 @ 2.40GHz             | 1         | 2.78%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 1         | 2.78%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz          | 1         | 2.78%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz          | 1         | 2.78%   |
| Intel Core 2 CPU T5500 @ 1.66GHz              | 1         | 2.78%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 2.78%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 2.78%   |
| Intel Celeron J4115 CPU @ 1.80GHz             | 1         | 2.78%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 2.78%   |
| Intel Celeron CPU N2940 @ 1.83GHz             | 1         | 2.78%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 1         | 2.78%   |
| Intel Atom CPU Z520 @ 1.33GHz                 | 1         | 2.78%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 2.78%   |
| AMD V120 Processor                            | 1         | 2.78%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 1         | 2.78%   |
| AMD Mobile Sempron Processor 3000+            | 1         | 2.78%   |
| AMD E-300 APU with Radeon HD Graphics         | 1         | 2.78%   |
| AMD C-70 APU with Radeon HD Graphics          | 1         | 2.78%   |
| AMD Athlon Processor                          | 1         | 2.78%   |
| AMD Athlon Neo Processor MV-40                | 1         | 2.78%   |
| AMD Athlon II X2 250 Processor                | 1         | 2.78%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 1         | 2.78%   |
| AMD A4-9120e RADEON R3, 4 COMPUTE CORES 2C+2G | 1         | 2.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 5         | 13.89%  |
| Intel Atom              | 5         | 13.89%  |
| Intel Core 2 Duo        | 3         | 8.33%   |
| Intel Pentium Dual-Core | 2         | 5.56%   |
| Intel Pentium 4         | 2         | 5.56%   |
| Intel Core i5           | 2         | 5.56%   |
| Intel Core i3           | 2         | 5.56%   |
| Other                   | 1         | 2.78%   |
| Intel Pentium M         | 1         | 2.78%   |
| Intel Pentium III       | 1         | 2.78%   |
| Intel Core i7           | 1         | 2.78%   |
| Intel Core 2            | 1         | 2.78%   |
| AMD V120                | 1         | 2.78%   |
| AMD Ryzen 7             | 1         | 2.78%   |
| AMD Mobile Sempron      | 1         | 2.78%   |
| AMD E                   | 1         | 2.78%   |
| AMD C-70                | 1         | 2.78%   |
| AMD Athlon Neo          | 1         | 2.78%   |
| AMD Athlon II X2        | 1         | 2.78%   |
| AMD Athlon              | 1         | 2.78%   |
| AMD A8                  | 1         | 2.78%   |
| AMD A4                  | 1         | 2.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 16        | 44.44%  |
| 4      | 10        | 27.78%  |
| 1      | 9         | 25%     |
| 8      | 1         | 2.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 36        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 27        | 75%     |
| 2      | 9         | 25%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 30        | 83.33%  |
| 32-bit         | 6         | 16.67%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 5         | 13.89%  |
| 0x30678    | 4         | 11.11%  |
| 0x206a7    | 3         | 8.33%   |
| 0x1067a    | 3         | 8.33%   |
| 0x706a1    | 2         | 5.56%   |
| 0x6fd      | 2         | 5.56%   |
| 0x010000c8 | 2         | 5.56%   |
| 0xf49      | 1         | 2.78%   |
| 0xf27      | 1         | 2.78%   |
| 0x806c1    | 1         | 2.78%   |
| 0x706a8    | 1         | 2.78%   |
| 0x6f6      | 1         | 2.78%   |
| 0x695      | 1         | 2.78%   |
| 0x68a      | 1         | 2.78%   |
| 0x406c4    | 1         | 2.78%   |
| 0x40651    | 1         | 2.78%   |
| 0x20655    | 1         | 2.78%   |
| 0x0800820d | 1         | 2.78%   |
| 0x07030106 | 1         | 2.78%   |
| 0x06006705 | 1         | 2.78%   |
| 0x05000119 | 1         | 2.78%   |
| 0x0500010d | 1         | 2.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 6         | 16.67%  |
| SandyBridge   | 3         | 8.33%   |
| Penryn        | 3         | 8.33%   |
| Goldmont plus | 3         | 8.33%   |
| Core          | 3         | 8.33%   |
| P6            | 2         | 5.56%   |
| NetBurst      | 2         | 5.56%   |
| K8 Hammer     | 2         | 5.56%   |
| K10           | 2         | 5.56%   |
| Bobcat        | 2         | 5.56%   |
| Zen+          | 1         | 2.78%   |
| Westmere      | 1         | 2.78%   |
| TigerLake     | 1         | 2.78%   |
| Puma          | 1         | 2.78%   |
| K6            | 1         | 2.78%   |
| Haswell       | 1         | 2.78%   |
| Excavator     | 1         | 2.78%   |
| Bonnell       | 1         | 2.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 19        | 51.35%  |
| AMD                              | 9         | 24.32%  |
| Silicon Integrated Systems [SiS] | 4         | 10.81%  |
| Nvidia                           | 4         | 10.81%  |
| S3 Graphics                      | 1         | 2.7%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 4         | 10.53%  |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 3         | 7.89%   |
| Intel GeminiLake [UHD Graphics 600]                                                        | 3         | 7.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 2         | 5.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 2         | 5.26%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 1         | 2.63%   |
| S3 Graphics 86C270-294 [SavageIX-MV]                                                       | 1         | 2.63%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                         | 1         | 2.63%   |
| Nvidia GM206 [GeForce GTX 960]                                                             | 1         | 2.63%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                              | 1         | 2.63%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                    | 1         | 2.63%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 1         | 2.63%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 1         | 2.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 1         | 2.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 1         | 2.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 1         | 2.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 1         | 2.63%   |
| Intel 82852/855GM Integrated Graphics Device                                               | 1         | 2.63%   |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device                         | 1         | 2.63%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 1         | 2.63%   |
| AMD Wrestler [Radeon HD 7290]                                                              | 1         | 2.63%   |
| AMD Wrestler [Radeon HD 6310]                                                              | 1         | 2.63%   |
| AMD Topaz PRO [Radeon R5 M255]                                                             | 1         | 2.63%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 1         | 2.63%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                          | 1         | 2.63%   |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                               | 1         | 2.63%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                  | 1         | 2.63%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                  | 1         | 2.63%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                        | 1         | 2.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 17        | 47.22%  |
| 1 x AMD         | 8         | 22.22%  |
| 1 x SiS         | 4         | 11.11%  |
| 1 x Nvidia      | 4         | 11.11%  |
| Other           | 1         | 2.78%   |
| 1 x S3 Graphics | 1         | 2.78%   |
| Intel + AMD     | 1         | 2.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 28        | 77.78%  |
| Unknown     | 5         | 13.89%  |
| Proprietary | 3         | 8.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 61.11%  |
| 0.01-0.5   | 10        | 27.78%  |
| 1.01-2.0   | 3         | 8.33%   |
| 3.01-4.0   | 1         | 2.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 19.35%  |
| Chimei Innolux      | 6         | 19.35%  |
| AU Optronics        | 6         | 19.35%  |
| LG Display          | 3         | 9.68%   |
| Hewlett-Packard     | 2         | 6.45%   |
| ViewSonic           | 1         | 3.23%   |
| VIE                 | 1         | 3.23%   |
| Orion               | 1         | 3.23%   |
| HannStar            | 1         | 3.23%   |
| Goldstar            | 1         | 3.23%   |
| Dell                | 1         | 3.23%   |
| CPT                 | 1         | 3.23%   |
| BOE                 | 1         | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 6.45%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch               | 1         | 3.23%   |
| VIE S20W VIE2080 1600x900 440x250mm 19.9-inch                           | 1         | 3.23%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 340x190mm 15.3-inch       | 1         | 3.23%   |
| Samsung Electronics S24B20/S24B30 SAM09ED 1920x1080 521x293mm 23.5-inch | 1         | 3.23%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch     | 1         | 3.23%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 1         | 3.23%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch    | 1         | 3.23%   |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 1020x570mm 46.0-inch  | 1         | 3.23%   |
| Orion ORION ORN120A 1920x540                                            | 1         | 3.23%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch             | 1         | 3.23%   |
| Hewlett-Packard Z24i HWP3100 1920x1200 518x324mm 24.1-inch              | 1         | 3.23%   |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch               | 1         | 3.23%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                | 1         | 3.23%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                    | 1         | 3.23%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                        | 1         | 3.23%   |
| CPT LCD Monitor CPT13B1 1280x800 330x210mm 15.4-inch                    | 1         | 3.23%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch        | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch         | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch         | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch         | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 1         | 3.23%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                    | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch          | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 256x144mm 11.6-inch          | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch           | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch           | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch           | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO12EC 1366x768 344x193mm 15.5-inch           | 1         | 3.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 12        | 38.71%  |
| 1920x1080 (FHD)    | 7         | 22.58%  |
| 1600x900 (HD+)     | 5         | 16.13%  |
| 1280x800 (WXGA)    | 2         | 6.45%   |
| 3840x2160 (4K)     | 1         | 3.23%   |
| 2160x1440          | 1         | 3.23%   |
| 1920x540           | 1         | 3.23%   |
| 1920x1200 (WUXGA)  | 1         | 3.23%   |
| 1680x1050 (WSXGA+) | 1         | 3.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 13        | 41.94%  |
| 23      | 2         | 6.45%   |
| 13      | 2         | 6.45%   |
| 11      | 2         | 6.45%   |
| 46      | 1         | 3.23%   |
| 40      | 1         | 3.23%   |
| 31      | 1         | 3.23%   |
| 24      | 1         | 3.23%   |
| 22      | 1         | 3.23%   |
| 20      | 1         | 3.23%   |
| 19      | 1         | 3.23%   |
| 18      | 1         | 3.23%   |
| 17      | 1         | 3.23%   |
| 14      | 1         | 3.23%   |
| 12      | 1         | 3.23%   |
| Unknown | 1         | 3.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 15        | 48.39%  |
| 201-300     | 4         | 12.9%   |
| 501-600     | 3         | 9.68%   |
| 401-500     | 3         | 9.68%   |
| 351-400     | 2         | 6.45%   |
| 801-900     | 1         | 3.23%   |
| 601-700     | 1         | 3.23%   |
| 1001-1500   | 1         | 3.23%   |
| Unknown     | 1         | 3.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 22        | 78.57%  |
| 16/10 | 4         | 14.29%  |
| 32/9  | 1         | 3.57%   |
| 3/2   | 1         | 3.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 13        | 41.94%  |
| 81-90          | 3         | 9.68%   |
| 201-250        | 3         | 9.68%   |
| 51-60          | 2         | 6.45%   |
| 151-200        | 2         | 6.45%   |
| 501-1000       | 2         | 6.45%   |
| 61-70          | 1         | 3.23%   |
| 351-500        | 1         | 3.23%   |
| 251-300        | 1         | 3.23%   |
| 141-150        | 1         | 3.23%   |
| 121-130        | 1         | 3.23%   |
| Unknown        | 1         | 3.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 13        | 41.94%  |
| 51-100  | 9         | 29.03%  |
| 121-160 | 5         | 16.13%  |
| 161-240 | 2         | 6.45%   |
| 1-50    | 1         | 3.23%   |
| Unknown | 1         | 3.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 31        | 86.11%  |
| 2     | 2         | 5.56%   |
| 0     | 2         | 5.56%   |
| 3     | 1         | 2.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 25        | 43.1%   |
| Qualcomm Atheros                 | 11        | 18.97%  |
| Intel                            | 8         | 13.79%  |
| Silicon Integrated Systems [SiS] | 3         | 5.17%   |
| Samsung Electronics              | 2         | 3.45%   |
| Broadcom                         | 2         | 3.45%   |
| Xiaomi                           | 1         | 1.72%   |
| Motorola PCS                     | 1         | 1.72%   |
| LG Electronics                   | 1         | 1.72%   |
| JMicron Technology               | 1         | 1.72%   |
| IBM                              | 1         | 1.72%   |
| Broadcom Limited                 | 1         | 1.72%   |
| Accton Technology                | 1         | 1.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 8         | 12.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 8         | 12.9%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 3         | 4.84%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 3         | 4.84%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                 | 2         | 3.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 2         | 3.23%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                  | 2         | 3.23%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                       | 2         | 3.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 2         | 3.23%   |
| Xiaomi Mi/Redmi series (RNDIS)                                              | 1         | 1.61%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                   | 1         | 1.61%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                     | 1         | 1.61%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter               | 1         | 1.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 1.61%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                  | 1         | 1.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 1.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 1.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                    | 1         | 1.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 1.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1         | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1         | 1.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 1.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                  | 1         | 1.61%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]         | 1         | 1.61%   |
| Motorola PCS moto g(6) play                                                 | 1         | 1.61%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                         | 1         | 1.61%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                      | 1         | 1.61%   |
| Intel Wireless 3165                                                         | 1         | 1.61%   |
| Intel Wi-Fi 6 AX200                                                         | 1         | 1.61%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                    | 1         | 1.61%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 1.61%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller           | 1         | 1.61%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                          | 1         | 1.61%   |
| Intel 82577LC Gigabit Network Connection                                    | 1         | 1.61%   |
| IBM Winnipeg PCI-X Host Bridge                                              | 1         | 1.61%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                             | 1         | 1.61%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1         | 1.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 1.61%   |
| Accton EN-1216 Ethernet Adapter                                             | 1         | 1.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 11        | 44%     |
| Realtek Semiconductor | 6         | 24%     |
| Intel                 | 6         | 24%     |
| Broadcom Limited      | 1         | 4%      |
| Broadcom              | 1         | 4%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 3         | 12%     |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 3         | 12%     |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 2         | 8%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 2         | 8%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 4%      |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                  | 1         | 4%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 4%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 4%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 4%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1         | 4%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1         | 4%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 4%      |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]         | 1         | 4%      |
| Intel Wireless 3165                                                         | 1         | 4%      |
| Intel Wi-Fi 6 AX200                                                         | 1         | 4%      |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                    | 1         | 4%      |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 4%      |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1         | 4%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 4%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 21        | 61.76%  |
| Silicon Integrated Systems [SiS] | 2         | 5.88%   |
| Samsung Electronics              | 2         | 5.88%   |
| Intel                            | 2         | 5.88%   |
| Xiaomi                           | 1         | 2.94%   |
| Qualcomm Atheros                 | 1         | 2.94%   |
| Motorola PCS                     | 1         | 2.94%   |
| LG Electronics                   | 1         | 2.94%   |
| JMicron Technology               | 1         | 2.94%   |
| Broadcom                         | 1         | 2.94%   |
| Accton Technology                | 1         | 2.94%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 23.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 23.53%  |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 5.88%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 5.88%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 5.88%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.94%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 2.94%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 2.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.94%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.94%   |
| Motorola PCS moto g(6) play                                       | 1         | 2.94%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)               | 1         | 2.94%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.94%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                | 1         | 2.94%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 2.94%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.94%   |
| Accton EN-1216 Ethernet Adapter                                   | 1         | 2.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 32        | 53.33%  |
| WiFi     | 25        | 41.67%  |
| Modem    | 2         | 3.33%   |
| Unknown  | 1         | 1.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 17        | 50%     |
| Ethernet | 17        | 50%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 20        | 55.56%  |
| 1     | 12        | 33.33%  |
| 0     | 4         | 11.11%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 34        | 94.44%  |
| Yes  | 2         | 5.56%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros Communications | 4         | 28.57%  |
| Realtek Semiconductor           | 3         | 21.43%  |
| Intel                           | 3         | 21.43%  |
| Toshiba                         | 1         | 7.14%   |
| Hewlett-Packard                 | 1         | 7.14%   |
| Cambridge Silicon Radio         | 1         | 7.14%   |
| ASUSTek Computer                | 1         | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 3         | 21.43%  |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 21.43%  |
| Toshiba Askey for                                   | 1         | 7.14%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 7.14%   |
| Intel Bluetooth wireless interface                  | 1         | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 7.14%   |
| Intel AX200 Bluetooth                               | 1         | 7.14%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 7.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 7.14%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 19        | 54.29%  |
| AMD                              | 9         | 25.71%  |
| Silicon Integrated Systems [SiS] | 3         | 8.57%   |
| Nvidia                           | 3         | 8.57%   |
| ESS Technology                   | 1         | 2.86%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 7.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 7.14%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 7.14%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 2         | 4.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 4.76%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 4.76%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 4.76%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 4.76%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 4.76%   |
| AMD FCH Azalia Controller                                                                         | 2         | 4.76%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 2.38%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 2.38%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 2.38%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 2.38%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 2.38%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 2.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 2.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 2.38%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2.38%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 2.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 2.38%   |
| ESS Technology ES1988 Allegro-1                                                                   | 1         | 2.38%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 2.38%   |
| AMD RS690 HDMI Audio [Radeon Xpress 1200 Series]                                                  | 1         | 2.38%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 2.38%   |
| AMD High Definition Audio Controller                                                              | 1         | 2.38%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 2.38%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 2.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 15        | 42.86%  |
| Samsung Electronics | 6         | 17.14%  |
| SK Hynix            | 4         | 11.43%  |
| Unknown (ABCD)      | 2         | 5.71%   |
| Kingston            | 2         | 5.71%   |
| Transcend           | 1         | 2.86%   |
| Toshiba             | 1         | 2.86%   |
| Teikon              | 1         | 2.86%   |
| Team                | 1         | 2.86%   |
| Elpida              | 1         | 2.86%   |
| A-DATA Technology   | 1         | 2.86%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                             | 3         | 7.89%   |
| Unknown RAM Module 1024MB DIMM DDR3 1333MT/s                   | 2         | 5.26%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s | 2         | 5.26%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 2         | 5.26%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 5.26%   |
| Unknown RAM Module 512MB SODIMM SDRAM                          | 1         | 2.63%   |
| Unknown RAM Module 512MB DIMM 400MT/s                          | 1         | 2.63%   |
| Unknown RAM Module 512MB DIMM                                  | 1         | 2.63%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                 | 1         | 2.63%   |
| Unknown RAM Module 256MB SODIMM SDRAM                          | 1         | 2.63%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 1         | 2.63%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1066MT/s                  | 1         | 2.63%   |
| Unknown RAM Module 2048MB DIMM SDRAM                           | 1         | 2.63%   |
| Unknown RAM Module 1GB SODIMM DRAM                             | 1         | 2.63%   |
| Unknown RAM Module 1GB SODIMM DDR 266MT/s                      | 1         | 2.63%   |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                      | 1         | 2.63%   |
| Transcend RAM Module 1GB DIMM SDRAM 266MT/s                    | 1         | 2.63%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s             | 1         | 2.63%   |
| Toshiba RAM 64T128020EDL2.5C2 4GB SODIMM 1066MT/s              | 1         | 2.63%   |
| Teikon RAM TMT41GU6AFR8C-PBHJ 8GB DIMM DDR3 1333MT/s           | 1         | 2.63%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s            | 1         | 2.63%   |
| SK Hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                | 1         | 2.63%   |
| SK Hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 800MT/s       | 1         | 2.63%   |
| SK Hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 2.63%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2400MT/s      | 1         | 2.63%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s          | 1         | 2.63%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 2.63%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 1         | 2.63%   |
| Kingston RAM HP32D4S2S1ME-4 4GB SODIMM DDR4 3200MT/s           | 1         | 2.63%   |
| Kingston RAM 99U5428-041.A01G 4GB SODIMM DDR3 1067MT/s         | 1         | 2.63%   |
| Elpida RAM EBJ10UE8BDS0-AE-F 1GB SODIMM DDR3 1067MT/s          | 1         | 2.63%   |
| A-DATA RAM AM1U16BC2P1-B1AH 2GB SODIMM DDR3 4199MT/s           | 1         | 2.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 13        | 38.24%  |
| SDRAM   | 6         | 17.65%  |
| DDR2    | 5         | 14.71%  |
| DDR4    | 4         | 11.76%  |
| LPDDR4  | 2         | 5.88%   |
| Unknown | 2         | 5.88%   |
| DRAM    | 1         | 2.94%   |
| DDR     | 1         | 2.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 24        | 70.59%  |
| DIMM   | 10        | 29.41%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 13        | 36.11%  |
| 2048  | 10        | 27.78%  |
| 1024  | 7         | 19.44%  |
| 512   | 3         | 8.33%   |
| 16384 | 1         | 2.78%   |
| 8192  | 1         | 2.78%   |
| 256   | 1         | 2.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 8         | 22.86%  |
| 1333    | 5         | 14.29%  |
| 1600    | 4         | 11.43%  |
| 2400    | 3         | 8.57%   |
| 1334    | 3         | 8.57%   |
| 1067    | 2         | 5.71%   |
| 1066    | 2         | 5.71%   |
| 266     | 2         | 5.71%   |
| 4199    | 1         | 2.86%   |
| 3600    | 1         | 2.86%   |
| 3266    | 1         | 2.86%   |
| 3200    | 1         | 2.86%   |
| 800     | 1         | 2.86%   |
| 400     | 1         | 2.86%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
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

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
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

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 28        | 77.78%  |
| 2     | 4         | 11.11%  |
| 1     | 4         | 11.11%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 6         | 50%     |
| Fingerprint reader       | 2         | 16.67%  |
| Network                  | 1         | 8.33%   |
| Flash memory             | 1         | 8.33%   |
| Communication controller | 1         | 8.33%   |
| Camera                   | 1         | 8.33%   |

