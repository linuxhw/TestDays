MX 21 - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for MX 21.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/MX_21/Desktop/README.md) and [notebooks](/Dist/MX_21/Notebook/README.md).

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

Total: 83

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [83dab83528](https://linux-hardware.org/?probe=83dab83528) | Apr 01, 2022 |
| TUXEDO        | N7x0WU                      | Notebook    | [cf4f31fe3c](https://linux-hardware.org/?probe=cf4f31fe3c) | Mar 30, 2022 |
| Lenovo        | ThinkPad T440p 20AW002VB... | Notebook    | [e3ec03ac31](https://linux-hardware.org/?probe=e3ec03ac31) | Mar 29, 2022 |
| Dell          | Latitude 3190               | Notebook    | [ffd3ee8119](https://linux-hardware.org/?probe=ffd3ee8119) | Mar 28, 2022 |
| Framework     | Laptop                      | Notebook    | [a9f49dfe70](https://linux-hardware.org/?probe=a9f49dfe70) | Mar 24, 2022 |
| Dell          | Latitude 3190               | Notebook    | [960989448e](https://linux-hardware.org/?probe=960989448e) | Mar 21, 2022 |
| Lenovo        | 1046 NO DPK                 | Desktop     | [561b1c3324](https://linux-hardware.org/?probe=561b1c3324) | Mar 17, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [d0b555e0ba](https://linux-hardware.org/?probe=d0b555e0ba) | Mar 17, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [c8c2d7bba3](https://linux-hardware.org/?probe=c8c2d7bba3) | Mar 14, 2022 |
| Dell          | Latitude 3190               | Notebook    | [6d1ab0283d](https://linux-hardware.org/?probe=6d1ab0283d) | Mar 14, 2022 |
| HP            | 3647h                       | Desktop     | [fd6766aabb](https://linux-hardware.org/?probe=fd6766aabb) | Mar 11, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | Desktop     | [772e020316](https://linux-hardware.org/?probe=772e020316) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [71aaa6a920](https://linux-hardware.org/?probe=71aaa6a920) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [b08ddd1115](https://linux-hardware.org/?probe=b08ddd1115) | Mar 09, 2022 |
| Dell          | Latitude 3190               | Notebook    | [620f4d4f09](https://linux-hardware.org/?probe=620f4d4f09) | Mar 07, 2022 |
| Dell          | Latitude 3190               | Notebook    | [964420352c](https://linux-hardware.org/?probe=964420352c) | Feb 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [7147fe2d5c](https://linux-hardware.org/?probe=7147fe2d5c) | Feb 26, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [b234cc741f](https://linux-hardware.org/?probe=b234cc741f) | Feb 22, 2022 |
| Dell          | Latitude 3190               | Notebook    | [9637b88602](https://linux-hardware.org/?probe=9637b88602) | Feb 21, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [851badde2e](https://linux-hardware.org/?probe=851badde2e) | Feb 20, 2022 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [e58223cc60](https://linux-hardware.org/?probe=e58223cc60) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [23c722f6cf](https://linux-hardware.org/?probe=23c722f6cf) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [f4fec6a5be](https://linux-hardware.org/?probe=f4fec6a5be) | Feb 17, 2022 |
| Sony          | VPCF119FX                   | Notebook    | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| Dell          | Latitude 3190               | Notebook    | [6340f68567](https://linux-hardware.org/?probe=6340f68567) | Feb 14, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [7c66c1b404](https://linux-hardware.org/?probe=7c66c1b404) | Feb 09, 2022 |
| Sony          | SVE1513Q1ESI                | Notebook    | [77e599ef9f](https://linux-hardware.org/?probe=77e599ef9f) | Feb 08, 2022 |
| Dell          | Latitude 3190               | Notebook    | [90df65f573](https://linux-hardware.org/?probe=90df65f573) | Feb 07, 2022 |
| Dell          | Latitude E4310              | Notebook    | [50190cb420](https://linux-hardware.org/?probe=50190cb420) | Feb 06, 2022 |
| efirstview    | v01099                      | Notebook    | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| Dell          | Latitude 3190               | Notebook    | [2e81dc022b](https://linux-hardware.org/?probe=2e81dc022b) | Jan 31, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [4ffe151e7a](https://linux-hardware.org/?probe=4ffe151e7a) | Jan 29, 2022 |
| Dell          | Latitude 3190               | Notebook    | [9b8e8549fd](https://linux-hardware.org/?probe=9b8e8549fd) | Jan 24, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | Notebook    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Sony          | VPCEH2N1E                   | Notebook    | [17a4bc1847](https://linux-hardware.org/?probe=17a4bc1847) | Jan 22, 2022 |
| Fujitsu Si... | LIFEBOOK E8010              | Notebook    | [82d1bc5db0](https://linux-hardware.org/?probe=82d1bc5db0) | Jan 22, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [882906d968](https://linux-hardware.org/?probe=882906d968) | Jan 17, 2022 |
| Alienware     | 13 R2                       | Notebook    | [65c1ae9026](https://linux-hardware.org/?probe=65c1ae9026) | Jan 14, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3bb6a6428f](https://linux-hardware.org/?probe=3bb6a6428f) | Jan 10, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [58cff543b5](https://linux-hardware.org/?probe=58cff543b5) | Jan 06, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [ecaec39529](https://linux-hardware.org/?probe=ecaec39529) | Jan 05, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| Dell          | Latitude 3190               | Notebook    | [2c483dc59d](https://linux-hardware.org/?probe=2c483dc59d) | Jan 03, 2022 |
| Gigabyte      | P15FV5                      | Notebook    | [164348e568](https://linux-hardware.org/?probe=164348e568) | Jan 03, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [7cc374183b](https://linux-hardware.org/?probe=7cc374183b) | Dec 30, 2021 |
| Dell          | Latitude 3190               | Notebook    | [67cba6d321](https://linux-hardware.org/?probe=67cba6d321) | Dec 27, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [9147191a67](https://linux-hardware.org/?probe=9147191a67) | Dec 24, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [b0cde813b9](https://linux-hardware.org/?probe=b0cde813b9) | Dec 23, 2021 |
| Dell          | Latitude 3190               | Notebook    | [1a96380872](https://linux-hardware.org/?probe=1a96380872) | Dec 20, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [78d4e04363](https://linux-hardware.org/?probe=78d4e04363) | Dec 16, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| Dell          | Latitude 3190               | Notebook    | [5321909b8c](https://linux-hardware.org/?probe=5321909b8c) | Dec 13, 2021 |
| Dell          | Latitude 3190               | Notebook    | [9c532278f1](https://linux-hardware.org/?probe=9c532278f1) | Dec 06, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [21180cbdad](https://linux-hardware.org/?probe=21180cbdad) | Dec 04, 2021 |
| GALAX         | B550M                       | Desktop     | [a6866c8a45](https://linux-hardware.org/?probe=a6866c8a45) | Dec 04, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [bc8359d097](https://linux-hardware.org/?probe=bc8359d097) | Dec 01, 2021 |
| Lenovo        | B590 20208                  | Notebook    | [ed08d6bdd9](https://linux-hardware.org/?probe=ed08d6bdd9) | Nov 30, 2021 |
| Dell          | Latitude 3190               | Notebook    | [700dd2459e](https://linux-hardware.org/?probe=700dd2459e) | Nov 29, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| Dell          | Latitude 3190               | Notebook    | [7f020f1d1f](https://linux-hardware.org/?probe=7f020f1d1f) | Nov 22, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [bb58f4914e](https://linux-hardware.org/?probe=bb58f4914e) | Nov 21, 2021 |
| ASUSTek       | N53SN                       | Notebook    | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| Dell          | Latitude 3190               | Notebook    | [f24ac635ba](https://linux-hardware.org/?probe=f24ac635ba) | Nov 15, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [791ae651bb](https://linux-hardware.org/?probe=791ae651bb) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [b105aaabf5](https://linux-hardware.org/?probe=b105aaabf5) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [fd5f409df8](https://linux-hardware.org/?probe=fd5f409df8) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [a85cc99f78](https://linux-hardware.org/?probe=a85cc99f78) | Nov 14, 2021 |
| HP            | Compaq Presario CQ60        | Notebook    | [9d83baca33](https://linux-hardware.org/?probe=9d83baca33) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [c277967769](https://linux-hardware.org/?probe=c277967769) | Nov 11, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [18391015f7](https://linux-hardware.org/?probe=18391015f7) | Nov 11, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [25964b9256](https://linux-hardware.org/?probe=25964b9256) | Nov 08, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [cd26ab6e8f](https://linux-hardware.org/?probe=cd26ab6e8f) | Nov 05, 2021 |
| Dell          | Latitude 3190               | Notebook    | [592b613273](https://linux-hardware.org/?probe=592b613273) | Nov 01, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [fbd2076eee](https://linux-hardware.org/?probe=fbd2076eee) | Oct 28, 2021 |
| ASUSTek       | E402MA                      | Notebook    | [4c2453c6a2](https://linux-hardware.org/?probe=4c2453c6a2) | Oct 26, 2021 |
| Sony          | VPCEC3S1E                   | Notebook    | [2af79ba873](https://linux-hardware.org/?probe=2af79ba873) | Oct 25, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ee6a141211](https://linux-hardware.org/?probe=ee6a141211) | Oct 19, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [5d136cb09b](https://linux-hardware.org/?probe=5d136cb09b) | Aug 13, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [c4ebb4c114](https://linux-hardware.org/?probe=c4ebb4c114) | Jun 04, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.0-9-amd64            | 18        | 31.03%  |
| 5.14.0-4mx-amd64          | 10        | 17.24%  |
| 5.10.0-11-amd64           | 8         | 13.79%  |
| 5.10.0-10-amd64           | 5         | 8.62%   |
| 5.14.0-3mx-amd64          | 2         | 3.45%   |
| 5.10.0-8-amd64            | 2         | 3.45%   |
| 5.10.0-13-amd64           | 2         | 3.45%   |
| 5.10.0-11-686-pae         | 2         | 3.45%   |
| 5.16.0-rc5-hwmon-next+    | 1         | 1.72%   |
| 5.16.0-4mx-amd64          | 1         | 1.72%   |
| 5.15.0-2-amd64            | 1         | 1.72%   |
| 5.15.0-0.bpo.2-amd64      | 1         | 1.72%   |
| 5.14.0-2mx-amd64          | 1         | 1.72%   |
| 5.10.52-antix.1-amd64-smp | 1         | 1.72%   |
| 5.10.0-5mx-amd64          | 1         | 1.72%   |
| 5.10.0-12-amd64           | 1         | 1.72%   |
| 5.10.0-11-686             | 1         | 1.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 38        | 67.86%  |
| 5.14.0  | 13        | 23.21%  |
| 5.16.0  | 2         | 3.57%   |
| 5.15.0  | 2         | 3.57%   |
| 5.10.52 | 1         | 1.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 39        | 69.64%  |
| 5.14    | 13        | 23.21%  |
| 5.16    | 2         | 3.57%   |
| 5.15    | 2         | 3.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 53        | 94.64%  |
| i686   | 3         | 5.36%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 37        | 66.07%  |
| KDE5             | 16        | 28.57%  |
| lightdm-xsession | 1         | 1.79%   |
| GNOME            | 1         | 1.79%   |
| Budgie           | 1         | 1.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 55        | 98.21%  |
| Tty  | 1         | 1.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 39        | 69.64%  |
| SDDM    | 16        | 28.57%  |
| Unknown | 1         | 1.79%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 26        | 46.43%  |
| de_DE   | 8         | 14.29%  |
| it_IT   | 3         | 5.36%   |
| en_GB   | 3         | 5.36%   |
| de_CH   | 3         | 5.36%   |
| Unknown | 3         | 5.36%   |
| ru_RU   | 2         | 3.57%   |
| pt_BR   | 2         | 3.57%   |
| fr_FR   | 2         | 3.57%   |
| tr_TR   | 1         | 1.79%   |
| sk_SK   | 1         | 1.79%   |
| es_PE   | 1         | 1.79%   |
| es_ES   | 1         | 1.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 38        | 67.86%  |
| BIOS | 18        | 32.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 46        | 82.14%  |
| Overlay | 6         | 10.71%  |
| Btrfs   | 3         | 5.36%   |
| F2fs    | 1         | 1.79%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 44        | 78.57%  |
| MBR  | 12        | 21.43%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 31        | 55.36%  |
| Yes       | 25        | 44.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 30        | 53.57%  |
| Yes       | 26        | 46.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 10        | 17.86%  |
| ASUSTek Computer    | 9         | 16.07%  |
| Hewlett-Packard     | 7         | 12.5%   |
| Sony                | 4         | 7.14%   |
| Gigabyte Technology | 4         | 7.14%   |
| Apple               | 4         | 7.14%   |
| Dell                | 3         | 5.36%   |
| Samsung Electronics | 2         | 3.57%   |
| MSI                 | 2         | 3.57%   |
| Fujitsu Siemens     | 2         | 3.57%   |
| TUXEDO              | 1         | 1.79%   |
| Huanan              | 1         | 1.79%   |
| GALAX               | 1         | 1.79%   |
| Fujitsu             | 1         | 1.79%   |
| Framework           | 1         | 1.79%   |
| efirstview          | 1         | 1.79%   |
| Chuwi               | 1         | 1.79%   |
| ASRock              | 1         | 1.79%   |
| Alienware           | 1         | 1.79%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| TUXEDO N7x0WU                             | 1         | 1.79%   |
| Sony VPCF119FX                            | 1         | 1.79%   |
| Sony VPCEH2N1E                            | 1         | 1.79%   |
| Sony VPCEC3S1E                            | 1         | 1.79%   |
| Sony SVE1513Q1ESI                         | 1         | 1.79%   |
| Samsung 350V5C/351V5C/3540VC/3440VC       | 1         | 1.79%   |
| Samsung 340XAA/350XAA/550XAA              | 1         | 1.79%   |
| MSI MS-7917                               | 1         | 1.79%   |
| MSI Alpha 15 B5EEK                        | 1         | 1.79%   |
| Lenovo Yoga 7 14ITL5 82BH                 | 1         | 1.79%   |
| Lenovo ThinkStation P620 30E0CTO1WW       | 1         | 1.79%   |
| Lenovo ThinkPad W541 20EG0005MS           | 1         | 1.79%   |
| Lenovo ThinkPad T440p 20AW002VBR          | 1         | 1.79%   |
| Lenovo ThinkPad E15 Gen 3 20YG008CUS      | 1         | 1.79%   |
| Lenovo ThinkBook 13s-IWL 20R9             | 1         | 1.79%   |
| Lenovo IdeaPad Y700-15ISK 80NV            | 1         | 1.79%   |
| Lenovo G400s VILG1                        | 1         | 1.79%   |
| Lenovo B590 20208                         | 1         | 1.79%   |
| Lenovo 10AAS1QB0B                         | 1         | 1.79%   |
| Huanan X99-F8                             | 1         | 1.79%   |
| HP Z400 Workstation                       | 1         | 1.79%   |
| HP Spectre x360 Convertible 15-df1xxx     | 1         | 1.79%   |
| HP EliteBook 850 G3                       | 1         | 1.79%   |
| HP EliteBook 8440p                        | 1         | 1.79%   |
| HP EliteBook 840 G3                       | 1         | 1.79%   |
| HP Compaq Presario CQ60                   | 1         | 1.79%   |
| HP Compaq 8000 Elite CMT PC               | 1         | 1.79%   |
| Gigabyte Z390 UD                          | 1         | 1.79%   |
| Gigabyte X570 AORUS PRO                   | 1         | 1.79%   |
| Gigabyte P15FV5                           | 1         | 1.79%   |
| Gigabyte B550M DS3H                       | 1         | 1.79%   |
| GALAX B550M                               | 1         | 1.79%   |
| Fujitsu Siemens LIFEBOOK E8010            | 1         | 1.79%   |
| Fujitsu Siemens ESPRIMO Mobile D9500      | 1         | 1.79%   |
| Fujitsu ESPRIMO P720                      | 1         | 1.79%   |
| Framework Laptop                          | 1         | 1.79%   |
| efirstview v01099                         | 1         | 1.79%   |
| Dell XPS 17 9710                          | 1         | 1.79%   |
| Dell Latitude E4310                       | 1         | 1.79%   |
| Dell Latitude 3190                        | 1         | 1.79%   |
| Chuwi GemiBook Pro                        | 1         | 1.79%   |
| ASUS X550CC                               | 1         | 1.79%   |
| ASUS TUF Gaming FX505DT_FX505DT           | 1         | 1.79%   |
| ASUS ROG Maximus XIII HERO                | 1         | 1.79%   |
| ASUS P5GC-MX/MEDION/SI                    | 1         | 1.79%   |
| ASUS N53SN                                | 1         | 1.79%   |
| ASUS E402MA                               | 1         | 1.79%   |
| ASUS ASUS TUF Gaming A15 FA506QE_TUF506QE | 1         | 1.79%   |
| ASUS All Series                           | 1         | 1.79%   |
| ASUS 1101HA                               | 1         | 1.79%   |
| ASRock X570 Steel Legend                  | 1         | 1.79%   |
| Apple Macmini6,2                          | 1         | 1.79%   |
| Apple MacBook3,1                          | 1         | 1.79%   |
| Apple iMac12,1                            | 1         | 1.79%   |
| Apple iMac11,2                            | 1         | 1.79%   |
| Alienware 13 R2                           | 1         | 1.79%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 3         | 5.36%   |
| HP EliteBook             | 3         | 5.36%   |
| HP Compaq                | 2         | 3.57%   |
| Dell Latitude            | 2         | 3.57%   |
| TUXEDO N7x0WU            | 1         | 1.79%   |
| Sony VPCF119FX           | 1         | 1.79%   |
| Sony VPCEH2N1E           | 1         | 1.79%   |
| Sony VPCEC3S1E           | 1         | 1.79%   |
| Sony SVE1513Q1ESI        | 1         | 1.79%   |
| Samsung 350V5C           | 1         | 1.79%   |
| Samsung 340XAA           | 1         | 1.79%   |
| MSI MS-7917              | 1         | 1.79%   |
| MSI Alpha                | 1         | 1.79%   |
| Lenovo Yoga              | 1         | 1.79%   |
| Lenovo ThinkStation      | 1         | 1.79%   |
| Lenovo ThinkBook         | 1         | 1.79%   |
| Lenovo IdeaPad           | 1         | 1.79%   |
| Lenovo G400s             | 1         | 1.79%   |
| Lenovo B590              | 1         | 1.79%   |
| Lenovo 10AAS1QB0B        | 1         | 1.79%   |
| Huanan X99-F8            | 1         | 1.79%   |
| HP Z400                  | 1         | 1.79%   |
| HP Spectre               | 1         | 1.79%   |
| Gigabyte Z390            | 1         | 1.79%   |
| Gigabyte X570            | 1         | 1.79%   |
| Gigabyte P15FV5          | 1         | 1.79%   |
| Gigabyte B550M           | 1         | 1.79%   |
| GALAX B550M              | 1         | 1.79%   |
| Fujitsu Siemens LIFEBOOK | 1         | 1.79%   |
| Fujitsu Siemens ESPRIMO  | 1         | 1.79%   |
| Fujitsu ESPRIMO          | 1         | 1.79%   |
| Framework Laptop         | 1         | 1.79%   |
| efirstview v01099        | 1         | 1.79%   |
| Dell XPS                 | 1         | 1.79%   |
| Chuwi GemiBook           | 1         | 1.79%   |
| ASUS X550CC              | 1         | 1.79%   |
| ASUS TUF                 | 1         | 1.79%   |
| ASUS ROG                 | 1         | 1.79%   |
| ASUS P5GC-MX             | 1         | 1.79%   |
| ASUS N53SN               | 1         | 1.79%   |
| ASUS E402MA              | 1         | 1.79%   |
| ASUS ASUS                | 1         | 1.79%   |
| ASUS All                 | 1         | 1.79%   |
| ASUS 1101HA              | 1         | 1.79%   |
| ASRock X570              | 1         | 1.79%   |
| Apple Macmini6           | 1         | 1.79%   |
| Apple MacBook3           | 1         | 1.79%   |
| Apple iMac12             | 1         | 1.79%   |
| Apple iMac11             | 1         | 1.79%   |
| Alienware 13             | 1         | 1.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 7         | 12.5%   |
| 2010    | 6         | 10.71%  |
| 2020    | 5         | 8.93%   |
| 2019    | 5         | 8.93%   |
| 2015    | 5         | 8.93%   |
| 2013    | 5         | 8.93%   |
| 2018    | 4         | 7.14%   |
| 2016    | 3         | 5.36%   |
| 2014    | 3         | 5.36%   |
| 2011    | 3         | 5.36%   |
| 2009    | 2         | 3.57%   |
| 2008    | 2         | 3.57%   |
| 2007    | 2         | 3.57%   |
| 2017    | 1         | 1.79%   |
| 2012    | 1         | 1.79%   |
| 2005    | 1         | 1.79%   |
| Unknown | 1         | 1.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 36        | 64.29%  |
| Desktop     | 15        | 26.79%  |
| Convertible | 2         | 3.57%   |
| All in one  | 2         | 3.57%   |
| Mini pc     | 1         | 1.79%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 55        | 98.21%  |
| Enabled  | 1         | 1.79%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 56        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 17        | 30.36%  |
| 8.01-16.0   | 12        | 21.43%  |
| 16.01-24.0  | 9         | 16.07%  |
| 32.01-64.0  | 6         | 10.71%  |
| 3.01-4.0    | 4         | 7.14%   |
| 2.01-3.0    | 3         | 5.36%   |
| 64.01-256.0 | 2         | 3.57%   |
| 24.01-32.0  | 1         | 1.79%   |
| 1.01-2.0    | 1         | 1.79%   |
| 0.51-1.0    | 1         | 1.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 22        | 38.6%   |
| 2.01-3.0   | 15        | 26.32%  |
| 3.01-4.0   | 7         | 12.28%  |
| 4.01-8.0   | 5         | 8.77%   |
| 0.51-1.0   | 5         | 8.77%   |
| 8.01-16.0  | 2         | 3.51%   |
| 16.01-24.0 | 1         | 1.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 31        | 55.36%  |
| 2      | 13        | 23.21%  |
| 3      | 8         | 14.29%  |
| 8      | 1         | 1.79%   |
| 5      | 1         | 1.79%   |
| 4      | 1         | 1.79%   |
| 0      | 1         | 1.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 36        | 64.29%  |
| Yes       | 20        | 35.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 83.93%  |
| No        | 9         | 16.07%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 78.57%  |
| No        | 12        | 21.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 60.71%  |
| No        | 22        | 39.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 16        | 28.57%  |
| Germany     | 7         | 12.5%   |
| Italy       | 5         | 8.93%   |
| Switzerland | 3         | 5.36%   |
| Brazil      | 3         | 5.36%   |
| France      | 2         | 3.57%   |
| Canada      | 2         | 3.57%   |
| Belgium     | 2         | 3.57%   |
| UK          | 1         | 1.79%   |
| Turkey      | 1         | 1.79%   |
| Spain       | 1         | 1.79%   |
| Slovakia    | 1         | 1.79%   |
| Serbia      | 1         | 1.79%   |
| Russia      | 1         | 1.79%   |
| Poland      | 1         | 1.79%   |
| Peru        | 1         | 1.79%   |
| Netherlands | 1         | 1.79%   |
| India       | 1         | 1.79%   |
| Greece      | 1         | 1.79%   |
| Finland     | 1         | 1.79%   |
| Belarus     | 1         | 1.79%   |
| Azerbaijan  | 1         | 1.79%   |
| Austria     | 1         | 1.79%   |
| Australia   | 1         | 1.79%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Portland       | 2         | 3.57%   |
| Lausen         | 2         | 3.57%   |
| Zurich         | 1         | 1.79%   |
| Warsaw         | 1         | 1.79%   |
| Volos          | 1         | 1.79%   |
| Vienna         | 1         | 1.79%   |
| Udine          | 1         | 1.79%   |
| Taggia         | 1         | 1.79%   |
| St Petersburg  | 1         | 1.79%   |
| Saskatoon      | 1         | 1.79%   |
| San Diego      | 1         | 1.79%   |
| Saarlouis      | 1         | 1.79%   |
| Rosporden      | 1         | 1.79%   |
| Roseville      | 1         | 1.79%   |
| Rochester      | 1         | 1.79%   |
| Powder Springs | 1         | 1.79%   |
| Ottawa         | 1         | 1.79%   |
| Osasco         | 1         | 1.79%   |
| Normal         | 1         | 1.79%   |
| Mussolente     | 1         | 1.79%   |
| Munster        | 1         | 1.79%   |
| Munich         | 1         | 1.79%   |
| Moses Lake     | 1         | 1.79%   |
| Minsk          | 1         | 1.79%   |
| Minneapolis    | 1         | 1.79%   |
| Milwaukee      | 1         | 1.79%   |
| Milan          | 1         | 1.79%   |
| London         | 1         | 1.79%   |
| Lima           | 1         | 1.79%   |
| Lannion        | 1         | 1.79%   |
| Kent           | 1         | 1.79%   |
| Istanbul       | 1         | 1.79%   |
| Huercal Overa  | 1         | 1.79%   |
| Houston        | 1         | 1.79%   |
| Helsinki       | 1         | 1.79%   |
| Graniteville   | 1         | 1.79%   |
| Göttingen     | 1         | 1.79%   |
| Glendale       | 1         | 1.79%   |
| Gilmer         | 1         | 1.79%   |
| Freital        | 1         | 1.79%   |
| Florence       | 1         | 1.79%   |
| Colfontaine    | 1         | 1.79%   |
| Cambui         | 1         | 1.79%   |
| Brussels       | 1         | 1.79%   |
| Brisbane       | 1         | 1.79%   |
| Bratislava     | 1         | 1.79%   |
| Bradenton      | 1         | 1.79%   |
| Bindlach       | 1         | 1.79%   |
| Berlin         | 1         | 1.79%   |
| Bengaluru      | 1         | 1.79%   |
| Belo Horizonte | 1         | 1.79%   |
| Belgrade       | 1         | 1.79%   |
| Baku           | 1         | 1.79%   |
| Amsterdam      | 1         | 1.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 19     | 18.6%   |
| Samsung Electronics | 15        | 20     | 17.44%  |
| Seagate             | 10        | 12     | 11.63%  |
| Kingston            | 7         | 7      | 8.14%   |
| Crucial             | 6         | 10     | 6.98%   |
| Transcend           | 3         | 3      | 3.49%   |
| PNY                 | 3         | 4      | 3.49%   |
| LITEON              | 3         | 3      | 3.49%   |
| SK Hynix            | 2         | 2      | 2.33%   |
| SanDisk             | 2         | 2      | 2.33%   |
| DOGFISH             | 2         | 2      | 2.33%   |
| Corsair             | 2         | 2      | 2.33%   |
| Unknown             | 1         | 1      | 1.16%   |
| Toshiba             | 1         | 1      | 1.16%   |
| SPCC                | 1         | 1      | 1.16%   |
| OCZ                 | 1         | 1      | 1.16%   |
| Netac               | 1         | 1      | 1.16%   |
| Micron Technology   | 1         | 1      | 1.16%   |
| MAXTOR              | 1         | 1      | 1.16%   |
| Intel               | 1         | 1      | 1.16%   |
| Hitachi             | 1         | 1      | 1.16%   |
| GOODRAM             | 1         | 1      | 1.16%   |
| Gigabyte Technology | 1         | 1      | 1.16%   |
| GeIL                | 1         | 1      | 1.16%   |
| Fujitsu             | 1         | 1      | 1.16%   |
| Apple               | 1         | 2      | 1.16%   |
| Unknown             | 1         | 1      | 1.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37480G 480GB SSD      | 3         | 3.13%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 3.13%   |
| Seagate ST2000DM008-2FR102 2TB       | 2         | 2.08%   |
| Samsung SSD 860 EVO 500GB            | 2         | 2.08%   |
| Corsair MP400 2TB                    | 2         | 2.08%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 1.04%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 1.04%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1         | 1.04%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 1         | 1.04%   |
| WDC WD60EZRZ-00RWYB1 6TB             | 1         | 1.04%   |
| WDC WD60EFRX-68L0BN1 6TB             | 1         | 1.04%   |
| WDC WD5000LPLX-08ZNTT0 500GB         | 1         | 1.04%   |
| WDC WD5000LPCX-22VHAT0 500GB         | 1         | 1.04%   |
| WDC WD5000AAKS-40V6A0 500GB          | 1         | 1.04%   |
| WDC WD40EFRX-68WT0N0 4TB             | 1         | 1.04%   |
| WDC WD30EFRX-68AX9N0 3TB             | 1         | 1.04%   |
| WDC WD1600BEVT-60ZCT1 160GB          | 1         | 1.04%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 1.04%   |
| WDC WD10EZEX-08M2NA0 1TB             | 1         | 1.04%   |
| WDC WD10EVDS-63U8B1 1TB              | 1         | 1.04%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB   | 1         | 1.04%   |
| WDC PC SN730 NVMe 1024GB             | 1         | 1.04%   |
| WDC PC SN530 SDBPMPZ-512G-1001 512GB | 1         | 1.04%   |
| Unknown SDW32G  32GB                 | 1         | 1.04%   |
| Transcend TS256GSSD370S 256GB        | 1         | 1.04%   |
| Transcend TS128GSSD370S 128GB        | 1         | 1.04%   |
| Transcend TS128GMTS800 128GB SSD     | 1         | 1.04%   |
| Toshiba MQ01ABD075 752GB             | 1         | 1.04%   |
| SPCC Solid State Disk 256GB          | 1         | 1.04%   |
| SK Hynix HFM512GD3JX013N 512GB       | 1         | 1.04%   |
| SK Hynix HFM256GDJTNG-8310A 256GB    | 1         | 1.04%   |
| Seagate ST750LM022 HN-M750MBB 752GB  | 1         | 1.04%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 1.04%   |
| Seagate ST500LM000-1EJ162 500GB      | 1         | 1.04%   |
| Seagate ST4000DM004-2CV104 4TB       | 1         | 1.04%   |
| Seagate ST3360320AS 360GB            | 1         | 1.04%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 1         | 1.04%   |
| Seagate ST1000LM048-2E7172 1TB       | 1         | 1.04%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1         | 1.04%   |
| SanDisk SDSSDH3 1T00 1TB             | 1         | 1.04%   |
| SanDisk SD8SN8U-512G-1006 512GB SSD  | 1         | 1.04%   |
| Samsung SSD 980 PRO 1TB              | 1         | 1.04%   |
| Samsung SSD 970 PRO 512GB            | 1         | 1.04%   |
| Samsung SSD 970 EVO Plus 1TB         | 1         | 1.04%   |
| Samsung SSD 970 EVO 1TB              | 1         | 1.04%   |
| Samsung SSD 870 EVO 500GB            | 1         | 1.04%   |
| Samsung SSD 860 EVO M.2 250GB        | 1         | 1.04%   |
| Samsung SSD 860 EVO M.2 1TB          | 1         | 1.04%   |
| Samsung SSD 860 EVO 1TB              | 1         | 1.04%   |
| Samsung SSD 850 EVO 500GB            | 1         | 1.04%   |
| Samsung SSD 840 Series 120GB         | 1         | 1.04%   |
| Samsung SSD 840 PRO Series 256GB     | 1         | 1.04%   |
| Samsung SSD 840 EVO 250GB            | 1         | 1.04%   |
| Samsung MZVPW256HEGL-00000 256GB     | 1         | 1.04%   |
| Samsung MZVLW256HEHP-000L2 256GB     | 1         | 1.04%   |
| Samsung MZVL21T0HCLR-00BL7 1TB       | 1         | 1.04%   |
| Samsung HM500JI 500GB                | 1         | 1.04%   |
| Samsung HD501LJ 500GB                | 1         | 1.04%   |
| Samsung HD204UI 2TB                  | 1         | 1.04%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 12     | 37.04%  |
| WDC                 | 9         | 12     | 33.33%  |
| Samsung Electronics | 3         | 3      | 11.11%  |
| Toshiba             | 1         | 1      | 3.7%    |
| MAXTOR              | 1         | 1      | 3.7%    |
| Hitachi             | 1         | 1      | 3.7%    |
| Fujitsu             | 1         | 1      | 3.7%    |
| Apple               | 1         | 1      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 10     | 20.93%  |
| Kingston            | 6         | 6      | 13.95%  |
| Crucial             | 5         | 9      | 11.63%  |
| Transcend           | 3         | 3      | 6.98%   |
| LITEON              | 3         | 3      | 6.98%   |
| WDC                 | 2         | 2      | 4.65%   |
| SanDisk             | 2         | 2      | 4.65%   |
| PNY                 | 2         | 2      | 4.65%   |
| DOGFISH             | 2         | 2      | 4.65%   |
| SPCC                | 1         | 1      | 2.33%   |
| OCZ                 | 1         | 1      | 2.33%   |
| Netac               | 1         | 1      | 2.33%   |
| Micron Technology   | 1         | 1      | 2.33%   |
| Intel               | 1         | 1      | 2.33%   |
| GOODRAM             | 1         | 1      | 2.33%   |
| Gigabyte Technology | 1         | 1      | 2.33%   |
| GeIL                | 1         | 1      | 2.33%   |
| Apple               | 1         | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 35        | 48     | 44.3%   |
| HDD  | 24        | 32     | 30.38%  |
| NVMe | 18        | 20     | 22.78%  |
| MMC  | 2         | 2      | 2.53%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 44        | 80     | 68.75%  |
| NVMe | 18        | 20     | 28.13%  |
| MMC  | 2         | 2      | 3.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 35        | 47     | 58.33%  |
| 0.51-1.0   | 17        | 22     | 28.33%  |
| 1.01-2.0   | 4         | 5      | 6.67%   |
| 3.01-4.0   | 2         | 2      | 3.33%   |
| 2.01-3.0   | 1         | 1      | 1.67%   |
| 4.01-10.0  | 1         | 3      | 1.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 13        | 23.21%  |
| 101-250        | 13        | 23.21%  |
| 501-1000       | 9         | 16.07%  |
| 21-50          | 5         | 8.93%   |
| 1001-2000      | 5         | 8.93%   |
| More than 3000 | 3         | 5.36%   |
| 1-20           | 3         | 5.36%   |
| 51-100         | 3         | 5.36%   |
| 2001-3000      | 2         | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 23        | 41.07%  |
| 21-50          | 9         | 16.07%  |
| 51-100         | 7         | 12.5%   |
| 101-250        | 6         | 10.71%  |
| 251-500        | 4         | 7.14%   |
| 1001-2000      | 4         | 7.14%   |
| 501-1000       | 2         | 3.57%   |
| More than 3000 | 1         | 1.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WDS100T2B0A-00SM50 1TB SSD               | 1         | 1      | 10%     |
| WDC WD5000AAKS-40V6A0 500GB                  | 1         | 1      | 10%     |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 10%     |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 10%     |
| Seagate ST3360320AS 360GB                    | 1         | 1      | 10%     |
| Samsung Electronics SSD 850 EVO 500GB        | 1         | 1      | 10%     |
| Samsung Electronics SSD 840 Series 120GB     | 1         | 1      | 10%     |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 10%     |
| MAXTOR 4K040H2 40GB                          | 1         | 1      | 10%     |
| GOODRAM SSDPR-CL100-480-G3 480GB             | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 30%     |
| Samsung Electronics | 3         | 3      | 30%     |
| WDC                 | 2         | 2      | 20%     |
| MAXTOR              | 1         | 1      | 10%     |
| GOODRAM             | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 60%     |
| WDC     | 1         | 1      | 20%     |
| MAXTOR  | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 5         | 5      | 55.56%  |
| HDD  | 4         | 5      | 44.44%  |

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
| Works    | 51        | 90     | 82.26%  |
| Malfunc  | 9         | 10     | 14.52%  |
| Detected | 2         | 2      | 3.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 41        | 60.29%  |
| Samsung Electronics         | 6         | 8.82%   |
| Sandisk                     | 5         | 7.35%   |
| AMD                         | 5         | 7.35%   |
| Phison Electronics          | 3         | 4.41%   |
| SK Hynix                    | 2         | 2.94%   |
| ASMedia Technology          | 2         | 2.94%   |
| Silicon Image               | 1         | 1.47%   |
| Nvidia                      | 1         | 1.47%   |
| Micron/Crucial Technology   | 1         | 1.47%   |
| Kingston Technology Company | 1         | 1.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 8%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 5.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 5.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 4%      |
| Phison E12 NVMe Controller                                                     | 3         | 4%      |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 4%      |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 4%      |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 2.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 2.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 2.67%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 2.67%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 2.67%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2         | 2.67%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2         | 2.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 2.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 2.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 2.67%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2         | 2.67%   |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 2.67%   |
| SK Hynix Gold P31 SSD                                                          | 1         | 1.33%   |
| SK Hynix BC501 NVMe Solid State Drive                                          | 1         | 1.33%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1         | 1.33%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 1.33%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 1         | 1.33%   |
| Sandisk Non-Volatile memory controller                                         | 1         | 1.33%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                   | 1         | 1.33%   |
| Nvidia MCP78S [GeForce 8200] IDE                                               | 1         | 1.33%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 1.33%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 1.33%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.33%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 1         | 1.33%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 1.33%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 1.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 1.33%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.33%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1         | 1.33%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1         | 1.33%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 1.33%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 1         | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 1.33%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1         | 1.33%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 39        | 57.35%  |
| NVMe | 18        | 26.47%  |
| IDE  | 6         | 8.82%   |
| RAID | 5         | 7.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 46        | 82.14%  |
| AMD    | 10        | 17.86%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 3.57%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 3.57%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 3.57%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 3.57%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 3.57%   |
| Intel Xeon CPU W3565 @ 3.20GHz                | 1         | 1.79%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz           | 1         | 1.79%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 1.79%   |
| Intel Pentium M processor 1.80GHz             | 1         | 1.79%   |
| Intel Core i9-10850K CPU @ 3.60GHz            | 1         | 1.79%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.79%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.79%   |
| Intel Core i7-5820K CPU @ 3.30GHz             | 1         | 1.79%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 1.79%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 1.79%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 1.79%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 1.79%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.79%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.79%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 1.79%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 1         | 1.79%   |
| Intel Core i5-4690K CPU @ 3.50GHz             | 1         | 1.79%   |
| Intel Core i5-4570T CPU @ 2.90GHz             | 1         | 1.79%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 1         | 1.79%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 1.79%   |
| Intel Core i5-2400S CPU @ 2.50GHz             | 1         | 1.79%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 1.79%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 1.79%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 1         | 1.79%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 1.79%   |
| Intel Core i3-2328M CPU @ 2.20GHz             | 1         | 1.79%   |
| Intel Core i3 CPU 540 @ 3.07GHz               | 1         | 1.79%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 1.79%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz          | 1         | 1.79%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 1         | 1.79%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz          | 1         | 1.79%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 1.79%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 1.79%   |
| Intel Atom CPU Z520 @ 1.33GHz                 | 1         | 1.79%   |
| Intel Atom CPU Z3735G @ 1.33GHz               | 1         | 1.79%   |
| Intel 11th Gen Core i9-11980HK @ 2.60GHz      | 1         | 1.79%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 1.79%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.79%   |
| AMD Sempron SI-42                             | 1         | 1.79%   |
| AMD Ryzen Threadripper PRO 3945WX 12-Cores    | 1         | 1.79%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 1         | 1.79%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 1.79%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 1.79%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 1         | 1.79%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 1         | 1.79%   |
| AMD Ryzen 3 3100 4-Core Processor             | 1         | 1.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 14        | 25%     |
| Intel Core i5          | 12        | 21.43%  |
| AMD Ryzen 7            | 5         | 8.93%   |
| Intel Core i3          | 4         | 7.14%   |
| Intel Core 2 Duo       | 4         | 7.14%   |
| Other                  | 3         | 5.36%   |
| Intel Xeon             | 2         | 3.57%   |
| Intel Celeron          | 2         | 3.57%   |
| Intel Atom             | 2         | 3.57%   |
| AMD Ryzen 5            | 2         | 3.57%   |
| Intel Pentium Silver   | 1         | 1.79%   |
| Intel Pentium M        | 1         | 1.79%   |
| Intel Core i9          | 1         | 1.79%   |
| AMD Sempron            | 1         | 1.79%   |
| AMD Ryzen Threadripper | 1         | 1.79%   |
| AMD Ryzen 3            | 1         | 1.79%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 21        | 37.5%   |
| 2      | 20        | 35.71%  |
| 8      | 5         | 8.93%   |
| 6      | 4         | 7.14%   |
| 1      | 3         | 5.36%   |
| 12     | 2         | 3.57%   |
| 10     | 1         | 1.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 56        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 42        | 75%     |
| 1      | 14        | 25%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 54        | 96.43%  |
| 32-bit         | 2         | 3.57%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 6         | 10.71%  |
| 0x306a9    | 5         | 8.93%   |
| 0x406e3    | 3         | 5.36%   |
| 0x306c3    | 3         | 5.36%   |
| 0x206a7    | 3         | 5.36%   |
| 0x20655    | 3         | 5.36%   |
| 0x806ea    | 2         | 3.57%   |
| 0x806c1    | 2         | 3.57%   |
| 0x6fd      | 2         | 3.57%   |
| 0x506e3    | 2         | 3.57%   |
| 0x30678    | 2         | 3.57%   |
| 0x0a50000c | 2         | 3.57%   |
| 0xa0655    | 1         | 1.79%   |
| 0x906ed    | 1         | 1.79%   |
| 0x806ec    | 1         | 1.79%   |
| 0x806eb    | 1         | 1.79%   |
| 0x806d1    | 1         | 1.79%   |
| 0x706a8    | 1         | 1.79%   |
| 0x706a1    | 1         | 1.79%   |
| 0x6fb      | 1         | 1.79%   |
| 0x6d6      | 1         | 1.79%   |
| 0x306f2    | 1         | 1.79%   |
| 0x106e5    | 1         | 1.79%   |
| 0x106c2    | 1         | 1.79%   |
| 0x1067a    | 1         | 1.79%   |
| 0x0a201016 | 1         | 1.79%   |
| 0x0a201009 | 1         | 1.79%   |
| 0x08701021 | 1         | 1.79%   |
| 0x08608103 | 1         | 1.79%   |
| 0x08301039 | 1         | 1.79%   |
| 0x08108102 | 1         | 1.79%   |
| 0x0800820d | 1         | 1.79%   |
| 0x02000057 | 1         | 1.79%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Haswell         | 7         | 12.5%   |
| Skylake         | 5         | 8.93%   |
| KabyLake        | 5         | 8.93%   |
| IvyBridge       | 5         | 8.93%   |
| Zen 3           | 4         | 7.14%   |
| Westmere        | 4         | 7.14%   |
| SandyBridge     | 4         | 7.14%   |
| Core            | 3         | 5.36%   |
| Zen+            | 2         | 3.57%   |
| Zen 2           | 2         | 3.57%   |
| TigerLake       | 2         | 3.57%   |
| Silvermont      | 2         | 3.57%   |
| Nehalem         | 2         | 3.57%   |
| Goldmont plus   | 2         | 3.57%   |
| Penryn          | 1         | 1.79%   |
| P6              | 1         | 1.79%   |
| K8 & K10 hybrid | 1         | 1.79%   |
| Icelake         | 1         | 1.79%   |
| CometLake       | 1         | 1.79%   |
| Bonnell         | 1         | 1.79%   |
| Unknown         | 1         | 1.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 36        | 50.7%   |
| Nvidia | 19        | 26.76%  |
| AMD    | 16        | 22.54%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                            | 5         | 6.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4         | 5.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 3         | 4.05%   |
| Nvidia GM107M [GeForce GTX 960M]                                            | 2         | 2.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 2.7%    |
| Intel UHD Graphics 620                                                      | 2         | 2.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 2         | 2.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 2         | 2.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 2         | 2.7%    |
| Intel HD Graphics 530                                                       | 2         | 2.7%    |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 2.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2         | 2.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 2.7%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 2         | 2.7%    |
| AMD Cezanne                                                                 | 2         | 2.7%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 1.35%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1         | 1.35%   |
| Nvidia GT216M [GeForce GT 330M]                                             | 1         | 1.35%   |
| Nvidia GP108M [GeForce MX250]                                               | 1         | 1.35%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1         | 1.35%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 1.35%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1         | 1.35%   |
| Nvidia GM108M [GeForce MX110]                                               | 1         | 1.35%   |
| Nvidia GM107M [GeForce GTX 950M]                                            | 1         | 1.35%   |
| Nvidia GK106GLM [Quadro K2100M]                                             | 1         | 1.35%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1         | 1.35%   |
| Nvidia GF108M [GeForce GT 550M]                                             | 1         | 1.35%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 1         | 1.35%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 1         | 1.35%   |
| Nvidia G94GL [Quadro FX 1800]                                               | 1         | 1.35%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 1         | 1.35%   |
| Nvidia C77 [GeForce 8200M G]                                                | 1         | 1.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 1         | 1.35%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                         | 1         | 1.35%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 1         | 1.35%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 1         | 1.35%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1         | 1.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 1         | 1.35%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1         | 1.35%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1         | 1.35%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                      | 1         | 1.35%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                   | 1         | 1.35%   |
| AMD RV730/M96-XT [Mobility Radeon HD 4670]                                  | 1         | 1.35%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]               | 1         | 1.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1         | 1.35%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1         | 1.35%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                    | 1         | 1.35%   |
| AMD Lucienne                                                                | 1         | 1.35%   |
| AMD Lexa XT [Radeon PRO WX 3200]                                            | 1         | 1.35%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1         | 1.35%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                          | 1         | 1.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1         | 1.35%   |
| AMD Cedar [Radeon HD 7350/8350 / R5 220]                                    | 1         | 1.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 23        | 41.07%  |
| 1 x AMD        | 11        | 19.64%  |
| Intel + Nvidia | 9         | 16.07%  |
| 1 x Nvidia     | 8         | 14.29%  |
| Intel + AMD    | 2         | 3.57%   |
| AMD + Nvidia   | 2         | 3.57%   |
| 2 x AMD        | 1         | 1.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 45        | 80.36%  |
| Proprietary | 10        | 17.86%  |
| Unknown     | 1         | 1.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 62.5%   |
| 7.01-8.0   | 5         | 8.93%   |
| 3.01-4.0   | 5         | 8.93%   |
| 0.01-0.5   | 5         | 8.93%   |
| 0.51-1.0   | 4         | 7.14%   |
| 8.01-16.0  | 2         | 3.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 7         | 10.94%  |
| Chimei Innolux          | 7         | 10.94%  |
| AU Optronics            | 7         | 10.94%  |
| LG Display              | 6         | 9.38%   |
| Ancor Communications    | 4         | 6.25%   |
| Dell                    | 3         | 4.69%   |
| BOE                     | 3         | 4.69%   |
| Sony                    | 2         | 3.13%   |
| Sharp                   | 2         | 3.13%   |
| Philips                 | 2         | 3.13%   |
| Medion                  | 2         | 3.13%   |
| Fujitsu Siemens         | 2         | 3.13%   |
| Chi Mei Optoelectronics | 2         | 3.13%   |
| Apple                   | 2         | 3.13%   |
| Acer                    | 2         | 3.13%   |
| Vizio                   | 1         | 1.56%   |
| PANDA                   | 1         | 1.56%   |
| Panasonic               | 1         | 1.56%   |
| NEC Computers           | 1         | 1.56%   |
| Lenovo                  | 1         | 1.56%   |
| Iiyama                  | 1         | 1.56%   |
| Grundig                 | 1         | 1.56%   |
| Goldstar                | 1         | 1.56%   |
| Gigabyte Technology     | 1         | 1.56%   |
| CPT                     | 1         | 1.56%   |
| AOC                     | 1         | 1.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                     | 2         | 3.13%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 3.13%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 3.13%   |
| Vizio M220MV VIZ0062 1920x1080 480x270mm 21.7-inch                       | 1         | 1.56%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch     | 1         | 1.56%   |
| Sony LCD Monitor MS_0025 1920x1080 340x190mm 15.3-inch                   | 1         | 1.56%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 1.56%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 1.56%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                         | 1         | 1.56%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch        | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC4245 1280x800 331x207mm 15.4-inch     | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 344x194mm 15.5-inch     | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 1         | 1.56%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 700x390mm 31.5-inch        | 1         | 1.56%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 1         | 1.56%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch                 | 1         | 1.56%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 1         | 1.56%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 1         | 1.56%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 344x193mm 15.5-inch             | 1         | 1.56%   |
| NEC Computers EA221WM NEC673D 1680x1050 474x296mm 22.0-inch              | 1         | 1.56%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 1         | 1.56%   |
| LG Display LCD Monitor LGD0570 1920x1080 344x194mm 15.5-inch             | 1         | 1.56%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch              | 1         | 1.56%   |
| LG Display LCD Monitor LGD024D 1366x768 294x166mm 13.3-inch              | 1         | 1.56%   |
| Lenovo LEN T2454pA LEN60C9 1920x1200 518x324mm 24.1-inch                 | 1         | 1.56%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                    | 1         | 1.56%   |
| Grundig TV GRU4448 1920x1080 1210x680mm 54.6-inch                        | 1         | 1.56%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch               | 1         | 1.56%   |
| Gigabyte Technology G34WQC GBT3400 3440x1440 800x330mm 34.1-inch         | 1         | 1.56%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch         | 1         | 1.56%   |
| Fujitsu Siemens B22W-5 ECO FUS07C3 1680x1050 474x296mm 22.0-inch         | 1         | 1.56%   |
| Dell U2719D DEL415A 2560x1440 597x336mm 27.0-inch                        | 1         | 1.56%   |
| Dell SR2320L DELF03A 1920x1080 510x290mm 23.1-inch                       | 1         | 1.56%   |
| Dell S3422DW DELD103 3440x1440 800x330mm 34.1-inch                       | 1         | 1.56%   |
| CPT LCD Monitor CPT1C21 1366x768 256x144mm 11.6-inch                     | 1         | 1.56%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C03 2160x1440 296x197mm 14.0-inch         | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch          | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN1402 1920x1080 309x173mm 13.9-inch         | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 1.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 1.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 1         | 1.56%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 1         | 1.56%   |
| BOE LCD Monitor BOE0714 1920x1080 344x193mm 15.5-inch                    | 1         | 1.56%   |
| BOE LCD Monitor BOE05DF 1366x768 293x165mm 13.2-inch                     | 1         | 1.56%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch           | 1         | 1.56%   |
| AU Optronics LCD Monitor AUO5A2D 1920x1080 293x165mm 13.2-inch           | 1         | 1.56%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 1.56%   |
| AU Optronics LCD Monitor AUO333C 1366x768 309x173mm 13.9-inch            | 1         | 1.56%   |
| AU Optronics LCD Monitor AUO30EB 3840x2160 344x193mm 15.5-inch           | 1         | 1.56%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 1         | 1.56%   |
| AU Optronics LCD Monitor AUO123E 1600x900 309x174mm 14.0-inch            | 1         | 1.56%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 1         | 1.56%   |
| Apple iMac APPA00C 1920x1080 475x267mm 21.5-inch                         | 1         | 1.56%   |
| AOC U2790B AOC2790 3840x2160 597x336mm 27.0-inch                         | 1         | 1.56%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch         | 1         | 1.56%   |
| Ancor Communications BE24A ACI24AB 1920x1200 520x320mm 24.0-inch         | 1         | 1.56%   |
| Ancor Communications ASUS VW193S ACI19D4 1440x900 408x255mm 18.9-inch    | 1         | 1.56%   |
| Ancor Communications ASUS VC239 ACI23C4 1920x1080 509x286mm 23.0-inch    | 1         | 1.56%   |
| Acer SB220Q ACR06AB 1920x1080 476x268mm 21.5-inch                        | 1         | 1.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 23        | 38.33%  |
| 1366x768 (WXGA)    | 12        | 20%     |
| 3840x2160 (4K)     | 6         | 10%     |
| 2560x1440 (QHD)    | 4         | 6.67%   |
| 3440x1440          | 2         | 3.33%   |
| 1680x1050 (WSXGA+) | 2         | 3.33%   |
| 1600x900 (HD+)     | 2         | 3.33%   |
| 1280x800 (WXGA)    | 2         | 3.33%   |
| 3840x2400          | 1         | 1.67%   |
| 2560x1080          | 1         | 1.67%   |
| 2256x1504          | 1         | 1.67%   |
| 2160x1440          | 1         | 1.67%   |
| 1920x1200 (WUXGA)  | 1         | 1.67%   |
| 1440x900 (WXGA+)   | 1         | 1.67%   |
| 1280x1024 (SXGA)   | 1         | 1.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 19        | 30.16%  |
| 27      | 6         | 9.52%   |
| 13      | 6         | 9.52%   |
| 24      | 4         | 6.35%   |
| 23      | 4         | 6.35%   |
| 17      | 4         | 6.35%   |
| 14      | 4         | 6.35%   |
| 34      | 3         | 4.76%   |
| 31      | 3         | 4.76%   |
| 22      | 2         | 3.17%   |
| 21      | 2         | 3.17%   |
| 11      | 2         | 3.17%   |
| 54      | 1         | 1.59%   |
| 26      | 1         | 1.59%   |
| 19      | 1         | 1.59%   |
| Unknown | 1         | 1.59%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 24        | 38.1%   |
| 501-600     | 15        | 23.81%  |
| 201-300     | 7         | 11.11%  |
| 401-500     | 5         | 7.94%   |
| 351-400     | 4         | 6.35%   |
| 701-800     | 3         | 4.76%   |
| 601-700     | 3         | 4.76%   |
| 1001-1500   | 1         | 1.59%   |
| Unknown     | 1         | 1.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 44        | 75.86%  |
| 16/10 | 8         | 13.79%  |
| 21/9  | 3         | 5.17%   |
| 3/2   | 2         | 3.45%   |
| 5/4   | 1         | 1.72%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 19        | 30.16%  |
| 201-250        | 10        | 15.87%  |
| 81-90          | 8         | 12.7%   |
| 351-500        | 6         | 9.52%   |
| 301-350        | 6         | 9.52%   |
| 251-300        | 3         | 4.76%   |
| 121-130        | 3         | 4.76%   |
| 71-80          | 2         | 3.17%   |
| 51-60          | 2         | 3.17%   |
| More than 1000 | 1         | 1.59%   |
| 151-200        | 1         | 1.59%   |
| 141-150        | 1         | 1.59%   |
| Unknown        | 1         | 1.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 23        | 38.98%  |
| 101-120       | 14        | 23.73%  |
| 121-160       | 13        | 22.03%  |
| More than 240 | 4         | 6.78%   |
| 161-240       | 4         | 6.78%   |
| Unknown       | 1         | 1.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 42        | 75%     |
| 2     | 11        | 19.64%  |
| 3     | 2         | 3.57%   |
| 0     | 1         | 1.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 28        | 34.15%  |
| Realtek Semiconductor    | 20        | 24.39%  |
| Qualcomm Atheros         | 14        | 17.07%  |
| Broadcom                 | 6         | 7.32%   |
| Marvell Technology Group | 4         | 4.88%   |
| TP-Link                  | 3         | 3.66%   |
| Ralink Technology        | 1         | 1.22%   |
| Nvidia                   | 1         | 1.22%   |
| MEDIATEK                 | 1         | 1.22%   |
| Edimax Technology        | 1         | 1.22%   |
| Dell                     | 1         | 1.22%   |
| Broadcom Limited         | 1         | 1.22%   |
| Aquantia                 | 1         | 1.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 17        | 17.35%  |
| Intel Wireless 8260                                                            | 4         | 4.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 3         | 3.06%   |
| Intel Wi-Fi 6 AX200                                                            | 3         | 3.06%   |
| Intel I211 Gigabit Network Connection                                          | 3         | 3.06%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 3.06%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 2         | 2.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 2         | 2.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 2.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2         | 2.04%   |
| Intel Wireless 8265 / 8275                                                     | 2         | 2.04%   |
| Intel Wireless 7260                                                            | 2         | 2.04%   |
| Intel Ethernet Connection I219-V                                               | 2         | 2.04%   |
| Intel Centrino Advanced-N 6200                                                 | 2         | 2.04%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 2.04%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 2.04%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 1.02%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 1         | 1.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 1.02%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                            | 1         | 1.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 1.02%   |
| Ralink RT2070 Wireless Adapter                                                 | 1         | 1.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 1         | 1.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 1         | 1.02%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 1.02%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 1.02%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1         | 1.02%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 1         | 1.02%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 1.02%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 1         | 1.02%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.02%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 1.02%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 1         | 1.02%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 1.02%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter                  | 1         | 1.02%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.02%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 1.02%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 1.02%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 1.02%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 1         | 1.02%   |
| Intel Wi-Fi 6 AX201                                                            | 1         | 1.02%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 1         | 1.02%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 1         | 1.02%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 1         | 1.02%   |
| Intel Ethernet Controller I225-V                                               | 1         | 1.02%   |
| Intel Ethernet Connection I217-V                                               | 1         | 1.02%   |
| Intel Ethernet Connection (2) I218-V                                           | 1         | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 1         | 1.02%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 1         | 1.02%   |
| Intel Centrino Advanced-N 6235                                                 | 1         | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 1         | 1.02%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1         | 1.02%   |
| Edimax RTL8192S WLAN Adapter                                                   | 1         | 1.02%   |
| Dell F3607gw v2 Mobile Broadband Module                                        | 1         | 1.02%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 1         | 1.02%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 1.02%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                     | 1         | 1.02%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                             | 1         | 1.02%   |
| Broadcom BCM4331 802.11a/b/g/n                                                 | 1         | 1.02%   |
| Broadcom BCM4321 802.11a/b/g/n                                                 | 1         | 1.02%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 46.81%  |
| Qualcomm Atheros      | 11        | 23.4%   |
| Realtek Semiconductor | 5         | 10.64%  |
| Broadcom              | 3         | 6.38%   |
| TP-Link               | 2         | 4.26%   |
| Ralink Technology     | 1         | 2.13%   |
| MEDIATEK              | 1         | 2.13%   |
| Edimax Technology     | 1         | 2.13%   |
| Broadcom Limited      | 1         | 2.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                                     | 4         | 8.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 6.38%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 6.38%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 4.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 4.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 4.26%   |
| Intel Wireless 8265 / 8275                                              | 2         | 4.26%   |
| Intel Wireless 7260                                                     | 2         | 4.26%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 4.26%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 2.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 2.13%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 2.13%   |
| Ralink RT2070 Wireless Adapter                                          | 1         | 2.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 2.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 2.13%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 2.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 2.13%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 2.13%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 2.13%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 2.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 2.13%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 2.13%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 2.13%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 2.13%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 2.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 2.13%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 2.13%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 2.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 2.13%   |
| Edimax RTL8192S WLAN Adapter                                            | 1         | 2.13%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 1         | 2.13%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1         | 2.13%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 1         | 2.13%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 1         | 2.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 19        | 39.58%  |
| Intel                    | 13        | 27.08%  |
| Qualcomm Atheros         | 5         | 10.42%  |
| Marvell Technology Group | 4         | 8.33%   |
| Broadcom                 | 4         | 8.33%   |
| TP-Link                  | 1         | 2.08%   |
| Nvidia                   | 1         | 2.08%   |
| Aquantia                 | 1         | 2.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 17        | 34%     |
| Intel I211 Gigabit Network Connection                                          | 3         | 6%      |
| Intel Ethernet Connection I217-LM                                              | 3         | 6%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 4%      |
| Intel Ethernet Connection I219-V                                               | 2         | 4%      |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 4%      |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 4%      |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 2%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 2%      |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 2%      |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 2%      |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1         | 2%      |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 2%      |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 2%      |
| Nvidia MCP77 Ethernet                                                          | 1         | 2%      |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 2%      |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 2%      |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 2%      |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 2%      |
| Intel Ethernet Controller I225-V                                               | 1         | 2%      |
| Intel Ethernet Connection I217-V                                               | 1         | 2%      |
| Intel Ethernet Connection (2) I218-V                                           | 1         | 2%      |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1         | 2%      |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 1         | 2%      |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 2%      |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 1         | 2%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 47        | 51.09%  |
| WiFi     | 44        | 47.83%  |
| Modem    | 1         | 1.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 37        | 61.67%  |
| Ethernet | 22        | 36.67%  |
| Modem    | 1         | 1.67%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 33        | 58.93%  |
| 1     | 21        | 37.5%   |
| 3     | 1         | 1.79%   |
| 0     | 1         | 1.79%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 42        | 75%     |
| Yes  | 14        | 25%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 37.14%  |
| Apple                           | 5         | 14.29%  |
| Qualcomm Atheros Communications | 4         | 11.43%  |
| Foxconn / Hon Hai               | 3         | 8.57%   |
| Realtek Semiconductor           | 2         | 5.71%   |
| IMC Networks                    | 2         | 5.71%   |
| Cambridge Silicon Radio         | 2         | 5.71%   |
| ASUSTek Computer                | 2         | 5.71%   |
| Hewlett-Packard                 | 1         | 2.86%   |
| Dell                            | 1         | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 6         | 17.14%  |
| Intel AX200 Bluetooth                                                               | 3         | 8.57%   |
| Realtek Bluetooth Radio                                                             | 2         | 5.71%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 5.71%   |
| Intel AX201 Bluetooth                                                               | 2         | 5.71%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 5.71%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 5.71%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 5.71%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 5.71%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 2.86%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 2.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 1         | 2.86%   |
| Intel AX210 Bluetooth                                                               | 1         | 2.86%   |
| IMC Networks Wireless_Device                                                        | 1         | 2.86%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 2.86%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 2.86%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 2.86%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 2.86%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 2.86%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                               | 1         | 2.86%   |
| Apple Bluetooth HCI                                                                 | 1         | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 44        | 55%     |
| AMD                 | 15        | 18.75%  |
| Nvidia              | 12        | 15%     |
| ROCCAT              | 2         | 2.5%    |
| Creative Labs       | 2         | 2.5%    |
| Unknown             | 1         | 1.25%   |
| Razer USA           | 1         | 1.25%   |
| Plantronics         | 1         | 1.25%   |
| C-Media Electronics | 1         | 1.25%   |
| Unknown             | 1         | 1.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 6.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 5.38%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 5.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 5.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 4.3%    |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 4.3%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 3.23%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 3.23%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 3.23%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 3.23%   |
| ROCCAT Khan AIMO                                                           | 2         | 2.15%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 2.15%   |
| Nvidia Audio device                                                        | 2         | 2.15%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 2.15%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.15%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2         | 2.15%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 2.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 2.15%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 2         | 2.15%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2         | 2.15%   |
| Unknown Realtek USB Audio Rear                                             | 1         | 1.08%   |
| Unknown Realtek USB Audio Front                                            | 1         | 1.08%   |
| Razer USA Razer Kraken Tournament Edition                                  | 1         | 1.08%   |
| Plantronics BT600                                                          | 1         | 1.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.08%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 1.08%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 1         | 1.08%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.08%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.08%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.08%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 1.08%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.08%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1         | 1.08%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.08%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.08%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.08%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1         | 1.08%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1         | 1.08%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 1.08%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 1         | 1.08%   |
| C-Media Electronics USB Advanced Audio Device                              | 1         | 1.08%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1         | 1.08%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 1.08%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 1.08%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                      | 1         | 1.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 1.08%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 1.08%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 1.08%   |
| Unknown                                                                    | 1         | 1.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 14        | 22.22%  |
| Unknown             | 12        | 19.05%  |
| SK Hynix            | 10        | 15.87%  |
| Kingston            | 5         | 7.94%   |
| Corsair             | 5         | 7.94%   |
| Micron Technology   | 4         | 6.35%   |
| G.Skill             | 3         | 4.76%   |
| Crucial             | 3         | 4.76%   |
| Smart               | 2         | 3.17%   |
| Unknown (ABCD)      | 1         | 1.59%   |
| PNY                 | 1         | 1.59%   |
| Elpida              | 1         | 1.59%   |
| Avant               | 1         | 1.59%   |
| Unknown             | 1         | 1.59%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3                                  | 3         | 4.41%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 2.94%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 2         | 2.94%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                         | 2         | 2.94%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 2.94%   |
| Corsair RAM CMK32GX4M2B3200C16 16384MB DIMM DDR4 3400MT/s           | 2         | 2.94%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 1         | 1.47%   |
| Unknown RAM Module 8GB SODIMM DDR3                                  | 1         | 1.47%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                          | 1         | 1.47%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                         | 1         | 1.47%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 1         | 1.47%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 1         | 1.47%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                            | 1         | 1.47%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 1.47%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                         | 1         | 1.47%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                          | 1         | 1.47%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 1.47%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s               | 1         | 1.47%   |
| Smart RAM SF4641G8CK8IEGKSBG 8GB SODIMM DDR4 2400MT/s               | 1         | 1.47%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.47%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 1.47%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| SK Hynix RAM HMT351S6EFR8A 4096MB SODIMM DDR3 1600MT/s              | 1         | 1.47%   |
| SK Hynix RAM HMT351S6AFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 1.47%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s           | 1         | 1.47%   |
| SK Hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s              | 1         | 1.47%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s           | 1         | 1.47%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4096MB SODIMM DDR4 2133MT/s           | 1         | 1.47%   |
| SK Hynix RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s              | 1         | 1.47%   |
| Samsung RAM Module 4GB SODIMM DDR2 667MT/s                          | 1         | 1.47%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s            | 1         | 1.47%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 1         | 1.47%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 1         | 1.47%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 1         | 1.47%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 1         | 1.47%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s                | 1         | 1.47%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s                | 1         | 1.47%   |
| PNY RAM Module 8GB SODIMM DDR3 1333MT/s                             | 1         | 1.47%   |
| Micron RAM Module 8GB SODIMM DDR3 1600MT/s                          | 1         | 1.47%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s              | 1         | 1.47%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s               | 1         | 1.47%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s              | 1         | 1.47%   |
| Kingston RAM KHX3200C16D4/4GX 4GB DIMM DDR4 3600MT/s                | 1         | 1.47%   |
| Kingston RAM HP594908-HR1-ELD 2GB SODIMM DDR3 1333MT/s              | 1         | 1.47%   |
| Kingston RAM 99U5471-033.A00LF 4096MB DIMM DDR3                     | 1         | 1.47%   |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 1600MT/s             | 1         | 1.47%   |
| Kingston RAM 99U5428-041.A01LF 4GB SODIMM DDR3 1067MT/s             | 1         | 1.47%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s             | 1         | 1.47%   |
| G.Skill RAM F4-4000C18-16GTZR 16GB DIMM DDR4 2133MT/s               | 1         | 1.47%   |
| G.Skill RAM F3-2133C11-8GAR 8GB DIMM DDR3 2133MT/s                  | 1         | 1.47%   |
| G.Skill RAM F3-10666CL9-4GBNT 4096MB DIMM DDR3 1400MT/s             | 1         | 1.47%   |
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                          | 1         | 1.47%   |
| Crucial RAM Module 4GB SODIMM DDR3 1333MT/s                         | 1         | 1.47%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 1         | 1.47%   |
| Crucial RAM BLS8G4S240FSDK.8FBD 8GB SODIMM DDR4 2400MT/s            | 1         | 1.47%   |
| Corsair RAM CMK32GX4M4A2666C16 8192MB DIMM 2667MT/s                 | 1         | 1.47%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s            | 1         | 1.47%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s               | 1         | 1.47%   |
| Avant RAM J644GU44J2320NQ 32GB SODIMM DDR4 3200MT/s                 | 1         | 1.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 24        | 43.64%  |
| DDR3   | 23        | 41.82%  |
| DDR2   | 4         | 7.27%   |
| SDRAM  | 1         | 1.82%   |
| LPDDR4 | 1         | 1.82%   |
| DRAM   | 1         | 1.82%   |
| DDR    | 1         | 1.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 40        | 74.07%  |
| DIMM         | 13        | 24.07%  |
| Row Of Chips | 1         | 1.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 24        | 40%     |
| 4096  | 16        | 26.67%  |
| 2048  | 11        | 18.33%  |
| 32768 | 3         | 5%      |
| 16384 | 3         | 5%      |
| 1024  | 3         | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 10        | 17.54%  |
| 3200    | 7         | 12.28%  |
| 1333    | 7         | 12.28%  |
| 2133    | 6         | 10.53%  |
| Unknown | 5         | 8.77%   |
| 2667    | 4         | 7.02%   |
| 2400    | 4         | 7.02%   |
| 667     | 3         | 5.26%   |
| 3600    | 2         | 3.51%   |
| 3400    | 2         | 3.51%   |
| 4199    | 1         | 1.75%   |
| 3466    | 1         | 1.75%   |
| 1400    | 1         | 1.75%   |
| 1334    | 1         | 1.75%   |
| 1067    | 1         | 1.75%   |
| 333     | 1         | 1.75%   |
| 166     | 1         | 1.75%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| HP LaserJet P2055 series | 1         | 50%     |
| Canon MF641C             | 1         | 50%     |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 8         | 22.22%  |
| Logitech                      | 4         | 11.11%  |
| Realtek Semiconductor         | 3         | 8.33%   |
| Microdia                      | 3         | 8.33%   |
| Acer                          | 3         | 8.33%   |
| Lite-On Technology            | 2         | 5.56%   |
| IMC Networks                  | 2         | 5.56%   |
| Apple                         | 2         | 5.56%   |
| Z-Star Microelectronics       | 1         | 2.78%   |
| Suyin                         | 1         | 2.78%   |
| Sunplus Innovation Technology | 1         | 2.78%   |
| Silicon Motion                | 1         | 2.78%   |
| Ricoh                         | 1         | 2.78%   |
| Primax Electronics            | 1         | 2.78%   |
| Goodong Industry              | 1         | 2.78%   |
| Generalplus Technology        | 1         | 2.78%   |
| 8SSC20F27145V1SR18P0H10       | 1         | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Logitech Webcam C930e                      | 2         | 5.56%   |
| Z-Star Venus USB2.0 Camera                 | 1         | 2.78%   |
| Suyin Sony Visual Communication Camera     | 1         | 2.78%   |
| Sunplus Integrated_Webcam_HD               | 1         | 2.78%   |
| Silicon Motion Web Camera                  | 1         | 2.78%   |
| Ricoh USB2.0 Camera                        | 1         | 2.78%   |
| Realtek USB Camera                         | 1         | 2.78%   |
| Realtek Lenovo EasyCamera                  | 1         | 2.78%   |
| Realtek Integrated Webcam                  | 1         | 2.78%   |
| Primax Dell Laptop Integrated Webcam 2Mpix | 1         | 2.78%   |
| Microdia Webcam Vitade AF                  | 1         | 2.78%   |
| Microdia WebCam SC-13HDL12639P             | 1         | 2.78%   |
| Microdia Webcam                            | 1         | 2.78%   |
| Logitech Webcam C270                       | 1         | 2.78%   |
| Logitech StreamCam                         | 1         | 2.78%   |
| Lite-On HP HD Webcam                       | 1         | 2.78%   |
| Lite-On HP HD Camera                       | 1         | 2.78%   |
| IMC Networks USB2.0 UVC 1.3M WebCam        | 1         | 2.78%   |
| IMC Networks USB2.0 HD UVC WebCam          | 1         | 2.78%   |
| Goodong Industry USB2.0 HD UVC WebCam      | 1         | 2.78%   |
| Generalplus GENERAL WEBCAM                 | 1         | 2.78%   |
| Chicony USB2.0 HD UVC WebCam               | 1         | 2.78%   |
| Chicony USB 2.0 Camera                     | 1         | 2.78%   |
| Chicony Sony Visual Communication Camera   | 1         | 2.78%   |
| Chicony Lenovo EasyCamera                  | 1         | 2.78%   |
| Chicony Integrated Camera                  | 1         | 2.78%   |
| Chicony HP Wide Vision FHD Camera          | 1         | 2.78%   |
| Chicony HP Webcam [2 MP Macro]             | 1         | 2.78%   |
| Chicony 2.0M UVC WebCam                    | 1         | 2.78%   |
| Apple FaceTime HD Camera (Built-in)        | 1         | 2.78%   |
| Apple Built-in iSight                      | 1         | 2.78%   |
| Acer SunplusIT INC. Integrated Camera      | 1         | 2.78%   |
| Acer Integrated Camera                     | 1         | 2.78%   |
| Acer BisonCam, NB Pro                      | 1         | 2.78%   |
| 8SSC20F27145V1SR18P0H10 Integrated Camera  | 1         | 2.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 42.86%  |
| Shenzhen Goodix Technology | 3         | 42.86%  |
| Synaptics                  | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 2         | 28.57%  |
| Shenzhen Goodix  FingerPrint Device          | 2         | 28.57%  |
| Validity Sensors VFS495 Fingerprint Reader   | 1         | 14.29%  |
| Shenzhen Goodix Fingerprint Reader           | 1         | 14.29%  |
| Unknown                                      | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 38        | 67.86%  |
| 1     | 15        | 26.79%  |
| 2     | 3         | 5.36%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Graphics card      | 9         | 47.37%  |
| Fingerprint reader | 7         | 36.84%  |
| Unassigned class   | 2         | 10.53%  |
| Chipcard           | 1         | 5.26%   |

