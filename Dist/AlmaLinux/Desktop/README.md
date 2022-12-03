AlmaLinux - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

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

Total: 8

| Vendor   | Model                 | Probe                                                      | Date         |
|----------|-----------------------|------------------------------------------------------------|--------------|
| Gigabyte | H81M-D2V              | [6035f1ee45](https://linux-hardware.org/?probe=6035f1ee45) | Nov 11, 2022 |
| ASUSTek  | Q170M2                | [c62954095d](https://linux-hardware.org/?probe=c62954095d) | Nov 11, 2022 |
| Lenovo   | 1052 NOK              | [28cd1416fe](https://linux-hardware.org/?probe=28cd1416fe) | Sep 22, 2022 |
| ASRock   | B460 Phantom Gaming 4 | [0dc125da55](https://linux-hardware.org/?probe=0dc125da55) | Jul 05, 2022 |
| Gigabyte | Z590 AORUS PRO AX     | [a517886d4d](https://linux-hardware.org/?probe=a517886d4d) | Feb 10, 2022 |
| ASUSTek  | M5A78L-M/USB3         | [e5a30a171e](https://linux-hardware.org/?probe=e5a30a171e) | Jun 08, 2021 |
| ASUSTek  | M5A78L-M/USB3         | [043878564d](https://linux-hardware.org/?probe=043878564d) | Jun 08, 2021 |
| HP       | 0AE8h C               | [b7fd559b13](https://linux-hardware.org/?probe=b7fd559b13) | Mar 24, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| AlmaLinux 9.0 | 3        | 42.86%  |
| AlmaLinux 8.6 | 1        | 14.29%  |
| AlmaLinux 8.5 | 1        | 14.29%  |
| AlmaLinux 8.4 | 1        | 14.29%  |
| AlmaLinux 8.3 | 1        | 14.29%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| AlmaLinux | 7        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.14.0-70.30.1.el9_0.x86_64  | 2        | 28.57%  |
| 5.14.0-70.22.1.el9_0.x86_64  | 1        | 14.29%  |
| 4.18.0-372.9.1.el8.x86_64    | 1        | 14.29%  |
| 4.18.0-348.12.2.el8_5.x86_64 | 1        | 14.29%  |
| 4.18.0-305.el8.x86_64        | 1        | 14.29%  |
| 4.18.0-240.15.1.el8_3.x86_64 | 1        | 14.29%  |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18.0  | 4        | 57.14%  |
| 5.14.0  | 3        | 42.86%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 4        | 57.14%  |
| 5.14    | 3        | 42.86%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 7        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GNOME   | 5        | 71.43%  |
| XFCE    | 1        | 14.29%  |
| Unknown | 1        | 14.29%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 3        | 42.86%  |
| Wayland | 2        | 28.57%  |
| Tty     | 2        | 28.57%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 5        | 71.43%  |
| GDM     | 2        | 28.57%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 3        | 42.86%  |
| uk_UA | 1        | 14.29%  |
| ru_RU | 1        | 14.29%  |
| en_CA | 1        | 14.29%  |
| de_DE | 1        | 14.29%  |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 5        | 71.43%  |
| BIOS | 2        | 28.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 5        | 71.43%  |
| Ext4 | 2        | 28.57%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 4        | 57.14%  |
| Unknown | 3        | 42.86%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 4        | 57.14%  |
| Yes       | 3        | 42.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 4        | 57.14%  |
| Yes       | 3        | 42.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 2        | 28.57%  |
| ASUSTek Computer    | 2        | 28.57%  |
| Lenovo              | 1        | 14.29%  |
| Hewlett-Packard     | 1        | 14.29%  |
| ASRock              | 1        | 14.29%  |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Lenovo ThinkStation P350 30E6S20S00 | 1        | 14.29%  |
| HP Z600 Workstation                 | 1        | 14.29%  |
| Gigabyte Z590 AORUS PRO AX          | 1        | 14.29%  |
| Gigabyte H81M-D2V                   | 1        | 14.29%  |
| ASUS Q170M2                         | 1        | 14.29%  |
| ASUS M5A78L-M/USB3                  | 1        | 14.29%  |
| ASRock B460 Phantom Gaming 4        | 1        | 14.29%  |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Lenovo ThinkStation | 1        | 14.29%  |
| HP Z600             | 1        | 14.29%  |
| Gigabyte Z590       | 1        | 14.29%  |
| Gigabyte H81M-D2V   | 1        | 14.29%  |
| ASUS Q170M2         | 1        | 14.29%  |
| ASUS M5A78L-M       | 1        | 14.29%  |
| ASRock B460         | 1        | 14.29%  |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2022 | 1        | 14.29%  |
| 2021 | 1        | 14.29%  |
| 2020 | 1        | 14.29%  |
| 2018 | 1        | 14.29%  |
| 2013 | 1        | 14.29%  |
| 2011 | 1        | 14.29%  |
| 2009 | 1        | 14.29%  |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 7        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 6        | 85.71%  |
| Enabled  | 1        | 14.29%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 7        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 8.01-16.0  | 3        | 42.86%  |
| 4.01-8.0   | 1        | 14.29%  |
| 32.01-64.0 | 1        | 14.29%  |
| 24.01-32.0 | 1        | 14.29%  |
| 16.01-24.0 | 1        | 14.29%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 2        | 28.57%  |
| 1.01-2.0  | 2        | 28.57%  |
| 4.01-8.0  | 1        | 14.29%  |
| 8.01-16.0 | 1        | 14.29%  |
| 0.51-1.0  | 1        | 14.29%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 4      | 4        | 57.14%  |
| 2      | 2        | 28.57%  |
| 1      | 1        | 14.29%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 5        | 71.43%  |
| Yes       | 2        | 28.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 7        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 5        | 71.43%  |
| Yes       | 2        | 28.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 4        | 57.14%  |
| Yes       | 3        | 42.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Russia      | 2        | 28.57%  |
| USA         | 1        | 14.29%  |
| Ukraine     | 1        | 14.29%  |
| Netherlands | 1        | 14.29%  |
| Germany     | 1        | 14.29%  |
| Canada      | 1        | 14.29%  |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Desktops | Percent |
|--------------|----------|---------|
| Zaporizhzhia | 1        | 14.29%  |
| Stadtilm     | 1        | 14.29%  |
| Shimanovsk   | 1        | 14.29%  |
| Moscow       | 1        | 14.29%  |
| Kitimat      | 1        | 14.29%  |
| Groningen    | 1        | 14.29%  |
| Bloomington  | 1        | 14.29%  |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 4        | 7      | 28.57%  |
| Crucial                     | 2        | 4      | 14.29%  |
| WDC                         | 1        | 1      | 7.14%   |
| Toshiba                     | 1        | 1      | 7.14%   |
| SK hynix                    | 1        | 1      | 7.14%   |
| Samsung Electronics         | 1        | 3      | 7.14%   |
| Netac                       | 1        | 1      | 7.14%   |
| LITEON                      | 1        | 1      | 7.14%   |
| Kingston Technology Company | 1        | 1      | 7.14%   |
| Kingston                    | 1        | 1      | 7.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB                    | 1        | 5.26%   |
| Toshiba DT01ACA100 1TB                      | 1        | 5.26%   |
| SK hynix SH920 2.5 7MM 256GB SSD            | 1        | 5.26%   |
| Seagate ST4000NM000A 00MX141 00MX141LEN 4TB | 1        | 5.26%   |
| Seagate ST4000NC001-1FS168 4TB              | 1        | 5.26%   |
| Seagate ST4000DM000-1F2168 4TB              | 1        | 5.26%   |
| Seagate ST31000528AS 1TB                    | 1        | 5.26%   |
| Seagate ST2000DM001-1ER164 2TB              | 1        | 5.26%   |
| Seagate ST1000NM0033-9ZM173 1TB             | 1        | 5.26%   |
| Seagate ST10000NM0478-2H7100 10TB           | 1        | 5.26%   |
| Samsung PSSD T7 Touch 1TB                   | 1        | 5.26%   |
| Samsung MZVL22T0HBLB-00BL7 2TB              | 1        | 5.26%   |
| Netac SSD 512GB                             | 1        | 5.26%   |
| LITEON CV1-8B256-HP 256GB SSD               | 1        | 5.26%   |
| Kingston Company A2000 NVMe SSD 500GB       | 1        | 5.26%   |
| Kingston SV300S37A240G 240GB SSD            | 1        | 5.26%   |
| Crucial CT480BX500SSD1 480GB                | 1        | 5.26%   |
| Crucial CT240BX500SSD1 240GB                | 1        | 5.26%   |
| Crucial CT1000P5PSSD8 1TB                   | 1        | 5.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 7      | 66.67%  |
| WDC     | 1        | 1      | 16.67%  |
| Toshiba | 1        | 1      | 16.67%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SK hynix            | 1        | 1      | 16.67%  |
| Samsung Electronics | 1        | 1      | 16.67%  |
| Netac               | 1        | 1      | 16.67%  |
| LITEON              | 1        | 1      | 16.67%  |
| Kingston            | 1        | 1      | 16.67%  |
| Crucial             | 1        | 2      | 16.67%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 5        | 7      | 38.46%  |
| HDD  | 5        | 9      | 38.46%  |
| NVMe | 3        | 5      | 23.08%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 7        | 15     | 63.64%  |
| NVMe | 3        | 5      | 27.27%  |
| SAS  | 1        | 1      | 9.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.51-1.0   | 5        | 6      | 35.71%  |
| 0.01-0.5   | 4        | 5      | 28.57%  |
| 3.01-4.0   | 3        | 3      | 21.43%  |
| 1.01-2.0   | 1        | 1      | 7.14%   |
| 4.01-10.0  | 1        | 1      | 7.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 2        | 28.57%  |
| More than 3000 | 1        | 14.29%  |
| 2001-3000      | 1        | 14.29%  |
| 1001-2000      | 1        | 14.29%  |
| 1-20           | 1        | 14.29%  |
| 501-1000       | 1        | 14.29%  |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 3        | 42.86%  |
| 251-500        | 2        | 28.57%  |
| More than 3000 | 1        | 14.29%  |
| 51-100         | 1        | 14.29%  |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| SK hynix SH920 2.5 7MM 256GB SSD | 1        | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| SK hynix | 1        | 1      | 100%    |

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
| Detected | 4        | 10     | 44.44%  |
| Works    | 4        | 10     | 44.44%  |
| Malfunc  | 1        | 1      | 11.11%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 6        | 60%     |
| Samsung Electronics         | 1        | 10%     |
| Micron/Crucial Technology   | 1        | 10%     |
| Kingston Technology Company | 1        | 10%     |
| AMD                         | 1        | 10%     |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2        | 18.18%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 9.09%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1        | 9.09%   |
| Kingston Company A2000 NVMe SSD                                                | 1        | 9.09%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 9.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 9.09%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 9.09%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1        | 9.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1        | 9.09%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1        | 9.09%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 6        | 54.55%  |
| NVMe | 3        | 27.27%  |
| RAID | 1        | 9.09%   |
| IDE  | 1        | 9.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 6        | 85.71%  |
| AMD    | 1        | 14.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Xeon W-1350 @ 3.30GHz            | 1        | 14.29%  |
| Intel Xeon CPU X5550 @ 2.67GHz         | 1        | 14.29%  |
| Intel Core i7-7700 CPU @ 3.60GHz       | 1        | 14.29%  |
| Intel Core i5-10400F CPU @ 2.90GHz     | 1        | 14.29%  |
| Intel Core i3-4130 CPU @ 3.40GHz       | 1        | 14.29%  |
| Intel 11th Gen Core i5-11400 @ 2.60GHz | 1        | 14.29%  |
| AMD FX-8350 Eight-Core Processor       | 1        | 14.29%  |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| Intel Xeon    | 2        | 28.57%  |
| Other         | 1        | 14.29%  |
| Intel Core i7 | 1        | 14.29%  |
| Intel Core i5 | 1        | 14.29%  |
| Intel Core i3 | 1        | 14.29%  |
| AMD FX        | 1        | 14.29%  |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 3        | 42.86%  |
| 4      | 3        | 42.86%  |
| 2      | 1        | 14.29%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 7        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 7        | 100%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 7        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0xa0671    | 2        | 28.57%  |
| 0xa0655    | 1        | 14.29%  |
| 0x906e9    | 1        | 14.29%  |
| 0x306c3    | 1        | 14.29%  |
| 0x106a5    | 1        | 14.29%  |
| 0x06000852 | 1        | 14.29%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Icelake    | 2        | 28.57%  |
| Piledriver | 1        | 14.29%  |
| Nehalem    | 1        | 14.29%  |
| KabyLake   | 1        | 14.29%  |
| Haswell    | 1        | 14.29%  |
| CometLake  | 1        | 14.29%  |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 3        | 42.86%  |
| AMD    | 3        | 42.86%  |
| Nvidia | 1        | 14.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Nvidia GP104 [GeForce GTX 1080]                                           | 1        | 14.29%  |
| Intel RocketLake-S GT1 [UHD Graphics P750]                                | 1        | 14.29%  |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                 | 1        | 14.29%  |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1        | 14.29%  |
| AMD RS780L [Radeon 3000]                                                  | 1        | 14.29%  |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 1        | 14.29%  |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]       | 1        | 14.29%  |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 3        | 42.86%  |
| 1 x AMD    | 3        | 42.86%  |
| 1 x Nvidia | 1        | 14.29%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 5        | 71.43%  |
| Unknown | 2        | 28.57%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 4        | 57.14%  |
| 7.01-8.0   | 1        | 14.29%  |
| 1.01-2.0   | 1        | 14.29%  |
| 0.01-0.5   | 1        | 14.29%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| STD                 | 1        | 16.67%  |
| Samsung Electronics | 1        | 16.67%  |
| Philips             | 1        | 16.67%  |
| Lenovo              | 1        | 16.67%  |
| Goldstar            | 1        | 16.67%  |
| Dell                | 1        | 16.67%  |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| STD HDMI TV STD00C7 1920x1080 698x392mm 31.5-inch                    | 1        | 14.29%  |
| Samsung Electronics SyncMaster SAM021B 1400x1050 408x300mm 19.9-inch | 1        | 14.29%  |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch    | 1        | 14.29%  |
| Philips 19B PHL0879 1280x1024 376x301mm 19.0-inch                    | 1        | 14.29%  |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                 | 1        | 14.29%  |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch          | 1        | 14.29%  |
| Dell 1905FP DEL400C 1280x1024 376x301mm 19.0-inch                    | 1        | 14.29%  |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 2        | 28.57%  |
| 1280x1024 (SXGA) | 2        | 28.57%  |
| 2560x1440 (QHD)  | 1        | 14.29%  |
| 2560x1080        | 1        | 14.29%  |
| 1400x1050        | 1        | 14.29%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 19     | 2        | 28.57%  |
| 34     | 1        | 14.29%  |
| 31     | 1        | 14.29%  |
| 27     | 1        | 14.29%  |
| 24     | 1        | 14.29%  |
| 20     | 1        | 14.29%  |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 2        | 28.57%  |
| 351-400     | 2        | 28.57%  |
| 701-800     | 1        | 14.29%  |
| 601-700     | 1        | 14.29%  |
| 401-500     | 1        | 14.29%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 3        | 42.86%  |
| 6/5   | 1        | 14.29%  |
| 5/4   | 1        | 14.29%  |
| 4/3   | 1        | 14.29%  |
| 21/9  | 1        | 14.29%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 3        | 42.86%  |
| 351-500        | 2        | 28.57%  |
| 301-350        | 1        | 14.29%  |
| 201-250        | 1        | 14.29%  |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 5        | 83.33%  |
| 121-160 | 1        | 16.67%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3        | 42.86%  |
| 2     | 2        | 28.57%  |
| 0     | 2        | 28.57%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 4        | 44.44%  |
| Realtek Semiconductor | 3        | 33.33%  |
| Broadcom Limited      | 1        | 11.11%  |
| Broadcom              | 1        | 11.11%  |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3        | 21.43%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 7.14%   |
| Intel Wireless 8260                                               | 1        | 7.14%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 7.14%   |
| Intel I350 Gigabit Network Connection                             | 1        | 7.14%   |
| Intel I210 Gigabit Network Connection                             | 1        | 7.14%   |
| Intel Ethernet Controller I225-V                                  | 1        | 7.14%   |
| Intel Ethernet Connection I219-LM                                 | 1        | 7.14%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 7.14%   |
| Intel Ethernet Connection (14) I219-LM                            | 1        | 7.14%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 7.14%   |
| Broadcom Limited NetXtreme II BCM5709 Gigabit Ethernet            | 1        | 7.14%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 2        | 100%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model               | Desktops | Percent |
|---------------------|----------|---------|
| Intel Wireless 8260 | 1        | 50%     |
| Intel Wi-Fi 6 AX200 | 1        | 50%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 4        | 44.44%  |
| Realtek Semiconductor | 3        | 33.33%  |
| Broadcom Limited      | 1        | 11.11%  |
| Broadcom              | 1        | 11.11%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3        | 25%     |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 8.33%   |
| Intel I350 Gigabit Network Connection                             | 1        | 8.33%   |
| Intel I210 Gigabit Network Connection                             | 1        | 8.33%   |
| Intel Ethernet Controller I225-V                                  | 1        | 8.33%   |
| Intel Ethernet Connection I219-LM                                 | 1        | 8.33%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 8.33%   |
| Intel Ethernet Connection (14) I219-LM                            | 1        | 8.33%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 8.33%   |
| Broadcom Limited NetXtreme II BCM5709 Gigabit Ethernet            | 1        | 8.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 7        | 77.78%  |
| WiFi     | 2        | 22.22%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 5        | 71.43%  |
| WiFi     | 2        | 28.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 4        | 57.14%  |
| 5     | 1        | 14.29%  |
| 4     | 1        | 14.29%  |
| 1     | 1        | 14.29%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 5        | 71.43%  |
| Yes  | 2        | 28.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 2        | 66.67%  |
| ASUSTek Computer | 1        | 33.33%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Intel Bluetooth wireless interface | 1        | 33.33%  |
| Intel AX200 Bluetooth              | 1        | 33.33%  |
| ASUS Broadcom BCM20702A0 Bluetooth | 1        | 33.33%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Intel                | 5        | 45.45%  |
| AMD                  | 3        | 27.27%  |
| Nvidia               | 1        | 9.09%   |
| Giga-Byte Technology | 1        | 9.09%   |
| Apple                | 1        | 9.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Nvidia GP104 High Definition Audio Controller                       | 1        | 7.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1        | 7.69%   |
| Intel Tiger Lake-H HD Audio Controller                              | 1        | 7.69%   |
| Intel Comet Lake PCH-V cAVS                                         | 1        | 7.69%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                    | 1        | 7.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 1        | 7.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 1        | 7.69%   |
| Giga-Byte Technology USB Audio                                      | 1        | 7.69%   |
| Apple USB-C to 3.5mm Headphone Jack Adapter                         | 1        | 7.69%   |
| AMD SBx00 Azalia (Intel HDA)                                        | 1        | 7.69%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]              | 1        | 7.69%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 1        | 7.69%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]        | 1        | 7.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Crucial           | 2        | 40%     |
| Unknown           | 1        | 20%     |
| Micron Technology | 1        | 20%     |
| Kingston          | 1        | 20%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM 1600MT/s                     | 1        | 20%     |
| Micron RAM 9ASF2G72AZ-3G2B1 16GB DIMM DDR4 3200MT/s      | 1        | 20%     |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s  | 1        | 20%     |
| Crucial RAM CT8G4DFRA32A.C4FE 8192MB DIMM DDR4 3200MT/s  | 1        | 20%     |
| Crucial RAM CT102464BA160B.C16 8192MB DIMM DDR3 1600MT/s | 1        | 20%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 3        | 60%     |
| DDR3    | 1        | 20%     |
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


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 4        | 80%     |
| 16384 | 1        | 20%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 2        | 40%     |
| 1600  | 2        | 40%     |
| 3600  | 1        | 20%     |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Creative Technology | 1        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Creative Live! Cam Chat HD [VF0700] | 1        | 100%    |

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
| 0     | 4        | 57.14%  |
| 1     | 2        | 28.57%  |
| 5     | 1        | 14.29%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 2        | 40%     |
| Storage/ide   | 1        | 20%     |
| Sound         | 1        | 20%     |
| Net/ethernet  | 1        | 20%     |

