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

Total: 25

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Oracle Linux 8.3 | 6        | 27.27%  |
| Oracle Linux 8.6 | 4        | 18.18%  |
| Oracle Linux 9.2 | 3        | 13.64%  |
| Oracle Linux 9.3 | 2        | 9.09%   |
| Oracle Linux 8.7 | 2        | 9.09%   |
| Oracle Linux 9.0 | 1        | 4.55%   |
| Oracle Linux 8.5 | 1        | 4.55%   |
| Oracle Linux 8.4 | 1        | 4.55%   |
| Oracle Linux 7.7 | 1        | 4.55%   |
| Oracle Linux 7.4 | 1        | 4.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Oracle Linux | 22       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Desktops | Percent |
|------------------------------------|----------|---------|
| 5.4.17-2036.102.0.2.el8uek.x86_64  | 2        | 8.7%    |
| 5.4.17-2036.101.2.el8uek.x86_64    | 2        | 8.7%    |
| 5.4.17-2136.313.6.el8uek.x86_64    | 1        | 4.35%   |
| 5.4.17-2136.310.7.1.el8uek.x86_64  | 1        | 4.35%   |
| 5.4.17-2136.308.9.el8uek.x86_64    | 1        | 4.35%   |
| 5.4.17-2136.307.3.1.el8uek.x86_64  | 1        | 4.35%   |
| 5.4.17-2136.300.7.el8uek.x86_64    | 1        | 4.35%   |
| 5.4.17-2102.202.5.el8uek.x86_64    | 1        | 4.35%   |
| 5.4.17-2102.200.13.el8uek.x86_64   | 1        | 4.35%   |
| 5.4.17-2036.100.6.1.el8uek.x86_64  | 1        | 4.35%   |
| 5.4.11-1.el7.elrepo.x86_64         | 1        | 4.35%   |
| 5.15.0-200.131.27.el9uek.x86_64    | 1        | 4.35%   |
| 5.15.0-200.131.27.1.el9uek.x86_64  | 1        | 4.35%   |
| 5.15.0-2.52.3.el9uek.x86_64        | 1        | 4.35%   |
| 5.15.0-105.125.6.2.2.el9uek.x86_64 | 1        | 4.35%   |
| 5.15.0-102.110.5.1.el9uek.x86_64   | 1        | 4.35%   |
| 5.15.0-101.103.2.1.el9uek.x86_64   | 1        | 4.35%   |
| 5.15.0-100.96.32.el8uek.x86_64     | 1        | 4.35%   |
| 4.18.0-372.16.1.0.2.el8_6.x86_64   | 1        | 4.35%   |
| 4.18.0-240.15.1.el8_3.x86_64       | 1        | 4.35%   |
| 3.10.0-693.11.6.el7.x86_64         | 1        | 4.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.17  | 11       | 50%     |
| 5.15.0  | 7        | 31.82%  |
| 4.18.0  | 2        | 9.09%   |
| 5.4.11  | 1        | 4.55%   |
| 3.10.0  | 1        | 4.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 12       | 54.55%  |
| 5.15    | 7        | 31.82%  |
| 4.18    | 2        | 9.09%   |
| 3.10    | 1        | 4.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 22       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 16       | 72.73%  |
| Unknown       | 4        | 18.18%  |
| KDE5          | 1        | 4.55%   |
| GNOME Classic | 1        | 4.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 11       | 50%     |
| X11     | 8        | 36.36%  |
| Unknown | 3        | 13.64%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 14       | 63.64%  |
| GDM     | 6        | 27.27%  |
| TDM     | 1        | 4.55%   |
| SDDM    | 1        | 4.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 12       | 54.55%  |
| it_IT      | 2        | 9.09%   |
| en_GB      | 2        | 9.09%   |
| ru_RU      | 1        | 4.55%   |
| pl_PL      | 1        | 4.55%   |
| en_US.UTF8 | 1        | 4.55%   |
| en_IN      | 1        | 4.55%   |
| de_DE      | 1        | 4.55%   |
| Unknown    | 1        | 4.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 12       | 54.55%  |
| EFI  | 10       | 45.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 19       | 86.36%  |
| Ext4 | 2        | 9.09%   |
| Zfs  | 1        | 4.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 11       | 50%     |
| GPT     | 6        | 27.27%  |
| MBR     | 5        | 22.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 90.91%  |
| Yes       | 2        | 9.09%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 95.45%  |
| Yes       | 1        | 4.55%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 6        | 27.27%  |
| Dell                | 5        | 22.73%  |
| Gigabyte Technology | 4        | 18.18%  |
| Hewlett-Packard     | 2        | 9.09%   |
| ASRock              | 2        | 9.09%   |
| MSI                 | 1        | 4.55%   |
| Foxconn             | 1        | 4.55%   |
| Cisco               | 1        | 4.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| MSI MS-7758                      | 1        | 4.55%   |
| HP Z820 Workstation              | 1        | 4.55%   |
| HP Z420 Workstation              | 1        | 4.55%   |
| Gigabyte Z490 AORUS ELITE AC     | 1        | 4.55%   |
| Gigabyte X99-Designare EX-CF     | 1        | 4.55%   |
| Gigabyte X470 AORUS ULTRA GAMING | 1        | 4.55%   |
| Gigabyte H81M-S2PV               | 1        | 4.55%   |
| Foxconn p6-2400el                | 1        | 4.55%   |
| Dell PowerEdge FC630             | 1        | 4.55%   |
| Dell OptiPlex 980                | 1        | 4.55%   |
| Dell OptiPlex 7090               | 1        | 4.55%   |
| Dell OptiPlex 7060               | 1        | 4.55%   |
| Dell OptiPlex 5000               | 1        | 4.55%   |
| Cisco WAVE-694-K9                | 1        | 4.55%   |
| ASUS SABERTOOTH 990FX R3.0       | 1        | 4.55%   |
| ASUS ROG STRIX G15CF_G15CF       | 1        | 4.55%   |
| ASUS PRIME B560M-A AC            | 1        | 4.55%   |
| ASUS P8H67                       | 1        | 4.55%   |
| ASUS G11CD                       | 1        | 4.55%   |
| ASUS All Series                  | 1        | 4.55%   |
| ASRock Z68 Extreme3 Gen3         | 1        | 4.55%   |
| ASRock B550M Steel Legend        | 1        | 4.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 4        | 18.18%  |
| MSI MS-7758            | 1        | 4.55%   |
| HP Z820                | 1        | 4.55%   |
| HP Z420                | 1        | 4.55%   |
| Gigabyte Z490          | 1        | 4.55%   |
| Gigabyte X99-Designare | 1        | 4.55%   |
| Gigabyte X470          | 1        | 4.55%   |
| Gigabyte H81M-S2PV     | 1        | 4.55%   |
| Foxconn p6-2400el      | 1        | 4.55%   |
| Dell PowerEdge         | 1        | 4.55%   |
| Cisco WAVE-694-K9      | 1        | 4.55%   |
| ASUS SABERTOOTH        | 1        | 4.55%   |
| ASUS ROG               | 1        | 4.55%   |
| ASUS PRIME             | 1        | 4.55%   |
| ASUS P8H67             | 1        | 4.55%   |
| ASUS G11CD             | 1        | 4.55%   |
| ASUS All               | 1        | 4.55%   |
| ASRock Z68             | 1        | 4.55%   |
| ASRock B550M           | 1        | 4.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 5        | 22.73%  |
| 2018 | 3        | 13.64%  |
| 2016 | 3        | 13.64%  |
| 2022 | 2        | 9.09%   |
| 2021 | 2        | 9.09%   |
| 2020 | 2        | 9.09%   |
| 2010 | 2        | 9.09%   |
| 2014 | 1        | 4.55%   |
| 2013 | 1        | 4.55%   |
| 2011 | 1        | 4.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 22       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 21       | 95.45%  |
| Enabled  | 1        | 4.55%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 22       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 64.01-256.0     | 5        | 22.73%  |
| 8.01-16.0       | 5        | 22.73%  |
| 4.01-8.0        | 3        | 13.64%  |
| 32.01-64.0      | 3        | 13.64%  |
| 16.01-24.0      | 2        | 9.09%   |
| More than 256.0 | 1        | 4.55%   |
| 3.01-4.0        | 1        | 4.55%   |
| 24.01-32.0      | 1        | 4.55%   |
| 1.01-2.0        | 1        | 4.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 6        | 26.09%  |
| 2.01-3.0   | 5        | 21.74%  |
| 3.01-4.0   | 4        | 17.39%  |
| 1.01-2.0   | 3        | 13.04%  |
| 8.01-16.0  | 2        | 8.7%    |
| 16.01-24.0 | 1        | 4.35%   |
| 0.51-1.0   | 1        | 4.35%   |
| 0.01-0.5   | 1        | 4.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 9        | 40.91%  |
| 2      | 6        | 27.27%  |
| 3      | 4        | 18.18%  |
| 6      | 1        | 4.55%   |
| 5      | 1        | 4.55%   |
| 4      | 1        | 4.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 68.18%  |
| Yes       | 7        | 31.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 21       | 95.45%  |
| No        | 1        | 4.55%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 59.09%  |
| Yes       | 9        | 40.91%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 59.09%  |
| Yes       | 9        | 40.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 5        | 22.73%  |
| Germany   | 4        | 18.18%  |
| Russia    | 2        | 9.09%   |
| Italy     | 2        | 9.09%   |
| India     | 2        | 9.09%   |
| UK        | 1        | 4.55%   |
| Slovakia  | 1        | 4.55%   |
| Romania   | 1        | 4.55%   |
| Poland    | 1        | 4.55%   |
| Finland   | 1        | 4.55%   |
| Bolivia   | 1        | 4.55%   |
| Australia | 1        | 4.55%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Bengaluru       | 2        | 8.7%    |
| Zavar           | 1        | 4.35%   |
| Weaverville     | 1        | 4.35%   |
| Warsaw          | 1        | 4.35%   |
| Veliky Novgorod | 1        | 4.35%   |
| Stuttgart       | 1        | 4.35%   |
| Santa Cruz      | 1        | 4.35%   |
| Riverside       | 1        | 4.35%   |
| Reading         | 1        | 4.35%   |
| Petersberg      | 1        | 4.35%   |
| Perugia         | 1        | 4.35%   |
| Parker          | 1        | 4.35%   |
| Neunkirchen     | 1        | 4.35%   |
| Moscow          | 1        | 4.35%   |
| Helsinki        | 1        | 4.35%   |
| Glenview        | 1        | 4.35%   |
| Glendale        | 1        | 4.35%   |
| Bucharest       | 1        | 4.35%   |
| Berlin          | 1        | 4.35%   |
| Asheville       | 1        | 4.35%   |
| Albairate       | 1        | 4.35%   |
| Adelaide        | 1        | 4.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 9        | 47     | 25.71%  |
| Samsung Electronics       | 5        | 8      | 14.29%  |
| WDC                       | 4        | 5      | 11.43%  |
| Toshiba                   | 3        | 3      | 8.57%   |
| Kingston                  | 3        | 4      | 8.57%   |
| SanDisk                   | 2        | 4      | 5.71%   |
| Crucial                   | 2        | 2      | 5.71%   |
| SK hynix                  | 1        | 1      | 2.86%   |
| Realtek Semiconductor     | 1        | 1      | 2.86%   |
| Phison Electronics        | 1        | 1      | 2.86%   |
| Phison                    | 1        | 1      | 2.86%   |
| Micron/Crucial Technology | 1        | 1      | 2.86%   |
| Intel                     | 1        | 1      | 2.86%   |
| Hewlett-Packard           | 1        | 1      | 2.86%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB                      | 2        | 4.76%   |
| Kingston SA400S37240G 240GB SSD                     | 2        | 4.76%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1        | 2.38%   |
| WDC WD3200BEKT-08PVMT1 320GB                        | 1        | 2.38%   |
| WDC WD1600YS-23SHB0 160GB                           | 1        | 2.38%   |
| WDC WD10EZEX-60M2NA0 1TB                            | 1        | 2.38%   |
| Toshiba NVMe SSD Drive 512GB                        | 1        | 2.38%   |
| Toshiba MG04ACA200E 2TB                             | 1        | 2.38%   |
| Toshiba DT01ACA050 500GB                            | 1        | 2.38%   |
| SK hynix PC801 NVMe 512GB                           | 1        | 2.38%   |
| Seagate ST8000VN004-2M2101 8TB                      | 1        | 2.38%   |
| Seagate ST3750528AS 752GB                           | 1        | 2.38%   |
| Seagate ST3500414CS 500GB                           | 1        | 2.38%   |
| Seagate ST2000NX0253 2TB                            | 1        | 2.38%   |
| Seagate ST2000DM001-1ER164 2TB                      | 1        | 2.38%   |
| Seagate ST1000VX000-1ES162 1TB                      | 1        | 2.38%   |
| Seagate ST1000NX0423 1TB                            | 1        | 2.38%   |
| Seagate ST1000LX015-1U7172 1TB                      | 1        | 2.38%   |
| Seagate ST1000LM010-9YH146 1TB                      | 1        | 2.38%   |
| Sandisk WD Blue SN570 500GB                         | 1        | 2.38%   |
| SanDisk SSD PLUS 2000GB                             | 1        | 2.38%   |
| SanDisk SDSSDH32000G 2TB                            | 1        | 2.38%   |
| Samsung SSD PM830 2.5 7mm 256GB                     | 1        | 2.38%   |
| Samsung SSD 960 EVO 250GB                           | 1        | 2.38%   |
| Samsung SSD 860 EVO 500GB                           | 1        | 2.38%   |
| Samsung SSD 860 EVO 250GB                           | 1        | 2.38%   |
| Samsung SSD 850 EVO 2TB                             | 1        | 2.38%   |
| Samsung SSD 840 PRO Series 256GB                    | 1        | 2.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 1        | 2.38%   |
| Samsung HD502IJ 500GB                               | 1        | 2.38%   |
| Realtek RTS5763DL NVMe SSD Controller 256GB         | 1        | 2.38%   |
| Phison NVMe SSD Drive 1TB                           | 1        | 2.38%   |
| Phison E12 NVMe Controller 1TB                      | 1        | 2.38%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                 | 1        | 2.38%   |
| Kingston SUV400S37240G 240GB SSD                    | 1        | 2.38%   |
| Kingston SQ500S37480G 480GB SSD                     | 1        | 2.38%   |
| Intel SSDSA2CW080G3 80GB                            | 1        | 2.38%   |
| HP SSD S700 120GB                                   | 1        | 2.38%   |
| Crucial CT500MX500SSD1 500GB                        | 1        | 2.38%   |
| Crucial CT2050MX300SSD1 2TB                         | 1        | 2.38%   |

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
| HDD  | 13       | 54     | 40.63%  |
| SSD  | 11       | 17     | 34.38%  |
| NVMe | 8        | 9      | 25%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 20       | 71     | 71.43%  |
| NVMe | 8        | 9      | 28.57%  |

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
| 251-500        | 8        | 36.36%  |
| 1001-2000      | 4        | 18.18%  |
| 101-250        | 3        | 13.64%  |
| 501-1000       | 3        | 13.64%  |
| More than 3000 | 1        | 4.55%   |
| 21-50          | 1        | 4.55%   |
| 2001-3000      | 1        | 4.55%   |
| Unknown        | 1        | 4.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 7        | 31.82%  |
| 101-250        | 6        | 27.27%  |
| 1-20           | 5        | 22.73%  |
| More than 3000 | 1        | 4.55%   |
| 251-500        | 1        | 4.55%   |
| 51-100         | 1        | 4.55%   |
| Unknown        | 1        | 4.55%   |

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
| Detected | 11       | 27     | 50%     |
| Works    | 10       | 52     | 45.45%  |
| Malfunc  | 1        | 1      | 4.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 19       | 55.88%  |
| AMD                          | 3        | 8.82%   |
| Samsung Electronics          | 2        | 5.88%   |
| Phison Electronics           | 2        | 5.88%   |
| Broadcom / LSI               | 2        | 5.88%   |
| VIA Technologies             | 1        | 2.94%   |
| Toshiba America Info Systems | 1        | 2.94%   |
| SK hynix                     | 1        | 2.94%   |
| SanDisk                      | 1        | 2.94%   |
| Realtek Semiconductor        | 1        | 2.94%   |
| Micron/Crucial Technology    | 1        | 2.94%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Phison E12 NVMe Controller                                                              | 2        | 4.55%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 4.55%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 4.55%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 4.55%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2        | 4.55%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2        | 4.55%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 4.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 4.55%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 4.55%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 2.27%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 1        | 2.27%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                      | 1        | 2.27%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 1        | 2.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 2.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 2.27%   |
| Realtek RTS5762 NVMe SSD Controller                                                     | 1        | 2.27%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 1        | 2.27%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 2.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 2.27%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 2.27%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 2.27%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 2.27%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 2.27%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1        | 2.27%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                            | 1        | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 2.27%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 1        | 2.27%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 2.27%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 2.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 17       | 47.22%  |
| NVMe | 8        | 22.22%  |
| IDE  | 5        | 13.89%  |
| RAID | 4        | 11.11%  |
| SAS  | 2        | 5.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 19       | 86.36%  |
| AMD    | 3        | 13.64%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Xeon CPU X3450 @ 2.67GHz         | 1        | 4.55%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz    | 1        | 4.55%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz    | 1        | 4.55%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz    | 1        | 4.55%   |
| Intel Pentium CPU G3240 @ 3.10GHz      | 1        | 4.55%   |
| Intel Pentium CPU G2020 @ 2.90GHz      | 1        | 4.55%   |
| Intel Core i9-10900K CPU @ 3.70GHz     | 1        | 4.55%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 1        | 4.55%   |
| Intel Core i7-6800K CPU @ 3.40GHz      | 1        | 4.55%   |
| Intel Core i7-6700 CPU @ 3.40GHz       | 1        | 4.55%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 1        | 4.55%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 1        | 4.55%   |
| Intel Core i7-10700K CPU @ 3.80GHz     | 1        | 4.55%   |
| Intel Core i5-4460 CPU @ 3.20GHz       | 1        | 4.55%   |
| Intel Core i5-10500 CPU @ 3.10GHz      | 1        | 4.55%   |
| Intel Core i3-2120 CPU @ 3.30GHz       | 1        | 4.55%   |
| Intel Core i3 CPU 550 @ 3.20GHz        | 1        | 4.55%   |
| Intel 12th Gen Core i9-12900K          | 1        | 4.55%   |
| Intel 12th Gen Core i7-12700           | 1        | 4.55%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 1        | 4.55%   |
| AMD Ryzen 5 5600G with Radeon Graphics | 1        | 4.55%   |
| AMD FX-8350 Eight-Core Processor       | 1        | 4.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| Intel Core i7 | 6        | 27.27%  |
| Intel Xeon    | 4        | 18.18%  |
| Other         | 2        | 9.09%   |
| Intel Pentium | 2        | 9.09%   |
| Intel Core i5 | 2        | 9.09%   |
| Intel Core i3 | 2        | 9.09%   |
| Intel Core i9 | 1        | 4.55%   |
| AMD Ryzen 7   | 1        | 4.55%   |
| AMD Ryzen 5   | 1        | 4.55%   |
| AMD FX        | 1        | 4.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 6        | 27.27%  |
| 6      | 4        | 18.18%  |
| 2      | 4        | 18.18%  |
| 16     | 3        | 13.64%  |
| 10     | 2        | 9.09%   |
| 8      | 2        | 9.09%   |
| 12     | 1        | 4.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 20       | 90.91%  |
| 2      | 2        | 9.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 19       | 86.36%  |
| 1      | 3        | 13.64%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 22       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 3        | 13.64%  |
| 0xa0655    | 2        | 9.09%   |
| 0x306e4    | 2        | 9.09%   |
| 0x306c3    | 2        | 9.09%   |
| 0x306a9    | 2        | 9.09%   |
| 0x206a7    | 2        | 9.09%   |
| 0xa0653    | 1        | 4.55%   |
| 0x906ea    | 1        | 4.55%   |
| 0x90672    | 1        | 4.55%   |
| 0x506e3    | 1        | 4.55%   |
| 0x406f1    | 1        | 4.55%   |
| 0x20655    | 1        | 4.55%   |
| 0x106e5    | 1        | 4.55%   |
| 0x0a50000c | 1        | 4.55%   |
| 0x0800820d | 1        | 4.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| IvyBridge        | 4        | 18.18%  |
| CometLake        | 3        | 13.64%  |
| SandyBridge      | 2        | 9.09%   |
| Haswell          | 2        | 9.09%   |
| Broadwell        | 2        | 9.09%   |
| Zen+             | 1        | 4.55%   |
| Zen 3            | 1        | 4.55%   |
| Westmere         | 1        | 4.55%   |
| Skylake          | 1        | 4.55%   |
| Piledriver       | 1        | 4.55%   |
| Nehalem          | 1        | 4.55%   |
| KabyLake         | 1        | 4.55%   |
| Alderlake Hybrid | 1        | 4.55%   |
| Unknown          | 1        | 4.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 12       | 46.15%  |
| Intel                      | 10       | 38.46%  |
| AMD                        | 3        | 11.54%  |
| Matrox Electronics Systems | 1        | 3.85%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 11.54%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 7.69%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 3.85%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 3.85%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 3.85%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 1        | 3.85%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 3.85%   |
| Nvidia GK110GL [Quadro K6000]                                               | 1        | 3.85%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 3.85%   |
| Nvidia GF110GL [Tesla C2050 / C2075]                                        | 1        | 3.85%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 3.85%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 1        | 3.85%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 3.85%   |
| Nvidia AD104 [GeForce RTX 4070 Ti]                                          | 1        | 3.85%   |
| Matrox Electronics Systems G200eR2                                          | 1        | 3.85%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 3.85%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 3.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 3.85%   |
| Intel AlderLake-S GT1                                                       | 1        | 3.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 3.85%   |
| AMD Turks [Radeon HD 7600 Series]                                           | 1        | 3.85%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 3.85%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 3.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 9        | 40.91%  |
| 1 x Intel      | 7        | 31.82%  |
| AMD + Nvidia   | 2        | 9.09%   |
| Other          | 1        | 4.55%   |
| 1 x Matrox     | 1        | 4.55%   |
| Intel + Nvidia | 1        | 4.55%   |
| 1 x AMD        | 1        | 4.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 15       | 68.18%  |
| Unknown     | 4        | 18.18%  |
| Proprietary | 3        | 13.64%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 63.64%  |
| 3.01-4.0   | 4        | 18.18%  |
| 1.01-2.0   | 2        | 9.09%   |
| 5.01-6.0   | 1        | 4.55%   |
| 8.01-16.0  | 1        | 4.55%   |

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
| Vizio V505-H1 VIZ1039 3840x2160 941x529mm 42.5-inch                 | 1        | 4.35%   |
| Viotek SUW49C VTK4900 3840x1080 1196x336mm 48.9-inch                | 1        | 4.35%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch | 1        | 4.35%   |
| Samsung Electronics S32B80P SAM71F1 3840x2160 700x400mm 31.7-inch   | 1        | 4.35%   |
| Samsung Electronics S27D391 SAM0B89 1920x1080 598x336mm 27.0-inch   | 1        | 4.35%   |
| Samsung Electronics S27D391 SAM0B88 1920x1080 598x336mm 27.0-inch   | 1        | 4.35%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch   | 1        | 4.35%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch   | 1        | 4.35%   |
| Samsung Electronics LCD Monitor S24C650                             | 1        | 4.35%   |
| SAC LED MONITOR SAC952D 1920x1080 443x249mm 20.0-inch               | 1        | 4.35%   |
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
| 1     | 13       | 59.09%  |
| 0     | 4        | 18.18%  |
| 2     | 3        | 13.64%  |
| 3     | 2        | 9.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 14       | 45.16%  |
| Realtek Semiconductor | 11       | 35.48%  |
| Broadcom              | 2        | 6.45%   |
| Qualcomm Atheros      | 1        | 3.23%   |
| QLogic                | 1        | 3.23%   |
| Mellanox Technologies | 1        | 3.23%   |
| ASUSTek Computer      | 1        | 3.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6        | 16.67%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 8.33%   |
| Intel I211 Gigabit Network Connection                             | 3        | 8.33%   |
| Intel Wireless 8260                                               | 2        | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 5.56%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 5.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 2.78%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1        | 2.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1        | 2.78%   |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller          | 1        | 2.78%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 1        | 2.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 2.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1        | 2.78%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 2.78%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 2.78%   |
| Intel Ethernet Connection (17) I219-LM                            | 1        | 2.78%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 2.78%   |
| Intel Ethernet Connection (14) I219-LM                            | 1        | 2.78%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1        | 2.78%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 1        | 2.78%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 2.78%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1        | 2.78%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1        | 2.78%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]         | 1        | 2.78%   |

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
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1        | 10%     |
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
| Intel                 | 11       | 45.83%  |
| Realtek Semiconductor | 9        | 37.5%   |
| Broadcom              | 2        | 8.33%   |
| QLogic                | 1        | 4.17%   |
| Mellanox Technologies | 1        | 4.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6        | 23.08%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 11.54%  |
| Intel I211 Gigabit Network Connection                             | 3        | 11.54%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 7.69%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 7.69%   |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller          | 1        | 3.85%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 1        | 3.85%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 3.85%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 3.85%   |
| Intel Ethernet Connection (17) I219-LM                            | 1        | 3.85%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 3.85%   |
| Intel Ethernet Connection (14) I219-LM                            | 1        | 3.85%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 3.85%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1        | 3.85%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1        | 3.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 21       | 70%     |
| WiFi     | 9        | 30%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 20       | 86.96%  |
| WiFi     | 3        | 13.04%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 11       | 50%     |
| 1     | 9        | 40.91%  |
| 4     | 1        | 4.55%   |
| 3     | 1        | 4.55%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 20       | 90.91%  |
| Yes  | 2        | 9.09%   |

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
| Intel Bluetooth Device                         | 1        | 10%     |
| Intel AX210 Bluetooth                          | 1        | 10%     |
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
| Intel                  | 16       | 44.44%  |
| Nvidia                 | 11       | 30.56%  |
| AMD                    | 5        | 13.89%  |
| M-Audio                | 1        | 2.78%   |
| GN Netcom              | 1        | 2.78%   |
| C-Media Electronics    | 1        | 2.78%   |
| AKAI Professional M.I. | 1        | 2.78%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 7.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 4.88%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 2        | 4.88%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 4.88%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 4.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 4.88%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 2.44%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 2.44%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 2.44%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 2.44%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 2.44%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 2.44%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 2.44%   |
| Nvidia GF110 High Definition Audio Controller                              | 1        | 2.44%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 2.44%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 2.44%   |
| Nvidia Audio device                                                        | 1        | 2.44%   |
| M-Audio AIR HUB                                                            | 1        | 2.44%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 2.44%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 2.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 2.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 2.44%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 2.44%   |
| GN Netcom Jabra EVOLVE LINK                                                | 1        | 2.44%   |
| C-Media Electronics TONOR TC-777 Audio Device                              | 1        | 2.44%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 2.44%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 2.44%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 2.44%   |
| AMD Navi 10 HDMI Audio                                                     | 1        | 2.44%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 2.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 2.44%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 2.44%   |
| AKAI Professional M.I. MPK mini 3                                          | 1        | 2.44%   |
| AKAI Professional M.I. FL STUDIO FIRE                                      | 1        | 2.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Micron Technology   | 3        | 30%     |
| Kingston            | 2        | 20%     |
| Unknown (0x0C26)    | 1        | 10%     |
| Unigen              | 1        | 10%     |
| Samsung Electronics | 1        | 10%     |
| Crucial             | 1        | 10%     |
| Corsair             | 1        | 10%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Unknown (0x0C26) RAM TIMETEC-UD4-3200 32GB DIMM DDR4 3200MT/s | 1        | 7.14%   |
| Unigen RAM Module 4GB DIMM DDR3 1333MT/s                      | 1        | 7.14%   |
| Samsung RAM M393B2G70BH0-YH9 16GB DIMM DDR3 1333MT/s          | 1        | 7.14%   |
| Micron RAM 8ATF1G64AZ-2G3H1 8GB DIMM DDR4 2448MT/s            | 1        | 7.14%   |
| Micron RAM 8ATF1G64AZ-2G3E1 8GB DIMM DDR4 2400MT/s            | 1        | 7.14%   |
| Micron RAM 8ATF1G64AZ-2G3B1 8GB DIMM DDR4 2448MT/s            | 1        | 7.14%   |
| Micron RAM 4ATF1G64AZ-3G2F1 8GB DIMM DDR4 3200MT/s            | 1        | 7.14%   |
| Micron RAM 18ASF2G72PDZ-2G3B1 16GB DIMM DDR4 2400MT/s         | 1        | 7.14%   |
| Kingston RAM KTW149-ELF 1GB DIMM DDR3 1333MT/s                | 1        | 7.14%   |
| Kingston RAM 9905471-006.A00LF 4GB DIMM DDR3 1333MT/s         | 1        | 7.14%   |
| Kingston RAM 9905403-892.A00LF 8GB DIMM DDR3 1333MT/s         | 1        | 7.14%   |
| Crucial RAM BLE8G4D34AEEAK.K8FB 8192MB DIMM DDR4 3466MT/s     | 1        | 7.14%   |
| Corsair RAM CMK8GX4M1E3200C16 8GB DIMM DDR4 3200MT/s          | 1        | 7.14%   |
| Corsair RAM CMK16GX4M1E3200C16 16GB DIMM DDR4 3200MT/s        | 1        | 7.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 6        | 60%     |
| DDR3 | 4        | 40%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 10       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 5        | 41.67%  |
| 16384 | 3        | 25%     |
| 4096  | 2        | 16.67%  |
| 32768 | 1        | 8.33%   |
| 1024  | 1        | 8.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1333  | 4        | 36.36%  |
| 3200  | 3        | 27.27%  |
| 2400  | 2        | 18.18%  |
| 3466  | 1        | 9.09%   |
| 2448  | 1        | 9.09%   |

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


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| OPPO Electronics | 1        | 33.33%  |
| Microdia         | 1        | 33.33%  |
| Logitech         | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| OPPO WAIPIO-MTP _SN:2B7F7E2C | 1        | 33.33%  |
| Microdia Webcam Vitade AF    | 1        | 33.33%  |
| Logitech Webcam C270         | 1        | 33.33%  |

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
| 0     | 15       | 68.18%  |
| 2     | 5        | 22.73%  |
| 1     | 2        | 9.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 4        | 36.36%  |
| Net/wireless             | 3        | 27.27%  |
| Unassigned class         | 2        | 18.18%  |
| Communication controller | 1        | 9.09%   |
| Bluetooth                | 1        | 9.09%   |

