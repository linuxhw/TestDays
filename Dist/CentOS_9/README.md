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

Total: 72

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | MAG B760M MORTAR WIFI       | Desktop     | [342164a6a4](https://linux-hardware.org/?probe=342164a6a4) | Dec 29, 2023 |
| SHANGZHAOY... | B85M-PRO V1.1               | Desktop     | [bd7c6e2693](https://linux-hardware.org/?probe=bd7c6e2693) | Dec 22, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [e8965075d3](https://linux-hardware.org/?probe=e8965075d3) | Dec 14, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [e9e5956d89](https://linux-hardware.org/?probe=e9e5956d89) | Dec 10, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [ecc33f393d](https://linux-hardware.org/?probe=ecc33f393d) | Nov 22, 2023 |
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
| 5.14.0-86.el9.x86_64           | 3         | 5.08%   |
| 5.14.0-202.el9.x86_64          | 3         | 5.08%   |
| 5.14.0-134.el9.x86_64          | 3         | 5.08%   |
| 5.14.0-391.el9.x86_64          | 2         | 3.39%   |
| 5.14.0-362.el9.x86_64          | 2         | 3.39%   |
| 5.14.0-325.el9.x86_64          | 2         | 3.39%   |
| 5.14.0-319.el9.x86_64          | 2         | 3.39%   |
| 5.14.0-214.el9.x86_64          | 2         | 3.39%   |
| 5.14.0-183.el9.x86_64          | 2         | 3.39%   |
| 5.14.0-171.el9.x86_64          | 2         | 3.39%   |
| 5.14.0-148.el9.x86_64          | 2         | 3.39%   |
| 6.1.8-1.el9.elrepo.x86_64      | 1         | 1.69%   |
| 6.1.1                          | 1         | 1.69%   |
| 5.17.2-lqx3.0.el9.x86_64       | 1         | 1.69%   |
| 5.14.0-78.el9.x86_64           | 1         | 1.69%   |
| 5.14.0-71.el9.x86_64           | 1         | 1.69%   |
| 5.14.0-66.el9.x86_64           | 1         | 1.69%   |
| 5.14.0-52.el9.x86_64           | 1         | 1.69%   |
| 5.14.0-44.el9.x86_64           | 1         | 1.69%   |
| 5.14.0-390.el9.x86_64          | 1         | 1.69%   |
| 5.14.0-383.el9.x86_64          | 1         | 1.69%   |
| 5.14.0-375.el9.x86_64          | 1         | 1.69%   |
| 5.14.0-373.el9.x86_64          | 1         | 1.69%   |
| 5.14.0-352.el9.x86_64          | 1         | 1.69%   |
| 5.14.0-350.el9.x86_64          | 1         | 1.69%   |
| 5.14.0-344.el9.x86_64          | 1         | 1.69%   |
| 5.14.0-340.el9.x86_64          | 1         | 1.69%   |
| 5.14.0-333.el9.x86_64          | 1         | 1.69%   |
| 5.14.0-316.el9.x86_64          | 1         | 1.69%   |
| 5.14.0-305.el9.x86_64          | 1         | 1.69%   |
| 5.14.0-302.el9.x86_64          | 1         | 1.69%   |
| 5.14.0-299.el9.x86_64          | 1         | 1.69%   |
| 5.14.0-289.el9.x86_64          | 1         | 1.69%   |
| 5.14.0-283.el9.x86_64          | 1         | 1.69%   |
| 5.14.0-282.el9.x86_64          | 1         | 1.69%   |
| 5.14.0-267.el9.x86_64          | 1         | 1.69%   |
| 5.14.0-226.el9.x86_64          | 1         | 1.69%   |
| 5.14.0-200.el9.x86_64          | 1         | 1.69%   |
| 5.14.0-163.el9.x86_64          | 1         | 1.69%   |
| 5.14.0-130.rt21.130.el9.x86_64 | 1         | 1.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 50        | 94.34%  |
| 6.1.8   | 1         | 1.89%   |
| 6.1.1   | 1         | 1.89%   |
| 5.17.2  | 1         | 1.89%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 50        | 94.34%  |
| 6.1     | 2         | 3.77%   |
| 5.17    | 1         | 1.89%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 52        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 44        | 84.62%  |
| KDE5          | 3         | 5.77%   |
| GNOME Classic | 3         | 5.77%   |
| Unknown       | 2         | 3.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 35        | 66.04%  |
| X11     | 16        | 30.19%  |
| Tty     | 2         | 3.77%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 28        | 52.83%  |
| GDM     | 22        | 41.51%  |
| SDDM    | 2         | 3.77%   |
| LightDM | 1         | 1.89%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 32        | 61.54%  |
| ru_RU | 3         | 5.77%   |
| de_DE | 3         | 5.77%   |
| zh_CN | 2         | 3.85%   |
| pt_BR | 2         | 3.85%   |
| ja_JP | 2         | 3.85%   |
| it_IT | 2         | 3.85%   |
| sv_SE | 1         | 1.92%   |
| ru_UA | 1         | 1.92%   |
| fr_FR | 1         | 1.92%   |
| en_IN | 1         | 1.92%   |
| en_GB | 1         | 1.92%   |
| en_AU | 1         | 1.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 38        | 73.08%  |
| BIOS | 14        | 26.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 48        | 92.31%  |
| Ext4 | 4         | 7.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 26        | 48.15%  |
| GPT     | 20        | 37.04%  |
| MBR     | 8         | 14.81%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 47        | 88.68%  |
| Yes       | 6         | 11.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 41        | 75.93%  |
| Yes       | 13        | 24.07%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 10        | 19.23%  |
| ASUSTek Computer    | 10        | 19.23%  |
| MSI                 | 4         | 7.69%   |
| Intel               | 4         | 7.69%   |
| Dell                | 4         | 7.69%   |
| Acer                | 4         | 7.69%   |
| Hewlett-Packard     | 3         | 5.77%   |
| Timi                | 2         | 3.85%   |
| Gigabyte Technology | 2         | 3.85%   |
| Zvezda              | 1         | 1.92%   |
| SHANGZHAOYUAN       | 1         | 1.92%   |
| Samsung Electronics | 1         | 1.92%   |
| Razer               | 1         | 1.92%   |
| IP3 Tech            | 1         | 1.92%   |
| IBM                 | 1         | 1.92%   |
| Gateway             | 1         | 1.92%   |
| Colorful Technology | 1         | 1.92%   |
| AZW                 | 1         | 1.92%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUS PRIME H670-PLUS D4              | 2         | 3.85%   |
| Zvezda Altair Z                      | 1         | 1.92%   |
| Timi RedmiBook 16                    | 1         | 1.92%   |
| Timi Mi NoteBook Horizon Edition 14  | 1         | 1.92%   |
| SHANGZHAOYUAN B85M-PRO V1.1          | 1         | 1.92%   |
| Samsung 355V4C/356V4C/3445VC/3545VC  | 1         | 1.92%   |
| Razer Blade 15 (2022) - RZ09-0421    | 1         | 1.92%   |
| MSI MS-7E01                          | 1         | 1.92%   |
| MSI MS-7D86                          | 1         | 1.92%   |
| MSI MS-7B79                          | 1         | 1.92%   |
| MSI Katana GF76 12UE                 | 1         | 1.92%   |
| Lenovo Yoga S740-14IIL 81RS          | 1         | 1.92%   |
| Lenovo V15 G2 ITL 82KB               | 1         | 1.92%   |
| Lenovo ThinkPad T460s 20FAS5WX00     | 1         | 1.92%   |
| Lenovo ThinkPad T430 2349DG5         | 1         | 1.92%   |
| Lenovo ThinkPad T430 2347DE9         | 1         | 1.92%   |
| Lenovo ThinkPad L14 Gen 1 20U5S0NT00 | 1         | 1.92%   |
| Lenovo Legion 5P 15IMH05H 82AW       | 1         | 1.92%   |
| Lenovo IdeaPad S145-15IWL 81S9       | 1         | 1.92%   |
| Lenovo G580 20150                    | 1         | 1.92%   |
| Lenovo G410 20237                    | 1         | 1.92%   |
| IP3 Tech HeroBox                     | 1         | 1.92%   |
| Intel NUC7i3BNK                      | 1         | 1.92%   |
| Intel NUC12WSHi7                     | 1         | 1.92%   |
| Intel NUC12WSHi5                     | 1         | 1.92%   |
| Intel D34010WYK H14771-303           | 1         | 1.92%   |
| IBM System x3250 M3 -[425242G]       | 1         | 1.92%   |
| HP Pavilion Gaming Laptop 15-ec0xxx  | 1         | 1.92%   |
| HP EliteBook 840 G3                  | 1         | 1.92%   |
| HP EliteBook 840 G1                  | 1         | 1.92%   |
| Gigabyte X99-UD4-CF                  | 1         | 1.92%   |
| Gigabyte 970A-DS3P                   | 1         | 1.92%   |
| Gateway SX2865                       | 1         | 1.92%   |
| Dell Vostro 5402                     | 1         | 1.92%   |
| Dell PowerEdge T640                  | 1         | 1.92%   |
| Dell PowerEdge R720                  | 1         | 1.92%   |
| Dell OptiPlex 790                    | 1         | 1.92%   |
| Colorful CVN Z590 GAMING PRO         | 1         | 1.92%   |
| AZW SER                              | 1         | 1.92%   |
| ASUS TUF Gaming X570-PLUS            | 1         | 1.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 4         | 7.69%   |
| HP EliteBook           | 2         | 3.85%   |
| Dell PowerEdge         | 2         | 3.85%   |
| ASUS ROG               | 2         | 3.85%   |
| ASUS PRIME             | 2         | 3.85%   |
| Acer Aspire            | 2         | 3.85%   |
| Zvezda Altair          | 1         | 1.92%   |
| Timi RedmiBook         | 1         | 1.92%   |
| Timi Mi                | 1         | 1.92%   |
| SHANGZHAOYUAN B85M-PRO | 1         | 1.92%   |
| Samsung 355V4C         | 1         | 1.92%   |
| Razer Blade            | 1         | 1.92%   |
| MSI MS-7E01            | 1         | 1.92%   |
| MSI MS-7D86            | 1         | 1.92%   |
| MSI MS-7B79            | 1         | 1.92%   |
| MSI Katana             | 1         | 1.92%   |
| Lenovo Yoga            | 1         | 1.92%   |
| Lenovo V15             | 1         | 1.92%   |
| Lenovo Legion          | 1         | 1.92%   |
| Lenovo IdeaPad         | 1         | 1.92%   |
| Lenovo G580            | 1         | 1.92%   |
| Lenovo G410            | 1         | 1.92%   |
| IP3 Tech HeroBox       | 1         | 1.92%   |
| Intel NUC7i3BNK        | 1         | 1.92%   |
| Intel NUC12WSHi7       | 1         | 1.92%   |
| Intel NUC12WSHi5       | 1         | 1.92%   |
| Intel D34010WYK        | 1         | 1.92%   |
| IBM System             | 1         | 1.92%   |
| HP Pavilion            | 1         | 1.92%   |
| Gigabyte X99-UD4-CF    | 1         | 1.92%   |
| Gigabyte 970A-DS3P     | 1         | 1.92%   |
| Gateway SX2865         | 1         | 1.92%   |
| Dell Vostro            | 1         | 1.92%   |
| Dell OptiPlex          | 1         | 1.92%   |
| Colorful CVN           | 1         | 1.92%   |
| AZW SER                | 1         | 1.92%   |
| ASUS TUF               | 1         | 1.92%   |
| ASUS Q550LF            | 1         | 1.92%   |
| ASUS P8H67-M           | 1         | 1.92%   |
| ASUS P8H61             | 1         | 1.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 10        | 19.23%  |
| 2022 | 7         | 13.46%  |
| 2021 | 7         | 13.46%  |
| 2020 | 6         | 11.54%  |
| 2019 | 5         | 9.62%   |
| 2012 | 4         | 7.69%   |
| 2011 | 3         | 5.77%   |
| 2023 | 2         | 3.85%   |
| 2018 | 2         | 3.85%   |
| 2016 | 2         | 3.85%   |
| 2014 | 2         | 3.85%   |
| 2010 | 1         | 1.92%   |
| 2009 | 1         | 1.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 24        | 46.15%  |
| Desktop  | 19        | 36.54%  |
| Mini pc  | 5         | 9.62%   |
| Server   | 4         | 7.69%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 47        | 90.38%  |
| Enabled  | 5         | 9.62%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 52        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 19        | 36.54%  |
| 8.01-16.0       | 11        | 21.15%  |
| 32.01-64.0      | 8         | 15.38%  |
| 64.01-256.0     | 7         | 13.46%  |
| More than 256.0 | 2         | 3.85%   |
| 3.01-4.0        | 2         | 3.85%   |
| 16.01-24.0      | 2         | 3.85%   |
| 24.01-32.0      | 1         | 1.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 21        | 38.18%  |
| 3.01-4.0   | 13        | 23.64%  |
| 4.01-8.0   | 9         | 16.36%  |
| 1.01-2.0   | 4         | 7.27%   |
| 8.01-16.0  | 4         | 7.27%   |
| 16.01-24.0 | 2         | 3.64%   |
| 0.51-1.0   | 2         | 3.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 25        | 48.08%  |
| 2      | 12        | 23.08%  |
| 4      | 6         | 11.54%  |
| 3      | 6         | 11.54%  |
| 5      | 2         | 3.85%   |
| 10     | 1         | 1.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 39        | 75%     |
| Yes       | 13        | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 90.38%  |
| No        | 5         | 9.62%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 76.92%  |
| No        | 12        | 23.08%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 69.23%  |
| No        | 16        | 30.77%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 10        | 19.23%  |
| Germany      | 6         | 11.54%  |
| Italy        | 3         | 5.77%   |
| China        | 3         | 5.77%   |
| Bulgaria     | 3         | 5.77%   |
| Ukraine      | 2         | 3.85%   |
| Russia       | 2         | 3.85%   |
| Poland       | 2         | 3.85%   |
| Japan        | 2         | 3.85%   |
| Canada       | 2         | 3.85%   |
| Brazil       | 2         | 3.85%   |
| Uzbekistan   | 1         | 1.92%   |
| Switzerland  | 1         | 1.92%   |
| Sweden       | 1         | 1.92%   |
| South Africa | 1         | 1.92%   |
| Puerto Rico  | 1         | 1.92%   |
| Netherlands  | 1         | 1.92%   |
| Myanmar      | 1         | 1.92%   |
| Kazakhstan   | 1         | 1.92%   |
| India        | 1         | 1.92%   |
| France       | 1         | 1.92%   |
| Finland      | 1         | 1.92%   |
| Colombia     | 1         | 1.92%   |
| Chile        | 1         | 1.92%   |
| Belarus      | 1         | 1.92%   |
| Australia    | 1         | 1.92%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Sofia             | 2         | 3.64%   |
| Moscow            | 2         | 3.64%   |
| Bristow           | 2         | 3.64%   |
| Beijing           | 2         | 3.64%   |
| Yangon            | 1         | 1.82%   |
| Wuhan             | 1         | 1.82%   |
| Vitebsk           | 1         | 1.82%   |
| Vicenza           | 1         | 1.82%   |
| Tomah             | 1         | 1.82%   |
| Tashkent          | 1         | 1.82%   |
| Stromberg         | 1         | 1.82%   |
| Stockholm         | 1         | 1.82%   |
| Soest             | 1         | 1.82%   |
| Schemmerhofen     | 1         | 1.82%   |
| San Juan          | 1         | 1.82%   |
| Ruda Śląska     | 1         | 1.82%   |
| Rome              | 1         | 1.82%   |
| Ribeirao Preto    | 1         | 1.82%   |
| Quitman           | 1         | 1.82%   |
| Puente Alto       | 1         | 1.82%   |
| Porto Alegre      | 1         | 1.82%   |
| Portland          | 1         | 1.82%   |
| Perth             | 1         | 1.82%   |
| Persan            | 1         | 1.82%   |
| Ozarow Mazowiecki | 1         | 1.82%   |
| Okazaki           | 1         | 1.82%   |
| New York          | 1         | 1.82%   |
| New Cumberland    | 1         | 1.82%   |
| Navapolatsk       | 1         | 1.82%   |
| Nagoya            | 1         | 1.82%   |
| Mumbai            | 1         | 1.82%   |
| Milpitas          | 1         | 1.82%   |
| Michelstadt       | 1         | 1.82%   |
| Meieki            | 1         | 1.82%   |
| L'Isle-Adam       | 1         | 1.82%   |
| Kyiv              | 1         | 1.82%   |
| Kramatorsk        | 1         | 1.82%   |
| Helsinki          | 1         | 1.82%   |
| Hamburg           | 1         | 1.82%   |
| Durham            | 1         | 1.82%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 13        | 19     | 15.48%  |
| WDC                       | 12        | 17     | 14.29%  |
| Seagate                   | 9         | 13     | 10.71%  |
| Kingston                  | 9         | 12     | 10.71%  |
| Toshiba                   | 5         | 8      | 5.95%   |
| SanDisk                   | 4         | 12     | 4.76%   |
| SK hynix                  | 3         | 3      | 3.57%   |
| Intel                     | 3         | 3      | 3.57%   |
| HGST                      | 3         | 4      | 3.57%   |
| Micron Technology         | 2         | 2      | 2.38%   |
| Crucial                   | 2         | 10     | 2.38%   |
| WD MediaMax               | 1         | 1      | 1.19%   |
| Unknown                   | 1         | 1      | 1.19%   |
| Union Memory              | 1         | 1      | 1.19%   |
| Team                      | 1         | 2      | 1.19%   |
| SPCC                      | 1         | 1      | 1.19%   |
| Plextor                   | 1         | 1      | 1.19%   |
| Phison Electronics        | 1         | 1      | 1.19%   |
| Phison                    | 1         | 1      | 1.19%   |
| OCZ                       | 1         | 1      | 1.19%   |
| Netac                     | 1         | 2      | 1.19%   |
| Micron/Crucial Technology | 1         | 1      | 1.19%   |
| LITEON                    | 1         | 1      | 1.19%   |
| Intenso                   | 1         | 1      | 1.19%   |
| Hjwdz                     | 1         | 1      | 1.19%   |
| Hitachi                   | 1         | 1      | 1.19%   |
| Hewlett-Packard           | 1         | 1      | 1.19%   |
| Gigabyte Technology       | 1         | 2      | 1.19%   |
| ASMT                      | 1         | 1      | 1.19%   |
| A-DATA Technology         | 1         | 1      | 1.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Sandisk WD_BLACK SN770 1TB                          | 2         | 2.2%    |
| SanDisk SDSSDH3 1T00 1TB                            | 2         | 2.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 2         | 2.2%    |
| Samsung MZNLH512HALU-00000 512GB SSD                | 2         | 2.2%    |
| Micron 2450_MTFDKBA512TFK 512GB                     | 2         | 2.2%    |
| Crucial CT525MX300SSD1 528GB                        | 2         | 2.2%    |
| WDC WDS250G2B0A-00SM50 250GB SSD                    | 1         | 1.1%    |
| WDC WD6400BEVT-22A0RT0 640GB                        | 1         | 1.1%    |
| WDC WD6003FZBX-00K5WB0 6TB                          | 1         | 1.1%    |
| WDC WD5000LPLX-60ZNTT1 500GB                        | 1         | 1.1%    |
| WDC WD5000BEVT-55A0RT0 500GB                        | 1         | 1.1%    |
| WDC WD3200AAKX-753CA1 320GB                         | 1         | 1.1%    |
| WDC WD2500AAJS-60M0A0 250GB                         | 1         | 1.1%    |
| WDC WD22EJRX-89BEMY0 2TB                            | 1         | 1.1%    |
| WDC WD2003FZEX-00Z4SA0 2TB                          | 1         | 1.1%    |
| WDC WD10EZEX-60M2NA0 1TB                            | 1         | 1.1%    |
| WDC WD10EZEX-08WN4A0 1TB                            | 1         | 1.1%    |
| WDC WD10EZEX-00BN5A0 1TB                            | 1         | 1.1%    |
| WDC WD Blue SA510 2.5 500GB                         | 1         | 1.1%    |
| WD MediaMax WL750GSA6472 752GB                      | 1         | 1.1%    |
| Unknown MMC Card  7GB                               | 1         | 1.1%    |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB             | 1         | 1.1%    |
| Toshiba MQ04ABF100 1TB                              | 1         | 1.1%    |
| Toshiba MK2561GSYN 250GB                            | 1         | 1.1%    |
| Toshiba DT01ACA200 2TB                              | 1         | 1.1%    |
| Toshiba DT01ACA100 1TB                              | 1         | 1.1%    |
| Toshiba AL15SEB24EQY 2TB                            | 1         | 1.1%    |
| Toshiba AL15SEB24EQY 2.4TB                          | 1         | 1.1%    |
| Team T253X1480G 480GB SSD                           | 1         | 1.1%    |
| SPCC Solid State Disk 120GB                         | 1         | 1.1%    |
| SK hynix NVMe SSD Drive 256GB                       | 1         | 1.1%    |
| SK hynix BC511 512GB                                | 1         | 1.1%    |
| SK hynix BC501 NVMe 256GB                           | 1         | 1.1%    |
| Seagate ST600MM0088 600GB                           | 1         | 1.1%    |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1.1%    |
| Seagate ST3500413AS 500GB                           | 1         | 1.1%    |
| Seagate ST3250820AS 250GB                           | 1         | 1.1%    |
| Seagate ST2000DL003-9VT166 2TB                      | 1         | 1.1%    |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1.1%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1.1%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor      | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| WDC         | 10        | 15     | 35.71%  |
| Seagate     | 8         | 11     | 28.57%  |
| Toshiba     | 5         | 7      | 17.86%  |
| HGST        | 3         | 4      | 10.71%  |
| WD MediaMax | 1         | 1      | 3.57%   |
| Hitachi     | 1         | 1      | 3.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 14     | 26.47%  |
| Kingston            | 6         | 9      | 17.65%  |
| SanDisk             | 3         | 6      | 8.82%   |
| WDC                 | 2         | 2      | 5.88%   |
| Crucial             | 2         | 10     | 5.88%   |
| Team                | 1         | 2      | 2.94%   |
| SPCC                | 1         | 1      | 2.94%   |
| Plextor             | 1         | 1      | 2.94%   |
| OCZ                 | 1         | 1      | 2.94%   |
| Netac               | 1         | 2      | 2.94%   |
| LITEON              | 1         | 1      | 2.94%   |
| Intenso             | 1         | 1      | 2.94%   |
| Intel               | 1         | 1      | 2.94%   |
| Hewlett-Packard     | 1         | 1      | 2.94%   |
| Gigabyte Technology | 1         | 2      | 2.94%   |
| ASMT                | 1         | 1      | 2.94%   |
| A-DATA Technology   | 1         | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 28        | 56     | 37.84%  |
| HDD     | 22        | 39     | 29.73%  |
| NVMe    | 21        | 27     | 28.38%  |
| Unknown | 2         | 2      | 2.7%    |
| MMC     | 1         | 1      | 1.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 39        | 92     | 60%     |
| NVMe | 21        | 27     | 32.31%  |
| SAS  | 4         | 5      | 6.15%   |
| MMC  | 1         | 1      | 1.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 40     | 50%     |
| 0.51-1.0   | 18        | 41     | 34.62%  |
| 1.01-2.0   | 6         | 11     | 11.54%  |
| 2.01-3.0   | 1         | 1      | 1.92%   |
| 4.01-10.0  | 1         | 2      | 1.92%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 17        | 31.48%  |
| 251-500        | 11        | 20.37%  |
| 1001-2000      | 11        | 20.37%  |
| 501-1000       | 6         | 11.11%  |
| 2001-3000      | 4         | 7.41%   |
| More than 3000 | 2         | 3.7%    |
| 51-100         | 2         | 3.7%    |
| 21-50          | 1         | 1.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 24        | 45.28%  |
| 21-50          | 6         | 11.32%  |
| 51-100         | 6         | 11.32%  |
| 251-500        | 5         | 9.43%   |
| 101-250        | 5         | 9.43%   |
| 501-1000       | 3         | 5.66%   |
| 1001-2000      | 2         | 3.77%   |
| More than 3000 | 1         | 1.89%   |
| 2001-3000      | 1         | 1.89%   |

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
| Detected | 32        | 69     | 53.33%  |
| Works    | 24        | 51     | 40%     |
| Malfunc  | 4         | 5      | 6.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 41        | 55.41%  |
| AMD                         | 7         | 9.46%   |
| Samsung Electronics         | 4         | 5.41%   |
| SK hynix                    | 3         | 4.05%   |
| Sandisk                     | 3         | 4.05%   |
| LSI Logic / Symbios Logic   | 3         | 4.05%   |
| Kingston Technology Company | 3         | 4.05%   |
| Phison Electronics          | 2         | 2.7%    |
| Micron Technology           | 2         | 2.7%    |
| Union Memory (Shenzhen)     | 1         | 1.35%   |
| Silicon Image               | 1         | 1.35%   |
| Seagate Technology          | 1         | 1.35%   |
| Micron/Crucial Technology   | 1         | 1.35%   |
| Broadcom / LSI              | 1         | 1.35%   |
| ASMedia Technology          | 1         | 1.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 6         | 7.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 6.25%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 5%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 5%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 3.75%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 3         | 3.75%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 3.75%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 2         | 2.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 2.5%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2         | 2.5%    |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 2.5%    |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                             | 2         | 2.5%    |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 2.5%    |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 2         | 2.5%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2         | 2.5%    |
| Intel 700 Series Chipset Family SATA AHCI Controller                           | 2         | 2.5%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 2.5%    |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                          | 1         | 1.25%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 1.25%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 1.25%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 1.25%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1         | 1.25%   |
| Seagate FireCuda 520/IronWolf 525 SSD                                          | 1         | 1.25%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 1         | 1.25%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.25%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 1.25%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.25%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 1.25%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                 | 1         | 1.25%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                        | 1         | 1.25%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2208 [Thunderbolt]                      | 1         | 1.25%   |
| Kingston Company NV1 NVMe SSD SM2263XT                                         | 1         | 1.25%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.25%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1         | 1.25%   |
| Intel SSD 660P Series                                                          | 1         | 1.25%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 1.25%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.25%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.25%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.25%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                   | 1         | 1.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 44        | 60.27%  |
| NVMe | 21        | 28.77%  |
| RAID | 6         | 8.22%   |
| SCSI | 1         | 1.37%   |
| IDE  | 1         | 1.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 43        | 82.69%  |
| AMD    | 9         | 17.31%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-1260P            | 2         | 3.85%   |
| Intel 12th Gen Core i5-12600K           | 2         | 3.85%   |
| Intel Xeon Silver 4215R CPU @ 3.20GHz   | 1         | 1.92%   |
| Intel Xeon Gold 6326 CPU @ 2.90GHz      | 1         | 1.92%   |
| Intel Xeon CPU X3440 @ 2.53GHz          | 1         | 1.92%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz      | 1         | 1.92%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1.92%   |
| Intel Core i7-5930K CPU @ 3.50GHz       | 1         | 1.92%   |
| Intel Core i7-4770K CPU @ 3.50GHz       | 1         | 1.92%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 1         | 1.92%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 1         | 1.92%   |
| Intel Core i7-2600K CPU @ 3.40GHz       | 1         | 1.92%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.92%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 1         | 1.92%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 1         | 1.92%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 1         | 1.92%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 1         | 1.92%   |
| Intel Core i5-4440 CPU @ 3.10GHz        | 1         | 1.92%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 1         | 1.92%   |
| Intel Core i5-4200M CPU @ 2.50GHz       | 1         | 1.92%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 1         | 1.92%   |
| Intel Core i5-3380M CPU @ 2.90GHz       | 1         | 1.92%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.92%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 1         | 1.92%   |
| Intel Core i5-2400S CPU @ 2.50GHz       | 1         | 1.92%   |
| Intel Core i5-10400F CPU @ 2.90GHz      | 1         | 1.92%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 1         | 1.92%   |
| Intel Core i5 CPU M 430 @ 2.27GHz       | 1         | 1.92%   |
| Intel Core i3-7100U CPU @ 2.40GHz       | 1         | 1.92%   |
| Intel Core i3-4010U CPU @ 1.70GHz       | 1         | 1.92%   |
| Intel Core i3-3217U CPU @ 1.80GHz       | 1         | 1.92%   |
| Intel Core i3-2130 CPU @ 3.40GHz        | 1         | 1.92%   |
| Intel Celeron J4125 CPU @ 2.00GHz       | 1         | 1.92%   |
| Intel 13th Gen Core i9-13900K           | 1         | 1.92%   |
| Intel 13th Gen Core i7-13700K           | 1         | 1.92%   |
| Intel 12th Gen Core i7-12800H           | 1         | 1.92%   |
| Intel 12th Gen Core i7-12700H           | 1         | 1.92%   |
| Intel 12th Gen Core i5-1240P            | 1         | 1.92%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 1         | 1.92%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz  | 1         | 1.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 14        | 26.92%  |
| Other             | 12        | 23.08%  |
| Intel Core i7     | 8         | 15.38%  |
| Intel Core i3     | 4         | 7.69%   |
| AMD Ryzen 5       | 3         | 5.77%   |
| Intel Xeon        | 2         | 3.85%   |
| AMD Ryzen 9       | 2         | 3.85%   |
| Intel Xeon Silver | 1         | 1.92%   |
| Intel Xeon Gold   | 1         | 1.92%   |
| Intel Celeron     | 1         | 1.92%   |
| AMD Ryzen 7       | 1         | 1.92%   |
| AMD Ryzen 3 PRO   | 1         | 1.92%   |
| AMD FX            | 1         | 1.92%   |
| AMD A10           | 1         | 1.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 17        | 32.69%  |
| 2      | 14        | 26.92%  |
| 6      | 6         | 11.54%  |
| 16     | 5         | 9.62%   |
| 12     | 3         | 5.77%   |
| 14     | 2         | 3.85%   |
| 10     | 2         | 3.85%   |
| 32     | 1         | 1.92%   |
| 24     | 1         | 1.92%   |
| 8      | 1         | 1.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 49        | 94.23%  |
| 2      | 3         | 5.77%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 42        | 80.77%  |
| 1      | 10        | 19.23%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 52        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 28.85%  |
| 0x906a3    | 5         | 9.62%   |
| 0x306c3    | 4         | 7.69%   |
| 0x306a9    | 4         | 7.69%   |
| 0x40651    | 3         | 5.77%   |
| 0x806ec    | 2         | 3.85%   |
| 0x406e3    | 2         | 3.85%   |
| 0x08600106 | 2         | 3.85%   |
| 0xa0671    | 1         | 1.92%   |
| 0xa0653    | 1         | 1.92%   |
| 0xa0652    | 1         | 1.92%   |
| 0x90672    | 1         | 1.92%   |
| 0x706e5    | 1         | 1.92%   |
| 0x706a8    | 1         | 1.92%   |
| 0x606a6    | 1         | 1.92%   |
| 0x306f2    | 1         | 1.92%   |
| 0x206a7    | 1         | 1.92%   |
| 0x20652    | 1         | 1.92%   |
| 0x0a201016 | 1         | 1.92%   |
| 0x08701021 | 1         | 1.92%   |
| 0x08701013 | 1         | 1.92%   |
| 0x06001119 | 1         | 1.92%   |
| 0x0600063d | 1         | 1.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 9         | 17.31%  |
| Alderlake Hybrid | 9         | 17.31%  |
| Zen 2            | 5         | 9.62%   |
| IvyBridge        | 5         | 9.62%   |
| SandyBridge      | 4         | 7.69%   |
| Skylake          | 3         | 5.77%   |
| KabyLake         | 3         | 5.77%   |
| Icelake          | 3         | 5.77%   |
| TigerLake        | 2         | 3.85%   |
| CometLake        | 2         | 3.85%   |
| Zen+             | 1         | 1.92%   |
| Zen 3            | 1         | 1.92%   |
| Westmere         | 1         | 1.92%   |
| Piledriver       | 1         | 1.92%   |
| Nehalem          | 1         | 1.92%   |
| Goldmont plus    | 1         | 1.92%   |
| Bulldozer        | 1         | 1.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 29        | 43.94%  |
| Nvidia                     | 21        | 31.82%  |
| AMD                        | 12        | 18.18%  |
| Matrox Electronics Systems | 3         | 4.55%   |
| ASPEED Technology          | 1         | 1.52%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 4         | 5.88%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 4         | 5.88%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3         | 4.41%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 3         | 4.41%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2         | 2.94%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 2         | 2.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 2.94%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 2         | 2.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 2.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2         | 2.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 1.47%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1         | 1.47%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1         | 1.47%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 1         | 1.47%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1         | 1.47%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1         | 1.47%   |
| Nvidia GP108M [GeForce MX330]                                               | 1         | 1.47%   |
| Nvidia GP108M [GeForce MX250]                                               | 1         | 1.47%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 1.47%   |
| Nvidia GP107M [GeForce MX350]                                               | 1         | 1.47%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1         | 1.47%   |
| Nvidia GM108M [GeForce MX110]                                               | 1         | 1.47%   |
| Nvidia GM107M [GeForce GTX 850M]                                            | 1         | 1.47%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1         | 1.47%   |
| Nvidia GK208M [GeForce GT 740M]                                             | 1         | 1.47%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1         | 1.47%   |
| Nvidia GK107M [GeForce GT 745M]                                             | 1         | 1.47%   |
| Nvidia GF108M [NVS 5400M]                                                   | 1         | 1.47%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 1         | 1.47%   |
| Nvidia GA103M [GeForce RTX 3080 Ti Mobile]                                  | 1         | 1.47%   |
| Matrox Electronics Systems MGA G200EV                                       | 1         | 1.47%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller    | 1         | 1.47%   |
| Matrox Electronics Systems G200eR2                                          | 1         | 1.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1         | 1.47%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 1         | 1.47%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1         | 1.47%   |
| Intel Iris Plus Graphics G7                                                 | 1         | 1.47%   |
| Intel HD Graphics 620                                                       | 1         | 1.47%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1         | 1.47%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 1         | 1.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 17        | 32.69%  |
| Intel + Nvidia  | 10        | 19.23%  |
| 1 x Nvidia      | 9         | 17.31%  |
| 1 x AMD         | 9         | 17.31%  |
| 1 x Matrox      | 2         | 3.85%   |
| 2 x AMD         | 1         | 1.92%   |
| Nvidia + Matrox | 1         | 1.92%   |
| Intel + AMD     | 1         | 1.92%   |
| 1 x ASPEED      | 1         | 1.92%   |
| AMD + Nvidia    | 1         | 1.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 42        | 79.25%  |
| Proprietary | 9         | 16.98%  |
| Unknown     | 2         | 3.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 50.91%  |
| 1.01-2.0   | 7         | 12.73%  |
| 0.01-0.5   | 5         | 9.09%   |
| 5.01-6.0   | 4         | 7.27%   |
| 3.01-4.0   | 4         | 7.27%   |
| 0.51-1.0   | 4         | 7.27%   |
| 8.01-16.0  | 3         | 5.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 7         | 12.5%   |
| LG Display              | 7         | 12.5%   |
| Chimei Innolux          | 5         | 8.93%   |
| Goldstar                | 4         | 7.14%   |
| Dell                    | 4         | 7.14%   |
| AU Optronics            | 4         | 7.14%   |
| ViewSonic               | 3         | 5.36%   |
| Iiyama                  | 2         | 3.57%   |
| Hewlett-Packard         | 2         | 3.57%   |
| BOE                     | 2         | 3.57%   |
| AOC                     | 2         | 3.57%   |
| Acer                    | 2         | 3.57%   |
| TMX                     | 1         | 1.79%   |
| SKY                     | 1         | 1.79%   |
| PANDA                   | 1         | 1.79%   |
| NXG                     | 1         | 1.79%   |
| LG Electronics          | 1         | 1.79%   |
| KVM                     | 1         | 1.79%   |
| HKC                     | 1         | 1.79%   |
| Gigabyte Technology     | 1         | 1.79%   |
| Eizo                    | 1         | 1.79%   |
| Chi Mei Optoelectronics | 1         | 1.79%   |
| CHD                     | 1         | 1.79%   |
| BenQ                    | 1         | 1.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Iiyama PL2888H IVM7106 1920x1080 620x340mm 27.8-inch                  | 2         | 3.33%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch         | 1         | 1.67%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch         | 1         | 1.67%   |
| ViewSonic PJ402D-2 HCD7B1D 1280x960                                   | 1         | 1.67%   |
| TMX LCD Monitor TMX1560 1920x1080 344x194mm 15.5-inch                 | 1         | 1.67%   |
| SKY 22X1-M225F SKY2150 1920x1080 476x268mm 21.5-inch                  | 1         | 1.67%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 607x345mm 27.5-inch     | 1         | 1.67%   |
| Samsung Electronics SyncMaster SAM05EB 1920x1080 597x336mm 27.0-inch  | 1         | 1.67%   |
| Samsung Electronics SMT22A350 SAM07A7 1920x1080 477x268mm 21.5-inch   | 1         | 1.67%   |
| Samsung Electronics SMEX2220 SAM0686 1920x1080 477x268mm 21.5-inch    | 1         | 1.67%   |
| Samsung Electronics S27C450 SAM09D9 1920x1080 598x336mm 27.0-inch     | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch | 1         | 1.67%   |
| PANDA LCD Monitor NCP0052 1920x1080 309x174mm 14.0-inch               | 1         | 1.67%   |
| NXG MIRAI DML-517 NXG138B 1280x1024 338x270mm 17.0-inch               | 1         | 1.67%   |
| LG Electronics LCD Monitor LG FULL HD                                 | 1         | 1.67%   |
| LG Display LCD Monitor LGD068A 1920x1080 309x174mm 14.0-inch          | 1         | 1.67%   |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch          | 1         | 1.67%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 1.67%   |
| LG Display LCD Monitor LGD046C 1920x1080 380x210mm 17.1-inch          | 1         | 1.67%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch           | 1         | 1.67%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 1         | 1.67%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 1         | 1.67%   |
| KVM LCD Monitor191919 KVM4308 1280x1024 376x301mm 19.0-inch           | 1         | 1.67%   |
| HKC 24N1 HKC2413 1920x1080 527x296mm 23.8-inch                        | 1         | 1.67%   |
| Hewlett-Packard L185x HWP298C 1366x768 410x230mm 18.5-inch            | 1         | 1.67%   |
| Hewlett-Packard 2159 HWP282C 1920x1080 479x269mm 21.6-inch            | 1         | 1.67%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 1         | 1.67%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 1         | 1.67%   |
| Goldstar 27GL650F GSM5B70 1920x1080 531x298mm 24.0-inch               | 1         | 1.67%   |
| Goldstar 22EA53 GSM59A6 1920x1080 477x268mm 21.5-inch                 | 1         | 1.67%   |
| Gigabyte Technology G34WQC A GBT3403 3440x1440 797x334mm 34.0-inch    | 1         | 1.67%   |
| Eizo EV2450 ENC2532 1920x1080 528x297mm 23.9-inch                     | 1         | 1.67%   |
| Dell U2720Q DEL41B0 3840x2160 597x336mm 27.0-inch                     | 1         | 1.67%   |
| Dell U2718Q DELA0E9 3840x2160 609x349mm 27.6-inch                     | 1         | 1.67%   |
| Dell U2520D DELA150 2560x1440 553x311mm 25.0-inch                     | 1         | 1.67%   |
| Dell U2520D DELA14E 2560x1440 553x311mm 25.0-inch                     | 1         | 1.67%   |
| Dell U2520D DELA14C 2560x1440 553x311mm 25.0-inch                     | 1         | 1.67%   |
| Dell SE2219H DELF10E 1920x1080 476x268mm 21.5-inch                    | 1         | 1.67%   |
| Dell P2418HT DEL4113 1920x1080 527x296mm 23.8-inch                    | 1         | 1.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 29        | 54.72%  |
| 1366x768 (WXGA)    | 7         | 13.21%  |
| 3840x2160 (4K)     | 4         | 7.55%   |
| 2560x1440 (QHD)    | 2         | 3.77%   |
| 1600x900 (HD+)     | 2         | 3.77%   |
| 1280x1024 (SXGA)   | 2         | 3.77%   |
| 3840x1080          | 1         | 1.89%   |
| 3440x1440          | 1         | 1.89%   |
| 3200x2000          | 1         | 1.89%   |
| 1920x1200 (WUXGA)  | 1         | 1.89%   |
| 1680x1050 (WSXGA+) | 1         | 1.89%   |
| 1280x960           | 1         | 1.89%   |
| Unknown            | 1         | 1.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 14      | 10        | 17.54%  |
| 15      | 9         | 15.79%  |
| 27      | 8         | 14.04%  |
| 21      | 8         | 14.04%  |
| 24      | 5         | 8.77%   |
| 23      | 4         | 7.02%   |
| 17      | 2         | 3.51%   |
| Unknown | 2         | 3.51%   |
| 84      | 1         | 1.75%   |
| 38      | 1         | 1.75%   |
| 34      | 1         | 1.75%   |
| 25      | 1         | 1.75%   |
| 22      | 1         | 1.75%   |
| 19      | 1         | 1.75%   |
| 18      | 1         | 1.75%   |
| 16      | 1         | 1.75%   |
| 13      | 1         | 1.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 21        | 38.18%  |
| 501-600     | 12        | 21.82%  |
| 401-500     | 10        | 18.18%  |
| 601-700     | 4         | 7.27%   |
| 351-400     | 3         | 5.45%   |
| Unknown     | 2         | 3.64%   |
| 801-900     | 1         | 1.82%   |
| 701-800     | 1         | 1.82%   |
| 1501-2000   | 1         | 1.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 39        | 82.98%  |
| 16/10   | 3         | 6.38%   |
| 5/4     | 2         | 4.26%   |
| 4/3     | 1         | 2.13%   |
| 21/9    | 1         | 2.13%   |
| Unknown | 1         | 2.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 13        | 23.64%  |
| 81-90          | 11        | 20%     |
| 101-110        | 9         | 16.36%  |
| 301-350        | 8         | 14.55%  |
| 251-300        | 3         | 5.45%   |
| 151-200        | 2         | 3.64%   |
| 141-150        | 2         | 3.64%   |
| Unknown        | 2         | 3.64%   |
| More than 1000 | 1         | 1.82%   |
| 351-500        | 1         | 1.82%   |
| 121-130        | 1         | 1.82%   |
| 111-120        | 1         | 1.82%   |
| 501-1000       | 1         | 1.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 18        | 32.73%  |
| 121-160       | 16        | 29.09%  |
| 101-120       | 16        | 29.09%  |
| 161-240       | 2         | 3.64%   |
| Unknown       | 2         | 3.64%   |
| More than 240 | 1         | 1.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 37        | 69.81%  |
| 2     | 9         | 16.98%  |
| 0     | 5         | 9.43%   |
| 4     | 1         | 1.89%   |
| 3     | 1         | 1.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 33        | 38.82%  |
| Realtek Semiconductor             | 23        | 27.06%  |
| Qualcomm Atheros                  | 11        | 12.94%  |
| Broadcom                          | 5         | 5.88%   |
| Xiaomi                            | 1         | 1.18%   |
| U-Blox                            | 1         | 1.18%   |
| TP-Link                           | 1         | 1.18%   |
| Mellanox Technologies             | 1         | 1.18%   |
| MediaTek                          | 1         | 1.18%   |
| IBM                               | 1         | 1.18%   |
| Ericsson Business Mobile Networks | 1         | 1.18%   |
| DisplayLink                       | 1         | 1.18%   |
| Dell                              | 1         | 1.18%   |
| Ceton Technologies                | 1         | 1.18%   |
| ASUSTek Computer                  | 1         | 1.18%   |
| ASIX Electronics                  | 1         | 1.18%   |
| Aquantia                          | 1         | 1.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 16.5%   |
| Intel Ethernet Controller I225-V                                  | 5         | 4.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 4.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 3.88%   |
| Intel Wireless 7260                                               | 4         | 3.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 2.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 1.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 1.94%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 1.94%   |
| Intel Wireless 8260                                               | 2         | 1.94%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 1.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.94%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 1.94%   |
| Intel 700 Series Chipset Family Wi-Fi                             | 2         | 1.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.97%   |
| U-Blox [u-blox 8]                                                 | 1         | 0.97%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 0.97%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.97%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.97%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.97%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.97%   |
| Mellanox MT27800 Family [ConnectX-5]                              | 1         | 0.97%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 0.97%   |
| Intel Wireless-AC 9260                                            | 1         | 0.97%   |
| Intel Wireless 8265 / 8275                                        | 1         | 0.97%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 0.97%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 0.97%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.97%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.97%   |
| Intel Ethernet Controller XL710 for 40GbE QSFP+                   | 1         | 0.97%   |
| Intel Ethernet Controller X710 for 10GBASE-T                      | 1         | 0.97%   |
| Intel Ethernet Controller I226-V                                  | 1         | 0.97%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.97%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.97%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.97%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 24        | 57.14%  |
| Qualcomm Atheros      | 10        | 23.81%  |
| Realtek Semiconductor | 4         | 9.52%   |
| TP-Link               | 1         | 2.38%   |
| MediaTek              | 1         | 2.38%   |
| Broadcom              | 1         | 2.38%   |
| ASUSTek Computer      | 1         | 2.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                               | 5         | 11.9%   |
| Intel Wireless 7260                                            | 4         | 9.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 7.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 4.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 4.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 4.76%   |
| Intel Wireless 8260                                            | 2         | 4.76%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 4.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 4.76%   |
| Intel 700 Series Chipset Family Wi-Fi                          | 2         | 4.76%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1         | 2.38%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 2.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 2.38%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 2.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 2.38%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1         | 2.38%   |
| Intel Wireless-AC 9260                                         | 1         | 2.38%   |
| Intel Wireless 8265 / 8275                                     | 1         | 2.38%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 2.38%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 2.38%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 2.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 2.38%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 2.38%   |
| ASUS 802.11ac NIC                                              | 1         | 2.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 21        | 37.5%   |
| Intel                 | 21        | 37.5%   |
| Broadcom              | 4         | 7.14%   |
| Qualcomm Atheros      | 2         | 3.57%   |
| Xiaomi                | 1         | 1.79%   |
| Mellanox Technologies | 1         | 1.79%   |
| IBM                   | 1         | 1.79%   |
| DisplayLink           | 1         | 1.79%   |
| Dell                  | 1         | 1.79%   |
| Ceton Technologies    | 1         | 1.79%   |
| ASIX Electronics      | 1         | 1.79%   |
| Aquantia              | 1         | 1.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 17        | 28.81%  |
| Intel Ethernet Controller I225-V                                      | 5         | 8.47%   |
| Realtek RTL8125 2.5GbE Controller                                     | 4         | 6.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 3         | 5.08%   |
| Intel 82574L Gigabit Network Connection                               | 2         | 3.39%   |
| Xiaomi Mi/Redmi series (RNDIS)                                        | 1         | 1.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                 | 1         | 1.69%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                | 1         | 1.69%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                 | 1         | 1.69%   |
| Mellanox MT27800 Family [ConnectX-5]                                  | 1         | 1.69%   |
| Intel I211 Gigabit Network Connection                                 | 1         | 1.69%   |
| Intel I210 Gigabit Network Connection                                 | 1         | 1.69%   |
| Intel Ethernet Controller XL710 for 40GbE QSFP+                       | 1         | 1.69%   |
| Intel Ethernet Controller X710 for 10GBASE-T                          | 1         | 1.69%   |
| Intel Ethernet Controller I226-V                                      | 1         | 1.69%   |
| Intel Ethernet Connection I219-V                                      | 1         | 1.69%   |
| Intel Ethernet Connection I219-LM                                     | 1         | 1.69%   |
| Intel Ethernet Connection I218-V                                      | 1         | 1.69%   |
| Intel Ethernet Connection I218-LM                                     | 1         | 1.69%   |
| Intel Ethernet Connection I217-V                                      | 1         | 1.69%   |
| Intel Ethernet Connection (4) I219-V                                  | 1         | 1.69%   |
| Intel Ethernet Connection (2) I218-V                                  | 1         | 1.69%   |
| Intel 82579V Gigabit Network Connection                               | 1         | 1.69%   |
| IBM RNDIS/CDC ETHER                                                   | 1         | 1.69%   |
| DisplayLink Plugable UD-6950PDZ                                       | 1         | 1.69%   |
| Dell iDRAC Virtual NIC                                                | 1         | 1.69%   |
| Ceton InfiniTV Network                                                | 1         | 1.69%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                     | 1         | 1.69%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 1         | 1.69%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                       | 1         | 1.69%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1         | 1.69%   |
| ASIX AX88179 Gigabit Ethernet                                         | 1         | 1.69%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 1         | 1.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 46        | 52.27%  |
| WiFi     | 40        | 45.45%  |
| Modem    | 2         | 2.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 26        | 52%     |
| WiFi     | 24        | 48%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 34        | 65.38%  |
| 1     | 13        | 25%     |
| 3     | 3         | 5.77%   |
| 7     | 1         | 1.92%   |
| 4     | 1         | 1.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 37        | 71.15%  |
| Yes  | 15        | 28.85%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 58.33%  |
| Qualcomm Atheros Communications | 4         | 11.11%  |
| Lite-On Technology              | 3         | 8.33%   |
| Realtek Semiconductor           | 2         | 5.56%   |
| Broadcom                        | 2         | 5.56%   |
| MediaTek                        | 1         | 2.78%   |
| IMC Networks                    | 1         | 2.78%   |
| Cambridge Silicon Radio         | 1         | 2.78%   |
| ASUSTek Computer                | 1         | 2.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 22.22%  |
| Intel Bluetooth Device                              | 8         | 22.22%  |
| Realtek Bluetooth Radio                             | 2         | 5.56%   |
| Lite-On Bluetooth Device                            | 2         | 5.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 5.56%   |
| Intel AX200 Bluetooth                               | 2         | 5.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.78%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 2.78%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.78%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 2.78%   |
| MediaTek Wireless_Device                            | 1         | 2.78%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 2.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.78%   |
| IMC Networks Bluetooth Device                       | 1         | 2.78%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.78%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 38        | 53.52%  |
| Nvidia                   | 14        | 19.72%  |
| AMD                      | 14        | 19.72%  |
| SteelSeries ApS          | 3         | 4.23%   |
| Micro Star International | 1         | 1.41%   |
| Anlya.cn                 | 1         | 1.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 6.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 6.02%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 4.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 4.82%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 4.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 3.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 3.61%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 3.61%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 3.61%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 3.61%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 3.61%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 2.41%   |
| Nvidia TU102 High Definition Audio Controller                              | 2         | 2.41%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 2.41%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 2.41%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 2.41%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 2         | 2.41%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 2.41%   |
| SteelSeries ApS SteelSeries Siberia 800                                    | 1         | 1.2%    |
| SteelSeries ApS SteelSeries GameDAC                                        | 1         | 1.2%    |
| SteelSeries ApS Arctis Nova Pro Wireless                                   | 1         | 1.2%    |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.2%    |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 1.2%    |
| Nvidia GM200 High Definition Audio                                         | 1         | 1.2%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1.2%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.2%    |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.2%    |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 1.2%    |
| Nvidia Audio device                                                        | 1         | 1.2%    |
| Micro Star International USB Audio                                         | 1         | 1.2%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.2%    |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1         | 1.2%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.2%    |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.2%    |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.2%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.2%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 1.2%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.2%    |
| Anlya.cn AB13X USB Audio                                                   | 1         | 1.2%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 32.26%  |
| SK hynix            | 5         | 16.13%  |
| G.Skill             | 3         | 9.68%   |
| Crucial             | 3         | 9.68%   |
| Corsair             | 3         | 9.68%   |
| Kingston            | 2         | 6.45%   |
| Unknown (ABCD)      | 1         | 3.23%   |
| Team                | 1         | 3.23%   |
| Smart Brazil        | 1         | 3.23%   |
| SHARETRONIC         | 1         | 3.23%   |
| A-DATA Technology   | 1         | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1         | 3.13%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s             | 1         | 3.13%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s   | 1         | 3.13%   |
| SK hynix RAM Module 4GB DIMM DDR3 1600MT/s                     | 1         | 3.13%   |
| SK hynix RAM HMT31GR7BFR4A-H9 8GB DIMM DDR3 1333MT/s           | 1         | 3.13%   |
| SK hynix RAM HMT125S6BFR8C-G7 2048MB SODIMM DDR3 1067MT/s      | 1         | 3.13%   |
| SK hynix RAM HMA84GR7DJR4N-XN 32GB DIMM DDR4 3200MT/s          | 1         | 3.13%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s        | 1         | 3.13%   |
| SHARETRONIC RAM Module 4GB SODIMM DDR3 800MT/s                 | 1         | 3.13%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                    | 1         | 3.13%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s          | 1         | 3.13%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s       | 1         | 3.13%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 3.13%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 3.13%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 1         | 3.13%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s          | 1         | 3.13%   |
| Samsung RAM M393B1K70DH0-YH9 8GB DIMM DDR3 1333MT/s            | 1         | 3.13%   |
| Samsung RAM M393A4K40EB3-CWE 32GB DIMM DDR4 3200MT/s           | 1         | 3.13%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s            | 1         | 3.13%   |
| Samsung RAM K4UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s   | 1         | 3.13%   |
| Kingston RAM 99U5471-034.A00LF 4GB DIMM DDR3 1600MT/s          | 1         | 3.13%   |
| Kingston RAM 9905417-083.A00G 4GB SODIMM DDR3 1600MT/s         | 1         | 3.13%   |
| G.Skill RAM F5-5600J3036D32G 32GB DIMM DDR5 5600MT/s           | 1         | 3.13%   |
| G.Skill RAM F4-3600C18-32GTZR 32GB DIMM DDR4 3600MT/s          | 1         | 3.13%   |
| G.Skill RAM F3-1600C9-8GRSL 8GB SODIMM DDR3 1600MT/s           | 1         | 3.13%   |
| Crucial RAM CT8G4SFS824A.M8FD 8GB SODIMM DDR4 2400MT/s         | 1         | 3.13%   |
| Crucial RAM CT16G4DFD824A.C16FBD 16GB DIMM DDR4 2933MT/s       | 1         | 3.13%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s          | 1         | 3.13%   |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s        | 1         | 3.13%   |
| Corsair RAM CMK64GX4M2Z4000C18 32GB DIMM DDR4 4000MT/s         | 1         | 3.13%   |
| Corsair RAM CMK128GX4M8A2666C16 16GB DIMM DDR4 2133MT/s        | 1         | 3.13%   |
| A-DATA RAM Module 32GB SODIMM DDR4 3200MT/s                    | 1         | 3.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 13        | 46.43%  |
| DDR3   | 12        | 42.86%  |
| LPDDR4 | 2         | 7.14%   |
| DDR5   | 1         | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 14        | 50%     |
| SODIMM       | 12        | 42.86%  |
| Row Of Chips | 2         | 7.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 13        | 43.33%  |
| 32768 | 6         | 20%     |
| 4096  | 6         | 20%     |
| 16384 | 4         | 13.33%  |
| 2048  | 1         | 3.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 7         | 24.14%  |
| 3200  | 5         | 17.24%  |
| 2667  | 2         | 6.9%    |
| 2400  | 2         | 6.9%    |
| 2133  | 2         | 6.9%    |
| 1800  | 2         | 6.9%    |
| 5600  | 1         | 3.45%   |
| 4267  | 1         | 3.45%   |
| 4000  | 1         | 3.45%   |
| 3600  | 1         | 3.45%   |
| 2933  | 1         | 3.45%   |
| 1334  | 1         | 3.45%   |
| 1333  | 1         | 3.45%   |
| 1067  | 1         | 3.45%   |
| 800   | 1         | 3.45%   |

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
| Chicony Electronics                    | 5         | 19.23%  |
| IMC Networks                           | 3         | 11.54%  |
| Bison Electronics                      | 3         | 11.54%  |
| Syntek                                 | 2         | 7.69%   |
| Sunplus Innovation Technology          | 2         | 7.69%   |
| Realtek Semiconductor                  | 2         | 7.69%   |
| Logitech                               | 2         | 7.69%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 7.69%   |
| Silicon Motion                         | 1         | 3.85%   |
| Microdia                               | 1         | 3.85%   |
| Luxvisions Innotech Limited            | 1         | 3.85%   |
| Apple                                  | 1         | 3.85%   |
| Acer                                   | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                            | 2         | 7.69%   |
| Sunplus WEBCAM ESSENTIELB W1                        | 2         | 7.69%   |
| Silicon Motion WebCam SC-13HDL11939N                | 1         | 3.85%   |
| Realtek Lenovo EasyCamera                           | 1         | 3.85%   |
| Realtek Integrated_Webcam_HD                        | 1         | 3.85%   |
| Microdia USB Live camera                            | 1         | 3.85%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 3.85%   |
| Logitech Webcam C270                                | 1         | 3.85%   |
| Logitech C922 Pro Stream Webcam                     | 1         | 3.85%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 3.85%   |
| IMC Networks Integrated RGB Camera                  | 1         | 3.85%   |
| IMC Networks Integrated Camera                      | 1         | 3.85%   |
| Chicony Thinkpad T430 camera                        | 1         | 3.85%   |
| Chicony Integrated Camera                           | 1         | 3.85%   |
| Chicony HD WebCam (Asus N-series)                   | 1         | 3.85%   |
| Chicony HD WebCam                                   | 1         | 3.85%   |
| Chicony Acer CrystalEye Webcam                      | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 3.85%   |
| Bison Lenovo Integrated Webcam                      | 1         | 3.85%   |
| Bison Integrated Camera                             | 1         | 3.85%   |
| Bison HD Webcam                                     | 1         | 3.85%   |
| Apple iPhone 5/5C/5S/6/SE                           | 1         | 3.85%   |
| Acer Integrated Camera                              | 1         | 3.85%   |

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
| 0     | 35        | 63.64%  |
| 1     | 14        | 25.45%  |
| 2     | 4         | 7.27%   |
| 4     | 1         | 1.82%   |
| 3     | 1         | 1.82%   |

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

