Pardus - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Pardus.

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

Total: 14

| Vendor   | Model                 | Probe                                                      | Date         |
|----------|-----------------------|------------------------------------------------------------|--------------|
| Acer     | Veriton ES2740G V:1.0 | [e14aeaaca3](https://linux-hardware.org/?probe=e14aeaaca3) | Jul 25, 2022 |
| MSI      | B250M GAMING PRO      | [052965926e](https://linux-hardware.org/?probe=052965926e) | Jun 26, 2022 |
| MSI      | MS-7360               | [1ca1d835ad](https://linux-hardware.org/?probe=1ca1d835ad) | May 22, 2022 |
| MSI      | H310M PRO-VDH PLUS    | [0d897cd79c](https://linux-hardware.org/?probe=0d897cd79c) | Apr 15, 2022 |
| MSI      | MS-7360               | [34c10f0508](https://linux-hardware.org/?probe=34c10f0508) | Apr 10, 2022 |
| MSI      | H81M-P33              | [2b0d95df2e](https://linux-hardware.org/?probe=2b0d95df2e) | Apr 02, 2022 |
| MSI      | MS-7360               | [8efb24e401](https://linux-hardware.org/?probe=8efb24e401) | Mar 21, 2022 |
| MSI      | MS-7360               | [99ac168204](https://linux-hardware.org/?probe=99ac168204) | Mar 18, 2022 |
| Gigabyte | A320M-S2H-CF          | [fcde789242](https://linux-hardware.org/?probe=fcde789242) | Jan 24, 2022 |
| Gigabyte | A320M-S2H-CF          | [dd92029684](https://linux-hardware.org/?probe=dd92029684) | Jan 21, 2022 |
| Lenovo   | 3132 NOK              | [9d1ef122f7](https://linux-hardware.org/?probe=9d1ef122f7) | Oct 11, 2021 |
| Lenovo   | 3132 NOK              | [5802651f49](https://linux-hardware.org/?probe=5802651f49) | Sep 15, 2021 |
| ASUSTek  | P5G41C-M LX           | [9149be671f](https://linux-hardware.org/?probe=9149be671f) | Jan 30, 2021 |
| Gigabyte | A320M-H-CF            | [33cdf15439](https://linux-hardware.org/?probe=33cdf15439) | Dec 15, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Pardus 21.2   | 5        | 45.45%  |
| Pardus 21.3   | 1        | 9.09%   |
| Pardus 21.1   | 1        | 9.09%   |
| Pardus 21.0   | 1        | 9.09%   |
| Pardus 19.5   | 1        | 9.09%   |
| Pardus 19.4-1 | 1        | 9.09%   |
| Pardus 19.4   | 1        | 9.09%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Pardus | 11       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Desktops | Percent |
|---------------------|----------|---------|
| 5.10.0-13-amd64     | 3        | 27.27%  |
| 5.9.0-0.bpo.2-amd64 | 1        | 9.09%   |
| 5.10.0-8-amd64      | 1        | 9.09%   |
| 5.10.0-16-amd64     | 1        | 9.09%   |
| 5.10.0-15-amd64     | 1        | 9.09%   |
| 5.10.0-14-amd64     | 1        | 9.09%   |
| 5.10.0-12-amd64     | 1        | 9.09%   |
| 4.19.0-18-amd64     | 1        | 9.09%   |
| 4.19.0-13-amd64     | 1        | 9.09%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 8        | 72.73%  |
| 4.19.0  | 2        | 18.18%  |
| 5.9.0   | 1        | 9.09%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 8        | 72.73%  |
| 4.19    | 2        | 18.18%  |
| 5.9     | 1        | 9.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 11       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| XFCE  | 8        | 72.73%  |
| GNOME | 2        | 18.18%  |
| KDE5  | 1        | 9.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 11       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 8        | 72.73%  |
| LightDM | 2        | 18.18%  |
| SDDM    | 1        | 9.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| tr_TR | 10       | 90.91%  |
| fr_FR | 1        | 9.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 11       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ext4 | 11       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 10       | 90.91%  |
| GPT     | 1        | 9.09%   |

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
| No        | 10       | 90.91%  |
| Yes       | 1        | 9.09%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI                 | 6        | 54.55%  |
| Gigabyte Technology | 2        | 18.18%  |
| Lenovo              | 1        | 9.09%   |
| ASUSTek Computer    | 1        | 9.09%   |
| Acer                | 1        | 9.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| MSI MS-7360                         | 3        | 27.27%  |
| MSI MS-7C09                         | 1        | 9.09%   |
| MSI MS-7A65                         | 1        | 9.09%   |
| MSI MS-7817                         | 1        | 9.09%   |
| Lenovo ThinkCentre M920t 10SGS62900 | 1        | 9.09%   |
| Gigabyte A320M-S2H                  | 1        | 9.09%   |
| Gigabyte A320M-H                    | 1        | 9.09%   |
| ASUS P5G41C-M LX                    | 1        | 9.09%   |
| Acer Veriton ES2740G                | 1        | 9.09%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| MSI MS-7360        | 3        | 27.27%  |
| MSI MS-7C09        | 1        | 9.09%   |
| MSI MS-7A65        | 1        | 9.09%   |
| MSI MS-7817        | 1        | 9.09%   |
| Lenovo ThinkCentre | 1        | 9.09%   |
| Gigabyte A320M-S2H | 1        | 9.09%   |
| Gigabyte A320M-H   | 1        | 9.09%   |
| ASUS P5G41C-M      | 1        | 9.09%   |
| Acer Veriton       | 1        | 9.09%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2007 | 3        | 27.27%  |
| 2018 | 2        | 18.18%  |
| 2017 | 2        | 18.18%  |
| 2021 | 1        | 9.09%   |
| 2020 | 1        | 9.09%   |
| 2013 | 1        | 9.09%   |
| 2010 | 1        | 9.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 11       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 11       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 11       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 4        | 36.36%  |
| 4.01-8.0   | 2        | 18.18%  |
| 16.01-24.0 | 2        | 18.18%  |
| 32.01-64.0 | 1        | 9.09%   |
| 2.01-3.0   | 1        | 9.09%   |
| 8.01-16.0  | 1        | 9.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 5        | 41.67%  |
| 3.01-4.0   | 2        | 16.67%  |
| 2.01-3.0   | 2        | 16.67%  |
| 4.01-8.0   | 1        | 8.33%   |
| 24.01-32.0 | 1        | 8.33%   |
| 8.01-16.0  | 1        | 8.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 5        | 45.45%  |
| 1      | 4        | 36.36%  |
| 4      | 1        | 9.09%   |
| 3      | 1        | 9.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 7        | 63.64%  |
| No        | 4        | 36.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 11       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 8        | 72.73%  |
| Yes       | 3        | 27.27%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 81.82%  |
| Yes       | 2        | 18.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Turkey  | 10       | 90.91%  |
| France  | 1        | 9.09%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City      | Desktops | Percent |
|-----------|----------|---------|
| Bursa     | 4        | 36.36%  |
| Aydin     | 2        | 18.18%  |
| Yaman     | 1        | 9.09%   |
| Soleymieu | 1        | 9.09%   |
| Konya     | 1        | 9.09%   |
| Istanbul  | 1        | 9.09%   |
| Ankara    | 1        | 9.09%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 5      | 25%     |
| Samsung Electronics | 3        | 5      | 15%     |
| A-DATA Technology   | 3        | 3      | 15%     |
| Seagate             | 2        | 3      | 10%     |
| KIOXIA-EXCERIA      | 2        | 2      | 10%     |
| Team                | 1        | 1      | 5%      |
| SanDisk             | 1        | 1      | 5%      |
| Kingston            | 1        | 1      | 5%      |
| Corsair             | 1        | 1      | 5%      |
| China               | 1        | 1      | 5%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| WDC WD6402AAEX-00Y9A0 640GB      | 3        | 14.29%  |
| A-DATA SU650 120GB SSD           | 3        | 14.29%  |
| WDC WD5000AAKX-00ERMA0 500GB     | 1        | 4.76%   |
| WDC WD3200AAJB-00WGA0 320GB      | 1        | 4.76%   |
| Team T253X1240G 240GB SSD        | 1        | 4.76%   |
| Seagate ST3160318AS 160GB        | 1        | 4.76%   |
| Seagate ST2000DM008-2FR102 2TB   | 1        | 4.76%   |
| SanDisk Ultra II 240GB SSD       | 1        | 4.76%   |
| Samsung NVMe SSD Drive 512GB     | 1        | 4.76%   |
| Samsung HD501LJ 500GB            | 1        | 4.76%   |
| Samsung HD160HJ 160GB            | 1        | 4.76%   |
| Samsung HD103SJ 1TB              | 1        | 4.76%   |
| KIOXIA-EXCERIA SATA SSD 480GB    | 1        | 4.76%   |
| KIOXIA-EXCERIA SATA SSD 240GB    | 1        | 4.76%   |
| Kingston SV300S37A120G 120GB SSD | 1        | 4.76%   |
| Corsair Force LS SSD 64GB        | 1        | 4.76%   |
| China SATA SSD 120GB             | 1        | 4.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 5      | 55.56%  |
| Seagate             | 2        | 3      | 22.22%  |
| Samsung Electronics | 2        | 3      | 22.22%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| A-DATA Technology | 3        | 3      | 30%     |
| KIOXIA-EXCERIA    | 2        | 2      | 20%     |
| Team              | 1        | 1      | 10%     |
| SanDisk           | 1        | 1      | 10%     |
| Kingston          | 1        | 1      | 10%     |
| Corsair           | 1        | 1      | 10%     |
| China             | 1        | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 8        | 10     | 50%     |
| HDD  | 7        | 11     | 43.75%  |
| NVMe | 1        | 2      | 6.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 11       | 21     | 91.67%  |
| NVMe | 1        | 2      | 8.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 10       | 15     | 66.67%  |
| 0.51-1.0   | 4        | 4      | 26.67%  |
| 1.01-2.0   | 1        | 2      | 6.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 5        | 45.45%  |
| 251-500    | 2        | 18.18%  |
| 501-1000   | 2        | 18.18%  |
| 2001-3000  | 1        | 9.09%   |
| 51-100     | 1        | 9.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 51-100   | 4        | 36.36%  |
| 21-50    | 3        | 27.27%  |
| 101-250  | 2        | 18.18%  |
| 1-20     | 1        | 9.09%   |
| 501-1000 | 1        | 9.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Kingston SV300S37A120G 120GB SSD | 1        | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Kingston | 1        | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 1        | 1      | 100%    |

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
| Detected | 10       | 20     | 83.33%  |
| Malfunc  | 1        | 1      | 8.33%   |
| Works    | 1        | 2      | 8.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 9        | 60%     |
| Marvell Technology Group | 3        | 20%     |
| AMD                      | 2        | 13.33%  |
| Samsung Electronics      | 1        | 6.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                          | 3        | 14.29%  |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                         | 3        | 14.29%  |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 3        | 14.29%  |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2        | 9.52%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2        | 9.52%   |
| AMD FCH SATA Controller D                                                      | 2        | 9.52%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 4.76%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 4.76%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 4.76%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1        | 4.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 4.76%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1        | 4.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 7        | 58.33%  |
| IDE  | 4        | 33.33%  |
| NVMe | 1        | 8.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 9        | 81.82%  |
| AMD    | 2        | 18.18%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 3        | 27.27%  |
| Intel Core i9-9900 CPU @ 3.10GHz              | 1        | 9.09%   |
| Intel Core i5-7600 CPU @ 3.50GHz              | 1        | 9.09%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 1        | 9.09%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 1        | 9.09%   |
| Intel Core i3-9100F CPU @ 3.60GHz             | 1        | 9.09%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz         | 1        | 9.09%   |
| AMD Ryzen 5 3500X 6-Core Processor            | 1        | 9.09%   |
| AMD A8-9600 RADEON R7, 10 COMPUTE CORES 4C+6G | 1        | 9.09%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core 2 Quad | 4        | 36.36%  |
| Intel Core i5     | 3        | 27.27%  |
| Intel Core i9     | 1        | 9.09%   |
| Intel Core i3     | 1        | 9.09%   |
| AMD Ryzen 5       | 1        | 9.09%   |
| AMD A8            | 1        | 9.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 7        | 63.64%  |
| 6      | 2        | 18.18%  |
| 8      | 1        | 9.09%   |
| 2      | 1        | 9.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 11       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 8        | 72.73%  |
| 2      | 3        | 27.27%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 11       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 8        | 72.73%  |
| 0x906eb | 1        | 9.09%   |
| 0x906e9 | 1        | 9.09%   |
| 0x306c3 | 1        | 9.09%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| KabyLake  | 3        | 27.27%  |
| Core      | 3        | 27.27%  |
| Zen 2     | 1        | 9.09%   |
| Penryn    | 1        | 9.09%   |
| Haswell   | 1        | 9.09%   |
| Excavator | 1        | 9.09%   |
| CometLake | 1        | 9.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 6        | 42.86%  |
| Intel  | 4        | 28.57%  |
| AMD    | 4        | 28.57%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GT200 [GeForce GTX 260]                                              | 3        | 21.43%  |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 14.29%  |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 7.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 7.14%   |
| Intel HD Graphics 630                                                       | 1        | 7.14%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 7.14%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 7.14%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1        | 7.14%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 7.14%   |
| AMD Bonaire XT [Radeon HD 7790/8770 / R7 360 / R9 260/360 OEM]              | 1        | 7.14%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 7.14%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 6        | 54.55%  |
| 1 x AMD    | 4        | 36.36%  |
| 1 x Intel  | 1        | 9.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 10       | 90.91%  |
| Proprietary | 1        | 9.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 8        | 72.73%  |
| 0.51-1.0   | 2        | 18.18%  |
| 1.01-2.0   | 1        | 9.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Goldstar            | 3        | 25%     |
| Samsung Electronics | 2        | 16.67%  |
| Acer                | 2        | 16.67%  |
| SAC                 | 1        | 8.33%   |
| Iiyama              | 1        | 8.33%   |
| Dell                | 1        | 8.33%   |
| Beko                | 1        | 8.33%   |
| AGO                 | 1        | 8.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Goldstar W2242 GSM5678 1680x1050 474x296mm 22.0-inch                | 3        | 25%     |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch   | 1        | 8.33%   |
| Samsung Electronics SyncMaster SAM0599 1600x900 443x249mm 20.0-inch | 1        | 8.33%   |
| SAC Casper SAC3219 1366x768 304x228mm 15.0-inch                     | 1        | 8.33%   |
| Iiyama PLX2380H IVM5621 1920x1080 509x286mm 23.0-inch               | 1        | 8.33%   |
| Dell E2421HN DELF129 1920x1080 527x296mm 23.8-inch                  | 1        | 8.33%   |
| Beko BK WUXGA BEK4448 1920x1080 1600x900mm 72.3-inch                | 1        | 8.33%   |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch               | 1        | 8.33%   |
| Acer V226HQL ACR032D 1920x1080 477x268mm 21.5-inch                  | 1        | 8.33%   |
| Acer G206HQL ACR0327 1600x900 432x239mm 19.4-inch                   | 1        | 8.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 5        | 41.67%  |
| 1680x1050 (WSXGA+) | 3        | 25%     |
| 1600x900 (HD+)     | 2        | 16.67%  |
| 3840x2160 (4K)     | 1        | 8.33%   |
| 1366x768 (WXGA)    | 1        | 8.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 23     | 5        | 41.67%  |
| 72     | 1        | 8.33%   |
| 31     | 1        | 8.33%   |
| 21     | 1        | 8.33%   |
| 20     | 1        | 8.33%   |
| 19     | 1        | 8.33%   |
| 15     | 1        | 8.33%   |
| 12     | 1        | 8.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 6        | 50%     |
| 501-600     | 2        | 16.67%  |
| 601-700     | 1        | 8.33%   |
| 301-350     | 1        | 8.33%   |
| 201-300     | 1        | 8.33%   |
| 1501-2000   | 1        | 8.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 6        | 54.55%  |
| 3/2   | 3        | 27.27%  |
| 4/3   | 2        | 18.18%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 6        | 50%     |
| 151-200        | 2        | 16.67%  |
| More than 1000 | 1        | 8.33%   |
| 71-80          | 1        | 8.33%   |
| 351-500        | 1        | 8.33%   |
| 101-110        | 1        | 8.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 7        | 58.33%  |
| 101-120 | 2        | 16.67%  |
| 1-50    | 1        | 8.33%   |
| 161-240 | 1        | 8.33%   |
| 121-160 | 1        | 8.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10       | 90.91%  |
| 2     | 1        | 9.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 9        | 64.29%  |
| Intel                 | 3        | 21.43%  |
| ZyXEL Communications  | 1        | 7.14%   |
| Ralink Technology     | 1        | 7.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9        | 64.29%  |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]      | 1        | 7.14%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 7.14%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 7.14%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 7.14%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 7.14%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| ZyXEL Communications | 1        | 33.33%  |
| Ralink Technology    | 1        | 33.33%  |
| Intel                | 1        | 33.33%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU] | 1        | 33.33%  |
| Ralink RT2870/RT3070 Wireless Adapter                        | 1        | 33.33%  |
| Intel Wi-Fi 6 AX200                                          | 1        | 33.33%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 9        | 81.82%  |
| Intel                 | 2        | 18.18%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9        | 81.82%  |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 9.09%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 9.09%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 11       | 78.57%  |
| WiFi     | 3        | 21.43%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 10       | 90.91%  |
| WiFi     | 1        | 9.09%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10       | 90.91%  |
| 2     | 1        | 9.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 10       | 90.91%  |
| Yes  | 1        | 9.09%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 1        | 50%     |
| Cambridge Silicon Radio | 1        | 50%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 1        | 50%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 50%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 9        | 60%     |
| AMD    | 4        | 26.67%  |
| Nvidia | 2        | 13.33%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel 82801I (ICH9 Family) HD Audio Controller                      | 3        | 17.65%  |
| Intel 200 Series PCH HD Audio                                       | 2        | 11.76%  |
| Nvidia High Definition Audio Controller                             | 1        | 5.88%   |
| Nvidia GP107GL High Definition Audio Controller                     | 1        | 5.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller             | 1        | 5.88%   |
| Intel Comet Lake PCH-V cAVS                                         | 1        | 5.88%   |
| Intel Cannon Lake PCH cAVS                                          | 1        | 5.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 1        | 5.88%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                  | 1        | 5.88%   |
| AMD Starship/Matisse HD Audio Controller                            | 1        | 5.88%   |
| AMD Kabini HDMI/DP Audio                                            | 1        | 5.88%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                    | 1        | 5.88%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 1        | 5.88%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]        | 1        | 5.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Kingston          | 1        | 33.33%  |
| G.Skill           | 1        | 33.33%  |
| A-DATA Technology | 1        | 33.33%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 3400MT/s | 1        | 25%     |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s    | 1        | 25%     |
| G.Skill RAM F4-2133C15-4GIS 4GB DIMM DDR4 2133MT/s   | 1        | 25%     |
| A-DATA RAM Module 8GB DIMM DDR4 2667MT/s             | 1        | 25%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 3        | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 3        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 8192 | 2        | 66.67%  |
| 4096 | 1        | 33.33%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3400  | 1        | 25%     |
| 2667  | 1        | 25%     |
| 2400  | 1        | 25%     |
| 2133  | 1        | 25%     |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Zebra  | 2        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Zebra Zebra GC420d Label Printer | 1        | 50%     |
| Zebra TLP2844                    | 1        | 50%     |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Microdia              | 1        | 50%     |
| Arkmicro Technologies | 1        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Microdia Integrated Camera | 1        | 50%     |
| Arkmicro USB2.0 PC CAMERA  | 1        | 50%     |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Advanced Card Systems | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Advanced Card Systems ACR38 SmartCard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 10       | 83.33%  |
| 1     | 2        | 16.67%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Chipcard | 1        | 50%     |
| Camera   | 1        | 50%     |

