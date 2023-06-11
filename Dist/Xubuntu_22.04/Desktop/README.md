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

Total: 219

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 5.15.0-56-generic         | 18       | 9.94%   |
| 5.15.0-52-generic         | 16       | 8.84%   |
| 5.15.0-58-generic         | 9        | 4.97%   |
| 5.15.0-47-generic         | 9        | 4.97%   |
| 5.15.0-46-generic         | 9        | 4.97%   |
| 5.15.0-67-generic         | 8        | 4.42%   |
| 5.15.0-60-generic         | 8        | 4.42%   |
| 5.15.0-48-generic         | 6        | 3.31%   |
| 5.15.0-27-generic         | 6        | 3.31%   |
| 5.19.0-41-generic         | 5        | 2.76%   |
| 5.19.0-35-generic         | 5        | 2.76%   |
| 5.15.0-43-generic         | 5        | 2.76%   |
| 5.15.0-41-generic         | 5        | 2.76%   |
| 5.15.0-25-generic         | 5        | 2.76%   |
| 5.19.0-43-generic         | 4        | 2.21%   |
| 5.15.0-57-generic         | 4        | 2.21%   |
| 5.15.0-53-generic         | 4        | 2.21%   |
| 5.15.0-50-generic         | 4        | 2.21%   |
| 5.19.0-32-generic         | 3        | 1.66%   |
| 5.15.0-69-generic         | 3        | 1.66%   |
| 5.15.0-40-generic         | 3        | 1.66%   |
| 6.2.7-060207-generic      | 2        | 1.1%    |
| 5.15.0-71-lowlatency      | 2        | 1.1%    |
| 5.15.0-71-generic         | 2        | 1.1%    |
| 5.15.0-70-generic         | 2        | 1.1%    |
| 5.15.0-60-lowlatency      | 2        | 1.1%    |
| 5.15.0-33-generic         | 2        | 1.1%    |
| 5.15.0-30-generic         | 2        | 1.1%    |
| 6.3.3-060303-generic      | 1        | 0.55%   |
| 6.2.2-060202-generic      | 1        | 0.55%   |
| 6.2.10-060210-generic     | 1        | 0.55%   |
| 6.2.0-10005-tuxedo        | 1        | 0.55%   |
| 6.1.10.mmn                | 1        | 0.55%   |
| 6.1.0                     | 1        | 0.55%   |
| 6.0.0                     | 1        | 0.55%   |
| 5.4.0-122-generic         | 1        | 0.55%   |
| 5.19.13-xanmod1           | 1        | 0.55%   |
| 5.19.1                    | 1        | 0.55%   |
| 5.19.0-8.2-liquorix-amd64 | 1        | 0.55%   |
| 5.19.0-42-generic         | 1        | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 132      | 78.57%  |
| 5.19.0  | 20       | 11.9%   |
| 6.2.7   | 2        | 1.19%   |
| 5.17.0  | 2        | 1.19%   |
| 6.3.3   | 1        | 0.6%    |
| 6.2.2   | 1        | 0.6%    |
| 6.2.10  | 1        | 0.6%    |
| 6.2.0   | 1        | 0.6%    |
| 6.1.10  | 1        | 0.6%    |
| 6.1.0   | 1        | 0.6%    |
| 6.0.0   | 1        | 0.6%    |
| 5.4.0   | 1        | 0.6%    |
| 5.19.13 | 1        | 0.6%    |
| 5.19.1  | 1        | 0.6%    |
| 5.18.0  | 1        | 0.6%    |
| 5.13.0  | 1        | 0.6%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 132      | 78.57%  |
| 5.19    | 22       | 13.1%   |
| 6.2     | 5        | 2.98%   |
| 6.1     | 2        | 1.19%   |
| 5.17    | 2        | 1.19%   |
| 6.3     | 1        | 0.6%    |
| 6.0     | 1        | 0.6%    |
| 5.4     | 1        | 0.6%    |
| 5.18    | 1        | 0.6%    |
| 5.13    | 1        | 0.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 164      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| XFCE  | 159      | 96.95%  |
| GNOME | 3        | 1.83%   |
| KDE5  | 1        | 0.61%   |
| i3    | 1        | 0.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 160      | 96.39%  |
| Tty  | 6        | 3.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 137      | 83.54%  |
| Unknown | 15       | 9.15%   |
| GDM3    | 9        | 5.49%   |
| SDDM    | 2        | 1.22%   |
| GDM     | 1        | 0.61%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 56       | 34.15%  |
| fr_FR   | 24       | 14.63%  |
| de_DE   | 23       | 14.02%  |
| it_IT   | 14       | 8.54%   |
| pt_BR   | 9        | 5.49%   |
| en_CA   | 6        | 3.66%   |
| ru_RU   | 5        | 3.05%   |
| en_GB   | 5        | 3.05%   |
| pl_PL   | 2        | 1.22%   |
| nl_NL   | 2        | 1.22%   |
| es_AR   | 2        | 1.22%   |
| en_AU   | 2        | 1.22%   |
| cs_CZ   | 2        | 1.22%   |
| tr_TR   | 1        | 0.61%   |
| sv_SE   | 1        | 0.61%   |
| ru_UA   | 1        | 0.61%   |
| hu_HU   | 1        | 0.61%   |
| fr_CH   | 1        | 0.61%   |
| fr_CA   | 1        | 0.61%   |
| fr_BE   | 1        | 0.61%   |
| es_VE   | 1        | 0.61%   |
| es_CO   | 1        | 0.61%   |
| en_ZA   | 1        | 0.61%   |
| C       | 1        | 0.61%   |
| Unknown | 1        | 0.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 99       | 60%     |
| EFI  | 66       | 40%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 144      | 86.23%  |
| Tmpfs   | 10       | 5.99%   |
| Overlay | 5        | 2.99%   |
| Btrfs   | 5        | 2.99%   |
| Zfs     | 2        | 1.2%    |
| Ext3    | 1        | 0.6%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 102      | 60.36%  |
| MBR     | 36       | 21.3%   |
| Unknown | 31       | 18.34%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 126      | 76.36%  |
| Yes       | 39       | 23.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 106      | 63.86%  |
| Yes       | 60       | 36.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 38       | 23.17%  |
| MSI                 | 28       | 17.07%  |
| Gigabyte Technology | 26       | 15.85%  |
| Hewlett-Packard     | 17       | 10.37%  |
| ASRock              | 13       | 7.93%   |
| Dell                | 11       | 6.71%   |
| Lenovo              | 8        | 4.88%   |
| Acer                | 4        | 2.44%   |
| Intel               | 3        | 1.83%   |
| PCWare              | 2        | 1.22%   |
| Fujitsu             | 2        | 1.22%   |
| Foxconn             | 2        | 1.22%   |
| Unknown             | 2        | 1.22%   |
| Pegatron            | 1        | 0.61%   |
| Packard Bell        | 1        | 0.61%   |
| OEM                 | 1        | 0.61%   |
| Medion              | 1        | 0.61%   |
| MACHINIST           | 1        | 0.61%   |
| Itautec             | 1        | 0.61%   |
| Hardkernel          | 1        | 0.61%   |
| eMachines           | 1        | 0.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Dell OptiPlex 7010                  | 4        | 2.44%   |
| ASUS All Series                     | 4        | 2.44%   |
| MSI MS-7D43                         | 3        | 1.83%   |
| Unknown                             | 3        | 1.83%   |
| MSI MS-7D46                         | 2        | 1.22%   |
| MSI MS-7D25                         | 2        | 1.22%   |
| MSI MS-7C52                         | 2        | 1.22%   |
| MSI MS-7817                         | 2        | 1.22%   |
| MSI MS-7721                         | 2        | 1.22%   |
| ASUS K30AD_M31AD_M51AD              | 2        | 1.22%   |
| Pegatron FZ132AA-ABF m9456fr        | 1        | 0.61%   |
| PCWare IPX1800E2                    | 1        | 0.61%   |
| PCWare IPMH81G1                     | 1        | 0.61%   |
| Packard Bell IMEDIA X9305           | 1        | 0.61%   |
| MSI MS-7E07                         | 1        | 0.61%   |
| MSI MS-7D40                         | 1        | 0.61%   |
| MSI MS-7C91                         | 1        | 0.61%   |
| MSI MS-7C84                         | 1        | 0.61%   |
| MSI MS-7C56                         | 1        | 0.61%   |
| MSI MS-7C08                         | 1        | 0.61%   |
| MSI MS-7C02                         | 1        | 0.61%   |
| MSI MS-7B98                         | 1        | 0.61%   |
| MSI MS-7A32                         | 1        | 0.61%   |
| MSI MS-7982                         | 1        | 0.61%   |
| MSI MS-7835                         | 1        | 0.61%   |
| MSI MS-7758                         | 1        | 0.61%   |
| MSI MS-7529                         | 1        | 0.61%   |
| MSI MS-7309                         | 1        | 0.61%   |
| MSI Hyrican PC A320M PRO-E          | 1        | 0.61%   |
| Medion MS-7848                      | 1        | 0.61%   |
| MACHINIST X99-RS9 V2.0              | 1        | 0.61%   |
| Lenovo V530S-07ICB 10TX0010PB       | 1        | 0.61%   |
| Lenovo ThinkCentre M90p 3282A9G     | 1        | 0.61%   |
| Lenovo ThinkCentre M83 10AM0010US   | 1        | 0.61%   |
| Lenovo ThinkCentre M83 10AGS17E00   | 1        | 0.61%   |
| Lenovo ThinkCentre M72e 32675L2     | 1        | 0.61%   |
| Lenovo ThinkCentre M710e 10UR001LUS | 1        | 0.61%   |
| Lenovo ThinkCentre M58 7373A5G      | 1        | 0.61%   |
| Lenovo ThinkCentre M32 10BV000CMD   | 1        | 0.61%   |
| Itautec Infoway ST-4273             | 1        | 0.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 10       | 6.1%    |
| ASUS PRIME           | 10       | 6.1%    |
| Lenovo ThinkCentre   | 7        | 4.27%   |
| HP Compaq            | 4        | 2.44%   |
| ASUS All             | 4        | 2.44%   |
| Acer Veriton         | 4        | 2.44%   |
| MSI MS-7D43          | 3        | 1.83%   |
| HP EliteDesk         | 3        | 1.83%   |
| ASUS TUF             | 3        | 1.83%   |
| ASUS ROG             | 3        | 1.83%   |
| Unknown              | 3        | 1.83%   |
| MSI MS-7D46          | 2        | 1.22%   |
| MSI MS-7D25          | 2        | 1.22%   |
| MSI MS-7C52          | 2        | 1.22%   |
| MSI MS-7817          | 2        | 1.22%   |
| MSI MS-7721          | 2        | 1.22%   |
| HP Pavilion          | 2        | 1.22%   |
| Gigabyte B550        | 2        | 1.22%   |
| ASUS P8H61-M         | 2        | 1.22%   |
| ASUS K30AD           | 2        | 1.22%   |
| Pegatron FZ132AA-ABF | 1        | 0.61%   |
| PCWare IPX1800E2     | 1        | 0.61%   |
| PCWare IPMH81G1      | 1        | 0.61%   |
| Packard Bell IMEDIA  | 1        | 0.61%   |
| MSI MS-7E07          | 1        | 0.61%   |
| MSI MS-7D40          | 1        | 0.61%   |
| MSI MS-7C91          | 1        | 0.61%   |
| MSI MS-7C84          | 1        | 0.61%   |
| MSI MS-7C56          | 1        | 0.61%   |
| MSI MS-7C08          | 1        | 0.61%   |
| MSI MS-7C02          | 1        | 0.61%   |
| MSI MS-7B98          | 1        | 0.61%   |
| MSI MS-7A32          | 1        | 0.61%   |
| MSI MS-7982          | 1        | 0.61%   |
| MSI MS-7835          | 1        | 0.61%   |
| MSI MS-7758          | 1        | 0.61%   |
| MSI MS-7529          | 1        | 0.61%   |
| MSI MS-7309          | 1        | 0.61%   |
| MSI Hyrican          | 1        | 0.61%   |
| Medion MS-7848       | 1        | 0.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2014 | 19       | 11.59%  |
| 2013 | 17       | 10.37%  |
| 2018 | 16       | 9.76%   |
| 2021 | 13       | 7.93%   |
| 2010 | 13       | 7.93%   |
| 2020 | 10       | 6.1%    |
| 2012 | 10       | 6.1%    |
| 2019 | 9        | 5.49%   |
| 2016 | 9        | 5.49%   |
| 2011 | 9        | 5.49%   |
| 2017 | 8        | 4.88%   |
| 2015 | 8        | 4.88%   |
| 2022 | 6        | 3.66%   |
| 2009 | 5        | 3.05%   |
| 2007 | 5        | 3.05%   |
| 2008 | 3        | 1.83%   |
| 2006 | 2        | 1.22%   |
| 2005 | 2        | 1.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 164      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 157      | 95.73%  |
| Enabled  | 7        | 4.27%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 164      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 37       | 22.56%  |
| 4.01-8.0    | 33       | 20.12%  |
| 3.01-4.0    | 31       | 18.9%   |
| 8.01-16.0   | 24       | 14.63%  |
| 32.01-64.0  | 23       | 14.02%  |
| 24.01-32.0  | 6        | 3.66%   |
| 64.01-256.0 | 4        | 2.44%   |
| 1.01-2.0    | 4        | 2.44%   |
| 2.01-3.0    | 2        | 1.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 72       | 40.91%  |
| 2.01-3.0   | 37       | 21.02%  |
| 3.01-4.0   | 26       | 14.77%  |
| 4.01-8.0   | 23       | 13.07%  |
| 0.51-1.0   | 9        | 5.11%   |
| 8.01-16.0  | 7        | 3.98%   |
| 16.01-24.0 | 1        | 0.57%   |
| 0.01-0.5   | 1        | 0.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 63       | 37.5%   |
| 2      | 49       | 29.17%  |
| 3      | 26       | 15.48%  |
| 4      | 14       | 8.33%   |
| 5      | 7        | 4.17%   |
| 6      | 5        | 2.98%   |
| 7      | 2        | 1.19%   |
| 10     | 1        | 0.6%    |
| 9      | 1        | 0.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 84       | 50.91%  |
| Yes       | 81       | 49.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 164      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 100      | 60.61%  |
| Yes       | 65       | 39.39%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 119      | 72.12%  |
| Yes       | 46       | 27.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Germany      | 27       | 16.36%  |
| USA          | 25       | 15.15%  |
| France       | 22       | 13.33%  |
| Italy        | 14       | 8.48%   |
| Brazil       | 10       | 6.06%   |
| Canada       | 7        | 4.24%   |
| Sweden       | 6        | 3.64%   |
| Russia       | 5        | 3.03%   |
| Netherlands  | 5        | 3.03%   |
| Poland       | 4        | 2.42%   |
| UK           | 3        | 1.82%   |
| Belgium      | 3        | 1.82%   |
| Argentina    | 3        | 1.82%   |
| Switzerland  | 2        | 1.21%   |
| Norway       | 2        | 1.21%   |
| Greece       | 2        | 1.21%   |
| Czechia      | 2        | 1.21%   |
| Colombia     | 2        | 1.21%   |
| Belarus      | 2        | 1.21%   |
| Australia    | 2        | 1.21%   |
| Turkey       | 1        | 0.61%   |
| Taiwan       | 1        | 0.61%   |
| Spain        | 1        | 0.61%   |
| South Africa | 1        | 0.61%   |
| Slovenia     | 1        | 0.61%   |
| Romania      | 1        | 0.61%   |
| Portugal     | 1        | 0.61%   |
| Pakistan     | 1        | 0.61%   |
| Mexico       | 1        | 0.61%   |
| Iran         | 1        | 0.61%   |
| Indonesia    | 1        | 0.61%   |
| Hungary      | 1        | 0.61%   |
| Guernsey     | 1        | 0.61%   |
| Guadeloupe   | 1        | 0.61%   |
| Denmark      | 1        | 0.61%   |
| China        | 1        | 0.61%   |
| Bulgaria     | 1        | 0.61%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Paris                | 5        | 2.92%   |
| Berlin               | 4        | 2.34%   |
| Stuttgart            | 2        | 1.17%   |
| Schwerte             | 2        | 1.17%   |
| Santiago de Cali     | 2        | 1.17%   |
| Rio de Janeiro       | 2        | 1.17%   |
| Munich               | 2        | 1.17%   |
| Milan                | 2        | 1.17%   |
| Clermont-Ferrand     | 2        | 1.17%   |
| Biella               | 2        | 1.17%   |
| Amsterdam            | 2        | 1.17%   |
| Żywiec              | 1        | 0.58%   |
| Yvoir                | 1        | 0.58%   |
| Wojnicz              | 1        | 0.58%   |
| Wilhelmshaven        | 1        | 0.58%   |
| White House          | 1        | 0.58%   |
| Wettringen           | 1        | 0.58%   |
| Washington           | 1        | 0.58%   |
| Waghausel            | 1        | 0.58%   |
| Waarder              | 1        | 0.58%   |
| Vohenstrauss         | 1        | 0.58%   |
| Vohburg an der Donau | 1        | 0.58%   |
| Vicenza              | 1        | 0.58%   |
| Västerås           | 1        | 0.58%   |
| Valparaiso de Goias  | 1        | 0.58%   |
| Uppsala              | 1        | 0.58%   |
| Trois-Rivières      | 1        | 0.58%   |
| Tourouvre            | 1        | 0.58%   |
| Toronto              | 1        | 0.58%   |
| Tijuana              | 1        | 0.58%   |
| The Hague            | 1        | 0.58%   |
| Terrace              | 1        | 0.58%   |
| Teresina             | 1        | 0.58%   |
| Tehran               | 1        | 0.58%   |
| Taichung             | 1        | 0.58%   |
| Sydney               | 1        | 0.58%   |
| Surrey               | 1        | 0.58%   |
| St Petersburg        | 1        | 0.58%   |
| Springfield          | 1        | 0.58%   |
| Sölvesborg          | 1        | 0.58%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 55       | 86     | 17.68%  |
| Samsung Electronics         | 49       | 64     | 15.76%  |
| Seagate                     | 42       | 61     | 13.5%   |
| Kingston                    | 22       | 28     | 7.07%   |
| Toshiba                     | 21       | 23     | 6.75%   |
| Hitachi                     | 14       | 23     | 4.5%    |
| SanDisk                     | 13       | 18     | 4.18%   |
| Crucial                     | 13       | 19     | 4.18%   |
| China                       | 7        | 7      | 2.25%   |
| HGST                        | 6        | 10     | 1.93%   |
| A-DATA Technology           | 6        | 6      | 1.93%   |
| Unknown                     | 5        | 6      | 1.61%   |
| PNY                         | 5        | 5      | 1.61%   |
| Intel                       | 5        | 5      | 1.61%   |
| ASMT                        | 4        | 7      | 1.29%   |
| Patriot                     | 3        | 3      | 0.96%   |
| TEXTORM                     | 2        | 2      | 0.64%   |
| SK hynix                    | 2        | 2      | 0.64%   |
| Phison Electronics          | 2        | 4      | 0.64%   |
| OCZ                         | 2        | 2      | 0.64%   |
| Micron Technology           | 2        | 2      | 0.64%   |
| Maxtor                      | 2        | 2      | 0.64%   |
| Intenso                     | 2        | 2      | 0.64%   |
| Gigabyte Technology         | 2        | 2      | 0.64%   |
| Corsair                     | 2        | 2      | 0.64%   |
| XPG                         | 1        | 1      | 0.32%   |
| Veno                        | 1        | 1      | 0.32%   |
| Vaseky                      | 1        | 1      | 0.32%   |
| USB3.0                      | 1        | 2      | 0.32%   |
| TO Exter                    | 1        | 2      | 0.32%   |
| Silicon Motion              | 1        | 1      | 0.32%   |
| Realtek Semiconductor       | 1        | 1      | 0.32%   |
| Phison                      | 1        | 8      | 0.32%   |
| PHD 3.0                     | 1        | 1      | 0.32%   |
| Mushkin                     | 1        | 1      | 0.32%   |
| Linux                       | 1        | 1      | 0.32%   |
| Lexar                       | 1        | 1      | 0.32%   |
| LaCie                       | 1        | 1      | 0.32%   |
| KIOXIA                      | 1        | 1      | 0.32%   |
| Kingston Technology Company | 1        | 3      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 860 EVO 500GB                           | 7        | 1.92%   |
| Kingston SA400S37240G 240GB SSD                     | 6        | 1.64%   |
| Crucial CT480BX500SSD1 480GB                        | 6        | 1.64%   |
| Kingston SA400S37480G 480GB SSD                     | 5        | 1.37%   |
| Toshiba DT01ACA200 2TB                              | 4        | 1.1%    |
| Toshiba HDWD110 1TB                                 | 3        | 0.82%   |
| Toshiba DT01ACA100 1TB                              | 3        | 0.82%   |
| Seagate ST500DM002-1BD142 500GB                     | 3        | 0.82%   |
| Seagate ST4000DM004-2CV104 4TB                      | 3        | 0.82%   |
| Seagate ST1000DM003-1SB102 1TB                      | 3        | 0.82%   |
| Seagate ST1000DM003-1ER162 1TB                      | 3        | 0.82%   |
| Samsung SSD 850 EVO 500GB                           | 3        | 0.82%   |
| Samsung SSD 840 Series 120GB                        | 3        | 0.82%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 2        | 0.55%   |
| WDC WD20EARS-00MVWB0 2TB                            | 2        | 0.55%   |
| WDC WD10EZRZ-00HTKB0 1TB                            | 2        | 0.55%   |
| WDC WD10EZEX-00BBHA0 1TB                            | 2        | 0.55%   |
| Toshiba DT01ACA050 500GB                            | 2        | 0.55%   |
| TEXTORM BM5 240GB SSD                               | 2        | 0.55%   |
| Seagate ST9500420AS 500GB                           | 2        | 0.55%   |
| Seagate ST500LM000-1EJ162 500GB                     | 2        | 0.55%   |
| Seagate ST4000VX007-2DT166 4TB                      | 2        | 0.55%   |
| Seagate ST31000528AS 1TB                            | 2        | 0.55%   |
| Seagate ST3000DM008-2DM166 3TB                      | 2        | 0.55%   |
| Seagate ST2000DM008-2FR102 2TB                      | 2        | 0.55%   |
| Seagate ST2000DM001-1CH164 2TB                      | 2        | 0.55%   |
| Seagate ST1000DM003-1CH162 1TB                      | 2        | 0.55%   |
| SanDisk SDSSDA240G 240GB                            | 2        | 0.55%   |
| Samsung SSD 970 EVO Plus 250GB                      | 2        | 0.55%   |
| Samsung SSD 970 EVO Plus 1TB                        | 2        | 0.55%   |
| Samsung SSD 870 QVO 1TB                             | 2        | 0.55%   |
| Samsung SSD 870 EVO 250GB                           | 2        | 0.55%   |
| Samsung SSD 850 EVO 250GB                           | 2        | 0.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 2        | 0.55%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 2        | 0.55%   |
| Samsung HM321HI 320GB                               | 2        | 0.55%   |
| Samsung HD250HJ 250GB                               | 2        | 0.55%   |
| PNY CS900 500GB SSD                                 | 2        | 0.55%   |
| Kingston SV300S37A120G 120GB SSD                    | 2        | 0.55%   |
| Kingston SUV400S37120G 120GB SSD                    | 2        | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 50       | 80     | 33.33%  |
| Seagate             | 42       | 59     | 28%     |
| Toshiba             | 18       | 20     | 12%     |
| Hitachi             | 14       | 23     | 9.33%   |
| Samsung Electronics | 10       | 14     | 6.67%   |
| HGST                | 6        | 10     | 4%      |
| ASMT                | 4        | 7      | 2.67%   |
| USB3.0              | 1        | 2      | 0.67%   |
| Unknown             | 1        | 1      | 0.67%   |
| PHD 3.0             | 1        | 1      | 0.67%   |
| Maxtor              | 1        | 1      | 0.67%   |
| LaCie               | 1        | 1      | 0.67%   |
| Hewlett-Packard     | 1        | 1      | 0.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 29       | 34     | 25%     |
| Kingston            | 18       | 22     | 15.52%  |
| Crucial             | 13       | 19     | 11.21%  |
| SanDisk             | 10       | 13     | 8.62%   |
| China               | 7        | 7      | 6.03%   |
| A-DATA Technology   | 6        | 6      | 5.17%   |
| WDC                 | 5        | 5      | 4.31%   |
| PNY                 | 4        | 4      | 3.45%   |
| Toshiba             | 3        | 3      | 2.59%   |
| Patriot             | 3        | 3      | 2.59%   |
| Intel               | 3        | 3      | 2.59%   |
| TEXTORM             | 2        | 2      | 1.72%   |
| OCZ                 | 2        | 2      | 1.72%   |
| Intenso             | 2        | 2      | 1.72%   |
| Veno                | 1        | 1      | 0.86%   |
| Vaseky              | 1        | 1      | 0.86%   |
| TO Exter            | 1        | 2      | 0.86%   |
| Micron Technology   | 1        | 1      | 0.86%   |
| Maxtor              | 1        | 1      | 0.86%   |
| Linux               | 1        | 1      | 0.86%   |
| KingFast            | 1        | 1      | 0.86%   |
| KingDian            | 1        | 1      | 0.86%   |
| Corsair             | 1        | 1      | 0.86%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 113      | 220    | 44.49%  |
| SSD     | 97       | 135    | 38.19%  |
| NVMe    | 35       | 60     | 13.78%  |
| Unknown | 6        | 7      | 2.36%   |
| MMC     | 3        | 3      | 1.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 152      | 334    | 74.15%  |
| NVMe | 35       | 60     | 17.07%  |
| SAS  | 15       | 28     | 7.32%   |
| MMC  | 3        | 3      | 1.46%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 127      | 210    | 54.04%  |
| 0.51-1.0   | 59       | 76     | 25.11%  |
| 1.01-2.0   | 27       | 36     | 11.49%  |
| 3.01-4.0   | 14       | 24     | 5.96%   |
| 2.01-3.0   | 4        | 4      | 1.7%    |
| 4.01-10.0  | 3        | 3      | 1.28%   |
| 10.01-20.0 | 1        | 2      | 0.43%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 42       | 25.15%  |
| 251-500        | 35       | 20.96%  |
| 1001-2000      | 26       | 15.57%  |
| 501-1000       | 22       | 13.17%  |
| More than 3000 | 16       | 9.58%   |
| 2001-3000      | 11       | 6.59%   |
| 1-20           | 6        | 3.59%   |
| 21-50          | 5        | 2.99%   |
| 51-100         | 4        | 2.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 39       | 22.81%  |
| 251-500        | 27       | 15.79%  |
| 21-50          | 27       | 15.79%  |
| 101-250        | 26       | 15.2%   |
| 501-1000       | 15       | 8.77%   |
| 51-100         | 15       | 8.77%   |
| 1001-2000      | 9        | 5.26%   |
| 2001-3000      | 7        | 4.09%   |
| More than 3000 | 6        | 3.51%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Toshiba DT01ACA100 1TB            | 2        | 2      | 5.71%   |
| Seagate ST1000DM003-1ER162 1TB    | 2        | 2      | 5.71%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD  | 1        | 1      | 2.86%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 1      | 2.86%   |
| WDC WD3200AAKS-00L9A0 320GB       | 1        | 1      | 2.86%   |
| WDC WD2500AAKS-00VSA0 250GB       | 1        | 1      | 2.86%   |
| WDC WD20EFRX-68AX9N0 2TB          | 1        | 1      | 2.86%   |
| WDC WD20EARS-00MVWB0 2TB          | 1        | 1      | 2.86%   |
| WDC WD2002FYPS-02W3B0 2TB         | 1        | 1      | 2.86%   |
| WDC WD10EZEX-60ZF5A0 1TB          | 1        | 1      | 2.86%   |
| WDC WD10EAVS-00D7B1 1TB           | 1        | 1      | 2.86%   |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1      | 2.86%   |
| WDC WD1003FBYX-01Y7B1 1TB         | 1        | 1      | 2.86%   |
| Seagate ST9250410AS 250GB         | 1        | 1      | 2.86%   |
| Seagate ST3750840AS 752GB         | 1        | 1      | 2.86%   |
| Seagate ST3250318AS 250GB         | 1        | 2      | 2.86%   |
| Seagate ST2000DM001-1CH164 2TB    | 1        | 1      | 2.86%   |
| Samsung Electronics SP2514N 250GB | 1        | 1      | 2.86%   |
| Samsung Electronics HM321HI 320GB | 1        | 2      | 2.86%   |
| Samsung Electronics HD753LJ 752GB | 1        | 1      | 2.86%   |
| Samsung Electronics HD250HJ 250GB | 1        | 1      | 2.86%   |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 2.86%   |
| PNY 69D03094-T 40GB SSD           | 1        | 1      | 2.86%   |
| Maxtor STM3160215AS 160GB         | 1        | 1      | 2.86%   |
| Intel SSDSC2BW120A4 120GB         | 1        | 1      | 2.86%   |
| Hitachi HDS722540VLAT20 40GB      | 1        | 1      | 2.86%   |
| Hitachi HDS721010CLA332 1TB       | 1        | 1      | 2.86%   |
| Hitachi HCP725032GLA380 320GB     | 1        | 2      | 2.86%   |
| HGST HUS724040ALA640 4TB          | 1        | 3      | 2.86%   |
| Hewlett-Packard VB0250EAVER 250GB | 1        | 1      | 2.86%   |
| Crucial CT128MX100SSD1 128GB      | 1        | 1      | 2.86%   |
| China SATA SSD 16GB               | 1        | 1      | 2.86%   |
| ASMT ASMT105x 2TB                 | 1        | 4      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 11     | 30.3%   |
| Seagate             | 6        | 7      | 18.18%  |
| Samsung Electronics | 4        | 6      | 12.12%  |
| Hitachi             | 3        | 4      | 9.09%   |
| Toshiba             | 2        | 2      | 6.06%   |
| PNY                 | 1        | 1      | 3.03%   |
| Maxtor              | 1        | 1      | 3.03%   |
| Intel               | 1        | 1      | 3.03%   |
| HGST                | 1        | 3      | 3.03%   |
| Hewlett-Packard     | 1        | 1      | 3.03%   |
| Crucial             | 1        | 1      | 3.03%   |
| China               | 1        | 1      | 3.03%   |
| ASMT                | 1        | 4      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 10     | 32.14%  |
| Seagate             | 6        | 7      | 21.43%  |
| Samsung Electronics | 4        | 6      | 14.29%  |
| Hitachi             | 3        | 4      | 10.71%  |
| Toshiba             | 2        | 2      | 7.14%   |
| Maxtor              | 1        | 1      | 3.57%   |
| HGST                | 1        | 3      | 3.57%   |
| Hewlett-Packard     | 1        | 1      | 3.57%   |
| ASMT                | 1        | 4      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 25       | 38     | 86.21%  |
| SSD  | 4        | 5      | 13.79%  |

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
| Works    | 95       | 197    | 49.48%  |
| Detected | 69       | 185    | 35.94%  |
| Malfunc  | 28       | 43     | 14.58%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 110      | 48.89%  |
| AMD                          | 47       | 20.89%  |
| Samsung Electronics          | 13       | 5.78%   |
| ASMedia Technology           | 7        | 3.11%   |
| Phison Electronics           | 6        | 2.67%   |
| Kingston Technology Company  | 6        | 2.67%   |
| JMicron Technology           | 6        | 2.67%   |
| SanDisk                      | 4        | 1.78%   |
| Nvidia                       | 4        | 1.78%   |
| VIA Technologies             | 3        | 1.33%   |
| Silicon Image                | 3        | 1.33%   |
| Marvell Technology Group     | 3        | 1.33%   |
| SK hynix                     | 2        | 0.89%   |
| Silicon Motion               | 2        | 0.89%   |
| Realtek Semiconductor        | 2        | 0.89%   |
| Shenzhen Longsys Electronics | 1        | 0.44%   |
| Micron Technology            | 1        | 0.44%   |
| LSI Logic / Symbios Logic    | 1        | 0.44%   |
| KIOXIA                       | 1        | 0.44%   |
| INNOGRIT                     | 1        | 0.44%   |
| ADATA Technology             | 1        | 0.44%   |
| Adaptec                      | 1        | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 28       | 9.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15       | 5.28%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10       | 3.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8        | 2.82%   |
| Intel SATA Controller [RAID mode]                                                       | 8        | 2.82%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 8        | 2.82%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 2.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 2.82%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 2.46%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7        | 2.46%   |
| AMD 500 Series Chipset SATA Controller                                                  | 7        | 2.46%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 2.11%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 2.11%   |
| AMD FCH SATA Controller D                                                               | 6        | 2.11%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 1.76%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 1.76%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5        | 1.76%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 1.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 1.76%   |
| Nvidia MCP61 SATA Controller                                                            | 4        | 1.41%   |
| Kingston Company A2000 NVMe SSD                                                         | 4        | 1.41%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.41%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                        | 3        | 1.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 1.06%   |
| Nvidia MCP61 IDE                                                                        | 3        | 1.06%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.06%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.06%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.06%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 2        | 0.7%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 0.7%    |
| SanDisk WD Black SN770 NVMe SSD                                                         | 2        | 0.7%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 0.7%    |
| Phison E18 PCIe4 NVMe Controller                                                        | 2        | 0.7%    |
| Intel Non-Volatile memory controller                                                    | 2        | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2        | 0.7%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.7%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 0.7%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 134      | 60.91%  |
| NVMe | 35       | 15.91%  |
| IDE  | 35       | 15.91%  |
| RAID | 14       | 6.36%   |
| SAS  | 1        | 0.45%   |
| SCSI | 1        | 0.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 112      | 68.29%  |
| AMD    | 52       | 31.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 5        | 3.03%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 1.82%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 3        | 1.82%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 3        | 1.82%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3        | 1.82%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2        | 1.21%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 2        | 1.21%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 1.21%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.21%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 1.21%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 2        | 1.21%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 1.21%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 1.21%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 2        | 1.21%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 1.21%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.21%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 2        | 1.21%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 1.21%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 1.21%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 2        | 1.21%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 2        | 1.21%   |
| Intel 13th Gen Core i7-13700KF              | 2        | 1.21%   |
| Intel 12th Gen Core i7-12700                | 2        | 1.21%   |
| Intel 12th Gen Core i3-12100                | 2        | 1.21%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 2        | 1.21%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 1.21%   |
| AMD Ryzen 5 3600XT 6-Core Processor         | 2        | 1.21%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.21%   |
| AMD Phenom II X4 955 Processor              | 2        | 1.21%   |
| AMD FX-6300 Six-Core Processor              | 2        | 1.21%   |
| Intel Xeon CPU X5687 @ 3.60GHz              | 1        | 0.61%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz          | 1        | 0.61%   |
| Intel Xeon CPU E5-2666 v3 @ 2.90GHz         | 1        | 0.61%   |
| Intel Xeon CPU E5-2658 v2 @ 2.40GHz         | 1        | 0.61%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz          | 1        | 0.61%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.61%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.61%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1        | 0.61%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 0.61%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 33       | 20%     |
| AMD Ryzen 5             | 19       | 11.52%  |
| Intel Core i7           | 18       | 10.91%  |
| Intel Core i3           | 17       | 10.3%   |
| Intel Celeron           | 13       | 7.88%   |
| Other                   | 10       | 6.06%   |
| AMD Ryzen 7             | 6        | 3.64%   |
| Intel Xeon              | 5        | 3.03%   |
| Intel Core 2 Quad       | 5        | 3.03%   |
| Intel Core 2 Duo        | 5        | 3.03%   |
| AMD A8                  | 4        | 2.42%   |
| AMD Ryzen 9             | 3        | 1.82%   |
| AMD Phenom II X4        | 3        | 1.82%   |
| AMD FX                  | 3        | 1.82%   |
| AMD Athlon II X2        | 3        | 1.82%   |
| Intel Pentium Dual-Core | 2        | 1.21%   |
| Intel Pentium 4         | 2        | 1.21%   |
| AMD Ryzen 3             | 2        | 1.21%   |
| AMD Athlon 64 X2        | 2        | 1.21%   |
| Intel Pentium           | 1        | 0.61%   |
| Intel Atom              | 1        | 0.61%   |
| AMD Turion II Neo       | 1        | 0.61%   |
| AMD Sempron             | 1        | 0.61%   |
| AMD Ryzen 7 PRO         | 1        | 0.61%   |
| AMD Phenom II X6        | 1        | 0.61%   |
| AMD GX                  | 1        | 0.61%   |
| AMD Athlon II           | 1        | 0.61%   |
| AMD Athlon              | 1        | 0.61%   |
| AMD A10                 | 1        | 0.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 73       | 43.98%  |
| 2      | 44       | 26.51%  |
| 6      | 23       | 13.86%  |
| 8      | 10       | 6.02%   |
| 12     | 5        | 3.01%   |
| 1      | 3        | 1.81%   |
| 16     | 2        | 1.2%    |
| 10     | 2        | 1.2%    |
| 3      | 2        | 1.2%    |
| 24     | 1        | 0.6%    |
| 14     | 1        | 0.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 164      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 91       | 55.49%  |
| 1      | 73       | 44.51%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 164      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 61       | 36.97%  |
| 0x306c3    | 14       | 8.48%   |
| 0x306a9    | 7        | 4.24%   |
| 0x206a7    | 7        | 4.24%   |
| 0x0800820d | 5        | 3.03%   |
| 0x506e3    | 4        | 2.42%   |
| 0x08701021 | 4        | 2.42%   |
| 0x010000c8 | 4        | 2.42%   |
| 0xb0671    | 3        | 1.82%   |
| 0x906ea    | 3        | 1.82%   |
| 0x90672    | 3        | 1.82%   |
| 0x106e5    | 3        | 1.82%   |
| 0x1067a    | 3        | 1.82%   |
| 0x906e9    | 2        | 1.21%   |
| 0x406c3    | 2        | 1.21%   |
| 0x206d7    | 2        | 1.21%   |
| 0x10676    | 2        | 1.21%   |
| 0x0a201016 | 2        | 1.21%   |
| 0x08701013 | 2        | 1.21%   |
| 0x08108109 | 2        | 1.21%   |
| 0x06000852 | 2        | 1.21%   |
| 0x010000c7 | 2        | 1.21%   |
| 0xa0653    | 1        | 0.61%   |
| 0x906ed    | 1        | 0.61%   |
| 0x906eb    | 1        | 0.61%   |
| 0x706a1    | 1        | 0.61%   |
| 0x6fb      | 1        | 0.61%   |
| 0x506c9    | 1        | 0.61%   |
| 0x406c4    | 1        | 0.61%   |
| 0x306f2    | 1        | 0.61%   |
| 0x306e4    | 1        | 0.61%   |
| 0x30679    | 1        | 0.61%   |
| 0x206c2    | 1        | 0.61%   |
| 0x20652    | 1        | 0.61%   |
| 0x106ca    | 1        | 0.61%   |
| 0x10677    | 1        | 0.61%   |
| 0x0a601201 | 1        | 0.61%   |
| 0x0a50000c | 1        | 0.61%   |
| 0x0a20120a | 1        | 0.61%   |
| 0x08600106 | 1        | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 21       | 12.73%  |
| SandyBridge      | 15       | 9.09%   |
| KabyLake         | 14       | 8.48%   |
| Zen 2            | 13       | 7.88%   |
| IvyBridge        | 12       | 7.27%   |
| Zen+             | 9        | 5.45%   |
| Penryn           | 9        | 5.45%   |
| K10              | 9        | 5.45%   |
| Unknown          | 7        | 4.24%   |
| Skylake          | 6        | 3.64%   |
| Zen 3            | 5        | 3.03%   |
| Silvermont       | 5        | 3.03%   |
| Piledriver       | 5        | 3.03%   |
| CometLake        | 5        | 3.03%   |
| Zen              | 4        | 2.42%   |
| Nehalem          | 4        | 2.42%   |
| Alderlake Hybrid | 4        | 2.42%   |
| Core             | 3        | 1.82%   |
| Westmere         | 2        | 1.21%   |
| NetBurst         | 2        | 1.21%   |
| K8 Hammer        | 2        | 1.21%   |
| Jaguar           | 2        | 1.21%   |
| Steamroller      | 1        | 0.61%   |
| K10 Llano        | 1        | 0.61%   |
| Goldmont plus    | 1        | 0.61%   |
| Goldmont         | 1        | 0.61%   |
| Excavator        | 1        | 0.61%   |
| Broadwell        | 1        | 0.61%   |
| Bonnell          | 1        | 0.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 73       | 41.01%  |
| Nvidia | 60       | 33.71%  |
| AMD    | 45       | 25.28%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11       | 6.15%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11       | 6.15%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 9        | 5.03%   |
| Intel HD Graphics 530                                                                    | 6        | 3.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6        | 3.35%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5        | 2.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5        | 2.79%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4        | 2.23%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4        | 2.23%   |
| Intel HD Graphics 630                                                                    | 4        | 2.23%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3        | 1.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 1.68%   |
| Intel AlderLake-S GT1                                                                    | 3        | 1.68%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3        | 1.68%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 2        | 1.12%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 1.12%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2        | 1.12%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 2        | 1.12%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 1.12%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                               | 2        | 1.12%   |
| Intel DG2 [Arc A770]                                                                     | 2        | 1.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 1.12%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                                | 2        | 1.12%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2        | 1.12%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2        | 1.12%   |
| AMD RS880 [Radeon HD 4250]                                                               | 2        | 1.12%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 1.12%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2        | 1.12%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 2        | 1.12%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 1.12%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2        | 1.12%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2        | 1.12%   |
| Nvidia TU117GL [T600]                                                                    | 1        | 0.56%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1        | 0.56%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1        | 0.56%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 0.56%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1        | 0.56%   |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1        | 0.56%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1        | 0.56%   |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 1        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 61       | 37.2%   |
| 1 x Nvidia     | 55       | 33.54%  |
| 1 x AMD        | 39       | 23.78%  |
| Intel + Nvidia | 3        | 1.83%   |
| Intel + AMD    | 3        | 1.83%   |
| AMD + Nvidia   | 2        | 1.22%   |
| 2 x AMD        | 1        | 0.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 120      | 72.73%  |
| Proprietary | 38       | 23.03%  |
| Unknown     | 7        | 4.24%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 98       | 59.39%  |
| 1.01-2.0   | 18       | 10.91%  |
| 0.51-1.0   | 17       | 10.3%   |
| 0.01-0.5   | 10       | 6.06%   |
| 3.01-4.0   | 8        | 4.85%   |
| 7.01-8.0   | 7        | 4.24%   |
| 8.01-16.0  | 3        | 1.82%   |
| 5.01-6.0   | 2        | 1.21%   |
| 2.01-3.0   | 2        | 1.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 27       | 16.27%  |
| Samsung Electronics  | 23       | 13.86%  |
| Hewlett-Packard      | 16       | 9.64%   |
| AOC                  | 11       | 6.63%   |
| Acer                 | 11       | 6.63%   |
| Goldstar             | 10       | 6.02%   |
| ViewSonic            | 6        | 3.61%   |
| Iiyama               | 6        | 3.61%   |
| BenQ                 | 6        | 3.61%   |
| Ancor Communications | 6        | 3.61%   |
| Philips              | 5        | 3.01%   |
| Lenovo               | 3        | 1.81%   |
| Fujitsu Siemens      | 3        | 1.81%   |
| Unknown              | 2        | 1.2%    |
| RTK                  | 2        | 1.2%    |
| Eizo                 | 2        | 1.2%    |
| ASUSTek Computer     | 2        | 1.2%    |
| Unknown              | 2        | 1.2%    |
| ___                  | 1        | 0.6%    |
| Vestel Elektronik    | 1        | 0.6%    |
| UGD                  | 1        | 0.6%    |
| Toshiba              | 1        | 0.6%    |
| TEO                  | 1        | 0.6%    |
| Tech Concepts        | 1        | 0.6%    |
| TCL                  | 1        | 0.6%    |
| Sony                 | 1        | 0.6%    |
| SNC                  | 1        | 0.6%    |
| RGT                  | 1        | 0.6%    |
| Packard Bell         | 1        | 0.6%    |
| Mi                   | 1        | 0.6%    |
| MAG                  | 1        | 0.6%    |
| LG Electronics       | 1        | 0.6%    |
| JINGLITAI            | 1        | 0.6%    |
| IBM                  | 1        | 0.6%    |
| Gateway              | 1        | 0.6%    |
| Envision Peripherals | 1        | 0.6%    |
| eMachines            | 1        | 0.6%    |
| Elo Touch            | 1        | 0.6%    |
| Denver               | 1        | 0.6%    |
| Compal               | 1        | 0.6%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                | 2        | 1.14%   |
| Philips 170S PHL082B 1280x1024 338x270mm 17.0-inch                    | 2        | 1.14%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                   | 2        | 1.14%   |
| Hewlett-Packard 2309 HWP2821 1920x1080 510x287mm 23.0-inch            | 2        | 1.14%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 2        | 1.14%   |
| Unknown                                                               | 2        | 1.14%   |
| ___ LCD Monitor ___1BBC 1920x540 140x90mm 6.6-inch                    | 1        | 0.57%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch         | 1        | 0.57%   |
| ViewSonic VX3276-UHD VSC5138 3840x2160 697x392mm 31.5-inch            | 1        | 0.57%   |
| ViewSonic VP2365 SERIES VSC7C28 1920x1080 509x286mm 23.0-inch         | 1        | 0.57%   |
| ViewSonic VA1948 SERIES VSCE827 1440x900 408x255mm 18.9-inch          | 1        | 0.57%   |
| Vestel Elektronik 43UHD_LCD_TV VES3700 3840x2160 950x540mm 43.0-inch  | 1        | 0.57%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 1        | 0.57%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1        | 0.57%   |
| UGD CD220F (H) UGD2210 1920x1080 527x296mm 23.8-inch                  | 1        | 0.57%   |
| Toshiba TV TSB0109 1920x1080                                          | 1        | 0.57%   |
| TEO TL765 TEO6700 1280x1024 338x270mm 17.0-inch                       | 1        | 0.57%   |
| Tech Concepts LCD Monitor 32S327 1280x720                             | 1        | 0.57%   |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                      | 1        | 0.57%   |
| Sony TV SNYAB03 1920x1080                                             | 1        | 0.57%   |
| SNC SKP_E20-27 SNC2700 2560x1440 597x336mm 27.0-inch                  | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM0653 1920x1080                      | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM05C4 1920x1080 510x290mm 23.1-inch  | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM03E3 1680x1050 433x271mm 20.1-inch  | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch   | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 408x306mm 20.1-inch  | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM00E5 1280x1024 338x270mm 17.0-inch  | 1        | 0.57%   |
| Samsung Electronics SME1920N SAM06A3 1360x768 410x230mm 18.5-inch     | 1        | 0.57%   |
| Samsung Electronics SMB2430L SAM0645 1920x1080 521x293mm 23.5-inch    | 1        | 0.57%   |
| Samsung Electronics SM2333TN SAM06FC 1920x1080 477x268mm 21.5-inch    | 1        | 0.57%   |
| Samsung Electronics S24E650 SAM0C86 1920x1200 518x324mm 24.1-inch     | 1        | 0.57%   |
| Samsung Electronics S24E360 SAM0C0F 1920x1080 521x293mm 23.5-inch     | 1        | 0.57%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 1        | 0.57%   |
| Samsung Electronics S24B300 SAM08CC 1920x1080 521x293mm 23.5-inch     | 1        | 0.57%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1        | 0.57%   |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch      | 1        | 0.57%   |
| Samsung Electronics LCD Monitor SMB2430L 3840x1080                    | 1        | 0.57%   |
| Samsung Electronics LCD Monitor SMB2430L                              | 1        | 0.57%   |
| Samsung Electronics LCD Monitor SAM094E 1920x1080 700x390mm 31.5-inch | 1        | 0.57%   |
| Samsung Electronics LCD Monitor SAM07BB 1360x768 410x256mm 19.0-inch  | 1        | 0.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 74       | 45.12%  |
| 1280x1024 (SXGA)   | 14       | 8.54%   |
| 2560x1440 (QHD)    | 11       | 6.71%   |
| 1366x768 (WXGA)    | 10       | 6.1%    |
| 1440x900 (WXGA+)   | 8        | 4.88%   |
| 3840x2160 (4K)     | 7        | 4.27%   |
| 1680x1050 (WSXGA+) | 6        | 3.66%   |
| 1600x900 (HD+)     | 6        | 3.66%   |
| 1920x1200 (WUXGA)  | 4        | 2.44%   |
| 1024x768 (XGA)     | 4        | 2.44%   |
| 3840x1080          | 3        | 1.83%   |
| 1600x1200          | 3        | 1.83%   |
| 1360x768           | 3        | 1.83%   |
| 3840x1600          | 2        | 1.22%   |
| 3440x1440          | 2        | 1.22%   |
| 2560x1600          | 2        | 1.22%   |
| Unknown            | 2        | 1.22%   |
| 2288x1287          | 1        | 0.61%   |
| 1920x540           | 1        | 0.61%   |
| 1280x720 (HD)      | 1        | 0.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 25       | 14.62%  |
| 24      | 24       | 14.04%  |
| 27      | 19       | 11.11%  |
| 21      | 15       | 8.77%   |
| 19      | 13       | 7.6%    |
| Unknown | 12       | 7.02%   |
| 18      | 10       | 5.85%   |
| 20      | 9        | 5.26%   |
| 17      | 8        | 4.68%   |
| 15      | 6        | 3.51%   |
| 31      | 5        | 2.92%   |
| 22      | 4        | 2.34%   |
| 72      | 2        | 1.17%   |
| 40      | 2        | 1.17%   |
| 37      | 2        | 1.17%   |
| 34      | 2        | 1.17%   |
| 32      | 2        | 1.17%   |
| 26      | 2        | 1.17%   |
| 25      | 2        | 1.17%   |
| 142     | 1        | 0.58%   |
| 84      | 1        | 0.58%   |
| 54      | 1        | 0.58%   |
| 49      | 1        | 0.58%   |
| 30      | 1        | 0.58%   |
| 29      | 1        | 0.58%   |
| 6       | 1        | 0.58%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 64       | 39.02%  |
| 401-500        | 47       | 28.66%  |
| 301-350        | 14       | 8.54%   |
| Unknown        | 12       | 7.32%   |
| 601-700        | 9        | 5.49%   |
| 801-900        | 4        | 2.44%   |
| 701-800        | 4        | 2.44%   |
| 351-400        | 3        | 1.83%   |
| 1501-2000      | 3        | 1.83%   |
| 1001-1500      | 2        | 1.22%   |
| More than 2000 | 1        | 0.61%   |
| 101-200        | 1        | 0.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 98       | 63.23%  |
| 16/10   | 23       | 14.84%  |
| 5/4     | 11       | 7.1%    |
| Unknown | 10       | 6.45%   |
| 4/3     | 7        | 4.52%   |
| 21/9    | 4        | 2.58%   |
| 32/9    | 1        | 0.65%   |
| 1.00    | 1        | 0.65%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 54       | 32.34%  |
| 151-200        | 29       | 17.37%  |
| 301-350        | 20       | 11.98%  |
| 141-150        | 17       | 10.18%  |
| Unknown        | 12       | 7.19%   |
| 351-500        | 11       | 6.59%   |
| 251-300        | 8        | 4.79%   |
| 101-110        | 6        | 3.59%   |
| More than 1000 | 5        | 2.99%   |
| 501-1000       | 4        | 2.4%    |
| 1-40           | 1        | 0.6%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 106      | 67.09%  |
| 101-120       | 28       | 17.72%  |
| Unknown       | 12       | 7.59%   |
| 121-160       | 6        | 3.8%    |
| 1-50          | 5        | 3.16%   |
| More than 240 | 1        | 0.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 132      | 80%     |
| 2     | 20       | 12.12%  |
| 0     | 9        | 5.45%   |
| 3     | 4        | 2.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 109      | 47.39%  |
| Intel                           | 69       | 30%     |
| Qualcomm Atheros                | 14       | 6.09%   |
| Ralink Technology               | 5        | 2.17%   |
| Nvidia                          | 4        | 1.74%   |
| Broadcom                        | 4        | 1.74%   |
| TP-Link                         | 3        | 1.3%    |
| Ralink                          | 2        | 0.87%   |
| Marvell Technology Group        | 2        | 0.87%   |
| D-Link System                   | 2        | 0.87%   |
| Broadcom Limited                | 2        | 0.87%   |
| ZyDAS                           | 1        | 0.43%   |
| Zoom Telephonics                | 1        | 0.43%   |
| TRENDnet                        | 1        | 0.43%   |
| Qualcomm Atheros Communications | 1        | 0.43%   |
| OPPO Electronics                | 1        | 0.43%   |
| NetGear                         | 1        | 0.43%   |
| Microchip Technology            | 1        | 0.43%   |
| Mellanox Technologies           | 1        | 0.43%   |
| MediaTek                        | 1        | 0.43%   |
| Dell                            | 1        | 0.43%   |
| Belkin Components               | 1        | 0.43%   |
| ASUSTek Computer                | 1        | 0.43%   |
| ASIX Electronics                | 1        | 0.43%   |
| Aquantia                        | 1        | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 85       | 33.07%  |
| Realtek RTL8125 2.5GbE Controller                                          | 13       | 5.06%   |
| Intel I211 Gigabit Network Connection                                      | 9        | 3.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 9        | 3.5%    |
| Intel Ethernet Connection (2) I219-V                                       | 8        | 3.11%   |
| Intel Wi-Fi 6 AX200                                                        | 6        | 2.33%   |
| Intel Ethernet Connection I217-LM                                          | 5        | 1.95%   |
| Nvidia MCP61 Ethernet                                                      | 4        | 1.56%   |
| Intel Ethernet Controller I225-V                                           | 4        | 1.56%   |
| Intel Ethernet Connection I217-V                                           | 4        | 1.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 3        | 1.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 3        | 1.17%   |
| Realtek 802.11ac NIC                                                       | 3        | 1.17%   |
| Ralink MT7601U Wireless Adapter                                            | 3        | 1.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 3        | 1.17%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 3        | 1.17%   |
| Intel Ethernet Connection (7) I219-V                                       | 3        | 1.17%   |
| Intel Ethernet Connection (2) I218-V                                       | 3        | 1.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 3        | 1.17%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                   | 2        | 0.78%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 2        | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 2        | 0.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 2        | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 2        | 0.78%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 2        | 0.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 2        | 0.78%   |
| Intel Wireless 7260                                                        | 2        | 0.78%   |
| Intel Wireless 3160                                                        | 2        | 0.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 2        | 0.78%   |
| Intel Ethernet Connection (7) I219-LM                                      | 2        | 0.78%   |
| Intel Ethernet Connection (17) I219-V                                      | 2        | 0.78%   |
| Intel Ethernet Connection (14) I219-V                                      | 2        | 0.78%   |
| Intel 82579V Gigabit Network Connection                                    | 2        | 0.78%   |
| Intel 82578DM Gigabit Network Connection                                   | 2        | 0.78%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 2        | 0.78%   |
| Intel 700 Series Chipset Family Wi-Fi                                      | 2        | 0.78%   |
| ZyDAS ZD1211B 802.11g                                                      | 1        | 0.39%   |
| Zoom Telephonics V.92 56K Mini External Modem Model 3095                   | 1        | 0.39%   |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU] | 1        | 0.39%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                      | 1        | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 19       | 27.54%  |
| Realtek Semiconductor           | 17       | 24.64%  |
| Qualcomm Atheros                | 13       | 18.84%  |
| Ralink Technology               | 5        | 7.25%   |
| TP-Link                         | 3        | 4.35%   |
| Ralink                          | 2        | 2.9%    |
| ZyDAS                           | 1        | 1.45%   |
| TRENDnet                        | 1        | 1.45%   |
| Qualcomm Atheros Communications | 1        | 1.45%   |
| NetGear                         | 1        | 1.45%   |
| MediaTek                        | 1        | 1.45%   |
| Dell                            | 1        | 1.45%   |
| D-Link System                   | 1        | 1.45%   |
| Broadcom                        | 1        | 1.45%   |
| Belkin Components               | 1        | 1.45%   |
| ASUSTek Computer                | 1        | 1.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                               | 6        | 8.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 3        | 4.35%   |
| Realtek 802.11ac NIC                                                              | 3        | 4.35%   |
| Ralink MT7601U Wireless Adapter                                                   | 3        | 4.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 3        | 4.35%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                  | 3        | 4.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                  | 3        | 4.35%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                          | 2        | 2.9%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                          | 2        | 2.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 2        | 2.9%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                  | 2        | 2.9%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                    | 2        | 2.9%    |
| Intel Wireless 7260                                                               | 2        | 2.9%    |
| Intel Wireless 3160                                                               | 2        | 2.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                            | 2        | 2.9%    |
| Intel 700 Series Chipset Family Wi-Fi                                             | 2        | 2.9%    |
| ZyDAS ZD1211B 802.11g                                                             | 1        | 1.45%   |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU]        | 1        | 1.45%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                             | 1        | 1.45%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                      | 1        | 1.45%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                        | 1        | 1.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                   | 1        | 1.45%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                        | 1        | 1.45%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                            | 1        | 1.45%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                   | 1        | 1.45%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                             | 1        | 1.45%   |
| Ralink RT2770 Wireless Adapter                                                    | 1        | 1.45%   |
| Ralink RT2501/RT2573 Wireless Adapter                                             | 1        | 1.45%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                            | 1        | 1.45%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                         | 1        | 1.45%   |
| Qualcomm Atheros AR9271 802.11n                                                   | 1        | 1.45%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                  | 1        | 1.45%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg]    | 1        | 1.45%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                        | 1        | 1.45%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                               | 1        | 1.45%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                     | 1        | 1.45%   |
| Intel Wireless 7265                                                               | 1        | 1.45%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                  | 1        | 1.45%   |
| Dell Wireless 1450 Dual-band (802.11a/b/g) Adapter [Intersil ISL3887]             | 1        | 1.45%   |
| D-Link System DWA-131 802.11n Wireless N Nano Adapter(rev.A1) [Realtek RTL8192SU] | 1        | 1.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 102      | 57.3%   |
| Intel                    | 59       | 33.15%  |
| Nvidia                   | 4        | 2.25%   |
| Broadcom                 | 3        | 1.69%   |
| Qualcomm Atheros         | 2        | 1.12%   |
| Marvell Technology Group | 2        | 1.12%   |
| Broadcom Limited         | 2        | 1.12%   |
| OPPO Electronics         | 1        | 0.56%   |
| D-Link System            | 1        | 0.56%   |
| ASIX Electronics         | 1        | 0.56%   |
| Aquantia                 | 1        | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 85       | 45.95%  |
| Realtek RTL8125 2.5GbE Controller                                 | 13       | 7.03%   |
| Intel I211 Gigabit Network Connection                             | 9        | 4.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9        | 4.86%   |
| Intel Ethernet Connection (2) I219-V                              | 8        | 4.32%   |
| Intel Ethernet Connection I217-LM                                 | 5        | 2.7%    |
| Nvidia MCP61 Ethernet                                             | 4        | 2.16%   |
| Intel Ethernet Controller I225-V                                  | 4        | 2.16%   |
| Intel Ethernet Connection I217-V                                  | 4        | 2.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 1.62%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.62%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.62%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.08%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 1.08%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 1.08%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 1.08%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 1.08%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.08%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 1.08%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.08%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 0.54%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.54%   |
| OPPO SM8350-MTP _SN:1518BD09                                      | 1        | 0.54%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.54%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.54%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.54%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.54%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.54%   |
| Intel 82541GI Gigabit Ethernet Controller                         | 1        | 0.54%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 0.54%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.54%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 1        | 0.54%   |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                       | 1        | 0.54%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 0.54%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 0.54%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 0.54%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 164      | 71%     |
| WiFi     | 64       | 27.71%  |
| Modem    | 2        | 0.87%   |
| Unknown  | 1        | 0.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 135      | 78.95%  |
| WiFi     | 36       | 21.05%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 109      | 66.06%  |
| 2     | 48       | 29.09%  |
| 3     | 7        | 4.24%   |
| 4     | 1        | 0.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 105      | 63.25%  |
| Yes  | 61       | 36.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 18       | 37.5%   |
| Cambridge Silicon Radio         | 16       | 33.33%  |
| Realtek Semiconductor           | 5        | 10.42%  |
| Broadcom                        | 3        | 6.25%   |
| IMC Networks                    | 2        | 4.17%   |
| Qualcomm Atheros Communications | 1        | 2.08%   |
| MediaTek                        | 1        | 2.08%   |
| Lite-On Technology              | 1        | 2.08%   |
| Fujitsu                         | 1        | 2.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 16       | 33.33%  |
| Intel AX200 Bluetooth                               | 6        | 12.5%   |
| Intel Bluetooth wireless interface                  | 5        | 10.42%  |
| Realtek Bluetooth Radio                             | 3        | 6.25%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 6.25%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 4.17%   |
| Intel Bluetooth Device                              | 2        | 4.17%   |
| IMC Networks Bluetooth Radio                        | 2        | 4.17%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 4.17%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1        | 2.08%   |
| MediaTek Wireless_Device                            | 1        | 2.08%   |
| Lite-On Bluetooth Device                            | 1        | 2.08%   |
| Intel AX210 Bluetooth                               | 1        | 2.08%   |
| Intel AX201 Bluetooth                               | 1        | 2.08%   |
| Fujitsu Bluetooth Device                            | 1        | 2.08%   |
| Broadcom BCM2210 Bluetooth                          | 1        | 2.08%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 112      | 44.8%   |
| AMD                        | 58       | 23.2%   |
| Nvidia                     | 55       | 22%     |
| C-Media Electronics        | 4        | 1.6%    |
| Creative Labs              | 3        | 1.2%    |
| SAVITECH                   | 2        | 0.8%    |
| Logitech                   | 2        | 0.8%    |
| VIA Technologies           | 1        | 0.4%    |
| STMicroelectronics         | 1        | 0.4%    |
| Samson Technologies        | 1        | 0.4%    |
| PreSonus Audio Electronics | 1        | 0.4%    |
| Micro Star International   | 1        | 0.4%    |
| Medeli Electronics         | 1        | 0.4%    |
| MAG Technology             | 1        | 0.4%    |
| Lenovo                     | 1        | 0.4%    |
| Kingston Technology        | 1        | 0.4%    |
| Hewlett-Packard            | 1        | 0.4%    |
| Guangzhou FiiO Electronics | 1        | 0.4%    |
| GN Netcom                  | 1        | 0.4%    |
| Creative Technology        | 1        | 0.4%    |
| Corsair                    | 1        | 0.4%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 17       | 5.88%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 14       | 4.84%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 13       | 4.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13       | 4.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12       | 4.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12       | 4.15%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9        | 3.11%   |
| Intel 200 Series PCH HD Audio                                                                     | 8        | 2.77%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 7        | 2.42%   |
| AMD FCH Azalia Controller                                                                         | 7        | 2.42%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7        | 2.42%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7        | 2.42%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6        | 2.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6        | 2.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6        | 2.08%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6        | 2.08%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5        | 1.73%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 5        | 1.73%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 5        | 1.73%   |
| Nvidia MCP61 High Definition Audio                                                                | 4        | 1.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4        | 1.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4        | 1.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4        | 1.38%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3        | 1.04%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3        | 1.04%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3        | 1.04%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 3        | 1.04%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3        | 1.04%   |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 3        | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3        | 1.04%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3        | 1.04%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3        | 1.04%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3        | 1.04%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2        | 0.69%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2        | 0.69%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2        | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2        | 0.69%   |
| Nvidia GF100 High Definition Audio Controller                                                     | 2        | 0.69%   |
| Nvidia Audio device                                                                               | 2        | 0.69%   |
| Intel DG2 Audio Controller                                                                        | 2        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 25       | 18.52%  |
| Unknown             | 23       | 17.04%  |
| Samsung Electronics | 16       | 11.85%  |
| Crucial             | 13       | 9.63%   |
| SK hynix            | 11       | 8.15%   |
| G.Skill             | 11       | 8.15%   |
| Corsair             | 10       | 7.41%   |
| Ramaxel Technology  | 5        | 3.7%    |
| Nanya Technology    | 3        | 2.22%   |
| Micron Technology   | 3        | 2.22%   |
| Elpida              | 3        | 2.22%   |
| Unknown (ABCD)      | 2        | 1.48%   |
| Unknown             | 2        | 1.48%   |
| Unknown (AB)        | 1        | 0.74%   |
| Transcend           | 1        | 0.74%   |
| Timetec             | 1        | 0.74%   |
| Qumo                | 1        | 0.74%   |
| GLOWAY              | 1        | 0.74%   |
| GIGA-BYTE           | 1        | 0.74%   |
| ASint Technology    | 1        | 0.74%   |
| A-DATA Technology   | 1        | 0.74%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 3        | 2.11%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 2        | 1.41%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 2        | 1.41%   |
| Ramaxel RAM RMUA5120ME86H9F-2666 4GB DIMM DDR4 2667MT/s        | 2        | 1.41%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 2        | 1.41%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 2        | 1.41%   |
| Kingston RAM 9905713-026.A00G 4GB DIMM DDR4 2667MT/s           | 2        | 1.41%   |
| Unknown                                                        | 2        | 1.41%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                      | 1        | 0.7%    |
| Unknown RAM Module 8GB DIMM 1600MT/s                           | 1        | 0.7%    |
| Unknown RAM Module 4GB DIMM SDRAM                              | 1        | 0.7%    |
| Unknown RAM Module 4GB DIMM 1600MT/s                           | 1        | 0.7%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 1        | 0.7%    |
| Unknown RAM Module 4GB DIMM 1066MT/s                           | 1        | 0.7%    |
| Unknown RAM Module 2GB DIMM SDRAM                              | 1        | 0.7%    |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                       | 1        | 0.7%    |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                      | 1        | 0.7%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 1        | 0.7%    |
| Unknown RAM Module 2GB DIMM DDR2 400MT/s                       | 1        | 0.7%    |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                      | 1        | 0.7%    |
| Unknown RAM Module 2GB DIMM DDR2                               | 1        | 0.7%    |
| Unknown RAM Module 2GB DIMM 5354MT/s                           | 1        | 0.7%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 0.7%    |
| Unknown RAM Module 1GB DIMM DDR2                               | 1        | 0.7%    |
| Unknown RAM CL17-17-17 D4-2400 16384MB DIMM DDR4 2400MT/s      | 1        | 0.7%    |
| Unknown RAM 2400 C16 Series 8192MB DIMM DDR4 1200MT/s          | 1        | 0.7%    |
| Unknown RAM 1600 CL9 Series 8192MB DIMM DDR3 1066MT/s          | 1        | 0.7%    |
| Unknown (AB) RAM Module 2GB DIMM LPDDR3 1333MT/s               | 1        | 0.7%    |
| Transcend RAM Module 2GB DIMM DDR3 1333MT/s                    | 1        | 0.7%    |
| Timetec RAM UD3-1333 4GB DIMM DDR3 1333MT/s                    | 1        | 0.7%    |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                   | 1        | 0.7%    |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                   | 1        | 0.7%    |
| SK hynix RAM Module 16GB DIMM DDR4 2667MT/s                    | 1        | 0.7%    |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.7%    |
| SK hynix RAM HMT451U6BFR8A-PB 4096MB DIMM DDR3 1648MT/s        | 1        | 0.7%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1        | 0.7%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.7%    |
| SK hynix RAM HMT351U7EFR8C-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.7%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 1        | 0.7%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB DIMM DDR3 1333MT/s           | 1        | 0.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 49       | 42.98%  |
| DDR4    | 45       | 39.47%  |
| Unknown | 6        | 5.26%   |
| SDRAM   | 5        | 4.39%   |
| DDR2    | 4        | 3.51%   |
| LPDDR4  | 2        | 1.75%   |
| DDR5    | 2        | 1.75%   |
| LPDDR3  | 1        | 0.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 105      | 93.75%  |
| SODIMM | 7        | 6.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 41       | 33.61%  |
| 4096  | 38       | 31.15%  |
| 2048  | 19       | 15.57%  |
| 16384 | 18       | 14.75%  |
| 32768 | 3        | 2.46%   |
| 1024  | 3        | 2.46%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 31       | 24.8%   |
| 1333    | 20       | 16%     |
| 2667    | 10       | 8%      |
| 2400    | 10       | 8%      |
| 3600    | 7        | 5.6%    |
| 3200    | 7        | 5.6%    |
| 3000    | 4        | 3.2%    |
| 3466    | 3        | 2.4%    |
| 2133    | 3        | 2.4%    |
| Unknown | 3        | 2.4%    |
| 2666    | 2        | 1.6%    |
| 1867    | 2        | 1.6%    |
| 1866    | 2        | 1.6%    |
| 1067    | 2        | 1.6%    |
| 1066    | 2        | 1.6%    |
| 800     | 2        | 1.6%    |
| 6000    | 1        | 0.8%    |
| 5354    | 1        | 0.8%    |
| 4800    | 1        | 0.8%    |
| 4000    | 1        | 0.8%    |
| 3866    | 1        | 0.8%    |
| 3400    | 1        | 0.8%    |
| 3333    | 1        | 0.8%    |
| 3020    | 1        | 0.8%    |
| 2800    | 1        | 0.8%    |
| 2000    | 1        | 0.8%    |
| 1800    | 1        | 0.8%    |
| 1648    | 1        | 0.8%    |
| 1639    | 1        | 0.8%    |
| 1334    | 1        | 0.8%    |
| 400     | 1        | 0.8%    |

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
| Logitech                    | 7        | 26.92%  |
| Microdia                    | 4        | 15.38%  |
| Realtek Semiconductor       | 2        | 7.69%   |
| Microsoft                   | 2        | 7.69%   |
| KYE Systems (Mouse Systems) | 2        | 7.69%   |
| Xiaomi                      | 1        | 3.85%   |
| Silicon Motion              | 1        | 3.85%   |
| Samsung Electronics         | 1        | 3.85%   |
| Quanta                      | 1        | 3.85%   |
| IMC Networks                | 1        | 3.85%   |
| Guillemot                   | 1        | 3.85%   |
| Generalplus Technology      | 1        | 3.85%   |
| Creative Technology         | 1        | 3.85%   |
| Apple                       | 1        | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Realtek FULL HD 1080P Webcam                   | 2        | 7.69%   |
| Logitech HD Pro Webcam C920                    | 2        | 7.69%   |
| Xiaomi Mi/Redmi series (PTP)                   | 1        | 3.85%   |
| Silicon Motion 300k Pixel Camera               | 1        | 3.85%   |
| Samsung Galaxy series, misc. (MTP mode)        | 1        | 3.85%   |
| Quanta HP HD Camera                            | 1        | 3.85%   |
| Microsoft MicrosoftÂ LifeCam Studio           | 1        | 3.85%   |
| Microsoft LifeCam VX-2000                      | 1        | 3.85%   |
| Microdia Webcam Vitade AF                      | 1        | 3.85%   |
| Microdia USB 2.0 Camera                        | 1        | 3.85%   |
| Microdia Sonix USB 2.0 Camera                  | 1        | 3.85%   |
| Microdia Camera                                | 1        | 3.85%   |
| Logitech Webcam C300                           | 1        | 3.85%   |
| Logitech Webcam C110                           | 1        | 3.85%   |
| Logitech HD Webcam C525                        | 1        | 3.85%   |
| Logitech C922 Pro Stream Webcam                | 1        | 3.85%   |
| Logitech BRIO Ultra HD Webcam                  | 1        | 3.85%   |
| KYE Systems (Mouse Systems) iSlim 2020AF       | 1        | 3.85%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320 | 1        | 3.85%   |
| IMC Networks USB2.0 UVC HD Webcam              | 1        | 3.85%   |
| Guillemot Hercules Dualpix Exchange            | 1        | 3.85%   |
| Generalplus GENERAL WEBCAM                     | 1        | 3.85%   |
| Creative Live! Cam Sync 1080p                  | 1        | 3.85%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                | 1        | 3.85%   |

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
| 0     | 143      | 85.63%  |
| 1     | 19       | 11.38%  |
| 2     | 4        | 2.4%    |
| 3     | 1        | 0.6%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Graphics card         | 14       | 51.85%  |
| Sound                 | 2        | 7.41%   |
| Net/wireless          | 2        | 7.41%   |
| Multimedia controller | 2        | 7.41%   |
| Chipcard              | 2        | 7.41%   |
| Camera                | 2        | 7.41%   |
| Unassigned class      | 1        | 3.7%    |
| Net/ethernet          | 1        | 3.7%    |
| Dvb card              | 1        | 3.7%    |

