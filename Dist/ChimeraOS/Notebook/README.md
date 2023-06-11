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

Total: 22

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| ChimeraOS 39 | 8         | 44.44%  |
| ChimeraOS 41 | 5         | 27.78%  |
| ChimeraOS 42 | 3         | 16.67%  |
| ChimeraOS 38 | 2         | 11.11%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| ChimeraOS | 18        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version        | Notebooks | Percent |
|----------------|-----------|---------|
| 6.1.11-arch1-1 | 8         | 44.44%  |
| 6.1.21-1-lts   | 5         | 27.78%  |
| 6.1.27-1-lts   | 3         | 16.67%  |
| 6.1.1-arch1-1  | 2         | 11.11%  |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1.11  | 8         | 44.44%  |
| 6.1.21  | 5         | 27.78%  |
| 6.1.27  | 3         | 16.67%  |
| 6.1.1   | 2         | 11.11%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 18        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 18        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| GNOME | 18        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 16        | 88.89%  |
| X11     | 2         | 11.11%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 18        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 16        | 88.89%  |
| pt_BR | 1         | 5.56%   |
| it_IT | 1         | 5.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 18        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 18        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 18        | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 18        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 18        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo            | 4         | 22.22%  |
| MSI               | 3         | 16.67%  |
| ASUSTek Computer  | 3         | 16.67%  |
| ONE-NETBOOK       | 2         | 11.11%  |
| Hewlett-Packard   | 2         | 11.11%  |
| Acer              | 2         | 11.11%  |
| Razer             | 1         | 5.56%   |
| Micro Electronics | 1         | 5.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| ONE-NETBOOK ONEXPLAYER 2 ARP23              | 2         | 11.11%  |
| Razer Blade Pro 17 (Early 2020) - RZ09-0329 | 1         | 5.56%   |
| MSI MS-7C91                                 | 1         | 5.56%   |
| MSI GE75 Raider 10SF                        | 1         | 5.56%   |
| MSI CX62 6QD                                | 1         | 5.56%   |
| Micro MG-VCP17I-3070                        | 1         | 5.56%   |
| Lenovo Y50-70 20378                         | 1         | 5.56%   |
| Lenovo Legion Y540-15IRH 81SX               | 1         | 5.56%   |
| Lenovo IdeaPad 700-15ISK 80RU               | 1         | 5.56%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 1         | 5.56%   |
| HP EliteBook 850 G8 Notebook PC             | 1         | 5.56%   |
| HP 250 G4 Notebook PC                       | 1         | 5.56%   |
| ASUS TUF Gaming FX505DV_FX505DV             | 1         | 5.56%   |
| ASUS ROG Zephyrus G15 GA503QM_GA503QM       | 1         | 5.56%   |
| ASUS K45VM                                  | 1         | 5.56%   |
| Acer Nitro AN515-51                         | 1         | 5.56%   |
| Acer Aspire A515-51G                        | 1         | 5.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| ONE-NETBOOK ONEXPLAYER | 2         | 11.11%  |
| Lenovo IdeaPad         | 2         | 11.11%  |
| Razer Blade            | 1         | 5.56%   |
| MSI MS-7C91            | 1         | 5.56%   |
| MSI GE75               | 1         | 5.56%   |
| MSI CX62               | 1         | 5.56%   |
| Micro MG-VCP17I-3070   | 1         | 5.56%   |
| Lenovo Y50-70          | 1         | 5.56%   |
| Lenovo Legion          | 1         | 5.56%   |
| HP EliteBook           | 1         | 5.56%   |
| HP 250                 | 1         | 5.56%   |
| ASUS TUF               | 1         | 5.56%   |
| ASUS ROG               | 1         | 5.56%   |
| ASUS K45VM             | 1         | 5.56%   |
| Acer Nitro             | 1         | 5.56%   |
| Acer Aspire            | 1         | 5.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 3         | 16.67%  |
| 2017 | 3         | 16.67%  |
| 2015 | 3         | 16.67%  |
| 2023 | 2         | 11.11%  |
| 2021 | 2         | 11.11%  |
| 2019 | 2         | 11.11%  |
| 2022 | 1         | 5.56%   |
| 2016 | 1         | 5.56%   |
| 2012 | 1         | 5.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 18        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 18        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 18        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 5         | 27.78%  |
| 32.01-64.0  | 4         | 22.22%  |
| 4.01-8.0    | 3         | 16.67%  |
| 8.01-16.0   | 3         | 16.67%  |
| 3.01-4.0    | 1         | 5.56%   |
| 24.01-32.0  | 1         | 5.56%   |
| 64.01-256.0 | 1         | 5.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 7         | 38.89%  |
| 3.01-4.0 | 5         | 27.78%  |
| 1.01-2.0 | 4         | 22.22%  |
| 4.01-8.0 | 2         | 11.11%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 10        | 55.56%  |
| 1      | 7         | 38.89%  |
| 3      | 1         | 5.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 18        | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 83.33%  |
| No        | 3         | 16.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 100%    |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 8         | 44.44%  |
| UK           | 2         | 11.11%  |
| Brazil       | 2         | 11.11%  |
| Saudi Arabia | 1         | 5.56%   |
| Poland       | 1         | 5.56%   |
| Italy        | 1         | 5.56%   |
| Hungary      | 1         | 5.56%   |
| Costa Rica   | 1         | 5.56%   |
| Belgium      | 1         | 5.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Wroclaw                  | 1         | 5.56%   |
| Virginia Beach           | 1         | 5.56%   |
| St Louis                 | 1         | 5.56%   |
| Santa Cruz das Palmeiras | 1         | 5.56%   |
| San José                | 1         | 5.56%   |
| Saltillo                 | 1         | 5.56%   |
| Ridley Park              | 1         | 5.56%   |
| Pittsburg                | 1         | 5.56%   |
| Pennsauken               | 1         | 5.56%   |
| Newport News             | 1         | 5.56%   |
| Milan                    | 1         | 5.56%   |
| Jeddah                   | 1         | 5.56%   |
| Hot Springs              | 1         | 5.56%   |
| Budapest                 | 1         | 5.56%   |
| Brussels                 | 1         | 5.56%   |
| Belfast                  | 1         | 5.56%   |
| Barnet                   | 1         | 5.56%   |
| Araras                   | 1         | 5.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                   | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| WDC                      | 5         | 5      | 16.67%  |
| Samsung Electronics      | 5         | 5      | 16.67%  |
| Kingston                 | 4         | 4      | 13.33%  |
| Seagate                  | 3         | 3      | 10%     |
| Sandisk                  | 3         | 3      | 10%     |
| Micron Technology        | 3         | 3      | 10%     |
| Unknown                  | 2         | 2      | 6.67%   |
| Toshiba                  | 2         | 2      | 6.67%   |
| Intel                    | 2         | 2      | 6.67%   |
| Biwin Storage Technology | 1         | 1      | 3.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 2         | 6.67%   |
| WDC WD7500BPVT-80HXZT3 752GB                        | 1         | 3.33%   |
| WDC WD20SPZX-08UA7 2TB                              | 1         | 3.33%   |
| WDC WD201KFGX-68BKJN0 20TB                          | 1         | 3.33%   |
| WDC WD10SPCX-24HWST1 1TB                            | 1         | 3.33%   |
| WDC WD10JPLX-00MBPT0 1TB                            | 1         | 3.33%   |
| Unknown NVMe SSD Drive 1024GB                       | 1         | 3.33%   |
| Unknown MMC Card  16GB                              | 1         | 3.33%   |
| Toshiba XG6 NVMe SSD Controller 256GB               | 1         | 3.33%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 3.33%   |
| Seagate ST9320423AS 320GB                           | 1         | 3.33%   |
| Seagate ST1000LM048-2E7172 1TB                      | 1         | 3.33%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 3.33%   |
| Sandisk WD_BLACK SN770 2TB                          | 1         | 3.33%   |
| Sandisk WD Black SN850 500GB                        | 1         | 3.33%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 256GB    | 1         | 3.33%   |
| Samsung Portable SSD T5 1TB                         | 1         | 3.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 1         | 3.33%   |
| Samsung MZNLF128HCHP-000H1 128GB SSD                | 1         | 3.33%   |
| Micron 2200V_MTFDHBA512TCK 512GB                    | 1         | 3.33%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD                 | 1         | 3.33%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                 | 1         | 3.33%   |
| Kingston SV300S37A120G 120GB SSD                    | 1         | 3.33%   |
| Kingston SV100S2128G 128GB SSD                      | 1         | 3.33%   |
| Kingston SA400S37480G 480GB SSD                     | 1         | 3.33%   |
| Kingston SA400S37120G 120GB SSD                     | 1         | 3.33%   |
| Intel SSDPEKNU512GZ 512GB                           | 1         | 3.33%   |
| Intel SSD 600P Series 256GB                         | 1         | 3.33%   |
| Biwin Storage ONE XPLAYER Q1 2TB                    | 1         | 3.33%   |

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


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 11        | 12     | 40.74%  |
| HDD  | 8         | 9      | 29.63%  |
| SSD  | 7         | 8      | 25.93%  |
| MMC  | 1         | 1      | 3.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 12        | 16     | 48%     |
| NVMe | 11        | 12     | 44%     |
| SAS  | 1         | 1      | 4%      |
| MMC  | 1         | 1      | 4%      |

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
| 1001-2000      | 7         | 38.89%  |
| More than 3000 | 6         | 33.33%  |
| 251-500        | 4         | 22.22%  |
| 501-1000       | 1         | 5.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 21-50    | 7         | 38.89%  |
| 101-250  | 4         | 22.22%  |
| 251-500  | 3         | 16.67%  |
| 51-100   | 3         | 16.67%  |
| 501-1000 | 1         | 5.56%   |

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
| Detected | 18        | 30     | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 14        | 53.85%  |
| SanDisk                      | 3         | 11.54%  |
| Samsung Electronics          | 3         | 11.54%  |
| AMD                          | 2         | 7.69%   |
| Toshiba America Info Systems | 1         | 3.85%   |
| Micron Technology            | 1         | 3.85%   |
| INNOGRIT                     | 1         | 3.85%   |
| Biwin Storage Technology     | 1         | 3.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 10.71%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 7.14%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 7.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 7.14%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 7.14%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 3.57%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 3.57%   |
| SanDisk WD Black SN770 NVMe SSD                                                | 1         | 3.57%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 3.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 3.57%   |
| Micron NVMe Storage Controller                                                 | 1         | 3.57%   |
| Intel SSD 600P Series                                                          | 1         | 3.57%   |
| Intel Non-Volatile memory controller                                           | 1         | 3.57%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 3.57%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 3.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 3.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 3.57%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1         | 3.57%   |
| INNOGRIT Non-Volatile memory controller                                        | 1         | 3.57%   |
| Biwin Storage Non-Volatile memory controller                                   | 1         | 3.57%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 1         | 3.57%   |
| AMD 500 Series Chipset SATA Controller                                         | 1         | 3.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 13        | 48.15%  |
| NVMe | 11        | 40.74%  |
| RAID | 3         | 11.11%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 13        | 72.22%  |
| AMD    | 5         | 27.78%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 11.11%  |
| AMD Ryzen 7 6800U with Radeon Graphics        | 2         | 11.11%  |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 5.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 5.56%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 5.56%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 5.56%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 5.56%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 5.56%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 5.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 5.56%   |
| Intel Core i5-4210H CPU @ 2.90GHz             | 1         | 5.56%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 5.56%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 5.56%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 1         | 5.56%   |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 1         | 5.56%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 5.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Intel Core i5 | 6         | 33.33%  |
| Intel Core i7 | 5         | 27.78%  |
| AMD Ryzen 7   | 3         | 16.67%  |
| Other         | 2         | 11.11%  |
| AMD Ryzen 9   | 2         | 11.11%  |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 7         | 38.89%  |
| 8      | 5         | 27.78%  |
| 2      | 3         | 16.67%  |
| 6      | 2         | 11.11%  |
| 12     | 1         | 5.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 18        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 15        | 83.33%  |
| 1      | 3         | 16.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 18        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 18        | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KabyLake  | 4         | 22.22%  |
| Skylake   | 3         | 16.67%  |
| Unknown   | 3         | 16.67%  |
| Zen 3     | 2         | 11.11%  |
| CometLake | 2         | 11.11%  |
| Zen+      | 1         | 5.56%   |
| TigerLake | 1         | 5.56%   |
| IvyBridge | 1         | 5.56%   |
| Haswell   | 1         | 5.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Nvidia | 12        | 42.86%  |
| Intel  | 11        | 39.29%  |
| AMD    | 5         | 17.86%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 530                                                | 2         | 7.14%   |
| AMD Rembrandt [Radeon 680M]                                          | 2         | 7.14%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                           | 1         | 3.57%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]              | 1         | 3.57%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                              | 1         | 3.57%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                | 1         | 3.57%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                              | 1         | 3.57%   |
| Nvidia GM108M [GeForce MX130]                                        | 1         | 3.57%   |
| Nvidia GM108M [GeForce 940MX]                                        | 1         | 3.57%   |
| Nvidia GM107M [GeForce GTX 960M]                                     | 1         | 3.57%   |
| Nvidia GM107M [GeForce GTX 950M]                                     | 1         | 3.57%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                    | 1         | 3.57%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                      | 1         | 3.57%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                      | 1         | 3.57%   |
| Intel UHD Graphics 620                                               | 1         | 3.57%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                            | 1         | 3.57%   |
| Intel Skylake GT2 [HD Graphics 520]                                  | 1         | 3.57%   |
| Intel HD Graphics 630                                                | 1         | 3.57%   |
| Intel HD Graphics 620                                                | 1         | 3.57%   |
| Intel CometLake-H GT2 [UHD Graphics]                                 | 1         | 3.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                            | 1         | 3.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller          | 1         | 3.57%   |
| Intel 3rd Gen Core processor Graphics Controller                     | 1         | 3.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 1         | 3.57%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                             | 1         | 3.57%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]         | 1         | 3.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 8         | 44.44%  |
| 1 x Intel      | 3         | 16.67%  |
| 1 x AMD        | 3         | 16.67%  |
| 1 x Nvidia     | 2         | 11.11%  |
| AMD + Nvidia   | 2         | 11.11%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Proprietary | 11        | 61.11%  |
| Free        | 7         | 38.89%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 4         | 22.22%  |
| Chimei Innolux      | 4         | 22.22%  |
| BOE                 | 4         | 22.22%  |
| Samsung Electronics | 2         | 11.11%  |
| AU Optronics        | 2         | 11.11%  |
| Sharp               | 1         | 5.56%   |
| Goldstar            | 1         | 5.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE FLQ8423-24L0 BOE1003 1600x2560 113x181mm 8.4-inch                | 2         | 11.11%  |
| Sharp LQ173M1JW02 SHP14DB 1920x1080 382x215mm 17.3-inch              | 1         | 5.56%   |
| Samsung Electronics QBQ95 SAM7229 3840x2160 1872x1053mm 84.6-inch    | 1         | 5.56%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch | 1         | 5.56%   |
| LG Display LCD Monitor LGD071E 1920x1080 344x194mm 15.5-inch         | 1         | 5.56%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch         | 1         | 5.56%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch         | 1         | 5.56%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 1         | 5.56%   |
| Goldstar M237WDP GSM5779 1920x1080 598x336mm 27.0-inch               | 1         | 5.56%   |
| Chimei Innolux LCD Monitor CMN176E 1920x1080 381x214mm 17.2-inch     | 1         | 5.56%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 1         | 5.56%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch     | 1         | 5.56%   |
| Chimei Innolux LCD Monitor CMN1540 2560x1440 344x193mm 15.5-inch     | 1         | 5.56%   |
| BOE LCD Monitor BOE0977 2560x1440 381x214mm 17.2-inch                | 1         | 5.56%   |
| BOE LCD Monitor BOE065D 1920x1080 344x194mm 15.5-inch                | 1         | 5.56%   |
| AU Optronics LCD Monitor AUOD0ED 1920x1080 344x193mm 15.5-inch       | 1         | 5.56%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 1         | 5.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 10        | 55.56%  |
| 1366x768 (WXGA) | 3         | 16.67%  |
| 2560x1440 (QHD) | 2         | 11.11%  |
| 1600x2560       | 2         | 11.11%  |
| 3840x2160 (4K)  | 1         | 5.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 10        | 55.56%  |
| 17     | 3         | 16.67%  |
| 8      | 2         | 11.11%  |
| 84     | 1         | 5.56%   |
| 27     | 1         | 5.56%   |
| 14     | 1         | 5.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 11        | 61.11%  |
| 351-400     | 3         | 16.67%  |
| 101-200     | 2         | 11.11%  |
| 501-600     | 1         | 5.56%   |
| 1501-2000   | 1         | 5.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 16        | 88.89%  |
| 0.62  | 2         | 11.11%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 10        | 55.56%  |
| 121-130        | 3         | 16.67%  |
| 1-40           | 2         | 11.11%  |
| More than 1000 | 1         | 5.56%   |
| 81-90          | 1         | 5.56%   |
| 301-350        | 1         | 5.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 9         | 50%     |
| 101-120       | 3         | 16.67%  |
| More than 240 | 2         | 11.11%  |
| 161-240       | 2         | 11.11%  |
| 51-100        | 2         | 11.11%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 17        | 94.44%  |
| 2     | 1         | 5.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 13        | 41.94%  |
| Intel                 | 9         | 29.03%  |
| Qualcomm Atheros      | 6         | 19.35%  |
| MediaTek              | 2         | 6.45%   |
| Broadcom Limited      | 1         | 3.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 27.27%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 9.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 6.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 6.06%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 6.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 3.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 3.03%   |
| Realtek PCIe GbE Family Controller                                | 1         | 3.03%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 3.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 3.03%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 3.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 3.03%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 3.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 3.03%   |
| Intel Wireless 3165                                               | 1         | 3.03%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 3.03%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 3.03%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 3.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 3.03%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 1         | 3.03%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 9         | 50%     |
| Qualcomm Atheros      | 4         | 22.22%  |
| Realtek Semiconductor | 2         | 11.11%  |
| MediaTek              | 2         | 11.11%  |
| Broadcom Limited      | 1         | 5.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 2         | 11.11%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 2         | 11.11%  |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 11.11%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 5.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 5.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1         | 5.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 1         | 5.56%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 1         | 5.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 5.56%   |
| Intel Wireless 3165                                           | 1         | 5.56%   |
| Intel Wi-Fi 6 AX201                                           | 1         | 5.56%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 1         | 5.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 5.56%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 1         | 5.56%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter    | 1         | 5.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 13        | 86.67%  |
| Qualcomm Atheros      | 2         | 13.33%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 60%     |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 20%     |
| Realtek PCIe GbE Family Controller                                | 1         | 6.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 6.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 6.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 18        | 54.55%  |
| Ethernet | 15        | 45.45%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 16        | 80%     |
| Ethernet | 4         | 20%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 15        | 83.33%  |
| 1     | 3         | 16.67%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 15        | 83.33%  |
| Yes  | 3         | 16.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 50%     |
| Lite-On Technology              | 2         | 11.11%  |
| IMC Networks                    | 2         | 11.11%  |
| Realtek Semiconductor           | 1         | 5.56%   |
| Qualcomm Atheros Communications | 1         | 5.56%   |
| MediaTek                        | 1         | 5.56%   |
| Foxconn / Hon Hai               | 1         | 5.56%   |
| Cambridge Silicon Radio         | 1         | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 4         | 22.22%  |
| Intel Bluetooth wireless interface                  | 2         | 11.11%  |
| Intel AX210 Bluetooth                               | 2         | 11.11%  |
| Realtek Bluetooth Radio                             | 1         | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 5.56%   |
| MediaTek Wireless_Device                            | 1         | 5.56%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 5.56%   |
| Lite-On Bluetooth Device                            | 1         | 5.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 5.56%   |
| IMC Networks Wireless_Device                        | 1         | 5.56%   |
| IMC Networks Bluetooth Radio                        | 1         | 5.56%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 5.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 13        | 48.15%  |
| Nvidia | 8         | 29.63%  |
| AMD    | 5         | 18.52%  |
| Sony   | 1         | 3.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                              | 4         | 12.5%   |
| Intel Sunrise Point-LP HD Audio                                     | 3         | 9.38%   |
| Nvidia TU106 High Definition Audio Controller                       | 2         | 6.25%   |
| Intel Comet Lake PCH cAVS                                           | 2         | 6.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 2         | 6.25%   |
| AMD Rembrandt Radeon High Definition Audio Controller               | 2         | 6.25%   |
| Sony DualSense wireless controller (PS5)                            | 1         | 3.13%   |
| Nvidia TU116 High Definition Audio Controller                       | 1         | 3.13%   |
| Nvidia TU104 HD Audio Controller                                    | 1         | 3.13%   |
| Nvidia GP107GL High Definition Audio Controller                     | 1         | 3.13%   |
| Nvidia GF108 High Definition Audio Controller                       | 1         | 3.13%   |
| Nvidia GA106 High Definition Audio Controller                       | 1         | 3.13%   |
| Nvidia GA104 High Definition Audio Controller                       | 1         | 3.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1         | 3.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 1         | 3.13%   |
| Intel Tiger Lake-H HD Audio Controller                              | 1         | 3.13%   |
| Intel CM238 HD Audio Controller                                     | 1         | 3.13%   |
| Intel Cannon Lake PCH cAVS                                          | 1         | 3.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 1         | 3.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 1         | 3.13%   |
| AMD Starship/Matisse HD Audio Controller                            | 1         | 3.13%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 1         | 3.13%   |
| AMD Navi 31 [Radeon RX 7000 HDMI Audio]                             | 1         | 3.13%   |

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
| Chicony Electronics           | 4         | 36.36%  |
| IMC Networks                  | 2         | 18.18%  |
| Bison Electronics             | 2         | 18.18%  |
| Sunplus Innovation Technology | 1         | 9.09%   |
| Quanta                        | 1         | 9.09%   |
| Microdia                      | 1         | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Bison Lenovo EasyCamera           | 2         | 18.18%  |
| Sunplus HD WebCam                 | 1         | 9.09%   |
| Quanta HP HD Camera               | 1         | 9.09%   |
| Microdia HP Webcam                | 1         | 9.09%   |
| IMC Networks USB2.0 HD UVC WebCam | 1         | 9.09%   |
| IMC Networks Integrated Camera    | 1         | 9.09%   |
| Chicony USB2.0 0.3M UVC WebCam    | 1         | 9.09%   |
| Chicony Integrated IR Camera      | 1         | 9.09%   |
| Chicony Integrated Camera         | 1         | 9.09%   |
| Chicony EasyCamera                | 1         | 9.09%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Synaptics | 1         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 100%    |

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
| 0     | 15        | 83.33%  |
| 1     | 3         | 16.67%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Multimedia controller | 1         | 33.33%  |
| Graphics card         | 1         | 33.33%  |
| Fingerprint reader    | 1         | 33.33%  |

