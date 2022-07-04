GNOME OS - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for GNOME OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/GNOME_OS/Desktop/README.md) and [notebooks](/Dist/GNOME_OS/Notebook/README.md).

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

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo   | Yoga Slim 7 14ARE05 82A2    | Notebook    | [a90e6b2be7](https://linux-hardware.org/?probe=a90e6b2be7) | Apr 30, 2022 |
| Apple    | MacBookPro10,1              | Notebook    | [1bbdbe7117](https://linux-hardware.org/?probe=1bbdbe7117) | Apr 04, 2022 |
| Acer     | Iconia W700                 | Notebook    | [604cdabab4](https://linux-hardware.org/?probe=604cdabab4) | Mar 23, 2022 |
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
| Lenovo   | IdeaPadFlex 5 14IIL05 81... | Convertible | [35876a09ad](https://linux-hardware.org/?probe=35876a09ad) | May 09, 2021 |
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
| Chuwi    | LarkBox                     | Mini pc     | [c7f6fd9a66](https://linux-hardware.org/?probe=c7f6fd9a66) | Oct 21, 2020 |
| HP       | Pavilion 17                 | Notebook    | [edc8ed595b](https://linux-hardware.org/?probe=edc8ed595b) | Oct 12, 2020 |
| Acer     | Aspire GX-781               | Desktop     | [159afb32c1](https://linux-hardware.org/?probe=159afb32c1) | Oct 10, 2020 |
| ASUSTek  | SABERTOOTH X79              | Desktop     | [17acfc90d4](https://linux-hardware.org/?probe=17acfc90d4) | Oct 07, 2020 |
| ASUSTek  | E202SA                      | Notebook    | [a226259559](https://linux-hardware.org/?probe=a226259559) | Sep 24, 2020 |
| Acer     | ChiefRiver Platform         | Notebook    | [23e2162b8e](https://linux-hardware.org/?probe=23e2162b8e) | Sep 20, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME OS Nightly | 25        | 71.43%  |
| GNOME OS 3.38    | 7         | 20%     |
| GNOME OS 42      | 1         | 2.86%   |
| GNOME OS 41      | 1         | 2.86%   |
| GNOME OS 40      | 1         | 2.86%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| GNOME OS | 35        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.7.14  | 8         | 21.62%  |
| 5.11.10 | 8         | 21.62%  |
| 5.14.18 | 7         | 18.92%  |
| 5.13.9  | 4         | 10.81%  |
| 5.11.2  | 3         | 8.11%   |
| 5.14.4  | 2         | 5.41%   |
| 5.13.8  | 2         | 5.41%   |
| 5.14.11 | 1         | 2.7%    |
| 5.12.12 | 1         | 2.7%    |
| 5.11.0  | 1         | 2.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.7.14  | 8         | 21.62%  |
| 5.11.10 | 8         | 21.62%  |
| 5.14.18 | 7         | 18.92%  |
| 5.13.9  | 4         | 10.81%  |
| 5.11.2  | 3         | 8.11%   |
| 5.14.4  | 2         | 5.41%   |
| 5.13.8  | 2         | 5.41%   |
| 5.14.11 | 1         | 2.7%    |
| 5.12.12 | 1         | 2.7%    |
| 5.11.0  | 1         | 2.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 12        | 33.33%  |
| 5.14    | 9         | 25%     |
| 5.7     | 8         | 22.22%  |
| 5.13    | 6         | 16.67%  |
| 5.12    | 1         | 2.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 35        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GNOME   | 35        | 97.22%  |
| Unknown | 1         | 2.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 35        | 97.22%  |
| Unknown | 1         | 2.78%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 35        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 16        | 45.71%  |
| ru_RU | 3         | 8.57%   |
| fr_FR | 3         | 8.57%   |
| pt_BR | 2         | 5.71%   |
| hu_HU | 2         | 5.71%   |
| de_DE | 2         | 5.71%   |
| sk_SK | 1         | 2.86%   |
| ru_UA | 1         | 2.86%   |
| nl_NL | 1         | 2.86%   |
| es_ES | 1         | 2.86%   |
| es_CL | 1         | 2.86%   |
| en_IN | 1         | 2.86%   |
| cs_CZ | 1         | 2.86%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 35        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ext4 | 35        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 35        | 97.22%  |
| GPT     | 1         | 2.78%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 7         | 20%     |
| Lenovo              | 6         | 17.14%  |
| ASUSTek Computer    | 6         | 17.14%  |
| Dell                | 4         | 11.43%  |
| Acer                | 3         | 8.57%   |
| Gigabyte Technology | 2         | 5.71%   |
| Chuwi               | 2         | 5.71%   |
| Apple               | 2         | 5.71%   |
| Toshiba             | 1         | 2.86%   |
| Intel               | 1         | 2.86%   |
| Gateway             | 1         | 2.86%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| HP Pavilion 17                         | 2         | 5.71%   |
| Toshiba Satellite C55-A-1F5            | 1         | 2.86%   |
| Lenovo Yoga Slim 7 14ARE05 82A2        | 1         | 2.86%   |
| Lenovo ThinkPad Edge E531 68851P6      | 1         | 2.86%   |
| Lenovo IdeaPadFlex 5 14IIL05 81X1      | 1         | 2.86%   |
| Lenovo IdeaPad S340-14API 81NB         | 1         | 2.86%   |
| Lenovo IdeaPad S145-15IWL 81S9         | 1         | 2.86%   |
| Lenovo IdeaCentre 3 07IMB05 90NB0020IN | 1         | 2.86%   |
| Intel X79                              | 1         | 2.86%   |
| HP ProBook 430 G3                      | 1         | 2.86%   |
| HP Pavilion Notebook                   | 1         | 2.86%   |
| HP Pavilion Gaming Laptop 15-ec0xxx    | 1         | 2.86%   |
| HP Pavilion Gaming Desktop TG01-1xxx   | 1         | 2.86%   |
| HP Laptop 14-dk1xxx                    | 1         | 2.86%   |
| Gigabyte X570 GAMING X                 | 1         | 2.86%   |
| Gigabyte B450M S2H V2                  | 1         | 2.86%   |
| Gateway NE71B                          | 1         | 2.86%   |
| Dell Precision M6800                   | 1         | 2.86%   |
| Dell Latitude 7490                     | 1         | 2.86%   |
| Dell Inspiron 5566                     | 1         | 2.86%   |
| Dell Inspiron 3542                     | 1         | 2.86%   |
| Chuwi LarkBox                          | 1         | 2.86%   |
| Chuwi HeroBook                         | 1         | 2.86%   |
| ASUS X555LD                            | 1         | 2.86%   |
| ASUS SABERTOOTH X79                    | 1         | 2.86%   |
| ASUS PRIME H410M-K                     | 1         | 2.86%   |
| ASUS PRIME A320M-K                     | 1         | 2.86%   |
| ASUS H61M-A/BR                         | 1         | 2.86%   |
| ASUS E202SA                            | 1         | 2.86%   |
| Apple MacBookPro10,1                   | 1         | 2.86%   |
| Apple iMac16,2                         | 1         | 2.86%   |
| Acer Iconia W700                       | 1         | 2.86%   |
| Acer ChiefRiver Platform               | 1         | 2.86%   |
| Acer Aspire GX-781                     | 1         | 2.86%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| HP Pavilion        | 5         | 14.29%  |
| Lenovo IdeaPad     | 2         | 5.71%   |
| Dell Inspiron      | 2         | 5.71%   |
| ASUS PRIME         | 2         | 5.71%   |
| Toshiba Satellite  | 1         | 2.86%   |
| Lenovo Yoga        | 1         | 2.86%   |
| Lenovo ThinkPad    | 1         | 2.86%   |
| Lenovo IdeaPadFlex | 1         | 2.86%   |
| Lenovo IdeaCentre  | 1         | 2.86%   |
| Intel X79          | 1         | 2.86%   |
| HP ProBook         | 1         | 2.86%   |
| HP Laptop          | 1         | 2.86%   |
| Gigabyte X570      | 1         | 2.86%   |
| Gigabyte B450M     | 1         | 2.86%   |
| Gateway NE71B      | 1         | 2.86%   |
| Dell Precision     | 1         | 2.86%   |
| Dell Latitude      | 1         | 2.86%   |
| Chuwi LarkBox      | 1         | 2.86%   |
| Chuwi HeroBook     | 1         | 2.86%   |
| ASUS X555LD        | 1         | 2.86%   |
| ASUS SABERTOOTH    | 1         | 2.86%   |
| ASUS H61M-A        | 1         | 2.86%   |
| ASUS E202SA        | 1         | 2.86%   |
| Apple MacBookPro10 | 1         | 2.86%   |
| Apple iMac16       | 1         | 2.86%   |
| Acer Iconia        | 1         | 2.86%   |
| Acer ChiefRiver    | 1         | 2.86%   |
| Acer Aspire        | 1         | 2.86%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 7         | 20%     |
| 2019 | 6         | 17.14%  |
| 2013 | 6         | 17.14%  |
| 2017 | 3         | 8.57%   |
| 2015 | 3         | 8.57%   |
| 2014 | 3         | 8.57%   |
| 2012 | 3         | 8.57%   |
| 2018 | 2         | 5.71%   |
| 2016 | 2         | 5.71%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 22        | 62.86%  |
| Desktop     | 10        | 28.57%  |
| Convertible | 1         | 2.86%   |
| Mini pc     | 1         | 2.86%   |
| All in one  | 1         | 2.86%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 35        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 35        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 16        | 45.71%  |
| 8.01-16.0  | 7         | 20%     |
| 3.01-4.0   | 6         | 17.14%  |
| 16.01-24.0 | 3         | 8.57%   |
| 32.01-64.0 | 2         | 5.71%   |
| 1.01-2.0   | 1         | 2.86%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 28        | 77.78%  |
| 2.01-3.0 | 3         | 8.33%   |
| 4.01-8.0 | 2         | 5.56%   |
| 0.51-1.0 | 2         | 5.56%   |
| 3.01-4.0 | 1         | 2.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 27        | 77.14%  |
| 2      | 5         | 14.29%  |
| 3      | 2         | 5.71%   |
| 4      | 1         | 2.86%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 26        | 74.29%  |
| Yes       | 9         | 25.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 82.86%  |
| No        | 6         | 17.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 88.57%  |
| No        | 4         | 11.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 71.43%  |
| No        | 10        | 28.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 7         | 20%     |
| Ukraine     | 3         | 8.57%   |
| France      | 3         | 8.57%   |
| Brazil      | 3         | 8.57%   |
| Russia      | 2         | 5.71%   |
| Germany     | 2         | 5.71%   |
| Chile       | 2         | 5.71%   |
| Canada      | 2         | 5.71%   |
| UAE         | 1         | 2.86%   |
| Slovakia    | 1         | 2.86%   |
| Serbia      | 1         | 2.86%   |
| Netherlands | 1         | 2.86%   |
| Iraq        | 1         | 2.86%   |
| India       | 1         | 2.86%   |
| Hungary     | 1         | 2.86%   |
| Greece      | 1         | 2.86%   |
| Finland     | 1         | 2.86%   |
| El Salvador | 1         | 2.86%   |
| Czechia     | 1         | 2.86%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Vancouver           | 2         | 5.71%   |
| Santiago            | 2         | 5.71%   |
| Waldachtal          | 1         | 2.86%   |
| Verden an der Aller | 1         | 2.86%   |
| Uruguaiana          | 1         | 2.86%   |
| Tyumen              | 1         | 2.86%   |
| Talence             | 1         | 2.86%   |
| Skydra              | 1         | 2.86%   |
| San Salvador        | 1         | 2.86%   |
| Rio de Janeiro      | 1         | 2.86%   |
| Prague              | 1         | 2.86%   |
| Pori                | 1         | 2.86%   |
| Parempuyre          | 1         | 2.86%   |
| Ottawa              | 1         | 2.86%   |
| Novoyavorovske      | 1         | 2.86%   |
| Novi Sad            | 1         | 2.86%   |
| Millers Creek       | 1         | 2.86%   |
| Mariupol            | 1         | 2.86%   |
| Levis               | 1         | 2.86%   |
| Lelystad            | 1         | 2.86%   |
| Lehighton           | 1         | 2.86%   |
| Kyiv                | 1         | 2.86%   |
| Krasnoyarsk         | 1         | 2.86%   |
| Kolkata             | 1         | 2.86%   |
| Kalispell           | 1         | 2.86%   |
| Juazeiro do Norte   | 1         | 2.86%   |
| Columbia            | 1         | 2.86%   |
| Castelnau-le-Lez    | 1         | 2.86%   |
| Budapest            | 1         | 2.86%   |
| Bratislava          | 1         | 2.86%   |
| Belton              | 1         | 2.86%   |
| Baghdad             | 1         | 2.86%   |
| Abu Dhabi           | 1         | 2.86%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 20%     |
| WDC                 | 7         | 7      | 15.56%  |
| Kingston            | 6         | 6      | 13.33%  |
| Samsung Electronics | 4         | 6      | 8.89%   |
| SK hynix            | 3         | 4      | 6.67%   |
| SanDisk             | 3         | 4      | 6.67%   |
| Toshiba             | 2         | 2      | 4.44%   |
| HGST                | 2         | 2      | 4.44%   |
| Apple               | 2         | 2      | 4.44%   |
| Transcend           | 1         | 1      | 2.22%   |
| SSSTC               | 1         | 1      | 2.22%   |
| PNY                 | 1         | 1      | 2.22%   |
| Intel               | 1         | 1      | 2.22%   |
| HECTRON             | 1         | 1      | 2.22%   |
| Crucial             | 1         | 1      | 2.22%   |
| Apacer              | 1         | 1      | 2.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| SK hynix NVMe SSD Drive 512GB             | 2         | 4.26%   |
| Seagate ST9500325AS 500GB                 | 2         | 4.26%   |
| Samsung NVMe SSD Drive 256GB              | 2         | 4.26%   |
| Kingston SA400S37120G 120GB SSD           | 2         | 4.26%   |
| WDC WDS240G2G0A-00JH30 240GB SSD          | 1         | 2.13%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 2.13%   |
| WDC WD5000LPVX-08V0TT5 500GB              | 1         | 2.13%   |
| WDC WD3200LPVX-08V0TT5 320GB              | 1         | 2.13%   |
| WDC WD1600AAJS-22L7A0 160GB               | 1         | 2.13%   |
| WDC WD10SPZX-24Z10 1TB                    | 1         | 2.13%   |
| WDC WD10EALX-009BA0 1TB                   | 1         | 2.13%   |
| Transcend TS64GMTS400 64GB SSD            | 1         | 2.13%   |
| Toshiba MQ01ABD032 320GB                  | 1         | 2.13%   |
| Toshiba HDWD120 2TB                       | 1         | 2.13%   |
| SSSTC CVB-8D128-HP 128GB SSD              | 1         | 2.13%   |
| SK hynix SKHynix_HFS512GD9TNG-L3A0B 512GB | 1         | 2.13%   |
| SK hynix HFS128G39TND-N210A 128GB SSD     | 1         | 2.13%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 1         | 2.13%   |
| Seagate ST4000DX001-1CE168 4TB            | 1         | 2.13%   |
| Seagate ST3500312CS 500GB                 | 1         | 2.13%   |
| Seagate ST2000DM001-1ER164 2TB            | 1         | 2.13%   |
| Seagate ST1000LM035-1RK172 1TB            | 1         | 2.13%   |
| Seagate ST1000DM010-2EP102 1TB            | 1         | 2.13%   |
| Seagate ST1000DM003-1SB102 1TB            | 1         | 2.13%   |
| SanDisk X300 MSATA 128GB SSD              | 1         | 2.13%   |
| SanDisk SD8SN8U512G1002 512GB SSD         | 1         | 2.13%   |
| SanDisk NVMe SSD Drive 500GB              | 1         | 2.13%   |
| Samsung SSD 860 QVO 1TB                   | 1         | 2.13%   |
| Samsung SSD 840 EVO 250GB                 | 1         | 2.13%   |
| Samsung NVMe SSD Drive 1024GB             | 1         | 2.13%   |
| PNY CS900 240GB SSD                       | 1         | 2.13%   |
| Kingston SV300S37A240G 240GB SSD          | 1         | 2.13%   |
| Kingston SHFS37A120G 120GB SSD            | 1         | 2.13%   |
| Kingston SA400M8240G 240GB SSD            | 1         | 2.13%   |
| Kingston RBUSNS4180S3256GJ 256GB SSD      | 1         | 2.13%   |
| Intel SSDSCKKF256G8 SATA 256GB            | 1         | 2.13%   |
| HGST HTS541010A9E680 1TB                  | 1         | 2.13%   |
| HGST HTS541010A7E630 1TB                  | 1         | 2.13%   |
| HECTRON HECX1-60G                         | 1         | 2.13%   |
| Crucial CT240BX500SSD1 240GB              | 1         | 2.13%   |
| Apple SSD SM768E 752GB                    | 1         | 2.13%   |
| Apple HDD HTS541010A9E662 1TB             | 1         | 2.13%   |
| Apacer AS350 120GB SSD                    | 1         | 2.13%   |

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
| Kingston            | 6         | 6      | 31.58%  |
| SanDisk             | 2         | 2      | 10.53%  |
| Samsung Electronics | 2         | 3      | 10.53%  |
| WDC                 | 1         | 1      | 5.26%   |
| Transcend           | 1         | 1      | 5.26%   |
| SSSTC               | 1         | 1      | 5.26%   |
| SK hynix            | 1         | 1      | 5.26%   |
| PNY                 | 1         | 1      | 5.26%   |
| Intel               | 1         | 1      | 5.26%   |
| Crucial             | 1         | 1      | 5.26%   |
| Apple               | 1         | 1      | 5.26%   |
| Apacer              | 1         | 1      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 19        | 20     | 44.19%  |
| SSD     | 17        | 20     | 39.53%  |
| NVMe    | 6         | 8      | 13.95%  |
| Unknown | 1         | 1      | 2.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 31        | 41     | 83.78%  |
| NVMe | 6         | 8      | 16.22%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 20        | 25     | 58.82%  |
| 0.51-1.0   | 11        | 12     | 32.35%  |
| 1.01-2.0   | 2         | 2      | 5.88%   |
| 3.01-4.0   | 1         | 1      | 2.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 14        | 40%     |
| 251-500    | 10        | 28.57%  |
| 501-1000   | 8         | 22.86%  |
| 51-100     | 2         | 5.71%   |
| 1001-2000  | 1         | 2.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 26        | 72.22%  |
| 21-50   | 6         | 16.67%  |
| 101-250 | 2         | 5.56%   |
| 251-500 | 1         | 2.78%   |
| 51-100  | 1         | 2.78%   |

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
| Detected | 35        | 48     | 97.22%  |
| Works    | 1         | 1      | 2.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 23        | 57.5%   |
| AMD                      | 9         | 22.5%   |
| Samsung Electronics      | 3         | 7.5%    |
| SK hynix                 | 2         | 5%      |
| SanDisk                  | 1         | 2.5%    |
| Marvell Technology Group | 1         | 2.5%    |
| ASMedia Technology       | 1         | 2.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 9         | 20.45%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5         | 11.36%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3         | 6.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 4.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 4.55%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 4.55%   |
| SK hynix Non-Volatile memory controller                                                 | 1         | 2.27%   |
| SK hynix BC511                                                                          | 1         | 2.27%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 2.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1         | 2.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 2.27%   |
| Samsung NVMe SSD Controller 980                                                         | 1         | 2.27%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1         | 2.27%   |
| Intel SATA Controller [RAID mode]                                                       | 1         | 2.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1         | 2.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 2.27%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 2.27%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1         | 2.27%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1         | 2.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 2.27%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1         | 2.27%   |
| AMD FCH SATA Controller D                                                               | 1         | 2.27%   |
| AMD FCH IDE Controller                                                                  | 1         | 2.27%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1         | 2.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 30        | 76.92%  |
| NVMe | 6         | 15.38%  |
| IDE  | 2         | 5.13%   |
| RAID | 1         | 2.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 24        | 68.57%  |
| AMD    | 11        | 31.43%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 5.71%   |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz            | 1         | 2.86%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 2.86%   |
| Intel Core i7-4930K CPU @ 3.40GHz             | 1         | 2.86%   |
| Intel Core i7-3820QM CPU @ 2.70GHz            | 1         | 2.86%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 2.86%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 1         | 2.86%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 2.86%   |
| Intel Core i5-5675R CPU @ 3.10GHz             | 1         | 2.86%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 2.86%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 2.86%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 1         | 2.86%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 2.86%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 2.86%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 2.86%   |
| Intel Core i3-2375M CPU @ 1.50GHz             | 1         | 2.86%   |
| Intel Core i3-10100F CPU @ 3.60GHz            | 1         | 2.86%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 1         | 2.86%   |
| Intel Celeron J4115 CPU @ 1.80GHz             | 1         | 2.86%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 2.86%   |
| Intel Celeron CPU G530 @ 2.40GHz              | 1         | 2.86%   |
| Intel Celeron 2957U @ 1.40GHz                 | 1         | 2.86%   |
| Intel Atom x5-E8000 CPU @ 1.04GHz             | 1         | 2.86%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 2.86%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 1         | 2.86%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 1         | 2.86%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 2.86%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.86%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 1         | 2.86%   |
| AMD E1-1200 APU with Radeon HD Graphics       | 1         | 2.86%   |
| AMD Athlon Silver 3050U with Radeon Graphics  | 1         | 2.86%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 1         | 2.86%   |
| AMD A8-5550M APU with Radeon HD Graphics      | 1         | 2.86%   |
| AMD A10-5745M APU with Radeon HD Graphics     | 1         | 2.86%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Computers | Percent |
|---------------|-----------|---------|
| Intel Core i5 | 8         | 22.86%  |
| Intel Core i3 | 7         | 20%     |
| AMD Ryzen 5   | 5         | 14.29%  |
| Intel Celeron | 4         | 11.43%  |
| Intel Core i7 | 3         | 8.57%   |
| AMD A8        | 2         | 5.71%   |
| Intel Xeon    | 1         | 2.86%   |
| Intel Atom    | 1         | 2.86%   |
| AMD Ryzen 7   | 1         | 2.86%   |
| AMD E1        | 1         | 2.86%   |
| AMD Athlon    | 1         | 2.86%   |
| AMD A10       | 1         | 2.86%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 15        | 42.86%  |
| 4      | 14        | 40%     |
| 6      | 4         | 11.43%  |
| 8      | 2         | 5.71%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 35        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 24        | 68.57%  |
| 1      | 11        | 31.43%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 35        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 4         | 11.43%  |
| 0x08108109 | 4         | 11.43%  |
| 0xa0653    | 3         | 8.57%   |
| 0x406e3    | 2         | 5.71%   |
| 0x40651    | 2         | 5.71%   |
| 0x206a7    | 2         | 5.71%   |
| 0x06001119 | 2         | 5.71%   |
| 0x906e9    | 1         | 2.86%   |
| 0x806ec    | 1         | 2.86%   |
| 0x806ea    | 1         | 2.86%   |
| 0x706e5    | 1         | 2.86%   |
| 0x706a1    | 1         | 2.86%   |
| 0x406c4    | 1         | 2.86%   |
| 0x406c3    | 1         | 2.86%   |
| 0x40671    | 1         | 2.86%   |
| 0x306e4    | 1         | 2.86%   |
| 0x306c3    | 1         | 2.86%   |
| 0x206d7    | 1         | 2.86%   |
| 0x0a201009 | 1         | 2.86%   |
| 0x08701021 | 1         | 2.86%   |
| 0x08600106 | 1         | 2.86%   |
| 0x07030105 | 1         | 2.86%   |
| 0x0500010d | 1         | 2.86%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| IvyBridge     | 5         | 14.29%  |
| Zen+          | 4         | 11.43%  |
| SandyBridge   | 3         | 8.57%   |
| KabyLake      | 3         | 8.57%   |
| Haswell       | 3         | 8.57%   |
| CometLake     | 3         | 8.57%   |
| Zen 2         | 2         | 5.71%   |
| Skylake       | 2         | 5.71%   |
| Silvermont    | 2         | 5.71%   |
| Piledriver    | 2         | 5.71%   |
| Zen 3         | 1         | 2.86%   |
| Puma          | 1         | 2.86%   |
| IceLake       | 1         | 2.86%   |
| Goldmont plus | 1         | 2.86%   |
| Broadwell     | 1         | 2.86%   |
| Bobcat        | 1         | 2.86%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 19        | 46.34%  |
| Nvidia | 11        | 26.83%  |
| AMD    | 11        | 26.83%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 9.3%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 9.3%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3         | 6.98%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 4.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 4.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 4.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 4.65%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 4.65%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 2.33%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 1         | 2.33%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 2.33%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 2.33%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 2.33%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 1         | 2.33%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 2.33%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 2.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 2.33%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.33%   |
| Intel Iris Pro Graphics 6200                                                             | 1         | 2.33%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 2.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 2.33%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 2.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 2.33%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 1         | 2.33%   |
| AMD Saturn XT [FirePro M6100]                                                            | 1         | 2.33%   |
| AMD Richland [Radeon HD 8610G]                                                           | 1         | 2.33%   |
| AMD Richland [Radeon HD 8550G]                                                           | 1         | 2.33%   |
| AMD Renoir                                                                               | 1         | 2.33%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 2.33%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1         | 2.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 14        | 40%     |
| 1 x AMD        | 7         | 20%     |
| 1 x Nvidia     | 6         | 17.14%  |
| Intel + Nvidia | 4         | 11.43%  |
| 2 x AMD        | 2         | 5.71%   |
| Intel + AMD    | 1         | 2.86%   |
| AMD + Nvidia   | 1         | 2.86%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver | Computers | Percent |
|--------|-----------|---------|
| Free   | 35        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 40%     |
| 0.51-1.0   | 6         | 17.14%  |
| 1.01-2.0   | 5         | 14.29%  |
| 2.01-3.0   | 4         | 11.43%  |
| 0.01-0.5   | 3         | 8.57%   |
| 7.01-8.0   | 1         | 2.86%   |
| 5.01-6.0   | 1         | 2.86%   |
| 3.01-4.0   | 1         | 2.86%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 18.92%  |
| AU Optronics        | 7         | 18.92%  |
| LG Display          | 5         | 13.51%  |
| Chimei Innolux      | 4         | 10.81%  |
| BOE                 | 3         | 8.11%   |
| Goldstar            | 2         | 5.41%   |
| Apple               | 2         | 5.41%   |
| Viotek              | 1         | 2.7%    |
| Philips             | 1         | 2.7%    |
| InfoVision          | 1         | 2.7%    |
| Dell                | 1         | 2.7%    |
| BenQ                | 1         | 2.7%    |
| AOC                 | 1         | 2.7%    |
| Acer                | 1         | 2.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Viotek GN34CW VTK3400 3440x1440 795x334mm 33.9-inch                  | 1         | 2.63%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch  | 1         | 2.63%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 1         | 2.63%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch    | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 382x215mm 17.3-inch | 1         | 2.63%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch    | 1         | 2.63%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 1         | 2.63%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 1         | 2.63%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch         | 1         | 2.63%   |
| LG Display LCD Monitor LGD04B3 1920x1080 345x194mm 15.6-inch         | 1         | 2.63%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch          | 1         | 2.63%   |
| LG Display LCD Monitor LGD0372 1600x900 382x215mm 17.3-inch          | 1         | 2.63%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch         | 1         | 2.63%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 1         | 2.63%   |
| Goldstar W1752 GSM4490 1440x900 370x232mm 17.2-inch                  | 1         | 2.63%   |
| Goldstar 24GL600F GSM5B73 1920x1080 531x298mm 24.0-inch              | 1         | 2.63%   |
| Dell P2421D DELD0FF 2560x1440 527x296mm 23.8-inch                    | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15BB 1920x1080 344x194mm 15.5-inch     | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch     | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch      | 1         | 2.63%   |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                 | 1         | 2.63%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 1         | 2.63%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                 | 1         | 2.63%   |
| BenQ LCD BNQ8024 2560x1440 597x336mm 27.0-inch                       | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch       | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO305D 1920x1080 256x144mm 11.6-inch       | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO233C 1366x768 309x173mm 13.9-inch        | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO223D 1920x1080 309x174mm 14.0-inch       | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO162C 1366x768 293x164mm 13.2-inch        | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch        | 1         | 2.63%   |
| Apple iMac APPA032 3840x2160 475x267mm 21.5-inch                     | 1         | 2.63%   |
| Apple Color LCD APPA00E 2880x1800 331x207mm 15.4-inch                | 1         | 2.63%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 1         | 2.63%   |
| Acer FT220HQL ACR03D2 1920x1080 476x268mm 21.5-inch                  | 1         | 2.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 17        | 47.22%  |
| 1366x768 (WXGA)  | 10        | 27.78%  |
| 1600x900 (HD+)   | 3         | 8.33%   |
| 2560x1440 (QHD)  | 2         | 5.56%   |
| 3840x2160 (4K)   | 1         | 2.78%   |
| 3440x1440        | 1         | 2.78%   |
| 2880x1800        | 1         | 2.78%   |
| 1440x900 (WXGA+) | 1         | 2.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 8         | 21.62%  |
| 17     | 5         | 13.51%  |
| 14     | 5         | 13.51%  |
| 21     | 4         | 10.81%  |
| 13     | 4         | 10.81%  |
| 24     | 3         | 8.11%   |
| 27     | 2         | 5.41%   |
| 11     | 2         | 5.41%   |
| 34     | 1         | 2.7%    |
| 31     | 1         | 2.7%    |
| 23     | 1         | 2.7%    |
| 18     | 1         | 2.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 16        | 44.44%  |
| 501-600     | 5         | 13.89%  |
| 401-500     | 5         | 13.89%  |
| 351-400     | 5         | 13.89%  |
| 201-300     | 3         | 8.33%   |
| 701-800     | 1         | 2.78%   |
| 601-700     | 1         | 2.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 33        | 91.67%  |
| 16/10 | 2         | 5.56%   |
| 21/9  | 1         | 2.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 8         | 22.22%  |
| 101-110        | 8         | 22.22%  |
| 201-250        | 6         | 16.67%  |
| 121-130        | 4         | 11.11%  |
| 51-60          | 2         | 5.56%   |
| 351-500        | 2         | 5.56%   |
| 301-350        | 2         | 5.56%   |
| 71-80          | 1         | 2.78%   |
| 151-200        | 1         | 2.78%   |
| 141-150        | 1         | 2.78%   |
| 131-140        | 1         | 2.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 15        | 41.67%  |
| 121-160 | 11        | 30.56%  |
| 51-100  | 7         | 19.44%  |
| 161-240 | 3         | 8.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 32        | 91.43%  |
| 2     | 3         | 8.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 22        | 41.51%  |
| Intel                           | 12        | 22.64%  |
| Qualcomm Atheros                | 8         | 15.09%  |
| Broadcom Limited                | 3         | 5.66%   |
| Broadcom                        | 3         | 5.66%   |
| Google                          | 2         | 3.77%   |
| TP-Link                         | 1         | 1.89%   |
| Qualcomm Atheros Communications | 1         | 1.89%   |
| Motorola PCS                    | 1         | 1.89%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 23.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 7.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 4.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 3.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 3.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 3.13%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 3.13%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.56%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 1.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 1.56%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.56%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.56%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.56%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1         | 1.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.56%   |
| Motorola PCS Moto G (5S) Plus                                     | 1         | 1.56%   |
| Intel Wireless-AC 9260                                            | 1         | 1.56%   |
| Intel Wireless 3165                                               | 1         | 1.56%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 1.56%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1         | 1.56%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 1.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.56%   |
| Intel Centrino Wireless-N 105                                     | 1         | 1.56%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.56%   |
| Google Pixel 6                                                    | 1         | 1.56%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 1.56%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.56%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.56%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.56%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 1         | 1.56%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                            | 1         | 1.56%   |
| Broadcom Limited BCM43142 802.11b/g/n                             | 1         | 1.56%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 1.56%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 9         | 29.03%  |
| Intel                           | 9         | 29.03%  |
| Qualcomm Atheros                | 7         | 22.58%  |
| Broadcom Limited                | 3         | 9.68%   |
| Broadcom                        | 2         | 6.45%   |
| Qualcomm Atheros Communications | 1         | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 3         | 9.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 2         | 6.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 2         | 6.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2         | 6.45%   |
| Intel Wi-Fi 6 AX200                                        | 2         | 6.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 3.23%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 1         | 3.23%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                 | 1         | 3.23%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 1         | 3.23%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1         | 3.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1         | 3.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 3.23%   |
| Qualcomm Atheros AR9271 802.11n                            | 1         | 3.23%   |
| Intel Wireless-AC 9260                                     | 1         | 3.23%   |
| Intel Wireless 3165                                        | 1         | 3.23%   |
| Intel Ice Lake-LP PCH CNVi WiFi                            | 1         | 3.23%   |
| Intel Gemini Lake PCH CNVi WiFi                            | 1         | 3.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1         | 3.23%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1         | 3.23%   |
| Intel Centrino Wireless-N 105                              | 1         | 3.23%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter | 1         | 3.23%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                     | 1         | 3.23%   |
| Broadcom Limited BCM43142 802.11b/g/n                      | 1         | 3.23%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                | 1         | 3.23%   |
| Broadcom BCM43142 802.11b/g/n                              | 1         | 3.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 21        | 67.74%  |
| Intel                 | 3         | 9.68%   |
| Qualcomm Atheros      | 2         | 6.45%   |
| Google                | 2         | 6.45%   |
| Broadcom              | 2         | 6.45%   |
| TP-Link               | 1         | 3.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 46.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 15.63%  |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 3.13%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 3.13%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 3.13%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 3.13%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 3.13%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 3.13%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 3.13%   |
| Google Pixel 6                                                    | 1         | 3.13%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 3.13%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 3.13%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 3.13%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 3.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 31        | 50.82%  |
| Ethernet | 29        | 47.54%  |
| Unknown  | 1         | 1.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 20        | 58.82%  |
| WiFi     | 14        | 41.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 21        | 60%     |
| 1     | 12        | 34.29%  |
| 3     | 1         | 2.86%   |
| 0     | 1         | 2.86%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 29        | 80.56%  |
| Yes  | 7         | 19.44%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 7         | 28%     |
| Realtek Semiconductor           | 6         | 24%     |
| Qualcomm Atheros Communications | 4         | 16%     |
| Lite-On Technology              | 3         | 12%     |
| Apple                           | 2         | 8%      |
| Toshiba                         | 1         | 4%      |
| Dell                            | 1         | 4%      |
| ASUSTek Computer                | 1         | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                        | 3         | 12%     |
| Qualcomm Atheros  Bluetooth Device             | 3         | 12%     |
| Realtek  Bluetooth 4.2 Adapter                 | 2         | 8%      |
| Lite-On Broadcom BCM43142A0 Bluetooth Device   | 2         | 8%      |
| Intel Bluetooth wireless interface             | 2         | 8%      |
| Toshiba Bluetooth Device                       | 1         | 4%      |
| Realtek RTL8821A Bluetooth                     | 1         | 4%      |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 4%      |
| Lite-On Bluetooth Device                       | 1         | 4%      |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1         | 4%      |
| Intel Wireless-AC 3168 Bluetooth               | 1         | 4%      |
| Intel Bluetooth Device                         | 1         | 4%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 4%      |
| Intel AX200 Bluetooth                          | 1         | 4%      |
| Dell Broadcom BCM20702A0 Bluetooth             | 1         | 4%      |
| ASUS Broadcom BCM20702A0 Bluetooth             | 1         | 4%      |
| Apple Bluetooth USB Host Controller            | 1         | 4%      |
| Apple Bluetooth Host Controller                | 1         | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 24        | 51.06%  |
| AMD                 | 12        | 25.53%  |
| Nvidia              | 9         | 19.15%  |
| Huawei Technologies | 1         | 2.13%   |
| C-Media Electronics | 1         | 2.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 8.33%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 8.33%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 6.67%   |
| AMD FCH Azalia Controller                                                                         | 4         | 6.67%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 5%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 5%      |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 3.33%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 2         | 3.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 3.33%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 3.33%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 3.33%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 3.33%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.67%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.67%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.67%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.67%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.67%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.67%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 1.67%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.67%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 1.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.67%   |
| Huawei Technologies USB-C HEADSET                                                                 | 1         | 1.67%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                                               | 1         | 1.67%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.67%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                                | 1         | 1.67%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.67%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.67%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 1.67%   |

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
| Chicony Electronics                    | 6         | 24%     |
| Suyin                                  | 3         | 12%     |
| Realtek Semiconductor                  | 3         | 12%     |
| Syntek                                 | 2         | 8%      |
| Sunplus Innovation Technology          | 2         | 8%      |
| Microdia                               | 2         | 8%      |
| Logitech                               | 2         | 8%      |
| Apple                                  | 2         | 8%      |
| IMC Networks                           | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) | 1         | 4%      |
| 2M UVC CAMERA                          | 1         | 4%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Suyin HP Truevision HD                           | 3         | 11.54%  |
| Syntek Integrated Camera                         | 2         | 7.69%   |
| Realtek USB Camera                               | 2         | 7.69%   |
| Chicony Integrated Camera                        | 2         | 7.69%   |
| Apple FaceTime HD Camera (Built-in)              | 2         | 7.69%   |
| Sunplus Integrated_Webcam_HD                     | 1         | 3.85%   |
| Sunplus HD WebCam                                | 1         | 3.85%   |
| Realtek Integrated Camera                        | 1         | 3.85%   |
| Microdia Integrated_Webcam_HD                    | 1         | 3.85%   |
| Microdia Integrated Webcam HD                    | 1         | 3.85%   |
| Logitech Webcam C270                             | 1         | 3.85%   |
| Logitech HD Pro Webcam C920                      | 1         | 3.85%   |
| IMC Networks HP TrueVision HD Camera             | 1         | 3.85%   |
| Chicony USB2.0 VGA UVC WebCam                    | 1         | 3.85%   |
| Chicony TOSHIBA Web Camera - HD                  | 1         | 3.85%   |
| Chicony HP HD Camera                             | 1         | 3.85%   |
| Chicony HD WebCam                                | 1         | 3.85%   |
| Chicony 5M Cam                                   | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 1         | 3.85%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam              | 1         | 3.85%   |

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
| 1     | 14        | 40%     |
| 2     | 10        | 28.57%  |
| 3     | 5         | 14.29%  |
| 4     | 3         | 8.57%   |
| 0     | 3         | 8.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 21        | 34.43%  |
| Net/wireless             | 16        | 26.23%  |
| Bluetooth                | 5         | 8.2%    |
| Multimedia controller    | 4         | 6.56%   |
| Card reader              | 4         | 6.56%   |
| Net/ethernet             | 3         | 4.92%   |
| Graphics card            | 3         | 4.92%   |
| Fingerprint reader       | 2         | 3.28%   |
| Storage/ide              | 1         | 1.64%   |
| Firewire controller      | 1         | 1.64%   |
| Chipcard                 | 1         | 1.64%   |

