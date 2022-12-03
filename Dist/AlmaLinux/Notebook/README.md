AlmaLinux - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for AlmaLinux.

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

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo  | B50-30 20382                | [3706f368de](https://linux-hardware.org/?probe=3706f368de) | Nov 24, 2022 |
| Lenovo  | Legion Y530-15ICH 81FV      | [832ebcb956](https://linux-hardware.org/?probe=832ebcb956) | Nov 03, 2022 |
| Toshiba | Satellite L50-C             | [b3e0ff9849](https://linux-hardware.org/?probe=b3e0ff9849) | Nov 01, 2022 |
| Acer    | TMP453-MG                   | [4d36d13ea9](https://linux-hardware.org/?probe=4d36d13ea9) | Oct 01, 2022 |
| Acer    | TravelMate 5735Z            | [b920fce554](https://linux-hardware.org/?probe=b920fce554) | Sep 17, 2022 |
| HP      | Falco                       | [5fa86b77d6](https://linux-hardware.org/?probe=5fa86b77d6) | Sep 17, 2022 |
| HP      | Laptop 15-ef1xxx            | [c01403937e](https://linux-hardware.org/?probe=c01403937e) | Sep 08, 2022 |
| HP      | ENVY dv6                    | [e7bc07047b](https://linux-hardware.org/?probe=e7bc07047b) | Aug 24, 2022 |
| HP      | Laptop 17-cp0xxx            | [82b34535ae](https://linux-hardware.org/?probe=82b34535ae) | Jul 06, 2022 |
| HP      | EliteBook 8470p             | [d6adb170de](https://linux-hardware.org/?probe=d6adb170de) | Jun 25, 2022 |
| Google  | Kohaku                      | [f43841c5e0](https://linux-hardware.org/?probe=f43841c5e0) | Jun 08, 2022 |
| Google  | Kohaku                      | [740a608274](https://linux-hardware.org/?probe=740a608274) | Jun 08, 2022 |
| Lenovo  | ThinkPad T440s 20ARS32P0... | [100b65a86d](https://linux-hardware.org/?probe=100b65a86d) | Jun 04, 2022 |
| Lenovo  | ThinkBook 13s-IWL 20R9      | [2fecc1fd76](https://linux-hardware.org/?probe=2fecc1fd76) | Apr 20, 2022 |
| Lenovo  | ThinkPad T14 Gen 1 20S1S... | [5ac68bc542](https://linux-hardware.org/?probe=5ac68bc542) | Mar 16, 2022 |
| Intel   | powered classmate PC        | [0585f5b715](https://linux-hardware.org/?probe=0585f5b715) | Dec 12, 2021 |
| Intel   | powered classmate PC        | [9416f348e4](https://linux-hardware.org/?probe=9416f348e4) | Dec 12, 2021 |
| Dell    | Inspiron 3185               | [53ac57fbea](https://linux-hardware.org/?probe=53ac57fbea) | Oct 26, 2021 |
| Dell    | Inspiron 3185               | [2c9cec7881](https://linux-hardware.org/?probe=2c9cec7881) | Oct 01, 2021 |
| Lenovo  | Yoga 2 13 20344             | [1a59499d3a](https://linux-hardware.org/?probe=1a59499d3a) | Sep 29, 2021 |
| Lenovo  | IdeaPad S145-15IWL 81MV     | [95a2b3a95d](https://linux-hardware.org/?probe=95a2b3a95d) | Aug 27, 2021 |
| HP      | EliteBook 8570w             | [37e72494a5](https://linux-hardware.org/?probe=37e72494a5) | Jul 29, 2021 |
| ASUSTek | ASUS EXPERTBOOK B9450FA_... | [cdf0f4017c](https://linux-hardware.org/?probe=cdf0f4017c) | Jul 16, 2021 |
| Lenovo  | IdeaPad Slim 1-14AST-05 ... | [9044b57593](https://linux-hardware.org/?probe=9044b57593) | Jul 11, 2021 |
| Lenovo  | Legion 5 15IMH05H 81Y6      | [21a6135eda](https://linux-hardware.org/?probe=21a6135eda) | Jun 16, 2021 |
| Dell    | Inspiron 3185               | [84fa76eb2f](https://linux-hardware.org/?probe=84fa76eb2f) | Apr 20, 2021 |
| Dell    | Inspiron 3185               | [d49edb76fa](https://linux-hardware.org/?probe=d49edb76fa) | Apr 15, 2021 |
| Dell    | Inspiron 3185               | [15b8da5bc1](https://linux-hardware.org/?probe=15b8da5bc1) | Apr 14, 2021 |
| Lenovo  | IdeaPad Slim 1-14AST-05 ... | [f0791eb42d](https://linux-hardware.org/?probe=f0791eb42d) | Mar 30, 2021 |
| Lenovo  | IdeaPad 330-15ARR 81D2      | [8810309035](https://linux-hardware.org/?probe=8810309035) | Mar 24, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| AlmaLinux 9.0 | 6         | 27.27%  |
| AlmaLinux 8.6 | 5         | 22.73%  |
| AlmaLinux 8.4 | 5         | 22.73%  |
| AlmaLinux 8.3 | 3         | 13.64%  |
| AlmaLinux 8.5 | 2         | 9.09%   |
| AlmaLinux 9.1 | 1         | 4.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| AlmaLinux | 22        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.14.0-70.22.1.el9_0.x86_64  | 2         | 9.09%   |
| 5.14.0-70.13.1.el9_0.x86_64  | 2         | 9.09%   |
| 4.18.0-372.26.1.el8_6.x86_64 | 2         | 9.09%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 2         | 9.09%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 2         | 9.09%   |
| 5.4.175-1.el8.elrepo.x86_64  | 1         | 4.55%   |
| 5.14.0-70.26.1.el9_0.x86_64  | 1         | 4.55%   |
| 5.14.0-70.17.1.el9_0.x86_64  | 1         | 4.55%   |
| 5.14.0-162.6.1.el9_1.x86_64  | 1         | 4.55%   |
| 4.18.0-372.9.1.el8.x86_64    | 1         | 4.55%   |
| 4.18.0-372.19.1.el8_6.x86_64 | 1         | 4.55%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 1         | 4.55%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 1         | 4.55%   |
| 4.18.0-305.el8.x86_64        | 1         | 4.55%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 1         | 4.55%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 1         | 4.55%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 1         | 4.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.0  | 14        | 63.64%  |
| 5.14.0  | 7         | 31.82%  |
| 5.4.175 | 1         | 4.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 14        | 63.64%  |
| 5.14    | 7         | 31.82%  |
| 5.4     | 1         | 4.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 22        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 16        | 72.73%  |
| MATE          | 2         | 9.09%   |
| KDE5          | 2         | 9.09%   |
| XFCE          | 1         | 4.55%   |
| GNOME Classic | 1         | 4.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 13        | 59.09%  |
| X11     | 9         | 40.91%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 10        | 45.45%  |
| GDM     | 8         | 36.36%  |
| SDDM    | 2         | 9.09%   |
| LightDM | 2         | 9.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 13        | 59.09%  |
| de_DE | 4         | 18.18%  |
| fr_FR | 2         | 9.09%   |
| es_VE | 1         | 4.55%   |
| es_ES | 1         | 4.55%   |
| C     | 1         | 4.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 15        | 68.18%  |
| BIOS | 7         | 31.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 17        | 77.27%  |
| Ext4 | 5         | 22.73%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 11        | 50%     |
| Unknown | 9         | 40.91%  |
| MBR     | 2         | 9.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 18        | 81.82%  |
| Yes       | 4         | 18.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 18        | 81.82%  |
| Yes       | 4         | 18.18%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 9         | 40.91%  |
| Hewlett-Packard  | 6         | 27.27%  |
| Acer             | 2         | 9.09%   |
| Toshiba          | 1         | 4.55%   |
| Intel            | 1         | 4.55%   |
| Google           | 1         | 4.55%   |
| Dell             | 1         | 4.55%   |
| ASUSTek Computer | 1         | 4.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba Satellite L50-C              | 1         | 4.55%   |
| Lenovo Yoga 2 13 20344               | 1         | 4.55%   |
| Lenovo ThinkPad T440s 20ARS32P00     | 1         | 4.55%   |
| Lenovo ThinkPad T14 Gen 1 20S1S39Q00 | 1         | 4.55%   |
| Lenovo Legion Y530-15ICH 81FV        | 1         | 4.55%   |
| Lenovo Legion 5 15IMH05H 81Y6        | 1         | 4.55%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS  | 1         | 4.55%   |
| Lenovo IdeaPad S145-15IWL 81MV       | 1         | 4.55%   |
| Lenovo IdeaPad 330-15ARR 81D2        | 1         | 4.55%   |
| Lenovo B50-30 20382                  | 1         | 4.55%   |
| Intel powered classmate PC           | 1         | 4.55%   |
| HP Laptop 17-cp0xxx                  | 1         | 4.55%   |
| HP Laptop 15-ef1xxx                  | 1         | 4.55%   |
| HP Falco                             | 1         | 4.55%   |
| HP ENVY dv6                          | 1         | 4.55%   |
| HP EliteBook 8570w                   | 1         | 4.55%   |
| HP EliteBook 8470p                   | 1         | 4.55%   |
| Google Kohaku                        | 1         | 4.55%   |
| Dell Inspiron 3185                   | 1         | 4.55%   |
| ASUS ASUS EXPERTBOOK B9450FA_B9450FA | 1         | 4.55%   |
| Acer TravelMate 5735Z                | 1         | 4.55%   |
| Acer TMP453-MG                       | 1         | 4.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo IdeaPad    | 3         | 13.64%  |
| Lenovo ThinkPad   | 2         | 9.09%   |
| Lenovo Legion     | 2         | 9.09%   |
| HP Laptop         | 2         | 9.09%   |
| HP EliteBook      | 2         | 9.09%   |
| Toshiba Satellite | 1         | 4.55%   |
| Lenovo Yoga       | 1         | 4.55%   |
| Lenovo B50-30     | 1         | 4.55%   |
| Intel powered     | 1         | 4.55%   |
| HP Falco          | 1         | 4.55%   |
| HP ENVY           | 1         | 4.55%   |
| Google Kohaku     | 1         | 4.55%   |
| Dell Inspiron     | 1         | 4.55%   |
| ASUS ASUS         | 1         | 4.55%   |
| Acer TravelMate   | 1         | 4.55%   |
| Acer TMP453-MG    | 1         | 4.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 3         | 13.64%  |
| 2019 | 3         | 13.64%  |
| 2018 | 3         | 13.64%  |
| 2014 | 3         | 13.64%  |
| 2012 | 3         | 13.64%  |
| 2011 | 2         | 9.09%   |
| 2022 | 1         | 4.55%   |
| 2021 | 1         | 4.55%   |
| 2015 | 1         | 4.55%   |
| 2013 | 1         | 4.55%   |
| 2010 | 1         | 4.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 22        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 18        | 81.82%  |
| Enabled  | 4         | 18.18%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 20        | 90.91%  |
| Yes  | 2         | 9.09%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 9         | 40.91%  |
| 3.01-4.0   | 4         | 18.18%  |
| 16.01-24.0 | 4         | 18.18%  |
| 8.01-16.0  | 3         | 13.64%  |
| 1.01-2.0   | 2         | 9.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 7         | 30.43%  |
| 1.01-2.0 | 7         | 30.43%  |
| 4.01-8.0 | 4         | 17.39%  |
| 3.01-4.0 | 3         | 13.04%  |
| 0.51-1.0 | 2         | 8.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 12        | 54.55%  |
| 2      | 8         | 36.36%  |
| 3      | 1         | 4.55%   |
| 0      | 1         | 4.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 16        | 72.73%  |
| Yes       | 6         | 27.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 17        | 77.27%  |
| No        | 5         | 22.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 90.91%  |
| No        | 2         | 9.09%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 6         | 27.27%  |
| Germany      | 5         | 22.73%  |
| France       | 3         | 13.64%  |
| Spain        | 2         | 9.09%   |
| Venezuela    | 1         | 4.55%   |
| Sweden       | 1         | 4.55%   |
| South Africa | 1         | 4.55%   |
| Pakistan     | 1         | 4.55%   |
| India        | 1         | 4.55%   |
| Bulgaria     | 1         | 4.55%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Queens        | 2         | 9.09%   |
| Hamburg       | 2         | 9.09%   |
| Uppsala       | 1         | 4.55%   |
| Sofia         | 1         | 4.55%   |
| Parla         | 1         | 4.55%   |
| Paris         | 1         | 4.55%   |
| Mangalore     | 1         | 4.55%   |
| Los Angeles   | 1         | 4.55%   |
| Lille         | 1         | 4.55%   |
| Land O' Lakes | 1         | 4.55%   |
| Lahore        | 1         | 4.55%   |
| Kennewick     | 1         | 4.55%   |
| Johannesburg  | 1         | 4.55%   |
| Guglingen     | 1         | 4.55%   |
| Guanare       | 1         | 4.55%   |
| Essen         | 1         | 4.55%   |
| Castelginest  | 1         | 4.55%   |
| Berlin        | 1         | 4.55%   |
| Barcelona     | 1         | 4.55%   |
| Austin        | 1         | 4.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 17.24%  |
| Samsung Electronics | 3         | 3      | 10.34%  |
| LITEONIT            | 2         | 2      | 6.9%    |
| Kingston            | 2         | 2      | 6.9%    |
| Unknown             | 1         | 1      | 3.45%   |
| Union Memory        | 1         | 1      | 3.45%   |
| Transcend           | 1         | 1      | 3.45%   |
| Toshiba             | 1         | 1      | 3.45%   |
| SSSTC               | 1         | 1      | 3.45%   |
| SK hynix            | 1         | 1      | 3.45%   |
| Seagate             | 1         | 1      | 3.45%   |
| Plextor             | 1         | 1      | 3.45%   |
| Micron Technology   | 1         | 1      | 3.45%   |
| Intel               | 1         | 1      | 3.45%   |
| Hitachi             | 1         | 1      | 3.45%   |
| HGST                | 1         | 1      | 3.45%   |
| EMTEC               | 1         | 2      | 3.45%   |
| Dell                | 1         | 2      | 3.45%   |
| China               | 1         | 1      | 3.45%   |
| ASMT                | 1         | 2      | 3.45%   |
| A-DATA Technology   | 1         | 1      | 3.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD10SPZX-24Z10 1TB                  | 2         | 6.9%    |
| WDC WD5000LPCX-21VHAT0 500GB            | 1         | 3.45%   |
| WDC WD10SPZX-60Z10T1 1TB                | 1         | 3.45%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB    | 1         | 3.45%   |
| Unknown SD/MMC/MS PRO 8GB               | 1         | 3.45%   |
| Union Memory UMIS RPITJ512VME2OWD 512GB | 1         | 3.45%   |
| Transcend TS256GMTE220S 256GB           | 1         | 3.45%   |
| Toshiba MK6475GSX 640GB                 | 1         | 3.45%   |
| SSSTC CL1-3D256 256GB                   | 1         | 3.45%   |
| SK hynix NVMe SSD Drive 256GB           | 1         | 3.45%   |
| Seagate ST250LM004 HN-M250MBB 250GB     | 1         | 3.45%   |
| Samsung SSD PM810 FDE 2.5 256GB         | 1         | 3.45%   |
| Samsung MZVLQ512HALU-00000 512GB        | 1         | 3.45%   |
| Samsung MZVLQ128HBHQ-000H1 128GB        | 1         | 3.45%   |
| Plextor PX-128S3C 128GB SSD             | 1         | 3.45%   |
| Micron MTFDDAK256MAM-1K12 256GB SSD     | 1         | 3.45%   |
| LITEONIT LSS-16L6G-HP 16GB SSD          | 1         | 3.45%   |
| LITEONIT LGT-128M6G 128GB SSD           | 1         | 3.45%   |
| Kingston SUV400S37120G 120GB SSD        | 1         | 3.45%   |
| Kingston SA400S37240G 240GB SSD         | 1         | 3.45%   |
| Intel SSDSC2KF128G8L 128GB              | 1         | 3.45%   |
| Hitachi HTS545032B9A300 320GB           | 1         | 3.45%   |
| HGST HTS541010A9E680 1TB                | 1         | 3.45%   |
| EMTEC X200 256GB                        | 1         | 3.45%   |
| Dell WR202KD032G E70290F5 32GB          | 1         | 3.45%   |
| China SATA SSD 120GB                    | 1         | 3.45%   |
| ASMT 2105 12TB                          | 1         | 3.45%   |
| A-DATA AXNS381E-256GM-B 256GB SSD       | 1         | 3.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 40%     |
| Unknown | 1         | 1      | 10%     |
| Toshiba | 1         | 1      | 10%     |
| Seagate | 1         | 1      | 10%     |
| Hitachi | 1         | 1      | 10%     |
| HGST    | 1         | 1      | 10%     |
| ASMT    | 1         | 2      | 10%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| LITEONIT            | 2         | 2      | 18.18%  |
| Kingston            | 2         | 2      | 18.18%  |
| Samsung Electronics | 1         | 1      | 9.09%   |
| Plextor             | 1         | 1      | 9.09%   |
| Micron Technology   | 1         | 1      | 9.09%   |
| Intel               | 1         | 1      | 9.09%   |
| Dell                | 1         | 2      | 9.09%   |
| China               | 1         | 1      | 9.09%   |
| A-DATA Technology   | 1         | 1      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 11        | 12     | 37.93%  |
| HDD     | 10        | 11     | 34.48%  |
| NVMe    | 7         | 7      | 24.14%  |
| Unknown | 1         | 2      | 3.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 17        | 20     | 65.38%  |
| NVMe | 7         | 7      | 26.92%  |
| SAS  | 2         | 5      | 7.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 14        | 16     | 70%     |
| 0.51-1.0   | 5         | 5      | 25%     |
| 10.01-20.0 | 1         | 2      | 5%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 9         | 40.91%  |
| 251-500    | 5         | 22.73%  |
| 21-50      | 2         | 9.09%   |
| 501-1000   | 2         | 9.09%   |
| 51-100     | 2         | 9.09%   |
| 1001-2000  | 1         | 4.55%   |
| 1-20       | 1         | 4.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 11        | 47.83%  |
| 21-50   | 8         | 34.78%  |
| 101-250 | 2         | 8.7%    |
| 251-500 | 1         | 4.35%   |
| 51-100  | 1         | 4.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| LITEONIT LSS-16L6G-HP 16GB SSD | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| LITEONIT | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 1      | 100%    |

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
| Works    | 11        | 14     | 50%     |
| Detected | 10        | 17     | 45.45%  |
| Malfunc  | 1         | 1      | 4.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 15        | 55.56%  |
| AMD                            | 4         | 14.81%  |
| Union Memory (Shenzhen)        | 2         | 7.41%   |
| Samsung Electronics            | 2         | 7.41%   |
| Solid State Storage Technology | 1         | 3.7%    |
| SK hynix                       | 1         | 3.7%    |
| Silicon Motion                 | 1         | 3.7%    |
| SanDisk                        | 1         | 3.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                   | 4         | 14.81%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                          | 3         | 11.11%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]      | 3         | 11.11%  |
| Union Memory (Shenzhen) Non-Volatile memory controller                | 2         | 7.41%   |
| Samsung NVMe SSD Controller 980                                       | 2         | 7.41%   |
| Solid State Storage Non-Volatile memory controller                    | 1         | 3.7%    |
| SK hynix BC511                                                        | 1         | 3.7%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                         | 1         | 3.7%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                            | 1         | 3.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                    | 1         | 3.7%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                    | 1         | 3.7%    |
| Intel Comet Lake SATA AHCI Controller                                 | 1         | 3.7%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                     | 1         | 3.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                     | 1         | 3.7%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                | 1         | 3.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode] | 1         | 3.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                        | 1         | 3.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                  | 1         | 3.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 18        | 66.67%  |
| NVMe | 8         | 29.63%  |
| RAID | 1         | 3.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 17        | 77.27%  |
| AMD    | 5         | 22.73%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 13.64%  |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 4.55%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 4.55%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 4.55%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 4.55%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 4.55%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 4.55%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 4.55%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 4.55%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 4.55%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 4.55%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 1         | 4.55%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 4.55%   |
| Intel Celeron 2955U @ 1.40GHz                 | 1         | 4.55%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 1         | 4.55%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 4.55%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 4.55%   |
| AMD Ryzen 3 3250U with Radeon Graphics        | 1         | 4.55%   |
| AMD A9-9420e RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 4.55%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G | 1         | 4.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 7         | 31.82%  |
| Intel Core i7           | 4         | 18.18%  |
| Intel Core i3           | 2         | 9.09%   |
| Other                   | 1         | 4.55%   |
| Intel Pentium Dual-Core | 1         | 4.55%   |
| Intel Pentium           | 1         | 4.55%   |
| Intel Celeron           | 1         | 4.55%   |
| Intel Atom              | 1         | 4.55%   |
| AMD Ryzen 7             | 1         | 4.55%   |
| AMD Ryzen 5             | 1         | 4.55%   |
| AMD Ryzen 3             | 1         | 4.55%   |
| AMD A6                  | 1         | 4.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 11        | 50%     |
| 4      | 8         | 36.36%  |
| 8      | 1         | 4.55%   |
| 6      | 1         | 4.55%   |
| 1      | 1         | 4.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 22        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 17        | 77.27%  |
| 1      | 5         | 22.73%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 22        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 4         | 18.18%  |
| 0x306a9    | 4         | 18.18%  |
| 0x40651    | 3         | 13.64%  |
| 0xa0652    | 1         | 4.55%   |
| 0x906ea    | 1         | 4.55%   |
| 0x406e3    | 1         | 4.55%   |
| 0x30678    | 1         | 4.55%   |
| 0x106ca    | 1         | 4.55%   |
| 0x1067a    | 1         | 4.55%   |
| 0x08608103 | 1         | 4.55%   |
| 0x08108109 | 1         | 4.55%   |
| 0x0810100b | 1         | 4.55%   |
| 0x06006705 | 1         | 4.55%   |
| 0x06006704 | 1         | 4.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KabyLake   | 5         | 22.73%  |
| IvyBridge  | 4         | 18.18%  |
| Haswell    | 3         | 13.64%  |
| Excavator  | 2         | 9.09%   |
| Zen+       | 1         | 4.55%   |
| Zen        | 1         | 4.55%   |
| Skylake    | 1         | 4.55%   |
| Silvermont | 1         | 4.55%   |
| Penryn     | 1         | 4.55%   |
| CometLake  | 1         | 4.55%   |
| Bonnell    | 1         | 4.55%   |
| Unknown    | 1         | 4.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 15        | 60%     |
| Nvidia | 5         | 20%     |
| AMD    | 5         | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                        | 3         | 12%     |
| Intel CometLake-U GT2 [UHD Graphics]                                    | 3         | 12%     |
| Intel 3rd Gen Core processor Graphics Controller                        | 2         | 8%      |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                | 2         | 8%      |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                              | 1         | 4%      |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                 | 1         | 4%      |
| Nvidia GM108M [GeForce 930M]                                            | 1         | 4%      |
| Nvidia GK107GLM [Quadro K1000M]                                         | 1         | 4%      |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                       | 1         | 4%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                              | 1         | 4%      |
| Intel Skylake GT2 [HD Graphics 520]                                     | 1         | 4%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller            | 1         | 4%      |
| Intel CometLake-H GT2 [UHD Graphics]                                    | 1         | 4%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                               | 1         | 4%      |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display            | 1         | 4%      |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller | 1         | 4%      |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]        | 1         | 4%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]    | 1         | 4%      |
| AMD Lucienne                                                            | 1         | 4%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 12        | 54.55%  |
| 1 x AMD        | 5         | 22.73%  |
| Intel + Nvidia | 3         | 13.64%  |
| 1 x Nvidia     | 2         | 9.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 19        | 86.36%  |
| Proprietary | 2         | 9.09%   |
| Unknown     | 1         | 4.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 63.64%  |
| 0.01-0.5   | 4         | 18.18%  |
| 1.01-2.0   | 3         | 13.64%  |
| 5.01-6.0   | 1         | 4.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 6         | 25%     |
| AU Optronics            | 6         | 25%     |
| Samsung Electronics     | 3         | 12.5%   |
| BOE                     | 2         | 8.33%   |
| Sharp                   | 1         | 4.17%   |
| Seiki                   | 1         | 4.17%   |
| PANDA                   | 1         | 4.17%   |
| InfoVision              | 1         | 4.17%   |
| Chimei Innolux          | 1         | 4.17%   |
| Chi Mei Optoelectronics | 1         | 4.17%   |
| BenQ                    | 1         | 4.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Sharp LC-32LB480U SHP3263 1920x1080 698x392mm 31.5-inch                  | 1         | 4.17%   |
| Seiki SC32HT04 SEK1366 1366x768 700x390mm 31.5-inch                      | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch    | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch     | 1         | 4.17%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 1         | 4.17%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 1         | 4.17%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 1         | 4.17%   |
| LG Display LCD Monitor LGD042D 1920x1080 294x165mm 13.3-inch             | 1         | 4.17%   |
| LG Display LCD Monitor LGD034A 1366x768 345x194mm 15.6-inch              | 1         | 4.17%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch              | 1         | 4.17%   |
| LG Display LCD Monitor LGD02A5 1366x768 345x194mm 15.6-inch              | 1         | 4.17%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 310x170mm 13.9-inch          | 1         | 4.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 1         | 4.17%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 1         | 4.17%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch                    | 1         | 4.17%   |
| BenQ GL2450 BNQ78A5 1920x1080 531x298mm 24.0-inch                        | 1         | 4.17%   |
| AU Optronics LCD Monitor AUOF992 1920x1080 382x215mm 17.3-inch           | 1         | 4.17%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch           | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch           | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO13ED 1920x1080 344x193mm 15.5-inch           | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch            | 1         | 4.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 14        | 58.33%  |
| 1366x768 (WXGA) | 8         | 33.33%  |
| 3840x2160 (4K)  | 2         | 8.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 11        | 45.83%  |
| 14     | 6         | 25%     |
| 31     | 2         | 8.33%   |
| 13     | 2         | 8.33%   |
| 24     | 1         | 4.17%   |
| 17     | 1         | 4.17%   |
| 11     | 1         | 4.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 70.83%  |
| 201-300     | 3         | 12.5%   |
| 601-700     | 2         | 8.33%   |
| 501-600     | 1         | 4.17%   |
| 351-400     | 1         | 4.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 21        | 100%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 11        | 45.83%  |
| 81-90          | 6         | 25%     |
| 71-80          | 2         | 8.33%   |
| 351-500        | 2         | 8.33%   |
| 51-60          | 1         | 4.17%   |
| 201-250        | 1         | 4.17%   |
| 121-130        | 1         | 4.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 11        | 45.83%  |
| 101-120       | 5         | 20.83%  |
| 51-100        | 4         | 16.67%  |
| More than 240 | 2         | 8.33%   |
| 1-50          | 1         | 4.17%   |
| 161-240       | 1         | 4.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 18        | 81.82%  |
| 2     | 3         | 13.64%  |
| 0     | 1         | 4.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 10        | 31.25%  |
| Realtek Semiconductor | 9         | 28.13%  |
| Qualcomm Atheros      | 6         | 18.75%  |
| Broadcom Limited      | 2         | 6.25%   |
| TP-Link               | 1         | 3.13%   |
| Sierra Wireless       | 1         | 3.13%   |
| Samsung Electronics   | 1         | 3.13%   |
| MediaTek              | 1         | 3.13%   |
| Broadcom              | 1         | 3.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 14.63%  |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 7.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 4.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 4.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 4.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 4.88%   |
| Intel Wireless 7260                                               | 2         | 4.88%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 4.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4.88%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 2.44%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 2.44%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 2.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 2.44%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 2.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 2.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.44%   |
| MediaTek TECNO F1                                                 | 1         | 2.44%   |
| Intel Wireless 3165                                               | 1         | 2.44%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.44%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 2.44%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 2.44%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 2.44%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 2.44%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                           | 1         | 2.44%   |
| Broadcom BCM43225 802.11b/g/n                                     | 1         | 2.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 9         | 39.13%  |
| Qualcomm Atheros      | 6         | 26.09%  |
| Realtek Semiconductor | 5         | 21.74%  |
| Sierra Wireless       | 1         | 4.35%   |
| Broadcom Limited      | 1         | 4.35%   |
| Broadcom              | 1         | 4.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Comet Lake PCH-LP CNVi WiFi                          | 3         | 13.04%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 2         | 8.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 2         | 8.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 8.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2         | 8.7%    |
| Intel Wireless 7260                                        | 2         | 8.7%    |
| Sierra Wireless EM7345 4G LTE                              | 1         | 4.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 4.35%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 4.35%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 1         | 4.35%   |
| Intel Wireless 3165                                        | 1         | 4.35%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 4.35%   |
| Intel Centrino Wireless-N 2230                             | 1         | 4.35%   |
| Intel Centrino Ultimate-N 6300                             | 1         | 4.35%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                    | 1         | 4.35%   |
| Broadcom BCM43225 802.11b/g/n                              | 1         | 4.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 8         | 44.44%  |
| Intel                 | 5         | 27.78%  |
| TP-Link               | 1         | 5.56%   |
| Samsung Electronics   | 1         | 5.56%   |
| Qualcomm Atheros      | 1         | 5.56%   |
| MediaTek              | 1         | 5.56%   |
| Broadcom Limited      | 1         | 5.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 33.33%  |
| Intel Ethernet Connection (10) I219-V                             | 2         | 11.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 11.11%  |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 5.56%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 5.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 5.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 5.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 5.56%   |
| MediaTek TECNO F1                                                 | 1         | 5.56%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 5.56%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 5.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 22        | 56.41%  |
| Ethernet | 17        | 43.59%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 15        | 60%     |
| Ethernet | 10        | 40%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 14        | 63.64%  |
| 1     | 8         | 36.36%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 17        | 77.27%  |
| Yes  | 5         | 22.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 8         | 40%     |
| Qualcomm Atheros Communications | 5         | 25%     |
| Realtek Semiconductor           | 4         | 20%     |
| Foxconn / Hon Hai               | 1         | 5%      |
| Cambridge Silicon Radio         | 1         | 5%      |
| Broadcom                        | 1         | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 4         | 20%     |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 20%     |
| Intel AX201 Bluetooth                               | 4         | 20%     |
| Intel Bluetooth wireless interface                  | 3         | 15%     |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 5%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 5%      |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 5%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 5%      |
| Broadcom HP Portable SoftSailing                    | 1         | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 17        | 58.62%  |
| AMD                  | 5         | 17.24%  |
| Nvidia               | 4         | 13.79%  |
| C-Media Electronics  | 2         | 6.9%    |
| Conrad Electronic SE | 1         | 3.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 10.81%  |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 8.11%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 8.11%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 8.11%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 8.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 5.41%   |
| AMD High Definition Audio Controller                                       | 2         | 5.41%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 5.41%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 2.7%    |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 2.7%    |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 2.7%    |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 2.7%    |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 2.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 2.7%    |
| Intel Comet Lake PCH cAVS                                                  | 1         | 2.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 2.7%    |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 2.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 2.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 2.7%    |
| Conrad Electronic SE MIDI Cable UA0037                                     | 1         | 2.7%    |
| C-Media Electronics USB Audio Device                                       | 1         | 2.7%    |
| C-Media Electronics CM106 Like Sound Device                                | 1         | 2.7%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 2.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 5         | 31.25%  |
| SK hynix            | 3         | 18.75%  |
| Kingston            | 3         | 18.75%  |
| Micron Technology   | 2         | 12.5%   |
| Unknown             | 1         | 6.25%   |
| Timetec             | 1         | 6.25%   |
| Elpida              | 1         | 6.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 5.56%   |
| Timetec RAM SD3-1600 8192MB SODIMM DDR3                                   | 1         | 5.56%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 5.56%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s                    | 1         | 5.56%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s              | 1         | 5.56%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4096MB Row Of Chips LPDDR3 2133MT/s       | 1         | 5.56%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 5.56%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s                       | 1         | 5.56%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 5.56%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s                  | 1         | 5.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 1         | 5.56%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s                     | 1         | 5.56%   |
| Micron RAM 4ATF51264HZ-2G6E3 4GB SODIMM DDR4 2667MT/s                     | 1         | 5.56%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s                      | 1         | 5.56%   |
| Kingston RAM KHX2666C15S4/8G 8GB SODIMM DDR4 2667MT/s                     | 1         | 5.56%   |
| Kingston RAM 787878787878787878787878787878787878 2GB SODIMM DDR2 667MT/s | 1         | 5.56%   |
| Kingston RAM 272727272727272727272727272727272727 2GB SODIMM DDR2 667MT/s | 1         | 5.56%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s                     | 1         | 5.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 5         | 41.67%  |
| DDR3   | 4         | 33.33%  |
| LPDDR3 | 2         | 16.67%  |
| DDR2   | 1         | 8.33%   |

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
| 4096  | 7         | 53.85%  |
| 8192  | 4         | 30.77%  |
| 16384 | 1         | 7.69%   |
| 2048  | 1         | 7.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 4         | 28.57%  |
| 3200  | 3         | 21.43%  |
| 2667  | 2         | 14.29%  |
| 2133  | 2         | 14.29%  |
| 1866  | 1         | 7.14%   |
| 1333  | 1         | 7.14%   |
| 667   | 1         | 7.14%   |

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
| Chicony Electronics                    | 8         | 36.36%  |
| IMC Networks                           | 5         | 22.73%  |
| Acer                                   | 3         | 13.64%  |
| Suyin                                  | 2         | 9.09%   |
| Realtek Semiconductor                  | 1         | 4.55%   |
| Microdia                               | 1         | 4.55%   |
| Luxvisions Innotech Limited            | 1         | 4.55%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 4.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                  | 4         | 17.39%  |
| Chicony Integrated HP HD Webcam                                 | 2         | 8.7%    |
| Chicony HP Truevision HD                                        | 2         | 8.7%    |
| Suyin HD WebCam                                                 | 1         | 4.35%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)     | 1         | 4.35%   |
| Realtek EasyCamera                                              | 1         | 4.35%   |
| Microdia Integrated_Webcam_HD                                   | 1         | 4.35%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 1         | 4.35%   |
| IMC Networks USB2.0 HD IR UVC WebCam                            | 1         | 4.35%   |
| Chicony TOSHIBA Web Camera - HD                                 | 1         | 4.35%   |
| Chicony Lenovo EasyCamera                                       | 1         | 4.35%   |
| Chicony EasyCamera                                              | 1         | 4.35%   |
| Chicony 8M Camera                                               | 1         | 4.35%   |
| Chicony 720p HD Camera                                          | 1         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera | 1         | 4.35%   |
| Acer USB Camera                                                 | 1         | 4.35%   |
| Acer Lenovo EasyCamera                                          | 1         | 4.35%   |
| Acer Integrated Camera                                          | 1         | 4.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 5         | 83.33%  |
| Elan Microelectronics | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS491                      | 2         | 33.33%  |
| Validity Sensors VFS5011 Fingerprint Reader  | 1         | 16.67%  |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 16.67%  |
| Validity Sensors Fingerprint scanner         | 1         | 16.67%  |
| Elan ELAN:ARM-M4                             | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 14        | 63.64%  |
| 1     | 5         | 22.73%  |
| 2     | 2         | 9.09%   |
| 7     | 1         | 4.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 6         | 42.86%  |
| Net/wireless          | 2         | 14.29%  |
| Sound                 | 1         | 7.14%   |
| Multimedia controller | 1         | 7.14%   |
| Graphics card         | 1         | 7.14%   |
| Chipcard              | 1         | 7.14%   |
| Camera                | 1         | 7.14%   |
| Bluetooth             | 1         | 7.14%   |

