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

Total: 33

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Unknown  | Unknown                     | [806e7d1dfa](https://linux-hardware.org/?probe=806e7d1dfa) | Apr 28, 2024 |
| Gigabyte | B450M DS3H-CF               | [cf6c011819](https://linux-hardware.org/?probe=cf6c011819) | Apr 13, 2024 |
| Dell     | 0D28YY A03                  | [894b628494](https://linux-hardware.org/?probe=894b628494) | Apr 12, 2024 |
| ASUSTek  | PRIME B250M-A               | [5d12c5c26e](https://linux-hardware.org/?probe=5d12c5c26e) | Mar 31, 2024 |
| ASUSTek  | PRIME B250M-A               | [142a42435b](https://linux-hardware.org/?probe=142a42435b) | Mar 30, 2024 |
| HP       | ProLiant ML110 Gen9         | [c2f9d107ed](https://linux-hardware.org/?probe=c2f9d107ed) | Mar 02, 2024 |
| HP       | ProLiant ML310e Gen8 v2     | [1b3629654d](https://linux-hardware.org/?probe=1b3629654d) | Mar 02, 2024 |
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
| Oracle Linux 8.3 | 6        | 20.69%  |
| Oracle Linux 9.3 | 5        | 17.24%  |
| Oracle Linux 8.9 | 4        | 13.79%  |
| Oracle Linux 8.6 | 4        | 13.79%  |
| Oracle Linux 9.2 | 3        | 10.34%  |
| Oracle Linux 8.7 | 2        | 6.9%    |
| Oracle Linux 9.0 | 1        | 3.45%   |
| Oracle Linux 8.5 | 1        | 3.45%   |
| Oracle Linux 8.4 | 1        | 3.45%   |
| Oracle Linux 7.7 | 1        | 3.45%   |
| Oracle Linux 7.4 | 1        | 3.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Oracle Linux | 29       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Desktops | Percent |
|------------------------------------|----------|---------|
| 5.4.17-2036.102.0.2.el8uek.x86_64  | 2        | 6.67%   |
| 5.4.17-2036.101.2.el8uek.x86_64    | 2        | 6.67%   |
| 5.15.0-205.149.5.1.el9uek.x86_64   | 2        | 6.67%   |
| 5.4.17-2136.313.6.el8uek.x86_64    | 1        | 3.33%   |
| 5.4.17-2136.310.7.1.el8uek.x86_64  | 1        | 3.33%   |
| 5.4.17-2136.308.9.el8uek.x86_64    | 1        | 3.33%   |
| 5.4.17-2136.307.3.1.el8uek.x86_64  | 1        | 3.33%   |
| 5.4.17-2136.300.7.el8uek.x86_64    | 1        | 3.33%   |
| 5.4.17-2102.202.5.el8uek.x86_64    | 1        | 3.33%   |
| 5.4.17-2102.200.13.el8uek.x86_64   | 1        | 3.33%   |
| 5.4.17-2036.100.6.1.el8uek.x86_64  | 1        | 3.33%   |
| 5.4.11-1.el7.elrepo.x86_64         | 1        | 3.33%   |
| 5.15.0-204.147.6.2.el8uek.x86_64   | 1        | 3.33%   |
| 5.15.0-201.135.6.el9uek.x86_64     | 1        | 3.33%   |
| 5.15.0-200.131.27.el9uek.x86_64    | 1        | 3.33%   |
| 5.15.0-200.131.27.1.el9uek.x86_64  | 1        | 3.33%   |
| 5.15.0-2.52.3.el9uek.x86_64        | 1        | 3.33%   |
| 5.15.0-105.125.6.2.2.el9uek.x86_64 | 1        | 3.33%   |
| 5.15.0-102.110.5.1.el9uek.x86_64   | 1        | 3.33%   |
| 5.15.0-101.103.2.1.el9uek.x86_64   | 1        | 3.33%   |
| 5.15.0-100.96.32.el8uek.x86_64     | 1        | 3.33%   |
| 4.18.0-513.9.1.el8_9.x86_64        | 1        | 3.33%   |
| 4.18.0-513.24.1.el8_9.x86_64       | 1        | 3.33%   |
| 4.18.0-513.18.0.1.el8_9.x86_64     | 1        | 3.33%   |
| 4.18.0-372.16.1.0.2.el8_6.x86_64   | 1        | 3.33%   |
| 4.18.0-240.15.1.el8_3.x86_64       | 1        | 3.33%   |
| 3.10.0-693.11.6.el7.x86_64         | 1        | 3.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.17  | 11       | 37.93%  |
| 5.15.0  | 11       | 37.93%  |
| 4.18.0  | 5        | 17.24%  |
| 5.4.11  | 1        | 3.45%   |
| 3.10.0  | 1        | 3.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 12       | 41.38%  |
| 5.15    | 11       | 37.93%  |
| 4.18    | 5        | 17.24%  |
| 3.10    | 1        | 3.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 29       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 18       | 62.07%  |
| Unknown       | 8        | 27.59%  |
| KDE5          | 2        | 6.9%    |
| GNOME Classic | 1        | 3.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 12       | 41.38%  |
| X11     | 11       | 37.93%  |
| Unknown | 5        | 17.24%  |
| Tty     | 1        | 3.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 18       | 62.07%  |
| GDM     | 8        | 27.59%  |
| SDDM    | 2        | 6.9%    |
| TDM     | 1        | 3.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 13       | 44.83%  |
| ru_RU      | 3        | 10.34%  |
| en_GB      | 3        | 10.34%  |
| pt_BR      | 2        | 6.9%    |
| it_IT      | 2        | 6.9%    |
| Unknown    | 2        | 6.9%    |
| pl_PL      | 1        | 3.45%   |
| en_US.UTF8 | 1        | 3.45%   |
| en_IN      | 1        | 3.45%   |
| de_DE      | 1        | 3.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 15       | 51.72%  |
| BIOS | 14       | 48.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Xfs   | 22       | 75.86%  |
| Ext4  | 5        | 17.24%  |
| Zfs   | 1        | 3.45%   |
| Btrfs | 1        | 3.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 13       | 44.83%  |
| Unknown | 11       | 37.93%  |
| MBR     | 5        | 17.24%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 86.21%  |
| Yes       | 4        | 13.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 96.55%  |
| Yes       | 1        | 3.45%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 7        | 24.14%  |
| Dell                | 6        | 20.69%  |
| Gigabyte Technology | 5        | 17.24%  |
| Hewlett-Packard     | 4        | 13.79%  |
| ASRock              | 3        | 10.34%  |
| MSI                 | 1        | 3.45%   |
| Foxconn             | 1        | 3.45%   |
| Cisco               | 1        | 3.45%   |
| Unknown             | 1        | 3.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| MSI MS-7758                      | 1        | 3.45%   |
| HP Z820 Workstation              | 1        | 3.45%   |
| HP Z420 Workstation              | 1        | 3.45%   |
| HP ProLiant ML310e Gen8 v2       | 1        | 3.45%   |
| HP ProLiant ML110 Gen9           | 1        | 3.45%   |
| Gigabyte Z490 AORUS ELITE AC     | 1        | 3.45%   |
| Gigabyte X99-Designare EX-CF     | 1        | 3.45%   |
| Gigabyte X470 AORUS ULTRA GAMING | 1        | 3.45%   |
| Gigabyte H81M-S2PV               | 1        | 3.45%   |
| Gigabyte B450M DS3H              | 1        | 3.45%   |
| Foxconn p6-2400el                | 1        | 3.45%   |
| Dell PowerEdge FC630             | 1        | 3.45%   |
| Dell OptiPlex 980                | 1        | 3.45%   |
| Dell OptiPlex 790                | 1        | 3.45%   |
| Dell OptiPlex 7090               | 1        | 3.45%   |
| Dell OptiPlex 7060               | 1        | 3.45%   |
| Dell OptiPlex 5000               | 1        | 3.45%   |
| Cisco WAVE-694-K9                | 1        | 3.45%   |
| ASUS SABERTOOTH 990FX R3.0       | 1        | 3.45%   |
| ASUS ROG STRIX G15CF_G15CF       | 1        | 3.45%   |
| ASUS PRIME B560M-A AC            | 1        | 3.45%   |
| ASUS PRIME B250M-A               | 1        | 3.45%   |
| ASUS P8H67                       | 1        | 3.45%   |
| ASUS G11CD                       | 1        | 3.45%   |
| ASUS All Series                  | 1        | 3.45%   |
| ASRock Z68 Extreme3 Gen3         | 1        | 3.45%   |
| ASRock B760M-STX                 | 1        | 3.45%   |
| ASRock B550M Steel Legend        | 1        | 3.45%   |
| Unknown                          | 1        | 3.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 5        | 17.24%  |
| HP ProLiant            | 2        | 6.9%    |
| ASUS PRIME             | 2        | 6.9%    |
| MSI MS-7758            | 1        | 3.45%   |
| HP Z820                | 1        | 3.45%   |
| HP Z420                | 1        | 3.45%   |
| Gigabyte Z490          | 1        | 3.45%   |
| Gigabyte X99-Designare | 1        | 3.45%   |
| Gigabyte X470          | 1        | 3.45%   |
| Gigabyte H81M-S2PV     | 1        | 3.45%   |
| Gigabyte B450M         | 1        | 3.45%   |
| Foxconn p6-2400el      | 1        | 3.45%   |
| Dell PowerEdge         | 1        | 3.45%   |
| Cisco WAVE-694-K9      | 1        | 3.45%   |
| ASUS SABERTOOTH        | 1        | 3.45%   |
| ASUS ROG               | 1        | 3.45%   |
| ASUS P8H67             | 1        | 3.45%   |
| ASUS G11CD             | 1        | 3.45%   |
| ASUS All               | 1        | 3.45%   |
| ASRock Z68             | 1        | 3.45%   |
| ASRock B760M-STX       | 1        | 3.45%   |
| ASRock B550M           | 1        | 3.45%   |
| Unknown                | 1        | 3.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 5        | 17.24%  |
| 2018 | 4        | 13.79%  |
| 2016 | 4        | 13.79%  |
| 2022 | 2        | 6.9%    |
| 2021 | 2        | 6.9%    |
| 2020 | 2        | 6.9%    |
| 2013 | 2        | 6.9%    |
| 2011 | 2        | 6.9%    |
| 2010 | 2        | 6.9%    |
| 2024 | 1        | 3.45%   |
| 2023 | 1        | 3.45%   |
| 2015 | 1        | 3.45%   |
| 2014 | 1        | 3.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 29       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 28       | 96.55%  |
| Enabled  | 1        | 3.45%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 29       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 64.01-256.0     | 7        | 24.14%  |
| 8.01-16.0       | 7        | 24.14%  |
| 32.01-64.0      | 5        | 17.24%  |
| 4.01-8.0        | 3        | 10.34%  |
| 24.01-32.0      | 2        | 6.9%    |
| 16.01-24.0      | 2        | 6.9%    |
| More than 256.0 | 1        | 3.45%   |
| 3.01-4.0        | 1        | 3.45%   |
| 1.01-2.0        | 1        | 3.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 7        | 23.33%  |
| 3.01-4.0   | 7        | 23.33%  |
| 2.01-3.0   | 5        | 16.67%  |
| 1.01-2.0   | 5        | 16.67%  |
| 8.01-16.0  | 2        | 6.67%   |
| 24.01-32.0 | 1        | 3.33%   |
| 16.01-24.0 | 1        | 3.33%   |
| 0.51-1.0   | 1        | 3.33%   |
| 0.01-0.5   | 1        | 3.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 10       | 34.48%  |
| 2      | 7        | 24.14%  |
| 3      | 5        | 17.24%  |
| 4      | 4        | 13.79%  |
| 5      | 2        | 6.9%    |
| 6      | 1        | 3.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 68.97%  |
| Yes       | 9        | 31.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 28       | 96.55%  |
| No        | 1        | 3.45%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 58.62%  |
| Yes       | 12       | 41.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 62.07%  |
| Yes       | 11       | 37.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 5        | 17.24%  |
| Germany   | 5        | 17.24%  |
| Russia    | 4        | 13.79%  |
| Vietnam   | 2        | 6.9%    |
| Italy     | 2        | 6.9%    |
| India     | 2        | 6.9%    |
| Brazil    | 2        | 6.9%    |
| UK        | 1        | 3.45%   |
| Slovakia  | 1        | 3.45%   |
| Romania   | 1        | 3.45%   |
| Poland    | 1        | 3.45%   |
| Finland   | 1        | 3.45%   |
| Bolivia   | 1        | 3.45%   |
| Australia | 1        | 3.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Sao Paulo       | 2        | 6.67%   |
| Moscow          | 2        | 6.67%   |
| Hanoi           | 2        | 6.67%   |
| Bengaluru       | 2        | 6.67%   |
| Zavar           | 1        | 3.33%   |
| Weaverville     | 1        | 3.33%   |
| Warsaw          | 1        | 3.33%   |
| Veliky Novgorod | 1        | 3.33%   |
| Stuttgart       | 1        | 3.33%   |
| Santa Cruz      | 1        | 3.33%   |
| Riverside       | 1        | 3.33%   |
| Reading         | 1        | 3.33%   |
| Petersberg      | 1        | 3.33%   |
| Perugia         | 1        | 3.33%   |
| Parker          | 1        | 3.33%   |
| Neunkirchen     | 1        | 3.33%   |
| Magdeburg       | 1        | 3.33%   |
| Ivanteyevka     | 1        | 3.33%   |
| Helsinki        | 1        | 3.33%   |
| Glenview        | 1        | 3.33%   |
| Glendale        | 1        | 3.33%   |
| Bucharest       | 1        | 3.33%   |
| Berlin          | 1        | 3.33%   |
| Asheville       | 1        | 3.33%   |
| Albairate       | 1        | 3.33%   |
| Adelaide        | 1        | 3.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 12       | 51     | 21.82%  |
| WDC                         | 8        | 11     | 14.55%  |
| Samsung Electronics         | 6        | 9      | 10.91%  |
| Toshiba                     | 5        | 5      | 9.09%   |
| Kingston                    | 5        | 6      | 9.09%   |
| SanDisk                     | 3        | 5      | 5.45%   |
| Kingston Technology Company | 2        | 2      | 3.64%   |
| Hewlett-Packard             | 2        | 2      | 3.64%   |
| Crucial                     | 2        | 2      | 3.64%   |
| SK hynix                    | 1        | 1      | 1.82%   |
| Realtek Semiconductor       | 1        | 1      | 1.82%   |
| Plextor                     | 1        | 1      | 1.82%   |
| Phison Electronics          | 1        | 1      | 1.82%   |
| Phison                      | 1        | 1      | 1.82%   |
| Micron/Crucial Technology   | 1        | 1      | 1.82%   |
| KingSpec                    | 1        | 1      | 1.82%   |
| Intel                       | 1        | 1      | 1.82%   |
| Hitachi                     | 1        | 1      | 1.82%   |
| Apacer                      | 1        | 1      | 1.82%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD  | 4        | 6.15%   |
| Seagate ST2000DM008-2FR102 2TB   | 2        | 3.08%   |
| Samsung SSD 860 EVO 250GB        | 2        | 3.08%   |
| Kingston Company SNV2S2000G 2TB  | 2        | 3.08%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 1.54%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD | 1        | 1.54%   |
| WDC WD40PURX-64GVNY0 4TB         | 1        | 1.54%   |
| WDC WD40PURX-64GVNY0 1 4TB       | 1        | 1.54%   |
| WDC WD40EFRX-68N32N0 4TB         | 1        | 1.54%   |
| WDC WD3200BEKT-08PVMT1 320GB     | 1        | 1.54%   |
| WDC WD30EFRX-68AX9N0 3TB         | 1        | 1.54%   |
| WDC WD2500AAKX-08U6AA0 250GB     | 1        | 1.54%   |
| WDC WD1600YS-23SHB0 160GB        | 1        | 1.54%   |
| WDC WD10EZEX-60M2NA0 1TB         | 1        | 1.54%   |
| Toshiba NVMe SSD Drive 512GB     | 1        | 1.54%   |
| Toshiba MG08ACA16TE 16TB         | 1        | 1.54%   |
| Toshiba MG04ACA200E 2TB          | 1        | 1.54%   |
| Toshiba DT01ACA300 3TB           | 1        | 1.54%   |
| Toshiba DT01ACA050 500GB         | 1        | 1.54%   |
| SK hynix PC801 NVMe 512GB        | 1        | 1.54%   |
| Seagate ST8000VN004-2M2101 8TB   | 1        | 1.54%   |
| Seagate ST8000AS0002-1NA17Z 8TB  | 1        | 1.54%   |
| Seagate ST5000AS0011-1L5178 5TB  | 1        | 1.54%   |
| Seagate ST3750528AS 752GB        | 1        | 1.54%   |
| Seagate ST3500414CS 500GB        | 1        | 1.54%   |
| Seagate ST3000DM001-1CH166 3TB   | 1        | 1.54%   |
| Seagate ST2000NX0253 2TB         | 1        | 1.54%   |
| Seagate ST2000NM0033-9ZM175 2TB  | 1        | 1.54%   |
| Seagate ST2000DM001-1ER164 2TB   | 1        | 1.54%   |
| Seagate ST1000VX000-1ES162 1TB   | 1        | 1.54%   |
| Seagate ST1000NX0423 1TB         | 1        | 1.54%   |
| Seagate ST1000LX015-1U7172 1TB   | 1        | 1.54%   |
| Seagate ST1000LM010-9YH146 1TB   | 1        | 1.54%   |
| Sandisk WD Blue SN580 1TB        | 1        | 1.54%   |
| Sandisk WD Blue SN570 500GB      | 1        | 1.54%   |
| SanDisk SSD PLUS 2000GB          | 1        | 1.54%   |
| SanDisk SDSSDH32000G 2TB         | 1        | 1.54%   |
| Samsung SSD PM830 2.5 7mm 256GB  | 1        | 1.54%   |
| Samsung SSD 960 EVO 250GB        | 1        | 1.54%   |
| Samsung SSD 860 EVO 500GB        | 1        | 1.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 51     | 46.15%  |
| WDC                 | 7        | 9      | 26.92%  |
| Toshiba             | 4        | 4      | 15.38%  |
| Samsung Electronics | 1        | 1      | 3.85%   |
| Hitachi             | 1        | 1      | 3.85%   |
| Hewlett-Packard     | 1        | 1      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 6      | 25%     |
| Kingston            | 5        | 6      | 25%     |
| WDC                 | 2        | 2      | 10%     |
| Crucial             | 2        | 2      | 10%     |
| SanDisk             | 1        | 3      | 5%      |
| Plextor             | 1        | 1      | 5%      |
| KingSpec            | 1        | 1      | 5%      |
| Intel               | 1        | 1      | 5%      |
| Hewlett-Packard     | 1        | 1      | 5%      |
| Apacer              | 1        | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 19       | 67     | 40.43%  |
| SSD  | 17       | 24     | 36.17%  |
| NVMe | 11       | 12     | 23.4%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 26       | 91     | 70.27%  |
| NVMe | 11       | 12     | 29.73%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 18       | 26     | 43.9%   |
| 1.01-2.0   | 7        | 45     | 17.07%  |
| 0.51-1.0   | 7        | 9      | 17.07%  |
| 2.01-3.0   | 3        | 3      | 7.32%   |
| 4.01-10.0  | 3        | 4      | 7.32%   |
| 3.01-4.0   | 2        | 3      | 4.88%   |
| 10.01-20.0 | 1        | 1      | 2.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 8        | 27.59%  |
| 101-250        | 6        | 20.69%  |
| 1001-2000      | 4        | 13.79%  |
| 501-1000       | 4        | 13.79%  |
| More than 3000 | 3        | 10.34%  |
| Unknown        | 2        | 6.9%    |
| 21-50          | 1        | 3.45%   |
| 2001-3000      | 1        | 3.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 8        | 27.59%  |
| 1-20           | 8        | 27.59%  |
| 101-250        | 6        | 20.69%  |
| More than 3000 | 3        | 10.34%  |
| Unknown        | 2        | 6.9%    |
| 251-500        | 1        | 3.45%   |
| 51-100         | 1        | 3.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC WD40PURX-64GVNY0 4TB       | 1        | 1      | 25%     |
| WDC WD40PURX-64GVNY0 1 4TB     | 1        | 1      | 25%     |
| Seagate ST3000DM001-1CH166 3TB | 1        | 1      | 25%     |
| Hewlett-Packard SSD S700 120GB | 1        | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| WDC             | 1        | 2      | 33.33%  |
| Seagate         | 1        | 1      | 33.33%  |
| Hewlett-Packard | 1        | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 2      | 50%     |
| Seagate | 1        | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 3      | 66.67%  |
| SSD  | 1        | 1      | 33.33%  |

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
| Works    | 17       | 72     | 54.84%  |
| Detected | 11       | 27     | 35.48%  |
| Malfunc  | 3        | 4      | 9.68%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 25       | 56.82%  |
| AMD                          | 4        | 9.09%   |
| SanDisk                      | 2        | 4.55%   |
| Samsung Electronics          | 2        | 4.55%   |
| Phison Electronics           | 2        | 4.55%   |
| Kingston Technology Company  | 2        | 4.55%   |
| Broadcom / LSI               | 2        | 4.55%   |
| VIA Technologies             | 1        | 2.27%   |
| Toshiba America Info Systems | 1        | 2.27%   |
| SK hynix                     | 1        | 2.27%   |
| Realtek Semiconductor        | 1        | 2.27%   |
| Micron/Crucial Technology    | 1        | 2.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 4        | 7.02%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 5.26%   |
| Phison E12 NVMe Controller                                                              | 2        | 3.51%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                                      | 2        | 3.51%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 3.51%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2        | 3.51%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2        | 3.51%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 3.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 3.51%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 3.51%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 2        | 3.51%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 3.51%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 1.75%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 1        | 1.75%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                      | 1        | 1.75%   |
| Sandisk WD Blue SN580 NVMe SSD (DRAM-less)                                              | 1        | 1.75%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 1        | 1.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 1.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.75%   |
| Realtek RTS5762 NVMe SSD Controller                                                     | 1        | 1.75%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 1        | 1.75%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1        | 1.75%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 1        | 1.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 1.75%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 1.75%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.75%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 1        | 1.75%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]           | 1        | 1.75%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 1.75%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 1.75%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.75%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1        | 1.75%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                            | 1        | 1.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 1.75%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 1.75%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 1.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 23       | 48.94%  |
| NVMe | 11       | 23.4%   |
| IDE  | 6        | 12.77%  |
| RAID | 5        | 10.64%  |
| SAS  | 2        | 4.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 25       | 86.21%  |
| AMD    | 4        | 13.79%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Xeon CPU X3450 @ 2.67GHz         | 1        | 3.45%   |
| Intel Xeon CPU E5-2690 v4 @ 2.60GHz    | 1        | 3.45%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz    | 1        | 3.45%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz    | 1        | 3.45%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz    | 1        | 3.45%   |
| Intel Xeon CPU E5-1603 v3 @ 2.80GHz    | 1        | 3.45%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz    | 1        | 3.45%   |
| Intel Pentium CPU G3240 @ 3.10GHz      | 1        | 3.45%   |
| Intel Pentium CPU G2020 @ 2.90GHz      | 1        | 3.45%   |
| Intel Core i9-10900K CPU @ 3.70GHz     | 1        | 3.45%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 1        | 3.45%   |
| Intel Core i7-6800K CPU @ 3.40GHz      | 1        | 3.45%   |
| Intel Core i7-6700 CPU @ 3.40GHz       | 1        | 3.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 1        | 3.45%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 1        | 3.45%   |
| Intel Core i7-10700K CPU @ 3.80GHz     | 1        | 3.45%   |
| Intel Core i5-4460 CPU @ 3.20GHz       | 1        | 3.45%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 1        | 3.45%   |
| Intel Core i5-10500 CPU @ 3.10GHz      | 1        | 3.45%   |
| Intel Core i3-7100 CPU @ 3.90GHz       | 1        | 3.45%   |
| Intel Core i3-2120 CPU @ 3.30GHz       | 1        | 3.45%   |
| Intel Core i3 CPU 550 @ 3.20GHz        | 1        | 3.45%   |
| Intel 13th Gen Core i5-13400T          | 1        | 3.45%   |
| Intel 12th Gen Core i9-12900K          | 1        | 3.45%   |
| Intel 12th Gen Core i7-12700           | 1        | 3.45%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 1        | 3.45%   |
| AMD Ryzen 5 5600G with Radeon Graphics | 1        | 3.45%   |
| AMD Ryzen 5 3600X 6-Core Processor     | 1        | 3.45%   |
| AMD FX-8350 Eight-Core Processor       | 1        | 3.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| Intel Xeon    | 7        | 24.14%  |
| Intel Core i7 | 6        | 20.69%  |
| Other         | 3        | 10.34%  |
| Intel Core i5 | 3        | 10.34%  |
| Intel Core i3 | 3        | 10.34%  |
| Intel Pentium | 2        | 6.9%    |
| AMD Ryzen 5   | 2        | 6.9%    |
| Intel Core i9 | 1        | 3.45%   |
| AMD Ryzen 7   | 1        | 3.45%   |
| AMD FX        | 1        | 3.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 9        | 31.03%  |
| 6      | 5        | 17.24%  |
| 2      | 5        | 17.24%  |
| 16     | 3        | 10.34%  |
| 10     | 3        | 10.34%  |
| 8      | 2        | 6.9%    |
| 14     | 1        | 3.45%   |
| 12     | 1        | 3.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 27       | 93.1%   |
| 2      | 2        | 6.9%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 23       | 79.31%  |
| 1      | 6        | 20.69%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 29       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 6        | 20.69%  |
| 0xa0655    | 2        | 6.9%    |
| 0x406f1    | 2        | 6.9%    |
| 0x306e4    | 2        | 6.9%    |
| 0x306c3    | 2        | 6.9%    |
| 0x306a9    | 2        | 6.9%    |
| 0x206a7    | 2        | 6.9%    |
| 0xb06f2    | 1        | 3.45%   |
| 0xa0653    | 1        | 3.45%   |
| 0x906ea    | 1        | 3.45%   |
| 0x906e9    | 1        | 3.45%   |
| 0x90672    | 1        | 3.45%   |
| 0x506e3    | 1        | 3.45%   |
| 0x20655    | 1        | 3.45%   |
| 0x106e5    | 1        | 3.45%   |
| 0x0a50000c | 1        | 3.45%   |
| 0x08701030 | 1        | 3.45%   |
| 0x0800820d | 1        | 3.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| IvyBridge        | 4        | 13.79%  |
| Haswell          | 4        | 13.79%  |
| SandyBridge      | 3        | 10.34%  |
| CometLake        | 3        | 10.34%  |
| Broadwell        | 3        | 10.34%  |
| KabyLake         | 2        | 6.9%    |
| Unknown          | 2        | 6.9%    |
| Zen+             | 1        | 3.45%   |
| Zen 3            | 1        | 3.45%   |
| Zen 2            | 1        | 3.45%   |
| Westmere         | 1        | 3.45%   |
| Skylake          | 1        | 3.45%   |
| Piledriver       | 1        | 3.45%   |
| Nehalem          | 1        | 3.45%   |
| Alderlake Hybrid | 1        | 3.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 13       | 40.63%  |
| Nvidia                     | 12       | 37.5%   |
| Matrox Electronics Systems | 3        | 9.38%   |
| AMD                        | 3        | 9.38%   |
| ASPEED Technology          | 1        | 3.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 9.38%   |
| Matrox Electronics Systems MGA G200EH                                       | 2        | 6.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 6.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 6.25%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 3.13%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 3.13%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 3.13%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 1        | 3.13%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 3.13%   |
| Nvidia GK110GL [Quadro K6000]                                               | 1        | 3.13%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 3.13%   |
| Nvidia GF110GL [Tesla C2050 / C2075]                                        | 1        | 3.13%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 3.13%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 1        | 3.13%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 3.13%   |
| Nvidia AD104 [GeForce RTX 4070 Ti]                                          | 1        | 3.13%   |
| Matrox Electronics Systems G200eR2                                          | 1        | 3.13%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 3.13%   |
| Intel HD Graphics 630                                                       | 1        | 3.13%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 3.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 3.13%   |
| Intel AlderLake-S GT1                                                       | 1        | 3.13%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 1        | 3.13%   |
| ASPEED Technology ASPEED Graphics Family                                    | 1        | 3.13%   |
| AMD Turks [Radeon HD 7600 Series]                                           | 1        | 3.13%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 3.13%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 3.13%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 10       | 34.48%  |
| 1 x Nvidia     | 9        | 31.03%  |
| 1 x Matrox     | 3        | 10.34%  |
| Other          | 2        | 6.9%    |
| AMD + Nvidia   | 2        | 6.9%    |
| Intel + Nvidia | 1        | 3.45%   |
| 1 x ASPEED     | 1        | 3.45%   |
| 1 x AMD        | 1        | 3.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 20       | 68.97%  |
| Unknown     | 6        | 20.69%  |
| Proprietary | 3        | 10.34%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 21       | 72.41%  |
| 3.01-4.0   | 4        | 13.79%  |
| 1.01-2.0   | 2        | 6.9%    |
| 5.01-6.0   | 1        | 3.45%   |
| 8.01-16.0  | 1        | 3.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 5        | 18.52%  |
| Dell                | 5        | 18.52%  |
| Hewlett-Packard     | 3        | 11.11%  |
| Chimei Innolux      | 2        | 7.41%   |
| AOC                 | 2        | 7.41%   |
| Vizio               | 1        | 3.7%    |
| Viotek              | 1        | 3.7%    |
| SAC                 | 1        | 3.7%    |
| Packard Bell        | 1        | 3.7%    |
| Goldstar            | 1        | 3.7%    |
| GameMax             | 1        | 3.7%    |
| Fujitsu Siemens     | 1        | 3.7%    |
| Eizo                | 1        | 3.7%    |
| BenQ                | 1        | 3.7%    |
| ASUSTek Computer    | 1        | 3.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch     | 2        | 6.9%    |
| AOC 24G1WG4 AOC2401 1920x1080 520x290mm 23.4-inch                   | 2        | 6.9%    |
| Vizio V555-J01 VIZ1039 3840x2160 1209x680mm 54.6-inch               | 1        | 3.45%   |
| Viotek SUW49C VTK4900 3840x1080 1196x336mm 48.9-inch                | 1        | 3.45%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch | 1        | 3.45%   |
| Samsung Electronics S32B80P SAM71F1 3840x2160 700x400mm 31.7-inch   | 1        | 3.45%   |
| Samsung Electronics S27D391 SAM0B89 1920x1080 598x336mm 27.0-inch   | 1        | 3.45%   |
| Samsung Electronics S27D391 SAM0B88 1920x1080 598x336mm 27.0-inch   | 1        | 3.45%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch   | 1        | 3.45%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch   | 1        | 3.45%   |
| Samsung Electronics LCD Monitor S24C650                             | 1        | 3.45%   |
| SAC DM-MONB2205 SAC952D 1920x1080 450x270mm 20.7-inch               | 1        | 3.45%   |
| Packard Bell Viseo223DX PKB037A 1920x1080 477x268mm 21.5-inch       | 1        | 3.45%   |
| Hewlett-Packard ZR24w HWP2869 1920x1200 546x352mm 25.6-inch         | 1        | 3.45%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch          | 1        | 3.45%   |
| Hewlett-Packard E273q HPN3474 2560x1440 597x336mm 27.0-inch         | 1        | 3.45%   |
| Goldstar E2240 GSM57A3 1920x1080 477x268mm 21.5-inch                | 1        | 3.45%   |
| GameMax HDMI-DA GMX0001 1920x540                                    | 1        | 3.45%   |
| Fujitsu Siemens B22W-5 ECO FUS07C4 1680x1050 474x296mm 22.0-inch    | 1        | 3.45%   |
| Eizo EV2460 ENC3129 1920x1080 528x297mm 23.9-inch                   | 1        | 3.45%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                   | 1        | 3.45%   |
| Dell P2217H DELA0D9 1920x1080 476x267mm 21.5-inch                   | 1        | 3.45%   |
| Dell P2217H DELA0D8 1920x1080 476x267mm 21.5-inch                   | 1        | 3.45%   |
| Dell LCD Monitor U2415 3840x1200                                    | 1        | 3.45%   |
| Dell LCD Monitor DEL0001 1280x1024                                  | 1        | 3.45%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                   | 1        | 3.45%   |
| ASUSTek Computer PA248QV AUS2400 1920x1200 518x324mm 24.1-inch      | 1        | 3.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 10       | 38.46%  |
| 2560x1440 (QHD)    | 3        | 11.54%  |
| 3840x2160 (4K)     | 2        | 7.69%   |
| 1920x1200 (WUXGA)  | 2        | 7.69%   |
| 1366x768 (WXGA)    | 2        | 7.69%   |
| 3840x1200          | 1        | 3.85%   |
| 3840x1080          | 1        | 3.85%   |
| 1920x540           | 1        | 3.85%   |
| 1680x1050 (WSXGA+) | 1        | 3.85%   |
| 1360x768           | 1        | 3.85%   |
| 1280x1024 (SXGA)   | 1        | 3.85%   |
| Unknown            | 1        | 3.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 6        | 22.22%  |
| 21      | 6        | 22.22%  |
| Unknown | 3        | 11.11%  |
| 27      | 2        | 7.41%   |
| 23      | 2        | 7.41%   |
| 15      | 2        | 7.41%   |
| 69      | 1        | 3.7%    |
| 48      | 1        | 3.7%    |
| 31      | 1        | 3.7%    |
| 25      | 1        | 3.7%    |
| 22      | 1        | 3.7%    |
| 18      | 1        | 3.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 10       | 40%     |
| 401-500     | 7        | 28%     |
| Unknown     | 3        | 12%     |
| 301-350     | 2        | 8%      |
| 601-700     | 1        | 4%      |
| 1501-2000   | 1        | 4%      |
| 1001-1500   | 1        | 4%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 16       | 69.57%  |
| 16/10   | 3        | 13.04%  |
| 32/9    | 2        | 8.7%    |
| 5/4     | 1        | 4.35%   |
| Unknown | 1        | 4.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 11       | 44%     |
| Unknown        | 3        | 12%     |
| 301-350        | 2        | 8%      |
| 251-300        | 2        | 8%      |
| 101-110        | 2        | 8%      |
| More than 1000 | 1        | 4%      |
| 351-500        | 1        | 4%      |
| 151-200        | 1        | 4%      |
| 141-150        | 1        | 4%      |
| 501-1000       | 1        | 4%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 13       | 50%     |
| 101-120 | 9        | 34.62%  |
| Unknown | 3        | 11.54%  |
| 121-160 | 1        | 3.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 15       | 51.72%  |
| 0     | 7        | 24.14%  |
| 2     | 5        | 17.24%  |
| 3     | 2        | 6.9%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 18       | 42.86%  |
| Realtek Semiconductor | 14       | 33.33%  |
| Broadcom              | 4        | 9.52%   |
| Qualcomm Atheros      | 2        | 4.76%   |
| QLogic                | 1        | 2.38%   |
| Mellanox Technologies | 1        | 2.38%   |
| Broadcom Limited      | 1        | 2.38%   |
| ASUSTek Computer      | 1        | 2.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 8        | 16.67%  |
| Realtek RTL8125 2.5GbE Controller                                      | 4        | 8.33%   |
| Intel I211 Gigabit Network Connection                                  | 3        | 6.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 6.25%   |
| Intel 82574L Gigabit Network Connection                                | 3        | 6.25%   |
| Intel Wireless 8260                                                    | 2        | 4.17%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1        | 2.08%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 1        | 2.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 2.08%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 1        | 2.08%   |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller               | 1        | 2.08%   |
| Mellanox MT27500 Family [ConnectX-3]                                   | 1        | 2.08%   |
| Intel Wireless 7260                                                    | 1        | 2.08%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 1        | 2.08%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 1        | 2.08%   |
| Intel Ethernet Controller I226-V                                       | 1        | 2.08%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 2.08%   |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 2.08%   |
| Intel Ethernet Connection (17) I219-LM                                 | 1        | 2.08%   |
| Intel Ethernet Connection (14) I219-V                                  | 1        | 2.08%   |
| Intel Ethernet Connection (14) I219-LM                                 | 1        | 2.08%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 1        | 2.08%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 1        | 2.08%   |
| Intel 82578DM Gigabit Network Connection                               | 1        | 2.08%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                     | 1        | 2.08%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                     | 1        | 2.08%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 1        | 2.08%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 1        | 2.08%   |
| Broadcom NetXtreme BCM5717 Gigabit Ethernet PCIe                       | 1        | 2.08%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 1        | 2.08%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]              | 1        | 2.08%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 7        | 53.85%  |
| Realtek Semiconductor | 2        | 15.38%  |
| Qualcomm Atheros      | 2        | 15.38%  |
| Broadcom Limited      | 1        | 7.69%   |
| ASUSTek Computer      | 1        | 7.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wireless 8260                                                  | 2        | 15.38%  |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1        | 7.69%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 1        | 7.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1        | 7.69%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 1        | 7.69%   |
| Intel Wireless 7260                                                  | 1        | 7.69%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 1        | 7.69%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 1        | 7.69%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 1        | 7.69%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 1        | 7.69%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 1        | 7.69%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]            | 1        | 7.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 15       | 45.45%  |
| Realtek Semiconductor | 12       | 36.36%  |
| Broadcom              | 4        | 12.12%  |
| QLogic                | 1        | 3.03%   |
| Mellanox Technologies | 1        | 3.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 8        | 22.86%  |
| Realtek RTL8125 2.5GbE Controller                                      | 4        | 11.43%  |
| Intel I211 Gigabit Network Connection                                  | 3        | 8.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 8.57%   |
| Intel 82574L Gigabit Network Connection                                | 3        | 8.57%   |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller               | 1        | 2.86%   |
| Mellanox MT27500 Family [ConnectX-3]                                   | 1        | 2.86%   |
| Intel Ethernet Controller I226-V                                       | 1        | 2.86%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 2.86%   |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 2.86%   |
| Intel Ethernet Connection (17) I219-LM                                 | 1        | 2.86%   |
| Intel Ethernet Connection (14) I219-V                                  | 1        | 2.86%   |
| Intel Ethernet Connection (14) I219-LM                                 | 1        | 2.86%   |
| Intel 82578DM Gigabit Network Connection                               | 1        | 2.86%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                     | 1        | 2.86%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                     | 1        | 2.86%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 1        | 2.86%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 1        | 2.86%   |
| Broadcom NetXtreme BCM5717 Gigabit Ethernet PCIe                       | 1        | 2.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 28       | 70%     |
| WiFi     | 12       | 30%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 25       | 83.33%  |
| WiFi     | 5        | 16.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 13       | 44.83%  |
| 1     | 11       | 37.93%  |
| 3     | 3        | 10.34%  |
| 7     | 1        | 3.45%   |
| 4     | 1        | 3.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 26       | 89.66%  |
| Yes  | 3        | 10.34%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 6        | 50%     |
| ASUSTek Computer                | 2        | 16.67%  |
| Qualcomm Atheros Communications | 1        | 8.33%   |
| IMC Networks                    | 1        | 8.33%   |
| Broadcom                        | 1        | 8.33%   |
| Apple                           | 1        | 8.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Bluetooth Device                         | 2        | 16.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 2        | 16.67%  |
| ASUS Broadcom BCM20702A0 Bluetooth             | 2        | 16.67%  |
| Qualcomm Atheros Bluetooth USB Host Controller | 1        | 8.33%   |
| Intel AX210 Bluetooth                          | 1        | 8.33%   |
| Intel AX201 Bluetooth                          | 1        | 8.33%   |
| IMC Networks Bluetooth Radio                   | 1        | 8.33%   |
| Broadcom BCM20702A0 Bluetooth 4.0              | 1        | 8.33%   |
| Apple Bluetooth Host Controller                | 1        | 8.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 20       | 48.78%  |
| Nvidia                 | 11       | 26.83%  |
| AMD                    | 6        | 14.63%  |
| M-Audio                | 1        | 2.44%   |
| GN Netcom              | 1        | 2.44%   |
| C-Media Electronics    | 1        | 2.44%   |
| AKAI Professional M.I. | 1        | 2.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 8.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 4.35%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 2        | 4.35%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 4.35%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 4.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 4.35%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 2.17%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 2.17%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 2.17%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 2.17%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 2.17%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 2.17%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 2.17%   |
| Nvidia GF110 High Definition Audio Controller                              | 1        | 2.17%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 2.17%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 2.17%   |
| Nvidia Audio device                                                        | 1        | 2.17%   |
| M-Audio AIR HUB                                                            | 1        | 2.17%   |
| Intel Raptor Lake High Definition Audio Controller                         | 1        | 2.17%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 2.17%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 2.17%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 2.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 2.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 2.17%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 2.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 2.17%   |
| GN Netcom Jabra EVOLVE LINK                                                | 1        | 2.17%   |
| C-Media Electronics USB PnP Audio Device                                   | 1        | 2.17%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 2.17%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1        | 2.17%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 2.17%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 2.17%   |
| AMD Navi 10 HDMI Audio                                                     | 1        | 2.17%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 2.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 2.17%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 2.17%   |
| AKAI Professional M.I. MPK mini 3                                          | 1        | 2.17%   |
| AKAI Professional M.I. FL STUDIO FIRE                                      | 1        | 2.17%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Micron Technology   | 4        | 20%     |
| Samsung Electronics | 2        | 10%     |
| Kingston            | 2        | 10%     |
| Unknown             | 2        | 10%     |
| Unknown (0x0C26)    | 1        | 5%      |
| Unknown             | 1        | 5%      |
| Unigen              | 1        | 5%      |
| SK hynix            | 1        | 5%      |
| Patriot             | 1        | 5%      |
| Hewlett-Packard     | 1        | 5%      |
| Crucial             | 1        | 5%      |
| Corsair             | 1        | 5%      |
| AVEXIR              | 1        | 5%      |
| Avant               | 1        | 5%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Unknown                                                       | 2        | 7.69%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                     | 1        | 3.85%   |
| Unknown (0x0C26) RAM TIMETEC-UD4-3200 32GB DIMM DDR4 3200MT/s | 1        | 3.85%   |
| Unigen RAM Module 4GB DIMM DDR3 1333MT/s                      | 1        | 3.85%   |
| SK hynix RAM HMA84GR7AFR4N-UH 32GB DIMM DDR4 2400MT/s         | 1        | 3.85%   |
| Samsung RAM M393B2G70BH0-YH9 16GB DIMM DDR3 1333MT/s          | 1        | 3.85%   |
| Samsung RAM M393A4K40BB1-CRC 32GB DIMM DDR4 2400MT/s          | 1        | 3.85%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s               | 1        | 3.85%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s           | 1        | 3.85%   |
| Micron RAM 8ATF1G64AZ-2G3H1 8GB DIMM DDR4 2448MT/s            | 1        | 3.85%   |
| Micron RAM 8ATF1G64AZ-2G3E1 8GB DIMM DDR4 2400MT/s            | 1        | 3.85%   |
| Micron RAM 8ATF1G64AZ-2G3B1 8GB DIMM DDR4 2448MT/s            | 1        | 3.85%   |
| Micron RAM 4ATF1G64AZ-3G2F1 8GB DIMM DDR4 3200MT/s            | 1        | 3.85%   |
| Micron RAM 18ASF2G72PDZ-2G3B1 16GB DIMM DDR4 2400MT/s         | 1        | 3.85%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s          | 1        | 3.85%   |
| Kingston RAM KTW149-ELF 1GB DIMM DDR3 1333MT/s                | 1        | 3.85%   |
| Kingston RAM 9905471-006.A00LF 4GB DIMM DDR3 1333MT/s         | 1        | 3.85%   |
| Kingston RAM 9905403-892.A00LF 8GB DIMM DDR3 1333MT/s         | 1        | 3.85%   |
| HP RAM 669239-081 8GB DIMM DDR3 1600MT/s                      | 1        | 3.85%   |
| Crucial RAM BLE8G4D34AEEAK.K8FB 8192MB DIMM DDR4 3466MT/s     | 1        | 3.85%   |
| Corsair RAM CMK8GX4M1E3200C16 8GB DIMM DDR4 3200MT/s          | 1        | 3.85%   |
| Corsair RAM CMK16GX4M1E3200C16 16GB DIMM DDR4 3200MT/s        | 1        | 3.85%   |
| AVEXIR RAM DDR4-2400 CL16 8GB 8GB DIMM DDR4 2400MT/s          | 1        | 3.85%   |
| AVEXIR RAM DDR4-2400 CL16 4GB 4GB DIMM DDR4 2400MT/s          | 1        | 3.85%   |
| Avant RAM J644GU44J2320NQ 32GB SODIMM DDR4 3200MT/s           | 1        | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 11       | 61.11%  |
| DDR3 | 6        | 33.33%  |
| DRAM | 1        | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 16       | 94.12%  |
| SODIMM | 1        | 5.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 10       | 47.62%  |
| 4096  | 4        | 19.05%  |
| 32768 | 3        | 14.29%  |
| 16384 | 3        | 14.29%  |
| 1024  | 1        | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 4        | 21.05%  |
| 2400  | 4        | 21.05%  |
| 1333  | 4        | 21.05%  |
| 1600  | 2        | 10.53%  |
| 3466  | 1        | 5.26%   |
| 2934  | 1        | 5.26%   |
| 2666  | 1        | 5.26%   |
| 2600  | 1        | 5.26%   |
| 2448  | 1        | 5.26%   |

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
| OPPO SM6375-QRD _SN:EA0028BC            | 1        | 25%     |
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
| 0     | 19       | 65.52%  |
| 2     | 5        | 17.24%  |
| 1     | 5        | 17.24%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 5        | 35.71%  |
| Unassigned class         | 4        | 28.57%  |
| Net/wireless             | 3        | 21.43%  |
| Communication controller | 1        | 7.14%   |
| Bluetooth                | 1        | 7.14%   |

