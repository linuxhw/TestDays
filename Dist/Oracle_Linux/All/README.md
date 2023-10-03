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

Total: 106

| Vendor     | Model                       | Form-Factor | Probe                                                      | Date         |
|------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP         | 240 G8 Notebook PC          | Notebook    | [6fec1bd640](https://linux-hardware.org/?probe=6fec1bd640) | Sep 11, 2023 |
| Dell       | Latitude 7440               | Notebook    | [47f28d7b00](https://linux-hardware.org/?probe=47f28d7b00) | Sep 04, 2023 |
| Dell       | Latitude 7440               | Notebook    | [27b2ae9d5b](https://linux-hardware.org/?probe=27b2ae9d5b) | Sep 04, 2023 |
| HP         | Pavilion x360 Convertibl... | Convertible | [913e1fef64](https://linux-hardware.org/?probe=913e1fef64) | Aug 23, 2023 |
| Intel      | NUC13ANBi5 N13061-202       | Mini pc     | [0a0fee9565](https://linux-hardware.org/?probe=0a0fee9565) | Aug 17, 2023 |
| HP         | ZBook Fury 16 G9 Mobile ... | Notebook    | [4b7e25150a](https://linux-hardware.org/?probe=4b7e25150a) | Aug 15, 2023 |
| MSI        | P65 Creator 8RE             | Notebook    | [853567f156](https://linux-hardware.org/?probe=853567f156) | Aug 06, 2023 |
| MSI        | P65 Creator 8RE             | Notebook    | [f26344a920](https://linux-hardware.org/?probe=f26344a920) | Aug 05, 2023 |
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

![OS](./images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Oracle Linux 8.5 | 13        | 15.85%  |
| Oracle Linux 8.3 | 12        | 14.63%  |
| Oracle Linux 9.2 | 7         | 8.54%   |
| Oracle Linux 8.4 | 7         | 8.54%   |
| Oracle Linux 8.6 | 6         | 7.32%   |
| Oracle Linux 9.1 | 5         | 6.1%    |
| Oracle Linux 9.0 | 5         | 6.1%    |
| Oracle Linux 8.8 | 5         | 6.1%    |
| Oracle Linux 8.7 | 5         | 6.1%    |
| Oracle Linux 7.9 | 4         | 4.88%   |
| Oracle Linux 8.1 | 3         | 3.66%   |
| Oracle Linux 7.7 | 3         | 3.66%   |
| Oracle Linux 8.2 | 2         | 2.44%   |
| Oracle Linux 7.8 | 2         | 2.44%   |
| Oracle Linux 7.6 | 2         | 2.44%   |
| Oracle Linux 7.4 | 1         | 1.22%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Oracle Linux | 75        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                           | Computers | Percent |
|-----------------------------------|-----------|---------|
| 5.4.17-2102.202.5.el8uek.x86_64   | 3         | 3.41%   |
| 5.4.17-2036.103.3.1.el8uek.x86_64 | 3         | 3.41%   |
| 5.15.0-2.52.3.el9uek.x86_64       | 3         | 3.41%   |
| 5.15.0-101.103.2.1.el9uek.x86_64  | 3         | 3.41%   |
| 5.15.0-100.96.32.el8uek.x86_64    | 3         | 3.41%   |
| 4.18.0-348.12.2.el8_5.x86_64      | 3         | 3.41%   |
| 5.4.17-2136.313.6.el8uek.x86_64   | 2         | 2.27%   |
| 5.4.17-2136.304.4.3.el8uek.x86_64 | 2         | 2.27%   |
| 5.4.17-2136.300.7.el8uek.x86_64   | 2         | 2.27%   |
| 5.4.17-2102.205.7.3.el8uek.x86_64 | 2         | 2.27%   |
| 5.4.17-2102.200.13.el8uek.x86_64  | 2         | 2.27%   |
| 5.4.17-2036.102.0.2.el8uek.x86_64 | 2         | 2.27%   |
| 5.4.17-2036.101.2.el8uek.x86_64   | 2         | 2.27%   |
| 5.15.0-5.76.5.1.el9uek.x86_64     | 2         | 2.27%   |
| 5.15.0-103.114.4.el8uek.x86_64    | 2         | 2.27%   |
| 4.18.0-240.15.1.el8_3.x86_64      | 2         | 2.27%   |
| 4.18.0-193.1.2.el8_2.x86_64       | 2         | 2.27%   |
| 4.18.0-147.3.1.el8_1.x86_64       | 2         | 2.27%   |
| 5.4.17-2136.318.7.2.el8uek.x86_64 | 1         | 1.14%   |
| 5.4.17-2136.312.3.4.el7uek.x86_64 | 1         | 1.14%   |
| 5.4.17-2136.310.7.el8uek.x86_64   | 1         | 1.14%   |
| 5.4.17-2136.310.7.1.el8uek.x86_64 | 1         | 1.14%   |
| 5.4.17-2136.309.4.el8uek.x86_64   | 1         | 1.14%   |
| 5.4.17-2136.308.9.el8uek.x86_64   | 1         | 1.14%   |
| 5.4.17-2136.308.9.el7uek.x86_64   | 1         | 1.14%   |
| 5.4.17-2136.307.3.1.el8uek.x86_64 | 1         | 1.14%   |
| 5.4.17-2136.306.1.3.el8uek.x86_64 | 1         | 1.14%   |
| 5.4.17-2136.305.5.4.el8uek.x86_64 | 1         | 1.14%   |
| 5.4.17-2136.305.5.3.el8uek.x86_64 | 1         | 1.14%   |
| 5.4.17-2136.305.5.2.el8uek.x86_64 | 1         | 1.14%   |
| 5.4.17-2136.301.1.4.el8uek.x86_64 | 1         | 1.14%   |
| 5.4.17-2102.204.4.4.el8uek.x86_64 | 1         | 1.14%   |
| 5.4.17-2102.204.4.2.el8uek.x86_64 | 1         | 1.14%   |
| 5.4.17-2102.201.3.el8uek.x86_64   | 1         | 1.14%   |
| 5.4.17-2036.104.4.el8uek.x86_64   | 1         | 1.14%   |
| 5.4.17-2036.100.6.1.el8uek.x86_64 | 1         | 1.14%   |
| 5.4.17-2011.0.7.el8uek.x86_64     | 1         | 1.14%   |
| 5.4.11-1.el7.elrepo.x86_64        | 1         | 1.14%   |
| 5.15.2-1.el8.elrepo.x86_64        | 1         | 1.14%   |
| 5.15.0-6.80.3.1.el9uek.x86_64     | 1         | 1.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.17  | 29        | 37.66%  |
| 5.15.0  | 20        | 25.97%  |
| 4.18.0  | 12        | 15.58%  |
| 4.14.35 | 5         | 6.49%   |
| 5.14.0  | 3         | 3.9%    |
| 3.10.0  | 3         | 3.9%    |
| 5.4.11  | 1         | 1.3%    |
| 5.15.2  | 1         | 1.3%    |
| 5.14.1  | 1         | 1.3%    |
| 5.11.1  | 1         | 1.3%    |
| 4.1.12  | 1         | 1.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 30        | 38.96%  |
| 5.15    | 21        | 27.27%  |
| 4.18    | 12        | 15.58%  |
| 4.14    | 5         | 6.49%   |
| 5.14    | 4         | 5.19%   |
| 3.10    | 3         | 3.9%    |
| 5.11    | 1         | 1.3%    |
| 4.1     | 1         | 1.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 75        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 58        | 73.42%  |
| Unknown       | 10        | 12.66%  |
| GNOME Classic | 3         | 3.8%    |
| XFCE          | 2         | 2.53%   |
| MATE          | 2         | 2.53%   |
| KDE5          | 2         | 2.53%   |
| KDE4          | 2         | 2.53%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 42        | 54.55%  |
| X11     | 26        | 33.77%  |
| Unknown | 7         | 9.09%   |
| Web     | 1         | 1.3%    |
| Tty     | 1         | 1.3%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 37        | 48.05%  |
| Unknown | 37        | 48.05%  |
| SDDM    | 2         | 2.6%    |
| TDM     | 1         | 1.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 48        | 63.16%  |
| en_GB      | 7         | 9.21%   |
| de_DE      | 4         | 5.26%   |
| Unknown    | 4         | 5.26%   |
| en_AU      | 3         | 3.95%   |
| pl_PL      | 2         | 2.63%   |
| it_IT      | 2         | 2.63%   |
| en_IN      | 2         | 2.63%   |
| zh_HK      | 1         | 1.32%   |
| ru_RU      | 1         | 1.32%   |
| pt_BR      | 1         | 1.32%   |
| en_US.UTF8 | 1         | 1.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 44        | 57.89%  |
| BIOS | 32        | 42.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 66        | 85.71%  |
| Ext4    | 8         | 10.39%  |
| Unknown | 2         | 2.6%    |
| Zfs     | 1         | 1.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 33        | 42.86%  |
| Unknown | 31        | 40.26%  |
| MBR     | 13        | 16.88%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 70        | 92.11%  |
| Yes       | 6         | 7.89%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 71        | 94.67%  |
| Yes       | 4         | 5.33%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 21        | 28%     |
| Dell                | 14        | 18.67%  |
| Hewlett-Packard     | 11        | 14.67%  |
| ASUSTek Computer    | 8         | 10.67%  |
| Intel               | 4         | 5.33%   |
| Gigabyte Technology | 4         | 5.33%   |
| MSI                 | 2         | 2.67%   |
| Supermicro          | 1         | 1.33%   |
| Standard            | 1         | 1.33%   |
| Panasonic           | 1         | 1.33%   |
| HPE                 | 1         | 1.33%   |
| Google              | 1         | 1.33%   |
| Fujitsu             | 1         | 1.33%   |
| Foxconn             | 1         | 1.33%   |
| Dynabook            | 1         | 1.33%   |
| Cisco               | 1         | 1.33%   |
| ASRock              | 1         | 1.33%   |
| Apple               | 1         | 1.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Lenovo ThinkPad T450 20BUS14900           | 2         | 2.67%   |
| ASUS X510UR                               | 2         | 2.67%   |
| Supermicro X8DTU                          | 1         | 1.33%   |
| Standard BW Series                        | 1         | 1.33%   |
| Panasonic CF-53AAG54FM                    | 1         | 1.33%   |
| MSI P65 Creator 8RE                       | 1         | 1.33%   |
| MSI MS-7758                               | 1         | 1.33%   |
| Lenovo ThinkPad X390 Yoga 20NQS2SF00      | 1         | 1.33%   |
| Lenovo ThinkPad X280 20KES4H34G           | 1         | 1.33%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QWS1R800 | 1         | 1.33%   |
| Lenovo ThinkPad W541 20EGS1PL00           | 1         | 1.33%   |
| Lenovo ThinkPad T490 20N3S77600           | 1         | 1.33%   |
| Lenovo ThinkPad T490 20N3S3XR00           | 1         | 1.33%   |
| Lenovo ThinkPad T480 20L6S56Y2X           | 1         | 1.33%   |
| Lenovo ThinkPad T480 20L5A07TAU           | 1         | 1.33%   |
| Lenovo ThinkPad T470 20HES21434           | 1         | 1.33%   |
| Lenovo ThinkPad T470 20HES0E71M           | 1         | 1.33%   |
| Lenovo ThinkPad T430s 2355C33             | 1         | 1.33%   |
| Lenovo ThinkPad P70 20ESS04S00            | 1         | 1.33%   |
| Lenovo ThinkPad P50s 20FL000MUS           | 1         | 1.33%   |
| Lenovo ThinkPad L540 20AVCTO1WW           | 1         | 1.33%   |
| Lenovo ThinkPad L490 20Q5CTO1WW           | 1         | 1.33%   |
| Lenovo Legion 5 15IMH05 82AU              | 1         | 1.33%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS       | 1         | 1.33%   |
| Lenovo IdeaPad C340-14IWL 81RL            | 1         | 1.33%   |
| Lenovo IdeaPad 300-15ISK 80RS             | 1         | 1.33%   |
| Intel NUC6CAYH                            | 1         | 1.33%   |
| Intel NUC13ANHi5                          | 1         | 1.33%   |
| Intel NUC12WSHi7                          | 1         | 1.33%   |
| Intel NUC12WSHi5                          | 1         | 1.33%   |
| HPE ProLiant BL460c Gen10                 | 1         | 1.33%   |
| HP ZBook Fury 16 G9 Mobile Workstation PC | 1         | 1.33%   |
| HP ZBook 15                               | 1         | 1.33%   |
| HP Z820 Workstation                       | 1         | 1.33%   |
| HP Z420 Workstation                       | 1         | 1.33%   |
| HP ProBook 445 G6                         | 1         | 1.33%   |
| HP Pavilion x360 Convertible 14-dy0xxx    | 1         | 1.33%   |
| HP Notebook                               | 1         | 1.33%   |
| HP Laptop 17-cp0xxx                       | 1         | 1.33%   |
| HP EliteBook 840 G5                       | 1         | 1.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 17        | 22.67%  |
| Dell Latitude          | 5         | 6.67%   |
| Dell OptiPlex          | 4         | 5.33%   |
| Lenovo IdeaPad         | 3         | 4%      |
| HP ZBook               | 2         | 2.67%   |
| Dell Precision         | 2         | 2.67%   |
| Dell Inspiron          | 2         | 2.67%   |
| ASUS X510UR            | 2         | 2.67%   |
| Supermicro X8DTU       | 1         | 1.33%   |
| Standard BW            | 1         | 1.33%   |
| Panasonic CF-53AAG54FM | 1         | 1.33%   |
| MSI P65                | 1         | 1.33%   |
| MSI MS-7758            | 1         | 1.33%   |
| Lenovo Legion          | 1         | 1.33%   |
| Intel NUC6CAYH         | 1         | 1.33%   |
| Intel NUC13ANHi5       | 1         | 1.33%   |
| Intel NUC12WSHi7       | 1         | 1.33%   |
| Intel NUC12WSHi5       | 1         | 1.33%   |
| HPE ProLiant           | 1         | 1.33%   |
| HP Z820                | 1         | 1.33%   |
| HP Z420                | 1         | 1.33%   |
| HP ProBook             | 1         | 1.33%   |
| HP Pavilion            | 1         | 1.33%   |
| HP Notebook            | 1         | 1.33%   |
| HP Laptop              | 1         | 1.33%   |
| HP EliteBook           | 1         | 1.33%   |
| HP Compaq              | 1         | 1.33%   |
| HP 240                 | 1         | 1.33%   |
| Google Lick            | 1         | 1.33%   |
| Gigabyte Z490          | 1         | 1.33%   |
| Gigabyte X99-Designare | 1         | 1.33%   |
| Gigabyte X470          | 1         | 1.33%   |
| Gigabyte H81M-S2PV     | 1         | 1.33%   |
| Fujitsu PRIMERGY       | 1         | 1.33%   |
| Foxconn p6-2400el      | 1         | 1.33%   |
| Dynabook PORTEGE       | 1         | 1.33%   |
| Dell PowerEdge         | 1         | 1.33%   |
| Cisco WAVE-694-K9      | 1         | 1.33%   |
| ASUS ZenBook           | 1         | 1.33%   |
| ASUS UX305FA           | 1         | 1.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 10        | 13.33%  |
| 2018 | 8         | 10.67%  |
| 2022 | 6         | 8%      |
| 2021 | 6         | 8%      |
| 2020 | 6         | 8%      |
| 2016 | 6         | 8%      |
| 2014 | 6         | 8%      |
| 2012 | 6         | 8%      |
| 2017 | 4         | 5.33%   |
| 2011 | 4         | 5.33%   |
| 2015 | 3         | 4%      |
| 2013 | 3         | 4%      |
| 2010 | 3         | 4%      |
| 2023 | 2         | 2.67%   |
| 2009 | 1         | 1.33%   |
| 2008 | 1         | 1.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 45        | 60%     |
| Desktop     | 19        | 25.33%  |
| Mini pc     | 5         | 6.67%   |
| Convertible | 3         | 4%      |
| Server      | 3         | 4%      |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 65        | 85.53%  |
| Enabled  | 11        | 14.47%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 74        | 98.67%  |
| Yes  | 1         | 1.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 22        | 28.95%  |
| 32.01-64.0      | 17        | 22.37%  |
| 4.01-8.0        | 12        | 15.79%  |
| 64.01-256.0     | 7         | 9.21%   |
| 3.01-4.0        | 6         | 7.89%   |
| 16.01-24.0      | 6         | 7.89%   |
| 24.01-32.0      | 4         | 5.26%   |
| More than 256.0 | 1         | 1.32%   |
| 1.01-2.0        | 1         | 1.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 25        | 30.12%  |
| 2.01-3.0    | 20        | 24.1%   |
| 3.01-4.0    | 13        | 15.66%  |
| 1.01-2.0    | 9         | 10.84%  |
| 8.01-16.0   | 9         | 10.84%  |
| 0.51-1.0    | 3         | 3.61%   |
| 24.01-32.0  | 1         | 1.2%    |
| 64.01-256.0 | 1         | 1.2%    |
| 16.01-24.0  | 1         | 1.2%    |
| 0.01-0.5    | 1         | 1.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 55        | 72.37%  |
| 2      | 14        | 18.42%  |
| 3      | 3         | 3.95%   |
| 4      | 2         | 2.63%   |
| 6      | 1         | 1.32%   |
| 5      | 1         | 1.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 60        | 80%     |
| Yes       | 15        | 20%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 84%     |
| No        | 12        | 16%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 77.33%  |
| No        | 17        | 22.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 59.21%  |
| No        | 31        | 40.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 24        | 31.58%  |
| Germany     | 8         | 10.53%  |
| UK          | 4         | 5.26%   |
| Poland      | 4         | 5.26%   |
| Brazil      | 4         | 5.26%   |
| Australia   | 4         | 5.26%   |
| Netherlands | 3         | 3.95%   |
| Finland     | 3         | 3.95%   |
| Russia      | 2         | 2.63%   |
| Romania     | 2         | 2.63%   |
| Italy       | 2         | 2.63%   |
| India       | 2         | 2.63%   |
| Yemen       | 1         | 1.32%   |
| Turkey      | 1         | 1.32%   |
| Sweden      | 1         | 1.32%   |
| Spain       | 1         | 1.32%   |
| Slovakia    | 1         | 1.32%   |
| Pakistan    | 1         | 1.32%   |
| Nigeria     | 1         | 1.32%   |
| Latvia      | 1         | 1.32%   |
| Kazakhstan  | 1         | 1.32%   |
| Hungary     | 1         | 1.32%   |
| Hong Kong   | 1         | 1.32%   |
| Bulgaria    | 1         | 1.32%   |
| Bolivia     | 1         | 1.32%   |
| Argentina   | 1         | 1.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| San Diego          | 3         | 3.7%    |
| Helsinki           | 3         | 3.7%    |
| Siegen             | 2         | 2.47%   |
| Seattle            | 2         | 2.47%   |
| Sao Paulo          | 2         | 2.47%   |
| Colorado Springs   | 2         | 2.47%   |
| Bucharest          | 2         | 2.47%   |
| Berlin             | 2         | 2.47%   |
| Amsterdam          | 2         | 2.47%   |
| Zavar              | 1         | 1.23%   |
| Weaverville        | 1         | 1.23%   |
| Warsaw             | 1         | 1.23%   |
| Veliky Novgorod    | 1         | 1.23%   |
| Valmiera           | 1         | 1.23%   |
| Utrecht            | 1         | 1.23%   |
| Turner             | 1         | 1.23%   |
| Sydney             | 1         | 1.23%   |
| Stockholm          | 1         | 1.23%   |
| Sofia              | 1         | 1.23%   |
| Shrewsbury         | 1         | 1.23%   |
| Sao Caetano do Sul | 1         | 1.23%   |
| Santa Cruz         | 1         | 1.23%   |
| Sanaa              | 1         | 1.23%   |
| San Francisco      | 1         | 1.23%   |
| Rocklin            | 1         | 1.23%   |
| Riverside          | 1         | 1.23%   |
| Redwood City       | 1         | 1.23%   |
| Reading            | 1         | 1.23%   |
| Port Saint Lucie   | 1         | 1.23%   |
| Pleven             | 1         | 1.23%   |
| Petersberg         | 1         | 1.23%   |
| Perugia            | 1         | 1.23%   |
| Parker             | 1         | 1.23%   |
| Ngau Wu Tok        | 1         | 1.23%   |
| Neunkirchen        | 1         | 1.23%   |
| Nagercoil          | 1         | 1.23%   |
| Moscow             | 1         | 1.23%   |
| Melbourne          | 1         | 1.23%   |
| Maple Valley       | 1         | 1.23%   |
| Madrid             | 1         | 1.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 24        | 30     | 24.74%  |
| Seagate                   | 12        | 50     | 12.37%  |
| SanDisk                   | 8         | 11     | 8.25%   |
| WDC                       | 7         | 8      | 7.22%   |
| Unknown                   | 5         | 7      | 5.15%   |
| Toshiba                   | 4         | 4      | 4.12%   |
| Intel                     | 4         | 4      | 4.12%   |
| Crucial                   | 4         | 5      | 4.12%   |
| SK hynix                  | 3         | 3      | 3.09%   |
| Phison Electronics        | 3         | 3      | 3.09%   |
| Micron Technology         | 3         | 6      | 3.09%   |
| Kingston                  | 3         | 10     | 3.09%   |
| HGST                      | 3         | 6      | 3.09%   |
| Hewlett-Packard           | 2         | 2      | 2.06%   |
| Union Memory (Shenzhen)   | 1         | 2      | 1.03%   |
| Transcend                 | 1         | 1      | 1.03%   |
| Phison                    | 1         | 1      | 1.03%   |
| Micron/Crucial Technology | 1         | 1      | 1.03%   |
| Lite-On                   | 1         | 1      | 1.03%   |
| Lenovo                    | 1         | 1      | 1.03%   |
| KIOXIA                    | 1         | 1      | 1.03%   |
| JMicron Technology        | 1         | 1      | 1.03%   |
| HPE                       | 1         | 1      | 1.03%   |
| GOODRAM                   | 1         | 1      | 1.03%   |
| Fujitsu                   | 1         | 1      | 1.03%   |
| Apple                     | 1         | 1      | 1.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Unknown SD/MMC/MS PRO 128GB                  | 2         | 1.94%   |
| Seagate ST2000DM008-2FR102 2TB               | 2         | 1.94%   |
| SanDisk SSD PLUS 1000GB                      | 2         | 1.94%   |
| Samsung SSD PM830 2.5 7mm 256GB              | 2         | 1.94%   |
| Samsung MZVLB512HAJQ-000L7 512GB             | 2         | 1.94%   |
| Samsung MZ7LN512HMJP-000L7 512GB SSD         | 2         | 1.94%   |
| Phison E12 NVMe Controller 2TB               | 2         | 1.94%   |
| Kingston SA400S37240G 240GB SSD              | 2         | 1.94%   |
| Intel SSD 660P Series 1024GB                 | 2         | 1.94%   |
| Crucial CT500MX500SSD1 500GB                 | 2         | 1.94%   |
| WDC WDS500G2B0A-00SM50 500GB SSD             | 1         | 0.97%   |
| WDC WDS250G2B0A-00SM50 250GB SSD             | 1         | 0.97%   |
| WDC WD3200BEKT-08PVMT1 320GB                 | 1         | 0.97%   |
| WDC WD1600YS-23SHB0 160GB                    | 1         | 0.97%   |
| WDC WD10SPZX-60Z10T1 1TB                     | 1         | 0.97%   |
| WDC WD10JPCX-24UE4T0 1TB                     | 1         | 0.97%   |
| WDC WD10EZEX-60M2NA0 1TB                     | 1         | 0.97%   |
| Unknown MMC64G  64GB                         | 1         | 0.97%   |
| Unknown MMC Card  256GB                      | 1         | 0.97%   |
| Unknown MMC Card  1TB                        | 1         | 0.97%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 0.97%   |
| Transcend TS2TMTE250H 2TB                    | 1         | 0.97%   |
| Toshiba THNSNJ512GCSU 512GB SSD              | 1         | 0.97%   |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 0.97%   |
| Toshiba MG04ACA200E 2TB                      | 1         | 0.97%   |
| Toshiba DT01ACA050 500GB                     | 1         | 0.97%   |
| SK hynix SKHynix_HFS256GD9TNG-L3A0B 256GB    | 1         | 0.97%   |
| SK hynix PC801 NVMe 512GB                    | 1         | 0.97%   |
| SK hynix BC901 NVMe 512GB                    | 1         | 0.97%   |
| Seagate ST9750420AS 752GB                    | 1         | 0.97%   |
| Seagate ST8000VN004-2M2101 8TB               | 1         | 0.97%   |
| Seagate ST3750528AS 752GB                    | 1         | 0.97%   |
| Seagate ST3500414CS 500GB                    | 1         | 0.97%   |
| Seagate ST2000NX0253 2TB                     | 1         | 0.97%   |
| Seagate ST2000DM001-1ER164 2TB               | 1         | 0.97%   |
| Seagate ST1000VX000-1ES162 1TB               | 1         | 0.97%   |
| Seagate ST1000NX0423 1TB                     | 1         | 0.97%   |
| Seagate ST1000LX015-1U7172 1TB               | 1         | 0.97%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 0.97%   |
| Seagate ST1000LM010-9YH146 1TB               | 1         | 0.97%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 50     | 41.38%  |
| WDC                 | 5         | 6      | 17.24%  |
| HGST                | 3         | 6      | 10.34%  |
| Unknown             | 2         | 4      | 6.9%    |
| Toshiba             | 2         | 2      | 6.9%    |
| Samsung Electronics | 2         | 2      | 6.9%    |
| JMicron Technology  | 1         | 1      | 3.45%   |
| Fujitsu             | 1         | 1      | 3.45%   |
| Apple               | 1         | 1      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 16     | 40.63%  |
| SanDisk             | 6         | 8      | 18.75%  |
| Crucial             | 3         | 4      | 9.38%   |
| WDC                 | 2         | 2      | 6.25%   |
| Kingston            | 2         | 3      | 6.25%   |
| Hewlett-Packard     | 2         | 2      | 6.25%   |
| Toshiba             | 1         | 1      | 3.13%   |
| Intel               | 1         | 1      | 3.13%   |
| HPE                 | 1         | 1      | 3.13%   |
| GOODRAM             | 1         | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 33        | 47     | 35.87%  |
| SSD  | 30        | 39     | 32.61%  |
| HDD  | 26        | 73     | 28.26%  |
| MMC  | 3         | 3      | 3.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 46        | 105    | 53.49%  |
| NVMe | 33        | 47     | 38.37%  |
| SAS  | 4         | 7      | 4.65%   |
| MMC  | 3         | 3      | 3.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 25        | 33     | 44.64%  |
| 0.51-1.0   | 23        | 32     | 41.07%  |
| 1.01-2.0   | 7         | 45     | 12.5%   |
| 4.01-10.0  | 1         | 2      | 1.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 20        | 26.32%  |
| 101-250        | 14        | 18.42%  |
| 501-1000       | 13        | 17.11%  |
| 1-20           | 7         | 9.21%   |
| Unknown        | 7         | 9.21%   |
| 51-100         | 5         | 6.58%   |
| 1001-2000      | 4         | 5.26%   |
| 2001-3000      | 3         | 3.95%   |
| 21-50          | 2         | 2.63%   |
| More than 3000 | 1         | 1.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 26        | 33.33%  |
| 21-50          | 18        | 23.08%  |
| 51-100         | 11        | 14.1%   |
| 101-250        | 8         | 10.26%  |
| Unknown        | 7         | 8.97%   |
| 251-500        | 4         | 5.13%   |
| 501-1000       | 2         | 2.56%   |
| More than 3000 | 1         | 1.28%   |
| 1001-2000      | 1         | 1.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST9750420AS 752GB                        | 1         | 1      | 20%     |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 20%     |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 20%     |
| Samsung Electronics HD753LJ 752GB                | 1         | 1      | 20%     |
| Hewlett-Packard SSD S700 120GB                   | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 40%     |
| Samsung Electronics | 2         | 2      | 40%     |
| Hewlett-Packard     | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 66.67%  |
| Samsung Electronics | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 60%     |
| SSD  | 2         | 2      | 40%     |

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
| Works    | 39        | 87     | 48.15%  |
| Detected | 37        | 70     | 45.68%  |
| Malfunc  | 5         | 5      | 6.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 49        | 54.44%  |
| Samsung Electronics          | 10        | 11.11%  |
| AMD                          | 5         | 5.56%   |
| Phison Electronics           | 4         | 4.44%   |
| SK hynix                     | 3         | 3.33%   |
| Micron Technology            | 3         | 3.33%   |
| Broadcom / LSI               | 3         | 3.33%   |
| Sandisk                      | 2         | 2.22%   |
| Micron/Crucial Technology    | 2         | 2.22%   |
| VIA Technologies             | 1         | 1.11%   |
| Union Memory (Shenzhen)      | 1         | 1.11%   |
| Transcend                    | 1         | 1.11%   |
| Toshiba America Info Systems | 1         | 1.11%   |
| Lite-On Technology           | 1         | 1.11%   |
| Lenovo                       | 1         | 1.11%   |
| KIOXIA                       | 1         | 1.11%   |
| Kingston Technology Company  | 1         | 1.11%   |
| Adaptec                      | 1         | 1.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6         | 5.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 4.9%    |
| AMD FCH SATA Controller [AHCI mode]                                                     | 5         | 4.9%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 3.92%   |
| Phison E12 NVMe Controller                                                              | 3         | 2.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 2.94%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 2.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 1.96%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 2         | 1.96%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 1.96%   |
| Intel SSD 660P Series                                                                   | 2         | 1.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 1.96%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2         | 1.96%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2         | 1.96%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2         | 1.96%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2         | 1.96%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2         | 1.96%   |
| Intel Alder Lake-P SATA AHCI Controller                                                 | 2         | 1.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.96%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2         | 1.96%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1         | 0.98%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 NVMe SSD 128GB                                   | 1         | 0.98%   |
| Transcend NVMe PCIe SSD 250H                                                            | 1         | 0.98%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 1         | 0.98%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                      | 1         | 0.98%   |
| SK hynix PC601 NVMe Solid State Drive                                                   | 1         | 0.98%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                                       | 1         | 0.98%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1         | 0.98%   |
| Sandisk PC SN740 NVMe SSD (DRAM-less)                                                   | 1         | 0.98%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.98%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                             | 1         | 0.98%   |
| Micron 2300 NVMe SSD [Santana]                                                          | 1         | 0.98%   |
| Micron 2200S NVMe SSD [Cassandra]                                                       | 1         | 0.98%   |
| Lite-On Non-Volatile memory controller                                                  | 1         | 0.98%   |
| Lenovo LENSE30512GMSP34MEAT3TA                                                          | 1         | 0.98%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 1         | 0.98%   |
| Kingston Company A2000 NVMe SSD                                                         | 1         | 0.98%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 42        | 45.16%  |
| NVMe | 33        | 35.48%  |
| RAID | 9         | 9.68%   |
| IDE  | 5         | 5.38%   |
| SAS  | 3         | 3.23%   |
| SCSI | 1         | 1.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 70        | 93.33%  |
| AMD    | 5         | 6.67%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8665U CPU @ 1.90GHz       | 3         | 4%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 3         | 4%      |
| Intel Core i7-7500U CPU @ 2.70GHz       | 2         | 2.67%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 2         | 2.67%   |
| Intel Core i7-10610U CPU @ 1.80GHz      | 2         | 2.67%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 2         | 2.67%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 2         | 2.67%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 2         | 2.67%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 2         | 2.67%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz    | 1         | 1.33%   |
| Intel Xeon CPU X3450 @ 2.67GHz          | 1         | 1.33%   |
| Intel Xeon CPU X3430 @ 2.40GHz          | 1         | 1.33%   |
| Intel Xeon CPU E5649 @ 2.53GHz          | 1         | 1.33%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz     | 1         | 1.33%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz     | 1         | 1.33%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz     | 1         | 1.33%   |
| Intel Processor 5Y10 CPU @ 0.80GHz      | 1         | 1.33%   |
| Intel Pentium CPU G3240 @ 3.10GHz       | 1         | 1.33%   |
| Intel Pentium CPU G2020 @ 2.90GHz       | 1         | 1.33%   |
| Intel Core i9-9880H CPU @ 2.30GHz       | 1         | 1.33%   |
| Intel Core i9-10900K CPU @ 3.70GHz      | 1         | 1.33%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 1         | 1.33%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 1         | 1.33%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 1         | 1.33%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1.33%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1.33%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 1         | 1.33%   |
| Intel Core i7-6800K CPU @ 3.40GHz       | 1         | 1.33%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 1         | 1.33%   |
| Intel Core i7-4940MX CPU @ 3.10GHz      | 1         | 1.33%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz      | 1         | 1.33%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz      | 1         | 1.33%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 1         | 1.33%   |
| Intel Core i7-2860QM CPU @ 2.50GHz      | 1         | 1.33%   |
| Intel Core i7-2760QM CPU @ 2.40GHz      | 1         | 1.33%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 1         | 1.33%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.33%   |
| Intel Core i7-10700K CPU @ 3.80GHz      | 1         | 1.33%   |
| Intel Core i5-8365U CPU @ 1.60GHz       | 1         | 1.33%   |
| Intel Core i5-4460 CPU @ 3.20GHz        | 1         | 1.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i7     | 26        | 34.67%  |
| Intel Core i5     | 14        | 18.67%  |
| Other             | 13        | 17.33%  |
| Intel Xeon        | 6         | 8%      |
| Intel Celeron     | 4         | 5.33%   |
| Intel Pentium     | 2         | 2.67%   |
| Intel Core i9     | 2         | 2.67%   |
| Intel Core i3     | 2         | 2.67%   |
| AMD Ryzen 7       | 2         | 2.67%   |
| Intel Xeon Silver | 1         | 1.33%   |
| Intel Core 2 Duo  | 1         | 1.33%   |
| AMD Ryzen 7 PRO   | 1         | 1.33%   |
| AMD A8            | 1         | 1.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 29        | 38.67%  |
| 2      | 23        | 30.67%  |
| 12     | 6         | 8%      |
| 6      | 5         | 6.67%   |
| 8      | 4         | 5.33%   |
| 16     | 3         | 4%      |
| 10     | 2         | 2.67%   |
| 20     | 1         | 1.33%   |
| 14     | 1         | 1.33%   |
| 1      | 1         | 1.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 71        | 94.67%  |
| 2      | 4         | 5.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 60        | 80%     |
| 1      | 15        | 20%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 74        | 97.37%  |
| Unknown        | 2         | 2.63%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ec    | 7         | 9.33%   |
| 0x306c3    | 6         | 8%      |
| 0x206a7    | 5         | 6.67%   |
| Unknown    | 5         | 6.67%   |
| 0x806ea    | 4         | 5.33%   |
| 0x806c1    | 4         | 5.33%   |
| 0x906a3    | 3         | 4%      |
| 0x306d4    | 3         | 4%      |
| 0x306a9    | 3         | 4%      |
| 0xb06a2    | 2         | 2.67%   |
| 0xa0655    | 2         | 2.67%   |
| 0x906ea    | 2         | 2.67%   |
| 0x806e9    | 2         | 2.67%   |
| 0x506e3    | 2         | 2.67%   |
| 0x406e3    | 2         | 2.67%   |
| 0x40651    | 2         | 2.67%   |
| 0x306e4    | 2         | 2.67%   |
| 0x106e5    | 2         | 2.67%   |
| 0xa0653    | 1         | 1.33%   |
| 0xa0652    | 1         | 1.33%   |
| 0x906ed    | 1         | 1.33%   |
| 0x90672    | 1         | 1.33%   |
| 0x706a8    | 1         | 1.33%   |
| 0x506c9    | 1         | 1.33%   |
| 0x50654    | 1         | 1.33%   |
| 0x406f1    | 1         | 1.33%   |
| 0x406c4    | 1         | 1.33%   |
| 0x206c2    | 1         | 1.33%   |
| 0x20655    | 1         | 1.33%   |
| 0x10676    | 1         | 1.33%   |
| 0x08608103 | 1         | 1.33%   |
| 0x0810100b | 1         | 1.33%   |
| 0x0800820d | 1         | 1.33%   |
| 0x07030105 | 1         | 1.33%   |
| 0x06006705 | 1         | 1.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 18        | 24%     |
| Haswell          | 8         | 10.67%  |
| Skylake          | 5         | 6.67%   |
| SandyBridge      | 5         | 6.67%   |
| IvyBridge        | 5         | 6.67%   |
| Broadwell        | 5         | 6.67%   |
| TigerLake        | 4         | 5.33%   |
| CometLake        | 4         | 5.33%   |
| Alderlake Hybrid | 4         | 5.33%   |
| Unknown          | 4         | 5.33%   |
| Westmere         | 2         | 2.67%   |
| Nehalem          | 2         | 2.67%   |
| Goldmont plus    | 2         | 2.67%   |
| Zen+             | 1         | 1.33%   |
| Zen              | 1         | 1.33%   |
| Silvermont       | 1         | 1.33%   |
| Puma             | 1         | 1.33%   |
| Penryn           | 1         | 1.33%   |
| Goldmont         | 1         | 1.33%   |
| Excavator        | 1         | 1.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 54        | 59.34%  |
| Nvidia                     | 23        | 25.27%  |
| AMD                        | 10        | 10.99%  |
| Matrox Electronics Systems | 4         | 4.4%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 5         | 5.49%   |
| Intel UHD Graphics 620                                                      | 4         | 4.4%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 4.4%    |
| Intel HD Graphics 620                                                       | 4         | 4.4%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 4         | 4.4%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3         | 3.3%    |
| Intel Alder Lake-P Integrated Graphics Controller                           | 3         | 3.3%    |
| Nvidia GM108M [GeForce 930MX]                                               | 2         | 2.2%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 2         | 2.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 2.2%    |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 2.2%    |
| Intel HD Graphics 5500                                                      | 2         | 2.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 2.2%    |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 2.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 2         | 2.2%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2         | 2.2%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 1.1%    |
| Nvidia TU117M                                                               | 1         | 1.1%    |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1         | 1.1%    |
| Nvidia GP107M [GeForce MX350]                                               | 1         | 1.1%    |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1         | 1.1%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                     | 1         | 1.1%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 1.1%    |
| Nvidia GM204GLM [Quadro M4000M]                                             | 1         | 1.1%    |
| Nvidia GM204 [GeForce GTX 980]                                              | 1         | 1.1%    |
| Nvidia GM108GLM [Quadro K620M / Quadro M500M]                               | 1         | 1.1%    |
| Nvidia GK208GLM [Quadro K610M]                                              | 1         | 1.1%    |
| Nvidia GK208B [GeForce GT 710]                                              | 1         | 1.1%    |
| Nvidia GK110GL [Quadro K6000]                                               | 1         | 1.1%    |
| Nvidia GK107GLM [Quadro K1100M]                                             | 1         | 1.1%    |
| Nvidia GK107GL [Quadro K2000]                                               | 1         | 1.1%    |
| Nvidia GF119M [NVS 4200M]                                                   | 1         | 1.1%    |
| Nvidia GA107GLM [RTX A1000 Laptop GPU]                                      | 1         | 1.1%    |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 1         | 1.1%    |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1         | 1.1%    |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 1         | 1.1%    |
| Matrox Electronics Systems MGA G200eH3                                      | 1         | 1.1%    |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)           | 1         | 1.1%    |
| Matrox Electronics Systems G200eR2                                          | 1         | 1.1%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1         | 1.1%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 37        | 48.68%  |
| 1 x Nvidia     | 12        | 15.79%  |
| Intel + Nvidia | 11        | 14.47%  |
| 1 x AMD        | 6         | 7.89%   |
| 1 x Matrox     | 4         | 5.26%   |
| Intel + AMD    | 3         | 3.95%   |
| Other          | 2         | 2.63%   |
| AMD + Nvidia   | 1         | 1.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 63        | 81.82%  |
| Unknown     | 8         | 10.39%  |
| Proprietary | 6         | 7.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 46        | 60.53%  |
| 1.01-2.0   | 12        | 15.79%  |
| 3.01-4.0   | 10        | 13.16%  |
| 0.51-1.0   | 3         | 3.95%   |
| 0.01-0.5   | 3         | 3.95%   |
| 5.01-6.0   | 1         | 1.32%   |
| 8.01-16.0  | 1         | 1.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 13        | 14.13%  |
| Chimei Innolux       | 11        | 11.96%  |
| Samsung Electronics  | 10        | 10.87%  |
| LG Display           | 9         | 9.78%   |
| Dell                 | 8         | 8.7%    |
| BOE                  | 7         | 7.61%   |
| Lenovo               | 4         | 4.35%   |
| BenQ                 | 4         | 4.35%   |
| ViewSonic            | 3         | 3.26%   |
| InfoVision           | 3         | 3.26%   |
| Hewlett-Packard      | 3         | 3.26%   |
| Acer                 | 3         | 3.26%   |
| ASUSTek Computer     | 2         | 2.17%   |
| Vizio                | 1         | 1.09%   |
| Viotek               | 1         | 1.09%   |
| Sony                 | 1         | 1.09%   |
| Sceptre Tech         | 1         | 1.09%   |
| SAC                  | 1         | 1.09%   |
| Panasonic            | 1         | 1.09%   |
| Goldstar             | 1         | 1.09%   |
| GameMax              | 1         | 1.09%   |
| Element              | 1         | 1.09%   |
| Eizo                 | 1         | 1.09%   |
| BOE Technology Group | 1         | 1.09%   |
| Ancor Communications | 1         | 1.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 3.09%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 2         | 2.06%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 2         | 2.06%   |
| Dell U2718Q DELA0E9 3840x2160 609x349mm 27.6-inch                     | 2         | 2.06%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 2         | 2.06%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 2         | 2.06%   |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                     | 2         | 2.06%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch         | 2         | 2.06%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 2         | 2.06%   |
| Acer SA230 ACR057E 1920x1080 509x286mm 23.0-inch                      | 2         | 2.06%   |
| Vizio V405-H9 VIZ1039 3840x2160 878x485mm 39.5-inch                   | 1         | 1.03%   |
| Viotek SUW49C VTK4900 3840x1080 1196x336mm 48.9-inch                  | 1         | 1.03%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 600x340mm 27.2-inch         | 1         | 1.03%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch              | 1         | 1.03%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 521x293mm 23.5-inch         | 1         | 1.03%   |
| Sony TV SNY4502 1920x1080                                             | 1         | 1.03%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x291mm 29.5-inch        | 1         | 1.03%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch   | 1         | 1.03%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch  | 1         | 1.03%   |
| Samsung Electronics SAMTRON STN0022 1280x1024 380x300mm 19.1-inch     | 1         | 1.03%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch     | 1         | 1.03%   |
| Samsung Electronics S27D391 SAM0B89 1920x1080 598x336mm 27.0-inch     | 1         | 1.03%   |
| Samsung Electronics S27D391 SAM0B88 1920x1080 598x336mm 27.0-inch     | 1         | 1.03%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 1.03%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch     | 1         | 1.03%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SDC3256 1920x1080 382x215mm 17.3-inch | 1         | 1.03%   |
| Samsung Electronics LCD Monitor S24C650                               | 1         | 1.03%   |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 697x392mm 31.5-inch     | 1         | 1.03%   |
| SAC DM-MONB2205 SAC952D 1920x1080 450x270mm 20.7-inch                 | 1         | 1.03%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                    | 1         | 1.03%   |
| LG Display LCD Monitor LGD0628 1920x1080 309x174mm 14.0-inch          | 1         | 1.03%   |
| LG Display LCD Monitor LGD0609 1920x1080 309x174mm 14.0-inch          | 1         | 1.03%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch           | 1         | 1.03%   |
| LG Display LCD Monitor LGD047C 1366x768 310x174mm 14.0-inch           | 1         | 1.03%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 1.03%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 1         | 1.03%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch          | 1         | 1.03%   |
| Lenovo T24i-10 LEN61A6 1920x1080 527x296mm 23.8-inch                  | 1         | 1.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 44        | 56.41%  |
| 3840x2160 (4K)     | 6         | 7.69%   |
| 1366x768 (WXGA)    | 6         | 7.69%   |
| 1920x1200 (WUXGA)  | 4         | 5.13%   |
| 1600x900 (HD+)     | 4         | 5.13%   |
| 1280x1024 (SXGA)   | 3         | 3.85%   |
| 2560x1440 (QHD)    | 2         | 2.56%   |
| 1680x1050 (WSXGA+) | 2         | 2.56%   |
| 3840x1200          | 1         | 1.28%   |
| 3840x1080          | 1         | 1.28%   |
| 2560x1080          | 1         | 1.28%   |
| 1920x540           | 1         | 1.28%   |
| 1360x768           | 1         | 1.28%   |
| 1280x800 (WXGA)    | 1         | 1.28%   |
| Unknown            | 1         | 1.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 16        | 17.2%   |
| 14      | 14        | 15.05%  |
| 27      | 10        | 10.75%  |
| 13      | 10        | 10.75%  |
| 24      | 9         | 9.68%   |
| 23      | 6         | 6.45%   |
| Unknown | 4         | 4.3%    |
| 21      | 3         | 3.23%   |
| 38      | 2         | 2.15%   |
| 31      | 2         | 2.15%   |
| 19      | 2         | 2.15%   |
| 17      | 2         | 2.15%   |
| 84      | 1         | 1.08%   |
| 72      | 1         | 1.08%   |
| 69      | 1         | 1.08%   |
| 48      | 1         | 1.08%   |
| 32      | 1         | 1.08%   |
| 29      | 1         | 1.08%   |
| 25      | 1         | 1.08%   |
| 22      | 1         | 1.08%   |
| 20      | 1         | 1.08%   |
| 18      | 1         | 1.08%   |
| 16      | 1         | 1.08%   |
| 12      | 1         | 1.08%   |
| 11      | 1         | 1.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 39        | 43.33%  |
| 501-600     | 24        | 26.67%  |
| 401-500     | 6         | 6.67%   |
| 201-300     | 4         | 4.44%   |
| Unknown     | 4         | 4.44%   |
| 601-700     | 3         | 3.33%   |
| 351-400     | 3         | 3.33%   |
| 1501-2000   | 3         | 3.33%   |
| 801-900     | 2         | 2.22%   |
| 701-800     | 1         | 1.11%   |
| 1001-1500   | 1         | 1.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 58        | 79.45%  |
| 16/10   | 7         | 9.59%   |
| 5/4     | 3         | 4.11%   |
| 32/9    | 2         | 2.74%   |
| Unknown | 2         | 2.74%   |
| 21/9    | 1         | 1.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 22        | 24.44%  |
| 101-110        | 16        | 17.78%  |
| 201-250        | 15        | 16.67%  |
| 301-350        | 11        | 12.22%  |
| Unknown        | 4         | 4.44%   |
| More than 1000 | 3         | 3.33%   |
| 351-500        | 3         | 3.33%   |
| 151-200        | 3         | 3.33%   |
| 501-1000       | 3         | 3.33%   |
| 71-80          | 2         | 2.22%   |
| 251-300        | 2         | 2.22%   |
| 121-130        | 2         | 2.22%   |
| 61-70          | 1         | 1.11%   |
| 51-60          | 1         | 1.11%   |
| 141-150        | 1         | 1.11%   |
| 111-120        | 1         | 1.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 36        | 41.86%  |
| 51-100  | 29        | 33.72%  |
| 101-120 | 11        | 12.79%  |
| 161-240 | 5         | 5.81%   |
| Unknown | 4         | 4.65%   |
| 1-50    | 1         | 1.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 42        | 55.26%  |
| 2     | 17        | 22.37%  |
| 0     | 10        | 13.16%  |
| 3     | 6         | 7.89%   |
| 4     | 1         | 1.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 58        | 56.31%  |
| Realtek Semiconductor | 24        | 23.3%   |
| Broadcom              | 5         | 4.85%   |
| Qualcomm Atheros      | 4         | 3.88%   |
| Lenovo                | 3         | 2.91%   |
| Broadcom Limited      | 2         | 1.94%   |
| Samsung Electronics   | 1         | 0.97%   |
| Ralink Technology     | 1         | 0.97%   |
| QLogic                | 1         | 0.97%   |
| NetGear               | 1         | 0.97%   |
| Mellanox Technologies | 1         | 0.97%   |
| Fibocom               | 1         | 0.97%   |
| ASIX Electronics      | 1         | 0.97%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 9.35%   |
| Intel Wireless 8265 / 8275                                        | 8         | 5.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 4.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 3.6%    |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 3.6%    |
| Intel Wireless 8260                                               | 4         | 2.88%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 2.88%   |
| Intel Wireless 7265                                               | 3         | 2.16%   |
| Intel Wireless 7260                                               | 3         | 2.16%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 2.16%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 2.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 2.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 2.16%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 2.16%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 2.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.44%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 1.44%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 2         | 1.44%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.44%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.44%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.44%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.44%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.72%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.72%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.72%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.72%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.72%   |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller          | 1         | 0.72%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                   | 1         | 0.72%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 1         | 0.72%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 47        | 75.81%  |
| Realtek Semiconductor | 6         | 9.68%   |
| Qualcomm Atheros      | 4         | 6.45%   |
| Ralink Technology     | 1         | 1.61%   |
| NetGear               | 1         | 1.61%   |
| Fibocom               | 1         | 1.61%   |
| Broadcom Limited      | 1         | 1.61%   |
| Broadcom              | 1         | 1.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 8         | 12.9%   |
| Intel Wireless 8260                                            | 4         | 6.45%   |
| Intel Wireless 7265                                            | 3         | 4.84%   |
| Intel Wireless 7260                                            | 3         | 4.84%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 4.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 4.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 4.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 4.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 3.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 3.23%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 2         | 3.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 3.23%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 3.23%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 1.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.61%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.61%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 1.61%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 1.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.61%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.61%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                | 1         | 1.61%   |
| Intel Wireless-AC 9260                                         | 1         | 1.61%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 1.61%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 1.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.61%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.61%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 1.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.61%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.61%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 1         | 1.61%   |
| Fibocom L830-EB-00 LTE WWAN Modem                              | 1         | 1.61%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 1         | 1.61%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 1.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 40        | 54.79%  |
| Realtek Semiconductor | 21        | 28.77%  |
| Broadcom              | 4         | 5.48%   |
| Lenovo                | 3         | 4.11%   |
| Samsung Electronics   | 1         | 1.37%   |
| QLogic                | 1         | 1.37%   |
| Mellanox Technologies | 1         | 1.37%   |
| Broadcom Limited      | 1         | 1.37%   |
| ASIX Electronics      | 1         | 1.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 16.88%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 7.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 6.49%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 6.49%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 5.19%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 3.9%    |
| Intel 82574L Gigabit Network Connection                           | 3         | 3.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.6%    |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 2.6%    |
| Intel I211 Gigabit Network Connection                             | 2         | 2.6%    |
| Intel Ethernet Controller I225-V                                  | 2         | 2.6%    |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 2.6%    |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 2.6%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.3%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.3%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.3%    |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller          | 1         | 1.3%    |
| Mellanox MT27500 Family [ConnectX-3]                              | 1         | 1.3%    |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 1.3%    |
| Intel Ethernet Controller I226-V                                  | 1         | 1.3%    |
| Intel Ethernet Connection I219-V                                  | 1         | 1.3%    |
| Intel Ethernet Connection I217-V                                  | 1         | 1.3%    |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.3%    |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.3%    |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.3%    |
| Intel Ethernet Connection (17) I219-V                             | 1         | 1.3%    |
| Intel Ethernet Connection (17) I219-LM                            | 1         | 1.3%    |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.3%    |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.3%    |
| Intel 82599 10 Gigabit Dual Port Backplane Connection             | 1         | 1.3%    |
| Intel 82578DM Gigabit Network Connection                          | 1         | 1.3%    |
| Intel 82576 Gigabit Network Connection                            | 1         | 1.3%    |
| Intel 82571EB Gigabit Ethernet Controller                         | 1         | 1.3%    |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1         | 1.3%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.3%    |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 1.3%    |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 1.3%    |
| Broadcom BCM57840 NetXtreme II 10/20-Gigabit Ethernet             | 1         | 1.3%    |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 63        | 52.07%  |
| WiFi     | 58        | 47.93%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 41        | 53.25%  |
| WiFi     | 36        | 46.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 46        | 61.33%  |
| 1     | 25        | 33.33%  |
| 4     | 2         | 2.67%   |
| 6     | 1         | 1.33%   |
| 3     | 1         | 1.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 60        | 75.95%  |
| Yes  | 19        | 24.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 71.74%  |
| Realtek Semiconductor           | 3         | 6.52%   |
| Qualcomm Atheros Communications | 3         | 6.52%   |
| Broadcom                        | 3         | 6.52%   |
| IMC Networks                    | 1         | 2.17%   |
| ASUSTek Computer                | 1         | 2.17%   |
| Apple                           | 1         | 2.17%   |
| Alps Electric                   | 1         | 2.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 13        | 28.26%  |
| Intel Bluetooth Device                         | 6         | 13.04%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 6         | 13.04%  |
| Intel AX201 Bluetooth                          | 5         | 10.87%  |
| Realtek  Bluetooth 4.2 Adapter                 | 2         | 4.35%   |
| Qualcomm Atheros  Bluetooth Device             | 2         | 4.35%   |
| Realtek Bluetooth Radio                        | 1         | 2.17%   |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 2.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1         | 2.17%   |
| Intel Wireless-AC 3168 Bluetooth               | 1         | 2.17%   |
| Intel AX210 Bluetooth                          | 1         | 2.17%   |
| IMC Networks Bluetooth Radio                   | 1         | 2.17%   |
| Broadcom BCM43142A0 Bluetooth 4.0              | 1         | 2.17%   |
| Broadcom BCM20702A0 Bluetooth 4.0              | 1         | 2.17%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 2.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth             | 1         | 2.17%   |
| Apple Bluetooth Host Controller                | 1         | 2.17%   |
| Alps Electric UGTZ4 Bluetooth                  | 1         | 2.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 64        | 62.75%  |
| Nvidia              | 16        | 15.69%  |
| AMD                 | 9         | 8.82%   |
| Lenovo              | 5         | 4.9%    |
| GN Netcom           | 5         | 4.9%    |
| Unknown             | 1         | 0.98%   |
| TEAC                | 1         | 0.98%   |
| C-Media Electronics | 1         | 0.98%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 10        | 8.62%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 5.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 5.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 4.31%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 4.31%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 3.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 2.59%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 2.59%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 2.59%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 2.59%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.72%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 1.72%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 1.72%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 1.72%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.72%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 2         | 1.72%   |
| Lenovo ThinkPad Dock USB Audio                                             | 2         | 1.72%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 2         | 1.72%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 2         | 1.72%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.72%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.72%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.72%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.72%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2         | 1.72%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 1.72%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.72%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 1.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.72%   |
| GN Netcom Jabra EVOLVE LINK                                                | 2         | 1.72%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2         | 1.72%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 1.72%   |
| Unknown Definitive Sym1                                                    | 1         | 0.86%   |
| TEAC US-2x2                                                                | 1         | 0.86%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.86%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.86%   |
| Nvidia GK110 High Definition Audio Controller                              | 1         | 0.86%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.86%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.86%   |
| Nvidia Audio device                                                        | 1         | 0.86%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                   | 1         | 0.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 11        | 22.45%  |
| Micron Technology                       | 10        | 20.41%  |
| SK hynix                                | 7         | 14.29%  |
| Kingston                                | 5         | 10.2%   |
| Unknown                                 | 3         | 6.12%   |
| Crucial                                 | 3         | 6.12%   |
| Unknown                                 | 2         | 4.08%   |
| Unigen                                  | 1         | 2.04%   |
| Smart                                   | 1         | 2.04%   |
| Silicon Power Computer & Communications | 1         | 2.04%   |
| Nanya Technology                        | 1         | 2.04%   |
| HPE                                     | 1         | 2.04%   |
| Corsair                                 | 1         | 2.04%   |
| Avant                                   | 1         | 2.04%   |
| 4ea5                                    | 1         | 2.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s           | 3         | 5.66%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s            | 2         | 3.77%   |
| Unknown                                                         | 2         | 3.77%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 1.89%   |
| Unknown RAM Module 4GB DIMM DDR3 800MT/s                        | 1         | 1.89%   |
| Unknown RAM Module 32GB SODIMM DDR4 2667MT/s                    | 1         | 1.89%   |
| Unigen RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 1.89%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s           | 1         | 1.89%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 1.89%   |
| SK hynix RAM HMT31GR7BFR4A-H9 8192MB DIMM 1333MT/s              | 1         | 1.89%   |
| SK hynix RAM HMAA1GS6CMR8N-VK 8192MB Row Of Chips DDR4 2667MT/s | 1         | 1.89%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s    | 1         | 1.89%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s       | 1         | 1.89%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 1         | 1.89%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s          | 1         | 1.89%   |
| SK hynix RAM H9HCNNNBKUMLXR-NEE 2GB LPDDR4 2400MT/s             | 1         | 1.89%   |
| Silicon Power & RAM Module 16GB SODIMM DDR4 2667MT/s            | 1         | 1.89%   |
| Samsung RAM Module 8GB SODIMM DDR5 4800MT/s                     | 1         | 1.89%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.89%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s          | 1         | 1.89%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s          | 1         | 1.89%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s          | 1         | 1.89%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s           | 1         | 1.89%   |
| Samsung RAM M393B2G70BH0-YH9 16GB DIMM DDR3 1333MT/s            | 1         | 1.89%   |
| Samsung RAM M393B2G70BH0-CK0 16GB DIMM 1600MT/s                 | 1         | 1.89%   |
| Nanya RAM NT8GA64D88AX3S-HR 8GB SODIMM DDR4 2667MT/s            | 1         | 1.89%   |
| Micron RAM Module 16384MB SODIMM DDR4 2400MT/s                  | 1         | 1.89%   |
| Micron RAM 8ATF1G64AZ-2G3H1 8GB DIMM DDR4 2448MT/s              | 1         | 1.89%   |
| Micron RAM 8ATF1G64AZ-2G3E1 8192MB DIMM DDR4 2400MT/s           | 1         | 1.89%   |
| Micron RAM 8ATF1G64AZ-2G3B1 8GB DIMM DDR4 2448MT/s              | 1         | 1.89%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s     | 1         | 1.89%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s           | 1         | 1.89%   |
| Micron RAM 4ATF1G64AZ-3G2F1 8GB DIMM DDR4 3200MT/s              | 1         | 1.89%   |
| Micron RAM 18ASF2G72PDZ-2G3B1 16GB DIMM DDR4 2400MT/s           | 1         | 1.89%   |
| Micron RAM 16JTF1G64HZ-1G4D1 8GB SODIMM DDR3 1333MT/s           | 1         | 1.89%   |
| Micron RAM 16ATF2G64HZ-2G1A1 16GB SODIMM DDR4 2133MT/s          | 1         | 1.89%   |
| Kingston RAM KX830D-ELC 4GB SODIMM DDR3 1333MT/s                | 1         | 1.89%   |
| Kingston RAM KTW149-ELF 1GB DIMM DDR3 1333MT/s                  | 1         | 1.89%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s                | 1         | 1.89%   |
| Kingston RAM 9905700-101.A00G 16GB SODIMM DDR4 3200MT/s         | 1         | 1.89%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 25        | 55.56%  |
| DDR3   | 15        | 33.33%  |
| LPDDR5 | 2         | 4.44%   |
| LPDDR4 | 2         | 4.44%   |
| DDR5   | 1         | 2.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 28        | 62.22%  |
| DIMM         | 11        | 24.44%  |
| Row Of Chips | 5         | 11.11%  |
| Unknown      | 1         | 2.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 19        | 40.43%  |
| 16384 | 12        | 25.53%  |
| 4096  | 11        | 23.4%   |
| 32768 | 3         | 6.38%   |
| 2048  | 1         | 2.13%   |
| 1024  | 1         | 2.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 12        | 25.53%  |
| 1600  | 8         | 17.02%  |
| 1333  | 7         | 14.89%  |
| 3200  | 5         | 10.64%  |
| 2400  | 5         | 10.64%  |
| 6400  | 2         | 4.26%   |
| 4800  | 1         | 2.13%   |
| 4267  | 1         | 2.13%   |
| 3466  | 1         | 2.13%   |
| 2666  | 1         | 2.13%   |
| 2448  | 1         | 2.13%   |
| 2133  | 1         | 2.13%   |
| 1866  | 1         | 2.13%   |
| 800   | 1         | 2.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Samsung ML-1660 Series | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 120 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 10        | 24.39%  |
| IMC Networks                           | 6         | 14.63%  |
| Logitech                               | 5         | 12.2%   |
| Realtek Semiconductor                  | 4         | 9.76%   |
| Suyin                                  | 3         | 7.32%   |
| Lite-On Technology                     | 3         | 7.32%   |
| Microdia                               | 2         | 4.88%   |
| Luxvisions Innotech Limited            | 2         | 4.88%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.88%   |
| Bison Electronics                      | 2         | 4.88%   |
| Quanta                                 | 1         | 2.44%   |
| Microsoft                              | 1         | 2.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 6         | 14.29%  |
| IMC Networks Integrated Camera                                  | 3         | 7.14%   |
| Realtek Integrated_Webcam_HD                                    | 2         | 4.76%   |
| Microdia Webcam Vitade AF                                       | 2         | 4.76%   |
| Lite-On Integrated Camera                                       | 2         | 4.76%   |
| IMC Networks VGA UVC WebCam                                     | 2         | 4.76%   |
| Chicony Integrated Camera (1280x720@30)                         | 2         | 4.76%   |
| Bison SunplusIT Integrated Camera                               | 2         | 4.76%   |
| Suyin Integrated_Webcam_HD                                      | 1         | 2.38%   |
| Suyin HP Truevision HD                                          | 1         | 2.38%   |
| Suyin Asus Integrated Webcam                                    | 1         | 2.38%   |
| Realtek Integrated_Webcam_FHD                                   | 1         | 2.38%   |
| Realtek EasyCamera                                              | 1         | 2.38%   |
| Quanta HP Webcam                                                | 1         | 2.38%   |
| Microsoft LifeCam HD-3000                                       | 1         | 2.38%   |
| Luxvisions Innotech Limited HP 5MP Camera                       | 1         | 2.38%   |
| Luxvisions Innotech Limited EasyCamera 1M                       | 1         | 2.38%   |
| Logitech Webcam C925e                                           | 1         | 2.38%   |
| Logitech Webcam C920-C                                          | 1         | 2.38%   |
| Logitech Webcam C270                                            | 1         | 2.38%   |
| Logitech HD Webcam C615                                         | 1         | 2.38%   |
| Logitech BRIO                                                   | 1         | 2.38%   |
| Lite-On HP HD Camera                                            | 1         | 2.38%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 1         | 2.38%   |
| Chicony TOSHIBA Web Camera - HD                                 | 1         | 2.38%   |
| Chicony ThinkPad T490 Webcam                                    | 1         | 2.38%   |
| Chicony Integrated IR Camera                                    | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera | 1         | 2.38%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 42.11%  |
| Synaptics                  | 8         | 42.11%  |
| Upek                       | 1         | 5.26%   |
| Shenzhen Goodix Technology | 1         | 5.26%   |
| Elan Microelectronics      | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 15.79%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 15.79%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 15.79%  |
| Validity Sensors Synaptics WBDI                                            | 2         | 10.53%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 10.53%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 5.26%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 5.26%   |
| Synaptics WBDI                                                             | 1         | 5.26%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 5.26%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 5.26%   |
| Elan ELAN:Fingerprint                                                      | 1         | 5.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 7         | 77.78%  |
| Alcor Micro | 2         | 22.22%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 58200                                 | 4         | 44.44%  |
| Broadcom BCM5880 Secure Applications Processor | 3         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader            | 2         | 22.22%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 36        | 46.75%  |
| 1     | 27        | 35.06%  |
| 2     | 10        | 12.99%  |
| 3     | 3         | 3.9%    |
| 7     | 1         | 1.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 19        | 33.33%  |
| Graphics card            | 9         | 15.79%  |
| Chipcard                 | 7         | 12.28%  |
| Net/wireless             | 5         | 8.77%   |
| Unassigned class         | 3         | 5.26%   |
| Communication controller | 3         | 5.26%   |
| Card reader              | 3         | 5.26%   |
| Bluetooth                | 3         | 5.26%   |
| Storage                  | 2         | 3.51%   |
| Sound                    | 2         | 3.51%   |
| Multimedia controller    | 1         | 1.75%   |

