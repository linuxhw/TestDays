Pardus - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

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

Total: 31

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Sony          | SVE14A2V2ES                 | [59435d662a](https://linux-hardware.org/?probe=59435d662a) | May 11, 2022 |
| Acer          | Aspire 5742G                | [b3cef97540](https://linux-hardware.org/?probe=b3cef97540) | Apr 12, 2022 |
| Sony          | SVE14A2V2ES                 | [b2695cc80d](https://linux-hardware.org/?probe=b2695cc80d) | Mar 13, 2022 |
| Sony          | SVE14A2V2ES                 | [4b2203862a](https://linux-hardware.org/?probe=4b2203862a) | Mar 11, 2022 |
| Sony          | SVE14A2V2ES                 | [1575f2f0be](https://linux-hardware.org/?probe=1575f2f0be) | Mar 11, 2022 |
| Sony          | SVE14A2V2ES                 | [ef603529f2](https://linux-hardware.org/?probe=ef603529f2) | Mar 08, 2022 |
| Sony          | SVE14A2V2ES                 | [35fe0c18bc](https://linux-hardware.org/?probe=35fe0c18bc) | Mar 07, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [e60367127e](https://linux-hardware.org/?probe=e60367127e) | Mar 07, 2022 |
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

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Pardus 21.1   | 5         | 20%     |
| Pardus 21.0   | 3         | 12%     |
| Pardus 19.5   | 3         | 12%     |
| Pardus 19.3   | 3         | 12%     |
| Pardus 21.2   | 2         | 8%      |
| Pardus 19.4-1 | 2         | 8%      |
| Pardus 19.2   | 2         | 8%      |
| Pardus 19.1   | 2         | 8%      |
| Pardus 19.0   | 2         | 8%      |
| Pardus 19.4   | 1         | 4%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Pardus | 23        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 5.10.0-11-amd64      | 3         | 12%     |
| 4.19.0-6-amd64       | 3         | 12%     |
| 4.19.0-10-amd64      | 3         | 12%     |
| 5.10.0-9-amd64       | 2         | 8%      |
| 5.10.0-10-amd64      | 2         | 8%      |
| 4.19.0-13-amd64      | 2         | 8%      |
| 5.9.0-0.bpo.2-amd64  | 1         | 4%      |
| 5.4.0-0.bpo.3-amd64  | 1         | 4%      |
| 5.10.0-8-amd64       | 1         | 4%      |
| 5.10.0-14-amd64      | 1         | 4%      |
| 5.10.0-13-amd64      | 1         | 4%      |
| 5.10.0-0.bpo.8-amd64 | 1         | 4%      |
| 4.19.0-8-amd64       | 1         | 4%      |
| 4.19.0-5-amd64       | 1         | 4%      |
| 4.19.0-19-amd64      | 1         | 4%      |
| 4.19.0-16-amd64      | 1         | 4%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 11        | 45.83%  |
| 4.19.0  | 11        | 45.83%  |
| 5.9.0   | 1         | 4.17%   |
| 5.4.0   | 1         | 4.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 11        | 45.83%  |
| 4.19    | 11        | 45.83%  |
| 5.9     | 1         | 4.17%   |
| 5.4     | 1         | 4.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 23        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| XFCE    | 17        | 73.91%  |
| GNOME   | 3         | 13.04%  |
| Unknown | 2         | 8.7%    |
| KDE5    | 1         | 4.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 23        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 14        | 60.87%  |
| TDM     | 6         | 26.09%  |
| LightDM | 2         | 8.7%    |
| GDM     | 1         | 4.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| tr_TR   | 17        | 73.91%  |
| Unknown | 3         | 13.04%  |
| pt_BR   | 1         | 4.35%   |
| en_US   | 1         | 4.35%   |
| en_GB   | 1         | 4.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 17        | 70.83%  |
| EFI  | 7         | 29.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ext4 | 23        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 15        | 65.22%  |
| GPT     | 6         | 26.09%  |
| MBR     | 2         | 8.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 22        | 95.65%  |
| Yes       | 1         | 4.35%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 18        | 78.26%  |
| Yes       | 5         | 21.74%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 6         | 26.09%  |
| Hewlett-Packard     | 4         | 17.39%  |
| Toshiba             | 2         | 8.7%    |
| Sony                | 2         | 8.7%    |
| Packard Bell        | 2         | 8.7%    |
| Dell                | 2         | 8.7%    |
| ASUSTek Computer    | 2         | 8.7%    |
| Samsung Electronics | 1         | 4.35%   |
| Philco              | 1         | 4.35%   |
| Acer                | 1         | 4.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Toshiba Satellite C855-1VM                 | 1         | 4.35%   |
| Toshiba PORTEGE M780                       | 1         | 4.35%   |
| Sony SVF1521QSTB                           | 1         | 4.35%   |
| Sony SVE14A2V2ES                           | 1         | 4.35%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 4.35%   |
| Philco 14F                                 | 1         | 4.35%   |
| Packard Bell EasyNote_GN45                 | 1         | 4.35%   |
| Packard Bell EasyNote ENTG81BA             | 1         | 4.35%   |
| Lenovo V145-15AST 81MT                     | 1         | 4.35%   |
| Lenovo V110-15ISK 80TL                     | 1         | 4.35%   |
| Lenovo ThinkPad T450 20BUS39Y00            | 1         | 4.35%   |
| Lenovo ThinkPad E15 Gen 2 20TD0047TX       | 1         | 4.35%   |
| Lenovo IdeaPad-510-15IKB 80SV              | 1         | 4.35%   |
| Lenovo IdeaPad 320-15IKB 81BT              | 1         | 4.35%   |
| HP Pavilion 15                             | 1         | 4.35%   |
| HP Laptop 15-dw3xxx                        | 1         | 4.35%   |
| HP 250 G3                                  | 1         | 4.35%   |
| HP 15                                      | 1         | 4.35%   |
| Dell Latitude E6540                        | 1         | 4.35%   |
| Dell G5 5587                               | 1         | 4.35%   |
| ASUS X555YI                                | 1         | 4.35%   |
| ASUS E402BP                                | 1         | 4.35%   |
| Acer Aspire 5742G                          | 1         | 4.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Packard Bell EasyNote    | 2         | 8.7%    |
| Lenovo ThinkPad          | 2         | 8.7%    |
| Toshiba Satellite        | 1         | 4.35%   |
| Toshiba PORTEGE          | 1         | 4.35%   |
| Sony SVF1521QSTB         | 1         | 4.35%   |
| Sony SVE14A2V2ES         | 1         | 4.35%   |
| Samsung 300E4A           | 1         | 4.35%   |
| Philco 14F               | 1         | 4.35%   |
| Lenovo V145-15AST        | 1         | 4.35%   |
| Lenovo V110-15ISK        | 1         | 4.35%   |
| Lenovo IdeaPad-510-15IKB | 1         | 4.35%   |
| Lenovo IdeaPad           | 1         | 4.35%   |
| HP Pavilion              | 1         | 4.35%   |
| HP Laptop                | 1         | 4.35%   |
| HP 250                   | 1         | 4.35%   |
| HP 15                    | 1         | 4.35%   |
| Dell Latitude            | 1         | 4.35%   |
| Dell G5                  | 1         | 4.35%   |
| ASUS X555YI              | 1         | 4.35%   |
| ASUS E402BP              | 1         | 4.35%   |
| Acer Aspire              | 1         | 4.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 6         | 26.09%  |
| 2018 | 4         | 17.39%  |
| 2015 | 3         | 13.04%  |
| 2020 | 2         | 8.7%    |
| 2011 | 2         | 8.7%    |
| 2010 | 2         | 8.7%    |
| 2019 | 1         | 4.35%   |
| 2016 | 1         | 4.35%   |
| 2014 | 1         | 4.35%   |
| 2006 | 1         | 4.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 23        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 23        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 23        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 9         | 39.13%  |
| 4.01-8.0   | 7         | 30.43%  |
| 16.01-24.0 | 3         | 13.04%  |
| 1.01-2.0   | 2         | 8.7%    |
| 8.01-16.0  | 2         | 8.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 11        | 45.83%  |
| 2.01-3.0 | 6         | 25%     |
| 3.01-4.0 | 4         | 16.67%  |
| 4.01-8.0 | 2         | 8.33%   |
| 0.51-1.0 | 1         | 4.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 18        | 78.26%  |
| 2      | 4         | 17.39%  |
| 3      | 1         | 4.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 14        | 60.87%  |
| No        | 9         | 39.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 95.65%  |
| No        | 1         | 4.35%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 82.61%  |
| No        | 4         | 17.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Turkey  | 21        | 91.3%   |
| UK      | 1         | 4.35%   |
| Brazil  | 1         | 4.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City        | Notebooks | Percent |
|-------------|-----------|---------|
| Istanbul    | 7         | 28%     |
| Ankara      | 4         | 16%     |
| Izmir       | 3         | 12%     |
| Çanakkale  | 2         | 8%      |
| Sao Gabriel | 1         | 4%      |
| London      | 1         | 4%      |
| Konya       | 1         | 4%      |
| Gaziantep   | 1         | 4%      |
| Esenyurt    | 1         | 4%      |
| Bursa       | 1         | 4%      |
| Aydin       | 1         | 4%      |
| Artvin      | 1         | 4%      |
| Antalya     | 1         | 4%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 7      | 17.86%  |
| Seagate             | 5         | 5      | 17.86%  |
| Samsung Electronics | 4         | 4      | 14.29%  |
| SK Hynix            | 2         | 2      | 7.14%   |
| Kingston            | 2         | 3      | 7.14%   |
| HGST                | 2         | 2      | 7.14%   |
| SPCC                | 1         | 1      | 3.57%   |
| Silicon Motion      | 1         | 1      | 3.57%   |
| SanDisk             | 1         | 1      | 3.57%   |
| Micron Technology   | 1         | 2      | 3.57%   |
| Lexar               | 1         | 1      | 3.57%   |
| KingSpec            | 1         | 1      | 3.57%   |
| Hitachi             | 1         | 1      | 3.57%   |
| addlink             | 1         | 1      | 3.57%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| HGST HTS545050A7E680 500GB                  | 2         | 7.14%   |
| WDC WD5000LPVX-55V0TT0 500GB                | 1         | 3.57%   |
| WDC WD5000LPCX-21VHAT0 500GB                | 1         | 3.57%   |
| WDC WD3200BPVT-35JJ5T0 320GB                | 1         | 3.57%   |
| WDC WD10JPVX-60JC3T0 1TB                    | 1         | 3.57%   |
| WDC WD10JPCX-24UE4T0 1TB                    | 1         | 3.57%   |
| SPCC Solid State Disk 512GB                 | 1         | 3.57%   |
| SK Hynix SC311 SATA 256GB SSD               | 1         | 3.57%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB     | 1         | 3.57%   |
| Silicon Motion Longline SSD 512GB           | 1         | 3.57%   |
| Seagate ST9500325AS 500GB                   | 1         | 3.57%   |
| Seagate ST9120822AS 120GB                   | 1         | 3.57%   |
| Seagate ST1000LM035-1RK172 1TB              | 1         | 3.57%   |
| Seagate Expansion 4TB                       | 1         | 3.57%   |
| Seagate BarraCuda Q1 SSD ZA480CV10001 480GB | 1         | 3.57%   |
| SanDisk SDSSDA480G 480GB                    | 1         | 3.57%   |
| Samsung SSD 860 EVO 500GB                   | 1         | 3.57%   |
| Samsung MZALQ256HAJD-000L1 256GB            | 1         | 3.57%   |
| Samsung MZ7LN128HAHQ-000L2 128GB SSD        | 1         | 3.57%   |
| Samsung MZ7LF192HCGS-000L1 192GB SSD        | 1         | 3.57%   |
| Micron 1300_MTFDDAK512TDL 512GB SSD         | 1         | 3.57%   |
| Lexar 120GB SSD                             | 1         | 3.57%   |
| Kingston SHFS37A120G 120GB SSD              | 1         | 3.57%   |
| Kingston SA400S37240G 240GB SSD             | 1         | 3.57%   |
| KingSpec P3-128 128GB                       | 1         | 3.57%   |
| Hitachi HTS545025B9A300 250GB               | 1         | 3.57%   |
| addlink S10 120GB                           | 1         | 3.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 7      | 41.67%  |
| Seagate | 4         | 4      | 33.33%  |
| HGST    | 2         | 2      | 16.67%  |
| Hitachi | 1         | 1      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 25%     |
| Kingston            | 2         | 3      | 16.67%  |
| SPCC                | 1         | 1      | 8.33%   |
| SK Hynix            | 1         | 1      | 8.33%   |
| Seagate             | 1         | 1      | 8.33%   |
| SanDisk             | 1         | 1      | 8.33%   |
| Micron Technology   | 1         | 2      | 8.33%   |
| Lexar               | 1         | 1      | 8.33%   |
| KingSpec            | 1         | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 12        | 14     | 48%     |
| SSD     | 10        | 14     | 40%     |
| NVMe    | 2         | 3      | 8%      |
| Unknown | 1         | 1      | 4%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 21        | 28     | 87.5%   |
| NVMe | 2         | 3      | 8.33%   |
| SAS  | 1         | 1      | 4.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 17        | 19     | 73.91%  |
| 0.51-1.0   | 5         | 8      | 21.74%  |
| 3.01-4.0   | 1         | 1      | 4.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 10        | 41.67%  |
| 251-500    | 9         | 37.5%   |
| 21-50      | 2         | 8.33%   |
| 501-1000   | 2         | 8.33%   |
| 51-100     | 1         | 4.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 10        | 41.67%  |
| 21-50   | 7         | 29.17%  |
| 51-100  | 4         | 16.67%  |
| 101-250 | 2         | 8.33%   |
| 251-500 | 1         | 4.17%   |

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
| Detected | 15        | 22     | 65.22%  |
| Works    | 7         | 9      | 30.43%  |
| Malfunc  | 1         | 1      | 4.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 18        | 72%     |
| AMD                 | 4         | 16%     |
| SK Hynix            | 1         | 4%      |
| Silicon Motion      | 1         | 4%      |
| Samsung Electronics | 1         | 4%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 15.38%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 11.54%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 11.54%  |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 7.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 7.69%   |
| SK Hynix BC511                                                                   | 1         | 3.85%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 3.85%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 3.85%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 3.85%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 1         | 3.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 3.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 3.85%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 3.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 3.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 3.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 3.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 21        | 84%     |
| NVMe | 2         | 8%      |
| RAID | 1         | 4%      |
| IDE  | 1         | 4%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 19        | 82.61%  |
| AMD    | 4         | 17.39%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core i3 CPU M 370 @ 2.40GHz            | 2         | 8.7%    |
| Intel Pentium CPU B960 @ 2.20GHz             | 1         | 4.35%   |
| Intel Pentium CPU B950 @ 2.10GHz             | 1         | 4.35%   |
| Intel Core i7-8750H CPU @ 2.20GHz            | 1         | 4.35%   |
| Intel Core i7-5500U CPU @ 2.40GHz            | 1         | 4.35%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz           | 1         | 4.35%   |
| Intel Core i7-3630QM CPU @ 2.40GHz           | 1         | 4.35%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 1         | 4.35%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 1         | 4.35%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 1         | 4.35%   |
| Intel Core i5-3230M CPU @ 2.60GHz            | 1         | 4.35%   |
| Intel Core i3-6006U CPU @ 2.00GHz            | 1         | 4.35%   |
| Intel Core i3-4005U CPU @ 1.70GHz            | 1         | 4.35%   |
| Intel Core i3-3227U CPU @ 1.90GHz            | 1         | 4.35%   |
| Intel Core 2 CPU T5600 @ 1.83GHz             | 1         | 4.35%   |
| Intel Celeron CPU N3050 @ 1.60GHz            | 1         | 4.35%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz      | 1         | 4.35%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz      | 1         | 4.35%   |
| AMD C-50 Processor                           | 1         | 4.35%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 4.35%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 4.35%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics  | 1         | 4.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Intel Core i3 | 5         | 21.74%  |
| Other         | 4         | 17.39%  |
| Intel Core i7 | 4         | 17.39%  |
| Intel Core i5 | 4         | 17.39%  |
| Intel Pentium | 2         | 8.7%    |
| Intel Core 2  | 1         | 4.35%   |
| Intel Celeron | 1         | 4.35%   |
| AMD C-50      | 1         | 4.35%   |
| AMD A8        | 1         | 4.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 17        | 73.91%  |
| 4      | 5         | 21.74%  |
| 6      | 1         | 4.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 23        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 15        | 65.22%  |
| 1      | 8         | 34.78%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 23        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 65.22%  |
| 0x906ea    | 1         | 4.35%   |
| 0x806c1    | 1         | 4.35%   |
| 0x6f6      | 1         | 4.35%   |
| 0x406e3    | 1         | 4.35%   |
| 0x306a9    | 1         | 4.35%   |
| 0x07030105 | 1         | 4.35%   |
| 0x06006705 | 1         | 4.35%   |
| 0x05000029 | 1         | 4.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 3         | 13.04%  |
| IvyBridge   | 3         | 13.04%  |
| Westmere    | 2         | 8.7%    |
| TigerLake   | 2         | 8.7%    |
| SandyBridge | 2         | 8.7%    |
| Haswell     | 2         | 8.7%    |
| Excavator   | 2         | 8.7%    |
| Broadwell   | 2         | 8.7%    |
| Skylake     | 1         | 4.35%   |
| Silvermont  | 1         | 4.35%   |
| Puma        | 1         | 4.35%   |
| Core        | 1         | 4.35%   |
| Bobcat      | 1         | 4.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 18        | 60%     |
| AMD    | 7         | 23.33%  |
| Nvidia | 5         | 16.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 8.82%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 5.88%   |
| Intel HD Graphics 5500                                                                   | 2         | 5.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 5.88%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 5.88%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 5.88%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 2.94%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 2.94%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 2.94%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.94%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 2.94%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 2.94%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 2.94%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 2.94%   |
| Intel HD Graphics 620                                                                    | 1         | 2.94%   |
| Intel HD Graphics 520                                                                    | 1         | 2.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.94%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.94%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 2.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 2.94%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 2.94%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 2.94%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 2.94%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 2.94%   |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 1         | 2.94%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 1         | 2.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 11        | 47.83%  |
| Intel + Nvidia | 4         | 17.39%  |
| 2 x AMD        | 3         | 13.04%  |
| Intel + AMD    | 3         | 13.04%  |
| 1 x Nvidia     | 1         | 4.35%   |
| 1 x AMD        | 1         | 4.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver | Notebooks | Percent |
|--------|-----------|---------|
| Free   | 23        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 82.61%  |
| 0.01-0.5   | 3         | 13.04%  |
| 5.01-6.0   | 1         | 4.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 4         | 18.18%  |
| AU Optronics            | 4         | 18.18%  |
| Samsung Electronics     | 3         | 13.64%  |
| Chimei Innolux          | 3         | 13.64%  |
| BOE                     | 3         | 13.64%  |
| LG Philips              | 1         | 4.55%   |
| Lenovo                  | 1         | 4.55%   |
| Goldstar                | 1         | 4.55%   |
| Chi Mei Optoelectronics | 1         | 4.55%   |
| AOC                     | 1         | 4.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch     | 1         | 4.35%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 1         | 4.35%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 4.35%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 1         | 4.35%   |
| LG Philips LCD Monitor LPL1146 1280x800 331x207mm 15.4-inch              | 1         | 4.35%   |
| LG Display LCD Monitor LGD053F 1920x1080 340x190mm 15.3-inch             | 1         | 4.35%   |
| LG Display LCD Monitor LGD0470 1920x1080 345x194mm 15.6-inch             | 1         | 4.35%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 1         | 4.35%   |
| LG Display LCD Monitor LGD033F 1366x768 309x174mm 14.0-inch              | 1         | 4.35%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 1         | 4.35%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                   | 1         | 4.35%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 4.35%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch          | 1         | 4.35%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 1         | 4.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO15AB 1366x768 340x190mm 15.3-inch | 1         | 4.35%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 1         | 4.35%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 1         | 4.35%   |
| BOE LCD Monitor BOE065E 1920x1080 344x194mm 15.5-inch                    | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 4.35%   |
| AOC 2260WG5 AOC2260 1920x1080 477x268mm 21.5-inch                        | 1         | 4.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 12        | 54.55%  |
| 1920x1080 (FHD)  | 7         | 31.82%  |
| 1600x900 (HD+)   | 1         | 4.55%   |
| 1280x800 (WXGA)  | 1         | 4.55%   |
| 1280x1024 (SXGA) | 1         | 4.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 17        | 73.91%  |
| 14     | 2         | 8.7%    |
| 23     | 1         | 4.35%   |
| 22     | 1         | 4.35%   |
| 17     | 1         | 4.35%   |
| 13     | 1         | 4.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 20        | 90.91%  |
| 501-600     | 1         | 4.55%   |
| 401-500     | 1         | 4.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 20        | 86.96%  |
| 16/10 | 2         | 8.7%    |
| 5/4   | 1         | 4.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 17        | 73.91%  |
| 81-90          | 3         | 13.04%  |
| 201-250        | 2         | 8.7%    |
| 141-150        | 1         | 4.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 11        | 47.83%  |
| 121-160 | 7         | 30.43%  |
| 51-100  | 5         | 21.74%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 21        | 91.3%   |
| 2     | 2         | 8.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 17        | 44.74%  |
| Intel                 | 9         | 23.68%  |
| Qualcomm Atheros      | 3         | 7.89%   |
| Broadcom              | 3         | 7.89%   |
| Ralink                | 2         | 5.26%   |
| ASUSTek Computer      | 2         | 5.26%   |
| Xiaomi                | 1         | 2.63%   |
| JMicron Technology    | 1         | 2.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 24.49%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 8.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 4.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 4.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 4.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.04%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.04%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 2.04%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 2.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.04%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 2.04%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 2.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 2.04%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.04%   |
| Intel Wireless 7265                                               | 1         | 2.04%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 2.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 2.04%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.04%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 2.04%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 2.04%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 2.04%   |
| Intel Centrino Wireless-N 130                                     | 1         | 2.04%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 2.04%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 2.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 2.04%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 2.04%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.04%   |
| Broadcom BCM43225 802.11b/g/n                                     | 1         | 2.04%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 2.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 2.04%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                               | 1         | 2.04%   |
| ASUS 802.11ac NIC                                                 | 1         | 2.04%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 9         | 36%     |
| Realtek Semiconductor | 6         | 24%     |
| Qualcomm Atheros      | 3         | 12%     |
| Broadcom              | 3         | 12%     |
| Ralink                | 2         | 8%      |
| ASUSTek Computer      | 2         | 8%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 2         | 8%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 2         | 8%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 8%      |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 1         | 4%      |
| Realtek RTL8723AE PCIe Wireless Network Adapter            | 1         | 4%      |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                  | 1         | 4%      |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                  | 1         | 4%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 4%      |
| Intel Wireless 7265                                        | 1         | 4%      |
| Intel Wi-Fi 6 AX201                                        | 1         | 4%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection      | 1         | 4%      |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1         | 4%      |
| Intel Centrino Wireless-N 2230                             | 1         | 4%      |
| Intel Centrino Wireless-N 130                              | 1         | 4%      |
| Intel Centrino Ultimate-N 6300                             | 1         | 4%      |
| Intel Centrino Advanced-N 6200                             | 1         | 4%      |
| Intel Cannon Lake PCH CNVi WiFi                            | 1         | 4%      |
| Broadcom BCM43225 802.11b/g/n                              | 1         | 4%      |
| Broadcom BCM43142 802.11b/g/n                              | 1         | 4%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 1         | 4%      |
| ASUS Realtek 8188EUS [USB-N10 Nano]                        | 1         | 4%      |
| ASUS 802.11ac NIC                                          | 1         | 4%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 17        | 73.91%  |
| Intel                 | 3         | 13.04%  |
| Xiaomi                | 1         | 4.35%   |
| JMicron Technology    | 1         | 4.35%   |
| Broadcom              | 1         | 4.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 50%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 16.67%  |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 4.17%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 4.17%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 4.17%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 4.17%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 4.17%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 4.17%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 4.17%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 4.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 23        | 51.11%  |
| Ethernet | 22        | 48.89%  |

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
| 2     | 22        | 95.65%  |
| 1     | 1         | 4.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 23        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 6         | 31.58%  |
| Realtek Semiconductor           | 5         | 26.32%  |
| Toshiba                         | 2         | 10.53%  |
| Ralink                          | 1         | 5.26%   |
| Qualcomm Atheros Communications | 1         | 5.26%   |
| Lite-On Technology              | 1         | 5.26%   |
| IMC Networks                    | 1         | 5.26%   |
| Foxconn / Hon Hai               | 1         | 5.26%   |
| Broadcom                        | 1         | 5.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                          | 5         | 26.32%  |
| Intel Bluetooth wireless interface               | 2         | 10.53%  |
| Toshiba RT Bluetooth Radio                       | 1         | 5.26%   |
| Toshiba Integrated Bluetooth HCI                 | 1         | 5.26%   |
| Ralink RT3290 Bluetooth                          | 1         | 5.26%   |
| Qualcomm Atheros  Bluetooth Device               | 1         | 5.26%   |
| Lite-On Atheros AR3012 Bluetooth                 | 1         | 5.26%   |
| Intel Centrino Bluetooth Wireless Transceiver    | 1         | 5.26%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 5.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 1         | 5.26%   |
| Intel AX201 Bluetooth                            | 1         | 5.26%   |
| IMC Networks Bluetooth Device                    | 1         | 5.26%   |
| Foxconn / Hon Hai BCM43142A0                     | 1         | 5.26%   |
| Broadcom HP Portable Valentine                   | 1         | 5.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 19        | 76%     |
| AMD                   | 4         | 16%     |
| Nvidia                | 1         | 4%      |
| Barco Display Systems | 1         | 4%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 12.12%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 9.09%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 6.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 6.06%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 6.06%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 6.06%   |
| AMD High Definition Audio Controller                                                              | 2         | 6.06%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 6.06%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 3.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 3.03%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 3.03%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 3.03%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 3.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 3.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 3.03%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 3.03%   |
| Barco Display Systems USBGH520-ENC                                                                | 1         | 3.03%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 3.03%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 3.03%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 3.03%   |
| AMD FCH Azalia Controller                                                                         | 1         | 3.03%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 44.44%  |
| Unknown (0x4509)    | 1         | 11.11%  |
| Unknown             | 1         | 11.11%  |
| SK Hynix            | 1         | 11.11%  |
| Micron Technology   | 1         | 11.11%  |
| Kingmax             | 1         | 11.11%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2                              | 1         | 11.11%  |
| Unknown (0x4509) RAM GKE800SO102408-2666A 8GB SODIMM DDR4 2133MT/s | 1         | 11.11%  |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s          | 1         | 11.11%  |
| Samsung RAM M471B5773CHS-CH9 2GB DIMM DDR3 1333MT/s                | 1         | 11.11%  |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s              | 1         | 11.11%  |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s              | 1         | 11.11%  |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s              | 1         | 11.11%  |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 1         | 11.11%  |
| Kingmax RAM FSFE85F-C8KL9 2GB DIMM DDR3 1333MT/s                   | 1         | 11.11%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR4  | 5         | 55.56%  |
| DDR3  | 2         | 22.22%  |
| SDRAM | 1         | 11.11%  |
| DDR2  | 1         | 11.11%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 7         | 87.5%   |
| DIMM   | 1         | 12.5%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 8192 | 3         | 37.5%   |
| 4096 | 3         | 37.5%   |
| 2048 | 2         | 25%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 2         | 25%     |
| 2667    | 2         | 25%     |
| 2133    | 1         | 12.5%   |
| 1600    | 1         | 12.5%   |
| 1333    | 1         | 12.5%   |
| Unknown | 1         | 12.5%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Notebooks | Percent |
|---------------------------|-----------|---------|
| Canon LBP6030/6030B/6018L | 1         | 100%    |

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
| Chicony Electronics         | 7         | 35%     |
| Microdia                    | 2         | 10%     |
| Luxvisions Innotech Limited | 2         | 10%     |
| IMC Networks                | 2         | 10%     |
| Suyin                       | 1         | 5%      |
| Silicon Motion              | 1         | 5%      |
| Realtek Semiconductor       | 1         | 5%      |
| Lite-On Technology          | 1         | 5%      |
| Foxconn / Hon Hai           | 1         | 5%      |
| ALi                         | 1         | 5%      |
| Acer                        | 1         | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony EasyCamera                                  | 2         | 10%     |
| Suyin HP Webcam                                     | 1         | 5%      |
| Silicon Motion WebCam SC-0311139N                   | 1         | 5%      |
| Realtek HP Truevision HD integrated webcam          | 1         | 5%      |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 5%      |
| Microdia Integrated_Webcam_HD                       | 1         | 5%      |
| Luxvisions Innotech Limited Integrated Camera       | 1         | 5%      |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 5%      |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 5%      |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 5%      |
| IMC Networks EasyCamera                             | 1         | 5%      |
| Foxconn / Hon Hai USB2.0 Camera                     | 1         | 5%      |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 5%      |
| Chicony Integrated Camera                           | 1         | 5%      |
| Chicony HP Truevision HD                            | 1         | 5%      |
| Chicony Front Camera                                | 1         | 5%      |
| Chicony CNA7157                                     | 1         | 5%      |
| ALi Gateway Webcam                                  | 1         | 5%      |
| Acer EasyCamera                                     | 1         | 5%      |

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
| 0     | 17        | 70.83%  |
| 1     | 5         | 20.83%  |
| 2     | 2         | 8.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Graphics card      | 3         | 33.33%  |
| Fingerprint reader | 2         | 22.22%  |
| Net/wireless       | 1         | 11.11%  |
| Chipcard           | 1         | 11.11%  |
| Camera             | 1         | 11.11%  |
| Bluetooth          | 1         | 11.11%  |

