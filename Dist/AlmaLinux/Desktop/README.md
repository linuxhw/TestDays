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

Total: 25

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | Z690 GAMING X DDR4          | [21ce876854](https://linux-hardware.org/?probe=21ce876854) | Feb 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | [602482d070](https://linux-hardware.org/?probe=602482d070) | Feb 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | [af3cf25119](https://linux-hardware.org/?probe=af3cf25119) | Jan 31, 2023 |
| ASRockRack    | X470D4U2-2T                 | [ec76a40223](https://linux-hardware.org/?probe=ec76a40223) | Jan 30, 2023 |
| ASRock        | B450M Pro4 R2.0             | [e4289105c5](https://linux-hardware.org/?probe=e4289105c5) | Jan 30, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [ee36c9d395](https://linux-hardware.org/?probe=ee36c9d395) | Jan 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | [6b99585bc0](https://linux-hardware.org/?probe=6b99585bc0) | Jan 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | [b9f3d19faa](https://linux-hardware.org/?probe=b9f3d19faa) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [df1811bf5d](https://linux-hardware.org/?probe=df1811bf5d) | Jan 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | [71a9255bc8](https://linux-hardware.org/?probe=71a9255bc8) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | [e327d1dea4](https://linux-hardware.org/?probe=e327d1dea4) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | [f62d0d9183](https://linux-hardware.org/?probe=f62d0d9183) | Jan 24, 2023 |
| ASRock        | B450M Pro4 R2.0             | [ed6204876e](https://linux-hardware.org/?probe=ed6204876e) | Jan 22, 2023 |
| HP            | 158A                        | [c0e1c9b6e6](https://linux-hardware.org/?probe=c0e1c9b6e6) | Jan 09, 2023 |
| MSI           | A88X-G45 GAMING             | [891e0757ed](https://linux-hardware.org/?probe=891e0757ed) | Dec 31, 2022 |
| MSI           | A88X-G45 GAMING             | [bdb45edaad](https://linux-hardware.org/?probe=bdb45edaad) | Dec 31, 2022 |
| Optimized ... | KVM                         | [d62625a751](https://linux-hardware.org/?probe=d62625a751) | Dec 13, 2022 |
| Gigabyte      | H81M-D2V                    | [6035f1ee45](https://linux-hardware.org/?probe=6035f1ee45) | Nov 11, 2022 |
| ASUSTek       | Q170M2                      | [c62954095d](https://linux-hardware.org/?probe=c62954095d) | Nov 11, 2022 |
| Lenovo        | 1052 NOK                    | [28cd1416fe](https://linux-hardware.org/?probe=28cd1416fe) | Sep 22, 2022 |
| ASRock        | B460 Phantom Gaming 4       | [0dc125da55](https://linux-hardware.org/?probe=0dc125da55) | Jul 05, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | [a517886d4d](https://linux-hardware.org/?probe=a517886d4d) | Feb 10, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [e5a30a171e](https://linux-hardware.org/?probe=e5a30a171e) | Jun 08, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [043878564d](https://linux-hardware.org/?probe=043878564d) | Jun 08, 2021 |
| HP            | 0AE8h C                     | [b7fd559b13](https://linux-hardware.org/?probe=b7fd559b13) | Mar 24, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| AlmaLinux 9.1 | 5        | 33.33%  |
| AlmaLinux 9.0 | 3        | 20%     |
| AlmaLinux 8.7 | 3        | 20%     |
| AlmaLinux 8.6 | 1        | 6.67%   |
| AlmaLinux 8.5 | 1        | 6.67%   |
| AlmaLinux 8.4 | 1        | 6.67%   |
| AlmaLinux 8.3 | 1        | 6.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| AlmaLinux | 15       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.14.0-162.6.1.el9_1.x86_64  | 3        | 20%     |
| 4.18.0-425.3.1.el8.x86_64    | 3        | 20%     |
| 5.14.0-70.30.1.el9_0.x86_64  | 2        | 13.33%  |
| 5.14.0-162.12.1.el9_1.x86_64 | 2        | 13.33%  |
| 5.14.0-70.22.1.el9_0.x86_64  | 1        | 6.67%   |
| 4.18.0-372.9.1.el8.x86_64    | 1        | 6.67%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 1        | 6.67%   |
| 4.18.0-305.el8.x86_64        | 1        | 6.67%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 1        | 6.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14.0  | 8        | 53.33%  |
| 4.18.0  | 7        | 46.67%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14    | 8        | 53.33%  |
| 4.18    | 7        | 46.67%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 15       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GNOME   | 9        | 60%     |
| Unknown | 4        | 26.67%  |
| XFCE    | 1        | 6.67%   |
| KDE5    | 1        | 6.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 6        | 40%     |
| Wayland | 6        | 40%     |
| Tty     | 2        | 13.33%  |
| Unknown | 1        | 6.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 13       | 86.67%  |
| GDM     | 2        | 13.33%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 6        | 37.5%   |
| en_CA   | 2        | 12.5%   |
| de_DE   | 2        | 12.5%   |
| uk_UA   | 1        | 6.25%   |
| ru_UA   | 1        | 6.25%   |
| ru_RU   | 1        | 6.25%   |
| en_GB   | 1        | 6.25%   |
| da_DK   | 1        | 6.25%   |
| Unknown | 1        | 6.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 9        | 60%     |
| BIOS | 6        | 40%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 11       | 73.33%  |
| Ext4 | 4        | 26.67%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 7        | 46.67%  |
| GPT     | 6        | 40%     |
| MBR     | 2        | 13.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 66.67%  |
| Yes       | 5        | 33.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 66.67%  |
| Yes       | 5        | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 3        | 20%     |
| ASUSTek Computer    | 3        | 20%     |
| Lenovo              | 2        | 13.33%  |
| Hewlett-Packard     | 2        | 13.33%  |
| ASRock              | 2        | 13.33%  |
| Optimized Hosting   | 1        | 6.67%   |
| MSI                 | 1        | 6.67%   |
| ASRockRack          | 1        | 6.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Optimized Hosting KVM               | 1        | 6.67%   |
| MSI MS-7900                         | 1        | 6.67%   |
| Lenovo ThinkStation P350 30E6S20S00 | 1        | 6.67%   |
| Lenovo H520S 10093                  | 1        | 6.67%   |
| HP Z620 Workstation                 | 1        | 6.67%   |
| HP Z600 Workstation                 | 1        | 6.67%   |
| Gigabyte Z690 GAMING X DDR4         | 1        | 6.67%   |
| Gigabyte Z590 AORUS PRO AX          | 1        | 6.67%   |
| Gigabyte H81M-D2V                   | 1        | 6.67%   |
| ASUS TUF Gaming B450-PLUS II        | 1        | 6.67%   |
| ASUS Q170M2                         | 1        | 6.67%   |
| ASUS M5A78L-M/USB3                  | 1        | 6.67%   |
| ASRockRack X470D4U2-2T              | 1        | 6.67%   |
| ASRock B460 Phantom Gaming 4        | 1        | 6.67%   |
| ASRock B450M Pro4 R2.0              | 1        | 6.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Optimized Hosting KVM  | 1        | 6.67%   |
| MSI MS-7900            | 1        | 6.67%   |
| Lenovo ThinkStation    | 1        | 6.67%   |
| Lenovo H520S           | 1        | 6.67%   |
| HP Z620                | 1        | 6.67%   |
| HP Z600                | 1        | 6.67%   |
| Gigabyte Z690          | 1        | 6.67%   |
| Gigabyte Z590          | 1        | 6.67%   |
| Gigabyte H81M-D2V      | 1        | 6.67%   |
| ASUS TUF               | 1        | 6.67%   |
| ASUS Q170M2            | 1        | 6.67%   |
| ASUS M5A78L-M          | 1        | 6.67%   |
| ASRockRack X470D4U2-2T | 1        | 6.67%   |
| ASRock B460            | 1        | 6.67%   |
| ASRock B450M           | 1        | 6.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 4        | 26.67%  |
| 2020 | 3        | 20%     |
| 2022 | 1        | 6.67%   |
| 2021 | 1        | 6.67%   |
| 2018 | 1        | 6.67%   |
| 2015 | 1        | 6.67%   |
| 2014 | 1        | 6.67%   |
| 2013 | 1        | 6.67%   |
| 2011 | 1        | 6.67%   |
| 2009 | 1        | 6.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 15       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 14       | 93.33%  |
| Enabled  | 1        | 6.67%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 15       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 4        | 26.67%  |
| 8.01-16.0   | 4        | 26.67%  |
| 64.01-256.0 | 3        | 20%     |
| 32.01-64.0  | 2        | 13.33%  |
| 24.01-32.0  | 1        | 6.67%   |
| 16.01-24.0  | 1        | 6.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 5        | 33.33%  |
| 3.01-4.0   | 4        | 26.67%  |
| 1.01-2.0   | 2        | 13.33%  |
| 4.01-8.0   | 1        | 6.67%   |
| 32.01-64.0 | 1        | 6.67%   |
| 8.01-16.0  | 1        | 6.67%   |
| 0.51-1.0   | 1        | 6.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 4      | 4        | 26.67%  |
| 2      | 4        | 26.67%  |
| 1      | 4        | 26.67%  |
| 3      | 2        | 13.33%  |
| 5      | 1        | 6.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 66.67%  |
| Yes       | 5        | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 14       | 93.33%  |
| No        | 1        | 6.67%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 66.67%  |
| Yes       | 5        | 33.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 60%     |
| Yes       | 6        | 40%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Canada      | 3        | 20%     |
| USA         | 2        | 13.33%  |
| Ukraine     | 2        | 13.33%  |
| Russia      | 2        | 13.33%  |
| Switzerland | 1        | 6.67%   |
| Netherlands | 1        | 6.67%   |
| Kazakhstan  | 1        | 6.67%   |
| Greenland   | 1        | 6.67%   |
| Germany     | 1        | 6.67%   |
| France      | 1        | 6.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Desktops | Percent |
|--------------|----------|---------|
| Zaporizhzhia | 1        | 6.67%   |
| Strasbourg   | 1        | 6.67%   |
| Stadtilm     | 1        | 6.67%   |
| St. Paul     | 1        | 6.67%   |
| Shimanovsk   | 1        | 6.67%   |
| Moscow       | 1        | 6.67%   |
| Kyiv         | 1        | 6.67%   |
| Kitimat      | 1        | 6.67%   |
| Ilulissat    | 1        | 6.67%   |
| Groningen    | 1        | 6.67%   |
| Bloomington  | 1        | 6.67%   |
| Bellevue     | 1        | 6.67%   |
| Beauharnois  | 1        | 6.67%   |
| Basel        | 1        | 6.67%   |
| Almaty       | 1        | 6.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 6        | 11     | 23.08%  |
| WDC                         | 4        | 6      | 15.38%  |
| Samsung Electronics         | 3        | 5      | 11.54%  |
| Kingston                    | 2        | 3      | 7.69%   |
| Crucial                     | 2        | 4      | 7.69%   |
| Toshiba                     | 1        | 1      | 3.85%   |
| Team                        | 1        | 1      | 3.85%   |
| SK hynix                    | 1        | 1      | 3.85%   |
| Silicon Motion              | 1        | 4      | 3.85%   |
| QEMU                        | 1        | 1      | 3.85%   |
| Netac                       | 1        | 1      | 3.85%   |
| LITEON                      | 1        | 1      | 3.85%   |
| Kingston Technology Company | 1        | 1      | 3.85%   |
| Hewlett-Packard             | 1        | 1      | 3.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB                          | 2        | 5.71%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                    | 1        | 2.86%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                    | 1        | 2.86%   |
| WDC WD20EARS-00J2GB0 2TB                          | 1        | 2.86%   |
| Toshiba DT01ACA100 1TB                            | 1        | 2.86%   |
| Team T253X1480G 480GB SSD                         | 1        | 2.86%   |
| SK hynix SH920 2.5 7MM 256GB SSD                  | 1        | 2.86%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 1TB | 1        | 2.86%   |
| Seagate ST4000NM000A 00MX141 00MX141LEN 4TB       | 1        | 2.86%   |
| Seagate ST4000NC001-1FS168 4TB                    | 1        | 2.86%   |
| Seagate ST4000DM000-1F2168 4TB                    | 1        | 2.86%   |
| Seagate ST31000528AS 1TB                          | 1        | 2.86%   |
| Seagate ST3000DM001-1CH166 3TB                    | 1        | 2.86%   |
| Seagate ST2000DM001-1ER164 2TB                    | 1        | 2.86%   |
| Seagate ST2000DL003-9VT166 2TB                    | 1        | 2.86%   |
| Seagate ST1000NM0033-9ZM173 1TB                   | 1        | 2.86%   |
| Seagate ST1000DM003-9YN162 1TB                    | 1        | 2.86%   |
| Seagate ST10000NM0478-2H7100 10TB                 | 1        | 2.86%   |
| Seagate Expansion 240GB                           | 1        | 2.86%   |
| Samsung SSD 980 1TB                               | 1        | 2.86%   |
| Samsung PSSD T7 Touch 1TB                         | 1        | 2.86%   |
| Samsung MZVL22T0HBLB-00BL7 2TB                    | 1        | 2.86%   |
| Samsung MZ7LN256HAJQ-000L2 256GB SSD              | 1        | 2.86%   |
| QEMU HARDDISK                                     | 1        | 2.86%   |
| Netac SSD 512GB                                   | 1        | 2.86%   |
| LITEON CV1-8B256-HP 256GB SSD                     | 1        | 2.86%   |
| Kingston Company A2000 NVMe SSD 1TB               | 1        | 2.86%   |
| Kingston SV300S37A240G 240GB SSD                  | 1        | 2.86%   |
| Kingston SKC3000S1024G 1TB                        | 1        | 2.86%   |
| Kingston SA400S37480G 480GB SSD                   | 1        | 2.86%   |
| HP SSD S700 500GB                                 | 1        | 2.86%   |
| Crucial CT480BX500SSD1 480GB                      | 1        | 2.86%   |
| Crucial CT240BX500SSD1 240GB                      | 1        | 2.86%   |
| Crucial CT1000P5PSSD8 1TB                         | 1        | 2.86%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 6        | 11     | 54.55%  |
| WDC     | 3        | 3      | 27.27%  |
| Toshiba | 1        | 1      | 9.09%   |
| QEMU    | 1        | 1      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 2      | 18.18%  |
| Kingston            | 2        | 2      | 18.18%  |
| WDC                 | 1        | 3      | 9.09%   |
| Team                | 1        | 1      | 9.09%   |
| SK hynix            | 1        | 1      | 9.09%   |
| Netac               | 1        | 1      | 9.09%   |
| LITEON              | 1        | 1      | 9.09%   |
| Hewlett-Packard     | 1        | 1      | 9.09%   |
| Crucial             | 1        | 2      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 10       | 14     | 40%     |
| HDD  | 9        | 16     | 36%     |
| NVMe | 6        | 11     | 24%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 14       | 28     | 63.64%  |
| NVMe | 6        | 11     | 27.27%  |
| SAS  | 2        | 2      | 9.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 9        | 11     | 37.5%   |
| 0.51-1.0   | 8        | 11     | 33.33%  |
| 3.01-4.0   | 3        | 3      | 12.5%   |
| 1.01-2.0   | 2        | 3      | 8.33%   |
| 2.01-3.0   | 1        | 1      | 4.17%   |
| 4.01-10.0  | 1        | 1      | 4.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 4        | 26.67%  |
| 501-1000       | 3        | 20%     |
| More than 3000 | 2        | 13.33%  |
| Unknown        | 2        | 13.33%  |
| 251-500        | 1        | 6.67%   |
| 2001-3000      | 1        | 6.67%   |
| 1001-2000      | 1        | 6.67%   |
| 1-20           | 1        | 6.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 4        | 26.67%  |
| 101-250        | 3        | 20%     |
| 251-500        | 2        | 13.33%  |
| Unknown        | 2        | 13.33%  |
| More than 3000 | 1        | 6.67%   |
| 21-50          | 1        | 6.67%   |
| 2001-3000      | 1        | 6.67%   |
| 51-100         | 1        | 6.67%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| WDC WD20EARS-00J2GB0 2TB         | 1        | 1      | 50%     |
| SK hynix SH920 2.5 7MM 256GB SSD | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| WDC      | 1        | 1      | 50%     |
| SK hynix | 1        | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 1        | 1      | 50%     |
| HDD  | 1        | 1      | 50%     |

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
| Detected | 10       | 20     | 52.63%  |
| Works    | 7        | 19     | 36.84%  |
| Malfunc  | 2        | 2      | 10.53%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 10       | 45.45%  |
| AMD                         | 5        | 22.73%  |
| Samsung Electronics         | 2        | 9.09%   |
| Kingston Technology Company | 2        | 9.09%   |
| Silicon Motion              | 1        | 4.55%   |
| Red Hat                     | 1        | 4.55%   |
| Micron/Crucial Technology   | 1        | 4.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 11.11%  |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 7.41%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 2        | 7.41%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 3.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 3.7%    |
| Samsung NVMe SSD Controller 980                                                         | 1        | 3.7%    |
| Red Hat Virtio SCSI                                                                     | 1        | 3.7%    |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                                    | 1        | 3.7%    |
| Kingston Company Company Non-Volatile memory controller                                 | 1        | 3.7%    |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 3.7%    |
| Intel SATA Controller [RAID mode]                                                       | 1        | 3.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 3.7%    |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 3.7%    |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 3.7%    |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 3.7%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 3.7%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 3.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1        | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 3.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 3.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 3.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 3.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 12       | 48%     |
| NVMe | 6        | 24%     |
| IDE  | 3        | 12%     |
| RAID | 2        | 8%      |
| SAS  | 1        | 4%      |
| SCSI | 1        | 4%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 9        | 60%     |
| AMD    | 6        | 40%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Xeon W-1350 @ 3.30GHz                     | 1        | 6.67%   |
| Intel Xeon CPU X5550 @ 2.67GHz                  | 1        | 6.67%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz             | 1        | 6.67%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1        | 6.67%   |
| Intel Core i5-10400F CPU @ 2.90GHz              | 1        | 6.67%   |
| Intel Core i3-4130 CPU @ 3.40GHz                | 1        | 6.67%   |
| Intel Core i3-2130 CPU @ 3.40GHz                | 1        | 6.67%   |
| Intel 12th Gen Core i7-12700KF                  | 1        | 6.67%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz          | 1        | 6.67%   |
| AMD Ryzen 9 3950X 16-Core Processor             | 1        | 6.67%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 1        | 6.67%   |
| AMD Ryzen 5 3600 6-Core Processor               | 1        | 6.67%   |
| AMD FX-8350 Eight-Core Processor                | 1        | 6.67%   |
| AMD EPYC-Rome Processor                         | 1        | 6.67%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1        | 6.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| Intel Xeon    | 3        | 20%     |
| Other         | 2        | 13.33%  |
| Intel Core i3 | 2        | 13.33%  |
| AMD Ryzen 9   | 2        | 13.33%  |
| Intel Core i7 | 1        | 6.67%   |
| Intel Core i5 | 1        | 6.67%   |
| AMD Ryzen 5   | 1        | 6.67%   |
| AMD FX        | 1        | 6.67%   |
| AMD EPYC      | 1        | 6.67%   |
| AMD A10       | 1        | 6.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 4        | 26.67%  |
| 4      | 4        | 26.67%  |
| 2      | 3        | 20%     |
| 16     | 2        | 13.33%  |
| 12     | 2        | 13.33%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 13       | 86.67%  |
| 4      | 1        | 6.67%   |
| 2      | 1        | 6.67%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 14       | 93.33%  |
| 1      | 1        | 6.67%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 15       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 3        | 18.75%  |
| 0xa0671    | 2        | 12.5%   |
| 0x08701021 | 2        | 12.5%   |
| 0xa0655    | 1        | 6.25%   |
| 0x906e9    | 1        | 6.25%   |
| 0x90672    | 1        | 6.25%   |
| 0x306e4    | 1        | 6.25%   |
| 0x306c3    | 1        | 6.25%   |
| 0x206a7    | 1        | 6.25%   |
| 0x106a5    | 1        | 6.25%   |
| 0x06003106 | 1        | 6.25%   |
| 0x06000852 | 1        | 6.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 4        | 26.67%  |
| Icelake          | 2        | 13.33%  |
| Steamroller      | 1        | 6.67%   |
| SandyBridge      | 1        | 6.67%   |
| Piledriver       | 1        | 6.67%   |
| Nehalem          | 1        | 6.67%   |
| KabyLake         | 1        | 6.67%   |
| IvyBridge        | 1        | 6.67%   |
| Haswell          | 1        | 6.67%   |
| CometLake        | 1        | 6.67%   |
| Alderlake Hybrid | 1        | 6.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| AMD               | 5        | 33.33%  |
| Nvidia            | 4        | 26.67%  |
| Intel             | 4        | 26.67%  |
| Red Hat           | 1        | 6.67%   |
| ASPEED Technology | 1        | 6.67%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Nvidia GA106 [Geforce RTX 3050]                                           | 2        | 13.33%  |
| Red Hat QXL paravirtual graphic card                                      | 1        | 6.67%   |
| Nvidia GP104 [GeForce GTX 1080]                                           | 1        | 6.67%   |
| Nvidia GM107GL [Quadro K2200]                                             | 1        | 6.67%   |
| Intel RocketLake-S GT1 [UHD Graphics P750]                                | 1        | 6.67%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                 | 1        | 6.67%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1        | 6.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1        | 6.67%   |
| ASPEED Technology ASPEED Graphics Family                                  | 1        | 6.67%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                  | 1        | 6.67%   |
| AMD RS780L [Radeon 3000]                                                  | 1        | 6.67%   |
| AMD Kaveri [Radeon R7 Graphics]                                           | 1        | 6.67%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 1        | 6.67%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]       | 1        | 6.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x AMD     | 5        | 33.33%  |
| 1 x Nvidia  | 4        | 26.67%  |
| 1 x Intel   | 4        | 26.67%  |
| 1 x Red Hat | 1        | 6.67%   |
| 1 x ASPEED  | 1        | 6.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 11       | 73.33%  |
| Unknown     | 3        | 20%     |
| Proprietary | 1        | 6.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 8        | 53.33%  |
| 7.01-8.0   | 3        | 20%     |
| 3.01-4.0   | 1        | 6.67%   |
| 1.01-2.0   | 1        | 6.67%   |
| 0.51-1.0   | 1        | 6.67%   |
| 0.01-0.5   | 1        | 6.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 2        | 15.38%  |
| Goldstar            | 2        | 15.38%  |
| ViewSonic           | 1        | 7.69%   |
| TopView             | 1        | 7.69%   |
| STD                 | 1        | 7.69%   |
| Philips             | 1        | 7.69%   |
| Medion              | 1        | 7.69%   |
| Lenovo              | 1        | 7.69%   |
| Dell                | 1        | 7.69%   |
| BenQ                | 1        | 7.69%   |
| AOC                 | 1        | 7.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| ViewSonic VX2233wm-1 VSC1D22 1920x1080 477x268mm 21.5-inch           | 1        | 7.14%   |
| TopView HD TV TOPC37E 1920x1080 700x390mm 31.5-inch                  | 1        | 7.14%   |
| STD HDMI TV STD00C7 1680x1050 698x392mm 31.5-inch                    | 1        | 7.14%   |
| Samsung Electronics SyncMaster SAM021B 1400x1050 408x300mm 19.9-inch | 1        | 7.14%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch    | 1        | 7.14%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch   | 1        | 7.14%   |
| Philips 19B PHL0879 1280x1024 376x301mm 19.0-inch                    | 1        | 7.14%   |
| Medion MD7212AS MED4971 1280x1024 359x287mm 18.1-inch                | 1        | 7.14%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                 | 1        | 7.14%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch          | 1        | 7.14%   |
| Goldstar 22EA53 GSM59A6 1920x1080 477x268mm 21.5-inch                | 1        | 7.14%   |
| Dell 1905FP DEL400C 1280x1024 376x301mm 19.0-inch                    | 1        | 7.14%   |
| BenQ GW2480 BNQ78E7 1920x1080 530x300mm 24.0-inch                    | 1        | 7.14%   |
| AOC 2330V AOC2330 1920x1080 476x268mm 21.5-inch                      | 1        | 7.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 8        | 57.14%  |
| 1280x1024 (SXGA) | 3        | 21.43%  |
| 2560x1440 (QHD)  | 1        | 7.14%   |
| 2560x1080        | 1        | 7.14%   |
| 1400x1050        | 1        | 7.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 21     | 3        | 21.43%  |
| 31     | 2        | 14.29%  |
| 27     | 2        | 14.29%  |
| 24     | 2        | 14.29%  |
| 19     | 2        | 14.29%  |
| 34     | 1        | 7.14%   |
| 20     | 1        | 7.14%   |
| 18     | 1        | 7.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 4        | 28.57%  |
| 401-500     | 4        | 28.57%  |
| 351-400     | 3        | 21.43%  |
| 601-700     | 2        | 14.29%  |
| 701-800     | 1        | 7.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 9        | 64.29%  |
| 5/4   | 2        | 14.29%  |
| 6/5   | 1        | 7.14%   |
| 4/3   | 1        | 7.14%   |
| 21/9  | 1        | 7.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 7        | 50%     |
| 351-500        | 3        | 21.43%  |
| 301-350        | 2        | 14.29%  |
| 201-250        | 2        | 14.29%  |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 8        | 66.67%  |
| 101-120 | 3        | 25%     |
| 121-160 | 1        | 8.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 6        | 40%     |
| 2     | 5        | 33.33%  |
| 0     | 4        | 26.67%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 36.84%  |
| Intel                 | 6        | 31.58%  |
| Qualcomm Atheros      | 2        | 10.53%  |
| TP-Link               | 1        | 5.26%   |
| Ralink                | 1        | 5.26%   |
| Broadcom Limited      | 1        | 5.26%   |
| Broadcom              | 1        | 5.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6        | 23.08%  |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 3.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 3.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 3.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 3.85%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1        | 3.85%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 3.85%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 3.85%   |
| Intel Wireless 8260                                               | 1        | 3.85%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 3.85%   |
| Intel I350 Gigabit Network Connection                             | 1        | 3.85%   |
| Intel I210 Gigabit Network Connection                             | 1        | 3.85%   |
| Intel Ethernet Controller X550                                    | 1        | 3.85%   |
| Intel Ethernet Controller I225-V                                  | 1        | 3.85%   |
| Intel Ethernet Connection I219-LM                                 | 1        | 3.85%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 3.85%   |
| Intel Ethernet Connection (14) I219-LM                            | 1        | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 3.85%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 3.85%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 3.85%   |
| Broadcom Limited NetXtreme II BCM5709 Gigabit Ethernet            | 1        | 3.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 2        | 40%     |
| TP-Link          | 1        | 20%     |
| Ralink           | 1        | 20%     |
| Qualcomm Atheros | 1        | 20%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| TP-Link Archer T3U [Realtek RTL8812BU]           | 1        | 20%     |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe        | 1        | 20%     |
| Qualcomm Atheros AR93xx Wireless Network Adapter | 1        | 20%     |
| Intel Wireless 8260                              | 1        | 20%     |
| Intel Wi-Fi 6 AX200                              | 1        | 20%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 43.75%  |
| Intel                 | 6        | 37.5%   |
| Qualcomm Atheros      | 1        | 6.25%   |
| Broadcom Limited      | 1        | 6.25%   |
| Broadcom              | 1        | 6.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6        | 28.57%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 4.76%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 4.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 4.76%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 4.76%   |
| Intel I350 Gigabit Network Connection                             | 1        | 4.76%   |
| Intel I210 Gigabit Network Connection                             | 1        | 4.76%   |
| Intel Ethernet Controller X550                                    | 1        | 4.76%   |
| Intel Ethernet Controller I225-V                                  | 1        | 4.76%   |
| Intel Ethernet Connection I219-LM                                 | 1        | 4.76%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 4.76%   |
| Intel Ethernet Connection (14) I219-LM                            | 1        | 4.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 4.76%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 4.76%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 4.76%   |
| Broadcom Limited NetXtreme II BCM5709 Gigabit Ethernet            | 1        | 4.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 14       | 73.68%  |
| WiFi     | 5        | 26.32%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 12       | 85.71%  |
| WiFi     | 2        | 14.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 9        | 60%     |
| 1     | 3        | 20%     |
| 5     | 1        | 6.67%   |
| 4     | 1        | 6.67%   |
| 0     | 1        | 6.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 12       | 80%     |
| Yes  | 3        | 20%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 2        | 33.33%  |
| Broadcom                | 2        | 33.33%  |
| Cambridge Silicon Radio | 1        | 16.67%  |
| ASUSTek Computer        | 1        | 16.67%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 1        | 16.67%  |
| Intel AX200 Bluetooth                               | 1        | 16.67%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 16.67%  |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 16.67%  |
| Broadcom BCM2045 Bluetooth                          | 1        | 16.67%  |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 16.67%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Intel                | 8        | 38.1%   |
| AMD                  | 7        | 33.33%  |
| Nvidia               | 4        | 19.05%  |
| Giga-Byte Technology | 1        | 4.76%   |
| Apple                | 1        | 4.76%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 12%     |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 8%      |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 4%      |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 4%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 4%      |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 4%      |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 4%      |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 4%      |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 4%      |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 4%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1        | 4%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 4%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 4%      |
| Giga-Byte Technology USB Audio                                             | 1        | 4%      |
| Apple USB-C to 3.5mm Headphone Jack Adapter                                | 1        | 4%      |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 1        | 4%      |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 4%      |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 1        | 4%      |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1        | 4%      |
| AMD FCH Azalia Controller                                                  | 1        | 4%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 4%      |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 4%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 3        | 33.33%  |
| Crucial             | 2        | 22.22%  |
| Unknown             | 1        | 11.11%  |
| Samsung Electronics | 1        | 11.11%  |
| QEMU                | 1        | 11.11%  |
| Micron Technology   | 1        | 11.11%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM 1600MT/s                    | 1        | 11.11%  |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 3466MT/s    | 1        | 11.11%  |
| QEMU RAM Module 8GB DIMM RAM                            | 1        | 11.11%  |
| Micron RAM 9ASF2G72AZ-3G2B1 16GB DIMM DDR4 3200MT/s     | 1        | 11.11%  |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s    | 1        | 11.11%  |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s   | 1        | 11.11%  |
| Kingston RAM ACR256X64D3U1333C9 2GB DIMM DDR3 1333MT/s  | 1        | 11.11%  |
| Crucial RAM CT8G4DFRA32A.C4FE 8192MB DIMM DDR4 3200MT/s | 1        | 11.11%  |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s   | 1        | 11.11%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 5        | 55.56%  |
| DDR3    | 2        | 22.22%  |
| RAM     | 1        | 11.11%  |
| Unknown | 1        | 11.11%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 9        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 5        | 55.56%  |
| 16384 | 2        | 22.22%  |
| 32768 | 1        | 11.11%  |
| 2048  | 1        | 11.11%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 3        | 33.33%  |
| 1600    | 2        | 22.22%  |
| 3600    | 1        | 11.11%  |
| 3466    | 1        | 11.11%  |
| 1333    | 1        | 11.11%  |
| Unknown | 1        | 11.11%  |

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
| Microdia            | 1        | 33.33%  |
| Logitech            | 1        | 33.33%  |
| Creative Technology | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Microdia USB 2.0 Camera             | 1        | 33.33%  |
| Logitech Webcam B500                | 1        | 33.33%  |
| Creative Live! Cam Chat HD [VF0700] | 1        | 33.33%  |

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
| 0     | 11       | 73.33%  |
| 1     | 3        | 20%     |
| 5     | 1        | 6.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 2        | 33.33%  |
| Storage/ide   | 1        | 16.67%  |
| Sound         | 1        | 16.67%  |
| Net/wireless  | 1        | 16.67%  |
| Net/ethernet  | 1        | 16.67%  |

