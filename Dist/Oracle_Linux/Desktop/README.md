Oracle Linux - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Oracle Linux.

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

Total: 26

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock   | B760M-STX                   | [1648b583d6](https://linux-hardware.org/?probe=1648b583d6) | Jan 10, 2024 |
| ASUSTek  | G15CF                       | [c2b88beb62](https://linux-hardware.org/?probe=c2b88beb62) | Dec 02, 2023 |
| ASRock   | B550M Steel Legend          | [9cb8304240](https://linux-hardware.org/?probe=9cb8304240) | Nov 24, 2023 |
| ASRock   | B550M Steel Legend          | [8cfb18380e](https://linux-hardware.org/?probe=8cfb18380e) | Nov 24, 2023 |
| ASUSTek  | SABERTOOTH 990FX R3.0       | [b63af8760f](https://linux-hardware.org/?probe=b63af8760f) | Oct 03, 2023 |
| ASUSTek  | SABERTOOTH 990FX R3.0       | [5ac9728fe0](https://linux-hardware.org/?probe=5ac9728fe0) | Oct 01, 2023 |
| Cisco    | WAVE-694-K9 A0              | [26b9c3adb7](https://linux-hardware.org/?probe=26b9c3adb7) | Jun 27, 2023 |
| ASRock   | Z68 Extreme3 Gen3           | [7849965aa1](https://linux-hardware.org/?probe=7849965aa1) | Jun 11, 2023 |
| HP       | 1589                        | [c905464231](https://linux-hardware.org/?probe=c905464231) | May 11, 2023 |
| Gigabyte | H81M-S2PV                   | [ac856abadc](https://linux-hardware.org/?probe=ac856abadc) | Mar 21, 2023 |
| ASUSTek  | PRIME B560M-A AC            | [d4cc718e46](https://linux-hardware.org/?probe=d4cc718e46) | Nov 29, 2022 |
| Dell     | 0DC48C A02                  | [9292e820c5](https://linux-hardware.org/?probe=9292e820c5) | Sep 27, 2022 |
| ASUSTek  | H81M-A                      | [a37e952875](https://linux-hardware.org/?probe=a37e952875) | Sep 04, 2022 |
| Dell     | 073Y7Y A00                  | [3bed97b23e](https://linux-hardware.org/?probe=3bed97b23e) | Jul 21, 2022 |
| MSI      | Z77A-G43                    | [909e3e3c2e](https://linux-hardware.org/?probe=909e3e3c2e) | Jun 29, 2022 |
| ASUSTek  | P8H67                       | [b194dad4cf](https://linux-hardware.org/?probe=b194dad4cf) | Jun 25, 2022 |
| Dell     | 0C522T A03                  | [3dc84dc8ff](https://linux-hardware.org/?probe=3dc84dc8ff) | Mar 24, 2022 |
| Gigabyte | Z490 AORUS ELITE AC         | [978ae6f2cb](https://linux-hardware.org/?probe=978ae6f2cb) | May 02, 2021 |
| Gigabyte | X99-Designare EX-CF         | [5195396549](https://linux-hardware.org/?probe=5195396549) | Mar 06, 2021 |
| ASUSTek  | G11CD                       | [13961e12a8](https://linux-hardware.org/?probe=13961e12a8) | Feb 01, 2021 |
| HP       | 158B                        | [5e6b9531d7](https://linux-hardware.org/?probe=5e6b9531d7) | Feb 01, 2021 |
| Dell     | PowerEdge FC630             | [bcd33a41f0](https://linux-hardware.org/?probe=bcd33a41f0) | Jan 25, 2021 |
| Gigabyte | X470 AORUS ULTRA GAMING-... | [71628a95b6](https://linux-hardware.org/?probe=71628a95b6) | Jan 13, 2021 |
| Foxconn  | 2ADA                        | [809e03aea5](https://linux-hardware.org/?probe=809e03aea5) | Dec 24, 2020 |
| ASUSTek  | G11CD                       | [d9d0f8fdf2](https://linux-hardware.org/?probe=d9d0f8fdf2) | Dec 20, 2020 |
| Dell     | 0C96W1 A01                  | [b5c14107bb](https://linux-hardware.org/?probe=b5c14107bb) | Feb 12, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Oracle Linux 8.3 | 6        | 26.09%  |
| Oracle Linux 8.6 | 4        | 17.39%  |
| Oracle Linux 9.3 | 3        | 13.04%  |
| Oracle Linux 9.2 | 3        | 13.04%  |
| Oracle Linux 8.7 | 2        | 8.7%    |
| Oracle Linux 9.0 | 1        | 4.35%   |
| Oracle Linux 8.5 | 1        | 4.35%   |
| Oracle Linux 8.4 | 1        | 4.35%   |
| Oracle Linux 7.7 | 1        | 4.35%   |
| Oracle Linux 7.4 | 1        | 4.35%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Oracle Linux | 23       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Desktops | Percent |
|------------------------------------|----------|---------|
| 5.4.17-2036.102.0.2.el8uek.x86_64  | 2        | 8.33%   |
| 5.4.17-2036.101.2.el8uek.x86_64    | 2        | 8.33%   |
| 5.4.17-2136.313.6.el8uek.x86_64    | 1        | 4.17%   |
| 5.4.17-2136.310.7.1.el8uek.x86_64  | 1        | 4.17%   |
| 5.4.17-2136.308.9.el8uek.x86_64    | 1        | 4.17%   |
| 5.4.17-2136.307.3.1.el8uek.x86_64  | 1        | 4.17%   |
| 5.4.17-2136.300.7.el8uek.x86_64    | 1        | 4.17%   |
| 5.4.17-2102.202.5.el8uek.x86_64    | 1        | 4.17%   |
| 5.4.17-2102.200.13.el8uek.x86_64   | 1        | 4.17%   |
| 5.4.17-2036.100.6.1.el8uek.x86_64  | 1        | 4.17%   |
| 5.4.11-1.el7.elrepo.x86_64         | 1        | 4.17%   |
| 5.15.0-201.135.6.el9uek.x86_64     | 1        | 4.17%   |
| 5.15.0-200.131.27.el9uek.x86_64    | 1        | 4.17%   |
| 5.15.0-200.131.27.1.el9uek.x86_64  | 1        | 4.17%   |
| 5.15.0-2.52.3.el9uek.x86_64        | 1        | 4.17%   |
| 5.15.0-105.125.6.2.2.el9uek.x86_64 | 1        | 4.17%   |
| 5.15.0-102.110.5.1.el9uek.x86_64   | 1        | 4.17%   |
| 5.15.0-101.103.2.1.el9uek.x86_64   | 1        | 4.17%   |
| 5.15.0-100.96.32.el8uek.x86_64     | 1        | 4.17%   |
| 4.18.0-372.16.1.0.2.el8_6.x86_64   | 1        | 4.17%   |
| 4.18.0-240.15.1.el8_3.x86_64       | 1        | 4.17%   |
| 3.10.0-693.11.6.el7.x86_64         | 1        | 4.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.17  | 11       | 47.83%  |
| 5.15.0  | 8        | 34.78%  |
| 4.18.0  | 2        | 8.7%    |
| 5.4.11  | 1        | 4.35%   |
| 3.10.0  | 1        | 4.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 12       | 52.17%  |
| 5.15    | 8        | 34.78%  |
| 4.18    | 2        | 8.7%    |
| 3.10    | 1        | 4.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 23       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 16       | 69.57%  |
| Unknown       | 4        | 17.39%  |
| KDE5          | 2        | 8.7%    |
| GNOME Classic | 1        | 4.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 11       | 47.83%  |
| X11     | 9        | 39.13%  |
| Unknown | 3        | 13.04%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 14       | 60.87%  |
| GDM     | 6        | 26.09%  |
| SDDM    | 2        | 8.7%    |
| TDM     | 1        | 4.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 12       | 52.17%  |
| en_GB      | 3        | 13.04%  |
| it_IT      | 2        | 8.7%    |
| ru_RU      | 1        | 4.35%   |
| pl_PL      | 1        | 4.35%   |
| en_US.UTF8 | 1        | 4.35%   |
| en_IN      | 1        | 4.35%   |
| de_DE      | 1        | 4.35%   |
| Unknown    | 1        | 4.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 12       | 52.17%  |
| EFI  | 11       | 47.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 19       | 82.61%  |
| Ext4 | 3        | 13.04%  |
| Zfs  | 1        | 4.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 11       | 47.83%  |
| GPT     | 7        | 30.43%  |
| MBR     | 5        | 21.74%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 91.3%   |
| Yes       | 2        | 8.7%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 95.65%  |
| Yes       | 1        | 4.35%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 6        | 26.09%  |
| Dell                | 5        | 21.74%  |
| Gigabyte Technology | 4        | 17.39%  |
| ASRock              | 3        | 13.04%  |
| Hewlett-Packard     | 2        | 8.7%    |
| MSI                 | 1        | 4.35%   |
| Foxconn             | 1        | 4.35%   |
| Cisco               | 1        | 4.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| MSI MS-7758                      | 1        | 4.35%   |
| HP Z820 Workstation              | 1        | 4.35%   |
| HP Z420 Workstation              | 1        | 4.35%   |
| Gigabyte Z490 AORUS ELITE AC     | 1        | 4.35%   |
| Gigabyte X99-Designare EX-CF     | 1        | 4.35%   |
| Gigabyte X470 AORUS ULTRA GAMING | 1        | 4.35%   |
| Gigabyte H81M-S2PV               | 1        | 4.35%   |
| Foxconn p6-2400el                | 1        | 4.35%   |
| Dell PowerEdge FC630             | 1        | 4.35%   |
| Dell OptiPlex 980                | 1        | 4.35%   |
| Dell OptiPlex 7090               | 1        | 4.35%   |
| Dell OptiPlex 7060               | 1        | 4.35%   |
| Dell OptiPlex 5000               | 1        | 4.35%   |
| Cisco WAVE-694-K9                | 1        | 4.35%   |
| ASUS SABERTOOTH 990FX R3.0       | 1        | 4.35%   |
| ASUS ROG STRIX G15CF_G15CF       | 1        | 4.35%   |
| ASUS PRIME B560M-A AC            | 1        | 4.35%   |
| ASUS P8H67                       | 1        | 4.35%   |
| ASUS G11CD                       | 1        | 4.35%   |
| ASUS All Series                  | 1        | 4.35%   |
| ASRock Z68 Extreme3 Gen3         | 1        | 4.35%   |
| ASRock B760M-STX                 | 1        | 4.35%   |
| ASRock B550M Steel Legend        | 1        | 4.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 4        | 17.39%  |
| MSI MS-7758            | 1        | 4.35%   |
| HP Z820                | 1        | 4.35%   |
| HP Z420                | 1        | 4.35%   |
| Gigabyte Z490          | 1        | 4.35%   |
| Gigabyte X99-Designare | 1        | 4.35%   |
| Gigabyte X470          | 1        | 4.35%   |
| Gigabyte H81M-S2PV     | 1        | 4.35%   |
| Foxconn p6-2400el      | 1        | 4.35%   |
| Dell PowerEdge         | 1        | 4.35%   |
| Cisco WAVE-694-K9      | 1        | 4.35%   |
| ASUS SABERTOOTH        | 1        | 4.35%   |
| ASUS ROG               | 1        | 4.35%   |
| ASUS PRIME             | 1        | 4.35%   |
| ASUS P8H67             | 1        | 4.35%   |
| ASUS G11CD             | 1        | 4.35%   |
| ASUS All               | 1        | 4.35%   |
| ASRock Z68             | 1        | 4.35%   |
| ASRock B760M-STX       | 1        | 4.35%   |
| ASRock B550M           | 1        | 4.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 5        | 21.74%  |
| 2018 | 3        | 13.04%  |
| 2016 | 3        | 13.04%  |
| 2022 | 2        | 8.7%    |
| 2021 | 2        | 8.7%    |
| 2020 | 2        | 8.7%    |
| 2010 | 2        | 8.7%    |
| 2023 | 1        | 4.35%   |
| 2014 | 1        | 4.35%   |
| 2013 | 1        | 4.35%   |
| 2011 | 1        | 4.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 23       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 22       | 95.65%  |
| Enabled  | 1        | 4.35%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 23       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 64.01-256.0     | 6        | 26.09%  |
| 8.01-16.0       | 5        | 21.74%  |
| 4.01-8.0        | 3        | 13.04%  |
| 32.01-64.0      | 3        | 13.04%  |
| 16.01-24.0      | 2        | 8.7%    |
| More than 256.0 | 1        | 4.35%   |
| 3.01-4.0        | 1        | 4.35%   |
| 24.01-32.0      | 1        | 4.35%   |
| 1.01-2.0        | 1        | 4.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 6        | 25%     |
| 3.01-4.0   | 5        | 20.83%  |
| 2.01-3.0   | 5        | 20.83%  |
| 1.01-2.0   | 3        | 12.5%   |
| 8.01-16.0  | 2        | 8.33%   |
| 16.01-24.0 | 1        | 4.17%   |
| 0.51-1.0   | 1        | 4.17%   |
| 0.01-0.5   | 1        | 4.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 10       | 43.48%  |
| 2      | 6        | 26.09%  |
| 3      | 4        | 17.39%  |
| 6      | 1        | 4.35%   |
| 5      | 1        | 4.35%   |
| 4      | 1        | 4.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 69.57%  |
| Yes       | 7        | 30.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 22       | 95.65%  |
| No        | 1        | 4.35%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 60.87%  |
| Yes       | 9        | 39.13%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 60.87%  |
| Yes       | 9        | 39.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 5        | 21.74%  |
| Germany   | 5        | 21.74%  |
| Russia    | 2        | 8.7%    |
| Italy     | 2        | 8.7%    |
| India     | 2        | 8.7%    |
| UK        | 1        | 4.35%   |
| Slovakia  | 1        | 4.35%   |
| Romania   | 1        | 4.35%   |
| Poland    | 1        | 4.35%   |
| Finland   | 1        | 4.35%   |
| Bolivia   | 1        | 4.35%   |
| Australia | 1        | 4.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Bengaluru       | 2        | 8.33%   |
| Zavar           | 1        | 4.17%   |
| Weaverville     | 1        | 4.17%   |
| Warsaw          | 1        | 4.17%   |
| Veliky Novgorod | 1        | 4.17%   |
| Stuttgart       | 1        | 4.17%   |
| Santa Cruz      | 1        | 4.17%   |
| Riverside       | 1        | 4.17%   |
| Reading         | 1        | 4.17%   |
| Petersberg      | 1        | 4.17%   |
| Perugia         | 1        | 4.17%   |
| Parker          | 1        | 4.17%   |
| Neunkirchen     | 1        | 4.17%   |
| Moscow          | 1        | 4.17%   |
| Magdeburg       | 1        | 4.17%   |
| Helsinki        | 1        | 4.17%   |
| Glenview        | 1        | 4.17%   |
| Glendale        | 1        | 4.17%   |
| Bucharest       | 1        | 4.17%   |
| Berlin          | 1        | 4.17%   |
| Asheville       | 1        | 4.17%   |
| Albairate       | 1        | 4.17%   |
| Adelaide        | 1        | 4.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 9        | 47     | 25%     |
| Samsung Electronics       | 5        | 8      | 13.89%  |
| WDC                       | 4        | 5      | 11.11%  |
| Toshiba                   | 3        | 3      | 8.33%   |
| Sandisk                   | 3        | 5      | 8.33%   |
| Kingston                  | 3        | 4      | 8.33%   |
| Crucial                   | 2        | 2      | 5.56%   |
| SK hynix                  | 1        | 1      | 2.78%   |
| Realtek Semiconductor     | 1        | 1      | 2.78%   |
| Phison Electronics        | 1        | 1      | 2.78%   |
| Phison                    | 1        | 1      | 2.78%   |
| Micron/Crucial Technology | 1        | 1      | 2.78%   |
| Intel                     | 1        | 1      | 2.78%   |
| Hewlett-Packard           | 1        | 1      | 2.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB                    | 2        | 4.65%   |
| Kingston SA400S37240G 240GB SSD                   | 2        | 4.65%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 1        | 2.33%   |
| WDC WD3200BEKT-08PVMT1 320GB                      | 1        | 2.33%   |
| WDC WD1600YS-23SHB0 160GB                         | 1        | 2.33%   |
| WDC WD10EZEX-60M2NA0 1TB                          | 1        | 2.33%   |
| Toshiba NVMe SSD Drive 512GB                      | 1        | 2.33%   |
| Toshiba MG04ACA200E 2TB                           | 1        | 2.33%   |
| Toshiba DT01ACA050 500GB                          | 1        | 2.33%   |
| SK hynix PC801 NVMe 512GB                         | 1        | 2.33%   |
| Seagate ST8000VN004-2M2101 8TB                    | 1        | 2.33%   |
| Seagate ST3750528AS 752GB                         | 1        | 2.33%   |
| Seagate ST3500414CS 500GB                         | 1        | 2.33%   |
| Seagate ST2000NX0253 2TB                          | 1        | 2.33%   |
| Seagate ST2000DM001-1ER164 2TB                    | 1        | 2.33%   |
| Seagate ST1000VX000-1ES162 1TB                    | 1        | 2.33%   |
| Seagate ST1000NX0423 1TB                          | 1        | 2.33%   |
| Seagate ST1000LX015-1U7172 1TB                    | 1        | 2.33%   |
| Seagate ST1000LM010-9YH146 1TB                    | 1        | 2.33%   |
| Sandisk WD Blue SN580 1TB                         | 1        | 2.33%   |
| Sandisk WD Blue SN570 500GB                       | 1        | 2.33%   |
| SanDisk SSD PLUS 2000GB                           | 1        | 2.33%   |
| SanDisk SDSSDH32000G 2TB                          | 1        | 2.33%   |
| Samsung SSD PM830 2.5 7mm 256GB                   | 1        | 2.33%   |
| Samsung SSD 960 EVO 250GB                         | 1        | 2.33%   |
| Samsung SSD 860 EVO 500GB                         | 1        | 2.33%   |
| Samsung SSD 860 EVO 250GB                         | 1        | 2.33%   |
| Samsung SSD 850 EVO 2TB                           | 1        | 2.33%   |
| Samsung SSD 840 PRO Series 256GB                  | 1        | 2.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 1        | 2.33%   |
| Samsung HD502IJ 500GB                             | 1        | 2.33%   |
| Realtek RTS5763DL NVMe SSD Controller 2TB         | 1        | 2.33%   |
| Phison NVMe SSD Drive 1TB                         | 1        | 2.33%   |
| Phison E12 NVMe Controller 1TB                    | 1        | 2.33%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB               | 1        | 2.33%   |
| Kingston SUV400S37240G 240GB SSD                  | 1        | 2.33%   |
| Kingston SQ500S37480G 480GB SSD                   | 1        | 2.33%   |
| Intel SSDSA2CW080G3 80GB                          | 1        | 2.33%   |
| HP SSD S700 120GB                                 | 1        | 2.33%   |
| Crucial CT500MX500SSD1 500GB                      | 1        | 2.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 47     | 60%     |
| WDC                 | 3        | 4      | 20%     |
| Toshiba             | 2        | 2      | 13.33%  |
| Samsung Electronics | 1        | 1      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 5      | 30.77%  |
| Kingston            | 3        | 4      | 23.08%  |
| Crucial             | 2        | 2      | 15.38%  |
| WDC                 | 1        | 1      | 7.69%   |
| SanDisk             | 1        | 3      | 7.69%   |
| Intel               | 1        | 1      | 7.69%   |
| Hewlett-Packard     | 1        | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 13       | 54     | 39.39%  |
| SSD  | 11       | 17     | 33.33%  |
| NVMe | 9        | 10     | 27.27%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 20       | 71     | 68.97%  |
| NVMe | 9        | 10     | 31.03%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 13       | 18     | 52%     |
| 1.01-2.0   | 6        | 44     | 24%     |
| 0.51-1.0   | 5        | 7      | 20%     |
| 4.01-10.0  | 1        | 2      | 4%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 8        | 34.78%  |
| 1001-2000      | 4        | 17.39%  |
| 501-1000       | 4        | 17.39%  |
| 101-250        | 3        | 13.04%  |
| More than 3000 | 1        | 4.35%   |
| 21-50          | 1        | 4.35%   |
| 2001-3000      | 1        | 4.35%   |
| Unknown        | 1        | 4.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 7        | 30.43%  |
| 101-250        | 6        | 26.09%  |
| 1-20           | 6        | 26.09%  |
| More than 3000 | 1        | 4.35%   |
| 251-500        | 1        | 4.35%   |
| 51-100         | 1        | 4.35%   |
| Unknown        | 1        | 4.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| Hewlett-Packard SSD S700 120GB | 1        | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| Hewlett-Packard | 1        | 1      | 100%    |

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
| Detected | 11       | 27     | 47.83%  |
| Works    | 11       | 53     | 47.83%  |
| Malfunc  | 1        | 1      | 4.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 20       | 55.56%  |
| AMD                          | 3        | 8.33%   |
| SanDisk                      | 2        | 5.56%   |
| Samsung Electronics          | 2        | 5.56%   |
| Phison Electronics           | 2        | 5.56%   |
| Broadcom / LSI               | 2        | 5.56%   |
| VIA Technologies             | 1        | 2.78%   |
| Toshiba America Info Systems | 1        | 2.78%   |
| SK hynix                     | 1        | 2.78%   |
| Realtek Semiconductor        | 1        | 2.78%   |
| Micron/Crucial Technology    | 1        | 2.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel SATA Controller [RAID Mode]                                                       | 3        | 6.38%   |
| Phison E12 NVMe Controller                                                              | 2        | 4.26%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 4.26%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 4.26%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 4.26%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2        | 4.26%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 4.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 4.26%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 4.26%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 4.26%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 4.26%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 2.13%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 1        | 2.13%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                      | 1        | 2.13%   |
| Sandisk WD Blue SN580 NVMe SSD (DRAM-less)                                              | 1        | 2.13%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 1        | 2.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 2.13%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 2.13%   |
| Realtek RTS5762 NVMe SSD Controller                                                     | 1        | 2.13%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 1        | 2.13%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1        | 2.13%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 1        | 2.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 2.13%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 2.13%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 2.13%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 2.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 2.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 2.13%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1        | 2.13%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                            | 1        | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 2.13%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 1        | 2.13%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 2.13%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 2.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 18       | 46.15%  |
| NVMe | 9        | 23.08%  |
| RAID | 5        | 12.82%  |
| IDE  | 5        | 12.82%  |
| SAS  | 2        | 5.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 20       | 86.96%  |
| AMD    | 3        | 13.04%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Xeon CPU X3450 @ 2.67GHz         | 1        | 4.35%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz    | 1        | 4.35%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz    | 1        | 4.35%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz    | 1        | 4.35%   |
| Intel Pentium CPU G3240 @ 3.10GHz      | 1        | 4.35%   |
| Intel Pentium CPU G2020 @ 2.90GHz      | 1        | 4.35%   |
| Intel Core i9-10900K CPU @ 3.70GHz     | 1        | 4.35%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 1        | 4.35%   |
| Intel Core i7-6800K CPU @ 3.40GHz      | 1        | 4.35%   |
| Intel Core i7-6700 CPU @ 3.40GHz       | 1        | 4.35%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 1        | 4.35%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 1        | 4.35%   |
| Intel Core i7-10700K CPU @ 3.80GHz     | 1        | 4.35%   |
| Intel Core i5-4460 CPU @ 3.20GHz       | 1        | 4.35%   |
| Intel Core i5-10500 CPU @ 3.10GHz      | 1        | 4.35%   |
| Intel Core i3-2120 CPU @ 3.30GHz       | 1        | 4.35%   |
| Intel Core i3 CPU 550 @ 3.20GHz        | 1        | 4.35%   |
| Intel 13th Gen Core i5-13400T          | 1        | 4.35%   |
| Intel 12th Gen Core i9-12900K          | 1        | 4.35%   |
| Intel 12th Gen Core i7-12700           | 1        | 4.35%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 1        | 4.35%   |
| AMD Ryzen 5 5600G with Radeon Graphics | 1        | 4.35%   |
| AMD FX-8350 Eight-Core Processor       | 1        | 4.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| Intel Core i7 | 6        | 26.09%  |
| Intel Xeon    | 4        | 17.39%  |
| Other         | 3        | 13.04%  |
| Intel Pentium | 2        | 8.7%    |
| Intel Core i5 | 2        | 8.7%    |
| Intel Core i3 | 2        | 8.7%    |
| Intel Core i9 | 1        | 4.35%   |
| AMD Ryzen 7   | 1        | 4.35%   |
| AMD Ryzen 5   | 1        | 4.35%   |
| AMD FX        | 1        | 4.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 6        | 26.09%  |
| 6      | 4        | 17.39%  |
| 2      | 4        | 17.39%  |
| 16     | 3        | 13.04%  |
| 10     | 3        | 13.04%  |
| 8      | 2        | 8.7%    |
| 12     | 1        | 4.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 21       | 91.3%   |
| 2      | 2        | 8.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 20       | 86.96%  |
| 1      | 3        | 13.04%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 23       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 3        | 13.04%  |
| 0xa0655    | 2        | 8.7%    |
| 0x306e4    | 2        | 8.7%    |
| 0x306c3    | 2        | 8.7%    |
| 0x306a9    | 2        | 8.7%    |
| 0x206a7    | 2        | 8.7%    |
| 0xb06f2    | 1        | 4.35%   |
| 0xa0653    | 1        | 4.35%   |
| 0x906ea    | 1        | 4.35%   |
| 0x90672    | 1        | 4.35%   |
| 0x506e3    | 1        | 4.35%   |
| 0x406f1    | 1        | 4.35%   |
| 0x20655    | 1        | 4.35%   |
| 0x106e5    | 1        | 4.35%   |
| 0x0a50000c | 1        | 4.35%   |
| 0x0800820d | 1        | 4.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| IvyBridge        | 4        | 17.39%  |
| CometLake        | 3        | 13.04%  |
| SandyBridge      | 2        | 8.7%    |
| Haswell          | 2        | 8.7%    |
| Broadwell        | 2        | 8.7%    |
| Unknown          | 2        | 8.7%    |
| Zen+             | 1        | 4.35%   |
| Zen 3            | 1        | 4.35%   |
| Westmere         | 1        | 4.35%   |
| Skylake          | 1        | 4.35%   |
| Piledriver       | 1        | 4.35%   |
| Nehalem          | 1        | 4.35%   |
| KabyLake         | 1        | 4.35%   |
| Alderlake Hybrid | 1        | 4.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 12       | 44.44%  |
| Intel                      | 11       | 40.74%  |
| AMD                        | 3        | 11.11%  |
| Matrox Electronics Systems | 1        | 3.7%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 11.11%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 7.41%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 3.7%    |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 3.7%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 3.7%    |
| Nvidia GM204 [GeForce GTX 980]                                              | 1        | 3.7%    |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 3.7%    |
| Nvidia GK110GL [Quadro K6000]                                               | 1        | 3.7%    |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 3.7%    |
| Nvidia GF110GL [Tesla C2050 / C2075]                                        | 1        | 3.7%    |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 3.7%    |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 1        | 3.7%    |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 3.7%    |
| Nvidia AD104 [GeForce RTX 4070 Ti]                                          | 1        | 3.7%    |
| Matrox Electronics Systems G200eR2                                          | 1        | 3.7%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 3.7%    |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 3.7%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 3.7%    |
| Intel AlderLake-S GT1                                                       | 1        | 3.7%    |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 1        | 3.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 3.7%    |
| AMD Turks [Radeon HD 7600 Series]                                           | 1        | 3.7%    |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 3.7%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 3.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 9        | 39.13%  |
| 1 x Intel      | 8        | 34.78%  |
| AMD + Nvidia   | 2        | 8.7%    |
| Other          | 1        | 4.35%   |
| 1 x Matrox     | 1        | 4.35%   |
| Intel + Nvidia | 1        | 4.35%   |
| 1 x AMD        | 1        | 4.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 15       | 65.22%  |
| Unknown     | 5        | 21.74%  |
| Proprietary | 3        | 13.04%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 15       | 65.22%  |
| 3.01-4.0   | 4        | 17.39%  |
| 1.01-2.0   | 2        | 8.7%    |
| 5.01-6.0   | 1        | 4.35%   |
| 8.01-16.0  | 1        | 4.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 5        | 23.81%  |
| Hewlett-Packard     | 3        | 14.29%  |
| Dell                | 3        | 14.29%  |
| Vizio               | 1        | 4.76%   |
| Viotek              | 1        | 4.76%   |
| SAC                 | 1        | 4.76%   |
| Packard Bell        | 1        | 4.76%   |
| Goldstar            | 1        | 4.76%   |
| GameMax             | 1        | 4.76%   |
| Fujitsu Siemens     | 1        | 4.76%   |
| Eizo                | 1        | 4.76%   |
| BenQ                | 1        | 4.76%   |
| ASUSTek Computer    | 1        | 4.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Vizio V405-H9 VIZ1039 3840x2160 878x485mm 39.5-inch                 | 1        | 4.35%   |
| Viotek SUW49C VTK4900 3840x1080 1196x336mm 48.9-inch                | 1        | 4.35%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch | 1        | 4.35%   |
| Samsung Electronics S32B80P SAM71F1 3840x2160 700x400mm 31.7-inch   | 1        | 4.35%   |
| Samsung Electronics S27D391 SAM0B89 1920x1080 598x336mm 27.0-inch   | 1        | 4.35%   |
| Samsung Electronics S27D391 SAM0B88 1920x1080 598x336mm 27.0-inch   | 1        | 4.35%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch   | 1        | 4.35%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch   | 1        | 4.35%   |
| Samsung Electronics LCD Monitor S24C650                             | 1        | 4.35%   |
| SAC LED MONITOR SAC952D 1920x1080 480x270mm 21.7-inch               | 1        | 4.35%   |
| Packard Bell Viseo223DX PKB037A 1920x1080 477x268mm 21.5-inch       | 1        | 4.35%   |
| Hewlett-Packard ZR24w HWP2869 1920x1200 546x352mm 25.6-inch         | 1        | 4.35%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch          | 1        | 4.35%   |
| Hewlett-Packard E273q HPN3474 2560x1440 597x336mm 27.0-inch         | 1        | 4.35%   |
| Goldstar E2240 GSM57A3 1920x1080 477x268mm 21.5-inch                | 1        | 4.35%   |
| GameMax HDMI-DA GMX0001 1920x540                                    | 1        | 4.35%   |
| Fujitsu Siemens B22W-5 ECO FUS07C4 1680x1050 474x296mm 22.0-inch    | 1        | 4.35%   |
| Eizo EV2460 ENC3129 1920x1080 528x297mm 23.9-inch                   | 1        | 4.35%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                   | 1        | 4.35%   |
| Dell LCD Monitor U2415 3840x1200                                    | 1        | 4.35%   |
| Dell LCD Monitor DEL0001 1280x1024                                  | 1        | 4.35%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                   | 1        | 4.35%   |
| ASUSTek Computer PA248QV AUS2400 1920x1200 520x320mm 24.0-inch      | 1        | 4.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 8        | 40%     |
| 3840x2160 (4K)     | 2        | 10%     |
| 1920x1200 (WUXGA)  | 2        | 10%     |
| 3840x1200          | 1        | 5%      |
| 3840x1080          | 1        | 5%      |
| 2560x1440 (QHD)    | 1        | 5%      |
| 1920x540           | 1        | 5%      |
| 1680x1050 (WSXGA+) | 1        | 5%      |
| 1360x768           | 1        | 5%      |
| 1280x1024 (SXGA)   | 1        | 5%      |
| Unknown            | 1        | 5%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 4        | 19.05%  |
| 21      | 4        | 19.05%  |
| Unknown | 3        | 14.29%  |
| 27      | 2        | 9.52%   |
| 23      | 2        | 9.52%   |
| 69      | 1        | 4.76%   |
| 48      | 1        | 4.76%   |
| 31      | 1        | 4.76%   |
| 25      | 1        | 4.76%   |
| 22      | 1        | 4.76%   |
| 18      | 1        | 4.76%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 8        | 42.11%  |
| 401-500     | 5        | 26.32%  |
| Unknown     | 3        | 15.79%  |
| 601-700     | 1        | 5.26%   |
| 1501-2000   | 1        | 5.26%   |
| 1001-1500   | 1        | 5.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 12       | 63.16%  |
| 16/10   | 3        | 15.79%  |
| 32/9    | 2        | 10.53%  |
| 5/4     | 1        | 5.26%   |
| Unknown | 1        | 5.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 7        | 36.84%  |
| Unknown        | 3        | 15.79%  |
| 301-350        | 2        | 10.53%  |
| 251-300        | 2        | 10.53%  |
| More than 1000 | 1        | 5.26%   |
| 351-500        | 1        | 5.26%   |
| 151-200        | 1        | 5.26%   |
| 141-150        | 1        | 5.26%   |
| 501-1000       | 1        | 5.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 11       | 55%     |
| 101-120 | 5        | 25%     |
| Unknown | 3        | 15%     |
| 121-160 | 1        | 5%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 13       | 56.52%  |
| 0     | 5        | 21.74%  |
| 2     | 3        | 13.04%  |
| 3     | 2        | 8.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 14       | 43.75%  |
| Realtek Semiconductor | 12       | 37.5%   |
| Broadcom              | 2        | 6.25%   |
| Qualcomm Atheros      | 1        | 3.13%   |
| QLogic                | 1        | 3.13%   |
| Mellanox Technologies | 1        | 3.13%   |
| ASUSTek Computer      | 1        | 3.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 6        | 16.22%  |
| Realtek RTL8125 2.5GbE Controller                                      | 4        | 10.81%  |
| Intel I211 Gigabit Network Connection                                  | 3        | 8.11%   |
| Intel Wireless 8260                                                    | 2        | 5.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2        | 5.41%   |
| Intel 82574L Gigabit Network Connection                                | 2        | 5.41%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1        | 2.7%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 1        | 2.7%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 1        | 2.7%    |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller               | 1        | 2.7%    |
| Mellanox MT27500 Family [ConnectX-3]                                   | 1        | 2.7%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 1        | 2.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                         | 1        | 2.7%    |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 2.7%    |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 2.7%    |
| Intel Ethernet Connection (17) I219-LM                                 | 1        | 2.7%    |
| Intel Ethernet Connection (14) I219-V                                  | 1        | 2.7%    |
| Intel Ethernet Connection (14) I219-LM                                 | 1        | 2.7%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 1        | 2.7%    |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 1        | 2.7%    |
| Intel 82578DM Gigabit Network Connection                               | 1        | 2.7%    |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                     | 1        | 2.7%    |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 1        | 2.7%    |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]              | 1        | 2.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 6        | 60%     |
| Realtek Semiconductor | 2        | 20%     |
| Qualcomm Atheros      | 1        | 10%     |
| ASUSTek Computer      | 1        | 10%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wireless 8260                                            | 2        | 20%     |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1        | 10%     |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1        | 10%     |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 10%     |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 1        | 10%     |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1        | 10%     |
| Intel Comet Lake PCH CNVi WiFi                                 | 1        | 10%     |
| Intel Alder Lake-S PCH CNVi WiFi                               | 1        | 10%     |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]      | 1        | 10%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 11       | 44%     |
| Realtek Semiconductor | 10       | 40%     |
| Broadcom              | 2        | 8%      |
| QLogic                | 1        | 4%      |
| Mellanox Technologies | 1        | 4%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 6        | 22.22%  |
| Realtek RTL8125 2.5GbE Controller                                      | 4        | 14.81%  |
| Intel I211 Gigabit Network Connection                                  | 3        | 11.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2        | 7.41%   |
| Intel 82574L Gigabit Network Connection                                | 2        | 7.41%   |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller               | 1        | 3.7%    |
| Mellanox MT27500 Family [ConnectX-3]                                   | 1        | 3.7%    |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 3.7%    |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 3.7%    |
| Intel Ethernet Connection (17) I219-LM                                 | 1        | 3.7%    |
| Intel Ethernet Connection (14) I219-V                                  | 1        | 3.7%    |
| Intel Ethernet Connection (14) I219-LM                                 | 1        | 3.7%    |
| Intel 82578DM Gigabit Network Connection                               | 1        | 3.7%    |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                     | 1        | 3.7%    |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 1        | 3.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 22       | 70.97%  |
| WiFi     | 9        | 29.03%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 21       | 87.5%   |
| WiFi     | 3        | 12.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 11       | 47.83%  |
| 1     | 10       | 43.48%  |
| 4     | 1        | 4.35%   |
| 3     | 1        | 4.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 20       | 86.96%  |
| Yes  | 3        | 13.04%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 6        | 60%     |
| ASUSTek Computer | 2        | 20%     |
| IMC Networks     | 1        | 10%     |
| Broadcom         | 1        | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface             | 2        | 20%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 2        | 20%     |
| ASUS Broadcom BCM20702A0 Bluetooth             | 2        | 20%     |
| Intel AX210 Bluetooth                          | 1        | 10%     |
| Intel AX201 Bluetooth                          | 1        | 10%     |
| IMC Networks Bluetooth Radio                   | 1        | 10%     |
| Broadcom BCM20702A0 Bluetooth 4.0              | 1        | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 17       | 45.95%  |
| Nvidia                 | 11       | 29.73%  |
| AMD                    | 5        | 13.51%  |
| M-Audio                | 1        | 2.7%    |
| GN Netcom              | 1        | 2.7%    |
| C-Media Electronics    | 1        | 2.7%    |
| AKAI Professional M.I. | 1        | 2.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 7.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 4.76%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 2        | 4.76%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 4.76%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 4.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 4.76%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 2.38%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 2.38%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 2.38%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 2.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 2.38%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 2.38%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 2.38%   |
| Nvidia GF110 High Definition Audio Controller                              | 1        | 2.38%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 2.38%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 2.38%   |
| Nvidia Audio device                                                        | 1        | 2.38%   |
| M-Audio AIR HUB                                                            | 1        | 2.38%   |
| Intel Raptor Lake High Definition Audio Controller                         | 1        | 2.38%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 2.38%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 2.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 2.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 2.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 2.38%   |
| GN Netcom Jabra EVOLVE LINK                                                | 1        | 2.38%   |
| C-Media Electronics TONOR TC30 Audio Device                                | 1        | 2.38%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 2.38%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 2.38%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 2.38%   |
| AMD Navi 10 HDMI Audio                                                     | 1        | 2.38%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 2.38%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 2.38%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 2.38%   |
| AKAI Professional M.I. MPK mini 3                                          | 1        | 2.38%   |
| AKAI Professional M.I. FL STUDIO FIRE                                      | 1        | 2.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Micron Technology   | 3        | 27.27%  |
| Kingston            | 2        | 18.18%  |
| Unknown (0x0C26)    | 1        | 9.09%   |
| Unigen              | 1        | 9.09%   |
| Samsung Electronics | 1        | 9.09%   |
| Crucial             | 1        | 9.09%   |
| Corsair             | 1        | 9.09%   |
| Avant               | 1        | 9.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Unknown (0x0C26) RAM TIMETEC-UD4-3200 32GB DIMM DDR4 3200MT/s | 1        | 6.67%   |
| Unigen RAM Module 4GB DIMM DDR3 1333MT/s                      | 1        | 6.67%   |
| Samsung RAM M393B2G70BH0-YH9 16GB DIMM DDR3 1333MT/s          | 1        | 6.67%   |
| Micron RAM 8ATF1G64AZ-2G3H1 8GB DIMM DDR4 2448MT/s            | 1        | 6.67%   |
| Micron RAM 8ATF1G64AZ-2G3E1 8GB DIMM DDR4 2400MT/s            | 1        | 6.67%   |
| Micron RAM 8ATF1G64AZ-2G3B1 8GB DIMM DDR4 2448MT/s            | 1        | 6.67%   |
| Micron RAM 4ATF1G64AZ-3G2F1 8192MB DIMM DDR4 3200MT/s         | 1        | 6.67%   |
| Micron RAM 18ASF2G72PDZ-2G3B1 16GB DIMM DDR4 2400MT/s         | 1        | 6.67%   |
| Kingston RAM KTW149-ELF 1GB DIMM DDR3 1333MT/s                | 1        | 6.67%   |
| Kingston RAM 9905471-006.A00LF 4GB DIMM DDR3 1333MT/s         | 1        | 6.67%   |
| Kingston RAM 9905403-892.A00LF 8GB DIMM DDR3 1333MT/s         | 1        | 6.67%   |
| Crucial RAM BLE8G4D34AEEAK.K8FB 8192MB DIMM DDR4 3466MT/s     | 1        | 6.67%   |
| Corsair RAM CMK8GX4M1E3200C16 8GB DIMM DDR4 3200MT/s          | 1        | 6.67%   |
| Corsair RAM CMK16GX4M1E3200C16 16GB DIMM DDR4 3200MT/s        | 1        | 6.67%   |
| Avant RAM J644GU44J2320NQ 32GB SODIMM DDR4 3200MT/s           | 1        | 6.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 7        | 63.64%  |
| DDR3 | 4        | 36.36%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 10       | 90.91%  |
| SODIMM | 1        | 9.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 5        | 38.46%  |
| 16384 | 3        | 23.08%  |
| 32768 | 2        | 15.38%  |
| 4096  | 2        | 15.38%  |
| 1024  | 1        | 7.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 4        | 33.33%  |
| 1333  | 4        | 33.33%  |
| 2400  | 2        | 16.67%  |
| 3466  | 1        | 8.33%   |
| 2448  | 1        | 8.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Samsung ML-1660 Series | 1        | 100%    |

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
| Samsung Electronics | 1        | 25%     |
| OPPO Electronics    | 1        | 25%     |
| Microdia            | 1        | 25%     |
| Logitech            | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode) | 1        | 25%     |
| OPPO WAIPIO-MTP _SN:2B7F7E2C            | 1        | 25%     |
| Microdia Webcam Vitade AF               | 1        | 25%     |
| Logitech Webcam C270                    | 1        | 25%     |

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
| 0     | 15       | 65.22%  |
| 2     | 5        | 21.74%  |
| 1     | 3        | 13.04%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 5        | 41.67%  |
| Net/wireless             | 3        | 25%     |
| Unassigned class         | 2        | 16.67%  |
| Communication controller | 1        | 8.33%   |
| Bluetooth                | 1        | 8.33%   |

