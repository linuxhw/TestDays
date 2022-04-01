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

Total: 79

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek    | H81M-R                      | [6fffff17df](https://linux-hardware.org/?probe=6fffff17df) | Mar 27, 2022 |
| ASUSTek    | H81M-R                      | [0d4d2c1358](https://linux-hardware.org/?probe=0d4d2c1358) | Mar 27, 2022 |
| MSI        | B450 TOMAHAWK               | [4345817b16](https://linux-hardware.org/?probe=4345817b16) | Mar 23, 2022 |
| Lenovo     | 102F SDK0J40697 WIN 3305... | [adce0625d3](https://linux-hardware.org/?probe=adce0625d3) | Mar 20, 2022 |
| Gigabyte   | B75M-D3H                    | [53ca03e8ec](https://linux-hardware.org/?probe=53ca03e8ec) | Mar 17, 2022 |
| Gigabyte   | F2A68HM-DS2                 | [455f94f1d3](https://linux-hardware.org/?probe=455f94f1d3) | Mar 04, 2022 |
| HP         | 2129                        | [a6b5f98b78](https://linux-hardware.org/?probe=a6b5f98b78) | Mar 02, 2022 |
| Intel      | DG41WV AAE90316-104         | [b6dc38eb16](https://linux-hardware.org/?probe=b6dc38eb16) | Feb 25, 2022 |
| MSI        | B450 TOMAHAWK               | [362c220f2d](https://linux-hardware.org/?probe=362c220f2d) | Feb 20, 2022 |
| MSI        | B450 TOMAHAWK               | [b3ff58ce92](https://linux-hardware.org/?probe=b3ff58ce92) | Feb 06, 2022 |
| ASRock     | Z68 Extreme4 Gen3           | [29ea90b598](https://linux-hardware.org/?probe=29ea90b598) | Feb 06, 2022 |
| MSI        | B450 TOMAHAWK               | [2f03547791](https://linux-hardware.org/?probe=2f03547791) | Feb 05, 2022 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [6423454dd8](https://linux-hardware.org/?probe=6423454dd8) | Jan 28, 2022 |
| ASUSTek    | H97M-E                      | [394132a26d](https://linux-hardware.org/?probe=394132a26d) | Jan 22, 2022 |
| ASUSTek    | H97M-E                      | [83e0c18dcb](https://linux-hardware.org/?probe=83e0c18dcb) | Jan 22, 2022 |
| ASUSTek    | H81M-R                      | [ea01dd4007](https://linux-hardware.org/?probe=ea01dd4007) | Jan 18, 2022 |
| ASUSTek    | H81M-R                      | [f65a651e3c](https://linux-hardware.org/?probe=f65a651e3c) | Jan 18, 2022 |
| Gigabyte   | G31M-S2C                    | [88d5bd947a](https://linux-hardware.org/?probe=88d5bd947a) | Jan 17, 2022 |
| ASUSTek    | H81M-R                      | [d8e311c6cc](https://linux-hardware.org/?probe=d8e311c6cc) | Jan 17, 2022 |
| ASUSTek    | H81M-R                      | [cf10bab7ad](https://linux-hardware.org/?probe=cf10bab7ad) | Jan 17, 2022 |
| Biostar    | H77MU3                      | [da779dbb31](https://linux-hardware.org/?probe=da779dbb31) | Jan 15, 2022 |
| ASUSTek    | H97M-E                      | [abf3b9c5c8](https://linux-hardware.org/?probe=abf3b9c5c8) | Jan 14, 2022 |
| ASUSTek    | H97M-E                      | [54fb155ee1](https://linux-hardware.org/?probe=54fb155ee1) | Jan 14, 2022 |
| ASUSTek    | M5A99X EVO R2.0             | [894589da9f](https://linux-hardware.org/?probe=894589da9f) | Jan 11, 2022 |
| Gigabyte   | GA-770TA-UD3                | [cda49a0b67](https://linux-hardware.org/?probe=cda49a0b67) | Jan 10, 2022 |
| ASUSTek    | TUF GAMING X570-PLUS        | [4c9489e27a](https://linux-hardware.org/?probe=4c9489e27a) | Jan 10, 2022 |
| HP         | 2B29                        | [cfb166f99c](https://linux-hardware.org/?probe=cfb166f99c) | Jan 10, 2022 |
| ASUSTek    | M5A99X EVO R2.0             | [980348cf8f](https://linux-hardware.org/?probe=980348cf8f) | Jan 09, 2022 |
| ASUSTek    | Z97-K                       | [87ffc81034](https://linux-hardware.org/?probe=87ffc81034) | Jan 08, 2022 |
| Dell       | 0RY007                      | [d51d13fdd1](https://linux-hardware.org/?probe=d51d13fdd1) | Dec 31, 2021 |
| ASUSTek    | ROG CROSSHAIR VIII HERO     | [559c6e472e](https://linux-hardware.org/?probe=559c6e472e) | Dec 30, 2021 |
| ASUSTek    | P8Z77-V LX                  | [6f6aeab7c1](https://linux-hardware.org/?probe=6f6aeab7c1) | Dec 20, 2021 |
| ASUSTek    | PRIME A320M-E               | [c008e360e7](https://linux-hardware.org/?probe=c008e360e7) | Dec 19, 2021 |
| ASUSTek    | P9X79 PRO                   | [ca4a106ccf](https://linux-hardware.org/?probe=ca4a106ccf) | Dec 18, 2021 |
| ASUSTek    | P8Z77-V LX                  | [1ff9d84c5f](https://linux-hardware.org/?probe=1ff9d84c5f) | Dec 17, 2021 |
| ASUSTek    | P8Z77-V LX                  | [a5ddb2410e](https://linux-hardware.org/?probe=a5ddb2410e) | Dec 16, 2021 |
| ASUSTek    | P8Z77-V LX                  | [e744dbe03d](https://linux-hardware.org/?probe=e744dbe03d) | Dec 15, 2021 |
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


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.3.18-59.37-default        | 12       | 21.43%  |
| 5.3.18-59.19-default        | 8        | 14.29%  |
| 5.3.18-59.27-default        | 5        | 8.93%   |
| 5.3.18-59.5-default         | 4        | 7.14%   |
| 5.3.18-59.24-default        | 4        | 7.14%   |
| 5.3.18-59.10-default        | 3        | 5.36%   |
| 5.3.18-57-default           | 3        | 5.36%   |
| 5.3.18-150300.59.54-default | 3        | 5.36%   |
| 5.3.18-150300.59.49-default | 3        | 5.36%   |
| 5.3.18-150300.59.43-default | 2        | 3.57%   |
| 5.3.18-lp152.57-default     | 1        | 1.79%   |
| 5.3.18-59.37-preempt        | 1        | 1.79%   |
| 5.3.18-59.34-default        | 1        | 1.79%   |
| 5.3.18-59.27-preempt        | 1        | 1.79%   |
| 5.3.18-59.24-preempt        | 1        | 1.79%   |
| 5.3.18-59.19-preempt        | 1        | 1.79%   |
| 5.3.18-59.16-default        | 1        | 1.79%   |
| 5.3.18-59.13-default        | 1        | 1.79%   |
| 5.3.18-150300.59.49-preempt | 1        | 1.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.3.18  | 51       | 100%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.3     | 51       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 51       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE5       | 23       | 43.4%   |
| Unknown    | 11       | 20.75%  |
| KDE        | 9        | 16.98%  |
| GNOME      | 6        | 11.32%  |
| XFCE       | 3        | 5.66%   |
| X-Cinnamon | 1        | 1.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 42       | 80.77%  |
| Tty     | 7        | 13.46%  |
| Wayland | 3        | 5.77%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 31       | 58.49%  |
| SDDM    | 10       | 18.87%  |
| LightDM | 10       | 18.87%  |
| XDM     | 2        | 3.77%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 12       | 23.53%  |
| de_DE   | 11       | 21.57%  |
| POSIX   | 7        | 13.73%  |
| pt_BR   | 4        | 7.84%   |
| ru_RU   | 2        | 3.92%   |
| es_ES   | 2        | 3.92%   |
| Unknown | 2        | 3.92%   |
| tr_TR   | 1        | 1.96%   |
| sk_SK   | 1        | 1.96%   |
| pl_PL   | 1        | 1.96%   |
| nl_NL   | 1        | 1.96%   |
| nl_BE   | 1        | 1.96%   |
| hr_HR   | 1        | 1.96%   |
| fi_FI   | 1        | 1.96%   |
| es_MX   | 1        | 1.96%   |
| en_GB   | 1        | 1.96%   |
| en_AU   | 1        | 1.96%   |
| ca_AD   | 1        | 1.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 30       | 57.69%  |
| EFI  | 22       | 42.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 32       | 61.54%  |
| Ext4    | 16       | 30.77%  |
| Xfs     | 3        | 5.77%   |
| Overlay | 1        | 1.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 25       | 47.17%  |
| Unknown | 24       | 45.28%  |
| MBR     | 4        | 7.55%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 42       | 79.25%  |
| Yes       | 11       | 20.75%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 37       | 72.55%  |
| Yes       | 14       | 27.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 15       | 29.41%  |
| MSI                 | 9        | 17.65%  |
| Hewlett-Packard     | 7        | 13.73%  |
| Gigabyte Technology | 6        | 11.76%  |
| ASRock              | 5        | 9.8%    |
| Lenovo              | 2        | 3.92%   |
| Dell                | 2        | 3.92%   |
| VS Company          | 1        | 1.96%   |
| Intel               | 1        | 1.96%   |
| Fujitsu             | 1        | 1.96%   |
| Biostar             | 1        | 1.96%   |
| Alienware           | 1        | 1.96%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Desktops | Percent |
|----------------------------------------------|----------|---------|
| ASUS All Series                              | 3        | 5.88%   |
| VS Company G31T-M                            | 1        | 1.96%   |
| MSI MS-7D16                                  | 1        | 1.96%   |
| MSI MS-7C34                                  | 1        | 1.96%   |
| MSI MS-7C02                                  | 1        | 1.96%   |
| MSI MS-7B89                                  | 1        | 1.96%   |
| MSI MS-7A38                                  | 1        | 1.96%   |
| MSI MS-7A34                                  | 1        | 1.96%   |
| MSI MS-7A33                                  | 1        | 1.96%   |
| MSI MS-7817                                  | 1        | 1.96%   |
| MSI ESPRIMO P1510                            | 1        | 1.96%   |
| Lenovo ThinkStation P500 30A6S4JU00          | 1        | 1.96%   |
| Lenovo IdeaCentre Y710 Cube-15ISH 90FL004WGE | 1        | 1.96%   |
| Intel DG41WV AAE90316-104                    | 1        | 1.96%   |
| HP Z840 Workstation                          | 1        | 1.96%   |
| HP xw4400 Workstation                        | 1        | 1.96%   |
| HP Pavilion Gaming Desktop 790-00xx          | 1        | 1.96%   |
| HP Pavilion Gaming Desktop 690-00xx          | 1        | 1.96%   |
| HP EliteDesk 800 G2 DM 65W                   | 1        | 1.96%   |
| HP 550-a114                                  | 1        | 1.96%   |
| HP 200-5120br                                | 1        | 1.96%   |
| Gigabyte GA-770TA-UD3                        | 1        | 1.96%   |
| Gigabyte G31M-ES2C                           | 1        | 1.96%   |
| Gigabyte F2A68HM-DS2                         | 1        | 1.96%   |
| Gigabyte B75M-D3H                            | 1        | 1.96%   |
| Gigabyte B550 AORUS PRO AC                   | 1        | 1.96%   |
| Gigabyte B250M-DS3H                          | 1        | 1.96%   |
| Fujitsu ESPRIMO P520                         | 1        | 1.96%   |
| Dell Vostro 3268                             | 1        | 1.96%   |
| Dell Inspiron 530                            | 1        | 1.96%   |
| Biostar H77MU3                               | 1        | 1.96%   |
| ASUS TUF GAMING X570-PLUS                    | 1        | 1.96%   |
| ASUS TUF B450-PRO GAMING                     | 1        | 1.96%   |
| ASUS ROG STRIX X570-E GAMING                 | 1        | 1.96%   |
| ASUS ROG CROSSHAIR VIII HERO                 | 1        | 1.96%   |
| ASUS PRIME H310M-A                           | 1        | 1.96%   |
| ASUS PRIME A320M-E                           | 1        | 1.96%   |
| ASUS P9X79 PRO                               | 1        | 1.96%   |
| ASUS P8Z77-V LX                              | 1        | 1.96%   |
| ASUS P8H61-M LE/USB3                         | 1        | 1.96%   |
| ASUS M5A99X EVO R2.0                         | 1        | 1.96%   |
| ASUS M4A78T-E                                | 1        | 1.96%   |
| ASUS CROSSHAIR VI HERO                       | 1        | 1.96%   |
| ASRock Z68 Extreme4 Gen3                     | 1        | 1.96%   |
| ASRock X570M Pro4                            | 1        | 1.96%   |
| ASRock X570 Steel Legend                     | 1        | 1.96%   |
| ASRock N68C-GS4 FX                           | 1        | 1.96%   |
| ASRock B450M Pro4                            | 1        | 1.96%   |
| Alienware X51 R2                             | 1        | 1.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS All              | 3        | 5.88%   |
| HP Pavilion           | 2        | 3.92%   |
| ASUS TUF              | 2        | 3.92%   |
| ASUS ROG              | 2        | 3.92%   |
| ASUS PRIME            | 2        | 3.92%   |
| VS Company G31T-M     | 1        | 1.96%   |
| MSI MS-7D16           | 1        | 1.96%   |
| MSI MS-7C34           | 1        | 1.96%   |
| MSI MS-7C02           | 1        | 1.96%   |
| MSI MS-7B89           | 1        | 1.96%   |
| MSI MS-7A38           | 1        | 1.96%   |
| MSI MS-7A34           | 1        | 1.96%   |
| MSI MS-7A33           | 1        | 1.96%   |
| MSI MS-7817           | 1        | 1.96%   |
| MSI ESPRIMO           | 1        | 1.96%   |
| Lenovo ThinkStation   | 1        | 1.96%   |
| Lenovo IdeaCentre     | 1        | 1.96%   |
| Intel DG41WV          | 1        | 1.96%   |
| HP Z840               | 1        | 1.96%   |
| HP xw4400             | 1        | 1.96%   |
| HP EliteDesk          | 1        | 1.96%   |
| HP 550-a114           | 1        | 1.96%   |
| HP 200-5120br         | 1        | 1.96%   |
| Gigabyte GA-770TA-UD3 | 1        | 1.96%   |
| Gigabyte G31M-ES2C    | 1        | 1.96%   |
| Gigabyte F2A68HM-DS2  | 1        | 1.96%   |
| Gigabyte B75M-D3H     | 1        | 1.96%   |
| Gigabyte B550         | 1        | 1.96%   |
| Gigabyte B250M-DS3H   | 1        | 1.96%   |
| Fujitsu ESPRIMO       | 1        | 1.96%   |
| Dell Vostro           | 1        | 1.96%   |
| Dell Inspiron         | 1        | 1.96%   |
| Biostar H77MU3        | 1        | 1.96%   |
| ASUS P9X79            | 1        | 1.96%   |
| ASUS P8Z77-V          | 1        | 1.96%   |
| ASUS P8H61-M          | 1        | 1.96%   |
| ASUS M5A99X           | 1        | 1.96%   |
| ASUS M4A78T-E         | 1        | 1.96%   |
| ASUS CROSSHAIR        | 1        | 1.96%   |
| ASRock Z68            | 1        | 1.96%   |
| ASRock X570M          | 1        | 1.96%   |
| ASRock X570           | 1        | 1.96%   |
| ASRock N68C-GS4       | 1        | 1.96%   |
| ASRock B450M          | 1        | 1.96%   |
| Alienware X51         | 1        | 1.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 9        | 17.65%  |
| 2018 | 6        | 11.76%  |
| 2014 | 6        | 11.76%  |
| 2012 | 5        | 9.8%    |
| 2021 | 4        | 7.84%   |
| 2015 | 3        | 5.88%   |
| 2010 | 3        | 5.88%   |
| 2009 | 3        | 5.88%   |
| 2017 | 2        | 3.92%   |
| 2016 | 2        | 3.92%   |
| 2013 | 2        | 3.92%   |
| 2011 | 2        | 3.92%   |
| 2020 | 1        | 1.96%   |
| 2008 | 1        | 1.96%   |
| 2007 | 1        | 1.96%   |
| 2006 | 1        | 1.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 51       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 49       | 96.08%  |
| Enabled  | 2        | 3.92%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 51       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 19       | 37.25%  |
| 8.01-16.0   | 9        | 17.65%  |
| 64.01-256.0 | 7        | 13.73%  |
| 32.01-64.0  | 6        | 11.76%  |
| 3.01-4.0    | 5        | 9.8%    |
| 4.01-8.0    | 4        | 7.84%   |
| 24.01-32.0  | 1        | 1.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 15       | 27.78%  |
| 4.01-8.0   | 13       | 24.07%  |
| 2.01-3.0   | 10       | 18.52%  |
| 3.01-4.0   | 9        | 16.67%  |
| 8.01-16.0  | 3        | 5.56%   |
| 0.51-1.0   | 3        | 5.56%   |
| 32.01-64.0 | 1        | 1.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 17       | 33.33%  |
| 1      | 13       | 25.49%  |
| 3      | 10       | 19.61%  |
| 4      | 6        | 11.76%  |
| 6      | 3        | 5.88%   |
| 7      | 1        | 1.96%   |
| 5      | 1        | 1.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 29       | 56.86%  |
| No        | 22       | 43.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 50       | 98.04%  |
| No        | 1        | 1.96%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 30       | 57.69%  |
| No        | 22       | 42.31%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 51.92%  |
| Yes       | 25       | 48.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Germany     | 13       | 25%     |
| USA         | 9        | 17.31%  |
| Brazil      | 5        | 9.62%   |
| Russia      | 3        | 5.77%   |
| Australia   | 3        | 5.77%   |
| Slovakia    | 2        | 3.85%   |
| Netherlands | 2        | 3.85%   |
| Mexico      | 2        | 3.85%   |
| Japan       | 2        | 3.85%   |
| Turkey      | 1        | 1.92%   |
| Spain       | 1        | 1.92%   |
| Poland      | 1        | 1.92%   |
| Peru        | 1        | 1.92%   |
| Luxembourg  | 1        | 1.92%   |
| India       | 1        | 1.92%   |
| Hungary     | 1        | 1.92%   |
| Finland     | 1        | 1.92%   |
| Croatia     | 1        | 1.92%   |
| Belgium     | 1        | 1.92%   |
| Andorra     | 1        | 1.92%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Tokyo                   | 2        | 3.85%   |
| Kiel                    | 2        | 3.85%   |
| Zagreb                  | 1        | 1.92%   |
| Voerde                  | 1        | 1.92%   |
| Vijayawada              | 1        | 1.92%   |
| TrГЄs Lagoas          | 1        | 1.92%   |
| Texarkana               | 1        | 1.92%   |
| Tacna                   | 1        | 1.92%   |
| Sydney                  | 1        | 1.92%   |
| Stupava                 | 1        | 1.92%   |
| Stabroek                | 1        | 1.92%   |
| Sao Paulo               | 1        | 1.92%   |
| San Luis PotosÃ­ City | 1        | 1.92%   |
| Saint Albans            | 1        | 1.92%   |
| Rio de Janeiro          | 1        | 1.92%   |
| Recife                  | 1        | 1.92%   |
| Prosper                 | 1        | 1.92%   |
| Oulu                    | 1        | 1.92%   |
| Oregon                  | 1        | 1.92%   |
| Odintsovo               | 1        | 1.92%   |
| Nordenham               | 1        | 1.92%   |
| Munich                  | 1        | 1.92%   |
| Melbourne               | 1        | 1.92%   |
| McDonough               | 1        | 1.92%   |
| Mansfield               | 1        | 1.92%   |
| Madrid                  | 1        | 1.92%   |
| Luxembourg              | 1        | 1.92%   |
| Lomonosov               | 1        | 1.92%   |
| Koleczkowo              | 1        | 1.92%   |
| Kazanâ€™           | 1        | 1.92%   |
| Heinsberg               | 1        | 1.92%   |
| Hamelin                 | 1        | 1.92%   |
| Halle                   | 1        | 1.92%   |
| Gelnhausen              | 1        | 1.92%   |
| GÃ¶dÃ¶llÅ‘       | 1        | 1.92%   |
| Gaildorf                | 1        | 1.92%   |
| Frankfurt am Main       | 1        | 1.92%   |
| Federal Way             | 1        | 1.92%   |
| East Longmeadow         | 1        | 1.92%   |
| Dornhan                 | 1        | 1.92%   |
| ChapecÃ³              | 1        | 1.92%   |
| CancÃºn               | 1        | 1.92%   |
| Čadca                  | 1        | 1.92%   |
| Brush                   | 1        | 1.92%   |
| Brisbane                | 1        | 1.92%   |
| Braunschweig            | 1        | 1.92%   |
| Antalya                 | 1        | 1.92%   |
| Andorra la Vella        | 1        | 1.92%   |
| Amsterdam               | 1        | 1.92%   |
| Almere Stad             | 1        | 1.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 26       | 42     | 24.07%  |
| Seagate             | 21       | 31     | 19.44%  |
| Samsung Electronics | 18       | 31     | 16.67%  |
| Kingston            | 7        | 8      | 6.48%   |
| Toshiba             | 6        | 6      | 5.56%   |
| Crucial             | 4        | 4      | 3.7%    |
| A-DATA Technology   | 4        | 4      | 3.7%    |
| SanDisk             | 3        | 4      | 2.78%   |
| Intel               | 3        | 3      | 2.78%   |
| Hitachi             | 3        | 5      | 2.78%   |
| Unknown             | 2        | 2      | 1.85%   |
| TO Exter            | 1        | 1      | 0.93%   |
| Phison              | 1        | 1      | 0.93%   |
| Micron Technology   | 1        | 2      | 0.93%   |
| Lite-On             | 1        | 1      | 0.93%   |
| JMicron             | 1        | 1      | 0.93%   |
| Inateck             | 1        | 1      | 0.93%   |
| HGST HTS            | 1        | 1      | 0.93%   |
| HGST                | 1        | 1      | 0.93%   |
| Fujitsu             | 1        | 1      | 0.93%   |
| Corsair             | 1        | 1      | 0.93%   |
| Apacer              | 1        | 2      | 0.93%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| WDC WDS500G1X0E-00AFY0 500GB         | 2        | 1.59%   |
| WDC WD5000AAKX-07U6AA0 500GB         | 2        | 1.59%   |
| Seagate ST3750528AS 752GB            | 2        | 1.59%   |
| Seagate ST3500418AS 500GB            | 2        | 1.59%   |
| Seagate ST3500413AS 500GB            | 2        | 1.59%   |
| Seagate ST2000DM008-2FR102 2TB       | 2        | 1.59%   |
| Seagate ST2000DM006-2DM164 2TB       | 2        | 1.59%   |
| Seagate ST2000DM001-9YN164 2TB       | 2        | 1.59%   |
| Seagate ST2000DM001-1ER164 2TB       | 2        | 1.59%   |
| Samsung SSD 980 PRO 1TB              | 2        | 1.59%   |
| Samsung SSD 870 QVO 1TB              | 2        | 1.59%   |
| Samsung SSD 860 EVO 250GB            | 2        | 1.59%   |
| Samsung SSD 850 EVO 500GB            | 2        | 1.59%   |
| Kingston SV300S37A120G 120GB SSD     | 2        | 1.59%   |
| Kingston SA400S37120G 120GB SSD      | 2        | 1.59%   |
| WDC WDS500G2B0A 500GB SSD            | 1        | 0.79%   |
| WDC WDS500G1B0B-00AS40 500GB SSD     | 1        | 0.79%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1        | 0.79%   |
| WDC WDS250G1B0C-00S6U0 250GB         | 1        | 0.79%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD     | 1        | 0.79%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1        | 0.79%   |
| WDC WDS200T2B0A-00SM50 2TB SSD       | 1        | 0.79%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1        | 0.79%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 1        | 0.79%   |
| WDC WD7500AALX-009BA0 752GB          | 1        | 0.79%   |
| WDC WD5000AAVS-00ZTB0 500GB          | 1        | 0.79%   |
| WDC WD5000AAKX-08U6AA0 500GB         | 1        | 0.79%   |
| WDC WD50 00LPCX-00VHAT0 500GB        | 1        | 0.79%   |
| WDC WD40EZAZ-00SF3B0 4TB             | 1        | 0.79%   |
| WDC WD3200AAKS-00B3A0 320GB          | 1        | 0.79%   |
| WDC WD3200AAJS-56M0A0 320GB          | 1        | 0.79%   |
| WDC WD2500BEVT-60ZCT1 250GB          | 1        | 0.79%   |
| WDC WD2500AAJS-00VTA0 250GB          | 1        | 0.79%   |
| WDC WD20EARX-00PASB0 2TB             | 1        | 0.79%   |
| WDC WD2005FBYZ-01YCBB2 2TB           | 1        | 0.79%   |
| WDC WD10EZEX-75WN4A0 1TB             | 1        | 0.79%   |
| WDC WD10EZEX-75M2NA0 1TB             | 1        | 0.79%   |
| WDC WD10EZEX-08WN4A0 1TB             | 1        | 0.79%   |
| WDC WD10EZEX-00KUWA0 1TB             | 1        | 0.79%   |
| WDC WD10EZEX-00BN5A0 1TB             | 1        | 0.79%   |
| WDC WD10EAVS-22D7B0 1TB              | 1        | 0.79%   |
| WDC WD10EACS-00D6B1 1TB              | 1        | 0.79%   |
| WDC WD1003FZEX-00K3CA0 1TB           | 1        | 0.79%   |
| WDC WD1001FALS-00E3A0 1TB            | 1        | 0.79%   |
| Unknown SD/MMC/MS PRO 32GB           | 1        | 0.79%   |
| Unknown 128GB SATA FLASH DRIVE       | 1        | 0.79%   |
| Toshiba TR200 240GB SSD              | 1        | 0.79%   |
| Toshiba TL100 240GB SSD              | 1        | 0.79%   |
| Toshiba NVMe SSD Drive 256GB         | 1        | 0.79%   |
| Toshiba HDWD130 3TB                  | 1        | 0.79%   |
| Toshiba HDWD110 1TB                  | 1        | 0.79%   |
| Toshiba DT01ACA200 2TB               | 1        | 0.79%   |
| TO Exter nal USB 3.0 1TB             | 1        | 0.79%   |
| Seagate ST500LM0 12 HN-M500MBB 500GB | 1        | 0.79%   |
| Seagate ST3750630AS 752GB            | 1        | 0.79%   |
| Seagate ST3320620AS 320GB            | 1        | 0.79%   |
| Seagate ST3250310AS 250GB            | 1        | 0.79%   |
| Seagate ST3160812AS 160GB            | 1        | 0.79%   |
| Seagate ST3000DM007-1WY10G 3TB       | 1        | 0.79%   |
| Seagate ST16000NM001G-2KK103 16TB    | 1        | 0.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 21       | 30     | 38.18%  |
| WDC                 | 19       | 31     | 34.55%  |
| Samsung Electronics | 5        | 10     | 9.09%   |
| Toshiba             | 3        | 3      | 5.45%   |
| Hitachi             | 3        | 5      | 5.45%   |
| Unknown             | 1        | 1      | 1.82%   |
| Inateck             | 1        | 1      | 1.82%   |
| HGST                | 1        | 1      | 1.82%   |
| Fujitsu             | 1        | 1      | 1.82%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 15     | 23.08%  |
| Kingston            | 7        | 8      | 17.95%  |
| WDC                 | 6        | 6      | 15.38%  |
| A-DATA Technology   | 4        | 4      | 10.26%  |
| SanDisk             | 3        | 4      | 7.69%   |
| Toshiba             | 2        | 2      | 5.13%   |
| Intel               | 2        | 2      | 5.13%   |
| Crucial             | 2        | 2      | 5.13%   |
| TO Exter            | 1        | 1      | 2.56%   |
| Micron Technology   | 1        | 2      | 2.56%   |
| JMicron             | 1        | 1      | 2.56%   |
| Apacer              | 1        | 2      | 2.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 40       | 83     | 45.45%  |
| SSD     | 33       | 49     | 37.5%   |
| NVMe    | 14       | 19     | 15.91%  |
| Unknown | 1        | 2      | 1.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 49       | 127    | 73.13%  |
| NVMe | 14       | 19     | 20.9%   |
| SAS  | 4        | 7      | 5.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 33       | 59     | 41.25%  |
| 0.51-1.0   | 27       | 44     | 33.75%  |
| 1.01-2.0   | 15       | 22     | 18.75%  |
| 2.01-3.0   | 2        | 2      | 2.5%    |
| 10.01-20.0 | 2        | 3      | 2.5%    |
| 3.01-4.0   | 1        | 2      | 1.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 14       | 26.42%  |
| 501-1000       | 9        | 16.98%  |
| 251-500        | 8        | 15.09%  |
| 1001-2000      | 8        | 15.09%  |
| 2001-3000      | 7        | 13.21%  |
| Unknown        | 3        | 5.66%   |
| 101-250        | 2        | 3.77%   |
| 1-20           | 2        | 3.77%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 12       | 22.22%  |
| 101-250        | 8        | 14.81%  |
| 501-1000       | 8        | 14.81%  |
| 1001-2000      | 7        | 12.96%  |
| 51-100         | 6        | 11.11%  |
| 1-20           | 5        | 9.26%   |
| Unknown        | 3        | 5.56%   |
| More than 3000 | 2        | 3.7%    |
| 2001-3000      | 2        | 3.7%    |
| 21-50          | 1        | 1.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| WDC WD3200AAJS-56M0A0 320GB      | 1        | 1      | 16.67%  |
| WDC WD2500BEVT-60ZCT1 250GB      | 1        | 1      | 16.67%  |
| Seagate ST3320620AS 320GB        | 1        | 1      | 16.67%  |
| Seagate ST1000DM003-1CH162 1TB   | 1        | 1      | 16.67%  |
| Kingston SV300S37A120G 120GB SSD | 1        | 1      | 16.67%  |
| Crucial CT1000P1SSD8 1TB         | 1        | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| WDC      | 2        | 2      | 33.33%  |
| Seagate  | 2        | 2      | 33.33%  |
| Kingston | 1        | 1      | 16.67%  |
| Crucial  | 1        | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 2      | 50%     |
| Seagate | 2        | 2      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 4      | 60%     |
| NVMe | 1        | 1      | 20%     |
| SSD  | 1        | 1      | 20%     |

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
| Works    | 28       | 76     | 48.28%  |
| Detected | 25       | 71     | 43.1%   |
| Malfunc  | 5        | 6      | 8.62%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 28       | 35.44%  |
| AMD                          | 23       | 29.11%  |
| Samsung Electronics          | 6        | 7.59%   |
| Sandisk                      | 5        | 6.33%   |
| Marvell Technology Group     | 3        | 3.8%    |
| ASMedia Technology           | 3        | 3.8%    |
| Phison Electronics           | 2        | 2.53%   |
| Micron/Crucial Technology    | 2        | 2.53%   |
| Toshiba America Info Systems | 1        | 1.27%   |
| Silicon Image                | 1        | 1.27%   |
| Seagate Technology           | 1        | 1.27%   |
| Nvidia                       | 1        | 1.27%   |
| Lite-On Technology           | 1        | 1.27%   |
| JMicron Technology           | 1        | 1.27%   |
| Broadcom / LSI               | 1        | 1.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 17       | 17.17%  |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 5.05%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                              | 3        | 3.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 3.03%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 3.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 3.03%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 3.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 3.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 2.02%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 2.02%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 2.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 2.02%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 2.02%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 2.02%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 2.02%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 2.02%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 1        | 1.01%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1        | 1.01%   |
| Seagate FireCuda 520 SSD                                                                | 1        | 1.01%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1        | 1.01%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 1.01%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 1.01%   |
| Samsung Electronics SATA controller                                                     | 1        | 1.01%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.01%   |
| Phison E12 NVMe Controller                                                              | 1        | 1.01%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 1.01%   |
| Nvidia MCP61 IDE                                                                        | 1        | 1.01%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 1.01%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 1.01%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                                 | 1        | 1.01%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1        | 1.01%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1        | 1.01%   |
| Lite-On Non-Volatile memory controller                                                  | 1        | 1.01%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 1.01%   |
| Intel SSD 660P Series                                                                   | 1        | 1.01%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 1.01%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                              | 1        | 1.01%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 1.01%   |
| Intel C610/X99 series chipset IDE-r Controller                                          | 1        | 1.01%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 1.01%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 1.01%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 1.01%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 1.01%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 1.01%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 1.01%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 1.01%   |
| Intel 82801GR/GDH (ICH7R/ICH7DH) SATA Controller [RAID mode]                            | 1        | 1.01%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1        | 1.01%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1        | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 1.01%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.01%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 1.01%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.01%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1        | 1.01%   |
| AMD FCH SATA Controller [RAID mode]                                                     | 1        | 1.01%   |
| AMD FCH SATA Controller D                                                               | 1        | 1.01%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 1.01%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 41       | 56.16%  |
| NVMe | 14       | 19.18%  |
| IDE  | 12       | 16.44%  |
| RAID | 5        | 6.85%   |
| SAS  | 1        | 1.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 27       | 52.94%  |
| AMD    | 24       | 47.06%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 9 5900X 12-Core Processor            | 3        | 5.88%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 2        | 3.92%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 2        | 3.92%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 2        | 3.92%   |
| AMD Ryzen 7 1700 Eight-Core Processor          | 2        | 3.92%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz           | 1        | 1.96%   |
| Intel Xeon CPU E5-2667 v3 @ 3.20GHz            | 1        | 1.96%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz            | 1        | 1.96%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz    | 1        | 1.96%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz         | 1        | 1.96%   |
| Intel Pentium CPU G3258 @ 3.20GHz              | 1        | 1.96%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 1.96%   |
| Intel Core i7-6700 CPU @ 3.40GHz               | 1        | 1.96%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 1.96%   |
| Intel Core i7 CPU 860 @ 2.80GHz                | 1        | 1.96%   |
| Intel Core i5-7600K CPU @ 3.80GHz              | 1        | 1.96%   |
| Intel Core i5-7500 CPU @ 3.40GHz               | 1        | 1.96%   |
| Intel Core i5-6400 CPU @ 2.70GHz               | 1        | 1.96%   |
| Intel Core i5-4590 CPU @ 3.30GHz               | 1        | 1.96%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 1.96%   |
| Intel Core i5-4440 CPU @ 3.10GHz               | 1        | 1.96%   |
| Intel Core i5-2400S CPU @ 2.50GHz              | 1        | 1.96%   |
| Intel Core i5-2320 CPU @ 3.00GHz               | 1        | 1.96%   |
| Intel Core i5-10400 CPU @ 2.90GHz              | 1        | 1.96%   |
| Intel Core i3-8100 CPU @ 3.60GHz               | 1        | 1.96%   |
| Intel Core i3-2100 CPU @ 3.10GHz               | 1        | 1.96%   |
| Intel Core 2 Quad CPU Q9300 @ 2.50GHz          | 1        | 1.96%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz           | 1        | 1.96%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz           | 1        | 1.96%   |
| Intel Core 2 CPU 6400 @ 2.13GHz                | 1        | 1.96%   |
| AMD Sempron 2650 APU with Radeon R3            | 1        | 1.96%   |
| AMD Ryzen 9 3950X 16-Core Processor            | 1        | 1.96%   |
| AMD Ryzen 7 3800X 8-Core Processor             | 1        | 1.96%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1        | 1.96%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics    | 1        | 1.96%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 1        | 1.96%   |
| AMD Ryzen 5 1600X Six-Core Processor           | 1        | 1.96%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 1        | 1.96%   |
| AMD Phenom II X4 B50 Processor                 | 1        | 1.96%   |
| AMD Phenom II X4 955 Processor                 | 1        | 1.96%   |
| AMD FX-8350 Eight-Core Processor               | 1        | 1.96%   |
| AMD FX-6300 Six-Core Processor                 | 1        | 1.96%   |
| AMD Athlon 3000G with Radeon Vega Graphics     | 1        | 1.96%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics    | 1        | 1.96%   |
| AMD A10-7800 Radeon R7, 12 Compute Cores 4C+8G | 1        | 1.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 11       | 21.57%  |
| AMD Ryzen 9             | 6        | 11.76%  |
| AMD Ryzen 7             | 6        | 11.76%  |
| Intel Core i7           | 4        | 7.84%   |
| AMD Ryzen 5             | 4        | 7.84%   |
| Intel Xeon              | 3        | 5.88%   |
| Intel Core i3           | 2        | 3.92%   |
| Intel Core 2 Duo        | 2        | 3.92%   |
| AMD Phenom II X4        | 2        | 3.92%   |
| AMD FX                  | 2        | 3.92%   |
| Intel Pentium Dual-Core | 1        | 1.96%   |
| Intel Pentium Dual      | 1        | 1.96%   |
| Intel Pentium           | 1        | 1.96%   |
| Intel Core 2 Quad       | 1        | 1.96%   |
| Intel Core 2            | 1        | 1.96%   |
| AMD Sempron             | 1        | 1.96%   |
| AMD Athlon              | 1        | 1.96%   |
| AMD A8                  | 1        | 1.96%   |
| AMD A10                 | 1        | 1.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 21       | 41.18%  |
| 2      | 10       | 19.61%  |
| 8      | 7        | 13.73%  |
| 6      | 5        | 9.8%    |
| 16     | 4        | 7.84%   |
| 12     | 3        | 5.88%   |
| 3      | 1        | 1.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 50       | 98.04%  |
| 2      | 1        | 1.96%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 29       | 56.86%  |
| 1      | 22       | 43.14%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 51       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 22       | 40.74%  |
| 0x306c3    | 4        | 7.41%   |
| 0x206a7    | 3        | 5.56%   |
| 0x906e9    | 2        | 3.7%    |
| 0x306a9    | 2        | 3.7%    |
| 0x0a201016 | 2        | 3.7%    |
| 0x0a201009 | 2        | 3.7%    |
| 0x08701021 | 2        | 3.7%    |
| 0x08001137 | 2        | 3.7%    |
| 0xa0653    | 1        | 1.85%   |
| 0x6fd      | 1        | 1.85%   |
| 0x306f2    | 1        | 1.85%   |
| 0x1067a    | 1        | 1.85%   |
| 0x10677    | 1        | 1.85%   |
| 0x0a201204 | 1        | 1.85%   |
| 0x08108109 | 1        | 1.85%   |
| 0x08108102 | 1        | 1.85%   |
| 0x0800820d | 1        | 1.85%   |
| 0x07030105 | 1        | 1.85%   |
| 0x06000852 | 1        | 1.85%   |
| 0x010000db | 1        | 1.85%   |
| 0x010000c8 | 1        | 1.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 7        | 13.73%  |
| Zen 3       | 5        | 9.8%    |
| Zen+        | 4        | 7.84%   |
| Zen 2       | 4        | 7.84%   |
| Zen         | 4        | 7.84%   |
| KabyLake    | 4        | 7.84%   |
| SandyBridge | 3        | 5.88%   |
| Penryn      | 3        | 5.88%   |
| IvyBridge   | 3        | 5.88%   |
| Core        | 3        | 5.88%   |
| Skylake     | 2        | 3.92%   |
| Piledriver  | 2        | 3.92%   |
| K10         | 2        | 3.92%   |
| Steamroller | 1        | 1.96%   |
| Puma        | 1        | 1.96%   |
| Nehalem     | 1        | 1.96%   |
| Jaguar      | 1        | 1.96%   |
| CometLake   | 1        | 1.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Nvidia      | 26       | 48.15%  |
| AMD         | 14       | 25.93%  |
| Intel       | 13       | 24.07%  |
| S3 Graphics | 1        | 1.85%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 3.64%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 3.64%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 2        | 3.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 3.64%   |
| Intel HD Graphics 630                                                       | 2        | 3.64%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 3.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 3.64%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 2        | 3.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 3.64%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 3.64%   |
| S3 Graphics 86c764/765 [Trio32/64/64V+]                                     | 1        | 1.82%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.82%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 1.82%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 1.82%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.82%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.82%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.82%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.82%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.82%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 1.82%   |
| Nvidia GM107GL [Quadro K2200]                                               | 1        | 1.82%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.82%   |
| Nvidia GK110GL [Quadro K5200]                                               | 1        | 1.82%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.82%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 1.82%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.82%   |
| Nvidia GA106 [GeForce RTX 3060]                                             | 1        | 1.82%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.82%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 1        | 1.82%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 1        | 1.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.82%   |
| Intel HD Graphics 530                                                       | 1        | 1.82%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.82%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.82%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 1.82%   |
| AMD RV610 [Radeon HD 2400 PRO]                                              | 1        | 1.82%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 1        | 1.82%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 1        | 1.82%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 1        | 1.82%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                         | 1        | 1.82%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 1.82%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 1        | 1.82%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                     | 1        | 1.82%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 1        | 1.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 25       | 49.02%  |
| 1 x AMD         | 13       | 25.49%  |
| 1 x Intel       | 10       | 19.61%  |
| 2 x AMD         | 1        | 1.96%   |
| 1 x S3 Graphics | 1        | 1.96%   |
| Intel + Nvidia  | 1        | 1.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 32       | 62.75%  |
| Proprietary | 16       | 31.37%  |
| Unknown     | 3        | 5.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 28       | 52.83%  |
| 1.01-2.0   | 7        | 13.21%  |
| 7.01-8.0   | 4        | 7.55%   |
| 3.01-4.0   | 3        | 5.66%   |
| 8.01-16.0  | 3        | 5.66%   |
| 5.01-6.0   | 2        | 3.77%   |
| 16.01-24.0 | 2        | 3.77%   |
| 0.51-1.0   | 2        | 3.77%   |
| 0.01-0.5   | 2        | 3.77%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 9        | 15.79%  |
| Dell                 | 9        | 15.79%  |
| Samsung Electronics  | 7        | 12.28%  |
| BenQ                 | 5        | 8.77%   |
| Ancor Communications | 5        | 8.77%   |
| Philips              | 4        | 7.02%   |
| Acer                 | 3        | 5.26%   |
| LG Electronics       | 2        | 3.51%   |
| Hewlett-Packard      | 2        | 3.51%   |
| AOC                  | 2        | 3.51%   |
| Vizio                | 1        | 1.75%   |
| ViewSonic            | 1        | 1.75%   |
| TCL                  | 1        | 1.75%   |
| Lenovo               | 1        | 1.75%   |
| Iiyama               | 1        | 1.75%   |
| Hitachi              | 1        | 1.75%   |
| Fujitsu Siemens      | 1        | 1.75%   |
| Denver               | 1        | 1.75%   |
| ASUSTek Computer     | 1        | 1.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Vizio E60-E3 VIZ1018 3840x2160 1330x748mm 60.1-inch                   | 1        | 1.67%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch             | 1        | 1.67%   |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                      | 1        | 1.67%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1        | 1.67%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 480x270mm 21.7-inch  | 1        | 1.67%   |
| Samsung Electronics SyncMaster SAM00A2 1024x768 304x228mm 15.0-inch   | 1        | 1.67%   |
| Samsung Electronics SMS27A850T SAM0887 2560x1440 518x324mm 24.1-inch  | 1        | 1.67%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 1        | 1.67%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 800x330mm 34.1-inch     | 1        | 1.67%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 800x330mm 34.1-inch     | 1        | 1.67%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch     | 1        | 1.67%   |
| Philips PHL 258B6QU PHL08F5 2560x1440 553x311mm 25.0-inch             | 1        | 1.67%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1        | 1.67%   |
| Philips 150S PHL0812 1024x768 307x230mm 15.1-inch                     | 1        | 1.67%   |
| Philips 150S PHL0805 1024x768 307x230mm 15.1-inch                     | 1        | 1.67%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 1        | 1.67%   |
| LG Electronics LCD Monitor LG TV SSCR 3840x2160                       | 1        | 1.67%   |
| Lenovo LEN T27i-10 LEN61C6 1920x1080 598x336mm 27.0-inch              | 1        | 1.67%   |
| Iiyama PL2592H IVM6135 1920x1080 544x303mm 24.5-inch                  | 1        | 1.67%   |
| Hitachi X90W D-sub HIT6008 1440x900 410x257mm 19.1-inch               | 1        | 1.67%   |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch          | 1        | 1.67%   |
| Hewlett-Packard 27es HWP3326 1920x1080 598x336mm 27.0-inch            | 1        | 1.67%   |
| Goldstar W2261 GSM56CF 1920x1080 477x268mm 21.5-inch                  | 1        | 1.67%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 1        | 1.67%   |
| Goldstar MP59G GSM5B35 1920x1080 600x340mm 27.2-inch                  | 1        | 1.67%   |
| Goldstar L1718S GSM443C 1280x1024 338x270mm 17.0-inch                 | 1        | 1.67%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1        | 1.67%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 1        | 1.67%   |
| Goldstar E2742 GSM58C9 1920x1080 600x340mm 27.2-inch                  | 1        | 1.67%   |
| Goldstar E2441 GSM581F 1920x1080 530x300mm 24.0-inch                  | 1        | 1.67%   |
| Goldstar BN550Y GSM5BAB 1920x1080 600x340mm 27.2-inch                 | 1        | 1.67%   |
| Fujitsu Siemens B19-5 ECO FUS07C0 1280x1024 376x301mm 19.0-inch       | 1        | 1.67%   |
| Denver UWQHD-100-V2 LHC3500 3440x1440 798x342mm 34.2-inch             | 1        | 1.67%   |
| Dell UZ2315H DELF055 1920x1080 509x286mm 23.0-inch                    | 1        | 1.67%   |
| Dell U2711 DELA057 2560x1440 597x336mm 27.0-inch                      | 1        | 1.67%   |
| Dell U2410 DELF014 1920x1200 518x324mm 24.1-inch                      | 1        | 1.67%   |
| Dell S3422DWG DELD12D 3440x1440 797x334mm 34.0-inch                   | 1        | 1.67%   |
| Dell S3422DWG DELD128 3440x1440 797x334mm 34.0-inch                   | 1        | 1.67%   |
| Dell S2216H DELD07A 1920x1080 476x268mm 21.5-inch                     | 1        | 1.67%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 1        | 1.67%   |
| Dell P2219H DELA114 1920x1080 476x267mm 21.5-inch                     | 1        | 1.67%   |
| Dell E228WFP DELD014 1680x1050 473x296mm 22.0-inch                    | 1        | 1.67%   |
| Dell 1703FP DEL3011 1280x1024 338x270mm 17.0-inch                     | 1        | 1.67%   |
| BenQ T221WA BNQ7719 1680x1050 473x296mm 22.0-inch                     | 1        | 1.67%   |
| BenQ SW2700 BNQ7F47 2560x1440 596x335mm 26.9-inch                     | 1        | 1.67%   |
| BenQ PD2500Q BNQ802A 2560x1440 553x311mm 25.0-inch                    | 1        | 1.67%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 1        | 1.67%   |
| BenQ BL2405 BNQ8016 1920x1080 531x298mm 24.0-inch                     | 1        | 1.67%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch          | 1        | 1.67%   |
| AOC LCD Monitor 28E850 640x480                                        | 1        | 1.67%   |
| AOC 2436 AOC2436 1920x1080 521x293mm 23.5-inch                        | 1        | 1.67%   |
| Ancor Communications PA248 ACI24B1 1920x1200 546x352mm 25.6-inch      | 1        | 1.67%   |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 408x255mm 18.9-inch  | 1        | 1.67%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 480x270mm 21.7-inch | 1        | 1.67%   |
| Ancor Communications ASUS VN248 ACI24C4 1920x1080 530x300mm 24.0-inch | 1        | 1.67%   |
| Ancor Communications ASUS VN247 ACI24C3 1920x1080 521x293mm 23.5-inch | 1        | 1.67%   |
| Acer X163W ACR0015 1366x768 344x193mm 15.5-inch                       | 1        | 1.67%   |
| Acer V203H ACR0102 1600x900 443x249mm 20.0-inch                       | 1        | 1.67%   |
| Acer V203H ACR00C7 1600x900 443x249mm 20.0-inch                       | 1        | 1.67%   |
| Acer GD245HQ ACR0125 1920x1080 520x290mm 23.4-inch                    | 1        | 1.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 23       | 44.23%  |
| 2560x1440 (QHD)    | 5        | 9.62%   |
| 3840x2160 (4K)     | 4        | 7.69%   |
| 3440x1440          | 3        | 5.77%   |
| 1280x1024 (SXGA)   | 3        | 5.77%   |
| 1024x768 (XGA)     | 3        | 5.77%   |
| 2560x1080          | 2        | 3.85%   |
| 1920x1200 (WUXGA)  | 2        | 3.85%   |
| 1680x1050 (WSXGA+) | 2        | 3.85%   |
| 1440x900 (WXGA+)   | 2        | 3.85%   |
| 640x480            | 1        | 1.92%   |
| 1600x900 (HD+)     | 1        | 1.92%   |
| 1366x768 (WXGA)    | 1        | 1.92%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 8        | 15.38%  |
| 21      | 8        | 15.38%  |
| 24      | 7        | 13.46%  |
| 23      | 5        | 9.62%   |
| 34      | 4        | 7.69%   |
| 15      | 4        | 7.69%   |
| Unknown | 3        | 5.77%   |
| 25      | 2        | 3.85%   |
| 22      | 2        | 3.85%   |
| 19      | 2        | 3.85%   |
| 17      | 2        | 3.85%   |
| 74      | 1        | 1.92%   |
| 32      | 1        | 1.92%   |
| 31      | 1        | 1.92%   |
| 20      | 1        | 1.92%   |
| 18      | 1        | 1.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 20       | 38.46%  |
| 401-500     | 14       | 26.92%  |
| 301-350     | 6        | 11.54%  |
| 701-800     | 5        | 9.62%   |
| Unknown     | 3        | 5.77%   |
| 601-700     | 2        | 3.85%   |
| 351-400     | 1        | 1.92%   |
| 1501-2000   | 1        | 1.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 31       | 60.78%  |
| 16/10   | 7        | 13.73%  |
| 21/9    | 4        | 7.84%   |
| 5/4     | 3        | 5.88%   |
| 4/3     | 3        | 5.88%   |
| Unknown | 3        | 5.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 19       | 35.85%  |
| 301-350        | 8        | 15.09%  |
| 351-500        | 6        | 11.32%  |
| 251-300        | 5        | 9.43%   |
| 151-200        | 4        | 7.55%   |
| 101-110        | 4        | 7.55%   |
| 141-150        | 3        | 5.66%   |
| Unknown        | 3        | 5.66%   |
| More than 1000 | 1        | 1.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 30       | 60%     |
| 101-120 | 15       | 30%     |
| Unknown | 3        | 6%      |
| 121-160 | 2        | 4%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 39       | 76.47%  |
| 2     | 8        | 15.69%  |
| 0     | 3        | 5.88%   |
| 3     | 1        | 1.96%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 37       | 48.05%  |
| Intel                 | 20       | 25.97%  |
| Qualcomm Atheros      | 5        | 6.49%   |
| Ralink                | 3        | 3.9%    |
| Broadcom              | 2        | 2.6%    |
| ZyXEL Communications  | 1        | 1.3%    |
| TP-Link               | 1        | 1.3%    |
| TOMTOM                | 1        | 1.3%    |
| Samsung Electronics   | 1        | 1.3%    |
| Ralink Technology     | 1        | 1.3%    |
| NetXen Incorporated   | 1        | 1.3%    |
| D-Link System         | 1        | 1.3%    |
| Broadcom Limited      | 1        | 1.3%    |
| AVM                   | 1        | 1.3%    |
| ASIX Electronics      | 1        | 1.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 28       | 30.43%  |
| Intel Wi-Fi 6 AX200                                                        | 5        | 5.43%   |
| Intel I211 Gigabit Network Connection                                      | 5        | 5.43%   |
| Realtek RTL8125 2.5GbE Controller                                          | 4        | 4.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 3        | 3.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 2        | 2.17%   |
| Intel Wireless-AC 9260                                                     | 2        | 2.17%   |
| Intel Wireless 7260                                                        | 2        | 2.17%   |
| Intel Ethernet Connection (2) I218-LM                                      | 2        | 2.17%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]               | 1        | 1.09%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                        | 1        | 1.09%   |
| TOMTOM GO 60                                                               | 1        | 1.09%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 1.09%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 1        | 1.09%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 1        | 1.09%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 1        | 1.09%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1        | 1.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1        | 1.09%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1        | 1.09%   |
| Realtek Killer E3000 2.5GbE Controller                                     | 1        | 1.09%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                           | 1        | 1.09%   |
| Realtek 802.11n                                                            | 1        | 1.09%   |
| Ralink RT3072 Wireless Adapter                                             | 1        | 1.09%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1        | 1.09%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                       | 1        | 1.09%   |
| Ralink RT2561/RT61 802.11g PCI                                             | 1        | 1.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 1        | 1.09%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 1        | 1.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 1        | 1.09%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                  | 1        | 1.09%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1        | 1.09%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 1.09%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter       | 1        | 1.09%   |
| Intel Wireless 8260                                                        | 1        | 1.09%   |
| Intel Tiger Lake PCH CNVi WiFi                                             | 1        | 1.09%   |
| Intel I210 Gigabit Network Connection                                      | 1        | 1.09%   |
| Intel Ethernet Connection (2) I219-LM                                      | 1        | 1.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 1        | 1.09%   |
| Intel 82579V Gigabit Network Connection                                    | 1        | 1.09%   |
| Intel 82574L Gigabit Network Connection                                    | 1        | 1.09%   |
| Intel 82562V-2 10/100 Network Connection                                   | 1        | 1.09%   |
| Intel 82541PI Gigabit Ethernet Controller                                  | 1        | 1.09%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 1        | 1.09%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                            | 1        | 1.09%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                 | 1        | 1.09%   |
| Broadcom BCM43142 802.11b/g/n                                              | 1        | 1.09%   |
| AVM Fritz!WLAN N v2 [Atheros AR9271]                                       | 1        | 1.09%   |
| ASIX AX88179 Gigabit Ethernet                                              | 1        | 1.09%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 12       | 38.71%  |
| Realtek Semiconductor | 6        | 19.35%  |
| Ralink                | 3        | 9.68%   |
| Qualcomm Atheros      | 3        | 9.68%   |
| ZyXEL Communications  | 1        | 3.23%   |
| TP-Link               | 1        | 3.23%   |
| Ralink Technology     | 1        | 3.23%   |
| D-Link System         | 1        | 3.23%   |
| Broadcom Limited      | 1        | 3.23%   |
| Broadcom              | 1        | 3.23%   |
| AVM                   | 1        | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 5        | 16.13%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 2        | 6.45%   |
| Intel Wireless-AC 9260                                                     | 2        | 6.45%   |
| Intel Wireless 7260                                                        | 2        | 6.45%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]               | 1        | 3.23%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                        | 1        | 3.23%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 1        | 3.23%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 1        | 3.23%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 1        | 3.23%   |
| Realtek 802.11n                                                            | 1        | 3.23%   |
| Ralink RT3072 Wireless Adapter                                             | 1        | 3.23%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1        | 3.23%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                       | 1        | 3.23%   |
| Ralink RT2561/RT61 802.11g PCI                                             | 1        | 3.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 1        | 3.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 1        | 3.23%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1        | 3.23%   |
| Intel Wireless 8260                                                        | 1        | 3.23%   |
| Intel Tiger Lake PCH CNVi WiFi                                             | 1        | 3.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 1        | 3.23%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 1        | 3.23%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                 | 1        | 3.23%   |
| Broadcom BCM43142 802.11b/g/n                                              | 1        | 3.23%   |
| AVM Fritz!WLAN N v2 [Atheros AR9271]                                       | 1        | 3.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 37       | 66.07%  |
| Intel                 | 12       | 21.43%  |
| Qualcomm Atheros      | 3        | 5.36%   |
| Samsung Electronics   | 1        | 1.79%   |
| NetXen Incorporated   | 1        | 1.79%   |
| Broadcom              | 1        | 1.79%   |
| ASIX Electronics      | 1        | 1.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 28       | 46.67%  |
| Intel I211 Gigabit Network Connection                                | 5        | 8.33%   |
| Realtek RTL8125 2.5GbE Controller                                    | 4        | 6.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 3        | 5%      |
| Intel Ethernet Connection (2) I218-LM                                | 2        | 3.33%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 1        | 1.67%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                      | 1        | 1.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 1        | 1.67%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                           | 1        | 1.67%   |
| Realtek Killer E3000 2.5GbE Controller                               | 1        | 1.67%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 1        | 1.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                            | 1        | 1.67%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 1        | 1.67%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 1        | 1.67%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter | 1        | 1.67%   |
| Intel I210 Gigabit Network Connection                                | 1        | 1.67%   |
| Intel Ethernet Connection (2) I219-LM                                | 1        | 1.67%   |
| Intel 82579V Gigabit Network Connection                              | 1        | 1.67%   |
| Intel 82574L Gigabit Network Connection                              | 1        | 1.67%   |
| Intel 82562V-2 10/100 Network Connection                             | 1        | 1.67%   |
| Intel 82541PI Gigabit Ethernet Controller                            | 1        | 1.67%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                      | 1        | 1.67%   |
| ASIX AX88179 Gigabit Ethernet                                        | 1        | 1.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 50       | 61.73%  |
| WiFi     | 30       | 37.04%  |
| Unknown  | 1        | 1.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 45       | 65.22%  |
| WiFi     | 23       | 33.33%  |
| Unknown  | 1        | 1.45%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 24       | 47.06%  |
| 2     | 22       | 43.14%  |
| 3     | 4        | 7.84%   |
| 5     | 1        | 1.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 41       | 78.85%  |
| Yes  | 11       | 21.15%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 10       | 40%     |
| Cambridge Silicon Radio         | 7        | 28%     |
| Realtek Semiconductor           | 2        | 8%      |
| Qualcomm Atheros Communications | 2        | 8%      |
| Dell                            | 1        | 4%      |
| Broadcom                        | 1        | 4%      |
| Belkin Components               | 1        | 4%      |
| ASUSTek Computer                | 1        | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 7        | 28%     |
| Intel AX200 Bluetooth                                 | 4        | 16%     |
| Realtek  Bluetooth 4.2 Adapter                        | 2        | 8%      |
| Intel Bluetooth wireless interface                    | 2        | 8%      |
| Intel Bluetooth Device                                | 2        | 8%      |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 4%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1        | 4%      |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 4%      |
| Intel AX201 Bluetooth                                 | 1        | 4%      |
| Dell Broadcom BCM20702A0 Bluetooth                    | 1        | 4%      |
| Broadcom BCM43142A0 Bluetooth Device                  | 1        | 4%      |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 1        | 4%      |
| ASUS Bluetooth Adapter                                | 1        | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| AMD                       | 29       | 32.58%  |
| Nvidia                    | 26       | 29.21%  |
| Intel                     | 25       | 28.09%  |
| C-Media Electronics       | 3        | 3.37%   |
| Creative Labs             | 2        | 2.25%   |
| Texas Instruments         | 1        | 1.12%   |
| Sennheiser Communications | 1        | 1.12%   |
| BEHRINGER International   | 1        | 1.12%   |
| ASUSTek Computer          | 1        | 1.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 9        | 9%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6        | 6%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4        | 4%      |
| Nvidia GA102 High Definition Audio Controller                              | 3        | 3%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 3%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 3%      |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 3%      |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 3%      |
| AMD FCH Azalia Controller                                                  | 3        | 3%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 2%      |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 2%      |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 2%      |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 2%      |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 2%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 2%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 2%      |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 2        | 2%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 2%      |
| AMD Kabini HDMI/DP Audio                                                   | 2        | 2%      |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 2%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 2%      |
| Texas Instruments PCM2900C Audio CODEC                                     | 1        | 1%      |
| Sennheiser Communications Sennheiser 3D G4ME1                              | 1        | 1%      |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 1%      |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 1%      |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1%      |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 1%      |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1%      |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1%      |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 1%      |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 1%      |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 1%      |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1%      |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 1%      |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 1%      |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 1%      |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 1%      |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 1%      |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 1%      |
| Nvidia Audio device                                                        | 1        | 1%      |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 1%      |
| Intel Audio device                                                         | 1        | 1%      |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 1%      |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 1%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 1%      |
| Intel 200 Series PCH HD Audio                                              | 1        | 1%      |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 1        | 1%      |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                 | 1        | 1%      |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 1        | 1%      |
| C-Media Electronics CM108 Audio Controller                                 | 1        | 1%      |
| C-Media Electronics Audio Adapter                                          | 1        | 1%      |
| BEHRINGER International UMC202HD 192k                                      | 1        | 1%      |
| ASUSTek Computer Xonar U7 MKII                                             | 1        | 1%      |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]          | 1        | 1%      |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1        | 1%      |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1        | 1%      |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 1%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 9        | 25.71%  |
| Corsair             | 5        | 14.29%  |
| Unknown             | 4        | 11.43%  |
| G.Skill             | 4        | 11.43%  |
| Crucial             | 4        | 11.43%  |
| Samsung Electronics | 3        | 8.57%   |
| Team                | 1        | 2.86%   |
| Patriot             | 1        | 2.86%   |
| Micron Technology   | 1        | 2.86%   |
| GeIL                | 1        | 2.86%   |
| Elpida              | 1        | 2.86%   |
| AMD                 | 1        | 2.86%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Kingston RAM KHX3600C18D4/32GX 32GB DIMM DDR4 3600MT/s      | 2        | 5.13%   |
| Kingston RAM KHX3200C16D4/16GX 16384MB DIMM DDR4 3600MT/s   | 2        | 5.13%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                   | 1        | 2.56%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                | 1        | 2.56%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                     | 1        | 2.56%   |
| Unknown RAM 992124 (997124) 8GB DIMM DDR3 1600MT/s          | 1        | 2.56%   |
| Team RAM TEAMGROUP-UD4-2400 8192MB DIMM DDR4 3007MT/s       | 1        | 2.56%   |
| Samsung RAM M471B5673FH0-CH9 2GB DIMM DDR3 4199MT/s         | 1        | 2.56%   |
| Samsung RAM M393A2G40DB0-CPB 16384MB DIMM DDR4 2133MT/s     | 1        | 2.56%   |
| Samsung RAM M393A1G40DB0-CPB 8192MB DIMM DDR4 2133MT/s      | 1        | 2.56%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s         | 1        | 2.56%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s             | 1        | 2.56%   |
| Micron RAM 16JTF1G64AZ-1G6D1 8GB DIMM DDR3 1600MT/s         | 1        | 2.56%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s           | 1        | 2.56%   |
| Kingston RAM KHX1866C10D3/8G 8192MB DIMM DDR3 1867MT/s      | 1        | 2.56%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s         | 1        | 2.56%   |
| Kingston RAM 99U5474-016.A00LF 4GB DIMM DDR3 1333MT/s       | 1        | 2.56%   |
| Kingston RAM 99U5471-040.A00LF 8GB DIMM DDR3 1333MT/s       | 1        | 2.56%   |
| Kingston RAM 9905474-012.A00LF 2048MB DIMM DDR3 1333MT/s    | 1        | 2.56%   |
| Kingston RAM 9905471-028.A00LF 4096MB DIMM DDR3 1333MT/s    | 1        | 2.56%   |
| GeIL RAM CL11-11-11 D3-1600 4096MB DIMM DDR3 1600MT/s       | 1        | 2.56%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s         | 1        | 2.56%   |
| G.Skill RAM F4-3200C15-16GTZKY 16384MB DIMM DDR4 3200MT/s   | 1        | 2.56%   |
| G.Skill RAM F4-2666C19-16GIS 16384MB DIMM DDR4 2667MT/s     | 1        | 2.56%   |
| G.Skill RAM F4-2400C15-8GNT 8GB DIMM DDR4 2666MT/s          | 1        | 2.56%   |
| Elpida RAM EBE11UD8AJWA-6E-E 1024MB DIMM DDR2 667MT/s       | 1        | 2.56%   |
| Crucial RAM CT16G4DFRA266.C16FE 16384MB DIMM DDR4 2667MT/s  | 1        | 2.56%   |
| Crucial RAM CT102464BD160B.M16 8GB DIMM DDR3 1600MT/s       | 1        | 2.56%   |
| Crucial RAM BLS16G4D32AESB.M16FE 16384MB DIMM DDR4 3400MT/s | 1        | 2.56%   |
| Crucial RAM BL32G32C16U4R.M16FB1 32GB DIMM DDR4 3200MT/s    | 1        | 2.56%   |
| Corsair RAM CMZ8GX3M2A1866C9 4096MB DIMM DDR3 1867MT/s      | 1        | 2.56%   |
| Corsair RAM CMT64GX4M4E3200C16 16384MB DIMM DDR4 3200MT/s   | 1        | 2.56%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1867MT/s         | 1        | 2.56%   |
| Corsair RAM CMK32GX4M2Z3600C18 16384MB DIMM DDR4 3800MT/s   | 1        | 2.56%   |
| Corsair RAM CMK16GX4M1E3200C16 16384MB DIMM DDR4 3000MT/s   | 1        | 2.56%   |
| AMD RAM R538G1601U2S-U 8192MB DIMM DDR3 1600MT/s            | 1        | 2.56%   |
| AMD RAM R538G1601U2S 8GB DIMM DDR3 1600MT/s                 | 1        | 2.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 17       | 56.67%  |
| DDR3    | 10       | 33.33%  |
| SDRAM   | 1        | 3.33%   |
| DDR2    | 1        | 3.33%   |
| Unknown | 1        | 3.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 30       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 12       | 35.29%  |
| 16384 | 11       | 32.35%  |
| 4096  | 4        | 11.76%  |
| 32768 | 3        | 8.82%   |
| 2048  | 3        | 8.82%   |
| 1024  | 1        | 2.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 5        | 14.71%  |
| 3600  | 4        | 11.76%  |
| 1333  | 4        | 11.76%  |
| 3200  | 3        | 8.82%   |
| 2667  | 2        | 5.88%   |
| 2133  | 2        | 5.88%   |
| 1867  | 2        | 5.88%   |
| 4199  | 1        | 2.94%   |
| 3800  | 1        | 2.94%   |
| 3466  | 1        | 2.94%   |
| 3400  | 1        | 2.94%   |
| 3007  | 1        | 2.94%   |
| 3000  | 1        | 2.94%   |
| 2934  | 1        | 2.94%   |
| 2933  | 1        | 2.94%   |
| 2666  | 1        | 2.94%   |
| 2400  | 1        | 2.94%   |
| 800   | 1        | 2.94%   |
| 667   | 1        | 2.94%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 2        | 28.57%  |
| Brother Industries  | 2        | 28.57%  |
| Samsung Electronics | 1        | 14.29%  |
| Kyocera             | 1        | 14.29%  |
| Canon               | 1        | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| Samsung SCX-4200 series   | 1        | 14.29%  |
| Kyocera FS-1030D printer  | 1        | 14.29%  |
| HP ENVY 4500 series       | 1        | 14.29%  |
| HP DeskJet 6940 series    | 1        | 14.29%  |
| Canon CanoScan LiDE 300   | 1        | 14.29%  |
| Brother Printer           | 1        | 14.29%  |
| Brother HL-L3210CW series | 1        | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Canon       | 3        | 75%     |
| Seiko Epson | 1        | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Seiko Epson GT-X770 [Perfection V500] | 1        | 25%     |
| Canon CanoScan N1240U/LiDE 30         | 1        | 25%     |
| Canon CanoScan LiDE 210               | 1        | 25%     |
| Canon CanoScan LiDE 110               | 1        | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 8        | 66.67%  |
| Z-Star Microelectronics | 1        | 8.33%   |
| Microsoft               | 1        | 8.33%   |
| Creative Technology     | 1        | 8.33%   |
| Chicony Electronics     | 1        | 8.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech Webcam C270          | 3        | 25%     |
| Logitech HD Pro Webcam C920   | 2        | 16.67%  |
| Logitech B525 HD Webcam       | 2        | 16.67%  |
| Z-Star Venus USB2.0 Camera    | 1        | 8.33%   |
| Microsoft LifeCam VX-700      | 1        | 8.33%   |
| Logitech Webcam C250          | 1        | 8.33%   |
| Creative Live! Cam Sync 1080p | 1        | 8.33%   |
| Chicony HP Webcam             | 1        | 8.33%   |

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
| 0     | 41       | 80.39%  |
| 1     | 10       | 19.61%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Graphics card    | 5        | 50%     |
| Unassigned class | 2        | 20%     |
| Net/wireless     | 2        | 20%     |
| Bluetooth        | 1        | 10%     |

