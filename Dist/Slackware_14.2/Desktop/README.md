Slackware 14.2 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Slackware 14.2.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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
| HP         | 21B4 A01                    | [871b196cc2](https://linux-hardware.org/?probe=871b196cc2) | Nov 21, 2021 |
| HP         | 21B4 A01                    | [259232d98b](https://linux-hardware.org/?probe=259232d98b) | Nov 21, 2021 |
| Supermicro | X9DA7/E                     | [3fc1ef2b58](https://linux-hardware.org/?probe=3fc1ef2b58) | Nov 09, 2021 |
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
| 5.10.28-Unraid       | 5        | 16.13%  |
| 4.19.80              | 4        | 12.9%   |
| 4.4.190              | 3        | 9.68%   |
| 4.4.240              | 2        | 6.45%   |
| 5.4.77               | 1        | 3.23%   |
| 5.4.53-APRL          | 1        | 3.23%   |
| 5.4.43               | 1        | 3.23%   |
| 5.4.0-rc2-vto        | 1        | 3.23%   |
| 5.12.12              | 1        | 3.23%   |
| 5.10.44-slack64-host | 1        | 3.23%   |
| 5.10.40              | 1        | 3.23%   |
| 4.9.248.a            | 1        | 3.23%   |
| 4.9.118              | 1        | 3.23%   |
| 4.4.261              | 1        | 3.23%   |
| 4.4.189              | 1        | 3.23%   |
| 4.4.14               | 1        | 3.23%   |
| 4.20.11              | 1        | 3.23%   |
| 4.19.98-Unraid       | 1        | 3.23%   |
| 4.19.88-Unraid       | 1        | 3.23%   |
| 4.19.107-Unraid      | 1        | 3.23%   |
| 4.19.10              | 1        | 3.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.28  | 5        | 16.13%  |
| 4.19.80  | 4        | 12.9%   |
| 4.4.190  | 3        | 9.68%   |
| 4.4.240  | 2        | 6.45%   |
| 5.4.77   | 1        | 3.23%   |
| 5.4.53   | 1        | 3.23%   |
| 5.4.43   | 1        | 3.23%   |
| 5.4.0    | 1        | 3.23%   |
| 5.12.12  | 1        | 3.23%   |
| 5.10.44  | 1        | 3.23%   |
| 5.10.40  | 1        | 3.23%   |
| 4.9.248  | 1        | 3.23%   |
| 4.9.118  | 1        | 3.23%   |
| 4.4.261  | 1        | 3.23%   |
| 4.4.189  | 1        | 3.23%   |
| 4.4.14   | 1        | 3.23%   |
| 4.20.11  | 1        | 3.23%   |
| 4.19.98  | 1        | 3.23%   |
| 4.19.88  | 1        | 3.23%   |
| 4.19.107 | 1        | 3.23%   |
| 4.19.10  | 1        | 3.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.4     | 8        | 25.81%  |
| 4.19    | 8        | 25.81%  |
| 5.10    | 7        | 22.58%  |
| 5.4     | 4        | 12.9%   |
| 4.9     | 2        | 6.45%   |
| 5.12    | 1        | 3.23%   |
| 4.20    | 1        | 3.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 31       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 19       | 61.29%  |
| XFCE    | 9        | 29.03%  |
| KDE5    | 1        | 3.23%   |
| KDE     | 1        | 3.23%   |
| fvwm    | 1        | 3.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 21       | 67.74%  |
| Unknown | 7        | 22.58%  |
| Tty     | 2        | 6.45%   |
| Wayland | 1        | 3.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 17       | 54.84%  |
| XDM     | 10       | 32.26%  |
| SLiM    | 2        | 6.45%   |
| SDDM    | 2        | 6.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 16       | 51.61%  |
| en_US   | 11       | 35.48%  |
| ru_RU   | 1        | 3.23%   |
| it_IT   | 1        | 3.23%   |
| en_GB   | 1        | 3.23%   |
| C       | 1        | 3.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 20       | 64.52%  |
| EFI  | 11       | 35.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 20       | 64.52%  |
| Btrfs    | 5        | 16.13%  |
| Rootfs   | 3        | 9.68%   |
| Xfs      | 2        | 6.45%   |
| Reiserfs | 1        | 3.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 18       | 58.06%  |
| MBR  | 13       | 41.94%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 64.52%  |
| Yes       | 11       | 35.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 67.74%  |
| Yes       | 10       | 32.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 11       | 35.48%  |
| Gigabyte Technology | 4        | 12.9%   |
| Hewlett-Packard     | 3        | 9.68%   |
| ASRock              | 3        | 9.68%   |
| Supermicro          | 2        | 6.45%   |
| Dell                | 2        | 6.45%   |
| Shuttle             | 1        | 3.23%   |
| MSI                 | 1        | 3.23%   |
| Intel               | 1        | 3.23%   |
| Huanan              | 1        | 3.23%   |
| HPE                 | 1        | 3.23%   |
| Foxconn             | 1        | 3.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 3        | 9.68%   |
| Supermicro X9DA7/E                  | 1        | 3.23%   |
| Supermicro ReadyDATA 5200           | 1        | 3.23%   |
| Shuttle NC03U                       | 1        | 3.23%   |
| MSI MS-7529                         | 1        | 3.23%   |
| Intel DZ77RE-75K AAG39010-302       | 1        | 3.23%   |
| Huanan X79-8D VAA31                 | 1        | 3.23%   |
| HPE ProLiant MicroServer Gen10 Plus | 1        | 3.23%   |
| HP Z620 Workstation                 | 1        | 3.23%   |
| HP t620 Quad Core TC                | 1        | 3.23%   |
| HP 500-515na                        | 1        | 3.23%   |
| Gigabyte X150M-PRO ECC              | 1        | 3.23%   |
| Gigabyte N3160TN                    | 1        | 3.23%   |
| Gigabyte M61SME-S2                  | 1        | 3.23%   |
| Gigabyte 970A-DS3P                  | 1        | 3.23%   |
| Foxconn p6-2390                     | 1        | 3.23%   |
| Dell Precision WorkStation T3400    | 1        | 3.23%   |
| Dell Precision T3600                | 1        | 3.23%   |
| ASUS ROG STRIX X470-F GAMING        | 1        | 3.23%   |
| ASUS Pro WS X570-ACE                | 1        | 3.23%   |
| ASUS PRIME X370-PRO                 | 1        | 3.23%   |
| ASUS PRIME B450-PLUS                | 1        | 3.23%   |
| ASUS PRIME B350M-A                  | 1        | 3.23%   |
| ASUS P5QLD PRO                      | 1        | 3.23%   |
| ASUS M5A97 R2.0                     | 1        | 3.23%   |
| ASUS A68HM-PLUS                     | 1        | 3.23%   |
| ASRock Z390M-ITX/ac                 | 1        | 3.23%   |
| ASRock H87M Pro4                    | 1        | 3.23%   |
| ASRock H310CM-HDV                   | 1        | 3.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 3        | 9.68%   |
| ASUS All             | 3        | 9.68%   |
| Dell Precision       | 2        | 6.45%   |
| Supermicro X9DA7     | 1        | 3.23%   |
| Supermicro ReadyDATA | 1        | 3.23%   |
| Shuttle NC03U        | 1        | 3.23%   |
| MSI MS-7529          | 1        | 3.23%   |
| Intel DZ77RE-75K     | 1        | 3.23%   |
| Huanan X79-8D        | 1        | 3.23%   |
| HPE ProLiant         | 1        | 3.23%   |
| HP Z620              | 1        | 3.23%   |
| HP t620              | 1        | 3.23%   |
| HP 500-515na         | 1        | 3.23%   |
| Gigabyte X150M-PRO   | 1        | 3.23%   |
| Gigabyte N3160TN     | 1        | 3.23%   |
| Gigabyte M61SME-S2   | 1        | 3.23%   |
| Gigabyte 970A-DS3P   | 1        | 3.23%   |
| Foxconn p6-2390      | 1        | 3.23%   |
| ASUS ROG             | 1        | 3.23%   |
| ASUS Pro             | 1        | 3.23%   |
| ASUS P5QLD           | 1        | 3.23%   |
| ASUS M5A97           | 1        | 3.23%   |
| ASUS A68HM-PLUS      | 1        | 3.23%   |
| ASRock Z390M-ITX     | 1        | 3.23%   |
| ASRock H87M          | 1        | 3.23%   |
| ASRock H310CM-HDV    | 1        | 3.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 8        | 25.81%  |
| 2018 | 4        | 12.9%   |
| 2015 | 4        | 12.9%   |
| 2020 | 3        | 9.68%   |
| 2016 | 3        | 9.68%   |
| 2017 | 2        | 6.45%   |
| 2012 | 2        | 6.45%   |
| 2010 | 2        | 6.45%   |
| 2011 | 1        | 3.23%   |
| 2009 | 1        | 3.23%   |
| 2008 | 1        | 3.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 31       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 31       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 31       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 8        | 25.81%  |
| 8.01-16.0   | 7        | 22.58%  |
| 4.01-8.0    | 4        | 12.9%   |
| 32.01-64.0  | 4        | 12.9%   |
| 64.01-256.0 | 4        | 12.9%   |
| 3.01-4.0    | 3        | 9.68%   |
| 24.01-32.0  | 1        | 3.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 10       | 31.25%  |
| 2.01-3.0    | 6        | 18.75%  |
| 3.01-4.0    | 5        | 15.63%  |
| 4.01-8.0    | 4        | 12.5%   |
| 24.01-32.0  | 2        | 6.25%   |
| 8.01-16.0   | 2        | 6.25%   |
| 64.01-256.0 | 1        | 3.13%   |
| 16.01-24.0  | 1        | 3.13%   |
| 0.01-0.5    | 1        | 3.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 9        | 29.03%  |
| 3      | 6        | 19.35%  |
| 4      | 5        | 16.13%  |
| 5      | 3        | 9.68%   |
| 6      | 2        | 6.45%   |
| 2      | 2        | 6.45%   |
| 13     | 1        | 3.23%   |
| 8      | 1        | 3.23%   |
| 7      | 1        | 3.23%   |
| 0      | 1        | 3.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 17       | 54.84%  |
| No        | 14       | 45.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 31       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 74.19%  |
| Yes       | 8        | 25.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 67.74%  |
| Yes       | 10       | 32.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 9        | 29.03%  |
| UK        | 5        | 16.13%  |
| Russia    | 3        | 9.68%   |
| Germany   | 3        | 9.68%   |
| Sweden    | 2        | 6.45%   |
| France    | 2        | 6.45%   |
| Canada    | 2        | 6.45%   |
| Spain     | 1        | 3.23%   |
| Portugal  | 1        | 3.23%   |
| Italy     | 1        | 3.23%   |
| Hong Kong | 1        | 3.23%   |
| Bulgaria  | 1        | 3.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Yekaterinburg         | 3        | 9.68%   |
| Springfield           | 2        | 6.45%   |
| Caen                  | 2        | 6.45%   |
| Weilheim              | 1        | 3.23%   |
| Toronto               | 1        | 3.23%   |
| Tiffin                | 1        | 3.23%   |
| Stockholm             | 1        | 3.23%   |
| Sidcup                | 1        | 3.23%   |
| Saedinenie            | 1        | 3.23%   |
| Paterson              | 1        | 3.23%   |
| Palma                 | 1        | 3.23%   |
| Ottawa                | 1        | 3.23%   |
| Oldham                | 1        | 3.23%   |
| Naples                | 1        | 3.23%   |
| Milwaukee             | 1        | 3.23%   |
| London                | 1        | 3.23%   |
| Lisbon                | 1        | 3.23%   |
| Lexington             | 1        | 3.23%   |
| Kowloon               | 1        | 3.23%   |
| Koblenz               | 1        | 3.23%   |
| Haar                  | 1        | 3.23%   |
| Enskede-Arsta-Vantoer | 1        | 3.23%   |
| Dallas                | 1        | 3.23%   |
| Chelmsford            | 1        | 3.23%   |
| Carrollton            | 1        | 3.23%   |
| Camp Hill             | 1        | 3.23%   |
| Barry                 | 1        | 3.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 35     | 24.56%  |
| Seagate             | 11       | 28     | 19.3%   |
| Samsung Electronics | 8        | 15     | 14.04%  |
| Toshiba             | 5        | 11     | 8.77%   |
| Kingston            | 3        | 3      | 5.26%   |
| Hitachi             | 3        | 3      | 5.26%   |
| Intel               | 2        | 2      | 3.51%   |
| A-DATA Technology   | 2        | 2      | 3.51%   |
| Team                | 1        | 1      | 1.75%   |
| SK Hynix            | 1        | 1      | 1.75%   |
| SanDisk             | 1        | 1      | 1.75%   |
| MAXTOR              | 1        | 1      | 1.75%   |
| HGST                | 1        | 1      | 1.75%   |
| Fujitsu             | 1        | 1      | 1.75%   |
| Crucial             | 1        | 1      | 1.75%   |
| China               | 1        | 2      | 1.75%   |
| Apple               | 1        | 2      | 1.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| WDC WD1003FZEX-00MK2A0 1TB                    | 2        | 2.47%   |
| Toshiba MQ01ABD100 1TB                        | 2        | 2.47%   |
| Seagate ST500DM002-1BD142 500GB               | 2        | 2.47%   |
| Seagate ST4000VN008-2DR166 4TB                | 2        | 2.47%   |
| Seagate ST31000524AS 1TB                      | 2        | 2.47%   |
| WDC WDS100T2B0C-00PXH0 1TB                    | 1        | 1.23%   |
| WDC WD5000BPVT-2 500GB                        | 1        | 1.23%   |
| WDC WD5000BPKX-60HPJT0 500GB                  | 1        | 1.23%   |
| WDC WD5000AAKX-00ERMA0 500GB                  | 1        | 1.23%   |
| WDC WD5000AAKS-00V0A0 500GB                   | 1        | 1.23%   |
| WDC WD5000AAKS-00A7B2 500GB                   | 1        | 1.23%   |
| WDC WD40EFRX-68WT0N0 4TB                      | 1        | 1.23%   |
| WDC WD40EFRX-68N32N0 4TB                      | 1        | 1.23%   |
| WDC WD30EZRX-00SPEB0 3TB                      | 1        | 1.23%   |
| WDC WD30EZRX-00M                              | 1        | 1.23%   |
| WDC WD30EFRX-68EUZN0 3TB                      | 1        | 1.23%   |
| WDC WD30EFRX-68AX9N0 3TB                      | 1        | 1.23%   |
| WDC WD2003FZEX-0 2TB                          | 1        | 1.23%   |
| WDC WD1600AAJS-00PSA0 160GB                   | 1        | 1.23%   |
| WDC WD120EDAZ-11F3RA0 12TB                    | 1        | 1.23%   |
| WDC WD10EZRZ-00HTKB0 1TB                      | 1        | 1.23%   |
| WDC WD10EZEX-22BN5A0 1TB                      | 1        | 1.23%   |
| WDC WD10EZEX-00RKKA0 1TB                      | 1        | 1.23%   |
| WDC WD10EZEX-00BN5A0 1TB                      | 1        | 1.23%   |
| WDC WD10EURX-61C57Y0 1TB                      | 1        | 1.23%   |
| WDC WD10EALS-00Z8A0 1TB                       | 1        | 1.23%   |
| WDC WD100EMAZ-00WJTA0 10TB                    | 1        | 1.23%   |
| WDC WD1003FZEX-00K3CA0 1TB                    | 1        | 1.23%   |
| Toshiba MG07ACA12TE 12TB                      | 1        | 1.23%   |
| Toshiba HDWD110 1TB                           | 1        | 1.23%   |
| Toshiba DT01ACA200 2TB                        | 1        | 1.23%   |
| Toshiba DT01ACA100 1TB                        | 1        | 1.23%   |
| Team T253X1480G 480GB SSD                     | 1        | 1.23%   |
| SK Hynix SHGP31-1000GM-2 1TB                  | 1        | 1.23%   |
| Seagate ST980310AS 80GB                       | 1        | 1.23%   |
| Seagate ST4000DM004-2CV104 4TB                | 1        | 1.23%   |
| Seagate ST380819AS 80GB                       | 1        | 1.23%   |
| Seagate ST380011A 80GB                        | 1        | 1.23%   |
| Seagate ST3500418AS 500GB                     | 1        | 1.23%   |
| Seagate ST3500410AS 500GB                     | 1        | 1.23%   |
| Seagate ST2000DM008-2FR102 2TB                | 1        | 1.23%   |
| Seagate ST2000DM001-1CH164 2TB                | 1        | 1.23%   |
| Seagate ST1000VM002-1SD102 1TB                | 1        | 1.23%   |
| Seagate ST1000NM0011 1TB                      | 1        | 1.23%   |
| Seagate ST1000NM0001 1TB                      | 1        | 1.23%   |
| Seagate ST1000DM010-2EP102 1TB                | 1        | 1.23%   |
| Seagate ST1000DM003-1ER162 1TB                | 1        | 1.23%   |
| Seagate DKS2D-H3R0SS 3TB                      | 1        | 1.23%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD            | 1        | 1.23%   |
| Samsung SSD PM851 mSATA 256GB                 | 1        | 1.23%   |
| Samsung SSD 970 EVO Plus 1TB                  | 1        | 1.23%   |
| Samsung SSD 970 EVO 250GB                     | 1        | 1.23%   |
| Samsung SSD 860 EVO 1TB                       | 1        | 1.23%   |
| Samsung SSD 850 PRO 512GB                     | 1        | 1.23%   |
| Samsung SSD 850 PRO 256GB                     | 1        | 1.23%   |
| Samsung SSD 750 EVO 250GB                     | 1        | 1.23%   |
| Samsung NVMe SSD Controller SM981/PM981 512GB | 1        | 1.23%   |
| Samsung HD501LJ 500GB                         | 1        | 1.23%   |
| Samsung HD160JJ 160GB                         | 1        | 1.23%   |
| MAXTOR 4G120J6 128GB                          | 1        | 1.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 34     | 36.84%  |
| Seagate             | 11       | 24     | 28.95%  |
| Toshiba             | 5        | 11     | 13.16%  |
| Hitachi             | 3        | 3      | 7.89%   |
| Samsung Electronics | 2        | 2      | 5.26%   |
| MAXTOR              | 1        | 1      | 2.63%   |
| HGST                | 1        | 1      | 2.63%   |
| Fujitsu             | 1        | 1      | 2.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 9      | 28.57%  |
| Kingston            | 3        | 3      | 21.43%  |
| Team                | 1        | 1      | 7.14%   |
| SanDisk             | 1        | 1      | 7.14%   |
| Intel               | 1        | 1      | 7.14%   |
| Crucial             | 1        | 1      | 7.14%   |
| China               | 1        | 2      | 7.14%   |
| Apple               | 1        | 2      | 7.14%   |
| A-DATA Technology   | 1        | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 25       | 77     | 54.35%  |
| SSD     | 13       | 21     | 28.26%  |
| NVMe    | 7        | 8      | 15.22%  |
| Unknown | 1        | 4      | 2.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 28       | 94     | 77.78%  |
| NVMe | 7        | 8      | 19.44%  |
| SAS  | 1        | 8      | 2.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 20       | 37     | 43.48%  |
| 0.51-1.0   | 12       | 33     | 26.09%  |
| 2.01-3.0   | 4        | 8      | 8.7%    |
| 1.01-2.0   | 4        | 5      | 8.7%    |
| 3.01-4.0   | 3        | 9      | 6.52%   |
| 10.01-20.0 | 2        | 5      | 4.35%   |
| 4.01-10.0  | 1        | 1      | 2.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 8        | 25.81%  |
| 501-1000   | 6        | 19.35%  |
| 1001-2000  | 5        | 16.13%  |
| 2001-3000  | 3        | 9.68%   |
| 101-250    | 3        | 9.68%   |
| 251-500    | 2        | 6.45%   |
| 51-100     | 2        | 6.45%   |
| 21-50      | 1        | 3.23%   |
| 1-20       | 1        | 3.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| Unknown   | 8        | 25.81%  |
| 101-250   | 5        | 16.13%  |
| 501-1000  | 5        | 16.13%  |
| 51-100    | 4        | 12.9%   |
| 251-500   | 3        | 9.68%   |
| 1-20      | 3        | 9.68%   |
| 1001-2000 | 2        | 6.45%   |
| 21-50     | 1        | 3.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD5000BPKX-60HPJT0 500GB       | 1        | 1      | 5%      |
| WDC WD5000AAKX-00ERMA0 500GB       | 1        | 1      | 5%      |
| WDC WD5000AAKS-00A7B2 500GB        | 1        | 1      | 5%      |
| WDC WD40EFRX-68WT0N0 4TB           | 1        | 2      | 5%      |
| WDC WD30EZRX-00M                   | 1        | 1      | 5%      |
| WDC WD30EFRX-68AX9N0 3TB           | 1        | 4      | 5%      |
| WDC WD10EZEX-00RKKA0 1TB           | 1        | 1      | 5%      |
| WDC WD10EALS-00Z8A0 1TB            | 1        | 2      | 5%      |
| WDC WD1003FZEX-00MK2A0 1TB         | 1        | 2      | 5%      |
| Seagate ST380011A 80GB             | 1        | 1      | 5%      |
| Seagate ST3500418AS 500GB          | 1        | 1      | 5%      |
| Seagate ST3500410AS 500GB          | 1        | 1      | 5%      |
| Seagate ST31000524AS 1TB           | 1        | 1      | 5%      |
| Seagate ST1000VM002-1SD102 1TB     | 1        | 1      | 5%      |
| Seagate ST1000NM0011 1TB           | 1        | 2      | 5%      |
| SanDisk SDSA6MM-016G-1006 16GB SSD | 1        | 1      | 5%      |
| MAXTOR 4G120J6 128GB               | 1        | 1      | 5%      |
| Intel SSDSA2M080G2GC 80GB          | 1        | 1      | 5%      |
| Hitachi HDS721050CLA660 500GB      | 1        | 1      | 5%      |
| HGST HDN726040ALE614 4TB           | 1        | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 7        | 15     | 38.89%  |
| Seagate | 6        | 7      | 33.33%  |
| SanDisk | 1        | 1      | 5.56%   |
| MAXTOR  | 1        | 1      | 5.56%   |
| Intel   | 1        | 1      | 5.56%   |
| Hitachi | 1        | 1      | 5.56%   |
| HGST    | 1        | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 7        | 15     | 43.75%  |
| Seagate | 6        | 7      | 37.5%   |
| MAXTOR  | 1        | 1      | 6.25%   |
| Hitachi | 1        | 1      | 6.25%   |
| HGST    | 1        | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 15       | 25     | 88.24%  |
| SSD  | 2        | 2      | 11.76%  |

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
| Works    | 26       | 75     | 59.09%  |
| Malfunc  | 17       | 27     | 38.64%  |
| Detected | 1        | 8      | 2.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 20       | 41.67%  |
| AMD                      | 10       | 20.83%  |
| Samsung Electronics      | 4        | 8.33%   |
| ASMedia Technology       | 3        | 6.25%   |
| Marvell Technology Group | 2        | 4.17%   |
| Broadcom / LSI           | 2        | 4.17%   |
| SK Hynix                 | 1        | 2.08%   |
| Silicon Image            | 1        | 2.08%   |
| Sandisk                  | 1        | 2.08%   |
| Realtek Semiconductor    | 1        | 2.08%   |
| Nvidia                   | 1        | 2.08%   |
| JMicron Technology       | 1        | 2.08%   |
| 3ware                    | 1        | 2.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 8        | 12.9%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 4        | 6.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3        | 4.84%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 3        | 4.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2        | 3.23%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 2        | 3.23%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 2        | 3.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2        | 3.23%   |
| AMD 400 Series Chipset SATA Controller                                           | 2        | 3.23%   |
| SK Hynix Gold P31 SSD                                                            | 1        | 1.61%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 1        | 1.61%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1        | 1.61%   |
| Samsung Apple PCIe SSD                                                           | 1        | 1.61%   |
| Realtek Realtek Non-Volatile memory controller                                   | 1        | 1.61%   |
| Nvidia MCP61 SATA Controller                                                     | 1        | 1.61%   |
| Nvidia MCP61 IDE                                                                 | 1        | 1.61%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 1        | 1.61%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                          | 1        | 1.61%   |
| JMicron JMB368 IDE controller                                                    | 1        | 1.61%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1        | 1.61%   |
| Intel SSD 600P Series                                                            | 1        | 1.61%   |
| Intel SATA Controller [RAID mode]                                                | 1        | 1.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1        | 1.61%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1        | 1.61%   |
| Intel C608 chipset Dual 4-Port SATA/SAS Storage Control Unit                     | 1        | 1.61%   |
| Intel C600/X79 series chipset IDE-r Controller                                   | 1        | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1        | 1.61%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1        | 1.61%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1        | 1.61%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1        | 1.61%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1        | 1.61%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]    | 1        | 1.61%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]    | 1        | 1.61%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1        | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1        | 1.61%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 1        | 1.61%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                              | 1        | 1.61%   |
| Broadcom / LSI SAS2116 PCI-Express Fusion-MPT SAS-2 [Meteor]                     | 1        | 1.61%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 1        | 1.61%   |
| ASMedia 106x SATA/RAID Controller                                                | 1        | 1.61%   |
| AMD X370 Series Chipset SATA Controller                                          | 1        | 1.61%   |
| AMD 300 Series Chipset SATA Controller                                           | 1        | 1.61%   |
| 3ware 9650SE SATA-II RAID PCIe                                                   | 1        | 1.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 27       | 58.7%   |
| NVMe | 7        | 15.22%  |
| IDE  | 5        | 10.87%  |
| SAS  | 4        | 8.7%    |
| RAID | 3        | 6.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 20       | 64.52%  |
| AMD    | 11       | 35.48%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Intel Xeon CPU E5-2670 0 @ 2.60GHz         | 2        | 6.45%   |
| Intel Core i7-4790K CPU @ 4.00GHz          | 2        | 6.45%   |
| AMD Ryzen 5 3600 6-Core Processor          | 2        | 6.45%   |
| AMD FX-8350 Eight-Core Processor           | 2        | 6.45%   |
| Intel Xeon CPU X3450 @ 2.67GHz             | 1        | 3.23%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz         | 1        | 3.23%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz         | 1        | 3.23%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz        | 1        | 3.23%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz     | 1        | 3.23%   |
| Intel Pentium CPU G640 @ 2.80GHz           | 1        | 3.23%   |
| Intel Pentium CPU G4560 @ 3.50GHz          | 1        | 3.23%   |
| Intel Core i7-9700 CPU @ 3.00GHz           | 1        | 3.23%   |
| Intel Core i5-9400 CPU @ 2.90GHz           | 1        | 3.23%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 1        | 3.23%   |
| Intel Core i5-4690 CPU @ 3.50GHz           | 1        | 3.23%   |
| Intel Core i5-3470 CPU @ 3.20GHz           | 1        | 3.23%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz      | 1        | 3.23%   |
| Intel Core 2 Quad CPU Q6700 @ 2.66GHz      | 1        | 3.23%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz       | 1        | 3.23%   |
| Intel Celeron CPU N3160 @ 1.60GHz          | 1        | 3.23%   |
| AMD Ryzen 9 3950X 16-Core Processor        | 1        | 3.23%   |
| AMD Ryzen 7 3800X 8-Core Processor         | 1        | 3.23%   |
| AMD Ryzen 7 1700X Eight-Core Processor     | 1        | 3.23%   |
| AMD GX-415GA SOC with Radeon HD Graphics   | 1        | 3.23%   |
| AMD Athlon 64 X2 Dual Core Processor 5200+ | 1        | 3.23%   |
| AMD A4-7300 APU with Radeon HD Graphics    | 1        | 3.23%   |
| AMD A10-5700 APU with Radeon HD Graphics   | 1        | 3.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Xeon         | 6        | 19.35%  |
| Intel Core i5      | 4        | 12.9%   |
| Intel Core i7      | 3        | 9.68%   |
| Intel Pentium      | 2        | 6.45%   |
| Intel Core 2 Quad  | 2        | 6.45%   |
| AMD Ryzen 7        | 2        | 6.45%   |
| AMD Ryzen 5        | 2        | 6.45%   |
| AMD FX             | 2        | 6.45%   |
| Intel Pentium Gold | 1        | 3.23%   |
| Intel Core 2 Duo   | 1        | 3.23%   |
| Intel Celeron      | 1        | 3.23%   |
| AMD Ryzen 9        | 1        | 3.23%   |
| AMD GX             | 1        | 3.23%   |
| AMD Athlon 64 X2   | 1        | 3.23%   |
| AMD A4             | 1        | 3.23%   |
| AMD A10            | 1        | 3.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 12       | 38.71%  |
| 2      | 7        | 22.58%  |
| 6      | 4        | 12.9%   |
| 16     | 3        | 9.68%   |
| 8      | 3        | 9.68%   |
| 12     | 1        | 3.23%   |
| 1      | 1        | 3.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 28       | 90.32%  |
| 2      | 3        | 9.68%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 20       | 64.52%  |
| 1      | 11       | 35.48%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 31       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 7        | 22.58%  |
| 0x306c3    | 3        | 9.68%   |
| 0x206d7    | 3        | 9.68%   |
| 0x906ed    | 2        | 6.45%   |
| 0x1067a    | 2        | 6.45%   |
| 0x08701013 | 2        | 6.45%   |
| 0x06001119 | 2        | 6.45%   |
| 0x906ea    | 1        | 3.23%   |
| 0x406c4    | 1        | 3.23%   |
| 0x306a9    | 1        | 3.23%   |
| 0x206a7    | 1        | 3.23%   |
| 0x106e5    | 1        | 3.23%   |
| 0x08701021 | 1        | 3.23%   |
| 0x08001138 | 1        | 3.23%   |
| 0x07000110 | 1        | 3.23%   |
| 0x06000852 | 1        | 3.23%   |
| 0x06000822 | 1        | 3.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| SandyBridge | 5        | 16.13%  |
| KabyLake    | 5        | 16.13%  |
| Zen 2       | 4        | 12.9%   |
| Piledriver  | 4        | 12.9%   |
| Haswell     | 4        | 12.9%   |
| Penryn      | 2        | 6.45%   |
| Zen         | 1        | 3.23%   |
| Silvermont  | 1        | 3.23%   |
| Nehalem     | 1        | 3.23%   |
| K8 Hammer   | 1        | 3.23%   |
| Jaguar      | 1        | 3.23%   |
| IvyBridge   | 1        | 3.23%   |
| Core        | 1        | 3.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 11       | 36.67%  |
| Nvidia                     | 9        | 30%     |
| Intel                      | 8        | 26.67%  |
| Matrox Electronics Systems | 2        | 6.67%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3        | 9.38%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2        | 6.25%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 3.13%   |
| Nvidia GP107GL [Quadro P1000]                                                            | 1        | 3.13%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 3.13%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 3.13%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 3.13%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 3.13%   |
| Nvidia GK110GL [Quadro K5200]                                                            | 1        | 3.13%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1        | 3.13%   |
| Nvidia GK104GL [Quadro K5000]                                                            | 1        | 3.13%   |
| Nvidia G80GL [Quadro FX 4600]                                                            | 1        | 3.13%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 3.13%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 1        | 3.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1        | 3.13%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 1        | 3.13%   |
| Intel HD Graphics 620                                                                    | 1        | 3.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 3.13%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 3.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 3.13%   |
| AMD Richland [Radeon HD 8470D]                                                           | 1        | 3.13%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 1        | 3.13%   |
| AMD Oland PRO [Radeon R7 240/340]                                                        | 1        | 3.13%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 1        | 3.13%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 1        | 3.13%   |
| AMD Cypress XT [Radeon HD 5870]                                                          | 1        | 3.13%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                                       | 1        | 3.13%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 1        | 3.13%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 1        | 3.13%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x AMD    | 11       | 35.48%  |
| 1 x Nvidia | 8        | 25.81%  |
| 1 x Intel  | 8        | 25.81%  |
| 1 x Matrox | 2        | 6.45%   |
| Other      | 1        | 3.23%   |
| 2 x Nvidia | 1        | 3.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 16       | 51.61%  |
| Proprietary | 9        | 29.03%  |
| Unknown     | 6        | 19.35%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 15       | 48.39%  |
| 3.01-4.0   | 5        | 16.13%  |
| 0.51-1.0   | 5        | 16.13%  |
| 1.01-2.0   | 4        | 12.9%   |
| 7.01-8.0   | 2        | 6.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 4        | 13.33%  |
| Hewlett-Packard      | 3        | 10%     |
| Goldstar             | 3        | 10%     |
| ViewSonic            | 2        | 6.67%   |
| Samsung Electronics  | 2        | 6.67%   |
| BenQ                 | 2        | 6.67%   |
| Acer                 | 2        | 6.67%   |
| Xiaomi               | 1        | 3.33%   |
| Unknown              | 1        | 3.33%   |
| Toshiba              | 1        | 3.33%   |
| ONN                  | 1        | 3.33%   |
| NEC Computers        | 1        | 3.33%   |
| Lenovo               | 1        | 3.33%   |
| JVC                  | 1        | 3.33%   |
| Iiyama               | 1        | 3.33%   |
| Gigabyte Technology  | 1        | 3.33%   |
| Eizo                 | 1        | 3.33%   |
| ASUSTek Computer     | 1        | 3.33%   |
| Ancor Communications | 1        | 3.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Xiaomi Mi TV XMD009A 2880x1800 480x270mm 21.7-inch                   | 1        | 3.13%   |
| ViewSonic LCD Monitor VX2276 Series 1920x1080                        | 1        | 3.13%   |
| ViewSonic LCD Monitor VA2448 SERIES 1920x1080                        | 1        | 3.13%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1        | 3.13%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                     | 1        | 3.13%   |
| Samsung Electronics SyncMaster SAM0578 1920x1080 476x268mm 21.5-inch | 1        | 3.13%   |
| Samsung Electronics SMB2430L SAM0644 1920x1080 521x293mm 23.5-inch   | 1        | 3.13%   |
| ONN ONA18HO015 ONN0101 1920x1080 470x290mm 21.7-inch                 | 1        | 3.13%   |
| NEC Computers LCD2490WUXi NEC66CE 1920x1200 518x324mm 24.1-inch      | 1        | 3.13%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch             | 1        | 3.13%   |
| JVC FPDEUFT3 JVC21BE 1920x540                                        | 1        | 3.13%   |
| Iiyama PLE2207WS IVM5609 1680x1050 474x296mm 22.0-inch               | 1        | 3.13%   |
| Hewlett-Packard ZR2740w HWP2957 2560x1440 597x336mm 27.0-inch        | 1        | 3.13%   |
| Hewlett-Packard LE1851w HWP2840 1366x768 413x234mm 18.7-inch         | 1        | 3.13%   |
| Hewlett-Packard 2309 HWP2823 1920x1080 510x287mm 23.0-inch           | 1        | 3.13%   |
| Goldstar W2242 GSM5678 1680x1050 474x296mm 22.0-inch                 | 1        | 3.13%   |
| Goldstar W2242 GSM5677 1680x1050 474x296mm 22.0-inch                 | 1        | 3.13%   |
| Goldstar FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch               | 1        | 3.13%   |
| Goldstar BK750Y GSM5B3E 1920x1080 600x340mm 27.2-inch                | 1        | 3.13%   |
| Goldstar BK750Y GSM5B3D 1920x1080 480x270mm 21.7-inch                | 1        | 3.13%   |
| Gigabyte Technology G27Q GBT2709 2560x1440 598x336mm 27.0-inch       | 1        | 3.13%   |
| Eizo M1700 ENC1788 1280x1024 338x271mm 17.1-inch                     | 1        | 3.13%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 1        | 3.13%   |
| Dell LCD Monitor U2312HM 1920x1080                                   | 1        | 3.13%   |
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                    | 1        | 3.13%   |
| Dell 1905FP DEL400D 1280x1024 376x301mm 19.0-inch                    | 1        | 3.13%   |
| BenQ EW2420 BNQ7923 1920x1080 530x300mm 24.0-inch                    | 1        | 3.13%   |
| BenQ BenQG2222HDL BNQ785A 1920x1080 478x269mm 21.6-inch              | 1        | 3.13%   |
| ASUSTek Computer VA24DQLB AUS2482 1920x1080 527x296mm 23.8-inch      | 1        | 3.13%   |
| Ancor Communications VG248 ACI24E1 1680x1050 530x300mm 24.0-inch     | 1        | 3.13%   |
| Acer K222HQL ACR040D 1920x1080 480x270mm 21.7-inch                   | 1        | 3.13%   |
| Acer AL171 ACRAD18 1280x1024 338x270mm 17.0-inch                     | 1        | 3.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 15       | 51.72%  |
| 1280x1024 (SXGA)   | 4        | 13.79%  |
| 2560x1440 (QHD)    | 2        | 6.9%    |
| 1920x1200 (WUXGA)  | 2        | 6.9%    |
| 1680x1050 (WSXGA+) | 2        | 6.9%    |
| 2880x1800          | 1        | 3.45%   |
| 2288x1287          | 1        | 3.45%   |
| 1920x540           | 1        | 3.45%   |
| 1366x768 (WXGA)    | 1        | 3.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 5        | 16.13%  |
| 21      | 5        | 16.13%  |
| 27      | 4        | 12.9%   |
| 23      | 4        | 12.9%   |
| Unknown | 4        | 12.9%   |
| 17      | 3        | 9.68%   |
| 142     | 1        | 3.23%   |
| 74      | 1        | 3.23%   |
| 22      | 1        | 3.23%   |
| 19      | 1        | 3.23%   |
| 18      | 1        | 3.23%   |
| 15      | 1        | 3.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 12       | 38.71%  |
| 401-500        | 8        | 25.81%  |
| 301-350        | 4        | 12.9%   |
| Unknown        | 4        | 12.9%   |
| More than 2000 | 1        | 3.23%   |
| 351-400        | 1        | 3.23%   |
| 1501-2000      | 1        | 3.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 13       | 46.43%  |
| 16/10   | 5        | 17.86%  |
| Unknown | 3        | 10.71%  |
| 6/5     | 2        | 7.14%   |
| 5/4     | 2        | 7.14%   |
| 32/9    | 1        | 3.57%   |
| 3/2     | 1        | 3.57%   |
| 1.00    | 1        | 3.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 11       | 36.67%  |
| 301-350        | 4        | 13.33%  |
| 141-150        | 4        | 13.33%  |
| Unknown        | 4        | 13.33%  |
| 251-300        | 3        | 10%     |
| More than 1000 | 2        | 6.67%   |
| 151-200        | 1        | 3.33%   |
| 101-110        | 1        | 3.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 16       | 51.61%  |
| 101-120 | 7        | 22.58%  |
| Unknown | 4        | 12.9%   |
| 1-50    | 2        | 6.45%   |
| 121-160 | 2        | 6.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 16       | 51.61%  |
| 0     | 7        | 22.58%  |
| 2     | 6        | 19.35%  |
| 3     | 2        | 6.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 16       | 40%     |
| Realtek Semiconductor    | 14       | 35%     |
| VIA Technologies         | 1        | 2.5%    |
| TP-Link                  | 1        | 2.5%    |
| Ralink Technology        | 1        | 2.5%    |
| Ralink                   | 1        | 2.5%    |
| Qualcomm Atheros         | 1        | 2.5%    |
| Nvidia                   | 1        | 2.5%    |
| Micro Star International | 1        | 2.5%    |
| Mellanox Technologies    | 1        | 2.5%    |
| Chelsio Communications   | 1        | 2.5%    |
| Broadcom                 | 1        | 2.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 12       | 25%     |
| Intel I211 Gigabit Network Connection                                         | 5        | 10.42%  |
| Intel 82574L Gigabit Network Connection                                       | 4        | 8.33%   |
| Intel Ethernet Connection (2) I218-V                                          | 3        | 6.25%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2        | 4.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 4.17%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 1        | 2.08%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                         | 1        | 2.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1        | 2.08%   |
| Ralink MT7601U Wireless Adapter                                               | 1        | 2.08%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1        | 2.08%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 2.08%   |
| Nvidia MCP61 Ethernet                                                         | 1        | 2.08%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]    | 1        | 2.08%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                         | 1        | 2.08%   |
| Intel Wireless 7260                                                           | 1        | 2.08%   |
| Intel I350 Gigabit Network Connection                                         | 1        | 2.08%   |
| Intel Ethernet Connection I217-V                                              | 1        | 2.08%   |
| Intel Ethernet Connection (7) I219-V                                          | 1        | 2.08%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 2.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1        | 2.08%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 2.08%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 2.08%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 2.08%   |
| Chelsio T320 10GbE Dual Port Adapter                                          | 1        | 2.08%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 1        | 2.08%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 2        | 25%     |
| Intel                    | 2        | 25%     |
| TP-Link                  | 1        | 12.5%   |
| Ralink Technology        | 1        | 12.5%   |
| Ralink                   | 1        | 12.5%   |
| Micro Star International | 1        | 12.5%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EE Wireless Network Adapter                                 | 2        | 25%     |
| TP-Link RTL8812AU Archer T4U 802.11ac                                      | 1        | 12.5%   |
| Ralink MT7601U Wireless Adapter                                            | 1        | 12.5%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                  | 1        | 12.5%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1        | 12.5%   |
| Intel Wireless 7260                                                        | 1        | 12.5%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 1        | 12.5%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 15       | 44.12%  |
| Realtek Semiconductor  | 13       | 38.24%  |
| VIA Technologies       | 1        | 2.94%   |
| Qualcomm Atheros       | 1        | 2.94%   |
| Nvidia                 | 1        | 2.94%   |
| Mellanox Technologies  | 1        | 2.94%   |
| Chelsio Communications | 1        | 2.94%   |
| Broadcom               | 1        | 2.94%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 12       | 30%     |
| Intel I211 Gigabit Network Connection                                         | 5        | 12.5%   |
| Intel 82574L Gigabit Network Connection                                       | 4        | 10%     |
| Intel Ethernet Connection (2) I218-V                                          | 3        | 7.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 5%      |
| VIA VT6105/VT6106S [Rhine-III]                                                | 1        | 2.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1        | 2.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 2.5%    |
| Nvidia MCP61 Ethernet                                                         | 1        | 2.5%    |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                         | 1        | 2.5%    |
| Intel I350 Gigabit Network Connection                                         | 1        | 2.5%    |
| Intel Ethernet Connection I217-V                                              | 1        | 2.5%    |
| Intel Ethernet Connection (7) I219-V                                          | 1        | 2.5%    |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 2.5%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 2.5%    |
| Intel 82579V Gigabit Network Connection                                       | 1        | 2.5%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 2.5%    |
| Chelsio T320 10GbE Dual Port Adapter                                          | 1        | 2.5%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 1        | 2.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 31       | 79.49%  |
| WiFi     | 8        | 20.51%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 26       | 96.3%   |
| WiFi     | 1        | 3.7%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 15       | 48.39%  |
| 2     | 10       | 32.26%  |
| 4     | 2        | 6.45%   |
| 3     | 2        | 6.45%   |
| 5     | 1        | 3.23%   |
| 0     | 1        | 3.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 27       | 87.1%   |
| Yes  | 4        | 12.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Cambridge Silicon Radio  | 6        | 60%     |
| Intel                    | 2        | 20%     |
| Micro Star International | 1        | 10%     |
| Broadcom                 | 1        | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 60%     |
| Micro Star International Bluetooth Device           | 1        | 10%     |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 10%     |
| Intel Bluetooth wireless interface                  | 1        | 10%     |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 18       | 40.91%  |
| AMD                 | 13       | 29.55%  |
| Nvidia              | 8        | 18.18%  |
| Creative Labs       | 3        | 6.82%   |
| EGO SYStems         | 1        | 2.27%   |
| C-Media Electronics | 1        | 2.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 4        | 7.27%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4        | 7.27%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3        | 5.45%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3        | 5.45%   |
| AMD FCH Azalia Controller                                                                         | 3        | 5.45%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3        | 5.45%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2        | 3.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2        | 3.64%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2        | 3.64%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1        | 1.82%   |
| Nvidia MCP61 High Definition Audio                                                                | 1        | 1.82%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1        | 1.82%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1        | 1.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1        | 1.82%   |
| Nvidia GK110 High Definition Audio Controller                                                     | 1        | 1.82%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1        | 1.82%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1        | 1.82%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1        | 1.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1        | 1.82%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1        | 1.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 1.82%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1        | 1.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1        | 1.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1        | 1.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1        | 1.82%   |
| Intel 200 Series PCH HD Audio                                                                     | 1        | 1.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1        | 1.82%   |
| EGO SYStems U24XL                                                                                 | 1        | 1.82%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 1        | 1.82%   |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                                                 | 1        | 1.82%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                | 1        | 1.82%   |
| C-Media Electronics USB Audio Device                                                              | 1        | 1.82%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1        | 1.82%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1        | 1.82%   |
| AMD Navi 10 HDMI Audio                                                                            | 1        | 1.82%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1        | 1.82%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1        | 1.82%   |
| AMD Cypress HDMI Audio [Radeon HD 5830/5850/5870 / 6850/6870 Rebrand]                             | 1        | 1.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 6        | 18.18%  |
| Corsair             | 6        | 18.18%  |
| Unknown             | 4        | 12.12%  |
| SK Hynix            | 4        | 12.12%  |
| Crucial             | 4        | 12.12%  |
| Samsung Electronics | 2        | 6.06%   |
| Micron Technology   | 2        | 6.06%   |
| Transcend           | 1        | 3.03%   |
| Team                | 1        | 3.03%   |
| HPE                 | 1        | 3.03%   |
| AMD                 | 1        | 3.03%   |
| Unknown             | 1        | 3.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM DDR3 65535MT/s              | 1        | 2.63%   |
| Unknown RAM Module 2048MB DIMM SDRAM                       | 1        | 2.63%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                 | 1        | 2.63%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                     | 1        | 2.63%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                 | 1        | 2.63%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                     | 1        | 2.63%   |
| Transcend RAM TS256MLQ72V6U 2048MB DIMM DDR2 667MT/s       | 1        | 2.63%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s        | 1        | 2.63%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 1        | 2.63%   |
| SK Hynix RAM HMT41GU6BFR8A-PB 8192MB DIMM DDR3 2000MT/s    | 1        | 2.63%   |
| SK Hynix RAM HMT351R7CFR8A-H9 4096MB DIMM DDR3 1333MT/s    | 1        | 2.63%   |
| SK Hynix RAM HMT31GR7EFR4A 8192MB DIMM DDR3 1600MT/s       | 1        | 2.63%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1        | 2.63%   |
| Samsung RAM M393B5273DH0-CK0 4GB DIMM DDR3 1600MT/s        | 1        | 2.63%   |
| Micron RAM 36KSF1G72PZ-1G4K1 8192MB DIMM DDR3 1333MT/s     | 1        | 2.63%   |
| Micron RAM 18JSF1G72PZ-1G9E1 8192MB DIMM DDR3 1866MT/s     | 1        | 2.63%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s       | 1        | 2.63%   |
| Kingston RAM KHX3600C17D4/8GX 8GB DIMM DDR4 3600MT/s       | 1        | 2.63%   |
| Kingston RAM KHX1600C10D3/8G 4GB DIMM DDR3 1867MT/s        | 1        | 2.63%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s   | 1        | 2.63%   |
| Kingston RAM 99U5471-037.A00LF 8GB DIMM DDR3 1600MT/s      | 1        | 2.63%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s      | 1        | 2.63%   |
| Kingston RAM 9965669-009.A00G 8192MB DIMM DDR4 2133MT/s    | 1        | 2.63%   |
| Kingston RAM 9905663-031.A00G 16GB SODIMM DDR4 2400MT/s    | 1        | 2.63%   |
| HPE RAM 879526-091 8192MB DIMM DDR4 2666MT/s               | 1        | 2.63%   |
| Crucial RAM BLT4G3D1869DT1TX0. 4GB DIMM DDR3 1867MT/s      | 1        | 2.63%   |
| Crucial RAM BLT4G3D1608DT1TX0. 4GB DIMM DDR3 1600MT/s      | 1        | 2.63%   |
| Crucial RAM BLS8G4D32AESBK.M8FE1 8GB DIMM DDR4 3600MT/s    | 1        | 2.63%   |
| Crucial RAM BLS8G4D240FSB.16FBD2 8GB DIMM DDR4 2400MT/s    | 1        | 2.63%   |
| Crucial RAM BLS16G4D26BFSC.16FD 16384MB DIMM DDR4 2666MT/s | 1        | 2.63%   |
| Corsair RAM CMZ32GX3M4X1600C10 8192MB DIMM DDR3 1600MT/s   | 1        | 2.63%   |
| Corsair RAM CMY32GX3M4A16 8192MB DIMM DDR3 667MT/s         | 1        | 2.63%   |
| Corsair RAM CMY16GX3M2A2400C11 8GB DIMM DDR3 2400MT/s      | 1        | 2.63%   |
| Corsair RAM CML16GX3M2A1600C10 8192MB DIMM DDR3 1600MT/s   | 1        | 2.63%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s     | 1        | 2.63%   |
| Corsair RAM CMK16GX4M1A2666C16 16384MB DIMM DDR4 2667MT/s  | 1        | 2.63%   |
| AMD RAM R534G1601S1SL 4096MB DIMM DDR3 1600MT/s            | 1        | 2.63%   |
| Unknown                                                    | 1        | 2.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 17       | 54.84%  |
| DDR4    | 10       | 32.26%  |
| SDRAM   | 1        | 3.23%   |
| DDR2    | 1        | 3.23%   |
| DDR     | 1        | 3.23%   |
| Unknown | 1        | 3.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 29       | 93.55%  |
| SODIMM | 2        | 6.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 15       | 44.12%  |
| 4096  | 8        | 23.53%  |
| 2048  | 4        | 11.76%  |
| 16384 | 3        | 8.82%   |
| 32768 | 2        | 5.88%   |
| 1024  | 2        | 5.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 10       | 29.41%  |
| 2400    | 3        | 8.82%   |
| 1333    | 3        | 8.82%   |
| 667     | 3        | 8.82%   |
| 3600    | 2        | 5.88%   |
| 3200    | 2        | 5.88%   |
| 2666    | 2        | 5.88%   |
| 1867    | 2        | 5.88%   |
| 65535   | 1        | 2.94%   |
| 2667    | 1        | 2.94%   |
| 2133    | 1        | 2.94%   |
| 2000    | 1        | 2.94%   |
| 1866    | 1        | 2.94%   |
| 800     | 1        | 2.94%   |
| Unknown | 1        | 2.94%   |

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
| 0     | 19       | 61.29%  |
| 1     | 4        | 12.9%   |
| 4     | 3        | 9.68%   |
| 2     | 3        | 9.68%   |
| 3     | 2        | 6.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Sound                    | 6        | 26.09%  |
| Graphics card            | 6        | 26.09%  |
| Communication controller | 4        | 17.39%  |
| Net/wireless             | 3        | 13.04%  |
| Unassigned class         | 1        | 4.35%   |
| Storage/ata              | 1        | 4.35%   |
| Card reader              | 1        | 4.35%   |
| Bluetooth                | 1        | 4.35%   |

