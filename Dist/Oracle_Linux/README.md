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

Total: 144

| Vendor     | Model                       | Form-Factor | Probe                                                      | Date         |
|------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Unknown    | Unknown                     | Desktop     | [806e7d1dfa](https://linux-hardware.org/?probe=806e7d1dfa) | Apr 28, 2024 |
| Gigabyte   | B450M DS3H-CF               | Desktop     | [cf6c011819](https://linux-hardware.org/?probe=cf6c011819) | Apr 13, 2024 |
| Dell       | 0D28YY A03                  | Desktop     | [894b628494](https://linux-hardware.org/?probe=894b628494) | Apr 12, 2024 |
| Lenovo     | ThinkPad P16s Gen 1 21BT... | Notebook    | [97c2387841](https://linux-hardware.org/?probe=97c2387841) | Apr 12, 2024 |
| Lenovo     | ThinkPad P16s Gen 1 21BT... | Notebook    | [e47633811b](https://linux-hardware.org/?probe=e47633811b) | Apr 12, 2024 |
| ASUSTek    | X541SA                      | Notebook    | [23ea4a0287](https://linux-hardware.org/?probe=23ea4a0287) | Apr 09, 2024 |
| ASUSTek    | X541SA                      | Notebook    | [0f5bd53c6f](https://linux-hardware.org/?probe=0f5bd53c6f) | Apr 08, 2024 |
| ASUSTek    | X541SA                      | Notebook    | [b3f083db5c](https://linux-hardware.org/?probe=b3f083db5c) | Apr 06, 2024 |
| ASUSTek    | PRIME B250M-A               | Desktop     | [5d12c5c26e](https://linux-hardware.org/?probe=5d12c5c26e) | Mar 31, 2024 |
| ASUSTek    | PRIME B250M-A               | Desktop     | [142a42435b](https://linux-hardware.org/?probe=142a42435b) | Mar 30, 2024 |
| HP         | EliteBook 640 14 inch G1... | Notebook    | [90a116696c](https://linux-hardware.org/?probe=90a116696c) | Mar 24, 2024 |
| Lenovo     | ThinkBook 15-IIL 20SM       | Notebook    | [692db635b4](https://linux-hardware.org/?probe=692db635b4) | Mar 23, 2024 |
| HP         | ProLiant ML110 Gen9         | Desktop     | [c2f9d107ed](https://linux-hardware.org/?probe=c2f9d107ed) | Mar 02, 2024 |
| HP         | ProLiant ML310e Gen8 v2     | Desktop     | [1b3629654d](https://linux-hardware.org/?probe=1b3629654d) | Mar 02, 2024 |
| HP         | ZBook Fury 15.6 inch G8 ... | Notebook    | [b27420dd64](https://linux-hardware.org/?probe=b27420dd64) | Feb 21, 2024 |
| Dell       | Latitude 7420               | Notebook    | [30e1dc7b9f](https://linux-hardware.org/?probe=30e1dc7b9f) | Feb 13, 2024 |
| Lenovo     | ThinkPad Yoga 370 20JJS0... | Convertible | [3ae3d26304](https://linux-hardware.org/?probe=3ae3d26304) | Jan 21, 2024 |
| Lenovo     | ThinkPad Yoga 370 20JJS0... | Convertible | [b244483cc6](https://linux-hardware.org/?probe=b244483cc6) | Jan 20, 2024 |
| Dell       | Latitude 7430               | Notebook    | [153f1a144c](https://linux-hardware.org/?probe=153f1a144c) | Jan 19, 2024 |
| Dell       | Latitude 7430               | Notebook    | [a05210eeb4](https://linux-hardware.org/?probe=a05210eeb4) | Jan 19, 2024 |
| Lenovo     | ThinkPad T490 20N3S3XR00    | Notebook    | [63ec999c70](https://linux-hardware.org/?probe=63ec999c70) | Jan 16, 2024 |
| ASRock     | B760M-STX                   | Desktop     | [1648b583d6](https://linux-hardware.org/?probe=1648b583d6) | Jan 10, 2024 |
| Lenovo     | ThinkPad W520 42844DG       | Notebook    | [52cd813233](https://linux-hardware.org/?probe=52cd813233) | Dec 20, 2023 |
| HP         | ZBook Fury 15.6 inch G8 ... | Notebook    | [58ad170a68](https://linux-hardware.org/?probe=58ad170a68) | Dec 10, 2023 |
| Dell       | XPS 15 9570                 | Notebook    | [35a10a1ae2](https://linux-hardware.org/?probe=35a10a1ae2) | Dec 10, 2023 |
| ASUSTek    | G15CF                       | Desktop     | [c2b88beb62](https://linux-hardware.org/?probe=c2b88beb62) | Dec 02, 2023 |
| Toshiba    | TECRA R950                  | Notebook    | [8ab7278f60](https://linux-hardware.org/?probe=8ab7278f60) | Dec 01, 2023 |
| Toshiba    | TECRA R950                  | Notebook    | [9634f68cab](https://linux-hardware.org/?probe=9634f68cab) | Dec 01, 2023 |
| ASRock     | B550M Steel Legend          | Desktop     | [9cb8304240](https://linux-hardware.org/?probe=9cb8304240) | Nov 24, 2023 |
| ASRock     | B550M Steel Legend          | Desktop     | [8cfb18380e](https://linux-hardware.org/?probe=8cfb18380e) | Nov 24, 2023 |
| Dell       | XPS 15 9570                 | Notebook    | [7728d0ab4b](https://linux-hardware.org/?probe=7728d0ab4b) | Nov 22, 2023 |
| HP         | EliteBook 840 G4            | Notebook    | [7d2d46e750](https://linux-hardware.org/?probe=7d2d46e750) | Nov 17, 2023 |
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
| Oracle Linux 8.5 | 13        | 12.04%  |
| Oracle Linux 9.3 | 12        | 11.11%  |
| Oracle Linux 8.3 | 12        | 11.11%  |
| Oracle Linux 9.2 | 10        | 9.26%   |
| Oracle Linux 8.9 | 9         | 8.33%   |
| Oracle Linux 8.8 | 7         | 6.48%   |
| Oracle Linux 8.4 | 7         | 6.48%   |
| Oracle Linux 8.6 | 6         | 5.56%   |
| Oracle Linux 9.1 | 5         | 4.63%   |
| Oracle Linux 9.0 | 5         | 4.63%   |
| Oracle Linux 8.7 | 5         | 4.63%   |
| Oracle Linux 7.9 | 4         | 3.7%    |
| Oracle Linux 8.1 | 3         | 2.78%   |
| Oracle Linux 7.7 | 3         | 2.78%   |
| Oracle Linux 8.2 | 2         | 1.85%   |
| Oracle Linux 7.8 | 2         | 1.85%   |
| Oracle Linux 7.6 | 2         | 1.85%   |
| Oracle Linux 7.4 | 1         | 0.93%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Oracle Linux | 99        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                           | Computers | Percent |
|-----------------------------------|-----------|---------|
| 5.15.0-200.131.27.el9uek.x86_64   | 4         | 3.45%   |
| 5.4.17-2102.202.5.el8uek.x86_64   | 3         | 2.59%   |
| 5.4.17-2036.103.3.1.el8uek.x86_64 | 3         | 2.59%   |
| 5.15.0-2.52.3.el9uek.x86_64       | 3         | 2.59%   |
| 5.15.0-101.103.2.1.el9uek.x86_64  | 3         | 2.59%   |
| 5.15.0-100.96.32.el8uek.x86_64    | 3         | 2.59%   |
| 4.18.0-348.12.2.el8_5.x86_64      | 3         | 2.59%   |
| 5.4.17-2136.313.6.el8uek.x86_64   | 2         | 1.72%   |
| 5.4.17-2136.304.4.3.el8uek.x86_64 | 2         | 1.72%   |
| 5.4.17-2136.300.7.el8uek.x86_64   | 2         | 1.72%   |
| 5.4.17-2102.205.7.3.el8uek.x86_64 | 2         | 1.72%   |
| 5.4.17-2102.200.13.el8uek.x86_64  | 2         | 1.72%   |
| 5.4.17-2036.102.0.2.el8uek.x86_64 | 2         | 1.72%   |
| 5.4.17-2036.101.2.el8uek.x86_64   | 2         | 1.72%   |
| 5.15.0-205.149.5.1.el9uek.x86_64  | 2         | 1.72%   |
| 5.15.0-200.131.27.el8uek.x86_64   | 2         | 1.72%   |
| 5.15.0-200.131.27.1.el8uek.x86_64 | 2         | 1.72%   |
| 5.15.0-106.131.4.el9uek.x86_64    | 2         | 1.72%   |
| 5.15.0-103.114.4.el8uek.x86_64    | 2         | 1.72%   |
| 4.18.0-240.15.1.el8_3.x86_64      | 2         | 1.72%   |
| 4.18.0-193.1.2.el8_2.x86_64       | 2         | 1.72%   |
| 4.18.0-147.3.1.el8_1.x86_64       | 2         | 1.72%   |
| 5.4.17-2136.326.6.el8uek.x86_64   | 1         | 0.86%   |
| 5.4.17-2136.318.7.2.el8uek.x86_64 | 1         | 0.86%   |
| 5.4.17-2136.312.3.4.el7uek.x86_64 | 1         | 0.86%   |
| 5.4.17-2136.310.7.el8uek.x86_64   | 1         | 0.86%   |
| 5.4.17-2136.310.7.1.el8uek.x86_64 | 1         | 0.86%   |
| 5.4.17-2136.309.4.el8uek.x86_64   | 1         | 0.86%   |
| 5.4.17-2136.308.9.el8uek.x86_64   | 1         | 0.86%   |
| 5.4.17-2136.308.9.el7uek.x86_64   | 1         | 0.86%   |
| 5.4.17-2136.307.3.1.el8uek.x86_64 | 1         | 0.86%   |
| 5.4.17-2136.306.1.3.el8uek.x86_64 | 1         | 0.86%   |
| 5.4.17-2136.305.5.4.el8uek.x86_64 | 1         | 0.86%   |
| 5.4.17-2136.305.5.3.el8uek.x86_64 | 1         | 0.86%   |
| 5.4.17-2136.305.5.2.el8uek.x86_64 | 1         | 0.86%   |
| 5.4.17-2136.301.1.4.el8uek.x86_64 | 1         | 0.86%   |
| 5.4.17-2102.204.4.4.el8uek.x86_64 | 1         | 0.86%   |
| 5.4.17-2102.204.4.2.el8uek.x86_64 | 1         | 0.86%   |
| 5.4.17-2102.201.3.el8uek.x86_64   | 1         | 0.86%   |
| 5.4.17-2036.104.4.el8uek.x86_64   | 1         | 0.86%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 34        | 33.66%  |
| 5.4.17  | 30        | 29.7%   |
| 4.18.0  | 18        | 17.82%  |
| 5.14.0  | 6         | 5.94%   |
| 4.14.35 | 5         | 4.95%   |
| 3.10.0  | 3         | 2.97%   |
| 5.4.11  | 1         | 0.99%   |
| 5.15.2  | 1         | 0.99%   |
| 5.14.1  | 1         | 0.99%   |
| 5.11.1  | 1         | 0.99%   |
| 4.1.12  | 1         | 0.99%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 35        | 34.65%  |
| 5.4     | 31        | 30.69%  |
| 4.18    | 18        | 17.82%  |
| 5.14    | 7         | 6.93%   |
| 4.14    | 5         | 4.95%   |
| 3.10    | 3         | 2.97%   |
| 5.11    | 1         | 0.99%   |
| 4.1     | 1         | 0.99%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 99        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 74        | 71.84%  |
| Unknown       | 14        | 13.59%  |
| GNOME Classic | 5         | 4.85%   |
| KDE5          | 4         | 3.88%   |
| XFCE          | 2         | 1.94%   |
| MATE          | 2         | 1.94%   |
| KDE4          | 2         | 1.94%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 54        | 52.94%  |
| X11     | 36        | 35.29%  |
| Unknown | 9         | 8.82%   |
| Tty     | 2         | 1.96%   |
| Web     | 1         | 0.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 50        | 49.5%   |
| Unknown | 47        | 46.53%  |
| SDDM    | 3         | 2.97%   |
| TDM     | 1         | 0.99%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 60        | 60%     |
| en_GB      | 11        | 11%     |
| Unknown    | 5         | 5%      |
| de_DE      | 4         | 4%      |
| ru_RU      | 3         | 3%      |
| pt_BR      | 3         | 3%      |
| pl_PL      | 3         | 3%      |
| it_IT      | 3         | 3%      |
| en_AU      | 3         | 3%      |
| en_IN      | 2         | 2%      |
| zh_HK      | 1         | 1%      |
| en_US.UTF8 | 1         | 1%      |
| en_DE      | 1         | 1%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 63        | 63%     |
| BIOS | 37        | 37%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 85        | 84.16%  |
| Ext4    | 12        | 11.88%  |
| Unknown | 2         | 1.98%   |
| Zfs     | 1         | 0.99%   |
| Btrfs   | 1         | 0.99%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 50        | 49.5%   |
| Unknown | 37        | 36.63%  |
| MBR     | 14        | 13.86%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 92        | 92%     |
| Yes       | 8         | 8%      |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 91        | 91%     |
| Yes       | 9         | 9%      |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 26        | 26.26%  |
| Dell                | 19        | 19.19%  |
| Hewlett-Packard     | 16        | 16.16%  |
| ASUSTek Computer    | 12        | 12.12%  |
| Gigabyte Technology | 5         | 5.05%   |
| Intel               | 4         | 4.04%   |
| ASRock              | 3         | 3.03%   |
| MSI                 | 2         | 2.02%   |
| Toshiba             | 1         | 1.01%   |
| Supermicro          | 1         | 1.01%   |
| Standard            | 1         | 1.01%   |
| Panasonic           | 1         | 1.01%   |
| HPE                 | 1         | 1.01%   |
| Google              | 1         | 1.01%   |
| Fujitsu             | 1         | 1.01%   |
| Foxconn             | 1         | 1.01%   |
| Dynabook            | 1         | 1.01%   |
| Cisco               | 1         | 1.01%   |
| Apple               | 1         | 1.01%   |
| Unknown             | 1         | 1.01%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Lenovo ThinkPad T450 20BUS14900           | 2         | 2.02%   |
| Dell Latitude 7430                        | 2         | 2.02%   |
| Dell Latitude 7420                        | 2         | 2.02%   |
| ASUS X510UR                               | 2         | 2.02%   |
| Toshiba TECRA R950                        | 1         | 1.01%   |
| Supermicro X8DTU                          | 1         | 1.01%   |
| Standard BW Series                        | 1         | 1.01%   |
| Panasonic CF-53AAG54FM                    | 1         | 1.01%   |
| MSI P65 Creator 8RE                       | 1         | 1.01%   |
| MSI MS-7758                               | 1         | 1.01%   |
| Lenovo ThinkPad Yoga 370 20JJS0A44R       | 1         | 1.01%   |
| Lenovo ThinkPad X390 Yoga 20NQS2SF00      | 1         | 1.01%   |
| Lenovo ThinkPad X280 20KES4H34G           | 1         | 1.01%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QWS1R800 | 1         | 1.01%   |
| Lenovo ThinkPad W541 20EGS1PL00           | 1         | 1.01%   |
| Lenovo ThinkPad W520 42844DG              | 1         | 1.01%   |
| Lenovo ThinkPad T490 20N3S77600           | 1         | 1.01%   |
| Lenovo ThinkPad T490 20N3S3XR00           | 1         | 1.01%   |
| Lenovo ThinkPad T480 20L6S56Y2X           | 1         | 1.01%   |
| Lenovo ThinkPad T480 20L5A07TAU           | 1         | 1.01%   |
| Lenovo ThinkPad T470 20HES21434           | 1         | 1.01%   |
| Lenovo ThinkPad T470 20HES0E71M           | 1         | 1.01%   |
| Lenovo ThinkPad T430s 2355C33             | 1         | 1.01%   |
| Lenovo ThinkPad P70 20ESS04S00            | 1         | 1.01%   |
| Lenovo ThinkPad P50s 20FL000MUS           | 1         | 1.01%   |
| Lenovo ThinkPad P16s Gen 1 21BTS0FR00     | 1         | 1.01%   |
| Lenovo ThinkPad L540 20AVCTO1WW           | 1         | 1.01%   |
| Lenovo ThinkPad L490 20Q5CTO1WW           | 1         | 1.01%   |
| Lenovo ThinkBook 15-IIL 20SM              | 1         | 1.01%   |
| Lenovo Legion Y540-15IRH 81SX             | 1         | 1.01%   |
| Lenovo Legion 5 15IMH05 82AU              | 1         | 1.01%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS       | 1         | 1.01%   |
| Lenovo IdeaPad C340-14IWL 81RL            | 1         | 1.01%   |
| Lenovo IdeaPad 300-15ISK 80RS             | 1         | 1.01%   |
| Intel NUC6CAYH                            | 1         | 1.01%   |
| Intel NUC13ANHi5                          | 1         | 1.01%   |
| Intel NUC12WSHi7                          | 1         | 1.01%   |
| Intel NUC12WSHi5                          | 1         | 1.01%   |
| HPE ProLiant BL460c Gen10                 | 1         | 1.01%   |
| HP ZBook Fury 16 G9 Mobile Workstation PC | 1         | 1.01%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 20        | 20.2%   |
| Dell Latitude          | 7         | 7.07%   |
| Dell OptiPlex          | 5         | 5.05%   |
| Lenovo IdeaPad         | 3         | 3.03%   |
| HP ZBook               | 3         | 3.03%   |
| HP EliteBook           | 3         | 3.03%   |
| Dell Precision         | 3         | 3.03%   |
| Lenovo Legion          | 2         | 2.02%   |
| HP ProLiant            | 2         | 2.02%   |
| Dell Inspiron          | 2         | 2.02%   |
| ASUS X510UR            | 2         | 2.02%   |
| ASUS PRIME             | 2         | 2.02%   |
| Toshiba TECRA          | 1         | 1.01%   |
| Supermicro X8DTU       | 1         | 1.01%   |
| Standard BW            | 1         | 1.01%   |
| Panasonic CF-53AAG54FM | 1         | 1.01%   |
| MSI P65                | 1         | 1.01%   |
| MSI MS-7758            | 1         | 1.01%   |
| Lenovo ThinkBook       | 1         | 1.01%   |
| Intel NUC6CAYH         | 1         | 1.01%   |
| Intel NUC13ANHi5       | 1         | 1.01%   |
| Intel NUC12WSHi7       | 1         | 1.01%   |
| Intel NUC12WSHi5       | 1         | 1.01%   |
| HPE ProLiant           | 1         | 1.01%   |
| HP Z820                | 1         | 1.01%   |
| HP Z420                | 1         | 1.01%   |
| HP ProBook             | 1         | 1.01%   |
| HP Pavilion            | 1         | 1.01%   |
| HP Notebook            | 1         | 1.01%   |
| HP Laptop              | 1         | 1.01%   |
| HP Compaq              | 1         | 1.01%   |
| HP 240                 | 1         | 1.01%   |
| Google Lick            | 1         | 1.01%   |
| Gigabyte Z490          | 1         | 1.01%   |
| Gigabyte X99-Designare | 1         | 1.01%   |
| Gigabyte X470          | 1         | 1.01%   |
| Gigabyte H81M-S2PV     | 1         | 1.01%   |
| Gigabyte B450M         | 1         | 1.01%   |
| Fujitsu PRIMERGY       | 1         | 1.01%   |
| Foxconn p6-2400el      | 1         | 1.01%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 11        | 11.11%  |
| 2020 | 10        | 10.1%   |
| 2018 | 10        | 10.1%   |
| 2022 | 9         | 9.09%   |
| 2016 | 8         | 8.08%   |
| 2012 | 8         | 8.08%   |
| 2021 | 6         | 6.06%   |
| 2017 | 6         | 6.06%   |
| 2011 | 6         | 6.06%   |
| 2015 | 5         | 5.05%   |
| 2014 | 5         | 5.05%   |
| 2013 | 5         | 5.05%   |
| 2023 | 4         | 4.04%   |
| 2010 | 3         | 3.03%   |
| 2024 | 1         | 1.01%   |
| 2009 | 1         | 1.01%   |
| 2008 | 1         | 1.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 58        | 58.59%  |
| Desktop     | 29        | 29.29%  |
| Mini pc     | 5         | 5.05%   |
| Convertible | 4         | 4.04%   |
| Server      | 3         | 3.03%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 84        | 84%     |
| Enabled  | 16        | 16%     |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 98        | 98.99%  |
| Yes  | 1         | 1.01%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 30        | 30%     |
| 32.01-64.0      | 23        | 23%     |
| 4.01-8.0        | 13        | 13%     |
| 64.01-256.0     | 11        | 11%     |
| 16.01-24.0      | 8         | 8%      |
| 3.01-4.0        | 7         | 7%      |
| 24.01-32.0      | 6         | 6%      |
| More than 256.0 | 1         | 1%      |
| 1.01-2.0        | 1         | 1%      |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 30        | 27.27%  |
| 2.01-3.0    | 24        | 21.82%  |
| 3.01-4.0    | 21        | 19.09%  |
| 8.01-16.0   | 13        | 11.82%  |
| 1.01-2.0    | 12        | 10.91%  |
| 0.51-1.0    | 3         | 2.73%   |
| 32.01-64.0  | 2         | 1.82%   |
| 24.01-32.0  | 2         | 1.82%   |
| 64.01-256.0 | 1         | 0.91%   |
| 16.01-24.0  | 1         | 0.91%   |
| 0.01-0.5    | 1         | 0.91%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 71        | 70.3%   |
| 2      | 16        | 15.84%  |
| 3      | 6         | 5.94%   |
| 4      | 5         | 4.95%   |
| 5      | 2         | 1.98%   |
| 6      | 1         | 0.99%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 79        | 79.8%   |
| Yes       | 20        | 20.2%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 87        | 87.88%  |
| No        | 12        | 12.12%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 78.79%  |
| No        | 21        | 21.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 62.38%  |
| No        | 38        | 37.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 29        | 29%     |
| Germany     | 11        | 11%     |
| UK          | 7         | 7%      |
| Brazil      | 6         | 6%      |
| Poland      | 5         | 5%      |
| Russia      | 4         | 4%      |
| Italy       | 4         | 4%      |
| Australia   | 4         | 4%      |
| Netherlands | 3         | 3%      |
| India       | 3         | 3%      |
| Finland     | 3         | 3%      |
| Vietnam     | 2         | 2%      |
| Spain       | 2         | 2%      |
| Romania     | 2         | 2%      |
| Latvia      | 2         | 2%      |
| Yemen       | 1         | 1%      |
| Turkey      | 1         | 1%      |
| Sweden      | 1         | 1%      |
| Slovakia    | 1         | 1%      |
| Peru        | 1         | 1%      |
| Pakistan    | 1         | 1%      |
| Nigeria     | 1         | 1%      |
| Kazakhstan  | 1         | 1%      |
| Hungary     | 1         | 1%      |
| Hong Kong   | 1         | 1%      |
| Bulgaria    | 1         | 1%      |
| Bolivia     | 1         | 1%      |
| Argentina   | 1         | 1%      |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Sao Paulo          | 4         | 3.74%   |
| San Diego          | 3         | 2.8%    |
| Helsinki           | 3         | 2.8%    |
| Warsaw             | 2         | 1.87%   |
| Siegen             | 2         | 1.87%   |
| Seattle            | 2         | 1.87%   |
| Moscow             | 2         | 1.87%   |
| London             | 2         | 1.87%   |
| Hanoi              | 2         | 1.87%   |
| Colorado Springs   | 2         | 1.87%   |
| Bucharest          | 2         | 1.87%   |
| Berlin             | 2         | 1.87%   |
| Bengaluru          | 2         | 1.87%   |
| Amsterdam          | 2         | 1.87%   |
| Zavar              | 1         | 0.93%   |
| West Linn          | 1         | 0.93%   |
| Weaverville        | 1         | 0.93%   |
| Veliky Novgorod    | 1         | 0.93%   |
| Valmiera           | 1         | 0.93%   |
| Utrecht            | 1         | 0.93%   |
| Turner             | 1         | 0.93%   |
| Sydney             | 1         | 0.93%   |
| Stuttgart          | 1         | 0.93%   |
| Stockholm          | 1         | 0.93%   |
| Sofia              | 1         | 0.93%   |
| Shrewsbury         | 1         | 0.93%   |
| Sao Caetano do Sul | 1         | 0.93%   |
| Santa Cruz         | 1         | 0.93%   |
| Sanaa              | 1         | 0.93%   |
| San Jose           | 1         | 0.93%   |
| San Francisco      | 1         | 0.93%   |
| Rocklin            | 1         | 0.93%   |
| Riverside          | 1         | 0.93%   |
| Riga               | 1         | 0.93%   |
| Richfield          | 1         | 0.93%   |
| Redwood City       | 1         | 0.93%   |
| Reading            | 1         | 0.93%   |
| Port Saint Lucie   | 1         | 0.93%   |
| Pleven             | 1         | 0.93%   |
| Petersberg         | 1         | 0.93%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 30        | 41     | 22.06%  |
| Seagate                     | 15        | 54     | 11.03%  |
| WDC                         | 12        | 15     | 8.82%   |
| Sandisk                     | 11        | 14     | 8.09%   |
| Toshiba                     | 7         | 7      | 5.15%   |
| Kingston                    | 6         | 13     | 4.41%   |
| Unknown                     | 5         | 8      | 3.68%   |
| Intel                       | 5         | 5      | 3.68%   |
| SK hynix                    | 4         | 4      | 2.94%   |
| Micron Technology           | 4         | 7      | 2.94%   |
| Crucial                     | 4         | 5      | 2.94%   |
| Phison Electronics          | 3         | 4      | 2.21%   |
| Micron/Crucial Technology   | 3         | 4      | 2.21%   |
| Kingston Technology Company | 3         | 3      | 2.21%   |
| HGST                        | 3         | 6      | 2.21%   |
| Hewlett-Packard             | 3         | 3      | 2.21%   |
| KIOXIA                      | 2         | 2      | 1.47%   |
| Union Memory (Shenzhen)     | 1         | 2      | 0.74%   |
| Transcend                   | 1         | 1      | 0.74%   |
| Realtek Semiconductor       | 1         | 1      | 0.74%   |
| Plextor                     | 1         | 1      | 0.74%   |
| Phison                      | 1         | 1      | 0.74%   |
| Lite-On                     | 1         | 1      | 0.74%   |
| Lenovo                      | 1         | 1      | 0.74%   |
| KingSpec                    | 1         | 1      | 0.74%   |
| KingFast                    | 1         | 1      | 0.74%   |
| JMicron Technology          | 1         | 1      | 0.74%   |
| HPE                         | 1         | 1      | 0.74%   |
| Hitachi                     | 1         | 1      | 0.74%   |
| GOODRAM                     | 1         | 1      | 0.74%   |
| Fujitsu                     | 1         | 1      | 0.74%   |
| Apple                       | 1         | 1      | 0.74%   |
| Apacer                      | 1         | 1      | 0.74%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 4         | 2.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 3         | 2.03%   |
| Unknown SD/MMC/MS PRO 128GB                       | 2         | 1.35%   |
| Seagate ST2000DM008-2FR102 2TB                    | 2         | 1.35%   |
| SanDisk SSD PLUS 1000GB                           | 2         | 1.35%   |
| Samsung SSD PM830 2.5 7mm 256GB                   | 2         | 1.35%   |
| Samsung SSD 860 EVO 250GB                         | 2         | 1.35%   |
| Samsung MZVLB512HAJQ-000L7 512GB                  | 2         | 1.35%   |
| Samsung MZ7LN512HMJP-000L7 512GB SSD              | 2         | 1.35%   |
| Phison E12 NVMe Controller 2TB                    | 2         | 1.35%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB               | 2         | 1.35%   |
| Kingston Company SNV2S2000G 2TB                   | 2         | 1.35%   |
| Intel SSD 660P Series 1024GB                      | 2         | 1.35%   |
| Crucial CT500MX500SSD1 500GB                      | 2         | 1.35%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 1         | 0.68%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                  | 1         | 0.68%   |
| WDC WDS200T2G0A-00JH30 2TB SSD                    | 1         | 0.68%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD                  | 1         | 0.68%   |
| WDC WD40PURX-64GVNY0 4TB                          | 1         | 0.68%   |
| WDC WD40PURX-64GVNY0 1 4TB                        | 1         | 0.68%   |
| WDC WD40EFRX-68N32N0 4TB                          | 1         | 0.68%   |
| WDC WD3200BEKT-08PVMT1 320GB                      | 1         | 0.68%   |
| WDC WD30EFRX-68AX9N0 3TB                          | 1         | 0.68%   |
| WDC WD2500AAKX-08U6AA0 250GB                      | 1         | 0.68%   |
| WDC WD1600YS-23SHB0 160GB                         | 1         | 0.68%   |
| WDC WD10SPZX-60Z10T1 1TB                          | 1         | 0.68%   |
| WDC WD10JPCX-24UE4T0 1TB                          | 1         | 0.68%   |
| WDC WD10EZEX-60M2NA0 1TB                          | 1         | 0.68%   |
| Unknown MMC64G  64GB                              | 1         | 0.68%   |
| Unknown MMC Card  256GB                           | 1         | 0.68%   |
| Unknown MMC Card  1TB                             | 1         | 0.68%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB      | 1         | 0.68%   |
| Transcend TS2TMTE250H 2TB                         | 1         | 0.68%   |
| Toshiba THNSNJ512GCSU 512GB SSD                   | 1         | 0.68%   |
| Toshiba NVMe SSD Drive 512GB                      | 1         | 0.68%   |
| Toshiba MQ01ABD100 1TB                            | 1         | 0.68%   |
| Toshiba MG08ACA16TE 16TB                          | 1         | 0.68%   |
| Toshiba MG04ACA200E 2TB                           | 1         | 0.68%   |
| Toshiba DT01ACA300 3TB                            | 1         | 0.68%   |
| Toshiba DT01ACA050 500GB                          | 1         | 0.68%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 54     | 36.59%  |
| WDC                 | 9         | 11     | 21.95%  |
| Toshiba             | 5         | 5      | 12.2%   |
| HGST                | 3         | 6      | 7.32%   |
| Unknown             | 2         | 4      | 4.88%   |
| Samsung Electronics | 2         | 2      | 4.88%   |
| JMicron Technology  | 1         | 1      | 2.44%   |
| Hitachi             | 1         | 1      | 2.44%   |
| Hewlett-Packard     | 1         | 1      | 2.44%   |
| Fujitsu             | 1         | 1      | 2.44%   |
| Apple               | 1         | 1      | 2.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 22     | 37.21%  |
| SanDisk             | 6         | 8      | 13.95%  |
| Kingston            | 5         | 6      | 11.63%  |
| WDC                 | 4         | 4      | 9.3%    |
| Crucial             | 3         | 4      | 6.98%   |
| Hewlett-Packard     | 2         | 2      | 4.65%   |
| Toshiba             | 1         | 1      | 2.33%   |
| Plextor             | 1         | 1      | 2.33%   |
| KingSpec            | 1         | 1      | 2.33%   |
| Intel               | 1         | 1      | 2.33%   |
| HPE                 | 1         | 1      | 2.33%   |
| GOODRAM             | 1         | 1      | 2.33%   |
| Apacer              | 1         | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 49        | 67     | 38.89%  |
| SSD     | 40        | 53     | 31.75%  |
| HDD     | 33        | 87     | 26.19%  |
| MMC     | 3         | 4      | 2.38%   |
| Unknown | 1         | 1      | 0.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 58        | 134    | 50.88%  |
| NVMe | 49        | 67     | 42.98%  |
| SAS  | 4         | 7      | 3.51%   |
| MMC  | 3         | 4      | 2.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 33        | 47     | 42.86%  |
| 0.51-1.0   | 24        | 33     | 31.17%  |
| 1.01-2.0   | 10        | 48     | 12.99%  |
| 3.01-4.0   | 3         | 4      | 3.9%    |
| 2.01-3.0   | 3         | 3      | 3.9%    |
| 4.01-10.0  | 3         | 4      | 3.9%    |
| 10.01-20.0 | 1         | 1      | 1.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 26        | 25.74%  |
| 101-250        | 20        | 19.8%   |
| 501-1000       | 17        | 16.83%  |
| 1-20           | 10        | 9.9%    |
| Unknown        | 8         | 7.92%   |
| 1001-2000      | 7         | 6.93%   |
| 51-100         | 5         | 4.95%   |
| More than 3000 | 3         | 2.97%   |
| 2001-3000      | 3         | 2.97%   |
| 21-50          | 2         | 1.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 36        | 34.95%  |
| 21-50          | 23        | 22.33%  |
| 51-100         | 14        | 13.59%  |
| 101-250        | 10        | 9.71%   |
| Unknown        | 8         | 7.77%   |
| 251-500        | 6         | 5.83%   |
| More than 3000 | 3         | 2.91%   |
| 501-1000       | 2         | 1.94%   |
| 1001-2000      | 1         | 0.97%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD40PURX-64GVNY0 4TB                         | 1         | 1      | 12.5%   |
| WDC WD40PURX-64GVNY0 1 4TB                       | 1         | 1      | 12.5%   |
| Seagate ST9750420AS 752GB                        | 1         | 1      | 12.5%   |
| Seagate ST3000DM001-1CH166 3TB                   | 1         | 1      | 12.5%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 12.5%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 2      | 12.5%   |
| Samsung Electronics HD753LJ 752GB                | 1         | 1      | 12.5%   |
| Hewlett-Packard SSD S700 120GB                   | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 42.86%  |
| Samsung Electronics | 2         | 3      | 28.57%  |
| WDC                 | 1         | 2      | 14.29%  |
| Hewlett-Packard     | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 60%     |
| WDC                 | 1         | 2      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 6      | 71.43%  |
| SSD  | 2         | 3      | 28.57%  |

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
| Works    | 56        | 122    | 52.34%  |
| Detected | 44        | 81     | 41.12%  |
| Malfunc  | 7         | 9      | 6.54%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 64        | 51.61%  |
| Samsung Electronics          | 14        | 11.29%  |
| AMD                          | 8         | 6.45%   |
| SanDisk                      | 5         | 4.03%   |
| SK hynix                     | 4         | 3.23%   |
| Phison Electronics           | 4         | 3.23%   |
| Micron/Crucial Technology    | 4         | 3.23%   |
| Micron Technology            | 4         | 3.23%   |
| Kingston Technology Company  | 4         | 3.23%   |
| Broadcom / LSI               | 3         | 2.42%   |
| KIOXIA                       | 2         | 1.61%   |
| VIA Technologies             | 1         | 0.81%   |
| Union Memory (Shenzhen)      | 1         | 0.81%   |
| Transcend                    | 1         | 0.81%   |
| Toshiba America Info Systems | 1         | 0.81%   |
| Realtek Semiconductor        | 1         | 0.81%   |
| Lite-On Technology           | 1         | 0.81%   |
| Lenovo                       | 1         | 0.81%   |
| Adaptec                      | 1         | 0.81%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9         | 6.38%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 6         | 4.26%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 5         | 3.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 3.55%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 4         | 2.84%   |
| Phison E12 NVMe Controller                                                              | 3         | 2.13%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 3         | 2.13%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                                      | 3         | 2.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 2.13%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3         | 2.13%   |
| Intel SATA Controller [RAID Mode]                                                       | 3         | 2.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 2.13%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.42%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 1.42%   |
| Intel SSD 660P Series                                                                   | 2         | 1.42%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 1.42%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 2         | 1.42%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2         | 1.42%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2         | 1.42%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2         | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 1.42%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2         | 1.42%   |
| Intel Alder Lake-P SATA AHCI Controller                                                 | 2         | 1.42%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 2         | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 1.42%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2         | 1.42%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2         | 1.42%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1         | 0.71%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB                         | 1         | 0.71%   |
| Transcend NVMe PCIe SSD 250H                                                            | 1         | 0.71%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 1         | 0.71%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                      | 1         | 0.71%   |
| SK hynix PC601 NVMe Solid State Drive                                                   | 1         | 0.71%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                                       | 1         | 0.71%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1         | 0.71%   |
| Sandisk WD Blue SN580 NVMe SSD (DRAM-less)                                              | 1         | 0.71%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 1         | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 57        | 44.53%  |
| NVMe | 49        | 38.28%  |
| RAID | 10        | 7.81%   |
| IDE  | 8         | 6.25%   |
| SAS  | 3         | 2.34%   |
| SCSI | 1         | 0.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 91        | 91.92%  |
| AMD    | 8         | 8.08%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8665U CPU @ 1.90GHz       | 3         | 3.03%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 3         | 3.03%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 3         | 3.03%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 3         | 3.03%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 2.02%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 2         | 2.02%   |
| Intel Core i7-10610U CPU @ 1.80GHz      | 2         | 2.02%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 2         | 2.02%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 2         | 2.02%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 2         | 2.02%   |
| Intel 12th Gen Core i7-1270P            | 2         | 2.02%   |
| Intel 12th Gen Core i7-1260P            | 2         | 2.02%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz | 2         | 2.02%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz    | 1         | 1.01%   |
| Intel Xeon CPU X3450 @ 2.67GHz          | 1         | 1.01%   |
| Intel Xeon CPU X3430 @ 2.40GHz          | 1         | 1.01%   |
| Intel Xeon CPU E5649 @ 2.53GHz          | 1         | 1.01%   |
| Intel Xeon CPU E5-2690 v4 @ 2.60GHz     | 1         | 1.01%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz     | 1         | 1.01%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz     | 1         | 1.01%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz     | 1         | 1.01%   |
| Intel Xeon CPU E5-1603 v3 @ 2.80GHz     | 1         | 1.01%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz     | 1         | 1.01%   |
| Intel Processor 5Y10 CPU @ 0.80GHz      | 1         | 1.01%   |
| Intel Pentium CPU N3710 @ 1.60GHz       | 1         | 1.01%   |
| Intel Pentium CPU G3240 @ 3.10GHz       | 1         | 1.01%   |
| Intel Pentium CPU G2020 @ 2.90GHz       | 1         | 1.01%   |
| Intel Core i9-9880H CPU @ 2.30GHz       | 1         | 1.01%   |
| Intel Core i9-10900K CPU @ 3.70GHz      | 1         | 1.01%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 1         | 1.01%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 1         | 1.01%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1.01%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1.01%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 1         | 1.01%   |
| Intel Core i7-6800K CPU @ 3.40GHz       | 1         | 1.01%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 1         | 1.01%   |
| Intel Core i7-4940MX CPU @ 3.10GHz      | 1         | 1.01%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz      | 1         | 1.01%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz      | 1         | 1.01%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 1         | 1.01%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i7     | 30        | 30.3%   |
| Other             | 20        | 20.2%   |
| Intel Core i5     | 19        | 19.19%  |
| Intel Xeon        | 9         | 9.09%   |
| Intel Celeron     | 4         | 4.04%   |
| Intel Pentium     | 3         | 3.03%   |
| Intel Core i3     | 3         | 3.03%   |
| Intel Core i9     | 2         | 2.02%   |
| AMD Ryzen 7       | 2         | 2.02%   |
| AMD Ryzen 5       | 2         | 2.02%   |
| Intel Xeon Silver | 1         | 1.01%   |
| Intel Core 2 Duo  | 1         | 1.01%   |
| AMD Ryzen 7 PRO   | 1         | 1.01%   |
| AMD FX            | 1         | 1.01%   |
| AMD A8            | 1         | 1.01%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 38        | 38.38%  |
| 2      | 27        | 27.27%  |
| 6      | 9         | 9.09%   |
| 12     | 8         | 8.08%   |
| 8      | 5         | 5.05%   |
| 16     | 4         | 4.04%   |
| 10     | 4         | 4.04%   |
| 14     | 2         | 2.02%   |
| 20     | 1         | 1.01%   |
| 1      | 1         | 1.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 95        | 95.96%  |
| 2      | 4         | 4.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 78        | 78.79%  |
| 1      | 21        | 21.21%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 98        | 98%     |
| Unknown        | 2         | 2%      |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 13.86%  |
| 0x806ec    | 7         | 6.93%   |
| 0x306c3    | 6         | 5.94%   |
| 0x206a7    | 6         | 5.94%   |
| 0x906a3    | 4         | 3.96%   |
| 0x806ea    | 4         | 3.96%   |
| 0x806c1    | 4         | 3.96%   |
| 0x306a9    | 4         | 3.96%   |
| 0x906ea    | 3         | 2.97%   |
| 0x806e9    | 3         | 2.97%   |
| 0x306d4    | 3         | 2.97%   |
| 0xb06a2    | 2         | 1.98%   |
| 0xa0655    | 2         | 1.98%   |
| 0xa0652    | 2         | 1.98%   |
| 0x906ed    | 2         | 1.98%   |
| 0x90672    | 2         | 1.98%   |
| 0x706a8    | 2         | 1.98%   |
| 0x506e3    | 2         | 1.98%   |
| 0x406f1    | 2         | 1.98%   |
| 0x406e3    | 2         | 1.98%   |
| 0x406c4    | 2         | 1.98%   |
| 0x40651    | 2         | 1.98%   |
| 0x306e4    | 2         | 1.98%   |
| 0x106e5    | 2         | 1.98%   |
| 0xb06f2    | 1         | 0.99%   |
| 0xa0653    | 1         | 0.99%   |
| 0x906e9    | 1         | 0.99%   |
| 0x806d1    | 1         | 0.99%   |
| 0x706e5    | 1         | 0.99%   |
| 0x506c9    | 1         | 0.99%   |
| 0x50654    | 1         | 0.99%   |
| 0x206c2    | 1         | 0.99%   |
| 0x20655    | 1         | 0.99%   |
| 0x10676    | 1         | 0.99%   |
| 0x0a50000c | 1         | 0.99%   |
| 0x08701030 | 1         | 0.99%   |
| 0x08608103 | 1         | 0.99%   |
| 0x0810100b | 1         | 0.99%   |
| 0x0800820d | 1         | 0.99%   |
| 0x07030105 | 1         | 0.99%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 23        | 23.23%  |
| Haswell          | 10        | 10.1%   |
| Alderlake Hybrid | 8         | 8.08%   |
| SandyBridge      | 7         | 7.07%   |
| IvyBridge        | 6         | 6.06%   |
| Broadwell        | 6         | 6.06%   |
| TigerLake        | 5         | 5.05%   |
| Skylake          | 5         | 5.05%   |
| CometLake        | 5         | 5.05%   |
| Unknown          | 5         | 5.05%   |
| Westmere         | 2         | 2.02%   |
| Silvermont       | 2         | 2.02%   |
| Nehalem          | 2         | 2.02%   |
| IceLake          | 2         | 2.02%   |
| Goldmont plus    | 2         | 2.02%   |
| Zen+             | 1         | 1.01%   |
| Zen 3            | 1         | 1.01%   |
| Zen 2            | 1         | 1.01%   |
| Zen              | 1         | 1.01%   |
| Puma             | 1         | 1.01%   |
| Piledriver       | 1         | 1.01%   |
| Penryn           | 1         | 1.01%   |
| Goldmont         | 1         | 1.01%   |
| Excavator        | 1         | 1.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 70        | 58.82%  |
| Nvidia                     | 31        | 26.05%  |
| AMD                        | 11        | 9.24%   |
| Matrox Electronics Systems | 6         | 5.04%   |
| ASPEED Technology          | 1         | 0.84%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 6         | 5.04%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 4.2%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 4.2%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 5         | 4.2%    |
| Intel UHD Graphics 620                                                                   | 4         | 3.36%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 3.36%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 3.36%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 2.52%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.68%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 1.68%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.68%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 1.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.68%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.68%   |
| Intel Raptor Lake-P [UHD Graphics]                                                       | 2         | 1.68%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.68%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.68%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.68%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.68%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.68%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.68%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 1.68%   |
| Nvidia TU117GLM [T550 Laptop GPU]                                                        | 1         | 0.84%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 1         | 0.84%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.84%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 0.84%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.84%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.84%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 0.84%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.84%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.84%   |
| Nvidia GM204GLM [Quadro M4000M]                                                          | 1         | 0.84%   |
| Nvidia GM204 [GeForce GTX 980]                                                           | 1         | 0.84%   |
| Nvidia GM108GLM [Quadro K620M / Quadro M500M]                                            | 1         | 0.84%   |
| Nvidia GK208GLM [Quadro K610M]                                                           | 1         | 0.84%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.84%   |
| Nvidia GK110GL [Quadro K6000]                                                            | 1         | 0.84%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.84%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 49        | 49%     |
| 1 x Nvidia     | 15        | 15%     |
| Intel + Nvidia | 15        | 15%     |
| 1 x Matrox     | 6         | 6%      |
| 1 x AMD        | 6         | 6%      |
| Other          | 3         | 3%      |
| Intel + AMD    | 3         | 3%      |
| AMD + Nvidia   | 2         | 2%      |
| 1 x ASPEED     | 1         | 1%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 82        | 81.19%  |
| Unknown     | 12        | 11.88%  |
| Proprietary | 7         | 6.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 66        | 66%     |
| 3.01-4.0   | 13        | 13%     |
| 1.01-2.0   | 12        | 12%     |
| 0.51-1.0   | 3         | 3%      |
| 0.01-0.5   | 3         | 3%      |
| 5.01-6.0   | 2         | 2%      |
| 8.01-16.0  | 1         | 1%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Chimei Innolux       | 17        | 14.53%  |
| Dell                 | 14        | 11.97%  |
| AU Optronics         | 14        | 11.97%  |
| Samsung Electronics  | 11        | 9.4%    |
| LG Display           | 11        | 9.4%    |
| BOE                  | 9         | 7.69%   |
| Lenovo               | 5         | 4.27%   |
| BenQ                 | 4         | 3.42%   |
| ViewSonic            | 3         | 2.56%   |
| InfoVision           | 3         | 2.56%   |
| Hewlett-Packard      | 3         | 2.56%   |
| Acer                 | 3         | 2.56%   |
| Sharp                | 2         | 1.71%   |
| ASUSTek Computer     | 2         | 1.71%   |
| AOC                  | 2         | 1.71%   |
| Vizio                | 1         | 0.85%   |
| Viotek               | 1         | 0.85%   |
| Sony                 | 1         | 0.85%   |
| Sceptre Tech         | 1         | 0.85%   |
| SAC                  | 1         | 0.85%   |
| Panasonic            | 1         | 0.85%   |
| Packard Bell         | 1         | 0.85%   |
| Goldstar             | 1         | 0.85%   |
| GameMax              | 1         | 0.85%   |
| Fujitsu Siemens      | 1         | 0.85%   |
| Element              | 1         | 0.85%   |
| Eizo                 | 1         | 0.85%   |
| BOE Technology Group | 1         | 0.85%   |
| Ancor Communications | 1         | 0.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 2.44%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 2         | 1.63%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 2         | 1.63%   |
| Dell U2718Q DELA0E9 3840x2160 609x349mm 27.6-inch                     | 2         | 1.63%   |
| Dell P2722H DEL4240 1920x1080 598x336mm 27.0-inch                     | 2         | 1.63%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 2         | 1.63%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 1.63%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 2         | 1.63%   |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                     | 2         | 1.63%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch         | 2         | 1.63%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 2         | 1.63%   |
| AOC 24G1WG4 AOC2401 1920x1080 520x290mm 23.4-inch                     | 2         | 1.63%   |
| Acer SA230 ACR057E 1920x1080 509x286mm 23.0-inch                      | 2         | 1.63%   |
| Vizio V555-J01 VIZ1039 3840x2160 1209x680mm 54.6-inch                 | 1         | 0.81%   |
| Viotek SUW49C VTK4900 3840x1080 1196x336mm 48.9-inch                  | 1         | 0.81%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch         | 1         | 0.81%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch              | 1         | 0.81%   |
| ViewSonic VG2439 SERIES VSCD22B 1920x1080 521x293mm 23.5-inch         | 1         | 0.81%   |
| Sony TV SNY4502 1920x1080                                             | 1         | 0.81%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.81%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 1         | 0.81%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x291mm 29.5-inch        | 1         | 0.81%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch   | 1         | 0.81%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch  | 1         | 0.81%   |
| Samsung Electronics SAMTRON STN0022 1280x1024 380x300mm 19.1-inch     | 1         | 0.81%   |
| Samsung Electronics S32B80P SAM71F1 3840x2160 700x400mm 31.7-inch     | 1         | 0.81%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch     | 1         | 0.81%   |
| Samsung Electronics S27D391 SAM0B89 1920x1080 598x336mm 27.0-inch     | 1         | 0.81%   |
| Samsung Electronics S27D391 SAM0B88 1920x1080 598x336mm 27.0-inch     | 1         | 0.81%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.81%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch     | 1         | 0.81%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC3256 1920x1080 382x215mm 17.3-inch | 1         | 0.81%   |
| Samsung Electronics LCD Monitor S24C650                               | 1         | 0.81%   |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch     | 1         | 0.81%   |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 697x392mm 31.5-inch     | 1         | 0.81%   |
| SAC DM-MONB2205 SAC952D 1920x1080 450x270mm 20.7-inch                 | 1         | 0.81%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 1         | 0.81%   |
| Packard Bell Viseo223DX PKB037A 1920x1080 477x268mm 21.5-inch         | 1         | 0.81%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 54        | 54%     |
| 3840x2160 (4K)     | 9         | 9%      |
| 1366x768 (WXGA)    | 9         | 9%      |
| 1920x1200 (WUXGA)  | 5         | 5%      |
| 1600x900 (HD+)     | 5         | 5%      |
| 2560x1440 (QHD)    | 4         | 4%      |
| 1680x1050 (WSXGA+) | 3         | 3%      |
| 1280x1024 (SXGA)   | 3         | 3%      |
| 3840x2400          | 1         | 1%      |
| 3840x1200          | 1         | 1%      |
| 3840x1080          | 1         | 1%      |
| 2560x1080          | 1         | 1%      |
| 1920x540           | 1         | 1%      |
| 1360x768           | 1         | 1%      |
| 1280x800 (WXGA)    | 1         | 1%      |
| Unknown            | 1         | 1%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 25        | 21.01%  |
| 14      | 15        | 12.61%  |
| 13      | 13        | 10.92%  |
| 27      | 12        | 10.08%  |
| 24      | 12        | 10.08%  |
| 21      | 7         | 5.88%   |
| 23      | 6         | 5.04%   |
| 31      | 4         | 3.36%   |
| Unknown | 4         | 3.36%   |
| 38      | 2         | 1.68%   |
| 22      | 2         | 1.68%   |
| 19      | 2         | 1.68%   |
| 17      | 2         | 1.68%   |
| 16      | 2         | 1.68%   |
| 84      | 1         | 0.84%   |
| 72      | 1         | 0.84%   |
| 69      | 1         | 0.84%   |
| 48      | 1         | 0.84%   |
| 32      | 1         | 0.84%   |
| 29      | 1         | 0.84%   |
| 25      | 1         | 0.84%   |
| 20      | 1         | 0.84%   |
| 18      | 1         | 0.84%   |
| 12      | 1         | 0.84%   |
| 11      | 1         | 0.84%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 52        | 45.22%  |
| 501-600     | 28        | 24.35%  |
| 401-500     | 10        | 8.7%    |
| 601-700     | 6         | 5.22%   |
| 201-300     | 5         | 4.35%   |
| Unknown     | 4         | 3.48%   |
| 351-400     | 3         | 2.61%   |
| 1501-2000   | 3         | 2.61%   |
| 801-900     | 2         | 1.74%   |
| 701-800     | 1         | 0.87%   |
| 1001-1500   | 1         | 0.87%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 75        | 80.65%  |
| 16/10   | 10        | 10.75%  |
| 5/4     | 3         | 3.23%   |
| 32/9    | 2         | 2.15%   |
| Unknown | 2         | 2.15%   |
| 21/9    | 1         | 1.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 25        | 21.55%  |
| 101-110        | 25        | 21.55%  |
| 201-250        | 22        | 18.97%  |
| 301-350        | 13        | 11.21%  |
| 351-500        | 5         | 4.31%   |
| 151-200        | 4         | 3.45%   |
| Unknown        | 4         | 3.45%   |
| More than 1000 | 3         | 2.59%   |
| 71-80          | 3         | 2.59%   |
| 501-1000       | 3         | 2.59%   |
| 251-300        | 2         | 1.72%   |
| 121-130        | 2         | 1.72%   |
| 111-120        | 2         | 1.72%   |
| 61-70          | 1         | 0.86%   |
| 51-60          | 1         | 0.86%   |
| 141-150        | 1         | 0.86%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 44        | 39.64%  |
| 51-100        | 35        | 31.53%  |
| 101-120       | 19        | 17.12%  |
| 161-240       | 6         | 5.41%   |
| Unknown       | 4         | 3.6%    |
| More than 240 | 2         | 1.8%    |
| 1-50          | 1         | 0.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 54        | 53.47%  |
| 2     | 23        | 22.77%  |
| 0     | 15        | 14.85%  |
| 3     | 8         | 7.92%   |
| 4     | 1         | 0.99%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 77        | 51.68%  |
| Realtek Semiconductor             | 38        | 25.5%   |
| Broadcom                          | 7         | 4.7%    |
| Qualcomm Atheros                  | 6         | 4.03%   |
| Lenovo                            | 4         | 2.68%   |
| Broadcom Limited                  | 3         | 2.01%   |
| Samsung Electronics               | 2         | 1.34%   |
| ASIX Electronics                  | 2         | 1.34%   |
| Ralink Technology                 | 1         | 0.67%   |
| QLogic                            | 1         | 0.67%   |
| NetGear                           | 1         | 0.67%   |
| Mellanox Technologies             | 1         | 0.67%   |
| Huawei Technologies               | 1         | 0.67%   |
| FIBOCOM                           | 1         | 0.67%   |
| Ericsson Business Mobile Networks | 1         | 0.67%   |
| Edimax Technology                 | 1         | 0.67%   |
| DisplayLink                       | 1         | 0.67%   |
| ASUSTek Computer                  | 1         | 0.67%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 17        | 8.76%   |
| Intel Wireless 8265 / 8275                                             | 10        | 5.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 9         | 4.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 4.64%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 3.09%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 5         | 2.58%   |
| Realtek RTL8125 2.5GbE Controller                                      | 4         | 2.06%   |
| Intel Wireless 8260                                                    | 4         | 2.06%   |
| Intel Wireless 7260                                                    | 4         | 2.06%   |
| Intel Wi-Fi 6 AX201                                                    | 4         | 2.06%   |
| Intel Ethernet Connection (6) I219-LM                                  | 4         | 2.06%   |
| Intel 82574L Gigabit Network Connection                                | 4         | 2.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3         | 1.55%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 3         | 1.55%   |
| Intel Wireless 7265                                                    | 3         | 1.55%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 3         | 1.55%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 1.55%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 1.55%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 3         | 1.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 3         | 1.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 3         | 1.55%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 1.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 1.03%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 1.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 2         | 1.03%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2         | 1.03%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 2         | 1.03%   |
| Intel Ethernet Controller I226-V                                       | 2         | 1.03%   |
| Intel Ethernet Controller I225-V                                       | 2         | 1.03%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 1.03%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 1.03%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 1.03%   |
| Intel Ethernet Connection (14) I219-V                                  | 2         | 1.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 1.03%   |
| Intel Centrino Ultimate-N 6300                                         | 2         | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2         | 1.03%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 2         | 1.03%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 2         | 1.03%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 1.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 1         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 62        | 73.81%  |
| Realtek Semiconductor | 8         | 9.52%   |
| Qualcomm Atheros      | 6         | 7.14%   |
| Broadcom Limited      | 2         | 2.38%   |
| Ralink Technology     | 1         | 1.19%   |
| NetGear               | 1         | 1.19%   |
| FIBOCOM               | 1         | 1.19%   |
| Edimax Technology     | 1         | 1.19%   |
| Broadcom              | 1         | 1.19%   |
| ASUSTek Computer      | 1         | 1.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                           | 10        | 11.9%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 5         | 5.95%   |
| Intel Wireless 8260                                                  | 4         | 4.76%   |
| Intel Wireless 7260                                                  | 4         | 4.76%   |
| Intel Wi-Fi 6 AX201                                                  | 4         | 4.76%   |
| Intel Wireless 7265                                                  | 3         | 3.57%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 3         | 3.57%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3         | 3.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 3         | 3.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 3         | 3.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 2.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 2         | 2.38%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 2         | 2.38%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 2         | 2.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 2         | 2.38%   |
| Intel Centrino Ultimate-N 6300                                       | 2         | 2.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 2         | 2.38%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 2         | 2.38%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 2         | 2.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 1         | 1.19%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 1.19%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 1         | 1.19%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 1         | 1.19%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 1.19%   |
| Ralink MT7601U Wireless Adapter                                      | 1         | 1.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1         | 1.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1         | 1.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1         | 1.19%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 1         | 1.19%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                      | 1         | 1.19%   |
| Intel Wi-Fi 6 AX200                                                  | 1         | 1.19%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 1         | 1.19%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection              | 1         | 1.19%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 1         | 1.19%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 1         | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1         | 1.19%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 1         | 1.19%   |
| Intel Centrino Advanced-N 6235                                       | 1         | 1.19%   |
| FIBOCOM L830-EB-00                                                   | 1         | 1.19%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 52        | 49.52%  |
| Realtek Semiconductor | 34        | 32.38%  |
| Broadcom              | 6         | 5.71%   |
| Lenovo                | 4         | 3.81%   |
| Samsung Electronics   | 2         | 1.9%    |
| ASIX Electronics      | 2         | 1.9%    |
| QLogic                | 1         | 0.95%   |
| Mellanox Technologies | 1         | 0.95%   |
| Huawei Technologies   | 1         | 0.95%   |
| DisplayLink           | 1         | 0.95%   |
| Broadcom Limited      | 1         | 0.95%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 17        | 15.6%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 9         | 8.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 8.26%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 5.5%    |
| Realtek RTL8125 2.5GbE Controller                                      | 4         | 3.67%   |
| Intel Ethernet Connection (6) I219-LM                                  | 4         | 3.67%   |
| Intel 82574L Gigabit Network Connection                                | 4         | 3.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3         | 2.75%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 3         | 2.75%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 2.75%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 2.75%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 1.83%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 1.83%   |
| Intel Ethernet Controller I226-V                                       | 2         | 1.83%   |
| Intel Ethernet Controller I225-V                                       | 2         | 1.83%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 1.83%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 1.83%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 1.83%   |
| Intel Ethernet Connection (14) I219-V                                  | 2         | 1.83%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 1.83%   |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller               | 1         | 0.92%   |
| Mellanox MT27500 Family [ConnectX-3]                                   | 1         | 0.92%   |
| Lenovo ThinkPad TBT3 LAN                                               | 1         | 0.92%   |
| Intel Ethernet Connection I219-V                                       | 1         | 0.92%   |
| Intel Ethernet Connection I217-V                                       | 1         | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 0.92%   |
| Intel Ethernet Connection (2) I218-V                                   | 1         | 0.92%   |
| Intel Ethernet Connection (17) I219-V                                  | 1         | 0.92%   |
| Intel Ethernet Connection (17) I219-LM                                 | 1         | 0.92%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 0.92%   |
| Intel Ethernet Connection (16) I219-LM                                 | 1         | 0.92%   |
| Intel Ethernet Connection (14) I219-LM                                 | 1         | 0.92%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection                  | 1         | 0.92%   |
| Intel 82578DM Gigabit Network Connection                               | 1         | 0.92%   |
| Intel 82576 Gigabit Network Connection                                 | 1         | 0.92%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                     | 1         | 0.92%   |
| Intel 82571EB Gigabit Ethernet Controller                              | 1         | 0.92%   |
| Huawei Mobile                                                          | 1         | 0.92%   |
| DisplayLink Dell Universal Dock D6000                                  | 1         | 0.92%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                     | 1         | 0.92%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 87        | 52.41%  |
| WiFi     | 78        | 46.99%  |
| Modem    | 1         | 0.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 56        | 54.9%   |
| WiFi     | 46        | 45.1%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 61        | 61.62%  |
| 1     | 31        | 31.31%  |
| 3     | 3         | 3.03%   |
| 4     | 2         | 2.02%   |
| 7     | 1         | 1.01%   |
| 6     | 1         | 1.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 80        | 77.67%  |
| Yes  | 23        | 22.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 46        | 71.88%  |
| Qualcomm Atheros Communications | 5         | 7.81%   |
| Realtek Semiconductor           | 4         | 6.25%   |
| Broadcom                        | 3         | 4.69%   |
| ASUSTek Computer                | 2         | 3.13%   |
| Apple                           | 2         | 3.13%   |
| IMC Networks                    | 1         | 1.56%   |
| Alps Electric                   | 1         | 1.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                         | 10        | 15.63%  |
| Intel AX211 Bluetooth                          | 9         | 14.06%  |
| Intel AX201 Bluetooth                          | 9         | 14.06%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 8         | 12.5%   |
| Intel Bluetooth wireless interface             | 5         | 7.81%   |
| Realtek Bluetooth Radio                        | 3         | 4.69%   |
| Qualcomm Atheros  Bluetooth Device             | 2         | 3.13%   |
| Intel AX210 Bluetooth                          | 2         | 3.13%   |
| ASUS Broadcom BCM20702A0 Bluetooth             | 2         | 3.13%   |
| Apple Bluetooth Host Controller                | 2         | 3.13%   |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 1.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0         | 1         | 1.56%   |
| Qualcomm Atheros Bluetooth USB Host Controller | 1         | 1.56%   |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 1.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1         | 1.56%   |
| Intel Wireless-AC 3168 Bluetooth               | 1         | 1.56%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 1.56%   |
| IMC Networks Bluetooth Radio                   | 1         | 1.56%   |
| Broadcom BCM43142A0 Bluetooth 4.0              | 1         | 1.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0              | 1         | 1.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 1.56%   |
| Alps Electric UGTZ4 Bluetooth                  | 1         | 1.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 83        | 60.14%  |
| Nvidia                 | 21        | 15.22%  |
| AMD                    | 12        | 8.7%    |
| Lenovo                 | 6         | 4.35%   |
| GN Netcom              | 5         | 3.62%   |
| Plantronics            | 2         | 1.45%   |
| C-Media Electronics    | 2         | 1.45%   |
| Unknown                | 1         | 0.72%   |
| TEAC                   | 1         | 0.72%   |
| RME                    | 1         | 0.72%   |
| Realtek Semiconductor  | 1         | 0.72%   |
| M-Audio                | 1         | 0.72%   |
| JMTek                  | 1         | 0.72%   |
| AKAI Professional M.I. | 1         | 0.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 7.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 5.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 3.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 3.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 3.23%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 3.23%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 3.23%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 3.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.94%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 3         | 1.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.94%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 3         | 1.94%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.94%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.94%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 3         | 1.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 1.94%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 1.94%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 1.29%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 1.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 1.29%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 1.29%   |
| Nvidia Audio device                                                                               | 2         | 1.29%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 2         | 1.29%   |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 2         | 1.29%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.29%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.29%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.29%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 2         | 1.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.29%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.29%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.29%   |
| GN Netcom Jabra EVOLVE LINK                                                                       | 2         | 1.29%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.29%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.29%   |
| Unknown Definitive Sym1                                                                           | 1         | 0.65%   |
| TEAC US-2x2                                                                                       | 1         | 0.65%   |
| RME ADI-2 DAC (56760369)                                                                          | 1         | 0.65%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.65%   |
| Plantronics Poly BT700                                                                            | 1         | 0.65%   |
| Plantronics BT600                                                                                 | 1         | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 13        | 18.57%  |
| Micron Technology                       | 13        | 18.57%  |
| SK hynix                                | 12        | 17.14%  |
| Kingston                                | 5         | 7.14%   |
| Unknown                                 | 5         | 7.14%   |
| Unknown                                 | 4         | 5.71%   |
| Crucial                                 | 3         | 4.29%   |
| Corsair                                 | 3         | 4.29%   |
| Avant                                   | 2         | 2.86%   |
| Unknown (0x0C26)                        | 1         | 1.43%   |
| Unigen                                  | 1         | 1.43%   |
| Smart                                   | 1         | 1.43%   |
| Silicon Power Computer & Communications | 1         | 1.43%   |
| Patriot                                 | 1         | 1.43%   |
| Nanya Technology                        | 1         | 1.43%   |
| HPE                                     | 1         | 1.43%   |
| Hewlett-Packard                         | 1         | 1.43%   |
| AVEXIR                                  | 1         | 1.43%   |
| 4ea5                                    | 1         | 1.43%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Unknown                                                       | 5         | 6.49%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 3         | 3.9%    |
| Micron RAM 4ATS1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s       | 2         | 2.6%    |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                   | 1         | 1.3%    |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                     | 1         | 1.3%    |
| Unknown RAM Module 4GB DIMM DDR3 800MT/s                      | 1         | 1.3%    |
| Unknown RAM Module 32GB SODIMM DDR4 2667MT/s                  | 1         | 1.3%    |
| Unknown (0x0C26) RAM TIMETEC-UD4-3200 32GB DIMM DDR4 3200MT/s | 1         | 1.3%    |
| Unigen RAM Module 4GB DIMM DDR3 1333MT/s                      | 1         | 1.3%    |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s         | 1         | 1.3%    |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                 | 1         | 1.3%    |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                 | 1         | 1.3%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 1         | 1.3%    |
| SK hynix RAM HMT31GR7BFR4A-H9 8192MB DIMM 1333MT/s            | 1         | 1.3%    |
| SK hynix RAM HMAA1GS6CMR8N-VK 8GB Row Of Chips DDR4 2667MT/s  | 1         | 1.3%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s  | 1         | 1.3%    |
| SK hynix RAM HMA84GR7AFR4N-UH 32GB DIMM DDR4 2400MT/s         | 1         | 1.3%    |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s       | 1         | 1.3%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s       | 1         | 1.3%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s     | 1         | 1.3%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 1.3%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 1         | 1.3%    |
| SK hynix RAM H9HCNNNBKUMLXR-NEE 2GB LPDDR4 2400MT/s           | 1         | 1.3%    |
| Silicon Power & RAM Module 16GB SODIMM DDR4 2667MT/s          | 1         | 1.3%    |
| Samsung RAM Module 8GB SODIMM DDR5 4800MT/s                   | 1         | 1.3%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.3%    |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s        | 1         | 1.3%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s        | 1         | 1.3%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s        | 1         | 1.3%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s         | 1         | 1.3%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 1.3%    |
| Samsung RAM M393B2G70BH0-YH9 16GB DIMM DDR3 1333MT/s          | 1         | 1.3%    |
| Samsung RAM M393B2G70BH0-CK0 16GB DIMM 1600MT/s               | 1         | 1.3%    |
| Samsung RAM M393A4K40BB1-CRC 32GB DIMM DDR4 2400MT/s          | 1         | 1.3%    |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s               | 1         | 1.3%    |
| Nanya RAM NT8GA64D88AX3S-HR 8GB SODIMM DDR4 2667MT/s          | 1         | 1.3%    |
| Micron RAM Module 32GB SODIMM DDR4 2667MT/s                   | 1         | 1.3%    |
| Micron RAM Module 16384MB SODIMM DDR4 2400MT/s                | 1         | 1.3%    |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s           | 1         | 1.3%    |
| Micron RAM 8ATF2G64HZ-3G2E1 16GB SODIMM DDR4 3200MT/s         | 1         | 1.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 39        | 61.9%   |
| DDR3   | 17        | 26.98%  |
| LPDDR5 | 3         | 4.76%   |
| LPDDR4 | 2         | 3.17%   |
| DRAM   | 1         | 1.59%   |
| DDR5   | 1         | 1.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 36        | 58.06%  |
| DIMM         | 19        | 30.65%  |
| Row Of Chips | 6         | 9.68%   |
| Unknown      | 1         | 1.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 26        | 38.81%  |
| 16384 | 18        | 26.87%  |
| 4096  | 13        | 19.4%   |
| 32768 | 7         | 10.45%  |
| 2048  | 2         | 2.99%   |
| 1024  | 1         | 1.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 15        | 22.73%  |
| 3200  | 12        | 18.18%  |
| 1600  | 10        | 15.15%  |
| 2400  | 8         | 12.12%  |
| 1333  | 7         | 10.61%  |
| 6400  | 3         | 4.55%   |
| 2666  | 2         | 3.03%   |
| 4800  | 1         | 1.52%   |
| 4267  | 1         | 1.52%   |
| 3466  | 1         | 1.52%   |
| 2934  | 1         | 1.52%   |
| 2600  | 1         | 1.52%   |
| 2448  | 1         | 1.52%   |
| 2133  | 1         | 1.52%   |
| 1866  | 1         | 1.52%   |
| 800   | 1         | 1.52%   |

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
| Chicony Electronics                    | 14        | 23.33%  |
| IMC Networks                           | 7         | 11.67%  |
| Logitech                               | 6         | 10%     |
| Realtek Semiconductor                  | 5         | 8.33%   |
| Microdia                               | 5         | 8.33%   |
| Suyin                                  | 3         | 5%      |
| Quanta                                 | 3         | 5%      |
| Luxvisions Innotech Limited            | 3         | 5%      |
| Lite-On Technology                     | 3         | 5%      |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5%      |
| Bison Electronics                      | 3         | 5%      |
| Apple                                  | 2         | 3.33%   |
| Samsung Electronics                    | 1         | 1.67%   |
| OPPO Electronics                       | 1         | 1.67%   |
| Microsoft                              | 1         | 1.67%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 7         | 11.48%  |
| Microdia Integrated_Webcam_HD                                   | 3         | 4.92%   |
| IMC Networks Integrated Camera                                  | 3         | 4.92%   |
| Realtek Integrated_Webcam_HD                                    | 2         | 3.28%   |
| Realtek Integrated_Webcam_FHD                                   | 2         | 3.28%   |
| Quanta HP HD Camera                                             | 2         | 3.28%   |
| Microdia Webcam Vitade AF                                       | 2         | 3.28%   |
| Lite-On Integrated Camera                                       | 2         | 3.28%   |
| IMC Networks VGA UVC WebCam                                     | 2         | 3.28%   |
| Chicony Integrated Camera (1280x720@30)                         | 2         | 3.28%   |
| Bison SunplusIT Integrated Camera                               | 2         | 3.28%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                 | 2         | 3.28%   |
| Suyin Integrated_Webcam_HD                                      | 1         | 1.64%   |
| Suyin HP Truevision HD                                          | 1         | 1.64%   |
| Suyin Asus Integrated Webcam                                    | 1         | 1.64%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 1         | 1.64%   |
| Realtek EasyCamera                                              | 1         | 1.64%   |
| Quanta HP Webcam                                                | 1         | 1.64%   |
| OPPO SM6375-QRD _SN:EA0028BC                                    | 1         | 1.64%   |
| Microsoft LifeCam HD-3000                                       | 1         | 1.64%   |
| Luxvisions Innotech Limited Integrated RGB Camera               | 1         | 1.64%   |
| Luxvisions Innotech Limited HP 5MP Camera                       | 1         | 1.64%   |
| Luxvisions Innotech Limited EasyCamera 1M                       | 1         | 1.64%   |
| Logitech Webcam C925e                                           | 1         | 1.64%   |
| Logitech Webcam C920-C                                          | 1         | 1.64%   |
| Logitech Webcam C270                                            | 1         | 1.64%   |
| Logitech HD Webcam C615                                         | 1         | 1.64%   |
| Logitech HD Webcam C510                                         | 1         | 1.64%   |
| Logitech BRIO Ultra HD Webcam                                   | 1         | 1.64%   |
| Lite-On HP HD Camera                                            | 1         | 1.64%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 1         | 1.64%   |
| IMC Networks SunplusIT Integrated Camera                        | 1         | 1.64%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 1         | 1.64%   |
| Chicony TOSHIBA Web Camera - HD                                 | 1         | 1.64%   |
| Chicony TOSHIBA Web Camera - FHD                                | 1         | 1.64%   |
| Chicony ThinkPad T490 Webcam                                    | 1         | 1.64%   |
| Chicony Lenovo Integrated Camera (0.3MP)                        | 1         | 1.64%   |
| Chicony Integrated IR Camera                                    | 1         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera | 1         | 1.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 10        | 41.67%  |
| Synaptics                  | 9         | 37.5%   |
| Shenzhen Goodix Technology | 2         | 8.33%   |
| Upek                       | 1         | 4.17%   |
| Elan Microelectronics      | 1         | 4.17%   |
| AuthenTec                  | 1         | 4.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 12.5%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 12.5%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 12.5%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 12.5%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 8.33%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 8.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 4.17%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 4.17%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 4.17%   |
| Synaptics WBDI                                                             | 1         | 4.17%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 4.17%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 4.17%   |
| Elan ELAN:Fingerprint                                                      | 1         | 4.17%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 4.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 9         | 69.23%  |
| Alcor Micro | 3         | 23.08%  |
| Lenovo      | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 58200                                 | 6         | 46.15%  |
| Broadcom BCM5880 Secure Applications Processor | 3         | 23.08%  |
| Alcor Micro AU9540 Smartcard Reader            | 2         | 15.38%  |
| Lenovo Integrated Smart Card Reader            | 1         | 7.69%   |
| Alcor Micro Watchdata W 1981                   | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 44        | 42.72%  |
| 1     | 39        | 37.86%  |
| 2     | 14        | 13.59%  |
| 3     | 5         | 4.85%   |
| 7     | 1         | 0.97%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 24        | 30%     |
| Graphics card            | 14        | 17.5%   |
| Net/wireless             | 13        | 16.25%  |
| Chipcard                 | 10        | 12.5%   |
| Unassigned class         | 5         | 6.25%   |
| Communication controller | 3         | 3.75%   |
| Card reader              | 3         | 3.75%   |
| Bluetooth                | 3         | 3.75%   |
| Storage                  | 2         | 2.5%    |
| Sound                    | 2         | 2.5%    |
| Multimedia controller    | 1         | 1.25%   |

