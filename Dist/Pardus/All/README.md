Pardus - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Pardus.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Pardus/Desktop/README.md) and [notebooks](/Dist/Pardus/Notebook/README.md).

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Sony          | SVF1521QSTB                 | Notebook    | [f74068fef9](https://linux-hardware.org/?probe=f74068fef9) | Feb 14, 2022 |
| HP            | Pavilion 15                 | Notebook    | [fe001e576b](https://linux-hardware.org/?probe=fe001e576b) | Feb 13, 2022 |
| Packard Be... | EasyNote ENTG81BA           | Notebook    | [10f68b4c82](https://linux-hardware.org/?probe=10f68b4c82) | Jan 31, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [fcde789242](https://linux-hardware.org/?probe=fcde789242) | Jan 24, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [dd92029684](https://linux-hardware.org/?probe=dd92029684) | Jan 21, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [121a750c5b](https://linux-hardware.org/?probe=121a750c5b) | Jan 03, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [16efe9685d](https://linux-hardware.org/?probe=16efe9685d) | Dec 17, 2021 |
| Toshiba       | PORTEGE M780                | Notebook    | [c68379ab38](https://linux-hardware.org/?probe=c68379ab38) | Nov 30, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [1cf8a783be](https://linux-hardware.org/?probe=1cf8a783be) | Oct 21, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [20a54c9779](https://linux-hardware.org/?probe=20a54c9779) | Oct 21, 2021 |
| Lenovo        | 3132 NOK                    | Desktop     | [9d1ef122f7](https://linux-hardware.org/?probe=9d1ef122f7) | Oct 11, 2021 |
| Lenovo        | 3132 NOK                    | Desktop     | [5802651f49](https://linux-hardware.org/?probe=5802651f49) | Sep 15, 2021 |
| Lenovo        | IdeaPad-510-15IKB 80SV      | Notebook    | [1a343f3596](https://linux-hardware.org/?probe=1a343f3596) | Sep 02, 2021 |
| Philco        | 14F                         | Notebook    | [343861b100](https://linux-hardware.org/?probe=343861b100) | Jun 20, 2021 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [9149be671f](https://linux-hardware.org/?probe=9149be671f) | Jan 30, 2021 |
| Toshiba       | Satellite C855-1VM          | Notebook    | [dab32c2669](https://linux-hardware.org/?probe=dab32c2669) | Jan 24, 2021 |
| Lenovo        | ThinkPad T450 20BUS39Y00    | Notebook    | [579099bf91](https://linux-hardware.org/?probe=579099bf91) | Dec 26, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [39f1d96886](https://linux-hardware.org/?probe=39f1d96886) | Dec 16, 2020 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [33cdf15439](https://linux-hardware.org/?probe=33cdf15439) | Dec 15, 2020 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [6cd7c2a8a6](https://linux-hardware.org/?probe=6cd7c2a8a6) | Dec 11, 2020 |
| ASUSTek       | X555YI                      | Notebook    | [d210c4b901](https://linux-hardware.org/?probe=d210c4b901) | Sep 26, 2020 |
| Packard Be... | EasyNote_GN45               | Notebook    | [210b740311](https://linux-hardware.org/?probe=210b740311) | Sep 24, 2020 |
| Dell          | Latitude E6540              | Notebook    | [d2337e32c1](https://linux-hardware.org/?probe=d2337e32c1) | Sep 05, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [c410333e82](https://linux-hardware.org/?probe=c410333e82) | Jun 11, 2020 |
| ASUSTek       | E402BP                      | Notebook    | [d531d0fe45](https://linux-hardware.org/?probe=d531d0fe45) | Jun 01, 2020 |
| HP            | 15                          | Notebook    | [36d90829ee](https://linux-hardware.org/?probe=36d90829ee) | May 02, 2020 |
| HP            | 15                          | Notebook    | [06393a1175](https://linux-hardware.org/?probe=06393a1175) | Apr 27, 2020 |
| HP            | 15                          | Notebook    | [e21973794b](https://linux-hardware.org/?probe=e21973794b) | Feb 02, 2020 |
| Dell          | G5 5587                     | Notebook    | [1742540bc9](https://linux-hardware.org/?probe=1742540bc9) | Nov 27, 2019 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [dd8de8c9a2](https://linux-hardware.org/?probe=dd8de8c9a2) | Oct 18, 2019 |
| HP            | 250 G3                      | Notebook    | [e82ead9af0](https://linux-hardware.org/?probe=e82ead9af0) | Oct 13, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 4.19.0-6-amd64       | 3         | 11.11%  |
| 4.19.0-13-amd64      | 3         | 11.11%  |
| 4.19.0-10-amd64      | 3         | 11.11%  |
| 5.9.0-0.bpo.2-amd64  | 2         | 7.41%   |
| 5.10.0-9-amd64       | 2         | 7.41%   |
| 5.10.0-8-amd64       | 2         | 7.41%   |
| 5.10.0-11-amd64      | 2         | 7.41%   |
| 5.10.0-10-amd64      | 2         | 7.41%   |
| 4.19.0-8-amd64       | 2         | 7.41%   |
| 5.4.0-0.bpo.3-amd64  | 1         | 3.7%    |
| 5.10.0-0.bpo.8-amd64 | 1         | 3.7%    |
| 4.19.0-5-amd64       | 1         | 3.7%    |
| 4.19.0-18-amd64      | 1         | 3.7%    |
| 4.19.0-16-amd64      | 1         | 3.7%    |
| 4.19.0-12-amd64      | 1         | 3.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19.0  | 14        | 53.85%  |
| 5.10.0  | 9         | 34.62%  |
| 5.9.0   | 2         | 7.69%   |
| 5.4.0   | 1         | 3.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19    | 14        | 53.85%  |
| 5.10    | 9         | 34.62%  |
| 5.9     | 2         | 7.69%   |
| 5.4     | 1         | 3.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 26        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| XFCE    | 16        | 61.54%  |
| GNOME   | 7         | 26.92%  |
| Unknown | 2         | 7.69%   |
| KDE5    | 1         | 3.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 26        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 16        | 61.54%  |
| TDM     | 6         | 23.08%  |
| LightDM | 2         | 7.69%   |
| GDM     | 2         | 7.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| tr_TR   | 19        | 73.08%  |
| Unknown | 3         | 11.54%  |
| pt_BR   | 1         | 3.85%   |
| fr_FR   | 1         | 3.85%   |
| en_US   | 1         | 3.85%   |
| en_GB   | 1         | 3.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 20        | 76.92%  |
| EFI  | 6         | 23.08%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ext4 | 26        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 18        | 69.23%  |
| GPT     | 6         | 23.08%  |
| MBR     | 2         | 7.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 25        | 96.15%  |
| Yes       | 1         | 3.85%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 22        | 84.62%  |
| Yes       | 4         | 15.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 7         | 26.92%  |
| Hewlett-Packard     | 4         | 15.38%  |
| ASUSTek Computer    | 4         | 15.38%  |
| Toshiba             | 2         | 7.69%   |
| Packard Bell        | 2         | 7.69%   |
| Gigabyte Technology | 2         | 7.69%   |
| Dell                | 2         | 7.69%   |
| Sony                | 1         | 3.85%   |
| Samsung Electronics | 1         | 3.85%   |
| Philco              | 1         | 3.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Toshiba Satellite C855-1VM                 | 1         | 3.85%   |
| Toshiba PORTEGE M780                       | 1         | 3.85%   |
| Sony SVF1521QSTB                           | 1         | 3.85%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 3.85%   |
| Philco 14F                                 | 1         | 3.85%   |
| Packard Bell EasyNote_GN45                 | 1         | 3.85%   |
| Packard Bell EasyNote ENTG81BA             | 1         | 3.85%   |
| Lenovo Yoga 310-11IAP 80U2                 | 1         | 3.85%   |
| Lenovo V145-15AST 81MT                     | 1         | 3.85%   |
| Lenovo V110-15ISK 80TL                     | 1         | 3.85%   |
| Lenovo ThinkPad T450 20BUS39Y00            | 1         | 3.85%   |
| Lenovo ThinkCentre M920t 10SGS62900        | 1         | 3.85%   |
| Lenovo IdeaPad-510-15IKB 80SV              | 1         | 3.85%   |
| Lenovo IdeaPad 320-15IKB 81BT              | 1         | 3.85%   |
| HP Pavilion 15                             | 1         | 3.85%   |
| HP Laptop 15-dw3xxx                        | 1         | 3.85%   |
| HP 250 G3                                  | 1         | 3.85%   |
| HP 15                                      | 1         | 3.85%   |
| Gigabyte A320M-S2H                         | 1         | 3.85%   |
| Gigabyte A320M-H                           | 1         | 3.85%   |
| Dell Latitude E6540                        | 1         | 3.85%   |
| Dell G5 5587                               | 1         | 3.85%   |
| ASUS X555YI                                | 1         | 3.85%   |
| ASUS V230IC-DDR4                           | 1         | 3.85%   |
| ASUS P5G41C-M LX                           | 1         | 3.85%   |
| ASUS E402BP                                | 1         | 3.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Packard Bell EasyNote    | 2         | 7.69%   |
| Toshiba Satellite        | 1         | 3.85%   |
| Toshiba PORTEGE          | 1         | 3.85%   |
| Sony SVF1521QSTB         | 1         | 3.85%   |
| Samsung 300E4A           | 1         | 3.85%   |
| Philco 14F               | 1         | 3.85%   |
| Lenovo Yoga              | 1         | 3.85%   |
| Lenovo V145-15AST        | 1         | 3.85%   |
| Lenovo V110-15ISK        | 1         | 3.85%   |
| Lenovo ThinkPad          | 1         | 3.85%   |
| Lenovo ThinkCentre       | 1         | 3.85%   |
| Lenovo IdeaPad-510-15IKB | 1         | 3.85%   |
| Lenovo IdeaPad           | 1         | 3.85%   |
| HP Pavilion              | 1         | 3.85%   |
| HP Laptop                | 1         | 3.85%   |
| HP 250                   | 1         | 3.85%   |
| HP 15                    | 1         | 3.85%   |
| Gigabyte A320M-S2H       | 1         | 3.85%   |
| Gigabyte A320M-H         | 1         | 3.85%   |
| Dell Latitude            | 1         | 3.85%   |
| Dell G5                  | 1         | 3.85%   |
| ASUS X555YI              | 1         | 3.85%   |
| ASUS V230IC-DDR4         | 1         | 3.85%   |
| ASUS P5G41C-M            | 1         | 3.85%   |
| ASUS E402BP              | 1         | 3.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 5         | 19.23%  |
| 2013 | 5         | 19.23%  |
| 2015 | 3         | 11.54%  |
| 2017 | 2         | 7.69%   |
| 2016 | 2         | 7.69%   |
| 2011 | 2         | 7.69%   |
| 2010 | 2         | 7.69%   |
| 2021 | 1         | 3.85%   |
| 2020 | 1         | 3.85%   |
| 2019 | 1         | 3.85%   |
| 2014 | 1         | 3.85%   |
| 2006 | 1         | 3.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 20        | 76.92%  |
| Desktop     | 4         | 15.38%  |
| Convertible | 1         | 3.85%   |
| All in one  | 1         | 3.85%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 26        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 26        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 10        | 38.46%  |
| 4.01-8.0   | 8         | 30.77%  |
| 16.01-24.0 | 3         | 11.54%  |
| 1.01-2.0   | 2         | 7.69%   |
| 8.01-16.0  | 2         | 7.69%   |
| 32.01-64.0 | 1         | 3.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 11        | 40.74%  |
| 2.01-3.0   | 8         | 29.63%  |
| 3.01-4.0   | 3         | 11.11%  |
| 4.01-8.0   | 2         | 7.41%   |
| 24.01-32.0 | 1         | 3.7%    |
| 8.01-16.0  | 1         | 3.7%    |
| 0.51-1.0   | 1         | 3.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 20        | 76.92%  |
| 2      | 4         | 15.38%  |
| 4      | 1         | 3.85%   |
| 3      | 1         | 3.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 16        | 61.54%  |
| No        | 10        | 38.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 96.15%  |
| No        | 1         | 3.85%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 84.62%  |
| No        | 4         | 15.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 73.08%  |
| No        | 7         | 26.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Turkey  | 23        | 88.46%  |
| UK      | 1         | 3.85%   |
| France  | 1         | 3.85%   |
| Brazil  | 1         | 3.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Istanbul      | 9         | 33.33%  |
| Bursa         | 4         | 14.81%  |
| Izmir         | 2         | 7.41%   |
| Ankara        | 2         | 7.41%   |
| Г‡anakkale | 1         | 3.7%    |
| Soleymieu     | 1         | 3.7%    |
| Porto Alegre  | 1         | 3.7%    |
| Mersin        | 1         | 3.7%    |
| Malatya       | 1         | 3.7%    |
| London        | 1         | 3.7%    |
| Kosekoy       | 1         | 3.7%    |
| Konya         | 1         | 3.7%    |
| Gaziantep     | 1         | 3.7%    |
| Antalya       | 1         | 3.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 8      | 18.18%  |
| Seagate             | 6         | 7      | 18.18%  |
| Samsung Electronics | 6         | 8      | 18.18%  |
| SK Hynix            | 2         | 2      | 6.06%   |
| HGST                | 2         | 2      | 6.06%   |
| Unknown             | 1         | 1      | 3.03%   |
| Toshiba             | 1         | 1      | 3.03%   |
| Team                | 1         | 1      | 3.03%   |
| SPCC                | 1         | 1      | 3.03%   |
| SanDisk             | 1         | 1      | 3.03%   |
| Lexar               | 1         | 1      | 3.03%   |
| Kingston            | 1         | 1      | 3.03%   |
| KingSpec            | 1         | 1      | 3.03%   |
| Hitachi             | 1         | 1      | 3.03%   |
| Corsair             | 1         | 1      | 3.03%   |
| addlink             | 1         | 1      | 3.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| HGST HTS545050A7E680 500GB                  | 2         | 5.88%   |
| WDC WD5000LPVX-55V0TT0 500GB                | 1         | 2.94%   |
| WDC WD5000LPCX-21VHAT0 500GB                | 1         | 2.94%   |
| WDC WD3200BPVT-35JJ5T0 320GB                | 1         | 2.94%   |
| WDC WD3200AAJB-00WGA0 320GB                 | 1         | 2.94%   |
| WDC WD10JPVX-60JC3T0 1TB                    | 1         | 2.94%   |
| WDC WD10JPCX-24UE4T0 1TB                    | 1         | 2.94%   |
| Unknown MMC Card  64GB                      | 1         | 2.94%   |
| Toshiba DT01ACA100 1TB                      | 1         | 2.94%   |
| Team T253X1240G 240GB SSD                   | 1         | 2.94%   |
| SPCC Solid State Disk 512GB                 | 1         | 2.94%   |
| SK Hynix SC311 SATA 256GB SSD               | 1         | 2.94%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB     | 1         | 2.94%   |
| Seagate ST9120822AS 120GB                   | 1         | 2.94%   |
| Seagate ST3160318AS 160GB                   | 1         | 2.94%   |
| Seagate ST2000DM008-2FR102 2TB              | 1         | 2.94%   |
| Seagate ST1000LM035-1RK172 1TB              | 1         | 2.94%   |
| Seagate Expansion+ 2TB                      | 1         | 2.94%   |
| Seagate BarraCuda Q1 SSD ZA480CV10001 480GB | 1         | 2.94%   |
| SanDisk SDSSDA480G 480GB                    | 1         | 2.94%   |
| Samsung SSD 860 EVO 500GB                   | 1         | 2.94%   |
| Samsung NVMe SSD Drive 512GB                | 1         | 2.94%   |
| Samsung MZ7LN128HAHQ-000L2 128GB SSD        | 1         | 2.94%   |
| Samsung MZ7LF192HCGS-000L1 192GB SSD        | 1         | 2.94%   |
| Samsung HD501LJ 500GB                       | 1         | 2.94%   |
| Samsung HD160HJ 160GB                       | 1         | 2.94%   |
| Samsung HD103SJ 1TB                         | 1         | 2.94%   |
| Lexar 120GB SSD                             | 1         | 2.94%   |
| Kingston SA400S37240G 240GB SSD             | 1         | 2.94%   |
| KingSpec P3-128 128GB                       | 1         | 2.94%   |
| Hitachi HTS545025B9A300 250GB               | 1         | 2.94%   |
| Corsair Force LS SSD 64GB                   | 1         | 2.94%   |
| addlink S10 120GB                           | 1         | 2.94%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 8      | 35.29%  |
| Seagate             | 5         | 6      | 29.41%  |
| Samsung Electronics | 2         | 3      | 11.76%  |
| HGST                | 2         | 2      | 11.76%  |
| Toshiba             | 1         | 1      | 5.88%   |
| Hitachi             | 1         | 1      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 25%     |
| Team                | 1         | 1      | 8.33%   |
| SPCC                | 1         | 1      | 8.33%   |
| SK Hynix            | 1         | 1      | 8.33%   |
| Seagate             | 1         | 1      | 8.33%   |
| SanDisk             | 1         | 1      | 8.33%   |
| Lexar               | 1         | 1      | 8.33%   |
| Kingston            | 1         | 1      | 8.33%   |
| KingSpec            | 1         | 1      | 8.33%   |
| Corsair             | 1         | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 15        | 21     | 50%     |
| SSD     | 11        | 12     | 36.67%  |
| NVMe    | 2         | 3      | 6.67%   |
| MMC     | 1         | 1      | 3.33%   |
| Unknown | 1         | 1      | 3.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 24        | 33     | 85.71%  |
| NVMe | 2         | 3      | 7.14%   |
| SAS  | 1         | 1      | 3.57%   |
| MMC  | 1         | 1      | 3.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 18        | 22     | 69.23%  |
| 0.51-1.0   | 6         | 8      | 23.08%  |
| 1.01-2.0   | 2         | 3      | 7.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 11        | 42.31%  |
| 251-500    | 8         | 30.77%  |
| 51-100     | 3         | 11.54%  |
| 21-50      | 2         | 7.69%   |
| 2001-3000  | 1         | 3.85%   |
| 501-1000   | 1         | 3.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 10        | 38.46%  |
| 21-50    | 7         | 26.92%  |
| 51-100   | 6         | 23.08%  |
| 101-250  | 2         | 7.69%   |
| 501-1000 | 1         | 3.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9120822AS 120GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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
| Detected | 18        | 29     | 69.23%  |
| Works    | 7         | 8      | 26.92%  |
| Malfunc  | 1         | 1      | 3.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 20        | 71.43%  |
| AMD                 | 6         | 21.43%  |
| SK Hynix            | 1         | 3.57%   |
| Samsung Electronics | 1         | 3.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 5         | 15.63%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 9.38%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 3         | 9.38%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 6.25%   |
| AMD FCH SATA Controller D                                                        | 2         | 6.25%   |
| SK Hynix BC511                                                                   | 1         | 3.13%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 3.13%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 3.13%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 1         | 3.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 3.13%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 3.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 3.13%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 3.13%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 3.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 3.13%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 3.13%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 3.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 3.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 3.13%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 3.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 3.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 24        | 82.76%  |
| NVMe | 2         | 6.9%    |
| IDE  | 2         | 6.9%    |
| RAID | 1         | 3.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 20        | 76.92%  |
| AMD    | 6         | 23.08%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 3.85%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 3.85%   |
| Intel Core i9-9900 CPU @ 3.10GHz              | 1         | 3.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 3.85%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 3.85%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 3.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 3.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 3.85%   |
| Intel Core i5-6400T CPU @ 2.20GHz             | 1         | 3.85%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 3.85%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 3.85%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 3.85%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 3.85%   |
| Intel Core i3-3227U CPU @ 1.90GHz             | 1         | 3.85%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 1         | 3.85%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz         | 1         | 3.85%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 1         | 3.85%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 3.85%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 3.85%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 3.85%   |
| AMD Ryzen 5 3500X 6-Core Processor            | 1         | 3.85%   |
| AMD C-50 Processor                            | 1         | 3.85%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 3.85%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 3.85%   |
| AMD A8-9600 RADEON R7, 10 COMPUTE CORES 4C+6G | 1         | 3.85%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 1         | 3.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 5         | 19.23%  |
| Intel Core i3     | 4         | 15.38%  |
| Other             | 3         | 11.54%  |
| Intel Core i7     | 3         | 11.54%  |
| Intel Pentium     | 2         | 7.69%   |
| Intel Celeron     | 2         | 7.69%   |
| AMD A8            | 2         | 7.69%   |
| Intel Core i9     | 1         | 3.85%   |
| Intel Core 2 Quad | 1         | 3.85%   |
| Intel Core 2      | 1         | 3.85%   |
| AMD Ryzen 5       | 1         | 3.85%   |
| AMD C-50          | 1         | 3.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 18        | 69.23%  |
| 4      | 5         | 19.23%  |
| 6      | 2         | 7.69%   |
| 8      | 1         | 3.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 26        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 14        | 53.85%  |
| 1      | 12        | 46.15%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 26        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 73.08%  |
| 0x906ea    | 1         | 3.85%   |
| 0x6f6      | 1         | 3.85%   |
| 0x506e3    | 1         | 3.85%   |
| 0x406e3    | 1         | 3.85%   |
| 0x07030105 | 1         | 3.85%   |
| 0x06006705 | 1         | 3.85%   |
| 0x05000029 | 1         | 3.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 4         | 15.38%  |
| Excavator   | 3         | 11.54%  |
| Skylake     | 2         | 7.69%   |
| SandyBridge | 2         | 7.69%   |
| IvyBridge   | 2         | 7.69%   |
| Haswell     | 2         | 7.69%   |
| Broadwell   | 2         | 7.69%   |
| Zen 2       | 1         | 3.85%   |
| Westmere    | 1         | 3.85%   |
| TigerLake   | 1         | 3.85%   |
| Silvermont  | 1         | 3.85%   |
| Puma        | 1         | 3.85%   |
| Penryn      | 1         | 3.85%   |
| Goldmont    | 1         | 3.85%   |
| Core        | 1         | 3.85%   |
| Bobcat      | 1         | 3.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 19        | 55.88%  |
| AMD    | 10        | 29.41%  |
| Nvidia | 5         | 14.71%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 5.26%   |
| Intel HD Graphics 5500                                                                   | 2         | 5.26%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 5.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 5.26%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 5.26%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 5.26%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 2.63%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 2.63%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 2.63%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.63%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 2.63%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 2.63%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 2.63%   |
| Intel HD Graphics 620                                                                    | 1         | 2.63%   |
| Intel HD Graphics 530                                                                    | 1         | 2.63%   |
| Intel HD Graphics 520                                                                    | 1         | 2.63%   |
| Intel HD Graphics 500                                                                    | 1         | 2.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.63%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.63%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 2.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 2.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.63%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 2.63%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 2.63%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 2.63%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 2.63%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 2.63%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 2.63%   |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 1         | 2.63%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 1         | 2.63%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1         | 2.63%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 1         | 2.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 11        | 42.31%  |
| Intel + Nvidia | 4         | 15.38%  |
| 1 x AMD        | 4         | 15.38%  |
| 2 x AMD        | 3         | 11.54%  |
| Intel + AMD    | 3         | 11.54%  |
| 1 x Nvidia     | 1         | 3.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 25        | 96.15%  |
| Proprietary | 1         | 3.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 84.62%  |
| 0.01-0.5   | 3         | 11.54%  |
| 5.01-6.0   | 1         | 3.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 5         | 20.83%  |
| AU Optronics            | 4         | 16.67%  |
| LG Display              | 3         | 12.5%   |
| Chimei Innolux          | 3         | 12.5%   |
| BOE                     | 3         | 12.5%   |
| LG Philips              | 1         | 4.17%   |
| Iiyama                  | 1         | 4.17%   |
| Goldstar                | 1         | 4.17%   |
| Chi Mei Optoelectronics | 1         | 4.17%   |
| Beko                    | 1         | 4.17%   |
| AGO                     | 1         | 4.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch        | 1         | 4%      |
| Samsung Electronics SyncMaster SAM0599 1600x900 443x249mm 20.0-inch      | 1         | 4%      |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch     | 1         | 4%      |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 1         | 4%      |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 4%      |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 1         | 4%      |
| LG Philips LCD Monitor LPL1146 1280x800 331x207mm 15.4-inch              | 1         | 4%      |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 1         | 4%      |
| LG Display LCD Monitor LGD0470 1920x1080 345x194mm 15.6-inch             | 1         | 4%      |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 1         | 4%      |
| Iiyama PLX2380H IVM5621 1920x1080 509x286mm 23.0-inch                    | 1         | 4%      |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                   | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x194mm 15.5-inch          | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 1         | 4%      |
| Chi Mei Optoelectronics LCD Monitor CMO15AB 1366x768 340x190mm 15.3-inch | 1         | 4%      |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 1         | 4%      |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 1         | 4%      |
| BOE LCD Monitor BOE065E 1920x1080 344x194mm 15.5-inch                    | 1         | 4%      |
| Beko BK WUXGA BEK4448 1920x1080 1600x900mm 72.3-inch                     | 1         | 4%      |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 4%      |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 4%      |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 1         | 4%      |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 1         | 4%      |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch                    | 1         | 4%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 11        | 44%     |
| 1920x1080 (FHD)  | 9         | 36%     |
| 1600x900 (HD+)   | 2         | 8%      |
| 3840x2160 (4K)   | 1         | 4%      |
| 1280x800 (WXGA)  | 1         | 4%      |
| 1280x1024 (SXGA) | 1         | 4%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 15        | 60%     |
| 23     | 2         | 8%      |
| 72     | 1         | 4%      |
| 31     | 1         | 4%      |
| 20     | 1         | 4%      |
| 17     | 1         | 4%      |
| 14     | 1         | 4%      |
| 13     | 1         | 4%      |
| 12     | 1         | 4%      |
| 11     | 1         | 4%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 70.83%  |
| 501-600     | 2         | 8.33%   |
| 201-300     | 2         | 8.33%   |
| 601-700     | 1         | 4.17%   |
| 401-500     | 1         | 4.17%   |
| 1501-2000   | 1         | 4.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 21        | 87.5%   |
| 5/4   | 1         | 4.17%   |
| 4/3   | 1         | 4.17%   |
| 16/10 | 1         | 4.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 15        | 60%     |
| 81-90          | 2         | 8%      |
| 201-250        | 2         | 8%      |
| More than 1000 | 1         | 4%      |
| 71-80          | 1         | 4%      |
| 51-60          | 1         | 4%      |
| 351-500        | 1         | 4%      |
| 151-200        | 1         | 4%      |
| 141-150        | 1         | 4%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 9         | 36%     |
| 121-160 | 8         | 32%     |
| 51-100  | 6         | 24%     |
| 1-50    | 1         | 4%      |
| 161-240 | 1         | 4%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 23        | 88.46%  |
| 2     | 2         | 7.69%   |
| 0     | 1         | 3.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 20        | 52.63%  |
| Intel                 | 8         | 21.05%  |
| Qualcomm Atheros      | 4         | 10.53%  |
| Ralink                | 2         | 5.26%   |
| Broadcom              | 2         | 5.26%   |
| JMicron Technology    | 1         | 2.63%   |
| ASUSTek Computer      | 1         | 2.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 31.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 8.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 6.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 4.17%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 4.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 4.17%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 2.08%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.08%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 2.08%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 2.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 2.08%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.08%   |
| Intel Wireless 7265                                               | 1         | 2.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 2.08%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.08%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 2.08%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 2.08%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 2.08%   |
| Intel Centrino Wireless-N 130                                     | 1         | 2.08%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 2.08%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 2.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 2.08%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 2.08%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 2.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 2.08%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                               | 1         | 2.08%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 7         | 30.43%  |
| Intel                 | 7         | 30.43%  |
| Qualcomm Atheros      | 4         | 17.39%  |
| Ralink                | 2         | 8.7%    |
| Broadcom              | 2         | 8.7%    |
| ASUSTek Computer      | 1         | 4.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 3         | 13.04%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 2         | 8.7%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 2         | 8.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 2         | 8.7%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter            | 1         | 4.35%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                  | 1         | 4.35%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                  | 1         | 4.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 4.35%   |
| Intel Wireless 7265                                        | 1         | 4.35%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection      | 1         | 4.35%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1         | 4.35%   |
| Intel Centrino Wireless-N 130                              | 1         | 4.35%   |
| Intel Centrino Ultimate-N 6300                             | 1         | 4.35%   |
| Intel Centrino Advanced-N 6200                             | 1         | 4.35%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 1         | 4.35%   |
| Broadcom BCM43142 802.11b/g/n                              | 1         | 4.35%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 1         | 4.35%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                        | 1         | 4.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 20        | 80%     |
| Intel                 | 4         | 16%     |
| JMicron Technology    | 1         | 4%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 60%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 16%     |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 4%      |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 4%      |
| Intel Ethernet Connection I217-LM                                 | 1         | 4%      |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 4%      |
| Intel Ethernet Connection (3) I218-V                              | 1         | 4%      |
| Intel 82577LC Gigabit Network Connection                          | 1         | 4%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 25        | 53.19%  |
| WiFi     | 22        | 46.81%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 21        | 52.5%   |
| Ethernet | 19        | 47.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 21        | 80.77%  |
| 1     | 5         | 19.23%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 25        | 96.15%  |
| Yes  | 1         | 3.85%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 5         | 26.32%  |
| Intel                           | 4         | 21.05%  |
| Toshiba                         | 2         | 10.53%  |
| Qualcomm Atheros Communications | 2         | 10.53%  |
| IMC Networks                    | 2         | 10.53%  |
| Ralink                          | 1         | 5.26%   |
| Lite-On Technology              | 1         | 5.26%   |
| Foxconn / Hon Hai               | 1         | 5.26%   |
| Broadcom                        | 1         | 5.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Realtek Bluetooth Radio            | 4         | 21.05%  |
| Qualcomm Atheros  Bluetooth Device | 2         | 10.53%  |
| Intel Bluetooth wireless interface | 2         | 10.53%  |
| Intel Bluetooth Device             | 2         | 10.53%  |
| Toshiba RT Bluetooth Radio         | 1         | 5.26%   |
| Toshiba Integrated Bluetooth HCI   | 1         | 5.26%   |
| Realtek RTL8821A Bluetooth         | 1         | 5.26%   |
| Ralink RT3290 Bluetooth            | 1         | 5.26%   |
| Lite-On Atheros AR3012 Bluetooth   | 1         | 5.26%   |
| IMC Networks Bluetooth Radio       | 1         | 5.26%   |
| IMC Networks Bluetooth Device      | 1         | 5.26%   |
| Foxconn / Hon Hai BCM43142A0       | 1         | 5.26%   |
| Broadcom HP Portable Valentine     | 1         | 5.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 68.97%  |
| AMD                   | 7         | 24.14%  |
| Nvidia                | 1         | 3.45%   |
| Barco Display Systems | 1         | 3.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 7.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 7.69%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 7.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 5.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 5.13%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 5.13%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 5.13%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 5.13%   |
| AMD High Definition Audio Controller                                                              | 2         | 5.13%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 2.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 2.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 2.56%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 2.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 2.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 2.56%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 2.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 2.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 2.56%   |
| Barco Display Systems USBGH520-ENC                                                                | 1         | 2.56%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 2.56%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 2.56%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 2.56%   |
| AMD FCH Azalia Controller                                                                         | 1         | 2.56%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 1         | 2.56%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 1         | 2.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 40%     |
| Unknown (0x4509)    | 1         | 10%     |
| Unknown             | 1         | 10%     |
| SK Hynix            | 1         | 10%     |
| Micron Technology   | 1         | 10%     |
| Kingmax             | 1         | 10%     |
| G.Skill             | 1         | 10%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2                              | 1         | 10%     |
| Unknown (0x4509) RAM GKE800SO102408-2666A 8GB SODIMM DDR4 2133MT/s | 1         | 10%     |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s             | 1         | 10%     |
| Samsung RAM M471B5773CHS-CH9 2GB DIMM DDR3 1333MT/s                | 1         | 10%     |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s              | 1         | 10%     |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s           | 1         | 10%     |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s              | 1         | 10%     |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 1         | 10%     |
| Kingmax RAM FSFE85F-C8KL9 2GB DIMM DDR3 1333MT/s                   | 1         | 10%     |
| G.Skill RAM F4-2133C15-4GIS 4GB DIMM DDR4 2133MT/s                 | 1         | 10%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Computers | Percent |
|-------|-----------|---------|
| DDR4  | 6         | 60%     |
| DDR3  | 2         | 20%     |
| SDRAM | 1         | 10%     |
| DDR2  | 1         | 10%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 7         | 77.78%  |
| DIMM   | 2         | 22.22%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Computers | Percent |
|------|-----------|---------|
| 4096 | 5         | 55.56%  |
| 8192 | 2         | 22.22%  |
| 2048 | 2         | 22.22%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2133    | 3         | 33.33%  |
| 2667    | 2         | 22.22%  |
| 3200    | 1         | 11.11%  |
| 1600    | 1         | 11.11%  |
| 1333    | 1         | 11.11%  |
| Unknown | 1         | 11.11%  |

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


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Chicony Electronics         | 8         | 38.1%   |
| Microdia                    | 3         | 14.29%  |
| IMC Networks                | 2         | 9.52%   |
| Acer                        | 2         | 9.52%   |
| Suyin                       | 1         | 4.76%   |
| Silicon Motion              | 1         | 4.76%   |
| Realtek Semiconductor       | 1         | 4.76%   |
| Luxvisions Innotech Limited | 1         | 4.76%   |
| Lite-On Technology          | 1         | 4.76%   |
| Arkmicro Technologies       | 1         | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony EasyCamera                                  | 2         | 9.52%   |
| Acer EasyCamera                                     | 2         | 9.52%   |
| Suyin HP Webcam                                     | 1         | 4.76%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 4.76%   |
| Realtek HP Truevision HD integrated webcam          | 1         | 4.76%   |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 4.76%   |
| Microdia Integrated_Webcam_HD                       | 1         | 4.76%   |
| Microdia Integrated Camera                          | 1         | 4.76%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 4.76%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 4.76%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 4.76%   |
| IMC Networks EasyCamera                             | 1         | 4.76%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 4.76%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 4.76%   |
| Chicony Integrated Camera                           | 1         | 4.76%   |
| Chicony HP Truevision HD                            | 1         | 4.76%   |
| Chicony Front Camera                                | 1         | 4.76%   |
| Chicony CNA7157                                     | 1         | 4.76%   |
| Arkmicro USB2.0 PC CAMERA                           | 1         | 4.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 1         | 50%     |
| AuthenTec        | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 50%     |
| AuthenTec AES1600                            | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 1         | 50%     |
| Advanced Card Systems | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 50%     |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 18        | 66.67%  |
| 1     | 6         | 22.22%  |
| 2     | 3         | 11.11%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 3         | 27.27%  |
| Fingerprint reader       | 2         | 18.18%  |
| Chipcard                 | 2         | 18.18%  |
| Camera                   | 2         | 18.18%  |
| Communication controller | 1         | 9.09%   |
| Bluetooth                | 1         | 9.09%   |

