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

Total: 38

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| 4.19.80           | 3         | 10%     |
| 5.3.7             | 2         | 6.67%   |
| 5.7.0             | 1         | 3.33%   |
| 5.5.10            | 1         | 3.33%   |
| 5.4.75            | 1         | 3.33%   |
| 5.4.50            | 1         | 3.33%   |
| 5.4.47            | 1         | 3.33%   |
| 5.4.24toshiba-new | 1         | 3.33%   |
| 5.4.2             | 1         | 3.33%   |
| 5.4.13            | 1         | 3.33%   |
| 5.2.2             | 1         | 3.33%   |
| 5.13.0.a          | 1         | 3.33%   |
| 5.10.4            | 1         | 3.33%   |
| 5.10.3            | 1         | 3.33%   |
| 5.10.21           | 1         | 3.33%   |
| 5.10.19           | 1         | 3.33%   |
| 4.4.88            | 1         | 3.33%   |
| 4.4.276           | 1         | 3.33%   |
| 4.4.240           | 1         | 3.33%   |
| 4.4.227           | 1         | 3.33%   |
| 4.4.202           | 1         | 3.33%   |
| 4.4.190-smp       | 1         | 3.33%   |
| 4.4.190           | 1         | 3.33%   |
| 4.19.79           | 1         | 3.33%   |
| 4.19.76           | 1         | 3.33%   |
| 4.19.206.a        | 1         | 3.33%   |
| 4.16.18           | 1         | 3.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.19.80  | 3         | 10%     |
| 5.3.7    | 2         | 6.67%   |
| 4.4.190  | 2         | 6.67%   |
| 5.7.0    | 1         | 3.33%   |
| 5.5.10   | 1         | 3.33%   |
| 5.4.75   | 1         | 3.33%   |
| 5.4.50   | 1         | 3.33%   |
| 5.4.47   | 1         | 3.33%   |
| 5.4.24   | 1         | 3.33%   |
| 5.4.2    | 1         | 3.33%   |
| 5.4.13   | 1         | 3.33%   |
| 5.2.2    | 1         | 3.33%   |
| 5.13.0   | 1         | 3.33%   |
| 5.10.4   | 1         | 3.33%   |
| 5.10.3   | 1         | 3.33%   |
| 5.10.21  | 1         | 3.33%   |
| 5.10.19  | 1         | 3.33%   |
| 4.4.88   | 1         | 3.33%   |
| 4.4.276  | 1         | 3.33%   |
| 4.4.240  | 1         | 3.33%   |
| 4.4.227  | 1         | 3.33%   |
| 4.4.202  | 1         | 3.33%   |
| 4.19.79  | 1         | 3.33%   |
| 4.19.76  | 1         | 3.33%   |
| 4.19.206 | 1         | 3.33%   |
| 4.16.18  | 1         | 3.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.4     | 7         | 23.33%  |
| 5.4     | 6         | 20%     |
| 4.19    | 6         | 20%     |
| 5.10    | 4         | 13.33%  |
| 5.3     | 2         | 6.67%   |
| 5.7     | 1         | 3.33%   |
| 5.5     | 1         | 3.33%   |
| 5.2     | 1         | 3.33%   |
| 5.13    | 1         | 3.33%   |
| 4.16    | 1         | 3.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 25        | 96.15%  |
| i686   | 1         | 3.85%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Unknown       | 12        | 44.44%  |
| XFCE          | 10        | 37.04%  |
| KDE           | 2         | 7.41%   |
| LXQt          | 1         | 3.7%    |
| KDE5          | 1         | 3.7%    |
| Enlightenment | 1         | 3.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 25        | 96.15%  |
| Tty  | 1         | 3.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 16        | 59.26%  |
| XDM     | 8         | 29.63%  |
| SDDM    | 3         | 11.11%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 12        | 46.15%  |
| en_US   | 11        | 42.31%  |
| pt_BR   | 1         | 3.85%   |
| pl_PL   | 1         | 3.85%   |
| fr_FR   | 1         | 3.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 18        | 66.67%  |
| EFI  | 9         | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 24        | 92.31%  |
| Btrfs | 2         | 7.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 15        | 55.56%  |
| MBR     | 9         | 33.33%  |
| Unknown | 3         | 11.11%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 23        | 85.19%  |
| Yes       | 4         | 14.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 19        | 73.08%  |
| Yes       | 7         | 26.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 7         | 26.92%  |
| Toshiba             | 3         | 11.54%  |
| Hewlett-Packard     | 3         | 11.54%  |
| Dell                | 3         | 11.54%  |
| ASUSTek Computer    | 3         | 11.54%  |
| Acer                | 2         | 7.69%   |
| Samsung Electronics | 1         | 3.85%   |
| Notebook            | 1         | 3.85%   |
| MSI                 | 1         | 3.85%   |
| Fujitsu             | 1         | 3.85%   |
| Dynabook            | 1         | 3.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Toshiba Satellite P50-A-12Z              | 1         | 3.85%   |
| Toshiba Satellite C660                   | 1         | 3.85%   |
| Toshiba PORTEGE Z30-A                    | 1         | 3.85%   |
| Samsung 300E5M/300E5L                    | 1         | 3.85%   |
| Notebook NL40_50CU                       | 1         | 3.85%   |
| MSI GL73 8RC                             | 1         | 3.85%   |
| Lenovo V330-14ARR 81B1                   | 1         | 3.85%   |
| Lenovo ThinkPad X1 Carbon 7th 20R10015US | 1         | 3.85%   |
| Lenovo ThinkPad T470 20HDCTO1WW          | 1         | 3.85%   |
| Lenovo ThinkPad T450s 20BW000EUS         | 1         | 3.85%   |
| Lenovo ThinkPad T400 6474BV7             | 1         | 3.85%   |
| Lenovo ThinkPad P70 20ERCTO1WW           | 1         | 3.85%   |
| Lenovo ThinkPad L440 20ASS05K00          | 1         | 3.85%   |
| HP Pavilion Notebook                     | 1         | 3.85%   |
| HP Laptop 15-bs2xx                       | 1         | 3.85%   |
| HP 15 Notebook PC                        | 1         | 3.85%   |
| Fujitsu LIFEBOOK A555                    | 1         | 3.85%   |
| Dynabook PORTEGE X50-G                   | 1         | 3.85%   |
| Dell Precision M4600                     | 1         | 3.85%   |
| Dell Latitude E7270                      | 1         | 3.85%   |
| Dell Latitude E5500                      | 1         | 3.85%   |
| ASUS VivoBook_ASUSLaptop X570ZD_K570ZD   | 1         | 3.85%   |
| ASUS P53E                                | 1         | 3.85%   |
| ASUS 1000H                               | 1         | 3.85%   |
| Acer Swift SF314-52                      | 1         | 3.85%   |
| Acer Aspire E1-572                       | 1         | 3.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 6         | 23.08%  |
| Toshiba Satellite | 2         | 7.69%   |
| Dell Latitude     | 2         | 7.69%   |
| Toshiba PORTEGE   | 1         | 3.85%   |
| Samsung 300E5M    | 1         | 3.85%   |
| Notebook NL40     | 1         | 3.85%   |
| MSI GL73          | 1         | 3.85%   |
| Lenovo V330-14ARR | 1         | 3.85%   |
| HP Pavilion       | 1         | 3.85%   |
| HP Laptop         | 1         | 3.85%   |
| HP 15             | 1         | 3.85%   |
| Fujitsu LIFEBOOK  | 1         | 3.85%   |
| Dynabook PORTEGE  | 1         | 3.85%   |
| Dell Precision    | 1         | 3.85%   |
| ASUS VivoBook     | 1         | 3.85%   |
| ASUS P53E         | 1         | 3.85%   |
| ASUS 1000H        | 1         | 3.85%   |
| Acer Swift        | 1         | 3.85%   |
| Acer Aspire       | 1         | 3.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 4         | 15.38%  |
| 2015 | 4         | 15.38%  |
| 2017 | 3         | 11.54%  |
| 2014 | 3         | 11.54%  |
| 2008 | 3         | 11.54%  |
| 2018 | 2         | 7.69%   |
| 2016 | 2         | 7.69%   |
| 2011 | 2         | 7.69%   |
| 2020 | 1         | 3.85%   |
| 2013 | 1         | 3.85%   |
| 2010 | 1         | 3.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 26        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 26        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 25        | 96.15%  |
| Yes  | 1         | 3.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 8         | 30.77%  |
| 3.01-4.0   | 6         | 23.08%  |
| 8.01-16.0  | 5         | 19.23%  |
| 16.01-24.0 | 4         | 15.38%  |
| 32.01-64.0 | 1         | 3.85%   |
| 1.01-2.0   | 1         | 3.85%   |
| 0.51-1.0   | 1         | 3.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 12        | 44.44%  |
| 2.01-3.0  | 6         | 22.22%  |
| 3.01-4.0  | 4         | 14.81%  |
| 4.01-8.0  | 2         | 7.41%   |
| 8.01-16.0 | 1         | 3.7%    |
| 0.51-1.0  | 1         | 3.7%    |
| 0.01-0.5  | 1         | 3.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 19        | 70.37%  |
| 2      | 7         | 25.93%  |
| 3      | 1         | 3.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 18        | 69.23%  |
| Yes       | 8         | 30.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 92.31%  |
| No        | 2         | 7.69%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 84.62%  |
| No        | 4         | 15.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 4         | 15.38%  |
| UK          | 3         | 11.54%  |
| Portugal    | 3         | 11.54%  |
| Poland      | 2         | 7.69%   |
| India       | 2         | 7.69%   |
| Canada      | 2         | 7.69%   |
| Brazil      | 2         | 7.69%   |
| Sweden      | 1         | 3.85%   |
| Russia      | 1         | 3.85%   |
| Philippines | 1         | 3.85%   |
| Italy       | 1         | 3.85%   |
| Germany     | 1         | 3.85%   |
| France      | 1         | 3.85%   |
| Finland     | 1         | 3.85%   |
| Chile       | 1         | 3.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Warsaw                 | 2         | 7.14%   |
| Lisbon                 | 2         | 7.14%   |
| Wokingham              | 1         | 3.57%   |
| Winnipeg               | 1         | 3.57%   |
| Visconde do Rio Branco | 1         | 3.57%   |
| Roknaes                | 1         | 3.57%   |
| Redding                | 1         | 3.57%   |
| Puente Alto            | 1         | 3.57%   |
| Pinhal Novo            | 1         | 3.57%   |
| Pesaro                 | 1         | 3.57%   |
| Pasay                  | 1         | 3.57%   |
| Paris                  | 1         | 3.57%   |
| Northport              | 1         | 3.57%   |
| Milan                  | 1         | 3.57%   |
| Lins                   | 1         | 3.57%   |
| Kstovo                 | 1         | 3.57%   |
| Jaipur                 | 1         | 3.57%   |
| Hornsey                | 1         | 3.57%   |
| Helsinki               | 1         | 3.57%   |
| Faridabad              | 1         | 3.57%   |
| Carrollton             | 1         | 3.57%   |
| Canandaigua            | 1         | 3.57%   |
| Borken                 | 1         | 3.57%   |
| Bengaluru              | 1         | 3.57%   |
| Barry                  | 1         | 3.57%   |
| Barrie                 | 1         | 3.57%   |

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
| 101-250    | 9         | 34.62%  |
| 501-1000   | 7         | 26.92%  |
| 251-500    | 6         | 23.08%  |
| 1001-2000  | 2         | 7.69%   |
| 1-20       | 1         | 3.85%   |
| 51-100     | 1         | 3.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 21-50    | 7         | 24.14%  |
| 1-20     | 7         | 24.14%  |
| 51-100   | 6         | 20.69%  |
| 501-1000 | 5         | 17.24%  |
| 251-500  | 2         | 6.9%    |
| 101-250  | 2         | 6.9%    |

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
| Intel                       | 22        | 73.33%  |
| Samsung Electronics         | 3         | 10%     |
| AMD                         | 2         | 6.67%   |
| SanDisk                     | 1         | 3.33%   |
| Phison Electronics          | 1         | 3.33%   |
| Kingston Technology Company | 1         | 3.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 9.68%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 9.68%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 6.45%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 6.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 6.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 6.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 6.45%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 2         | 6.45%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 3.23%   |
| Phison NVMe Storage Controller                                                   | 1         | 3.23%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 3.23%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 3.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 3.23%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 3.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 3.23%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 3.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 3.23%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 3.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1         | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                       | 1         | 3.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 3.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 21        | 67.74%  |
| NVMe | 7         | 22.58%  |
| IDE  | 2         | 6.45%   |
| RAID | 1         | 3.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 24        | 92.31%  |
| AMD    | 2         | 7.69%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 7.69%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 3.85%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 3.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 3.85%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 3.85%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 3.85%   |
| Intel Core i7-2860QM CPU @ 2.50GHz            | 1         | 3.85%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 3.85%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 3.85%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 3.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 3.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 3.85%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 3.85%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 3.85%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 3.85%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 3.85%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 3.85%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 3.85%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 3.85%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 3.85%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 1         | 3.85%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 1         | 3.85%   |
| Intel Core 2 CPU P8400 @ 2.26GHz              | 1         | 3.85%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 3.85%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 1         | 3.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 8         | 30.77%  |
| Intel Core i7    | 6         | 23.08%  |
| Intel Core i3    | 4         | 15.38%  |
| Intel Pentium    | 2         | 7.69%   |
| AMD Ryzen 5      | 2         | 7.69%   |
| Intel Core 2 Duo | 1         | 3.85%   |
| Intel Core 2     | 1         | 3.85%   |
| Intel Celeron    | 1         | 3.85%   |
| Intel Atom       | 1         | 3.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 14        | 53.85%  |
| 4      | 10        | 38.46%  |
| 6      | 1         | 3.85%   |
| 1      | 1         | 3.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 26        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 21        | 80.77%  |
| 1      | 5         | 19.23%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 23        | 88.46%  |
| Unknown        | 2         | 7.69%   |
| 32-bit         | 1         | 3.85%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 6         | 23.08%  |
| 0x806ec    | 2         | 7.69%   |
| 0x406e3    | 2         | 7.69%   |
| 0x306d4    | 2         | 7.69%   |
| 0x206a7    | 2         | 7.69%   |
| 0xa0660    | 1         | 3.85%   |
| 0x806ea    | 1         | 3.85%   |
| 0x806e9    | 1         | 3.85%   |
| 0x706a1    | 1         | 3.85%   |
| 0x6fd      | 1         | 3.85%   |
| 0x506e3    | 1         | 3.85%   |
| 0x40651    | 1         | 3.85%   |
| 0x306c3    | 1         | 3.85%   |
| 0x20655    | 1         | 3.85%   |
| 0x106c2    | 1         | 3.85%   |
| 0x1067a    | 1         | 3.85%   |
| 0x0810100b | 1         | 3.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 5         | 19.23%  |
| Skylake       | 4         | 15.38%  |
| Haswell       | 4         | 15.38%  |
| Zen           | 2         | 7.69%   |
| SandyBridge   | 2         | 7.69%   |
| Broadwell     | 2         | 7.69%   |
| Westmere      | 1         | 3.85%   |
| Silvermont    | 1         | 3.85%   |
| Penryn        | 1         | 3.85%   |
| Goldmont plus | 1         | 3.85%   |
| Core          | 1         | 3.85%   |
| CometLake     | 1         | 3.85%   |
| Bonnell       | 1         | 3.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 23        | 76.67%  |
| Nvidia | 5         | 16.67%  |
| AMD    | 2         | 6.67%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 9.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 6.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 6.45%   |
| Intel HD Graphics 5500                                                                   | 2         | 6.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 6.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 6.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 6.45%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 6.45%   |
| Nvidia GM204GLM [Quadro M3000M]                                                          | 1         | 3.23%   |
| Nvidia GK107M [GeForce GT 745M]                                                          | 1         | 3.23%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 3.23%   |
| Intel UHD Graphics 620                                                                   | 1         | 3.23%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 3.23%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 3.23%   |
| Intel HD Graphics 620                                                                    | 1         | 3.23%   |
| Intel HD Graphics 530                                                                    | 1         | 3.23%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 3.23%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 3.23%   |
| Intel Comet Lake UHD Graphics                                                            | 1         | 3.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 3.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 3.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 3.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 20        | 76.92%  |
| Intel + Nvidia | 3         | 11.54%  |
| 1 x Nvidia     | 1         | 3.85%   |
| AMD + Nvidia   | 1         | 3.85%   |
| 1 x AMD        | 1         | 3.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 25        | 96.15%  |
| Unknown | 1         | 3.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 70.37%  |
| 1.01-2.0   | 4         | 14.81%  |
| 3.01-4.0   | 2         | 7.41%   |
| 0.51-1.0   | 1         | 3.7%    |
| 0.01-0.5   | 1         | 3.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 7         | 25.93%  |
| LG Display          | 6         | 22.22%  |
| AU Optronics        | 4         | 14.81%  |
| Samsung Electronics | 3         | 11.11%  |
| BOE                 | 3         | 11.11%  |
| Sharp               | 1         | 3.7%    |
| Panasonic           | 1         | 3.7%    |
| Lenovo              | 1         | 3.7%    |
| Goldstar            | 1         | 3.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 2         | 7.41%   |
| Sharp LCD Monitor SHP14C4 1920x1080 344x194mm 15.5-inch              | 1         | 3.7%    |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch | 1         | 3.7%    |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch | 1         | 3.7%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 1         | 3.7%    |
| Panasonic LCD Monitor MEI96A2 3840x2160 382x215mm 17.3-inch          | 1         | 3.7%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 1         | 3.7%    |
| LG Display LCD Monitor LGD0508 1366x768 309x174mm 14.0-inch          | 1         | 3.7%    |
| LG Display LCD Monitor LGD03D7 1366x768 310x174mm 14.0-inch          | 1         | 3.7%    |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch          | 1         | 3.7%    |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch          | 1         | 3.7%    |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch         | 1         | 3.7%    |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch              | 1         | 3.7%    |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 1         | 3.7%    |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 1         | 3.7%    |
| Chimei Innolux LCD Monitor CMN15CC 1366x768 344x193mm 15.5-inch      | 1         | 3.7%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 1         | 3.7%    |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch      | 1         | 3.7%    |
| Chimei Innolux LCD Monitor CMN1355 1366x768 293x165mm 13.2-inch      | 1         | 3.7%    |
| BOE LCD Monitor BOE07C8 3840x2160 309x174mm 14.0-inch                | 1         | 3.7%    |
| BOE LCD Monitor BOE0703 1920x1080 344x194mm 15.5-inch                | 1         | 3.7%    |
| BOE LCD Monitor BOE0690 1920x1080 344x193mm 15.5-inch                | 1         | 3.7%    |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 1         | 3.7%    |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch        | 1         | 3.7%    |
| AU Optronics LCD Monitor AUO30ED 1920x1080 344x193mm 15.5-inch       | 1         | 3.7%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 1         | 3.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 11        | 40.74%  |
| 1920x1080 (FHD)    | 10        | 37.04%  |
| 3840x2160 (4K)     | 2         | 7.41%   |
| 1600x900 (HD+)     | 2         | 7.41%   |
| 1680x1050 (WSXGA+) | 1         | 3.7%    |
| 1280x800 (WXGA)    | 1         | 3.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 12        | 44.44%  |
| 14     | 6         | 22.22%  |
| 13     | 4         | 14.81%  |
| 17     | 2         | 7.41%   |
| 21     | 1         | 3.7%    |
| 20     | 1         | 3.7%    |
| 12     | 1         | 3.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 20        | 74.07%  |
| 351-400     | 3         | 11.11%  |
| 401-500     | 2         | 7.41%   |
| 201-300     | 2         | 7.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 24        | 92.31%  |
| 3/2   | 1         | 3.85%   |
| 16/10 | 1         | 3.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 44.44%  |
| 81-90          | 9         | 33.33%  |
| 121-130        | 2         | 7.41%   |
| 71-80          | 1         | 3.7%    |
| 61-70          | 1         | 3.7%    |
| 201-250        | 1         | 3.7%    |
| 151-200        | 1         | 3.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 12        | 44.44%  |
| 101-120       | 9         | 33.33%  |
| 51-100        | 4         | 14.81%  |
| More than 240 | 2         | 7.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 24        | 92.31%  |
| 2     | 2         | 7.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 45.45%  |
| Realtek Semiconductor | 10        | 22.73%  |
| Qualcomm Atheros      | 7         | 15.91%  |
| Broadcom              | 2         | 4.55%   |
| Sierra Wireless       | 1         | 2.27%   |
| Ralink Technology     | 1         | 2.27%   |
| Dell                  | 1         | 2.27%   |
| Broadcom Limited      | 1         | 2.27%   |
| ASIX Electronics      | 1         | 2.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 5         | 9.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 4         | 7.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 3.7%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                             | 2         | 3.7%    |
| Intel Wireless-AC 9260                                                                | 2         | 3.7%    |
| Intel Wireless 8265 / 8275                                                            | 2         | 3.7%    |
| Intel Wireless 8260                                                                   | 2         | 3.7%    |
| Intel Wireless 7265                                                                   | 2         | 3.7%    |
| Intel Wireless 7260                                                                   | 2         | 3.7%    |
| Intel Wireless 3160                                                                   | 2         | 3.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 2         | 3.7%    |
| Sierra Wireless EM7305                                                                | 1         | 1.85%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 1.85%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 1.85%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 1.85%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 1.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 1.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1         | 1.85%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                        | 1         | 1.85%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.85%   |
| Intel WiFi Link 5100                                                                  | 1         | 1.85%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 1.85%   |
| Intel Ethernet Connection I219-LM                                                     | 1         | 1.85%   |
| Intel Ethernet Connection I218-V                                                      | 1         | 1.85%   |
| Intel Ethernet Connection I217-V                                                      | 1         | 1.85%   |
| Intel Ethernet Connection (4) I219-V                                                  | 1         | 1.85%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 1         | 1.85%   |
| Intel Ethernet Connection (2) I219-LM                                                 | 1         | 1.85%   |
| Intel Ethernet Connection (10) I219-V                                                 | 1         | 1.85%   |
| Intel Centrino Ultimate-N 6300                                                        | 1         | 1.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 1         | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 1         | 1.85%   |
| Intel 82567LM Gigabit Network Connection                                              | 1         | 1.85%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                                  | 1         | 1.85%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                                     | 1         | 1.85%   |
| Broadcom Limited NetXtreme BCM5756ME Gigabit Ethernet PCI Express                     | 1         | 1.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 1.85%   |
| ASIX AX88772B                                                                         | 1         | 1.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 18        | 62.07%  |
| Qualcomm Atheros      | 5         | 17.24%  |
| Realtek Semiconductor | 2         | 6.9%    |
| Sierra Wireless       | 1         | 3.45%   |
| Ralink Technology     | 1         | 3.45%   |
| Dell                  | 1         | 3.45%   |
| Broadcom              | 1         | 3.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 6.9%    |
| Intel Wireless-AC 9260                                                                | 2         | 6.9%    |
| Intel Wireless 8265 / 8275                                                            | 2         | 6.9%    |
| Intel Wireless 8260                                                                   | 2         | 6.9%    |
| Intel Wireless 7265                                                                   | 2         | 6.9%    |
| Intel Wireless 7260                                                                   | 2         | 6.9%    |
| Intel Wireless 3160                                                                   | 2         | 6.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 2         | 6.9%    |
| Sierra Wireless EM7305                                                                | 1         | 3.45%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 3.45%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 3.45%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 3.45%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 3.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 3.45%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 3.45%   |
| Intel WiFi Link 5100                                                                  | 1         | 3.45%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 3.45%   |
| Intel Centrino Ultimate-N 6300                                                        | 1         | 3.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 1         | 3.45%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                                  | 1         | 3.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 3.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 9         | 36%     |
| Intel                 | 9         | 36%     |
| Qualcomm Atheros      | 4         | 16%     |
| Broadcom Limited      | 1         | 4%      |
| Broadcom              | 1         | 4%      |
| ASIX Electronics      | 1         | 4%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 20%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 16%     |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 8%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 4%      |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 4%      |
| Intel Ethernet Connection I219-LM                                 | 1         | 4%      |
| Intel Ethernet Connection I218-V                                  | 1         | 4%      |
| Intel Ethernet Connection I217-V                                  | 1         | 4%      |
| Intel Ethernet Connection (4) I219-V                              | 1         | 4%      |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 4%      |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 4%      |
| Intel Ethernet Connection (10) I219-V                             | 1         | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 4%      |
| Intel 82567LM Gigabit Network Connection                          | 1         | 4%      |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 4%      |
| Broadcom Limited NetXtreme BCM5756ME Gigabit Ethernet PCI Express | 1         | 4%      |
| ASIX AX88772B                                                     | 1         | 4%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 52%     |
| Ethernet | 24        | 48%     |

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
| 2     | 23        | 88.46%  |
| 1     | 2         | 7.69%   |
| 0     | 1         | 3.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 26        | 100%    |

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
| Intel             | 24        | 82.76%  |
| Nvidia            | 2         | 6.9%    |
| AMD               | 2         | 6.9%    |
| Texas Instruments | 1         | 3.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 13.51%  |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 8.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 5.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 5.41%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 5.41%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 5.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 5.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 5.41%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 5.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 5.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 5.41%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 5.41%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 2.7%    |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 2.7%    |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 2.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 2.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 2.7%    |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 2.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 2.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 2.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 9         | 34.62%  |
| Samsung Electronics | 7         | 26.92%  |
| Micron Technology   | 2         | 7.69%   |
| Kingston            | 2         | 7.69%   |
| Unknown             | 1         | 3.85%   |
| Smart               | 1         | 3.85%   |
| Ramaxel Technology  | 1         | 3.85%   |
| Elpida              | 1         | 3.85%   |
| Crucial             | 1         | 3.85%   |
| Corsair             | 1         | 3.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s     | 2         | 7.69%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                     | 1         | 3.85%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s      | 1         | 3.85%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s    | 1         | 3.85%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s            | 1         | 3.85%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s      | 1         | 3.85%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s  | 1         | 3.85%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s     | 1         | 3.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s     | 1         | 3.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s     | 1         | 3.85%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s      | 1         | 3.85%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s   | 1         | 3.85%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s      | 1         | 3.85%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s   | 1         | 3.85%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 3.85%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s      | 1         | 3.85%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s     | 1         | 3.85%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8GB SODIMM DDR4 2667MT/s  | 1         | 3.85%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s      | 1         | 3.85%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s      | 1         | 3.85%   |
| Kingston RAM KHX2666C15S4/8G 8GB SODIMM DDR4 2667MT/s      | 1         | 3.85%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s    | 1         | 3.85%   |
| Elpida RAM EBJ81UG8BBU0-GN-F 8GB SODIMM DDR3 1600MT/s      | 1         | 3.85%   |
| Crucial RAM CT4G4SFS824A.C8FE 4GB SODIMM DDR4 2400MT/s     | 1         | 3.85%   |
| Corsair RAM CMSO4GX3M1C1600C11 4096MB SODIMM DDR3 1600MT/s | 1         | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 9         | 40.91%  |
| DDR3   | 7         | 31.82%  |
| SDRAM  | 2         | 9.09%   |
| LPDDR4 | 2         | 9.09%   |
| LPDDR3 | 1         | 4.55%   |
| DDR2   | 1         | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 21        | 95.45%  |
| Row Of Chips | 1         | 4.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 10        | 43.48%  |
| 8192  | 8         | 34.78%  |
| 16384 | 2         | 8.7%    |
| 2048  | 2         | 8.7%    |
| 1024  | 1         | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 9         | 39.13%  |
| 1600    | 6         | 26.09%  |
| 2400    | 3         | 13.04%  |
| 4199    | 1         | 4.35%   |
| 2133    | 1         | 4.35%   |
| 1334    | 1         | 4.35%   |
| 975     | 1         | 4.35%   |
| Unknown | 1         | 4.35%   |

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
| 0     | 13        | 46.43%  |
| 1     | 7         | 25%     |
| 2     | 5         | 17.86%  |
| 3     | 3         | 10.71%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 6         | 24%     |
| Chipcard                 | 6         | 24%     |
| Graphics card            | 4         | 16%     |
| Card reader              | 3         | 12%     |
| Storage                  | 1         | 4%      |
| Net/wireless             | 1         | 4%      |
| Net/ethernet             | 1         | 4%      |
| Firewire controller      | 1         | 4%      |
| Communication controller | 1         | 4%      |
| Camera                   | 1         | 4%      |

