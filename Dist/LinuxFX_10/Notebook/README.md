LinuxFX 10 - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for LinuxFX 10.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=windowsfx-10

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

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Medion   | S4216                       | [677bd3ecb4](https://linux-hardware.org/?probe=677bd3ecb4) | Aug 27, 2021 |
| Medion   | S4216                       | [a0ae7753cf](https://linux-hardware.org/?probe=a0ae7753cf) | Aug 26, 2021 |
| Dell     | Inspiron 3421               | [06a0a6486b](https://linux-hardware.org/?probe=06a0a6486b) | Aug 26, 2021 |
| Dell     | Latitude E5520              | [cae8dd2173](https://linux-hardware.org/?probe=cae8dd2173) | Jul 27, 2021 |
| Dell     | Latitude E5520              | [0112c3a302](https://linux-hardware.org/?probe=0112c3a302) | Jul 22, 2021 |
| Samsung  | 305E4A/305E5A/305E7A        | [3db60d4f9a](https://linux-hardware.org/?probe=3db60d4f9a) | Jun 01, 2021 |
| Lenovo   | ThinkPad T450s 20BWS0YF0... | [7b1e0f2693](https://linux-hardware.org/?probe=7b1e0f2693) | May 11, 2021 |
| Acer     | Aspire 5755G                | [0984c7aebc](https://linux-hardware.org/?probe=0984c7aebc) | Mar 18, 2021 |
| Acer     | Aspire 5755G                | [861fb95171](https://linux-hardware.org/?probe=861fb95171) | Mar 09, 2021 |
| ASUSTek  | K50C                        | [d6ac6b2de1](https://linux-hardware.org/?probe=d6ac6b2de1) | Feb 18, 2021 |
| ASUSTek  | K50C                        | [a899af5e96](https://linux-hardware.org/?probe=a899af5e96) | Feb 18, 2021 |
| Dell     | Inspiron 1525               | [30d9ab855e](https://linux-hardware.org/?probe=30d9ab855e) | Feb 16, 2021 |
| Dell     | Inspiron 1525               | [a37ef6324c](https://linux-hardware.org/?probe=a37ef6324c) | Feb 16, 2021 |
| Lenovo   | ThinkPad X1 Carbon 2nd F... | [799c301ad6](https://linux-hardware.org/?probe=799c301ad6) | Feb 08, 2021 |
| Pegatron | B34C                        | [4c3a4f9ad1](https://linux-hardware.org/?probe=4c3a4f9ad1) | Feb 05, 2021 |
| ASUSTek  | TUF Gaming FX506LI_FX506... | [a22da47202](https://linux-hardware.org/?probe=a22da47202) | Jan 30, 2021 |
| Acer     | Aspire A515-51G             | [3300b2bb9d](https://linux-hardware.org/?probe=3300b2bb9d) | Jan 22, 2021 |
| Lenovo   | Y70-70 Touch 80DU           | [023b353ca8](https://linux-hardware.org/?probe=023b353ca8) | Dec 22, 2020 |
| Acer     | Aspire 5720Z                | [38045109f8](https://linux-hardware.org/?probe=38045109f8) | Nov 29, 2020 |
| Toshiba  | Satellite C50D-A-12R        | [2b5e2b26b2](https://linux-hardware.org/?probe=2b5e2b26b2) | Nov 23, 2020 |
| Gigabyte | P57V6                       | [ec76a0907c](https://linux-hardware.org/?probe=ec76a0907c) | Nov 15, 2020 |
| Acer     | Aspire ES1-512              | [328c13ce38](https://linux-hardware.org/?probe=328c13ce38) | Oct 25, 2020 |
| Acer     | Aspire ES1-512              | [59368b9e58](https://linux-hardware.org/?probe=59368b9e58) | Oct 24, 2020 |
| Acer     | Aspire 6930G                | [1519ec67b5](https://linux-hardware.org/?probe=1519ec67b5) | Sep 07, 2020 |
| Acer     | Aspire 6930G                | [51b6611d94](https://linux-hardware.org/?probe=51b6611d94) | Sep 06, 2020 |
| Dell     | Inspiron 15-3567            | [d7fbcdbfbe](https://linux-hardware.org/?probe=d7fbcdbfbe) | Sep 03, 2020 |
| HP       | Compaq Presario CQ50        | [b82778b925](https://linux-hardware.org/?probe=b82778b925) | Sep 01, 2020 |
| Gigabyte | P57V6                       | [7f8d44d28e](https://linux-hardware.org/?probe=7f8d44d28e) | Aug 30, 2020 |
| HP       | ProBook 6560b               | [99a7a9817b](https://linux-hardware.org/?probe=99a7a9817b) | Aug 26, 2020 |
| HP       | ProBook 6560b               | [b9893a704d](https://linux-hardware.org/?probe=b9893a704d) | Aug 26, 2020 |
| Olivetti | P55-AEU-323-4G320           | [c08737d73c](https://linux-hardware.org/?probe=c08737d73c) | Aug 23, 2020 |
| Lenovo   | G505 20240                  | [aa6a5c7462](https://linux-hardware.org/?probe=aa6a5c7462) | Aug 22, 2020 |
| ASUSTek  | K72Jr                       | [51cd547219](https://linux-hardware.org/?probe=51cd547219) | Aug 18, 2020 |
| ASUSTek  | K72Jr                       | [d68a58547e](https://linux-hardware.org/?probe=d68a58547e) | Aug 15, 2020 |
| Dell     | Inspiron 5423               | [1f3e63e601](https://linux-hardware.org/?probe=1f3e63e601) | Jul 24, 2020 |
| Acer     | Aspire E1-531               | [6104770d46](https://linux-hardware.org/?probe=6104770d46) | Jul 23, 2020 |
| Dell     | Vostro 1000                 | [ffb49e4b86](https://linux-hardware.org/?probe=ffb49e4b86) | Jul 22, 2020 |
| Positivo | Mobile                      | [7ac9083ae4](https://linux-hardware.org/?probe=7ac9083ae4) | Jul 21, 2020 |
| HP       | Mini 210-1000               | [d1e83a2d9b](https://linux-hardware.org/?probe=d1e83a2d9b) | Jul 19, 2020 |
| HP       | 250 G6 Notebook PC          | [bc9d23a74c](https://linux-hardware.org/?probe=bc9d23a74c) | Jul 02, 2020 |
| HP       | 250 G6 Notebook PC          | [b1757b232f](https://linux-hardware.org/?probe=b1757b232f) | Jul 02, 2020 |
| Lenovo   | G550 2958                   | [6cfc44a819](https://linux-hardware.org/?probe=6cfc44a819) | Jun 11, 2020 |
| Lenovo   | G550 2958                   | [95b68a8144](https://linux-hardware.org/?probe=95b68a8144) | Jun 11, 2020 |
| Dell     | Inspiron 3520               | [c78c5e6395](https://linux-hardware.org/?probe=c78c5e6395) | May 16, 2020 |
| HP       | EliteBook Folio 9470m       | [f0b4ebc551](https://linux-hardware.org/?probe=f0b4ebc551) | May 16, 2020 |
| HP       | G42                         | [5c1017a089](https://linux-hardware.org/?probe=5c1017a089) | May 11, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.6.15-windowsfx-10-generic | 5         | 16.13%  |
| 5.4.0-52-generic            | 4         | 12.9%   |
| 5.7.15-050715-generic       | 3         | 9.68%   |
| 5.4.0-65-generic            | 3         | 9.68%   |
| 5.4.0-42-generic            | 3         | 9.68%   |
| 5.4.0-29-generic            | 3         | 9.68%   |
| 5.7.8-windowsfx-generic     | 2         | 6.45%   |
| 5.5.19-050519-generic       | 2         | 6.45%   |
| 5.4.0-73-generic            | 2         | 6.45%   |
| 5.4.0-72-generic            | 2         | 6.45%   |
| 5.4.0-54-generic            | 1         | 3.23%   |
| 5.10.2-051002-generic       | 1         | 3.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 18        | 58.06%  |
| 5.6.15  | 5         | 16.13%  |
| 5.7.15  | 3         | 9.68%   |
| 5.7.8   | 2         | 6.45%   |
| 5.5.19  | 2         | 6.45%   |
| 5.10.2  | 1         | 3.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 18        | 58.06%  |
| 5.7     | 5         | 16.13%  |
| 5.6     | 5         | 16.13%  |
| 5.5     | 2         | 6.45%   |
| 5.10    | 1         | 3.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 31        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| X-Cinnamon | 25        | 80.65%  |
| KDE        | 3         | 9.68%   |
| Cinnamon   | 3         | 9.68%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 31        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 17        | 54.84%  |
| SDDM    | 7         | 22.58%  |
| LightDM | 7         | 22.58%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| pt_BR | 11        | 35.48%  |
| pl_PL | 3         | 9.68%   |
| it_IT | 3         | 9.68%   |
| fr_FR | 2         | 6.45%   |
| es_AR | 2         | 6.45%   |
| en_US | 2         | 6.45%   |
| en_AU | 2         | 6.45%   |
| ro_RO | 1         | 3.23%   |
| es_ES | 1         | 3.23%   |
| es_CL | 1         | 3.23%   |
| en_ZA | 1         | 3.23%   |
| en_CA | 1         | 3.23%   |
| C     | 1         | 3.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 20        | 64.52%  |
| EFI  | 11        | 35.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ext4 | 31        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 28        | 90.32%  |
| GPT     | 2         | 6.45%   |
| MBR     | 1         | 3.23%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 27        | 87.1%   |
| Yes       | 4         | 12.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 27        | 87.1%   |
| Yes       | 4         | 12.9%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 6         | 19.35%  |
| Dell                | 6         | 19.35%  |
| Lenovo              | 5         | 16.13%  |
| Acer                | 4         | 12.9%   |
| ASUSTek Computer    | 3         | 9.68%   |
| Toshiba             | 1         | 3.23%   |
| Samsung Electronics | 1         | 3.23%   |
| Positivo            | 1         | 3.23%   |
| Pegatron            | 1         | 3.23%   |
| Olivetti            | 1         | 3.23%   |
| Medion              | 1         | 3.23%   |
| Gigabyte Technology | 1         | 3.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Toshiba Satellite C50D-A-12R          | 1         | 3.23%   |
| Samsung 305E4A/305E5A/305E7A          | 1         | 3.23%   |
| Positivo Mobile                       | 1         | 3.23%   |
| Pegatron B34C                         | 1         | 3.23%   |
| Olivetti P55-AEU-323-4G320            | 1         | 3.23%   |
| Medion S4216                          | 1         | 3.23%   |
| Lenovo Y70-70 Touch 80DU              | 1         | 3.23%   |
| Lenovo ThinkPad X1 Carbon 2nd F2G3H4J | 1         | 3.23%   |
| Lenovo ThinkPad T450s 20BWS0YF00      | 1         | 3.23%   |
| Lenovo G550 2958                      | 1         | 3.23%   |
| Lenovo G505 20240                     | 1         | 3.23%   |
| HP ProBook 6560b                      | 1         | 3.23%   |
| HP Mini 210-1000                      | 1         | 3.23%   |
| HP G42                                | 1         | 3.23%   |
| HP EliteBook Folio 9470m              | 1         | 3.23%   |
| HP Compaq Presario CQ50               | 1         | 3.23%   |
| HP 250 G6 Notebook PC                 | 1         | 3.23%   |
| Gigabyte P57V6                        | 1         | 3.23%   |
| Dell Vostro 1000                      | 1         | 3.23%   |
| Dell Inspiron 5423                    | 1         | 3.23%   |
| Dell Inspiron 3520                    | 1         | 3.23%   |
| Dell Inspiron 3421                    | 1         | 3.23%   |
| Dell Inspiron 1525                    | 1         | 3.23%   |
| Dell Inspiron 15-3567                 | 1         | 3.23%   |
| ASUS TUF Gaming FX506LI_FX506LI       | 1         | 3.23%   |
| ASUS K72Jr                            | 1         | 3.23%   |
| ASUS K50C                             | 1         | 3.23%   |
| Acer Aspire ES1-512                   | 1         | 3.23%   |
| Acer Aspire E1-531                    | 1         | 3.23%   |
| Acer Aspire A515-51G                  | 1         | 3.23%   |
| Acer Aspire 5720Z                     | 1         | 3.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Dell Inspiron              | 5         | 16.13%  |
| Acer Aspire                | 4         | 12.9%   |
| Lenovo ThinkPad            | 2         | 6.45%   |
| Toshiba Satellite          | 1         | 3.23%   |
| Samsung 305E4A             | 1         | 3.23%   |
| Positivo Mobile            | 1         | 3.23%   |
| Pegatron B34C              | 1         | 3.23%   |
| Olivetti P55-AEU-323-4G320 | 1         | 3.23%   |
| Medion S4216               | 1         | 3.23%   |
| Lenovo Y70-70              | 1         | 3.23%   |
| Lenovo G550                | 1         | 3.23%   |
| Lenovo G505                | 1         | 3.23%   |
| HP ProBook                 | 1         | 3.23%   |
| HP Mini                    | 1         | 3.23%   |
| HP G42                     | 1         | 3.23%   |
| HP EliteBook               | 1         | 3.23%   |
| HP Compaq                  | 1         | 3.23%   |
| HP 250                     | 1         | 3.23%   |
| Gigabyte P57V6             | 1         | 3.23%   |
| Dell Vostro                | 1         | 3.23%   |
| ASUS TUF                   | 1         | 3.23%   |
| ASUS K72Jr                 | 1         | 3.23%   |
| ASUS K50C                  | 1         | 3.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 6         | 19.35%  |
| 2015    | 4         | 12.9%   |
| 2011    | 4         | 12.9%   |
| 2019    | 3         | 9.68%   |
| 2018    | 2         | 6.45%   |
| 2014    | 2         | 6.45%   |
| 2012    | 2         | 6.45%   |
| 2009    | 2         | 6.45%   |
| 2008    | 2         | 6.45%   |
| 2020    | 1         | 3.23%   |
| 2010    | 1         | 3.23%   |
| 2006    | 1         | 3.23%   |
| Unknown | 1         | 3.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 31        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 30        | 93.75%  |
| Enabled  | 2         | 6.25%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 31        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 15        | 48.39%  |
| 4.01-8.0   | 9         | 29.03%  |
| 16.01-24.0 | 3         | 9.68%   |
| 1.01-2.0   | 2         | 6.45%   |
| 2.01-3.0   | 1         | 3.23%   |
| 8.01-16.0  | 1         | 3.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 19        | 61.29%  |
| 3.01-4.0 | 6         | 19.35%  |
| 2.01-3.0 | 4         | 12.9%   |
| 4.01-8.0 | 1         | 3.23%   |
| 0.51-1.0 | 1         | 3.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 26        | 83.87%  |
| 2      | 4         | 12.9%   |
| 3      | 1         | 3.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 70.97%  |
| No        | 9         | 29.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 96.77%  |
| No        | 1         | 3.23%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 17        | 54.84%  |
| No        | 14        | 45.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Brazil       | 11        | 35.48%  |
| Poland       | 3         | 9.68%   |
| Italy        | 3         | 9.68%   |
| USA          | 2         | 6.45%   |
| Australia    | 2         | 6.45%   |
| Argentina    | 2         | 6.45%   |
| Spain        | 1         | 3.23%   |
| South Africa | 1         | 3.23%   |
| Russia       | 1         | 3.23%   |
| Romania      | 1         | 3.23%   |
| France       | 1         | 3.23%   |
| Chile        | 1         | 3.23%   |
| Canada       | 1         | 3.23%   |
| Cameroon     | 1         | 3.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Krakow         | 2         | 6.25%   |
| Curitiba       | 2         | 6.25%   |
| Zielonka       | 1         | 3.13%   |
| Winston-Salem  | 1         | 3.13%   |
| Villemomble    | 1         | 3.13%   |
| Vila Velha     | 1         | 3.13%   |
| Sydney         | 1         | 3.13%   |
| S??o Paulo     | 1         | 3.13%   |
| Sao Bernardo   | 1         | 3.13%   |
| Salerno        | 1         | 3.13%   |
| Saladas        | 1         | 3.13%   |
| Rosario        | 1         | 3.13%   |
| Recife         | 1         | 3.13%   |
| Ramenskoye     | 1         | 3.13%   |
| Porto Alegre   | 1         | 3.13%   |
| Pontevedra     | 1         | 3.13%   |
| Pietra Ligure  | 1         | 3.13%   |
| Monserrato     | 1         | 3.13%   |
| Londrina       | 1         | 3.13%   |
| Launceston     | 1         | 3.13%   |
| Johannesburg   | 1         | 3.13%   |
| Itatiba        | 1         | 3.13%   |
| Hobart         | 1         | 3.13%   |
| Edmundston     | 1         | 3.13%   |
| Douala         | 1         | 3.13%   |
| Cincinnati     | 1         | 3.13%   |
| Central        | 1         | 3.13%   |
| Belo Horizonte | 1         | 3.13%   |
| Bel?�m         | 1         | 3.13%   |
| Arad           | 1         | 3.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 20%     |
| WDC                 | 6         | 6      | 17.14%  |
| Toshiba             | 4         | 4      | 11.43%  |
| Kingston            | 4         | 4      | 11.43%  |
| Samsung Electronics | 3         | 3      | 8.57%   |
| Unknown             | 2         | 3      | 5.71%   |
| LITEONIT            | 2         | 2      | 5.71%   |
| Hitachi             | 2         | 3      | 5.71%   |
| HGST                | 2         | 3      | 5.71%   |
| SanDisk             | 1         | 1      | 2.86%   |
| GOODRAM             | 1         | 1      | 2.86%   |
| A-DATA Technology   | 1         | 1      | 2.86%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB            | 2         | 5.71%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 2.86%   |
| WDC WD5000LPVT-24G33T1 500GB        | 1         | 2.86%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 1         | 2.86%   |
| WDC WD3200BEVT-80A0RT0 320GB        | 1         | 2.86%   |
| WDC WD1200BEVS-75UST0 120GB         | 1         | 2.86%   |
| WDC WD10JPVX-60JC3T1 1TB            | 1         | 2.86%   |
| Unknown NVMe SSD Drive 512GB        | 1         | 2.86%   |
| Unknown MMC Card  8GB               | 1         | 2.86%   |
| Toshiba MQ01ABF032 320GB            | 1         | 2.86%   |
| Toshiba MK2561GSYN 250GB            | 1         | 2.86%   |
| Seagate ST9320325AS 320GB           | 1         | 2.86%   |
| Seagate ST9160827AS 160GB           | 1         | 2.86%   |
| Seagate ST9160314AS 160GB           | 1         | 2.86%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 2.86%   |
| Seagate ST500LM021-1KJ152 500GB     | 1         | 2.86%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 2.86%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 2.86%   |
| SanDisk SSD PLUS 1000GB             | 1         | 2.86%   |
| Samsung SSD 850 EVO 250GB           | 1         | 2.86%   |
| Samsung MZMPC032HBCD-000D1 32GB SSD | 1         | 2.86%   |
| Samsung HM321HI 320GB               | 1         | 2.86%   |
| LITEONIT LMT-256M6M-HP 256GB SSD    | 1         | 2.86%   |
| LITEONIT LGT-256M6G 256GB SSD       | 1         | 2.86%   |
| Kingston SV300S37A120G 120GB SSD    | 1         | 2.86%   |
| Kingston SUV400S37120G 120GB SSD    | 1         | 2.86%   |
| Kingston SA400S37240G 240GB SSD     | 1         | 2.86%   |
| Kingston NVMe SSD Drive 512GB       | 1         | 2.86%   |
| Hitachi HTS722012K9A300 120GB       | 1         | 2.86%   |
| Hitachi HTS545050B9A300 500GB       | 1         | 2.86%   |
| HGST HTS721010A9E630 1TB            | 1         | 2.86%   |
| HGST HTS545025A7E380 250GB          | 1         | 2.86%   |
| GOODRAM SSDPR-CX300-240 240GB       | 1         | 2.86%   |
| A-DATA SU750 256GB SSD              | 1         | 2.86%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 31.82%  |
| WDC                 | 6         | 6      | 27.27%  |
| Toshiba             | 4         | 4      | 18.18%  |
| Hitachi             | 2         | 3      | 9.09%   |
| HGST                | 2         | 3      | 9.09%   |
| Samsung Electronics | 1         | 1      | 4.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 3         | 3      | 30%     |
| Samsung Electronics | 2         | 2      | 20%     |
| LITEONIT            | 2         | 2      | 20%     |
| SanDisk             | 1         | 1      | 10%     |
| GOODRAM             | 1         | 1      | 10%     |
| A-DATA Technology   | 1         | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 24     | 61.76%  |
| SSD  | 10        | 10     | 29.41%  |
| NVMe | 2         | 3      | 5.88%   |
| MMC  | 1         | 1      | 2.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 30        | 34     | 90.91%  |
| NVMe | 2         | 3      | 6.06%   |
| MMC  | 1         | 1      | 3.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 27        | 29     | 87.1%   |
| 0.51-1.0   | 4         | 5      | 12.9%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 13        | 40.63%  |
| 251-500    | 10        | 31.25%  |
| 501-1000   | 3         | 9.38%   |
| 21-50      | 2         | 6.25%   |
| 1001-2000  | 2         | 6.25%   |
| 1-20       | 1         | 3.13%   |
| 51-100     | 1         | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 17        | 53.13%  |
| 21-50    | 10        | 31.25%  |
| 501-1000 | 2         | 6.25%   |
| 251-500  | 1         | 3.13%   |
| 101-250  | 1         | 3.13%   |
| 51-100   | 1         | 3.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 50%     |
| Hitachi HTS722012K9A300 120GB   | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 100%    |

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
| Detected | 28        | 34     | 87.5%   |
| Malfunc  | 2         | 2      | 6.25%   |
| Works    | 2         | 2      | 6.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 24        | 72.73%  |
| AMD                              | 5         | 15.15%  |
| Silicon Integrated Systems [SiS] | 2         | 6.06%   |
| Kingston Technology Company      | 1         | 3.03%   |
| ADATA Technology                 | 1         | 3.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 12.2%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 7.32%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 7.32%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 4.88%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 4.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 4.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 4.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 4.88%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 2         | 4.88%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 2         | 4.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 4.88%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 2.44%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 2.44%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 2.44%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 2.44%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 2.44%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 2.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 2.44%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 2.44%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 1         | 2.44%   |
| AMD SB600 IDE                                                                  | 1         | 2.44%   |
| AMD FCH SATA Controller [IDE mode]                                             | 1         | 2.44%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1         | 2.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 27        | 72.97%  |
| IDE  | 7         | 18.92%  |
| NVMe | 2         | 5.41%   |
| RAID | 1         | 2.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 26        | 83.87%  |
| AMD    | 5         | 16.13%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| AMD A4-5000 APU with Radeon HD Graphics     | 3         | 9.68%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 2         | 6.45%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 3.23%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz      | 1         | 3.23%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 3.23%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz      | 1         | 3.23%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 1         | 3.23%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 3.23%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 3.23%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 3.23%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 3.23%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 3.23%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 3.23%   |
| Intel Core i5-3437U CPU @ 1.90GHz           | 1         | 3.23%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 3.23%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 3.23%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 3.23%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 3.23%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 1         | 3.23%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 1         | 3.23%   |
| Intel Core i3-3227U CPU @ 1.90GHz           | 1         | 3.23%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1         | 3.23%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz        | 1         | 3.23%   |
| Intel Celeron D CPU 220 @ 1.20GHz           | 1         | 3.23%   |
| Intel Celeron CPU N2940 @ 1.83GHz           | 1         | 3.23%   |
| Intel Atom CPU N450 @ 1.66GHz               | 1         | 3.23%   |
| AMD Athlon 64 X2 Dual-Core Processor TK-55  | 1         | 3.23%   |
| AMD A6-3420M APU with Radeon HD Graphics    | 1         | 3.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 7         | 22.58%  |
| Intel Core i7           | 5         | 16.13%  |
| Intel Core i3           | 5         | 16.13%  |
| Intel Pentium Dual      | 3         | 9.68%   |
| AMD A4                  | 3         | 9.68%   |
| Intel Pentium Dual-Core | 1         | 3.23%   |
| Intel Pentium           | 1         | 3.23%   |
| Intel Core 2 Duo        | 1         | 3.23%   |
| Intel Celeron D         | 1         | 3.23%   |
| Intel Celeron           | 1         | 3.23%   |
| Intel Atom              | 1         | 3.23%   |
| AMD Athlon 64 X2        | 1         | 3.23%   |
| AMD A6                  | 1         | 3.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 20        | 64.52%  |
| 4      | 8         | 25.81%  |
| 1      | 3         | 9.68%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 31        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 16        | 51.61%  |
| 1      | 15        | 48.39%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 31        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306a9    | 6         | 19.35%  |
| Unknown    | 4         | 12.9%   |
| 0x806e9    | 3         | 9.68%   |
| 0x6fd      | 3         | 9.68%   |
| 0x206a7    | 2         | 6.45%   |
| 0x20655    | 2         | 6.45%   |
| 0x0700010f | 2         | 6.45%   |
| 0xa0652    | 1         | 3.23%   |
| 0x506e3    | 1         | 3.23%   |
| 0x40651    | 1         | 3.23%   |
| 0x306d4    | 1         | 3.23%   |
| 0x30678    | 1         | 3.23%   |
| 0x1067a    | 1         | 3.23%   |
| 0x10661    | 1         | 3.23%   |
| 0x07000106 | 1         | 3.23%   |
| 0x03000027 | 1         | 3.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| IvyBridge   | 6         | 19.35%  |
| Core        | 4         | 12.9%   |
| KabyLake    | 3         | 9.68%   |
| Jaguar      | 3         | 9.68%   |
| Westmere    | 2         | 6.45%   |
| SandyBridge | 2         | 6.45%   |
| Penryn      | 2         | 6.45%   |
| Haswell     | 2         | 6.45%   |
| Skylake     | 1         | 3.23%   |
| Silvermont  | 1         | 3.23%   |
| K8 Hammer   | 1         | 3.23%   |
| K10 Llano   | 1         | 3.23%   |
| CometLake   | 1         | 3.23%   |
| Broadwell   | 1         | 3.23%   |
| Bonnell     | 1         | 3.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 23        | 63.89%  |
| AMD                              | 6         | 16.67%  |
| Nvidia                           | 5         | 13.89%  |
| Silicon Integrated Systems [SiS] | 2         | 5.56%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 6         | 15.79%  |
| Intel HD Graphics 620                                                     | 3         | 7.89%   |
| AMD Kabini [Radeon HD 8330]                                               | 3         | 7.89%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter         | 2         | 5.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 2         | 5.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 2         | 5.26%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 2         | 5.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 5.26%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 2.63%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 1         | 2.63%   |
| Nvidia GM108M [GeForce 940MX]                                             | 1         | 2.63%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 2.63%   |
| Nvidia G84M [GeForce 8600M GT]                                            | 1         | 2.63%   |
| Intel HD Graphics 5500                                                    | 1         | 2.63%   |
| Intel HD Graphics 530                                                     | 1         | 2.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 2.63%   |
| Intel Core Processor Integrated Graphics Controller                       | 1         | 2.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 1         | 2.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1         | 2.63%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 1         | 2.63%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1         | 2.63%   |
| AMD Sumo [Radeon HD 6520G]                                                | 1         | 2.63%   |
| AMD RS482M [Mobility Radeon Xpress 200]                                   | 1         | 2.63%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                              | 1         | 2.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 19        | 61.29%  |
| 1 x AMD        | 6         | 19.35%  |
| Intel + Nvidia | 4         | 12.9%   |
| 1 x SiS        | 2         | 6.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 28        | 90.32%  |
| Unknown | 3         | 9.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 71.88%  |
| 0.01-0.5   | 5         | 15.63%  |
| 5.01-6.0   | 1         | 3.13%   |
| 3.01-4.0   | 1         | 3.13%   |
| 1.01-2.0   | 1         | 3.13%   |
| 0.51-1.0   | 1         | 3.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 9         | 31.03%  |
| LG Display              | 7         | 24.14%  |
| Samsung Electronics     | 5         | 17.24%  |
| Chimei Innolux          | 4         | 13.79%  |
| BOE                     | 2         | 6.9%    |
| Chi Mei Optoelectronics | 1         | 3.45%   |
| Ancor Communications    | 1         | 3.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 2         | 6.9%    |
| LG Display LCD Monitor LGD038E 1366x768 340x190mm 15.3-inch              | 2         | 6.9%    |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch            | 2         | 6.9%    |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch     | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SEC4249 1366x768 309x174mm 14.0-inch     | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 340x190mm 15.3-inch     | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 340x190mm 15.3-inch     | 1         | 3.45%   |
| LG Display LCD Monitor LGD03B7 1366x768 309x174mm 14.0-inch              | 1         | 3.45%   |
| LG Display LCD Monitor LGD03B3 1366x768 309x174mm 14.0-inch              | 1         | 3.45%   |
| LG Display LCD Monitor LGD0251 1366x768 310x174mm 14.0-inch              | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 340x190mm 15.3-inch          | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch          | 1         | 3.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO1007 1024x600 222x125mm 10.0-inch | 1         | 3.45%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                    | 1         | 3.45%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO253C 1366x768 310x170mm 13.9-inch            | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO2374 1280x800 331x207mm 15.4-inch            | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 1         | 3.45%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch    | 1         | 3.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1366x768 (WXGA) | 17        | 58.62%  |
| 1920x1080 (FHD) | 5         | 17.24%  |
| 1280x800 (WXGA) | 4         | 13.79%  |
| 1600x900 (HD+)  | 2         | 6.9%    |
| 1024x600        | 1         | 3.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 16        | 55.17%  |
| 14     | 7         | 24.14%  |
| 17     | 2         | 6.9%    |
| 13     | 2         | 6.9%    |
| 21     | 1         | 3.45%   |
| 10     | 1         | 3.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 25        | 86.21%  |
| 351-400     | 2         | 6.9%    |
| 401-500     | 1         | 3.45%   |
| 201-300     | 1         | 3.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 24        | 85.71%  |
| 16/10 | 4         | 14.29%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 16        | 55.17%  |
| 81-90          | 9         | 31.03%  |
| 121-130        | 2         | 6.9%    |
| 41-50          | 1         | 3.45%   |
| 201-250        | 1         | 3.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 18        | 64.29%  |
| 121-160 | 6         | 21.43%  |
| 51-100  | 4         | 14.29%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 28        | 90.32%  |
| 0     | 2         | 6.45%   |
| 2     | 1         | 3.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 18        | 33.33%  |
| Qualcomm Atheros                  | 12        | 22.22%  |
| Intel                             | 9         | 16.67%  |
| Broadcom                          | 6         | 11.11%  |
| Broadcom Limited                  | 3         | 5.56%   |
| Silicon Integrated Systems [SiS]  | 1         | 1.85%   |
| Ralink                            | 1         | 1.85%   |
| NetGear                           | 1         | 1.85%   |
| Marvell Technology Group          | 1         | 1.85%   |
| Ericsson Business Mobile Networks | 1         | 1.85%   |
| ASIX Electronics                  | 1         | 1.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 10        | 15.15%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 7         | 10.61%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 6.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 4.55%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 2         | 3.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 3.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 3.03%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 3.03%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 3.03%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 1.52%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 1.52%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.52%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 1.52%   |
| Realtek 802.11ac NIC                                                    | 1         | 1.52%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 1         | 1.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 1         | 1.52%   |
| NetGear WG111v2 54 Mbps Wireless [RealTek RTL8187L]                     | 1         | 1.52%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 1         | 1.52%   |
| Intel Wireless 8260                                                     | 1         | 1.52%   |
| Intel Wireless 7265                                                     | 1         | 1.52%   |
| Intel Wireless 7260                                                     | 1         | 1.52%   |
| Intel Wireless 3165                                                     | 1         | 1.52%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 1.52%   |
| Intel Ethernet Connection (3) I218-LM                                   | 1         | 1.52%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 1.52%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 1.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.52%   |
| Intel 82579V Gigabit Network Connection                                 | 1         | 1.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 1         | 1.52%   |
| Ericsson Business Mobile Networks N5321 gw                              | 1         | 1.52%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 1         | 1.52%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                  | 1         | 1.52%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 1         | 1.52%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                  | 1         | 1.52%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 1         | 1.52%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 1.52%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 1.52%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 1         | 1.52%   |
| ASIX AX88179 Gigabit Ethernet                                           | 1         | 1.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 12        | 37.5%   |
| Intel                 | 8         | 25%     |
| Realtek Semiconductor | 4         | 12.5%   |
| Broadcom              | 4         | 12.5%   |
| Broadcom Limited      | 2         | 6.25%   |
| Ralink                | 1         | 3.13%   |
| NetGear               | 1         | 3.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 12.5%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 9.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 6.25%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 6.25%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 6.25%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 6.25%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 3.13%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 3.13%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 3.13%   |
| Realtek 802.11ac NIC                                                    | 1         | 3.13%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 3.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 3.13%   |
| NetGear WG111v2 54 Mbps Wireless [RealTek RTL8187L]                     | 1         | 3.13%   |
| Intel Wireless 8260                                                     | 1         | 3.13%   |
| Intel Wireless 7265                                                     | 1         | 3.13%   |
| Intel Wireless 7260                                                     | 1         | 3.13%   |
| Intel Wireless 3165                                                     | 1         | 3.13%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 3.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 3.13%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 1         | 3.13%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 3.13%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 3.13%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 1         | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 17        | 51.52%  |
| Intel                            | 5         | 15.15%  |
| Qualcomm Atheros                 | 4         | 12.12%  |
| Broadcom                         | 3         | 9.09%   |
| Silicon Integrated Systems [SiS] | 1         | 3.03%   |
| Marvell Technology Group         | 1         | 3.03%   |
| Broadcom Limited                 | 1         | 3.03%   |
| ASIX Electronics                 | 1         | 3.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 30.3%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 21.21%  |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 6.06%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 3.03%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 3.03%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 3.03%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 3.03%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 3.03%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 3.03%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 3.03%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 3.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 3.03%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 3.03%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 3.03%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 3.03%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 1         | 3.03%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 3.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 31        | 50%     |
| WiFi     | 30        | 48.39%  |
| Modem    | 1         | 1.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 23        | 54.76%  |
| Ethernet | 19        | 45.24%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 30        | 96.77%  |
| 1     | 1         | 3.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 29        | 93.55%  |
| Yes  | 2         | 6.45%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 6         | 31.58%  |
| Qualcomm Atheros Communications | 4         | 21.05%  |
| Lite-On Technology              | 2         | 10.53%  |
| Hewlett-Packard                 | 2         | 10.53%  |
| Cambridge Silicon Radio         | 2         | 10.53%  |
| Realtek Semiconductor           | 1         | 5.26%   |
| Ralink Technology               | 1         | 5.26%   |
| Foxconn / Hon Hai               | 1         | 5.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                      | 4         | 21.05%  |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 10.53%  |
| Intel Bluetooth wireless interface                          | 2         | 10.53%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 10.53%  |
| Realtek 802.11n WLAN Adapter                                | 1         | 5.26%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                | 1         | 5.26%   |
| Qualcomm Atheros Bluetooth USB Host Controller              | 1         | 5.26%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 5.26%   |
| Lite-On Bluetooth Device                                    | 1         | 5.26%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 5.26%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 5.26%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 5.26%   |
| Foxconn / Hon Hai BCM20702A0                                | 1         | 5.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 24        | 70.59%  |
| AMD                              | 6         | 17.65%  |
| Silicon Integrated Systems [SiS] | 2         | 5.88%   |
| Nvidia                           | 2         | 5.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 17.07%  |
| AMD FCH Azalia Controller                                                  | 4         | 9.76%   |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 7.32%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 7.32%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 4.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 4.88%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 4.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 4.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 2.44%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 2.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 2.44%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 2.44%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 2.44%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.44%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 2.44%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 2.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 2.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 2.44%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.44%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 2.44%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 2.44%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 2.44%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1         | 2.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 2         | 40%     |
| Unknown             | 1         | 20%     |
| Samsung Electronics | 1         | 20%     |
| Kingston            | 1         | 20%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM SDRAM                     | 1         | 20%     |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 1         | 20%     |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s  | 1         | 20%     |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s    | 1         | 20%     |
| Kingston RAM 9905428-026.A00LF 2GB SODIMM DDR3 1066MT/s | 1         | 20%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 2         | 50%     |
| SDRAM  | 1         | 25%     |
| LPDDR4 | 1         | 25%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 4         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 2         | 40%     |
| 2048 | 2         | 40%     |
| 8192 | 1         | 20%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 1         | 25%     |
| 1600    | 1         | 25%     |
| 1066    | 1         | 25%     |
| Unknown | 1         | 25%     |

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
| Suyin                                  | 5         | 20.83%  |
| Chicony Electronics                    | 5         | 20.83%  |
| Realtek Semiconductor                  | 4         | 16.67%  |
| IMC Networks                           | 3         | 12.5%   |
| Microdia                               | 2         | 8.33%   |
| Syntek                                 | 1         | 4.17%   |
| Silicon Motion                         | 1         | 4.17%   |
| Quanta                                 | 1         | 4.17%   |
| Lite-On Technology                     | 1         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Syntek Lenovo EasyCamera                                    | 1         | 4.17%   |
| Suyin HP Webcam-50                                          | 1         | 4.17%   |
| Suyin HP Webcam-101                                         | 1         | 4.17%   |
| Suyin HP Integrated Webcam                                  | 1         | 4.17%   |
| Suyin Acer/Lenovo Webcam [CN0316]                           | 1         | 4.17%   |
| Suyin Acer CrystalEye Webcam                                | 1         | 4.17%   |
| Silicon Motion WebCam SCB-1100N                             | 1         | 4.17%   |
| Realtek Lenovo EasyCamera                                   | 1         | 4.17%   |
| Realtek Laptop_Integrated_Webcam_HD                         | 1         | 4.17%   |
| Realtek Integrated_Webcam_HD                                | 1         | 4.17%   |
| Realtek Acer 640 x 480 laptop camera                        | 1         | 4.17%   |
| Quanta HD Webcam                                            | 1         | 4.17%   |
| Microdia USB 2.0 Camera                                     | 1         | 4.17%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 4.17%   |
| Lite-On Integrated Camera                                   | 1         | 4.17%   |
| IMC Networks USB2.0 UVC VGA WebCam                          | 1         | 4.17%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 4.17%   |
| IMC Networks Integrated Webcam                              | 1         | 4.17%   |
| Chicony USB2.0 HD UVC WebCam                                | 1         | 4.17%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 4.17%   |
| Chicony Integrated Camera                                   | 1         | 4.17%   |
| Chicony HP TrueVision HD Camera                             | 1         | 4.17%   |
| Chicony HD WebCam                                           | 1         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed] | 1         | 4.17%   |

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


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS491                      | 1         | 50%     |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 23        | 71.88%  |
| 1     | 9         | 28.13%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Graphics card      | 4         | 44.44%  |
| Net/wireless       | 2         | 22.22%  |
| Fingerprint reader | 2         | 22.22%  |
| Chipcard           | 1         | 11.11%  |

