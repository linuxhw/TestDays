openSUSE Leap-15.3 - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for openSUSE Leap-15.3.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/openSUSE_Leap-15.3/Desktop/README.md) and [notebooks](/Dist/openSUSE_Leap-15.3/Notebook/README.md).

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

| Vendor     | Model                       | Form-Factor | Probe                                                      | Date         |
|------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock     | Z68 Extreme4 Gen3           | Desktop     | [00a3ad4abc](https://linux-hardware.org/?probe=00a3ad4abc) | Dec 02, 2021 |
| ASRock     | Z68 Extreme4 Gen3           | Desktop     | [e75c56906a](https://linux-hardware.org/?probe=e75c56906a) | Dec 01, 2021 |
| HUAWEI     | KLVL-WXX9                   | Notebook    | [34898be259](https://linux-hardware.org/?probe=34898be259) | Nov 28, 2021 |
| Lenovo     | ThinkPad T490s 20NYS1XK0... | Notebook    | [aef7318ff6](https://linux-hardware.org/?probe=aef7318ff6) | Nov 27, 2021 |
| Acer       | Aspire E1-772G              | Notebook    | [d49a3f3160](https://linux-hardware.org/?probe=d49a3f3160) | Nov 26, 2021 |
| ASUSTek    | CROSSHAIR VI HERO           | Desktop     | [a2761e06a4](https://linux-hardware.org/?probe=a2761e06a4) | Nov 24, 2021 |
| ASUSTek    | CROSSHAIR VI HERO           | Desktop     | [5bfec76970](https://linux-hardware.org/?probe=5bfec76970) | Nov 24, 2021 |
| Lenovo     | G50-45 80E3                 | Notebook    | [43f110e082](https://linux-hardware.org/?probe=43f110e082) | Nov 20, 2021 |
| Dell       | 03015M A09                  | Server      | [c685a0033b](https://linux-hardware.org/?probe=c685a0033b) | Nov 17, 2021 |
| MSI        | H510I PRO WIFI              | Desktop     | [d50547de1f](https://linux-hardware.org/?probe=d50547de1f) | Nov 15, 2021 |
| ASRock     | N68C-GS4 FX                 | Desktop     | [c863f2ca43](https://linux-hardware.org/?probe=c863f2ca43) | Nov 14, 2021 |
| Fujitsu    | D3220-A1 S26361-D3220-A1    | Desktop     | [7d1fd58f75](https://linux-hardware.org/?probe=7d1fd58f75) | Nov 14, 2021 |
| HP         | 844C                        | Desktop     | [2d709598d7](https://linux-hardware.org/?probe=2d709598d7) | Nov 12, 2021 |
| ASUSTek    | M4A78T-E                    | Desktop     | [10991ab539](https://linux-hardware.org/?probe=10991ab539) | Nov 10, 2021 |
| Acer       | Aspire E1-772G              | Notebook    | [ec97cd08d4](https://linux-hardware.org/?probe=ec97cd08d4) | Nov 09, 2021 |
| Acer       | Aspire E1-772G              | Notebook    | [be0c106296](https://linux-hardware.org/?probe=be0c106296) | Nov 09, 2021 |
| Lenovo     | IdeaPad 330-15IKB 81DC      | Notebook    | [9a632ea5d1](https://linux-hardware.org/?probe=9a632ea5d1) | Nov 08, 2021 |
| Acer       | Aspire 5820TG               | Notebook    | [d8ae1a4109](https://linux-hardware.org/?probe=d8ae1a4109) | Nov 03, 2021 |
| Acer       | Aspire 5820TG               | Notebook    | [c79617751e](https://linux-hardware.org/?probe=c79617751e) | Nov 03, 2021 |
| Dell       | 0M859N A00                  | Desktop     | [aadca45789](https://linux-hardware.org/?probe=aadca45789) | Nov 01, 2021 |
| Acer       | Aspire E1-772G              | Notebook    | [2ffccc532e](https://linux-hardware.org/?probe=2ffccc532e) | Oct 24, 2021 |
| Acer       | Nitro AN515-54              | Notebook    | [b6be115eec](https://linux-hardware.org/?probe=b6be115eec) | Oct 23, 2021 |
| Acer       | Aspire 5560                 | Notebook    | [39fd26f895](https://linux-hardware.org/?probe=39fd26f895) | Oct 22, 2021 |
| TUXEDO     | Aura 15 Gen1                | Notebook    | [627c62ae00](https://linux-hardware.org/?probe=627c62ae00) | Oct 21, 2021 |
| Dell       | 0Y2YM6 A00                  | Desktop     | [d9a12dc22c](https://linux-hardware.org/?probe=d9a12dc22c) | Oct 19, 2021 |
| Dell       | 0Y2YM6 A00                  | Desktop     | [34a55551e2](https://linux-hardware.org/?probe=34a55551e2) | Oct 19, 2021 |
| Medion     | E6436 MD61150               | Notebook    | [1edd4700fd](https://linux-hardware.org/?probe=1edd4700fd) | Oct 17, 2021 |
| Medion     | E6436 MD61150               | Notebook    | [2eaa34b93e](https://linux-hardware.org/?probe=2eaa34b93e) | Oct 17, 2021 |
| HP         | Laptop 15s-eq0xxx           | Notebook    | [fc4da04b79](https://linux-hardware.org/?probe=fc4da04b79) | Oct 16, 2021 |
| HP         | Laptop 17-ca1xxx            | Notebook    | [ae1811a242](https://linux-hardware.org/?probe=ae1811a242) | Oct 13, 2021 |
| Lenovo     | ThinkPad T490s 20NYS1XK0... | Notebook    | [d3700d8667](https://linux-hardware.org/?probe=d3700d8667) | Oct 13, 2021 |
| Lenovo     | ThinkPad L15 Gen 1 20U4S... | Notebook    | [3bb6121afa](https://linux-hardware.org/?probe=3bb6121afa) | Oct 13, 2021 |
| Lenovo     | ThinkPad X1 Carbon Gen 9... | Notebook    | [f3c6229102](https://linux-hardware.org/?probe=f3c6229102) | Oct 06, 2021 |
| Lenovo     | 364A SDK0J40700 WIN 3258... | Desktop     | [ce4776505f](https://linux-hardware.org/?probe=ce4776505f) | Oct 03, 2021 |
| MSI        | B450M MORTAR MAX            | Desktop     | [556c37ba9b](https://linux-hardware.org/?probe=556c37ba9b) | Oct 03, 2021 |
| MSI        | B450M PRO-VDH MAX           | Desktop     | [ad69186227](https://linux-hardware.org/?probe=ad69186227) | Oct 02, 2021 |
| ASRock     | Z68 Extreme4 Gen3           | Desktop     | [3cec37b610](https://linux-hardware.org/?probe=3cec37b610) | Oct 02, 2021 |
| MSI        | B450M PRO-VDH MAX           | Desktop     | [540dca7da7](https://linux-hardware.org/?probe=540dca7da7) | Oct 02, 2021 |
| Lenovo     | ThinkPad T550 20CJS1VD01    | Notebook    | [390b9a8a74](https://linux-hardware.org/?probe=390b9a8a74) | Oct 01, 2021 |
| MSI        | GP63 Leopard 8RD            | Notebook    | [21189bb3e0](https://linux-hardware.org/?probe=21189bb3e0) | Oct 01, 2021 |
| ASUSTek    | M4A78T-E                    | Desktop     | [01ec64f498](https://linux-hardware.org/?probe=01ec64f498) | Sep 24, 2021 |
| Lenovo     | 364A SDK0J40700 WIN 3258... | Desktop     | [58f9ca6247](https://linux-hardware.org/?probe=58f9ca6247) | Sep 22, 2021 |
| Lenovo     | 364A SDK0J40700 WIN 3258... | Desktop     | [db9ccd461b](https://linux-hardware.org/?probe=db9ccd461b) | Sep 22, 2021 |
| Dell       | Precision M6700             | Notebook    | [0d8cf3bf1c](https://linux-hardware.org/?probe=0d8cf3bf1c) | Sep 21, 2021 |
| VS Company | G31T-M                      | Desktop     | [ed8bb8c0d1](https://linux-hardware.org/?probe=ed8bb8c0d1) | Sep 21, 2021 |
| ASUSTek    | AM1M-A/BR                   | Desktop     | [c586c22b15](https://linux-hardware.org/?probe=c586c22b15) | Sep 20, 2021 |
| Alienware  | 0PGRP5 A02                  | Desktop     | [65615a3aaa](https://linux-hardware.org/?probe=65615a3aaa) | Sep 16, 2021 |
| Alienware  | 0PGRP5 A02                  | Desktop     | [158a015f26](https://linux-hardware.org/?probe=158a015f26) | Sep 15, 2021 |
| MSI        | X370 GAMING PRO             | Desktop     | [629a45e23d](https://linux-hardware.org/?probe=629a45e23d) | Sep 12, 2021 |
| HP         | 8056                        | Desktop     | [3cab8505c4](https://linux-hardware.org/?probe=3cab8505c4) | Sep 06, 2021 |
| Intel      | DG41WV AAE90316-104         | Desktop     | [27c162218f](https://linux-hardware.org/?probe=27c162218f) | Sep 05, 2021 |
| Gigabyte   | B550 AORUS PRO AC           | Desktop     | [be3b65a81d](https://linux-hardware.org/?probe=be3b65a81d) | Aug 29, 2021 |
| Lenovo     | ThinkPad X1 Carbon 4th 2... | Notebook    | [44d0412dd3](https://linux-hardware.org/?probe=44d0412dd3) | Aug 27, 2021 |
| Samsung    | 600B4B/600B5B               | Notebook    | [200275bbd6](https://linux-hardware.org/?probe=200275bbd6) | Aug 27, 2021 |
| ASRock     | B450M Pro4                  | Desktop     | [a13b05f65f](https://linux-hardware.org/?probe=a13b05f65f) | Aug 27, 2021 |
| Dell       | Precision M6700             | Notebook    | [191db00b83](https://linux-hardware.org/?probe=191db00b83) | Aug 26, 2021 |
| Lenovo     | V330-15IKB 81AX             | Notebook    | [4b5a1af4dd](https://linux-hardware.org/?probe=4b5a1af4dd) | Aug 26, 2021 |
| Lenovo     | G500 20236                  | Notebook    | [73a5085a79](https://linux-hardware.org/?probe=73a5085a79) | Aug 24, 2021 |
| Dell       | Latitude 5480               | Notebook    | [a2110d9601](https://linux-hardware.org/?probe=a2110d9601) | Aug 24, 2021 |
| Dell       | Latitude 5480               | Notebook    | [64e1f3e16c](https://linux-hardware.org/?probe=64e1f3e16c) | Aug 19, 2021 |
| Lenovo     | ThinkPad T61 8895W9U        | Notebook    | [424c5f3e75](https://linux-hardware.org/?probe=424c5f3e75) | Aug 19, 2021 |
| Dell       | Inspiron 3521               | Notebook    | [c68ce33d52](https://linux-hardware.org/?probe=c68ce33d52) | Aug 11, 2021 |
| Dell       | Inspiron 3521               | Notebook    | [9a422a10d3](https://linux-hardware.org/?probe=9a422a10d3) | Aug 11, 2021 |
| Dell       | Inspiron 7460               | Notebook    | [f954aa3826](https://linux-hardware.org/?probe=f954aa3826) | Aug 10, 2021 |
| Samsung    | 600B4B/600B5B               | Notebook    | [0a650b495e](https://linux-hardware.org/?probe=0a650b495e) | Aug 09, 2021 |
| Lenovo     | ThinkPad T460 20FMS75800    | Notebook    | [1a1c3f469d](https://linux-hardware.org/?probe=1a1c3f469d) | Aug 07, 2021 |
| Lenovo     | ThinkPad X1 Carbon 4th 2... | Notebook    | [5953bc46ad](https://linux-hardware.org/?probe=5953bc46ad) | Aug 06, 2021 |
| Lenovo     | ThinkPad X1 Carbon 4th 2... | Notebook    | [fafaeed466](https://linux-hardware.org/?probe=fafaeed466) | Aug 06, 2021 |
| ASUSTek    | PRIME H310M-A               | Desktop     | [a22aa3c48c](https://linux-hardware.org/?probe=a22aa3c48c) | Aug 01, 2021 |
| MSI        | B85M-E45                    | Desktop     | [0e20d4cea9](https://linux-hardware.org/?probe=0e20d4cea9) | Jul 30, 2021 |
| Gigabyte   | B250M-DS3H-CF               | Desktop     | [acbcbe74d7](https://linux-hardware.org/?probe=acbcbe74d7) | Jul 22, 2021 |
| HP         | Stream Notebook PC 11       | Notebook    | [a612aa5d15](https://linux-hardware.org/?probe=a612aa5d15) | Jul 20, 2021 |
| HP         | 8433 11                     | Desktop     | [b079ccb608](https://linux-hardware.org/?probe=b079ccb608) | Jul 15, 2021 |
| MSI        | D2415 S26361-D2415-A21      | Desktop     | [b49400f636](https://linux-hardware.org/?probe=b49400f636) | Jul 11, 2021 |
| Lenovo     | ThinkPad T450s 20BWA06J0... | Notebook    | [e4cd39ef75](https://linux-hardware.org/?probe=e4cd39ef75) | Jul 09, 2021 |
| Lenovo     | ThinkPad T450s 20BWA06J0... | Notebook    | [5565f4e4fe](https://linux-hardware.org/?probe=5565f4e4fe) | Jul 09, 2021 |
| Fujitsu    | LIFEBOOK E754               | Notebook    | [e7923c27f1](https://linux-hardware.org/?probe=e7923c27f1) | Jul 08, 2021 |
| MSI        | B350 TOMAHAWK               | Desktop     | [27a6ac997b](https://linux-hardware.org/?probe=27a6ac997b) | Jul 03, 2021 |
| ASRock     | X570M Pro4                  | Desktop     | [a00aea4331](https://linux-hardware.org/?probe=a00aea4331) | Jul 03, 2021 |
| HP         | 0A68h                       | Desktop     | [36cfa6a366](https://linux-hardware.org/?probe=36cfa6a366) | Jun 27, 2021 |
| ASUSTek    | TUF B450-PRO GAMING         | Desktop     | [dfc2f82575](https://linux-hardware.org/?probe=dfc2f82575) | Jun 26, 2021 |
| ASUSTek    | G771JW                      | Notebook    | [8e6c4ddee8](https://linux-hardware.org/?probe=8e6c4ddee8) | Jun 24, 2021 |
| ASRock     | X570 Steel Legend           | Desktop     | [b4a11b3e4e](https://linux-hardware.org/?probe=b4a11b3e4e) | Jun 17, 2021 |
| MSI        | MEG X570 GODLIKE            | Desktop     | [11b7f0e8ae](https://linux-hardware.org/?probe=11b7f0e8ae) | Jun 17, 2021 |
| HP         | ZBook 17 G2                 | Notebook    | [3342d4d378](https://linux-hardware.org/?probe=3342d4d378) | Jun 17, 2021 |
| HP         | OMEN by HP Laptop 15-dc1... | Notebook    | [0c01b21401](https://linux-hardware.org/?probe=0c01b21401) | Jun 15, 2021 |
| Sony       | VPCSB15GB                   | Notebook    | [43a9d38ca0](https://linux-hardware.org/?probe=43a9d38ca0) | Jun 03, 2021 |
| HP         | 2AA2                        | Desktop     | [65e7cd2d3e](https://linux-hardware.org/?probe=65e7cd2d3e) | Jun 02, 2021 |
| Sony       | VGN-Z570AN                  | Notebook    | [13d58b8d90](https://linux-hardware.org/?probe=13d58b8d90) | May 21, 2021 |
| Sony       | VGN-Z570AN                  | Notebook    | [e6c7882e05](https://linux-hardware.org/?probe=e6c7882e05) | May 21, 2021 |
| MSI        | GS60 6QE                    | Notebook    | [93c6fd8911](https://linux-hardware.org/?probe=93c6fd8911) | May 18, 2021 |
| MSI        | GS60 6QE                    | Notebook    | [41fe777475](https://linux-hardware.org/?probe=41fe777475) | May 18, 2021 |
| ASUSTek    | VivoBook 12_ASUS Laptop ... | Notebook    | [184bedf2fd](https://linux-hardware.org/?probe=184bedf2fd) | May 01, 2021 |
| HP         | Pavilion dx6500             | Notebook    | [091cc2c616](https://linux-hardware.org/?probe=091cc2c616) | Apr 13, 2021 |
| HP         | Pavilion dx6500             | Notebook    | [6ad0d5c87f](https://linux-hardware.org/?probe=6ad0d5c87f) | Apr 13, 2021 |
| Dell       | Inspiron 15 7000 Gaming     | Notebook    | [97a7246099](https://linux-hardware.org/?probe=97a7246099) | Mar 01, 2021 |
| Dell       | Inspiron 15 7000 Gaming     | Notebook    | [b1e186207c](https://linux-hardware.org/?probe=b1e186207c) | Feb 28, 2021 |
| ASUSTek    | P8H61-M LE/USB3             | Desktop     | [fca0fd3336](https://linux-hardware.org/?probe=fca0fd3336) | Jan 03, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 5.3.18-59.27-default                | 13        | 17.81%  |
| 5.3.18-59.19-default                | 13        | 17.81%  |
| 5.3.18-57-default                   | 8         | 10.96%  |
| 5.3.18-59.5-default                 | 6         | 8.22%   |
| 5.3.18-59.24-default                | 6         | 8.22%   |
| 5.3.18-59.16-default                | 6         | 8.22%   |
| 5.3.18-59.10-default                | 5         | 6.85%   |
| 5.3.18-59.34-default                | 3         | 4.11%   |
| 5.3.18-59.19-preempt                | 2         | 2.74%   |
| 5.3.18-59.13-default                | 2         | 2.74%   |
| 5.3.18-lp152.57-default             | 1         | 1.37%   |
| 5.3.18-59.34-preempt                | 1         | 1.37%   |
| 5.3.18-59.27-preempt                | 1         | 1.37%   |
| 5.3.18-59.24-preempt                | 1         | 1.37%   |
| 5.3.18-57-preempt                   | 1         | 1.37%   |
| 5.3.18-56-default                   | 1         | 1.37%   |
| 5.3.18-52-default                   | 1         | 1.37%   |
| 5.3.18-46-default                   | 1         | 1.37%   |
| 5.16.0-rc2-lp153.2.g696d453-default | 1         | 1.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.3.18  | 69        | 98.57%  |
| 5.16.0  | 1         | 1.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.3     | 69        | 98.57%  |
| 5.16    | 1         | 1.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 70        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 27        | 37.5%   |
| KDE        | 17        | 23.61%  |
| XFCE       | 8         | 11.11%  |
| GNOME      | 8         | 11.11%  |
| Unknown    | 8         | 11.11%  |
| X-Cinnamon | 3         | 4.17%   |
| MATE       | 1         | 1.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 57        | 80.28%  |
| Wayland | 9         | 12.68%  |
| Tty     | 5         | 7.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 40        | 57.14%  |
| LightDM | 16        | 22.86%  |
| SDDM    | 11        | 15.71%  |
| XDM     | 2         | 2.86%   |
| GDM     | 1         | 1.43%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 25        | 35.71%  |
| de_DE   | 15        | 21.43%  |
| POSIX   | 6         | 8.57%   |
| pt_BR   | 3         | 4.29%   |
| fr_FR   | 3         | 4.29%   |
| es_ES   | 3         | 4.29%   |
| ru_RU   | 2         | 2.86%   |
| en_GB   | 2         | 2.86%   |
| zh_CN   | 1         | 1.43%   |
| sv_SE   | 1         | 1.43%   |
| pt_PT   | 1         | 1.43%   |
| pl_PL   | 1         | 1.43%   |
| nl_BE   | 1         | 1.43%   |
| hu_HU   | 1         | 1.43%   |
| hr_HR   | 1         | 1.43%   |
| es_MX   | 1         | 1.43%   |
| en_AU   | 1         | 1.43%   |
| cs_CZ   | 1         | 1.43%   |
| Unknown | 1         | 1.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 42        | 60%     |
| EFI  | 28        | 40%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 48        | 68.57%  |
| Ext4    | 18        | 25.71%  |
| Xfs     | 3         | 4.29%   |
| Overlay | 1         | 1.43%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 36        | 50.7%   |
| GPT     | 32        | 45.07%  |
| MBR     | 3         | 4.23%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 65        | 91.55%  |
| Yes       | 6         | 8.45%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 50        | 71.43%  |
| Yes       | 20        | 28.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 12        | 17.14%  |
| Hewlett-Packard     | 11        | 15.71%  |
| MSI                 | 10        | 14.29%  |
| ASUSTek Computer    | 8         | 11.43%  |
| Dell                | 7         | 10%     |
| ASRock              | 5         | 7.14%   |
| Acer                | 4         | 5.71%   |
| Sony                | 2         | 2.86%   |
| Gigabyte Technology | 2         | 2.86%   |
| Fujitsu             | 2         | 2.86%   |
| VS Company          | 1         | 1.43%   |
| TUXEDO              | 1         | 1.43%   |
| Samsung Electronics | 1         | 1.43%   |
| Medion              | 1         | 1.43%   |
| Intel               | 1         | 1.43%   |
| HUAWEI              | 1         | 1.43%   |
| Alienware           | 1         | 1.43%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| VS Company G31T-M                            | 1         | 1.43%   |
| TUXEDO Aura 15 Gen1                          | 1         | 1.43%   |
| Sony VPCSB15GB                               | 1         | 1.43%   |
| Sony VGN-Z570AN                              | 1         | 1.43%   |
| Samsung 600B4B/600B5B                        | 1         | 1.43%   |
| MSI MS-7D16                                  | 1         | 1.43%   |
| MSI MS-7C34                                  | 1         | 1.43%   |
| MSI MS-7B89                                  | 1         | 1.43%   |
| MSI MS-7A38                                  | 1         | 1.43%   |
| MSI MS-7A34                                  | 1         | 1.43%   |
| MSI MS-7A33                                  | 1         | 1.43%   |
| MSI MS-7817                                  | 1         | 1.43%   |
| MSI GS60 6QE                                 | 1         | 1.43%   |
| MSI GP63 Leopard 8RD                         | 1         | 1.43%   |
| MSI ESPRIMO P1510                            | 1         | 1.43%   |
| Medion E6436 MD61150                         | 1         | 1.43%   |
| Lenovo V330-15IKB 81AX                       | 1         | 1.43%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW00A7TH   | 1         | 1.43%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB002UMC     | 1         | 1.43%   |
| Lenovo ThinkPad T61 8895W9U                  | 1         | 1.43%   |
| Lenovo ThinkPad T490s 20NYS1XK00             | 1         | 1.43%   |
| Lenovo ThinkPad T460 20FMS75800              | 1         | 1.43%   |
| Lenovo ThinkPad T450s 20BWA06J00             | 1         | 1.43%   |
| Lenovo ThinkPad L15 Gen 1 20U4S88000         | 1         | 1.43%   |
| Lenovo IdeaPad 330-15IKB 81DC                | 1         | 1.43%   |
| Lenovo IdeaCentre Y710 Cube-15ISH 90FL004WGE | 1         | 1.43%   |
| Lenovo G500 20236                            | 1         | 1.43%   |
| Lenovo G50-45 80E3                           | 1         | 1.43%   |
| Intel DG41WV AAE90316-104                    | 1         | 1.43%   |
| HUAWEI KLVL-WXX9                             | 1         | 1.43%   |
| HP ZBook 17 G2                               | 1         | 1.43%   |
| HP xw4400 Workstation                        | 1         | 1.43%   |
| HP Stream Notebook PC 11                     | 1         | 1.43%   |
| HP Pavilion Gaming Desktop 790-00xx          | 1         | 1.43%   |
| HP Pavilion Gaming Desktop 690-00xx          | 1         | 1.43%   |
| HP Pavilion dx6500                           | 1         | 1.43%   |
| HP OMEN by HP Laptop 15-dc1xxx               | 1         | 1.43%   |
| HP Laptop 17-ca1xxx                          | 1         | 1.43%   |
| HP Laptop 15s-eq0xxx                         | 1         | 1.43%   |
| HP EliteDesk 800 G2 DM 65W                   | 1         | 1.43%   |
| HP 200-5120br                                | 1         | 1.43%   |
| Gigabyte B550 AORUS PRO AC                   | 1         | 1.43%   |
| Gigabyte B250M-DS3H                          | 1         | 1.43%   |
| Fujitsu LIFEBOOK E754                        | 1         | 1.43%   |
| Fujitsu ESPRIMO P520                         | 1         | 1.43%   |
| Dell Vostro 3268                             | 1         | 1.43%   |
| Dell Precision M6700                         | 1         | 1.43%   |
| Dell PowerEdge T420                          | 1         | 1.43%   |
| Dell Latitude 5480                           | 1         | 1.43%   |
| Dell Inspiron 7460                           | 1         | 1.43%   |
| Dell Inspiron 3521                           | 1         | 1.43%   |
| Dell Inspiron 15 7000 Gaming                 | 1         | 1.43%   |
| ASUS VivoBook 12_ASUS Laptop E203MAS_E203MA  | 1         | 1.43%   |
| ASUS TUF B450-PRO GAMING                     | 1         | 1.43%   |
| ASUS PRIME H310M-A                           | 1         | 1.43%   |
| ASUS P8H61-M LE/USB3                         | 1         | 1.43%   |
| ASUS M4A78T-E                                | 1         | 1.43%   |
| ASUS G771JW                                  | 1         | 1.43%   |
| ASUS CROSSHAIR VI HERO                       | 1         | 1.43%   |
| ASUS All Series                              | 1         | 1.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 7         | 10%     |
| HP Pavilion         | 3         | 4.29%   |
| Dell Inspiron       | 3         | 4.29%   |
| Acer Aspire         | 3         | 4.29%   |
| HP Laptop           | 2         | 2.86%   |
| VS Company G31T-M   | 1         | 1.43%   |
| TUXEDO Aura         | 1         | 1.43%   |
| Sony VPCSB15GB      | 1         | 1.43%   |
| Sony VGN-Z570AN     | 1         | 1.43%   |
| Samsung 600B4B      | 1         | 1.43%   |
| MSI MS-7D16         | 1         | 1.43%   |
| MSI MS-7C34         | 1         | 1.43%   |
| MSI MS-7B89         | 1         | 1.43%   |
| MSI MS-7A38         | 1         | 1.43%   |
| MSI MS-7A34         | 1         | 1.43%   |
| MSI MS-7A33         | 1         | 1.43%   |
| MSI MS-7817         | 1         | 1.43%   |
| MSI GS60            | 1         | 1.43%   |
| MSI GP63            | 1         | 1.43%   |
| MSI ESPRIMO         | 1         | 1.43%   |
| Medion E6436        | 1         | 1.43%   |
| Lenovo V330-15IKB   | 1         | 1.43%   |
| Lenovo IdeaPad      | 1         | 1.43%   |
| Lenovo IdeaCentre   | 1         | 1.43%   |
| Lenovo G500         | 1         | 1.43%   |
| Lenovo G50-45       | 1         | 1.43%   |
| Intel DG41WV        | 1         | 1.43%   |
| HUAWEI KLVL-WXX9    | 1         | 1.43%   |
| HP ZBook            | 1         | 1.43%   |
| HP xw4400           | 1         | 1.43%   |
| HP Stream           | 1         | 1.43%   |
| HP OMEN             | 1         | 1.43%   |
| HP EliteDesk        | 1         | 1.43%   |
| HP 200-5120br       | 1         | 1.43%   |
| Gigabyte B550       | 1         | 1.43%   |
| Gigabyte B250M-DS3H | 1         | 1.43%   |
| Fujitsu LIFEBOOK    | 1         | 1.43%   |
| Fujitsu ESPRIMO     | 1         | 1.43%   |
| Dell Vostro         | 1         | 1.43%   |
| Dell Precision      | 1         | 1.43%   |
| Dell PowerEdge      | 1         | 1.43%   |
| Dell Latitude       | 1         | 1.43%   |
| ASUS VivoBook       | 1         | 1.43%   |
| ASUS TUF            | 1         | 1.43%   |
| ASUS PRIME          | 1         | 1.43%   |
| ASUS P8H61-M        | 1         | 1.43%   |
| ASUS M4A78T-E       | 1         | 1.43%   |
| ASUS G771JW         | 1         | 1.43%   |
| ASUS CROSSHAIR      | 1         | 1.43%   |
| ASUS All            | 1         | 1.43%   |
| ASRock Z68          | 1         | 1.43%   |
| ASRock X570M        | 1         | 1.43%   |
| ASRock X570         | 1         | 1.43%   |
| ASRock N68C-GS4     | 1         | 1.43%   |
| ASRock B450M        | 1         | 1.43%   |
| Alienware X51       | 1         | 1.43%   |
| Acer Nitro          | 1         | 1.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 16        | 22.86%  |
| 2020 | 10        | 14.29%  |
| 2018 | 10        | 14.29%  |
| 2019 | 7         | 10%     |
| 2010 | 6         | 8.57%   |
| 2016 | 5         | 7.14%   |
| 2011 | 4         | 5.71%   |
| 2017 | 2         | 2.86%   |
| 2015 | 2         | 2.86%   |
| 2014 | 2         | 2.86%   |
| 2013 | 2         | 2.86%   |
| 2009 | 2         | 2.86%   |
| 2012 | 1         | 1.43%   |
| 2007 | 1         | 1.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 37        | 52.86%  |
| Desktop  | 32        | 45.71%  |
| Server   | 1         | 1.43%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 63        | 90%     |
| Enabled  | 7         | 10%     |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 70        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 20        | 28.57%  |
| 8.01-16.0   | 12        | 17.14%  |
| 4.01-8.0    | 11        | 15.71%  |
| 3.01-4.0    | 10        | 14.29%  |
| 64.01-256.0 | 7         | 10%     |
| 32.01-64.0  | 6         | 8.57%   |
| 1.01-2.0    | 2         | 2.86%   |
| 24.01-32.0  | 1         | 1.43%   |
| 2.01-3.0    | 1         | 1.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 25        | 34.72%  |
| 2.01-3.0  | 19        | 26.39%  |
| 4.01-8.0  | 15        | 20.83%  |
| 3.01-4.0  | 9         | 12.5%   |
| 8.01-16.0 | 2         | 2.78%   |
| 0.51-1.0  | 2         | 2.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 32        | 45.71%  |
| 2      | 23        | 32.86%  |
| 3      | 8         | 11.43%  |
| 4      | 4         | 5.71%   |
| 6      | 2         | 2.86%   |
| 9      | 1         | 1.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 37        | 52.86%  |
| Yes       | 33        | 47.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 65        | 92.86%  |
| No        | 5         | 7.14%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 81.43%  |
| No        | 13        | 18.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 64.79%  |
| No        | 25        | 35.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Germany     | 16        | 22.86%  |
| USA         | 8         | 11.43%  |
| Brazil      | 7         | 10%     |
| Spain       | 3         | 4.29%   |
| Russia      | 3         | 4.29%   |
| Mexico      | 3         | 4.29%   |
| India       | 3         | 4.29%   |
| France      | 3         | 4.29%   |
| Nicaragua   | 2         | 2.86%   |
| Japan       | 2         | 2.86%   |
| Hungary     | 2         | 2.86%   |
| Czechia     | 2         | 2.86%   |
| Australia   | 2         | 2.86%   |
| Thailand    | 1         | 1.43%   |
| Sweden      | 1         | 1.43%   |
| Sudan       | 1         | 1.43%   |
| Slovakia    | 1         | 1.43%   |
| Romania     | 1         | 1.43%   |
| Portugal    | 1         | 1.43%   |
| Poland      | 1         | 1.43%   |
| Netherlands | 1         | 1.43%   |
| Luxembourg  | 1         | 1.43%   |
| Greece      | 1         | 1.43%   |
| Croatia     | 1         | 1.43%   |
| China       | 1         | 1.43%   |
| Canada      | 1         | 1.43%   |
| Belgium     | 1         | 1.43%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| SÃ£o Paulo            | 3         | 4.23%   |
| Tokyo                 | 2         | 2.82%   |
| Prague                | 2         | 2.82%   |
| Managua               | 2         | 2.82%   |
| Zagreb                | 1         | 1.41%   |
| Vijayawada            | 1         | 1.41%   |
| Vaennaesby            | 1         | 1.41%   |
| TrÃªs Lagoas          | 1         | 1.41%   |
| The Hague             | 1         | 1.41%   |
| Stupava               | 1         | 1.41%   |
| Stabroek              | 1         | 1.41%   |
| Sehnde                | 1         | 1.41%   |
| S??o Paulo            | 1         | 1.41%   |
| San Luis Potos?­ City | 1         | 1.41%   |
| Saint Albans          | 1         | 1.41%   |
| Rockville             | 1         | 1.41%   |
| Recife                | 1         | 1.41%   |
| Pringy                | 1         | 1.41%   |
| Petrozavodsk          | 1         | 1.41%   |
| Palanpur              | 1         | 1.41%   |
| Oregon                | 1         | 1.41%   |
| Nuremberg             | 1         | 1.41%   |
| Nordenham             | 1         | 1.41%   |
| Munich                | 1         | 1.41%   |
| Moscow                | 1         | 1.41%   |
| Monterrey             | 1         | 1.41%   |
| Moelan-sur-Mer        | 1         | 1.41%   |
| Miami                 | 1         | 1.41%   |
| Melbourne             | 1         | 1.41%   |
| McDonough             | 1         | 1.41%   |
| Mansfield             | 1         | 1.41%   |
| Madrid                | 1         | 1.41%   |
| Luxembourg            | 1         | 1.41%   |
| Lomonosov             | 1         | 1.41%   |
| Leiria                | 1         | 1.41%   |
| Le??n                 | 1         | 1.41%   |
| Koleczkowo            | 1         | 1.41%   |
| Khartoum              | 1         | 1.41%   |
| Kehl                  | 1         | 1.41%   |
| Kathu                 | 1         | 1.41%   |
| Isernhagen            | 1         | 1.41%   |
| Howick                | 1         | 1.41%   |
| Heinsberg             | 1         | 1.41%   |
| Hamelin               | 1         | 1.41%   |
| Halle                 | 1         | 1.41%   |
| Guangzhou             | 1         | 1.41%   |
| Gevelsberg            | 1         | 1.41%   |
| Gelnhausen            | 1         | 1.41%   |
| G?¶d?¶ll?‘            | 1         | 1.41%   |
| Federal Way           | 1         | 1.41%   |
| Esztergom             | 1         | 1.41%   |
| Dunkirk               | 1         | 1.41%   |
| Dornhan               | 1         | 1.41%   |
| Dahme                 | 1         | 1.41%   |
| Concarneau            | 1         | 1.41%   |
| Cologne               | 1         | 1.41%   |
| Chapec??              | 1         | 1.41%   |
| Cestona               | 1         | 1.41%   |
| Canc??n               | 1         | 1.41%   |
| Bucharest             | 1         | 1.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 24        | 34     | 19.83%  |
| Samsung Electronics | 19        | 28     | 15.7%   |
| Seagate             | 17        | 25     | 14.05%  |
| Kingston            | 10        | 10     | 8.26%   |
| SanDisk             | 7         | 8      | 5.79%   |
| Hitachi             | 6         | 8      | 4.96%   |
| Toshiba             | 4         | 5      | 3.31%   |
| HGST                | 4         | 4      | 3.31%   |
| A-DATA Technology   | 4         | 4      | 3.31%   |
| Unknown             | 3         | 3      | 2.48%   |
| Intel               | 3         | 3      | 2.48%   |
| Crucial             | 3         | 3      | 2.48%   |
| SK Hynix            | 2         | 2      | 1.65%   |
| Silicon Motion      | 2         | 2      | 1.65%   |
| Phison              | 2         | 2      | 1.65%   |
| Fujitsu             | 2         | 2      | 1.65%   |
| TO Exter            | 1         | 1      | 0.83%   |
| PLEXTOR             | 1         | 2      | 0.83%   |
| Micron Technology   | 1         | 1      | 0.83%   |
| LITEON              | 1         | 1      | 0.83%   |
| Lite-On             | 1         | 1      | 0.83%   |
| JMicron             | 1         | 1      | 0.83%   |
| Intenso             | 1         | 1      | 0.83%   |
| Inateck             | 1         | 1      | 0.83%   |
| HGST HTS            | 1         | 1      | 0.83%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB             | 3         | 2.27%   |
| Silicon Motion NVMe SSD Drive 512GB   | 2         | 1.52%   |
| Seagate ST3750528AS 752GB             | 2         | 1.52%   |
| Seagate ST2000DM006-2DM164 2TB        | 2         | 1.52%   |
| Seagate ST1000LM035-1RK172 1TB        | 2         | 1.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 1.52%   |
| Samsung SSD 860 EVO 250GB             | 2         | 1.52%   |
| Samsung SSD 850 EVO 500GB             | 2         | 1.52%   |
| HGST HTS721010A9E630 1TB              | 2         | 1.52%   |
| Fujitsu MHW2120BH 120GB               | 2         | 1.52%   |
| WDC WDS500G1X0E-00AFY0 500GB          | 1         | 0.76%   |
| WDC WDS500G1B0B-00AS40 500GB SSD      | 1         | 0.76%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 0.76%   |
| WDC WDS250G1B0C-00S6U0 250GB          | 1         | 0.76%   |
| WDC WDS100T3X0C-00SJG0 1TB            | 1         | 0.76%   |
| WDC WDS100T1X0E-00AFY0 1TB            | 1         | 0.76%   |
| WDC WD800BEVS-60RST0 80GB             | 1         | 0.76%   |
| WDC WD7500AALX-009BA0 752GB           | 1         | 0.76%   |
| WDC WD5000LPLX-66ZNTT1 500GB          | 1         | 0.76%   |
| WDC WD5000AAVS-00ZTB0 500GB           | 1         | 0.76%   |
| WDC WD5000AAKX-07U6AA0 500GB          | 1         | 0.76%   |
| WDC WD50 00LPCX-00VHAT0 500GB         | 1         | 0.76%   |
| WDC WD3200AAKS-00B3A0 320GB           | 1         | 0.76%   |
| WDC WD2500AAJS-00VTA0 250GB           | 1         | 0.76%   |
| WDC WD20EARX-00PASB0 2TB              | 1         | 0.76%   |
| WDC WD2005FBYZ-01YCBB2 2TB            | 1         | 0.76%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 0.76%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 0.76%   |
| WDC WD10SPZX-17Z10T0 1TB              | 1         | 0.76%   |
| WDC WD10EZEX-75WN4A0 1TB              | 1         | 0.76%   |
| WDC WD10EZEX-75M2NA0 1TB              | 1         | 0.76%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 0.76%   |
| WDC WD10EZEX-00KUWA0 1TB              | 1         | 0.76%   |
| WDC WD10EZEX-00BN5A0 1TB              | 1         | 0.76%   |
| WDC WD10EAVS-22D7B0 1TB               | 1         | 0.76%   |
| WDC WD10EACS-00D6B1 1TB               | 1         | 0.76%   |
| WDC WD1003FZEX-00K3CA0 1TB            | 1         | 0.76%   |
| WDC WD1001FALS-00E3A0 1TB             | 1         | 0.76%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB  | 1         | 0.76%   |
| Unknown USD00  256GB                  | 1         | 0.76%   |
| Unknown DA4064  64GB                  | 1         | 0.76%   |
| Unknown 128GB SATA FLASH DRIVE        | 1         | 0.76%   |
| Toshiba THNSNJ256G8NU 256GB SSD       | 1         | 0.76%   |
| Toshiba NVMe SSD Drive 256GB          | 1         | 0.76%   |
| Toshiba MQ01ABD075 752GB              | 1         | 0.76%   |
| Toshiba HDWD130 3TB                   | 1         | 0.76%   |
| TO Exter nal USB 3.0 1TB              | 1         | 0.76%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD | 1         | 0.76%   |
| SK Hynix HBG4e  32GB                  | 1         | 0.76%   |
| Seagate ST9320325AS 320GB             | 1         | 0.76%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 0.76%   |
| Seagate ST500LM000-SSHD-8GB           | 1         | 0.76%   |
| Seagate ST500LM0 12 HN-M500MBB 500GB  | 1         | 0.76%   |
| Seagate ST3750630AS 752GB             | 1         | 0.76%   |
| Seagate ST3160812AS 160GB             | 1         | 0.76%   |
| Seagate ST3000DM007-1WY10G 3TB        | 1         | 0.76%   |
| Seagate ST2000NM0023 2TB              | 1         | 0.76%   |
| Seagate ST2000DM001-1ER164 2TB        | 1         | 0.76%   |
| Seagate ST1000DM010-2EP102 1TB        | 1         | 0.76%   |
| Seagate ST1000DM003-1SB102 1TB        | 1         | 0.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 19        | 27     | 35.19%  |
| Seagate             | 17        | 25     | 31.48%  |
| Hitachi             | 6         | 8      | 11.11%  |
| HGST                | 4         | 4      | 7.41%   |
| Toshiba             | 2         | 3      | 3.7%    |
| Samsung Electronics | 2         | 5      | 3.7%    |
| Fujitsu             | 2         | 2      | 3.7%    |
| TO Exter            | 1         | 1      | 1.85%   |
| Inateck             | 1         | 1      | 1.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 14     | 21.95%  |
| Kingston            | 9         | 9      | 21.95%  |
| SanDisk             | 7         | 8      | 17.07%  |
| A-DATA Technology   | 4         | 4      | 9.76%   |
| WDC                 | 2         | 2      | 4.88%   |
| Intel               | 2         | 2      | 4.88%   |
| Crucial             | 2         | 2      | 4.88%   |
| Toshiba             | 1         | 1      | 2.44%   |
| SK Hynix            | 1         | 1      | 2.44%   |
| PLEXTOR             | 1         | 2      | 2.44%   |
| LITEON              | 1         | 1      | 2.44%   |
| JMicron             | 1         | 1      | 2.44%   |
| Intenso             | 1         | 1      | 2.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 42        | 76     | 39.62%  |
| SSD     | 38        | 48     | 35.85%  |
| NVMe    | 22        | 24     | 20.75%  |
| MMC     | 3         | 3      | 2.83%   |
| Unknown | 1         | 2      | 0.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 60        | 119    | 67.42%  |
| NVMe | 22        | 24     | 24.72%  |
| SAS  | 4         | 7      | 4.49%   |
| MMC  | 3         | 3      | 3.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 38        | 49     | 44.19%  |
| 0.01-0.5   | 37        | 56     | 43.02%  |
| 1.01-2.0   | 8         | 16     | 9.3%    |
| 2.01-3.0   | 2         | 2      | 2.33%   |
| 10.01-20.0 | 1         | 1      | 1.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1001-2000      | 17        | 23.61%  |
| More than 3000 | 14        | 19.44%  |
| 501-1000       | 12        | 16.67%  |
| 251-500        | 11        | 15.28%  |
| 2001-3000      | 11        | 15.28%  |
| 51-100         | 3         | 4.17%   |
| 1-20           | 2         | 2.78%   |
| 101-250        | 1         | 1.39%   |
| Unknown        | 1         | 1.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 51-100         | 15        | 20%     |
| 101-250        | 14        | 18.67%  |
| 251-500        | 13        | 17.33%  |
| 501-1000       | 10        | 13.33%  |
| 1001-2000      | 8         | 10.67%  |
| 1-20           | 7         | 9.33%   |
| 2001-3000      | 4         | 5.33%   |
| 21-50          | 2         | 2.67%   |
| More than 3000 | 1         | 1.33%   |
| Unknown        | 1         | 1.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500LM000-SSHD-8GB         | 1         | 1      | 16.67%  |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 16.67%  |
| Samsung Electronics SSD 970 EVO 1TB | 1         | 1      | 16.67%  |
| Phison 311CD0512GB                  | 1         | 1      | 16.67%  |
| Kingston SV300S37A120G 120GB SSD    | 1         | 1      | 16.67%  |
| Crucial CT1000P1SSD8 1TB            | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 33.33%  |
| Samsung Electronics | 1         | 1      | 16.67%  |
| Phison              | 1         | 1      | 16.67%  |
| Kingston            | 1         | 1      | 16.67%  |
| Crucial             | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 3         | 3      | 50%     |
| HDD  | 2         | 2      | 33.33%  |
| SSD  | 1         | 1      | 16.67%  |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 39        | 84     | 52%     |
| Works    | 30        | 63     | 40%     |
| Malfunc  | 6         | 6      | 8%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 45        | 50%     |
| AMD                          | 17        | 18.89%  |
| Samsung Electronics          | 8         | 8.89%   |
| Sandisk                      | 5         | 5.56%   |
| Silicon Motion               | 2         | 2.22%   |
| Phison Electronics           | 2         | 2.22%   |
| Lite-On Technology           | 2         | 2.22%   |
| Toshiba America Info Systems | 1         | 1.11%   |
| Silicon Image                | 1         | 1.11%   |
| Nvidia                       | 1         | 1.11%   |
| Micron/Crucial Technology    | 1         | 1.11%   |
| Micron Technology            | 1         | 1.11%   |
| Marvell Technology Group     | 1         | 1.11%   |
| Kingston Technology Company  | 1         | 1.11%   |
| Broadcom / LSI               | 1         | 1.11%   |
| ASMedia Technology           | 1         | 1.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 14        | 13.46%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 6         | 5.77%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6         | 5.77%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4         | 3.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 2.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 2.88%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2         | 1.92%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                              | 2         | 1.92%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2         | 1.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 1.92%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 1.92%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 1.92%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 1.92%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 1.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 2         | 1.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 1.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 1.92%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 1.92%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 1.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2         | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 2         | 1.92%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2         | 1.92%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2         | 1.92%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 1         | 0.96%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1         | 0.96%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1         | 0.96%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1         | 0.96%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1         | 0.96%   |
| Phison E12 NVMe Controller                                                              | 1         | 0.96%   |
| Nvidia MCP61 SATA Controller                                                            | 1         | 0.96%   |
| Nvidia MCP61 IDE                                                                        | 1         | 0.96%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1         | 0.96%   |
| Micron Non-Volatile memory controller                                                   | 1         | 0.96%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                                 | 1         | 0.96%   |
| Lite-On SATA controller                                                                 | 1         | 0.96%   |
| Lite-On Non-Volatile memory controller                                                  | 1         | 0.96%   |
| Kingston Company A2000 NVMe SSD                                                         | 1         | 0.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1         | 0.96%   |
| Intel SSD 660P Series                                                                   | 1         | 0.96%   |
| Intel SATA Controller [RAID mode]                                                       | 1         | 0.96%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1         | 0.96%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1         | 0.96%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1         | 0.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1         | 0.96%   |
| Intel 82801GR/GDH (ICH7R/ICH7DH) SATA Controller [RAID mode]                            | 1         | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 0.96%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1         | 0.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1         | 0.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 1         | 0.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1         | 0.96%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                          | 1         | 0.96%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1         | 0.96%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 1         | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1         | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1         | 0.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 54        | 59.34%  |
| NVMe | 22        | 24.18%  |
| IDE  | 9         | 9.89%   |
| RAID | 6         | 6.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 49        | 70%     |
| AMD    | 21        | 30%     |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 4.29%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 2.86%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 2         | 2.86%   |
| AMD Ryzen 7 1700 Eight-Core Processor         | 2         | 2.86%   |
| Intel Xeon CPU E5-2470 v2 @ 2.40GHz           | 1         | 1.43%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 1         | 1.43%   |
| Intel Pentium CPU G3258 @ 3.20GHz             | 1         | 1.43%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.43%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 1         | 1.43%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.43%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.43%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.43%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 1         | 1.43%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 1.43%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 1.43%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 1.43%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 1         | 1.43%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 1.43%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 1.43%   |
| Intel Core i7 CPU 860 @ 2.80GHz               | 1         | 1.43%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 1.43%   |
| Intel Core i5-7600K CPU @ 3.80GHz             | 1         | 1.43%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 1         | 1.43%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 1         | 1.43%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 1.43%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 1         | 1.43%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 1         | 1.43%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 1.43%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 1.43%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.43%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.43%   |
| Intel Core i5-2400S CPU @ 2.50GHz             | 1         | 1.43%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 1         | 1.43%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.43%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 1.43%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 1         | 1.43%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 1.43%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 1.43%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 1         | 1.43%   |
| Intel Core 2 Quad CPU Q9300 @ 2.50GHz         | 1         | 1.43%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 1         | 1.43%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz          | 1         | 1.43%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 1         | 1.43%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 1         | 1.43%   |
| Intel Core 2 CPU 6400 @ 2.13GHz               | 1         | 1.43%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 1.43%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 1.43%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.43%   |
| AMD Sempron 2650 APU with Radeon R3           | 1         | 1.43%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 1         | 1.43%   |
| AMD Ryzen 9 3950X 16-Core Processor           | 1         | 1.43%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 1.43%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 1.43%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 1         | 1.43%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 1         | 1.43%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 1         | 1.43%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 1.43%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 1         | 1.43%   |
| AMD Ryzen 5 1600X Six-Core Processor          | 1         | 1.43%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 1         | 1.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 18        | 25.71%  |
| Intel Core i7           | 15        | 21.43%  |
| AMD Ryzen 7             | 7         | 10%     |
| Intel Core i3           | 4         | 5.71%   |
| Intel Core 2 Duo        | 4         | 5.71%   |
| AMD Ryzen 9             | 4         | 5.71%   |
| AMD Ryzen 5             | 4         | 5.71%   |
| Intel Celeron           | 2         | 2.86%   |
| AMD A6                  | 2         | 2.86%   |
| Other                   | 1         | 1.43%   |
| Intel Xeon              | 1         | 1.43%   |
| Intel Pentium Dual-Core | 1         | 1.43%   |
| Intel Pentium           | 1         | 1.43%   |
| Intel Core 2 Quad       | 1         | 1.43%   |
| Intel Core 2            | 1         | 1.43%   |
| AMD Sempron             | 1         | 1.43%   |
| AMD Ryzen 3             | 1         | 1.43%   |
| AMD Phenom II X4        | 1         | 1.43%   |
| AMD FX                  | 1         | 1.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 26        | 37.14%  |
| 4      | 25        | 35.71%  |
| 8      | 7         | 10%     |
| 6      | 7         | 10%     |
| 16     | 2         | 2.86%   |
| 12     | 2         | 2.86%   |
| 20     | 1         | 1.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 69        | 98.57%  |
| 2      | 1         | 1.43%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 47        | 67.14%  |
| 1      | 23        | 32.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 70        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 42.47%  |
| 0x806e9    | 3         | 4.11%   |
| 0x306c3    | 3         | 4.11%   |
| 0x206a7    | 3         | 4.11%   |
| 0x906ea    | 2         | 2.74%   |
| 0x906e9    | 2         | 2.74%   |
| 0x6fd      | 2         | 2.74%   |
| 0x406e3    | 2         | 2.74%   |
| 0x0a201009 | 2         | 2.74%   |
| 0x08600106 | 2         | 2.74%   |
| 0x08108109 | 2         | 2.74%   |
| 0x08001137 | 2         | 2.74%   |
| 0xa0653    | 1         | 1.37%   |
| 0x806ec    | 1         | 1.37%   |
| 0x806c1    | 1         | 1.37%   |
| 0x706a1    | 1         | 1.37%   |
| 0x506e3    | 1         | 1.37%   |
| 0x306e4    | 1         | 1.37%   |
| 0x306d4    | 1         | 1.37%   |
| 0x306a9    | 1         | 1.37%   |
| 0x30678    | 1         | 1.37%   |
| 0x1067a    | 1         | 1.37%   |
| 0x10677    | 1         | 1.37%   |
| 0x10676    | 1         | 1.37%   |
| 0x0a201016 | 1         | 1.37%   |
| 0x08701021 | 1         | 1.37%   |
| 0x0800820d | 1         | 1.37%   |
| 0x07030105 | 1         | 1.37%   |
| 0x010000db | 1         | 1.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 15        | 21.43%  |
| Haswell       | 7         | 10%     |
| Zen 2         | 5         | 7.14%   |
| Skylake       | 5         | 7.14%   |
| Zen+          | 4         | 5.71%   |
| Zen           | 4         | 5.71%   |
| SandyBridge   | 4         | 5.71%   |
| Penryn        | 4         | 5.71%   |
| IvyBridge     | 4         | 5.71%   |
| Zen 3         | 3         | 4.29%   |
| Core          | 3         | 4.29%   |
| Westmere      | 1         | 1.43%   |
| TigerLake     | 1         | 1.43%   |
| Silvermont    | 1         | 1.43%   |
| Puma          | 1         | 1.43%   |
| Piledriver    | 1         | 1.43%   |
| Nehalem       | 1         | 1.43%   |
| K10 Llano     | 1         | 1.43%   |
| K10           | 1         | 1.43%   |
| Jaguar        | 1         | 1.43%   |
| Goldmont plus | 1         | 1.43%   |
| CometLake     | 1         | 1.43%   |
| Broadwell     | 1         | 1.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 41        | 46.59%  |
| Nvidia | 26        | 29.55%  |
| AMD    | 21        | 23.86%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                 | 4         | 4.44%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 4         | 4.44%   |
| Intel HD Graphics 630                                                                 | 3         | 3.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 3         | 3.33%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 3         | 3.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 3         | 3.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 3         | 3.33%   |
| Nvidia TU117 [GeForce GTX 1650]                                                       | 2         | 2.22%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 2         | 2.22%   |
| Nvidia GA102 [GeForce RTX 3090]                                                       | 2         | 2.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 2         | 2.22%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 2.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 2         | 2.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 2         | 2.22%   |
| Intel HD Graphics 530                                                                 | 2         | 2.22%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                 | 2         | 2.22%   |
| AMD Tonga PRO [Radeon R9 285/380]                                                     | 2         | 2.22%   |
| AMD Renoir                                                                            | 2         | 2.22%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 2         | 2.22%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 1.11%   |
| Nvidia TU116 [GeForce GTX 1660]                                                       | 1         | 1.11%   |
| Nvidia TU106 [GeForce RTX 2070]                                                       | 1         | 1.11%   |
| Nvidia GT216 [GeForce GT 220]                                                         | 1         | 1.11%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                           | 1         | 1.11%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                    | 1         | 1.11%   |
| Nvidia GP104 [GeForce GTX 1070]                                                       | 1         | 1.11%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                    | 1         | 1.11%   |
| Nvidia GM206 [GeForce GTX 960]                                                        | 1         | 1.11%   |
| Nvidia GM204M [GeForce GTX 980M]                                                      | 1         | 1.11%   |
| Nvidia GM204M [GeForce GTX 970M]                                                      | 1         | 1.11%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 1         | 1.11%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 1         | 1.11%   |
| Nvidia GK107 [GeForce GTX 650]                                                        | 1         | 1.11%   |
| Nvidia GK104GLM [Quadro K3000M]                                                       | 1         | 1.11%   |
| Nvidia GF119 [GeForce GT 520]                                                         | 1         | 1.11%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 1         | 1.11%   |
| Nvidia GF100GL [Tesla C2050 / C2070]                                                  | 1         | 1.11%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                                    | 1         | 1.11%   |
| Nvidia G98M [GeForce 9300M GS]                                                        | 1         | 1.11%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 1         | 1.11%   |
| Intel UHD Graphics 620                                                                | 1         | 1.11%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 1         | 1.11%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 1.11%   |
| Intel HD Graphics 5500                                                                | 1         | 1.11%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 1         | 1.11%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 1.11%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 1         | 1.11%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                              | 1         | 1.11%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 1         | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 1         | 1.11%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.11%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 1         | 1.11%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                                   | 1         | 1.11%   |
| AMD Sumo [Radeon HD 6520G]                                                            | 1         | 1.11%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 1         | 1.11%   |
| AMD RV610 [Radeon HD 2400 PRO]                                                        | 1         | 1.11%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                             | 1         | 1.11%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 1         | 1.11%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                              | 1         | 1.11%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                            | 1         | 1.11%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 24        | 34.29%  |
| 1 x AMD        | 16        | 22.86%  |
| 1 x Nvidia     | 15        | 21.43%  |
| Intel + Nvidia | 10        | 14.29%  |
| Intel + AMD    | 5         | 7.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 56        | 80%     |
| Proprietary | 13        | 18.57%  |
| Unknown     | 1         | 1.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 48        | 66.67%  |
| 3.01-4.0   | 4         | 5.56%   |
| 1.01-2.0   | 4         | 5.56%   |
| 0.01-0.5   | 4         | 5.56%   |
| 7.01-8.0   | 3         | 4.17%   |
| 0.51-1.0   | 3         | 4.17%   |
| 5.01-6.0   | 2         | 2.78%   |
| 16.01-24.0 | 2         | 2.78%   |
| 8.01-16.0  | 2         | 2.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Chimei Innolux       | 11        | 13.41%  |
| LG Display           | 10        | 12.2%   |
| Goldstar             | 9         | 10.98%  |
| Samsung Electronics  | 8         | 9.76%   |
| Dell                 | 7         | 8.54%   |
| AU Optronics         | 7         | 8.54%   |
| Hewlett-Packard      | 4         | 4.88%   |
| Philips              | 3         | 3.66%   |
| BenQ                 | 3         | 3.66%   |
| Acer                 | 3         | 3.66%   |
| LG Electronics       | 2         | 2.44%   |
| Lenovo               | 2         | 2.44%   |
| Ancor Communications | 2         | 2.44%   |
| ViewSonic            | 1         | 1.22%   |
| TCL                  | 1         | 1.22%   |
| Sony                 | 1         | 1.22%   |
| LG Philips           | 1         | 1.22%   |
| InfoVision           | 1         | 1.22%   |
| Iiyama               | 1         | 1.22%   |
| Denver               | 1         | 1.22%   |
| CSO                  | 1         | 1.22%   |
| BOE                  | 1         | 1.22%   |
| ASUSTek Computer     | 1         | 1.22%   |
| AOC                  | 1         | 1.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Hewlett-Packard LV1911 HWP3005 1366x768 410x230mm 18.5-inch           | 2         | 2.35%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch             | 1         | 1.18%   |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                      | 1         | 1.18%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch  | 1         | 1.18%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1         | 1.18%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1         | 1.18%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 477x268mm 21.5-inch  | 1         | 1.18%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 1         | 1.18%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch     | 1         | 1.18%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 1         | 1.18%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch     | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SEC3449 1366x768 309x174mm 14.0-inch  | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SDC424B 3840x2160 344x194mm 15.5-inch | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch | 1         | 1.18%   |
| Philips PHL 258B6QU PHL08F5 2560x1440 553x311mm 25.0-inch             | 1         | 1.18%   |
| Philips 150S PHL0812 1024x768 307x230mm 15.1-inch                     | 1         | 1.18%   |
| Philips 150S PHL0805 1024x768 307x230mm 15.1-inch                     | 1         | 1.18%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch           | 1         | 1.18%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 1         | 1.18%   |
| LG Electronics LCD Monitor LG TV SSCR 3840x2160                       | 1         | 1.18%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch          | 1         | 1.18%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch          | 1         | 1.18%   |
| LG Display LCD Monitor LGD053C 1920x1080 309x174mm 14.0-inch          | 1         | 1.18%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 1         | 1.18%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 1.18%   |
| LG Display LCD Monitor LGD04A9 1920x1080 309x174mm 14.0-inch          | 1         | 1.18%   |
| LG Display LCD Monitor LGD046C 1920x1080 380x210mm 17.1-inch          | 1         | 1.18%   |
| LG Display LCD Monitor LGD044F 1920x1080 350x190mm 15.7-inch          | 1         | 1.18%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 1         | 1.18%   |
| LG Display LCD Monitor LGD02DA 1920x1080 380x220mm 17.3-inch          | 1         | 1.18%   |
| Lenovo LEN P27q-10 LEN61A8 2560x1440 597x336mm 27.0-inch              | 1         | 1.18%   |
| Lenovo LCD Monitor LEN4020 1024x768 286x214mm 14.1-inch               | 1         | 1.18%   |
| InfoVision LCD Monitor IVO03F4 1920x1200 263x164mm 12.2-inch          | 1         | 1.18%   |
| Iiyama PL2492H IVM612F 1920x1080 530x300mm 24.0-inch                  | 1         | 1.18%   |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch          | 1         | 1.18%   |
| Hewlett-Packard 27es HWP3326 1920x1080 598x336mm 27.0-inch            | 1         | 1.18%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                  | 1         | 1.18%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch           | 1         | 1.18%   |
| Goldstar L1718S GSM443C 1280x1024 338x270mm 17.0-inch                 | 1         | 1.18%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 1         | 1.18%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1         | 1.18%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 1         | 1.18%   |
| Goldstar E2742 GSM58C9 1920x1080 598x337mm 27.0-inch                  | 1         | 1.18%   |
| Goldstar E2441 GSM581F 1920x1080 531x299mm 24.0-inch                  | 1         | 1.18%   |
| Goldstar 2D FHD LG TV GSM59C6 1920x1080 509x286mm 23.0-inch           | 1         | 1.18%   |
| Denver UWQHD-100-V2 LHC3500 3440x1440 798x342mm 34.2-inch             | 1         | 1.18%   |
| Dell UZ2315H DELF055 1920x1080 509x286mm 23.0-inch                    | 1         | 1.18%   |
| Dell U2711 DELA057 2560x1440 597x336mm 27.0-inch                      | 1         | 1.18%   |
| Dell U2410 DELF017 1920x1200 518x324mm 24.1-inch                      | 1         | 1.18%   |
| Dell S2216H DELD07A 1920x1080 476x268mm 21.5-inch                     | 1         | 1.18%   |
| Dell P2219H DELA114 1920x1080 476x267mm 21.5-inch                     | 1         | 1.18%   |
| Dell E228WFP DELD014 1680x1050 473x296mm 22.0-inch                    | 1         | 1.18%   |
| Dell 1703FP DEL3011 1280x1024 338x270mm 17.0-inch                     | 1         | 1.18%   |
| CSO LCD Monitor CSO1404 1920x1200 302x189mm 14.0-inch                 | 1         | 1.18%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 1         | 1.18%   |
| Chimei Innolux LCD Monitor CMN15F6 1920x1080 344x193mm 15.5-inch      | 1         | 1.18%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch      | 1         | 1.18%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 1         | 1.18%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 1         | 1.18%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch      | 1         | 1.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 32        | 43.24%  |
| 1366x768 (WXGA)    | 11        | 14.86%  |
| 3840x2160 (4K)     | 5         | 6.76%   |
| 2560x1440 (QHD)    | 5         | 6.76%   |
| 2560x1080          | 3         | 4.05%   |
| 1920x1200 (WUXGA)  | 3         | 4.05%   |
| 1600x900 (HD+)     | 3         | 4.05%   |
| 1024x768 (XGA)     | 3         | 4.05%   |
| 3440x1440          | 2         | 2.7%    |
| 1280x1024 (SXGA)   | 2         | 2.7%    |
| 640x480            | 1         | 1.35%   |
| 2160x1440          | 1         | 1.35%   |
| 1680x1050 (WSXGA+) | 1         | 1.35%   |
| 1440x900 (WXGA+)   | 1         | 1.35%   |
| 1280x800 (WXGA)    | 1         | 1.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 21        | 26.25%  |
| 27      | 8         | 10%     |
| 17      | 8         | 10%     |
| 14      | 8         | 10%     |
| 21      | 6         | 7.5%    |
| 34      | 4         | 5%      |
| 24      | 4         | 5%      |
| 23      | 3         | 3.75%   |
| 18      | 3         | 3.75%   |
| Unknown | 3         | 3.75%   |
| 13      | 2         | 2.5%    |
| 11      | 2         | 2.5%    |
| 84      | 1         | 1.25%   |
| 32      | 1         | 1.25%   |
| 31      | 1         | 1.25%   |
| 26      | 1         | 1.25%   |
| 25      | 1         | 1.25%   |
| 22      | 1         | 1.25%   |
| 20      | 1         | 1.25%   |
| 19      | 1         | 1.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 38.75%  |
| 501-600     | 15        | 18.75%  |
| 401-500     | 12        | 15%     |
| 351-400     | 6         | 7.5%    |
| 701-800     | 5         | 6.25%   |
| 201-300     | 4         | 5%      |
| 601-700     | 3         | 3.75%   |
| Unknown     | 3         | 3.75%   |
| 1501-2000   | 1         | 1.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 53        | 74.65%  |
| 16/10   | 5         | 7.04%   |
| 21/9    | 4         | 5.63%   |
| 4/3     | 3         | 4.23%   |
| Unknown | 3         | 4.23%   |
| 5/4     | 2         | 2.82%   |
| 3/2     | 1         | 1.41%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inchÂ² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 21        | 26.25%  |
| 201-250        | 13        | 16.25%  |
| 81-90          | 9         | 11.25%  |
| 301-350        | 9         | 11.25%  |
| 351-500        | 6         | 7.5%    |
| 121-130        | 6         | 7.5%    |
| 141-150        | 5         | 6.25%   |
| 151-200        | 3         | 3.75%   |
| Unknown        | 3         | 3.75%   |
| 51-60          | 2         | 2.5%    |
| More than 1000 | 1         | 1.25%   |
| 251-300        | 1         | 1.25%   |
| 91-100         | 1         | 1.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 27        | 34.62%  |
| 101-120       | 23        | 29.49%  |
| 121-160       | 22        | 28.21%  |
| Unknown       | 3         | 3.85%   |
| 161-240       | 2         | 2.56%   |
| More than 240 | 1         | 1.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 52        | 74.29%  |
| 2     | 15        | 21.43%  |
| 0     | 2         | 2.86%   |
| 3     | 1         | 1.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 40        | 37.38%  |
| Intel                 | 35        | 32.71%  |
| Qualcomm Atheros      | 13        | 12.15%  |
| Broadcom              | 5         | 4.67%   |
| Ralink                | 3         | 2.8%    |
| Broadcom Limited      | 3         | 2.8%    |
| Samsung Electronics   | 2         | 1.87%   |
| NetXen Incorporated   | 1         | 0.93%   |
| Lenovo                | 1         | 0.93%   |
| Dell                  | 1         | 0.93%   |
| D-Link System         | 1         | 0.93%   |
| AVM                   | 1         | 0.93%   |
| ASIX Electronics      | 1         | 0.93%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 29        | 22.48%  |
| Intel Wi-Fi 6 AX200                                                  | 7         | 5.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 4         | 3.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 3         | 2.33%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 3         | 2.33%   |
| Intel Wireless 8260                                                  | 3         | 2.33%   |
| Intel Wireless 7260                                                  | 3         | 2.33%   |
| Intel I211 Gigabit Network Connection                                | 3         | 2.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 2         | 1.55%   |
| Realtek RTL8125 2.5GbE Controller                                    | 2         | 1.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 2         | 1.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 2         | 1.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 1.55%   |
| Intel Wireless 8265 / 8275                                           | 2         | 1.55%   |
| Intel Wireless 3165                                                  | 2         | 1.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 2         | 1.55%   |
| Samsung Kiera                                                        | 1         | 0.78%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 1         | 0.78%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 1         | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.78%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1         | 0.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 1         | 0.78%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                           | 1         | 0.78%   |
| Realtek Killer E3000 2.5GbE Controller                               | 1         | 0.78%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 1         | 0.78%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 1         | 0.78%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 1         | 0.78%   |
| Ralink RT2561/RT61 802.11g PCI                                       | 1         | 0.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1         | 0.78%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 1         | 0.78%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                            | 1         | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 1         | 0.78%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                        | 1         | 0.78%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 1         | 0.78%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter | 1         | 0.78%   |
| Lenovo OneLink+ Giga                                                 | 1         | 0.78%   |
| Intel Wireless-AC 9260                                               | 1         | 0.78%   |
| Intel Wireless 7265                                                  | 1         | 0.78%   |
| Intel WiFi Link 5100                                                 | 1         | 0.78%   |
| Intel Wi-Fi 6 AX201                                                  | 1         | 0.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 1         | 0.78%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection        | 1         | 0.78%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 1         | 0.78%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 1         | 0.78%   |
| Intel Ethernet Connection I219-V                                     | 1         | 0.78%   |
| Intel Ethernet Connection I219-LM                                    | 1         | 0.78%   |
| Intel Ethernet Connection I217-V                                     | 1         | 0.78%   |
| Intel Ethernet Connection I217-LM                                    | 1         | 0.78%   |
| Intel Ethernet Connection (6) I219-LM                                | 1         | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                                | 1         | 0.78%   |
| Intel Ethernet Connection (3) I218-LM                                | 1         | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                                | 1         | 0.78%   |
| Intel Ethernet Connection (10) I219-V                                | 1         | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1         | 0.78%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                         | 1         | 0.78%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                        | 1         | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 1         | 0.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1         | 0.78%   |
| Intel 82574L Gigabit Network Connection                              | 1         | 0.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 30        | 52.63%  |
| Realtek Semiconductor | 10        | 17.54%  |
| Qualcomm Atheros      | 8         | 14.04%  |
| Ralink                | 3         | 5.26%   |
| Broadcom              | 3         | 5.26%   |
| D-Link System         | 1         | 1.75%   |
| Broadcom Limited      | 1         | 1.75%   |
| AVM                   | 1         | 1.75%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 7         | 12.28%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 4         | 7.02%   |
| Intel Wireless 8260                                                        | 3         | 5.26%   |
| Intel Wireless 7260                                                        | 3         | 5.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 2         | 3.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 2         | 3.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 2         | 3.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 2         | 3.51%   |
| Intel Wireless 8265 / 8275                                                 | 2         | 3.51%   |
| Intel Wireless 3165                                                        | 2         | 3.51%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1         | 1.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.75%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 1         | 1.75%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1         | 1.75%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                       | 1         | 1.75%   |
| Ralink RT2561/RT61 802.11g PCI                                             | 1         | 1.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 1.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1         | 1.75%   |
| Intel Wireless-AC 9260                                                     | 1         | 1.75%   |
| Intel Wireless 7265                                                        | 1         | 1.75%   |
| Intel WiFi Link 5100                                                       | 1         | 1.75%   |
| Intel Wi-Fi 6 AX201                                                        | 1         | 1.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                             | 1         | 1.75%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection              | 1         | 1.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                      | 1         | 1.75%   |
| Intel Gemini Lake PCH CNVi WiFi                                            | 1         | 1.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 1         | 1.75%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                               | 1         | 1.75%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                              | 1         | 1.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                   | 1         | 1.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 1         | 1.75%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 1         | 1.75%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                 | 1         | 1.75%   |
| Broadcom BCM43228 802.11a/b/g/n                                            | 1         | 1.75%   |
| Broadcom BCM43227 802.11b/g/n                                              | 1         | 1.75%   |
| Broadcom BCM43225 802.11b/g/n                                              | 1         | 1.75%   |
| AVM Fritz!WLAN N v2 [Atheros AR9271]                                       | 1         | 1.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 36        | 52.94%  |
| Intel                 | 17        | 25%     |
| Qualcomm Atheros      | 7         | 10.29%  |
| Broadcom Limited      | 2         | 2.94%   |
| Broadcom              | 2         | 2.94%   |
| Samsung Electronics   | 1         | 1.47%   |
| NetXen Incorporated   | 1         | 1.47%   |
| Lenovo                | 1         | 1.47%   |
| ASIX Electronics      | 1         | 1.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 29        | 41.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 3         | 4.29%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 3         | 4.29%   |
| Intel I211 Gigabit Network Connection                                | 3         | 4.29%   |
| Realtek RTL8125 2.5GbE Controller                                    | 2         | 2.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 2         | 2.86%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 1         | 1.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 1         | 1.43%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                           | 1         | 1.43%   |
| Realtek Killer E3000 2.5GbE Controller                               | 1         | 1.43%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 1         | 1.43%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 1         | 1.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                            | 1         | 1.43%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                        | 1         | 1.43%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 1         | 1.43%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter | 1         | 1.43%   |
| Lenovo OneLink+ Giga                                                 | 1         | 1.43%   |
| Intel Ethernet Connection I219-V                                     | 1         | 1.43%   |
| Intel Ethernet Connection I219-LM                                    | 1         | 1.43%   |
| Intel Ethernet Connection I217-V                                     | 1         | 1.43%   |
| Intel Ethernet Connection I217-LM                                    | 1         | 1.43%   |
| Intel Ethernet Connection (6) I219-LM                                | 1         | 1.43%   |
| Intel Ethernet Connection (4) I219-LM                                | 1         | 1.43%   |
| Intel Ethernet Connection (3) I218-LM                                | 1         | 1.43%   |
| Intel Ethernet Connection (2) I219-LM                                | 1         | 1.43%   |
| Intel Ethernet Connection (10) I219-V                                | 1         | 1.43%   |
| Intel 82574L Gigabit Network Connection                              | 1         | 1.43%   |
| Intel 82567LM Gigabit Network Connection                             | 1         | 1.43%   |
| Intel 82566MM Gigabit Network Connection                             | 1         | 1.43%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                     | 1         | 1.43%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                      | 1         | 1.43%   |
| Broadcom Limited NetLink BCM57785 Gigabit Ethernet PCIe              | 1         | 1.43%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe              | 1         | 1.43%   |
| ASIX AX88179 Gigabit Ethernet                                        | 1         | 1.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 65        | 52.42%  |
| WiFi     | 57        | 45.97%  |
| Modem    | 1         | 0.81%   |
| Unknown  | 1         | 0.81%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 59        | 53.64%  |
| WiFi     | 50        | 45.45%  |
| Modem    | 1         | 0.91%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 48        | 68.57%  |
| 1     | 19        | 27.14%  |
| 3     | 2         | 2.86%   |
| 5     | 1         | 1.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 53        | 74.65%  |
| Yes  | 18        | 25.35%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 39.13%  |
| Realtek Semiconductor           | 7         | 15.22%  |
| Qualcomm Atheros Communications | 6         | 13.04%  |
| Cambridge Silicon Radio         | 4         | 8.7%    |
| Foxconn / Hon Hai               | 2         | 4.35%   |
| Dell                            | 2         | 4.35%   |
| Realtek                         | 1         | 2.17%   |
| Lite-On Technology              | 1         | 2.17%   |
| IMC Networks                    | 1         | 2.17%   |
| Broadcom                        | 1         | 2.17%   |
| Belkin Components               | 1         | 2.17%   |
| ASUSTek Computer                | 1         | 2.17%   |
| Alps Electric                   | 1         | 2.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 7         | 15.22%  |
| Intel AX200 Bluetooth                                                               | 5         | 10.87%  |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 8.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 8.7%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 6.52%   |
| Realtek Bluetooth Radio                                                             | 2         | 4.35%   |
| Intel Bluetooth Device                                                              | 2         | 4.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 2         | 4.35%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 2.17%   |
| Realtek Bluetooth Radio                                                             | 1         | 2.17%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 2.17%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 2.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 2.17%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 2.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 2.17%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 2.17%   |
| IMC Networks Bluetooth Device                                                       | 1         | 2.17%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 2.17%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 2.17%   |
| Dell Broadcom BCM20702A0 Bluetooth                                                  | 1         | 2.17%   |
| Dell BCM20702A0                                                                     | 1         | 2.17%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 2.17%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                               | 1         | 2.17%   |
| ASUS ASUS USB-BT500                                                                 | 1         | 2.17%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 2.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 47        | 45.63%  |
| AMD                       | 26        | 25.24%  |
| Nvidia                    | 19        | 18.45%  |
| Logitech                  | 2         | 1.94%   |
| C-Media Electronics       | 2         | 1.94%   |
| Texas Instruments         | 1         | 0.97%   |
| Sennheiser Communications | 1         | 0.97%   |
| Lenovo                    | 1         | 0.97%   |
| JMTek                     | 1         | 0.97%   |
| GN Netcom                 | 1         | 0.97%   |
| Creative Labs             | 1         | 0.97%   |
| BEHRINGER International   | 1         | 0.97%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 7         | 5.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 5.04%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6         | 5.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 4.2%    |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 4.2%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5         | 4.2%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 3.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 3.36%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 4         | 3.36%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 2.52%   |
| Nvidia GA102 High Definition Audio Controller                              | 3         | 2.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 2.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 2.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 2.52%   |
| AMD FCH Azalia Controller                                                  | 3         | 2.52%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.68%   |
| Logitech Headset H390                                                      | 2         | 1.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 1.68%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.68%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 2         | 1.68%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 1.68%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 2         | 1.68%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.68%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 1.68%   |
| Texas Instruments PCM2900C Audio CODEC                                     | 1         | 0.84%   |
| Sennheiser Communications Sennheiser 3D G4ME1                              | 1         | 0.84%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.84%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.84%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 0.84%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.84%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.84%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 0.84%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 0.84%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.84%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.84%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.84%   |
| Nvidia GF100 High Definition Audio Controller                              | 1         | 0.84%   |
| Lenovo ThinkPad OneLink Plus Dock Audio                                    | 1         | 0.84%   |
| JMTek audio controller                                                     | 1         | 0.84%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 0.84%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 0.84%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 0.84%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.84%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.84%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.84%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 0.84%   |
| Intel Audio device                                                         | 1         | 0.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.84%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1         | 0.84%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 0.84%   |
| Intel 200 Series PCH HD Audio                                              | 1         | 0.84%   |
| GN Netcom Jabra UC VOICE 150a MS                                           | 1         | 0.84%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 1         | 0.84%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 1         | 0.84%   |
| C-Media Electronics CM108 Audio Controller                                 | 1         | 0.84%   |
| BEHRINGER International UMC202HD 192k                                      | 1         | 0.84%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 0.84%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]          | 1         | 0.84%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 0.84%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1         | 0.84%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 10        | 22.22%  |
| Unknown                | 6         | 13.33%  |
| SK Hynix               | 6         | 13.33%  |
| Kingston               | 6         | 13.33%  |
| G.Skill                | 4         | 8.89%   |
| Crucial                | 4         | 8.89%   |
| Micron Technology      | 2         | 4.44%   |
| Corsair                | 2         | 4.44%   |
| Unknown (000004B30000) | 1         | 2.22%   |
| Ramaxel Technology     | 1         | 2.22%   |
| GOODRAM                | 1         | 2.22%   |
| GeIL                   | 1         | 2.22%   |
| A-DATA Technology      | 1         | 2.22%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Kingston RAM KHX3600C18D4/32GX 32GB DIMM DDR4 3600MT/s         | 2         | 4%      |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                     | 1         | 2%      |
| Unknown RAM Module 4096MB SODIMM DDR3                          | 1         | 2%      |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 2%      |
| Unknown RAM Module 2048MB SODIMM 1067MT/s                      | 1         | 2%      |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                   | 1         | 2%      |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                     | 1         | 2%      |
| Unknown RAM Module 1024MB SODIMM 1067MT/s                      | 1         | 2%      |
| Unknown RAM 992124 (997124) 8GB DIMM DDR3 1600MT/s             | 1         | 2%      |
| Unknown (000004B30000) RAM Module 32GB DIMM DDR3 1333MT/s      | 1         | 2%      |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                   | 1         | 2%      |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s         | 1         | 2%      |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 1         | 2%      |
| SK Hynix RAM HMT351R7CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 1         | 2%      |
| SK Hynix RAM HMT151R7BFR4C-G7 4GB DIMM DDR3 1066MT/s           | 1         | 2%      |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 1         | 2%      |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s      | 1         | 2%      |
| SK Hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s      | 1         | 2%      |
| Samsung RAM M471B5673FH0-CH9 2GB DIMM DDR3 4199MT/s            | 1         | 2%      |
| Samsung RAM M471B5673EH1-CH9 2GB SODIMM DDR3 1334MT/s          | 1         | 2%      |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 2%      |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 1         | 2%      |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s         | 1         | 2%      |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s      | 1         | 2%      |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s       | 1         | 2%      |
| Samsung RAM M471A1G44AB0-CWE 8192MB Row Of Chips DDR4 3200MT/s | 1         | 2%      |
| Samsung RAM K4F6E3S4HM-MGCJ 4GB SODIMM LPDDR4 3733MT/s         | 1         | 2%      |
| Samsung RAM K4E6E304EE-EGCF 4GB SODIMM LPDDR3 1867MT/s         | 1         | 2%      |
| Samsung RAM K4E6E304EE-EGCF 4GB Chip LPDDR3 1867MT/s           | 1         | 2%      |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s        | 1         | 2%      |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s    | 1         | 2%      |
| Micron RAM 16JTF1G64AZ-1G6D1 8GB DIMM DDR3 1600MT/s            | 1         | 2%      |
| Kingston RAM MSI26D4S9S8ME-8 8192MB SODIMM DDR4 2667MT/s       | 1         | 2%      |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s         | 1         | 2%      |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s              | 1         | 2%      |
| Kingston RAM ACR16D3LS1KFG/8G 8192MB SODIMM DDR3 1600MT/s      | 1         | 2%      |
| GOODRAM RAM IR2400S464L15S/8G 8192MB SODIMM DDR4 2133MT/s      | 1         | 2%      |
| GeIL RAM CL11-11-11 D3-1600 4GB DIMM DDR3 1600MT/s             | 1         | 2%      |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s            | 1         | 2%      |
| G.Skill RAM F4-3200C15-16GTZKY 16384MB DIMM DDR4 3200MT/s      | 1         | 2%      |
| G.Skill RAM F4-2666C19-16GIS 16384MB DIMM DDR4 2667MT/s        | 1         | 2%      |
| G.Skill RAM F4-2400C15-8GNT 8GB DIMM DDR4 2400MT/s             | 1         | 2%      |
| Crucial RAM CT16G4DFRA266.C16FE 16384MB DIMM DDR4 2667MT/s     | 1         | 2%      |
| Crucial RAM CT102464BD160B.M16 8GB DIMM DDR3 1600MT/s          | 1         | 2%      |
| Crucial RAM BLS16G4D32AESB.M16FE 16GB DIMM DDR4 3400MT/s       | 1         | 2%      |
| Crucial RAM BL32G32C16U4R.M16FB1 32GB DIMM DDR4 3200MT/s       | 1         | 2%      |
| Corsair RAM CMSX8GX4M1A2400C16 8GB SODIMM DDR4 2400MT/s        | 1         | 2%      |
| Corsair RAM CMK16GX4M1E3200C16 16384MB DIMM DDR4 3000MT/s      | 1         | 2%      |
| A-DATA RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 1         | 2%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 22        | 53.66%  |
| DDR3    | 11        | 26.83%  |
| LPDDR4  | 3         | 7.32%   |
| DDR2    | 2         | 4.88%   |
| SDRAM   | 1         | 2.44%   |
| LPDDR3  | 1         | 2.44%   |
| Unknown | 1         | 2.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 21        | 51.22%  |
| DIMM         | 17        | 41.46%  |
| Row Of Chips | 2         | 4.88%   |
| Chip         | 1         | 2.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 17        | 36.96%  |
| 4096  | 10        | 21.74%  |
| 16384 | 7         | 15.22%  |
| 32768 | 5         | 10.87%  |
| 2048  | 5         | 10.87%  |
| 1024  | 2         | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 9         | 20%     |
| 2667    | 8         | 17.78%  |
| 3200    | 6         | 13.33%  |
| 3600    | 3         | 6.67%   |
| 2400    | 2         | 4.44%   |
| 2133    | 2         | 4.44%   |
| 667     | 2         | 4.44%   |
| 4267    | 1         | 2.22%   |
| 4199    | 1         | 2.22%   |
| 3733    | 1         | 2.22%   |
| 3400    | 1         | 2.22%   |
| 3000    | 1         | 2.22%   |
| 2933    | 1         | 2.22%   |
| 1867    | 1         | 2.22%   |
| 1334    | 1         | 2.22%   |
| 1333    | 1         | 2.22%   |
| 1067    | 1         | 2.22%   |
| 1066    | 1         | 2.22%   |
| 800     | 1         | 2.22%   |
| Unknown | 1         | 2.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 2         | 28.57%  |
| Samsung Electronics | 1         | 14.29%  |
| Prolific Technology | 1         | 14.29%  |
| Kyocera             | 1         | 14.29%  |
| Hewlett-Packard     | 1         | 14.29%  |
| Canon               | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung SCX-4200 series       | 1         | 14.29%  |
| Prolific PL2305 Parallel Port | 1         | 14.29%  |
| Kyocera FS-1030D printer      | 1         | 14.29%  |
| HP ENVY 4500 series           | 1         | 14.29%  |
| Canon CanoScan LiDE 300       | 1         | 14.29%  |
| Brother Printer               | 1         | 14.29%  |
| Brother HL-L3210CW series     | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 50%     |
| Canon CanoScan LiDE 210       | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 7         | 16.67%  |
| Logitech                               | 5         | 11.9%   |
| Acer                                   | 5         | 11.9%   |
| Realtek Semiconductor                  | 4         | 9.52%   |
| Sunplus Innovation Technology          | 3         | 7.14%   |
| Quanta                                 | 3         | 7.14%   |
| IMC Networks                           | 3         | 7.14%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 7.14%   |
| Z-Star Microelectronics                | 1         | 2.38%   |
| Syntek                                 | 1         | 2.38%   |
| Silicon Motion                         | 1         | 2.38%   |
| Ricoh                                  | 1         | 2.38%   |
| Microdia                               | 1         | 2.38%   |
| Luxvisions Innotech Limited            | 1         | 2.38%   |
| Lite-On Technology                     | 1         | 2.38%   |
| Creative Technology                    | 1         | 2.38%   |
| ALi                                    | 1         | 2.38%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Logitech Webcam C270                                                     | 2         | 4.65%   |
| Logitech B525 HD Webcam                                                  | 2         | 4.65%   |
| Chicony Integrated Camera                                                | 2         | 4.65%   |
| Acer Integrated Camera                                                   | 2         | 4.65%   |
| Z-Star Venus USB2.0 Camera                                               | 1         | 2.33%   |
| Syntek Lenovo EasyCamera                                                 | 1         | 2.33%   |
| Sunplus Integrated_Webcam_HD                                             | 1         | 2.33%   |
| Sunplus HD WebCam                                                        | 1         | 2.33%   |
| Sunplus 1.3M HD WebCam                                                   | 1         | 2.33%   |
| Silicon Motion WebCam SC-13HDN10939N                                     | 1         | 2.33%   |
| Ricoh Sony Vaio Integrated Webcam                                        | 1         | 2.33%   |
| Realtek USB Camera                                                       | 1         | 2.33%   |
| Realtek Lenovo EasyCamera                                                | 1         | 2.33%   |
| Realtek Laptop_Integrated_Webcam_HD                                      | 1         | 2.33%   |
| Realtek Integrated_Webcam_HD                                             | 1         | 2.33%   |
| Realtek Integrated Webcam HD                                             | 1         | 2.33%   |
| Quanta HP Wide Vision HD Camera                                          | 1         | 2.33%   |
| Quanta HP TrueVision HD Camera                                           | 1         | 2.33%   |
| Quanta HD User Facing                                                    | 1         | 2.33%   |
| Microdia Integrated_Webcam_HD                                            | 1         | 2.33%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                      | 1         | 2.33%   |
| Logitech Webcam C250                                                     | 1         | 2.33%   |
| Lite-On Integrated Camera                                                | 1         | 2.33%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 1         | 2.33%   |
| IMC Networks USB2.0 UVC HD Webcam                                        | 1         | 2.33%   |
| IMC Networks Integrated Camera                                           | 1         | 2.33%   |
| Creative Live! Cam Sync 1080p                                            | 1         | 2.33%   |
| Chicony VGA 24fps UVC Webcam                                             | 1         | 2.33%   |
| Chicony USB2.0 Camera                                                    | 1         | 2.33%   |
| Chicony ThinkPad T490 Webcam                                             | 1         | 2.33%   |
| Chicony HP Webcam                                                        | 1         | 2.33%   |
| Chicony EasyCamera                                                       | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                            | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                         | 1         | 2.33%   |
| ALi Gateway Webcam                                                       | 1         | 2.33%   |
| Acer HD Webcam                                                           | 1         | 2.33%   |
| Acer BisonCam,NB Pro                                                     | 1         | 2.33%   |
| Acer BisonCam, NB Pro                                                    | 1         | 2.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 40%     |
| Synaptics                  | 3         | 30%     |
| Upek                       | 1         | 10%     |
| Shenzhen Goodix Technology | 1         | 10%     |
| AuthenTec                  | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 20%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 10%     |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 10%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 10%     |
| Synaptics  WBDI                                        | 1         | 10%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 10%     |
| Shenzhen Goodix  Fingerprint Device                    | 1         | 10%     |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 10%     |
| Unknown                                                | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 2         | 40%     |
| O2 Micro              | 1         | 20%     |
| Gemalto (was Gemplus) | 1         | 20%     |
| Broadcom              | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader               | 2         | 40%     |
| O2 Micro OZ776 CCID Smartcard Reader              | 1         | 20%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor    | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 49        | 69.01%  |
| 1     | 18        | 25.35%  |
| 2     | 4         | 5.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 10        | 38.46%  |
| Chipcard                 | 6         | 23.08%  |
| Graphics card            | 5         | 19.23%  |
| Net/wireless             | 2         | 7.69%   |
| Communication controller | 1         | 3.85%   |
| Camera                   | 1         | 3.85%   |
| Bluetooth                | 1         | 3.85%   |

