Sparky - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Sparky.

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

Total: 32

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| HP        | EliteBook 745 G3            | [fac15b2640](https://linux-hardware.org/?probe=fac15b2640) | May 18, 2022 |
| HP        | EliteBook 8770w             | [4fa8e91f6d](https://linux-hardware.org/?probe=4fa8e91f6d) | Apr 26, 2022 |
| Lenovo    | G50-30 80G0                 | [c7ea70f7ba](https://linux-hardware.org/?probe=c7ea70f7ba) | Apr 25, 2022 |
| HP        | Pavilion dv5                | [22ae3dae3d](https://linux-hardware.org/?probe=22ae3dae3d) | Mar 22, 2022 |
| ASUSTek   | 1000HE                      | [5dd6246e59](https://linux-hardware.org/?probe=5dd6246e59) | Feb 08, 2022 |
| ASUSTek   | S101                        | [a850549e73](https://linux-hardware.org/?probe=a850549e73) | Feb 04, 2022 |
| HP        | EliteBook 8770w             | [9a2052fc8c](https://linux-hardware.org/?probe=9a2052fc8c) | Nov 25, 2021 |
| HP        | Pavilion g7                 | [6cebc99fe6](https://linux-hardware.org/?probe=6cebc99fe6) | Nov 22, 2021 |
| Dell      | Inspiron N5010              | [df5e66431b](https://linux-hardware.org/?probe=df5e66431b) | Nov 20, 2021 |
| HP        | EliteBook Folio 9480m       | [dae2e04d45](https://linux-hardware.org/?probe=dae2e04d45) | Oct 04, 2021 |
| Google    | Banon                       | [764debedcd](https://linux-hardware.org/?probe=764debedcd) | Sep 25, 2021 |
| Lenovo    | ThinkPad E15 20RES0GF00     | [8722c3498e](https://linux-hardware.org/?probe=8722c3498e) | May 14, 2021 |
| Apple     | MacBook1,1                  | [cc415ab6c7](https://linux-hardware.org/?probe=cc415ab6c7) | Mar 15, 2021 |
| Samsung   | NC10                        | [b5909af616](https://linux-hardware.org/?probe=b5909af616) | Mar 11, 2021 |
| Samsung   | NC10                        | [3b8de5559e](https://linux-hardware.org/?probe=3b8de5559e) | Feb 27, 2021 |
| Lenovo    | ThinkPad T61 7659AB7        | [43f03346c5](https://linux-hardware.org/?probe=43f03346c5) | Feb 19, 2021 |
| Beelink   | BT3 PRO                     | [8dbfa4dacd](https://linux-hardware.org/?probe=8dbfa4dacd) | Jan 06, 2021 |
| Beelink   | BT3 PRO                     | [d85a392e02](https://linux-hardware.org/?probe=d85a392e02) | Jan 06, 2021 |
| Samsung   | NC10                        | [8c878860a7](https://linux-hardware.org/?probe=8c878860a7) | Jan 03, 2021 |
| Dell      | Inspiron 5720               | [d360a61780](https://linux-hardware.org/?probe=d360a61780) | Dec 08, 2020 |
| eMachines | E525                        | [0c11b6b4dc](https://linux-hardware.org/?probe=0c11b6b4dc) | Nov 25, 2020 |
| Lenovo    | IdeaPad S206 20154          | [393f27acf7](https://linux-hardware.org/?probe=393f27acf7) | Nov 18, 2020 |
| Dell      | Inspiron 5720               | [787263a0c6](https://linux-hardware.org/?probe=787263a0c6) | Oct 10, 2020 |
| HP        | Laptop 17z-ca100            | [2217d0703c](https://linux-hardware.org/?probe=2217d0703c) | Oct 05, 2020 |
| HP        | Laptop 17z-ca100            | [1927ffc179](https://linux-hardware.org/?probe=1927ffc179) | Oct 05, 2020 |
| Apple     | MacBook1,1                  | [73b04f9de4](https://linux-hardware.org/?probe=73b04f9de4) | Aug 26, 2020 |
| Acer      | Aspire 5742G                | [a90fb35c67](https://linux-hardware.org/?probe=a90fb35c67) | May 01, 2020 |
| Lenovo    | ThinkPad T60 2007FUG        | [d552e50d7e](https://linux-hardware.org/?probe=d552e50d7e) | Mar 12, 2020 |
| Dell      | Latitude XT3                | [0944e88882](https://linux-hardware.org/?probe=0944e88882) | Mar 09, 2020 |
| Dell      | Inspiron 5770               | [a3dd71465d](https://linux-hardware.org/?probe=a3dd71465d) | Jan 06, 2020 |
| HP        | Pavilion dv9000 (GA359UA... | [db4a924be0](https://linux-hardware.org/?probe=db4a924be0) | Sep 07, 2019 |
| HP        | Pavilion dv9000 (GA359UA... | [6f024c0dd0](https://linux-hardware.org/?probe=6f024c0dd0) | Sep 03, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Sparky 6    | 8         | 30.77%  |
| Sparky 6.1  | 4         | 15.38%  |
| Sparky 7    | 3         | 11.54%  |
| Sparky 5.14 | 3         | 11.54%  |
| Sparky 6.0  | 2         | 7.69%   |
| Sparky 5.13 | 2         | 7.69%   |
| Sparky 5.12 | 2         | 7.69%   |
| Sparky 5.10 | 2         | 7.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Sparky | 24        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 5.17.0-1-amd64      | 2         | 7.14%   |
| 5.10.0-9-amd64      | 2         | 7.14%   |
| 5.10.0-8-amd64      | 2         | 7.14%   |
| 5.10.0-11-686       | 2         | 7.14%   |
| 4.19.0-8-amd64      | 2         | 7.14%   |
| 4.19.0-13-686       | 2         | 7.14%   |
| 4.19.0-12-amd64     | 2         | 7.14%   |
| 5.9.0-4-amd64       | 1         | 3.57%   |
| 5.8.13-sparky-amd64 | 1         | 3.57%   |
| 5.8.0-2-amd64       | 1         | 3.57%   |
| 5.5.0-2-amd64       | 1         | 3.57%   |
| 5.4.7-sparky-amd64  | 1         | 3.57%   |
| 5.2.0-2-amd64       | 1         | 3.57%   |
| 5.16.0-5-amd64      | 1         | 3.57%   |
| 5.15.0-3-amd64      | 1         | 3.57%   |
| 5.14.0-4-amd64      | 1         | 3.57%   |
| 5.10.4-sparky-amd64 | 1         | 3.57%   |
| 5.10.0-6-amd64      | 1         | 3.57%   |
| 5.10.0-3-amd64      | 1         | 3.57%   |
| 4.19.0-14-686       | 1         | 3.57%   |
| 4.19.0-10-686       | 1         | 3.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 8         | 30.77%  |
| 4.19.0  | 6         | 23.08%  |
| 5.17.0  | 2         | 7.69%   |
| 5.9.0   | 1         | 3.85%   |
| 5.8.13  | 1         | 3.85%   |
| 5.8.0   | 1         | 3.85%   |
| 5.5.0   | 1         | 3.85%   |
| 5.4.7   | 1         | 3.85%   |
| 5.2.0   | 1         | 3.85%   |
| 5.16.0  | 1         | 3.85%   |
| 5.15.0  | 1         | 3.85%   |
| 5.14.0  | 1         | 3.85%   |
| 5.10.4  | 1         | 3.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 9         | 34.62%  |
| 4.19    | 6         | 23.08%  |
| 5.8     | 2         | 7.69%   |
| 5.17    | 2         | 7.69%   |
| 5.9     | 1         | 3.85%   |
| 5.5     | 1         | 3.85%   |
| 5.4     | 1         | 3.85%   |
| 5.2     | 1         | 3.85%   |
| 5.16    | 1         | 3.85%   |
| 5.15    | 1         | 3.85%   |
| 5.14    | 1         | 3.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 20        | 83.33%  |
| i686   | 4         | 16.67%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| XFCE    | 8         | 32%     |
| LXQt    | 7         | 28%     |
| Unknown | 6         | 24%     |
| openbox | 1         | 4%      |
| MATE    | 1         | 4%      |
| KDE5    | 1         | 4%      |
| GNOME   | 1         | 4%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 22        | 88%     |
| Tty  | 3         | 12%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| TDM     | 6         | 25%     |
| LightDM | 6         | 25%     |
| Unknown | 6         | 25%     |
| SDDM    | 4         | 16.67%  |
| XDM     | 1         | 4.17%   |
| GDM     | 1         | 4.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 8         | 33.33%  |
| pl_PL   | 3         | 12.5%   |
| en_GB   | 3         | 12.5%   |
| fr_FR   | 2         | 8.33%   |
| Unknown | 2         | 8.33%   |
| ja_JP   | 1         | 4.17%   |
| es_CL   | 1         | 4.17%   |
| en_PH   | 1         | 4.17%   |
| en_IN   | 1         | 4.17%   |
| en_CA   | 1         | 4.17%   |
| de_DE   | 1         | 4.17%   |

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


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 21        | 87.5%   |
| Overlay | 2         | 8.33%   |
| Btrfs   | 1         | 4.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 10        | 41.67%  |
| GPT     | 7         | 29.17%  |
| Unknown | 7         | 29.17%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 21        | 87.5%   |
| Yes       | 3         | 12.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 16        | 66.67%  |
| Yes       | 8         | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 7         | 29.17%  |
| Lenovo              | 5         | 20.83%  |
| Dell                | 4         | 16.67%  |
| ASUSTek Computer    | 2         | 8.33%   |
| Samsung Electronics | 1         | 4.17%   |
| Google              | 1         | 4.17%   |
| eMachines           | 1         | 4.17%   |
| Beelink             | 1         | 4.17%   |
| Apple               | 1         | 4.17%   |
| Acer                | 1         | 4.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Samsung NC10                     | 1         | 4.17%   |
| Lenovo ThinkPad T61 7659AB7      | 1         | 4.17%   |
| Lenovo ThinkPad T60 2007FUG      | 1         | 4.17%   |
| Lenovo ThinkPad E15 20RES0GF00   | 1         | 4.17%   |
| Lenovo IdeaPad S206 20154        | 1         | 4.17%   |
| Lenovo G50-30 80G0               | 1         | 4.17%   |
| HP Pavilion g7                   | 1         | 4.17%   |
| HP Pavilion dv9000 (GA359UA#ABA) | 1         | 4.17%   |
| HP Pavilion dv5                  | 1         | 4.17%   |
| HP Laptop 17z-ca100              | 1         | 4.17%   |
| HP EliteBook Folio 9480m         | 1         | 4.17%   |
| HP EliteBook 8770w               | 1         | 4.17%   |
| HP EliteBook 745 G3              | 1         | 4.17%   |
| Google Banon                     | 1         | 4.17%   |
| eMachines E525                   | 1         | 4.17%   |
| Dell Latitude XT3                | 1         | 4.17%   |
| Dell Inspiron N5010              | 1         | 4.17%   |
| Dell Inspiron 5770               | 1         | 4.17%   |
| Dell Inspiron 5720               | 1         | 4.17%   |
| Beelink BT3 PRO                  | 1         | 4.17%   |
| ASUS S101                        | 1         | 4.17%   |
| ASUS 1000HE                      | 1         | 4.17%   |
| Apple MacBook1,1                 | 1         | 4.17%   |
| Acer Aspire 5742G                | 1         | 4.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Lenovo ThinkPad | 3         | 12.5%   |
| HP Pavilion     | 3         | 12.5%   |
| HP EliteBook    | 3         | 12.5%   |
| Dell Inspiron   | 3         | 12.5%   |
| Samsung NC10    | 1         | 4.17%   |
| Lenovo IdeaPad  | 1         | 4.17%   |
| Lenovo G50-30   | 1         | 4.17%   |
| HP Laptop       | 1         | 4.17%   |
| Google Banon    | 1         | 4.17%   |
| eMachines E525  | 1         | 4.17%   |
| Dell Latitude   | 1         | 4.17%   |
| Beelink BT3     | 1         | 4.17%   |
| ASUS S101       | 1         | 4.17%   |
| ASUS 1000HE     | 1         | 4.17%   |
| Apple MacBook1  | 1         | 4.17%   |
| Acer Aspire     | 1         | 4.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 3         | 12.5%   |
| 2009 | 3         | 12.5%   |
| 2008 | 3         | 12.5%   |
| 2014 | 2         | 8.33%   |
| 2011 | 2         | 8.33%   |
| 2010 | 2         | 8.33%   |
| 2006 | 2         | 8.33%   |
| 2021 | 1         | 4.17%   |
| 2020 | 1         | 4.17%   |
| 2019 | 1         | 4.17%   |
| 2018 | 1         | 4.17%   |
| 2017 | 1         | 4.17%   |
| 2016 | 1         | 4.17%   |
| 2007 | 1         | 4.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 24        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 24        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 23        | 95.83%  |
| Yes  | 1         | 4.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 9         | 37.5%   |
| 4.01-8.0   | 5         | 20.83%  |
| 2.01-3.0   | 4         | 16.67%  |
| 1.01-2.0   | 2         | 8.33%   |
| 32.01-64.0 | 1         | 4.17%   |
| 24.01-32.0 | 1         | 4.17%   |
| 16.01-24.0 | 1         | 4.17%   |
| 0.51-1.0   | 1         | 4.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.51-1.0 | 8         | 30.77%  |
| 1.01-2.0 | 6         | 23.08%  |
| 2.01-3.0 | 5         | 19.23%  |
| 4.01-8.0 | 3         | 11.54%  |
| 3.01-4.0 | 2         | 7.69%   |
| 0.01-0.5 | 2         | 7.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 19        | 79.17%  |
| 2      | 3         | 12.5%   |
| 5      | 1         | 4.17%   |
| 4      | 1         | 4.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 13        | 54.17%  |
| Yes       | 11        | 45.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 91.67%  |
| No        | 2         | 8.33%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 91.67%  |
| No        | 2         | 8.33%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 62.5%   |
| No        | 9         | 37.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 8         | 33.33%  |
| UK          | 3         | 12.5%   |
| Poland      | 3         | 12.5%   |
| Germany     | 2         | 8.33%   |
| France      | 2         | 8.33%   |
| Canada      | 2         | 8.33%   |
| Philippines | 1         | 4.17%   |
| Japan       | 1         | 4.17%   |
| India       | 1         | 4.17%   |
| Chile       | 1         | 4.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Wenatchee      | 1         | 3.7%    |
| Tucson         | 1         | 3.7%    |
| Takahama       | 1         | 3.7%    |
| Spokane        | 1         | 3.7%    |
| San Antonio    | 1         | 3.7%    |
| Sainte-Julie   | 1         | 3.7%    |
| Quezon City    | 1         | 3.7%    |
| Pujaudran      | 1         | 3.7%    |
| Puente Alto    | 1         | 3.7%    |
| Pompano Beach  | 1         | 3.7%    |
| Montreuil      | 1         | 3.7%    |
| Montreal       | 1         | 3.7%    |
| Miekoszyn      | 1         | 3.7%    |
| Mannheim       | 1         | 3.7%    |
| Liverpool      | 1         | 3.7%    |
| Leipzig        | 1         | 3.7%    |
| Koło          | 1         | 3.7%    |
| Houston        | 1         | 3.7%    |
| Gmina Bolków  | 1         | 3.7%    |
| Glasgow        | 1         | 3.7%    |
| East Wenatchee | 1         | 3.7%    |
| Dunoon         | 1         | 3.7%    |
| Dobrzen Wielki | 1         | 3.7%    |
| Dehradun       | 1         | 3.7%    |
| Chicago        | 1         | 3.7%    |
| Birmingham     | 1         | 3.7%    |
| Barnsley       | 1         | 3.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 10     | 19.35%  |
| Samsung Electronics | 4         | 4      | 12.9%   |
| Hitachi             | 4         | 5      | 12.9%   |
| WDC                 | 3         | 5      | 9.68%   |
| Unknown             | 2         | 2      | 6.45%   |
| GOODRAM             | 2         | 4      | 6.45%   |
| SPCC                | 1         | 2      | 3.23%   |
| ORICO               | 1         | 1      | 3.23%   |
| Netac               | 1         | 1      | 3.23%   |
| Micron Technology   | 1         | 1      | 3.23%   |
| Intel               | 1         | 1      | 3.23%   |
| Fujitsu             | 1         | 2      | 3.23%   |
| Crucial             | 1         | 1      | 3.23%   |
| ASUS-JM             | 1         | 1      | 3.23%   |
| asmedia             | 1         | 1      | 3.23%   |
| A-DATA Technology   | 1         | 1      | 3.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Hitachi HTS545025B9A300 250GB            | 2         | 6.06%   |
| WDC WD5000BEVT-22ZAT0 500GB              | 1         | 3.03%   |
| WDC WD3200BPVT-75ZEST0 320GB             | 1         | 3.03%   |
| WDC WD1600BEVT-22ZCT0 160GB              | 1         | 3.03%   |
| Unknown MMC Card  64GB                   | 1         | 3.03%   |
| Unknown HBG4a2  32GB                     | 1         | 3.03%   |
| SPCC Solid State Disk 256GB              | 1         | 3.03%   |
| Seagate ST9500325AS 500GB                | 1         | 3.03%   |
| Seagate ST9160310AS 160GB                | 1         | 3.03%   |
| Seagate ST1000LM048-2E7172 1TB           | 1         | 3.03%   |
| Seagate ST1000LM035-1RK172 1TB           | 1         | 3.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 3.03%   |
| Seagate Backup+ Hub BK 8TB               | 1         | 3.03%   |
| Seagate Backup+ Desk 5TB                 | 1         | 3.03%   |
| Samsung SSD 840 Series 120GB             | 1         | 3.03%   |
| Samsung NVMe SSD Drive 256GB             | 1         | 3.03%   |
| Samsung MZALQ512HALU-000L1 512GB         | 1         | 3.03%   |
| Samsung MZ7TD128HAFV-000L1 128GB SSD     | 1         | 3.03%   |
| ORICO M200 1TB                           | 1         | 3.03%   |
| Netac SSD 256GB                          | 1         | 3.03%   |
| Micron MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 3.03%   |
| Intel SSDMAEXC024G3H 24GB                | 1         | 3.03%   |
| Hitachi HTS545025B9SA02 250GB            | 1         | 3.03%   |
| Hitachi HTS541080G9SA00 80GB             | 1         | 3.03%   |
| GOODRAM SSDPR-CX400-256-G2 256GB         | 1         | 3.03%   |
| GOODRAM SSDPR-CL100-240-G3 240GB         | 1         | 3.03%   |
| GOODRAM IR-SSDPR-S25A-120 120GB          | 1         | 3.03%   |
| Fujitsu MHW2120BH 120GB                  | 1         | 3.03%   |
| Crucial CT250MX500SSD1 250GB             | 1         | 3.03%   |
| ASUS-JM S41 SSD 16GB                     | 1         | 3.03%   |
| asmedia ASMT1153e 1TB                    | 1         | 3.03%   |
| A-DATA SX8200NP 480GB                    | 1         | 3.03%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 9      | 40%     |
| Hitachi | 4         | 5      | 26.67%  |
| WDC     | 3         | 5      | 20%     |
| Fujitsu | 1         | 2      | 6.67%   |
| asmedia | 1         | 1      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 20%     |
| GOODRAM             | 2         | 4      | 20%     |
| SPCC                | 1         | 2      | 10%     |
| Netac               | 1         | 1      | 10%     |
| Micron Technology   | 1         | 1      | 10%     |
| Intel               | 1         | 1      | 10%     |
| Crucial             | 1         | 1      | 10%     |
| ASUS-JM             | 1         | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 14        | 22     | 48.28%  |
| SSD     | 8         | 13     | 27.59%  |
| NVMe    | 3         | 3      | 10.34%  |
| MMC     | 2         | 2      | 6.9%    |
| Unknown | 2         | 2      | 6.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 20        | 32     | 74.07%  |
| NVMe | 3         | 3      | 11.11%  |
| SAS  | 2         | 5      | 7.41%   |
| MMC  | 2         | 2      | 7.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 17        | 27     | 80.95%  |
| 0.51-1.0   | 3         | 5      | 14.29%  |
| 4.01-10.0  | 1         | 3      | 4.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 10        | 41.67%  |
| 501-1000       | 4         | 16.67%  |
| 1-20           | 3         | 12.5%   |
| 251-500        | 2         | 8.33%   |
| 21-50          | 2         | 8.33%   |
| More than 3000 | 1         | 4.17%   |
| 1001-2000      | 1         | 4.17%   |
| Unknown        | 1         | 4.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 11        | 42.31%  |
| 21-50          | 4         | 15.38%  |
| 51-100         | 3         | 11.54%  |
| 101-250        | 2         | 7.69%   |
| 501-1000       | 2         | 7.69%   |
| More than 3000 | 1         | 3.85%   |
| 251-500        | 1         | 3.85%   |
| 1001-2000      | 1         | 3.85%   |
| Unknown        | 1         | 3.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22ZAT0 500GB                         | 1         | 1      | 20%     |
| WDC WD3200BPVT-75ZEST0 320GB                        | 1         | 1      | 20%     |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 20%     |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 20%     |
| asmedia ASMT1153e 1TB                               | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 2         | 2      | 40%     |
| Seagate           | 1         | 1      | 20%     |
| Micron Technology | 1         | 1      | 20%     |
| asmedia           | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 50%     |
| Seagate | 1         | 1      | 25%     |
| asmedia | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 80%     |
| SSD  | 1         | 1      | 20%     |

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
| Works    | 12        | 22     | 46.15%  |
| Detected | 9         | 15     | 34.62%  |
| Malfunc  | 5         | 5      | 19.23%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 18        | 72%     |
| Samsung Electronics | 2         | 8%      |
| AMD                 | 2         | 8%      |
| Silicon Motion      | 1         | 4%      |
| Nvidia              | 1         | 4%      |
| JMicron Technology  | 1         | 4%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 3         | 10.34%  |
| Samsung NVMe SSD Controller 980                                              | 2         | 6.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 6.9%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]               | 2         | 6.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 2         | 6.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 2         | 6.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 2         | 6.9%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                | 1         | 3.45%   |
| Nvidia MCP51 Serial ATA Controller                                           | 1         | 3.45%   |
| Nvidia MCP51 IDE                                                             | 1         | 3.45%   |
| JMicron JMB360 AHCI Controller                                               | 1         | 3.45%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 1         | 3.45%   |
| Intel Comet Lake SATA AHCI Controller                                        | 1         | 3.45%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 1         | 3.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 1         | 3.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 1         | 3.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 3.45%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 1         | 3.45%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 1         | 3.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 1         | 3.45%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 1         | 3.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 17        | 62.96%  |
| IDE  | 7         | 25.93%  |
| NVMe | 3         | 11.11%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 20        | 83.33%  |
| AMD    | 4         | 16.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz                 | 2         | 8.33%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 4.17%   |
| Intel Genuine CPU T2400 @ 1.83GHz             | 1         | 4.17%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 4.17%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 4.17%   |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 1         | 4.17%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 4.17%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 4.17%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 4.17%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 4.17%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 4.17%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 4.17%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 1         | 4.17%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 1         | 4.17%   |
| Intel Celeron CPU N3160 @ 1.60GHz             | 1         | 4.17%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 4.17%   |
| Intel Celeron CPU 900 @ 2.20GHz               | 1         | 4.17%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 4.17%   |
| Intel Atom CPU N280 @ 1.66GHz                 | 1         | 4.17%   |
| AMD Turion 64 X2 Mobile Technology TL-64      | 1         | 4.17%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 4.17%   |
| AMD PRO A10-8700B R6, 10 Compute Cores 4C+6G  | 1         | 4.17%   |
| AMD C-50 Processor                            | 1         | 4.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 4         | 16.67%  |
| Intel Atom              | 4         | 16.67%  |
| Intel Core i7           | 3         | 12.5%   |
| Intel Celeron           | 3         | 12.5%   |
| Intel Core 2 Duo        | 2         | 8.33%   |
| Intel Pentium           | 1         | 4.17%   |
| Intel Genuine           | 1         | 4.17%   |
| Intel Core i3           | 1         | 4.17%   |
| Intel Core 2            | 1         | 4.17%   |
| AMD Turion 64 X2 Mobile | 1         | 4.17%   |
| AMD Ryzen 5             | 1         | 4.17%   |
| AMD PRO A10             | 1         | 4.17%   |
| AMD C-50                | 1         | 4.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 13        | 54.17%  |
| 4      | 7         | 29.17%  |
| 1      | 4         | 16.67%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 24        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 13        | 54.17%  |
| 1      | 11        | 45.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 20        | 83.33%  |
| 32-bit         | 4         | 16.67%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4         | 16.67%  |
| 0x406c4    | 2         | 8.33%   |
| 0x306a9    | 2         | 8.33%   |
| 0x206a7    | 2         | 8.33%   |
| 0x20655    | 2         | 8.33%   |
| 0x106c2    | 2         | 8.33%   |
| 0x806ec    | 1         | 4.17%   |
| 0x806ea    | 1         | 4.17%   |
| 0x6f2      | 1         | 4.17%   |
| 0x40651    | 1         | 4.17%   |
| 0x30678    | 1         | 4.17%   |
| 0x1067a    | 1         | 4.17%   |
| 0x10676    | 1         | 4.17%   |
| 0x08108109 | 1         | 4.17%   |
| 0x0600611a | 1         | 4.17%   |
| 0x05000029 | 1         | 4.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Silvermont  | 3         | 12.5%   |
| Bonnell     | 3         | 12.5%   |
| Westmere    | 2         | 8.33%   |
| SandyBridge | 2         | 8.33%   |
| Penryn      | 2         | 8.33%   |
| KabyLake    | 2         | 8.33%   |
| IvyBridge   | 2         | 8.33%   |
| Core        | 2         | 8.33%   |
| Zen+        | 1         | 4.17%   |
| P6          | 1         | 4.17%   |
| K8 Hammer   | 1         | 4.17%   |
| Haswell     | 1         | 4.17%   |
| Excavator   | 1         | 4.17%   |
| Bobcat      | 1         | 4.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 16        | 66.67%  |
| Nvidia | 4         | 16.67%  |
| AMD    | 4         | 16.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 13.79%  |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 10.34%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 6.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 6.9%    |
| Nvidia GK104GLM [Quadro K3000M]                                                          | 1         | 3.45%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 3.45%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 3.45%   |
| Nvidia C51 [GeForce Go 6150]                                                             | 1         | 3.45%   |
| Intel UHD Graphics 620                                                                   | 1         | 3.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 3.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 3.45%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 3.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 3.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 3.45%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 3.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 3.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 3.45%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 3.45%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 3.45%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 3.45%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 1         | 3.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 3.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| 1 x Intel  | 16        | 66.67%  |
| 1 x Nvidia | 4         | 16.67%  |
| 1 x AMD    | 4         | 16.67%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 23        | 95.83%  |
| Proprietary | 1         | 4.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 70.83%  |
| 0.01-0.5   | 4         | 16.67%  |
| 1.01-2.0   | 2         | 8.33%   |
| 0.51-1.0   | 1         | 4.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 6         | 25%     |
| Chimei Innolux      | 3         | 12.5%   |
| AU Optronics        | 3         | 12.5%   |
| Samsung Electronics | 2         | 8.33%   |
| Lenovo              | 2         | 8.33%   |
| CPT                 | 2         | 8.33%   |
| LG Philips          | 1         | 4.17%   |
| Insignia            | 1         | 4.17%   |
| Hitachi             | 1         | 4.17%   |
| HannStar            | 1         | 4.17%   |
| BOE                 | 1         | 4.17%   |
| Apple               | 1         | 4.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S24D330 SAM0D93 1920x1080 531x299mm 24.0-inch    | 1         | 4%      |
| Samsung Electronics LCD Monitor SEC4F45 1280x800 331x207mm 15.4-inch | 1         | 4%      |
| Samsung Electronics LCD Monitor SEC4141 1366x768 344x193mm 15.5-inch | 1         | 4%      |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch          | 1         | 4%      |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch        | 1         | 4%      |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch         | 1         | 4%      |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch          | 1         | 4%      |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch          | 1         | 4%      |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch          | 1         | 4%      |
| LG Display LCD Monitor LGD01C5 1366x768 293x165mm 13.2-inch          | 1         | 4%      |
| Lenovo LCD Monitor LEN4033 1440x900 303x190mm 14.1-inch              | 1         | 4%      |
| Lenovo LCD Monitor LEN4022 1400x1050 287x215mm 14.1-inch             | 1         | 4%      |
| Insignia DX-32D20SNA14 BBY0032 1360x768 544x326mm 25.0-inch          | 1         | 4%      |
| Hitachi HDMI HEC0088 1920x540                                        | 1         | 4%      |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 1         | 4%      |
| CPT LCD Monitor CPT04CE 1024x600 222x130mm 10.1-inch                 | 1         | 4%      |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                 | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch     | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch     | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x174mm 14.0-inch      | 1         | 4%      |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                | 1         | 4%      |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch       | 1         | 4%      |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch        | 1         | 4%      |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch       | 1         | 4%      |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 1         | 4%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 7         | 28%     |
| 1366x768 (WXGA)  | 5         | 20%     |
| 1600x900 (HD+)   | 3         | 12%     |
| 1024x600         | 3         | 12%     |
| 1920x540         | 2         | 8%      |
| 1440x900 (WXGA+) | 2         | 8%      |
| 1280x800 (WXGA)  | 2         | 8%      |
| 1400x1050        | 1         | 4%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 7         | 28%     |
| 17     | 6         | 24%     |
| 14     | 3         | 12%     |
| 13     | 3         | 12%     |
| 10     | 3         | 12%     |
| 48     | 2         | 8%      |
| 24     | 1         | 4%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 10        | 40%     |
| 351-400     | 6         | 24%     |
| 201-300     | 6         | 24%     |
| 1001-1500   | 2         | 8%      |
| 501-600     | 1         | 4%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 18        | 72%     |
| 16/10 | 4         | 16%     |
| 1.96  | 2         | 8%      |
| 4/3   | 1         | 4%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 7         | 28%     |
| 121-130        | 5         | 20%     |
| 81-90          | 3         | 12%     |
| 41-50          | 3         | 12%     |
| 71-80          | 2         | 8%      |
| 501-1000       | 2         | 8%      |
| 201-250        | 1         | 4%      |
| 131-140        | 1         | 4%      |
| 91-100         | 1         | 4%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 11        | 45.83%  |
| 121-160 | 9         | 37.5%   |
| 1-50    | 2         | 8.33%   |
| 51-100  | 2         | 8.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 23        | 95.83%  |
| 2     | 1         | 4.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 11        | 30.56%  |
| Realtek Semiconductor    | 9         | 25%     |
| Qualcomm Atheros         | 7         | 19.44%  |
| Marvell Technology Group | 2         | 5.56%   |
| Broadcom Limited         | 2         | 5.56%   |
| Broadcom                 | 2         | 5.56%   |
| TP-Link                  | 1         | 2.78%   |
| Ralink                   | 1         | 2.78%   |
| Nvidia                   | 1         | 2.78%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 5         | 11.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 4         | 8.89%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 4.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 4.44%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 4.44%   |
| Intel Wireless 7265                                                     | 2         | 4.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 4.44%   |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 2.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 2.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 2.22%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 2.22%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 2.22%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 2.22%   |
| Nvidia MCP51 Ethernet Controller                                        | 1         | 2.22%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 1         | 2.22%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 1         | 2.22%   |
| Intel Wireless 7260                                                     | 1         | 2.22%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 2.22%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 2.22%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 2.22%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 2.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 2.22%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 2.22%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 2.22%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 2.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 2.22%   |
| Intel 82573L Gigabit Ethernet Controller                                | 1         | 2.22%   |
| Intel 82566MM Gigabit Network Connection                                | 1         | 2.22%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                        | 1         | 2.22%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 1         | 2.22%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 1         | 2.22%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 2.22%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 11        | 47.83%  |
| Qualcomm Atheros      | 6         | 26.09%  |
| Realtek Semiconductor | 2         | 8.7%    |
| Broadcom Limited      | 2         | 8.7%    |
| TP-Link               | 1         | 4.35%   |
| Ralink                | 1         | 4.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 8.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 8.7%    |
| Intel Wireless 7265                                                     | 2         | 8.7%    |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 4.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 4.35%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 4.35%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 4.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 4.35%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 4.35%   |
| Intel Wireless 7260                                                     | 1         | 4.35%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 4.35%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 4.35%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 4.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 4.35%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 4.35%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 4.35%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 4.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 4.35%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 1         | 4.35%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 4.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 9         | 40.91%  |
| Intel                    | 5         | 22.73%  |
| Qualcomm Atheros         | 3         | 13.64%  |
| Marvell Technology Group | 2         | 9.09%   |
| Broadcom                 | 2         | 9.09%   |
| Nvidia                   | 1         | 4.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 22.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 18.18%  |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 9.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 9.09%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 4.55%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 4.55%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 4.55%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 4.55%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 4.55%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 4.55%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 4.55%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 4.55%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 4.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 22        | 50%     |
| Ethernet | 22        | 50%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 19        | 73.08%  |
| Ethernet | 7         | 26.92%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 20        | 83.33%  |
| 1     | 4         | 16.67%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 21        | 80.77%  |
| Yes  | 5         | 19.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 5         | 33.33%  |
| Broadcom                        | 3         | 20%     |
| Realtek Semiconductor           | 2         | 13.33%  |
| Qualcomm Atheros Communications | 1         | 6.67%   |
| Dell                            | 1         | 6.67%   |
| Cambridge Silicon Radio         | 1         | 6.67%   |
| ASUSTek Computer                | 1         | 6.67%   |
| Apple                           | 1         | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 3         | 20%     |
| Realtek RTL8723B Bluetooth                          | 1         | 6.67%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 6.67%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 6.67%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 6.67%   |
| Intel AX201 Bluetooth                               | 1         | 6.67%   |
| Dell Wireless 365 Bluetooth                         | 1         | 6.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 6.67%   |
| Broadcom HP Portable SoftSailing                    | 1         | 6.67%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 6.67%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 6.67%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 6.67%   |
| Apple Bluetooth HCI                                 | 1         | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel              | 19        | 70.37%  |
| Nvidia             | 3         | 11.11%  |
| AMD                | 3         | 11.11%  |
| Native Instruments | 1         | 3.7%    |
| Focusrite-Novation | 1         | 3.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 16.13%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 6.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 6.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 6.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 6.45%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 3.23%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 3.23%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 3.23%   |
| Native Instruments KOMPLETE KONTROL M32                                                           | 1         | 3.23%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1         | 3.23%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 3.23%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 3.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 3.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 3.23%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 3.23%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 3.23%   |
| Focusrite-Novation Focusrite Scarlett 2i2 2nd Gen                                                 | 1         | 3.23%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 3.23%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 3.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 3.23%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 3.23%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 3.23%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 3.23%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 30%     |
| Unknown             | 3         | 15%     |
| SK Hynix            | 3         | 15%     |
| Nanya Technology    | 2         | 10%     |
| Micron Technology   | 2         | 10%     |
| Kingston            | 1         | 5%      |
| GOODRAM             | 1         | 5%      |
| G.Skill             | 1         | 5%      |
| Corsair             | 1         | 5%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM SDRAM                      | 1         | 4.55%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                 | 1         | 4.55%   |
| Unknown RAM Module 1024MB SODIMM DDR2                    | 1         | 4.55%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                 | 1         | 4.55%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1066MT/s             | 1         | 4.55%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s  | 1         | 4.55%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 1         | 4.55%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s              | 1         | 4.55%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s    | 1         | 4.55%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s    | 1         | 4.55%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s    | 1         | 4.55%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 1         | 4.55%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s    | 1         | 4.55%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s          | 1         | 4.55%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s     | 1         | 4.55%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s     | 1         | 4.55%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s | 1         | 4.55%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s   | 1         | 4.55%   |
| Kingston RAM ACR128X64D3S1333C9 1GB SODIMM DDR3 1333MT/s | 1         | 4.55%   |
| GOODRAM RAM GR1600S3V64L11/8G 8GB SODIMM DDR3 1600MT/s   | 1         | 4.55%   |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s   | 1         | 4.55%   |
| Corsair RAM CMSA4GX3M1A1333C9 4GB SODIMM DDR3 1333MT/s   | 1         | 4.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 11        | 61.11%  |
| SDRAM   | 2         | 11.11%  |
| DDR4    | 2         | 11.11%  |
| LPDDR3  | 1         | 5.56%   |
| DDR2    | 1         | 5.56%   |
| Unknown | 1         | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SODIMM  | 16        | 94.12%  |
| Unknown | 1         | 5.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 7         | 33.33%  |
| 2048  | 6         | 28.57%  |
| 8192  | 3         | 14.29%  |
| 1024  | 3         | 14.29%  |
| 16384 | 2         | 9.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 7         | 36.84%  |
| 2667    | 2         | 10.53%  |
| 1334    | 2         | 10.53%  |
| 1333    | 2         | 10.53%  |
| Unknown | 2         | 10.53%  |
| 4199    | 1         | 5.26%   |
| 1867    | 1         | 5.26%   |
| 1066    | 1         | 5.26%   |
| 800     | 1         | 5.26%   |

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
| Chicony Electronics                    | 7         | 36.84%  |
| Microdia                               | 4         | 21.05%  |
| Sunplus Innovation Technology          | 2         | 10.53%  |
| Acer                                   | 2         | 10.53%  |
| Z-Star Microelectronics                | 1         | 5.26%   |
| Suyin                                  | 1         | 5.26%   |
| Microsoft                              | 1         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Z-Star Namuga 1.3M Webcam                                   | 1         | 5.26%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 5.26%   |
| Sunplus Integrated Webcam                                   | 1         | 5.26%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 5.26%   |
| Microsoft LifeCam Cinema                                    | 1         | 5.26%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 5.26%   |
| Microdia Lenovo EasyCamera                                  | 1         | 5.26%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 5.26%   |
| Microdia Laptop_Integrated_Webcam_1.3M                      | 1         | 5.26%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 5.26%   |
| Chicony HP TrueVision HD Camera                             | 1         | 5.26%   |
| Chicony HP Integrated Webcam                                | 1         | 5.26%   |
| Chicony HP HD Webcam                                        | 1         | 5.26%   |
| Chicony HD WebCam                                           | 1         | 5.26%   |
| Chicony Asus Integrated 0.3M UVC Webcam                     | 1         | 5.26%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 1         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 1         | 5.26%   |
| Acer Lenovo EasyCamera                                      | 1         | 5.26%   |
| Acer HP Webcam                                              | 1         | 5.26%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 3         | 75%     |
| STMicroelectronics | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 1         | 25%     |
| Validity Sensors VFS491                    | 1         | 25%     |
| Validity Sensors VFS101 Fingerprint Reader | 1         | 25%     |
| STMicroelectronics Fingerprint Reader      | 1         | 25%     |

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
| 0     | 15        | 62.5%   |
| 1     | 7         | 29.17%  |
| 2     | 2         | 8.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 4         | 36.36%  |
| Net/wireless          | 2         | 18.18%  |
| Multimedia controller | 2         | 18.18%  |
| Graphics card         | 2         | 18.18%  |
| Chipcard              | 1         | 9.09%   |

