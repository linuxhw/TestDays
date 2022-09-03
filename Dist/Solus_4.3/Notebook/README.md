Solus 4.3 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Solus 4.3.

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E5470              | [8cd7ffad9e](https://linux-hardware.org/?probe=8cd7ffad9e) | Aug 08, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [76083d81dc](https://linux-hardware.org/?probe=76083d81dc) | Jul 30, 2022 |
| Acer          | Aspire A315-54              | [9e0bbc26f4](https://linux-hardware.org/?probe=9e0bbc26f4) | Jul 22, 2022 |
| AZW           | SEi                         | [7556cabcae](https://linux-hardware.org/?probe=7556cabcae) | Jul 07, 2022 |
| GPU Compan... | GWTC116-2                   | [d0c0f4f120](https://linux-hardware.org/?probe=d0c0f4f120) | Jul 06, 2022 |
| GPU Compan... | GWTC116-2                   | [9d0dd21c70](https://linux-hardware.org/?probe=9d0dd21c70) | Jul 06, 2022 |
| HP            | ProBook 450 G5              | [c4880f9bab](https://linux-hardware.org/?probe=c4880f9bab) | Jun 02, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [5330a5aa11](https://linux-hardware.org/?probe=5330a5aa11) | Jun 02, 2022 |
| HP            | ProBook 450 G5              | [7f8acf64cd](https://linux-hardware.org/?probe=7f8acf64cd) | May 31, 2022 |
| HP            | ProBook 450 G5              | [2fbbe84744](https://linux-hardware.org/?probe=2fbbe84744) | May 31, 2022 |
| Google        | Edgar                       | [fef9eeb5db](https://linux-hardware.org/?probe=fef9eeb5db) | May 02, 2022 |
| Lenovo        | Z50-70 20354                | [6d50395aee](https://linux-hardware.org/?probe=6d50395aee) | Apr 22, 2022 |
| Dell          | XPS 13 7390                 | [80c38b1425](https://linux-hardware.org/?probe=80c38b1425) | Apr 19, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [9391fc9592](https://linux-hardware.org/?probe=9391fc9592) | Mar 23, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [81ec123b24](https://linux-hardware.org/?probe=81ec123b24) | Mar 15, 2022 |
| Dell          | XPS 13 9380                 | [efc6123d49](https://linux-hardware.org/?probe=efc6123d49) | Mar 06, 2022 |
| Google        | Delbin                      | [fbf8763bd4](https://linux-hardware.org/?probe=fbf8763bd4) | Feb 05, 2022 |
| Acer          | Aspire A315-54              | [5eb9b9e574](https://linux-hardware.org/?probe=5eb9b9e574) | Jan 22, 2022 |
| Acer          | Swift SF114-34              | [15431686d8](https://linux-hardware.org/?probe=15431686d8) | Jan 06, 2022 |
| Toshiba       | TECRA R840                  | [753c7caef6](https://linux-hardware.org/?probe=753c7caef6) | Dec 27, 2021 |
| Sony          | VPCYB15AB                   | [780ef18db3](https://linux-hardware.org/?probe=780ef18db3) | Dec 13, 2021 |
| Dell          | Latitude 5580               | [a10f022f63](https://linux-hardware.org/?probe=a10f022f63) | Nov 26, 2021 |
| Framework     | Laptop                      | [7995a7a4de](https://linux-hardware.org/?probe=7995a7a4de) | Nov 18, 2021 |
| Dell          | Latitude E6220              | [09a75055c9](https://linux-hardware.org/?probe=09a75055c9) | Nov 12, 2021 |
| Framework     | Laptop                      | [72a07a2e81](https://linux-hardware.org/?probe=72a07a2e81) | Nov 11, 2021 |
| AZW           | SEi                         | [0e29003348](https://linux-hardware.org/?probe=0e29003348) | Oct 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c7f1620c1c](https://linux-hardware.org/?probe=c7f1620c1c) | Oct 05, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [f19ad7cba2](https://linux-hardware.org/?probe=f19ad7cba2) | Sep 16, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [1cca1c6ce5](https://linux-hardware.org/?probe=1cca1c6ce5) | Sep 13, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [888bf75e20](https://linux-hardware.org/?probe=888bf75e20) | Sep 13, 2021 |
| Acer          | Nitro AN515-45              | [5bad88330d](https://linux-hardware.org/?probe=5bad88330d) | Sep 01, 2021 |
| Dell          | Inspiron 1525               | [3f3cd9c9e2](https://linux-hardware.org/?probe=3f3cd9c9e2) | Aug 25, 2021 |
| Dell          | Inspiron 1525               | [de3cb038ef](https://linux-hardware.org/?probe=de3cb038ef) | Aug 25, 2021 |
| Acer          | Nitro AN515-45              | [d98d816e7f](https://linux-hardware.org/?probe=d98d816e7f) | Aug 18, 2021 |
| Acer          | Nitro AN515-45              | [5320b136ea](https://linux-hardware.org/?probe=5320b136ea) | Aug 12, 2021 |
| Dell          | Vostro 15-3568              | [5f68a1fdaa](https://linux-hardware.org/?probe=5f68a1fdaa) | Aug 07, 2021 |
| HP            | ProBook 650 G2              | [15257858f3](https://linux-hardware.org/?probe=15257858f3) | Aug 07, 2021 |
| Dell          | Inspiron 15-3573            | [52916532a3](https://linux-hardware.org/?probe=52916532a3) | Aug 06, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [75ec31cefd](https://linux-hardware.org/?probe=75ec31cefd) | Jul 16, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 5.15.50-216.current | 4         | 14.81%  |
| 5.13.1-187.current  | 4         | 14.81%  |
| 5.15.32-213.current | 3         | 11.11%  |
| 5.14.21-210.current | 3         | 11.11%  |
| 5.14.16-205.current | 2         | 7.41%   |
| 5.13.6-190.current  | 2         | 7.41%   |
| 5.13.12-193.current | 2         | 7.41%   |
| 5.15.37-214.current | 1         | 3.7%    |
| 5.15.26-211.current | 1         | 3.7%    |
| 5.14.7-198.current  | 1         | 3.7%    |
| 5.14.16-204.current | 1         | 3.7%    |
| 5.14.15-203.current | 1         | 3.7%    |
| 5.14.12-201.current | 1         | 3.7%    |
| 5.13.15-194.current | 1         | 3.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.50 | 4         | 14.81%  |
| 5.13.1  | 4         | 14.81%  |
| 5.15.32 | 3         | 11.11%  |
| 5.14.21 | 3         | 11.11%  |
| 5.14.16 | 3         | 11.11%  |
| 5.13.6  | 2         | 7.41%   |
| 5.13.12 | 2         | 7.41%   |
| 5.15.37 | 1         | 3.7%    |
| 5.15.26 | 1         | 3.7%    |
| 5.14.7  | 1         | 3.7%    |
| 5.14.15 | 1         | 3.7%    |
| 5.14.12 | 1         | 3.7%    |
| 5.13.15 | 1         | 3.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 9         | 33.33%  |
| 5.14    | 9         | 33.33%  |
| 5.13    | 9         | 33.33%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 25        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Budgie  | 12        | 48%     |
| MATE    | 3         | 12%     |
| KDE5    | 3         | 12%     |
| Unknown | 3         | 12%     |
| KDE     | 2         | 8%      |
| GNOME   | 2         | 8%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 25        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 17        | 68%     |
| LightDM | 5         | 20%     |
| SDDM    | 2         | 8%      |
| GDM     | 1         | 4%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 17        | 68%     |
| en_GB | 3         | 12%     |
| de_DE | 2         | 8%      |
| pt_BR | 1         | 4%      |
| fr_FR | 1         | 4%      |
| en_IN | 1         | 4%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 20        | 74.07%  |
| BIOS | 7         | 25.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 24        | 96%     |
| Overlay | 1         | 4%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 17        | 68%     |
| GPT     | 7         | 28%     |
| MBR     | 1         | 4%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 96%     |
| Yes       | 1         | 4%      |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 20        | 80%     |
| Yes       | 5         | 20%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Dell             | 8         | 32%     |
| Lenovo           | 4         | 16%     |
| Acer             | 3         | 12%     |
| Hewlett-Packard  | 2         | 8%      |
| Google           | 2         | 8%      |
| Toshiba          | 1         | 4%      |
| Sony             | 1         | 4%      |
| GPU Company      | 1         | 4%      |
| Framework        | 1         | 4%      |
| AZW              | 1         | 4%      |
| ASUSTek Computer | 1         | 4%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Toshiba TECRA R840                     | 1         | 4%      |
| Sony VPCYB15AB                         | 1         | 4%      |
| Lenovo Z50-70 20354                    | 1         | 4%      |
| Lenovo ThinkPad T15 Gen 2i 20W4CTO1WW  | 1         | 4%      |
| Lenovo IdeaPad S340-15API 81NC         | 1         | 4%      |
| Lenovo IdeaPad 320-15ISK 80XH          | 1         | 4%      |
| HP ProBook 450 G5                      | 1         | 4%      |
| HP OMEN Laptop 15-en0xxx               | 1         | 4%      |
| GPU Company GWTC116-2                  | 1         | 4%      |
| Google Edgar                           | 1         | 4%      |
| Google Delbin                          | 1         | 4%      |
| Framework Laptop                       | 1         | 4%      |
| Dell XPS 13 9380                       | 1         | 4%      |
| Dell XPS 13 7390                       | 1         | 4%      |
| Dell Vostro 15-3568                    | 1         | 4%      |
| Dell Latitude E6220                    | 1         | 4%      |
| Dell Latitude E5470                    | 1         | 4%      |
| Dell Latitude 5580                     | 1         | 4%      |
| Dell Inspiron 1525                     | 1         | 4%      |
| Dell Inspiron 15-3573                  | 1         | 4%      |
| AZW SEi                                | 1         | 4%      |
| ASUS VivoBook_ASUSLaptop X509DA_M509DA | 1         | 4%      |
| Acer Swift SF114-34                    | 1         | 4%      |
| Acer Nitro AN515-45                    | 1         | 4%      |
| Acer Aspire A315-54                    | 1         | 4%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 3         | 12%     |
| Lenovo IdeaPad        | 2         | 8%      |
| Dell XPS              | 2         | 8%      |
| Dell Inspiron         | 2         | 8%      |
| Toshiba TECRA         | 1         | 4%      |
| Sony VPCYB15AB        | 1         | 4%      |
| Lenovo Z50-70         | 1         | 4%      |
| Lenovo ThinkPad       | 1         | 4%      |
| HP ProBook            | 1         | 4%      |
| HP OMEN               | 1         | 4%      |
| GPU Company GWTC116-2 | 1         | 4%      |
| Google Edgar          | 1         | 4%      |
| Google Delbin         | 1         | 4%      |
| Framework Laptop      | 1         | 4%      |
| Dell Vostro           | 1         | 4%      |
| AZW SEi               | 1         | 4%      |
| ASUS VivoBook         | 1         | 4%      |
| Acer Swift            | 1         | 4%      |
| Acer Nitro            | 1         | 4%      |
| Acer Aspire           | 1         | 4%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 5         | 20%     |
| 2019 | 5         | 20%     |
| 2020 | 3         | 12%     |
| 2017 | 3         | 12%     |
| 2018 | 2         | 8%      |
| 2016 | 2         | 8%      |
| 2011 | 2         | 8%      |
| 2014 | 1         | 4%      |
| 2010 | 1         | 4%      |
| 2008 | 1         | 4%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 25        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 25        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 23        | 92%     |
| Yes  | 2         | 8%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 7         | 28%     |
| 3.01-4.0   | 5         | 20%     |
| 32.01-64.0 | 4         | 16%     |
| 16.01-24.0 | 4         | 16%     |
| 8.01-16.0  | 3         | 12%     |
| 2.01-3.0   | 1         | 4%      |
| 1.01-2.0   | 1         | 4%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 12        | 44.44%  |
| 1.01-2.0 | 8         | 29.63%  |
| 4.01-8.0 | 3         | 11.11%  |
| 3.01-4.0 | 3         | 11.11%  |
| 0.51-1.0 | 1         | 3.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 20        | 80%     |
| 2      | 5         | 20%     |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 20        | 80%     |
| Yes       | 5         | 20%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 16        | 64%     |
| No        | 9         | 36%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 84%     |
| No        | 4         | 16%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 6         | 24%     |
| India       | 3         | 12%     |
| UK          | 2         | 8%      |
| Netherlands | 2         | 8%      |
| Brazil      | 2         | 8%      |
| Vietnam     | 1         | 4%      |
| Ukraine     | 1         | 4%      |
| Switzerland | 1         | 4%      |
| Poland      | 1         | 4%      |
| Norway      | 1         | 4%      |
| Nepal       | 1         | 4%      |
| Germany     | 1         | 4%      |
| France      | 1         | 4%      |
| Belgium     | 1         | 4%      |
| Australia   | 1         | 4%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Yverdon-les-Bains        | 1         | 3.85%   |
| Wendell                  | 1         | 3.85%   |
| Vineland                 | 1         | 3.85%   |
| Vasco da Gama            | 1         | 3.85%   |
| Stare Babice             | 1         | 3.85%   |
| Saint-Just-Saint-Rambert | 1         | 3.85%   |
| Red Oak                  | 1         | 3.85%   |
| Pomeroy                  | 1         | 3.85%   |
| Oslo                     | 1         | 3.85%   |
| Mohali                   | 1         | 3.85%   |
| Milwaukee                | 1         | 3.85%   |
| Melbourne                | 1         | 3.85%   |
| Lviv                     | 1         | 3.85%   |
| Linter                   | 1         | 3.85%   |
| Kathmandu                | 1         | 3.85%   |
| Ilford                   | 1         | 3.85%   |
| Hanoi                    | 1         | 3.85%   |
| Groningen                | 1         | 3.85%   |
| Greenwich                | 1         | 3.85%   |
| Goiânia                 | 1         | 3.85%   |
| Essen                    | 1         | 3.85%   |
| Coimbatore               | 1         | 3.85%   |
| Chelmsford               | 1         | 3.85%   |
| Belo Horizonte           | 1         | 3.85%   |
| Anacortes                | 1         | 3.85%   |
| Amsterdam                | 1         | 3.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 12.5%   |
| SK hynix            | 4         | 4      | 12.5%   |
| SanDisk             | 4         | 6      | 12.5%   |
| Unknown             | 3         | 3      | 9.38%   |
| Samsung Electronics | 3         | 4      | 9.38%   |
| Intel               | 3         | 4      | 9.38%   |
| Toshiba             | 2         | 2      | 6.25%   |
| Seagate             | 2         | 2      | 6.25%   |
| Silicon Motion      | 1         | 1      | 3.13%   |
| SABRENT             | 1         | 1      | 3.13%   |
| PNY                 | 1         | 1      | 3.13%   |
| Phison              | 1         | 1      | 3.13%   |
| KIOXIA              | 1         | 1      | 3.13%   |
| Kingston            | 1         | 1      | 3.13%   |
| Advantech           | 1         | 1      | 3.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| SK hynix NVMe SSD Drive 128GB          | 2         | 5.88%   |
| SanDisk NVMe SSD Drive 256GB           | 2         | 5.88%   |
| WDC WD3200BEVT-75ZCT2 320GB            | 1         | 2.94%   |
| WDC WD10SPZX-24Z10T0 1TB               | 1         | 2.94%   |
| WDC WD10SPZX-24Z10 1TB                 | 1         | 2.94%   |
| WDC WD10JPCX-24UE4T0 1TB               | 1         | 2.94%   |
| Unknown USB DISK 3.2 1TB               | 1         | 2.94%   |
| Unknown MMC Card  64GB                 | 1         | 2.94%   |
| Unknown MMC Card  128GB                | 1         | 2.94%   |
| Toshiba MQ01ABF050 500GB               | 1         | 2.94%   |
| Toshiba KXG60ZNV512G NVMe 512GB        | 1         | 2.94%   |
| SK hynix NVMe SSD Drive 500GB          | 1         | 2.94%   |
| SK hynix NVMe SSD Drive 256GB          | 1         | 2.94%   |
| Silicon Motion NVMe SSD Drive 512GB    | 1         | 2.94%   |
| Seagate ST1000LM049-2GH172 1TB         | 1         | 2.94%   |
| Seagate ST1000LM035-1RK172 1TB         | 1         | 2.94%   |
| SanDisk NVMe SSD Drive 1TB             | 1         | 2.94%   |
| SanDisk Extreme Pro 1TB                | 1         | 2.94%   |
| SanDisk DF4032  32GB                   | 1         | 2.94%   |
| Samsung SSD 850 EVO 250GB              | 1         | 2.94%   |
| Samsung NVMe SSD Drive 512GB           | 1         | 2.94%   |
| Samsung NVMe SSD Drive 2TB             | 1         | 2.94%   |
| Samsung MZVL22T0HBLB-00BL7 2TB         | 1         | 2.94%   |
| SABRENT Disk 480GB                     | 1         | 2.94%   |
| PNY CS900 240GB SSD                    | 1         | 2.94%   |
| Phison NVMe SSD Drive 512GB            | 1         | 2.94%   |
| KIOXIA KXG60ZNV512G NVMe 512GB         | 1         | 2.94%   |
| Kingston SA400S37240G 240GB SSD        | 1         | 2.94%   |
| Intel SSDPEKKW512G7 512GB              | 1         | 2.94%   |
| Intel NVMe SSD Drive 512GB             | 1         | 2.94%   |
| Intel NVMe SSD Drive 256GB             | 1         | 2.94%   |
| Advantech SQF-S25M8-128G-AAG 128GB SSD | 1         | 2.94%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 50%     |
| Seagate | 2         | 2      | 25%     |
| Toshiba | 1         | 1      | 12.5%   |
| SABRENT | 1         | 1      | 12.5%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 25%     |
| PNY                 | 1         | 1      | 25%     |
| Kingston            | 1         | 1      | 25%     |
| Advantech           | 1         | 1      | 25%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 14        | 20     | 46.67%  |
| HDD     | 8         | 8      | 26.67%  |
| SSD     | 4         | 4      | 13.33%  |
| MMC     | 3         | 3      | 10%     |
| Unknown | 1         | 1      | 3.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 14        | 20     | 46.67%  |
| SATA | 11        | 11     | 36.67%  |
| MMC  | 3         | 3      | 10%     |
| SAS  | 2         | 2      | 6.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 6         | 7      | 54.55%  |
| 0.51-1.0   | 5         | 5      | 45.45%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 9         | 34.62%  |
| 501-1000   | 7         | 26.92%  |
| 251-500    | 6         | 23.08%  |
| 21-50      | 2         | 7.69%   |
| 51-100     | 2         | 7.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 11        | 39.29%  |
| 21-50   | 8         | 28.57%  |
| 51-100  | 4         | 14.29%  |
| 251-500 | 3         | 10.71%  |
| 101-250 | 2         | 7.14%   |

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
| Detected | 20        | 29     | 74.07%  |
| Works    | 7         | 7      | 25.93%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 14        | 43.75%  |
| AMD                          | 5         | 15.63%  |
| SK hynix                     | 4         | 12.5%   |
| SanDisk                      | 3         | 9.38%   |
| Toshiba America Info Systems | 2         | 6.25%   |
| Samsung Electronics          | 2         | 6.25%   |
| Silicon Motion               | 1         | 3.13%   |
| Phison Electronics           | 1         | 3.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 4         | 11.43%  |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 2         | 5.71%   |
| SK hynix BC501 NVMe Solid State Drive                                         | 2         | 5.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 2         | 5.71%   |
| Intel SSD 600P Series                                                         | 2         | 5.71%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2         | 5.71%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 2         | 5.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 2         | 5.71%   |
| SK hynix PC300 NVMe Solid State Drive 256GB                                   | 1         | 2.86%   |
| SK hynix Gold P31 SSD                                                         | 1         | 2.86%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                               | 1         | 2.86%   |
| SanDisk WD Blue SN550 NVMe SSD                                                | 1         | 2.86%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                     | 1         | 2.86%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                               | 1         | 2.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 1         | 2.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1         | 2.86%   |
| Phison PS5013 E13 NVMe Controller                                             | 1         | 2.86%   |
| Intel SSD 660P Series                                                         | 1         | 2.86%   |
| Intel Comet Lake SATA AHCI Controller                                         | 1         | 2.86%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 1         | 2.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                 | 1         | 2.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                              | 1         | 2.86%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 1         | 2.86%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 1         | 2.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 1         | 2.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 17        | 51.52%  |
| NVMe | 14        | 42.42%  |
| RAID | 1         | 3.03%   |
| IDE  | 1         | 3.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 20        | 80%     |
| AMD    | 5         | 20%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 8%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 8%      |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 4%      |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 4%      |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 4%      |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 4%      |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 4%      |
| Intel Core i5-8259U CPU @ 2.30GHz             | 1         | 4%      |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 4%      |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 4%      |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 4%      |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 4%      |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 4%      |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 4%      |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 4%      |
| Intel Celeron CPU 540 @ 1.86GHz               | 1         | 4%      |
| Intel Atom x5-E8000 CPU @ 1.04GHz             | 1         | 4%      |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 4%      |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 4%      |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 4%      |
| AMD Ryzen 5 5600H with Radeon Graphics        | 1         | 4%      |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 4%      |
| AMD E-350 Processor                           | 1         | 4%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 6         | 24%     |
| Intel Core i5        | 5         | 20%     |
| Other                | 3         | 12%     |
| Intel Celeron        | 3         | 12%     |
| AMD Ryzen 7          | 2         | 8%      |
| AMD Ryzen 5          | 2         | 8%      |
| Intel Pentium Silver | 1         | 4%      |
| Intel Core i3        | 1         | 4%      |
| Intel Atom           | 1         | 4%      |
| AMD E                | 1         | 4%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 13        | 52%     |
| 2      | 9         | 36%     |
| 8      | 1         | 4%      |
| 6      | 1         | 4%      |
| 1      | 1         | 4%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 25        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 19        | 76%     |
| 1      | 6         | 24%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 25        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 3         | 11.54%  |
| 0x806c1    | 3         | 11.54%  |
| Unknown    | 3         | 11.54%  |
| 0x806ea    | 2         | 7.69%   |
| 0x206a7    | 2         | 7.69%   |
| 0x906e9    | 1         | 3.85%   |
| 0x906c0    | 1         | 3.85%   |
| 0x706a8    | 1         | 3.85%   |
| 0x706a1    | 1         | 3.85%   |
| 0x506e3    | 1         | 3.85%   |
| 0x406e3    | 1         | 3.85%   |
| 0x40651    | 1         | 3.85%   |
| 0x10661    | 1         | 3.85%   |
| 0x0a50000c | 1         | 3.85%   |
| 0x08600106 | 1         | 3.85%   |
| 0x08108109 | 1         | 3.85%   |
| 0x08108102 | 1         | 3.85%   |
| 0x05000029 | 1         | 3.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 7         | 28%     |
| TigerLake     | 3         | 12%     |
| Zen+          | 2         | 8%      |
| Skylake       | 2         | 8%      |
| SandyBridge   | 2         | 8%      |
| Goldmont plus | 2         | 8%      |
| Zen 3         | 1         | 4%      |
| Zen 2         | 1         | 4%      |
| Tremont       | 1         | 4%      |
| Silvermont    | 1         | 4%      |
| Haswell       | 1         | 4%      |
| Core          | 1         | 4%      |
| Bobcat        | 1         | 4%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 19        | 61.29%  |
| AMD    | 7         | 22.58%  |
| Nvidia | 5         | 16.13%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 6.25%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 6.25%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 6.25%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 6.25%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 3.13%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 3.13%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 3.13%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 3.13%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 3.13%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 3.13%   |
| Intel UHD Graphics 620                                                                   | 1         | 3.13%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 3.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 3.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 3.13%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 3.13%   |
| Intel HD Graphics 630                                                                    | 1         | 3.13%   |
| Intel HD Graphics 620                                                                    | 1         | 3.13%   |
| Intel HD Graphics 530                                                                    | 1         | 3.13%   |
| Intel HD Graphics 520                                                                    | 1         | 3.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 3.13%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 1         | 3.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 3.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 3.13%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 3.13%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 3.13%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 3.13%   |
| AMD Renoir                                                                               | 1         | 3.13%   |
| AMD Cezanne                                                                              | 1         | 3.13%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 15        | 60%     |
| 1 x AMD        | 4         | 16%     |
| Intel + Nvidia | 3         | 12%     |
| AMD + Nvidia   | 2         | 8%      |
| Intel + AMD    | 1         | 4%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 21        | 84%     |
| Proprietary | 4         | 16%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 64%     |
| 1.01-2.0   | 4         | 16%     |
| 0.01-0.5   | 2         | 8%      |
| 5.01-6.0   | 1         | 4%      |
| 3.01-4.0   | 1         | 4%      |
| 0.51-1.0   | 1         | 4%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 7         | 23.33%  |
| BOE                     | 5         | 16.67%  |
| AU Optronics            | 4         | 13.33%  |
| Samsung Electronics     | 3         | 10%     |
| LG Display              | 2         | 6.67%   |
| Ancor Communications    | 2         | 6.67%   |
| Toshiba                 | 1         | 3.33%   |
| Philips                 | 1         | 3.33%   |
| PANDA                   | 1         | 3.33%   |
| Lenovo                  | 1         | 3.33%   |
| CSO                     | 1         | 3.33%   |
| Chi Mei Optoelectronics | 1         | 3.33%   |
| Acer                    | 1         | 3.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Toshiba Internal LCD TOS5091 1366x768 344x193mm 15.5-inch                | 1         | 3.23%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 3.23%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 1         | 3.23%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch        | 1         | 3.23%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 600x340mm 27.2-inch        | 1         | 3.23%   |
| Philips 273PLPH PHL08A8 1920x1080 598x336mm 27.0-inch                    | 1         | 3.23%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                  | 1         | 3.23%   |
| LG Display LCD Monitor LGD06FB 1920x1080 309x174mm 14.0-inch             | 1         | 3.23%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch             | 1         | 3.23%   |
| Lenovo D22-10 LEN65E4 1920x1080 476x268mm 21.5-inch                      | 1         | 3.23%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                    | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 344x193mm 15.5-inch         | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch         | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch          | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 1         | 3.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO1113 1366x768 256x144mm 11.6-inch | 1         | 3.23%   |
| BOE NV116WHM-T16 BOE0956 1366x768 256x144mm 11.6-inch                    | 1         | 3.23%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 1         | 3.23%   |
| BOE LCD Monitor BOE06CB 1920x1080 344x194mm 15.5-inch                    | 1         | 3.23%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 1         | 3.23%   |
| BOE LCD Monitor BOE0653 1920x1080 309x173mm 13.9-inch                    | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch            | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO282B 3840x2160 293x165mm 13.2-inch           | 1         | 3.23%   |
| Ancor Communications C624B ACI24A9 1920x1200 518x324mm 24.1-inch         | 1         | 3.23%   |
| Ancor Communications ASUS VS229 ACI22D3 1920x1080 475x267mm 21.5-inch    | 1         | 3.23%   |
| Acer K242HYL ACR064A 1920x1080 527x296mm 23.8-inch                       | 1         | 3.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 13        | 46.43%  |
| 1366x768 (WXGA)   | 10        | 35.71%  |
| 3840x2160 (4K)    | 2         | 7.14%   |
| 2256x1504         | 1         | 3.57%   |
| 1920x1200 (WUXGA) | 1         | 3.57%   |
| 1280x800 (WXGA)   | 1         | 3.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 16        | 53.33%  |
| 13     | 5         | 16.67%  |
| 27     | 2         | 6.67%   |
| 21     | 2         | 6.67%   |
| 11     | 2         | 6.67%   |
| 24     | 1         | 3.33%   |
| 23     | 1         | 3.33%   |
| 14     | 1         | 3.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 18        | 60%     |
| 201-300     | 5         | 16.67%  |
| 501-600     | 4         | 13.33%  |
| 401-500     | 2         | 6.67%   |
| 351-400     | 1         | 3.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 23        | 88.46%  |
| 16/10 | 2         | 7.69%   |
| 3/2   | 1         | 3.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 16        | 53.33%  |
| 81-90          | 4         | 13.33%  |
| 71-80          | 2         | 6.67%   |
| 51-60          | 2         | 6.67%   |
| 301-350        | 2         | 6.67%   |
| 201-250        | 2         | 6.67%   |
| 251-300        | 1         | 3.33%   |
| 151-200        | 1         | 3.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 11        | 39.29%  |
| 101-120       | 8         | 28.57%  |
| 51-100        | 5         | 17.86%  |
| More than 240 | 2         | 7.14%   |
| 161-240       | 2         | 7.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 20        | 80%     |
| 2     | 4         | 16%     |
| 3     | 1         | 4%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 13        | 37.14%  |
| Realtek Semiconductor    | 10        | 28.57%  |
| Qualcomm Atheros         | 6         | 17.14%  |
| TP-Link                  | 1         | 2.86%   |
| T & A Mobile Phones      | 1         | 2.86%   |
| MediaTek                 | 1         | 2.86%   |
| Marvell Technology Group | 1         | 2.86%   |
| Dell                     | 1         | 2.86%   |
| Broadcom                 | 1         | 2.86%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 16.28%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 6.98%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 6.98%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 4.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4.65%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 2.33%   |
| T & A Mobile Phones 5087Z                                         | 1         | 2.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.33%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.33%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 2.33%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 2.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 2.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 2.33%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 2.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 2.33%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 2.33%   |
| Intel Wireless 8265 / 8275                                        | 1         | 2.33%   |
| Intel Wireless 8260                                               | 1         | 2.33%   |
| Intel Wireless 7265                                               | 1         | 2.33%   |
| Intel Wireless 3165                                               | 1         | 2.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 2.33%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 1         | 2.33%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 2.33%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.33%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 2.33%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 2.33%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 1         | 2.33%   |
| Dell DW5550                                                       | 1         | 2.33%   |
| Broadcom BCM4311 802.11b/g WLAN                                   | 1         | 2.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 52%     |
| Qualcomm Atheros      | 6         | 24%     |
| Realtek Semiconductor | 4         | 16%     |
| MediaTek              | 1         | 4%      |
| Broadcom              | 1         | 4%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 12%     |
| Intel Wi-Fi 6 AX200                                            | 3         | 12%     |
| Intel Wi-Fi 6 AX201                                            | 2         | 8%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 4%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 4%      |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 4%      |
| Realtek 802.11n WLAN Adapter                                   | 1         | 4%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 4%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 4%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 4%      |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 4%      |
| Intel Wireless 8265 / 8275                                     | 1         | 4%      |
| Intel Wireless 8260                                            | 1         | 4%      |
| Intel Wireless 7265                                            | 1         | 4%      |
| Intel Wireless 3165                                            | 1         | 4%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 4%      |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1         | 4%      |
| Intel Centrino Ultimate-N 6300                                 | 1         | 4%      |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 1         | 4%      |
| Broadcom BCM4311 802.11b/g WLAN                                | 1         | 4%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 8         | 50%     |
| Intel                    | 5         | 31.25%  |
| TP-Link                  | 1         | 6.25%   |
| Qualcomm Atheros         | 1         | 6.25%   |
| Marvell Technology Group | 1         | 6.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 43.75%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 12.5%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 6.25%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 6.25%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 6.25%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 6.25%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 6.25%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 6.25%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 6.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 25        | 58.14%  |
| Ethernet | 16        | 37.21%  |
| Modem    | 1         | 2.33%   |
| Unknown  | 1         | 2.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 20        | 80%     |
| Ethernet | 5         | 20%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 15        | 60%     |
| 1     | 9         | 36%     |
| 0     | 1         | 4%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 18        | 72%     |
| Yes  | 7         | 28%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 52.38%  |
| Qualcomm Atheros Communications | 3         | 14.29%  |
| Realtek Semiconductor           | 2         | 9.52%   |
| Lite-On Technology              | 2         | 9.52%   |
| IMC Networks                    | 1         | 4.76%   |
| Foxconn / Hon Hai               | 1         | 4.76%   |
| Dell                            | 1         | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface         | 4         | 19.05%  |
| Intel AX201 Bluetooth                      | 3         | 14.29%  |
| Intel AX200 Bluetooth                      | 3         | 14.29%  |
| Qualcomm Atheros  Bluetooth Device         | 2         | 9.52%   |
| Realtek RTL8821A Bluetooth                 | 1         | 4.76%   |
| Realtek  Bluetooth 4.2 Adapter             | 1         | 4.76%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0      | 1         | 4.76%   |
| Lite-On Wireless_Device                    | 1         | 4.76%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth | 1         | 4.76%   |
| Intel AX210 Bluetooth                      | 1         | 4.76%   |
| IMC Networks Bluetooth Radio               | 1         | 4.76%   |
| Foxconn / Hon Hai Bluetooth Device         | 1         | 4.76%   |
| Dell DW375 Bluetooth Module                | 1         | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 20        | 64.52%  |
| AMD                 | 6         | 19.35%  |
| Nvidia              | 3         | 9.68%   |
| Samsung Electronics | 1         | 3.23%   |
| Conexant Systems    | 1         | 3.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 11.43%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 8.57%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 8.57%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 5.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 5.71%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 5.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 5.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 5.71%   |
| Samsung Electronics USBC Headset                                                                  | 1         | 2.86%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 2.86%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 2.86%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 2.86%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 2.86%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 2.86%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 2.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.86%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2.86%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 2.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 2.86%   |
| Conexant Systems Hi-Res Audio                                                                     | 1         | 2.86%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 2.86%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 2.86%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 2.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 5         | 33.33%  |
| SK hynix            | 3         | 20%     |
| Micron Technology   | 2         | 13.33%  |
| Unknown             | 1         | 6.67%   |
| Team                | 1         | 6.67%   |
| G.Skill             | 1         | 6.67%   |
| Crucial             | 1         | 6.67%   |
| A-DATA Technology   | 1         | 6.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 6.67%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 6.67%   |
| SK hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 6.67%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 6.67%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 6.67%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 6.67%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 6.67%   |
| Samsung RAM M471A2G43AB2-CWE 16384MB SODIMM DDR4 3200MT/s        | 1         | 6.67%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 6.67%   |
| Samsung RAM K4E8E324EB-EGCF 2GB SODIMM LPDDR3 1867MT/s           | 1         | 6.67%   |
| Micron RAM 8HTF12864HDY-667E1 1GB SODIMM DDR2 667MT/s            | 1         | 6.67%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16384MB SODIMM DDR4 3200MT/s         | 1         | 6.67%   |
| G.Skill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s           | 1         | 6.67%   |
| Crucial RAM CT16G4SFD8213.C16FBD 16GB SODIMM DDR4 2133MT/s       | 1         | 6.67%   |
| A-DATA RAM Module 8192MB SODIMM DDR4 2133MT/s                    | 1         | 6.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 6         | 46.15%  |
| LPDDR3 | 3         | 23.08%  |
| LPDDR4 | 1         | 7.69%   |
| DDR3   | 1         | 7.69%   |
| DDR2   | 1         | 7.69%   |
| DDR    | 1         | 7.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 9         | 75%     |
| Row Of Chips | 3         | 25%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 4         | 33.33%  |
| 16384 | 3         | 25%     |
| 4096  | 3         | 25%     |
| 32768 | 1         | 8.33%   |
| 1024  | 1         | 8.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2133    | 4         | 30.77%  |
| 3200    | 3         | 23.08%  |
| 4267    | 1         | 7.69%   |
| 2667    | 1         | 7.69%   |
| 1867    | 1         | 7.69%   |
| 1333    | 1         | 7.69%   |
| 667     | 1         | 7.69%   |
| Unknown | 1         | 7.69%   |

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
| Realtek Semiconductor                  | 4         | 18.18%  |
| Quanta                                 | 4         | 18.18%  |
| Sunplus Innovation Technology          | 3         | 13.64%  |
| Microdia                               | 3         | 13.64%  |
| IMC Networks                           | 2         | 9.09%   |
| Chicony Electronics                    | 2         | 9.09%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 9.09%   |
| Logitech                               | 1         | 4.55%   |
| Acer                                   | 1         | 4.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                    | 2         | 9.09%   |
| Quanta HD User Facing                                           | 2         | 9.09%   |
| Microdia Integrated_Webcam_HD                                   | 2         | 9.09%   |
| Sunplus Laptop_Integrated_Webcam_HD                             | 1         | 4.55%   |
| Realtek Laptop Camera                                           | 1         | 4.55%   |
| Realtek Integrated Webcam_HD                                    | 1         | 4.55%   |
| Realtek Integrated Webcam                                       | 1         | 4.55%   |
| Realtek HD WebCam                                               | 1         | 4.55%   |
| Quanta VGA WebCam                                               | 1         | 4.55%   |
| Quanta USB2.0 HD UVC WebCam                                     | 1         | 4.55%   |
| Microdia USB 2.0 Camera                                         | 1         | 4.55%   |
| Logitech Webcam C270                                            | 1         | 4.55%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 1         | 4.55%   |
| IMC Networks Integrated Camera                                  | 1         | 4.55%   |
| Chicony Sony Visual Communication Camera                        | 1         | 4.55%   |
| Chicony EasyCamera                                              | 1         | 4.55%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 1         | 4.55%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 4.55%   |
| Acer Lenovo EasyCamera                                          | 1         | 4.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 50%     |
| Synaptics        | 1         | 25%     |
| AuthenTec        | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 25%     |
| Validity Sensors VFS Fingerprint sensor           | 1         | 25%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 25%     |
| AuthenTec Fingerprint Sensor                      | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 50%     |
| O2 Micro    | 1         | 25%     |
| Alcor Micro | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 25%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 25%     |
| Broadcom 5880                                  | 1         | 25%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 16        | 64%     |
| 1     | 5         | 20%     |
| 2     | 4         | 16%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 4         | 26.67%  |
| Chipcard              | 4         | 26.67%  |
| Net/wireless          | 3         | 20%     |
| Multimedia controller | 2         | 13.33%  |
| Unassigned class      | 1         | 6.67%   |
| Storage               | 1         | 6.67%   |

