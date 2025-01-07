CentOS 9 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for CentOS 9.

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

Total: 47

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 18E7                        | [4ed0c6182c](https://linux-hardware.org/?probe=4ed0c6182c) | Dec 21, 2024 |
| ASUSTek       | P8H61/USB3                  | [6d27d6c54c](https://linux-hardware.org/?probe=6d27d6c54c) | Nov 22, 2024 |
| ASUSTek       | P8H61/USB3                  | [90ebd3b804](https://linux-hardware.org/?probe=90ebd3b804) | Nov 22, 2024 |
| ASUSTek       | P8H61/USB3                  | [645136fe14](https://linux-hardware.org/?probe=645136fe14) | Nov 22, 2024 |
| ASUSTek       | PRIME H670-PLUS D4          | [fbfd923c5c](https://linux-hardware.org/?probe=fbfd923c5c) | Nov 11, 2024 |
| ASUSTek       | PRIME X570-P                | [c747936704](https://linux-hardware.org/?probe=c747936704) | Oct 20, 2024 |
| ASUSTek       | PRIME H670-PLUS D4          | [313e850ec5](https://linux-hardware.org/?probe=313e850ec5) | Oct 14, 2024 |
| ASUSTek       | P8H61/USB3                  | [9abaa26cf8](https://linux-hardware.org/?probe=9abaa26cf8) | Sep 29, 2024 |
| AZW           | MINI S                      | [f9c5011b08](https://linux-hardware.org/?probe=f9c5011b08) | Sep 03, 2024 |
| AZW           | MINI S                      | [7a6ffcc519](https://linux-hardware.org/?probe=7a6ffcc519) | Sep 03, 2024 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [a83776fa56](https://linux-hardware.org/?probe=a83776fa56) | Aug 15, 2024 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [6cabf822ae](https://linux-hardware.org/?probe=6cabf822ae) | Aug 03, 2024 |
| Gigabyte      | TRX50 AERO D                | [8a253c988f](https://linux-hardware.org/?probe=8a253c988f) | Jul 20, 2024 |
| ASUSTek       | PRIME H670-PLUS D4          | [03405c1729](https://linux-hardware.org/?probe=03405c1729) | Jul 17, 2024 |
| Gigabyte      | B550M DS3H                  | [0bea57057c](https://linux-hardware.org/?probe=0bea57057c) | Mar 13, 2024 |
| ASUSTek       | PRIME H670-PLUS D4          | [5a711c0ff0](https://linux-hardware.org/?probe=5a711c0ff0) | Jan 20, 2024 |
| ASUSTek       | AT4NM10T-I                  | [7adc9b4d41](https://linux-hardware.org/?probe=7adc9b4d41) | Jan 06, 2024 |
| MSI           | MAG B760M MORTAR WIFI       | [342164a6a4](https://linux-hardware.org/?probe=342164a6a4) | Dec 29, 2023 |
| SHANGZHAOY... | B85M-PRO V1.1               | [bd7c6e2693](https://linux-hardware.org/?probe=bd7c6e2693) | Dec 22, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [e8965075d3](https://linux-hardware.org/?probe=e8965075d3) | Dec 14, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [e9e5956d89](https://linux-hardware.org/?probe=e9e5956d89) | Dec 10, 2023 |
| MSI           | MEG Z790 ACE                | [41d0e4fddd](https://linux-hardware.org/?probe=41d0e4fddd) | Oct 24, 2023 |
| ASUSTek       | P8H61/USB3                  | [ecf1a70c5d](https://linux-hardware.org/?probe=ecf1a70c5d) | Sep 08, 2023 |
| ASUSTek       | P8H61/USB3                  | [149cb27e46](https://linux-hardware.org/?probe=149cb27e46) | Aug 18, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [888c56f232](https://linux-hardware.org/?probe=888c56f232) | Aug 01, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [993a10a30b](https://linux-hardware.org/?probe=993a10a30b) | Aug 01, 2023 |
| Gateway       | H61H2-AD V1.0               | [9a34a9295c](https://linux-hardware.org/?probe=9a34a9295c) | Jun 15, 2023 |
| ASUSTek       | P8H61/USB3                  | [d93dbf6db3](https://linux-hardware.org/?probe=d93dbf6db3) | Jun 01, 2023 |
| ASUSTek       | P8H61/USB3                  | [16c7ca187a](https://linux-hardware.org/?probe=16c7ca187a) | Jun 01, 2023 |
| ASUSTek       | P8H67-M LE                  | [a69366e2b7](https://linux-hardware.org/?probe=a69366e2b7) | May 29, 2023 |
| ASUSTek       | P8H67-M LE                  | [07202660b9](https://linux-hardware.org/?probe=07202660b9) | May 26, 2023 |
| Acer          | Predator G3-605             | [6f91022c83](https://linux-hardware.org/?probe=6f91022c83) | May 04, 2023 |
| Colorful T... | CVN Z590 GAMING PRO V20     | [209ec5e477](https://linux-hardware.org/?probe=209ec5e477) | Apr 28, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [a7270cf962](https://linux-hardware.org/?probe=a7270cf962) | Feb 19, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [117f4c04d6](https://linux-hardware.org/?probe=117f4c04d6) | Dec 21, 2022 |
| Dell          | 0NKW6Y A02                  | [f20d5b9289](https://linux-hardware.org/?probe=f20d5b9289) | Dec 07, 2022 |
| MSI           | X470 GAMING PRO             | [6ca3196f35](https://linux-hardware.org/?probe=6ca3196f35) | Dec 05, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e840ded8c0](https://linux-hardware.org/?probe=e840ded8c0) | Nov 09, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | [8ee7171b61](https://linux-hardware.org/?probe=8ee7171b61) | Nov 03, 2022 |
| Intel         | D34010WYK H14771-303        | [e58d9849a5](https://linux-hardware.org/?probe=e58d9849a5) | Oct 06, 2022 |
| ASUSTek       | H81M-K                      | [e115d77240](https://linux-hardware.org/?probe=e115d77240) | Aug 07, 2022 |
| ASUSTek       | H81M-K                      | [46201e4773](https://linux-hardware.org/?probe=46201e4773) | Jul 27, 2022 |
| NCR           | Pocono BIOS.6.0             | [ae030a0cda](https://linux-hardware.org/?probe=ae030a0cda) | Jul 15, 2022 |
| Gigabyte      | 970A-DS3P                   | [c45dba9246](https://linux-hardware.org/?probe=c45dba9246) | Jun 26, 2022 |
| Gigabyte      | 970A-DS3P                   | [3d36beed4b](https://linux-hardware.org/?probe=3d36beed4b) | Jun 25, 2022 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | [88a7cd954c](https://linux-hardware.org/?probe=88a7cd954c) | Jun 19, 2022 |
| Gigabyte      | X99-UD4-CF                  | [db53151112](https://linux-hardware.org/?probe=db53151112) | Apr 19, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.14.0-511.el9.x86_64          | 3        | 7.89%   |
| 5.14.0-391.el9.x86_64          | 3        | 7.89%   |
| 5.14.0-480.el9.x86_64          | 2        | 5.26%   |
| 5.14.0-479.el9.x86_64          | 2        | 5.26%   |
| 5.14.0-202.el9.x86_64          | 2        | 5.26%   |
| 5.17.2-lqx3.0.el9.x86_64       | 1        | 2.63%   |
| 5.14.0-86.el9.x86_64           | 1        | 2.63%   |
| 5.14.0-542.el9.x86_64          | 1        | 2.63%   |
| 5.14.0-529.el9.x86_64          | 1        | 2.63%   |
| 5.14.0-522.el9.x86_64          | 1        | 2.63%   |
| 5.14.0-496.el9.x86_64          | 1        | 2.63%   |
| 5.14.0-427.el9.x86_64          | 1        | 2.63%   |
| 5.14.0-407.el9.x86_64          | 1        | 2.63%   |
| 5.14.0-375.el9.x86_64          | 1        | 2.63%   |
| 5.14.0-362.el9.x86_64          | 1        | 2.63%   |
| 5.14.0-352.el9.x86_64          | 1        | 2.63%   |
| 5.14.0-344.el9.x86_64          | 1        | 2.63%   |
| 5.14.0-340.el9.x86_64          | 1        | 2.63%   |
| 5.14.0-325.el9.x86_64          | 1        | 2.63%   |
| 5.14.0-319.el9.x86_64          | 1        | 2.63%   |
| 5.14.0-316.el9.x86_64          | 1        | 2.63%   |
| 5.14.0-305.el9.x86_64          | 1        | 2.63%   |
| 5.14.0-302.el9.x86_64          | 1        | 2.63%   |
| 5.14.0-267.el9.x86_64          | 1        | 2.63%   |
| 5.14.0-214.el9.x86_64          | 1        | 2.63%   |
| 5.14.0-183.el9.x86_64          | 1        | 2.63%   |
| 5.14.0-134.el9.x86_64          | 1        | 2.63%   |
| 5.14.0-130.rt21.130.el9.x86_64 | 1        | 2.63%   |
| 5.14.0-115.el9.x86_64          | 1        | 2.63%   |
| 5.14.0-109.el9.x86_64          | 1        | 2.63%   |
| 4.18.0-529.el8.x86_64          | 1        | 2.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14.0  | 25       | 92.59%  |
| 5.17.2  | 1        | 3.7%    |
| 4.18.0  | 1        | 3.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14    | 25       | 92.59%  |
| 5.17    | 1        | 3.7%    |
| 4.18    | 1        | 3.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 27       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 20       | 74.07%  |
| KDE5          | 4        | 14.81%  |
| GNOME Classic | 2        | 7.41%   |
| Unknown       | 1        | 3.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 15       | 53.57%  |
| X11     | 12       | 42.86%  |
| Unknown | 1        | 3.57%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 17       | 58.62%  |
| GDM     | 10       | 34.48%  |
| SDDM    | 2        | 6.9%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 14       | 51.85%  |
| ja_JP   | 2        | 7.41%   |
| de_DE   | 2        | 7.41%   |
| zh_CN   | 1        | 3.7%    |
| ru_UA   | 1        | 3.7%    |
| ru_RU   | 1        | 3.7%    |
| ro_RO   | 1        | 3.7%    |
| pt_BR   | 1        | 3.7%    |
| it_IT   | 1        | 3.7%    |
| en_GB   | 1        | 3.7%    |
| en_AU   | 1        | 3.7%    |
| Unknown | 1        | 3.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 19       | 67.86%  |
| BIOS | 9        | 32.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 24       | 88.89%  |
| Ext4 | 3        | 11.11%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 15       | 50%     |
| GPT     | 11       | 36.67%  |
| MBR     | 4        | 13.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 82.14%  |
| Yes       | 5        | 17.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 66.67%  |
| Yes       | 10       | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 11       | 40.74%  |
| Gigabyte Technology | 4        | 14.81%  |
| MSI                 | 3        | 11.11%  |
| SHANGZHAOYUAN       | 1        | 3.7%    |
| Lenovo              | 1        | 3.7%    |
| Intel               | 1        | 3.7%    |
| Hewlett-Packard     | 1        | 3.7%    |
| Gateway             | 1        | 3.7%    |
| Dell                | 1        | 3.7%    |
| Colorful Technology | 1        | 3.7%    |
| AZW                 | 1        | 3.7%    |
| Acer                | 1        | 3.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS PRIME H670-PLUS D4            | 2        | 7.41%   |
| SHANGZHAOYUAN B85M-PRO V1.1        | 1        | 3.7%    |
| MSI MS-7E01                        | 1        | 3.7%    |
| MSI MS-7D86                        | 1        | 3.7%    |
| MSI MS-7B79                        | 1        | 3.7%    |
| Lenovo ThinkCentre M900 10FGS0301H | 1        | 3.7%    |
| Intel D34010WYK H14771-303         | 1        | 3.7%    |
| HP ProDesk 600 G1 SFF              | 1        | 3.7%    |
| Gigabyte X99-UD4-CF                | 1        | 3.7%    |
| Gigabyte TRX50 AERO D              | 1        | 3.7%    |
| Gigabyte B550M DS3H                | 1        | 3.7%    |
| Gigabyte 970A-DS3P                 | 1        | 3.7%    |
| Gateway SX2865                     | 1        | 3.7%    |
| Dell OptiPlex 790                  | 1        | 3.7%    |
| Colorful CVN Z590 GAMING PRO       | 1        | 3.7%    |
| AZW MINI S                         | 1        | 3.7%    |
| ASUS TUF Gaming X570-PLUS          | 1        | 3.7%    |
| ASUS ROG STRIX B560-G GAMING WIFI  | 1        | 3.7%    |
| ASUS ROG STRIX B550-A GAMING       | 1        | 3.7%    |
| ASUS ROG CROSSHAIR VIII DARK HERO  | 1        | 3.7%    |
| ASUS PRIME X570-P                  | 1        | 3.7%    |
| ASUS P8H67-M LE                    | 1        | 3.7%    |
| ASUS P8H61/USB3                    | 1        | 3.7%    |
| ASUS AT4NM10T-I                    | 1        | 3.7%    |
| ASUS All Series                    | 1        | 3.7%    |
| Acer Predator G3-605               | 1        | 3.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS ROG               | 3        | 11.11%  |
| ASUS PRIME             | 3        | 11.11%  |
| SHANGZHAOYUAN B85M-PRO | 1        | 3.7%    |
| MSI MS-7E01            | 1        | 3.7%    |
| MSI MS-7D86            | 1        | 3.7%    |
| MSI MS-7B79            | 1        | 3.7%    |
| Lenovo ThinkCentre     | 1        | 3.7%    |
| Intel D34010WYK        | 1        | 3.7%    |
| HP ProDesk             | 1        | 3.7%    |
| Gigabyte X99-UD4-CF    | 1        | 3.7%    |
| Gigabyte TRX50         | 1        | 3.7%    |
| Gigabyte B550M         | 1        | 3.7%    |
| Gigabyte 970A-DS3P     | 1        | 3.7%    |
| Gateway SX2865         | 1        | 3.7%    |
| Dell OptiPlex          | 1        | 3.7%    |
| Colorful CVN           | 1        | 3.7%    |
| AZW MINI               | 1        | 3.7%    |
| ASUS TUF               | 1        | 3.7%    |
| ASUS P8H67-M           | 1        | 3.7%    |
| ASUS P8H61             | 1        | 3.7%    |
| ASUS AT4NM10T-I        | 1        | 3.7%    |
| ASUS All               | 1        | 3.7%    |
| Acer Predator          | 1        | 3.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 7        | 25.93%  |
| 2022 | 4        | 14.81%  |
| 2021 | 4        | 14.81%  |
| 2020 | 3        | 11.11%  |
| 2011 | 3        | 11.11%  |
| 2023 | 2        | 7.41%   |
| 2019 | 2        | 7.41%   |
| 2018 | 1        | 3.7%    |
| 2014 | 1        | 3.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 27       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 25       | 92.59%  |
| Enabled  | 2        | 7.41%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 27       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 8        | 29.63%  |
| 64.01-256.0 | 7        | 25.93%  |
| 32.01-64.0  | 5        | 18.52%  |
| 8.01-16.0   | 4        | 14.81%  |
| 16.01-24.0  | 2        | 7.41%   |
| 3.01-4.0    | 1        | 3.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 11       | 35.48%  |
| 2.01-3.0   | 8        | 25.81%  |
| 4.01-8.0   | 6        | 19.35%  |
| 1.01-2.0   | 3        | 9.68%   |
| 8.01-16.0  | 2        | 6.45%   |
| 16.01-24.0 | 1        | 3.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 3      | 9        | 33.33%  |
| 2      | 6        | 22.22%  |
| 1      | 6        | 22.22%  |
| 4      | 5        | 18.52%  |
| 5      | 1        | 3.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 74.07%  |
| Yes       | 7        | 25.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 27       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 14       | 51.85%  |
| No        | 13       | 48.15%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 55.56%  |
| Yes       | 12       | 44.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 5        | 18.52%  |
| Russia      | 3        | 11.11%  |
| Bulgaria    | 3        | 11.11%  |
| Japan       | 2        | 7.41%   |
| Germany     | 2        | 7.41%   |
| Brazil      | 2        | 7.41%   |
| Australia   | 2        | 7.41%   |
| Ukraine     | 1        | 3.7%    |
| Romania     | 1        | 3.7%    |
| Puerto Rico | 1        | 3.7%    |
| Myanmar     | 1        | 3.7%    |
| Italy       | 1        | 3.7%    |
| Greece      | 1        | 3.7%    |
| China       | 1        | 3.7%    |
| Belarus     | 1        | 3.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Sofia                | 2        | 6.9%    |
| Yangon               | 1        | 3.45%   |
| Wuhan                | 1        | 3.45%   |
| Vitebsk              | 1        | 3.45%   |
| Tyumen               | 1        | 3.45%   |
| Tomah                | 1        | 3.45%   |
| Sao José dos Campos | 1        | 3.45%   |
| San Juan             | 1        | 3.45%   |
| Rome                 | 1        | 3.45%   |
| Porto Alegre         | 1        | 3.45%   |
| Portland             | 1        | 3.45%   |
| Perth                | 1        | 3.45%   |
| Okazaki              | 1        | 3.45%   |
| New Cumberland       | 1        | 3.45%   |
| Neunkirchen          | 1        | 3.45%   |
| Navapolatsk          | 1        | 3.45%   |
| Nagoya               | 1        | 3.45%   |
| Moscow               | 1        | 3.45%   |
| Milpitas             | 1        | 3.45%   |
| Meieki               | 1        | 3.45%   |
| Kyiv                 | 1        | 3.45%   |
| Kovrov               | 1        | 3.45%   |
| Durham               | 1        | 3.45%   |
| Dortmund             | 1        | 3.45%   |
| Canberra             | 1        | 3.45%   |
| Burgas               | 1        | 3.45%   |
| Bucharest            | 1        | 3.45%   |
| Athens               | 1        | 3.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 11       | 19     | 20.37%  |
| Seagate             | 9        | 13     | 16.67%  |
| Samsung Electronics | 7        | 10     | 12.96%  |
| Toshiba             | 5        | 7      | 9.26%   |
| Kingston            | 5        | 9      | 9.26%   |
| SanDisk             | 3        | 19     | 5.56%   |
| Crucial             | 2        | 18     | 3.7%    |
| WD MediaMax         | 1        | 1      | 1.85%   |
| Team                | 1        | 2      | 1.85%   |
| Plextor             | 1        | 1      | 1.85%   |
| Phison Electronics  | 1        | 1      | 1.85%   |
| Phison              | 1        | 1      | 1.85%   |
| OCZ                 | 1        | 1      | 1.85%   |
| Intel               | 1        | 1      | 1.85%   |
| Hitachi             | 1        | 1      | 1.85%   |
| Gigabyte Technology | 1        | 2      | 1.85%   |
| China               | 1        | 1      | 1.85%   |
| ADATA Technology    | 1        | 1      | 1.85%   |
| A-DATA Technology   | 1        | 1      | 1.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB             | 2        | 3.17%   |
| Sandisk WD_BLACK SN770 1TB                 | 2        | 3.17%   |
| SanDisk SDSSDH3 1T00 1TB                   | 2        | 3.17%   |
| Crucial CT525MX300SSD1 528GB               | 2        | 3.17%   |
| WDC WDS250G2B0A-00SM50 250GB SSD           | 1        | 1.59%   |
| WDC WDS120G2G0A-00JH30 120GB SSD           | 1        | 1.59%   |
| WDC WD6003FZBX-00K5WB0 6TB                 | 1        | 1.59%   |
| WDC WD5000BEVT-55A0RT0 500GB               | 1        | 1.59%   |
| WDC WD3200AAKX-753CA1 320GB                | 1        | 1.59%   |
| WDC WD2500AAJS-60M0A0 250GB                | 1        | 1.59%   |
| WDC WD22EJRX-89BEMY0 2TB                   | 1        | 1.59%   |
| WDC WD20EZAZ-00GGJB0 2TB                   | 1        | 1.59%   |
| WDC WD2003FZEX-00Z4SA0 2TB                 | 1        | 1.59%   |
| WDC WD10EZEX-60M2NA0 1TB                   | 1        | 1.59%   |
| WDC WD10EZEX-08WN4A0 1TB                   | 1        | 1.59%   |
| WDC WD10EZEX-00BN5A0 1TB                   | 1        | 1.59%   |
| WDC WD Blue SA510 2.5 500GB                | 1        | 1.59%   |
| WD MediaMax WL750GSA6472 752GB             | 1        | 1.59%   |
| Toshiba MQ01ABD100 1TB                     | 1        | 1.59%   |
| Toshiba MK2561GSYN 250GB                   | 1        | 1.59%   |
| Toshiba MK1234GSX 120GB                    | 1        | 1.59%   |
| Toshiba DT01ACA200 2TB                     | 1        | 1.59%   |
| Toshiba DT01ACA100 1TB                     | 1        | 1.59%   |
| Team T253X1480G 480GB SSD                  | 1        | 1.59%   |
| Seagate ST3500413AS 500GB                  | 1        | 1.59%   |
| Seagate ST3250820AS 250GB                  | 1        | 1.59%   |
| Seagate ST320LM001 HN-M320MBB 320GB        | 1        | 1.59%   |
| Seagate ST32000644NS 2TB                   | 1        | 1.59%   |
| Seagate ST31000528AS 1TB                   | 1        | 1.59%   |
| Seagate ST2000DL003-9VT166 2TB             | 1        | 1.59%   |
| Seagate ST1000DM 010-2EP102 1TB            | 1        | 1.59%   |
| Seagate One Touch HDD 4TB                  | 1        | 1.59%   |
| Seagate FireCuda 520 SSD ZP2000GM30002 2TB | 1        | 1.59%   |
| Seagate FireCuda 520 SSD ZP1000GM30002 1TB | 1        | 1.59%   |
| Sandisk WD_BLACK SN850X 4000GB             | 1        | 1.59%   |
| Samsung SSD 870 QVO 2TB                    | 1        | 1.59%   |
| Samsung SSD 870 EVO 250GB                  | 1        | 1.59%   |
| Samsung SSD 860 PRO 2TB                    | 1        | 1.59%   |
| Samsung SSD 860 EVO 1TB                    | 1        | 1.59%   |
| Samsung SSD 850 EVO 500GB                  | 1        | 1.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor      | Desktops | Drives | Percent |
|-------------|----------|--------|---------|
| WDC         | 9        | 16     | 37.5%   |
| Seagate     | 8        | 11     | 33.33%  |
| Toshiba     | 5        | 7      | 20.83%  |
| WD MediaMax | 1        | 1      | 4.17%   |
| Hitachi     | 1        | 1      | 4.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 6        | 8      | 26.09%  |
| Kingston            | 4        | 8      | 17.39%  |
| WDC                 | 3        | 3      | 13.04%  |
| SanDisk             | 2        | 9      | 8.7%    |
| Crucial             | 2        | 18     | 8.7%    |
| Team                | 1        | 2      | 4.35%   |
| Plextor             | 1        | 1      | 4.35%   |
| OCZ                 | 1        | 1      | 4.35%   |
| Gigabyte Technology | 1        | 2      | 4.35%   |
| China               | 1        | 1      | 4.35%   |
| A-DATA Technology   | 1        | 1      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 19       | 54     | 41.3%   |
| HDD  | 16       | 36     | 34.78%  |
| NVMe | 11       | 19     | 23.91%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 24       | 88     | 64.86%  |
| NVMe | 11       | 19     | 29.73%  |
| SAS  | 2        | 2      | 5.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 17       | 29     | 43.59%  |
| 0.51-1.0   | 12       | 43     | 30.77%  |
| 1.01-2.0   | 8        | 15     | 20.51%  |
| 3.01-4.0   | 1        | 1      | 2.56%   |
| 4.01-10.0  | 1        | 2      | 2.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 9        | 31.03%  |
| 101-250        | 5        | 17.24%  |
| 251-500        | 4        | 13.79%  |
| More than 3000 | 3        | 10.34%  |
| 2001-3000      | 3        | 10.34%  |
| 501-1000       | 2        | 6.9%    |
| 21-50          | 1        | 3.45%   |
| 51-100         | 1        | 3.45%   |
| Unknown        | 1        | 3.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 7        | 24.14%  |
| 21-50          | 6        | 20.69%  |
| 1-20           | 6        | 20.69%  |
| 51-100         | 4        | 13.79%  |
| 101-250        | 2        | 6.9%    |
| More than 3000 | 1        | 3.45%   |
| 251-500        | 1        | 3.45%   |
| 1001-2000      | 1        | 3.45%   |
| Unknown        | 1        | 3.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC WD10EZEX-60M2NA0 1TB  | 1        | 1      | 16.67%  |
| Toshiba MQ01ABD100 1TB    | 1        | 1      | 16.67%  |
| Toshiba MK2561GSYN 250GB  | 1        | 1      | 16.67%  |
| Toshiba MK1234GSX 120GB   | 1        | 1      | 16.67%  |
| Seagate ST3250820AS 250GB | 1        | 1      | 16.67%  |
| Seagate ST32000644NS 2TB  | 1        | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 3        | 3      | 50%     |
| Seagate | 2        | 2      | 33.33%  |
| WDC     | 1        | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 3        | 3      | 50%     |
| Seagate | 2        | 2      | 33.33%  |
| WDC     | 1        | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 6      | 100%    |

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
| Detected | 16       | 68     | 45.71%  |
| Works    | 14       | 35     | 40%     |
| Malfunc  | 5        | 6      | 14.29%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 20       | 48.78%  |
| AMD                         | 8        | 19.51%  |
| SanDisk                     | 3        | 7.32%   |
| Samsung Electronics         | 2        | 4.88%   |
| Phison Electronics          | 2        | 4.88%   |
| Silicon Image               | 1        | 2.44%   |
| Seagate Technology          | 1        | 2.44%   |
| Kingston Technology Company | 1        | 2.44%   |
| JMicron Technology          | 1        | 2.44%   |
| ASMedia Technology          | 1        | 2.44%   |
| ADATA Technology            | 1        | 2.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 5        | 11.63%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4        | 9.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4        | 9.3%    |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 2        | 4.65%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 2        | 4.65%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2        | 4.65%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2        | 4.65%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 4.65%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 2.33%   |
| Seagate FireCuda 520/IronWolf 525 SSD                                          | 1        | 2.33%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 1        | 2.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 2.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 2.33%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 2.33%   |
| Phison E12 NVMe Controller                                                     | 1        | 2.33%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                           | 1        | 2.33%   |
| JMicron JMB362 SATA Controller                                                 | 1        | 2.33%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1        | 2.33%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 2.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 2.33%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1        | 2.33%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1        | 2.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1        | 2.33%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 1        | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1        | 2.33%   |
| AMD 600 Series Chipset SATA Controller                                         | 1        | 2.33%   |
| AMD 400 Series Chipset SATA Controller                                         | 1        | 2.33%   |
| ADATA XPG GAMMIX S5 NVMe SSD (DRAM-less)                                       | 1        | 2.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 26       | 66.67%  |
| NVMe | 11       | 28.21%  |
| RAID | 2        | 5.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 19       | 70.37%  |
| AMD    | 8        | 29.63%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel 12th Gen Core i5-12600K          | 2        | 7.41%   |
| Intel Core i7-5930K CPU @ 3.50GHz      | 1        | 3.7%    |
| Intel Core i7-4770K CPU @ 3.50GHz      | 1        | 3.7%    |
| Intel Core i7-4770 CPU @ 3.40GHz       | 1        | 3.7%    |
| Intel Core i7-2600K CPU @ 3.40GHz      | 1        | 3.7%    |
| Intel Core i5-6500 CPU @ 3.20GHz       | 1        | 3.7%    |
| Intel Core i5-4590 CPU @ 3.30GHz       | 1        | 3.7%    |
| Intel Core i5-4440 CPU @ 3.10GHz       | 1        | 3.7%    |
| Intel Core i5-3470 CPU @ 3.20GHz       | 1        | 3.7%    |
| Intel Core i5-2400S CPU @ 2.50GHz      | 1        | 3.7%    |
| Intel Core i5-10400F CPU @ 2.90GHz     | 1        | 3.7%    |
| Intel Core i3-4010U CPU @ 1.70GHz      | 1        | 3.7%    |
| Intel Core i3-2130 CPU @ 3.40GHz       | 1        | 3.7%    |
| Intel Celeron N5095 @ 2.00GHz          | 1        | 3.7%    |
| Intel Atom CPU D425 @ 1.80GHz          | 1        | 3.7%    |
| Intel 13th Gen Core i9-13900K          | 1        | 3.7%    |
| Intel 13th Gen Core i7-13700K          | 1        | 3.7%    |
| Intel 11th Gen Core i5-11400 @ 2.60GHz | 1        | 3.7%    |
| AMD Ryzen Threadripper 7960X 24-Cores  | 1        | 3.7%    |
| AMD Ryzen 9 5950X 16-Core Processor    | 1        | 3.7%    |
| AMD Ryzen 9 3950X 16-Core Processor    | 1        | 3.7%    |
| AMD Ryzen 9 3900X 12-Core Processor    | 1        | 3.7%    |
| AMD Ryzen 7 5800X3D 8-Core Processor   | 1        | 3.7%    |
| AMD Ryzen 7 5700G with Radeon Graphics | 1        | 3.7%    |
| AMD Ryzen 5 3600 6-Core Processor      | 1        | 3.7%    |
| AMD FX-8120 Eight-Core Processor       | 1        | 3.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 6        | 22.22%  |
| Other                  | 5        | 18.52%  |
| Intel Core i7          | 4        | 14.81%  |
| AMD Ryzen 9            | 3        | 11.11%  |
| Intel Core i3          | 2        | 7.41%   |
| AMD Ryzen 7            | 2        | 7.41%   |
| Intel Celeron          | 1        | 3.7%    |
| Intel Atom             | 1        | 3.7%    |
| AMD Ryzen Threadripper | 1        | 3.7%    |
| AMD Ryzen 5            | 1        | 3.7%    |
| AMD FX                 | 1        | 3.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 10       | 37.04%  |
| 6      | 4        | 14.81%  |
| 16     | 3        | 11.11%  |
| 24     | 2        | 7.41%   |
| 10     | 2        | 7.41%   |
| 8      | 2        | 7.41%   |
| 2      | 2        | 7.41%   |
| 12     | 1        | 3.7%    |
| 1      | 1        | 3.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 27       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 20       | 74.07%  |
| 1      | 7        | 25.93%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 27       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 51.85%  |
| 0x306c3    | 2        | 7.41%   |
| 0xa0671    | 1        | 3.7%    |
| 0xa0653    | 1        | 3.7%    |
| 0x90672    | 1        | 3.7%    |
| 0x40651    | 1        | 3.7%    |
| 0x306f2    | 1        | 3.7%    |
| 0x206a7    | 1        | 3.7%    |
| 0x0a50000c | 1        | 3.7%    |
| 0x0a201016 | 1        | 3.7%    |
| 0x08701021 | 1        | 3.7%    |
| 0x08701013 | 1        | 3.7%    |
| 0x0600063d | 1        | 3.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 6        | 21.43%  |
| Alderlake Hybrid | 4        | 14.29%  |
| Zen 3            | 3        | 10.71%  |
| Zen 2            | 3        | 10.71%  |
| SandyBridge      | 3        | 10.71%  |
| Unknown          | 2        | 7.14%   |
| Tremont          | 1        | 3.57%   |
| Skylake          | 1        | 3.57%   |
| IvyBridge        | 1        | 3.57%   |
| Icelake          | 1        | 3.57%   |
| CometLake        | 1        | 3.57%   |
| Bulldozer        | 1        | 3.57%   |
| Bonnell          | 1        | 3.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 12       | 41.38%  |
| Intel  | 11       | 37.93%  |
| AMD    | 6        | 20.69%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 6.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 6.45%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 2        | 6.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 6.45%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 3.23%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 3.23%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 3.23%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 3.23%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 3.23%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1        | 3.23%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 3.23%   |
| Nvidia GK208 [GeForce GT 720]                                               | 1        | 3.23%   |
| Nvidia GK107GL [Quadro K600]                                                | 1        | 3.23%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 1        | 3.23%   |
| Nvidia AD104 [GeForce RTX 4070]                                             | 1        | 3.23%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 3.23%   |
| Intel JasperLake [UHD Graphics]                                             | 1        | 3.23%   |
| Intel HD Graphics 530                                                       | 1        | 3.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 3.23%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 1        | 3.23%   |
| AMD RV370 [Radeon X300/X550/X1050 Series] (Secondary)                       | 1        | 3.23%   |
| AMD RV370 [Radeon X300/X550/X1050 Series]                                   | 1        | 3.23%   |
| AMD Park [Mobility Radeon HD 5430]                                          | 1        | 3.23%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 1        | 3.23%   |
| AMD Juniper XT [Radeon HD 6770]                                             | 1        | 3.23%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 1        | 3.23%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 3.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 12       | 44.44%  |
| 1 x Intel  | 9        | 33.33%  |
| 1 x AMD    | 5        | 18.52%  |
| 2 x AMD    | 1        | 3.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 18       | 64.29%  |
| Proprietary | 8        | 28.57%  |
| Unknown     | 2        | 7.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 11       | 36.67%  |
| 3.01-4.0   | 4        | 13.33%  |
| 1.01-2.0   | 4        | 13.33%  |
| 8.01-16.0  | 4        | 13.33%  |
| 5.01-6.0   | 3        | 10%     |
| 0.51-1.0   | 3        | 10%     |
| 0.01-0.5   | 1        | 3.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 6        | 20.69%  |
| Dell                | 5        | 17.24%  |
| Goldstar            | 4        | 13.79%  |
| ViewSonic           | 2        | 6.9%    |
| Iiyama              | 2        | 6.9%    |
| BenQ                | 2        | 6.9%    |
| AOC                 | 2        | 6.9%    |
| MStar               | 1        | 3.45%   |
| LG Electronics      | 1        | 3.45%   |
| HKC                 | 1        | 3.45%   |
| Hewlett-Packard     | 1        | 3.45%   |
| ASUSTek Computer    | 1        | 3.45%   |
| Acer                | 1        | 3.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Iiyama PL2888H IVM7106 1920x1080 621x341mm 27.9-inch                    | 2        | 5.88%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch           | 1        | 2.94%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch           | 1        | 2.94%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 607x345mm 27.5-inch       | 1        | 2.94%   |
| Samsung Electronics SyncMaster SAM05EB 1920x1080 597x336mm 27.0-inch    | 1        | 2.94%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch    | 1        | 2.94%   |
| Samsung Electronics SMEX2220 SAM0686 1920x1080 477x268mm 21.5-inch      | 1        | 2.94%   |
| Samsung Electronics S27C450 SAM09D9 1920x1080 598x336mm 27.0-inch       | 1        | 2.94%   |
| Samsung Electronics LCD Monitor SAM7048 1366x768 522x293mm 23.6-inch    | 1        | 2.94%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1        | 2.94%   |
| MStar LCD Monitor Demo 1920x1080                                        | 1        | 2.94%   |
| LG Electronics LCD Monitor LG FULL HD                                   | 1        | 2.94%   |
| HKC 24N1A HKC2413 1920x1080 527x296mm 23.8-inch                         | 1        | 2.94%   |
| Hewlett-Packard 2159 HWP282C 1920x1080 479x269mm 21.6-inch              | 1        | 2.94%   |
| Goldstar ULTRAGEAR GSM5B70 1920x1080 531x298mm 24.0-inch                | 1        | 2.94%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                    | 1        | 2.94%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch               | 1        | 2.94%   |
| Goldstar 22EA53 GSM59A6 1920x1080 477x268mm 21.5-inch                   | 1        | 2.94%   |
| Dell U2720Q DEL41B0 3840x2160 597x336mm 27.0-inch                       | 1        | 2.94%   |
| Dell U2719D DEL415A 2560x1440 597x336mm 27.0-inch                       | 1        | 2.94%   |
| Dell U2718Q DELA0E9 3840x2160 609x349mm 27.6-inch                       | 1        | 2.94%   |
| Dell U2520D DELA150 2560x1440 553x311mm 25.0-inch                       | 1        | 2.94%   |
| Dell U2520D DELA14E 2560x1440 553x311mm 25.0-inch                       | 1        | 2.94%   |
| Dell U2520D DELA14C 2560x1440 550x310mm 24.9-inch                       | 1        | 2.94%   |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                       | 1        | 2.94%   |
| Dell P2418HT DEL4113 1920x1080 527x296mm 23.8-inch                      | 1        | 2.94%   |
| Dell 2408WFP DELA029 1920x1200 519x324mm 24.1-inch                      | 1        | 2.94%   |
| BenQ ZOWIE XL LCD BNQ7F83 1920x1080 544x303mm 24.5-inch                 | 1        | 2.94%   |
| BenQ PD2705U BNQ8039 3840x2160 597x336mm 27.0-inch                      | 1        | 2.94%   |
| ASUSTek Computer PG329 AUS32F3 2560x1440 708x399mm 32.0-inch            | 1        | 2.94%   |
| AOC LCD Monitor 24G1WG4 3840x1080                                       | 1        | 2.94%   |
| AOC 2217 AOC2217 1680x1050 470x300mm 22.0-inch                          | 1        | 2.94%   |
| Acer H236HL ACR0318 1920x1080 509x286mm 23.0-inch                       | 1        | 2.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 15       | 51.72%  |
| 3840x2160 (4K)     | 5        | 17.24%  |
| 2560x1440 (QHD)    | 3        | 10.34%  |
| 1920x1200 (WUXGA)  | 2        | 6.9%    |
| 3840x1080          | 1        | 3.45%   |
| 1680x1050 (WSXGA+) | 1        | 3.45%   |
| 1366x768 (WXGA)    | 1        | 3.45%   |
| Unknown            | 1        | 3.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 9        | 29.03%  |
| 21      | 6        | 19.35%  |
| 23      | 5        | 16.13%  |
| 24      | 3        | 9.68%   |
| 32      | 2        | 6.45%   |
| Unknown | 2        | 6.45%   |
| 84      | 1        | 3.23%   |
| 38      | 1        | 3.23%   |
| 25      | 1        | 3.23%   |
| 22      | 1        | 3.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 12       | 41.38%  |
| 401-500     | 7        | 24.14%  |
| 601-700     | 4        | 13.79%  |
| 701-800     | 2        | 6.9%    |
| Unknown     | 2        | 6.9%    |
| 801-900     | 1        | 3.45%   |
| 1501-2000   | 1        | 3.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 21       | 84%     |
| 16/10   | 2        | 8%      |
| Unknown | 2        | 8%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 12       | 40%     |
| 301-350        | 9        | 30%     |
| 251-300        | 3        | 10%     |
| 351-500        | 2        | 6.67%   |
| Unknown        | 2        | 6.67%   |
| More than 1000 | 1        | 3.33%   |
| 501-1000       | 1        | 3.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 14       | 48.28%  |
| 101-120 | 9        | 31.03%  |
| 161-240 | 2        | 6.9%    |
| 121-160 | 2        | 6.9%    |
| Unknown | 2        | 6.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 19       | 65.52%  |
| 2     | 6        | 20.69%  |
| 0     | 3        | 10.34%  |
| 4     | 1        | 3.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 19       | 41.3%   |
| Intel                 | 16       | 34.78%  |
| Qualcomm Atheros      | 3        | 6.52%   |
| Ralink Technology     | 2        | 4.35%   |
| Aquantia              | 2        | 4.35%   |
| U-Blox                | 1        | 2.17%   |
| TP-Link               | 1        | 2.17%   |
| DisplayLink           | 1        | 2.17%   |
| Ceton Technologies    | 1        | 2.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller            | 11       | 21.57%  |
| Realtek RTL8125 2.5GbE Controller                                                 | 5        | 9.8%    |
| Intel Ethernet Controller I225-V                                                  | 3        | 5.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 2        | 3.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                  | 2        | 3.92%   |
| Intel Wi-Fi 6 AX200                                                               | 2        | 3.92%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                                 | 2        | 3.92%   |
| U-Blox [u-blox 8]                                                                 | 1        | 1.96%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                            | 1        | 1.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                          | 1        | 1.96%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                             | 1        | 1.96%   |
| Ralink RT5370 Wireless Adapter                                                    | 1        | 1.96%   |
| Ralink RT2501/RT2573 Wireless Adapter                                             | 1        | 1.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                        | 1        | 1.96%   |
| Intel Wireless 7265                                                               | 1        | 1.96%   |
| Intel Wireless 7260                                                               | 1        | 1.96%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                           | 1        | 1.96%   |
| Intel I211 Gigabit Network Connection                                             | 1        | 1.96%   |
| Intel Ethernet Controller I226-V                                                  | 1        | 1.96%   |
| Intel Ethernet Connection I218-V                                                  | 1        | 1.96%   |
| Intel Ethernet Connection I217-V                                                  | 1        | 1.96%   |
| Intel Ethernet Connection I217-LM                                                 | 1        | 1.96%   |
| Intel Ethernet Connection (2) I219-LM                                             | 1        | 1.96%   |
| Intel Ethernet Connection (2) I218-V                                              | 1        | 1.96%   |
| Intel 82579V Gigabit Network Connection                                           | 1        | 1.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                             | 1        | 1.96%   |
| Intel 82574L Gigabit Network Connection                                           | 1        | 1.96%   |
| DisplayLink Plugable UD-ULTC4K                                                    | 1        | 1.96%   |
| Ceton InfiniTV Network                                                            | 1        | 1.96%   |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G]   | 1        | 1.96%   |
| Aquantia AQC113C NBase-T/IEEE 802.3an Ethernet Controller [Marvell Scalable mGig] | 1        | 1.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 7        | 46.67%  |
| Qualcomm Atheros      | 3        | 20%     |
| Realtek Semiconductor | 2        | 13.33%  |
| Ralink Technology     | 2        | 13.33%  |
| TP-Link               | 1        | 6.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 2        | 13.33%  |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2        | 13.33%  |
| Intel Wi-Fi 6 AX200                                        | 2        | 13.33%  |
| Intel Raptor Lake-S PCH CNVi WiFi                          | 2        | 13.33%  |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 1        | 6.67%   |
| Ralink RT5370 Wireless Adapter                             | 1        | 6.67%   |
| Ralink RT2501/RT2573 Wireless Adapter                      | 1        | 6.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1        | 6.67%   |
| Intel Wireless 7265                                        | 1        | 6.67%   |
| Intel Wireless 7260                                        | 1        | 6.67%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]    | 1        | 6.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 17       | 50%     |
| Intel                 | 13       | 38.24%  |
| Aquantia              | 2        | 5.88%   |
| DisplayLink           | 1        | 2.94%   |
| Ceton Technologies    | 1        | 2.94%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller            | 11       | 31.43%  |
| Realtek RTL8125 2.5GbE Controller                                                 | 5        | 14.29%  |
| Intel Ethernet Controller I225-V                                                  | 3        | 8.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                          | 1        | 2.86%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                             | 1        | 2.86%   |
| Intel I211 Gigabit Network Connection                                             | 1        | 2.86%   |
| Intel Ethernet Controller I226-V                                                  | 1        | 2.86%   |
| Intel Ethernet Connection I218-V                                                  | 1        | 2.86%   |
| Intel Ethernet Connection I217-V                                                  | 1        | 2.86%   |
| Intel Ethernet Connection I217-LM                                                 | 1        | 2.86%   |
| Intel Ethernet Connection (2) I219-LM                                             | 1        | 2.86%   |
| Intel Ethernet Connection (2) I218-V                                              | 1        | 2.86%   |
| Intel 82579V Gigabit Network Connection                                           | 1        | 2.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                             | 1        | 2.86%   |
| Intel 82574L Gigabit Network Connection                                           | 1        | 2.86%   |
| DisplayLink Plugable UD-ULTC4K                                                    | 1        | 2.86%   |
| Ceton InfiniTV Network                                                            | 1        | 2.86%   |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G]   | 1        | 2.86%   |
| Aquantia AQC113C NBase-T/IEEE 802.3an Ethernet Controller [Marvell Scalable mGig] | 1        | 2.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 27       | 64.29%  |
| WiFi     | 14       | 33.33%  |
| Modem    | 1        | 2.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 25       | 89.29%  |
| WiFi     | 3        | 10.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 12       | 44.44%  |
| 1     | 12       | 44.44%  |
| 3     | 3        | 11.11%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 18       | 66.67%  |
| Yes  | 9        | 33.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 7        | 58.33%  |
| Qualcomm Atheros Communications | 1        | 8.33%   |
| Lite-On Technology              | 1        | 8.33%   |
| Foxconn / Hon Hai               | 1        | 8.33%   |
| Cambridge Silicon Radio         | 1        | 8.33%   |
| ASUSTek Computer                | 1        | 8.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 2        | 16.67%  |
| Intel AX211 Bluetooth                               | 2        | 16.67%  |
| Intel AX200 Bluetooth                               | 2        | 16.67%  |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 8.33%   |
| Lite-On Bluetooth Device                            | 1        | 8.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 8.33%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1        | 8.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 8.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 8.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 19       | 38%     |
| Nvidia                   | 12       | 24%     |
| AMD                      | 11       | 22%     |
| SteelSeries ApS          | 3        | 6%      |
| Walmart                  | 1        | 2%      |
| Micro Star International | 1        | 2%      |
| KTMicro                  | 1        | 2%      |
| Giga-Byte Technology     | 1        | 2%      |
| DSEA A/S                 | 1        | 2%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 8.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4        | 7.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 7.14%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 3.57%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 3.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 3.57%   |
| Intel Raptor Lake High Definition Audio Controller                         | 2        | 3.57%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 3.57%   |
| Walmart AB13X Headset Adapter                                              | 1        | 1.79%   |
| SteelSeries ApS SteelSeries Siberia 800                                    | 1        | 1.79%   |
| SteelSeries ApS SteelSeries GameDAC                                        | 1        | 1.79%   |
| SteelSeries ApS Arctis Nova Pro Wireless                                   | 1        | 1.79%   |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 1.79%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.79%   |
| Nvidia GM200 High Definition Audio                                         | 1        | 1.79%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1.79%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 1.79%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 1.79%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 1.79%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 1.79%   |
| Nvidia AD104 High Definition Audio Controller                              | 1        | 1.79%   |
| Micro Star International USB Audio                                         | 1        | 1.79%   |
| KTMicro KT USB Audio                                                       | 1        | 1.79%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 1.79%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1        | 1.79%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 1.79%   |
| Intel Jasper Lake HD Audio                                                 | 1        | 1.79%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 1.79%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 1.79%   |
| Intel 8 Series HD Audio Controller                                         | 1        | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 1.79%   |
| Giga-Byte Technology USB Audio                                             | 1        | 1.79%   |
| DSEA A/S Sennheiser USB headset                                            | 1        | 1.79%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 1.79%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 1.79%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1        | 1.79%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 1        | 1.79%   |
| AMD Genoa HD Audio Controller                                              | 1        | 1.79%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 1        | 1.79%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 1.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 2        | 14.29%  |
| Kingston            | 2        | 14.29%  |
| G.Skill             | 2        | 14.29%  |
| Crucial             | 2        | 14.29%  |
| Corsair             | 2        | 14.29%  |
| Team                | 1        | 7.14%   |
| SK hynix            | 1        | 7.14%   |
| Samsung Electronics | 1        | 7.14%   |
| Ramaxel Technology  | 1        | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s               | 1        | 7.14%   |
| Unknown RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s     | 1        | 7.14%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s       | 1        | 7.14%   |
| SK hynix RAM Module 4GB DIMM DDR3 1600MT/s               | 1        | 7.14%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s      | 1        | 7.14%   |
| Ramaxel RAM RMUA5090KB78HAF2133 8GB DIMM DDR4 2400MT/s   | 1        | 7.14%   |
| Kingston RAM KF556R36-32 32GB DIMM DDR5 4800MT/s         | 1        | 7.14%   |
| Kingston RAM 99U5471-034.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 7.14%   |
| G.Skill RAM F5-5600J3036D32G 32GB DIMM DDR5 5600MT/s     | 1        | 7.14%   |
| G.Skill RAM F4-3600C18-32GTZR 32GB DIMM DDR4 3600MT/s    | 1        | 7.14%   |
| Crucial RAM CT16G4DFD824A.C16FBD 16GB DIMM DDR4 2933MT/s | 1        | 7.14%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s    | 1        | 7.14%   |
| Corsair RAM CMK64GX4M2Z4000C18 32GB DIMM DDR4 4000MT/s   | 1        | 7.14%   |
| Corsair RAM CMK128GX4M8A2666C16 16GB DIMM DDR4 2133MT/s  | 1        | 7.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 6        | 42.86%  |
| DDR3 | 6        | 42.86%  |
| DDR5 | 2        | 14.29%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 12       | 85.71%  |
| SODIMM | 2        | 14.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 5        | 35.71%  |
| 32768 | 4        | 28.57%  |
| 16384 | 2        | 14.29%  |
| 4096  | 2        | 14.29%  |
| 2048  | 1        | 7.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 3        | 21.43%  |
| 1800  | 2        | 14.29%  |
| 5600  | 1        | 7.14%   |
| 4800  | 1        | 7.14%   |
| 4000  | 1        | 7.14%   |
| 3600  | 1        | 7.14%   |
| 2933  | 1        | 7.14%   |
| 2667  | 1        | 7.14%   |
| 2400  | 1        | 7.14%   |
| 2133  | 1        | 7.14%   |
| 800   | 1        | 7.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 3        | 50%     |
| Sunplus Innovation Technology | 2        | 33.33%  |
| KYE Systems                   | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Sunplus Full HD webcam          | 2        | 33.33%  |
| Logitech C922 Pro Stream Webcam | 2        | 33.33%  |
| Logitech Webcam C270            | 1        | 16.67%  |
| KYE Systems FaceCam 1320        | 1        | 16.67%  |

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
| 0     | 20       | 68.97%  |
| 1     | 7        | 24.14%  |
| 5     | 1        | 3.45%   |
| 2     | 1        | 3.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 5        | 35.71%  |
| Graphics card            | 2        | 14.29%  |
| Bluetooth                | 2        | 14.29%  |
| Unassigned class         | 1        | 7.14%   |
| Storage/ata              | 1        | 7.14%   |
| Sound                    | 1        | 7.14%   |
| Dvb card                 | 1        | 7.14%   |
| Communication controller | 1        | 7.14%   |

