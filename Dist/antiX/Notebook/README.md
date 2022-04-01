antiX - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for antiX.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 28

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
| Apple   | MacBook7,1                  | [70413280df](https://linux-hardware.org/?probe=70413280df) | Mar 26, 2022 |
| HP      | EliteBook 2570p             | [20e998c205](https://linux-hardware.org/?probe=20e998c205) | Mar 17, 2022 |
| IBM     | ThinkPad T40 237342G        | [2c96b391e2](https://linux-hardware.org/?probe=2c96b391e2) | Jan 16, 2022 |
| IBM     | ThinkPad T40 237342G        | [5c4e8748ef](https://linux-hardware.org/?probe=5c4e8748ef) | Jan 16, 2022 |
| Toshiba | Satellite 1905              | [e72b9043c8](https://linux-hardware.org/?probe=e72b9043c8) | Jan 14, 2022 |
| Lenovo  | ThinkPad T440p 20AWS3RH0... | [b2a71d3bbe](https://linux-hardware.org/?probe=b2a71d3bbe) | Dec 30, 2021 |
| ASUSTek | X71SL                       | [42e7b57eb8](https://linux-hardware.org/?probe=42e7b57eb8) | Dec 07, 2021 |
| ASUSTek | A3L                         | [32489f1764](https://linux-hardware.org/?probe=32489f1764) | Dec 06, 2021 |
| ASUSTek | A3L                         | [2b01c636c2](https://linux-hardware.org/?probe=2b01c636c2) | Dec 06, 2021 |
| ASUSTek | X51RL                       | [0aeee18806](https://linux-hardware.org/?probe=0aeee18806) | Nov 19, 2021 |
| Acer    | AOA150                      | [24833c6a59](https://linux-hardware.org/?probe=24833c6a59) | Oct 26, 2021 |
| Dell    | Latitude E6400              | [6b7ef9cad5](https://linux-hardware.org/?probe=6b7ef9cad5) | Oct 21, 2021 |
| MSI     | GE62 7RE                    | [9d064bcc8d](https://linux-hardware.org/?probe=9d064bcc8d) | May 21, 2021 |
| MSI     | GE62 7RE                    | [d560e067d4](https://linux-hardware.org/?probe=d560e067d4) | May 21, 2021 |
| HP      | EliteBook 8770w             | [0af42b4958](https://linux-hardware.org/?probe=0af42b4958) | Mar 17, 2021 |
| Fujitsu | FMVS54EB                    | [f01ca3644f](https://linux-hardware.org/?probe=f01ca3644f) | Mar 11, 2021 |
| Dell    | Latitude 5480               | [c9e0b19e8b](https://linux-hardware.org/?probe=c9e0b19e8b) | Mar 07, 2021 |
| HP      | Mini 110-3700               | [33a6e65493](https://linux-hardware.org/?probe=33a6e65493) | Jan 06, 2021 |
| IBM     | ThinkPad T41 2374K50        | [c77530ec4e](https://linux-hardware.org/?probe=c77530ec4e) | Nov 19, 2020 |
| IBM     | ThinkPad T41 2374K50        | [9c27b878ae](https://linux-hardware.org/?probe=9c27b878ae) | Nov 17, 2020 |
| IBM     | ThinkPad T43 2668WEJ        | [c7508c3b5c](https://linux-hardware.org/?probe=c7508c3b5c) | Oct 02, 2020 |
| HP      | Pavilion dv2700             | [312d41f446](https://linux-hardware.org/?probe=312d41f446) | Aug 01, 2020 |
| HP      | Mini 5101                   | [c0abbe79e6](https://linux-hardware.org/?probe=c0abbe79e6) | Apr 24, 2020 |
| HP      | Mini 5101                   | [8fd41129bc](https://linux-hardware.org/?probe=8fd41129bc) | Apr 24, 2020 |
| ASUSTek | 900A                        | [9ab5761eb1](https://linux-hardware.org/?probe=9ab5761eb1) | Apr 05, 2020 |
| ASUSTek | 900HA                       | [39b2bfbefc](https://linux-hardware.org/?probe=39b2bfbefc) | Mar 21, 2020 |
| Medion  | WIM2170                     | [a8c4771b62](https://linux-hardware.org/?probe=a8c4771b62) | Jan 13, 2020 |
| Medion  | WIM2170                     | [c879195021](https://linux-hardware.org/?probe=c879195021) | Jan 13, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| antiX 19.2     | 6         | 27.27%  |
| antiX 21       | 5         | 22.73%  |
| antiX 19.3     | 3         | 13.64%  |
| antiX 19.4     | 2         | 9.09%   |
| antiX 19.1     | 2         | 9.09%   |
| antiX 21-runit | 1         | 4.55%   |
| antiX 17.4.1   | 1         | 4.55%   |
| antiX 17.2.1   | 1         | 4.55%   |
| antiX 17       | 1         | 4.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| antiX | 22        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp    | 3         | 13.64%  |
| 4.9.235-antix.1-amd64-smp    | 2         | 9.09%   |
| 4.9.212-antix.1-amd64-smp    | 2         | 9.09%   |
| 4.9.212-antix.1-486-smp      | 2         | 9.09%   |
| 4.9.200-antix.1-486-smp      | 2         | 9.09%   |
| 5.14.0-14.1-liquorix-amd64   | 1         | 4.55%   |
| 5.10.88-antix.1-amd64-smp    | 1         | 4.55%   |
| 5.10.57-antix.1-amd64-smp    | 1         | 4.55%   |
| 5.10.27-antix.1-amd64-smp    | 1         | 4.55%   |
| 4.9.160-antix.2-486-smp      | 1         | 4.55%   |
| 4.9.160-antix.1-amd64-smp    | 1         | 4.55%   |
| 4.9.0-279-antix.1-amd64-smp  | 1         | 4.55%   |
| 4.9.0-264-antix.1-486-smp    | 1         | 4.55%   |
| 4.19.202-antix.1-686-smp-pae | 1         | 4.55%   |
| 4.19.100-antix.1-686-smp-pae | 1         | 4.55%   |
| 4.10.5-antix.1-486-smp       | 1         | 4.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.9.0    | 5         | 22.73%  |
| 4.9.212  | 4         | 18.18%  |
| 4.9.235  | 2         | 9.09%   |
| 4.9.200  | 2         | 9.09%   |
| 4.9.160  | 2         | 9.09%   |
| 5.14.0   | 1         | 4.55%   |
| 5.10.88  | 1         | 4.55%   |
| 5.10.57  | 1         | 4.55%   |
| 5.10.27  | 1         | 4.55%   |
| 4.19.202 | 1         | 4.55%   |
| 4.19.100 | 1         | 4.55%   |
| 4.10.5   | 1         | 4.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 15        | 68.18%  |
| 5.10    | 3         | 13.64%  |
| 4.19    | 2         | 9.09%   |
| 5.14    | 1         | 4.55%   |
| 4.10    | 1         | 4.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| i686   | 12        | 54.55%  |
| x86_64 | 10        | 45.45%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 14        | 63.64%  |
| icewm   | 7         | 31.82%  |
| GNOME   | 1         | 4.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 22        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 15        | 68.18%  |
| Unknown | 6         | 27.27%  |
| LightDM | 1         | 4.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 9         | 40.91%  |
| de_DE | 3         | 13.64%  |
| ru_RU | 2         | 9.09%   |
| en_AU | 2         | 9.09%   |
| uk_UA | 1         | 4.55%   |
| pt_BR | 1         | 4.55%   |
| ja_JP | 1         | 4.55%   |
| it_IT | 1         | 4.55%   |
| es_MX | 1         | 4.55%   |
| en_GB | 1         | 4.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 18        | 81.82%  |
| EFI  | 4         | 18.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 17        | 77.27%  |
| Overlay  | 4         | 18.18%  |
| Reiserfs | 1         | 4.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 17        | 77.27%  |
| GPT     | 4         | 18.18%  |
| Unknown | 1         | 4.55%   |

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
| No        | 14        | 63.64%  |
| Yes       | 8         | 36.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 5         | 22.73%  |
| ASUSTek Computer | 5         | 22.73%  |
| IBM              | 3         | 13.64%  |
| Dell             | 2         | 9.09%   |
| Toshiba          | 1         | 4.55%   |
| MSI              | 1         | 4.55%   |
| Medion           | 1         | 4.55%   |
| Lenovo           | 1         | 4.55%   |
| Fujitsu          | 1         | 4.55%   |
| Apple            | 1         | 4.55%   |
| Acer             | 1         | 4.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Toshiba Satellite 1905           | 1         | 4.55%   |
| MSI GE62 7RE                     | 1         | 4.55%   |
| Medion WIM2170                   | 1         | 4.55%   |
| Lenovo ThinkPad T440p 20AWS3RH00 | 1         | 4.55%   |
| IBM ThinkPad T43 2668WEJ         | 1         | 4.55%   |
| IBM ThinkPad T41 2374K50         | 1         | 4.55%   |
| IBM ThinkPad T40 237342G         | 1         | 4.55%   |
| HP Pavilion dv2700               | 1         | 4.55%   |
| HP Mini 5101                     | 1         | 4.55%   |
| HP Mini 110-3700                 | 1         | 4.55%   |
| HP EliteBook 8770w               | 1         | 4.55%   |
| HP EliteBook 2570p               | 1         | 4.55%   |
| Fujitsu FMVS54EB                 | 1         | 4.55%   |
| Dell Latitude E6400              | 1         | 4.55%   |
| Dell Latitude 5480               | 1         | 4.55%   |
| ASUS X71SL                       | 1         | 4.55%   |
| ASUS X51RL                       | 1         | 4.55%   |
| ASUS A3L                         | 1         | 4.55%   |
| ASUS 900HA                       | 1         | 4.55%   |
| ASUS 900A                        | 1         | 4.55%   |
| Apple MacBook7,1                 | 1         | 4.55%   |
| Acer AOA150                      | 1         | 4.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| IBM ThinkPad      | 3         | 13.64%  |
| HP Mini           | 2         | 9.09%   |
| HP EliteBook      | 2         | 9.09%   |
| Dell Latitude     | 2         | 9.09%   |
| Toshiba Satellite | 1         | 4.55%   |
| MSI GE62          | 1         | 4.55%   |
| Medion WIM2170    | 1         | 4.55%   |
| Lenovo ThinkPad   | 1         | 4.55%   |
| HP Pavilion       | 1         | 4.55%   |
| Fujitsu FMVS54EB  | 1         | 4.55%   |
| ASUS X71SL        | 1         | 4.55%   |
| ASUS X51RL        | 1         | 4.55%   |
| ASUS A3L          | 1         | 4.55%   |
| ASUS 900HA        | 1         | 4.55%   |
| ASUS 900A         | 1         | 4.55%   |
| Apple MacBook7    | 1         | 4.55%   |
| Acer AOA150       | 1         | 4.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2009 | 3         | 13.64%  |
| 2008 | 3         | 13.64%  |
| 2007 | 3         | 13.64%  |
| 2013 | 2         | 9.09%   |
| 2012 | 2         | 9.09%   |
| 2005 | 2         | 9.09%   |
| 2003 | 2         | 9.09%   |
| 2017 | 1         | 4.55%   |
| 2016 | 1         | 4.55%   |
| 2011 | 1         | 4.55%   |
| 2010 | 1         | 4.55%   |
| 2004 | 1         | 4.55%   |

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
| Disabled | 22        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 22        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 6         | 27.27%  |
| 1.01-2.0   | 5         | 22.73%  |
| 3.01-4.0   | 3         | 13.64%  |
| 32.01-64.0 | 2         | 9.09%   |
| 2.01-3.0   | 2         | 9.09%   |
| 8.01-16.0  | 2         | 9.09%   |
| 4.01-8.0   | 1         | 4.55%   |
| 16.01-24.0 | 1         | 4.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 9         | 40.91%  |
| 0.51-1.0 | 8         | 36.36%  |
| 2.01-3.0 | 3         | 13.64%  |
| 1.01-2.0 | 2         | 9.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 18        | 81.82%  |
| 2      | 3         | 13.64%  |
| 3      | 1         | 4.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 13        | 59.09%  |
| No        | 9         | 40.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 95.45%  |
| No        | 1         | 4.55%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 95.45%  |
| No        | 1         | 4.55%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 14        | 63.64%  |
| Yes       | 8         | 36.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| USA        | 5         | 22.73%  |
| Germany    | 4         | 18.18%  |
| Russia     | 3         | 13.64%  |
| Australia  | 2         | 9.09%   |
| Ukraine    | 1         | 4.55%   |
| Mexico     | 1         | 4.55%   |
| Kazakhstan | 1         | 4.55%   |
| Japan      | 1         | 4.55%   |
| Italy      | 1         | 4.55%   |
| Hungary    | 1         | 4.55%   |
| Denmark    | 1         | 4.55%   |
| Brazil     | 1         | 4.55%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Sydney                    | 2         | 9.09%   |
| Moscow                    | 2         | 9.09%   |
| Yuzhno-Sakhalinsk         | 1         | 4.55%   |
| Wiesmoor                  | 1         | 4.55%   |
| Toms River                | 1         | 4.55%   |
| Schloss Holte-Stukenbrock | 1         | 4.55%   |
| Salto                     | 1         | 4.55%   |
| Portland                  | 1         | 4.55%   |
| Osaka                     | 1         | 4.55%   |
| Norden                    | 1         | 4.55%   |
| Metzingen                 | 1         | 4.55%   |
| Mechanicsburg             | 1         | 4.55%   |
| Karaganda                 | 1         | 4.55%   |
| Jonesboro                 | 1         | 4.55%   |
| El Cerrito                | 1         | 4.55%   |
| Dnipropetrovsk            | 1         | 4.55%   |
| Copenhagen                | 1         | 4.55%   |
| Celaya                    | 1         | 4.55%   |
| Budapest                  | 1         | 4.55%   |
| Albairate                 | 1         | 4.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 19.23%  |
| Hitachi             | 5         | 5      | 19.23%  |
| WDC                 | 3         | 3      | 11.54%  |
| Toshiba             | 2         | 2      | 7.69%   |
| Samsung Electronics | 2         | 2      | 7.69%   |
| Kingston            | 2         | 2      | 7.69%   |
| Zheino              | 1         | 1      | 3.85%   |
| Unknown             | 1         | 1      | 3.85%   |
| OCZ                 | 1         | 1      | 3.85%   |
| Intel               | 1         | 1      | 3.85%   |
| HGST                | 1         | 1      | 3.85%   |
| Hewlett-Packard     | 1         | 1      | 3.85%   |
| ASUS-PHISON         | 1         | 1      | 3.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Samsung SSD 750 EVO 120GB        | 2         | 7.69%   |
| Zheino CHN mSATAM3 128 128GB SSD | 1         | 3.85%   |
| WDC WD5000LPLX-08ZNTT0 500GB     | 1         | 3.85%   |
| WDC WD3200BEVT-60ZCT1 320GB      | 1         | 3.85%   |
| WDC WD1200BEVE-00A0HT0 120GB     | 1         | 3.85%   |
| Unknown SR64G  64GB              | 1         | 3.85%   |
| Toshiba THNSNJ256G8NY 256GB SSD  | 1         | 3.85%   |
| Toshiba MK2576GSX 250GB          | 1         | 3.85%   |
| Seagate ST9160411AS 160GB        | 1         | 3.85%   |
| Seagate ST9160314AS 160GB        | 1         | 3.85%   |
| Seagate ST9160310AS 160GB        | 1         | 3.85%   |
| Seagate ST9160301AS 160GB        | 1         | 3.85%   |
| Seagate ST500LM021-1KJ152 500GB  | 1         | 3.85%   |
| OCZ AGILITY3 120GB SSD           | 1         | 3.85%   |
| Kingston SUV500MS120G 120GB SSD  | 1         | 3.85%   |
| Kingston SUV400S37120G 120GB SSD | 1         | 3.85%   |
| Intel SSDSC2BW180A3H 180GB       | 1         | 3.85%   |
| Hitachi HTS725050A7E630 500GB    | 1         | 3.85%   |
| Hitachi HTS723232A7A364 320GB    | 1         | 3.85%   |
| Hitachi HTS721060G9AT00 64GB     | 1         | 3.85%   |
| Hitachi HTS548040M9AT00 40GB     | 1         | 3.85%   |
| Hitachi HTS541612J9SA00 120GB    | 1         | 3.85%   |
| HGST HTS721010A9E630 1TB         | 1         | 3.85%   |
| HP SSD S750 512GB                | 1         | 3.85%   |
| ASUS-PHISON SSD 8GB              | 1         | 3.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 33.33%  |
| Hitachi | 5         | 5      | 33.33%  |
| WDC     | 3         | 3      | 20%     |
| Toshiba | 1         | 1      | 6.67%   |
| HGST    | 1         | 1      | 6.67%   |

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
| HDD  | 15        | 15     | 57.69%  |
| SSD  | 10        | 10     | 38.46%  |
| MMC  | 1         | 1      | 3.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 22        | 25     | 95.65%  |
| MMC  | 1         | 1      | 4.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 22        | 23     | 91.67%  |
| 0.51-1.0   | 2         | 2      | 8.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 8         | 36.36%  |
| 21-50      | 4         | 18.18%  |
| 1-20       | 4         | 18.18%  |
| 51-100     | 3         | 13.64%  |
| 251-500    | 1         | 4.55%   |
| 501-1000   | 1         | 4.55%   |
| Unknown    | 1         | 4.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 15        | 68.18%  |
| 21-50   | 3         | 13.64%  |
| 101-250 | 2         | 9.09%   |
| 51-100  | 1         | 4.55%   |
| Unknown | 1         | 4.55%   |

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
| Works    | 13        | 15     | 54.17%  |
| Malfunc  | 8         | 8      | 33.33%  |
| Detected | 3         | 3      | 12.5%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 19        | 79.17%  |
| Silicon Integrated Systems [SiS] | 1         | 4.17%   |
| Silicon Image                    | 1         | 4.17%   |
| Nvidia                           | 1         | 4.17%   |
| JMicron Technology               | 1         | 4.17%   |
| AMD                              | 1         | 4.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 10.34%  |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 3         | 10.34%  |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 6.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 6.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 6.9%    |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1         | 3.45%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1         | 3.45%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller               | 1         | 3.45%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 3.45%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 3.45%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 3.45%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 3.45%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 3.45%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 1         | 3.45%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 3.45%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 1         | 3.45%   |
| Intel 82801BA IDE U100 Controller                                              | 1         | 3.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 3.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 3.45%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 1         | 3.45%   |
| AMD SB600 IDE                                                                  | 1         | 3.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| IDE  | 13        | 48.15%  |
| SATA | 11        | 40.74%  |
| RAID | 3         | 11.11%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 22        | 100%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz        | 3         | 13.64%  |
| Intel Pentium M processor 1.60GHz    | 2         | 9.09%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz | 2         | 9.09%   |
| Intel Pentium M processor 1600MHz    | 1         | 4.55%   |
| Intel Pentium M processor 1.86GHz    | 1         | 4.55%   |
| Intel Pentium 4 CPU 2.00GHz          | 1         | 4.55%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz   | 1         | 4.55%   |
| Intel Core i7-7600U CPU @ 2.80GHz    | 1         | 4.55%   |
| Intel Core i7-3740QM CPU @ 2.70GHz   | 1         | 4.55%   |
| Intel Core i5-4300M CPU @ 2.60GHz    | 1         | 4.55%   |
| Intel Core i5-3320M CPU @ 2.60GHz    | 1         | 4.55%   |
| Intel Core i3-2330M CPU @ 2.20GHz    | 1         | 4.55%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz | 1         | 4.55%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz | 1         | 4.55%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz | 1         | 4.55%   |
| Intel Celeron CPU 540 @ 1.86GHz      | 1         | 4.55%   |
| Intel Atom CPU N455 @ 1.66GHz        | 1         | 4.55%   |
| Intel Atom CPU N280 @ 1.66GHz        | 1         | 4.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core 2 Duo | 5         | 22.73%  |
| Intel Atom       | 5         | 22.73%  |
| Intel Pentium M  | 4         | 18.18%  |
| Intel Core i7    | 3         | 13.64%  |
| Intel Core i5    | 2         | 9.09%   |
| Intel Pentium 4  | 1         | 4.55%   |
| Intel Core i3    | 1         | 4.55%   |
| Intel Celeron    | 1         | 4.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 11        | 50%     |
| 2      | 9         | 40.91%  |
| 4      | 2         | 9.09%   |

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
| 2      | 11        | 50%     |
| 1      | 11        | 50%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 13        | 59.09%  |
| 32-bit         | 9         | 40.91%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 0x106c2 | 4         | 18.18%  |
| 0x1067a | 3         | 13.64%  |
| 0x6fd   | 2         | 9.09%   |
| 0x6d6   | 2         | 9.09%   |
| 0x306a9 | 2         | 9.09%   |
| 0xf24   | 1         | 4.55%   |
| 0x906e9 | 1         | 4.55%   |
| 0x806e9 | 1         | 4.55%   |
| 0x6d8   | 1         | 4.55%   |
| 0x695   | 1         | 4.55%   |
| 0x306c3 | 1         | 4.55%   |
| 0x206a7 | 1         | 4.55%   |
| 0x106ca | 1         | 4.55%   |
| 0x10661 | 1         | 4.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Bonnell     | 5         | 22.73%  |
| P6          | 4         | 18.18%  |
| Penryn      | 3         | 13.64%  |
| Core        | 3         | 13.64%  |
| KabyLake    | 2         | 9.09%   |
| IvyBridge   | 2         | 9.09%   |
| SandyBridge | 1         | 4.55%   |
| NetBurst    | 1         | 4.55%   |
| Haswell     | 1         | 4.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 13        | 56.52%  |
| Nvidia | 5         | 21.74%  |
| AMD    | 5         | 21.74%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 4         | 14.29%  |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 4         | 14.29%  |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 2         | 7.14%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 3.57%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 3.57%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 3.57%   |
| Nvidia G98M [GeForce 9300M GS]                                                | 1         | 3.57%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 3.57%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 3.57%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 3.57%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 3.57%   |
| Intel HD Graphics 630                                                         | 1         | 3.57%   |
| Intel HD Graphics 620                                                         | 1         | 3.57%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 1         | 3.57%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 1         | 3.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 3.57%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 1         | 3.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 1         | 3.57%   |
| AMD RV370/M22 [Mobility Radeon X300]                                          | 1         | 3.57%   |
| AMD RV100/M6 [Rage/Radeon Mobility Series]                                    | 1         | 3.57%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                      | 1         | 3.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 11        | 50%     |
| 1 x AMD        | 5         | 22.73%  |
| 1 x Nvidia     | 4         | 18.18%  |
| Other          | 1         | 4.55%   |
| Intel + Nvidia | 1         | 4.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 20        | 90.91%  |
| Proprietary | 1         | 4.55%   |
| Unknown     | 1         | 4.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 14        | 63.64%  |
| Unknown    | 5         | 22.73%  |
| 1.01-2.0   | 2         | 9.09%   |
| 3.01-4.0   | 1         | 4.55%   |

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
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 1         | 6.25%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch          | 1         | 6.25%   |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch          | 1         | 6.25%   |
| HannStar LCD Monitor HSD0325 1024x600 195x113mm 8.9-inch             | 1         | 6.25%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x129mm 10.0-inch             | 1         | 6.25%   |
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
| 1     | 22        | 100%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 11        | 28.95%  |
| Qualcomm Atheros                 | 10        | 26.32%  |
| Realtek Semiconductor            | 6         | 15.79%  |
| Broadcom                         | 4         | 10.53%  |
| Marvell Technology Group         | 2         | 5.26%   |
| Silicon Integrated Systems [SiS] | 1         | 2.63%   |
| Ralink                           | 1         | 2.63%   |
| Qualcomm Atheros Communications  | 1         | 2.63%   |
| Nvidia                           | 1         | 2.63%   |
| Hewlett-Packard                  | 1         | 2.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 4         | 8%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 6%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 4%      |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 4%      |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller             | 2         | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 4%      |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                            | 2         | 4%      |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 4%      |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 1         | 2%      |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 2%      |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 2%      |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 2%      |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 2%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 2%      |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 2%      |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 2%      |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 2%      |
| Nvidia MCP89 Ethernet                                                         | 1         | 2%      |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                       | 1         | 2%      |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                          | 1         | 2%      |
| Intel Wireless 8265 / 8275                                                    | 1         | 2%      |
| Intel Wireless 7260                                                           | 1         | 2%      |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 2%      |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 2%      |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 1         | 2%      |
| Intel Ethernet Connection I217-LM                                             | 1         | 2%      |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 2%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 2%      |
| Intel Centrino Wireless-N 6150                                                | 1         | 2%      |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 2%      |
| Intel Centrino Ultimate-N 6300                                                | 1         | 2%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 2%      |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller              | 1         | 2%      |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                                  | 1         | 2%      |
| Intel 82801BA/BAM AC'97 Modem Controller                                      | 1         | 2%      |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 2%      |
| HP lt2523 Mobile Broadband Device                                             | 1         | 2%      |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                      | 1         | 2%      |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 1         | 2%      |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 39.13%  |
| Qualcomm Atheros                | 8         | 34.78%  |
| Broadcom                        | 3         | 13.04%  |
| Realtek Semiconductor           | 1         | 4.35%   |
| Ralink                          | 1         | 4.35%   |
| Qualcomm Atheros Communications | 1         | 4.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 4         | 16.67%  |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 8.33%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 4.17%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 4.17%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 4.17%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 4.17%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 4.17%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 4.17%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 4.17%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 4.17%   |
| Intel Wireless 7260                                                           | 1         | 4.17%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 4.17%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 4.17%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 1         | 4.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 4.17%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 4.17%   |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 4.17%   |
| Intel Centrino Ultimate-N 6300                                                | 1         | 4.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 4.17%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 1         | 4.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 8         | 38.1%   |
| Realtek Semiconductor            | 5         | 23.81%  |
| Qualcomm Atheros                 | 3         | 14.29%  |
| Marvell Technology Group         | 2         | 9.52%   |
| Silicon Integrated Systems [SiS] | 1         | 4.76%   |
| Nvidia                           | 1         | 4.76%   |
| Broadcom                         | 1         | 4.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller          | 3         | 14.29%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter          | 2         | 9.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet | 2         | 9.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)          | 2         | 9.52%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)             | 2         | 9.52%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter  | 1         | 4.76%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller      | 1         | 4.76%   |
| Nvidia MCP89 Ethernet                                          | 1         | 4.76%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller        | 1         | 4.76%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller           | 1         | 4.76%   |
| Intel Ethernet Connection I217-LM                              | 1         | 4.76%   |
| Intel Ethernet Connection (4) I219-LM                          | 1         | 4.76%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                   | 1         | 4.76%   |
| Intel 82567LM Gigabit Network Connection                       | 1         | 4.76%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express       | 1         | 4.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 21        | 44.68%  |
| Ethernet | 21        | 44.68%  |
| Modem    | 5         | 10.64%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 18        | 85.71%  |
| Ethernet | 3         | 14.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 20        | 90.91%  |
| 1     | 2         | 9.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 19        | 86.36%  |
| Yes  | 3         | 13.64%  |

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
| Intel                            | 19        | 82.61%  |
| Nvidia                           | 2         | 8.7%    |
| Silicon Integrated Systems [SiS] | 1         | 4.35%   |
| AMD                              | 1         | 4.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 20.83%  |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 3         | 12.5%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 8.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 8.33%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 4.17%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 4.17%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 4.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 4.17%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 4.17%   |
| Intel CM238 HD Audio Controller                                            | 1         | 4.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 4.17%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 4.17%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 4.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 4.17%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 4.17%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 9         | 39.13%  |
| SK Hynix            | 5         | 21.74%  |
| Micron Technology   | 2         | 8.7%    |
| Kingston            | 2         | 8.7%    |
| Unknown (8A02)      | 1         | 4.35%   |
| Samsung Electronics | 1         | 4.35%   |
| Crucial             | 1         | 4.35%   |
| Avant               | 1         | 4.35%   |
| Unknown             | 1         | 4.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 1024MB SODIMM DDR                           | 3         | 12.5%   |
| Unknown RAM Module 512MB SODIMM DDR                            | 1         | 4.17%   |
| Unknown RAM Module 2GB SODIMM SDRAM                            | 1         | 4.17%   |
| Unknown RAM Module 256MB DIMM SDRAM                            | 1         | 4.17%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 1         | 4.17%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 4.17%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 4.17%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1         | 4.17%   |
| Unknown (8A02) RAM DDR4 16GB 2400MHz 16GB SODIMM DDR4 2400MT/s | 1         | 4.17%   |
| SK Hynix RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 4.17%   |
| SK Hynix RAM Module 1GB SODIMM DDR3 1067MT/s                   | 1         | 4.17%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s           | 1         | 4.17%   |
| SK Hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 4.17%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 4.17%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s          | 1         | 4.17%   |
| Micron RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 4.17%   |
| Micron RAM 8HTF12864HDY-800G1 1024MB SODIMM DDR2 800MT/s       | 1         | 4.17%   |
| Kingston RAM MSI24D4S7D8MB-16 16384MB SODIMM DDR4 2400MT/s     | 1         | 4.17%   |
| Kingston RAM 9905428-095.D00LF 8GB SODIMM DDR3 1600MT/s        | 1         | 4.17%   |
| Crucial RAM CT102464BF160B.M16 8192MB SODIMM DDR3 1600MT/s     | 1         | 4.17%   |
| Avant RAM H641GU67F1600G 8GB SODIMM DDR3 1600MT/s              | 1         | 4.17%   |
| Unknown                                                        | 1         | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| SDRAM | 5         | 25%     |
| DDR3  | 5         | 25%     |
| DDR2  | 4         | 20%     |
| DDR   | 4         | 20%     |
| DDR4  | 2         | 10%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 19        | 95%     |
| DIMM   | 1         | 5%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 1024  | 8         | 36.36%  |
| 2048  | 5         | 22.73%  |
| 8192  | 4         | 18.18%  |
| 512   | 2         | 9.09%   |
| 16384 | 1         | 4.55%   |
| 4096  | 1         | 4.55%   |
| 256   | 1         | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 8         | 38.1%   |
| 1600    | 3         | 14.29%  |
| 1067    | 2         | 9.52%   |
| 2667    | 1         | 4.76%   |
| 2400    | 1         | 4.76%   |
| 1333    | 1         | 4.76%   |
| 975     | 1         | 4.76%   |
| 800     | 1         | 4.76%   |
| 667     | 1         | 4.76%   |
| 533     | 1         | 4.76%   |
| 266     | 1         | 4.76%   |

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
| Chicony Electronics                    | 4         | 28.57%  |
| Pixart Imaging                         | 2         | 14.29%  |
| Microdia                               | 2         | 14.29%  |
| Suyin                                  | 1         | 7.14%   |
| Sunplus Innovation Technology          | 1         | 7.14%   |
| Importek                               | 1         | 7.14%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 7.14%   |
| Apple                                  | 1         | 7.14%   |
| Acer                                   | 1         | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Pixart Imaging GE 1.3 MP MiniCam Pro                | 2         | 14.29%  |
| Suyin Lenovo EasyCamera                             | 1         | 7.14%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 7.14%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 7.14%   |
| Microdia Integrated Webcam                          | 1         | 7.14%   |
| Importek FJ Camera                                  | 1         | 7.14%   |
| Chicony VGA 30fps UVC Webcam                        | 1         | 7.14%   |
| Chicony Integrated HP HD Webcam                     | 1         | 7.14%   |
| Chicony HP HD Webcam [Fixed]                        | 1         | 7.14%   |
| Chicony CNF8243 Webcam                              | 1         | 7.14%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC) | 1         | 7.14%   |
| Apple Built-in iSight                               | 1         | 7.14%   |
| Acer HP Webcam                                      | 1         | 7.14%   |

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
| 0     | 17        | 77.27%  |
| 1     | 4         | 18.18%  |
| 2     | 1         | 4.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 3         | 50%     |
| Graphics card      | 2         | 33.33%  |
| Chipcard           | 1         | 16.67%  |

