CentOS 9 - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for CentOS 9.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/CentOS_9/Desktop/README.md) and [notebooks](/Dist/CentOS_9/Notebook/README.md).

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

Total: 55

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | P8H61/USB3                  | Desktop     | [d93dbf6db3](https://linux-hardware.org/?probe=d93dbf6db3) | Jun 01, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [16c7ca187a](https://linux-hardware.org/?probe=16c7ca187a) | Jun 01, 2023 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [a69366e2b7](https://linux-hardware.org/?probe=a69366e2b7) | May 29, 2023 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [07202660b9](https://linux-hardware.org/?probe=07202660b9) | May 26, 2023 |
| Acer          | Predator G3-605             | Desktop     | [6f91022c83](https://linux-hardware.org/?probe=6f91022c83) | May 04, 2023 |
| Colorful T... | CVN Z590 GAMING PRO V20     | Desktop     | [209ec5e477](https://linux-hardware.org/?probe=209ec5e477) | Apr 28, 2023 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | Notebook    | [61408603be](https://linux-hardware.org/?probe=61408603be) | Apr 21, 2023 |
| Intel         | NUC12WSBi5 M63398-302       | Mini pc     | [785a41f4e9](https://linux-hardware.org/?probe=785a41f4e9) | Apr 02, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [d148f91b52](https://linux-hardware.org/?probe=d148f91b52) | Mar 15, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [eecf7c5d8b](https://linux-hardware.org/?probe=eecf7c5d8b) | Mar 13, 2023 |
| ASUSTek       | Q550LF                      | Notebook    | [793bf0d1d8](https://linux-hardware.org/?probe=793bf0d1d8) | Mar 06, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [a7270cf962](https://linux-hardware.org/?probe=a7270cf962) | Feb 19, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [a67a4d078f](https://linux-hardware.org/?probe=a67a4d078f) | Jan 21, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [259556fd6f](https://linux-hardware.org/?probe=259556fd6f) | Jan 11, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [b9522e3683](https://linux-hardware.org/?probe=b9522e3683) | Jan 02, 2023 |
| Lenovo        | ThinkPad T430 2347DE9       | Notebook    | [7b4305ce5a](https://linux-hardware.org/?probe=7b4305ce5a) | Dec 27, 2022 |
| Lenovo        | ThinkPad T430 2347DE9       | Notebook    | [afc91c5da0](https://linux-hardware.org/?probe=afc91c5da0) | Dec 24, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [117f4c04d6](https://linux-hardware.org/?probe=117f4c04d6) | Dec 21, 2022 |
| Dell          | 0NKW6Y A02                  | Desktop     | [f20d5b9289](https://linux-hardware.org/?probe=f20d5b9289) | Dec 07, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [b2aac5194c](https://linux-hardware.org/?probe=b2aac5194c) | Dec 06, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [6ca3196f35](https://linux-hardware.org/?probe=6ca3196f35) | Dec 05, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [558174d9f4](https://linux-hardware.org/?probe=558174d9f4) | Nov 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e840ded8c0](https://linux-hardware.org/?probe=e840ded8c0) | Nov 09, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [b981adc21a](https://linux-hardware.org/?probe=b981adc21a) | Nov 07, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [8ee7171b61](https://linux-hardware.org/?probe=8ee7171b61) | Nov 03, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [9598c40129](https://linux-hardware.org/?probe=9598c40129) | Oct 27, 2022 |
| Zvezda        | Arctur test_serv            | Server      | [0ace3642f0](https://linux-hardware.org/?probe=0ace3642f0) | Oct 21, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [8bd50f112b](https://linux-hardware.org/?probe=8bd50f112b) | Oct 15, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [88497baf29](https://linux-hardware.org/?probe=88497baf29) | Oct 15, 2022 |
| Intel         | D34010WYK H14771-303        | Desktop     | [e58d9849a5](https://linux-hardware.org/?probe=e58d9849a5) | Oct 06, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [2293724ae2](https://linux-hardware.org/?probe=2293724ae2) | Sep 19, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [09db514840](https://linux-hardware.org/?probe=09db514840) | Sep 19, 2022 |
| Lenovo        | ThinkPad T430 2349DG5       | Notebook    | [740898521d](https://linux-hardware.org/?probe=740898521d) | Aug 27, 2022 |
| AZW           | SER V01                     | Mini pc     | [873aac6635](https://linux-hardware.org/?probe=873aac6635) | Aug 11, 2022 |
| Timi          | Mi NoteBook Horizon Edit... | Notebook    | [52a0cb298b](https://linux-hardware.org/?probe=52a0cb298b) | Aug 09, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [e115d77240](https://linux-hardware.org/?probe=e115d77240) | Aug 07, 2022 |
| Lenovo        | G410 20237                  | Notebook    | [daea3239f0](https://linux-hardware.org/?probe=daea3239f0) | Aug 05, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [46201e4773](https://linux-hardware.org/?probe=46201e4773) | Jul 27, 2022 |
| Dell          | CS24-TY                     | Server      | [230ad2532f](https://linux-hardware.org/?probe=230ad2532f) | Jul 24, 2022 |
| NCR           | Pocono BIOS.6.0             | Desktop     | [ae030a0cda](https://linux-hardware.org/?probe=ae030a0cda) | Jul 15, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [c45dba9246](https://linux-hardware.org/?probe=c45dba9246) | Jun 26, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [3d36beed4b](https://linux-hardware.org/?probe=3d36beed4b) | Jun 25, 2022 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | Desktop     | [88a7cd954c](https://linux-hardware.org/?probe=88a7cd954c) | Jun 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [29f2cd44d5](https://linux-hardware.org/?probe=29f2cd44d5) | Jun 11, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [9a331b90a5](https://linux-hardware.org/?probe=9a331b90a5) | May 19, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [4c3a3b2de2](https://linux-hardware.org/?probe=4c3a3b2de2) | May 17, 2022 |
| MSI           | Katana GF76 12UE            | Notebook    | [460e78b93a](https://linux-hardware.org/?probe=460e78b93a) | May 15, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [a7fb96d9aa](https://linux-hardware.org/?probe=a7fb96d9aa) | May 13, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | Notebook    | [228ec1a5f7](https://linux-hardware.org/?probe=228ec1a5f7) | Apr 24, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [db53151112](https://linux-hardware.org/?probe=db53151112) | Apr 19, 2022 |
| Timi          | RedmiBook 16                | Notebook    | [bef46c5065](https://linux-hardware.org/?probe=bef46c5065) | Mar 20, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [1f84b1e42d](https://linux-hardware.org/?probe=1f84b1e42d) | Mar 11, 2022 |
| Lenovo        | ThinkPad T460s 20FAS5WX0... | Notebook    | [6fa180d5fa](https://linux-hardware.org/?probe=6fa180d5fa) | Feb 06, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [cf90d5430c](https://linux-hardware.org/?probe=cf90d5430c) | Feb 04, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [0c661cb2d6](https://linux-hardware.org/?probe=0c661cb2d6) | Nov 12, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.14.0-86.el9.x86_64           | 3         | 6.98%   |
| 5.14.0-202.el9.x86_64          | 3         | 6.98%   |
| 5.14.0-134.el9.x86_64          | 3         | 6.98%   |
| 5.14.0-214.el9.x86_64          | 2         | 4.65%   |
| 5.14.0-183.el9.x86_64          | 2         | 4.65%   |
| 5.14.0-171.el9.x86_64          | 2         | 4.65%   |
| 5.14.0-148.el9.x86_64          | 2         | 4.65%   |
| 6.1.8-1.el9.elrepo.x86_64      | 1         | 2.33%   |
| 6.1.1                          | 1         | 2.33%   |
| 5.17.2-lqx3.0.el9.x86_64       | 1         | 2.33%   |
| 5.14.0-78.el9.x86_64           | 1         | 2.33%   |
| 5.14.0-71.el9.x86_64           | 1         | 2.33%   |
| 5.14.0-66.el9.x86_64           | 1         | 2.33%   |
| 5.14.0-52.el9.x86_64           | 1         | 2.33%   |
| 5.14.0-44.el9.x86_64           | 1         | 2.33%   |
| 5.14.0-319.el9.x86_64          | 1         | 2.33%   |
| 5.14.0-316.el9.x86_64          | 1         | 2.33%   |
| 5.14.0-305.el9.x86_64          | 1         | 2.33%   |
| 5.14.0-302.el9.x86_64          | 1         | 2.33%   |
| 5.14.0-299.el9.x86_64          | 1         | 2.33%   |
| 5.14.0-289.el9.x86_64          | 1         | 2.33%   |
| 5.14.0-283.el9.x86_64          | 1         | 2.33%   |
| 5.14.0-282.el9.x86_64          | 1         | 2.33%   |
| 5.14.0-267.el9.x86_64          | 1         | 2.33%   |
| 5.14.0-226.el9.x86_64          | 1         | 2.33%   |
| 5.14.0-200.el9.x86_64          | 1         | 2.33%   |
| 5.14.0-163.el9.x86_64          | 1         | 2.33%   |
| 5.14.0-130.rt21.130.el9.x86_64 | 1         | 2.33%   |
| 5.14.0-130.el9.x86_64          | 1         | 2.33%   |
| 5.14.0-12.el9.x86_64           | 1         | 2.33%   |
| 5.14.0-115.el9.x86_64          | 1         | 2.33%   |
| 5.14.0-109.el9.x86_64          | 1         | 2.33%   |
| 5.14.0-105.el9.x86_64          | 1         | 2.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 37        | 92.5%   |
| 6.1.8   | 1         | 2.5%    |
| 6.1.1   | 1         | 2.5%    |
| 5.17.2  | 1         | 2.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 37        | 92.5%   |
| 6.1     | 2         | 5%      |
| 5.17    | 1         | 2.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 39        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 34        | 87.18%  |
| KDE5          | 2         | 5.13%   |
| GNOME Classic | 2         | 5.13%   |
| Unknown       | 1         | 2.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 27        | 67.5%   |
| X11     | 11        | 27.5%   |
| Tty     | 2         | 5%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 22        | 55%     |
| GDM     | 16        | 40%     |
| SDDM    | 2         | 5%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 25        | 64.1%   |
| zh_CN | 2         | 5.13%   |
| ru_RU | 2         | 5.13%   |
| it_IT | 2         | 5.13%   |
| de_DE | 2         | 5.13%   |
| sv_SE | 1         | 2.56%   |
| ru_UA | 1         | 2.56%   |
| pt_BR | 1         | 2.56%   |
| ja_JP | 1         | 2.56%   |
| fr_FR | 1         | 2.56%   |
| en_IN | 1         | 2.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 28        | 71.79%  |
| BIOS | 11        | 28.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 36        | 92.31%  |
| Ext4 | 3         | 7.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 21        | 51.22%  |
| GPT     | 14        | 34.15%  |
| MBR     | 6         | 14.63%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 87.5%   |
| Yes       | 5         | 12.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 31        | 75.61%  |
| Yes       | 10        | 24.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 9         | 23.08%  |
| ASUSTek Computer    | 8         | 20.51%  |
| Acer                | 4         | 10.26%  |
| Intel               | 3         | 7.69%   |
| Hewlett-Packard     | 3         | 7.69%   |
| Timi                | 2         | 5.13%   |
| MSI                 | 2         | 5.13%   |
| Gigabyte Technology | 2         | 5.13%   |
| Zvezda              | 1         | 2.56%   |
| Razer               | 1         | 2.56%   |
| IP3 Tech            | 1         | 2.56%   |
| Dell                | 1         | 2.56%   |
| Colorful Technology | 1         | 2.56%   |
| AZW                 | 1         | 2.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Zvezda Altair Z                      | 1         | 2.56%   |
| Timi RedmiBook 16                    | 1         | 2.56%   |
| Timi Mi NoteBook Horizon Edition 14  | 1         | 2.56%   |
| Razer Blade 15 (2022) - RZ09-0421    | 1         | 2.56%   |
| MSI MS-7B79                          | 1         | 2.56%   |
| MSI Katana GF76 12UE                 | 1         | 2.56%   |
| Lenovo Yoga S740-14IIL 81RS          | 1         | 2.56%   |
| Lenovo ThinkPad T460s 20FAS5WX00     | 1         | 2.56%   |
| Lenovo ThinkPad T430 2349DG5         | 1         | 2.56%   |
| Lenovo ThinkPad T430 2347DE9         | 1         | 2.56%   |
| Lenovo ThinkPad L14 Gen 1 20U5S0NT00 | 1         | 2.56%   |
| Lenovo Legion 5P 15IMH05H 82AW       | 1         | 2.56%   |
| Lenovo IdeaPad S145-15IWL 81S9       | 1         | 2.56%   |
| Lenovo G580 20150                    | 1         | 2.56%   |
| Lenovo G410 20237                    | 1         | 2.56%   |
| IP3 Tech HeroBox                     | 1         | 2.56%   |
| Intel NUC12WSHi7                     | 1         | 2.56%   |
| Intel NUC12WSHi5                     | 1         | 2.56%   |
| Intel D34010WYK H14771-303           | 1         | 2.56%   |
| HP Pavilion Gaming Laptop 15-ec0xxx  | 1         | 2.56%   |
| HP EliteBook 840 G3                  | 1         | 2.56%   |
| HP EliteBook 840 G1                  | 1         | 2.56%   |
| Gigabyte X99-UD4-CF                  | 1         | 2.56%   |
| Gigabyte 970A-DS3P                   | 1         | 2.56%   |
| Dell OptiPlex 790                    | 1         | 2.56%   |
| Colorful CVN Z590 GAMING PRO         | 1         | 2.56%   |
| AZW SER                              | 1         | 2.56%   |
| ASUS TUF Gaming X570-PLUS            | 1         | 2.56%   |
| ASUS ROG STRIX B560-G GAMING WIFI    | 1         | 2.56%   |
| ASUS Q550LF                          | 1         | 2.56%   |
| ASUS PRIME H670-PLUS D4              | 1         | 2.56%   |
| ASUS P8H67-M LE                      | 1         | 2.56%   |
| ASUS P8H61/USB3                      | 1         | 2.56%   |
| ASUS N751JK                          | 1         | 2.56%   |
| ASUS All Series                      | 1         | 2.56%   |
| Acer Swift SF314-512                 | 1         | 2.56%   |
| Acer Predator G3-605                 | 1         | 2.56%   |
| Acer Aspire E1-570G                  | 1         | 2.56%   |
| Acer Aspire 5740                     | 1         | 2.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 4         | 10.26%  |
| HP EliteBook        | 2         | 5.13%   |
| Acer Aspire         | 2         | 5.13%   |
| Zvezda Altair       | 1         | 2.56%   |
| Timi RedmiBook      | 1         | 2.56%   |
| Timi Mi             | 1         | 2.56%   |
| Razer Blade         | 1         | 2.56%   |
| MSI MS-7B79         | 1         | 2.56%   |
| MSI Katana          | 1         | 2.56%   |
| Lenovo Yoga         | 1         | 2.56%   |
| Lenovo Legion       | 1         | 2.56%   |
| Lenovo IdeaPad      | 1         | 2.56%   |
| Lenovo G580         | 1         | 2.56%   |
| Lenovo G410         | 1         | 2.56%   |
| IP3 Tech HeroBox    | 1         | 2.56%   |
| Intel NUC12WSHi7    | 1         | 2.56%   |
| Intel NUC12WSHi5    | 1         | 2.56%   |
| Intel D34010WYK     | 1         | 2.56%   |
| HP Pavilion         | 1         | 2.56%   |
| Gigabyte X99-UD4-CF | 1         | 2.56%   |
| Gigabyte 970A-DS3P  | 1         | 2.56%   |
| Dell OptiPlex       | 1         | 2.56%   |
| Colorful CVN        | 1         | 2.56%   |
| AZW SER             | 1         | 2.56%   |
| ASUS TUF            | 1         | 2.56%   |
| ASUS ROG            | 1         | 2.56%   |
| ASUS Q550LF         | 1         | 2.56%   |
| ASUS PRIME          | 1         | 2.56%   |
| ASUS P8H67-M        | 1         | 2.56%   |
| ASUS P8H61          | 1         | 2.56%   |
| ASUS N751JK         | 1         | 2.56%   |
| ASUS All            | 1         | 2.56%   |
| Acer Swift          | 1         | 2.56%   |
| Acer Predator       | 1         | 2.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 8         | 20.51%  |
| 2022 | 5         | 12.82%  |
| 2021 | 5         | 12.82%  |
| 2012 | 5         | 12.82%  |
| 2020 | 4         | 10.26%  |
| 2019 | 4         | 10.26%  |
| 2016 | 2         | 5.13%   |
| 2014 | 2         | 5.13%   |
| 2011 | 2         | 5.13%   |
| 2018 | 1         | 2.56%   |
| 2009 | 1         | 2.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 21        | 53.85%  |
| Desktop  | 13        | 33.33%  |
| Mini pc  | 4         | 10.26%  |
| Server   | 1         | 2.56%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 36        | 92.31%  |
| Enabled  | 3         | 7.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 39        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 15        | 38.46%  |
| 8.01-16.0       | 10        | 25.64%  |
| 32.01-64.0      | 6         | 15.38%  |
| 64.01-256.0     | 3         | 7.69%   |
| 3.01-4.0        | 2         | 5.13%   |
| 16.01-24.0      | 2         | 5.13%   |
| More than 256.0 | 1         | 2.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 17        | 40.48%  |
| 4.01-8.0  | 9         | 21.43%  |
| 3.01-4.0  | 8         | 19.05%  |
| 1.01-2.0  | 3         | 7.14%   |
| 8.01-16.0 | 3         | 7.14%   |
| 0.51-1.0  | 2         | 4.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 20        | 51.28%  |
| 2      | 10        | 25.64%  |
| 4      | 4         | 10.26%  |
| 3      | 4         | 10.26%  |
| 10     | 1         | 2.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 30        | 76.92%  |
| Yes       | 9         | 23.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 87.18%  |
| No        | 5         | 12.82%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 82.05%  |
| No        | 7         | 17.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 74.36%  |
| No        | 10        | 25.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 8         | 20.51%  |
| Germany     | 3         | 7.69%   |
| China       | 3         | 7.69%   |
| Bulgaria    | 3         | 7.69%   |
| Ukraine     | 2         | 5.13%   |
| Italy       | 2         | 5.13%   |
| Canada      | 2         | 5.13%   |
| Uzbekistan  | 1         | 2.56%   |
| Switzerland | 1         | 2.56%   |
| Sweden      | 1         | 2.56%   |
| Russia      | 1         | 2.56%   |
| Poland      | 1         | 2.56%   |
| Netherlands | 1         | 2.56%   |
| Myanmar     | 1         | 2.56%   |
| Kazakhstan  | 1         | 2.56%   |
| Japan       | 1         | 2.56%   |
| India       | 1         | 2.56%   |
| France      | 1         | 2.56%   |
| Finland     | 1         | 2.56%   |
| Colombia    | 1         | 2.56%   |
| Chile       | 1         | 2.56%   |
| Brazil      | 1         | 2.56%   |
| Belarus     | 1         | 2.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sofia          | 2         | 4.88%   |
| Bristow        | 2         | 4.88%   |
| Beijing        | 2         | 4.88%   |
| Yangon         | 1         | 2.44%   |
| Wuhan          | 1         | 2.44%   |
| Vitebsk        | 1         | 2.44%   |
| Tomah          | 1         | 2.44%   |
| Tashkent       | 1         | 2.44%   |
| Stromberg      | 1         | 2.44%   |
| Stockholm      | 1         | 2.44%   |
| Soest          | 1         | 2.44%   |
| Schemmerhofen  | 1         | 2.44%   |
| Ruda Śląska  | 1         | 2.44%   |
| Rome           | 1         | 2.44%   |
| Ribeirao Preto | 1         | 2.44%   |
| Quitman        | 1         | 2.44%   |
| Puente Alto    | 1         | 2.44%   |
| Portland       | 1         | 2.44%   |
| Persan         | 1         | 2.44%   |
| Okazaki        | 1         | 2.44%   |
| New York       | 1         | 2.44%   |
| New Cumberland | 1         | 2.44%   |
| Mumbai         | 1         | 2.44%   |
| Moscow         | 1         | 2.44%   |
| Meieki         | 1         | 2.44%   |
| L'Isle-Adam    | 1         | 2.44%   |
| Kyiv           | 1         | 2.44%   |
| Kramatorsk     | 1         | 2.44%   |
| Helsinki       | 1         | 2.44%   |
| Dortmund       | 1         | 2.44%   |
| Burgas         | 1         | 2.44%   |
| Bogotá        | 1         | 2.44%   |
| Birmensdorf    | 1         | 2.44%   |
| Battle Creek   | 1         | 2.44%   |
| Barrie         | 1         | 2.44%   |
| Almaty         | 1         | 2.44%   |
| Airdrie        | 1         | 2.44%   |
| Adelfia        | 1         | 2.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 11        | 15     | 17.74%  |
| WDC                       | 9         | 11     | 14.52%  |
| Kingston                  | 8         | 9      | 12.9%   |
| Seagate                   | 6         | 8      | 9.68%   |
| Toshiba                   | 3         | 4      | 4.84%   |
| Intel                     | 3         | 3      | 4.84%   |
| HGST                      | 3         | 4      | 4.84%   |
| SK hynix                  | 2         | 2      | 3.23%   |
| Micron Technology         | 2         | 2      | 3.23%   |
| WD MediaMax               | 1         | 1      | 1.61%   |
| Unknown                   | 1         | 1      | 1.61%   |
| Team                      | 1         | 2      | 1.61%   |
| SanDisk                   | 1         | 6      | 1.61%   |
| Plextor                   | 1         | 1      | 1.61%   |
| Phison                    | 1         | 1      | 1.61%   |
| Netac                     | 1         | 2      | 1.61%   |
| Micron/Crucial Technology | 1         | 1      | 1.61%   |
| LITEON                    | 1         | 1      | 1.61%   |
| Hjwdz                     | 1         | 1      | 1.61%   |
| Hitachi                   | 1         | 1      | 1.61%   |
| Hewlett-Packard           | 1         | 1      | 1.61%   |
| Gigabyte Technology       | 1         | 2      | 1.61%   |
| Crucial                   | 1         | 6      | 1.61%   |
| A-DATA Technology         | 1         | 1      | 1.61%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 2         | 2.99%   |
| Samsung MZNLH512HALU-00000 512GB SSD                | 2         | 2.99%   |
| Micron 2450_MTFDKBA512TFK 512GB                     | 2         | 2.99%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                    | 1         | 1.49%   |
| WDC WD6400BEVT-22A0RT0 640GB                        | 1         | 1.49%   |
| WDC WD5000LPLX-60ZNTT1 500GB                        | 1         | 1.49%   |
| WDC WD3200AAKX-753CA1 320GB                         | 1         | 1.49%   |
| WDC WD2500AAJS-60M0A0 250GB                         | 1         | 1.49%   |
| WDC WD22EJRX-89BEMY0 2TB                            | 1         | 1.49%   |
| WDC WD2003FZEX-00Z4SA0 2TB                          | 1         | 1.49%   |
| WDC WD10EZEX-60M2NA0 1TB                            | 1         | 1.49%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 1         | 1.49%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 1         | 1.49%   |
| WD MediaMax WL750GSA6472 752GB                      | 1         | 1.49%   |
| Unknown MMC Card  7GB                               | 1         | 1.49%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 1.49%   |
| Toshiba MK2561GSYN 250GB                            | 1         | 1.49%   |
| Toshiba DT01ACA100 1TB                              | 1         | 1.49%   |
| Team T253X1480G 480GB SSD                           | 1         | 1.49%   |
| SK hynix NVMe SSD Drive 256GB                       | 1         | 1.49%   |
| SK hynix BC501 NVMe 256GB                           | 1         | 1.49%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1.49%   |
| Seagate ST3500413AS 500GB                           | 1         | 1.49%   |
| Seagate ST3250820AS 250GB                           | 1         | 1.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1.49%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1.49%   |
| Seagate FireCuda 520 SSD ZP2000GM30002 2TB          | 1         | 1.49%   |
| Seagate FireCuda 520 SSD ZP1000GM30002 1TB          | 1         | 1.49%   |
| Sandisk WD_BLACK SN770 1TB                          | 1         | 1.49%   |
| SanDisk SDSSDH3 1T00 1TB                            | 1         | 1.49%   |
| Samsung SSD 870 QVO 2TB                             | 1         | 1.49%   |
| Samsung SSD 870 EVO 250GB                           | 1         | 1.49%   |
| Samsung PSSD T7 1TB                                 | 1         | 1.49%   |
| Samsung NVMe SSD Drive 1TB                          | 1         | 1.49%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 1         | 1.49%   |
| Samsung MZALQ512HALU-000L2 512GB                    | 1         | 1.49%   |
| Samsung MZ7LN256HAJQ-00000 256GB SSD                | 1         | 1.49%   |
| Samsung MZ7LH240HAHQ-00005 240GB                    | 1         | 1.49%   |
| Samsung MZ7LH240HAHQ-00005 1GB SSD                  | 1         | 1.49%   |
| Plextor PX-256M8VC 256GB SSD                        | 1         | 1.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor      | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| WDC         | 8         | 10     | 38.1%   |
| Seagate     | 5         | 6      | 23.81%  |
| Toshiba     | 3         | 4      | 14.29%  |
| HGST        | 3         | 4      | 14.29%  |
| WD MediaMax | 1         | 1      | 4.76%   |
| Hitachi     | 1         | 1      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 10     | 29.17%  |
| Kingston            | 6         | 7      | 25%     |
| WDC                 | 1         | 1      | 4.17%   |
| Team                | 1         | 2      | 4.17%   |
| SanDisk             | 1         | 3      | 4.17%   |
| Plextor             | 1         | 1      | 4.17%   |
| Netac               | 1         | 2      | 4.17%   |
| LITEON              | 1         | 1      | 4.17%   |
| Intel               | 1         | 1      | 4.17%   |
| Hewlett-Packard     | 1         | 1      | 4.17%   |
| Gigabyte Technology | 1         | 2      | 4.17%   |
| Crucial             | 1         | 6      | 4.17%   |
| A-DATA Technology   | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 20        | 38     | 37.74%  |
| HDD     | 16        | 26     | 30.19%  |
| NVMe    | 15        | 20     | 28.3%   |
| MMC     | 1         | 1      | 1.89%   |
| Unknown | 1         | 1      | 1.89%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 29        | 62     | 61.7%   |
| NVMe | 15        | 20     | 31.91%  |
| SAS  | 2         | 3      | 4.26%   |
| MMC  | 1         | 1      | 2.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 21        | 30     | 53.85%  |
| 0.51-1.0   | 14        | 29     | 35.9%   |
| 1.01-2.0   | 4         | 5      | 10.26%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 15        | 36.59%  |
| 251-500        | 9         | 21.95%  |
| 1001-2000      | 7         | 17.07%  |
| 501-1000       | 6         | 14.63%  |
| 2001-3000      | 2         | 4.88%   |
| More than 3000 | 1         | 2.44%   |
| 21-50          | 1         | 2.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 19        | 47.5%   |
| 251-500        | 5         | 12.5%   |
| 101-250        | 5         | 12.5%   |
| 51-100         | 5         | 12.5%   |
| 21-50          | 2         | 5%      |
| 501-1000       | 2         | 5%      |
| More than 3000 | 1         | 2.5%    |
| 1001-2000      | 1         | 2.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD5000LPLX-60ZNTT1 500GB    | 1         | 1      | 20%     |
| WDC WD10EZEX-60M2NA0 1TB        | 1         | 1      | 20%     |
| Toshiba MK2561GSYN 250GB        | 1         | 1      | 20%     |
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 20%     |
| Seagate ST3250820AS 250GB       | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 40%     |
| Seagate | 2         | 2      | 40%     |
| Toshiba | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 40%     |
| Seagate | 2         | 2      | 40%     |
| Toshiba | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 5      | 100%    |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 25        | 50     | 55.56%  |
| Works    | 16        | 31     | 35.56%  |
| Malfunc  | 4         | 5      | 8.89%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 31        | 59.62%  |
| AMD                         | 5         | 9.62%   |
| Samsung Electronics         | 4         | 7.69%   |
| SK hynix                    | 2         | 3.85%   |
| Micron Technology           | 2         | 3.85%   |
| Kingston Technology Company | 2         | 3.85%   |
| Silicon Image               | 1         | 1.92%   |
| Seagate Technology          | 1         | 1.92%   |
| SanDisk                     | 1         | 1.92%   |
| Phison Electronics          | 1         | 1.92%   |
| Micron/Crucial Technology   | 1         | 1.92%   |
| LSI Logic / Symbios Logic   | 1         | 1.92%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 7.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 7.27%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 4         | 7.27%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 3         | 5.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 5.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3         | 5.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 3.64%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 3.64%   |
| Micron NVMe Storage Controller                                                 | 2         | 3.64%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 3.64%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 3.64%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 1         | 1.82%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 1.82%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1         | 1.82%   |
| Seagate FireCuda 520 SSD                                                       | 1         | 1.82%   |
| SanDisk WD Black SN770 NVMe SSD                                                | 1         | 1.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.82%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.82%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 1.82%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                        | 1         | 1.82%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 1.82%   |
| Kingston Company NVMe Controller                                               | 1         | 1.82%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.82%   |
| Intel SSD 660P Series                                                          | 1         | 1.82%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 1.82%   |
| Intel Non-Volatile memory controller                                           | 1         | 1.82%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.82%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.82%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 1         | 1.82%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1         | 1.82%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.82%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.82%   |
| AMD 400 Series Chipset SATA Controller                                         | 1         | 1.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 33        | 63.46%  |
| NVMe | 15        | 28.85%  |
| RAID | 4         | 7.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 32        | 82.05%  |
| AMD    | 7         | 17.95%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-1260P                  | 2         | 5.13%   |
| Intel Xeon Gold 6326 CPU @ 2.90GHz            | 1         | 2.56%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 2.56%   |
| Intel Core i7-5930K CPU @ 3.50GHz             | 1         | 2.56%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 2.56%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 2.56%   |
| Intel Core i7-2600K CPU @ 3.40GHz             | 1         | 2.56%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 2.56%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 2.56%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 2.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 2.56%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 1         | 2.56%   |
| Intel Core i5-4440 CPU @ 3.10GHz              | 1         | 2.56%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 2.56%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 2.56%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1         | 2.56%   |
| Intel Core i5-3380M CPU @ 2.90GHz             | 1         | 2.56%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 2.56%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 2.56%   |
| Intel Core i5-2400S CPU @ 2.50GHz             | 1         | 2.56%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 1         | 2.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2.56%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 1         | 2.56%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 2.56%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 2.56%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 2.56%   |
| Intel 12th Gen Core i7-12800H                 | 1         | 2.56%   |
| Intel 12th Gen Core i7-12700H                 | 1         | 2.56%   |
| Intel 12th Gen Core i5-12600K                 | 1         | 2.56%   |
| Intel 12th Gen Core i5-1240P                  | 1         | 2.56%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz        | 1         | 2.56%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 1         | 2.56%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 2.56%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 2.56%   |
| AMD Ryzen 5 3600 6-Core Processor             | 1         | 2.56%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 2.56%   |
| AMD Ryzen 3 PRO 4450U with Radeon Graphics    | 1         | 2.56%   |
| AMD FX-8120 Eight-Core Processor              | 1         | 2.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Computers | Percent |
|-----------------|-----------|---------|
| Intel Core i5   | 14        | 35.9%   |
| Other           | 7         | 17.95%  |
| Intel Core i7   | 7         | 17.95%  |
| AMD Ryzen 5     | 3         | 7.69%   |
| Intel Core i3   | 2         | 5.13%   |
| Intel Xeon Gold | 1         | 2.56%   |
| Intel Celeron   | 1         | 2.56%   |
| AMD Ryzen 9     | 1         | 2.56%   |
| AMD Ryzen 7     | 1         | 2.56%   |
| AMD Ryzen 3 PRO | 1         | 2.56%   |
| AMD FX          | 1         | 2.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 13        | 33.33%  |
| 2      | 11        | 28.21%  |
| 6      | 6         | 15.38%  |
| 12     | 3         | 7.69%   |
| 14     | 2         | 5.13%   |
| 32     | 1         | 2.56%   |
| 16     | 1         | 2.56%   |
| 10     | 1         | 2.56%   |
| 8      | 1         | 2.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 38        | 97.44%  |
| 2      | 1         | 2.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 30        | 76.92%  |
| 1      | 9         | 23.08%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 39        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x906a3    | 5         | 12.82%  |
| 0x306c3    | 4         | 10.26%  |
| 0x306a9    | 4         | 10.26%  |
| Unknown    | 4         | 10.26%  |
| 0x40651    | 3         | 7.69%   |
| 0x806ec    | 2         | 5.13%   |
| 0x406e3    | 2         | 5.13%   |
| 0x08600106 | 2         | 5.13%   |
| 0xa0671    | 1         | 2.56%   |
| 0xa0653    | 1         | 2.56%   |
| 0xa0652    | 1         | 2.56%   |
| 0x90672    | 1         | 2.56%   |
| 0x706e5    | 1         | 2.56%   |
| 0x706a8    | 1         | 2.56%   |
| 0x606a6    | 1         | 2.56%   |
| 0x306f2    | 1         | 2.56%   |
| 0x206a7    | 1         | 2.56%   |
| 0x20652    | 1         | 2.56%   |
| 0x0a201016 | 1         | 2.56%   |
| 0x08701013 | 1         | 2.56%   |
| 0x0600063d | 1         | 2.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 8         | 20.51%  |
| Alderlake Hybrid | 6         | 15.38%  |
| IvyBridge        | 5         | 12.82%  |
| Zen 2            | 4         | 10.26%  |
| Icelake          | 3         | 7.69%   |
| Skylake          | 2         | 5.13%   |
| SandyBridge      | 2         | 5.13%   |
| KabyLake         | 2         | 5.13%   |
| CometLake        | 2         | 5.13%   |
| Zen+             | 1         | 2.56%   |
| Zen 3            | 1         | 2.56%   |
| Westmere         | 1         | 2.56%   |
| Goldmont plus    | 1         | 2.56%   |
| Bulldozer        | 1         | 2.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 22        | 44%     |
| Nvidia            | 16        | 32%     |
| AMD               | 11        | 22%     |
| ASPEED Technology | 1         | 2%      |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P Integrated Graphics Controller                         | 5         | 9.62%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 7.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 5.77%   |
| AMD Renoir                                                                | 3         | 5.77%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 3.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 2         | 3.85%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 1.92%   |
| Nvidia TU117 [GeForce GTX 1650]                                           | 1         | 1.92%   |
| Nvidia TU116 [GeForce GTX 1660]                                           | 1         | 1.92%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 1         | 1.92%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 1.92%   |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 1.92%   |
| Nvidia GP107M [GeForce MX350]                                             | 1         | 1.92%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                         | 1         | 1.92%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 1.92%   |
| Nvidia GM107M [GeForce GTX 850M]                                          | 1         | 1.92%   |
| Nvidia GM107 [GeForce GTX 745]                                            | 1         | 1.92%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 1         | 1.92%   |
| Nvidia GK208B [GeForce GT 730]                                            | 1         | 1.92%   |
| Nvidia GK107M [GeForce GT 745M]                                           | 1         | 1.92%   |
| Nvidia GF108M [NVS 5400M]                                                 | 1         | 1.92%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 1.92%   |
| Nvidia GA103M [GeForce RTX 3080 Ti Mobile]                                | 1         | 1.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 1.92%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                 | 1         | 1.92%   |
| Intel Iris Plus Graphics G7                                               | 1         | 1.92%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 1.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 1.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1         | 1.92%   |
| ASPEED Technology ASPEED Graphics Family                                  | 1         | 1.92%   |
| AMD RV370 [Radeon X300/X550/X1050 Series] (Secondary)                     | 1         | 1.92%   |
| AMD RV370 [Radeon X300/X550/X1050 Series]                                 | 1         | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 1.92%   |
| AMD Park [Mobility Radeon HD 5430]                                        | 1         | 1.92%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                              | 1         | 1.92%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]             | 1         | 1.92%   |
| AMD Mars [Radeon HD 8730M]                                                | 1         | 1.92%   |
| AMD Juniper XT [Radeon HD 6770]                                           | 1         | 1.92%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                            | 1         | 1.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 12        | 30.77%  |
| Intel + Nvidia | 9         | 23.08%  |
| 1 x AMD        | 8         | 20.51%  |
| 1 x Nvidia     | 6         | 15.38%  |
| 2 x AMD        | 1         | 2.56%   |
| Intel + AMD    | 1         | 2.56%   |
| 1 x ASPEED     | 1         | 2.56%   |
| AMD + Nvidia   | 1         | 2.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 32        | 80%     |
| Proprietary | 6         | 15%     |
| Unknown     | 2         | 5%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 45.24%  |
| 1.01-2.0   | 5         | 11.9%   |
| 5.01-6.0   | 4         | 9.52%   |
| 3.01-4.0   | 4         | 9.52%   |
| 0.51-1.0   | 4         | 9.52%   |
| 0.01-0.5   | 4         | 9.52%   |
| 8.01-16.0  | 2         | 4.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 16.67%  |
| LG Display          | 6         | 14.29%  |
| Chimei Innolux      | 5         | 11.9%   |
| AU Optronics        | 4         | 9.52%   |
| ViewSonic           | 2         | 4.76%   |
| Hewlett-Packard     | 2         | 4.76%   |
| Goldstar            | 2         | 4.76%   |
| Acer                | 2         | 4.76%   |
| TMX                 | 1         | 2.38%   |
| SKY                 | 1         | 2.38%   |
| PANDA               | 1         | 2.38%   |
| LG Electronics      | 1         | 2.38%   |
| KVM                 | 1         | 2.38%   |
| Iiyama              | 1         | 2.38%   |
| Gigabyte Technology | 1         | 2.38%   |
| Dell                | 1         | 2.38%   |
| CHD                 | 1         | 2.38%   |
| BOE                 | 1         | 2.38%   |
| BenQ                | 1         | 2.38%   |
| AOC                 | 1         | 2.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch           | 1         | 2.38%   |
| ViewSonic PJ402D-2 HCD7B1D 1280x960                                     | 1         | 2.38%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch                 | 1         | 2.38%   |
| SKY 22X1-M225F SKY2150 1920x1080 476x268mm 21.5-inch                    | 1         | 2.38%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 607x345mm 27.5-inch       | 1         | 2.38%   |
| Samsung Electronics SyncMaster SAM05EB 1920x1080 597x336mm 27.0-inch    | 1         | 2.38%   |
| Samsung Electronics SMT23A350 SAM07A7 1920x1080 510x287mm 23.0-inch     | 1         | 2.38%   |
| Samsung Electronics SMEX2220 SAM0686 1920x1080 477x268mm 21.5-inch      | 1         | 2.38%   |
| Samsung Electronics S27C450 SAM09D9 1920x1080 598x336mm 27.0-inch       | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch   | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1         | 2.38%   |
| PANDA LCD Monitor NCP0052 1920x1080 309x174mm 14.0-inch                 | 1         | 2.38%   |
| LG Electronics LCD Monitor LG FULL HD                                   | 1         | 2.38%   |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch            | 1         | 2.38%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch            | 1         | 2.38%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch            | 1         | 2.38%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch             | 1         | 2.38%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch             | 1         | 2.38%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch             | 1         | 2.38%   |
| KVM LCD Monitor17 KVM4308 1280x1024 338x270mm 17.0-inch                 | 1         | 2.38%   |
| Iiyama PL2888H IVM7106 1920x1080 621x341mm 27.9-inch                    | 1         | 2.38%   |
| Hewlett-Packard L185x HWP298C 1366x768 410x230mm 18.5-inch              | 1         | 2.38%   |
| Hewlett-Packard 2159 HWP282C 1920x1080 479x269mm 21.6-inch              | 1         | 2.38%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                    | 1         | 2.38%   |
| Goldstar 22EA53 GSM59A6 1920x1080 477x268mm 21.5-inch                   | 1         | 2.38%   |
| Gigabyte Technology G34WQC A GBT3403 3440x1440 797x334mm 34.0-inch      | 1         | 2.38%   |
| Dell 2408WFP DELA029 1920x1200 519x324mm 24.1-inch                      | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN1608 1920x1080 355x199mm 16.0-inch        | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch         | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch        | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch         | 1         | 2.38%   |
| CHD 24VCF CHD0240 1920x1080 368x207mm 16.6-inch                         | 1         | 2.38%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                    | 1         | 2.38%   |
| BenQ ZOWIE XL LCD BNQ7F83 1920x1080 544x303mm 24.5-inch                 | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO5A3D 1920x1080 309x174mm 14.0-inch          | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch          | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch           | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO0BA2 2560x1440 309x174mm 14.0-inch          | 1         | 2.38%   |
| AOC LCD Monitor 24G1WG4 3840x1080                                       | 1         | 2.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 21        | 53.85%  |
| 1366x768 (WXGA)   | 6         | 15.38%  |
| 3840x2160 (4K)    | 2         | 5.13%   |
| 1600x900 (HD+)    | 2         | 5.13%   |
| 3840x1080         | 1         | 2.56%   |
| 3440x1440         | 1         | 2.56%   |
| 3200x2000         | 1         | 2.56%   |
| 2560x1440 (QHD)   | 1         | 2.56%   |
| 1920x1200 (WUXGA) | 1         | 2.56%   |
| 1280x960          | 1         | 2.56%   |
| 1280x1024 (SXGA)  | 1         | 2.56%   |
| Unknown           | 1         | 2.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 14      | 9         | 21.95%  |
| 15      | 7         | 17.07%  |
| 21      | 6         | 14.63%  |
| 27      | 5         | 12.2%   |
| 24      | 3         | 7.32%   |
| 23      | 2         | 4.88%   |
| Unknown | 2         | 4.88%   |
| 84      | 1         | 2.44%   |
| 34      | 1         | 2.44%   |
| 19      | 1         | 2.44%   |
| 18      | 1         | 2.44%   |
| 17      | 1         | 2.44%   |
| 16      | 1         | 2.44%   |
| 13      | 1         | 2.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 42.5%   |
| 501-600     | 7         | 17.5%   |
| 401-500     | 7         | 17.5%   |
| 351-400     | 3         | 7.5%    |
| 601-700     | 2         | 5%      |
| Unknown     | 2         | 5%      |
| 701-800     | 1         | 2.5%    |
| 1501-2000   | 1         | 2.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 29        | 82.86%  |
| 16/10   | 2         | 5.71%   |
| 5/4     | 1         | 2.86%   |
| 4/3     | 1         | 2.86%   |
| 21/9    | 1         | 2.86%   |
| Unknown | 1         | 2.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 10        | 25%     |
| 101-110        | 7         | 17.5%   |
| 201-250        | 6         | 15%     |
| 301-350        | 5         | 12.5%   |
| 151-200        | 3         | 7.5%    |
| 251-300        | 2         | 5%      |
| Unknown        | 2         | 5%      |
| More than 1000 | 1         | 2.5%    |
| 351-500        | 1         | 2.5%    |
| 141-150        | 1         | 2.5%    |
| 121-130        | 1         | 2.5%    |
| 111-120        | 1         | 2.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 13        | 33.33%  |
| 101-120       | 12        | 30.77%  |
| 51-100        | 10        | 25.64%  |
| Unknown       | 2         | 5.13%   |
| More than 240 | 1         | 2.56%   |
| 161-240       | 1         | 2.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 29        | 72.5%   |
| 2     | 6         | 15%     |
| 0     | 4         | 10%     |
| 3     | 1         | 2.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 26        | 41.94%  |
| Realtek Semiconductor             | 15        | 24.19%  |
| Qualcomm Atheros                  | 9         | 14.52%  |
| Broadcom                          | 3         | 4.84%   |
| Xiaomi                            | 1         | 1.61%   |
| U-Blox                            | 1         | 1.61%   |
| TP-Link                           | 1         | 1.61%   |
| Mellanox Technologies             | 1         | 1.61%   |
| MediaTek                          | 1         | 1.61%   |
| Ericsson Business Mobile Networks | 1         | 1.61%   |
| Ceton Technologies                | 1         | 1.61%   |
| ASUSTek Computer                  | 1         | 1.61%   |
| ASIX Electronics                  | 1         | 1.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 16.88%  |
| Intel Ethernet Controller I225-V                                  | 5         | 6.49%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 6.49%   |
| Intel Wireless 7260                                               | 4         | 5.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 3.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.9%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 2.6%    |
| Intel Wireless 8260                                               | 2         | 2.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 2.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.3%    |
| U-Blox [u-blox 8]                                                 | 1         | 1.3%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 1.3%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 1.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.3%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.3%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.3%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 1.3%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.3%    |
| Mellanox MT27800 Family [ConnectX-5]                              | 1         | 1.3%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 1.3%    |
| Intel Wireless-AC 9260                                            | 1         | 1.3%    |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.3%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 1.3%    |
| Intel I210 Gigabit Network Connection                             | 1         | 1.3%    |
| Intel Ethernet Controller XL710 for 40GbE QSFP+                   | 1         | 1.3%    |
| Intel Ethernet Controller X710 for 10GBASE-T                      | 1         | 1.3%    |
| Intel Ethernet Connection I219-V                                  | 1         | 1.3%    |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.3%    |
| Intel Ethernet Connection I218-V                                  | 1         | 1.3%    |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.3%    |
| Intel Ethernet Connection I217-V                                  | 1         | 1.3%    |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.3%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.3%    |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 19        | 55.88%  |
| Qualcomm Atheros      | 8         | 23.53%  |
| Realtek Semiconductor | 3         | 8.82%   |
| TP-Link               | 1         | 2.94%   |
| MediaTek              | 1         | 2.94%   |
| Broadcom              | 1         | 2.94%   |
| ASUSTek Computer      | 1         | 2.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                               | 5         | 14.71%  |
| Intel Wireless 7260                                            | 4         | 11.76%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 8.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 5.88%   |
| Intel Wireless 8260                                            | 2         | 5.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 5.88%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1         | 2.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 2.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 2.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 2.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 2.94%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 2.94%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1         | 2.94%   |
| Intel Wireless-AC 9260                                         | 1         | 2.94%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 2.94%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 2.94%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 2.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 2.94%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 2.94%   |
| ASUS 802.11ac NIC                                              | 1         | 2.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 42.11%  |
| Realtek Semiconductor | 14        | 36.84%  |
| Qualcomm Atheros      | 2         | 5.26%   |
| Broadcom              | 2         | 5.26%   |
| Xiaomi                | 1         | 2.63%   |
| Mellanox Technologies | 1         | 2.63%   |
| Ceton Technologies    | 1         | 2.63%   |
| ASIX Electronics      | 1         | 2.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 31.71%  |
| Intel Ethernet Controller I225-V                                  | 5         | 12.2%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 7.32%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.44%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.44%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 2.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 2.44%   |
| Mellanox MT27800 Family [ConnectX-5]                              | 1         | 2.44%   |
| Intel I210 Gigabit Network Connection                             | 1         | 2.44%   |
| Intel Ethernet Controller XL710 for 40GbE QSFP+                   | 1         | 2.44%   |
| Intel Ethernet Controller X710 for 10GBASE-T                      | 1         | 2.44%   |
| Intel Ethernet Connection I219-V                                  | 1         | 2.44%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.44%   |
| Intel Ethernet Connection I218-V                                  | 1         | 2.44%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.44%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.44%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 2.44%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 2.44%   |
| Ceton InfiniTV Network                                            | 1         | 2.44%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 2.44%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.44%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 33        | 49.25%  |
| WiFi     | 32        | 47.76%  |
| Modem    | 2         | 2.99%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 20        | 54.05%  |
| Ethernet | 17        | 45.95%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 26        | 66.67%  |
| 1     | 11        | 28.21%  |
| 7     | 1         | 2.56%   |
| 3     | 1         | 2.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 29        | 74.36%  |
| Yes  | 10        | 25.64%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 16        | 55.17%  |
| Lite-On Technology              | 3         | 10.34%  |
| Realtek Semiconductor           | 2         | 6.9%    |
| Qualcomm Atheros Communications | 2         | 6.9%    |
| Broadcom                        | 2         | 6.9%    |
| MediaTek                        | 1         | 3.45%   |
| IMC Networks                    | 1         | 3.45%   |
| Cambridge Silicon Radio         | 1         | 3.45%   |
| ASUSTek Computer                | 1         | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 24.14%  |
| Intel Bluetooth Device                              | 4         | 13.79%  |
| Realtek Bluetooth Radio                             | 2         | 6.9%    |
| Lite-On Bluetooth Device                            | 2         | 6.9%    |
| Intel AX201 Bluetooth                               | 2         | 6.9%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 6.9%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 3.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 3.45%   |
| MediaTek Wireless_Device                            | 1         | 3.45%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 3.45%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 3.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 3.45%   |
| Intel AX200 Bluetooth                               | 1         | 3.45%   |
| IMC Networks Bluetooth Device                       | 1         | 3.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Intel           | 30        | 56.6%   |
| AMD             | 12        | 22.64%  |
| Nvidia          | 10        | 18.87%  |
| SteelSeries ApS | 1         | 1.89%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 7.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 6.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 6.35%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 6.35%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 4.76%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 4.76%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 4.76%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 3.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 3.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 3.17%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 3.17%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 3.17%   |
| SteelSeries ApS SteelSeries GameDAC                                        | 1         | 1.59%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.59%   |
| Nvidia GM200 High Definition Audio                                         | 1         | 1.59%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.59%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.59%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.59%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 1.59%   |
| Nvidia Audio device                                                        | 1         | 1.59%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.59%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.59%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1         | 1.59%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.59%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.59%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.59%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.59%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.59%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 1.59%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1         | 1.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.59%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.59%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 1.59%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1         | 1.59%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 1         | 1.59%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1         | 1.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 31.82%  |
| SK hynix            | 3         | 13.64%  |
| Kingston            | 2         | 9.09%   |
| G.Skill             | 2         | 9.09%   |
| Corsair             | 2         | 9.09%   |
| Unknown (ABCD)      | 1         | 4.55%   |
| Team                | 1         | 4.55%   |
| Smart Brazil        | 1         | 4.55%   |
| SHARETRONIC         | 1         | 4.55%   |
| Crucial             | 1         | 4.55%   |
| A-DATA Technology   | 1         | 4.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1         | 4.55%   |
| Team RAM TEAMGROUP-UD3-1600 4GB DIMM DDR3 1600MT/s             | 1         | 4.55%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s   | 1         | 4.55%   |
| SK hynix RAM Module 4GB DIMM DDR3 1600MT/s                     | 1         | 4.55%   |
| SK hynix RAM HMT125S6BFR8C-G7 2048MB SODIMM DDR3 1067MT/s      | 1         | 4.55%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s        | 1         | 4.55%   |
| SHARETRONIC RAM Module 4GB SODIMM DDR3 800MT/s                 | 1         | 4.55%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                    | 1         | 4.55%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s          | 1         | 4.55%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 4.55%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s          | 1         | 4.55%   |
| Samsung RAM M393A4K40EB3-CWE 32GB DIMM DDR4 3200MT/s           | 1         | 4.55%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s            | 1         | 4.55%   |
| Samsung RAM K4UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s   | 1         | 4.55%   |
| Kingston RAM 99U5471-034.A00LF 4GB DIMM DDR3 1600MT/s          | 1         | 4.55%   |
| Kingston RAM 9905417-083.A00G 4GB SODIMM DDR3 1600MT/s         | 1         | 4.55%   |
| G.Skill RAM F4-3600C18-32GTZR 32GB DIMM DDR4 3600MT/s          | 1         | 4.55%   |
| G.Skill RAM F3-1600C9-8GRSL 8GB SODIMM DDR3 1600MT/s           | 1         | 4.55%   |
| Crucial RAM CT16G4DFD824A.C16FBD 16GB DIMM DDR4 2933MT/s       | 1         | 4.55%   |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s        | 1         | 4.55%   |
| Corsair RAM CMK128GX4M8A2666C16 16GB DIMM DDR4 2133MT/s        | 1         | 4.55%   |
| A-DATA RAM Module 32GB SODIMM DDR4 3200MT/s                    | 1         | 4.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 9         | 45%     |
| DDR3   | 9         | 45%     |
| LPDDR4 | 2         | 10%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 10        | 50%     |
| DIMM         | 9         | 45%     |
| Row Of Chips | 1         | 5%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 8         | 38.1%   |
| 4096  | 5         | 23.81%  |
| 16384 | 4         | 19.05%  |
| 32768 | 3         | 14.29%  |
| 2048  | 1         | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 6         | 30%     |
| 3200  | 3         | 15%     |
| 2667  | 2         | 10%     |
| 2133  | 2         | 10%     |
| 4267  | 1         | 5%      |
| 3600  | 1         | 5%      |
| 2933  | 1         | 5%      |
| 2400  | 1         | 5%      |
| 1800  | 1         | 5%      |
| 1067  | 1         | 5%      |
| 800   | 1         | 5%      |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 5         | 22.73%  |
| IMC Networks                           | 3         | 13.64%  |
| Acer                                   | 3         | 13.64%  |
| Sunplus Innovation Technology          | 2         | 9.09%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 9.09%   |
| Syntek                                 | 1         | 4.55%   |
| Realtek Semiconductor                  | 1         | 4.55%   |
| Microdia                               | 1         | 4.55%   |
| Luxvisions Innotech Limited            | 1         | 4.55%   |
| Logitech                               | 1         | 4.55%   |
| Bison Electronics                      | 1         | 4.55%   |
| Apple                                  | 1         | 4.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Sunplus Full HD webcam                              | 2         | 9.09%   |
| Acer Integrated Camera                              | 2         | 9.09%   |
| Syntek Integrated Camera                            | 1         | 4.55%   |
| Realtek Lenovo EasyCamera                           | 1         | 4.55%   |
| Microdia USB Live camera                            | 1         | 4.55%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 4.55%   |
| Logitech Webcam C270                                | 1         | 4.55%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 4.55%   |
| IMC Networks Integrated RGB Camera                  | 1         | 4.55%   |
| IMC Networks Integrated Camera                      | 1         | 4.55%   |
| Chicony Thinkpad T430 camera                        | 1         | 4.55%   |
| Chicony Integrated Camera                           | 1         | 4.55%   |
| Chicony HD WebCam (Asus N-series)                   | 1         | 4.55%   |
| Chicony HD WebCam                                   | 1         | 4.55%   |
| Chicony Acer CrystalEye Webcam                      | 1         | 4.55%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 4.55%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 4.55%   |
| Bison Lenovo Integrated Webcam                      | 1         | 4.55%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 1         | 4.55%   |
| Acer HD Webcam                                      | 1         | 4.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 50%     |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Upek   | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 24        | 57.14%  |
| 1     | 13        | 30.95%  |
| 2     | 4         | 9.52%   |
| 3     | 1         | 2.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 5         | 23.81%  |
| Net/wireless             | 4         | 19.05%  |
| Multimedia controller    | 3         | 14.29%  |
| Unassigned class         | 2         | 9.52%   |
| Fingerprint reader       | 2         | 9.52%   |
| Storage/ata              | 1         | 4.76%   |
| Dvb card                 | 1         | 4.76%   |
| Communication controller | 1         | 4.76%   |
| Chipcard                 | 1         | 4.76%   |
| Bluetooth                | 1         | 4.76%   |

