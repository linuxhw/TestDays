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

Total: 35

| Vendor        | Model                    | Probe                                                      | Date         |
|---------------|--------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T495 20NKS0PG00 | [ee35a21db4](https://linux-hardware.org/?probe=ee35a21db4) | Jun 30, 2022 |
| Sony          | VGN-P11Z_Q               | [e51be2b6a4](https://linux-hardware.org/?probe=e51be2b6a4) | Jun 16, 2022 |
| Toshiba       | Satellite M70            | [61617a3561](https://linux-hardware.org/?probe=61617a3561) | Jun 05, 2022 |
| HP            | 250 G5 Notebook PC       | [0e5792fc9f](https://linux-hardware.org/?probe=0e5792fc9f) | May 15, 2022 |
| ASUSTek       | A6U                      | [4a8ad00e5e](https://linux-hardware.org/?probe=4a8ad00e5e) | May 12, 2022 |
| Toshiba       | Satellite Pro L500       | [5b72ea9a47](https://linux-hardware.org/?probe=5b72ea9a47) | May 02, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1   | [8cdcd8d130](https://linux-hardware.org/?probe=8cdcd8d130) | Apr 08, 2022 |
| Acer          | AO751h                   | [23737182d1](https://linux-hardware.org/?probe=23737182d1) | Mar 21, 2022 |
| AMI           | Intel                    | [6d581b03a6](https://linux-hardware.org/?probe=6d581b03a6) | Mar 19, 2022 |
| ASUSTek       | X540YA                   | [0cd3840828](https://linux-hardware.org/?probe=0cd3840828) | Mar 14, 2022 |
| Visual Lan... | Premier 10               | [64450e11a3](https://linux-hardware.org/?probe=64450e11a3) | Feb 04, 2022 |
| HP            | Presario CQ56            | [8d03d80424](https://linux-hardware.org/?probe=8d03d80424) | Jan 14, 2022 |
| HP            | Presario CQ56            | [a0bc0364a8](https://linux-hardware.org/?probe=a0bc0364a8) | Jan 08, 2022 |
| MSI           | U210                     | [24eb05a4d9](https://linux-hardware.org/?probe=24eb05a4d9) | Dec 29, 2021 |
| Toshiba       | Satellite C660           | [b159811d48](https://linux-hardware.org/?probe=b159811d48) | Dec 12, 2021 |
| Toshiba       | Satellite C660           | [2197770fd0](https://linux-hardware.org/?probe=2197770fd0) | Dec 12, 2021 |
| ASUSTek       | T12Eg                    | [115e8b584f](https://linux-hardware.org/?probe=115e8b584f) | Dec 11, 2021 |
| Toshiba       | Satellite C660           | [64521297e2](https://linux-hardware.org/?probe=64521297e2) | Dec 07, 2021 |
| Toshiba       | Satellite C660           | [b6a5bb8982](https://linux-hardware.org/?probe=b6a5bb8982) | Dec 06, 2021 |
| Phoenix/Si... | M720SR                   | [f92c7e8c3e](https://linux-hardware.org/?probe=f92c7e8c3e) | Oct 09, 2021 |
| HP            | Laptop 15s-fq2xxx        | [cfa6202518](https://linux-hardware.org/?probe=cfa6202518) | Sep 14, 2021 |
| HP            | Laptop 15s-fq2xxx        | [726c3230ef](https://linux-hardware.org/?probe=726c3230ef) | Sep 14, 2021 |
| Chuwi         | GemiBook Pro             | [ebe8d67a10](https://linux-hardware.org/?probe=ebe8d67a10) | Sep 04, 2021 |
| HP            | ProBook 450 G2           | [dbba9b9771](https://linux-hardware.org/?probe=dbba9b9771) | Jul 30, 2021 |
| JVC           | J3N                      | [f8da57e850](https://linux-hardware.org/?probe=f8da57e850) | Jul 09, 2021 |
| HP            | ProBook 6550b            | [b192718656](https://linux-hardware.org/?probe=b192718656) | Mar 13, 2021 |
| HP            | 2000                     | [736561e497](https://linux-hardware.org/?probe=736561e497) | Mar 07, 2021 |
| ASUSTek       | A6JC                     | [b04f51dd1c](https://linux-hardware.org/?probe=b04f51dd1c) | Jan 29, 2021 |
| ASUSTek       | A6JC                     | [097dd7f151](https://linux-hardware.org/?probe=097dd7f151) | Jan 29, 2021 |
| Lenovo        | ThinkPad 11e 20DAS0PS00  | [2d618b7420](https://linux-hardware.org/?probe=2d618b7420) | Dec 14, 2020 |
| Packard Be... | EasyNote LM81            | [d6b0c23c18](https://linux-hardware.org/?probe=d6b0c23c18) | Nov 23, 2020 |
| Qilive        | QW19141AMSP              | [b8f3486ae1](https://linux-hardware.org/?probe=b8f3486ae1) | Aug 27, 2020 |
| HP            | OmniBook PC              | [5e33febbc1](https://linux-hardware.org/?probe=5e33febbc1) | Jul 10, 2020 |
| Medion        | Unknown                  | [6a06a14f6a](https://linux-hardware.org/?probe=6a06a14f6a) | May 07, 2020 |
| Philco        | 14I                      | [bf4c449b31](https://linux-hardware.org/?probe=bf4c449b31) | Apr 14, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Q4OS 4 | 17        | 56.67%  |
| Q4OS 3 | 10        | 33.33%  |
| Q4OS 2 | 3         | 10%     |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Q4OS | 30        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 4.19.0-17-amd64      | 4         | 13.33%  |
| 5.10.0-12-amd64      | 3         | 10%     |
| 5.10.0-8-amd64       | 2         | 6.67%   |
| 5.10.0-14-686-pae    | 2         | 6.67%   |
| 5.9.0-5-amd64        | 1         | 3.33%   |
| 5.6.0-1-amd64        | 1         | 3.33%   |
| 5.18.0-0.bpo.1-amd64 | 1         | 3.33%   |
| 5.10.0-9-amd64       | 1         | 3.33%   |
| 5.10.0-8-686-pae     | 1         | 3.33%   |
| 5.10.0-15-686-pae    | 1         | 3.33%   |
| 5.10.0-13-amd64      | 1         | 3.33%   |
| 5.10.0-12-686-pae    | 1         | 3.33%   |
| 5.10.0-11-686-pae    | 1         | 3.33%   |
| 5.10.0-10-686-pae    | 1         | 3.33%   |
| 4.9.0-8-amd64        | 1         | 3.33%   |
| 4.9.0-14-686-pae     | 1         | 3.33%   |
| 4.9.0-12-686-pae     | 1         | 3.33%   |
| 4.19.0-20-amd64      | 1         | 3.33%   |
| 4.19.0-17-686        | 1         | 3.33%   |
| 4.19.0-14-amd64      | 1         | 3.33%   |
| 4.19.0-13-amd64      | 1         | 3.33%   |
| 4.19.0-12-amd64      | 1         | 3.33%   |
| 4.19.0-10-amd64      | 1         | 3.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 14        | 46.67%  |
| 4.19.0  | 10        | 33.33%  |
| 4.9.0   | 3         | 10%     |
| 5.9.0   | 1         | 3.33%   |
| 5.6.0   | 1         | 3.33%   |
| 5.18.0  | 1         | 3.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 14        | 46.67%  |
| 4.19    | 10        | 33.33%  |
| 4.9     | 3         | 10%     |
| 5.9     | 1         | 3.33%   |
| 5.6     | 1         | 3.33%   |
| 5.18    | 1         | 3.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 20        | 66.67%  |
| i686   | 10        | 33.33%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| KDE5    | 15        | 50%     |
| trinity | 14        | 46.67%  |
| KDE     | 1         | 3.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 29        | 96.67%  |
| Tty  | 1         | 3.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SDDM | 16        | 53.33%  |
| TDM  | 14        | 46.67%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 13        | 43.33%  |
| es_ES   | 3         | 10%     |
| en_GB   | 3         | 10%     |
| sv_SE   | 1         | 3.33%   |
| sl_SI   | 1         | 3.33%   |
| ru_RU   | 1         | 3.33%   |
| pl_PL   | 1         | 3.33%   |
| it_IT   | 1         | 3.33%   |
| fr_FR   | 1         | 3.33%   |
| es_VE   | 1         | 3.33%   |
| en_SG   | 1         | 3.33%   |
| de_DE   | 1         | 3.33%   |
| C       | 1         | 3.33%   |
| Unknown | 1         | 3.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 18        | 60%     |
| EFI  | 12        | 40%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 27        | 90%     |
| Overlay | 3         | 10%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 17        | 56.67%  |
| GPT     | 12        | 40%     |
| Unknown | 1         | 3.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 25        | 83.33%  |
| Yes       | 5         | 16.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 21        | 70%     |
| Yes       | 9         | 30%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 7         | 23.33%  |
| Toshiba          | 4         | 13.33%  |
| ASUSTek Computer | 4         | 13.33%  |
| Lenovo           | 3         | 10%     |
| Visual Land      | 1         | 3.33%   |
| Sony             | 1         | 3.33%   |
| Qilive           | 1         | 3.33%   |
| Phoenix/SiS      | 1         | 3.33%   |
| Philco           | 1         | 3.33%   |
| Packard Bell     | 1         | 3.33%   |
| MSI              | 1         | 3.33%   |
| Medion           | 1         | 3.33%   |
| JVC              | 1         | 3.33%   |
| Chuwi            | 1         | 3.33%   |
| AMI              | 1         | 3.33%   |
| Acer             | 1         | 3.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Toshiba Satellite C660          | 2         | 6.67%   |
| Visual Land Premier 10          | 1         | 3.33%   |
| Toshiba Satellite Pro L500      | 1         | 3.33%   |
| Toshiba Satellite M70           | 1         | 3.33%   |
| Sony VGN-P11Z_Q                 | 1         | 3.33%   |
| Qilive QW19141AMSP              | 1         | 3.33%   |
| Phoenix/SiS M720SR              | 1         | 3.33%   |
| Philco 14I                      | 1         | 3.33%   |
| Packard Bell EasyNote LM81      | 1         | 3.33%   |
| MSI U210                        | 1         | 3.33%   |
| Lenovo ThinkPad T495 20NKS0PG00 | 1         | 3.33%   |
| Lenovo ThinkPad 11e 20DAS0PS00  | 1         | 3.33%   |
| Lenovo IdeaPad 330-15IGM 81D1   | 1         | 3.33%   |
| JVC J3N                         | 1         | 3.33%   |
| HP ProBook 6550b                | 1         | 3.33%   |
| HP ProBook 450 G2               | 1         | 3.33%   |
| HP Presario CQ56                | 1         | 3.33%   |
| HP OmniBook PC                  | 1         | 3.33%   |
| HP Laptop 15s-fq2xxx            | 1         | 3.33%   |
| HP 250 G5 Notebook PC           | 1         | 3.33%   |
| HP 2000                         | 1         | 3.33%   |
| Chuwi GemiBook Pro              | 1         | 3.33%   |
| ASUS X540YA                     | 1         | 3.33%   |
| ASUS T12Eg                      | 1         | 3.33%   |
| ASUS A6U                        | 1         | 3.33%   |
| ASUS A6JC                       | 1         | 3.33%   |
| AMI Intel                       | 1         | 3.33%   |
| Acer AO751h                     | 1         | 3.33%   |
| Unknown                         | 1         | 3.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Toshiba Satellite     | 4         | 13.33%  |
| Lenovo ThinkPad       | 2         | 6.67%   |
| HP ProBook            | 2         | 6.67%   |
| Visual Land Premier   | 1         | 3.33%   |
| Sony VGN-P11Z         | 1         | 3.33%   |
| Qilive QW19141AMSP    | 1         | 3.33%   |
| Phoenix/SiS M720SR    | 1         | 3.33%   |
| Philco 14I            | 1         | 3.33%   |
| Packard Bell EasyNote | 1         | 3.33%   |
| MSI U210              | 1         | 3.33%   |
| Lenovo IdeaPad        | 1         | 3.33%   |
| JVC J3N               | 1         | 3.33%   |
| HP Presario           | 1         | 3.33%   |
| HP OmniBook           | 1         | 3.33%   |
| HP Laptop             | 1         | 3.33%   |
| HP 250                | 1         | 3.33%   |
| HP 2000               | 1         | 3.33%   |
| Chuwi GemiBook        | 1         | 3.33%   |
| ASUS X540YA           | 1         | 3.33%   |
| ASUS T12Eg            | 1         | 3.33%   |
| ASUS A6U              | 1         | 3.33%   |
| ASUS A6JC             | 1         | 3.33%   |
| AMI Intel             | 1         | 3.33%   |
| Acer AO751h           | 1         | 3.33%   |
| Unknown               | 1         | 3.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2010    | 5         | 16.67%  |
| 2020    | 3         | 10%     |
| 2009    | 3         | 10%     |
| 2019    | 2         | 6.67%   |
| 2016    | 2         | 6.67%   |
| 2014    | 2         | 6.67%   |
| 2005    | 2         | 6.67%   |
| Unknown | 2         | 6.67%   |
| 2018    | 1         | 3.33%   |
| 2017    | 1         | 3.33%   |
| 2015    | 1         | 3.33%   |
| 2012    | 1         | 3.33%   |
| 2011    | 1         | 3.33%   |
| 2008    | 1         | 3.33%   |
| 2007    | 1         | 3.33%   |
| 2006    | 1         | 3.33%   |
| 2004    | 1         | 3.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 30        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 28        | 93.33%  |
| Enabled  | 2         | 6.67%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 30        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 9         | 30%     |
| 4.01-8.0   | 5         | 16.67%  |
| 2.01-3.0   | 5         | 16.67%  |
| 1.01-2.0   | 5         | 16.67%  |
| 0.51-1.0   | 3         | 10%     |
| 24.01-32.0 | 1         | 3.33%   |
| 16.01-24.0 | 1         | 3.33%   |
| 0.01-0.5   | 1         | 3.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 13        | 43.33%  |
| 0.51-1.0 | 7         | 23.33%  |
| 2.01-3.0 | 4         | 13.33%  |
| 0.01-0.5 | 4         | 13.33%  |
| 3.01-4.0 | 2         | 6.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 23        | 76.67%  |
| 2      | 6         | 20%     |
| 3      | 1         | 3.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 16        | 53.33%  |
| No        | 14        | 46.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 86.67%  |
| No        | 4         | 13.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 90%     |
| No        | 3         | 10%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 50%     |
| No        | 15        | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 4         | 13.33%  |
| UK           | 3         | 10%     |
| Spain        | 3         | 10%     |
| Kenya        | 3         | 10%     |
| Romania      | 2         | 6.67%   |
| Poland       | 2         | 6.67%   |
| Italy        | 2         | 6.67%   |
| Venezuela    | 1         | 3.33%   |
| Sweden       | 1         | 3.33%   |
| Slovenia     | 1         | 3.33%   |
| Singapore    | 1         | 3.33%   |
| Saudi Arabia | 1         | 3.33%   |
| Russia       | 1         | 3.33%   |
| Qatar        | 1         | 3.33%   |
| Germany      | 1         | 3.33%   |
| France       | 1         | 3.33%   |
| Brazil       | 1         | 3.33%   |
| Belarus      | 1         | 3.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Nairobi               | 3         | 10%     |
| Swindon               | 2         | 6.67%   |
| Mesa                  | 2         | 6.67%   |
| Drobeta-Turnu Severin | 2         | 6.67%   |
| Tranas                | 1         | 3.33%   |
| Tellico Plains        | 1         | 3.33%   |
| Sosnowiec             | 1         | 3.33%   |
| Singapore             | 1         | 3.33%   |
| Salsomaggiore Terme   | 1         | 3.33%   |
| Rostock               | 1         | 3.33%   |
| Puerto Cumarebo       | 1         | 3.33%   |
| Moscow                | 1         | 3.33%   |
| Moirans               | 1         | 3.33%   |
| Mogilev               | 1         | 3.33%   |
| Londrina              | 1         | 3.33%   |
| Ljubljana             | 1         | 3.33%   |
| Las Vegas             | 1         | 3.33%   |
| Klaudyn               | 1         | 3.33%   |
| Gijón                | 1         | 3.33%   |
| Fulham                | 1         | 3.33%   |
| Doha                  | 1         | 3.33%   |
| Dammam                | 1         | 3.33%   |
| Calvecchia            | 1         | 3.33%   |
| Barcelona             | 1         | 3.33%   |
| Alicante              | 1         | 3.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 12.12%  |
| Unknown             | 4         | 4      | 12.12%  |
| Samsung Electronics | 3         | 3      | 9.09%   |
| Hitachi             | 3         | 3      | 9.09%   |
| Toshiba             | 2         | 2      | 6.06%   |
| Seagate             | 2         | 2      | 6.06%   |
| SanDisk             | 2         | 2      | 6.06%   |
| Kingston            | 2         | 2      | 6.06%   |
| KESU                | 2         | 2      | 6.06%   |
| HGST                | 2         | 2      | 6.06%   |
| China               | 2         | 2      | 6.06%   |
| Silicon Motion      | 1         | 1      | 3.03%   |
| Phison              | 1         | 1      | 3.03%   |
| Fujitsu             | 1         | 1      | 3.03%   |
| A-DATA Technology   | 1         | 1      | 3.03%   |
| Unknown             | 1         | 1      | 3.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB            | 2         | 6.06%   |
| KESU USB 3.1 128GB                   | 2         | 6.06%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 3.03%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 3.03%   |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 3.03%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 3.03%   |
| Unknown USDU1  32GB                  | 1         | 3.03%   |
| Unknown SLD64G  64GB                 | 1         | 3.03%   |
| Unknown SD/MMC/MS PRO 64GB           | 1         | 3.03%   |
| Unknown 064G38  64GB                 | 1         | 3.03%   |
| Toshiba MK8025GAS 80GB               | 1         | 3.03%   |
| Toshiba MK6028GAL 64GB               | 1         | 3.03%   |
| Silicon Motion NVME SSD 512GB        | 1         | 3.03%   |
| Seagate ST9120822AS 120GB            | 1         | 3.03%   |
| Seagate Backup+ SL 1TB               | 1         | 3.03%   |
| SanDisk SDCFX-032G SSD               | 1         | 3.03%   |
| SanDisk SD8SN8U1T001122 1TB SSD      | 1         | 3.03%   |
| Samsung AWMB3R  16GB                 | 1         | 3.03%   |
| Phison APS-SE20G-1T                  | 1         | 3.03%   |
| Kingston SV300S37A60G 64GB SSD       | 1         | 3.03%   |
| Kingston SA400S37240G 240GB SSD      | 1         | 3.03%   |
| Hitachi HTS545032B9A300 320GB        | 1         | 3.03%   |
| Hitachi HTS543225L9SA00 250GB        | 1         | 3.03%   |
| Hitachi DK23CA-20 20GB               | 1         | 3.03%   |
| HGST HTS725050A7E630 500GB           | 1         | 3.03%   |
| HGST HTS541075A9E680 752GB           | 1         | 3.03%   |
| Fujitsu MHY2080BH 80GB               | 1         | 3.03%   |
| China SSD128GBS800                   | 1         | 3.03%   |
| China SATA SSD 240GB                 | 1         | 3.03%   |
| A-DATA SU630 240GB SSD               | 1         | 3.03%   |
| Unknown                              | 1         | 3.03%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 23.08%  |
| Hitachi | 3         | 3      | 23.08%  |
| Toshiba | 2         | 2      | 15.38%  |
| HGST    | 2         | 2      | 15.38%  |
| Unknown | 1         | 1      | 7.69%   |
| Seagate | 1         | 1      | 7.69%   |
| Fujitsu | 1         | 1      | 7.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 2         | 2      | 20%     |
| Samsung Electronics | 2         | 2      | 20%     |
| Kingston            | 2         | 2      | 20%     |
| China               | 2         | 2      | 20%     |
| A-DATA Technology   | 1         | 1      | 10%     |
| Unknown             | 1         | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 12        | 13     | 38.71%  |
| SSD     | 10        | 10     | 32.26%  |
| MMC     | 4         | 4      | 12.9%   |
| Unknown | 3         | 3      | 9.68%   |
| NVMe    | 2         | 3      | 6.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 22        | 22     | 68.75%  |
| SAS  | 4         | 4      | 12.5%   |
| MMC  | 4         | 4      | 12.5%   |
| NVMe | 2         | 3      | 6.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 20        | 21     | 90.91%  |
| 0.51-1.0   | 2         | 2      | 9.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 51-100     | 7         | 23.33%  |
| 101-250    | 6         | 20%     |
| 1-20       | 5         | 16.67%  |
| 21-50      | 4         | 13.33%  |
| 251-500    | 3         | 10%     |
| 1001-2000  | 2         | 6.67%   |
| 501-1000   | 2         | 6.67%   |
| Unknown    | 1         | 3.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 20        | 66.67%  |
| 21-50    | 5         | 16.67%  |
| 251-500  | 2         | 6.67%   |
| 501-1000 | 1         | 3.33%   |
| 51-100   | 1         | 3.33%   |
| Unknown  | 1         | 3.33%   |

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
| Works    | 15        | 16     | 48.39%  |
| Detected | 8         | 9      | 25.81%  |
| Malfunc  | 8         | 8      | 25.81%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 19        | 63.33%  |
| AMD                              | 6         | 20%     |
| Silicon Integrated Systems [SiS] | 2         | 6.67%   |
| Silicon Motion                   | 1         | 3.33%   |
| SanDisk                          | 1         | 3.33%   |
| Phison Electronics               | 1         | 3.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 8.82%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 8.82%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 2         | 5.88%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 2         | 5.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 5.88%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 2.94%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 2.94%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 2.94%   |
| Phison E12 NVMe Controller                                                       | 1         | 2.94%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 2.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 2.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 2.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 2.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 2.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 2.94%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 1         | 2.94%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 1         | 2.94%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 1         | 2.94%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 1         | 2.94%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 2.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 2.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 2.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 2.94%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 2.94%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 2.94%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 17        | 56.67%  |
| IDE  | 10        | 33.33%  |
| NVMe | 2         | 6.67%   |
| RAID | 1         | 3.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 22        | 73.33%  |
| AMD    | 8         | 26.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i3-2350M CPU @ 2.30GHz               | 2         | 6.67%   |
| Intel Atom CPU Z520 @ 1.33GHz                   | 2         | 6.67%   |
| Intel Pentium M processor 1000MHz               | 1         | 3.33%   |
| Intel Pentium M processor 1.70GHz               | 1         | 3.33%   |
| Intel Pentium III (Coppermine)                  | 1         | 3.33%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz     | 1         | 3.33%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 3.33%   |
| Intel Core i5 CPU M 450 @ 2.40GHz               | 1         | 3.33%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz            | 1         | 3.33%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz            | 1         | 3.33%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz            | 1         | 3.33%   |
| Intel Core 2 CPU T5500 @ 1.66GHz                | 1         | 3.33%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 1         | 3.33%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 1         | 3.33%   |
| Intel Celeron J4115 CPU @ 1.80GHz               | 1         | 3.33%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 1         | 3.33%   |
| Intel Celeron CPU N2940 @ 1.83GHz               | 1         | 3.33%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz               | 1         | 3.33%   |
| Intel Atom CPU Z3735G @ 1.33GHz                 | 1         | 3.33%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 1         | 3.33%   |
| AMD V120 Processor                              | 1         | 3.33%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 1         | 3.33%   |
| AMD Mobile Sempron Processor 3000+              | 1         | 3.33%   |
| AMD E-300 APU with Radeon HD Graphics           | 1         | 3.33%   |
| AMD C-70 APU with Radeon HD Graphics            | 1         | 3.33%   |
| AMD Athlon Neo Processor MV-40                  | 1         | 3.33%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 1         | 3.33%   |
| AMD A4-9120e RADEON R3, 4 COMPUTE CORES 2C+2G   | 1         | 3.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 5         | 16.67%  |
| Intel Atom              | 4         | 13.33%  |
| Intel Core 2 Duo        | 3         | 10%     |
| Intel Pentium M         | 2         | 6.67%   |
| Intel Core i5           | 2         | 6.67%   |
| Intel Core i3           | 2         | 6.67%   |
| Other                   | 1         | 3.33%   |
| Intel Pentium III       | 1         | 3.33%   |
| Intel Pentium Dual-Core | 1         | 3.33%   |
| Intel Core 2            | 1         | 3.33%   |
| AMD V120                | 1         | 3.33%   |
| AMD Ryzen 7 PRO         | 1         | 3.33%   |
| AMD Mobile Sempron      | 1         | 3.33%   |
| AMD E                   | 1         | 3.33%   |
| AMD C-70                | 1         | 3.33%   |
| AMD Athlon Neo          | 1         | 3.33%   |
| AMD A8                  | 1         | 3.33%   |
| AMD A4                  | 1         | 3.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 14        | 46.67%  |
| 4      | 8         | 26.67%  |
| 1      | 8         | 26.67%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 30        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 22        | 73.33%  |
| 2      | 8         | 26.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 24        | 80%     |
| 32-bit         | 6         | 20%     |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4         | 13.33%  |
| 0x706a1    | 2         | 6.67%   |
| 0x6fd      | 2         | 6.67%   |
| 0x30678    | 2         | 6.67%   |
| 0x206a7    | 2         | 6.67%   |
| 0x1067a    | 2         | 6.67%   |
| 0x806c1    | 1         | 3.33%   |
| 0x706a8    | 1         | 3.33%   |
| 0x6f6      | 1         | 3.33%   |
| 0x6d8      | 1         | 3.33%   |
| 0x695      | 1         | 3.33%   |
| 0x68a      | 1         | 3.33%   |
| 0x406c4    | 1         | 3.33%   |
| 0x40651    | 1         | 3.33%   |
| 0x20655    | 1         | 3.33%   |
| 0x106c2    | 1         | 3.33%   |
| 0x08108102 | 1         | 3.33%   |
| 0x07030106 | 1         | 3.33%   |
| 0x06006705 | 1         | 3.33%   |
| 0x05000119 | 1         | 3.33%   |
| 0x0500010d | 1         | 3.33%   |
| 0x010000c8 | 1         | 3.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Silvermont    | 4         | 13.33%  |
| P6            | 3         | 10%     |
| Goldmont plus | 3         | 10%     |
| Core          | 3         | 10%     |
| SandyBridge   | 2         | 6.67%   |
| Penryn        | 2         | 6.67%   |
| K8 Hammer     | 2         | 6.67%   |
| Bonnell       | 2         | 6.67%   |
| Bobcat        | 2         | 6.67%   |
| Zen+          | 1         | 3.33%   |
| Westmere      | 1         | 3.33%   |
| TigerLake     | 1         | 3.33%   |
| Puma          | 1         | 3.33%   |
| K10           | 1         | 3.33%   |
| Haswell       | 1         | 3.33%   |
| Excavator     | 1         | 3.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 17        | 54.84%  |
| AMD                              | 10        | 32.26%  |
| Silicon Integrated Systems [SiS] | 2         | 6.45%   |
| S3 Graphics                      | 1         | 3.23%   |
| Nvidia                           | 1         | 3.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Notebooks | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel GeminiLake [UHD Graphics 600]                                                        | 3         | 9.38%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 2         | 6.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 2         | 6.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 2         | 6.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 2         | 6.25%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 1         | 3.13%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 1         | 3.13%   |
| S3 Graphics 86C270-294 [SavageIX-MV]                                                       | 1         | 3.13%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                              | 1         | 3.13%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 1         | 3.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 1         | 3.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 1         | 3.13%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 1         | 3.13%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 1         | 3.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 1         | 3.13%   |
| Intel 82852/855GM Integrated Graphics Device                                               | 1         | 3.13%   |
| AMD Wrestler [Radeon HD 7290]                                                              | 1         | 3.13%   |
| AMD Wrestler [Radeon HD 6310]                                                              | 1         | 3.13%   |
| AMD Topaz PRO [Radeon R5 M255]                                                             | 1         | 3.13%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 1         | 3.13%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                          | 1         | 3.13%   |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                               | 1         | 3.13%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                  | 1         | 3.13%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                  | 1         | 3.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                       | 1         | 3.13%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                        | 1         | 3.13%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 15        | 50%     |
| 1 x AMD         | 9         | 30%     |
| 1 x SiS         | 2         | 6.67%   |
| Other           | 1         | 3.33%   |
| 1 x S3 Graphics | 1         | 3.33%   |
| 1 x Nvidia      | 1         | 3.33%   |
| Intel + AMD     | 1         | 3.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 26        | 86.67%  |
| Unknown     | 3         | 10%     |
| Proprietary | 1         | 3.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 63.33%  |
| 0.01-0.5   | 9         | 30%     |
| 1.01-2.0   | 2         | 6.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 7         | 26.92%  |
| AU Optronics        | 6         | 23.08%  |
| Samsung Electronics | 5         | 19.23%  |
| LG Display          | 3         | 11.54%  |
| Hewlett-Packard     | 1         | 3.85%   |
| HannStar            | 1         | 3.85%   |
| Dell                | 1         | 3.85%   |
| CPT                 | 1         | 3.85%   |
| BOE                 | 1         | 3.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 2         | 7.69%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 2         | 7.69%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch    | 1         | 3.85%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch   | 1         | 3.85%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch   | 1         | 3.85%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch   | 1         | 3.85%   |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 1020x570mm 46.0-inch | 1         | 3.85%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch            | 1         | 3.85%   |
| Hewlett-Packard Z24i HWP3100 1920x1200 518x324mm 24.1-inch             | 1         | 3.85%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch               | 1         | 3.85%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                       | 1         | 3.85%   |
| CPT LCD Monitor CPT13B1 1280x800 330x210mm 15.4-inch                   | 1         | 3.85%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch       | 1         | 3.85%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 1         | 3.85%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch        | 1         | 3.85%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch        | 1         | 3.85%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch        | 1         | 3.85%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                   | 1         | 3.85%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch         | 1         | 3.85%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 256x144mm 11.6-inch         | 1         | 3.85%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch          | 1         | 3.85%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch          | 1         | 3.85%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch          | 1         | 3.85%   |
| AU Optronics LCD Monitor AUO12EC 1366x768 344x193mm 15.5-inch          | 1         | 3.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 11        | 42.31%  |
| 1920x1080 (FHD)   | 7         | 26.92%  |
| 1600x900 (HD+)    | 3         | 11.54%  |
| 1280x800 (WXGA)   | 3         | 11.54%  |
| 2160x1440         | 1         | 3.85%   |
| 1920x1200 (WUXGA) | 1         | 3.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 13        | 50%     |
| 13     | 3         | 11.54%  |
| 11     | 2         | 7.69%   |
| 46     | 1         | 3.85%   |
| 40     | 1         | 3.85%   |
| 24     | 1         | 3.85%   |
| 23     | 1         | 3.85%   |
| 18     | 1         | 3.85%   |
| 17     | 1         | 3.85%   |
| 14     | 1         | 3.85%   |
| 12     | 1         | 3.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 16        | 61.54%  |
| 201-300     | 4         | 15.38%  |
| 501-600     | 2         | 7.69%   |
| 351-400     | 2         | 7.69%   |
| 801-900     | 1         | 3.85%   |
| 1001-1500   | 1         | 3.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 19        | 79.17%  |
| 16/10 | 4         | 16.67%  |
| 3/2   | 1         | 4.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 13        | 50%     |
| 81-90          | 4         | 15.38%  |
| 51-60          | 2         | 7.69%   |
| 501-1000       | 2         | 7.69%   |
| 61-70          | 1         | 3.85%   |
| 251-300        | 1         | 3.85%   |
| 201-250        | 1         | 3.85%   |
| 141-150        | 1         | 3.85%   |
| 121-130        | 1         | 3.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 12        | 46.15%  |
| 51-100  | 6         | 23.08%  |
| 121-160 | 5         | 19.23%  |
| 161-240 | 2         | 7.69%   |
| 1-50    | 1         | 3.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 26        | 86.67%  |
| 2     | 2         | 6.67%   |
| 0     | 2         | 6.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 22        | 41.51%  |
| Qualcomm Atheros                 | 11        | 20.75%  |
| Intel                            | 9         | 16.98%  |
| Silicon Integrated Systems [SiS] | 2         | 3.77%   |
| Broadcom                         | 2         | 3.77%   |
| Xiaomi                           | 1         | 1.89%   |
| Motorola PCS                     | 1         | 1.89%   |
| Marvell Technology Group         | 1         | 1.89%   |
| LG Electronics                   | 1         | 1.89%   |
| JMicron Technology               | 1         | 1.89%   |
| Broadcom Limited                 | 1         | 1.89%   |
| Accton Technology                | 1         | 1.89%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 7         | 12.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 7         | 12.28%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                       | 3         | 5.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 3         | 5.26%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 3         | 5.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 2         | 3.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 2         | 3.51%   |
| Intel Wi-Fi 6 AX200                                                         | 2         | 3.51%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 2         | 3.51%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                    | 2         | 3.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                              | 1         | 1.75%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                     | 1         | 1.75%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter               | 1         | 1.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 1.75%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                  | 1         | 1.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 1.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 1.75%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                  | 1         | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 1.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1         | 1.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1         | 1.75%   |
| Motorola PCS moto g(9) play                                                 | 1         | 1.75%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                     | 1         | 1.75%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                         | 1         | 1.75%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                      | 1         | 1.75%   |
| Intel Wireless 3165                                                         | 1         | 1.75%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 1.75%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller            | 1         | 1.75%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller           | 1         | 1.75%   |
| Intel 82577LC Gigabit Network Connection                                    | 1         | 1.75%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                             | 1         | 1.75%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1         | 1.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 1.75%   |
| Accton EN-1216 Ethernet Adapter                                             | 1         | 1.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 11        | 40.74%  |
| Intel                 | 8         | 29.63%  |
| Realtek Semiconductor | 6         | 22.22%  |
| Broadcom Limited      | 1         | 3.7%    |
| Broadcom              | 1         | 3.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 3         | 11.11%  |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 3         | 11.11%  |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 2         | 7.41%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 2         | 7.41%   |
| Intel Wi-Fi 6 AX200                                                         | 2         | 7.41%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 2         | 7.41%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                    | 2         | 7.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 3.7%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                  | 1         | 3.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 3.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 3.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 3.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1         | 3.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1         | 3.7%    |
| Intel Wireless 3165                                                         | 1         | 3.7%    |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 3.7%    |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1         | 3.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 3.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 18        | 66.67%  |
| Xiaomi                           | 1         | 3.7%    |
| Silicon Integrated Systems [SiS] | 1         | 3.7%    |
| Motorola PCS                     | 1         | 3.7%    |
| Marvell Technology Group         | 1         | 3.7%    |
| LG Electronics                   | 1         | 3.7%    |
| JMicron Technology               | 1         | 3.7%    |
| Intel                            | 1         | 3.7%    |
| Broadcom                         | 1         | 3.7%    |
| Accton Technology                | 1         | 3.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 25.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 25.93%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 11.11%  |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 3.7%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 3.7%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 3.7%    |
| Motorola PCS moto g(9) play                                       | 1         | 3.7%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 3.7%    |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)               | 1         | 3.7%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 3.7%    |
| Intel 82577LC Gigabit Network Connection                          | 1         | 3.7%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 3.7%    |
| Accton EN-1216 Ethernet Adapter                                   | 1         | 3.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 48.21%  |
| Ethernet | 26        | 46.43%  |
| Modem    | 3         | 5.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 19        | 63.33%  |
| Ethernet | 11        | 36.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 20        | 66.67%  |
| 1     | 7         | 23.33%  |
| 0     | 2         | 6.67%   |
| 3     | 1         | 3.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 29        | 96.67%  |
| Yes  | 1         | 3.33%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros Communications | 4         | 26.67%  |
| Intel                           | 4         | 26.67%  |
| Realtek Semiconductor           | 3         | 20%     |
| Toshiba                         | 1         | 6.67%   |
| Hewlett-Packard                 | 1         | 6.67%   |
| ASUSTek Computer                | 1         | 6.67%   |
| Alps Electric                   | 1         | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                        | 3         | 20%     |
| Qualcomm Atheros AR3011 Bluetooth              | 3         | 20%     |
| Intel AX200 Bluetooth                          | 2         | 13.33%  |
| Toshiba Askey for                              | 1         | 6.67%   |
| Qualcomm Atheros  Bluetooth Device             | 1         | 6.67%   |
| Intel Bluetooth wireless interface             | 1         | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 6.67%   |
| HP Broadcom 2070 Bluetooth Combo               | 1         | 6.67%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter          | 1         | 6.67%   |
| Alps Electric BCM2046 Bluetooth Device         | 1         | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 18        | 60%     |
| AMD                              | 9         | 30%     |
| Silicon Integrated Systems [SiS] | 2         | 6.67%   |
| ESS Technology                   | 1         | 3.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 7.89%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 7.89%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 2         | 5.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 5.26%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 5.26%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 5.26%   |
| AMD FCH Azalia Controller                                                                         | 2         | 5.26%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 1         | 2.63%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 2.63%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 2.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 2.63%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 2.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 2.63%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2.63%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 2.63%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 2.63%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 2.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 2.63%   |
| ESS Technology ES1988 Allegro-1                                                                   | 1         | 2.63%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 2.63%   |
| AMD RS690 HDMI Audio [Radeon Xpress 1200 Series]                                                  | 1         | 2.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 2.63%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 2.63%   |
| AMD High Definition Audio Controller                                                              | 1         | 2.63%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 2.63%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 2.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 12        | 40%     |
| Samsung Electronics | 7         | 23.33%  |
| SK hynix            | 4         | 13.33%  |
| Unknown (ABCD)      | 2         | 6.67%   |
| Kingston            | 2         | 6.67%   |
| Toshiba             | 1         | 3.33%   |
| Elpida              | 1         | 3.33%   |
| A-DATA Technology   | 1         | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 4         | 12.12%  |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 2         | 6.06%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 6.06%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 6.06%   |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 3.03%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 3.03%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 3.03%   |
| Unknown RAM Module 256MB SODIMM SDRAM                            | 1         | 3.03%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 3.03%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 3.03%   |
| Unknown RAM Module 1GB SODIMM DDR 266MT/s                        | 1         | 3.03%   |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                        | 1         | 3.03%   |
| Unknown RAM CL19-19-19 D4-2666 8GB SODIMM DDR4 2133MT/s          | 1         | 3.03%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 3.03%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 1         | 3.03%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 1         | 3.03%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 3.03%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 3.03%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2400MT/s           | 1         | 3.03%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 3.03%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 3.03%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 1         | 3.03%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 3.03%   |
| Kingston RAM HP32D4S2S1ME-4 4GB SODIMM DDR4 3200MT/s             | 1         | 3.03%   |
| Kingston RAM 99U5428-041.A01G 4GB SODIMM DDR3 1067MT/s           | 1         | 3.03%   |
| Elpida RAM EBJ10UE8BDS0-AE-F 1GB SODIMM DDR3 1067MT/s            | 1         | 3.03%   |
| A-DATA RAM AM1U16BC2P1-B1AH 2GB SODIMM DDR3 4199MT/s             | 1         | 3.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 10        | 35.71%  |
| DDR2   | 6         | 21.43%  |
| DDR4   | 4         | 14.29%  |
| SDRAM  | 3         | 10.71%  |
| LPDDR4 | 2         | 7.14%   |
| DDR    | 2         | 7.14%   |
| DRAM   | 1         | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 27        | 96.43%  |
| DIMM   | 1         | 3.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 13        | 43.33%  |
| 2048  | 10        | 33.33%  |
| 1024  | 4         | 13.33%  |
| 16384 | 1         | 3.33%   |
| 512   | 1         | 3.33%   |
| 256   | 1         | 3.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 8         | 26.67%  |
| 2400    | 4         | 13.33%  |
| 1600    | 4         | 13.33%  |
| 1334    | 3         | 10%     |
| 1333    | 2         | 6.67%   |
| 1067    | 2         | 6.67%   |
| 4199    | 1         | 3.33%   |
| 3266    | 1         | 3.33%   |
| 3200    | 1         | 3.33%   |
| 2667    | 1         | 3.33%   |
| 1066    | 1         | 3.33%   |
| 800     | 1         | 3.33%   |
| 266     | 1         | 3.33%   |

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
| Chicony Electronics                    | 4         | 23.53%  |
| Microdia                               | 2         | 11.76%  |
| IMC Networks                           | 2         | 11.76%  |
| Acer                                   | 2         | 11.76%  |
| Suyin                                  | 1         | 5.88%   |
| Silicon Motion                         | 1         | 5.88%   |
| Ricoh                                  | 1         | 5.88%   |
| Realtek Semiconductor                  | 1         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 5.88%   |
| ALi                                    | 1         | 5.88%   |
| Alcor Micro                            | 1         | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 5.88%   |
| Silicon Motion 300k Pixel Camera                            | 1         | 5.88%   |
| Ricoh Sony Visual Communication Camera                      | 1         | 5.88%   |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 5.88%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 5.88%   |
| Microdia Amcrest AWC2198 USB Webcam                         | 1         | 5.88%   |
| IMC Networks Integrated Camera                              | 1         | 5.88%   |
| IMC Networks HP TrueVision HD Camera                        | 1         | 5.88%   |
| Chicony USB2.0 UVC WebCam                                   | 1         | 5.88%   |
| Chicony Integrated Camera                                   | 1         | 5.88%   |
| Chicony HP Webcam                                           | 1         | 5.88%   |
| Chicony HP HD Webcam                                        | 1         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 1         | 5.88%   |
| ALi M5603 Video Camera Controller                           | 1         | 5.88%   |
| Alcor Micro USB 2.0 PC cam                                  | 1         | 5.88%   |
| Acer USB Camera                                             | 1         | 5.88%   |
| Acer EasyCamera                                             | 1         | 5.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 66.67%  |
| Synaptics        | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 33.33%  |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 33.33%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 33.33%  |

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
| 0     | 24        | 80%     |
| 2     | 3         | 10%     |
| 1     | 3         | 10%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 3         | 33.33%  |
| Fingerprint reader       | 3         | 33.33%  |
| Flash memory             | 1         | 11.11%  |
| Communication controller | 1         | 11.11%  |
| Camera                   | 1         | 11.11%  |

