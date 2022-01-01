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


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 5.3.18-59.19-default    | 8        | 20.51%  |
| 5.3.18-59.37-default    | 5        | 12.82%  |
| 5.3.18-59.27-default    | 5        | 12.82%  |
| 5.3.18-59.5-default     | 4        | 10.26%  |
| 5.3.18-59.24-default    | 4        | 10.26%  |
| 5.3.18-59.10-default    | 3        | 7.69%   |
| 5.3.18-57-default       | 3        | 7.69%   |
| 5.3.18-lp152.57-default | 1        | 2.56%   |
| 5.3.18-59.34-default    | 1        | 2.56%   |
| 5.3.18-59.27-preempt    | 1        | 2.56%   |
| 5.3.18-59.24-preempt    | 1        | 2.56%   |
| 5.3.18-59.19-preempt    | 1        | 2.56%   |
| 5.3.18-59.16-default    | 1        | 2.56%   |
| 5.3.18-59.13-default    | 1        | 2.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.3.18  | 37       | 100%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.3     | 37       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 37       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE5       | 14       | 36.84%  |
| KDE        | 9        | 23.68%  |
| Unknown    | 8        | 21.05%  |
| XFCE       | 3        | 7.89%   |
| GNOME      | 3        | 7.89%   |
| X-Cinnamon | 1        | 2.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 30       | 78.95%  |
| Tty     | 6        | 15.79%  |
| Wayland | 2        | 5.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 23       | 62.16%  |
| LightDM | 7        | 18.92%  |
| SDDM    | 5        | 13.51%  |
| XDM     | 2        | 5.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 12       | 32.43%  |
| de_DE   | 7        | 18.92%  |
| POSIX   | 5        | 13.51%  |
| pt_BR   | 3        | 8.11%   |
| tr_TR   | 1        | 2.7%    |
| pl_PL   | 1        | 2.7%    |
| nl_BE   | 1        | 2.7%    |
| hr_HR   | 1        | 2.7%    |
| es_MX   | 1        | 2.7%    |
| es_ES   | 1        | 2.7%    |
| en_GB   | 1        | 2.7%    |
| en_AU   | 1        | 2.7%    |
| ca_AD   | 1        | 2.7%    |
| Unknown | 1        | 2.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 22       | 59.46%  |
| EFI  | 15       | 40.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 24       | 64.86%  |
| Ext4    | 10       | 27.03%  |
| Xfs     | 2        | 5.41%   |
| Overlay | 1        | 2.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 19       | 50%     |
| GPT     | 18       | 47.37%  |
| MBR     | 1        | 2.63%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 78.95%  |
| Yes       | 8        | 21.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 75.68%  |
| Yes       | 9        | 24.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 10       | 27.03%  |
| MSI                 | 8        | 21.62%  |
| Hewlett-Packard     | 5        | 13.51%  |
| ASRock              | 5        | 13.51%  |
| Gigabyte Technology | 2        | 5.41%   |
| Dell                | 2        | 5.41%   |
| VS Company          | 1        | 2.7%    |
| Lenovo              | 1        | 2.7%    |
| Intel               | 1        | 2.7%    |
| Fujitsu             | 1        | 2.7%    |
| Alienware           | 1        | 2.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Desktops | Percent |
|----------------------------------------------|----------|---------|
| VS Company G31T-M                            | 1        | 2.7%    |
| MSI MS-7D16                                  | 1        | 2.7%    |
| MSI MS-7C34                                  | 1        | 2.7%    |
| MSI MS-7B89                                  | 1        | 2.7%    |
| MSI MS-7A38                                  | 1        | 2.7%    |
| MSI MS-7A34                                  | 1        | 2.7%    |
| MSI MS-7A33                                  | 1        | 2.7%    |
| MSI MS-7817                                  | 1        | 2.7%    |
| MSI ESPRIMO P1510                            | 1        | 2.7%    |
| Lenovo IdeaCentre Y710 Cube-15ISH 90FL004WGE | 1        | 2.7%    |
| Intel DG41WV AAE90316-104                    | 1        | 2.7%    |
| HP xw4400 Workstation                        | 1        | 2.7%    |
| HP Pavilion Gaming Desktop 790-00xx          | 1        | 2.7%    |
| HP Pavilion Gaming Desktop 690-00xx          | 1        | 2.7%    |
| HP EliteDesk 800 G2 DM 65W                   | 1        | 2.7%    |
| HP 200-5120br                                | 1        | 2.7%    |
| Gigabyte B550 AORUS PRO AC                   | 1        | 2.7%    |
| Gigabyte B250M-DS3H                          | 1        | 2.7%    |
| Fujitsu ESPRIMO P520                         | 1        | 2.7%    |
| Dell Vostro 3268                             | 1        | 2.7%    |
| Dell Inspiron 530                            | 1        | 2.7%    |
| ASUS TUF B450-PRO GAMING                     | 1        | 2.7%    |
| ASUS ROG CROSSHAIR VIII HERO                 | 1        | 2.7%    |
| ASUS PRIME H310M-A                           | 1        | 2.7%    |
| ASUS PRIME A320M-E                           | 1        | 2.7%    |
| ASUS P9X79 PRO                               | 1        | 2.7%    |
| ASUS P8Z77-V LX                              | 1        | 2.7%    |
| ASUS P8H61-M LE/USB3                         | 1        | 2.7%    |
| ASUS M4A78T-E                                | 1        | 2.7%    |
| ASUS CROSSHAIR VI HERO                       | 1        | 2.7%    |
| ASUS All Series                              | 1        | 2.7%    |
| ASRock Z68 Extreme4 Gen3                     | 1        | 2.7%    |
| ASRock X570M Pro4                            | 1        | 2.7%    |
| ASRock X570 Steel Legend                     | 1        | 2.7%    |
| ASRock N68C-GS4 FX                           | 1        | 2.7%    |
| ASRock B450M Pro4                            | 1        | 2.7%    |
| Alienware X51 R2                             | 1        | 2.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| HP Pavilion         | 2        | 5.41%   |
| ASUS PRIME          | 2        | 5.41%   |
| VS Company G31T-M   | 1        | 2.7%    |
| MSI MS-7D16         | 1        | 2.7%    |
| MSI MS-7C34         | 1        | 2.7%    |
| MSI MS-7B89         | 1        | 2.7%    |
| MSI MS-7A38         | 1        | 2.7%    |
| MSI MS-7A34         | 1        | 2.7%    |
| MSI MS-7A33         | 1        | 2.7%    |
| MSI MS-7817         | 1        | 2.7%    |
| MSI ESPRIMO         | 1        | 2.7%    |
| Lenovo IdeaCentre   | 1        | 2.7%    |
| Intel DG41WV        | 1        | 2.7%    |
| HP xw4400           | 1        | 2.7%    |
| HP EliteDesk        | 1        | 2.7%    |
| HP 200-5120br       | 1        | 2.7%    |
| Gigabyte B550       | 1        | 2.7%    |
| Gigabyte B250M-DS3H | 1        | 2.7%    |
| Fujitsu ESPRIMO     | 1        | 2.7%    |
| Dell Vostro         | 1        | 2.7%    |
| Dell Inspiron       | 1        | 2.7%    |
| ASUS TUF            | 1        | 2.7%    |
| ASUS ROG            | 1        | 2.7%    |
| ASUS P9X79          | 1        | 2.7%    |
| ASUS P8Z77-V        | 1        | 2.7%    |
| ASUS P8H61-M        | 1        | 2.7%    |
| ASUS M4A78T-E       | 1        | 2.7%    |
| ASUS CROSSHAIR      | 1        | 2.7%    |
| ASUS All            | 1        | 2.7%    |
| ASRock Z68          | 1        | 2.7%    |
| ASRock X570M        | 1        | 2.7%    |
| ASRock X570         | 1        | 2.7%    |
| ASRock N68C-GS4     | 1        | 2.7%    |
| ASRock B450M        | 1        | 2.7%    |
| Alienware X51       | 1        | 2.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 8        | 21.62%  |
| 2019 | 5        | 13.51%  |
| 2018 | 5        | 13.51%  |
| 2010 | 5        | 13.51%  |
| 2020 | 3        | 8.11%   |
| 2016 | 3        | 8.11%   |
| 2014 | 2        | 5.41%   |
| 2011 | 2        | 5.41%   |
| 2017 | 1        | 2.7%    |
| 2015 | 1        | 2.7%    |
| 2009 | 1        | 2.7%    |
| 2007 | 1        | 2.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 37       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 36       | 97.3%   |
| Enabled  | 1        | 2.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 37       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 13       | 35.14%  |
| 8.01-16.0   | 7        | 18.92%  |
| 64.01-256.0 | 6        | 16.22%  |
| 32.01-64.0  | 4        | 10.81%  |
| 3.01-4.0    | 4        | 10.81%  |
| 4.01-8.0    | 2        | 5.41%   |
| 24.01-32.0  | 1        | 2.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 13       | 34.21%  |
| 4.01-8.0  | 8        | 21.05%  |
| 3.01-4.0  | 7        | 18.42%  |
| 2.01-3.0  | 6        | 15.79%  |
| 8.01-16.0 | 2        | 5.26%   |
| 0.51-1.0  | 2        | 5.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 11       | 29.73%  |
| 2      | 10       | 27.03%  |
| 3      | 9        | 24.32%  |
| 4      | 4        | 10.81%  |
| 6      | 2        | 5.41%   |
| 7      | 1        | 2.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 19       | 51.35%  |
| No        | 18       | 48.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 36       | 97.3%   |
| No        | 1        | 2.7%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 24       | 64.86%  |
| No        | 13       | 35.14%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 51.35%  |
| Yes       | 18       | 48.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| Germany    | 8        | 21.62%  |
| USA        | 7        | 18.92%  |
| Brazil     | 4        | 10.81%  |
| Australia  | 3        | 8.11%   |
| Mexico     | 2        | 5.41%   |
| Japan      | 2        | 5.41%   |
| Turkey     | 1        | 2.7%    |
| Spain      | 1        | 2.7%    |
| Slovakia   | 1        | 2.7%    |
| Russia     | 1        | 2.7%    |
| Poland     | 1        | 2.7%    |
| Luxembourg | 1        | 2.7%    |
| India      | 1        | 2.7%    |
| Hungary    | 1        | 2.7%    |
| Croatia    | 1        | 2.7%    |
| Belgium    | 1        | 2.7%    |
| Andorra    | 1        | 2.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Tokyo                 | 2        | 5.41%   |
| Zagreb                | 1        | 2.7%    |
| Vijayawada            | 1        | 2.7%    |
| TrÃªs Lagoas          | 1        | 2.7%    |
| SÃ£o Paulo            | 1        | 2.7%    |
| Sydney                | 1        | 2.7%    |
| Stupava               | 1        | 2.7%    |
| Stabroek              | 1        | 2.7%    |
| San Luis Potos?­ City | 1        | 2.7%    |
| Saint Albans          | 1        | 2.7%    |
| Recife                | 1        | 2.7%    |
| Oregon                | 1        | 2.7%    |
| Nordenham             | 1        | 2.7%    |
| Munich                | 1        | 2.7%    |
| Melbourne             | 1        | 2.7%    |
| McDonough             | 1        | 2.7%    |
| Mansfield             | 1        | 2.7%    |
| Madrid                | 1        | 2.7%    |
| Luxembourg            | 1        | 2.7%    |
| Lomonosov             | 1        | 2.7%    |
| Koleczkowo            | 1        | 2.7%    |
| Heinsberg             | 1        | 2.7%    |
| Hamelin               | 1        | 2.7%    |
| Halle                 | 1        | 2.7%    |
| Gelnhausen            | 1        | 2.7%    |
| G?¶d?¶ll?‘            | 1        | 2.7%    |
| Federal Way           | 1        | 2.7%    |
| East Longmeadow       | 1        | 2.7%    |
| Dornhan               | 1        | 2.7%    |
| Chapec??              | 1        | 2.7%    |
| Canc??n               | 1        | 2.7%    |
| Brush                 | 1        | 2.7%    |
| Brisbane              | 1        | 2.7%    |
| Braunschweig          | 1        | 2.7%    |
| Antalya               | 1        | 2.7%    |
| Andorra la Vella      | 1        | 2.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 20       | 30     | 25%     |
| Seagate             | 15       | 20     | 18.75%  |
| Samsung Electronics | 11       | 18     | 13.75%  |
| Toshiba             | 4        | 4      | 5%      |
| Kingston            | 4        | 4      | 5%      |
| A-DATA Technology   | 4        | 4      | 5%      |
| SanDisk             | 3        | 4      | 3.75%   |
| Intel               | 3        | 3      | 3.75%   |
| Hitachi             | 3        | 4      | 3.75%   |
| Crucial             | 3        | 3      | 3.75%   |
| Unknown             | 1        | 1      | 1.25%   |
| TO Exter            | 1        | 1      | 1.25%   |
| Phison              | 1        | 1      | 1.25%   |
| Lite-On             | 1        | 1      | 1.25%   |
| JMicron             | 1        | 1      | 1.25%   |
| Inateck             | 1        | 1      | 1.25%   |
| HGST HTS            | 1        | 1      | 1.25%   |
| HGST                | 1        | 1      | 1.25%   |
| Fujitsu             | 1        | 1      | 1.25%   |
| Corsair             | 1        | 1      | 1.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Seagate ST3750528AS 752GB                  | 2        | 2.2%    |
| Seagate ST2000DM008-2FR102 2TB             | 2        | 2.2%    |
| Seagate ST2000DM006-2DM164 2TB             | 2        | 2.2%    |
| Samsung SSD 860 EVO 250GB                  | 2        | 2.2%    |
| Samsung SSD 850 EVO 500GB                  | 2        | 2.2%    |
| WDC WDS500G1X0E-00AFY0 500GB               | 1        | 1.1%    |
| WDC WDS500G1B0B-00AS40 500GB SSD           | 1        | 1.1%    |
| WDC WDS250G1B0C-00S6U0 250GB               | 1        | 1.1%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD           | 1        | 1.1%    |
| WDC WDS200T2B0A-00SM50 2TB SSD             | 1        | 1.1%    |
| WDC WDS100T3X0C-00SJG0 1TB                 | 1        | 1.1%    |
| WDC WDS100T1X0E-00AFY0 1TB                 | 1        | 1.1%    |
| WDC WD7500AALX-009BA0 752GB                | 1        | 1.1%    |
| WDC WD5000AAVS-00ZTB0 500GB                | 1        | 1.1%    |
| WDC WD5000AAKX-07U6AA0 500GB               | 1        | 1.1%    |
| WDC WD50 00LPCX-00VHAT0 500GB              | 1        | 1.1%    |
| WDC WD3200AAKS-00B3A0 320GB                | 1        | 1.1%    |
| WDC WD2500BEVT-60ZCT1 250GB                | 1        | 1.1%    |
| WDC WD2500AAJS-00VTA0 250GB                | 1        | 1.1%    |
| WDC WD20EARX-00PASB0 2TB                   | 1        | 1.1%    |
| WDC WD2005FBYZ-01YCBB2 2TB                 | 1        | 1.1%    |
| WDC WD10EZEX-75WN4A0 1TB                   | 1        | 1.1%    |
| WDC WD10EZEX-75M2NA0 1TB                   | 1        | 1.1%    |
| WDC WD10EZEX-08WN4A0 1TB                   | 1        | 1.1%    |
| WDC WD10EZEX-00KUWA0 1TB                   | 1        | 1.1%    |
| WDC WD10EZEX-00BN5A0 1TB                   | 1        | 1.1%    |
| WDC WD10EAVS-22D7B0 1TB                    | 1        | 1.1%    |
| WDC WD10EACS-00D6B1 1TB                    | 1        | 1.1%    |
| WDC WD1003FZEX-00K3CA0 1TB                 | 1        | 1.1%    |
| WDC WD1001FALS-00E3A0 1TB                  | 1        | 1.1%    |
| Unknown 128GB SATA FLASH DRIVE             | 1        | 1.1%    |
| Toshiba TR200 240GB SSD                    | 1        | 1.1%    |
| Toshiba TL100 240GB SSD                    | 1        | 1.1%    |
| Toshiba NVMe SSD Drive 256GB               | 1        | 1.1%    |
| Toshiba HDWD130 3TB                        | 1        | 1.1%    |
| TO Exter nal USB 3.0 250GB                 | 1        | 1.1%    |
| Seagate ST500LM0 12 HN-M500MBB 500GB       | 1        | 1.1%    |
| Seagate ST3750630AS 752GB                  | 1        | 1.1%    |
| Seagate ST3320620AS 320GB                  | 1        | 1.1%    |
| Seagate ST3160812AS 160GB                  | 1        | 1.1%    |
| Seagate ST3000DM007-1WY10G 3TB             | 1        | 1.1%    |
| Seagate ST2000DM001-1ER164 2TB             | 1        | 1.1%    |
| Seagate ST16000NM001G-2KK103 16TB          | 1        | 1.1%    |
| Seagate ST1000VX000-1CU162 1TB             | 1        | 1.1%    |
| Seagate ST1000LM024 HN-M101MBB 1TB         | 1        | 1.1%    |
| Seagate ST1000DM010-2EP102 1TB             | 1        | 1.1%    |
| Seagate ST1000DM003-1SB102 1TB             | 1        | 1.1%    |
| Seagate FireCuda 520 SSD ZP2000GM30002 2TB | 1        | 1.1%    |
| SanDisk SDSSDA240G 240GB                   | 1        | 1.1%    |
| SanDisk SD7SB6S256G1001 256GB SSD          | 1        | 1.1%    |
| SanDisk SD7SB3Q-256G-1006 256GB SSD        | 1        | 1.1%    |
| Samsung SSD 980 PRO 1TB                    | 1        | 1.1%    |
| Samsung SSD 970 EVO Plus 2TB               | 1        | 1.1%    |
| Samsung SSD 870 QVO 1TB                    | 1        | 1.1%    |
| Samsung SSD 860 EVO 1TB                    | 1        | 1.1%    |
| Samsung SSD 850 EVO 250GB                  | 1        | 1.1%    |
| Samsung SSD 840 Series 120GB               | 1        | 1.1%    |
| Samsung MZVPV512HDGL-000H1 512GB           | 1        | 1.1%    |
| Samsung HD401LJ 400GB                      | 1        | 1.1%    |
| Samsung HD105SI 1TB                        | 1        | 1.1%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 23     | 37.5%   |
| Seagate             | 15       | 19     | 37.5%   |
| Hitachi             | 3        | 4      | 7.5%    |
| Samsung Electronics | 2        | 5      | 5%      |
| Toshiba             | 1        | 1      | 2.5%    |
| TO Exter            | 1        | 1      | 2.5%    |
| Inateck             | 1        | 1      | 2.5%    |
| HGST                | 1        | 1      | 2.5%    |
| Fujitsu             | 1        | 1      | 2.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 6        | 10     | 23.08%  |
| Kingston            | 4        | 4      | 15.38%  |
| A-DATA Technology   | 4        | 4      | 15.38%  |
| WDC                 | 3        | 3      | 11.54%  |
| SanDisk             | 3        | 4      | 11.54%  |
| Toshiba             | 2        | 2      | 7.69%   |
| Intel               | 2        | 2      | 7.69%   |
| JMicron             | 1        | 1      | 3.85%   |
| Crucial             | 1        | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 29       | 56     | 44.62%  |
| SSD     | 23       | 31     | 35.38%  |
| NVMe    | 12       | 15     | 18.46%  |
| Unknown | 1        | 2      | 1.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 36       | 83     | 70.59%  |
| NVMe | 12       | 15     | 23.53%  |
| SAS  | 3        | 6      | 5.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 23       | 39     | 40.35%  |
| 0.51-1.0   | 20       | 29     | 35.09%  |
| 1.01-2.0   | 10       | 14     | 17.54%  |
| 2.01-3.0   | 2        | 2      | 3.51%   |
| 10.01-20.0 | 2        | 3      | 3.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 11       | 28.95%  |
| 1001-2000      | 7        | 18.42%  |
| 251-500        | 6        | 15.79%  |
| 2001-3000      | 5        | 13.16%  |
| 501-1000       | 5        | 13.16%  |
| 1-20           | 2        | 5.26%   |
| 101-250        | 1        | 2.63%   |
| Unknown        | 1        | 2.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 8        | 20.51%  |
| 101-250        | 6        | 15.38%  |
| 501-1000       | 6        | 15.38%  |
| 51-100         | 6        | 15.38%  |
| 1001-2000      | 5        | 12.82%  |
| 1-20           | 4        | 10.26%  |
| 2001-3000      | 2        | 5.13%   |
| More than 3000 | 1        | 2.56%   |
| Unknown        | 1        | 2.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| WDC WD2500BEVT-60ZCT1 250GB      | 1        | 1      | 25%     |
| Seagate ST3320620AS 320GB        | 1        | 1      | 25%     |
| Kingston SV300S37A120G 120GB SSD | 1        | 1      | 25%     |
| Crucial CT1000P1SSD8 1TB         | 1        | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| WDC      | 1        | 1      | 25%     |
| Seagate  | 1        | 1      | 25%     |
| Kingston | 1        | 1      | 25%     |
| Crucial  | 1        | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 50%     |
| Seagate | 1        | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 2      | 50%     |
| NVMe | 1        | 1      | 25%     |
| SSD  | 1        | 1      | 25%     |

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
| Detected | 19       | 51     | 46.34%  |
| Works    | 18       | 49     | 43.9%   |
| Malfunc  | 4        | 4      | 9.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 21       | 36.84%  |
| AMD                          | 16       | 28.07%  |
| Sandisk                      | 4        | 7.02%   |
| Samsung Electronics          | 3        | 5.26%   |
| Phison Electronics           | 2        | 3.51%   |
| Micron/Crucial Technology    | 2        | 3.51%   |
| Marvell Technology Group     | 2        | 3.51%   |
| ASMedia Technology           | 2        | 3.51%   |
| Toshiba America Info Systems | 1        | 1.75%   |
| Silicon Image                | 1        | 1.75%   |
| Seagate Technology           | 1        | 1.75%   |
| Nvidia                       | 1        | 1.75%   |
| Lite-On Technology           | 1        | 1.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 13       | 18.31%  |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 5.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 4.23%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                              | 2        | 2.82%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 2.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 2.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 2.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 2.82%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 2.82%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 2.82%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 2.82%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 1        | 1.41%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1        | 1.41%   |
| Seagate FireCuda 520 SSD                                                                | 1        | 1.41%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1        | 1.41%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 1.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 1.41%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 1.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 1.41%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.41%   |
| Phison E12 NVMe Controller                                                              | 1        | 1.41%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 1.41%   |
| Nvidia MCP61 IDE                                                                        | 1        | 1.41%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 1.41%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 1.41%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                                 | 1        | 1.41%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1        | 1.41%   |
| Lite-On Non-Volatile memory controller                                                  | 1        | 1.41%   |
| Intel SSD 660P Series                                                                   | 1        | 1.41%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 1.41%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 1.41%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 1.41%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 1.41%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 1.41%   |
| Intel 82801GR/GDH (ICH7R/ICH7DH) SATA Controller [RAID mode]                            | 1        | 1.41%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 1.41%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.41%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 1.41%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.41%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 1        | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 1.41%   |
| AMD FCH SATA Controller D                                                               | 1        | 1.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 30       | 56.6%   |
| NVMe | 12       | 22.64%  |
| IDE  | 8        | 15.09%  |
| RAID | 3        | 5.66%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 20       | 54.05%  |
| AMD    | 17       | 45.95%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 9 5950X 16-Core Processor         | 2        | 5.41%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 5.41%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 2        | 5.41%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1        | 2.7%    |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 2.7%    |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 2.7%    |
| Intel Pentium CPU G3258 @ 3.20GHz           | 1        | 2.7%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 2.7%    |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 2.7%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 2.7%    |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 2.7%    |
| Intel Core i5-7600K CPU @ 3.80GHz           | 1        | 2.7%    |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 2.7%    |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 2.7%    |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 2.7%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 2.7%    |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1        | 2.7%    |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 2.7%    |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 2.7%    |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1        | 2.7%    |
| Intel Core 2 Quad CPU Q9300 @ 2.50GHz       | 1        | 2.7%    |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 1        | 2.7%    |
| Intel Core 2 CPU 6400 @ 2.13GHz             | 1        | 2.7%    |
| AMD Sempron 2650 APU with Radeon R3         | 1        | 2.7%    |
| AMD Ryzen 9 3950X 16-Core Processor         | 1        | 2.7%    |
| AMD Ryzen 7 3800X 8-Core Processor          | 1        | 2.7%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 1        | 2.7%    |
| AMD Ryzen 7 2700X Eight-Core Processor      | 1        | 2.7%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 1        | 2.7%    |
| AMD Ryzen 5 1600X Six-Core Processor        | 1        | 2.7%    |
| AMD Ryzen 5 1600 Six-Core Processor         | 1        | 2.7%    |
| AMD Phenom II X4 B50 Processor              | 1        | 2.7%    |
| AMD FX-8350 Eight-Core Processor            | 1        | 2.7%    |
| AMD Athlon 3000G with Radeon Vega Graphics  | 1        | 2.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 7        | 18.92%  |
| AMD Ryzen 9             | 5        | 13.51%  |
| AMD Ryzen 7             | 5        | 13.51%  |
| Intel Core i7           | 4        | 10.81%  |
| AMD Ryzen 5             | 3        | 8.11%   |
| Intel Core i3           | 2        | 5.41%   |
| Intel Xeon              | 1        | 2.7%    |
| Intel Pentium Dual-Core | 1        | 2.7%    |
| Intel Pentium Dual      | 1        | 2.7%    |
| Intel Pentium           | 1        | 2.7%    |
| Intel Core 2 Quad       | 1        | 2.7%    |
| Intel Core 2 Duo        | 1        | 2.7%    |
| Intel Core 2            | 1        | 2.7%    |
| AMD Sempron             | 1        | 2.7%    |
| AMD Phenom II X4        | 1        | 2.7%    |
| AMD FX                  | 1        | 2.7%    |
| AMD Athlon              | 1        | 2.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 14       | 37.84%  |
| 2      | 8        | 21.62%  |
| 8      | 6        | 16.22%  |
| 6      | 4        | 10.81%  |
| 16     | 3        | 8.11%   |
| 12     | 2        | 5.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 37       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 22       | 59.46%  |
| 1      | 15       | 40.54%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 37       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 17       | 43.59%  |
| 0x906e9    | 2        | 5.13%   |
| 0x306c3    | 2        | 5.13%   |
| 0x206a7    | 2        | 5.13%   |
| 0x0a201016 | 2        | 5.13%   |
| 0x0a201009 | 2        | 5.13%   |
| 0x08001137 | 2        | 5.13%   |
| 0xa0653    | 1        | 2.56%   |
| 0x6fd      | 1        | 2.56%   |
| 0x306a9    | 1        | 2.56%   |
| 0x1067a    | 1        | 2.56%   |
| 0x10677    | 1        | 2.56%   |
| 0x08701021 | 1        | 2.56%   |
| 0x08108109 | 1        | 2.56%   |
| 0x08108102 | 1        | 2.56%   |
| 0x0800820d | 1        | 2.56%   |
| 0x010000db | 1        | 2.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 3       | 4        | 10.81%  |
| Zen         | 4        | 10.81%  |
| KabyLake    | 4        | 10.81%  |
| Zen+        | 3        | 8.11%   |
| Zen 2       | 3        | 8.11%   |
| Penryn      | 3        | 8.11%   |
| Haswell     | 3        | 8.11%   |
| Skylake     | 2        | 5.41%   |
| SandyBridge | 2        | 5.41%   |
| IvyBridge   | 2        | 5.41%   |
| Core        | 2        | 5.41%   |
| Piledriver  | 1        | 2.7%    |
| Nehalem     | 1        | 2.7%    |
| K10         | 1        | 2.7%    |
| Jaguar      | 1        | 2.7%    |
| CometLake   | 1        | 2.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 17       | 43.59%  |
| AMD    | 12       | 30.77%  |
| Intel  | 10       | 25.64%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 5.13%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 2        | 5.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 5.13%   |
| Intel HD Graphics 630                                                       | 2        | 5.13%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 5.13%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 2        | 5.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 5.13%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 5.13%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 2.56%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 2.56%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 2.56%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 2.56%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 2.56%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 2.56%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 2.56%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 2.56%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 2.56%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 2.56%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 2.56%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 1        | 2.56%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 1        | 2.56%   |
| Intel HD Graphics 530                                                       | 1        | 2.56%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 2.56%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 2.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 2.56%   |
| AMD RV610 [Radeon HD 2400 PRO]                                              | 1        | 2.56%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 1        | 2.56%   |
| AMD Oland PRO [Radeon R7 240/340]                                           | 1        | 2.56%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 2.56%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                     | 1        | 2.56%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 1        | 2.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 17       | 45.95%  |
| 1 x AMD    | 12       | 32.43%  |
| 1 x Intel  | 8        | 21.62%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 26       | 70.27%  |
| Proprietary | 10       | 27.03%  |
| Unknown     | 1        | 2.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 21       | 53.85%  |
| 1.01-2.0   | 4        | 10.26%  |
| 7.01-8.0   | 3        | 7.69%   |
| 3.01-4.0   | 3        | 7.69%   |
| 16.01-24.0 | 2        | 5.13%   |
| 8.01-16.0  | 2        | 5.13%   |
| 0.51-1.0   | 2        | 5.13%   |
| 5.01-6.0   | 1        | 2.56%   |
| 0.01-0.5   | 1        | 2.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 7        | 17.07%  |
| Dell                 | 6        | 14.63%  |
| Samsung Electronics  | 5        | 12.2%   |
| BenQ                 | 4        | 9.76%   |
| Ancor Communications | 4        | 9.76%   |
| Philips              | 3        | 7.32%   |
| Acer                 | 3        | 7.32%   |
| LG Electronics       | 2        | 4.88%   |
| Hewlett-Packard      | 2        | 4.88%   |
| AOC                  | 2        | 4.88%   |
| ViewSonic            | 1        | 2.44%   |
| TCL                  | 1        | 2.44%   |
| Denver               | 1        | 2.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch             | 1        | 2.33%   |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                      | 1        | 2.33%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1        | 2.33%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 477x268mm 21.5-inch  | 1        | 2.33%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 1        | 2.33%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch     | 1        | 2.33%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 1        | 2.33%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch     | 1        | 2.33%   |
| Philips PHL 258B6QU PHL08F5 2560x1440 553x311mm 25.0-inch             | 1        | 2.33%   |
| Philips 150S PHL0812 1024x768 307x230mm 15.1-inch                     | 1        | 2.33%   |
| Philips 150S PHL0805 1024x768 307x230mm 15.1-inch                     | 1        | 2.33%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 1        | 2.33%   |
| LG Electronics LCD Monitor LG TV SSCR 3840x2160                       | 1        | 2.33%   |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch          | 1        | 2.33%   |
| Hewlett-Packard 27es HWP3326 1920x1080 598x336mm 27.0-inch            | 1        | 2.33%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                  | 1        | 2.33%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch           | 1        | 2.33%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch             | 1        | 2.33%   |
| Goldstar L1718S GSM443C 1280x1024 338x270mm 17.0-inch                 | 1        | 2.33%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1        | 2.33%   |
| Goldstar E2742 GSM58C9 1920x1080 598x337mm 27.0-inch                  | 1        | 2.33%   |
| Goldstar E2441 GSM581F 1920x1080 531x299mm 24.0-inch                  | 1        | 2.33%   |
| Denver UWQHD-100-V2 LHC3500 3440x1440 798x342mm 34.2-inch             | 1        | 2.33%   |
| Dell UZ2315H DELF055 1920x1080 509x286mm 23.0-inch                    | 1        | 2.33%   |
| Dell U2711 DELA057 2560x1440 597x336mm 27.0-inch                      | 1        | 2.33%   |
| Dell S2216H DELD07A 1920x1080 476x268mm 21.5-inch                     | 1        | 2.33%   |
| Dell P2219H DELA114 1920x1080 476x267mm 21.5-inch                     | 1        | 2.33%   |
| Dell E228WFP DELD014 1680x1050 473x296mm 22.0-inch                    | 1        | 2.33%   |
| Dell 1703FP DEL3011 1280x1024 338x270mm 17.0-inch                     | 1        | 2.33%   |
| BenQ SW2700 BNQ7F47 2560x1440 596x335mm 26.9-inch                     | 1        | 2.33%   |
| BenQ PD2500Q BNQ802A 2560x1440 553x311mm 25.0-inch                    | 1        | 2.33%   |
| BenQ BL2405 BNQ8016 1920x1080 531x298mm 24.0-inch                     | 1        | 2.33%   |
| BenQ BenQT221W BNQ7719 1680x1050 470x290mm 21.7-inch                  | 1        | 2.33%   |
| AOC LCD Monitor 28E850 640x480                                        | 1        | 2.33%   |
| AOC 2436 AOC2436 1920x1080 521x293mm 23.5-inch                        | 1        | 2.33%   |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 408x255mm 18.9-inch  | 1        | 2.33%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 1        | 2.33%   |
| Ancor Communications ASUS VN248 ACI24C4 1920x1080 530x300mm 24.0-inch | 1        | 2.33%   |
| Ancor Communications ASUS VN247 ACI24C3 1920x1080 520x290mm 23.4-inch | 1        | 2.33%   |
| Acer X163W ACR0015 1366x768 344x193mm 15.5-inch                       | 1        | 2.33%   |
| Acer V203H ACR0102 1600x900 443x249mm 20.0-inch                       | 1        | 2.33%   |
| Acer V203H ACR00C7 1600x900 443x249mm 20.0-inch                       | 1        | 2.33%   |
| Acer GD245HQ ACR0125 1920x1080 520x290mm 23.4-inch                    | 1        | 2.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 16       | 43.24%  |
| 2560x1440 (QHD)    | 4        | 10.81%  |
| 3840x2160 (4K)     | 3        | 8.11%   |
| 3440x1440          | 2        | 5.41%   |
| 2560x1080          | 2        | 5.41%   |
| 1680x1050 (WSXGA+) | 2        | 5.41%   |
| 1280x1024 (SXGA)   | 2        | 5.41%   |
| 1024x768 (XGA)     | 2        | 5.41%   |
| 640x480            | 1        | 2.7%    |
| 1600x900 (HD+)     | 1        | 2.7%    |
| 1440x900 (WXGA+)   | 1        | 2.7%    |
| 1366x768 (WXGA)    | 1        | 2.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 7        | 18.42%  |
| 27      | 6        | 15.79%  |
| 23      | 4        | 10.53%  |
| 34      | 3        | 7.89%   |
| 15      | 3        | 7.89%   |
| Unknown | 3        | 7.89%   |
| 24      | 2        | 5.26%   |
| 22      | 2        | 5.26%   |
| 17      | 2        | 5.26%   |
| 32      | 1        | 2.63%   |
| 31      | 1        | 2.63%   |
| 25      | 1        | 2.63%   |
| 20      | 1        | 2.63%   |
| 19      | 1        | 2.63%   |
| 18      | 1        | 2.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 12       | 31.58%  |
| 401-500     | 12       | 31.58%  |
| 301-350     | 5        | 13.16%  |
| 701-800     | 4        | 10.53%  |
| Unknown     | 3        | 7.89%   |
| 601-700     | 2        | 5.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 23       | 63.89%  |
| 21/9    | 3        | 8.33%   |
| 16/10   | 3        | 8.33%   |
| Unknown | 3        | 8.33%   |
| 5/4     | 2        | 5.56%   |
| 4/3     | 2        | 5.56%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 14       | 36.84%  |
| 301-350        | 6        | 15.79%  |
| 351-500        | 5        | 13.16%  |
| 151-200        | 3        | 7.89%   |
| 141-150        | 3        | 7.89%   |
| 101-110        | 3        | 7.89%   |
| Unknown        | 3        | 7.89%   |
| 251-300        | 1        | 2.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 20       | 54.05%  |
| 101-120 | 13       | 35.14%  |
| Unknown | 3        | 8.11%   |
| 121-160 | 1        | 2.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 28       | 75.68%  |
| 2     | 6        | 16.22%  |
| 0     | 2        | 5.41%   |
| 3     | 1        | 2.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 25       | 43.86%  |
| Intel                 | 15       | 26.32%  |
| Qualcomm Atheros      | 4        | 7.02%   |
| Ralink                | 3        | 5.26%   |
| ZyXEL Communications  | 1        | 1.75%   |
| TP-Link               | 1        | 1.75%   |
| TOMTOM                | 1        | 1.75%   |
| Samsung Electronics   | 1        | 1.75%   |
| Ralink Technology     | 1        | 1.75%   |
| NetXen Incorporated   | 1        | 1.75%   |
| D-Link System         | 1        | 1.75%   |
| Broadcom Limited      | 1        | 1.75%   |
| Broadcom              | 1        | 1.75%   |
| AVM                   | 1        | 1.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 19       | 28.36%  |
| Intel Wi-Fi 6 AX200                                                        | 4        | 5.97%   |
| Intel I211 Gigabit Network Connection                                      | 4        | 5.97%   |
| Realtek RTL8125 2.5GbE Controller                                          | 3        | 4.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 2        | 2.99%   |
| Intel Wireless 7260                                                        | 2        | 2.99%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]               | 1        | 1.49%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                        | 1        | 1.49%   |
| TOMTOM GO 60                                                               | 1        | 1.49%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 1.49%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 1        | 1.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 1        | 1.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1        | 1.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 1        | 1.49%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1        | 1.49%   |
| Realtek Killer E3000 2.5GbE Controller                                     | 1        | 1.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                           | 1        | 1.49%   |
| Ralink RT3072 Wireless Adapter                                             | 1        | 1.49%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1        | 1.49%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                       | 1        | 1.49%   |
| Ralink RT2561/RT61 802.11g PCI                                             | 1        | 1.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 1        | 1.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 1        | 1.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 1        | 1.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                  | 1        | 1.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 1.49%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter       | 1        | 1.49%   |
| Intel Wireless-AC 9260                                                     | 1        | 1.49%   |
| Intel Wireless 8260                                                        | 1        | 1.49%   |
| Intel Tiger Lake PCH CNVi WiFi                                             | 1        | 1.49%   |
| Intel Ethernet Connection (2) I219-LM                                      | 1        | 1.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 1        | 1.49%   |
| Intel 82579V Gigabit Network Connection                                    | 1        | 1.49%   |
| Intel 82574L Gigabit Network Connection                                    | 1        | 1.49%   |
| Intel 82562V-2 10/100 Network Connection                                   | 1        | 1.49%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 1        | 1.49%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                            | 1        | 1.49%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                 | 1        | 1.49%   |
| AVM Fritz!WLAN N v2 [Atheros AR9271]                                       | 1        | 1.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 10       | 40%     |
| Realtek Semiconductor | 4        | 16%     |
| Ralink                | 3        | 12%     |
| Qualcomm Atheros      | 2        | 8%      |
| ZyXEL Communications  | 1        | 4%      |
| TP-Link               | 1        | 4%      |
| Ralink Technology     | 1        | 4%      |
| D-Link System         | 1        | 4%      |
| Broadcom Limited      | 1        | 4%      |
| AVM                   | 1        | 4%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 4        | 16%     |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 2        | 8%      |
| Intel Wireless 7260                                                        | 2        | 8%      |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]               | 1        | 4%      |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                        | 1        | 4%      |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 1        | 4%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 1        | 4%      |
| Ralink RT3072 Wireless Adapter                                             | 1        | 4%      |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1        | 4%      |
| Ralink RT3060 Wireless 802.11n 1T/1R                                       | 1        | 4%      |
| Ralink RT2561/RT61 802.11g PCI                                             | 1        | 4%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 1        | 4%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 1        | 4%      |
| Intel Wireless-AC 9260                                                     | 1        | 4%      |
| Intel Wireless 8260                                                        | 1        | 4%      |
| Intel Tiger Lake PCH CNVi WiFi                                             | 1        | 4%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 1        | 4%      |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 1        | 4%      |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                 | 1        | 4%      |
| AVM Fritz!WLAN N v2 [Atheros AR9271]                                       | 1        | 4%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 25       | 64.1%   |
| Intel                 | 8        | 20.51%  |
| Qualcomm Atheros      | 3        | 7.69%   |
| Samsung Electronics   | 1        | 2.56%   |
| NetXen Incorporated   | 1        | 2.56%   |
| Broadcom              | 1        | 2.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 19       | 46.34%  |
| Intel I211 Gigabit Network Connection                                | 4        | 9.76%   |
| Realtek RTL8125 2.5GbE Controller                                    | 3        | 7.32%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 1        | 2.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 1        | 2.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 1        | 2.44%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                           | 1        | 2.44%   |
| Realtek Killer E3000 2.5GbE Controller                               | 1        | 2.44%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 1        | 2.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                            | 1        | 2.44%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 1        | 2.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 1        | 2.44%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter | 1        | 2.44%   |
| Intel Ethernet Connection (2) I219-LM                                | 1        | 2.44%   |
| Intel 82579V Gigabit Network Connection                              | 1        | 2.44%   |
| Intel 82574L Gigabit Network Connection                              | 1        | 2.44%   |
| Intel 82562V-2 10/100 Network Connection                             | 1        | 2.44%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                      | 1        | 2.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 36       | 59.02%  |
| WiFi     | 24       | 39.34%  |
| Unknown  | 1        | 1.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 32       | 60.38%  |
| WiFi     | 20       | 37.74%  |
| Unknown  | 1        | 1.89%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 17       | 45.95%  |
| 2     | 16       | 43.24%  |
| 3     | 3        | 8.11%   |
| 5     | 1        | 2.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 31       | 81.58%  |
| Yes  | 7        | 18.42%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 8        | 44.44%  |
| Cambridge Silicon Radio         | 3        | 16.67%  |
| Realtek Semiconductor           | 2        | 11.11%  |
| Qualcomm Atheros Communications | 2        | 11.11%  |
| Dell                            | 1        | 5.56%   |
| Belkin Components               | 1        | 5.56%   |
| ASUSTek Computer                | 1        | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                 | 3        | 16.67%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 3        | 16.67%  |
| Realtek  Bluetooth 4.2 Adapter                        | 2        | 11.11%  |
| Qualcomm Atheros  Bluetooth Device                    | 2        | 11.11%  |
| Intel Bluetooth Device                                | 2        | 11.11%  |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 5.56%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 5.56%   |
| Intel Bluetooth wireless interface                    | 1        | 5.56%   |
| Dell Broadcom BCM20702A0 Bluetooth                    | 1        | 5.56%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 1        | 5.56%   |
| ASUS Bluetooth Adapter                                | 1        | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| AMD                       | 22       | 33.85%  |
| Intel                     | 19       | 29.23%  |
| Nvidia                    | 17       | 26.15%  |
| Creative Labs             | 2        | 3.08%   |
| C-Media Electronics       | 2        | 3.08%   |
| Texas Instruments         | 1        | 1.54%   |
| Sennheiser Communications | 1        | 1.54%   |
| BEHRINGER International   | 1        | 1.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 7        | 9.59%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5        | 6.85%   |
| Nvidia GA102 High Definition Audio Controller                              | 3        | 4.11%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 4.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 4.11%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 2.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 2.74%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 2.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 2.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 2.74%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 2        | 2.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 2.74%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 2.74%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 2        | 2.74%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 2.74%   |
| Texas Instruments PCM2900C Audio CODEC                                     | 1        | 1.37%   |
| Sennheiser Communications Sennheiser 3D G4ME1                              | 1        | 1.37%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 1.37%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 1.37%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1.37%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 1.37%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.37%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 1.37%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 1.37%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 1.37%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 1.37%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 1.37%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 1.37%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 1.37%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 1.37%   |
| Intel Audio device                                                         | 1        | 1.37%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 1.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 1.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 1.37%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 1.37%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 1        | 1.37%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                 | 1        | 1.37%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 1        | 1.37%   |
| C-Media Electronics CM108 Audio Controller                                 | 1        | 1.37%   |
| BEHRINGER International UMC202HD 192k                                      | 1        | 1.37%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 1.37%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]          | 1        | 1.37%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1        | 1.37%   |
| AMD Kabini HDMI/DP Audio                                                   | 1        | 1.37%   |
| AMD FCH Azalia Controller                                                  | 1        | 1.37%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 1.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 5        | 21.74%  |
| G.Skill             | 4        | 17.39%  |
| Crucial             | 4        | 17.39%  |
| Unknown             | 2        | 8.7%    |
| Corsair             | 2        | 8.7%    |
| Team                | 1        | 4.35%   |
| Samsung Electronics | 1        | 4.35%   |
| Patriot             | 1        | 4.35%   |
| Micron Technology   | 1        | 4.35%   |
| GeIL                | 1        | 4.35%   |
| Elpida              | 1        | 4.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Kingston RAM KHX3600C18D4/32GX 32GB DIMM DDR4 3600MT/s     | 2        | 8.33%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s               | 1        | 4.17%   |
| Unknown RAM 992124 (997124) 8GB DIMM DDR3 1600MT/s         | 1        | 4.17%   |
| Team RAM TEAMGROUP-UD4-2400 8192MB DIMM DDR4 3007MT/s      | 1        | 4.17%   |
| Samsung RAM M471B5673FH0-CH9 2GB DIMM DDR3 4199MT/s        | 1        | 4.17%   |
| Patriot RAM PSD48G266681 8192MB DIMM DDR4 2934MT/s         | 1        | 4.17%   |
| Micron RAM 16JTF1G64AZ-1G6D1 8GB DIMM DDR3 1600MT/s        | 1        | 4.17%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s     | 1        | 4.17%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s          | 1        | 4.17%   |
| Kingston RAM 99U5474-016.A00LF 4096MB DIMM DDR3 1333MT/s   | 1        | 4.17%   |
| Kingston RAM 9905474-012.A00LF 2048MB DIMM DDR3 1333MT/s   | 1        | 4.17%   |
| GeIL RAM CL11-11-11 D3-1600 4096MB DIMM DDR3 1600MT/s      | 1        | 4.17%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s        | 1        | 4.17%   |
| G.Skill RAM F4-3200C15-16GTZKY 16384MB DIMM DDR4 3200MT/s  | 1        | 4.17%   |
| G.Skill RAM F4-2666C19-16GIS 16384MB DIMM DDR4 2667MT/s    | 1        | 4.17%   |
| G.Skill RAM F4-2400C15-8GNT 8GB DIMM DDR4 2400MT/s         | 1        | 4.17%   |
| Elpida RAM EBE11UD8AJWA-6E-E 1024MB DIMM DDR2 667MT/s      | 1        | 4.17%   |
| Crucial RAM CT16G4DFRA266.C16FE 16384MB DIMM DDR4 2667MT/s | 1        | 4.17%   |
| Crucial RAM CT102464BD160B.M16 8GB DIMM DDR3 1600MT/s      | 1        | 4.17%   |
| Crucial RAM BLS16G4D32AESB.M16FE 16GB DIMM DDR4 3400MT/s   | 1        | 4.17%   |
| Crucial RAM BL32G32C16U4R.M16FB1 32GB DIMM DDR4 3200MT/s   | 1        | 4.17%   |
| Corsair RAM CMT64GX4M4E3200C16 16GB DIMM DDR4 3200MT/s     | 1        | 4.17%   |
| Corsair RAM CMK16GX4M1E3200C16 16384MB DIMM DDR4 3000MT/s  | 1        | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 14       | 70%     |
| DDR3  | 4        | 20%     |
| SDRAM | 1        | 5%      |
| DDR2  | 1        | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 20       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 8        | 36.36%  |
| 8192  | 7        | 31.82%  |
| 32768 | 3        | 13.64%  |
| 2048  | 2        | 9.09%   |
| 4096  | 1        | 4.55%   |
| 1024  | 1        | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 4        | 18.18%  |
| 3600  | 3        | 13.64%  |
| 1600  | 3        | 13.64%  |
| 2667  | 2        | 9.09%   |
| 4199  | 1        | 4.55%   |
| 3400  | 1        | 4.55%   |
| 3007  | 1        | 4.55%   |
| 3000  | 1        | 4.55%   |
| 2934  | 1        | 4.55%   |
| 2933  | 1        | 4.55%   |
| 2400  | 1        | 4.55%   |
| 1333  | 1        | 4.55%   |
| 800   | 1        | 4.55%   |
| 667   | 1        | 4.55%   |

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
| Logitech                | 6        | 66.67%  |
| Z-Star Microelectronics | 1        | 11.11%  |
| Creative Technology     | 1        | 11.11%  |
| Chicony Electronics     | 1        | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech Webcam C270          | 2        | 22.22%  |
| Logitech B525 HD Webcam       | 2        | 22.22%  |
| Z-Star Venus USB2.0 Camera    | 1        | 11.11%  |
| Logitech Webcam C250          | 1        | 11.11%  |
| Logitech HD Pro Webcam C920   | 1        | 11.11%  |
| Creative Live! Cam Sync 1080p | 1        | 11.11%  |
| Chicony HP Webcam             | 1        | 11.11%  |

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
| 0     | 33       | 89.19%  |
| 1     | 4        | 10.81%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 2        | 50%     |
| Net/wireless  | 1        | 25%     |
| Bluetooth     | 1        | 25%     |

