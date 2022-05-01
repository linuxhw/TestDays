antiX - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for antiX.

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

Total: 29

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Packard Be... | EasyNote_MX37-U-057NL       | [41760b3852](https://linux-hardware.org/?probe=41760b3852) | Apr 27, 2022 |
| Apple         | MacBook7,1                  | [70413280df](https://linux-hardware.org/?probe=70413280df) | Mar 26, 2022 |
| HP            | EliteBook 2570p             | [20e998c205](https://linux-hardware.org/?probe=20e998c205) | Mar 17, 2022 |
| IBM           | ThinkPad T40 237342G        | [2c96b391e2](https://linux-hardware.org/?probe=2c96b391e2) | Jan 16, 2022 |
| IBM           | ThinkPad T40 237342G        | [5c4e8748ef](https://linux-hardware.org/?probe=5c4e8748ef) | Jan 16, 2022 |
| Toshiba       | Satellite 1905              | [e72b9043c8](https://linux-hardware.org/?probe=e72b9043c8) | Jan 14, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3RH0... | [b2a71d3bbe](https://linux-hardware.org/?probe=b2a71d3bbe) | Dec 30, 2021 |
| ASUSTek       | X71SL                       | [42e7b57eb8](https://linux-hardware.org/?probe=42e7b57eb8) | Dec 07, 2021 |
| ASUSTek       | A3L                         | [32489f1764](https://linux-hardware.org/?probe=32489f1764) | Dec 06, 2021 |
| ASUSTek       | A3L                         | [2b01c636c2](https://linux-hardware.org/?probe=2b01c636c2) | Dec 06, 2021 |
| ASUSTek       | X51RL                       | [0aeee18806](https://linux-hardware.org/?probe=0aeee18806) | Nov 19, 2021 |
| Acer          | AOA150                      | [24833c6a59](https://linux-hardware.org/?probe=24833c6a59) | Oct 26, 2021 |
| Dell          | Latitude E6400              | [6b7ef9cad5](https://linux-hardware.org/?probe=6b7ef9cad5) | Oct 21, 2021 |
| MSI           | GE62 7RE                    | [9d064bcc8d](https://linux-hardware.org/?probe=9d064bcc8d) | May 21, 2021 |
| MSI           | GE62 7RE                    | [d560e067d4](https://linux-hardware.org/?probe=d560e067d4) | May 21, 2021 |
| HP            | EliteBook 8770w             | [0af42b4958](https://linux-hardware.org/?probe=0af42b4958) | Mar 17, 2021 |
| Fujitsu       | FMVS54EB                    | [f01ca3644f](https://linux-hardware.org/?probe=f01ca3644f) | Mar 11, 2021 |
| Dell          | Latitude 5480               | [c9e0b19e8b](https://linux-hardware.org/?probe=c9e0b19e8b) | Mar 07, 2021 |
| HP            | Mini 110-3700               | [33a6e65493](https://linux-hardware.org/?probe=33a6e65493) | Jan 06, 2021 |
| IBM           | ThinkPad T41 2374K50        | [c77530ec4e](https://linux-hardware.org/?probe=c77530ec4e) | Nov 19, 2020 |
| IBM           | ThinkPad T41 2374K50        | [9c27b878ae](https://linux-hardware.org/?probe=9c27b878ae) | Nov 17, 2020 |
| IBM           | ThinkPad T43 2668WEJ        | [c7508c3b5c](https://linux-hardware.org/?probe=c7508c3b5c) | Oct 02, 2020 |
| HP            | Pavilion dv2700             | [312d41f446](https://linux-hardware.org/?probe=312d41f446) | Aug 01, 2020 |
| HP            | Mini 5101                   | [c0abbe79e6](https://linux-hardware.org/?probe=c0abbe79e6) | Apr 24, 2020 |
| HP            | Mini 5101                   | [8fd41129bc](https://linux-hardware.org/?probe=8fd41129bc) | Apr 24, 2020 |
| ASUSTek       | 900A                        | [9ab5761eb1](https://linux-hardware.org/?probe=9ab5761eb1) | Apr 05, 2020 |
| ASUSTek       | 900HA                       | [39b2bfbefc](https://linux-hardware.org/?probe=39b2bfbefc) | Mar 21, 2020 |
| Medion        | WIM2170                     | [a8c4771b62](https://linux-hardware.org/?probe=a8c4771b62) | Jan 13, 2020 |
| Medion        | WIM2170                     | [c879195021](https://linux-hardware.org/?probe=c879195021) | Jan 13, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| antiX 21       | 6         | 26.09%  |
| antiX 19.2     | 6         | 26.09%  |
| antiX 19.3     | 3         | 13.04%  |
| antiX 19.4     | 2         | 8.7%    |
| antiX 19.1     | 2         | 8.7%    |
| antiX 21-runit | 1         | 4.35%   |
| antiX 17.4.1   | 1         | 4.35%   |
| antiX 17.2.1   | 1         | 4.35%   |
| antiX 17       | 1         | 4.35%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| antiX | 23        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp    | 3         | 13.04%  |
| 5.10.57-antix.1-amd64-smp    | 2         | 8.7%    |
| 4.9.235-antix.1-amd64-smp    | 2         | 8.7%    |
| 4.9.212-antix.1-amd64-smp    | 2         | 8.7%    |
| 4.9.212-antix.1-486-smp      | 2         | 8.7%    |
| 4.9.200-antix.1-486-smp      | 2         | 8.7%    |
| 5.14.0-14.1-liquorix-amd64   | 1         | 4.35%   |
| 5.10.88-antix.1-amd64-smp    | 1         | 4.35%   |
| 5.10.27-antix.1-amd64-smp    | 1         | 4.35%   |
| 4.9.160-antix.2-486-smp      | 1         | 4.35%   |
| 4.9.160-antix.1-amd64-smp    | 1         | 4.35%   |
| 4.9.0-279-antix.1-amd64-smp  | 1         | 4.35%   |
| 4.9.0-264-antix.1-486-smp    | 1         | 4.35%   |
| 4.19.202-antix.1-686-smp-pae | 1         | 4.35%   |
| 4.19.100-antix.1-686-smp-pae | 1         | 4.35%   |
| 4.10.5-antix.1-486-smp       | 1         | 4.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.9.0    | 5         | 21.74%  |
| 4.9.212  | 4         | 17.39%  |
| 5.10.57  | 2         | 8.7%    |
| 4.9.235  | 2         | 8.7%    |
| 4.9.200  | 2         | 8.7%    |
| 4.9.160  | 2         | 8.7%    |
| 5.14.0   | 1         | 4.35%   |
| 5.10.88  | 1         | 4.35%   |
| 5.10.27  | 1         | 4.35%   |
| 4.19.202 | 1         | 4.35%   |
| 4.19.100 | 1         | 4.35%   |
| 4.10.5   | 1         | 4.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 15        | 65.22%  |
| 5.10    | 4         | 17.39%  |
| 4.19    | 2         | 8.7%    |
| 5.14    | 1         | 4.35%   |
| 4.10    | 1         | 4.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| i686   | 12        | 52.17%  |
| x86_64 | 11        | 47.83%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 14        | 60.87%  |
| icewm   | 8         | 34.78%  |
| GNOME   | 1         | 4.35%   |

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
| SLiM    | 15        | 65.22%  |
| Unknown | 7         | 30.43%  |
| LightDM | 1         | 4.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 9         | 39.13%  |
| de_DE | 3         | 13.04%  |
| ru_RU | 2         | 8.7%    |
| en_AU | 2         | 8.7%    |
| uk_UA | 1         | 4.35%   |
| pt_BR | 1         | 4.35%   |
| nl_NL | 1         | 4.35%   |
| ja_JP | 1         | 4.35%   |
| it_IT | 1         | 4.35%   |
| es_MX | 1         | 4.35%   |
| en_GB | 1         | 4.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 19        | 82.61%  |
| EFI  | 4         | 17.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 18        | 78.26%  |
| Overlay  | 4         | 17.39%  |
| Reiserfs | 1         | 4.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 18        | 78.26%  |
| GPT     | 4         | 17.39%  |
| Unknown | 1         | 4.35%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 19        | 82.61%  |
| Yes       | 4         | 17.39%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 15        | 65.22%  |
| Yes       | 8         | 34.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 5         | 21.74%  |
| ASUSTek Computer | 5         | 21.74%  |
| IBM              | 3         | 13.04%  |
| Dell             | 2         | 8.7%    |
| Toshiba          | 1         | 4.35%   |
| Packard Bell     | 1         | 4.35%   |
| MSI              | 1         | 4.35%   |
| Medion           | 1         | 4.35%   |
| Lenovo           | 1         | 4.35%   |
| Fujitsu          | 1         | 4.35%   |
| Apple            | 1         | 4.35%   |
| Acer             | 1         | 4.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Toshiba Satellite 1905             | 1         | 4.35%   |
| Packard Bell EasyNote_MX37-U-057NL | 1         | 4.35%   |
| MSI GE62 7RE                       | 1         | 4.35%   |
| Medion WIM2170                     | 1         | 4.35%   |
| Lenovo ThinkPad T440p 20AWS3RH00   | 1         | 4.35%   |
| IBM ThinkPad T43 2668WEJ           | 1         | 4.35%   |
| IBM ThinkPad T41 2374K50           | 1         | 4.35%   |
| IBM ThinkPad T40 237342G           | 1         | 4.35%   |
| HP Pavilion dv2700                 | 1         | 4.35%   |
| HP Mini 5101                       | 1         | 4.35%   |
| HP Mini 110-3700                   | 1         | 4.35%   |
| HP EliteBook 8770w                 | 1         | 4.35%   |
| HP EliteBook 2570p                 | 1         | 4.35%   |
| Fujitsu FMVS54EB                   | 1         | 4.35%   |
| Dell Latitude E6400                | 1         | 4.35%   |
| Dell Latitude 5480                 | 1         | 4.35%   |
| ASUS X71SL                         | 1         | 4.35%   |
| ASUS X51RL                         | 1         | 4.35%   |
| ASUS A3L                           | 1         | 4.35%   |
| ASUS 900HA                         | 1         | 4.35%   |
| ASUS 900A                          | 1         | 4.35%   |
| Apple MacBook7,1                   | 1         | 4.35%   |
| Acer AOA150                        | 1         | 4.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| IBM ThinkPad          | 3         | 13.04%  |
| HP Mini               | 2         | 8.7%    |
| HP EliteBook          | 2         | 8.7%    |
| Dell Latitude         | 2         | 8.7%    |
| Toshiba Satellite     | 1         | 4.35%   |
| Packard Bell EasyNote | 1         | 4.35%   |
| MSI GE62              | 1         | 4.35%   |
| Medion WIM2170        | 1         | 4.35%   |
| Lenovo ThinkPad       | 1         | 4.35%   |
| HP Pavilion           | 1         | 4.35%   |
| Fujitsu FMVS54EB      | 1         | 4.35%   |
| ASUS X71SL            | 1         | 4.35%   |
| ASUS X51RL            | 1         | 4.35%   |
| ASUS A3L              | 1         | 4.35%   |
| ASUS 900HA            | 1         | 4.35%   |
| ASUS 900A             | 1         | 4.35%   |
| Apple MacBook7        | 1         | 4.35%   |
| Acer AOA150           | 1         | 4.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2008 | 4         | 17.39%  |
| 2009 | 3         | 13.04%  |
| 2007 | 3         | 13.04%  |
| 2013 | 2         | 8.7%    |
| 2012 | 2         | 8.7%    |
| 2005 | 2         | 8.7%    |
| 2003 | 2         | 8.7%    |
| 2017 | 1         | 4.35%   |
| 2016 | 1         | 4.35%   |
| 2011 | 1         | 4.35%   |
| 2010 | 1         | 4.35%   |
| 2004 | 1         | 4.35%   |

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
| 0.51-1.0   | 6         | 26.09%  |
| 1.01-2.0   | 5         | 21.74%  |
| 3.01-4.0   | 4         | 17.39%  |
| 32.01-64.0 | 2         | 8.7%    |
| 2.01-3.0   | 2         | 8.7%    |
| 8.01-16.0  | 2         | 8.7%    |
| 4.01-8.0   | 1         | 4.35%   |
| 16.01-24.0 | 1         | 4.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.51-1.0 | 9         | 39.13%  |
| 0.01-0.5 | 9         | 39.13%  |
| 2.01-3.0 | 3         | 13.04%  |
| 1.01-2.0 | 2         | 8.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 19        | 82.61%  |
| 2      | 3         | 13.04%  |
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
| Yes       | 22        | 95.65%  |
| No        | 1         | 4.35%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 15        | 65.22%  |
| Yes       | 8         | 34.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 5         | 21.74%  |
| Germany     | 4         | 17.39%  |
| Russia      | 3         | 13.04%  |
| Australia   | 2         | 8.7%    |
| Ukraine     | 1         | 4.35%   |
| Netherlands | 1         | 4.35%   |
| Mexico      | 1         | 4.35%   |
| Kazakhstan  | 1         | 4.35%   |
| Japan       | 1         | 4.35%   |
| Italy       | 1         | 4.35%   |
| Hungary     | 1         | 4.35%   |
| Denmark     | 1         | 4.35%   |
| Brazil      | 1         | 4.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Sydney                    | 2         | 8.7%    |
| Moscow                    | 2         | 8.7%    |
| Yuzhno-Sakhalinsk         | 1         | 4.35%   |
| Wiesmoor                  | 1         | 4.35%   |
| Toms River                | 1         | 4.35%   |
| Schloss Holte-Stukenbrock | 1         | 4.35%   |
| Salto                     | 1         | 4.35%   |
| Rotterdam                 | 1         | 4.35%   |
| Portland                  | 1         | 4.35%   |
| Osaka                     | 1         | 4.35%   |
| Norden                    | 1         | 4.35%   |
| Metzingen                 | 1         | 4.35%   |
| Mechanicsburg             | 1         | 4.35%   |
| Karaganda                 | 1         | 4.35%   |
| Jonesboro                 | 1         | 4.35%   |
| El Cerrito                | 1         | 4.35%   |
| Dnipropetrovsk            | 1         | 4.35%   |
| Copenhagen                | 1         | 4.35%   |
| Celaya                    | 1         | 4.35%   |
| Budapest                  | 1         | 4.35%   |
| Albairate                 | 1         | 4.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 18.52%  |
| Hitachi             | 5         | 5      | 18.52%  |
| WDC                 | 4         | 4      | 14.81%  |
| Toshiba             | 2         | 2      | 7.41%   |
| Samsung Electronics | 2         | 2      | 7.41%   |
| Kingston            | 2         | 2      | 7.41%   |
| Zheino              | 1         | 1      | 3.7%    |
| Unknown             | 1         | 1      | 3.7%    |
| OCZ                 | 1         | 1      | 3.7%    |
| Intel               | 1         | 1      | 3.7%    |
| HGST                | 1         | 1      | 3.7%    |
| Hewlett-Packard     | 1         | 1      | 3.7%    |
| ASUS-PHISON         | 1         | 1      | 3.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Samsung SSD 750 EVO 120GB        | 2         | 7.41%   |
| Zheino CHN mSATAM3 128 128GB SSD | 1         | 3.7%    |
| WDC WD5000LPLX-08ZNTT0 500GB     | 1         | 3.7%    |
| WDC WD3200BEVT-60ZCT1 320GB      | 1         | 3.7%    |
| WDC WD3200BEVT-22ZCT0 320GB      | 1         | 3.7%    |
| WDC WD1200BEVE-00A0HT0 120GB     | 1         | 3.7%    |
| Unknown SR64G  64GB              | 1         | 3.7%    |
| Toshiba THNSNJ256G8NY 256GB SSD  | 1         | 3.7%    |
| Toshiba MK2576GSX 250GB          | 1         | 3.7%    |
| Seagate ST9160411AS 160GB        | 1         | 3.7%    |
| Seagate ST9160314AS 160GB        | 1         | 3.7%    |
| Seagate ST9160310AS 160GB        | 1         | 3.7%    |
| Seagate ST9160301AS 160GB        | 1         | 3.7%    |
| Seagate ST500LM021-1KJ152 500GB  | 1         | 3.7%    |
| OCZ AGILITY3 120GB SSD           | 1         | 3.7%    |
| Kingston SUV500MS120G 120GB SSD  | 1         | 3.7%    |
| Kingston SUV400S37120G 120GB SSD | 1         | 3.7%    |
| Intel SSDSC2BW180A3H 180GB       | 1         | 3.7%    |
| Hitachi HTS725050A7E630 500GB    | 1         | 3.7%    |
| Hitachi HTS723232A7A364 320GB    | 1         | 3.7%    |
| Hitachi HTS721060G9AT00 64GB     | 1         | 3.7%    |
| Hitachi HTS548040M9AT00 40GB     | 1         | 3.7%    |
| Hitachi HTS541612J9SA00 120GB    | 1         | 3.7%    |
| HGST HTS721010A9E630 1TB         | 1         | 3.7%    |
| HP SSD S750 512GB                | 1         | 3.7%    |
| ASUS-PHISON SSD 8GB              | 1         | 3.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 31.25%  |
| Hitachi | 5         | 5      | 31.25%  |
| WDC     | 4         | 4      | 25%     |
| Toshiba | 1         | 1      | 6.25%   |
| HGST    | 1         | 1      | 6.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 20%     |
| Kingston            | 2         | 2      | 20%     |
| Zheino              | 1         | 1      | 10%     |
| Toshiba             | 1         | 1      | 10%     |
| OCZ                 | 1         | 1      | 10%     |
| Intel               | 1         | 1      | 10%     |
| Hewlett-Packard     | 1         | 1      | 10%     |
| ASUS-PHISON         | 1         | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 16     | 59.26%  |
| SSD  | 10        | 10     | 37.04%  |
| MMC  | 1         | 1      | 3.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 23        | 26     | 95.83%  |
| MMC  | 1         | 1      | 4.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 23        | 24     | 92%     |
| 0.51-1.0   | 2         | 2      | 8%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 8         | 34.78%  |
| 21-50      | 4         | 17.39%  |
| 1-20       | 4         | 17.39%  |
| 51-100     | 3         | 13.04%  |
| 251-500    | 2         | 8.7%    |
| 501-1000   | 1         | 4.35%   |
| Unknown    | 1         | 4.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 16        | 69.57%  |
| 21-50   | 3         | 13.04%  |
| 101-250 | 2         | 8.7%    |
| 51-100  | 1         | 4.35%   |
| Unknown | 1         | 4.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-60ZCT1 320GB   | 1         | 1      | 12.5%   |
| Seagate ST9160314AS 160GB     | 1         | 1      | 12.5%   |
| Seagate ST9160310AS 160GB     | 1         | 1      | 12.5%   |
| Hitachi HTS725050A7E630 500GB | 1         | 1      | 12.5%   |
| Hitachi HTS723232A7A364 320GB | 1         | 1      | 12.5%   |
| Hitachi HTS721060G9AT00 64GB  | 1         | 1      | 12.5%   |
| Hitachi HTS548040M9AT00 40GB  | 1         | 1      | 12.5%   |
| Hitachi HTS541612J9SA00 120GB | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 5         | 5      | 62.5%   |
| Seagate | 2         | 2      | 25%     |
| WDC     | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 5         | 5      | 62.5%   |
| Seagate | 2         | 2      | 25%     |
| WDC     | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 8      | 100%    |

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
| Works    | 14        | 16     | 56%     |
| Malfunc  | 8         | 8      | 32%     |
| Detected | 3         | 3      | 12%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 19        | 76%     |
| Silicon Integrated Systems [SiS] | 2         | 8%      |
| Silicon Image                    | 1         | 4%      |
| Nvidia                           | 1         | 4%      |
| JMicron Technology               | 1         | 4%      |
| AMD                              | 1         | 4%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 9.68%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 3         | 9.68%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 6.45%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 6.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 6.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 6.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 6.45%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller               | 1         | 3.23%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 3.23%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 3.23%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 3.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 3.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 3.23%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 1         | 3.23%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 3.23%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 1         | 3.23%   |
| Intel 82801BA IDE U100 Controller                                              | 1         | 3.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 3.23%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 3.23%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 1         | 3.23%   |
| AMD SB600 IDE                                                                  | 1         | 3.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| IDE  | 14        | 50%     |
| SATA | 11        | 39.29%  |
| RAID | 3         | 10.71%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 23        | 100%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz          | 3         | 13.04%  |
| Intel Pentium M processor 1.60GHz      | 2         | 8.7%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz   | 2         | 8.7%    |
| Intel Pentium M processor 1600MHz      | 1         | 4.35%   |
| Intel Pentium M processor 1.86GHz      | 1         | 4.35%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz | 1         | 4.35%   |
| Intel Pentium 4 CPU 2.00GHz            | 1         | 4.35%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz     | 1         | 4.35%   |
| Intel Core i7-7600U CPU @ 2.80GHz      | 1         | 4.35%   |
| Intel Core i7-3740QM CPU @ 2.70GHz     | 1         | 4.35%   |
| Intel Core i5-4300M CPU @ 2.60GHz      | 1         | 4.35%   |
| Intel Core i5-3320M CPU @ 2.60GHz      | 1         | 4.35%   |
| Intel Core i3-2330M CPU @ 2.20GHz      | 1         | 4.35%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz   | 1         | 4.35%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz   | 1         | 4.35%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz   | 1         | 4.35%   |
| Intel Celeron CPU 540 @ 1.86GHz        | 1         | 4.35%   |
| Intel Atom CPU N455 @ 1.66GHz          | 1         | 4.35%   |
| Intel Atom CPU N280 @ 1.66GHz          | 1         | 4.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core 2 Duo   | 5         | 21.74%  |
| Intel Atom         | 5         | 21.74%  |
| Intel Pentium M    | 4         | 17.39%  |
| Intel Core i7      | 3         | 13.04%  |
| Intel Core i5      | 2         | 8.7%    |
| Intel Pentium Dual | 1         | 4.35%   |
| Intel Pentium 4    | 1         | 4.35%   |
| Intel Core i3      | 1         | 4.35%   |
| Intel Celeron      | 1         | 4.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 11        | 47.83%  |
| 2      | 10        | 43.48%  |
| 4      | 2         | 8.7%    |

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
| 1      | 12        | 52.17%  |
| 2      | 11        | 47.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 14        | 60.87%  |
| 32-bit         | 9         | 39.13%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 0x106c2 | 4         | 17.39%  |
| 0x6fd   | 3         | 13.04%  |
| 0x1067a | 3         | 13.04%  |
| 0x6d6   | 2         | 8.7%    |
| 0x306a9 | 2         | 8.7%    |
| 0xf24   | 1         | 4.35%   |
| 0x906e9 | 1         | 4.35%   |
| 0x806e9 | 1         | 4.35%   |
| 0x6d8   | 1         | 4.35%   |
| 0x695   | 1         | 4.35%   |
| 0x306c3 | 1         | 4.35%   |
| 0x206a7 | 1         | 4.35%   |
| 0x106ca | 1         | 4.35%   |
| 0x10661 | 1         | 4.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Bonnell     | 5         | 21.74%  |
| P6          | 4         | 17.39%  |
| Core        | 4         | 17.39%  |
| Penryn      | 3         | 13.04%  |
| KabyLake    | 2         | 8.7%    |
| IvyBridge   | 2         | 8.7%    |
| SandyBridge | 1         | 4.35%   |
| NetBurst    | 1         | 4.35%   |
| Haswell     | 1         | 4.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 13        | 54.17%  |
| Nvidia                           | 5         | 20.83%  |
| AMD                              | 5         | 20.83%  |
| Silicon Integrated Systems [SiS] | 1         | 4.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 4         | 13.79%  |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 4         | 13.79%  |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 2         | 6.9%    |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 3.45%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 3.45%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 3.45%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 3.45%   |
| Nvidia G98M [GeForce 9300M GS]                                                | 1         | 3.45%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 3.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 3.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 3.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 3.45%   |
| Intel HD Graphics 630                                                         | 1         | 3.45%   |
| Intel HD Graphics 620                                                         | 1         | 3.45%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 1         | 3.45%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 1         | 3.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 3.45%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 1         | 3.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 1         | 3.45%   |
| AMD RV370/M22 [Mobility Radeon X300]                                          | 1         | 3.45%   |
| AMD RV100/M6 [Rage/Radeon Mobility Series]                                    | 1         | 3.45%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                      | 1         | 3.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 11        | 47.83%  |
| 1 x AMD        | 5         | 21.74%  |
| 1 x Nvidia     | 4         | 17.39%  |
| Other          | 1         | 4.35%   |
| 1 x SiS        | 1         | 4.35%   |
| Intel + Nvidia | 1         | 4.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 20        | 86.96%  |
| Unknown     | 2         | 8.7%    |
| Proprietary | 1         | 4.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 14        | 60.87%  |
| Unknown    | 6         | 26.09%  |
| 1.01-2.0   | 2         | 8.7%    |
| 3.01-4.0   | 1         | 4.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 5         | 31.25%  |
| LG Display          | 4         | 25%     |
| Samsung Electronics | 2         | 12.5%   |
| HannStar            | 2         | 12.5%   |
| LG Philips          | 1         | 6.25%   |
| BOE                 | 1         | 6.25%   |
| Apple               | 1         | 6.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch | 1         | 6.25%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch | 1         | 6.25%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch          | 1         | 6.25%   |
| LG Display LP101WH1-TLB5 LGD0248 1366x768 224x126mm 10.1-inch        | 1         | 6.25%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 1         | 6.25%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch          | 1         | 6.25%   |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch          | 1         | 6.25%   |
| HannStar LCD Monitor HSD0325 1024x600 195x113mm 8.9-inch             | 1         | 6.25%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch             | 1         | 6.25%   |
| BOE LCD Monitor BOE06E2 1920x1080 309x173mm 13.9-inch                | 1         | 6.25%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch        | 1         | 6.25%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch        | 1         | 6.25%   |
| AU Optronics LCD Monitor AUO4047 1440x900 303x189mm 14.1-inch        | 1         | 6.25%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch       | 1         | 6.25%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch         | 1         | 6.25%   |
| Apple LCD Monitor APP9CBE 1280x800 286x179mm 13.3-inch               | 1         | 6.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 4         | 25%     |
| 1280x800 (WXGA)  | 4         | 25%     |
| 1920x1080 (FHD)  | 3         | 18.75%  |
| 1024x600         | 3         | 18.75%  |
| 1440x900 (WXGA+) | 2         | 12.5%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 4         | 25%     |
| 15     | 3         | 18.75%  |
| 14     | 3         | 18.75%  |
| 17     | 2         | 12.5%   |
| 10     | 2         | 12.5%   |
| 8      | 2         | 12.5%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 7         | 43.75%  |
| 201-300     | 5         | 31.25%  |
| 351-400     | 2         | 12.5%   |
| 101-200     | 2         | 12.5%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 10        | 62.5%   |
| 16/10 | 6         | 37.5%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 5         | 31.25%  |
| 101-110        | 3         | 18.75%  |
| 71-80          | 2         | 12.5%   |
| 41-50          | 2         | 12.5%   |
| 1-40           | 2         | 12.5%   |
| 131-140        | 1         | 6.25%   |
| 121-130        | 1         | 6.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 7         | 43.75%  |
| 101-120 | 6         | 37.5%   |
| 51-100  | 3         | 18.75%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 22        | 95.65%  |
| 0     | 1         | 4.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Qualcomm Atheros                 | 11        | 27.5%   |
| Intel                            | 11        | 27.5%   |
| Realtek Semiconductor            | 6         | 15%     |
| Broadcom                         | 4         | 10%     |
| Silicon Integrated Systems [SiS] | 2         | 5%      |
| Marvell Technology Group         | 2         | 5%      |
| Ralink                           | 1         | 2.5%    |
| Qualcomm Atheros Communications  | 1         | 2.5%    |
| Nvidia                           | 1         | 2.5%    |
| Hewlett-Packard                  | 1         | 2.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 5         | 9.62%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 5.77%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 2         | 3.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 3.85%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 3.85%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller             | 2         | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 3.85%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                            | 2         | 3.85%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 3.85%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 1.92%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 1.92%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 1.92%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.92%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 1.92%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 1.92%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.92%   |
| Nvidia MCP89 Ethernet                                                         | 1         | 1.92%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                       | 1         | 1.92%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                          | 1         | 1.92%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.92%   |
| Intel Wireless 7260                                                           | 1         | 1.92%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.92%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 1.92%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 1         | 1.92%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 1.92%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 1.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.92%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 1.92%   |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 1.92%   |
| Intel Centrino Ultimate-N 6300                                                | 1         | 1.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 1.92%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller              | 1         | 1.92%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                                  | 1         | 1.92%   |
| Intel 82801BA/BAM AC'97 Modem Controller                                      | 1         | 1.92%   |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 1.92%   |
| HP lt2523 Mobile Broadband Device                                             | 1         | 1.92%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                      | 1         | 1.92%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 1         | 1.92%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 9         | 37.5%   |
| Intel                           | 9         | 37.5%   |
| Broadcom                        | 3         | 12.5%   |
| Realtek Semiconductor           | 1         | 4.17%   |
| Ralink                          | 1         | 4.17%   |
| Qualcomm Atheros Communications | 1         | 4.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 5         | 20%     |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 8%      |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 4%      |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 4%      |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 4%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 4%      |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 4%      |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 4%      |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 4%      |
| Intel Wireless 8265 / 8275                                                    | 1         | 4%      |
| Intel Wireless 7260                                                           | 1         | 4%      |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 4%      |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 4%      |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 1         | 4%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 4%      |
| Intel Centrino Wireless-N 6150                                                | 1         | 4%      |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 4%      |
| Intel Centrino Ultimate-N 6300                                                | 1         | 4%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 4%      |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 1         | 4%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 8         | 36.36%  |
| Realtek Semiconductor            | 5         | 22.73%  |
| Qualcomm Atheros                 | 3         | 13.64%  |
| Silicon Integrated Systems [SiS] | 2         | 9.09%   |
| Marvell Technology Group         | 2         | 9.09%   |
| Nvidia                           | 1         | 4.55%   |
| Broadcom                         | 1         | 4.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller          | 3         | 13.64%  |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter  | 2         | 9.09%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter          | 2         | 9.09%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet | 2         | 9.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)          | 2         | 9.09%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)             | 2         | 9.09%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller      | 1         | 4.55%   |
| Nvidia MCP89 Ethernet                                          | 1         | 4.55%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller        | 1         | 4.55%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller           | 1         | 4.55%   |
| Intel Ethernet Connection I217-LM                              | 1         | 4.55%   |
| Intel Ethernet Connection (4) I219-LM                          | 1         | 4.55%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                   | 1         | 4.55%   |
| Intel 82567LM Gigabit Network Connection                       | 1         | 4.55%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express       | 1         | 4.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 22        | 44.9%   |
| Ethernet | 22        | 44.9%   |
| Modem    | 5         | 10.2%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 19        | 86.36%  |
| Ethernet | 3         | 13.64%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 21        | 91.3%   |
| 1     | 2         | 8.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 19        | 82.61%  |
| Yes  | 4         | 17.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Broadcom          | 3         | 37.5%   |
| Intel             | 2         | 25%     |
| Ralink Technology | 1         | 12.5%   |
| ASUSTek Computer  | 1         | 12.5%   |
| Apple             | 1         | 12.5%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Broadcom HP Portable SoftSailing             | 2         | 25%     |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter | 1         | 12.5%   |
| Intel Wireless-AC 3168 Bluetooth             | 1         | 12.5%   |
| Intel Bluetooth wireless interface           | 1         | 12.5%   |
| Broadcom BCM20702A0 Bluetooth 4.0            | 1         | 12.5%   |
| ASUS BT-253 Bluetooth Adapter                | 1         | 12.5%   |
| Apple Bluetooth Host Controller              | 1         | 12.5%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 19        | 79.17%  |
| Silicon Integrated Systems [SiS] | 2         | 8.33%   |
| Nvidia                           | 2         | 8.33%   |
| AMD                              | 1         | 4.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 20%     |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 3         | 12%     |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 8%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 8%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 8%      |
| Nvidia MCP89 High Definition Audio                                         | 1         | 4%      |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 4%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 4%      |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 4%      |
| Intel CM238 HD Audio Controller                                            | 1         | 4%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 4%      |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 4%      |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 4%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 4%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 4%      |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 4%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 10        | 41.67%  |
| SK Hynix            | 5         | 20.83%  |
| Micron Technology   | 2         | 8.33%   |
| Kingston            | 2         | 8.33%   |
| Unknown (8A02)      | 1         | 4.17%   |
| Samsung Electronics | 1         | 4.17%   |
| Crucial             | 1         | 4.17%   |
| Avant               | 1         | 4.17%   |
| Unknown             | 1         | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 1024MB SODIMM DDR                           | 3         | 12%     |
| Unknown RAM Module 2GB SODIMM SDRAM                            | 2         | 8%      |
| Unknown RAM Module 512MB SODIMM DDR                            | 1         | 4%      |
| Unknown RAM Module 256MB DIMM SDRAM                            | 1         | 4%      |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 1         | 4%      |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 4%      |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 4%      |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1         | 4%      |
| Unknown (8A02) RAM DDR4 16GB 2400MHz 16GB SODIMM DDR4 2400MT/s | 1         | 4%      |
| SK Hynix RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 4%      |
| SK Hynix RAM Module 1GB SODIMM DDR3 1067MT/s                   | 1         | 4%      |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s           | 1         | 4%      |
| SK Hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 4%      |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 4%      |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s          | 1         | 4%      |
| Micron RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 4%      |
| Micron RAM 8HTF12864HDY-800G1 1024MB SODIMM DDR2 800MT/s       | 1         | 4%      |
| Kingston RAM MSI24D4S7D8MB-16 16GB SODIMM DDR4 2400MT/s        | 1         | 4%      |
| Kingston RAM 9905428-095.D00LF 8GB SODIMM DDR3 1600MT/s        | 1         | 4%      |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 1         | 4%      |
| Avant RAM H641GU67F1600G 8GB SODIMM DDR3 1600MT/s              | 1         | 4%      |
| Unknown                                                        | 1         | 4%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| SDRAM | 6         | 28.57%  |
| DDR3  | 5         | 23.81%  |
| DDR2  | 4         | 19.05%  |
| DDR   | 4         | 19.05%  |
| DDR4  | 2         | 9.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 20        | 95.24%  |
| DIMM   | 1         | 4.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 1024  | 8         | 34.78%  |
| 2048  | 6         | 26.09%  |
| 8192  | 4         | 17.39%  |
| 512   | 2         | 8.7%    |
| 16384 | 1         | 4.35%   |
| 4096  | 1         | 4.35%   |
| 256   | 1         | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 9         | 40.91%  |
| 1600    | 3         | 13.64%  |
| 1067    | 2         | 9.09%   |
| 2667    | 1         | 4.55%   |
| 2400    | 1         | 4.55%   |
| 1333    | 1         | 4.55%   |
| 975     | 1         | 4.55%   |
| 800     | 1         | 4.55%   |
| 667     | 1         | 4.55%   |
| 533     | 1         | 4.55%   |
| 266     | 1         | 4.55%   |

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
| Chicony Electronics                    | 5         | 33.33%  |
| Pixart Imaging                         | 2         | 13.33%  |
| Microdia                               | 2         | 13.33%  |
| Suyin                                  | 1         | 6.67%   |
| Sunplus Innovation Technology          | 1         | 6.67%   |
| Importek                               | 1         | 6.67%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 6.67%   |
| Apple                                  | 1         | 6.67%   |
| Acer                                   | 1         | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Pixart Imaging USB2.0_Camera                        | 2         | 13.33%  |
| Suyin USB2.0 UVC 1.3M WebCam                        | 1         | 6.67%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 6.67%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 6.67%   |
| Microdia Integrated Webcam                          | 1         | 6.67%   |
| Importek FJ Camera                                  | 1         | 6.67%   |
| Chicony VGA 30fps UVC Webcam                        | 1         | 6.67%   |
| Chicony Integrated HP HD Webcam                     | 1         | 6.67%   |
| Chicony HP HD Webcam [Fixed]                        | 1         | 6.67%   |
| Chicony CNF8243 Webcam                              | 1         | 6.67%   |
| Chicony CNF7050                                     | 1         | 6.67%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC) | 1         | 6.67%   |
| Apple Built-in iSight                               | 1         | 6.67%   |
| Acer HP Webcam                                      | 1         | 6.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| AuthenTec        | 2         | 66.67%  |
| Validity Sensors | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Validity Sensors VFS491              | 1         | 33.33%  |
| AuthenTec AES2501 Fingerprint Sensor | 1         | 33.33%  |
| AuthenTec AES1600                    | 1         | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Broadcom 5880                                  | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 17        | 73.91%  |
| 1     | 5         | 21.74%  |
| 2     | 1         | 4.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Graphics card      | 3         | 42.86%  |
| Fingerprint reader | 3         | 42.86%  |
| Chipcard           | 1         | 14.29%  |

