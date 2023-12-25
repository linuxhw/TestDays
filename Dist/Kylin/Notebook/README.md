Kylin - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for Kylin.

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

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| HUAWEI    | CREM-WXX9                   | [cf753bfc89](https://linux-hardware.org/?probe=cf753bfc89) | Dec 05, 2023 |
| HUAWEI    | KLVDZ-WXX9                  | [d6486c4e50](https://linux-hardware.org/?probe=d6486c4e50) | Oct 27, 2023 |
| ASUSTek   | TUF Gaming FX505GT          | [a5fde2a0ed](https://linux-hardware.org/?probe=a5fde2a0ed) | Oct 24, 2023 |
| Dell      | Vostro 3350                 | [1034a53a9d](https://linux-hardware.org/?probe=1034a53a9d) | Sep 30, 2023 |
| Lenovo    | Legion R9000P2021H 82JQ     | [5168f99a06](https://linux-hardware.org/?probe=5168f99a06) | Sep 26, 2023 |
| ASUSTek   | ROG Strix G713PV_G713PV     | [0d1c562190](https://linux-hardware.org/?probe=0d1c562190) | Sep 08, 2023 |
| Apple     | MacBookPro12,1              | [4a1def29d3](https://linux-hardware.org/?probe=4a1def29d3) | Aug 09, 2023 |
| ASUSTek   | UX31LA                      | [0695e3bb09](https://linux-hardware.org/?probe=0695e3bb09) | Aug 08, 2023 |
| HUAWEI    | QingYun L420 KLVV-W5821     | [e3227788f6](https://linux-hardware.org/?probe=e3227788f6) | Jul 08, 2023 |
| Lenovo    | ThinkBook 16 G5+ ARP 21J... | [211f5e5cf1](https://linux-hardware.org/?probe=211f5e5cf1) | Jul 02, 2023 |
| Lenovo    | ThinkPad X1 Extreme Gen ... | [80b6536a46](https://linux-hardware.org/?probe=80b6536a46) | Jun 28, 2023 |
| HUAWEI    | MACH-WX9                    | [016268562d](https://linux-hardware.org/?probe=016268562d) | Jun 21, 2023 |
| HUAWEI    | MACH-WX9                    | [25bc3b1533](https://linux-hardware.org/?probe=25bc3b1533) | Jun 21, 2023 |
| Dell      | Inspiron 5468               | [b16aeda09e](https://linux-hardware.org/?probe=b16aeda09e) | Jun 02, 2023 |
| Lenovo    | ThinkPad X200 74574AC       | [e770387a34](https://linux-hardware.org/?probe=e770387a34) | May 25, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop K550... | [cacfc4dacd](https://linux-hardware.org/?probe=cacfc4dacd) | May 16, 2023 |
| HP        | ZHAN 99 Mobile Workstati... | [3dcc7ab043](https://linux-hardware.org/?probe=3dcc7ab043) | Apr 12, 2023 |
| Lenovo    | Legion Y9000P IAH7H 82RF    | [30d91acf27](https://linux-hardware.org/?probe=30d91acf27) | Mar 07, 2023 |
| Lenovo    | Legion Y9000P IAH7H 82RF    | [97925534c2](https://linux-hardware.org/?probe=97925534c2) | Mar 02, 2023 |
| Lenovo    | ThinkPad X1 Carbon Gen 1... | [cc10e54ab9](https://linux-hardware.org/?probe=cc10e54ab9) | Feb 20, 2023 |
| Lenovo    | XiaoXinPro 14ACH 2021 82... | [29326a6340](https://linux-hardware.org/?probe=29326a6340) | Feb 11, 2023 |
| Lenovo    | ThinkPad T480s 20L7A00HH... | [801c1bad94](https://linux-hardware.org/?probe=801c1bad94) | Jan 02, 2023 |
| THTF      | CR F860-T1                  | [9f0a52783f](https://linux-hardware.org/?probe=9f0a52783f) | Oct 27, 2022 |
| HUAWEI    | L410 KLVU-WDU0              | [00edb23106](https://linux-hardware.org/?probe=00edb23106) | Oct 07, 2022 |
| GreatWall | Unknown                     | [12ee24a7c7](https://linux-hardware.org/?probe=12ee24a7c7) | Sep 20, 2022 |
| Timi      | TM1612                      | [fe85c2d733](https://linux-hardware.org/?probe=fe85c2d733) | Feb 05, 2022 |
| Lenovo    | ThinkPad X13 Gen 1 20T2A... | [0c261084db](https://linux-hardware.org/?probe=0c261084db) | Oct 16, 2021 |
| HP        | EliteBook 840 G7 Noteboo... | [ebe2901cc8](https://linux-hardware.org/?probe=ebe2901cc8) | Apr 30, 2021 |
| Lenovo    | IdeaPad 710S-13ISK 80SW     | [55b2402c28](https://linux-hardware.org/?probe=55b2402c28) | Feb 25, 2021 |
| Lenovo    | IdeaPad 710S-13ISK 80SW     | [44013b0bb4](https://linux-hardware.org/?probe=44013b0bb4) | Feb 23, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Kylin V10   | 25        | 92.59%  |
| Kylin V10.1 | 2         | 7.41%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Kylin | 27        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 6.1.0-13-amd64          | 3         | 11.11%  |
| 5.19.0-32-generic       | 3         | 11.11%  |
| 5.4.18-35-generic       | 2         | 7.41%   |
| 5.4.18-15-generic       | 2         | 7.41%   |
| 5.19.0-45-generic       | 2         | 7.41%   |
| 6.2.0-33-generic        | 1         | 3.7%    |
| 6.2.0-32-generic        | 1         | 3.7%    |
| 6.2.0-23-generic        | 1         | 3.7%    |
| 6.2.0-21-generic        | 1         | 3.7%    |
| 5.4.96-7-kr9a0          | 1         | 3.7%    |
| 5.4.18-27-generic       | 1         | 3.7%    |
| 5.4.0-155-generic       | 1         | 3.7%    |
| 5.19.0-46-generic       | 1         | 3.7%    |
| 5.19.0-41-generic       | 1         | 3.7%    |
| 5.15.0-73-generic       | 1         | 3.7%    |
| 5.15.0-69-generic       | 1         | 3.7%    |
| 5.10.0-23-amd64         | 1         | 3.7%    |
| 5.10.0-20-amd64         | 1         | 3.7%    |
| 5.10.0-0.bpo.9-rt-amd64 | 1         | 3.7%    |
| 4.19.71-14-kr990        | 1         | 3.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19.0  | 7         | 25.93%  |
| 5.4.18  | 5         | 18.52%  |
| 6.2.0   | 4         | 14.81%  |
| 6.1.0   | 3         | 11.11%  |
| 5.10.0  | 3         | 11.11%  |
| 5.15.0  | 2         | 7.41%   |
| 5.4.96  | 1         | 3.7%    |
| 5.4.0   | 1         | 3.7%    |
| 4.19.71 | 1         | 3.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 7         | 25.93%  |
| 5.19    | 7         | 25.93%  |
| 6.2     | 4         | 14.81%  |
| 6.1     | 3         | 11.11%  |
| 5.10    | 3         | 11.11%  |
| 5.15    | 2         | 7.41%   |
| 4.19    | 1         | 3.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 23        | 85.19%  |
| aarch64 | 4         | 14.81%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 14        | 51.85%  |
| UKUI            | 7         | 25.93%  |
| XFCE            | 2         | 7.41%   |
| KDE5            | 2         | 7.41%   |
| X-Cinnamon      | 1         | 3.7%    |
| GNOME Flashback | 1         | 3.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 17        | 62.96%  |
| Wayland | 10        | 37.04%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM3    | 14        | 51.85%  |
| LightDM | 8         | 29.63%  |
| TDM     | 2         | 7.41%   |
| SDDM    | 2         | 7.41%   |
| GDM     | 1         | 3.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| zh_CN | 19        | 70.37%  |
| en_US | 6         | 22.22%  |
| en_HK | 1         | 3.7%    |
| C     | 1         | 3.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 22        | 81.48%  |
| BIOS | 5         | 18.52%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 24        | 88.89%  |
| Tmpfs   | 2         | 7.41%   |
| Overlay | 1         | 3.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 26        | 96.3%   |
| MBR  | 1         | 3.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 22        | 81.48%  |
| Yes       | 5         | 18.52%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 17        | 62.96%  |
| Yes       | 10        | 37.04%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 10        | 37.04%  |
| HUAWEI           | 5         | 18.52%  |
| ASUSTek Computer | 4         | 14.81%  |
| Hewlett-Packard  | 2         | 7.41%   |
| Dell             | 2         | 7.41%   |
| Timi             | 1         | 3.7%    |
| THTF             | 1         | 3.7%    |
| GreatWall        | 1         | 3.7%    |
| Apple            | 1         | 3.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Timi TM1612                                  | 1         | 3.7%    |
| THTF CR F860-T1                              | 1         | 3.7%    |
| Lenovo XiaoXinPro 14ACH 2021 82MS            | 1         | 3.7%    |
| Lenovo ThinkPad X200 74574AC                 | 1         | 3.7%    |
| Lenovo ThinkPad X13 Gen 1 20T2A003CD         | 1         | 3.7%    |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y6S00400 | 1         | 3.7%    |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBA002CD  | 1         | 3.7%    |
| Lenovo ThinkPad T480s 20L7A00HHK             | 1         | 3.7%    |
| Lenovo ThinkBook 16 G5+ ARP 21J0             | 1         | 3.7%    |
| Lenovo Legion Y9000P IAH7H 82RF              | 1         | 3.7%    |
| Lenovo Legion R9000P2021H 82JQ               | 1         | 3.7%    |
| Lenovo IdeaPad 710S-13ISK 80SW               | 1         | 3.7%    |
| HUAWEI QingYun L420 KLVV-W5821               | 1         | 3.7%    |
| HUAWEI MACH-WX9                              | 1         | 3.7%    |
| HUAWEI L410 KLVU-WDU0                        | 1         | 3.7%    |
| HUAWEI KLVDZ-WXX9                            | 1         | 3.7%    |
| HUAWEI CREM-WXX9                             | 1         | 3.7%    |
| HP ZHAN 99 Mobile Workstation G3             | 1         | 3.7%    |
| HP EliteBook 840 G7 Notebook PC              | 1         | 3.7%    |
| Dell Vostro 3350                             | 1         | 3.7%    |
| Dell Inspiron 5468                           | 1         | 3.7%    |
| ASUS VivoBook_ASUSLaptop K5504VA_K5504VA     | 1         | 3.7%    |
| ASUS UX31LA                                  | 1         | 3.7%    |
| ASUS TUF Gaming FX505GT                      | 1         | 3.7%    |
| ASUS ROG Strix G713PV_G713PV                 | 1         | 3.7%    |
| Apple MacBookPro12,1                         | 1         | 3.7%    |
| Unknown                                      | 1         | 3.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 5         | 18.52%  |
| Lenovo Legion      | 2         | 7.41%   |
| Timi TM1612        | 1         | 3.7%    |
| THTF CR            | 1         | 3.7%    |
| Lenovo XiaoXinPro  | 1         | 3.7%    |
| Lenovo ThinkBook   | 1         | 3.7%    |
| Lenovo IdeaPad     | 1         | 3.7%    |
| HUAWEI QingYun     | 1         | 3.7%    |
| HUAWEI MACH-WX9    | 1         | 3.7%    |
| HUAWEI L410        | 1         | 3.7%    |
| HUAWEI KLVDZ-WXX9  | 1         | 3.7%    |
| HUAWEI CREM-WXX9   | 1         | 3.7%    |
| HP ZHAN            | 1         | 3.7%    |
| HP EliteBook       | 1         | 3.7%    |
| Dell Vostro        | 1         | 3.7%    |
| Dell Inspiron      | 1         | 3.7%    |
| ASUS VivoBook      | 1         | 3.7%    |
| ASUS UX31LA        | 1         | 3.7%    |
| ASUS TUF           | 1         | 3.7%    |
| ASUS ROG           | 1         | 3.7%    |
| Apple MacBookPro12 | 1         | 3.7%    |
| Unknown            | 1         | 3.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 8         | 29.63%  |
| 2022    | 4         | 14.81%  |
| 2016    | 3         | 11.11%  |
| 2020    | 2         | 7.41%   |
| 2018    | 2         | 7.41%   |
| 2014    | 2         | 7.41%   |
| 2023    | 1         | 3.7%    |
| 2015    | 1         | 3.7%    |
| 2012    | 1         | 3.7%    |
| 2011    | 1         | 3.7%    |
| 2008    | 1         | 3.7%    |
| Unknown | 1         | 3.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 27        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 23        | 85.19%  |
| Enabled  | 4         | 14.81%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 27        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 9         | 33.33%  |
| 4.01-8.0    | 6         | 22.22%  |
| 3.01-4.0    | 5         | 18.52%  |
| 16.01-24.0  | 5         | 18.52%  |
| 24.01-32.0  | 1         | 3.7%    |
| 64.01-256.0 | 1         | 3.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 3.01-4.0  | 9         | 33.33%  |
| 2.01-3.0  | 6         | 22.22%  |
| 1.01-2.0  | 5         | 18.52%  |
| 4.01-8.0  | 3         | 11.11%  |
| 8.01-16.0 | 3         | 11.11%  |
| 0.51-1.0  | 1         | 3.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 17        | 62.96%  |
| 2      | 7         | 25.93%  |
| 4      | 2         | 7.41%   |
| 3      | 1         | 3.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 25        | 92.59%  |
| Yes       | 2         | 7.41%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 66.67%  |
| No        | 9         | 33.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 88.89%  |
| No        | 3         | 11.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 88.89%  |
| No        | 3         | 11.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| China     | 22        | 81.48%  |
| Hong Kong | 3         | 11.11%  |
| USA       | 1         | 3.7%    |
| Taiwan    | 1         | 3.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City        | Notebooks | Percent |
|-------------|-----------|---------|
| Tianjin     | 3         | 11.11%  |
| Shenzhen    | 2         | 7.41%   |
| Jinrongjie  | 2         | 7.41%   |
| Haidian     | 2         | 7.41%   |
| Central     | 2         | 7.41%   |
| Zhongshan   | 1         | 3.7%    |
| Xiaolou     | 1         | 3.7%    |
| Xi'an       | 1         | 3.7%    |
| Shizishan   | 1         | 3.7%    |
| Shanghai    | 1         | 3.7%    |
| Putuo       | 1         | 3.7%    |
| Mong Kok    | 1         | 3.7%    |
| Los Angeles | 1         | 3.7%    |
| Kunming     | 1         | 3.7%    |
| Jinan       | 1         | 3.7%    |
| Harbin      | 1         | 3.7%    |
| Haikou      | 1         | 3.7%    |
| Changsha    | 1         | 3.7%    |
| Chancheng   | 1         | 3.7%    |
| Beijing     | 1         | 3.7%    |
| Banqiao     | 1         | 3.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 14     | 29.41%  |
| Toshiba             | 3         | 3      | 8.82%   |
| Micron Technology   | 3         | 3      | 8.82%   |
| WDC                 | 2         | 2      | 5.88%   |
| SanDisk             | 2         | 2      | 5.88%   |
| Phison              | 2         | 2      | 5.88%   |
| ZX1 1TB             | 1         | 1      | 2.94%   |
| ZHITAI              | 1         | 1      | 2.94%   |
| Unknown             | 1         | 1      | 2.94%   |
| SK hynix            | 1         | 1      | 2.94%   |
| Seagate             | 1         | 1      | 2.94%   |
| Lenovo              | 1         | 1      | 2.94%   |
| Kingchuxing         | 1         | 1      | 2.94%   |
| Intel               | 1         | 1      | 2.94%   |
| HISI                | 1         | 4      | 2.94%   |
| Hewlett-Packard     | 1         | 1      | 2.94%   |
| Fanxiang            | 1         | 1      | 2.94%   |
| Apple               | 1         | 1      | 2.94%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 2         | 5.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 2         | 5.71%   |
| Micron MTFDKBA512TFH 512GB                          | 2         | 5.71%   |
| ZX1 1TB Disk 1TB                                    | 1         | 2.86%   |
| ZHITAI TiPlus7100 2TB                               | 1         | 2.86%   |
| WDC PC SN730 SDBPNTY-512G                           | 1         | 2.86%   |
| WDC PC SN530 SDBPNPZ-512G-1014 512GB                | 1         | 2.86%   |
| Unknown NVMe SSD Drive 256GB                        | 1         | 2.86%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 2.86%   |
| Toshiba MK3261GSYN 320GB                            | 1         | 2.86%   |
| Toshiba KXG60ZNV512G KIOXIA 512GB                   | 1         | 2.86%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB              | 1         | 2.86%   |
| Seagate ST9500325AS 500GB                           | 1         | 2.86%   |
| SanDisk SD6SP1M256G1102 256GB SSD                   | 1         | 2.86%   |
| SanDisk NVMe SSD Drive 1TB                          | 1         | 2.86%   |
| Samsung MZVLW256HEHP-000L2 256GB                    | 1         | 2.86%   |
| Samsung MZVLB512HBJQ-000L7 512GB                    | 1         | 2.86%   |
| Samsung MZVLB512HAJQ-00000 512GB                    | 1         | 2.86%   |
| Samsung MZVL2512HCJQ-00BL7 512GB                    | 1         | 2.86%   |
| Samsung MZNTY128HDHP-00000 128GB SSD                | 1         | 2.86%   |
| Samsung KLUFG8RHDA-B2D1 512GB                       | 1         | 2.86%   |
| Samsung KLUFG8RHDA-B2D1 1GB                         | 1         | 2.86%   |
| Phison ThinkPlus ST8000 PCI-E M.2 256G              | 1         | 2.86%   |
| Phison 511BS0512HB 512GB                            | 1         | 2.86%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                       | 1         | 2.86%   |
| Lenovo SSD SL500 240G                               | 1         | 2.86%   |
| Kingchuxing SSD 128GB                               | 1         | 2.86%   |
| Intel SSDPEKNW512G8 512GB                           | 1         | 2.86%   |
| HISI THR920GFCV100HAE 256GB                         | 1         | 2.86%   |
| HP SSD EX950 1TB                                    | 1         | 2.86%   |
| Fanxiang S690 2TB                                   | 1         | 2.86%   |
| Apple SSD SM0256G 256GB                             | 1         | 2.86%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 66.67%  |
| Seagate | 1         | 1      | 33.33%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 5      | 28.57%  |
| SanDisk             | 1         | 1      | 14.29%  |
| Lenovo              | 1         | 1      | 14.29%  |
| Kingchuxing         | 1         | 1      | 14.29%  |
| HISI                | 1         | 4      | 14.29%  |
| Apple               | 1         | 1      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 19        | 24     | 63.33%  |
| SSD     | 7         | 13     | 23.33%  |
| HDD     | 3         | 3      | 10%     |
| Unknown | 1         | 1      | 3.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 19        | 23     | 61.29%  |
| SATA | 10        | 16     | 32.26%  |
| SAS  | 2         | 2      | 6.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 9         | 14     | 81.82%  |
| 0.51-1.0   | 2         | 2      | 18.18%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 11        | 40.74%  |
| 51-100     | 5         | 18.52%  |
| 101-250    | 4         | 14.81%  |
| 501-1000   | 4         | 14.81%  |
| 1001-2000  | 2         | 7.41%   |
| 2001-3000  | 1         | 3.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 21-50    | 6         | 22.22%  |
| 1-20     | 6         | 22.22%  |
| 51-100   | 6         | 22.22%  |
| 101-250  | 4         | 14.81%  |
| 251-500  | 3         | 11.11%  |
| 501-1000 | 2         | 7.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                     | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB | 1         | 1      | 100%    |

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
| Works    | 20        | 23     | 68.97%  |
| Detected | 8         | 17     | 27.59%  |
| Malfunc  | 1         | 1      | 3.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Samsung Electronics             | 9         | 27.27%  |
| Intel                           | 8         | 24.24%  |
| SanDisk                         | 3         | 9.09%   |
| Micron Technology               | 3         | 9.09%   |
| AMD                             | 3         | 9.09%   |
| Phison Electronics              | 2         | 6.06%   |
| Yangtze Memory Technologies     | 1         | 3.03%   |
| Toshiba America Info Systems    | 1         | 3.03%   |
| SK hynix                        | 1         | 3.03%   |
| Silicon Motion                  | 1         | 3.03%   |
| Hefei DATANG Storage Technology | 1         | 3.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 4         | 11.43%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 3         | 8.57%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 3         | 8.57%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 3         | 8.57%   |
| Micron 3400 NVMe SSD [Hendrix]                                               | 2         | 5.71%   |
| Yangtze Memory ZHITAI TiPlus7100                                             | 1         | 2.86%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 1         | 2.86%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 1         | 2.86%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                | 1         | 2.86%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD      | 1         | 2.86%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                    | 1         | 2.86%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD         | 1         | 2.86%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                   | 1         | 2.86%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 2.86%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                          | 1         | 2.86%   |
| Phison E12 NVMe Controller                                                   | 1         | 2.86%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                  | 1         | 2.86%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation        | 1         | 2.86%   |
| Intel SSD 660P Series                                                        | 1         | 2.86%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                             | 1         | 2.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 2.86%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 1         | 2.86%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 1         | 2.86%   |
| Hefei DATANG Storage NVMe SSD Controller 300A                                | 1         | 2.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 19        | 59.38%  |
| SATA | 11        | 34.38%  |
| RAID | 1         | 3.13%   |
| IDE  | 1         | 3.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 17        | 62.96%  |
| AMD     | 6         | 22.22%  |
| Phytium | 2         | 7.41%   |
| ARM     | 2         | 7.41%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen 7 5800H with Radeon Graphics  | 3         | 11.11%  |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 7.41%   |
| ARM Processor                           | 2         | 7.41%   |
| Phytium FT-2000/4                       | 1         | 3.7%    |
| Phytium D2000/8 E8C                     | 1         | 3.7%    |
| Intel Core m3-6Y30 CPU @ 0.90GHz        | 1         | 3.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 3.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 3.7%    |
| Intel Core i7-7500U CPU @ 2.70GHz       | 1         | 3.7%    |
| Intel Core i7-6560U CPU @ 2.20GHz       | 1         | 3.7%    |
| Intel Core i5-8350U CPU @ 1.70GHz       | 1         | 3.7%    |
| Intel Core i5-5257U CPU @ 2.70GHz       | 1         | 3.7%    |
| Intel Core i5-4200U CPU @ 1.60GHz       | 1         | 3.7%    |
| Intel Core i3-2310M CPU @ 2.10GHz       | 1         | 3.7%    |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz    | 1         | 3.7%    |
| Intel 13th Gen Core i9-13900H           | 1         | 3.7%    |
| Intel 12th Gen Core i7-12700H           | 1         | 3.7%    |
| Intel 12th Gen Core i5-1240P            | 1         | 3.7%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 1         | 3.7%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 1         | 3.7%    |
| AMD Ryzen 9 7845HX with Radeon Graphics | 1         | 3.7%    |
| AMD Ryzen 7 7735H with Radeon Graphics  | 1         | 3.7%    |
| AMD Ryzen 5 5600H with Radeon Graphics  | 1         | 3.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Other            | 9         | 33.33%  |
| Intel Core i5    | 5         | 18.52%  |
| Intel Core i7    | 4         | 14.81%  |
| AMD Ryzen 7      | 4         | 14.81%  |
| Intel Core m3    | 1         | 3.7%    |
| Intel Core i3    | 1         | 3.7%    |
| Intel Core 2 Duo | 1         | 3.7%    |
| AMD Ryzen 9      | 1         | 3.7%    |
| AMD Ryzen 5      | 1         | 3.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 7         | 25.93%  |
| 8      | 6         | 22.22%  |
| 4      | 6         | 22.22%  |
| 6      | 4         | 14.81%  |
| 14     | 2         | 7.41%   |
| 12     | 2         | 7.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 25        | 92.59%  |
| 3      | 2         | 7.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 21        | 77.78%  |
| 1      | 6         | 22.22%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 27        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 10        | 37.04%  |
| 0x806ec    | 2         | 7.41%   |
| 0x406e3    | 2         | 7.41%   |
| 0x906ea    | 1         | 3.7%    |
| 0x906a3    | 1         | 3.7%    |
| 0x806ea    | 1         | 3.7%    |
| 0x806e9    | 1         | 3.7%    |
| 0x806c1    | 1         | 3.7%    |
| 0x40651    | 1         | 3.7%    |
| 0x306d4    | 1         | 3.7%    |
| 0x1067a    | 1         | 3.7%    |
| 0x0a601203 | 1         | 3.7%    |
| 0x0a50000d | 1         | 3.7%    |
| 0x0a50000c | 1         | 3.7%    |
| 0x0a50000b | 1         | 3.7%    |
| 0x0a404102 | 1         | 3.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 8         | 29.63%  |
| KabyLake         | 6         | 22.22%  |
| Zen 3            | 4         | 14.81%  |
| Skylake          | 2         | 7.41%   |
| Alderlake Hybrid | 2         | 7.41%   |
| TigerLake        | 1         | 3.7%    |
| SandyBridge      | 1         | 3.7%    |
| Penryn           | 1         | 3.7%    |
| Haswell          | 1         | 3.7%    |
| Broadwell        | 1         | 3.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 17        | 51.52%  |
| AMD    | 9         | 27.27%  |
| Nvidia | 7         | 21.21%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 4         | 12.12%  |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 3         | 9.09%   |
| Intel UHD Graphics 620                                                                | 2         | 6.06%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 6.06%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 2         | 6.06%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                  | 2         | 6.06%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 3.03%   |
| Nvidia TU117GLM [T600 Mobile]                                                         | 1         | 3.03%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 3.03%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                       | 1         | 3.03%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 1         | 3.03%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 1         | 3.03%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 1         | 3.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 3.03%   |
| Intel Iris Graphics 6100                                                              | 1         | 3.03%   |
| Intel Iris Graphics 540                                                               | 1         | 3.03%   |
| Intel HD Graphics 620                                                                 | 1         | 3.03%   |
| Intel HD Graphics 515                                                                 | 1         | 3.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 1         | 3.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 1         | 3.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 1         | 3.03%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 3.03%   |
| AMD Rembrandt [Radeon 680M]                                                           | 1         | 3.03%   |
| AMD Raphael                                                                           | 1         | 3.03%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 12        | 44.44%  |
| 1 x AMD        | 5         | 18.52%  |
| Intel + Nvidia | 4         | 14.81%  |
| AMD + Nvidia   | 3         | 11.11%  |
| Other          | 2         | 7.41%   |
| Intel + AMD    | 1         | 3.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 21        | 77.78%  |
| Proprietary | 4         | 14.81%  |
| Unknown     | 2         | 7.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 66.67%  |
| 1.01-2.0   | 5         | 18.52%  |
| 3.01-4.0   | 2         | 7.41%   |
| 0.01-0.5   | 2         | 7.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 8         | 25.81%  |
| CSO                 | 4         | 12.9%   |
| LG Display          | 3         | 9.68%   |
| Chimei Innolux      | 3         | 9.68%   |
| Lenovo              | 2         | 6.45%   |
| AOC                 | 2         | 6.45%   |
| Xiaomi              | 1         | 3.23%   |
| Samsung Electronics | 1         | 3.23%   |
| PANDA               | 1         | 3.23%   |
| KIG                 | 1         | 3.23%   |
| JDI                 | 1         | 3.23%   |
| Dell                | 1         | 3.23%   |
| CPT                 | 1         | 3.23%   |
| AU Optronics        | 1         | 3.23%   |
| Apple               | 1         | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Xiaomi Mi TV XMD004A 1440x900 708x398mm 32.0-inch                     | 1         | 3.23%   |
| Samsung Electronics LCD Monitor SDC4180 2880x1620 344x194mm 15.5-inch | 1         | 3.23%   |
| PANDA LCD Monitor NCP0042 1920x1080 344x194mm 15.5-inch               | 1         | 3.23%   |
| LG Display LCD Monitor LGD06AA 3840x2400 344x215mm 16.0-inch          | 1         | 3.23%   |
| LG Display LCD Monitor LGD060A 1920x1080 294x165mm 13.3-inch          | 1         | 3.23%   |
| LG Display LCD Monitor LGD04EF 1920x1080 294x165mm 13.3-inch          | 1         | 3.23%   |
| Lenovo X24i-10 LEN61AA 1920x1080 527x296mm 23.8-inch                  | 1         | 3.23%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch               | 1         | 3.23%   |
| KIG KKTV KIG2700 1920x1080 598x336mm 27.0-inch                        | 1         | 3.23%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 1         | 3.23%   |
| Dell P2717H DEL40F7 1920x1080 598x336mm 27.0-inch                     | 1         | 3.23%   |
| CSO MNH301CA3-1 CSO1702 2560x1440 381x214mm 17.2-inch                 | 1         | 3.23%   |
| CSO LCD Monitor CSO1612 2560x1600 345x215mm 16.0-inch                 | 1         | 3.23%   |
| CSO LCD Monitor CSO1609 2560x1600 345x215mm 16.0-inch                 | 1         | 3.23%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                 | 1         | 3.23%   |
| CPT LCD Monitor CPT17DB 1600x900 293x164mm 13.2-inch                  | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN153A 1920x1080 344x193mm 15.5-inch      | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch      | 1         | 3.23%   |
| BOE LCD Monitor BOE0AC9 2240x1400 302x189mm 14.0-inch                 | 1         | 3.23%   |
| BOE LCD Monitor BOE0AC1 2560x1600 344x215mm 16.0-inch                 | 1         | 3.23%   |
| BOE LCD Monitor BOE092F 2520x1680 338x226mm 16.0-inch                 | 1         | 3.23%   |
| BOE LCD Monitor BOE08DA 1920x1080 309x174mm 14.0-inch                 | 1         | 3.23%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 1         | 3.23%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                 | 1         | 3.23%   |
| BOE LCD Monitor BOE06B6 1366x768 309x173mm 13.9-inch                  | 1         | 3.23%   |
| BOE LCD Monitor BOE0691 1920x1080 280x165mm 12.8-inch                 | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch         | 1         | 3.23%   |
| Apple Color LCD APPA02A 2560x1600 286x179mm 13.3-inch                 | 1         | 3.23%   |
| AOC 27B3HM AOC2703 1920x1080 598x336mm 27.0-inch                      | 1         | 3.23%   |
| AOC 23E1WX AOC2301 1920x1080 488x297mm 22.5-inch                      | 1         | 3.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 11        | 37.93%  |
| 2560x1600       | 4         | 13.79%  |
| 3840x2160 (4K)  | 2         | 6.9%    |
| 1366x768 (WXGA) | 2         | 6.9%    |
| 3840x2400       | 1         | 3.45%   |
| 3000x2000       | 1         | 3.45%   |
| 2880x1800       | 1         | 3.45%   |
| 2880x1620       | 1         | 3.45%   |
| 2560x1440 (QHD) | 1         | 3.45%   |
| 2520x1680       | 1         | 3.45%   |
| 2240x1400       | 1         | 3.45%   |
| 2160x1440       | 1         | 3.45%   |
| 1600x900 (HD+)  | 1         | 3.45%   |
| 1280x800 (WXGA) | 1         | 3.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 9         | 29.03%  |
| 16     | 5         | 16.13%  |
| 14     | 5         | 16.13%  |
| 27     | 3         | 9.68%   |
| 15     | 3         | 9.68%   |
| 12     | 2         | 6.45%   |
| 65     | 1         | 3.23%   |
| 23     | 1         | 3.23%   |
| 22     | 1         | 3.23%   |
| 17     | 1         | 3.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 15        | 48.39%  |
| 201-300     | 9         | 29.03%  |
| 501-600     | 4         | 12.9%   |
| 401-500     | 1         | 3.23%   |
| 351-400     | 1         | 3.23%   |
| 1001-1500   | 1         | 3.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 16        | 59.26%  |
| 16/10 | 8         | 29.63%  |
| 3/2   | 3         | 11.11%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 10        | 32.26%  |
| 71-80          | 5         | 16.13%  |
| 111-120        | 5         | 16.13%  |
| 301-350        | 3         | 9.68%   |
| 101-110        | 3         | 9.68%   |
| 201-250        | 2         | 6.45%   |
| More than 1000 | 1         | 3.23%   |
| 61-70          | 1         | 3.23%   |
| 121-130        | 1         | 3.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 161-240       | 12        | 40%     |
| 121-160       | 8         | 26.67%  |
| 51-100        | 4         | 13.33%  |
| More than 240 | 3         | 10%     |
| 101-120       | 2         | 6.67%   |
| 1-50          | 1         | 3.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 19        | 70.37%  |
| 2     | 6         | 22.22%  |
| 0     | 2         | 7.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 17        | 41.46%  |
| Intel                      | 15        | 36.59%  |
| MediaTek                   | 3         | 7.32%   |
| Huawei Technologies        | 2         | 4.88%   |
| Quectel Wireless Solutions | 1         | 2.44%   |
| ICS Advent                 | 1         | 2.44%   |
| Broadcom                   | 1         | 2.44%   |
| ASIX Electronics           | 1         | 2.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 23.4%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 4.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 4.26%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 4.26%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 4.26%   |
| Intel Wireless 8265 / 8275                                        | 2         | 4.26%   |
| Intel Wireless 8260                                               | 2         | 4.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 4.26%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 4.26%   |
| Huawei Network controller                                         | 2         | 4.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 2.13%   |
| Quectel Wireless Solutions Quectel EM05-CE                        | 1         | 2.13%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1         | 2.13%   |
| Intel Wireless 7260                                               | 1         | 2.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 2.13%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 2.13%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 1         | 2.13%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 2.13%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.13%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 2.13%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 1         | 2.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 2.13%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.13%   |
| ICS Advent 10/100M LAN                                            | 1         | 2.13%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 2.13%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2.13%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 15        | 60%     |
| Realtek Semiconductor      | 5         | 20%     |
| MediaTek                   | 3         | 12%     |
| Quectel Wireless Solutions | 1         | 4%      |
| Broadcom                   | 1         | 4%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 2         | 8%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 8%      |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 8%      |
| Intel Wireless 8265 / 8275                                    | 2         | 8%      |
| Intel Wireless 8260                                           | 2         | 8%      |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 8%      |
| Intel Alder Lake-P PCH CNVi WiFi                              | 2         | 8%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 4%      |
| Quectel Wireless Solutions Quectel EM05-CE                    | 1         | 4%      |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 1         | 4%      |
| Intel Wireless 7260                                           | 1         | 4%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 1         | 4%      |
| Intel Wi-Fi 6 AX201                                           | 1         | 4%      |
| Intel Raptor Lake PCH CNVi WiFi                               | 1         | 4%      |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection       | 1         | 4%      |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                 | 1         | 4%      |
| Intel Cannon Lake PCH CNVi WiFi                               | 1         | 4%      |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 1         | 4%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 15        | 75%     |
| Intel                 | 3         | 15%     |
| ICS Advent            | 1         | 5%      |
| ASIX Electronics      | 1         | 5%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 55%     |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 10%     |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 5%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 5%      |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 5%      |
| Intel Ethernet Connection (10) I219-V                             | 1         | 5%      |
| Intel 82567LM Gigabit Network Connection                          | 1         | 5%      |
| ICS Advent 10/100M LAN                                            | 1         | 5%      |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 5%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 24        | 54.55%  |
| Ethernet | 18        | 40.91%  |
| Unknown  | 2         | 4.55%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 22        | 78.57%  |
| Ethernet | 6         | 21.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 14        | 51.85%  |
| 1     | 13        | 48.15%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 22        | 81.48%  |
| Yes  | 5         | 18.52%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 58.33%  |
| Foxconn / Hon Hai               | 3         | 12.5%   |
| Realtek Semiconductor           | 2         | 8.33%   |
| Realtek                         | 1         | 4.17%   |
| Qualcomm Atheros Communications | 1         | 4.17%   |
| IMC Networks                    | 1         | 4.17%   |
| Broadcom                        | 1         | 4.17%   |
| Apple                           | 1         | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 5         | 20.83%  |
| Intel Bluetooth Device                             | 3         | 12.5%   |
| Intel AX201 Bluetooth                              | 3         | 12.5%   |
| Realtek Bluetooth Radio                            | 2         | 8.33%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter       | 2         | 8.33%   |
| Realtek 802.11ac WLAN Adapter                      | 1         | 4.17%   |
| Qualcomm Atheros  Bluetooth Device                 | 1         | 4.17%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter   | 1         | 4.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 1         | 4.17%   |
| Intel AX210 Bluetooth                              | 1         | 4.17%   |
| IMC Networks Bluetooth Radio                       | 1         | 4.17%   |
| Foxconn / Hon Hai Wireless_Device                  | 1         | 4.17%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 4.17%   |
| Apple Bluetooth Host Controller                    | 1         | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 17        | 54.84%  |
| AMD    | 8         | 25.81%  |
| Nvidia | 6         | 19.35%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 6         | 16.67%  |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 13.89%  |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 8.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 5.56%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 5.56%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 5.56%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 5.56%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2         | 5.56%   |
| Nvidia Audio device                                                        | 1         | 2.78%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 2.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 2.78%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 2.78%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 1         | 2.78%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.78%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 2.78%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 2.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 2.78%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.78%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1         | 2.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 7         | 29.17%  |
| Samsung Electronics | 6         | 25%     |
| Micron Technology   | 6         | 25%     |
| Elpida              | 2         | 8.33%   |
| UNILC               | 1         | 4.17%   |
| Nanya Technology    | 1         | 4.17%   |
| A-DATA Technology   | 1         | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| UNILC RAM 6478545886 8192MB SODIMM DDR4 2400MT/s                 | 1         | 4%      |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s                     | 1         | 4%      |
| SK hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                | 1         | 4%      |
| SK hynix RAM HMAA1GS6DMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 4%      |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 4%      |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 4%      |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 4%      |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 4%      |
| SK hynix RAM H9HKNNNFBMBUDR 8192MB Row Of Chips LPDDR4 4266MT/s  | 1         | 4%      |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 1         | 4%      |
| Samsung RAM Module 2048MB SODIMM LPDDR3 1867MT/s                 | 1         | 4%      |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 4%      |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 4%      |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 4%      |
| Samsung RAM K3UH7H70AM 8192MB Row Of Chips LPDDR4 4266MT/s       | 1         | 4%      |
| Nanya RAM M2N2G64CB8HA5N-BE 2GB SODIMM 1066MT/s                  | 1         | 4%      |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 1         | 4%      |
| Micron RAM MT62F2G32D8DR-031 WT 8GB Row Of Chips LPDDR5 6400MT/s | 1         | 4%      |
| Micron RAM MT62F1G32D4DR-031 2GB Row Of Chips LPDDR5 6400MT/s    | 1         | 4%      |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 4%      |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 4%      |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 4%      |
| Elpida RAM Module 2048MB SODIMM DDR3 1600MT/s                    | 1         | 4%      |
| Elpida RAM EBJ21UE8BDS0-AE-F 2048MB SODIMM DDR3 1067MT/s         | 1         | 4%      |
| A-DATA RAM Module 8GB SODIMM DDR4 2667MT/s                       | 1         | 4%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 10        | 41.67%  |
| LPDDR5  | 3         | 12.5%   |
| LPDDR4  | 3         | 12.5%   |
| LPDDR3  | 3         | 12.5%   |
| DDR3    | 3         | 12.5%   |
| DDR5    | 1         | 4.17%   |
| Unknown | 1         | 4.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 13        | 59.09%  |
| Row Of Chips | 9         | 40.91%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 8192 | 16        | 72.73%  |
| 4096 | 3         | 13.64%  |
| 2048 | 3         | 13.64%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 5         | 21.74%  |
| 2667  | 4         | 17.39%  |
| 6400  | 3         | 13.04%  |
| 1867  | 3         | 13.04%  |
| 4266  | 2         | 8.7%    |
| 4800  | 1         | 4.35%   |
| 2400  | 1         | 4.35%   |
| 2133  | 1         | 4.35%   |
| 1600  | 1         | 4.35%   |
| 1067  | 1         | 4.35%   |
| 1066  | 1         | 4.35%   |

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
| IMC Networks                           | 6         | 24%     |
| Chicony Electronics                    | 6         | 24%     |
| Unknown (0000066029)                   | 2         | 8%      |
| Microdia                               | 2         | 8%      |
| Syntek                                 | 1         | 4%      |
| Sonix Technology                       | 1         | 4%      |
| ShineTech                              | 1         | 4%      |
| Realtek Semiconductor                  | 1         | 4%      |
| Quanta                                 | 1         | 4%      |
| Luxvisions Innotech Limited            | 1         | 4%      |
| Lenovo                                 | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) | 1         | 4%      |
| BL012030059711690428                   | 1         | 4%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                      | 3         | 12%     |
| Unknown (0000066029) HD Camera                      | 2         | 8%      |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 8%      |
| Syntek Integrated Camera                            | 1         | 4%      |
| Sonix USB2.0 FHD UVC WebCam                         | 1         | 4%      |
| ShineTech HD Camera                                 | 1         | 4%      |
| Realtek Integrated_Webcam_HD                        | 1         | 4%      |
| Quanta ov9734_techfront_camera                      | 1         | 4%      |
| Microdia USB2.0 Camera                              | 1         | 4%      |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 4%      |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 4%      |
| Lenovo Integrated Webcam                            | 1         | 4%      |
| IMC Networks Integrated RGB Camera                  | 1         | 4%      |
| Chicony XiaoMi USB 2.0 Webcam                       | 1         | 4%      |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 4%      |
| Chicony Integrated Camera (1280x720@30)             | 1         | 4%      |
| Chicony Integrated Camera                           | 1         | 4%      |
| Chicony HP HD Camera                                | 1         | 4%      |
| Chicony EasyCamera                                  | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 1         | 4%      |
| BL012030059711690428 Integrated Camera              | 1         | 4%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 4         | 50%     |
| Shenzhen Goodix Technology | 2         | 25%     |
| Validity Sensors           | 1         | 12.5%   |
| AuthenTec                  | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                       | 2         | 25%     |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 12.5%   |
| Synaptics UWP WBDI Device                                 | 1         | 12.5%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 12.5%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 12.5%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 12.5%   |
| AuthenTec AES2810                                         | 1         | 12.5%   |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 15        | 55.56%  |
| 1     | 10        | 37.04%  |
| 2     | 2         | 7.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 8         | 57.14%  |
| Graphics card         | 3         | 21.43%  |
| Multimedia controller | 2         | 14.29%  |
| Camera                | 1         | 7.14%   |

