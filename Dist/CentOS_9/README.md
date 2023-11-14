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

Total: 67

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | MEG Z790 ACE                | Desktop     | [41d0e4fddd](https://linux-hardware.org/?probe=41d0e4fddd) | Oct 24, 2023 |
| Dell          | Vostro 5402                 | Notebook    | [f23d8804a7](https://linux-hardware.org/?probe=f23d8804a7) | Oct 11, 2023 |
| Dell          | 0HJK12 A03                  | Server      | [b4ec3650ef](https://linux-hardware.org/?probe=b4ec3650ef) | Sep 11, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [ecf1a70c5d](https://linux-hardware.org/?probe=ecf1a70c5d) | Sep 08, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [149cb27e46](https://linux-hardware.org/?probe=149cb27e46) | Aug 18, 2023 |
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

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.14.0-86.el9.x86_64           | 3         | 5.45%   |
| 5.14.0-202.el9.x86_64          | 3         | 5.45%   |
| 5.14.0-134.el9.x86_64          | 3         | 5.45%   |
| 5.14.0-362.el9.x86_64          | 2         | 3.64%   |
| 5.14.0-325.el9.x86_64          | 2         | 3.64%   |
| 5.14.0-319.el9.x86_64          | 2         | 3.64%   |
| 5.14.0-214.el9.x86_64          | 2         | 3.64%   |
| 5.14.0-183.el9.x86_64          | 2         | 3.64%   |
| 5.14.0-171.el9.x86_64          | 2         | 3.64%   |
| 5.14.0-148.el9.x86_64          | 2         | 3.64%   |
| 6.1.8-1.el9.elrepo.x86_64      | 1         | 1.82%   |
| 6.1.1                          | 1         | 1.82%   |
| 5.17.2-lqx3.0.el9.x86_64       | 1         | 1.82%   |
| 5.14.0-78.el9.x86_64           | 1         | 1.82%   |
| 5.14.0-71.el9.x86_64           | 1         | 1.82%   |
| 5.14.0-66.el9.x86_64           | 1         | 1.82%   |
| 5.14.0-52.el9.x86_64           | 1         | 1.82%   |
| 5.14.0-44.el9.x86_64           | 1         | 1.82%   |
| 5.14.0-375.el9.x86_64          | 1         | 1.82%   |
| 5.14.0-373.el9.x86_64          | 1         | 1.82%   |
| 5.14.0-352.el9.x86_64          | 1         | 1.82%   |
| 5.14.0-350.el9.x86_64          | 1         | 1.82%   |
| 5.14.0-344.el9.x86_64          | 1         | 1.82%   |
| 5.14.0-340.el9.x86_64          | 1         | 1.82%   |
| 5.14.0-333.el9.x86_64          | 1         | 1.82%   |
| 5.14.0-316.el9.x86_64          | 1         | 1.82%   |
| 5.14.0-305.el9.x86_64          | 1         | 1.82%   |
| 5.14.0-302.el9.x86_64          | 1         | 1.82%   |
| 5.14.0-299.el9.x86_64          | 1         | 1.82%   |
| 5.14.0-289.el9.x86_64          | 1         | 1.82%   |
| 5.14.0-283.el9.x86_64          | 1         | 1.82%   |
| 5.14.0-282.el9.x86_64          | 1         | 1.82%   |
| 5.14.0-267.el9.x86_64          | 1         | 1.82%   |
| 5.14.0-226.el9.x86_64          | 1         | 1.82%   |
| 5.14.0-200.el9.x86_64          | 1         | 1.82%   |
| 5.14.0-163.el9.x86_64          | 1         | 1.82%   |
| 5.14.0-130.rt21.130.el9.x86_64 | 1         | 1.82%   |
| 5.14.0-130.el9.x86_64          | 1         | 1.82%   |
| 5.14.0-12.el9.x86_64           | 1         | 1.82%   |
| 5.14.0-115.el9.x86_64          | 1         | 1.82%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 47        | 94%     |
| 6.1.8   | 1         | 2%      |
| 6.1.1   | 1         | 2%      |
| 5.17.2  | 1         | 2%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 47        | 94%     |
| 6.1     | 2         | 4%      |
| 5.17    | 1         | 2%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 49        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 41        | 83.67%  |
| KDE5          | 3         | 6.12%   |
| GNOME Classic | 3         | 6.12%   |
| Unknown       | 2         | 4.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 32        | 64%     |
| X11     | 16        | 32%     |
| Tty     | 2         | 4%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 27        | 54%     |
| GDM     | 20        | 40%     |
| SDDM    | 2         | 4%      |
| LightDM | 1         | 2%      |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 31        | 63.27%  |
| de_DE | 3         | 6.12%   |
| zh_CN | 2         | 4.08%   |
| ru_RU | 2         | 4.08%   |
| ja_JP | 2         | 4.08%   |
| it_IT | 2         | 4.08%   |
| sv_SE | 1         | 2.04%   |
| ru_UA | 1         | 2.04%   |
| pt_BR | 1         | 2.04%   |
| fr_FR | 1         | 2.04%   |
| en_IN | 1         | 2.04%   |
| en_GB | 1         | 2.04%   |
| en_AU | 1         | 2.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 36        | 73.47%  |
| BIOS | 13        | 26.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 45        | 91.84%  |
| Ext4 | 4         | 8.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 25        | 49.02%  |
| GPT     | 19        | 37.25%  |
| MBR     | 7         | 13.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 88%     |
| Yes       | 6         | 12%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 74.51%  |
| Yes       | 13        | 25.49%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 10        | 20.41%  |
| ASUSTek Computer    | 10        | 20.41%  |
| Intel               | 4         | 8.16%   |
| Dell                | 4         | 8.16%   |
| Acer                | 4         | 8.16%   |
| MSI                 | 3         | 6.12%   |
| Hewlett-Packard     | 3         | 6.12%   |
| Timi                | 2         | 4.08%   |
| Gigabyte Technology | 2         | 4.08%   |
| Zvezda              | 1         | 2.04%   |
| Razer               | 1         | 2.04%   |
| IP3 Tech            | 1         | 2.04%   |
| IBM                 | 1         | 2.04%   |
| Gateway             | 1         | 2.04%   |
| Colorful Technology | 1         | 2.04%   |
| AZW                 | 1         | 2.04%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUS PRIME H670-PLUS D4              | 2         | 4.08%   |
| Zvezda Altair Z                      | 1         | 2.04%   |
| Timi RedmiBook 16                    | 1         | 2.04%   |
| Timi Mi NoteBook Horizon Edition 14  | 1         | 2.04%   |
| Razer Blade 15 (2022) - RZ09-0421    | 1         | 2.04%   |
| MSI MS-7D86                          | 1         | 2.04%   |
| MSI MS-7B79                          | 1         | 2.04%   |
| MSI Katana GF76 12UE                 | 1         | 2.04%   |
| Lenovo Yoga S740-14IIL 81RS          | 1         | 2.04%   |
| Lenovo V15 G2 ITL 82KB               | 1         | 2.04%   |
| Lenovo ThinkPad T460s 20FAS5WX00     | 1         | 2.04%   |
| Lenovo ThinkPad T430 2349DG5         | 1         | 2.04%   |
| Lenovo ThinkPad T430 2347DE9         | 1         | 2.04%   |
| Lenovo ThinkPad L14 Gen 1 20U5S0NT00 | 1         | 2.04%   |
| Lenovo Legion 5P 15IMH05H 82AW       | 1         | 2.04%   |
| Lenovo IdeaPad S145-15IWL 81S9       | 1         | 2.04%   |
| Lenovo G580 20150                    | 1         | 2.04%   |
| Lenovo G410 20237                    | 1         | 2.04%   |
| IP3 Tech HeroBox                     | 1         | 2.04%   |
| Intel NUC7i3BNK                      | 1         | 2.04%   |
| Intel NUC12WSHi7                     | 1         | 2.04%   |
| Intel NUC12WSHi5                     | 1         | 2.04%   |
| Intel D34010WYK H14771-303           | 1         | 2.04%   |
| IBM System x3250 M3 -[425242G]       | 1         | 2.04%   |
| HP Pavilion Gaming Laptop 15-ec0xxx  | 1         | 2.04%   |
| HP EliteBook 840 G3                  | 1         | 2.04%   |
| HP EliteBook 840 G1                  | 1         | 2.04%   |
| Gigabyte X99-UD4-CF                  | 1         | 2.04%   |
| Gigabyte 970A-DS3P                   | 1         | 2.04%   |
| Gateway SX2865                       | 1         | 2.04%   |
| Dell Vostro 5402                     | 1         | 2.04%   |
| Dell PowerEdge T640                  | 1         | 2.04%   |
| Dell PowerEdge R720                  | 1         | 2.04%   |
| Dell OptiPlex 790                    | 1         | 2.04%   |
| Colorful CVN Z590 GAMING PRO         | 1         | 2.04%   |
| AZW SER                              | 1         | 2.04%   |
| ASUS TUF Gaming X570-PLUS            | 1         | 2.04%   |
| ASUS ROG STRIX B560-G GAMING WIFI    | 1         | 2.04%   |
| ASUS ROG CROSSHAIR VIII DARK HERO    | 1         | 2.04%   |
| ASUS Q550LF                          | 1         | 2.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 4         | 8.16%   |
| HP EliteBook        | 2         | 4.08%   |
| Dell PowerEdge      | 2         | 4.08%   |
| ASUS ROG            | 2         | 4.08%   |
| ASUS PRIME          | 2         | 4.08%   |
| Acer Aspire         | 2         | 4.08%   |
| Zvezda Altair       | 1         | 2.04%   |
| Timi RedmiBook      | 1         | 2.04%   |
| Timi Mi             | 1         | 2.04%   |
| Razer Blade         | 1         | 2.04%   |
| MSI MS-7D86         | 1         | 2.04%   |
| MSI MS-7B79         | 1         | 2.04%   |
| MSI Katana          | 1         | 2.04%   |
| Lenovo Yoga         | 1         | 2.04%   |
| Lenovo V15          | 1         | 2.04%   |
| Lenovo Legion       | 1         | 2.04%   |
| Lenovo IdeaPad      | 1         | 2.04%   |
| Lenovo G580         | 1         | 2.04%   |
| Lenovo G410         | 1         | 2.04%   |
| IP3 Tech HeroBox    | 1         | 2.04%   |
| Intel NUC7i3BNK     | 1         | 2.04%   |
| Intel NUC12WSHi7    | 1         | 2.04%   |
| Intel NUC12WSHi5    | 1         | 2.04%   |
| Intel D34010WYK     | 1         | 2.04%   |
| IBM System          | 1         | 2.04%   |
| HP Pavilion         | 1         | 2.04%   |
| Gigabyte X99-UD4-CF | 1         | 2.04%   |
| Gigabyte 970A-DS3P  | 1         | 2.04%   |
| Gateway SX2865      | 1         | 2.04%   |
| Dell Vostro         | 1         | 2.04%   |
| Dell OptiPlex       | 1         | 2.04%   |
| Colorful CVN        | 1         | 2.04%   |
| AZW SER             | 1         | 2.04%   |
| ASUS TUF            | 1         | 2.04%   |
| ASUS Q550LF         | 1         | 2.04%   |
| ASUS P8H67-M        | 1         | 2.04%   |
| ASUS P8H61          | 1         | 2.04%   |
| ASUS N751JK         | 1         | 2.04%   |
| ASUS All            | 1         | 2.04%   |
| Acer Swift          | 1         | 2.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 9         | 18.37%  |
| 2021 | 7         | 14.29%  |
| 2020 | 6         | 12.24%  |
| 2022 | 5         | 10.2%   |
| 2019 | 5         | 10.2%   |
| 2012 | 4         | 8.16%   |
| 2011 | 3         | 6.12%   |
| 2023 | 2         | 4.08%   |
| 2018 | 2         | 4.08%   |
| 2016 | 2         | 4.08%   |
| 2014 | 2         | 4.08%   |
| 2010 | 1         | 2.04%   |
| 2009 | 1         | 2.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 23        | 46.94%  |
| Desktop  | 17        | 34.69%  |
| Mini pc  | 5         | 10.2%   |
| Server   | 4         | 8.16%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 45        | 91.84%  |
| Enabled  | 4         | 8.16%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 49        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 18        | 36.73%  |
| 8.01-16.0       | 11        | 22.45%  |
| 32.01-64.0      | 7         | 14.29%  |
| 64.01-256.0     | 6         | 12.24%  |
| More than 256.0 | 2         | 4.08%   |
| 3.01-4.0        | 2         | 4.08%   |
| 16.01-24.0      | 2         | 4.08%   |
| 24.01-32.0      | 1         | 2.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 21        | 40.38%  |
| 3.01-4.0   | 10        | 19.23%  |
| 4.01-8.0   | 9         | 17.31%  |
| 1.01-2.0   | 4         | 7.69%   |
| 8.01-16.0  | 4         | 7.69%   |
| 16.01-24.0 | 2         | 3.85%   |
| 0.51-1.0   | 2         | 3.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 23        | 46.94%  |
| 2      | 12        | 24.49%  |
| 4      | 6         | 12.24%  |
| 3      | 5         | 10.2%   |
| 5      | 2         | 4.08%   |
| 10     | 1         | 2.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 77.55%  |
| Yes       | 11        | 22.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 89.8%   |
| No        | 5         | 10.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 77.55%  |
| No        | 11        | 22.45%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 69.39%  |
| No        | 15        | 30.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 9         | 18.37%  |
| Germany      | 6         | 12.24%  |
| Italy        | 3         | 6.12%   |
| China        | 3         | 6.12%   |
| Bulgaria     | 3         | 6.12%   |
| Ukraine      | 2         | 4.08%   |
| Poland       | 2         | 4.08%   |
| Japan        | 2         | 4.08%   |
| Canada       | 2         | 4.08%   |
| Uzbekistan   | 1         | 2.04%   |
| Switzerland  | 1         | 2.04%   |
| Sweden       | 1         | 2.04%   |
| South Africa | 1         | 2.04%   |
| Russia       | 1         | 2.04%   |
| Puerto Rico  | 1         | 2.04%   |
| Netherlands  | 1         | 2.04%   |
| Myanmar      | 1         | 2.04%   |
| Kazakhstan   | 1         | 2.04%   |
| India        | 1         | 2.04%   |
| France       | 1         | 2.04%   |
| Finland      | 1         | 2.04%   |
| Colombia     | 1         | 2.04%   |
| Chile        | 1         | 2.04%   |
| Brazil       | 1         | 2.04%   |
| Belarus      | 1         | 2.04%   |
| Australia    | 1         | 2.04%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Sofia             | 2         | 3.85%   |
| Bristow           | 2         | 3.85%   |
| Beijing           | 2         | 3.85%   |
| Yangon            | 1         | 1.92%   |
| Wuhan             | 1         | 1.92%   |
| Vitebsk           | 1         | 1.92%   |
| Vicenza           | 1         | 1.92%   |
| Tomah             | 1         | 1.92%   |
| Tashkent          | 1         | 1.92%   |
| Stromberg         | 1         | 1.92%   |
| Stockholm         | 1         | 1.92%   |
| Soest             | 1         | 1.92%   |
| Schemmerhofen     | 1         | 1.92%   |
| San Juan          | 1         | 1.92%   |
| Ruda Śląska     | 1         | 1.92%   |
| Rome              | 1         | 1.92%   |
| Ribeirao Preto    | 1         | 1.92%   |
| Quitman           | 1         | 1.92%   |
| Puente Alto       | 1         | 1.92%   |
| Portland          | 1         | 1.92%   |
| Perth             | 1         | 1.92%   |
| Persan            | 1         | 1.92%   |
| Ozarow Mazowiecki | 1         | 1.92%   |
| Okazaki           | 1         | 1.92%   |
| New York          | 1         | 1.92%   |
| New Cumberland    | 1         | 1.92%   |
| Navapolatsk       | 1         | 1.92%   |
| Nagoya            | 1         | 1.92%   |
| Mumbai            | 1         | 1.92%   |
| Moscow            | 1         | 1.92%   |
| Milpitas          | 1         | 1.92%   |
| Michelstadt       | 1         | 1.92%   |
| Meieki            | 1         | 1.92%   |
| L'Isle-Adam       | 1         | 1.92%   |
| Kyiv              | 1         | 1.92%   |
| Kramatorsk        | 1         | 1.92%   |
| Helsinki          | 1         | 1.92%   |
| Hamburg           | 1         | 1.92%   |
| Durban            | 1         | 1.92%   |
| Dortmund          | 1         | 1.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 13        | 19     | 16.25%  |
| WDC                       | 11        | 16     | 13.75%  |
| Seagate                   | 9         | 13     | 11.25%  |
| Kingston                  | 8         | 11     | 10%     |
| Toshiba                   | 4         | 6      | 5%      |
| Sandisk                   | 4         | 10     | 5%      |
| SK hynix                  | 3         | 3      | 3.75%   |
| Intel                     | 3         | 3      | 3.75%   |
| HGST                      | 3         | 4      | 3.75%   |
| Micron Technology         | 2         | 2      | 2.5%    |
| Crucial                   | 2         | 8      | 2.5%    |
| WD MediaMax               | 1         | 1      | 1.25%   |
| Unknown                   | 1         | 1      | 1.25%   |
| Union Memory              | 1         | 1      | 1.25%   |
| Team                      | 1         | 2      | 1.25%   |
| Plextor                   | 1         | 1      | 1.25%   |
| Phison Electronics        | 1         | 1      | 1.25%   |
| Phison                    | 1         | 1      | 1.25%   |
| OCZ                       | 1         | 1      | 1.25%   |
| Netac                     | 1         | 2      | 1.25%   |
| Micron/Crucial Technology | 1         | 1      | 1.25%   |
| LITEON                    | 1         | 1      | 1.25%   |
| Intenso                   | 1         | 1      | 1.25%   |
| Hjwdz                     | 1         | 1      | 1.25%   |
| Hitachi                   | 1         | 1      | 1.25%   |
| Hewlett-Packard           | 1         | 1      | 1.25%   |
| Gigabyte Technology       | 1         | 2      | 1.25%   |
| ASMT                      | 1         | 1      | 1.25%   |
| A-DATA Technology         | 1         | 1      | 1.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Sandisk WD_BLACK SN770 1TB                        | 2         | 2.3%    |
| SanDisk SDSSDH3 1T00 1TB                          | 2         | 2.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2         | 2.3%    |
| Samsung MZNLH512HALU-00000 512GB SSD              | 2         | 2.3%    |
| Micron 2450_MTFDKBA512TFK 512GB                   | 2         | 2.3%    |
| Crucial CT525MX300SSD1 528GB                      | 2         | 2.3%    |
| WDC WDS250G2B0A-00SM50 250GB SSD                  | 1         | 1.15%   |
| WDC WD6400BEVT-22A0RT0 640GB                      | 1         | 1.15%   |
| WDC WD6003FZBX-00K5WB0 6TB                        | 1         | 1.15%   |
| WDC WD5000LPLX-60ZNTT1 500GB                      | 1         | 1.15%   |
| WDC WD5000BEVT-55A0RT0 500GB                      | 1         | 1.15%   |
| WDC WD3200AAKX-753CA1 320GB                       | 1         | 1.15%   |
| WDC WD2500AAJS-60M0A0 250GB                       | 1         | 1.15%   |
| WDC WD22EJRX-89BEMY0 2TB                          | 1         | 1.15%   |
| WDC WD2003FZEX-00Z4SA0 2TB                        | 1         | 1.15%   |
| WDC WD10EZEX-60M2NA0 1TB                          | 1         | 1.15%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 1         | 1.15%   |
| WDC WD10EZEX-00BN5A0 1TB                          | 1         | 1.15%   |
| WD MediaMax WL750GSA6472 752GB                    | 1         | 1.15%   |
| Unknown MMC Card  7GB                             | 1         | 1.15%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB           | 1         | 1.15%   |
| Toshiba MQ04ABF100 1TB                            | 1         | 1.15%   |
| Toshiba MK2561GSYN 250GB                          | 1         | 1.15%   |
| Toshiba DT01ACA100 1TB                            | 1         | 1.15%   |
| Toshiba AL15SEB24EQY 2TB                          | 1         | 1.15%   |
| Toshiba AL15SEB24EQY 2.4TB                        | 1         | 1.15%   |
| Team T253X1480G 480GB SSD                         | 1         | 1.15%   |
| SK hynix NVMe SSD Drive 256GB                     | 1         | 1.15%   |
| SK hynix BC511 512GB                              | 1         | 1.15%   |
| SK hynix BC501 NVMe 256GB                         | 1         | 1.15%   |
| Seagate ST600MM0088 600GB                         | 1         | 1.15%   |
| Seagate ST500LT012-9WS142 500GB                   | 1         | 1.15%   |
| Seagate ST3500413AS 500GB                         | 1         | 1.15%   |
| Seagate ST3250820AS 250GB                         | 1         | 1.15%   |
| Seagate ST2000DL003-9VT166 2TB                    | 1         | 1.15%   |
| Seagate ST1000LM035-1RK172 1TB                    | 1         | 1.15%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 1         | 1.15%   |
| Seagate ST1000DM010-2EP102 1TB                    | 1         | 1.15%   |
| Seagate FireCuda 520 SSD ZP2000GM30002 2TB        | 1         | 1.15%   |
| Seagate FireCuda 520 SSD ZP1000GM30002 1TB        | 1         | 1.15%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor      | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| WDC         | 10        | 15     | 37.04%  |
| Seagate     | 8         | 11     | 29.63%  |
| Toshiba     | 4         | 5      | 14.81%  |
| HGST        | 3         | 4      | 11.11%  |
| WD MediaMax | 1         | 1      | 3.7%    |
| Hitachi     | 1         | 1      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 14     | 28.13%  |
| Kingston            | 6         | 9      | 18.75%  |
| SanDisk             | 3         | 5      | 9.38%   |
| Crucial             | 2         | 8      | 6.25%   |
| WDC                 | 1         | 1      | 3.13%   |
| Team                | 1         | 2      | 3.13%   |
| Plextor             | 1         | 1      | 3.13%   |
| OCZ                 | 1         | 1      | 3.13%   |
| Netac               | 1         | 2      | 3.13%   |
| LITEON              | 1         | 1      | 3.13%   |
| Intenso             | 1         | 1      | 3.13%   |
| Intel               | 1         | 1      | 3.13%   |
| Hewlett-Packard     | 1         | 1      | 3.13%   |
| Gigabyte Technology | 1         | 2      | 3.13%   |
| ASMT                | 1         | 1      | 3.13%   |
| A-DATA Technology   | 1         | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 26        | 51     | 37.14%  |
| HDD     | 21        | 37     | 30%     |
| NVMe    | 20        | 25     | 28.57%  |
| Unknown | 2         | 2      | 2.86%   |
| MMC     | 1         | 1      | 1.43%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 37        | 85     | 59.68%  |
| NVMe | 20        | 25     | 32.26%  |
| SAS  | 4         | 5      | 6.45%   |
| MMC  | 1         | 1      | 1.61%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 24        | 38     | 48.98%  |
| 0.51-1.0   | 18        | 38     | 36.73%  |
| 1.01-2.0   | 5         | 9      | 10.2%   |
| 2.01-3.0   | 1         | 1      | 2.04%   |
| 4.01-10.0  | 1         | 2      | 2.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 16        | 31.37%  |
| 251-500        | 10        | 19.61%  |
| 1001-2000      | 10        | 19.61%  |
| 501-1000       | 6         | 11.76%  |
| 2001-3000      | 4         | 7.84%   |
| More than 3000 | 2         | 3.92%   |
| 51-100         | 2         | 3.92%   |
| 21-50          | 1         | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 22        | 44%     |
| 51-100         | 6         | 12%     |
| 251-500        | 5         | 10%     |
| 21-50          | 5         | 10%     |
| 101-250        | 5         | 10%     |
| 501-1000       | 3         | 6%      |
| 1001-2000      | 2         | 4%      |
| More than 3000 | 1         | 2%      |
| 2001-3000      | 1         | 2%      |

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
| Detected | 31        | 64     | 54.39%  |
| Works    | 22        | 47     | 38.6%   |
| Malfunc  | 4         | 5      | 7.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 39        | 55.71%  |
| AMD                         | 6         | 8.57%   |
| Samsung Electronics         | 4         | 5.71%   |
| SK hynix                    | 3         | 4.29%   |
| SanDisk                     | 3         | 4.29%   |
| LSI Logic / Symbios Logic   | 3         | 4.29%   |
| Phison Electronics          | 2         | 2.86%   |
| Micron Technology           | 2         | 2.86%   |
| Kingston Technology Company | 2         | 2.86%   |
| Union Memory (Shenzhen)     | 1         | 1.43%   |
| Silicon Image               | 1         | 1.43%   |
| Seagate Technology          | 1         | 1.43%   |
| Micron/Crucial Technology   | 1         | 1.43%   |
| Broadcom / LSI              | 1         | 1.43%   |
| ASMedia Technology          | 1         | 1.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 5         | 6.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 5.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 5.26%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 3.95%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 3         | 3.95%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 3.95%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 2         | 2.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 2.63%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2         | 2.63%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 2.63%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 2.63%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 2         | 2.63%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2         | 2.63%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 2.63%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                          | 1         | 1.32%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 1.32%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 1.32%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 1.32%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1         | 1.32%   |
| Seagate FireCuda 520/IronWolf 525 SSD                                          | 1         | 1.32%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 1         | 1.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.32%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 1.32%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.32%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 1.32%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                 | 1         | 1.32%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                        | 1         | 1.32%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2208 [Thunderbolt]                      | 1         | 1.32%   |
| Kingston Company NV1 NVMe SSD SM2263XT                                         | 1         | 1.32%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                             | 1         | 1.32%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.32%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1         | 1.32%   |
| Intel SSD 660P Series                                                          | 1         | 1.32%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 1.32%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.32%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.32%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.32%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                   | 1         | 1.32%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 1         | 1.32%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 41        | 59.42%  |
| NVMe | 20        | 28.99%  |
| RAID | 6         | 8.7%    |
| SCSI | 1         | 1.45%   |
| IDE  | 1         | 1.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 41        | 83.67%  |
| AMD    | 8         | 16.33%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-1260P            | 2         | 4.08%   |
| Intel 12th Gen Core i5-12600K           | 2         | 4.08%   |
| Intel Xeon Silver 4215R CPU @ 3.20GHz   | 1         | 2.04%   |
| Intel Xeon Gold 6326 CPU @ 2.90GHz      | 1         | 2.04%   |
| Intel Xeon CPU X3440 @ 2.53GHz          | 1         | 2.04%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz      | 1         | 2.04%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 2.04%   |
| Intel Core i7-5930K CPU @ 3.50GHz       | 1         | 2.04%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 1         | 2.04%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 1         | 2.04%   |
| Intel Core i7-2600K CPU @ 3.40GHz       | 1         | 2.04%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 2.04%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 1         | 2.04%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 1         | 2.04%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 1         | 2.04%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 1         | 2.04%   |
| Intel Core i5-4440 CPU @ 3.10GHz        | 1         | 2.04%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 1         | 2.04%   |
| Intel Core i5-4200M CPU @ 2.50GHz       | 1         | 2.04%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 1         | 2.04%   |
| Intel Core i5-3380M CPU @ 2.90GHz       | 1         | 2.04%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 2.04%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 1         | 2.04%   |
| Intel Core i5-2400S CPU @ 2.50GHz       | 1         | 2.04%   |
| Intel Core i5-10400F CPU @ 2.90GHz      | 1         | 2.04%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 1         | 2.04%   |
| Intel Core i5 CPU M 430 @ 2.27GHz       | 1         | 2.04%   |
| Intel Core i3-7100U CPU @ 2.40GHz       | 1         | 2.04%   |
| Intel Core i3-4010U CPU @ 1.70GHz       | 1         | 2.04%   |
| Intel Core i3-3217U CPU @ 1.80GHz       | 1         | 2.04%   |
| Intel Core i3-2130 CPU @ 3.40GHz        | 1         | 2.04%   |
| Intel Celeron J4125 CPU @ 2.00GHz       | 1         | 2.04%   |
| Intel 13th Gen Core i9-13900K           | 1         | 2.04%   |
| Intel 12th Gen Core i7-12800H           | 1         | 2.04%   |
| Intel 12th Gen Core i7-12700H           | 1         | 2.04%   |
| Intel 12th Gen Core i5-1240P            | 1         | 2.04%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 1         | 2.04%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz  | 1         | 2.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 1         | 2.04%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 1         | 2.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 14        | 28.57%  |
| Other             | 11        | 22.45%  |
| Intel Core i7     | 7         | 14.29%  |
| Intel Core i3     | 4         | 8.16%   |
| AMD Ryzen 5       | 3         | 6.12%   |
| Intel Xeon        | 2         | 4.08%   |
| AMD Ryzen 9       | 2         | 4.08%   |
| Intel Xeon Silver | 1         | 2.04%   |
| Intel Xeon Gold   | 1         | 2.04%   |
| Intel Celeron     | 1         | 2.04%   |
| AMD Ryzen 7       | 1         | 2.04%   |
| AMD Ryzen 3 PRO   | 1         | 2.04%   |
| AMD FX            | 1         | 2.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 16        | 32.65%  |
| 2      | 13        | 26.53%  |
| 6      | 6         | 12.24%  |
| 16     | 4         | 8.16%   |
| 12     | 3         | 6.12%   |
| 14     | 2         | 4.08%   |
| 10     | 2         | 4.08%   |
| 32     | 1         | 2.04%   |
| 24     | 1         | 2.04%   |
| 8      | 1         | 2.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 46        | 93.88%  |
| 2      | 3         | 6.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 39        | 79.59%  |
| 1      | 10        | 20.41%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 49        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 26.53%  |
| 0x906a3    | 5         | 10.2%   |
| 0x306c3    | 4         | 8.16%   |
| 0x306a9    | 4         | 8.16%   |
| 0x40651    | 3         | 6.12%   |
| 0x806ec    | 2         | 4.08%   |
| 0x406e3    | 2         | 4.08%   |
| 0x08600106 | 2         | 4.08%   |
| 0xa0671    | 1         | 2.04%   |
| 0xa0653    | 1         | 2.04%   |
| 0xa0652    | 1         | 2.04%   |
| 0x90672    | 1         | 2.04%   |
| 0x706e5    | 1         | 2.04%   |
| 0x706a8    | 1         | 2.04%   |
| 0x606a6    | 1         | 2.04%   |
| 0x306f2    | 1         | 2.04%   |
| 0x206a7    | 1         | 2.04%   |
| 0x20652    | 1         | 2.04%   |
| 0x0a201016 | 1         | 2.04%   |
| 0x08701021 | 1         | 2.04%   |
| 0x08701013 | 1         | 2.04%   |
| 0x0600063d | 1         | 2.04%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 8         | 16.33%  |
| Alderlake Hybrid | 8         | 16.33%  |
| Zen 2            | 5         | 10.2%   |
| IvyBridge        | 5         | 10.2%   |
| SandyBridge      | 4         | 8.16%   |
| Skylake          | 3         | 6.12%   |
| KabyLake         | 3         | 6.12%   |
| Icelake          | 3         | 6.12%   |
| TigerLake        | 2         | 4.08%   |
| CometLake        | 2         | 4.08%   |
| Zen+             | 1         | 2.04%   |
| Zen 3            | 1         | 2.04%   |
| Westmere         | 1         | 2.04%   |
| Nehalem          | 1         | 2.04%   |
| Goldmont plus    | 1         | 2.04%   |
| Bulldozer        | 1         | 2.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 27        | 42.86%  |
| Nvidia                     | 21        | 33.33%  |
| AMD                        | 11        | 17.46%  |
| Matrox Electronics Systems | 3         | 4.76%   |
| ASPEED Technology          | 1         | 1.59%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 4         | 6.15%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 6.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 4.62%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 3         | 4.62%   |
| Nvidia TU117 [GeForce GTX 1650]                                           | 2         | 3.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 3.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 3.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 2         | 3.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 3.08%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 1.54%   |
| Nvidia TU116 [GeForce GTX 1660]                                           | 1         | 1.54%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 1         | 1.54%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 1.54%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                        | 1         | 1.54%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                 | 1         | 1.54%   |
| Nvidia GP108M [GeForce MX330]                                             | 1         | 1.54%   |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 1.54%   |
| Nvidia GP108 [GeForce GT 1030]                                            | 1         | 1.54%   |
| Nvidia GP107M [GeForce MX350]                                             | 1         | 1.54%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                         | 1         | 1.54%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 1.54%   |
| Nvidia GM107M [GeForce GTX 850M]                                          | 1         | 1.54%   |
| Nvidia GM107 [GeForce GTX 745]                                            | 1         | 1.54%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 1         | 1.54%   |
| Nvidia GK208B [GeForce GT 730]                                            | 1         | 1.54%   |
| Nvidia GK107M [GeForce GT 745M]                                           | 1         | 1.54%   |
| Nvidia GF108M [NVS 5400M]                                                 | 1         | 1.54%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 1.54%   |
| Nvidia GA103M [GeForce RTX 3080 Ti Mobile]                                | 1         | 1.54%   |
| Matrox Electronics Systems MGA G200EV                                     | 1         | 1.54%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller  | 1         | 1.54%   |
| Matrox Electronics Systems G200eR2                                        | 1         | 1.54%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 1.54%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                 | 1         | 1.54%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                | 1         | 1.54%   |
| Intel Iris Plus Graphics G7                                               | 1         | 1.54%   |
| Intel HD Graphics 620                                                     | 1         | 1.54%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 1.54%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 1.54%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 1         | 1.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 15        | 30.61%  |
| Intel + Nvidia  | 10        | 20.41%  |
| 1 x Nvidia      | 9         | 18.37%  |
| 1 x AMD         | 8         | 16.33%  |
| 1 x Matrox      | 2         | 4.08%   |
| 2 x AMD         | 1         | 2.04%   |
| Nvidia + Matrox | 1         | 2.04%   |
| Intel + AMD     | 1         | 2.04%   |
| 1 x ASPEED      | 1         | 2.04%   |
| AMD + Nvidia    | 1         | 2.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 39        | 78%     |
| Proprietary | 9         | 18%     |
| Unknown     | 2         | 4%      |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 50%     |
| 1.01-2.0   | 7         | 13.46%  |
| 5.01-6.0   | 4         | 7.69%   |
| 3.01-4.0   | 4         | 7.69%   |
| 0.51-1.0   | 4         | 7.69%   |
| 0.01-0.5   | 4         | 7.69%   |
| 8.01-16.0  | 3         | 5.77%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 13.46%  |
| LG Display          | 7         | 13.46%  |
| Chimei Innolux      | 5         | 9.62%   |
| Dell                | 4         | 7.69%   |
| AU Optronics        | 4         | 7.69%   |
| ViewSonic           | 3         | 5.77%   |
| Goldstar            | 3         | 5.77%   |
| Iiyama              | 2         | 3.85%   |
| Hewlett-Packard     | 2         | 3.85%   |
| BOE                 | 2         | 3.85%   |
| Acer                | 2         | 3.85%   |
| TMX                 | 1         | 1.92%   |
| SKY                 | 1         | 1.92%   |
| PANDA               | 1         | 1.92%   |
| NXG                 | 1         | 1.92%   |
| LG Electronics      | 1         | 1.92%   |
| KVM                 | 1         | 1.92%   |
| Gigabyte Technology | 1         | 1.92%   |
| Eizo                | 1         | 1.92%   |
| CHD                 | 1         | 1.92%   |
| BenQ                | 1         | 1.92%   |
| AOC                 | 1         | 1.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Iiyama PL2888H IVM7106 1920x1080 621x341mm 27.9-inch                    | 2         | 3.57%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch           | 1         | 1.79%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch           | 1         | 1.79%   |
| ViewSonic PJ402D-2 HCD7B1D 1280x960                                     | 1         | 1.79%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch                 | 1         | 1.79%   |
| SKY 22X1-M225F SKY2150 1920x1080 476x268mm 21.5-inch                    | 1         | 1.79%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 607x345mm 27.5-inch       | 1         | 1.79%   |
| Samsung Electronics SyncMaster SAM05EB 1920x1080 597x336mm 27.0-inch    | 1         | 1.79%   |
| Samsung Electronics SMT22A350 SAM07A7 1920x1080 477x268mm 21.5-inch     | 1         | 1.79%   |
| Samsung Electronics SMEX2220 SAM0686 1920x1080 477x268mm 21.5-inch      | 1         | 1.79%   |
| Samsung Electronics S27C450 SAM09D9 1920x1080 598x336mm 27.0-inch       | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch   | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1         | 1.79%   |
| PANDA LCD Monitor NCP0052 1920x1080 309x174mm 14.0-inch                 | 1         | 1.79%   |
| NXG MIRAI DML-517 NXG138B 1280x1024 338x270mm 17.0-inch                 | 1         | 1.79%   |
| LG Electronics LCD Monitor LG FULL HD                                   | 1         | 1.79%   |
| LG Display LCD Monitor LGD068A 1920x1080 309x174mm 14.0-inch            | 1         | 1.79%   |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch            | 1         | 1.79%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch            | 1         | 1.79%   |
| LG Display LCD Monitor LGD046C 1920x1080 380x210mm 17.1-inch            | 1         | 1.79%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch             | 1         | 1.79%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch             | 1         | 1.79%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch             | 1         | 1.79%   |
| KVM LCD Monitor 1 1 9" KVM4308 1280x1024 338x270mm 17.0-inch            | 1         | 1.79%   |
| Hewlett-Packard L185x HWP298C 1366x768 410x230mm 18.5-inch              | 1         | 1.79%   |
| Hewlett-Packard 2159 HWP282C 1920x1080 479x269mm 21.6-inch              | 1         | 1.79%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                    | 1         | 1.79%   |
| Goldstar 27GL650F GSM5B70 1920x1080 531x298mm 24.0-inch                 | 1         | 1.79%   |
| Goldstar 22EA53 GSM59A6 1920x1080 477x268mm 21.5-inch                   | 1         | 1.79%   |
| Gigabyte Technology G34WQC A GBT3403 3440x1440 797x334mm 34.0-inch      | 1         | 1.79%   |
| Eizo EV2450 ENC2532 1920x1080 528x297mm 23.9-inch                       | 1         | 1.79%   |
| Dell U2720Q DEL41B0 3840x2160 597x336mm 27.0-inch                       | 1         | 1.79%   |
| Dell U2718Q DELA0E9 3840x2160 610x350mm 27.7-inch                       | 1         | 1.79%   |
| Dell U2520D DELA150 2560x1440 553x311mm 25.0-inch                       | 1         | 1.79%   |
| Dell U2520D DELA14E 2560x1440 553x311mm 25.0-inch                       | 1         | 1.79%   |
| Dell U2520D DELA14C 2560x1440 553x311mm 25.0-inch                       | 1         | 1.79%   |
| Dell SE2219H DELF10E 1920x1080 476x268mm 21.5-inch                      | 1         | 1.79%   |
| Dell P2418HT DEL4113 1920x1080 527x296mm 23.8-inch                      | 1         | 1.79%   |
| Dell 2408WFP DELA029 1920x1200 519x324mm 24.1-inch                      | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN1608 1920x1080 355x199mm 16.0-inch        | 1         | 1.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 28        | 56%     |
| 1366x768 (WXGA)   | 6         | 12%     |
| 3840x2160 (4K)    | 4         | 8%      |
| 2560x1440 (QHD)   | 2         | 4%      |
| 1600x900 (HD+)    | 2         | 4%      |
| 1280x1024 (SXGA)  | 2         | 4%      |
| 3840x1080         | 1         | 2%      |
| 3440x1440         | 1         | 2%      |
| 3200x2000         | 1         | 2%      |
| 1920x1200 (WUXGA) | 1         | 2%      |
| 1280x960          | 1         | 2%      |
| Unknown           | 1         | 2%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 14      | 10        | 18.87%  |
| 27      | 8         | 15.09%  |
| 15      | 8         | 15.09%  |
| 21      | 7         | 13.21%  |
| 24      | 5         | 9.43%   |
| 23      | 3         | 5.66%   |
| 17      | 2         | 3.77%   |
| Unknown | 2         | 3.77%   |
| 84      | 1         | 1.89%   |
| 38      | 1         | 1.89%   |
| 34      | 1         | 1.89%   |
| 25      | 1         | 1.89%   |
| 19      | 1         | 1.89%   |
| 18      | 1         | 1.89%   |
| 16      | 1         | 1.89%   |
| 13      | 1         | 1.89%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 20        | 39.22%  |
| 501-600     | 11        | 21.57%  |
| 401-500     | 8         | 15.69%  |
| 601-700     | 4         | 7.84%   |
| 351-400     | 3         | 5.88%   |
| Unknown     | 2         | 3.92%   |
| 801-900     | 1         | 1.96%   |
| 701-800     | 1         | 1.96%   |
| 1501-2000   | 1         | 1.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 37        | 84.09%  |
| 5/4     | 2         | 4.55%   |
| 16/10   | 2         | 4.55%   |
| 4/3     | 1         | 2.27%   |
| 21/9    | 1         | 2.27%   |
| Unknown | 1         | 2.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 11        | 21.15%  |
| 201-250        | 11        | 21.15%  |
| 301-350        | 8         | 15.38%  |
| 101-110        | 8         | 15.38%  |
| 251-300        | 3         | 5.77%   |
| 151-200        | 2         | 3.85%   |
| 141-150        | 2         | 3.85%   |
| Unknown        | 2         | 3.85%   |
| More than 1000 | 1         | 1.92%   |
| 351-500        | 1         | 1.92%   |
| 121-130        | 1         | 1.92%   |
| 111-120        | 1         | 1.92%   |
| 501-1000       | 1         | 1.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 16        | 31.37%  |
| 101-120       | 15        | 29.41%  |
| 51-100        | 15        | 29.41%  |
| 161-240       | 2         | 3.92%   |
| Unknown       | 2         | 3.92%   |
| More than 240 | 1         | 1.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 35        | 70%     |
| 2     | 8         | 16%     |
| 0     | 5         | 10%     |
| 4     | 1         | 2%      |
| 3     | 1         | 2%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 32        | 40%     |
| Realtek Semiconductor             | 20        | 25%     |
| Qualcomm Atheros                  | 10        | 12.5%   |
| Broadcom                          | 5         | 6.25%   |
| Xiaomi                            | 1         | 1.25%   |
| U-Blox                            | 1         | 1.25%   |
| TP-Link                           | 1         | 1.25%   |
| Mellanox Technologies             | 1         | 1.25%   |
| MediaTek                          | 1         | 1.25%   |
| IBM                               | 1         | 1.25%   |
| Ericsson Business Mobile Networks | 1         | 1.25%   |
| DisplayLink                       | 1         | 1.25%   |
| Dell                              | 1         | 1.25%   |
| Ceton Technologies                | 1         | 1.25%   |
| ASUSTek Computer                  | 1         | 1.25%   |
| ASIX Electronics                  | 1         | 1.25%   |
| Aquantia                          | 1         | 1.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 15.31%  |
| Intel Ethernet Controller I225-V                                  | 5         | 5.1%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 5.1%    |
| Intel Wireless 7260                                               | 4         | 4.08%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 3.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 3.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.06%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 2.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 2.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 2.04%   |
| Intel Wireless 8260                                               | 2         | 2.04%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 2.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 2.04%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 2.04%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.02%   |
| U-Blox [u-blox 8]                                                 | 1         | 1.02%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 1.02%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 1.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.02%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.02%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.02%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 1.02%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.02%   |
| Mellanox MT27800 Family [ConnectX-5]                              | 1         | 1.02%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 1.02%   |
| Intel Wireless-AC 9260                                            | 1         | 1.02%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.02%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 1.02%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.02%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.02%   |
| Intel Ethernet Controller XL710 for 40GbE QSFP+                   | 1         | 1.02%   |
| Intel Ethernet Controller X710 for 10GBASE-T                      | 1         | 1.02%   |
| Intel Ethernet Controller I226-V                                  | 1         | 1.02%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.02%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.02%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.02%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.02%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.02%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 57.5%   |
| Qualcomm Atheros      | 9         | 22.5%   |
| Realtek Semiconductor | 4         | 10%     |
| TP-Link               | 1         | 2.5%    |
| MediaTek              | 1         | 2.5%    |
| Broadcom              | 1         | 2.5%    |
| ASUSTek Computer      | 1         | 2.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                               | 5         | 12.5%   |
| Intel Wireless 7260                                            | 4         | 10%     |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 7.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 5%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 5%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 5%      |
| Intel Wireless 8260                                            | 2         | 5%      |
| Intel Wi-Fi 6 AX200                                            | 2         | 5%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 5%      |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1         | 2.5%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 2.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 2.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 2.5%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1         | 2.5%    |
| Intel Wireless-AC 9260                                         | 1         | 2.5%    |
| Intel Wireless 8265 / 8275                                     | 1         | 2.5%    |
| Intel Wi-Fi 6 AX201                                            | 1         | 2.5%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 2.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 2.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 2.5%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2.5%    |
| Intel 700 Series Chipset Family Wi-Fi                          | 1         | 2.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 2.5%    |
| ASUS 802.11ac NIC                                              | 1         | 2.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 21        | 39.62%  |
| Realtek Semiconductor | 18        | 33.96%  |
| Broadcom              | 4         | 7.55%   |
| Qualcomm Atheros      | 2         | 3.77%   |
| Xiaomi                | 1         | 1.89%   |
| Mellanox Technologies | 1         | 1.89%   |
| IBM                   | 1         | 1.89%   |
| DisplayLink           | 1         | 1.89%   |
| Dell                  | 1         | 1.89%   |
| Ceton Technologies    | 1         | 1.89%   |
| ASIX Electronics      | 1         | 1.89%   |
| Aquantia              | 1         | 1.89%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 15        | 26.79%  |
| Intel Ethernet Controller I225-V                                      | 5         | 8.93%   |
| Realtek RTL8125 2.5GbE Controller                                     | 3         | 5.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 3         | 5.36%   |
| Intel 82574L Gigabit Network Connection                               | 2         | 3.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                        | 1         | 1.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                 | 1         | 1.79%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                | 1         | 1.79%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                 | 1         | 1.79%   |
| Mellanox MT27800 Family [ConnectX-5]                                  | 1         | 1.79%   |
| Intel I211 Gigabit Network Connection                                 | 1         | 1.79%   |
| Intel I210 Gigabit Network Connection                                 | 1         | 1.79%   |
| Intel Ethernet Controller XL710 for 40GbE QSFP+                       | 1         | 1.79%   |
| Intel Ethernet Controller X710 for 10GBASE-T                          | 1         | 1.79%   |
| Intel Ethernet Controller I226-V                                      | 1         | 1.79%   |
| Intel Ethernet Connection I219-V                                      | 1         | 1.79%   |
| Intel Ethernet Connection I219-LM                                     | 1         | 1.79%   |
| Intel Ethernet Connection I218-V                                      | 1         | 1.79%   |
| Intel Ethernet Connection I218-LM                                     | 1         | 1.79%   |
| Intel Ethernet Connection I217-V                                      | 1         | 1.79%   |
| Intel Ethernet Connection (4) I219-V                                  | 1         | 1.79%   |
| Intel Ethernet Connection (2) I218-V                                  | 1         | 1.79%   |
| Intel 82579V Gigabit Network Connection                               | 1         | 1.79%   |
| IBM RNDIS/Ethernet Gadget                                             | 1         | 1.79%   |
| DisplayLink Plugable UD-6950PDZ                                       | 1         | 1.79%   |
| Dell iDRAC Virtual NIC                                                | 1         | 1.79%   |
| Ceton InfiniTV Network                                                | 1         | 1.79%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                     | 1         | 1.79%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 1         | 1.79%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                       | 1         | 1.79%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1         | 1.79%   |
| ASIX AX88179 Gigabit Ethernet                                         | 1         | 1.79%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 1         | 1.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 43        | 51.81%  |
| WiFi     | 38        | 45.78%  |
| Modem    | 2         | 2.41%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 24        | 51.06%  |
| WiFi     | 23        | 48.94%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 32        | 65.31%  |
| 1     | 12        | 24.49%  |
| 3     | 3         | 6.12%   |
| 7     | 1         | 2.04%   |
| 4     | 1         | 2.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 37        | 75.51%  |
| Yes  | 12        | 24.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 58.82%  |
| Qualcomm Atheros Communications | 3         | 8.82%   |
| Lite-On Technology              | 3         | 8.82%   |
| Realtek Semiconductor           | 2         | 5.88%   |
| Broadcom                        | 2         | 5.88%   |
| MediaTek                        | 1         | 2.94%   |
| IMC Networks                    | 1         | 2.94%   |
| Cambridge Silicon Radio         | 1         | 2.94%   |
| ASUSTek Computer                | 1         | 2.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 23.53%  |
| Intel Bluetooth Device                              | 5         | 14.71%  |
| Realtek Bluetooth Radio                             | 2         | 5.88%   |
| Lite-On Bluetooth Device                            | 2         | 5.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 5.88%   |
| Intel AX201 Bluetooth                               | 2         | 5.88%   |
| Intel AX200 Bluetooth                               | 2         | 5.88%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 5.88%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.94%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 2.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.94%   |
| MediaTek Wireless_Device                            | 1         | 2.94%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 2.94%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.94%   |
| IMC Networks Bluetooth Device                       | 1         | 2.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.94%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 36        | 52.94%  |
| Nvidia                   | 14        | 20.59%  |
| AMD                      | 13        | 19.12%  |
| SteelSeries ApS          | 3         | 4.41%   |
| Micro Star International | 1         | 1.47%   |
| Anlya.cn                 | 1         | 1.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 6.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 5.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 5.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 5.13%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 5.13%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 3.85%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 3.85%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 3.85%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 3.85%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 3.85%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 2.56%   |
| Nvidia TU102 High Definition Audio Controller                              | 2         | 2.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 2.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 2.56%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 2.56%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 2.56%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 2.56%   |
| SteelSeries ApS SteelSeries Siberia 800                                    | 1         | 1.28%   |
| SteelSeries ApS SteelSeries GameDAC                                        | 1         | 1.28%   |
| SteelSeries ApS Arctis Nova Pro Wireless                                   | 1         | 1.28%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.28%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 1.28%   |
| Nvidia GM200 High Definition Audio                                         | 1         | 1.28%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.28%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.28%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.28%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 1.28%   |
| Nvidia Audio device                                                        | 1         | 1.28%   |
| Micro Star International USB Audio                                         | 1         | 1.28%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.28%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1         | 1.28%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.28%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.28%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.28%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.28%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.28%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 1.28%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 1         | 1.28%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.28%   |
| Anlya.cn AB13X USB Audio                                                   | 1         | 1.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 9         | 31.03%  |
| SK hynix            | 5         | 17.24%  |
| G.Skill             | 3         | 10.34%  |
| Corsair             | 3         | 10.34%  |
| Kingston            | 2         | 6.9%    |
| Crucial             | 2         | 6.9%    |
| Unknown (ABCD)      | 1         | 3.45%   |
| Team                | 1         | 3.45%   |
| Smart Brazil        | 1         | 3.45%   |
| SHARETRONIC         | 1         | 3.45%   |
| A-DATA Technology   | 1         | 3.45%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1         | 3.45%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s             | 1         | 3.45%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s   | 1         | 3.45%   |
| SK hynix RAM Module 4GB DIMM DDR3 1600MT/s                     | 1         | 3.45%   |
| SK hynix RAM HMT31GR7BFR4A-H9 8GB DIMM DDR3 1333MT/s           | 1         | 3.45%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s         | 1         | 3.45%   |
| SK hynix RAM HMA84GR7DJR4N-XN 32GB DIMM DDR4 3200MT/s          | 1         | 3.45%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s        | 1         | 3.45%   |
| SHARETRONIC RAM Module 4GB SODIMM DDR3 800MT/s                 | 1         | 3.45%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                    | 1         | 3.45%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s          | 1         | 3.45%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 3.45%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 1         | 3.45%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s          | 1         | 3.45%   |
| Samsung RAM M393B1K70DH0-YH9 8GB DIMM 1333MT/s                 | 1         | 3.45%   |
| Samsung RAM M393A4K40EB3-CWE 32GB DIMM DDR4 3200MT/s           | 1         | 3.45%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s            | 1         | 3.45%   |
| Samsung RAM K4UBE3D4AA-MGCR 8GB Row Of Chips LPDDR4 4267MT/s   | 1         | 3.45%   |
| Kingston RAM 99U5471-034.A00LF 4GB DIMM DDR3 1600MT/s          | 1         | 3.45%   |
| Kingston RAM 9905417-083.A00G 4GB SODIMM DDR3 1600MT/s         | 1         | 3.45%   |
| G.Skill RAM F5-5600J3036D32G 32GB DIMM DDR5 5600MT/s           | 1         | 3.45%   |
| G.Skill RAM F4-3600C18-32GTZR 32GB DIMM DDR4 3600MT/s          | 1         | 3.45%   |
| G.Skill RAM F3-1600C9-8GRSL 8GB SODIMM DDR3 1600MT/s           | 1         | 3.45%   |
| Crucial RAM CT8G4SFS824A.M8FD 8GB SODIMM DDR4 2400MT/s         | 1         | 3.45%   |
| Crucial RAM CT16G4DFD824A.C16FBD 16GB DIMM DDR4 2933MT/s       | 1         | 3.45%   |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s        | 1         | 3.45%   |
| Corsair RAM CMK64GX4M2Z4000C18 32GB DIMM DDR4 4000MT/s         | 1         | 3.45%   |
| Corsair RAM CMK128GX4M8A2666C16 16GB DIMM DDR4 2133MT/s        | 1         | 3.45%   |
| A-DATA RAM Module 32GB SODIMM DDR4 3200MT/s                    | 1         | 3.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 13        | 50%     |
| DDR3   | 10        | 38.46%  |
| LPDDR4 | 2         | 7.69%   |
| DDR5   | 1         | 3.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 13        | 50%     |
| SODIMM       | 11        | 42.31%  |
| Row Of Chips | 2         | 7.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 11        | 40.74%  |
| 32768 | 6         | 22.22%  |
| 4096  | 5         | 18.52%  |
| 16384 | 4         | 14.81%  |
| 2048  | 1         | 3.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 6         | 23.08%  |
| 3200  | 5         | 19.23%  |
| 2667  | 2         | 7.69%   |
| 2400  | 2         | 7.69%   |
| 2133  | 2         | 7.69%   |
| 5600  | 1         | 3.85%   |
| 4267  | 1         | 3.85%   |
| 4000  | 1         | 3.85%   |
| 3600  | 1         | 3.85%   |
| 2933  | 1         | 3.85%   |
| 1800  | 1         | 3.85%   |
| 1333  | 1         | 3.85%   |
| 1067  | 1         | 3.85%   |
| 800   | 1         | 3.85%   |

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
| Chicony Electronics                    | 5         | 20%     |
| Bison Electronics                      | 4         | 16%     |
| IMC Networks                           | 3         | 12%     |
| Syntek                                 | 2         | 8%      |
| Sunplus Innovation Technology          | 2         | 8%      |
| Realtek Semiconductor                  | 2         | 8%      |
| Logitech                               | 2         | 8%      |
| Cheng Uei Precision Industry (Foxlink) | 2         | 8%      |
| Microdia                               | 1         | 4%      |
| Luxvisions Innotech Limited            | 1         | 4%      |
| Apple                                  | 1         | 4%      |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                            | 2         | 8%      |
| Sunplus Full HD webcam                              | 2         | 8%      |
| Bison Integrated Camera                             | 2         | 8%      |
| Realtek Lenovo EasyCamera                           | 1         | 4%      |
| Realtek Integrated_Webcam_HD                        | 1         | 4%      |
| Microdia USB Live camera                            | 1         | 4%      |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 4%      |
| Logitech Webcam C270                                | 1         | 4%      |
| Logitech C922 Pro Stream Webcam                     | 1         | 4%      |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 4%      |
| IMC Networks Integrated RGB Camera                  | 1         | 4%      |
| IMC Networks Integrated Camera                      | 1         | 4%      |
| Chicony Thinkpad T430 camera                        | 1         | 4%      |
| Chicony Integrated Camera                           | 1         | 4%      |
| Chicony HD WebCam (Asus N-series)                   | 1         | 4%      |
| Chicony HD WebCam                                   | 1         | 4%      |
| Chicony Acer CrystalEye Webcam                      | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 4%      |
| Bison Lenovo Integrated Webcam                      | 1         | 4%      |
| Bison HD Webcam                                     | 1         | 4%      |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 1         | 4%      |

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
| 0     | 32        | 61.54%  |
| 1     | 14        | 26.92%  |
| 2     | 4         | 7.69%   |
| 4     | 1         | 1.92%   |
| 3     | 1         | 1.92%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 5         | 20%     |
| Net/wireless             | 4         | 16%     |
| Unassigned class         | 3         | 12%     |
| Multimedia controller    | 3         | 12%     |
| Communication controller | 3         | 12%     |
| Fingerprint reader       | 2         | 8%      |
| Storage/ata              | 1         | 4%      |
| Storage                  | 1         | 4%      |
| Dvb card                 | 1         | 4%      |
| Chipcard                 | 1         | 4%      |
| Bluetooth                | 1         | 4%      |

