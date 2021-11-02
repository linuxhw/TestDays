Parrot 4.11 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for Parrot 4.11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=parrot-4.11

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

| Vendor   | Model                  | Probe                                                      | Date         |
|----------|------------------------|------------------------------------------------------------|--------------|
| Dell     | 0T2HR0 A00             | [dc55f173fe](https://linux-hardware.org/?probe=dc55f173fe) | Oct 05, 2021 |
| ASUSTek  | P8H67-M PRO            | [7dcd6067ac](https://linux-hardware.org/?probe=7dcd6067ac) | Oct 04, 2021 |
| Gigabyte | A320M-S2H-CF           | [b733e7fac1](https://linux-hardware.org/?probe=b733e7fac1) | Sep 23, 2021 |
| Gigabyte | A320M-S2H-CF           | [6647d75cdb](https://linux-hardware.org/?probe=6647d75cdb) | Aug 20, 2021 |
| Gigabyte | A320M-S2H-CF           | [5363cc3efd](https://linux-hardware.org/?probe=5363cc3efd) | Aug 12, 2021 |
| Gigabyte | A320M-S2H-CF           | [3ba02ffef3](https://linux-hardware.org/?probe=3ba02ffef3) | Aug 10, 2021 |
| ZOTAC    | Unknown                | [0324aff0a3](https://linux-hardware.org/?probe=0324aff0a3) | Aug 03, 2021 |
| ZOTAC    | Unknown                | [c1a9e01bd7](https://linux-hardware.org/?probe=c1a9e01bd7) | Aug 03, 2021 |
| HP       | 1850                   | [687c780f5c](https://linux-hardware.org/?probe=687c780f5c) | Jul 19, 2021 |
| Dell     | 0T10XW A02             | [57a4116288](https://linux-hardware.org/?probe=57a4116288) | Jul 17, 2021 |
| HP       | 1850                   | [3bde7e8e11](https://linux-hardware.org/?probe=3bde7e8e11) | May 27, 2021 |
| Dell     | 0C1R19 A02             | [ff5bb2ee2a](https://linux-hardware.org/?probe=ff5bb2ee2a) | May 03, 2021 |
| ASUSTek  | PRIME X399-A           | [4dd4f28ca7](https://linux-hardware.org/?probe=4dd4f28ca7) | Apr 11, 2021 |
| Acer     | Predator PO3-600 V:1.1 | [6ea75bdbb5](https://linux-hardware.org/?probe=6ea75bdbb5) | Mar 26, 2021 |
| ASUSTek  | M5A78L-M/USB3          | [6b26a69326](https://linux-hardware.org/?probe=6b26a69326) | Mar 21, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 5.10.0-8parrot1-amd64 | 3        | 30%     |
| 5.10.0-6parrot1-amd64 | 2        | 20%     |
| 5.10.0-3parrot1-amd64 | 2        | 20%     |
| 5.7.0-2parrot2-amd64  | 1        | 10%     |
| 5.14.0-2parrot1-amd64 | 1        | 10%     |
| 5.10.0-5parrot1-amd64 | 1        | 10%     |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 8        | 80%     |
| 5.7.0   | 1        | 10%     |
| 5.14.0  | 1        | 10%     |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 8        | 80%     |
| 5.7     | 1        | 10%     |
| 5.14    | 1        | 10%     |

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


| Name    | Desktops | Percent |
|---------|----------|---------|
| MATE    | 4        | 36.36%  |
| KDE5    | 3        | 27.27%  |
| XFCE    | 2        | 18.18%  |
| KDE     | 1        | 9.09%   |
| Unknown | 1        | 9.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 10       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 6        | 54.55%  |
| TDM     | 3        | 27.27%  |
| LightDM | 2        | 18.18%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 5        | 50%     |
| ru_UA | 1        | 10%     |
| ru_RU | 1        | 10%     |
| pt_BR | 1        | 10%     |
| fr_FR | 1        | 10%     |
| en_AU | 1        | 10%     |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 8        | 72.73%  |
| EFI  | 3        | 27.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 9        | 90%     |
| Ext4  | 1        | 10%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 6        | 54.55%  |
| GPT     | 4        | 36.36%  |
| MBR     | 1        | 9.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 90.91%  |
| Yes       | 1        | 9.09%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 8        | 80%     |
| Yes       | 2        | 20%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 3        | 30%     |
| ASUSTek Computer    | 3        | 30%     |
| ZOTAC               | 1        | 10%     |
| Hewlett-Packard     | 1        | 10%     |
| Gigabyte Technology | 1        | 10%     |
| Acer                | 1        | 10%     |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| HP Compaq Pro 6305 MT | 1        | 10%     |
| Gigabyte A320M-S2H    | 1        | 10%     |
| Dell XPS 8930         | 1        | 10%     |
| Dell OptiPlex 7070    | 1        | 10%     |
| Dell OptiPlex 3010    | 1        | 10%     |
| ASUS PRIME X399-A     | 1        | 10%     |
| ASUS P8H67-M PRO      | 1        | 10%     |
| ASUS M5A78L-M/USB3    | 1        | 10%     |
| Acer Predator PO3-600 | 1        | 10%     |
| Unknown               | 1        | 10%     |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Dell OptiPlex      | 2        | 20%     |
| HP Compaq          | 1        | 10%     |
| Gigabyte A320M-S2H | 1        | 10%     |
| Dell XPS           | 1        | 10%     |
| ASUS PRIME         | 1        | 10%     |
| ASUS P8H67-M       | 1        | 10%     |
| ASUS M5A78L-M      | 1        | 10%     |
| Acer Predator      | 1        | 10%     |
| Unknown            | 1        | 10%     |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 3        | 30%     |
| 2020 | 2        | 20%     |
| 2013 | 2        | 20%     |
| 2018 | 1        | 10%     |
| 2016 | 1        | 10%     |
| 2014 | 1        | 10%     |

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
| 4.01-8.0   | 4        | 40%     |
| 16.01-24.0 | 2        | 20%     |
| 8.01-16.0  | 2        | 20%     |
| 32.01-64.0 | 1        | 10%     |
| 3.01-4.0   | 1        | 10%     |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 4        | 40%     |
| 2.01-3.0  | 3        | 30%     |
| 4.01-8.0  | 2        | 20%     |
| 8.01-16.0 | 1        | 10%     |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 3      | 4        | 40%     |
| 2      | 4        | 40%     |
| 4      | 1        | 10%     |
| 1      | 1        | 10%     |

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
| Yes       | 8        | 72.73%  |
| No        | 3        | 27.27%  |

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


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 4        | 40%     |
| Ukraine   | 1        | 10%     |
| Russia    | 1        | 10%     |
| Germany   | 1        | 10%     |
| France    | 1        | 10%     |
| Brazil    | 1        | 10%     |
| Australia | 1        | 10%     |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City        | Desktops | Percent |
|-------------|----------|---------|
| Ternopil    | 1        | 9.09%   |
| S??o Paulo  | 1        | 9.09%   |
| Portsmouth  | 1        | 9.09%   |
| Offenbach   | 1        | 9.09%   |
| Melbourne   | 1        | 9.09%   |
| Lyon        | 1        | 9.09%   |
| Los Angeles | 1        | 9.09%   |
| Khabarovsk  | 1        | 9.09%   |
| Eugene      | 1        | 9.09%   |
| Dudenhofen  | 1        | 9.09%   |
| Brunswick   | 1        | 9.09%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 9      | 21.74%  |
| WDC                 | 3        | 4      | 13.04%  |
| Toshiba             | 2        | 2      | 8.7%    |
| SK Hynix            | 2        | 2      | 8.7%    |
| Hitachi             | 2        | 3      | 8.7%    |
| Unknown             | 1        | 1      | 4.35%   |
| SPCC                | 1        | 1      | 4.35%   |
| Samsung Electronics | 1        | 1      | 4.35%   |
| Phison              | 1        | 1      | 4.35%   |
| LITEONIT            | 1        | 1      | 4.35%   |
| Intenso             | 1        | 1      | 4.35%   |
| FORESEE             | 1        | 1      | 4.35%   |
| Crucial             | 1        | 1      | 4.35%   |
| China               | 1        | 2      | 4.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| WDC WDBNCE0010PNC 1TB SSD             | 1        | 3.85%   |
| WDC WD3200LPVX-60V0TT0 320GB          | 1        | 3.85%   |
| WDC WD10EARS-00Y5B1 1TB               | 1        | 3.85%   |
| Unknown SD/MMC/MS PRO 128GB           | 1        | 3.85%   |
| Toshiba MK2552GSX 250GB               | 1        | 3.85%   |
| Toshiba DT01ACA100 1TB                | 1        | 3.85%   |
| SPCC Solid State Disk 120GB           | 1        | 3.85%   |
| SK Hynix PC601 NVMe 256GB             | 1        | 3.85%   |
| SK Hynix NVMe SSD Drive 256GB         | 1        | 3.85%   |
| Seagate ST9250410AS 250GB             | 1        | 3.85%   |
| Seagate ST500NM0011 500GB             | 1        | 3.85%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1        | 3.85%   |
| Seagate ST500DM002-1SB10A 500GB       | 1        | 3.85%   |
| Seagate ST4000DM004-2CV104 4TB        | 1        | 3.85%   |
| Seagate ST31000528AS 1TB              | 1        | 3.85%   |
| Seagate ST250DM000-1BD141 250GB       | 1        | 3.85%   |
| Samsung NVMe SSD Drive 1TB            | 1        | 3.85%   |
| Phison NVMe SSD Drive 1TB             | 1        | 3.85%   |
| LITEONIT LCS-128M6S 2.5 7mm 128GB SSD | 1        | 3.85%   |
| Intenso SSD SATAIII 120GB             | 1        | 3.85%   |
| Hitachi HTS547564A9E384 640GB         | 1        | 3.85%   |
| Hitachi HTS545050B9A300 500GB         | 1        | 3.85%   |
| Hitachi HDT721010SLA360 1TB           | 1        | 3.85%   |
| FORESEE 60GB SSD                      | 1        | 3.85%   |
| Crucial CT1000BX500SSD1 1TB           | 1        | 3.85%   |
| China SATA SSD 256GB                  | 1        | 3.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 5        | 9      | 41.67%  |
| WDC     | 2        | 3      | 16.67%  |
| Toshiba | 2        | 2      | 16.67%  |
| Hitachi | 2        | 3      | 16.67%  |
| Unknown | 1        | 1      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| WDC      | 1        | 1      | 14.29%  |
| SPCC     | 1        | 1      | 14.29%  |
| LITEONIT | 1        | 1      | 14.29%  |
| Intenso  | 1        | 1      | 14.29%  |
| FORESEE  | 1        | 1      | 14.29%  |
| Crucial  | 1        | 1      | 14.29%  |
| China    | 1        | 2      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 18     | 45%     |
| SSD  | 7        | 8      | 35%     |
| NVMe | 4        | 4      | 20%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 9        | 25     | 64.29%  |
| NVMe | 4        | 4      | 28.57%  |
| SAS  | 1        | 1      | 7.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 8        | 17     | 50%     |
| 0.51-1.0   | 7        | 8      | 43.75%  |
| 3.01-4.0   | 1        | 1      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 251-500    | 3        | 25%     |
| 1001-2000  | 3        | 25%     |
| 101-250    | 2        | 16.67%  |
| 2001-3000  | 1        | 8.33%   |
| 501-1000   | 1        | 8.33%   |
| 51-100     | 1        | 8.33%   |
| Unknown    | 1        | 8.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 101-250  | 4        | 33.33%  |
| 21-50    | 3        | 25%     |
| 251-500  | 1        | 8.33%   |
| 1-20     | 1        | 8.33%   |
| 501-1000 | 1        | 8.33%   |
| 51-100   | 1        | 8.33%   |
| Unknown  | 1        | 8.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST9250410AS 250GB | 1        | 1      | 33.33%  |
| Seagate ST500NM0011 500GB | 1        | 1      | 33.33%  |
| Seagate ST31000528AS 1TB  | 1        | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 3      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Intenso SSD SATAIII 120GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Intenso | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 6        | 16     | 37.5%   |
| Works    | 6        | 10     | 37.5%   |
| Malfunc  | 3        | 3      | 18.75%  |
| Failed   | 1        | 1      | 6.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 6        | 40%     |
| AMD                 | 4        | 26.67%  |
| SK Hynix            | 2        | 13.33%  |
| VIA Technologies    | 1        | 6.67%   |
| Samsung Electronics | 1        | 6.67%   |
| Phison Electronics  | 1        | 6.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 3        | 15.79%  |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 10.53%  |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 5.26%   |
| SK Hynix Non-Volatile memory controller                                                 | 1        | 5.26%   |
| SK Hynix BC511                                                                          | 1        | 5.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 5.26%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 5.26%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1        | 5.26%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 5.26%   |
| AMD X399 Series Chipset SATA Controller                                                 | 1        | 5.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 5.26%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 5.26%   |
| AMD FCH SATA Controller D                                                               | 1        | 5.26%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 8        | 53.33%  |
| NVMe | 4        | 26.67%  |
| IDE  | 2        | 13.33%  |
| RAID | 1        | 6.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 6        | 60%     |
| AMD    | 4        | 40%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core M-5Y10c CPU @ 0.80GHz               | 1        | 10%     |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 10%     |
| Intel Core i7-2600 CPU @ 3.40GHz               | 1        | 10%     |
| Intel Core i5-9500T CPU @ 2.20GHz              | 1        | 10%     |
| Intel Core i5-9400 CPU @ 2.90GHz               | 1        | 10%     |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 10%     |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 1        | 10%     |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 1        | 10%     |
| AMD FX-6300 Six-Core Processor                 | 1        | 10%     |
| AMD A4-5300B APU with Radeon HD Graphics       | 1        | 10%     |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 3        | 30%     |
| Intel Core i7          | 2        | 20%     |
| Intel Core M           | 1        | 10%     |
| AMD Ryzen Threadripper | 1        | 10%     |
| AMD Ryzen 3            | 1        | 10%     |
| AMD FX                 | 1        | 10%     |
| AMD A4                 | 1        | 10%     |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 3        | 30%     |
| 4      | 3        | 30%     |
| 12     | 1        | 10%     |
| 3      | 1        | 10%     |
| 2      | 1        | 10%     |
| 1      | 1        | 10%     |

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
| 2      | 6        | 60%     |
| 1      | 4        | 40%     |

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
| Unknown    | 6        | 54.55%  |
| 0x906ed    | 1        | 9.09%   |
| 0x306a9    | 1        | 9.09%   |
| 0x206a7    | 1        | 9.09%   |
| 0x0600111f | 1        | 9.09%   |
| 0x06000852 | 1        | 9.09%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 3        | 30%     |
| Zen         | 2        | 20%     |
| Piledriver  | 2        | 20%     |
| SandyBridge | 1        | 10%     |
| IvyBridge   | 1        | 10%     |
| Broadwell   | 1        | 10%     |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 5        | 41.67%  |
| Intel  | 4        | 33.33%  |
| AMD    | 3        | 25%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Nvidia TU117 [GeForce GTX 1650]                                  | 1        | 8.33%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                | 1        | 8.33%   |
| Nvidia GK104 [GeForce GTX 770]                                   | 1        | 8.33%   |
| Nvidia GA104 [GeForce RTX 3070]                                  | 1        | 8.33%   |
| Nvidia G86 [GeForce 8300 GS]                                     | 1        | 8.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller | 1        | 8.33%   |
| Intel HD Graphics 5300                                           | 1        | 8.33%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                         | 1        | 8.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                        | 1        | 8.33%   |
| AMD Trinity 2 [Radeon HD 7480D]                                  | 1        | 8.33%   |
| AMD RS780L [Radeon 3000]                                         | 1        | 8.33%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]             | 1        | 8.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 4        | 40%     |
| 1 x Intel    | 3        | 30%     |
| 1 x AMD      | 2        | 20%     |
| AMD + Nvidia | 1        | 10%     |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 6        | 60%     |
| Proprietary | 4        | 40%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 5        | 45.45%  |
| 1.01-2.0   | 2        | 18.18%  |
| 7.01-8.0   | 1        | 9.09%   |
| 3.01-4.0   | 1        | 9.09%   |
| 0.51-1.0   | 1        | 9.09%   |
| 0.01-0.5   | 1        | 9.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| AOC             | 2        | 20%     |
| Vizio           | 1        | 10%     |
| Sony            | 1        | 10%     |
| Sceptre         | 1        | 10%     |
| Philips         | 1        | 10%     |
| Hewlett-Packard | 1        | 10%     |
| Goldstar        | 1        | 10%     |
| Dell            | 1        | 10%     |
| AUS             | 1        | 10%     |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Vizio M320NV VIZ0070 1920x1080 700x390mm 31.5-inch         | 1        | 10%     |
| Sony SDM-HX73 SNY2870 1280x1024 338x270mm 17.0-inch        | 1        | 10%     |
| Sceptre LCD Monitor P30 2560x1080                          | 1        | 10%     |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch    | 1        | 10%     |
| Hewlett-Packard P224 HPN361C 1920x1080 480x270mm 21.7-inch | 1        | 10%     |
| Goldstar 24GM79G GSM5B39 1920x1080 531x298mm 24.0-inch     | 1        | 10%     |
| Dell S2419H DELD0D2 1920x1080 527x296mm 23.8-inch          | 1        | 10%     |
| AUS LCD Monitor VG259 1920x1080                            | 1        | 10%     |
| AOC LCD Monitor 2217 1680x1050                             | 1        | 10%     |
| AOC 917W AOC1917 1440x900 410x256mm 19.0-inch              | 1        | 10%     |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 5        | 55.56%  |
| 2560x1080          | 1        | 11.11%  |
| 1680x1050 (WSXGA+) | 1        | 11.11%  |
| 1440x900 (WXGA+)   | 1        | 11.11%  |
| 1280x1024 (SXGA)   | 1        | 11.11%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 3        | 30%     |
| 24      | 2        | 20%     |
| 42      | 1        | 10%     |
| 27      | 1        | 10%     |
| 23      | 1        | 10%     |
| 19      | 1        | 10%     |
| 17      | 1        | 10%     |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 3        | 33.33%  |
| Unknown     | 3        | 33.33%  |
| 401-500     | 1        | 11.11%  |
| 301-350     | 1        | 11.11%  |
| 901-1000    | 1        | 11.11%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 4        | 44.44%  |
| Unknown | 3        | 33.33%  |
| 5/4     | 1        | 11.11%  |
| 16/10   | 1        | 11.11%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 3        | 30%     |
| Unknown        | 3        | 30%     |
| 301-350        | 1        | 10%     |
| 151-200        | 1        | 10%     |
| 141-150        | 1        | 10%     |
| 501-1000       | 1        | 10%     |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 6        | 66.67%  |
| Unknown | 3        | 33.33%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 9        | 90%     |
| 2     | 1        | 10%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 8        | 47.06%  |
| Intel                           | 3        | 17.65%  |
| Qualcomm Atheros Communications | 2        | 11.76%  |
| Ralink Technology               | 1        | 5.88%   |
| Qualcomm Atheros                | 1        | 5.88%   |
| D-Link System                   | 1        | 5.88%   |
| Broadcom Limited                | 1        | 5.88%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 6        | 31.58%  |
| Qualcomm Atheros AR9271 802.11n                                      | 2        | 10.53%  |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 1        | 5.26%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 1        | 5.26%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1        | 5.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1        | 5.26%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 1        | 5.26%   |
| Intel Wireless 7265                                                  | 1        | 5.26%   |
| Intel Wireless 3160                                                  | 1        | 5.26%   |
| Intel I211 Gigabit Network Connection                                | 1        | 5.26%   |
| Intel Ethernet Connection (7) I219-LM                                | 1        | 5.26%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 1        | 5.26%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe             | 1        | 5.26%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Qualcomm Atheros Communications | 2        | 25%     |
| Intel                           | 2        | 25%     |
| Realtek Semiconductor           | 1        | 12.5%   |
| Ralink Technology               | 1        | 12.5%   |
| Qualcomm Atheros                | 1        | 12.5%   |
| D-Link System                   | 1        | 12.5%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                      | 2        | 25%     |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 1        | 12.5%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1        | 12.5%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1        | 12.5%   |
| Intel Wireless 7265                                                  | 1        | 12.5%   |
| Intel Wireless 3160                                                  | 1        | 12.5%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 1        | 12.5%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 63.64%  |
| Intel                 | 2        | 18.18%  |
| Qualcomm Atheros      | 1        | 9.09%   |
| Broadcom Limited      | 1        | 9.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6        | 54.55%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 9.09%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 9.09%   |
| Intel I211 Gigabit Network Connection                             | 1        | 9.09%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 9.09%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 9.09%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 10       | 55.56%  |
| WiFi     | 8        | 44.44%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 8        | 66.67%  |
| WiFi     | 4        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 6        | 60%     |
| 2     | 3        | 30%     |
| 3     | 1        | 10%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 9        | 90%     |
| Yes  | 1        | 10%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 2        | 50%     |
| Realtek Semiconductor           | 1        | 25%     |
| Qualcomm Atheros Communications | 1        | 25%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Intel Bluetooth wireless interface | 2        | 50%     |
| Realtek Bluetooth Radio            | 1        | 25%     |
| Qualcomm Atheros  Bluetooth Device | 1        | 25%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 6        | 37.5%   |
| AMD                 | 5        | 31.25%  |
| Nvidia              | 4        | 25%     |
| C-Media Electronics | 1        | 6.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Cannon Lake PCH cAVS                                                        | 2        | 10.53%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 2        | 10.53%  |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1        | 5.26%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1        | 5.26%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 5.26%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1        | 5.26%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 1        | 5.26%   |
| Intel Broadwell-U Audio Controller                                                | 1        | 5.26%   |
| Intel 200 Series PCH HD Audio                                                     | 1        | 5.26%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                               | 1        | 5.26%   |
| AMD Trinity HDMI Audio Controller                                                 | 1        | 5.26%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1        | 5.26%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 1        | 5.26%   |
| AMD FCH Azalia Controller                                                         | 1        | 5.26%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 1        | 5.26%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1        | 5.26%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 5.26%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 1        | 20%     |
| S                | 1        | 20%     |
| Nanya Technology | 1        | 20%     |
| Crucial          | 1        | 20%     |
| Corsair          | 1        | 20%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1600MT/s                  | 1        | 20%     |
| S RAM Module 2GB DIMM DDR3 1600MT/s                   | 1        | 20%     |
| Nanya RAM NT4GC64B88B1NF-DI 4GB DIMM DDR3 1600MT/s    | 1        | 20%     |
| Crucial RAM CT102464BA1339.C16 8GB DIMM DDR3 1333MT/s | 1        | 20%     |
| Corsair RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s   | 1        | 20%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 3        | 60%     |
| DDR4    | 1        | 20%     |
| Unknown | 1        | 20%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 5        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 8192 | 2        | 40%     |
| 4096 | 2        | 40%     |
| 2048 | 1        | 20%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 3        | 60%     |
| 2666  | 1        | 20%     |
| 1333  | 1        | 20%     |

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

Zero info for selected period =(

Camera Model
------------

Camera device models

Zero info for selected period =(

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
| 0     | 9        | 90%     |
| 1     | 1        | 10%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type         | Desktops | Percent |
|--------------|----------|---------|
| Net/wireless | 1        | 100%    |

