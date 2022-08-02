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

Total: 44

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer     | Aspire A515-51G             | Notebook    | [4856a5fefb](https://linux-hardware.org/?probe=4856a5fefb) | Jul 22, 2022 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME OS Nightly | 26        | 72.22%  |
| GNOME OS 3.38    | 7         | 19.44%  |
| GNOME OS 42      | 1         | 2.78%   |
| GNOME OS 41      | 1         | 2.78%   |
| GNOME OS 40      | 1         | 2.78%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| GNOME OS | 36        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.7.14  | 8         | 21.05%  |
| 5.11.10 | 8         | 21.05%  |
| 5.14.18 | 7         | 18.42%  |
| 5.13.9  | 4         | 10.53%  |
| 5.11.2  | 3         | 7.89%   |
| 5.14.4  | 2         | 5.26%   |
| 5.13.8  | 2         | 5.26%   |
| 5.18.10 | 1         | 2.63%   |
| 5.14.11 | 1         | 2.63%   |
| 5.12.12 | 1         | 2.63%   |
| 5.11.0  | 1         | 2.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.7.14  | 8         | 21.05%  |
| 5.11.10 | 8         | 21.05%  |
| 5.14.18 | 7         | 18.42%  |
| 5.13.9  | 4         | 10.53%  |
| 5.11.2  | 3         | 7.89%   |
| 5.14.4  | 2         | 5.26%   |
| 5.13.8  | 2         | 5.26%   |
| 5.18.10 | 1         | 2.63%   |
| 5.14.11 | 1         | 2.63%   |
| 5.12.12 | 1         | 2.63%   |
| 5.11.0  | 1         | 2.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 12        | 32.43%  |
| 5.14    | 9         | 24.32%  |
| 5.7     | 8         | 21.62%  |
| 5.13    | 6         | 16.22%  |
| 5.18    | 1         | 2.7%    |
| 5.12    | 1         | 2.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 36        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GNOME   | 36        | 97.3%   |
| Unknown | 1         | 2.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 36        | 97.3%   |
| Unknown | 1         | 2.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 36        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 16        | 44.44%  |
| ru_RU | 4         | 11.11%  |
| fr_FR | 3         | 8.33%   |
| pt_BR | 2         | 5.56%   |
| hu_HU | 2         | 5.56%   |
| de_DE | 2         | 5.56%   |
| sk_SK | 1         | 2.78%   |
| ru_UA | 1         | 2.78%   |
| nl_NL | 1         | 2.78%   |
| es_ES | 1         | 2.78%   |
| es_CL | 1         | 2.78%   |
| en_IN | 1         | 2.78%   |
| cs_CZ | 1         | 2.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 36        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ext4 | 36        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 36        | 97.3%   |
| GPT     | 1         | 2.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 36        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 36        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 7         | 19.44%  |
| Lenovo              | 6         | 16.67%  |
| ASUSTek Computer    | 6         | 16.67%  |
| Dell                | 4         | 11.11%  |
| Acer                | 4         | 11.11%  |
| Gigabyte Technology | 2         | 5.56%   |
| Chuwi               | 2         | 5.56%   |
| Apple               | 2         | 5.56%   |
| Toshiba             | 1         | 2.78%   |
| Intel               | 1         | 2.78%   |
| Gateway             | 1         | 2.78%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| HP Pavilion 17                         | 2         | 5.56%   |
| Toshiba Satellite C55-A-1F5            | 1         | 2.78%   |
| Lenovo Yoga Slim 7 14ARE05 82A2        | 1         | 2.78%   |
| Lenovo ThinkPad Edge E531 68851P6      | 1         | 2.78%   |
| Lenovo IdeaPadFlex 5 14IIL05 81X1      | 1         | 2.78%   |
| Lenovo IdeaPad S340-14API 81NB         | 1         | 2.78%   |
| Lenovo IdeaPad S145-15IWL 81S9         | 1         | 2.78%   |
| Lenovo IdeaCentre 3 07IMB05 90NB0020IN | 1         | 2.78%   |
| Intel X79                              | 1         | 2.78%   |
| HP ProBook 430 G3                      | 1         | 2.78%   |
| HP Pavilion Notebook                   | 1         | 2.78%   |
| HP Pavilion Gaming Laptop 15-ec0xxx    | 1         | 2.78%   |
| HP Pavilion Gaming Desktop TG01-1xxx   | 1         | 2.78%   |
| HP Laptop 14-dk1xxx                    | 1         | 2.78%   |
| Gigabyte X570 GAMING X                 | 1         | 2.78%   |
| Gigabyte B450M S2H V2                  | 1         | 2.78%   |
| Gateway NE71B                          | 1         | 2.78%   |
| Dell Precision M6800                   | 1         | 2.78%   |
| Dell Latitude 7490                     | 1         | 2.78%   |
| Dell Inspiron 5566                     | 1         | 2.78%   |
| Dell Inspiron 3542                     | 1         | 2.78%   |
| Chuwi LarkBox                          | 1         | 2.78%   |
| Chuwi HeroBook                         | 1         | 2.78%   |
| ASUS X555LD                            | 1         | 2.78%   |
| ASUS SABERTOOTH X79                    | 1         | 2.78%   |
| ASUS PRIME H410M-K                     | 1         | 2.78%   |
| ASUS PRIME A320M-K                     | 1         | 2.78%   |
| ASUS H61M-A/BR                         | 1         | 2.78%   |
| ASUS E202SA                            | 1         | 2.78%   |
| Apple MacBookPro10,1                   | 1         | 2.78%   |
| Apple iMac16,2                         | 1         | 2.78%   |
| Acer Iconia W700                       | 1         | 2.78%   |
| Acer ChiefRiver Platform               | 1         | 2.78%   |
| Acer Aspire GX-781                     | 1         | 2.78%   |
| Acer Aspire A515-51G                   | 1         | 2.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| HP Pavilion        | 5         | 13.89%  |
| Lenovo IdeaPad     | 2         | 5.56%   |
| Dell Inspiron      | 2         | 5.56%   |
| ASUS PRIME         | 2         | 5.56%   |
| Acer Aspire        | 2         | 5.56%   |
| Toshiba Satellite  | 1         | 2.78%   |
| Lenovo Yoga        | 1         | 2.78%   |
| Lenovo ThinkPad    | 1         | 2.78%   |
| Lenovo IdeaPadFlex | 1         | 2.78%   |
| Lenovo IdeaCentre  | 1         | 2.78%   |
| Intel X79          | 1         | 2.78%   |
| HP ProBook         | 1         | 2.78%   |
| HP Laptop          | 1         | 2.78%   |
| Gigabyte X570      | 1         | 2.78%   |
| Gigabyte B450M     | 1         | 2.78%   |
| Gateway NE71B      | 1         | 2.78%   |
| Dell Precision     | 1         | 2.78%   |
| Dell Latitude      | 1         | 2.78%   |
| Chuwi LarkBox      | 1         | 2.78%   |
| Chuwi HeroBook     | 1         | 2.78%   |
| ASUS X555LD        | 1         | 2.78%   |
| ASUS SABERTOOTH    | 1         | 2.78%   |
| ASUS H61M-A        | 1         | 2.78%   |
| ASUS E202SA        | 1         | 2.78%   |
| Apple MacBookPro10 | 1         | 2.78%   |
| Apple iMac16       | 1         | 2.78%   |
| Acer Iconia        | 1         | 2.78%   |
| Acer ChiefRiver    | 1         | 2.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 7         | 19.44%  |
| 2019 | 6         | 16.67%  |
| 2013 | 6         | 16.67%  |
| 2017 | 4         | 11.11%  |
| 2015 | 3         | 8.33%   |
| 2014 | 3         | 8.33%   |
| 2012 | 3         | 8.33%   |
| 2018 | 2         | 5.56%   |
| 2016 | 2         | 5.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 23        | 63.89%  |
| Desktop     | 10        | 27.78%  |
| Convertible | 1         | 2.78%   |
| Mini pc     | 1         | 2.78%   |
| All in one  | 1         | 2.78%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 36        | 100%    |

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


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 16        | 44.44%  |
| 3.01-4.0   | 7         | 19.44%  |
| 8.01-16.0  | 7         | 19.44%  |
| 16.01-24.0 | 3         | 8.33%   |
| 32.01-64.0 | 2         | 5.56%   |
| 1.01-2.0   | 1         | 2.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 29        | 78.38%  |
| 2.01-3.0 | 3         | 8.11%   |
| 4.01-8.0 | 2         | 5.41%   |
| 0.51-1.0 | 2         | 5.41%   |
| 3.01-4.0 | 1         | 2.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 28        | 77.78%  |
| 2      | 5         | 13.89%  |
| 3      | 2         | 5.56%   |
| 4      | 1         | 2.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 27        | 75%     |
| Yes       | 9         | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 83.33%  |
| No        | 6         | 16.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 88.89%  |
| No        | 4         | 11.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 72.22%  |
| No        | 10        | 27.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 7         | 19.44%  |
| Ukraine     | 3         | 8.33%   |
| France      | 3         | 8.33%   |
| Brazil      | 3         | 8.33%   |
| Russia      | 2         | 5.56%   |
| Germany     | 2         | 5.56%   |
| Chile       | 2         | 5.56%   |
| Canada      | 2         | 5.56%   |
| UAE         | 1         | 2.78%   |
| Slovakia    | 1         | 2.78%   |
| Serbia      | 1         | 2.78%   |
| Netherlands | 1         | 2.78%   |
| Latvia      | 1         | 2.78%   |
| Iraq        | 1         | 2.78%   |
| India       | 1         | 2.78%   |
| Hungary     | 1         | 2.78%   |
| Greece      | 1         | 2.78%   |
| Finland     | 1         | 2.78%   |
| El Salvador | 1         | 2.78%   |
| Czechia     | 1         | 2.78%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Vancouver           | 2         | 5.56%   |
| Santiago            | 2         | 5.56%   |
| Waldachtal          | 1         | 2.78%   |
| Verden an der Aller | 1         | 2.78%   |
| Uruguaiana          | 1         | 2.78%   |
| Tyumen              | 1         | 2.78%   |
| Talence             | 1         | 2.78%   |
| Skydra              | 1         | 2.78%   |
| San Salvador        | 1         | 2.78%   |
| Rio de Janeiro      | 1         | 2.78%   |
| Riga                | 1         | 2.78%   |
| Prague              | 1         | 2.78%   |
| Pori                | 1         | 2.78%   |
| Parempuyre          | 1         | 2.78%   |
| Ottawa              | 1         | 2.78%   |
| Novoyavorovske      | 1         | 2.78%   |
| Novi Sad            | 1         | 2.78%   |
| Millers Creek       | 1         | 2.78%   |
| Mariupol            | 1         | 2.78%   |
| Levis               | 1         | 2.78%   |
| Lelystad            | 1         | 2.78%   |
| Lehighton           | 1         | 2.78%   |
| Kyiv                | 1         | 2.78%   |
| Krasnoyarsk         | 1         | 2.78%   |
| Kolkata             | 1         | 2.78%   |
| Kalispell           | 1         | 2.78%   |
| Juazeiro do Norte   | 1         | 2.78%   |
| Columbia            | 1         | 2.78%   |
| Castelnau-le-Lez    | 1         | 2.78%   |
| Budapest            | 1         | 2.78%   |
| Bratislava          | 1         | 2.78%   |
| Belton              | 1         | 2.78%   |
| Baghdad             | 1         | 2.78%   |
| Abu Dhabi           | 1         | 2.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 19.57%  |
| WDC                 | 7         | 7      | 15.22%  |
| Kingston            | 6         | 6      | 13.04%  |
| Samsung Electronics | 4         | 6      | 8.7%    |
| SK hynix            | 3         | 4      | 6.52%   |
| SanDisk             | 3         | 4      | 6.52%   |
| Toshiba             | 2         | 2      | 4.35%   |
| HGST                | 2         | 2      | 4.35%   |
| Apple               | 2         | 2      | 4.35%   |
| Transcend           | 1         | 1      | 2.17%   |
| SSSTC               | 1         | 1      | 2.17%   |
| PNY                 | 1         | 1      | 2.17%   |
| Micron Technology   | 1         | 1      | 2.17%   |
| Intel               | 1         | 1      | 2.17%   |
| HECTRON             | 1         | 1      | 2.17%   |
| Crucial             | 1         | 1      | 2.17%   |
| Apacer              | 1         | 1      | 2.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| SK hynix NVMe SSD Drive 512GB             | 2         | 4.17%   |
| Seagate ST9500325AS 500GB                 | 2         | 4.17%   |
| Samsung NVMe SSD Drive 256GB              | 2         | 4.17%   |
| Kingston SA400S37120G 120GB SSD           | 2         | 4.17%   |
| WDC WDS240G2G0A-00JH30 240GB SSD          | 1         | 2.08%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 2.08%   |
| WDC WD5000LPVX-08V0TT5 500GB              | 1         | 2.08%   |
| WDC WD3200LPVX-08V0TT5 320GB              | 1         | 2.08%   |
| WDC WD1600AAJS-22L7A0 160GB               | 1         | 2.08%   |
| WDC WD10SPZX-24Z10 1TB                    | 1         | 2.08%   |
| WDC WD10EALX-009BA0 1TB                   | 1         | 2.08%   |
| Transcend TS64GMTS400 64GB SSD            | 1         | 2.08%   |
| Toshiba MQ01ABD032 320GB                  | 1         | 2.08%   |
| Toshiba HDWD120 2TB                       | 1         | 2.08%   |
| SSSTC CVB-8D128-HP 128GB SSD              | 1         | 2.08%   |
| SK hynix SKHynix_HFS512GD9TNG-L3A0B 512GB | 1         | 2.08%   |
| SK hynix HFS128G39TND-N210A 128GB SSD     | 1         | 2.08%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 1         | 2.08%   |
| Seagate ST4000DX001-1CE168 4TB            | 1         | 2.08%   |
| Seagate ST3500312CS 500GB                 | 1         | 2.08%   |
| Seagate ST2000DM001-1ER164 2TB            | 1         | 2.08%   |
| Seagate ST1000LM035-1RK172 1TB            | 1         | 2.08%   |
| Seagate ST1000DM010-2EP102 1TB            | 1         | 2.08%   |
| Seagate ST1000DM003-1SB102 1TB            | 1         | 2.08%   |
| SanDisk X300 MSATA 128GB SSD              | 1         | 2.08%   |
| SanDisk SD8SN8U512G1002 512GB SSD         | 1         | 2.08%   |
| SanDisk NVMe SSD Drive 500GB              | 1         | 2.08%   |
| Samsung SSD 860 QVO 1TB                   | 1         | 2.08%   |
| Samsung SSD 840 EVO 250GB                 | 1         | 2.08%   |
| Samsung NVMe SSD Drive 1024GB             | 1         | 2.08%   |
| PNY CS900 240GB SSD                       | 1         | 2.08%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD       | 1         | 2.08%   |
| Kingston SV300S37A240G 240GB SSD          | 1         | 2.08%   |
| Kingston SHFS37A120G 120GB SSD            | 1         | 2.08%   |
| Kingston SA400M8240G 240GB SSD            | 1         | 2.08%   |
| Kingston RBUSNS4180S3256GJ 256GB SSD      | 1         | 2.08%   |
| Intel SSDSCKKF256G8 SATA 256GB            | 1         | 2.08%   |
| HGST HTS541010A9E680 1TB                  | 1         | 2.08%   |
| HGST HTS541010A7E630 1TB                  | 1         | 2.08%   |
| HECTRON HECX1-60G                         | 1         | 2.08%   |
| Crucial CT240BX500SSD1 240GB              | 1         | 2.08%   |
| Apple SSD SM768E 752GB                    | 1         | 2.08%   |
| Apple HDD HTS541010A9E662 1TB             | 1         | 2.08%   |
| Apacer AS350 120GB SSD                    | 1         | 2.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


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

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 6      | 30%     |
| SanDisk             | 2         | 2      | 10%     |
| Samsung Electronics | 2         | 3      | 10%     |
| WDC                 | 1         | 1      | 5%      |
| Transcend           | 1         | 1      | 5%      |
| SSSTC               | 1         | 1      | 5%      |
| SK hynix            | 1         | 1      | 5%      |
| PNY                 | 1         | 1      | 5%      |
| Micron Technology   | 1         | 1      | 5%      |
| Intel               | 1         | 1      | 5%      |
| Crucial             | 1         | 1      | 5%      |
| Apple               | 1         | 1      | 5%      |
| Apacer              | 1         | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 19        | 20     | 43.18%  |
| SSD     | 18        | 21     | 40.91%  |
| NVMe    | 6         | 8      | 13.64%  |
| Unknown | 1         | 1      | 2.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 32        | 42     | 84.21%  |
| NVMe | 6         | 8      | 15.79%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 21        | 26     | 60%     |
| 0.51-1.0   | 11        | 12     | 31.43%  |
| 1.01-2.0   | 2         | 2      | 5.71%   |
| 3.01-4.0   | 1         | 1      | 2.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 15        | 41.67%  |
| 251-500    | 10        | 27.78%  |
| 501-1000   | 8         | 22.22%  |
| 51-100     | 2         | 5.56%   |
| 1001-2000  | 1         | 2.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 27        | 72.97%  |
| 21-50   | 6         | 16.22%  |
| 101-250 | 2         | 5.41%   |
| 251-500 | 1         | 2.7%    |
| 51-100  | 1         | 2.7%    |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 36        | 49     | 97.3%   |
| Works    | 1         | 1      | 2.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 24        | 58.54%  |
| AMD                      | 9         | 21.95%  |
| Samsung Electronics      | 3         | 7.32%   |
| SK hynix                 | 2         | 4.88%   |
| SanDisk                  | 1         | 2.44%   |
| Marvell Technology Group | 1         | 2.44%   |
| ASMedia Technology       | 1         | 2.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 9         | 20%     |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5         | 11.11%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 8.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 4.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 4.44%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 4.44%   |
| SK hynix Non-Volatile memory controller                                                 | 1         | 2.22%   |
| SK hynix BC511                                                                          | 1         | 2.22%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 2.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1         | 2.22%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 2.22%   |
| Samsung NVMe SSD Controller 980                                                         | 1         | 2.22%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1         | 2.22%   |
| Intel SATA Controller [RAID mode]                                                       | 1         | 2.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1         | 2.22%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 2.22%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 2.22%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1         | 2.22%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1         | 2.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1         | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 2.22%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1         | 2.22%   |
| AMD FCH SATA Controller D                                                               | 1         | 2.22%   |
| AMD FCH IDE Controller                                                                  | 1         | 2.22%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1         | 2.22%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 31        | 77.5%   |
| NVMe | 6         | 15%     |
| IDE  | 2         | 5%      |
| RAID | 1         | 2.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 25        | 69.44%  |
| AMD    | 11        | 30.56%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 5.56%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 5.56%   |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz            | 1         | 2.78%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 2.78%   |
| Intel Core i7-4930K CPU @ 3.40GHz             | 1         | 2.78%   |
| Intel Core i7-3820QM CPU @ 2.70GHz            | 1         | 2.78%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 2.78%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 1         | 2.78%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 2.78%   |
| Intel Core i5-5675R CPU @ 3.10GHz             | 1         | 2.78%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 2.78%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 2.78%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 1         | 2.78%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 2.78%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 2.78%   |
| Intel Core i3-2375M CPU @ 1.50GHz             | 1         | 2.78%   |
| Intel Core i3-10100F CPU @ 3.60GHz            | 1         | 2.78%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 1         | 2.78%   |
| Intel Celeron J4115 CPU @ 1.80GHz             | 1         | 2.78%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 2.78%   |
| Intel Celeron CPU G530 @ 2.40GHz              | 1         | 2.78%   |
| Intel Celeron 2957U @ 1.40GHz                 | 1         | 2.78%   |
| Intel Atom x5-E8000 CPU @ 1.04GHz             | 1         | 2.78%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 2.78%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 1         | 2.78%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 1         | 2.78%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 2.78%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.78%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 1         | 2.78%   |
| AMD E1-1200 APU with Radeon HD Graphics       | 1         | 2.78%   |
| AMD Athlon Silver 3050U with Radeon Graphics  | 1         | 2.78%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 1         | 2.78%   |
| AMD A8-5550M APU with Radeon HD Graphics      | 1         | 2.78%   |
| AMD A10-5745M APU with Radeon HD Graphics     | 1         | 2.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model         | Computers | Percent |
|---------------|-----------|---------|
| Intel Core i5 | 8         | 22.22%  |
| Intel Core i3 | 8         | 22.22%  |
| AMD Ryzen 5   | 5         | 13.89%  |
| Intel Celeron | 4         | 11.11%  |
| Intel Core i7 | 3         | 8.33%   |
| AMD A8        | 2         | 5.56%   |
| Intel Xeon    | 1         | 2.78%   |
| Intel Atom    | 1         | 2.78%   |
| AMD Ryzen 7   | 1         | 2.78%   |
| AMD E1        | 1         | 2.78%   |
| AMD Athlon    | 1         | 2.78%   |
| AMD A10       | 1         | 2.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 16        | 44.44%  |
| 4      | 14        | 38.89%  |
| 6      | 4         | 11.11%  |
| 8      | 2         | 5.56%   |

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
| 2      | 25        | 69.44%  |
| 1      | 11        | 30.56%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 36        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 4         | 11.11%  |
| 0x08108109 | 4         | 11.11%  |
| 0xa0653    | 3         | 8.33%   |
| 0x406e3    | 3         | 8.33%   |
| 0x40651    | 2         | 5.56%   |
| 0x206a7    | 2         | 5.56%   |
| 0x06001119 | 2         | 5.56%   |
| 0x906e9    | 1         | 2.78%   |
| 0x806ec    | 1         | 2.78%   |
| 0x806ea    | 1         | 2.78%   |
| 0x706e5    | 1         | 2.78%   |
| 0x706a1    | 1         | 2.78%   |
| 0x406c4    | 1         | 2.78%   |
| 0x406c3    | 1         | 2.78%   |
| 0x40671    | 1         | 2.78%   |
| 0x306e4    | 1         | 2.78%   |
| 0x306c3    | 1         | 2.78%   |
| 0x206d7    | 1         | 2.78%   |
| 0x0a201009 | 1         | 2.78%   |
| 0x08701021 | 1         | 2.78%   |
| 0x08600106 | 1         | 2.78%   |
| 0x07030105 | 1         | 2.78%   |
| 0x0500010d | 1         | 2.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| IvyBridge     | 5         | 13.89%  |
| Zen+          | 4         | 11.11%  |
| Skylake       | 3         | 8.33%   |
| SandyBridge   | 3         | 8.33%   |
| KabyLake      | 3         | 8.33%   |
| Haswell       | 3         | 8.33%   |
| CometLake     | 3         | 8.33%   |
| Zen 2         | 2         | 5.56%   |
| Silvermont    | 2         | 5.56%   |
| Piledriver    | 2         | 5.56%   |
| Zen 3         | 1         | 2.78%   |
| Puma          | 1         | 2.78%   |
| IceLake       | 1         | 2.78%   |
| Goldmont plus | 1         | 2.78%   |
| Broadwell     | 1         | 2.78%   |
| Bobcat        | 1         | 2.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 20        | 46.51%  |
| Nvidia | 12        | 27.91%  |
| AMD    | 11        | 25.58%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 8.89%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 8.89%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3         | 6.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 6.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 4.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 4.44%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 4.44%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 4.44%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 2.22%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 1         | 2.22%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 2.22%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 2.22%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 2.22%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 2.22%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 1         | 2.22%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 2.22%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 2.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 2.22%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.22%   |
| Intel Iris Pro Graphics 6200                                                             | 1         | 2.22%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 2.22%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 2.22%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 2.22%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 2.22%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 1         | 2.22%   |
| AMD Saturn XT [FirePro M6100]                                                            | 1         | 2.22%   |
| AMD Richland [Radeon HD 8610G]                                                           | 1         | 2.22%   |
| AMD Richland [Radeon HD 8550G]                                                           | 1         | 2.22%   |
| AMD Renoir                                                                               | 1         | 2.22%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 2.22%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1         | 2.22%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 14        | 38.89%  |
| 1 x AMD        | 7         | 19.44%  |
| 1 x Nvidia     | 6         | 16.67%  |
| Intel + Nvidia | 5         | 13.89%  |
| 2 x AMD        | 2         | 5.56%   |
| Intel + AMD    | 1         | 2.78%   |
| AMD + Nvidia   | 1         | 2.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver | Computers | Percent |
|--------|-----------|---------|
| Free   | 36        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 38.89%  |
| 1.01-2.0   | 6         | 16.67%  |
| 0.51-1.0   | 6         | 16.67%  |
| 2.01-3.0   | 4         | 11.11%  |
| 0.01-0.5   | 3         | 8.33%   |
| 7.01-8.0   | 1         | 2.78%   |
| 5.01-6.0   | 1         | 2.78%   |
| 3.01-4.0   | 1         | 2.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 18.42%  |
| AU Optronics        | 7         | 18.42%  |
| LG Display          | 5         | 13.16%  |
| Chimei Innolux      | 5         | 13.16%  |
| BOE                 | 3         | 7.89%   |
| Goldstar            | 2         | 5.26%   |
| Apple               | 2         | 5.26%   |
| Viotek              | 1         | 2.63%   |
| Philips             | 1         | 2.63%   |
| InfoVision          | 1         | 2.63%   |
| Dell                | 1         | 2.63%   |
| BenQ                | 1         | 2.63%   |
| AOC                 | 1         | 2.63%   |
| Acer                | 1         | 2.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Viotek GN34CW VTK3400 3440x1440 795x334mm 33.9-inch                  | 1         | 2.56%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch  | 1         | 2.56%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 1         | 2.56%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 1         | 2.56%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch | 1         | 2.56%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 382x215mm 17.3-inch | 1         | 2.56%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch    | 1         | 2.56%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 1         | 2.56%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 1         | 2.56%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 1         | 2.56%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch         | 1         | 2.56%   |
| LG Display LCD Monitor LGD04B3 1920x1080 345x194mm 15.6-inch         | 1         | 2.56%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch          | 1         | 2.56%   |
| LG Display LCD Monitor LGD0372 1600x900 382x215mm 17.3-inch          | 1         | 2.56%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch         | 1         | 2.56%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 1         | 2.56%   |
| Goldstar W1752 GSM4490 1440x900 370x232mm 17.2-inch                  | 1         | 2.56%   |
| Goldstar 24GL600F GSM5B73 1920x1080 531x298mm 24.0-inch              | 1         | 2.56%   |
| Dell P2421D DELD0FF 2560x1440 527x296mm 23.8-inch                    | 1         | 2.56%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 1         | 2.56%   |
| Chimei Innolux LCD Monitor CMN15D6 1920x1080 344x193mm 15.5-inch     | 1         | 2.56%   |
| Chimei Innolux LCD Monitor CMN15BB 1920x1080 344x194mm 15.5-inch     | 1         | 2.56%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch     | 1         | 2.56%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch      | 1         | 2.56%   |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                 | 1         | 2.56%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 1         | 2.56%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                 | 1         | 2.56%   |
| BenQ LCD BNQ8024 2560x1440 597x336mm 27.0-inch                       | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch       | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch       | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO305D 1920x1080 256x144mm 11.6-inch       | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO233C 1366x768 309x173mm 13.9-inch        | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO223D 1920x1080 309x174mm 14.0-inch       | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO162C 1366x768 293x164mm 13.2-inch        | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch        | 1         | 2.56%   |
| Apple iMac APPA032 3840x2160 475x267mm 21.5-inch                     | 1         | 2.56%   |
| Apple Color LCD APPA00E 2880x1800 331x207mm 15.4-inch                | 1         | 2.56%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 1         | 2.56%   |
| Acer FT220HQL ACR03D2 1920x1080 476x268mm 21.5-inch                  | 1         | 2.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 18        | 48.65%  |
| 1366x768 (WXGA)  | 10        | 27.03%  |
| 1600x900 (HD+)   | 3         | 8.11%   |
| 2560x1440 (QHD)  | 2         | 5.41%   |
| 3840x2160 (4K)   | 1         | 2.7%    |
| 3440x1440        | 1         | 2.7%    |
| 2880x1800        | 1         | 2.7%    |
| 1440x900 (WXGA+) | 1         | 2.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 9         | 23.68%  |
| 17     | 5         | 13.16%  |
| 14     | 5         | 13.16%  |
| 21     | 4         | 10.53%  |
| 13     | 4         | 10.53%  |
| 24     | 3         | 7.89%   |
| 27     | 2         | 5.26%   |
| 11     | 2         | 5.26%   |
| 34     | 1         | 2.63%   |
| 31     | 1         | 2.63%   |
| 23     | 1         | 2.63%   |
| 18     | 1         | 2.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 45.95%  |
| 501-600     | 5         | 13.51%  |
| 401-500     | 5         | 13.51%  |
| 351-400     | 5         | 13.51%  |
| 201-300     | 3         | 8.11%   |
| 701-800     | 1         | 2.7%    |
| 601-700     | 1         | 2.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 34        | 91.89%  |
| 16/10 | 2         | 5.41%   |
| 21/9  | 1         | 2.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 9         | 24.32%  |
| 81-90          | 8         | 21.62%  |
| 201-250        | 6         | 16.22%  |
| 121-130        | 4         | 10.81%  |
| 51-60          | 2         | 5.41%   |
| 351-500        | 2         | 5.41%   |
| 301-350        | 2         | 5.41%   |
| 71-80          | 1         | 2.7%    |
| 151-200        | 1         | 2.7%    |
| 141-150        | 1         | 2.7%    |
| 131-140        | 1         | 2.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 15        | 40.54%  |
| 121-160 | 12        | 32.43%  |
| 51-100  | 7         | 18.92%  |
| 161-240 | 3         | 8.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 33        | 91.67%  |
| 2     | 3         | 8.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 23        | 41.82%  |
| Intel                           | 12        | 21.82%  |
| Qualcomm Atheros                | 9         | 16.36%  |
| Broadcom Limited                | 3         | 5.45%   |
| Broadcom                        | 3         | 5.45%   |
| Google                          | 2         | 3.64%   |
| TP-Link                         | 1         | 1.82%   |
| Qualcomm Atheros Communications | 1         | 1.82%   |
| Motorola PCS                    | 1         | 1.82%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 24.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 7.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 4.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 3.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 3.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 3.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 3.03%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 3.03%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.52%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.52%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 1.52%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 1.52%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.52%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.52%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.52%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1         | 1.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.52%   |
| Motorola PCS moto g pure                                          | 1         | 1.52%   |
| Intel Wireless-AC 9260                                            | 1         | 1.52%   |
| Intel Wireless 3165                                               | 1         | 1.52%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 1.52%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1         | 1.52%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.52%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 1.52%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.52%   |
| Intel Centrino Wireless-N 105                                     | 1         | 1.52%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.52%   |
| Google Pixel 6                                                    | 1         | 1.52%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 1.52%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.52%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.52%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.52%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 1         | 1.52%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                            | 1         | 1.52%   |
| Broadcom Limited BCM43142 802.11b/g/n                             | 1         | 1.52%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 1.52%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 9         | 28.13%  |
| Intel                           | 9         | 28.13%  |
| Qualcomm Atheros                | 8         | 25%     |
| Broadcom Limited                | 3         | 9.38%   |
| Broadcom                        | 2         | 6.25%   |
| Qualcomm Atheros Communications | 1         | 3.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 3         | 9.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 2         | 6.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 2         | 6.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 6.25%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2         | 6.25%   |
| Intel Wi-Fi 6 AX200                                        | 2         | 6.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 3.13%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 1         | 3.13%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                 | 1         | 3.13%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 1         | 3.13%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1         | 3.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 3.13%   |
| Qualcomm Atheros AR9271 802.11n                            | 1         | 3.13%   |
| Intel Wireless-AC 9260                                     | 1         | 3.13%   |
| Intel Wireless 3165                                        | 1         | 3.13%   |
| Intel Ice Lake-LP PCH CNVi WiFi                            | 1         | 3.13%   |
| Intel Gemini Lake PCH CNVi WiFi                            | 1         | 3.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1         | 3.13%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1         | 3.13%   |
| Intel Centrino Wireless-N 105                              | 1         | 3.13%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter | 1         | 3.13%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                     | 1         | 3.13%   |
| Broadcom Limited BCM43142 802.11b/g/n                      | 1         | 3.13%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                | 1         | 3.13%   |
| Broadcom BCM43142 802.11b/g/n                              | 1         | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 22        | 68.75%  |
| Intel                 | 3         | 9.38%   |
| Qualcomm Atheros      | 2         | 6.25%   |
| Google                | 2         | 6.25%   |
| Broadcom              | 2         | 6.25%   |
| TP-Link               | 1         | 3.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 48.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 15.15%  |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 3.03%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 3.03%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 3.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 3.03%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 3.03%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 3.03%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 3.03%   |
| Google Pixel 6                                                    | 1         | 3.03%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 3.03%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 3.03%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 3.03%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 3.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 32        | 50.79%  |
| Ethernet | 30        | 47.62%  |
| Unknown  | 1         | 1.59%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 20        | 57.14%  |
| WiFi     | 15        | 42.86%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 22        | 61.11%  |
| 1     | 12        | 33.33%  |
| 3     | 1         | 2.78%   |
| 0     | 1         | 2.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 30        | 81.08%  |
| Yes  | 7         | 18.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 7         | 26.92%  |
| Realtek Semiconductor           | 6         | 23.08%  |
| Qualcomm Atheros Communications | 4         | 15.38%  |
| Lite-On Technology              | 4         | 15.38%  |
| Apple                           | 2         | 7.69%   |
| Toshiba                         | 1         | 3.85%   |
| Dell                            | 1         | 3.85%   |
| ASUSTek Computer                | 1         | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                        | 3         | 11.54%  |
| Qualcomm Atheros  Bluetooth Device             | 3         | 11.54%  |
| Realtek  Bluetooth 4.2 Adapter                 | 2         | 7.69%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device   | 2         | 7.69%   |
| Intel Bluetooth wireless interface             | 2         | 7.69%   |
| Toshiba Bluetooth Device                       | 1         | 3.85%   |
| Realtek RTL8821A Bluetooth                     | 1         | 3.85%   |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 3.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 1         | 3.85%   |
| Lite-On Bluetooth Device                       | 1         | 3.85%   |
| Intel Wireless-AC 3168 Bluetooth               | 1         | 3.85%   |
| Intel Bluetooth Device                         | 1         | 3.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 3.85%   |
| Intel AX201 Bluetooth                          | 1         | 3.85%   |
| Intel AX200 Bluetooth                          | 1         | 3.85%   |
| Dell Broadcom BCM20702A0 Bluetooth             | 1         | 3.85%   |
| ASUS Broadcom BCM20702A0 Bluetooth             | 1         | 3.85%   |
| Apple Bluetooth USB Host Controller            | 1         | 3.85%   |
| Apple Bluetooth Host Controller                | 1         | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 25        | 52.08%  |
| AMD                 | 12        | 25%     |
| Nvidia              | 9         | 18.75%  |
| Huawei Technologies | 1         | 2.08%   |
| C-Media Electronics | 1         | 2.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 8.2%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 8.2%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 6.56%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 6.56%   |
| AMD FCH Azalia Controller                                                                         | 4         | 6.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 4.92%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 3.28%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 2         | 3.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 3.28%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 3.28%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 3.28%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 3.28%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 3.28%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.64%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.64%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.64%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.64%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.64%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.64%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.64%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.64%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.64%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 1.64%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.64%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 1.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.64%   |
| Huawei Technologies USB-C HEADSET                                                                 | 1         | 1.64%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                                               | 1         | 1.64%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.64%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                                | 1         | 1.64%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.64%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.64%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 1.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Micron Technology | 1         | 100%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Micron RAM MT53E1G32D4NQ-046WTE 8GB Row Of Chips LPDDR4 4266MT/s | 1         | 100%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| LPDDR4 | 1         | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Row Of Chips | 1         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size | Computers | Percent |
|------|-----------|---------|
| 8192 | 1         | 100%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 6         | 23.08%  |
| Suyin                                  | 3         | 11.54%  |
| Realtek Semiconductor                  | 3         | 11.54%  |
| Syntek                                 | 2         | 7.69%   |
| Sunplus Innovation Technology          | 2         | 7.69%   |
| Microdia                               | 2         | 7.69%   |
| Logitech                               | 2         | 7.69%   |
| Apple                                  | 2         | 7.69%   |
| Quanta                                 | 1         | 3.85%   |
| IMC Networks                           | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.85%   |
| 2M UVC CAMERA                          | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Suyin HP Truevision HD                           | 3         | 11.11%  |
| Syntek Integrated Camera                         | 2         | 7.41%   |
| Realtek USB Camera                               | 2         | 7.41%   |
| Chicony Integrated Camera                        | 2         | 7.41%   |
| Apple FaceTime HD Camera (Built-in)              | 2         | 7.41%   |
| Sunplus Integrated_Webcam_HD                     | 1         | 3.7%    |
| Sunplus HD Webcam                                | 1         | 3.7%    |
| Realtek Integrated Camera                        | 1         | 3.7%    |
| Quanta HD Webcam                                 | 1         | 3.7%    |
| Microdia Integrated_Webcam_HD                    | 1         | 3.7%    |
| Microdia Integrated Webcam HD                    | 1         | 3.7%    |
| Logitech Webcam C270                             | 1         | 3.7%    |
| Logitech HD Pro Webcam C920                      | 1         | 3.7%    |
| IMC Networks HP TrueVision HD Camera             | 1         | 3.7%    |
| Chicony USB2.0 VGA UVC WebCam                    | 1         | 3.7%    |
| Chicony TOSHIBA Web Camera - HD                  | 1         | 3.7%    |
| Chicony HP HD Camera                             | 1         | 3.7%    |
| Chicony HD WebCam                                | 1         | 3.7%    |
| Chicony 5M Cam                                   | 1         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 1         | 3.7%    |
| 2M UVC CAMERA NexiGo N660 FHD Webcam             | 1         | 3.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 1         | 50%     |
| Synaptics        | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader | 1         | 50%     |
| Unknown                                     | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 14        | 38.89%  |
| 2     | 11        | 30.56%  |
| 3     | 5         | 13.89%  |
| 4     | 3         | 8.33%   |
| 0     | 3         | 8.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 22        | 34.92%  |
| Net/wireless             | 16        | 25.4%   |
| Bluetooth                | 5         | 7.94%   |
| Multimedia controller    | 4         | 6.35%   |
| Graphics card            | 4         | 6.35%   |
| Card reader              | 4         | 6.35%   |
| Net/ethernet             | 3         | 4.76%   |
| Fingerprint reader       | 2         | 3.17%   |
| Storage/ide              | 1         | 1.59%   |
| Firewire controller      | 1         | 1.59%   |
| Chipcard                 | 1         | 1.59%   |

