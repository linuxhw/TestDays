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

Total: 87

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Intel     | NUC6CAYB J23203-406         | Mini pc     | [65bb9a17dd](https://linux-hardware.org/?probe=65bb9a17dd) | Feb 04, 2023 |
| HP        | Laptop 17-cp0xxx            | Notebook    | [e87b8175b1](https://linux-hardware.org/?probe=e87b8175b1) | Jan 27, 2023 |
| HP        | Laptop 17-cp0xxx            | Notebook    | [70019cbdbf](https://linux-hardware.org/?probe=70019cbdbf) | Jan 25, 2023 |
| Google    | Lick                        | Notebook    | [d792b79719](https://linux-hardware.org/?probe=d792b79719) | Jan 12, 2023 |
| Intel     | NUC12WSBi7 M46422-303       | Mini pc     | [3ddd96770b](https://linux-hardware.org/?probe=3ddd96770b) | Dec 24, 2022 |
| Intel     | NUC12WSBi7 M46422-303       | Mini pc     | [8f10e15f9a](https://linux-hardware.org/?probe=8f10e15f9a) | Dec 24, 2022 |
| Panasonic | CF-53AAG54FM                | Notebook    | [cf7f652846](https://linux-hardware.org/?probe=cf7f652846) | Dec 21, 2022 |
| Lenovo    | ThinkPad T470 20HES0E71M    | Notebook    | [85fc801717](https://linux-hardware.org/?probe=85fc801717) | Dec 05, 2022 |
| ASUSTek   | PRIME B560M-A AC            | Desktop     | [d4cc718e46](https://linux-hardware.org/?probe=d4cc718e46) | Nov 29, 2022 |
| Lenovo    | ThinkPad P70 20ESS04S00     | Notebook    | [01b85c4c2a](https://linux-hardware.org/?probe=01b85c4c2a) | Nov 10, 2022 |
| Lenovo    | ThinkPad T470 20HES21434    | Notebook    | [39ff1846e3](https://linux-hardware.org/?probe=39ff1846e3) | Oct 23, 2022 |
| Fujitsu   | D2759 S26361-D2759-A13 W... | Server      | [c4c0b53877](https://linux-hardware.org/?probe=c4c0b53877) | Oct 23, 2022 |
| Dynabook  | PORTEGE X40-G               | Notebook    | [fc68a9cdbf](https://linux-hardware.org/?probe=fc68a9cdbf) | Oct 03, 2022 |
| Dell      | 0DC48C A02                  | Desktop     | [9292e820c5](https://linux-hardware.org/?probe=9292e820c5) | Sep 27, 2022 |
| HP        | EliteBook 840 G5            | Notebook    | [2709daf415](https://linux-hardware.org/?probe=2709daf415) | Sep 13, 2022 |
| ASUSTek   | H81M-A                      | Desktop     | [a37e952875](https://linux-hardware.org/?probe=a37e952875) | Sep 04, 2022 |
| Lenovo    | Legion 5 15IMH05 82AU       | Notebook    | [bd4737dfcf](https://linux-hardware.org/?probe=bd4737dfcf) | Aug 18, 2022 |
| Dell      | Inspiron 5502               | Notebook    | [28dcf01e88](https://linux-hardware.org/?probe=28dcf01e88) | Aug 03, 2022 |
| Dell      | 073Y7Y A00                  | Desktop     | [3bed97b23e](https://linux-hardware.org/?probe=3bed97b23e) | Jul 21, 2022 |
| Lenovo    | Legion 5 15IMH05 82AU       | Notebook    | [3dddb3aac3](https://linux-hardware.org/?probe=3dddb3aac3) | Jul 20, 2022 |
| MSI       | Z77A-G43                    | Desktop     | [909e3e3c2e](https://linux-hardware.org/?probe=909e3e3c2e) | Jun 29, 2022 |
| ASUSTek   | P8H67                       | Desktop     | [b194dad4cf](https://linux-hardware.org/?probe=b194dad4cf) | Jun 25, 2022 |
| Lenovo    | ThinkPad P70 20ESS04S00     | Notebook    | [fc29967bed](https://linux-hardware.org/?probe=fc29967bed) | Jun 17, 2022 |
| HP        | Compaq 6730b                | Notebook    | [dd94c9145b](https://linux-hardware.org/?probe=dd94c9145b) | Jun 11, 2022 |
| Lenovo    | ThinkPad T410 2518A37       | Notebook    | [04e81b8b3f](https://linux-hardware.org/?probe=04e81b8b3f) | Jun 04, 2022 |
| Lenovo    | ThinkPad T430s 2355C33      | Notebook    | [33de2bbd12](https://linux-hardware.org/?probe=33de2bbd12) | May 31, 2022 |
| Lenovo    | ThinkPad T430s 2355C33      | Notebook    | [4eab57bebf](https://linux-hardware.org/?probe=4eab57bebf) | May 30, 2022 |
| Dell      | Precision M4600             | Notebook    | [0ac2adfe5a](https://linux-hardware.org/?probe=0ac2adfe5a) | Apr 21, 2022 |
| Dell      | Precision M4800             | Notebook    | [fb13b19803](https://linux-hardware.org/?probe=fb13b19803) | Apr 21, 2022 |
| Lenovo    | ThinkPad P50s 20FL000MUS    | Notebook    | [99fbb4446c](https://linux-hardware.org/?probe=99fbb4446c) | Apr 16, 2022 |
| Dell      | 0C522T A03                  | Desktop     | [3dc84dc8ff](https://linux-hardware.org/?probe=3dc84dc8ff) | Mar 24, 2022 |
| Lenovo    | ThinkPad X1 Extreme 2nd ... | Notebook    | [b708e920f3](https://linux-hardware.org/?probe=b708e920f3) | Mar 21, 2022 |
| Lenovo    | ThinkPad T450 20BUS14900    | Notebook    | [bd60aae97a](https://linux-hardware.org/?probe=bd60aae97a) | Mar 11, 2022 |
| Lenovo    | ThinkPad T480 20L5A07TAU    | Notebook    | [755854f7d4](https://linux-hardware.org/?probe=755854f7d4) | Mar 11, 2022 |
| Lenovo    | ThinkPad X280 20KES4H34G    | Notebook    | [2b8a4f4664](https://linux-hardware.org/?probe=2b8a4f4664) | Mar 10, 2022 |
| Dell      | Latitude 7420               | Notebook    | [af5f1055fe](https://linux-hardware.org/?probe=af5f1055fe) | Mar 10, 2022 |
| HP        | ProBook 445 G6              | Notebook    | [88d8b32328](https://linux-hardware.org/?probe=88d8b32328) | Jan 26, 2022 |
| Lenovo    | ThinkPad X390 Yoga 20NQS... | Convertible | [8219e32fef](https://linux-hardware.org/?probe=8219e32fef) | Dec 22, 2021 |
| Lenovo    | ThinkPad T450 20BUS14900    | Notebook    | [44c8e11f02](https://linux-hardware.org/?probe=44c8e11f02) | Dec 22, 2021 |
| Lenovo    | IdeaPad 300-15ISK 80RS      | Notebook    | [1c9ca21f4e](https://linux-hardware.org/?probe=1c9ca21f4e) | Dec 10, 2021 |
| Dell      | Latitude 7410               | Notebook    | [3efa87284e](https://linux-hardware.org/?probe=3efa87284e) | Nov 18, 2021 |
| Dell      | Latitude E6420              | Notebook    | [b809392380](https://linux-hardware.org/?probe=b809392380) | Oct 08, 2021 |
| Lenovo    | IdeaPad C340-14IWL 81RL     | Convertible | [cf3c570b7a](https://linux-hardware.org/?probe=cf3c570b7a) | Sep 27, 2021 |
| Dell      | Latitude 7410               | Notebook    | [8f1a1a4798](https://linux-hardware.org/?probe=8f1a1a4798) | Sep 06, 2021 |
| Dell      | Latitude 7410               | Notebook    | [b03a0e0152](https://linux-hardware.org/?probe=b03a0e0152) | Sep 06, 2021 |
| Lenovo    | Legion 5 15IMH05 82AU       | Notebook    | [7b393c5790](https://linux-hardware.org/?probe=7b393c5790) | Aug 21, 2021 |
| Lenovo    | Legion 5 15IMH05 82AU       | Notebook    | [394c99adc8](https://linux-hardware.org/?probe=394c99adc8) | Aug 19, 2021 |
| Dell      | Inspiron 3542               | Notebook    | [0909599e9c](https://linux-hardware.org/?probe=0909599e9c) | Aug 11, 2021 |
| Lenovo    | Legion 5 15IMH05 82AU       | Notebook    | [ba7afba1a6](https://linux-hardware.org/?probe=ba7afba1a6) | Jul 08, 2021 |
| Lenovo    | ThinkPad L490 20Q5CTO1WW    | Notebook    | [0225c17d79](https://linux-hardware.org/?probe=0225c17d79) | Jul 02, 2021 |
| Lenovo    | Legion 5 15IMH05 82AU       | Notebook    | [505b82b2de](https://linux-hardware.org/?probe=505b82b2de) | Jun 06, 2021 |
| Lenovo    | Legion 5 15IMH05 82AU       | Notebook    | [75b2ef5126](https://linux-hardware.org/?probe=75b2ef5126) | May 13, 2021 |
| Lenovo    | Legion 5 15IMH05 82AU       | Notebook    | [734a4fbc56](https://linux-hardware.org/?probe=734a4fbc56) | May 09, 2021 |
| Gigabyte  | Z490 AORUS ELITE AC         | Desktop     | [978ae6f2cb](https://linux-hardware.org/?probe=978ae6f2cb) | May 02, 2021 |
| ASUSTek   | UX305FA                     | Notebook    | [0bf50fba2d](https://linux-hardware.org/?probe=0bf50fba2d) | Mar 15, 2021 |
| Lenovo    | IdeaPad Slim 1-14AST-05 ... | Notebook    | [ff355a9bb1](https://linux-hardware.org/?probe=ff355a9bb1) | Mar 11, 2021 |
| Gigabyte  | X99-Designare EX-CF         | Desktop     | [5195396549](https://linux-hardware.org/?probe=5195396549) | Mar 06, 2021 |
| Lenovo    | IdeaPad Slim 1-14AST-05 ... | Notebook    | [9f67379954](https://linux-hardware.org/?probe=9f67379954) | Mar 04, 2021 |
| Lenovo    | ThinkPad L490 20Q5CTO1WW    | Notebook    | [db0f24aee5](https://linux-hardware.org/?probe=db0f24aee5) | Mar 01, 2021 |
| Dell      | Latitude 7410               | Notebook    | [5b725b01aa](https://linux-hardware.org/?probe=5b725b01aa) | Feb 26, 2021 |
| Lenovo    | Legion 5 15IMH05 82AU       | Notebook    | [835e8cad03](https://linux-hardware.org/?probe=835e8cad03) | Feb 25, 2021 |
| Dell      | Latitude 7410               | Notebook    | [430ac9fa0c](https://linux-hardware.org/?probe=430ac9fa0c) | Feb 24, 2021 |
| Lenovo    | ThinkPad T490 20N3S77600    | Notebook    | [26e61c39f2](https://linux-hardware.org/?probe=26e61c39f2) | Feb 24, 2021 |
| Dell      | Latitude 7410               | Notebook    | [7aeb2cc674](https://linux-hardware.org/?probe=7aeb2cc674) | Feb 22, 2021 |
| Lenovo    | IdeaPad Slim 1-14AST-05 ... | Notebook    | [8af2c8d83c](https://linux-hardware.org/?probe=8af2c8d83c) | Feb 05, 2021 |
| ASUSTek   | G11CD                       | Desktop     | [13961e12a8](https://linux-hardware.org/?probe=13961e12a8) | Feb 01, 2021 |
| HP        | 158B                        | Desktop     | [5e6b9531d7](https://linux-hardware.org/?probe=5e6b9531d7) | Feb 01, 2021 |
| Dell      | PowerEdge FC630             | Desktop     | [bcd33a41f0](https://linux-hardware.org/?probe=bcd33a41f0) | Jan 25, 2021 |
| Gigabyte  | X470 AORUS ULTRA GAMING-... | Desktop     | [71628a95b6](https://linux-hardware.org/?probe=71628a95b6) | Jan 13, 2021 |
| Lenovo    | IdeaPad Slim 1-14AST-05 ... | Notebook    | [7ea3c87bfe](https://linux-hardware.org/?probe=7ea3c87bfe) | Jan 06, 2021 |
| Foxconn   | 2ADA                        | Desktop     | [809e03aea5](https://linux-hardware.org/?probe=809e03aea5) | Dec 24, 2020 |
| ASUSTek   | G11CD                       | Desktop     | [d9d0f8fdf2](https://linux-hardware.org/?probe=d9d0f8fdf2) | Dec 20, 2020 |
| Standard  | BW Series                   | Notebook    | [1f6cf82ba8](https://linux-hardware.org/?probe=1f6cf82ba8) | Jun 13, 2020 |
| Apple     | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [109e02e0f2](https://linux-hardware.org/?probe=109e02e0f2) | Jun 07, 2020 |
| Apple     | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [2d385b9cb0](https://linux-hardware.org/?probe=2d385b9cb0) | Jun 07, 2020 |
| HP        | Notebook                    | Notebook    | [e3c242a846](https://linux-hardware.org/?probe=e3c242a846) | May 24, 2020 |
| Lenovo    | ThinkPad L490 20Q5CTO1WW    | Notebook    | [d8b2c132c1](https://linux-hardware.org/?probe=d8b2c132c1) | Apr 09, 2020 |
| HP        | ZBook 15                    | Notebook    | [4723616d8c](https://linux-hardware.org/?probe=4723616d8c) | Apr 09, 2020 |
| Lenovo    | ThinkPad L490 20Q5CTO1WW    | Notebook    | [1acbabb197](https://linux-hardware.org/?probe=1acbabb197) | Apr 06, 2020 |
| Lenovo    | ThinkPad T480 20L6S56Y2X    | Notebook    | [5343997520](https://linux-hardware.org/?probe=5343997520) | Feb 23, 2020 |
| Dell      | 0C96W1 A01                  | Desktop     | [b5c14107bb](https://linux-hardware.org/?probe=b5c14107bb) | Feb 12, 2020 |
| ASUSTek   | X510UR                      | Notebook    | [914b9fbe64](https://linux-hardware.org/?probe=914b9fbe64) | Feb 04, 2020 |
| ASUSTek   | X510UR                      | Notebook    | [014d5ef0c8](https://linux-hardware.org/?probe=014d5ef0c8) | Jan 28, 2020 |
| ASUSTek   | X510UR                      | Notebook    | [9d05b420d4](https://linux-hardware.org/?probe=9d05b420d4) | Jan 28, 2020 |
| Lenovo    | ThinkPad L540 20AVCTO1WW    | Notebook    | [8c1dba9d6e](https://linux-hardware.org/?probe=8c1dba9d6e) | Sep 10, 2019 |
| HPE       | ProLiant BL460c Gen10       | Server      | [9e91d0ed19](https://linux-hardware.org/?probe=9e91d0ed19) | Jun 14, 2019 |
| Lenovo    | ThinkPad T480 20L6S56Y2X    | Notebook    | [f012a475eb](https://linux-hardware.org/?probe=f012a475eb) | Apr 11, 2019 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Oracle Linux 8.5 | 12        | 18.18%  |
| Oracle Linux 8.3 | 12        | 18.18%  |
| Oracle Linux 8.4 | 7         | 10.61%  |
| Oracle Linux 8.6 | 6         | 9.09%   |
| Oracle Linux 9.1 | 5         | 7.58%   |
| Oracle Linux 9.0 | 5         | 7.58%   |
| Oracle Linux 7.9 | 4         | 6.06%   |
| Oracle Linux 8.1 | 3         | 4.55%   |
| Oracle Linux 7.7 | 3         | 4.55%   |
| Oracle Linux 8.7 | 2         | 3.03%   |
| Oracle Linux 8.2 | 2         | 3.03%   |
| Oracle Linux 7.8 | 2         | 3.03%   |
| Oracle Linux 7.6 | 2         | 3.03%   |
| Oracle Linux 7.4 | 1         | 1.52%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Oracle Linux | 59        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                           | Computers | Percent |
|-----------------------------------|-----------|---------|
| 5.4.17-2102.202.5.el8uek.x86_64   | 3         | 4.17%   |
| 5.4.17-2036.103.3.1.el8uek.x86_64 | 3         | 4.17%   |
| 5.15.0-2.52.3.el9uek.x86_64       | 3         | 4.17%   |
| 4.18.0-348.12.2.el8_5.x86_64      | 3         | 4.17%   |
| 5.4.17-2136.304.4.3.el8uek.x86_64 | 2         | 2.78%   |
| 5.4.17-2102.205.7.3.el8uek.x86_64 | 2         | 2.78%   |
| 5.4.17-2102.200.13.el8uek.x86_64  | 2         | 2.78%   |
| 5.4.17-2036.102.0.2.el8uek.x86_64 | 2         | 2.78%   |
| 5.4.17-2036.101.2.el8uek.x86_64   | 2         | 2.78%   |
| 5.15.0-5.76.5.1.el9uek.x86_64     | 2         | 2.78%   |
| 4.18.0-240.15.1.el8_3.x86_64      | 2         | 2.78%   |
| 4.18.0-193.1.2.el8_2.x86_64       | 2         | 2.78%   |
| 4.18.0-147.3.1.el8_1.x86_64       | 2         | 2.78%   |
| 5.4.17-2136.313.6.el8uek.x86_64   | 1         | 1.39%   |
| 5.4.17-2136.312.3.4.el7uek.x86_64 | 1         | 1.39%   |
| 5.4.17-2136.310.7.el8uek.x86_64   | 1         | 1.39%   |
| 5.4.17-2136.310.7.1.el8uek.x86_64 | 1         | 1.39%   |
| 5.4.17-2136.309.4.el8uek.x86_64   | 1         | 1.39%   |
| 5.4.17-2136.308.9.el8uek.x86_64   | 1         | 1.39%   |
| 5.4.17-2136.308.9.el7uek.x86_64   | 1         | 1.39%   |
| 5.4.17-2136.307.3.1.el8uek.x86_64 | 1         | 1.39%   |
| 5.4.17-2136.306.1.3.el8uek.x86_64 | 1         | 1.39%   |
| 5.4.17-2136.305.5.4.el8uek.x86_64 | 1         | 1.39%   |
| 5.4.17-2136.305.5.3.el8uek.x86_64 | 1         | 1.39%   |
| 5.4.17-2136.305.5.2.el8uek.x86_64 | 1         | 1.39%   |
| 5.4.17-2136.301.1.4.el8uek.x86_64 | 1         | 1.39%   |
| 5.4.17-2136.300.7.el8uek.x86_64   | 1         | 1.39%   |
| 5.4.17-2102.204.4.4.el8uek.x86_64 | 1         | 1.39%   |
| 5.4.17-2102.204.4.2.el8uek.x86_64 | 1         | 1.39%   |
| 5.4.17-2102.201.3.el8uek.x86_64   | 1         | 1.39%   |
| 5.4.17-2036.104.4.el8uek.x86_64   | 1         | 1.39%   |
| 5.4.17-2036.100.6.1.el8uek.x86_64 | 1         | 1.39%   |
| 5.4.17-2011.0.7.el8uek.x86_64     | 1         | 1.39%   |
| 5.4.11-1.el7.elrepo.x86_64        | 1         | 1.39%   |
| 5.15.2-1.el8.elrepo.x86_64        | 1         | 1.39%   |
| 5.15.0-6.80.3.1.el9uek.x86_64     | 1         | 1.39%   |
| 5.15.0-100.76.15.el9uek.x86_64    | 1         | 1.39%   |
| 5.15.0-0.30.20.1.el9uek.x86_64    | 1         | 1.39%   |
| 5.15.0-0.30.19.el9uek.x86_64      | 1         | 1.39%   |
| 5.14.1-1.el8.elrepo.x86_64        | 1         | 1.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.17  | 26        | 42.62%  |
| 4.18.0  | 12        | 19.67%  |
| 5.15.0  | 9         | 14.75%  |
| 4.14.35 | 5         | 8.2%    |
| 3.10.0  | 3         | 4.92%   |
| 5.4.11  | 1         | 1.64%   |
| 5.15.2  | 1         | 1.64%   |
| 5.14.1  | 1         | 1.64%   |
| 5.14.0  | 1         | 1.64%   |
| 5.11.1  | 1         | 1.64%   |
| 4.1.12  | 1         | 1.64%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 27        | 44.26%  |
| 4.18    | 12        | 19.67%  |
| 5.15    | 10        | 16.39%  |
| 4.14    | 5         | 8.2%    |
| 3.10    | 3         | 4.92%   |
| 5.14    | 2         | 3.28%   |
| 5.11    | 1         | 1.64%   |
| 4.1     | 1         | 1.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 59        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 45        | 71.43%  |
| Unknown       | 8         | 12.7%   |
| GNOME Classic | 3         | 4.76%   |
| XFCE          | 2         | 3.17%   |
| MATE          | 2         | 3.17%   |
| KDE4          | 2         | 3.17%   |
| KDE5          | 1         | 1.59%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 33        | 54.1%   |
| X11     | 22        | 36.07%  |
| Unknown | 5         | 8.2%    |
| Web     | 1         | 1.64%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 32        | 52.46%  |
| GDM     | 27        | 44.26%  |
| TDM     | 1         | 1.64%   |
| SDDM    | 1         | 1.64%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 37        | 61.67%  |
| en_GB      | 5         | 8.33%   |
| de_DE      | 4         | 6.67%   |
| Unknown    | 4         | 6.67%   |
| pl_PL      | 2         | 3.33%   |
| en_AU      | 2         | 3.33%   |
| zh_HK      | 1         | 1.67%   |
| ru_RU      | 1         | 1.67%   |
| pt_BR      | 1         | 1.67%   |
| it_IT      | 1         | 1.67%   |
| en_US.UTF8 | 1         | 1.67%   |
| en_IN      | 1         | 1.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 33        | 55%     |
| BIOS | 27        | 45%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 51        | 83.61%  |
| Ext4    | 7         | 11.48%  |
| Unknown | 2         | 3.28%   |
| Zfs     | 1         | 1.64%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 28        | 45.9%   |
| GPT     | 22        | 36.07%  |
| MBR     | 11        | 18.03%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 55        | 91.67%  |
| Yes       | 5         | 8.33%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 57        | 96.61%  |
| Yes       | 2         | 3.39%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 19        | 32.2%   |
| Dell                | 12        | 20.34%  |
| Hewlett-Packard     | 7         | 11.86%  |
| ASUSTek Computer    | 7         | 11.86%  |
| Gigabyte Technology | 3         | 5.08%   |
| Intel               | 2         | 3.39%   |
| Standard            | 1         | 1.69%   |
| Panasonic           | 1         | 1.69%   |
| MSI                 | 1         | 1.69%   |
| HPE                 | 1         | 1.69%   |
| Google              | 1         | 1.69%   |
| Fujitsu             | 1         | 1.69%   |
| Foxconn             | 1         | 1.69%   |
| Dynabook            | 1         | 1.69%   |
| Apple               | 1         | 1.69%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Lenovo ThinkPad T450 20BUS14900           | 2         | 3.39%   |
| ASUS X510UR                               | 2         | 3.39%   |
| Standard BW Series                        | 1         | 1.69%   |
| Panasonic CF-53AAG54FM                    | 1         | 1.69%   |
| MSI MS-7758                               | 1         | 1.69%   |
| Lenovo ThinkPad X390 Yoga 20NQS2SF00      | 1         | 1.69%   |
| Lenovo ThinkPad X280 20KES4H34G           | 1         | 1.69%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QWS1R800 | 1         | 1.69%   |
| Lenovo ThinkPad T490 20N3S77600           | 1         | 1.69%   |
| Lenovo ThinkPad T480 20L6S56Y2X           | 1         | 1.69%   |
| Lenovo ThinkPad T480 20L5A07TAU           | 1         | 1.69%   |
| Lenovo ThinkPad T470 20HES21434           | 1         | 1.69%   |
| Lenovo ThinkPad T470 20HES0E71M           | 1         | 1.69%   |
| Lenovo ThinkPad T430s 2355C33             | 1         | 1.69%   |
| Lenovo ThinkPad P70 20ESS04S00            | 1         | 1.69%   |
| Lenovo ThinkPad P50s 20FL000MUS           | 1         | 1.69%   |
| Lenovo ThinkPad L540 20AVCTO1WW           | 1         | 1.69%   |
| Lenovo ThinkPad L490 20Q5CTO1WW           | 1         | 1.69%   |
| Lenovo Legion 5 15IMH05 82AU              | 1         | 1.69%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS       | 1         | 1.69%   |
| Lenovo IdeaPad C340-14IWL 81RL            | 1         | 1.69%   |
| Lenovo IdeaPad 300-15ISK 80RS             | 1         | 1.69%   |
| Intel NUC6CAYH                            | 1         | 1.69%   |
| Intel NUC12WSHi7                          | 1         | 1.69%   |
| HPE ProLiant BL460c Gen10                 | 1         | 1.69%   |
| HP ZBook 15                               | 1         | 1.69%   |
| HP Z820 Workstation                       | 1         | 1.69%   |
| HP ProBook 445 G6                         | 1         | 1.69%   |
| HP Notebook                               | 1         | 1.69%   |
| HP Laptop 17-cp0xxx                       | 1         | 1.69%   |
| HP EliteBook 840 G5                       | 1         | 1.69%   |
| HP Compaq 6730b                           | 1         | 1.69%   |
| Google Lick                               | 1         | 1.69%   |
| Gigabyte Z490 AORUS ELITE AC              | 1         | 1.69%   |
| Gigabyte X99-Designare EX-CF              | 1         | 1.69%   |
| Gigabyte X470 AORUS ULTRA GAMING          | 1         | 1.69%   |
| Fujitsu PRIMERGY TX150 S7                 | 1         | 1.69%   |
| Foxconn p6-2400el                         | 1         | 1.69%   |
| Dynabook PORTEGE X40-G                    | 1         | 1.69%   |
| Dell Precision M4800                      | 1         | 1.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 15        | 25.42%  |
| Dell OptiPlex          | 4         | 6.78%   |
| Lenovo IdeaPad         | 3         | 5.08%   |
| Dell Latitude          | 3         | 5.08%   |
| Dell Precision         | 2         | 3.39%   |
| Dell Inspiron          | 2         | 3.39%   |
| ASUS X510UR            | 2         | 3.39%   |
| Standard BW            | 1         | 1.69%   |
| Panasonic CF-53AAG54FM | 1         | 1.69%   |
| MSI MS-7758            | 1         | 1.69%   |
| Lenovo Legion          | 1         | 1.69%   |
| Intel NUC6CAYH         | 1         | 1.69%   |
| Intel NUC12WSHi7       | 1         | 1.69%   |
| HPE ProLiant           | 1         | 1.69%   |
| HP ZBook               | 1         | 1.69%   |
| HP Z820                | 1         | 1.69%   |
| HP ProBook             | 1         | 1.69%   |
| HP Notebook            | 1         | 1.69%   |
| HP Laptop              | 1         | 1.69%   |
| HP EliteBook           | 1         | 1.69%   |
| HP Compaq              | 1         | 1.69%   |
| Google Lick            | 1         | 1.69%   |
| Gigabyte Z490          | 1         | 1.69%   |
| Gigabyte X99-Designare | 1         | 1.69%   |
| Gigabyte X470          | 1         | 1.69%   |
| Fujitsu PRIMERGY       | 1         | 1.69%   |
| Foxconn p6-2400el      | 1         | 1.69%   |
| Dynabook PORTEGE       | 1         | 1.69%   |
| Dell PowerEdge         | 1         | 1.69%   |
| ASUS UX305FA           | 1         | 1.69%   |
| ASUS PRIME             | 1         | 1.69%   |
| ASUS P8H67             | 1         | 1.69%   |
| ASUS G11CD             | 1         | 1.69%   |
| ASUS All               | 1         | 1.69%   |
| Apple Macmini7         | 1         | 1.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 8         | 13.56%  |
| 2018 | 8         | 13.56%  |
| 2016 | 6         | 10.17%  |
| 2020 | 5         | 8.47%   |
| 2021 | 4         | 6.78%   |
| 2017 | 4         | 6.78%   |
| 2015 | 4         | 6.78%   |
| 2012 | 4         | 6.78%   |
| 2022 | 3         | 5.08%   |
| 2014 | 3         | 5.08%   |
| 2013 | 3         | 5.08%   |
| 2011 | 3         | 5.08%   |
| 2010 | 3         | 5.08%   |
| 2008 | 1         | 1.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 37        | 62.71%  |
| Desktop     | 15        | 25.42%  |
| Mini pc     | 3         | 5.08%   |
| Convertible | 2         | 3.39%   |
| Server      | 2         | 3.39%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 52        | 86.67%  |
| Enabled  | 8         | 13.33%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 58        | 98.31%  |
| Yes  | 1         | 1.69%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 17        | 28.33%  |
| 32.01-64.0      | 13        | 21.67%  |
| 4.01-8.0        | 10        | 16.67%  |
| 16.01-24.0      | 6         | 10%     |
| 3.01-4.0        | 5         | 8.33%   |
| 64.01-256.0     | 4         | 6.67%   |
| 24.01-32.0      | 3         | 5%      |
| More than 256.0 | 1         | 1.67%   |
| 1.01-2.0        | 1         | 1.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 20        | 29.85%  |
| 2.01-3.0   | 18        | 26.87%  |
| 3.01-4.0   | 9         | 13.43%  |
| 8.01-16.0  | 8         | 11.94%  |
| 1.01-2.0   | 7         | 10.45%  |
| 0.51-1.0   | 2         | 2.99%   |
| 24.01-32.0 | 1         | 1.49%   |
| 16.01-24.0 | 1         | 1.49%   |
| 0.01-0.5   | 1         | 1.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 46        | 76.67%  |
| 2      | 7         | 11.67%  |
| 3      | 3         | 5%      |
| 4      | 2         | 3.33%   |
| 6      | 1         | 1.67%   |
| 5      | 1         | 1.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 74.58%  |
| Yes       | 15        | 25.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 84.75%  |
| No        | 9         | 15.25%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 79.66%  |
| No        | 12        | 20.34%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 60%     |
| No        | 24        | 40%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 19        | 31.67%  |
| Germany     | 8         | 13.33%  |
| UK          | 4         | 6.67%   |
| Brazil      | 4         | 6.67%   |
| Poland      | 3         | 5%      |
| Netherlands | 3         | 5%      |
| Australia   | 3         | 5%      |
| Russia      | 2         | 3.33%   |
| Romania     | 2         | 3.33%   |
| Finland     | 2         | 3.33%   |
| Yemen       | 1         | 1.67%   |
| Pakistan    | 1         | 1.67%   |
| Kazakhstan  | 1         | 1.67%   |
| Italy       | 1         | 1.67%   |
| India       | 1         | 1.67%   |
| Hungary     | 1         | 1.67%   |
| Hong Kong   | 1         | 1.67%   |
| Bulgaria    | 1         | 1.67%   |
| Bolivia     | 1         | 1.67%   |
| Argentina   | 1         | 1.67%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| San Diego          | 3         | 4.62%   |
| Siegen             | 2         | 3.08%   |
| Seattle            | 2         | 3.08%   |
| Sao Paulo          | 2         | 3.08%   |
| Helsinki           | 2         | 3.08%   |
| Colorado Springs   | 2         | 3.08%   |
| Bucharest          | 2         | 3.08%   |
| Berlin             | 2         | 3.08%   |
| Amsterdam          | 2         | 3.08%   |
| Weaverville        | 1         | 1.54%   |
| Warsaw             | 1         | 1.54%   |
| Veliky Novgorod    | 1         | 1.54%   |
| Utrecht            | 1         | 1.54%   |
| Sydney             | 1         | 1.54%   |
| Sofia              | 1         | 1.54%   |
| Shrewsbury         | 1         | 1.54%   |
| Sao Caetano do Sul | 1         | 1.54%   |
| Santa Cruz         | 1         | 1.54%   |
| Sanaa              | 1         | 1.54%   |
| San Francisco      | 1         | 1.54%   |
| Rocklin            | 1         | 1.54%   |
| Riverside          | 1         | 1.54%   |
| Reading            | 1         | 1.54%   |
| Port Saint Lucie   | 1         | 1.54%   |
| Pleven             | 1         | 1.54%   |
| Parker             | 1         | 1.54%   |
| Ngau Wu Tok        | 1         | 1.54%   |
| Neunkirchen        | 1         | 1.54%   |
| Moscow             | 1         | 1.54%   |
| Maple Valley       | 1         | 1.54%   |
| Ludwigsburg        | 1         | 1.54%   |
| London             | 1         | 1.54%   |
| Las Vegas          | 1         | 1.54%   |
| Langgons           | 1         | 1.54%   |
| Katowice           | 1         | 1.54%   |
| Karaganda          | 1         | 1.54%   |
| Karachi            | 1         | 1.54%   |
| Itzehoe            | 1         | 1.54%   |
| Houston            | 1         | 1.54%   |
| Greven             | 1         | 1.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 21        | 27     | 28%     |
| Seagate                 | 10        | 48     | 13.33%  |
| SanDisk                 | 7         | 10     | 9.33%   |
| WDC                     | 5         | 5      | 6.67%   |
| Crucial                 | 4         | 5      | 5.33%   |
| Unknown                 | 3         | 5      | 4%      |
| Kingston                | 3         | 10     | 4%      |
| HGST                    | 3         | 6      | 4%      |
| Toshiba                 | 2         | 2      | 2.67%   |
| SK hynix                | 2         | 2      | 2.67%   |
| Micron Technology       | 2         | 5      | 2.67%   |
| Hewlett-Packard         | 2         | 2      | 2.67%   |
| Union Memory (Shenzhen) | 1         | 2      | 1.33%   |
| Phison Electronics      | 1         | 1      | 1.33%   |
| Phison                  | 1         | 1      | 1.33%   |
| Lite-On                 | 1         | 1      | 1.33%   |
| Lenovo                  | 1         | 1      | 1.33%   |
| KIOXIA                  | 1         | 1      | 1.33%   |
| JMicron Technology      | 1         | 1      | 1.33%   |
| Intel                   | 1         | 1      | 1.33%   |
| HPE                     | 1         | 1      | 1.33%   |
| Fujitsu                 | 1         | 1      | 1.33%   |
| Apple                   | 1         | 1      | 1.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seagate ST2000DM008-2FR102 2TB               | 2         | 2.47%   |
| SanDisk SSD PLUS 1000GB                      | 2         | 2.47%   |
| Samsung SSD PM830 2.5 7mm 256GB              | 2         | 2.47%   |
| Samsung MZVLB512HAJQ-000L7 512GB             | 2         | 2.47%   |
| Samsung MZ7LN512HMJP-000L7 512GB SSD         | 2         | 2.47%   |
| Kingston SA400S37240G 240GB SSD              | 2         | 2.47%   |
| Crucial CT500MX500SSD1 500GB                 | 2         | 2.47%   |
| WDC WDS500G2B0A-00SM50 500GB SSD             | 1         | 1.23%   |
| WDC WDS250G2B0A-00SM50 250GB SSD             | 1         | 1.23%   |
| WDC WD10SPZX-60Z10T1 1TB                     | 1         | 1.23%   |
| WDC WD10JPCX-24UE4T0 1TB                     | 1         | 1.23%   |
| WDC WD10EZEX-60M2NA0 1TB                     | 1         | 1.23%   |
| Unknown SD/MMC/MS PRO 16GB                   | 1         | 1.23%   |
| Unknown MMC64G  64GB                         | 1         | 1.23%   |
| Unknown MMC Card  256GB                      | 1         | 1.23%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 1.23%   |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 1.23%   |
| Toshiba MG04ACA200E 2TB                      | 1         | 1.23%   |
| SK hynix SKHynix_HFS256GD9TNG-L3A0B 256GB    | 1         | 1.23%   |
| SK hynix PC801 NVMe 512GB                    | 1         | 1.23%   |
| Seagate ST9750420AS 752GB                    | 1         | 1.23%   |
| Seagate ST8000VN004-2M2101 8TB               | 1         | 1.23%   |
| Seagate ST3750528AS 752GB                    | 1         | 1.23%   |
| Seagate ST3500414CS 500GB                    | 1         | 1.23%   |
| Seagate ST2000NX0253 2TB                     | 1         | 1.23%   |
| Seagate ST2000DM001-1ER164 2TB               | 1         | 1.23%   |
| Seagate ST1000NX0423 1TB                     | 1         | 1.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1.23%   |
| Seagate ST1000LM010-9YH146 1TB               | 1         | 1.23%   |
| Seagate BUP Slim BK 1TB                      | 1         | 1.23%   |
| SanDisk SSD PLUS 2000GB                      | 1         | 1.23%   |
| SanDisk SDSSDH3512G 512GB                    | 1         | 1.23%   |
| SanDisk SDSSDH32000G 2TB                     | 1         | 1.23%   |
| SanDisk SD7SN3Q256G1002 256GB SSD            | 1         | 1.23%   |
| SanDisk SD6SB1M-256G-1006 256GB SSD          | 1         | 1.23%   |
| SanDisk NVMe SSD Drive 512GB                 | 1         | 1.23%   |
| Samsung SSD SM841N 2.5 7mm 512GB             | 1         | 1.23%   |
| Samsung SSD 960 EVO 250GB                    | 1         | 1.23%   |
| Samsung SSD 860 EVO 250GB                    | 1         | 1.23%   |
| Samsung SSD 850 PRO 256GB                    | 1         | 1.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 48     | 43.48%  |
| WDC                 | 3         | 3      | 13.04%  |
| HGST                | 3         | 6      | 13.04%  |
| Unknown             | 1         | 3      | 4.35%   |
| Toshiba             | 1         | 1      | 4.35%   |
| Samsung Electronics | 1         | 1      | 4.35%   |
| JMicron Technology  | 1         | 1      | 4.35%   |
| HPE                 | 1         | 1      | 4.35%   |
| Fujitsu             | 1         | 1      | 4.35%   |
| Apple               | 1         | 1      | 4.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 15     | 44.44%  |
| SanDisk             | 6         | 8      | 22.22%  |
| Crucial             | 3         | 4      | 11.11%  |
| WDC                 | 2         | 2      | 7.41%   |
| Kingston            | 2         | 3      | 7.41%   |
| Hewlett-Packard     | 2         | 2      | 7.41%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 25        | 34     | 34.72%  |
| NVMe | 24        | 37     | 33.33%  |
| HDD  | 21        | 66     | 29.17%  |
| MMC  | 2         | 2      | 2.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 39        | 94     | 57.35%  |
| NVMe | 24        | 37     | 35.29%  |
| SAS  | 3         | 6      | 4.41%   |
| MMC  | 2         | 2      | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 21        | 26     | 44.68%  |
| 0.51-1.0   | 18        | 27     | 38.3%   |
| 1.01-2.0   | 7         | 45     | 14.89%  |
| 4.01-10.0  | 1         | 2      | 2.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 14        | 23.33%  |
| 101-250        | 12        | 20%     |
| 501-1000       | 9         | 15%     |
| Unknown        | 7         | 11.67%  |
| 1-20           | 6         | 10%     |
| 51-100         | 4         | 6.67%   |
| 2001-3000      | 3         | 5%      |
| 1001-2000      | 3         | 5%      |
| More than 3000 | 1         | 1.67%   |
| 21-50          | 1         | 1.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 20        | 32.26%  |
| 21-50          | 13        | 20.97%  |
| 101-250        | 7         | 11.29%  |
| 51-100         | 7         | 11.29%  |
| Unknown        | 7         | 11.29%  |
| 251-500        | 4         | 6.45%   |
| 501-1000       | 2         | 3.23%   |
| More than 3000 | 1         | 1.61%   |
| 1001-2000      | 1         | 1.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST9750420AS 752GB          | 1         | 1      | 33.33%  |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 33.33%  |
| Hewlett-Packard SSD S700 120GB     | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| Seagate         | 2         | 2      | 66.67%  |
| Hewlett-Packard | 1         | 1      | 33.33%  |

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
| HDD  | 2         | 2      | 66.67%  |
| SSD  | 1         | 1      | 33.33%  |

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
| Detected | 32        | 64     | 51.61%  |
| Works    | 27        | 72     | 43.55%  |
| Malfunc  | 3         | 3      | 4.84%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 39        | 54.17%  |
| Samsung Electronics          | 9         | 12.5%   |
| AMD                          | 5         | 6.94%   |
| Broadcom / LSI               | 3         | 4.17%   |
| SK hynix                     | 2         | 2.78%   |
| Phison Electronics           | 2         | 2.78%   |
| Micron Technology            | 2         | 2.78%   |
| VIA Technologies             | 1         | 1.39%   |
| Union Memory (Shenzhen)      | 1         | 1.39%   |
| Toshiba America Info Systems | 1         | 1.39%   |
| SanDisk                      | 1         | 1.39%   |
| Micron/Crucial Technology    | 1         | 1.39%   |
| Lite-On Technology           | 1         | 1.39%   |
| Lenovo                       | 1         | 1.39%   |
| KIOXIA                       | 1         | 1.39%   |
| Kingston Technology Company  | 1         | 1.39%   |
| Adaptec                      | 1         | 1.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 7.59%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 5         | 6.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4         | 5.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 3.8%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 3.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 3.8%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 2.53%   |
| Phison E12 NVMe Controller                                                       | 2         | 2.53%   |
| Micron Non-Volatile memory controller                                            | 2         | 2.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 2.53%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2         | 2.53%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 2         | 2.53%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 2.53%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 2         | 2.53%   |
| VIA VT6415 PATA IDE Host Controller                                              | 1         | 1.27%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 1.27%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 1         | 1.27%   |
| SK hynix Platinum P41 NVMe Solid State Drive 2TB                                 | 1         | 1.27%   |
| SK hynix Non-Volatile memory controller                                          | 1         | 1.27%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 1.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 1.27%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 1.27%   |
| Lite-On Non-Volatile memory controller                                           | 1         | 1.27%   |
| Lenovo Non-Volatile memory controller                                            | 1         | 1.27%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 1.27%   |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 1.27%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 1.27%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 1.27%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.27%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.27%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.27%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 1.27%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 1         | 1.27%   |
| Intel C600/X79 series chipset SATA RAID Controller                               | 1         | 1.27%   |
| Intel C600/X79 series chipset IDE-r Controller                                   | 1         | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.27%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 1         | 1.27%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 1         | 1.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 1.27%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1         | 1.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 36        | 50%     |
| NVMe | 24        | 33.33%  |
| RAID | 6         | 8.33%   |
| IDE  | 3         | 4.17%   |
| SAS  | 2         | 2.78%   |
| SCSI | 1         | 1.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 54        | 91.53%  |
| AMD    | 5         | 8.47%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i7-8665U CPU @ 1.90GHz    | 2         | 3.39%   |
| Intel Core i7-7500U CPU @ 2.70GHz    | 2         | 3.39%   |
| Intel Core i7-6500U CPU @ 2.50GHz    | 2         | 3.39%   |
| Intel Core i7-10610U CPU @ 1.80GHz   | 2         | 3.39%   |
| Intel Core i5-8350U CPU @ 1.70GHz    | 2         | 3.39%   |
| Intel Core i5-7300U CPU @ 2.60GHz    | 2         | 3.39%   |
| Intel Core i5-5300U CPU @ 2.30GHz    | 2         | 3.39%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz | 1         | 1.69%   |
| Intel Xeon CPU X3430 @ 2.40GHz       | 1         | 1.69%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz  | 1         | 1.69%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz  | 1         | 1.69%   |
| Intel Processor 5Y10 CPU @ 0.80GHz   | 1         | 1.69%   |
| Intel Pentium CPU G2020 @ 2.90GHz    | 1         | 1.69%   |
| Intel Core i9-9880H CPU @ 2.30GHz    | 1         | 1.69%   |
| Intel Core i9-10900K CPU @ 3.70GHz   | 1         | 1.69%   |
| Intel Core i7-8700 CPU @ 3.20GHz     | 1         | 1.69%   |
| Intel Core i7-8650U CPU @ 1.90GHz    | 1         | 1.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz    | 1         | 1.69%   |
| Intel Core i7-8550U CPU @ 1.80GHz    | 1         | 1.69%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz   | 1         | 1.69%   |
| Intel Core i7-6800K CPU @ 3.40GHz    | 1         | 1.69%   |
| Intel Core i7-6700 CPU @ 3.40GHz     | 1         | 1.69%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz   | 1         | 1.69%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz   | 1         | 1.69%   |
| Intel Core i7-3770 CPU @ 3.40GHz     | 1         | 1.69%   |
| Intel Core i7-2860QM CPU @ 2.50GHz   | 1         | 1.69%   |
| Intel Core i7-2760QM CPU @ 2.40GHz   | 1         | 1.69%   |
| Intel Core i7-2600 CPU @ 3.40GHz     | 1         | 1.69%   |
| Intel Core i7-10750H CPU @ 2.60GHz   | 1         | 1.69%   |
| Intel Core i7-10700K CPU @ 3.80GHz   | 1         | 1.69%   |
| Intel Core i5-8365U CPU @ 1.60GHz    | 1         | 1.69%   |
| Intel Core i5-4460 CPU @ 3.20GHz     | 1         | 1.69%   |
| Intel Core i5-4278U CPU @ 2.60GHz    | 1         | 1.69%   |
| Intel Core i5-4210U CPU @ 1.70GHz    | 1         | 1.69%   |
| Intel Core i5-4210M CPU @ 2.60GHz    | 1         | 1.69%   |
| Intel Core i5-3320M CPU @ 2.60GHz    | 1         | 1.69%   |
| Intel Core i5-2520M CPU @ 2.50GHz    | 1         | 1.69%   |
| Intel Core i5-10500 CPU @ 3.10GHz    | 1         | 1.69%   |
| Intel Core i3 CPU 550 @ 3.20GHz      | 1         | 1.69%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz | 1         | 1.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i7     | 23        | 38.98%  |
| Intel Core i5     | 14        | 23.73%  |
| Other             | 6         | 10.17%  |
| Intel Xeon        | 3         | 5.08%   |
| Intel Celeron     | 3         | 5.08%   |
| Intel Core i9     | 2         | 3.39%   |
| AMD Ryzen 7       | 2         | 3.39%   |
| Intel Xeon Silver | 1         | 1.69%   |
| Intel Pentium     | 1         | 1.69%   |
| Intel Core i3     | 1         | 1.69%   |
| Intel Core 2 Duo  | 1         | 1.69%   |
| AMD Ryzen 7 PRO   | 1         | 1.69%   |
| AMD A8            | 1         | 1.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 24        | 40.68%  |
| 2      | 20        | 33.9%   |
| 8      | 4         | 6.78%   |
| 6      | 4         | 6.78%   |
| 16     | 2         | 3.39%   |
| 12     | 2         | 3.39%   |
| 20     | 1         | 1.69%   |
| 10     | 1         | 1.69%   |
| 1      | 1         | 1.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 56        | 94.92%  |
| 2      | 3         | 5.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 49        | 83.05%  |
| 1      | 10        | 16.95%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 58        | 96.67%  |
| Unknown        | 2         | 3.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ec    | 6         | 10.17%  |
| 0x806ea    | 4         | 6.78%   |
| 0x306c3    | 4         | 6.78%   |
| 0x206a7    | 4         | 6.78%   |
| Unknown    | 4         | 6.78%   |
| 0x306d4    | 3         | 5.08%   |
| 0x306a9    | 3         | 5.08%   |
| 0xa0655    | 2         | 3.39%   |
| 0x806e9    | 2         | 3.39%   |
| 0x806c1    | 2         | 3.39%   |
| 0x506e3    | 2         | 3.39%   |
| 0x406e3    | 2         | 3.39%   |
| 0x40651    | 2         | 3.39%   |
| 0xa0653    | 1         | 1.69%   |
| 0xa0652    | 1         | 1.69%   |
| 0x906ed    | 1         | 1.69%   |
| 0x906ea    | 1         | 1.69%   |
| 0x906a3    | 1         | 1.69%   |
| 0x706a8    | 1         | 1.69%   |
| 0x506c9    | 1         | 1.69%   |
| 0x50654    | 1         | 1.69%   |
| 0x406f1    | 1         | 1.69%   |
| 0x406c4    | 1         | 1.69%   |
| 0x306e4    | 1         | 1.69%   |
| 0x20655    | 1         | 1.69%   |
| 0x106e5    | 1         | 1.69%   |
| 0x10676    | 1         | 1.69%   |
| 0x08608103 | 1         | 1.69%   |
| 0x0810100b | 1         | 1.69%   |
| 0x0800820d | 1         | 1.69%   |
| 0x07030105 | 1         | 1.69%   |
| 0x06006705 | 1         | 1.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 16        | 27.12%  |
| Haswell          | 6         | 10.17%  |
| Skylake          | 5         | 8.47%   |
| Broadwell        | 5         | 8.47%   |
| SandyBridge      | 4         | 6.78%   |
| IvyBridge        | 4         | 6.78%   |
| CometLake        | 4         | 6.78%   |
| TigerLake        | 2         | 3.39%   |
| Unknown          | 2         | 3.39%   |
| Zen+             | 1         | 1.69%   |
| Zen              | 1         | 1.69%   |
| Westmere         | 1         | 1.69%   |
| Silvermont       | 1         | 1.69%   |
| Puma             | 1         | 1.69%   |
| Penryn           | 1         | 1.69%   |
| Nehalem          | 1         | 1.69%   |
| Goldmont plus    | 1         | 1.69%   |
| Goldmont         | 1         | 1.69%   |
| Excavator        | 1         | 1.69%   |
| Alderlake Hybrid | 1         | 1.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 42        | 57.53%  |
| Nvidia                     | 19        | 26.03%  |
| AMD                        | 9         | 12.33%  |
| Matrox Electronics Systems | 3         | 4.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 5.48%   |
| Intel UHD Graphics 620                                                                   | 4         | 5.48%   |
| Intel HD Graphics 620                                                                    | 4         | 5.48%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 4.11%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 4.11%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 2.74%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 2.74%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.74%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 2.74%   |
| Intel HD Graphics 5500                                                                   | 2         | 2.74%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.74%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2.74%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.37%   |
| Nvidia TU117M                                                                            | 1         | 1.37%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 1.37%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 1.37%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 1.37%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 1.37%   |
| Nvidia GM204GLM [Quadro M4000M]                                                          | 1         | 1.37%   |
| Nvidia GM204 [GeForce GTX 980]                                                           | 1         | 1.37%   |
| Nvidia GM108GLM [Quadro K620M / Quadro M500M]                                            | 1         | 1.37%   |
| Nvidia GK208GLM [Quadro K610M]                                                           | 1         | 1.37%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 1.37%   |
| Nvidia GK110GL [Quadro K6000]                                                            | 1         | 1.37%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 1.37%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                                           | 1         | 1.37%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 1         | 1.37%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 1         | 1.37%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1         | 1.37%   |
| Matrox Electronics Systems G200eR2                                                       | 1         | 1.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 1.37%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 1.37%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.37%   |
| Intel HD Graphics 5300                                                                   | 1         | 1.37%   |
| Intel HD Graphics 500                                                                    | 1         | 1.37%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.37%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.37%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.37%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 27        | 45%     |
| 1 x Nvidia     | 11        | 18.33%  |
| Intel + Nvidia | 9         | 15%     |
| 1 x AMD        | 6         | 10%     |
| 1 x Matrox     | 3         | 5%      |
| Intel + AMD    | 3         | 5%      |
| Other          | 1         | 1.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 52        | 85.25%  |
| Proprietary | 5         | 8.2%    |
| Unknown     | 4         | 6.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 55%     |
| 1.01-2.0   | 11        | 18.33%  |
| 3.01-4.0   | 8         | 13.33%  |
| 0.51-1.0   | 3         | 5%      |
| 0.01-0.5   | 3         | 5%      |
| 5.01-6.0   | 1         | 1.67%   |
| 8.01-16.0  | 1         | 1.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 12        | 15.79%  |
| Samsung Electronics  | 9         | 11.84%  |
| LG Display           | 9         | 11.84%  |
| Dell                 | 8         | 10.53%  |
| Chimei Innolux       | 6         | 7.89%   |
| BOE                  | 5         | 6.58%   |
| Lenovo               | 4         | 5.26%   |
| ViewSonic            | 3         | 3.95%   |
| InfoVision           | 3         | 3.95%   |
| BenQ                 | 3         | 3.95%   |
| Hewlett-Packard      | 2         | 2.63%   |
| Acer                 | 2         | 2.63%   |
| Viotek               | 1         | 1.32%   |
| Sony                 | 1         | 1.32%   |
| SAC                  | 1         | 1.32%   |
| Panasonic            | 1         | 1.32%   |
| Goldstar             | 1         | 1.32%   |
| Element              | 1         | 1.32%   |
| Eizo                 | 1         | 1.32%   |
| BOE Technology Group | 1         | 1.32%   |
| ASUSTek Computer     | 1         | 1.32%   |
| Ancor Communications | 1         | 1.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 2         | 2.47%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 2         | 2.47%   |
| Dell U2718Q DELA0E9 3840x2160 609x349mm 27.6-inch                     | 2         | 2.47%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 2.47%   |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                     | 2         | 2.47%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch         | 2         | 2.47%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 2         | 2.47%   |
| Viotek SUW49C VTK4900 3840x1080 1196x336mm 48.9-inch                  | 1         | 1.23%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch         | 1         | 1.23%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch              | 1         | 1.23%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 521x293mm 23.5-inch         | 1         | 1.23%   |
| Sony TV SNY4502 1920x1080                                             | 1         | 1.23%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch   | 1         | 1.23%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch  | 1         | 1.23%   |
| Samsung Electronics SAMTRON STN0022 1280x1024 376x301mm 19.0-inch     | 1         | 1.23%   |
| Samsung Electronics S27D391 SAM0B89 1920x1080 598x336mm 27.0-inch     | 1         | 1.23%   |
| Samsung Electronics S27D391 SAM0B88 1920x1080 598x336mm 27.0-inch     | 1         | 1.23%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 1.23%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch     | 1         | 1.23%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SDC3256 1920x1080 382x215mm 17.3-inch | 1         | 1.23%   |
| Samsung Electronics LCD Monitor S24C650                               | 1         | 1.23%   |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 697x392mm 31.5-inch     | 1         | 1.23%   |
| SAC LED MONITOR SAC952D 1920x1080 443x249mm 20.0-inch                 | 1         | 1.23%   |
| Panasonic TV MEIA296 3840x2160 1872x1053mm 84.6-inch                  | 1         | 1.23%   |
| LG Display LCD Monitor LGD0628 1920x1080 309x174mm 14.0-inch          | 1         | 1.23%   |
| LG Display LCD Monitor LGD0609 1920x1080 309x174mm 14.0-inch          | 1         | 1.23%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch           | 1         | 1.23%   |
| LG Display LCD Monitor LGD047C 1366x768 310x174mm 14.0-inch           | 1         | 1.23%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 1.23%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 1         | 1.23%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch          | 1         | 1.23%   |
| Lenovo T24i-10 LEN61A6 1920x1080 527x296mm 23.8-inch                  | 1         | 1.23%   |
| Lenovo LEN T2424pA LEN60C8 1920x1080 527x296mm 23.8-inch              | 1         | 1.23%   |
| Lenovo LEN T2254pC LEN60CC 1680x1050 474x296mm 22.0-inch              | 1         | 1.23%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch              | 1         | 1.23%   |
| InfoVision LCD Monitor IVO048E 1366x768 256x144mm 11.6-inch           | 1         | 1.23%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch            | 1         | 1.23%   |
| Hewlett-Packard E273q HPN3474 2560x1440 597x336mm 27.0-inch           | 1         | 1.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 38        | 58.46%  |
| 3840x2160 (4K)     | 5         | 7.69%   |
| 1366x768 (WXGA)    | 5         | 7.69%   |
| 1600x900 (HD+)     | 4         | 6.15%   |
| 1280x1024 (SXGA)   | 3         | 4.62%   |
| 2560x1440 (QHD)    | 2         | 3.08%   |
| 1680x1050 (WSXGA+) | 2         | 3.08%   |
| 3840x1200          | 1         | 1.54%   |
| 3840x1080          | 1         | 1.54%   |
| 1920x1200 (WUXGA)  | 1         | 1.54%   |
| 1360x768           | 1         | 1.54%   |
| 1280x800 (WXGA)    | 1         | 1.54%   |
| Unknown            | 1         | 1.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 14        | 18.18%  |
| 14      | 12        | 15.58%  |
| 27      | 8         | 10.39%  |
| 24      | 8         | 10.39%  |
| 13      | 7         | 9.09%   |
| 23      | 5         | 6.49%   |
| 21      | 3         | 3.9%    |
| Unknown | 3         | 3.9%    |
| 38      | 2         | 2.6%    |
| 31      | 2         | 2.6%    |
| 19      | 2         | 2.6%    |
| 17      | 2         | 2.6%    |
| 84      | 1         | 1.3%    |
| 72      | 1         | 1.3%    |
| 48      | 1         | 1.3%    |
| 32      | 1         | 1.3%    |
| 22      | 1         | 1.3%    |
| 20      | 1         | 1.3%    |
| 18      | 1         | 1.3%    |
| 12      | 1         | 1.3%    |
| 11      | 1         | 1.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 41.33%  |
| 501-600     | 20        | 26.67%  |
| 401-500     | 6         | 8%      |
| 201-300     | 4         | 5.33%   |
| 351-400     | 3         | 4%      |
| Unknown     | 3         | 4%      |
| 801-900     | 2         | 2.67%   |
| 601-700     | 2         | 2.67%   |
| 1501-2000   | 2         | 2.67%   |
| 701-800     | 1         | 1.33%   |
| 1001-1500   | 1         | 1.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 50        | 83.33%  |
| 16/10   | 4         | 6.67%   |
| 5/4     | 3         | 5%      |
| Unknown | 2         | 3.33%   |
| 32/9    | 1         | 1.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 17        | 22.67%  |
| 201-250        | 14        | 18.67%  |
| 101-110        | 14        | 18.67%  |
| 301-350        | 8         | 10.67%  |
| 351-500        | 3         | 4%      |
| 151-200        | 3         | 4%      |
| 501-1000       | 3         | 4%      |
| Unknown        | 3         | 4%      |
| More than 1000 | 2         | 2.67%   |
| 71-80          | 2         | 2.67%   |
| 121-130        | 2         | 2.67%   |
| 61-70          | 1         | 1.33%   |
| 51-60          | 1         | 1.33%   |
| 251-300        | 1         | 1.33%   |
| 141-150        | 1         | 1.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 30        | 42.25%  |
| 51-100  | 23        | 32.39%  |
| 101-120 | 10        | 14.08%  |
| 161-240 | 4         | 5.63%   |
| Unknown | 3         | 4.23%   |
| 1-50    | 1         | 1.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 38        | 63.33%  |
| 2     | 12        | 20%     |
| 3     | 5         | 8.33%   |
| 0     | 4         | 6.67%   |
| 4     | 1         | 1.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 45        | 54.22%  |
| Realtek Semiconductor | 19        | 22.89%  |
| Broadcom              | 5         | 6.02%   |
| Qualcomm Atheros      | 4         | 4.82%   |
| Lenovo                | 3         | 3.61%   |
| Broadcom Limited      | 2         | 2.41%   |
| Ralink Technology     | 1         | 1.2%    |
| QLogic                | 1         | 1.2%    |
| NetGear               | 1         | 1.2%    |
| Fibocom               | 1         | 1.2%    |
| ASIX Electronics      | 1         | 1.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 8.11%   |
| Intel Wireless 8265 / 8275                                        | 8         | 7.21%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 4.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 4.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 3.6%    |
| Intel Wireless 8260                                               | 4         | 3.6%    |
| Intel Wireless 7265                                               | 3         | 2.7%    |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 2.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 2.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.8%    |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 1.8%    |
| Intel Wireless 7260                                               | 2         | 1.8%    |
| Intel I211 Gigabit Network Connection                             | 2         | 1.8%    |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.8%    |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.8%    |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.8%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.8%    |
| Intel 82574L Gigabit Network Connection                           | 2         | 1.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.9%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.9%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.9%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.9%    |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.9%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.9%    |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller          | 1         | 0.9%    |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                   | 1         | 0.9%    |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 0.9%    |
| Intel Wireless-AC 9260                                            | 1         | 0.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 0.9%    |
| Intel Wi-Fi 6 AX201                                               | 1         | 0.9%    |
| Intel Wi-Fi 6 AX200                                               | 1         | 0.9%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 0.9%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 0.9%    |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1         | 0.9%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 37        | 72.55%  |
| Realtek Semiconductor | 5         | 9.8%    |
| Qualcomm Atheros      | 4         | 7.84%   |
| Ralink Technology     | 1         | 1.96%   |
| NetGear               | 1         | 1.96%   |
| Fibocom               | 1         | 1.96%   |
| Broadcom Limited      | 1         | 1.96%   |
| Broadcom              | 1         | 1.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 8         | 15.69%  |
| Intel Wireless 8260                                            | 4         | 7.84%   |
| Intel Wireless 7265                                            | 3         | 5.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 5.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 3.92%   |
| Intel Wireless 7260                                            | 2         | 3.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 3.92%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 3.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 3.92%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 1.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.96%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.96%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 1.96%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 1.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.96%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.96%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                | 1         | 1.96%   |
| Intel Wireless-AC 9260                                         | 1         | 1.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 1.96%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 1.96%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 1.96%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.96%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.96%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 1.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.96%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.96%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.96%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 1         | 1.96%   |
| Fibocom L830-EB-00 LTE WWAN Modem                              | 1         | 1.96%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 1         | 1.96%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 1.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 32        | 55.17%  |
| Realtek Semiconductor | 16        | 27.59%  |
| Broadcom              | 4         | 6.9%    |
| Lenovo                | 3         | 5.17%   |
| QLogic                | 1         | 1.72%   |
| Broadcom Limited      | 1         | 1.72%   |
| ASIX Electronics      | 1         | 1.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 15%     |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 8.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 8.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 6.67%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 5%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 3.33%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 3.33%   |
| Intel I211 Gigabit Network Connection                             | 2         | 3.33%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 3.33%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 3.33%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 3.33%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 3.33%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.67%   |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller          | 1         | 1.67%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 1.67%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.67%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.67%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.67%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.67%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.67%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.67%   |
| Intel Ethernet Connection (17) I219-LM                            | 1         | 1.67%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.67%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.67%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection             | 1         | 1.67%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 1.67%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1         | 1.67%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.67%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 1.67%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 1.67%   |
| Broadcom BCM57840 NetXtreme II 10/20-Gigabit Ethernet             | 1         | 1.67%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 50        | 51.55%  |
| WiFi     | 47        | 48.45%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 32        | 50.79%  |
| WiFi     | 31        | 49.21%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 37        | 62.71%  |
| 1     | 19        | 32.2%   |
| 4     | 2         | 3.39%   |
| 3     | 1         | 1.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 47        | 74.6%   |
| Yes  | 16        | 25.4%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 67.57%  |
| Qualcomm Atheros Communications | 3         | 8.11%   |
| Broadcom                        | 3         | 8.11%   |
| Realtek Semiconductor           | 2         | 5.41%   |
| IMC Networks                    | 1         | 2.7%    |
| ASUSTek Computer                | 1         | 2.7%    |
| Apple                           | 1         | 2.7%    |
| Alps Electric                   | 1         | 2.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 13        | 35.14%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 5         | 13.51%  |
| Intel AX201 Bluetooth                          | 3         | 8.11%   |
| Qualcomm Atheros  Bluetooth Device             | 2         | 5.41%   |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 2.7%    |
| Realtek Bluetooth Radio                        | 1         | 2.7%    |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 2.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1         | 2.7%    |
| Intel Wireless-AC 3168 Bluetooth               | 1         | 2.7%    |
| Intel Bluetooth Device                         | 1         | 2.7%    |
| Intel AX210 Bluetooth                          | 1         | 2.7%    |
| IMC Networks Bluetooth Radio                   | 1         | 2.7%    |
| Broadcom BCM43142A0 Bluetooth 4.0              | 1         | 2.7%    |
| Broadcom BCM20702A0 Bluetooth 4.0              | 1         | 2.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 2.7%    |
| ASUS Broadcom BCM20702A0 Bluetooth             | 1         | 2.7%    |
| Apple Bluetooth Host Controller                | 1         | 2.7%    |
| Alps Electric UGTZ4 Bluetooth                  | 1         | 2.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 50        | 60.24%  |
| Nvidia              | 12        | 14.46%  |
| AMD                 | 8         | 9.64%   |
| Lenovo              | 5         | 6.02%   |
| GN Netcom           | 5         | 6.02%   |
| Unknown             | 1         | 1.2%    |
| TEAC                | 1         | 1.2%    |
| C-Media Electronics | 1         | 1.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 10.53%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 5.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 4.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 4.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 3.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 3.16%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 3.16%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 2.11%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 2.11%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 2.11%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 2         | 2.11%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 2         | 2.11%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.11%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.11%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 2.11%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 2.11%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 2.11%   |
| Intel Audio device                                                                                | 2         | 2.11%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 2.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 2.11%   |
| GN Netcom Jabra EVOLVE LINK                                                                       | 2         | 2.11%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 2.11%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 2.11%   |
| Unknown Definitive Sym1                                                                           | 1         | 1.05%   |
| TEAC US-2x2                                                                                       | 1         | 1.05%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.05%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.05%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 1.05%   |
| Nvidia GK110 High Definition Audio Controller                                                     | 1         | 1.05%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 1.05%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 1.05%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                                          | 1         | 1.05%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.05%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.05%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 1.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.05%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 1         | 1.05%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 1.05%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.05%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Micron Technology   | 9         | 26.47%  |
| Samsung Electronics | 7         | 20.59%  |
| SK hynix            | 5         | 14.71%  |
| Kingston            | 4         | 11.76%  |
| Unknown             | 2         | 5.88%   |
| Crucial             | 2         | 5.88%   |
| Smart               | 1         | 2.94%   |
| HPE                 | 1         | 2.94%   |
| Corsair             | 1         | 2.94%   |
| Avant               | 1         | 2.94%   |
| 4ea5                | 1         | 2.94%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s     | 2         | 5.26%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                  | 1         | 2.63%   |
| Unknown RAM Module 4GB DIMM DDR3 800MT/s                     | 1         | 2.63%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s        | 1         | 2.63%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 2.63%   |
| SK hynix RAM HMAA1GS6CMR8N-VK 8GB Row Of Chips DDR4 2667MT/s | 1         | 2.63%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s | 1         | 2.63%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 2.63%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 1         | 2.63%   |
| SK hynix RAM H9HCNNNBKUMLXR-NEE 2GB LPDDR4 2400MT/s          | 1         | 2.63%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 2.63%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s       | 1         | 2.63%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 2.63%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 1         | 2.63%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 2.63%   |
| Micron RAM Module 16384MB SODIMM DDR4 2400MT/s               | 1         | 2.63%   |
| Micron RAM 8ATF1G64AZ-2G3H1 8GB DIMM DDR4 2448MT/s           | 1         | 2.63%   |
| Micron RAM 8ATF1G64AZ-2G3E1 8GB DIMM DDR4 2400MT/s           | 1         | 2.63%   |
| Micron RAM 8ATF1G64AZ-2G3B1 8GB DIMM DDR4 2448MT/s           | 1         | 2.63%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s  | 1         | 2.63%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s         | 1         | 2.63%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s        | 1         | 2.63%   |
| Micron RAM 4ATF1G64AZ-3G2F1 8GB DIMM DDR4 3200MT/s           | 1         | 2.63%   |
| Micron RAM 18ASF2G72PDZ-2G3B1 16GB DIMM DDR4 2400MT/s        | 1         | 2.63%   |
| Micron RAM 16JTF1G64HZ-1G4D1 8GB SODIMM DDR3 1333MT/s        | 1         | 2.63%   |
| Micron RAM 16ATF2G64HZ-2G1A1 16384MB SODIMM DDR4 2133MT/s    | 1         | 2.63%   |
| Kingston RAM KX830D-ELC 4GB SODIMM DDR3 1333MT/s             | 1         | 2.63%   |
| Kingston RAM KTW149-ELF 1GB DIMM DDR3 1333MT/s               | 1         | 2.63%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s             | 1         | 2.63%   |
| Kingston RAM 9905471-006.A00LF 4GB DIMM DDR3 1333MT/s        | 1         | 2.63%   |
| Kingston RAM 9905403-892.A00LF 8GB DIMM DDR3 1333MT/s        | 1         | 2.63%   |
| HPE RAM 840756-091 16GB DIMM DDR4 2666MT/s                   | 1         | 2.63%   |
| Crucial RAM CT16G4SFRA32A.M16FR 16GB SODIMM DDR4 3200MT/s    | 1         | 2.63%   |
| Crucial RAM BLE8G4D34AEEAK.K8FB 8192MB DIMM DDR4 3466MT/s    | 1         | 2.63%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s    | 1         | 2.63%   |
| Avant RAM H6451U66G1600G 4096MB SODIMM DDR3 1600MT/s         | 1         | 2.63%   |
| 4ea5 RAM H9HCNNNBKUMLXR-NEE 2GB LPDDR4 2400MT/s              | 1         | 2.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 19        | 59.38%  |
| DDR3   | 11        | 34.38%  |
| LPDDR4 | 2         | 6.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 20        | 62.5%   |
| DIMM         | 8         | 25%     |
| Row Of Chips | 3         | 9.38%   |
| Unknown      | 1         | 3.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 14        | 42.42%  |
| 16384 | 8         | 24.24%  |
| 4096  | 8         | 24.24%  |
| 32768 | 1         | 3.03%   |
| 2048  | 1         | 3.03%   |
| 1024  | 1         | 3.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 8         | 24.24%  |
| 1600  | 6         | 18.18%  |
| 2400  | 5         | 15.15%  |
| 1333  | 4         | 12.12%  |
| 3200  | 3         | 9.09%   |
| 4267  | 1         | 3.03%   |
| 3466  | 1         | 3.03%   |
| 2666  | 1         | 3.03%   |
| 2448  | 1         | 3.03%   |
| 2133  | 1         | 3.03%   |
| 1866  | 1         | 3.03%   |
| 800   | 1         | 3.03%   |

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
| Chicony Electronics                    | 10        | 29.41%  |
| Logitech                               | 5         | 14.71%  |
| IMC Networks                           | 5         | 14.71%  |
| Suyin                                  | 3         | 8.82%   |
| Realtek Semiconductor                  | 3         | 8.82%   |
| Lite-On Technology                     | 3         | 8.82%   |
| Microdia                               | 2         | 5.88%   |
| Luxvisions Innotech Limited            | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.94%   |
| Acer                                   | 1         | 2.94%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 6         | 17.14%  |
| IMC Networks Integrated Camera                                  | 3         | 8.57%   |
| Realtek Integrated_Webcam_HD                                    | 2         | 5.71%   |
| Microdia Webcam Vitade AF                                       | 2         | 5.71%   |
| Lite-On Integrated Camera                                       | 2         | 5.71%   |
| IMC Networks VGA UVC WebCam                                     | 2         | 5.71%   |
| Chicony Integrated Camera (1280x720@30)                         | 2         | 5.71%   |
| Suyin Integrated_Webcam_HD                                      | 1         | 2.86%   |
| Suyin HP Truevision HD                                          | 1         | 2.86%   |
| Suyin Asus Integrated Webcam                                    | 1         | 2.86%   |
| Realtek EasyCamera                                              | 1         | 2.86%   |
| Luxvisions Innotech Limited EasyCamera 1M                       | 1         | 2.86%   |
| Logitech Webcam C925e                                           | 1         | 2.86%   |
| Logitech Webcam C920-C                                          | 1         | 2.86%   |
| Logitech Webcam C270                                            | 1         | 2.86%   |
| Logitech HD Webcam C615                                         | 1         | 2.86%   |
| Logitech BRIO Ultra HD Webcam                                   | 1         | 2.86%   |
| Lite-On HP HD Camera                                            | 1         | 2.86%   |
| Chicony TOSHIBA Web Camera - HD                                 | 1         | 2.86%   |
| Chicony ThinkPad T490 Webcam                                    | 1         | 2.86%   |
| Chicony Integrated IR Camera                                    | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera | 1         | 2.86%   |
| Acer SunplusIT Integrated Camera                                | 1         | 2.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 50%     |
| Synaptics                  | 6         | 37.5%   |
| Upek                       | 1         | 6.25%   |
| Shenzhen Goodix Technology | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 18.75%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 18.75%  |
| Validity Sensors Synaptics WBDI                                            | 2         | 12.5%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 12.5%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 12.5%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 6.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 6.25%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 6.25%   |
| Unknown                                                                    | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 83.33%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 3         | 50%     |
| Broadcom 58200                                 | 2         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 27        | 44.26%  |
| 1     | 25        | 40.98%  |
| 2     | 7         | 11.48%  |
| 3     | 2         | 3.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 16        | 39.02%  |
| Graphics card            | 5         | 12.2%   |
| Chipcard                 | 5         | 12.2%   |
| Unassigned class         | 3         | 7.32%   |
| Net/wireless             | 3         | 7.32%   |
| Bluetooth                | 3         | 7.32%   |
| Storage                  | 2         | 4.88%   |
| Communication controller | 2         | 4.88%   |
| Card reader              | 2         | 4.88%   |

