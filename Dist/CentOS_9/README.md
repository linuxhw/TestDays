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

Total: 57

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| IBM           | 69Y1006 SIT                 | Server      | [b34e147b1c](https://linux-hardware.org/?probe=b34e147b1c) | Jun 25, 2023 |
| Gateway       | H61H2-AD V1.0               | Desktop     | [9a34a9295c](https://linux-hardware.org/?probe=9a34a9295c) | Jun 15, 2023 |
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

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.14.0-86.el9.x86_64           | 3         | 6.67%   |
| 5.14.0-202.el9.x86_64          | 3         | 6.67%   |
| 5.14.0-134.el9.x86_64          | 3         | 6.67%   |
| 5.14.0-325.el9.x86_64          | 2         | 4.44%   |
| 5.14.0-214.el9.x86_64          | 2         | 4.44%   |
| 5.14.0-183.el9.x86_64          | 2         | 4.44%   |
| 5.14.0-171.el9.x86_64          | 2         | 4.44%   |
| 5.14.0-148.el9.x86_64          | 2         | 4.44%   |
| 6.1.8-1.el9.elrepo.x86_64      | 1         | 2.22%   |
| 6.1.1                          | 1         | 2.22%   |
| 5.17.2-lqx3.0.el9.x86_64       | 1         | 2.22%   |
| 5.14.0-78.el9.x86_64           | 1         | 2.22%   |
| 5.14.0-71.el9.x86_64           | 1         | 2.22%   |
| 5.14.0-66.el9.x86_64           | 1         | 2.22%   |
| 5.14.0-52.el9.x86_64           | 1         | 2.22%   |
| 5.14.0-44.el9.x86_64           | 1         | 2.22%   |
| 5.14.0-319.el9.x86_64          | 1         | 2.22%   |
| 5.14.0-316.el9.x86_64          | 1         | 2.22%   |
| 5.14.0-305.el9.x86_64          | 1         | 2.22%   |
| 5.14.0-302.el9.x86_64          | 1         | 2.22%   |
| 5.14.0-299.el9.x86_64          | 1         | 2.22%   |
| 5.14.0-289.el9.x86_64          | 1         | 2.22%   |
| 5.14.0-283.el9.x86_64          | 1         | 2.22%   |
| 5.14.0-282.el9.x86_64          | 1         | 2.22%   |
| 5.14.0-267.el9.x86_64          | 1         | 2.22%   |
| 5.14.0-226.el9.x86_64          | 1         | 2.22%   |
| 5.14.0-200.el9.x86_64          | 1         | 2.22%   |
| 5.14.0-163.el9.x86_64          | 1         | 2.22%   |
| 5.14.0-130.rt21.130.el9.x86_64 | 1         | 2.22%   |
| 5.14.0-130.el9.x86_64          | 1         | 2.22%   |
| 5.14.0-12.el9.x86_64           | 1         | 2.22%   |
| 5.14.0-115.el9.x86_64          | 1         | 2.22%   |
| 5.14.0-109.el9.x86_64          | 1         | 2.22%   |
| 5.14.0-105.el9.x86_64          | 1         | 2.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 39        | 92.86%  |
| 6.1.8   | 1         | 2.38%   |
| 6.1.1   | 1         | 2.38%   |
| 5.17.2  | 1         | 2.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 39        | 92.86%  |
| 6.1     | 2         | 4.76%   |
| 5.17    | 1         | 2.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 41        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 36        | 87.8%   |
| KDE5          | 2         | 4.88%   |
| GNOME Classic | 2         | 4.88%   |
| Unknown       | 1         | 2.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 29        | 69.05%  |
| X11     | 11        | 26.19%  |
| Tty     | 2         | 4.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 24        | 57.14%  |
| GDM     | 16        | 38.1%   |
| SDDM    | 2         | 4.76%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 26        | 63.41%  |
| zh_CN | 2         | 4.88%   |
| ru_RU | 2         | 4.88%   |
| it_IT | 2         | 4.88%   |
| de_DE | 2         | 4.88%   |
| sv_SE | 1         | 2.44%   |
| ru_UA | 1         | 2.44%   |
| pt_BR | 1         | 2.44%   |
| ja_JP | 1         | 2.44%   |
| fr_FR | 1         | 2.44%   |
| en_IN | 1         | 2.44%   |
| en_GB | 1         | 2.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 30        | 73.17%  |
| BIOS | 11        | 26.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 38        | 92.68%  |
| Ext4 | 3         | 7.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 23        | 53.49%  |
| GPT     | 14        | 32.56%  |
| MBR     | 6         | 13.95%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 37        | 88.1%   |
| Yes       | 5         | 11.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 76.74%  |
| Yes       | 10        | 23.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 9         | 21.95%  |
| ASUSTek Computer    | 8         | 19.51%  |
| Acer                | 4         | 9.76%   |
| Intel               | 3         | 7.32%   |
| Hewlett-Packard     | 3         | 7.32%   |
| Timi                | 2         | 4.88%   |
| MSI                 | 2         | 4.88%   |
| Gigabyte Technology | 2         | 4.88%   |
| Zvezda              | 1         | 2.44%   |
| Razer               | 1         | 2.44%   |
| IP3 Tech            | 1         | 2.44%   |
| IBM                 | 1         | 2.44%   |
| Gateway             | 1         | 2.44%   |
| Dell                | 1         | 2.44%   |
| Colorful Technology | 1         | 2.44%   |
| AZW                 | 1         | 2.44%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Zvezda Altair Z                      | 1         | 2.44%   |
| Timi RedmiBook 16                    | 1         | 2.44%   |
| Timi Mi NoteBook Horizon Edition 14  | 1         | 2.44%   |
| Razer Blade 15 (2022) - RZ09-0421    | 1         | 2.44%   |
| MSI MS-7B79                          | 1         | 2.44%   |
| MSI Katana GF76 12UE                 | 1         | 2.44%   |
| Lenovo Yoga S740-14IIL 81RS          | 1         | 2.44%   |
| Lenovo ThinkPad T460s 20FAS5WX00     | 1         | 2.44%   |
| Lenovo ThinkPad T430 2349DG5         | 1         | 2.44%   |
| Lenovo ThinkPad T430 2347DE9         | 1         | 2.44%   |
| Lenovo ThinkPad L14 Gen 1 20U5S0NT00 | 1         | 2.44%   |
| Lenovo Legion 5P 15IMH05H 82AW       | 1         | 2.44%   |
| Lenovo IdeaPad S145-15IWL 81S9       | 1         | 2.44%   |
| Lenovo G580 20150                    | 1         | 2.44%   |
| Lenovo G410 20237                    | 1         | 2.44%   |
| IP3 Tech HeroBox                     | 1         | 2.44%   |
| Intel NUC12WSHi7                     | 1         | 2.44%   |
| Intel NUC12WSHi5                     | 1         | 2.44%   |
| Intel D34010WYK H14771-303           | 1         | 2.44%   |
| IBM System x3250 M3 -[425242G]       | 1         | 2.44%   |
| HP Pavilion Gaming Laptop 15-ec0xxx  | 1         | 2.44%   |
| HP EliteBook 840 G3                  | 1         | 2.44%   |
| HP EliteBook 840 G1                  | 1         | 2.44%   |
| Gigabyte X99-UD4-CF                  | 1         | 2.44%   |
| Gigabyte 970A-DS3P                   | 1         | 2.44%   |
| Gateway SX2865                       | 1         | 2.44%   |
| Dell OptiPlex 790                    | 1         | 2.44%   |
| Colorful CVN Z590 GAMING PRO         | 1         | 2.44%   |
| AZW SER                              | 1         | 2.44%   |
| ASUS TUF Gaming X570-PLUS            | 1         | 2.44%   |
| ASUS ROG STRIX B560-G GAMING WIFI    | 1         | 2.44%   |
| ASUS Q550LF                          | 1         | 2.44%   |
| ASUS PRIME H670-PLUS D4              | 1         | 2.44%   |
| ASUS P8H67-M LE                      | 1         | 2.44%   |
| ASUS P8H61/USB3                      | 1         | 2.44%   |
| ASUS N751JK                          | 1         | 2.44%   |
| ASUS All Series                      | 1         | 2.44%   |
| Acer Swift SF314-512                 | 1         | 2.44%   |
| Acer Predator G3-605                 | 1         | 2.44%   |
| Acer Aspire E1-570G                  | 1         | 2.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 4         | 9.76%   |
| HP EliteBook        | 2         | 4.88%   |
| Acer Aspire         | 2         | 4.88%   |
| Zvezda Altair       | 1         | 2.44%   |
| Timi RedmiBook      | 1         | 2.44%   |
| Timi Mi             | 1         | 2.44%   |
| Razer Blade         | 1         | 2.44%   |
| MSI MS-7B79         | 1         | 2.44%   |
| MSI Katana          | 1         | 2.44%   |
| Lenovo Yoga         | 1         | 2.44%   |
| Lenovo Legion       | 1         | 2.44%   |
| Lenovo IdeaPad      | 1         | 2.44%   |
| Lenovo G580         | 1         | 2.44%   |
| Lenovo G410         | 1         | 2.44%   |
| IP3 Tech HeroBox    | 1         | 2.44%   |
| Intel NUC12WSHi7    | 1         | 2.44%   |
| Intel NUC12WSHi5    | 1         | 2.44%   |
| Intel D34010WYK     | 1         | 2.44%   |
| IBM System          | 1         | 2.44%   |
| HP Pavilion         | 1         | 2.44%   |
| Gigabyte X99-UD4-CF | 1         | 2.44%   |
| Gigabyte 970A-DS3P  | 1         | 2.44%   |
| Gateway SX2865      | 1         | 2.44%   |
| Dell OptiPlex       | 1         | 2.44%   |
| Colorful CVN        | 1         | 2.44%   |
| AZW SER             | 1         | 2.44%   |
| ASUS TUF            | 1         | 2.44%   |
| ASUS ROG            | 1         | 2.44%   |
| ASUS Q550LF         | 1         | 2.44%   |
| ASUS PRIME          | 1         | 2.44%   |
| ASUS P8H67-M        | 1         | 2.44%   |
| ASUS P8H61          | 1         | 2.44%   |
| ASUS N751JK         | 1         | 2.44%   |
| ASUS All            | 1         | 2.44%   |
| Acer Swift          | 1         | 2.44%   |
| Acer Predator       | 1         | 2.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 9         | 21.95%  |
| 2022 | 5         | 12.2%   |
| 2021 | 5         | 12.2%   |
| 2012 | 5         | 12.2%   |
| 2020 | 4         | 9.76%   |
| 2019 | 4         | 9.76%   |
| 2016 | 2         | 4.88%   |
| 2014 | 2         | 4.88%   |
| 2011 | 2         | 4.88%   |
| 2018 | 1         | 2.44%   |
| 2010 | 1         | 2.44%   |
| 2009 | 1         | 2.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 21        | 51.22%  |
| Desktop  | 14        | 34.15%  |
| Mini pc  | 4         | 9.76%   |
| Server   | 2         | 4.88%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 38        | 92.68%  |
| Enabled  | 3         | 7.32%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 41        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 16        | 39.02%  |
| 8.01-16.0       | 10        | 24.39%  |
| 32.01-64.0      | 6         | 14.63%  |
| 64.01-256.0     | 3         | 7.32%   |
| 3.01-4.0        | 2         | 4.88%   |
| 16.01-24.0      | 2         | 4.88%   |
| More than 256.0 | 1         | 2.44%   |
| 24.01-32.0      | 1         | 2.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 18        | 40.91%  |
| 4.01-8.0  | 9         | 20.45%  |
| 3.01-4.0  | 9         | 20.45%  |
| 1.01-2.0  | 3         | 6.82%   |
| 8.01-16.0 | 3         | 6.82%   |
| 0.51-1.0  | 2         | 4.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 21        | 51.22%  |
| 2      | 10        | 24.39%  |
| 3      | 5         | 12.2%   |
| 4      | 4         | 9.76%   |
| 10     | 1         | 2.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 32        | 78.05%  |
| Yes       | 9         | 21.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 87.8%   |
| No        | 5         | 12.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 80.49%  |
| No        | 8         | 19.51%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 70.73%  |
| No        | 12        | 29.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 8         | 19.51%  |
| Germany      | 3         | 7.32%   |
| China        | 3         | 7.32%   |
| Bulgaria     | 3         | 7.32%   |
| Ukraine      | 2         | 4.88%   |
| Italy        | 2         | 4.88%   |
| Canada       | 2         | 4.88%   |
| Uzbekistan   | 1         | 2.44%   |
| Switzerland  | 1         | 2.44%   |
| Sweden       | 1         | 2.44%   |
| South Africa | 1         | 2.44%   |
| Russia       | 1         | 2.44%   |
| Puerto Rico  | 1         | 2.44%   |
| Poland       | 1         | 2.44%   |
| Netherlands  | 1         | 2.44%   |
| Myanmar      | 1         | 2.44%   |
| Kazakhstan   | 1         | 2.44%   |
| Japan        | 1         | 2.44%   |
| India        | 1         | 2.44%   |
| France       | 1         | 2.44%   |
| Finland      | 1         | 2.44%   |
| Colombia     | 1         | 2.44%   |
| Chile        | 1         | 2.44%   |
| Brazil       | 1         | 2.44%   |
| Belarus      | 1         | 2.44%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sofia          | 2         | 4.65%   |
| Bristow        | 2         | 4.65%   |
| Beijing        | 2         | 4.65%   |
| Yangon         | 1         | 2.33%   |
| Wuhan          | 1         | 2.33%   |
| Vitebsk        | 1         | 2.33%   |
| Tomah          | 1         | 2.33%   |
| Tashkent       | 1         | 2.33%   |
| Stromberg      | 1         | 2.33%   |
| Stockholm      | 1         | 2.33%   |
| Soest          | 1         | 2.33%   |
| Schemmerhofen  | 1         | 2.33%   |
| San Juan       | 1         | 2.33%   |
| Ruda Śląska  | 1         | 2.33%   |
| Rome           | 1         | 2.33%   |
| Ribeirao Preto | 1         | 2.33%   |
| Quitman        | 1         | 2.33%   |
| Puente Alto    | 1         | 2.33%   |
| Portland       | 1         | 2.33%   |
| Persan         | 1         | 2.33%   |
| Okazaki        | 1         | 2.33%   |
| New York       | 1         | 2.33%   |
| New Cumberland | 1         | 2.33%   |
| Mumbai         | 1         | 2.33%   |
| Moscow         | 1         | 2.33%   |
| Meieki         | 1         | 2.33%   |
| L'Isle-Adam    | 1         | 2.33%   |
| Kyiv           | 1         | 2.33%   |
| Kramatorsk     | 1         | 2.33%   |
| Helsinki       | 1         | 2.33%   |
| Durban         | 1         | 2.33%   |
| Dortmund       | 1         | 2.33%   |
| Burgas         | 1         | 2.33%   |
| Bogotá        | 1         | 2.33%   |
| Birmensdorf    | 1         | 2.33%   |
| Battle Creek   | 1         | 2.33%   |
| Barrie         | 1         | 2.33%   |
| Almaty         | 1         | 2.33%   |
| Airdrie        | 1         | 2.33%   |
| Adelfia        | 1         | 2.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 11        | 15     | 16.92%  |
| WDC                       | 10        | 12     | 15.38%  |
| Kingston                  | 8         | 9      | 12.31%  |
| Seagate                   | 6         | 8      | 9.23%   |
| Toshiba                   | 3         | 4      | 4.62%   |
| Intel                     | 3         | 3      | 4.62%   |
| HGST                      | 3         | 4      | 4.62%   |
| SK hynix                  | 2         | 2      | 3.08%   |
| Sandisk                   | 2         | 7      | 3.08%   |
| Micron Technology         | 2         | 2      | 3.08%   |
| WD MediaMax               | 1         | 1      | 1.54%   |
| Unknown                   | 1         | 1      | 1.54%   |
| Team                      | 1         | 2      | 1.54%   |
| Plextor                   | 1         | 1      | 1.54%   |
| Phison                    | 1         | 1      | 1.54%   |
| OCZ                       | 1         | 1      | 1.54%   |
| Netac                     | 1         | 2      | 1.54%   |
| Micron/Crucial Technology | 1         | 1      | 1.54%   |
| LITEON                    | 1         | 1      | 1.54%   |
| Hjwdz                     | 1         | 1      | 1.54%   |
| Hitachi                   | 1         | 1      | 1.54%   |
| Hewlett-Packard           | 1         | 1      | 1.54%   |
| Gigabyte Technology       | 1         | 2      | 1.54%   |
| Crucial                   | 1         | 6      | 1.54%   |
| A-DATA Technology         | 1         | 1      | 1.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 2         | 2.86%   |
| Samsung MZNLH512HALU-00000 512GB SSD                | 2         | 2.86%   |
| Micron 2450_MTFDKBA512TFK 512GB                     | 2         | 2.86%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                    | 1         | 1.43%   |
| WDC WD6400BEVT-22A0RT0 640GB                        | 1         | 1.43%   |
| WDC WD5000LPLX-60ZNTT1 500GB                        | 1         | 1.43%   |
| WDC WD5000BEVT-55A0RT0 500GB                        | 1         | 1.43%   |
| WDC WD3200AAKX-753CA1 320GB                         | 1         | 1.43%   |
| WDC WD2500AAJS-60M0A0 250GB                         | 1         | 1.43%   |
| WDC WD22EJRX-89BEMY0 2TB                            | 1         | 1.43%   |
| WDC WD2003FZEX-00Z4SA0 2TB                          | 1         | 1.43%   |
| WDC WD10EZEX-60M2NA0 1TB                            | 1         | 1.43%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 1         | 1.43%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 1         | 1.43%   |
| WD MediaMax WL750GSA6472 752GB                      | 1         | 1.43%   |
| Unknown MMC Card  7GB                               | 1         | 1.43%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 1.43%   |
| Toshiba MK2561GSYN 250GB                            | 1         | 1.43%   |
| Toshiba DT01ACA100 1TB                              | 1         | 1.43%   |
| Team T253X1480G 480GB SSD                           | 1         | 1.43%   |
| SK hynix NVMe SSD Drive 256GB                       | 1         | 1.43%   |
| SK hynix BC501 NVMe 256GB                           | 1         | 1.43%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1.43%   |
| Seagate ST3500413AS 500GB                           | 1         | 1.43%   |
| Seagate ST3250820AS 250GB                           | 1         | 1.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1.43%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1.43%   |
| Seagate FireCuda 520 SSD ZP2000GM30002 2TB          | 1         | 1.43%   |
| Seagate FireCuda 520 SSD ZP1000GM30002 1TB          | 1         | 1.43%   |
| Sandisk WD_BLACK SN770 1TB                          | 1         | 1.43%   |
| SanDisk SDSSDH3 1T00 1TB                            | 1         | 1.43%   |
| SanDisk SD6SB1M-128G-1006 128GB SSD                 | 1         | 1.43%   |
| Samsung SSD 870 QVO 2TB                             | 1         | 1.43%   |
| Samsung SSD 870 EVO 250GB                           | 1         | 1.43%   |
| Samsung PSSD T7 1TB                                 | 1         | 1.43%   |
| Samsung NVMe SSD Drive 1TB                          | 1         | 1.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 1         | 1.43%   |
| Samsung MZALQ512HALU-000L2 512GB                    | 1         | 1.43%   |
| Samsung MZ7LN256HAJQ-00000 256GB SSD                | 1         | 1.43%   |
| Samsung MZ7LH240HAHQ-00005 240GB SSD                | 1         | 1.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor      | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| WDC         | 9         | 11     | 40.91%  |
| Seagate     | 5         | 6      | 22.73%  |
| Toshiba     | 3         | 4      | 13.64%  |
| HGST        | 3         | 4      | 13.64%  |
| WD MediaMax | 1         | 1      | 4.55%   |
| Hitachi     | 1         | 1      | 4.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 10     | 26.92%  |
| Kingston            | 6         | 7      | 23.08%  |
| SanDisk             | 2         | 4      | 7.69%   |
| WDC                 | 1         | 1      | 3.85%   |
| Team                | 1         | 2      | 3.85%   |
| Plextor             | 1         | 1      | 3.85%   |
| OCZ                 | 1         | 1      | 3.85%   |
| Netac               | 1         | 2      | 3.85%   |
| LITEON              | 1         | 1      | 3.85%   |
| Intel               | 1         | 1      | 3.85%   |
| Hewlett-Packard     | 1         | 1      | 3.85%   |
| Gigabyte Technology | 1         | 2      | 3.85%   |
| Crucial             | 1         | 6      | 3.85%   |
| A-DATA Technology   | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 22        | 40     | 39.29%  |
| HDD     | 17        | 27     | 30.36%  |
| NVMe    | 15        | 20     | 26.79%  |
| MMC     | 1         | 1      | 1.79%   |
| Unknown | 1         | 1      | 1.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 31        | 65     | 63.27%  |
| NVMe | 15        | 20     | 30.61%  |
| SAS  | 2         | 3      | 4.08%   |
| MMC  | 1         | 1      | 2.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 23        | 33     | 56.1%   |
| 0.51-1.0   | 14        | 29     | 34.15%  |
| 1.01-2.0   | 4         | 5      | 9.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 16        | 37.21%  |
| 251-500        | 9         | 20.93%  |
| 1001-2000      | 7         | 16.28%  |
| 501-1000       | 6         | 13.95%  |
| 2001-3000      | 2         | 4.65%   |
| More than 3000 | 1         | 2.33%   |
| 21-50          | 1         | 2.33%   |
| 51-100         | 1         | 2.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 20        | 47.62%  |
| 251-500        | 5         | 11.9%   |
| 101-250        | 5         | 11.9%   |
| 51-100         | 5         | 11.9%   |
| 21-50          | 3         | 7.14%   |
| 501-1000       | 2         | 4.76%   |
| More than 3000 | 1         | 2.38%   |
| 1001-2000      | 1         | 2.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 40%     |
| Seagate | 2         | 2      | 40%     |
| Toshiba | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 40%     |
| Seagate | 2         | 2      | 40%     |
| Toshiba | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 27        | 53     | 57.45%  |
| Works    | 16        | 31     | 34.04%  |
| Malfunc  | 4         | 5      | 8.51%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 33        | 60%     |
| AMD                         | 5         | 9.09%   |
| Samsung Electronics         | 4         | 7.27%   |
| SK hynix                    | 2         | 3.64%   |
| Micron Technology           | 2         | 3.64%   |
| LSI Logic / Symbios Logic   | 2         | 3.64%   |
| Kingston Technology Company | 2         | 3.64%   |
| Silicon Image               | 1         | 1.82%   |
| Seagate Technology          | 1         | 1.82%   |
| SanDisk                     | 1         | 1.82%   |
| Phison Electronics          | 1         | 1.82%   |
| Micron/Crucial Technology   | 1         | 1.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 6.78%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 6.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 6.78%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 4         | 6.78%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 3         | 5.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 5.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 3.39%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 3.39%   |
| Micron 2450 NVMe SSD (DRAM-less)                                               | 2         | 3.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 3.39%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 3.39%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 1.69%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 1.69%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1         | 1.69%   |
| Seagate FireCuda 520 SSD                                                       | 1         | 1.69%   |
| SanDisk WD Black SN770 NVMe SSD                                                | 1         | 1.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.69%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.69%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 1.69%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                 | 1         | 1.69%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                        | 1         | 1.69%   |
| Kingston Company NVMe Controller                                               | 1         | 1.69%   |
| Kingston Company FURY Renegade NVMe SSD                                        | 1         | 1.69%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.69%   |
| Intel SSD 660P Series                                                          | 1         | 1.69%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 1.69%   |
| Intel Non-Volatile memory controller                                           | 1         | 1.69%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.69%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.69%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.69%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 1         | 1.69%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1         | 1.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1         | 1.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.69%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1         | 1.69%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.69%   |
| AMD 400 Series Chipset SATA Controller                                         | 1         | 1.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 34        | 61.82%  |
| NVMe | 15        | 27.27%  |
| RAID | 4         | 7.27%   |
| SCSI | 1         | 1.82%   |
| IDE  | 1         | 1.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 34        | 82.93%  |
| AMD    | 7         | 17.07%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-1260P                  | 2         | 4.88%   |
| Intel Xeon Gold 6326 CPU @ 2.90GHz            | 1         | 2.44%   |
| Intel Xeon CPU X3440 @ 2.53GHz                | 1         | 2.44%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 2.44%   |
| Intel Core i7-5930K CPU @ 3.50GHz             | 1         | 2.44%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 2.44%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 2.44%   |
| Intel Core i7-2600K CPU @ 3.40GHz             | 1         | 2.44%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 2.44%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 2.44%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 2.44%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 2.44%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 1         | 2.44%   |
| Intel Core i5-4440 CPU @ 3.10GHz              | 1         | 2.44%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 2.44%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 2.44%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1         | 2.44%   |
| Intel Core i5-3380M CPU @ 2.90GHz             | 1         | 2.44%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 2.44%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 2.44%   |
| Intel Core i5-2400S CPU @ 2.50GHz             | 1         | 2.44%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 1         | 2.44%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2.44%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 1         | 2.44%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 2.44%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 2.44%   |
| Intel Core i3-2130 CPU @ 3.40GHz              | 1         | 2.44%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 2.44%   |
| Intel 12th Gen Core i7-12800H                 | 1         | 2.44%   |
| Intel 12th Gen Core i7-12700H                 | 1         | 2.44%   |
| Intel 12th Gen Core i5-12600K                 | 1         | 2.44%   |
| Intel 12th Gen Core i5-1240P                  | 1         | 2.44%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz        | 1         | 2.44%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 1         | 2.44%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 2.44%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 2.44%   |
| AMD Ryzen 5 3600 6-Core Processor             | 1         | 2.44%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 2.44%   |
| AMD Ryzen 3 PRO 4450U with Radeon Graphics    | 1         | 2.44%   |
| AMD FX-8120 Eight-Core Processor              | 1         | 2.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model           | Computers | Percent |
|-----------------|-----------|---------|
| Intel Core i5   | 14        | 34.15%  |
| Other           | 7         | 17.07%  |
| Intel Core i7   | 7         | 17.07%  |
| Intel Core i3   | 3         | 7.32%   |
| AMD Ryzen 5     | 3         | 7.32%   |
| Intel Xeon Gold | 1         | 2.44%   |
| Intel Xeon      | 1         | 2.44%   |
| Intel Celeron   | 1         | 2.44%   |
| AMD Ryzen 9     | 1         | 2.44%   |
| AMD Ryzen 7     | 1         | 2.44%   |
| AMD Ryzen 3 PRO | 1         | 2.44%   |
| AMD FX          | 1         | 2.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 14        | 34.15%  |
| 2      | 12        | 29.27%  |
| 6      | 6         | 14.63%  |
| 12     | 3         | 7.32%   |
| 14     | 2         | 4.88%   |
| 32     | 1         | 2.44%   |
| 16     | 1         | 2.44%   |
| 10     | 1         | 2.44%   |
| 8      | 1         | 2.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 40        | 97.56%  |
| 2      | 1         | 2.44%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 32        | 78.05%  |
| 1      | 9         | 21.95%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 41        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 6         | 14.63%  |
| 0x906a3    | 5         | 12.2%   |
| 0x306c3    | 4         | 9.76%   |
| 0x306a9    | 4         | 9.76%   |
| 0x40651    | 3         | 7.32%   |
| 0x806ec    | 2         | 4.88%   |
| 0x406e3    | 2         | 4.88%   |
| 0x08600106 | 2         | 4.88%   |
| 0xa0671    | 1         | 2.44%   |
| 0xa0653    | 1         | 2.44%   |
| 0xa0652    | 1         | 2.44%   |
| 0x90672    | 1         | 2.44%   |
| 0x706e5    | 1         | 2.44%   |
| 0x706a8    | 1         | 2.44%   |
| 0x606a6    | 1         | 2.44%   |
| 0x306f2    | 1         | 2.44%   |
| 0x206a7    | 1         | 2.44%   |
| 0x20652    | 1         | 2.44%   |
| 0x0a201016 | 1         | 2.44%   |
| 0x08701013 | 1         | 2.44%   |
| 0x0600063d | 1         | 2.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 8         | 19.51%  |
| Alderlake Hybrid | 6         | 14.63%  |
| IvyBridge        | 5         | 12.2%   |
| Zen 2            | 4         | 9.76%   |
| SandyBridge      | 3         | 7.32%   |
| IceLake          | 3         | 7.32%   |
| Skylake          | 2         | 4.88%   |
| KabyLake         | 2         | 4.88%   |
| CometLake        | 2         | 4.88%   |
| Zen+             | 1         | 2.44%   |
| Zen 3            | 1         | 2.44%   |
| Westmere         | 1         | 2.44%   |
| Nehalem          | 1         | 2.44%   |
| Goldmont plus    | 1         | 2.44%   |
| Bulldozer        | 1         | 2.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 23        | 44.23%  |
| Nvidia                     | 16        | 30.77%  |
| AMD                        | 11        | 21.15%  |
| Matrox Electronics Systems | 1         | 1.92%   |
| ASPEED Technology          | 1         | 1.92%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P Integrated Graphics Controller                         | 5         | 9.26%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 7.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 5.56%   |
| AMD Renoir                                                                | 3         | 5.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 3.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 2         | 3.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 3.7%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 1.85%   |
| Nvidia TU117 [GeForce GTX 1650]                                           | 1         | 1.85%   |
| Nvidia TU116 [GeForce GTX 1660]                                           | 1         | 1.85%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 1         | 1.85%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 1.85%   |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 1.85%   |
| Nvidia GP107M [GeForce MX350]                                             | 1         | 1.85%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                         | 1         | 1.85%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 1.85%   |
| Nvidia GM107M [GeForce GTX 850M]                                          | 1         | 1.85%   |
| Nvidia GM107 [GeForce GTX 745]                                            | 1         | 1.85%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 1         | 1.85%   |
| Nvidia GK208B [GeForce GT 730]                                            | 1         | 1.85%   |
| Nvidia GK107M [GeForce GT 745M]                                           | 1         | 1.85%   |
| Nvidia GF108M [NVS 5400M]                                                 | 1         | 1.85%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 1.85%   |
| Nvidia GA103M [GeForce RTX 3080 Ti Mobile]                                | 1         | 1.85%   |
| Matrox Electronics Systems MGA G200EV                                     | 1         | 1.85%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 1.85%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                 | 1         | 1.85%   |
| Intel Iris Plus Graphics G7                                               | 1         | 1.85%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 1.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 1.85%   |
| ASPEED Technology ASPEED Graphics Family                                  | 1         | 1.85%   |
| AMD RV370 [Radeon X300/X550/X1050 Series] (Secondary)                     | 1         | 1.85%   |
| AMD RV370 [Radeon X300/X550/X1050 Series]                                 | 1         | 1.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 1.85%   |
| AMD Park [Mobility Radeon HD 5430]                                        | 1         | 1.85%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                              | 1         | 1.85%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]             | 1         | 1.85%   |
| AMD Mars [Radeon HD 8730M]                                                | 1         | 1.85%   |
| AMD Juniper XT [Radeon HD 6770]                                           | 1         | 1.85%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                            | 1         | 1.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 13        | 31.71%  |
| Intel + Nvidia | 9         | 21.95%  |
| 1 x AMD        | 8         | 19.51%  |
| 1 x Nvidia     | 6         | 14.63%  |
| 2 x AMD        | 1         | 2.44%   |
| 1 x Matrox     | 1         | 2.44%   |
| Intel + AMD    | 1         | 2.44%   |
| 1 x ASPEED     | 1         | 2.44%   |
| AMD + Nvidia   | 1         | 2.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 34        | 80.95%  |
| Proprietary | 6         | 14.29%  |
| Unknown     | 2         | 4.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 47.73%  |
| 1.01-2.0   | 5         | 11.36%  |
| 5.01-6.0   | 4         | 9.09%   |
| 3.01-4.0   | 4         | 9.09%   |
| 0.51-1.0   | 4         | 9.09%   |
| 0.01-0.5   | 4         | 9.09%   |
| 8.01-16.0  | 2         | 4.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 15.56%  |
| LG Display          | 6         | 13.33%  |
| Chimei Innolux      | 5         | 11.11%  |
| AU Optronics        | 4         | 8.89%   |
| ViewSonic           | 3         | 6.67%   |
| Goldstar            | 3         | 6.67%   |
| Hewlett-Packard     | 2         | 4.44%   |
| Dell                | 2         | 4.44%   |
| Acer                | 2         | 4.44%   |
| TMX                 | 1         | 2.22%   |
| SKY                 | 1         | 2.22%   |
| PANDA               | 1         | 2.22%   |
| LG Electronics      | 1         | 2.22%   |
| KVM                 | 1         | 2.22%   |
| Iiyama              | 1         | 2.22%   |
| Gigabyte Technology | 1         | 2.22%   |
| CHD                 | 1         | 2.22%   |
| BOE                 | 1         | 2.22%   |
| BenQ                | 1         | 2.22%   |
| AOC                 | 1         | 2.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch           | 1         | 2.22%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch           | 1         | 2.22%   |
| ViewSonic PJ402D-2 HCD7B1D 1280x960                                     | 1         | 2.22%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch                 | 1         | 2.22%   |
| SKY 22X1-M225F SKY2150 1920x1080 476x268mm 21.5-inch                    | 1         | 2.22%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 607x345mm 27.5-inch       | 1         | 2.22%   |
| Samsung Electronics SyncMaster SAM05EB 1920x1080 597x336mm 27.0-inch    | 1         | 2.22%   |
| Samsung Electronics SMT23A350 SAM07A7 1920x1080 510x287mm 23.0-inch     | 1         | 2.22%   |
| Samsung Electronics SMEX2220 SAM0686 1920x1080 477x268mm 21.5-inch      | 1         | 2.22%   |
| Samsung Electronics S27C450 SAM09D9 1920x1080 598x336mm 27.0-inch       | 1         | 2.22%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch   | 1         | 2.22%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1         | 2.22%   |
| PANDA LCD Monitor NCP0052 1920x1080 309x174mm 14.0-inch                 | 1         | 2.22%   |
| LG Electronics LCD Monitor LG FULL HD                                   | 1         | 2.22%   |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch            | 1         | 2.22%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch            | 1         | 2.22%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch            | 1         | 2.22%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch             | 1         | 2.22%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch             | 1         | 2.22%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch             | 1         | 2.22%   |
| KVM LCD Monitor17 KVM4308 1280x1024 338x270mm 17.0-inch                 | 1         | 2.22%   |
| Iiyama PL2888H IVM7106 1920x1080 621x341mm 27.9-inch                    | 1         | 2.22%   |
| Hewlett-Packard L185x HWP298C 1366x768 410x230mm 18.5-inch              | 1         | 2.22%   |
| Hewlett-Packard 2159 HWP282C 1920x1080 479x269mm 21.6-inch              | 1         | 2.22%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                    | 1         | 2.22%   |
| Goldstar 27GL650F GSM5B70 1920x1080 531x298mm 24.0-inch                 | 1         | 2.22%   |
| Goldstar 22EA53 GSM59A6 1920x1080 477x268mm 21.5-inch                   | 1         | 2.22%   |
| Gigabyte Technology G34WQC A GBT3403 3440x1440 797x334mm 34.0-inch      | 1         | 2.22%   |
| Dell SE2219H DELF10E 1920x1080 476x268mm 21.5-inch                      | 1         | 2.22%   |
| Dell 2408WFP DELA029 1920x1200 519x324mm 24.1-inch                      | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN1608 1920x1080 355x199mm 16.0-inch        | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch         | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch        | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch         | 1         | 2.22%   |
| CHD 24VCF CHD0240 1920x1080 368x207mm 16.6-inch                         | 1         | 2.22%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                    | 1         | 2.22%   |
| BenQ ZOWIE XL LCD BNQ7F83 1920x1080 544x303mm 24.5-inch                 | 1         | 2.22%   |
| AU Optronics LCD Monitor AUO5A3D 1920x1080 309x174mm 14.0-inch          | 1         | 2.22%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch          | 1         | 2.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 23        | 56.1%   |
| 1366x768 (WXGA)   | 6         | 14.63%  |
| 3840x2160 (4K)    | 2         | 4.88%   |
| 1600x900 (HD+)    | 2         | 4.88%   |
| 3840x1080         | 1         | 2.44%   |
| 3440x1440         | 1         | 2.44%   |
| 3200x2000         | 1         | 2.44%   |
| 2560x1440 (QHD)   | 1         | 2.44%   |
| 1920x1200 (WUXGA) | 1         | 2.44%   |
| 1280x960          | 1         | 2.44%   |
| 1280x1024 (SXGA)  | 1         | 2.44%   |
| Unknown           | 1         | 2.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 14      | 9         | 20.45%  |
| 21      | 7         | 15.91%  |
| 15      | 7         | 15.91%  |
| 27      | 5         | 11.36%  |
| 24      | 4         | 9.09%   |
| 23      | 3         | 6.82%   |
| Unknown | 2         | 4.55%   |
| 84      | 1         | 2.27%   |
| 34      | 1         | 2.27%   |
| 19      | 1         | 2.27%   |
| 18      | 1         | 2.27%   |
| 17      | 1         | 2.27%   |
| 16      | 1         | 2.27%   |
| 13      | 1         | 2.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 40.48%  |
| 501-600     | 8         | 19.05%  |
| 401-500     | 8         | 19.05%  |
| 351-400     | 3         | 7.14%   |
| 601-700     | 2         | 4.76%   |
| Unknown     | 2         | 4.76%   |
| 701-800     | 1         | 2.38%   |
| 1501-2000   | 1         | 2.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 31        | 83.78%  |
| 16/10   | 2         | 5.41%   |
| 5/4     | 1         | 2.7%    |
| 4/3     | 1         | 2.7%    |
| 21/9    | 1         | 2.7%    |
| Unknown | 1         | 2.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 10        | 23.81%  |
| 201-250        | 8         | 19.05%  |
| 101-110        | 7         | 16.67%  |
| 301-350        | 5         | 11.9%   |
| 151-200        | 3         | 7.14%   |
| 251-300        | 2         | 4.76%   |
| Unknown        | 2         | 4.76%   |
| More than 1000 | 1         | 2.38%   |
| 351-500        | 1         | 2.38%   |
| 141-150        | 1         | 2.38%   |
| 121-130        | 1         | 2.38%   |
| 111-120        | 1         | 2.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 13        | 31.71%  |
| 101-120       | 13        | 31.71%  |
| 51-100        | 11        | 26.83%  |
| Unknown       | 2         | 4.88%   |
| More than 240 | 1         | 2.44%   |
| 161-240       | 1         | 2.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 30        | 71.43%  |
| 2     | 7         | 16.67%  |
| 0     | 4         | 9.52%   |
| 3     | 1         | 2.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 28        | 42.42%  |
| Realtek Semiconductor             | 16        | 24.24%  |
| Qualcomm Atheros                  | 9         | 13.64%  |
| Broadcom                          | 3         | 4.55%   |
| Xiaomi                            | 1         | 1.52%   |
| U-Blox                            | 1         | 1.52%   |
| TP-Link                           | 1         | 1.52%   |
| Mellanox Technologies             | 1         | 1.52%   |
| MediaTek                          | 1         | 1.52%   |
| IBM                               | 1         | 1.52%   |
| Ericsson Business Mobile Networks | 1         | 1.52%   |
| Ceton Technologies                | 1         | 1.52%   |
| ASUSTek Computer                  | 1         | 1.52%   |
| ASIX Electronics                  | 1         | 1.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 16.05%  |
| Intel Ethernet Controller I225-V                                  | 5         | 6.17%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 6.17%   |
| Intel Wireless 7260                                               | 4         | 4.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 2.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 2.47%   |
| Intel Wireless 8260                                               | 2         | 2.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 2.47%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 2.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.23%   |
| U-Blox [u-blox 8]                                                 | 1         | 1.23%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 1.23%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 1.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.23%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.23%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.23%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 1.23%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.23%   |
| Mellanox MT27800 Family [ConnectX-5]                              | 1         | 1.23%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 1.23%   |
| Intel Wireless-AC 9260                                            | 1         | 1.23%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.23%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 1.23%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.23%   |
| Intel Ethernet Controller XL710 for 40GbE QSFP+                   | 1         | 1.23%   |
| Intel Ethernet Controller X710 for 10GBASE-T                      | 1         | 1.23%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.23%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.23%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.23%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.23%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.23%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.23%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.23%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.23%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 19        | 54.29%  |
| Qualcomm Atheros      | 8         | 22.86%  |
| Realtek Semiconductor | 4         | 11.43%  |
| TP-Link               | 1         | 2.86%   |
| MediaTek              | 1         | 2.86%   |
| Broadcom              | 1         | 2.86%   |
| ASUSTek Computer      | 1         | 2.86%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                               | 5         | 14.29%  |
| Intel Wireless 7260                                            | 4         | 11.43%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 8.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 5.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 5.71%   |
| Intel Wireless 8260                                            | 2         | 5.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 5.71%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1         | 2.86%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 2.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 2.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 2.86%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 2.86%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1         | 2.86%   |
| Intel Wireless-AC 9260                                         | 1         | 2.86%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 2.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 2.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 2.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 2.86%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 2.86%   |
| ASUS 802.11ac NIC                                              | 1         | 2.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 18        | 43.9%   |
| Realtek Semiconductor | 14        | 34.15%  |
| Qualcomm Atheros      | 2         | 4.88%   |
| Broadcom              | 2         | 4.88%   |
| Xiaomi                | 1         | 2.44%   |
| Mellanox Technologies | 1         | 2.44%   |
| IBM                   | 1         | 2.44%   |
| Ceton Technologies    | 1         | 2.44%   |
| ASIX Electronics      | 1         | 2.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 29.55%  |
| Intel Ethernet Controller I225-V                                  | 5         | 11.36%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 6.82%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 4.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.27%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.27%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 2.27%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 2.27%   |
| Mellanox MT27800 Family [ConnectX-5]                              | 1         | 2.27%   |
| Intel I210 Gigabit Network Connection                             | 1         | 2.27%   |
| Intel Ethernet Controller XL710 for 40GbE QSFP+                   | 1         | 2.27%   |
| Intel Ethernet Controller X710 for 10GBASE-T                      | 1         | 2.27%   |
| Intel Ethernet Connection I219-V                                  | 1         | 2.27%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.27%   |
| Intel Ethernet Connection I218-V                                  | 1         | 2.27%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.27%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.27%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 2.27%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 2.27%   |
| IBM RNDIS/CDC ETHER                                               | 1         | 2.27%   |
| Ceton InfiniTV Network                                            | 1         | 2.27%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 2.27%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.27%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 35        | 50%     |
| WiFi     | 33        | 47.14%  |
| Modem    | 2         | 2.86%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 20        | 51.28%  |
| Ethernet | 19        | 48.72%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 27        | 65.85%  |
| 1     | 12        | 29.27%  |
| 7     | 1         | 2.44%   |
| 3     | 1         | 2.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 31        | 75.61%  |
| Yes  | 10        | 24.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


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

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


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

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Intel           | 31        | 57.41%  |
| AMD             | 12        | 22.22%  |
| Nvidia          | 10        | 18.52%  |
| SteelSeries ApS | 1         | 1.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 7.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 6.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 6.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 6.25%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 6.25%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 4.69%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 4.69%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 4.69%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 3.13%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 3.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 3.13%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 3.13%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 3.13%   |
| SteelSeries ApS SteelSeries GameDAC                                        | 1         | 1.56%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.56%   |
| Nvidia GM200 High Definition Audio                                         | 1         | 1.56%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.56%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.56%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 1.56%   |
| Nvidia Audio device                                                        | 1         | 1.56%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.56%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.56%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1         | 1.56%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.56%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.56%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.56%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.56%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 1.56%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1         | 1.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.56%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.56%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 1.56%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1         | 1.56%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 1         | 1.56%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1         | 1.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


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

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1         | 4.55%   |
| Team RAM TEAMGROUP-UD3-1600 4GB DIMM DDR3 1600MT/s             | 1         | 4.55%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s   | 1         | 4.55%   |
| SK hynix RAM Module 4GB DIMM DDR3 1600MT/s                     | 1         | 4.55%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s         | 1         | 4.55%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s        | 1         | 4.55%   |
| SHARETRONIC RAM Module 4GB SODIMM DDR3 800MT/s                 | 1         | 4.55%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                    | 1         | 4.55%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s          | 1         | 4.55%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 4.55%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s          | 1         | 4.55%   |
| Samsung RAM M393A4K40EB3-CWE 32GB DIMM DDR4 3200MT/s           | 1         | 4.55%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s            | 1         | 4.55%   |
| Samsung RAM K4UBE3D4AA-MGCR 8GB Row Of Chips LPDDR4 4267MT/s   | 1         | 4.55%   |
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

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 9         | 45%     |
| DDR3   | 9         | 45%     |
| LPDDR4 | 2         | 10%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 10        | 50%     |
| DIMM         | 9         | 45%     |
| Row Of Chips | 1         | 5%      |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


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

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


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

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Sunplus Full HD webcam                              | 2         | 9.09%   |
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
| Bison Integrated Camera                             | 1         | 4.55%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 1         | 4.55%   |
| Acer Lenovo Integrated Webcam                       | 1         | 4.55%   |
| Acer Integrated Camera                              | 1         | 4.55%   |
| Acer HD Webcam                                      | 1         | 4.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 50%     |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Upek   | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 26        | 59.09%  |
| 1     | 13        | 29.55%  |
| 2     | 4         | 9.09%   |
| 3     | 1         | 2.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


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

