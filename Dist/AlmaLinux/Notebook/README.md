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

Total: 41

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
| HP      | ZBook 17 G2                 | [fc2425ffde](https://linux-hardware.org/?probe=fc2425ffde) | Apr 08, 2023 |
| TUXEDO  | Aura 15 Gen1                | [1584039ca8](https://linux-hardware.org/?probe=1584039ca8) | Mar 24, 2023 |
| TUXEDO  | Aura 15 Gen1                | [a8e6ba1268](https://linux-hardware.org/?probe=a8e6ba1268) | Mar 24, 2023 |
| Lenovo  | ThinkPad P1 Gen 4i 20Y30... | [97af59e728](https://linux-hardware.org/?probe=97af59e728) | Mar 18, 2023 |
| Google  | Kefka                       | [8142fbc91a](https://linux-hardware.org/?probe=8142fbc91a) | Feb 24, 2023 |
| Dell    | Inspiron 3501               | [725c2a80f8](https://linux-hardware.org/?probe=725c2a80f8) | Jan 29, 2023 |
| Lenovo  | V14-ARE 82DQ                | [9fbcd4b714](https://linux-hardware.org/?probe=9fbcd4b714) | Jan 28, 2023 |
| HP      | Falco                       | [a52a8f8f4e](https://linux-hardware.org/?probe=a52a8f8f4e) | Jan 14, 2023 |
| Dell    | Latitude E6510              | [dab9cdc1be](https://linux-hardware.org/?probe=dab9cdc1be) | Jan 11, 2023 |
| HP      | Falco                       | [61ce7c6739](https://linux-hardware.org/?probe=61ce7c6739) | Dec 21, 2022 |
| HP      | EliteBook 850 G8 Noteboo... | [95d47d14cb](https://linux-hardware.org/?probe=95d47d14cb) | Dec 09, 2022 |
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
| AlmaLinux 9.1 | 8         | 26.67%  |
| AlmaLinux 9.0 | 6         | 20%     |
| AlmaLinux 8.6 | 5         | 16.67%  |
| AlmaLinux 8.4 | 5         | 16.67%  |
| AlmaLinux 8.3 | 3         | 10%     |
| AlmaLinux 8.5 | 2         | 6.67%   |
| AlmaLinux 8.7 | 1         | 3.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| AlmaLinux | 29        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.x86_64  | 3         | 10%     |
| 5.14.0-70.22.1.el9_0.x86_64  | 2         | 6.67%   |
| 5.14.0-70.13.1.el9_0.x86_64  | 2         | 6.67%   |
| 5.14.0-162.18.1.el9_1.x86_64 | 2         | 6.67%   |
| 5.14.0-162.12.1.el9_1.x86_64 | 2         | 6.67%   |
| 4.18.0-372.26.1.el8_6.x86_64 | 2         | 6.67%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 2         | 6.67%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 2         | 6.67%   |
| 5.4.175-1.el8.elrepo.x86_64  | 1         | 3.33%   |
| 5.14.0-70.26.1.el9_0.x86_64  | 1         | 3.33%   |
| 5.14.0-70.17.1.el9_0.x86_64  | 1         | 3.33%   |
| 5.14.0-162.22.2.el9_1.x86_64 | 1         | 3.33%   |
| 4.18.0-425.3.1.el8.x86_64    | 1         | 3.33%   |
| 4.18.0-372.9.1.el8.x86_64    | 1         | 3.33%   |
| 4.18.0-372.19.1.el8_6.x86_64 | 1         | 3.33%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 1         | 3.33%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 1         | 3.33%   |
| 4.18.0-305.el8.x86_64        | 1         | 3.33%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 1         | 3.33%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 1         | 3.33%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 1         | 3.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 14        | 48.28%  |
| 4.18.0  | 14        | 48.28%  |
| 5.4.175 | 1         | 3.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 14        | 48.28%  |
| 4.18    | 14        | 48.28%  |
| 5.4     | 1         | 3.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 29        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 22        | 75.86%  |
| MATE            | 2         | 6.9%    |
| KDE5            | 2         | 6.9%    |
| XFCE            | 1         | 3.45%   |
| GNOME Flashback | 1         | 3.45%   |
| GNOME Classic   | 1         | 3.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 20        | 68.97%  |
| X11     | 9         | 31.03%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 13        | 44.83%  |
| GDM     | 12        | 41.38%  |
| SDDM    | 2         | 6.9%    |
| LightDM | 2         | 6.9%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 18        | 62.07%  |
| de_DE | 4         | 13.79%  |
| fr_FR | 3         | 10.34%  |
| es_VE | 1         | 3.45%   |
| es_ES | 1         | 3.45%   |
| en_CA | 1         | 3.45%   |
| C     | 1         | 3.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 20        | 68.97%  |
| BIOS | 9         | 31.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 24        | 82.76%  |
| Ext4 | 5         | 17.24%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 15        | 51.72%  |
| Unknown | 12        | 41.38%  |
| MBR     | 2         | 6.9%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 25        | 86.21%  |
| Yes       | 4         | 13.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 23        | 79.31%  |
| Yes       | 6         | 20.69%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 11        | 37.93%  |
| Hewlett-Packard  | 8         | 27.59%  |
| Google           | 2         | 6.9%    |
| Dell             | 2         | 6.9%    |
| Acer             | 2         | 6.9%    |
| TUXEDO           | 1         | 3.45%   |
| Toshiba          | 1         | 3.45%   |
| Intel            | 1         | 3.45%   |
| ASUSTek Computer | 1         | 3.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| TUXEDO Aura 15 Gen1                  | 1         | 3.45%   |
| Toshiba Satellite L50-C              | 1         | 3.45%   |
| Lenovo Yoga 2 13 20344               | 1         | 3.45%   |
| Lenovo V14-ARE 82DQ                  | 1         | 3.45%   |
| Lenovo ThinkPad T440s 20ARS32P00     | 1         | 3.45%   |
| Lenovo ThinkPad T14 Gen 1 20S1S39Q00 | 1         | 3.45%   |
| Lenovo ThinkPad P1 Gen 4i 20Y3003XUS | 1         | 3.45%   |
| Lenovo Legion Y530-15ICH 81FV        | 1         | 3.45%   |
| Lenovo Legion 5 15IMH05H 81Y6        | 1         | 3.45%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS  | 1         | 3.45%   |
| Lenovo IdeaPad S145-15IWL 81MV       | 1         | 3.45%   |
| Lenovo IdeaPad 330-15ARR 81D2        | 1         | 3.45%   |
| Lenovo B50-30 20382                  | 1         | 3.45%   |
| Intel powered classmate PC           | 1         | 3.45%   |
| HP ZBook 17 G2                       | 1         | 3.45%   |
| HP Laptop 17-cp0xxx                  | 1         | 3.45%   |
| HP Laptop 15-ef1xxx                  | 1         | 3.45%   |
| HP Falco                             | 1         | 3.45%   |
| HP ENVY dv6                          | 1         | 3.45%   |
| HP EliteBook 8570w                   | 1         | 3.45%   |
| HP EliteBook 850 G8 Notebook PC      | 1         | 3.45%   |
| HP EliteBook 8470p                   | 1         | 3.45%   |
| Google Kohaku                        | 1         | 3.45%   |
| Google Kefka                         | 1         | 3.45%   |
| Dell Latitude E6510                  | 1         | 3.45%   |
| Dell Inspiron 3185                   | 1         | 3.45%   |
| ASUS ASUS EXPERTBOOK B9450FA_B9450FA | 1         | 3.45%   |
| Acer TravelMate 5735Z                | 1         | 3.45%   |
| Acer TMP453-MG                       | 1         | 3.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 3         | 10.34%  |
| Lenovo IdeaPad    | 3         | 10.34%  |
| HP EliteBook      | 3         | 10.34%  |
| Lenovo Legion     | 2         | 6.9%    |
| HP Laptop         | 2         | 6.9%    |
| TUXEDO Aura       | 1         | 3.45%   |
| Toshiba Satellite | 1         | 3.45%   |
| Lenovo Yoga       | 1         | 3.45%   |
| Lenovo V14-ARE    | 1         | 3.45%   |
| Lenovo B50-30     | 1         | 3.45%   |
| Intel powered     | 1         | 3.45%   |
| HP ZBook          | 1         | 3.45%   |
| HP Falco          | 1         | 3.45%   |
| HP ENVY           | 1         | 3.45%   |
| Google Kohaku     | 1         | 3.45%   |
| Google Kefka      | 1         | 3.45%   |
| Dell Latitude     | 1         | 3.45%   |
| Dell Inspiron     | 1         | 3.45%   |
| ASUS ASUS         | 1         | 3.45%   |
| Acer TravelMate   | 1         | 3.45%   |
| Acer TMP453-MG    | 1         | 3.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 6         | 20.69%  |
| 2014 | 4         | 13.79%  |
| 2019 | 3         | 10.34%  |
| 2018 | 3         | 10.34%  |
| 2012 | 3         | 10.34%  |
| 2022 | 2         | 6.9%    |
| 2021 | 2         | 6.9%    |
| 2011 | 2         | 6.9%    |
| 2010 | 2         | 6.9%    |
| 2015 | 1         | 3.45%   |
| 2013 | 1         | 3.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 29        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 24        | 82.76%  |
| Enabled  | 5         | 17.24%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 26        | 89.66%  |
| Yes  | 3         | 10.34%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 11        | 37.93%  |
| 8.01-16.0   | 6         | 20.69%  |
| 3.01-4.0    | 5         | 17.24%  |
| 16.01-24.0  | 4         | 13.79%  |
| 1.01-2.0    | 2         | 6.9%    |
| 64.01-256.0 | 1         | 3.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 10        | 32.26%  |
| 1.01-2.0  | 9         | 29.03%  |
| 4.01-8.0  | 5         | 16.13%  |
| 3.01-4.0  | 4         | 12.9%   |
| 0.51-1.0  | 2         | 6.45%   |
| 8.01-16.0 | 1         | 3.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 19        | 63.33%  |
| 2      | 8         | 26.67%  |
| 3      | 2         | 6.67%   |
| 0      | 1         | 3.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 21        | 72.41%  |
| Yes       | 8         | 27.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 65.52%  |
| No        | 10        | 34.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 89.66%  |
| No        | 3         | 10.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 9         | 31.03%  |
| Germany      | 5         | 17.24%  |
| France       | 4         | 13.79%  |
| Spain        | 2         | 6.9%    |
| Venezuela    | 1         | 3.45%   |
| Sweden       | 1         | 3.45%   |
| South Africa | 1         | 3.45%   |
| Puerto Rico  | 1         | 3.45%   |
| Pakistan     | 1         | 3.45%   |
| Netherlands  | 1         | 3.45%   |
| India        | 1         | 3.45%   |
| Canada       | 1         | 3.45%   |
| Bulgaria     | 1         | 3.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Queens        | 2         | 6.9%    |
| Hamburg       | 2         | 6.9%    |
| Winterswijk   | 1         | 3.45%   |
| Uppsala       | 1         | 3.45%   |
| Sofia         | 1         | 3.45%   |
| Saint-Brieuc  | 1         | 3.45%   |
| Regina        | 1         | 3.45%   |
| Redlands      | 1         | 3.45%   |
| Parla         | 1         | 3.45%   |
| Paris         | 1         | 3.45%   |
| Mangalore     | 1         | 3.45%   |
| Los Angeles   | 1         | 3.45%   |
| Lille         | 1         | 3.45%   |
| Land O' Lakes | 1         | 3.45%   |
| Lahore        | 1         | 3.45%   |
| Kennewick     | 1         | 3.45%   |
| Johannesburg  | 1         | 3.45%   |
| Guglingen     | 1         | 3.45%   |
| Guanare       | 1         | 3.45%   |
| Essen         | 1         | 3.45%   |
| Columbia      | 1         | 3.45%   |
| Castelginest  | 1         | 3.45%   |
| Boston        | 1         | 3.45%   |
| Berlin        | 1         | 3.45%   |
| Bayamón      | 1         | 3.45%   |
| Barcelona     | 1         | 3.45%   |
| Austin        | 1         | 3.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 5         | 5      | 13.16%  |
| Samsung Electronics         | 4         | 4      | 10.53%  |
| Kingston                    | 3         | 3      | 7.89%   |
| Unknown                     | 2         | 3      | 5.26%   |
| SK hynix                    | 2         | 2      | 5.26%   |
| LITEONIT                    | 2         | 4      | 5.26%   |
| Union Memory                | 1         | 1      | 2.63%   |
| Transcend                   | 1         | 1      | 2.63%   |
| Toshiba                     | 1         | 1      | 2.63%   |
| SSSTC                       | 1         | 1      | 2.63%   |
| Seagate                     | 1         | 1      | 2.63%   |
| SanDisk                     | 1         | 1      | 2.63%   |
| Plextor                     | 1         | 1      | 2.63%   |
| Netac                       | 1         | 1      | 2.63%   |
| Micron Technology           | 1         | 1      | 2.63%   |
| KIOXIA                      | 1         | 1      | 2.63%   |
| Kingston Technology Company | 1         | 1      | 2.63%   |
| Intel                       | 1         | 1      | 2.63%   |
| Hitachi                     | 1         | 1      | 2.63%   |
| HGST                        | 1         | 1      | 2.63%   |
| EMTEC                       | 1         | 2      | 2.63%   |
| Dell                        | 1         | 2      | 2.63%   |
| Crucial                     | 1         | 2      | 2.63%   |
| China                       | 1         | 1      | 2.63%   |
| ASMT                        | 1         | 2      | 2.63%   |
| A-DATA Technology           | 1         | 1      | 2.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD10SPZX-24Z10 1TB                  | 2         | 5.13%   |
| WDC WD5000LPCX-21VHAT0 500GB            | 1         | 2.56%   |
| WDC WD10SPZX-60Z10T1 1TB                | 1         | 2.56%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB    | 1         | 2.56%   |
| Unknown SD/MMC/MS PRO 249GB             | 1         | 2.56%   |
| Unknown MMC Card  16GB                  | 1         | 2.56%   |
| Union Memory UMIS RPITJ512VME2OWD 512GB | 1         | 2.56%   |
| Transcend TS256GMTE220S 256GB           | 1         | 2.56%   |
| Toshiba MK6475GSX 640GB                 | 1         | 2.56%   |
| SSSTC CL1-3D256 256GB                   | 1         | 2.56%   |
| SK hynix NVMe SSD Drive 256GB           | 1         | 2.56%   |
| SK hynix BC511 NVMe 256GB               | 1         | 2.56%   |
| Seagate ST250LM004 HN-M250MBB 250GB     | 1         | 2.56%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD     | 1         | 2.56%   |
| Samsung SSD PM810 FDE 2.5 256GB         | 1         | 2.56%   |
| Samsung MZVLQ512HALU-00000 512GB        | 1         | 2.56%   |
| Samsung MZVLQ128HBHQ-000H1 128GB        | 1         | 2.56%   |
| Samsung MZVL22T0HBLB-00BL7 2TB          | 1         | 2.56%   |
| Plextor PX-128S3C 128GB SSD             | 1         | 2.56%   |
| Netac SSD 128GB                         | 1         | 2.56%   |
| Micron MTFDDAK256MAM-1K12 256GB SSD     | 1         | 2.56%   |
| LITEONIT LSS-16L6G-HP 16GB SSD          | 1         | 2.56%   |
| LITEONIT LGT-128M6G 128GB SSD           | 1         | 2.56%   |
| KIOXIA KXG60ZNV512G 512GB               | 1         | 2.56%   |
| Kingston Company A2000 NVMe SSD 500GB   | 1         | 2.56%   |
| Kingston SUV400S37120G 120GB SSD        | 1         | 2.56%   |
| Kingston SA400S37480G 480GB SSD         | 1         | 2.56%   |
| Kingston SA400S37240G 240GB SSD         | 1         | 2.56%   |
| Intel SSDSC2KF128G8L 128GB              | 1         | 2.56%   |
| Hitachi HTS545032B9A300 320GB           | 1         | 2.56%   |
| HGST HTS541010A9E680 1TB                | 1         | 2.56%   |
| EMTEC X200 256GB                        | 1         | 2.56%   |
| Dell WR202KD032G E70290F5 32GB          | 1         | 2.56%   |
| Crucial CT240BX500SSD1 240GB            | 1         | 2.56%   |
| Crucial CT1024MX200SSD1 1TB             | 1         | 2.56%   |
| China SATA SSD 120GB                    | 1         | 2.56%   |
| ASMT 2105 1TB                           | 1         | 2.56%   |
| A-DATA AXNS381E-256GM-B 256GB SSD       | 1         | 2.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 40%     |
| Unknown | 1         | 2      | 10%     |
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
| Kingston            | 3         | 3      | 20%     |
| LITEONIT            | 2         | 4      | 13.33%  |
| SanDisk             | 1         | 1      | 6.67%   |
| Samsung Electronics | 1         | 1      | 6.67%   |
| Plextor             | 1         | 1      | 6.67%   |
| Netac               | 1         | 1      | 6.67%   |
| Micron Technology   | 1         | 1      | 6.67%   |
| Intel               | 1         | 1      | 6.67%   |
| Dell                | 1         | 2      | 6.67%   |
| Crucial             | 1         | 2      | 6.67%   |
| China               | 1         | 1      | 6.67%   |
| A-DATA Technology   | 1         | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 14        | 19     | 37.84%  |
| NVMe    | 11        | 11     | 29.73%  |
| HDD     | 10        | 12     | 27.03%  |
| MMC     | 1         | 1      | 2.7%    |
| Unknown | 1         | 2      | 2.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 20        | 27     | 58.82%  |
| NVMe | 11        | 11     | 32.35%  |
| SAS  | 2         | 6      | 5.88%   |
| MMC  | 1         | 1      | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 17        | 23     | 70.83%  |
| 0.51-1.0   | 7         | 8      | 29.17%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 11        | 36.67%  |
| 251-500    | 8         | 26.67%  |
| 51-100     | 3         | 10%     |
| 21-50      | 2         | 6.67%   |
| 1001-2000  | 2         | 6.67%   |
| 1-20       | 2         | 6.67%   |
| 501-1000   | 2         | 6.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 16        | 51.61%  |
| 21-50   | 9         | 29.03%  |
| 101-250 | 3         | 9.68%   |
| 51-100  | 2         | 6.45%   |
| 251-500 | 1         | 3.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| LITEONIT LSS-16L6G-HP 16GB SSD | 1         | 3      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| LITEONIT | 1         | 3      | 100%    |

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
| SSD  | 1         | 3      | 100%    |

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
| Works    | 15        | 20     | 50%     |
| Detected | 14        | 22     | 46.67%  |
| Malfunc  | 1         | 3      | 3.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 18        | 51.43%  |
| AMD                            | 5         | 14.29%  |
| Samsung Electronics            | 3         | 8.57%   |
| Union Memory (Shenzhen)        | 2         | 5.71%   |
| Toshiba America Info Systems   | 1         | 2.86%   |
| Solid State Storage Technology | 1         | 2.86%   |
| SK hynix                       | 1         | 2.86%   |
| Silicon Motion                 | 1         | 2.86%   |
| SanDisk                        | 1         | 2.86%   |
| Marvell Technology Group       | 1         | 2.86%   |
| Kingston Technology Company    | 1         | 2.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 5         | 14.29%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 8.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 8.57%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 5.71%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 5.71%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 5.71%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 2.86%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 2.86%   |
| SK hynix BC511                                                                 | 1         | 2.86%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 2.86%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 2.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 2.86%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 2.86%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 2.86%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 2.86%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 2.86%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 2.86%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 2.86%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 2.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 2.86%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 2.86%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 2.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.86%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 2.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 20        | 58.82%  |
| NVMe | 11        | 32.35%  |
| RAID | 3         | 8.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 22        | 75.86%  |
| AMD    | 7         | 24.14%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 10.34%  |
| Intel Xeon W-11855M CPU @ 3.20GHz             | 1         | 3.45%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 3.45%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 3.45%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 3.45%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 1         | 3.45%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 3.45%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 3.45%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 3.45%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 3.45%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 3.45%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 3.45%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 3.45%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 1         | 3.45%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 3.45%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 1         | 3.45%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 3.45%   |
| Intel Celeron 2955U @ 1.40GHz                 | 1         | 3.45%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 1         | 3.45%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 3.45%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 3.45%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 3.45%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 3.45%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 3.45%   |
| AMD Ryzen 3 3250U with Radeon Graphics        | 1         | 3.45%   |
| AMD A9-9420e RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 3.45%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G | 1         | 3.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 7         | 24.14%  |
| Intel Core i7           | 5         | 17.24%  |
| Intel Core i3           | 3         | 10.34%  |
| Other                   | 2         | 6.9%    |
| Intel Celeron           | 2         | 6.9%    |
| AMD Ryzen 7             | 2         | 6.9%    |
| AMD Ryzen 5             | 2         | 6.9%    |
| Intel Xeon              | 1         | 3.45%   |
| Intel Pentium Dual-Core | 1         | 3.45%   |
| Intel Pentium           | 1         | 3.45%   |
| Intel Atom              | 1         | 3.45%   |
| AMD Ryzen 3             | 1         | 3.45%   |
| AMD A6                  | 1         | 3.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 13        | 44.83%  |
| 4      | 10        | 34.48%  |
| 6      | 3         | 10.34%  |
| 8      | 2         | 6.9%    |
| 1      | 1         | 3.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 29        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 21        | 72.41%  |
| 1      | 8         | 27.59%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 29        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 4         | 13.79%  |
| 0x306a9    | 4         | 13.79%  |
| 0x40651    | 3         | 10.34%  |
| 0x08600106 | 2         | 6.9%    |
| 0xa0652    | 1         | 3.45%   |
| 0x906ea    | 1         | 3.45%   |
| 0x806d1    | 1         | 3.45%   |
| 0x806c1    | 1         | 3.45%   |
| 0x406e3    | 1         | 3.45%   |
| 0x406c4    | 1         | 3.45%   |
| 0x306c3    | 1         | 3.45%   |
| 0x30678    | 1         | 3.45%   |
| 0x20655    | 1         | 3.45%   |
| 0x106ca    | 1         | 3.45%   |
| 0x1067a    | 1         | 3.45%   |
| 0x08608103 | 1         | 3.45%   |
| 0x08108109 | 1         | 3.45%   |
| 0x0810100b | 1         | 3.45%   |
| 0x06006705 | 1         | 3.45%   |
| 0x06006704 | 1         | 3.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KabyLake   | 5         | 17.24%  |
| IvyBridge  | 4         | 13.79%  |
| Haswell    | 4         | 13.79%  |
| Zen 2      | 2         | 6.9%    |
| Silvermont | 2         | 6.9%    |
| Excavator  | 2         | 6.9%    |
| Zen+       | 1         | 3.45%   |
| Zen        | 1         | 3.45%   |
| Westmere   | 1         | 3.45%   |
| TigerLake  | 1         | 3.45%   |
| Skylake    | 1         | 3.45%   |
| Penryn     | 1         | 3.45%   |
| Icelake    | 1         | 3.45%   |
| CometLake  | 1         | 3.45%   |
| Bonnell    | 1         | 3.45%   |
| Unknown    | 1         | 3.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 20        | 58.82%  |
| Nvidia | 7         | 20.59%  |
| AMD    | 7         | 20.59%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 8.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 8.82%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 5.88%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 5.88%   |
| AMD Renoir                                                                               | 2         | 5.88%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 2.94%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 2.94%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 2.94%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 2.94%   |
| Nvidia GK104GLM [Quadro K3100M]                                                          | 1         | 2.94%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 2.94%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                                       | 1         | 2.94%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 2.94%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 2.94%   |
| Intel Tiger Lake-H GT1 [UHD Graphics]                                                    | 1         | 2.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 2.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 2.94%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.94%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 2.94%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 2.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 2.94%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 2.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 2.94%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 2.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 2.94%   |
| AMD Lucienne                                                                             | 1         | 2.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 15        | 51.72%  |
| 1 x AMD        | 7         | 24.14%  |
| Intel + Nvidia | 5         | 17.24%  |
| 1 x Nvidia     | 2         | 6.9%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 26        | 89.66%  |
| Proprietary | 2         | 6.9%    |
| Unknown     | 1         | 3.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 58.62%  |
| 0.01-0.5   | 6         | 20.69%  |
| 1.01-2.0   | 3         | 10.34%  |
| 3.01-4.0   | 2         | 6.9%    |
| 5.01-6.0   | 1         | 3.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 7         | 22.58%  |
| AU Optronics            | 7         | 22.58%  |
| Samsung Electronics     | 4         | 12.9%   |
| Chimei Innolux          | 3         | 9.68%   |
| BOE                     | 3         | 9.68%   |
| InfoVision              | 2         | 6.45%   |
| Sharp                   | 1         | 3.23%   |
| Seiki                   | 1         | 3.23%   |
| PANDA                   | 1         | 3.23%   |
| Chi Mei Optoelectronics | 1         | 3.23%   |
| BenQ                    | 1         | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 2         | 6.45%   |
| Sharp LC-32LB480U SHP3263 1920x1080 698x392mm 31.5-inch                  | 1         | 3.23%   |
| Seiki SC32HT04 SEK1366 1366x768 700x390mm 31.5-inch                      | 1         | 3.23%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 1         | 3.23%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 1         | 3.23%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch    | 1         | 3.23%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch    | 1         | 3.23%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 1         | 3.23%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 1         | 3.23%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 1         | 3.23%   |
| LG Display LCD Monitor LGD042D 1920x1080 294x165mm 13.3-inch             | 1         | 3.23%   |
| LG Display LCD Monitor LGD03FB 1920x1080 382x215mm 17.3-inch             | 1         | 3.23%   |
| LG Display LCD Monitor LGD034A 1366x768 345x194mm 15.6-inch              | 1         | 3.23%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch              | 1         | 3.23%   |
| LG Display LCD Monitor LGD02A5 1366x768 345x194mm 15.6-inch              | 1         | 3.23%   |
| InfoVision LCD Monitor IVO3D41 1920x1080 344x194mm 15.5-inch             | 1         | 3.23%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN1510 1920x1080 344x193mm 15.5-inch         | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch          | 1         | 3.23%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 3.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 1         | 3.23%   |
| BOE LCD Monitor BOE09BA 2560x1600 345x215mm 16.0-inch                    | 1         | 3.23%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 1         | 3.23%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch                    | 1         | 3.23%   |
| BenQ GL2450 BNQ78A5 1920x1080 531x298mm 24.0-inch                        | 1         | 3.23%   |
| AU Optronics LCD Monitor AUOF992 1920x1080 382x215mm 17.3-inch           | 1         | 3.23%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch           | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch           | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO13ED 1920x1080 344x193mm 15.5-inch           | 1         | 3.23%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch            | 1         | 3.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 18        | 58.06%  |
| 1366x768 (WXGA) | 9         | 29.03%  |
| 3840x2160 (4K)  | 2         | 6.45%   |
| 2560x1600       | 1         | 3.23%   |
| 1600x900 (HD+)  | 1         | 3.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 13        | 41.94%  |
| 14     | 7         | 22.58%  |
| 17     | 3         | 9.68%   |
| 31     | 2         | 6.45%   |
| 13     | 2         | 6.45%   |
| 11     | 2         | 6.45%   |
| 24     | 1         | 3.23%   |
| 16     | 1         | 3.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 21        | 67.74%  |
| 201-300     | 4         | 12.9%   |
| 351-400     | 3         | 9.68%   |
| 601-700     | 2         | 6.45%   |
| 501-600     | 1         | 3.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 27        | 96.43%  |
| 16/10 | 1         | 3.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 13        | 41.94%  |
| 81-90          | 7         | 22.58%  |
| 121-130        | 3         | 9.68%   |
| 71-80          | 2         | 6.45%   |
| 51-60          | 2         | 6.45%   |
| 351-500        | 2         | 6.45%   |
| 201-250        | 1         | 3.23%   |
| 111-120        | 1         | 3.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 16        | 51.61%  |
| 101-120       | 6         | 19.35%  |
| 51-100        | 4         | 12.9%   |
| More than 240 | 2         | 6.45%   |
| 161-240       | 2         | 6.45%   |
| 1-50          | 1         | 3.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 25        | 86.21%  |
| 2     | 3         | 10.34%  |
| 0     | 1         | 3.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 37.21%  |
| Realtek Semiconductor | 11        | 25.58%  |
| Qualcomm Atheros      | 7         | 16.28%  |
| Broadcom Limited      | 2         | 4.65%   |
| Broadcom              | 2         | 4.65%   |
| TP-Link               | 1         | 2.33%   |
| Sierra Wireless       | 1         | 2.33%   |
| Samsung Electronics   | 1         | 2.33%   |
| Ralink Technology     | 1         | 2.33%   |
| MediaTek              | 1         | 2.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 13.21%  |
| Intel Wireless 7260                                               | 3         | 5.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 5.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 3.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 3.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 3.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 3.77%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 3.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.77%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.89%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 1.89%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.89%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1         | 1.89%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.89%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.89%   |
| MediaTek BL8800Pro                                                | 1         | 1.89%   |
| Intel Wireless 7265                                               | 1         | 1.89%   |
| Intel Wireless 3165                                               | 1         | 1.89%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 1.89%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.89%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.89%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.89%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.89%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.89%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 1.89%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.89%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.89%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 1.89%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                           | 1         | 1.89%   |
| Broadcom BCM43225 802.11b/g/n                                     | 1         | 1.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 1.89%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 14        | 45.16%  |
| Qualcomm Atheros      | 7         | 22.58%  |
| Realtek Semiconductor | 6         | 19.35%  |
| Broadcom              | 2         | 6.45%   |
| Ralink Technology     | 1         | 3.23%   |
| Broadcom Limited      | 1         | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                        | 3         | 9.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 3         | 9.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 2         | 6.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 2         | 6.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 6.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2         | 6.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 3.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 3.23%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter        | 1         | 3.23%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 1         | 3.23%   |
| Ralink MT7601U Wireless Adapter                            | 1         | 3.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 3.23%   |
| Intel Wireless 7265                                        | 1         | 3.23%   |
| Intel Wireless 3165                                        | 1         | 3.23%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1         | 3.23%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 3.23%   |
| Intel Wi-Fi 6 AX200                                        | 1         | 3.23%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 3.23%   |
| Intel Centrino Wireless-N 2230                             | 1         | 3.23%   |
| Intel Centrino Ultimate-N 6300                             | 1         | 3.23%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                    | 1         | 3.23%   |
| Broadcom BCM43225 802.11b/g/n                              | 1         | 3.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 1         | 3.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 9         | 42.86%  |
| Intel                 | 7         | 33.33%  |
| TP-Link               | 1         | 4.76%   |
| Sierra Wireless       | 1         | 4.76%   |
| Qualcomm Atheros      | 1         | 4.76%   |
| MediaTek              | 1         | 4.76%   |
| Broadcom Limited      | 1         | 4.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 33.33%  |
| Intel Ethernet Connection (10) I219-V                             | 2         | 9.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 9.52%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 4.76%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 4.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 4.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 4.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 4.76%   |
| MediaTek BL8800Pro                                                | 1         | 4.76%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 4.76%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 4.76%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 4.76%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 4.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 29        | 59.18%  |
| Ethernet | 19        | 38.78%  |
| Modem    | 1         | 2.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 23        | 69.7%   |
| Ethernet | 10        | 30.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 17        | 58.62%  |
| 1     | 12        | 41.38%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 23        | 79.31%  |
| Yes  | 6         | 20.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 50%     |
| Qualcomm Atheros Communications | 6         | 23.08%  |
| Realtek Semiconductor           | 4         | 15.38%  |
| Foxconn / Hon Hai               | 1         | 3.85%   |
| Cambridge Silicon Radio         | 1         | 3.85%   |
| Broadcom                        | 1         | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                  | 5         | 19.23%  |
| Intel Bluetooth wireless interface                  | 5         | 19.23%  |
| Intel AX201 Bluetooth                               | 5         | 19.23%  |
| Realtek Bluetooth Radio                             | 3         | 11.54%  |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 3.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 3.85%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.85%   |
| Intel AX210 Bluetooth                               | 1         | 3.85%   |
| Intel AX200 Bluetooth                               | 1         | 3.85%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 3.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.85%   |
| Broadcom HP Portable SoftSailing                    | 1         | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 22        | 57.89%  |
| AMD                  | 7         | 18.42%  |
| Nvidia               | 6         | 15.79%  |
| C-Media Electronics  | 2         | 5.26%   |
| Conrad Electronic SE | 1         | 2.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 10.42%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 8.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 6.25%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 6.25%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 6.25%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 6.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 4.17%   |
| AMD High Definition Audio Controller                                                              | 2         | 4.17%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 4.17%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 2.08%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 2.08%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 2.08%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 2.08%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 2.08%   |
| Nvidia Audio device                                                                               | 1         | 2.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 2.08%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 2.08%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1         | 2.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 2.08%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 2.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 2.08%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 2.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 2.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 2.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 2.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 2.08%   |
| Conrad Electronic SE MIDI Cable UA0037                                                            | 1         | 2.08%   |
| C-Media Electronics USB Audio Device                                                              | 1         | 2.08%   |
| C-Media Electronics CM106 Like Sound Device                                                       | 1         | 2.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 35%     |
| SK hynix            | 4         | 20%     |
| Micron Technology   | 3         | 15%     |
| Kingston            | 3         | 15%     |
| Unknown             | 1         | 5%      |
| Timetec             | 1         | 5%      |
| Elpida              | 1         | 5%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 4.35%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                             | 1         | 4.35%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 4.35%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 4.35%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s                 | 1         | 4.35%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s              | 1         | 4.35%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s          | 1         | 4.35%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 4.35%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s                       | 1         | 4.35%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                              | 1         | 4.35%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 4.35%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s                    | 1         | 4.35%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 1         | 4.35%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 1         | 4.35%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s                     | 1         | 4.35%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s                     | 1         | 4.35%   |
| Micron RAM 4ATF51264HZ-2G6E3 4GB SODIMM DDR4 2667MT/s                     | 1         | 4.35%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                      | 1         | 4.35%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s                      | 1         | 4.35%   |
| Kingston RAM KHX2666C15S4/8G 8GB SODIMM DDR4 2667MT/s                     | 1         | 4.35%   |
| Kingston RAM 787878787878787878787878787878787878 2GB SODIMM DDR2 667MT/s | 1         | 4.35%   |
| Kingston RAM 272727272727272727272727272727272727 2GB SODIMM DDR2 800MT/s | 1         | 4.35%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s                     | 1         | 4.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 8         | 50%     |
| DDR3   | 5         | 31.25%  |
| LPDDR3 | 2         | 12.5%   |
| DDR2   | 1         | 6.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 13        | 81.25%  |
| Row Of Chips | 3         | 18.75%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 8         | 47.06%  |
| 8192  | 5         | 29.41%  |
| 16384 | 2         | 11.76%  |
| 32768 | 1         | 5.88%   |
| 2048  | 1         | 5.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 6         | 31.58%  |
| 1600  | 5         | 26.32%  |
| 2667  | 2         | 10.53%  |
| 2133  | 2         | 10.53%  |
| 1866  | 1         | 5.26%   |
| 1333  | 1         | 5.26%   |
| 800   | 1         | 5.26%   |
| 667   | 1         | 5.26%   |

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
| Chicony Electronics                    | 9         | 34.62%  |
| IMC Networks                           | 5         | 19.23%  |
| Suyin                                  | 2         | 7.69%   |
| Luxvisions Innotech Limited            | 2         | 7.69%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 7.69%   |
| Acer                                   | 2         | 7.69%   |
| Syntek                                 | 1         | 3.85%   |
| Realtek Semiconductor                  | 1         | 3.85%   |
| Microdia                               | 1         | 3.85%   |
| Bison Electronics                      | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                           | 4         | 14.81%  |
| Chicony Integrated HP HD Webcam                                          | 2         | 7.41%   |
| Chicony HP Truevision HD                                                 | 2         | 7.41%   |
| Syntek Integrated Camera                                                 | 1         | 3.7%    |
| Suyin HD WebCam                                                          | 1         | 3.7%    |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)              | 1         | 3.7%    |
| Realtek EasyCamera                                                       | 1         | 3.7%    |
| Microdia Integrated_Webcam_HD                                            | 1         | 3.7%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera                      | 1         | 3.7%    |
| Luxvisions Innotech Limited HP HD Camera                                 | 1         | 3.7%    |
| IMC Networks USB2.0 HD IR UVC WebCam                                     | 1         | 3.7%    |
| Chicony TOSHIBA Web Camera - HD                                          | 1         | 3.7%    |
| Chicony Lenovo EasyCamera                                                | 1         | 3.7%    |
| Chicony Integrated RGB Camera                                            | 1         | 3.7%    |
| Chicony EasyCamera                                                       | 1         | 3.7%    |
| Chicony 8M Camera                                                        | 1         | 3.7%    |
| Chicony 720p HD Camera                                                   | 1         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera          | 1         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 3.7%    |
| Bison Lenovo EasyCamera                                                  | 1         | 3.7%    |
| Acer USB Camera                                                          | 1         | 3.7%    |
| Acer Integrated Camera                                                   | 1         | 3.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 6         | 75%     |
| Synaptics             | 1         | 12.5%   |
| Elan Microelectronics | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS491                      | 2         | 25%     |
| Validity Sensors VFS5011 Fingerprint Reader  | 1         | 12.5%   |
| Validity Sensors VFS495 Fingerprint Reader   | 1         | 12.5%   |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 12.5%   |
| Validity Sensors Fingerprint scanner         | 1         | 12.5%   |
| Synaptics UWP WBDI Device                    | 1         | 12.5%   |
| Elan ELAN:ARM-M4                             | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 16        | 55.17%  |
| 1     | 9         | 31.03%  |
| 2     | 3         | 10.34%  |
| 7     | 1         | 3.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 8         | 40%     |
| Net/wireless          | 3         | 15%     |
| Multimedia controller | 3         | 15%     |
| Sound                 | 1         | 5%      |
| Graphics card         | 1         | 5%      |
| Firewire controller   | 1         | 5%      |
| Chipcard              | 1         | 5%      |
| Camera                | 1         | 5%      |
| Bluetooth             | 1         | 5%      |

