openSUSE Leap-15.3 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for openSUSE Leap-15.3.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 92

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek    | WS C422 PRO_SE              | [e278a4ab5e](https://linux-hardware.org/?probe=e278a4ab5e) | Sep 21, 2022 |
| Gigabyte   | Z77-DS3H                    | [7532844cd7](https://linux-hardware.org/?probe=7532844cd7) | Sep 11, 2022 |
| Biostar    | H77MU3                      | [20ba4d44ed](https://linux-hardware.org/?probe=20ba4d44ed) | Sep 05, 2022 |
| ASRock     | B85 Pro4                    | [db3bc987b6](https://linux-hardware.org/?probe=db3bc987b6) | Aug 29, 2022 |
| ASUSTek    | M3A78-EM                    | [d9fa82e283](https://linux-hardware.org/?probe=d9fa82e283) | Aug 15, 2022 |
| Lenovo     | 1036 SDK0K17763 WIN 1801... | [325cde32e5](https://linux-hardware.org/?probe=325cde32e5) | Jun 06, 2022 |
| Lenovo     | 1036 SDK0K17763 WIN 1801... | [6abee365c1](https://linux-hardware.org/?probe=6abee365c1) | Jun 06, 2022 |
| Gigabyte   | B550 AORUS PRO V2           | [7fe5175e37](https://linux-hardware.org/?probe=7fe5175e37) | May 30, 2022 |
| MSI        | B450 TOMAHAWK               | [66b453536a](https://linux-hardware.org/?probe=66b453536a) | May 24, 2022 |
| HP         | 2820h                       | [af311c3a41](https://linux-hardware.org/?probe=af311c3a41) | May 18, 2022 |
| ASRock     | Z390 Extreme4               | [4142d08db8](https://linux-hardware.org/?probe=4142d08db8) | May 11, 2022 |
| Gigabyte   | B560 HD3                    | [34fd3f60c4](https://linux-hardware.org/?probe=34fd3f60c4) | May 11, 2022 |
| Gigabyte   | B550 AORUS PRO V2           | [699a7ea54b](https://linux-hardware.org/?probe=699a7ea54b) | May 04, 2022 |
| ASRock     | Z390 Extreme4               | [344c43c31a](https://linux-hardware.org/?probe=344c43c31a) | May 04, 2022 |
| ASUSTek    | H81M-R                      | [34fa61f6bd](https://linux-hardware.org/?probe=34fa61f6bd) | Apr 11, 2022 |
| Lenovo     | 1036 SDK0K17763 WIN 1801... | [eec98977a3](https://linux-hardware.org/?probe=eec98977a3) | Apr 05, 2022 |
| Shuttle    | FS35V4                      | [bfe34cde0c](https://linux-hardware.org/?probe=bfe34cde0c) | Apr 04, 2022 |
| Gigabyte   | GA-880GM-UD2H               | [0fd3382ba7](https://linux-hardware.org/?probe=0fd3382ba7) | Apr 02, 2022 |
| Itautec    | SM 3330 SM-3330 Padrao 0... | [47e5e82b88](https://linux-hardware.org/?probe=47e5e82b88) | Apr 01, 2022 |
| ASUSTek    | H81M-R                      | [6fffff17df](https://linux-hardware.org/?probe=6fffff17df) | Mar 27, 2022 |
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
| ASUSTek    | H81M-R                      | [ea01dd4007](https://linux-hardware.org/?probe=ea01dd4007) | Jan 18, 2022 |
| Gigabyte   | G31M-S2C                    | [88d5bd947a](https://linux-hardware.org/?probe=88d5bd947a) | Jan 17, 2022 |
| ASUSTek    | H81M-R                      | [cf10bab7ad](https://linux-hardware.org/?probe=cf10bab7ad) | Jan 17, 2022 |
| Biostar    | H77MU3                      | [da779dbb31](https://linux-hardware.org/?probe=da779dbb31) | Jan 15, 2022 |
| ASUSTek    | H97M-E                      | [abf3b9c5c8](https://linux-hardware.org/?probe=abf3b9c5c8) | Jan 14, 2022 |
| ASUSTek    | H97M-E                      | [54fb155ee1](https://linux-hardware.org/?probe=54fb155ee1) | Jan 14, 2022 |
| ASUSTek    | M5A99X EVO R2.0             | [894589da9f](https://linux-hardware.org/?probe=894589da9f) | Jan 11, 2022 |
| Gigabyte   | GA-770TA-UD3                | [cda49a0b67](https://linux-hardware.org/?probe=cda49a0b67) | Jan 10, 2022 |
| ASUSTek    | TUF Gaming X570-PLUS        | [4c9489e27a](https://linux-hardware.org/?probe=4c9489e27a) | Jan 10, 2022 |
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
| 5.3.18-59.37-default        | 12       | 16.9%   |
| 5.3.18-59.19-default        | 8        | 11.27%  |
| 5.3.18-59.27-default        | 5        | 7.04%   |
| 5.3.18-59.5-default         | 4        | 5.63%   |
| 5.3.18-59.24-default        | 4        | 5.63%   |
| 5.3.18-150300.59.54-default | 4        | 5.63%   |
| 5.3.18-59.10-default        | 3        | 4.23%   |
| 5.3.18-57-default           | 3        | 4.23%   |
| 5.3.18-150300.59.87-default | 3        | 4.23%   |
| 5.3.18-150300.59.60-default | 3        | 4.23%   |
| 5.3.18-150300.59.49-default | 3        | 4.23%   |
| 5.3.18-150300.59.63-default | 2        | 2.82%   |
| 5.3.18-150300.59.43-default | 2        | 2.82%   |
| 5.3.18-lp152.57-default     | 1        | 1.41%   |
| 5.3.18-59.37-preempt        | 1        | 1.41%   |
| 5.3.18-59.34-default        | 1        | 1.41%   |
| 5.3.18-59.27-preempt        | 1        | 1.41%   |
| 5.3.18-59.24-preempt        | 1        | 1.41%   |
| 5.3.18-59.19-preempt        | 1        | 1.41%   |
| 5.3.18-59.16-default        | 1        | 1.41%   |
| 5.3.18-59.13-default        | 1        | 1.41%   |
| 5.3.18-150300.59.93-default | 1        | 1.41%   |
| 5.3.18-150300.59.90-default | 1        | 1.41%   |
| 5.3.18-150300.59.68-default | 1        | 1.41%   |
| 5.3.18-150300.59.63-preempt | 1        | 1.41%   |
| 5.3.18-150300.59.60-preempt | 1        | 1.41%   |
| 5.3.18-150300.59.49-preempt | 1        | 1.41%   |
| 5.17.2-1.gb49cf22-default   | 1        | 1.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.3.18  | 63       | 98.44%  |
| 5.17.2  | 1        | 1.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.3     | 63       | 98.44%  |
| 5.17    | 1        | 1.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 63       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE5       | 33       | 50%     |
| Unknown    | 12       | 18.18%  |
| KDE        | 9        | 13.64%  |
| GNOME      | 6        | 9.09%   |
| XFCE       | 4        | 6.06%   |
| X-Cinnamon | 1        | 1.52%   |
| LXDE       | 1        | 1.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 54       | 83.08%  |
| Tty     | 8        | 12.31%  |
| Wayland | 3        | 4.62%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 36       | 54.55%  |
| SDDM    | 14       | 21.21%  |
| LightDM | 14       | 21.21%  |
| XDM     | 2        | 3.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| de_DE   | 15       | 23.08%  |
| en_US   | 14       | 21.54%  |
| POSIX   | 9        | 13.85%  |
| pt_BR   | 5        | 7.69%   |
| ru_RU   | 3        | 4.62%   |
| nl_NL   | 3        | 4.62%   |
| Unknown | 3        | 4.62%   |
| es_ES   | 2        | 3.08%   |
| en_GB   | 2        | 3.08%   |
| tr_TR   | 1        | 1.54%   |
| sk_SK   | 1        | 1.54%   |
| pl_PL   | 1        | 1.54%   |
| nl_BE   | 1        | 1.54%   |
| hr_HR   | 1        | 1.54%   |
| fi_FI   | 1        | 1.54%   |
| es_MX   | 1        | 1.54%   |
| en_AU   | 1        | 1.54%   |
| ca_AD   | 1        | 1.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 40       | 62.5%   |
| EFI  | 24       | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 39       | 60.94%  |
| Ext4    | 21       | 32.81%  |
| Xfs     | 3        | 4.69%   |
| Overlay | 1        | 1.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 32       | 49.23%  |
| Unknown | 28       | 43.08%  |
| MBR     | 5        | 7.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 46       | 70.77%  |
| Yes       | 19       | 29.23%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 74.6%   |
| Yes       | 16       | 25.4%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 17       | 26.98%  |
| Gigabyte Technology | 10       | 15.87%  |
| MSI                 | 9        | 14.29%  |
| Hewlett-Packard     | 8        | 12.7%   |
| ASRock              | 7        | 11.11%  |
| Lenovo              | 3        | 4.76%   |
| Dell                | 2        | 3.17%   |
| VS Company          | 1        | 1.59%   |
| Shuttle             | 1        | 1.59%   |
| Itautec             | 1        | 1.59%   |
| Intel               | 1        | 1.59%   |
| Fujitsu             | 1        | 1.59%   |
| Biostar             | 1        | 1.59%   |
| Alienware           | 1        | 1.59%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Desktops | Percent |
|----------------------------------------------|----------|---------|
| ASUS All Series                              | 3        | 4.76%   |
| VS Company G31T-M                            | 1        | 1.59%   |
| Shuttle XS35V4                               | 1        | 1.59%   |
| MSI MS-7D16                                  | 1        | 1.59%   |
| MSI MS-7C34                                  | 1        | 1.59%   |
| MSI MS-7C02                                  | 1        | 1.59%   |
| MSI MS-7B89                                  | 1        | 1.59%   |
| MSI MS-7A38                                  | 1        | 1.59%   |
| MSI MS-7A34                                  | 1        | 1.59%   |
| MSI MS-7A33                                  | 1        | 1.59%   |
| MSI MS-7817                                  | 1        | 1.59%   |
| MSI ESPRIMO P1510                            | 1        | 1.59%   |
| Lenovo ThinkStation P520 30BE008VGE          | 1        | 1.59%   |
| Lenovo ThinkStation P500 30A6S4JU00          | 1        | 1.59%   |
| Lenovo IdeaCentre Y710 Cube-15ISH 90FL004WGE | 1        | 1.59%   |
| Itautec Infoway SM-3330                      | 1        | 1.59%   |
| Intel DG41WV AAE90316-104                    | 1        | 1.59%   |
| HP Z840 Workstation                          | 1        | 1.59%   |
| HP xw4400 Workstation                        | 1        | 1.59%   |
| HP Pavilion Gaming Desktop 790-00xx          | 1        | 1.59%   |
| HP Pavilion Gaming Desktop 690-00xx          | 1        | 1.59%   |
| HP EliteDesk 800 G2 DM 65W                   | 1        | 1.59%   |
| HP Compaq dc5800 Small Form Factor           | 1        | 1.59%   |
| HP 550-a114                                  | 1        | 1.59%   |
| HP 200-5120br                                | 1        | 1.59%   |
| Gigabyte Z77-DS3H                            | 1        | 1.59%   |
| Gigabyte GA-880GM-UD2H                       | 1        | 1.59%   |
| Gigabyte GA-770TA-UD3                        | 1        | 1.59%   |
| Gigabyte G31M-ES2C                           | 1        | 1.59%   |
| Gigabyte F2A68HM-DS2                         | 1        | 1.59%   |
| Gigabyte B75M-D3H                            | 1        | 1.59%   |
| Gigabyte B560 HD3                            | 1        | 1.59%   |
| Gigabyte B550 AORUS PRO V2                   | 1        | 1.59%   |
| Gigabyte B550 AORUS PRO AC                   | 1        | 1.59%   |
| Gigabyte B250M-DS3H                          | 1        | 1.59%   |
| Fujitsu ESPRIMO P520                         | 1        | 1.59%   |
| Dell Vostro 3268                             | 1        | 1.59%   |
| Dell Inspiron 530                            | 1        | 1.59%   |
| Biostar H77MU3                               | 1        | 1.59%   |
| ASUS WS C422 PRO_SE                          | 1        | 1.59%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS All               | 3        | 4.76%   |
| Lenovo ThinkStation    | 2        | 3.17%   |
| HP Pavilion            | 2        | 3.17%   |
| Gigabyte B550          | 2        | 3.17%   |
| ASUS TUF               | 2        | 3.17%   |
| ASUS ROG               | 2        | 3.17%   |
| ASUS PRIME             | 2        | 3.17%   |
| VS Company G31T-M      | 1        | 1.59%   |
| Shuttle XS35V4         | 1        | 1.59%   |
| MSI MS-7D16            | 1        | 1.59%   |
| MSI MS-7C34            | 1        | 1.59%   |
| MSI MS-7C02            | 1        | 1.59%   |
| MSI MS-7B89            | 1        | 1.59%   |
| MSI MS-7A38            | 1        | 1.59%   |
| MSI MS-7A34            | 1        | 1.59%   |
| MSI MS-7A33            | 1        | 1.59%   |
| MSI MS-7817            | 1        | 1.59%   |
| MSI ESPRIMO            | 1        | 1.59%   |
| Lenovo IdeaCentre      | 1        | 1.59%   |
| Itautec Infoway        | 1        | 1.59%   |
| Intel DG41WV           | 1        | 1.59%   |
| HP Z840                | 1        | 1.59%   |
| HP xw4400              | 1        | 1.59%   |
| HP EliteDesk           | 1        | 1.59%   |
| HP Compaq              | 1        | 1.59%   |
| HP 550-a114            | 1        | 1.59%   |
| HP 200-5120br          | 1        | 1.59%   |
| Gigabyte Z77-DS3H      | 1        | 1.59%   |
| Gigabyte GA-880GM-UD2H | 1        | 1.59%   |
| Gigabyte GA-770TA-UD3  | 1        | 1.59%   |
| Gigabyte G31M-ES2C     | 1        | 1.59%   |
| Gigabyte F2A68HM-DS2   | 1        | 1.59%   |
| Gigabyte B75M-D3H      | 1        | 1.59%   |
| Gigabyte B560          | 1        | 1.59%   |
| Gigabyte B250M-DS3H    | 1        | 1.59%   |
| Fujitsu ESPRIMO        | 1        | 1.59%   |
| Dell Vostro            | 1        | 1.59%   |
| Dell Inspiron          | 1        | 1.59%   |
| Biostar H77MU3         | 1        | 1.59%   |
| ASUS WS                | 1        | 1.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 9        | 14.29%  |
| 2019 | 8        | 12.7%   |
| 2014 | 7        | 11.11%  |
| 2012 | 6        | 9.52%   |
| 2021 | 5        | 7.94%   |
| 2010 | 4        | 6.35%   |
| 2020 | 3        | 4.76%   |
| 2015 | 3        | 4.76%   |
| 2013 | 3        | 4.76%   |
| 2011 | 3        | 4.76%   |
| 2009 | 3        | 4.76%   |
| 2008 | 3        | 4.76%   |
| 2017 | 2        | 3.17%   |
| 2016 | 2        | 3.17%   |
| 2007 | 1        | 1.59%   |
| 2006 | 1        | 1.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 63       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 61       | 96.83%  |
| Enabled  | 2        | 3.17%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 63       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 23       | 36.51%  |
| 8.01-16.0   | 10       | 15.87%  |
| 64.01-256.0 | 9        | 14.29%  |
| 32.01-64.0  | 7        | 11.11%  |
| 3.01-4.0    | 7        | 11.11%  |
| 4.01-8.0    | 5        | 7.94%   |
| 24.01-32.0  | 2        | 3.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 18       | 26.87%  |
| 4.01-8.0   | 17       | 25.37%  |
| 2.01-3.0   | 12       | 17.91%  |
| 3.01-4.0   | 10       | 14.93%  |
| 0.51-1.0   | 4        | 5.97%   |
| 8.01-16.0  | 3        | 4.48%   |
| 32.01-64.0 | 1        | 1.49%   |
| 24.01-32.0 | 1        | 1.49%   |
| 0.01-0.5   | 1        | 1.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 21       | 33.33%  |
| 1      | 18       | 28.57%  |
| 3      | 10       | 15.87%  |
| 4      | 7        | 11.11%  |
| 6      | 3        | 4.76%   |
| 5      | 3        | 4.76%   |
| 7      | 1        | 1.59%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 40       | 63.49%  |
| No        | 23       | 36.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 62       | 98.41%  |
| No        | 1        | 1.59%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 33       | 51.56%  |
| No        | 31       | 48.44%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 38       | 58.46%  |
| Yes       | 27       | 41.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Germany     | 17       | 26.98%  |
| USA         | 10       | 15.87%  |
| Brazil      | 6        | 9.52%   |
| Russia      | 4        | 6.35%   |
| Netherlands | 3        | 4.76%   |
| Australia   | 3        | 4.76%   |
| Slovakia    | 2        | 3.17%   |
| Mexico      | 2        | 3.17%   |
| Japan       | 2        | 3.17%   |
| UK          | 1        | 1.59%   |
| Turkey      | 1        | 1.59%   |
| Spain       | 1        | 1.59%   |
| Poland      | 1        | 1.59%   |
| Peru        | 1        | 1.59%   |
| Luxembourg  | 1        | 1.59%   |
| India       | 1        | 1.59%   |
| Hungary     | 1        | 1.59%   |
| Finland     | 1        | 1.59%   |
| Estonia     | 1        | 1.59%   |
| Croatia     | 1        | 1.59%   |
| Belgium     | 1        | 1.59%   |
| Austria     | 1        | 1.59%   |
| Andorra     | 1        | 1.59%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Tokyo                 | 2        | 3.17%   |
| Stolk                 | 2        | 3.17%   |
| Moscow                | 2        | 3.17%   |
| Halle                 | 2        | 3.17%   |
| Zagreb                | 1        | 1.59%   |
| Wesel                 | 1        | 1.59%   |
| Waltham               | 1        | 1.59%   |
| Vijayawada            | 1        | 1.59%   |
| Veresegyhaz           | 1        | 1.59%   |
| Três Lagoas          | 1        | 1.59%   |
| Tallinn               | 1        | 1.59%   |
| Tacna                 | 1        | 1.59%   |
| Sydney                | 1        | 1.59%   |
| Sterling              | 1        | 1.59%   |
| Stargard              | 1        | 1.59%   |
| Southampton           | 1        | 1.59%   |
| Sao Paulo             | 1        | 1.59%   |
| San Luis Potosí City | 1        | 1.59%   |
| Samorin               | 1        | 1.59%   |
| Rotterdam             | 1        | 1.59%   |
| Rottenburg            | 1        | 1.59%   |
| Rio de Janeiro        | 1        | 1.59%   |
| Rio Branco            | 1        | 1.59%   |
| Recife                | 1        | 1.59%   |
| Puyallup              | 1        | 1.59%   |
| Prosper               | 1        | 1.59%   |
| Oulu                  | 1        | 1.59%   |
| Nordenham             | 1        | 1.59%   |
| Munich                | 1        | 1.59%   |
| Melbourne             | 1        | 1.59%   |
| McDonough             | 1        | 1.59%   |
| Mansfield             | 1        | 1.59%   |
| Madrid                | 1        | 1.59%   |
| Madison               | 1        | 1.59%   |
| Luxembourg            | 1        | 1.59%   |
| London                | 1        | 1.59%   |
| Lomonosov             | 1        | 1.59%   |
| Lier                  | 1        | 1.59%   |
| Kyzyl                 | 1        | 1.59%   |
| Hanau                 | 1        | 1.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 31       | 50     | 24.03%  |
| Seagate             | 27       | 42     | 20.93%  |
| Samsung Electronics | 25       | 45     | 19.38%  |
| Kingston            | 8        | 10     | 6.2%    |
| Toshiba             | 6        | 6      | 4.65%   |
| Intel               | 4        | 4      | 3.1%    |
| Hitachi             | 4        | 6      | 3.1%    |
| Crucial             | 4        | 4      | 3.1%    |
| A-DATA Technology   | 4        | 4      | 3.1%    |
| SanDisk             | 3        | 4      | 2.33%   |
| Unknown             | 2        | 2      | 1.55%   |
| TO Exter            | 1        | 1      | 0.78%   |
| Phison              | 1        | 1      | 0.78%   |
| Micron Technology   | 1        | 2      | 0.78%   |
| Lite-On             | 1        | 1      | 0.78%   |
| JMicron Technology  | 1        | 1      | 0.78%   |
| Inateck             | 1        | 1      | 0.78%   |
| HGST HTS            | 1        | 1      | 0.78%   |
| HGST                | 1        | 1      | 0.78%   |
| Fujitsu             | 1        | 1      | 0.78%   |
| Corsair             | 1        | 1      | 0.78%   |
| Apacer              | 1        | 3      | 0.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| WDC WDS500G1X0E-00AFY0 500GB       | 2        | 1.32%   |
| WDC WD5000AAKX-07U6AA0 500GB       | 2        | 1.32%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2        | 1.32%   |
| WDC WD10EAVS-22D7B0 1TB            | 2        | 1.32%   |
| Seagate ST3750528AS 752GB          | 2        | 1.32%   |
| Seagate ST3500418AS 500GB          | 2        | 1.32%   |
| Seagate ST3500413AS 500GB          | 2        | 1.32%   |
| Seagate ST2000DM008-2FR102 2TB     | 2        | 1.32%   |
| Seagate ST2000DM006-2DM164 2TB     | 2        | 1.32%   |
| Seagate ST2000DM001-9YN164 2TB     | 2        | 1.32%   |
| Seagate ST2000DM001-1ER164 2TB     | 2        | 1.32%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 1.32%   |
| Seagate ST1000DM010-2EP102 1TB     | 2        | 1.32%   |
| Samsung SSD 980 PRO 1TB            | 2        | 1.32%   |
| Samsung SSD 870 QVO 1TB            | 2        | 1.32%   |
| Samsung SSD 860 EVO 250GB          | 2        | 1.32%   |
| Samsung SSD 850 EVO 500GB          | 2        | 1.32%   |
| Samsung HD105SI 1TB                | 2        | 1.32%   |
| Samsung HD103SI 1TB                | 2        | 1.32%   |
| Kingston SV300S37A120G 120GB SSD   | 2        | 1.32%   |
| Kingston SA400S37120G 120GB SSD    | 2        | 1.32%   |
| Hitachi HDS5C3020ALA632 2TB        | 2        | 1.32%   |
| WDC WDS500G2B0A 500GB SSD          | 1        | 0.66%   |
| WDC WDS500G1B0B-00AS40 500GB SSD   | 1        | 0.66%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1        | 0.66%   |
| WDC WDS250G1B0C-00S6U0 250GB       | 1        | 0.66%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD   | 1        | 0.66%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 1        | 0.66%   |
| WDC WDS200T2B0A-00SM50 2TB SSD     | 1        | 0.66%   |
| WDC WDS100T3X0C-00SJG0 1TB         | 1        | 0.66%   |
| WDC WDS100T1X0E-00AFY0 1TB         | 1        | 0.66%   |
| WDC WD7500AALX-009BA0 752GB        | 1        | 0.66%   |
| WDC WD5000AAVS-00ZTB0 500GB        | 1        | 0.66%   |
| WDC WD5000AAKX-08U6AA0 500GB       | 1        | 0.66%   |
| WDC WD50 00LPCX-00VHAT0 500GB      | 1        | 0.66%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 1        | 0.66%   |
| WDC WD40EZAZ-00SF3B0 4TB           | 1        | 0.66%   |
| WDC WD3200AAKS-00B3A0 320GB        | 1        | 0.66%   |
| WDC WD3200AAJS-56M0A0 320GB        | 1        | 0.66%   |
| WDC WD2500BEVT-60ZCT1 250GB        | 1        | 0.66%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 27       | 41     | 39.13%  |
| WDC                 | 24       | 38     | 34.78%  |
| Samsung Electronics | 7        | 14     | 10.14%  |
| Hitachi             | 4        | 6      | 5.8%    |
| Toshiba             | 3        | 3      | 4.35%   |
| Unknown             | 1        | 1      | 1.45%   |
| Inateck             | 1        | 1      | 1.45%   |
| HGST                | 1        | 1      | 1.45%   |
| Fujitsu             | 1        | 1      | 1.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 12       | 19     | 29.27%  |
| Kingston            | 7        | 9      | 17.07%  |
| WDC                 | 6        | 7      | 14.63%  |
| A-DATA Technology   | 4        | 4      | 9.76%   |
| SanDisk             | 3        | 4      | 7.32%   |
| Toshiba             | 2        | 2      | 4.88%   |
| Intel               | 2        | 2      | 4.88%   |
| Crucial             | 2        | 2      | 4.88%   |
| TO Exter            | 1        | 1      | 2.44%   |
| Micron Technology   | 1        | 2      | 2.44%   |
| Apacer              | 1        | 3      | 2.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 50       | 106    | 48.08%  |
| SSD     | 35       | 55     | 33.65%  |
| NVMe    | 18       | 28     | 17.31%  |
| Unknown | 1        | 2      | 0.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 60       | 156    | 72.29%  |
| NVMe | 18       | 27     | 21.69%  |
| SAS  | 5        | 8      | 6.02%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 38       | 68     | 40%     |
| 0.51-1.0   | 33       | 56     | 34.74%  |
| 1.01-2.0   | 15       | 21     | 15.79%  |
| 3.01-4.0   | 4        | 9      | 4.21%   |
| 2.01-3.0   | 2        | 2      | 2.11%   |
| 10.01-20.0 | 2        | 3      | 2.11%   |
| 4.01-10.0  | 1        | 2      | 1.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 20       | 30.77%  |
| 501-1000       | 11       | 16.92%  |
| 1001-2000      | 9        | 13.85%  |
| 251-500        | 8        | 12.31%  |
| 2001-3000      | 7        | 10.77%  |
| Unknown        | 4        | 6.15%   |
| 1-20           | 3        | 4.62%   |
| 101-250        | 2        | 3.08%   |
| 21-50          | 1        | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 12       | 18.18%  |
| 101-250        | 11       | 16.67%  |
| 501-1000       | 10       | 15.15%  |
| 1001-2000      | 8        | 12.12%  |
| 1-20           | 7        | 10.61%  |
| 51-100         | 6        | 9.09%   |
| 2001-3000      | 4        | 6.06%   |
| Unknown        | 4        | 6.06%   |
| More than 3000 | 3        | 4.55%   |
| 21-50          | 1        | 1.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| WDC WD3200AAJS-56M0A0 320GB      | 1        | 1      | 14.29%  |
| WDC WD2500BEVT-60ZCT1 250GB      | 1        | 1      | 14.29%  |
| WDC WD10PURX-64E5EY0 1TB         | 1        | 1      | 14.29%  |
| Seagate ST3320620AS 320GB        | 1        | 1      | 14.29%  |
| Seagate ST1000DM003-1CH162 1TB   | 1        | 1      | 14.29%  |
| Kingston SV300S37A120G 120GB SSD | 1        | 1      | 14.29%  |
| Crucial CT1000P1SSD8 1TB         | 1        | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| WDC      | 3        | 3      | 42.86%  |
| Seagate  | 2        | 2      | 28.57%  |
| Kingston | 1        | 1      | 14.29%  |
| Crucial  | 1        | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 60%     |
| Seagate | 2        | 2      | 40%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 5      | 66.67%  |
| NVMe | 1        | 1      | 16.67%  |
| SSD  | 1        | 1      | 16.67%  |

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
| Works    | 36       | 94     | 50.7%   |
| Detected | 29       | 90     | 40.85%  |
| Malfunc  | 6        | 7      | 8.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 36       | 37.5%   |
| AMD                          | 27       | 28.13%  |
| Samsung Electronics          | 9        | 9.38%   |
| SanDisk                      | 5        | 5.21%   |
| ASMedia Technology           | 4        | 4.17%   |
| Marvell Technology Group     | 3        | 3.13%   |
| Phison Electronics           | 2        | 2.08%   |
| Micron/Crucial Technology    | 2        | 2.08%   |
| Toshiba America Info Systems | 1        | 1.04%   |
| Silicon Image                | 1        | 1.04%   |
| Seagate Technology           | 1        | 1.04%   |
| Nvidia                       | 1        | 1.04%   |
| Lite-On Technology           | 1        | 1.04%   |
| Kingston Technology Company  | 1        | 1.04%   |
| JMicron Technology           | 1        | 1.04%   |
| Broadcom / LSI               | 1        | 1.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 17       | 14.05%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5        | 4.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5        | 4.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 5        | 4.13%   |
| AMD 400 Series Chipset SATA Controller                                         | 5        | 4.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4        | 3.31%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 4        | 3.31%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3        | 2.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3        | 2.48%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3        | 2.48%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3        | 2.48%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3        | 2.48%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 2.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 1.65%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 2        | 1.65%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2        | 1.65%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2        | 1.65%   |
| AMD X370 Series Chipset SATA Controller                                        | 2        | 1.65%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 1.65%   |
| AMD 300 Series Chipset SATA Controller                                         | 2        | 1.65%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1        | 0.83%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 0.83%   |
| Seagate FireCuda 520 SSD                                                       | 1        | 0.83%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1        | 0.83%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 0.83%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1        | 0.83%   |
| Samsung Electronics SATA controller                                            | 1        | 0.83%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 0.83%   |
| Phison E12 NVMe Controller                                                     | 1        | 0.83%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 0.83%   |
| Nvidia MCP61 IDE                                                               | 1        | 0.83%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1        | 0.83%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1        | 0.83%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                        | 1        | 0.83%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo          | 1        | 0.83%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                        | 1        | 0.83%   |
| Lite-On Non-Volatile memory controller                                         | 1        | 0.83%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                             | 1        | 0.83%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1        | 0.83%   |
| Intel SSD 660P Series                                                          | 1        | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 52       | 56.52%  |
| NVMe | 18       | 19.57%  |
| IDE  | 16       | 17.39%  |
| RAID | 5        | 5.43%   |
| SAS  | 1        | 1.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 35       | 55.56%  |
| AMD    | 28       | 44.44%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 9 5900X 12-Core Processor         | 3        | 4.76%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 3.17%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 2        | 3.17%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 3.17%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 2        | 3.17%   |
| Intel Xeon W-2145 CPU @ 3.70GHz             | 1        | 1.59%   |
| Intel Xeon W-2135 CPU @ 3.70GHz             | 1        | 1.59%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1        | 1.59%   |
| Intel Xeon CPU E5-2667 v3 @ 3.20GHz         | 1        | 1.59%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz         | 1        | 1.59%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1        | 1.59%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 1.59%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 1.59%   |
| Intel Pentium CPU G3258 @ 3.20GHz           | 1        | 1.59%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 1.59%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 1.59%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.59%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.59%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 1.59%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 1        | 1.59%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 1.59%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 1.59%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.59%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 1.59%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 1        | 1.59%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 1.59%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1        | 1.59%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1        | 1.59%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 1.59%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 1.59%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1        | 1.59%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 1        | 1.59%   |
| Intel Core 2 Quad CPU Q9300 @ 2.50GHz       | 1        | 1.59%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 1        | 1.59%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 1        | 1.59%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 1        | 1.59%   |
| Intel Core 2 CPU 6400 @ 2.13GHz             | 1        | 1.59%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 1        | 1.59%   |
| AMD Sempron 2650 APU with Radeon R3         | 1        | 1.59%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 1        | 1.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 12       | 19.05%  |
| Intel Xeon              | 6        | 9.52%   |
| AMD Ryzen 9             | 6        | 9.52%   |
| AMD Ryzen 7             | 6        | 9.52%   |
| AMD Ryzen 5             | 5        | 7.94%   |
| Intel Core i7           | 4        | 6.35%   |
| Intel Core i3           | 3        | 4.76%   |
| AMD Phenom II X4        | 3        | 4.76%   |
| Intel Core 2 Quad       | 2        | 3.17%   |
| Intel Core 2 Duo        | 2        | 3.17%   |
| AMD FX                  | 2        | 3.17%   |
| Intel Pentium Dual-Core | 1        | 1.59%   |
| Intel Pentium Dual      | 1        | 1.59%   |
| Intel Pentium           | 1        | 1.59%   |
| Intel Core i9           | 1        | 1.59%   |
| Intel Core 2            | 1        | 1.59%   |
| Intel Celeron           | 1        | 1.59%   |
| AMD Sempron             | 1        | 1.59%   |
| AMD Phenom II X6        | 1        | 1.59%   |
| AMD Phenom II X2        | 1        | 1.59%   |
| AMD Athlon              | 1        | 1.59%   |
| AMD A8                  | 1        | 1.59%   |
| AMD A10                 | 1        | 1.59%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 27       | 42.86%  |
| 2      | 11       | 17.46%  |
| 8      | 9        | 14.29%  |
| 6      | 8        | 12.7%   |
| 16     | 4        | 6.35%   |
| 12     | 3        | 4.76%   |
| 3      | 1        | 1.59%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 62       | 98.41%  |
| 2      | 1        | 1.59%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 35       | 55.56%  |
| 1      | 28       | 44.44%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 63       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 27       | 40.91%  |
| 0x306c3    | 4        | 6.06%   |
| 0x306a9    | 3        | 4.55%   |
| 0x206a7    | 3        | 4.55%   |
| 0xa0653    | 2        | 3.03%   |
| 0x906e9    | 2        | 3.03%   |
| 0x1067a    | 2        | 3.03%   |
| 0x0a201016 | 2        | 3.03%   |
| 0x0a201009 | 2        | 3.03%   |
| 0x08701021 | 2        | 3.03%   |
| 0x08001137 | 2        | 3.03%   |
| 0x010000c8 | 2        | 3.03%   |
| 0x906ec    | 1        | 1.52%   |
| 0x6fd      | 1        | 1.52%   |
| 0x50654    | 1        | 1.52%   |
| 0x306f2    | 1        | 1.52%   |
| 0x10677    | 1        | 1.52%   |
| 0x0a201204 | 1        | 1.52%   |
| 0x08108109 | 1        | 1.52%   |
| 0x08108102 | 1        | 1.52%   |
| 0x0800820d | 1        | 1.52%   |
| 0x07030105 | 1        | 1.52%   |
| 0x06000852 | 1        | 1.52%   |
| 0x010000dc | 1        | 1.52%   |
| 0x010000db | 1        | 1.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 8        | 12.7%   |
| Zen 3       | 6        | 9.52%   |
| KabyLake    | 5        | 7.94%   |
| K10         | 5        | 7.94%   |
| Zen+        | 4        | 6.35%   |
| Zen 2       | 4        | 6.35%   |
| Zen         | 4        | 6.35%   |
| Skylake     | 4        | 6.35%   |
| Penryn      | 4        | 6.35%   |
| IvyBridge   | 4        | 6.35%   |
| SandyBridge | 3        | 4.76%   |
| Core        | 3        | 4.76%   |
| Piledriver  | 2        | 3.17%   |
| CometLake   | 2        | 3.17%   |
| Steamroller | 1        | 1.59%   |
| Silvermont  | 1        | 1.59%   |
| Puma        | 1        | 1.59%   |
| Nehalem     | 1        | 1.59%   |
| Jaguar      | 1        | 1.59%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 34       | 50%     |
| AMD               | 18       | 26.47%  |
| Intel             | 14       | 20.59%  |
| S3 Graphics       | 1        | 1.47%   |
| ASPEED Technology | 1        | 1.47%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 5.8%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 4.35%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 4.35%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 3        | 4.35%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 2.9%    |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 2.9%    |
| Nvidia GF108 [GeForce GT 630]                                               | 2        | 2.9%    |
| Nvidia GA102 [GeForce RTX 3090]                                             | 2        | 2.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 2.9%    |
| Intel HD Graphics 630                                                       | 2        | 2.9%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 2.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.9%    |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 2        | 2.9%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 2.9%    |
| S3 Graphics 86c764/765 [Trio32/64/64V+]                                     | 1        | 1.45%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.45%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 1.45%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 1.45%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.45%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.45%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.45%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.45%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.45%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 1.45%   |
| Nvidia GM107GL [Quadro K2200]                                               | 1        | 1.45%   |
| Nvidia GK110GL [Quadro K5200]                                               | 1        | 1.45%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.45%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 1.45%   |
| Nvidia GA106 [GeForce RTX 3060]                                             | 1        | 1.45%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.45%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 1        | 1.45%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 1        | 1.45%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.45%   |
| Intel HD Graphics 530                                                       | 1        | 1.45%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.45%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1        | 1.45%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 1.45%   |
| ASPEED Technology ASPEED Graphics Family                                    | 1        | 1.45%   |
| AMD RV610 [Radeon HD 2400 PRO]                                              | 1        | 1.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 31       | 49.21%  |
| 1 x AMD         | 16       | 25.4%   |
| 1 x Intel       | 11       | 17.46%  |
| 2 x AMD         | 1        | 1.59%   |
| 1 x S3 Graphics | 1        | 1.59%   |
| Nvidia + ASPEED | 1        | 1.59%   |
| Intel + Nvidia  | 1        | 1.59%   |
| AMD + Nvidia    | 1        | 1.59%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 39       | 60.94%  |
| Proprietary | 21       | 32.81%  |
| Unknown     | 4        | 6.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 33       | 50%     |
| 1.01-2.0   | 11       | 16.67%  |
| 3.01-4.0   | 5        | 7.58%   |
| 7.01-8.0   | 4        | 6.06%   |
| 8.01-16.0  | 3        | 4.55%   |
| 0.51-1.0   | 3        | 4.55%   |
| 5.01-6.0   | 2        | 3.03%   |
| 16.01-24.0 | 2        | 3.03%   |
| 0.01-0.5   | 2        | 3.03%   |
| 2.01-3.0   | 1        | 1.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 13       | 18.06%  |
| Dell                 | 11       | 15.28%  |
| Samsung Electronics  | 7        | 9.72%   |
| Ancor Communications | 6        | 8.33%   |
| BenQ                 | 5        | 6.94%   |
| Philips              | 4        | 5.56%   |
| Hewlett-Packard      | 4        | 5.56%   |
| Acer                 | 4        | 5.56%   |
| AOC                  | 3        | 4.17%   |
| ViewSonic            | 2        | 2.78%   |
| Medion               | 2        | 2.78%   |
| LG Electronics       | 2        | 2.78%   |
| Vizio                | 1        | 1.39%   |
| TCL                  | 1        | 1.39%   |
| Lenovo               | 1        | 1.39%   |
| Iiyama               | 1        | 1.39%   |
| Hitachi              | 1        | 1.39%   |
| Fujitsu Siemens      | 1        | 1.39%   |
| Denver               | 1        | 1.39%   |
| ASUSTek Computer     | 1        | 1.39%   |
| AGO                  | 1        | 1.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch            | 2        | 2.6%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 2        | 2.6%    |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch               | 2        | 2.6%    |
| Vizio E60-E3 VIZ1018 3840x2160 1330x748mm 60.1-inch                  | 1        | 1.3%    |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                     | 1        | 1.3%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM0524 1920x1080 480x270mm 21.7-inch | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM00A2 1024x768 304x228mm 15.0-inch  | 1        | 1.3%    |
| Samsung Electronics SMS27A850T SAM0887 2560x1440 518x324mm 24.1-inch | 1        | 1.3%    |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 1        | 1.3%    |
| Samsung Electronics S34J55x SAM0F72 1720x1440                        | 1        | 1.3%    |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch    | 1        | 1.3%    |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch    | 1        | 1.3%    |
| Philips PHL 258B6QU PHL08F5 2560x1440 553x311mm 25.0-inch            | 1        | 1.3%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 1        | 1.3%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 1        | 1.3%    |
| Philips 150S PHL0812 1024x768 307x230mm 15.1-inch                    | 1        | 1.3%    |
| Philips 150S PHL0805 1024x768 307x230mm 15.1-inch                    | 1        | 1.3%    |
| Medion MD30999PE MED8928 1440x900 410x256mm 19.0-inch                | 1        | 1.3%    |
| Medion MD20581 MED369A 1920x1080 597x336mm 27.0-inch                 | 1        | 1.3%    |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                    | 1        | 1.3%    |
| LG Electronics LCD Monitor LG TV SSCR 3840x2160                      | 1        | 1.3%    |
| Lenovo LEN T27i-10 LEN61C6 1920x1080 598x336mm 27.0-inch             | 1        | 1.3%    |
| Iiyama PL2592H IVM6135 1920x1080 544x303mm 24.5-inch                 | 1        | 1.3%    |
| Hitachi X90W D-sub HIT6008 1440x900 410x257mm 19.1-inch              | 1        | 1.3%    |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch         | 1        | 1.3%    |
| Hewlett-Packard 27fw HPN354A 1920x1080 598x336mm 27.0-inch           | 1        | 1.3%    |
| Hewlett-Packard 27es HWP3326 1920x1080 598x336mm 27.0-inch           | 1        | 1.3%    |
| Hewlett-Packard 22m HPN3576 1920x1080 476x268mm 21.5-inch            | 1        | 1.3%    |
| Goldstar W2261 GSM56CF 1920x1080 530x300mm 24.0-inch                 | 1        | 1.3%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 1        | 1.3%    |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                 | 1        | 1.3%    |
| Goldstar M2380D GSM57BC 1920x1080 598x336mm 27.0-inch                | 1        | 1.3%    |
| Goldstar L1718S GSM443C 1280x1024 338x270mm 17.0-inch                | 1        | 1.3%    |
| Goldstar E2742 GSM58C9 1920x1080 598x337mm 27.0-inch                 | 1        | 1.3%    |
| Goldstar E2441 GSM581F 1920x1080 531x299mm 24.0-inch                 | 1        | 1.3%    |
| Goldstar E2011 GSM4ED4 1600x900 443x249mm 20.0-inch                  | 1        | 1.3%    |
| Goldstar BN550Y GSM5BAB 1920x1080 600x340mm 27.2-inch                | 1        | 1.3%    |
| Goldstar BK550Y GSM5B40 1920x1080 480x270mm 21.7-inch                | 1        | 1.3%    |
| Fujitsu Siemens B19-5 ECO FUS07C0 1280x1024 376x301mm 19.0-inch      | 1        | 1.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 30       | 46.15%  |
| 3840x2160 (4K)     | 7        | 10.77%  |
| 2560x1440 (QHD)    | 6        | 9.23%   |
| 3440x1440          | 3        | 4.62%   |
| 1440x900 (WXGA+)   | 3        | 4.62%   |
| 1280x1024 (SXGA)   | 3        | 4.62%   |
| 1024x768 (XGA)     | 3        | 4.62%   |
| 2560x1080          | 2        | 3.08%   |
| 1920x1200 (WUXGA)  | 2        | 3.08%   |
| 1680x1050 (WSXGA+) | 2        | 3.08%   |
| 1600x900 (HD+)     | 2        | 3.08%   |
| 640x480            | 1        | 1.54%   |
| 1366x768 (WXGA)    | 1        | 1.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 13       | 19.12%  |
| 27      | 12       | 17.65%  |
| 24      | 8        | 11.76%  |
| 23      | 6        | 8.82%   |
| 15      | 4        | 5.88%   |
| 34      | 3        | 4.41%   |
| 19      | 3        | 4.41%   |
| Unknown | 3        | 4.41%   |
| 31      | 2        | 2.94%   |
| 25      | 2        | 2.94%   |
| 22      | 2        | 2.94%   |
| 20      | 2        | 2.94%   |
| 17      | 2        | 2.94%   |
| 74      | 1        | 1.47%   |
| 42      | 1        | 1.47%   |
| 35      | 1        | 1.47%   |
| 32      | 1        | 1.47%   |
| 18      | 1        | 1.47%   |
| 12      | 1        | 1.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 24       | 35.82%  |
| 401-500     | 21       | 31.34%  |
| 301-350     | 6        | 8.96%   |
| 701-800     | 4        | 5.97%   |
| 601-700     | 4        | 5.97%   |
| Unknown     | 3        | 4.48%   |
| 801-900     | 1        | 1.49%   |
| 351-400     | 1        | 1.49%   |
| 201-300     | 1        | 1.49%   |
| 1501-2000   | 1        | 1.49%   |
| 901-1000    | 1        | 1.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 41       | 65.08%  |
| 16/10   | 8        | 12.7%   |
| 4/3     | 4        | 6.35%   |
| 21/9    | 4        | 6.35%   |
| 5/4     | 3        | 4.76%   |
| Unknown | 3        | 4.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 24       | 35.29%  |
| 301-350        | 12       | 17.65%  |
| 351-500        | 7        | 10.29%  |
| 151-200        | 7        | 10.29%  |
| 251-300        | 5        | 7.35%   |
| 101-110        | 4        | 5.88%   |
| 141-150        | 3        | 4.41%   |
| Unknown        | 3        | 4.41%   |
| More than 1000 | 1        | 1.47%   |
| 71-80          | 1        | 1.47%   |
| 501-1000       | 1        | 1.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 37       | 56.92%  |
| 101-120 | 21       | 32.31%  |
| 121-160 | 3        | 4.62%   |
| Unknown | 3        | 4.62%   |
| 161-240 | 1        | 1.54%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 48       | 75%     |
| 2     | 9        | 14.06%  |
| 0     | 4        | 6.25%   |
| 3     | 3        | 4.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 43       | 47.25%  |
| Intel                 | 25       | 27.47%  |
| Qualcomm Atheros      | 6        | 6.59%   |
| Ralink                | 4        | 4.4%    |
| Broadcom              | 2        | 2.2%    |
| ZyXEL Communications  | 1        | 1.1%    |
| TP-Link               | 1        | 1.1%    |
| TOMTOM                | 1        | 1.1%    |
| Samsung Electronics   | 1        | 1.1%    |
| Ralink Technology     | 1        | 1.1%    |
| NetXen Incorporated   | 1        | 1.1%    |
| Edimax Technology     | 1        | 1.1%    |
| D-Link System         | 1        | 1.1%    |
| Broadcom Limited      | 1        | 1.1%    |
| AVM                   | 1        | 1.1%    |
| ASIX Electronics      | 1        | 1.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 33       | 30.84%  |
| Realtek RTL8125 2.5GbE Controller                                    | 5        | 4.67%   |
| Intel Wi-Fi 6 AX200                                                  | 5        | 4.67%   |
| Intel I211 Gigabit Network Connection                                | 5        | 4.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 3        | 2.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2        | 1.87%   |
| Intel Wireless-AC 9260                                               | 2        | 1.87%   |
| Intel Wireless 7260                                                  | 2        | 1.87%   |
| Intel I210 Gigabit Network Connection                                | 2        | 1.87%   |
| Intel Ethernet Connection (2) I218-LM                                | 2        | 1.87%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]         | 1        | 0.93%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 1        | 0.93%   |
| TOMTOM GO 60                                                         | 1        | 0.93%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 1        | 0.93%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 1        | 0.93%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 1        | 0.93%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1        | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1        | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1        | 0.93%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                      | 1        | 0.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 1        | 0.93%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                           | 1        | 0.93%   |
| Realtek Killer E3000 2.5GbE Controller                               | 1        | 0.93%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 1        | 0.93%   |
| Ralink RT3072 Wireless Adapter                                       | 1        | 0.93%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 1        | 0.93%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                 | 1        | 0.93%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 1        | 0.93%   |
| Ralink RT2561/RT61 802.11g PCI                                       | 1        | 0.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1        | 0.93%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                            | 1        | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1        | 0.93%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 1        | 0.93%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 1        | 0.93%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                             | 1        | 0.93%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 1        | 0.93%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter | 1        | 0.93%   |
| Intel Wireless 8260                                                  | 1        | 0.93%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 1        | 0.93%   |
| Intel I350 Gigabit Network Connection                                | 1        | 0.93%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 12       | 35.29%  |
| Realtek Semiconductor | 7        | 20.59%  |
| Ralink                | 4        | 11.76%  |
| Qualcomm Atheros      | 3        | 8.82%   |
| ZyXEL Communications  | 1        | 2.94%   |
| TP-Link               | 1        | 2.94%   |
| Ralink Technology     | 1        | 2.94%   |
| Edimax Technology     | 1        | 2.94%   |
| D-Link System         | 1        | 2.94%   |
| Broadcom Limited      | 1        | 2.94%   |
| Broadcom              | 1        | 2.94%   |
| AVM                   | 1        | 2.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 5        | 14.71%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 2        | 5.88%   |
| Intel Wireless-AC 9260                                                     | 2        | 5.88%   |
| Intel Wireless 7260                                                        | 2        | 5.88%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]               | 1        | 2.94%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                        | 1        | 2.94%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 1        | 2.94%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 1        | 2.94%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                      | 1        | 2.94%   |
| Realtek RTL8188EE Wireless Network Adapter                                 | 1        | 2.94%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 1        | 2.94%   |
| Ralink RT3072 Wireless Adapter                                             | 1        | 2.94%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1        | 2.94%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                       | 1        | 2.94%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                       | 1        | 2.94%   |
| Ralink RT2561/RT61 802.11g PCI                                             | 1        | 2.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 1        | 2.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 1        | 2.94%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1        | 2.94%   |
| Intel Wireless 8260                                                        | 1        | 2.94%   |
| Intel Tiger Lake PCH CNVi WiFi                                             | 1        | 2.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 1        | 2.94%   |
| Edimax AC1200 MU-MIMO USB2.0 Adapter                                       | 1        | 2.94%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 1        | 2.94%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                 | 1        | 2.94%   |
| Broadcom BCM43142 802.11b/g/n                                              | 1        | 2.94%   |
| AVM Fritz!WLAN N v2 [Atheros AR9271]                                       | 1        | 2.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 43       | 63.24%  |
| Intel                 | 17       | 25%     |
| Qualcomm Atheros      | 4        | 5.88%   |
| Samsung Electronics   | 1        | 1.47%   |
| NetXen Incorporated   | 1        | 1.47%   |
| Broadcom              | 1        | 1.47%   |
| ASIX Electronics      | 1        | 1.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 33       | 45.83%  |
| Realtek RTL8125 2.5GbE Controller                                    | 5        | 6.94%   |
| Intel I211 Gigabit Network Connection                                | 5        | 6.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 3        | 4.17%   |
| Intel I210 Gigabit Network Connection                                | 2        | 2.78%   |
| Intel Ethernet Connection (2) I218-LM                                | 2        | 2.78%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 1        | 1.39%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                      | 1        | 1.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 1        | 1.39%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                           | 1        | 1.39%   |
| Realtek Killer E3000 2.5GbE Controller                               | 1        | 1.39%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 1        | 1.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                            | 1        | 1.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 1        | 1.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                             | 1        | 1.39%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 1        | 1.39%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter | 1        | 1.39%   |
| Intel I350 Gigabit Network Connection                                | 1        | 1.39%   |
| Intel Ethernet Connection I217-V                                     | 1        | 1.39%   |
| Intel Ethernet Connection (7) I219-V                                 | 1        | 1.39%   |
| Intel Ethernet Connection (2) I219-LM                                | 1        | 1.39%   |
| Intel 82579V Gigabit Network Connection                              | 1        | 1.39%   |
| Intel 82574L Gigabit Network Connection                              | 1        | 1.39%   |
| Intel 82566DM-2 Gigabit Network Connection                           | 1        | 1.39%   |
| Intel 82562V-2 10/100 Network Connection                             | 1        | 1.39%   |
| Intel 82541PI Gigabit Ethernet Controller                            | 1        | 1.39%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                      | 1        | 1.39%   |
| ASIX AX88179 Gigabit Ethernet                                        | 1        | 1.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 62       | 64.58%  |
| WiFi     | 33       | 34.38%  |
| Unknown  | 1        | 1.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 50       | 72.46%  |
| WiFi     | 18       | 26.09%  |
| Unknown  | 1        | 1.45%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 32       | 50.79%  |
| 2     | 25       | 39.68%  |
| 3     | 4        | 6.35%   |
| 5     | 1        | 1.59%   |
| 4     | 1        | 1.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 49       | 76.56%  |
| Yes  | 15       | 23.44%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 10       | 37.04%  |
| Cambridge Silicon Radio         | 8        | 29.63%  |
| Realtek Semiconductor           | 2        | 7.41%   |
| Qualcomm Atheros Communications | 2        | 7.41%   |
| ASUSTek Computer                | 2        | 7.41%   |
| Dell                            | 1        | 3.7%    |
| Broadcom                        | 1        | 3.7%    |
| Belkin Components               | 1        | 3.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 8        | 29.63%  |
| Intel AX200 Bluetooth                                 | 4        | 14.81%  |
| Realtek  Bluetooth 4.2 Adapter                        | 2        | 7.41%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 2        | 7.41%   |
| Intel Bluetooth wireless interface                    | 2        | 7.41%   |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 3.7%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1        | 3.7%    |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 3.7%    |
| Intel AX201 Bluetooth                                 | 1        | 3.7%    |
| Dell Broadcom BCM20702A0 Bluetooth                    | 1        | 3.7%    |
| Broadcom BCM43142A0 Bluetooth Device                  | 1        | 3.7%    |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 1        | 3.7%    |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 3.7%    |
| ASUS Bluetooth Adapter                                | 1        | 3.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| AMD                       | 35       | 31.25%  |
| Nvidia                    | 34       | 30.36%  |
| Intel                     | 32       | 28.57%  |
| C-Media Electronics       | 4        | 3.57%   |
| Creative Labs             | 3        | 2.68%   |
| Texas Instruments         | 1        | 0.89%   |
| Sennheiser Communications | 1        | 0.89%   |
| BEHRINGER International   | 1        | 0.89%   |
| ASUSTek Computer          | 1        | 0.89%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 10       | 8%      |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 4.8%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6        | 4.8%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4        | 3.2%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 3.2%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 3.2%    |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 2.4%    |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 2.4%    |
| Nvidia GK106 HDMI Audio Controller                                         | 3        | 2.4%    |
| Nvidia GA102 High Definition Audio Controller                              | 3        | 2.4%    |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 2.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 2.4%    |
| Intel 200 Series PCH HD Audio                                              | 3        | 2.4%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 2.4%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 2.4%    |
| AMD FCH Azalia Controller                                                  | 3        | 2.4%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 1.6%    |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 1.6%    |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 1.6%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 1.6%    |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 1.6%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 1.6%    |
| Intel Audio device                                                         | 2        | 1.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 1.6%    |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 2        | 1.6%    |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 2        | 1.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 1.6%    |
| AMD Kabini HDMI/DP Audio                                                   | 2        | 1.6%    |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 1.6%    |
| Texas Instruments PCM2900C Audio CODEC                                     | 1        | 0.8%    |
| Sennheiser Communications Sennheiser 3D G4ME1                              | 1        | 0.8%    |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.8%    |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.8%    |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.8%    |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 0.8%    |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 0.8%    |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 0.8%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.8%    |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 0.8%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 11       | 24.44%  |
| Unknown             | 6        | 13.33%  |
| G.Skill             | 6        | 13.33%  |
| Crucial             | 5        | 11.11%  |
| Corsair             | 5        | 11.11%  |
| Samsung Electronics | 4        | 8.89%   |
| Patriot             | 2        | 4.44%   |
| Team                | 1        | 2.22%   |
| Micron Technology   | 1        | 2.22%   |
| GeIL                | 1        | 2.22%   |
| Elpida              | 1        | 2.22%   |
| AMD                 | 1        | 2.22%   |
| A-DATA Technology   | 1        | 2.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Kingston RAM KHX3600C18D4/32GX 32GB DIMM DDR4 3600MT/s     | 2        | 4.08%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s     | 2        | 4.08%   |
| G.Skill RAM F4-2400C15-8GNT 8192MB DIMM DDR4 2666MT/s      | 2        | 4.08%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                  | 1        | 2.04%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                    | 1        | 2.04%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s               | 1        | 2.04%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 1        | 2.04%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                    | 1        | 2.04%   |
| Unknown RAM 992124 (997124) 8GB DIMM DDR3 1600MT/s         | 1        | 2.04%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 3007MT/s         | 1        | 2.04%   |
| Samsung RAM M471B5673FH0-CH9 2048MB DIMM SDRAM 4199MT/s    | 1        | 2.04%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s       | 1        | 2.04%   |
| Samsung RAM M393A1G40DB0-CPB 8GB DIMM 2133MT/s             | 1        | 2.04%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s        | 1        | 2.04%   |
| Samsung RAM M3 78T2863EHS-CF7 1024MB DIMM DDR2 800MT/s     | 1        | 2.04%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s            | 1        | 2.04%   |
| Patriot RAM PSD22G80026 2048MB DIMM DDR2 800MT/s           | 1        | 2.04%   |
| Micron RAM 16JTF1G64AZ-1G6D1 8GB DIMM DDR3 1600MT/s        | 1        | 2.04%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s          | 1        | 2.04%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s        | 1        | 2.04%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s        | 1        | 2.04%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s       | 1        | 2.04%   |
| Kingston RAM 99U5474-016.A00LF 4GB DIMM DDR3 1600MT/s      | 1        | 2.04%   |
| Kingston RAM 99U5471-040.A00LF 8GB DIMM DDR3 1333MT/s      | 1        | 2.04%   |
| Kingston RAM 9965698-001.A00G 16GB DIMM DDR4 2667MT/s      | 1        | 2.04%   |
| Kingston RAM 9905474-012.A00LF 2048MB DIMM DDR3 1333MT/s   | 1        | 2.04%   |
| Kingston RAM 9905471-028.A00LF 4096MB DIMM DDR3 1333MT/s   | 1        | 2.04%   |
| GeIL RAM CL11-11-11 D3-1600 8GB DIMM DDR3 1600MT/s         | 1        | 2.04%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s        | 1        | 2.04%   |
| G.Skill RAM F4-3200C15-16GTZKY 16384MB DIMM DDR4 3200MT/s  | 1        | 2.04%   |
| G.Skill RAM F4-2666C19-16GIS 16384MB DIMM DDR4 2667MT/s    | 1        | 2.04%   |
| G.Skill RAM F3-10666CL9-4GBNT 4GB DIMM DDR3 1400MT/s       | 1        | 2.04%   |
| Elpida RAM EBE11UD8AJWA-6E-E 1GB DIMM DDR2 667MT/s         | 1        | 2.04%   |
| Crucial RAM CT8G4DFS8266.M8FE 8GB DIMM DDR4 2667MT/s       | 1        | 2.04%   |
| Crucial RAM CT16G4DFRA266.C16FE 16384MB DIMM DDR4 2667MT/s | 1        | 2.04%   |
| Crucial RAM CT102464BD160B.M16 8GB DIMM DDR3 1600MT/s      | 1        | 2.04%   |
| Crucial RAM BLS16G4D32AESB.M16FE 16GB DIMM DDR4 3600MT/s   | 1        | 2.04%   |
| Crucial RAM BL32G32C16U4R.M16FB1 32GB DIMM DDR4 3200MT/s   | 1        | 2.04%   |
| Corsair RAM CMZ8GX3M2A1866C9 4GB DIMM DDR3 1867MT/s        | 1        | 2.04%   |
| Corsair RAM CMT64GX4M4E3200C16 16GB DIMM DDR4 3200MT/s     | 1        | 2.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 20       | 52.63%  |
| DDR3    | 12       | 31.58%  |
| DDR2    | 3        | 7.89%   |
| Unknown | 2        | 5.26%   |
| SDRAM   | 1        | 2.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 38       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 17       | 38.64%  |
| 16384 | 12       | 27.27%  |
| 4096  | 5        | 11.36%  |
| 2048  | 5        | 11.36%  |
| 32768 | 3        | 6.82%   |
| 1024  | 2        | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 7        | 15.91%  |
| 1333  | 6        | 13.64%  |
| 3600  | 4        | 9.09%   |
| 3200  | 4        | 9.09%   |
| 2667  | 4        | 9.09%   |
| 800   | 3        | 6.82%   |
| 3800  | 2        | 4.55%   |
| 2666  | 2        | 4.55%   |
| 2133  | 2        | 4.55%   |
| 1867  | 2        | 4.55%   |
| 4199  | 1        | 2.27%   |
| 3466  | 1        | 2.27%   |
| 3007  | 1        | 2.27%   |
| 2934  | 1        | 2.27%   |
| 2933  | 1        | 2.27%   |
| 2400  | 1        | 2.27%   |
| 1400  | 1        | 2.27%   |
| 667   | 1        | 2.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 2        | 25%     |
| Canon               | 2        | 25%     |
| Brother Industries  | 2        | 25%     |
| Samsung Electronics | 1        | 12.5%   |
| Kyocera             | 1        | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| Samsung SCX-4200 series   | 1        | 12.5%   |
| Kyocera FS-1030D printer  | 1        | 12.5%   |
| HP ENVY 4500 series       | 1        | 12.5%   |
| HP DeskJet 6940 series    | 1        | 12.5%   |
| Canon LiDE 300            | 1        | 12.5%   |
| Canon G3020 series        | 1        | 12.5%   |
| Brother Printer           | 1        | 12.5%   |
| Brother HL-L3210CW series | 1        | 12.5%   |

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
| Logitech                | 10       | 58.82%  |
| Z-Star Microelectronics | 1        | 5.88%   |
| Microsoft               | 1        | 5.88%   |
| Hewlett-Packard         | 1        | 5.88%   |
| Generalplus Technology  | 1        | 5.88%   |
| Cubeternet              | 1        | 5.88%   |
| Creative Technology     | 1        | 5.88%   |
| Chicony Electronics     | 1        | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech Webcam C270          | 3        | 17.65%  |
| Logitech HD Pro Webcam C920   | 2        | 11.76%  |
| Logitech B525 HD Webcam       | 2        | 11.76%  |
| Z-Star Venus USB2.0 Camera    | 1        | 5.88%   |
| Microsoft LifeCam VX-700      | 1        | 5.88%   |
| Logitech Webcam C250          | 1        | 5.88%   |
| Logitech QuickCam Pro 4000    | 1        | 5.88%   |
| Logitech HD Webcam C615       | 1        | 5.88%   |
| HP Webcam 3100                | 1        | 5.88%   |
| Generalplus GENERAL WEBCAM    | 1        | 5.88%   |
| Cubeternet USB2.0 Camera      | 1        | 5.88%   |
| Creative Live! Cam Sync 1080p | 1        | 5.88%   |
| Chicony HP Webcam             | 1        | 5.88%   |

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
| 0     | 51       | 78.46%  |
| 1     | 13       | 20%     |
| 2     | 1        | 1.54%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Graphics card    | 6        | 42.86%  |
| Net/wireless     | 3        | 21.43%  |
| Unassigned class | 2        | 14.29%  |
| Sound            | 2        | 14.29%  |
| Bluetooth        | 1        | 7.14%   |

