Pardus - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Pardus.

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

Total: 28

| Vendor   | Model                    | Probe                                                      | Date         |
|----------|--------------------------|------------------------------------------------------------|--------------|
| ASUSTek  | ProArt X570-CREATOR WIFI | [a9b6f1553d](https://linux-hardware.org/?probe=a9b6f1553d) | Dec 16, 2023 |
| Intel    | H55                      | [edff4a2637](https://linux-hardware.org/?probe=edff4a2637) | Oct 25, 2023 |
| ASUSTek  | P8H61-M LX               | [10e8cc92f1](https://linux-hardware.org/?probe=10e8cc92f1) | Apr 19, 2023 |
| ASUSTek  | P8H61-M LX               | [1e59096b86](https://linux-hardware.org/?probe=1e59096b86) | Apr 19, 2023 |
| HP       | 18E6                     | [d7cf5918eb](https://linux-hardware.org/?probe=d7cf5918eb) | Apr 11, 2023 |
| Dell     | 057FFP A01               | [023591084f](https://linux-hardware.org/?probe=023591084f) | Apr 07, 2023 |
| Dell     | 057FFP A01               | [683dea4da0](https://linux-hardware.org/?probe=683dea4da0) | Apr 07, 2023 |
| Gigabyte | H410M H V3               | [5349814c06](https://linux-hardware.org/?probe=5349814c06) | Apr 07, 2023 |
| Lenovo   | 3132 NOK                 | [787c98df69](https://linux-hardware.org/?probe=787c98df69) | Jan 20, 2023 |
| ASUSTek  | P5G41C-M LX              | [0990a5e3e8](https://linux-hardware.org/?probe=0990a5e3e8) | Jan 05, 2023 |
| ASUSTek  | P5G41C-M LX              | [78a3773180](https://linux-hardware.org/?probe=78a3773180) | Jan 05, 2023 |
| ASUSTek  | H81M-PLUS                | [ffe63e6795](https://linux-hardware.org/?probe=ffe63e6795) | Oct 25, 2022 |
| ASUSTek  | H81M-PLUS                | [b0700ec521](https://linux-hardware.org/?probe=b0700ec521) | Oct 24, 2022 |
| ASUSTek  | P7H55-M LX               | [517cb3cb75](https://linux-hardware.org/?probe=517cb3cb75) | Oct 11, 2022 |
| Acer     | Veriton ES2740G V:1.0    | [e14aeaaca3](https://linux-hardware.org/?probe=e14aeaaca3) | Jul 25, 2022 |
| MSI      | B250M GAMING PRO         | [052965926e](https://linux-hardware.org/?probe=052965926e) | Jun 26, 2022 |
| MSI      | MS-7360                  | [1ca1d835ad](https://linux-hardware.org/?probe=1ca1d835ad) | May 22, 2022 |
| MSI      | H310M PRO-VDH PLUS       | [0d897cd79c](https://linux-hardware.org/?probe=0d897cd79c) | Apr 15, 2022 |
| MSI      | MS-7360                  | [34c10f0508](https://linux-hardware.org/?probe=34c10f0508) | Apr 10, 2022 |
| MSI      | H81M-P33                 | [2b0d95df2e](https://linux-hardware.org/?probe=2b0d95df2e) | Apr 02, 2022 |
| MSI      | MS-7360                  | [8efb24e401](https://linux-hardware.org/?probe=8efb24e401) | Mar 21, 2022 |
| MSI      | MS-7360                  | [99ac168204](https://linux-hardware.org/?probe=99ac168204) | Mar 18, 2022 |
| Gigabyte | A320M-S2H-CF             | [fcde789242](https://linux-hardware.org/?probe=fcde789242) | Jan 24, 2022 |
| Gigabyte | A320M-S2H-CF             | [dd92029684](https://linux-hardware.org/?probe=dd92029684) | Jan 21, 2022 |
| Lenovo   | 3132 NOK                 | [9d1ef122f7](https://linux-hardware.org/?probe=9d1ef122f7) | Oct 11, 2021 |
| Lenovo   | 3132 NOK                 | [5802651f49](https://linux-hardware.org/?probe=5802651f49) | Sep 15, 2021 |
| ASUSTek  | P5G41C-M LX              | [9149be671f](https://linux-hardware.org/?probe=9149be671f) | Jan 30, 2021 |
| Gigabyte | A320M-H-CF               | [33cdf15439](https://linux-hardware.org/?probe=33cdf15439) | Dec 15, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Pardus 21.4   | 5        | 23.81%  |
| Pardus 21.2   | 5        | 23.81%  |
| Pardus 21.3   | 4        | 19.05%  |
| Pardus 23.0   | 2        | 9.52%   |
| Pardus 21.1   | 1        | 4.76%   |
| Pardus 21.0   | 1        | 4.76%   |
| Pardus 19.5   | 1        | 4.76%   |
| Pardus 19.4-1 | 1        | 4.76%   |
| Pardus 19.4   | 1        | 4.76%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Pardus | 19       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Desktops | Percent |
|---------------------|----------|---------|
| 5.10.0-21-amd64     | 3        | 14.29%  |
| 5.10.0-13-amd64     | 3        | 14.29%  |
| 6.1.0-13-amd64      | 2        | 9.52%   |
| 5.10.0-20-amd64     | 2        | 9.52%   |
| 5.10.0-16-amd64     | 2        | 9.52%   |
| 5.9.0-0.bpo.2-amd64 | 1        | 4.76%   |
| 5.10.0-8-amd64      | 1        | 4.76%   |
| 5.10.0-19-amd64     | 1        | 4.76%   |
| 5.10.0-18-amd64     | 1        | 4.76%   |
| 5.10.0-15-amd64     | 1        | 4.76%   |
| 5.10.0-14-amd64     | 1        | 4.76%   |
| 5.10.0-12-amd64     | 1        | 4.76%   |
| 4.19.0-18-amd64     | 1        | 4.76%   |
| 4.19.0-13-amd64     | 1        | 4.76%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 15       | 75%     |
| 6.1.0   | 2        | 10%     |
| 4.19.0  | 2        | 10%     |
| 5.9.0   | 1        | 5%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 15       | 75%     |
| 6.1     | 2        | 10%     |
| 4.19    | 2        | 10%     |
| 5.9     | 1        | 5%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 19       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| XFCE  | 13       | 65%     |
| GNOME | 5        | 25%     |
| KDE5  | 2        | 10%     |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 18       | 94.74%  |
| Tty  | 1        | 5.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 12       | 60%     |
| LightDM | 3        | 15%     |
| GDM     | 3        | 15%     |
| SDDM    | 2        | 10%     |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| tr_TR | 16       | 80%     |
| en_US | 3        | 15%     |
| fr_FR | 1        | 5%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 18       | 90%     |
| EFI  | 2        | 10%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ext4 | 19       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 14       | 70%     |
| GPT     | 4        | 20%     |
| MBR     | 2        | 10%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 89.47%  |
| Yes       | 2        | 10.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 94.74%  |
| Yes       | 1        | 5.26%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI                 | 6        | 31.58%  |
| ASUSTek Computer    | 5        | 26.32%  |
| Gigabyte Technology | 3        | 15.79%  |
| Lenovo              | 1        | 5.26%   |
| Intel               | 1        | 5.26%   |
| Hewlett-Packard     | 1        | 5.26%   |
| Dell                | 1        | 5.26%   |
| Acer                | 1        | 5.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| MSI MS-7360                         | 3        | 15.79%  |
| MSI MS-7C09                         | 1        | 5.26%   |
| MSI MS-7A65                         | 1        | 5.26%   |
| MSI MS-7817                         | 1        | 5.26%   |
| Lenovo ThinkCentre M920t 10SGS62900 | 1        | 5.26%   |
| Intel H55                           | 1        | 5.26%   |
| HP EliteOne 800 G1 AiO              | 1        | 5.26%   |
| Gigabyte H410M H V3                 | 1        | 5.26%   |
| Gigabyte A320M-S2H                  | 1        | 5.26%   |
| Gigabyte A320M-H                    | 1        | 5.26%   |
| Dell OptiPlex 3000                  | 1        | 5.26%   |
| ASUS ProArt X570-CREATOR WIFI       | 1        | 5.26%   |
| ASUS P8H61-M LX                     | 1        | 5.26%   |
| ASUS P7H55-M LX                     | 1        | 5.26%   |
| ASUS P5G41C-M LX                    | 1        | 5.26%   |
| ASUS All Series                     | 1        | 5.26%   |
| Acer Veriton ES2740G                | 1        | 5.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| MSI MS-7360        | 3        | 15.79%  |
| MSI MS-7C09        | 1        | 5.26%   |
| MSI MS-7A65        | 1        | 5.26%   |
| MSI MS-7817        | 1        | 5.26%   |
| Lenovo ThinkCentre | 1        | 5.26%   |
| Intel H55          | 1        | 5.26%   |
| HP EliteOne        | 1        | 5.26%   |
| Gigabyte H410M     | 1        | 5.26%   |
| Gigabyte A320M-S2H | 1        | 5.26%   |
| Gigabyte A320M-H   | 1        | 5.26%   |
| Dell OptiPlex      | 1        | 5.26%   |
| ASUS ProArt        | 1        | 5.26%   |
| ASUS P8H61-M       | 1        | 5.26%   |
| ASUS P7H55-M       | 1        | 5.26%   |
| ASUS P5G41C-M      | 1        | 5.26%   |
| ASUS All           | 1        | 5.26%   |
| Acer Veriton       | 1        | 5.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 3        | 15.79%  |
| 2013 | 3        | 15.79%  |
| 2007 | 3        | 15.79%  |
| 2021 | 2        | 10.53%  |
| 2017 | 2        | 10.53%  |
| 2010 | 2        | 10.53%  |
| 2022 | 1        | 5.26%   |
| 2020 | 1        | 5.26%   |
| 2014 | 1        | 5.26%   |
| 2011 | 1        | 5.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 19       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 19       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 19       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 5        | 25%     |
| 3.01-4.0    | 5        | 25%     |
| 8.01-16.0   | 4        | 20%     |
| 16.01-24.0  | 3        | 15%     |
| 32.01-64.0  | 1        | 5%      |
| 2.01-3.0    | 1        | 5%      |
| 64.01-256.0 | 1        | 5%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 10       | 47.62%  |
| 2.01-3.0   | 4        | 19.05%  |
| 3.01-4.0   | 3        | 14.29%  |
| 4.01-8.0   | 1        | 4.76%   |
| 24.01-32.0 | 1        | 4.76%   |
| 16.01-24.0 | 1        | 4.76%   |
| 8.01-16.0  | 1        | 4.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 11       | 57.89%  |
| 2      | 6        | 31.58%  |
| 4      | 1        | 5.26%   |
| 3      | 1        | 5.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 10       | 52.63%  |
| No        | 9        | 47.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 19       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 68.42%  |
| Yes       | 6        | 31.58%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 89.47%  |
| Yes       | 2        | 10.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Turkey  | 18       | 94.74%  |
| France  | 1        | 5.26%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City      | Desktops | Percent |
|-----------|----------|---------|
| Bursa     | 4        | 21.05%  |
| Aydin     | 4        | 21.05%  |
| Ankara    | 4        | 21.05%  |
| Istanbul  | 3        | 15.79%  |
| Yaman     | 1        | 5.26%   |
| Soleymieu | 1        | 5.26%   |
| Niğde    | 1        | 5.26%   |
| Konya     | 1        | 5.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 6      | 17.24%  |
| Seagate             | 5        | 8      | 17.24%  |
| SanDisk             | 3        | 3      | 10.34%  |
| Samsung Electronics | 3        | 8      | 10.34%  |
| A-DATA Technology   | 3        | 3      | 10.34%  |
| KIOXIA-EXCERIA      | 2        | 2      | 6.9%    |
| Corsair             | 2        | 2      | 6.9%    |
| China               | 2        | 2      | 6.9%    |
| Team                | 1        | 1      | 3.45%   |
| KIOXIA              | 1        | 1      | 3.45%   |
| Kingston            | 1        | 1      | 3.45%   |
| 120G                | 1        | 1      | 3.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| WDC WD6402AAEX-00Y9A0 640GB      | 3        | 9.68%   |
| A-DATA SU650 120GB SSD           | 3        | 9.68%   |
| Seagate ST500DM002-1BD142 500GB  | 2        | 6.45%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 1        | 3.23%   |
| WDC WD3200AAJB-00WGA0 320GB      | 1        | 3.23%   |
| Team T253X1240G 240GB SSD        | 1        | 3.23%   |
| Seagate ST3160318AS 160GB        | 1        | 3.23%   |
| Seagate ST2000DM008-2UB102 2TB   | 1        | 3.23%   |
| Seagate ST2000DM008-2FR102 2TB   | 1        | 3.23%   |
| SanDisk Ultra II 240GB SSD       | 1        | 3.23%   |
| SanDisk SSD PLUS 240GB           | 1        | 3.23%   |
| SanDisk SDSSDA240G 240GB         | 1        | 3.23%   |
| Samsung NVMe SSD Drive 512GB     | 1        | 3.23%   |
| Samsung MZALQ512HALU-000L1 512GB | 1        | 3.23%   |
| Samsung HD501LJ 500GB            | 1        | 3.23%   |
| Samsung HD160HJ 160GB            | 1        | 3.23%   |
| Samsung HD103SJ 1TB              | 1        | 3.23%   |
| KIOXIA-EXCERIA SATA SSD 480GB    | 1        | 3.23%   |
| KIOXIA-EXCERIA SATA SSD 240GB    | 1        | 3.23%   |
| KIOXIA KBG50ZNS256G NVMe 256GB   | 1        | 3.23%   |
| Kingston SV300S37A120G 120GB SSD | 1        | 3.23%   |
| Corsair MP600 PRO 1TB            | 1        | 3.23%   |
| Corsair Force LS SSD 64GB        | 1        | 3.23%   |
| China SATA SSD 240GB             | 1        | 3.23%   |
| China SATA SSD 120GB             | 1        | 3.23%   |
| 120G SSD 120GB                   | 1        | 3.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 6      | 41.67%  |
| Seagate             | 5        | 8      | 41.67%  |
| Samsung Electronics | 2        | 5      | 16.67%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| SanDisk           | 3        | 3      | 21.43%  |
| A-DATA Technology | 3        | 3      | 21.43%  |
| KIOXIA-EXCERIA    | 2        | 2      | 14.29%  |
| China             | 2        | 2      | 14.29%  |
| Team              | 1        | 1      | 7.14%   |
| Kingston          | 1        | 1      | 7.14%   |
| Corsair           | 1        | 1      | 7.14%   |
| 120G              | 1        | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 12       | 14     | 48%     |
| HDD  | 10       | 19     | 40%     |
| NVMe | 3        | 5      | 12%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 18       | 33     | 85.71%  |
| NVMe | 3        | 5      | 14.29%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 16       | 24     | 72.73%  |
| 0.51-1.0   | 4        | 5      | 18.18%  |
| 1.01-2.0   | 2        | 4      | 9.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 9        | 47.37%  |
| 251-500    | 5        | 26.32%  |
| 501-1000   | 3        | 15.79%  |
| 2001-3000  | 1        | 5.26%   |
| 51-100     | 1        | 5.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 51-100   | 6        | 31.58%  |
| 21-50    | 4        | 21.05%  |
| 1-20     | 4        | 21.05%  |
| 251-500  | 2        | 10.53%  |
| 101-250  | 2        | 10.53%  |
| 501-1000 | 1        | 5.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB  | 1        | 1      | 50%     |
| Kingston SV300S37A120G 120GB SSD | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Seagate  | 1        | 1      | 50%     |
| Kingston | 1        | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 1        | 1      | 50%     |
| HDD  | 1        | 1      | 50%     |

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
| Detected | 14       | 28     | 66.67%  |
| Works    | 5        | 8      | 23.81%  |
| Malfunc  | 2        | 2      | 9.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 16       | 64%     |
| Marvell Technology Group | 3        | 12%     |
| AMD                      | 3        | 12%     |
| Samsung Electronics      | 1        | 4%      |
| Phison Electronics       | 1        | 4%      |
| KIOXIA                   | 1        | 4%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 3        | 8.82%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 3        | 8.82%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 3        | 8.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 8.82%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 3        | 8.82%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 5.88%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 5.88%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 5.88%   |
| AMD FCH SATA Controller D                                                               | 2        | 5.88%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 1        | 2.94%   |
| Phison E18 PCIe4 NVMe Controller                                                        | 1        | 2.94%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                              | 1        | 2.94%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 2.94%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 2.94%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 2.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 2.94%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 2.94%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 2.94%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 12       | 54.55%  |
| IDE  | 7        | 31.82%  |
| NVMe | 3        | 13.64%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 16       | 84.21%  |
| AMD    | 3        | 15.79%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 3        | 15.79%  |
| Intel Pentium CPU G2010 @ 2.80GHz             | 1        | 5.26%   |
| Intel Core i9-9900 CPU @ 3.10GHz              | 1        | 5.26%   |
| Intel Core i7-4790S CPU @ 3.20GHz             | 1        | 5.26%   |
| Intel Core i5-7600 CPU @ 3.50GHz              | 1        | 5.26%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 1        | 5.26%   |
| Intel Core i5-4440 CPU @ 3.10GHz              | 1        | 5.26%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 1        | 5.26%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 1        | 5.26%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1        | 5.26%   |
| Intel Core i3-9100F CPU @ 3.60GHz             | 1        | 5.26%   |
| Intel Core i3 CPU 540 @ 3.07GHz               | 1        | 5.26%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz         | 1        | 5.26%   |
| Intel 12th Gen Core i5-12500T                 | 1        | 5.26%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 1        | 5.26%   |
| AMD Ryzen 5 3500X 6-Core Processor            | 1        | 5.26%   |
| AMD A8-9600 RADEON R7, 10 COMPUTE CORES 4C+6G | 1        | 5.26%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 6        | 31.58%  |
| Intel Core 2 Quad | 4        | 21.05%  |
| Intel Core i3     | 2        | 10.53%  |
| Other             | 1        | 5.26%   |
| Intel Pentium     | 1        | 5.26%   |
| Intel Core i9     | 1        | 5.26%   |
| Intel Core i7     | 1        | 5.26%   |
| AMD Ryzen 7       | 1        | 5.26%   |
| AMD Ryzen 5       | 1        | 5.26%   |
| AMD A8            | 1        | 5.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 9        | 47.37%  |
| 6      | 4        | 21.05%  |
| 2      | 4        | 21.05%  |
| 8      | 2        | 10.53%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 19       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 10       | 52.63%  |
| 2      | 9        | 47.37%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 19       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 11       | 52.38%  |
| 0x306c3    | 2        | 9.52%   |
| 0x906ed    | 1        | 4.76%   |
| 0x906eb    | 1        | 4.76%   |
| 0x906e9    | 1        | 4.76%   |
| 0x90675    | 1        | 4.76%   |
| 0x306a9    | 1        | 4.76%   |
| 0x20655    | 1        | 4.76%   |
| 0x1067a    | 1        | 4.76%   |
| 0x0a50000d | 1        | 4.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| KabyLake  | 3        | 15.79%  |
| Haswell   | 3        | 15.79%  |
| Core      | 3        | 15.79%  |
| Westmere  | 2        | 10.53%  |
| CometLake | 2        | 10.53%  |
| Zen 3     | 1        | 5.26%   |
| Zen 2     | 1        | 5.26%   |
| Penryn    | 1        | 5.26%   |
| IvyBridge | 1        | 5.26%   |
| Excavator | 1        | 5.26%   |
| Unknown   | 1        | 5.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 8        | 34.78%  |
| Intel  | 8        | 34.78%  |
| AMD    | 7        | 30.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GT200 [GeForce GTX 260]                                              | 3        | 13.04%  |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 8.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 8.7%    |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 4.35%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 4.35%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 4.35%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 4.35%   |
| Intel HD Graphics 630                                                       | 1        | 4.35%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 4.35%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 4.35%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 4.35%   |
| Intel Alder Lake-S GT1 [UHD Graphics 770]                                   | 1        | 4.35%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1        | 4.35%   |
| AMD RV630 PRO [Radeon HD 2600 PRO]                                          | 1        | 4.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 4.35%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 1        | 4.35%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 4.35%   |
| AMD Bonaire XT [Radeon HD 7790/8770 / R7 360 / R9 260/360 OEM]              | 1        | 4.35%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 4.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 7        | 36.84%  |
| 1 x AMD      | 6        | 31.58%  |
| 1 x Intel    | 5        | 26.32%  |
| AMD + Nvidia | 1        | 5.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 17       | 89.47%  |
| Proprietary | 2        | 10.53%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 70%     |
| 1.01-2.0   | 2        | 10%     |
| 0.51-1.0   | 2        | 10%     |
| 0.01-0.5   | 2        | 10%     |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 5        | 23.81%  |
| Samsung Electronics  | 3        | 14.29%  |
| Dell                 | 3        | 14.29%  |
| Acer                 | 2        | 9.52%   |
| SAC                  | 1        | 4.76%   |
| Philips              | 1        | 4.76%   |
| Iiyama               | 1        | 4.76%   |
| HKC                  | 1        | 4.76%   |
| Hewlett-Packard      | 1        | 4.76%   |
| Beko                 | 1        | 4.76%   |
| Ancor Communications | 1        | 4.76%   |
| AGO                  | 1        | 4.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar W2242 GSM5678 1680x1050 490x320mm 23.0-inch                  | 3        | 13.64%  |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1        | 4.55%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch     | 1        | 4.55%   |
| Samsung Electronics SyncMaster SAM0599 1600x900 443x249mm 20.0-inch   | 1        | 4.55%   |
| Samsung Electronics S27H65x SAM0E1E 1920x1080 598x336mm 27.0-inch     | 1        | 4.55%   |
| SAC Casper SAC3219 1366x768 304x228mm 15.0-inch                       | 1        | 4.55%   |
| Philips PHL 243B9 PHL0941 1920x1080 527x296mm 23.8-inch               | 1        | 4.55%   |
| Iiyama PLX2380H IVM5621 1920x1080 509x286mm 23.0-inch                 | 1        | 4.55%   |
| HKC '' HKC2160 1920x1080 360x270mm 17.7-inch                          | 1        | 4.55%   |
| Hewlett-Packard HPQ 800 AIO HWP1080 1920x1080 510x287mm 23.0-inch     | 1        | 4.55%   |
| Goldstar L1753T GSM4476 1280x1024 338x270mm 17.0-inch                 | 1        | 4.55%   |
| Goldstar E2242 GSM58BE 1920x1080 477x268mm 21.5-inch                  | 1        | 4.55%   |
| Dell SE2416H DELD082 1920x1080 530x300mm 24.0-inch                    | 1        | 4.55%   |
| Dell P2717H DEL40F6 1920x1080 598x336mm 27.0-inch                     | 1        | 4.55%   |
| Dell E2421HN DELF129 1920x1080 530x300mm 24.0-inch                    | 1        | 4.55%   |
| Beko BK WUXGA BEK4448 1920x1080 1210x680mm 54.6-inch                  | 1        | 4.55%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 1        | 4.55%   |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch                 | 1        | 4.55%   |
| Acer V226HQL ACR032D 1920x1080 477x268mm 21.5-inch                    | 1        | 4.55%   |
| Acer G206HQL ACR0327 1600x900 432x239mm 19.4-inch                     | 1        | 4.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 10       | 52.63%  |
| 1680x1050 (WSXGA+) | 3        | 15.79%  |
| 3840x2160 (4K)     | 2        | 10.53%  |
| 1600x900 (HD+)     | 2        | 10.53%  |
| 1366x768 (WXGA)    | 1        | 5.26%   |
| 1280x1024 (SXGA)   | 1        | 5.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 23     | 6        | 28.57%  |
| 21     | 3        | 14.29%  |
| 27     | 2        | 9.52%   |
| 24     | 2        | 9.52%   |
| 17     | 2        | 9.52%   |
| 72     | 1        | 4.76%   |
| 31     | 1        | 4.76%   |
| 20     | 1        | 4.76%   |
| 19     | 1        | 4.76%   |
| 15     | 1        | 4.76%   |
| 12     | 1        | 4.76%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 8        | 40%     |
| 501-600     | 6        | 30%     |
| 301-350     | 2        | 10%     |
| 601-700     | 1        | 5%      |
| 351-400     | 1        | 5%      |
| 201-300     | 1        | 5%      |
| 1501-2000   | 1        | 5%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 11       | 61.11%  |
| 4/3   | 3        | 16.67%  |
| 3/2   | 3        | 16.67%  |
| 5/4   | 1        | 5.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 10       | 50%     |
| 151-200        | 3        | 15%     |
| 301-350        | 2        | 10%     |
| More than 1000 | 1        | 5%      |
| 71-80          | 1        | 5%      |
| 351-500        | 1        | 5%      |
| 141-150        | 1        | 5%      |
| 101-110        | 1        | 5%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 12       | 60%     |
| 101-120 | 4        | 20%     |
| 121-160 | 2        | 10%     |
| 1-50    | 1        | 5%      |
| 161-240 | 1        | 5%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 16       | 84.21%  |
| 2     | 3        | 15.79%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 15       | 62.5%   |
| Intel                 | 5        | 20.83%  |
| Ralink Technology     | 2        | 8.33%   |
| ZyXEL Communications  | 1        | 4.17%   |
| Aquantia              | 1        | 4.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 14       | 51.85%  |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]        | 1        | 3.7%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 1        | 3.7%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter               | 1        | 3.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 1        | 3.7%    |
| Realtek 802.11n WLAN Adapter                                        | 1        | 3.7%    |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1        | 3.7%    |
| Ralink MT7601U Wireless Adapter                                     | 1        | 3.7%    |
| Intel Wi-Fi 6 AX200                                                 | 1        | 3.7%    |
| Intel Ethernet Controller I225-V                                    | 1        | 3.7%    |
| Intel Ethernet Connection I217-LM                                   | 1        | 3.7%    |
| Intel Ethernet Connection (7) I219-LM                               | 1        | 3.7%    |
| Intel Ethernet Connection (2) I219-V                                | 1        | 3.7%    |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 3.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 3        | 42.86%  |
| Ralink Technology     | 2        | 28.57%  |
| ZyXEL Communications  | 1        | 14.29%  |
| Intel                 | 1        | 14.29%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU] | 1        | 14.29%  |
| Realtek RTL8192CU 802.11n WLAN Adapter                       | 1        | 14.29%  |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter        | 1        | 14.29%  |
| Realtek 802.11n WLAN Adapter                                 | 1        | 14.29%  |
| Ralink RT2870/RT3070 Wireless Adapter                        | 1        | 14.29%  |
| Ralink MT7601U Wireless Adapter                              | 1        | 14.29%  |
| Intel Wi-Fi 6 AX200                                          | 1        | 14.29%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 15       | 75%     |
| Intel                 | 4        | 20%     |
| Aquantia              | 1        | 5%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 14       | 70%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 1        | 5%      |
| Intel Ethernet Controller I225-V                                    | 1        | 5%      |
| Intel Ethernet Connection I217-LM                                   | 1        | 5%      |
| Intel Ethernet Connection (7) I219-LM                               | 1        | 5%      |
| Intel Ethernet Connection (2) I219-V                                | 1        | 5%      |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 5%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 19       | 76%     |
| WiFi     | 6        | 24%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 16       | 80%     |
| WiFi     | 4        | 20%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 17       | 89.47%  |
| 2     | 2        | 10.53%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 18       | 94.74%  |
| Yes  | 1        | 5.26%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 1        | 50%     |
| Cambridge Silicon Radio | 1        | 50%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 1        | 50%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 50%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 16       | 57.14%  |
| AMD                 | 7        | 25%     |
| Nvidia              | 4        | 14.29%  |
| Kingston Technology | 1        | 3.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 9.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 9.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 6.25%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 6.25%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 3.13%   |
| Nvidia High Definition Audio Controller                                    | 1        | 3.13%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 3.13%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 3.13%   |
| Kingston Technology HyperX QuadCast S                                      | 1        | 3.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 3.13%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1        | 3.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 3.13%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 3.13%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 3.13%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 3.13%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 1        | 3.13%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1        | 3.13%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                     | 1        | 3.13%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 3.13%   |
| AMD Kabini HDMI/DP Audio                                                   | 1        | 3.13%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 3.13%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1        | 3.13%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 3.13%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 3.13%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 3.13%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 2        | 22.22%  |
| Kingston            | 2        | 22.22%  |
| G.Skill             | 2        | 22.22%  |
| Micron Technology   | 1        | 11.11%  |
| A-DATA Technology   | 1        | 11.11%  |
| Unknown             | 1        | 11.11%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s   | 1        | 10%     |
| Samsung RAM M378A2K43DB1-CTD 16384MB DIMM DDR4 2667MT/s | 1        | 10%     |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s    | 1        | 10%     |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 3400MT/s    | 1        | 10%     |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2666MT/s       | 1        | 10%     |
| Kingston RAM 99U5471-057.A00LF 8GB DIMM DDR3 1333MT/s   | 1        | 10%     |
| G.Skill RAM F4-3200C16-32GTZN 32GB DIMM DDR4 3200MT/s   | 1        | 10%     |
| G.Skill RAM F4-2133C15-4GIS 4GB DIMM DDR4 2133MT/s      | 1        | 10%     |
| A-DATA RAM Module 8GB DIMM DDR4 2667MT/s                | 1        | 10%     |
| Unknown                                                 | 1        | 10%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 6        | 75%     |
| DDR3 | 2        | 25%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 6        | 75%     |
| SODIMM | 2        | 25%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 5        | 62.5%   |
| 32768 | 1        | 12.5%   |
| 16384 | 1        | 12.5%   |
| 4096  | 1        | 12.5%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 2        | 22.22%  |
| 2667  | 2        | 22.22%  |
| 3400  | 1        | 11.11%  |
| 2666  | 1        | 11.11%  |
| 2133  | 1        | 11.11%  |
| 1600  | 1        | 11.11%  |
| 1333  | 1        | 11.11%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Zebra  | 3        | 75%     |
| Canon  | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Zebra TLP2844                    | 2        | 50%     |
| Zebra Zebra GC420d Label Printer | 1        | 25%     |
| Canon LBP6000                    | 1        | 25%     |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 1        | 16.67%  |
| Microdia              | 1        | 16.67%  |
| MacroSilicon          | 1        | 16.67%  |
| Arkmicro Technologies | 1        | 16.67%  |
| Allwinner Technology  | 1        | 16.67%  |
| Alcor Micro           | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Realtek HP 2.0MP High Definition Webcam | 1        | 16.67%  |
| Microdia Integrated Camera              | 1        | 16.67%  |
| MacroSilicon USB Video                  | 1        | 16.67%  |
| Arkmicro USB2.0 PC CAMERA               | 1        | 16.67%  |
| Allwinner TP1005                        | 1        | 16.67%  |
| Alcor Micro USB 2.0 PC Camera           | 1        | 16.67%  |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Advanced Card Systems | 2        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Advanced Card Systems ACR38 SmartCard Reader | 2        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 15       | 75%     |
| 1     | 5        | 25%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 1        | 20%     |
| Graphics card            | 1        | 20%     |
| Communication controller | 1        | 20%     |
| Chipcard                 | 1        | 20%     |
| Camera                   | 1        | 20%     |

