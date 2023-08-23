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

Total: 33

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple     | MacBookPro12,1              | Notebook    | [4a1def29d3](https://linux-hardware.org/?probe=4a1def29d3) | Aug 09, 2023 |
| ASUSTek   | UX31LA                      | Notebook    | [0695e3bb09](https://linux-hardware.org/?probe=0695e3bb09) | Aug 08, 2023 |
| HUAWEI    | QingYun L420 KLVV-W5821     | Notebook    | [e3227788f6](https://linux-hardware.org/?probe=e3227788f6) | Jul 08, 2023 |
| Lenovo    | ThinkBook 16 G5+ ARP 21J... | Notebook    | [211f5e5cf1](https://linux-hardware.org/?probe=211f5e5cf1) | Jul 02, 2023 |
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
| Kylin V10   | 25        | 92.59%  |
| Kylin V10.1 | 2         | 7.41%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Kylin | 27        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 5.4.18-35-generic       | 5         | 17.86%  |
| 5.19.0-32-generic       | 3         | 10.71%  |
| 5.4.18-15-generic       | 2         | 7.14%   |
| 5.19.0-45-generic       | 2         | 7.14%   |
| 6.2.0-23-generic        | 1         | 3.57%   |
| 6.2.0-21-generic        | 1         | 3.57%   |
| 5.4.96-7-kr9a0          | 1         | 3.57%   |
| 5.4.18-27-generic       | 1         | 3.57%   |
| 5.4.0-155-generic       | 1         | 3.57%   |
| 5.19.0-41-generic       | 1         | 3.57%   |
| 5.15.0-73-generic       | 1         | 3.57%   |
| 5.15.0-69-generic       | 1         | 3.57%   |
| 5.15.0-56-generic       | 1         | 3.57%   |
| 5.10.46-marvis          | 1         | 3.57%   |
| 5.10.0-23-amd64         | 1         | 3.57%   |
| 5.10.0-20-amd64         | 1         | 3.57%   |
| 5.10.0-0.bpo.9-rt-amd64 | 1         | 3.57%   |
| 4.19.71-14-kr990        | 1         | 3.57%   |
| 4.19.260-atzlinux-ft9   | 1         | 3.57%   |
| 4.19.237-atzlinux-ft8   | 1         | 3.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.18   | 8         | 28.57%  |
| 5.19.0   | 6         | 21.43%  |
| 5.15.0   | 3         | 10.71%  |
| 5.10.0   | 3         | 10.71%  |
| 6.2.0    | 2         | 7.14%   |
| 5.4.96   | 1         | 3.57%   |
| 5.4.0    | 1         | 3.57%   |
| 5.10.46  | 1         | 3.57%   |
| 4.19.71  | 1         | 3.57%   |
| 4.19.260 | 1         | 3.57%   |
| 4.19.237 | 1         | 3.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 10        | 37.04%  |
| 5.19    | 6         | 22.22%  |
| 5.10    | 4         | 14.81%  |
| 5.15    | 3         | 11.11%  |
| 6.2     | 2         | 7.41%   |
| 4.19    | 2         | 7.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 20        | 74.07%  |
| aarch64 | 7         | 25.93%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| UKUI       | 12        | 44.44%  |
| GNOME      | 12        | 44.44%  |
| XFCE       | 1         | 3.7%    |
| X-Cinnamon | 1         | 3.7%    |
| KDE5       | 1         | 3.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 19        | 67.86%  |
| Wayland | 6         | 21.43%  |
| Tty     | 3         | 10.71%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 12        | 44.44%  |
| GDM3    | 11        | 40.74%  |
| TDM     | 2         | 7.41%   |
| SDDM    | 1         | 3.7%    |
| GDM     | 1         | 3.7%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| zh_CN | 21        | 77.78%  |
| en_US | 4         | 14.81%  |
| en_HK | 1         | 3.7%    |
| en_CA | 1         | 3.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 23        | 85.19%  |
| BIOS | 4         | 14.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 24        | 88.89%  |
| Overlay | 2         | 7.41%   |
| Tmpfs   | 1         | 3.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 25        | 92.59%  |
| MBR     | 1         | 3.7%    |
| Unknown | 1         | 3.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 21        | 75%     |
| Yes       | 7         | 25%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 18        | 66.67%  |
| Yes       | 9         | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 9         | 33.33%  |
| Phytium             | 3         | 11.11%  |
| HUAWEI              | 3         | 11.11%  |
| Hewlett-Packard     | 3         | 11.11%  |
| Dell                | 2         | 7.41%   |
| ASUSTek Computer    | 2         | 7.41%   |
| Timi                | 1         | 3.7%    |
| THTF                | 1         | 3.7%    |
| GreatWall           | 1         | 3.7%    |
| Gigabyte Technology | 1         | 3.7%    |
| Apple               | 1         | 3.7%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Phytium FT2000/4                             | 2         | 7.41%   |
| Timi TM1612                                  | 1         | 3.7%    |
| THTF CR F860-T1                              | 1         | 3.7%    |
| Phytium FT-2000/4                            | 1         | 3.7%    |
| Lenovo XiaoXinPro 14ACH 2021 82MS            | 1         | 3.7%    |
| Lenovo ThinkPad X200 74574AC                 | 1         | 3.7%    |
| Lenovo ThinkPad X13 Gen 1 20T2A003CD         | 1         | 3.7%    |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y6S00400 | 1         | 3.7%    |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBA002CD  | 1         | 3.7%    |
| Lenovo ThinkPad T480s 20L7A00HHK             | 1         | 3.7%    |
| Lenovo ThinkBook 16 G5+ ARP 21J0             | 1         | 3.7%    |
| Lenovo Legion Y9000P IAH7H 82RF              | 1         | 3.7%    |
| Lenovo IdeaPad 710S-13ISK 80SW               | 1         | 3.7%    |
| HUAWEI QingYun L420 KLVV-W5821               | 1         | 3.7%    |
| HUAWEI MACH-WX9                              | 1         | 3.7%    |
| HUAWEI L410 KLVU-WDU0                        | 1         | 3.7%    |
| HP ZHAN 99 Mobile Workstation G3             | 1         | 3.7%    |
| HP Tablet 11-be0xxx                          | 1         | 3.7%    |
| HP EliteBook 840 G7 Notebook PC              | 1         | 3.7%    |
| Gigabyte Z97X-SLI                            | 1         | 3.7%    |
| Dell Vostro 5880                             | 1         | 3.7%    |
| Dell Inspiron 5468                           | 1         | 3.7%    |
| ASUS VivoBook_ASUSLaptop K5504VA_K5504VA     | 1         | 3.7%    |
| ASUS UX31LA                                  | 1         | 3.7%    |
| Apple MacBookPro12,1                         | 1         | 3.7%    |
| Unknown                                      | 1         | 3.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 5         | 18.52%  |
| Phytium FT2000     | 2         | 7.41%   |
| Timi TM1612        | 1         | 3.7%    |
| THTF CR            | 1         | 3.7%    |
| Phytium FT-2000    | 1         | 3.7%    |
| Lenovo XiaoXinPro  | 1         | 3.7%    |
| Lenovo ThinkBook   | 1         | 3.7%    |
| Lenovo Legion      | 1         | 3.7%    |
| Lenovo IdeaPad     | 1         | 3.7%    |
| HUAWEI QingYun     | 1         | 3.7%    |
| HUAWEI MACH-WX9    | 1         | 3.7%    |
| HUAWEI L410        | 1         | 3.7%    |
| HP ZHAN            | 1         | 3.7%    |
| HP Tablet          | 1         | 3.7%    |
| HP EliteBook       | 1         | 3.7%    |
| Gigabyte Z97X-SLI  | 1         | 3.7%    |
| Dell Vostro        | 1         | 3.7%    |
| Dell Inspiron      | 1         | 3.7%    |
| ASUS VivoBook      | 1         | 3.7%    |
| ASUS UX31LA        | 1         | 3.7%    |
| Apple MacBookPro12 | 1         | 3.7%    |
| Unknown            | 1         | 3.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 6         | 22.22%  |
| 2022    | 4         | 14.81%  |
| 2020    | 4         | 14.81%  |
| 2016    | 3         | 11.11%  |
| 2014    | 3         | 11.11%  |
| Unknown | 3         | 11.11%  |
| 2018    | 2         | 7.41%   |
| 2015    | 1         | 3.7%    |
| 2008    | 1         | 3.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 21        | 77.78%  |
| Server   | 3         | 11.11%  |
| Desktop  | 2         | 7.41%   |
| Tablet   | 1         | 3.7%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 25        | 92.59%  |
| Enabled  | 2         | 7.41%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 27        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 8         | 29.63%  |
| 4.01-8.0    | 6         | 22.22%  |
| 3.01-4.0    | 5         | 18.52%  |
| 16.01-24.0  | 5         | 18.52%  |
| 32.01-64.0  | 1         | 3.7%    |
| 24.01-32.0  | 1         | 3.7%    |
| 64.01-256.0 | 1         | 3.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 3.01-4.0  | 8         | 28.57%  |
| 1.01-2.0  | 8         | 28.57%  |
| 2.01-3.0  | 5         | 17.86%  |
| 4.01-8.0  | 3         | 10.71%  |
| 8.01-16.0 | 2         | 7.14%   |
| 0.51-1.0  | 2         | 7.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 20        | 74.07%  |
| 2      | 4         | 14.81%  |
| 4      | 2         | 7.41%   |
| 3      | 1         | 3.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 26        | 96.3%   |
| Yes       | 1         | 3.7%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 16        | 59.26%  |
| No        | 11        | 40.74%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 81.48%  |
| No        | 5         | 18.52%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 77.78%  |
| No        | 6         | 22.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| China     | 22        | 81.48%  |
| Hong Kong | 3         | 11.11%  |
| Taiwan    | 1         | 3.7%    |
| Canada    | 1         | 3.7%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City       | Computers | Percent |
|------------|-----------|---------|
| Shenzhen   | 3         | 11.11%  |
| Tianjin    | 2         | 7.41%   |
| Shanghai   | 2         | 7.41%   |
| Jinrongjie | 2         | 7.41%   |
| Central    | 2         | 7.41%   |
| Beijing    | 2         | 7.41%   |
| Zhongshan  | 1         | 3.7%    |
| Xuhui      | 1         | 3.7%    |
| Xiaolou    | 1         | 3.7%    |
| Xi'an      | 1         | 3.7%    |
| Shizishan  | 1         | 3.7%    |
| Putuo      | 1         | 3.7%    |
| Mong Kok   | 1         | 3.7%    |
| Markham    | 1         | 3.7%    |
| Harbin     | 1         | 3.7%    |
| Haidian    | 1         | 3.7%    |
| Guangzhou  | 1         | 3.7%    |
| Changsha   | 1         | 3.7%    |
| Chancheng  | 1         | 3.7%    |
| Banqiao    | 1         | 3.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 13     | 30.3%   |
| Micron Technology   | 3         | 3      | 9.09%   |
| Toshiba             | 2         | 2      | 6.06%   |
| FORESEE             | 2         | 3      | 6.06%   |
| ZX1 1TB             | 1         | 1      | 3.03%   |
| WDC                 | 1         | 1      | 3.03%   |
| Unknown             | 1         | 1      | 3.03%   |
| SK hynix            | 1         | 1      | 3.03%   |
| Seagate             | 1         | 1      | 3.03%   |
| SanDisk             | 1         | 1      | 3.03%   |
| Phison              | 1         | 1      | 3.03%   |
| Pear 2TB            | 1         | 1      | 3.03%   |
| Lenovo              | 1         | 1      | 3.03%   |
| Kingston            | 1         | 1      | 3.03%   |
| Kingchuxing         | 1         | 1      | 3.03%   |
| HISI                | 1         | 4      | 3.03%   |
| Hikvision           | 1         | 1      | 3.03%   |
| Hewlett-Packard     | 1         | 1      | 3.03%   |
| FC-1307             | 1         | 1      | 3.03%   |
| Apple               | 1         | 1      | 3.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 2         | 5.88%   |
| Micron MTFDKBA512TFH 512GB                          | 2         | 5.88%   |
| FORESEE 64GB SSD                                    | 2         | 5.88%   |
| ZX1 1TB Disk 1TB                                    | 1         | 2.94%   |
| WDC PC SN530 SDBPNPZ-512G-1014 512GB                | 1         | 2.94%   |
| Unknown NVMe SSD Drive 256GB                        | 1         | 2.94%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 2.94%   |
| Toshiba KXG60ZNV512G KIOXIA 512GB                   | 1         | 2.94%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB              | 1         | 2.94%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 2.94%   |
| SanDisk SD6SP1M256G1102 256GB SSD                   | 1         | 2.94%   |
| Samsung PM991 NVMe 256GB                            | 1         | 2.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 1         | 2.94%   |
| Samsung MZVLW256HEHP-000L2 256GB                    | 1         | 2.94%   |
| Samsung MZVLB512HBJQ-000L7 512GB                    | 1         | 2.94%   |
| Samsung MZVLB512HAJQ-00000 512GB                    | 1         | 2.94%   |
| Samsung MZVL2512HCJQ-00BL7 512GB                    | 1         | 2.94%   |
| Samsung MZNTY128HDHP-00000 128GB SSD                | 1         | 2.94%   |
| Samsung KLUFG8RHDA-B2D1 512GB                       | 1         | 2.94%   |
| Samsung KLUFG8RHDA-B2D1 1GB                         | 1         | 2.94%   |
| Phison ThinkPlus ST8000 PCI-E M.2 256G              | 1         | 2.94%   |
| Pear 2TB Disk 2TB                                   | 1         | 2.94%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                       | 1         | 2.94%   |
| Lenovo SSD SL500 240G                               | 1         | 2.94%   |
| Kingston OM3PDP3128B-AH 128GB                       | 1         | 2.94%   |
| Kingchuxing SSD 128GB                               | 1         | 2.94%   |
| HISI THR920GFCV100HAE 256GB                         | 1         | 2.94%   |
| Hikvision HS-SSD-E2000L 512G                        | 1         | 2.94%   |
| HP SSD EX950 1TB                                    | 1         | 2.94%   |
| FC-1307 SD to CF Adapter V1.4                       | 1         | 2.94%   |
| Apple SSD SM0256G 256GB                             | 1         | 2.94%   |

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
| Samsung Electronics | 2         | 5      | 22.22%  |
| FORESEE             | 2         | 3      | 22.22%  |
| SanDisk             | 1         | 1      | 11.11%  |
| Lenovo              | 1         | 1      | 11.11%  |
| Kingchuxing         | 1         | 1      | 11.11%  |
| HISI                | 1         | 4      | 11.11%  |
| Apple               | 1         | 1      | 11.11%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 17        | 19     | 54.84%  |
| SSD     | 9         | 16     | 29.03%  |
| HDD     | 3         | 3      | 9.68%   |
| Unknown | 2         | 2      | 6.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 17        | 19     | 54.84%  |
| SATA | 12        | 19     | 38.71%  |
| SAS  | 2         | 2      | 6.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 9         | 15     | 69.23%  |
| 0.51-1.0   | 3         | 3      | 23.08%  |
| 1.01-2.0   | 1         | 1      | 7.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 10        | 35.71%  |
| 51-100     | 7         | 25%     |
| 101-250    | 6         | 21.43%  |
| 501-1000   | 3         | 10.71%  |
| 21-50      | 1         | 3.57%   |
| 1001-2000  | 1         | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 21-50    | 9         | 33.33%  |
| 51-100   | 6         | 22.22%  |
| 1-20     | 5         | 18.52%  |
| 101-250  | 4         | 14.81%  |
| 251-500  | 2         | 7.41%   |
| 501-1000 | 1         | 3.7%    |

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
| Works    | 20        | 23     | 71.43%  |
| Detected | 8         | 17     | 28.57%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Samsung Electronics             | 9         | 29.03%  |
| Intel                           | 8         | 25.81%  |
| Micron Technology               | 3         | 9.68%   |
| Phison Electronics              | 2         | 6.45%   |
| Marvell Technology Group        | 2         | 6.45%   |
| Toshiba America Info Systems    | 1         | 3.23%   |
| SK hynix                        | 1         | 3.23%   |
| Silicon Motion                  | 1         | 3.23%   |
| SanDisk                         | 1         | 3.23%   |
| Kingston Technology Company     | 1         | 3.23%   |
| Hefei DATANG Storage Technology | 1         | 3.23%   |
| AMD                             | 1         | 3.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                         | 3         | 9.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                        | 3         | 9.38%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                    | 3         | 9.38%   |
| Phison PS5013 E13 NVMe Controller                                     | 2         | 6.25%   |
| Micron 3400 NVMe SSD [Hendrix]                                        | 2         | 6.25%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller      | 2         | 6.25%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                  | 1         | 3.13%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                  | 1         | 3.13%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                         | 1         | 3.13%   |
| SanDisk WD Blue SN550 NVMe SSD                                        | 1         | 3.13%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)            | 1         | 3.13%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                         | 1         | 3.13%   |
| Samsung NVMe SSD Controller 980                                       | 1         | 3.13%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                           | 1         | 3.13%   |
| Kingston Company OM3PDP3 NVMe SSD                                     | 1         | 3.13%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation | 1         | 3.13%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                      | 1         | 3.13%   |
| Intel Comet Lake SATA AHCI Controller                                 | 1         | 3.13%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]             | 1         | 3.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode] | 1         | 3.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                          | 1         | 3.13%   |
| Hefei DATANG Storage NVMe SSD Controller 300A                         | 1         | 3.13%   |
| AMD FCH SATA Controller [AHCI mode]                                   | 1         | 3.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 17        | 56.67%  |
| SATA | 11        | 36.67%  |
| RAID | 1         | 3.33%   |
| IDE  | 1         | 3.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 17        | 62.96%  |
| Phytium | 5         | 18.52%  |
| AMD     | 3         | 11.11%  |
| ARM     | 2         | 7.41%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Phytium FT2000/4                        | 2         | 7.41%   |
| Phytium FT-2000/4                       | 2         | 7.41%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 7.41%   |
| ARM Processor                           | 2         | 7.41%   |
| Phytium D2000/8 E8C                     | 1         | 3.7%    |
| Intel Pentium Silver N6000 @ 1.10GHz    | 1         | 3.7%    |
| Intel Core m3-6Y30 CPU @ 0.90GHz        | 1         | 3.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 3.7%    |
| Intel Core i7-7500U CPU @ 2.70GHz       | 1         | 3.7%    |
| Intel Core i7-6560U CPU @ 2.20GHz       | 1         | 3.7%    |
| Intel Core i7-4790 CPU @ 3.60GHz        | 1         | 3.7%    |
| Intel Core i7-10700 CPU @ 2.90GHz       | 1         | 3.7%    |
| Intel Core i5-8350U CPU @ 1.70GHz       | 1         | 3.7%    |
| Intel Core i5-5257U CPU @ 2.70GHz       | 1         | 3.7%    |
| Intel Core i5-4200U CPU @ 1.60GHz       | 1         | 3.7%    |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz    | 1         | 3.7%    |
| Intel 13th Gen Core i9-13900H           | 1         | 3.7%    |
| Intel 12th Gen Core i7-12700H           | 1         | 3.7%    |
| Intel 12th Gen Core i5-1240P            | 1         | 3.7%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 1         | 3.7%    |
| AMD Ryzen 7 7735H with Radeon Graphics  | 1         | 3.7%    |
| AMD Ryzen 7 5800H with Radeon Graphics  | 1         | 3.7%    |
| AMD Ryzen 5 5600H with Radeon Graphics  | 1         | 3.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Other                | 11        | 40.74%  |
| Intel Core i7        | 5         | 18.52%  |
| Intel Core i5        | 5         | 18.52%  |
| AMD Ryzen 7          | 2         | 7.41%   |
| Intel Pentium Silver | 1         | 3.7%    |
| Intel Core m3        | 1         | 3.7%    |
| Intel Core 2 Duo     | 1         | 3.7%    |
| AMD Ryzen 5          | 1         | 3.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 10        | 37.04%  |
| 2      | 6         | 22.22%  |
| 8      | 5         | 18.52%  |
| 6      | 3         | 11.11%  |
| 14     | 2         | 7.41%   |
| 12     | 1         | 3.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 24        | 88.89%  |
| 3      | 2         | 7.41%   |
| 2      | 1         | 3.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 17        | 62.96%  |
| 1      | 10        | 37.04%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 27        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 11        | 40.74%  |
| 0x806ec    | 2         | 7.41%   |
| 0x406e3    | 2         | 7.41%   |
| 0xa0655    | 1         | 3.7%    |
| 0x906c0    | 1         | 3.7%    |
| 0x906a3    | 1         | 3.7%    |
| 0x806ea    | 1         | 3.7%    |
| 0x806e9    | 1         | 3.7%    |
| 0x40651    | 1         | 3.7%    |
| 0x306d4    | 1         | 3.7%    |
| 0x306c3    | 1         | 3.7%    |
| 0x1067a    | 1         | 3.7%    |
| 0x0a50000d | 1         | 3.7%    |
| 0x0a50000b | 1         | 3.7%    |
| 0x0a404102 | 1         | 3.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 10        | 37.04%  |
| KabyLake         | 5         | 18.52%  |
| Zen 3            | 2         | 7.41%   |
| Skylake          | 2         | 7.41%   |
| Haswell          | 2         | 7.41%   |
| Alderlake Hybrid | 2         | 7.41%   |
| Tremont          | 1         | 3.7%    |
| Penryn           | 1         | 3.7%    |
| CometLake        | 1         | 3.7%    |
| Broadwell        | 1         | 3.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 17        | 53.13%  |
| AMD    | 9         | 28.13%  |
| Nvidia | 6         | 18.75%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 2         | 6.25%   |
| Intel UHD Graphics 620                                                                | 2         | 6.25%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 6.25%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 2         | 6.25%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                  | 2         | 6.25%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 2         | 6.25%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                    | 2         | 6.25%   |
| Nvidia TU117GLM [T600 Mobile]                                                         | 1         | 3.13%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 3.13%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 1         | 3.13%   |
| Nvidia GK208B [GeForce GT 730]                                                        | 1         | 3.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 1         | 3.13%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 1         | 3.13%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 1         | 3.13%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 3.13%   |
| Intel JasperLake [UHD Graphics]                                                       | 1         | 3.13%   |
| Intel Iris Graphics 6100                                                              | 1         | 3.13%   |
| Intel Iris Graphics 540                                                               | 1         | 3.13%   |
| Intel HD Graphics 620                                                                 | 1         | 3.13%   |
| Intel HD Graphics 515                                                                 | 1         | 3.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 1         | 3.13%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                              | 1         | 3.13%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 3.13%   |
| AMD Rembrandt [Radeon 680M]                                                           | 1         | 3.13%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                            | 1         | 3.13%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 11        | 40.74%  |
| 1 x AMD        | 7         | 25.93%  |
| Intel + Nvidia | 4         | 14.81%  |
| Other          | 2         | 7.41%   |
| 1 x Nvidia     | 1         | 3.7%    |
| Intel + AMD    | 1         | 3.7%    |
| AMD + Nvidia   | 1         | 3.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 22        | 81.48%  |
| Proprietary | 3         | 11.11%  |
| Unknown     | 2         | 7.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 59.26%  |
| 1.01-2.0   | 6         | 22.22%  |
| 0.51-1.0   | 2         | 7.41%   |
| 5.01-6.0   | 1         | 3.7%    |
| 3.01-4.0   | 1         | 3.7%    |
| 0.01-0.5   | 1         | 3.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| BOE                  | 7         | 21.88%  |
| Dell                 | 4         | 12.5%   |
| LG Display           | 3         | 9.38%   |
| Chimei Innolux       | 3         | 9.38%   |
| Xiaomi               | 2         | 6.25%   |
| Lenovo               | 2         | 6.25%   |
| CSO                  | 2         | 6.25%   |
| AOC                  | 2         | 6.25%   |
| Samsung Electronics  | 1         | 3.13%   |
| KIG                  | 1         | 3.13%   |
| JDI                  | 1         | 3.13%   |
| CPT                  | 1         | 3.13%   |
| BenQ                 | 1         | 3.13%   |
| Apple                | 1         | 3.13%   |
| Ancor Communications | 1         | 3.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Xiaomi Mi TV XMD004A 1920x1080 890x500mm 40.2-inch                    | 2         | 6.25%   |
| Dell P2422H DELA1C4 1920x1080 527x296mm 23.8-inch                     | 2         | 6.25%   |
| Samsung Electronics LCD Monitor SDC4180 2880x1620 344x194mm 15.5-inch | 1         | 3.13%   |
| LG Display LCD Monitor LGD06AA 3840x2400 344x215mm 16.0-inch          | 1         | 3.13%   |
| LG Display LCD Monitor LGD060A 1920x1080 294x165mm 13.3-inch          | 1         | 3.13%   |
| LG Display LCD Monitor LGD04EF 1920x1080 294x165mm 13.3-inch          | 1         | 3.13%   |
| Lenovo X24i-10 LEN61AA 1920x1080 527x296mm 23.8-inch                  | 1         | 3.13%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch               | 1         | 3.13%   |
| KIG KKTV KIG2700 1920x1080 598x336mm 27.0-inch                        | 1         | 3.13%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 1         | 3.13%   |
| Dell P2717H DEL40F7 1920x1080 598x336mm 27.0-inch                     | 1         | 3.13%   |
| Dell 1704FPT DEL4005 1280x1024 338x270mm 17.0-inch                    | 1         | 3.13%   |
| CSO LCD Monitor CSO1612 2560x1600 345x215mm 16.0-inch                 | 1         | 3.13%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                 | 1         | 3.13%   |
| CPT LCD Monitor CPT17DB 1600x900 293x164mm 13.2-inch                  | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN153A 1920x1080 344x193mm 15.5-inch      | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch      | 1         | 3.13%   |
| BOE LCD Monitor BOE0AC9 2240x1400 302x189mm 14.0-inch                 | 1         | 3.13%   |
| BOE LCD Monitor BOE0AC1 2560x1600 344x215mm 16.0-inch                 | 1         | 3.13%   |
| BOE LCD Monitor BOE0A0A 2160x1440 233x155mm 11.0-inch                 | 1         | 3.13%   |
| BOE LCD Monitor BOE08DA 1920x1080 309x174mm 14.0-inch                 | 1         | 3.13%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                 | 1         | 3.13%   |
| BOE LCD Monitor BOE06B6 1366x768 309x173mm 13.9-inch                  | 1         | 3.13%   |
| BOE LCD Monitor BOE0691 1920x1080 280x165mm 12.8-inch                 | 1         | 3.13%   |
| BenQ LCD Monitor G2400W 1920x1200                                     | 1         | 3.13%   |
| Apple Color LCD APPA02A 2560x1600 286x179mm 13.3-inch                 | 1         | 3.13%   |
| AOC Q27B3MA AOC2703 2560x1440 597x336mm 27.0-inch                     | 1         | 3.13%   |
| AOC 23E1WX AOC2301 1920x1080 488x297mm 22.5-inch                      | 1         | 3.13%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 1         | 3.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 13        | 43.33%  |
| 3840x2160 (4K)    | 3         | 10%     |
| 2560x1600         | 3         | 10%     |
| 3840x2400         | 1         | 3.33%   |
| 3000x2000         | 1         | 3.33%   |
| 2880x1800         | 1         | 3.33%   |
| 2880x1620         | 1         | 3.33%   |
| 2240x1400         | 1         | 3.33%   |
| 2160x1440         | 1         | 3.33%   |
| 1920x1200 (WUXGA) | 1         | 3.33%   |
| 1600x900 (HD+)    | 1         | 3.33%   |
| 1366x768 (WXGA)   | 1         | 3.33%   |
| 1280x800 (WXGA)   | 1         | 3.33%   |
| 1280x1024 (SXGA)  | 1         | 3.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 8         | 25%     |
| 14      | 4         | 12.5%   |
| 27      | 3         | 9.38%   |
| 16      | 3         | 9.38%   |
| 65      | 2         | 6.25%   |
| 24      | 2         | 6.25%   |
| 23      | 2         | 6.25%   |
| 15      | 2         | 6.25%   |
| 12      | 2         | 6.25%   |
| 22      | 1         | 3.13%   |
| 17      | 1         | 3.13%   |
| 11      | 1         | 3.13%   |
| Unknown | 1         | 3.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 13        | 40.63%  |
| 201-300     | 8         | 25%     |
| 501-600     | 7         | 21.88%  |
| 1001-1500   | 2         | 6.25%   |
| 401-500     | 1         | 3.13%   |
| Unknown     | 1         | 3.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 17        | 60.71%  |
| 16/10   | 7         | 25%     |
| 3/2     | 2         | 7.14%   |
| 5/4     | 1         | 3.57%   |
| Unknown | 1         | 3.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 9         | 28.13%  |
| 201-250        | 5         | 15.63%  |
| 71-80          | 4         | 12.5%   |
| 301-350        | 3         | 9.38%   |
| 111-120        | 3         | 9.38%   |
| More than 1000 | 2         | 6.25%   |
| 101-110        | 2         | 6.25%   |
| 61-70          | 1         | 3.13%   |
| 51-60          | 1         | 3.13%   |
| 141-150        | 1         | 3.13%   |
| Unknown        | 1         | 3.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 161-240       | 9         | 30%     |
| 121-160       | 7         | 23.33%  |
| 51-100        | 7         | 23.33%  |
| More than 240 | 3         | 10%     |
| 1-50          | 2         | 6.67%   |
| 101-120       | 1         | 3.33%   |
| Unknown       | 1         | 3.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 18        | 64.29%  |
| 2     | 7         | 25%     |
| 0     | 3         | 10.71%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 15        | 40.54%  |
| Realtek Semiconductor      | 13        | 35.14%  |
| MediaTek                   | 2         | 5.41%   |
| Huawei Technologies        | 2         | 5.41%   |
| ASIX Electronics           | 2         | 5.41%   |
| Quectel Wireless Solutions | 1         | 2.7%    |
| ICS Advent                 | 1         | 2.7%    |
| Broadcom                   | 1         | 2.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 13.95%  |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 4.65%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 4.65%   |
| Intel Wireless 8265 / 8275                                        | 2         | 4.65%   |
| Intel Wireless 8260                                               | 2         | 4.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 4.65%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 4.65%   |
| Huawei Network controller                                         | 2         | 4.65%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 4.65%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 2.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.33%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 2.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 2.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 2.33%   |
| Quectel Wireless Solutions Quectel EM05-CE                        | 1         | 2.33%   |
| Intel Wireless 7260                                               | 1         | 2.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 2.33%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 1         | 2.33%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 2.33%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 1         | 2.33%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 2.33%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.33%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 2.33%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 2.33%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.33%   |
| ICS Advent 10/100M LAN                                            | 1         | 2.33%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 2.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 14        | 60.87%  |
| Realtek Semiconductor      | 5         | 21.74%  |
| MediaTek                   | 2         | 8.7%    |
| Quectel Wireless Solutions | 1         | 4.35%   |
| Broadcom                   | 1         | 4.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 8.7%    |
| Intel Wireless 8265 / 8275                                    | 2         | 8.7%    |
| Intel Wireless 8260                                           | 2         | 8.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 8.7%    |
| Intel Alder Lake-P PCH CNVi WiFi                              | 2         | 8.7%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 4.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 4.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 4.35%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 4.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1         | 4.35%   |
| Quectel Wireless Solutions Quectel EM05-CE                    | 1         | 4.35%   |
| Intel Wireless 7260                                           | 1         | 4.35%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 1         | 4.35%   |
| Intel Wi-Fi 6 AX201 160MHz                                    | 1         | 4.35%   |
| Intel Wi-Fi 6 AX200                                           | 1         | 4.35%   |
| Intel Raptor Lake PCH CNVi WiFi                               | 1         | 4.35%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection       | 1         | 4.35%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 1         | 4.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 10        | 55.56%  |
| Intel                 | 5         | 27.78%  |
| ASIX Electronics      | 2         | 11.11%  |
| ICS Advent            | 1         | 5.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 33.33%  |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 11.11%  |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 11.11%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 5.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 5.56%   |
| Intel Ethernet Connection I217-V                                  | 1         | 5.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 5.56%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 5.56%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 5.56%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 5.56%   |
| ICS Advent 10/100M LAN                                            | 1         | 5.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 22        | 55%     |
| Ethernet | 16        | 40%     |
| Unknown  | 2         | 5%      |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 19        | 73.08%  |
| Ethernet | 7         | 26.92%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 13        | 48.15%  |
| 2     | 11        | 40.74%  |
| 0     | 3         | 11.11%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 23        | 85.19%  |
| Yes  | 4         | 14.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 61.9%   |
| Realtek Semiconductor           | 2         | 9.52%   |
| Foxconn / Hon Hai               | 2         | 9.52%   |
| Qualcomm Atheros Communications | 1         | 4.76%   |
| IMC Networks                    | 1         | 4.76%   |
| Broadcom                        | 1         | 4.76%   |
| Apple                           | 1         | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 5         | 23.81%  |
| Intel Bluetooth Device                             | 3         | 14.29%  |
| Intel AX201 Bluetooth                              | 3         | 14.29%  |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter       | 2         | 9.52%   |
| Realtek Bluetooth Radio                            | 1         | 4.76%   |
| Realtek 802.11n WLAN Adapter                       | 1         | 4.76%   |
| Qualcomm Atheros  Bluetooth Device                 | 1         | 4.76%   |
| Intel AX210 Bluetooth                              | 1         | 4.76%   |
| Intel AX200 Bluetooth                              | 1         | 4.76%   |
| IMC Networks Bluetooth Radio                       | 1         | 4.76%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 4.76%   |
| Apple Bluetooth Host Controller                    | 1         | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 17        | 53.13%  |
| AMD                                          | 8         | 25%     |
| Nvidia                                       | 5         | 15.63%  |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 6.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 5         | 13.51%  |
| AMD Family 17h/19h HD Audio Controller                                            | 3         | 8.11%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 3         | 8.11%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                    | 2         | 5.41%   |
| Nvidia GA106 High Definition Audio Controller                                     | 2         | 5.41%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 2         | 5.41%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 2         | 5.41%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 5.41%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 2.7%    |
| Nvidia GP106 High Definition Audio Controller                                     | 1         | 2.7%    |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1         | 2.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1         | 2.7%    |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 1         | 2.7%    |
| Intel Tiger Lake-H HD Audio Controller                                            | 1         | 2.7%    |
| Intel Raptor Lake-P/U/H cAVS                                                      | 1         | 2.7%    |
| Intel Jasper Lake HD Audio                                                        | 1         | 2.7%    |
| Intel Haswell-ULT HD Audio Controller                                             | 1         | 2.7%    |
| Intel Comet Lake PCH cAVS                                                         | 1         | 2.7%    |
| Intel Broadwell-U Audio Controller                                                | 1         | 2.7%    |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 1         | 2.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 1         | 2.7%    |
| Intel 8 Series HD Audio Controller                                                | 1         | 2.7%    |
| AMD Renoir Radeon High Definition Audio Controller                                | 1         | 2.7%    |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 1         | 2.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Micron Technology   | 8         | 33.33%  |
| SK hynix            | 6         | 25%     |
| Samsung Electronics | 5         | 20.83%  |
| Elpida              | 2         | 8.33%   |
| UNILC               | 1         | 4.17%   |
| Nanya Technology    | 1         | 4.17%   |
| Unknown             | 1         | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Micron RAM Not Set 8192MB DIMM DDR4 2668MT/s                     | 2         | 8%      |
| UNILC RAM 6478545886 8192MB SODIMM DDR4 2400MT/s                 | 1         | 4%      |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s                     | 1         | 4%      |
| SK hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                | 1         | 4%      |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 1         | 4%      |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s             | 1         | 4%      |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 4%      |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips 6400MT/s        | 1         | 4%      |
| SK hynix RAM H9HKNNNFBMBUDR 8192MB Row Of Chips LPDDR4 4266MT/s  | 1         | 4%      |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 1         | 4%      |
| Samsung RAM Module 2048MB SODIMM LPDDR3 1867MT/s                 | 1         | 4%      |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 4%      |
| Samsung RAM K3UH7H70AM 8192MB Row Of Chips LPDDR4 4266MT/s       | 1         | 4%      |
| Samsung RAM 6478545886 16GB DIMM DDR4 2668MT/s                   | 1         | 4%      |
| Nanya RAM M2N2G64CB8HA5N-BE 2GB SODIMM 1066MT/s                  | 1         | 4%      |
| Micron RAM MT62F2G32D8DR-031 WT 8GB Row Of Chips LPDDR5 6400MT/s | 1         | 4%      |
| Micron RAM MT62F1G32D4DR-031 2GB Row Of Chips LPDDR5 6400MT/s    | 1         | 4%      |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 4%      |
| Micron RAM 53E512M32D2NP-046 1GB Row Of Chips LPDDR4 4267MT/s    | 1         | 4%      |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 4%      |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 4%      |
| Elpida RAM Module 2048MB SODIMM DDR3 1600MT/s                    | 1         | 4%      |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s            | 1         | 4%      |
| Unknown                                                          | 1         | 4%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 11        | 44%     |
| LPDDR4  | 4         | 16%     |
| LPDDR5  | 3         | 12%     |
| LPDDR3  | 3         | 12%     |
| DDR3    | 3         | 12%     |
| Unknown | 1         | 4%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 11        | 47.83%  |
| Row Of Chips | 8         | 34.78%  |
| DIMM         | 4         | 17.39%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 14        | 60.87%  |
| 4096  | 4         | 17.39%  |
| 2048  | 4         | 17.39%  |
| 16384 | 1         | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 6400  | 3         | 12.5%   |
| 3200  | 3         | 12.5%   |
| 2668  | 3         | 12.5%   |
| 2667  | 3         | 12.5%   |
| 1867  | 3         | 12.5%   |
| 4266  | 2         | 8.33%   |
| 4267  | 1         | 4.17%   |
| 2666  | 1         | 4.17%   |
| 2400  | 1         | 4.17%   |
| 2133  | 1         | 4.17%   |
| 1600  | 1         | 4.17%   |
| 1067  | 1         | 4.17%   |
| 1066  | 1         | 4.17%   |

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
| Chicony Electronics                    | 6         | 31.58%  |
| IMC Networks                           | 3         | 15.79%  |
| Unknown (0000066029)                   | 2         | 10.53%  |
| Syntek                                 | 1         | 5.26%   |
| Sonix Technology                       | 1         | 5.26%   |
| Realtek Semiconductor                  | 1         | 5.26%   |
| Microdia                               | 1         | 5.26%   |
| Luxvisions Innotech Limited            | 1         | 5.26%   |
| Lenovo                                 | 1         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 5.26%   |
| BL012030059711690428                   | 1         | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown (0000066029) HD Camera                      | 2         | 10.53%  |
| IMC Networks Integrated Camera                      | 2         | 10.53%  |
| Syntek Integrated Camera                            | 1         | 5.26%   |
| Sonix USB2.0 FHD UVC WebCam                         | 1         | 5.26%   |
| Realtek Integrated_Webcam_HD                        | 1         | 5.26%   |
| Microdia USB2.0 Camera                              | 1         | 5.26%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 5.26%   |
| Lenovo Integrated Webcam                            | 1         | 5.26%   |
| IMC Networks Integrated RGB Camera                  | 1         | 5.26%   |
| Chicony XiaoMi USB 2.0 Webcam                       | 1         | 5.26%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 5.26%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 5.26%   |
| Chicony Integrated Camera                           | 1         | 5.26%   |
| Chicony HP HD Camera                                | 1         | 5.26%   |
| Chicony EasyCamera                                  | 1         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 1         | 5.26%   |
| BL012030059711690428 Integrated Camera              | 1         | 5.26%   |

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
| 0     | 17        | 62.96%  |
| 1     | 9         | 33.33%  |
| 2     | 1         | 3.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 5         | 45.45%  |
| Multimedia controller | 2         | 18.18%  |
| Graphics card         | 2         | 18.18%  |
| Net/wireless          | 1         | 9.09%   |
| Camera                | 1         | 9.09%   |

