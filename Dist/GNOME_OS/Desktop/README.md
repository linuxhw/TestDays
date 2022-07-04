GNOME OS - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for GNOME OS.

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

Total: 12

| Vendor   | Model          | Probe                                                      | Date         |
|----------|----------------|------------------------------------------------------------|--------------|
| Gigabyte | B450M S2H V2   | [cd6b701253](https://linux-hardware.org/?probe=cd6b701253) | Nov 03, 2021 |
| ASUSTek  | PRIME A320M-K  | [11c23a1f37](https://linux-hardware.org/?probe=11c23a1f37) | Sep 26, 2021 |
| ASUSTek  | PRIME A320M-K  | [b33430e135](https://linux-hardware.org/?probe=b33430e135) | Sep 26, 2021 |
| ASUSTek  | H61M-A/BR      | [73b5c289e2](https://linux-hardware.org/?probe=73b5c289e2) | Sep 04, 2021 |
| HP       | 8767 A         | [926ac56be9](https://linux-hardware.org/?probe=926ac56be9) | Aug 10, 2021 |
| Gigabyte | X570 GAMING X  | [b751f6615d](https://linux-hardware.org/?probe=b751f6615d) | Jul 17, 2021 |
| Gigabyte | B450M S2H V2   | [d8886335b1](https://linux-hardware.org/?probe=d8886335b1) | Jul 10, 2021 |
| Intel    | X79            | [9f19896285](https://linux-hardware.org/?probe=9f19896285) | May 13, 2021 |
| Lenovo   | 317E NOK       | [2ce2a68735](https://linux-hardware.org/?probe=2ce2a68735) | Apr 14, 2021 |
| ASUSTek  | PRIME H410M-K  | [f685fefbec](https://linux-hardware.org/?probe=f685fefbec) | Mar 04, 2021 |
| Acer     | Aspire GX-781  | [159afb32c1](https://linux-hardware.org/?probe=159afb32c1) | Oct 10, 2020 |
| ASUSTek  | SABERTOOTH X79 | [17acfc90d4](https://linux-hardware.org/?probe=17acfc90d4) | Oct 07, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME OS Nightly | 8        | 80%     |
| GNOME OS 3.38    | 2        | 20%     |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| GNOME OS | 10       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.10 | 5        | 45.45%  |
| 5.7.14  | 2        | 18.18%  |
| 5.14.4  | 1        | 9.09%   |
| 5.13.9  | 1        | 9.09%   |
| 5.12.12 | 1        | 9.09%   |
| 5.11.0  | 1        | 9.09%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.10 | 5        | 45.45%  |
| 5.7.14  | 2        | 18.18%  |
| 5.14.4  | 1        | 9.09%   |
| 5.13.9  | 1        | 9.09%   |
| 5.12.12 | 1        | 9.09%   |
| 5.11.0  | 1        | 9.09%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 6        | 54.55%  |
| 5.7     | 2        | 18.18%  |
| 5.14    | 1        | 9.09%   |
| 5.13    | 1        | 9.09%   |
| 5.12    | 1        | 9.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 10       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| GNOME | 10       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 10       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 10       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 4        | 40%     |
| de_DE | 2        | 20%     |
| ru_UA | 1        | 10%     |
| pt_BR | 1        | 10%     |
| en_IN | 1        | 10%     |
| cs_CZ | 1        | 10%     |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 10       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ext4 | 10       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 10       | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 4        | 40%     |
| Gigabyte Technology | 2        | 20%     |
| Lenovo              | 1        | 10%     |
| Intel               | 1        | 10%     |
| Hewlett-Packard     | 1        | 10%     |
| Acer                | 1        | 10%     |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| Lenovo IdeaCentre 3 07IMB05 90NB0020IN | 1        | 10%     |
| Intel X79                              | 1        | 10%     |
| HP Pavilion Gaming Desktop TG01-1xxx   | 1        | 10%     |
| Gigabyte X570 GAMING X                 | 1        | 10%     |
| Gigabyte B450M S2H V2                  | 1        | 10%     |
| ASUS SABERTOOTH X79                    | 1        | 10%     |
| ASUS PRIME H410M-K                     | 1        | 10%     |
| ASUS PRIME A320M-K                     | 1        | 10%     |
| ASUS H61M-A/BR                         | 1        | 10%     |
| Acer Aspire GX-781                     | 1        | 10%     |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| ASUS PRIME        | 2        | 20%     |
| Lenovo IdeaCentre | 1        | 10%     |
| Intel X79         | 1        | 10%     |
| HP Pavilion       | 1        | 10%     |
| Gigabyte X570     | 1        | 10%     |
| Gigabyte B450M    | 1        | 10%     |
| ASUS SABERTOOTH   | 1        | 10%     |
| ASUS H61M-A       | 1        | 10%     |
| Acer Aspire       | 1        | 10%     |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 4        | 40%     |
| 2017 | 2        | 20%     |
| 2019 | 1        | 10%     |
| 2016 | 1        | 10%     |
| 2013 | 1        | 10%     |
| 2012 | 1        | 10%     |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 10       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 10       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 10       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 8.01-16.0  | 4        | 40%     |
| 32.01-64.0 | 2        | 20%     |
| 16.01-24.0 | 2        | 20%     |
| 4.01-8.0   | 1        | 10%     |
| 3.01-4.0   | 1        | 10%     |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 8        | 72.73%  |
| 4.01-8.0 | 1        | 9.09%   |
| 3.01-4.0 | 1        | 9.09%   |
| 0.51-1.0 | 1        | 9.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 4        | 40%     |
| 1      | 3        | 30%     |
| 3      | 2        | 20%     |
| 4      | 1        | 10%     |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 90%     |
| Yes       | 1        | 10%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 10       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 6        | 60%     |
| No        | 4        | 40%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 6        | 60%     |
| Yes       | 4        | 40%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| USA     | 2        | 20%     |
| Germany | 2        | 20%     |
| Ukraine | 1        | 10%     |
| Russia  | 1        | 10%     |
| India   | 1        | 10%     |
| Czechia | 1        | 10%     |
| Canada  | 1        | 10%     |
| Brazil  | 1        | 10%     |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Waldachtal          | 1        | 10%     |
| Verden an der Aller | 1        | 10%     |
| Vancouver           | 1        | 10%     |
| Tyumen              | 1        | 10%     |
| Rio de Janeiro      | 1        | 10%     |
| Prague              | 1        | 10%     |
| Ottawa              | 1        | 10%     |
| Novoyavorovske      | 1        | 10%     |
| Kolkata             | 1        | 10%     |
| Columbia            | 1        | 10%     |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 6      | 31.58%  |
| Samsung Electronics | 3        | 5      | 15.79%  |
| Kingston            | 3        | 3      | 15.79%  |
| WDC                 | 2        | 2      | 10.53%  |
| Toshiba             | 1        | 1      | 5.26%   |
| SK hynix            | 1        | 1      | 5.26%   |
| SanDisk             | 1        | 2      | 5.26%   |
| PNY                 | 1        | 1      | 5.26%   |
| Apacer              | 1        | 1      | 5.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| WDC WD1600AAJS-22L7A0 160GB           | 1        | 5%      |
| WDC WD10EALX-009BA0 1TB               | 1        | 5%      |
| Toshiba HDWD120 2TB                   | 1        | 5%      |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1        | 5%      |
| Seagate ST9500325AS 500GB             | 1        | 5%      |
| Seagate ST4000DX001-1CE168 4TB        | 1        | 5%      |
| Seagate ST3500312CS 500GB             | 1        | 5%      |
| Seagate ST2000DM001-1ER164 2TB        | 1        | 5%      |
| Seagate ST1000DM010-2EP102 1TB        | 1        | 5%      |
| Seagate ST1000DM003-1SB102 1TB        | 1        | 5%      |
| SanDisk NVMe SSD Drive 500GB          | 1        | 5%      |
| Samsung SSD 860 QVO 1TB               | 1        | 5%      |
| Samsung SSD 840 EVO 250GB             | 1        | 5%      |
| Samsung NVMe SSD Drive 256GB          | 1        | 5%      |
| Samsung NVMe SSD Drive 1024GB         | 1        | 5%      |
| PNY CS900 240GB SSD                   | 1        | 5%      |
| Kingston SV300S37A240G 240GB SSD      | 1        | 5%      |
| Kingston SA400S37120G 120GB SSD       | 1        | 5%      |
| Kingston SA400M8240G 240GB SSD        | 1        | 5%      |
| Apacer AS350 120GB SSD                | 1        | 5%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 6        | 6      | 66.67%  |
| WDC     | 2        | 2      | 22.22%  |
| Toshiba | 1        | 1      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 3        | 3      | 37.5%   |
| Samsung Electronics | 2        | 3      | 25%     |
| SK hynix            | 1        | 1      | 12.5%   |
| PNY                 | 1        | 1      | 12.5%   |
| Apacer              | 1        | 1      | 12.5%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 8        | 9      | 47.06%  |
| SSD  | 6        | 9      | 35.29%  |
| NVMe | 3        | 4      | 17.65%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 9        | 18     | 75%     |
| NVMe | 3        | 4      | 25%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 6        | 10     | 46.15%  |
| 0.51-1.0   | 4        | 5      | 30.77%  |
| 1.01-2.0   | 2        | 2      | 15.38%  |
| 3.01-4.0   | 1        | 1      | 7.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 5        | 50%     |
| 251-500    | 2        | 20%     |
| 501-1000   | 2        | 20%     |
| 1001-2000  | 1        | 10%     |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 6        | 54.55%  |
| 101-250 | 2        | 18.18%  |
| 251-500 | 1        | 9.09%   |
| 21-50   | 1        | 9.09%   |
| 51-100  | 1        | 9.09%   |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 10       | 22     | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 7        | 46.67%  |
| AMD                      | 3        | 20%     |
| Samsung Electronics      | 2        | 13.33%  |
| SanDisk                  | 1        | 6.67%   |
| Marvell Technology Group | 1        | 6.67%   |
| ASMedia Technology       | 1        | 6.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 3        | 16.67%  |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 11.11%  |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 5.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 5.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 5.56%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1        | 5.56%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 5.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 5.56%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 5.56%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 5.56%   |
| AMD FCH SATA Controller D                                                               | 1        | 5.56%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 5.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 8        | 61.54%  |
| NVMe | 3        | 23.08%  |
| RAID | 1        | 7.69%   |
| IDE  | 1        | 7.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 7        | 70%     |
| AMD    | 3        | 30%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Xeon CPU E5-2660 0 @ 2.20GHz          | 1        | 10%     |
| Intel Core i7-4930K CPU @ 3.40GHz           | 1        | 10%     |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 10%     |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 10%     |
| Intel Core i3-10100F CPU @ 3.60GHz          | 1        | 10%     |
| Intel Core i3-10100 CPU @ 3.60GHz           | 1        | 10%     |
| Intel Celeron CPU G530 @ 2.40GHz            | 1        | 10%     |
| AMD Ryzen 5 5600X 6-Core Processor          | 1        | 10%     |
| AMD Ryzen 5 3600X 6-Core Processor          | 1        | 10%     |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 1        | 10%     |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| AMD Ryzen 5   | 3        | 30%     |
| Intel Core i5 | 2        | 20%     |
| Intel Core i3 | 2        | 20%     |
| Intel Xeon    | 1        | 10%     |
| Intel Core i7 | 1        | 10%     |
| Intel Celeron | 1        | 10%     |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 4        | 40%     |
| 4      | 4        | 40%     |
| 8      | 1        | 10%     |
| 2      | 1        | 10%     |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 10       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 8        | 80%     |
| 1      | 2        | 20%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 10       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0xa0653    | 3        | 30%     |
| 0x906e9    | 1        | 10%     |
| 0x306e4    | 1        | 10%     |
| 0x206d7    | 1        | 10%     |
| 0x206a7    | 1        | 10%     |
| 0x0a201009 | 1        | 10%     |
| 0x08701021 | 1        | 10%     |
| 0x08108109 | 1        | 10%     |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| CometLake   | 3        | 30%     |
| SandyBridge | 2        | 20%     |
| Zen+        | 1        | 10%     |
| Zen 3       | 1        | 10%     |
| Zen 2       | 1        | 10%     |
| KabyLake    | 1        | 10%     |
| IvyBridge   | 1        | 10%     |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 6        | 60%     |
| Intel  | 2        | 20%     |
| AMD    | 2        | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Nvidia GP106 [GeForce GTX 1060 3GB]                                       | 3        | 30%     |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                     | 1        | 10%     |
| Nvidia TU106 [GeForce RTX 2070]                                           | 1        | 10%     |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                       | 1        | 10%     |
| Intel CometLake-S GT2 [UHD Graphics 630]                                  | 1        | 10%     |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1        | 10%     |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1        | 10%     |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                          | 1        | 10%     |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 6        | 60%     |
| 1 x Intel  | 2        | 20%     |
| 1 x AMD    | 2        | 20%     |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver | Desktops | Percent |
|--------|----------|---------|
| Free   | 10       | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 3        | 30%     |
| 1.01-2.0   | 2        | 20%     |
| Unknown    | 2        | 20%     |
| 7.01-8.0   | 1        | 10%     |
| 5.01-6.0   | 1        | 10%     |
| 3.01-4.0   | 1        | 10%     |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 5        | 45.45%  |
| Goldstar            | 2        | 18.18%  |
| Viotek              | 1        | 9.09%   |
| Philips             | 1        | 9.09%   |
| AOC                 | 1        | 9.09%   |
| Acer                | 1        | 9.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Viotek GN34CW VTK3400 3440x1440 795x334mm 33.9-inch                 | 1        | 8.33%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch | 1        | 8.33%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch  | 1        | 8.33%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch   | 1        | 8.33%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch   | 1        | 8.33%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch   | 1        | 8.33%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch   | 1        | 8.33%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch             | 1        | 8.33%   |
| Goldstar W1752 GSM4490 1440x900 370x232mm 17.2-inch                 | 1        | 8.33%   |
| Goldstar 24GL600F GSM5B73 1920x1080 531x298mm 24.0-inch             | 1        | 8.33%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                      | 1        | 8.33%   |
| Acer FT220HQL ACR03D2 1920x1080 476x268mm 21.5-inch                 | 1        | 8.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 7        | 70%     |
| 3440x1440        | 1        | 10%     |
| 1440x900 (WXGA+) | 1        | 10%     |
| 1366x768 (WXGA)  | 1        | 10%     |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 21     | 3        | 27.27%  |
| 24     | 2        | 18.18%  |
| 34     | 1        | 9.09%   |
| 31     | 1        | 9.09%   |
| 27     | 1        | 9.09%   |
| 23     | 1        | 9.09%   |
| 18     | 1        | 9.09%   |
| 17     | 1        | 9.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 4        | 40%     |
| 501-600     | 3        | 30%     |
| 701-800     | 1        | 10%     |
| 601-700     | 1        | 10%     |
| 351-400     | 1        | 10%     |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 9        | 81.82%  |
| 21/9  | 1        | 9.09%   |
| 16/10 | 1        | 9.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 5        | 50%     |
| 351-500        | 2        | 20%     |
| 301-350        | 1        | 10%     |
| 141-150        | 1        | 10%     |
| 131-140        | 1        | 10%     |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 6        | 60%     |
| 101-120 | 4        | 40%     |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 8        | 80%     |
| 2     | 2        | 20%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 9        | 56.25%  |
| Intel                           | 4        | 25%     |
| Qualcomm Atheros Communications | 1        | 6.25%   |
| Motorola PCS                    | 1        | 6.25%   |
| Google                          | 1        | 6.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9        | 50%     |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 5.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 5.56%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1        | 5.56%   |
| Motorola PCS Moto G (5S) Plus                                     | 1        | 5.56%   |
| Intel Wireless-AC 9260                                            | 1        | 5.56%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 5.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 5.56%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 5.56%   |
| Google Nexus/Pixel Device (tether)                                | 1        | 5.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 3        | 50%     |
| Realtek Semiconductor           | 2        | 33.33%  |
| Qualcomm Atheros Communications | 1        | 16.67%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter | 1        | 16.67%  |
| Realtek RTL8192EE PCIe Wireless Network Adapter          | 1        | 16.67%  |
| Qualcomm Atheros AR9271 802.11n                          | 1        | 16.67%  |
| Intel Wireless-AC 9260                                   | 1        | 16.67%  |
| Intel Wi-Fi 6 AX200                                      | 1        | 16.67%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]         | 1        | 16.67%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 9        | 81.82%  |
| Intel                 | 1        | 9.09%   |
| Google                | 1        | 9.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9        | 81.82%  |
| Intel 82579V Gigabit Network Connection                           | 1        | 9.09%   |
| Google Nexus/Pixel Device (tether)                                | 1        | 9.09%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 10       | 58.82%  |
| WiFi     | 6        | 35.29%  |
| Unknown  | 1        | 5.88%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 6        | 66.67%  |
| WiFi     | 3        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 5        | 50%     |
| 1     | 5        | 50%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 8        | 80%     |
| Yes  | 2        | 20%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 2        | 50%     |
| Realtek Semiconductor | 1        | 25%     |
| ASUSTek Computer      | 1        | 25%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Realtek  Bluetooth 4.2 Adapter           | 1        | 25%     |
| Intel Wireless-AC 9260 Bluetooth Adapter | 1        | 25%     |
| Intel Wireless-AC 3168 Bluetooth         | 1        | 25%     |
| ASUS Broadcom BCM20702A0 Bluetooth       | 1        | 25%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 7        | 41.18%  |
| Nvidia              | 6        | 35.29%  |
| AMD                 | 3        | 17.65%  |
| C-Media Electronics | 1        | 5.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Nvidia GP106 High Definition Audio Controller                              | 4        | 21.05%  |
| Intel Comet Lake PCH-V cAVS                                                | 2        | 10.53%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 10.53%  |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 10.53%  |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 5.26%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 5.26%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 5.26%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 5.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 5.26%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                        | 1        | 5.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 5.26%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 5.26%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 5.26%   |

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


| Vendor        | Desktops | Percent |
|---------------|----------|---------|
| Logitech      | 1        | 50%     |
| 2M UVC CAMERA | 1        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920         | 1        | 50%     |
| 2M UVC CAMERA NexiGo N60 FHD Webcam | 1        | 50%     |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

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


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 5        | 50%     |
| 2     | 2        | 20%     |
| 0     | 2        | 20%     |
| 3     | 1        | 10%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 6        | 50%     |
| Net/wireless             | 3        | 25%     |
| Graphics card            | 1        | 8.33%   |
| Firewire controller      | 1        | 8.33%   |
| Bluetooth                | 1        | 8.33%   |

