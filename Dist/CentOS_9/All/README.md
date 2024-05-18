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

Total: 86

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [994aae0769](https://linux-hardware.org/?probe=994aae0769) | Apr 21, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [e26cecc411](https://linux-hardware.org/?probe=e26cecc411) | Apr 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [05372f86e5](https://linux-hardware.org/?probe=05372f86e5) | Apr 10, 2024 |
| Lenovo        | ThinkPad X390 20Q00039CD    | Notebook    | [9e8475784d](https://linux-hardware.org/?probe=9e8475784d) | Apr 05, 2024 |
| Micro Comp... | Venus series                | Notebook    | [ec0a83d39a](https://linux-hardware.org/?probe=ec0a83d39a) | Mar 27, 2024 |
| Dell          | 02C2CP A04                  | Server      | [2eb0ecb18c](https://linux-hardware.org/?probe=2eb0ecb18c) | Mar 15, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [0bea57057c](https://linux-hardware.org/?probe=0bea57057c) | Mar 13, 2024 |
| Notebook      | P377SM-A                    | Notebook    | [c073b6897b](https://linux-hardware.org/?probe=c073b6897b) | Mar 05, 2024 |
| Dell          | Precision 5560              | Notebook    | [e500714178](https://linux-hardware.org/?probe=e500714178) | Feb 22, 2024 |
| Dell          | Precision 5520              | Notebook    | [47f7336949](https://linux-hardware.org/?probe=47f7336949) | Jan 30, 2024 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [5a711c0ff0](https://linux-hardware.org/?probe=5a711c0ff0) | Jan 20, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [6c329db1cf](https://linux-hardware.org/?probe=6c329db1cf) | Jan 18, 2024 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [7adc9b4d41](https://linux-hardware.org/?probe=7adc9b4d41) | Jan 06, 2024 |
| Dell          | G5 5505                     | Notebook    | [fd284cda8a](https://linux-hardware.org/?probe=fd284cda8a) | Jan 04, 2024 |
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

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.14.0-86.el9.x86_64      | 3         | 4.17%   |
| 5.14.0-391.el9.x86_64     | 3         | 4.17%   |
| 5.14.0-202.el9.x86_64     | 3         | 4.17%   |
| 5.14.0-134.el9.x86_64     | 3         | 4.17%   |
| 5.14.0-432.el9.x86_64     | 2         | 2.78%   |
| 5.14.0-427.el9.x86_64     | 2         | 2.78%   |
| 5.14.0-407.el9.x86_64     | 2         | 2.78%   |
| 5.14.0-362.el9.x86_64     | 2         | 2.78%   |
| 5.14.0-325.el9.x86_64     | 2         | 2.78%   |
| 5.14.0-319.el9.x86_64     | 2         | 2.78%   |
| 5.14.0-214.el9.x86_64     | 2         | 2.78%   |
| 5.14.0-183.el9.x86_64     | 2         | 2.78%   |
| 5.14.0-171.el9.x86_64     | 2         | 2.78%   |
| 5.14.0-148.el9.x86_64     | 2         | 2.78%   |
| 6.1.8-1.el9.elrepo.x86_64 | 1         | 1.39%   |
| 6.1.1                     | 1         | 1.39%   |
| 5.17.2-lqx3.0.el9.x86_64  | 1         | 1.39%   |
| 5.14.0-78.el9.x86_64      | 1         | 1.39%   |
| 5.14.0-71.el9.x86_64      | 1         | 1.39%   |
| 5.14.0-66.el9.x86_64      | 1         | 1.39%   |
| 5.14.0-52.el9.x86_64      | 1         | 1.39%   |
| 5.14.0-44.el9.x86_64      | 1         | 1.39%   |
| 5.14.0-437.el9.x86_64     | 1         | 1.39%   |
| 5.14.0-435.el9.x86_64     | 1         | 1.39%   |
| 5.14.0-425.el9.x86_64     | 1         | 1.39%   |
| 5.14.0-419.el9.x86_64     | 1         | 1.39%   |
| 5.14.0-410.el9.x86_64     | 1         | 1.39%   |
| 5.14.0-402.el9.x86_64     | 1         | 1.39%   |
| 5.14.0-383.el9.x86_64     | 1         | 1.39%   |
| 5.14.0-375.el9.x86_64     | 1         | 1.39%   |
| 5.14.0-373.el9.x86_64     | 1         | 1.39%   |
| 5.14.0-352.el9.x86_64     | 1         | 1.39%   |
| 5.14.0-350.el9.x86_64     | 1         | 1.39%   |
| 5.14.0-344.el9.x86_64     | 1         | 1.39%   |
| 5.14.0-340.el9.x86_64     | 1         | 1.39%   |
| 5.14.0-333.el9.x86_64     | 1         | 1.39%   |
| 5.14.0-316.el9.x86_64     | 1         | 1.39%   |
| 5.14.0-305.el9.x86_64     | 1         | 1.39%   |
| 5.14.0-302.el9.x86_64     | 1         | 1.39%   |
| 5.14.0-299.el9.x86_64     | 1         | 1.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 61        | 93.85%  |
| 6.1.8   | 1         | 1.54%   |
| 6.1.1   | 1         | 1.54%   |
| 5.17.2  | 1         | 1.54%   |
| 4.18.0  | 1         | 1.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 61        | 93.85%  |
| 6.1     | 2         | 3.08%   |
| 5.17    | 1         | 1.54%   |
| 4.18    | 1         | 1.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 64        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 54        | 84.38%  |
| KDE5          | 4         | 6.25%   |
| GNOME Classic | 3         | 4.69%   |
| Unknown       | 3         | 4.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 41        | 63.08%  |
| X11     | 21        | 32.31%  |
| Tty     | 2         | 3.08%   |
| Unknown | 1         | 1.54%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 35        | 53.85%  |
| GDM     | 26        | 40%     |
| SDDM    | 2         | 3.08%   |
| LightDM | 2         | 3.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 39        | 60.94%  |
| ru_RU   | 3         | 4.69%   |
| de_DE   | 3         | 4.69%   |
| zh_CN   | 2         | 3.13%   |
| pt_BR   | 2         | 3.13%   |
| ja_JP   | 2         | 3.13%   |
| it_IT   | 2         | 3.13%   |
| en_GB   | 2         | 3.13%   |
| en_AU   | 2         | 3.13%   |
| sv_SE   | 1         | 1.56%   |
| ru_UA   | 1         | 1.56%   |
| fr_FR   | 1         | 1.56%   |
| fr_CA   | 1         | 1.56%   |
| en_IN   | 1         | 1.56%   |
| C       | 1         | 1.56%   |
| Unknown | 1         | 1.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 49        | 75.38%  |
| BIOS | 16        | 24.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 59        | 92.19%  |
| Ext4 | 5         | 7.81%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 32        | 48.48%  |
| GPT     | 25        | 37.88%  |
| MBR     | 9         | 13.64%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 56        | 86.15%  |
| Yes       | 9         | 13.85%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 52        | 78.79%  |
| Yes       | 14        | 21.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Lenovo                           | 12        | 18.75%  |
| ASUSTek Computer                 | 12        | 18.75%  |
| Dell                             | 8         | 12.5%   |
| MSI                              | 4         | 6.25%   |
| Intel                            | 4         | 6.25%   |
| Hewlett-Packard                  | 4         | 6.25%   |
| Acer                             | 4         | 6.25%   |
| Gigabyte Technology              | 3         | 4.69%   |
| Timi                             | 2         | 3.13%   |
| Zvezda                           | 1         | 1.56%   |
| SHANGZHAOYUAN                    | 1         | 1.56%   |
| Samsung Electronics              | 1         | 1.56%   |
| Razer                            | 1         | 1.56%   |
| Notebook                         | 1         | 1.56%   |
| Micro Computer (HK) Tech Limited | 1         | 1.56%   |
| IP3 Tech                         | 1         | 1.56%   |
| IBM                              | 1         | 1.56%   |
| Gateway                          | 1         | 1.56%   |
| Colorful Technology              | 1         | 1.56%   |
| AZW                              | 1         | 1.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| ASUS PRIME H670-PLUS D4                     | 2         | 3.13%   |
| Zvezda Altair Z                             | 1         | 1.56%   |
| Timi RedmiBook 16                           | 1         | 1.56%   |
| Timi Mi NoteBook Horizon Edition 14         | 1         | 1.56%   |
| SHANGZHAOYUAN B85M-PRO V1.1                 | 1         | 1.56%   |
| Samsung 355V4C/356V4C/3445VC/3545VC         | 1         | 1.56%   |
| Razer Blade 15 (2022) - RZ09-0421           | 1         | 1.56%   |
| Notebook P377SM-A                           | 1         | 1.56%   |
| MSI MS-7E01                                 | 1         | 1.56%   |
| MSI MS-7D86                                 | 1         | 1.56%   |
| MSI MS-7B79                                 | 1         | 1.56%   |
| MSI Katana GF76 12UE                        | 1         | 1.56%   |
| Micro (HK) Tech Limited Venus series        | 1         | 1.56%   |
| Lenovo Yoga S740-14IIL 81RS                 | 1         | 1.56%   |
| Lenovo V15 G2 ITL 82KB                      | 1         | 1.56%   |
| Lenovo ThinkPad X390 20Q00039CD             | 1         | 1.56%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBCTO1WW | 1         | 1.56%   |
| Lenovo ThinkPad T460s 20FAS5WX00            | 1         | 1.56%   |
| Lenovo ThinkPad T430 2349DG5                | 1         | 1.56%   |
| Lenovo ThinkPad T430 2347DE9                | 1         | 1.56%   |
| Lenovo ThinkPad L14 Gen 1 20U5S0NT00        | 1         | 1.56%   |
| Lenovo Legion 5P 15IMH05H 82AW              | 1         | 1.56%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 1         | 1.56%   |
| Lenovo G580 20150                           | 1         | 1.56%   |
| Lenovo G410 20237                           | 1         | 1.56%   |
| IP3 Tech HeroBox                            | 1         | 1.56%   |
| Intel NUC7i3BNK                             | 1         | 1.56%   |
| Intel NUC12WSHi7                            | 1         | 1.56%   |
| Intel NUC12WSHi5                            | 1         | 1.56%   |
| Intel D34010WYK H14771-303                  | 1         | 1.56%   |
| IBM System x3250 M3 -[425242G]              | 1         | 1.56%   |
| HP Spectre x360 Convertible 15-df0xxx       | 1         | 1.56%   |
| HP Pavilion Gaming Laptop 15-ec0xxx         | 1         | 1.56%   |
| HP EliteBook 840 G3                         | 1         | 1.56%   |
| HP EliteBook 840 G1                         | 1         | 1.56%   |
| Gigabyte X99-UD4-CF                         | 1         | 1.56%   |
| Gigabyte B550M DS3H                         | 1         | 1.56%   |
| Gigabyte 970A-DS3P                          | 1         | 1.56%   |
| Gateway SX2865                              | 1         | 1.56%   |
| Dell Vostro 5402                            | 1         | 1.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 6         | 9.38%   |
| Dell PowerEdge                | 3         | 4.69%   |
| HP EliteBook                  | 2         | 3.13%   |
| Dell Precision                | 2         | 3.13%   |
| ASUS ROG                      | 2         | 3.13%   |
| ASUS PRIME                    | 2         | 3.13%   |
| Acer Aspire                   | 2         | 3.13%   |
| Zvezda Altair                 | 1         | 1.56%   |
| Timi RedmiBook                | 1         | 1.56%   |
| Timi Mi                       | 1         | 1.56%   |
| SHANGZHAOYUAN B85M-PRO        | 1         | 1.56%   |
| Samsung 355V4C                | 1         | 1.56%   |
| Razer Blade                   | 1         | 1.56%   |
| Notebook P377SM-A             | 1         | 1.56%   |
| MSI MS-7E01                   | 1         | 1.56%   |
| MSI MS-7D86                   | 1         | 1.56%   |
| MSI MS-7B79                   | 1         | 1.56%   |
| MSI Katana                    | 1         | 1.56%   |
| Micro (HK) Tech Limited Venus | 1         | 1.56%   |
| Lenovo Yoga                   | 1         | 1.56%   |
| Lenovo V15                    | 1         | 1.56%   |
| Lenovo Legion                 | 1         | 1.56%   |
| Lenovo IdeaPad                | 1         | 1.56%   |
| Lenovo G580                   | 1         | 1.56%   |
| Lenovo G410                   | 1         | 1.56%   |
| IP3 Tech HeroBox              | 1         | 1.56%   |
| Intel NUC7i3BNK               | 1         | 1.56%   |
| Intel NUC12WSHi7              | 1         | 1.56%   |
| Intel NUC12WSHi5              | 1         | 1.56%   |
| Intel D34010WYK               | 1         | 1.56%   |
| IBM System                    | 1         | 1.56%   |
| HP Spectre                    | 1         | 1.56%   |
| HP Pavilion                   | 1         | 1.56%   |
| Gigabyte X99-UD4-CF           | 1         | 1.56%   |
| Gigabyte B550M                | 1         | 1.56%   |
| Gigabyte 970A-DS3P            | 1         | 1.56%   |
| Gateway SX2865                | 1         | 1.56%   |
| Dell Vostro                   | 1         | 1.56%   |
| Dell OptiPlex                 | 1         | 1.56%   |
| Dell G5                       | 1         | 1.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 11        | 17.19%  |
| 2022 | 8         | 12.5%   |
| 2021 | 8         | 12.5%   |
| 2020 | 8         | 12.5%   |
| 2019 | 7         | 10.94%  |
| 2012 | 4         | 6.25%   |
| 2023 | 3         | 4.69%   |
| 2018 | 3         | 4.69%   |
| 2014 | 3         | 4.69%   |
| 2011 | 3         | 4.69%   |
| 2016 | 2         | 3.13%   |
| 2017 | 1         | 1.56%   |
| 2015 | 1         | 1.56%   |
| 2010 | 1         | 1.56%   |
| 2009 | 1         | 1.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 32        | 50%     |
| Desktop     | 21        | 32.81%  |
| Mini pc     | 5         | 7.81%   |
| Server      | 5         | 7.81%   |
| Convertible | 1         | 1.56%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 59        | 92.19%  |
| Enabled  | 5         | 7.81%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 64        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 21        | 32.81%  |
| 8.01-16.0       | 15        | 23.44%  |
| 32.01-64.0      | 10        | 15.63%  |
| 64.01-256.0     | 8         | 12.5%   |
| More than 256.0 | 3         | 4.69%   |
| 3.01-4.0        | 3         | 4.69%   |
| 24.01-32.0      | 2         | 3.13%   |
| 16.01-24.0      | 2         | 3.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 24        | 35.29%  |
| 3.01-4.0   | 16        | 23.53%  |
| 4.01-8.0   | 12        | 17.65%  |
| 8.01-16.0  | 6         | 8.82%   |
| 1.01-2.0   | 5         | 7.35%   |
| 16.01-24.0 | 3         | 4.41%   |
| 0.51-1.0   | 2         | 2.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 33        | 51.56%  |
| 2      | 14        | 21.88%  |
| 3      | 7         | 10.94%  |
| 4      | 6         | 9.38%   |
| 5      | 3         | 4.69%   |
| 10     | 1         | 1.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 51        | 79.69%  |
| Yes       | 13        | 20.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 85.94%  |
| No        | 9         | 14.06%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 76.56%  |
| No        | 15        | 23.44%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 70.31%  |
| No        | 19        | 29.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 14        | 21.88%  |
| Germany      | 6         | 9.38%   |
| Russia       | 4         | 6.25%   |
| China        | 4         | 6.25%   |
| Italy        | 3         | 4.69%   |
| Canada       | 3         | 4.69%   |
| Bulgaria     | 3         | 4.69%   |
| Ukraine      | 2         | 3.13%   |
| Poland       | 2         | 3.13%   |
| Japan        | 2         | 3.13%   |
| Brazil       | 2         | 3.13%   |
| Australia    | 2         | 3.13%   |
| Vietnam      | 1         | 1.56%   |
| Uzbekistan   | 1         | 1.56%   |
| Switzerland  | 1         | 1.56%   |
| Sweden       | 1         | 1.56%   |
| South Africa | 1         | 1.56%   |
| Puerto Rico  | 1         | 1.56%   |
| Norway       | 1         | 1.56%   |
| Netherlands  | 1         | 1.56%   |
| Myanmar      | 1         | 1.56%   |
| Kazakhstan   | 1         | 1.56%   |
| India        | 1         | 1.56%   |
| France       | 1         | 1.56%   |
| Finland      | 1         | 1.56%   |
| Colombia     | 1         | 1.56%   |
| Chile        | 1         | 1.56%   |
| Belarus      | 1         | 1.56%   |
| Argentina    | 1         | 1.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 3         | 4.48%   |
| Beijing           | 3         | 4.48%   |
| Sofia             | 2         | 2.99%   |
| Bristow           | 2         | 2.99%   |
| Yangon            | 1         | 1.49%   |
| Yakima            | 1         | 1.49%   |
| Wuhan             | 1         | 1.49%   |
| Vitebsk           | 1         | 1.49%   |
| Vicenza           | 1         | 1.49%   |
| Tromsø           | 1         | 1.49%   |
| Tomah             | 1         | 1.49%   |
| Tashkent          | 1         | 1.49%   |
| Sykesville        | 1         | 1.49%   |
| Stromberg         | 1         | 1.49%   |
| Stockholm         | 1         | 1.49%   |
| Soest             | 1         | 1.49%   |
| Schemmerhofen     | 1         | 1.49%   |
| Sanford           | 1         | 1.49%   |
| San Juan          | 1         | 1.49%   |
| Ruda Śląska     | 1         | 1.49%   |
| Rome              | 1         | 1.49%   |
| Ribeirao Preto    | 1         | 1.49%   |
| Quitman           | 1         | 1.49%   |
| Québec           | 1         | 1.49%   |
| Puente Alto       | 1         | 1.49%   |
| Porto Alegre      | 1         | 1.49%   |
| Portland          | 1         | 1.49%   |
| Perth             | 1         | 1.49%   |
| Persan            | 1         | 1.49%   |
| Ozarow Mazowiecki | 1         | 1.49%   |
| Okazaki           | 1         | 1.49%   |
| New York          | 1         | 1.49%   |
| New Cumberland    | 1         | 1.49%   |
| Navapolatsk       | 1         | 1.49%   |
| Nagoya            | 1         | 1.49%   |
| Mumbai            | 1         | 1.49%   |
| Milpitas          | 1         | 1.49%   |
| Michelstadt       | 1         | 1.49%   |
| Melbourne         | 1         | 1.49%   |
| Meieki            | 1         | 1.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 16        | 26     | 16.49%  |
| WDC                       | 12        | 17     | 12.37%  |
| Seagate                   | 10        | 15     | 10.31%  |
| Kingston                  | 9         | 12     | 9.28%   |
| Toshiba                   | 7         | 10     | 7.22%   |
| SK hynix                  | 5         | 5      | 5.15%   |
| SanDisk                   | 4         | 14     | 4.12%   |
| Intel                     | 4         | 4      | 4.12%   |
| Micron Technology         | 3         | 3      | 3.09%   |
| HGST                      | 3         | 4      | 3.09%   |
| Phison Electronics        | 2         | 2      | 2.06%   |
| Crucial                   | 2         | 12     | 2.06%   |
| WD MediaMax               | 1         | 1      | 1.03%   |
| VICKTER                   | 1         | 1      | 1.03%   |
| Unknown                   | 1         | 1      | 1.03%   |
| Union Memory              | 1         | 1      | 1.03%   |
| Team                      | 1         | 2      | 1.03%   |
| SPCC                      | 1         | 1      | 1.03%   |
| Plextor                   | 1         | 1      | 1.03%   |
| Phison                    | 1         | 1      | 1.03%   |
| OCZ                       | 1         | 1      | 1.03%   |
| Netac                     | 1         | 2      | 1.03%   |
| Micron/Crucial Technology | 1         | 1      | 1.03%   |
| LITEON                    | 1         | 1      | 1.03%   |
| Intenso                   | 1         | 1      | 1.03%   |
| Hjwdz                     | 1         | 1      | 1.03%   |
| Hitachi                   | 1         | 1      | 1.03%   |
| Hewlett-Packard           | 1         | 1      | 1.03%   |
| Gigabyte Technology       | 1         | 2      | 1.03%   |
| ASMT                      | 1         | 1      | 1.03%   |
| ADATA Technology          | 1         | 1      | 1.03%   |
| A-DATA Technology         | 1         | 1      | 1.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| SK hynix BC511 256GB                               | 2         | 1.87%   |
| Seagate ST1000DM010-2EP102 1TB                     | 2         | 1.87%   |
| Sandisk WD_BLACK SN770 1TB                         | 2         | 1.87%   |
| SanDisk SDSSDH3 1T00 1TB                           | 2         | 1.87%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 2         | 1.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 2         | 1.87%   |
| Samsung MZNLH512HALU-00000 512GB SSD               | 2         | 1.87%   |
| Micron 2450_MTFDKBA512TFK 512GB                    | 2         | 1.87%   |
| Crucial CT525MX300SSD1 528GB                       | 2         | 1.87%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                   | 1         | 0.93%   |
| WDC WD6400BEVT-22A0RT0 640GB                       | 1         | 0.93%   |
| WDC WD6003FZBX-00K5WB0 6TB                         | 1         | 0.93%   |
| WDC WD5000LPLX-60ZNTT1 500GB                       | 1         | 0.93%   |
| WDC WD5000BEVT-55A0RT0 500GB                       | 1         | 0.93%   |
| WDC WD3200AAKX-753CA1 320GB                        | 1         | 0.93%   |
| WDC WD2500AAJS-60M0A0 250GB                        | 1         | 0.93%   |
| WDC WD22EJRX-89BEMY0 2TB                           | 1         | 0.93%   |
| WDC WD2003FZEX-00Z4SA0 2TB                         | 1         | 0.93%   |
| WDC WD10EZEX-60M2NA0 1TB                           | 1         | 0.93%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 1         | 0.93%   |
| WDC WD10EZEX-00BN5A0 1TB                           | 1         | 0.93%   |
| WDC WD Blue SA510 2.5 500GB SSD                    | 1         | 0.93%   |
| WD MediaMax WL750GSA6472 752GB                     | 1         | 0.93%   |
| VICKTER SSD 128GB                                  | 1         | 0.93%   |
| Unknown MMC Card  7GB                              | 1         | 0.93%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB            | 1         | 0.93%   |
| Toshiba MQ04ABF100 1TB                             | 1         | 0.93%   |
| Toshiba MK2561GSYN 250GB                           | 1         | 0.93%   |
| Toshiba MK1234GSX 118GB                            | 1         | 0.93%   |
| Toshiba KXG50ZNV512G 512GB                         | 1         | 0.93%   |
| Toshiba DT01ACA200 2TB                             | 1         | 0.93%   |
| Toshiba DT01ACA100 1TB                             | 1         | 0.93%   |
| Toshiba AL15SEB24EQY 2TB                           | 1         | 0.93%   |
| Toshiba AL15SEB24EQY 2.4TB                         | 1         | 0.93%   |
| Team T253X1480G 480GB SSD                          | 1         | 0.93%   |
| SPCC Solid State Disk 120GB                        | 1         | 0.93%   |
| SK hynix PC711 NVMe 1TB                            | 1         | 0.93%   |
| SK hynix NVMe SSD Drive 256GB                      | 1         | 0.93%   |
| SK hynix BC501 NVMe 256GB                          | 1         | 0.93%   |
| Seagate ST600MM0088 600GB                          | 1         | 0.93%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor      | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| WDC         | 10        | 15     | 33.33%  |
| Seagate     | 9         | 13     | 30%     |
| Toshiba     | 6         | 8      | 20%     |
| HGST        | 3         | 4      | 10%     |
| WD MediaMax | 1         | 1      | 3.33%   |
| Hitachi     | 1         | 1      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 18     | 27.78%  |
| Kingston            | 6         | 9      | 16.67%  |
| SanDisk             | 3         | 7      | 8.33%   |
| WDC                 | 2         | 2      | 5.56%   |
| Crucial             | 2         | 12     | 5.56%   |
| VICKTER             | 1         | 1      | 2.78%   |
| Team                | 1         | 2      | 2.78%   |
| SPCC                | 1         | 1      | 2.78%   |
| Plextor             | 1         | 1      | 2.78%   |
| OCZ                 | 1         | 1      | 2.78%   |
| Netac               | 1         | 2      | 2.78%   |
| LITEON              | 1         | 1      | 2.78%   |
| Intenso             | 1         | 1      | 2.78%   |
| Intel               | 1         | 1      | 2.78%   |
| Hewlett-Packard     | 1         | 1      | 2.78%   |
| Gigabyte Technology | 1         | 2      | 2.78%   |
| ASMT                | 1         | 1      | 2.78%   |
| A-DATA Technology   | 1         | 1      | 2.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 30        | 38     | 34.88%  |
| SSD     | 30        | 64     | 34.88%  |
| HDD     | 23        | 42     | 26.74%  |
| Unknown | 2         | 2      | 2.33%   |
| MMC     | 1         | 1      | 1.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 42        | 105    | 55.26%  |
| NVMe | 29        | 36     | 38.16%  |
| SAS  | 4         | 5      | 5.26%   |
| MMC  | 1         | 1      | 1.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 29        | 46     | 51.79%  |
| 0.51-1.0   | 19        | 46     | 33.93%  |
| 1.01-2.0   | 6         | 11     | 10.71%  |
| 2.01-3.0   | 1         | 1      | 1.79%   |
| 4.01-10.0  | 1         | 2      | 1.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 19        | 28.79%  |
| 251-500        | 15        | 22.73%  |
| 1001-2000      | 11        | 16.67%  |
| 501-1000       | 10        | 15.15%  |
| 2001-3000      | 4         | 6.06%   |
| More than 3000 | 3         | 4.55%   |
| 51-100         | 2         | 3.03%   |
| 21-50          | 1         | 1.52%   |
| Unknown        | 1         | 1.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 28        | 43.08%  |
| 21-50          | 8         | 12.31%  |
| 101-250        | 8         | 12.31%  |
| 51-100         | 7         | 10.77%  |
| 251-500        | 6         | 9.23%   |
| 501-1000       | 3         | 4.62%   |
| 1001-2000      | 2         | 3.08%   |
| More than 3000 | 1         | 1.54%   |
| 2001-3000      | 1         | 1.54%   |
| Unknown        | 1         | 1.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000LPLX-60ZNTT1 500GB      | 1         | 1      | 14.29%  |
| WDC WD10EZEX-60M2NA0 1TB          | 1         | 1      | 14.29%  |
| Toshiba MK2561GSYN 250GB          | 1         | 1      | 14.29%  |
| Toshiba MK1234GSX 118GB           | 1         | 1      | 14.29%  |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 14.29%  |
| Seagate ST3250820AS 250GB         | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 840 250GB | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 28.57%  |
| Toshiba             | 2         | 2      | 28.57%  |
| Seagate             | 2         | 2      | 28.57%  |
| Samsung Electronics | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 33.33%  |
| Toshiba | 2         | 2      | 33.33%  |
| Seagate | 2         | 2      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 6      | 83.33%  |
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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 37        | 82     | 50.68%  |
| Works    | 30        | 58     | 41.1%   |
| Malfunc  | 6         | 7      | 8.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 47        | 52.22%  |
| AMD                          | 8         | 8.89%   |
| SK hynix                     | 5         | 5.56%   |
| Samsung Electronics          | 5         | 5.56%   |
| LSI Logic / Symbios Logic    | 4         | 4.44%   |
| Sandisk                      | 3         | 3.33%   |
| Phison Electronics           | 3         | 3.33%   |
| Micron Technology            | 3         | 3.33%   |
| Kingston Technology Company  | 3         | 3.33%   |
| Union Memory (Shenzhen)      | 1         | 1.11%   |
| Toshiba America Info Systems | 1         | 1.11%   |
| Silicon Image                | 1         | 1.11%   |
| Seagate Technology           | 1         | 1.11%   |
| Micron/Crucial Technology    | 1         | 1.11%   |
| JMicron Technology           | 1         | 1.11%   |
| Broadcom / LSI               | 1         | 1.11%   |
| ASMedia Technology           | 1         | 1.11%   |
| ADATA Technology             | 1         | 1.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 6         | 6.12%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 5.1%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 4.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 4.08%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 3.06%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 3         | 3.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 3.06%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 2.04%   |
| SK hynix BC511 NVMe SSD                                                        | 2         | 2.04%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 2         | 2.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 2.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 2.04%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2         | 2.04%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 2.04%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                             | 2         | 2.04%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 2.04%   |
| Intel SSD 660P Series                                                          | 2         | 2.04%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 2         | 2.04%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 2.04%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 2         | 2.04%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2         | 2.04%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 2.04%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                          | 1         | 1.02%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 1.02%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 1.02%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1         | 1.02%   |
| Seagate FireCuda 520/IronWolf 525 SSD                                          | 1         | 1.02%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 1         | 1.02%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 1.02%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 1.02%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.02%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 1.02%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 1         | 1.02%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                 | 1         | 1.02%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                        | 1         | 1.02%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3008 [Fury]                           | 1         | 1.02%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2208 [Thunderbolt]                      | 1         | 1.02%   |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                             | 1         | 1.02%   |
| JMicron JMB362 SATA Controller                                                 | 1         | 1.02%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.02%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 50        | 55.56%  |
| NVMe | 29        | 32.22%  |
| RAID | 9         | 10%     |
| SCSI | 1         | 1.11%   |
| IDE  | 1         | 1.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 53        | 82.81%  |
| AMD    | 11        | 17.19%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-1260P          | 2         | 3.13%   |
| Intel 12th Gen Core i5-12600K         | 2         | 3.13%   |
| Intel Xeon Silver 4215R CPU @ 3.20GHz | 1         | 1.56%   |
| Intel Xeon Gold 6326 CPU @ 2.90GHz    | 1         | 1.56%   |
| Intel Xeon CPU X3440 @ 2.53GHz        | 1         | 1.56%   |
| Intel Xeon CPU E5-2687W v4 @ 3.00GHz  | 1         | 1.56%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz    | 1         | 1.56%   |
| Intel N100                            | 1         | 1.56%   |
| Intel Core i7-8750H CPU @ 2.20GHz     | 1         | 1.56%   |
| Intel Core i7-8565U CPU @ 1.80GHz     | 1         | 1.56%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz    | 1         | 1.56%   |
| Intel Core i7-5930K CPU @ 3.50GHz     | 1         | 1.56%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz    | 1         | 1.56%   |
| Intel Core i7-4770K CPU @ 3.50GHz     | 1         | 1.56%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz    | 1         | 1.56%   |
| Intel Core i7-4500U CPU @ 1.80GHz     | 1         | 1.56%   |
| Intel Core i7-2600K CPU @ 3.40GHz     | 1         | 1.56%   |
| Intel Core i7-10750H CPU @ 2.60GHz    | 1         | 1.56%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz    | 1         | 1.56%   |
| Intel Core i5-8265U CPU @ 1.60GHz     | 1         | 1.56%   |
| Intel Core i5-6300U CPU @ 2.40GHz     | 1         | 1.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz     | 1         | 1.56%   |
| Intel Core i5-4590 CPU @ 3.30GHz      | 1         | 1.56%   |
| Intel Core i5-4440 CPU @ 3.10GHz      | 1         | 1.56%   |
| Intel Core i5-4210U CPU @ 1.70GHz     | 1         | 1.56%   |
| Intel Core i5-4200M CPU @ 2.50GHz     | 1         | 1.56%   |
| Intel Core i5-3470 CPU @ 3.20GHz      | 1         | 1.56%   |
| Intel Core i5-3380M CPU @ 2.90GHz     | 1         | 1.56%   |
| Intel Core i5-3320M CPU @ 2.60GHz     | 1         | 1.56%   |
| Intel Core i5-3230M CPU @ 2.60GHz     | 1         | 1.56%   |
| Intel Core i5-2400S CPU @ 2.50GHz     | 1         | 1.56%   |
| Intel Core i5-10400F CPU @ 2.90GHz    | 1         | 1.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz    | 1         | 1.56%   |
| Intel Core i5 CPU M 430 @ 2.27GHz     | 1         | 1.56%   |
| Intel Core i3-8145U CPU @ 2.10GHz     | 1         | 1.56%   |
| Intel Core i3-7100U CPU @ 2.40GHz     | 1         | 1.56%   |
| Intel Core i3-4010U CPU @ 1.70GHz     | 1         | 1.56%   |
| Intel Core i3-3217U CPU @ 1.80GHz     | 1         | 1.56%   |
| Intel Core i3-2130 CPU @ 3.40GHz      | 1         | 1.56%   |
| Intel Celeron J4125 CPU @ 2.00GHz     | 1         | 1.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Other             | 15        | 23.44%  |
| Intel Core i5     | 15        | 23.44%  |
| Intel Core i7     | 11        | 17.19%  |
| Intel Core i3     | 5         | 7.81%   |
| Intel Xeon        | 3         | 4.69%   |
| AMD Ryzen 7       | 3         | 4.69%   |
| AMD Ryzen 5       | 3         | 4.69%   |
| AMD Ryzen 9       | 2         | 3.13%   |
| Intel Xeon Silver | 1         | 1.56%   |
| Intel Xeon Gold   | 1         | 1.56%   |
| Intel Celeron     | 1         | 1.56%   |
| Intel Atom        | 1         | 1.56%   |
| AMD Ryzen 3 PRO   | 1         | 1.56%   |
| AMD FX            | 1         | 1.56%   |
| AMD A10           | 1         | 1.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 21        | 32.81%  |
| 2      | 15        | 23.44%  |
| 6      | 7         | 10.94%  |
| 16     | 5         | 7.81%   |
| 12     | 4         | 6.25%   |
| 8      | 4         | 6.25%   |
| 24     | 2         | 3.13%   |
| 14     | 2         | 3.13%   |
| 10     | 2         | 3.13%   |
| 32     | 1         | 1.56%   |
| 1      | 1         | 1.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 60        | 93.75%  |
| 2      | 4         | 6.25%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 52        | 81.25%  |
| 1      | 12        | 18.75%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 64        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 39.06%  |
| 0x906a3    | 5         | 7.81%   |
| 0x306c3    | 4         | 6.25%   |
| 0x306a9    | 4         | 6.25%   |
| 0x40651    | 3         | 4.69%   |
| 0x08600106 | 3         | 4.69%   |
| 0x806ec    | 2         | 3.13%   |
| 0x406e3    | 2         | 3.13%   |
| 0xa0671    | 1         | 1.56%   |
| 0xa0653    | 1         | 1.56%   |
| 0xa0652    | 1         | 1.56%   |
| 0x90672    | 1         | 1.56%   |
| 0x706e5    | 1         | 1.56%   |
| 0x706a8    | 1         | 1.56%   |
| 0x606a6    | 1         | 1.56%   |
| 0x306f2    | 1         | 1.56%   |
| 0x206a7    | 1         | 1.56%   |
| 0x20652    | 1         | 1.56%   |
| 0x0a50000c | 1         | 1.56%   |
| 0x0a201016 | 1         | 1.56%   |
| 0x08701021 | 1         | 1.56%   |
| 0x08701013 | 1         | 1.56%   |
| 0x06001119 | 1         | 1.56%   |
| 0x0600063d | 1         | 1.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 10        | 15.38%  |
| Alderlake Hybrid | 10        | 15.38%  |
| KabyLake         | 7         | 10.77%  |
| Zen 2            | 6         | 9.23%   |
| IvyBridge        | 5         | 7.69%   |
| SandyBridge      | 4         | 6.15%   |
| IceLake          | 4         | 6.15%   |
| Skylake          | 3         | 4.62%   |
| Zen 3            | 2         | 3.08%   |
| TigerLake        | 2         | 3.08%   |
| CometLake        | 2         | 3.08%   |
| Zen+             | 1         | 1.54%   |
| Westmere         | 1         | 1.54%   |
| Piledriver       | 1         | 1.54%   |
| Nehalem          | 1         | 1.54%   |
| Gracemont        | 1         | 1.54%   |
| Goldmont plus    | 1         | 1.54%   |
| Bulldozer        | 1         | 1.54%   |
| Broadwell        | 1         | 1.54%   |
| Bonnell          | 1         | 1.54%   |
| Unknown          | 1         | 1.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 37        | 45.68%  |
| Nvidia                     | 25        | 30.86%  |
| AMD                        | 14        | 17.28%  |
| Matrox Electronics Systems | 4         | 4.94%   |
| ASPEED Technology          | 1         | 1.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 5         | 5.95%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 4         | 4.76%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 4         | 4.76%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 3         | 3.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3         | 3.57%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2         | 2.38%   |
| Matrox Electronics Systems G200eR2                                          | 2         | 2.38%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 2         | 2.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 2.38%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 2         | 2.38%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 2.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2         | 2.38%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 1.19%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1         | 1.19%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1         | 1.19%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 1         | 1.19%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1         | 1.19%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1         | 1.19%   |
| Nvidia GP108M [GeForce MX330]                                               | 1         | 1.19%   |
| Nvidia GP108M [GeForce MX250]                                               | 1         | 1.19%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 1.19%   |
| Nvidia GP107M [GeForce MX350]                                               | 1         | 1.19%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 1.19%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                     | 1         | 1.19%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1         | 1.19%   |
| Nvidia GM108M [GeForce MX110]                                               | 1         | 1.19%   |
| Nvidia GM107M [GeForce GTX 850M]                                            | 1         | 1.19%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                       | 1         | 1.19%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1         | 1.19%   |
| Nvidia GK208M [GeForce GT 740M]                                             | 1         | 1.19%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1         | 1.19%   |
| Nvidia GK107M [GeForce GT 745M]                                             | 1         | 1.19%   |
| Nvidia GF108M [NVS 5400M]                                                   | 1         | 1.19%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                          | 1         | 1.19%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 1         | 1.19%   |
| Nvidia GA103M [GeForce RTX 3080 Ti Mobile]                                  | 1         | 1.19%   |
| Matrox Electronics Systems MGA G200EV                                       | 1         | 1.19%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller    | 1         | 1.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1         | 1.19%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 1         | 1.19%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 22        | 34.38%  |
| Intel + Nvidia  | 13        | 20.31%  |
| 1 x Nvidia      | 10        | 15.63%  |
| 1 x AMD         | 10        | 15.63%  |
| 1 x Matrox      | 3         | 4.69%   |
| 2 x AMD         | 2         | 3.13%   |
| Nvidia + Matrox | 1         | 1.56%   |
| Intel + AMD     | 1         | 1.56%   |
| 1 x ASPEED      | 1         | 1.56%   |
| AMD + Nvidia    | 1         | 1.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 53        | 81.54%  |
| Proprietary | 10        | 15.38%  |
| Unknown     | 2         | 3.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 50.75%  |
| 1.01-2.0   | 8         | 11.94%  |
| 3.01-4.0   | 7         | 10.45%  |
| 5.01-6.0   | 5         | 7.46%   |
| 0.01-0.5   | 5         | 7.46%   |
| 0.51-1.0   | 4         | 5.97%   |
| 8.01-16.0  | 3         | 4.48%   |
| 7.01-8.0   | 1         | 1.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 9         | 13.24%  |
| Samsung Electronics     | 7         | 10.29%  |
| AU Optronics            | 6         | 8.82%   |
| Goldstar                | 5         | 7.35%   |
| Dell                    | 5         | 7.35%   |
| Chimei Innolux          | 5         | 7.35%   |
| ViewSonic               | 3         | 4.41%   |
| BOE                     | 3         | 4.41%   |
| Iiyama                  | 2         | 2.94%   |
| Hewlett-Packard         | 2         | 2.94%   |
| BenQ                    | 2         | 2.94%   |
| AOC                     | 2         | 2.94%   |
| Acer                    | 2         | 2.94%   |
| Unknown (XXX)           | 1         | 1.47%   |
| TMX                     | 1         | 1.47%   |
| SKY                     | 1         | 1.47%   |
| Sharp                   | 1         | 1.47%   |
| PANDA                   | 1         | 1.47%   |
| NXG                     | 1         | 1.47%   |
| LG Electronics          | 1         | 1.47%   |
| KVM                     | 1         | 1.47%   |
| HKC                     | 1         | 1.47%   |
| Gigabyte Technology     | 1         | 1.47%   |
| Eizo                    | 1         | 1.47%   |
| CSO                     | 1         | 1.47%   |
| Chi Mei Optoelectronics | 1         | 1.47%   |
| CHD                     | 1         | 1.47%   |
| Unknown                 | 1         | 1.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Iiyama PL2888H IVM7106 1920x1080 620x340mm 27.8-inch                  | 2         | 2.78%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch         | 1         | 1.39%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch         | 1         | 1.39%   |
| ViewSonic PJ402D-2 HCD7B1D 1280x960                                   | 1         | 1.39%   |
| Unknown (XXX) FURRION TV XXX3553 1920x1080 520x290mm 23.4-inch        | 1         | 1.39%   |
| TMX TL156VDXP01 TMX1560 1920x1080 344x194mm 15.5-inch                 | 1         | 1.39%   |
| SKY 22X1-M225F SKY2150 1920x1080 476x268mm 21.5-inch                  | 1         | 1.39%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 1.39%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 607x345mm 27.5-inch     | 1         | 1.39%   |
| Samsung Electronics SyncMaster SAM05EB 1920x1080 597x336mm 27.0-inch  | 1         | 1.39%   |
| Samsung Electronics SMT22A350 SAM07A7 1920x1080 477x268mm 21.5-inch   | 1         | 1.39%   |
| Samsung Electronics SMEX2220 SAM0686 1920x1080 477x268mm 21.5-inch    | 1         | 1.39%   |
| Samsung Electronics S27C450 SAM09D9 1920x1080 598x336mm 27.0-inch     | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch | 1         | 1.39%   |
| PANDA LCD Monitor NCP0052 1920x1080 309x174mm 14.0-inch               | 1         | 1.39%   |
| NXG MIRAI DML-517 NXG138B 1280x1024 338x270mm 17.0-inch               | 1         | 1.39%   |
| LG Electronics LCD Monitor LG FULL HD                                 | 1         | 1.39%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch          | 1         | 1.39%   |
| LG Display LCD Monitor LGD068A 1920x1080 309x174mm 14.0-inch          | 1         | 1.39%   |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch          | 1         | 1.39%   |
| LG Display LCD Monitor LGD05E4 1920x1080 344x194mm 15.5-inch          | 1         | 1.39%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 1.39%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch          | 1         | 1.39%   |
| LG Display LCD Monitor LGD033C 1366x768 310x170mm 13.9-inch           | 1         | 1.39%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 1         | 1.39%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 1         | 1.39%   |
| KVM LCD Monitor191919 KVM4308 1280x1024 376x301mm 19.0-inch           | 1         | 1.39%   |
| HKC GF40 HKC2413 1920x1080 521x297mm 23.6-inch                        | 1         | 1.39%   |
| Hewlett-Packard L185x HWP298C 1366x768 410x230mm 18.5-inch            | 1         | 1.39%   |
| Hewlett-Packard 2159 HWP282C 1920x1080 479x269mm 21.6-inch            | 1         | 1.39%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 1         | 1.39%   |
| Goldstar LG ULTRAGEAR GSM5B70 1920x1080 600x340mm 27.2-inch           | 1         | 1.39%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1         | 1.39%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 1         | 1.39%   |
| Goldstar 22EA53 GSM59A6 1920x1080 477x268mm 21.5-inch                 | 1         | 1.39%   |
| Gigabyte Technology G34WQC A GBT3403 3440x1440 797x334mm 34.0-inch    | 1         | 1.39%   |
| Eizo EV2450 ENC2532 1920x1080 528x297mm 23.9-inch                     | 1         | 1.39%   |
| Dell U2720Q DEL41B0 3840x2160 597x336mm 27.0-inch                     | 1         | 1.39%   |
| Dell U2718Q DELA0E9 3840x2160 609x349mm 27.6-inch                     | 1         | 1.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 34        | 52.31%  |
| 3840x2160 (4K)     | 7         | 10.77%  |
| 1366x768 (WXGA)    | 7         | 10.77%  |
| 1920x1200 (WUXGA)  | 3         | 4.62%   |
| 2560x1440 (QHD)    | 2         | 3.08%   |
| 1600x900 (HD+)     | 2         | 3.08%   |
| 1280x1024 (SXGA)   | 2         | 3.08%   |
| Unknown            | 2         | 3.08%   |
| 5760x1080          | 1         | 1.54%   |
| 3840x1080          | 1         | 1.54%   |
| 3440x1440          | 1         | 1.54%   |
| 3200x2000          | 1         | 1.54%   |
| 1680x1050 (WSXGA+) | 1         | 1.54%   |
| 1280x960           | 1         | 1.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 13        | 18.84%  |
| 14      | 12        | 17.39%  |
| 21      | 10        | 14.49%  |
| 27      | 9         | 13.04%  |
| 24      | 5         | 7.25%   |
| 23      | 5         | 7.25%   |
| Unknown | 3         | 4.35%   |
| 17      | 2         | 2.9%    |
| 13      | 2         | 2.9%    |
| 84      | 1         | 1.45%   |
| 38      | 1         | 1.45%   |
| 34      | 1         | 1.45%   |
| 25      | 1         | 1.45%   |
| 22      | 1         | 1.45%   |
| 19      | 1         | 1.45%   |
| 18      | 1         | 1.45%   |
| 16      | 1         | 1.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 27        | 40.3%   |
| 501-600     | 14        | 20.9%   |
| 401-500     | 12        | 17.91%  |
| 601-700     | 4         | 5.97%   |
| 351-400     | 3         | 4.48%   |
| Unknown     | 3         | 4.48%   |
| 801-900     | 1         | 1.49%   |
| 701-800     | 1         | 1.49%   |
| 201-300     | 1         | 1.49%   |
| 1501-2000   | 1         | 1.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 46        | 80.7%   |
| 16/10   | 5         | 8.77%   |
| 5/4     | 2         | 3.51%   |
| Unknown | 2         | 3.51%   |
| 4/3     | 1         | 1.75%   |
| 21/9    | 1         | 1.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 16        | 23.88%  |
| 81-90          | 13        | 19.4%   |
| 101-110        | 13        | 19.4%   |
| 301-350        | 9         | 13.43%  |
| 251-300        | 3         | 4.48%   |
| Unknown        | 3         | 4.48%   |
| 151-200        | 2         | 2.99%   |
| 141-150        | 2         | 2.99%   |
| More than 1000 | 1         | 1.49%   |
| 71-80          | 1         | 1.49%   |
| 351-500        | 1         | 1.49%   |
| 121-130        | 1         | 1.49%   |
| 111-120        | 1         | 1.49%   |
| 501-1000       | 1         | 1.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 20        | 29.85%  |
| 51-100        | 19        | 28.36%  |
| 101-120       | 18        | 26.87%  |
| 161-240       | 5         | 7.46%   |
| Unknown       | 3         | 4.48%   |
| More than 240 | 2         | 2.99%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 45        | 69.23%  |
| 2     | 12        | 18.46%  |
| 0     | 6         | 9.23%   |
| 4     | 1         | 1.54%   |
| 3     | 1         | 1.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 42        | 41.18%  |
| Realtek Semiconductor             | 29        | 28.43%  |
| Qualcomm Atheros                  | 11        | 10.78%  |
| Broadcom                          | 5         | 4.9%    |
| TP-Link                           | 2         | 1.96%   |
| ASUSTek Computer                  | 2         | 1.96%   |
| Xiaomi                            | 1         | 0.98%   |
| U-Blox                            | 1         | 0.98%   |
| Mellanox Technologies             | 1         | 0.98%   |
| MediaTek                          | 1         | 0.98%   |
| IBM                               | 1         | 0.98%   |
| Ericsson Business Mobile Networks | 1         | 0.98%   |
| DisplayLink                       | 1         | 0.98%   |
| Dell                              | 1         | 0.98%   |
| Ceton Technologies                | 1         | 0.98%   |
| ASIX Electronics                  | 1         | 0.98%   |
| Aquantia                          | 1         | 0.98%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 22        | 17.74%  |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 6         | 4.84%   |
| Intel Ethernet Controller I225-V                                       | 5         | 4.03%   |
| Realtek RTL8125 2.5GbE Controller                                      | 4         | 3.23%   |
| Intel Wireless 7260                                                    | 4         | 3.23%   |
| Intel Wi-Fi 6 AX200                                                    | 4         | 3.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 3         | 2.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 2.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 2         | 1.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 2         | 1.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2         | 1.61%   |
| Intel Wireless 8265 / 8275                                             | 2         | 1.61%   |
| Intel Wireless 8260                                                    | 2         | 1.61%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 2         | 1.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 2         | 1.61%   |
| Intel 82574L Gigabit Network Connection                                | 2         | 1.61%   |
| ASUS 802.11ac NIC                                                      | 2         | 1.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.81%   |
| U-Blox [u-blox 8]                                                      | 1         | 0.81%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 1         | 0.81%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1         | 0.81%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1         | 0.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 1         | 0.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 0.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1         | 0.81%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.81%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 1         | 0.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 1         | 0.81%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.81%   |
| Mellanox MT27800 Family [ConnectX-5]                                   | 1         | 0.81%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 1         | 0.81%   |
| Intel Wireless 7265                                                    | 1         | 0.81%   |
| Intel Wi-Fi 6 AX201                                                    | 1         | 0.81%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 1         | 0.81%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 1         | 0.81%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 1         | 0.81%   |
| Intel I350 Gigabit Network Connection                                  | 1         | 0.81%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 0.81%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 32        | 60.38%  |
| Qualcomm Atheros      | 10        | 18.87%  |
| Realtek Semiconductor | 5         | 9.43%   |
| TP-Link               | 2         | 3.77%   |
| ASUSTek Computer      | 2         | 3.77%   |
| MediaTek              | 1         | 1.89%   |
| Broadcom              | 1         | 1.89%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                               | 6         | 11.32%  |
| Intel Wireless 7260                                            | 4         | 7.55%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 7.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 5.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 3.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 3.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 3.77%   |
| Intel Wireless 8265 / 8275                                     | 2         | 3.77%   |
| Intel Wireless 8260                                            | 2         | 3.77%   |
| Intel Raptor Lake-S PCH CNVi WiFi                              | 2         | 3.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 3.77%   |
| ASUS 802.11ac NIC                                              | 2         | 3.77%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1         | 1.89%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 1.89%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 1.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 1.89%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.89%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1         | 1.89%   |
| Intel Wireless 7265                                            | 1         | 1.89%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 1.89%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 1         | 1.89%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.89%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 1.89%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.89%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 1.89%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 27        | 42.19%  |
| Intel                 | 23        | 35.94%  |
| Broadcom              | 4         | 6.25%   |
| Qualcomm Atheros      | 2         | 3.13%   |
| Xiaomi                | 1         | 1.56%   |
| Mellanox Technologies | 1         | 1.56%   |
| IBM                   | 1         | 1.56%   |
| DisplayLink           | 1         | 1.56%   |
| Dell                  | 1         | 1.56%   |
| Ceton Technologies    | 1         | 1.56%   |
| ASIX Electronics      | 1         | 1.56%   |
| Aquantia              | 1         | 1.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                           | Computers | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 22        | 31.88%  |
| Intel Ethernet Controller I225-V                                                | 5         | 7.25%   |
| Realtek RTL8125 2.5GbE Controller                                               | 4         | 5.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 3         | 4.35%   |
| Intel 82574L Gigabit Network Connection                                         | 2         | 2.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                  | 1         | 1.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                        | 1         | 1.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                           | 1         | 1.45%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                          | 1         | 1.45%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                           | 1         | 1.45%   |
| Mellanox MT27800 Family [ConnectX-5]                                            | 1         | 1.45%   |
| Intel I350 Gigabit Network Connection                                           | 1         | 1.45%   |
| Intel I211 Gigabit Network Connection                                           | 1         | 1.45%   |
| Intel I210 Gigabit Network Connection                                           | 1         | 1.45%   |
| Intel Ethernet Controller XL710 for 40GbE QSFP+                                 | 1         | 1.45%   |
| Intel Ethernet Controller X710 for 10GBASE-T                                    | 1         | 1.45%   |
| Intel Ethernet Controller X550                                                  | 1         | 1.45%   |
| Intel Ethernet Controller I226-V                                                | 1         | 1.45%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                   | 1         | 1.45%   |
| Intel Ethernet Connection I219-V                                                | 1         | 1.45%   |
| Intel Ethernet Connection I219-LM                                               | 1         | 1.45%   |
| Intel Ethernet Connection I218-V                                                | 1         | 1.45%   |
| Intel Ethernet Connection I218-LM                                               | 1         | 1.45%   |
| Intel Ethernet Connection I217-V                                                | 1         | 1.45%   |
| Intel Ethernet Connection (6) I219-V                                            | 1         | 1.45%   |
| Intel Ethernet Connection (4) I219-V                                            | 1         | 1.45%   |
| Intel Ethernet Connection (2) I218-V                                            | 1         | 1.45%   |
| Intel 82579V Gigabit Network Connection                                         | 1         | 1.45%   |
| IBM XClarity Controller                                                         | 1         | 1.45%   |
| DisplayLink Plugable UD-6950PDZ                                                 | 1         | 1.45%   |
| Dell iDRAC Virtual NIC                                                          | 1         | 1.45%   |
| Ceton InfiniTV Network                                                          | 1         | 1.45%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                               | 1         | 1.45%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                                | 1         | 1.45%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                 | 1         | 1.45%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller           | 1         | 1.45%   |
| ASIX AX88179 Gigabit Ethernet                                                   | 1         | 1.45%   |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G] | 1         | 1.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 54        | 51.43%  |
| WiFi     | 49        | 46.67%  |
| Modem    | 2         | 1.9%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 31        | 50%     |
| Ethernet | 31        | 50%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 38        | 59.38%  |
| 1     | 19        | 29.69%  |
| 3     | 4         | 6.25%   |
| 7     | 1         | 1.56%   |
| 6     | 1         | 1.56%   |
| 4     | 1         | 1.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 47        | 73.44%  |
| Yes  | 17        | 26.56%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 64.44%  |
| Qualcomm Atheros Communications | 4         | 8.89%   |
| Lite-On Technology              | 3         | 6.67%   |
| Realtek Semiconductor           | 2         | 4.44%   |
| IMC Networks                    | 2         | 4.44%   |
| Broadcom                        | 2         | 4.44%   |
| MediaTek                        | 1         | 2.22%   |
| Cambridge Silicon Radio         | 1         | 2.22%   |
| ASUSTek Computer                | 1         | 2.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX211 Bluetooth                               | 7         | 15.56%  |
| Intel Bluetooth wireless interface                  | 6         | 13.33%  |
| Intel Bluetooth Device                              | 4         | 8.89%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 8.89%   |
| Intel AX200 Bluetooth                               | 4         | 8.89%   |
| Intel AX201 Bluetooth                               | 3         | 6.67%   |
| Lite-On Bluetooth Device                            | 2         | 4.44%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 4.44%   |
| Realtek Bluetooth Radio                             | 1         | 2.22%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 2.22%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.22%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 2.22%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.22%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 2.22%   |
| MediaTek Wireless_Device                            | 1         | 2.22%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 2.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.22%   |
| IMC Networks Bluetooth Radio                        | 1         | 2.22%   |
| IMC Networks Bluetooth Device                       | 1         | 2.22%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.22%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 47        | 54.65%  |
| Nvidia                   | 16        | 18.6%   |
| AMD                      | 16        | 18.6%   |
| SteelSeries ApS          | 3         | 3.49%   |
| TX                       | 1         | 1.16%   |
| Micro Star International | 1         | 1.16%   |
| JBL                      | 1         | 1.16%   |
| Generalplus Technology   | 1         | 1.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 6         | 5.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 5.94%   |
| AMD Family 17h/19h HD Audio Controller                                     | 6         | 5.94%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 4.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 3.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 3.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 2.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 2.97%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 2.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 2.97%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 2.97%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 2.97%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.98%   |
| Nvidia TU102 High Definition Audio Controller                              | 2         | 1.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 1.98%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.98%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 1.98%   |
| Intel Raptor Lake High Definition Audio Controller                         | 2         | 1.98%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 1.98%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 1.98%   |
| TX USB Audio                                                               | 1         | 0.99%   |
| SteelSeries ApS SteelSeries Siberia 800                                    | 1         | 0.99%   |
| SteelSeries ApS SteelSeries GameDAC                                        | 1         | 0.99%   |
| SteelSeries ApS Arctis Nova Pro Wireless                                   | 1         | 0.99%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.99%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.99%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.99%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.99%   |
| Nvidia GM200 High Definition Audio                                         | 1         | 0.99%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.99%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.99%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.99%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.99%   |
| Nvidia Audio device                                                        | 1         | 0.99%   |
| Micro Star International USB Audio                                         | 1         | 0.99%   |
| JBL Quantum 600                                                            | 1         | 0.99%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1         | 0.99%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.99%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 0.99%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 0.99%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 14        | 35%     |
| SK hynix            | 7         | 17.5%   |
| Crucial             | 4         | 10%     |
| Corsair             | 4         | 10%     |
| G.Skill             | 3         | 7.5%    |
| Kingston            | 2         | 5%      |
| Unknown (ABCD)      | 1         | 2.5%    |
| Unknown             | 1         | 2.5%    |
| Team                | 1         | 2.5%    |
| Smart Brazil        | 1         | 2.5%    |
| SHARETRONIC         | 1         | 2.5%    |
| A-DATA Technology   | 1         | 2.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                   | 1         | 2.44%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 1         | 2.44%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1067MT/s           | 1         | 2.44%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s | 1         | 2.44%   |
| SK hynix RAM Module 4GB DIMM DDR3 1600MT/s                   | 1         | 2.44%   |
| SK hynix RAM HMT31GR7BFR4A-H9 8GB DIMM DDR3 1333MT/s         | 1         | 2.44%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s       | 1         | 2.44%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s      | 1         | 2.44%   |
| SK hynix RAM HMA84GR7DJR4N-XN 32GB DIMM DDR4 3200MT/s        | 1         | 2.44%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 2.44%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 1         | 2.44%   |
| SHARETRONIC RAM Module 4GB SODIMM DDR3 800MT/s               | 1         | 2.44%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 2.44%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR5 4000MT/s          | 1         | 2.44%   |
| Samsung RAM M474A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s       | 1         | 2.44%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s     | 1         | 2.44%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 2.44%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 2.44%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s        | 1         | 2.44%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 2.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 1         | 2.44%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 2.44%   |
| Samsung RAM M393B1K70DH0-YH9 8GB DIMM 1333MT/s               | 1         | 2.44%   |
| Samsung RAM M393A4K40EB3-CWE 32GB DIMM DDR4 3200MT/s         | 1         | 2.44%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s          | 1         | 2.44%   |
| Samsung RAM K4UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s | 1         | 2.44%   |
| Samsung RAM K3LKBKB0BM-MGCP 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 2.44%   |
| Kingston RAM 99U5471-034.A00LF 4GB DIMM DDR3 1600MT/s        | 1         | 2.44%   |
| Kingston RAM 9905417-083.A00G 4GB SODIMM DDR3 1600MT/s       | 1         | 2.44%   |
| G.Skill RAM F5-5600J3036D32G 32GB DIMM DDR5 5600MT/s         | 1         | 2.44%   |
| G.Skill RAM F4-3600C18-32GTZR 32GB DIMM DDR4 3600MT/s        | 1         | 2.44%   |
| G.Skill RAM F3-1600C9-8GRSL 8GB SODIMM DDR3 1600MT/s         | 1         | 2.44%   |
| Crucial RAM CT8G4SFS824A.M8FD 8GB SODIMM DDR4 2400MT/s       | 1         | 2.44%   |
| Crucial RAM CT16G4SFRA32A.M16FR 16GB SODIMM DDR4 3200MT/s    | 1         | 2.44%   |
| Crucial RAM CT16G4DFD824A.C16FBD 16GB DIMM DDR4 2933MT/s     | 1         | 2.44%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s        | 1         | 2.44%   |
| Corsair RAM CMSX8GX4M1A2400C16 8GB SODIMM DDR4 2400MT/s      | 1         | 2.44%   |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s      | 1         | 2.44%   |
| Corsair RAM CMK64GX4M2Z4000C18 32GB DIMM DDR4 4000MT/s       | 1         | 2.44%   |
| Corsair RAM CMK128GX4M8A2666C16 16GB DIMM DDR4 2133MT/s      | 1         | 2.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 17        | 48.57%  |
| DDR3   | 13        | 37.14%  |
| LPDDR5 | 2         | 5.71%   |
| LPDDR4 | 2         | 5.71%   |
| DDR5   | 1         | 2.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 17        | 48.57%  |
| DIMM         | 14        | 40%     |
| Row Of Chips | 4         | 11.43%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 15        | 40.54%  |
| 32768 | 7         | 18.92%  |
| 16384 | 6         | 16.22%  |
| 4096  | 6         | 16.22%  |
| 2048  | 3         | 8.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 7         | 18.42%  |
| 1600  | 7         | 18.42%  |
| 2667  | 4         | 10.53%  |
| 2400  | 4         | 10.53%  |
| 4000  | 2         | 5.26%   |
| 2133  | 2         | 5.26%   |
| 1800  | 2         | 5.26%   |
| 800   | 2         | 5.26%   |
| 6400  | 1         | 2.63%   |
| 5600  | 1         | 2.63%   |
| 4267  | 1         | 2.63%   |
| 3600  | 1         | 2.63%   |
| 2933  | 1         | 2.63%   |
| 1334  | 1         | 2.63%   |
| 1333  | 1         | 2.63%   |
| 1067  | 1         | 2.63%   |

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
| Chicony Electronics                    | 6         | 17.65%  |
| IMC Networks                           | 5         | 14.71%  |
| Syntek                                 | 3         | 8.82%   |
| Sunplus Innovation Technology          | 3         | 8.82%   |
| Acer                                   | 3         | 8.82%   |
| Realtek Semiconductor                  | 2         | 5.88%   |
| Microdia                               | 2         | 5.88%   |
| Logitech                               | 2         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.88%   |
| Silicon Motion                         | 1         | 2.94%   |
| Luxvisions Innotech Limited            | 1         | 2.94%   |
| Lite-On Technology                     | 1         | 2.94%   |
| KYE Systems                            | 1         | 2.94%   |
| Bison Electronics                      | 1         | 2.94%   |
| Apple                                  | 1         | 2.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                            | 3         | 8.57%   |
| Sunplus Full HD webcam                              | 2         | 5.71%   |
| IMC Networks Integrated Camera                      | 2         | 5.71%   |
| Acer Integrated Camera                              | 2         | 5.71%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 2.86%   |
| Silicon Motion WebCam SC-13HDL11939N                | 1         | 2.86%   |
| Realtek Lenovo EasyCamera                           | 1         | 2.86%   |
| Realtek Integrated_Webcam_HD                        | 1         | 2.86%   |
| Microdia USB Live camera                            | 1         | 2.86%   |
| Microdia Integrated_Webcam_HD                       | 1         | 2.86%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 2.86%   |
| Logitech Webcam C270                                | 1         | 2.86%   |
| Logitech C922 Pro Stream Webcam                     | 1         | 2.86%   |
| Lite-On HP Wide Vision FHD Camera                   | 1         | 2.86%   |
| KYE Systems FaceCam 1320                            | 1         | 2.86%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 2.86%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 2.86%   |
| IMC Networks Integrated RGB Camera                  | 1         | 2.86%   |
| Chicony USB2.0 2M WebCam                            | 1         | 2.86%   |
| Chicony USB 5M WebCam                               | 1         | 2.86%   |
| Chicony Thinkpad T430 camera                        | 1         | 2.86%   |
| Chicony Integrated Camera                           | 1         | 2.86%   |
| Chicony HD WebCam (Asus N-series)                   | 1         | 2.86%   |
| Chicony HD WebCam                                   | 1         | 2.86%   |
| Chicony Acer CrystalEye Webcam                      | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 2.86%   |
| Bison HD Webcam                                     | 1         | 2.86%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 1         | 2.86%   |
| Acer Lenovo Integrated Webcam                       | 1         | 2.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 2         | 50%     |
| Synaptics             | 1         | 25%     |
| LighTuning Technology | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 25%     |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 25%     |
| Synaptics WBDI Fingerprint Reader USB 102         | 1         | 25%     |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 25%     |

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
| 0     | 43        | 64.18%  |
| 1     | 16        | 23.88%  |
| 2     | 5         | 7.46%   |
| 3     | 2         | 2.99%   |
| 4     | 1         | 1.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 5         | 16.67%  |
| Graphics card            | 5         | 16.67%  |
| Unassigned class         | 4         | 13.33%  |
| Fingerprint reader       | 4         | 13.33%  |
| Communication controller | 4         | 13.33%  |
| Multimedia controller    | 3         | 10%     |
| Storage/ata              | 1         | 3.33%   |
| Storage                  | 1         | 3.33%   |
| Dvb card                 | 1         | 3.33%   |
| Chipcard                 | 1         | 3.33%   |
| Bluetooth                | 1         | 3.33%   |

