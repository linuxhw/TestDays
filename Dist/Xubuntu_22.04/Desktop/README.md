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

Total: 275

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 18E5                        | [1f3e02bd3e](https://linux-hardware.org/?probe=1f3e02bd3e) | Oct 01, 2023 |
| Medion        | B660M DS3H AX DDR4          | [1dbbeda8cd](https://linux-hardware.org/?probe=1dbbeda8cd) | Sep 30, 2023 |
| Medion        | B660M DS3H AX DDR4          | [57a42b9ccf](https://linux-hardware.org/?probe=57a42b9ccf) | Sep 30, 2023 |
| Dell          | 0YJPT1 A00                  | [27b01f468d](https://linux-hardware.org/?probe=27b01f468d) | Sep 30, 2023 |
| Lenovo        | NOK                         | [95ba956749](https://linux-hardware.org/?probe=95ba956749) | Sep 28, 2023 |
| Gigabyte      | EX58-UD5                    | [060deb4c88](https://linux-hardware.org/?probe=060deb4c88) | Sep 26, 2023 |
| ASUSTek       | M5A97 R2.0                  | [275018a17e](https://linux-hardware.org/?probe=275018a17e) | Sep 26, 2023 |
| Gigabyte      | F2A68HM-H                   | [f3b7fdc0c1](https://linux-hardware.org/?probe=f3b7fdc0c1) | Sep 26, 2023 |
| Medion        | MS-7848                     | [5ce2a07d18](https://linux-hardware.org/?probe=5ce2a07d18) | Sep 25, 2023 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | [c3043092b9](https://linux-hardware.org/?probe=c3043092b9) | Sep 22, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [d2fe3f1d44](https://linux-hardware.org/?probe=d2fe3f1d44) | Sep 19, 2023 |
| Gigabyte      | F2A68HM-H                   | [08e19ba183](https://linux-hardware.org/?probe=08e19ba183) | Sep 13, 2023 |
| ASUSTek       | P9X79 PRO                   | [1056a6ebb4](https://linux-hardware.org/?probe=1056a6ebb4) | Sep 06, 2023 |
| Dell          | 042P49 A00                  | [b9dddc1ef8](https://linux-hardware.org/?probe=b9dddc1ef8) | Sep 06, 2023 |
| Dell          | 0GY6Y8 A03                  | [da9dc1f5d9](https://linux-hardware.org/?probe=da9dc1f5d9) | Sep 05, 2023 |
| HP            | 198E                        | [7f57cfbacc](https://linux-hardware.org/?probe=7f57cfbacc) | Sep 04, 2023 |
| AMD           | A88K                        | [d58c29d4ad](https://linux-hardware.org/?probe=d58c29d4ad) | Sep 03, 2023 |
| HP            | 2B2C                        | [a24d61a0f4](https://linux-hardware.org/?probe=a24d61a0f4) | Sep 02, 2023 |
| HP            | 198E                        | [3f3cb2e64c](https://linux-hardware.org/?probe=3f3cb2e64c) | Sep 02, 2023 |
| AMD           | A88K                        | [08a455504f](https://linux-hardware.org/?probe=08a455504f) | Sep 01, 2023 |
| Gigabyte      | H97N-WIFI                   | [6edcb45992](https://linux-hardware.org/?probe=6edcb45992) | Aug 26, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [4d01543131](https://linux-hardware.org/?probe=4d01543131) | Aug 24, 2023 |
| ASUSTek       | P8Z68-V GEN3                | [aad70f30d7](https://linux-hardware.org/?probe=aad70f30d7) | Aug 21, 2023 |
| ASUSTek       | PRIME B550M-K               | [60de8d6d38](https://linux-hardware.org/?probe=60de8d6d38) | Aug 11, 2023 |
| Acer          | Aspire TC-885 V:1.1         | [63f0153cfe](https://linux-hardware.org/?probe=63f0153cfe) | Aug 10, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [150d68269d](https://linux-hardware.org/?probe=150d68269d) | Aug 08, 2023 |
| MSI           | A68HM-E33 V2                | [047ae922f7](https://linux-hardware.org/?probe=047ae922f7) | Aug 07, 2023 |
| MSI           | A68HM-E33 V2                | [341fecf811](https://linux-hardware.org/?probe=341fecf811) | Aug 06, 2023 |
| ASUSTek       | PRIME Z790-P WIFI D4        | [13f47a5399](https://linux-hardware.org/?probe=13f47a5399) | Aug 06, 2023 |
| ASUSTek       | M5A78L-M LX3                | [0ffd23b534](https://linux-hardware.org/?probe=0ffd23b534) | Aug 04, 2023 |
| ASUSTek       | P5B-Deluxe                  | [122ba504c1](https://linux-hardware.org/?probe=122ba504c1) | Aug 04, 2023 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | [a61b8168b7](https://linux-hardware.org/?probe=a61b8168b7) | Aug 02, 2023 |
| ASUSTek       | H97-PLUS                    | [485793f801](https://linux-hardware.org/?probe=485793f801) | Aug 02, 2023 |
| ASRock        | Z490M-ITX/ac                | [80558a1dcd](https://linux-hardware.org/?probe=80558a1dcd) | Aug 02, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [136cb11fa2](https://linux-hardware.org/?probe=136cb11fa2) | Jul 28, 2023 |
| Foxconn       | nT-iBT18/nT-iBT19/nT-iBT... | [23633cafce](https://linux-hardware.org/?probe=23633cafce) | Jul 27, 2023 |
| Toshiba       | STI 005492G                 | [6e73cad7e4](https://linux-hardware.org/?probe=6e73cad7e4) | Jul 27, 2023 |
| MSI           | A520M-A PRO                 | [6a1aa5fbc8](https://linux-hardware.org/?probe=6a1aa5fbc8) | Jul 26, 2023 |
| ASRock        | 960GC-GS FX                 | [187cbf1010](https://linux-hardware.org/?probe=187cbf1010) | Jul 21, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [287298e199](https://linux-hardware.org/?probe=287298e199) | Jul 21, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [0bd37865ac](https://linux-hardware.org/?probe=0bd37865ac) | Jul 15, 2023 |
| Dell          | 09M8Y8 A01                  | [8807f705d0](https://linux-hardware.org/?probe=8807f705d0) | Jul 12, 2023 |
| ASRock        | A320M-HD                    | [5477254db4](https://linux-hardware.org/?probe=5477254db4) | Jul 10, 2023 |
| ASRock        | Z170 Extreme4               | [abc4554a51](https://linux-hardware.org/?probe=abc4554a51) | Jul 04, 2023 |
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


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.15.0-56-generic    | 18       | 7.93%   |
| 5.15.0-52-generic    | 16       | 7.05%   |
| 5.15.0-58-generic    | 9        | 3.96%   |
| 5.15.0-47-generic    | 9        | 3.96%   |
| 5.15.0-46-generic    | 9        | 3.96%   |
| 5.15.0-67-generic    | 8        | 3.52%   |
| 5.15.0-60-generic    | 8        | 3.52%   |
| 5.15.0-48-generic    | 6        | 2.64%   |
| 5.15.0-27-generic    | 6        | 2.64%   |
| 5.19.0-41-generic    | 5        | 2.2%    |
| 5.19.0-35-generic    | 5        | 2.2%    |
| 5.15.0-43-generic    | 5        | 2.2%    |
| 5.15.0-41-generic    | 5        | 2.2%    |
| 5.15.0-25-generic    | 5        | 2.2%    |
| 5.19.0-50-generic    | 4        | 1.76%   |
| 5.19.0-43-generic    | 4        | 1.76%   |
| 5.15.0-78-generic    | 4        | 1.76%   |
| 5.15.0-69-generic    | 4        | 1.76%   |
| 5.15.0-57-generic    | 4        | 1.76%   |
| 5.15.0-53-generic    | 4        | 1.76%   |
| 5.15.0-50-generic    | 4        | 1.76%   |
| 6.2.0-31-generic     | 3        | 1.32%   |
| 5.19.0-46-generic    | 3        | 1.32%   |
| 5.19.0-32-generic    | 3        | 1.32%   |
| 5.15.0-75-generic    | 3        | 1.32%   |
| 5.15.0-73-generic    | 3        | 1.32%   |
| 5.15.0-40-generic    | 3        | 1.32%   |
| 6.2.7-060207-generic | 2        | 0.88%   |
| 6.2.0-33-generic     | 2        | 0.88%   |
| 6.2.0-32-generic     | 2        | 0.88%   |
| 6.2.0-26-generic     | 2        | 0.88%   |
| 5.19.0-45-generic    | 2        | 0.88%   |
| 5.15.0-84-generic    | 2        | 0.88%   |
| 5.15.0-83-generic    | 2        | 0.88%   |
| 5.15.0-79-generic    | 2        | 0.88%   |
| 5.15.0-76-generic    | 2        | 0.88%   |
| 5.15.0-72-generic    | 2        | 0.88%   |
| 5.15.0-71-lowlatency | 2        | 0.88%   |
| 5.15.0-71-generic    | 2        | 0.88%   |
| 5.15.0-70-generic    | 2        | 0.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 151      | 72.95%  |
| 5.19.0  | 27       | 13.04%  |
| 6.2.0   | 11       | 5.31%   |
| 6.2.7   | 2        | 0.97%   |
| 5.17.0  | 2        | 0.97%   |
| 5.13.0  | 2        | 0.97%   |
| 6.4.8   | 1        | 0.48%   |
| 6.3.3   | 1        | 0.48%   |
| 6.3.12  | 1        | 0.48%   |
| 6.2.2   | 1        | 0.48%   |
| 6.2.10  | 1        | 0.48%   |
| 6.1.10  | 1        | 0.48%   |
| 6.1.0   | 1        | 0.48%   |
| 6.0.0   | 1        | 0.48%   |
| 5.4.0   | 1        | 0.48%   |
| 5.19.13 | 1        | 0.48%   |
| 5.19.1  | 1        | 0.48%   |
| 5.18.0  | 1        | 0.48%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 151      | 72.95%  |
| 5.19    | 29       | 14.01%  |
| 6.2     | 15       | 7.25%   |
| 6.3     | 2        | 0.97%   |
| 6.1     | 2        | 0.97%   |
| 5.17    | 2        | 0.97%   |
| 5.13    | 2        | 0.97%   |
| 6.4     | 1        | 0.48%   |
| 6.0     | 1        | 0.48%   |
| 5.4     | 1        | 0.48%   |
| 5.18    | 1        | 0.48%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 203      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| XFCE  | 197      | 97.04%  |
| GNOME | 4        | 1.97%   |
| KDE5  | 1        | 0.49%   |
| i3    | 1        | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 197      | 95.63%  |
| Tty  | 9        | 4.37%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 166      | 81.77%  |
| Unknown | 22       | 10.84%  |
| GDM3    | 12       | 5.91%   |
| SDDM    | 2        | 0.99%   |
| GDM     | 1        | 0.49%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 68       | 33.5%   |
| fr_FR   | 27       | 13.3%   |
| de_DE   | 27       | 13.3%   |
| it_IT   | 16       | 7.88%   |
| pt_BR   | 12       | 5.91%   |
| en_CA   | 9        | 4.43%   |
| en_GB   | 7        | 3.45%   |
| ru_RU   | 5        | 2.46%   |
| pl_PL   | 3        | 1.48%   |
| es_AR   | 3        | 1.48%   |
| en_AU   | 3        | 1.48%   |
| nl_NL   | 2        | 0.99%   |
| hu_HU   | 2        | 0.99%   |
| en_IN   | 2        | 0.99%   |
| cs_CZ   | 2        | 0.99%   |
| C       | 2        | 0.99%   |
| tr_TR   | 1        | 0.49%   |
| sv_SE   | 1        | 0.49%   |
| ru_UA   | 1        | 0.49%   |
| fr_CH   | 1        | 0.49%   |
| fr_CA   | 1        | 0.49%   |
| fr_BE   | 1        | 0.49%   |
| fi_FI   | 1        | 0.49%   |
| es_VE   | 1        | 0.49%   |
| es_ES   | 1        | 0.49%   |
| es_CO   | 1        | 0.49%   |
| en_ZA   | 1        | 0.49%   |
| en_NZ   | 1        | 0.49%   |
| Unknown | 1        | 0.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 122      | 59.8%   |
| EFI  | 82       | 40.2%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 173      | 83.98%  |
| Tmpfs   | 20       | 9.71%   |
| Overlay | 5        | 2.43%   |
| Btrfs   | 5        | 2.43%   |
| Zfs     | 2        | 0.97%   |
| Ext3    | 1        | 0.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 132      | 63.46%  |
| MBR     | 40       | 19.23%  |
| Unknown | 36       | 17.31%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 157      | 76.96%  |
| Yes       | 47       | 23.04%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 132      | 64.39%  |
| Yes       | 73       | 35.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 50       | 24.63%  |
| MSI                 | 30       | 14.78%  |
| Gigabyte Technology | 30       | 14.78%  |
| Hewlett-Packard     | 21       | 10.34%  |
| ASRock              | 16       | 7.88%   |
| Dell                | 15       | 7.39%   |
| Lenovo              | 10       | 4.93%   |
| Acer                | 5        | 2.46%   |
| Intel               | 4        | 1.97%   |
| Fujitsu             | 3        | 1.48%   |
| Foxconn             | 3        | 1.48%   |
| PCWare              | 2        | 0.99%   |
| Medion              | 2        | 0.99%   |
| Unknown             | 2        | 0.99%   |
| Semp Toshiba        | 1        | 0.49%   |
| Pegatron            | 1        | 0.49%   |
| Packard Bell        | 1        | 0.49%   |
| OEM                 | 1        | 0.49%   |
| MACHINIST           | 1        | 0.49%   |
| Itautec             | 1        | 0.49%   |
| Hardkernel          | 1        | 0.49%   |
| eMachines           | 1        | 0.49%   |
| Biostar             | 1        | 0.49%   |
| AMD                 | 1        | 0.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 5        | 2.46%   |
| Dell OptiPlex 7010                | 4        | 1.97%   |
| MSI MS-7D43                       | 3        | 1.48%   |
| MSI MS-7721                       | 3        | 1.48%   |
| Unknown                           | 3        | 1.48%   |
| MSI MS-7D46                       | 2        | 0.99%   |
| MSI MS-7D25                       | 2        | 0.99%   |
| MSI MS-7C52                       | 2        | 0.99%   |
| MSI MS-7817                       | 2        | 0.99%   |
| Lenovo V530S-07ICB 10TX0010PB     | 2        | 0.99%   |
| Dell OptiPlex 9020                | 2        | 0.99%   |
| ASUS K30AD_M31AD_M51AD            | 2        | 0.99%   |
| Semp Toshiba STI                  | 1        | 0.49%   |
| Pegatron FZ132AA-ABF m9456fr      | 1        | 0.49%   |
| PCWare IPX1800E2                  | 1        | 0.49%   |
| PCWare IPMH81G1                   | 1        | 0.49%   |
| Packard Bell IMEDIA X9305         | 1        | 0.49%   |
| MSI MS-7E07                       | 1        | 0.49%   |
| MSI MS-7D40                       | 1        | 0.49%   |
| MSI MS-7C91                       | 1        | 0.49%   |
| MSI MS-7C84                       | 1        | 0.49%   |
| MSI MS-7C56                       | 1        | 0.49%   |
| MSI MS-7C08                       | 1        | 0.49%   |
| MSI MS-7C02                       | 1        | 0.49%   |
| MSI MS-7B98                       | 1        | 0.49%   |
| MSI MS-7A32                       | 1        | 0.49%   |
| MSI MS-7982                       | 1        | 0.49%   |
| MSI MS-7835                       | 1        | 0.49%   |
| MSI MS-7758                       | 1        | 0.49%   |
| MSI MS-7529                       | 1        | 0.49%   |
| MSI MS-7309                       | 1        | 0.49%   |
| MSI Hyrican PC A320M PRO-E        | 1        | 0.49%   |
| MSI 5860                          | 1        | 0.49%   |
| Medion MS-7848                    | 1        | 0.49%   |
| Medion MD34805                    | 1        | 0.49%   |
| MACHINIST X99-RS9 V2.0            | 1        | 0.49%   |
| Lenovo ThinkCentre M90p 3282A9G   | 1        | 0.49%   |
| Lenovo ThinkCentre M83 10AM0010US | 1        | 0.49%   |
| Lenovo ThinkCentre M83 10AGS17E00 | 1        | 0.49%   |
| Lenovo ThinkCentre M72e 32675L2   | 1        | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 14       | 6.9%    |
| Dell OptiPlex        | 12       | 5.91%   |
| Lenovo ThinkCentre   | 7        | 3.45%   |
| HP Compaq            | 5        | 2.46%   |
| ASUS All             | 5        | 2.46%   |
| HP EliteDesk         | 4        | 1.97%   |
| ASUS TUF             | 4        | 1.97%   |
| Acer Veriton         | 4        | 1.97%   |
| MSI MS-7D43          | 3        | 1.48%   |
| MSI MS-7721          | 3        | 1.48%   |
| ASUS ROG             | 3        | 1.48%   |
| Unknown              | 3        | 1.48%   |
| MSI MS-7D46          | 2        | 0.99%   |
| MSI MS-7D25          | 2        | 0.99%   |
| MSI MS-7C52          | 2        | 0.99%   |
| MSI MS-7817          | 2        | 0.99%   |
| Lenovo V530S-07ICB   | 2        | 0.99%   |
| HP ProDesk           | 2        | 0.99%   |
| HP Pavilion          | 2        | 0.99%   |
| Gigabyte B550        | 2        | 0.99%   |
| Fujitsu ESPRIMO      | 2        | 0.99%   |
| Dell XPS             | 2        | 0.99%   |
| ASUS P8H61-M         | 2        | 0.99%   |
| ASUS M5A97           | 2        | 0.99%   |
| ASUS K30AD           | 2        | 0.99%   |
| Semp Toshiba STI     | 1        | 0.49%   |
| Pegatron FZ132AA-ABF | 1        | 0.49%   |
| PCWare IPX1800E2     | 1        | 0.49%   |
| PCWare IPMH81G1      | 1        | 0.49%   |
| Packard Bell IMEDIA  | 1        | 0.49%   |
| MSI MS-7E07          | 1        | 0.49%   |
| MSI MS-7D40          | 1        | 0.49%   |
| MSI MS-7C91          | 1        | 0.49%   |
| MSI MS-7C84          | 1        | 0.49%   |
| MSI MS-7C56          | 1        | 0.49%   |
| MSI MS-7C08          | 1        | 0.49%   |
| MSI MS-7C02          | 1        | 0.49%   |
| MSI MS-7B98          | 1        | 0.49%   |
| MSI MS-7A32          | 1        | 0.49%   |
| MSI MS-7982          | 1        | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2014 | 25       | 12.32%  |
| 2013 | 22       | 10.84%  |
| 2018 | 21       | 10.34%  |
| 2012 | 17       | 8.37%   |
| 2021 | 14       | 6.9%    |
| 2010 | 14       | 6.9%    |
| 2020 | 13       | 6.4%    |
| 2015 | 11       | 5.42%   |
| 2016 | 10       | 4.93%   |
| 2011 | 10       | 4.93%   |
| 2022 | 9        | 4.43%   |
| 2019 | 9        | 4.43%   |
| 2017 | 9        | 4.43%   |
| 2009 | 6        | 2.96%   |
| 2007 | 5        | 2.46%   |
| 2008 | 4        | 1.97%   |
| 2006 | 2        | 0.99%   |
| 2005 | 2        | 0.99%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 203      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 192      | 94.58%  |
| Enabled  | 11       | 5.42%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 203      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 45       | 21.95%  |
| 4.01-8.0    | 39       | 19.02%  |
| 3.01-4.0    | 38       | 18.54%  |
| 8.01-16.0   | 35       | 17.07%  |
| 32.01-64.0  | 28       | 13.66%  |
| 24.01-32.0  | 8        | 3.9%    |
| 64.01-256.0 | 5        | 2.44%   |
| 1.01-2.0    | 4        | 1.95%   |
| 2.01-3.0    | 3        | 1.46%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 82       | 37.44%  |
| 2.01-3.0   | 48       | 21.92%  |
| 3.01-4.0   | 34       | 15.53%  |
| 4.01-8.0   | 29       | 13.24%  |
| 0.51-1.0   | 14       | 6.39%   |
| 8.01-16.0  | 8        | 3.65%   |
| 16.01-24.0 | 3        | 1.37%   |
| 0.01-0.5   | 1        | 0.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 80       | 38.28%  |
| 2      | 60       | 28.71%  |
| 3      | 35       | 16.75%  |
| 4      | 16       | 7.66%   |
| 5      | 9        | 4.31%   |
| 6      | 5        | 2.39%   |
| 7      | 2        | 0.96%   |
| 10     | 1        | 0.48%   |
| 9      | 1        | 0.48%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 105      | 51.47%  |
| Yes       | 99       | 48.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 201      | 99.01%  |
| No        | 2        | 0.99%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 121      | 59.02%  |
| Yes       | 84       | 40.98%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 147      | 71.71%  |
| Yes       | 58       | 28.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Germany      | 32       | 15.69%  |
| USA          | 30       | 14.71%  |
| France       | 25       | 12.25%  |
| Italy        | 16       | 7.84%   |
| Brazil       | 14       | 6.86%   |
| Canada       | 11       | 5.39%   |
| Sweden       | 6        | 2.94%   |
| Russia       | 5        | 2.45%   |
| Poland       | 5        | 2.45%   |
| Netherlands  | 5        | 2.45%   |
| UK           | 4        | 1.96%   |
| Argentina    | 4        | 1.96%   |
| Switzerland  | 3        | 1.47%   |
| Belgium      | 3        | 1.47%   |
| Australia    | 3        | 1.47%   |
| Spain        | 2        | 0.98%   |
| Norway       | 2        | 0.98%   |
| Mexico       | 2        | 0.98%   |
| India        | 2        | 0.98%   |
| Hungary      | 2        | 0.98%   |
| Greece       | 2        | 0.98%   |
| Czechia      | 2        | 0.98%   |
| Colombia     | 2        | 0.98%   |
| Belarus      | 2        | 0.98%   |
| Turkey       | 1        | 0.49%   |
| Taiwan       | 1        | 0.49%   |
| South Africa | 1        | 0.49%   |
| Slovenia     | 1        | 0.49%   |
| Serbia       | 1        | 0.49%   |
| Romania      | 1        | 0.49%   |
| Portugal     | 1        | 0.49%   |
| Pakistan     | 1        | 0.49%   |
| New Zealand  | 1        | 0.49%   |
| Ireland      | 1        | 0.49%   |
| Iran         | 1        | 0.49%   |
| Indonesia    | 1        | 0.49%   |
| Guernsey     | 1        | 0.49%   |
| Guadeloupe   | 1        | 0.49%   |
| Finland      | 1        | 0.49%   |
| Denmark      | 1        | 0.49%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Paris                | 5        | 2.37%   |
| Berlin               | 5        | 2.37%   |
| Rio de Janeiro       | 3        | 1.42%   |
| Milan                | 3        | 1.42%   |
| Toul                 | 2        | 0.95%   |
| Toronto              | 2        | 0.95%   |
| Sydney               | 2        | 0.95%   |
| Stuttgart            | 2        | 0.95%   |
| Schwerte             | 2        | 0.95%   |
| Santiago de Cali     | 2        | 0.95%   |
| Rho                  | 2        | 0.95%   |
| Peterborough         | 2        | 0.95%   |
| Munich               | 2        | 0.95%   |
| Hanover              | 2        | 0.95%   |
| Gdansk               | 2        | 0.95%   |
| Clermont-Ferrand     | 2        | 0.95%   |
| Budapest             | 2        | 0.95%   |
| Biella               | 2        | 0.95%   |
| Amsterdam            | 2        | 0.95%   |
| Żywiec              | 1        | 0.47%   |
| Yvoir                | 1        | 0.47%   |
| Wojnicz              | 1        | 0.47%   |
| Wilhelmshaven        | 1        | 0.47%   |
| Wiener Neustadt      | 1        | 0.47%   |
| White House          | 1        | 0.47%   |
| Wettringen           | 1        | 0.47%   |
| Washington           | 1        | 0.47%   |
| Waghausel            | 1        | 0.47%   |
| Waarder              | 1        | 0.47%   |
| Vohenstrauss         | 1        | 0.47%   |
| Vohburg an der Donau | 1        | 0.47%   |
| Vicenza              | 1        | 0.47%   |
| Västerås           | 1        | 0.47%   |
| Valparaiso de Goias  | 1        | 0.47%   |
| Uppsala              | 1        | 0.47%   |
| Trois-Rivières      | 1        | 0.47%   |
| Tourouvre            | 1        | 0.47%   |
| Tijuana              | 1        | 0.47%   |
| The Hague            | 1        | 0.47%   |
| Terrace              | 1        | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 68       | 112    | 17.75%  |
| Samsung Electronics   | 57       | 76     | 14.88%  |
| Seagate               | 56       | 77     | 14.62%  |
| Kingston              | 27       | 34     | 7.05%   |
| Toshiba               | 24       | 26     | 6.27%   |
| Hitachi               | 20       | 30     | 5.22%   |
| SanDisk               | 16       | 22     | 4.18%   |
| Crucial               | 16       | 22     | 4.18%   |
| Intel                 | 8        | 10     | 2.09%   |
| China                 | 8        | 8      | 2.09%   |
| Unknown               | 7        | 9      | 1.83%   |
| HGST                  | 7        | 11     | 1.83%   |
| A-DATA Technology     | 6        | 6      | 1.57%   |
| PNY                   | 5        | 5      | 1.31%   |
| Gigabyte Technology   | 4        | 5      | 1.04%   |
| ASMT                  | 4        | 7      | 1.04%   |
| Patriot               | 3        | 3      | 0.78%   |
| Intenso               | 3        | 3      | 0.78%   |
| TEXTORM               | 2        | 2      | 0.52%   |
| SPCC                  | 2        | 2      | 0.52%   |
| SK hynix              | 2        | 2      | 0.52%   |
| Phison Electronics    | 2        | 4      | 0.52%   |
| PHD 3.0               | 2        | 2      | 0.52%   |
| OCZ                   | 2        | 2      | 0.52%   |
| Micron Technology     | 2        | 2      | 0.52%   |
| Maxtor                | 2        | 2      | 0.52%   |
| Lexar                 | 2        | 2      | 0.52%   |
| Hewlett-Packard       | 2        | 2      | 0.52%   |
| Corsair               | 2        | 2      | 0.52%   |
| XPG                   | 1        | 1      | 0.26%   |
| Veno                  | 1        | 1      | 0.26%   |
| Vaseky                | 1        | 1      | 0.26%   |
| USB3.0                | 1        | 2      | 0.26%   |
| TO Exter              | 1        | 2      | 0.26%   |
| Silicon Motion        | 1        | 1      | 0.26%   |
| Realtek Semiconductor | 1        | 1      | 0.26%   |
| Phison                | 1        | 8      | 0.26%   |
| Mushkin               | 1        | 1      | 0.26%   |
| Linux                 | 1        | 1      | 0.26%   |
| LaCie                 | 1        | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 860 EVO 500GB        | 7        | 1.57%   |
| Kingston SA400S37240G 240GB SSD  | 6        | 1.35%   |
| Crucial CT480BX500SSD1 480GB     | 6        | 1.35%   |
| Toshiba DT01ACA100 1TB           | 5        | 1.12%   |
| Kingston SA400S37480G 480GB SSD  | 5        | 1.12%   |
| Toshiba HDWD110 1TB              | 4        | 0.9%    |
| Toshiba DT01ACA200 2TB           | 4        | 0.9%    |
| Seagate ST500DM002-1BD142 500GB  | 4        | 0.9%    |
| Seagate ST2000DM008-2FR102 2TB   | 4        | 0.9%    |
| Seagate ST1000DM003-1ER162 1TB   | 4        | 0.9%    |
| Kingston SV300S37A120G 120GB SSD | 4        | 0.9%    |
| WDC WDS500G2B0A-00SM50 500GB SSD | 3        | 0.67%   |
| Unknown SD/MMC/MS PRO 128GB      | 3        | 0.67%   |
| Seagate ST4000DM004-2CV104 4TB   | 3        | 0.67%   |
| Seagate ST1000DM003-1SB102 1TB   | 3        | 0.67%   |
| Samsung SSD 870 QVO 1TB          | 3        | 0.67%   |
| Samsung SSD 850 EVO 500GB        | 3        | 0.67%   |
| Samsung SSD 850 EVO 250GB        | 3        | 0.67%   |
| Samsung SSD 840 Series 120GB     | 3        | 0.67%   |
| Kingston SUV400S37120G 120GB SSD | 3        | 0.67%   |
| Hitachi HDS721010CLA332 1TB      | 3        | 0.67%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 2        | 0.45%   |
| WDC WD3200AAKS-00L9A0 320GB      | 2        | 0.45%   |
| WDC WD20EARX-00PASB0 2TB         | 2        | 0.45%   |
| WDC WD20EARS-00MVWB0 2TB         | 2        | 0.45%   |
| WDC WD10EZRZ-00HTKB0 1TB         | 2        | 0.45%   |
| WDC WD10EZEX-08M2NA0 1TB         | 2        | 0.45%   |
| WDC WD10EZEX-00BBHA0 1TB         | 2        | 0.45%   |
| Toshiba DT01ACA050 500GB         | 2        | 0.45%   |
| TEXTORM BM5 240GB SSD            | 2        | 0.45%   |
| Seagate ST9500420AS 500GB        | 2        | 0.45%   |
| Seagate ST500LM000-1EJ162 500GB  | 2        | 0.45%   |
| Seagate ST4000VX007-2DT166 4TB   | 2        | 0.45%   |
| Seagate ST31000528AS 1TB         | 2        | 0.45%   |
| Seagate ST3000DM008-2DM166 3TB   | 2        | 0.45%   |
| Seagate ST2000DM001-1ER164 2TB   | 2        | 0.45%   |
| Seagate ST2000DM001-1CH164 2TB   | 2        | 0.45%   |
| Seagate ST2000DL003-9VT166 2TB   | 2        | 0.45%   |
| Seagate ST1000DM003-1CH162 1TB   | 2        | 0.45%   |
| SanDisk SDSSDA240G 240GB         | 2        | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 62       | 104    | 32.98%  |
| Seagate             | 56       | 75     | 29.79%  |
| Toshiba             | 21       | 23     | 11.17%  |
| Hitachi             | 20       | 30     | 10.64%  |
| Samsung Electronics | 10       | 14     | 5.32%   |
| HGST                | 7        | 11     | 3.72%   |
| ASMT                | 4        | 7      | 2.13%   |
| Unknown             | 3        | 3      | 1.6%    |
| USB3.0              | 1        | 2      | 0.53%   |
| Maxtor              | 1        | 1      | 0.53%   |
| LaCie               | 1        | 1      | 0.53%   |
| ICY BOX             | 1        | 1      | 0.53%   |
| Hewlett-Packard     | 1        | 1      | 0.53%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 36       | 45     | 25.17%  |
| Kingston            | 21       | 26     | 14.69%  |
| Crucial             | 15       | 21     | 10.49%  |
| SanDisk             | 12       | 16     | 8.39%   |
| China               | 8        | 8      | 5.59%   |
| WDC                 | 7        | 7      | 4.9%    |
| A-DATA Technology   | 6        | 6      | 4.2%    |
| PNY                 | 4        | 4      | 2.8%    |
| Toshiba             | 3        | 3      | 2.1%    |
| Patriot             | 3        | 3      | 2.1%    |
| Intenso             | 3        | 3      | 2.1%    |
| Intel               | 3        | 3      | 2.1%    |
| TEXTORM             | 2        | 2      | 1.4%    |
| SPCC                | 2        | 2      | 1.4%    |
| PHD 3.0             | 2        | 2      | 1.4%    |
| OCZ                 | 2        | 2      | 1.4%    |
| Gigabyte Technology | 2        | 2      | 1.4%    |
| Veno                | 1        | 1      | 0.7%    |
| Vaseky              | 1        | 1      | 0.7%    |
| TO Exter            | 1        | 2      | 0.7%    |
| Micron Technology   | 1        | 1      | 0.7%    |
| Maxtor              | 1        | 1      | 0.7%    |
| Linux               | 1        | 1      | 0.7%    |
| Lexar               | 1        | 1      | 0.7%    |
| KingFast            | 1        | 1      | 0.7%    |
| KingDian            | 1        | 1      | 0.7%    |
| Hewlett-Packard     | 1        | 1      | 0.7%    |
| Dogfish             | 1        | 1      | 0.7%    |
| Corsair             | 1        | 1      | 0.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 140      | 273    | 44.44%  |
| SSD     | 122      | 168    | 38.73%  |
| NVMe    | 44       | 71     | 13.97%  |
| Unknown | 6        | 7      | 1.9%    |
| MMC     | 3        | 4      | 0.95%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 189      | 415    | 73.83%  |
| NVMe | 44       | 71     | 17.19%  |
| SAS  | 20       | 33     | 7.81%   |
| MMC  | 3        | 4      | 1.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 155      | 254    | 53.08%  |
| 0.51-1.0   | 74       | 101    | 25.34%  |
| 1.01-2.0   | 35       | 45     | 11.99%  |
| 3.01-4.0   | 19       | 30     | 6.51%   |
| 2.01-3.0   | 5        | 5      | 1.71%   |
| 10.01-20.0 | 2        | 3      | 0.68%   |
| 4.01-10.0  | 2        | 3      | 0.68%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 52       | 25%     |
| 251-500        | 43       | 20.67%  |
| 1001-2000      | 31       | 14.9%   |
| 501-1000       | 28       | 13.46%  |
| More than 3000 | 22       | 10.58%  |
| 2001-3000      | 16       | 7.69%   |
| 1-20           | 6        | 2.88%   |
| 21-50          | 5        | 2.4%    |
| 51-100         | 5        | 2.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 46       | 21.6%   |
| 251-500        | 32       | 15.02%  |
| 21-50          | 32       | 15.02%  |
| 101-250        | 29       | 13.62%  |
| 51-100         | 23       | 10.8%   |
| 1001-2000      | 16       | 7.51%   |
| 501-1000       | 15       | 7.04%   |
| 2001-3000      | 11       | 5.16%   |
| More than 3000 | 9        | 4.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Toshiba DT01ACA100 1TB            | 2        | 2      | 4.55%   |
| Seagate ST1000DM003-1ER162 1TB    | 2        | 2      | 4.55%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD  | 1        | 1      | 2.27%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 1        | 1      | 2.27%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 1      | 2.27%   |
| WDC WD3200AAKS-00L9A0 320GB       | 1        | 1      | 2.27%   |
| WDC WD2500AAKS-00VSA0 250GB       | 1        | 1      | 2.27%   |
| WDC WD20EFRX-68AX9N0 2TB          | 1        | 1      | 2.27%   |
| WDC WD20EARS-00MVWB0 2TB          | 1        | 1      | 2.27%   |
| WDC WD2002FYPS-02W3B0 2TB         | 1        | 1      | 2.27%   |
| WDC WD10EZEX-60ZF5A0 1TB          | 1        | 1      | 2.27%   |
| WDC WD10EAVS-00D7B1 1TB           | 1        | 1      | 2.27%   |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1      | 2.27%   |
| WDC WD10EARS-003BB1 1TB           | 1        | 1      | 2.27%   |
| WDC WD1003FBYX-01Y7B1 1TB         | 1        | 1      | 2.27%   |
| Seagate ST9250410AS 250GB         | 1        | 1      | 2.27%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 2.27%   |
| Seagate ST4000DX001-1CE168 4TB    | 1        | 1      | 2.27%   |
| Seagate ST3750840AS 752GB         | 1        | 1      | 2.27%   |
| Seagate ST3500414CS 500GB         | 1        | 1      | 2.27%   |
| Seagate ST3250318AS 250GB         | 1        | 2      | 2.27%   |
| Seagate ST3250310AS 250GB         | 1        | 1      | 2.27%   |
| Seagate ST2000DM001-1CH164 2TB    | 1        | 1      | 2.27%   |
| Seagate ST1000DM010-2EP102 1TB    | 1        | 1      | 2.27%   |
| Samsung Electronics SP2514N 250GB | 1        | 1      | 2.27%   |
| Samsung Electronics HM321HI 320GB | 1        | 2      | 2.27%   |
| Samsung Electronics HD753LJ 752GB | 1        | 1      | 2.27%   |
| Samsung Electronics HD250HJ 250GB | 1        | 1      | 2.27%   |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 2.27%   |
| PNY 69D03094-T 40GB SSD           | 1        | 1      | 2.27%   |
| Maxtor STM3160215AS 160GB         | 1        | 1      | 2.27%   |
| Intel SSDSC2BW120A4 120GB         | 1        | 1      | 2.27%   |
| ICY BOX IB-250StU3+BH15 2TB       | 1        | 1      | 2.27%   |
| Hitachi HTS723216L9A360 160GB     | 1        | 1      | 2.27%   |
| Hitachi HDS722540VLAT20 40GB      | 1        | 1      | 2.27%   |
| Hitachi HDS721010CLA332 1TB       | 1        | 1      | 2.27%   |
| Hitachi HCP725032GLA380 320GB     | 1        | 2      | 2.27%   |
| HGST HUS724040ALA640 4TB          | 1        | 3      | 2.27%   |
| Hewlett-Packard VB0250EAVER 250GB | 1        | 1      | 2.27%   |
| Crucial CT128MX100SSD1 128GB      | 1        | 1      | 2.27%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 13     | 28.57%  |
| Seagate             | 11       | 12     | 26.19%  |
| Samsung Electronics | 4        | 6      | 9.52%   |
| Hitachi             | 4        | 5      | 9.52%   |
| Toshiba             | 2        | 2      | 4.76%   |
| PNY                 | 1        | 1      | 2.38%   |
| Maxtor              | 1        | 1      | 2.38%   |
| Intel               | 1        | 1      | 2.38%   |
| ICY BOX             | 1        | 1      | 2.38%   |
| HGST                | 1        | 3      | 2.38%   |
| Hewlett-Packard     | 1        | 1      | 2.38%   |
| Crucial             | 1        | 1      | 2.38%   |
| China               | 1        | 1      | 2.38%   |
| ASMT                | 1        | 4      | 2.38%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 11       | 12     | 29.73%  |
| Seagate             | 11       | 12     | 29.73%  |
| Samsung Electronics | 4        | 6      | 10.81%  |
| Hitachi             | 4        | 5      | 10.81%  |
| Toshiba             | 2        | 2      | 5.41%   |
| Maxtor              | 1        | 1      | 2.7%    |
| ICY BOX             | 1        | 1      | 2.7%    |
| HGST                | 1        | 3      | 2.7%    |
| Hewlett-Packard     | 1        | 1      | 2.7%    |
| ASMT                | 1        | 4      | 2.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 32       | 47     | 88.89%  |
| SSD  | 4        | 5      | 11.11%  |

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
| Works    | 116      | 245    | 48.74%  |
| Detected | 87       | 226    | 36.55%  |
| Malfunc  | 35       | 52     | 14.71%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 136      | 49.28%  |
| AMD                          | 60       | 21.74%  |
| Samsung Electronics          | 14       | 5.07%   |
| ASMedia Technology           | 9        | 3.26%   |
| Kingston Technology Company  | 8        | 2.9%    |
| JMicron Technology           | 8        | 2.9%    |
| Phison Electronics           | 7        | 2.54%   |
| SanDisk                      | 5        | 1.81%   |
| Marvell Technology Group     | 5        | 1.81%   |
| Nvidia                       | 4        | 1.45%   |
| VIA Technologies             | 3        | 1.09%   |
| Silicon Image                | 3        | 1.09%   |
| SK hynix                     | 2        | 0.72%   |
| Silicon Motion               | 2        | 0.72%   |
| Realtek Semiconductor        | 2        | 0.72%   |
| Shenzhen Longsys Electronics | 1        | 0.36%   |
| Micron/Crucial Technology    | 1        | 0.36%   |
| Micron Technology            | 1        | 0.36%   |
| LSI Logic / Symbios Logic    | 1        | 0.36%   |
| KIOXIA                       | 1        | 0.36%   |
| INNOGRIT                     | 1        | 0.36%   |
| ADATA Technology             | 1        | 0.36%   |
| Adaptec                      | 1        | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 35       | 10.03%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 19       | 5.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12       | 3.44%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 10       | 2.87%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 10       | 2.87%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10       | 2.87%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 9        | 2.58%   |
| AMD 500 Series Chipset SATA Controller                                                  | 9        | 2.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8        | 2.29%   |
| Intel SATA Controller [RAID mode]                                                       | 8        | 2.29%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8        | 2.29%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 8        | 2.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 8        | 2.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 2.01%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7        | 2.01%   |
| AMD FCH SATA Controller D                                                               | 7        | 2.01%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 6        | 1.72%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 1.72%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 1.43%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 1.43%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5        | 1.43%   |
| Nvidia MCP61 SATA Controller                                                            | 4        | 1.15%   |
| Kingston Company A2000 NVMe SSD                                                         | 4        | 1.15%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 1.15%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 1.15%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 1.15%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 1.15%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                        | 3        | 0.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 0.86%   |
| Nvidia MCP61 IDE                                                                        | 3        | 0.86%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 3        | 0.86%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3        | 0.86%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3        | 0.86%   |
| Intel 700 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.86%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.86%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 2        | 0.57%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 2        | 0.57%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 2        | 0.57%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 170      | 61.82%  |
| NVMe | 44       | 16%     |
| IDE  | 41       | 14.91%  |
| RAID | 18       | 6.55%   |
| SAS  | 1        | 0.36%   |
| SCSI | 1        | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 138      | 67.98%  |
| AMD    | 65       | 32.02%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 5        | 2.45%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 1.96%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 3        | 1.47%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 1.47%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 3        | 1.47%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 1.47%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 3        | 1.47%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 3        | 1.47%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3        | 1.47%   |
| AMD Phenom II X4 955 Processor              | 3        | 1.47%   |
| AMD FX-6300 Six-Core Processor              | 3        | 1.47%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2        | 0.98%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 0.98%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 2        | 0.98%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 0.98%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 0.98%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2        | 0.98%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 0.98%   |
| Intel Core i5-4590S CPU @ 3.00GHz           | 2        | 0.98%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 2        | 0.98%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 0.98%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 0.98%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 2        | 0.98%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 0.98%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 0.98%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 0.98%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 2        | 0.98%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 0.98%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 0.98%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 2        | 0.98%   |
| Intel 13th Gen Core i7-13700KF              | 2        | 0.98%   |
| Intel 13th Gen Core i5-13600K               | 2        | 0.98%   |
| Intel 12th Gen Core i7-12700                | 2        | 0.98%   |
| Intel 12th Gen Core i3-12100F               | 2        | 0.98%   |
| Intel 12th Gen Core i3-12100                | 2        | 0.98%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 2        | 0.98%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 0.98%   |
| AMD Ryzen 5 3600XT 6-Core Processor         | 2        | 0.98%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 0.98%   |
| AMD FX-8320 Eight-Core Processor            | 2        | 0.98%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 40       | 19.61%  |
| Intel Core i7           | 27       | 13.24%  |
| AMD Ryzen 5             | 21       | 10.29%  |
| Intel Core i3           | 19       | 9.31%   |
| Intel Celeron           | 14       | 6.86%   |
| Other                   | 13       | 6.37%   |
| Intel Xeon              | 7        | 3.43%   |
| AMD Ryzen 7             | 7        | 3.43%   |
| AMD FX                  | 6        | 2.94%   |
| Intel Core 2 Quad       | 5        | 2.45%   |
| Intel Core 2 Duo        | 5        | 2.45%   |
| AMD A8                  | 5        | 2.45%   |
| AMD Phenom II X4        | 4        | 1.96%   |
| Intel Pentium Dual-Core | 3        | 1.47%   |
| AMD Ryzen 9             | 3        | 1.47%   |
| AMD Athlon II X2        | 3        | 1.47%   |
| Intel Pentium 4         | 2        | 0.98%   |
| Intel Pentium           | 2        | 0.98%   |
| AMD Ryzen 3             | 2        | 0.98%   |
| AMD Athlon 64 X2        | 2        | 0.98%   |
| AMD A6                  | 2        | 0.98%   |
| AMD A10                 | 2        | 0.98%   |
| Intel Atom              | 1        | 0.49%   |
| AMD Turion II Neo       | 1        | 0.49%   |
| AMD Sempron             | 1        | 0.49%   |
| AMD Ryzen 7 PRO         | 1        | 0.49%   |
| AMD Ryzen 5 PRO         | 1        | 0.49%   |
| AMD Phenom II X6        | 1        | 0.49%   |
| AMD GX                  | 1        | 0.49%   |
| AMD Athlon X4           | 1        | 0.49%   |
| AMD Athlon II           | 1        | 0.49%   |
| AMD Athlon              | 1        | 0.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 92       | 44.88%  |
| 2      | 51       | 24.88%  |
| 6      | 29       | 14.15%  |
| 8      | 12       | 5.85%   |
| 1      | 6        | 2.93%   |
| 12     | 5        | 2.44%   |
| 3      | 3        | 1.46%   |
| 16     | 2        | 0.98%   |
| 14     | 2        | 0.98%   |
| 10     | 2        | 0.98%   |
| 24     | 1        | 0.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 203      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 117      | 57.64%  |
| 1      | 86       | 42.36%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 203      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 87       | 42.65%  |
| 0x306c3    | 14       | 6.86%   |
| 0x306a9    | 8        | 3.92%   |
| 0x206a7    | 8        | 3.92%   |
| 0x1067a    | 5        | 2.45%   |
| 0x0800820d | 5        | 2.45%   |
| 0x06000852 | 5        | 2.45%   |
| 0x010000c8 | 5        | 2.45%   |
| 0x906ea    | 4        | 1.96%   |
| 0x506e3    | 4        | 1.96%   |
| 0x08701021 | 4        | 1.96%   |
| 0xb0671    | 3        | 1.47%   |
| 0x90672    | 3        | 1.47%   |
| 0x106e5    | 3        | 1.47%   |
| 0x906e9    | 2        | 0.98%   |
| 0x406c3    | 2        | 0.98%   |
| 0x306e4    | 2        | 0.98%   |
| 0x206d7    | 2        | 0.98%   |
| 0x10676    | 2        | 0.98%   |
| 0x0a201016 | 2        | 0.98%   |
| 0x08701013 | 2        | 0.98%   |
| 0x08108109 | 2        | 0.98%   |
| 0x010000c7 | 2        | 0.98%   |
| 0xa0655    | 1        | 0.49%   |
| 0xa0653    | 1        | 0.49%   |
| 0x906ed    | 1        | 0.49%   |
| 0x906eb    | 1        | 0.49%   |
| 0x706a1    | 1        | 0.49%   |
| 0x6fb      | 1        | 0.49%   |
| 0x506c9    | 1        | 0.49%   |
| 0x406c4    | 1        | 0.49%   |
| 0x306f2    | 1        | 0.49%   |
| 0x30679    | 1        | 0.49%   |
| 0x30678    | 1        | 0.49%   |
| 0x206d6    | 1        | 0.49%   |
| 0x206c2    | 1        | 0.49%   |
| 0x20652    | 1        | 0.49%   |
| 0x106ca    | 1        | 0.49%   |
| 0x10677    | 1        | 0.49%   |
| 0x0a601201 | 1        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 27       | 13.24%  |
| SandyBridge      | 19       | 9.31%   |
| KabyLake         | 17       | 8.33%   |
| IvyBridge        | 16       | 7.84%   |
| Zen 2            | 15       | 7.35%   |
| Piledriver       | 11       | 5.39%   |
| Penryn           | 11       | 5.39%   |
| K10              | 10       | 4.9%    |
| Zen+             | 9        | 4.41%   |
| Unknown          | 8        | 3.92%   |
| Skylake          | 7        | 3.43%   |
| Zen 3            | 6        | 2.94%   |
| Silvermont       | 6        | 2.94%   |
| CometLake        | 6        | 2.94%   |
| Alderlake Hybrid | 6        | 2.94%   |
| Zen              | 5        | 2.45%   |
| Nehalem          | 5        | 2.45%   |
| Core             | 3        | 1.47%   |
| Westmere         | 2        | 0.98%   |
| Steamroller      | 2        | 0.98%   |
| NetBurst         | 2        | 0.98%   |
| K8 Hammer        | 2        | 0.98%   |
| Jaguar           | 2        | 0.98%   |
| Excavator        | 2        | 0.98%   |
| K10 Llano        | 1        | 0.49%   |
| Goldmont plus    | 1        | 0.49%   |
| Goldmont         | 1        | 0.49%   |
| Broadwell        | 1        | 0.49%   |
| Bonnell          | 1        | 0.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 87       | 39.73%  |
| Nvidia | 75       | 34.25%  |
| AMD    | 57       | 26.03%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 15       | 6.73%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12       | 5.38%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 10       | 4.48%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7        | 3.14%   |
| Intel HD Graphics 530                                                                    | 7        | 3.14%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7        | 3.14%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6        | 2.69%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4        | 1.79%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 4        | 1.79%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4        | 1.79%   |
| Intel HD Graphics 630                                                                    | 4        | 1.79%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4        | 1.79%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                               | 3        | 1.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 1.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3        | 1.35%   |
| Intel AlderLake-S GT1                                                                    | 3        | 1.35%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3        | 1.35%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3        | 1.35%   |
| AMD RS780L [Radeon 3000]                                                                 | 3        | 1.35%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3        | 1.35%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3        | 1.35%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 2        | 0.9%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 0.9%    |
| Nvidia GM206 [GeForce GTX 950]                                                           | 2        | 0.9%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 0.9%    |
| Nvidia GM107 [GeForce GTX 745]                                                           | 2        | 0.9%    |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 0.9%    |
| Intel DG2 [Arc A770]                                                                     | 2        | 0.9%    |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                                | 2        | 0.9%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2        | 0.9%    |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2        | 0.9%    |
| AMD RS880 [Radeon HD 4250]                                                               | 2        | 0.9%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2        | 0.9%    |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 2        | 0.9%    |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2        | 0.9%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 0.9%    |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                                        | 2        | 0.9%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2        | 0.9%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2        | 0.9%    |
| Nvidia TU117GL [T600]                                                                    | 1        | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 74       | 36.45%  |
| 1 x Nvidia     | 69       | 33.99%  |
| 1 x AMD        | 48       | 23.65%  |
| 2 x AMD        | 3        | 1.48%   |
| Intel + Nvidia | 3        | 1.48%   |
| Intel + AMD    | 3        | 1.48%   |
| AMD + Nvidia   | 3        | 1.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 148      | 72.55%  |
| Proprietary | 48       | 23.53%  |
| Unknown     | 8        | 3.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 123      | 60.29%  |
| 1.01-2.0   | 21       | 10.29%  |
| 0.51-1.0   | 20       | 9.8%    |
| 0.01-0.5   | 12       | 5.88%   |
| 3.01-4.0   | 10       | 4.9%    |
| 7.01-8.0   | 8        | 3.92%   |
| 8.01-16.0  | 5        | 2.45%   |
| 5.01-6.0   | 3        | 1.47%   |
| 2.01-3.0   | 2        | 0.98%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 30       | 14.35%  |
| Dell                 | 30       | 14.35%  |
| Hewlett-Packard      | 18       | 8.61%   |
| AOC                  | 18       | 8.61%   |
| Goldstar             | 16       | 7.66%   |
| Acer                 | 13       | 6.22%   |
| BenQ                 | 9        | 4.31%   |
| Ancor Communications | 9        | 4.31%   |
| Philips              | 8        | 3.83%   |
| ViewSonic            | 6        | 2.87%   |
| Iiyama               | 6        | 2.87%   |
| Fujitsu Siemens      | 4        | 1.91%   |
| Lenovo               | 3        | 1.44%   |
| ASUSTek Computer     | 3        | 1.44%   |
| Unknown              | 2        | 0.96%   |
| RTK                  | 2        | 0.96%   |
| HannStar             | 2        | 0.96%   |
| Eizo                 | 2        | 0.96%   |
| Unknown              | 2        | 0.96%   |
| ___                  | 1        | 0.48%   |
| Vestel Elektronik    | 1        | 0.48%   |
| Unknown (AAA)        | 1        | 0.48%   |
| UGD                  | 1        | 0.48%   |
| Toshiba              | 1        | 0.48%   |
| TEO                  | 1        | 0.48%   |
| Tech Concepts        | 1        | 0.48%   |
| TCL                  | 1        | 0.48%   |
| Sony                 | 1        | 0.48%   |
| SNC                  | 1        | 0.48%   |
| Sceptre Tech         | 1        | 0.48%   |
| RGT                  | 1        | 0.48%   |
| Packard Bell         | 1        | 0.48%   |
| Mi                   | 1        | 0.48%   |
| MAG                  | 1        | 0.48%   |
| LG Electronics       | 1        | 0.48%   |
| JRY                  | 1        | 0.48%   |
| JINGLITAI            | 1        | 0.48%   |
| IBM                  | 1        | 0.48%   |
| Gateway              | 1        | 0.48%   |
| Envision Peripherals | 1        | 0.48%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch               | 2        | 0.9%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 2        | 0.9%    |
| Philips 170S PHL082B 1280x1024 338x270mm 17.0-inch                   | 2        | 0.9%    |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                  | 2        | 0.9%    |
| Hewlett-Packard 2309 HWP2821 1920x1080 510x287mm 23.0-inch           | 2        | 0.9%    |
| HannStar HL205DPB HSD62E0 1600x900 432x240mm 19.5-inch               | 2        | 0.9%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 2        | 0.9%    |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                   | 2        | 0.9%    |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                      | 2        | 0.9%    |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 2        | 0.9%    |
| Unknown                                                              | 2        | 0.9%    |
| ___ LCD Monitor ___1BBC 1920x540 140x90mm 6.6-inch                   | 1        | 0.45%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch        | 1        | 0.45%   |
| ViewSonic VX3276-UHD VSC5138 3840x2160 697x392mm 31.5-inch           | 1        | 0.45%   |
| ViewSonic VP2365 SERIES VSC7C28 1920x1080 509x286mm 23.0-inch        | 1        | 0.45%   |
| ViewSonic VA1948 SERIES VSCE827 1440x900 408x255mm 18.9-inch         | 1        | 0.45%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch   | 1        | 0.45%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                | 1        | 0.45%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1        | 0.45%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch             | 1        | 0.45%   |
| UGD CD220F (H) UGD2210 1920x1080 527x296mm 23.8-inch                 | 1        | 0.45%   |
| Toshiba TV TSB0109 1920x1080                                         | 1        | 0.45%   |
| TEO TL765 TEO6700 1280x1024 338x270mm 17.0-inch                      | 1        | 0.45%   |
| Tech Concepts LCD Monitor 32S327 1280x720                            | 1        | 0.45%   |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                     | 1        | 0.45%   |
| Sony TV SNYAB03 1920x1080                                            | 1        | 0.45%   |
| SNC SKP_E20-27 SNC2700 2560x1440 597x336mm 27.0-inch                 | 1        | 0.45%   |
| Sceptre Tech Sceptre Y27 SPT0AB9 2560x1440 597x336mm 27.0-inch       | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM06A3 1360x768 410x230mm 18.5-inch  | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM0653 1920x1080                     | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM05C4 1920x1080 510x290mm 23.1-inch | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch  | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM03E3 1680x1050 433x271mm 20.1-inch | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch  | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM0273 1440x900 410x257mm 19.1-inch  | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 408x306mm 20.1-inch | 1        | 0.45%   |
| Samsung Electronics SyncMaster SAM00E5 1280x1024 338x270mm 17.0-inch | 1        | 0.45%   |
| Samsung Electronics SMS22A450 SAM0836 1680x1050 470x300mm 22.0-inch  | 1        | 0.45%   |
| Samsung Electronics SMS22A450 SAM0835 1680x1050 470x300mm 22.0-inch  | 1        | 0.45%   |
| Samsung Electronics SMB2430L SAM0645 1920x1080 521x293mm 23.5-inch   | 1        | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 95       | 45.89%  |
| 1280x1024 (SXGA)   | 16       | 7.73%   |
| 2560x1440 (QHD)    | 14       | 6.76%   |
| 1366x768 (WXGA)    | 14       | 6.76%   |
| 1600x900 (HD+)     | 11       | 5.31%   |
| 1440x900 (WXGA+)   | 10       | 4.83%   |
| 3840x2160 (4K)     | 8        | 3.86%   |
| 1680x1050 (WSXGA+) | 7        | 3.38%   |
| 1920x1200 (WUXGA)  | 4        | 1.93%   |
| 1600x1200          | 4        | 1.93%   |
| 1360x768           | 4        | 1.93%   |
| 1024x768 (XGA)     | 4        | 1.93%   |
| 3840x1080          | 3        | 1.45%   |
| 3840x1600          | 2        | 0.97%   |
| 3440x1440          | 2        | 0.97%   |
| 2560x1600          | 2        | 0.97%   |
| 2560x1080          | 2        | 0.97%   |
| Unknown            | 2        | 0.97%   |
| 2288x1287          | 1        | 0.48%   |
| 1920x540           | 1        | 0.48%   |
| 1280x720 (HD)      | 1        | 0.48%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 32       | 15.02%  |
| 23      | 31       | 14.55%  |
| 27      | 22       | 10.33%  |
| 21      | 19       | 8.92%   |
| 19      | 19       | 8.92%   |
| 18      | 16       | 7.51%   |
| Unknown | 12       | 5.63%   |
| 20      | 11       | 5.16%   |
| 17      | 8        | 3.76%   |
| 31      | 6        | 2.82%   |
| 15      | 6        | 2.82%   |
| 22      | 5        | 2.35%   |
| 40      | 4        | 1.88%   |
| 34      | 4        | 1.88%   |
| 72      | 2        | 0.94%   |
| 37      | 2        | 0.94%   |
| 32      | 2        | 0.94%   |
| 26      | 2        | 0.94%   |
| 25      | 2        | 0.94%   |
| 142     | 1        | 0.47%   |
| 84      | 1        | 0.47%   |
| 54      | 1        | 0.47%   |
| 49      | 1        | 0.47%   |
| 48      | 1        | 0.47%   |
| 30      | 1        | 0.47%   |
| 29      | 1        | 0.47%   |
| 6       | 1        | 0.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 81       | 39.32%  |
| 401-500        | 64       | 31.07%  |
| 301-350        | 14       | 6.8%    |
| Unknown        | 12       | 5.83%   |
| 601-700        | 10       | 4.85%   |
| 801-900        | 6        | 2.91%   |
| 701-800        | 6        | 2.91%   |
| 351-400        | 5        | 2.43%   |
| 1501-2000      | 3        | 1.46%   |
| 1001-1500      | 3        | 1.46%   |
| More than 2000 | 1        | 0.49%   |
| 101-200        | 1        | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 131      | 67.18%  |
| 16/10   | 26       | 13.33%  |
| 5/4     | 12       | 6.15%   |
| Unknown | 10       | 5.13%   |
| 4/3     | 7        | 3.59%   |
| 21/9    | 6        | 3.08%   |
| 6/5     | 1        | 0.51%   |
| 32/9    | 1        | 0.51%   |
| 1.00    | 1        | 0.51%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 70       | 33.49%  |
| 151-200        | 39       | 18.66%  |
| 301-350        | 23       | 11%     |
| 141-150        | 23       | 11%     |
| 351-500        | 14       | 6.7%    |
| Unknown        | 12       | 5.74%   |
| 251-300        | 9        | 4.31%   |
| More than 1000 | 6        | 2.87%   |
| 101-110        | 6        | 2.87%   |
| 501-1000       | 6        | 2.87%   |
| 1-40           | 1        | 0.48%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 134      | 68.72%  |
| 101-120       | 35       | 17.95%  |
| Unknown       | 12       | 6.15%   |
| 1-50          | 7        | 3.59%   |
| 121-160       | 6        | 3.08%   |
| More than 240 | 1        | 0.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 161      | 78.92%  |
| 2     | 26       | 12.75%  |
| 0     | 11       | 5.39%   |
| 3     | 6        | 2.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 138      | 47.92%  |
| Intel                           | 85       | 29.51%  |
| Qualcomm Atheros                | 17       | 5.9%    |
| Ralink Technology               | 9        | 3.13%   |
| TP-Link                         | 4        | 1.39%   |
| Nvidia                          | 4        | 1.39%   |
| Broadcom                        | 4        | 1.39%   |
| Broadcom Limited                | 3        | 1.04%   |
| Samsung Electronics             | 2        | 0.69%   |
| Ralink                          | 2        | 0.69%   |
| Marvell Technology Group        | 2        | 0.69%   |
| D-Link System                   | 2        | 0.69%   |
| ZyDAS                           | 1        | 0.35%   |
| Zoom Telephonics                | 1        | 0.35%   |
| TRENDnet                        | 1        | 0.35%   |
| Qualcomm Atheros Communications | 1        | 0.35%   |
| OPPO Electronics                | 1        | 0.35%   |
| NetGear                         | 1        | 0.35%   |
| MicroPython                     | 1        | 0.35%   |
| Microchip Technology            | 1        | 0.35%   |
| Mellanox Technologies           | 1        | 0.35%   |
| MediaTek                        | 1        | 0.35%   |
| Dell                            | 1        | 0.35%   |
| D-Link                          | 1        | 0.35%   |
| Belkin Components               | 1        | 0.35%   |
| ASUSTek Computer                | 1        | 0.35%   |
| ASIX Electronics                | 1        | 0.35%   |
| Aquantia                        | 1        | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 107      | 33.13%  |
| Realtek RTL8125 2.5GbE Controller                                 | 16       | 4.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11       | 3.41%   |
| Intel I211 Gigabit Network Connection                             | 9        | 2.79%   |
| Intel Ethernet Connection (2) I219-V                              | 9        | 2.79%   |
| Intel Wi-Fi 6 AX200                                               | 7        | 2.17%   |
| Intel Ethernet Connection I217-LM                                 | 7        | 2.17%   |
| Ralink MT7601U Wireless Adapter                                   | 6        | 1.86%   |
| Intel Ethernet Controller I225-V                                  | 5        | 1.55%   |
| Intel Ethernet Connection I217-V                                  | 5        | 1.55%   |
| Realtek 802.11ac NIC                                              | 4        | 1.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4        | 1.24%   |
| Nvidia MCP61 Ethernet                                             | 4        | 1.24%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4        | 1.24%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 1.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 0.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.93%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3        | 0.93%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.93%   |
| Intel Wireless 7260                                               | 3        | 0.93%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3        | 0.93%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 0.93%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 0.93%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.62%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.62%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 2        | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.62%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2        | 0.62%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2        | 0.62%   |
| Intel Wireless 3160                                               | 2        | 0.62%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.62%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 0.62%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.62%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2        | 0.62%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 0.62%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 0.62%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 2        | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 25       | 28.41%  |
| Realtek Semiconductor           | 23       | 26.14%  |
| Qualcomm Atheros                | 14       | 15.91%  |
| Ralink Technology               | 9        | 10.23%  |
| TP-Link                         | 4        | 4.55%   |
| Ralink                          | 2        | 2.27%   |
| ZyDAS                           | 1        | 1.14%   |
| TRENDnet                        | 1        | 1.14%   |
| Qualcomm Atheros Communications | 1        | 1.14%   |
| NetGear                         | 1        | 1.14%   |
| MediaTek                        | 1        | 1.14%   |
| Dell                            | 1        | 1.14%   |
| D-Link System                   | 1        | 1.14%   |
| D-Link                          | 1        | 1.14%   |
| Broadcom                        | 1        | 1.14%   |
| Belkin Components               | 1        | 1.14%   |
| ASUSTek Computer                | 1        | 1.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                            | 7        | 7.95%   |
| Ralink MT7601U Wireless Adapter                                                | 6        | 6.82%   |
| Realtek 802.11ac NIC                                                           | 4        | 4.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 4        | 4.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 4        | 4.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 3        | 3.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 3        | 3.41%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 3        | 3.41%   |
| Intel Wireless 7260                                                            | 3        | 3.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 3        | 3.41%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                       | 2        | 2.27%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                       | 2        | 2.27%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 2        | 2.27%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 2        | 2.27%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 2        | 2.27%   |
| Intel Wireless 3160                                                            | 2        | 2.27%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 2        | 2.27%   |
| Intel 700 Series Chipset Family Wi-Fi                                          | 2        | 2.27%   |
| ZyDAS ZD1211B 802.11g                                                          | 1        | 1.14%   |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU]     | 1        | 1.14%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                          | 1        | 1.14%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 1        | 1.14%   |
| TP-Link Archer T4U ver.3                                                       | 1        | 1.14%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 1        | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 1        | 1.14%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 1        | 1.14%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 1        | 1.14%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                | 1        | 1.14%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 1        | 1.14%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1        | 1.14%   |
| Realtek RTL8187 Wireless Adapter                                               | 1        | 1.14%   |
| Ralink RT5572 Wireless Adapter                                                 | 1        | 1.14%   |
| Ralink RT2770 Wireless Adapter                                                 | 1        | 1.14%   |
| Ralink RT2501/RT2573 Wireless Adapter                                          | 1        | 1.14%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                         | 1        | 1.14%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 1        | 1.14%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1        | 1.14%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                               | 1        | 1.14%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1        | 1.14%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                     | 1        | 1.14%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 128      | 57.66%  |
| Intel                    | 72       | 32.43%  |
| Qualcomm Atheros         | 4        | 1.8%    |
| Nvidia                   | 4        | 1.8%    |
| Broadcom Limited         | 3        | 1.35%   |
| Broadcom                 | 3        | 1.35%   |
| Samsung Electronics      | 2        | 0.9%    |
| Marvell Technology Group | 2        | 0.9%    |
| OPPO Electronics         | 1        | 0.45%   |
| D-Link System            | 1        | 0.45%   |
| ASIX Electronics         | 1        | 0.45%   |
| Aquantia                 | 1        | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 107      | 46.32%  |
| Realtek RTL8125 2.5GbE Controller                                 | 16       | 6.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11       | 4.76%   |
| Intel I211 Gigabit Network Connection                             | 9        | 3.9%    |
| Intel Ethernet Connection (2) I219-V                              | 9        | 3.9%    |
| Intel Ethernet Connection I217-LM                                 | 7        | 3.03%   |
| Intel Ethernet Controller I225-V                                  | 5        | 2.16%   |
| Intel Ethernet Connection I217-V                                  | 5        | 2.16%   |
| Nvidia MCP61 Ethernet                                             | 4        | 1.73%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 1.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 1.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 1.3%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 1.3%    |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.3%    |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.87%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.87%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.87%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 0.87%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.87%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 0.87%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 0.87%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 2        | 0.87%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.43%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 0.43%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.43%   |
| OPPO 8                                                            | 1        | 0.43%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.43%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.43%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.43%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.43%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 0.43%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.43%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.43%   |
| Intel 82541GI Gigabit Ethernet Controller                         | 1        | 0.43%   |
| Intel 82540EM Gigabit Ethernet Controller                         | 1        | 0.43%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 0.43%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.43%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 1        | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 201      | 69.79%  |
| WiFi     | 83       | 28.82%  |
| Modem    | 3        | 1.04%   |
| Unknown  | 1        | 0.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 164      | 76.28%  |
| WiFi     | 51       | 23.72%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 134      | 65.69%  |
| 2     | 57       | 27.94%  |
| 3     | 9        | 4.41%   |
| 4     | 2        | 0.98%   |
| 0     | 2        | 0.98%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 135      | 65.53%  |
| Yes  | 71       | 34.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 23       | 38.33%  |
| Cambridge Silicon Radio         | 19       | 31.67%  |
| Realtek Semiconductor           | 6        | 10%     |
| Qualcomm Atheros Communications | 3        | 5%      |
| Broadcom                        | 3        | 5%      |
| IMC Networks                    | 2        | 3.33%   |
| TP-Link                         | 1        | 1.67%   |
| MediaTek                        | 1        | 1.67%   |
| Lite-On Technology              | 1        | 1.67%   |
| Fujitsu                         | 1        | 1.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 19       | 31.67%  |
| Intel AX200 Bluetooth                               | 7        | 11.67%  |
| Intel Bluetooth wireless interface                  | 6        | 10%     |
| Realtek Bluetooth Radio                             | 4        | 6.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4        | 6.67%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 3.33%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2        | 3.33%   |
| Intel Bluetooth Device                              | 2        | 3.33%   |
| Intel AX201 Bluetooth                               | 2        | 3.33%   |
| IMC Networks Bluetooth Radio                        | 2        | 3.33%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 3.33%   |
| TP-Link UB5A Adapter                                | 1        | 1.67%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 1.67%   |
| MediaTek Wireless_Device                            | 1        | 1.67%   |
| Lite-On Bluetooth Device                            | 1        | 1.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 1.67%   |
| Intel AX210 Bluetooth                               | 1        | 1.67%   |
| Fujitsu Bluetooth Device                            | 1        | 1.67%   |
| Broadcom BCM2210 Bluetooth                          | 1        | 1.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 138      | 43.53%  |
| AMD                         | 73       | 23.03%  |
| Nvidia                      | 67       | 21.14%  |
| Creative Labs               | 6        | 1.89%   |
| C-Media Electronics         | 5        | 1.58%   |
| Texas Instruments           | 2        | 0.63%   |
| SAVITECH                    | 2        | 0.63%   |
| Medeli Electronics          | 2        | 0.63%   |
| Logitech                    | 2        | 0.63%   |
| VIA Technologies            | 1        | 0.32%   |
| Tenx Technology             | 1        | 0.32%   |
| STMicroelectronics          | 1        | 0.32%   |
| Sennheiser Communications   | 1        | 0.32%   |
| Samson Technologies         | 1        | 0.32%   |
| Roland                      | 1        | 0.32%   |
| PreSonus Audio Electronics  | 1        | 0.32%   |
| Micro Star International    | 1        | 0.32%   |
| MAG Technology              | 1        | 0.32%   |
| M-Audio                     | 1        | 0.32%   |
| Lenovo                      | 1        | 0.32%   |
| Kingston Technology         | 1        | 0.32%   |
| JMTek                       | 1        | 0.32%   |
| Hewlett-Packard             | 1        | 0.32%   |
| GN Netcom                   | 1        | 0.32%   |
| FiiO Electronics Technology | 1        | 0.32%   |
| Creative Technology         | 1        | 0.32%   |
| Corsair                     | 1        | 0.32%   |
| BR23                        | 1        | 0.32%   |
| BEHRINGER International     | 1        | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 21       | 5.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16       | 4.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 15       | 4.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 15       | 4.09%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 15       | 4.09%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 14       | 3.81%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 13       | 3.54%   |
| AMD FCH Azalia Controller                                                                         | 12       | 3.27%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10       | 2.72%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 9        | 2.45%   |
| Intel 200 Series PCH HD Audio                                                                     | 9        | 2.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7        | 1.91%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7        | 1.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7        | 1.91%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 7        | 1.91%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7        | 1.91%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6        | 1.63%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6        | 1.63%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 5        | 1.36%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 5        | 1.36%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 5        | 1.36%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5        | 1.36%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 5        | 1.36%   |
| Nvidia MCP61 High Definition Audio                                                                | 4        | 1.09%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4        | 1.09%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4        | 1.09%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 4        | 1.09%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4        | 1.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4        | 1.09%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4        | 1.09%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4        | 1.09%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3        | 0.82%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3        | 0.82%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 3        | 0.82%   |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 3        | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3        | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3        | 0.82%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1                                  | 3        | 0.82%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3        | 0.82%   |
| Texas Instruments PCM2900C Audio CODEC                                                            | 2        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 30       | 18.29%  |
| Unknown             | 26       | 15.85%  |
| Samsung Electronics | 19       | 11.59%  |
| SK hynix            | 16       | 9.76%   |
| Crucial             | 14       | 8.54%   |
| Corsair             | 14       | 8.54%   |
| G.Skill             | 12       | 7.32%   |
| Ramaxel Technology  | 5        | 3.05%   |
| Nanya Technology    | 5        | 3.05%   |
| Micron Technology   | 3        | 1.83%   |
| Elpida              | 3        | 1.83%   |
| A-DATA Technology   | 3        | 1.83%   |
| Unknown             | 3        | 1.83%   |
| Unknown (ABCD)      | 2        | 1.22%   |
| V-Color             | 1        | 0.61%   |
| Unknown (AB)        | 1        | 0.61%   |
| Unknown (0x0B15)    | 1        | 0.61%   |
| Transcend           | 1        | 0.61%   |
| Timetec             | 1        | 0.61%   |
| Qumo                | 1        | 0.61%   |
| GLOWAY              | 1        | 0.61%   |
| GIGA-BYTE           | 1        | 0.61%   |
| ASint Technology    | 1        | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 3        | 1.72%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 3        | 1.72%   |
| Unknown                                                        | 3        | 1.72%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 2        | 1.15%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                           | 2        | 1.15%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s | 2        | 1.15%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 2        | 1.15%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 2        | 1.15%   |
| Ramaxel RAM RMUA5120ME86H9F-2666 4GB DIMM DDR4 2667MT/s        | 2        | 1.15%   |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s             | 2        | 1.15%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 2        | 1.15%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 2        | 1.15%   |
| Kingston RAM 9905713-026.A00G 4GB DIMM DDR4 2667MT/s           | 2        | 1.15%   |
| V-Color RAM TN4G8C11-H11 4GB DIMM DDR3 1600MT/s                | 1        | 0.57%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                      | 1        | 0.57%   |
| Unknown RAM Module 4GB DIMM SDRAM                              | 1        | 0.57%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                           | 1        | 0.57%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 1        | 0.57%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                           | 1        | 0.57%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                       | 1        | 0.57%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                      | 1        | 0.57%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 1        | 0.57%   |
| Unknown RAM Module 2GB DIMM DDR2 400MT/s                       | 1        | 0.57%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                      | 1        | 0.57%   |
| Unknown RAM Module 2GB DIMM DDR2                               | 1        | 0.57%   |
| Unknown RAM Module 2GB DIMM 5354MT/s                           | 1        | 0.57%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 0.57%   |
| Unknown RAM Module 1GB DIMM DDR2                               | 1        | 0.57%   |
| Unknown RAM CL17-17-17 D4-2400 16384MB DIMM DDR4 2400MT/s      | 1        | 0.57%   |
| Unknown RAM 2400 C16 Series 8192MB DIMM DDR4 1200MT/s          | 1        | 0.57%   |
| Unknown RAM 1600 CL9 Series 8192MB DIMM DDR3 1066MT/s          | 1        | 0.57%   |
| Unknown (AB) RAM Module 2GB DIMM LPDDR3 1333MT/s               | 1        | 0.57%   |
| Unknown (0x0B15) RAM JAD3200U1816 16GB DIMM DDR4 2667MT/s      | 1        | 0.57%   |
| Transcend RAM Module 2GB DIMM DDR3 1333MT/s                    | 1        | 0.57%   |
| Timetec RAM UD3-1333 4GB DIMM DDR3 1333MT/s                    | 1        | 0.57%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                   | 1        | 0.57%   |
| SK hynix RAM Module 8GB DIMM DDR4 2133MT/s                     | 1        | 0.57%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                   | 1        | 0.57%   |
| SK hynix RAM Module 16GB DIMM DDR4 2667MT/s                    | 1        | 0.57%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 62       | 44.6%   |
| DDR4    | 52       | 37.41%  |
| Unknown | 8        | 5.76%   |
| SDRAM   | 7        | 5.04%   |
| DDR2    | 5        | 3.6%    |
| LPDDR4  | 2        | 1.44%   |
| DDR5    | 2        | 1.44%   |
| LPDDR3  | 1        | 0.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 129      | 94.85%  |
| SODIMM | 7        | 5.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 51       | 34.23%  |
| 4096  | 50       | 33.56%  |
| 16384 | 21       | 14.09%  |
| 2048  | 21       | 14.09%  |
| 32768 | 3        | 2.01%   |
| 1024  | 3        | 2.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 38       | 24.84%  |
| 1333    | 21       | 13.73%  |
| 2667    | 11       | 7.19%   |
| 2400    | 11       | 7.19%   |
| 3200    | 10       | 6.54%   |
| 3600    | 9        | 5.88%   |
| Unknown | 6        | 3.92%   |
| 2133    | 5        | 3.27%   |
| 3000    | 4        | 2.61%   |
| 1866    | 4        | 2.61%   |
| 3466    | 3        | 1.96%   |
| 2666    | 3        | 1.96%   |
| 1867    | 3        | 1.96%   |
| 1800    | 3        | 1.96%   |
| 1067    | 2        | 1.31%   |
| 1066    | 2        | 1.31%   |
| 800     | 2        | 1.31%   |
| 52217   | 1        | 0.65%   |
| 6000    | 1        | 0.65%   |
| 5354    | 1        | 0.65%   |
| 4800    | 1        | 0.65%   |
| 4000    | 1        | 0.65%   |
| 3866    | 1        | 0.65%   |
| 3400    | 1        | 0.65%   |
| 3333    | 1        | 0.65%   |
| 3020    | 1        | 0.65%   |
| 2800    | 1        | 0.65%   |
| 2200    | 1        | 0.65%   |
| 2000    | 1        | 0.65%   |
| 1648    | 1        | 0.65%   |
| 1639    | 1        | 0.65%   |
| 1334    | 1        | 0.65%   |
| 400     | 1        | 0.65%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 5        | 41.67%  |
| Brother Industries  | 3        | 25%     |
| Samsung Electronics | 2        | 16.67%  |
| Kyocera             | 1        | 8.33%   |
| Canon               | 1        | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Samsung SF-760 Series         | 1        | 8.33%   |
| Samsung ML-1865               | 1        | 8.33%   |
| Kyocera FS-1300D              | 1        | 8.33%   |
| HP LaserJet P1102             | 1        | 8.33%   |
| HP DeskJet D1360              | 1        | 8.33%   |
| HP DeskJet 840c               | 1        | 8.33%   |
| HP DeskJet 810c/812c          | 1        | 8.33%   |
| HP Deskjet 3070 B611 series   | 1        | 8.33%   |
| Canon TS3500 series           | 1        | 8.33%   |
| Brother QL-560 Label Printer  | 1        | 8.33%   |
| Brother HL-2030 Laser Printer | 1        | 8.33%   |
| Brother DCP-7040              | 1        | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 4        | 66.67%  |
| Seiko Epson     | 1        | 16.67%  |
| Hewlett-Packard | 1        | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Canon CanoScan LiDE 100                | 2        | 33.33%  |
| Seiko Epson GT-9800F [Perfection 3200] | 1        | 16.67%  |
| HP ScanJet 7400c                       | 1        | 16.67%  |
| Canon CanoScan LIDE 25                 | 1        | 16.67%  |
| Canon CanoScan LiDE 110                | 1        | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 8        | 26.67%  |
| Microdia                    | 4        | 13.33%  |
| Realtek Semiconductor       | 2        | 6.67%   |
| Microsoft                   | 2        | 6.67%   |
| KYE Systems (Mouse Systems) | 2        | 6.67%   |
| Jieli Technology            | 2        | 6.67%   |
| Xiaomi                      | 1        | 3.33%   |
| Silicon Motion              | 1        | 3.33%   |
| Samsung Electronics         | 1        | 3.33%   |
| Ruision                     | 1        | 3.33%   |
| Quanta                      | 1        | 3.33%   |
| IMC Networks                | 1        | 3.33%   |
| Guillemot                   | 1        | 3.33%   |
| Generalplus Technology      | 1        | 3.33%   |
| Creative Technology         | 1        | 3.33%   |
| Apple                       | 1        | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                    | 2        | 6.67%   |
| Logitech C922 Pro Stream Webcam                | 2        | 6.67%   |
| Xiaomi Mi/Redmi series (PTP)                   | 1        | 3.33%   |
| Silicon Motion 300k Pixel Camera               | 1        | 3.33%   |
| Samsung Galaxy series, misc. (MTP mode)        | 1        | 3.33%   |
| Ruision UVC Camera                             | 1        | 3.33%   |
| Realtek Full HD webcam                         | 1        | 3.33%   |
| Realtek FULL HD 1080P Webcam                   | 1        | 3.33%   |
| Quanta HP HD Camera                            | 1        | 3.33%   |
| Microsoft MicrosoftÂ LifeCam Studio           | 1        | 3.33%   |
| Microsoft LifeCam VX-2000                      | 1        | 3.33%   |
| Microdia Webcam Vitade AF                      | 1        | 3.33%   |
| Microdia USB 2.0 Camera                        | 1        | 3.33%   |
| Microdia Sonix USB 2.0 Camera                  | 1        | 3.33%   |
| Microdia Camera                                | 1        | 3.33%   |
| Logitech Webcam C300                           | 1        | 3.33%   |
| Logitech Webcam C110                           | 1        | 3.33%   |
| Logitech HD Webcam C525                        | 1        | 3.33%   |
| Logitech BRIO                                  | 1        | 3.33%   |
| KYE Systems (Mouse Systems) iSlim 2020AF       | 1        | 3.33%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320 | 1        | 3.33%   |
| Jieli USB PHY 2.0                              | 1        | 3.33%   |
| Jieli USB Composite Device                     | 1        | 3.33%   |
| IMC Networks USB2.0 UVC HD Webcam              | 1        | 3.33%   |
| Guillemot Hercules Dualpix Exchange            | 1        | 3.33%   |
| Generalplus CAMERA - UVC                       | 1        | 3.33%   |
| Creative Live! Cam Sync 1080p                  | 1        | 3.33%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR             | 1        | 3.33%   |

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
| 0     | 175      | 84.95%  |
| 1     | 26       | 12.62%  |
| 2     | 3        | 1.46%   |
| 3     | 2        | 0.97%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 17       | 48.57%  |
| Net/wireless             | 3        | 8.57%   |
| Unassigned class         | 2        | 5.71%   |
| Sound                    | 2        | 5.71%   |
| Multimedia controller    | 2        | 5.71%   |
| Chipcard                 | 2        | 5.71%   |
| Camera                   | 2        | 5.71%   |
| Network                  | 1        | 2.86%   |
| Net/ethernet             | 1        | 2.86%   |
| Dvb card                 | 1        | 2.86%   |
| Communication controller | 1        | 2.86%   |
| Bluetooth                | 1        | 2.86%   |

