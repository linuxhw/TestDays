Pardus - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Pardus.

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Sony          | SVF1521QSTB                 | [f74068fef9](https://linux-hardware.org/?probe=f74068fef9) | Feb 14, 2022 |
| HP            | Pavilion 15                 | [fe001e576b](https://linux-hardware.org/?probe=fe001e576b) | Feb 13, 2022 |
| Packard Be... | EasyNote ENTG81BA           | [10f68b4c82](https://linux-hardware.org/?probe=10f68b4c82) | Jan 31, 2022 |
| Lenovo        | V145-15AST 81MT             | [121a750c5b](https://linux-hardware.org/?probe=121a750c5b) | Jan 03, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [16efe9685d](https://linux-hardware.org/?probe=16efe9685d) | Dec 17, 2021 |
| Toshiba       | PORTEGE M780                | [c68379ab38](https://linux-hardware.org/?probe=c68379ab38) | Nov 30, 2021 |
| HP            | Laptop 15-dw3xxx            | [1cf8a783be](https://linux-hardware.org/?probe=1cf8a783be) | Oct 21, 2021 |
| HP            | Laptop 15-dw3xxx            | [20a54c9779](https://linux-hardware.org/?probe=20a54c9779) | Oct 21, 2021 |
| Lenovo        | IdeaPad-510-15IKB 80SV      | [1a343f3596](https://linux-hardware.org/?probe=1a343f3596) | Sep 02, 2021 |
| Philco        | 14F                         | [343861b100](https://linux-hardware.org/?probe=343861b100) | Jun 20, 2021 |
| Toshiba       | Satellite C855-1VM          | [dab32c2669](https://linux-hardware.org/?probe=dab32c2669) | Jan 24, 2021 |
| Lenovo        | ThinkPad T450 20BUS39Y00    | [579099bf91](https://linux-hardware.org/?probe=579099bf91) | Dec 26, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [39f1d96886](https://linux-hardware.org/?probe=39f1d96886) | Dec 16, 2020 |
| ASUSTek       | X555YI                      | [d210c4b901](https://linux-hardware.org/?probe=d210c4b901) | Sep 26, 2020 |
| Packard Be... | EasyNote_GN45               | [210b740311](https://linux-hardware.org/?probe=210b740311) | Sep 24, 2020 |
| Dell          | Latitude E6540              | [d2337e32c1](https://linux-hardware.org/?probe=d2337e32c1) | Sep 05, 2020 |
| ASUSTek       | E402BP                      | [d531d0fe45](https://linux-hardware.org/?probe=d531d0fe45) | Jun 01, 2020 |
| HP            | 15                          | [36d90829ee](https://linux-hardware.org/?probe=36d90829ee) | May 02, 2020 |
| HP            | 15                          | [06393a1175](https://linux-hardware.org/?probe=06393a1175) | Apr 27, 2020 |
| HP            | 15                          | [e21973794b](https://linux-hardware.org/?probe=e21973794b) | Feb 02, 2020 |
| Dell          | G5 5587                     | [1742540bc9](https://linux-hardware.org/?probe=1742540bc9) | Nov 27, 2019 |
| Lenovo        | V110-15ISK 80TL             | [dd8de8c9a2](https://linux-hardware.org/?probe=dd8de8c9a2) | Oct 18, 2019 |
| HP            | 250 G3                      | [e82ead9af0](https://linux-hardware.org/?probe=e82ead9af0) | Oct 13, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 4.19.0-6-amd64       | 3         | 14.29%  |
| 4.19.0-10-amd64      | 3         | 14.29%  |
| 5.10.0-9-amd64       | 2         | 9.52%   |
| 5.10.0-11-amd64      | 2         | 9.52%   |
| 5.10.0-10-amd64      | 2         | 9.52%   |
| 4.19.0-13-amd64      | 2         | 9.52%   |
| 5.9.0-0.bpo.2-amd64  | 1         | 4.76%   |
| 5.4.0-0.bpo.3-amd64  | 1         | 4.76%   |
| 5.10.0-8-amd64       | 1         | 4.76%   |
| 5.10.0-0.bpo.8-amd64 | 1         | 4.76%   |
| 4.19.0-8-amd64       | 1         | 4.76%   |
| 4.19.0-5-amd64       | 1         | 4.76%   |
| 4.19.0-16-amd64      | 1         | 4.76%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.19.0  | 10        | 50%     |
| 5.10.0  | 8         | 40%     |
| 5.9.0   | 1         | 5%      |
| 5.4.0   | 1         | 5%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.19    | 10        | 50%     |
| 5.10    | 8         | 40%     |
| 5.9     | 1         | 5%      |
| 5.4     | 1         | 5%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 20        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| XFCE    | 14        | 70%     |
| GNOME   | 3         | 15%     |
| Unknown | 2         | 10%     |
| KDE5    | 1         | 5%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 20        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 12        | 60%     |
| TDM     | 6         | 30%     |
| LightDM | 1         | 5%      |
| GDM     | 1         | 5%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| tr_TR   | 14        | 70%     |
| Unknown | 3         | 15%     |
| pt_BR   | 1         | 5%      |
| en_US   | 1         | 5%      |
| en_GB   | 1         | 5%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 15        | 75%     |
| EFI  | 5         | 25%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ext4 | 20        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 13        | 65%     |
| GPT     | 5         | 25%     |
| MBR     | 2         | 10%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 19        | 95%     |
| Yes       | 1         | 5%      |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 16        | 80%     |
| Yes       | 4         | 20%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 5         | 25%     |
| Hewlett-Packard     | 4         | 20%     |
| Toshiba             | 2         | 10%     |
| Packard Bell        | 2         | 10%     |
| Dell                | 2         | 10%     |
| ASUSTek Computer    | 2         | 10%     |
| Sony                | 1         | 5%      |
| Samsung Electronics | 1         | 5%      |
| Philco              | 1         | 5%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Toshiba Satellite C855-1VM                 | 1         | 5%      |
| Toshiba PORTEGE M780                       | 1         | 5%      |
| Sony SVF1521QSTB                           | 1         | 5%      |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 5%      |
| Philco 14F                                 | 1         | 5%      |
| Packard Bell EasyNote_GN45                 | 1         | 5%      |
| Packard Bell EasyNote ENTG81BA             | 1         | 5%      |
| Lenovo V145-15AST 81MT                     | 1         | 5%      |
| Lenovo V110-15ISK 80TL                     | 1         | 5%      |
| Lenovo ThinkPad T450 20BUS39Y00            | 1         | 5%      |
| Lenovo IdeaPad-510-15IKB 80SV              | 1         | 5%      |
| Lenovo IdeaPad 320-15IKB 81BT              | 1         | 5%      |
| HP Pavilion 15                             | 1         | 5%      |
| HP Laptop 15-dw3xxx                        | 1         | 5%      |
| HP 250 G3                                  | 1         | 5%      |
| HP 15                                      | 1         | 5%      |
| Dell Latitude E6540                        | 1         | 5%      |
| Dell G5 5587                               | 1         | 5%      |
| ASUS X555YI                                | 1         | 5%      |
| ASUS E402BP                                | 1         | 5%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Packard Bell EasyNote    | 2         | 10%     |
| Toshiba Satellite        | 1         | 5%      |
| Toshiba PORTEGE          | 1         | 5%      |
| Sony SVF1521QSTB         | 1         | 5%      |
| Samsung 300E4A           | 1         | 5%      |
| Philco 14F               | 1         | 5%      |
| Lenovo V145-15AST        | 1         | 5%      |
| Lenovo V110-15ISK        | 1         | 5%      |
| Lenovo ThinkPad          | 1         | 5%      |
| Lenovo IdeaPad-510-15IKB | 1         | 5%      |
| Lenovo IdeaPad           | 1         | 5%      |
| HP Pavilion              | 1         | 5%      |
| HP Laptop                | 1         | 5%      |
| HP 250                   | 1         | 5%      |
| HP 15                    | 1         | 5%      |
| Dell Latitude            | 1         | 5%      |
| Dell G5                  | 1         | 5%      |
| ASUS X555YI              | 1         | 5%      |
| ASUS E402BP              | 1         | 5%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 5         | 25%     |
| 2018 | 4         | 20%     |
| 2015 | 3         | 15%     |
| 2011 | 2         | 10%     |
| 2020 | 1         | 5%      |
| 2019 | 1         | 5%      |
| 2016 | 1         | 5%      |
| 2014 | 1         | 5%      |
| 2010 | 1         | 5%      |
| 2006 | 1         | 5%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 20        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 20        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 20        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 8         | 40%     |
| 4.01-8.0   | 6         | 30%     |
| 16.01-24.0 | 2         | 10%     |
| 1.01-2.0   | 2         | 10%     |
| 8.01-16.0  | 2         | 10%     |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 10        | 50%     |
| 2.01-3.0 | 5         | 25%     |
| 4.01-8.0 | 2         | 10%     |
| 3.01-4.0 | 2         | 10%     |
| 0.51-1.0 | 1         | 5%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 17        | 85%     |
| 2      | 2         | 10%     |
| 3      | 1         | 5%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 13        | 65%     |
| No        | 7         | 35%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 95%     |
| No        | 1         | 5%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 17        | 85%     |
| No        | 3         | 15%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Turkey  | 18        | 90%     |
| UK      | 1         | 5%      |
| Brazil  | 1         | 5%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Istanbul      | 7         | 33.33%  |
| Izmir         | 2         | 9.52%   |
| Bursa         | 2         | 9.52%   |
| Г‡anakkale | 1         | 4.76%   |
| Porto Alegre  | 1         | 4.76%   |
| Mersin        | 1         | 4.76%   |
| Malatya       | 1         | 4.76%   |
| London        | 1         | 4.76%   |
| Kosekoy       | 1         | 4.76%   |
| Konya         | 1         | 4.76%   |
| Gaziantep     | 1         | 4.76%   |
| Antalya       | 1         | 4.76%   |
| Ankara        | 1         | 4.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 7      | 21.74%  |
| Seagate             | 4         | 4      | 17.39%  |
| Samsung Electronics | 3         | 3      | 13.04%  |
| SK Hynix            | 2         | 2      | 8.7%    |
| HGST                | 2         | 2      | 8.7%    |
| SPCC                | 1         | 1      | 4.35%   |
| SanDisk             | 1         | 1      | 4.35%   |
| Lexar               | 1         | 1      | 4.35%   |
| Kingston            | 1         | 1      | 4.35%   |
| KingSpec            | 1         | 1      | 4.35%   |
| Hitachi             | 1         | 1      | 4.35%   |
| addlink             | 1         | 1      | 4.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| HGST HTS545050A7E680 500GB                  | 2         | 8.7%    |
| WDC WD5000LPVX-55V0TT0 500GB                | 1         | 4.35%   |
| WDC WD5000LPCX-21VHAT0 500GB                | 1         | 4.35%   |
| WDC WD3200BPVT-35JJ5T0 320GB                | 1         | 4.35%   |
| WDC WD10JPVX-60JC3T0 1TB                    | 1         | 4.35%   |
| WDC WD10JPCX-24UE4T0 1TB                    | 1         | 4.35%   |
| SPCC Solid State Disk 512GB                 | 1         | 4.35%   |
| SK Hynix SC311 SATA 256GB SSD               | 1         | 4.35%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB     | 1         | 4.35%   |
| Seagate ST9120822AS 120GB                   | 1         | 4.35%   |
| Seagate ST1000LM035-1RK172 1TB              | 1         | 4.35%   |
| Seagate Expansion+ 2TB                      | 1         | 4.35%   |
| Seagate BarraCuda Q1 SSD ZA480CV10001 480GB | 1         | 4.35%   |
| SanDisk SDSSDA480G 480GB                    | 1         | 4.35%   |
| Samsung SSD 860 EVO 500GB                   | 1         | 4.35%   |
| Samsung MZ7LN128HAHQ-000L2 128GB SSD        | 1         | 4.35%   |
| Samsung MZ7LF192HCGS-000L1 192GB SSD        | 1         | 4.35%   |
| Lexar 120GB SSD                             | 1         | 4.35%   |
| Kingston SA400S37240G 240GB SSD             | 1         | 4.35%   |
| KingSpec P3-128 128GB                       | 1         | 4.35%   |
| Hitachi HTS545025B9A300 250GB               | 1         | 4.35%   |
| addlink S10 120GB                           | 1         | 4.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 7      | 45.45%  |
| Seagate | 3         | 3      | 27.27%  |
| HGST    | 2         | 2      | 18.18%  |
| Hitachi | 1         | 1      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 30%     |
| SPCC                | 1         | 1      | 10%     |
| SK Hynix            | 1         | 1      | 10%     |
| Seagate             | 1         | 1      | 10%     |
| SanDisk             | 1         | 1      | 10%     |
| Lexar               | 1         | 1      | 10%     |
| Kingston            | 1         | 1      | 10%     |
| KingSpec            | 1         | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 11        | 13     | 50%     |
| SSD     | 9         | 10     | 40.91%  |
| NVMe    | 1         | 1      | 4.55%   |
| Unknown | 1         | 1      | 4.55%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 19        | 23     | 90.48%  |
| SAS  | 1         | 1      | 4.76%   |
| NVMe | 1         | 1      | 4.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 15        | 16     | 75%     |
| 0.51-1.0   | 4         | 6      | 20%     |
| 1.01-2.0   | 1         | 1      | 5%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 9         | 45%     |
| 251-500    | 7         | 35%     |
| 21-50      | 2         | 10%     |
| 501-1000   | 1         | 5%      |
| 51-100     | 1         | 5%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 8         | 40%     |
| 21-50   | 6         | 30%     |
| 51-100  | 4         | 20%     |
| 101-250 | 2         | 10%     |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                     | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9120822AS 120GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

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
| Detected | 13        | 17     | 65%     |
| Works    | 6         | 7      | 30%     |
| Malfunc  | 1         | 1      | 5%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Intel    | 16        | 76.19%  |
| AMD      | 4         | 19.05%  |
| SK Hynix | 1         | 4.76%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 13.64%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 3         | 13.64%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 13.64%  |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 9.09%   |
| SK Hynix BC511                                                                   | 1         | 4.55%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 4.55%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 1         | 4.55%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 4.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 4.55%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 4.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 4.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 4.55%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 4.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 4.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 19        | 86.36%  |
| RAID | 1         | 4.55%   |
| NVMe | 1         | 4.55%   |
| IDE  | 1         | 4.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 16        | 80%     |
| AMD    | 4         | 20%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Pentium CPU B960 @ 2.20GHz             | 1         | 5%      |
| Intel Pentium CPU B950 @ 2.10GHz             | 1         | 5%      |
| Intel Core i7-8750H CPU @ 2.20GHz            | 1         | 5%      |
| Intel Core i7-5500U CPU @ 2.40GHz            | 1         | 5%      |
| Intel Core i7-4800MQ CPU @ 2.70GHz           | 1         | 5%      |
| Intel Core i5-8250U CPU @ 1.60GHz            | 1         | 5%      |
| Intel Core i5-7200U CPU @ 2.50GHz            | 1         | 5%      |
| Intel Core i5-5200U CPU @ 2.20GHz            | 1         | 5%      |
| Intel Core i5-3230M CPU @ 2.60GHz            | 1         | 5%      |
| Intel Core i3-6006U CPU @ 2.00GHz            | 1         | 5%      |
| Intel Core i3-4005U CPU @ 1.70GHz            | 1         | 5%      |
| Intel Core i3-3227U CPU @ 1.90GHz            | 1         | 5%      |
| Intel Core i3 CPU M 370 @ 2.40GHz            | 1         | 5%      |
| Intel Core 2 CPU T5600 @ 1.83GHz             | 1         | 5%      |
| Intel Celeron CPU N3050 @ 1.60GHz            | 1         | 5%      |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz      | 1         | 5%      |
| AMD C-50 Processor                           | 1         | 5%      |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 5%      |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 5%      |
| AMD A8-7410 APU with AMD Radeon R5 Graphics  | 1         | 5%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Intel Core i5 | 4         | 20%     |
| Intel Core i3 | 4         | 20%     |
| Other         | 3         | 15%     |
| Intel Core i7 | 3         | 15%     |
| Intel Pentium | 2         | 10%     |
| Intel Core 2  | 1         | 5%      |
| Intel Celeron | 1         | 5%      |
| AMD C-50      | 1         | 5%      |
| AMD A8        | 1         | 5%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 16        | 80%     |
| 4      | 3         | 15%     |
| 6      | 1         | 5%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 20        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 12        | 60%     |
| 1      | 8         | 40%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 20        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 70%     |
| 0x906ea    | 1         | 5%      |
| 0x6f6      | 1         | 5%      |
| 0x406e3    | 1         | 5%      |
| 0x07030105 | 1         | 5%      |
| 0x06006705 | 1         | 5%      |
| 0x05000029 | 1         | 5%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 3         | 15%     |
| SandyBridge | 2         | 10%     |
| IvyBridge   | 2         | 10%     |
| Haswell     | 2         | 10%     |
| Excavator   | 2         | 10%     |
| Broadwell   | 2         | 10%     |
| Westmere    | 1         | 5%      |
| TigerLake   | 1         | 5%      |
| Skylake     | 1         | 5%      |
| Silvermont  | 1         | 5%      |
| Puma        | 1         | 5%      |
| Core        | 1         | 5%      |
| Bobcat      | 1         | 5%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 16        | 59.26%  |
| AMD    | 7         | 25.93%  |
| Nvidia | 4         | 14.81%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 6.45%   |
| Intel HD Graphics 5500                                                                   | 2         | 6.45%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 6.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 6.45%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 6.45%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 6.45%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 3.23%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 3.23%   |
| Intel UHD Graphics 620                                                                   | 1         | 3.23%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 3.23%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 3.23%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 3.23%   |
| Intel HD Graphics 620                                                                    | 1         | 3.23%   |
| Intel HD Graphics 520                                                                    | 1         | 3.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 3.23%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 3.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 3.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 3.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 3.23%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 3.23%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 3.23%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 3.23%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 3.23%   |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 1         | 3.23%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 1         | 3.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 9         | 45%     |
| Intel + Nvidia | 4         | 20%     |
| 2 x AMD        | 3         | 15%     |
| Intel + AMD    | 3         | 15%     |
| 1 x AMD        | 1         | 5%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver | Notebooks | Percent |
|--------|-----------|---------|
| Free   | 20        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 80%     |
| 0.01-0.5   | 3         | 15%     |
| 5.01-6.0   | 1         | 5%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 3         | 16.67%  |
| LG Display              | 3         | 16.67%  |
| Chimei Innolux          | 3         | 16.67%  |
| BOE                     | 3         | 16.67%  |
| AU Optronics            | 3         | 16.67%  |
| LG Philips              | 1         | 5.56%   |
| Goldstar                | 1         | 5.56%   |
| Chi Mei Optoelectronics | 1         | 5.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch     | 1         | 5.26%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 1         | 5.26%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 5.26%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 1         | 5.26%   |
| LG Philips LCD Monitor LPL1146 1280x800 331x207mm 15.4-inch              | 1         | 5.26%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 1         | 5.26%   |
| LG Display LCD Monitor LGD0470 1920x1080 345x194mm 15.6-inch             | 1         | 5.26%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 1         | 5.26%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                   | 1         | 5.26%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 5.26%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x194mm 15.5-inch          | 1         | 5.26%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 1         | 5.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO15AB 1366x768 340x190mm 15.3-inch | 1         | 5.26%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 1         | 5.26%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 1         | 5.26%   |
| BOE LCD Monitor BOE065E 1920x1080 344x194mm 15.5-inch                    | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 1         | 5.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 10        | 52.63%  |
| 1920x1080 (FHD)  | 6         | 31.58%  |
| 1600x900 (HD+)   | 1         | 5.26%   |
| 1280x800 (WXGA)  | 1         | 5.26%   |
| 1280x1024 (SXGA) | 1         | 5.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 15        | 78.95%  |
| 23     | 1         | 5.26%   |
| 17     | 1         | 5.26%   |
| 14     | 1         | 5.26%   |
| 13     | 1         | 5.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 94.44%  |
| 501-600     | 1         | 5.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 17        | 89.47%  |
| 5/4   | 1         | 5.26%   |
| 16/10 | 1         | 5.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 15        | 78.95%  |
| 81-90          | 2         | 10.53%  |
| 201-250        | 1         | 5.26%   |
| 141-150        | 1         | 5.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 9         | 47.37%  |
| 121-160 | 6         | 31.58%  |
| 51-100  | 4         | 21.05%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 19        | 95%     |
| 2     | 1         | 5%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 15        | 48.39%  |
| Intel                 | 7         | 22.58%  |
| Qualcomm Atheros      | 3         | 9.68%   |
| Ralink                | 2         | 6.45%   |
| Broadcom              | 2         | 6.45%   |
| JMicron Technology    | 1         | 3.23%   |
| ASUSTek Computer      | 1         | 3.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 25%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 10%     |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 5%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 5%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 5%      |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.5%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 2.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.5%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 2.5%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 2.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 2.5%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.5%    |
| Intel Wireless 7265                                               | 1         | 2.5%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 2.5%    |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.5%    |
| Intel Ethernet Connection (3) I218-V                              | 1         | 2.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 2.5%    |
| Intel Centrino Wireless-N 130                                     | 1         | 2.5%    |
| Intel Centrino Ultimate-N 6300                                    | 1         | 2.5%    |
| Intel Centrino Advanced-N 6200                                    | 1         | 2.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 2.5%    |
| Intel 82577LC Gigabit Network Connection                          | 1         | 2.5%    |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 2.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 2.5%    |
| ASUS Realtek 8188EUS [USB-N10 Nano]                               | 1         | 2.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 7         | 33.33%  |
| Realtek Semiconductor | 6         | 28.57%  |
| Qualcomm Atheros      | 3         | 14.29%  |
| Ralink                | 2         | 9.52%   |
| Broadcom              | 2         | 9.52%   |
| ASUSTek Computer      | 1         | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 2         | 9.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 2         | 9.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 9.52%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 1         | 4.76%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter            | 1         | 4.76%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                  | 1         | 4.76%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                  | 1         | 4.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 4.76%   |
| Intel Wireless 7265                                        | 1         | 4.76%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection      | 1         | 4.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1         | 4.76%   |
| Intel Centrino Wireless-N 130                              | 1         | 4.76%   |
| Intel Centrino Ultimate-N 6300                             | 1         | 4.76%   |
| Intel Centrino Advanced-N 6200                             | 1         | 4.76%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 1         | 4.76%   |
| Broadcom BCM43142 802.11b/g/n                              | 1         | 4.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 1         | 4.76%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                        | 1         | 4.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 15        | 78.95%  |
| Intel                 | 3         | 15.79%  |
| JMicron Technology    | 1         | 5.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 52.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 21.05%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 5.26%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 5.26%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 5.26%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 5.26%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 5.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 20        | 51.28%  |
| Ethernet | 19        | 48.72%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 19        | 59.38%  |
| Ethernet | 13        | 40.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 19        | 95%     |
| 1     | 1         | 5%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 20        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 5         | 29.41%  |
| Intel                           | 4         | 23.53%  |
| Toshiba                         | 2         | 11.76%  |
| Ralink                          | 1         | 5.88%   |
| Qualcomm Atheros Communications | 1         | 5.88%   |
| Lite-On Technology              | 1         | 5.88%   |
| IMC Networks                    | 1         | 5.88%   |
| Foxconn / Hon Hai               | 1         | 5.88%   |
| Broadcom                        | 1         | 5.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Realtek Bluetooth Radio            | 4         | 23.53%  |
| Intel Bluetooth wireless interface | 2         | 11.76%  |
| Intel Bluetooth Device             | 2         | 11.76%  |
| Toshiba RT Bluetooth Radio         | 1         | 5.88%   |
| Toshiba Integrated Bluetooth HCI   | 1         | 5.88%   |
| Realtek RTL8821A Bluetooth         | 1         | 5.88%   |
| Ralink RT3290 Bluetooth            | 1         | 5.88%   |
| Qualcomm Atheros  Bluetooth Device | 1         | 5.88%   |
| Lite-On Atheros AR3012 Bluetooth   | 1         | 5.88%   |
| IMC Networks Bluetooth Device      | 1         | 5.88%   |
| Foxconn / Hon Hai BCM43142A0       | 1         | 5.88%   |
| Broadcom HP Portable Valentine     | 1         | 5.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 76.19%  |
| AMD                   | 4         | 19.05%  |
| Barco Display Systems | 1         | 4.76%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 10.34%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 10.34%  |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 6.9%    |
| Intel Broadwell-U Audio Controller                                                                | 2         | 6.9%    |
| AMD High Definition Audio Controller                                                              | 2         | 6.9%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 6.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 3.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 3.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 3.45%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 3.45%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 3.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 3.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 3.45%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 3.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 3.45%   |
| Barco Display Systems USBGH520-ENC                                                                | 1         | 3.45%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 3.45%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 3.45%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 3.45%   |
| AMD FCH Azalia Controller                                                                         | 1         | 3.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 3         | 37.5%   |
| Unknown (0x4509)    | 1         | 12.5%   |
| Unknown             | 1         | 12.5%   |
| SK Hynix            | 1         | 12.5%   |
| Micron Technology   | 1         | 12.5%   |
| Kingmax             | 1         | 12.5%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2                              | 1         | 12.5%   |
| Unknown (0x4509) RAM GKE800SO102408-2666A 8GB SODIMM DDR4 2133MT/s | 1         | 12.5%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s             | 1         | 12.5%   |
| Samsung RAM M471B5773CHS-CH9 2GB DIMM DDR3 1333MT/s                | 1         | 12.5%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s              | 1         | 12.5%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s           | 1         | 12.5%   |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 1         | 12.5%   |
| Kingmax RAM FSFE85F-C8KL9 2GB DIMM DDR3 1333MT/s                   | 1         | 12.5%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR4  | 4         | 50%     |
| DDR3  | 2         | 25%     |
| SDRAM | 1         | 12.5%   |
| DDR2  | 1         | 12.5%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 6         | 85.71%  |
| DIMM   | 1         | 14.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 3         | 42.86%  |
| 8192 | 2         | 28.57%  |
| 2048 | 2         | 28.57%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 2         | 28.57%  |
| 3200    | 1         | 14.29%  |
| 2133    | 1         | 14.29%  |
| 1600    | 1         | 14.29%  |
| 1333    | 1         | 14.29%  |
| Unknown | 1         | 14.29%  |

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
| Chicony Electronics         | 7         | 41.18%  |
| Microdia                    | 2         | 11.76%  |
| IMC Networks                | 2         | 11.76%  |
| Suyin                       | 1         | 5.88%   |
| Silicon Motion              | 1         | 5.88%   |
| Realtek Semiconductor       | 1         | 5.88%   |
| Luxvisions Innotech Limited | 1         | 5.88%   |
| Lite-On Technology          | 1         | 5.88%   |
| Acer                        | 1         | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony EasyCamera                                  | 2         | 11.76%  |
| Suyin HP Webcam                                     | 1         | 5.88%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 5.88%   |
| Realtek HP Truevision HD integrated webcam          | 1         | 5.88%   |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 5.88%   |
| Microdia Integrated_Webcam_HD                       | 1         | 5.88%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 5.88%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 5.88%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 5.88%   |
| IMC Networks EasyCamera                             | 1         | 5.88%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 5.88%   |
| Chicony Integrated Camera                           | 1         | 5.88%   |
| Chicony HP Truevision HD                            | 1         | 5.88%   |
| Chicony Front Camera                                | 1         | 5.88%   |
| Chicony CNA7157                                     | 1         | 5.88%   |
| Acer EasyCamera                                     | 1         | 5.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 1         | 50%     |
| AuthenTec        | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 50%     |
| AuthenTec AES1600                            | 1         | 50%     |

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


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 14        | 70%     |
| 1     | 4         | 20%     |
| 2     | 2         | 10%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Graphics card      | 3         | 37.5%   |
| Fingerprint reader | 2         | 25%     |
| Chipcard           | 1         | 12.5%   |
| Camera             | 1         | 12.5%   |
| Bluetooth          | 1         | 12.5%   |

