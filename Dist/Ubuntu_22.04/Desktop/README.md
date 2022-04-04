Ubuntu 22.04 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

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

Total: 44

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Packard Be... | IMEDIA S2110A               | [b8bf871708](https://linux-hardware.org/?probe=b8bf871708) | Apr 04, 2022 |
| Gigabyte      | B365 M AORUS ELITE-CF       | [7da8a936ea](https://linux-hardware.org/?probe=7da8a936ea) | Apr 04, 2022 |
| Gigabyte      | Z690 UD AX                  | [a052a5e936](https://linux-hardware.org/?probe=a052a5e936) | Apr 03, 2022 |
| Unknown       | Unknown                     | [ec51dcaf0a](https://linux-hardware.org/?probe=ec51dcaf0a) | Apr 03, 2022 |
| MSI           | MAG B660M MORTAR DDR4       | [a9f2820894](https://linux-hardware.org/?probe=a9f2820894) | Apr 02, 2022 |
| Dell          | 07PR60 A00                  | [40f34fbc8f](https://linux-hardware.org/?probe=40f34fbc8f) | Apr 01, 2022 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [f0fdc95810](https://linux-hardware.org/?probe=f0fdc95810) | Apr 01, 2022 |
| HP            | ProLiant ML110 G7           | [9e1e2b2ae7](https://linux-hardware.org/?probe=9e1e2b2ae7) | Apr 01, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | [ce2e9f743d](https://linux-hardware.org/?probe=ce2e9f743d) | Mar 31, 2022 |
| Dell          | 0YNVJG A01                  | [4ccce61117](https://linux-hardware.org/?probe=4ccce61117) | Mar 30, 2022 |
| MSI           | B450M PRO-M2 MAX            | [f21ef43d0f](https://linux-hardware.org/?probe=f21ef43d0f) | Mar 30, 2022 |
| Le Cube 1     | Unknown                     | [a881cc0397](https://linux-hardware.org/?probe=a881cc0397) | Mar 26, 2022 |
| HP            | 1589                        | [8c1f30bb6f](https://linux-hardware.org/?probe=8c1f30bb6f) | Mar 23, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [f417e6a6ef](https://linux-hardware.org/?probe=f417e6a6ef) | Mar 11, 2022 |
| Unknown       | T3 MRD                      | [256dc440ec](https://linux-hardware.org/?probe=256dc440ec) | Mar 09, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | [1fb25ad2c3](https://linux-hardware.org/?probe=1fb25ad2c3) | Mar 05, 2022 |
| ASUSTek       | M4A87TD/USB3                | [aa80ded615](https://linux-hardware.org/?probe=aa80ded615) | Mar 04, 2022 |
| ASUSTek       | M4A87TD/USB3                | [3e997c5618](https://linux-hardware.org/?probe=3e997c5618) | Mar 03, 2022 |
| Unknown       | T3 MRD                      | [35ab38818d](https://linux-hardware.org/?probe=35ab38818d) | Feb 28, 2022 |
| Unknown       | T3 MRD                      | [01dd9cefa7](https://linux-hardware.org/?probe=01dd9cefa7) | Feb 28, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [18d37562a8](https://linux-hardware.org/?probe=18d37562a8) | Feb 26, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [d8af57f59a](https://linux-hardware.org/?probe=d8af57f59a) | Feb 26, 2022 |
| Gigabyte      | H61M-DS2 DVI                | [90c43679f7](https://linux-hardware.org/?probe=90c43679f7) | Feb 23, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | [fa5ed1f68b](https://linux-hardware.org/?probe=fa5ed1f68b) | Feb 13, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | [e329340668](https://linux-hardware.org/?probe=e329340668) | Feb 11, 2022 |
| Dell          | 0YXT71 A03                  | [19227aa57d](https://linux-hardware.org/?probe=19227aa57d) | Feb 11, 2022 |
| HP            | 212B                        | [fab24340a5](https://linux-hardware.org/?probe=fab24340a5) | Feb 10, 2022 |
| ASRockRack    | X470D4U2/1N1                | [735bc0f806](https://linux-hardware.org/?probe=735bc0f806) | Feb 04, 2022 |
| ASUSTek       | P5P41T/USB3                 | [f45dc3454a](https://linux-hardware.org/?probe=f45dc3454a) | Jan 25, 2022 |
| ASUSTek       | P5P41T/USB3                 | [b69dafbb2b](https://linux-hardware.org/?probe=b69dafbb2b) | Jan 25, 2022 |
| ASUSTek       | P5P41T/USB3                 | [105593cece](https://linux-hardware.org/?probe=105593cece) | Jan 23, 2022 |
| Gigabyte      | GB-BSi7-1165G7              | [ab94ff1199](https://linux-hardware.org/?probe=ab94ff1199) | Jan 20, 2022 |
| MSI           | Z490-A PRO                  | [b2655bbd43](https://linux-hardware.org/?probe=b2655bbd43) | Jan 15, 2022 |
| MSI           | C236A WORKSTATION           | [97795d3ebc](https://linux-hardware.org/?probe=97795d3ebc) | Jan 07, 2022 |
| Intel         | H61                         | [e2b49aa759](https://linux-hardware.org/?probe=e2b49aa759) | Dec 30, 2021 |
| Lenovo        | 3141 NOK                    | [cc90d7c889](https://linux-hardware.org/?probe=cc90d7c889) | Dec 13, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [0db33a5b23](https://linux-hardware.org/?probe=0db33a5b23) | Dec 10, 2021 |
| Huanan        | X99 F8D V2.2                | [dcd5217827](https://linux-hardware.org/?probe=dcd5217827) | Nov 29, 2021 |
| Gigabyte      | M52L-S3                     | [16854f2502](https://linux-hardware.org/?probe=16854f2502) | Nov 29, 2021 |
| Gigabyte      | M52L-S3                     | [e6f3417028](https://linux-hardware.org/?probe=e6f3417028) | Nov 27, 2021 |
| Gigabyte      | EP31-DS3L                   | [c0134f6231](https://linux-hardware.org/?probe=c0134f6231) | Nov 11, 2021 |
| Gigabyte      | EP31-DS3L                   | [4d659bf7e4](https://linux-hardware.org/?probe=4d659bf7e4) | Nov 11, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [36e64b8256](https://linux-hardware.org/?probe=36e64b8256) | Nov 10, 2021 |
| MSI           | MS-7235                     | [bbfa7fb897](https://linux-hardware.org/?probe=bbfa7fb897) | Oct 24, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.15.0-18-generic        | 9        | 26.47%  |
| 5.15.0-23-generic        | 8        | 23.53%  |
| 5.13.0-19-generic        | 7        | 20.59%  |
| 5.15.0-22-generic        | 3        | 8.82%   |
| 5.17.1-051701-generic    | 1        | 2.94%   |
| 5.16.0-051600-generic    | 1        | 2.94%   |
| 5.15.13-051513-generic   | 1        | 2.94%   |
| 5.15.0-25-generic        | 1        | 2.94%   |
| 5.15.0-17-generic        | 1        | 2.94%   |
| 5.15.0-051500rc7-generic | 1        | 2.94%   |
| 5.13.0-20-generic        | 1        | 2.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 22       | 66.67%  |
| 5.13.0  | 8        | 24.24%  |
| 5.17.1  | 1        | 3.03%   |
| 5.16.0  | 1        | 3.03%   |
| 5.15.13 | 1        | 3.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 23       | 69.7%   |
| 5.13    | 8        | 24.24%  |
| 5.17    | 1        | 3.03%   |
| 5.16    | 1        | 3.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 33       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 29       | 87.88%  |
| Unknown         | 2        | 6.06%   |
| X-Cinnamon      | 1        | 3.03%   |
| GNOME Flashback | 1        | 3.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 16       | 48.48%  |
| Wayland | 15       | 45.45%  |
| Tty     | 1        | 3.03%   |
| Unknown | 1        | 3.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM3    | 27       | 81.82%  |
| LightDM | 2        | 6.06%   |
| GDM     | 2        | 6.06%   |
| Unknown | 2        | 6.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 12       | 36.36%  |
| de_DE | 5        | 15.15%  |
| pt_BR | 2        | 6.06%   |
| fr_FR | 2        | 6.06%   |
| cs_CZ | 2        | 6.06%   |
| zh_TW | 1        | 3.03%   |
| zh_CN | 1        | 3.03%   |
| th_TH | 1        | 3.03%   |
| ru_RU | 1        | 3.03%   |
| ro_RO | 1        | 3.03%   |
| pl_PL | 1        | 3.03%   |
| it_IT | 1        | 3.03%   |
| es_ES | 1        | 3.03%   |
| en_IN | 1        | 3.03%   |
| en_GB | 1        | 3.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 19       | 57.58%  |
| EFI  | 14       | 42.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 30       | 88.24%  |
| Xfs   | 2        | 5.88%   |
| Zfs   | 1        | 2.94%   |
| Btrfs | 1        | 2.94%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 22       | 66.67%  |
| GPT     | 11       | 33.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 60.61%  |
| Yes       | 13       | 39.39%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 18       | 54.55%  |
| No        | 15       | 45.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 8        | 24.24%  |
| MSI                 | 6        | 18.18%  |
| ASUSTek Computer    | 4        | 12.12%  |
| Hewlett-Packard     | 3        | 9.09%   |
| Dell                | 3        | 9.09%   |
| Packard Bell        | 1        | 3.03%   |
| Lenovo              | 1        | 3.03%   |
| Le Cube 1           | 1        | 3.03%   |
| Intel               | 1        | 3.03%   |
| Huanan              | 1        | 3.03%   |
| Fujitsu             | 1        | 3.03%   |
| ASRockRack          | 1        | 3.03%   |
| ASRock              | 1        | 3.03%   |
| Unknown             | 1        | 3.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Unknown                           | 2        | 6.06%   |
| Packard Bell IMEDIA S2110         | 1        | 3.03%   |
| MSI MS-7D42                       | 1        | 3.03%   |
| MSI MS-7C75                       | 1        | 3.03%   |
| MSI MS-7B84                       | 1        | 3.03%   |
| MSI MS-7A32                       | 1        | 3.03%   |
| MSI MS-7998                       | 1        | 3.03%   |
| MSI MS-7235                       | 1        | 3.03%   |
| Lenovo QiTianM520-D164 90K7S03T00 | 1        | 3.03%   |
| Intel H61                         | 1        | 3.03%   |
| Huanan X99 F8D V2.2               | 1        | 3.03%   |
| HP Z440 Workstation               | 1        | 3.03%   |
| HP Z420 Workstation               | 1        | 3.03%   |
| HP ProLiant ML110 G7              | 1        | 3.03%   |
| Gigabyte Z690 UD AX               | 1        | 3.03%   |
| Gigabyte X570S AORUS PRO AX       | 1        | 3.03%   |
| Gigabyte X570 I AORUS PRO WIFI    | 1        | 3.03%   |
| Gigabyte M52L-S3                  | 1        | 3.03%   |
| Gigabyte H61M-DS2 DVI             | 1        | 3.03%   |
| Gigabyte GB-BSi7-1165G7           | 1        | 3.03%   |
| Gigabyte EP31-DS3L                | 1        | 3.03%   |
| Gigabyte B365 M AORUS ELITE       | 1        | 3.03%   |
| Fujitsu ESPRIMO Q520              | 1        | 3.03%   |
| Dell OptiPlex 7070                | 1        | 3.03%   |
| Dell OptiPlex 7010                | 1        | 3.03%   |
| Dell Inspiron 5675                | 1        | 3.03%   |
| ASUS ROG STRIX B350-F GAMING      | 1        | 3.03%   |
| ASUS P5P41T/USB3                  | 1        | 3.03%   |
| ASUS M4A87TD/USB3                 | 1        | 3.03%   |
| ASUS K30AD_M31AD_M51AD            | 1        | 3.03%   |
| ASRockRack 520004                 | 1        | 3.03%   |
| ASRock 970 Extreme3 R2.0          | 1        | 3.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 2        | 6.06%   |
| Unknown                 | 2        | 6.06%   |
| Packard Bell IMEDIA     | 1        | 3.03%   |
| MSI MS-7D42             | 1        | 3.03%   |
| MSI MS-7C75             | 1        | 3.03%   |
| MSI MS-7B84             | 1        | 3.03%   |
| MSI MS-7A32             | 1        | 3.03%   |
| MSI MS-7998             | 1        | 3.03%   |
| MSI MS-7235             | 1        | 3.03%   |
| Lenovo QiTianM520-D164  | 1        | 3.03%   |
| Intel H61               | 1        | 3.03%   |
| Huanan X99              | 1        | 3.03%   |
| HP Z440                 | 1        | 3.03%   |
| HP Z420                 | 1        | 3.03%   |
| HP ProLiant             | 1        | 3.03%   |
| Gigabyte Z690           | 1        | 3.03%   |
| Gigabyte X570S          | 1        | 3.03%   |
| Gigabyte X570           | 1        | 3.03%   |
| Gigabyte M52L-S3        | 1        | 3.03%   |
| Gigabyte H61M-DS2       | 1        | 3.03%   |
| Gigabyte GB-BSi7-1165G7 | 1        | 3.03%   |
| Gigabyte EP31-DS3L      | 1        | 3.03%   |
| Gigabyte B365           | 1        | 3.03%   |
| Fujitsu ESPRIMO         | 1        | 3.03%   |
| Dell Inspiron           | 1        | 3.03%   |
| ASUS ROG                | 1        | 3.03%   |
| ASUS P5P41T             | 1        | 3.03%   |
| ASUS M4A87TD            | 1        | 3.03%   |
| ASUS K30AD              | 1        | 3.03%   |
| ASRockRack 520004       | 1        | 3.03%   |
| ASRock 970              | 1        | 3.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 6        | 18.18%  |
| 2012 | 5        | 15.15%  |
| 2020 | 4        | 12.12%  |
| 2019 | 3        | 9.09%   |
| 2017 | 3        | 9.09%   |
| 2018 | 2        | 6.06%   |
| 2010 | 2        | 6.06%   |
| 2016 | 1        | 3.03%   |
| 2015 | 1        | 3.03%   |
| 2014 | 1        | 3.03%   |
| 2013 | 1        | 3.03%   |
| 2011 | 1        | 3.03%   |
| 2008 | 1        | 3.03%   |
| 2007 | 1        | 3.03%   |
| 2006 | 1        | 3.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 33       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 32       | 96.97%  |
| Enabled  | 1        | 3.03%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 33       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 64.01-256.0 | 7        | 21.21%  |
| 16.01-24.0  | 7        | 21.21%  |
| 32.01-64.0  | 5        | 15.15%  |
| 3.01-4.0    | 5        | 15.15%  |
| 8.01-16.0   | 5        | 15.15%  |
| 4.01-8.0    | 4        | 12.12%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 13       | 39.39%  |
| 2.01-3.0  | 9        | 27.27%  |
| 8.01-16.0 | 4        | 12.12%  |
| 4.01-8.0  | 3        | 9.09%   |
| 3.01-4.0  | 3        | 9.09%   |
| 0.51-1.0  | 1        | 3.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 13       | 38.24%  |
| 1      | 9        | 26.47%  |
| 4      | 4        | 11.76%  |
| 3      | 4        | 11.76%  |
| 20     | 1        | 2.94%   |
| 8      | 1        | 2.94%   |
| 6      | 1        | 2.94%   |
| 5      | 1        | 2.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 57.58%  |
| Yes       | 14       | 42.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 33       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 51.52%  |
| Yes       | 16       | 48.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 57.58%  |
| Yes       | 14       | 42.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 7        | 21.21%  |
| Germany     | 6        | 18.18%  |
| Spain       | 2        | 6.06%   |
| Russia      | 2        | 6.06%   |
| France      | 2        | 6.06%   |
| Czechia     | 2        | 6.06%   |
| Brazil      | 2        | 6.06%   |
| UK          | 1        | 3.03%   |
| Thailand    | 1        | 3.03%   |
| Taiwan      | 1        | 3.03%   |
| South Korea | 1        | 3.03%   |
| Romania     | 1        | 3.03%   |
| Poland      | 1        | 3.03%   |
| Japan       | 1        | 3.03%   |
| Italy       | 1        | 3.03%   |
| India       | 1        | 3.03%   |
| China       | 1        | 3.03%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Madrid              | 2        | 6.06%   |
| Warsaw              | 1        | 3.03%   |
| Sutton Coldfield    | 1        | 3.03%   |
| Suffolk             | 1        | 3.03%   |
| St Petersburg       | 1        | 3.03%   |
| Springdale          | 1        | 3.03%   |
| Soest               | 1        | 3.03%   |
| Seoul               | 1        | 3.03%   |
| Senonches           | 1        | 3.03%   |
| San Valentino Torio | 1        | 3.03%   |
| Recife              | 1        | 3.03%   |
| Prague              | 1        | 3.03%   |
| Phuket              | 1        | 3.03%   |
| Ostrava             | 1        | 3.03%   |
| Osasco              | 1        | 3.03%   |
| Oakland             | 1        | 3.03%   |
| Novosibirsk         | 1        | 3.03%   |
| Newark              | 1        | 3.03%   |
| New Taipei          | 1        | 3.03%   |
| Moses Lake          | 1        | 3.03%   |
| Millville           | 1        | 3.03%   |
| Krefeld             | 1        | 3.03%   |
| Hyattsville         | 1        | 3.03%   |
| Hamburg             | 1        | 3.03%   |
| Gudensberg          | 1        | 3.03%   |
| Frankfurt am Main   | 1        | 3.03%   |
| Chantonnay          | 1        | 3.03%   |
| Bucharest           | 1        | 3.03%   |
| Bengaluru           | 1        | 3.03%   |
| Beijing             | 1        | 3.03%   |
| Aspisheim           | 1        | 3.03%   |
| Aichi               | 1        | 3.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 13       | 17     | 19.7%   |
| WDC                 | 11       | 34     | 16.67%  |
| Samsung Electronics | 10       | 16     | 15.15%  |
| Toshiba             | 4        | 4      | 6.06%   |
| Kingston            | 3        | 6      | 4.55%   |
| SK Hynix            | 2        | 2      | 3.03%   |
| SanDisk             | 2        | 2      | 3.03%   |
| Phison              | 2        | 2      | 3.03%   |
| OCZ                 | 2        | 5      | 3.03%   |
| Intenso             | 2        | 2      | 3.03%   |
| Intel               | 2        | 2      | 3.03%   |
| Hitachi             | 2        | 2      | 3.03%   |
| Unknown             | 1        | 4      | 1.52%   |
| UMAX                | 1        | 1      | 1.52%   |
| Transcend           | 1        | 1      | 1.52%   |
| SPCC                | 1        | 1      | 1.52%   |
| Silicon Motion      | 1        | 1      | 1.52%   |
| Micron Technology   | 1        | 1      | 1.52%   |
| KIOXIA              | 1        | 2      | 1.52%   |
| JMicron             | 1        | 1      | 1.52%   |
| HGST                | 1        | 2      | 1.52%   |
| Crucial             | 1        | 1      | 1.52%   |
| A-DATA Technology   | 1        | 1      | 1.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB         | 3        | 3.53%   |
| WDC WD10EZRX-00A8LB0 1TB               | 2        | 2.35%   |
| Seagate ST2000DM008-2FR102 2TB         | 2        | 2.35%   |
| Samsung SSD 850 EVO 500GB              | 2        | 2.35%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 2        | 2.35%   |
| Samsung NVMe SSD Drive 1TB             | 2        | 2.35%   |
| WDC WDS500G3X0C-00SJG0 500GB           | 1        | 1.18%   |
| WDC WDS100T3X0C-00SJG0 1TB             | 1        | 1.18%   |
| WDC WD80EMAZ-00WJTA0 8TB               | 1        | 1.18%   |
| WDC WD80EFZX-68UW8N0 8TB               | 1        | 1.18%   |
| WDC WD80EFAX-68LHPN0 8TB               | 1        | 1.18%   |
| WDC WD80 EMAZ-00WJTA0 8TB              | 1        | 1.18%   |
| WDC WD60 EFRX-68L0BN1 6TB              | 1        | 1.18%   |
| WDC WD40EFRX-68N32N0 4TB               | 1        | 1.18%   |
| WDC WD4000AAKS-00TMA0 400GB            | 1        | 1.18%   |
| WDC WD3200AAKS-00L9A0 320GB            | 1        | 1.18%   |
| WDC WD3200AAKS-00B3A0 320GB            | 1        | 1.18%   |
| WDC WD3200AAJS-00VWA0 320GB            | 1        | 1.18%   |
| WDC WD20SPZX-75UA7T1 2TB               | 1        | 1.18%   |
| WDC WD20EARX-00PASB0 2TB               | 1        | 1.18%   |
| WDC WD20EARS-00MVWB0 2TB               | 1        | 1.18%   |
| WDC WD140EDFZ-11A0VA0 14TB             | 1        | 1.18%   |
| WDC WD12 0EMAZ-11BLFA 12TB             | 1        | 1.18%   |
| WDC WD10SPSX-60A6WT0 1TB               | 1        | 1.18%   |
| WDC WD100EMAZ-00WJTA0 10TB             | 1        | 1.18%   |
| WDC WD1001FALS-00J7B0 1TB              | 1        | 1.18%   |
| WDC WD10 0EMAZ-00WJTA 10TB             | 1        | 1.18%   |
| WDC PC SN520 SDAPMUW-128G-1001 128GB   | 1        | 1.18%   |
| Unknown MMC Card  64GB                 | 1        | 1.18%   |
| UMAX 2280 64G SSD                      | 1        | 1.18%   |
| Transcend TS512GSSD370S 512GB          | 1        | 1.18%   |
| Toshiba HDWL120 2TB                    | 1        | 1.18%   |
| Toshiba HDWE140 4TB                    | 1        | 1.18%   |
| Toshiba DT01ACA100 1TB                 | 1        | 1.18%   |
| Toshiba DT01ACA050 500GB               | 1        | 1.18%   |
| SPCC Solid State Disk 256GB            | 1        | 1.18%   |
| SK Hynix NVMe SSD Drive 1TB            | 1        | 1.18%   |
| SK Hynix BC511 NVMe 256GB              | 1        | 1.18%   |
| Silicon Motion NVMe SSD Drive 256GB    | 1        | 1.18%   |
| Seagate ST8000AS 0002-1NA17Z 8TB       | 1        | 1.18%   |
| Seagate ST3750640NS 752GB              | 1        | 1.18%   |
| Seagate ST3500410SV 500GB              | 1        | 1.18%   |
| Seagate ST3250312AS 250GB              | 1        | 1.18%   |
| Seagate ST2000VX005-1TD164 2TB         | 1        | 1.18%   |
| Seagate ST2000DM001-9YN164 2TB         | 1        | 1.18%   |
| Seagate ST1000DM003-9YN162 1TB         | 1        | 1.18%   |
| Seagate Expansion 500GB                | 1        | 1.18%   |
| SanDisk SSD PLUS 2000GB                | 1        | 1.18%   |
| SanDisk SDSSDP128G 128GB               | 1        | 1.18%   |
| Samsung SSD 980 PRO 1TB                | 1        | 1.18%   |
| Samsung SSD 980 1TB                    | 1        | 1.18%   |
| Samsung SSD 970 EVO Plus 1TB           | 1        | 1.18%   |
| Samsung SSD 870 QVO 1TB                | 1        | 1.18%   |
| Samsung SSD 860 PRO 256GB              | 1        | 1.18%   |
| Samsung SSD 860 EVO M.2 1TB            | 1        | 1.18%   |
| Samsung SSD 850 PRO 128GB              | 1        | 1.18%   |
| Samsung SSD 750 EVO 250GB              | 1        | 1.18%   |
| Samsung NVMe SSD Drive 512GB           | 1        | 1.18%   |
| Phison NVMe SSD Drive 256GB            | 1        | 1.18%   |
| Phison NVMe SSD Drive 1TB              | 1        | 1.18%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 13       | 17     | 44.83%  |
| WDC     | 9        | 31     | 31.03%  |
| Toshiba | 4        | 4      | 13.79%  |
| Hitachi | 2        | 2      | 6.9%    |
| HGST    | 1        | 2      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 7      | 22.73%  |
| Kingston            | 3        | 4      | 13.64%  |
| SanDisk             | 2        | 2      | 9.09%   |
| Intenso             | 2        | 2      | 9.09%   |
| Intel               | 2        | 2      | 9.09%   |
| UMAX                | 1        | 1      | 4.55%   |
| Transcend           | 1        | 1      | 4.55%   |
| SPCC                | 1        | 1      | 4.55%   |
| OCZ                 | 1        | 1      | 4.55%   |
| Micron Technology   | 1        | 1      | 4.55%   |
| JMicron             | 1        | 1      | 4.55%   |
| Crucial             | 1        | 1      | 4.55%   |
| A-DATA Technology   | 1        | 1      | 4.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 20       | 56     | 36.36%  |
| NVMe | 17       | 25     | 30.91%  |
| SSD  | 17       | 25     | 30.91%  |
| MMC  | 1        | 4      | 1.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 27       | 70     | 55.1%   |
| NVMe | 17       | 24     | 34.69%  |
| SAS  | 4        | 12     | 8.16%   |
| MMC  | 1        | 4      | 2.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 17       | 25     | 41.46%  |
| 0.51-1.0   | 13       | 20     | 31.71%  |
| 1.01-2.0   | 7        | 16     | 17.07%  |
| 10.01-20.0 | 2        | 6      | 4.88%   |
| 3.01-4.0   | 1        | 2      | 2.44%   |
| 4.01-10.0  | 1        | 12     | 2.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 11       | 32.35%  |
| 501-1000       | 7        | 20.59%  |
| 251-500        | 5        | 14.71%  |
| More than 3000 | 3        | 8.82%   |
| 1001-2000      | 3        | 8.82%   |
| 2001-3000      | 2        | 5.88%   |
| 1-20           | 1        | 2.94%   |
| 51-100         | 1        | 2.94%   |
| Unknown        | 1        | 2.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 10       | 29.41%  |
| 21-50          | 6        | 17.65%  |
| 251-500        | 4        | 11.76%  |
| 101-250        | 4        | 11.76%  |
| 51-100         | 4        | 11.76%  |
| More than 3000 | 2        | 5.88%   |
| 2001-3000      | 1        | 2.94%   |
| 501-1000       | 1        | 2.94%   |
| 0              | 1        | 2.94%   |
| Unknown        | 1        | 2.94%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST3750640NS 752GB | 1        | 2      | 50%     |
| Intenso SSD 120GB         | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 2      | 50%     |
| Intenso | 1        | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 1        | 1      | 50%     |
| HDD  | 1        | 2      | 50%     |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 24       | 80     | 64.86%  |
| Works    | 11       | 27     | 29.73%  |
| Malfunc  | 2        | 3      | 5.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 20       | 36.36%  |
| AMD                         | 11       | 20%     |
| Samsung Electronics         | 7        | 12.73%  |
| Sandisk                     | 3        | 5.45%   |
| SK Hynix                    | 2        | 3.64%   |
| Phison Electronics          | 2        | 3.64%   |
| ASMedia Technology          | 2        | 3.64%   |
| Silicon Motion              | 1        | 1.82%   |
| OCZ Technology Group        | 1        | 1.82%   |
| Nvidia                      | 1        | 1.82%   |
| Marvell Technology Group    | 1        | 1.82%   |
| LSI Logic / Symbios Logic   | 1        | 1.82%   |
| KIOXIA                      | 1        | 1.82%   |
| Kingston Technology Company | 1        | 1.82%   |
| JMicron Technology          | 1        | 1.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 7        | 10%     |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 5.71%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 4.29%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 4.29%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 2.86%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 2.86%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2        | 2.86%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 2.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 2.86%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 2.86%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 2.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 2.86%   |
| SK Hynix Gold P31 SSD                                                                   | 1        | 1.43%   |
| SK Hynix BC511                                                                          | 1        | 1.43%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 1.43%   |
| Sandisk PC SN520 NVMe SSD                                                               | 1        | 1.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 1.43%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 1.43%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.43%   |
| Phison E12 NVMe Controller                                                              | 1        | 1.43%   |
| OCZ Group RD400/400A SSD                                                                | 1        | 1.43%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 1.43%   |
| Nvidia MCP61 IDE                                                                        | 1        | 1.43%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 1.43%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                 | 1        | 1.43%   |
| KIOXIA NVMe SSD Controller Cx6                                                          | 1        | 1.43%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1        | 1.43%   |
| JMicron JMB368 IDE controller                                                           | 1        | 1.43%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1        | 1.43%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 1.43%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 1.43%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 1.43%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.43%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                              | 1        | 1.43%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 1.43%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 1.43%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 1        | 1.43%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1        | 1.43%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 1.43%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 1.43%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 1.43%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 1.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 23       | 42.59%  |
| NVMe | 17       | 31.48%  |
| IDE  | 9        | 16.67%  |
| RAID | 3        | 5.56%   |
| SAS  | 2        | 3.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 21       | 63.64%  |
| AMD    | 12       | 36.36%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel 12th Gen Core i5-12600K               | 2        | 6.06%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 6.06%   |
| Intel Xeon CPU E5-2696 v2 @ 2.50GHz         | 1        | 3.03%   |
| Intel Xeon CPU E5-2690 v4 @ 2.60GHz         | 1        | 3.03%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz         | 1        | 3.03%   |
| Intel Xeon CPU E31220 @ 3.10GHz             | 1        | 3.03%   |
| Intel Pentium CPU G3260T @ 2.90GHz          | 1        | 3.03%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 3.03%   |
| Intel Core i5-9500 CPU @ 3.00GHz            | 1        | 3.03%   |
| Intel Core i5-4460S CPU @ 2.90GHz           | 1        | 3.03%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 3.03%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 1        | 3.03%   |
| Intel Core i3-9100F CPU @ 3.60GHz           | 1        | 3.03%   |
| Intel Core i3-6300T CPU @ 3.30GHz           | 1        | 3.03%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 3.03%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 1        | 3.03%   |
| Intel Celeron J4105 CPU @ 1.50GHz           | 1        | 3.03%   |
| Intel Celeron CPU G1620 @ 2.70GHz           | 1        | 3.03%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 1        | 3.03%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz     | 1        | 3.03%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 1        | 3.03%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1        | 3.03%   |
| AMD Ryzen 7 PRO 3700 8-Core Processor       | 1        | 3.03%   |
| AMD Ryzen 7 1800X Eight-Core Processor      | 1        | 3.03%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 1        | 3.03%   |
| AMD Ryzen 5 3600 6-Core Processor           | 1        | 3.03%   |
| AMD PRO A12-8870 R7, 12 COMPUTE CORES 4C+8G | 1        | 3.03%   |
| AMD Phenom II X6 1090T Processor            | 1        | 3.03%   |
| AMD Phenom II X4 965 Processor              | 1        | 3.03%   |
| AMD E1-1200 APU with Radeon HD Graphics     | 1        | 3.03%   |
| AMD Athlon 64 X2 Dual Core Processor 5200+  | 1        | 3.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| Other            | 5        | 15.15%  |
| Intel Xeon       | 4        | 12.12%  |
| Intel Core i5    | 4        | 12.12%  |
| AMD Ryzen 5      | 3        | 9.09%   |
| Intel Core i3    | 2        | 6.06%   |
| Intel Core 2 Duo | 2        | 6.06%   |
| Intel Celeron    | 2        | 6.06%   |
| AMD Ryzen 7      | 2        | 6.06%   |
| Intel Pentium 4  | 1        | 3.03%   |
| Intel Pentium    | 1        | 3.03%   |
| Intel Atom       | 1        | 3.03%   |
| AMD Ryzen 9      | 1        | 3.03%   |
| AMD Ryzen 7 PRO  | 1        | 3.03%   |
| AMD Phenom II X6 | 1        | 3.03%   |
| AMD Phenom II X4 | 1        | 3.03%   |
| AMD E1           | 1        | 3.03%   |
| AMD Athlon 64 X2 | 1        | 3.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 9        | 27.27%  |
| 2      | 7        | 21.21%  |
| 6      | 6        | 18.18%  |
| 8      | 4        | 12.12%  |
| 12     | 2        | 6.06%   |
| 10     | 2        | 6.06%   |
| 1      | 2        | 6.06%   |
| 28     | 1        | 3.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 32       | 96.97%  |
| 2      | 1        | 3.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 18       | 54.55%  |
| 2      | 15       | 45.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 33       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 17       | 51.52%  |
| 0xa0671    | 1        | 3.03%   |
| 0x906ea    | 1        | 3.03%   |
| 0x806c1    | 1        | 3.03%   |
| 0x706a1    | 1        | 3.03%   |
| 0x506e3    | 1        | 3.03%   |
| 0x306e4    | 1        | 3.03%   |
| 0x306c3    | 1        | 3.03%   |
| 0x306a9    | 1        | 3.03%   |
| 0x10677    | 1        | 3.03%   |
| 0x0a201016 | 1        | 3.03%   |
| 0x0a201009 | 1        | 3.03%   |
| 0x08701021 | 1        | 3.03%   |
| 0x08001137 | 1        | 3.03%   |
| 0x0600611a | 1        | 3.03%   |
| 0x05000119 | 1        | 3.03%   |
| 0x010000c8 | 1        | 3.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| IvyBridge     | 4        | 12.12%  |
| Zen 2         | 3        | 9.09%   |
| Zen 3         | 2        | 6.06%   |
| Zen           | 2        | 6.06%   |
| KabyLake      | 2        | 6.06%   |
| K10           | 2        | 6.06%   |
| Haswell       | 2        | 6.06%   |
| Broadwell     | 2        | 6.06%   |
| Unknown       | 2        | 6.06%   |
| TigerLake     | 1        | 3.03%   |
| Skylake       | 1        | 3.03%   |
| Silvermont    | 1        | 3.03%   |
| SandyBridge   | 1        | 3.03%   |
| Penryn        | 1        | 3.03%   |
| NetBurst      | 1        | 3.03%   |
| K8 Hammer     | 1        | 3.03%   |
| Icelake       | 1        | 3.03%   |
| Goldmont plus | 1        | 3.03%   |
| Excavator     | 1        | 3.03%   |
| Core          | 1        | 3.03%   |
| Bobcat        | 1        | 3.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 15       | 42.86%  |
| Intel                      | 9        | 25.71%  |
| AMD                        | 9        | 25.71%  |
| Matrox Electronics Systems | 1        | 2.86%   |
| ASPEED Technology          | 1        | 2.86%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 5.71%   |
| Intel AlderLake-S GT1                                                                    | 2        | 5.71%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 2.86%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 2.86%   |
| Nvidia GM204GL [Quadro M4000]                                                            | 1        | 2.86%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 2.86%   |
| Nvidia GM107 [GeForce GTX 745]                                                           | 1        | 2.86%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1        | 2.86%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 2.86%   |
| Nvidia GK104 [GeForce GTX 680]                                                           | 1        | 2.86%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 1        | 2.86%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 1        | 2.86%   |
| Nvidia GA106 [Geforce RTX 3050]                                                          | 1        | 2.86%   |
| Nvidia GA104GL [RTX A4000]                                                               | 1        | 2.86%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 1        | 2.86%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1        | 2.86%   |
| Nvidia G92 [GeForce 9800 GT]                                                             | 1        | 2.86%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1        | 2.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1        | 2.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1        | 2.86%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1        | 2.86%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1        | 2.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 2.86%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 1        | 2.86%   |
| AMD Tahiti PRO [Radeon HD 7950/8950 OEM / R9 280]                                        | 1        | 2.86%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 1        | 2.86%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 1        | 2.86%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 1        | 2.86%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1        | 2.86%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1        | 2.86%   |
| AMD Cedar [Radeon HD 7350/8350 / R5 220]                                                 | 1        | 2.86%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1        | 2.86%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 1        | 2.86%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 14       | 42.42%  |
| 1 x AMD         | 9        | 27.27%  |
| 1 x Intel       | 8        | 24.24%  |
| Nvidia + Matrox | 1        | 3.03%   |
| 1 x ASPEED      | 1        | 3.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 20       | 60.61%  |
| Proprietary | 10       | 30.3%   |
| Unknown     | 3        | 9.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 19       | 57.58%  |
| 1.01-2.0   | 5        | 15.15%  |
| 7.01-8.0   | 4        | 12.12%  |
| 0.51-1.0   | 2        | 6.06%   |
| 3.01-4.0   | 1        | 3.03%   |
| 2.01-3.0   | 1        | 3.03%   |
| 8.01-16.0  | 1        | 3.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 7        | 20.59%  |
| Dell                 | 5        | 14.71%  |
| Philips              | 3        | 8.82%   |
| LG Electronics       | 3        | 8.82%   |
| Hewlett-Packard      | 2        | 5.88%   |
| ViewSonic            | 1        | 2.94%   |
| Vestel Elektronik    | 1        | 2.94%   |
| Skyworth             | 1        | 2.94%   |
| Sceptre Tech         | 1        | 2.94%   |
| Panasonic            | 1        | 2.94%   |
| Onkyo                | 1        | 2.94%   |
| Lenovo               | 1        | 2.94%   |
| KTC                  | 1        | 2.94%   |
| HUAWEI               | 1        | 2.94%   |
| Goldstar             | 1        | 2.94%   |
| Gigabyte Technology  | 1        | 2.94%   |
| Compal               | 1        | 2.94%   |
| Ancor Communications | 1        | 2.94%   |
| Acer                 | 1        | 2.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                 | 1        | 2.94%   |
| Vestel Elektronik 48FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch  | 1        | 2.94%   |
| Skyworth SII REPEATER SII214F 1920x1080 476x268mm 21.5-inch            | 1        | 2.94%   |
| Sceptre Tech F27 SPT0ABF 1920x1080 409x230mm 18.5-inch                 | 1        | 2.94%   |
| Samsung Electronics T24D391 SAM0B73 1920x1080 521x293mm 23.5-inch      | 1        | 2.94%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch    | 1        | 2.94%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch      | 1        | 2.94%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch  | 1        | 2.94%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch   | 1        | 2.94%   |
| Samsung Electronics LCD Monitor SAM08FC 1366x768                       | 1        | 2.94%   |
| Samsung Electronics LCD Monitor LS32A70 3840x2160                      | 1        | 2.94%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                | 1        | 2.94%   |
| Philips FTV PHL04C3 1920x1080 1440x810mm 65.0-inch                     | 1        | 2.94%   |
| Philips 224CL PHLC075 1920x1080 492x278mm 22.2-inch                    | 1        | 2.94%   |
| Panasonic 10SP_AMP MEI4012 1920x540                                    | 1        | 2.94%   |
| Onkyo TX-NR747 ONK0F71 1920x1200 550x309mm 24.8-inch                   | 1        | 2.94%   |
| LG Electronics LCD Monitor LG ULTRAWIDE                                | 1        | 2.94%   |
| LG Electronics LCD Monitor LG ULTRAGEAR 2560x1440                      | 1        | 2.94%   |
| LG Electronics LCD Monitor LG HDR WFHD 2560x1080                       | 1        | 2.94%   |
| Lenovo X24q-10 LEN61A4 2560x1440 527x296mm 23.8-inch                   | 1        | 2.94%   |
| KTC 43 TV KTC4300 1920x1080 953x543mm 43.2-inch                        | 1        | 2.94%   |
| HUAWEI ZQE-CAA HWV6A25 3440x1440 797x334mm 34.0-inch                   | 1        | 2.94%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch            | 1        | 2.94%   |
| Hewlett-Packard 2710 HWP2893 1920x1080 600x340mm 27.2-inch             | 1        | 2.94%   |
| Goldstar W2252 GSM567E 1680x1050 474x296mm 22.0-inch                   | 1        | 2.94%   |
| Gigabyte Technology AORUS AD27QD GBT2701 2560x1440 609x355mm 27.8-inch | 1        | 2.94%   |
| Dell U2713H DELA091 2560x1440 597x336mm 27.0-inch                      | 1        | 2.94%   |
| Dell S2421HS DEL41F4 1920x1080 530x300mm 24.0-inch                     | 1        | 2.94%   |
| Dell LCD Monitor P2419H 4480x1080                                      | 1        | 2.94%   |
| Dell 1909W DELA03D 1440x900 408x255mm 18.9-inch                        | 1        | 2.94%   |
| Dell 1704FPV DEL3016 1280x1024 338x270mm 17.0-inch                     | 1        | 2.94%   |
| Compal TERRA 1940HA WOR1940 1280x1024 376x301mm 19.0-inch              | 1        | 2.94%   |
| Ancor Communications ASUS VP247 ACI24C7 1920x1080 521x293mm 23.5-inch  | 1        | 2.94%   |
| Acer KG271 A ACR0596 1920x1080 598x336mm 27.0-inch                     | 1        | 2.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 11       | 33.33%  |
| 3840x2160 (4K)     | 4        | 12.12%  |
| 2560x1440 (QHD)    | 4        | 12.12%  |
| 1280x1024 (SXGA)   | 3        | 9.09%   |
| 1440x900 (WXGA+)   | 2        | 6.06%   |
| 1366x768 (WXGA)    | 2        | 6.06%   |
| 4480x1080          | 1        | 3.03%   |
| 3440x1440          | 1        | 3.03%   |
| 2560x1080          | 1        | 3.03%   |
| 1920x540           | 1        | 3.03%   |
| 1920x1200 (WUXGA)  | 1        | 3.03%   |
| 1680x1050 (WSXGA+) | 1        | 3.03%   |
| Unknown            | 1        | 3.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 6        | 18.18%  |
| Unknown | 6        | 18.18%  |
| 27      | 5        | 15.15%  |
| 19      | 3        | 9.09%   |
| 43      | 2        | 6.06%   |
| 17      | 2        | 6.06%   |
| 84      | 1        | 3.03%   |
| 65      | 1        | 3.03%   |
| 34      | 1        | 3.03%   |
| 32      | 1        | 3.03%   |
| 31      | 1        | 3.03%   |
| 25      | 1        | 3.03%   |
| 24      | 1        | 3.03%   |
| 22      | 1        | 3.03%   |
| 21      | 1        | 3.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 10       | 31.25%  |
| Unknown     | 6        | 18.75%  |
| 401-500     | 5        | 15.63%  |
| 701-800     | 2        | 6.25%   |
| 601-700     | 2        | 6.25%   |
| 301-350     | 2        | 6.25%   |
| 901-1000    | 2        | 6.25%   |
| 351-400     | 1        | 3.13%   |
| 1501-2000   | 1        | 3.13%   |
| 1001-1500   | 1        | 3.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 20       | 62.5%   |
| Unknown | 4        | 12.5%   |
| 5/4     | 3        | 9.38%   |
| 16/10   | 2        | 6.25%   |
| 32/9    | 1        | 3.13%   |
| 3/2     | 1        | 3.13%   |
| 21/9    | 1        | 3.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 8        | 24.24%  |
| Unknown        | 6        | 18.18%  |
| 301-350        | 5        | 15.15%  |
| 151-200        | 4        | 12.12%  |
| 351-500        | 3        | 9.09%   |
| More than 1000 | 2        | 6.06%   |
| 141-150        | 2        | 6.06%   |
| 501-1000       | 2        | 6.06%   |
| 251-300        | 1        | 3.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 16       | 51.61%  |
| Unknown | 6        | 19.35%  |
| 101-120 | 5        | 16.13%  |
| 1-50    | 2        | 6.45%   |
| 121-160 | 2        | 6.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 28       | 84.85%  |
| 2     | 4        | 12.12%  |
| 0     | 1        | 3.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 21       | 45.65%  |
| Intel                 | 17       | 36.96%  |
| Qualcomm Atheros      | 2        | 4.35%   |
| Xiaomi                | 1        | 2.17%   |
| Pulse-Eight           | 1        | 2.17%   |
| Nvidia                | 1        | 2.17%   |
| Mellanox Technologies | 1        | 2.17%   |
| Linksys               | 1        | 2.17%   |
| American Megatrends   | 1        | 2.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12       | 21.05%  |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3        | 5.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 5.26%   |
| Intel I211 Gigabit Network Connection                             | 3        | 5.26%   |
| Realtek 802.11ac NIC                                              | 2        | 3.51%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 3.51%   |
| Intel Ethernet Controller I225-V                                  | 2        | 3.51%   |
| Intel Ethernet Connection I217-V                                  | 2        | 3.51%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 3.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 3.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.75%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 1.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.75%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 1.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1        | 1.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1        | 1.75%   |
| Pulse-Eight CEC Adapter                                           | 1        | 1.75%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.75%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 1        | 1.75%   |
| Linksys AE3000 802.11abgn (3x3) Wireless Adapter [Ralink RT3573]  | 1        | 1.75%   |
| Intel Wireless 8265 / 8275                                        | 1        | 1.75%   |
| Intel Wireless 7265                                               | 1        | 1.75%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 1.75%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.75%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 1.75%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.75%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 1.75%   |
| Intel Ethernet Connection (13) I219-V                             | 1        | 1.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 1.75%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 1        | 1.75%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.75%   |
| American Megatrends Virtual Ethernet                              | 1        | 1.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 41.18%  |
| Intel                 | 7        | 41.18%  |
| Qualcomm Atheros      | 2        | 11.76%  |
| Linksys               | 1        | 5.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Realtek RTL88x2bu [AC1200 Techkey]                               | 3        | 17.65%  |
| Realtek 802.11ac NIC                                             | 2        | 11.76%  |
| Intel Wi-Fi 6 AX200                                              | 2        | 11.76%  |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter         | 1        | 5.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter              | 1        | 5.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 1        | 5.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)   | 1        | 5.88%   |
| Linksys AE3000 802.11abgn (3x3) Wireless Adapter [Ralink RT3573] | 1        | 5.88%   |
| Intel Wireless 8265 / 8275                                       | 1        | 5.88%   |
| Intel Wireless 7265                                              | 1        | 5.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                           | 1        | 5.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                 | 1        | 5.88%   |
| Intel Alder Lake-S PCH CNVi WiFi                                 | 1        | 5.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 17       | 47.22%  |
| Intel                 | 15       | 41.67%  |
| Xiaomi                | 1        | 2.78%   |
| Nvidia                | 1        | 2.78%   |
| Mellanox Technologies | 1        | 2.78%   |
| American Megatrends   | 1        | 2.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12       | 30.77%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 7.69%   |
| Intel I211 Gigabit Network Connection                             | 3        | 7.69%   |
| Intel Ethernet Controller I225-V                                  | 2        | 5.13%   |
| Intel Ethernet Connection I217-V                                  | 2        | 5.13%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 5.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 5.13%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 2.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 2.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 2.56%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 2.56%   |
| Nvidia MCP61 Ethernet                                             | 1        | 2.56%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 1        | 2.56%   |
| Intel I210 Gigabit Network Connection                             | 1        | 2.56%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 2.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 2.56%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 2.56%   |
| Intel Ethernet Connection (13) I219-V                             | 1        | 2.56%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 2.56%   |
| American Megatrends Virtual Ethernet                              | 1        | 2.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 33       | 66%     |
| WiFi     | 16       | 32%     |
| Modem    | 1        | 2%      |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 28       | 71.79%  |
| WiFi     | 11       | 28.21%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 20       | 60.61%  |
| 2     | 11       | 33.33%  |
| 3     | 2        | 6.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 22       | 66.67%  |
| Yes  | 11       | 33.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 6        | 40%     |
| Realtek Semiconductor           | 2        | 13.33%  |
| Cambridge Silicon Radio         | 2        | 13.33%  |
| Qualcomm Atheros Communications | 1        | 6.67%   |
| Logitech                        | 1        | 6.67%   |
| IMC Networks                    | 1        | 6.67%   |
| Dell                            | 1        | 6.67%   |
| Broadcom                        | 1        | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Realtek Bluetooth Radio                             | 2        | 13.33%  |
| Intel Bluetooth Device                              | 2        | 13.33%  |
| Intel AX200 Bluetooth                               | 2        | 13.33%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 13.33%  |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 6.67%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1        | 6.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 6.67%   |
| Intel AX210 Bluetooth                               | 1        | 6.67%   |
| IMC Networks Bluetooth Radio                        | 1        | 6.67%   |
| Dell BCM20702A0                                     | 1        | 6.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 19       | 36.54%  |
| Nvidia              | 14       | 26.92%  |
| AMD                 | 14       | 26.92%  |
| C-Media Electronics | 3        | 5.77%   |
| DigiTech            | 1        | 1.92%   |
| Corsair             | 1        | 1.92%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 8.47%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 5.08%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 3.39%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 3.39%   |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 3.39%   |
| Nvidia Audio device                                                        | 2        | 3.39%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 3.39%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 3.39%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 3.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 3.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 3.39%   |
| AMD Navi 10 HDMI Audio                                                     | 2        | 3.39%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 3.39%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 3.39%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 3.39%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1.69%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.69%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 1.69%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 1.69%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 1.69%   |
| Nvidia GF116 High Definition Audio Controller                              | 1        | 1.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 1.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1        | 1.69%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 1.69%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.69%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 1.69%   |
| Intel Audio device                                                         | 1        | 1.69%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1        | 1.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 1.69%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 1.69%   |
| DigiTech Lexicon Alpha                                                     | 1        | 1.69%   |
| Corsair Slipstream Multi-Device Receiver                                   | 1        | 1.69%   |
| C-Media Electronics USB Advanced Audio Device                              | 1        | 1.69%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1        | 1.69%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1        | 1.69%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 1        | 1.69%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 1.69%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1        | 1.69%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 1.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK Hynix            | 3        | 16.67%  |
| Micron Technology   | 3        | 16.67%  |
| Kingston            | 3        | 16.67%  |
| Samsung Electronics | 2        | 11.11%  |
| G.Skill             | 2        | 11.11%  |
| Unknown (ABCD)      | 1        | 5.56%   |
| Unknown             | 1        | 5.56%   |
| Patriot             | 1        | 5.56%   |
| Kllisre             | 1        | 5.56%   |
| Corsair             | 1        | 5.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM 1066MT/s                           | 1        | 4.76%   |
| Unknown (ABCD) RAM 123456789012345678 3GB DIMM LPDDR4 2400MT/s | 1        | 4.76%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1066MT/s                     | 1        | 4.76%   |
| SK Hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s           | 1        | 4.76%   |
| SK Hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2666MT/s           | 1        | 4.76%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s          | 1        | 4.76%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 2667MT/s           | 1        | 4.76%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s                 | 1        | 4.76%   |
| Micron RAM 8ATF2G64AZ-3G2E1 16GB DIMM DDR4 3200MT/s            | 1        | 4.76%   |
| Micron RAM 38ADF2G72AZ-2G6E1 16GB DIMM DDR4 2133MT/s           | 1        | 4.76%   |
| Micron RAM 36JSF2G72PZ-1G9E1 16GB DIMM DDR3 1866MT/s           | 1        | 4.76%   |
| Micron RAM 18ASF2G72AZ-2G1A1 16GB DIMM DDR4 2133MT/s           | 1        | 4.76%   |
| Micron RAM 18ADF2G72AZ-2G6E1 16GB DIMM DDR4 2667MT/s           | 1        | 4.76%   |
| Kllisre RAM KRE-D3U1600M/8G 8GB DIMM DDR3 1600MT/s             | 1        | 4.76%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s         | 1        | 4.76%   |
| Kingston RAM CL7-7-7 DDR3-1333 2GB DIMM DDR3 1333MT/s          | 1        | 4.76%   |
| Kingston RAM 99U5474-015.A00LF 2048MB DIMM 1600MT/s            | 1        | 4.76%   |
| Kingston RAM 9905428-123.A00LF 8GB SODIMM DDR3 1600MT/s        | 1        | 4.76%   |
| G.Skill RAM F4-3600C18-16GTZN 16GB DIMM DDR4 3666MT/s          | 1        | 4.76%   |
| G.Skill RAM F4-3200C22-16GRS 16384MB SODIMM DDR4 3200MT/s      | 1        | 4.76%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s          | 1        | 4.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 9        | 56.25%  |
| DDR3    | 5        | 31.25%  |
| LPDDR4  | 1        | 6.25%   |
| Unknown | 1        | 6.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 14       | 87.5%   |
| SODIMM | 2        | 12.5%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 7        | 43.75%  |
| 8192  | 5        | 31.25%  |
| 4096  | 2        | 12.5%   |
| 32768 | 1        | 6.25%   |
| 2048  | 1        | 6.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 3        | 15.79%  |
| 2667  | 3        | 15.79%  |
| 1600  | 3        | 15.79%  |
| 2666  | 2        | 10.53%  |
| 1066  | 2        | 10.53%  |
| 3666  | 1        | 5.26%   |
| 3466  | 1        | 5.26%   |
| 2400  | 1        | 5.26%   |
| 2133  | 1        | 5.26%   |
| 1866  | 1        | 5.26%   |
| 1333  | 1        | 5.26%   |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Sunplus Innovation Technology | 2        | 28.57%  |
| Sony                          | 1        | 14.29%  |
| Samsung Electronics           | 1        | 14.29%  |
| Razer USA                     | 1        | 14.29%  |
| Hewlett-Packard               | 1        | 14.29%  |
| HD 2MP WEBCAM                 | 1        | 14.29%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                          | Desktops | Percent |
|--------------------------------|----------|---------|
| Sunplus USB camera             | 1        | 14.29%  |
| Sunplus Full HD webcam         | 1        | 14.29%  |
| Sony CEVCECM                   | 1        | 14.29%  |
| Samsung Galaxy A5 (MTP)        | 1        | 14.29%  |
| Razer USA Gaming Webcam [Kiyo] | 1        | 14.29%  |
| HP Webcam                      | 1        | 14.29%  |
| HD 2MP WEBCAM HD 2MP WEBCAM    | 1        | 14.29%  |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

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


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 25       | 75.76%  |
| 1     | 7        | 21.21%  |
| 2     | 1        | 3.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 4        | 50%     |
| Unassigned class         | 2        | 25%     |
| Net/wireless             | 1        | 12.5%   |
| Communication controller | 1        | 12.5%   |

