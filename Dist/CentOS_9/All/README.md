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

Total: 62

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [dfcebaef82](https://linux-hardware.org/?probe=dfcebaef82) | Aug 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [888c56f232](https://linux-hardware.org/?probe=888c56f232) | Aug 01, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [993a10a30b](https://linux-hardware.org/?probe=993a10a30b) | Aug 01, 2023 |
| Dell          | 07978V A05                  | Server      | [8e1deb831f](https://linux-hardware.org/?probe=8e1deb831f) | Jul 26, 2023 |
| Intel         | NUC7i3BNB J22859-315        | Mini pc     | [8b2dd0b294](https://linux-hardware.org/?probe=8b2dd0b294) | Jul 07, 2023 |
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

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.14.0-86.el9.x86_64           | 3         | 6%      |
| 5.14.0-202.el9.x86_64          | 3         | 6%      |
| 5.14.0-134.el9.x86_64          | 3         | 6%      |
| 5.14.0-325.el9.x86_64          | 2         | 4%      |
| 5.14.0-319.el9.x86_64          | 2         | 4%      |
| 5.14.0-214.el9.x86_64          | 2         | 4%      |
| 5.14.0-183.el9.x86_64          | 2         | 4%      |
| 5.14.0-171.el9.x86_64          | 2         | 4%      |
| 5.14.0-148.el9.x86_64          | 2         | 4%      |
| 6.1.8-1.el9.elrepo.x86_64      | 1         | 2%      |
| 6.1.1                          | 1         | 2%      |
| 5.17.2-lqx3.0.el9.x86_64       | 1         | 2%      |
| 5.14.0-78.el9.x86_64           | 1         | 2%      |
| 5.14.0-71.el9.x86_64           | 1         | 2%      |
| 5.14.0-66.el9.x86_64           | 1         | 2%      |
| 5.14.0-52.el9.x86_64           | 1         | 2%      |
| 5.14.0-44.el9.x86_64           | 1         | 2%      |
| 5.14.0-350.el9.x86_64          | 1         | 2%      |
| 5.14.0-344.el9.x86_64          | 1         | 2%      |
| 5.14.0-340.el9.x86_64          | 1         | 2%      |
| 5.14.0-333.el9.x86_64          | 1         | 2%      |
| 5.14.0-316.el9.x86_64          | 1         | 2%      |
| 5.14.0-305.el9.x86_64          | 1         | 2%      |
| 5.14.0-302.el9.x86_64          | 1         | 2%      |
| 5.14.0-299.el9.x86_64          | 1         | 2%      |
| 5.14.0-289.el9.x86_64          | 1         | 2%      |
| 5.14.0-283.el9.x86_64          | 1         | 2%      |
| 5.14.0-282.el9.x86_64          | 1         | 2%      |
| 5.14.0-267.el9.x86_64          | 1         | 2%      |
| 5.14.0-226.el9.x86_64          | 1         | 2%      |
| 5.14.0-200.el9.x86_64          | 1         | 2%      |
| 5.14.0-163.el9.x86_64          | 1         | 2%      |
| 5.14.0-130.rt21.130.el9.x86_64 | 1         | 2%      |
| 5.14.0-130.el9.x86_64          | 1         | 2%      |
| 5.14.0-12.el9.x86_64           | 1         | 2%      |
| 5.14.0-115.el9.x86_64          | 1         | 2%      |
| 5.14.0-109.el9.x86_64          | 1         | 2%      |
| 5.14.0-105.el9.x86_64          | 1         | 2%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 44        | 93.62%  |
| 6.1.8   | 1         | 2.13%   |
| 6.1.1   | 1         | 2.13%   |
| 5.17.2  | 1         | 2.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 44        | 93.62%  |
| 6.1     | 2         | 4.26%   |
| 5.17    | 1         | 2.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 46        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 39        | 84.78%  |
| KDE5          | 3         | 6.52%   |
| GNOME Classic | 2         | 4.35%   |
| Unknown       | 2         | 4.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 30        | 63.83%  |
| X11     | 15        | 31.91%  |
| Tty     | 2         | 4.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 26        | 55.32%  |
| GDM     | 18        | 38.3%   |
| SDDM    | 2         | 4.26%   |
| LightDM | 1         | 2.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 28        | 60.87%  |
| de_DE | 3         | 6.52%   |
| zh_CN | 2         | 4.35%   |
| ru_RU | 2         | 4.35%   |
| ja_JP | 2         | 4.35%   |
| it_IT | 2         | 4.35%   |
| sv_SE | 1         | 2.17%   |
| ru_UA | 1         | 2.17%   |
| pt_BR | 1         | 2.17%   |
| fr_FR | 1         | 2.17%   |
| en_IN | 1         | 2.17%   |
| en_GB | 1         | 2.17%   |
| en_AU | 1         | 2.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 34        | 73.91%  |
| BIOS | 12        | 26.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 42        | 91.3%   |
| Ext4 | 4         | 8.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 24        | 50%     |
| GPT     | 17        | 35.42%  |
| MBR     | 7         | 14.58%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 42        | 89.36%  |
| Yes       | 5         | 10.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 36        | 75%     |
| Yes       | 12        | 25%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 10        | 21.74%  |
| ASUSTek Computer    | 10        | 21.74%  |
| Intel               | 4         | 8.7%    |
| Acer                | 4         | 8.7%    |
| Hewlett-Packard     | 3         | 6.52%   |
| Timi                | 2         | 4.35%   |
| MSI                 | 2         | 4.35%   |
| Gigabyte Technology | 2         | 4.35%   |
| Dell                | 2         | 4.35%   |
| Zvezda              | 1         | 2.17%   |
| Razer               | 1         | 2.17%   |
| IP3 Tech            | 1         | 2.17%   |
| IBM                 | 1         | 2.17%   |
| Gateway             | 1         | 2.17%   |
| Colorful Technology | 1         | 2.17%   |
| AZW                 | 1         | 2.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUS PRIME H670-PLUS D4              | 2         | 4.35%   |
| Zvezda Altair Z                      | 1         | 2.17%   |
| Timi RedmiBook 16                    | 1         | 2.17%   |
| Timi Mi NoteBook Horizon Edition 14  | 1         | 2.17%   |
| Razer Blade 15 (2022) - RZ09-0421    | 1         | 2.17%   |
| MSI MS-7B79                          | 1         | 2.17%   |
| MSI Katana GF76 12UE                 | 1         | 2.17%   |
| Lenovo Yoga S740-14IIL 81RS          | 1         | 2.17%   |
| Lenovo V15 G2 ITL 82KB               | 1         | 2.17%   |
| Lenovo ThinkPad T460s 20FAS5WX00     | 1         | 2.17%   |
| Lenovo ThinkPad T430 2349DG5         | 1         | 2.17%   |
| Lenovo ThinkPad T430 2347DE9         | 1         | 2.17%   |
| Lenovo ThinkPad L14 Gen 1 20U5S0NT00 | 1         | 2.17%   |
| Lenovo Legion 5P 15IMH05H 82AW       | 1         | 2.17%   |
| Lenovo IdeaPad S145-15IWL 81S9       | 1         | 2.17%   |
| Lenovo G580 20150                    | 1         | 2.17%   |
| Lenovo G410 20237                    | 1         | 2.17%   |
| IP3 Tech HeroBox                     | 1         | 2.17%   |
| Intel NUC7i3BNK                      | 1         | 2.17%   |
| Intel NUC12WSHi7                     | 1         | 2.17%   |
| Intel NUC12WSHi5                     | 1         | 2.17%   |
| Intel D34010WYK H14771-303           | 1         | 2.17%   |
| IBM System x3250 M3 -[425242G]       | 1         | 2.17%   |
| HP Pavilion Gaming Laptop 15-ec0xxx  | 1         | 2.17%   |
| HP EliteBook 840 G3                  | 1         | 2.17%   |
| HP EliteBook 840 G1                  | 1         | 2.17%   |
| Gigabyte X99-UD4-CF                  | 1         | 2.17%   |
| Gigabyte 970A-DS3P                   | 1         | 2.17%   |
| Gateway SX2865                       | 1         | 2.17%   |
| Dell PowerEdge T640                  | 1         | 2.17%   |
| Dell OptiPlex 790                    | 1         | 2.17%   |
| Colorful CVN Z590 GAMING PRO         | 1         | 2.17%   |
| AZW SER                              | 1         | 2.17%   |
| ASUS TUF Gaming X570-PLUS            | 1         | 2.17%   |
| ASUS ROG STRIX B560-G GAMING WIFI    | 1         | 2.17%   |
| ASUS ROG CROSSHAIR VIII DARK HERO    | 1         | 2.17%   |
| ASUS Q550LF                          | 1         | 2.17%   |
| ASUS P8H67-M LE                      | 1         | 2.17%   |
| ASUS P8H61/USB3                      | 1         | 2.17%   |
| ASUS N751JK                          | 1         | 2.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 4         | 8.7%    |
| HP EliteBook        | 2         | 4.35%   |
| ASUS ROG            | 2         | 4.35%   |
| ASUS PRIME          | 2         | 4.35%   |
| Acer Aspire         | 2         | 4.35%   |
| Zvezda Altair       | 1         | 2.17%   |
| Timi RedmiBook      | 1         | 2.17%   |
| Timi Mi             | 1         | 2.17%   |
| Razer Blade         | 1         | 2.17%   |
| MSI MS-7B79         | 1         | 2.17%   |
| MSI Katana          | 1         | 2.17%   |
| Lenovo Yoga         | 1         | 2.17%   |
| Lenovo V15          | 1         | 2.17%   |
| Lenovo Legion       | 1         | 2.17%   |
| Lenovo IdeaPad      | 1         | 2.17%   |
| Lenovo G580         | 1         | 2.17%   |
| Lenovo G410         | 1         | 2.17%   |
| IP3 Tech HeroBox    | 1         | 2.17%   |
| Intel NUC7i3BNK     | 1         | 2.17%   |
| Intel NUC12WSHi7    | 1         | 2.17%   |
| Intel NUC12WSHi5    | 1         | 2.17%   |
| Intel D34010WYK     | 1         | 2.17%   |
| IBM System          | 1         | 2.17%   |
| HP Pavilion         | 1         | 2.17%   |
| Gigabyte X99-UD4-CF | 1         | 2.17%   |
| Gigabyte 970A-DS3P  | 1         | 2.17%   |
| Gateway SX2865      | 1         | 2.17%   |
| Dell PowerEdge      | 1         | 2.17%   |
| Dell OptiPlex       | 1         | 2.17%   |
| Colorful CVN        | 1         | 2.17%   |
| AZW SER             | 1         | 2.17%   |
| ASUS TUF            | 1         | 2.17%   |
| ASUS Q550LF         | 1         | 2.17%   |
| ASUS P8H67-M        | 1         | 2.17%   |
| ASUS P8H61          | 1         | 2.17%   |
| ASUS N751JK         | 1         | 2.17%   |
| ASUS All            | 1         | 2.17%   |
| Acer Swift          | 1         | 2.17%   |
| Acer Predator       | 1         | 2.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 9         | 19.57%  |
| 2021 | 7         | 15.22%  |
| 2022 | 5         | 10.87%  |
| 2020 | 5         | 10.87%  |
| 2019 | 5         | 10.87%  |
| 2012 | 5         | 10.87%  |
| 2016 | 2         | 4.35%   |
| 2014 | 2         | 4.35%   |
| 2011 | 2         | 4.35%   |
| 2023 | 1         | 2.17%   |
| 2018 | 1         | 2.17%   |
| 2010 | 1         | 2.17%   |
| 2009 | 1         | 2.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 22        | 47.83%  |
| Desktop  | 16        | 34.78%  |
| Mini pc  | 5         | 10.87%  |
| Server   | 3         | 6.52%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 43        | 93.48%  |
| Enabled  | 3         | 6.52%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 46        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 18        | 39.13%  |
| 8.01-16.0       | 10        | 21.74%  |
| 32.01-64.0      | 7         | 15.22%  |
| 64.01-256.0     | 4         | 8.7%    |
| More than 256.0 | 2         | 4.35%   |
| 3.01-4.0        | 2         | 4.35%   |
| 16.01-24.0      | 2         | 4.35%   |
| 24.01-32.0      | 1         | 2.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 20        | 40.82%  |
| 3.01-4.0  | 10        | 20.41%  |
| 4.01-8.0  | 9         | 18.37%  |
| 1.01-2.0  | 4         | 8.16%   |
| 8.01-16.0 | 4         | 8.16%   |
| 0.51-1.0  | 2         | 4.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 21        | 45.65%  |
| 2      | 12        | 26.09%  |
| 4      | 5         | 10.87%  |
| 3      | 5         | 10.87%  |
| 5      | 2         | 4.35%   |
| 10     | 1         | 2.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 36        | 78.26%  |
| Yes       | 10        | 21.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 89.13%  |
| No        | 5         | 10.87%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 78.26%  |
| No        | 10        | 21.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 69.57%  |
| No        | 14        | 30.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 8         | 17.39%  |
| Germany      | 6         | 13.04%  |
| China        | 3         | 6.52%   |
| Bulgaria     | 3         | 6.52%   |
| Ukraine      | 2         | 4.35%   |
| Japan        | 2         | 4.35%   |
| Italy        | 2         | 4.35%   |
| Canada       | 2         | 4.35%   |
| Uzbekistan   | 1         | 2.17%   |
| Switzerland  | 1         | 2.17%   |
| Sweden       | 1         | 2.17%   |
| South Africa | 1         | 2.17%   |
| Russia       | 1         | 2.17%   |
| Puerto Rico  | 1         | 2.17%   |
| Poland       | 1         | 2.17%   |
| Netherlands  | 1         | 2.17%   |
| Myanmar      | 1         | 2.17%   |
| Kazakhstan   | 1         | 2.17%   |
| India        | 1         | 2.17%   |
| France       | 1         | 2.17%   |
| Finland      | 1         | 2.17%   |
| Colombia     | 1         | 2.17%   |
| Chile        | 1         | 2.17%   |
| Brazil       | 1         | 2.17%   |
| Belarus      | 1         | 2.17%   |
| Australia    | 1         | 2.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sofia          | 2         | 4.17%   |
| Bristow        | 2         | 4.17%   |
| Beijing        | 2         | 4.17%   |
| Yangon         | 1         | 2.08%   |
| Wuhan          | 1         | 2.08%   |
| Vitebsk        | 1         | 2.08%   |
| Tomah          | 1         | 2.08%   |
| Tashkent       | 1         | 2.08%   |
| Stromberg      | 1         | 2.08%   |
| Stockholm      | 1         | 2.08%   |
| Soest          | 1         | 2.08%   |
| Schemmerhofen  | 1         | 2.08%   |
| San Juan       | 1         | 2.08%   |
| Ruda Śląska  | 1         | 2.08%   |
| Rome           | 1         | 2.08%   |
| Ribeirao Preto | 1         | 2.08%   |
| Quitman        | 1         | 2.08%   |
| Puente Alto    | 1         | 2.08%   |
| Portland       | 1         | 2.08%   |
| Perth          | 1         | 2.08%   |
| Persan         | 1         | 2.08%   |
| Okazaki        | 1         | 2.08%   |
| New York       | 1         | 2.08%   |
| New Cumberland | 1         | 2.08%   |
| Nagoya         | 1         | 2.08%   |
| Mumbai         | 1         | 2.08%   |
| Moscow         | 1         | 2.08%   |
| Michelstadt    | 1         | 2.08%   |
| Meieki         | 1         | 2.08%   |
| L'Isle-Adam    | 1         | 2.08%   |
| Kyiv           | 1         | 2.08%   |
| Kramatorsk     | 1         | 2.08%   |
| Helsinki       | 1         | 2.08%   |
| Hamburg        | 1         | 2.08%   |
| Durban         | 1         | 2.08%   |
| Dortmund       | 1         | 2.08%   |
| Burgas         | 1         | 2.08%   |
| Bogotá        | 1         | 2.08%   |
| Birmensdorf    | 1         | 2.08%   |
| Berlin         | 1         | 2.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 13        | 19     | 16.88%  |
| WDC                       | 11        | 14     | 14.29%  |
| Seagate                   | 8         | 10     | 10.39%  |
| Kingston                  | 8         | 9      | 10.39%  |
| Toshiba                   | 4         | 6      | 5.19%   |
| Sandisk                   | 3         | 9      | 3.9%    |
| Intel                     | 3         | 3      | 3.9%    |
| HGST                      | 3         | 4      | 3.9%    |
| SK hynix                  | 2         | 2      | 2.6%    |
| Micron Technology         | 2         | 2      | 2.6%    |
| Crucial                   | 2         | 8      | 2.6%    |
| WD MediaMax               | 1         | 1      | 1.3%    |
| Unknown                   | 1         | 1      | 1.3%    |
| Union Memory              | 1         | 1      | 1.3%    |
| Team                      | 1         | 2      | 1.3%    |
| Plextor                   | 1         | 1      | 1.3%    |
| Phison Electronics        | 1         | 1      | 1.3%    |
| Phison                    | 1         | 1      | 1.3%    |
| OCZ                       | 1         | 1      | 1.3%    |
| Netac                     | 1         | 2      | 1.3%    |
| Micron/Crucial Technology | 1         | 1      | 1.3%    |
| LITEON                    | 1         | 1      | 1.3%    |
| Intenso                   | 1         | 1      | 1.3%    |
| Hjwdz                     | 1         | 1      | 1.3%    |
| Hitachi                   | 1         | 1      | 1.3%    |
| Hewlett-Packard           | 1         | 1      | 1.3%    |
| Gigabyte Technology       | 1         | 2      | 1.3%    |
| ASMT                      | 1         | 1      | 1.3%    |
| A-DATA Technology         | 1         | 1      | 1.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Sandisk WD_BLACK SN770 1TB                          | 2         | 2.38%   |
| SanDisk SDSSDH3 1T00 1TB                            | 2         | 2.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 2         | 2.38%   |
| Samsung MZNLH512HALU-00000 512GB SSD                | 2         | 2.38%   |
| Micron 2450_MTFDKBA512TFK 512GB                     | 2         | 2.38%   |
| Crucial CT525MX300SSD1 528GB                        | 2         | 2.38%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                    | 1         | 1.19%   |
| WDC WD6400BEVT-22A0RT0 640GB                        | 1         | 1.19%   |
| WDC WD6003FZBX-00K5WB0 6TB                          | 1         | 1.19%   |
| WDC WD5000LPLX-60ZNTT1 500GB                        | 1         | 1.19%   |
| WDC WD5000BEVT-55A0RT0 500GB                        | 1         | 1.19%   |
| WDC WD3200AAKX-753CA1 320GB                         | 1         | 1.19%   |
| WDC WD2500AAJS-60M0A0 250GB                         | 1         | 1.19%   |
| WDC WD22EJRX-89BEMY0 2TB                            | 1         | 1.19%   |
| WDC WD2003FZEX-00Z4SA0 2TB                          | 1         | 1.19%   |
| WDC WD10EZEX-60M2NA0 1TB                            | 1         | 1.19%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 1         | 1.19%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 1         | 1.19%   |
| WD MediaMax WL750GSA6472 752GB                      | 1         | 1.19%   |
| Unknown MMC Card  7GB                               | 1         | 1.19%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB             | 1         | 1.19%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 1.19%   |
| Toshiba MK2561GSYN 250GB                            | 1         | 1.19%   |
| Toshiba DT01ACA100 1TB                              | 1         | 1.19%   |
| Toshiba AL15SEB24EQY 2TB                            | 1         | 1.19%   |
| Toshiba AL15SEB24EQY 2.4TB                          | 1         | 1.19%   |
| Team T253X1480G 480GB SSD                           | 1         | 1.19%   |
| SK hynix NVMe SSD Drive 256GB                       | 1         | 1.19%   |
| SK hynix BC501 NVMe 256GB                           | 1         | 1.19%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1.19%   |
| Seagate ST3500413AS 500GB                           | 1         | 1.19%   |
| Seagate ST3250820AS 250GB                           | 1         | 1.19%   |
| Seagate ST2000DL003-9VT166 2TB                      | 1         | 1.19%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1.19%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1.19%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1.19%   |
| Seagate FireCuda 520 SSD ZP2000GM30002 2TB          | 1         | 1.19%   |
| Seagate FireCuda 520 SSD ZP1000GM30002 1TB          | 1         | 1.19%   |
| SanDisk SD6SB1M-128G-1006 128GB SSD                 | 1         | 1.19%   |
| Samsung SSD 870 QVO 2TB                             | 1         | 1.19%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor      | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| WDC         | 10        | 13     | 37.04%  |
| Seagate     | 7         | 8      | 25.93%  |
| Toshiba     | 4         | 5      | 14.81%  |
| HGST        | 3         | 4      | 11.11%  |
| WD MediaMax | 1         | 1      | 3.7%    |
| Hitachi     | 1         | 1      | 3.7%    |
| ASMT        | 1         | 1      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 14     | 29.03%  |
| Kingston            | 6         | 7      | 19.35%  |
| SanDisk             | 3         | 5      | 9.68%   |
| Crucial             | 2         | 8      | 6.45%   |
| WDC                 | 1         | 1      | 3.23%   |
| Team                | 1         | 2      | 3.23%   |
| Plextor             | 1         | 1      | 3.23%   |
| OCZ                 | 1         | 1      | 3.23%   |
| Netac               | 1         | 2      | 3.23%   |
| LITEON              | 1         | 1      | 3.23%   |
| Intenso             | 1         | 1      | 3.23%   |
| Intel               | 1         | 1      | 3.23%   |
| Hewlett-Packard     | 1         | 1      | 3.23%   |
| Gigabyte Technology | 1         | 2      | 3.23%   |
| A-DATA Technology   | 1         | 1      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 26        | 48     | 38.24%  |
| HDD     | 21        | 33     | 30.88%  |
| NVMe    | 18        | 23     | 26.47%  |
| Unknown | 2         | 2      | 2.94%   |
| MMC     | 1         | 1      | 1.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 36        | 78     | 61.02%  |
| NVMe | 18        | 23     | 30.51%  |
| SAS  | 4         | 5      | 6.78%   |
| MMC  | 1         | 1      | 1.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 25        | 38     | 52.08%  |
| 0.51-1.0   | 16        | 33     | 33.33%  |
| 1.01-2.0   | 5         | 7      | 10.42%  |
| 2.01-3.0   | 1         | 1      | 2.08%   |
| 4.01-10.0  | 1         | 2      | 2.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 16        | 33.33%  |
| 251-500        | 9         | 18.75%  |
| 1001-2000      | 9         | 18.75%  |
| 501-1000       | 6         | 12.5%   |
| 2001-3000      | 4         | 8.33%   |
| More than 3000 | 2         | 4.17%   |
| 21-50          | 1         | 2.08%   |
| 51-100         | 1         | 2.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 21        | 44.68%  |
| 251-500        | 5         | 10.64%  |
| 101-250        | 5         | 10.64%  |
| 51-100         | 5         | 10.64%  |
| 21-50          | 4         | 8.51%   |
| 501-1000       | 3         | 6.38%   |
| 1001-2000      | 2         | 4.26%   |
| More than 3000 | 1         | 2.13%   |
| 2001-3000      | 1         | 2.13%   |

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
| Detected | 30        | 59     | 55.56%  |
| Works    | 20        | 43     | 37.04%  |
| Malfunc  | 4         | 5      | 7.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 37        | 57.81%  |
| AMD                         | 6         | 9.38%   |
| Samsung Electronics         | 4         | 6.25%   |
| SK hynix                    | 2         | 3.13%   |
| SanDisk                     | 2         | 3.13%   |
| Phison Electronics          | 2         | 3.13%   |
| Micron Technology           | 2         | 3.13%   |
| LSI Logic / Symbios Logic   | 2         | 3.13%   |
| Kingston Technology Company | 2         | 3.13%   |
| Union Memory (Shenzhen)     | 1         | 1.56%   |
| Silicon Image               | 1         | 1.56%   |
| Seagate Technology          | 1         | 1.56%   |
| Micron/Crucial Technology   | 1         | 1.56%   |
| Broadcom / LSI              | 1         | 1.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 5         | 7.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 5.71%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 5.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 5.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 4.29%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 3         | 4.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 4.29%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 2         | 2.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 2.86%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 2.86%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 2.86%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 2.86%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 2         | 2.86%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2         | 2.86%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 2.86%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                          | 1         | 1.43%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 1.43%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 1.43%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1         | 1.43%   |
| Seagate FireCuda 520 SSD                                                       | 1         | 1.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.43%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 1.43%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.43%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 1.43%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                 | 1         | 1.43%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                        | 1         | 1.43%   |
| Kingston Company NVMe Controller                                               | 1         | 1.43%   |
| Kingston Company KC3000/Renegade NVMe SSD                                      | 1         | 1.43%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.43%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1         | 1.43%   |
| Intel SSD 660P Series                                                          | 1         | 1.43%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 1.43%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.43%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.43%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.43%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                   | 1         | 1.43%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1         | 1.43%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.43%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1         | 1.43%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 39        | 60.94%  |
| NVMe | 18        | 28.13%  |
| RAID | 5         | 7.81%   |
| SCSI | 1         | 1.56%   |
| IDE  | 1         | 1.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 38        | 82.61%  |
| AMD    | 8         | 17.39%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-1260P            | 2         | 4.35%   |
| Intel 12th Gen Core i5-12600K           | 2         | 4.35%   |
| Intel Xeon Silver 4215R CPU @ 3.20GHz   | 1         | 2.17%   |
| Intel Xeon Gold 6326 CPU @ 2.90GHz      | 1         | 2.17%   |
| Intel Xeon CPU X3440 @ 2.53GHz          | 1         | 2.17%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 2.17%   |
| Intel Core i7-5930K CPU @ 3.50GHz       | 1         | 2.17%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 1         | 2.17%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 1         | 2.17%   |
| Intel Core i7-2600K CPU @ 3.40GHz       | 1         | 2.17%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 2.17%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 1         | 2.17%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 1         | 2.17%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 1         | 2.17%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 1         | 2.17%   |
| Intel Core i5-4440 CPU @ 3.10GHz        | 1         | 2.17%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 1         | 2.17%   |
| Intel Core i5-4200M CPU @ 2.50GHz       | 1         | 2.17%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 1         | 2.17%   |
| Intel Core i5-3380M CPU @ 2.90GHz       | 1         | 2.17%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 2.17%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 1         | 2.17%   |
| Intel Core i5-2400S CPU @ 2.50GHz       | 1         | 2.17%   |
| Intel Core i5-10400F CPU @ 2.90GHz      | 1         | 2.17%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 1         | 2.17%   |
| Intel Core i5 CPU M 430 @ 2.27GHz       | 1         | 2.17%   |
| Intel Core i3-7100U CPU @ 2.40GHz       | 1         | 2.17%   |
| Intel Core i3-4010U CPU @ 1.70GHz       | 1         | 2.17%   |
| Intel Core i3-3217U CPU @ 1.80GHz       | 1         | 2.17%   |
| Intel Core i3-2130 CPU @ 3.40GHz        | 1         | 2.17%   |
| Intel Celeron J4125 CPU @ 2.00GHz       | 1         | 2.17%   |
| Intel 12th Gen Core i7-12800H           | 1         | 2.17%   |
| Intel 12th Gen Core i7-12700H           | 1         | 2.17%   |
| Intel 12th Gen Core i5-1240P            | 1         | 2.17%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz  | 1         | 2.17%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 1         | 2.17%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 1         | 2.17%   |
| AMD Ryzen 9 3950X 16-Core Processor     | 1         | 2.17%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 1         | 2.17%   |
| AMD Ryzen 5 4500U with Radeon Graphics  | 1         | 2.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 14        | 30.43%  |
| Other             | 9         | 19.57%  |
| Intel Core i7     | 7         | 15.22%  |
| Intel Core i3     | 4         | 8.7%    |
| AMD Ryzen 5       | 3         | 6.52%   |
| AMD Ryzen 9       | 2         | 4.35%   |
| Intel Xeon Silver | 1         | 2.17%   |
| Intel Xeon Gold   | 1         | 2.17%   |
| Intel Xeon        | 1         | 2.17%   |
| Intel Celeron     | 1         | 2.17%   |
| AMD Ryzen 7       | 1         | 2.17%   |
| AMD Ryzen 3 PRO   | 1         | 2.17%   |
| AMD FX            | 1         | 2.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 15        | 32.61%  |
| 2      | 13        | 28.26%  |
| 6      | 6         | 13.04%  |
| 16     | 3         | 6.52%   |
| 12     | 3         | 6.52%   |
| 14     | 2         | 4.35%   |
| 10     | 2         | 4.35%   |
| 32     | 1         | 2.17%   |
| 8      | 1         | 2.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 44        | 95.65%  |
| 2      | 2         | 4.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 36        | 78.26%  |
| 1      | 10        | 21.74%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 46        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 10        | 21.74%  |
| 0x906a3    | 5         | 10.87%  |
| 0x306c3    | 4         | 8.7%    |
| 0x306a9    | 4         | 8.7%    |
| 0x40651    | 3         | 6.52%   |
| 0x806ec    | 2         | 4.35%   |
| 0x406e3    | 2         | 4.35%   |
| 0x08600106 | 2         | 4.35%   |
| 0xa0671    | 1         | 2.17%   |
| 0xa0653    | 1         | 2.17%   |
| 0xa0652    | 1         | 2.17%   |
| 0x90672    | 1         | 2.17%   |
| 0x706e5    | 1         | 2.17%   |
| 0x706a8    | 1         | 2.17%   |
| 0x606a6    | 1         | 2.17%   |
| 0x306f2    | 1         | 2.17%   |
| 0x206a7    | 1         | 2.17%   |
| 0x20652    | 1         | 2.17%   |
| 0x0a201016 | 1         | 2.17%   |
| 0x08701021 | 1         | 2.17%   |
| 0x08701013 | 1         | 2.17%   |
| 0x0600063d | 1         | 2.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 8         | 17.39%  |
| Alderlake Hybrid | 7         | 15.22%  |
| Zen 2            | 5         | 10.87%  |
| IvyBridge        | 5         | 10.87%  |
| Skylake          | 3         | 6.52%   |
| SandyBridge      | 3         | 6.52%   |
| KabyLake         | 3         | 6.52%   |
| Icelake          | 3         | 6.52%   |
| CometLake        | 2         | 4.35%   |
| Zen+             | 1         | 2.17%   |
| Zen 3            | 1         | 2.17%   |
| Westmere         | 1         | 2.17%   |
| TigerLake        | 1         | 2.17%   |
| Nehalem          | 1         | 2.17%   |
| Goldmont plus    | 1         | 2.17%   |
| Bulldozer        | 1         | 2.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 25        | 43.1%   |
| Nvidia                     | 19        | 32.76%  |
| AMD                        | 11        | 18.97%  |
| Matrox Electronics Systems | 2         | 3.45%   |
| ASPEED Technology          | 1         | 1.72%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P Integrated Graphics Controller                         | 5         | 8.33%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 6.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 5%      |
| AMD Renoir                                                                | 3         | 5%      |
| Nvidia TU117 [GeForce GTX 1650]                                           | 2         | 3.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 3.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 2         | 3.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 3.33%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 1.67%   |
| Nvidia TU116 [GeForce GTX 1660]                                           | 1         | 1.67%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 1         | 1.67%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 1.67%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                        | 1         | 1.67%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                 | 1         | 1.67%   |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 1.67%   |
| Nvidia GP107M [GeForce MX350]                                             | 1         | 1.67%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                         | 1         | 1.67%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 1.67%   |
| Nvidia GM107M [GeForce GTX 850M]                                          | 1         | 1.67%   |
| Nvidia GM107 [GeForce GTX 745]                                            | 1         | 1.67%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 1         | 1.67%   |
| Nvidia GK208B [GeForce GT 730]                                            | 1         | 1.67%   |
| Nvidia GK107M [GeForce GT 745M]                                           | 1         | 1.67%   |
| Nvidia GF108M [NVS 5400M]                                                 | 1         | 1.67%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 1.67%   |
| Nvidia GA103M [GeForce RTX 3080 Ti Mobile]                                | 1         | 1.67%   |
| Matrox Electronics Systems MGA G200EV                                     | 1         | 1.67%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller  | 1         | 1.67%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 1.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 1         | 1.67%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                 | 1         | 1.67%   |
| Intel Iris Plus Graphics G7                                               | 1         | 1.67%   |
| Intel HD Graphics 620                                                     | 1         | 1.67%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 1.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 1.67%   |
| ASPEED Technology ASPEED Graphics Family                                  | 1         | 1.67%   |
| AMD RV370 [Radeon X300/X550/X1050 Series] (Secondary)                     | 1         | 1.67%   |
| AMD RV370 [Radeon X300/X550/X1050 Series]                                 | 1         | 1.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 1.67%   |
| AMD Park [Mobility Radeon HD 5430]                                        | 1         | 1.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 15        | 32.61%  |
| Intel + Nvidia  | 9         | 19.57%  |
| 1 x Nvidia      | 8         | 17.39%  |
| 1 x AMD         | 8         | 17.39%  |
| 2 x AMD         | 1         | 2.17%   |
| Nvidia + Matrox | 1         | 2.17%   |
| 1 x Matrox      | 1         | 2.17%   |
| Intel + AMD     | 1         | 2.17%   |
| 1 x ASPEED      | 1         | 2.17%   |
| AMD + Nvidia    | 1         | 2.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 37        | 78.72%  |
| Proprietary | 8         | 17.02%  |
| Unknown     | 2         | 4.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 51.02%  |
| 1.01-2.0   | 5         | 10.2%   |
| 5.01-6.0   | 4         | 8.16%   |
| 3.01-4.0   | 4         | 8.16%   |
| 0.51-1.0   | 4         | 8.16%   |
| 0.01-0.5   | 4         | 8.16%   |
| 8.01-16.0  | 3         | 6.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 14.29%  |
| LG Display          | 6         | 12.24%  |
| Chimei Innolux      | 5         | 10.2%   |
| AU Optronics        | 4         | 8.16%   |
| ViewSonic           | 3         | 6.12%   |
| Goldstar            | 3         | 6.12%   |
| Dell                | 3         | 6.12%   |
| Iiyama              | 2         | 4.08%   |
| Hewlett-Packard     | 2         | 4.08%   |
| BOE                 | 2         | 4.08%   |
| Acer                | 2         | 4.08%   |
| TMX                 | 1         | 2.04%   |
| SKY                 | 1         | 2.04%   |
| PANDA               | 1         | 2.04%   |
| LG Electronics      | 1         | 2.04%   |
| KVM                 | 1         | 2.04%   |
| Gigabyte Technology | 1         | 2.04%   |
| Eizo                | 1         | 2.04%   |
| CHD                 | 1         | 2.04%   |
| BenQ                | 1         | 2.04%   |
| AOC                 | 1         | 2.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Iiyama PL2888H IVM7106 1920x1080 620x340mm 27.8-inch                  | 2         | 3.85%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch         | 1         | 1.92%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch         | 1         | 1.92%   |
| ViewSonic PJ402D-2 HCD7B1D 1280x960                                   | 1         | 1.92%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 1         | 1.92%   |
| SKY 22X1-M225F SKY2150 1920x1080 476x268mm 21.5-inch                  | 1         | 1.92%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 607x345mm 27.5-inch     | 1         | 1.92%   |
| Samsung Electronics SyncMaster SAM05EB 1920x1080 597x336mm 27.0-inch  | 1         | 1.92%   |
| Samsung Electronics SMT22A350 SAM07A7 1920x1080 477x268mm 21.5-inch   | 1         | 1.92%   |
| Samsung Electronics SMEX2220 SAM0686 1920x1080 477x268mm 21.5-inch    | 1         | 1.92%   |
| Samsung Electronics S27C450 SAM09D9 1920x1080 598x336mm 27.0-inch     | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch | 1         | 1.92%   |
| PANDA LCD Monitor NCP0052 1920x1080 309x174mm 14.0-inch               | 1         | 1.92%   |
| LG Electronics LCD Monitor LG FULL HD                                 | 1         | 1.92%   |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch          | 1         | 1.92%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 1.92%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch          | 1         | 1.92%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch           | 1         | 1.92%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 1         | 1.92%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 1         | 1.92%   |
| KVM LCD Monitor 1 1 9" KVM4308 1280x1024 338x270mm 17.0-inch          | 1         | 1.92%   |
| Hewlett-Packard L185x HWP298C 1366x768 410x230mm 18.5-inch            | 1         | 1.92%   |
| Hewlett-Packard 2159 HWP282C 1920x1080 479x269mm 21.6-inch            | 1         | 1.92%   |
| Goldstar ULTRAGEAR GSM5B70 1920x1080 531x298mm 24.0-inch              | 1         | 1.92%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 1         | 1.92%   |
| Goldstar 22EA53 GSM59A6 1920x1080 477x268mm 21.5-inch                 | 1         | 1.92%   |
| Gigabyte Technology G34WQC A GBT3403 3440x1440 797x334mm 34.0-inch    | 1         | 1.92%   |
| Eizo EV2450 ENC2532 1920x1080 528x297mm 23.9-inch                     | 1         | 1.92%   |
| Dell U2520D DELA150 2560x1440 553x311mm 25.0-inch                     | 1         | 1.92%   |
| Dell U2520D DELA14E 2560x1440 553x311mm 25.0-inch                     | 1         | 1.92%   |
| Dell U2520D DELA14C 2560x1440 553x311mm 25.0-inch                     | 1         | 1.92%   |
| Dell SE2219H DELF10E 1920x1080 476x268mm 21.5-inch                    | 1         | 1.92%   |
| Dell P2418HT DEL4113 1920x1080 527x296mm 23.8-inch                    | 1         | 1.92%   |
| Dell 2408WFP DELA029 1920x1200 519x324mm 24.1-inch                    | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN1608 1920x1080 355x199mm 16.0-inch      | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch       | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch      | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch       | 1         | 1.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 27        | 58.7%   |
| 1366x768 (WXGA)   | 6         | 13.04%  |
| 3840x2160 (4K)    | 2         | 4.35%   |
| 2560x1440 (QHD)   | 2         | 4.35%   |
| 1600x900 (HD+)    | 2         | 4.35%   |
| 3840x1080         | 1         | 2.17%   |
| 3440x1440         | 1         | 2.17%   |
| 3200x2000         | 1         | 2.17%   |
| 1920x1200 (WUXGA) | 1         | 2.17%   |
| 1280x960          | 1         | 2.17%   |
| 1280x1024 (SXGA)  | 1         | 2.17%   |
| Unknown           | 1         | 2.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 14      | 9         | 18.37%  |
| 15      | 8         | 16.33%  |
| 21      | 7         | 14.29%  |
| 27      | 6         | 12.24%  |
| 24      | 6         | 12.24%  |
| 23      | 3         | 6.12%   |
| Unknown | 2         | 4.08%   |
| 84      | 1         | 2.04%   |
| 34      | 1         | 2.04%   |
| 25      | 1         | 2.04%   |
| 19      | 1         | 2.04%   |
| 18      | 1         | 2.04%   |
| 17      | 1         | 2.04%   |
| 16      | 1         | 2.04%   |
| 13      | 1         | 2.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 18        | 39.13%  |
| 501-600     | 10        | 21.74%  |
| 401-500     | 8         | 17.39%  |
| 601-700     | 3         | 6.52%   |
| 351-400     | 3         | 6.52%   |
| Unknown     | 2         | 4.35%   |
| 701-800     | 1         | 2.17%   |
| 1501-2000   | 1         | 2.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 35        | 85.37%  |
| 16/10   | 2         | 4.88%   |
| 5/4     | 1         | 2.44%   |
| 4/3     | 1         | 2.44%   |
| 21/9    | 1         | 2.44%   |
| Unknown | 1         | 2.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 10        | 21.28%  |
| 201-250        | 10        | 21.28%  |
| 101-110        | 8         | 17.02%  |
| 301-350        | 6         | 12.77%  |
| 251-300        | 3         | 6.38%   |
| 151-200        | 3         | 6.38%   |
| Unknown        | 2         | 4.26%   |
| More than 1000 | 1         | 2.13%   |
| 351-500        | 1         | 2.13%   |
| 141-150        | 1         | 2.13%   |
| 121-130        | 1         | 2.13%   |
| 111-120        | 1         | 2.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 14        | 30.43%  |
| 101-120       | 14        | 30.43%  |
| 51-100        | 14        | 30.43%  |
| Unknown       | 2         | 4.35%   |
| More than 240 | 1         | 2.17%   |
| 161-240       | 1         | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 33        | 70.21%  |
| 2     | 7         | 14.89%  |
| 0     | 5         | 10.64%  |
| 4     | 1         | 2.13%   |
| 3     | 1         | 2.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 31        | 41.33%  |
| Realtek Semiconductor             | 19        | 25.33%  |
| Qualcomm Atheros                  | 9         | 12%     |
| Broadcom                          | 4         | 5.33%   |
| Xiaomi                            | 1         | 1.33%   |
| U-Blox                            | 1         | 1.33%   |
| TP-Link                           | 1         | 1.33%   |
| Mellanox Technologies             | 1         | 1.33%   |
| MediaTek                          | 1         | 1.33%   |
| IBM                               | 1         | 1.33%   |
| Ericsson Business Mobile Networks | 1         | 1.33%   |
| Dell                              | 1         | 1.33%   |
| Ceton Technologies                | 1         | 1.33%   |
| ASUSTek Computer                  | 1         | 1.33%   |
| ASIX Electronics                  | 1         | 1.33%   |
| Aquantia                          | 1         | 1.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 15.22%  |
| Intel Ethernet Controller I225-V                                  | 5         | 5.43%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 5.43%   |
| Intel Wireless 7260                                               | 4         | 4.35%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 3.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 3.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 2.17%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 2.17%   |
| Intel Wireless 8260                                               | 2         | 2.17%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 2.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 2.17%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 2.17%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.09%   |
| U-Blox [u-blox 8]                                                 | 1         | 1.09%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 1.09%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 1.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.09%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.09%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.09%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 1.09%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.09%   |
| Mellanox MT27800 Family [ConnectX-5]                              | 1         | 1.09%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 1.09%   |
| Intel Wireless-AC 9260                                            | 1         | 1.09%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.09%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.09%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 1.09%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.09%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.09%   |
| Intel Ethernet Controller XL710 for 40GbE QSFP+                   | 1         | 1.09%   |
| Intel Ethernet Controller X710 for 10GBASE-T                      | 1         | 1.09%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.09%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.09%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.09%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.09%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.09%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.09%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 57.89%  |
| Qualcomm Atheros      | 8         | 21.05%  |
| Realtek Semiconductor | 4         | 10.53%  |
| TP-Link               | 1         | 2.63%   |
| MediaTek              | 1         | 2.63%   |
| Broadcom              | 1         | 2.63%   |
| ASUSTek Computer      | 1         | 2.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                               | 5         | 13.16%  |
| Intel Wireless 7260                                            | 4         | 10.53%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 7.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 5.26%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 5.26%   |
| Intel Wireless 8260                                            | 2         | 5.26%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 5.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 5.26%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1         | 2.63%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 2.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 2.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 2.63%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 2.63%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1         | 2.63%   |
| Intel Wireless-AC 9260                                         | 1         | 2.63%   |
| Intel Wireless 8265 / 8275                                     | 1         | 2.63%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 2.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 2.63%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 2.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 2.63%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2.63%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 2.63%   |
| ASUS 802.11ac NIC                                              | 1         | 2.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 40.82%  |
| Realtek Semiconductor | 17        | 34.69%  |
| Broadcom              | 3         | 6.12%   |
| Qualcomm Atheros      | 2         | 4.08%   |
| Xiaomi                | 1         | 2.04%   |
| Mellanox Technologies | 1         | 2.04%   |
| IBM                   | 1         | 2.04%   |
| Dell                  | 1         | 2.04%   |
| Ceton Technologies    | 1         | 2.04%   |
| ASIX Electronics      | 1         | 2.04%   |
| Aquantia              | 1         | 2.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 14        | 26.92%  |
| Intel Ethernet Controller I225-V                                      | 5         | 9.62%   |
| Realtek RTL8125 2.5GbE Controller                                     | 3         | 5.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 3         | 5.77%   |
| Intel 82574L Gigabit Network Connection                               | 2         | 3.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                        | 1         | 1.92%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                 | 1         | 1.92%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                | 1         | 1.92%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                 | 1         | 1.92%   |
| Mellanox MT27800 Family [ConnectX-5]                                  | 1         | 1.92%   |
| Intel I211 Gigabit Network Connection                                 | 1         | 1.92%   |
| Intel I210 Gigabit Network Connection                                 | 1         | 1.92%   |
| Intel Ethernet Controller XL710 for 40GbE QSFP+                       | 1         | 1.92%   |
| Intel Ethernet Controller X710 for 10GBASE-T                          | 1         | 1.92%   |
| Intel Ethernet Connection I219-V                                      | 1         | 1.92%   |
| Intel Ethernet Connection I219-LM                                     | 1         | 1.92%   |
| Intel Ethernet Connection I218-V                                      | 1         | 1.92%   |
| Intel Ethernet Connection I218-LM                                     | 1         | 1.92%   |
| Intel Ethernet Connection I217-V                                      | 1         | 1.92%   |
| Intel Ethernet Connection (4) I219-V                                  | 1         | 1.92%   |
| Intel Ethernet Connection (2) I218-V                                  | 1         | 1.92%   |
| Intel 82579V Gigabit Network Connection                               | 1         | 1.92%   |
| IBM RNDIS/CDC ETHER                                                   | 1         | 1.92%   |
| Dell iDRAC Virtual NIC                                                | 1         | 1.92%   |
| Ceton InfiniTV Network                                                | 1         | 1.92%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                     | 1         | 1.92%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                       | 1         | 1.92%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1         | 1.92%   |
| ASIX AX88179 Gigabit Ethernet                                         | 1         | 1.92%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 1         | 1.92%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 40        | 51.28%  |
| WiFi     | 36        | 46.15%  |
| Modem    | 2         | 2.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 23        | 52.27%  |
| WiFi     | 21        | 47.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 31        | 67.39%  |
| 1     | 12        | 26.09%  |
| 3     | 2         | 4.35%   |
| 7     | 1         | 2.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 34        | 73.91%  |
| Yes  | 12        | 26.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 59.38%  |
| Lite-On Technology              | 3         | 9.38%   |
| Realtek Semiconductor           | 2         | 6.25%   |
| Qualcomm Atheros Communications | 2         | 6.25%   |
| Broadcom                        | 2         | 6.25%   |
| MediaTek                        | 1         | 3.13%   |
| IMC Networks                    | 1         | 3.13%   |
| Cambridge Silicon Radio         | 1         | 3.13%   |
| ASUSTek Computer                | 1         | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 25%     |
| Intel Bluetooth Device                              | 4         | 12.5%   |
| Realtek Bluetooth Radio                             | 2         | 6.25%   |
| Lite-On Bluetooth Device                            | 2         | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 6.25%   |
| Intel AX201 Bluetooth                               | 2         | 6.25%   |
| Intel AX200 Bluetooth                               | 2         | 6.25%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 6.25%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 3.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 3.13%   |
| MediaTek Wireless_Device                            | 1         | 3.13%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 3.13%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 3.13%   |
| IMC Networks Bluetooth Device                       | 1         | 3.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.13%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 3.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Intel           | 34        | 54.84%  |
| Nvidia          | 13        | 20.97%  |
| AMD             | 13        | 20.97%  |
| SteelSeries ApS | 2         | 3.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 6.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 5.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 5.56%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 5.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 4.17%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 4.17%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 4.17%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 4.17%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 4.17%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 2.78%   |
| Nvidia TU102 High Definition Audio Controller                              | 2         | 2.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 2.78%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 2.78%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 2.78%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 2.78%   |
| SteelSeries ApS SteelSeries Siberia 800                                    | 1         | 1.39%   |
| SteelSeries ApS SteelSeries GameDAC                                        | 1         | 1.39%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.39%   |
| Nvidia GM200 High Definition Audio                                         | 1         | 1.39%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.39%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.39%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.39%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 1.39%   |
| Nvidia Audio device                                                        | 1         | 1.39%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.39%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.39%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1         | 1.39%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.39%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.39%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.39%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.39%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.39%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 1.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.39%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.39%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 1.39%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1         | 1.39%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 1         | 1.39%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1         | 1.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 30.77%  |
| SK hynix            | 4         | 15.38%  |
| Corsair             | 3         | 11.54%  |
| Kingston            | 2         | 7.69%   |
| G.Skill             | 2         | 7.69%   |
| Crucial             | 2         | 7.69%   |
| Unknown (ABCD)      | 1         | 3.85%   |
| Team                | 1         | 3.85%   |
| Smart Brazil        | 1         | 3.85%   |
| SHARETRONIC         | 1         | 3.85%   |
| A-DATA Technology   | 1         | 3.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 1         | 3.85%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s                | 1         | 3.85%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2667MT/s   | 1         | 3.85%   |
| SK hynix RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 3.85%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s            | 1         | 3.85%   |
| SK hynix RAM HMA84GR7DJR4N-XN 32GB DIMM DDR4 3200MT/s             | 1         | 3.85%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s           | 1         | 3.85%   |
| SHARETRONIC RAM Module 4GB SODIMM DDR3 800MT/s                    | 1         | 3.85%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                       | 1         | 3.85%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s             | 1         | 3.85%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s             | 1         | 3.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s       | 1         | 3.85%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s             | 1         | 3.85%   |
| Samsung RAM M393A4K40EB3-CWE 32GB DIMM DDR4 3200MT/s              | 1         | 3.85%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s               | 1         | 3.85%   |
| Samsung RAM K4UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 3.85%   |
| Kingston RAM 99U5471-034.A00LF 4GB DIMM DDR3 1600MT/s             | 1         | 3.85%   |
| Kingston RAM 9905417-083.A00G 4GB SODIMM DDR3 1600MT/s            | 1         | 3.85%   |
| G.Skill RAM F4-3600C18-32GTZR 32GB DIMM DDR4 3600MT/s             | 1         | 3.85%   |
| G.Skill RAM F3-1600C9-8GRSL 8GB SODIMM DDR3 1600MT/s              | 1         | 3.85%   |
| Crucial RAM CT8G4SFS824A.M8FD 8GB SODIMM DDR4 2400MT/s            | 1         | 3.85%   |
| Crucial RAM CT16G4DFD824A.C16FBD 16GB DIMM DDR4 2933MT/s          | 1         | 3.85%   |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s           | 1         | 3.85%   |
| Corsair RAM CMK64GX4M2Z4000C18 32GB DIMM DDR4 4000MT/s            | 1         | 3.85%   |
| Corsair RAM CMK128GX4M8A2666C16 16GB DIMM DDR4 2133MT/s           | 1         | 3.85%   |
| A-DATA RAM Module 32GB SODIMM DDR4 3200MT/s                       | 1         | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 13        | 54.17%  |
| DDR3   | 9         | 37.5%   |
| LPDDR4 | 2         | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 11        | 45.83%  |
| DIMM         | 11        | 45.83%  |
| Row Of Chips | 2         | 8.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 10        | 40%     |
| 32768 | 5         | 20%     |
| 4096  | 5         | 20%     |
| 16384 | 4         | 16%     |
| 2048  | 1         | 4%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 6         | 25%     |
| 3200  | 5         | 20.83%  |
| 2667  | 2         | 8.33%   |
| 2400  | 2         | 8.33%   |
| 2133  | 2         | 8.33%   |
| 4267  | 1         | 4.17%   |
| 4000  | 1         | 4.17%   |
| 3600  | 1         | 4.17%   |
| 2933  | 1         | 4.17%   |
| 1800  | 1         | 4.17%   |
| 1067  | 1         | 4.17%   |
| 800   | 1         | 4.17%   |

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
| Chicony Electronics                    | 5         | 21.74%  |
| IMC Networks                           | 3         | 13.04%  |
| Syntek                                 | 2         | 8.7%    |
| Sunplus Innovation Technology          | 2         | 8.7%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 8.7%    |
| Bison Electronics                      | 2         | 8.7%    |
| Acer                                   | 2         | 8.7%    |
| Realtek Semiconductor                  | 1         | 4.35%   |
| Microdia                               | 1         | 4.35%   |
| Luxvisions Innotech Limited            | 1         | 4.35%   |
| Logitech                               | 1         | 4.35%   |
| Apple                                  | 1         | 4.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                            | 2         | 8.7%    |
| Sunplus papalook AF 925                             | 2         | 8.7%    |
| Realtek Lenovo EasyCamera                           | 1         | 4.35%   |
| Microdia USB Live camera                            | 1         | 4.35%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 4.35%   |
| Logitech Webcam C270                                | 1         | 4.35%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 4.35%   |
| IMC Networks Integrated RGB Camera                  | 1         | 4.35%   |
| IMC Networks Integrated Camera                      | 1         | 4.35%   |
| Chicony Thinkpad T430 camera                        | 1         | 4.35%   |
| Chicony Integrated Camera                           | 1         | 4.35%   |
| Chicony HD WebCam (Asus N-series)                   | 1         | 4.35%   |
| Chicony HD WebCam                                   | 1         | 4.35%   |
| Chicony Acer CrystalEye Webcam                      | 1         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 4.35%   |
| Bison Lenovo Integrated Webcam                      | 1         | 4.35%   |
| Bison Integrated Camera                             | 1         | 4.35%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 1         | 4.35%   |
| Acer Integrated Camera                              | 1         | 4.35%   |
| Acer HD Webcam                                      | 1         | 4.35%   |

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
| 0     | 30        | 61.22%  |
| 1     | 13        | 26.53%  |
| 2     | 4         | 8.16%   |
| 4     | 1         | 2.04%   |
| 3     | 1         | 2.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 5         | 20.83%  |
| Net/wireless             | 4         | 16.67%  |
| Unassigned class         | 3         | 12.5%   |
| Multimedia controller    | 3         | 12.5%   |
| Fingerprint reader       | 2         | 8.33%   |
| Communication controller | 2         | 8.33%   |
| Storage/ata              | 1         | 4.17%   |
| Storage                  | 1         | 4.17%   |
| Dvb card                 | 1         | 4.17%   |
| Chipcard                 | 1         | 4.17%   |
| Bluetooth                | 1         | 4.17%   |

