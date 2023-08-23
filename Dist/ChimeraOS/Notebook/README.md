ChimeraOS - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

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

Total: 32

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| GPD           | P2 MAX                      | [064bc78973](https://linux-hardware.org/?probe=064bc78973) | Aug 09, 2023 |
| HP            | Victus by Laptop 16-d1xx... | [74c80ca51b](https://linux-hardware.org/?probe=74c80ca51b) | Aug 06, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d3e22fde36](https://linux-hardware.org/?probe=d3e22fde36) | Jul 25, 2023 |
| Lenovo        | ThinkPad E15 20RD0011IX     | [c7a1caa230](https://linux-hardware.org/?probe=c7a1caa230) | Jul 25, 2023 |
| Acer          | Aspire A715-42G             | [ac10700edb](https://linux-hardware.org/?probe=ac10700edb) | Jul 13, 2023 |
| AMI           | Unknown                     | [88da6b0232](https://linux-hardware.org/?probe=88da6b0232) | Jun 25, 2023 |
| Acer          | Aspire A315-58G             | [ea2b8a58b1](https://linux-hardware.org/?probe=ea2b8a58b1) | Jun 22, 2023 |
| Razer         | Blade 14 - RZ09-0370        | [4932ae40b6](https://linux-hardware.org/?probe=4932ae40b6) | Jun 13, 2023 |
| Google        | Snappy                      | [737988d62e](https://linux-hardware.org/?probe=737988d62e) | Jun 11, 2023 |
| Google        | Snappy                      | [f228dabe46](https://linux-hardware.org/?probe=f228dabe46) | Jun 11, 2023 |
| Lenovo        | Y50-70 20378                | [5e060b53c2](https://linux-hardware.org/?probe=5e060b53c2) | Jun 10, 2023 |
| Lenovo        | Y50-70 20378                | [0d548e314b](https://linux-hardware.org/?probe=0d548e314b) | Jun 10, 2023 |
| Acer          | Nitro AN515-51              | [4bbf7dc69e](https://linux-hardware.org/?probe=4bbf7dc69e) | May 21, 2023 |
| Micro Elec... | MG-VCP17I-3070              | [8ba5bb4bc7](https://linux-hardware.org/?probe=8ba5bb4bc7) | May 19, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [79bdb284fe](https://linux-hardware.org/?probe=79bdb284fe) | May 09, 2023 |
| MSI           | CX62 6QD                    | [9c6b781beb](https://linux-hardware.org/?probe=9c6b781beb) | May 02, 2023 |
| HP            | 250 G4 Notebook PC          | [08036de728](https://linux-hardware.org/?probe=08036de728) | Apr 15, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [a34f2e065b](https://linux-hardware.org/?probe=a34f2e065b) | Apr 14, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [cacab44211](https://linux-hardware.org/?probe=cacab44211) | Apr 13, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [2a4894bdc0](https://linux-hardware.org/?probe=2a4894bdc0) | Apr 13, 2023 |
| MSI           | MS-7C91                     | [663c6729cb](https://linux-hardware.org/?probe=663c6729cb) | Apr 12, 2023 |
| Razer         | Blade Pro 17 (Early 2020... | [36d75e1d7f](https://linux-hardware.org/?probe=36d75e1d7f) | Mar 26, 2023 |
| Razer         | Blade Pro 17 (Early 2020... | [244b228a30](https://linux-hardware.org/?probe=244b228a30) | Mar 26, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [8a92687be7](https://linux-hardware.org/?probe=8a92687be7) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [f383688a79](https://linux-hardware.org/?probe=f383688a79) | Mar 23, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [de9712600d](https://linux-hardware.org/?probe=de9712600d) | Mar 20, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [1ee17b12bd](https://linux-hardware.org/?probe=1ee17b12bd) | Mar 19, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [b8ea458df5](https://linux-hardware.org/?probe=b8ea458df5) | Mar 08, 2023 |
| Acer          | Aspire A515-51G             | [432235c684](https://linux-hardware.org/?probe=432235c684) | Feb 25, 2023 |
| MSI           | GE75 Raider 10SF            | [cc21335206](https://linux-hardware.org/?probe=cc21335206) | Feb 24, 2023 |
| ASUSTek       | K45VM                       | [06af577a0c](https://linux-hardware.org/?probe=06af577a0c) | Feb 04, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [f5ff2f8568](https://linux-hardware.org/?probe=f5ff2f8568) | Jan 06, 2023 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| ChimeraOS 39   | 8         | 29.63%  |
| ChimeraOS 42   | 7         | 25.93%  |
| ChimeraOS 41   | 5         | 18.52%  |
| ChimeraOS 43-1 | 3         | 11.11%  |
| ChimeraOS 38   | 2         | 7.41%   |
| ChimeraOS 43   | 1         | 3.7%    |
| ChimeraOS      | 1         | 3.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| ChimeraOS | 27        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 6.1.11-arch1-1    | 8         | 29.63%  |
| 6.1.27-1-lts      | 7         | 25.93%  |
| 6.1.21-1-lts      | 5         | 18.52%  |
| 6.3.9-chimeraos-1 | 4         | 14.81%  |
| 6.1.1-arch1-1     | 2         | 7.41%   |
| 6.4.9-0-generic   | 1         | 3.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1.11  | 8         | 29.63%  |
| 6.1.27  | 7         | 25.93%  |
| 6.1.21  | 5         | 18.52%  |
| 6.3.9   | 4         | 14.81%  |
| 6.1.1   | 2         | 7.41%   |
| 6.4.9   | 1         | 3.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 22        | 81.48%  |
| 6.3     | 4         | 14.81%  |
| 6.4     | 1         | 3.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 27        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| GNOME | 27        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 25        | 92.59%  |
| X11     | 2         | 7.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 27        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 22        | 81.48%  |
| it_IT | 2         | 7.41%   |
| pt_BR | 1         | 3.7%    |
| es_ES | 1         | 3.7%    |
| C     | 1         | 3.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 27        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 26        | 96.3%   |
| Ext4  | 1         | 3.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 27        | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 27        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 27        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo            | 6         | 22.22%  |
| Acer              | 4         | 14.81%  |
| MSI               | 3         | 11.11%  |
| Hewlett-Packard   | 3         | 11.11%  |
| ASUSTek Computer  | 3         | 11.11%  |
| Razer             | 2         | 7.41%   |
| ONE-NETBOOK       | 2         | 7.41%   |
| Micro Electronics | 1         | 3.7%    |
| GPD               | 1         | 3.7%    |
| Google            | 1         | 3.7%    |
| AMI               | 1         | 3.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| ONE-NETBOOK ONEXPLAYER 2 ARP23              | 2         | 7.41%   |
| Razer Blade Pro 17 (Early 2020) - RZ09-0329 | 1         | 3.7%    |
| Razer Blade 14 - RZ09-0370                  | 1         | 3.7%    |
| MSI MS-7C91                                 | 1         | 3.7%    |
| MSI GE75 Raider 10SF                        | 1         | 3.7%    |
| MSI CX62 6QD                                | 1         | 3.7%    |
| Micro MG-VCP17I-3070                        | 1         | 3.7%    |
| Lenovo Y50-70 20378                         | 1         | 3.7%    |
| Lenovo ThinkPad E15 20RD0011IX              | 1         | 3.7%    |
| Lenovo Legion Y540-15IRH 81SX               | 1         | 3.7%    |
| Lenovo IdeaPad 700-15ISK 80RU               | 1         | 3.7%    |
| Lenovo IdeaPad 320-15IKB 80YH               | 1         | 3.7%    |
| Lenovo IdeaPad 3 15ADA05 81W1               | 1         | 3.7%    |
| HP Victus by Laptop 16-d1xxx                | 1         | 3.7%    |
| HP EliteBook 850 G8 Notebook PC             | 1         | 3.7%    |
| HP 250 G4 Notebook PC                       | 1         | 3.7%    |
| GPD P2 MAX                                  | 1         | 3.7%    |
| Google Snappy                               | 1         | 3.7%    |
| ASUS TUF Gaming FX505DV_FX505DV             | 1         | 3.7%    |
| ASUS ROG Zephyrus G15 GA503QM_GA503QM       | 1         | 3.7%    |
| ASUS K45VM                                  | 1         | 3.7%    |
| Acer Nitro AN515-51                         | 1         | 3.7%    |
| Acer Aspire A715-42G                        | 1         | 3.7%    |
| Acer Aspire A515-51G                        | 1         | 3.7%    |
| Acer Aspire A315-58G                        | 1         | 3.7%    |
| Unknown                                     | 1         | 3.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo IdeaPad         | 3         | 11.11%  |
| Acer Aspire            | 3         | 11.11%  |
| Razer Blade            | 2         | 7.41%   |
| ONE-NETBOOK ONEXPLAYER | 2         | 7.41%   |
| MSI MS-7C91            | 1         | 3.7%    |
| MSI GE75               | 1         | 3.7%    |
| MSI CX62               | 1         | 3.7%    |
| Micro MG-VCP17I-3070   | 1         | 3.7%    |
| Lenovo Y50-70          | 1         | 3.7%    |
| Lenovo ThinkPad        | 1         | 3.7%    |
| Lenovo Legion          | 1         | 3.7%    |
| HP Victus              | 1         | 3.7%    |
| HP EliteBook           | 1         | 3.7%    |
| HP 250                 | 1         | 3.7%    |
| GPD P2                 | 1         | 3.7%    |
| Google Snappy          | 1         | 3.7%    |
| ASUS TUF               | 1         | 3.7%    |
| ASUS ROG               | 1         | 3.7%    |
| ASUS K45VM             | 1         | 3.7%    |
| Acer Nitro             | 1         | 3.7%    |
| Unknown                | 1         | 3.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 5         | 18.52%  |
| 2020 | 5         | 18.52%  |
| 2019 | 4         | 14.81%  |
| 2023 | 3         | 11.11%  |
| 2017 | 3         | 11.11%  |
| 2016 | 2         | 7.41%   |
| 2015 | 2         | 7.41%   |
| 2022 | 1         | 3.7%    |
| 2014 | 1         | 3.7%    |
| 2012 | 1         | 3.7%    |

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
| Disabled | 27        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 26        | 96.3%   |
| Yes  | 1         | 3.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 7         | 25.93%  |
| 32.01-64.0  | 5         | 18.52%  |
| 8.01-16.0   | 5         | 18.52%  |
| 4.01-8.0    | 4         | 14.81%  |
| 3.01-4.0    | 3         | 11.11%  |
| 64.01-256.0 | 2         | 7.41%   |
| 24.01-32.0  | 1         | 3.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 10        | 37.04%  |
| 1.01-2.0 | 8         | 29.63%  |
| 3.01-4.0 | 6         | 22.22%  |
| 4.01-8.0 | 3         | 11.11%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 14        | 51.85%  |
| 2      | 12        | 44.44%  |
| 3      | 1         | 3.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 26        | 96.3%   |
| Yes       | 1         | 3.7%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 70.37%  |
| No        | 8         | 29.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 96.3%   |
| No        | 1         | 3.7%    |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 10        | 37.04%  |
| UK           | 2         | 7.41%   |
| Saudi Arabia | 2         | 7.41%   |
| Italy        | 2         | 7.41%   |
| Brazil       | 2         | 7.41%   |
| Vietnam      | 1         | 3.7%    |
| Switzerland  | 1         | 3.7%    |
| Spain        | 1         | 3.7%    |
| Romania      | 1         | 3.7%    |
| Poland       | 1         | 3.7%    |
| Netherlands  | 1         | 3.7%    |
| Hungary      | 1         | 3.7%    |
| Costa Rica   | 1         | 3.7%    |
| Belgium      | 1         | 3.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Wroclaw                  | 1         | 3.7%    |
| Virginia Beach           | 1         | 3.7%    |
| Tulcea                   | 1         | 3.7%    |
| St Louis                 | 1         | 3.7%    |
| Santa Cruz das Palmeiras | 1         | 3.7%    |
| San José                | 1         | 3.7%    |
| Saltillo                 | 1         | 3.7%    |
| Ridley Park              | 1         | 3.7%    |
| Pittsburg                | 1         | 3.7%    |
| Pennsauken               | 1         | 3.7%    |
| Parma                    | 1         | 3.7%    |
| Newport News             | 1         | 3.7%    |
| Monticello               | 1         | 3.7%    |
| Milan                    | 1         | 3.7%    |
| Legazpia                 | 1         | 3.7%    |
| Jeddah                   | 1         | 3.7%    |
| Hot Springs              | 1         | 3.7%    |
| Dammam                   | 1         | 3.7%    |
| Chattanooga              | 1         | 3.7%    |
| Budapest                 | 1         | 3.7%    |
| Brussels                 | 1         | 3.7%    |
| Binh Duong               | 1         | 3.7%    |
| Biel/Bienne              | 1         | 3.7%    |
| Belfast                  | 1         | 3.7%    |
| Barnet                   | 1         | 3.7%    |
| Araras                   | 1         | 3.7%    |
| Almere Stad              | 1         | 3.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 7         | 7      | 17.07%  |
| WDC                       | 5         | 5      | 12.2%   |
| Unknown                   | 4         | 4      | 9.76%   |
| Micron Technology         | 4         | 4      | 9.76%   |
| Kingston                  | 4         | 4      | 9.76%   |
| Seagate                   | 3         | 3      | 7.32%   |
| Sandisk                   | 3         | 3      | 7.32%   |
| Toshiba                   | 2         | 2      | 4.88%   |
| Micron/Crucial Technology | 2         | 2      | 4.88%   |
| Intel                     | 2         | 2      | 4.88%   |
| SK hynix                  | 1         | 1      | 2.44%   |
| Phison Electronics        | 1         | 1      | 2.44%   |
| KIOXIA                    | 1         | 1      | 2.44%   |
| JMicron Technology        | 1         | 1      | 2.44%   |
| Biwin Storage Technology  | 1         | 1      | 2.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 3         | 7.32%   |
| Unknown MMC Card  64GB                              | 2         | 4.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 2         | 4.88%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 2         | 4.88%   |
| WDC WD7500BPVT-80HXZT3 752GB                        | 1         | 2.44%   |
| WDC WD20SPZX-08UA7 2TB                              | 1         | 2.44%   |
| WDC WD201KFGX-68BKJN0 20TB                          | 1         | 2.44%   |
| WDC WD10SPCX-24HWST1 1TB                            | 1         | 2.44%   |
| WDC WD10JPLX-00MBPT0 1TB                            | 1         | 2.44%   |
| Unknown NVMe SSD Drive 1024GB                       | 1         | 2.44%   |
| Unknown MMC Card  16GB                              | 1         | 2.44%   |
| Toshiba XG6 NVMe SSD Controller 512GB               | 1         | 2.44%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 2.44%   |
| SK hynix HFM512GD3JX016N 512GB                      | 1         | 2.44%   |
| Seagate ST9320423AS 320GB                           | 1         | 2.44%   |
| Seagate ST1000LM048-2E7172 1TB                      | 1         | 2.44%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 2.44%   |
| Sandisk WD_BLACK SN770 2TB                          | 1         | 2.44%   |
| Sandisk WD Black SN850 1TB                          | 1         | 2.44%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB   | 1         | 2.44%   |
| Samsung Portable SSD T5 1TB                         | 1         | 2.44%   |
| Samsung MZNLF128HCHP-000H1 128GB SSD                | 1         | 2.44%   |
| Phison E12 NVMe Controller 2TB                      | 1         | 2.44%   |
| Micron MTFDHBA512QFD 512GB                          | 1         | 2.44%   |
| Micron 2200V_MTFDHBA512TCK 512GB                    | 1         | 2.44%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD                 | 1         | 2.44%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                 | 1         | 2.44%   |
| KIOXIA KBG40ZNT512G TOSHIBA MEMORY 512GB            | 1         | 2.44%   |
| Kingston SV300S37A120G 120GB SSD                    | 1         | 2.44%   |
| Kingston SV100S2128G 128GB SSD                      | 1         | 2.44%   |
| Kingston SA400S37480G 480GB SSD                     | 1         | 2.44%   |
| Kingston SA400S37120G 120GB SSD                     | 1         | 2.44%   |
| JMicron Tech 250GB                                  | 1         | 2.44%   |
| Intel SSDPEKNU512GZ 512GB                           | 1         | 2.44%   |
| Intel SSD 600P Series 512GB                         | 1         | 2.44%   |
| Biwin Storage ONE XPLAYER Q1 2TB                    | 1         | 2.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 55.56%  |
| Seagate | 3         | 3      | 33.33%  |
| Toshiba | 1         | 1      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 4         | 4      | 50%     |
| Samsung Electronics | 2         | 2      | 25%     |
| Micron Technology   | 2         | 2      | 25%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 18        | 20     | 48.65%  |
| HDD     | 8         | 9      | 21.62%  |
| SSD     | 7         | 8      | 18.92%  |
| MMC     | 3         | 3      | 8.11%   |
| Unknown | 1         | 1      | 2.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 18        | 20     | 51.43%  |
| SATA | 12        | 16     | 34.29%  |
| MMC  | 3         | 3      | 8.57%   |
| SAS  | 2         | 2      | 5.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 7         | 7      | 46.67%  |
| 0.01-0.5   | 6         | 8      | 40%     |
| 10.01-20.0 | 1         | 1      | 6.67%   |
| 1.01-2.0   | 1         | 1      | 6.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1001-2000      | 11        | 40.74%  |
| More than 3000 | 8         | 29.63%  |
| 251-500        | 5         | 18.52%  |
| 101-250        | 2         | 7.41%   |
| 501-1000       | 1         | 3.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 10        | 37.04%  |
| 101-250        | 5         | 18.52%  |
| 51-100         | 5         | 18.52%  |
| 251-500        | 4         | 14.81%  |
| More than 3000 | 1         | 3.7%    |
| 1-20           | 1         | 3.7%    |
| 501-1000       | 1         | 3.7%    |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 27        | 41     | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 16        | 43.24%  |
| Samsung Electronics          | 5         | 13.51%  |
| SanDisk                      | 3         | 8.11%   |
| AMD                          | 3         | 8.11%   |
| Micron/Crucial Technology    | 2         | 5.41%   |
| Micron Technology            | 2         | 5.41%   |
| Toshiba America Info Systems | 1         | 2.7%    |
| SK hynix                     | 1         | 2.7%    |
| Phison Electronics           | 1         | 2.7%    |
| KIOXIA                       | 1         | 2.7%    |
| INNOGRIT                     | 1         | 2.7%    |
| Biwin Storage Technology     | 1         | 2.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 7.5%    |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 7.5%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 7.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 5%      |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 5%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 5%      |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 5%      |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 5%      |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 2.5%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 2.5%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 2.5%    |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1         | 2.5%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 2.5%    |
| Phison E12 NVMe Controller                                                     | 1         | 2.5%    |
| Micron 2210 NVMe SSD [Cobain]                                                  | 1         | 2.5%    |
| Micron 2200S NVMe SSD [Cassandra]                                              | 1         | 2.5%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 1         | 2.5%    |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 2.5%    |
| Intel Tiger Lake SATA AHCI Controller                                          | 1         | 2.5%    |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1         | 2.5%    |
| Intel SSD 600P Series                                                          | 1         | 2.5%    |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 2.5%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 2.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 2.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 2.5%    |
| INNOGRIT NVMe SSD Controller IG5236                                            | 1         | 2.5%    |
| Biwin Storage Non-Volatile memory controller                                   | 1         | 2.5%    |
| AMD 500 Series Chipset SATA Controller                                         | 1         | 2.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 18        | 47.37%  |
| SATA | 16        | 42.11%  |
| RAID | 4         | 10.53%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 19        | 70.37%  |
| AMD    | 8         | 29.63%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 7.41%   |
| AMD Ryzen 7 6800U with Radeon Graphics        | 2         | 7.41%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 1         | 3.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 3.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 3.7%    |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 3.7%    |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 3.7%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 3.7%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 3.7%    |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 3.7%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 3.7%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 3.7%    |
| Intel Core i5-4210H CPU @ 2.90GHz             | 1         | 3.7%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 3.7%    |
| Intel Atom x7-Z8700 CPU @ 1.60GHz             | 1         | 3.7%    |
| Intel 12th Gen Core i7-12700H                 | 1         | 3.7%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 3.7%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 3.7%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 3.7%    |
| AMD Ryzen 9 5900X 12-Core Processor           | 1         | 3.7%    |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1         | 3.7%    |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 1         | 3.7%    |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 3.7%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 3.7%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 3.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Intel Core i7 | 6         | 22.22%  |
| Intel Core i5 | 6         | 22.22%  |
| Other         | 4         | 14.81%  |
| AMD Ryzen 9   | 3         | 11.11%  |
| AMD Ryzen 7   | 3         | 11.11%  |
| AMD Ryzen 5   | 2         | 7.41%   |
| Intel Core m3 | 1         | 3.7%    |
| Intel Celeron | 1         | 3.7%    |
| Intel Atom    | 1         | 3.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 10        | 37.04%  |
| 8      | 6         | 22.22%  |
| 2      | 6         | 22.22%  |
| 6      | 3         | 11.11%  |
| 14     | 1         | 3.7%    |
| 12     | 1         | 3.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 27        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 22        | 81.48%  |
| 1      | 5         | 18.52%  |

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


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 27        | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KabyLake   | 6         | 22.22%  |
| Unknown    | 5         | 18.52%  |
| Zen 3      | 3         | 11.11%  |
| Skylake    | 3         | 11.11%  |
| Zen+       | 2         | 7.41%   |
| TigerLake  | 2         | 7.41%   |
| CometLake  | 2         | 7.41%   |
| Silvermont | 1         | 3.7%    |
| IvyBridge  | 1         | 3.7%    |
| Haswell    | 1         | 3.7%    |
| Goldmont   | 1         | 3.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 17        | 40.48%  |
| Nvidia | 16        | 38.1%   |
| AMD    | 9         | 21.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 4.76%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 2         | 4.76%   |
| Intel HD Graphics 530                                                                    | 2         | 4.76%   |
| AMD Rembrandt [Radeon 680M]                                                              | 2         | 4.76%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 4.76%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 4.76%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 2.38%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 2.38%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 2.38%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                                    | 1         | 2.38%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 2.38%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 2.38%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 2.38%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 2.38%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 2.38%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 2.38%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 2.38%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 2.38%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.38%   |
| Intel UHD Graphics 615                                                                   | 1         | 2.38%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 2.38%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 2.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 2.38%   |
| Intel HD Graphics 630                                                                    | 1         | 2.38%   |
| Intel HD Graphics 620                                                                    | 1         | 2.38%   |
| Intel HD Graphics 500                                                                    | 1         | 2.38%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 2.38%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 2.38%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 2.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.38%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 1         | 2.38%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 2.38%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 2.38%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                                 | 1         | 2.38%   |
| AMD Lucienne                                                                             | 1         | 2.38%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 1         | 2.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 10        | 37.04%  |
| 1 x Intel      | 5         | 18.52%  |
| AMD + Nvidia   | 4         | 14.81%  |
| 1 x AMD        | 4         | 14.81%  |
| 1 x Nvidia     | 2         | 7.41%   |
| Other          | 1         | 3.7%    |
| Intel + AMD    | 1         | 3.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Proprietary | 15        | 55.56%  |
| Free        | 12        | 44.44%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 6         | 23.08%  |
| BOE                 | 6         | 23.08%  |
| LG Display          | 4         | 15.38%  |
| AU Optronics        | 3         | 11.54%  |
| Samsung Electronics | 2         | 7.69%   |
| TMX                 | 1         | 3.85%   |
| Sharp               | 1         | 3.85%   |
| PANDA               | 1         | 3.85%   |
| Goldstar            | 1         | 3.85%   |
| Fujitsu Siemens     | 1         | 3.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE TV080WUM-NL0 BOE1003 1600x2560 113x181mm 8.4-inch                | 2         | 7.69%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch              | 1         | 3.85%   |
| Sharp LQ173M1JW02 SHP14DB 1920x1080 382x215mm 17.3-inch              | 1         | 3.85%   |
| Samsung Electronics QBQ95 SAM7229 3840x2160 1872x1053mm 84.6-inch    | 1         | 3.85%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch | 1         | 3.85%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 1         | 3.85%   |
| LG Display LCD Monitor LGD071E 1920x1080 344x194mm 15.5-inch         | 1         | 3.85%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch         | 1         | 3.85%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch         | 1         | 3.85%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 1         | 3.85%   |
| Goldstar M237WDP GSM5779 1920x1080 598x336mm 27.0-inch               | 1         | 3.85%   |
| Fujitsu Siemens B22T-7 LED PG FUS082A 1920x1080 477x268mm 21.5-inch  | 1         | 3.85%   |
| Chimei Innolux LCD Monitor CMN176E 1920x1080 381x214mm 17.2-inch     | 1         | 3.85%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 1         | 3.85%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 1         | 3.85%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 1         | 3.85%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch     | 1         | 3.85%   |
| Chimei Innolux LCD Monitor CMN1540 2560x1440 344x193mm 15.5-inch     | 1         | 3.85%   |
| BOE LCD Monitor BOE0AAD 1920x1080 355x200mm 16.0-inch                | 1         | 3.85%   |
| BOE LCD Monitor BOE0977 2560x1440 381x214mm 17.2-inch                | 1         | 3.85%   |
| BOE LCD Monitor BOE0816 1366x768 344x193mm 15.5-inch                 | 1         | 3.85%   |
| BOE LCD Monitor BOE065D 1920x1080 344x194mm 15.5-inch                | 1         | 3.85%   |
| AU Optronics LCD Monitor AUOD0ED 1920x1080 344x193mm 15.5-inch       | 1         | 3.85%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 1         | 3.85%   |
| AU Optronics LCD Monitor AUO135C 1366x768 256x144mm 11.6-inch        | 1         | 3.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 14        | 56%     |
| 1366x768 (WXGA) | 5         | 20%     |
| 2560x1440 (QHD) | 3         | 12%     |
| 1600x2560       | 2         | 8%      |
| 3840x2160 (4K)  | 1         | 4%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 14        | 53.85%  |
| 17     | 3         | 11.54%  |
| 14     | 2         | 7.69%   |
| 8      | 2         | 7.69%   |
| 84     | 1         | 3.85%   |
| 27     | 1         | 3.85%   |
| 21     | 1         | 3.85%   |
| 16     | 1         | 3.85%   |
| 11     | 1         | 3.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 16        | 61.54%  |
| 351-400     | 4         | 15.38%  |
| 101-200     | 2         | 7.69%   |
| 501-600     | 1         | 3.85%   |
| 401-500     | 1         | 3.85%   |
| 201-300     | 1         | 3.85%   |
| 1501-2000   | 1         | 3.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 23        | 92%     |
| 0.62  | 2         | 8%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 15        | 57.69%  |
| 121-130        | 3         | 11.54%  |
| 81-90          | 2         | 7.69%   |
| 1-40           | 2         | 7.69%   |
| More than 1000 | 1         | 3.85%   |
| 51-60          | 1         | 3.85%   |
| 301-350        | 1         | 3.85%   |
| 201-250        | 1         | 3.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 14        | 53.85%  |
| 101-120       | 5         | 19.23%  |
| 161-240       | 3         | 11.54%  |
| More than 240 | 2         | 7.69%   |
| 51-100        | 2         | 7.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 22        | 81.48%  |
| 2     | 3         | 11.11%  |
| 0     | 2         | 7.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 17        | 38.64%  |
| Intel                 | 14        | 31.82%  |
| Qualcomm Atheros      | 7         | 15.91%  |
| MediaTek              | 4         | 9.09%   |
| Broadcom Limited      | 1         | 2.27%   |
| Broadcom              | 1         | 2.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 28.26%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 6.52%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 6.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 6.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 4.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 4.35%   |
| Intel Wireless 7265                                               | 2         | 4.35%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 4.35%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 4.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 2.17%   |
| Realtek PCIe GbE Family Controller                                | 1         | 2.17%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.17%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 2.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 2.17%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 2.17%   |
| Intel Wireless 3165                                               | 1         | 2.17%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 2.17%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 2.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 2.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 2.17%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 1         | 2.17%   |
| Broadcom BCM4356 802.11ac Wireless Network Adapter                | 1         | 2.17%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 14        | 51.85%  |
| Qualcomm Atheros      | 5         | 18.52%  |
| MediaTek              | 4         | 14.81%  |
| Realtek Semiconductor | 2         | 7.41%   |
| Broadcom Limited      | 1         | 3.7%    |
| Broadcom              | 1         | 3.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 3         | 11.11%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 3         | 11.11%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 2         | 7.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 2         | 7.41%   |
| Intel Wireless 7265                                           | 2         | 7.41%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 7.41%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 7.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 3.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 3.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 1         | 3.7%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 1         | 3.7%    |
| Intel Wireless 3165                                           | 1         | 3.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                | 1         | 3.7%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 3.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 1         | 3.7%    |
| Intel Cannon Lake PCH CNVi WiFi                               | 1         | 3.7%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter    | 1         | 3.7%    |
| Broadcom BCM4356 802.11ac Wireless Network Adapter            | 1         | 3.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 17        | 89.47%  |
| Qualcomm Atheros      | 2         | 10.53%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 68.42%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 15.79%  |
| Realtek PCIe GbE Family Controller                                | 1         | 5.26%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 5.26%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 5.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 58.7%   |
| Ethernet | 19        | 41.3%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 23        | 82.14%  |
| Ethernet | 5         | 17.86%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 19        | 70.37%  |
| 1     | 8         | 29.63%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 19        | 70.37%  |
| Yes  | 8         | 29.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 53.85%  |
| Lite-On Technology              | 3         | 11.54%  |
| IMC Networks                    | 3         | 11.54%  |
| Qualcomm Atheros Communications | 2         | 7.69%   |
| Realtek Semiconductor           | 1         | 3.85%   |
| MediaTek                        | 1         | 3.85%   |
| Foxconn / Hon Hai               | 1         | 3.85%   |
| Cambridge Silicon Radio         | 1         | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 5         | 19.23%  |
| Intel Bluetooth wireless interface                  | 4         | 15.38%  |
| Intel AX210 Bluetooth                               | 3         | 11.54%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 7.69%   |
| IMC Networks Wireless_Device                        | 2         | 7.69%   |
| Realtek Bluetooth Radio                             | 1         | 3.85%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 3.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 3.85%   |
| MediaTek Wireless_Device                            | 1         | 3.85%   |
| Lite-On Wireless_Device                             | 1         | 3.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 3.85%   |
| Lite-On Bluetooth Device                            | 1         | 3.85%   |
| IMC Networks Bluetooth Radio                        | 1         | 3.85%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 3.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 18        | 47.37%  |
| Nvidia                 | 10        | 26.32%  |
| AMD                    | 8         | 21.05%  |
| Sony                   | 1         | 2.63%   |
| Generalplus Technology | 1         | 2.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                              | 7         | 15.56%  |
| Intel Sunrise Point-LP HD Audio                                     | 4         | 8.89%   |
| Nvidia TU106 High Definition Audio Controller                       | 2         | 4.44%   |
| Nvidia GA106 High Definition Audio Controller                       | 2         | 4.44%   |
| Nvidia GA104 High Definition Audio Controller                       | 2         | 4.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 2         | 4.44%   |
| Intel Comet Lake PCH cAVS                                           | 2         | 4.44%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 2         | 4.44%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 2         | 4.44%   |
| AMD Rembrandt Radeon High Definition Audio Controller               | 2         | 4.44%   |
| Sony DualSense wireless controller (PS5)                            | 1         | 2.22%   |
| Nvidia TU116 High Definition Audio Controller                       | 1         | 2.22%   |
| Nvidia TU104 HD Audio Controller                                    | 1         | 2.22%   |
| Nvidia GP107GL High Definition Audio Controller                     | 1         | 2.22%   |
| Nvidia GF108 High Definition Audio Controller                       | 1         | 2.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1         | 2.22%   |
| Intel Tiger Lake-H HD Audio Controller                              | 1         | 2.22%   |
| Intel Comet Lake PCH-LP cAVS                                        | 1         | 2.22%   |
| Intel CM238 HD Audio Controller                                     | 1         | 2.22%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster   | 1         | 2.22%   |
| Intel Cannon Lake PCH cAVS                                          | 1         | 2.22%   |
| Intel Alder Lake PCH-P High Definition Audio Controller             | 1         | 2.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 1         | 2.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 1         | 2.22%   |
| Generalplus Technology USB Audio Device                             | 1         | 2.22%   |
| AMD Starship/Matisse HD Audio Controller                            | 1         | 2.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 1         | 2.22%   |
| AMD Navi 31 HDMI/DP Audio                                           | 1         | 2.22%   |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 8         | 42.11%  |
| IMC Networks                  | 4         | 21.05%  |
| Quanta                        | 2         | 10.53%  |
| Sunplus Innovation Technology | 1         | 5.26%   |
| Silicon Motion                | 1         | 5.26%   |
| Microdia                      | 1         | 5.26%   |
| Bison Electronics             | 1         | 5.26%   |
| Acer                          | 1         | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| IMC Networks Integrated Camera    | 3         | 15.79%  |
| Chicony Integrated Camera         | 2         | 10.53%  |
| Sunplus HD WebCam                 | 1         | 5.26%   |
| Silicon Motion 300k Pixel Camera  | 1         | 5.26%   |
| Quanta HP HD Camera               | 1         | 5.26%   |
| Quanta HD User Facing             | 1         | 5.26%   |
| Microdia HP Webcam                | 1         | 5.26%   |
| IMC Networks USB2.0 HD UVC WebCam | 1         | 5.26%   |
| Chicony USB2.0 0.3M UVC WebCam    | 1         | 5.26%   |
| Chicony Integrated IR Camera      | 1         | 5.26%   |
| Chicony HP Wide Vision HD Camera  | 1         | 5.26%   |
| Chicony HP Truevision HD          | 1         | 5.26%   |
| Chicony HD User Facing            | 1         | 5.26%   |
| Chicony EasyCamera                | 1         | 5.26%   |
| Bison Lenovo EasyCamera           | 1         | 5.26%   |
| Acer Lenovo EasyCamera            | 1         | 5.26%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 1         | 50%     |
| Shenzhen Goodix Technology | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 50%     |
| Shenzhen Goodix  FingerPrint Device                      | 1         | 50%     |

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
| 0     | 21        | 77.78%  |
| 1     | 6         | 22.22%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Multimedia controller | 2         | 33.33%  |
| Fingerprint reader    | 2         | 33.33%  |
| Net/wireless          | 1         | 16.67%  |
| Graphics card         | 1         | 16.67%  |

