GNOME OS - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for GNOME OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/GNOME_OS/Desktop/README.md) and [notebooks](/Dist/GNOME_OS/Notebook/README.md).

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

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo   | ThinkPad Edge E531 68851... | Notebook    | [54269ad944](https://linux-hardware.org/?probe=54269ad944) | Feb 18, 2022 |
| Gateway  | NE71B                       | Notebook    | [ac3dc96ccf](https://linux-hardware.org/?probe=ac3dc96ccf) | Feb 02, 2022 |
| HP       | Laptop 14-dk1xxx            | Notebook    | [c604eec754](https://linux-hardware.org/?probe=c604eec754) | Jan 27, 2022 |
| Chuwi    | HeroBook                    | Notebook    | [67990dbe7f](https://linux-hardware.org/?probe=67990dbe7f) | Jan 19, 2022 |
| Apple    | Mac-FFE5EF870D7BA81A iMa... | All in one  | [e53f2b7fd5](https://linux-hardware.org/?probe=e53f2b7fd5) | Nov 03, 2021 |
| Apple    | Mac-FFE5EF870D7BA81A iMa... | All in one  | [922c058537](https://linux-hardware.org/?probe=922c058537) | Nov 03, 2021 |
| Gigabyte | B450M S2H V2                | Desktop     | [cd6b701253](https://linux-hardware.org/?probe=cd6b701253) | Nov 03, 2021 |
| Lenovo   | Yoga Slim 7 14ARE05 82A2    | Notebook    | [594815bb9d](https://linux-hardware.org/?probe=594815bb9d) | Oct 17, 2021 |
| ASUSTek  | X555LD                      | Notebook    | [2560d8b5a0](https://linux-hardware.org/?probe=2560d8b5a0) | Sep 27, 2021 |
| ASUSTek  | PRIME A320M-K               | Desktop     | [11c23a1f37](https://linux-hardware.org/?probe=11c23a1f37) | Sep 26, 2021 |
| ASUSTek  | PRIME A320M-K               | Desktop     | [b33430e135](https://linux-hardware.org/?probe=b33430e135) | Sep 26, 2021 |
| Lenovo   | IdeaPad S340-14API 81NB     | Notebook    | [c248e4551a](https://linux-hardware.org/?probe=c248e4551a) | Sep 25, 2021 |
| HP       | Pavilion Notebook           | Notebook    | [835f183d57](https://linux-hardware.org/?probe=835f183d57) | Sep 17, 2021 |
| ASUSTek  | H61M-A/BR                   | Desktop     | [73b5c289e2](https://linux-hardware.org/?probe=73b5c289e2) | Sep 04, 2021 |
| Lenovo   | IdeaPad S145-15IWL 81S9     | Notebook    | [35c20c8cde](https://linux-hardware.org/?probe=35c20c8cde) | Aug 30, 2021 |
| HP       | Pavilion Gaming Laptop 1... | Notebook    | [5a54384297](https://linux-hardware.org/?probe=5a54384297) | Aug 11, 2021 |
| HP       | 8767 A                      | Desktop     | [926ac56be9](https://linux-hardware.org/?probe=926ac56be9) | Aug 10, 2021 |
| Gigabyte | X570 GAMING X               | Desktop     | [b751f6615d](https://linux-hardware.org/?probe=b751f6615d) | Jul 17, 2021 |
| Gigabyte | B450M S2H V2                | Desktop     | [d8886335b1](https://linux-hardware.org/?probe=d8886335b1) | Jul 10, 2021 |
| Intel    | X79                         | Desktop     | [9f19896285](https://linux-hardware.org/?probe=9f19896285) | May 13, 2021 |
| Lenovo   | IdeaPad Flex 5 14IIL05 8... | Convertible | [35876a09ad](https://linux-hardware.org/?probe=35876a09ad) | May 09, 2021 |
| HP       | ProBook 430 G3              | Notebook    | [c3acaeb030](https://linux-hardware.org/?probe=c3acaeb030) | Apr 26, 2021 |
| HP       | ProBook 430 G3              | Notebook    | [de3298645e](https://linux-hardware.org/?probe=de3298645e) | Apr 26, 2021 |
| Toshiba  | Satellite C55-A-1F5         | Notebook    | [d7b4bf2642](https://linux-hardware.org/?probe=d7b4bf2642) | Apr 15, 2021 |
| Toshiba  | Satellite C55-A-1F5         | Notebook    | [aa32e3693a](https://linux-hardware.org/?probe=aa32e3693a) | Apr 14, 2021 |
| Lenovo   | 317E NOK                    | Desktop     | [2ce2a68735](https://linux-hardware.org/?probe=2ce2a68735) | Apr 14, 2021 |
| HP       | Pavilion 17                 | Notebook    | [220bf859f8](https://linux-hardware.org/?probe=220bf859f8) | Mar 28, 2021 |
| HP       | Pavilion 17                 | Notebook    | [a5a6941b23](https://linux-hardware.org/?probe=a5a6941b23) | Mar 28, 2021 |
| Dell     | Latitude 7490               | Notebook    | [ce86510d2b](https://linux-hardware.org/?probe=ce86510d2b) | Mar 28, 2021 |
| Dell     | Inspiron 3542               | Notebook    | [517406f8b6](https://linux-hardware.org/?probe=517406f8b6) | Mar 21, 2021 |
| ASUSTek  | PRIME H410M-K               | Desktop     | [f685fefbec](https://linux-hardware.org/?probe=f685fefbec) | Mar 04, 2021 |
| Unknown  | Unknown                     | Notebook    | [1c5ed732c5](https://linux-hardware.org/?probe=1c5ed732c5) | Mar 01, 2021 |
| Dell     | Precision M6800             | Notebook    | [95fa029c09](https://linux-hardware.org/?probe=95fa029c09) | Jan 14, 2021 |
| Dell     | Inspiron 5566               | Notebook    | [a3fd17119a](https://linux-hardware.org/?probe=a3fd17119a) | Nov 03, 2020 |
| Chuwi    | LarkBox                     | Desktop     | [c7f6fd9a66](https://linux-hardware.org/?probe=c7f6fd9a66) | Oct 21, 2020 |
| HP       | Pavilion 17                 | Notebook    | [edc8ed595b](https://linux-hardware.org/?probe=edc8ed595b) | Oct 12, 2020 |
| Acer     | Aspire GX-781               | Desktop     | [159afb32c1](https://linux-hardware.org/?probe=159afb32c1) | Oct 10, 2020 |
| ASUSTek  | SABERTOOTH X79              | Desktop     | [17acfc90d4](https://linux-hardware.org/?probe=17acfc90d4) | Oct 07, 2020 |
| ASUSTek  | E202SA                      | Notebook    | [a226259559](https://linux-hardware.org/?probe=a226259559) | Sep 24, 2020 |
| Acer     | ChiefRiver Platform         | Notebook    | [23e2162b8e](https://linux-hardware.org/?probe=23e2162b8e) | Sep 20, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.7.14  | 8         | 23.53%  |
| 5.11.10 | 8         | 23.53%  |
| 5.14.18 | 4         | 11.76%  |
| 5.13.9  | 4         | 11.76%  |
| 5.11.2  | 3         | 8.82%   |
| 5.14.4  | 2         | 5.88%   |
| 5.13.8  | 2         | 5.88%   |
| 5.14.11 | 1         | 2.94%   |
| 5.12.12 | 1         | 2.94%   |
| 5.11.0  | 1         | 2.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.7.14  | 8         | 23.53%  |
| 5.11.10 | 8         | 23.53%  |
| 5.14.18 | 4         | 11.76%  |
| 5.13.9  | 4         | 11.76%  |
| 5.11.2  | 3         | 8.82%   |
| 5.14.4  | 2         | 5.88%   |
| 5.13.8  | 2         | 5.88%   |
| 5.14.11 | 1         | 2.94%   |
| 5.12.12 | 1         | 2.94%   |
| 5.11.0  | 1         | 2.94%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 12        | 35.29%  |
| 5.7     | 8         | 23.53%  |
| 5.14    | 7         | 20.59%  |
| 5.13    | 6         | 17.65%  |
| 5.12    | 1         | 2.94%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 33        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GNOME   | 32        | 96.97%  |
| Unknown | 1         | 3.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 32        | 96.97%  |
| Unknown | 1         | 3.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 33        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 15        | 45.45%  |
| ru_RU | 3         | 9.09%   |
| fr_FR | 3         | 9.09%   |
| pt_BR | 2         | 6.06%   |
| hu_HU | 2         | 6.06%   |
| de_DE | 2         | 6.06%   |
| sk_SK | 1         | 3.03%   |
| ru_UA | 1         | 3.03%   |
| es_ES | 1         | 3.03%   |
| es_CL | 1         | 3.03%   |
| en_IN | 1         | 3.03%   |
| cs_CZ | 1         | 3.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 33        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ext4 | 33        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 32        | 96.97%  |
| GPT     | 1         | 3.03%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 7         | 21.21%  |
| Lenovo              | 6         | 18.18%  |
| ASUSTek Computer    | 6         | 18.18%  |
| Dell                | 4         | 12.12%  |
| Gigabyte Technology | 2         | 6.06%   |
| Chuwi               | 2         | 6.06%   |
| Acer                | 2         | 6.06%   |
| Toshiba             | 1         | 3.03%   |
| Intel               | 1         | 3.03%   |
| Gateway             | 1         | 3.03%   |
| Apple               | 1         | 3.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| HP Pavilion 17                         | 2         | 6.06%   |
| Toshiba Satellite C55-A-1F5            | 1         | 3.03%   |
| Lenovo Yoga Slim 7 14ARE05 82A2        | 1         | 3.03%   |
| Lenovo ThinkPad Edge E531 68851P6      | 1         | 3.03%   |
| Lenovo IdeaPad S340-14API 81NB         | 1         | 3.03%   |
| Lenovo IdeaPad S145-15IWL 81S9         | 1         | 3.03%   |
| Lenovo IdeaPad Flex 5 14IIL05 81X1     | 1         | 3.03%   |
| Lenovo IdeaCentre 3 07IMB05 90NB0020IN | 1         | 3.03%   |
| Intel X79                              | 1         | 3.03%   |
| HP ProBook 430 G3                      | 1         | 3.03%   |
| HP Pavilion Notebook                   | 1         | 3.03%   |
| HP Pavilion Gaming Laptop 15-ec0xxx    | 1         | 3.03%   |
| HP Pavilion Gaming Desktop TG01-1xxx   | 1         | 3.03%   |
| HP Laptop 14-dk1xxx                    | 1         | 3.03%   |
| Gigabyte X570 GAMING X                 | 1         | 3.03%   |
| Gigabyte B450M S2H V2                  | 1         | 3.03%   |
| Gateway NE71B                          | 1         | 3.03%   |
| Dell Precision M6800                   | 1         | 3.03%   |
| Dell Latitude 7490                     | 1         | 3.03%   |
| Dell Inspiron 5566                     | 1         | 3.03%   |
| Dell Inspiron 3542                     | 1         | 3.03%   |
| Chuwi LarkBox                          | 1         | 3.03%   |
| Chuwi HeroBook                         | 1         | 3.03%   |
| ASUS X555LD                            | 1         | 3.03%   |
| ASUS SABERTOOTH X79                    | 1         | 3.03%   |
| ASUS PRIME H410M-K                     | 1         | 3.03%   |
| ASUS PRIME A320M-K                     | 1         | 3.03%   |
| ASUS H61M-A/BR                         | 1         | 3.03%   |
| ASUS E202SA                            | 1         | 3.03%   |
| Apple iMac16,2                         | 1         | 3.03%   |
| Acer ChiefRiver Platform               | 1         | 3.03%   |
| Acer Aspire GX-781                     | 1         | 3.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| HP Pavilion       | 5         | 15.15%  |
| Lenovo IdeaPad    | 3         | 9.09%   |
| Dell Inspiron     | 2         | 6.06%   |
| ASUS PRIME        | 2         | 6.06%   |
| Toshiba Satellite | 1         | 3.03%   |
| Lenovo Yoga       | 1         | 3.03%   |
| Lenovo ThinkPad   | 1         | 3.03%   |
| Lenovo IdeaCentre | 1         | 3.03%   |
| Intel X79         | 1         | 3.03%   |
| HP ProBook        | 1         | 3.03%   |
| HP Laptop         | 1         | 3.03%   |
| Gigabyte X570     | 1         | 3.03%   |
| Gigabyte B450M    | 1         | 3.03%   |
| Gateway NE71B     | 1         | 3.03%   |
| Dell Precision    | 1         | 3.03%   |
| Dell Latitude     | 1         | 3.03%   |
| Chuwi LarkBox     | 1         | 3.03%   |
| Chuwi HeroBook    | 1         | 3.03%   |
| ASUS X555LD       | 1         | 3.03%   |
| ASUS SABERTOOTH   | 1         | 3.03%   |
| ASUS H61M-A       | 1         | 3.03%   |
| ASUS E202SA       | 1         | 3.03%   |
| Apple iMac16      | 1         | 3.03%   |
| Acer ChiefRiver   | 1         | 3.03%   |
| Acer Aspire       | 1         | 3.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 7         | 21.21%  |
| 2019 | 7         | 21.21%  |
| 2013 | 6         | 18.18%  |
| 2017 | 3         | 9.09%   |
| 2014 | 3         | 9.09%   |
| 2016 | 2         | 6.06%   |
| 2015 | 2         | 6.06%   |
| 2012 | 2         | 6.06%   |
| 2018 | 1         | 3.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 20        | 60.61%  |
| Desktop     | 11        | 33.33%  |
| Convertible | 1         | 3.03%   |
| All in one  | 1         | 3.03%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 33        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 33        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 16        | 48.48%  |
| 8.01-16.0  | 7         | 21.21%  |
| 3.01-4.0   | 5         | 15.15%  |
| 32.01-64.0 | 2         | 6.06%   |
| 16.01-24.0 | 2         | 6.06%   |
| 1.01-2.0   | 1         | 3.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 26        | 76.47%  |
| 2.01-3.0 | 3         | 8.82%   |
| 4.01-8.0 | 2         | 5.88%   |
| 0.51-1.0 | 2         | 5.88%   |
| 3.01-4.0 | 1         | 2.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 25        | 75.76%  |
| 2      | 5         | 15.15%  |
| 3      | 2         | 6.06%   |
| 4      | 1         | 3.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 24        | 72.73%  |
| Yes       | 9         | 27.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 84.85%  |
| No        | 5         | 15.15%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 87.88%  |
| No        | 4         | 12.12%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 69.7%   |
| No        | 10        | 30.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 7         | 21.21%  |
| Ukraine     | 3         | 9.09%   |
| France      | 3         | 9.09%   |
| Brazil      | 3         | 9.09%   |
| Russia      | 2         | 6.06%   |
| Germany     | 2         | 6.06%   |
| Chile       | 2         | 6.06%   |
| Canada      | 2         | 6.06%   |
| UAE         | 1         | 3.03%   |
| Slovakia    | 1         | 3.03%   |
| Serbia      | 1         | 3.03%   |
| India       | 1         | 3.03%   |
| Hungary     | 1         | 3.03%   |
| Greece      | 1         | 3.03%   |
| Finland     | 1         | 3.03%   |
| El Salvador | 1         | 3.03%   |
| Czechia     | 1         | 3.03%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Vancouver           | 2         | 6.06%   |
| Verden an der Aller | 1         | 3.03%   |
| Uruguaiana          | 1         | 3.03%   |
| Tyumen              | 1         | 3.03%   |
| Talence             | 1         | 3.03%   |
| Sobral              | 1         | 3.03%   |
| Skydra              | 1         | 3.03%   |
| Santiago            | 1         | 3.03%   |
| Rio de Janeiro      | 1         | 3.03%   |
| Prague              | 1         | 3.03%   |
| Pori                | 1         | 3.03%   |
| Ottawa              | 1         | 3.03%   |
| Novoyavorovske      | 1         | 3.03%   |
| Novi Sad            | 1         | 3.03%   |
| Millers Creek       | 1         | 3.03%   |
| Mariupol            | 1         | 3.03%   |
| Levis               | 1         | 3.03%   |
| Lehighton           | 1         | 3.03%   |
| Kyiv                | 1         | 3.03%   |
| Krasnoyarsk         | 1         | 3.03%   |
| Kolkata             | 1         | 3.03%   |
| Kalispell           | 1         | 3.03%   |
| Grandview           | 1         | 3.03%   |
| Glatten             | 1         | 3.03%   |
| Columbia            | 1         | 3.03%   |
| Castelnau-le-Lez    | 1         | 3.03%   |
| Budapest            | 1         | 3.03%   |
| Bratislava          | 1         | 3.03%   |
| Arica               | 1         | 3.03%   |
| Antiguo Cuscatlan   | 1         | 3.03%   |
| Abu Dhabi           | 1         | 3.03%   |
| Abbeville           | 1         | 3.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 20.93%  |
| WDC                 | 7         | 7      | 16.28%  |
| Kingston            | 6         | 6      | 13.95%  |
| Samsung Electronics | 4         | 6      | 9.3%    |
| SK Hynix            | 3         | 3      | 6.98%   |
| Toshiba             | 2         | 2      | 4.65%   |
| Sandisk             | 2         | 3      | 4.65%   |
| HGST                | 2         | 2      | 4.65%   |
| Transcend           | 1         | 1      | 2.33%   |
| SSSTC               | 1         | 1      | 2.33%   |
| PNY                 | 1         | 1      | 2.33%   |
| Intel               | 1         | 1      | 2.33%   |
| HECTRON             | 1         | 1      | 2.33%   |
| Crucial             | 1         | 1      | 2.33%   |
| Apple               | 1         | 1      | 2.33%   |
| Apacer              | 1         | 1      | 2.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Seagate ST9500325AS 500GB                 | 2         | 4.55%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB    | 2         | 4.55%   |
| Kingston SA400S37120G 120GB SSD           | 2         | 4.55%   |
| WDC WDS240G2G0A-00JH30 240GB SSD          | 1         | 2.27%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 2.27%   |
| WDC WD5000LPVX-08V0TT5 500GB              | 1         | 2.27%   |
| WDC WD3200LPVX-08V0TT5 320GB              | 1         | 2.27%   |
| WDC WD1600AAJS-22L7A0 160GB               | 1         | 2.27%   |
| WDC WD10SPZX-24Z10 1TB                    | 1         | 2.27%   |
| WDC WD10EALX-009BA0 1TB                   | 1         | 2.27%   |
| Transcend TS64GMTS400 64GB SSD            | 1         | 2.27%   |
| Toshiba MQ01ABD032 320GB                  | 1         | 2.27%   |
| Toshiba HDWD120 2TB                       | 1         | 2.27%   |
| SSSTC CVB-8D128-HP 128GB                  | 1         | 2.27%   |
| SK Hynix SKHynix_HFS512GD9TNG-L3A0B 512GB | 1         | 2.27%   |
| SK Hynix NVMe SSD Drive 512GB             | 1         | 2.27%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD     | 1         | 2.27%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 1         | 2.27%   |
| Seagate ST4000DX001-1CE168 4TB            | 1         | 2.27%   |
| Seagate ST3500312CS 500GB                 | 1         | 2.27%   |
| Seagate ST2000DM001-1ER164 2TB            | 1         | 2.27%   |
| Seagate ST1000LM035-1RK172 1TB            | 1         | 2.27%   |
| Seagate ST1000DM010-2EP102 1TB            | 1         | 2.27%   |
| Seagate ST1000DM003-1SB102 1TB            | 1         | 2.27%   |
| SanDisk SD8SN8U512G1002 512GB SSD         | 1         | 2.27%   |
| Sandisk NVMe SSD Drive 500GB              | 1         | 2.27%   |
| Samsung SSD 860 QVO 1TB                   | 1         | 2.27%   |
| Samsung SSD 840 EVO 250GB                 | 1         | 2.27%   |
| Samsung NVMe SSD Drive 1024GB             | 1         | 2.27%   |
| PNY CS900 240GB SSD                       | 1         | 2.27%   |
| Kingston SV300S37A240G 240GB SSD          | 1         | 2.27%   |
| Kingston SHFS37A120G 120GB SSD            | 1         | 2.27%   |
| Kingston SA400M8240G 240GB SSD            | 1         | 2.27%   |
| Kingston RBUSNS4180S3256GJ 256GB SSD      | 1         | 2.27%   |
| Intel SSDSCKKF256G8 SATA 256GB            | 1         | 2.27%   |
| HGST HTS541010A9E680 1TB                  | 1         | 2.27%   |
| HGST HTS541010A7E630 1TB                  | 1         | 2.27%   |
| HECTRON HECX1-60G                         | 1         | 2.27%   |
| Crucial CT240BX500SSD1 240GB              | 1         | 2.27%   |
| Apple HDD HTS541010A9E662 1TB             | 1         | 2.27%   |
| Apacer AS350 120GB SSD                    | 1         | 2.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 9      | 45%     |
| WDC     | 6         | 6      | 30%     |
| Toshiba | 2         | 2      | 10%     |
| HGST    | 2         | 2      | 10%     |
| Apple   | 1         | 1      | 5%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 6      | 35.29%  |
| Samsung Electronics | 2         | 3      | 11.76%  |
| WDC                 | 1         | 1      | 5.88%   |
| Transcend           | 1         | 1      | 5.88%   |
| SSSTC               | 1         | 1      | 5.88%   |
| SK Hynix            | 1         | 1      | 5.88%   |
| SanDisk             | 1         | 1      | 5.88%   |
| PNY                 | 1         | 1      | 5.88%   |
| Intel               | 1         | 1      | 5.88%   |
| Crucial             | 1         | 1      | 5.88%   |
| Apacer              | 1         | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 19        | 20     | 46.34%  |
| SSD     | 15        | 18     | 36.59%  |
| NVMe    | 6         | 7      | 14.63%  |
| Unknown | 1         | 1      | 2.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 29        | 39     | 82.86%  |
| NVMe | 6         | 7      | 17.14%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 19        | 24     | 59.38%  |
| 0.51-1.0   | 10        | 11     | 31.25%  |
| 1.01-2.0   | 2         | 2      | 6.25%   |
| 3.01-4.0   | 1         | 1      | 3.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 13        | 39.39%  |
| 251-500    | 10        | 30.3%   |
| 501-1000   | 7         | 21.21%  |
| 51-100     | 2         | 6.06%   |
| 1001-2000  | 1         | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 24        | 70.59%  |
| 21-50   | 6         | 17.65%  |
| 101-250 | 2         | 5.88%   |
| 251-500 | 1         | 2.94%   |
| 51-100  | 1         | 2.94%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 32        | 45     | 96.97%  |
| Works    | 1         | 1      | 3.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 21        | 55.26%  |
| AMD                      | 9         | 23.68%  |
| Samsung Electronics      | 3         | 7.89%   |
| SK Hynix                 | 2         | 5.26%   |
| Sandisk                  | 1         | 2.63%   |
| Marvell Technology Group | 1         | 2.63%   |
| ASMedia Technology       | 1         | 2.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 9         | 21.43%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3         | 7.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3         | 7.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 4.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 4.76%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 4.76%   |
| SK Hynix Non-Volatile memory controller                                                 | 1         | 2.38%   |
| SK Hynix BC511                                                                          | 1         | 2.38%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 2.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1         | 2.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 2.38%   |
| Samsung NVMe SSD Controller 980                                                         | 1         | 2.38%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1         | 2.38%   |
| Intel SATA Controller [RAID mode]                                                       | 1         | 2.38%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1         | 2.38%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 2.38%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 2.38%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1         | 2.38%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1         | 2.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1         | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 2.38%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1         | 2.38%   |
| AMD FCH SATA Controller D                                                               | 1         | 2.38%   |
| AMD FCH IDE Controller                                                                  | 1         | 2.38%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1         | 2.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 28        | 75.68%  |
| NVMe | 6         | 16.22%  |
| IDE  | 2         | 5.41%   |
| RAID | 1         | 2.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 22        | 66.67%  |
| AMD    | 11        | 33.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 6.06%   |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz            | 1         | 3.03%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 3.03%   |
| Intel Core i7-4930K CPU @ 3.40GHz             | 1         | 3.03%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 3.03%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 1         | 3.03%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 3.03%   |
| Intel Core i5-5675R CPU @ 3.10GHz             | 1         | 3.03%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 3.03%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 3.03%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 1         | 3.03%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 3.03%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 3.03%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 3.03%   |
| Intel Core i3-10100F CPU @ 3.60GHz            | 1         | 3.03%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 1         | 3.03%   |
| Intel Celeron J4115 CPU @ 1.80GHz             | 1         | 3.03%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 3.03%   |
| Intel Celeron CPU G530 @ 2.40GHz              | 1         | 3.03%   |
| Intel Celeron 2957U @ 1.40GHz                 | 1         | 3.03%   |
| Intel Atom x5-E8000 CPU @ 1.04GHz             | 1         | 3.03%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 3.03%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 1         | 3.03%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 1         | 3.03%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 3.03%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 3.03%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 1         | 3.03%   |
| AMD E1-1200 APU with Radeon HD Graphics       | 1         | 3.03%   |
| AMD Athlon Silver 3050U with Radeon Graphics  | 1         | 3.03%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 1         | 3.03%   |
| AMD A8-5550M APU with Radeon HD Graphics      | 1         | 3.03%   |
| AMD A10-5745M APU with Radeon HD Graphics     | 1         | 3.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Computers | Percent |
|---------------|-----------|---------|
| Intel Core i5 | 8         | 24.24%  |
| Intel Core i3 | 6         | 18.18%  |
| AMD Ryzen 5   | 5         | 15.15%  |
| Intel Celeron | 4         | 12.12%  |
| Intel Core i7 | 2         | 6.06%   |
| AMD A8        | 2         | 6.06%   |
| Intel Xeon    | 1         | 3.03%   |
| Intel Atom    | 1         | 3.03%   |
| AMD Ryzen 7   | 1         | 3.03%   |
| AMD E1        | 1         | 3.03%   |
| AMD Athlon    | 1         | 3.03%   |
| AMD A10       | 1         | 3.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 14        | 42.42%  |
| 4      | 13        | 39.39%  |
| 6      | 4         | 12.12%  |
| 8      | 2         | 6.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 33        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 22        | 66.67%  |
| 1      | 11        | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 33        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x08108109 | 4         | 12.12%  |
| 0xa0653    | 3         | 9.09%   |
| 0x306a9    | 3         | 9.09%   |
| 0x406e3    | 2         | 6.06%   |
| 0x40651    | 2         | 6.06%   |
| 0x06001119 | 2         | 6.06%   |
| 0x906e9    | 1         | 3.03%   |
| 0x806ec    | 1         | 3.03%   |
| 0x806ea    | 1         | 3.03%   |
| 0x706e5    | 1         | 3.03%   |
| 0x706a1    | 1         | 3.03%   |
| 0x406c4    | 1         | 3.03%   |
| 0x406c3    | 1         | 3.03%   |
| 0x40671    | 1         | 3.03%   |
| 0x306e4    | 1         | 3.03%   |
| 0x306c3    | 1         | 3.03%   |
| 0x206d7    | 1         | 3.03%   |
| 0x206a7    | 1         | 3.03%   |
| 0x0a201009 | 1         | 3.03%   |
| 0x08701021 | 1         | 3.03%   |
| 0x08600106 | 1         | 3.03%   |
| 0x07030105 | 1         | 3.03%   |
| 0x0500010d | 1         | 3.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Zen+          | 4         | 12.12%  |
| IvyBridge     | 4         | 12.12%  |
| KabyLake      | 3         | 9.09%   |
| Haswell       | 3         | 9.09%   |
| CometLake     | 3         | 9.09%   |
| Zen 2         | 2         | 6.06%   |
| Skylake       | 2         | 6.06%   |
| Silvermont    | 2         | 6.06%   |
| SandyBridge   | 2         | 6.06%   |
| Piledriver    | 2         | 6.06%   |
| Zen 3         | 1         | 3.03%   |
| Puma          | 1         | 3.03%   |
| IceLake       | 1         | 3.03%   |
| Goldmont plus | 1         | 3.03%   |
| Broadwell     | 1         | 3.03%   |
| Bobcat        | 1         | 3.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 17        | 44.74%  |
| AMD    | 11        | 28.95%  |
| Nvidia | 10        | 26.32%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 10%     |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3         | 7.5%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 7.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 5%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 5%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 5%      |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 5%      |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 2.5%    |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 1         | 2.5%    |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 2.5%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 2.5%    |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 2.5%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 2.5%    |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 2.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 2.5%    |
| Intel UHD Graphics 620                                                                   | 1         | 2.5%    |
| Intel Iris Pro Graphics 6200                                                             | 1         | 2.5%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 2.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 2.5%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 2.5%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 2.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 2.5%    |
| AMD Wrestler [Radeon HD 7310]                                                            | 1         | 2.5%    |
| AMD Saturn XT [FirePro M6100]                                                            | 1         | 2.5%    |
| AMD Richland [Radeon HD 8610G]                                                           | 1         | 2.5%    |
| AMD Richland [Radeon HD 8550G]                                                           | 1         | 2.5%    |
| AMD Renoir                                                                               | 1         | 2.5%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 2.5%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1         | 2.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 13        | 39.39%  |
| 1 x AMD        | 7         | 21.21%  |
| 1 x Nvidia     | 6         | 18.18%  |
| Intel + Nvidia | 3         | 9.09%   |
| 2 x AMD        | 2         | 6.06%   |
| Intel + AMD    | 1         | 3.03%   |
| AMD + Nvidia   | 1         | 3.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver | Computers | Percent |
|--------|-----------|---------|
| Free   | 33        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 39.39%  |
| 1.01-2.0   | 5         | 15.15%  |
| 0.51-1.0   | 5         | 15.15%  |
| 2.01-3.0   | 4         | 12.12%  |
| 0.01-0.5   | 3         | 9.09%   |
| 7.01-8.0   | 1         | 3.03%   |
| 5.01-6.0   | 1         | 3.03%   |
| 3.01-4.0   | 1         | 3.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 20%     |
| AU Optronics        | 6         | 17.14%  |
| LG Display          | 5         | 14.29%  |
| Chimei Innolux      | 4         | 11.43%  |
| BOE                 | 3         | 8.57%   |
| Goldstar            | 2         | 5.71%   |
| Viotek              | 1         | 2.86%   |
| Philips             | 1         | 2.86%   |
| InfoVision          | 1         | 2.86%   |
| Dell                | 1         | 2.86%   |
| BenQ                | 1         | 2.86%   |
| Apple               | 1         | 2.86%   |
| AOC                 | 1         | 2.86%   |
| Acer                | 1         | 2.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Viotek GN34CW VTK3400 3440x1440 795x334mm 33.9-inch                  | 1         | 2.78%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch  | 1         | 2.78%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 1         | 2.78%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 382x215mm 17.3-inch | 1         | 2.78%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 700x390mm 31.5-inch    | 1         | 2.78%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 1         | 2.78%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 1         | 2.78%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch              | 1         | 2.78%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch         | 1         | 2.78%   |
| LG Display LCD Monitor LGD04B3 1920x1080 350x190mm 15.7-inch         | 1         | 2.78%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch          | 1         | 2.78%   |
| LG Display LCD Monitor LGD0372 1600x900 382x215mm 17.3-inch          | 1         | 2.78%   |
| LG Display LCD Monitor LGD02DA 1920x1080 380x220mm 17.3-inch         | 1         | 2.78%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 1         | 2.78%   |
| Goldstar W1752 GSM4490 1440x900 370x232mm 17.2-inch                  | 1         | 2.78%   |
| Goldstar 24GL600F GSM5B73 1920x1080 530x300mm 24.0-inch              | 1         | 2.78%   |
| Dell P2421D DELD0FF 2560x1440 527x296mm 23.8-inch                    | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15BB 1920x1080 344x194mm 15.5-inch     | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch     | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch      | 1         | 2.78%   |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                 | 1         | 2.78%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 1         | 2.78%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                 | 1         | 2.78%   |
| BenQ LCD BNQ8024 2560x1440 600x340mm 27.2-inch                       | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch       | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO233C 1366x768 309x173mm 13.9-inch        | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO223D 1920x1080 309x174mm 14.0-inch       | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO162C 1366x768 293x164mm 13.2-inch        | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch        | 1         | 2.78%   |
| Apple iMac APPA032 3840x2160 475x267mm 21.5-inch                     | 1         | 2.78%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 1         | 2.78%   |
| Acer FT220HQL ACR03D2 1920x1080 476x268mm 21.5-inch                  | 1         | 2.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 16        | 47.06%  |
| 1366x768 (WXGA)  | 10        | 29.41%  |
| 1600x900 (HD+)   | 3         | 8.82%   |
| 2560x1440 (QHD)  | 2         | 5.88%   |
| 3840x2160 (4K)   | 1         | 2.94%   |
| 3440x1440        | 1         | 2.94%   |
| 1440x900 (WXGA+) | 1         | 2.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 7         | 20%     |
| 17     | 5         | 14.29%  |
| 14     | 5         | 14.29%  |
| 21     | 4         | 11.43%  |
| 13     | 4         | 11.43%  |
| 24     | 3         | 8.57%   |
| 27     | 2         | 5.71%   |
| 34     | 1         | 2.86%   |
| 31     | 1         | 2.86%   |
| 23     | 1         | 2.86%   |
| 18     | 1         | 2.86%   |
| 11     | 1         | 2.86%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 15        | 44.12%  |
| 501-600     | 5         | 14.71%  |
| 401-500     | 5         | 14.71%  |
| 351-400     | 5         | 14.71%  |
| 201-300     | 2         | 5.88%   |
| 701-800     | 1         | 2.94%   |
| 601-700     | 1         | 2.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 32        | 94.12%  |
| 21/9  | 1         | 2.94%   |
| 16/10 | 1         | 2.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 8         | 23.53%  |
| 101-110        | 7         | 20.59%  |
| 201-250        | 6         | 17.65%  |
| 121-130        | 4         | 11.76%  |
| 351-500        | 2         | 5.88%   |
| 301-350        | 2         | 5.88%   |
| 71-80          | 1         | 2.94%   |
| 51-60          | 1         | 2.94%   |
| 151-200        | 1         | 2.94%   |
| 141-150        | 1         | 2.94%   |
| 131-140        | 1         | 2.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 15        | 44.12%  |
| 121-160 | 11        | 32.35%  |
| 51-100  | 7         | 20.59%  |
| 161-240 | 1         | 2.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 30        | 90.91%  |
| 2     | 3         | 9.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 22        | 44%     |
| Intel                           | 12        | 24%     |
| Qualcomm Atheros                | 7         | 14%     |
| Google                          | 2         | 4%      |
| Broadcom Limited                | 2         | 4%      |
| Broadcom                        | 2         | 4%      |
| TP-Link                         | 1         | 2%      |
| Qualcomm Atheros Communications | 1         | 2%      |
| Motorola PCS                    | 1         | 2%      |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 25%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 8.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 5%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 3.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 3.33%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 3.33%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.67%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 1.67%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 1.67%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.67%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.67%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.67%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1         | 1.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 1.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.67%   |
| Motorola PCS moto g stylus                                        | 1         | 1.67%   |
| Intel Wireless-AC 9260                                            | 1         | 1.67%   |
| Intel Wireless 3165                                               | 1         | 1.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 1.67%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1         | 1.67%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 1.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.67%   |
| Intel Centrino Wireless-N 105                                     | 1         | 1.67%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.67%   |
| Google Pixel 6                                                    | 1         | 1.67%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 1.67%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.67%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 1         | 1.67%   |
| Broadcom Limited BCM43142 802.11b/g/n                             | 1         | 1.67%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 1.67%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 9         | 31.03%  |
| Intel                           | 9         | 31.03%  |
| Qualcomm Atheros                | 6         | 20.69%  |
| Broadcom Limited                | 2         | 6.9%    |
| Broadcom                        | 2         | 6.9%    |
| Qualcomm Atheros Communications | 1         | 3.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 3         | 10.34%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 2         | 6.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 2         | 6.9%    |
| Intel Wi-Fi 6 AX200                                        | 2         | 6.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 3.45%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 1         | 3.45%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                 | 1         | 3.45%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 1         | 3.45%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1         | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1         | 3.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 3.45%   |
| Qualcomm Atheros AR9271 802.11n                            | 1         | 3.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 1         | 3.45%   |
| Intel Wireless-AC 9260                                     | 1         | 3.45%   |
| Intel Wireless 3165                                        | 1         | 3.45%   |
| Intel Ice Lake-LP PCH CNVi WiFi                            | 1         | 3.45%   |
| Intel Gemini Lake PCH CNVi WiFi                            | 1         | 3.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1         | 3.45%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1         | 3.45%   |
| Intel Centrino Wireless-N 105                              | 1         | 3.45%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter | 1         | 3.45%   |
| Broadcom Limited BCM43142 802.11b/g/n                      | 1         | 3.45%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                | 1         | 3.45%   |
| Broadcom BCM43142 802.11b/g/n                              | 1         | 3.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 21        | 70%     |
| Intel                 | 3         | 10%     |
| Qualcomm Atheros      | 2         | 6.67%   |
| Google                | 2         | 6.67%   |
| TP-Link               | 1         | 3.33%   |
| Broadcom              | 1         | 3.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 50%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 16.67%  |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 3.33%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 3.33%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 3.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 3.33%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 3.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 3.33%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 3.33%   |
| Google Pixel 6                                                    | 1         | 3.33%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 3.33%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 3.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 29        | 50%     |
| Ethernet | 28        | 48.28%  |
| Unknown  | 1         | 1.72%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 26        | 65%     |
| WiFi     | 14        | 35%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 21        | 63.64%  |
| 1     | 11        | 33.33%  |
| 0     | 1         | 3.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 28        | 84.85%  |
| Yes  | 5         | 15.15%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 7         | 30.43%  |
| Realtek Semiconductor           | 6         | 26.09%  |
| Qualcomm Atheros Communications | 4         | 17.39%  |
| Lite-On Technology              | 2         | 8.7%    |
| Toshiba                         | 1         | 4.35%   |
| Dell                            | 1         | 4.35%   |
| ASUSTek Computer                | 1         | 4.35%   |
| Apple                           | 1         | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                      | 3         | 13.04%  |
| Qualcomm Atheros  Bluetooth Device           | 3         | 13.04%  |
| Realtek  Bluetooth 4.2 Adapter               | 2         | 8.7%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device | 2         | 8.7%    |
| Intel Bluetooth wireless interface           | 2         | 8.7%    |
| Toshiba Bluetooth Device                     | 1         | 4.35%   |
| Realtek RTL8821A Bluetooth                   | 1         | 4.35%   |
| Qualcomm Atheros AR9462 Bluetooth            | 1         | 4.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter     | 1         | 4.35%   |
| Intel Wireless-AC 3168 Bluetooth             | 1         | 4.35%   |
| Intel Bluetooth Device                       | 1         | 4.35%   |
| Intel AX201 Bluetooth                        | 1         | 4.35%   |
| Intel AX200 Bluetooth                        | 1         | 4.35%   |
| Dell Broadcom BCM20702A0 Bluetooth           | 1         | 4.35%   |
| ASUS Broadcom BCM20702A0 Bluetooth           | 1         | 4.35%   |
| Apple Bluetooth USB Host Controller          | 1         | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 22        | 51.16%  |
| AMD                 | 12        | 27.91%  |
| Nvidia              | 8         | 18.6%   |
| C-Media Electronics | 1         | 2.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 8.93%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 7.14%   |
| AMD FCH Azalia Controller                                                                         | 4         | 7.14%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 5.36%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 5.36%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 5.36%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 3.57%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 2         | 3.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 3.57%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 3.57%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 3.57%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 3.57%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.79%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.79%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.79%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.79%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.79%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.79%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.79%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 1.79%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.79%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 1.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.79%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                                               | 1         | 1.79%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.79%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                                | 1         | 1.79%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.79%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.79%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 1.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Micron Technology | 1         | 100%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Micron RAM MT53E1G32D4NQ-046WTE 8GB Row Of Chips LPDDR4 4266MT/s | 1         | 100%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| LPDDR4 | 1         | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Row Of Chips | 1         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Computers | Percent |
|------|-----------|---------|
| 8192 | 1         | 100%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 4266  | 1         | 100%    |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 5         | 21.74%  |
| Suyin                                  | 3         | 13.04%  |
| Realtek Semiconductor                  | 3         | 13.04%  |
| Syntek                                 | 2         | 8.7%    |
| Sunplus Innovation Technology          | 2         | 8.7%    |
| Microdia                               | 2         | 8.7%    |
| Logitech                               | 2         | 8.7%    |
| IMC Networks                           | 1         | 4.35%   |
| HD 2MP WEBCAM                          | 1         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 4.35%   |
| Apple                                  | 1         | 4.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Suyin HP Truevision HD                           | 3         | 13.04%  |
| Syntek Integrated Camera                         | 2         | 8.7%    |
| Realtek USB Camera                               | 2         | 8.7%    |
| Chicony Integrated Camera                        | 2         | 8.7%    |
| Sunplus Integrated_Webcam_HD                     | 1         | 4.35%   |
| Sunplus HD WebCam                                | 1         | 4.35%   |
| Realtek Integrated Camera                        | 1         | 4.35%   |
| Microdia Integrated_Webcam_HD                    | 1         | 4.35%   |
| Microdia Integrated Webcam HD                    | 1         | 4.35%   |
| Logitech Webcam C270                             | 1         | 4.35%   |
| Logitech HD Pro Webcam C920                      | 1         | 4.35%   |
| IMC Networks HP TrueVision HD Camera             | 1         | 4.35%   |
| HD 2MP WEBCAM HD 2MP WEBCAM                      | 1         | 4.35%   |
| Chicony USB2.0 VGA UVC WebCam                    | 1         | 4.35%   |
| Chicony TOSHIBA Web Camera - HD                  | 1         | 4.35%   |
| Chicony HP HD Camera                             | 1         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 1         | 4.35%   |
| Apple FaceTime HD Camera (Built-in)              | 1         | 4.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 1         | 50%     |
| Synaptics        | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader | 1         | 50%     |
| Unknown                                     | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 14        | 42.42%  |
| 2     | 9         | 27.27%  |
| 3     | 4         | 12.12%  |
| 4     | 3         | 9.09%   |
| 0     | 3         | 9.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 19        | 33.93%  |
| Net/wireless             | 15        | 26.79%  |
| Multimedia controller    | 4         | 7.14%   |
| Card reader              | 4         | 7.14%   |
| Bluetooth                | 4         | 7.14%   |
| Graphics card            | 3         | 5.36%   |
| Net/ethernet             | 2         | 3.57%   |
| Fingerprint reader       | 2         | 3.57%   |
| Storage/ide              | 1         | 1.79%   |
| Firewire controller      | 1         | 1.79%   |
| Chipcard                 | 1         | 1.79%   |

