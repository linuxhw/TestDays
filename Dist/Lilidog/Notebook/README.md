Lilidog - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Lilidog.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 30

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 435                         | [cb02103775](https://linux-hardware.org/?probe=cb02103775) | Aug 17, 2023 |
| HP            | Laptop 15s-fq1xxx           | [f495796fe8](https://linux-hardware.org/?probe=f495796fe8) | Aug 03, 2023 |
| Panasonic     | CFMX4-1                     | [925f36396d](https://linux-hardware.org/?probe=925f36396d) | Jul 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [31b0d46f32](https://linux-hardware.org/?probe=31b0d46f32) | Jul 22, 2023 |
| Google        | Auron_Yuna                  | [abff7f6ed0](https://linux-hardware.org/?probe=abff7f6ed0) | Jul 19, 2023 |
| Dell          | Latitude E5440              | [9d0c95f893](https://linux-hardware.org/?probe=9d0c95f893) | Jul 18, 2023 |
| Dell          | Latitude 7414               | [184c56a43a](https://linux-hardware.org/?probe=184c56a43a) | Jul 01, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [18c2eb78d4](https://linux-hardware.org/?probe=18c2eb78d4) | Jun 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [f7a2bd2ca8](https://linux-hardware.org/?probe=f7a2bd2ca8) | Jun 10, 2023 |
| TUXEDO        | N8xEJEK                     | [28ca72e1e1](https://linux-hardware.org/?probe=28ca72e1e1) | Jun 05, 2023 |
| Google        | Sand                        | [e6d70635d6](https://linux-hardware.org/?probe=e6d70635d6) | May 30, 2023 |
| HP            | G62                         | [68f5984aa8](https://linux-hardware.org/?probe=68f5984aa8) | May 11, 2023 |
| Google        | Sand                        | [044ac39e57](https://linux-hardware.org/?probe=044ac39e57) | Apr 11, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [061b0673b4](https://linux-hardware.org/?probe=061b0673b4) | Mar 12, 2023 |
| Apple         | MacBookPro3,1               | [266ef88c0c](https://linux-hardware.org/?probe=266ef88c0c) | Jan 25, 2023 |
| Apple         | MacBookPro3,1               | [910de59ed9](https://linux-hardware.org/?probe=910de59ed9) | Jan 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d64272e554](https://linux-hardware.org/?probe=d64272e554) | Dec 03, 2022 |
| Dell          | Latitude 7390               | [9278bcc6a2](https://linux-hardware.org/?probe=9278bcc6a2) | Nov 27, 2022 |
| Acer          | Aspire 7540                 | [8e80ccea19](https://linux-hardware.org/?probe=8e80ccea19) | Oct 01, 2022 |
| Acer          | V5-131                      | [7a218d1ae7](https://linux-hardware.org/?probe=7a218d1ae7) | Sep 14, 2022 |
| Dell          | Inspiron 3793               | [66f5acc518](https://linux-hardware.org/?probe=66f5acc518) | Sep 10, 2022 |
| Lenovo        | G500 20236                  | [5846b57c77](https://linux-hardware.org/?probe=5846b57c77) | Aug 09, 2022 |
| Acer          | Aspire E5-573               | [d5f490187d](https://linux-hardware.org/?probe=d5f490187d) | Jul 19, 2022 |
| Acer          | V5-131                      | [620f2657d4](https://linux-hardware.org/?probe=620f2657d4) | Jul 07, 2022 |
| Panasonic     | CF-31ATXAX1M                | [46be7cc40c](https://linux-hardware.org/?probe=46be7cc40c) | Jul 06, 2022 |
| Acer          | AOD255E                     | [01c9e4194b](https://linux-hardware.org/?probe=01c9e4194b) | Jul 06, 2022 |
| Acer          | AOD255E                     | [1737f8b906](https://linux-hardware.org/?probe=1737f8b906) | Jun 26, 2022 |
| GPU Compan... | GWNR71517                   | [89a074e539](https://linux-hardware.org/?probe=89a074e539) | Jun 02, 2022 |
| Lenovo        | ThinkPad T400 6474WPU       | [ce7e91802e](https://linux-hardware.org/?probe=ce7e91802e) | May 03, 2022 |
| Dell          | Inspiron 3793               | [3df5028c64](https://linux-hardware.org/?probe=3df5028c64) | Apr 10, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Lilidog 22 | 16        | 61.54%  |
| Lilidog 23 | 10        | 38.46%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Lilidog | 25        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 6.1.0-9-amd64             | 5         | 17.24%  |
| 5.10.0-15-amd64           | 4         | 13.79%  |
| 6.1.0-10-amd64            | 3         | 10.34%  |
| 5.10.0-16-amd64           | 3         | 10.34%  |
| 5.10.0-21-amd64           | 2         | 6.9%    |
| 5.10.0-18-amd64           | 2         | 6.9%    |
| 6.4.5-1-liquorix-amd64    | 1         | 3.45%   |
| 6.1.0-7-amd64             | 1         | 3.45%   |
| 6.1.0-11-amd64            | 1         | 3.45%   |
| 6.1.0-0.deb11.6-amd64     | 1         | 3.45%   |
| 6.0.10-x64v1-xanmod1      | 1         | 3.45%   |
| 6.0.0-0.deb11.2-amd64     | 1         | 3.45%   |
| 5.17.0-5.1-liquorix-amd64 | 1         | 3.45%   |
| 5.10.0-22-amd64           | 1         | 3.45%   |
| 5.10.0-14-amd64           | 1         | 3.45%   |
| 5.10.0-13-amd64           | 1         | 3.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 12        | 46.15%  |
| 6.1.0   | 10        | 38.46%  |
| 6.4.5   | 1         | 3.85%   |
| 6.0.10  | 1         | 3.85%   |
| 6.0.0   | 1         | 3.85%   |
| 5.17.0  | 1         | 3.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 12        | 46.15%  |
| 6.1     | 10        | 38.46%  |
| 6.0     | 2         | 7.69%   |
| 6.4     | 1         | 3.85%   |
| 5.17    | 1         | 3.85%   |

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


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| lightdm-xsession | 22        | 84.62%  |
| openbox          | 4         | 15.38%  |

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
| LightDM | 25        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 17        | 65.38%  |
| de_DE | 4         | 15.38%  |
| es_ES | 2         | 7.69%   |
| es_CL | 1         | 3.85%   |
| en_IE | 1         | 3.85%   |
| cs_CZ | 1         | 3.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 13        | 52%     |
| EFI  | 12        | 48%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 16        | 64%     |
| Overlay | 8         | 32%     |
| Btrfs   | 1         | 4%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| MBR  | 13        | 52%     |
| GPT  | 12        | 48%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 16        | 59.26%  |
| Yes       | 11        | 40.74%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 21        | 84%     |
| Yes       | 4         | 16%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 5         | 20%     |
| Acer             | 5         | 20%     |
| Dell             | 4         | 16%     |
| Hewlett-Packard  | 3         | 12%     |
| Panasonic        | 2         | 8%      |
| Google           | 2         | 8%      |
| TUXEDO           | 1         | 4%      |
| GPU Company      | 1         | 4%      |
| ASUSTek Computer | 1         | 4%      |
| Apple            | 1         | 4%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Acer AOD255E                               | 2         | 8%      |
| TUXEDO N8xEJEK                             | 1         | 4%      |
| Panasonic CFMX4-1                          | 1         | 4%      |
| Panasonic CF-31ATXAX1M                     | 1         | 4%      |
| Lenovo Yoga Slim 7 14ARE05 82A2            | 1         | 4%      |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 1         | 4%      |
| Lenovo ThinkPad X1 Carbon 4th 20FCS24900   | 1         | 4%      |
| Lenovo ThinkPad T400 6474WPU               | 1         | 4%      |
| Lenovo G500 20236                          | 1         | 4%      |
| HP Laptop 15s-fq1xxx                       | 1         | 4%      |
| HP G62                                     | 1         | 4%      |
| HP 435                                     | 1         | 4%      |
| GPU Company GWNR71517                      | 1         | 4%      |
| Google Sand                                | 1         | 4%      |
| Google Auron_Yuna                          | 1         | 4%      |
| Dell Latitude E5440                        | 1         | 4%      |
| Dell Latitude 7414                         | 1         | 4%      |
| Dell Latitude 7390                         | 1         | 4%      |
| Dell Inspiron 3793                         | 1         | 4%      |
| ASUS VivoBook 15_ASUS Laptop X560UD        | 1         | 4%      |
| Apple MacBookPro3,1                        | 1         | 4%      |
| Acer V5-131                                | 1         | 4%      |
| Acer Aspire E5-573                         | 1         | 4%      |
| Acer Aspire 7540                           | 1         | 4%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 3         | 12%     |
| Dell Latitude          | 3         | 12%     |
| Acer Aspire            | 2         | 8%      |
| Acer AOD255E           | 2         | 8%      |
| TUXEDO N8xEJEK         | 1         | 4%      |
| Panasonic CFMX4-1      | 1         | 4%      |
| Panasonic CF-31ATXAX1M | 1         | 4%      |
| Lenovo Yoga            | 1         | 4%      |
| Lenovo G500            | 1         | 4%      |
| HP Laptop              | 1         | 4%      |
| HP G62                 | 1         | 4%      |
| HP 435                 | 1         | 4%      |
| GPU Company GWNR71517  | 1         | 4%      |
| Google Sand            | 1         | 4%      |
| Google Auron           | 1         | 4%      |
| Dell Inspiron          | 1         | 4%      |
| ASUS VivoBook          | 1         | 4%      |
| Apple MacBookPro3      | 1         | 4%      |
| Acer V5-131            | 1         | 4%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 4         | 16%     |
| 2010 | 4         | 16%     |
| 2021 | 2         | 8%      |
| 2020 | 2         | 8%      |
| 2019 | 2         | 8%      |
| 2013 | 2         | 8%      |
| 2017 | 1         | 4%      |
| 2016 | 1         | 4%      |
| 2015 | 1         | 4%      |
| 2014 | 1         | 4%      |
| 2012 | 1         | 4%      |
| 2011 | 1         | 4%      |
| 2009 | 1         | 4%      |
| 2008 | 1         | 4%      |
| 2007 | 1         | 4%      |

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
| Disabled | 24        | 96%     |
| Enabled  | 1         | 4%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 22        | 88%     |
| Yes  | 3         | 12%     |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 8         | 32%     |
| 3.01-4.0   | 8         | 32%     |
| 16.01-24.0 | 3         | 12%     |
| 1.01-2.0   | 2         | 8%      |
| 8.01-16.0  | 2         | 8%      |
| 32.01-64.0 | 1         | 4%      |
| 0.51-1.0   | 1         | 4%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.51-1.0 | 15        | 57.69%  |
| 1.01-2.0 | 8         | 30.77%  |
| 2.01-3.0 | 3         | 11.54%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 22        | 84.62%  |
| 2      | 4         | 15.38%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 17        | 68%     |
| Yes       | 8         | 32%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 72%     |
| No        | 7         | 28%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 96%     |
| No        | 1         | 4%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 72%     |
| No        | 7         | 28%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| USA      | 9         | 36%     |
| Germany  | 6         | 24%     |
| Spain    | 3         | 12%     |
| Vietnam  | 1         | 4%      |
| Thailand | 1         | 4%      |
| Portugal | 1         | 4%      |
| Kenya    | 1         | 4%      |
| Italy    | 1         | 4%      |
| Czechia  | 1         | 4%      |
| Chile    | 1         | 4%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Fayetteville           | 3         | 12%     |
| Egan                   | 2         | 8%      |
| Denver                 | 2         | 8%      |
| Viña del Mar          | 1         | 4%      |
| Uelzen                 | 1         | 4%      |
| Rinteln                | 1         | 4%      |
| Ratchathewi            | 1         | 4%      |
| Poricany               | 1         | 4%      |
| Nairobi                | 1         | 4%      |
| Morgantown             | 1         | 4%      |
| Milan                  | 1         | 4%      |
| Madrid                 | 1         | 4%      |
| Lisbon                 | 1         | 4%      |
| Ho Chi Minh City       | 1         | 4%      |
| Filderstadt            | 1         | 4%      |
| Eppelborn              | 1         | 4%      |
| Düsseldorf            | 1         | 4%      |
| Darmstadt              | 1         | 4%      |
| Charlotte              | 1         | 4%      |
| Cervera del Rio Alhama | 1         | 4%      |
| Barcelona              | 1         | 4%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 9      | 25%     |
| Toshiba             | 3         | 4      | 10.71%  |
| Seagate             | 3         | 4      | 10.71%  |
| SanDisk             | 2         | 3      | 7.14%   |
| Kingston            | 2         | 2      | 7.14%   |
| Wibtek              | 1         | 1      | 3.57%   |
| WDC                 | 1         | 1      | 3.57%   |
| Unknown             | 1         | 1      | 3.57%   |
| Mushkin             | 1         | 1      | 3.57%   |
| Micron Technology   | 1         | 2      | 3.57%   |
| Lexar               | 1         | 1      | 3.57%   |
| KIOXIA              | 1         | 1      | 3.57%   |
| Hitachi             | 1         | 1      | 3.57%   |
| Crucial             | 1         | 1      | 3.57%   |
| China               | 1         | 1      | 3.57%   |
| Apacer              | 1         | 1      | 3.57%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Wibtek W800S 512GB SSD               | 1         | 3.45%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 3.45%   |
| Unknown NCard  32GB                  | 1         | 3.45%   |
| Toshiba MQ04ABF100 1TB               | 1         | 3.45%   |
| Toshiba MK6034GSX 64GB               | 1         | 3.45%   |
| Toshiba MK1665GSX 160GB              | 1         | 3.45%   |
| Seagate ST9320325AS 320GB            | 1         | 3.45%   |
| Seagate ST9250315AS 250GB            | 1         | 3.45%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 3.45%   |
| SanDisk SD8TN8U256G1001 256GB SSD    | 1         | 3.45%   |
| SanDisk DF4032  32GB                 | 1         | 3.45%   |
| Samsung SSD PM841 2.5 7mm 256GB      | 1         | 3.45%   |
| Samsung SSD 970 EVO Plus 250GB       | 1         | 3.45%   |
| Samsung SSD 860 EVO 500GB            | 1         | 3.45%   |
| Samsung SSD 860 EVO 1TB              | 1         | 3.45%   |
| Samsung SSD 850 EVO 250GB            | 1         | 3.45%   |
| Samsung PM991a NVMe 512GB            | 1         | 3.45%   |
| Samsung MZVL21T0HCLR-00BL7 1TB       | 1         | 3.45%   |
| Samsung MZNTE128HMGR-00000 128GB SSD | 1         | 3.45%   |
| Mushkin MKNSSDCR120GB                | 1         | 3.45%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 1         | 3.45%   |
| Lexar SSD NM620 256GB                | 1         | 3.45%   |
| KIOXIA KBG40ZNV1T02 1TB              | 1         | 3.45%   |
| Kingston SNS4151S332GD 32GB SSD      | 1         | 3.45%   |
| Kingston SKC3000D2048G 2TB           | 1         | 3.45%   |
| Hitachi HTS545016B9SA00 160GB        | 1         | 3.45%   |
| Crucial CT480BX500SSD1 480GB         | 1         | 3.45%   |
| China SSD 120GB                      | 1         | 3.45%   |
| Apacer AS350 512GB SSD               | 1         | 3.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 4      | 37.5%   |
| Seagate | 3         | 4      | 37.5%   |
| WDC     | 1         | 1      | 12.5%   |
| Hitachi | 1         | 1      | 12.5%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 38.46%  |
| Wibtek              | 1         | 1      | 7.69%   |
| SanDisk             | 1         | 1      | 7.69%   |
| Mushkin             | 1         | 1      | 7.69%   |
| Micron Technology   | 1         | 2      | 7.69%   |
| Kingston            | 1         | 1      | 7.69%   |
| Crucial             | 1         | 1      | 7.69%   |
| China               | 1         | 1      | 7.69%   |
| Apacer              | 1         | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 13        | 14     | 46.43%  |
| HDD  | 8         | 10     | 28.57%  |
| NVMe | 6         | 7      | 21.43%  |
| MMC  | 1         | 3      | 3.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 19        | 24     | 73.08%  |
| NVMe | 6         | 7      | 23.08%  |
| MMC  | 1         | 3      | 3.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 16        | 19     | 80%     |
| 0.51-1.0   | 4         | 5      | 20%     |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 8         | 30.77%  |
| 251-500    | 7         | 26.92%  |
| 101-250    | 5         | 19.23%  |
| 21-50      | 2         | 7.69%   |
| 51-100     | 2         | 7.69%   |
| 1001-2000  | 1         | 3.85%   |
| 501-1000   | 1         | 3.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 23        | 88.46%  |
| 21-50   | 3         | 11.54%  |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Toshiba MK1665GSX 160GB         | 1         | 1      | 20%     |
| Seagate ST9250315AS 250GB       | 1         | 1      | 20%     |
| Seagate ST500LT012-9WS142 500GB | 1         | 2      | 20%     |
| Mushkin MKNSSDCR120GB           | 1         | 1      | 20%     |
| Kingston SNS4151S332GD 32GB SSD | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 2         | 3      | 40%     |
| Toshiba  | 1         | 1      | 20%     |
| Mushkin  | 1         | 1      | 20%     |
| Kingston | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 3      | 66.67%  |
| Toshiba | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 4      | 60%     |
| SSD  | 2         | 2      | 40%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 19        | 24     | 73.08%  |
| Malfunc  | 5         | 6      | 19.23%  |
| Detected | 1         | 3      | 3.85%   |
| Failed   | 1         | 1      | 3.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 18        | 66.67%  |
| Samsung Electronics          | 3         | 11.11%  |
| AMD                          | 3         | 11.11%  |
| Shenzhen Longsys Electronics | 1         | 3.7%    |
| KIOXIA                       | 1         | 3.7%    |
| Kingston Technology Company  | 1         | 3.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                    | 3         | 10%     |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                    | 2         | 6.67%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                    | 2         | 6.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                        | 2         | 6.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                     | 2         | 6.67%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                     | 1         | 3.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                         | 1         | 3.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                        | 1         | 3.33%   |
| Samsung NVMe SSD Controller 980                                       | 1         | 3.33%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                            | 1         | 3.33%   |
| Kingston Company KC3000/Renegade NVMe SSD                             | 1         | 3.33%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                         | 1         | 3.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                     | 1         | 3.33%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode] | 1         | 3.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]         | 1         | 3.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                      | 1         | 3.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                          | 1         | 3.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]      | 1         | 3.33%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]       | 1         | 3.33%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]       | 1         | 3.33%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller        | 1         | 3.33%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller        | 1         | 3.33%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                  | 1         | 3.33%   |
| AMD FCH SATA Controller [AHCI mode]                                   | 1         | 3.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 18        | 62.07%  |
| NVMe | 6         | 20.69%  |
| IDE  | 3         | 10.34%  |
| RAID | 2         | 6.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 21        | 84%     |
| AMD    | 4         | 16%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 8%      |
| Intel Atom CPU N455 @ 1.66GHz                 | 2         | 8%      |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 4%      |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 4%      |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 4%      |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 4%      |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 4%      |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 4%      |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 4%      |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 4%      |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 4%      |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 4%      |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 4%      |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 4%      |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 4%      |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 1         | 4%      |
| Intel Celeron CPU 1007U @ 1.50GHz             | 1         | 4%      |
| Intel Celeron 3205U @ 1.50GHz                 | 1         | 4%      |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 4%      |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 4%      |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 4%      |
| AMD Phenom II N830 Triple-Core Processor      | 1         | 4%      |
| AMD Athlon II Dual-Core M300                  | 1         | 4%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 7         | 28%     |
| Intel Core i7           | 5         | 20%     |
| Intel Pentium           | 2         | 8%      |
| Intel Core 2 Duo        | 2         | 8%      |
| Intel Celeron           | 2         | 8%      |
| Intel Atom              | 2         | 8%      |
| Other                   | 1         | 4%      |
| AMD Ryzen 7             | 1         | 4%      |
| AMD Ryzen 5             | 1         | 4%      |
| AMD Phenom II           | 1         | 4%      |
| AMD Athlon II Dual-Core | 1         | 4%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 13        | 52%     |
| 4      | 7         | 28%     |
| 6      | 2         | 8%      |
| 1      | 2         | 8%      |
| 3      | 1         | 4%      |

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
| 2      | 16        | 64%     |
| 1      | 9         | 36%     |

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
| Unknown    | 3         | 12%     |
| 0x806ea    | 2         | 8%      |
| 0x406e3    | 2         | 8%      |
| 0x40651    | 2         | 8%      |
| 0x306d4    | 2         | 8%      |
| 0x306a9    | 2         | 8%      |
| 0x106ca    | 2         | 8%      |
| 0x906ea    | 1         | 4%      |
| 0x806c1    | 1         | 4%      |
| 0x706e5    | 1         | 4%      |
| 0x6fa      | 1         | 4%      |
| 0x506c9    | 1         | 4%      |
| 0x20655    | 1         | 4%      |
| 0x10676    | 1         | 4%      |
| 0x08600106 | 1         | 4%      |
| 0x08108109 | 1         | 4%      |
| 0x010000c8 | 1         | 4%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KabyLake  | 3         | 12%     |
| Westmere  | 2         | 8%      |
| Skylake   | 2         | 8%      |
| K10       | 2         | 8%      |
| IvyBridge | 2         | 8%      |
| IceLake   | 2         | 8%      |
| Haswell   | 2         | 8%      |
| Broadwell | 2         | 8%      |
| Bonnell   | 2         | 8%      |
| Zen+      | 1         | 4%      |
| Zen 2     | 1         | 4%      |
| TigerLake | 1         | 4%      |
| Penryn    | 1         | 4%      |
| Goldmont  | 1         | 4%      |
| Core      | 1         | 4%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 20        | 68.97%  |
| AMD    | 6         | 20.69%  |
| Nvidia | 3         | 10.34%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                  | 2         | 6.9%    |
| Intel Skylake GT2 [HD Graphics 520]                                     | 2         | 6.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                        | 2         | 6.9%    |
| Intel Core Processor Integrated Graphics Controller                     | 2         | 6.9%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller | 2         | 6.9%    |
| Intel 3rd Gen Core processor Graphics Controller                        | 2         | 6.9%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                              | 1         | 3.45%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                 | 1         | 3.45%   |
| Nvidia G84M [GeForce 8600M GT]                                          | 1         | 3.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                               | 1         | 3.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller            | 1         | 3.45%   |
| Intel Iris Plus Graphics G7                                             | 1         | 3.45%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                  | 1         | 3.45%   |
| Intel HD Graphics 5500                                                  | 1         | 3.45%   |
| Intel HD Graphics                                                       | 1         | 3.45%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                               | 1         | 3.45%   |
| Intel Apollo Lake [HD Graphics 505]                                     | 1         | 3.45%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]        | 1         | 3.45%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                               | 1         | 3.45%   |
| AMD Renoir                                                              | 1         | 3.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]    | 1         | 3.45%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                            | 1         | 3.45%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                        | 1         | 3.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 16        | 64%     |
| 1 x AMD        | 4         | 16%     |
| Intel + Nvidia | 2         | 8%      |
| Intel + AMD    | 2         | 8%      |
| 1 x Nvidia     | 1         | 4%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 24        | 96%     |
| Unknown | 1         | 4%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 68%     |
| 0.01-0.5   | 5         | 20%     |
| 3.01-4.0   | 2         | 8%      |
| 1.01-2.0   | 1         | 4%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 9         | 37.5%   |
| LG Display              | 4         | 16.67%  |
| Chimei Innolux          | 4         | 16.67%  |
| BOE                     | 2         | 8.33%   |
| Sharp                   | 1         | 4.17%   |
| Lenovo                  | 1         | 4.17%   |
| JDI                     | 1         | 4.17%   |
| Chi Mei Optoelectronics | 1         | 4.17%   |
| AOC                     | 1         | 4.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 8.33%   |
| Sharp LCD Monitor SHP1416 1366x768 309x174mm 14.0-inch                   | 1         | 4.17%   |
| LG Display LP101WSB-TLN1 LGD026E 1024x600 224x126mm 10.1-inch            | 1         | 4.17%   |
| LG Display LCD Monitor LGD0479 1920x1080 309x174mm 14.0-inch             | 1         | 4.17%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 1         | 4.17%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 1         | 4.17%   |
| Lenovo LCD Monitor LEN4037 1280x800 303x190mm 14.1-inch                  | 1         | 4.17%   |
| JDI LAM125M007D JDI1402 1920x1080 277x156mm 12.5-inch                    | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN1382 1920x1080 293x165mm 13.2-inch         | 1         | 4.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 1         | 4.17%   |
| BOE LCD Monitor BOE0A06 1920x1080 344x194mm 15.5-inch                    | 1         | 4.17%   |
| BOE LCD Monitor BOE05F6 1366x768 309x173mm 13.9-inch                     | 1         | 4.17%   |
| AU Optronics LCD Monitor AUOD291 1920x1200 301x188mm 14.0-inch           | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch           | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO60D2 1024x600 222x125mm 10.0-inch            | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch            | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO319D 1920x1080 382x214mm 17.2-inch           | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO30ED 1920x1080 340x190mm 15.3-inch           | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch           | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch            | 1         | 4.17%   |
| AOC 2219 AOC2219 1680x1050 474x296mm 22.0-inch                           | 1         | 4.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 10        | 41.67%  |
| 1366x768 (WXGA)    | 8         | 33.33%  |
| 1024x600           | 2         | 8.33%   |
| 1920x1200 (WUXGA)  | 1         | 4.17%   |
| 1680x1050 (WSXGA+) | 1         | 4.17%   |
| 1600x900 (HD+)     | 1         | 4.17%   |
| 1280x800 (WXGA)    | 1         | 4.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 8         | 33.33%  |
| 14     | 6         | 25%     |
| 17     | 3         | 12.5%   |
| 13     | 2         | 8.33%   |
| 10     | 2         | 8.33%   |
| 22     | 1         | 4.17%   |
| 12     | 1         | 4.17%   |
| 11     | 1         | 4.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 15        | 62.5%   |
| 201-300     | 5         | 20.83%  |
| 351-400     | 3         | 12.5%   |
| 401-500     | 1         | 4.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 21        | 87.5%   |
| 16/10 | 3         | 12.5%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 8         | 33.33%  |
| 81-90          | 7         | 29.17%  |
| 121-130        | 3         | 12.5%   |
| 41-50          | 2         | 8.33%   |
| 71-80          | 1         | 4.17%   |
| 61-70          | 1         | 4.17%   |
| 51-60          | 1         | 4.17%   |
| 201-250        | 1         | 4.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 10        | 41.67%  |
| 121-160 | 9         | 37.5%   |
| 161-240 | 3         | 12.5%   |
| 51-100  | 2         | 8.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 23        | 92%     |
| 2     | 1         | 4%      |
| 0     | 1         | 4%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 33.33%  |
| Qualcomm Atheros                | 10        | 25.64%  |
| Realtek Semiconductor           | 9         | 23.08%  |
| Broadcom                        | 5         | 12.82%  |
| Qualcomm Atheros Communications | 1         | 2.56%   |
| Marvell Technology Group        | 1         | 2.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 3         | 6.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 3         | 6.67%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 2         | 4.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 4.44%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                            | 2         | 4.44%   |
| Intel Wireless 8260                                                                   | 2         | 4.44%   |
| Intel Wireless 7260                                                                   | 2         | 4.44%   |
| Intel Ethernet Connection I219-LM                                                     | 2         | 4.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 4.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 2.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 2.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 1         | 2.22%   |
| Realtek 802.11ac NIC                                                                  | 1         | 2.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 2.22%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 2.22%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 2.22%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 2.22%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 2.22%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                               | 1         | 2.22%   |
| Intel Wireless-AC 9260                                                                | 1         | 2.22%   |
| Intel Wireless 8265 / 8275                                                            | 1         | 2.22%   |
| Intel Wireless 7265                                                                   | 1         | 2.22%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 2.22%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 2.22%   |
| Intel Ethernet Connection I218-LM                                                     | 1         | 2.22%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 1         | 2.22%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 1         | 2.22%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 2.22%   |
| Intel Centrino Advanced-N 6200                                                        | 1         | 2.22%   |
| Intel 82577LM Gigabit Network Connection                                              | 1         | 2.22%   |
| Intel 82567LM Gigabit Network Connection                                              | 1         | 2.22%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                       | 1         | 2.22%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                       | 1         | 2.22%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 1         | 2.22%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 42.31%  |
| Qualcomm Atheros                | 8         | 30.77%  |
| Realtek Semiconductor           | 3         | 11.54%  |
| Broadcom                        | 3         | 11.54%  |
| Qualcomm Atheros Communications | 1         | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 3         | 11.54%  |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 7.69%   |
| Intel Wireless 8260                                                                   | 2         | 7.69%   |
| Intel Wireless 7260                                                                   | 2         | 7.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 7.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 3.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 3.85%   |
| Realtek 802.11ac NIC                                                                  | 1         | 3.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 3.85%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 3.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 3.85%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 3.85%   |
| Intel Wireless-AC 9260                                                                | 1         | 3.85%   |
| Intel Wireless 8265 / 8275                                                            | 1         | 3.85%   |
| Intel Wireless 7265                                                                   | 1         | 3.85%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 3.85%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 3.85%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 3.85%   |
| Intel Centrino Advanced-N 6200                                                        | 1         | 3.85%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 1         | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 7         | 36.84%  |
| Realtek Semiconductor    | 6         | 31.58%  |
| Qualcomm Atheros         | 3         | 15.79%  |
| Broadcom                 | 2         | 10.53%  |
| Marvell Technology Group | 1         | 5.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 15.79%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2         | 10.53%  |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 10.53%  |
| Intel Ethernet Connection I219-LM                                 | 2         | 10.53%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 5.26%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 5.26%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 5.26%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 5.26%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 5.26%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 5.26%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 5.26%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 5.26%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 5.26%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 5.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 24        | 57.14%  |
| Ethernet | 18        | 42.86%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 16        | 64%     |
| Ethernet | 9         | 36%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 17        | 68%     |
| 1     | 7         | 28%     |
| 0     | 1         | 4%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 14        | 56%     |
| Yes  | 11        | 44%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 50%     |
| Qualcomm Atheros Communications | 3         | 16.67%  |
| Lite-On Technology              | 2         | 11.11%  |
| Realtek Semiconductor           | 1         | 5.56%   |
| IMC Networks                    | 1         | 5.56%   |
| Broadcom                        | 1         | 5.56%   |
| Apple                           | 1         | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 6         | 33.33%  |
| Qualcomm Atheros AR3011 Bluetooth                  | 2         | 11.11%  |
| Realtek Bluetooth Radio                            | 1         | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                 | 1         | 5.56%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth         | 1         | 5.56%   |
| Lite-On Atheros AR3012 Bluetooth                   | 1         | 5.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter           | 1         | 5.56%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 1         | 5.56%   |
| Intel AX201 Bluetooth                              | 1         | 5.56%   |
| IMC Networks Bluetooth Device                      | 1         | 5.56%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 5.56%   |
| Apple Bluetooth HCI MacBookPro (HID mode)          | 1         | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 21        | 75%     |
| AMD    | 5         | 17.86%  |
| Nvidia | 1         | 3.57%   |
| JMTek  | 1         | 3.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                     | 4         | 11.11%  |
| Intel Wildcat Point-LP High Definition Audio Controller             | 2         | 5.56%   |
| Intel NM10/ICH7 Family High Definition Audio Controller             | 2         | 5.56%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller           | 2         | 5.56%   |
| Intel Haswell-ULT HD Audio Controller                               | 2         | 5.56%   |
| Intel Broadwell-U Audio Controller                                  | 2         | 5.56%   |
| Intel 8 Series HD Audio Controller                                  | 2         | 5.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 2         | 5.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio            | 2         | 5.56%   |
| AMD SBx00 Azalia (Intel HDA)                                        | 2         | 5.56%   |
| AMD Family 17h/19h HD Audio Controller                              | 2         | 5.56%   |
| Nvidia GP107GL High Definition Audio Controller                     | 1         | 2.78%   |
| JMTek USB Audio Device                                              | 1         | 2.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 1         | 2.78%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster   | 1         | 2.78%   |
| Intel Cannon Lake PCH cAVS                                          | 1         | 2.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                      | 1         | 2.78%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                      | 1         | 2.78%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                    | 1         | 2.78%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                        | 1         | 2.78%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 1         | 2.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 1         | 2.78%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]              | 1         | 2.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 6         | 24%     |
| Micron Technology   | 5         | 20%     |
| Unknown             | 4         | 16%     |
| Samsung Electronics | 3         | 12%     |
| Elpida              | 3         | 12%     |
| A-DATA Technology   | 3         | 12%     |
| Kingston            | 1         | 4%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 3.85%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 3.85%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 3.85%   |
| Unknown RAM Module 1GB SODIMM DDR3 667MT/s                       | 1         | 3.85%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1334MT/s           | 1         | 3.85%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 3.85%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB DDR3 1600MT/s                  | 1         | 3.85%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 1         | 3.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 3.85%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 3.85%   |
| Samsung RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 3.85%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 3.85%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 1         | 3.85%   |
| Micron RAM MT53E1G32D4NQ-046WTE 4GB Row Of Chips LPDDR4 4266MT/s | 1         | 3.85%   |
| Micron RAM MT53B256M32D1NP 1GB 2400MT/s                          | 1         | 3.85%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 3.85%   |
| Micron RAM 8ATF1G64HZ-2G3H1 8GB SODIMM DDR4 2400MT/s             | 1         | 3.85%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 3.85%   |
| Kingston RAM 99U5428-040.A01LF 4GB SODIMM DDR3 1334MT/s          | 1         | 3.85%   |
| Elpida RAM EDFA232A2MA-JD-F 4GB SODIMM LPDDR3 1867MT/s           | 1         | 3.85%   |
| Elpida RAM EDFA232A2MA-JD-F 4GB Chip LPDDR3 1867MT/s             | 1         | 3.85%   |
| Elpida RAM EBJ40UG8EFU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 1         | 3.85%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s            | 1         | 3.85%   |
| A-DATA RAM Module 2GB SODIMM DDR3 1067MT/s                       | 1         | 3.85%   |
| A-DATA RAM AO1P26KC8T1-BXPS 8GB SODIMM DDR4 2667MT/s             | 1         | 3.85%   |
| A-DATA RAM AM1L16BC2P1-B1FS 2GB SODIMM DDR3 1600MT/s             | 1         | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 10        | 45.45%  |
| DDR4   | 6         | 27.27%  |
| LPDDR4 | 3         | 13.64%  |
| DDR2   | 2         | 9.09%   |
| LPDDR3 | 1         | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 18        | 78.26%  |
| Row Of Chips | 2         | 8.7%    |
| Unknown      | 2         | 8.7%    |
| Chip         | 1         | 4.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 7         | 31.82%  |
| 2048  | 7         | 31.82%  |
| 8192  | 5         | 22.73%  |
| 1024  | 2         | 9.09%   |
| 16384 | 1         | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 5         | 22.73%  |
| 2667  | 4         | 18.18%  |
| 667   | 4         | 18.18%  |
| 2400  | 2         | 9.09%   |
| 1067  | 2         | 9.09%   |
| 8400  | 1         | 4.55%   |
| 4267  | 1         | 4.55%   |
| 4266  | 1         | 4.55%   |
| 1867  | 1         | 4.55%   |
| 1334  | 1         | 4.55%   |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 5         | 25%     |
| Sunplus Innovation Technology | 2         | 10%     |
| Realtek Semiconductor         | 2         | 10%     |
| Microdia                      | 2         | 10%     |
| IMC Networks                  | 2         | 10%     |
| Apple                         | 2         | 10%     |
| ALi                           | 2         | 10%     |
| Suyin                         | 1         | 5%      |
| Luxvisions Innotech Limited   | 1         | 5%      |
| Acer                          | 1         | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                   | 2         | 10%     |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 5%      |
| Sunplus Integrated_Webcam_HD                        | 1         | 5%      |
| Sunplus HD WebCam                                   | 1         | 5%      |
| Realtek Lenovo EasyCamera                           | 1         | 5%      |
| Realtek 2SF022                                      | 1         | 5%      |
| Microdia Integrated_Webcam_HD                       | 1         | 5%      |
| Microdia Integrated Webcam                          | 1         | 5%      |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 5%      |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 5%      |
| IMC Networks Integrated Camera                      | 1         | 5%      |
| Chicony Integrated Camera                           | 1         | 5%      |
| Chicony HP Integrated Webcam                        | 1         | 5%      |
| Chicony HD WebCam (Acer)                            | 1         | 5%      |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 1         | 5%      |
| Apple Built-in iSight                               | 1         | 5%      |
| ALi WebCam                                          | 1         | 5%      |
| ALi Gateway Webcam                                  | 1         | 5%      |
| Acer BisonCam, NB Pro                               | 1         | 5%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| LighTuning Technology | 1         | 50%     |
| Focal-systems.Corp    | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| LighTuning ES603 Swipe Fingerprint Sensor | 1         | 50%     |
| Focal-systems.Corp FT9201Fingerprint.     | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Broadcom 5880 | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 18        | 72%     |
| 1     | 6         | 24%     |
| 2     | 1         | 4%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 2         | 25%     |
| Fingerprint reader    | 2         | 25%     |
| Net/wireless          | 1         | 12.5%   |
| Multimedia controller | 1         | 12.5%   |
| Chipcard              | 1         | 12.5%   |
| Camera                | 1         | 12.5%   |

