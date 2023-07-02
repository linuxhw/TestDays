Kylin - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for Kylin.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Kylin/Desktop/README.md) and [notebooks](/Dist/Kylin/Notebook/README.md).

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

Total: 29

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo    | ThinkPad X1 Extreme Gen ... | Notebook    | [80b6536a46](https://linux-hardware.org/?probe=80b6536a46) | Jun 28, 2023 |
| HUAWEI    | MACH-WX9                    | Notebook    | [016268562d](https://linux-hardware.org/?probe=016268562d) | Jun 21, 2023 |
| HUAWEI    | MACH-WX9                    | Notebook    | [25bc3b1533](https://linux-hardware.org/?probe=25bc3b1533) | Jun 21, 2023 |
| Dell      | Inspiron 5468               | Notebook    | [b16aeda09e](https://linux-hardware.org/?probe=b16aeda09e) | Jun 02, 2023 |
| Lenovo    | ThinkPad X200 74574AC       | Notebook    | [e770387a34](https://linux-hardware.org/?probe=e770387a34) | May 25, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop K550... | Notebook    | [cacfc4dacd](https://linux-hardware.org/?probe=cacfc4dacd) | May 16, 2023 |
| HP        | ZHAN 99 Mobile Workstati... | Notebook    | [3dcc7ab043](https://linux-hardware.org/?probe=3dcc7ab043) | Apr 12, 2023 |
| Lenovo    | Legion Y9000P IAH7H 82RF    | Notebook    | [30d91acf27](https://linux-hardware.org/?probe=30d91acf27) | Mar 07, 2023 |
| Lenovo    | Legion Y9000P IAH7H 82RF    | Notebook    | [97925534c2](https://linux-hardware.org/?probe=97925534c2) | Mar 02, 2023 |
| Dell      | 0V7K5Y A00                  | Desktop     | [831a493e15](https://linux-hardware.org/?probe=831a493e15) | Feb 24, 2023 |
| Lenovo    | ThinkPad X1 Carbon Gen 1... | Notebook    | [cc10e54ab9](https://linux-hardware.org/?probe=cc10e54ab9) | Feb 20, 2023 |
| Lenovo    | XiaoXinPro 14ACH 2021 82... | Notebook    | [29326a6340](https://linux-hardware.org/?probe=29326a6340) | Feb 11, 2023 |
| Lenovo    | ThinkPad T480s 20L7A00HH... | Notebook    | [801c1bad94](https://linux-hardware.org/?probe=801c1bad94) | Jan 02, 2023 |
| Gigabyte  | Z97X-SLI-CF                 | Desktop     | [4e829bc252](https://linux-hardware.org/?probe=4e829bc252) | Dec 10, 2022 |
| THTF      | CR F860-T1                  | Notebook    | [9f0a52783f](https://linux-hardware.org/?probe=9f0a52783f) | Oct 27, 2022 |
| Phytium   | D2000                       | Server      | [e43b580add](https://linux-hardware.org/?probe=e43b580add) | Oct 18, 2022 |
| HUAWEI    | L410 KLVU-WDU0              | Notebook    | [00edb23106](https://linux-hardware.org/?probe=00edb23106) | Oct 07, 2022 |
| Phytium   | FT2000/4                    | Server      | [5f7f5d61af](https://linux-hardware.org/?probe=5f7f5d61af) | Oct 02, 2022 |
| Phytium   | FT2000/4                    | Server      | [c8aa4d1457](https://linux-hardware.org/?probe=c8aa4d1457) | Sep 30, 2022 |
| Phytium   | FT2000/4                    | Server      | [ff17710900](https://linux-hardware.org/?probe=ff17710900) | Sep 29, 2022 |
| GreatWall | Unknown                     | Notebook    | [12ee24a7c7](https://linux-hardware.org/?probe=12ee24a7c7) | Sep 20, 2022 |
| HP        | Tablet 11-be0xxx            | Tablet      | [e3bcbaf593](https://linux-hardware.org/?probe=e3bcbaf593) | Apr 08, 2022 |
| Timi      | TM1612                      | Notebook    | [fe85c2d733](https://linux-hardware.org/?probe=fe85c2d733) | Feb 05, 2022 |
| HANWEI    | FT-208-COME-B               | Soc         | [d22caa9915](https://linux-hardware.org/?probe=d22caa9915) | Jan 23, 2022 |
| Phytium   | FT-2000/4 V0001             | Server      | [152a75acd0](https://linux-hardware.org/?probe=152a75acd0) | Jan 19, 2022 |
| Lenovo    | ThinkPad X13 Gen 1 20T2A... | Notebook    | [0c261084db](https://linux-hardware.org/?probe=0c261084db) | Oct 16, 2021 |
| HP        | EliteBook 840 G7 Noteboo... | Notebook    | [ebe2901cc8](https://linux-hardware.org/?probe=ebe2901cc8) | Apr 30, 2021 |
| Lenovo    | IdeaPad 710S-13ISK 80SW     | Notebook    | [55b2402c28](https://linux-hardware.org/?probe=55b2402c28) | Feb 25, 2021 |
| Lenovo    | IdeaPad 710S-13ISK 80SW     | Notebook    | [44013b0bb4](https://linux-hardware.org/?probe=44013b0bb4) | Feb 23, 2021 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Kylin V10   | 21        | 91.3%   |
| Kylin V10.1 | 2         | 8.7%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Kylin | 23        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 5.4.18-35-generic       | 5         | 20.83%  |
| 5.19.0-32-generic       | 3         | 12.5%   |
| 5.4.18-15-generic       | 2         | 8.33%   |
| 6.2.0-23-generic        | 1         | 4.17%   |
| 6.2.0-21-generic        | 1         | 4.17%   |
| 5.4.18-27-generic       | 1         | 4.17%   |
| 5.19.0-45-generic       | 1         | 4.17%   |
| 5.19.0-41-generic       | 1         | 4.17%   |
| 5.15.0-73-generic       | 1         | 4.17%   |
| 5.15.0-69-generic       | 1         | 4.17%   |
| 5.15.0-56-generic       | 1         | 4.17%   |
| 5.10.46-marvis          | 1         | 4.17%   |
| 5.10.0-20-amd64         | 1         | 4.17%   |
| 5.10.0-0.bpo.9-rt-amd64 | 1         | 4.17%   |
| 4.19.71-14-kr990        | 1         | 4.17%   |
| 4.19.260-atzlinux-ft9   | 1         | 4.17%   |
| 4.19.237-atzlinux-ft8   | 1         | 4.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.18   | 8         | 33.33%  |
| 5.19.0   | 5         | 20.83%  |
| 5.15.0   | 3         | 12.5%   |
| 6.2.0    | 2         | 8.33%   |
| 5.10.0   | 2         | 8.33%   |
| 5.10.46  | 1         | 4.17%   |
| 4.19.71  | 1         | 4.17%   |
| 4.19.260 | 1         | 4.17%   |
| 4.19.237 | 1         | 4.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 8         | 34.78%  |
| 5.19    | 5         | 21.74%  |
| 5.15    | 3         | 13.04%  |
| 5.10    | 3         | 13.04%  |
| 6.2     | 2         | 8.7%    |
| 4.19    | 2         | 8.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 17        | 73.91%  |
| aarch64 | 6         | 26.09%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| UKUI  | 11        | 47.83%  |
| GNOME | 10        | 43.48%  |
| XFCE  | 1         | 4.35%   |
| KDE5  | 1         | 4.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 16        | 66.67%  |
| Wayland | 5         | 20.83%  |
| Tty     | 3         | 12.5%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 10        | 43.48%  |
| GDM3    | 9         | 39.13%  |
| TDM     | 2         | 8.7%    |
| SDDM    | 1         | 4.35%   |
| GDM     | 1         | 4.35%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| zh_CN | 19        | 82.61%  |
| en_US | 3         | 13.04%  |
| en_CA | 1         | 4.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 20        | 86.96%  |
| BIOS | 3         | 13.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 21        | 91.3%   |
| Tmpfs   | 1         | 4.35%   |
| Overlay | 1         | 4.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 21        | 91.3%   |
| MBR     | 1         | 4.35%   |
| Unknown | 1         | 4.35%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 18        | 75%     |
| Yes       | 6         | 25%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 15        | 65.22%  |
| Yes       | 8         | 34.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 8         | 34.78%  |
| Phytium             | 3         | 13.04%  |
| Hewlett-Packard     | 3         | 13.04%  |
| HUAWEI              | 2         | 8.7%    |
| Dell                | 2         | 8.7%    |
| Timi                | 1         | 4.35%   |
| THTF                | 1         | 4.35%   |
| GreatWall           | 1         | 4.35%   |
| Gigabyte Technology | 1         | 4.35%   |
| ASUSTek Computer    | 1         | 4.35%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Phytium FT2000/4                             | 2         | 8.7%    |
| Timi TM1612                                  | 1         | 4.35%   |
| THTF CR F860-T1                              | 1         | 4.35%   |
| Phytium FT-2000/4                            | 1         | 4.35%   |
| Lenovo XiaoXinPro 14ACH 2021 82MS            | 1         | 4.35%   |
| Lenovo ThinkPad X200 74574AC                 | 1         | 4.35%   |
| Lenovo ThinkPad X13 Gen 1 20T2A003CD         | 1         | 4.35%   |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y6S00400 | 1         | 4.35%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBA002CD  | 1         | 4.35%   |
| Lenovo ThinkPad T480s 20L7A00HHK             | 1         | 4.35%   |
| Lenovo Legion Y9000P IAH7H 82RF              | 1         | 4.35%   |
| Lenovo IdeaPad 710S-13ISK 80SW               | 1         | 4.35%   |
| HUAWEI MACH-WX9                              | 1         | 4.35%   |
| HUAWEI L410 KLVU-WDU0                        | 1         | 4.35%   |
| HP ZHAN 99 Mobile Workstation G3             | 1         | 4.35%   |
| HP Tablet 11-be0xxx                          | 1         | 4.35%   |
| HP EliteBook 840 G7 Notebook PC              | 1         | 4.35%   |
| Gigabyte Z97X-SLI                            | 1         | 4.35%   |
| Dell Vostro 5880                             | 1         | 4.35%   |
| Dell Inspiron 5468                           | 1         | 4.35%   |
| ASUS VivoBook_ASUSLaptop K5504VA_K5504VA     | 1         | 4.35%   |
| Unknown                                      | 1         | 4.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 5         | 21.74%  |
| Phytium FT2000    | 2         | 8.7%    |
| Timi TM1612       | 1         | 4.35%   |
| THTF CR           | 1         | 4.35%   |
| Phytium FT-2000   | 1         | 4.35%   |
| Lenovo XiaoXinPro | 1         | 4.35%   |
| Lenovo Legion     | 1         | 4.35%   |
| Lenovo IdeaPad    | 1         | 4.35%   |
| HUAWEI MACH-WX9   | 1         | 4.35%   |
| HUAWEI L410       | 1         | 4.35%   |
| HP ZHAN           | 1         | 4.35%   |
| HP Tablet         | 1         | 4.35%   |
| HP EliteBook      | 1         | 4.35%   |
| Gigabyte Z97X-SLI | 1         | 4.35%   |
| Dell Vostro       | 1         | 4.35%   |
| Dell Inspiron     | 1         | 4.35%   |
| ASUS VivoBook     | 1         | 4.35%   |
| Unknown           | 1         | 4.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 5         | 21.74%  |
| 2020    | 4         | 17.39%  |
| 2022    | 3         | 13.04%  |
| 2016    | 3         | 13.04%  |
| Unknown | 3         | 13.04%  |
| 2018    | 2         | 8.7%    |
| 2014    | 2         | 8.7%    |
| 2008    | 1         | 4.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 17        | 73.91%  |
| Server   | 3         | 13.04%  |
| Desktop  | 2         | 8.7%    |
| Tablet   | 1         | 4.35%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 22        | 95.65%  |
| Enabled  | 1         | 4.35%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 23        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 8         | 34.78%  |
| 16.01-24.0  | 5         | 21.74%  |
| 4.01-8.0    | 4         | 17.39%  |
| 3.01-4.0    | 4         | 17.39%  |
| 32.01-64.0  | 1         | 4.35%   |
| 64.01-256.0 | 1         | 4.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 7         | 29.17%  |
| 3.01-4.0  | 6         | 25%     |
| 2.01-3.0  | 5         | 20.83%  |
| 4.01-8.0  | 2         | 8.33%   |
| 8.01-16.0 | 2         | 8.33%   |
| 0.51-1.0  | 2         | 8.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 17        | 73.91%  |
| 2      | 4         | 17.39%  |
| 4      | 1         | 4.35%   |
| 3      | 1         | 4.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 22        | 95.65%  |
| Yes       | 1         | 4.35%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 13        | 56.52%  |
| No        | 10        | 43.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 82.61%  |
| No        | 4         | 17.39%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 78.26%  |
| No        | 5         | 21.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| China     | 19        | 82.61%  |
| Hong Kong | 3         | 13.04%  |
| Canada    | 1         | 4.35%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City       | Computers | Percent |
|------------|-----------|---------|
| Shenzhen   | 3         | 13.04%  |
| Tianjin    | 2         | 8.7%    |
| Jinrongjie | 2         | 8.7%    |
| Central    | 2         | 8.7%    |
| Beijing    | 2         | 8.7%    |
| Xuhui      | 1         | 4.35%   |
| Xi'an      | 1         | 4.35%   |
| Shizishan  | 1         | 4.35%   |
| Shanghai   | 1         | 4.35%   |
| Putuo      | 1         | 4.35%   |
| Mong Kok   | 1         | 4.35%   |
| Markham    | 1         | 4.35%   |
| Harbin     | 1         | 4.35%   |
| Haidian    | 1         | 4.35%   |
| Guangzhou  | 1         | 4.35%   |
| Changsha   | 1         | 4.35%   |
| Chancheng  | 1         | 4.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 13     | 34.48%  |
| Toshiba             | 2         | 2      | 6.9%    |
| Micron Technology   | 2         | 2      | 6.9%    |
| FORESEE             | 2         | 3      | 6.9%    |
| ZX1 1TB             | 1         | 1      | 3.45%   |
| WDC                 | 1         | 1      | 3.45%   |
| Unknown             | 1         | 1      | 3.45%   |
| SK hynix            | 1         | 1      | 3.45%   |
| Seagate             | 1         | 1      | 3.45%   |
| Phison              | 1         | 1      | 3.45%   |
| Pear 2TB            | 1         | 1      | 3.45%   |
| Lenovo              | 1         | 1      | 3.45%   |
| Kingston            | 1         | 1      | 3.45%   |
| Kingchuxing         | 1         | 1      | 3.45%   |
| Hikvision           | 1         | 1      | 3.45%   |
| Hewlett-Packard     | 1         | 1      | 3.45%   |
| FC-1307             | 1         | 1      | 3.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 2         | 6.67%   |
| FORESEE 64GB SSD                                    | 2         | 6.67%   |
| ZX1 1TB Disk 1TB                                    | 1         | 3.33%   |
| WDC PC SN530 SDBPNPZ-512G-1014 512GB                | 1         | 3.33%   |
| Unknown NVMe SSD Drive 256GB                        | 1         | 3.33%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 3.33%   |
| Toshiba KXG60ZNV512G KIOXIA 512GB                   | 1         | 3.33%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB              | 1         | 3.33%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 3.33%   |
| Samsung PM991 NVMe 256GB                            | 1         | 3.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 1         | 3.33%   |
| Samsung MZVLW256HEHP-000L2 256GB                    | 1         | 3.33%   |
| Samsung MZVLB512HBJQ-000L7 512GB                    | 1         | 3.33%   |
| Samsung MZVLB512HAJQ-00000 512GB                    | 1         | 3.33%   |
| Samsung MZVL2512HCJQ-00BL7 512GB                    | 1         | 3.33%   |
| Samsung MZNTY128HDHP-00000 128GB SSD                | 1         | 3.33%   |
| Samsung KLUFG8RHDA-B2D1 512GB                       | 1         | 3.33%   |
| Samsung KLUFG8RHDA-B2D1 1GB                         | 1         | 3.33%   |
| Phison ThinkPlus ST8000 PCI-E M.2 256G              | 1         | 3.33%   |
| Pear 2TB Disk 2TB                                   | 1         | 3.33%   |
| Micron MTFDKBA512TFH 512GB                          | 1         | 3.33%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                       | 1         | 3.33%   |
| Lenovo SSD SL500 240G                               | 1         | 3.33%   |
| Kingston OM3PDP3128B-AH 128GB                       | 1         | 3.33%   |
| Kingchuxing SSD 128GB                               | 1         | 3.33%   |
| Hikvision HS-SSD-E2000L 512G                        | 1         | 3.33%   |
| HP SSD EX950 1TB                                    | 1         | 3.33%   |
| FC-1307 SD to CF Adapter V1.4                       | 1         | 3.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 1         | 1      | 33.33%  |
| Seagate  | 1         | 1      | 33.33%  |
| Pear 2TB | 1         | 1      | 33.33%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 5      | 33.33%  |
| FORESEE             | 2         | 3      | 33.33%  |
| Lenovo              | 1         | 1      | 16.67%  |
| Kingchuxing         | 1         | 1      | 16.67%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 16        | 18     | 59.26%  |
| SSD     | 6         | 10     | 22.22%  |
| HDD     | 3         | 3      | 11.11%  |
| Unknown | 2         | 2      | 7.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 16        | 18     | 59.26%  |
| SATA | 9         | 13     | 33.33%  |
| SAS  | 2         | 2      | 7.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 6         | 9      | 60%     |
| 0.51-1.0   | 3         | 3      | 30%     |
| 1.01-2.0   | 1         | 1      | 10%     |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 9         | 37.5%   |
| 51-100     | 6         | 25%     |
| 101-250    | 4         | 16.67%  |
| 501-1000   | 3         | 12.5%   |
| 21-50      | 1         | 4.17%   |
| 1001-2000  | 1         | 4.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 21-50    | 8         | 34.78%  |
| 1-20     | 5         | 21.74%  |
| 101-250  | 4         | 17.39%  |
| 51-100   | 4         | 17.39%  |
| 251-500  | 1         | 4.35%   |
| 501-1000 | 1         | 4.35%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 17        | 20     | 70.83%  |
| Detected | 7         | 13     | 29.17%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Samsung Electronics             | 8         | 28.57%  |
| Intel                           | 7         | 25%     |
| Phison Electronics              | 2         | 7.14%   |
| Micron Technology               | 2         | 7.14%   |
| Marvell Technology Group        | 2         | 7.14%   |
| Toshiba America Info Systems    | 1         | 3.57%   |
| SK hynix                        | 1         | 3.57%   |
| Silicon Motion                  | 1         | 3.57%   |
| SanDisk                         | 1         | 3.57%   |
| Kingston Technology Company     | 1         | 3.57%   |
| Hefei DATANG Storage Technology | 1         | 3.57%   |
| AMD                             | 1         | 3.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                         | 3         | 10.34%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                        | 3         | 10.34%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                    | 3         | 10.34%  |
| Phison PS5013 E13 NVMe Controller                                     | 2         | 6.9%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller      | 2         | 6.9%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                  | 1         | 3.45%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                  | 1         | 3.45%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                         | 1         | 3.45%   |
| SanDisk WD Blue SN550 NVMe SSD                                        | 1         | 3.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                         | 1         | 3.45%   |
| Samsung NVMe SSD Controller 980                                       | 1         | 3.45%   |
| Micron NVMe Storage Controller                                        | 1         | 3.45%   |
| Micron 2450 NVMe SSD (DRAM-less)                                      | 1         | 3.45%   |
| Kingston Company OM3PDP3 NVMe SSD                                     | 1         | 3.45%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation | 1         | 3.45%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                      | 1         | 3.45%   |
| Intel Comet Lake SATA AHCI Controller                                 | 1         | 3.45%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]             | 1         | 3.45%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode] | 1         | 3.45%   |
| Hefei DATANG Storage NVMe SSD Controller 300A                         | 1         | 3.45%   |
| AMD FCH SATA Controller [AHCI mode]                                   | 1         | 3.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 16        | 59.26%  |
| SATA | 9         | 33.33%  |
| RAID | 1         | 3.7%    |
| IDE  | 1         | 3.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 15        | 65.22%  |
| Phytium | 5         | 21.74%  |
| AMD     | 2         | 8.7%    |
| ARM     | 1         | 4.35%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Phytium FT2000/4                        | 2         | 8.7%    |
| Phytium FT-2000/4                       | 2         | 8.7%    |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 8.7%    |
| Phytium D2000/8 E8C                     | 1         | 4.35%   |
| Intel Pentium Silver N6000 @ 1.10GHz    | 1         | 4.35%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz        | 1         | 4.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 4.35%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 1         | 4.35%   |
| Intel Core i7-6560U CPU @ 2.20GHz       | 1         | 4.35%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 1         | 4.35%   |
| Intel Core i7-10700 CPU @ 2.90GHz       | 1         | 4.35%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 1         | 4.35%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz    | 1         | 4.35%   |
| Intel 13th Gen Core i9-13900H           | 1         | 4.35%   |
| Intel 12th Gen Core i7-12700H           | 1         | 4.35%   |
| Intel 12th Gen Core i5-1240P            | 1         | 4.35%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 1         | 4.35%   |
| ARM Processor                           | 1         | 4.35%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 1         | 4.35%   |
| AMD Ryzen 5 5600H with Radeon Graphics  | 1         | 4.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Other                | 10        | 43.48%  |
| Intel Core i7        | 5         | 21.74%  |
| Intel Core i5        | 3         | 13.04%  |
| Intel Pentium Silver | 1         | 4.35%   |
| Intel Core m3        | 1         | 4.35%   |
| Intel Core 2 Duo     | 1         | 4.35%   |
| AMD Ryzen 7          | 1         | 4.35%   |
| AMD Ryzen 5          | 1         | 4.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 10        | 43.48%  |
| 8      | 4         | 17.39%  |
| 2      | 4         | 17.39%  |
| 14     | 2         | 8.7%    |
| 6      | 2         | 8.7%    |
| 12     | 1         | 4.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 21        | 91.3%   |
| 3      | 1         | 4.35%   |
| 2      | 1         | 4.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 14        | 60.87%  |
| 1      | 9         | 39.13%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 23        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 10        | 43.48%  |
| 0x806ec    | 2         | 8.7%    |
| 0x406e3    | 2         | 8.7%    |
| 0xa0655    | 1         | 4.35%   |
| 0x906c0    | 1         | 4.35%   |
| 0x906a3    | 1         | 4.35%   |
| 0x806ea    | 1         | 4.35%   |
| 0x806e9    | 1         | 4.35%   |
| 0x306c3    | 1         | 4.35%   |
| 0x1067a    | 1         | 4.35%   |
| 0x0a50000d | 1         | 4.35%   |
| 0x0a50000b | 1         | 4.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 8         | 34.78%  |
| KabyLake         | 5         | 21.74%  |
| Zen 3            | 2         | 8.7%    |
| Skylake          | 2         | 8.7%    |
| Alderlake Hybrid | 2         | 8.7%    |
| Tremont          | 1         | 4.35%   |
| Penryn           | 1         | 4.35%   |
| Haswell          | 1         | 4.35%   |
| CometLake        | 1         | 4.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 15        | 51.72%  |
| AMD    | 8         | 27.59%  |
| Nvidia | 6         | 20.69%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 2         | 6.9%    |
| Intel UHD Graphics 620                                                                | 2         | 6.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 6.9%    |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 2         | 6.9%    |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                  | 2         | 6.9%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 2         | 6.9%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                    | 2         | 6.9%    |
| Nvidia TU117GLM [T600 Mobile]                                                         | 1         | 3.45%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 3.45%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 1         | 3.45%   |
| Nvidia GK208B [GeForce GT 730]                                                        | 1         | 3.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 1         | 3.45%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 1         | 3.45%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 1         | 3.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 3.45%   |
| Intel JasperLake [UHD Graphics]                                                       | 1         | 3.45%   |
| Intel Iris Graphics 540                                                               | 1         | 3.45%   |
| Intel HD Graphics 620                                                                 | 1         | 3.45%   |
| Intel HD Graphics 515                                                                 | 1         | 3.45%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                              | 1         | 3.45%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 3.45%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                            | 1         | 3.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 9         | 39.13%  |
| 1 x AMD        | 6         | 26.09%  |
| Intel + Nvidia | 4         | 17.39%  |
| Other          | 1         | 4.35%   |
| 1 x Nvidia     | 1         | 4.35%   |
| Intel + AMD    | 1         | 4.35%   |
| AMD + Nvidia   | 1         | 4.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 19        | 82.61%  |
| Proprietary | 3         | 13.04%  |
| Unknown     | 1         | 4.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 56.52%  |
| 1.01-2.0   | 6         | 26.09%  |
| 0.51-1.0   | 2         | 8.7%    |
| 5.01-6.0   | 1         | 4.35%   |
| 0.01-0.5   | 1         | 4.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| BOE                  | 6         | 20.69%  |
| Dell                 | 4         | 13.79%  |
| LG Display           | 3         | 10.34%  |
| Chimei Innolux       | 3         | 10.34%  |
| Xiaomi               | 2         | 6.9%    |
| Lenovo               | 2         | 6.9%    |
| CSO                  | 2         | 6.9%    |
| AOC                  | 2         | 6.9%    |
| Samsung Electronics  | 1         | 3.45%   |
| KIG                  | 1         | 3.45%   |
| JDI                  | 1         | 3.45%   |
| BenQ                 | 1         | 3.45%   |
| Ancor Communications | 1         | 3.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Xiaomi Mi TV XMD004A 1920x1080 708x398mm 32.0-inch                    | 2         | 6.9%    |
| Dell P2422H DELA1C4 1920x1080 527x296mm 23.8-inch                     | 2         | 6.9%    |
| Samsung Electronics LCD Monitor SDC4180 2880x1620 344x194mm 15.5-inch | 1         | 3.45%   |
| LG Display LCD Monitor LGD06AA 3840x2400 344x215mm 16.0-inch          | 1         | 3.45%   |
| LG Display LCD Monitor LGD060A 1920x1080 294x165mm 13.3-inch          | 1         | 3.45%   |
| LG Display LCD Monitor LGD04EF 1920x1080 294x165mm 13.3-inch          | 1         | 3.45%   |
| Lenovo X24i-10 LEN61AA 1920x1080 527x296mm 23.8-inch                  | 1         | 3.45%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch               | 1         | 3.45%   |
| KIG KKTV KIG2700 1920x1080 598x336mm 27.0-inch                        | 1         | 3.45%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 1         | 3.45%   |
| Dell P2717H DEL40F7 1920x1080 598x336mm 27.0-inch                     | 1         | 3.45%   |
| Dell 1704FPT DEL4005 1280x1024 338x270mm 17.0-inch                    | 1         | 3.45%   |
| CSO LCD Monitor CSO1612 2560x1600 345x215mm 16.0-inch                 | 1         | 3.45%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                 | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN153A 1920x1080 344x193mm 15.5-inch      | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch      | 1         | 3.45%   |
| BOE LCD Monitor BOE0AC9 2240x1400 302x189mm 14.0-inch                 | 1         | 3.45%   |
| BOE LCD Monitor BOE0A0A 2160x1440 233x155mm 11.0-inch                 | 1         | 3.45%   |
| BOE LCD Monitor BOE08DA 1920x1080 309x174mm 14.0-inch                 | 1         | 3.45%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                 | 1         | 3.45%   |
| BOE LCD Monitor BOE06B6 1366x768 309x173mm 13.9-inch                  | 1         | 3.45%   |
| BOE LCD Monitor BOE0691 1920x1080 280x165mm 12.8-inch                 | 1         | 3.45%   |
| BenQ LCD Monitor G2400W 1920x1200                                     | 1         | 3.45%   |
| AOC Q27B3MA AOC2703 2560x1440 597x336mm 27.0-inch                     | 1         | 3.45%   |
| AOC 23E1WX AOC2301 1920x1080 488x297mm 22.5-inch                      | 1         | 3.45%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 1         | 3.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 13        | 48.15%  |
| 3840x2160 (4K)    | 3         | 11.11%  |
| 3840x2400         | 1         | 3.7%    |
| 3000x2000         | 1         | 3.7%    |
| 2880x1800         | 1         | 3.7%    |
| 2880x1620         | 1         | 3.7%    |
| 2560x1600         | 1         | 3.7%    |
| 2240x1400         | 1         | 3.7%    |
| 2160x1440         | 1         | 3.7%    |
| 1920x1200 (WUXGA) | 1         | 3.7%    |
| 1366x768 (WXGA)   | 1         | 3.7%    |
| 1280x800 (WXGA)   | 1         | 3.7%    |
| 1280x1024 (SXGA)  | 1         | 3.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 6         | 20.69%  |
| 14      | 4         | 13.79%  |
| 27      | 3         | 10.34%  |
| 65      | 2         | 6.9%    |
| 24      | 2         | 6.9%    |
| 23      | 2         | 6.9%    |
| 16      | 2         | 6.9%    |
| 15      | 2         | 6.9%    |
| 12      | 2         | 6.9%    |
| 22      | 1         | 3.45%   |
| 17      | 1         | 3.45%   |
| 11      | 1         | 3.45%   |
| Unknown | 1         | 3.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 12        | 41.38%  |
| 501-600     | 7         | 24.14%  |
| 201-300     | 6         | 20.69%  |
| 1001-1500   | 2         | 6.9%    |
| 401-500     | 1         | 3.45%   |
| Unknown     | 1         | 3.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 16        | 64%     |
| 16/10   | 5         | 20%     |
| 3/2     | 2         | 8%      |
| 5/4     | 1         | 4%      |
| Unknown | 1         | 4%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 8         | 27.59%  |
| 201-250        | 5         | 17.24%  |
| 71-80          | 3         | 10.34%  |
| 301-350        | 3         | 10.34%  |
| More than 1000 | 2         | 6.9%    |
| 111-120        | 2         | 6.9%    |
| 101-110        | 2         | 6.9%    |
| 61-70          | 1         | 3.45%   |
| 51-60          | 1         | 3.45%   |
| 141-150        | 1         | 3.45%   |
| Unknown        | 1         | 3.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 161-240       | 7         | 25.93%  |
| 51-100        | 7         | 25.93%  |
| 121-160       | 6         | 22.22%  |
| More than 240 | 3         | 11.11%  |
| 1-50          | 2         | 7.41%   |
| 101-120       | 1         | 3.7%    |
| Unknown       | 1         | 3.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 15        | 62.5%   |
| 2     | 7         | 29.17%  |
| 0     | 2         | 8.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 14        | 46.67%  |
| Realtek Semiconductor      | 10        | 33.33%  |
| ASIX Electronics           | 2         | 6.67%   |
| Quectel Wireless Solutions | 1         | 3.33%   |
| MediaTek                   | 1         | 3.33%   |
| ICS Advent                 | 1         | 3.33%   |
| Huawei Technologies        | 1         | 3.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 11.11%  |
| Intel Wireless 8265 / 8275                                        | 2         | 5.56%   |
| Intel Wireless 8260                                               | 2         | 5.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 5.56%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 5.56%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 5.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 2.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.78%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 2.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 2.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.78%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 2.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 2.78%   |
| Quectel Wireless Solutions Quectel EM05-CE                        | 1         | 2.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 2.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 2.78%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 1         | 2.78%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 2.78%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 2.78%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.78%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 2.78%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 2.78%   |
| Intel Alder Lake-U CNVi: Wireless-AC                              | 1         | 2.78%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.78%   |
| ICS Advent 10/100M LAN                                            | 1         | 2.78%   |
| Huawei Network controller                                         | 1         | 2.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 13        | 65%     |
| Realtek Semiconductor      | 5         | 25%     |
| Quectel Wireless Solutions | 1         | 5%      |
| MediaTek                   | 1         | 5%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                    | 2         | 10%     |
| Intel Wireless 8260                                           | 2         | 10%     |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 10%     |
| Intel Alder Lake-P PCH CNVi WiFi                              | 2         | 10%     |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 5%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 5%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 5%      |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 5%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1         | 5%      |
| Quectel Wireless Solutions Quectel EM05-CE                    | 1         | 5%      |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 5%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 1         | 5%      |
| Intel Wi-Fi 6 AX201 160MHz                                    | 1         | 5%      |
| Intel Wi-Fi 6 AX200                                           | 1         | 5%      |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection       | 1         | 5%      |
| Intel Alder Lake-U CNVi: Wireless-AC                          | 1         | 5%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 7         | 46.67%  |
| Intel                 | 5         | 33.33%  |
| ASIX Electronics      | 2         | 13.33%  |
| ICS Advent            | 1         | 6.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 26.67%  |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 13.33%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 6.67%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 6.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 6.67%   |
| Intel Ethernet Connection I217-V                                  | 1         | 6.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 6.67%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 6.67%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 6.67%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 6.67%   |
| ICS Advent 10/100M LAN                                            | 1         | 6.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 19        | 57.58%  |
| Ethernet | 13        | 39.39%  |
| Unknown  | 1         | 3.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 16        | 72.73%  |
| Ethernet | 6         | 27.27%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 11        | 47.83%  |
| 2     | 9         | 39.13%  |
| 0     | 3         | 13.04%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 19        | 82.61%  |
| Yes  | 4         | 17.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 66.67%  |
| Realtek Semiconductor           | 2         | 11.11%  |
| Qualcomm Atheros Communications | 1         | 5.56%   |
| IMC Networks                    | 1         | 5.56%   |
| Foxconn / Hon Hai               | 1         | 5.56%   |
| Broadcom                        | 1         | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 4         | 22.22%  |
| Intel Bluetooth Device                             | 3         | 16.67%  |
| Intel AX201 Bluetooth                              | 3         | 16.67%  |
| Realtek Bluetooth Radio                            | 1         | 5.56%   |
| Realtek 802.11n WLAN Adapter                       | 1         | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                 | 1         | 5.56%   |
| Intel AX210 Bluetooth                              | 1         | 5.56%   |
| Intel AX200 Bluetooth                              | 1         | 5.56%   |
| IMC Networks Bluetooth Radio                       | 1         | 5.56%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter       | 1         | 5.56%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 15        | 51.72%  |
| AMD                                          | 7         | 24.14%  |
| Nvidia                                       | 5         | 17.24%  |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 6.9%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 5         | 16.13%  |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 3         | 9.68%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                    | 2         | 6.45%   |
| Nvidia GA106 High Definition Audio Controller                                     | 2         | 6.45%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 2         | 6.45%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 2         | 6.45%   |
| AMD Family 17h/19h HD Audio Controller                                            | 2         | 6.45%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 6.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 3.23%   |
| Nvidia GP106 High Definition Audio Controller                                     | 1         | 3.23%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1         | 3.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1         | 3.23%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 1         | 3.23%   |
| Intel Jasper Lake HD Audio                                                        | 1         | 3.23%   |
| Intel Comet Lake PCH cAVS                                                         | 1         | 3.23%   |
| Intel Alder Lake-U cAVS (Audio, Voice, Speech)                                    | 1         | 3.23%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 1         | 3.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 1         | 3.23%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 1         | 3.23%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Micron Technology   | 7         | 35%     |
| Samsung Electronics | 5         | 25%     |
| SK hynix            | 4         | 20%     |
| UNILC               | 1         | 5%      |
| Nanya Technology    | 1         | 5%      |
| Elpida              | 1         | 5%      |
| Unknown             | 1         | 5%      |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Micron RAM Not Set 8192MB DIMM DDR4 2668MT/s                     | 2         | 9.52%   |
| UNILC RAM 6478545886 8192MB SODIMM DDR4 2400MT/s                 | 1         | 4.76%   |
| SK hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                | 1         | 4.76%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 4.76%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s             | 1         | 4.76%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 4.76%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 4.76%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 1         | 4.76%   |
| Samsung RAM Module 2048MB SODIMM LPDDR3 1867MT/s                 | 1         | 4.76%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 4.76%   |
| Samsung RAM K3UH7H70AM 8192MB Row Of Chips LPDDR4 4266MT/s       | 1         | 4.76%   |
| Samsung RAM 6478545886 16GB DIMM DDR4 2668MT/s                   | 1         | 4.76%   |
| Nanya RAM M2N2G64CB8HA5N-BE 2GB SODIMM 1066MT/s                  | 1         | 4.76%   |
| Micron RAM MT62F1G32D4DR-031 2GB Row Of Chips LPDDR5 6400MT/s    | 1         | 4.76%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 4.76%   |
| Micron RAM 53E512M32D2NP-046 1GB Row Of Chips LPDDR4 4267MT/s    | 1         | 4.76%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 4.76%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 4.76%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s            | 1         | 4.76%   |
| Unknown                                                          | 1         | 4.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 11        | 52.38%  |
| LPDDR4  | 3         | 14.29%  |
| LPDDR3  | 3         | 14.29%  |
| LPDDR5  | 2         | 9.52%   |
| DDR3    | 1         | 4.76%   |
| Unknown | 1         | 4.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 9         | 47.37%  |
| Row Of Chips | 6         | 31.58%  |
| DIMM         | 4         | 21.05%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 12        | 63.16%  |
| 4096  | 3         | 15.79%  |
| 2048  | 3         | 15.79%  |
| 16384 | 1         | 5.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 3         | 15%     |
| 2668  | 3         | 15%     |
| 2667  | 3         | 15%     |
| 6400  | 2         | 10%     |
| 1867  | 2         | 10%     |
| 4267  | 1         | 5%      |
| 4266  | 1         | 5%      |
| 2666  | 1         | 5%      |
| 2400  | 1         | 5%      |
| 2133  | 1         | 5%      |
| 1067  | 1         | 5%      |
| 1066  | 1         | 5%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 50%     |
| Hewlett-Packard     | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung M2020 Series    | 1         | 50%     |
| HP DeskJet F4200 series | 1         | 50%     |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 5         | 31.25%  |
| IMC Networks                           | 3         | 18.75%  |
| Unknown (0000034083)                   | 1         | 6.25%   |
| Sonix Technology                       | 1         | 6.25%   |
| Realtek Semiconductor                  | 1         | 6.25%   |
| Microdia                               | 1         | 6.25%   |
| Luxvisions Innotech Limited            | 1         | 6.25%   |
| Lenovo                                 | 1         | 6.25%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 6.25%   |
| BL012030059711690428                   | 1         | 6.25%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                      | 2         | 12.5%   |
| Unknown (0000034083) HD Camera                      | 1         | 6.25%   |
| Sonix USB2.0 FHD UVC WebCam                         | 1         | 6.25%   |
| Realtek Integrated_Webcam_HD                        | 1         | 6.25%   |
| Microdia USB2.0 Camera                              | 1         | 6.25%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 6.25%   |
| Lenovo Integrated Webcam                            | 1         | 6.25%   |
| IMC Networks Integrated RGB Camera                  | 1         | 6.25%   |
| Chicony XiaoMi USB 2.0 Webcam                       | 1         | 6.25%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 6.25%   |
| Chicony Integrated Camera                           | 1         | 6.25%   |
| Chicony HP HD Camera                                | 1         | 6.25%   |
| Chicony EasyCamera                                  | 1         | 6.25%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 1         | 6.25%   |
| BL012030059711690428 Integrated Camera              | 1         | 6.25%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Computers | Percent |
|-----------|-----------|---------|
| Synaptics | 4         | 80%     |
| AuthenTec | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics UWP WBDI Device                                 | 1         | 20%     |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 20%     |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 20%     |
| AuthenTec AES2810                                         | 1         | 20%     |

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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 14        | 60.87%  |
| 1     | 8         | 34.78%  |
| 2     | 1         | 4.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 5         | 50%     |
| Graphics card         | 2         | 20%     |
| Net/wireless          | 1         | 10%     |
| Multimedia controller | 1         | 10%     |
| Camera                | 1         | 10%     |

