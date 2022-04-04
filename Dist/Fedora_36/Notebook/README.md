Fedora 36 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 36.

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

Total: 35

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Swift SF314-41              | [564cfd1f31](https://linux-hardware.org/?probe=564cfd1f31) | Apr 04, 2022 |
| Acer          | Aspire A515-45              | [eb69a7978b](https://linux-hardware.org/?probe=eb69a7978b) | Apr 04, 2022 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [8444b44333](https://linux-hardware.org/?probe=8444b44333) | Apr 04, 2022 |
| Chuwi         | Hi10 Go                     | [cfa6610288](https://linux-hardware.org/?probe=cfa6610288) | Apr 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [8c1841d2d0](https://linux-hardware.org/?probe=8c1841d2d0) | Apr 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5eef69398a](https://linux-hardware.org/?probe=5eef69398a) | Apr 03, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [ba4863a7bb](https://linux-hardware.org/?probe=ba4863a7bb) | Apr 02, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [cd942b0305](https://linux-hardware.org/?probe=cd942b0305) | Apr 02, 2022 |
| Dell          | Inspiron 5548               | [9e35cab29a](https://linux-hardware.org/?probe=9e35cab29a) | Apr 02, 2022 |
| Dell          | XPS 13 9333                 | [f4fb42182f](https://linux-hardware.org/?probe=f4fb42182f) | Apr 01, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [4c0c1422e7](https://linux-hardware.org/?probe=4c0c1422e7) | Mar 31, 2022 |
| Lenovo        | ThinkPad X260 20F5S0HK1J    | [a83d3cbe5f](https://linux-hardware.org/?probe=a83d3cbe5f) | Mar 31, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [cc95f0e3ab](https://linux-hardware.org/?probe=cc95f0e3ab) | Mar 31, 2022 |
| VALE          | Notebook Slim S132          | [138a4f1d68](https://linux-hardware.org/?probe=138a4f1d68) | Mar 31, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | [05c02cbe41](https://linux-hardware.org/?probe=05c02cbe41) | Mar 31, 2022 |
| Avell High... | B.ON                        | [697fc1d4ec](https://linux-hardware.org/?probe=697fc1d4ec) | Mar 29, 2022 |
| Framework     | Laptop                      | [a22656afee](https://linux-hardware.org/?probe=a22656afee) | Mar 28, 2022 |
| Dell          | XPS 17 9710                 | [461d175c44](https://linux-hardware.org/?probe=461d175c44) | Mar 28, 2022 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [16ac712c84](https://linux-hardware.org/?probe=16ac712c84) | Mar 24, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [1b57f1f410](https://linux-hardware.org/?probe=1b57f1f410) | Mar 13, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [917a6b65a8](https://linux-hardware.org/?probe=917a6b65a8) | Mar 10, 2022 |
| Sony          | VGN-FW21E                   | [930ce5581f](https://linux-hardware.org/?probe=930ce5581f) | Feb 25, 2022 |
| Unknown       | Unknown                     | [033354ee53](https://linux-hardware.org/?probe=033354ee53) | Jan 02, 2022 |
| Unknown       | Unknown                     | [809200ad60](https://linux-hardware.org/?probe=809200ad60) | Jan 02, 2022 |
| Unknown       | Unknown                     | [ea795a97e1](https://linux-hardware.org/?probe=ea795a97e1) | Dec 26, 2021 |
| Unknown       | Unknown                     | [2b26e185d0](https://linux-hardware.org/?probe=2b26e185d0) | Dec 06, 2021 |
| Unknown       | Unknown                     | [f09a7c7125](https://linux-hardware.org/?probe=f09a7c7125) | Dec 06, 2021 |
| Positivo      | CHT12CP                     | [53054c8f7a](https://linux-hardware.org/?probe=53054c8f7a) | Nov 20, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | [1734da4566](https://linux-hardware.org/?probe=1734da4566) | Nov 13, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [2da0673527](https://linux-hardware.org/?probe=2da0673527) | Nov 01, 2021 |
| Notebook      | PCx0Dx                      | [b1a527acdc](https://linux-hardware.org/?probe=b1a527acdc) | Oct 11, 2021 |
| Notebook      | PCx0Dx                      | [90d4556fdf](https://linux-hardware.org/?probe=90d4556fdf) | Oct 11, 2021 |
| Unknown       | Unknown                     | [af4bbffabf](https://linux-hardware.org/?probe=af4bbffabf) | Sep 27, 2021 |
| Unknown       | Unknown                     | [81fd834473](https://linux-hardware.org/?probe=81fd834473) | Sep 26, 2021 |
| HP            | ProBook 4740s               | [77b2eed991](https://linux-hardware.org/?probe=77b2eed991) | Sep 22, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                       | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| 5.17.1-300.fc36.x86_64                                        | 12        | 41.38%  |
| 5.17.0-0.rc7.116.fc36.x86_64                                  | 4         | 13.79%  |
| 5.17.0-300.fc36.x86_64                                        | 3         | 10.34%  |
| 5.17.0-0.rc5.102.fc36.x86_64                                  | 2         | 6.9%    |
| 5.16.16-200.fc35.x86_64                                       | 1         | 3.45%   |
| 5.16.0-0.rc7.20211231git4f3d93c6eaff.52.vanilla.1.fc36.x86_64 | 1         | 3.45%   |
| 5.15.0-0.rc7.20211028git1fc596a56b33.56.fc36.x86_64           | 1         | 3.45%   |
| 5.15.0-0.rc4.20211008git1da38549dd64.36.fc36.x86_64           | 1         | 3.45%   |
| 5.15.0-0.rc2.20210923git58e2cf5d7946.21.vanilla.1.fc36.x86_64 | 1         | 3.45%   |
| 5.15.0-0.rc2.18.fc36.x86_64                                   | 1         | 3.45%   |
| 5.14.14-300.fc35.x86_64                                       | 1         | 3.45%   |
| 5.14.10-300.fc35.x86_64                                       | 1         | 3.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17.1  | 12        | 41.38%  |
| 5.17.0  | 9         | 31.03%  |
| 5.15.0  | 4         | 13.79%  |
| 5.16.16 | 1         | 3.45%   |
| 5.16.0  | 1         | 3.45%   |
| 5.14.14 | 1         | 3.45%   |
| 5.14.10 | 1         | 3.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17    | 21        | 72.41%  |
| 5.15    | 4         | 13.79%  |
| 5.16    | 2         | 6.9%    |
| 5.14    | 2         | 6.9%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 28        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GNOME   | 22        | 75.86%  |
| KDE5    | 4         | 13.79%  |
| Unknown | 2         | 6.9%    |
| i3      | 1         | 3.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 21        | 75%     |
| X11     | 6         | 21.43%  |
| Unknown | 1         | 3.57%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 15        | 53.57%  |
| Unknown | 7         | 25%     |
| SDDM    | 4         | 14.29%  |
| LightDM | 2         | 7.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 16        | 57.14%  |
| pt_BR | 2         | 7.14%   |
| pl_PL | 2         | 7.14%   |
| en_GB | 2         | 7.14%   |
| de_DE | 2         | 7.14%   |
| pt_PT | 1         | 3.57%   |
| hr_HR | 1         | 3.57%   |
| fr_FR | 1         | 3.57%   |
| cs_CZ | 1         | 3.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 26        | 92.86%  |
| BIOS | 2         | 7.14%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 19        | 67.86%  |
| Ext4  | 7         | 25%     |
| Xfs   | 2         | 7.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 20        | 68.97%  |
| Unknown | 8         | 27.59%  |
| MBR     | 1         | 3.45%   |

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
| No        | 18        | 64.29%  |
| Yes       | 10        | 35.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 12        | 42.86%  |
| Dell                   | 3         | 10.71%  |
| Hewlett-Packard        | 2         | 7.14%   |
| Acer                   | 2         | 7.14%   |
| VALE                   | 1         | 3.57%   |
| Sony                   | 1         | 3.57%   |
| Positivo               | 1         | 3.57%   |
| Notebook               | 1         | 3.57%   |
| Framework              | 1         | 3.57%   |
| Chuwi                  | 1         | 3.57%   |
| Avell High Performance | 1         | 3.57%   |
| ASUSTek Computer       | 1         | 3.57%   |
| Unknown                | 1         | 3.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| VALE Notebook Slim S132                     | 1         | 3.57%   |
| Sony VGN-FW21E                              | 1         | 3.57%   |
| Positivo CHT12CP                            | 1         | 3.57%   |
| Notebook PCx0Dx                             | 1         | 3.57%   |
| Lenovo ThinkPad X260 20F5S0HK1J             | 1         | 3.57%   |
| Lenovo ThinkPad X1 Carbon 7th 20R1S05B00    | 1         | 3.57%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S0P    | 1         | 3.57%   |
| Lenovo ThinkPad P15 Gen 1 20STS0J500        | 1         | 3.57%   |
| Lenovo ThinkPad L13 Gen 2 20VJS0HB00        | 1         | 3.57%   |
| Lenovo ThinkBook 15 G2 ITL 20VE             | 1         | 3.57%   |
| Lenovo ThinkBook 14 G3 ACL 21A2             | 1         | 3.57%   |
| Lenovo ThinkBook 13s G3 ACN 20YA            | 1         | 3.57%   |
| Lenovo IdeaPadFlex 14 20308                 | 1         | 3.57%   |
| Lenovo IdeaPad Yoga 13 20175                | 1         | 3.57%   |
| Lenovo IdeaPad 530S-14ARR 81H1              | 1         | 3.57%   |
| Lenovo IdeaPad 320S-13IKB 81AK              | 1         | 3.57%   |
| HP ZBook Fury 15 G7 Mobile Workstation      | 1         | 3.57%   |
| HP ProBook 4740s                            | 1         | 3.57%   |
| Framework Laptop                            | 1         | 3.57%   |
| Dell XPS 17 9710                            | 1         | 3.57%   |
| Dell XPS 13 9333                            | 1         | 3.57%   |
| Dell Inspiron 5548                          | 1         | 3.57%   |
| Chuwi Hi10 Go                               | 1         | 3.57%   |
| Avell High Performance B.ON                 | 1         | 3.57%   |
| ASUS ROG Zephyrus Duo 15 SE GX551QS_GX551QS | 1         | 3.57%   |
| Acer Swift SF314-41                         | 1         | 3.57%   |
| Acer Aspire A515-45                         | 1         | 3.57%   |
| Unknown                                     | 1         | 3.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 5         | 17.86%  |
| Lenovo ThinkBook            | 3         | 10.71%  |
| Lenovo IdeaPad              | 3         | 10.71%  |
| Dell XPS                    | 2         | 7.14%   |
| VALE Notebook               | 1         | 3.57%   |
| Sony VGN-FW21E              | 1         | 3.57%   |
| Positivo CHT12CP            | 1         | 3.57%   |
| Notebook PCx0Dx             | 1         | 3.57%   |
| Lenovo IdeaPadFlex          | 1         | 3.57%   |
| HP ZBook                    | 1         | 3.57%   |
| HP ProBook                  | 1         | 3.57%   |
| Framework Laptop            | 1         | 3.57%   |
| Dell Inspiron               | 1         | 3.57%   |
| Chuwi Hi10                  | 1         | 3.57%   |
| Avell High Performance B.ON | 1         | 3.57%   |
| ASUS ROG                    | 1         | 3.57%   |
| Acer Swift                  | 1         | 3.57%   |
| Acer Aspire                 | 1         | 3.57%   |
| Unknown                     | 1         | 3.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 10        | 35.71%  |
| 2020 | 4         | 14.29%  |
| 2019 | 3         | 10.71%  |
| 2018 | 3         | 10.71%  |
| 2013 | 2         | 7.14%   |
| 2012 | 2         | 7.14%   |
| 2017 | 1         | 3.57%   |
| 2016 | 1         | 3.57%   |
| 2015 | 1         | 3.57%   |
| 2008 | 1         | 3.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 28        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 20        | 71.43%  |
| Enabled  | 8         | 28.57%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 28        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 8         | 28.57%  |
| 32.01-64.0  | 5         | 17.86%  |
| 3.01-4.0    | 5         | 17.86%  |
| 8.01-16.0   | 5         | 17.86%  |
| 16.01-24.0  | 4         | 14.29%  |
| 64.01-256.0 | 1         | 3.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 3.01-4.0 | 12        | 41.38%  |
| 2.01-3.0 | 8         | 27.59%  |
| 4.01-8.0 | 7         | 24.14%  |
| 1.01-2.0 | 2         | 6.9%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 21        | 72.41%  |
| 2      | 6         | 20.69%  |
| 3      | 2         | 6.9%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 26        | 92.86%  |
| Yes       | 2         | 7.14%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 53.57%  |
| No        | 13        | 46.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 96.43%  |
| No        | 1         | 3.57%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 82.14%  |
| No        | 5         | 17.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| USA        | 4         | 14.29%  |
| UK         | 4         | 14.29%  |
| Brazil     | 3         | 10.71%  |
| Poland     | 2         | 7.14%   |
| Italy      | 2         | 7.14%   |
| Uzbekistan | 1         | 3.57%   |
| Turkey     | 1         | 3.57%   |
| Slovakia   | 1         | 3.57%   |
| Romania    | 1         | 3.57%   |
| Norway     | 1         | 3.57%   |
| Nepal      | 1         | 3.57%   |
| Latvia     | 1         | 3.57%   |
| Germany    | 1         | 3.57%   |
| France     | 1         | 3.57%   |
| Estonia    | 1         | 3.57%   |
| Czechia    | 1         | 3.57%   |
| Croatia    | 1         | 3.57%   |
| Austria    | 1         | 3.57%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Zagreb                        | 1         | 3.57%   |
| Warsaw                        | 1         | 3.57%   |
| Warrington                    | 1         | 3.57%   |
| Vegarshei                     | 1         | 3.57%   |
| Trzciel                       | 1         | 3.57%   |
| Tashkent                      | 1         | 3.57%   |
| Tallinn                       | 1         | 3.57%   |
| Solihull                      | 1         | 3.57%   |
| Sao Paulo                     | 1         | 3.57%   |
| Rozmital pod Tremsinem        | 1         | 3.57%   |
| Riga                          | 1         | 3.57%   |
| Newport                       | 1         | 3.57%   |
| Mölten                       | 1         | 3.57%   |
| Marseille                     | 1         | 3.57%   |
| Macaiba                       | 1         | 3.57%   |
| Kathmandu                     | 1         | 3.57%   |
| Kasten bei Boeheimkirchen     | 1         | 3.57%   |
| Joinville                     | 1         | 3.57%   |
| Istanbul                      | 1         | 3.57%   |
| Halstead                      | 1         | 3.57%   |
| Fort Collins                  | 1         | 3.57%   |
| Folsom                        | 1         | 3.57%   |
| El Segundo                    | 1         | 3.57%   |
| Caldaro sulla Strada del Vino | 1         | 3.57%   |
| Bucharest                     | 1         | 3.57%   |
| Bratislava                    | 1         | 3.57%   |
| Berlin                        | 1         | 3.57%   |
| Beaverton                     | 1         | 3.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 10     | 22.86%  |
| WDC                 | 4         | 4      | 11.43%  |
| Unknown             | 4         | 6      | 11.43%  |
| SK Hynix            | 2         | 2      | 5.71%   |
| Kingston            | 2         | 4      | 5.71%   |
| A-DATA Technology   | 2         | 2      | 5.71%   |
| Unknown             | 2         | 2      | 5.71%   |
| Transcend           | 1         | 1      | 2.86%   |
| Toshiba             | 1         | 1      | 2.86%   |
| Seagate             | 1         | 1      | 2.86%   |
| SanDisk             | 1         | 1      | 2.86%   |
| PNY                 | 1         | 2      | 2.86%   |
| Phison              | 1         | 1      | 2.86%   |
| Leven               | 1         | 1      | 2.86%   |
| KIOXIA              | 1         | 1      | 2.86%   |
| Hitachi             | 1         | 1      | 2.86%   |
| Fujitsu             | 1         | 1      | 2.86%   |
| Crucial             | 1         | 1      | 2.86%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 1TB             | 2         | 5.56%   |
| Unknown                                | 2         | 5.56%   |
| WDC WDS500G1X0E-00AFY0 500GB           | 1         | 2.78%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1         | 2.78%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB   | 1         | 2.78%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB   | 1         | 2.78%   |
| Unknown SU32G  32GB                    | 1         | 2.78%   |
| Unknown MMC64G  64GB                   | 1         | 2.78%   |
| Unknown MMC Card  64GB                 | 1         | 2.78%   |
| Unknown ED2S5  128GB                   | 1         | 2.78%   |
| Transcend TS240GMTS420S 240GB SSD      | 1         | 2.78%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD    | 1         | 2.78%   |
| SK Hynix NVMe SSD Drive 256GB          | 1         | 2.78%   |
| SK Hynix HFM256GDHTNG-8310A 256GB      | 1         | 2.78%   |
| Seagate Expansion 500GB                | 1         | 2.78%   |
| SanDisk DF4032  32GB                   | 1         | 2.78%   |
| Samsung SSD 970 EVO Plus 500GB         | 1         | 2.78%   |
| Samsung SSD 860 EVO mSATA 500GB        | 1         | 2.78%   |
| Samsung SSD 860 EVO 250GB              | 1         | 2.78%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 1         | 2.78%   |
| Samsung NVMe SSD Drive 1024GB          | 1         | 2.78%   |
| Samsung MZMPC128HBFU-000L1 128GB SSD   | 1         | 2.78%   |
| Samsung MZALQ512HBLU-00BL2 512GB       | 1         | 2.78%   |
| PNY CS3040 4TB SSD                     | 1         | 2.78%   |
| Phison Sabrent 1TB                     | 1         | 2.78%   |
| Leven JAJS600M256C 256GB               | 1         | 2.78%   |
| KIOXIA KXG60ZNV1T02 1TB                | 1         | 2.78%   |
| Kingston SUV500MS240G 240GB SSD        | 1         | 2.78%   |
| Kingston SA400S37960G 960GB SSD        | 1         | 2.78%   |
| Hitachi HTS543232A7A384 320GB          | 1         | 2.78%   |
| Fujitsu MJA2500BH G1 500GB             | 1         | 2.78%   |
| Crucial CT1000P2SSD8 1TB               | 1         | 2.78%   |
| A-DATA IM2P33F8ABR2-256GB              | 1         | 2.78%   |
| A-DATA IM2P33F8ABR1-256GB              | 1         | 2.78%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 33.33%  |
| Hitachi | 1         | 1      | 33.33%  |
| Fujitsu | 1         | 1      | 33.33%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 37.5%   |
| Kingston            | 2         | 4      | 25%     |
| WDC                 | 1         | 1      | 12.5%   |
| Transcend           | 1         | 1      | 12.5%   |
| Leven               | 1         | 1      | 12.5%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 17        | 20     | 51.52%  |
| SSD  | 7         | 10     | 21.21%  |
| MMC  | 6         | 9      | 18.18%  |
| HDD  | 3         | 3      | 9.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 17        | 20     | 51.52%  |
| SATA | 9         | 12     | 27.27%  |
| MMC  | 6         | 9      | 18.18%  |
| SAS  | 1         | 1      | 3.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 8         | 12     | 88.89%  |
| 0.51-1.0   | 1         | 1      | 11.11%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 9         | 32.14%  |
| 251-500    | 6         | 21.43%  |
| 101-250    | 4         | 14.29%  |
| 1001-2000  | 3         | 10.71%  |
| 501-1000   | 3         | 10.71%  |
| 51-100     | 3         | 10.71%  |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 17        | 60.71%  |
| 51-100   | 4         | 14.29%  |
| 21-50    | 3         | 10.71%  |
| 501-1000 | 2         | 7.14%   |
| 251-500  | 1         | 3.57%   |
| 101-250  | 1         | 3.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                      | Notebooks | Drives | Percent |
|----------------------------|-----------|--------|---------|
| Fujitsu MJA2500BH G1 500GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Fujitsu | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Fujitsu | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 18        | 19     | 56.25%  |
| Detected | 13        | 22     | 40.63%  |
| Malfunc  | 1         | 1      | 3.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 14        | 42.42%  |
| Samsung Electronics          | 5         | 15.15%  |
| Sandisk                      | 3         | 9.09%   |
| Toshiba America Info Systems | 2         | 6.06%   |
| SK Hynix                     | 2         | 6.06%   |
| Phison Electronics           | 2         | 6.06%   |
| AMD                          | 2         | 6.06%   |
| ADATA Technology             | 2         | 6.06%   |
| Micron/Crucial Technology    | 1         | 3.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                            | 3         | 8.57%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                     | 2         | 5.71%   |
| Sandisk Non-Volatile memory controller                                   | 2         | 5.71%   |
| Samsung NVMe SSD Controller 980                                          | 2         | 5.71%   |
| Intel Volume Management Device NVMe RAID Controller                      | 2         | 5.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                       | 2         | 5.71%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                             | 2         | 5.71%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]         | 2         | 5.71%   |
| AMD FCH SATA Controller [AHCI mode]                                      | 2         | 5.71%   |
| ADATA Non-Volatile memory controller                                     | 2         | 5.71%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                              | 1         | 2.86%   |
| SK Hynix BC501 NVMe Solid State Drive                                    | 1         | 2.86%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                               | 1         | 2.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                           | 1         | 2.86%   |
| Phison E16 PCIe4 NVMe Controller                                         | 1         | 2.86%   |
| Phison E12 NVMe Controller                                               | 1         | 2.86%   |
| Micron/Crucial P2 NVMe PCIe SSD                                          | 1         | 2.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                       | 1         | 2.86%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                          | 1         | 2.86%   |
| Intel Jasper Lake SATA AHCI Controller                                   | 1         | 2.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                   | 1         | 2.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller | 1         | 2.86%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]    | 1         | 2.86%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                     | 1         | 2.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 17        | 50%     |
| SATA | 15        | 44.12%  |
| RAID | 2         | 5.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 22        | 78.57%  |
| AMD    | 6         | 21.43%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 10.71%  |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 3.57%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 3.57%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 3.57%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 3.57%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 3.57%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 3.57%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 3.57%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 3.57%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 3.57%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 3.57%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 3.57%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 3.57%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 1         | 3.57%   |
| Intel Celeron N5100 @ 1.10GHz                 | 1         | 3.57%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 3.57%   |
| Intel Celeron CPU J3455 @ 1.50GHz             | 1         | 3.57%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 3.57%   |
| Intel 11th Gen Core i9-11900H @ 2.50GHz       | 1         | 3.57%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 3.57%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1         | 3.57%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 3.57%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 1         | 3.57%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 3.57%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 3.57%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 1         | 3.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 7         | 25%     |
| Other            | 5         | 17.86%  |
| Intel Core i5    | 4         | 14.29%  |
| Intel Celeron    | 3         | 10.71%  |
| AMD Ryzen 5      | 3         | 10.71%  |
| Intel Pentium    | 1         | 3.57%   |
| Intel Core 2 Duo | 1         | 3.57%   |
| Intel Atom       | 1         | 3.57%   |
| AMD Ryzen 9      | 1         | 3.57%   |
| AMD Ryzen 7      | 1         | 3.57%   |
| AMD Ryzen 3      | 1         | 3.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 13        | 46.43%  |
| 2      | 7         | 25%     |
| 8      | 5         | 17.86%  |
| 6      | 3         | 10.71%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 28        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 22        | 78.57%  |
| 1      | 6         | 21.43%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 28        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 4         | 14.29%  |
| 0xa0652    | 3         | 10.71%  |
| 0x806ea    | 2         | 7.14%   |
| 0x40651    | 2         | 7.14%   |
| 0x306a9    | 2         | 7.14%   |
| 0x0a50000c | 2         | 7.14%   |
| 0xa0660    | 1         | 3.57%   |
| 0x906c0    | 1         | 3.57%   |
| 0x806d1    | 1         | 3.57%   |
| 0x706a8    | 1         | 3.57%   |
| 0x506c9    | 1         | 3.57%   |
| 0x406e3    | 1         | 3.57%   |
| 0x406c4    | 1         | 3.57%   |
| 0x306d4    | 1         | 3.57%   |
| 0x10676    | 1         | 3.57%   |
| 0x08608103 | 1         | 3.57%   |
| 0x08608102 | 1         | 3.57%   |
| 0x08108109 | 1         | 3.57%   |
| 0x0810100b | 1         | 3.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| TigerLake     | 4         | 14.29%  |
| CometLake     | 4         | 14.29%  |
| Zen 3         | 2         | 7.14%   |
| KabyLake      | 2         | 7.14%   |
| IvyBridge     | 2         | 7.14%   |
| Haswell       | 2         | 7.14%   |
| Unknown       | 2         | 7.14%   |
| Zen+          | 1         | 3.57%   |
| Zen           | 1         | 3.57%   |
| Tremont       | 1         | 3.57%   |
| Skylake       | 1         | 3.57%   |
| Silvermont    | 1         | 3.57%   |
| Penryn        | 1         | 3.57%   |
| Icelake       | 1         | 3.57%   |
| Goldmont plus | 1         | 3.57%   |
| Goldmont      | 1         | 3.57%   |
| Broadwell     | 1         | 3.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 21        | 60%     |
| AMD    | 8         | 22.86%  |
| Nvidia | 6         | 17.14%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 11.43%  |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 8.57%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 2         | 5.71%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 5.71%   |
| Intel UHD Graphics 620                                                                   | 2         | 5.71%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 5.71%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 5.71%   |
| AMD Lucienne                                                                             | 2         | 5.71%   |
| AMD Cezanne                                                                              | 2         | 5.71%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 2.86%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 1         | 2.86%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 2.86%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 2.86%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 2.86%   |
| Intel HD Graphics 5500                                                                   | 1         | 2.86%   |
| Intel HD Graphics 500                                                                    | 1         | 2.86%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 2.86%   |
| Intel Comet Lake UHD Graphics                                                            | 1         | 2.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.86%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 2.86%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 1         | 2.86%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 2.86%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 2.86%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 15        | 53.57%  |
| 1 x AMD        | 6         | 21.43%  |
| Intel + Nvidia | 5         | 17.86%  |
| Intel + AMD    | 1         | 3.57%   |
| AMD + Nvidia   | 1         | 3.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 26        | 89.66%  |
| Proprietary | 2         | 6.9%    |
| Unknown     | 1         | 3.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 60.71%  |
| 0.01-0.5   | 5         | 17.86%  |
| 1.01-2.0   | 4         | 14.29%  |
| 3.01-4.0   | 2         | 7.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| BOE                  | 6         | 21.43%  |
| LG Display           | 5         | 17.86%  |
| AU Optronics         | 5         | 17.86%  |
| InfoVision           | 3         | 10.71%  |
| Chimei Innolux       | 3         | 10.71%  |
| Sharp                | 2         | 7.14%   |
| Ancor Communications | 2         | 7.14%   |
| Samsung Electronics  | 1         | 3.57%   |
| Dell                 | 1         | 3.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch              | 1         | 3.45%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch              | 1         | 3.45%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch    | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SEC3554 1600x900 382x215mm 17.3-inch | 1         | 3.45%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch         | 1         | 3.45%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch         | 1         | 3.45%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch         | 1         | 3.45%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch          | 1         | 3.45%   |
| LG Display LCD Monitor LGD0360 1600x900 294x166mm 13.3-inch          | 1         | 3.45%   |
| InfoVision LCD Monitor IVO854A 1920x1200 286x179mm 13.3-inch         | 1         | 3.45%   |
| InfoVision LCD Monitor IVO3D40 1920x1080 344x194mm 15.5-inch         | 1         | 3.45%   |
| InfoVision LCD Monitor IVO0536 1920x1080 294x165mm 13.3-inch         | 1         | 3.45%   |
| Dell U2415 DELA0B8 1920x1200 518x324mm 24.1-inch                     | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch     | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch     | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN1345 1920x1080 293x165mm 13.2-inch     | 1         | 3.45%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 1         | 3.45%   |
| BOE LCD Monitor BOE0922 1920x550                                     | 1         | 3.45%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                | 1         | 3.45%   |
| BOE LCD Monitor BOE08F5 1920x1080 344x194mm 15.5-inch                | 1         | 3.45%   |
| BOE LCD Monitor BOE06FA 1920x1080 294x165mm 13.3-inch                | 1         | 3.45%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO4999 1920x1080 344x193mm 15.5-inch       | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch        | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO11EC 1366x768 344x193mm 15.5-inch        | 1         | 3.45%   |
| AU Optronics LCD Monitor AUO103C 1366x768 309x173mm 13.9-inch        | 1         | 3.45%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch     | 1         | 3.45%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch     | 1         | 3.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 17        | 60.71%  |
| 1366x768 (WXGA)   | 4         | 14.29%  |
| 1920x1200 (WUXGA) | 2         | 7.14%   |
| 1600x900 (HD+)    | 2         | 7.14%   |
| 3840x2400         | 1         | 3.57%   |
| 2256x1504         | 1         | 3.57%   |
| 1920x550          | 1         | 3.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 9         | 31.03%  |
| 15      | 8         | 27.59%  |
| 24      | 3         | 10.34%  |
| 14      | 3         | 10.34%  |
| 17      | 2         | 6.9%    |
| 23      | 1         | 3.45%   |
| 12      | 1         | 3.45%   |
| 11      | 1         | 3.45%   |
| Unknown | 1         | 3.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 14        | 48.28%  |
| 201-300     | 8         | 27.59%  |
| 501-600     | 4         | 13.79%  |
| 351-400     | 2         | 6.9%    |
| Unknown     | 1         | 3.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 22        | 81.48%  |
| 16/10 | 3         | 11.11%  |
| 32/9  | 1         | 3.7%    |
| 3/2   | 1         | 3.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 8         | 27.59%  |
| 81-90          | 7         | 24.14%  |
| 71-80          | 5         | 17.24%  |
| 201-250        | 3         | 10.34%  |
| 121-130        | 2         | 6.9%    |
| 61-70          | 1         | 3.45%   |
| 51-60          | 1         | 3.45%   |
| 251-300        | 1         | 3.45%   |
| Unknown        | 1         | 3.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 15        | 51.72%  |
| 161-240       | 5         | 17.24%  |
| 51-100        | 4         | 13.79%  |
| 101-120       | 3         | 10.34%  |
| More than 240 | 1         | 3.45%   |
| Unknown       | 1         | 3.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 22        | 75.86%  |
| 2     | 4         | 13.79%  |
| 0     | 3         | 10.34%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 21        | 56.76%  |
| Realtek Semiconductor    | 10        | 27.03%  |
| Qualcomm Atheros         | 3         | 8.11%   |
| MEDIATEK                 | 1         | 2.7%    |
| Marvell Technology Group | 1         | 2.7%    |
| Belkin Components        | 1         | 2.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 7         | 15.56%  |
| Intel Wi-Fi 6 AX201                                                | 3         | 6.67%   |
| Intel Wi-Fi 6 AX200                                                | 3         | 6.67%   |
| Intel Comet Lake PCH CNVi WiFi                                     | 3         | 6.67%   |
| Intel Wireless 7260                                                | 2         | 4.44%   |
| Intel Wireless 3165                                                | 2         | 4.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 1         | 2.22%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                             | 1         | 2.22%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter              | 1         | 2.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 1         | 2.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 1         | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 1         | 2.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 1         | 2.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 1         | 2.22%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter      | 1         | 2.22%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller            | 1         | 2.22%   |
| Intel Wireless 8265 / 8275                                         | 1         | 2.22%   |
| Intel Wireless 8260                                                | 1         | 2.22%   |
| Intel Wireless 3160                                                | 1         | 2.22%   |
| Intel WiFi Link 5100                                               | 1         | 2.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 1         | 2.22%   |
| Intel Tiger Lake PCH CNVi WiFi                                     | 1         | 2.22%   |
| Intel Ethernet Connection I219-LM                                  | 1         | 2.22%   |
| Intel Ethernet Connection (4) I219-LM                              | 1         | 2.22%   |
| Intel Ethernet Connection (13) I219-V                              | 1         | 2.22%   |
| Intel Ethernet Connection (11) I219-LM                             | 1         | 2.22%   |
| Intel Ethernet Connection (10) I219-V                              | 1         | 2.22%   |
| Intel Ethernet Connection (10) I219-LM                             | 1         | 2.22%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                    | 1         | 2.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 1         | 2.22%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B] | 1         | 2.22%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 21        | 72.41%  |
| Realtek Semiconductor | 3         | 10.34%  |
| Qualcomm Atheros      | 3         | 10.34%  |
| MEDIATEK              | 1         | 3.45%   |
| Belkin Components     | 1         | 3.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                | 3         | 10.34%  |
| Intel Wi-Fi 6 AX200                                                | 3         | 10.34%  |
| Intel Comet Lake PCH CNVi WiFi                                     | 3         | 10.34%  |
| Intel Wireless 7260                                                | 2         | 6.9%    |
| Intel Wireless 3165                                                | 2         | 6.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 1         | 3.45%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                             | 1         | 3.45%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter              | 1         | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 1         | 3.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 1         | 3.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 1         | 3.45%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter      | 1         | 3.45%   |
| Intel Wireless 8265 / 8275                                         | 1         | 3.45%   |
| Intel Wireless 8260                                                | 1         | 3.45%   |
| Intel Wireless 3160                                                | 1         | 3.45%   |
| Intel WiFi Link 5100                                               | 1         | 3.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 1         | 3.45%   |
| Intel Tiger Lake PCH CNVi WiFi                                     | 1         | 3.45%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                    | 1         | 3.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 1         | 3.45%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B] | 1         | 3.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 8         | 53.33%  |
| Intel                    | 6         | 40%     |
| Marvell Technology Group | 1         | 6.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 43.75%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 6.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 6.25%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 6.25%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 6.25%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 6.25%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 6.25%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 6.25%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 6.25%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 6.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 64.29%  |
| Ethernet | 15        | 35.71%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 86.67%  |
| Ethernet | 4         | 13.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 15        | 53.57%  |
| 1     | 11        | 39.29%  |
| 0     | 2         | 7.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 20        | 71.43%  |
| Yes  | 8         | 28.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 78.26%  |
| Qualcomm Atheros Communications | 2         | 8.7%    |
| Lite-On Technology              | 2         | 8.7%    |
| Realtek Semiconductor           | 1         | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                         | 10        | 43.48%  |
| Intel Bluetooth wireless interface             | 4         | 17.39%  |
| Intel AX200 Bluetooth                          | 3         | 13.04%  |
| Realtek Bluetooth Radio                        | 1         | 4.35%   |
| Qualcomm Atheros  Bluetooth Device             | 1         | 4.35%   |
| Qualcomm Atheros Bluetooth USB Host Controller | 1         | 4.35%   |
| Lite-On Wireless_Device                        | 1         | 4.35%   |
| Lite-On Bluetooth Device                       | 1         | 4.35%   |
| Intel AX210 Bluetooth                          | 1         | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 21        | 58.33%  |
| AMD                 | 7         | 19.44%  |
| Nvidia              | 5         | 13.89%  |
| Texas Instruments   | 1         | 2.78%   |
| Plantronics         | 1         | 2.78%   |
| C-Media Electronics | 1         | 2.78%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                              | 6         | 13.64%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 4         | 9.09%   |
| Intel Sunrise Point-LP HD Audio                                     | 3         | 6.82%   |
| Intel Comet Lake PCH cAVS                                           | 3         | 6.82%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 3         | 6.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 2         | 4.55%   |
| Nvidia Audio device                                                 | 2         | 4.55%   |
| Intel Haswell-ULT HD Audio Controller                               | 2         | 4.55%   |
| Intel 8 Series HD Audio Controller                                  | 2         | 4.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 2         | 4.55%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 2         | 4.55%   |
| Texas Instruments PCM2903B Audio CODEC                              | 1         | 2.27%   |
| Plantronics Blackwire 325.1                                         | 1         | 2.27%   |
| Nvidia GA104 High Definition Audio Controller                       | 1         | 2.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller             | 1         | 2.27%   |
| Intel Tiger Lake-H HD Audio Controller                              | 1         | 2.27%   |
| Intel Jasper Lake HD Audio                                          | 1         | 2.27%   |
| Intel Comet Lake PCH-LP cAVS                                        | 1         | 2.27%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 1         | 2.27%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster   | 1         | 2.27%   |
| Intel Broadwell-U Audio Controller                                  | 1         | 2.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                      | 1         | 2.27%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                   | 1         | 2.27%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                | 1         | 2.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 26.92%  |
| SK Hynix            | 6         | 23.08%  |
| Micron Technology   | 3         | 11.54%  |
| Unknown (ABCD)      | 2         | 7.69%   |
| Unknown             | 2         | 7.69%   |
| Crucial             | 2         | 7.69%   |
| Silicon Power       | 1         | 3.85%   |
| Sesame              | 1         | 3.85%   |
| Patriot             | 1         | 3.85%   |
| A-DATA Technology   | 1         | 3.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 7.41%   |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                      | 1         | 3.7%    |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 3.7%    |
| SK Hynix RAM Module 32GB SODIMM DDR4 2667MT/s                    | 1         | 3.7%    |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 3.7%    |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 3.7%    |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 3.7%    |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 3.7%    |
| SK Hynix RAM H5TC8G63AMR-PBR 4GB SODIMM DDR3 1600MT/s            | 1         | 3.7%    |
| Silicon Power RAM SP016GBSFU266B02 16GB SODIMM DDR4 2667MT/s     | 1         | 3.7%    |
| Sesame RAM S939A2SGS-ITR 8GB SODIMM DDR3 1600MT/s                | 1         | 3.7%    |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 3.7%    |
| Samsung RAM M474A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 3.7%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 3.7%    |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 1         | 3.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 3.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 3.7%    |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 3.7%    |
| Patriot RAM PSD38G1600L2S 8GB SODIMM DDR3 1600MT/s               | 1         | 3.7%    |
| Micron RAM MT53E512M32D2NP-046 4GB Row Of Chips LPDDR4 4267MT/s  | 1         | 3.7%    |
| Micron RAM Module 3GB Row Of Chips LPDDR4 1867MT/s               | 1         | 3.7%    |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 3.7%    |
| Crucial RAM CT32G4SFD832A.C16FB 32GB SODIMM DDR4 3200MT/s        | 1         | 3.7%    |
| Crucial RAM CT16G4SFD8266.M16FJ 16GB SODIMM DDR4 2667MT/s        | 1         | 3.7%    |
| A-DATA RAM AD4S3200J4G22-B 4GB SODIMM DDR4 3200MT/s              | 1         | 3.7%    |
| A-DATA RAM 4JQA-0622AC 4GB SODIMM DDR4 3200MT/s                  | 1         | 3.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 9         | 42.86%  |
| LPDDR4 | 5         | 23.81%  |
| DDR3   | 4         | 19.05%  |
| LPDDR3 | 2         | 9.52%   |
| DDR2   | 1         | 4.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 16        | 72.73%  |
| Row Of Chips | 6         | 27.27%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 9         | 37.5%   |
| 8192  | 7         | 29.17%  |
| 32768 | 3         | 12.5%   |
| 16384 | 2         | 8.33%   |
| 2048  | 2         | 8.33%   |
| 3072  | 1         | 4.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 5         | 22.73%  |
| 2667    | 3         | 13.64%  |
| 2133    | 3         | 13.64%  |
| 1600    | 3         | 13.64%  |
| 4267    | 2         | 9.09%   |
| 2400    | 2         | 9.09%   |
| 3266    | 1         | 4.55%   |
| 1867    | 1         | 4.55%   |
| 1066    | 1         | 4.55%   |
| Unknown | 1         | 4.55%   |

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


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Chicony Electronics         | 4         | 16%     |
| Acer                        | 4         | 16%     |
| Realtek Semiconductor       | 3         | 12%     |
| IMC Networks                | 3         | 12%     |
| Syntek                      | 2         | 8%      |
| USB Camera                  | 1         | 4%      |
| Samsung Electronics         | 1         | 4%      |
| Ricoh                       | 1         | 4%      |
| Quanta                      | 1         | 4%      |
| Primax Electronics          | 1         | 4%      |
| Microdia                    | 1         | 4%      |
| Luxvisions Innotech Limited | 1         | 4%      |
| Lite-On Technology          | 1         | 4%      |
| Alcor Micro                 | 1         | 4%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 3         | 11.54%  |
| IMC Networks Integrated Camera           | 2         | 7.69%   |
| Acer Integrated Camera                   | 2         | 7.69%   |
| USB Camera USB Camera                    | 1         | 3.85%   |
| Syntek Lenovo EasyCamera                 | 1         | 3.85%   |
| Syntek Integrated Camera                 | 1         | 3.85%   |
| Samsung Galaxy A5 (MTP)                  | 1         | 3.85%   |
| Ricoh Sony Vaio Integrated Webcam        | 1         | 3.85%   |
| Realtek Integrated_Webcam_HD             | 1         | 3.85%   |
| Realtek Integrated Webcam                | 1         | 3.85%   |
| Realtek Front Camera                     | 1         | 3.85%   |
| Realtek Back Camera                      | 1         | 3.85%   |
| Quanta HD User Facing                    | 1         | 3.85%   |
| Primax HP HD Webcam [Fixed]              | 1         | 3.85%   |
| Microdia Integrated_Webcam_HD            | 1         | 3.85%   |
| Luxvisions Innotech Limited HP HD Camera | 1         | 3.85%   |
| Lite-On Integrated Camera                | 1         | 3.85%   |
| IMC Networks EasyCamera                  | 1         | 3.85%   |
| Chicony HD WebCam                        | 1         | 3.85%   |
| Alcor Micro USB 2.0 Camera               | 1         | 3.85%   |
| Acer Lenovo EasyCamera                   | 1         | 3.85%   |
| Acer BisonCam,NB Pro                     | 1         | 3.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 5         | 62.5%   |
| Validity Sensors           | 1         | 12.5%   |
| Shenzhen Goodix Technology | 1         | 12.5%   |
| LighTuning Technology      | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 2         | 25%     |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 12.5%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 12.5%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 12.5%   |
| Shenzhen Goodix  FingerPrint Device                       | 1         | 12.5%   |
| LighTuning EgisTec Touch Fingerprint Sensor               | 1         | 12.5%   |
| Unknown                                                   | 1         | 12.5%   |

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
| 0     | 13        | 44.83%  |
| 1     | 12        | 41.38%  |
| 3     | 2         | 6.9%    |
| 2     | 2         | 6.9%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 8         | 42.11%  |
| Graphics card         | 5         | 26.32%  |
| Multimedia controller | 3         | 15.79%  |
| Sound                 | 1         | 5.26%   |
| Net/wireless          | 1         | 5.26%   |
| Card reader           | 1         | 5.26%   |

