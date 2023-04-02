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

Total: 184

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 5.15.0-56-generic          | 17       | 11.11%  |
| 5.15.0-52-generic          | 16       | 10.46%  |
| 5.15.0-58-generic          | 9        | 5.88%   |
| 5.15.0-47-generic          | 9        | 5.88%   |
| 5.15.0-46-generic          | 9        | 5.88%   |
| 5.15.0-67-generic          | 7        | 4.58%   |
| 5.15.0-60-generic          | 7        | 4.58%   |
| 5.15.0-48-generic          | 6        | 3.92%   |
| 5.15.0-27-generic          | 6        | 3.92%   |
| 5.19.0-35-generic          | 5        | 3.27%   |
| 5.15.0-43-generic          | 5        | 3.27%   |
| 5.15.0-41-generic          | 5        | 3.27%   |
| 5.15.0-25-generic          | 5        | 3.27%   |
| 5.15.0-53-generic          | 4        | 2.61%   |
| 5.15.0-50-generic          | 4        | 2.61%   |
| 5.19.0-32-generic          | 3        | 1.96%   |
| 5.15.0-57-generic          | 3        | 1.96%   |
| 5.15.0-40-generic          | 3        | 1.96%   |
| 5.15.0-69-generic          | 2        | 1.31%   |
| 5.15.0-60-lowlatency       | 2        | 1.31%   |
| 5.15.0-33-generic          | 2        | 1.31%   |
| 5.15.0-30-generic          | 2        | 1.31%   |
| 6.2.7-060207-generic       | 1        | 0.65%   |
| 6.2.2-060202-generic       | 1        | 0.65%   |
| 6.1.10.mmn                 | 1        | 0.65%   |
| 6.1.0                      | 1        | 0.65%   |
| 6.0.0                      | 1        | 0.65%   |
| 5.4.0-122-generic          | 1        | 0.65%   |
| 5.19.13-xanmod1            | 1        | 0.65%   |
| 5.19.1                     | 1        | 0.65%   |
| 5.19.0-8.2-liquorix-amd64  | 1        | 0.65%   |
| 5.19.0-15.2-liquorix-amd64 | 1        | 0.65%   |
| 5.18.0                     | 1        | 0.65%   |
| 5.17.0-8-generic           | 1        | 0.65%   |
| 5.17.0-1003-oem            | 1        | 0.65%   |
| 5.15.0-57-lowlatency       | 1        | 0.65%   |
| 5.15.0-53-lowlatency       | 1        | 0.65%   |
| 5.15.0-50-lowlatency       | 1        | 0.65%   |
| 5.15.0-48-lowlatency       | 1        | 0.65%   |
| 5.15.0-46-lowlatency       | 1        | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 122      | 85.31%  |
| 5.19.0  | 10       | 6.99%   |
| 5.17.0  | 2        | 1.4%    |
| 6.2.7   | 1        | 0.7%    |
| 6.2.2   | 1        | 0.7%    |
| 6.1.10  | 1        | 0.7%    |
| 6.1.0   | 1        | 0.7%    |
| 6.0.0   | 1        | 0.7%    |
| 5.4.0   | 1        | 0.7%    |
| 5.19.13 | 1        | 0.7%    |
| 5.19.1  | 1        | 0.7%    |
| 5.18.0  | 1        | 0.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 122      | 85.31%  |
| 5.19    | 12       | 8.39%   |
| 6.2     | 2        | 1.4%    |
| 6.1     | 2        | 1.4%    |
| 5.17    | 2        | 1.4%    |
| 6.0     | 1        | 0.7%    |
| 5.4     | 1        | 0.7%    |
| 5.18    | 1        | 0.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 140      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| XFCE  | 135      | 96.43%  |
| GNOME | 3        | 2.14%   |
| KDE5  | 1        | 0.71%   |
| i3    | 1        | 0.71%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 137      | 96.48%  |
| Tty  | 5        | 3.52%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 115      | 82.14%  |
| Unknown | 14       | 10%     |
| GDM3    | 9        | 6.43%   |
| SDDM    | 1        | 0.71%   |
| GDM     | 1        | 0.71%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 44       | 31.43%  |
| fr_FR   | 22       | 15.71%  |
| de_DE   | 19       | 13.57%  |
| it_IT   | 14       | 10%     |
| pt_BR   | 9        | 6.43%   |
| en_CA   | 6        | 4.29%   |
| ru_RU   | 4        | 2.86%   |
| en_GB   | 4        | 2.86%   |
| nl_NL   | 2        | 1.43%   |
| es_AR   | 2        | 1.43%   |
| cs_CZ   | 2        | 1.43%   |
| tr_TR   | 1        | 0.71%   |
| sv_SE   | 1        | 0.71%   |
| ru_UA   | 1        | 0.71%   |
| pl_PL   | 1        | 0.71%   |
| hu_HU   | 1        | 0.71%   |
| fr_CH   | 1        | 0.71%   |
| fr_CA   | 1        | 0.71%   |
| es_CO   | 1        | 0.71%   |
| en_ZA   | 1        | 0.71%   |
| en_AU   | 1        | 0.71%   |
| C       | 1        | 0.71%   |
| Unknown | 1        | 0.71%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 84       | 59.57%  |
| EFI  | 57       | 40.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 127      | 90.71%  |
| Overlay | 5        | 3.57%   |
| Btrfs   | 5        | 3.57%   |
| Zfs     | 2        | 1.43%   |
| Ext3    | 1        | 0.71%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 84       | 58.74%  |
| Unknown | 30       | 20.98%  |
| MBR     | 29       | 20.28%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 108      | 77.14%  |
| Yes       | 32       | 22.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 89       | 63.12%  |
| Yes       | 52       | 36.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 36       | 25.71%  |
| MSI                 | 23       | 16.43%  |
| Gigabyte Technology | 22       | 15.71%  |
| Hewlett-Packard     | 13       | 9.29%   |
| Dell                | 10       | 7.14%   |
| ASRock              | 10       | 7.14%   |
| Lenovo              | 7        | 5%      |
| Intel               | 3        | 2.14%   |
| Acer                | 3        | 2.14%   |
| PCWare              | 2        | 1.43%   |
| Fujitsu             | 2        | 1.43%   |
| Foxconn             | 2        | 1.43%   |
| Packard Bell        | 1        | 0.71%   |
| OEM                 | 1        | 0.71%   |
| MACHINIST           | 1        | 0.71%   |
| Itautec             | 1        | 0.71%   |
| Hardkernel          | 1        | 0.71%   |
| eMachines           | 1        | 0.71%   |
| Unknown             | 1        | 0.71%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 4        | 2.86%   |
| MSI MS-7D43                         | 3        | 2.14%   |
| Dell OptiPlex 7010                  | 3        | 2.14%   |
| MSI MS-7D46                         | 2        | 1.43%   |
| MSI MS-7D25                         | 2        | 1.43%   |
| MSI MS-7C52                         | 2        | 1.43%   |
| MSI MS-7817                         | 2        | 1.43%   |
| ASUS K30AD_M31AD_M51AD              | 2        | 1.43%   |
| Unknown                             | 2        | 1.43%   |
| PCWare IPX1800E2                    | 1        | 0.71%   |
| PCWare IPMH81G1                     | 1        | 0.71%   |
| Packard Bell IMEDIA X9305           | 1        | 0.71%   |
| MSI MS-7E07                         | 1        | 0.71%   |
| MSI MS-7C91                         | 1        | 0.71%   |
| MSI MS-7C84                         | 1        | 0.71%   |
| MSI MS-7C56                         | 1        | 0.71%   |
| MSI MS-7C08                         | 1        | 0.71%   |
| MSI MS-7B98                         | 1        | 0.71%   |
| MSI MS-7A32                         | 1        | 0.71%   |
| MSI MS-7982                         | 1        | 0.71%   |
| MSI MS-7835                         | 1        | 0.71%   |
| MSI MS-7529                         | 1        | 0.71%   |
| MSI MS-7309                         | 1        | 0.71%   |
| MSI Hyrican PC A320M PRO-E          | 1        | 0.71%   |
| MACHINIST X99-RS9 V2.0              | 1        | 0.71%   |
| Lenovo V530S-07ICB 10TX0010PB       | 1        | 0.71%   |
| Lenovo ThinkCentre M90p 3282A9G     | 1        | 0.71%   |
| Lenovo ThinkCentre M83 10AM0010US   | 1        | 0.71%   |
| Lenovo ThinkCentre M72e 32675L2     | 1        | 0.71%   |
| Lenovo ThinkCentre M710e 10UR001LUS | 1        | 0.71%   |
| Lenovo ThinkCentre M58 7373A5G      | 1        | 0.71%   |
| Lenovo ThinkCentre M32 10BV000CMD   | 1        | 0.71%   |
| Itautec Infoway ST-4273             | 1        | 0.71%   |
| Intel X79                           | 1        | 0.71%   |
| Intel DH61AG AAG23736-507           | 1        | 0.71%   |
| Intel D525MW AAE93082-401           | 1        | 0.71%   |
| HP Z420 Workstation                 | 1        | 0.71%   |
| HP Z1 Entry Tower G5                | 1        | 0.71%   |
| HP ProLiant MicroServer             | 1        | 0.71%   |
| HP ProDesk 400 G2 MT (TPM DP)       | 1        | 0.71%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 9        | 6.43%   |
| ASUS PRIME          | 9        | 6.43%   |
| Lenovo ThinkCentre  | 6        | 4.29%   |
| HP Compaq           | 4        | 2.86%   |
| ASUS All            | 4        | 2.86%   |
| MSI MS-7D43         | 3        | 2.14%   |
| HP EliteDesk        | 3        | 2.14%   |
| ASUS TUF            | 3        | 2.14%   |
| ASUS ROG            | 3        | 2.14%   |
| Acer Veriton        | 3        | 2.14%   |
| MSI MS-7D46         | 2        | 1.43%   |
| MSI MS-7D25         | 2        | 1.43%   |
| MSI MS-7C52         | 2        | 1.43%   |
| MSI MS-7817         | 2        | 1.43%   |
| HP Pavilion         | 2        | 1.43%   |
| Gigabyte B550       | 2        | 1.43%   |
| ASUS P8H61-M        | 2        | 1.43%   |
| ASUS K30AD          | 2        | 1.43%   |
| Unknown             | 2        | 1.43%   |
| PCWare IPX1800E2    | 1        | 0.71%   |
| PCWare IPMH81G1     | 1        | 0.71%   |
| Packard Bell IMEDIA | 1        | 0.71%   |
| MSI MS-7E07         | 1        | 0.71%   |
| MSI MS-7C91         | 1        | 0.71%   |
| MSI MS-7C84         | 1        | 0.71%   |
| MSI MS-7C56         | 1        | 0.71%   |
| MSI MS-7C08         | 1        | 0.71%   |
| MSI MS-7B98         | 1        | 0.71%   |
| MSI MS-7A32         | 1        | 0.71%   |
| MSI MS-7982         | 1        | 0.71%   |
| MSI MS-7835         | 1        | 0.71%   |
| MSI MS-7529         | 1        | 0.71%   |
| MSI MS-7309         | 1        | 0.71%   |
| MSI Hyrican         | 1        | 0.71%   |
| MACHINIST X99-RS9   | 1        | 0.71%   |
| Lenovo V530S-07ICB  | 1        | 0.71%   |
| Itautec Infoway     | 1        | 0.71%   |
| Intel X79           | 1        | 0.71%   |
| Intel DH61AG        | 1        | 0.71%   |
| Intel D525MW        | 1        | 0.71%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2014 | 17       | 12.14%  |
| 2018 | 16       | 11.43%  |
| 2013 | 13       | 9.29%   |
| 2010 | 11       | 7.86%   |
| 2021 | 10       | 7.14%   |
| 2020 | 9        | 6.43%   |
| 2012 | 9        | 6.43%   |
| 2019 | 8        | 5.71%   |
| 2011 | 8        | 5.71%   |
| 2017 | 7        | 5%      |
| 2016 | 7        | 5%      |
| 2015 | 7        | 5%      |
| 2007 | 5        | 3.57%   |
| 2022 | 4        | 2.86%   |
| 2009 | 4        | 2.86%   |
| 2006 | 2        | 1.43%   |
| 2005 | 2        | 1.43%   |
| 2008 | 1        | 0.71%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 140      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 134      | 95.71%  |
| Enabled  | 6        | 4.29%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 140      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 33       | 23.57%  |
| 4.01-8.0    | 30       | 21.43%  |
| 3.01-4.0    | 26       | 18.57%  |
| 8.01-16.0   | 20       | 14.29%  |
| 32.01-64.0  | 17       | 12.14%  |
| 24.01-32.0  | 5        | 3.57%   |
| 1.01-2.0    | 4        | 2.86%   |
| 64.01-256.0 | 3        | 2.14%   |
| 2.01-3.0    | 2        | 1.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 63       | 42.57%  |
| 2.01-3.0  | 31       | 20.95%  |
| 3.01-4.0  | 23       | 15.54%  |
| 4.01-8.0  | 19       | 12.84%  |
| 8.01-16.0 | 6        | 4.05%   |
| 0.51-1.0  | 5        | 3.38%   |
| 0.01-0.5  | 1        | 0.68%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 53       | 37.06%  |
| 2      | 43       | 30.07%  |
| 3      | 22       | 15.38%  |
| 4      | 12       | 8.39%   |
| 5      | 6        | 4.2%    |
| 6      | 3        | 2.1%    |
| 7      | 2        | 1.4%    |
| 10     | 1        | 0.7%    |
| 9      | 1        | 0.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 74       | 52.48%  |
| Yes       | 67       | 47.52%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 140      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 87       | 62.14%  |
| Yes       | 53       | 37.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 104      | 74.29%  |
| Yes       | 36       | 25.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Germany      | 22       | 15.6%   |
| France       | 20       | 14.18%  |
| USA          | 19       | 13.48%  |
| Italy        | 14       | 9.93%   |
| Brazil       | 10       | 7.09%   |
| Canada       | 7        | 4.96%   |
| Sweden       | 5        | 3.55%   |
| Netherlands  | 5        | 3.55%   |
| Russia       | 4        | 2.84%   |
| UK           | 3        | 2.13%   |
| Switzerland  | 2        | 1.42%   |
| Poland       | 2        | 1.42%   |
| Norway       | 2        | 1.42%   |
| Greece       | 2        | 1.42%   |
| Czechia      | 2        | 1.42%   |
| Colombia     | 2        | 1.42%   |
| Belgium      | 2        | 1.42%   |
| Belarus      | 2        | 1.42%   |
| Argentina    | 2        | 1.42%   |
| Turkey       | 1        | 0.71%   |
| Taiwan       | 1        | 0.71%   |
| South Africa | 1        | 0.71%   |
| Slovenia     | 1        | 0.71%   |
| Romania      | 1        | 0.71%   |
| Portugal     | 1        | 0.71%   |
| Mexico       | 1        | 0.71%   |
| Iran         | 1        | 0.71%   |
| Indonesia    | 1        | 0.71%   |
| Hungary      | 1        | 0.71%   |
| Guernsey     | 1        | 0.71%   |
| Guadeloupe   | 1        | 0.71%   |
| Bulgaria     | 1        | 0.71%   |
| Australia    | 1        | 0.71%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Paris                | 5        | 3.45%   |
| Berlin               | 3        | 2.07%   |
| Witten               | 2        | 1.38%   |
| Stuttgart            | 2        | 1.38%   |
| Santiago de Cali     | 2        | 1.38%   |
| Rio de Janeiro       | 2        | 1.38%   |
| Munich               | 2        | 1.38%   |
| Milan                | 2        | 1.38%   |
| Clermont-Ferrand     | 2        | 1.38%   |
| Biella               | 2        | 1.38%   |
| Almere Stad          | 2        | 1.38%   |
| Żywiec              | 1        | 0.69%   |
| Zaltbommel           | 1        | 0.69%   |
| White House          | 1        | 0.69%   |
| Wettringen           | 1        | 0.69%   |
| Washington           | 1        | 0.69%   |
| Waghausel            | 1        | 0.69%   |
| Waarder              | 1        | 0.69%   |
| Vohenstrauss         | 1        | 0.69%   |
| Vohburg an der Donau | 1        | 0.69%   |
| Vicenza              | 1        | 0.69%   |
| Västerås           | 1        | 0.69%   |
| Valparaiso de Goias  | 1        | 0.69%   |
| Uppsala              | 1        | 0.69%   |
| Tourouvre            | 1        | 0.69%   |
| Toronto              | 1        | 0.69%   |
| Tijuana              | 1        | 0.69%   |
| The Hague            | 1        | 0.69%   |
| Terrace              | 1        | 0.69%   |
| Teresina             | 1        | 0.69%   |
| Tehran               | 1        | 0.69%   |
| Taichung             | 1        | 0.69%   |
| Surrey               | 1        | 0.69%   |
| Sölvesborg          | 1        | 0.69%   |
| Sofia                | 1        | 0.69%   |
| Schopfloch           | 1        | 0.69%   |
| Sassari              | 1        | 0.69%   |
| Santa Cruz           | 1        | 0.69%   |
| Salzgitter           | 1        | 0.69%   |
| Salisbury            | 1        | 0.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 43       | 69     | 16.23%  |
| Samsung Electronics         | 41       | 51     | 15.47%  |
| Seagate                     | 39       | 55     | 14.72%  |
| Toshiba                     | 19       | 19     | 7.17%   |
| Kingston                    | 18       | 23     | 6.79%   |
| Hitachi                     | 13       | 22     | 4.91%   |
| Sandisk                     | 12       | 17     | 4.53%   |
| Crucial                     | 12       | 17     | 4.53%   |
| PNY                         | 5        | 5      | 1.89%   |
| Intel                       | 5        | 5      | 1.89%   |
| HGST                        | 5        | 9      | 1.89%   |
| China                       | 5        | 5      | 1.89%   |
| A-DATA Technology           | 5        | 5      | 1.89%   |
| Unknown                     | 3        | 4      | 1.13%   |
| Patriot                     | 3        | 3      | 1.13%   |
| TEXTORM                     | 2        | 2      | 0.75%   |
| SK hynix                    | 2        | 2      | 0.75%   |
| OCZ                         | 2        | 2      | 0.75%   |
| Maxtor                      | 2        | 2      | 0.75%   |
| Intenso                     | 2        | 2      | 0.75%   |
| Gigabyte Technology         | 2        | 2      | 0.75%   |
| ASMT                        | 2        | 5      | 0.75%   |
| XPG                         | 1        | 1      | 0.38%   |
| Veno                        | 1        | 1      | 0.38%   |
| Vaseky                      | 1        | 1      | 0.38%   |
| USB3.0                      | 1        | 2      | 0.38%   |
| Silicon Motion              | 1        | 1      | 0.38%   |
| Realtek Semiconductor       | 1        | 1      | 0.38%   |
| Phison Electronics          | 1        | 2      | 0.38%   |
| Phison                      | 1        | 8      | 0.38%   |
| PHD 3.0                     | 1        | 1      | 0.38%   |
| Mushkin                     | 1        | 1      | 0.38%   |
| Micron Technology           | 1        | 1      | 0.38%   |
| Linux                       | 1        | 1      | 0.38%   |
| Lexar                       | 1        | 1      | 0.38%   |
| LaCie                       | 1        | 1      | 0.38%   |
| KIOXIA                      | 1        | 1      | 0.38%   |
| Kingston Technology Company | 1        | 3      | 0.38%   |
| KingFast                    | 1        | 1      | 0.38%   |
| KingDian                    | 1        | 1      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD  | 6        | 1.92%   |
| Crucial CT480BX500SSD1 480GB     | 5        | 1.6%    |
| Samsung SSD 860 EVO 500GB        | 4        | 1.28%   |
| Kingston SA400S37480G 480GB SSD  | 4        | 1.28%   |
| Toshiba HDWD110 1TB              | 3        | 0.96%   |
| Toshiba DT01ACA200 2TB           | 3        | 0.96%   |
| Toshiba DT01ACA100 1TB           | 3        | 0.96%   |
| Seagate ST500DM002-1BD142 500GB  | 3        | 0.96%   |
| Seagate ST1000DM003-1SB102 1TB   | 3        | 0.96%   |
| Samsung SSD 840 Series 120GB     | 3        | 0.96%   |
| WDC WD20EARS-00MVWB0 2TB         | 2        | 0.64%   |
| WDC WD10EZRZ-00HTKB0 1TB         | 2        | 0.64%   |
| WDC WD10EZEX-00BBHA0 1TB         | 2        | 0.64%   |
| Toshiba DT01ACA050 500GB         | 2        | 0.64%   |
| TEXTORM BM5 240GB SSD            | 2        | 0.64%   |
| Seagate ST9500420AS 500GB        | 2        | 0.64%   |
| Seagate ST500LM000-1EJ162 500GB  | 2        | 0.64%   |
| Seagate ST4000VX007-2DT166 4TB   | 2        | 0.64%   |
| Seagate ST4000DM004-2CV104 4TB   | 2        | 0.64%   |
| Seagate ST31000528AS 1TB         | 2        | 0.64%   |
| Seagate ST3000DM008-2DM166 3TB   | 2        | 0.64%   |
| Seagate ST2000DM008-2FR102 2TB   | 2        | 0.64%   |
| Seagate ST1000DM003-1ER162 1TB   | 2        | 0.64%   |
| Seagate ST1000DM003-1CH162 1TB   | 2        | 0.64%   |
| SanDisk SDSSDA240G 240GB         | 2        | 0.64%   |
| Samsung SSD 970 EVO Plus 250GB   | 2        | 0.64%   |
| Samsung SSD 970 EVO Plus 1TB     | 2        | 0.64%   |
| Samsung SSD 850 EVO 500GB        | 2        | 0.64%   |
| Samsung SSD 850 EVO 250GB        | 2        | 0.64%   |
| Samsung HM321HI 320GB            | 2        | 0.64%   |
| Samsung HD250HJ 250GB            | 2        | 0.64%   |
| PNY CS900 500GB SSD              | 2        | 0.64%   |
| Kingston SUV400S37120G 120GB SSD | 2        | 0.64%   |
| Kingston SA2000M81000G 1TB       | 2        | 0.64%   |
| Hitachi HDS721050CLA362 500GB    | 2        | 0.64%   |
| Hitachi HDS721010CLA332 1TB      | 2        | 0.64%   |
| Hitachi HDP725050GLA360 500GB    | 2        | 0.64%   |
| Crucial CT500MX500SSD1 500GB     | 2        | 0.64%   |
| A-DATA SU800 256GB SSD           | 2        | 0.64%   |
| XPG GAMMIX S11L 256GB            | 1        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 40       | 65     | 30.53%  |
| Seagate             | 39       | 53     | 29.77%  |
| Toshiba             | 16       | 16     | 12.21%  |
| Hitachi             | 13       | 22     | 9.92%   |
| Samsung Electronics | 10       | 14     | 7.63%   |
| HGST                | 5        | 9      | 3.82%   |
| ASMT                | 2        | 5      | 1.53%   |
| USB3.0              | 1        | 2      | 0.76%   |
| Unknown             | 1        | 1      | 0.76%   |
| PHD 3.0             | 1        | 1      | 0.76%   |
| Maxtor              | 1        | 1      | 0.76%   |
| LaCie               | 1        | 1      | 0.76%   |
| Hewlett-Packard     | 1        | 1      | 0.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 23       | 25     | 23.47%  |
| Kingston            | 15       | 18     | 15.31%  |
| Crucial             | 12       | 17     | 12.24%  |
| SanDisk             | 9        | 12     | 9.18%   |
| China               | 5        | 5      | 5.1%    |
| A-DATA Technology   | 5        | 5      | 5.1%    |
| PNY                 | 4        | 4      | 4.08%   |
| WDC                 | 3        | 3      | 3.06%   |
| Toshiba             | 3        | 3      | 3.06%   |
| Patriot             | 3        | 3      | 3.06%   |
| Intel               | 3        | 3      | 3.06%   |
| TEXTORM             | 2        | 2      | 2.04%   |
| OCZ                 | 2        | 2      | 2.04%   |
| Intenso             | 2        | 2      | 2.04%   |
| Veno                | 1        | 1      | 1.02%   |
| Vaseky              | 1        | 1      | 1.02%   |
| Micron Technology   | 1        | 1      | 1.02%   |
| Maxtor              | 1        | 1      | 1.02%   |
| Linux               | 1        | 1      | 1.02%   |
| KingFast            | 1        | 1      | 1.02%   |
| KingDian            | 1        | 1      | 1.02%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 98       | 191    | 45.58%  |
| SSD     | 81       | 111    | 37.67%  |
| NVMe    | 29       | 50     | 13.49%  |
| Unknown | 6        | 7      | 2.79%   |
| MMC     | 1        | 1      | 0.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 132      | 285    | 75.43%  |
| NVMe | 29       | 50     | 16.57%  |
| SAS  | 13       | 24     | 7.43%   |
| MMC  | 1        | 1      | 0.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 109      | 179    | 54.23%  |
| 0.51-1.0   | 48       | 62     | 23.88%  |
| 1.01-2.0   | 24       | 32     | 11.94%  |
| 3.01-4.0   | 13       | 21     | 6.47%   |
| 2.01-3.0   | 4        | 4      | 1.99%   |
| 4.01-10.0  | 2        | 2      | 1%      |
| 10.01-20.0 | 1        | 2      | 0.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 35       | 24.65%  |
| 251-500        | 31       | 21.83%  |
| 1001-2000      | 23       | 16.2%   |
| 501-1000       | 18       | 12.68%  |
| More than 3000 | 15       | 10.56%  |
| 2001-3000      | 9        | 6.34%   |
| 21-50          | 5        | 3.52%   |
| 1-20           | 5        | 3.52%   |
| 51-100         | 1        | 0.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 31       | 21.38%  |
| 251-500        | 26       | 17.93%  |
| 21-50          | 23       | 15.86%  |
| 101-250        | 23       | 15.86%  |
| 51-100         | 12       | 8.28%   |
| 501-1000       | 10       | 6.9%    |
| 1001-2000      | 8        | 5.52%   |
| 2001-3000      | 7        | 4.83%   |
| More than 3000 | 5        | 3.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Toshiba DT01ACA100 1TB            | 2        | 2      | 6.25%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD  | 1        | 1      | 3.13%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 1      | 3.13%   |
| WDC WD3200AAKS-00L9A0 320GB       | 1        | 1      | 3.13%   |
| WDC WD2500AAKS-00VSA0 250GB       | 1        | 1      | 3.13%   |
| WDC WD20EFRX-68AX9N0 2TB          | 1        | 1      | 3.13%   |
| WDC WD20EARS-00MVWB0 2TB          | 1        | 1      | 3.13%   |
| WDC WD2002FYPS-02W3B0 2TB         | 1        | 1      | 3.13%   |
| WDC WD10EZEX-60ZF5A0 1TB          | 1        | 1      | 3.13%   |
| WDC WD10EAVS-00D7B1 1TB           | 1        | 1      | 3.13%   |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1      | 3.13%   |
| WDC WD1003FBYX-01Y7B1 1TB         | 1        | 1      | 3.13%   |
| Seagate ST9250410AS 250GB         | 1        | 1      | 3.13%   |
| Seagate ST3750840AS 752GB         | 1        | 1      | 3.13%   |
| Seagate ST3250318AS 250GB         | 1        | 2      | 3.13%   |
| Seagate ST1000DM003-1ER162 1TB    | 1        | 1      | 3.13%   |
| Samsung Electronics SP2514N 250GB | 1        | 1      | 3.13%   |
| Samsung Electronics HM321HI 320GB | 1        | 2      | 3.13%   |
| Samsung Electronics HD753LJ 752GB | 1        | 1      | 3.13%   |
| Samsung Electronics HD250HJ 250GB | 1        | 1      | 3.13%   |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 3.13%   |
| PNY 69D03094-T 40GB SSD           | 1        | 1      | 3.13%   |
| Maxtor STM3160215AS 160GB         | 1        | 1      | 3.13%   |
| Intel SSDSC2BW120A4 120GB         | 1        | 1      | 3.13%   |
| Hitachi HDS722540VLAT20 40GB      | 1        | 1      | 3.13%   |
| Hitachi HDS721010CLA332 1TB       | 1        | 1      | 3.13%   |
| Hitachi HCP725032GLA380 320GB     | 1        | 2      | 3.13%   |
| HGST HUS724040ALA640 4TB          | 1        | 3      | 3.13%   |
| Hewlett-Packard VB0250EAVER 250GB | 1        | 1      | 3.13%   |
| Crucial CT128MX100SSD1 128GB      | 1        | 1      | 3.13%   |
| ASMT ASMT105x 2TB                 | 1        | 4      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 11     | 33.33%  |
| Seagate             | 4        | 5      | 13.33%  |
| Samsung Electronics | 4        | 6      | 13.33%  |
| Hitachi             | 3        | 4      | 10%     |
| Toshiba             | 2        | 2      | 6.67%   |
| PNY                 | 1        | 1      | 3.33%   |
| Maxtor              | 1        | 1      | 3.33%   |
| Intel               | 1        | 1      | 3.33%   |
| HGST                | 1        | 3      | 3.33%   |
| Hewlett-Packard     | 1        | 1      | 3.33%   |
| Crucial             | 1        | 1      | 3.33%   |
| ASMT                | 1        | 4      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 10     | 34.62%  |
| Seagate             | 4        | 5      | 15.38%  |
| Samsung Electronics | 4        | 6      | 15.38%  |
| Hitachi             | 3        | 4      | 11.54%  |
| Toshiba             | 2        | 2      | 7.69%   |
| Maxtor              | 1        | 1      | 3.85%   |
| HGST                | 1        | 3      | 3.85%   |
| Hewlett-Packard     | 1        | 1      | 3.85%   |
| ASMT                | 1        | 4      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 23       | 36     | 88.46%  |
| SSD  | 3        | 4      | 11.54%  |

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
| Works    | 82       | 168    | 49.4%   |
| Detected | 59       | 152    | 35.54%  |
| Malfunc  | 25       | 40     | 15.06%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 92       | 49.2%   |
| AMD                          | 42       | 22.46%  |
| Samsung Electronics          | 10       | 5.35%   |
| ASMedia Technology           | 6        | 3.21%   |
| Kingston Technology Company  | 5        | 2.67%   |
| JMicron Technology           | 5        | 2.67%   |
| SanDisk                      | 4        | 2.14%   |
| Phison Electronics           | 4        | 2.14%   |
| VIA Technologies             | 3        | 1.6%    |
| Nvidia                       | 3        | 1.6%    |
| SK hynix                     | 2        | 1.07%   |
| Silicon Motion               | 2        | 1.07%   |
| Silicon Image                | 2        | 1.07%   |
| Realtek Semiconductor        | 2        | 1.07%   |
| Shenzhen Longsys Electronics | 1        | 0.53%   |
| Marvell Technology Group     | 1        | 0.53%   |
| KIOXIA                       | 1        | 0.53%   |
| INNOGRIT                     | 1        | 0.53%   |
| Adaptec                      | 1        | 0.53%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 24       | 9.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13       | 5.39%   |
| AMD 400 Series Chipset SATA Controller                                                  | 9        | 3.73%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 7        | 2.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 2.9%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7        | 2.9%    |
| AMD 500 Series Chipset SATA Controller                                                  | 7        | 2.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 2.49%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 2.49%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 2.49%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6        | 2.49%   |
| AMD FCH SATA Controller D                                                               | 6        | 2.49%   |
| Intel SATA Controller [RAID mode]                                                       | 5        | 2.07%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 2.07%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 2.07%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 2.07%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 2.07%   |
| Kingston Company A2000 NVMe SSD                                                         | 4        | 1.66%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 4        | 1.66%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 1.66%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4        | 1.66%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 1.66%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.66%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 1.24%   |
| Nvidia MCP61 IDE                                                                        | 3        | 1.24%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.24%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 2        | 0.83%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 0.83%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                        | 2        | 0.83%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 0.83%   |
| SanDisk NVMe Controller                                                                 | 2        | 0.83%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 0.83%   |
| Phison E18 PCIe4 NVMe Controller                                                        | 2        | 0.83%   |
| Intel Non-Volatile memory controller                                                    | 2        | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2        | 0.83%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.83%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2        | 0.83%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.83%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 2        | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 116      | 62.03%  |
| IDE  | 32       | 17.11%  |
| NVMe | 29       | 15.51%  |
| RAID | 9        | 4.81%   |
| SAS  | 1        | 0.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 94       | 67.14%  |
| AMD    | 46       | 32.86%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 2.84%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 3        | 2.13%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3        | 2.13%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2        | 1.42%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.42%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 1.42%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.42%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 1.42%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 1.42%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 2        | 1.42%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 1.42%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 2        | 1.42%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 1.42%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.42%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 1.42%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 1.42%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 2        | 1.42%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 2        | 1.42%   |
| Intel 12th Gen Core i7-12700                | 2        | 1.42%   |
| Intel 12th Gen Core i3-12100                | 2        | 1.42%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 2        | 1.42%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 1.42%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.42%   |
| AMD Phenom II X4 955 Processor              | 2        | 1.42%   |
| AMD FX-6300 Six-Core Processor              | 2        | 1.42%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz          | 1        | 0.71%   |
| Intel Xeon CPU E5-2666 v3 @ 2.90GHz         | 1        | 0.71%   |
| Intel Xeon CPU E5-2658 v2 @ 2.40GHz         | 1        | 0.71%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz          | 1        | 0.71%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.71%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.71%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1        | 0.71%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 0.71%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 0.71%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.71%   |
| Intel Core i7-6800K CPU @ 3.40GHz           | 1        | 0.71%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.71%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 0.71%   |
| Intel Core i7-4771 CPU @ 3.50GHz            | 1        | 0.71%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 31       | 21.99%  |
| AMD Ryzen 5             | 17       | 12.06%  |
| Intel Core i3           | 14       | 9.93%   |
| Intel Core i7           | 13       | 9.22%   |
| Intel Celeron           | 10       | 7.09%   |
| Other                   | 8        | 5.67%   |
| AMD Ryzen 7             | 6        | 4.26%   |
| Intel Core 2 Duo        | 5        | 3.55%   |
| Intel Xeon              | 4        | 2.84%   |
| Intel Core 2 Quad       | 3        | 2.13%   |
| AMD Ryzen 9             | 3        | 2.13%   |
| AMD Phenom II X4        | 3        | 2.13%   |
| AMD FX                  | 3        | 2.13%   |
| Intel Pentium Dual-Core | 2        | 1.42%   |
| Intel Pentium 4         | 2        | 1.42%   |
| AMD Ryzen 3             | 2        | 1.42%   |
| AMD Athlon II X2        | 2        | 1.42%   |
| AMD Athlon 64 X2        | 2        | 1.42%   |
| AMD A8                  | 2        | 1.42%   |
| Intel Pentium           | 1        | 0.71%   |
| Intel Atom              | 1        | 0.71%   |
| AMD Turion II Neo       | 1        | 0.71%   |
| AMD Sempron             | 1        | 0.71%   |
| AMD Ryzen 7 PRO         | 1        | 0.71%   |
| AMD Phenom II X6        | 1        | 0.71%   |
| AMD Athlon II           | 1        | 0.71%   |
| AMD Athlon              | 1        | 0.71%   |
| AMD A10                 | 1        | 0.71%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 60       | 42.25%  |
| 2      | 37       | 26.06%  |
| 6      | 21       | 14.79%  |
| 8      | 9        | 6.34%   |
| 12     | 5        | 3.52%   |
| 1      | 3        | 2.11%   |
| 16     | 2        | 1.41%   |
| 10     | 2        | 1.41%   |
| 3      | 2        | 1.41%   |
| 14     | 1        | 0.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 140      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 76       | 54.29%  |
| 1      | 64       | 45.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 140      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 51       | 36.17%  |
| 0x306c3    | 12       | 8.51%   |
| 0x306a9    | 6        | 4.26%   |
| 0x206a7    | 6        | 4.26%   |
| 0x0800820d | 5        | 3.55%   |
| 0x08701021 | 4        | 2.84%   |
| 0x010000c8 | 4        | 2.84%   |
| 0x906ea    | 3        | 2.13%   |
| 0x90672    | 3        | 2.13%   |
| 0x506e3    | 3        | 2.13%   |
| 0x106e5    | 3        | 2.13%   |
| 0xb0671    | 2        | 1.42%   |
| 0x906e9    | 2        | 1.42%   |
| 0x406c3    | 2        | 1.42%   |
| 0x206d7    | 2        | 1.42%   |
| 0x1067a    | 2        | 1.42%   |
| 0x10676    | 2        | 1.42%   |
| 0x0a201016 | 2        | 1.42%   |
| 0x08108109 | 2        | 1.42%   |
| 0x06000852 | 2        | 1.42%   |
| 0xa0653    | 1        | 0.71%   |
| 0x906ed    | 1        | 0.71%   |
| 0x906eb    | 1        | 0.71%   |
| 0x706a1    | 1        | 0.71%   |
| 0x6fb      | 1        | 0.71%   |
| 0x406c4    | 1        | 0.71%   |
| 0x306f2    | 1        | 0.71%   |
| 0x306e4    | 1        | 0.71%   |
| 0x30679    | 1        | 0.71%   |
| 0x20652    | 1        | 0.71%   |
| 0x106ca    | 1        | 0.71%   |
| 0x0a601201 | 1        | 0.71%   |
| 0x0a50000c | 1        | 0.71%   |
| 0x0a20120a | 1        | 0.71%   |
| 0x08701013 | 1        | 0.71%   |
| 0x08600106 | 1        | 0.71%   |
| 0x08101016 | 1        | 0.71%   |
| 0x08001138 | 1        | 0.71%   |
| 0x08001137 | 1        | 0.71%   |
| 0x0700010f | 1        | 0.71%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 19       | 13.48%  |
| SandyBridge      | 13       | 9.22%   |
| KabyLake         | 13       | 9.22%   |
| Zen 2            | 11       | 7.8%    |
| IvyBridge        | 10       | 7.09%   |
| Zen+             | 9        | 6.38%   |
| K10              | 8        | 5.67%   |
| Penryn           | 7        | 4.96%   |
| Unknown          | 6        | 4.26%   |
| Zen 3            | 5        | 3.55%   |
| Skylake          | 5        | 3.55%   |
| Silvermont       | 5        | 3.55%   |
| Zen              | 4        | 2.84%   |
| Piledriver       | 4        | 2.84%   |
| Nehalem          | 3        | 2.13%   |
| Core             | 3        | 2.13%   |
| Alderlake Hybrid | 3        | 2.13%   |
| NetBurst         | 2        | 1.42%   |
| K8 Hammer        | 2        | 1.42%   |
| CometLake        | 2        | 1.42%   |
| Westmere         | 1        | 0.71%   |
| K10 Llano        | 1        | 0.71%   |
| Jaguar           | 1        | 0.71%   |
| Goldmont plus    | 1        | 0.71%   |
| Excavator        | 1        | 0.71%   |
| Broadwell        | 1        | 0.71%   |
| Bonnell          | 1        | 0.71%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 64       | 41.56%  |
| Nvidia | 50       | 32.47%  |
| AMD    | 40       | 25.97%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10       | 6.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9        | 5.81%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 7        | 4.52%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5        | 3.23%   |
| Intel HD Graphics 530                                                                    | 5        | 3.23%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5        | 3.23%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5        | 3.23%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4        | 2.58%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4        | 2.58%   |
| Intel HD Graphics 630                                                                    | 4        | 2.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 1.94%   |
| Intel AlderLake-S GT1                                                                    | 3        | 1.94%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3        | 1.94%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 2        | 1.29%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 1.29%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 2        | 1.29%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 1.29%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 1.29%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 1.29%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                                | 2        | 1.29%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2        | 1.29%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2        | 1.29%   |
| AMD RS880 [Radeon HD 4250]                                                               | 2        | 1.29%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 1.29%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2        | 1.29%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 2        | 1.29%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 1.29%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2        | 1.29%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2        | 1.29%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 0.65%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1        | 0.65%   |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1        | 0.65%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1        | 0.65%   |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 1        | 0.65%   |
| Nvidia GT218 [GeForce 310]                                                               | 1        | 0.65%   |
| Nvidia GP107GL [Quadro P620]                                                             | 1        | 0.65%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 0.65%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 0.65%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1        | 0.65%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 52       | 37.14%  |
| 1 x Nvidia     | 45       | 32.14%  |
| 1 x AMD        | 34       | 24.29%  |
| Intel + Nvidia | 3        | 2.14%   |
| Intel + AMD    | 3        | 2.14%   |
| AMD + Nvidia   | 2        | 1.43%   |
| 2 x AMD        | 1        | 0.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 104      | 74.29%  |
| Proprietary | 32       | 22.86%  |
| Unknown     | 4        | 2.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 86       | 60.99%  |
| 1.01-2.0   | 18       | 12.77%  |
| 0.51-1.0   | 12       | 8.51%   |
| 0.01-0.5   | 8        | 5.67%   |
| 3.01-4.0   | 7        | 4.96%   |
| 7.01-8.0   | 5        | 3.55%   |
| 8.01-16.0  | 3        | 2.13%   |
| 5.01-6.0   | 1        | 0.71%   |
| 2.01-3.0   | 1        | 0.71%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Dell                    | 23       | 16.31%  |
| Samsung Electronics     | 20       | 14.18%  |
| Hewlett-Packard         | 14       | 9.93%   |
| Goldstar                | 10       | 7.09%   |
| AOC                     | 10       | 7.09%   |
| Acer                    | 9        | 6.38%   |
| ViewSonic               | 6        | 4.26%   |
| BenQ                    | 6        | 4.26%   |
| Iiyama                  | 5        | 3.55%   |
| Philips                 | 4        | 2.84%   |
| Lenovo                  | 3        | 2.13%   |
| Fujitsu Siemens         | 3        | 2.13%   |
| Ancor Communications    | 3        | 2.13%   |
| Unknown                 | 2        | 1.42%   |
| Eizo                    | 2        | 1.42%   |
| ___                     | 1        | 0.71%   |
| Vestel Elektronik       | 1        | 0.71%   |
| Toshiba                 | 1        | 0.71%   |
| TEO                     | 1        | 0.71%   |
| TCL                     | 1        | 0.71%   |
| SNC                     | 1        | 0.71%   |
| RTK                     | 1        | 0.71%   |
| Packard Bell            | 1        | 0.71%   |
| Mi                      | 1        | 0.71%   |
| MAG                     | 1        | 0.71%   |
| LG Electronics          | 1        | 0.71%   |
| IBM                     | 1        | 0.71%   |
| Gateway                 | 1        | 0.71%   |
| Envision Peripherals    | 1        | 0.71%   |
| eMachines               | 1        | 0.71%   |
| Elo Touch               | 1        | 0.71%   |
| Denver                  | 1        | 0.71%   |
| Compal                  | 1        | 0.71%   |
| Chi Mei Optoelectronics | 1        | 0.71%   |
| ASUSTek Computer        | 1        | 0.71%   |
| Unknown                 | 1        | 0.71%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                 | 2        | 1.34%   |
| Philips 170S PHL082B 1280x1024 338x270mm 17.0-inch                     | 2        | 1.34%   |
| Hewlett-Packard 2309 HWP2821 1920x1080 510x287mm 23.0-inch             | 2        | 1.34%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                         | 2        | 1.34%   |
| ___ LCD Monitor ___1BBC 1920x540 140x90mm 6.6-inch                     | 1        | 0.67%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch          | 1        | 0.67%   |
| ViewSonic VX3276-UHD VSC5138 3840x2160 697x392mm 31.5-inch             | 1        | 0.67%   |
| ViewSonic VP2365 SERIES VSC7C28 1920x1080 509x286mm 23.0-inch          | 1        | 0.67%   |
| ViewSonic VA1948 SERIES VSCE827 1440x900 408x255mm 18.9-inch           | 1        | 0.67%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1        | 0.67%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                  | 1        | 0.67%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 1        | 0.67%   |
| Toshiba TV TSB0109 1920x1080                                           | 1        | 0.67%   |
| TEO TL765 TEO6700 1280x1024 338x270mm 17.0-inch                        | 1        | 0.67%   |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                       | 1        | 0.67%   |
| SNC SKP_E20-27 SNC2700 2560x1440 597x336mm 27.0-inch                   | 1        | 0.67%   |
| Samsung Electronics SyncMaster SAM0653 1920x1080                       | 1        | 0.67%   |
| Samsung Electronics SyncMaster SAM03E3 1680x1050 433x271mm 20.1-inch   | 1        | 0.67%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 408x306mm 20.1-inch   | 1        | 0.67%   |
| Samsung Electronics SyncMaster SAM00E5 1280x1024 338x270mm 17.0-inch   | 1        | 0.67%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch      | 1        | 0.67%   |
| Samsung Electronics SMB2430L SAM0645 1920x1080 521x293mm 23.5-inch     | 1        | 0.67%   |
| Samsung Electronics SM2333TN SAM06FC 1920x1080 477x268mm 21.5-inch     | 1        | 0.67%   |
| Samsung Electronics S24E650 SAM0C86 1920x1200 518x324mm 24.1-inch      | 1        | 0.67%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 1        | 0.67%   |
| Samsung Electronics S24B300 SAM08CC 1920x1080 521x293mm 23.5-inch      | 1        | 0.67%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch      | 1        | 0.67%   |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch       | 1        | 0.67%   |
| Samsung Electronics LCD Monitor SMB2430L 3840x1080                     | 1        | 0.67%   |
| Samsung Electronics LCD Monitor SMB2430L                               | 1        | 0.67%   |
| Samsung Electronics LCD Monitor SAM094E 1920x1080 890x500mm 40.2-inch  | 1        | 0.67%   |
| Samsung Electronics LCD Monitor SAM07BB 1360x768 410x256mm 19.0-inch   | 1        | 0.67%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                      | 1        | 0.67%   |
| Samsung Electronics LCD Monitor S22E450 1920x1080                      | 1        | 0.67%   |
| Samsung Electronics LC34G55T SAM711A 3440x1440 798x334mm 34.1-inch     | 1        | 0.67%   |
| Samsung Electronics C27R50x SAM0F9E 1920x1080 598x336mm 27.0-inch      | 1        | 0.67%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 598x337mm 27.0-inch      | 1        | 0.67%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 1        | 0.67%   |
| RTK FHD HDR RTK3B3A 1920x1080 344x195mm 15.6-inch                      | 1        | 0.67%   |
| Philips PHL 274E5 PHLC0C8 1920x1080 598x336mm 27.0-inch                | 1        | 0.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 64       | 46.38%  |
| 1280x1024 (SXGA)   | 11       | 7.97%   |
| 1366x768 (WXGA)    | 10       | 7.25%   |
| 1440x900 (WXGA+)   | 7        | 5.07%   |
| 3840x2160 (4K)     | 6        | 4.35%   |
| 1680x1050 (WSXGA+) | 6        | 4.35%   |
| 1600x900 (HD+)     | 6        | 4.35%   |
| 2560x1440 (QHD)    | 5        | 3.62%   |
| 3840x1080          | 3        | 2.17%   |
| 1920x1200 (WUXGA)  | 3        | 2.17%   |
| 1024x768 (XGA)     | 3        | 2.17%   |
| 3840x1600          | 2        | 1.45%   |
| 3440x1440          | 2        | 1.45%   |
| 2560x1600          | 2        | 1.45%   |
| 1600x1200          | 2        | 1.45%   |
| 1360x768           | 2        | 1.45%   |
| Unknown            | 2        | 1.45%   |
| 2288x1287          | 1        | 0.72%   |
| 1920x540           | 1        | 0.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 22       | 15.28%  |
| 23      | 18       | 12.5%   |
| 27      | 14       | 9.72%   |
| 21      | 12       | 8.33%   |
| 19      | 11       | 7.64%   |
| 18      | 10       | 6.94%   |
| Unknown | 10       | 6.94%   |
| 20      | 8        | 5.56%   |
| 17      | 8        | 5.56%   |
| 15      | 5        | 3.47%   |
| 31      | 4        | 2.78%   |
| 22      | 4        | 2.78%   |
| 40      | 2        | 1.39%   |
| 37      | 2        | 1.39%   |
| 34      | 2        | 1.39%   |
| 26      | 2        | 1.39%   |
| 142     | 1        | 0.69%   |
| 84      | 1        | 0.69%   |
| 72      | 1        | 0.69%   |
| 54      | 1        | 0.69%   |
| 49      | 1        | 0.69%   |
| 32      | 1        | 0.69%   |
| 30      | 1        | 0.69%   |
| 29      | 1        | 0.69%   |
| 25      | 1        | 0.69%   |
| 6       | 1        | 0.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 51       | 36.96%  |
| 401-500        | 42       | 30.43%  |
| 301-350        | 13       | 9.42%   |
| Unknown        | 10       | 7.25%   |
| 601-700        | 7        | 5.07%   |
| 801-900        | 4        | 2.9%    |
| 701-800        | 3        | 2.17%   |
| 351-400        | 2        | 1.45%   |
| 1501-2000      | 2        | 1.45%   |
| 1001-1500      | 2        | 1.45%   |
| More than 2000 | 1        | 0.72%   |
| 101-200        | 1        | 0.72%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 82       | 61.65%  |
| 16/10   | 22       | 16.54%  |
| 5/4     | 10       | 7.52%   |
| Unknown | 8        | 6.02%   |
| 4/3     | 5        | 3.76%   |
| 21/9    | 4        | 3.01%   |
| 32/9    | 1        | 0.75%   |
| 1.00    | 1        | 0.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 43       | 30.71%  |
| 151-200        | 26       | 18.57%  |
| 141-150        | 17       | 12.14%  |
| 301-350        | 15       | 10.71%  |
| Unknown        | 10       | 7.14%   |
| 351-500        | 9        | 6.43%   |
| 251-300        | 6        | 4.29%   |
| 101-110        | 5        | 3.57%   |
| More than 1000 | 4        | 2.86%   |
| 501-1000       | 4        | 2.86%   |
| 1-40           | 1        | 0.71%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 93       | 69.92%  |
| 101-120       | 21       | 15.79%  |
| Unknown       | 10       | 7.52%   |
| 121-160       | 5        | 3.76%   |
| 1-50          | 3        | 2.26%   |
| More than 240 | 1        | 0.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 115      | 82.14%  |
| 2     | 16       | 11.43%  |
| 0     | 6        | 4.29%   |
| 3     | 3        | 2.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 92       | 47.18%  |
| Intel                           | 59       | 30.26%  |
| Qualcomm Atheros                | 14       | 7.18%   |
| Ralink Technology               | 4        | 2.05%   |
| Nvidia                          | 3        | 1.54%   |
| Broadcom                        | 3        | 1.54%   |
| Marvell Technology Group        | 2        | 1.03%   |
| D-Link System                   | 2        | 1.03%   |
| Broadcom Limited                | 2        | 1.03%   |
| ZyDAS                           | 1        | 0.51%   |
| TRENDnet                        | 1        | 0.51%   |
| TP-Link                         | 1        | 0.51%   |
| Ralink                          | 1        | 0.51%   |
| Qualcomm Atheros Communications | 1        | 0.51%   |
| OPPO Electronics                | 1        | 0.51%   |
| NetGear                         | 1        | 0.51%   |
| Microchip Technology            | 1        | 0.51%   |
| Mellanox Technologies           | 1        | 0.51%   |
| MediaTek                        | 1        | 0.51%   |
| Dell                            | 1        | 0.51%   |
| Belkin Components               | 1        | 0.51%   |
| ASIX Electronics                | 1        | 0.51%   |
| Aquantia                        | 1        | 0.51%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 73       | 33.49%  |
| Realtek RTL8125 2.5GbE Controller                                          | 10       | 4.59%   |
| Intel I211 Gigabit Network Connection                                      | 8        | 3.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 7        | 3.21%   |
| Intel Wi-Fi 6 AX200                                                        | 6        | 2.75%   |
| Intel Ethernet Connection (2) I219-V                                       | 6        | 2.75%   |
| Intel Ethernet Connection I217-V                                           | 4        | 1.83%   |
| Intel Ethernet Connection I217-LM                                          | 4        | 1.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 3        | 1.38%   |
| Realtek 802.11ac NIC                                                       | 3        | 1.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 3        | 1.38%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 3        | 1.38%   |
| Nvidia MCP61 Ethernet                                                      | 3        | 1.38%   |
| Intel Ethernet Controller I225-V                                           | 3        | 1.38%   |
| Intel Ethernet Connection (7) I219-V                                       | 3        | 1.38%   |
| Intel Ethernet Connection (2) I218-V                                       | 3        | 1.38%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 3        | 1.38%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                   | 2        | 0.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 2        | 0.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 2        | 0.92%   |
| Ralink MT7601U Wireless Adapter                                            | 2        | 0.92%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 2        | 0.92%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 2        | 0.92%   |
| Intel Wireless 3160                                                        | 2        | 0.92%   |
| Intel Ethernet Connection (7) I219-LM                                      | 2        | 0.92%   |
| Intel Ethernet Connection (17) I219-V                                      | 2        | 0.92%   |
| Intel 82579V Gigabit Network Connection                                    | 2        | 0.92%   |
| Intel 82578DM Gigabit Network Connection                                   | 2        | 0.92%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 2        | 0.92%   |
| ZyDAS ZD1211B 802.11g                                                      | 1        | 0.46%   |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU] | 1        | 0.46%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                        | 1        | 0.46%   |
| Realtek USB 10/100/1G/2.5G LAN                                             | 1        | 0.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1        | 0.46%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 1        | 0.46%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1        | 0.46%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                 | 1        | 0.46%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 1        | 0.46%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 1        | 0.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 16       | 28.07%  |
| Realtek Semiconductor           | 13       | 22.81%  |
| Qualcomm Atheros                | 13       | 22.81%  |
| Ralink Technology               | 4        | 7.02%   |
| ZyDAS                           | 1        | 1.75%   |
| TRENDnet                        | 1        | 1.75%   |
| TP-Link                         | 1        | 1.75%   |
| Ralink                          | 1        | 1.75%   |
| Qualcomm Atheros Communications | 1        | 1.75%   |
| NetGear                         | 1        | 1.75%   |
| MediaTek                        | 1        | 1.75%   |
| Dell                            | 1        | 1.75%   |
| D-Link System                   | 1        | 1.75%   |
| Broadcom                        | 1        | 1.75%   |
| Belkin Components               | 1        | 1.75%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                   | 6        | 10.53%  |
| Realtek 802.11ac NIC                                                                  | 3        | 5.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 3        | 5.26%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 3        | 5.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 3        | 5.26%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 2        | 3.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 2        | 3.51%   |
| Ralink MT7601U Wireless Adapter                                                       | 2        | 3.51%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 2        | 3.51%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 2        | 3.51%   |
| Intel Wireless 3160                                                                   | 2        | 3.51%   |
| ZyDAS ZD1211B 802.11g                                                                 | 1        | 1.75%   |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU]            | 1        | 1.75%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                   | 1        | 1.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 1.75%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1        | 1.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1        | 1.75%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                            | 1        | 1.75%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1        | 1.75%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1        | 1.75%   |
| Ralink RT2770 Wireless Adapter                                                        | 1        | 1.75%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                 | 1        | 1.75%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 1        | 1.75%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1        | 1.75%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                      | 1        | 1.75%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg]        | 1        | 1.75%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                            | 1        | 1.75%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                                   | 1        | 1.75%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                         | 1        | 1.75%   |
| Intel Wireless 7265                                                                   | 1        | 1.75%   |
| Intel Wireless 7260                                                                   | 1        | 1.75%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 1        | 1.75%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                      | 1        | 1.75%   |
| Intel 700 Series Chipset Family Wi-Fi                                                 | 1        | 1.75%   |
| Dell Wireless 1450 Dual-band (802.11a/b/g) Adapter [Intersil ISL3887]                 | 1        | 1.75%   |
| D-Link System DWA-131 802.11n Wireless N Nano Adapter(rev.A1) [Realtek RTL8192SU]     | 1        | 1.75%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 1        | 1.75%   |
| Belkin Components F7D1102 N150/Surf Micro Wireless Adapter v1000 [Realtek RTL8188CUS] | 1        | 1.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 87       | 56.86%  |
| Intel                    | 51       | 33.33%  |
| Nvidia                   | 3        | 1.96%   |
| Qualcomm Atheros         | 2        | 1.31%   |
| Marvell Technology Group | 2        | 1.31%   |
| Broadcom Limited         | 2        | 1.31%   |
| Broadcom                 | 2        | 1.31%   |
| OPPO Electronics         | 1        | 0.65%   |
| D-Link System            | 1        | 0.65%   |
| ASIX Electronics         | 1        | 0.65%   |
| Aquantia                 | 1        | 0.65%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 73       | 45.91%  |
| Realtek RTL8125 2.5GbE Controller                                 | 10       | 6.29%   |
| Intel I211 Gigabit Network Connection                             | 8        | 5.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 4.4%    |
| Intel Ethernet Connection (2) I219-V                              | 6        | 3.77%   |
| Intel Ethernet Connection I217-V                                  | 4        | 2.52%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 2.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 1.89%   |
| Nvidia MCP61 Ethernet                                             | 3        | 1.89%   |
| Intel Ethernet Controller I225-V                                  | 3        | 1.89%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.89%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.26%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 1.26%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 1.26%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.26%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 1.26%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.26%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.63%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.63%   |
| OPPO RMX3263                                                      | 1        | 0.63%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.63%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.63%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.63%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.63%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.63%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.63%   |
| Intel 82541GI Gigabit Ethernet Controller                         | 1        | 0.63%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 0.63%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 1        | 0.63%   |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                       | 1        | 0.63%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 0.63%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 0.63%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 0.63%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 140      | 72.16%  |
| WiFi     | 52       | 26.8%   |
| Modem    | 1        | 0.52%   |
| Unknown  | 1        | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 118      | 80.82%  |
| WiFi     | 28       | 19.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 94       | 66.67%  |
| 2     | 40       | 28.37%  |
| 3     | 6        | 4.26%   |
| 4     | 1        | 0.71%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 89       | 62.68%  |
| Yes  | 53       | 37.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 15       | 39.47%  |
| Cambridge Silicon Radio         | 13       | 34.21%  |
| Realtek Semiconductor           | 2        | 5.26%   |
| IMC Networks                    | 2        | 5.26%   |
| Broadcom                        | 2        | 5.26%   |
| Qualcomm Atheros Communications | 1        | 2.63%   |
| MediaTek                        | 1        | 2.63%   |
| Lite-On Technology              | 1        | 2.63%   |
| Fujitsu                         | 1        | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13       | 34.21%  |
| Intel AX200 Bluetooth                               | 6        | 15.79%  |
| Intel Bluetooth wireless interface                  | 4        | 10.53%  |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 7.89%   |
| IMC Networks Bluetooth Radio                        | 2        | 5.26%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 2.63%   |
| Realtek Bluetooth Radio                             | 1        | 2.63%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1        | 2.63%   |
| MediaTek Wireless_Device                            | 1        | 2.63%   |
| Lite-On Bluetooth Device                            | 1        | 2.63%   |
| Intel Bluetooth Device                              | 1        | 2.63%   |
| Intel AX201 Bluetooth                               | 1        | 2.63%   |
| Fujitsu Bluetooth Device                            | 1        | 2.63%   |
| Broadcom BCM2210 Bluetooth                          | 1        | 2.63%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 94       | 44.76%  |
| AMD                         | 51       | 24.29%  |
| Nvidia                      | 46       | 21.9%   |
| C-Media Electronics         | 3        | 1.43%   |
| SAVITECH                    | 2        | 0.95%   |
| VIA Technologies            | 1        | 0.48%   |
| STMicroelectronics          | 1        | 0.48%   |
| Samson Technologies         | 1        | 0.48%   |
| Micro Star International    | 1        | 0.48%   |
| Medeli Electronics          | 1        | 0.48%   |
| MAG Technology              | 1        | 0.48%   |
| Logitech                    | 1        | 0.48%   |
| Lenovo                      | 1        | 0.48%   |
| Kingston Technology         | 1        | 0.48%   |
| Hewlett-Packard             | 1        | 0.48%   |
| GN Netcom                   | 1        | 0.48%   |
| FiiO Electronics Technology | 1        | 0.48%   |
| Creative Labs               | 1        | 0.48%   |
| Corsair                     | 1        | 0.48%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 15       | 6.15%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 12       | 4.92%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 11       | 4.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 11       | 4.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11       | 4.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10       | 4.1%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9        | 3.69%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 7        | 2.87%   |
| Intel 200 Series PCH HD Audio                                                                     | 7        | 2.87%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7        | 2.87%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7        | 2.87%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6        | 2.46%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6        | 2.46%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5        | 2.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5        | 2.05%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 5        | 2.05%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 5        | 2.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4        | 1.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4        | 1.64%   |
| AMD FCH Azalia Controller                                                                         | 4        | 1.64%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3        | 1.23%   |
| Nvidia MCP61 High Definition Audio                                                                | 3        | 1.23%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 3        | 1.23%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3        | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3        | 1.23%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3        | 1.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3        | 1.23%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3        | 1.23%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2        | 0.82%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2        | 0.82%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2        | 0.82%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2        | 0.82%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2        | 0.82%   |
| Nvidia Audio device                                                                               | 2        | 0.82%   |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 2        | 0.82%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 2        | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2        | 0.82%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2        | 0.82%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 2        | 0.82%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2        | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 24       | 20.51%  |
| Unknown             | 20       | 17.09%  |
| Samsung Electronics | 14       | 11.97%  |
| Crucial             | 12       | 10.26%  |
| SK hynix            | 9        | 7.69%   |
| G.Skill             | 9        | 7.69%   |
| Corsair             | 7        | 5.98%   |
| Ramaxel Technology  | 5        | 4.27%   |
| Micron Technology   | 3        | 2.56%   |
| Elpida              | 3        | 2.56%   |
| Nanya Technology    | 2        | 1.71%   |
| Unknown             | 2        | 1.71%   |
| Unknown (ABCD)      | 1        | 0.85%   |
| Transcend           | 1        | 0.85%   |
| Timetec             | 1        | 0.85%   |
| Qumo                | 1        | 0.85%   |
| GLOWAY              | 1        | 0.85%   |
| ASint Technology    | 1        | 0.85%   |
| A-DATA Technology   | 1        | 0.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 3        | 2.44%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 2        | 1.63%   |
| Ramaxel RAM RMUA5120ME86H9F-2666 4GB DIMM DDR4 2667MT/s      | 2        | 1.63%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s            | 2        | 1.63%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s        | 2        | 1.63%   |
| Kingston RAM 9905713-026.A00G 4GB DIMM DDR4 2667MT/s         | 2        | 1.63%   |
| Unknown                                                      | 2        | 1.63%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                    | 1        | 0.81%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                         | 1        | 0.81%   |
| Unknown RAM Module 4GB DIMM SDRAM                            | 1        | 0.81%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                         | 1        | 0.81%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                     | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                    | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM DDR2 400MT/s                     | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                    | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM DDR2                             | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM 5354MT/s                         | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 1        | 0.81%   |
| Unknown RAM Module 1GB DIMM DDR2                             | 1        | 0.81%   |
| Unknown RAM CL17-17-17 D4-2400 16384MB DIMM DDR4 2400MT/s    | 1        | 0.81%   |
| Unknown RAM 2400 C16 Series 8192MB DIMM DDR4 1200MT/s        | 1        | 0.81%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s | 1        | 0.81%   |
| Transcend RAM Module 2GB DIMM DDR3 1333MT/s                  | 1        | 0.81%   |
| Timetec RAM UD3-1333 4GB DIMM DDR3 1333MT/s                  | 1        | 0.81%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                 | 1        | 0.81%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                 | 1        | 0.81%   |
| SK hynix RAM Module 16GB DIMM DDR4 2667MT/s                  | 1        | 0.81%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s         | 1        | 0.81%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s         | 1        | 0.81%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 1        | 0.81%   |
| SK hynix RAM HMT351U7EFR8C-PB 4GB DIMM DDR3 1600MT/s         | 1        | 0.81%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s         | 1        | 0.81%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB DIMM DDR3 1333MT/s         | 1        | 0.81%   |
| SK hynix RAM DMT451E6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 1        | 0.81%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                    | 1        | 0.81%   |
| Samsung RAM Module 2GB DIMM DDR3 1066MT/s                    | 1        | 0.81%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1        | 0.81%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s        | 1        | 0.81%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 42       | 42.86%  |
| DDR4    | 41       | 41.84%  |
| Unknown | 5        | 5.1%    |
| SDRAM   | 4        | 4.08%   |
| DDR2    | 3        | 3.06%   |
| DDR5    | 2        | 2.04%   |
| LPDDR4  | 1        | 1.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 91       | 93.81%  |
| SODIMM | 6        | 6.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 36       | 33.96%  |
| 4096  | 34       | 32.08%  |
| 2048  | 16       | 15.09%  |
| 16384 | 14       | 13.21%  |
| 32768 | 3        | 2.83%   |
| 1024  | 3        | 2.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 26       | 24.3%   |
| 1333    | 17       | 15.89%  |
| 2667    | 10       | 9.35%   |
| 2400    | 8        | 7.48%   |
| 3200    | 7        | 6.54%   |
| 3600    | 5        | 4.67%   |
| 3000    | 4        | 3.74%   |
| 3466    | 3        | 2.8%    |
| Unknown | 3        | 2.8%    |
| 2666    | 2        | 1.87%   |
| 2133    | 2        | 1.87%   |
| 1867    | 2        | 1.87%   |
| 1866    | 2        | 1.87%   |
| 6000    | 1        | 0.93%   |
| 5354    | 1        | 0.93%   |
| 4800    | 1        | 0.93%   |
| 4000    | 1        | 0.93%   |
| 3866    | 1        | 0.93%   |
| 3400    | 1        | 0.93%   |
| 3020    | 1        | 0.93%   |
| 2800    | 1        | 0.93%   |
| 2000    | 1        | 0.93%   |
| 1800    | 1        | 0.93%   |
| 1648    | 1        | 0.93%   |
| 1334    | 1        | 0.93%   |
| 1067    | 1        | 0.93%   |
| 1066    | 1        | 0.93%   |
| 800     | 1        | 0.93%   |
| 400     | 1        | 0.93%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 3        | 42.86%  |
| Brother Industries  | 2        | 28.57%  |
| Samsung Electronics | 1        | 14.29%  |
| Canon               | 1        | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Samsung SF-760 Series         | 1        | 14.29%  |
| HP DeskJet D1360              | 1        | 14.29%  |
| HP DeskJet 840c               | 1        | 14.29%  |
| HP Deskjet 3070 B611 series   | 1        | 14.29%  |
| Canon TS3500 series           | 1        | 14.29%  |
| Brother HL-2030 Laser Printer | 1        | 14.29%  |
| Brother DCP-7040              | 1        | 14.29%  |

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
| Logitech                    | 6        | 27.27%  |
| Microdia                    | 4        | 18.18%  |
| Realtek Semiconductor       | 2        | 9.09%   |
| Microsoft                   | 2        | 9.09%   |
| Xiaomi                      | 1        | 4.55%   |
| Samsung Electronics         | 1        | 4.55%   |
| Quanta                      | 1        | 4.55%   |
| KYE Systems (Mouse Systems) | 1        | 4.55%   |
| IMC Networks                | 1        | 4.55%   |
| Guillemot                   | 1        | 4.55%   |
| Creative Technology         | 1        | 4.55%   |
| Apple                       | 1        | 4.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Realtek FULL HD 1080P Webcam             | 2        | 9.09%   |
| Logitech HD Pro Webcam C920              | 2        | 9.09%   |
| Xiaomi Mi/Redmi series (PTP)             | 1        | 4.55%   |
| Samsung Galaxy A5 (MTP)                  | 1        | 4.55%   |
| Quanta HP HD Camera                      | 1        | 4.55%   |
| Microsoft MicrosoftÂ LifeCam Studio     | 1        | 4.55%   |
| Microsoft LifeCam VX-2000                | 1        | 4.55%   |
| Microdia Webcam Vitade AF                | 1        | 4.55%   |
| Microdia USB 2.0 Camera                  | 1        | 4.55%   |
| Microdia Sonix USB 2.0 Camera            | 1        | 4.55%   |
| Microdia Camera                          | 1        | 4.55%   |
| Logitech Webcam C300                     | 1        | 4.55%   |
| Logitech HD Webcam C525                  | 1        | 4.55%   |
| Logitech C922 Pro Stream Webcam          | 1        | 4.55%   |
| Logitech BRIO Ultra HD Webcam            | 1        | 4.55%   |
| KYE Systems (Mouse Systems) iSlim 2020AF | 1        | 4.55%   |
| IMC Networks USB2.0 UVC HD Webcam        | 1        | 4.55%   |
| Guillemot Hercules Dualpix Exchange      | 1        | 4.55%   |
| Creative Live! Cam Sync 1080p            | 1        | 4.55%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 1        | 4.55%   |

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
| 0     | 123      | 87.23%  |
| 1     | 14       | 9.93%   |
| 2     | 3        | 2.13%   |
| 3     | 1        | 0.71%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Graphics card         | 11       | 55%     |
| Multimedia controller | 2        | 10%     |
| Chipcard              | 2        | 10%     |
| Camera                | 2        | 10%     |
| Unassigned class      | 1        | 5%      |
| Sound                 | 1        | 5%      |
| Net/ethernet          | 1        | 5%      |

