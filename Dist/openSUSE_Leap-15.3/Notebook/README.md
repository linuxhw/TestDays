openSUSE Leap-15.3 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for openSUSE Leap-15.3.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=opensuse-leap-15.3

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

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
| Acer    | Aspire E1-772G              | [2ffccc532e](https://linux-hardware.org/?probe=2ffccc532e) | Oct 24, 2021 |
| Acer    | Nitro AN515-54              | [b6be115eec](https://linux-hardware.org/?probe=b6be115eec) | Oct 23, 2021 |
| Acer    | Aspire 5560                 | [39fd26f895](https://linux-hardware.org/?probe=39fd26f895) | Oct 22, 2021 |
| TUXEDO  | Aura 15 Gen1                | [627c62ae00](https://linux-hardware.org/?probe=627c62ae00) | Oct 21, 2021 |
| Medion  | E6436 MD61150               | [1edd4700fd](https://linux-hardware.org/?probe=1edd4700fd) | Oct 17, 2021 |
| Medion  | E6436 MD61150               | [2eaa34b93e](https://linux-hardware.org/?probe=2eaa34b93e) | Oct 17, 2021 |
| HP      | Laptop 15s-eq0xxx           | [fc4da04b79](https://linux-hardware.org/?probe=fc4da04b79) | Oct 16, 2021 |
| HP      | Laptop 17-ca1xxx            | [ae1811a242](https://linux-hardware.org/?probe=ae1811a242) | Oct 13, 2021 |
| Lenovo  | ThinkPad T490s 20NYS1XK0... | [d3700d8667](https://linux-hardware.org/?probe=d3700d8667) | Oct 13, 2021 |
| Lenovo  | ThinkPad L15 Gen 1 20U4S... | [3bb6121afa](https://linux-hardware.org/?probe=3bb6121afa) | Oct 13, 2021 |
| Lenovo  | ThinkPad X1 Carbon Gen 9... | [f3c6229102](https://linux-hardware.org/?probe=f3c6229102) | Oct 06, 2021 |
| Lenovo  | ThinkPad T550 20CJS1VD01    | [390b9a8a74](https://linux-hardware.org/?probe=390b9a8a74) | Oct 01, 2021 |
| MSI     | GP63 Leopard 8RD            | [21189bb3e0](https://linux-hardware.org/?probe=21189bb3e0) | Oct 01, 2021 |
| Dell    | Precision M6700             | [0d8cf3bf1c](https://linux-hardware.org/?probe=0d8cf3bf1c) | Sep 21, 2021 |
| Lenovo  | ThinkPad X1 Carbon 4th 2... | [44d0412dd3](https://linux-hardware.org/?probe=44d0412dd3) | Aug 27, 2021 |
| Samsung | 600B4B/600B5B               | [200275bbd6](https://linux-hardware.org/?probe=200275bbd6) | Aug 27, 2021 |
| Dell    | Precision M6700             | [191db00b83](https://linux-hardware.org/?probe=191db00b83) | Aug 26, 2021 |
| Lenovo  | V330-15IKB 81AX             | [4b5a1af4dd](https://linux-hardware.org/?probe=4b5a1af4dd) | Aug 26, 2021 |
| Lenovo  | G500 20236                  | [73a5085a79](https://linux-hardware.org/?probe=73a5085a79) | Aug 24, 2021 |
| Dell    | Latitude 5480               | [a2110d9601](https://linux-hardware.org/?probe=a2110d9601) | Aug 24, 2021 |
| Dell    | Latitude 5480               | [64e1f3e16c](https://linux-hardware.org/?probe=64e1f3e16c) | Aug 19, 2021 |
| Lenovo  | ThinkPad T61 8895W9U        | [424c5f3e75](https://linux-hardware.org/?probe=424c5f3e75) | Aug 19, 2021 |
| Dell    | Inspiron 3521               | [c68ce33d52](https://linux-hardware.org/?probe=c68ce33d52) | Aug 11, 2021 |
| Dell    | Inspiron 3521               | [9a422a10d3](https://linux-hardware.org/?probe=9a422a10d3) | Aug 11, 2021 |
| Dell    | Inspiron 7460               | [f954aa3826](https://linux-hardware.org/?probe=f954aa3826) | Aug 10, 2021 |
| Samsung | 600B4B/600B5B               | [0a650b495e](https://linux-hardware.org/?probe=0a650b495e) | Aug 09, 2021 |
| Lenovo  | ThinkPad T460 20FMS75800    | [1a1c3f469d](https://linux-hardware.org/?probe=1a1c3f469d) | Aug 07, 2021 |
| Lenovo  | ThinkPad X1 Carbon 4th 2... | [5953bc46ad](https://linux-hardware.org/?probe=5953bc46ad) | Aug 06, 2021 |
| Lenovo  | ThinkPad X1 Carbon 4th 2... | [fafaeed466](https://linux-hardware.org/?probe=fafaeed466) | Aug 06, 2021 |
| HP      | Stream Notebook PC 11       | [a612aa5d15](https://linux-hardware.org/?probe=a612aa5d15) | Jul 20, 2021 |
| Lenovo  | ThinkPad T450s 20BWA06J0... | [e4cd39ef75](https://linux-hardware.org/?probe=e4cd39ef75) | Jul 09, 2021 |
| Lenovo  | ThinkPad T450s 20BWA06J0... | [5565f4e4fe](https://linux-hardware.org/?probe=5565f4e4fe) | Jul 09, 2021 |
| Fujitsu | LIFEBOOK E754               | [e7923c27f1](https://linux-hardware.org/?probe=e7923c27f1) | Jul 08, 2021 |
| ASUSTek | G771JW                      | [8e6c4ddee8](https://linux-hardware.org/?probe=8e6c4ddee8) | Jun 24, 2021 |
| HP      | ZBook 17 G2                 | [3342d4d378](https://linux-hardware.org/?probe=3342d4d378) | Jun 17, 2021 |
| HP      | OMEN by HP Laptop 15-dc1... | [0c01b21401](https://linux-hardware.org/?probe=0c01b21401) | Jun 15, 2021 |
| Sony    | VPCSB15GB                   | [43a9d38ca0](https://linux-hardware.org/?probe=43a9d38ca0) | Jun 03, 2021 |
| Sony    | VGN-Z570AN                  | [13d58b8d90](https://linux-hardware.org/?probe=13d58b8d90) | May 21, 2021 |
| Sony    | VGN-Z570AN                  | [e6c7882e05](https://linux-hardware.org/?probe=e6c7882e05) | May 21, 2021 |
| MSI     | GS60 6QE                    | [93c6fd8911](https://linux-hardware.org/?probe=93c6fd8911) | May 18, 2021 |
| MSI     | GS60 6QE                    | [41fe777475](https://linux-hardware.org/?probe=41fe777475) | May 18, 2021 |
| ASUSTek | VivoBook 12_ASUS Laptop ... | [184bedf2fd](https://linux-hardware.org/?probe=184bedf2fd) | May 01, 2021 |
| HP      | Pavilion dx6500             | [091cc2c616](https://linux-hardware.org/?probe=091cc2c616) | Apr 13, 2021 |
| HP      | Pavilion dx6500             | [6ad0d5c87f](https://linux-hardware.org/?probe=6ad0d5c87f) | Apr 13, 2021 |
| Dell    | Inspiron 15 7000 Gaming     | [97a7246099](https://linux-hardware.org/?probe=97a7246099) | Mar 01, 2021 |
| Dell    | Inspiron 15 7000 Gaming     | [b1e186207c](https://linux-hardware.org/?probe=b1e186207c) | Feb 28, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 5.3.18-59.27-default | 6         | 18.18%  |
| 5.3.18-59.19-default | 5         | 15.15%  |
| 5.3.18-59.16-default | 5         | 15.15%  |
| 5.3.18-57-default    | 5         | 15.15%  |
| 5.3.18-59.5-default  | 2         | 6.06%   |
| 5.3.18-59.24-default | 2         | 6.06%   |
| 5.3.18-59.10-default | 2         | 6.06%   |
| 5.3.18-59.19-preempt | 1         | 3.03%   |
| 5.3.18-59.13-default | 1         | 3.03%   |
| 5.3.18-57-preempt    | 1         | 3.03%   |
| 5.3.18-56-default    | 1         | 3.03%   |
| 5.3.18-52-default    | 1         | 3.03%   |
| 5.3.18-46-default    | 1         | 3.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.3.18  | 33        | 100%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.3     | 33        | 100%    |

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


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 11        | 32.35%  |
| KDE        | 8         | 23.53%  |
| GNOME      | 6         | 17.65%  |
| XFCE       | 5         | 14.71%  |
| X-Cinnamon | 2         | 5.88%   |
| Unknown    | 2         | 5.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 26        | 78.79%  |
| Wayland | 7         | 21.21%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 17        | 51.52%  |
| SDDM    | 7         | 21.21%  |
| LightDM | 7         | 21.21%  |
| XDM     | 1         | 3.03%   |
| GDM     | 1         | 3.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 14        | 42.42%  |
| de_DE | 6         | 18.18%  |
| POSIX | 2         | 6.06%   |
| fr_FR | 2         | 6.06%   |
| es_ES | 2         | 6.06%   |
| zh_CN | 1         | 3.03%   |
| sv_SE | 1         | 3.03%   |
| ru_RU | 1         | 3.03%   |
| pt_PT | 1         | 3.03%   |
| hu_HU | 1         | 3.03%   |
| en_GB | 1         | 3.03%   |
| cs_CZ | 1         | 3.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 21        | 63.64%  |
| EFI  | 12        | 36.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 24        | 72.73%  |
| Ext4  | 8         | 24.24%  |
| Xfs   | 1         | 3.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 17        | 51.52%  |
| GPT     | 14        | 42.42%  |
| MBR     | 2         | 6.06%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 32        | 96.97%  |
| Yes       | 1         | 3.03%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 23        | 69.7%   |
| Yes       | 10        | 30.3%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 9         | 27.27%  |
| Hewlett-Packard     | 6         | 18.18%  |
| Dell                | 5         | 15.15%  |
| Acer                | 3         | 9.09%   |
| Sony                | 2         | 6.06%   |
| MSI                 | 2         | 6.06%   |
| ASUSTek Computer    | 2         | 6.06%   |
| TUXEDO              | 1         | 3.03%   |
| Samsung Electronics | 1         | 3.03%   |
| Medion              | 1         | 3.03%   |
| Fujitsu             | 1         | 3.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| TUXEDO Aura 15 Gen1                         | 1         | 3.03%   |
| Sony VPCSB15GB                              | 1         | 3.03%   |
| Sony VGN-Z570AN                             | 1         | 3.03%   |
| Samsung 600B4B/600B5B                       | 1         | 3.03%   |
| MSI GS60 6QE                                | 1         | 3.03%   |
| MSI GP63 Leopard 8RD                        | 1         | 3.03%   |
| Medion E6436 MD61150                        | 1         | 3.03%   |
| Lenovo V330-15IKB 81AX                      | 1         | 3.03%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW00A7TH  | 1         | 3.03%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB002UMC    | 1         | 3.03%   |
| Lenovo ThinkPad T61 8895W9U                 | 1         | 3.03%   |
| Lenovo ThinkPad T490s 20NYS1XK00            | 1         | 3.03%   |
| Lenovo ThinkPad T460 20FMS75800             | 1         | 3.03%   |
| Lenovo ThinkPad T450s 20BWA06J00            | 1         | 3.03%   |
| Lenovo ThinkPad L15 Gen 1 20U4S88000        | 1         | 3.03%   |
| Lenovo G500 20236                           | 1         | 3.03%   |
| HP ZBook 17 G2                              | 1         | 3.03%   |
| HP Stream Notebook PC 11                    | 1         | 3.03%   |
| HP Pavilion dx6500                          | 1         | 3.03%   |
| HP OMEN by HP Laptop 15-dc1xxx              | 1         | 3.03%   |
| HP Laptop 17-ca1xxx                         | 1         | 3.03%   |
| HP Laptop 15s-eq0xxx                        | 1         | 3.03%   |
| Fujitsu LIFEBOOK E754                       | 1         | 3.03%   |
| Dell Precision M6700                        | 1         | 3.03%   |
| Dell Latitude 5480                          | 1         | 3.03%   |
| Dell Inspiron 7460                          | 1         | 3.03%   |
| Dell Inspiron 3521                          | 1         | 3.03%   |
| Dell Inspiron 15 7000 Gaming                | 1         | 3.03%   |
| ASUS VivoBook 12_ASUS Laptop E203MAS_E203MA | 1         | 3.03%   |
| ASUS G771JW                                 | 1         | 3.03%   |
| Acer Nitro AN515-54                         | 1         | 3.03%   |
| Acer Aspire E1-772G                         | 1         | 3.03%   |
| Acer Aspire 5560                            | 1         | 3.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 7         | 21.21%  |
| Dell Inspiron     | 3         | 9.09%   |
| HP Laptop         | 2         | 6.06%   |
| Acer Aspire       | 2         | 6.06%   |
| TUXEDO Aura       | 1         | 3.03%   |
| Sony VPCSB15GB    | 1         | 3.03%   |
| Sony VGN-Z570AN   | 1         | 3.03%   |
| Samsung 600B4B    | 1         | 3.03%   |
| MSI GS60          | 1         | 3.03%   |
| MSI GP63          | 1         | 3.03%   |
| Medion E6436      | 1         | 3.03%   |
| Lenovo V330-15IKB | 1         | 3.03%   |
| Lenovo G500       | 1         | 3.03%   |
| HP ZBook          | 1         | 3.03%   |
| HP Stream         | 1         | 3.03%   |
| HP Pavilion       | 1         | 3.03%   |
| HP OMEN           | 1         | 3.03%   |
| Fujitsu LIFEBOOK  | 1         | 3.03%   |
| Dell Precision    | 1         | 3.03%   |
| Dell Latitude     | 1         | 3.03%   |
| ASUS VivoBook     | 1         | 3.03%   |
| ASUS G771JW       | 1         | 3.03%   |
| Acer Nitro        | 1         | 3.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 7         | 21.21%  |
| 2020 | 6         | 18.18%  |
| 2018 | 5         | 15.15%  |
| 2019 | 3         | 9.09%   |
| 2014 | 2         | 6.06%   |
| 2013 | 2         | 6.06%   |
| 2011 | 2         | 6.06%   |
| 2017 | 1         | 3.03%   |
| 2016 | 1         | 3.03%   |
| 2015 | 1         | 3.03%   |
| 2012 | 1         | 3.03%   |
| 2009 | 1         | 3.03%   |
| 2007 | 1         | 3.03%   |

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
| Disabled | 28        | 84.85%  |
| Enabled  | 5         | 15.15%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 33        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 9         | 27.27%  |
| 16.01-24.0  | 8         | 24.24%  |
| 3.01-4.0    | 5         | 15.15%  |
| 8.01-16.0   | 5         | 15.15%  |
| 32.01-64.0  | 2         | 6.06%   |
| 1.01-2.0    | 2         | 6.06%   |
| 2.01-3.0    | 1         | 3.03%   |
| 64.01-256.0 | 1         | 3.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 11        | 33.33%  |
| 1.01-2.0  | 10        | 30.3%   |
| 4.01-8.0  | 7         | 21.21%  |
| 3.01-4.0  | 3         | 9.09%   |
| 8.01-16.0 | 1         | 3.03%   |
| 0.51-1.0  | 1         | 3.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 18        | 54.55%  |
| 2      | 15        | 45.45%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 20        | 60.61%  |
| Yes       | 13        | 39.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 90.91%  |
| No        | 3         | 9.09%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 76.47%  |
| No        | 8         | 23.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 6         | 18.18%  |
| Brazil      | 3         | 9.09%   |
| USA         | 2         | 6.06%   |
| Spain       | 2         | 6.06%   |
| Nicaragua   | 2         | 6.06%   |
| India       | 2         | 6.06%   |
| France      | 2         | 6.06%   |
| Czechia     | 2         | 6.06%   |
| Thailand    | 1         | 3.03%   |
| Sweden      | 1         | 3.03%   |
| Sudan       | 1         | 3.03%   |
| Russia      | 1         | 3.03%   |
| Romania     | 1         | 3.03%   |
| Portugal    | 1         | 3.03%   |
| Netherlands | 1         | 3.03%   |
| Mexico      | 1         | 3.03%   |
| Hungary     | 1         | 3.03%   |
| Greece      | 1         | 3.03%   |
| China       | 1         | 3.03%   |
| Canada      | 1         | 3.03%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City       | Notebooks | Percent |
|------------|-----------|---------|
| São Paulo | 2         | 5.88%   |
| Prague     | 2         | 5.88%   |
| Managua    | 2         | 5.88%   |
| Zhuhai     | 1         | 2.94%   |
| Umeå      | 1         | 2.94%   |
| The Hague  | 1         | 2.94%   |
| S??o Paulo | 1         | 2.94%   |
| Rockville  | 1         | 2.94%   |
| Pringy     | 1         | 2.94%   |
| Palanpur   | 1         | 2.94%   |
| Nuremberg  | 1         | 2.94%   |
| Nevez      | 1         | 2.94%   |
| Moscow     | 1         | 2.94%   |
| Monterrey  | 1         | 2.94%   |
| Leiria     | 1         | 2.94%   |
| Le??n      | 1         | 2.94%   |
| Khartoum   | 1         | 2.94%   |
| Kathu      | 1         | 2.94%   |
| Isernhagen | 1         | 2.94%   |
| Howick     | 1         | 2.94%   |
| Gevelsberg | 1         | 2.94%   |
| Esztergom  | 1         | 2.94%   |
| Dahme      | 1         | 2.94%   |
| Concarneau | 1         | 2.94%   |
| Cologne    | 1         | 2.94%   |
| Bucharest  | 1         | 2.94%   |
| Bremen     | 1         | 2.94%   |
| Bilbao     | 1         | 2.94%   |
| Bengaluru  | 1         | 2.94%   |
| Atlanta    | 1         | 2.94%   |
| Athens     | 1         | 2.94%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 8      | 16.67%  |
| WDC                 | 6         | 6      | 12.5%   |
| Kingston            | 6         | 6      | 12.5%   |
| Seagate             | 5         | 5      | 10.42%  |
| SanDisk             | 4         | 4      | 8.33%   |
| Hitachi             | 3         | 4      | 6.25%   |
| HGST                | 3         | 3      | 6.25%   |
| Unknown             | 2         | 2      | 4.17%   |
| Toshiba             | 2         | 3      | 4.17%   |
| SK Hynix            | 2         | 2      | 4.17%   |
| Silicon Motion      | 2         | 2      | 4.17%   |
| PLEXTOR             | 1         | 2      | 2.08%   |
| Micron Technology   | 1         | 1      | 2.08%   |
| LITEON              | 1         | 1      | 2.08%   |
| Intenso             | 1         | 1      | 2.08%   |
| Fujitsu             | 1         | 1      | 2.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Silicon Motion NVMe SSD Drive 512GB     | 2         | 4.17%   |
| Seagate ST1000LM035-1RK172 1TB          | 2         | 4.17%   |
| HGST HTS721010A9E630 1TB                | 2         | 4.17%   |
| WDC WDS480G2G0A-00JH30 480GB SSD        | 1         | 2.08%   |
| WDC WD800BEVS-60RST0 80GB               | 1         | 2.08%   |
| WDC WD5000LPLX-66ZNTT1 500GB            | 1         | 2.08%   |
| WDC WD10SPZX-60Z10T0 1TB                | 1         | 2.08%   |
| WDC WD10SPZX-17Z10T0 1TB                | 1         | 2.08%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB    | 1         | 2.08%   |
| Unknown USD00  256GB                    | 1         | 2.08%   |
| Unknown DA4064  64GB                    | 1         | 2.08%   |
| Toshiba THNSNJ256G8NU 256GB SSD         | 1         | 2.08%   |
| Toshiba MQ01ABD075 752GB                | 1         | 2.08%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD   | 1         | 2.08%   |
| SK Hynix HBG4e  32GB                    | 1         | 2.08%   |
| Seagate ST9320325AS 320GB               | 1         | 2.08%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 1         | 2.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 2.08%   |
| SanDisk SSD PLUS 1000GB                 | 1         | 2.08%   |
| SanDisk SDSSDH3 1T00 1TB                | 1         | 2.08%   |
| SanDisk SD9SN8W256G 256GB SSD           | 1         | 2.08%   |
| SanDisk SD8TB8U512G1001 512GB SSD       | 1         | 2.08%   |
| Samsung SSD 970 EVO 1TB                 | 1         | 2.08%   |
| Samsung SSD 860 EVO 1TB                 | 1         | 2.08%   |
| Samsung SSD 850 EVO 250GB               | 1         | 2.08%   |
| Samsung NVMe SSD Drive 1TB              | 1         | 2.08%   |
| Samsung MZVLB512HAJQ-000H1 512GB        | 1         | 2.08%   |
| Samsung MZVL21T0HCLR-00BL7 1TB          | 1         | 2.08%   |
| Samsung MZALQ256HAJD-000L1 256GB        | 1         | 2.08%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD    | 1         | 2.08%   |
| PLEXTOR PX-512M5Pro 512GB SSD           | 1         | 2.08%   |
| Micron NVMe SSD Drive 512GB             | 1         | 2.08%   |
| LITEON CX1-JB256-HP 256GB SSD           | 1         | 2.08%   |
| Kingston SNA-DC/U3 512GB SSD            | 1         | 2.08%   |
| Kingston SM2280S3G2480G 480GB SSD       | 1         | 2.08%   |
| Kingston SA400S37240G 240GB SSD         | 1         | 2.08%   |
| Kingston SA2000M81000G 1TB              | 1         | 2.08%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 1         | 2.08%   |
| Kingston RBU-SC100S37128GD 128GB SSD    | 1         | 2.08%   |
| Intenso SSD 512GB                       | 1         | 2.08%   |
| Hitachi HTS727550A9E365 500GB           | 1         | 2.08%   |
| Hitachi HTS547575A9E384 752GB           | 1         | 2.08%   |
| Hitachi HTS542525K9SA00 250GB           | 1         | 2.08%   |
| HGST HTS541010A9E680 1TB                | 1         | 2.08%   |
| Fujitsu MHW2120BH 120GB                 | 1         | 2.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 29.41%  |
| WDC     | 4         | 4      | 23.53%  |
| Hitachi | 3         | 4      | 17.65%  |
| HGST    | 3         | 3      | 17.65%  |
| Toshiba | 1         | 2      | 5.88%   |
| Fujitsu | 1         | 1      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 5         | 5      | 27.78%  |
| SanDisk             | 4         | 4      | 22.22%  |
| Samsung Electronics | 3         | 3      | 16.67%  |
| WDC                 | 1         | 1      | 5.56%   |
| Toshiba             | 1         | 1      | 5.56%   |
| SK Hynix            | 1         | 1      | 5.56%   |
| PLEXTOR             | 1         | 2      | 5.56%   |
| LITEON              | 1         | 1      | 5.56%   |
| Intenso             | 1         | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 17        | 19     | 37.78%  |
| HDD  | 15        | 19     | 33.33%  |
| NVMe | 10        | 10     | 22.22%  |
| MMC  | 3         | 3      | 6.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 25        | 37     | 64.1%   |
| NVMe | 10        | 10     | 25.64%  |
| MMC  | 3         | 3      | 7.69%   |
| SAS  | 1         | 1      | 2.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 17        | 19     | 53.13%  |
| 0.01-0.5   | 15        | 19     | 46.88%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1001-2000      | 8         | 24.24%  |
| 501-1000       | 7         | 21.21%  |
| More than 3000 | 6         | 18.18%  |
| 2001-3000      | 5         | 15.15%  |
| 251-500        | 4         | 12.12%  |
| 51-100         | 3         | 9.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 51-100    | 10        | 29.41%  |
| 101-250   | 6         | 17.65%  |
| 251-500   | 5         | 14.71%  |
| 501-1000  | 5         | 14.71%  |
| 1-20      | 3         | 8.82%   |
| 21-50     | 2         | 5.88%   |
| 1001-2000 | 2         | 5.88%   |
| 2001-3000 | 1         | 2.94%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 50%     |
| Samsung Electronics SSD 970 EVO 1TB | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1         | 1      | 50%     |
| HDD  | 1         | 1      | 50%     |

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
| Detected | 20        | 32     | 57.14%  |
| Works    | 13        | 17     | 37.14%  |
| Malfunc  | 2         | 2      | 5.71%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 24        | 64.86%  |
| Samsung Electronics         | 5         | 13.51%  |
| Silicon Motion              | 2         | 5.41%   |
| AMD                         | 2         | 5.41%   |
| Sandisk                     | 1         | 2.7%    |
| Micron Technology           | 1         | 2.7%    |
| Lite-On Technology          | 1         | 2.7%    |
| Kingston Technology Company | 1         | 2.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 12.82%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 10.26%  |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 5.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 5.13%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 5.13%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 5.13%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 5.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 5.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 5.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 5.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 5.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 5.13%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 5.13%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 2.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 2.56%   |
| Micron Non-Volatile memory controller                                          | 1         | 2.56%   |
| Lite-On SATA controller                                                        | 1         | 2.56%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 2.56%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 2.56%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 2.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 2.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 24        | 63.16%  |
| NVMe | 10        | 26.32%  |
| RAID | 2         | 5.26%   |
| IDE  | 2         | 5.26%   |

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
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 6.06%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 6.06%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 3.03%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 3.03%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 3.03%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 3.03%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 3.03%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 3.03%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 3.03%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 3.03%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 3.03%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 3.03%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 3.03%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 1         | 3.03%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 3.03%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 3.03%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 3.03%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 3.03%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 3.03%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 3.03%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 3.03%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 1         | 3.03%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz          | 1         | 3.03%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 1         | 3.03%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 3.03%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 3.03%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 3.03%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 3.03%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 3.03%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 1         | 3.03%   |
| AMD A6-3420M APU with Radeon HD Graphics      | 1         | 3.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 11        | 33.33%  |
| Intel Core i5    | 10        | 30.3%   |
| Intel Core 2 Duo | 3         | 9.09%   |
| Intel Core i3    | 2         | 6.06%   |
| Intel Celeron    | 2         | 6.06%   |
| Other            | 1         | 3.03%   |
| AMD Ryzen 7      | 1         | 3.03%   |
| AMD Ryzen 5      | 1         | 3.03%   |
| AMD Ryzen 3      | 1         | 3.03%   |
| AMD A6           | 1         | 3.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 18        | 54.55%  |
| 4      | 11        | 33.33%  |
| 6      | 3         | 9.09%   |
| 8      | 1         | 3.03%   |

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
| 2      | 25        | 75.76%  |
| 1      | 8         | 24.24%  |

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
| Unknown    | 14        | 42.42%  |
| 0x906ea    | 2         | 6.06%   |
| 0x806e9    | 2         | 6.06%   |
| 0x6fd      | 2         | 6.06%   |
| 0x406e3    | 2         | 6.06%   |
| 0x806ec    | 1         | 3.03%   |
| 0x806c1    | 1         | 3.03%   |
| 0x706a1    | 1         | 3.03%   |
| 0x506e3    | 1         | 3.03%   |
| 0x306d4    | 1         | 3.03%   |
| 0x306a9    | 1         | 3.03%   |
| 0x30678    | 1         | 3.03%   |
| 0x206a7    | 1         | 3.03%   |
| 0x10676    | 1         | 3.03%   |
| 0x08600106 | 1         | 3.03%   |
| 0x08108109 | 1         | 3.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 10        | 30.3%   |
| Haswell       | 4         | 12.12%  |
| Skylake       | 3         | 9.09%   |
| IvyBridge     | 3         | 9.09%   |
| Zen+          | 2         | 6.06%   |
| SandyBridge   | 2         | 6.06%   |
| Core          | 2         | 6.06%   |
| Zen 2         | 1         | 3.03%   |
| TigerLake     | 1         | 3.03%   |
| Silvermont    | 1         | 3.03%   |
| Penryn        | 1         | 3.03%   |
| K10 Llano     | 1         | 3.03%   |
| Goldmont plus | 1         | 3.03%   |
| Broadwell     | 1         | 3.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 29        | 61.7%   |
| Nvidia | 11        | 23.4%   |
| AMD    | 7         | 14.89%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 4         | 8.16%   |
| Intel HD Graphics 620                                                     | 3         | 6.12%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 3         | 6.12%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 3         | 6.12%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 2         | 4.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 4.08%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 2         | 4.08%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 2         | 4.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 4.08%   |
| AMD Picasso                                                               | 2         | 4.08%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 2.04%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                               | 1         | 2.04%   |
| Nvidia GM204M [GeForce GTX 980M]                                          | 1         | 2.04%   |
| Nvidia GM204M [GeForce GTX 970M]                                          | 1         | 2.04%   |
| Nvidia GM108M [GeForce 940MX]                                             | 1         | 2.04%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 2.04%   |
| Nvidia GK104GLM [Quadro K3000M]                                           | 1         | 2.04%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 2.04%   |
| Nvidia G98M [GeForce 9300M GS]                                            | 1         | 2.04%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 2.04%   |
| Intel UHD Graphics 620                                                    | 1         | 2.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 1         | 2.04%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 2.04%   |
| Intel HD Graphics 630                                                     | 1         | 2.04%   |
| Intel HD Graphics 5500                                                    | 1         | 2.04%   |
| Intel HD Graphics 530                                                     | 1         | 2.04%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 2.04%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 2.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1         | 2.04%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                 | 1         | 2.04%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                       | 1         | 2.04%   |
| AMD Sumo [Radeon HD 6520G]                                                | 1         | 2.04%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 1         | 2.04%   |
| AMD Renoir                                                                | 1         | 2.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 16        | 48.48%  |
| Intel + Nvidia | 10        | 30.3%   |
| 1 x AMD        | 4         | 12.12%  |
| Intel + AMD    | 3         | 9.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 29        | 87.88%  |
| Proprietary | 4         | 12.12%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 81.82%  |
| 0.01-0.5   | 2         | 6.06%   |
| 7.01-8.0   | 1         | 3.03%   |
| 3.01-4.0   | 1         | 3.03%   |
| 1.01-2.0   | 1         | 3.03%   |
| 0.51-1.0   | 1         | 3.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 10        | 25%     |
| Chimei Innolux      | 9         | 22.5%   |
| AU Optronics        | 6         | 15%     |
| Samsung Electronics | 3         | 7.5%    |
| Goldstar            | 3         | 7.5%    |
| Lenovo              | 2         | 5%      |
| Hewlett-Packard     | 2         | 5%      |
| Sony                | 1         | 2.5%    |
| LG Philips          | 1         | 2.5%    |
| InfoVision          | 1         | 2.5%    |
| Dell                | 1         | 2.5%    |
| CSO                 | 1         | 2.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Hewlett-Packard LV1911 HWP3005 1366x768 410x230mm 18.5-inch           | 2         | 5%      |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch  | 1         | 2.5%    |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1         | 2.5%    |
| Samsung Electronics LCD Monitor SEC3449 1366x768 309x174mm 14.0-inch  | 1         | 2.5%    |
| Samsung Electronics LCD Monitor SDC424B 3840x2160 344x194mm 15.5-inch | 1         | 2.5%    |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch           | 1         | 2.5%    |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch          | 1         | 2.5%    |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch          | 1         | 2.5%    |
| LG Display LCD Monitor LGD053C 1920x1080 309x174mm 14.0-inch          | 1         | 2.5%    |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 1         | 2.5%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 2.5%    |
| LG Display LCD Monitor LGD04A9 1920x1080 309x174mm 14.0-inch          | 1         | 2.5%    |
| LG Display LCD Monitor LGD046C 1920x1080 380x210mm 17.1-inch          | 1         | 2.5%    |
| LG Display LCD Monitor LGD044F 1920x1080 350x190mm 15.7-inch          | 1         | 2.5%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 1         | 2.5%    |
| LG Display LCD Monitor LGD02DA 1920x1080 380x220mm 17.3-inch          | 1         | 2.5%    |
| Lenovo LEN P27q-10 LEN61A8 2560x1440 597x336mm 27.0-inch              | 1         | 2.5%    |
| Lenovo LCD Monitor LEN4020 1024x768 286x214mm 14.1-inch               | 1         | 2.5%    |
| InfoVision LCD Monitor IVO03F4 1920x1200 263x164mm 12.2-inch          | 1         | 2.5%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 1         | 2.5%    |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 1         | 2.5%    |
| Goldstar 2D FHD LG TV GSM59C6 1920x1080 509x286mm 23.0-inch           | 1         | 2.5%    |
| Dell U2410 DELF017 1920x1200 518x324mm 24.1-inch                      | 1         | 2.5%    |
| CSO LCD Monitor CSO1404 1920x1200 302x189mm 14.0-inch                 | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN15F6 1920x1080 344x193mm 15.5-inch      | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch      | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch      | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN1136 1366x768 256x144mm 11.6-inch       | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch        | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch        | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO225C 1366x768 256x144mm 11.6-inch         | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch        | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch         | 1         | 2.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 18        | 48.65%  |
| 1366x768 (WXGA)   | 8         | 21.62%  |
| 1920x1200 (WUXGA) | 3         | 8.11%   |
| 3840x2160 (4K)    | 2         | 5.41%   |
| 1600x900 (HD+)    | 2         | 5.41%   |
| 2560x1440 (QHD)   | 1         | 2.7%    |
| 2560x1080         | 1         | 2.7%    |
| 1280x800 (WXGA)   | 1         | 2.7%    |
| 1024x768 (XGA)    | 1         | 2.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 15        | 37.5%   |
| 14     | 7         | 17.5%   |
| 17     | 6         | 15%     |
| 27     | 2         | 5%      |
| 18     | 2         | 5%      |
| 13     | 2         | 5%      |
| 11     | 2         | 5%      |
| 34     | 1         | 2.5%    |
| 26     | 1         | 2.5%    |
| 23     | 1         | 2.5%    |
| 21     | 1         | 2.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 23        | 57.5%   |
| 351-400     | 6         | 15%     |
| 501-600     | 3         | 7.5%    |
| 401-500     | 3         | 7.5%    |
| 201-300     | 3         | 7.5%    |
| 701-800     | 1         | 2.5%    |
| 601-700     | 1         | 2.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 30        | 85.71%  |
| 16/10 | 3         | 8.57%   |
| 4/3   | 1         | 2.86%   |
| 21/9  | 1         | 2.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 15        | 37.5%   |
| 81-90          | 8         | 20%     |
| 121-130        | 6         | 15%     |
| 301-350        | 3         | 7.5%    |
| 51-60          | 2         | 5%      |
| 201-250        | 2         | 5%      |
| 141-150        | 2         | 5%      |
| 351-500        | 1         | 2.5%    |
| 91-100         | 1         | 2.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 20        | 51.28%  |
| 101-120       | 10        | 25.64%  |
| 51-100        | 7         | 17.95%  |
| More than 240 | 1         | 2.56%   |
| 161-240       | 1         | 2.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 25        | 75.76%  |
| 2     | 8         | 24.24%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 24        | 45.28%  |
| Realtek Semiconductor | 15        | 28.3%   |
| Qualcomm Atheros      | 7         | 13.21%  |
| Broadcom Limited      | 2         | 3.77%   |
| Broadcom              | 2         | 3.77%   |
| Samsung Electronics   | 1         | 1.89%   |
| Lenovo                | 1         | 1.89%   |
| ASIX Electronics      | 1         | 1.89%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 15.38%  |
| Intel Wi-Fi 6 AX200                                               | 4         | 6.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 3.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 3.08%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 3.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 3.08%   |
| Intel Wireless 8265 / 8275                                        | 2         | 3.08%   |
| Intel Wireless 8260                                               | 2         | 3.08%   |
| Intel Wireless 7260                                               | 2         | 3.08%   |
| Intel Wireless 3165                                               | 2         | 3.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.08%   |
| Samsung Kiera                                                     | 1         | 1.54%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 1.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.54%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 1.54%   |
| Lenovo OneLink+ Giga                                              | 1         | 1.54%   |
| Intel Wireless 7265                                               | 1         | 1.54%   |
| Intel WiFi Link 5100                                              | 1         | 1.54%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.54%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 1         | 1.54%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 1.54%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1         | 1.54%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.54%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.54%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.54%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.54%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.54%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.54%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.54%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.54%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 1         | 1.54%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 1         | 1.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 1.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 1.54%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.54%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.54%   |
| Broadcom Limited NetLink BCM57785 Gigabit Ethernet PCIe           | 1         | 1.54%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 1.54%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 1         | 1.54%   |
| Broadcom BCM43227 802.11b/g/n                                     | 1         | 1.54%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 66.67%  |
| Qualcomm Atheros      | 5         | 15.15%  |
| Realtek Semiconductor | 4         | 12.12%  |
| Broadcom              | 2         | 6.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 4         | 12.12%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 2         | 6.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 2         | 6.06%   |
| Intel Wireless 8265 / 8275                                    | 2         | 6.06%   |
| Intel Wireless 8260                                           | 2         | 6.06%   |
| Intel Wireless 7260                                           | 2         | 6.06%   |
| Intel Wireless 3165                                           | 2         | 6.06%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 3.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 3.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 1         | 3.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1         | 3.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 1         | 3.03%   |
| Intel Wireless 7265                                           | 1         | 3.03%   |
| Intel WiFi Link 5100                                          | 1         | 3.03%   |
| Intel Wi-Fi 6 AX201                                           | 1         | 3.03%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection | 1         | 3.03%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection         | 1         | 3.03%   |
| Intel Gemini Lake PCH CNVi WiFi                               | 1         | 3.03%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                  | 1         | 3.03%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                 | 1         | 3.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 1         | 3.03%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 1         | 3.03%   |
| Broadcom BCM43228 802.11a/b/g/n                               | 1         | 3.03%   |
| Broadcom BCM43227 802.11b/g/n                                 | 1         | 3.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 12        | 38.71%  |
| Intel                 | 12        | 38.71%  |
| Qualcomm Atheros      | 3         | 9.68%   |
| Broadcom Limited      | 2         | 6.45%   |
| Lenovo                | 1         | 3.23%   |
| ASIX Electronics      | 1         | 3.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 32.26%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 6.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 6.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 6.45%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 3.23%   |
| Lenovo OneLink+ Giga                                              | 1         | 3.23%   |
| Intel Ethernet Connection I219-V                                  | 1         | 3.23%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 3.23%   |
| Intel Ethernet Connection I217-V                                  | 1         | 3.23%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 3.23%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 3.23%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 3.23%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 3.23%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 3.23%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 3.23%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 3.23%   |
| Broadcom Limited NetLink BCM57785 Gigabit Ethernet PCIe           | 1         | 3.23%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 3.23%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 3.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 33        | 51.56%  |
| Ethernet | 30        | 46.88%  |
| Modem    | 1         | 1.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 50.85%  |
| Ethernet | 28        | 47.46%  |
| Modem    | 1         | 1.69%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 29        | 87.88%  |
| 1     | 4         | 12.12%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 24        | 72.73%  |
| Yes  | 9         | 27.27%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 46.15%  |
| Realtek Semiconductor           | 4         | 15.38%  |
| Qualcomm Atheros Communications | 3         | 11.54%  |
| Lite-On Technology              | 1         | 3.85%   |
| IMC Networks                    | 1         | 3.85%   |
| Foxconn / Hon Hai               | 1         | 3.85%   |
| Dell                            | 1         | 3.85%   |
| Cambridge Silicon Radio         | 1         | 3.85%   |
| Broadcom                        | 1         | 3.85%   |
| Alps Electric                   | 1         | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 5         | 19.23%  |
| Intel AX200 Bluetooth                                                               | 3         | 11.54%  |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 7.69%   |
| Realtek Bluetooth Radio                                                             | 2         | 7.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 2         | 7.69%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 1         | 3.85%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 3.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 3.85%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 3.85%   |
| Intel Bluetooth Device                                                              | 1         | 3.85%   |
| Intel AX201 Bluetooth                                                               | 1         | 3.85%   |
| IMC Networks Bluetooth Device                                                       | 1         | 3.85%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 3.85%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 3.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 3.85%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 3.85%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Intel     | 29        | 70.73%  |
| AMD       | 4         | 9.76%   |
| Nvidia    | 3         | 7.32%   |
| Logitech  | 2         | 4.88%   |
| Lenovo    | 1         | 2.44%   |
| JMTek     | 1         | 2.44%   |
| GN Netcom | 1         | 2.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 6         | 12.24%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 8.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 6.12%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 6.12%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 6.12%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 3         | 6.12%   |
| Logitech Headset H390                                                      | 2         | 4.08%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 4.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 4.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 4.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 2.04%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 2.04%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 2.04%   |
| Lenovo ThinkPad OneLink Plus Dock Audio                                    | 1         | 2.04%   |
| JMTek audio controller                                                     | 1         | 2.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 2.04%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 2.04%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 2.04%   |
| Intel CM238 HD Audio Controller                                            | 1         | 2.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 2.04%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 2.04%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 2.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 2.04%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 2.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 2.04%   |
| GN Netcom Jabra UC VOICE 150a MS                                           | 1         | 2.04%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 2.04%   |
| AMD FCH Azalia Controller                                                  | 1         | 2.04%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1         | 2.04%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 40%     |
| Unknown             | 4         | 20%     |
| SK Hynix            | 4         | 20%     |
| Micron Technology   | 1         | 5%      |
| Kingston            | 1         | 5%      |
| Corsair             | 1         | 5%      |
| A-DATA Technology   | 1         | 5%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                     | 1         | 4.17%   |
| Unknown RAM Module 4096MB SODIMM DDR3                          | 1         | 4.17%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 4.17%   |
| Unknown RAM Module 2048MB SODIMM 1067MT/s                      | 1         | 4.17%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                     | 1         | 4.17%   |
| Unknown RAM Module 1024MB SODIMM 1067MT/s                      | 1         | 4.17%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                   | 1         | 4.17%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s         | 1         | 4.17%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s      | 1         | 4.17%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s      | 1         | 4.17%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s      | 1         | 4.17%   |
| Samsung RAM M471B5673EH1-CH9 2GB SODIMM DDR3 1334MT/s          | 1         | 4.17%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s       | 1         | 4.17%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 1         | 4.17%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s         | 1         | 4.17%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s         | 1         | 4.17%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 4.17%   |
| Samsung RAM K4F6E3S4HM-MGCJ 4096MB SODIMM LPDDR4 3733MT/s      | 1         | 4.17%   |
| Samsung RAM K4E6E304EE-EGCF 4GB SODIMM LPDDR3 1867MT/s         | 1         | 4.17%   |
| Samsung RAM K4E6E304EE-EGCF 4GB Chip LPDDR3 1867MT/s           | 1         | 4.17%   |
| Micron RAM 53E1G32D2NP-046 2048MB Row Of Chips LPDDR4 4267MT/s | 1         | 4.17%   |
| Kingston RAM MSI26D4S9S8ME-8 8192MB SODIMM DDR4 2667MT/s       | 1         | 4.17%   |
| Corsair RAM CMSX8GX4M1A2400C16 8GB SODIMM DDR4 2400MT/s        | 1         | 4.17%   |
| A-DATA RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 1         | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 8         | 42.11%  |
| DDR3    | 5         | 26.32%  |
| LPDDR4  | 2         | 10.53%  |
| DDR2    | 2         | 10.53%  |
| LPDDR3  | 1         | 5.26%   |
| Unknown | 1         | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 18        | 90%     |
| Row Of Chips | 1         | 5%      |
| Chip         | 1         | 5%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 8         | 34.78%  |
| 4096  | 7         | 30.43%  |
| 2048  | 4         | 17.39%  |
| 1024  | 2         | 8.7%    |
| 32768 | 1         | 4.35%   |
| 16384 | 1         | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 5         | 25%     |
| 1600    | 3         | 15%     |
| 3200    | 2         | 10%     |
| 667     | 2         | 10%     |
| 4267    | 1         | 5%      |
| 3733    | 1         | 5%      |
| 2400    | 1         | 5%      |
| 2133    | 1         | 5%      |
| 1867    | 1         | 5%      |
| 1334    | 1         | 5%      |
| 1067    | 1         | 5%      |
| Unknown | 1         | 5%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Prolific Technology | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 1         | 100%    |

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
| Chicony Electronics                    | 5         | 16.67%  |
| Acer                                   | 5         | 16.67%  |
| Sunplus Innovation Technology          | 3         | 10%     |
| Realtek Semiconductor                  | 3         | 10%     |
| Quanta                                 | 3         | 10%     |
| IMC Networks                           | 3         | 10%     |
| Cheng Uei Precision Industry (Foxlink) | 2         | 6.67%   |
| Syntek                                 | 1         | 3.33%   |
| Silicon Motion                         | 1         | 3.33%   |
| Ricoh                                  | 1         | 3.33%   |
| Microdia                               | 1         | 3.33%   |
| Luxvisions Innotech Limited            | 1         | 3.33%   |
| Lite-On Technology                     | 1         | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                | 3         | 9.68%   |
| Syntek Lenovo EasyCamera                                                 | 1         | 3.23%   |
| Sunplus Integrated_Webcam_HD                                             | 1         | 3.23%   |
| Sunplus HD WebCam                                                        | 1         | 3.23%   |
| Sunplus 1.3M HD WebCam                                                   | 1         | 3.23%   |
| Silicon Motion WebCam SC-13HDN10939N                                     | 1         | 3.23%   |
| Ricoh Sony Vaio Integrated Webcam                                        | 1         | 3.23%   |
| Realtek USB2.0 HD UVC WebCam                                             | 1         | 3.23%   |
| Realtek USB Camera                                                       | 1         | 3.23%   |
| Realtek Integrated_Webcam_HD                                             | 1         | 3.23%   |
| Realtek Integrated Webcam HD                                             | 1         | 3.23%   |
| Quanta HP Wide Vision HD Camera                                          | 1         | 3.23%   |
| Quanta HP TrueVision HD Camera                                           | 1         | 3.23%   |
| Quanta HD User Facing                                                    | 1         | 3.23%   |
| Microdia Integrated_Webcam_HD                                            | 1         | 3.23%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                      | 1         | 3.23%   |
| Lite-On Integrated Camera                                                | 1         | 3.23%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 1         | 3.23%   |
| IMC Networks USB2.0 UVC HD Webcam                                        | 1         | 3.23%   |
| IMC Networks Integrated Camera                                           | 1         | 3.23%   |
| Chicony VGA 24fps UVC Webcam                                             | 1         | 3.23%   |
| Chicony USB2.0 Camera                                                    | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                            | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 3.23%   |
| Acer ThinkPad P50 Integrated Camera                                      | 1         | 3.23%   |
| Acer Integrated Camera                                                   | 1         | 3.23%   |
| Acer HD Webcam                                                           | 1         | 3.23%   |
| Acer BisonCam,NB Pro                                                     | 1         | 3.23%   |
| Acer BisonCam, NB Pro                                                    | 1         | 3.23%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 4         | 44.44%  |
| Synaptics        | 3         | 33.33%  |
| Upek             | 1         | 11.11%  |
| AuthenTec        | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 22.22%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 11.11%  |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 11.11%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 11.11%  |
| Synaptics  WBDI                                        | 1         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 11.11%  |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 11.11%  |
| Unknown                                                | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 2         | 40%     |
| O2 Micro              | 1         | 20%     |
| Gemalto (was Gemplus) | 1         | 20%     |
| Broadcom              | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader               | 2         | 40%     |
| O2 Micro OZ776 CCID Smartcard Reader              | 1         | 20%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor    | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 18        | 54.55%  |
| 1     | 12        | 36.36%  |
| 2     | 3         | 9.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 9         | 47.37%  |
| Chipcard           | 6         | 31.58%  |
| Graphics card      | 2         | 10.53%  |
| Net/wireless       | 1         | 5.26%   |
| Camera             | 1         | 5.26%   |

