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

Total: 112

| Vendor     | Model                       | Form-Factor | Probe                                                      | Date         |
|------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo     | Legion Y540-15IRH 81SX      | Notebook    | [1da691596b](https://linux-hardware.org/?probe=1da691596b) | Nov 06, 2023 |
| Lenovo     | Legion Y540-15IRH 81SX      | Notebook    | [d385d4714c](https://linux-hardware.org/?probe=d385d4714c) | Nov 06, 2023 |
| Dell       | Precision 5550              | Notebook    | [033e294199](https://linux-hardware.org/?probe=033e294199) | Nov 03, 2023 |
| HP         | 240 G8 Notebook PC          | Notebook    | [0a98dcd952](https://linux-hardware.org/?probe=0a98dcd952) | Oct 11, 2023 |
| ASUSTek    | SABERTOOTH 990FX R3.0       | Desktop     | [b63af8760f](https://linux-hardware.org/?probe=b63af8760f) | Oct 03, 2023 |
| ASUSTek    | SABERTOOTH 990FX R3.0       | Desktop     | [5ac9728fe0](https://linux-hardware.org/?probe=5ac9728fe0) | Oct 01, 2023 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Oracle Linux 8.5 | 13        | 15.29%  |
| Oracle Linux 8.3 | 12        | 14.12%  |
| Oracle Linux 9.2 | 9         | 10.59%  |
| Oracle Linux 8.4 | 7         | 8.24%   |
| Oracle Linux 8.8 | 6         | 7.06%   |
| Oracle Linux 8.6 | 6         | 7.06%   |
| Oracle Linux 9.1 | 5         | 5.88%   |
| Oracle Linux 9.0 | 5         | 5.88%   |
| Oracle Linux 8.7 | 5         | 5.88%   |
| Oracle Linux 7.9 | 4         | 4.71%   |
| Oracle Linux 8.1 | 3         | 3.53%   |
| Oracle Linux 7.7 | 3         | 3.53%   |
| Oracle Linux 8.2 | 2         | 2.35%   |
| Oracle Linux 7.8 | 2         | 2.35%   |
| Oracle Linux 7.6 | 2         | 2.35%   |
| Oracle Linux 7.4 | 1         | 1.18%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Oracle Linux | 78        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                           | Computers | Percent |
|-----------------------------------|-----------|---------|
| 5.4.17-2102.202.5.el8uek.x86_64   | 3         | 3.26%   |
| 5.4.17-2036.103.3.1.el8uek.x86_64 | 3         | 3.26%   |
| 5.15.0-2.52.3.el9uek.x86_64       | 3         | 3.26%   |
| 5.15.0-101.103.2.1.el9uek.x86_64  | 3         | 3.26%   |
| 5.15.0-100.96.32.el8uek.x86_64    | 3         | 3.26%   |
| 4.18.0-348.12.2.el8_5.x86_64      | 3         | 3.26%   |
| 5.4.17-2136.313.6.el8uek.x86_64   | 2         | 2.17%   |
| 5.4.17-2136.304.4.3.el8uek.x86_64 | 2         | 2.17%   |
| 5.4.17-2136.300.7.el8uek.x86_64   | 2         | 2.17%   |
| 5.4.17-2102.205.7.3.el8uek.x86_64 | 2         | 2.17%   |
| 5.4.17-2102.200.13.el8uek.x86_64  | 2         | 2.17%   |
| 5.4.17-2036.102.0.2.el8uek.x86_64 | 2         | 2.17%   |
| 5.4.17-2036.101.2.el8uek.x86_64   | 2         | 2.17%   |
| 5.15.0-5.76.5.1.el9uek.x86_64     | 2         | 2.17%   |
| 5.15.0-103.114.4.el8uek.x86_64    | 2         | 2.17%   |
| 4.18.0-240.15.1.el8_3.x86_64      | 2         | 2.17%   |
| 4.18.0-193.1.2.el8_2.x86_64       | 2         | 2.17%   |
| 4.18.0-147.3.1.el8_1.x86_64       | 2         | 2.17%   |
| 5.4.17-2136.318.7.2.el8uek.x86_64 | 1         | 1.09%   |
| 5.4.17-2136.312.3.4.el7uek.x86_64 | 1         | 1.09%   |
| 5.4.17-2136.310.7.el8uek.x86_64   | 1         | 1.09%   |
| 5.4.17-2136.310.7.1.el8uek.x86_64 | 1         | 1.09%   |
| 5.4.17-2136.309.4.el8uek.x86_64   | 1         | 1.09%   |
| 5.4.17-2136.308.9.el8uek.x86_64   | 1         | 1.09%   |
| 5.4.17-2136.308.9.el7uek.x86_64   | 1         | 1.09%   |
| 5.4.17-2136.307.3.1.el8uek.x86_64 | 1         | 1.09%   |
| 5.4.17-2136.306.1.3.el8uek.x86_64 | 1         | 1.09%   |
| 5.4.17-2136.305.5.4.el8uek.x86_64 | 1         | 1.09%   |
| 5.4.17-2136.305.5.3.el8uek.x86_64 | 1         | 1.09%   |
| 5.4.17-2136.305.5.2.el8uek.x86_64 | 1         | 1.09%   |
| 5.4.17-2136.301.1.4.el8uek.x86_64 | 1         | 1.09%   |
| 5.4.17-2102.204.4.4.el8uek.x86_64 | 1         | 1.09%   |
| 5.4.17-2102.204.4.2.el8uek.x86_64 | 1         | 1.09%   |
| 5.4.17-2102.201.3.el8uek.x86_64   | 1         | 1.09%   |
| 5.4.17-2036.104.4.el8uek.x86_64   | 1         | 1.09%   |
| 5.4.17-2036.100.6.1.el8uek.x86_64 | 1         | 1.09%   |
| 5.4.17-2011.0.7.el8uek.x86_64     | 1         | 1.09%   |
| 5.4.11-1.el7.elrepo.x86_64        | 1         | 1.09%   |
| 5.15.2-1.el8.elrepo.x86_64        | 1         | 1.09%   |
| 5.15.0-6.80.3.1.el9uek.x86_64     | 1         | 1.09%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.17  | 29        | 36.25%  |
| 5.15.0  | 23        | 28.75%  |
| 4.18.0  | 12        | 15%     |
| 4.14.35 | 5         | 6.25%   |
| 5.14.0  | 3         | 3.75%   |
| 3.10.0  | 3         | 3.75%   |
| 5.4.11  | 1         | 1.25%   |
| 5.15.2  | 1         | 1.25%   |
| 5.14.1  | 1         | 1.25%   |
| 5.11.1  | 1         | 1.25%   |
| 4.1.12  | 1         | 1.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 30        | 37.5%   |
| 5.15    | 24        | 30%     |
| 4.18    | 12        | 15%     |
| 4.14    | 5         | 6.25%   |
| 5.14    | 4         | 5%      |
| 3.10    | 3         | 3.75%   |
| 5.11    | 1         | 1.25%   |
| 4.1     | 1         | 1.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 78        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 61        | 74.39%  |
| Unknown       | 10        | 12.2%   |
| GNOME Classic | 3         | 3.66%   |
| XFCE          | 2         | 2.44%   |
| MATE          | 2         | 2.44%   |
| KDE5          | 2         | 2.44%   |
| KDE4          | 2         | 2.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 43        | 53.75%  |
| X11     | 28        | 35%     |
| Unknown | 7         | 8.75%   |
| Web     | 1         | 1.25%   |
| Tty     | 1         | 1.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 39        | 48.75%  |
| Unknown | 38        | 47.5%   |
| SDDM    | 2         | 2.5%    |
| TDM     | 1         | 1.25%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 49        | 62.03%  |
| en_GB      | 8         | 10.13%  |
| de_DE      | 4         | 5.06%   |
| Unknown    | 4         | 5.06%   |
| pl_PL      | 3         | 3.8%    |
| en_AU      | 3         | 3.8%    |
| it_IT      | 2         | 2.53%   |
| en_IN      | 2         | 2.53%   |
| zh_HK      | 1         | 1.27%   |
| ru_RU      | 1         | 1.27%   |
| pt_BR      | 1         | 1.27%   |
| en_US.UTF8 | 1         | 1.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 46        | 58.23%  |
| BIOS | 33        | 41.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 69        | 86.25%  |
| Ext4    | 8         | 10%     |
| Unknown | 2         | 2.5%    |
| Zfs     | 1         | 1.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 35        | 43.75%  |
| Unknown | 32        | 40%     |
| MBR     | 13        | 16.25%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 73        | 92.41%  |
| Yes       | 6         | 7.59%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 73        | 93.59%  |
| Yes       | 5         | 6.41%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 22        | 28.21%  |
| Dell                | 15        | 19.23%  |
| Hewlett-Packard     | 11        | 14.1%   |
| ASUSTek Computer    | 9         | 11.54%  |
| Intel               | 4         | 5.13%   |
| Gigabyte Technology | 4         | 5.13%   |
| MSI                 | 2         | 2.56%   |
| Supermicro          | 1         | 1.28%   |
| Standard            | 1         | 1.28%   |
| Panasonic           | 1         | 1.28%   |
| HPE                 | 1         | 1.28%   |
| Google              | 1         | 1.28%   |
| Fujitsu             | 1         | 1.28%   |
| Foxconn             | 1         | 1.28%   |
| Dynabook            | 1         | 1.28%   |
| Cisco               | 1         | 1.28%   |
| ASRock              | 1         | 1.28%   |
| Apple               | 1         | 1.28%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Lenovo ThinkPad T450 20BUS14900           | 2         | 2.56%   |
| ASUS X510UR                               | 2         | 2.56%   |
| Supermicro X8DTU                          | 1         | 1.28%   |
| Standard BW Series                        | 1         | 1.28%   |
| Panasonic CF-53AAG54FM                    | 1         | 1.28%   |
| MSI P65 Creator 8RE                       | 1         | 1.28%   |
| MSI MS-7758                               | 1         | 1.28%   |
| Lenovo ThinkPad X390 Yoga 20NQS2SF00      | 1         | 1.28%   |
| Lenovo ThinkPad X280 20KES4H34G           | 1         | 1.28%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QWS1R800 | 1         | 1.28%   |
| Lenovo ThinkPad W541 20EGS1PL00           | 1         | 1.28%   |
| Lenovo ThinkPad T490 20N3S77600           | 1         | 1.28%   |
| Lenovo ThinkPad T490 20N3S3XR00           | 1         | 1.28%   |
| Lenovo ThinkPad T480 20L6S56Y2X           | 1         | 1.28%   |
| Lenovo ThinkPad T480 20L5A07TAU           | 1         | 1.28%   |
| Lenovo ThinkPad T470 20HES21434           | 1         | 1.28%   |
| Lenovo ThinkPad T470 20HES0E71M           | 1         | 1.28%   |
| Lenovo ThinkPad T430s 2355C33             | 1         | 1.28%   |
| Lenovo ThinkPad P70 20ESS04S00            | 1         | 1.28%   |
| Lenovo ThinkPad P50s 20FL000MUS           | 1         | 1.28%   |
| Lenovo ThinkPad L540 20AVCTO1WW           | 1         | 1.28%   |
| Lenovo ThinkPad L490 20Q5CTO1WW           | 1         | 1.28%   |
| Lenovo Legion Y540-15IRH 81SX             | 1         | 1.28%   |
| Lenovo Legion 5 15IMH05 82AU              | 1         | 1.28%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS       | 1         | 1.28%   |
| Lenovo IdeaPad C340-14IWL 81RL            | 1         | 1.28%   |
| Lenovo IdeaPad 300-15ISK 80RS             | 1         | 1.28%   |
| Intel NUC6CAYH                            | 1         | 1.28%   |
| Intel NUC13ANHi5                          | 1         | 1.28%   |
| Intel NUC12WSHi7                          | 1         | 1.28%   |
| Intel NUC12WSHi5                          | 1         | 1.28%   |
| HPE ProLiant BL460c Gen10                 | 1         | 1.28%   |
| HP ZBook Fury 16 G9 Mobile Workstation PC | 1         | 1.28%   |
| HP ZBook 15                               | 1         | 1.28%   |
| HP Z820 Workstation                       | 1         | 1.28%   |
| HP Z420 Workstation                       | 1         | 1.28%   |
| HP ProBook 445 G6                         | 1         | 1.28%   |
| HP Pavilion x360 Convertible 14-dy0xxx    | 1         | 1.28%   |
| HP Notebook                               | 1         | 1.28%   |
| HP Laptop 17-cp0xxx                       | 1         | 1.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 17        | 21.79%  |
| Dell Latitude          | 5         | 6.41%   |
| Dell OptiPlex          | 4         | 5.13%   |
| Lenovo IdeaPad         | 3         | 3.85%   |
| Dell Precision         | 3         | 3.85%   |
| Lenovo Legion          | 2         | 2.56%   |
| HP ZBook               | 2         | 2.56%   |
| Dell Inspiron          | 2         | 2.56%   |
| ASUS X510UR            | 2         | 2.56%   |
| Supermicro X8DTU       | 1         | 1.28%   |
| Standard BW            | 1         | 1.28%   |
| Panasonic CF-53AAG54FM | 1         | 1.28%   |
| MSI P65                | 1         | 1.28%   |
| MSI MS-7758            | 1         | 1.28%   |
| Intel NUC6CAYH         | 1         | 1.28%   |
| Intel NUC13ANHi5       | 1         | 1.28%   |
| Intel NUC12WSHi7       | 1         | 1.28%   |
| Intel NUC12WSHi5       | 1         | 1.28%   |
| HPE ProLiant           | 1         | 1.28%   |
| HP Z820                | 1         | 1.28%   |
| HP Z420                | 1         | 1.28%   |
| HP ProBook             | 1         | 1.28%   |
| HP Pavilion            | 1         | 1.28%   |
| HP Notebook            | 1         | 1.28%   |
| HP Laptop              | 1         | 1.28%   |
| HP EliteBook           | 1         | 1.28%   |
| HP Compaq              | 1         | 1.28%   |
| HP 240                 | 1         | 1.28%   |
| Google Lick            | 1         | 1.28%   |
| Gigabyte Z490          | 1         | 1.28%   |
| Gigabyte X99-Designare | 1         | 1.28%   |
| Gigabyte X470          | 1         | 1.28%   |
| Gigabyte H81M-S2PV     | 1         | 1.28%   |
| Fujitsu PRIMERGY       | 1         | 1.28%   |
| Foxconn p6-2400el      | 1         | 1.28%   |
| Dynabook PORTEGE       | 1         | 1.28%   |
| Dell PowerEdge         | 1         | 1.28%   |
| Cisco WAVE-694-K9      | 1         | 1.28%   |
| ASUS ZenBook           | 1         | 1.28%   |
| ASUS UX305FA           | 1         | 1.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 10        | 12.82%  |
| 2020 | 8         | 10.26%  |
| 2018 | 8         | 10.26%  |
| 2016 | 7         | 8.97%   |
| 2022 | 6         | 7.69%   |
| 2021 | 6         | 7.69%   |
| 2014 | 6         | 7.69%   |
| 2012 | 6         | 7.69%   |
| 2017 | 4         | 5.13%   |
| 2011 | 4         | 5.13%   |
| 2015 | 3         | 3.85%   |
| 2013 | 3         | 3.85%   |
| 2010 | 3         | 3.85%   |
| 2023 | 2         | 2.56%   |
| 2009 | 1         | 1.28%   |
| 2008 | 1         | 1.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 47        | 60.26%  |
| Desktop     | 20        | 25.64%  |
| Mini pc     | 5         | 6.41%   |
| Convertible | 3         | 3.85%   |
| Server      | 3         | 3.85%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 68        | 86.08%  |
| Enabled  | 11        | 13.92%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 77        | 98.72%  |
| Yes  | 1         | 1.28%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 23        | 29.11%  |
| 32.01-64.0      | 18        | 22.78%  |
| 4.01-8.0        | 12        | 15.19%  |
| 64.01-256.0     | 7         | 8.86%   |
| 16.01-24.0      | 7         | 8.86%   |
| 3.01-4.0        | 6         | 7.59%   |
| 24.01-32.0      | 4         | 5.06%   |
| More than 256.0 | 1         | 1.27%   |
| 1.01-2.0        | 1         | 1.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 25        | 29.07%  |
| 2.01-3.0    | 21        | 24.42%  |
| 3.01-4.0    | 14        | 16.28%  |
| 8.01-16.0   | 10        | 11.63%  |
| 1.01-2.0    | 9         | 10.47%  |
| 0.51-1.0    | 3         | 3.49%   |
| 24.01-32.0  | 1         | 1.16%   |
| 64.01-256.0 | 1         | 1.16%   |
| 16.01-24.0  | 1         | 1.16%   |
| 0.01-0.5    | 1         | 1.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 58        | 72.5%   |
| 2      | 14        | 17.5%   |
| 3      | 4         | 5%      |
| 4      | 2         | 2.5%    |
| 6      | 1         | 1.25%   |
| 5      | 1         | 1.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 62        | 79.49%  |
| Yes       | 16        | 20.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 84.62%  |
| No        | 12        | 15.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 78.21%  |
| No        | 17        | 21.79%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 60.76%  |
| No        | 31        | 39.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 24        | 30.38%  |
| Germany     | 9         | 11.39%  |
| UK          | 5         | 6.33%   |
| Poland      | 5         | 6.33%   |
| Brazil      | 4         | 5.06%   |
| Australia   | 4         | 5.06%   |
| Netherlands | 3         | 3.8%    |
| Finland     | 3         | 3.8%    |
| Russia      | 2         | 2.53%   |
| Romania     | 2         | 2.53%   |
| Italy       | 2         | 2.53%   |
| India       | 2         | 2.53%   |
| Yemen       | 1         | 1.27%   |
| Turkey      | 1         | 1.27%   |
| Sweden      | 1         | 1.27%   |
| Spain       | 1         | 1.27%   |
| Slovakia    | 1         | 1.27%   |
| Pakistan    | 1         | 1.27%   |
| Nigeria     | 1         | 1.27%   |
| Latvia      | 1         | 1.27%   |
| Kazakhstan  | 1         | 1.27%   |
| Hungary     | 1         | 1.27%   |
| Hong Kong   | 1         | 1.27%   |
| Bulgaria    | 1         | 1.27%   |
| Bolivia     | 1         | 1.27%   |
| Argentina   | 1         | 1.27%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| San Diego          | 3         | 3.53%   |
| Helsinki           | 3         | 3.53%   |
| Warsaw             | 2         | 2.35%   |
| Siegen             | 2         | 2.35%   |
| Seattle            | 2         | 2.35%   |
| Sao Paulo          | 2         | 2.35%   |
| Colorado Springs   | 2         | 2.35%   |
| Bucharest          | 2         | 2.35%   |
| Berlin             | 2         | 2.35%   |
| Amsterdam          | 2         | 2.35%   |
| Zavar              | 1         | 1.18%   |
| Weaverville        | 1         | 1.18%   |
| Veliky Novgorod    | 1         | 1.18%   |
| Valmiera           | 1         | 1.18%   |
| Utrecht            | 1         | 1.18%   |
| Turner             | 1         | 1.18%   |
| Sydney             | 1         | 1.18%   |
| Stuttgart          | 1         | 1.18%   |
| Stockholm          | 1         | 1.18%   |
| Sofia              | 1         | 1.18%   |
| Shrewsbury         | 1         | 1.18%   |
| Sao Caetano do Sul | 1         | 1.18%   |
| Santa Cruz         | 1         | 1.18%   |
| Sanaa              | 1         | 1.18%   |
| San Francisco      | 1         | 1.18%   |
| Rocklin            | 1         | 1.18%   |
| Riverside          | 1         | 1.18%   |
| Redwood City       | 1         | 1.18%   |
| Reading            | 1         | 1.18%   |
| Port Saint Lucie   | 1         | 1.18%   |
| Pleven             | 1         | 1.18%   |
| Petersberg         | 1         | 1.18%   |
| Perugia            | 1         | 1.18%   |
| Parker             | 1         | 1.18%   |
| Ngau Wu Tok        | 1         | 1.18%   |
| Neunkirchen        | 1         | 1.18%   |
| Nagercoil          | 1         | 1.18%   |
| Moscow             | 1         | 1.18%   |
| Melbourne          | 1         | 1.18%   |
| Maple Valley       | 1         | 1.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 26        | 35     | 26%     |
| Seagate                   | 12        | 50     | 12%     |
| SanDisk                   | 8         | 11     | 8%      |
| WDC                       | 7         | 8      | 7%      |
| Unknown                   | 5         | 7      | 5%      |
| Toshiba                   | 4         | 4      | 4%      |
| SK hynix                  | 4         | 4      | 4%      |
| Intel                     | 4         | 4      | 4%      |
| Crucial                   | 4         | 5      | 4%      |
| Phison Electronics        | 3         | 3      | 3%      |
| Micron Technology         | 3         | 6      | 3%      |
| Kingston                  | 3         | 10     | 3%      |
| HGST                      | 3         | 6      | 3%      |
| Hewlett-Packard           | 2         | 2      | 2%      |
| Union Memory (Shenzhen)   | 1         | 2      | 1%      |
| Transcend                 | 1         | 1      | 1%      |
| Phison                    | 1         | 1      | 1%      |
| Micron/Crucial Technology | 1         | 1      | 1%      |
| Lite-On                   | 1         | 1      | 1%      |
| Lenovo                    | 1         | 1      | 1%      |
| KIOXIA                    | 1         | 1      | 1%      |
| JMicron Technology        | 1         | 1      | 1%      |
| HPE                       | 1         | 1      | 1%      |
| GOODRAM                   | 1         | 1      | 1%      |
| Fujitsu                   | 1         | 1      | 1%      |
| Apple                     | 1         | 1      | 1%      |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown SD/MMC/MS PRO 16GB                        | 2         | 1.85%   |
| Seagate ST2000DM008-2FR102 2TB                    | 2         | 1.85%   |
| SanDisk SSD PLUS 1000GB                           | 2         | 1.85%   |
| Samsung SSD PM830 2.5 7mm 256GB                   | 2         | 1.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2         | 1.85%   |
| Samsung MZVLB512HAJQ-000L7 512GB                  | 2         | 1.85%   |
| Samsung MZ7LN512HMJP-000L7 512GB SSD              | 2         | 1.85%   |
| Phison E12 NVMe Controller 1TB                    | 2         | 1.85%   |
| Kingston SA400S37240G 240GB SSD                   | 2         | 1.85%   |
| Intel SSD 660P Series 1024GB                      | 2         | 1.85%   |
| Crucial CT500MX500SSD1 500GB                      | 2         | 1.85%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 1         | 0.93%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                  | 1         | 0.93%   |
| WDC WD3200BEKT-08PVMT1 320GB                      | 1         | 0.93%   |
| WDC WD1600YS-23SHB0 160GB                         | 1         | 0.93%   |
| WDC WD10SPZX-60Z10T1 1TB                          | 1         | 0.93%   |
| WDC WD10JPCX-24UE4T0 1TB                          | 1         | 0.93%   |
| WDC WD10EZEX-60M2NA0 1TB                          | 1         | 0.93%   |
| Unknown MMC64G  64GB                              | 1         | 0.93%   |
| Unknown MMC Card  256GB                           | 1         | 0.93%   |
| Unknown MMC Card  1TB                             | 1         | 0.93%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB      | 1         | 0.93%   |
| Transcend TS2TMTE250H 2TB                         | 1         | 0.93%   |
| Toshiba THNSNJ512GCSU 512GB SSD                   | 1         | 0.93%   |
| Toshiba NVMe SSD Drive 512GB                      | 1         | 0.93%   |
| Toshiba MG04ACA200E 2TB                           | 1         | 0.93%   |
| Toshiba DT01ACA050 500GB                          | 1         | 0.93%   |
| SK hynix SKHynix_HFS256GD9TNG-L3A0B 256GB         | 1         | 0.93%   |
| SK hynix PC801 NVMe 512GB                         | 1         | 0.93%   |
| SK hynix BC901 NVMe 512GB                         | 1         | 0.93%   |
| SK hynix BC501 NVMe Solid State Drive 512GB       | 1         | 0.93%   |
| Seagate ST9750420AS 752GB                         | 1         | 0.93%   |
| Seagate ST8000VN004-2M2101 8TB                    | 1         | 0.93%   |
| Seagate ST3750528AS 752GB                         | 1         | 0.93%   |
| Seagate ST3500414CS 500GB                         | 1         | 0.93%   |
| Seagate ST2000NX0253 2TB                          | 1         | 0.93%   |
| Seagate ST2000DM001-1ER164 2TB                    | 1         | 0.93%   |
| Seagate ST1000VX000-1ES162 1TB                    | 1         | 0.93%   |
| Seagate ST1000NX0423 1TB                          | 1         | 0.93%   |
| Seagate ST1000LX015-1U7172 1TB                    | 1         | 0.93%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


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

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 19     | 42.42%  |
| SanDisk             | 6         | 8      | 18.18%  |
| Crucial             | 3         | 4      | 9.09%   |
| WDC                 | 2         | 2      | 6.06%   |
| Kingston            | 2         | 3      | 6.06%   |
| Hewlett-Packard     | 2         | 2      | 6.06%   |
| Toshiba             | 1         | 1      | 3.03%   |
| Intel               | 1         | 1      | 3.03%   |
| HPE                 | 1         | 1      | 3.03%   |
| GOODRAM             | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 36        | 50     | 37.5%   |
| SSD  | 31        | 42     | 32.29%  |
| HDD  | 26        | 73     | 27.08%  |
| MMC  | 3         | 3      | 3.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 47        | 108    | 52.22%  |
| NVMe | 36        | 50     | 40%     |
| SAS  | 4         | 7      | 4.44%   |
| MMC  | 3         | 3      | 3.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 27        | 37     | 48.21%  |
| 0.51-1.0   | 21        | 31     | 37.5%   |
| 1.01-2.0   | 7         | 45     | 12.5%   |
| 4.01-10.0  | 1         | 2      | 1.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 22        | 27.5%   |
| 101-250        | 15        | 18.75%  |
| 501-1000       | 13        | 16.25%  |
| 1-20           | 8         | 10%     |
| Unknown        | 7         | 8.75%   |
| 51-100         | 5         | 6.25%   |
| 1001-2000      | 4         | 5%      |
| 2001-3000      | 3         | 3.75%   |
| 21-50          | 2         | 2.5%    |
| More than 3000 | 1         | 1.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 28        | 34.57%  |
| 21-50          | 19        | 23.46%  |
| 51-100         | 11        | 13.58%  |
| 101-250        | 8         | 9.88%   |
| Unknown        | 7         | 8.64%   |
| 251-500        | 4         | 4.94%   |
| 501-1000       | 2         | 2.47%   |
| More than 3000 | 1         | 1.23%   |
| 1001-2000      | 1         | 1.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST9750420AS 752GB                        | 1         | 1      | 20%     |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 20%     |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 2      | 20%     |
| Samsung Electronics HD753LJ 752GB                | 1         | 1      | 20%     |
| Hewlett-Packard SSD S700 120GB                   | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 40%     |
| Samsung Electronics | 2         | 3      | 40%     |
| Hewlett-Packard     | 1         | 1      | 20%     |

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
| HDD  | 3         | 3      | 60%     |
| SSD  | 2         | 3      | 40%     |

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
| Works    | 41        | 89     | 48.81%  |
| Detected | 38        | 73     | 45.24%  |
| Malfunc  | 5         | 6      | 5.95%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 50        | 52.63%  |
| Samsung Electronics          | 12        | 12.63%  |
| AMD                          | 6         | 6.32%   |
| SK hynix                     | 4         | 4.21%   |
| Phison Electronics           | 4         | 4.21%   |
| Micron Technology            | 3         | 3.16%   |
| Broadcom / LSI               | 3         | 3.16%   |
| SanDisk                      | 2         | 2.11%   |
| Micron/Crucial Technology    | 2         | 2.11%   |
| VIA Technologies             | 1         | 1.05%   |
| Union Memory (Shenzhen)      | 1         | 1.05%   |
| Transcend                    | 1         | 1.05%   |
| Toshiba America Info Systems | 1         | 1.05%   |
| Lite-On Technology           | 1         | 1.05%   |
| Lenovo                       | 1         | 1.05%   |
| KIOXIA                       | 1         | 1.05%   |
| Kingston Technology Company  | 1         | 1.05%   |
| Adaptec                      | 1         | 1.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8         | 7.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 4.63%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 5         | 4.63%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 3.7%    |
| Phison E12 NVMe Controller                                                              | 3         | 2.78%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 2.78%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 2.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 1.85%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 2         | 1.85%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 1.85%   |
| Intel SSD 660P Series                                                                   | 2         | 1.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 1.85%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2         | 1.85%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2         | 1.85%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2         | 1.85%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2         | 1.85%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2         | 1.85%   |
| Intel Alder Lake-P SATA AHCI Controller                                                 | 2         | 1.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.85%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2         | 1.85%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1         | 0.93%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB                         | 1         | 0.93%   |
| Transcend NVMe PCIe SSD 250H                                                            | 1         | 0.93%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 1         | 0.93%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                      | 1         | 0.93%   |
| SK hynix PC601 NVMe Solid State Drive                                                   | 1         | 0.93%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                                       | 1         | 0.93%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1         | 0.93%   |
| Sandisk PC SN740 NVMe SSD (DRAM-less)                                                   | 1         | 0.93%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 1         | 0.93%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.93%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                             | 1         | 0.93%   |
| Micron 2300 NVMe SSD [Santana]                                                          | 1         | 0.93%   |
| Micron 2200S NVMe SSD [Cassandra]                                                       | 1         | 0.93%   |
| Lite-On CA5-8D512 NVMe SSD                                                              | 1         | 0.93%   |
| Lenovo LENSE30512GMSP34MEAT3TA                                                          | 1         | 0.93%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 1         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 44        | 44.44%  |
| NVMe | 36        | 36.36%  |
| RAID | 9         | 9.09%   |
| IDE  | 6         | 6.06%   |
| SAS  | 3         | 3.03%   |
| SCSI | 1         | 1.01%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 72        | 92.31%  |
| AMD    | 6         | 7.69%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8665U CPU @ 1.90GHz       | 3         | 3.85%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 3         | 3.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 2         | 2.56%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 2         | 2.56%   |
| Intel Core i7-10610U CPU @ 1.80GHz      | 2         | 2.56%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 2         | 2.56%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 2         | 2.56%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 2         | 2.56%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 2         | 2.56%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz    | 1         | 1.28%   |
| Intel Xeon CPU X3450 @ 2.67GHz          | 1         | 1.28%   |
| Intel Xeon CPU X3430 @ 2.40GHz          | 1         | 1.28%   |
| Intel Xeon CPU E5649 @ 2.53GHz          | 1         | 1.28%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz     | 1         | 1.28%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz     | 1         | 1.28%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz     | 1         | 1.28%   |
| Intel Processor 5Y10 CPU @ 0.80GHz      | 1         | 1.28%   |
| Intel Pentium CPU G3240 @ 3.10GHz       | 1         | 1.28%   |
| Intel Pentium CPU G2020 @ 2.90GHz       | 1         | 1.28%   |
| Intel Core i9-9880H CPU @ 2.30GHz       | 1         | 1.28%   |
| Intel Core i9-10900K CPU @ 3.70GHz      | 1         | 1.28%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 1         | 1.28%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 1         | 1.28%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 1         | 1.28%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1.28%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1.28%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 1         | 1.28%   |
| Intel Core i7-6800K CPU @ 3.40GHz       | 1         | 1.28%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 1         | 1.28%   |
| Intel Core i7-4940MX CPU @ 3.10GHz      | 1         | 1.28%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz      | 1         | 1.28%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz      | 1         | 1.28%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 1         | 1.28%   |
| Intel Core i7-2860QM CPU @ 2.50GHz      | 1         | 1.28%   |
| Intel Core i7-2760QM CPU @ 2.40GHz      | 1         | 1.28%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 1         | 1.28%   |
| Intel Core i7-10850H CPU @ 2.70GHz      | 1         | 1.28%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.28%   |
| Intel Core i7-10700K CPU @ 3.80GHz      | 1         | 1.28%   |
| Intel Core i5-9300HF CPU @ 2.40GHz      | 1         | 1.28%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i7     | 27        | 34.62%  |
| Intel Core i5     | 15        | 19.23%  |
| Other             | 13        | 16.67%  |
| Intel Xeon        | 6         | 7.69%   |
| Intel Celeron     | 4         | 5.13%   |
| Intel Pentium     | 2         | 2.56%   |
| Intel Core i9     | 2         | 2.56%   |
| Intel Core i3     | 2         | 2.56%   |
| AMD Ryzen 7       | 2         | 2.56%   |
| Intel Xeon Silver | 1         | 1.28%   |
| Intel Core 2 Duo  | 1         | 1.28%   |
| AMD Ryzen 7 PRO   | 1         | 1.28%   |
| AMD FX            | 1         | 1.28%   |
| AMD A8            | 1         | 1.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 31        | 39.74%  |
| 2      | 23        | 29.49%  |
| 12     | 6         | 7.69%   |
| 6      | 6         | 7.69%   |
| 8      | 4         | 5.13%   |
| 16     | 3         | 3.85%   |
| 10     | 2         | 2.56%   |
| 20     | 1         | 1.28%   |
| 14     | 1         | 1.28%   |
| 1      | 1         | 1.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 74        | 94.87%  |
| 2      | 4         | 5.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 63        | 80.77%  |
| 1      | 15        | 19.23%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 77        | 97.47%  |
| Unknown        | 2         | 2.53%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ec    | 7         | 8.86%   |
| 0x306c3    | 6         | 7.59%   |
| Unknown    | 6         | 7.59%   |
| 0x206a7    | 5         | 6.33%   |
| 0x806ea    | 4         | 5.06%   |
| 0x806c1    | 4         | 5.06%   |
| 0x906a3    | 3         | 3.8%    |
| 0x306d4    | 3         | 3.8%    |
| 0x306a9    | 3         | 3.8%    |
| 0xb06a2    | 2         | 2.53%   |
| 0xa0655    | 2         | 2.53%   |
| 0xa0652    | 2         | 2.53%   |
| 0x906ed    | 2         | 2.53%   |
| 0x906ea    | 2         | 2.53%   |
| 0x806e9    | 2         | 2.53%   |
| 0x706a8    | 2         | 2.53%   |
| 0x506e3    | 2         | 2.53%   |
| 0x406e3    | 2         | 2.53%   |
| 0x40651    | 2         | 2.53%   |
| 0x306e4    | 2         | 2.53%   |
| 0x106e5    | 2         | 2.53%   |
| 0xa0653    | 1         | 1.27%   |
| 0x90672    | 1         | 1.27%   |
| 0x506c9    | 1         | 1.27%   |
| 0x50654    | 1         | 1.27%   |
| 0x406f1    | 1         | 1.27%   |
| 0x406c4    | 1         | 1.27%   |
| 0x206c2    | 1         | 1.27%   |
| 0x20655    | 1         | 1.27%   |
| 0x10676    | 1         | 1.27%   |
| 0x08608103 | 1         | 1.27%   |
| 0x0810100b | 1         | 1.27%   |
| 0x0800820d | 1         | 1.27%   |
| 0x07030105 | 1         | 1.27%   |
| 0x06006705 | 1         | 1.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 19        | 24.36%  |
| Haswell          | 8         | 10.26%  |
| Skylake          | 5         | 6.41%   |
| SandyBridge      | 5         | 6.41%   |
| IvyBridge        | 5         | 6.41%   |
| CometLake        | 5         | 6.41%   |
| Broadwell        | 5         | 6.41%   |
| TigerLake        | 4         | 5.13%   |
| Alderlake Hybrid | 4         | 5.13%   |
| Unknown          | 4         | 5.13%   |
| Westmere         | 2         | 2.56%   |
| Nehalem          | 2         | 2.56%   |
| Goldmont plus    | 2         | 2.56%   |
| Zen+             | 1         | 1.28%   |
| Zen              | 1         | 1.28%   |
| Silvermont       | 1         | 1.28%   |
| Puma             | 1         | 1.28%   |
| Piledriver       | 1         | 1.28%   |
| Penryn           | 1         | 1.28%   |
| Goldmont         | 1         | 1.28%   |
| Excavator        | 1         | 1.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 55        | 57.29%  |
| Nvidia                     | 26        | 27.08%  |
| AMD                        | 11        | 11.46%  |
| Matrox Electronics Systems | 4         | 4.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 5         | 5.21%   |
| Intel UHD Graphics 620                                                      | 4         | 4.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 4.17%   |
| Intel HD Graphics 620                                                       | 4         | 4.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 4         | 4.17%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3         | 3.13%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 3         | 3.13%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 2.08%   |
| Nvidia GM108M [GeForce 930MX]                                               | 2         | 2.08%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 2         | 2.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 2.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 2.08%   |
| Intel HD Graphics 5500                                                      | 2         | 2.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 2.08%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 2.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 2         | 2.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 2         | 2.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2         | 2.08%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                               | 1         | 1.04%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1         | 1.04%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 1         | 1.04%   |
| Nvidia GP107M [GeForce MX350]                                               | 1         | 1.04%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1         | 1.04%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                     | 1         | 1.04%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 1.04%   |
| Nvidia GM204GLM [Quadro M4000M]                                             | 1         | 1.04%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 1         | 1.04%   |
| Nvidia GM108GLM [Quadro K620M / Quadro M500M]                               | 1         | 1.04%   |
| Nvidia GK208GLM [Quadro K610M]                                              | 1         | 1.04%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1         | 1.04%   |
| Nvidia GK110GL [Quadro K6000]                                               | 1         | 1.04%   |
| Nvidia GK107GLM [Quadro K1100M]                                             | 1         | 1.04%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1         | 1.04%   |
| Nvidia GF119M [NVS 4200M]                                                   | 1         | 1.04%   |
| Nvidia GF110GL [Tesla C2050 / C2075]                                        | 1         | 1.04%   |
| Nvidia GA107GLM [RTX A1000 Laptop GPU]                                      | 1         | 1.04%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 1         | 1.04%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1         | 1.04%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 1         | 1.04%   |
| Matrox Electronics Systems MGA G200eH3                                      | 1         | 1.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 37        | 46.84%  |
| 1 x Nvidia     | 13        | 16.46%  |
| Intel + Nvidia | 12        | 15.19%  |
| 1 x AMD        | 6         | 7.59%   |
| 1 x Matrox     | 4         | 5.06%   |
| Intel + AMD    | 3         | 3.8%    |
| Other          | 2         | 2.53%   |
| AMD + Nvidia   | 2         | 2.53%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 66        | 82.5%   |
| Unknown     | 8         | 10%     |
| Proprietary | 6         | 7.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 48        | 60.76%  |
| 1.01-2.0   | 12        | 15.19%  |
| 3.01-4.0   | 10        | 12.66%  |
| 0.51-1.0   | 3         | 3.8%    |
| 0.01-0.5   | 3         | 3.8%    |
| 5.01-6.0   | 2         | 2.53%   |
| 8.01-16.0  | 1         | 1.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 13        | 13.4%   |
| Chimei Innolux       | 11        | 11.34%  |
| Samsung Electronics  | 10        | 10.31%  |
| LG Display           | 9         | 9.28%   |
| Dell                 | 9         | 9.28%   |
| BOE                  | 8         | 8.25%   |
| Lenovo               | 4         | 4.12%   |
| BenQ                 | 4         | 4.12%   |
| ViewSonic            | 3         | 3.09%   |
| InfoVision           | 3         | 3.09%   |
| Hewlett-Packard      | 3         | 3.09%   |
| Acer                 | 3         | 3.09%   |
| ASUSTek Computer     | 2         | 2.06%   |
| Vizio                | 1         | 1.03%   |
| Viotek               | 1         | 1.03%   |
| Sony                 | 1         | 1.03%   |
| Sharp                | 1         | 1.03%   |
| Sceptre Tech         | 1         | 1.03%   |
| SAC                  | 1         | 1.03%   |
| Panasonic            | 1         | 1.03%   |
| Packard Bell         | 1         | 1.03%   |
| Goldstar             | 1         | 1.03%   |
| GameMax              | 1         | 1.03%   |
| Fujitsu Siemens      | 1         | 1.03%   |
| Element              | 1         | 1.03%   |
| Eizo                 | 1         | 1.03%   |
| BOE Technology Group | 1         | 1.03%   |
| Ancor Communications | 1         | 1.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 2.94%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 2         | 1.96%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 2         | 1.96%   |
| Dell U2718Q DELA0E9 3840x2160 610x350mm 27.7-inch                     | 2         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 2         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 2         | 1.96%   |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                     | 2         | 1.96%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch         | 2         | 1.96%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 2         | 1.96%   |
| Acer SA230 ACR057E 1920x1080 509x286mm 23.0-inch                      | 2         | 1.96%   |
| Vizio V705-H3 VIZ1039 3840x2160 1538x865mm 69.5-inch                  | 1         | 0.98%   |
| Viotek SUW49C VTK4900 3840x1080 1196x336mm 48.9-inch                  | 1         | 0.98%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch         | 1         | 0.98%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch              | 1         | 0.98%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 521x293mm 23.5-inch         | 1         | 0.98%   |
| Sony TV SNY4502 1920x1080                                             | 1         | 0.98%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.98%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x291mm 29.5-inch        | 1         | 0.98%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch   | 1         | 0.98%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch  | 1         | 0.98%   |
| Samsung Electronics SAMTRON STN0022 1280x1024 380x300mm 19.1-inch     | 1         | 0.98%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch     | 1         | 0.98%   |
| Samsung Electronics S27D391 SAM0B89 1920x1080 598x336mm 27.0-inch     | 1         | 0.98%   |
| Samsung Electronics S27D391 SAM0B88 1920x1080 598x336mm 27.0-inch     | 1         | 0.98%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.98%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch     | 1         | 0.98%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SDC3256 1920x1080 382x215mm 17.3-inch | 1         | 0.98%   |
| Samsung Electronics LCD Monitor S24C650                               | 1         | 0.98%   |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 697x392mm 31.5-inch     | 1         | 0.98%   |
| SAC DM-MONB2205 SAC952D 1920x1080 450x270mm 20.7-inch                 | 1         | 0.98%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 1         | 0.98%   |
| Packard Bell Viseo223DX PKB037A 1920x1080 477x268mm 21.5-inch         | 1         | 0.98%   |
| LG Display LCD Monitor LGD0628 1920x1080 309x174mm 14.0-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD0609 1920x1080 309x174mm 14.0-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD047C 1366x768 310x174mm 14.0-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 1         | 0.98%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 46        | 55.42%  |
| 3840x2160 (4K)     | 7         | 8.43%   |
| 1366x768 (WXGA)    | 6         | 7.23%   |
| 1920x1200 (WUXGA)  | 4         | 4.82%   |
| 1600x900 (HD+)     | 4         | 4.82%   |
| 1680x1050 (WSXGA+) | 3         | 3.61%   |
| 1280x1024 (SXGA)   | 3         | 3.61%   |
| 2560x1440 (QHD)    | 2         | 2.41%   |
| 3840x2400          | 1         | 1.2%    |
| 3840x1200          | 1         | 1.2%    |
| 3840x1080          | 1         | 1.2%    |
| 2560x1080          | 1         | 1.2%    |
| 1920x540           | 1         | 1.2%    |
| 1360x768           | 1         | 1.2%    |
| 1280x800 (WXGA)    | 1         | 1.2%    |
| Unknown            | 1         | 1.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 18        | 18.37%  |
| 14      | 14        | 14.29%  |
| 27      | 11        | 11.22%  |
| 13      | 10        | 10.2%   |
| 24      | 9         | 9.18%   |
| 23      | 6         | 6.12%   |
| 21      | 4         | 4.08%   |
| Unknown | 4         | 4.08%   |
| 38      | 2         | 2.04%   |
| 31      | 2         | 2.04%   |
| 22      | 2         | 2.04%   |
| 19      | 2         | 2.04%   |
| 17      | 2         | 2.04%   |
| 84      | 1         | 1.02%   |
| 72      | 1         | 1.02%   |
| 69      | 1         | 1.02%   |
| 48      | 1         | 1.02%   |
| 32      | 1         | 1.02%   |
| 29      | 1         | 1.02%   |
| 25      | 1         | 1.02%   |
| 20      | 1         | 1.02%   |
| 18      | 1         | 1.02%   |
| 16      | 1         | 1.02%   |
| 12      | 1         | 1.02%   |
| 11      | 1         | 1.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 41        | 43.62%  |
| 501-600     | 24        | 25.53%  |
| 401-500     | 7         | 7.45%   |
| 601-700     | 4         | 4.26%   |
| 201-300     | 4         | 4.26%   |
| Unknown     | 4         | 4.26%   |
| 351-400     | 3         | 3.19%   |
| 1501-2000   | 3         | 3.19%   |
| 801-900     | 2         | 2.13%   |
| 701-800     | 1         | 1.06%   |
| 1001-1500   | 1         | 1.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 61        | 78.21%  |
| 16/10   | 9         | 11.54%  |
| 5/4     | 3         | 3.85%   |
| 32/9    | 2         | 2.56%   |
| Unknown | 2         | 2.56%   |
| 21/9    | 1         | 1.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 22        | 23.16%  |
| 101-110        | 18        | 18.95%  |
| 201-250        | 16        | 16.84%  |
| 301-350        | 12        | 12.63%  |
| 151-200        | 4         | 4.21%   |
| Unknown        | 4         | 4.21%   |
| More than 1000 | 3         | 3.16%   |
| 351-500        | 3         | 3.16%   |
| 501-1000       | 3         | 3.16%   |
| 71-80          | 2         | 2.11%   |
| 251-300        | 2         | 2.11%   |
| 121-130        | 2         | 2.11%   |
| 61-70          | 1         | 1.05%   |
| 51-60          | 1         | 1.05%   |
| 141-150        | 1         | 1.05%   |
| 111-120        | 1         | 1.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 38        | 41.76%  |
| 51-100        | 30        | 32.97%  |
| 101-120       | 12        | 13.19%  |
| 161-240       | 5         | 5.49%   |
| Unknown       | 4         | 4.4%    |
| More than 240 | 1         | 1.1%    |
| 1-50          | 1         | 1.1%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 43        | 54.43%  |
| 2     | 18        | 22.78%  |
| 0     | 10        | 12.66%  |
| 3     | 7         | 8.86%   |
| 4     | 1         | 1.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 61        | 55.45%  |
| Realtek Semiconductor | 27        | 24.55%  |
| Broadcom              | 5         | 4.55%   |
| Qualcomm Atheros      | 4         | 3.64%   |
| Lenovo                | 3         | 2.73%   |
| Broadcom Limited      | 2         | 1.82%   |
| Samsung Electronics   | 1         | 0.91%   |
| Ralink Technology     | 1         | 0.91%   |
| QLogic                | 1         | 0.91%   |
| NetGear               | 1         | 0.91%   |
| Mellanox Technologies | 1         | 0.91%   |
| Fibocom               | 1         | 0.91%   |
| ASUSTek Computer      | 1         | 0.91%   |
| ASIX Electronics      | 1         | 0.91%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 9.59%   |
| Intel Wireless 8265 / 8275                                        | 8         | 5.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 4.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 4.11%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 3.42%   |
| Intel Wireless 8260                                               | 4         | 2.74%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 2.74%   |
| Intel Wireless 7265                                               | 3         | 2.05%   |
| Intel Wireless 7260                                               | 3         | 2.05%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 2.05%   |
| Intel I211 Gigabit Network Connection                             | 3         | 2.05%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 2.05%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 2.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 2.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 2.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 2.05%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 2.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.37%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 1.37%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 2         | 1.37%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.37%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.37%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.37%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.37%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.68%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.68%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.68%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1         | 0.68%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.68%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.68%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.68%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.68%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.68%   |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller          | 1         | 0.68%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                   | 1         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 49        | 74.24%  |
| Realtek Semiconductor | 7         | 10.61%  |
| Qualcomm Atheros      | 4         | 6.06%   |
| Ralink Technology     | 1         | 1.52%   |
| NetGear               | 1         | 1.52%   |
| Fibocom               | 1         | 1.52%   |
| Broadcom Limited      | 1         | 1.52%   |
| Broadcom              | 1         | 1.52%   |
| ASUSTek Computer      | 1         | 1.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                           | 8         | 12.12%  |
| Intel Wireless 8260                                                  | 4         | 6.06%   |
| Intel Wireless 7265                                                  | 3         | 4.55%   |
| Intel Wireless 7260                                                  | 3         | 4.55%   |
| Intel Wi-Fi 6 AX201                                                  | 3         | 4.55%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3         | 4.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 3         | 4.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 3         | 4.55%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 3         | 4.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 3.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 2         | 3.03%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 2         | 3.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 2         | 3.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 2         | 3.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 1         | 1.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 1.52%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.52%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 1         | 1.52%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 1.52%   |
| Ralink MT7601U Wireless Adapter                                      | 1         | 1.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1         | 1.52%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 1         | 1.52%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                      | 1         | 1.52%   |
| Intel Wireless-AC 9260                                               | 1         | 1.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 1         | 1.52%   |
| Intel Wi-Fi 6 AX200                                                  | 1         | 1.52%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 1         | 1.52%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection              | 1         | 1.52%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 1         | 1.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1         | 1.52%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 1         | 1.52%   |
| Intel Centrino Ultimate-N 6300                                       | 1         | 1.52%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 1         | 1.52%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                    | 1         | 1.52%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 1         | 1.52%   |
| Broadcom BCM43142 802.11b/g/n                                        | 1         | 1.52%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]            | 1         | 1.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 41        | 53.95%  |
| Realtek Semiconductor | 23        | 30.26%  |
| Broadcom              | 4         | 5.26%   |
| Lenovo                | 3         | 3.95%   |
| Samsung Electronics   | 1         | 1.32%   |
| QLogic                | 1         | 1.32%   |
| Mellanox Technologies | 1         | 1.32%   |
| Broadcom Limited      | 1         | 1.32%   |
| ASIX Electronics      | 1         | 1.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 17.5%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 7.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 7.5%    |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 6.25%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 5%      |
| Intel I211 Gigabit Network Connection                             | 3         | 3.75%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 3.75%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 3.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.5%    |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 2.5%    |
| Intel Ethernet Controller I225-V                                  | 2         | 2.5%    |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 2.5%    |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 2.5%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.25%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.25%   |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller          | 1         | 1.25%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 1         | 1.25%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 1.25%   |
| Intel Ethernet Controller I226-V                                  | 1         | 1.25%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.25%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.25%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.25%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.25%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.25%   |
| Intel Ethernet Connection (17) I219-V                             | 1         | 1.25%   |
| Intel Ethernet Connection (17) I219-LM                            | 1         | 1.25%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.25%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.25%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection             | 1         | 1.25%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 1.25%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 1.25%   |
| Intel 82571EB Gigabit Ethernet Controller                         | 1         | 1.25%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1         | 1.25%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.25%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 1.25%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 1.25%   |
| Broadcom BCM57840 NetXtreme II 10/20-Gigabit Ethernet             | 1         | 1.25%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 66        | 51.97%  |
| WiFi     | 61        | 48.03%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 43        | 53.75%  |
| WiFi     | 37        | 46.25%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 48        | 61.54%  |
| 1     | 26        | 33.33%  |
| 4     | 2         | 2.56%   |
| 6     | 1         | 1.28%   |
| 3     | 1         | 1.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 62        | 75.61%  |
| Yes  | 20        | 24.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 71.43%  |
| Realtek Semiconductor           | 3         | 6.12%   |
| Qualcomm Atheros Communications | 3         | 6.12%   |
| Broadcom                        | 3         | 6.12%   |
| ASUSTek Computer                | 2         | 4.08%   |
| IMC Networks                    | 1         | 2.04%   |
| Apple                           | 1         | 2.04%   |
| Alps Electric                   | 1         | 2.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 13        | 26.53%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 7         | 14.29%  |
| Intel Bluetooth Device                         | 6         | 12.24%  |
| Intel AX201 Bluetooth                          | 6         | 12.24%  |
| Realtek  Bluetooth 4.2 Adapter                 | 2         | 4.08%   |
| Qualcomm Atheros  Bluetooth Device             | 2         | 4.08%   |
| ASUS Broadcom BCM20702A0 Bluetooth             | 2         | 4.08%   |
| Realtek Bluetooth Radio                        | 1         | 2.04%   |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 2.04%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1         | 2.04%   |
| Intel Wireless-AC 3168 Bluetooth               | 1         | 2.04%   |
| Intel AX210 Bluetooth                          | 1         | 2.04%   |
| IMC Networks Bluetooth Radio                   | 1         | 2.04%   |
| Broadcom BCM43142A0 Bluetooth 4.0              | 1         | 2.04%   |
| Broadcom BCM20702A0 Bluetooth 4.0              | 1         | 2.04%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 2.04%   |
| Apple Bluetooth Host Controller                | 1         | 2.04%   |
| Alps Electric UGTZ4 Bluetooth                  | 1         | 2.04%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 66        | 58.41%  |
| Nvidia                 | 18        | 15.93%  |
| AMD                    | 10        | 8.85%   |
| Lenovo                 | 5         | 4.42%   |
| GN Netcom              | 5         | 4.42%   |
| C-Media Electronics    | 2         | 1.77%   |
| Unknown                | 1         | 0.88%   |
| TEAC                   | 1         | 0.88%   |
| Realtek Semiconductor  | 1         | 0.88%   |
| Plantronics            | 1         | 0.88%   |
| M-Audio                | 1         | 0.88%   |
| JMTek                  | 1         | 0.88%   |
| AKAI Professional M.I. | 1         | 0.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 10        | 7.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 4.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 4.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 3.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 3.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 3.1%    |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 3.1%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 2.33%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 2.33%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 2.33%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 2.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.55%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 1.55%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 1.55%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 1.55%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.55%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 2         | 1.55%   |
| Lenovo ThinkPad Dock USB Audio                                             | 2         | 1.55%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 2         | 1.55%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 2         | 1.55%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.55%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.55%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.55%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2         | 1.55%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 1.55%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 1.55%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.55%   |
| GN Netcom Jabra EVOLVE LINK                                                | 2         | 1.55%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2         | 1.55%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 1.55%   |
| Unknown Definitive Sym1                                                    | 1         | 0.78%   |
| TEAC US-2x2                                                                | 1         | 0.78%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.78%   |
| Plantronics BT600                                                          | 1         | 0.78%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.78%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.78%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.78%   |
| Nvidia GK110 High Definition Audio Controller                              | 1         | 0.78%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 12        | 23.53%  |
| Micron Technology                       | 10        | 19.61%  |
| SK hynix                                | 8         | 15.69%  |
| Kingston                                | 5         | 9.8%    |
| Unknown                                 | 3         | 5.88%   |
| Crucial                                 | 3         | 5.88%   |
| Unknown                                 | 2         | 3.92%   |
| Unigen                                  | 1         | 1.96%   |
| Smart                                   | 1         | 1.96%   |
| Silicon Power Computer & Communications | 1         | 1.96%   |
| Nanya Technology                        | 1         | 1.96%   |
| HPE                                     | 1         | 1.96%   |
| Corsair                                 | 1         | 1.96%   |
| Avant                                   | 1         | 1.96%   |
| 4ea5                                    | 1         | 1.96%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s           | 3         | 5.45%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s            | 2         | 3.64%   |
| Unknown                                                         | 2         | 3.64%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 1.82%   |
| Unknown RAM Module 4GB DIMM DDR3 800MT/s                        | 1         | 1.82%   |
| Unknown RAM Module 32GB SODIMM DDR4 2667MT/s                    | 1         | 1.82%   |
| Unigen RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 1.82%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s           | 1         | 1.82%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s       | 1         | 1.82%   |
| SK hynix RAM HMT31GR7BFR4A-H9 8192MB DIMM 1333MT/s              | 1         | 1.82%   |
| SK hynix RAM HMAA1GS6CMR8N-VK 8192MB Row Of Chips DDR4 2667MT/s | 1         | 1.82%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s    | 1         | 1.82%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.82%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s          | 1         | 1.82%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 1         | 1.82%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s          | 1         | 1.82%   |
| SK hynix RAM H9HCNNNBKUMLXR-NEE 2GB LPDDR4 2400MT/s             | 1         | 1.82%   |
| Silicon Power & RAM Module 16GB SODIMM DDR4 2667MT/s            | 1         | 1.82%   |
| Samsung RAM Module 8GB SODIMM DDR5 4800MT/s                     | 1         | 1.82%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.82%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s          | 1         | 1.82%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s          | 1         | 1.82%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s          | 1         | 1.82%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s           | 1         | 1.82%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s           | 1         | 1.82%   |
| Samsung RAM M393B2G70BH0-YH9 16GB DIMM DDR3 1333MT/s            | 1         | 1.82%   |
| Samsung RAM M393B2G70BH0-CK0 16GB DIMM 1600MT/s                 | 1         | 1.82%   |
| Nanya RAM NT8GA64D88AX3S-HR 8GB SODIMM DDR4 2667MT/s            | 1         | 1.82%   |
| Micron RAM Module 16384MB SODIMM DDR4 2400MT/s                  | 1         | 1.82%   |
| Micron RAM 8ATF1G64AZ-2G3H1 8GB DIMM DDR4 2448MT/s              | 1         | 1.82%   |
| Micron RAM 8ATF1G64AZ-2G3E1 8192MB DIMM DDR4 2400MT/s           | 1         | 1.82%   |
| Micron RAM 8ATF1G64AZ-2G3B1 8GB DIMM DDR4 2448MT/s              | 1         | 1.82%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s     | 1         | 1.82%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s           | 1         | 1.82%   |
| Micron RAM 4ATF1G64AZ-3G2F1 8GB DIMM DDR4 3200MT/s              | 1         | 1.82%   |
| Micron RAM 18ASF2G72PDZ-2G3B1 16GB DIMM DDR4 2400MT/s           | 1         | 1.82%   |
| Micron RAM 16JTF1G64HZ-1G4D1 8GB SODIMM DDR3 1333MT/s           | 1         | 1.82%   |
| Micron RAM 16ATF2G64HZ-2G1A1 16GB SODIMM DDR4 2133MT/s          | 1         | 1.82%   |
| Kingston RAM KX830D-ELC 4GB SODIMM DDR3 1333MT/s                | 1         | 1.82%   |
| Kingston RAM KTW149-ELF 1GB DIMM DDR3 1333MT/s                  | 1         | 1.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 27        | 57.45%  |
| DDR3   | 15        | 31.91%  |
| LPDDR5 | 2         | 4.26%   |
| LPDDR4 | 2         | 4.26%   |
| DDR5   | 1         | 2.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 30        | 63.83%  |
| DIMM         | 11        | 23.4%   |
| Row Of Chips | 5         | 10.64%  |
| Unknown      | 1         | 2.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 20        | 40.82%  |
| 16384 | 13        | 26.53%  |
| 4096  | 11        | 22.45%  |
| 32768 | 3         | 6.12%   |
| 2048  | 1         | 2.04%   |
| 1024  | 1         | 2.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 13        | 26.53%  |
| 1600  | 8         | 16.33%  |
| 1333  | 7         | 14.29%  |
| 3200  | 6         | 12.24%  |
| 2400  | 5         | 10.2%   |
| 6400  | 2         | 4.08%   |
| 4800  | 1         | 2.04%   |
| 4267  | 1         | 2.04%   |
| 3466  | 1         | 2.04%   |
| 2666  | 1         | 2.04%   |
| 2448  | 1         | 2.04%   |
| 2133  | 1         | 2.04%   |
| 1866  | 1         | 2.04%   |
| 800   | 1         | 2.04%   |

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
| Chicony Electronics                    | 11        | 24.44%  |
| Logitech                               | 6         | 13.33%  |
| IMC Networks                           | 6         | 13.33%  |
| Realtek Semiconductor                  | 4         | 8.89%   |
| Suyin                                  | 3         | 6.67%   |
| Microdia                               | 3         | 6.67%   |
| Lite-On Technology                     | 3         | 6.67%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.44%   |
| Bison Electronics                      | 2         | 4.44%   |
| Quanta                                 | 1         | 2.22%   |
| Microsoft                              | 1         | 2.22%   |
| Luxvisions Innotech Limited            | 1         | 2.22%   |
| DLTDC0A9II090N                         | 1         | 2.22%   |
| Apple                                  | 1         | 2.22%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 7         | 15.22%  |
| IMC Networks Integrated Camera                                  | 3         | 6.52%   |
| Realtek Integrated_Webcam_HD                                    | 2         | 4.35%   |
| Microdia Webcam Vitade AF                                       | 2         | 4.35%   |
| Lite-On Integrated Camera                                       | 2         | 4.35%   |
| IMC Networks VGA UVC WebCam                                     | 2         | 4.35%   |
| Chicony Integrated Camera (1280x720@30)                         | 2         | 4.35%   |
| Bison SunplusIT Integrated Camera                               | 2         | 4.35%   |
| Suyin Integrated_Webcam_HD                                      | 1         | 2.17%   |
| Suyin HP Truevision HD                                          | 1         | 2.17%   |
| Suyin Asus Integrated Webcam                                    | 1         | 2.17%   |
| Realtek Integrated_Webcam_FHD                                   | 1         | 2.17%   |
| Realtek EasyCamera                                              | 1         | 2.17%   |
| Quanta HP Webcam                                                | 1         | 2.17%   |
| Microsoft LifeCam HD-3000                                       | 1         | 2.17%   |
| Microdia Integrated_Webcam_HD                                   | 1         | 2.17%   |
| Luxvisions Innotech Limited EasyCamera 1M                       | 1         | 2.17%   |
| Logitech Webcam C925e                                           | 1         | 2.17%   |
| Logitech Webcam C920-C                                          | 1         | 2.17%   |
| Logitech Webcam C270                                            | 1         | 2.17%   |
| Logitech HD Webcam C615                                         | 1         | 2.17%   |
| Logitech HD Webcam C510                                         | 1         | 2.17%   |
| Logitech BRIO Ultra HD Webcam                                   | 1         | 2.17%   |
| Lite-On HP HD Camera                                            | 1         | 2.17%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 1         | 2.17%   |
| DLTDC0A9II090N HP 5MP Camera                                    | 1         | 2.17%   |
| Chicony TOSHIBA Web Camera - HD                                 | 1         | 2.17%   |
| Chicony ThinkPad T490 Webcam                                    | 1         | 2.17%   |
| Chicony Integrated IR Camera                                    | 1         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera | 1         | 2.17%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                 | 1         | 2.17%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 40%     |
| Synaptics                  | 8         | 40%     |
| Shenzhen Goodix Technology | 2         | 10%     |
| Upek                       | 1         | 5%      |
| Elan Microelectronics      | 1         | 5%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 15%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 15%     |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 15%     |
| Validity Sensors Synaptics WBDI                                            | 2         | 10%     |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 10%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 5%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 5%      |
| Synaptics WBDI                                                             | 1         | 5%      |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 5%      |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 5%      |
| Shenzhen Goodix FingerPrint                                                | 1         | 5%      |
| Elan ELAN:Fingerprint                                                      | 1         | 5%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 7         | 77.78%  |
| Alcor Micro | 2         | 22.22%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 37        | 46.25%  |
| 1     | 28        | 35%     |
| 2     | 10        | 12.5%   |
| 3     | 4         | 5%      |
| 7     | 1         | 1.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 20        | 32.79%  |
| Graphics card            | 10        | 16.39%  |
| Net/wireless             | 7         | 11.48%  |
| Chipcard                 | 7         | 11.48%  |
| Unassigned class         | 3         | 4.92%   |
| Communication controller | 3         | 4.92%   |
| Card reader              | 3         | 4.92%   |
| Bluetooth                | 3         | 4.92%   |
| Storage                  | 2         | 3.28%   |
| Sound                    | 2         | 3.28%   |
| Multimedia controller    | 1         | 1.64%   |

