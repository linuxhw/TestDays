openSUSE Leap-15.3 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for openSUSE Leap-15.3.

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
| ASRock     | Z68 Extreme4 Gen3           | [00a3ad4abc](https://linux-hardware.org/?probe=00a3ad4abc) | Dec 02, 2021 |
| ASRock     | Z68 Extreme4 Gen3           | [e75c56906a](https://linux-hardware.org/?probe=e75c56906a) | Dec 01, 2021 |
| ASUSTek    | CROSSHAIR VI HERO           | [a2761e06a4](https://linux-hardware.org/?probe=a2761e06a4) | Nov 24, 2021 |
| ASUSTek    | CROSSHAIR VI HERO           | [5bfec76970](https://linux-hardware.org/?probe=5bfec76970) | Nov 24, 2021 |
| MSI        | H510I PRO WIFI              | [d50547de1f](https://linux-hardware.org/?probe=d50547de1f) | Nov 15, 2021 |
| ASRock     | N68C-GS4 FX                 | [c863f2ca43](https://linux-hardware.org/?probe=c863f2ca43) | Nov 14, 2021 |
| Fujitsu    | D3220-A1 S26361-D3220-A1    | [7d1fd58f75](https://linux-hardware.org/?probe=7d1fd58f75) | Nov 14, 2021 |
| HP         | 844C                        | [2d709598d7](https://linux-hardware.org/?probe=2d709598d7) | Nov 12, 2021 |
| ASUSTek    | M4A78T-E                    | [10991ab539](https://linux-hardware.org/?probe=10991ab539) | Nov 10, 2021 |
| Dell       | 0M859N A00                  | [aadca45789](https://linux-hardware.org/?probe=aadca45789) | Nov 01, 2021 |
| Dell       | 0Y2YM6 A00                  | [d9a12dc22c](https://linux-hardware.org/?probe=d9a12dc22c) | Oct 19, 2021 |
| Dell       | 0Y2YM6 A00                  | [34a55551e2](https://linux-hardware.org/?probe=34a55551e2) | Oct 19, 2021 |
| Lenovo     | 364A SDK0J40700 WIN 3258... | [ce4776505f](https://linux-hardware.org/?probe=ce4776505f) | Oct 03, 2021 |
| MSI        | B450M MORTAR MAX            | [556c37ba9b](https://linux-hardware.org/?probe=556c37ba9b) | Oct 03, 2021 |
| MSI        | B450M PRO-VDH MAX           | [ad69186227](https://linux-hardware.org/?probe=ad69186227) | Oct 02, 2021 |
| ASRock     | Z68 Extreme4 Gen3           | [3cec37b610](https://linux-hardware.org/?probe=3cec37b610) | Oct 02, 2021 |
| MSI        | B450M PRO-VDH MAX           | [540dca7da7](https://linux-hardware.org/?probe=540dca7da7) | Oct 02, 2021 |
| ASUSTek    | M4A78T-E                    | [01ec64f498](https://linux-hardware.org/?probe=01ec64f498) | Sep 24, 2021 |
| Lenovo     | 364A SDK0J40700 WIN 3258... | [58f9ca6247](https://linux-hardware.org/?probe=58f9ca6247) | Sep 22, 2021 |
| Lenovo     | 364A SDK0J40700 WIN 3258... | [db9ccd461b](https://linux-hardware.org/?probe=db9ccd461b) | Sep 22, 2021 |
| VS Company | G31T-M                      | [ed8bb8c0d1](https://linux-hardware.org/?probe=ed8bb8c0d1) | Sep 21, 2021 |
| ASUSTek    | AM1M-A/BR                   | [c586c22b15](https://linux-hardware.org/?probe=c586c22b15) | Sep 20, 2021 |
| Alienware  | 0PGRP5 A02                  | [65615a3aaa](https://linux-hardware.org/?probe=65615a3aaa) | Sep 16, 2021 |
| Alienware  | 0PGRP5 A02                  | [158a015f26](https://linux-hardware.org/?probe=158a015f26) | Sep 15, 2021 |
| MSI        | X370 GAMING PRO             | [629a45e23d](https://linux-hardware.org/?probe=629a45e23d) | Sep 12, 2021 |
| HP         | 8056                        | [3cab8505c4](https://linux-hardware.org/?probe=3cab8505c4) | Sep 06, 2021 |
| Intel      | DG41WV AAE90316-104         | [27c162218f](https://linux-hardware.org/?probe=27c162218f) | Sep 05, 2021 |
| Gigabyte   | B550 AORUS PRO AC           | [be3b65a81d](https://linux-hardware.org/?probe=be3b65a81d) | Aug 29, 2021 |
| ASRock     | B450M Pro4                  | [a13b05f65f](https://linux-hardware.org/?probe=a13b05f65f) | Aug 27, 2021 |
| ASUSTek    | PRIME H310M-A               | [a22aa3c48c](https://linux-hardware.org/?probe=a22aa3c48c) | Aug 01, 2021 |
| MSI        | B85M-E45                    | [0e20d4cea9](https://linux-hardware.org/?probe=0e20d4cea9) | Jul 30, 2021 |
| Gigabyte   | B250M-DS3H-CF               | [acbcbe74d7](https://linux-hardware.org/?probe=acbcbe74d7) | Jul 22, 2021 |
| HP         | 8433 11                     | [b079ccb608](https://linux-hardware.org/?probe=b079ccb608) | Jul 15, 2021 |
| MSI        | D2415 S26361-D2415-A21      | [b49400f636](https://linux-hardware.org/?probe=b49400f636) | Jul 11, 2021 |
| MSI        | B350 TOMAHAWK               | [27a6ac997b](https://linux-hardware.org/?probe=27a6ac997b) | Jul 03, 2021 |
| ASRock     | X570M Pro4                  | [a00aea4331](https://linux-hardware.org/?probe=a00aea4331) | Jul 03, 2021 |
| HP         | 0A68h                       | [36cfa6a366](https://linux-hardware.org/?probe=36cfa6a366) | Jun 27, 2021 |
| ASUSTek    | TUF B450-PRO GAMING         | [dfc2f82575](https://linux-hardware.org/?probe=dfc2f82575) | Jun 26, 2021 |
| ASRock     | X570 Steel Legend           | [b4a11b3e4e](https://linux-hardware.org/?probe=b4a11b3e4e) | Jun 17, 2021 |
| MSI        | MEG X570 GODLIKE            | [11b7f0e8ae](https://linux-hardware.org/?probe=11b7f0e8ae) | Jun 17, 2021 |
| HP         | 2AA2                        | [65e7cd2d3e](https://linux-hardware.org/?probe=65e7cd2d3e) | Jun 02, 2021 |
| ASUSTek    | P8H61-M LE/USB3             | [fca0fd3336](https://linux-hardware.org/?probe=fca0fd3336) | Jan 03, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 5.3.18-59.19-default    | 8        | 23.53%  |
| 5.3.18-59.27-default    | 5        | 14.71%  |
| 5.3.18-59.5-default     | 4        | 11.76%  |
| 5.3.18-59.24-default    | 4        | 11.76%  |
| 5.3.18-59.10-default    | 3        | 8.82%   |
| 5.3.18-57-default       | 3        | 8.82%   |
| 5.3.18-lp152.57-default | 1        | 2.94%   |
| 5.3.18-59.34-default    | 1        | 2.94%   |
| 5.3.18-59.27-preempt    | 1        | 2.94%   |
| 5.3.18-59.24-preempt    | 1        | 2.94%   |
| 5.3.18-59.19-preempt    | 1        | 2.94%   |
| 5.3.18-59.16-default    | 1        | 2.94%   |
| 5.3.18-59.13-default    | 1        | 2.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.3.18  | 32       | 100%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.3     | 32       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 32       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE5       | 12       | 36.36%  |
| KDE        | 9        | 27.27%  |
| Unknown    | 6        | 18.18%  |
| XFCE       | 3        | 9.09%   |
| GNOME      | 2        | 6.06%   |
| X-Cinnamon | 1        | 3.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 27       | 81.82%  |
| Tty     | 5        | 15.15%  |
| Wayland | 1        | 3.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 21       | 65.63%  |
| LightDM | 7        | 21.88%  |
| SDDM    | 3        | 9.38%   |
| XDM     | 1        | 3.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 10       | 31.25%  |
| de_DE   | 7        | 21.88%  |
| POSIX   | 4        | 12.5%   |
| pt_BR   | 3        | 9.38%   |
| pl_PL   | 1        | 3.13%   |
| nl_BE   | 1        | 3.13%   |
| hr_HR   | 1        | 3.13%   |
| es_MX   | 1        | 3.13%   |
| es_ES   | 1        | 3.13%   |
| en_GB   | 1        | 3.13%   |
| en_AU   | 1        | 3.13%   |
| Unknown | 1        | 3.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 20       | 62.5%   |
| EFI  | 12       | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 20       | 62.5%   |
| Ext4    | 9        | 28.13%  |
| Xfs     | 2        | 6.25%   |
| Overlay | 1        | 3.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 18       | 54.55%  |
| GPT     | 14       | 42.42%  |
| MBR     | 1        | 3.03%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 84.85%  |
| Yes       | 5        | 15.15%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 78.13%  |
| Yes       | 7        | 21.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI                 | 8        | 25%     |
| ASUSTek Computer    | 6        | 18.75%  |
| Hewlett-Packard     | 5        | 15.63%  |
| ASRock              | 5        | 15.63%  |
| Gigabyte Technology | 2        | 6.25%   |
| VS Company          | 1        | 3.13%   |
| Lenovo              | 1        | 3.13%   |
| Intel               | 1        | 3.13%   |
| Fujitsu             | 1        | 3.13%   |
| Dell                | 1        | 3.13%   |
| Alienware           | 1        | 3.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Desktops | Percent |
|----------------------------------------------|----------|---------|
| VS Company G31T-M                            | 1        | 3.13%   |
| MSI MS-7D16                                  | 1        | 3.13%   |
| MSI MS-7C34                                  | 1        | 3.13%   |
| MSI MS-7B89                                  | 1        | 3.13%   |
| MSI MS-7A38                                  | 1        | 3.13%   |
| MSI MS-7A34                                  | 1        | 3.13%   |
| MSI MS-7A33                                  | 1        | 3.13%   |
| MSI MS-7817                                  | 1        | 3.13%   |
| MSI ESPRIMO P1510                            | 1        | 3.13%   |
| Lenovo IdeaCentre Y710 Cube-15ISH 90FL004WGE | 1        | 3.13%   |
| Intel DG41WV AAE90316-104                    | 1        | 3.13%   |
| HP xw4400 Workstation                        | 1        | 3.13%   |
| HP Pavilion Gaming Desktop 790-00xx          | 1        | 3.13%   |
| HP Pavilion Gaming Desktop 690-00xx          | 1        | 3.13%   |
| HP EliteDesk 800 G2 DM 65W                   | 1        | 3.13%   |
| HP 200-5120br                                | 1        | 3.13%   |
| Gigabyte B550 AORUS PRO AC                   | 1        | 3.13%   |
| Gigabyte B250M-DS3H                          | 1        | 3.13%   |
| Fujitsu ESPRIMO P520                         | 1        | 3.13%   |
| Dell Vostro 3268                             | 1        | 3.13%   |
| ASUS TUF B450-PRO GAMING                     | 1        | 3.13%   |
| ASUS PRIME H310M-A                           | 1        | 3.13%   |
| ASUS P8H61-M LE/USB3                         | 1        | 3.13%   |
| ASUS M4A78T-E                                | 1        | 3.13%   |
| ASUS CROSSHAIR VI HERO                       | 1        | 3.13%   |
| ASUS All Series                              | 1        | 3.13%   |
| ASRock Z68 Extreme4 Gen3                     | 1        | 3.13%   |
| ASRock X570M Pro4                            | 1        | 3.13%   |
| ASRock X570 Steel Legend                     | 1        | 3.13%   |
| ASRock N68C-GS4 FX                           | 1        | 3.13%   |
| ASRock B450M Pro4                            | 1        | 3.13%   |
| Alienware X51 R2                             | 1        | 3.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| HP Pavilion         | 2        | 6.25%   |
| VS Company G31T-M   | 1        | 3.13%   |
| MSI MS-7D16         | 1        | 3.13%   |
| MSI MS-7C34         | 1        | 3.13%   |
| MSI MS-7B89         | 1        | 3.13%   |
| MSI MS-7A38         | 1        | 3.13%   |
| MSI MS-7A34         | 1        | 3.13%   |
| MSI MS-7A33         | 1        | 3.13%   |
| MSI MS-7817         | 1        | 3.13%   |
| MSI ESPRIMO         | 1        | 3.13%   |
| Lenovo IdeaCentre   | 1        | 3.13%   |
| Intel DG41WV        | 1        | 3.13%   |
| HP xw4400           | 1        | 3.13%   |
| HP EliteDesk        | 1        | 3.13%   |
| HP 200-5120br       | 1        | 3.13%   |
| Gigabyte B550       | 1        | 3.13%   |
| Gigabyte B250M-DS3H | 1        | 3.13%   |
| Fujitsu ESPRIMO     | 1        | 3.13%   |
| Dell Vostro         | 1        | 3.13%   |
| ASUS TUF            | 1        | 3.13%   |
| ASUS PRIME          | 1        | 3.13%   |
| ASUS P8H61-M        | 1        | 3.13%   |
| ASUS M4A78T-E       | 1        | 3.13%   |
| ASUS CROSSHAIR      | 1        | 3.13%   |
| ASUS All            | 1        | 3.13%   |
| ASRock Z68          | 1        | 3.13%   |
| ASRock X570M        | 1        | 3.13%   |
| ASRock X570         | 1        | 3.13%   |
| ASRock N68C-GS4     | 1        | 3.13%   |
| ASRock B450M        | 1        | 3.13%   |
| Alienware X51       | 1        | 3.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 7        | 21.88%  |
| 2018 | 5        | 15.63%  |
| 2010 | 5        | 15.63%  |
| 2019 | 4        | 12.5%   |
| 2020 | 3        | 9.38%   |
| 2016 | 3        | 9.38%   |
| 2011 | 2        | 6.25%   |
| 2017 | 1        | 3.13%   |
| 2015 | 1        | 3.13%   |
| 2009 | 1        | 3.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 32       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 31       | 96.88%  |
| Enabled  | 1        | 3.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 32       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 12       | 37.5%   |
| 64.01-256.0 | 5        | 15.63%  |
| 8.01-16.0   | 5        | 15.63%  |
| 32.01-64.0  | 4        | 12.5%   |
| 3.01-4.0    | 3        | 9.38%   |
| 4.01-8.0    | 2        | 6.25%   |
| 24.01-32.0  | 1        | 3.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 13       | 39.39%  |
| 4.01-8.0  | 7        | 21.21%  |
| 3.01-4.0  | 6        | 18.18%  |
| 2.01-3.0  | 5        | 15.15%  |
| 8.01-16.0 | 1        | 3.03%   |
| 0.51-1.0  | 1        | 3.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 10       | 31.25%  |
| 3      | 8        | 25%     |
| 2      | 8        | 25%     |
| 4      | 4        | 12.5%   |
| 6      | 2        | 6.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 17       | 53.13%  |
| No        | 15       | 46.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 31       | 96.88%  |
| No        | 1        | 3.13%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 20       | 62.5%   |
| No        | 12       | 37.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 53.13%  |
| Yes       | 15       | 46.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| Germany    | 8        | 25%     |
| USA        | 5        | 15.63%  |
| Brazil     | 4        | 12.5%   |
| Mexico     | 2        | 6.25%   |
| Japan      | 2        | 6.25%   |
| Australia  | 2        | 6.25%   |
| Spain      | 1        | 3.13%   |
| Slovakia   | 1        | 3.13%   |
| Russia     | 1        | 3.13%   |
| Poland     | 1        | 3.13%   |
| Luxembourg | 1        | 3.13%   |
| India      | 1        | 3.13%   |
| Hungary    | 1        | 3.13%   |
| Croatia    | 1        | 3.13%   |
| Belgium    | 1        | 3.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Tokyo                 | 2        | 6.25%   |
| Zagreb                | 1        | 3.13%   |
| Vijayawada            | 1        | 3.13%   |
| TrÃªs Lagoas          | 1        | 3.13%   |
| SÃ£o Paulo            | 1        | 3.13%   |
| Stupava               | 1        | 3.13%   |
| Stabroek              | 1        | 3.13%   |
| San Luis Potos?­ City | 1        | 3.13%   |
| Saint Albans          | 1        | 3.13%   |
| Recife                | 1        | 3.13%   |
| Oregon                | 1        | 3.13%   |
| Nordenham             | 1        | 3.13%   |
| Munich                | 1        | 3.13%   |
| Melbourne             | 1        | 3.13%   |
| McDonough             | 1        | 3.13%   |
| Mansfield             | 1        | 3.13%   |
| Madrid                | 1        | 3.13%   |
| Luxembourg            | 1        | 3.13%   |
| Lomonosov             | 1        | 3.13%   |
| Koleczkowo            | 1        | 3.13%   |
| Heinsberg             | 1        | 3.13%   |
| Hamelin               | 1        | 3.13%   |
| Halle                 | 1        | 3.13%   |
| Gelnhausen            | 1        | 3.13%   |
| G?¶d?¶ll?‘            | 1        | 3.13%   |
| Federal Way           | 1        | 3.13%   |
| Dornhan               | 1        | 3.13%   |
| Chapec??              | 1        | 3.13%   |
| Canc??n               | 1        | 3.13%   |
| Brisbane              | 1        | 3.13%   |
| Braunschweig          | 1        | 3.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 17       | 27     | 25.37%  |
| Seagate             | 10       | 12     | 14.93%  |
| Samsung Electronics | 10       | 17     | 14.93%  |
| Kingston            | 4        | 4      | 5.97%   |
| A-DATA Technology   | 4        | 4      | 5.97%   |
| SanDisk             | 3        | 4      | 4.48%   |
| Intel               | 3        | 3      | 4.48%   |
| Hitachi             | 3        | 4      | 4.48%   |
| Toshiba             | 2        | 2      | 2.99%   |
| Crucial             | 2        | 2      | 2.99%   |
| Unknown             | 1        | 1      | 1.49%   |
| TO Exter            | 1        | 1      | 1.49%   |
| Phison              | 1        | 1      | 1.49%   |
| Lite-On             | 1        | 1      | 1.49%   |
| JMicron             | 1        | 1      | 1.49%   |
| Inateck             | 1        | 1      | 1.49%   |
| HGST HTS            | 1        | 1      | 1.49%   |
| HGST                | 1        | 1      | 1.49%   |
| Fujitsu             | 1        | 1      | 1.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST3750528AS 752GB            | 2        | 2.6%    |
| Seagate ST2000DM006-2DM164 2TB       | 2        | 2.6%    |
| Samsung SSD 860 EVO 250GB            | 2        | 2.6%    |
| Samsung SSD 850 EVO 500GB            | 2        | 2.6%    |
| WDC WDS500G1X0E-00AFY0 500GB         | 1        | 1.3%    |
| WDC WDS500G1B0B-00AS40 500GB SSD     | 1        | 1.3%    |
| WDC WDS250G1B0C-00S6U0 250GB         | 1        | 1.3%    |
| WDC WDS100T3X0C-00SJG0 1TB           | 1        | 1.3%    |
| WDC WDS100T1X0E-00AFY0 1TB           | 1        | 1.3%    |
| WDC WD7500AALX-009BA0 752GB          | 1        | 1.3%    |
| WDC WD5000AAVS-00ZTB0 500GB          | 1        | 1.3%    |
| WDC WD5000AAKX-07U6AA0 500GB         | 1        | 1.3%    |
| WDC WD50 00LPCX-00VHAT0 500GB        | 1        | 1.3%    |
| WDC WD3200AAKS-00B3A0 320GB          | 1        | 1.3%    |
| WDC WD2500AAJS-00VTA0 250GB          | 1        | 1.3%    |
| WDC WD20EARX-00PASB0 2TB             | 1        | 1.3%    |
| WDC WD2005FBYZ-01YCBB2 2TB           | 1        | 1.3%    |
| WDC WD10EZEX-75WN4A0 1TB             | 1        | 1.3%    |
| WDC WD10EZEX-75M2NA0 1TB             | 1        | 1.3%    |
| WDC WD10EZEX-08WN4A0 1TB             | 1        | 1.3%    |
| WDC WD10EZEX-00KUWA0 1TB             | 1        | 1.3%    |
| WDC WD10EZEX-00BN5A0 1TB             | 1        | 1.3%    |
| WDC WD10EAVS-22D7B0 1TB              | 1        | 1.3%    |
| WDC WD10EACS-00D6B1 1TB              | 1        | 1.3%    |
| WDC WD1003FZEX-00K3CA0 1TB           | 1        | 1.3%    |
| WDC WD1001FALS-00E3A0 1TB            | 1        | 1.3%    |
| Unknown 128GB SATA FLASH DRIVE       | 1        | 1.3%    |
| Toshiba NVMe SSD Drive 256GB         | 1        | 1.3%    |
| Toshiba HDWD130 3TB                  | 1        | 1.3%    |
| TO Exter nal USB 3.0 1TB             | 1        | 1.3%    |
| Seagate ST500LM0 12 HN-M500MBB 500GB | 1        | 1.3%    |
| Seagate ST3750630AS 752GB            | 1        | 1.3%    |
| Seagate ST3160812AS 160GB            | 1        | 1.3%    |
| Seagate ST3000DM007-1WY10G 3TB       | 1        | 1.3%    |
| Seagate ST2000DM001-1ER164 2TB       | 1        | 1.3%    |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1        | 1.3%    |
| Seagate ST1000DM010-2EP102 1TB       | 1        | 1.3%    |
| Seagate ST1000DM003-1SB102 1TB       | 1        | 1.3%    |
| SanDisk SDSSDA240G 240GB             | 1        | 1.3%    |
| SanDisk SD7SB6S256G1001 256GB SSD    | 1        | 1.3%    |
| SanDisk SD7SB3Q-256G-1006 256GB SSD  | 1        | 1.3%    |
| Samsung SSD 980 PRO 1TB              | 1        | 1.3%    |
| Samsung SSD 970 EVO Plus 2TB         | 1        | 1.3%    |
| Samsung SSD 870 QVO 1TB              | 1        | 1.3%    |
| Samsung SSD 850 EVO 250GB            | 1        | 1.3%    |
| Samsung SSD 840 Series 120GB         | 1        | 1.3%    |
| Samsung MZVPV512HDGL-000H1 512GB     | 1        | 1.3%    |
| Samsung HD401LJ 400GB                | 1        | 1.3%    |
| Samsung HD105SI 1TB                  | 1        | 1.3%    |
| Samsung HD103SI 1TB                  | 1        | 1.3%    |
| Phison Viper M.2 VPN100 256GB        | 1        | 1.3%    |
| Lite-On NVMe SSD Drive 256GB         | 1        | 1.3%    |
| Kingston SV300S37A240G 240GB SSD     | 1        | 1.3%    |
| Kingston SV300S37A120G 120GB SSD     | 1        | 1.3%    |
| Kingston SA400S37480G 480GB SSD      | 1        | 1.3%    |
| Kingston SA400S37120G 120GB SSD      | 1        | 1.3%    |
| JMicron Generic 1TB                  | 1        | 1.3%    |
| Intel SSDSC2BW240A4 240GB            | 1        | 1.3%    |
| Intel SSDSC2BB012T7O 1TB             | 1        | 1.3%    |
| Intel NVMe SSD Drive 512GB           | 1        | 1.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 22     | 41.18%  |
| Seagate             | 10       | 12     | 29.41%  |
| Hitachi             | 3        | 4      | 8.82%   |
| Samsung Electronics | 2        | 5      | 5.88%   |
| Toshiba             | 1        | 1      | 2.94%   |
| TO Exter            | 1        | 1      | 2.94%   |
| Inateck             | 1        | 1      | 2.94%   |
| HGST                | 1        | 1      | 2.94%   |
| Fujitsu             | 1        | 1      | 2.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 9      | 23.81%  |
| Kingston            | 4        | 4      | 19.05%  |
| A-DATA Technology   | 4        | 4      | 19.05%  |
| SanDisk             | 3        | 4      | 14.29%  |
| Intel               | 2        | 2      | 9.52%   |
| WDC                 | 1        | 1      | 4.76%   |
| JMicron             | 1        | 1      | 4.76%   |
| Crucial             | 1        | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 24       | 48     | 43.64%  |
| SSD     | 19       | 26     | 34.55%  |
| NVMe    | 11       | 12     | 20%     |
| Unknown | 1        | 2      | 1.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 31       | 70     | 68.89%  |
| NVMe | 11       | 12     | 24.44%  |
| SAS  | 3        | 6      | 6.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.51-1.0   | 20       | 29     | 40.82%  |
| 0.01-0.5   | 19       | 32     | 38.78%  |
| 1.01-2.0   | 7        | 10     | 14.29%  |
| 2.01-3.0   | 2        | 2      | 4.08%   |
| 10.01-20.0 | 1        | 1      | 2.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 7        | 21.21%  |
| 1001-2000      | 7        | 21.21%  |
| 251-500        | 6        | 18.18%  |
| 2001-3000      | 5        | 15.15%  |
| 501-1000       | 4        | 12.12%  |
| 1-20           | 2        | 6.06%   |
| 101-250        | 1        | 3.03%   |
| Unknown        | 1        | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 6        | 17.65%  |
| 101-250        | 6        | 17.65%  |
| 501-1000       | 5        | 14.71%  |
| 51-100         | 5        | 14.71%  |
| 1001-2000      | 4        | 11.76%  |
| 1-20           | 4        | 11.76%  |
| 2001-3000      | 2        | 5.88%   |
| More than 3000 | 1        | 2.94%   |
| Unknown        | 1        | 2.94%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Kingston SV300S37A120G 120GB SSD | 1        | 1      | 50%     |
| Crucial CT1000P1SSD8 1TB         | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Kingston | 1        | 1      | 50%     |
| Crucial  | 1        | 1      | 50%     |

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
| NVMe | 1        | 1      | 50%     |
| SSD  | 1        | 1      | 50%     |

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
| Detected | 18       | 49     | 51.43%  |
| Works    | 15       | 37     | 42.86%  |
| Malfunc  | 2        | 2      | 5.71%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 18       | 38.3%   |
| AMD                          | 14       | 29.79%  |
| Sandisk                      | 4        | 8.51%   |
| Samsung Electronics          | 3        | 6.38%   |
| Toshiba America Info Systems | 1        | 2.13%   |
| Silicon Image                | 1        | 2.13%   |
| Phison Electronics           | 1        | 2.13%   |
| Nvidia                       | 1        | 2.13%   |
| Micron/Crucial Technology    | 1        | 2.13%   |
| Marvell Technology Group     | 1        | 2.13%   |
| Lite-On Technology           | 1        | 2.13%   |
| ASMedia Technology           | 1        | 2.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 11       | 18.64%  |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 6.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 5.08%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                              | 2        | 3.39%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 3.39%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 3.39%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 3.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 3.39%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 3.39%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 3.39%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 1        | 1.69%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1        | 1.69%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1        | 1.69%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 1.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 1.69%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 1.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 1.69%   |
| Phison E12 NVMe Controller                                                              | 1        | 1.69%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 1.69%   |
| Nvidia MCP61 IDE                                                                        | 1        | 1.69%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 1.69%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                                 | 1        | 1.69%   |
| Lite-On Non-Volatile memory controller                                                  | 1        | 1.69%   |
| Intel SSD 660P Series                                                                   | 1        | 1.69%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 1.69%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 1.69%   |
| Intel 82801GR/GDH (ICH7R/ICH7DH) SATA Controller [RAID mode]                            | 1        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 1.69%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 1.69%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.69%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 1.69%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 1        | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 1.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 26       | 55.32%  |
| NVMe | 11       | 23.4%   |
| IDE  | 7        | 14.89%  |
| RAID | 3        | 6.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 17       | 53.13%  |
| AMD    | 15       | 46.88%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 6.25%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 2        | 6.25%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 3.13%   |
| Intel Pentium CPU G3258 @ 3.20GHz           | 1        | 3.13%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 3.13%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 3.13%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 3.13%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 3.13%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 1        | 3.13%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 3.13%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 3.13%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 3.13%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1        | 3.13%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 3.13%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 3.13%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1        | 3.13%   |
| Intel Core 2 Quad CPU Q9300 @ 2.50GHz       | 1        | 3.13%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 1        | 3.13%   |
| Intel Core 2 CPU 6400 @ 2.13GHz             | 1        | 3.13%   |
| AMD Sempron 2650 APU with Radeon R3         | 1        | 3.13%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 1        | 3.13%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 1        | 3.13%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 1        | 3.13%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 1        | 3.13%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 1        | 3.13%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 1        | 3.13%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 1        | 3.13%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 1        | 3.13%   |
| AMD Phenom II X4 B50 Processor              | 1        | 3.13%   |
| AMD FX-8350 Eight-Core Processor            | 1        | 3.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 6        | 18.75%  |
| AMD Ryzen 7             | 5        | 15.63%  |
| Intel Core i7           | 4        | 12.5%   |
| AMD Ryzen 9             | 4        | 12.5%   |
| AMD Ryzen 5             | 3        | 9.38%   |
| Intel Core i3           | 2        | 6.25%   |
| Intel Pentium Dual-Core | 1        | 3.13%   |
| Intel Pentium           | 1        | 3.13%   |
| Intel Core 2 Quad       | 1        | 3.13%   |
| Intel Core 2 Duo        | 1        | 3.13%   |
| Intel Core 2            | 1        | 3.13%   |
| AMD Sempron             | 1        | 3.13%   |
| AMD Phenom II X4        | 1        | 3.13%   |
| AMD FX                  | 1        | 3.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 13       | 40.63%  |
| 2      | 6        | 18.75%  |
| 8      | 5        | 15.63%  |
| 6      | 4        | 12.5%   |
| 16     | 2        | 6.25%   |
| 12     | 2        | 6.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 32       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 19       | 59.38%  |
| 1      | 13       | 40.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 32       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 47.06%  |
| 0x906e9    | 2        | 5.88%   |
| 0x306c3    | 2        | 5.88%   |
| 0x206a7    | 2        | 5.88%   |
| 0x0a201009 | 2        | 5.88%   |
| 0x08001137 | 2        | 5.88%   |
| 0xa0653    | 1        | 2.94%   |
| 0x1067a    | 1        | 2.94%   |
| 0x10677    | 1        | 2.94%   |
| 0x0a201016 | 1        | 2.94%   |
| 0x08701021 | 1        | 2.94%   |
| 0x08108109 | 1        | 2.94%   |
| 0x0800820d | 1        | 2.94%   |
| 0x010000db | 1        | 2.94%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen         | 4        | 12.5%   |
| KabyLake    | 4        | 12.5%   |
| Zen 3       | 3        | 9.38%   |
| Zen 2       | 3        | 9.38%   |
| Penryn      | 3        | 9.38%   |
| Haswell     | 3        | 9.38%   |
| Zen+        | 2        | 6.25%   |
| Skylake     | 2        | 6.25%   |
| SandyBridge | 2        | 6.25%   |
| Piledriver  | 1        | 3.13%   |
| Nehalem     | 1        | 3.13%   |
| K10         | 1        | 3.13%   |
| Jaguar      | 1        | 3.13%   |
| Core        | 1        | 3.13%   |
| CometLake   | 1        | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 14       | 41.18%  |
| Intel  | 10       | 29.41%  |
| AMD    | 10       | 29.41%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 5.88%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 2        | 5.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 5.88%   |
| Intel HD Graphics 630                                                       | 2        | 5.88%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 5.88%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 2        | 5.88%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 5.88%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 2.94%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 2.94%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 2.94%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 2.94%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 2.94%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 2.94%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 2.94%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 2.94%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 2.94%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 1        | 2.94%   |
| Intel HD Graphics 530                                                       | 1        | 2.94%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 2.94%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 2.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 2.94%   |
| AMD RV610 [Radeon HD 2400 PRO]                                              | 1        | 2.94%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 1        | 2.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 2.94%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 2.94%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                     | 1        | 2.94%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 1        | 2.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 14       | 43.75%  |
| 1 x AMD    | 10       | 31.25%  |
| 1 x Intel  | 8        | 25%     |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 22       | 68.75%  |
| Proprietary | 9        | 28.13%  |
| Unknown     | 1        | 3.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 20       | 58.82%  |
| 3.01-4.0   | 3        | 8.82%   |
| 7.01-8.0   | 2        | 5.88%   |
| 16.01-24.0 | 2        | 5.88%   |
| 1.01-2.0   | 2        | 5.88%   |
| 8.01-16.0  | 2        | 5.88%   |
| 0.51-1.0   | 2        | 5.88%   |
| 5.01-6.0   | 1        | 2.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 6        | 16.67%  |
| Dell                 | 6        | 16.67%  |
| Samsung Electronics  | 5        | 13.89%  |
| Philips              | 3        | 8.33%   |
| BenQ                 | 3        | 8.33%   |
| Acer                 | 3        | 8.33%   |
| LG Electronics       | 2        | 5.56%   |
| Hewlett-Packard      | 2        | 5.56%   |
| Ancor Communications | 2        | 5.56%   |
| ViewSonic            | 1        | 2.78%   |
| TCL                  | 1        | 2.78%   |
| Denver               | 1        | 2.78%   |
| AOC                  | 1        | 2.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch             | 1        | 2.63%   |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                      | 1        | 2.63%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1        | 2.63%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 477x268mm 21.5-inch  | 1        | 2.63%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 1        | 2.63%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch     | 1        | 2.63%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 1        | 2.63%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch     | 1        | 2.63%   |
| Philips PHL 258B6QU PHL08F5 2560x1440 553x311mm 25.0-inch             | 1        | 2.63%   |
| Philips 150S PHL0812 1024x768 307x230mm 15.1-inch                     | 1        | 2.63%   |
| Philips 150S PHL0805 1024x768 307x230mm 15.1-inch                     | 1        | 2.63%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 1        | 2.63%   |
| LG Electronics LCD Monitor LG TV SSCR 3840x2160                       | 1        | 2.63%   |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch          | 1        | 2.63%   |
| Hewlett-Packard 27es HWP3326 1920x1080 598x336mm 27.0-inch            | 1        | 2.63%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                  | 1        | 2.63%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch           | 1        | 2.63%   |
| Goldstar L1718S GSM443C 1280x1024 338x270mm 17.0-inch                 | 1        | 2.63%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1        | 2.63%   |
| Goldstar E2742 GSM58C9 1920x1080 598x337mm 27.0-inch                  | 1        | 2.63%   |
| Goldstar E2441 GSM581F 1920x1080 531x299mm 24.0-inch                  | 1        | 2.63%   |
| Denver UWQHD-100-V2 LHC3500 3440x1440 798x342mm 34.2-inch             | 1        | 2.63%   |
| Dell UZ2315H DELF055 1920x1080 509x286mm 23.0-inch                    | 1        | 2.63%   |
| Dell U2711 DELA057 2560x1440 597x336mm 27.0-inch                      | 1        | 2.63%   |
| Dell S2216H DELD07A 1920x1080 476x268mm 21.5-inch                     | 1        | 2.63%   |
| Dell P2219H DELA114 1920x1080 476x267mm 21.5-inch                     | 1        | 2.63%   |
| Dell E228WFP DELD014 1680x1050 473x296mm 22.0-inch                    | 1        | 2.63%   |
| Dell 1703FP DEL3011 1280x1024 338x270mm 17.0-inch                     | 1        | 2.63%   |
| BenQ SW2700 BNQ7F47 2560x1440 596x335mm 26.9-inch                     | 1        | 2.63%   |
| BenQ PD2500Q BNQ802A 2560x1440 553x311mm 25.0-inch                    | 1        | 2.63%   |
| BenQ BL2405 BNQ8016 1920x1080 531x298mm 24.0-inch                     | 1        | 2.63%   |
| AOC LCD Monitor 28E850 640x480                                        | 1        | 2.63%   |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 408x255mm 18.9-inch  | 1        | 2.63%   |
| Ancor Communications ASUS VN248 ACI24C4 1920x1080 530x300mm 24.0-inch | 1        | 2.63%   |
| Acer X163W ACR0015 1366x768 344x193mm 15.5-inch                       | 1        | 2.63%   |
| Acer V203H ACR0102 1600x900 443x249mm 20.0-inch                       | 1        | 2.63%   |
| Acer V203H ACR00C7 1600x900 443x249mm 20.0-inch                       | 1        | 2.63%   |
| Acer GD245HQ ACR0125 1920x1080 520x290mm 23.4-inch                    | 1        | 2.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 12       | 37.5%   |
| 2560x1440 (QHD)    | 4        | 12.5%   |
| 3840x2160 (4K)     | 3        | 9.38%   |
| 3440x1440          | 2        | 6.25%   |
| 2560x1080          | 2        | 6.25%   |
| 1280x1024 (SXGA)   | 2        | 6.25%   |
| 1024x768 (XGA)     | 2        | 6.25%   |
| 640x480            | 1        | 3.13%   |
| 1680x1050 (WSXGA+) | 1        | 3.13%   |
| 1600x900 (HD+)     | 1        | 3.13%   |
| 1440x900 (WXGA+)   | 1        | 3.13%   |
| 1366x768 (WXGA)    | 1        | 3.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 6        | 18.18%  |
| 21      | 5        | 15.15%  |
| 34      | 3        | 9.09%   |
| 15      | 3        | 9.09%   |
| Unknown | 3        | 9.09%   |
| 24      | 2        | 6.06%   |
| 23      | 2        | 6.06%   |
| 17      | 2        | 6.06%   |
| 32      | 1        | 3.03%   |
| 31      | 1        | 3.03%   |
| 25      | 1        | 3.03%   |
| 22      | 1        | 3.03%   |
| 20      | 1        | 3.03%   |
| 19      | 1        | 3.03%   |
| 18      | 1        | 3.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 10       | 30.3%   |
| 401-500     | 9        | 27.27%  |
| 301-350     | 5        | 15.15%  |
| 701-800     | 4        | 12.12%  |
| Unknown     | 3        | 9.09%   |
| 601-700     | 2        | 6.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 19       | 61.29%  |
| 21/9    | 3        | 9.68%   |
| Unknown | 3        | 9.68%   |
| 5/4     | 2        | 6.45%   |
| 4/3     | 2        | 6.45%   |
| 16/10   | 2        | 6.45%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 9        | 27.27%  |
| 301-350        | 6        | 18.18%  |
| 351-500        | 5        | 15.15%  |
| 151-200        | 3        | 9.09%   |
| 141-150        | 3        | 9.09%   |
| 101-110        | 3        | 9.09%   |
| Unknown        | 3        | 9.09%   |
| 251-300        | 1        | 3.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 17       | 53.13%  |
| 101-120 | 11       | 34.38%  |
| Unknown | 3        | 9.38%   |
| 121-160 | 1        | 3.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 23       | 71.88%  |
| 2     | 6        | 18.75%  |
| 0     | 2        | 6.25%   |
| 3     | 1        | 3.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 22       | 47.83%  |
| Intel                 | 11       | 23.91%  |
| Qualcomm Atheros      | 4        | 8.7%    |
| Ralink                | 3        | 6.52%   |
| Samsung Electronics   | 1        | 2.17%   |
| NetXen Incorporated   | 1        | 2.17%   |
| D-Link System         | 1        | 2.17%   |
| Broadcom Limited      | 1        | 2.17%   |
| Broadcom              | 1        | 2.17%   |
| AVM                   | 1        | 2.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 17       | 30.91%  |
| Intel Wi-Fi 6 AX200                                                        | 3        | 5.45%   |
| Intel I211 Gigabit Network Connection                                      | 3        | 5.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 2        | 3.64%   |
| Realtek RTL8125 2.5GbE Controller                                          | 2        | 3.64%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 1.82%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 1        | 1.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 1        | 1.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1        | 1.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 1        | 1.82%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1        | 1.82%   |
| Realtek Killer E3000 2.5GbE Controller                                     | 1        | 1.82%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                           | 1        | 1.82%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1        | 1.82%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                       | 1        | 1.82%   |
| Ralink RT2561/RT61 802.11g PCI                                             | 1        | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 1        | 1.82%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 1        | 1.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 1        | 1.82%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                  | 1        | 1.82%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 1.82%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter       | 1        | 1.82%   |
| Intel Wireless-AC 9260                                                     | 1        | 1.82%   |
| Intel Wireless 8260                                                        | 1        | 1.82%   |
| Intel Wireless 7260                                                        | 1        | 1.82%   |
| Intel Tiger Lake PCH CNVi WiFi                                             | 1        | 1.82%   |
| Intel Ethernet Connection (2) I219-LM                                      | 1        | 1.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 1        | 1.82%   |
| Intel 82574L Gigabit Network Connection                                    | 1        | 1.82%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 1        | 1.82%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                            | 1        | 1.82%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                 | 1        | 1.82%   |
| AVM Fritz!WLAN N v2 [Atheros AR9271]                                       | 1        | 1.82%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 8        | 40%     |
| Realtek Semiconductor | 4        | 20%     |
| Ralink                | 3        | 15%     |
| Qualcomm Atheros      | 2        | 10%     |
| D-Link System         | 1        | 5%      |
| Broadcom Limited      | 1        | 5%      |
| AVM                   | 1        | 5%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 3        | 15%     |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 2        | 10%     |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 1        | 5%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 1        | 5%      |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1        | 5%      |
| Ralink RT3060 Wireless 802.11n 1T/1R                                       | 1        | 5%      |
| Ralink RT2561/RT61 802.11g PCI                                             | 1        | 5%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 1        | 5%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 1        | 5%      |
| Intel Wireless-AC 9260                                                     | 1        | 5%      |
| Intel Wireless 8260                                                        | 1        | 5%      |
| Intel Wireless 7260                                                        | 1        | 5%      |
| Intel Tiger Lake PCH CNVi WiFi                                             | 1        | 5%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 1        | 5%      |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 1        | 5%      |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                 | 1        | 5%      |
| AVM Fritz!WLAN N v2 [Atheros AR9271]                                       | 1        | 5%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 22       | 66.67%  |
| Intel                 | 5        | 15.15%  |
| Qualcomm Atheros      | 3        | 9.09%   |
| Samsung Electronics   | 1        | 3.03%   |
| NetXen Incorporated   | 1        | 3.03%   |
| Broadcom              | 1        | 3.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 17       | 48.57%  |
| Intel I211 Gigabit Network Connection                                | 3        | 8.57%   |
| Realtek RTL8125 2.5GbE Controller                                    | 2        | 5.71%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 1        | 2.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 1        | 2.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 1        | 2.86%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                           | 1        | 2.86%   |
| Realtek Killer E3000 2.5GbE Controller                               | 1        | 2.86%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 1        | 2.86%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                            | 1        | 2.86%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 1        | 2.86%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 1        | 2.86%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter | 1        | 2.86%   |
| Intel Ethernet Connection (2) I219-LM                                | 1        | 2.86%   |
| Intel 82574L Gigabit Network Connection                              | 1        | 2.86%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                      | 1        | 2.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 31       | 60.78%  |
| WiFi     | 20       | 39.22%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 28       | 63.64%  |
| WiFi     | 16       | 36.36%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 15       | 46.88%  |
| 1     | 14       | 43.75%  |
| 3     | 2        | 6.25%   |
| 5     | 1        | 3.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 26       | 78.79%  |
| Yes  | 7        | 21.21%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 6        | 40%     |
| Cambridge Silicon Radio         | 3        | 20%     |
| Realtek Semiconductor           | 2        | 13.33%  |
| Qualcomm Atheros Communications | 2        | 13.33%  |
| Dell                            | 1        | 6.67%   |
| Belkin Components               | 1        | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 3        | 20%     |
| Realtek  Bluetooth 4.2 Adapter                        | 2        | 13.33%  |
| Intel AX200 Bluetooth                                 | 2        | 13.33%  |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 6.67%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1        | 6.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 6.67%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 6.67%   |
| Intel Bluetooth wireless interface                    | 1        | 6.67%   |
| Intel Bluetooth Device                                | 1        | 6.67%   |
| Dell Broadcom BCM20702A0 Bluetooth                    | 1        | 6.67%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 1        | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| AMD                       | 19       | 33.93%  |
| Intel                     | 16       | 28.57%  |
| Nvidia                    | 15       | 26.79%  |
| C-Media Electronics       | 2        | 3.57%   |
| Texas Instruments         | 1        | 1.79%   |
| Sennheiser Communications | 1        | 1.79%   |
| Creative Labs             | 1        | 1.79%   |
| BEHRINGER International   | 1        | 1.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 9.52%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5        | 7.94%   |
| Nvidia GA102 High Definition Audio Controller                              | 3        | 4.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 4.76%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 4.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 3.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 3.17%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 3.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 3.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 3.17%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 2        | 3.17%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 3.17%   |
| Texas Instruments PCM2900C Audio CODEC                                     | 1        | 1.59%   |
| Sennheiser Communications Sennheiser 3D G4ME1                              | 1        | 1.59%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 1.59%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 1.59%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1.59%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 1.59%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.59%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 1.59%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 1.59%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 1.59%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 1.59%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 1.59%   |
| Intel Audio device                                                         | 1        | 1.59%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 1.59%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 1.59%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 1        | 1.59%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 1        | 1.59%   |
| C-Media Electronics CM108 Audio Controller                                 | 1        | 1.59%   |
| BEHRINGER International UMC202HD 192k                                      | 1        | 1.59%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 1.59%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]          | 1        | 1.59%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1        | 1.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 1.59%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 1.59%   |
| AMD Kabini HDMI/DP Audio                                                   | 1        | 1.59%   |
| AMD FCH Azalia Controller                                                  | 1        | 1.59%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 1        | 1.59%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 1.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 4        | 22.22%  |
| G.Skill             | 4        | 22.22%  |
| Crucial             | 4        | 22.22%  |
| Unknown             | 2        | 11.11%  |
| Samsung Electronics | 1        | 5.56%   |
| Micron Technology   | 1        | 5.56%   |
| GeIL                | 1        | 5.56%   |
| Corsair             | 1        | 5.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Kingston RAM KHX3600C18D4/32GX 32GB DIMM DDR4 3600MT/s     | 2        | 11.11%  |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s               | 1        | 5.56%   |
| Unknown RAM 992124 (997124) 8GB DIMM DDR3 1600MT/s         | 1        | 5.56%   |
| Samsung RAM M471B5673FH0-CH9 2GB DIMM DDR3 4199MT/s        | 1        | 5.56%   |
| Micron RAM 16JTF1G64AZ-1G6D1 8GB DIMM DDR3 1600MT/s        | 1        | 5.56%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s     | 1        | 5.56%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s          | 1        | 5.56%   |
| GeIL RAM CL11-11-11 D3-1600 4GB DIMM DDR3 1600MT/s         | 1        | 5.56%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s        | 1        | 5.56%   |
| G.Skill RAM F4-3200C15-16GTZKY 16384MB DIMM DDR4 3200MT/s  | 1        | 5.56%   |
| G.Skill RAM F4-2666C19-16GIS 16384MB DIMM DDR4 2667MT/s    | 1        | 5.56%   |
| G.Skill RAM F4-2400C15-8GNT 8GB DIMM DDR4 2400MT/s         | 1        | 5.56%   |
| Crucial RAM CT16G4DFRA266.C16FE 16384MB DIMM DDR4 2667MT/s | 1        | 5.56%   |
| Crucial RAM CT102464BD160B.M16 8GB DIMM DDR3 1600MT/s      | 1        | 5.56%   |
| Crucial RAM BLS16G4D32AESB.M16FE 16GB DIMM DDR4 3400MT/s   | 1        | 5.56%   |
| Crucial RAM BL32G32C16U4R.M16FB1 32GB DIMM DDR4 3200MT/s   | 1        | 5.56%   |
| Corsair RAM CMK16GX4M1E3200C16 16384MB DIMM DDR4 3000MT/s  | 1        | 5.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 12       | 75%     |
| DDR3  | 3        | 18.75%  |
| SDRAM | 1        | 6.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 16       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 6        | 37.5%   |
| 8192  | 6        | 37.5%   |
| 32768 | 3        | 18.75%  |
| 2048  | 1        | 6.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 3        | 17.65%  |
| 3200  | 3        | 17.65%  |
| 1600  | 3        | 17.65%  |
| 2667  | 2        | 11.76%  |
| 4199  | 1        | 5.88%   |
| 3400  | 1        | 5.88%   |
| 3000  | 1        | 5.88%   |
| 2933  | 1        | 5.88%   |
| 2400  | 1        | 5.88%   |
| 800   | 1        | 5.88%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 2        | 33.33%  |
| Samsung Electronics | 1        | 16.67%  |
| Kyocera             | 1        | 16.67%  |
| Hewlett-Packard     | 1        | 16.67%  |
| Canon               | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| Samsung SCX-4200 series   | 1        | 16.67%  |
| Kyocera FS-1030D printer  | 1        | 16.67%  |
| HP ENVY 4500 series       | 1        | 16.67%  |
| Canon CanoScan LiDE 300   | 1        | 16.67%  |
| Brother Printer           | 1        | 16.67%  |
| Brother HL-L3210CW series | 1        | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1        | 50%     |
| Canon CanoScan LiDE 210       | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 5        | 62.5%   |
| Z-Star Microelectronics | 1        | 12.5%   |
| Creative Technology     | 1        | 12.5%   |
| Chicony Electronics     | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech Webcam C270          | 2        | 25%     |
| Logitech B525 HD Webcam       | 2        | 25%     |
| Z-Star Venus USB2.0 Camera    | 1        | 12.5%   |
| Logitech Webcam C250          | 1        | 12.5%   |
| Creative Live! Cam Sync 1080p | 1        | 12.5%   |
| Chicony HP Webcam             | 1        | 12.5%   |

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
| 0     | 28       | 87.5%   |
| 1     | 4        | 12.5%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 2        | 50%     |
| Net/wireless  | 1        | 25%     |
| Bluetooth     | 1        | 25%     |

