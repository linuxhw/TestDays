Slackware 14.2 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Slackware 14.2.

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

Total: 39

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Acer     | Extensa 5220                | [30ca0c3efa](https://linux-hardware.org/?probe=30ca0c3efa) | Dec 06, 2022 |
| HP       | Laptop 15-bs2xx             | [bf53c3c878](https://linux-hardware.org/?probe=bf53c3c878) | Jan 02, 2022 |
| Toshiba  | PORTEGE Z30-A               | [13b9ce0773](https://linux-hardware.org/?probe=13b9ce0773) | Sep 22, 2021 |
| Dynabook | PORTEGE X50-G               | [da8279a7a9](https://linux-hardware.org/?probe=da8279a7a9) | Sep 22, 2021 |
| HP       | 15 Notebook PC              | [bec2fe2e78](https://linux-hardware.org/?probe=bec2fe2e78) | Mar 21, 2021 |
| Toshiba  | Satellite C660              | [5189fbc4c9](https://linux-hardware.org/?probe=5189fbc4c9) | Mar 10, 2021 |
| Samsung  | 300E5M/300E5L               | [bda4ee984f](https://linux-hardware.org/?probe=bda4ee984f) | Mar 05, 2021 |
| Dell     | Latitude E5500              | [a8e17b79ce](https://linux-hardware.org/?probe=a8e17b79ce) | Feb 26, 2021 |
| HP       | Pavilion Notebook           | [45dfe3c2b1](https://linux-hardware.org/?probe=45dfe3c2b1) | Feb 24, 2021 |
| Lenovo   | ThinkPad L440 20ASS05K00    | [aecef5c789](https://linux-hardware.org/?probe=aecef5c789) | Jan 22, 2021 |
| Lenovo   | ThinkPad L440 20ASS05K00    | [7a6a06bb55](https://linux-hardware.org/?probe=7a6a06bb55) | Jan 04, 2021 |
| Dell     | Precision M4600             | [71bb8e2e9a](https://linux-hardware.org/?probe=71bb8e2e9a) | Dec 28, 2020 |
| Lenovo   | ThinkPad L440 20ASS05K00    | [b330b2d38a](https://linux-hardware.org/?probe=b330b2d38a) | Nov 19, 2020 |
| MSI      | GL73 8RC                    | [44f82bfc01](https://linux-hardware.org/?probe=44f82bfc01) | Nov 09, 2020 |
| Lenovo   | ThinkPad L440 20ASS05K00    | [a4cb1ecf16](https://linux-hardware.org/?probe=a4cb1ecf16) | Nov 08, 2020 |
| Samsung  | 300E5M/300E5L               | [270b65ced8](https://linux-hardware.org/?probe=270b65ced8) | Jul 24, 2020 |
| Notebook | NL40_50CU                   | [941073da73](https://linux-hardware.org/?probe=941073da73) | Jun 27, 2020 |
| Lenovo   | V330-14ARR 81B1             | [5089cbcf84](https://linux-hardware.org/?probe=5089cbcf84) | Jun 24, 2020 |
| Lenovo   | V330-14ARR 81B1             | [cb63994f94](https://linux-hardware.org/?probe=cb63994f94) | Jun 22, 2020 |
| Notebook | NL40_50CU                   | [9a1c09c6e1](https://linux-hardware.org/?probe=9a1c09c6e1) | Mar 28, 2020 |
| Notebook | NL40_50CU                   | [bc5ed8dea4](https://linux-hardware.org/?probe=bc5ed8dea4) | Mar 24, 2020 |
| Notebook | NL40_50CU                   | [ae7070b067](https://linux-hardware.org/?probe=ae7070b067) | Mar 21, 2020 |
| Notebook | NL40_50CU                   | [320dada481](https://linux-hardware.org/?probe=320dada481) | Mar 20, 2020 |
| Toshiba  | Satellite P50-A-12Z         | [96927db16b](https://linux-hardware.org/?probe=96927db16b) | Mar 17, 2020 |
| Lenovo   | ThinkPad X1 Carbon 7th 2... | [afe3135216](https://linux-hardware.org/?probe=afe3135216) | Dec 10, 2019 |
| ASUSTek  | P53E                        | [e9dcced0f7](https://linux-hardware.org/?probe=e9dcced0f7) | Oct 28, 2019 |
| Lenovo   | ThinkPad T400 6474BV7       | [825bdb9fd0](https://linux-hardware.org/?probe=825bdb9fd0) | Oct 28, 2019 |
| ASUSTek  | 1000H                       | [50da35c0d0](https://linux-hardware.org/?probe=50da35c0d0) | Oct 28, 2019 |
| Acer     | Aspire E1-572               | [0fe80f5758](https://linux-hardware.org/?probe=0fe80f5758) | Oct 23, 2019 |
| ASUSTek  | VivoBook_ASUSLaptop X570... | [ecca7bced0](https://linux-hardware.org/?probe=ecca7bced0) | Oct 22, 2019 |
| Acer     | Swift SF314-52              | [05f880ecec](https://linux-hardware.org/?probe=05f880ecec) | Oct 21, 2019 |
| Lenovo   | ThinkPad P70 20ERCTO1WW     | [0ceeb50e5e](https://linux-hardware.org/?probe=0ceeb50e5e) | Oct 21, 2019 |
| Lenovo   | ThinkPad T450s 20BW000EU... | [41ca8d1a20](https://linux-hardware.org/?probe=41ca8d1a20) | Oct 21, 2019 |
| ASUSTek  | VivoBook_ASUSLaptop X570... | [c2fd6acb71](https://linux-hardware.org/?probe=c2fd6acb71) | Oct 21, 2019 |
| Dell     | Latitude E7270              | [859e021e2f](https://linux-hardware.org/?probe=859e021e2f) | Oct 20, 2019 |
| Fujitsu  | LIFEBOOK A555               | [e0c6729d5b](https://linux-hardware.org/?probe=e0c6729d5b) | Oct 20, 2019 |
| Lenovo   | ThinkPad T470 20HDCTO1WW    | [0f9287651d](https://linux-hardware.org/?probe=0f9287651d) | Jul 24, 2019 |
| Lenovo   | ThinkPad T470 20HDCTO1WW    | [67672ef038](https://linux-hardware.org/?probe=67672ef038) | Jul 23, 2019 |
| Fujitsu  | LIFEBOOK A555               | [63c120aa28](https://linux-hardware.org/?probe=63c120aa28) | Aug 19, 2018 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 4.19.80           | 3         | 9.68%   |
| 5.3.7             | 2         | 6.45%   |
| 4.4.276           | 2         | 6.45%   |
| 5.7.0             | 1         | 3.23%   |
| 5.5.10            | 1         | 3.23%   |
| 5.4.75            | 1         | 3.23%   |
| 5.4.50            | 1         | 3.23%   |
| 5.4.47            | 1         | 3.23%   |
| 5.4.24toshiba-new | 1         | 3.23%   |
| 5.4.2             | 1         | 3.23%   |
| 5.4.13            | 1         | 3.23%   |
| 5.2.2             | 1         | 3.23%   |
| 5.13.0.a          | 1         | 3.23%   |
| 5.10.4            | 1         | 3.23%   |
| 5.10.3            | 1         | 3.23%   |
| 5.10.21           | 1         | 3.23%   |
| 5.10.19           | 1         | 3.23%   |
| 4.4.88            | 1         | 3.23%   |
| 4.4.240           | 1         | 3.23%   |
| 4.4.227           | 1         | 3.23%   |
| 4.4.202           | 1         | 3.23%   |
| 4.4.190-smp       | 1         | 3.23%   |
| 4.4.190           | 1         | 3.23%   |
| 4.19.79           | 1         | 3.23%   |
| 4.19.76           | 1         | 3.23%   |
| 4.19.206.a        | 1         | 3.23%   |
| 4.16.18           | 1         | 3.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.19.80  | 3         | 9.68%   |
| 5.3.7    | 2         | 6.45%   |
| 4.4.276  | 2         | 6.45%   |
| 4.4.190  | 2         | 6.45%   |
| 5.7.0    | 1         | 3.23%   |
| 5.5.10   | 1         | 3.23%   |
| 5.4.75   | 1         | 3.23%   |
| 5.4.50   | 1         | 3.23%   |
| 5.4.47   | 1         | 3.23%   |
| 5.4.24   | 1         | 3.23%   |
| 5.4.2    | 1         | 3.23%   |
| 5.4.13   | 1         | 3.23%   |
| 5.2.2    | 1         | 3.23%   |
| 5.13.0   | 1         | 3.23%   |
| 5.10.4   | 1         | 3.23%   |
| 5.10.3   | 1         | 3.23%   |
| 5.10.21  | 1         | 3.23%   |
| 5.10.19  | 1         | 3.23%   |
| 4.4.88   | 1         | 3.23%   |
| 4.4.240  | 1         | 3.23%   |
| 4.4.227  | 1         | 3.23%   |
| 4.4.202  | 1         | 3.23%   |
| 4.19.79  | 1         | 3.23%   |
| 4.19.76  | 1         | 3.23%   |
| 4.19.206 | 1         | 3.23%   |
| 4.16.18  | 1         | 3.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.4     | 8         | 25.81%  |
| 5.4     | 6         | 19.35%  |
| 4.19    | 6         | 19.35%  |
| 5.10    | 4         | 12.9%   |
| 5.3     | 2         | 6.45%   |
| 5.7     | 1         | 3.23%   |
| 5.5     | 1         | 3.23%   |
| 5.2     | 1         | 3.23%   |
| 5.13    | 1         | 3.23%   |
| 4.16    | 1         | 3.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 26        | 96.3%   |
| i686   | 1         | 3.7%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Unknown       | 12        | 42.86%  |
| XFCE          | 11        | 39.29%  |
| KDE           | 2         | 7.14%   |
| LXQt          | 1         | 3.57%   |
| KDE5          | 1         | 3.57%   |
| Enlightenment | 1         | 3.57%   |

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


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 16        | 57.14%  |
| XDM     | 9         | 32.14%  |
| SDDM    | 3         | 10.71%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 12        | 44.44%  |
| en_US   | 11        | 40.74%  |
| ru_RU   | 1         | 3.7%    |
| pt_BR   | 1         | 3.7%    |
| pl_PL   | 1         | 3.7%    |
| fr_FR   | 1         | 3.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 19        | 67.86%  |
| EFI  | 9         | 32.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 25        | 92.59%  |
| Btrfs | 2         | 7.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 15        | 53.57%  |
| MBR     | 10        | 35.71%  |
| Unknown | 3         | 10.71%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 85.71%  |
| Yes       | 4         | 14.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 20        | 74.07%  |
| Yes       | 7         | 25.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 7         | 25.93%  |
| Toshiba             | 3         | 11.11%  |
| Hewlett-Packard     | 3         | 11.11%  |
| Dell                | 3         | 11.11%  |
| ASUSTek Computer    | 3         | 11.11%  |
| Acer                | 3         | 11.11%  |
| Samsung Electronics | 1         | 3.7%    |
| Notebook            | 1         | 3.7%    |
| MSI                 | 1         | 3.7%    |
| Fujitsu             | 1         | 3.7%    |
| Dynabook            | 1         | 3.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Toshiba Satellite P50-A-12Z              | 1         | 3.7%    |
| Toshiba Satellite C660                   | 1         | 3.7%    |
| Toshiba PORTEGE Z30-A                    | 1         | 3.7%    |
| Samsung 300E5M/300E5L                    | 1         | 3.7%    |
| Notebook NL40_50CU                       | 1         | 3.7%    |
| MSI GL73 8RC                             | 1         | 3.7%    |
| Lenovo V330-14ARR 81B1                   | 1         | 3.7%    |
| Lenovo ThinkPad X1 Carbon 7th 20R10015US | 1         | 3.7%    |
| Lenovo ThinkPad T470 20HDCTO1WW          | 1         | 3.7%    |
| Lenovo ThinkPad T450s 20BW000EUS         | 1         | 3.7%    |
| Lenovo ThinkPad T400 6474BV7             | 1         | 3.7%    |
| Lenovo ThinkPad P70 20ERCTO1WW           | 1         | 3.7%    |
| Lenovo ThinkPad L440 20ASS05K00          | 1         | 3.7%    |
| HP Pavilion Notebook                     | 1         | 3.7%    |
| HP Laptop 15-bs2xx                       | 1         | 3.7%    |
| HP 15 Notebook PC                        | 1         | 3.7%    |
| Fujitsu LIFEBOOK A555                    | 1         | 3.7%    |
| Dynabook PORTEGE X50-G                   | 1         | 3.7%    |
| Dell Precision M4600                     | 1         | 3.7%    |
| Dell Latitude E7270                      | 1         | 3.7%    |
| Dell Latitude E5500                      | 1         | 3.7%    |
| ASUS VivoBook_ASUSLaptop X570ZD_K570ZD   | 1         | 3.7%    |
| ASUS P53E                                | 1         | 3.7%    |
| ASUS 1000H                               | 1         | 3.7%    |
| Acer Swift SF314-52                      | 1         | 3.7%    |
| Acer Extensa 5220                        | 1         | 3.7%    |
| Acer Aspire E1-572                       | 1         | 3.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 6         | 22.22%  |
| Toshiba Satellite | 2         | 7.41%   |
| Dell Latitude     | 2         | 7.41%   |
| Toshiba PORTEGE   | 1         | 3.7%    |
| Samsung 300E5M    | 1         | 3.7%    |
| Notebook NL40     | 1         | 3.7%    |
| MSI GL73          | 1         | 3.7%    |
| Lenovo V330-14ARR | 1         | 3.7%    |
| HP Pavilion       | 1         | 3.7%    |
| HP Laptop         | 1         | 3.7%    |
| HP 15             | 1         | 3.7%    |
| Fujitsu LIFEBOOK  | 1         | 3.7%    |
| Dynabook PORTEGE  | 1         | 3.7%    |
| Dell Precision    | 1         | 3.7%    |
| ASUS VivoBook     | 1         | 3.7%    |
| ASUS P53E         | 1         | 3.7%    |
| ASUS 1000H        | 1         | 3.7%    |
| Acer Swift        | 1         | 3.7%    |
| Acer Extensa      | 1         | 3.7%    |
| Acer Aspire       | 1         | 3.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 4         | 14.81%  |
| 2015 | 4         | 14.81%  |
| 2017 | 3         | 11.11%  |
| 2014 | 3         | 11.11%  |
| 2008 | 3         | 11.11%  |
| 2018 | 2         | 7.41%   |
| 2016 | 2         | 7.41%   |
| 2011 | 2         | 7.41%   |
| 2020 | 1         | 3.7%    |
| 2013 | 1         | 3.7%    |
| 2010 | 1         | 3.7%    |
| 2007 | 1         | 3.7%    |

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
| Disabled | 27        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 26        | 96.3%   |
| Yes  | 1         | 3.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 8         | 29.63%  |
| 3.01-4.0   | 6         | 22.22%  |
| 8.01-16.0  | 5         | 18.52%  |
| 16.01-24.0 | 4         | 14.81%  |
| 1.01-2.0   | 2         | 7.41%   |
| 32.01-64.0 | 1         | 3.7%    |
| 0.51-1.0   | 1         | 3.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 12        | 42.86%  |
| 2.01-3.0  | 6         | 21.43%  |
| 3.01-4.0  | 4         | 14.29%  |
| 4.01-8.0  | 2         | 7.14%   |
| 0.51-1.0  | 2         | 7.14%   |
| 8.01-16.0 | 1         | 3.57%   |
| 0.01-0.5  | 1         | 3.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 19        | 67.86%  |
| 2      | 7         | 25%     |
| 3      | 1         | 3.57%   |
| 0      | 1         | 3.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 19        | 70.37%  |
| Yes       | 8         | 29.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 92.59%  |
| No        | 2         | 7.41%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 81.48%  |
| No        | 5         | 18.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 4         | 14.81%  |
| UK          | 3         | 11.11%  |
| Portugal    | 3         | 11.11%  |
| Russia      | 2         | 7.41%   |
| Poland      | 2         | 7.41%   |
| India       | 2         | 7.41%   |
| Canada      | 2         | 7.41%   |
| Brazil      | 2         | 7.41%   |
| Sweden      | 1         | 3.7%    |
| Philippines | 1         | 3.7%    |
| Italy       | 1         | 3.7%    |
| Germany     | 1         | 3.7%    |
| France      | 1         | 3.7%    |
| Finland     | 1         | 3.7%    |
| Chile       | 1         | 3.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Warsaw                 | 2         | 6.9%    |
| Lisbon                 | 2         | 6.9%    |
| Wokingham              | 1         | 3.45%   |
| Winnipeg               | 1         | 3.45%   |
| Voskresensk            | 1         | 3.45%   |
| Visconde do Rio Branco | 1         | 3.45%   |
| Roknaes                | 1         | 3.45%   |
| Redding                | 1         | 3.45%   |
| Puente Alto            | 1         | 3.45%   |
| Pinhal Novo            | 1         | 3.45%   |
| Pesaro                 | 1         | 3.45%   |
| Pasay                  | 1         | 3.45%   |
| Paris                  | 1         | 3.45%   |
| Northport              | 1         | 3.45%   |
| Milan                  | 1         | 3.45%   |
| Lins                   | 1         | 3.45%   |
| Kstovo                 | 1         | 3.45%   |
| Jaipur                 | 1         | 3.45%   |
| Hornsey                | 1         | 3.45%   |
| Helsinki               | 1         | 3.45%   |
| Faridabad              | 1         | 3.45%   |
| Carrollton             | 1         | 3.45%   |
| Canandaigua            | 1         | 3.45%   |
| Borken                 | 1         | 3.45%   |
| Bengaluru              | 1         | 3.45%   |
| Barry                  | 1         | 3.45%   |
| Barrie                 | 1         | 3.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 8      | 21.21%  |
| WDC                 | 5         | 7      | 15.15%  |
| Seagate             | 4         | 4      | 12.12%  |
| Crucial             | 3         | 4      | 9.09%   |
| Unknown             | 2         | 2      | 6.06%   |
| Toshiba             | 2         | 2      | 6.06%   |
| Kingston            | 2         | 2      | 6.06%   |
| SanDisk             | 1         | 1      | 3.03%   |
| Patriot             | 1         | 2      | 3.03%   |
| Netac               | 1         | 1      | 3.03%   |
| Micron Technology   | 1         | 1      | 3.03%   |
| Intel               | 1         | 1      | 3.03%   |
| HGST                | 1         | 1      | 3.03%   |
| Gigabyte Technology | 1         | 1      | 3.03%   |
| Dogfish             | 1         | 1      | 3.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| WDC WD5000LPCX-60VHAT1 500GB         | 1         | 2.94%   |
| WDC WD10JPVX-35JC3T0 1TB             | 1         | 2.94%   |
| WDC WD10JPVX-16JC3T3 1TB             | 1         | 2.94%   |
| WDC WD10JPLX-00MBPT0 1TB             | 1         | 2.94%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB | 1         | 2.94%   |
| Unknown SD32G  32GB                  | 1         | 2.94%   |
| Unknown SC32G  32GB                  | 1         | 2.94%   |
| Toshiba MK2565GSXN 250GB             | 1         | 2.94%   |
| Toshiba MK1646GSX 160GB              | 1         | 2.94%   |
| Seagate ST9160827AS 160GB            | 1         | 2.94%   |
| Seagate ST9160412AS 160GB            | 1         | 2.94%   |
| Seagate ST500VT000-1DK142 500GB      | 1         | 2.94%   |
| Seagate ST1000LM048-2E7172 1TB       | 1         | 2.94%   |
| SanDisk SD8TN8U256G1001 256GB SSD    | 1         | 2.94%   |
| Samsung SSD 970 EVO Plus 250GB       | 1         | 2.94%   |
| Samsung SSD 860 QVO 2TB              | 1         | 2.94%   |
| Samsung SSD 840 EVO 250GB            | 1         | 2.94%   |
| Samsung MZVLB512HAJQ-000L7 512GB     | 1         | 2.94%   |
| Samsung MZVLB1T0HBLR-00007 1TB       | 1         | 2.94%   |
| Samsung MZMTE256HMHP-00000 256GB SSD | 1         | 2.94%   |
| Samsung MZ7LN256HAJQ-000L2 256GB SSD | 1         | 2.94%   |
| Patriot Burst 960GB SSD              | 1         | 2.94%   |
| Patriot Burst 120GB SSD              | 1         | 2.94%   |
| Netac SSD 720GB                      | 1         | 2.94%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 1         | 2.94%   |
| Kingston SA400S37240G 240GB SSD      | 1         | 2.94%   |
| Kingston RBUSNS8154P3128GJ 128GB     | 1         | 2.94%   |
| Intel SSDPEKKF010T8L 1TB             | 1         | 2.94%   |
| HGST HTS541010A9E680 1TB             | 1         | 2.94%   |
| Gigabyte GP-GSM2NE8128GNTD 128GB     | 1         | 2.94%   |
| Dogfish SSD 256G                     | 1         | 2.94%   |
| Crucial CT500MX200SSD1 500GB         | 1         | 2.94%   |
| Crucial CT480BX500SSD1 480GB         | 1         | 2.94%   |
| Crucial CT120BX500SSD1 120GB         | 1         | 2.94%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 6      | 36.36%  |
| Seagate | 4         | 4      | 36.36%  |
| Toshiba | 2         | 2      | 18.18%  |
| HGST    | 1         | 1      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 30.77%  |
| Crucial             | 3         | 4      | 23.08%  |
| SanDisk             | 1         | 1      | 7.69%   |
| Patriot             | 1         | 2      | 7.69%   |
| Netac               | 1         | 1      | 7.69%   |
| Micron Technology   | 1         | 1      | 7.69%   |
| Kingston            | 1         | 1      | 7.69%   |
| Dogfish             | 1         | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 12        | 15     | 37.5%   |
| HDD  | 11        | 13     | 34.38%  |
| NVMe | 7         | 8      | 21.88%  |
| MMC  | 2         | 2      | 6.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 20        | 28     | 68.97%  |
| NVMe | 7         | 8      | 24.14%  |
| MMC  | 2         | 2      | 6.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 15        | 18     | 65.22%  |
| 0.51-1.0   | 7         | 9      | 30.43%  |
| 1.01-2.0   | 1         | 1      | 4.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 9         | 33.33%  |
| 251-500    | 7         | 25.93%  |
| 501-1000   | 7         | 25.93%  |
| 1001-2000  | 2         | 7.41%   |
| 1-20       | 1         | 3.7%    |
| 51-100     | 1         | 3.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 21-50    | 7         | 23.33%  |
| 1-20     | 7         | 23.33%  |
| 51-100   | 6         | 20%     |
| 501-1000 | 5         | 16.67%  |
| 251-500  | 3         | 10%     |
| 101-250  | 2         | 6.67%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                        | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT1 500GB | 1         | 1      | 33.33%  |
| WDC WD10JPLX-00MBPT0 1TB     | 1         | 1      | 33.33%  |
| Toshiba MK2565GSXN 250GB     | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 66.67%  |
| Toshiba | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 66.67%  |
| Toshiba | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 100%    |

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
| Works    | 20        | 29     | 68.97%  |
| Detected | 6         | 6      | 20.69%  |
| Malfunc  | 3         | 3      | 10.34%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 23        | 74.19%  |
| Samsung Electronics         | 3         | 9.68%   |
| AMD                         | 2         | 6.45%   |
| SanDisk                     | 1         | 3.23%   |
| Phison Electronics          | 1         | 3.23%   |
| Kingston Technology Company | 1         | 3.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 9.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 9.09%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 6.06%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 6.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 6.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 6.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 6.06%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 2         | 6.06%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 3.03%   |
| Phison NVMe Storage Controller                                                   | 1         | 3.03%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 3.03%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 3.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 3.03%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 3.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 3.03%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 3.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 3.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 3.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 3.03%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 3.03%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1         | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                       | 1         | 3.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 3.03%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 22        | 66.67%  |
| NVMe | 7         | 21.21%  |
| IDE  | 3         | 9.09%   |
| RAID | 1         | 3.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 25        | 92.59%  |
| AMD    | 2         | 7.41%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 7.41%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 3.7%    |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 3.7%    |
| Intel CPU Version                             | 1         | 3.7%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 3.7%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 3.7%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 3.7%    |
| Intel Core i7-2860QM CPU @ 2.50GHz            | 1         | 3.7%    |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 3.7%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 3.7%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 3.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 3.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 3.7%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 3.7%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 3.7%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 3.7%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 3.7%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 3.7%    |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 3.7%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 3.7%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 3.7%    |
| Intel Core i3-4000M CPU @ 2.40GHz             | 1         | 3.7%    |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 1         | 3.7%    |
| Intel Core 2 CPU P8400 @ 2.26GHz              | 1         | 3.7%    |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 3.7%    |
| Intel Atom CPU N270 @ 1.60GHz                 | 1         | 3.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 8         | 29.63%  |
| Intel Core i7    | 6         | 22.22%  |
| Intel Core i3    | 4         | 14.81%  |
| Intel Pentium    | 2         | 7.41%   |
| AMD Ryzen 5      | 2         | 7.41%   |
| Other            | 1         | 3.7%    |
| Intel Core 2 Duo | 1         | 3.7%    |
| Intel Core 2     | 1         | 3.7%    |
| Intel Celeron    | 1         | 3.7%    |
| Intel Atom       | 1         | 3.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 14        | 51.85%  |
| 4      | 10        | 37.04%  |
| 1      | 2         | 7.41%   |
| 6      | 1         | 3.7%    |

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
| 2      | 21        | 77.78%  |
| 1      | 6         | 22.22%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 24        | 88.89%  |
| Unknown        | 2         | 7.41%   |
| 32-bit         | 1         | 3.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 6         | 22.22%  |
| 0x806ec    | 2         | 7.41%   |
| 0x406e3    | 2         | 7.41%   |
| 0x306d4    | 2         | 7.41%   |
| 0x206a7    | 2         | 7.41%   |
| 0xa0660    | 1         | 3.7%    |
| 0x806ea    | 1         | 3.7%    |
| 0x806e9    | 1         | 3.7%    |
| 0x706a1    | 1         | 3.7%    |
| 0x6fd      | 1         | 3.7%    |
| 0x506e3    | 1         | 3.7%    |
| 0x40651    | 1         | 3.7%    |
| 0x306c3    | 1         | 3.7%    |
| 0x20655    | 1         | 3.7%    |
| 0x106c2    | 1         | 3.7%    |
| 0x1067a    | 1         | 3.7%    |
| 0x10661    | 1         | 3.7%    |
| 0x0810100b | 1         | 3.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 5         | 18.52%  |
| Skylake       | 4         | 14.81%  |
| Haswell       | 4         | 14.81%  |
| Zen           | 2         | 7.41%   |
| SandyBridge   | 2         | 7.41%   |
| Core          | 2         | 7.41%   |
| Broadwell     | 2         | 7.41%   |
| Westmere      | 1         | 3.7%    |
| Silvermont    | 1         | 3.7%    |
| Penryn        | 1         | 3.7%    |
| Goldmont plus | 1         | 3.7%    |
| CometLake     | 1         | 3.7%    |
| Bonnell       | 1         | 3.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 24        | 77.42%  |
| Nvidia | 5         | 16.13%  |
| AMD    | 2         | 6.45%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 9.09%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 6.06%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 6.06%   |
| Intel HD Graphics 5500                                                                   | 2         | 6.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 6.06%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 6.06%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 6.06%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 6.06%   |
| Nvidia GM204GLM [Quadro M3000M]                                                          | 1         | 3.03%   |
| Nvidia GK107M [GeForce GT 745M]                                                          | 1         | 3.03%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 3.03%   |
| Intel UHD Graphics 620                                                                   | 1         | 3.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 3.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 3.03%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 3.03%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 3.03%   |
| Intel HD Graphics 620                                                                    | 1         | 3.03%   |
| Intel HD Graphics 530                                                                    | 1         | 3.03%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 3.03%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 3.03%   |
| Intel Comet Lake UHD Graphics                                                            | 1         | 3.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 3.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 3.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 3.03%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 21        | 77.78%  |
| Intel + Nvidia | 3         | 11.11%  |
| 1 x Nvidia     | 1         | 3.7%    |
| AMD + Nvidia   | 1         | 3.7%    |
| 1 x AMD        | 1         | 3.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 26        | 96.3%   |
| Unknown | 1         | 3.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 67.86%  |
| 1.01-2.0   | 4         | 14.29%  |
| 3.01-4.0   | 2         | 7.14%   |
| 0.01-0.5   | 2         | 7.14%   |
| 0.51-1.0   | 1         | 3.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 7         | 25%     |
| LG Display          | 6         | 21.43%  |
| AU Optronics        | 5         | 17.86%  |
| Samsung Electronics | 3         | 10.71%  |
| BOE                 | 3         | 10.71%  |
| Sharp               | 1         | 3.57%   |
| Panasonic           | 1         | 3.57%   |
| Lenovo              | 1         | 3.57%   |
| Goldstar            | 1         | 3.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 2         | 7.14%   |
| Sharp LCD Monitor SHP14C4 1920x1080 344x194mm 15.5-inch              | 1         | 3.57%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch | 1         | 3.57%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch | 1         | 3.57%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 1         | 3.57%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch          | 1         | 3.57%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 1         | 3.57%   |
| LG Display LCD Monitor LGD0508 1366x768 309x174mm 14.0-inch          | 1         | 3.57%   |
| LG Display LCD Monitor LGD03D7 1366x768 309x174mm 14.0-inch          | 1         | 3.57%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch          | 1         | 3.57%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch          | 1         | 3.57%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch         | 1         | 3.57%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch              | 1         | 3.57%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN15CC 1366x768 344x193mm 15.5-inch      | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch      | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN1355 1366x768 293x165mm 13.2-inch      | 1         | 3.57%   |
| BOE LCD Monitor BOE07C8 3840x2160 309x174mm 14.0-inch                | 1         | 3.57%   |
| BOE LCD Monitor BOE0703 1920x1080 344x194mm 15.5-inch                | 1         | 3.57%   |
| BOE LCD Monitor BOE0690 1920x1080 344x193mm 15.5-inch                | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch        | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO30ED 1920x1080 344x193mm 15.5-inch       | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO2074 1280x800 331x207mm 15.4-inch        | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 1         | 3.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 11        | 39.29%  |
| 1920x1080 (FHD)    | 10        | 35.71%  |
| 3840x2160 (4K)     | 2         | 7.14%   |
| 1600x900 (HD+)     | 2         | 7.14%   |
| 1280x800 (WXGA)    | 2         | 7.14%   |
| 1680x1050 (WSXGA+) | 1         | 3.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 13        | 46.43%  |
| 14     | 6         | 21.43%  |
| 13     | 4         | 14.29%  |
| 17     | 2         | 7.14%   |
| 21     | 1         | 3.57%   |
| 20     | 1         | 3.57%   |
| 12     | 1         | 3.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 21        | 75%     |
| 351-400     | 3         | 10.71%  |
| 401-500     | 2         | 7.14%   |
| 201-300     | 2         | 7.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 24        | 88.89%  |
| 16/10 | 2         | 7.41%   |
| 3/2   | 1         | 3.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 13        | 46.43%  |
| 81-90          | 9         | 32.14%  |
| 121-130        | 2         | 7.14%   |
| 71-80          | 1         | 3.57%   |
| 61-70          | 1         | 3.57%   |
| 201-250        | 1         | 3.57%   |
| 151-200        | 1         | 3.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 12        | 42.86%  |
| 101-120       | 9         | 32.14%  |
| 51-100        | 5         | 17.86%  |
| More than 240 | 2         | 7.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 25        | 92.59%  |
| 2     | 2         | 7.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 43.48%  |
| Realtek Semiconductor | 10        | 21.74%  |
| Qualcomm Atheros      | 8         | 17.39%  |
| Broadcom              | 3         | 6.52%   |
| Sierra Wireless       | 1         | 2.17%   |
| Ralink Technology     | 1         | 2.17%   |
| Dell                  | 1         | 2.17%   |
| Broadcom Limited      | 1         | 2.17%   |
| ASIX Electronics      | 1         | 2.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 5         | 8.93%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 4         | 7.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 3.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                             | 2         | 3.57%   |
| Intel Wireless-AC 9260                                                                | 2         | 3.57%   |
| Intel Wireless 8265 / 8275                                                            | 2         | 3.57%   |
| Intel Wireless 8260                                                                   | 2         | 3.57%   |
| Intel Wireless 7265                                                                   | 2         | 3.57%   |
| Intel Wireless 7260                                                                   | 2         | 3.57%   |
| Intel Wireless 3160                                                                   | 2         | 3.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 2         | 3.57%   |
| Sierra Wireless EM7305                                                                | 1         | 1.79%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 1.79%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 1.79%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 1.79%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 1.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 1.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1         | 1.79%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                        | 1         | 1.79%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.79%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 1.79%   |
| Intel WiFi Link 5100                                                                  | 1         | 1.79%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 1.79%   |
| Intel Ethernet Connection I219-LM                                                     | 1         | 1.79%   |
| Intel Ethernet Connection I218-V                                                      | 1         | 1.79%   |
| Intel Ethernet Connection I217-V                                                      | 1         | 1.79%   |
| Intel Ethernet Connection (4) I219-V                                                  | 1         | 1.79%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 1         | 1.79%   |
| Intel Ethernet Connection (2) I219-LM                                                 | 1         | 1.79%   |
| Intel Ethernet Connection (10) I219-V                                                 | 1         | 1.79%   |
| Intel Centrino Ultimate-N 6300                                                        | 1         | 1.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 1         | 1.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 1         | 1.79%   |
| Intel 82567LM Gigabit Network Connection                                              | 1         | 1.79%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                                  | 1         | 1.79%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                                     | 1         | 1.79%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                                | 1         | 1.79%   |
| Broadcom Limited NetXtreme BCM5756ME Gigabit Ethernet PCI Express                     | 1         | 1.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 1.79%   |
| ASIX AX88772B                                                                         | 1         | 1.79%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 18        | 60%     |
| Qualcomm Atheros      | 6         | 20%     |
| Realtek Semiconductor | 2         | 6.67%   |
| Sierra Wireless       | 1         | 3.33%   |
| Ralink Technology     | 1         | 3.33%   |
| Dell                  | 1         | 3.33%   |
| Broadcom              | 1         | 3.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 6.67%   |
| Intel Wireless-AC 9260                                                                | 2         | 6.67%   |
| Intel Wireless 8265 / 8275                                                            | 2         | 6.67%   |
| Intel Wireless 8260                                                                   | 2         | 6.67%   |
| Intel Wireless 7265                                                                   | 2         | 6.67%   |
| Intel Wireless 7260                                                                   | 2         | 6.67%   |
| Intel Wireless 3160                                                                   | 2         | 6.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 2         | 6.67%   |
| Sierra Wireless EM7305                                                                | 1         | 3.33%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 3.33%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 3.33%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 3.33%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 3.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 3.33%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 3.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 3.33%   |
| Intel WiFi Link 5100                                                                  | 1         | 3.33%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 3.33%   |
| Intel Centrino Ultimate-N 6300                                                        | 1         | 3.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 1         | 3.33%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                                  | 1         | 3.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 3.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 9         | 34.62%  |
| Intel                 | 9         | 34.62%  |
| Qualcomm Atheros      | 4         | 15.38%  |
| Broadcom              | 2         | 7.69%   |
| Broadcom Limited      | 1         | 3.85%   |
| ASIX Electronics      | 1         | 3.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 19.23%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 15.38%  |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 7.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 3.85%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 3.85%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 3.85%   |
| Intel Ethernet Connection I218-V                                  | 1         | 3.85%   |
| Intel Ethernet Connection I217-V                                  | 1         | 3.85%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 3.85%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 3.85%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 3.85%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 3.85%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 3.85%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 3.85%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 3.85%   |
| Broadcom Limited NetXtreme BCM5756ME Gigabit Ethernet PCI Express | 1         | 3.85%   |
| ASIX AX88772B                                                     | 1         | 3.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 51.92%  |
| Ethernet | 25        | 48.08%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 17        | 68%     |
| Ethernet | 8         | 32%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 23        | 85.19%  |
| 1     | 2         | 7.41%   |
| 0     | 2         | 7.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 27        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 16        | 72.73%  |
| Qualcomm Atheros Communications | 3         | 13.64%  |
| Toshiba                         | 1         | 4.55%   |
| Realtek Semiconductor           | 1         | 4.55%   |
| Cambridge Silicon Radio         | 1         | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 10        | 45.45%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 13.64%  |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 9.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 9.09%   |
| Toshiba Askey Bluetooth Module                      | 1         | 4.55%   |
| Realtek Bluetooth Radio                             | 1         | 4.55%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 4.55%   |
| Intel AX201 Bluetooth                               | 1         | 4.55%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel             | 25        | 83.33%  |
| Nvidia            | 2         | 6.67%   |
| AMD               | 2         | 6.67%   |
| Texas Instruments | 1         | 3.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 13.16%  |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 7.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 5.26%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 5.26%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 5.26%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 5.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 5.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 5.26%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 5.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 5.26%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 5.26%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 2.63%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 2.63%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 2.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 2.63%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 2.63%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 2.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.63%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 2.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 2.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 9         | 33.33%  |
| Samsung Electronics | 7         | 25.93%  |
| Unknown             | 2         | 7.41%   |
| Micron Technology   | 2         | 7.41%   |
| Kingston            | 2         | 7.41%   |
| Smart               | 1         | 3.7%    |
| Ramaxel Technology  | 1         | 3.7%    |
| Elpida              | 1         | 3.7%    |
| Crucial             | 1         | 3.7%    |
| Corsair             | 1         | 3.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6AFR6N-UH 2GB SODIMM LPDDR4 2667MT/s  | 2         | 7.41%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                    | 1         | 3.7%    |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s             | 1         | 3.7%    |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s     | 1         | 3.7%    |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s   | 1         | 3.7%    |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s           | 1         | 3.7%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s     | 1         | 3.7%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 3.7%    |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 3.7%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 1         | 3.7%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s    | 1         | 3.7%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s     | 1         | 3.7%    |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s  | 1         | 3.7%    |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s     | 1         | 3.7%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 3.7%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 1         | 3.7%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 1         | 3.7%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s    | 1         | 3.7%    |
| Ramaxel RAM RMSA3260MH78HAF-2666 8GB SODIMM DDR4 2667MT/s | 1         | 3.7%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s     | 1         | 3.7%    |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s     | 1         | 3.7%    |
| Kingston RAM KHX2666C15S4/8G 8GB SODIMM DDR4 2667MT/s     | 1         | 3.7%    |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s   | 1         | 3.7%    |
| Elpida RAM EBJ81UG8BBU0-GN-F 8GB SODIMM DDR3 1600MT/s     | 1         | 3.7%    |
| Crucial RAM CT4G4SFS824A.C8FE 4GB SODIMM DDR4 2400MT/s    | 1         | 3.7%    |
| Corsair RAM CMSO4GX3M1C1600C11 4GB SODIMM DDR3 1600MT/s   | 1         | 3.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 9         | 39.13%  |
| DDR3   | 7         | 30.43%  |
| SDRAM  | 2         | 8.7%    |
| LPDDR4 | 2         | 8.7%    |
| DDR2   | 2         | 8.7%    |
| LPDDR3 | 1         | 4.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 22        | 95.65%  |
| Row Of Chips | 1         | 4.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 10        | 41.67%  |
| 4096  | 8         | 33.33%  |
| 16384 | 2         | 8.33%   |
| 2048  | 2         | 8.33%   |
| 1024  | 2         | 8.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 9         | 37.5%   |
| 1600    | 6         | 25%     |
| 2400    | 3         | 12.5%   |
| 4199    | 1         | 4.17%   |
| 2133    | 1         | 4.17%   |
| 1334    | 1         | 4.17%   |
| 975     | 1         | 4.17%   |
| 533     | 1         | 4.17%   |
| Unknown | 1         | 4.17%   |

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
| Chicony Electronics                    | 9         | 39.13%  |
| IMC Networks                           | 3         | 13.04%  |
| Sunplus Innovation Technology          | 2         | 8.7%    |
| Realtek Semiconductor                  | 2         | 8.7%    |
| Lite-On Technology                     | 2         | 8.7%    |
| Silicon Motion                         | 1         | 4.35%   |
| Quanta                                 | 1         | 4.35%   |
| Motorola PCS                           | 1         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 4.35%   |
| Acer                                   | 1         | 4.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek USB Camera                                                         | 2         | 8.7%    |
| Chicony Integrated Camera                                                  | 2         | 8.7%    |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 4.35%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 4.35%   |
| Silicon Motion Web Camera                                                  | 1         | 4.35%   |
| Quanta HP Webcam                                                           | 1         | 4.35%   |
| Motorola PCS XT1033 [Moto G], PTP mode                                     | 1         | 4.35%   |
| Lite-On TOSHIBA Web Camera - FHD                                           | 1         | 4.35%   |
| Lite-On Integrated Camera                                                  | 1         | 4.35%   |
| IMC Networks UVC VGA Webcam                                                | 1         | 4.35%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 1         | 4.35%   |
| IMC Networks Integrated Camera                                             | 1         | 4.35%   |
| Chicony TOSHIBA Web Camera - HD                                            | 1         | 4.35%   |
| Chicony TOSHIBA Web Camera - FHD                                           | 1         | 4.35%   |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 4.35%   |
| Chicony HD WebCam (Acer)                                                   | 1         | 4.35%   |
| Chicony HD WebCam                                                          | 1         | 4.35%   |
| Chicony FJ Camera                                                          | 1         | 4.35%   |
| Chicony 2.0M UVC Webcam / CNF7129                                          | 1         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 4.35%   |
| Acer BisonCam,NB Pro                                                       | 1         | 4.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 3         | 50%     |
| Synaptics             | 1         | 16.67%  |
| LighTuning Technology | 1         | 16.67%  |
| Elan Microelectronics | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 16.67%  |
| Validity Sensors VFS Fingerprint sensor           | 1         | 16.67%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 16.67%  |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 16.67%  |
| Elan ELAN:Fingerprint                             | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 2         | 33.33%  |
| Alcor Micro           | 2         | 33.33%  |
| O2 Micro              | 1         | 16.67%  |
| Gemalto (was Gemplus) | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                    | 2         | 33.33%  |
| O2 Micro OZ776 CCID Smartcard Reader                   | 1         | 16.67%  |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor         | 1         | 16.67%  |
| Broadcom 5880                                          | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 13        | 44.83%  |
| 1     | 8         | 27.59%  |
| 2     | 5         | 17.24%  |
| 3     | 3         | 10.34%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 6         | 23.08%  |
| Chipcard                 | 6         | 23.08%  |
| Graphics card            | 5         | 19.23%  |
| Card reader              | 3         | 11.54%  |
| Storage                  | 1         | 3.85%   |
| Net/wireless             | 1         | 3.85%   |
| Net/ethernet             | 1         | 3.85%   |
| Firewire controller      | 1         | 3.85%   |
| Communication controller | 1         | 3.85%   |
| Camera                   | 1         | 3.85%   |

