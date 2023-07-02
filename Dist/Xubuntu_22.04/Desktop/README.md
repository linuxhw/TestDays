Xubuntu 22.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Xubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 231

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME H610M-K D4            | [196daaa768](https://linux-hardware.org/?probe=196daaa768) | Jun 30, 2023 |
| ASUSTek       | PRIME H610M-K D4            | [8e7db66929](https://linux-hardware.org/?probe=8e7db66929) | Jun 30, 2023 |
| ASUSTek       | H61M-CS                     | [2878c06857](https://linux-hardware.org/?probe=2878c06857) | Jun 26, 2023 |
| HP            | 339A                        | [ff38f43250](https://linux-hardware.org/?probe=ff38f43250) | Jun 25, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [a39abe1278](https://linux-hardware.org/?probe=a39abe1278) | Jun 24, 2023 |
| Hardkernel    | ODROID-H2                   | [8f879f5566](https://linux-hardware.org/?probe=8f879f5566) | Jun 21, 2023 |
| ASUSTek       | PRIME Z270-K                | [66736b8fbb](https://linux-hardware.org/?probe=66736b8fbb) | Jun 21, 2023 |
| Intel         | H61                         | [d8de2bb1a7](https://linux-hardware.org/?probe=d8de2bb1a7) | Jun 20, 2023 |
| Dell          | 0N4YC8 A00                  | [154f9809e6](https://linux-hardware.org/?probe=154f9809e6) | Jun 18, 2023 |
| Dell          | 0N4YC8 A00                  | [66ce1a98a8](https://linux-hardware.org/?probe=66ce1a98a8) | Jun 18, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [10b3b517f3](https://linux-hardware.org/?probe=10b3b517f3) | Jun 18, 2023 |
| Biostar       | TPower I45                  | [b88767bce0](https://linux-hardware.org/?probe=b88767bce0) | Jun 11, 2023 |
| MSI           | A55M-E35                    | [7800efb785](https://linux-hardware.org/?probe=7800efb785) | Jun 08, 2023 |
| ASUSTek       | PRIME H410I-PLUS            | [83988ad739](https://linux-hardware.org/?probe=83988ad739) | Jun 06, 2023 |
| HP            | 8768 A                      | [17d0560a85](https://linux-hardware.org/?probe=17d0560a85) | Jun 05, 2023 |
| HP            | 21B4 A01                    | [5d394c52ed](https://linux-hardware.org/?probe=5d394c52ed) | Jun 04, 2023 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | [c716b12ee2](https://linux-hardware.org/?probe=c716b12ee2) | Jun 02, 2023 |
| Gigabyte      | H270-HD3-CF                 | [d2912dfb69](https://linux-hardware.org/?probe=d2912dfb69) | May 31, 2023 |
| Acer          | Veriton N4620G              | [4f2cc019b8](https://linux-hardware.org/?probe=4f2cc019b8) | May 26, 2023 |
| Unknown       | 1.0                         | [54d3a069a4](https://linux-hardware.org/?probe=54d3a069a4) | May 22, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [9419d4d25c](https://linux-hardware.org/?probe=9419d4d25c) | May 19, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [584948af65](https://linux-hardware.org/?probe=584948af65) | May 19, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [0b802ad297](https://linux-hardware.org/?probe=0b802ad297) | May 19, 2023 |
| Gigabyte      | M68MT-S2                    | [bd7e95bf66](https://linux-hardware.org/?probe=bd7e95bf66) | May 18, 2023 |
| Pegatron      | Benicia                     | [8d49889e39](https://linux-hardware.org/?probe=8d49889e39) | May 18, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [3a7b647f0b](https://linux-hardware.org/?probe=3a7b647f0b) | May 17, 2023 |
| HP            | 09F8h                       | [380bbcda71](https://linux-hardware.org/?probe=380bbcda71) | May 17, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [f48dba1e04](https://linux-hardware.org/?probe=f48dba1e04) | May 16, 2023 |
| ASUSTek       | P5B-Deluxe                  | [87edc3a632](https://linux-hardware.org/?probe=87edc3a632) | May 12, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [d5bd5c8930](https://linux-hardware.org/?probe=d5bd5c8930) | May 12, 2023 |
| ASRock        | Z590M-ITX/ax                | [2d3692d380](https://linux-hardware.org/?probe=2d3692d380) | May 11, 2023 |
| ASRock        | Z590M-ITX/ax                | [3c43bfe7bc](https://linux-hardware.org/?probe=3c43bfe7bc) | May 11, 2023 |
| ASUSTek       | P5Q SE2                     | [c7d1eac585](https://linux-hardware.org/?probe=c7d1eac585) | May 07, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [307dfb1c46](https://linux-hardware.org/?probe=307dfb1c46) | May 05, 2023 |
| MSI           | A68HM-E33 V2                | [bbac197d5d](https://linux-hardware.org/?probe=bbac197d5d) | May 04, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [11e132041b](https://linux-hardware.org/?probe=11e132041b) | May 04, 2023 |
| Dell          | 0GY6Y8 A03                  | [b735e1019b](https://linux-hardware.org/?probe=b735e1019b) | May 03, 2023 |
| Gigabyte      | X58A-UD3R                   | [36f4134c6b](https://linux-hardware.org/?probe=36f4134c6b) | May 01, 2023 |
| ASRock        | Z170 Extreme4               | [b2c012c1e2](https://linux-hardware.org/?probe=b2c012c1e2) | Apr 27, 2023 |
| HP            | 1632                        | [b818834691](https://linux-hardware.org/?probe=b818834691) | Apr 26, 2023 |
| HP            | 1632                        | [caae9b5992](https://linux-hardware.org/?probe=caae9b5992) | Apr 26, 2023 |
| HP            | 0AECh D                     | [827246f901](https://linux-hardware.org/?probe=827246f901) | Apr 22, 2023 |
| ASRock        | N3700-ITX                   | [849679b442](https://linux-hardware.org/?probe=849679b442) | Apr 17, 2023 |
| ASRock        | X370 Killer SLI             | [912a7f830b](https://linux-hardware.org/?probe=912a7f830b) | Apr 16, 2023 |
| Gigabyte      | M68MT-S2                    | [7b5363bc3e](https://linux-hardware.org/?probe=7b5363bc3e) | Apr 16, 2023 |
| MSI           | Z77A-G43                    | [f44505b54b](https://linux-hardware.org/?probe=f44505b54b) | Apr 12, 2023 |
| Medion        | MS-7848                     | [40e46961a4](https://linux-hardware.org/?probe=40e46961a4) | Apr 08, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [8bc61e0fcd](https://linux-hardware.org/?probe=8bc61e0fcd) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [0f26b74917](https://linux-hardware.org/?probe=0f26b74917) | Mar 30, 2023 |
| Dell          | 0KWVT8 A02                  | [a46eb24b2a](https://linux-hardware.org/?probe=a46eb24b2a) | Mar 29, 2023 |
| MSI           | H110M PRO-D                 | [a822425dcf](https://linux-hardware.org/?probe=a822425dcf) | Mar 25, 2023 |
| ASUSTek       | P5B-Deluxe                  | [3d8b7a6d89](https://linux-hardware.org/?probe=3d8b7a6d89) | Mar 25, 2023 |
| MSI           | H81M-E33                    | [47f031e68c](https://linux-hardware.org/?probe=47f031e68c) | Mar 25, 2023 |
| Dell          | 00V62H A00                  | [34d3fc12b2](https://linux-hardware.org/?probe=34d3fc12b2) | Mar 25, 2023 |
| Dell          | 00V62H A00                  | [f7aaf1dcd0](https://linux-hardware.org/?probe=f7aaf1dcd0) | Mar 25, 2023 |
| ASRock        | FM2A68M-DG3+                | [204b7c3324](https://linux-hardware.org/?probe=204b7c3324) | Mar 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [bbd16627c2](https://linux-hardware.org/?probe=bbd16627c2) | Mar 22, 2023 |
| ASRock        | H270 Pro4                   | [01eb4c8ba5](https://linux-hardware.org/?probe=01eb4c8ba5) | Mar 22, 2023 |
| ASRock        | Z390M-ITX/ac                | [5c07e530e9](https://linux-hardware.org/?probe=5c07e530e9) | Mar 21, 2023 |
| ASRock        | FM2A68M-DG3+                | [00b550c606](https://linux-hardware.org/?probe=00b550c606) | Mar 18, 2023 |
| MSI           | H81M-E34                    | [4cad3cfe12](https://linux-hardware.org/?probe=4cad3cfe12) | Mar 14, 2023 |
| HP            | 0A64h                       | [d5b197e7f2](https://linux-hardware.org/?probe=d5b197e7f2) | Mar 12, 2023 |
| HP            | 0A64h                       | [14de22ae05](https://linux-hardware.org/?probe=14de22ae05) | Mar 11, 2023 |
| Foxconn       | ETON                        | [3a087bc020](https://linux-hardware.org/?probe=3a087bc020) | Mar 10, 2023 |
| Gigabyte      | H81M-H                      | [6f915814dd](https://linux-hardware.org/?probe=6f915814dd) | Mar 08, 2023 |
| Gigabyte      | H81M-H                      | [5fdd1701df](https://linux-hardware.org/?probe=5fdd1701df) | Mar 08, 2023 |
| Foxconn       | ETON                        | [2afed9b076](https://linux-hardware.org/?probe=2afed9b076) | Mar 08, 2023 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | [44509323b0](https://linux-hardware.org/?probe=44509323b0) | Mar 08, 2023 |
| HP            | ProLiant MicroServer        | [32dedf99a8](https://linux-hardware.org/?probe=32dedf99a8) | Mar 07, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [5bd9a1c0d2](https://linux-hardware.org/?probe=5bd9a1c0d2) | Mar 07, 2023 |
| MSI           | PRO Z790-A WIFI             | [439ec46914](https://linux-hardware.org/?probe=439ec46914) | Mar 05, 2023 |
| ASUSTek       | PRIME Z270-A                | [ec9c2f21a5](https://linux-hardware.org/?probe=ec9c2f21a5) | Mar 05, 2023 |
| OEM           | Unknown                     | [d0f1ae246c](https://linux-hardware.org/?probe=d0f1ae246c) | Mar 03, 2023 |
| ASUSTek       | PRIME Z270-A                | [e367c45f3b](https://linux-hardware.org/?probe=e367c45f3b) | Mar 03, 2023 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | [c803be2765](https://linux-hardware.org/?probe=c803be2765) | Mar 02, 2023 |
| ASUSTek       | P5KC                        | [45f781ee3a](https://linux-hardware.org/?probe=45f781ee3a) | Feb 28, 2023 |
| Gigabyte      | MZBSWBP-00                  | [525ac20362](https://linux-hardware.org/?probe=525ac20362) | Feb 26, 2023 |
| MSI           | C847MS-E33                  | [698d950f05](https://linux-hardware.org/?probe=698d950f05) | Feb 24, 2023 |
| Dell          | 0YC03K A03                  | [0101ef8ce7](https://linux-hardware.org/?probe=0101ef8ce7) | Feb 23, 2023 |
| Intel         | X79                         | [28c9b2590c](https://linux-hardware.org/?probe=28c9b2590c) | Feb 18, 2023 |
| Intel         | X79                         | [89c51847f9](https://linux-hardware.org/?probe=89c51847f9) | Feb 18, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | [8338ee5a0d](https://linux-hardware.org/?probe=8338ee5a0d) | Feb 17, 2023 |
| Gigabyte      | H410M S2 V3                 | [0dbeeea38c](https://linux-hardware.org/?probe=0dbeeea38c) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [e1bbf14222](https://linux-hardware.org/?probe=e1bbf14222) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [ba96494c0f](https://linux-hardware.org/?probe=ba96494c0f) | Feb 16, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | [40c415883e](https://linux-hardware.org/?probe=40c415883e) | Feb 16, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [21ad600245](https://linux-hardware.org/?probe=21ad600245) | Feb 14, 2023 |
| ASRock        | AOD790GX/128M               | [693f4f40f8](https://linux-hardware.org/?probe=693f4f40f8) | Feb 13, 2023 |
| Gigabyte      | GA-A75-UD4H                 | [eb4302c6dd](https://linux-hardware.org/?probe=eb4302c6dd) | Feb 10, 2023 |
| Gigabyte      | MZBSWMP-00                  | [894f632950](https://linux-hardware.org/?probe=894f632950) | Feb 01, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [3fac03d01d](https://linux-hardware.org/?probe=3fac03d01d) | Jan 30, 2023 |
| MSI           | PRO B660M-A DDR4            | [0f2037dcd8](https://linux-hardware.org/?probe=0f2037dcd8) | Jan 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [0e28b954b4](https://linux-hardware.org/?probe=0e28b954b4) | Jan 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [10421fe598](https://linux-hardware.org/?probe=10421fe598) | Jan 30, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [6444a93633](https://linux-hardware.org/?probe=6444a93633) | Jan 29, 2023 |
| Gigabyte      | B450M S2H                   | [058de08b2b](https://linux-hardware.org/?probe=058de08b2b) | Jan 24, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [7e91e49912](https://linux-hardware.org/?probe=7e91e49912) | Jan 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [3324fafe5a](https://linux-hardware.org/?probe=3324fafe5a) | Jan 23, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [b5e6a74fcb](https://linux-hardware.org/?probe=b5e6a74fcb) | Jan 22, 2023 |
| Gigabyte      | 8I945GMF                    | [2971006e43](https://linux-hardware.org/?probe=2971006e43) | Jan 21, 2023 |
| MSI           | B450 TOMAHAWK               | [d5ad4c9486](https://linux-hardware.org/?probe=d5ad4c9486) | Jan 17, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [a49a3ddeaa](https://linux-hardware.org/?probe=a49a3ddeaa) | Jan 17, 2023 |
| Gigabyte      | B550M DS3H                  | [d667bf6bb2](https://linux-hardware.org/?probe=d667bf6bb2) | Jan 15, 2023 |
| Gigabyte      | X670 GAMING X AX            | [0277ea7e50](https://linux-hardware.org/?probe=0277ea7e50) | Jan 15, 2023 |
| Lenovo        | ThinkCentre M58 7373A5G     | [07a6ffe405](https://linux-hardware.org/?probe=07a6ffe405) | Jan 11, 2023 |
| Acer          | Veriton N2620G              | [6345424cff](https://linux-hardware.org/?probe=6345424cff) | Jan 07, 2023 |
| Gigabyte      | Z87N-WIFI                   | [ef5e737fd6](https://linux-hardware.org/?probe=ef5e737fd6) | Jan 04, 2023 |
| Gigabyte      | J1800N-D2H                  | [f809473b20](https://linux-hardware.org/?probe=f809473b20) | Jan 03, 2023 |
| Gigabyte      | B550 GAMING X V2            | [da1db1e278](https://linux-hardware.org/?probe=da1db1e278) | Jan 02, 2023 |
| Unknown       | Intel X79                   | [f26c05e261](https://linux-hardware.org/?probe=f26c05e261) | Dec 31, 2022 |
| ASUSTek       | PRIME B450M-K               | [cc1d0776d5](https://linux-hardware.org/?probe=cc1d0776d5) | Dec 30, 2022 |
| Lenovo        | ChiefRiver                  | [847a9e86cd](https://linux-hardware.org/?probe=847a9e86cd) | Dec 30, 2022 |
| HP            | 1998                        | [c3404205e3](https://linux-hardware.org/?probe=c3404205e3) | Dec 29, 2022 |
| Dell          | 040DDP A01                  | [3548fd618d](https://linux-hardware.org/?probe=3548fd618d) | Dec 28, 2022 |
| Acer          | Veriton NBU                 | [cca454d1bd](https://linux-hardware.org/?probe=cca454d1bd) | Dec 26, 2022 |
| MSI           | Z390-A PRO                  | [9bfeb5727a](https://linux-hardware.org/?probe=9bfeb5727a) | Dec 26, 2022 |
| ASRock        | N3700-ITX                   | [dc3f0d5062](https://linux-hardware.org/?probe=dc3f0d5062) | Dec 25, 2022 |
| ASRock        | A320M-HDV R4.0              | [41ec48c0e5](https://linux-hardware.org/?probe=41ec48c0e5) | Dec 23, 2022 |
| HP            | 81C9                        | [cb40ddba01](https://linux-hardware.org/?probe=cb40ddba01) | Dec 22, 2022 |
| HP            | 8594                        | [de0b36257e](https://linux-hardware.org/?probe=de0b36257e) | Dec 21, 2022 |
| PCWare        | IPMH81G1                    | [3dc25592eb](https://linux-hardware.org/?probe=3dc25592eb) | Dec 20, 2022 |
| ASUSTek       | M4A88T-M/USB3               | [52b5b53173](https://linux-hardware.org/?probe=52b5b53173) | Dec 19, 2022 |
| ASUSTek       | M4A88T-M/USB3               | [64972eb902](https://linux-hardware.org/?probe=64972eb902) | Dec 19, 2022 |
| Packard Be... | PT890-8237A                 | [bb9e8d2cd7](https://linux-hardware.org/?probe=bb9e8d2cd7) | Dec 17, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [fdb9e278dd](https://linux-hardware.org/?probe=fdb9e278dd) | Dec 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [c62c8e69b0](https://linux-hardware.org/?probe=c62c8e69b0) | Dec 12, 2022 |
| HP            | 1497                        | [475049bb79](https://linux-hardware.org/?probe=475049bb79) | Dec 10, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | [ef403a3962](https://linux-hardware.org/?probe=ef403a3962) | Dec 10, 2022 |
| ASUSTek       | PRIME A320M-K               | [ce802653d4](https://linux-hardware.org/?probe=ce802653d4) | Dec 07, 2022 |
| ASUSTek       | PRIME A320M-K               | [e2e47d2d43](https://linux-hardware.org/?probe=e2e47d2d43) | Dec 06, 2022 |
| ASUSTek       | P8H61-M LX3                 | [87d3950072](https://linux-hardware.org/?probe=87d3950072) | Nov 30, 2022 |
| MSI           | PRO Z690-A DDR4             | [bd30397e24](https://linux-hardware.org/?probe=bd30397e24) | Nov 29, 2022 |
| MSI           | PRO Z690-A DDR4             | [3b4f834c63](https://linux-hardware.org/?probe=3b4f834c63) | Nov 29, 2022 |
| ASRock        | H270M-ITX/ac                | [dfc381d411](https://linux-hardware.org/?probe=dfc381d411) | Nov 29, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [472530d650](https://linux-hardware.org/?probe=472530d650) | Nov 29, 2022 |
| Gigabyte      | A320M-S2H-CF                | [452417fa68](https://linux-hardware.org/?probe=452417fa68) | Nov 21, 2022 |
| ASUSTek       | M4A88TD-M/USB3              | [8ff2384625](https://linux-hardware.org/?probe=8ff2384625) | Nov 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [c9a4863d1f](https://linux-hardware.org/?probe=c9a4863d1f) | Nov 15, 2022 |
| MSI           | PRO H610M-B DDR4            | [5ffe9844bd](https://linux-hardware.org/?probe=5ffe9844bd) | Nov 15, 2022 |
| HP            | 1495                        | [e29c423a17](https://linux-hardware.org/?probe=e29c423a17) | Nov 15, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | [b042e75495](https://linux-hardware.org/?probe=b042e75495) | Nov 11, 2022 |
| Dell          | 0M5DCD A00                  | [ac93b84c08](https://linux-hardware.org/?probe=ac93b84c08) | Nov 10, 2022 |
| MSI           | A320M PRO-VH                | [70ba1bf558](https://linux-hardware.org/?probe=70ba1bf558) | Nov 08, 2022 |
| MSI           | PRO H610M-B DDR4            | [377df38ed7](https://linux-hardware.org/?probe=377df38ed7) | Nov 08, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [2796faab6c](https://linux-hardware.org/?probe=2796faab6c) | Nov 08, 2022 |
| Intel         | D525MW AAE93082-401         | [d37fe5f0b4](https://linux-hardware.org/?probe=d37fe5f0b4) | Nov 06, 2022 |
| Gigabyte      | Z77-DS3H                    | [e97900160b](https://linux-hardware.org/?probe=e97900160b) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | [f60040c1b7](https://linux-hardware.org/?probe=f60040c1b7) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | [cd87b011a0](https://linux-hardware.org/?probe=cd87b011a0) | Nov 05, 2022 |
| HP            | 8054                        | [0f1371d133](https://linux-hardware.org/?probe=0f1371d133) | Nov 03, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | [423d3158cd](https://linux-hardware.org/?probe=423d3158cd) | Nov 03, 2022 |
| Gigabyte      | 970A-DS3P                   | [65231808f8](https://linux-hardware.org/?probe=65231808f8) | Nov 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3c65639aad](https://linux-hardware.org/?probe=3c65639aad) | Oct 25, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [7027921568](https://linux-hardware.org/?probe=7027921568) | Oct 25, 2022 |
| Intel         | DH61AG AAG23736-507         | [7fa3b3bc6a](https://linux-hardware.org/?probe=7fa3b3bc6a) | Oct 25, 2022 |
| Hardkernel    | ODROID-H2                   | [6398e45c99](https://linux-hardware.org/?probe=6398e45c99) | Oct 24, 2022 |
| MSI           | A320M PRO-VH                | [5f1aeaf170](https://linux-hardware.org/?probe=5f1aeaf170) | Oct 22, 2022 |
| ASUSTek       | Z97-P                       | [f5b8282e1f](https://linux-hardware.org/?probe=f5b8282e1f) | Oct 21, 2022 |
| Itautec       | ST 4273 ST-4273 Padrao 0... | [8c4af1707c](https://linux-hardware.org/?probe=8c4af1707c) | Oct 17, 2022 |
| MSI           | MS-7309                     | [9d4f0daf60](https://linux-hardware.org/?probe=9d4f0daf60) | Oct 16, 2022 |
| ASUSTek       | P8H67                       | [4f03e84827](https://linux-hardware.org/?probe=4f03e84827) | Oct 16, 2022 |
| Lenovo        | ThinkCentre M58 7373A5G     | [ed6ebf5f98](https://linux-hardware.org/?probe=ed6ebf5f98) | Oct 16, 2022 |
| HP            | 198E                        | [47439edd0e](https://linux-hardware.org/?probe=47439edd0e) | Oct 15, 2022 |
| Gigabyte      | G33M-DS2R                   | [a14ced18eb](https://linux-hardware.org/?probe=a14ced18eb) | Oct 15, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [c3513de476](https://linux-hardware.org/?probe=c3513de476) | Oct 11, 2022 |
| Dell          | 0WR7PY A03                  | [3598f82c1e](https://linux-hardware.org/?probe=3598f82c1e) | Oct 10, 2022 |
| HP            | 1589                        | [d50afd3db1](https://linux-hardware.org/?probe=d50afd3db1) | Oct 08, 2022 |
| ASUSTek       | ET1612I                     | [91fea00cbf](https://linux-hardware.org/?probe=91fea00cbf) | Oct 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [10e3123558](https://linux-hardware.org/?probe=10e3123558) | Oct 03, 2022 |
| MSI           | H170M PRO-VDH               | [f7254adff2](https://linux-hardware.org/?probe=f7254adff2) | Sep 25, 2022 |
| ASUSTek       | PRIME A320M-K               | [5588f73920](https://linux-hardware.org/?probe=5588f73920) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | [a83e57d8c1](https://linux-hardware.org/?probe=a83e57d8c1) | Sep 23, 2022 |
| ASUSTek       | A68HM-K                     | [966ae734c2](https://linux-hardware.org/?probe=966ae734c2) | Sep 20, 2022 |
| ASRock        | 960GC-GS FX                 | [3e40742ff0](https://linux-hardware.org/?probe=3e40742ff0) | Sep 18, 2022 |
| ASUSTek       | ET1612I                     | [0ddd9554cc](https://linux-hardware.org/?probe=0ddd9554cc) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [588c189149](https://linux-hardware.org/?probe=588c189149) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [4b94d21772](https://linux-hardware.org/?probe=4b94d21772) | Sep 16, 2022 |
| ASUSTek       | Maximus VII HERO            | [6d40add21a](https://linux-hardware.org/?probe=6d40add21a) | Sep 15, 2022 |
| Dell          | 0DR845                      | [158b3832bc](https://linux-hardware.org/?probe=158b3832bc) | Sep 13, 2022 |
| ASUSTek       | K30BD                       | [d6daf0e1f8](https://linux-hardware.org/?probe=d6daf0e1f8) | Sep 13, 2022 |
| ASUSTek       | H61M-C                      | [bb07dfab63](https://linux-hardware.org/?probe=bb07dfab63) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | [e59aa2e1d5](https://linux-hardware.org/?probe=e59aa2e1d5) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | [930da2e105](https://linux-hardware.org/?probe=930da2e105) | Sep 13, 2022 |
| Dell          | 0DR845                      | [f65bf44380](https://linux-hardware.org/?probe=f65bf44380) | Sep 13, 2022 |
| ASUSTek       | PRIME A320M-K               | [7b7a1cfeb9](https://linux-hardware.org/?probe=7b7a1cfeb9) | Sep 11, 2022 |
| Dell          | 03NVJ6 A01                  | [3f51b6da48](https://linux-hardware.org/?probe=3f51b6da48) | Sep 10, 2022 |
| ASUSTek       | PRIME A320M-C R2.0          | [7649a53341](https://linux-hardware.org/?probe=7649a53341) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | [989e0d5d57](https://linux-hardware.org/?probe=989e0d5d57) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | [f51b1f139e](https://linux-hardware.org/?probe=f51b1f139e) | Sep 06, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | [668995f3ff](https://linux-hardware.org/?probe=668995f3ff) | Sep 04, 2022 |
| ASUSTek       | K30BD                       | [6042bda5d7](https://linux-hardware.org/?probe=6042bda5d7) | Sep 03, 2022 |
| HP            | 8433 11                     | [00868f25c6](https://linux-hardware.org/?probe=00868f25c6) | Aug 31, 2022 |
| ASUSTek       | Z97-C                       | [9bdae9239f](https://linux-hardware.org/?probe=9bdae9239f) | Aug 29, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | [e692fe97cb](https://linux-hardware.org/?probe=e692fe97cb) | Aug 28, 2022 |
| ASUSTek       | P8H67-M LE                  | [7bf3626764](https://linux-hardware.org/?probe=7bf3626764) | Aug 25, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [c37bc2a345](https://linux-hardware.org/?probe=c37bc2a345) | Aug 24, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [5dabf74b7f](https://linux-hardware.org/?probe=5dabf74b7f) | Aug 21, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [ed1f055157](https://linux-hardware.org/?probe=ed1f055157) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [764eaea2ba](https://linux-hardware.org/?probe=764eaea2ba) | Aug 19, 2022 |
| eMachines     | ET1350                      | [96e9f7aba7](https://linux-hardware.org/?probe=96e9f7aba7) | Aug 18, 2022 |
| Foxconn       | 2ADA                        | [015ccc4b06](https://linux-hardware.org/?probe=015ccc4b06) | Aug 18, 2022 |
| HP            | 8591                        | [4235eb97c1](https://linux-hardware.org/?probe=4235eb97c1) | Aug 18, 2022 |
| Dell          | 0YXT71 A00                  | [def7e10c65](https://linux-hardware.org/?probe=def7e10c65) | Aug 17, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [b98fcab3a6](https://linux-hardware.org/?probe=b98fcab3a6) | Aug 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [fd06db829d](https://linux-hardware.org/?probe=fd06db829d) | Aug 14, 2022 |
| MSI           | H310M PRO-M2 PLUS           | [0fadd2421f](https://linux-hardware.org/?probe=0fadd2421f) | Aug 08, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [01bcafef3c](https://linux-hardware.org/?probe=01bcafef3c) | Jul 30, 2022 |
| ASUSTek       | PRIME A320M-K               | [9a97caa028](https://linux-hardware.org/?probe=9a97caa028) | Jul 28, 2022 |
| ASUSTek       | PRIME A320M-K               | [d00325cd68](https://linux-hardware.org/?probe=d00325cd68) | Jul 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [da54317b9a](https://linux-hardware.org/?probe=da54317b9a) | Jul 27, 2022 |
| ASUSTek       | P8H67-M LE                  | [a27a0707b8](https://linux-hardware.org/?probe=a27a0707b8) | Jul 25, 2022 |
| PCWare        | IPX1800E2                   | [4426727633](https://linux-hardware.org/?probe=4426727633) | Jul 24, 2022 |
| MSI           | PRO B660M-A DDR4            | [ba0058e96e](https://linux-hardware.org/?probe=ba0058e96e) | Jul 20, 2022 |
| ASUSTek       | PRIME B450M-A               | [d5a64d7baa](https://linux-hardware.org/?probe=d5a64d7baa) | Jul 16, 2022 |
| MSI           | A320M PRO-E                 | [d16a812a12](https://linux-hardware.org/?probe=d16a812a12) | Jul 10, 2022 |
| MSI           | PRO B660M-A DDR4            | [7b470f27d3](https://linux-hardware.org/?probe=7b470f27d3) | Jul 03, 2022 |
| Dell          | 0GXM1W A00                  | [d48eb55102](https://linux-hardware.org/?probe=d48eb55102) | Jul 01, 2022 |
| MSI           | B450M-A PRO MAX             | [db4763808b](https://linux-hardware.org/?probe=db4763808b) | Jun 22, 2022 |
| MSI           | G31TM-P21                   | [824dc8a1c9](https://linux-hardware.org/?probe=824dc8a1c9) | Jun 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [33dbe3e5db](https://linux-hardware.org/?probe=33dbe3e5db) | Jun 08, 2022 |
| ASUSTek       | PRIME X470-PRO              | [496399846f](https://linux-hardware.org/?probe=496399846f) | May 26, 2022 |
| Lenovo        | MAHOBAY NOK                 | [aa8d9cb3b9](https://linux-hardware.org/?probe=aa8d9cb3b9) | May 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [a22a5ebbff](https://linux-hardware.org/?probe=a22a5ebbff) | May 25, 2022 |
| ASUSTek       | X99-A II                    | [288a6b3b20](https://linux-hardware.org/?probe=288a6b3b20) | May 23, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [3e34ce179d](https://linux-hardware.org/?probe=3e34ce179d) | May 22, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | [6f58937bed](https://linux-hardware.org/?probe=6f58937bed) | May 13, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | [bd94a8145a](https://linux-hardware.org/?probe=bd94a8145a) | May 08, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [e7ad5ed098](https://linux-hardware.org/?probe=e7ad5ed098) | May 06, 2022 |
| Acer          | Veriton M490G               | [f55983d536](https://linux-hardware.org/?probe=f55983d536) | May 04, 2022 |
| ASRock        | P55 Pro                     | [e626676348](https://linux-hardware.org/?probe=e626676348) | May 02, 2022 |
| HP            | 09F8h                       | [8605181df9](https://linux-hardware.org/?probe=8605181df9) | Apr 26, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 5.15.0-56-generic     | 18       | 9.47%   |
| 5.15.0-52-generic     | 16       | 8.42%   |
| 5.15.0-58-generic     | 9        | 4.74%   |
| 5.15.0-47-generic     | 9        | 4.74%   |
| 5.15.0-46-generic     | 9        | 4.74%   |
| 5.15.0-67-generic     | 8        | 4.21%   |
| 5.15.0-60-generic     | 8        | 4.21%   |
| 5.15.0-48-generic     | 6        | 3.16%   |
| 5.15.0-27-generic     | 6        | 3.16%   |
| 5.19.0-41-generic     | 5        | 2.63%   |
| 5.19.0-35-generic     | 5        | 2.63%   |
| 5.15.0-43-generic     | 5        | 2.63%   |
| 5.15.0-41-generic     | 5        | 2.63%   |
| 5.15.0-25-generic     | 5        | 2.63%   |
| 5.19.0-43-generic     | 4        | 2.11%   |
| 5.15.0-57-generic     | 4        | 2.11%   |
| 5.15.0-53-generic     | 4        | 2.11%   |
| 5.15.0-50-generic     | 4        | 2.11%   |
| 5.19.0-32-generic     | 3        | 1.58%   |
| 5.15.0-75-generic     | 3        | 1.58%   |
| 5.15.0-73-generic     | 3        | 1.58%   |
| 5.15.0-69-generic     | 3        | 1.58%   |
| 5.15.0-40-generic     | 3        | 1.58%   |
| 6.2.7-060207-generic  | 2        | 1.05%   |
| 5.19.0-45-generic     | 2        | 1.05%   |
| 5.15.0-71-lowlatency  | 2        | 1.05%   |
| 5.15.0-71-generic     | 2        | 1.05%   |
| 5.15.0-70-generic     | 2        | 1.05%   |
| 5.15.0-60-lowlatency  | 2        | 1.05%   |
| 5.15.0-33-generic     | 2        | 1.05%   |
| 5.15.0-30-generic     | 2        | 1.05%   |
| 5.13.0-40-generic     | 2        | 1.05%   |
| 6.3.3-060303-generic  | 1        | 0.53%   |
| 6.2.2-060202-generic  | 1        | 0.53%   |
| 6.2.10-060210-generic | 1        | 0.53%   |
| 6.2.0-10005-tuxedo    | 1        | 0.53%   |
| 6.1.10.mmn            | 1        | 0.53%   |
| 6.1.0                 | 1        | 0.53%   |
| 6.0.0                 | 1        | 0.53%   |
| 5.4.0-122-generic     | 1        | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 137      | 77.84%  |
| 5.19.0  | 22       | 12.5%   |
| 6.2.7   | 2        | 1.14%   |
| 5.17.0  | 2        | 1.14%   |
| 5.13.0  | 2        | 1.14%   |
| 6.3.3   | 1        | 0.57%   |
| 6.2.2   | 1        | 0.57%   |
| 6.2.10  | 1        | 0.57%   |
| 6.2.0   | 1        | 0.57%   |
| 6.1.10  | 1        | 0.57%   |
| 6.1.0   | 1        | 0.57%   |
| 6.0.0   | 1        | 0.57%   |
| 5.4.0   | 1        | 0.57%   |
| 5.19.13 | 1        | 0.57%   |
| 5.19.1  | 1        | 0.57%   |
| 5.18.0  | 1        | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 137      | 77.84%  |
| 5.19    | 24       | 13.64%  |
| 6.2     | 5        | 2.84%   |
| 6.1     | 2        | 1.14%   |
| 5.17    | 2        | 1.14%   |
| 5.13    | 2        | 1.14%   |
| 6.3     | 1        | 0.57%   |
| 6.0     | 1        | 0.57%   |
| 5.4     | 1        | 0.57%   |
| 5.18    | 1        | 0.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 172      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| XFCE  | 167      | 97.09%  |
| GNOME | 3        | 1.74%   |
| KDE5  | 1        | 0.58%   |
| i3    | 1        | 0.58%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 168      | 96.55%  |
| Tty  | 6        | 3.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 142      | 82.56%  |
| Unknown | 17       | 9.88%   |
| GDM3    | 10       | 5.81%   |
| SDDM    | 2        | 1.16%   |
| GDM     | 1        | 0.58%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 60       | 34.88%  |
| fr_FR   | 24       | 13.95%  |
| de_DE   | 24       | 13.95%  |
| it_IT   | 14       | 8.14%   |
| pt_BR   | 9        | 5.23%   |
| en_CA   | 6        | 3.49%   |
| ru_RU   | 5        | 2.91%   |
| en_GB   | 5        | 2.91%   |
| es_AR   | 3        | 1.74%   |
| pl_PL   | 2        | 1.16%   |
| nl_NL   | 2        | 1.16%   |
| en_IN   | 2        | 1.16%   |
| en_AU   | 2        | 1.16%   |
| cs_CZ   | 2        | 1.16%   |
| tr_TR   | 1        | 0.58%   |
| sv_SE   | 1        | 0.58%   |
| ru_UA   | 1        | 0.58%   |
| hu_HU   | 1        | 0.58%   |
| fr_CH   | 1        | 0.58%   |
| fr_CA   | 1        | 0.58%   |
| fr_BE   | 1        | 0.58%   |
| es_VE   | 1        | 0.58%   |
| es_CO   | 1        | 0.58%   |
| en_ZA   | 1        | 0.58%   |
| C       | 1        | 0.58%   |
| Unknown | 1        | 0.58%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 105      | 60.69%  |
| EFI  | 68       | 39.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 150      | 85.71%  |
| Tmpfs   | 12       | 6.86%   |
| Overlay | 5        | 2.86%   |
| Btrfs   | 5        | 2.86%   |
| Zfs     | 2        | 1.14%   |
| Ext3    | 1        | 0.57%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 107      | 60.45%  |
| MBR     | 37       | 20.9%   |
| Unknown | 33       | 18.64%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 132      | 76.3%   |
| Yes       | 41       | 23.7%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 109      | 62.64%  |
| Yes       | 65       | 37.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 41       | 23.84%  |
| MSI                 | 28       | 16.28%  |
| Gigabyte Technology | 27       | 15.7%   |
| Hewlett-Packard     | 18       | 10.47%  |
| ASRock              | 13       | 7.56%   |
| Dell                | 12       | 6.98%   |
| Lenovo              | 8        | 4.65%   |
| Intel               | 4        | 2.33%   |
| Acer                | 4        | 2.33%   |
| PCWare              | 2        | 1.16%   |
| Fujitsu             | 2        | 1.16%   |
| Foxconn             | 2        | 1.16%   |
| Unknown             | 2        | 1.16%   |
| Pegatron            | 1        | 0.58%   |
| Packard Bell        | 1        | 0.58%   |
| OEM                 | 1        | 0.58%   |
| Medion              | 1        | 0.58%   |
| MACHINIST           | 1        | 0.58%   |
| Itautec             | 1        | 0.58%   |
| Hardkernel          | 1        | 0.58%   |
| eMachines           | 1        | 0.58%   |
| Biostar             | 1        | 0.58%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Dell OptiPlex 7010                  | 4        | 2.33%   |
| ASUS All Series                     | 4        | 2.33%   |
| MSI MS-7D43                         | 3        | 1.74%   |
| Unknown                             | 3        | 1.74%   |
| MSI MS-7D46                         | 2        | 1.16%   |
| MSI MS-7D25                         | 2        | 1.16%   |
| MSI MS-7C52                         | 2        | 1.16%   |
| MSI MS-7817                         | 2        | 1.16%   |
| MSI MS-7721                         | 2        | 1.16%   |
| Dell OptiPlex 9020                  | 2        | 1.16%   |
| ASUS K30AD_M31AD_M51AD              | 2        | 1.16%   |
| Pegatron FZ132AA-ABF m9456fr        | 1        | 0.58%   |
| PCWare IPX1800E2                    | 1        | 0.58%   |
| PCWare IPMH81G1                     | 1        | 0.58%   |
| Packard Bell IMEDIA X9305           | 1        | 0.58%   |
| MSI MS-7E07                         | 1        | 0.58%   |
| MSI MS-7D40                         | 1        | 0.58%   |
| MSI MS-7C91                         | 1        | 0.58%   |
| MSI MS-7C84                         | 1        | 0.58%   |
| MSI MS-7C56                         | 1        | 0.58%   |
| MSI MS-7C08                         | 1        | 0.58%   |
| MSI MS-7C02                         | 1        | 0.58%   |
| MSI MS-7B98                         | 1        | 0.58%   |
| MSI MS-7A32                         | 1        | 0.58%   |
| MSI MS-7982                         | 1        | 0.58%   |
| MSI MS-7835                         | 1        | 0.58%   |
| MSI MS-7758                         | 1        | 0.58%   |
| MSI MS-7529                         | 1        | 0.58%   |
| MSI MS-7309                         | 1        | 0.58%   |
| MSI Hyrican PC A320M PRO-E          | 1        | 0.58%   |
| Medion MS-7848                      | 1        | 0.58%   |
| MACHINIST X99-RS9 V2.0              | 1        | 0.58%   |
| Lenovo V530S-07ICB 10TX0010PB       | 1        | 0.58%   |
| Lenovo ThinkCentre M90p 3282A9G     | 1        | 0.58%   |
| Lenovo ThinkCentre M83 10AM0010US   | 1        | 0.58%   |
| Lenovo ThinkCentre M83 10AGS17E00   | 1        | 0.58%   |
| Lenovo ThinkCentre M72e 32675L2     | 1        | 0.58%   |
| Lenovo ThinkCentre M710e 10UR001LUS | 1        | 0.58%   |
| Lenovo ThinkCentre M58 7373A5G      | 1        | 0.58%   |
| Lenovo ThinkCentre M32 10BV000CMD   | 1        | 0.58%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 12       | 6.98%   |
| Dell OptiPlex        | 11       | 6.4%    |
| Lenovo ThinkCentre   | 7        | 4.07%   |
| HP Compaq            | 5        | 2.91%   |
| ASUS All             | 4        | 2.33%   |
| Acer Veriton         | 4        | 2.33%   |
| MSI MS-7D43          | 3        | 1.74%   |
| HP EliteDesk         | 3        | 1.74%   |
| ASUS TUF             | 3        | 1.74%   |
| ASUS ROG             | 3        | 1.74%   |
| Unknown              | 3        | 1.74%   |
| MSI MS-7D46          | 2        | 1.16%   |
| MSI MS-7D25          | 2        | 1.16%   |
| MSI MS-7C52          | 2        | 1.16%   |
| MSI MS-7817          | 2        | 1.16%   |
| MSI MS-7721          | 2        | 1.16%   |
| HP Pavilion          | 2        | 1.16%   |
| Gigabyte B550        | 2        | 1.16%   |
| ASUS P8H61-M         | 2        | 1.16%   |
| ASUS K30AD           | 2        | 1.16%   |
| Pegatron FZ132AA-ABF | 1        | 0.58%   |
| PCWare IPX1800E2     | 1        | 0.58%   |
| PCWare IPMH81G1      | 1        | 0.58%   |
| Packard Bell IMEDIA  | 1        | 0.58%   |
| MSI MS-7E07          | 1        | 0.58%   |
| MSI MS-7D40          | 1        | 0.58%   |
| MSI MS-7C91          | 1        | 0.58%   |
| MSI MS-7C84          | 1        | 0.58%   |
| MSI MS-7C56          | 1        | 0.58%   |
| MSI MS-7C08          | 1        | 0.58%   |
| MSI MS-7C02          | 1        | 0.58%   |
| MSI MS-7B98          | 1        | 0.58%   |
| MSI MS-7A32          | 1        | 0.58%   |
| MSI MS-7982          | 1        | 0.58%   |
| MSI MS-7835          | 1        | 0.58%   |
| MSI MS-7758          | 1        | 0.58%   |
| MSI MS-7529          | 1        | 0.58%   |
| MSI MS-7309          | 1        | 0.58%   |
| MSI Hyrican          | 1        | 0.58%   |
| Medion MS-7848       | 1        | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2014 | 20       | 11.63%  |
| 2013 | 18       | 10.47%  |
| 2018 | 16       | 9.3%    |
| 2021 | 14       | 8.14%   |
| 2010 | 14       | 8.14%   |
| 2012 | 11       | 6.4%    |
| 2020 | 10       | 5.81%   |
| 2016 | 10       | 5.81%   |
| 2019 | 9        | 5.23%   |
| 2017 | 9        | 5.23%   |
| 2015 | 9        | 5.23%   |
| 2011 | 9        | 5.23%   |
| 2022 | 6        | 3.49%   |
| 2009 | 5        | 2.91%   |
| 2007 | 5        | 2.91%   |
| 2008 | 3        | 1.74%   |
| 2006 | 2        | 1.16%   |
| 2005 | 2        | 1.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 172      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 165      | 95.93%  |
| Enabled  | 7        | 4.07%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 172      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 38       | 22.09%  |
| 4.01-8.0    | 34       | 19.77%  |
| 3.01-4.0    | 33       | 19.19%  |
| 8.01-16.0   | 26       | 15.12%  |
| 32.01-64.0  | 25       | 14.53%  |
| 24.01-32.0  | 6        | 3.49%   |
| 64.01-256.0 | 4        | 2.33%   |
| 1.01-2.0    | 4        | 2.33%   |
| 2.01-3.0    | 2        | 1.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 75       | 40.54%  |
| 2.01-3.0   | 38       | 20.54%  |
| 3.01-4.0   | 28       | 15.14%  |
| 4.01-8.0   | 24       | 12.97%  |
| 0.51-1.0   | 10       | 5.41%   |
| 8.01-16.0  | 7        | 3.78%   |
| 16.01-24.0 | 2        | 1.08%   |
| 0.01-0.5   | 1        | 0.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 66       | 37.5%   |
| 2      | 50       | 28.41%  |
| 3      | 29       | 16.48%  |
| 4      | 15       | 8.52%   |
| 5      | 7        | 3.98%   |
| 6      | 5        | 2.84%   |
| 7      | 2        | 1.14%   |
| 10     | 1        | 0.57%   |
| 9      | 1        | 0.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 88       | 50.87%  |
| Yes       | 85       | 49.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 172      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 104      | 60.12%  |
| Yes       | 69       | 39.88%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 124      | 71.68%  |
| Yes       | 49       | 28.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Germany      | 28       | 16.18%  |
| USA          | 27       | 15.61%  |
| France       | 22       | 12.72%  |
| Italy        | 14       | 8.09%   |
| Brazil       | 10       | 5.78%   |
| Canada       | 7        | 4.05%   |
| Sweden       | 6        | 3.47%   |
| Russia       | 5        | 2.89%   |
| Netherlands  | 5        | 2.89%   |
| Poland       | 4        | 2.31%   |
| Argentina    | 4        | 2.31%   |
| UK           | 3        | 1.73%   |
| Belgium      | 3        | 1.73%   |
| Switzerland  | 2        | 1.16%   |
| Norway       | 2        | 1.16%   |
| Mexico       | 2        | 1.16%   |
| India        | 2        | 1.16%   |
| Greece       | 2        | 1.16%   |
| Czechia      | 2        | 1.16%   |
| Colombia     | 2        | 1.16%   |
| Belarus      | 2        | 1.16%   |
| Australia    | 2        | 1.16%   |
| Turkey       | 1        | 0.58%   |
| Taiwan       | 1        | 0.58%   |
| Spain        | 1        | 0.58%   |
| South Africa | 1        | 0.58%   |
| Slovenia     | 1        | 0.58%   |
| Romania      | 1        | 0.58%   |
| Portugal     | 1        | 0.58%   |
| Pakistan     | 1        | 0.58%   |
| Iran         | 1        | 0.58%   |
| Indonesia    | 1        | 0.58%   |
| Hungary      | 1        | 0.58%   |
| Guernsey     | 1        | 0.58%   |
| Guadeloupe   | 1        | 0.58%   |
| Denmark      | 1        | 0.58%   |
| China        | 1        | 0.58%   |
| Bulgaria     | 1        | 0.58%   |
| Austria      | 1        | 0.58%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Paris                | 5        | 2.79%   |
| Berlin               | 4        | 2.23%   |
| Stuttgart            | 2        | 1.12%   |
| Schwerte             | 2        | 1.12%   |
| Santiago de Cali     | 2        | 1.12%   |
| Rio de Janeiro       | 2        | 1.12%   |
| Munich               | 2        | 1.12%   |
| Milan                | 2        | 1.12%   |
| Clermont-Ferrand     | 2        | 1.12%   |
| Biella               | 2        | 1.12%   |
| Amsterdam            | 2        | 1.12%   |
| Żywiec              | 1        | 0.56%   |
| Yvoir                | 1        | 0.56%   |
| Wojnicz              | 1        | 0.56%   |
| Wilhelmshaven        | 1        | 0.56%   |
| Wiener Neustadt      | 1        | 0.56%   |
| White House          | 1        | 0.56%   |
| Wettringen           | 1        | 0.56%   |
| Washington           | 1        | 0.56%   |
| Waghausel            | 1        | 0.56%   |
| Waarder              | 1        | 0.56%   |
| Vohenstrauss         | 1        | 0.56%   |
| Vohburg an der Donau | 1        | 0.56%   |
| Vicenza              | 1        | 0.56%   |
| Västerås           | 1        | 0.56%   |
| Valparaiso de Goias  | 1        | 0.56%   |
| Uppsala              | 1        | 0.56%   |
| Trois-Rivières      | 1        | 0.56%   |
| Tourouvre            | 1        | 0.56%   |
| Toronto              | 1        | 0.56%   |
| Tijuana              | 1        | 0.56%   |
| The Hague            | 1        | 0.56%   |
| Terrace              | 1        | 0.56%   |
| Teresina             | 1        | 0.56%   |
| Tehran               | 1        | 0.56%   |
| Taichung             | 1        | 0.56%   |
| Sydney               | 1        | 0.56%   |
| Surrey               | 1        | 0.56%   |
| St Petersburg        | 1        | 0.56%   |
| Springfield          | 1        | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 58       | 90     | 17.68%  |
| Samsung Electronics   | 51       | 66     | 15.55%  |
| Seagate               | 45       | 65     | 13.72%  |
| Kingston              | 25       | 31     | 7.62%   |
| Toshiba               | 21       | 23     | 6.4%    |
| Hitachi               | 16       | 25     | 4.88%   |
| Crucial               | 14       | 20     | 4.27%   |
| SanDisk               | 13       | 18     | 3.96%   |
| China                 | 8        | 8      | 2.44%   |
| HGST                  | 7        | 11     | 2.13%   |
| A-DATA Technology     | 6        | 6      | 1.83%   |
| Unknown               | 5        | 7      | 1.52%   |
| PNY                   | 5        | 5      | 1.52%   |
| Intel                 | 5        | 5      | 1.52%   |
| ASMT                  | 4        | 7      | 1.22%   |
| Patriot               | 3        | 3      | 0.91%   |
| TEXTORM               | 2        | 2      | 0.61%   |
| SK hynix              | 2        | 2      | 0.61%   |
| Phison Electronics    | 2        | 4      | 0.61%   |
| OCZ                   | 2        | 2      | 0.61%   |
| Micron Technology     | 2        | 2      | 0.61%   |
| Maxtor                | 2        | 2      | 0.61%   |
| Intenso               | 2        | 2      | 0.61%   |
| Gigabyte Technology   | 2        | 2      | 0.61%   |
| Corsair               | 2        | 2      | 0.61%   |
| XPG                   | 1        | 1      | 0.3%    |
| Veno                  | 1        | 1      | 0.3%    |
| Vaseky                | 1        | 1      | 0.3%    |
| USB3.0                | 1        | 2      | 0.3%    |
| TO Exter              | 1        | 2      | 0.3%    |
| SPCC                  | 1        | 1      | 0.3%    |
| Silicon Motion        | 1        | 1      | 0.3%    |
| Realtek Semiconductor | 1        | 1      | 0.3%    |
| Phison                | 1        | 8      | 0.3%    |
| PHD 3.0               | 1        | 1      | 0.3%    |
| Mushkin               | 1        | 1      | 0.3%    |
| Linux                 | 1        | 1      | 0.3%    |
| Lexar                 | 1        | 1      | 0.3%    |
| LaCie                 | 1        | 1      | 0.3%    |
| KIOXIA                | 1        | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 860 EVO 500GB                           | 7        | 1.83%   |
| Kingston SA400S37240G 240GB SSD                     | 6        | 1.57%   |
| Crucial CT480BX500SSD1 480GB                        | 6        | 1.57%   |
| Kingston SA400S37480G 480GB SSD                     | 5        | 1.31%   |
| Toshiba DT01ACA200 2TB                              | 4        | 1.05%   |
| Kingston SV300S37A120G 120GB SSD                    | 4        | 1.05%   |
| Toshiba HDWD110 1TB                                 | 3        | 0.79%   |
| Toshiba DT01ACA100 1TB                              | 3        | 0.79%   |
| Seagate ST500DM002-1BD142 500GB                     | 3        | 0.79%   |
| Seagate ST4000DM004-2CV104 4TB                      | 3        | 0.79%   |
| Seagate ST2000DM008-2FR102 2TB                      | 3        | 0.79%   |
| Seagate ST1000DM003-1SB102 1TB                      | 3        | 0.79%   |
| Seagate ST1000DM003-1ER162 1TB                      | 3        | 0.79%   |
| Samsung SSD 850 EVO 500GB                           | 3        | 0.79%   |
| Samsung SSD 850 EVO 250GB                           | 3        | 0.79%   |
| Samsung SSD 840 Series 120GB                        | 3        | 0.79%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 2        | 0.52%   |
| WDC WD20EARX-00PASB0 2TB                            | 2        | 0.52%   |
| WDC WD20EARS-00MVWB0 2TB                            | 2        | 0.52%   |
| WDC WD10EZRZ-00HTKB0 1TB                            | 2        | 0.52%   |
| WDC WD10EZEX-00BBHA0 1TB                            | 2        | 0.52%   |
| Toshiba DT01ACA050 500GB                            | 2        | 0.52%   |
| TEXTORM BM5 240GB SSD                               | 2        | 0.52%   |
| Seagate ST9500420AS 500GB                           | 2        | 0.52%   |
| Seagate ST500LM000-1EJ162 500GB                     | 2        | 0.52%   |
| Seagate ST4000VX007-2DT166 4TB                      | 2        | 0.52%   |
| Seagate ST31000528AS 1TB                            | 2        | 0.52%   |
| Seagate ST3000DM008-2DM166 3TB                      | 2        | 0.52%   |
| Seagate ST2000DM001-1CH164 2TB                      | 2        | 0.52%   |
| Seagate ST1000DM003-1CH162 1TB                      | 2        | 0.52%   |
| SanDisk SDSSDA240G 240GB                            | 2        | 0.52%   |
| Samsung SSD 970 EVO Plus 250GB                      | 2        | 0.52%   |
| Samsung SSD 970 EVO Plus 1TB                        | 2        | 0.52%   |
| Samsung SSD 870 QVO 1TB                             | 2        | 0.52%   |
| Samsung SSD 870 EVO 250GB                           | 2        | 0.52%   |
| Samsung SSD 840 EVO 250GB                           | 2        | 0.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 2        | 0.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 2        | 0.52%   |
| Samsung HM321HI 320GB                               | 2        | 0.52%   |
| Samsung HD250HJ 250GB                               | 2        | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 53       | 84     | 33.33%  |
| Seagate             | 45       | 63     | 28.3%   |
| Toshiba             | 18       | 20     | 11.32%  |
| Hitachi             | 16       | 25     | 10.06%  |
| Samsung Electronics | 10       | 14     | 6.29%   |
| HGST                | 7        | 11     | 4.4%    |
| ASMT                | 4        | 7      | 2.52%   |
| USB3.0              | 1        | 2      | 0.63%   |
| Unknown             | 1        | 1      | 0.63%   |
| PHD 3.0             | 1        | 1      | 0.63%   |
| Maxtor              | 1        | 1      | 0.63%   |
| LaCie               | 1        | 1      | 0.63%   |
| Hewlett-Packard     | 1        | 1      | 0.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 31       | 36     | 25.41%  |
| Kingston            | 20       | 24     | 16.39%  |
| Crucial             | 13       | 19     | 10.66%  |
| SanDisk             | 10       | 13     | 8.2%    |
| China               | 8        | 8      | 6.56%   |
| A-DATA Technology   | 6        | 6      | 4.92%   |
| WDC                 | 5        | 5      | 4.1%    |
| PNY                 | 4        | 4      | 3.28%   |
| Toshiba             | 3        | 3      | 2.46%   |
| Patriot             | 3        | 3      | 2.46%   |
| Intel               | 3        | 3      | 2.46%   |
| TEXTORM             | 2        | 2      | 1.64%   |
| OCZ                 | 2        | 2      | 1.64%   |
| Intenso             | 2        | 2      | 1.64%   |
| Veno                | 1        | 1      | 0.82%   |
| Vaseky              | 1        | 1      | 0.82%   |
| TO Exter            | 1        | 2      | 0.82%   |
| SPCC                | 1        | 1      | 0.82%   |
| Micron Technology   | 1        | 1      | 0.82%   |
| Maxtor              | 1        | 1      | 0.82%   |
| Linux               | 1        | 1      | 0.82%   |
| KingFast            | 1        | 1      | 0.82%   |
| KingDian            | 1        | 1      | 0.82%   |
| Corsair             | 1        | 1      | 0.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 120      | 231    | 44.78%  |
| SSD     | 102      | 141    | 38.06%  |
| NVMe    | 37       | 62     | 13.81%  |
| Unknown | 6        | 7      | 2.24%   |
| MMC     | 3        | 4      | 1.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 160      | 350    | 74.07%  |
| NVMe | 37       | 62     | 17.13%  |
| SAS  | 16       | 29     | 7.41%   |
| MMC  | 3        | 4      | 1.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 134      | 219    | 54.25%  |
| 0.51-1.0   | 59       | 76     | 23.89%  |
| 1.01-2.0   | 31       | 42     | 12.55%  |
| 3.01-4.0   | 14       | 24     | 5.67%   |
| 2.01-3.0   | 4        | 4      | 1.62%   |
| 4.01-10.0  | 4        | 5      | 1.62%   |
| 10.01-20.0 | 1        | 2      | 0.4%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 44       | 25.14%  |
| 251-500        | 37       | 21.14%  |
| 1001-2000      | 26       | 14.86%  |
| 501-1000       | 22       | 12.57%  |
| More than 3000 | 18       | 10.29%  |
| 2001-3000      | 12       | 6.86%   |
| 1-20           | 6        | 3.43%   |
| 21-50          | 5        | 2.86%   |
| 51-100         | 5        | 2.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 42       | 23.46%  |
| 21-50          | 28       | 15.64%  |
| 251-500        | 27       | 15.08%  |
| 101-250        | 26       | 14.53%  |
| 51-100         | 16       | 8.94%   |
| 501-1000       | 15       | 8.38%   |
| 1001-2000      | 10       | 5.59%   |
| 2001-3000      | 8        | 4.47%   |
| More than 3000 | 7        | 3.91%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Toshiba DT01ACA100 1TB            | 2        | 2      | 5.56%   |
| Seagate ST1000DM003-1ER162 1TB    | 2        | 2      | 5.56%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD  | 1        | 1      | 2.78%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 1      | 2.78%   |
| WDC WD3200AAKS-00L9A0 320GB       | 1        | 1      | 2.78%   |
| WDC WD2500AAKS-00VSA0 250GB       | 1        | 1      | 2.78%   |
| WDC WD20EFRX-68AX9N0 2TB          | 1        | 1      | 2.78%   |
| WDC WD20EARS-00MVWB0 2TB          | 1        | 1      | 2.78%   |
| WDC WD2002FYPS-02W3B0 2TB         | 1        | 1      | 2.78%   |
| WDC WD10EZEX-60ZF5A0 1TB          | 1        | 1      | 2.78%   |
| WDC WD10EAVS-00D7B1 1TB           | 1        | 1      | 2.78%   |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1      | 2.78%   |
| WDC WD1003FBYX-01Y7B1 1TB         | 1        | 1      | 2.78%   |
| Seagate ST9250410AS 250GB         | 1        | 1      | 2.78%   |
| Seagate ST3750840AS 752GB         | 1        | 1      | 2.78%   |
| Seagate ST3500414CS 500GB         | 1        | 1      | 2.78%   |
| Seagate ST3250318AS 250GB         | 1        | 2      | 2.78%   |
| Seagate ST2000DM001-1CH164 2TB    | 1        | 1      | 2.78%   |
| Samsung Electronics SP2514N 250GB | 1        | 1      | 2.78%   |
| Samsung Electronics HM321HI 320GB | 1        | 2      | 2.78%   |
| Samsung Electronics HD753LJ 752GB | 1        | 1      | 2.78%   |
| Samsung Electronics HD250HJ 250GB | 1        | 1      | 2.78%   |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 2.78%   |
| PNY 69D03094-T 40GB SSD           | 1        | 1      | 2.78%   |
| Maxtor STM3160215AS 160GB         | 1        | 1      | 2.78%   |
| Intel SSDSC2BW120A4 120GB         | 1        | 1      | 2.78%   |
| Hitachi HDS722540VLAT20 40GB      | 1        | 1      | 2.78%   |
| Hitachi HDS721010CLA332 1TB       | 1        | 1      | 2.78%   |
| Hitachi HCP725032GLA380 320GB     | 1        | 2      | 2.78%   |
| HGST HUS724040ALA640 4TB          | 1        | 3      | 2.78%   |
| Hewlett-Packard VB0250EAVER 250GB | 1        | 1      | 2.78%   |
| Crucial CT128MX100SSD1 128GB      | 1        | 1      | 2.78%   |
| China SATA SSD 16GB               | 1        | 1      | 2.78%   |
| ASMT ASMT105x 2TB                 | 1        | 4      | 2.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 11     | 29.41%  |
| Seagate             | 7        | 8      | 20.59%  |
| Samsung Electronics | 4        | 6      | 11.76%  |
| Hitachi             | 3        | 4      | 8.82%   |
| Toshiba             | 2        | 2      | 5.88%   |
| PNY                 | 1        | 1      | 2.94%   |
| Maxtor              | 1        | 1      | 2.94%   |
| Intel               | 1        | 1      | 2.94%   |
| HGST                | 1        | 3      | 2.94%   |
| Hewlett-Packard     | 1        | 1      | 2.94%   |
| Crucial             | 1        | 1      | 2.94%   |
| China               | 1        | 1      | 2.94%   |
| ASMT                | 1        | 4      | 2.94%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 10     | 31.03%  |
| Seagate             | 7        | 8      | 24.14%  |
| Samsung Electronics | 4        | 6      | 13.79%  |
| Hitachi             | 3        | 4      | 10.34%  |
| Toshiba             | 2        | 2      | 6.9%    |
| Maxtor              | 1        | 1      | 3.45%   |
| HGST                | 1        | 3      | 3.45%   |
| Hewlett-Packard     | 1        | 1      | 3.45%   |
| ASMT                | 1        | 4      | 3.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 26       | 39     | 86.67%  |
| SSD  | 4        | 5      | 13.33%  |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 98       | 206    | 48.76%  |
| Detected | 74       | 195    | 36.82%  |
| Malfunc  | 29       | 44     | 14.43%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 117      | 49.58%  |
| AMD                          | 48       | 20.34%  |
| Samsung Electronics          | 13       | 5.51%   |
| Kingston Technology Company  | 7        | 2.97%   |
| ASMedia Technology           | 7        | 2.97%   |
| Phison Electronics           | 6        | 2.54%   |
| JMicron Technology           | 6        | 2.54%   |
| SanDisk                      | 4        | 1.69%   |
| Nvidia                       | 4        | 1.69%   |
| Marvell Technology Group     | 4        | 1.69%   |
| VIA Technologies             | 3        | 1.27%   |
| Silicon Image                | 3        | 1.27%   |
| SK hynix                     | 2        | 0.85%   |
| Silicon Motion               | 2        | 0.85%   |
| Realtek Semiconductor        | 2        | 0.85%   |
| Shenzhen Longsys Electronics | 1        | 0.42%   |
| Micron/Crucial Technology    | 1        | 0.42%   |
| Micron Technology            | 1        | 0.42%   |
| LSI Logic / Symbios Logic    | 1        | 0.42%   |
| KIOXIA                       | 1        | 0.42%   |
| INNOGRIT                     | 1        | 0.42%   |
| ADATA Technology             | 1        | 0.42%   |
| Adaptec                      | 1        | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 29       | 9.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 16       | 5.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 10       | 3.36%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10       | 3.36%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 9        | 3.02%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9        | 3.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8        | 2.68%   |
| Intel SATA Controller [RAID mode]                                                       | 8        | 2.68%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 8        | 2.68%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7        | 2.35%   |
| AMD 500 Series Chipset SATA Controller                                                  | 7        | 2.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 2.01%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 2.01%   |
| AMD FCH SATA Controller D                                                               | 6        | 2.01%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 1.68%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 1.68%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5        | 1.68%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 1.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 1.68%   |
| Nvidia MCP61 SATA Controller                                                            | 4        | 1.34%   |
| Kingston Company A2000 NVMe SSD                                                         | 4        | 1.34%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 1.34%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 1.34%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.34%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                        | 3        | 1.01%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 1.01%   |
| Nvidia MCP61 IDE                                                                        | 3        | 1.01%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.01%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 1.01%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 1.01%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.01%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 2        | 0.67%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 0.67%   |
| SanDisk WD Black SN770 NVMe SSD                                                         | 2        | 0.67%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 0.67%   |
| Phison E18 PCIe4 NVMe Controller                                                        | 2        | 0.67%   |
| Kingston Company NVMe Controller                                                        | 2        | 0.67%   |
| Intel Non-Volatile memory controller                                                    | 2        | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 141      | 60.78%  |
| NVMe | 37       | 15.95%  |
| IDE  | 36       | 15.52%  |
| RAID | 16       | 6.9%    |
| SAS  | 1        | 0.43%   |
| SCSI | 1        | 0.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 119      | 69.19%  |
| AMD    | 53       | 30.81%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 5        | 2.89%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 2.31%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 3        | 1.73%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 3        | 1.73%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 3        | 1.73%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3        | 1.73%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2        | 1.16%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 1.16%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.16%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 1.16%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 2        | 1.16%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 1.16%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 1.16%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 2        | 1.16%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 1.16%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.16%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.16%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 2        | 1.16%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 1.16%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 1.16%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 2        | 1.16%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 2        | 1.16%   |
| Intel 13th Gen Core i7-13700KF              | 2        | 1.16%   |
| Intel 12th Gen Core i7-12700                | 2        | 1.16%   |
| Intel 12th Gen Core i3-12100F               | 2        | 1.16%   |
| Intel 12th Gen Core i3-12100                | 2        | 1.16%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 2        | 1.16%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 1.16%   |
| AMD Ryzen 5 3600XT 6-Core Processor         | 2        | 1.16%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.16%   |
| AMD Phenom II X4 955 Processor              | 2        | 1.16%   |
| AMD FX-6300 Six-Core Processor              | 2        | 1.16%   |
| Intel Xeon CPU X5687 @ 3.60GHz              | 1        | 0.58%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 0.58%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz          | 1        | 0.58%   |
| Intel Xeon CPU E5-2666 v3 @ 2.90GHz         | 1        | 0.58%   |
| Intel Xeon CPU E5-2658 v2 @ 2.40GHz         | 1        | 0.58%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz          | 1        | 0.58%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.58%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 33       | 19.08%  |
| Intel Core i7           | 20       | 11.56%  |
| Intel Core i3           | 19       | 10.98%  |
| AMD Ryzen 5             | 19       | 10.98%  |
| Intel Celeron           | 13       | 7.51%   |
| Other                   | 11       | 6.36%   |
| Intel Xeon              | 6        | 3.47%   |
| AMD Ryzen 7             | 6        | 3.47%   |
| Intel Core 2 Quad       | 5        | 2.89%   |
| Intel Core 2 Duo        | 5        | 2.89%   |
| AMD A8                  | 5        | 2.89%   |
| AMD Ryzen 9             | 3        | 1.73%   |
| AMD Phenom II X4        | 3        | 1.73%   |
| AMD FX                  | 3        | 1.73%   |
| AMD Athlon II X2        | 3        | 1.73%   |
| Intel Pentium Dual-Core | 2        | 1.16%   |
| Intel Pentium 4         | 2        | 1.16%   |
| Intel Pentium           | 2        | 1.16%   |
| AMD Ryzen 3             | 2        | 1.16%   |
| AMD Athlon 64 X2        | 2        | 1.16%   |
| Intel Atom              | 1        | 0.58%   |
| AMD Turion II Neo       | 1        | 0.58%   |
| AMD Sempron             | 1        | 0.58%   |
| AMD Ryzen 7 PRO         | 1        | 0.58%   |
| AMD Phenom II X6        | 1        | 0.58%   |
| AMD GX                  | 1        | 0.58%   |
| AMD Athlon II           | 1        | 0.58%   |
| AMD Athlon              | 1        | 0.58%   |
| AMD A10                 | 1        | 0.58%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 77       | 44.25%  |
| 2      | 48       | 27.59%  |
| 6      | 23       | 13.22%  |
| 8      | 10       | 5.75%   |
| 12     | 5        | 2.87%   |
| 1      | 3        | 1.72%   |
| 16     | 2        | 1.15%   |
| 10     | 2        | 1.15%   |
| 3      | 2        | 1.15%   |
| 24     | 1        | 0.57%   |
| 14     | 1        | 0.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 172      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 97       | 56.4%   |
| 1      | 75       | 43.6%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 172      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 67       | 38.73%  |
| 0x306c3    | 14       | 8.09%   |
| 0x306a9    | 8        | 4.62%   |
| 0x206a7    | 7        | 4.05%   |
| 0x0800820d | 5        | 2.89%   |
| 0x506e3    | 4        | 2.31%   |
| 0x1067a    | 4        | 2.31%   |
| 0x08701021 | 4        | 2.31%   |
| 0x010000c8 | 4        | 2.31%   |
| 0xb0671    | 3        | 1.73%   |
| 0x906ea    | 3        | 1.73%   |
| 0x90672    | 3        | 1.73%   |
| 0x106e5    | 3        | 1.73%   |
| 0x906e9    | 2        | 1.16%   |
| 0x406c3    | 2        | 1.16%   |
| 0x206d7    | 2        | 1.16%   |
| 0x10676    | 2        | 1.16%   |
| 0x0a201016 | 2        | 1.16%   |
| 0x08701013 | 2        | 1.16%   |
| 0x08108109 | 2        | 1.16%   |
| 0x06000852 | 2        | 1.16%   |
| 0x010000c7 | 2        | 1.16%   |
| 0xa0653    | 1        | 0.58%   |
| 0x906ed    | 1        | 0.58%   |
| 0x906eb    | 1        | 0.58%   |
| 0x706a1    | 1        | 0.58%   |
| 0x6fb      | 1        | 0.58%   |
| 0x506c9    | 1        | 0.58%   |
| 0x406c4    | 1        | 0.58%   |
| 0x306f2    | 1        | 0.58%   |
| 0x306e4    | 1        | 0.58%   |
| 0x30679    | 1        | 0.58%   |
| 0x206c2    | 1        | 0.58%   |
| 0x20652    | 1        | 0.58%   |
| 0x106ca    | 1        | 0.58%   |
| 0x10677    | 1        | 0.58%   |
| 0x0a601201 | 1        | 0.58%   |
| 0x0a50000c | 1        | 0.58%   |
| 0x0a20120a | 1        | 0.58%   |
| 0x08600106 | 1        | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 22       | 12.72%  |
| SandyBridge      | 16       | 9.25%   |
| KabyLake         | 15       | 8.67%   |
| IvyBridge        | 14       | 8.09%   |
| Zen 2            | 13       | 7.51%   |
| Penryn           | 10       | 5.78%   |
| Zen+             | 9        | 5.2%    |
| K10              | 9        | 5.2%    |
| Unknown          | 8        | 4.62%   |
| Skylake          | 6        | 3.47%   |
| Piledriver       | 6        | 3.47%   |
| Zen 3            | 5        | 2.89%   |
| Silvermont       | 5        | 2.89%   |
| CometLake        | 5        | 2.89%   |
| Zen              | 4        | 2.31%   |
| Nehalem          | 4        | 2.31%   |
| Alderlake Hybrid | 4        | 2.31%   |
| Core             | 3        | 1.73%   |
| Westmere         | 2        | 1.16%   |
| NetBurst         | 2        | 1.16%   |
| K8 Hammer        | 2        | 1.16%   |
| Jaguar           | 2        | 1.16%   |
| Steamroller      | 1        | 0.58%   |
| K10 Llano        | 1        | 0.58%   |
| Goldmont plus    | 1        | 0.58%   |
| Goldmont         | 1        | 0.58%   |
| Excavator        | 1        | 0.58%   |
| Broadwell        | 1        | 0.58%   |
| Bonnell          | 1        | 0.58%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 76       | 40.86%  |
| Nvidia | 64       | 34.41%  |
| AMD    | 46       | 24.73%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12       | 6.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11       | 5.88%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 9        | 4.81%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7        | 3.74%   |
| Intel HD Graphics 530                                                                    | 6        | 3.21%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6        | 3.21%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5        | 2.67%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4        | 2.14%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4        | 2.14%   |
| Intel HD Graphics 630                                                                    | 4        | 2.14%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3        | 1.6%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3        | 1.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 1.6%    |
| Intel AlderLake-S GT1                                                                    | 3        | 1.6%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3        | 1.6%    |
| Nvidia GT216 [GeForce GT 220]                                                            | 2        | 1.07%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 1.07%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 2        | 1.07%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 1.07%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 1.07%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                               | 2        | 1.07%   |
| Intel DG2 [Arc A770]                                                                     | 2        | 1.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 1.07%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                                | 2        | 1.07%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2        | 1.07%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2        | 1.07%   |
| AMD RS880 [Radeon HD 4250]                                                               | 2        | 1.07%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 1.07%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2        | 1.07%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 2        | 1.07%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 1.07%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2        | 1.07%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2        | 1.07%   |
| Nvidia TU117GL [T600]                                                                    | 1        | 0.53%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1        | 0.53%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1        | 0.53%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 0.53%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1        | 0.53%   |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1        | 0.53%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 64       | 37.21%  |
| 1 x Nvidia     | 59       | 34.3%   |
| 1 x AMD        | 40       | 23.26%  |
| Intel + Nvidia | 3        | 1.74%   |
| Intel + AMD    | 3        | 1.74%   |
| AMD + Nvidia   | 2        | 1.16%   |
| 2 x AMD        | 1        | 0.58%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 126      | 72.83%  |
| Proprietary | 40       | 23.12%  |
| Unknown     | 7        | 4.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 104      | 60.12%  |
| 1.01-2.0   | 18       | 10.4%   |
| 0.51-1.0   | 17       | 9.83%   |
| 0.01-0.5   | 11       | 6.36%   |
| 3.01-4.0   | 8        | 4.62%   |
| 7.01-8.0   | 7        | 4.05%   |
| 8.01-16.0  | 4        | 2.31%   |
| 5.01-6.0   | 2        | 1.16%   |
| 2.01-3.0   | 2        | 1.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 28       | 16.18%  |
| Samsung Electronics  | 24       | 13.87%  |
| Hewlett-Packard      | 17       | 9.83%   |
| Goldstar             | 12       | 6.94%   |
| AOC                  | 12       | 6.94%   |
| Acer                 | 11       | 6.36%   |
| BenQ                 | 7        | 4.05%   |
| ViewSonic            | 6        | 3.47%   |
| Iiyama               | 6        | 3.47%   |
| Ancor Communications | 6        | 3.47%   |
| Philips              | 5        | 2.89%   |
| Lenovo               | 3        | 1.73%   |
| Fujitsu Siemens      | 3        | 1.73%   |
| Unknown              | 2        | 1.16%   |
| RTK                  | 2        | 1.16%   |
| Eizo                 | 2        | 1.16%   |
| ASUSTek Computer     | 2        | 1.16%   |
| Unknown              | 2        | 1.16%   |
| ___                  | 1        | 0.58%   |
| Vestel Elektronik    | 1        | 0.58%   |
| UGD                  | 1        | 0.58%   |
| Toshiba              | 1        | 0.58%   |
| TEO                  | 1        | 0.58%   |
| Tech Concepts        | 1        | 0.58%   |
| TCL                  | 1        | 0.58%   |
| Sony                 | 1        | 0.58%   |
| SNC                  | 1        | 0.58%   |
| RGT                  | 1        | 0.58%   |
| Packard Bell         | 1        | 0.58%   |
| Mi                   | 1        | 0.58%   |
| MAG                  | 1        | 0.58%   |
| LG Electronics       | 1        | 0.58%   |
| JINGLITAI            | 1        | 0.58%   |
| IBM                  | 1        | 0.58%   |
| Gateway              | 1        | 0.58%   |
| Envision Peripherals | 1        | 0.58%   |
| eMachines            | 1        | 0.58%   |
| Elo Touch            | 1        | 0.58%   |
| Denver               | 1        | 0.58%   |
| Compal               | 1        | 0.58%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                | 2        | 1.09%   |
| Philips 170S PHL082B 1280x1024 338x270mm 17.0-inch                    | 2        | 1.09%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                   | 2        | 1.09%   |
| Hewlett-Packard 2309 HWP2821 1920x1080 510x287mm 23.0-inch            | 2        | 1.09%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 2        | 1.09%   |
| Unknown                                                               | 2        | 1.09%   |
| ___ LCD Monitor ___1BBC 1920x540 140x90mm 6.6-inch                    | 1        | 0.55%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch         | 1        | 0.55%   |
| ViewSonic VX3276-UHD VSC5138 3840x2160 697x392mm 31.5-inch            | 1        | 0.55%   |
| ViewSonic VP2365 SERIES VSC7C28 1920x1080 509x286mm 23.0-inch         | 1        | 0.55%   |
| ViewSonic VA1948 SERIES VSCE827 1440x900 408x255mm 18.9-inch          | 1        | 0.55%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch  | 1        | 0.55%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 1        | 0.55%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1        | 0.55%   |
| UGD CD220F (H) UGD2210 1920x1080 527x296mm 23.8-inch                  | 1        | 0.55%   |
| Toshiba TV TSB0109 1920x1080                                          | 1        | 0.55%   |
| TEO TL765 TEO6700 1280x1024 338x270mm 17.0-inch                       | 1        | 0.55%   |
| Tech Concepts LCD Monitor 32S327 1280x720                             | 1        | 0.55%   |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                      | 1        | 0.55%   |
| Sony TV SNYAB03 1920x1080                                             | 1        | 0.55%   |
| SNC SKP_E20-27 SNC2700 2560x1440 597x336mm 27.0-inch                  | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0653 1920x1080                      | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM05C4 1920x1080 510x290mm 23.1-inch  | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM03E3 1680x1050 433x271mm 20.1-inch  | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch   | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 408x306mm 20.1-inch  | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM00E5 1280x1024 338x270mm 17.0-inch  | 1        | 0.55%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch     | 1        | 0.55%   |
| Samsung Electronics SMB2430L SAM0645 1920x1080 521x293mm 23.5-inch    | 1        | 0.55%   |
| Samsung Electronics SM2333TN SAM06FC 1920x1080 477x268mm 21.5-inch    | 1        | 0.55%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 477x268mm 21.5-inch | 1        | 0.55%   |
| Samsung Electronics S24E650 SAM0C86 1920x1200 518x324mm 24.1-inch     | 1        | 0.55%   |
| Samsung Electronics S24E360 SAM0C0F 1920x1080 521x293mm 23.5-inch     | 1        | 0.55%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 1        | 0.55%   |
| Samsung Electronics S24B300 SAM08CC 1920x1080 521x293mm 23.5-inch     | 1        | 0.55%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1        | 0.55%   |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch      | 1        | 0.55%   |
| Samsung Electronics LCD Monitor SMB2430L 3840x1080                    | 1        | 0.55%   |
| Samsung Electronics LCD Monitor SMB2430L                              | 1        | 0.55%   |
| Samsung Electronics LCD Monitor SAM094E 1920x1080 700x390mm 31.5-inch | 1        | 0.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 80       | 46.78%  |
| 1280x1024 (SXGA)   | 14       | 8.19%   |
| 2560x1440 (QHD)    | 11       | 6.43%   |
| 1366x768 (WXGA)    | 10       | 5.85%   |
| 1440x900 (WXGA+)   | 8        | 4.68%   |
| 3840x2160 (4K)     | 7        | 4.09%   |
| 1600x900 (HD+)     | 7        | 4.09%   |
| 1680x1050 (WSXGA+) | 6        | 3.51%   |
| 1920x1200 (WUXGA)  | 4        | 2.34%   |
| 1024x768 (XGA)     | 4        | 2.34%   |
| 3840x1080          | 3        | 1.75%   |
| 1600x1200          | 3        | 1.75%   |
| 1360x768           | 3        | 1.75%   |
| 3840x1600          | 2        | 1.17%   |
| 3440x1440          | 2        | 1.17%   |
| 2560x1600          | 2        | 1.17%   |
| Unknown            | 2        | 1.17%   |
| 2288x1287          | 1        | 0.58%   |
| 1920x540           | 1        | 0.58%   |
| 1280x720 (HD)      | 1        | 0.58%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 26       | 14.61%  |
| 23      | 26       | 14.61%  |
| 27      | 19       | 10.67%  |
| 21      | 18       | 10.11%  |
| 19      | 14       | 7.87%   |
| Unknown | 12       | 6.74%   |
| 18      | 10       | 5.62%   |
| 20      | 9        | 5.06%   |
| 17      | 8        | 4.49%   |
| 15      | 6        | 3.37%   |
| 31      | 5        | 2.81%   |
| 22      | 4        | 2.25%   |
| 72      | 2        | 1.12%   |
| 40      | 2        | 1.12%   |
| 37      | 2        | 1.12%   |
| 34      | 2        | 1.12%   |
| 32      | 2        | 1.12%   |
| 26      | 2        | 1.12%   |
| 25      | 2        | 1.12%   |
| 142     | 1        | 0.56%   |
| 84      | 1        | 0.56%   |
| 54      | 1        | 0.56%   |
| 49      | 1        | 0.56%   |
| 30      | 1        | 0.56%   |
| 29      | 1        | 0.56%   |
| 6       | 1        | 0.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 67       | 39.18%  |
| 401-500        | 51       | 29.82%  |
| 301-350        | 14       | 8.19%   |
| Unknown        | 12       | 7.02%   |
| 601-700        | 9        | 5.26%   |
| 801-900        | 4        | 2.34%   |
| 701-800        | 4        | 2.34%   |
| 351-400        | 3        | 1.75%   |
| 1501-2000      | 3        | 1.75%   |
| 1001-1500      | 2        | 1.17%   |
| More than 2000 | 1        | 0.58%   |
| 101-200        | 1        | 0.58%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 104      | 64.2%   |
| 16/10   | 24       | 14.81%  |
| 5/4     | 11       | 6.79%   |
| Unknown | 10       | 6.17%   |
| 4/3     | 7        | 4.32%   |
| 21/9    | 4        | 2.47%   |
| 32/9    | 1        | 0.62%   |
| 1.00    | 1        | 0.62%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 58       | 33.33%  |
| 151-200        | 31       | 17.82%  |
| 301-350        | 20       | 11.49%  |
| 141-150        | 17       | 9.77%   |
| Unknown        | 12       | 6.9%    |
| 351-500        | 11       | 6.32%   |
| 251-300        | 9        | 5.17%   |
| 101-110        | 6        | 3.45%   |
| More than 1000 | 5        | 2.87%   |
| 501-1000       | 4        | 2.3%    |
| 1-40           | 1        | 0.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 110      | 66.67%  |
| 101-120       | 31       | 18.79%  |
| Unknown       | 12       | 7.27%   |
| 121-160       | 6        | 3.64%   |
| 1-50          | 5        | 3.03%   |
| More than 240 | 1        | 0.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 140      | 80.92%  |
| 2     | 20       | 11.56%  |
| 0     | 9        | 5.2%    |
| 3     | 4        | 2.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 115      | 47.33%  |
| Intel                           | 73       | 30.04%  |
| Qualcomm Atheros                | 14       | 5.76%   |
| Ralink Technology               | 6        | 2.47%   |
| TP-Link                         | 4        | 1.65%   |
| Nvidia                          | 4        | 1.65%   |
| Broadcom                        | 4        | 1.65%   |
| Ralink                          | 2        | 0.82%   |
| Marvell Technology Group        | 2        | 0.82%   |
| D-Link System                   | 2        | 0.82%   |
| Broadcom Limited                | 2        | 0.82%   |
| ZyDAS                           | 1        | 0.41%   |
| Zoom Telephonics                | 1        | 0.41%   |
| TRENDnet                        | 1        | 0.41%   |
| Samsung Electronics             | 1        | 0.41%   |
| Qualcomm Atheros Communications | 1        | 0.41%   |
| OPPO Electronics                | 1        | 0.41%   |
| NetGear                         | 1        | 0.41%   |
| Microchip Technology            | 1        | 0.41%   |
| Mellanox Technologies           | 1        | 0.41%   |
| MediaTek                        | 1        | 0.41%   |
| Dell                            | 1        | 0.41%   |
| Belkin Components               | 1        | 0.41%   |
| ASUSTek Computer                | 1        | 0.41%   |
| ASIX Electronics                | 1        | 0.41%   |
| Aquantia                        | 1        | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 89       | 32.72%  |
| Realtek RTL8125 2.5GbE Controller                                          | 13       | 4.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 10       | 3.68%   |
| Intel I211 Gigabit Network Connection                                      | 9        | 3.31%   |
| Intel Ethernet Connection (2) I219-V                                       | 9        | 3.31%   |
| Intel Wi-Fi 6 AX200                                                        | 6        | 2.21%   |
| Intel Ethernet Connection I217-LM                                          | 6        | 2.21%   |
| Realtek 802.11ac NIC                                                       | 4        | 1.47%   |
| Ralink MT7601U Wireless Adapter                                            | 4        | 1.47%   |
| Nvidia MCP61 Ethernet                                                      | 4        | 1.47%   |
| Intel Ethernet Controller I225-V                                           | 4        | 1.47%   |
| Intel Ethernet Connection I217-V                                           | 4        | 1.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 3        | 1.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 3        | 1.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 3        | 1.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 3        | 1.1%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 3        | 1.1%    |
| Intel Ethernet Connection (7) I219-V                                       | 3        | 1.1%    |
| Intel Ethernet Connection (2) I218-V                                       | 3        | 1.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 3        | 1.1%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                   | 2        | 0.74%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 2        | 0.74%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                      | 2        | 0.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 2        | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 2        | 0.74%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 2        | 0.74%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 2        | 0.74%   |
| Intel Wireless 7260                                                        | 2        | 0.74%   |
| Intel Wireless 3160                                                        | 2        | 0.74%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 2        | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                                      | 2        | 0.74%   |
| Intel Ethernet Connection (17) I219-V                                      | 2        | 0.74%   |
| Intel Ethernet Connection (14) I219-V                                      | 2        | 0.74%   |
| Intel 82579V Gigabit Network Connection                                    | 2        | 0.74%   |
| Intel 82578DM Gigabit Network Connection                                   | 2        | 0.74%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 2        | 0.74%   |
| Intel 700 Series Chipset Family Wi-Fi                                      | 2        | 0.74%   |
| ZyDAS ZD1211B 802.11g                                                      | 1        | 0.37%   |
| Zoom Telephonics V.92 56K Mini External Modem Model 3095                   | 1        | 0.37%   |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU] | 1        | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 19       | 26.03%  |
| Intel                           | 19       | 26.03%  |
| Qualcomm Atheros                | 13       | 17.81%  |
| Ralink Technology               | 6        | 8.22%   |
| TP-Link                         | 4        | 5.48%   |
| Ralink                          | 2        | 2.74%   |
| ZyDAS                           | 1        | 1.37%   |
| TRENDnet                        | 1        | 1.37%   |
| Qualcomm Atheros Communications | 1        | 1.37%   |
| NetGear                         | 1        | 1.37%   |
| MediaTek                        | 1        | 1.37%   |
| Dell                            | 1        | 1.37%   |
| D-Link System                   | 1        | 1.37%   |
| Broadcom                        | 1        | 1.37%   |
| Belkin Components               | 1        | 1.37%   |
| ASUSTek Computer                | 1        | 1.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                            | 6        | 8.22%   |
| Realtek 802.11ac NIC                                                           | 4        | 5.48%   |
| Ralink MT7601U Wireless Adapter                                                | 4        | 5.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 3        | 4.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 3        | 4.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 3        | 4.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 3        | 4.11%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                       | 2        | 2.74%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                       | 2        | 2.74%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 2        | 2.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 2        | 2.74%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 2        | 2.74%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 2        | 2.74%   |
| Intel Wireless 7260                                                            | 2        | 2.74%   |
| Intel Wireless 3160                                                            | 2        | 2.74%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 2        | 2.74%   |
| Intel 700 Series Chipset Family Wi-Fi                                          | 2        | 2.74%   |
| ZyDAS ZD1211B 802.11g                                                          | 1        | 1.37%   |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU]     | 1        | 1.37%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                            | 1        | 1.37%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 1        | 1.37%   |
| TP-Link Archer T4U ver.3                                                       | 1        | 1.37%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 1        | 1.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 1        | 1.37%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 1        | 1.37%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 1        | 1.37%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                | 1        | 1.37%   |
| Ralink RT2770 Wireless Adapter                                                 | 1        | 1.37%   |
| Ralink RT2501/RT2573 Wireless Adapter                                          | 1        | 1.37%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                         | 1        | 1.37%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 1        | 1.37%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1        | 1.37%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                               | 1        | 1.37%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1        | 1.37%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 1        | 1.37%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                            | 1        | 1.37%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 1        | 1.37%   |
| Intel Wireless 7265                                                            | 1        | 1.37%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 1        | 1.37%   |
| Dell Wireless 1450 Dual-band (802.11a/b/g) Adapter [Intersil ISL3887]          | 1        | 1.37%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 107      | 57.22%  |
| Intel                    | 63       | 33.69%  |
| Nvidia                   | 4        | 2.14%   |
| Broadcom                 | 3        | 1.6%    |
| Qualcomm Atheros         | 2        | 1.07%   |
| Marvell Technology Group | 2        | 1.07%   |
| Broadcom Limited         | 2        | 1.07%   |
| OPPO Electronics         | 1        | 0.53%   |
| D-Link System            | 1        | 0.53%   |
| ASIX Electronics         | 1        | 0.53%   |
| Aquantia                 | 1        | 0.53%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 89       | 45.64%  |
| Realtek RTL8125 2.5GbE Controller                                 | 13       | 6.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10       | 5.13%   |
| Intel I211 Gigabit Network Connection                             | 9        | 4.62%   |
| Intel Ethernet Connection (2) I219-V                              | 9        | 4.62%   |
| Intel Ethernet Connection I217-LM                                 | 6        | 3.08%   |
| Nvidia MCP61 Ethernet                                             | 4        | 2.05%   |
| Intel Ethernet Controller I225-V                                  | 4        | 2.05%   |
| Intel Ethernet Connection I217-V                                  | 4        | 2.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 1.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 1.54%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.54%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 1.03%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 1.03%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 1.03%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 1.03%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.03%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 1.03%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.03%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 0.51%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.51%   |
| OPPO CPH2411                                                      | 1        | 0.51%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.51%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.51%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.51%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.51%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.51%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1        | 0.51%   |
| Intel 82541GI Gigabit Ethernet Controller                         | 1        | 0.51%   |
| Intel 82540EM Gigabit Ethernet Controller                         | 1        | 0.51%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 0.51%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.51%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 1        | 0.51%   |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                       | 1        | 0.51%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 0.51%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 0.51%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 172      | 70.49%  |
| WiFi     | 68       | 27.87%  |
| Modem    | 3        | 1.23%   |
| Unknown  | 1        | 0.41%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 140      | 78.21%  |
| WiFi     | 39       | 21.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 115      | 66.47%  |
| 2     | 50       | 28.9%   |
| 3     | 7        | 4.05%   |
| 4     | 1        | 0.58%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 110      | 63.22%  |
| Yes  | 64       | 36.78%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 18       | 35.29%  |
| Cambridge Silicon Radio         | 17       | 33.33%  |
| Realtek Semiconductor           | 6        | 11.76%  |
| Broadcom                        | 3        | 5.88%   |
| IMC Networks                    | 2        | 3.92%   |
| TP-Link                         | 1        | 1.96%   |
| Qualcomm Atheros Communications | 1        | 1.96%   |
| MediaTek                        | 1        | 1.96%   |
| Lite-On Technology              | 1        | 1.96%   |
| Fujitsu                         | 1        | 1.96%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 17       | 33.33%  |
| Intel AX200 Bluetooth                               | 6        | 11.76%  |
| Intel Bluetooth wireless interface                  | 5        | 9.8%    |
| Realtek Bluetooth Radio                             | 4        | 7.84%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 5.88%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 3.92%   |
| Intel Bluetooth Device                              | 2        | 3.92%   |
| IMC Networks Bluetooth Radio                        | 2        | 3.92%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 3.92%   |
| TP-Link UB500 Adapter                               | 1        | 1.96%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1        | 1.96%   |
| MediaTek Wireless_Device                            | 1        | 1.96%   |
| Lite-On Bluetooth Device                            | 1        | 1.96%   |
| Intel AX210 Bluetooth                               | 1        | 1.96%   |
| Intel AX201 Bluetooth                               | 1        | 1.96%   |
| Fujitsu Bluetooth Device                            | 1        | 1.96%   |
| Broadcom BCM2210 Bluetooth                          | 1        | 1.96%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 119      | 45.42%  |
| AMD                         | 59       | 22.52%  |
| Nvidia                      | 58       | 22.14%  |
| Creative Labs               | 4        | 1.53%   |
| C-Media Electronics         | 4        | 1.53%   |
| SAVITECH                    | 2        | 0.76%   |
| Logitech                    | 2        | 0.76%   |
| VIA Technologies            | 1        | 0.38%   |
| STMicroelectronics          | 1        | 0.38%   |
| Samson Technologies         | 1        | 0.38%   |
| PreSonus Audio Electronics  | 1        | 0.38%   |
| Micro Star International    | 1        | 0.38%   |
| Medeli Electronics          | 1        | 0.38%   |
| MAG Technology              | 1        | 0.38%   |
| Lenovo                      | 1        | 0.38%   |
| Kingston Technology         | 1        | 0.38%   |
| Hewlett-Packard             | 1        | 0.38%   |
| GN Netcom                   | 1        | 0.38%   |
| FiiO Electronics Technology | 1        | 0.38%   |
| Creative Technology         | 1        | 0.38%   |
| Corsair                     | 1        | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 18       | 5.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14       | 4.64%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 14       | 4.64%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 14       | 4.64%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 13       | 4.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12       | 3.97%   |
| Intel 200 Series PCH HD Audio                                                                     | 9        | 2.98%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9        | 2.98%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 8        | 2.65%   |
| AMD FCH Azalia Controller                                                                         | 8        | 2.65%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7        | 2.32%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7        | 2.32%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6        | 1.99%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6        | 1.99%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6        | 1.99%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6        | 1.99%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5        | 1.66%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 5        | 1.66%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 5        | 1.66%   |
| Nvidia MCP61 High Definition Audio                                                                | 4        | 1.32%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4        | 1.32%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 4        | 1.32%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4        | 1.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4        | 1.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4        | 1.32%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3        | 0.99%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3        | 0.99%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 3        | 0.99%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3        | 0.99%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3        | 0.99%   |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 3        | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3        | 0.99%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3        | 0.99%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3        | 0.99%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2        | 0.66%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2        | 0.66%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2        | 0.66%   |
| Nvidia GF100 High Definition Audio Controller                                                     | 2        | 0.66%   |
| Nvidia Audio device                                                                               | 2        | 0.66%   |
| Intel DG2 Audio Controller                                                                        | 2        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 26       | 18.57%  |
| Unknown             | 24       | 17.14%  |
| Samsung Electronics | 17       | 12.14%  |
| Crucial             | 14       | 10%     |
| SK hynix            | 11       | 7.86%   |
| G.Skill             | 11       | 7.86%   |
| Corsair             | 10       | 7.14%   |
| Ramaxel Technology  | 5        | 3.57%   |
| Nanya Technology    | 3        | 2.14%   |
| Micron Technology   | 3        | 2.14%   |
| Elpida              | 3        | 2.14%   |
| Unknown (ABCD)      | 2        | 1.43%   |
| A-DATA Technology   | 2        | 1.43%   |
| Unknown             | 2        | 1.43%   |
| Unknown (AB)        | 1        | 0.71%   |
| Transcend           | 1        | 0.71%   |
| Timetec             | 1        | 0.71%   |
| Qumo                | 1        | 0.71%   |
| GLOWAY              | 1        | 0.71%   |
| GIGA-BYTE           | 1        | 0.71%   |
| ASint Technology    | 1        | 0.71%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 3        | 2.03%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 2        | 1.35%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2        | 1.35%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 2        | 1.35%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 2        | 1.35%   |
| Ramaxel RAM RMUA5120ME86H9F-2666 4GB DIMM DDR4 2667MT/s        | 2        | 1.35%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 2        | 1.35%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 2        | 1.35%   |
| Kingston RAM 9905713-026.A00G 4GB DIMM DDR4 2667MT/s           | 2        | 1.35%   |
| Unknown                                                        | 2        | 1.35%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                      | 1        | 0.68%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                           | 1        | 0.68%   |
| Unknown RAM Module 4GB DIMM SDRAM                              | 1        | 0.68%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                           | 1        | 0.68%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 1        | 0.68%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                           | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                       | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                      | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR2 400MT/s                       | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                      | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR2                               | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM 5354MT/s                           | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 0.68%   |
| Unknown RAM Module 1GB DIMM DDR2                               | 1        | 0.68%   |
| Unknown RAM CL17-17-17 D4-2400 16384MB DIMM DDR4 2400MT/s      | 1        | 0.68%   |
| Unknown RAM 2400 C16 Series 8192MB DIMM DDR4 1200MT/s          | 1        | 0.68%   |
| Unknown RAM 1600 CL9 Series 8192MB DIMM DDR3 1066MT/s          | 1        | 0.68%   |
| Unknown (AB) RAM Module 2GB DIMM LPDDR3 1333MT/s               | 1        | 0.68%   |
| Transcend RAM Module 2GB DIMM DDR3 1333MT/s                    | 1        | 0.68%   |
| Timetec RAM UD3-1333 4GB DIMM DDR3 1333MT/s                    | 1        | 0.68%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                   | 1        | 0.68%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                   | 1        | 0.68%   |
| SK hynix RAM Module 16GB DIMM DDR4 2667MT/s                    | 1        | 0.68%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.68%   |
| SK hynix RAM HMT451U6BFR8A-PB 4096MB DIMM DDR3 1648MT/s        | 1        | 0.68%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1        | 0.68%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.68%   |
| SK hynix RAM HMT351U7EFR8C-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.68%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 1        | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 51       | 43.22%  |
| DDR4    | 46       | 38.98%  |
| SDRAM   | 6        | 5.08%   |
| Unknown | 6        | 5.08%   |
| DDR2    | 4        | 3.39%   |
| LPDDR4  | 2        | 1.69%   |
| DDR5    | 2        | 1.69%   |
| LPDDR3  | 1        | 0.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 109      | 93.97%  |
| SODIMM | 7        | 6.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 42       | 33.07%  |
| 4096  | 40       | 31.5%   |
| 2048  | 20       | 15.75%  |
| 16384 | 19       | 14.96%  |
| 32768 | 3        | 2.36%   |
| 1024  | 3        | 2.36%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 32       | 24.62%  |
| 1333    | 20       | 15.38%  |
| 2667    | 10       | 7.69%   |
| 2400    | 10       | 7.69%   |
| 3200    | 8        | 6.15%   |
| 3600    | 7        | 5.38%   |
| Unknown | 5        | 3.85%   |
| 3000    | 4        | 3.08%   |
| 3466    | 3        | 2.31%   |
| 2133    | 3        | 2.31%   |
| 1866    | 3        | 2.31%   |
| 2666    | 2        | 1.54%   |
| 1867    | 2        | 1.54%   |
| 1067    | 2        | 1.54%   |
| 1066    | 2        | 1.54%   |
| 800     | 2        | 1.54%   |
| 6000    | 1        | 0.77%   |
| 5354    | 1        | 0.77%   |
| 4800    | 1        | 0.77%   |
| 4000    | 1        | 0.77%   |
| 3866    | 1        | 0.77%   |
| 3400    | 1        | 0.77%   |
| 3333    | 1        | 0.77%   |
| 3020    | 1        | 0.77%   |
| 2800    | 1        | 0.77%   |
| 2000    | 1        | 0.77%   |
| 1800    | 1        | 0.77%   |
| 1648    | 1        | 0.77%   |
| 1639    | 1        | 0.77%   |
| 1334    | 1        | 0.77%   |
| 400     | 1        | 0.77%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 4        | 44.44%  |
| Brother Industries  | 3        | 33.33%  |
| Samsung Electronics | 1        | 11.11%  |
| Canon               | 1        | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Samsung SF-760 Series         | 1        | 11.11%  |
| HP DeskJet D1360              | 1        | 11.11%  |
| HP DeskJet 840c               | 1        | 11.11%  |
| HP DeskJet 810c/812c          | 1        | 11.11%  |
| HP Deskjet 3070 B611 series   | 1        | 11.11%  |
| Canon TS3500 series           | 1        | 11.11%  |
| Brother QL-560 Label Printer  | 1        | 11.11%  |
| Brother HL-2030 Laser Printer | 1        | 11.11%  |
| Brother DCP-7040              | 1        | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 3        | 60%     |
| Seiko Epson     | 1        | 20%     |
| Hewlett-Packard | 1        | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Canon CanoScan LiDE 100                | 2        | 40%     |
| Seiko Epson GT-9800F [Perfection 3200] | 1        | 20%     |
| HP ScanJet 7400c                       | 1        | 20%     |
| Canon CanoScan LiDE 110                | 1        | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 7        | 25%     |
| Microdia                    | 4        | 14.29%  |
| Realtek Semiconductor       | 2        | 7.14%   |
| Microsoft                   | 2        | 7.14%   |
| KYE Systems (Mouse Systems) | 2        | 7.14%   |
| Xiaomi                      | 1        | 3.57%   |
| Silicon Motion              | 1        | 3.57%   |
| Samsung Electronics         | 1        | 3.57%   |
| Ruision                     | 1        | 3.57%   |
| Quanta                      | 1        | 3.57%   |
| Jieli Technology            | 1        | 3.57%   |
| IMC Networks                | 1        | 3.57%   |
| Guillemot                   | 1        | 3.57%   |
| Generalplus Technology      | 1        | 3.57%   |
| Creative Technology         | 1        | 3.57%   |
| Apple                       | 1        | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Realtek FULL HD 1080P Webcam                   | 2        | 7.14%   |
| Logitech HD Pro Webcam C920                    | 2        | 7.14%   |
| Xiaomi Mi/Redmi series (PTP)                   | 1        | 3.57%   |
| Silicon Motion 300k Pixel Camera               | 1        | 3.57%   |
| Samsung Galaxy A5 (MTP)                        | 1        | 3.57%   |
| Ruision UVC Camera                             | 1        | 3.57%   |
| Quanta HP HD Camera                            | 1        | 3.57%   |
| Microsoft MicrosoftÂ LifeCam Studio           | 1        | 3.57%   |
| Microsoft LifeCam VX-2000                      | 1        | 3.57%   |
| Microdia Webcam Vitade AF                      | 1        | 3.57%   |
| Microdia USB 2.0 Camera                        | 1        | 3.57%   |
| Microdia Sonix USB 2.0 Camera                  | 1        | 3.57%   |
| Microdia Camera                                | 1        | 3.57%   |
| Logitech Webcam C300                           | 1        | 3.57%   |
| Logitech Webcam C110                           | 1        | 3.57%   |
| Logitech HD Webcam C525                        | 1        | 3.57%   |
| Logitech C922 Pro Stream Webcam                | 1        | 3.57%   |
| Logitech BRIO Ultra HD Webcam                  | 1        | 3.57%   |
| KYE Systems (Mouse Systems) iSlim 2020AF       | 1        | 3.57%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320 | 1        | 3.57%   |
| Jieli USB PHY 2.0                              | 1        | 3.57%   |
| IMC Networks USB2.0 UVC HD Webcam              | 1        | 3.57%   |
| Guillemot Hercules Dualpix Exchange            | 1        | 3.57%   |
| Generalplus GENERAL WEBCAM                     | 1        | 3.57%   |
| Creative Live! Cam Sync 1080p                  | 1        | 3.57%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                | 1        | 3.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Reiner SCT Kartensysteme | 1        | 50%     |
| In Focus Systems         | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Reiner SCT Kartensysteme cyberJack one | 1        | 50%     |
| In Focus Systems EMV Smartcard Reader  | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 148      | 84.57%  |
| 1     | 22       | 12.57%  |
| 2     | 4        | 2.29%   |
| 3     | 1        | 0.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Graphics card         | 14       | 46.67%  |
| Net/wireless          | 3        | 10%     |
| Unassigned class      | 2        | 6.67%   |
| Sound                 | 2        | 6.67%   |
| Multimedia controller | 2        | 6.67%   |
| Chipcard              | 2        | 6.67%   |
| Camera                | 2        | 6.67%   |
| Network               | 1        | 3.33%   |
| Net/ethernet          | 1        | 3.33%   |
| Dvb card              | 1        | 3.33%   |

