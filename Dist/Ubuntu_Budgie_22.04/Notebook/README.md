Ubuntu Budgie 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie 22.04.

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

Total: 41

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E6410              | [98545a1050](https://linux-hardware.org/?probe=98545a1050) | Sep 30, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [15d9ea100b](https://linux-hardware.org/?probe=15d9ea100b) | Sep 26, 2022 |
| TUXEDO        | Book BA1510                 | [76a485fe7e](https://linux-hardware.org/?probe=76a485fe7e) | Sep 22, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [f185fff0a3](https://linux-hardware.org/?probe=f185fff0a3) | Sep 21, 2022 |
| Lenovo        | G50-45 80E3                 | [5c9688dac8](https://linux-hardware.org/?probe=5c9688dac8) | Sep 19, 2022 |
| Lenovo        | G500 20236                  | [fc210ff2c2](https://linux-hardware.org/?probe=fc210ff2c2) | Sep 07, 2022 |
| Google        | Rabbid                      | [8049c3894c](https://linux-hardware.org/?probe=8049c3894c) | Aug 24, 2022 |
| Lenovo        | G500 20236                  | [81ba48faa1](https://linux-hardware.org/?probe=81ba48faa1) | Aug 20, 2022 |
| Lenovo        | G500 20236                  | [45df8f9be9](https://linux-hardware.org/?probe=45df8f9be9) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | [6974cf32ce](https://linux-hardware.org/?probe=6974cf32ce) | Aug 17, 2022 |
| TUXEDO        | Book XUX7 Gen11             | [ecf8be45de](https://linux-hardware.org/?probe=ecf8be45de) | Aug 16, 2022 |
| TUXEDO        | Book XUX7 Gen11             | [c5c7e42e91](https://linux-hardware.org/?probe=c5c7e42e91) | Aug 16, 2022 |
| Dell          | Inspiron 3793               | [15f2e25089](https://linux-hardware.org/?probe=15f2e25089) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [e82d2e1076](https://linux-hardware.org/?probe=e82d2e1076) | Jul 28, 2022 |
| HP            | EliteBook 840 G3            | [e34f81fcfa](https://linux-hardware.org/?probe=e34f81fcfa) | Jul 18, 2022 |
| Lenovo        | ThinkPad T500 2242CTO       | [47bddb4e10](https://linux-hardware.org/?probe=47bddb4e10) | Jul 10, 2022 |
| HP            | ENVY 17                     | [2d97952e56](https://linux-hardware.org/?probe=2d97952e56) | Jul 08, 2022 |
| Acer          | Aspire E5-573G              | [9f14a273b0](https://linux-hardware.org/?probe=9f14a273b0) | Jun 26, 2022 |
| HP            | ElitePad 1000 G2            | [e478f31175](https://linux-hardware.org/?probe=e478f31175) | Jun 25, 2022 |
| MSI           | GL62 6QF                    | [39e2d35166](https://linux-hardware.org/?probe=39e2d35166) | Jun 20, 2022 |
| Timi          | TM1604                      | [2f45cc25b4](https://linux-hardware.org/?probe=2f45cc25b4) | Jun 20, 2022 |
| Dell          | Inspiron 5570               | [ea74ff47bc](https://linux-hardware.org/?probe=ea74ff47bc) | May 27, 2022 |
| Dell          | Inspiron 5570               | [83e0c49ab0](https://linux-hardware.org/?probe=83e0c49ab0) | May 27, 2022 |
| HP            | Pavilion g6                 | [ef71909561](https://linux-hardware.org/?probe=ef71909561) | May 26, 2022 |
| HP            | Pavilion g6                 | [41d1e81397](https://linux-hardware.org/?probe=41d1e81397) | May 26, 2022 |
| Chuwi         | HeroBook Pro                | [9f009d836c](https://linux-hardware.org/?probe=9f009d836c) | May 23, 2022 |
| Chuwi         | HeroBook Pro                | [206aa9b805](https://linux-hardware.org/?probe=206aa9b805) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [b128814505](https://linux-hardware.org/?probe=b128814505) | May 21, 2022 |
| Apple         | MacBookPro5,4               | [5b7383f9cb](https://linux-hardware.org/?probe=5b7383f9cb) | May 15, 2022 |
| Avell High... | B.ON                        | [9069ca4c66](https://linux-hardware.org/?probe=9069ca4c66) | May 13, 2022 |
| MSI           | Modern 15 A10M              | [88c226c079](https://linux-hardware.org/?probe=88c226c079) | May 09, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [296dc11e4b](https://linux-hardware.org/?probe=296dc11e4b) | May 08, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [ca08dea33b](https://linux-hardware.org/?probe=ca08dea33b) | May 07, 2022 |
| Google        | Boten                       | [6204cff7de](https://linux-hardware.org/?probe=6204cff7de) | May 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [ff291ff9e3](https://linux-hardware.org/?probe=ff291ff9e3) | May 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [0c5f20e02c](https://linux-hardware.org/?probe=0c5f20e02c) | May 02, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [6ace557278](https://linux-hardware.org/?probe=6ace557278) | Apr 29, 2022 |
| Apple         | MacBookPro9,2               | [967eac195b](https://linux-hardware.org/?probe=967eac195b) | Apr 23, 2022 |
| ASUSTek       | T200TAC                     | [20834c0dba](https://linux-hardware.org/?probe=20834c0dba) | Feb 17, 2022 |
| Apple         | MacBookPro8,1               | [56d0201ca6](https://linux-hardware.org/?probe=56d0201ca6) | Dec 29, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.15.0-27-generic     | 7         | 20.59%  |
| 5.15.0-40-generic     | 3         | 8.82%   |
| 5.15.0-39-generic     | 3         | 8.82%   |
| 5.15.0-30-generic     | 3         | 8.82%   |
| 5.15.0-47-generic     | 2         | 5.88%   |
| 5.15.0-46-generic     | 2         | 5.88%   |
| 5.15.0-33-generic     | 2         | 5.88%   |
| 5.15.0-25-generic     | 2         | 5.88%   |
| 5.19.0-051900-generic | 1         | 2.94%   |
| 5.15.0-48-generic     | 1         | 2.94%   |
| 5.15.0-43-generic     | 1         | 2.94%   |
| 5.15.0-41-generic     | 1         | 2.94%   |
| 5.15.0-35-generic     | 1         | 2.94%   |
| 5.15.0-18-generic     | 1         | 2.94%   |
| 5.15.0-10047-tuxedo   | 1         | 2.94%   |
| 5.15.0-10041-tuxedo   | 1         | 2.94%   |
| 5.13.0-35-generic     | 1         | 2.94%   |
| 5.13.0-19-generic     | 1         | 2.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 30        | 90.91%  |
| 5.13.0  | 2         | 6.06%   |
| 5.19.0  | 1         | 3.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 30        | 90.91%  |
| 5.13    | 2         | 6.06%   |
| 5.19    | 1         | 3.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 33        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Budgie | 31        | 93.94%  |
| GNOME  | 2         | 6.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 31        | 93.94%  |
| Wayland | 2         | 6.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 22        | 66.67%  |
| Unknown | 6         | 18.18%  |
| GDM3    | 5         | 15.15%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 10        | 30.3%   |
| fr_FR | 5         | 15.15%  |
| de_DE | 5         | 15.15%  |
| pt_BR | 3         | 9.09%   |
| en_CA | 2         | 6.06%   |
| it_IT | 1         | 3.03%   |
| hu_HU | 1         | 3.03%   |
| fr_BE | 1         | 3.03%   |
| es_MX | 1         | 3.03%   |
| es_EC | 1         | 3.03%   |
| en_IE | 1         | 3.03%   |
| en_GB | 1         | 3.03%   |
| C     | 1         | 3.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 19        | 57.58%  |
| EFI  | 14        | 42.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 29        | 87.88%  |
| Overlay | 2         | 6.06%   |
| Xfs     | 1         | 3.03%   |
| Btrfs   | 1         | 3.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 16        | 48.48%  |
| Unknown | 15        | 45.45%  |
| MBR     | 2         | 6.06%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 27        | 81.82%  |
| Yes       | 6         | 18.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 25        | 75.76%  |
| Yes       | 8         | 24.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 8         | 24.24%  |
| Hewlett-Packard        | 5         | 15.15%  |
| ASUSTek Computer       | 4         | 12.12%  |
| Dell                   | 3         | 9.09%   |
| Apple                  | 3         | 9.09%   |
| TUXEDO                 | 2         | 6.06%   |
| MSI                    | 2         | 6.06%   |
| Google                 | 2         | 6.06%   |
| Timi                   | 1         | 3.03%   |
| Chuwi                  | 1         | 3.03%   |
| Avell High Performance | 1         | 3.03%   |
| Acer                   | 1         | 3.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| TUXEDO Book XUX7 Gen11                   | 1         | 3.03%   |
| TUXEDO Book BA1510                       | 1         | 3.03%   |
| Timi TM1604                              | 1         | 3.03%   |
| MSI Modern 15 A10M                       | 1         | 3.03%   |
| MSI GL62 6QF                             | 1         | 3.03%   |
| Lenovo ThinkPad T500 2242CTO             | 1         | 3.03%   |
| Lenovo ThinkPad T440 20B7S0F100          | 1         | 3.03%   |
| Lenovo ThinkPad T14 Gen 2i 20W000Q4GE    | 1         | 3.03%   |
| Lenovo IdeaPad S145-14IWL 81MU           | 1         | 3.03%   |
| Lenovo IdeaPad 5 15ARE05 81YQ            | 1         | 3.03%   |
| Lenovo IdeaPad 330-15IKB 81FE            | 1         | 3.03%   |
| Lenovo G500 20236                        | 1         | 3.03%   |
| Lenovo G50-45 80E3                       | 1         | 3.03%   |
| HP ProBook 450 G8 Notebook PC            | 1         | 3.03%   |
| HP Pavilion g6                           | 1         | 3.03%   |
| HP ENVY 17                               | 1         | 3.03%   |
| HP ElitePad 1000 G2                      | 1         | 3.03%   |
| HP EliteBook 840 G3                      | 1         | 3.03%   |
| Google Rabbid                            | 1         | 3.03%   |
| Google Boten                             | 1         | 3.03%   |
| Dell Latitude E6410                      | 1         | 3.03%   |
| Dell Inspiron 5570                       | 1         | 3.03%   |
| Dell Inspiron 3793                       | 1         | 3.03%   |
| Chuwi HeroBook Pro                       | 1         | 3.03%   |
| Avell High Performance B.ON              | 1         | 3.03%   |
| ASUS ZenBook UX533FD_UX533FD             | 1         | 3.03%   |
| ASUS VivoBook_ASUSLaptop X705MAR_X705MA  | 1         | 3.03%   |
| ASUS VivoBook_ASUSLaptop M3401QC_M3401QC | 1         | 3.03%   |
| ASUS T200TAC                             | 1         | 3.03%   |
| Apple MacBookPro9,2                      | 1         | 3.03%   |
| Apple MacBookPro8,1                      | 1         | 3.03%   |
| Apple MacBookPro5,4                      | 1         | 3.03%   |
| Acer Aspire E5-573G                      | 1         | 3.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 3         | 9.09%   |
| Lenovo IdeaPad              | 3         | 9.09%   |
| TUXEDO Book                 | 2         | 6.06%   |
| Dell Inspiron               | 2         | 6.06%   |
| ASUS VivoBook               | 2         | 6.06%   |
| Timi TM1604                 | 1         | 3.03%   |
| MSI Modern                  | 1         | 3.03%   |
| MSI GL62                    | 1         | 3.03%   |
| Lenovo G500                 | 1         | 3.03%   |
| Lenovo G50-45               | 1         | 3.03%   |
| HP ProBook                  | 1         | 3.03%   |
| HP Pavilion                 | 1         | 3.03%   |
| HP ENVY                     | 1         | 3.03%   |
| HP ElitePad                 | 1         | 3.03%   |
| HP EliteBook                | 1         | 3.03%   |
| Google Rabbid               | 1         | 3.03%   |
| Google Boten                | 1         | 3.03%   |
| Dell Latitude               | 1         | 3.03%   |
| Chuwi HeroBook              | 1         | 3.03%   |
| Avell High Performance B.ON | 1         | 3.03%   |
| ASUS ZenBook                | 1         | 3.03%   |
| ASUS T200TAC                | 1         | 3.03%   |
| Apple MacBookPro9           | 1         | 3.03%   |
| Apple MacBookPro8           | 1         | 3.03%   |
| Apple MacBookPro5           | 1         | 3.03%   |
| Acer Aspire                 | 1         | 3.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 5         | 15.15%  |
| 2020 | 5         | 15.15%  |
| 2019 | 3         | 9.09%   |
| 2014 | 3         | 9.09%   |
| 2018 | 2         | 6.06%   |
| 2017 | 2         | 6.06%   |
| 2016 | 2         | 6.06%   |
| 2013 | 2         | 6.06%   |
| 2011 | 2         | 6.06%   |
| 2010 | 2         | 6.06%   |
| 2022 | 1         | 3.03%   |
| 2015 | 1         | 3.03%   |
| 2012 | 1         | 3.03%   |
| 2009 | 1         | 3.03%   |
| 2008 | 1         | 3.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 33        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 31        | 93.94%  |
| Enabled  | 2         | 6.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 31        | 93.94%  |
| Yes  | 2         | 6.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 11        | 33.33%  |
| 3.01-4.0    | 7         | 21.21%  |
| 16.01-24.0  | 6         | 18.18%  |
| 8.01-16.0   | 5         | 15.15%  |
| 32.01-64.0  | 2         | 6.06%   |
| 64.01-256.0 | 2         | 6.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 11        | 33.33%  |
| 1.01-2.0   | 11        | 33.33%  |
| 4.01-8.0   | 8         | 24.24%  |
| 3.01-4.0   | 1         | 3.03%   |
| 24.01-32.0 | 1         | 3.03%   |
| 8.01-16.0  | 1         | 3.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 20        | 60.61%  |
| 2      | 11        | 33.33%  |
| 3      | 2         | 6.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 27        | 81.82%  |
| Yes       | 6         | 18.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 72.73%  |
| No        | 9         | 27.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 96.97%  |
| No        | 1         | 3.03%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 87.88%  |
| No        | 4         | 12.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 7         | 21.21%  |
| Germany            | 5         | 15.15%  |
| France             | 4         | 12.12%  |
| Brazil             | 3         | 9.09%   |
| Canada             | 2         | 6.06%   |
| Slovenia           | 1         | 3.03%   |
| Mexico             | 1         | 3.03%   |
| Italy              | 1         | 3.03%   |
| Ireland            | 1         | 3.03%   |
| Hungary            | 1         | 3.03%   |
| Greece             | 1         | 3.03%   |
| Ecuador            | 1         | 3.03%   |
| Dominican Republic | 1         | 3.03%   |
| Cabo Verde         | 1         | 3.03%   |
| Belgium            | 1         | 3.03%   |
| Austria            | 1         | 3.03%   |
| Algeria            | 1         | 3.03%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Wertheim am Main   | 1         | 3.03%   |
| Vienna             | 1         | 3.03%   |
| Victoria           | 1         | 3.03%   |
| Sétif             | 1         | 3.03%   |
| Seelze             | 1         | 3.03%   |
| Sao Paulo          | 1         | 3.03%   |
| Santo Domingo Este | 1         | 3.03%   |
| Saint-Gilles       | 1         | 3.03%   |
| Queens             | 1         | 3.03%   |
| Puebla City        | 1         | 3.03%   |
| Praia              | 1         | 3.03%   |
| Postojna           | 1         | 3.03%   |
| Nuremberg          | 1         | 3.03%   |
| Monza              | 1         | 3.03%   |
| Mishawaka          | 1         | 3.03%   |
| Massaranduba       | 1         | 3.03%   |
| Lille              | 1         | 3.03%   |
| Leominster         | 1         | 3.03%   |
| Le Mee-sur-Seine   | 1         | 3.03%   |
| Laval              | 1         | 3.03%   |
| Kassel             | 1         | 3.03%   |
| Fontenay-sous-Bois | 1         | 3.03%   |
| Dublin             | 1         | 3.03%   |
| DeQuincy           | 1         | 3.03%   |
| Cuenca             | 1         | 3.03%   |
| Charlotte          | 1         | 3.03%   |
| Budapest           | 1         | 3.03%   |
| Brasília          | 1         | 3.03%   |
| Berlin             | 1         | 3.03%   |
| Austin             | 1         | 3.03%   |
| Athens             | 1         | 3.03%   |
| Argol              | 1         | 3.03%   |
| Albuquerque        | 1         | 3.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Samsung Electronics   | 8         | 9      | 17.39%  |
| Unknown               | 5         | 5      | 10.87%  |
| WDC                   | 3         | 4      | 6.52%   |
| SK hynix              | 3         | 3      | 6.52%   |
| Crucial               | 3         | 4      | 6.52%   |
| Toshiba               | 2         | 2      | 4.35%   |
| Seagate               | 2         | 2      | 4.35%   |
| Micron Technology     | 2         | 2      | 4.35%   |
| Kingston              | 2         | 2      | 4.35%   |
| JMicron Technology    | 2         | 2      | 4.35%   |
| China                 | 2         | 2      | 4.35%   |
| Union Memory          | 1         | 1      | 2.17%   |
| TO Exter              | 1         | 1      | 2.17%   |
| SPCC                  | 1         | 1      | 2.17%   |
| Realtek Semiconductor | 1         | 1      | 2.17%   |
| OWC                   | 1         | 1      | 2.17%   |
| Netac                 | 1         | 1      | 2.17%   |
| Intel                 | 1         | 1      | 2.17%   |
| Hewlett-Packard       | 1         | 1      | 2.17%   |
| Corsair               | 1         | 2      | 2.17%   |
| Apple                 | 1         | 1      | 2.17%   |
| A-DATA Technology     | 1         | 1      | 2.17%   |
| Unknown               | 1         | 1      | 2.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| WDC WD10JPVX-22JC3T0 1TB                 | 2         | 4.26%   |
| Unknown SD64G  64GB                      | 2         | 4.26%   |
| WDC PC SN730 NVMe 256GB                  | 1         | 2.13%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB     | 1         | 2.13%   |
| Unknown SL128  128GB                     | 1         | 2.13%   |
| Unknown SA16G  16GB                      | 1         | 2.13%   |
| Unknown MMC128  128GB                    | 1         | 2.13%   |
| Union Memory RTOTJ128VGD2EYX 128GB SSD   | 1         | 2.13%   |
| Toshiba TR150 480GB SSD                  | 1         | 2.13%   |
| Toshiba KBG40ZNT256G MEMORY 256GB        | 1         | 2.13%   |
| TO Exter nal USB 3.0 180GB               | 1         | 2.13%   |
| SPCC Solid State Disk 120GB              | 1         | 2.13%   |
| SK hynix SKHynix_HFS001TDE9X081N 1TB     | 1         | 2.13%   |
| SK hynix HCG8e  64GB                     | 1         | 2.13%   |
| SK hynix HBG4e  32GB                     | 1         | 2.13%   |
| Seagate ST2000LM007-1R8174 2TB           | 1         | 2.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 2.13%   |
| Samsung SSD 980 PRO 2TB                  | 1         | 2.13%   |
| Samsung SSD 860 EVO M.2 500GB            | 1         | 2.13%   |
| Samsung SSD 860 EVO M.2 250GB            | 1         | 2.13%   |
| Samsung SSD 860 EVO 500GB                | 1         | 2.13%   |
| Samsung SSD 850 EVO 500GB                | 1         | 2.13%   |
| Samsung SSD 850 EVO 250GB                | 1         | 2.13%   |
| Samsung NVMe SSD Drive 256GB             | 1         | 2.13%   |
| Samsung HM320II 320GB                    | 1         | 2.13%   |
| Realtek NVMe SSD Drive 512GB             | 1         | 2.13%   |
| OWC Mercury Electra 3G SSD               | 1         | 2.13%   |
| Netac SSD 256GB                          | 1         | 2.13%   |
| Micron MTFDDAV256TBN-1AR1ZABHA 256GB SSD | 1         | 2.13%   |
| Micron 1300_MTFDDAK256TDL 256GB SSD      | 1         | 2.13%   |
| Kingston SNVS2000G 2TB                   | 1         | 2.13%   |
| Kingston NVMe SSD Drive 256GB            | 1         | 2.13%   |
| JMicron Tech 250GB                       | 1         | 2.13%   |
| JMicron Generic 120GB                    | 1         | 2.13%   |
| Intel SSDSA2CW080G3 80GB                 | 1         | 2.13%   |
| HP SSD S700 500GB                        | 1         | 2.13%   |
| Crucial CT480BX500SSD1 480GB             | 1         | 2.13%   |
| Crucial CT240BX500SSD1 240GB             | 1         | 2.13%   |
| Crucial CT2000BX500SSD1 2TB              | 1         | 2.13%   |
| Corsair Force 3 SSD 240GB                | 1         | 2.13%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 40%     |
| Seagate             | 2         | 2      | 40%     |
| Samsung Electronics | 1         | 1      | 20%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 22.73%  |
| Crucial             | 3         | 4      | 13.64%  |
| Micron Technology   | 2         | 2      | 9.09%   |
| China               | 2         | 2      | 9.09%   |
| Union Memory        | 1         | 1      | 4.55%   |
| Toshiba             | 1         | 1      | 4.55%   |
| TO Exter            | 1         | 1      | 4.55%   |
| SPCC                | 1         | 1      | 4.55%   |
| OWC                 | 1         | 1      | 4.55%   |
| Netac               | 1         | 1      | 4.55%   |
| Intel               | 1         | 1      | 4.55%   |
| Hewlett-Packard     | 1         | 1      | 4.55%   |
| Corsair             | 1         | 2      | 4.55%   |
| Apple               | 1         | 1      | 4.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 19        | 24     | 46.34%  |
| NVMe    | 10        | 12     | 24.39%  |
| MMC     | 6         | 8      | 14.63%  |
| HDD     | 5         | 5      | 12.2%   |
| Unknown | 1         | 1      | 2.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 21        | 28     | 53.85%  |
| NVMe | 10        | 11     | 25.64%  |
| MMC  | 6         | 8      | 15.38%  |
| SAS  | 2         | 3      | 5.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 19        | 22     | 73.08%  |
| 0.51-1.0   | 4         | 4      | 15.38%  |
| 1.01-2.0   | 3         | 3      | 11.54%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 12        | 36.36%  |
| 251-500        | 11        | 33.33%  |
| 51-100         | 4         | 12.12%  |
| 1001-2000      | 2         | 6.06%   |
| More than 3000 | 1         | 3.03%   |
| 21-50          | 1         | 3.03%   |
| 1-20           | 1         | 3.03%   |
| 501-1000       | 1         | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 11        | 33.33%  |
| 21-50     | 7         | 21.21%  |
| 51-100    | 7         | 21.21%  |
| 101-250   | 4         | 12.12%  |
| 251-500   | 2         | 6.06%   |
| 1001-2000 | 1         | 3.03%   |
| 501-1000  | 1         | 3.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 19        | 28     | 54.29%  |
| Works    | 16        | 22     | 45.71%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 20        | 57.14%  |
| AMD                         | 4         | 11.43%  |
| SanDisk                     | 2         | 5.71%   |
| Samsung Electronics         | 2         | 5.71%   |
| Kingston Technology Company | 2         | 5.71%   |
| SK hynix                    | 1         | 2.86%   |
| Realtek Semiconductor       | 1         | 2.86%   |
| Nvidia                      | 1         | 2.86%   |
| KIOXIA                      | 1         | 2.86%   |
| ADATA Technology            | 1         | 2.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 4         | 10.81%  |
| AMD FCH SATA Controller [AHCI mode]                                          | 4         | 10.81%  |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 2         | 5.41%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 5.41%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 2         | 5.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 2         | 5.41%   |
| SK hynix Gold P31 SSD                                                        | 1         | 2.7%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                    | 1         | 2.7%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 1         | 2.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 2.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 1         | 2.7%    |
| Realtek Realtek Non-Volatile memory controller                               | 1         | 2.7%    |
| Nvidia MCP79 AHCI Controller                                                 | 1         | 2.7%    |
| KIOXIA NVMe SSD Controller BG4                                               | 1         | 2.7%    |
| Kingston Company Company Non-Volatile memory controller                      | 1         | 2.7%    |
| Kingston Company OM3PDP3 NVMe SSD                                            | 1         | 2.7%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 1         | 2.7%    |
| Intel Volume Management Device NVMe RAID Controller                          | 1         | 2.7%    |
| Intel Tiger Lake-LP SATA Controller                                          | 1         | 2.7%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 1         | 2.7%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 1         | 2.7%    |
| Intel Comet Lake SATA AHCI Controller                                        | 1         | 2.7%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 1         | 2.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 1         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                | 1         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                | 1         | 2.7%    |
| ADATA Non-Volatile memory controller                                         | 1         | 2.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 24        | 66.67%  |
| NVMe | 10        | 27.78%  |
| RAID | 1         | 2.78%   |
| IDE  | 1         | 2.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 29        | 87.88%  |
| AMD    | 4         | 12.12%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 9.09%   |
| Intel Atom CPU Z3795 @ 1.60GHz                | 2         | 6.06%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 3.03%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 3.03%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 3.03%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 3.03%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 3.03%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 3.03%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 3.03%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 3.03%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 3.03%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 3.03%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 3.03%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 3.03%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 3.03%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 3.03%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 3.03%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 1         | 3.03%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 3.03%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 3.03%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 1         | 3.03%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 1         | 3.03%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 1         | 3.03%   |
| Intel Celeron N4500 @ 1.10GHz                 | 1         | 3.03%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 3.03%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 3.03%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 1         | 3.03%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 3.03%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 3.03%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 1         | 3.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 11        | 33.33%  |
| Intel Core i7        | 4         | 12.12%  |
| Other                | 3         | 9.09%   |
| Intel Celeron        | 3         | 9.09%   |
| Intel Core 2 Duo     | 2         | 6.06%   |
| Intel Atom           | 2         | 6.06%   |
| AMD Ryzen 5          | 2         | 6.06%   |
| Intel Pentium Silver | 1         | 3.03%   |
| Intel Pentium        | 1         | 3.03%   |
| Intel Core i9        | 1         | 3.03%   |
| Intel Core i3        | 1         | 3.03%   |
| AMD Ryzen 7          | 1         | 3.03%   |
| AMD A8               | 1         | 3.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 16        | 48.48%  |
| 4      | 14        | 42.42%  |
| 10     | 1         | 3.03%   |
| 8      | 1         | 3.03%   |
| 6      | 1         | 3.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 33        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 22        | 66.67%  |
| 1      | 11        | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 33        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 54.55%  |
| 0x806c1    | 2         | 6.06%   |
| 0x206a7    | 2         | 6.06%   |
| 0x806eb    | 1         | 3.03%   |
| 0x706a8    | 1         | 3.03%   |
| 0x506c9    | 1         | 3.03%   |
| 0x40651    | 1         | 3.03%   |
| 0x306d4    | 1         | 3.03%   |
| 0x30678    | 1         | 3.03%   |
| 0x20655    | 1         | 3.03%   |
| 0x0a50000c | 1         | 3.03%   |
| 0x08600106 | 1         | 3.03%   |
| 0x08108102 | 1         | 3.03%   |
| 0x07030104 | 1         | 3.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 6         | 18.18%  |
| TigerLake     | 3         | 9.09%   |
| Skylake       | 2         | 6.06%   |
| Silvermont    | 2         | 6.06%   |
| SandyBridge   | 2         | 6.06%   |
| Penryn        | 2         | 6.06%   |
| IvyBridge     | 2         | 6.06%   |
| Haswell       | 2         | 6.06%   |
| Goldmont plus | 2         | 6.06%   |
| Zen+          | 1         | 3.03%   |
| Zen 3         | 1         | 3.03%   |
| Zen 2         | 1         | 3.03%   |
| Westmere      | 1         | 3.03%   |
| Puma          | 1         | 3.03%   |
| IceLake       | 1         | 3.03%   |
| Goldmont      | 1         | 3.03%   |
| CometLake     | 1         | 3.03%   |
| Broadwell     | 1         | 3.03%   |
| Unknown       | 1         | 3.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 27        | 64.29%  |
| Nvidia | 9         | 21.43%  |
| AMD    | 6         | 14.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 3         | 6.98%   |
| Intel UHD Graphics 620                                                                | 2         | 4.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 4.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 2         | 4.65%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 2         | 4.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 2         | 4.65%   |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                                | 1         | 2.33%   |
| Nvidia GP108M [GeForce MX230]                                                         | 1         | 2.33%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 2.33%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 2.33%   |
| Nvidia GM108M [GeForce 840M]                                                          | 1         | 2.33%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 1         | 2.33%   |
| Nvidia GK208BM [GeForce 920M]                                                         | 1         | 2.33%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 1         | 2.33%   |
| Nvidia C79 [GeForce 9400M]                                                            | 1         | 2.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 1         | 2.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 1         | 2.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 2.33%   |
| Intel JasperLake [UHD Graphics]                                                       | 1         | 2.33%   |
| Intel Iris Plus Graphics G7                                                           | 1         | 2.33%   |
| Intel HD Graphics 620                                                                 | 1         | 2.33%   |
| Intel HD Graphics 5500                                                                | 1         | 2.33%   |
| Intel HD Graphics 530                                                                 | 1         | 2.33%   |
| Intel HD Graphics 500                                                                 | 1         | 2.33%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 1         | 2.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 1         | 2.33%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 2.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 1         | 2.33%   |
| Intel Coffee Lake UHD 610 Graphics Controller                                         | 1         | 2.33%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 2.33%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                | 1         | 2.33%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 1         | 2.33%   |
| AMD Renoir                                                                            | 1         | 2.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 1         | 2.33%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 1         | 2.33%   |
| AMD Cezanne                                                                           | 1         | 2.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 18        | 54.55%  |
| Intel + Nvidia | 6         | 18.18%  |
| 1 x Nvidia     | 2         | 6.06%   |
| Intel + AMD    | 2         | 6.06%   |
| 1 x AMD        | 2         | 6.06%   |
| Other          | 1         | 3.03%   |
| 2 x AMD        | 1         | 3.03%   |
| AMD + Nvidia   | 1         | 3.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 27        | 81.82%  |
| Proprietary | 5         | 15.15%  |
| Unknown     | 1         | 3.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 81.82%  |
| 1.01-2.0   | 3         | 9.09%   |
| 7.01-8.0   | 1         | 3.03%   |
| 0.51-1.0   | 1         | 3.03%   |
| 0.01-0.5   | 1         | 3.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 11        | 30.56%  |
| BOE                     | 6         | 16.67%  |
| AU Optronics            | 4         | 11.11%  |
| Samsung Electronics     | 3         | 8.33%   |
| Apple                   | 3         | 8.33%   |
| LG Display              | 2         | 5.56%   |
| Goldstar                | 2         | 5.56%   |
| Unknown (AAA)           | 1         | 2.78%   |
| Sharp                   | 1         | 2.78%   |
| Lenovo                  | 1         | 2.78%   |
| IBM                     | 1         | 2.78%   |
| Chi Mei Optoelectronics | 1         | 2.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 2         | 5.56%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch                 | 1         | 2.78%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                  | 1         | 2.78%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch     | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch    | 1         | 2.78%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 1         | 2.78%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch              | 1         | 2.78%   |
| Lenovo LEN D27-20B LEN65F5 1920x1080 598x336mm 27.0-inch                 | 1         | 2.78%   |
| IBM LCD Monitor IBM2887 1680x1050 331x207mm 15.4-inch                    | 1         | 2.78%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                  | 1         | 2.78%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch         | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch         | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch         | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN1138 1366x768 256x144mm 11.6-inch          | 1         | 2.78%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 2.78%   |
| BOE LCD Monitor BOE08F5 1920x1080 344x194mm 15.5-inch                    | 1         | 2.78%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                    | 1         | 2.78%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                    | 1         | 2.78%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 1         | 2.78%   |
| BOE LCD Monitor BOE0685 1600x900 382x215mm 17.3-inch                     | 1         | 2.78%   |
| BOE LCD Monitor BOE05E4 1366x768 256x144mm 11.6-inch                     | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO5544 1280x800 303x189mm 14.1-inch            | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO309B 3840x2160 381x214mm 17.2-inch           | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 380x210mm 17.1-inch           | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO1AD8 1920x1200 216x136mm 10.0-inch           | 1         | 2.78%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                   | 1         | 2.78%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                   | 1         | 2.78%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 1         | 2.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 12        | 36.36%  |
| 1366x768 (WXGA)    | 10        | 30.3%   |
| 1280x800 (WXGA)    | 3         | 9.09%   |
| 1680x1050 (WSXGA+) | 2         | 6.06%   |
| 1600x900 (HD+)     | 2         | 6.06%   |
| 3840x2160 (4K)     | 1         | 3.03%   |
| 2880x1800          | 1         | 3.03%   |
| 1920x1200 (WUXGA)  | 1         | 3.03%   |
| 1440x900 (WXGA+)   | 1         | 3.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 13        | 36.11%  |
| 13     | 7         | 19.44%  |
| 17     | 4         | 11.11%  |
| 14     | 4         | 11.11%  |
| 40     | 2         | 5.56%   |
| 11     | 2         | 5.56%   |
| 27     | 1         | 2.78%   |
| 23     | 1         | 2.78%   |
| 21     | 1         | 2.78%   |
| 10     | 1         | 2.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 21        | 58.33%  |
| 201-300     | 6         | 16.67%  |
| 351-400     | 4         | 11.11%  |
| 801-900     | 2         | 5.56%   |
| 401-500     | 2         | 5.56%   |
| 501-600     | 1         | 2.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 25        | 75.76%  |
| 16/10 | 7         | 21.21%  |
| 3/2   | 1         | 3.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 13        | 36.11%  |
| 81-90          | 10        | 27.78%  |
| 121-130        | 4         | 11.11%  |
| 51-60          | 2         | 5.56%   |
| 201-250        | 2         | 5.56%   |
| 501-1000       | 2         | 5.56%   |
| 71-80          | 1         | 2.78%   |
| 41-50          | 1         | 2.78%   |
| 301-350        | 1         | 2.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 14        | 38.89%  |
| 101-120       | 13        | 36.11%  |
| 161-240       | 3         | 8.33%   |
| 51-100        | 3         | 8.33%   |
| More than 240 | 2         | 5.56%   |
| 1-50          | 1         | 2.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 27        | 81.82%  |
| 2     | 5         | 15.15%  |
| 0     | 1         | 3.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 16        | 31.37%  |
| Intel                 | 16        | 31.37%  |
| Qualcomm Atheros      | 7         | 13.73%  |
| Broadcom              | 6         | 11.76%  |
| MediaTek              | 2         | 3.92%   |
| Hewlett-Packard       | 2         | 3.92%   |
| Nvidia                | 1         | 1.96%   |
| ASIX Electronics      | 1         | 1.96%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 7         | 12.07%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 5.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 3         | 5.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 5.17%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 5.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 3.45%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 3.45%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 2         | 3.45%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 3.45%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 3.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 1.72%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 1         | 1.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.72%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 1.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 1.72%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.72%   |
| Nvidia MCP79 Ethernet                                                   | 1         | 1.72%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.72%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 1.72%   |
| Intel Wireless 8265 / 8275                                              | 1         | 1.72%   |
| Intel Wireless 8260                                                     | 1         | 1.72%   |
| Intel Wireless 7265                                                     | 1         | 1.72%   |
| Intel Wireless 7260                                                     | 1         | 1.72%   |
| Intel Wireless 3165                                                     | 1         | 1.72%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.72%   |
| Intel Ethernet Connection I219-LM                                       | 1         | 1.72%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 1.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 1.72%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.72%   |
| Intel 82577LM Gigabit Network Connection                                | 1         | 1.72%   |
| Intel 82567LM Gigabit Network Connection                                | 1         | 1.72%   |
| HP lt4120 Snapdragon X5 LTE                                             | 1         | 1.72%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 1         | 1.72%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 1.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 1.72%   |
| ASIX AX88179 Gigabit Ethernet                                           | 1         | 1.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 15        | 45.45%  |
| Broadcom              | 6         | 18.18%  |
| Qualcomm Atheros      | 5         | 15.15%  |
| Realtek Semiconductor | 4         | 12.12%  |
| MediaTek              | 2         | 6.06%   |
| Hewlett-Packard       | 1         | 3.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 9.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 9.09%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 9.09%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 6.06%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 6.06%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 6.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 3.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 3.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 3.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 3.03%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 3.03%   |
| Intel Wireless 8265 / 8275                                              | 1         | 3.03%   |
| Intel Wireless 8260                                                     | 1         | 3.03%   |
| Intel Wireless 7265                                                     | 1         | 3.03%   |
| Intel Wireless 7260                                                     | 1         | 3.03%   |
| Intel Wireless 3165                                                     | 1         | 3.03%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 3.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 3.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 3.03%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 3.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 3.03%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 1         | 3.03%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 3.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 3.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 14        | 56%     |
| Intel                 | 4         | 16%     |
| Qualcomm Atheros      | 2         | 8%      |
| Broadcom              | 2         | 8%      |
| Nvidia                | 1         | 4%      |
| Hewlett-Packard       | 1         | 4%      |
| ASIX Electronics      | 1         | 4%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 28%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 12%     |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 8%      |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 8%      |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 4%      |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 4%      |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 4%      |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 4%      |
| Nvidia MCP79 Ethernet                                             | 1         | 4%      |
| Intel Ethernet Connection I219-LM                                 | 1         | 4%      |
| Intel Ethernet Connection I218-LM                                 | 1         | 4%      |
| Intel 82577LM Gigabit Network Connection                          | 1         | 4%      |
| Intel 82567LM Gigabit Network Connection                          | 1         | 4%      |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 4%      |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 4%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 32        | 57.14%  |
| Ethernet | 24        | 42.86%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 29        | 85.29%  |
| Ethernet | 5         | 14.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 20        | 60.61%  |
| 1     | 11        | 33.33%  |
| 0     | 2         | 6.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 22        | 66.67%  |
| Yes  | 11        | 33.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 44.83%  |
| Realtek Semiconductor           | 3         | 10.34%  |
| Broadcom                        | 3         | 10.34%  |
| Apple                           | 3         | 10.34%  |
| Qualcomm Atheros Communications | 2         | 6.9%    |
| IMC Networks                    | 2         | 6.9%    |
| Unknown                         | 1         | 3.45%   |
| Foxconn International           | 1         | 3.45%   |
| Dell                            | 1         | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 5         | 17.24%  |
| Intel AX201 Bluetooth                              | 3         | 10.34%  |
| Realtek Bluetooth Radio                            | 2         | 6.9%    |
| Qualcomm Atheros  Bluetooth Device                 | 2         | 6.9%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 2         | 6.9%    |
| Intel AX200 Bluetooth                              | 2         | 6.9%    |
| Apple Bluetooth Host Controller                    | 2         | 6.9%    |
| Unknown Bluetooth Device                           | 1         | 3.45%   |
| Realtek RTL8723B Bluetooth                         | 1         | 3.45%   |
| Intel Wireless-AC 3168 Bluetooth                   | 1         | 3.45%   |
| IMC Networks Wireless_Device                       | 1         | 3.45%   |
| IMC Networks Bluetooth Radio                       | 1         | 3.45%   |
| Foxconn International BCM43142A0 Bluetooth module  | 1         | 3.45%   |
| Dell DW375 Bluetooth Module                        | 1         | 3.45%   |
| Broadcom BCM43142A0 Bluetooth Device               | 1         | 3.45%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR               | 1         | 3.45%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 3.45%   |
| Apple Bluetooth USB Host Controller                | 1         | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 26        | 78.79%  |
| AMD    | 4         | 12.12%  |
| Nvidia | 3         | 9.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 4         | 10%     |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 7.5%    |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 7.5%    |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 5%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 5%      |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 5%      |
| Intel 8 Series HD Audio Controller                                         | 2         | 5%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 5%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 5%      |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 5%      |
| Nvidia TU104 HD Audio Controller                                           | 1         | 2.5%    |
| Nvidia MCP79 High Definition Audio                                         | 1         | 2.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 2.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 2.5%    |
| Intel Jasper Lake HD Audio                                                 | 1         | 2.5%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 2.5%    |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 2.5%    |
| Intel Comet Lake PCH cAVS                                                  | 1         | 2.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 2.5%    |
| Intel Broadwell-U Audio Controller                                         | 1         | 2.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 2.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 2.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 2.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 2.5%    |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 2.5%    |
| AMD FCH Azalia Controller                                                  | 1         | 2.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 33.33%  |
| SK hynix            | 6         | 25%     |
| Kingston            | 3         | 12.5%   |
| Unknown (ABCD)      | 1         | 4.17%   |
| Unknown             | 1         | 4.17%   |
| Teikon              | 1         | 4.17%   |
| Micron Technology   | 1         | 4.17%   |
| fef5                | 1         | 4.17%   |
| Elpida              | 1         | 4.17%   |
| Unknown             | 1         | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 4%      |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 1         | 4%      |
| Teikon RAM TMT41GS6BFR8A-PBHJ 8GB SODIMM DDR3 1600MT/s           | 1         | 4%      |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 4%      |
| SK hynix RAM Module 4GB SODIMM DDR4 2133MT/s                     | 1         | 4%      |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 4%      |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s             | 1         | 4%      |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 4%      |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 4%      |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 1         | 4%      |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 4%      |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 4%      |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 4%      |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 4%      |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s            | 1         | 4%      |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 4%      |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 4%      |
| Samsung RAM K4F8E304HB-MGCJ 1GB 2400MT/s                         | 1         | 4%      |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 4%      |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s            | 1         | 4%      |
| Kingston RAM 9905624-059.A00G 8GB SODIMM DDR4 2667MT/s           | 1         | 4%      |
| Kingston RAM 9905428-417.A00LF 8GB SODIMM DDR3 1600MT/s          | 1         | 4%      |
| fef5 RAM K4F8E304HB-MGCJ 1GB 2400MT/s                            | 1         | 4%      |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 1         | 4%      |
| Unknown                                                          | 1         | 4%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 10        | 50%     |
| DDR3    | 6         | 30%     |
| LPDDR4  | 3         | 15%     |
| Unknown | 1         | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 15        | 78.95%  |
| Row Of Chips | 2         | 10.53%  |
| Chip         | 1         | 5.26%   |
| Unknown      | 1         | 5.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 8         | 40%     |
| 4096  | 6         | 30%     |
| 16384 | 2         | 10%     |
| 2048  | 2         | 10%     |
| 32768 | 1         | 5%      |
| 1024  | 1         | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 4         | 19.05%  |
| 2400  | 4         | 19.05%  |
| 1600  | 4         | 19.05%  |
| 2667  | 3         | 14.29%  |
| 4267  | 1         | 4.76%   |
| 3266  | 1         | 4.76%   |
| 2133  | 1         | 4.76%   |
| 1334  | 1         | 4.76%   |
| 1067  | 1         | 4.76%   |
| 1066  | 1         | 4.76%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| HP LaserJet 1320 | 1         | 50%     |
| Canon LiDE 400   | 1         | 50%     |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 8         | 32%     |
| Syntek                        | 3         | 12%     |
| Realtek Semiconductor         | 3         | 12%     |
| IMC Networks                  | 3         | 12%     |
| Apple                         | 3         | 12%     |
| Sunplus Innovation Technology | 1         | 4%      |
| Quanta                        | 1         | 4%      |
| Luxvisions Innotech Limited   | 1         | 4%      |
| Alcor Micro                   | 1         | 4%      |
| Acer                          | 1         | 4%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Syntek Integrated Camera                 | 2         | 8%      |
| Chicony Integrated Camera                | 2         | 8%      |
| Apple FaceTime HD Camera                 | 2         | 8%      |
| Syntek Lenovo EasyCamera                 | 1         | 4%      |
| Sunplus HD WebCam                        | 1         | 4%      |
| Realtek Lenovo EasyCamera                | 1         | 4%      |
| Realtek Integrated_Webcam_HD             | 1         | 4%      |
| Realtek Integrated Webcam                | 1         | 4%      |
| Quanta USB2.0 HD UVC WebCam              | 1         | 4%      |
| Luxvisions Innotech Limited HP HD Camera | 1         | 4%      |
| IMC Networks USB2.0 VGA UVC WebCam       | 1         | 4%      |
| IMC Networks USB2.0 HD UVC WebCam        | 1         | 4%      |
| IMC Networks Integrated Camera           | 1         | 4%      |
| Chicony XiaoMi USB 2.0 Webcam            | 1         | 4%      |
| Chicony USB2.0 Camera                    | 1         | 4%      |
| Chicony HP Truevision HD camera          | 1         | 4%      |
| Chicony HP Integrated Webcam             | 1         | 4%      |
| Chicony HP HD Camera                     | 1         | 4%      |
| Chicony HD Webcam                        | 1         | 4%      |
| Apple Built-in iSight                    | 1         | 4%      |
| Alcor Micro SHUNCCM2MP                   | 1         | 4%      |
| Acer EasyCamera                          | 1         | 4%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 2         | 33.33%  |
| Synaptics                  | 2         | 33.33%  |
| Shenzhen Goodix Technology | 1         | 16.67%  |
| Elan Microelectronics      | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 16.67%  |
| Validity Sensors Swipe Fingerprint Sensor         | 1         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 16.67%  |
| Shenzhen Goodix  FingerPrint Device               | 1         | 16.67%  |
| Elan ELAN:Fingerprint                             | 1         | 16.67%  |
| Unknown                                           | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 19        | 57.58%  |
| 1     | 9         | 27.27%  |
| 2     | 3         | 9.09%   |
| 6     | 1         | 3.03%   |
| 3     | 1         | 3.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 6         | 30%     |
| Net/wireless             | 3         | 15%     |
| Sound                    | 2         | 10%     |
| Graphics card            | 2         | 10%     |
| Chipcard                 | 2         | 10%     |
| Camera                   | 2         | 10%     |
| Multimedia controller    | 1         | 5%      |
| Communication controller | 1         | 5%      |
| Bluetooth                | 1         | 5%      |

