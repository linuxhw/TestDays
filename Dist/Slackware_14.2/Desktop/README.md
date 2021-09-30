Slackware 14.2 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Slackware 14.2.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=slackware-14.2

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

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| Intel      | DZ77RE-75K AAG39010-302     | [069c508e80](https://linux-hardware.org/?probe=069c508e80) | Sep 25, 2021 |
| Shuttle    | NC03U                       | [c5f76c4400](https://linux-hardware.org/?probe=c5f76c4400) | Sep 22, 2021 |
| HPE        | ProLiant MicroServer Gen... | [9ac798b737](https://linux-hardware.org/?probe=9ac798b737) | Aug 05, 2021 |
| HPE        | ProLiant MicroServer Gen... | [095745e5fb](https://linux-hardware.org/?probe=095745e5fb) | Jul 06, 2021 |
| HP         | 158A                        | [d612124939](https://linux-hardware.org/?probe=d612124939) | Jun 21, 2021 |
| ASRock     | H310CM-HDV                  | [3291e5d2de](https://linux-hardware.org/?probe=3291e5d2de) | Jun 19, 2021 |
| ASRock     | H87M Pro4                   | [8d4b7f121d](https://linux-hardware.org/?probe=8d4b7f121d) | Jun 02, 2021 |
| ASUSTek    | Pro WS X570-ACE             | [6e60025ac5](https://linux-hardware.org/?probe=6e60025ac5) | May 25, 2021 |
| ASUSTek    | PRIME X370-PRO              | [3e5f76719a](https://linux-hardware.org/?probe=3e5f76719a) | May 24, 2021 |
| ASUSTek    | PRIME X370-PRO              | [c75f9d5c0d](https://linux-hardware.org/?probe=c75f9d5c0d) | May 23, 2021 |
| Dell       | 0PTTT9 A00                  | [e5b81a0da1](https://linux-hardware.org/?probe=e5b81a0da1) | May 20, 2021 |
| Gigabyte   | N3160TN                     | [2fd537312f](https://linux-hardware.org/?probe=2fd537312f) | May 14, 2021 |
| MSI        | G31TM-P21                   | [91c11ae82e](https://linux-hardware.org/?probe=91c11ae82e) | May 07, 2021 |
| Foxconn    | 2ADA                        | [425d15a5ce](https://linux-hardware.org/?probe=425d15a5ce) | Mar 09, 2021 |
| Dell       | 0TP412                      | [f0e56aacff](https://linux-hardware.org/?probe=f0e56aacff) | Jan 05, 2021 |
| Supermicro | X8SIE 0001                  | [96607f4270](https://linux-hardware.org/?probe=96607f4270) | Nov 12, 2020 |
| ASRock     | Z390M-ITX/ac                | [06eb8afdbc](https://linux-hardware.org/?probe=06eb8afdbc) | Oct 19, 2020 |
| ASUSTek    | PRIME B450-PLUS             | [d42d44dd82](https://linux-hardware.org/?probe=d42d44dd82) | Jul 23, 2020 |
| ASUSTek    | PRIME B450-PLUS             | [888f105221](https://linux-hardware.org/?probe=888f105221) | Jul 23, 2020 |
| ASUSTek    | M5A97 R2.0                  | [2eb600bb96](https://linux-hardware.org/?probe=2eb600bb96) | Jul 10, 2020 |
| ASUSTek    | M5A97 R2.0                  | [232221bf45](https://linux-hardware.org/?probe=232221bf45) | Jul 10, 2020 |
| Huanan     | X79-8D VAA31                | [bbfc99d048](https://linux-hardware.org/?probe=bbfc99d048) | Jan 22, 2020 |
| ASUSTek    | A68HM-PLUS                  | [505df04abc](https://linux-hardware.org/?probe=505df04abc) | Oct 27, 2019 |
| ASUSTek    | PRIME B350M-A               | [0b246f9623](https://linux-hardware.org/?probe=0b246f9623) | Oct 27, 2019 |
| ASUSTek    | ROG STRIX X470-F GAMING     | [21d76cde28](https://linux-hardware.org/?probe=21d76cde28) | Oct 22, 2019 |
| ASUSTek    | Z97-A                       | [482c60ec21](https://linux-hardware.org/?probe=482c60ec21) | Oct 21, 2019 |
| Gigabyte   | M61SME-S2                   | [10469f1659](https://linux-hardware.org/?probe=10469f1659) | Oct 21, 2019 |
| HP         | 2B35                        | [45c5e4afbe](https://linux-hardware.org/?probe=45c5e4afbe) | Oct 21, 2019 |
| Gigabyte   | 970A-DS3P                   | [70ea4f97bf](https://linux-hardware.org/?probe=70ea4f97bf) | Oct 21, 2019 |
| ASUSTek    | Maximus VII HERO            | [4751f76aa2](https://linux-hardware.org/?probe=4751f76aa2) | Oct 20, 2019 |
| ASUSTek    | Maximus VII RANGER          | [71121ccd6f](https://linux-hardware.org/?probe=71121ccd6f) | Oct 20, 2019 |
| ASUSTek    | P5QLD PRO                   | [dabc1ee203](https://linux-hardware.org/?probe=dabc1ee203) | Oct 20, 2019 |
| Gigabyte   | X150M-PRO ECC-CF            | [39987c5d8e](https://linux-hardware.org/?probe=39987c5d8e) | Oct 10, 2018 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 4.19.80              | 4        | 13.79%  |
| 5.10.28-Unraid       | 3        | 10.34%  |
| 4.4.190              | 3        | 10.34%  |
| 4.4.240              | 2        | 6.9%    |
| 5.4.77               | 1        | 3.45%   |
| 5.4.53-APRL          | 1        | 3.45%   |
| 5.4.43               | 1        | 3.45%   |
| 5.4.0-rc2-vto        | 1        | 3.45%   |
| 5.12.12              | 1        | 3.45%   |
| 5.10.44-slack64-host | 1        | 3.45%   |
| 5.10.40              | 1        | 3.45%   |
| 4.9.248.a            | 1        | 3.45%   |
| 4.9.118              | 1        | 3.45%   |
| 4.4.261              | 1        | 3.45%   |
| 4.4.189              | 1        | 3.45%   |
| 4.4.14               | 1        | 3.45%   |
| 4.20.11              | 1        | 3.45%   |
| 4.19.98-Unraid       | 1        | 3.45%   |
| 4.19.88-Unraid       | 1        | 3.45%   |
| 4.19.107-Unraid      | 1        | 3.45%   |
| 4.19.10              | 1        | 3.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.19.80  | 4        | 13.79%  |
| 5.10.28  | 3        | 10.34%  |
| 4.4.190  | 3        | 10.34%  |
| 4.4.240  | 2        | 6.9%    |
| 5.4.77   | 1        | 3.45%   |
| 5.4.53   | 1        | 3.45%   |
| 5.4.43   | 1        | 3.45%   |
| 5.4.0    | 1        | 3.45%   |
| 5.12.12  | 1        | 3.45%   |
| 5.10.44  | 1        | 3.45%   |
| 5.10.40  | 1        | 3.45%   |
| 4.9.248  | 1        | 3.45%   |
| 4.9.118  | 1        | 3.45%   |
| 4.4.261  | 1        | 3.45%   |
| 4.4.189  | 1        | 3.45%   |
| 4.4.14   | 1        | 3.45%   |
| 4.20.11  | 1        | 3.45%   |
| 4.19.98  | 1        | 3.45%   |
| 4.19.88  | 1        | 3.45%   |
| 4.19.107 | 1        | 3.45%   |
| 4.19.10  | 1        | 3.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.4     | 8        | 27.59%  |
| 4.19    | 8        | 27.59%  |
| 5.10    | 5        | 17.24%  |
| 5.4     | 4        | 13.79%  |
| 4.9     | 2        | 6.9%    |
| 5.12    | 1        | 3.45%   |
| 4.20    | 1        | 3.45%   |

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


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 17       | 58.62%  |
| XFCE    | 9        | 31.03%  |
| KDE5    | 1        | 3.45%   |
| KDE     | 1        | 3.45%   |
| fvwm    | 1        | 3.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 20       | 68.97%  |
| Unknown | 6        | 20.69%  |
| Tty     | 2        | 6.9%    |
| Wayland | 1        | 3.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 16       | 55.17%  |
| XDM     | 10       | 34.48%  |
| SDDM    | 2        | 6.9%    |
| SLiM    | 1        | 3.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 16       | 55.17%  |
| en_US   | 9        | 31.03%  |
| ru_RU   | 1        | 3.45%   |
| it_IT   | 1        | 3.45%   |
| en_GB   | 1        | 3.45%   |
| C       | 1        | 3.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 19       | 65.52%  |
| EFI  | 10       | 34.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 20       | 68.97%  |
| Btrfs    | 5        | 17.24%  |
| Xfs      | 2        | 6.9%    |
| Rootfs   | 1        | 3.45%   |
| Reiserfs | 1        | 3.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 17       | 58.62%  |
| MBR  | 12       | 41.38%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 62.07%  |
| Yes       | 11       | 37.93%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 65.52%  |
| Yes       | 10       | 34.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 11       | 37.93%  |
| Gigabyte Technology | 4        | 13.79%  |
| ASRock              | 3        | 10.34%  |
| Hewlett-Packard     | 2        | 6.9%    |
| Dell                | 2        | 6.9%    |
| Supermicro          | 1        | 3.45%   |
| Shuttle             | 1        | 3.45%   |
| MSI                 | 1        | 3.45%   |
| Intel               | 1        | 3.45%   |
| Huanan              | 1        | 3.45%   |
| HPE                 | 1        | 3.45%   |
| Foxconn             | 1        | 3.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 3        | 10.34%  |
| Supermicro ReadyDATA 5200           | 1        | 3.45%   |
| Shuttle NC03U                       | 1        | 3.45%   |
| MSI MS-7529                         | 1        | 3.45%   |
| Intel DZ77RE-75K AAG39010-302       | 1        | 3.45%   |
| Huanan X79-8D VAA31                 | 1        | 3.45%   |
| HPE ProLiant MicroServer Gen10 Plus | 1        | 3.45%   |
| HP Z620 Workstation                 | 1        | 3.45%   |
| HP 500-515na                        | 1        | 3.45%   |
| Gigabyte X150M-PRO ECC              | 1        | 3.45%   |
| Gigabyte N3160TN                    | 1        | 3.45%   |
| Gigabyte M61SME-S2                  | 1        | 3.45%   |
| Gigabyte 970A-DS3P                  | 1        | 3.45%   |
| Foxconn p6-2390                     | 1        | 3.45%   |
| Dell Precision WorkStation T3400    | 1        | 3.45%   |
| Dell Precision T3600                | 1        | 3.45%   |
| ASUS ROG STRIX X470-F GAMING        | 1        | 3.45%   |
| ASUS Pro WS X570-ACE                | 1        | 3.45%   |
| ASUS PRIME X370-PRO                 | 1        | 3.45%   |
| ASUS PRIME B450-PLUS                | 1        | 3.45%   |
| ASUS PRIME B350M-A                  | 1        | 3.45%   |
| ASUS P5QLD PRO                      | 1        | 3.45%   |
| ASUS M5A97 R2.0                     | 1        | 3.45%   |
| ASUS A68HM-PLUS                     | 1        | 3.45%   |
| ASRock Z390M-ITX/ac                 | 1        | 3.45%   |
| ASRock H87M Pro4                    | 1        | 3.45%   |
| ASRock H310CM-HDV                   | 1        | 3.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 3        | 10.34%  |
| ASUS All             | 3        | 10.34%  |
| Dell Precision       | 2        | 6.9%    |
| Supermicro ReadyDATA | 1        | 3.45%   |
| Shuttle NC03U        | 1        | 3.45%   |
| MSI MS-7529          | 1        | 3.45%   |
| Intel DZ77RE-75K     | 1        | 3.45%   |
| Huanan X79-8D        | 1        | 3.45%   |
| HPE ProLiant         | 1        | 3.45%   |
| HP Z620              | 1        | 3.45%   |
| HP 500-515na         | 1        | 3.45%   |
| Gigabyte X150M-PRO   | 1        | 3.45%   |
| Gigabyte N3160TN     | 1        | 3.45%   |
| Gigabyte M61SME-S2   | 1        | 3.45%   |
| Gigabyte 970A-DS3P   | 1        | 3.45%   |
| Foxconn p6-2390      | 1        | 3.45%   |
| ASUS ROG             | 1        | 3.45%   |
| ASUS Pro             | 1        | 3.45%   |
| ASUS P5QLD           | 1        | 3.45%   |
| ASUS M5A97           | 1        | 3.45%   |
| ASUS A68HM-PLUS      | 1        | 3.45%   |
| ASRock Z390M-ITX     | 1        | 3.45%   |
| ASRock H87M          | 1        | 3.45%   |
| ASRock H310CM-HDV    | 1        | 3.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 8        | 27.59%  |
| 2020 | 3        | 10.34%  |
| 2018 | 3        | 10.34%  |
| 2016 | 3        | 10.34%  |
| 2015 | 3        | 10.34%  |
| 2017 | 2        | 6.9%    |
| 2012 | 2        | 6.9%    |
| 2010 | 2        | 6.9%    |
| 2011 | 1        | 3.45%   |
| 2009 | 1        | 3.45%   |
| 2008 | 1        | 3.45%   |

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
| Disabled | 29       | 100%    |

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


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 8        | 27.59%  |
| 8.01-16.0   | 7        | 24.14%  |
| 32.01-64.0  | 4        | 13.79%  |
| 4.01-8.0    | 3        | 10.34%  |
| 3.01-4.0    | 3        | 10.34%  |
| 64.01-256.0 | 3        | 10.34%  |
| 24.01-32.0  | 1        | 3.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 10       | 33.33%  |
| 2.01-3.0   | 6        | 20%     |
| 4.01-8.0   | 4        | 13.33%  |
| 3.01-4.0   | 4        | 13.33%  |
| 24.01-32.0 | 2        | 6.67%   |
| 8.01-16.0  | 2        | 6.67%   |
| 16.01-24.0 | 1        | 3.33%   |
| 0.01-0.5   | 1        | 3.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 8        | 27.59%  |
| 3      | 6        | 20.69%  |
| 4      | 5        | 17.24%  |
| 5      | 3        | 10.34%  |
| 6      | 2        | 6.9%    |
| 2      | 2        | 6.9%    |
| 13     | 1        | 3.45%   |
| 7      | 1        | 3.45%   |
| 0      | 1        | 3.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 16       | 55.17%  |
| No        | 13       | 44.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 29       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 75.86%  |
| Yes       | 7        | 24.14%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 68.97%  |
| Yes       | 9        | 31.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 8        | 27.59%  |
| UK        | 5        | 17.24%  |
| Russia    | 3        | 10.34%  |
| Sweden    | 2        | 6.9%    |
| Germany   | 2        | 6.9%    |
| France    | 2        | 6.9%    |
| Canada    | 2        | 6.9%    |
| Spain     | 1        | 3.45%   |
| Portugal  | 1        | 3.45%   |
| Italy     | 1        | 3.45%   |
| Hong Kong | 1        | 3.45%   |
| Bulgaria  | 1        | 3.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Yekaterinburg         | 3        | 10.34%  |
| Caen                  | 2        | 6.9%    |
| Toronto               | 1        | 3.45%   |
| Tiffin                | 1        | 3.45%   |
| Stockholm             | 1        | 3.45%   |
| Springfield           | 1        | 3.45%   |
| Sidcup                | 1        | 3.45%   |
| Saedinenie            | 1        | 3.45%   |
| Paterson              | 1        | 3.45%   |
| Palma                 | 1        | 3.45%   |
| Ottawa                | 1        | 3.45%   |
| Oldham                | 1        | 3.45%   |
| Naples                | 1        | 3.45%   |
| Milwaukee             | 1        | 3.45%   |
| London                | 1        | 3.45%   |
| Lisbon                | 1        | 3.45%   |
| Lexington             | 1        | 3.45%   |
| Kowloon               | 1        | 3.45%   |
| Koblenz               | 1        | 3.45%   |
| Haar                  | 1        | 3.45%   |
| Enskede-Arsta-Vantoer | 1        | 3.45%   |
| Dallas                | 1        | 3.45%   |
| Chelmsford            | 1        | 3.45%   |
| Carrollton            | 1        | 3.45%   |
| Camp Hill             | 1        | 3.45%   |
| Barry                 | 1        | 3.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 33     | 25%     |
| Seagate             | 10       | 27     | 19.23%  |
| Samsung Electronics | 7        | 11     | 13.46%  |
| Toshiba             | 5        | 11     | 9.62%   |
| Kingston            | 3        | 3      | 5.77%   |
| Hitachi             | 3        | 3      | 5.77%   |
| Intel               | 2        | 2      | 3.85%   |
| A-DATA Technology   | 2        | 2      | 3.85%   |
| Team                | 1        | 1      | 1.92%   |
| SK Hynix            | 1        | 1      | 1.92%   |
| MAXTOR              | 1        | 1      | 1.92%   |
| Fujitsu             | 1        | 1      | 1.92%   |
| Crucial             | 1        | 1      | 1.92%   |
| China               | 1        | 2      | 1.92%   |
| Apple               | 1        | 2      | 1.92%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| WDC WD1003FZEX-00MK2A0 1TB                    | 2        | 2.63%   |
| Toshiba MQ01ABD100 1TB                        | 2        | 2.63%   |
| Seagate ST500DM002-1BD142 500GB               | 2        | 2.63%   |
| Seagate ST31000524AS 1TB                      | 2        | 2.63%   |
| WDC WDS100T2B0C-00PXH0 1TB                    | 1        | 1.32%   |
| WDC WD5000BPVT-2 500GB                        | 1        | 1.32%   |
| WDC WD5000BPKX-60HPJT0 500GB                  | 1        | 1.32%   |
| WDC WD5000AAKX-00ERMA0 500GB                  | 1        | 1.32%   |
| WDC WD5000AAKS-00V0A0 500GB                   | 1        | 1.32%   |
| WDC WD5000AAKS-00A7B2 500GB                   | 1        | 1.32%   |
| WDC WD40EFRX-68WT0N0 4TB                      | 1        | 1.32%   |
| WDC WD30EZRX-00SPEB0 3TB                      | 1        | 1.32%   |
| WDC WD30EZRX-00M                              | 1        | 1.32%   |
| WDC WD30EFRX-68EUZN0 3TB                      | 1        | 1.32%   |
| WDC WD30EFRX-68AX9N0 3TB                      | 1        | 1.32%   |
| WDC WD2003FZEX-0 2TB                          | 1        | 1.32%   |
| WDC WD1600AAJS-00PSA0 160GB                   | 1        | 1.32%   |
| WDC WD120EDAZ-11F3RA0 12TB                    | 1        | 1.32%   |
| WDC WD10EZRZ-00HTKB0 1TB                      | 1        | 1.32%   |
| WDC WD10EZEX-22BN5A0 1TB                      | 1        | 1.32%   |
| WDC WD10EZEX-00RKKA0 1TB                      | 1        | 1.32%   |
| WDC WD10EZEX-00BN5A0 1TB                      | 1        | 1.32%   |
| WDC WD10EURX-61C57Y0 1TB                      | 1        | 1.32%   |
| WDC WD10EALS-00Z8A0 1TB                       | 1        | 1.32%   |
| WDC WD100EMAZ-00WJTA0 10TB                    | 1        | 1.32%   |
| WDC WD1003FZEX-00K3CA0 1TB                    | 1        | 1.32%   |
| Toshiba MG07ACA12TE 12TB                      | 1        | 1.32%   |
| Toshiba HDWD110 1TB                           | 1        | 1.32%   |
| Toshiba DT01ACA200 2TB                        | 1        | 1.32%   |
| Toshiba DT01ACA100 1TB                        | 1        | 1.32%   |
| Team T253X1480G 480GB SSD                     | 1        | 1.32%   |
| SK Hynix SHGP31-1000GM-2 1TB                  | 1        | 1.32%   |
| Seagate ST980310AS 80GB                       | 1        | 1.32%   |
| Seagate ST4000VN008-2DR166 4TB                | 1        | 1.32%   |
| Seagate ST4000DM004-2CV104 4TB                | 1        | 1.32%   |
| Seagate ST380819AS 80GB                       | 1        | 1.32%   |
| Seagate ST380011A 80GB                        | 1        | 1.32%   |
| Seagate ST3500418AS 500GB                     | 1        | 1.32%   |
| Seagate ST3500410AS 500GB                     | 1        | 1.32%   |
| Seagate ST2000DM008-2FR102 2TB                | 1        | 1.32%   |
| Seagate ST2000DM001-1CH164 2TB                | 1        | 1.32%   |
| Seagate ST1000VM002-1SD102 1TB                | 1        | 1.32%   |
| Seagate ST1000NM0011 1TB                      | 1        | 1.32%   |
| Seagate ST1000NM0001 1TB                      | 1        | 1.32%   |
| Seagate ST1000DM010-2EP102 1TB                | 1        | 1.32%   |
| Seagate ST1000DM003-1ER162 1TB                | 1        | 1.32%   |
| Seagate DKS2D-H3R0SS 3TB                      | 1        | 1.32%   |
| Samsung SSD 970 EVO Plus 1TB                  | 1        | 1.32%   |
| Samsung SSD 970 EVO 250GB                     | 1        | 1.32%   |
| Samsung SSD 860 EVO 1TB                       | 1        | 1.32%   |
| Samsung SSD 850 PRO 512GB                     | 1        | 1.32%   |
| Samsung SSD 850 PRO 256GB                     | 1        | 1.32%   |
| Samsung SSD 750 EVO 250GB                     | 1        | 1.32%   |
| Samsung NVMe SSD Controller SM981/PM981 512GB | 1        | 1.32%   |
| Samsung HD501LJ 500GB                         | 1        | 1.32%   |
| Samsung HD160JJ/ 160GB                        | 1        | 1.32%   |
| MAXTOR 4G120J6 128GB                          | 1        | 1.32%   |
| Kingston SUV500MS120G 120GB SSD               | 1        | 1.32%   |
| Kingston SUV400S37120G 120GB SSD              | 1        | 1.32%   |
| Kingston SA400S37240G 240GB SSD               | 1        | 1.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 32     | 37.14%  |
| Seagate             | 10       | 23     | 28.57%  |
| Toshiba             | 5        | 11     | 14.29%  |
| Hitachi             | 3        | 3      | 8.57%   |
| Samsung Electronics | 2        | 2      | 5.71%   |
| MAXTOR              | 1        | 1      | 2.86%   |
| Fujitsu             | 1        | 1      | 2.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 5      | 25%     |
| Kingston            | 3        | 3      | 25%     |
| Team                | 1        | 1      | 8.33%   |
| Intel               | 1        | 1      | 8.33%   |
| Crucial             | 1        | 1      | 8.33%   |
| China               | 1        | 2      | 8.33%   |
| Apple               | 1        | 2      | 8.33%   |
| A-DATA Technology   | 1        | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 24       | 73     | 55.81%  |
| SSD     | 11       | 16     | 25.58%  |
| NVMe    | 7        | 8      | 16.28%  |
| Unknown | 1        | 4      | 2.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 26       | 85     | 76.47%  |
| NVMe | 7        | 8      | 20.59%  |
| SAS  | 1        | 8      | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 18       | 32     | 41.86%  |
| 0.51-1.0   | 12       | 33     | 27.91%  |
| 2.01-3.0   | 4        | 8      | 9.3%    |
| 1.01-2.0   | 4        | 5      | 9.3%    |
| 3.01-4.0   | 2        | 5      | 4.65%   |
| 10.01-20.0 | 2        | 5      | 4.65%   |
| 4.01-10.0  | 1        | 1      | 2.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 8        | 27.59%  |
| 1001-2000  | 5        | 17.24%  |
| 501-1000   | 5        | 17.24%  |
| 2001-3000  | 3        | 10.34%  |
| 101-250    | 3        | 10.34%  |
| 251-500    | 2        | 6.9%    |
| 51-100     | 2        | 6.9%    |
| 21-50      | 1        | 3.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| Unknown   | 8        | 27.59%  |
| 501-1000  | 5        | 17.24%  |
| 101-250   | 4        | 13.79%  |
| 51-100    | 4        | 13.79%  |
| 251-500   | 3        | 10.34%  |
| 1001-2000 | 2        | 6.9%    |
| 1-20      | 2        | 6.9%    |
| 21-50     | 1        | 3.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC WD5000BPKX-60HPJT0 500GB   | 1        | 1      | 5.56%   |
| WDC WD5000AAKX-00ERMA0 500GB   | 1        | 1      | 5.56%   |
| WDC WD5000AAKS-00A7B2 500GB    | 1        | 1      | 5.56%   |
| WDC WD40EFRX-68WT0N0 4TB       | 1        | 2      | 5.56%   |
| WDC WD30EZRX-00M               | 1        | 1      | 5.56%   |
| WDC WD30EFRX-68AX9N0 3TB       | 1        | 4      | 5.56%   |
| WDC WD10EZEX-00RKKA0 1TB       | 1        | 1      | 5.56%   |
| WDC WD10EALS-00Z8A0 1TB        | 1        | 2      | 5.56%   |
| WDC WD1003FZEX-00MK2A0 1TB     | 1        | 2      | 5.56%   |
| Seagate ST380011A 80GB         | 1        | 1      | 5.56%   |
| Seagate ST3500418AS 500GB      | 1        | 1      | 5.56%   |
| Seagate ST3500410AS 500GB      | 1        | 1      | 5.56%   |
| Seagate ST31000524AS 1TB       | 1        | 1      | 5.56%   |
| Seagate ST1000VM002-1SD102 1TB | 1        | 1      | 5.56%   |
| Seagate ST1000NM0011 1TB       | 1        | 2      | 5.56%   |
| MAXTOR 4G120J6 128GB           | 1        | 1      | 5.56%   |
| Intel SSDSA2M080G2GC 80GB      | 1        | 1      | 5.56%   |
| Hitachi HDS721050CLA660 500GB  | 1        | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 7        | 15     | 43.75%  |
| Seagate | 6        | 7      | 37.5%   |
| MAXTOR  | 1        | 1      | 6.25%   |
| Intel   | 1        | 1      | 6.25%   |
| Hitachi | 1        | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 7        | 15     | 46.67%  |
| Seagate | 6        | 7      | 40%     |
| MAXTOR  | 1        | 1      | 6.67%   |
| Hitachi | 1        | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 14       | 24     | 93.33%  |
| SSD  | 1        | 1      | 6.67%   |

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
| Works    | 25       | 68     | 60.98%  |
| Malfunc  | 15       | 25     | 36.59%  |
| Detected | 1        | 8      | 2.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 19       | 42.22%  |
| AMD                      | 9        | 20%     |
| Samsung Electronics      | 4        | 8.89%   |
| ASMedia Technology       | 3        | 6.67%   |
| Marvell Technology Group | 2        | 4.44%   |
| SK Hynix                 | 1        | 2.22%   |
| Silicon Image            | 1        | 2.22%   |
| Sandisk                  | 1        | 2.22%   |
| Realtek Semiconductor    | 1        | 2.22%   |
| Nvidia                   | 1        | 2.22%   |
| JMicron Technology       | 1        | 2.22%   |
| Broadcom / LSI           | 1        | 2.22%   |
| 3ware                    | 1        | 2.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 7        | 12.28%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3        | 5.26%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 3        | 5.26%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 3        | 5.26%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2        | 3.51%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 2        | 3.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2        | 3.51%   |
| AMD 400 Series Chipset SATA Controller                                           | 2        | 3.51%   |
| SK Hynix Gold P31 SSD                                                            | 1        | 1.75%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 1        | 1.75%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1        | 1.75%   |
| Samsung Apple PCIe SSD                                                           | 1        | 1.75%   |
| Realtek Realtek Non-Volatile memory controller                                   | 1        | 1.75%   |
| Nvidia MCP61 SATA Controller                                                     | 1        | 1.75%   |
| Nvidia MCP61 IDE                                                                 | 1        | 1.75%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 1        | 1.75%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                          | 1        | 1.75%   |
| JMicron JMB368 IDE controller                                                    | 1        | 1.75%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1        | 1.75%   |
| Intel SSD 600P Series                                                            | 1        | 1.75%   |
| Intel SATA Controller [RAID mode]                                                | 1        | 1.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1        | 1.75%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1        | 1.75%   |
| Intel C608 chipset Dual 4-Port SATA/SAS Storage Control Unit                     | 1        | 1.75%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 1        | 1.75%   |
| Intel C600/X79 series chipset IDE-r Controller                                   | 1        | 1.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1        | 1.75%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1        | 1.75%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1        | 1.75%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1        | 1.75%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1        | 1.75%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]    | 1        | 1.75%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]    | 1        | 1.75%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1        | 1.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1        | 1.75%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 1        | 1.75%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 1        | 1.75%   |
| ASMedia 106x SATA/RAID Controller                                                | 1        | 1.75%   |
| AMD X370 Series Chipset SATA Controller                                          | 1        | 1.75%   |
| AMD 300 Series Chipset SATA Controller                                           | 1        | 1.75%   |
| 3ware 9650SE SATA-II RAID PCIe                                                   | 1        | 1.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 25       | 58.14%  |
| NVMe | 7        | 16.28%  |
| IDE  | 5        | 11.63%  |
| RAID | 3        | 6.98%   |
| SAS  | 3        | 6.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 19       | 65.52%  |
| AMD    | 10       | 34.48%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Intel Core i7-4790K CPU @ 4.00GHz          | 2        | 6.9%    |
| AMD Ryzen 5 3600 6-Core Processor          | 2        | 6.9%    |
| AMD FX-8350 Eight-Core Processor           | 2        | 6.9%    |
| Intel Xeon CPU X3450 @ 2.67GHz             | 1        | 3.45%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz         | 1        | 3.45%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz         | 1        | 3.45%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz         | 1        | 3.45%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz        | 1        | 3.45%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz     | 1        | 3.45%   |
| Intel Pentium CPU G640 @ 2.80GHz           | 1        | 3.45%   |
| Intel Pentium CPU G4560 @ 3.50GHz          | 1        | 3.45%   |
| Intel Core i7-9700 CPU @ 3.00GHz           | 1        | 3.45%   |
| Intel Core i5-9400 CPU @ 2.90GHz           | 1        | 3.45%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 1        | 3.45%   |
| Intel Core i5-4690 CPU @ 3.50GHz           | 1        | 3.45%   |
| Intel Core i5-3470 CPU @ 3.20GHz           | 1        | 3.45%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz      | 1        | 3.45%   |
| Intel Core 2 Quad CPU Q6700 @ 2.66GHz      | 1        | 3.45%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz       | 1        | 3.45%   |
| Intel Celeron CPU N3160 @ 1.60GHz          | 1        | 3.45%   |
| AMD Ryzen 9 3950X 16-Core Processor        | 1        | 3.45%   |
| AMD Ryzen 7 3800X 8-Core Processor         | 1        | 3.45%   |
| AMD Ryzen 7 1700X Eight-Core Processor     | 1        | 3.45%   |
| AMD Athlon 64 X2 Dual Core Processor 5200+ | 1        | 3.45%   |
| AMD A4-7300 APU with Radeon HD Graphics    | 1        | 3.45%   |
| AMD A10-5700 APU with Radeon HD Graphics   | 1        | 3.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Xeon         | 5        | 17.24%  |
| Intel Core i5      | 4        | 13.79%  |
| Intel Core i7      | 3        | 10.34%  |
| Intel Pentium      | 2        | 6.9%    |
| Intel Core 2 Quad  | 2        | 6.9%    |
| AMD Ryzen 7        | 2        | 6.9%    |
| AMD Ryzen 5        | 2        | 6.9%    |
| AMD FX             | 2        | 6.9%    |
| Intel Pentium Gold | 1        | 3.45%   |
| Intel Core 2 Duo   | 1        | 3.45%   |
| Intel Celeron      | 1        | 3.45%   |
| AMD Ryzen 9        | 1        | 3.45%   |
| AMD Athlon 64 X2   | 1        | 3.45%   |
| AMD A4             | 1        | 3.45%   |
| AMD A10            | 1        | 3.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 11       | 37.93%  |
| 2      | 7        | 24.14%  |
| 6      | 4        | 13.79%  |
| 8      | 3        | 10.34%  |
| 16     | 2        | 6.9%    |
| 12     | 1        | 3.45%   |
| 1      | 1        | 3.45%   |

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
| 2      | 19       | 65.52%  |
| 1      | 10       | 34.48%  |

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
| 0x306c3    | 3        | 10.34%  |
| 0x206d7    | 3        | 10.34%  |
| 0x906ed    | 2        | 6.9%    |
| 0x1067a    | 2        | 6.9%    |
| 0x08701013 | 2        | 6.9%    |
| 0x06001119 | 2        | 6.9%    |
| 0x906ea    | 1        | 3.45%   |
| 0x406c4    | 1        | 3.45%   |
| 0x306a9    | 1        | 3.45%   |
| 0x206a7    | 1        | 3.45%   |
| 0x106e5    | 1        | 3.45%   |
| 0x08701021 | 1        | 3.45%   |
| 0x08001138 | 1        | 3.45%   |
| 0x06000852 | 1        | 3.45%   |
| 0x06000822 | 1        | 3.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 5        | 17.24%  |
| Zen 2       | 4        | 13.79%  |
| SandyBridge | 4        | 13.79%  |
| Piledriver  | 4        | 13.79%  |
| Haswell     | 4        | 13.79%  |
| Penryn      | 2        | 6.9%    |
| Zen         | 1        | 3.45%   |
| Silvermont  | 1        | 3.45%   |
| Nehalem     | 1        | 3.45%   |
| K8 Hammer   | 1        | 3.45%   |
| IvyBridge   | 1        | 3.45%   |
| Core        | 1        | 3.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 10       | 35.71%  |
| Nvidia                     | 8        | 28.57%  |
| Intel                      | 8        | 28.57%  |
| Matrox Electronics Systems | 2        | 7.14%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3        | 10.34%  |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2        | 6.9%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 3.45%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 3.45%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 3.45%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 3.45%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 3.45%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1        | 3.45%   |
| Nvidia GK104GL [Quadro K5000]                                                            | 1        | 3.45%   |
| Nvidia G80GL [Quadro FX 4600]                                                            | 1        | 3.45%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 3.45%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 1        | 3.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1        | 3.45%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 1        | 3.45%   |
| Intel HD Graphics 620                                                                    | 1        | 3.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 3.45%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 3.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 3.45%   |
| AMD Richland [Radeon HD 8470D]                                                           | 1        | 3.45%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 1        | 3.45%   |
| AMD Oland PRO [Radeon R7 240/340]                                                        | 1        | 3.45%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 1        | 3.45%   |
| AMD Cypress XT [Radeon HD 5870]                                                          | 1        | 3.45%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                                       | 1        | 3.45%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 1        | 3.45%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 1        | 3.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x AMD    | 10       | 34.48%  |
| 1 x Nvidia | 8        | 27.59%  |
| 1 x Intel  | 8        | 27.59%  |
| 1 x Matrox | 2        | 6.9%    |
| Other      | 1        | 3.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 16       | 55.17%  |
| Proprietary | 8        | 27.59%  |
| Unknown     | 5        | 17.24%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 13       | 44.83%  |
| 3.01-4.0   | 5        | 17.24%  |
| 0.51-1.0   | 5        | 17.24%  |
| 1.01-2.0   | 4        | 13.79%  |
| 7.01-8.0   | 2        | 6.9%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 4        | 14.29%  |
| Hewlett-Packard      | 3        | 10.71%  |
| Goldstar             | 3        | 10.71%  |
| ViewSonic            | 2        | 7.14%   |
| Samsung Electronics  | 2        | 7.14%   |
| BenQ                 | 2        | 7.14%   |
| Acer                 | 2        | 7.14%   |
| Xiaomi               | 1        | 3.57%   |
| Toshiba              | 1        | 3.57%   |
| NEC Computers        | 1        | 3.57%   |
| Lenovo               | 1        | 3.57%   |
| JVC                  | 1        | 3.57%   |
| Iiyama               | 1        | 3.57%   |
| Gigabyte Technology  | 1        | 3.57%   |
| Eizo                 | 1        | 3.57%   |
| ASUSTek Computer     | 1        | 3.57%   |
| Ancor Communications | 1        | 3.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Xiaomi Mi TV XMD009A 2880x1800 480x270mm 21.7-inch                   | 1        | 3.33%   |
| ViewSonic LCD Monitor VX2276 Series 1920x1080                        | 1        | 3.33%   |
| ViewSonic LCD Monitor VA2448 SERIES 1920x1080                        | 1        | 3.33%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                     | 1        | 3.33%   |
| Samsung Electronics SyncMaster SAM0578 1920x1080 476x268mm 21.5-inch | 1        | 3.33%   |
| Samsung Electronics SMB2430L SAM0644 1920x1080 521x293mm 23.5-inch   | 1        | 3.33%   |
| NEC Computers LCD2490WUXi NEC66CE 1920x1200 518x324mm 24.1-inch      | 1        | 3.33%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch             | 1        | 3.33%   |
| JVC FPDEUFT3 JVC21BE 1920x540                                        | 1        | 3.33%   |
| Iiyama PLE2207WS IVM5609 1680x1050 474x296mm 22.0-inch               | 1        | 3.33%   |
| Hewlett-Packard ZR2740w HWP2957 2560x1440 597x336mm 27.0-inch        | 1        | 3.33%   |
| Hewlett-Packard LE1851w HWP2840 1366x768 413x234mm 18.7-inch         | 1        | 3.33%   |
| Hewlett-Packard 2309 HWP2823 1920x1080 510x287mm 23.0-inch           | 1        | 3.33%   |
| Goldstar W2242 GSM5678 1680x1050 474x296mm 22.0-inch                 | 1        | 3.33%   |
| Goldstar W2242 GSM5677 1680x1050 474x296mm 22.0-inch                 | 1        | 3.33%   |
| Goldstar FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch               | 1        | 3.33%   |
| Goldstar BK750Y GSM5B3E 1920x1080 600x340mm 27.2-inch                | 1        | 3.33%   |
| Goldstar BK750Y GSM5B3D 1920x1080 480x270mm 21.7-inch                | 1        | 3.33%   |
| Gigabyte Technology G27Q GBT2709 2560x1440 598x336mm 27.0-inch       | 1        | 3.33%   |
| Eizo M1700 ENC1788 1280x1024 338x271mm 17.1-inch                     | 1        | 3.33%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 1        | 3.33%   |
| Dell LCD Monitor U2312HM 1920x1080                                   | 1        | 3.33%   |
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                    | 1        | 3.33%   |
| Dell 1905FP DEL400D 1280x1024 376x301mm 19.0-inch                    | 1        | 3.33%   |
| BenQ EW2420 BNQ7923 1920x1080 530x300mm 24.0-inch                    | 1        | 3.33%   |
| BenQ BenQG2222HDL BNQ785A 1920x1080 478x269mm 21.6-inch              | 1        | 3.33%   |
| ASUSTek Computer VA24DQLB AUS2482 1920x1080 527x296mm 23.8-inch      | 1        | 3.33%   |
| Ancor Communications VG248 ACI24E1 1680x1050 530x300mm 24.0-inch     | 1        | 3.33%   |
| Acer K222HQL ACR040D 1920x1080 480x270mm 21.7-inch                   | 1        | 3.33%   |
| Acer AL171 ACRAD18 1280x1024 338x270mm 17.0-inch                     | 1        | 3.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 14       | 51.85%  |
| 1280x1024 (SXGA)   | 4        | 14.81%  |
| 2560x1440 (QHD)    | 2        | 7.41%   |
| 1920x1200 (WUXGA)  | 2        | 7.41%   |
| 1680x1050 (WSXGA+) | 2        | 7.41%   |
| 2880x1800          | 1        | 3.7%    |
| 1920x540           | 1        | 3.7%    |
| 1366x768 (WXGA)    | 1        | 3.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 5        | 17.24%  |
| 27      | 4        | 13.79%  |
| 24      | 4        | 13.79%  |
| 23      | 4        | 13.79%  |
| Unknown | 4        | 13.79%  |
| 17      | 3        | 10.34%  |
| 74      | 1        | 3.45%   |
| 22      | 1        | 3.45%   |
| 19      | 1        | 3.45%   |
| 18      | 1        | 3.45%   |
| 15      | 1        | 3.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 11       | 37.93%  |
| 401-500     | 8        | 27.59%  |
| 301-350     | 4        | 13.79%  |
| Unknown     | 4        | 13.79%  |
| 351-400     | 1        | 3.45%   |
| 1501-2000   | 1        | 3.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 13       | 50%     |
| 16/10   | 4        | 15.38%  |
| Unknown | 3        | 11.54%  |
| 6/5     | 2        | 7.69%   |
| 5/4     | 2        | 7.69%   |
| 32/9    | 1        | 3.85%   |
| 3/2     | 1        | 3.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 11       | 39.29%  |
| 301-350        | 4        | 14.29%  |
| 141-150        | 4        | 14.29%  |
| Unknown        | 4        | 14.29%  |
| 251-300        | 2        | 7.14%   |
| More than 1000 | 1        | 3.57%   |
| 151-200        | 1        | 3.57%   |
| 101-110        | 1        | 3.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 15       | 51.72%  |
| 101-120 | 7        | 24.14%  |
| Unknown | 4        | 13.79%  |
| 121-160 | 2        | 6.9%    |
| 1-50    | 1        | 3.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 16       | 55.17%  |
| 0     | 6        | 20.69%  |
| 2     | 5        | 17.24%  |
| 3     | 2        | 6.9%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 15       | 40.54%  |
| Realtek Semiconductor    | 13       | 35.14%  |
| VIA Technologies         | 1        | 2.7%    |
| TP-Link                  | 1        | 2.7%    |
| Ralink Technology        | 1        | 2.7%    |
| Ralink                   | 1        | 2.7%    |
| Qualcomm Atheros         | 1        | 2.7%    |
| Nvidia                   | 1        | 2.7%    |
| Micro Star International | 1        | 2.7%    |
| Chelsio Communications   | 1        | 2.7%    |
| Broadcom                 | 1        | 2.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 11       | 24.44%  |
| Intel I211 Gigabit Network Connection                                         | 5        | 11.11%  |
| Intel 82574L Gigabit Network Connection                                       | 4        | 8.89%   |
| Intel Ethernet Connection (2) I218-V                                          | 3        | 6.67%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 4.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 4.44%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 1        | 2.22%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                         | 1        | 2.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1        | 2.22%   |
| Ralink MT7601U Wireless Adapter                                               | 1        | 2.22%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1        | 2.22%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 2.22%   |
| Nvidia MCP61 Ethernet                                                         | 1        | 2.22%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]    | 1        | 2.22%   |
| Intel I350 Gigabit Network Connection                                         | 1        | 2.22%   |
| Intel Ethernet Connection I217-V                                              | 1        | 2.22%   |
| Intel Ethernet Connection (7) I219-V                                          | 1        | 2.22%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 2.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1        | 2.22%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 2.22%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 2.22%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 2.22%   |
| Chelsio T320 10GbE Dual Port Adapter                                          | 1        | 2.22%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 1        | 2.22%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 2        | 28.57%  |
| TP-Link                  | 1        | 14.29%  |
| Ralink Technology        | 1        | 14.29%  |
| Ralink                   | 1        | 14.29%  |
| Micro Star International | 1        | 14.29%  |
| Intel                    | 1        | 14.29%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EE Wireless Network Adapter                                 | 2        | 28.57%  |
| TP-Link RTL8812AU Archer T4U 802.11ac                                      | 1        | 14.29%  |
| Ralink MT7601U Wireless Adapter                                            | 1        | 14.29%  |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                  | 1        | 14.29%  |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1        | 14.29%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 1        | 14.29%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 15       | 46.88%  |
| Realtek Semiconductor  | 12       | 37.5%   |
| VIA Technologies       | 1        | 3.13%   |
| Qualcomm Atheros       | 1        | 3.13%   |
| Nvidia                 | 1        | 3.13%   |
| Chelsio Communications | 1        | 3.13%   |
| Broadcom               | 1        | 3.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 11       | 28.95%  |
| Intel I211 Gigabit Network Connection                                         | 5        | 13.16%  |
| Intel 82574L Gigabit Network Connection                                       | 4        | 10.53%  |
| Intel Ethernet Connection (2) I218-V                                          | 3        | 7.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 5.26%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 1        | 2.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1        | 2.63%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 2.63%   |
| Nvidia MCP61 Ethernet                                                         | 1        | 2.63%   |
| Intel I350 Gigabit Network Connection                                         | 1        | 2.63%   |
| Intel Ethernet Connection I217-V                                              | 1        | 2.63%   |
| Intel Ethernet Connection (7) I219-V                                          | 1        | 2.63%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 2.63%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 2.63%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 2.63%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 2.63%   |
| Chelsio T320 10GbE Dual Port Adapter                                          | 1        | 2.63%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 1        | 2.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 29       | 80.56%  |
| WiFi     | 7        | 19.44%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 24       | 96%     |
| WiFi     | 1        | 4%      |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 15       | 51.72%  |
| 2     | 8        | 27.59%  |
| 4     | 2        | 6.9%    |
| 3     | 2        | 6.9%    |
| 5     | 1        | 3.45%   |
| 0     | 1        | 3.45%   |

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


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Cambridge Silicon Radio  | 6        | 66.67%  |
| Micro Star International | 1        | 11.11%  |
| Intel                    | 1        | 11.11%  |
| Broadcom                 | 1        | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 66.67%  |
| Micro Star International Bluetooth Device           | 1        | 11.11%  |
| Intel Bluetooth Device                              | 1        | 11.11%  |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 11.11%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 17       | 41.46%  |
| AMD                 | 12       | 29.27%  |
| Nvidia              | 7        | 17.07%  |
| Creative Labs       | 3        | 7.32%   |
| EGO SYStems         | 1        | 2.44%   |
| C-Media Electronics | 1        | 2.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                          | 4        | 8%      |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 3        | 6%      |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3        | 6%      |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3        | 6%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3        | 6%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2        | 4%      |
| AMD FCH Azalia Controller                                                                         | 2        | 4%      |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2        | 4%      |
| Nvidia TU116 High Definition Audio Controller                                                     | 1        | 2%      |
| Nvidia MCP61 High Definition Audio                                                                | 1        | 2%      |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1        | 2%      |
| Nvidia GM206 High Definition Audio Controller                                                     | 1        | 2%      |
| Nvidia GM204 High Definition Audio Controller                                                     | 1        | 2%      |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1        | 2%      |
| Nvidia GK107 HDMI Audio Controller                                                                | 1        | 2%      |
| Nvidia GK104 HDMI Audio Controller                                                                | 1        | 2%      |
| Intel Sunrise Point-LP HD Audio                                                                   | 1        | 2%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1        | 2%      |
| Intel Cannon Lake PCH cAVS                                                                        | 1        | 2%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 2%      |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1        | 2%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1        | 2%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1        | 2%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1        | 2%      |
| Intel 200 Series PCH HD Audio                                                                     | 1        | 2%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1        | 2%      |
| EGO SYStems U24XL                                                                                 | 1        | 2%      |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 1        | 2%      |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                                                 | 1        | 2%      |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                | 1        | 2%      |
| C-Media Electronics USB Audio Device                                                              | 1        | 2%      |
| AMD Trinity HDMI Audio Controller                                                                 | 1        | 2%      |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1        | 2%      |
| AMD Navi 10 HDMI Audio                                                                            | 1        | 2%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1        | 2%      |
| AMD Cypress HDMI Audio [Radeon HD 5830/5850/5870 / 6850/6870 Rebrand]                             | 1        | 2%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 6        | 20%     |
| Corsair             | 6        | 20%     |
| Unknown             | 4        | 13.33%  |
| Crucial             | 4        | 13.33%  |
| SK Hynix            | 3        | 10%     |
| Micron Technology   | 2        | 6.67%   |
| Transcend           | 1        | 3.33%   |
| Team                | 1        | 3.33%   |
| Samsung Electronics | 1        | 3.33%   |
| HPE                 | 1        | 3.33%   |
| AMD                 | 1        | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM DDR3 65535MT/s              | 1        | 2.86%   |
| Unknown RAM Module 2048MB DIMM SDRAM                       | 1        | 2.86%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                 | 1        | 2.86%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                     | 1        | 2.86%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                 | 1        | 2.86%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                     | 1        | 2.86%   |
| Transcend RAM TS256MLQ72V6U 2048MB DIMM DDR2 667MT/s       | 1        | 2.86%   |
| Team RAM TEAMGROUP-UD4-3200 16384MB DIMM DDR4 3200MT/s     | 1        | 2.86%   |
| SK Hynix RAM HMT41GU6BFR8A-PB 8192MB DIMM DDR3 2000MT/s    | 1        | 2.86%   |
| SK Hynix RAM HMT351R7CFR8A-H9 4096MB DIMM DDR3 1333MT/s    | 1        | 2.86%   |
| SK Hynix RAM HMT31GR7EFR4A 8192MB DIMM DDR3 1600MT/s       | 1        | 2.86%   |
| Samsung RAM M393B5273DH0-CK0 4GB DIMM DDR3 1600MT/s        | 1        | 2.86%   |
| Micron RAM 36KSF1G72PZ-1G4K1 8192MB DIMM DDR3 1333MT/s     | 1        | 2.86%   |
| Micron RAM 18JSF1G72PZ-1G9E1 8192MB DIMM DDR3 1866MT/s     | 1        | 2.86%   |
| Micron RAM 16JTF51264AZ-1G6M1 4096MB DIMM DDR3 1600MT/s    | 1        | 2.86%   |
| Kingston RAM KHX3600C17D4/8GX 8GB DIMM DDR4 3600MT/s       | 1        | 2.86%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1867MT/s        | 1        | 2.86%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s   | 1        | 2.86%   |
| Kingston RAM 99U5471-037.A00LF 8192MB DIMM DDR3 1600MT/s   | 1        | 2.86%   |
| Kingston RAM 99U5471-012.A00LF 4096MB DIMM DDR3 1600MT/s   | 1        | 2.86%   |
| Kingston RAM 9965669-009.A00G 8192MB DIMM DDR4 2133MT/s    | 1        | 2.86%   |
| Kingston RAM 9905663-031.A00G 16384MB SODIMM DDR4 2400MT/s | 1        | 2.86%   |
| HPE RAM 879526-091 8192MB DIMM DDR4 2666MT/s               | 1        | 2.86%   |
| Crucial RAM BLT4G3D1869DT1TX0. 4GB DIMM DDR3 1867MT/s      | 1        | 2.86%   |
| Crucial RAM BLT4G3D1608DT1TX0. 4GB DIMM DDR3 1600MT/s      | 1        | 2.86%   |
| Crucial RAM BLS8G4D32AESBK.M8FE1 8GB DIMM DDR4 3600MT/s    | 1        | 2.86%   |
| Crucial RAM BLS8G4D240FSB.16FBD2 8GB DIMM DDR4 2400MT/s    | 1        | 2.86%   |
| Crucial RAM BLS16G4D26BFSC.16FD 16384MB DIMM DDR4 2666MT/s | 1        | 2.86%   |
| Corsair RAM CMZ32GX3M4X1600C10 8192MB DIMM DDR3 1600MT/s   | 1        | 2.86%   |
| Corsair RAM CMY32GX3M4A16 8192MB DIMM DDR3 667MT/s         | 1        | 2.86%   |
| Corsair RAM CMY16GX3M2A2400C11 8192MB DIMM DDR3 2400MT/s   | 1        | 2.86%   |
| Corsair RAM CML16GX3M2A1600C10 8192MB DIMM DDR3 1600MT/s   | 1        | 2.86%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s     | 1        | 2.86%   |
| Corsair RAM CMK16GX4M1A2666C16 16384MB DIMM DDR4 2667MT/s  | 1        | 2.86%   |
| AMD RAM R534G1601S1SL 4096MB DIMM DDR3 1600MT/s            | 1        | 2.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 15       | 51.72%  |
| DDR4    | 10       | 34.48%  |
| SDRAM   | 1        | 3.45%   |
| DDR2    | 1        | 3.45%   |
| DDR     | 1        | 3.45%   |
| Unknown | 1        | 3.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 28       | 96.55%  |
| SODIMM | 1        | 3.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 14       | 43.75%  |
| 4096  | 7        | 21.88%  |
| 2048  | 4        | 12.5%   |
| 16384 | 3        | 9.38%   |
| 32768 | 2        | 6.25%   |
| 1024  | 2        | 6.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 9        | 28.13%  |
| 2400    | 3        | 9.38%   |
| 667     | 3        | 9.38%   |
| 3600    | 2        | 6.25%   |
| 3200    | 2        | 6.25%   |
| 2666    | 2        | 6.25%   |
| 1867    | 2        | 6.25%   |
| 1333    | 2        | 6.25%   |
| 65535   | 1        | 3.13%   |
| 2667    | 1        | 3.13%   |
| 2133    | 1        | 3.13%   |
| 2000    | 1        | 3.13%   |
| 1866    | 1        | 3.13%   |
| 800     | 1        | 3.13%   |
| Unknown | 1        | 3.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 2        | 40%     |
| Brother Industries | 2        | 40%     |
| Dell               | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| HP ENVY 4520 series      | 1        | 20%     |
| HP ENVY 4500 series      | 1        | 20%     |
| Dell 2330d Laser Printer | 1        | 20%     |
| Brother Printer          | 1        | 20%     |
| Brother HL-L2320D series | 1        | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model           | Desktops | Percent |
|-----------------|----------|---------|
| HP ScanJet 5590 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Logitech | 4        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech Webcam C300        | 1        | 25%     |
| Logitech Webcam C170        | 1        | 25%     |
| Logitech HD Webcam C525     | 1        | 25%     |
| Logitech HD Pro Webcam C920 | 1        | 25%     |

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
| 1     | 4        | 13.79%  |
| 2     | 3        | 10.34%  |
| 3     | 2        | 6.9%    |
| 4     | 1        | 3.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 5        | 27.78%  |
| Sound                    | 4        | 22.22%  |
| Communication controller | 3        | 16.67%  |
| Net/wireless             | 2        | 11.11%  |
| Unassigned class         | 1        | 5.56%   |
| Storage/ata              | 1        | 5.56%   |
| Card reader              | 1        | 5.56%   |
| Bluetooth                | 1        | 5.56%   |

