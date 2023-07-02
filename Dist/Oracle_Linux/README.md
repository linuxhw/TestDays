Oracle Linux - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Oracle Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Oracle_Linux/Desktop/README.md) and [notebooks](/Dist/Oracle_Linux/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
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

Total: 98

| Vendor     | Model                       | Form-Factor | Probe                                                      | Date         |
|------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Cisco      | WAVE-694-K9 A0              | Desktop     | [26b9c3adb7](https://linux-hardware.org/?probe=26b9c3adb7) | Jun 27, 2023 |
| ASRock     | Z68 Extreme3 Gen3           | Desktop     | [7849965aa1](https://linux-hardware.org/?probe=7849965aa1) | Jun 11, 2023 |
| Dell       | Latitude 7430               | Notebook    | [299e6897d2](https://linux-hardware.org/?probe=299e6897d2) | Jun 05, 2023 |
| Supermicro | X8DTU                       | Server      | [2e1d03c7da](https://linux-hardware.org/?probe=2e1d03c7da) | Jun 01, 2023 |
| Intel      | NUC12WSBi5 M46425-303       | Mini pc     | [e3dca941cf](https://linux-hardware.org/?probe=e3dca941cf) | May 28, 2023 |
| Intel      | NUC12WSBi5 M46425-303       | Mini pc     | [9327ef1887](https://linux-hardware.org/?probe=9327ef1887) | May 27, 2023 |
| Lenovo     | ThinkPad T490 20N3S3XR00    | Notebook    | [0f80e19e5b](https://linux-hardware.org/?probe=0f80e19e5b) | May 23, 2023 |
| Lenovo     | ThinkPad W541 20EGS1PL00    | Notebook    | [751cc5dbc7](https://linux-hardware.org/?probe=751cc5dbc7) | May 22, 2023 |
| HP         | 1589                        | Desktop     | [c905464231](https://linux-hardware.org/?probe=c905464231) | May 11, 2023 |
| ASUSTek    | ZenBook UX425EA_UX425EA     | Notebook    | [9be6e0f395](https://linux-hardware.org/?probe=9be6e0f395) | Apr 18, 2023 |
| Gigabyte   | H81M-S2PV                   | Desktop     | [ac856abadc](https://linux-hardware.org/?probe=ac856abadc) | Mar 21, 2023 |
| Intel      | NUC6CAYB J23203-406         | Mini pc     | [65bb9a17dd](https://linux-hardware.org/?probe=65bb9a17dd) | Feb 04, 2023 |
| HP         | Laptop 17-cp0xxx            | Notebook    | [e87b8175b1](https://linux-hardware.org/?probe=e87b8175b1) | Jan 27, 2023 |
| HP         | Laptop 17-cp0xxx            | Notebook    | [70019cbdbf](https://linux-hardware.org/?probe=70019cbdbf) | Jan 25, 2023 |
| Google     | Lick                        | Notebook    | [d792b79719](https://linux-hardware.org/?probe=d792b79719) | Jan 12, 2023 |
| Intel      | NUC12WSBi7 M46422-303       | Mini pc     | [3ddd96770b](https://linux-hardware.org/?probe=3ddd96770b) | Dec 24, 2022 |
| Intel      | NUC12WSBi7 M46422-303       | Mini pc     | [8f10e15f9a](https://linux-hardware.org/?probe=8f10e15f9a) | Dec 24, 2022 |
| Panasonic  | CF-53AAG54FM                | Notebook    | [cf7f652846](https://linux-hardware.org/?probe=cf7f652846) | Dec 21, 2022 |
| Lenovo     | ThinkPad T470 20HES0E71M    | Notebook    | [85fc801717](https://linux-hardware.org/?probe=85fc801717) | Dec 05, 2022 |
| ASUSTek    | PRIME B560M-A AC            | Desktop     | [d4cc718e46](https://linux-hardware.org/?probe=d4cc718e46) | Nov 29, 2022 |
| Lenovo     | ThinkPad P70 20ESS04S00     | Notebook    | [01b85c4c2a](https://linux-hardware.org/?probe=01b85c4c2a) | Nov 10, 2022 |
| Lenovo     | ThinkPad T470 20HES21434    | Notebook    | [39ff1846e3](https://linux-hardware.org/?probe=39ff1846e3) | Oct 23, 2022 |
| Fujitsu    | D2759 S26361-D2759-A13 W... | Server      | [c4c0b53877](https://linux-hardware.org/?probe=c4c0b53877) | Oct 23, 2022 |
| Dynabook   | PORTEGE X40-G               | Notebook    | [fc68a9cdbf](https://linux-hardware.org/?probe=fc68a9cdbf) | Oct 03, 2022 |
| Dell       | 0DC48C A02                  | Desktop     | [9292e820c5](https://linux-hardware.org/?probe=9292e820c5) | Sep 27, 2022 |
| HP         | EliteBook 840 G5            | Notebook    | [2709daf415](https://linux-hardware.org/?probe=2709daf415) | Sep 13, 2022 |
| ASUSTek    | H81M-A                      | Desktop     | [a37e952875](https://linux-hardware.org/?probe=a37e952875) | Sep 04, 2022 |
| Lenovo     | Legion 5 15IMH05 82AU       | Notebook    | [bd4737dfcf](https://linux-hardware.org/?probe=bd4737dfcf) | Aug 18, 2022 |
| Dell       | Inspiron 5502               | Notebook    | [28dcf01e88](https://linux-hardware.org/?probe=28dcf01e88) | Aug 03, 2022 |
| Dell       | 073Y7Y A00                  | Desktop     | [3bed97b23e](https://linux-hardware.org/?probe=3bed97b23e) | Jul 21, 2022 |
| Lenovo     | Legion 5 15IMH05 82AU       | Notebook    | [3dddb3aac3](https://linux-hardware.org/?probe=3dddb3aac3) | Jul 20, 2022 |
| MSI        | Z77A-G43                    | Desktop     | [909e3e3c2e](https://linux-hardware.org/?probe=909e3e3c2e) | Jun 29, 2022 |
| ASUSTek    | P8H67                       | Desktop     | [b194dad4cf](https://linux-hardware.org/?probe=b194dad4cf) | Jun 25, 2022 |
| Lenovo     | ThinkPad P70 20ESS04S00     | Notebook    | [fc29967bed](https://linux-hardware.org/?probe=fc29967bed) | Jun 17, 2022 |
| HP         | Compaq 6730b                | Notebook    | [dd94c9145b](https://linux-hardware.org/?probe=dd94c9145b) | Jun 11, 2022 |
| Lenovo     | ThinkPad T410 2518A37       | Notebook    | [04e81b8b3f](https://linux-hardware.org/?probe=04e81b8b3f) | Jun 04, 2022 |
| Lenovo     | ThinkPad T430s 2355C33      | Notebook    | [33de2bbd12](https://linux-hardware.org/?probe=33de2bbd12) | May 31, 2022 |
| Lenovo     | ThinkPad T430s 2355C33      | Notebook    | [4eab57bebf](https://linux-hardware.org/?probe=4eab57bebf) | May 30, 2022 |
| Dell       | Precision M4600             | Notebook    | [0ac2adfe5a](https://linux-hardware.org/?probe=0ac2adfe5a) | Apr 21, 2022 |
| Dell       | Precision M4800             | Notebook    | [fb13b19803](https://linux-hardware.org/?probe=fb13b19803) | Apr 21, 2022 |
| Lenovo     | ThinkPad P50s 20FL000MUS    | Notebook    | [99fbb4446c](https://linux-hardware.org/?probe=99fbb4446c) | Apr 16, 2022 |
| Dell       | 0C522T A03                  | Desktop     | [3dc84dc8ff](https://linux-hardware.org/?probe=3dc84dc8ff) | Mar 24, 2022 |
| Lenovo     | ThinkPad X1 Extreme 2nd ... | Notebook    | [b708e920f3](https://linux-hardware.org/?probe=b708e920f3) | Mar 21, 2022 |
| Lenovo     | ThinkPad T450 20BUS14900    | Notebook    | [bd60aae97a](https://linux-hardware.org/?probe=bd60aae97a) | Mar 11, 2022 |
| Lenovo     | ThinkPad T480 20L5A07TAU    | Notebook    | [755854f7d4](https://linux-hardware.org/?probe=755854f7d4) | Mar 11, 2022 |
| Lenovo     | ThinkPad X280 20KES4H34G    | Notebook    | [2b8a4f4664](https://linux-hardware.org/?probe=2b8a4f4664) | Mar 10, 2022 |
| Dell       | Latitude 7420               | Notebook    | [af5f1055fe](https://linux-hardware.org/?probe=af5f1055fe) | Mar 10, 2022 |
| HP         | ProBook 445 G6              | Notebook    | [88d8b32328](https://linux-hardware.org/?probe=88d8b32328) | Jan 26, 2022 |
| Lenovo     | ThinkPad X390 Yoga 20NQS... | Convertible | [8219e32fef](https://linux-hardware.org/?probe=8219e32fef) | Dec 22, 2021 |
| Lenovo     | ThinkPad T450 20BUS14900    | Notebook    | [44c8e11f02](https://linux-hardware.org/?probe=44c8e11f02) | Dec 22, 2021 |
| Lenovo     | IdeaPad 300-15ISK 80RS      | Notebook    | [1c9ca21f4e](https://linux-hardware.org/?probe=1c9ca21f4e) | Dec 10, 2021 |
| Dell       | Latitude 7410               | Notebook    | [3efa87284e](https://linux-hardware.org/?probe=3efa87284e) | Nov 18, 2021 |
| Dell       | Latitude E6420              | Notebook    | [b809392380](https://linux-hardware.org/?probe=b809392380) | Oct 08, 2021 |
| Lenovo     | IdeaPad C340-14IWL 81RL     | Convertible | [cf3c570b7a](https://linux-hardware.org/?probe=cf3c570b7a) | Sep 27, 2021 |
| Dell       | Latitude 7410               | Notebook    | [8f1a1a4798](https://linux-hardware.org/?probe=8f1a1a4798) | Sep 06, 2021 |
| Dell       | Latitude 7410               | Notebook    | [b03a0e0152](https://linux-hardware.org/?probe=b03a0e0152) | Sep 06, 2021 |
| Lenovo     | Legion 5 15IMH05 82AU       | Notebook    | [7b393c5790](https://linux-hardware.org/?probe=7b393c5790) | Aug 21, 2021 |
| Lenovo     | Legion 5 15IMH05 82AU       | Notebook    | [394c99adc8](https://linux-hardware.org/?probe=394c99adc8) | Aug 19, 2021 |
| Dell       | Inspiron 3542               | Notebook    | [0909599e9c](https://linux-hardware.org/?probe=0909599e9c) | Aug 11, 2021 |
| Lenovo     | Legion 5 15IMH05 82AU       | Notebook    | [ba7afba1a6](https://linux-hardware.org/?probe=ba7afba1a6) | Jul 08, 2021 |
| Lenovo     | ThinkPad L490 20Q5CTO1WW    | Notebook    | [0225c17d79](https://linux-hardware.org/?probe=0225c17d79) | Jul 02, 2021 |
| Lenovo     | Legion 5 15IMH05 82AU       | Notebook    | [505b82b2de](https://linux-hardware.org/?probe=505b82b2de) | Jun 06, 2021 |
| Lenovo     | Legion 5 15IMH05 82AU       | Notebook    | [75b2ef5126](https://linux-hardware.org/?probe=75b2ef5126) | May 13, 2021 |
| Lenovo     | Legion 5 15IMH05 82AU       | Notebook    | [734a4fbc56](https://linux-hardware.org/?probe=734a4fbc56) | May 09, 2021 |
| Gigabyte   | Z490 AORUS ELITE AC         | Desktop     | [978ae6f2cb](https://linux-hardware.org/?probe=978ae6f2cb) | May 02, 2021 |
| ASUSTek    | UX305FA                     | Notebook    | [0bf50fba2d](https://linux-hardware.org/?probe=0bf50fba2d) | Mar 15, 2021 |
| Lenovo     | IdeaPad Slim 1-14AST-05 ... | Notebook    | [ff355a9bb1](https://linux-hardware.org/?probe=ff355a9bb1) | Mar 11, 2021 |
| Gigabyte   | X99-Designare EX-CF         | Desktop     | [5195396549](https://linux-hardware.org/?probe=5195396549) | Mar 06, 2021 |
| Lenovo     | IdeaPad Slim 1-14AST-05 ... | Notebook    | [9f67379954](https://linux-hardware.org/?probe=9f67379954) | Mar 04, 2021 |
| Lenovo     | ThinkPad L490 20Q5CTO1WW    | Notebook    | [db0f24aee5](https://linux-hardware.org/?probe=db0f24aee5) | Mar 01, 2021 |
| Dell       | Latitude 7410               | Notebook    | [5b725b01aa](https://linux-hardware.org/?probe=5b725b01aa) | Feb 26, 2021 |
| Lenovo     | Legion 5 15IMH05 82AU       | Notebook    | [835e8cad03](https://linux-hardware.org/?probe=835e8cad03) | Feb 25, 2021 |
| Dell       | Latitude 7410               | Notebook    | [430ac9fa0c](https://linux-hardware.org/?probe=430ac9fa0c) | Feb 24, 2021 |
| Lenovo     | ThinkPad T490 20N3S77600    | Notebook    | [26e61c39f2](https://linux-hardware.org/?probe=26e61c39f2) | Feb 24, 2021 |
| Dell       | Latitude 7410               | Notebook    | [7aeb2cc674](https://linux-hardware.org/?probe=7aeb2cc674) | Feb 22, 2021 |
| Lenovo     | IdeaPad Slim 1-14AST-05 ... | Notebook    | [8af2c8d83c](https://linux-hardware.org/?probe=8af2c8d83c) | Feb 05, 2021 |
| ASUSTek    | G11CD                       | Desktop     | [13961e12a8](https://linux-hardware.org/?probe=13961e12a8) | Feb 01, 2021 |
| HP         | 158B                        | Desktop     | [5e6b9531d7](https://linux-hardware.org/?probe=5e6b9531d7) | Feb 01, 2021 |
| Dell       | PowerEdge FC630             | Desktop     | [bcd33a41f0](https://linux-hardware.org/?probe=bcd33a41f0) | Jan 25, 2021 |
| Gigabyte   | X470 AORUS ULTRA GAMING-... | Desktop     | [71628a95b6](https://linux-hardware.org/?probe=71628a95b6) | Jan 13, 2021 |
| Lenovo     | IdeaPad Slim 1-14AST-05 ... | Notebook    | [7ea3c87bfe](https://linux-hardware.org/?probe=7ea3c87bfe) | Jan 06, 2021 |
| Foxconn    | 2ADA                        | Desktop     | [809e03aea5](https://linux-hardware.org/?probe=809e03aea5) | Dec 24, 2020 |
| ASUSTek    | G11CD                       | Desktop     | [d9d0f8fdf2](https://linux-hardware.org/?probe=d9d0f8fdf2) | Dec 20, 2020 |
| Standard   | BW Series                   | Notebook    | [1f6cf82ba8](https://linux-hardware.org/?probe=1f6cf82ba8) | Jun 13, 2020 |
| Apple      | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [109e02e0f2](https://linux-hardware.org/?probe=109e02e0f2) | Jun 07, 2020 |
| Apple      | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [2d385b9cb0](https://linux-hardware.org/?probe=2d385b9cb0) | Jun 07, 2020 |
| HP         | Notebook                    | Notebook    | [e3c242a846](https://linux-hardware.org/?probe=e3c242a846) | May 24, 2020 |
| Lenovo     | ThinkPad L490 20Q5CTO1WW    | Notebook    | [d8b2c132c1](https://linux-hardware.org/?probe=d8b2c132c1) | Apr 09, 2020 |
| HP         | ZBook 15                    | Notebook    | [4723616d8c](https://linux-hardware.org/?probe=4723616d8c) | Apr 09, 2020 |
| Lenovo     | ThinkPad L490 20Q5CTO1WW    | Notebook    | [1acbabb197](https://linux-hardware.org/?probe=1acbabb197) | Apr 06, 2020 |
| Lenovo     | ThinkPad T480 20L6S56Y2X    | Notebook    | [5343997520](https://linux-hardware.org/?probe=5343997520) | Feb 23, 2020 |
| Dell       | 0C96W1 A01                  | Desktop     | [b5c14107bb](https://linux-hardware.org/?probe=b5c14107bb) | Feb 12, 2020 |
| ASUSTek    | X510UR                      | Notebook    | [914b9fbe64](https://linux-hardware.org/?probe=914b9fbe64) | Feb 04, 2020 |
| ASUSTek    | X510UR                      | Notebook    | [014d5ef0c8](https://linux-hardware.org/?probe=014d5ef0c8) | Jan 28, 2020 |
| ASUSTek    | X510UR                      | Notebook    | [9d05b420d4](https://linux-hardware.org/?probe=9d05b420d4) | Jan 28, 2020 |
| Lenovo     | ThinkPad L540 20AVCTO1WW    | Notebook    | [8c1dba9d6e](https://linux-hardware.org/?probe=8c1dba9d6e) | Sep 10, 2019 |
| HPE        | ProLiant BL460c Gen10       | Server      | [9e91d0ed19](https://linux-hardware.org/?probe=9e91d0ed19) | Jun 14, 2019 |
| Lenovo     | ThinkPad T480 20L6S56Y2X    | Notebook    | [f012a475eb](https://linux-hardware.org/?probe=f012a475eb) | Apr 11, 2019 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Oracle Linux 8.5 | 13        | 17.11%  |
| Oracle Linux 8.3 | 12        | 15.79%  |
| Oracle Linux 8.4 | 7         | 9.21%   |
| Oracle Linux 8.6 | 6         | 7.89%   |
| Oracle Linux 9.1 | 5         | 6.58%   |
| Oracle Linux 9.0 | 5         | 6.58%   |
| Oracle Linux 8.7 | 5         | 6.58%   |
| Oracle Linux 9.2 | 4         | 5.26%   |
| Oracle Linux 7.9 | 4         | 5.26%   |
| Oracle Linux 8.1 | 3         | 3.95%   |
| Oracle Linux 7.7 | 3         | 3.95%   |
| Oracle Linux 8.8 | 2         | 2.63%   |
| Oracle Linux 8.2 | 2         | 2.63%   |
| Oracle Linux 7.8 | 2         | 2.63%   |
| Oracle Linux 7.6 | 2         | 2.63%   |
| Oracle Linux 7.4 | 1         | 1.32%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Oracle Linux | 69        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                           | Computers | Percent |
|-----------------------------------|-----------|---------|
| 5.4.17-2102.202.5.el8uek.x86_64   | 3         | 3.66%   |
| 5.4.17-2036.103.3.1.el8uek.x86_64 | 3         | 3.66%   |
| 5.15.0-2.52.3.el9uek.x86_64       | 3         | 3.66%   |
| 5.15.0-100.96.32.el8uek.x86_64    | 3         | 3.66%   |
| 4.18.0-348.12.2.el8_5.x86_64      | 3         | 3.66%   |
| 5.4.17-2136.313.6.el8uek.x86_64   | 2         | 2.44%   |
| 5.4.17-2136.304.4.3.el8uek.x86_64 | 2         | 2.44%   |
| 5.4.17-2136.300.7.el8uek.x86_64   | 2         | 2.44%   |
| 5.4.17-2102.205.7.3.el8uek.x86_64 | 2         | 2.44%   |
| 5.4.17-2102.200.13.el8uek.x86_64  | 2         | 2.44%   |
| 5.4.17-2036.102.0.2.el8uek.x86_64 | 2         | 2.44%   |
| 5.4.17-2036.101.2.el8uek.x86_64   | 2         | 2.44%   |
| 5.15.0-5.76.5.1.el9uek.x86_64     | 2         | 2.44%   |
| 5.15.0-101.103.2.1.el9uek.x86_64  | 2         | 2.44%   |
| 4.18.0-240.15.1.el8_3.x86_64      | 2         | 2.44%   |
| 4.18.0-193.1.2.el8_2.x86_64       | 2         | 2.44%   |
| 4.18.0-147.3.1.el8_1.x86_64       | 2         | 2.44%   |
| 5.4.17-2136.312.3.4.el7uek.x86_64 | 1         | 1.22%   |
| 5.4.17-2136.310.7.el8uek.x86_64   | 1         | 1.22%   |
| 5.4.17-2136.310.7.1.el8uek.x86_64 | 1         | 1.22%   |
| 5.4.17-2136.309.4.el8uek.x86_64   | 1         | 1.22%   |
| 5.4.17-2136.308.9.el8uek.x86_64   | 1         | 1.22%   |
| 5.4.17-2136.308.9.el7uek.x86_64   | 1         | 1.22%   |
| 5.4.17-2136.307.3.1.el8uek.x86_64 | 1         | 1.22%   |
| 5.4.17-2136.306.1.3.el8uek.x86_64 | 1         | 1.22%   |
| 5.4.17-2136.305.5.4.el8uek.x86_64 | 1         | 1.22%   |
| 5.4.17-2136.305.5.3.el8uek.x86_64 | 1         | 1.22%   |
| 5.4.17-2136.305.5.2.el8uek.x86_64 | 1         | 1.22%   |
| 5.4.17-2136.301.1.4.el8uek.x86_64 | 1         | 1.22%   |
| 5.4.17-2102.204.4.4.el8uek.x86_64 | 1         | 1.22%   |
| 5.4.17-2102.204.4.2.el8uek.x86_64 | 1         | 1.22%   |
| 5.4.17-2102.201.3.el8uek.x86_64   | 1         | 1.22%   |
| 5.4.17-2036.104.4.el8uek.x86_64   | 1         | 1.22%   |
| 5.4.17-2036.100.6.1.el8uek.x86_64 | 1         | 1.22%   |
| 5.4.17-2011.0.7.el8uek.x86_64     | 1         | 1.22%   |
| 5.4.11-1.el7.elrepo.x86_64        | 1         | 1.22%   |
| 5.15.2-1.el8.elrepo.x86_64        | 1         | 1.22%   |
| 5.15.0-6.80.3.1.el9uek.x86_64     | 1         | 1.22%   |
| 5.15.0-102.110.5.1.el9uek.x86_64  | 1         | 1.22%   |
| 5.15.0-101.103.2.1.el8uek.x86_64  | 1         | 1.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.17  | 28        | 39.44%  |
| 5.15.0  | 16        | 22.54%  |
| 4.18.0  | 12        | 16.9%   |
| 4.14.35 | 5         | 7.04%   |
| 3.10.0  | 3         | 4.23%   |
| 5.14.0  | 2         | 2.82%   |
| 5.4.11  | 1         | 1.41%   |
| 5.15.2  | 1         | 1.41%   |
| 5.14.1  | 1         | 1.41%   |
| 5.11.1  | 1         | 1.41%   |
| 4.1.12  | 1         | 1.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 29        | 40.85%  |
| 5.15    | 17        | 23.94%  |
| 4.18    | 12        | 16.9%   |
| 4.14    | 5         | 7.04%   |
| 5.14    | 3         | 4.23%   |
| 3.10    | 3         | 4.23%   |
| 5.11    | 1         | 1.41%   |
| 4.1     | 1         | 1.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 69        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 52        | 71.23%  |
| Unknown       | 10        | 13.7%   |
| GNOME Classic | 3         | 4.11%   |
| XFCE          | 2         | 2.74%   |
| MATE          | 2         | 2.74%   |
| KDE5          | 2         | 2.74%   |
| KDE4          | 2         | 2.74%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 38        | 53.52%  |
| X11     | 24        | 33.8%   |
| Unknown | 7         | 9.86%   |
| Web     | 1         | 1.41%   |
| Tty     | 1         | 1.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 36        | 50.7%   |
| GDM     | 32        | 45.07%  |
| SDDM    | 2         | 2.82%   |
| TDM     | 1         | 1.41%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 43        | 61.43%  |
| en_GB      | 7         | 10%     |
| de_DE      | 4         | 5.71%   |
| Unknown    | 4         | 5.71%   |
| pl_PL      | 2         | 2.86%   |
| it_IT      | 2         | 2.86%   |
| en_IN      | 2         | 2.86%   |
| en_AU      | 2         | 2.86%   |
| zh_HK      | 1         | 1.43%   |
| ru_RU      | 1         | 1.43%   |
| pt_BR      | 1         | 1.43%   |
| en_US.UTF8 | 1         | 1.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 38        | 54.29%  |
| BIOS | 32        | 45.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 60        | 84.51%  |
| Ext4    | 8         | 11.27%  |
| Unknown | 2         | 2.82%   |
| Zfs     | 1         | 1.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 30        | 42.25%  |
| GPT     | 28        | 39.44%  |
| MBR     | 13        | 18.31%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 64        | 91.43%  |
| Yes       | 6         | 8.57%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 67        | 97.1%   |
| Yes       | 2         | 2.9%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 21        | 30.43%  |
| Dell                | 13        | 18.84%  |
| Hewlett-Packard     | 8         | 11.59%  |
| ASUSTek Computer    | 8         | 11.59%  |
| Gigabyte Technology | 4         | 5.8%    |
| Intel               | 3         | 4.35%   |
| Supermicro          | 1         | 1.45%   |
| Standard            | 1         | 1.45%   |
| Panasonic           | 1         | 1.45%   |
| MSI                 | 1         | 1.45%   |
| HPE                 | 1         | 1.45%   |
| Google              | 1         | 1.45%   |
| Fujitsu             | 1         | 1.45%   |
| Foxconn             | 1         | 1.45%   |
| Dynabook            | 1         | 1.45%   |
| Cisco               | 1         | 1.45%   |
| ASRock              | 1         | 1.45%   |
| Apple               | 1         | 1.45%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Lenovo ThinkPad T450 20BUS14900           | 2         | 2.9%    |
| ASUS X510UR                               | 2         | 2.9%    |
| Supermicro X8DTU                          | 1         | 1.45%   |
| Standard BW Series                        | 1         | 1.45%   |
| Panasonic CF-53AAG54FM                    | 1         | 1.45%   |
| MSI MS-7758                               | 1         | 1.45%   |
| Lenovo ThinkPad X390 Yoga 20NQS2SF00      | 1         | 1.45%   |
| Lenovo ThinkPad X280 20KES4H34G           | 1         | 1.45%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QWS1R800 | 1         | 1.45%   |
| Lenovo ThinkPad W541 20EGS1PL00           | 1         | 1.45%   |
| Lenovo ThinkPad T490 20N3S77600           | 1         | 1.45%   |
| Lenovo ThinkPad T490 20N3S3XR00           | 1         | 1.45%   |
| Lenovo ThinkPad T480 20L6S56Y2X           | 1         | 1.45%   |
| Lenovo ThinkPad T480 20L5A07TAU           | 1         | 1.45%   |
| Lenovo ThinkPad T470 20HES21434           | 1         | 1.45%   |
| Lenovo ThinkPad T470 20HES0E71M           | 1         | 1.45%   |
| Lenovo ThinkPad T430s 2355C33             | 1         | 1.45%   |
| Lenovo ThinkPad P70 20ESS04S00            | 1         | 1.45%   |
| Lenovo ThinkPad P50s 20FL000MUS           | 1         | 1.45%   |
| Lenovo ThinkPad L540 20AVCTO1WW           | 1         | 1.45%   |
| Lenovo ThinkPad L490 20Q5CTO1WW           | 1         | 1.45%   |
| Lenovo Legion 5 15IMH05 82AU              | 1         | 1.45%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS       | 1         | 1.45%   |
| Lenovo IdeaPad C340-14IWL 81RL            | 1         | 1.45%   |
| Lenovo IdeaPad 300-15ISK 80RS             | 1         | 1.45%   |
| Intel NUC6CAYH                            | 1         | 1.45%   |
| Intel NUC12WSHi7                          | 1         | 1.45%   |
| Intel NUC12WSHi5                          | 1         | 1.45%   |
| HPE ProLiant BL460c Gen10                 | 1         | 1.45%   |
| HP ZBook 15                               | 1         | 1.45%   |
| HP Z820 Workstation                       | 1         | 1.45%   |
| HP Z420 Workstation                       | 1         | 1.45%   |
| HP ProBook 445 G6                         | 1         | 1.45%   |
| HP Notebook                               | 1         | 1.45%   |
| HP Laptop 17-cp0xxx                       | 1         | 1.45%   |
| HP EliteBook 840 G5                       | 1         | 1.45%   |
| HP Compaq 6730b                           | 1         | 1.45%   |
| Google Lick                               | 1         | 1.45%   |
| Gigabyte Z490 AORUS ELITE AC              | 1         | 1.45%   |
| Gigabyte X99-Designare EX-CF              | 1         | 1.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 17        | 24.64%  |
| Dell OptiPlex          | 4         | 5.8%    |
| Dell Latitude          | 4         | 5.8%    |
| Lenovo IdeaPad         | 3         | 4.35%   |
| Dell Precision         | 2         | 2.9%    |
| Dell Inspiron          | 2         | 2.9%    |
| ASUS X510UR            | 2         | 2.9%    |
| Supermicro X8DTU       | 1         | 1.45%   |
| Standard BW            | 1         | 1.45%   |
| Panasonic CF-53AAG54FM | 1         | 1.45%   |
| MSI MS-7758            | 1         | 1.45%   |
| Lenovo Legion          | 1         | 1.45%   |
| Intel NUC6CAYH         | 1         | 1.45%   |
| Intel NUC12WSHi7       | 1         | 1.45%   |
| Intel NUC12WSHi5       | 1         | 1.45%   |
| HPE ProLiant           | 1         | 1.45%   |
| HP ZBook               | 1         | 1.45%   |
| HP Z820                | 1         | 1.45%   |
| HP Z420                | 1         | 1.45%   |
| HP ProBook             | 1         | 1.45%   |
| HP Notebook            | 1         | 1.45%   |
| HP Laptop              | 1         | 1.45%   |
| HP EliteBook           | 1         | 1.45%   |
| HP Compaq              | 1         | 1.45%   |
| Google Lick            | 1         | 1.45%   |
| Gigabyte Z490          | 1         | 1.45%   |
| Gigabyte X99-Designare | 1         | 1.45%   |
| Gigabyte X470          | 1         | 1.45%   |
| Gigabyte H81M-S2PV     | 1         | 1.45%   |
| Fujitsu PRIMERGY       | 1         | 1.45%   |
| Foxconn p6-2400el      | 1         | 1.45%   |
| Dynabook PORTEGE       | 1         | 1.45%   |
| Dell PowerEdge         | 1         | 1.45%   |
| Cisco WAVE-694-K9      | 1         | 1.45%   |
| ASUS ZenBook           | 1         | 1.45%   |
| ASUS UX305FA           | 1         | 1.45%   |
| ASUS PRIME             | 1         | 1.45%   |
| ASUS P8H67             | 1         | 1.45%   |
| ASUS G11CD             | 1         | 1.45%   |
| ASUS All               | 1         | 1.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 9         | 13.04%  |
| 2018 | 8         | 11.59%  |
| 2020 | 6         | 8.7%    |
| 2016 | 6         | 8.7%    |
| 2014 | 6         | 8.7%    |
| 2012 | 6         | 8.7%    |
| 2022 | 5         | 7.25%   |
| 2021 | 4         | 5.8%    |
| 2017 | 4         | 5.8%    |
| 2011 | 4         | 5.8%    |
| 2015 | 3         | 4.35%   |
| 2013 | 3         | 4.35%   |
| 2010 | 3         | 4.35%   |
| 2009 | 1         | 1.45%   |
| 2008 | 1         | 1.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 41        | 59.42%  |
| Desktop     | 19        | 27.54%  |
| Mini pc     | 4         | 5.8%    |
| Server      | 3         | 4.35%   |
| Convertible | 2         | 2.9%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 60        | 85.71%  |
| Enabled  | 10        | 14.29%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 68        | 98.55%  |
| Yes  | 1         | 1.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 19        | 27.14%  |
| 32.01-64.0      | 16        | 22.86%  |
| 4.01-8.0        | 11        | 15.71%  |
| 3.01-4.0        | 6         | 8.57%   |
| 64.01-256.0     | 6         | 8.57%   |
| 16.01-24.0      | 6         | 8.57%   |
| 24.01-32.0      | 4         | 5.71%   |
| More than 256.0 | 1         | 1.43%   |
| 1.01-2.0        | 1         | 1.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 22        | 28.57%  |
| 2.01-3.0    | 19        | 24.68%  |
| 3.01-4.0    | 11        | 14.29%  |
| 1.01-2.0    | 9         | 11.69%  |
| 8.01-16.0   | 9         | 11.69%  |
| 0.51-1.0    | 3         | 3.9%    |
| 24.01-32.0  | 1         | 1.3%    |
| 64.01-256.0 | 1         | 1.3%    |
| 16.01-24.0  | 1         | 1.3%    |
| 0.01-0.5    | 1         | 1.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 51        | 72.86%  |
| 2      | 12        | 17.14%  |
| 3      | 3         | 4.29%   |
| 4      | 2         | 2.86%   |
| 6      | 1         | 1.43%   |
| 5      | 1         | 1.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 54        | 78.26%  |
| Yes       | 15        | 21.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 85.51%  |
| No        | 10        | 14.49%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 75.36%  |
| No        | 17        | 24.64%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 55.71%  |
| No        | 31        | 44.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 22        | 31.43%  |
| Germany     | 8         | 11.43%  |
| UK          | 4         | 5.71%   |
| Poland      | 4         | 5.71%   |
| Brazil      | 4         | 5.71%   |
| Netherlands | 3         | 4.29%   |
| Finland     | 3         | 4.29%   |
| Australia   | 3         | 4.29%   |
| Russia      | 2         | 2.86%   |
| Romania     | 2         | 2.86%   |
| Italy       | 2         | 2.86%   |
| India       | 2         | 2.86%   |
| Yemen       | 1         | 1.43%   |
| Turkey      | 1         | 1.43%   |
| Slovakia    | 1         | 1.43%   |
| Pakistan    | 1         | 1.43%   |
| Latvia      | 1         | 1.43%   |
| Kazakhstan  | 1         | 1.43%   |
| Hungary     | 1         | 1.43%   |
| Hong Kong   | 1         | 1.43%   |
| Bulgaria    | 1         | 1.43%   |
| Bolivia     | 1         | 1.43%   |
| Argentina   | 1         | 1.43%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| San Diego          | 3         | 4%      |
| Helsinki           | 3         | 4%      |
| Siegen             | 2         | 2.67%   |
| Seattle            | 2         | 2.67%   |
| Sao Paulo          | 2         | 2.67%   |
| Colorado Springs   | 2         | 2.67%   |
| Bucharest          | 2         | 2.67%   |
| Berlin             | 2         | 2.67%   |
| Amsterdam          | 2         | 2.67%   |
| Zavar              | 1         | 1.33%   |
| Weaverville        | 1         | 1.33%   |
| Warsaw             | 1         | 1.33%   |
| Veliky Novgorod    | 1         | 1.33%   |
| Valmiera           | 1         | 1.33%   |
| Utrecht            | 1         | 1.33%   |
| Sydney             | 1         | 1.33%   |
| Sofia              | 1         | 1.33%   |
| Shrewsbury         | 1         | 1.33%   |
| Sao Caetano do Sul | 1         | 1.33%   |
| Santa Cruz         | 1         | 1.33%   |
| Sanaa              | 1         | 1.33%   |
| San Francisco      | 1         | 1.33%   |
| Rocklin            | 1         | 1.33%   |
| Riverside          | 1         | 1.33%   |
| Redwood City       | 1         | 1.33%   |
| Reading            | 1         | 1.33%   |
| Port Saint Lucie   | 1         | 1.33%   |
| Pleven             | 1         | 1.33%   |
| Petersberg         | 1         | 1.33%   |
| Perugia            | 1         | 1.33%   |
| Parker             | 1         | 1.33%   |
| Ngau Wu Tok        | 1         | 1.33%   |
| Neunkirchen        | 1         | 1.33%   |
| Nagercoil          | 1         | 1.33%   |
| Moscow             | 1         | 1.33%   |
| Maple Valley       | 1         | 1.33%   |
| Lynnwood           | 1         | 1.33%   |
| Ludwigsburg        | 1         | 1.33%   |
| London             | 1         | 1.33%   |
| Las Vegas          | 1         | 1.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 22        | 28     | 24.72%  |
| Seagate                 | 12        | 50     | 13.48%  |
| SanDisk                 | 8         | 11     | 8.99%   |
| WDC                     | 7         | 8      | 7.87%   |
| Unknown                 | 4         | 6      | 4.49%   |
| Toshiba                 | 4         | 4      | 4.49%   |
| Crucial                 | 4         | 5      | 4.49%   |
| Kingston                | 3         | 10     | 3.37%   |
| Intel                   | 3         | 3      | 3.37%   |
| HGST                    | 3         | 6      | 3.37%   |
| SK hynix                | 2         | 2      | 2.25%   |
| Phison Electronics      | 2         | 2      | 2.25%   |
| Micron Technology       | 2         | 5      | 2.25%   |
| Hewlett-Packard         | 2         | 2      | 2.25%   |
| Union Memory (Shenzhen) | 1         | 2      | 1.12%   |
| Transcend               | 1         | 1      | 1.12%   |
| Phison                  | 1         | 1      | 1.12%   |
| Lite-On                 | 1         | 1      | 1.12%   |
| Lenovo                  | 1         | 1      | 1.12%   |
| KIOXIA                  | 1         | 1      | 1.12%   |
| JMicron Technology      | 1         | 1      | 1.12%   |
| HPE                     | 1         | 1      | 1.12%   |
| GOODRAM                 | 1         | 1      | 1.12%   |
| Fujitsu                 | 1         | 1      | 1.12%   |
| Apple                   | 1         | 1      | 1.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seagate ST2000DM008-2FR102 2TB               | 2         | 2.11%   |
| SanDisk SSD PLUS 1000GB                      | 2         | 2.11%   |
| Samsung SSD PM830 2.5 7mm 256GB              | 2         | 2.11%   |
| Samsung MZVLB512HAJQ-000L7 512GB             | 2         | 2.11%   |
| Samsung MZ7LN512HMJP-000L7 512GB SSD         | 2         | 2.11%   |
| Kingston SA400S37240G 240GB SSD              | 2         | 2.11%   |
| Crucial CT500MX500SSD1 500GB                 | 2         | 2.11%   |
| WDC WDS500G2B0A-00SM50 500GB SSD             | 1         | 1.05%   |
| WDC WDS250G2B0A-00SM50 250GB SSD             | 1         | 1.05%   |
| WDC WD3200BEKT-08PVMT1 320GB                 | 1         | 1.05%   |
| WDC WD1600YS-23SHB0 160GB                    | 1         | 1.05%   |
| WDC WD10SPZX-60Z10T1 1TB                     | 1         | 1.05%   |
| WDC WD10JPCX-24UE4T0 1TB                     | 1         | 1.05%   |
| WDC WD10EZEX-60M2NA0 1TB                     | 1         | 1.05%   |
| Unknown SD/MMC/MS PRO 250GB                  | 1         | 1.05%   |
| Unknown MMC64G  64GB                         | 1         | 1.05%   |
| Unknown MMC Card  256GB                      | 1         | 1.05%   |
| Unknown MMC Card  1TB                        | 1         | 1.05%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 1.05%   |
| Transcend TS2TMTE250H 2TB                    | 1         | 1.05%   |
| Toshiba THNSNJ512GCSU 512GB SSD              | 1         | 1.05%   |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 1.05%   |
| Toshiba MG04ACA200E 2TB                      | 1         | 1.05%   |
| Toshiba DT01ACA050 500GB                     | 1         | 1.05%   |
| SK hynix SKHynix_HFS256GD9TNG-L3A0B 256GB    | 1         | 1.05%   |
| SK hynix PC801 NVMe 512GB                    | 1         | 1.05%   |
| Seagate ST9750420AS 752GB                    | 1         | 1.05%   |
| Seagate ST8000VN004-2M2101 8TB               | 1         | 1.05%   |
| Seagate ST3750528AS 752GB                    | 1         | 1.05%   |
| Seagate ST3500414CS 500GB                    | 1         | 1.05%   |
| Seagate ST2000NX0253 2TB                     | 1         | 1.05%   |
| Seagate ST2000DM001-1ER164 2TB               | 1         | 1.05%   |
| Seagate ST1000VX000-1ES162 1TB               | 1         | 1.05%   |
| Seagate ST1000NX0423 1TB                     | 1         | 1.05%   |
| Seagate ST1000LX015-1U7172 1TB               | 1         | 1.05%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1.05%   |
| Seagate ST1000LM010-9YH146 1TB               | 1         | 1.05%   |
| Seagate BUP Slim BK 1TB                      | 1         | 1.05%   |
| SanDisk SSD PLUS 2000GB                      | 1         | 1.05%   |
| SanDisk SDSSDH3512G 512GB                    | 1         | 1.05%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 50     | 41.38%  |
| WDC                 | 5         | 6      | 17.24%  |
| HGST                | 3         | 6      | 10.34%  |
| Toshiba             | 2         | 2      | 6.9%    |
| Samsung Electronics | 2         | 2      | 6.9%    |
| Unknown             | 1         | 3      | 3.45%   |
| JMicron Technology  | 1         | 1      | 3.45%   |
| HPE                 | 1         | 1      | 3.45%   |
| Fujitsu             | 1         | 1      | 3.45%   |
| Apple               | 1         | 1      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 15     | 40%     |
| SanDisk             | 6         | 8      | 20%     |
| Crucial             | 3         | 4      | 10%     |
| WDC                 | 2         | 2      | 6.67%   |
| Kingston            | 2         | 3      | 6.67%   |
| Hewlett-Packard     | 2         | 2      | 6.67%   |
| Toshiba             | 1         | 1      | 3.33%   |
| Intel               | 1         | 1      | 3.33%   |
| GOODRAM             | 1         | 1      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 28        | 41     | 32.94%  |
| SSD  | 28        | 37     | 32.94%  |
| HDD  | 26        | 73     | 30.59%  |
| MMC  | 3         | 3      | 3.53%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 45        | 104    | 56.96%  |
| NVMe | 28        | 41     | 35.44%  |
| SAS  | 3         | 6      | 3.8%    |
| MMC  | 3         | 3      | 3.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 24        | 31     | 43.64%  |
| 0.51-1.0   | 22        | 31     | 40%     |
| 1.01-2.0   | 8         | 46     | 14.55%  |
| 4.01-10.0  | 1         | 2      | 1.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 17        | 24.29%  |
| 101-250        | 14        | 20%     |
| 501-1000       | 11        | 15.71%  |
| 1-20           | 7         | 10%     |
| Unknown        | 7         | 10%     |
| 51-100         | 5         | 7.14%   |
| 1001-2000      | 4         | 5.71%   |
| 2001-3000      | 3         | 4.29%   |
| More than 3000 | 1         | 1.43%   |
| 21-50          | 1         | 1.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 24        | 33.33%  |
| 21-50          | 16        | 22.22%  |
| 51-100         | 9         | 12.5%   |
| 101-250        | 8         | 11.11%  |
| Unknown        | 7         | 9.72%   |
| 251-500        | 4         | 5.56%   |
| 501-1000       | 2         | 2.78%   |
| More than 3000 | 1         | 1.39%   |
| 1001-2000      | 1         | 1.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST9750420AS 752GB          | 1         | 1      | 25%     |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 25%     |
| Samsung Electronics HD753LJ 752GB  | 1         | 1      | 25%     |
| Hewlett-Packard SSD S700 120GB     | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 50%     |
| Samsung Electronics | 1         | 1      | 25%     |
| Hewlett-Packard     | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 66.67%  |
| Samsung Electronics | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 75%     |
| SSD  | 1         | 1      | 25%     |

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
| Detected | 35        | 67     | 47.3%   |
| Works    | 35        | 83     | 47.3%   |
| Malfunc  | 4         | 4      | 5.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 46        | 56.1%   |
| Samsung Electronics          | 9         | 10.98%  |
| AMD                          | 5         | 6.1%    |
| Phison Electronics           | 3         | 3.66%   |
| Broadcom / LSI               | 3         | 3.66%   |
| SK hynix                     | 2         | 2.44%   |
| SanDisk                      | 2         | 2.44%   |
| Micron Technology            | 2         | 2.44%   |
| VIA Technologies             | 1         | 1.22%   |
| Union Memory (Shenzhen)      | 1         | 1.22%   |
| Transcend                    | 1         | 1.22%   |
| Toshiba America Info Systems | 1         | 1.22%   |
| Micron/Crucial Technology    | 1         | 1.22%   |
| Lite-On Technology           | 1         | 1.22%   |
| Lenovo                       | 1         | 1.22%   |
| KIOXIA                       | 1         | 1.22%   |
| Kingston Technology Company  | 1         | 1.22%   |
| Adaptec                      | 1         | 1.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6         | 6.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 5.38%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 5         | 5.38%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 4.3%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 3.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 3.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 2.15%   |
| Phison E12 NVMe Controller                                                              | 2         | 2.15%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 2.15%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2         | 2.15%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2         | 2.15%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2         | 2.15%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2         | 2.15%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2         | 2.15%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 2.15%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 2.15%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 2.15%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2         | 2.15%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1         | 1.08%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 1         | 1.08%   |
| Transcend Non-Volatile memory controller                                                | 1         | 1.08%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 1         | 1.08%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                      | 1         | 1.08%   |
| SK hynix Non-Volatile memory controller                                                 | 1         | 1.08%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1         | 1.08%   |
| Sandisk PC SN740 NVMe SSD                                                               | 1         | 1.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 1.08%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 1.08%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1         | 1.08%   |
| Micron NVMe Storage Controller                                                          | 1         | 1.08%   |
| Micron 2200S NVMe SSD                                                                   | 1         | 1.08%   |
| Lite-On Non-Volatile memory controller                                                  | 1         | 1.08%   |
| Lenovo Non-Volatile memory controller                                                   | 1         | 1.08%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 1         | 1.08%   |
| Kingston Company A2000 NVMe SSD                                                         | 1         | 1.08%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1         | 1.08%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 1         | 1.08%   |
| Intel SSD 660P Series                                                                   | 1         | 1.08%   |
| Intel SATA Controller [RAID mode]                                                       | 1         | 1.08%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1         | 1.08%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 40        | 47.06%  |
| NVMe | 28        | 32.94%  |
| RAID | 8         | 9.41%   |
| IDE  | 5         | 5.88%   |
| SAS  | 3         | 3.53%   |
| SCSI | 1         | 1.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 64        | 92.75%  |
| AMD    | 5         | 7.25%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8665U CPU @ 1.90GHz       | 3         | 4.35%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 2         | 2.9%    |
| Intel Core i7-6500U CPU @ 2.50GHz       | 2         | 2.9%    |
| Intel Core i7-10610U CPU @ 1.80GHz      | 2         | 2.9%    |
| Intel Core i5-8350U CPU @ 1.70GHz       | 2         | 2.9%    |
| Intel Core i5-7300U CPU @ 2.60GHz       | 2         | 2.9%    |
| Intel Core i5-5300U CPU @ 2.30GHz       | 2         | 2.9%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 2.9%    |
| Intel Xeon Silver 4114 CPU @ 2.20GHz    | 1         | 1.45%   |
| Intel Xeon CPU X3450 @ 2.67GHz          | 1         | 1.45%   |
| Intel Xeon CPU X3430 @ 2.40GHz          | 1         | 1.45%   |
| Intel Xeon CPU E5649 @ 2.53GHz          | 1         | 1.45%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz     | 1         | 1.45%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz     | 1         | 1.45%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz     | 1         | 1.45%   |
| Intel Processor 5Y10 CPU @ 0.80GHz      | 1         | 1.45%   |
| Intel Pentium CPU G3240 @ 3.10GHz       | 1         | 1.45%   |
| Intel Pentium CPU G2020 @ 2.90GHz       | 1         | 1.45%   |
| Intel Core i9-9880H CPU @ 2.30GHz       | 1         | 1.45%   |
| Intel Core i9-10900K CPU @ 3.70GHz      | 1         | 1.45%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 1         | 1.45%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 1         | 1.45%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1.45%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1.45%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 1         | 1.45%   |
| Intel Core i7-6800K CPU @ 3.40GHz       | 1         | 1.45%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 1         | 1.45%   |
| Intel Core i7-4940MX CPU @ 3.10GHz      | 1         | 1.45%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz      | 1         | 1.45%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz      | 1         | 1.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 1         | 1.45%   |
| Intel Core i7-2860QM CPU @ 2.50GHz      | 1         | 1.45%   |
| Intel Core i7-2760QM CPU @ 2.40GHz      | 1         | 1.45%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 1         | 1.45%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.45%   |
| Intel Core i7-10700K CPU @ 3.80GHz      | 1         | 1.45%   |
| Intel Core i5-8365U CPU @ 1.60GHz       | 1         | 1.45%   |
| Intel Core i5-4460 CPU @ 3.20GHz        | 1         | 1.45%   |
| Intel Core i5-4278U CPU @ 2.60GHz       | 1         | 1.45%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 1         | 1.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i7     | 25        | 36.23%  |
| Intel Core i5     | 14        | 20.29%  |
| Other             | 9         | 13.04%  |
| Intel Xeon        | 6         | 8.7%    |
| Intel Celeron     | 3         | 4.35%   |
| Intel Pentium     | 2         | 2.9%    |
| Intel Core i9     | 2         | 2.9%    |
| Intel Core i3     | 2         | 2.9%    |
| AMD Ryzen 7       | 2         | 2.9%    |
| Intel Xeon Silver | 1         | 1.45%   |
| Intel Core 2 Duo  | 1         | 1.45%   |
| AMD Ryzen 7 PRO   | 1         | 1.45%   |
| AMD A8            | 1         | 1.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 28        | 40.58%  |
| 2      | 22        | 31.88%  |
| 12     | 5         | 7.25%   |
| 8      | 4         | 5.8%    |
| 6      | 4         | 5.8%    |
| 16     | 2         | 2.9%    |
| 10     | 2         | 2.9%    |
| 20     | 1         | 1.45%   |
| 1      | 1         | 1.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 65        | 94.2%   |
| 2      | 4         | 5.8%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 57        | 82.61%  |
| 1      | 12        | 17.39%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 68        | 97.14%  |
| Unknown        | 2         | 2.86%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ec    | 7         | 10.14%  |
| 0x306c3    | 6         | 8.7%    |
| 0x206a7    | 5         | 7.25%   |
| 0x806ea    | 4         | 5.8%    |
| Unknown    | 4         | 5.8%    |
| 0x906a3    | 3         | 4.35%   |
| 0x806c1    | 3         | 4.35%   |
| 0x306d4    | 3         | 4.35%   |
| 0x306a9    | 3         | 4.35%   |
| 0xa0655    | 2         | 2.9%    |
| 0x806e9    | 2         | 2.9%    |
| 0x506e3    | 2         | 2.9%    |
| 0x406e3    | 2         | 2.9%    |
| 0x40651    | 2         | 2.9%    |
| 0x306e4    | 2         | 2.9%    |
| 0x106e5    | 2         | 2.9%    |
| 0xa0653    | 1         | 1.45%   |
| 0xa0652    | 1         | 1.45%   |
| 0x906ed    | 1         | 1.45%   |
| 0x906ea    | 1         | 1.45%   |
| 0x706a8    | 1         | 1.45%   |
| 0x506c9    | 1         | 1.45%   |
| 0x50654    | 1         | 1.45%   |
| 0x406f1    | 1         | 1.45%   |
| 0x406c4    | 1         | 1.45%   |
| 0x206c2    | 1         | 1.45%   |
| 0x20655    | 1         | 1.45%   |
| 0x10676    | 1         | 1.45%   |
| 0x08608103 | 1         | 1.45%   |
| 0x0810100b | 1         | 1.45%   |
| 0x0800820d | 1         | 1.45%   |
| 0x07030105 | 1         | 1.45%   |
| 0x06006705 | 1         | 1.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 17        | 24.64%  |
| Haswell          | 8         | 11.59%  |
| Skylake          | 5         | 7.25%   |
| SandyBridge      | 5         | 7.25%   |
| IvyBridge        | 5         | 7.25%   |
| Broadwell        | 5         | 7.25%   |
| CometLake        | 4         | 5.8%    |
| TigerLake        | 3         | 4.35%   |
| Alderlake Hybrid | 3         | 4.35%   |
| Westmere         | 2         | 2.9%    |
| Nehalem          | 2         | 2.9%    |
| Unknown          | 2         | 2.9%    |
| Zen+             | 1         | 1.45%   |
| Zen              | 1         | 1.45%   |
| Silvermont       | 1         | 1.45%   |
| Puma             | 1         | 1.45%   |
| Penryn           | 1         | 1.45%   |
| Goldmont plus    | 1         | 1.45%   |
| Goldmont         | 1         | 1.45%   |
| Excavator        | 1         | 1.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 49        | 58.33%  |
| Nvidia                     | 21        | 25%     |
| AMD                        | 10        | 11.9%   |
| Matrox Electronics Systems | 4         | 4.76%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 5         | 5.95%   |
| Intel UHD Graphics 620                                                      | 4         | 4.76%   |
| Intel HD Graphics 620                                                       | 4         | 4.76%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 4         | 4.76%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 3         | 3.57%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3         | 3.57%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 3         | 3.57%   |
| Nvidia GM108M [GeForce 930MX]                                               | 2         | 2.38%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 2         | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 2.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 2.38%   |
| Intel HD Graphics 5500                                                      | 2         | 2.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 2.38%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 2         | 2.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2         | 2.38%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 1.19%   |
| Nvidia TU117M                                                               | 1         | 1.19%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1         | 1.19%   |
| Nvidia GP107M [GeForce MX350]                                               | 1         | 1.19%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1         | 1.19%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 1.19%   |
| Nvidia GM204GLM [Quadro M4000M]                                             | 1         | 1.19%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 1         | 1.19%   |
| Nvidia GM108GLM [Quadro K620M / Quadro M500M]                               | 1         | 1.19%   |
| Nvidia GK208GLM [Quadro K610M]                                              | 1         | 1.19%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1         | 1.19%   |
| Nvidia GK110GL [Quadro K6000]                                               | 1         | 1.19%   |
| Nvidia GK107GLM [Quadro K1100M]                                             | 1         | 1.19%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1         | 1.19%   |
| Nvidia GF119M [NVS 4200M]                                                   | 1         | 1.19%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 1         | 1.19%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1         | 1.19%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 1         | 1.19%   |
| Matrox Electronics Systems MGA G200eH3                                      | 1         | 1.19%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)           | 1         | 1.19%   |
| Matrox Electronics Systems G200eR2                                          | 1         | 1.19%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1         | 1.19%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1         | 1.19%   |
| Intel HD Graphics 5300                                                      | 1         | 1.19%   |
| Intel HD Graphics 500                                                       | 1         | 1.19%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 33        | 47.14%  |
| 1 x Nvidia     | 11        | 15.71%  |
| Intel + Nvidia | 10        | 14.29%  |
| 1 x AMD        | 6         | 8.57%   |
| 1 x Matrox     | 4         | 5.71%   |
| Intel + AMD    | 3         | 4.29%   |
| Other          | 2         | 2.86%   |
| AMD + Nvidia   | 1         | 1.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 59        | 83.1%   |
| Unknown     | 7         | 9.86%   |
| Proprietary | 5         | 7.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 58.57%  |
| 1.01-2.0   | 12        | 17.14%  |
| 3.01-4.0   | 9         | 12.86%  |
| 0.51-1.0   | 3         | 4.29%   |
| 0.01-0.5   | 3         | 4.29%   |
| 5.01-6.0   | 1         | 1.43%   |
| 8.01-16.0  | 1         | 1.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 12        | 14.12%  |
| Samsung Electronics  | 10        | 11.76%  |
| LG Display           | 9         | 10.59%  |
| Chimei Innolux       | 9         | 10.59%  |
| Dell                 | 8         | 9.41%   |
| BOE                  | 5         | 5.88%   |
| Lenovo               | 4         | 4.71%   |
| ViewSonic            | 3         | 3.53%   |
| InfoVision           | 3         | 3.53%   |
| Hewlett-Packard      | 3         | 3.53%   |
| BenQ                 | 3         | 3.53%   |
| Acer                 | 3         | 3.53%   |
| ASUSTek Computer     | 2         | 2.35%   |
| Vizio                | 1         | 1.18%   |
| Viotek               | 1         | 1.18%   |
| Sony                 | 1         | 1.18%   |
| SAC                  | 1         | 1.18%   |
| Panasonic            | 1         | 1.18%   |
| Goldstar             | 1         | 1.18%   |
| GameMax              | 1         | 1.18%   |
| Element              | 1         | 1.18%   |
| Eizo                 | 1         | 1.18%   |
| BOE Technology Group | 1         | 1.18%   |
| Ancor Communications | 1         | 1.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 3.33%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 2         | 2.22%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 2         | 2.22%   |
| Dell U2718Q DELA0E9 3840x2160 609x349mm 27.6-inch                     | 2         | 2.22%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 2         | 2.22%   |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                     | 2         | 2.22%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch         | 2         | 2.22%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 2         | 2.22%   |
| Acer SA230 ACR057E 1920x1080 509x286mm 23.0-inch                      | 2         | 2.22%   |
| Vizio M50Q7-H1 VIZ1039 3840x2160 941x529mm 42.5-inch                  | 1         | 1.11%   |
| Viotek SUW49C VTK4900 3840x1080 1196x336mm 48.9-inch                  | 1         | 1.11%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch         | 1         | 1.11%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch              | 1         | 1.11%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 521x293mm 23.5-inch         | 1         | 1.11%   |
| Sony TV SNY4502 1920x1080                                             | 1         | 1.11%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch   | 1         | 1.11%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch  | 1         | 1.11%   |
| Samsung Electronics SAMTRON STN0022 1280x1024 376x301mm 19.0-inch     | 1         | 1.11%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch     | 1         | 1.11%   |
| Samsung Electronics S27D391 SAM0B89 1920x1080 598x336mm 27.0-inch     | 1         | 1.11%   |
| Samsung Electronics S27D391 SAM0B88 1920x1080 598x336mm 27.0-inch     | 1         | 1.11%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 1.11%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch     | 1         | 1.11%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SDC3256 1920x1080 382x215mm 17.3-inch | 1         | 1.11%   |
| Samsung Electronics LCD Monitor S24C650                               | 1         | 1.11%   |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 697x392mm 31.5-inch     | 1         | 1.11%   |
| SAC LED MONITOR SAC952D 1920x1080 480x270mm 21.7-inch                 | 1         | 1.11%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                    | 1         | 1.11%   |
| LG Display LCD Monitor LGD0628 1920x1080 309x174mm 14.0-inch          | 1         | 1.11%   |
| LG Display LCD Monitor LGD0609 1920x1080 309x174mm 14.0-inch          | 1         | 1.11%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch           | 1         | 1.11%   |
| LG Display LCD Monitor LGD047C 1366x768 310x174mm 14.0-inch           | 1         | 1.11%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 1.11%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 1         | 1.11%   |
| LG Display LCD Monitor LGD02D9 1920x1080 345x194mm 15.6-inch          | 1         | 1.11%   |
| Lenovo T24i-10 LEN61A6 1920x1080 527x296mm 23.8-inch                  | 1         | 1.11%   |
| Lenovo LEN T2424pA LEN60C8 1920x1080 527x296mm 23.8-inch              | 1         | 1.11%   |
| Lenovo LEN T2254pC LEN60CC 1680x1050 474x296mm 22.0-inch              | 1         | 1.11%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 41        | 57.75%  |
| 3840x2160 (4K)     | 6         | 8.45%   |
| 1366x768 (WXGA)    | 5         | 7.04%   |
| 1600x900 (HD+)     | 4         | 5.63%   |
| 1280x1024 (SXGA)   | 3         | 4.23%   |
| 2560x1440 (QHD)    | 2         | 2.82%   |
| 1920x1200 (WUXGA)  | 2         | 2.82%   |
| 1680x1050 (WSXGA+) | 2         | 2.82%   |
| 3840x1200          | 1         | 1.41%   |
| 3840x1080          | 1         | 1.41%   |
| 1920x540           | 1         | 1.41%   |
| 1360x768           | 1         | 1.41%   |
| 1280x800 (WXGA)    | 1         | 1.41%   |
| Unknown            | 1         | 1.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 15        | 17.44%  |
| 14      | 12        | 13.95%  |
| 27      | 10        | 11.63%  |
| 24      | 9         | 10.47%  |
| 13      | 9         | 10.47%  |
| 23      | 5         | 5.81%   |
| Unknown | 4         | 4.65%   |
| 21      | 3         | 3.49%   |
| 38      | 2         | 2.33%   |
| 31      | 2         | 2.33%   |
| 19      | 2         | 2.33%   |
| 17      | 2         | 2.33%   |
| 84      | 1         | 1.16%   |
| 72      | 1         | 1.16%   |
| 69      | 1         | 1.16%   |
| 48      | 1         | 1.16%   |
| 32      | 1         | 1.16%   |
| 25      | 1         | 1.16%   |
| 22      | 1         | 1.16%   |
| 20      | 1         | 1.16%   |
| 18      | 1         | 1.16%   |
| 12      | 1         | 1.16%   |
| 11      | 1         | 1.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 34        | 40.96%  |
| 501-600     | 23        | 27.71%  |
| 401-500     | 6         | 7.23%   |
| 201-300     | 4         | 4.82%   |
| Unknown     | 4         | 4.82%   |
| 351-400     | 3         | 3.61%   |
| 1501-2000   | 3         | 3.61%   |
| 801-900     | 2         | 2.41%   |
| 601-700     | 2         | 2.41%   |
| 701-800     | 1         | 1.2%    |
| 1001-1500   | 1         | 1.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 54        | 81.82%  |
| 16/10   | 5         | 7.58%   |
| 5/4     | 3         | 4.55%   |
| 32/9    | 2         | 3.03%   |
| Unknown | 2         | 3.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 19        | 22.89%  |
| 101-110        | 15        | 18.07%  |
| 201-250        | 14        | 16.87%  |
| 301-350        | 10        | 12.05%  |
| Unknown        | 4         | 4.82%   |
| More than 1000 | 3         | 3.61%   |
| 351-500        | 3         | 3.61%   |
| 151-200        | 3         | 3.61%   |
| 501-1000       | 3         | 3.61%   |
| 71-80          | 2         | 2.41%   |
| 251-300        | 2         | 2.41%   |
| 121-130        | 2         | 2.41%   |
| 61-70          | 1         | 1.2%    |
| 51-60          | 1         | 1.2%    |
| 141-150        | 1         | 1.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 33        | 41.77%  |
| 51-100  | 27        | 34.18%  |
| 101-120 | 10        | 12.66%  |
| 161-240 | 4         | 5.06%   |
| Unknown | 4         | 5.06%   |
| 1-50    | 1         | 1.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 40        | 57.14%  |
| 2     | 14        | 20%     |
| 0     | 9         | 12.86%  |
| 3     | 6         | 8.57%   |
| 4     | 1         | 1.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 53        | 55.79%  |
| Realtek Semiconductor | 22        | 23.16%  |
| Broadcom              | 5         | 5.26%   |
| Qualcomm Atheros      | 4         | 4.21%   |
| Lenovo                | 3         | 3.16%   |
| Broadcom Limited      | 2         | 2.11%   |
| Ralink Technology     | 1         | 1.05%   |
| QLogic                | 1         | 1.05%   |
| NetGear               | 1         | 1.05%   |
| Mellanox Technologies | 1         | 1.05%   |
| Fibocom               | 1         | 1.05%   |
| ASIX Electronics      | 1         | 1.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 8.66%   |
| Intel Wireless 8265 / 8275                                        | 8         | 6.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 4.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 3.94%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 3.94%   |
| Intel Wireless 8260                                               | 4         | 3.15%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 3.15%   |
| Intel Wireless 7265                                               | 3         | 2.36%   |
| Intel Wireless 7260                                               | 3         | 2.36%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 2.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 2.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 2.36%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 2.36%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 2.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.57%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 1.57%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.57%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.57%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.57%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.57%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.57%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.57%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.79%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.79%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.79%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.79%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.79%   |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller          | 1         | 0.79%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                   | 1         | 0.79%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 1         | 0.79%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 0.79%   |
| Intel Wireless-AC 9260                                            | 1         | 0.79%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 0.79%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 0.79%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 42        | 75%     |
| Realtek Semiconductor | 5         | 8.93%   |
| Qualcomm Atheros      | 4         | 7.14%   |
| Ralink Technology     | 1         | 1.79%   |
| NetGear               | 1         | 1.79%   |
| Fibocom               | 1         | 1.79%   |
| Broadcom Limited      | 1         | 1.79%   |
| Broadcom              | 1         | 1.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 8         | 14.29%  |
| Intel Wireless 8260                                            | 4         | 7.14%   |
| Intel Wireless 7265                                            | 3         | 5.36%   |
| Intel Wireless 7260                                            | 3         | 5.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 5.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 5.36%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 5.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 3.57%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 3.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 3.57%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 3.57%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 1.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.79%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.79%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 1.79%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.79%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                | 1         | 1.79%   |
| Intel Wireless-AC 9260                                         | 1         | 1.79%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 1.79%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 1.79%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.79%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.79%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 1.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.79%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.79%   |
| Fibocom L830-EB-00 LTE WWAN Modem                              | 1         | 1.79%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 1         | 1.79%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 1.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 38        | 55.88%  |
| Realtek Semiconductor | 19        | 27.94%  |
| Broadcom              | 4         | 5.88%   |
| Lenovo                | 3         | 4.41%   |
| QLogic                | 1         | 1.47%   |
| Mellanox Technologies | 1         | 1.47%   |
| Broadcom Limited      | 1         | 1.47%   |
| ASIX Electronics      | 1         | 1.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 15.49%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 8.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 7.04%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 7.04%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 5.63%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 4.23%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 4.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.82%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 2.82%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.82%   |
| Intel Ethernet Controller I225-V                                  | 2         | 2.82%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 2.82%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 2.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.41%   |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller          | 1         | 1.41%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 1         | 1.41%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 1.41%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.41%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.41%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.41%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.41%   |
| Intel Ethernet Connection (17) I219-LM                            | 1         | 1.41%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.41%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.41%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection             | 1         | 1.41%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 1.41%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 1.41%   |
| Intel 82571EB Gigabit Ethernet Controller                         | 1         | 1.41%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1         | 1.41%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.41%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 1.41%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 1.41%   |
| Broadcom BCM57840 NetXtreme II 10/20-Gigabit Ethernet             | 1         | 1.41%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 59        | 53.15%  |
| WiFi     | 52        | 46.85%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 40        | 55.56%  |
| WiFi     | 32        | 44.44%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 42        | 60.87%  |
| 1     | 23        | 33.33%  |
| 4     | 2         | 2.9%    |
| 6     | 1         | 1.45%   |
| 3     | 1         | 1.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 57        | 78.08%  |
| Yes  | 16        | 21.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 28        | 70%     |
| Qualcomm Atheros Communications | 3         | 7.5%    |
| Broadcom                        | 3         | 7.5%    |
| Realtek Semiconductor           | 2         | 5%      |
| IMC Networks                    | 1         | 2.5%    |
| ASUSTek Computer                | 1         | 2.5%    |
| Apple                           | 1         | 2.5%    |
| Alps Electric                   | 1         | 2.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 13        | 32.5%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 5         | 12.5%   |
| Intel AX201 Bluetooth                          | 4         | 10%     |
| Intel Bluetooth Device                         | 3         | 7.5%    |
| Qualcomm Atheros  Bluetooth Device             | 2         | 5%      |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 2.5%    |
| Realtek Bluetooth Radio                        | 1         | 2.5%    |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 2.5%    |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1         | 2.5%    |
| Intel Wireless-AC 3168 Bluetooth               | 1         | 2.5%    |
| Intel AX210 Bluetooth                          | 1         | 2.5%    |
| IMC Networks Bluetooth Radio                   | 1         | 2.5%    |
| Broadcom BCM43142A0 Bluetooth 4.0              | 1         | 2.5%    |
| Broadcom BCM20702A0 Bluetooth 4.0              | 1         | 2.5%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 2.5%    |
| ASUS Broadcom BCM20702A0 Bluetooth             | 1         | 2.5%    |
| Apple Bluetooth Host Controller                | 1         | 2.5%    |
| Alps Electric UGTZ4 Bluetooth                  | 1         | 2.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 58        | 61.7%   |
| Nvidia              | 14        | 14.89%  |
| AMD                 | 9         | 9.57%   |
| Lenovo              | 5         | 5.32%   |
| GN Netcom           | 5         | 5.32%   |
| Unknown             | 1         | 1.06%   |
| TEAC                | 1         | 1.06%   |
| C-Media Electronics | 1         | 1.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 9.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 5.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 4.63%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 4.63%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 2.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.78%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 2.78%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 2.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.85%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 1.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 1.85%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 1.85%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 2         | 1.85%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 2         | 1.85%   |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 2         | 1.85%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.85%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.85%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.85%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.85%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 2         | 1.85%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 1.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.85%   |
| GN Netcom Jabra EVOLVE LINK                                                                       | 2         | 1.85%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.85%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 1.85%   |
| Unknown Definitive Sym1                                                                           | 1         | 0.93%   |
| TEAC US-2x2                                                                                       | 1         | 0.93%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.93%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.93%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.93%   |
| Nvidia GK110 High Definition Audio Controller                                                     | 1         | 0.93%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.93%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.93%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                                          | 1         | 0.93%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.93%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 1         | 0.93%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 10        | 23.26%  |
| Micron Technology                       | 10        | 23.26%  |
| SK hynix                                | 6         | 13.95%  |
| Kingston                                | 4         | 9.3%    |
| Unknown                                 | 3         | 6.98%   |
| Crucial                                 | 2         | 4.65%   |
| Unigen                                  | 1         | 2.33%   |
| Smart                                   | 1         | 2.33%   |
| Silicon Power Computer & Communications | 1         | 2.33%   |
| HPE                                     | 1         | 2.33%   |
| Corsair                                 | 1         | 2.33%   |
| Avant                                   | 1         | 2.33%   |
| 4ea5                                    | 1         | 2.33%   |
| Unknown                                 | 1         | 2.33%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 3         | 6.38%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s         | 2         | 4.26%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                  | 1         | 2.13%   |
| Unknown RAM Module 4GB DIMM DDR3 800MT/s                     | 1         | 2.13%   |
| Unknown RAM Module 32GB SODIMM DDR4 2667MT/s                 | 1         | 2.13%   |
| Unigen RAM Module 4GB DIMM DDR3 1333MT/s                     | 1         | 2.13%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s        | 1         | 2.13%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 2.13%   |
| SK hynix RAM HMT31GR7BFR4A-H9 8192MB DIMM 1333MT/s           | 1         | 2.13%   |
| SK hynix RAM HMAA1GS6CMR8N-VK 8GB Row Of Chips DDR4 2667MT/s | 1         | 2.13%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s | 1         | 2.13%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s    | 1         | 2.13%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 1         | 2.13%   |
| SK hynix RAM H9HCNNNBKUMLXR-NEE 2GB LPDDR4 2400MT/s          | 1         | 2.13%   |
| Silicon Power & RAM Module 16GB SODIMM DDR4 2667MT/s         | 1         | 2.13%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 2.13%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s       | 1         | 2.13%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 2.13%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 1         | 2.13%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 2.13%   |
| Samsung RAM M393B2G70BH0-YH9 16GB DIMM DDR3 1333MT/s         | 1         | 2.13%   |
| Samsung RAM M393B2G70BH0-CK0 16GB DIMM 1600MT/s              | 1         | 2.13%   |
| Micron RAM Module 16384MB SODIMM DDR4 2400MT/s               | 1         | 2.13%   |
| Micron RAM 8ATF1G64AZ-2G3H1 8GB DIMM DDR4 2448MT/s           | 1         | 2.13%   |
| Micron RAM 8ATF1G64AZ-2G3E1 8GB DIMM DDR4 2400MT/s           | 1         | 2.13%   |
| Micron RAM 8ATF1G64AZ-2G3B1 8GB DIMM DDR4 2448MT/s           | 1         | 2.13%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s  | 1         | 2.13%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s        | 1         | 2.13%   |
| Micron RAM 4ATF1G64AZ-3G2F1 8GB DIMM DDR4 3200MT/s           | 1         | 2.13%   |
| Micron RAM 18ASF2G72PDZ-2G3B1 16GB DIMM DDR4 2400MT/s        | 1         | 2.13%   |
| Micron RAM 16JTF1G64HZ-1G4D1 8GB SODIMM DDR3 1333MT/s        | 1         | 2.13%   |
| Micron RAM 16ATF2G64HZ-2G1A1 16GB SODIMM DDR4 2133MT/s       | 1         | 2.13%   |
| Kingston RAM KX830D-ELC 4GB SODIMM DDR3 1333MT/s             | 1         | 2.13%   |
| Kingston RAM KTW149-ELF 1GB DIMM DDR3 1333MT/s               | 1         | 2.13%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s             | 1         | 2.13%   |
| Kingston RAM 9905471-006.A00LF 4GB DIMM DDR3 1333MT/s        | 1         | 2.13%   |
| Kingston RAM 9905403-892.A00LF 8GB DIMM DDR3 1333MT/s        | 1         | 2.13%   |
| HPE RAM 840756-091 16GB DIMM DDR4 2666MT/s                   | 1         | 2.13%   |
| Crucial RAM CT16G4SFRA32A.M16FR 16GB SODIMM DDR4 3200MT/s    | 1         | 2.13%   |
| Crucial RAM BLE8G4D34AEEAK.K8FB 8192MB DIMM DDR4 3466MT/s    | 1         | 2.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 21        | 53.85%  |
| DDR3   | 15        | 38.46%  |
| LPDDR4 | 2         | 5.13%   |
| LPDDR5 | 1         | 2.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 23        | 58.97%  |
| DIMM         | 11        | 28.21%  |
| Row Of Chips | 4         | 10.26%  |
| Unknown      | 1         | 2.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 16        | 39.02%  |
| 16384 | 11        | 26.83%  |
| 4096  | 10        | 24.39%  |
| 32768 | 2         | 4.88%   |
| 2048  | 1         | 2.44%   |
| 1024  | 1         | 2.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 10        | 24.39%  |
| 1600  | 8         | 19.51%  |
| 1333  | 7         | 17.07%  |
| 2400  | 5         | 12.2%   |
| 3200  | 3         | 7.32%   |
| 6400  | 1         | 2.44%   |
| 4267  | 1         | 2.44%   |
| 3466  | 1         | 2.44%   |
| 2666  | 1         | 2.44%   |
| 2448  | 1         | 2.44%   |
| 2133  | 1         | 2.44%   |
| 1866  | 1         | 2.44%   |
| 800   | 1         | 2.44%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Samsung ML-1660 Series | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 120 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 10        | 27.03%  |
| IMC Networks                           | 6         | 16.22%  |
| Logitech                               | 5         | 13.51%  |
| Realtek Semiconductor                  | 4         | 10.81%  |
| Suyin                                  | 3         | 8.11%   |
| Lite-On Technology                     | 3         | 8.11%   |
| Microdia                               | 2         | 5.41%   |
| Bison Electronics                      | 2         | 5.41%   |
| Luxvisions Innotech Limited            | 1         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.7%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 6         | 15.79%  |
| IMC Networks Integrated Camera                                  | 3         | 7.89%   |
| Realtek Integrated_Webcam_HD                                    | 2         | 5.26%   |
| Microdia Webcam Vitade AF                                       | 2         | 5.26%   |
| Lite-On Integrated Camera                                       | 2         | 5.26%   |
| IMC Networks VGA UVC WebCam                                     | 2         | 5.26%   |
| Chicony Integrated Camera (1280x720@30)                         | 2         | 5.26%   |
| Bison SunplusIT Integrated Camera                               | 2         | 5.26%   |
| Suyin Integrated_Webcam_HD                                      | 1         | 2.63%   |
| Suyin HP Truevision HD                                          | 1         | 2.63%   |
| Suyin Asus Integrated Webcam                                    | 1         | 2.63%   |
| Realtek Integrated_Webcam_FHD                                   | 1         | 2.63%   |
| Realtek EasyCamera                                              | 1         | 2.63%   |
| Luxvisions Innotech Limited EasyCamera 1M                       | 1         | 2.63%   |
| Logitech Webcam C925e                                           | 1         | 2.63%   |
| Logitech Webcam C920-C                                          | 1         | 2.63%   |
| Logitech Webcam C270                                            | 1         | 2.63%   |
| Logitech HD Webcam C615                                         | 1         | 2.63%   |
| Logitech BRIO Ultra HD Webcam                                   | 1         | 2.63%   |
| Lite-On HP HD Camera                                            | 1         | 2.63%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 1         | 2.63%   |
| Chicony TOSHIBA Web Camera - HD                                 | 1         | 2.63%   |
| Chicony ThinkPad T490 Webcam                                    | 1         | 2.63%   |
| Chicony Integrated IR Camera                                    | 1         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera | 1         | 2.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 47.06%  |
| Synaptics                  | 7         | 41.18%  |
| Upek                       | 1         | 5.88%   |
| Shenzhen Goodix Technology | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 17.65%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 17.65%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 17.65%  |
| Validity Sensors Synaptics WBDI                                            | 2         | 11.76%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 11.76%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 5.88%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 5.88%   |
| Synaptics WBDI                                                             | 1         | 5.88%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 5.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 75%     |
| Alcor Micro | 2         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 3         | 37.5%   |
| Broadcom 58200                                 | 3         | 37.5%   |
| Alcor Micro AU9540 Smartcard Reader            | 2         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 33        | 46.48%  |
| 1     | 28        | 39.44%  |
| 2     | 8         | 11.27%  |
| 3     | 2         | 2.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 17        | 36.96%  |
| Graphics card            | 8         | 17.39%  |
| Chipcard                 | 6         | 13.04%  |
| Unassigned class         | 3         | 6.52%   |
| Net/wireless             | 3         | 6.52%   |
| Bluetooth                | 3         | 6.52%   |
| Storage                  | 2         | 4.35%   |
| Communication controller | 2         | 4.35%   |
| Card reader              | 2         | 4.35%   |

