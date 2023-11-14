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

Total: 31

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 1318               | [2ac81db219](https://linux-hardware.org/?probe=2ac81db219) | Oct 14, 2023 |
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
| Lilidog 22 | 16        | 59.26%  |
| Lilidog 23 | 11        | 40.74%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Lilidog | 26        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 6.1.0-9-amd64             | 5         | 16.67%  |
| 5.10.0-15-amd64           | 4         | 13.33%  |
| 6.1.0-10-amd64            | 3         | 10%     |
| 5.10.0-16-amd64           | 3         | 10%     |
| 5.10.0-21-amd64           | 2         | 6.67%   |
| 5.10.0-18-amd64           | 2         | 6.67%   |
| 6.4.5-1-liquorix-amd64    | 1         | 3.33%   |
| 6.1.0-7-amd64             | 1         | 3.33%   |
| 6.1.0-13-amd64            | 1         | 3.33%   |
| 6.1.0-11-amd64            | 1         | 3.33%   |
| 6.1.0-0.deb11.6-amd64     | 1         | 3.33%   |
| 6.0.10-x64v1-xanmod1      | 1         | 3.33%   |
| 6.0.0-0.deb11.2-amd64     | 1         | 3.33%   |
| 5.17.0-5.1-liquorix-amd64 | 1         | 3.33%   |
| 5.10.0-22-amd64           | 1         | 3.33%   |
| 5.10.0-14-amd64           | 1         | 3.33%   |
| 5.10.0-13-amd64           | 1         | 3.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 12        | 44.44%  |
| 6.1.0   | 11        | 40.74%  |
| 6.4.5   | 1         | 3.7%    |
| 6.0.10  | 1         | 3.7%    |
| 6.0.0   | 1         | 3.7%    |
| 5.17.0  | 1         | 3.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 12        | 44.44%  |
| 6.1     | 11        | 40.74%  |
| 6.0     | 2         | 7.41%   |
| 6.4     | 1         | 3.7%    |
| 5.17    | 1         | 3.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 26        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| lightdm-xsession | 23        | 85.19%  |
| openbox          | 4         | 14.81%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 26        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 26        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 18        | 66.67%  |
| de_DE | 4         | 14.81%  |
| es_ES | 2         | 7.41%   |
| es_CL | 1         | 3.7%    |
| en_IE | 1         | 3.7%    |
| cs_CZ | 1         | 3.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 14        | 53.85%  |
| EFI  | 12        | 46.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 17        | 65.38%  |
| Overlay | 8         | 30.77%  |
| Btrfs   | 1         | 3.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| MBR  | 14        | 53.85%  |
| GPT  | 12        | 46.15%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 17        | 60.71%  |
| Yes       | 11        | 39.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 22        | 84.62%  |
| Yes       | 4         | 15.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 5         | 19.23%  |
| Dell             | 5         | 19.23%  |
| Acer             | 5         | 19.23%  |
| Hewlett-Packard  | 3         | 11.54%  |
| Panasonic        | 2         | 7.69%   |
| Google           | 2         | 7.69%   |
| TUXEDO           | 1         | 3.85%   |
| GPU Company      | 1         | 3.85%   |
| ASUSTek Computer | 1         | 3.85%   |
| Apple            | 1         | 3.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Acer AOD255E                               | 2         | 7.69%   |
| TUXEDO N8xEJEK                             | 1         | 3.85%   |
| Panasonic CFMX4-1                          | 1         | 3.85%   |
| Panasonic CF-31ATXAX1M                     | 1         | 3.85%   |
| Lenovo Yoga Slim 7 14ARE05 82A2            | 1         | 3.85%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 1         | 3.85%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS24900   | 1         | 3.85%   |
| Lenovo ThinkPad T400 6474WPU               | 1         | 3.85%   |
| Lenovo G500 20236                          | 1         | 3.85%   |
| HP Laptop 15s-fq1xxx                       | 1         | 3.85%   |
| HP G62                                     | 1         | 3.85%   |
| HP 435                                     | 1         | 3.85%   |
| GPU Company GWNR71517                      | 1         | 3.85%   |
| Google Sand                                | 1         | 3.85%   |
| Google Auron_Yuna                          | 1         | 3.85%   |
| Dell Latitude E5440                        | 1         | 3.85%   |
| Dell Latitude 7414                         | 1         | 3.85%   |
| Dell Latitude 7390                         | 1         | 3.85%   |
| Dell Inspiron 3793                         | 1         | 3.85%   |
| Dell Inspiron 1318                         | 1         | 3.85%   |
| ASUS VivoBook 15_ASUS Laptop X560UD        | 1         | 3.85%   |
| Apple MacBookPro3,1                        | 1         | 3.85%   |
| Acer V5-131                                | 1         | 3.85%   |
| Acer Aspire E5-573                         | 1         | 3.85%   |
| Acer Aspire 7540                           | 1         | 3.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 3         | 11.54%  |
| Dell Latitude          | 3         | 11.54%  |
| Dell Inspiron          | 2         | 7.69%   |
| Acer Aspire            | 2         | 7.69%   |
| Acer AOD255E           | 2         | 7.69%   |
| TUXEDO N8xEJEK         | 1         | 3.85%   |
| Panasonic CFMX4-1      | 1         | 3.85%   |
| Panasonic CF-31ATXAX1M | 1         | 3.85%   |
| Lenovo Yoga            | 1         | 3.85%   |
| Lenovo G500            | 1         | 3.85%   |
| HP Laptop              | 1         | 3.85%   |
| HP G62                 | 1         | 3.85%   |
| HP 435                 | 1         | 3.85%   |
| GPU Company GWNR71517  | 1         | 3.85%   |
| Google Sand            | 1         | 3.85%   |
| Google Auron           | 1         | 3.85%   |
| ASUS VivoBook          | 1         | 3.85%   |
| Apple MacBookPro3      | 1         | 3.85%   |
| Acer V5-131            | 1         | 3.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 4         | 15.38%  |
| 2010 | 4         | 15.38%  |
| 2021 | 2         | 7.69%   |
| 2020 | 2         | 7.69%   |
| 2019 | 2         | 7.69%   |
| 2013 | 2         | 7.69%   |
| 2008 | 2         | 7.69%   |
| 2017 | 1         | 3.85%   |
| 2016 | 1         | 3.85%   |
| 2015 | 1         | 3.85%   |
| 2014 | 1         | 3.85%   |
| 2012 | 1         | 3.85%   |
| 2011 | 1         | 3.85%   |
| 2009 | 1         | 3.85%   |
| 2007 | 1         | 3.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 26        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 25        | 96.15%  |
| Enabled  | 1         | 3.85%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 23        | 88.46%  |
| Yes  | 3         | 11.54%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 9         | 34.62%  |
| 4.01-8.0   | 8         | 30.77%  |
| 16.01-24.0 | 3         | 11.54%  |
| 1.01-2.0   | 2         | 7.69%   |
| 8.01-16.0  | 2         | 7.69%   |
| 32.01-64.0 | 1         | 3.85%   |
| 0.51-1.0   | 1         | 3.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.51-1.0 | 16        | 59.26%  |
| 1.01-2.0 | 8         | 29.63%  |
| 2.01-3.0 | 3         | 11.11%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 23        | 85.19%  |
| 2      | 4         | 14.81%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 17        | 65.38%  |
| Yes       | 9         | 34.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 73.08%  |
| No        | 7         | 26.92%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 96.15%  |
| No        | 1         | 3.85%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 69.23%  |
| No        | 8         | 30.77%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| USA      | 9         | 34.62%  |
| Germany  | 6         | 23.08%  |
| Spain    | 3         | 11.54%  |
| Vietnam  | 1         | 3.85%   |
| Thailand | 1         | 3.85%   |
| Portugal | 1         | 3.85%   |
| Mexico   | 1         | 3.85%   |
| Kenya    | 1         | 3.85%   |
| Italy    | 1         | 3.85%   |
| Czechia  | 1         | 3.85%   |
| Chile    | 1         | 3.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Fayetteville           | 3         | 11.54%  |
| Egan                   | 2         | 7.69%   |
| Denver                 | 2         | 7.69%   |
| Viña del Mar          | 1         | 3.85%   |
| Uelzen                 | 1         | 3.85%   |
| Rinteln                | 1         | 3.85%   |
| Ratchathewi            | 1         | 3.85%   |
| Poricany               | 1         | 3.85%   |
| Nairobi                | 1         | 3.85%   |
| Morgantown             | 1         | 3.85%   |
| Monclova               | 1         | 3.85%   |
| Milan                  | 1         | 3.85%   |
| Madrid                 | 1         | 3.85%   |
| Lisbon                 | 1         | 3.85%   |
| Ho Chi Minh City       | 1         | 3.85%   |
| Filderstadt            | 1         | 3.85%   |
| Eppelborn              | 1         | 3.85%   |
| Düsseldorf            | 1         | 3.85%   |
| Darmstadt              | 1         | 3.85%   |
| Charlotte              | 1         | 3.85%   |
| Cervera del Rio Alhama | 1         | 3.85%   |
| Barcelona              | 1         | 3.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 9      | 24.14%  |
| Toshiba             | 3         | 4      | 10.34%  |
| Seagate             | 3         | 4      | 10.34%  |
| SanDisk             | 2         | 3      | 6.9%    |
| Kingston            | 2         | 2      | 6.9%    |
| Wibtek              | 1         | 1      | 3.45%   |
| WDC                 | 1         | 1      | 3.45%   |
| Unknown             | 1         | 1      | 3.45%   |
| Mushkin             | 1         | 1      | 3.45%   |
| Micron Technology   | 1         | 2      | 3.45%   |
| Lexar               | 1         | 1      | 3.45%   |
| KIOXIA              | 1         | 1      | 3.45%   |
| Hitachi             | 1         | 1      | 3.45%   |
| Crucial             | 1         | 1      | 3.45%   |
| China               | 1         | 1      | 3.45%   |
| Blackpcs            | 1         | 1      | 3.45%   |
| Apacer              | 1         | 1      | 3.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Wibtek W800S 512GB SSD               | 1         | 3.33%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 3.33%   |
| Unknown NCard  32GB                  | 1         | 3.33%   |
| Toshiba MQ04ABF100 1TB               | 1         | 3.33%   |
| Toshiba MK6034GSX 64GB               | 1         | 3.33%   |
| Toshiba MK1665GSX 160GB              | 1         | 3.33%   |
| Seagate ST9320325AS 320GB            | 1         | 3.33%   |
| Seagate ST9250315AS 250GB            | 1         | 3.33%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 3.33%   |
| SanDisk SD8TN8U256G1001 256GB SSD    | 1         | 3.33%   |
| SanDisk DF4032  32GB                 | 1         | 3.33%   |
| Samsung SSD PM841 2.5 7mm 256GB      | 1         | 3.33%   |
| Samsung SSD 970 EVO Plus 250GB       | 1         | 3.33%   |
| Samsung SSD 860 EVO 500GB            | 1         | 3.33%   |
| Samsung SSD 860 EVO 1TB              | 1         | 3.33%   |
| Samsung SSD 850 EVO 250GB            | 1         | 3.33%   |
| Samsung PM991a NVMe 512GB            | 1         | 3.33%   |
| Samsung MZVL21T0HCLR-00BL7 1TB       | 1         | 3.33%   |
| Samsung MZNTE128HMGR-00000 128GB SSD | 1         | 3.33%   |
| Mushkin MKNSSDCR120GB                | 1         | 3.33%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 1         | 3.33%   |
| Lexar SSD NM620 256GB                | 1         | 3.33%   |
| KIOXIA KBG40ZNV1T02 1TB              | 1         | 3.33%   |
| Kingston SNS4151S332GD 32GB SSD      | 1         | 3.33%   |
| Kingston SKC3000D2048G 2TB           | 1         | 3.33%   |
| Hitachi HTS545016B9SA00 160GB        | 1         | 3.33%   |
| Crucial CT480BX500SSD1 480GB         | 1         | 3.33%   |
| China SSD 120GB                      | 1         | 3.33%   |
| Blackpcs SSDPro 120GB                | 1         | 3.33%   |
| Apacer AS350 512GB SSD               | 1         | 3.33%   |

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
| Samsung Electronics | 5         | 5      | 35.71%  |
| Wibtek              | 1         | 1      | 7.14%   |
| SanDisk             | 1         | 1      | 7.14%   |
| Mushkin             | 1         | 1      | 7.14%   |
| Micron Technology   | 1         | 2      | 7.14%   |
| Kingston            | 1         | 1      | 7.14%   |
| Crucial             | 1         | 1      | 7.14%   |
| China               | 1         | 1      | 7.14%   |
| Blackpcs            | 1         | 1      | 7.14%   |
| Apacer              | 1         | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 14        | 15     | 48.28%  |
| HDD  | 8         | 10     | 27.59%  |
| NVMe | 6         | 7      | 20.69%  |
| MMC  | 1         | 3      | 3.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 20        | 25     | 74.07%  |
| NVMe | 6         | 7      | 22.22%  |
| MMC  | 1         | 3      | 3.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 17        | 20     | 80.95%  |
| 0.51-1.0   | 4         | 5      | 19.05%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 8         | 29.63%  |
| 251-500    | 7         | 25.93%  |
| 101-250    | 6         | 22.22%  |
| 21-50      | 2         | 7.41%   |
| 51-100     | 2         | 7.41%   |
| 1001-2000  | 1         | 3.7%    |
| 501-1000   | 1         | 3.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 24        | 88.89%  |
| 21-50   | 3         | 11.11%  |

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
| Works    | 20        | 25     | 74.07%  |
| Malfunc  | 5         | 6      | 18.52%  |
| Detected | 1         | 3      | 3.7%    |
| Failed   | 1         | 1      | 3.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 19        | 67.86%  |
| Samsung Electronics          | 3         | 10.71%  |
| AMD                          | 3         | 10.71%  |
| Shenzhen Longsys Electronics | 1         | 3.57%   |
| KIOXIA                       | 1         | 3.57%   |
| Kingston Technology Company  | 1         | 3.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                    | 3         | 9.38%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                    | 2         | 6.25%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                    | 2         | 6.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]         | 2         | 6.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                      | 2         | 6.25%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                        | 2         | 6.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                     | 2         | 6.25%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                     | 1         | 3.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                         | 1         | 3.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                        | 1         | 3.13%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                           | 1         | 3.13%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                            | 1         | 3.13%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                    | 1         | 3.13%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                         | 1         | 3.13%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                     | 1         | 3.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode] | 1         | 3.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                          | 1         | 3.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]      | 1         | 3.13%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]       | 1         | 3.13%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]       | 1         | 3.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller        | 1         | 3.13%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller        | 1         | 3.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                  | 1         | 3.13%   |
| AMD FCH SATA Controller [AHCI mode]                                   | 1         | 3.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 19        | 61.29%  |
| NVMe | 6         | 19.35%  |
| IDE  | 4         | 12.9%   |
| RAID | 2         | 6.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 22        | 84.62%  |
| AMD    | 4         | 15.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 7.69%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 2         | 7.69%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 3.85%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 3.85%   |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 3.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 3.85%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 3.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 3.85%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 3.85%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 3.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 3.85%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 3.85%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 3.85%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 3.85%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 3.85%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 3.85%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 1         | 3.85%   |
| Intel Celeron CPU 1007U @ 1.50GHz             | 1         | 3.85%   |
| Intel Celeron 3205U @ 1.50GHz                 | 1         | 3.85%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 3.85%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 3.85%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 3.85%   |
| AMD Phenom II N830 Triple-Core Processor      | 1         | 3.85%   |
| AMD Athlon II Dual-Core M300                  | 1         | 3.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 7         | 26.92%  |
| Intel Core i7           | 5         | 19.23%  |
| Intel Pentium           | 2         | 7.69%   |
| Intel Core 2 Duo        | 2         | 7.69%   |
| Intel Celeron           | 2         | 7.69%   |
| Intel Atom              | 2         | 7.69%   |
| Other                   | 1         | 3.85%   |
| Intel Pentium Dual-Core | 1         | 3.85%   |
| AMD Ryzen 7             | 1         | 3.85%   |
| AMD Ryzen 5             | 1         | 3.85%   |
| AMD Phenom II           | 1         | 3.85%   |
| AMD Athlon II Dual-Core | 1         | 3.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 14        | 53.85%  |
| 4      | 7         | 26.92%  |
| 6      | 2         | 7.69%   |
| 1      | 2         | 7.69%   |
| 3      | 1         | 3.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 26        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 16        | 61.54%  |
| 1      | 10        | 38.46%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 26        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3         | 11.54%  |
| 0x806ea    | 2         | 7.69%   |
| 0x406e3    | 2         | 7.69%   |
| 0x40651    | 2         | 7.69%   |
| 0x306d4    | 2         | 7.69%   |
| 0x306a9    | 2         | 7.69%   |
| 0x106ca    | 2         | 7.69%   |
| 0x906ea    | 1         | 3.85%   |
| 0x806c1    | 1         | 3.85%   |
| 0x706e5    | 1         | 3.85%   |
| 0x6fa      | 1         | 3.85%   |
| 0x506c9    | 1         | 3.85%   |
| 0x20655    | 1         | 3.85%   |
| 0x1067a    | 1         | 3.85%   |
| 0x10676    | 1         | 3.85%   |
| 0x08600106 | 1         | 3.85%   |
| 0x08108109 | 1         | 3.85%   |
| 0x010000c8 | 1         | 3.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KabyLake  | 3         | 11.54%  |
| Westmere  | 2         | 7.69%   |
| Skylake   | 2         | 7.69%   |
| Penryn    | 2         | 7.69%   |
| K10       | 2         | 7.69%   |
| IvyBridge | 2         | 7.69%   |
| IceLake   | 2         | 7.69%   |
| Haswell   | 2         | 7.69%   |
| Broadwell | 2         | 7.69%   |
| Bonnell   | 2         | 7.69%   |
| Zen+      | 1         | 3.85%   |
| Zen 2     | 1         | 3.85%   |
| TigerLake | 1         | 3.85%   |
| Goldmont  | 1         | 3.85%   |
| Core      | 1         | 3.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 21        | 70%     |
| AMD    | 6         | 20%     |
| Nvidia | 3         | 10%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                  | 2         | 6.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                     | 2         | 6.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                        | 2         | 6.45%   |
| Intel Core Processor Integrated Graphics Controller                     | 2         | 6.45%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller | 2         | 6.45%   |
| Intel 3rd Gen Core processor Graphics Controller                        | 2         | 6.45%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                              | 1         | 3.23%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                 | 1         | 3.23%   |
| Nvidia G84M [GeForce 8600M GT]                                          | 1         | 3.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                               | 1         | 3.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)     | 1         | 3.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)       | 1         | 3.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller            | 1         | 3.23%   |
| Intel Iris Plus Graphics G7                                             | 1         | 3.23%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                  | 1         | 3.23%   |
| Intel HD Graphics 5500                                                  | 1         | 3.23%   |
| Intel HD Graphics                                                       | 1         | 3.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                               | 1         | 3.23%   |
| Intel Apollo Lake [HD Graphics 505]                                     | 1         | 3.23%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]        | 1         | 3.23%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                               | 1         | 3.23%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]           | 1         | 3.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]    | 1         | 3.23%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                            | 1         | 3.23%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                        | 1         | 3.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 16        | 61.54%  |
| 1 x AMD        | 4         | 15.38%  |
| Intel + Nvidia | 2         | 7.69%   |
| Intel + AMD    | 2         | 7.69%   |
| 2 x Intel      | 1         | 3.85%   |
| 1 x Nvidia     | 1         | 3.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 25        | 96.15%  |
| Unknown | 1         | 3.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 69.23%  |
| 0.01-0.5   | 5         | 19.23%  |
| 3.01-4.0   | 2         | 7.69%   |
| 1.01-2.0   | 1         | 3.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 9         | 36%     |
| LG Display              | 4         | 16%     |
| Chimei Innolux          | 4         | 16%     |
| BOE                     | 2         | 8%      |
| Sharp                   | 1         | 4%      |
| Samsung Electronics     | 1         | 4%      |
| Lenovo                  | 1         | 4%      |
| JDI                     | 1         | 4%      |
| Chi Mei Optoelectronics | 1         | 4%      |
| AOC                     | 1         | 4%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 8%      |
| Sharp LCD Monitor SHP1416 1366x768 309x174mm 14.0-inch                   | 1         | 4%      |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 1         | 4%      |
| LG Display LP101WSB-TLN1 LGD026E 1024x600 224x126mm 10.1-inch            | 1         | 4%      |
| LG Display LCD Monitor LGD0479 1920x1080 309x174mm 14.0-inch             | 1         | 4%      |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 1         | 4%      |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 1         | 4%      |
| Lenovo LCD Monitor LEN4037 1280x800 303x190mm 14.1-inch                  | 1         | 4%      |
| JDI LAM125M007D JDI1402 1920x1080 277x156mm 12.5-inch                    | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN1382 1920x1080 293x165mm 13.2-inch         | 1         | 4%      |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 1         | 4%      |
| BOE LCD Monitor BOE0A06 1920x1080 344x194mm 15.5-inch                    | 1         | 4%      |
| BOE LCD Monitor BOE05F6 1366x768 309x173mm 13.9-inch                     | 1         | 4%      |
| AU Optronics LCD Monitor AUOD291 1920x1200 301x188mm 14.0-inch           | 1         | 4%      |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch           | 1         | 4%      |
| AU Optronics LCD Monitor AUO60D2 1024x600 222x125mm 10.0-inch            | 1         | 4%      |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch            | 1         | 4%      |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 1         | 4%      |
| AU Optronics LCD Monitor AUO319D 1920x1080 382x214mm 17.2-inch           | 1         | 4%      |
| AU Optronics LCD Monitor AUO30ED 1920x1080 340x190mm 15.3-inch           | 1         | 4%      |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch           | 1         | 4%      |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch            | 1         | 4%      |
| AOC 2219 AOC2219 1680x1050 474x296mm 22.0-inch                           | 1         | 4%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 10        | 40%     |
| 1366x768 (WXGA)    | 9         | 36%     |
| 1024x600           | 2         | 8%      |
| 1920x1200 (WUXGA)  | 1         | 4%      |
| 1680x1050 (WSXGA+) | 1         | 4%      |
| 1600x900 (HD+)     | 1         | 4%      |
| 1280x800 (WXGA)    | 1         | 4%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 9         | 36%     |
| 14     | 6         | 24%     |
| 17     | 3         | 12%     |
| 13     | 2         | 8%      |
| 10     | 2         | 8%      |
| 22     | 1         | 4%      |
| 12     | 1         | 4%      |
| 11     | 1         | 4%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 15        | 60%     |
| 201-300     | 5         | 20%     |
| 351-400     | 4         | 16%     |
| 401-500     | 1         | 4%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 22        | 88%     |
| 16/10 | 3         | 12%     |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 9         | 36%     |
| 81-90          | 7         | 28%     |
| 121-130        | 3         | 12%     |
| 41-50          | 2         | 8%      |
| 71-80          | 1         | 4%      |
| 61-70          | 1         | 4%      |
| 51-60          | 1         | 4%      |
| 201-250        | 1         | 4%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 10        | 40%     |
| 121-160 | 9         | 36%     |
| 161-240 | 3         | 12%     |
| 51-100  | 3         | 12%     |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 24        | 92.31%  |
| 2     | 1         | 3.85%   |
| 0     | 1         | 3.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 32.5%   |
| Qualcomm Atheros                | 10        | 25%     |
| Realtek Semiconductor           | 9         | 22.5%   |
| Broadcom                        | 6         | 15%     |
| Qualcomm Atheros Communications | 1         | 2.5%    |
| Marvell Technology Group        | 1         | 2.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 3         | 6.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 3         | 6.38%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 2         | 4.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 4.26%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                            | 2         | 4.26%   |
| Intel Wireless 8260                                                                   | 2         | 4.26%   |
| Intel Wireless 7260                                                                   | 2         | 4.26%   |
| Intel Ethernet Connection I219-LM                                                     | 2         | 4.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 4.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 2.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 2.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 1         | 2.13%   |
| Realtek 802.11ac NIC                                                                  | 1         | 2.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 2.13%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 2.13%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 2.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 2.13%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 2.13%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                               | 1         | 2.13%   |
| Intel Wireless-AC 9260                                                                | 1         | 2.13%   |
| Intel Wireless 8265 / 8275                                                            | 1         | 2.13%   |
| Intel Wireless 7265                                                                   | 1         | 2.13%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 2.13%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 2.13%   |
| Intel Ethernet Connection I218-LM                                                     | 1         | 2.13%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 1         | 2.13%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 1         | 2.13%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 2.13%   |
| Intel Centrino Advanced-N 6200                                                        | 1         | 2.13%   |
| Intel 82577LM Gigabit Network Connection                                              | 1         | 2.13%   |
| Intel 82567LM Gigabit Network Connection                                              | 1         | 2.13%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                                   | 1         | 2.13%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                       | 1         | 2.13%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                       | 1         | 2.13%   |
| Broadcom BCM4360 802.11ac 5G Wireless Network Adapter                                 | 1         | 2.13%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 1         | 2.13%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 40.74%  |
| Qualcomm Atheros                | 8         | 29.63%  |
| Broadcom                        | 4         | 14.81%  |
| Realtek Semiconductor           | 3         | 11.11%  |
| Qualcomm Atheros Communications | 1         | 3.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 3         | 11.11%  |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 7.41%   |
| Intel Wireless 8260                                                                   | 2         | 7.41%   |
| Intel Wireless 7260                                                                   | 2         | 7.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 7.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 3.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 3.7%    |
| Realtek 802.11ac NIC                                                                  | 1         | 3.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 3.7%    |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 3.7%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 3.7%    |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 3.7%    |
| Intel Wireless-AC 9260                                                                | 1         | 3.7%    |
| Intel Wireless 8265 / 8275                                                            | 1         | 3.7%    |
| Intel Wireless 7265                                                                   | 1         | 3.7%    |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 3.7%    |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 3.7%    |
| Intel Centrino Wireless-N 135                                                         | 1         | 3.7%    |
| Intel Centrino Advanced-N 6200                                                        | 1         | 3.7%    |
| Broadcom BCM4360 802.11ac 5G Wireless Network Adapter                                 | 1         | 3.7%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 1         | 3.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 7         | 35%     |
| Realtek Semiconductor    | 6         | 30%     |
| Qualcomm Atheros         | 3         | 15%     |
| Broadcom                 | 3         | 15%     |
| Marvell Technology Group | 1         | 5%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 15%     |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2         | 10%     |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 10%     |
| Intel Ethernet Connection I219-LM                                 | 2         | 10%     |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 5%      |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 5%      |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 5%      |
| Intel Ethernet Connection I218-LM                                 | 1         | 5%      |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 5%      |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 5%      |
| Intel 82577LM Gigabit Network Connection                          | 1         | 5%      |
| Intel 82567LM Gigabit Network Connection                          | 1         | 5%      |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 5%      |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 5%      |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 5%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 25        | 56.82%  |
| Ethernet | 19        | 43.18%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 17        | 65.38%  |
| Ethernet | 9         | 34.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 18        | 69.23%  |
| 1     | 7         | 26.92%  |
| 0     | 1         | 3.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 15        | 57.69%  |
| Yes  | 11        | 42.31%  |

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
| Intel  | 22        | 75.86%  |
| AMD    | 5         | 17.24%  |
| Nvidia | 1         | 3.45%   |
| JMTek  | 1         | 3.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                     | 4         | 10.81%  |
| Intel Wildcat Point-LP High Definition Audio Controller             | 2         | 5.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller             | 2         | 5.41%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller           | 2         | 5.41%   |
| Intel Haswell-ULT HD Audio Controller                               | 2         | 5.41%   |
| Intel Broadwell-U Audio Controller                                  | 2         | 5.41%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                      | 2         | 5.41%   |
| Intel 8 Series HD Audio Controller                                  | 2         | 5.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 2         | 5.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio            | 2         | 5.41%   |
| AMD SBx00 Azalia (Intel HDA)                                        | 2         | 5.41%   |
| AMD Family 17h/19h HD Audio Controller                              | 2         | 5.41%   |
| Nvidia GP107GL High Definition Audio Controller                     | 1         | 2.7%    |
| JMTek USB Audio Device                                              | 1         | 2.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 1         | 2.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster   | 1         | 2.7%    |
| Intel Cannon Lake PCH cAVS                                          | 1         | 2.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                      | 1         | 2.7%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                    | 1         | 2.7%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                        | 1         | 2.7%    |
| AMD Renoir Radeon High Definition Audio Controller                  | 1         | 2.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 1         | 2.7%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]              | 1         | 2.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 6         | 22.22%  |
| Micron Technology   | 5         | 18.52%  |
| Unknown             | 4         | 14.81%  |
| A-DATA Technology   | 4         | 14.81%  |
| Samsung Electronics | 3         | 11.11%  |
| Elpida              | 3         | 11.11%  |
| Kingston            | 2         | 7.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 3.57%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 3.57%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 3.57%   |
| Unknown RAM Module 1GB SODIMM DDR3 667MT/s                       | 1         | 3.57%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1334MT/s           | 1         | 3.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 3.57%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB DDR3 1600MT/s                  | 1         | 3.57%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 1         | 3.57%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 3.57%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 3.57%   |
| Samsung RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 3.57%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 3.57%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 1         | 3.57%   |
| Micron RAM MT53E1G32D4NQ-046WTE 4GB Row Of Chips LPDDR4 4266MT/s | 1         | 3.57%   |
| Micron RAM MT53B256M32D1NP 1GB 2400MT/s                          | 1         | 3.57%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 3.57%   |
| Micron RAM 8ATF1G64HZ-2G3H1 8192MB SODIMM DDR4 2400MT/s          | 1         | 3.57%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 3.57%   |
| Kingston RAM 99U5428-040.A01LF 4GB SODIMM DDR3 1334MT/s          | 1         | 3.57%   |
| Kingston RAM 9905295-045.A01LF 2GB SODIMM DDR 667MT/s            | 1         | 3.57%   |
| Elpida RAM EDFA232A2MA-JD-F 4GB SODIMM LPDDR3 1867MT/s           | 1         | 3.57%   |
| Elpida RAM EDFA232A2MA-JD-F 4GB Chip LPDDR3 1867MT/s             | 1         | 3.57%   |
| Elpida RAM EBJ40UG8EFU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 1         | 3.57%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s            | 1         | 3.57%   |
| A-DATA RAM Module 2GB SODIMM DDR3 1067MT/s                       | 1         | 3.57%   |
| A-DATA RAM AO1P26KC8T1-BXPS 8GB SODIMM DDR4 2667MT/s             | 1         | 3.57%   |
| A-DATA RAM AM1L16BC2P1-B1FS 2GB SODIMM DDR3 1600MT/s             | 1         | 3.57%   |
| A-DATA RAM ADOVE1B163BE 2GB SODIMM DDR 975MT/s                   | 1         | 3.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 10        | 43.48%  |
| DDR4   | 6         | 26.09%  |
| LPDDR4 | 3         | 13.04%  |
| DDR2   | 3         | 13.04%  |
| LPDDR3 | 1         | 4.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 19        | 79.17%  |
| Row Of Chips | 2         | 8.33%   |
| Unknown      | 2         | 8.33%   |
| Chip         | 1         | 4.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 8         | 34.78%  |
| 4096  | 7         | 30.43%  |
| 8192  | 5         | 21.74%  |
| 1024  | 2         | 8.7%    |
| 16384 | 1         | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 5         | 20.83%  |
| 667   | 5         | 20.83%  |
| 2667  | 4         | 16.67%  |
| 2400  | 2         | 8.33%   |
| 1067  | 2         | 8.33%   |
| 8400  | 1         | 4.17%   |
| 4267  | 1         | 4.17%   |
| 4266  | 1         | 4.17%   |
| 1867  | 1         | 4.17%   |
| 1334  | 1         | 4.17%   |
| 975   | 1         | 4.17%   |

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
| Realtek USB2.0-Camera                               | 1         | 5%      |
| Realtek Lenovo EasyCamera                           | 1         | 5%      |
| Microdia Integrated_Webcam_HD                       | 1         | 5%      |
| Microdia Integrated Webcam                          | 1         | 5%      |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 5%      |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 5%      |
| IMC Networks Integrated Camera                      | 1         | 5%      |
| Chicony Integrated Camera                           | 1         | 5%      |
| Chicony HP Integrated Webcam                        | 1         | 5%      |
| Chicony HD WebCam (Acer)                            | 1         | 5%      |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 1         | 5%      |
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
| 0     | 18        | 69.23%  |
| 1     | 8         | 30.77%  |

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

