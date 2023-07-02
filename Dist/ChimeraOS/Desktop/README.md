ChimeraOS - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for ChimeraOS.

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

Total: 39

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| HP        | 1998                        | [91f6e54877](https://linux-hardware.org/?probe=91f6e54877) | Jun 30, 2023 |
| Gigabyte  | G1.Sniper A88X-CF           | [d4470db5d3](https://linux-hardware.org/?probe=d4470db5d3) | Jun 20, 2023 |
| Dell      | 02YYK5 A01                  | [50efda9604](https://linux-hardware.org/?probe=50efda9604) | Jun 19, 2023 |
| Gigabyte  | B450 AORUS M                | [299db094f8](https://linux-hardware.org/?probe=299db094f8) | Jun 18, 2023 |
| Dell      | 07HXY6 A01                  | [ec3adcbe42](https://linux-hardware.org/?probe=ec3adcbe42) | Jun 16, 2023 |
| Gigabyte  | X470 AORUS GAMING 5 WIFI... | [c6401638dd](https://linux-hardware.org/?probe=c6401638dd) | Jun 11, 2023 |
| Gigabyte  | B550I AORUS PRO AX          | [798d8e8914](https://linux-hardware.org/?probe=798d8e8914) | Jun 11, 2023 |
| MSI       | MPG B650I EDGE WIFI         | [d43ce99616](https://linux-hardware.org/?probe=d43ce99616) | Jun 07, 2023 |
| Gigabyte  | X470 AORUS GAMING 5 WIFI... | [8c6370ac0d](https://linux-hardware.org/?probe=8c6370ac0d) | May 23, 2023 |
| Gigabyte  | X470 AORUS GAMING 5 WIFI... | [41b69ae4db](https://linux-hardware.org/?probe=41b69ae4db) | May 12, 2023 |
| ASUSTek   | PRIME B760-PLUS D4          | [bb01d9e92b](https://linux-hardware.org/?probe=bb01d9e92b) | May 12, 2023 |
| ASUSTek   | ROG STRIX B460-I GAMING     | [3a9528f661](https://linux-hardware.org/?probe=3a9528f661) | May 10, 2023 |
| Gigabyte  | X470 AORUS GAMING 5 WIFI... | [bf3fee03d2](https://linux-hardware.org/?probe=bf3fee03d2) | May 09, 2023 |
| ASUSTek   | ROG STRIX B550-F GAMING     | [ad66608cf0](https://linux-hardware.org/?probe=ad66608cf0) | May 08, 2023 |
| Gigabyte  | X470 AORUS GAMING 5 WIFI... | [101ec0a833](https://linux-hardware.org/?probe=101ec0a833) | May 05, 2023 |
| ASUSTek   | PRIME B760-PLUS D4          | [4ec161ab9b](https://linux-hardware.org/?probe=4ec161ab9b) | May 04, 2023 |
| Dell      | 0FDY5C A00                  | [a6865b8591](https://linux-hardware.org/?probe=a6865b8591) | Apr 16, 2023 |
| ASUSTek   | ROG STRIX B460-I GAMING     | [14db4e6f1d](https://linux-hardware.org/?probe=14db4e6f1d) | Apr 11, 2023 |
| ASUSTek   | ROG STRIX B650E-I GAMING... | [03db223af4](https://linux-hardware.org/?probe=03db223af4) | Apr 06, 2023 |
| ASUSTek   | ROG STRIX B650E-I GAMING... | [f8c2ffcd09](https://linux-hardware.org/?probe=f8c2ffcd09) | Apr 06, 2023 |
| MACHINIST | X99-RS9 V2.0                | [ad4c43dd09](https://linux-hardware.org/?probe=ad4c43dd09) | Mar 21, 2023 |
| Gigabyte  | B460M DS3H AC V2-Y1         | [b21cd49226](https://linux-hardware.org/?probe=b21cd49226) | Mar 16, 2023 |
| MSI       | MPG B650I EDGE WIFI         | [9f40b861a5](https://linux-hardware.org/?probe=9f40b861a5) | Mar 12, 2023 |
| Gigabyte  | B460M DS3H AC V2-Y1         | [7f8fc2ba96](https://linux-hardware.org/?probe=7f8fc2ba96) | Mar 10, 2023 |
| Dell      | 0XHGV1 A00                  | [8fa504e81f](https://linux-hardware.org/?probe=8fa504e81f) | Mar 07, 2023 |
| Intel     | DB75EN AAG39650-400         | [4a0feca3f5](https://linux-hardware.org/?probe=4a0feca3f5) | Mar 02, 2023 |
| Gigabyte  | H77M-D3H                    | [01eb743492](https://linux-hardware.org/?probe=01eb743492) | Feb 25, 2023 |
| Gigabyte  | H77M-D3H                    | [766790f373](https://linux-hardware.org/?probe=766790f373) | Feb 25, 2023 |
| ASUSTek   | B150I PRO GAMING/WIFI/AU... | [eb1e211b0f](https://linux-hardware.org/?probe=eb1e211b0f) | Feb 25, 2023 |
| HP        | 1998                        | [dbb952f3f6](https://linux-hardware.org/?probe=dbb952f3f6) | Feb 13, 2023 |
| HP        | 1998                        | [0171575a1d](https://linux-hardware.org/?probe=0171575a1d) | Feb 13, 2023 |
| Gigabyte  | H510M H                     | [69d2cb7e14](https://linux-hardware.org/?probe=69d2cb7e14) | Jan 11, 2023 |
| ASUSTek   | P8H61-MX R2.0               | [3e4b14919e](https://linux-hardware.org/?probe=3e4b14919e) | Jan 05, 2023 |
| Gigabyte  | X570S AORUS ELITE AX        | [02b3cbc8c6](https://linux-hardware.org/?probe=02b3cbc8c6) | Jan 04, 2023 |
| Gigabyte  | X570S AORUS ELITE AX        | [13ae6c7e25](https://linux-hardware.org/?probe=13ae6c7e25) | Jan 01, 2023 |
| Gigabyte  | X570 AORUS ELITE WIFI       | [49ca01435b](https://linux-hardware.org/?probe=49ca01435b) | Dec 27, 2022 |
| Lenovo    | ThinkCentre M70e 0832B1U    | [d95663a632](https://linux-hardware.org/?probe=d95663a632) | Dec 07, 2022 |
| Gigabyte  | X470 AORUS GAMING 5 WIFI... | [2a7b6d570f](https://linux-hardware.org/?probe=2a7b6d570f) | Nov 26, 2022 |
| Gigabyte  | X470 AORUS GAMING 5 WIFI... | [58b3db6784](https://linux-hardware.org/?probe=58b3db6784) | Nov 23, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| ChimeraOS 42 | 7        | 26.92%  |
| ChimeraOS 39 | 7        | 26.92%  |
| ChimeraOS 41 | 4        | 15.38%  |
| ChimeraOS 38 | 4        | 15.38%  |
| ChimeraOS 37 | 3        | 11.54%  |
| ChimeraOS 43 | 1        | 3.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| ChimeraOS | 24       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version        | Desktops | Percent |
|----------------|----------|---------|
| 6.1.27-1-lts   | 7        | 25.93%  |
| 6.1.11-arch1-1 | 7        | 25.93%  |
| 6.1.21-1-lts   | 4        | 14.81%  |
| 6.1.1-arch1-1  | 4        | 14.81%  |
| 6.0.8-arch1-1  | 3        | 11.11%  |
| 6.3.3-arch1-1  | 1        | 3.7%    |
| 6.3.1-arch2-1  | 1        | 3.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1.27  | 7        | 25.93%  |
| 6.1.11  | 7        | 25.93%  |
| 6.1.21  | 4        | 14.81%  |
| 6.1.1   | 4        | 14.81%  |
| 6.0.8   | 3        | 11.11%  |
| 6.3.3   | 1        | 3.7%    |
| 6.3.1   | 1        | 3.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1     | 21       | 84%     |
| 6.0     | 3        | 12%     |
| 6.3     | 1        | 4%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 24       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GNOME   | 23       | 95.83%  |
| steamos | 1        | 4.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 20       | 83.33%  |
| X11     | 4        | 16.67%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 24       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 22       | 91.67%  |
| es_ES | 1        | 4.17%   |
| de_DE | 1        | 4.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 24       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 24       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 24       | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 9        | 37.5%   |
| ASUSTek Computer    | 6        | 25%     |
| Dell                | 3        | 12.5%   |
| Hewlett-Packard     | 2        | 8.33%   |
| MSI                 | 1        | 4.17%   |
| MACHINIST           | 1        | 4.17%   |
| Lenovo              | 1        | 4.17%   |
| Intel               | 1        | 4.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| HP EliteDesk 800 G1 SFF            | 2        | 8.33%   |
| MSI MS-7D73                        | 1        | 4.17%   |
| MACHINIST X99-RS9 V2.0             | 1        | 4.17%   |
| Lenovo ThinkCentre M70e 0832B1U    | 1        | 4.17%   |
| Intel DB75EN AAG39650-400          | 1        | 4.17%   |
| Gigabyte X570S AORUS ELITE AX      | 1        | 4.17%   |
| Gigabyte X570 AORUS ELITE WIFI     | 1        | 4.17%   |
| Gigabyte X470 AORUS GAMING 5 WIFI  | 1        | 4.17%   |
| Gigabyte H77M-D3H                  | 1        | 4.17%   |
| Gigabyte H510M H                   | 1        | 4.17%   |
| Gigabyte G1.Sniper A88X-CF         | 1        | 4.17%   |
| Gigabyte B550I AORUS PRO AX        | 1        | 4.17%   |
| Gigabyte B460M DS3H AC V2-Y1       | 1        | 4.17%   |
| Gigabyte B450 AORUS M              | 1        | 4.17%   |
| Dell OptiPlex 7050                 | 1        | 4.17%   |
| Dell OptiPlex 7020                 | 1        | 4.17%   |
| Dell OptiPlex 5055 Ryzen APU       | 1        | 4.17%   |
| ASUS ROG STRIX B650E-I GAMING WIFI | 1        | 4.17%   |
| ASUS ROG STRIX B550-F GAMING       | 1        | 4.17%   |
| ASUS ROG STRIX B460-I GAMING       | 1        | 4.17%   |
| ASUS PRIME B760-PLUS D4            | 1        | 4.17%   |
| ASUS P8H61-MX R2.0                 | 1        | 4.17%   |
| ASUS B150I PRO GAMING/WIFI/AURA    | 1        | 4.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Dell OptiPlex      | 3        | 12.5%   |
| ASUS ROG           | 3        | 12.5%   |
| HP EliteDesk       | 2        | 8.33%   |
| MSI MS-7D73        | 1        | 4.17%   |
| MACHINIST X99-RS9  | 1        | 4.17%   |
| Lenovo ThinkCentre | 1        | 4.17%   |
| Intel DB75EN       | 1        | 4.17%   |
| Gigabyte X570S     | 1        | 4.17%   |
| Gigabyte X570      | 1        | 4.17%   |
| Gigabyte X470      | 1        | 4.17%   |
| Gigabyte H77M-D3H  | 1        | 4.17%   |
| Gigabyte H510M     | 1        | 4.17%   |
| Gigabyte G1.Sniper | 1        | 4.17%   |
| Gigabyte B550I     | 1        | 4.17%   |
| Gigabyte B460M     | 1        | 4.17%   |
| Gigabyte B450      | 1        | 4.17%   |
| ASUS PRIME         | 1        | 4.17%   |
| ASUS P8H61-MX      | 1        | 4.17%   |
| ASUS B150I         | 1        | 4.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 4        | 16.67%  |
| 2022 | 3        | 12.5%   |
| 2021 | 3        | 12.5%   |
| 2013 | 3        | 12.5%   |
| 2012 | 3        | 12.5%   |
| 2019 | 2        | 8.33%   |
| 2018 | 2        | 8.33%   |
| 2017 | 1        | 4.17%   |
| 2016 | 1        | 4.17%   |
| 2015 | 1        | 4.17%   |
| 2010 | 1        | 4.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 24       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 24       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 24       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 11       | 45.83%  |
| 16.01-24.0  | 5        | 20.83%  |
| 4.01-8.0    | 3        | 12.5%   |
| 24.01-32.0  | 2        | 8.33%   |
| 8.01-16.0   | 2        | 8.33%   |
| 64.01-256.0 | 1        | 4.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 11       | 42.31%  |
| 1.01-2.0   | 6        | 23.08%  |
| 3.01-4.0   | 5        | 19.23%  |
| 4.01-8.0   | 3        | 11.54%  |
| 16.01-24.0 | 1        | 3.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 9        | 34.62%  |
| 2      | 7        | 26.92%  |
| 3      | 6        | 23.08%  |
| 4      | 2        | 7.69%   |
| 8      | 1        | 3.85%   |
| 7      | 1        | 3.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 83.33%  |
| Yes       | 4        | 16.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 24       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 16       | 66.67%  |
| No        | 8        | 33.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 15       | 62.5%   |
| No        | 9        | 37.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 13       | 54.17%  |
| Germany   | 2        | 8.33%   |
| Canada    | 2        | 8.33%   |
| Australia | 2        | 8.33%   |
| UK        | 1        | 4.17%   |
| Spain     | 1        | 4.17%   |
| Russia    | 1        | 4.17%   |
| Norway    | 1        | 4.17%   |
| Brazil    | 1        | 4.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Desktops | Percent |
|--------------|----------|---------|
| Yaroslavl    | 1        | 4%      |
| Watsonville  | 1        | 4%      |
| Toronto      | 1        | 4%      |
| Sumaré      | 1        | 4%      |
| Steyning     | 1        | 4%      |
| Shelbyville  | 1        | 4%      |
| Sanford      | 1        | 4%      |
| Round Rock   | 1        | 4%      |
| Racine       | 1        | 4%      |
| Phoenix      | 1        | 4%      |
| Philadelphia | 1        | 4%      |
| Melbourne    | 1        | 4%      |
| Longueuil    | 1        | 4%      |
| Lewiston     | 1        | 4%      |
| Houston      | 1        | 4%      |
| Hixson       | 1        | 4%      |
| Hamburg      | 1        | 4%      |
| Gary         | 1        | 4%      |
| Eidsberg     | 1        | 4%      |
| Chattanooga  | 1        | 4%      |
| Brossard     | 1        | 4%      |
| Bielefeld    | 1        | 4%      |
| Beaverton    | 1        | 4%      |
| Badalona     | 1        | 4%      |
| Adelaide     | 1        | 4%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 8        | 16     | 16.33%  |
| Seagate                   | 7        | 9      | 14.29%  |
| WDC                       | 6        | 9      | 12.24%  |
| SanDisk                   | 4        | 8      | 8.16%   |
| Kingston                  | 4        | 4      | 8.16%   |
| Micron/Crucial Technology | 3        | 3      | 6.12%   |
| Phison Electronics        | 2        | 2      | 4.08%   |
| Crucial                   | 2        | 4      | 4.08%   |
| Toshiba                   | 1        | 2      | 2.04%   |
| SK hynix                  | 1        | 1      | 2.04%   |
| Silicon Motion            | 1        | 1      | 2.04%   |
| Netac                     | 1        | 1      | 2.04%   |
| Micron Technology         | 1        | 3      | 2.04%   |
| KingFast                  | 1        | 1      | 2.04%   |
| KingDian                  | 1        | 3      | 2.04%   |
| Intel                     | 1        | 2      | 2.04%   |
| Hitachi                   | 1        | 1      | 2.04%   |
| Hewlett-Packard           | 1        | 1      | 2.04%   |
| Fanxiang                  | 1        | 1      | 2.04%   |
| Corsair                   | 1        | 1      | 2.04%   |
| ADATA Technology          | 1        | 2      | 2.04%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Micron/Crucial P2 NVMe PCIe SSD 4TB                   | 3        | 5.36%   |
| Samsung SSD 870 QVO 2TB                               | 2        | 3.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB   | 2        | 3.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB    | 2        | 3.57%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 1        | 1.79%   |
| WDC WDBNCE5000PNC 500GB SSD                           | 1        | 1.79%   |
| WDC WD5000BEVT-22A0RT0 500GB                          | 1        | 1.79%   |
| WDC WD5000AVDS-63U7B1 500GB                           | 1        | 1.79%   |
| WDC WD40EZRX-00SPEB0 4TB                              | 1        | 1.79%   |
| WDC WD20EARX-00PASB0 2TB                              | 1        | 1.79%   |
| WDC WD1500HLFS-01G6U0 150GB                           | 1        | 1.79%   |
| Toshiba MQ02ABD100H 1TB                               | 1        | 1.79%   |
| SK hynix PC601 NVMe 256GB                             | 1        | 1.79%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 1        | 1.79%   |
| Seagate ST9500325AS 500GB                             | 1        | 1.79%   |
| Seagate ST500LM000-1EJ162-SSHD 500GB                  | 1        | 1.79%   |
| Seagate ST4000LM024-2AN17V 4TB                        | 1        | 1.79%   |
| Seagate ST2000DM008-2FR102 2TB                        | 1        | 1.79%   |
| Seagate ST2000DM006-2DM164 2TB                        | 1        | 1.79%   |
| Seagate ST2000DL003-9VT166 2TB                        | 1        | 1.79%   |
| Seagate ST1000DM010-2EP102 1TB                        | 1        | 1.79%   |
| Seagate Expansion Desk 5TB                            | 1        | 1.79%   |
| Sandisk WD_BLACK SN750 SE NVMe 1TB                    | 1        | 1.79%   |
| SanDisk SDSSDP128G 128GB                              | 1        | 1.79%   |
| SanDisk SDSSDA480G 480GB                              | 1        | 1.79%   |
| SanDisk SD7TB3Q-256G-1006 256GB SSD                   | 1        | 1.79%   |
| SanDisk Extreme SSD 500GB                             | 1        | 1.79%   |
| Samsung SSD 860 EVO 1TB                               | 1        | 1.79%   |
| Samsung SSD 850 EVO 250GB                             | 1        | 1.79%   |
| Samsung SSD 840 PRO Series 512GB                      | 1        | 1.79%   |
| Samsung SSD 840 EVO 250GB                             | 1        | 1.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 1        | 1.79%   |
| Samsung HD502IJ 500GB                                 | 1        | 1.79%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 1        | 1.79%   |
| Phison E12 NVMe Controller 1TB                        | 1        | 1.79%   |
| Netac SSD 1TB                                         | 1        | 1.79%   |
| Micron MTFDDAK256MBF-1AN15ABHA 256GB SSD              | 1        | 1.79%   |
| Kingston SNVS500G 500GB                               | 1        | 1.79%   |
| Kingston SNVS1000GB 1TB                               | 1        | 1.79%   |
| Kingston SA400S37960G 960GB SSD                       | 1        | 1.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 9      | 46.67%  |
| WDC                 | 5        | 7      | 33.33%  |
| Toshiba             | 1        | 2      | 6.67%   |
| Samsung Electronics | 1        | 1      | 6.67%   |
| Hitachi             | 1        | 1      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 9      | 25%     |
| SanDisk             | 4        | 6      | 20%     |
| Kingston            | 2        | 2      | 10%     |
| Crucial             | 2        | 4      | 10%     |
| WDC                 | 1        | 2      | 5%      |
| Netac               | 1        | 1      | 5%      |
| Micron Technology   | 1        | 3      | 5%      |
| KingDian            | 1        | 3      | 5%      |
| Hewlett-Packard     | 1        | 1      | 5%      |
| Fanxiang            | 1        | 1      | 5%      |
| Corsair             | 1        | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 14       | 33     | 35.9%   |
| NVMe    | 13       | 21     | 33.33%  |
| HDD     | 11       | 20     | 28.21%  |
| Unknown | 1        | 1      | 2.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 20       | 52     | 57.14%  |
| NVMe | 13       | 21     | 37.14%  |
| SAS  | 2        | 2      | 5.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 13       | 32     | 46.43%  |
| 0.51-1.0   | 6        | 7      | 21.43%  |
| 1.01-2.0   | 5        | 7      | 17.86%  |
| 3.01-4.0   | 2        | 5      | 7.14%   |
| 2.01-3.0   | 1        | 1      | 3.57%   |
| 4.01-10.0  | 1        | 1      | 3.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 10       | 40%     |
| 1001-2000      | 8        | 32%     |
| 501-1000       | 4        | 16%     |
| 251-500        | 2        | 8%      |
| 2001-3000      | 1        | 4%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 7        | 26.92%  |
| 101-250        | 4        | 15.38%  |
| 51-100         | 4        | 15.38%  |
| More than 3000 | 3        | 11.54%  |
| 251-500        | 3        | 11.54%  |
| 2001-3000      | 2        | 7.69%   |
| 501-1000       | 2        | 7.69%   |
| 1001-2000      | 1        | 3.85%   |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 24       | 75     | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 15       | 36.59%  |
| AMD                         | 10       | 24.39%  |
| Samsung Electronics         | 4        | 9.76%   |
| Micron/Crucial Technology   | 3        | 7.32%   |
| Phison Electronics          | 2        | 4.88%   |
| Kingston Technology Company | 2        | 4.88%   |
| SK hynix                    | 1        | 2.44%   |
| Silicon Motion              | 1        | 2.44%   |
| SanDisk                     | 1        | 2.44%   |
| Biwin Storage Technology    | 1        | 2.44%   |
| ADATA Technology            | 1        | 2.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 8        | 17.02%  |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 3        | 6.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3        | 6.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2        | 4.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 4.26%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 4.26%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2        | 4.26%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 4.26%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 4.26%   |
| SK hynix Non-Volatile memory controller                                        | 1        | 2.13%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 2.13%   |
| SanDisk Non-Volatile memory controller                                         | 1        | 2.13%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 2.13%   |
| Phison PS5013 E13 NVMe Controller                                              | 1        | 2.13%   |
| Phison E12 NVMe Controller                                                     | 1        | 2.13%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                             | 1        | 2.13%   |
| Kingston Company NVMe Controller                                               | 1        | 2.13%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 1        | 2.13%   |
| Intel SSD 665p Series                                                          | 1        | 2.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 2.13%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 2.13%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1        | 2.13%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]  | 1        | 2.13%   |
| Intel 700 Series Chipset Family SATA AHCI Controller                           | 1        | 2.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 2.13%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 2.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1        | 2.13%   |
| Biwin Storage Non-Volatile memory controller                                   | 1        | 2.13%   |
| AMD 300 Series Chipset SATA Controller                                         | 1        | 2.13%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1        | 2.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 22       | 57.89%  |
| NVMe | 13       | 34.21%  |
| IDE  | 2        | 5.26%   |
| RAID | 1        | 2.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 14       | 58.33%  |
| AMD    | 10       | 41.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz             | 1        | 4%      |
| Intel Core i7-7700K CPU @ 4.20GHz               | 1        | 4%      |
| Intel Core i7-4770 CPU @ 3.40GHz                | 1        | 4%      |
| Intel Core i5-7500 CPU @ 3.40GHz                | 1        | 4%      |
| Intel Core i5-4570 CPU @ 3.20GHz                | 1        | 4%      |
| Intel Core i5-3570 CPU @ 3.40GHz                | 1        | 4%      |
| Intel Core i5-2500K CPU @ 3.30GHz               | 1        | 4%      |
| Intel Core i5-2500 CPU @ 3.30GHz                | 1        | 4%      |
| Intel Core i5-10400F CPU @ 2.90GHz              | 1        | 4%      |
| Intel Core i3-4160 CPU @ 3.60GHz                | 1        | 4%      |
| Intel Core i3-10100F CPU @ 3.60GHz              | 1        | 4%      |
| Intel Core i3-10100 CPU @ 3.60GHz               | 1        | 4%      |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz           | 1        | 4%      |
| Intel 13th Gen Core i9-13900K                   | 1        | 4%      |
| AMD Ryzen 9 7950X3D 16-Core Processor           | 1        | 4%      |
| AMD Ryzen 9 5950X 16-Core Processor             | 1        | 4%      |
| AMD Ryzen 9 5900X 12-Core Processor             | 1        | 4%      |
| AMD Ryzen 7 7700X 8-Core Processor              | 1        | 4%      |
| AMD Ryzen 7 5800X 8-Core Processor              | 1        | 4%      |
| AMD Ryzen 7 1700X Eight-Core Processor          | 1        | 4%      |
| AMD Ryzen 5 PRO 2400G with Radeon Vega Graphics | 1        | 4%      |
| AMD Ryzen 5 7600X 6-Core Processor              | 1        | 4%      |
| AMD Ryzen 5 5600G with Radeon Graphics          | 1        | 4%      |
| AMD Ryzen 5 5500                                | 1        | 4%      |
| AMD A10-6800K APU with Radeon HD Graphics       | 1        | 4%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 6        | 24%     |
| Intel Core i3     | 3        | 12%     |
| AMD Ryzen 9       | 3        | 12%     |
| AMD Ryzen 7       | 3        | 12%     |
| AMD Ryzen 5       | 3        | 12%     |
| Intel Core i7     | 2        | 8%      |
| Other             | 1        | 4%      |
| Intel Xeon        | 1        | 4%      |
| Intel Core 2 Quad | 1        | 4%      |
| AMD Ryzen 5 PRO   | 1        | 4%      |
| AMD A10           | 1        | 4%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 11       | 44%     |
| 6      | 5        | 20%     |
| 8      | 3        | 12%     |
| 16     | 2        | 8%      |
| 2      | 2        | 8%      |
| 24     | 1        | 4%      |
| 12     | 1        | 4%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 24       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 18       | 75%     |
| 1      | 6        | 25%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 24       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 24       | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 3       | 5        | 20.83%  |
| Haswell     | 4        | 16.67%  |
| CometLake   | 3        | 12.5%   |
| Unknown     | 3        | 12.5%   |
| Zen         | 2        | 8.33%   |
| SandyBridge | 2        | 8.33%   |
| KabyLake    | 2        | 8.33%   |
| Piledriver  | 1        | 4.17%   |
| Penryn      | 1        | 4.17%   |
| IvyBridge   | 1        | 4.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 14       | 50%     |
| Nvidia | 8        | 28.57%  |
| Intel  | 6        | 21.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 6.9%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 6.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 6.9%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 3.45%   |
| Nvidia TU117 [GeForce GTX 1630]                                             | 1        | 3.45%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 3.45%   |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1        | 3.45%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 3.45%   |
| Nvidia GA106 [RTX A2000]                                                    | 1        | 3.45%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 1        | 3.45%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 1        | 3.45%   |
| Intel HD Graphics 630                                                       | 1        | 3.45%   |
| Intel HD Graphics 530                                                       | 1        | 3.45%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 3.45%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 3.45%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 3.45%   |
| AMD Raphael                                                                 | 1        | 3.45%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                    | 1        | 3.45%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 1        | 3.45%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1        | 3.45%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 1        | 3.45%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 1        | 3.45%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 1        | 3.45%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                        | 1        | 3.45%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 3.45%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 3.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x AMD     | 13       | 52%     |
| 1 x Nvidia  | 8        | 32%     |
| 1 x Intel   | 3        | 12%     |
| Intel + AMD | 1        | 4%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 16       | 66.67%  |
| Proprietary | 8        | 33.33%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 21       | 87.5%   |
| 3.01-4.0   | 2        | 8.33%   |
| 8.01-16.0  | 1        | 4.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 8        | 32%     |
| BenQ                | 3        | 12%     |
| Toshiba             | 2        | 8%      |
| Sony                | 2        | 8%      |
| Vizio               | 1        | 4%      |
| Sharp               | 1        | 4%      |
| SANYO               | 1        | 4%      |
| Onkyo               | 1        | 4%      |
| MSI                 | 1        | 4%      |
| Insignia            | 1        | 4%      |
| Hewlett-Packard     | 1        | 4%      |
| Goldstar            | 1        | 4%      |
| Dell                | 1        | 4%      |
| ASUSTek Computer    | 1        | 4%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Vizio D40f-G9 VIZ1027 1920x1080 930x520mm 41.9-inch                  | 1        | 4%      |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                     | 1        | 4%      |
| Toshiba TV TSB002F 3840x2160 1095x616mm 49.5-inch                    | 1        | 4%      |
| Sony TV SNYEE01 1920x1080                                            | 1        | 4%      |
| Sony TV SNY3002 1920x1080 1018x573mm 46.0-inch                       | 1        | 4%      |
| Sharp HDMI SHP0FE8 1920x1080 1152x648mm 52.0-inch                    | 1        | 4%      |
| SANYO TV SAN0206 1920x1080 886x498mm 40.0-inch                       | 1        | 4%      |
| Samsung Electronics SyncMaster SAM030F 1680x1050 474x296mm 22.0-inch | 1        | 4%      |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 527x296mm 23.8-inch  | 1        | 4%      |
| Samsung Electronics S24C650 SAM09E8 1920x1080 521x293mm 23.5-inch    | 1        | 4%      |
| Samsung Electronics LCD Monitor SAM065D 1920x1080                    | 1        | 4%      |
| Samsung Electronics LCD Monitor SAM020B 1920x540                     | 1        | 4%      |
| Samsung Electronics LC49G95T SAM7053 2560x1440 1193x336mm 48.8-inch  | 1        | 4%      |
| Samsung Electronics LC27T55 SAM701F 1920x1080 609x349mm 27.6-inch    | 1        | 4%      |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 1        | 4%      |
| Onkyo AV Receiver ONK1150 3840x2160 1872x1053mm 84.6-inch            | 1        | 4%      |
| MSI MAG301CR2 MSI3CB4 2560x1080 690x291mm 29.5-inch                  | 1        | 4%      |
| Insignia NS32DD200NA14 BBY0032 1680x1050 700x390mm 31.5-inch         | 1        | 4%      |
| Hewlett-Packard M24fwa FHD HPN372F 1920x1080 527x296mm 23.8-inch     | 1        | 4%      |
| Goldstar TV GSMC0A0 3840x2160                                        | 1        | 4%      |
| Dell IN1910N DELA04C 1366x768 410x230mm 18.5-inch                    | 1        | 4%      |
| BenQ ZOWIE XL LCD BNQ7F31 1920x1080 531x298mm 24.0-inch              | 1        | 4%      |
| BenQ M2700HD BNQ7C06 1920x1080 598x336mm 27.0-inch                   | 1        | 4%      |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                       | 1        | 4%      |
| ASUSTek Computer ROG XG279Q AUS278D 2560x1440 597x336mm 27.0-inch    | 1        | 4%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 12       | 52.17%  |
| 3840x2160 (4K)     | 3        | 13.04%  |
| 2560x1440 (QHD)    | 2        | 8.7%    |
| 1920x540           | 2        | 8.7%    |
| 3840x1080          | 1        | 4.35%   |
| 2560x1080          | 1        | 4.35%   |
| 1680x1050 (WSXGA+) | 1        | 4.35%   |
| 1366x768 (WXGA)    | 1        | 4.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 72      | 3        | 12%     |
| 27      | 3        | 12%     |
| 23      | 3        | 12%     |
| 84      | 2        | 8%      |
| 48      | 2        | 8%      |
| 24      | 2        | 8%      |
| Unknown | 2        | 8%      |
| 74      | 1        | 4%      |
| 52      | 1        | 4%      |
| 49      | 1        | 4%      |
| 46      | 1        | 4%      |
| 40      | 1        | 4%      |
| 29      | 1        | 4%      |
| 22      | 1        | 4%      |
| 18      | 1        | 4%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 7        | 29.17%  |
| 1501-2000   | 5        | 20.83%  |
| 1001-1500   | 5        | 20.83%  |
| 601-700     | 2        | 8.33%   |
| 401-500     | 2        | 8.33%   |
| Unknown     | 2        | 8.33%   |
| 801-900     | 1        | 4.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 18       | 75%     |
| 32/9  | 2        | 8.33%   |
| 16/10 | 2        | 8.33%   |
| 21/9  | 1        | 4.17%   |
| 1.96  | 1        | 4.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| More than 1000 | 7        | 30.43%  |
| 201-250        | 5        | 21.74%  |
| 301-350        | 4        | 17.39%  |
| 501-1000       | 4        | 17.39%  |
| Unknown        | 2        | 8.7%    |
| 141-150        | 1        | 4.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 14       | 58.33%  |
| 1-50    | 6        | 25%     |
| Unknown | 2        | 8.33%   |
| 121-160 | 1        | 4.17%   |
| 101-120 | 1        | 4.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 88%     |
| 2     | 3        | 12%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 13       | 34.21%  |
| Intel                    | 12       | 31.58%  |
| MediaTek                 | 4        | 10.53%  |
| TP-Link                  | 2        | 5.26%   |
| Qualcomm Atheros         | 2        | 5.26%   |
| Broadcom                 | 2        | 5.26%   |
| Ralink Technology        | 1        | 2.63%   |
| Ralink                   | 1        | 2.63%   |
| Marvell Technology Group | 1        | 2.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6        | 12.24%  |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 8.16%   |
| Intel Wi-Fi 6 AX200                                               | 3        | 6.12%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 6.12%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 4.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 4.08%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2        | 4.08%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2        | 4.08%   |
| Intel I211 Gigabit Network Connection                             | 2        | 4.08%   |
| Intel Ethernet Controller I225-V                                  | 2        | 4.08%   |
| TP-Link Archer T4U ver.3                                          | 1        | 2.04%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 2.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 2.04%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 2.04%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 2.04%   |
| Realtek RTL8187 Wireless Adapter                                  | 1        | 2.04%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                 | 1        | 2.04%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1        | 2.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1        | 2.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 2.04%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 2.04%   |
| Intel Wireless-AC 9260                                            | 1        | 2.04%   |
| Intel Wireless 3165                                               | 1        | 2.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 2.04%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 2.04%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 2.04%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 2.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 2.04%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 2.04%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 2.04%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1        | 2.04%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 6        | 31.58%  |
| MediaTek              | 4        | 21.05%  |
| Realtek Semiconductor | 3        | 15.79%  |
| TP-Link               | 2        | 10.53%  |
| Ralink Technology     | 1        | 5.26%   |
| Ralink                | 1        | 5.26%   |
| Qualcomm Atheros      | 1        | 5.26%   |
| Broadcom              | 1        | 5.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 3        | 13.04%  |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 2        | 8.7%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 2        | 8.7%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 2        | 8.7%    |
| TP-Link Archer T4U ver.3                                      | 1        | 4.35%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 1        | 4.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1        | 4.35%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                        | 1        | 4.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1        | 4.35%   |
| Realtek RTL8187 Wireless Adapter                              | 1        | 4.35%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter             | 1        | 4.35%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                     | 1        | 4.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1        | 4.35%   |
| Intel Wireless-AC 9260                                        | 1        | 4.35%   |
| Intel Wireless 3165                                           | 1        | 4.35%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 1        | 4.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 1        | 4.35%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 1        | 4.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 11       | 44%     |
| Intel                    | 11       | 44%     |
| Qualcomm Atheros         | 1        | 4%      |
| Marvell Technology Group | 1        | 4%      |
| Broadcom                 | 1        | 4%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6        | 23.08%  |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 15.38%  |
| Intel Ethernet Connection I217-LM                                 | 3        | 11.54%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 7.69%   |
| Intel I211 Gigabit Network Connection                             | 2        | 7.69%   |
| Intel Ethernet Controller I225-V                                  | 2        | 7.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 3.85%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 3.85%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 3.85%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 3.85%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 3.85%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 3.85%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 3.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 24       | 61.54%  |
| WiFi     | 15       | 38.46%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 14       | 53.85%  |
| WiFi     | 12       | 46.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 11       | 45.83%  |
| 1     | 11       | 45.83%  |
| 3     | 2        | 8.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 17       | 68%     |
| Yes  | 8        | 32%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 5        | 33.33%  |
| Cambridge Silicon Radio | 4        | 26.67%  |
| MediaTek                | 3        | 20%     |
| IMC Networks            | 1        | 6.67%   |
| ASUSTek Computer        | 1        | 6.67%   |
| Apple                   | 1        | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 25%     |
| MediaTek Wireless_Device                            | 3        | 18.75%  |
| Intel AX200 Bluetooth                               | 2        | 12.5%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 6.25%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 6.25%   |
| Intel Bluetooth wireless interface                  | 1        | 6.25%   |
| Intel AX210 Bluetooth                               | 1        | 6.25%   |
| IMC Networks Bluetooth Radio                        | 1        | 6.25%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 6.25%   |
| Apple Bluetooth USB Host Controller                 | 1        | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 17       | 34.69%  |
| Intel                    | 14       | 28.57%  |
| Nvidia                   | 8        | 16.33%  |
| Logitech                 | 2        | 4.08%   |
| SteelSeries ApS          | 1        | 2.04%   |
| Razer USA                | 1        | 2.04%   |
| Micro Star International | 1        | 2.04%   |
| Kingston Technology      | 1        | 2.04%   |
| Hewlett-Packard          | 1        | 2.04%   |
| Focusrite-Novation       | 1        | 2.04%   |
| ASUSTek Computer         | 1        | 2.04%   |
| Astro Gaming             | 1        | 2.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5        | 8.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4        | 6.45%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4        | 6.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 4.84%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 4.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 3.23%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 3.23%   |
| Intel Comet Lake PCH-V cAVS                                                | 2        | 3.23%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 3.23%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 3.23%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 3.23%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 3.23%   |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                              | 1        | 1.61%   |
| Razer USA Razer Seiren Mini                                                | 1        | 1.61%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 1.61%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 1.61%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 1.61%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 1.61%   |
| Micro Star International USB Audio                                         | 1        | 1.61%   |
| Logitech Logitech USB Microphone                                           | 1        | 1.61%   |
| Logitech G432 Gaming Headset                                               | 1        | 1.61%   |
| Kingston Technology HyperX QuadCast                                        | 1        | 1.61%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1        | 1.61%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 1.61%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 1        | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 1.61%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 1.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 1.61%   |
| Hewlett-Packard HyperX Cloud Stinger Core Wireless DTS                     | 1        | 1.61%   |
| Focusrite-Novation Scarlett 6i6                                            | 1        | 1.61%   |
| ASUSTek Computer USB Audio                                                 | 1        | 1.61%   |
| Astro Gaming ASTRO C40                                                     | 1        | 1.61%   |
| Astro Gaming Astro A50                                                     | 1        | 1.61%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 1        | 1.61%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1        | 1.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 1.61%   |
| AMD Navi 31 [Radeon RX 7000 HDMI Audio]                                    | 1        | 1.61%   |
| AMD Navi 10 HDMI Audio                                                     | 1        | 1.61%   |
| AMD FCH Azalia Controller                                                  | 1        | 1.61%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 1.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

Zero info for selected period =(

Memory Model
------------

Memory module models

Zero info for selected period =(

Memory Kind
-----------

Memory module kinds

Zero info for selected period =(

Memory Form Factor
------------------

Physical design of the memory module

Zero info for selected period =(

Memory Size
-----------

Memory module size

Zero info for selected period =(

Memory Speed
------------

Memory module speed

Zero info for selected period =(

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


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Microdia | 2        | 66.67%  |
| Logitech | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| Microdia Webcam Vitade AF | 1        | 33.33%  |
| Microdia USB Camera       | 1        | 33.33%  |
| Logitech Webcam C200      | 1        | 33.33%  |

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
| 0     | 21       | 87.5%   |
| 1     | 3        | 12.5%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Storage/nvme  | 1        | 33.33%  |
| Network       | 1        | 33.33%  |
| Graphics card | 1        | 33.33%  |

