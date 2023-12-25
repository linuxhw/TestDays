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

Total: 315

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | P35-DS3R                    | [741ad16651](https://linux-hardware.org/?probe=741ad16651) | Dec 22, 2023 |
| MSI           | X570-A PRO                  | [07a7762b25](https://linux-hardware.org/?probe=07a7762b25) | Dec 21, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [ee1a222677](https://linux-hardware.org/?probe=ee1a222677) | Dec 20, 2023 |
| HP            | 212B                        | [1ce8b8d929](https://linux-hardware.org/?probe=1ce8b8d929) | Dec 14, 2023 |
| Intel         | H310 Series                 | [9565b22822](https://linux-hardware.org/?probe=9565b22822) | Dec 13, 2023 |
| Lenovo        | NO DPK                      | [2204183295](https://linux-hardware.org/?probe=2204183295) | Dec 12, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [e223660e23](https://linux-hardware.org/?probe=e223660e23) | Dec 11, 2023 |
| ASUSTek       | PRIME H510M-A WIFI          | [ba43863b29](https://linux-hardware.org/?probe=ba43863b29) | Dec 09, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [74440ebfad](https://linux-hardware.org/?probe=74440ebfad) | Dec 07, 2023 |
| Intel         | DB75EN                      | [15f11719b5](https://linux-hardware.org/?probe=15f11719b5) | Dec 02, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [c8e6af0346](https://linux-hardware.org/?probe=c8e6af0346) | Nov 30, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [4b14c830c0](https://linux-hardware.org/?probe=4b14c830c0) | Nov 26, 2023 |
| MSI           | B250M PRO-VD                | [d3697eee2c](https://linux-hardware.org/?probe=d3697eee2c) | Nov 24, 2023 |
| Dell          | 0M5DCD A00                  | [78748bcf50](https://linux-hardware.org/?probe=78748bcf50) | Nov 24, 2023 |
| Intel         | DH55TC AAG26116-302         | [0edf2befff](https://linux-hardware.org/?probe=0edf2befff) | Nov 21, 2023 |
| Gigabyte      | H81M-DS2                    | [9701d268e8](https://linux-hardware.org/?probe=9701d268e8) | Nov 21, 2023 |
| HP            | 21B4 A01                    | [73a4740b8f](https://linux-hardware.org/?probe=73a4740b8f) | Nov 18, 2023 |
| Intel         | DH55TC AAG26116-302         | [8a23e4f586](https://linux-hardware.org/?probe=8a23e4f586) | Nov 16, 2023 |
| Intel         | DH55TC AAG26116-302         | [7fabbf9cb1](https://linux-hardware.org/?probe=7fabbf9cb1) | Nov 16, 2023 |
| ASRock        | Z590M-ITX/ax                | [238b7326f1](https://linux-hardware.org/?probe=238b7326f1) | Nov 10, 2023 |
| ASRock        | Z590M-ITX/ax                | [c1a263f3b5](https://linux-hardware.org/?probe=c1a263f3b5) | Nov 08, 2023 |
| ASUSTek       | P5K                         | [4870e13f93](https://linux-hardware.org/?probe=4870e13f93) | Nov 08, 2023 |
| Pegatron      | 2AF0                        | [d918aae63e](https://linux-hardware.org/?probe=d918aae63e) | Nov 06, 2023 |
| Pegatron      | 2AF0                        | [de892702f8](https://linux-hardware.org/?probe=de892702f8) | Nov 05, 2023 |
| Gigabyte      | B450M DS3H-CF               | [fefb7e12d2](https://linux-hardware.org/?probe=fefb7e12d2) | Nov 05, 2023 |
| Acer          | Aspire TC-885 V:1.1         | [a871f012a2](https://linux-hardware.org/?probe=a871f012a2) | Nov 02, 2023 |
| Gigabyte      | H77M-D3H                    | [1d3f58a610](https://linux-hardware.org/?probe=1d3f58a610) | Oct 25, 2023 |
| Dell          | 0XKH0D A02                  | [bba36c01cf](https://linux-hardware.org/?probe=bba36c01cf) | Oct 19, 2023 |
| MSI           | B550 GAMING GEN3            | [e657535210](https://linux-hardware.org/?probe=e657535210) | Oct 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d519c10989](https://linux-hardware.org/?probe=d519c10989) | Oct 16, 2023 |
| Unknown       | Unknown                     | [626c7e1591](https://linux-hardware.org/?probe=626c7e1591) | Oct 16, 2023 |
| HP            | 18E5                        | [d869fcd6dc](https://linux-hardware.org/?probe=d869fcd6dc) | Oct 16, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [18922baf01](https://linux-hardware.org/?probe=18922baf01) | Oct 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [430df05ea3](https://linux-hardware.org/?probe=430df05ea3) | Oct 14, 2023 |
| HP            | 339A                        | [188e7d023e](https://linux-hardware.org/?probe=188e7d023e) | Oct 14, 2023 |
| HP            | 18E5                        | [653e855c90](https://linux-hardware.org/?probe=653e855c90) | Oct 05, 2023 |
| MSI           | B550 GAMING GEN3            | [870556d425](https://linux-hardware.org/?probe=870556d425) | Oct 04, 2023 |
| HP            | 09F8h                       | [996f1179ba](https://linux-hardware.org/?probe=996f1179ba) | Oct 02, 2023 |
| ASUSTek       | P5Q SE2                     | [df644adbab](https://linux-hardware.org/?probe=df644adbab) | Oct 01, 2023 |
| ASUSTek       | P5Q SE2                     | [2ccade9ad8](https://linux-hardware.org/?probe=2ccade9ad8) | Oct 01, 2023 |
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
| 5.15.0-56-generic    | 18       | 7.03%   |
| 5.15.0-52-generic    | 16       | 6.25%   |
| 5.15.0-58-generic    | 9        | 3.52%   |
| 5.15.0-47-generic    | 9        | 3.52%   |
| 5.15.0-46-generic    | 9        | 3.52%   |
| 5.15.0-67-generic    | 8        | 3.13%   |
| 5.15.0-60-generic    | 8        | 3.13%   |
| 6.2.0-36-generic     | 6        | 2.34%   |
| 5.15.0-48-generic    | 6        | 2.34%   |
| 5.15.0-27-generic    | 6        | 2.34%   |
| 5.15.0-25-generic    | 6        | 2.34%   |
| 6.2.0-37-generic     | 5        | 1.95%   |
| 5.19.0-41-generic    | 5        | 1.95%   |
| 5.19.0-35-generic    | 5        | 1.95%   |
| 5.15.0-43-generic    | 5        | 1.95%   |
| 5.15.0-41-generic    | 5        | 1.95%   |
| 6.2.0-33-generic     | 4        | 1.56%   |
| 5.19.0-50-generic    | 4        | 1.56%   |
| 5.19.0-43-generic    | 4        | 1.56%   |
| 5.15.0-78-generic    | 4        | 1.56%   |
| 5.15.0-69-generic    | 4        | 1.56%   |
| 5.15.0-57-generic    | 4        | 1.56%   |
| 5.15.0-53-generic    | 4        | 1.56%   |
| 5.15.0-50-generic    | 4        | 1.56%   |
| 6.2.0-34-generic     | 3        | 1.17%   |
| 6.2.0-31-generic     | 3        | 1.17%   |
| 6.2.0-26-generic     | 3        | 1.17%   |
| 5.19.0-46-generic    | 3        | 1.17%   |
| 5.19.0-32-generic    | 3        | 1.17%   |
| 5.15.0-84-generic    | 3        | 1.17%   |
| 5.15.0-75-generic    | 3        | 1.17%   |
| 5.15.0-73-generic    | 3        | 1.17%   |
| 5.15.0-40-generic    | 3        | 1.17%   |
| 6.2.7-060207-generic | 2        | 0.78%   |
| 6.2.0-32-generic     | 2        | 0.78%   |
| 5.19.0-45-generic    | 2        | 0.78%   |
| 5.15.0-88-generic    | 2        | 0.78%   |
| 5.15.0-83-generic    | 2        | 0.78%   |
| 5.15.0-79-generic    | 2        | 0.78%   |
| 5.15.0-76-generic    | 2        | 0.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 158      | 67.52%  |
| 6.2.0   | 28       | 11.97%  |
| 5.19.0  | 27       | 11.54%  |
| 6.2.7   | 2        | 0.85%   |
| 6.1.0   | 2        | 0.85%   |
| 5.17.0  | 2        | 0.85%   |
| 5.13.0  | 2        | 0.85%   |
| 6.5.0   | 1        | 0.43%   |
| 6.4.8   | 1        | 0.43%   |
| 6.3.3   | 1        | 0.43%   |
| 6.3.12  | 1        | 0.43%   |
| 6.2.2   | 1        | 0.43%   |
| 6.2.10  | 1        | 0.43%   |
| 6.1.10  | 1        | 0.43%   |
| 6.0.0   | 1        | 0.43%   |
| 5.4.0   | 1        | 0.43%   |
| 5.19.13 | 1        | 0.43%   |
| 5.19.1  | 1        | 0.43%   |
| 5.18.0  | 1        | 0.43%   |
| 5.17.5  | 1        | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 158      | 67.52%  |
| 6.2     | 32       | 13.68%  |
| 5.19    | 29       | 12.39%  |
| 6.1     | 3        | 1.28%   |
| 5.17    | 3        | 1.28%   |
| 6.3     | 2        | 0.85%   |
| 5.13    | 2        | 0.85%   |
| 6.5     | 1        | 0.43%   |
| 6.4     | 1        | 0.43%   |
| 6.0     | 1        | 0.43%   |
| 5.4     | 1        | 0.43%   |
| 5.18    | 1        | 0.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 228      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| XFCE            | 221      | 96.51%  |
| GNOME           | 4        | 1.75%   |
| i3              | 2        | 0.87%   |
| KDE5            | 1        | 0.44%   |
| GNOME Flashback | 1        | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 221      | 95.26%  |
| Tty  | 11       | 4.74%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 187      | 82.02%  |
| Unknown | 23       | 10.09%  |
| GDM3    | 15       | 6.58%   |
| SDDM    | 2        | 0.88%   |
| GDM     | 1        | 0.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 80       | 35.09%  |
| de_DE   | 30       | 13.16%  |
| fr_FR   | 29       | 12.72%  |
| it_IT   | 17       | 7.46%   |
| pt_BR   | 13       | 5.7%    |
| en_CA   | 9        | 3.95%   |
| en_GB   | 7        | 3.07%   |
| ru_RU   | 5        | 2.19%   |
| en_AU   | 4        | 1.75%   |
| C       | 4        | 1.75%   |
| pl_PL   | 3        | 1.32%   |
| es_ES   | 3        | 1.32%   |
| es_AR   | 3        | 1.32%   |
| nl_NL   | 2        | 0.88%   |
| hu_HU   | 2        | 0.88%   |
| fi_FI   | 2        | 0.88%   |
| en_IN   | 2        | 0.88%   |
| cs_CZ   | 2        | 0.88%   |
| tr_TR   | 1        | 0.44%   |
| sv_SE   | 1        | 0.44%   |
| ru_UA   | 1        | 0.44%   |
| fr_CH   | 1        | 0.44%   |
| fr_CA   | 1        | 0.44%   |
| fr_BE   | 1        | 0.44%   |
| es_VE   | 1        | 0.44%   |
| es_CO   | 1        | 0.44%   |
| en_ZA   | 1        | 0.44%   |
| en_NZ   | 1        | 0.44%   |
| Unknown | 1        | 0.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 133      | 58.08%  |
| EFI  | 96       | 41.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 193      | 83.55%  |
| Tmpfs   | 23       | 9.96%   |
| Overlay | 7        | 3.03%   |
| Btrfs   | 5        | 2.16%   |
| Zfs     | 2        | 0.87%   |
| Ext3    | 1        | 0.43%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 153      | 65.67%  |
| MBR     | 44       | 18.88%  |
| Unknown | 36       | 15.45%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 180      | 77.92%  |
| Yes       | 51       | 22.08%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 148      | 64.35%  |
| Yes       | 82       | 35.65%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 58       | 25.44%  |
| Gigabyte Technology | 34       | 14.91%  |
| MSI                 | 33       | 14.47%  |
| Hewlett-Packard     | 23       | 10.09%  |
| Dell                | 17       | 7.46%   |
| ASRock              | 16       | 7.02%   |
| Lenovo              | 11       | 4.82%   |
| Intel               | 7        | 3.07%   |
| Acer                | 5        | 2.19%   |
| Fujitsu             | 3        | 1.32%   |
| Foxconn             | 3        | 1.32%   |
| Unknown             | 3        | 1.32%   |
| Pegatron            | 2        | 0.88%   |
| PCWare              | 2        | 0.88%   |
| Medion              | 2        | 0.88%   |
| Semp Toshiba        | 1        | 0.44%   |
| Packard Bell        | 1        | 0.44%   |
| OEM                 | 1        | 0.44%   |
| MACHINIST           | 1        | 0.44%   |
| Itautec             | 1        | 0.44%   |
| Hardkernel          | 1        | 0.44%   |
| eMachines           | 1        | 0.44%   |
| Biostar             | 1        | 0.44%   |
| AMD                 | 1        | 0.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| ASUS All Series                 | 5        | 2.19%   |
| Dell OptiPlex 7010              | 4        | 1.75%   |
| Unknown                         | 4        | 1.75%   |
| MSI MS-7D43                     | 3        | 1.32%   |
| MSI MS-7721                     | 3        | 1.32%   |
| ASUS K30AD_M31AD_M51AD          | 3        | 1.32%   |
| MSI MS-7D46                     | 2        | 0.88%   |
| MSI MS-7D25                     | 2        | 0.88%   |
| MSI MS-7C52                     | 2        | 0.88%   |
| MSI MS-7817                     | 2        | 0.88%   |
| Lenovo V530S-07ICB 10TX0010PB   | 2        | 0.88%   |
| HP t620 Quad Core TC            | 2        | 0.88%   |
| Dell OptiPlex 9020              | 2        | 0.88%   |
| Dell OptiPlex 390               | 2        | 0.88%   |
| ASUS ROG STRIX B450-F GAMING II | 2        | 0.88%   |
| Semp Toshiba STI                | 1        | 0.44%   |
| Pegatron FZ132AA-ABF m9456fr    | 1        | 0.44%   |
| Pegatron 20-b010                | 1        | 0.44%   |
| PCWare IPX1800E2                | 1        | 0.44%   |
| PCWare IPMH81G1                 | 1        | 0.44%   |
| Packard Bell IMEDIA X9305       | 1        | 0.44%   |
| MSI MS-7E07                     | 1        | 0.44%   |
| MSI MS-7D40                     | 1        | 0.44%   |
| MSI MS-7C91                     | 1        | 0.44%   |
| MSI MS-7C84                     | 1        | 0.44%   |
| MSI MS-7C56                     | 1        | 0.44%   |
| MSI MS-7C37                     | 1        | 0.44%   |
| MSI MS-7C08                     | 1        | 0.44%   |
| MSI MS-7C02                     | 1        | 0.44%   |
| MSI MS-7B98                     | 1        | 0.44%   |
| MSI MS-7B86                     | 1        | 0.44%   |
| MSI MS-7A74                     | 1        | 0.44%   |
| MSI MS-7A32                     | 1        | 0.44%   |
| MSI MS-7982                     | 1        | 0.44%   |
| MSI MS-7835                     | 1        | 0.44%   |
| MSI MS-7758                     | 1        | 0.44%   |
| MSI MS-7529                     | 1        | 0.44%   |
| MSI MS-7309                     | 1        | 0.44%   |
| MSI Hyrican PC A320M PRO-E      | 1        | 0.44%   |
| MSI 5860                        | 1        | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 16       | 7.02%   |
| Dell OptiPlex        | 13       | 5.7%    |
| Lenovo ThinkCentre   | 7        | 3.07%   |
| ASUS ROG             | 7        | 3.07%   |
| HP Compaq            | 5        | 2.19%   |
| ASUS All             | 5        | 2.19%   |
| HP EliteDesk         | 4        | 1.75%   |
| ASUS TUF             | 4        | 1.75%   |
| Acer Veriton         | 4        | 1.75%   |
| Unknown              | 4        | 1.75%   |
| MSI MS-7D43          | 3        | 1.32%   |
| MSI MS-7721          | 3        | 1.32%   |
| ASUS K30AD           | 3        | 1.32%   |
| MSI MS-7D46          | 2        | 0.88%   |
| MSI MS-7D25          | 2        | 0.88%   |
| MSI MS-7C52          | 2        | 0.88%   |
| MSI MS-7817          | 2        | 0.88%   |
| Lenovo V530S-07ICB   | 2        | 0.88%   |
| HP t620              | 2        | 0.88%   |
| HP ProDesk           | 2        | 0.88%   |
| HP Pavilion          | 2        | 0.88%   |
| Gigabyte B550        | 2        | 0.88%   |
| Gigabyte B450M       | 2        | 0.88%   |
| Fujitsu ESPRIMO      | 2        | 0.88%   |
| Dell XPS             | 2        | 0.88%   |
| ASUS P8H61-M         | 2        | 0.88%   |
| ASUS M5A97           | 2        | 0.88%   |
| Semp Toshiba STI     | 1        | 0.44%   |
| Pegatron FZ132AA-ABF | 1        | 0.44%   |
| Pegatron 20-b010     | 1        | 0.44%   |
| PCWare IPX1800E2     | 1        | 0.44%   |
| PCWare IPMH81G1      | 1        | 0.44%   |
| Packard Bell IMEDIA  | 1        | 0.44%   |
| MSI MS-7E07          | 1        | 0.44%   |
| MSI MS-7D40          | 1        | 0.44%   |
| MSI MS-7C91          | 1        | 0.44%   |
| MSI MS-7C84          | 1        | 0.44%   |
| MSI MS-7C56          | 1        | 0.44%   |
| MSI MS-7C37          | 1        | 0.44%   |
| MSI MS-7C08          | 1        | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2014 | 28       | 12.28%  |
| 2013 | 23       | 10.09%  |
| 2018 | 21       | 9.21%   |
| 2012 | 20       | 8.77%   |
| 2020 | 16       | 7.02%   |
| 2021 | 15       | 6.58%   |
| 2010 | 15       | 6.58%   |
| 2022 | 12       | 5.26%   |
| 2015 | 12       | 5.26%   |
| 2016 | 11       | 4.82%   |
| 2011 | 11       | 4.82%   |
| 2019 | 10       | 4.39%   |
| 2017 | 10       | 4.39%   |
| 2007 | 7        | 3.07%   |
| 2009 | 6        | 2.63%   |
| 2008 | 4        | 1.75%   |
| 2023 | 3        | 1.32%   |
| 2006 | 2        | 0.88%   |
| 2005 | 2        | 0.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 228      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 215      | 94.3%   |
| Enabled  | 13       | 5.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 228      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 49       | 21.3%   |
| 4.01-8.0    | 44       | 19.13%  |
| 3.01-4.0    | 41       | 17.83%  |
| 8.01-16.0   | 37       | 16.09%  |
| 32.01-64.0  | 34       | 14.78%  |
| 64.01-256.0 | 10       | 4.35%   |
| 24.01-32.0  | 8        | 3.48%   |
| 1.01-2.0    | 4        | 1.74%   |
| 2.01-3.0    | 3        | 1.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 90       | 36.29%  |
| 2.01-3.0   | 54       | 21.77%  |
| 4.01-8.0   | 37       | 14.92%  |
| 3.01-4.0   | 37       | 14.92%  |
| 0.51-1.0   | 15       | 6.05%   |
| 8.01-16.0  | 11       | 4.44%   |
| 16.01-24.0 | 3        | 1.21%   |
| 0.01-0.5   | 1        | 0.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 91       | 38.89%  |
| 2      | 68       | 29.06%  |
| 3      | 37       | 15.81%  |
| 4      | 17       | 7.26%   |
| 5      | 10       | 4.27%   |
| 6      | 5        | 2.14%   |
| 7      | 2        | 0.85%   |
| 0      | 2        | 0.85%   |
| 10     | 1        | 0.43%   |
| 9      | 1        | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 119      | 51.97%  |
| Yes       | 110      | 48.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 226      | 99.12%  |
| No        | 2        | 0.88%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 134      | 58.26%  |
| Yes       | 96       | 41.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 162      | 70.43%  |
| Yes       | 68       | 29.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 39       | 17.03%  |
| Germany      | 34       | 14.85%  |
| France       | 27       | 11.79%  |
| Italy        | 16       | 6.99%   |
| Brazil       | 15       | 6.55%   |
| Canada       | 11       | 4.8%    |
| Russia       | 7        | 3.06%   |
| Sweden       | 6        | 2.62%   |
| Poland       | 5        | 2.18%   |
| Netherlands  | 5        | 2.18%   |
| UK           | 4        | 1.75%   |
| Spain        | 4        | 1.75%   |
| Belgium      | 4        | 1.75%   |
| Australia    | 4        | 1.75%   |
| Argentina    | 4        | 1.75%   |
| Switzerland  | 3        | 1.31%   |
| Portugal     | 2        | 0.87%   |
| Norway       | 2        | 0.87%   |
| Mexico       | 2        | 0.87%   |
| India        | 2        | 0.87%   |
| Hungary      | 2        | 0.87%   |
| Greece       | 2        | 0.87%   |
| Finland      | 2        | 0.87%   |
| Czechia      | 2        | 0.87%   |
| Colombia     | 2        | 0.87%   |
| China        | 2        | 0.87%   |
| Belarus      | 2        | 0.87%   |
| Austria      | 2        | 0.87%   |
| Turkey       | 1        | 0.44%   |
| Taiwan       | 1        | 0.44%   |
| South Africa | 1        | 0.44%   |
| Slovenia     | 1        | 0.44%   |
| Serbia       | 1        | 0.44%   |
| Romania      | 1        | 0.44%   |
| Pakistan     | 1        | 0.44%   |
| New Zealand  | 1        | 0.44%   |
| Madagascar   | 1        | 0.44%   |
| Ireland      | 1        | 0.44%   |
| Iran         | 1        | 0.44%   |
| Indonesia    | 1        | 0.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Paris                | 5        | 2.11%   |
| Berlin               | 5        | 2.11%   |
| Sydney               | 3        | 1.27%   |
| Rio de Janeiro       | 3        | 1.27%   |
| Milan                | 3        | 1.27%   |
| Harrisonburg         | 3        | 1.27%   |
| Toul                 | 2        | 0.84%   |
| Toronto              | 2        | 0.84%   |
| Stuttgart            | 2        | 0.84%   |
| Springfield          | 2        | 0.84%   |
| Schwerte             | 2        | 0.84%   |
| Santiago de Cali     | 2        | 0.84%   |
| Rho                  | 2        | 0.84%   |
| Peterborough         | 2        | 0.84%   |
| Munich               | 2        | 0.84%   |
| Lisbon               | 2        | 0.84%   |
| Lake Placid          | 2        | 0.84%   |
| Helsinki             | 2        | 0.84%   |
| Hanover              | 2        | 0.84%   |
| Gdansk               | 2        | 0.84%   |
| Clermont-Ferrand     | 2        | 0.84%   |
| Budapest             | 2        | 0.84%   |
| Biella               | 2        | 0.84%   |
| Amsterdam            | 2        | 0.84%   |
| Żywiec              | 1        | 0.42%   |
| Yvoir                | 1        | 0.42%   |
| Wusterhausen         | 1        | 0.42%   |
| Wojnicz              | 1        | 0.42%   |
| Winkelhaid           | 1        | 0.42%   |
| Wilhelmshaven        | 1        | 0.42%   |
| Wiener Neustadt      | 1        | 0.42%   |
| White House          | 1        | 0.42%   |
| Wettringen           | 1        | 0.42%   |
| Washington           | 1        | 0.42%   |
| Waghausel            | 1        | 0.42%   |
| Waarder              | 1        | 0.42%   |
| Vohenstrauss         | 1        | 0.42%   |
| Vohburg an der Donau | 1        | 0.42%   |
| Vise                 | 1        | 0.42%   |
| Vicenza              | 1        | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 77       | 126    | 18.29%  |
| Samsung Electronics   | 64       | 85     | 15.2%   |
| Seagate               | 60       | 83     | 14.25%  |
| Kingston              | 30       | 39     | 7.13%   |
| Toshiba               | 25       | 28     | 5.94%   |
| Hitachi               | 21       | 32     | 4.99%   |
| Crucial               | 19       | 25     | 4.51%   |
| SanDisk               | 18       | 24     | 4.28%   |
| Unknown               | 8        | 11     | 1.9%    |
| Intel                 | 8        | 10     | 1.9%    |
| China                 | 8        | 8      | 1.9%    |
| HGST                  | 7        | 11     | 1.66%   |
| A-DATA Technology     | 7        | 7      | 1.66%   |
| PNY                   | 5        | 5      | 1.19%   |
| Gigabyte Technology   | 4        | 5      | 0.95%   |
| ASMT                  | 4        | 7      | 0.95%   |
| Patriot               | 3        | 3      | 0.71%   |
| Intenso               | 3        | 3      | 0.71%   |
| Hewlett-Packard       | 3        | 3      | 0.71%   |
| TEXTORM               | 2        | 2      | 0.48%   |
| SPCC                  | 2        | 2      | 0.48%   |
| SK hynix              | 2        | 2      | 0.48%   |
| Phison Electronics    | 2        | 4      | 0.48%   |
| PHD 3.0               | 2        | 2      | 0.48%   |
| OCZ                   | 2        | 2      | 0.48%   |
| Micron Technology     | 2        | 2      | 0.48%   |
| Maxtor                | 2        | 2      | 0.48%   |
| Lexar                 | 2        | 2      | 0.48%   |
| Corsair               | 2        | 2      | 0.48%   |
| XPG                   | 1        | 1      | 0.24%   |
| Veno                  | 1        | 1      | 0.24%   |
| Vaseky                | 1        | 1      | 0.24%   |
| USB3.0                | 1        | 2      | 0.24%   |
| TO Exter              | 1        | 2      | 0.24%   |
| Silicon Motion        | 1        | 1      | 0.24%   |
| Realtek Semiconductor | 1        | 1      | 0.24%   |
| Phison                | 1        | 8      | 0.24%   |
| Mushkin               | 1        | 1      | 0.24%   |
| MARVELL               | 1        | 1      | 0.24%   |
| LITEON                | 1        | 1      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 860 EVO 500GB        | 9        | 1.85%   |
| Crucial CT480BX500SSD1 480GB     | 7        | 1.44%   |
| Toshiba DT01ACA100 1TB           | 6        | 1.23%   |
| Kingston SA400S37240G 240GB SSD  | 6        | 1.23%   |
| Seagate ST500DM002-1BD142 500GB  | 5        | 1.03%   |
| Seagate ST1000DM003-1ER162 1TB   | 5        | 1.03%   |
| Kingston SA400S37480G 480GB SSD  | 5        | 1.03%   |
| Toshiba HDWD110 1TB              | 4        | 0.82%   |
| Toshiba DT01ACA200 2TB           | 4        | 0.82%   |
| Seagate ST2000DM008-2FR102 2TB   | 4        | 0.82%   |
| Kingston SV300S37A120G 120GB SSD | 4        | 0.82%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 3        | 0.62%   |
| Unknown SD/MMC/MS PRO 128GB      | 3        | 0.62%   |
| Seagate ST4000DM004-2CV104 4TB   | 3        | 0.62%   |
| Seagate ST1000DM003-1SB102 1TB   | 3        | 0.62%   |
| SanDisk SDSSDA240G 240GB         | 3        | 0.62%   |
| Samsung SSD 870 QVO 1TB          | 3        | 0.62%   |
| Samsung SSD 850 EVO 500GB        | 3        | 0.62%   |
| Samsung SSD 850 EVO 250GB        | 3        | 0.62%   |
| Samsung SSD 840 Series 120GB     | 3        | 0.62%   |
| Samsung SSD 840 EVO 250GB        | 3        | 0.62%   |
| Samsung HD250HJ 250GB            | 3        | 0.62%   |
| Kingston SUV400S37120G 120GB SSD | 3        | 0.62%   |
| Kingston SA2000M81000G 1TB       | 3        | 0.62%   |
| Hitachi HDS721010CLA332 1TB      | 3        | 0.62%   |
| WDC WDS250G2B0B-00YS70 250GB SSD | 2        | 0.41%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 2        | 0.41%   |
| WDC WD5000AADS-00S9B0 500GB      | 2        | 0.41%   |
| WDC WD3200AAKS-00L9A0 320GB      | 2        | 0.41%   |
| WDC WD20EARX-00PASB0 2TB         | 2        | 0.41%   |
| WDC WD20EARS-00MVWB0 2TB         | 2        | 0.41%   |
| WDC WD10EZRZ-00HTKB0 1TB         | 2        | 0.41%   |
| WDC WD10EZEX-08M2NA0 1TB         | 2        | 0.41%   |
| WDC WD10EZEX-00BBHA0 1TB         | 2        | 0.41%   |
| Toshiba DT01ACA050 500GB         | 2        | 0.41%   |
| TEXTORM BM5 240GB SSD            | 2        | 0.41%   |
| Seagate ST9500420AS 500GB        | 2        | 0.41%   |
| Seagate ST500LM000-1EJ162 500GB  | 2        | 0.41%   |
| Seagate ST4000VX007-2DT166 4TB   | 2        | 0.41%   |
| Seagate ST31000528AS 1TB         | 2        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 71       | 117    | 34.3%   |
| Seagate             | 60       | 81     | 28.99%  |
| Toshiba             | 22       | 25     | 10.63%  |
| Hitachi             | 21       | 32     | 10.14%  |
| Samsung Electronics | 11       | 15     | 5.31%   |
| HGST                | 7        | 11     | 3.38%   |
| ASMT                | 4        | 7      | 1.93%   |
| Unknown             | 3        | 4      | 1.45%   |
| USB3.0              | 1        | 2      | 0.48%   |
| TO Exter            | 1        | 2      | 0.48%   |
| Maxtor              | 1        | 1      | 0.48%   |
| MARVELL             | 1        | 1      | 0.48%   |
| LaCie               | 1        | 1      | 0.48%   |
| ICY BOX             | 1        | 1      | 0.48%   |
| Hewlett-Packard     | 1        | 1      | 0.48%   |
| Apple               | 1        | 1      | 0.48%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 39       | 50     | 25.16%  |
| Kingston            | 23       | 28     | 14.84%  |
| Crucial             | 18       | 24     | 11.61%  |
| SanDisk             | 13       | 17     | 8.39%   |
| WDC                 | 8        | 8      | 5.16%   |
| China               | 8        | 8      | 5.16%   |
| A-DATA Technology   | 6        | 6      | 3.87%   |
| PNY                 | 4        | 4      | 2.58%   |
| Toshiba             | 3        | 3      | 1.94%   |
| Patriot             | 3        | 3      | 1.94%   |
| Intenso             | 3        | 3      | 1.94%   |
| Intel               | 3        | 3      | 1.94%   |
| TEXTORM             | 2        | 2      | 1.29%   |
| SPCC                | 2        | 2      | 1.29%   |
| PHD 3.0             | 2        | 2      | 1.29%   |
| OCZ                 | 2        | 2      | 1.29%   |
| Hewlett-Packard     | 2        | 2      | 1.29%   |
| Gigabyte Technology | 2        | 2      | 1.29%   |
| Veno                | 1        | 1      | 0.65%   |
| Vaseky              | 1        | 1      | 0.65%   |
| Micron Technology   | 1        | 1      | 0.65%   |
| Maxtor              | 1        | 1      | 0.65%   |
| LITEON              | 1        | 1      | 0.65%   |
| Linux               | 1        | 1      | 0.65%   |
| Lexar               | 1        | 1      | 0.65%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.65%   |
| KingFast            | 1        | 1      | 0.65%   |
| KingDian            | 1        | 1      | 0.65%   |
| Dogfish             | 1        | 1      | 0.65%   |
| Corsair             | 1        | 1      | 0.65%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 156      | 302    | 44.7%   |
| SSD     | 132      | 181    | 37.82%  |
| NVMe    | 51       | 80     | 14.61%  |
| Unknown | 7        | 8      | 2.01%   |
| MMC     | 3        | 4      | 0.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 211      | 454    | 73.52%  |
| NVMe | 51       | 80     | 17.77%  |
| SAS  | 22       | 37     | 7.67%   |
| MMC  | 3        | 4      | 1.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 169      | 270    | 53.48%  |
| 0.51-1.0   | 80       | 117    | 25.32%  |
| 1.01-2.0   | 39       | 54     | 12.34%  |
| 3.01-4.0   | 18       | 28     | 5.7%    |
| 2.01-3.0   | 6        | 8      | 1.9%    |
| 10.01-20.0 | 2        | 3      | 0.63%   |
| 4.01-10.0  | 2        | 3      | 0.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 58       | 24.79%  |
| 251-500        | 47       | 20.09%  |
| 1001-2000      | 35       | 14.96%  |
| 501-1000       | 34       | 14.53%  |
| More than 3000 | 26       | 11.11%  |
| 2001-3000      | 16       | 6.84%   |
| 51-100         | 7        | 2.99%   |
| 1-20           | 6        | 2.56%   |
| 21-50          | 5        | 2.14%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 52       | 21.67%  |
| 251-500        | 37       | 15.42%  |
| 21-50          | 33       | 13.75%  |
| 101-250        | 33       | 13.75%  |
| 51-100         | 27       | 11.25%  |
| 1001-2000      | 18       | 7.5%    |
| 501-1000       | 17       | 7.08%   |
| 2001-3000      | 12       | 5%      |
| More than 3000 | 11       | 4.58%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Toshiba DT01ACA100 1TB            | 2        | 2      | 4.17%   |
| Seagate ST1000DM003-1ER162 1TB    | 2        | 2      | 4.17%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD  | 1        | 1      | 2.08%   |
| WDC WD5000BEVT-22A0RT0 500GB      | 1        | 1      | 2.08%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 1        | 1      | 2.08%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 1      | 2.08%   |
| WDC WD3200AAKS-75B3A0 320GB       | 1        | 2      | 2.08%   |
| WDC WD3200AAKS-00L9A0 320GB       | 1        | 1      | 2.08%   |
| WDC WD2500AAKS-00VSA0 250GB       | 1        | 1      | 2.08%   |
| WDC WD20EFRX-68AX9N0 2TB          | 1        | 1      | 2.08%   |
| WDC WD20EARS-00MVWB0 2TB          | 1        | 1      | 2.08%   |
| WDC WD2002FYPS-02W3B0 2TB         | 1        | 1      | 2.08%   |
| WDC WD10EZEX-60ZF5A0 1TB          | 1        | 1      | 2.08%   |
| WDC WD10EAVS-00D7B1 1TB           | 1        | 1      | 2.08%   |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1      | 2.08%   |
| WDC WD10EARS-003BB1 1TB           | 1        | 1      | 2.08%   |
| WDC WD1003FBYX-01Y7B1 1TB         | 1        | 1      | 2.08%   |
| Seagate ST9250410AS 250GB         | 1        | 1      | 2.08%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 2.08%   |
| Seagate ST4000DX001-1CE168 4TB    | 1        | 1      | 2.08%   |
| Seagate ST3750840AS 752GB         | 1        | 1      | 2.08%   |
| Seagate ST3500414CS 500GB         | 1        | 1      | 2.08%   |
| Seagate ST3250318AS 250GB         | 1        | 2      | 2.08%   |
| Seagate ST3250310AS 250GB         | 1        | 1      | 2.08%   |
| Seagate ST2000DM001-1CH164 2TB    | 1        | 1      | 2.08%   |
| Seagate ST18000NM000J-2TV103 18TB | 1        | 1      | 2.08%   |
| Seagate ST1000DM010-2EP102 1TB    | 1        | 1      | 2.08%   |
| Samsung Electronics SP2514N 250GB | 1        | 1      | 2.08%   |
| Samsung Electronics HM321HI 320GB | 1        | 2      | 2.08%   |
| Samsung Electronics HD753LJ 752GB | 1        | 1      | 2.08%   |
| Samsung Electronics HD250HJ 250GB | 1        | 1      | 2.08%   |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 2.08%   |
| PNY 69D03094-T 40GB SSD           | 1        | 1      | 2.08%   |
| Maxtor STM3160215AS 160GB         | 1        | 1      | 2.08%   |
| Intel SSDSC2BW120A4 120GB         | 1        | 1      | 2.08%   |
| ICY BOX IB-250StU3+BH15 2TB       | 1        | 1      | 2.08%   |
| Hitachi HTS723216L9A360 160GB     | 1        | 1      | 2.08%   |
| Hitachi HDS722540VLAT20 40GB      | 1        | 1      | 2.08%   |
| Hitachi HDS721010CLA332 1TB       | 1        | 1      | 2.08%   |
| Hitachi HCP725032GLA380 320GB     | 1        | 2      | 2.08%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 16     | 30.43%  |
| Seagate             | 12       | 13     | 26.09%  |
| Samsung Electronics | 4        | 6      | 8.7%    |
| Hitachi             | 4        | 5      | 8.7%    |
| Toshiba             | 2        | 2      | 4.35%   |
| PNY                 | 1        | 1      | 2.17%   |
| Maxtor              | 1        | 1      | 2.17%   |
| Intel               | 1        | 1      | 2.17%   |
| ICY BOX             | 1        | 1      | 2.17%   |
| HGST                | 1        | 3      | 2.17%   |
| Hewlett-Packard     | 1        | 1      | 2.17%   |
| Crucial             | 1        | 1      | 2.17%   |
| China               | 1        | 1      | 2.17%   |
| ASMT                | 1        | 4      | 2.17%   |
| A-DATA Technology   | 1        | 1      | 2.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 15     | 32.5%   |
| Seagate             | 12       | 13     | 30%     |
| Samsung Electronics | 4        | 6      | 10%     |
| Hitachi             | 4        | 5      | 10%     |
| Toshiba             | 2        | 2      | 5%      |
| Maxtor              | 1        | 1      | 2.5%    |
| ICY BOX             | 1        | 1      | 2.5%    |
| HGST                | 1        | 3      | 2.5%    |
| Hewlett-Packard     | 1        | 1      | 2.5%    |
| ASMT                | 1        | 4      | 2.5%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 35       | 51     | 87.5%   |
| SSD  | 4        | 5      | 10%     |
| NVMe | 1        | 1      | 2.5%    |

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
| Works    | 133      | 278    | 49.63%  |
| Detected | 96       | 240    | 35.82%  |
| Malfunc  | 39       | 57     | 14.55%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 150      | 48.08%  |
| AMD                          | 70       | 22.44%  |
| Samsung Electronics          | 17       | 5.45%   |
| JMicron Technology           | 10       | 3.21%   |
| ASMedia Technology           | 10       | 3.21%   |
| Kingston Technology Company  | 9        | 2.88%   |
| Phison Electronics           | 7        | 2.24%   |
| SanDisk                      | 6        | 1.92%   |
| Marvell Technology Group     | 6        | 1.92%   |
| Nvidia                       | 4        | 1.28%   |
| VIA Technologies             | 3        | 0.96%   |
| Silicon Image                | 3        | 0.96%   |
| Realtek Semiconductor        | 3        | 0.96%   |
| SK hynix                     | 2        | 0.64%   |
| Silicon Motion               | 2        | 0.64%   |
| Shenzhen Longsys Electronics | 1        | 0.32%   |
| Micron/Crucial Technology    | 1        | 0.32%   |
| Micron Technology            | 1        | 0.32%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.32%   |
| LSI Logic / Symbios Logic    | 1        | 0.32%   |
| KIOXIA                       | 1        | 0.32%   |
| INNOGRIT                     | 1        | 0.32%   |
| Broadcom / LSI               | 1        | 0.32%   |
| ADATA Technology             | 1        | 0.32%   |
| Adaptec                      | 1        | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 42       | 10.61%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 21       | 5.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12       | 3.03%   |
| AMD 400 Series Chipset SATA Controller                                                  | 12       | 3.03%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 11       | 2.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 11       | 2.78%   |
| AMD 500 Series Chipset SATA Controller                                                  | 11       | 2.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10       | 2.53%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 2.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9        | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 9        | 2.27%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 8        | 2.02%   |
| Intel SATA Controller [RAID mode]                                                       | 8        | 2.02%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 8        | 2.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 8        | 2.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 1.77%   |
| AMD FCH SATA Controller D                                                               | 7        | 1.77%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 1.52%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 5        | 1.26%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 1.26%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 1.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5        | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 1.26%   |
| Nvidia MCP61 SATA Controller                                                            | 4        | 1.01%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 4        | 1.01%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 1.01%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 1.01%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4        | 1.01%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 1.01%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                        | 3        | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 0.76%   |
| Nvidia MCP61 IDE                                                                        | 3        | 0.76%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 0.76%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 3        | 0.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3        | 0.76%   |
| Intel 700 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.76%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 3        | 0.76%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3        | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 188      | 60.65%  |
| NVMe | 51       | 16.45%  |
| IDE  | 47       | 15.16%  |
| RAID | 20       | 6.45%   |
| SAS  | 3        | 0.97%   |
| SCSI | 1        | 0.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 152      | 66.67%  |
| AMD    | 76       | 33.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 6        | 2.62%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 1.75%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 3        | 1.31%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 1.31%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 3        | 1.31%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 1.31%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3        | 1.31%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 1.31%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 3        | 1.31%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 3        | 1.31%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 3        | 1.31%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3        | 1.31%   |
| AMD Phenom II X4 955 Processor              | 3        | 1.31%   |
| AMD FX-6300 Six-Core Processor              | 3        | 1.31%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz         | 2        | 0.87%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2        | 0.87%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 0.87%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 2        | 0.87%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 0.87%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 0.87%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2        | 0.87%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 0.87%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 2        | 0.87%   |
| Intel Core i5-4590S CPU @ 3.00GHz           | 2        | 0.87%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 2        | 0.87%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 0.87%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 0.87%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 2        | 0.87%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 0.87%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 0.87%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 2        | 0.87%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 0.87%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 2        | 0.87%   |
| Intel 13th Gen Core i7-13700KF              | 2        | 0.87%   |
| Intel 13th Gen Core i5-13600K               | 2        | 0.87%   |
| Intel 12th Gen Core i7-12700                | 2        | 0.87%   |
| Intel 12th Gen Core i3-12100F               | 2        | 0.87%   |
| Intel 12th Gen Core i3-12100                | 2        | 0.87%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 2        | 0.87%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 2        | 0.87%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 44       | 19.21%  |
| Intel Core i7           | 27       | 11.79%  |
| AMD Ryzen 5             | 24       | 10.48%  |
| Intel Core i3           | 22       | 9.61%   |
| Intel Celeron           | 15       | 6.55%   |
| Other                   | 14       | 6.11%   |
| AMD Ryzen 7             | 10       | 4.37%   |
| Intel Xeon              | 9        | 3.93%   |
| Intel Core 2 Quad       | 6        | 2.62%   |
| Intel Core 2 Duo        | 6        | 2.62%   |
| AMD FX                  | 6        | 2.62%   |
| AMD Ryzen 9             | 5        | 2.18%   |
| AMD A8                  | 5        | 2.18%   |
| AMD Phenom II X4        | 4        | 1.75%   |
| Intel Pentium Dual-Core | 3        | 1.31%   |
| Intel Pentium           | 3        | 1.31%   |
| AMD Ryzen 3             | 3        | 1.31%   |
| AMD Athlon II X2        | 3        | 1.31%   |
| Intel Pentium 4         | 2        | 0.87%   |
| AMD GX                  | 2        | 0.87%   |
| AMD Athlon 64 X2        | 2        | 0.87%   |
| AMD A6                  | 2        | 0.87%   |
| AMD A10                 | 2        | 0.87%   |
| Intel Atom              | 1        | 0.44%   |
| AMD Turion II Neo       | 1        | 0.44%   |
| AMD Sempron             | 1        | 0.44%   |
| AMD Ryzen 7 PRO         | 1        | 0.44%   |
| AMD Ryzen 5 PRO         | 1        | 0.44%   |
| AMD Phenom II X6        | 1        | 0.44%   |
| AMD E1                  | 1        | 0.44%   |
| AMD Athlon X4           | 1        | 0.44%   |
| AMD Athlon II           | 1        | 0.44%   |
| AMD Athlon              | 1        | 0.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 100      | 43.48%  |
| 2      | 57       | 24.78%  |
| 6      | 34       | 14.78%  |
| 8      | 15       | 6.52%   |
| 1      | 6        | 2.61%   |
| 12     | 5        | 2.17%   |
| 16     | 4        | 1.74%   |
| 10     | 3        | 1.3%    |
| 3      | 3        | 1.3%    |
| 14     | 2        | 0.87%   |
| 24     | 1        | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 228      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 131      | 57.46%  |
| 1      | 97       | 42.54%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 228      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 103      | 44.59%  |
| 0x306c3    | 14       | 6.06%   |
| 0x306a9    | 10       | 4.33%   |
| 0x206a7    | 8        | 3.46%   |
| 0x1067a    | 5        | 2.16%   |
| 0x08701021 | 5        | 2.16%   |
| 0x0800820d | 5        | 2.16%   |
| 0x06000852 | 5        | 2.16%   |
| 0x010000c8 | 5        | 2.16%   |
| 0x906ea    | 4        | 1.73%   |
| 0x506e3    | 4        | 1.73%   |
| 0xb0671    | 3        | 1.3%    |
| 0x90672    | 3        | 1.3%    |
| 0x306e4    | 3        | 1.3%    |
| 0x106e5    | 3        | 1.3%    |
| 0x08108109 | 3        | 1.3%    |
| 0x906e9    | 2        | 0.87%   |
| 0x406c3    | 2        | 0.87%   |
| 0x206d7    | 2        | 0.87%   |
| 0x10676    | 2        | 0.87%   |
| 0x0a201016 | 2        | 0.87%   |
| 0x08701013 | 2        | 0.87%   |
| 0x0700010f | 2        | 0.87%   |
| 0x010000c7 | 2        | 0.87%   |
| 0xa0655    | 1        | 0.43%   |
| 0xa0653    | 1        | 0.43%   |
| 0x906ed    | 1        | 0.43%   |
| 0x906eb    | 1        | 0.43%   |
| 0x706a1    | 1        | 0.43%   |
| 0x6fb      | 1        | 0.43%   |
| 0x506c9    | 1        | 0.43%   |
| 0x406c4    | 1        | 0.43%   |
| 0x306f2    | 1        | 0.43%   |
| 0x30679    | 1        | 0.43%   |
| 0x30678    | 1        | 0.43%   |
| 0x206d6    | 1        | 0.43%   |
| 0x206c2    | 1        | 0.43%   |
| 0x20652    | 1        | 0.43%   |
| 0x106ca    | 1        | 0.43%   |
| 0x10677    | 1        | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 29       | 12.66%  |
| SandyBridge      | 20       | 8.73%   |
| KabyLake         | 19       | 8.3%    |
| IvyBridge        | 19       | 8.3%    |
| Zen 2            | 17       | 7.42%   |
| Zen+             | 11       | 4.8%    |
| Piledriver       | 11       | 4.8%    |
| Penryn           | 11       | 4.8%    |
| Unknown          | 11       | 4.8%    |
| K10              | 10       | 4.37%   |
| Zen 3            | 9        | 3.93%   |
| Skylake          | 7        | 3.06%   |
| CometLake        | 7        | 3.06%   |
| Silvermont       | 6        | 2.62%   |
| Alderlake Hybrid | 6        | 2.62%   |
| Zen              | 5        | 2.18%   |
| Nehalem          | 5        | 2.18%   |
| Core             | 5        | 2.18%   |
| Westmere         | 3        | 1.31%   |
| Jaguar           | 3        | 1.31%   |
| Steamroller      | 2        | 0.87%   |
| NetBurst         | 2        | 0.87%   |
| K8 Hammer        | 2        | 0.87%   |
| Excavator        | 2        | 0.87%   |
| Broadwell        | 2        | 0.87%   |
| K10 Llano        | 1        | 0.44%   |
| Goldmont plus    | 1        | 0.44%   |
| Goldmont         | 1        | 0.44%   |
| Bonnell          | 1        | 0.44%   |
| Bobcat           | 1        | 0.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 95       | 38.31%  |
| Nvidia | 87       | 35.08%  |
| AMD    | 66       | 26.61%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 17       | 6.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13       | 5.1%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 11       | 4.31%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 8        | 3.14%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7        | 2.75%   |
| Intel HD Graphics 530                                                                    | 7        | 2.75%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6        | 2.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6        | 2.35%   |
| Intel HD Graphics 630                                                                    | 5        | 1.96%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5        | 1.96%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 4        | 1.57%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4        | 1.57%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 3        | 1.18%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                               | 3        | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3        | 1.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3        | 1.18%   |
| Intel AlderLake-S GT1                                                                    | 3        | 1.18%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                                | 3        | 1.18%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3        | 1.18%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3        | 1.18%   |
| AMD RS780L [Radeon 3000]                                                                 | 3        | 1.18%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3        | 1.18%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3        | 1.18%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3        | 1.18%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 3        | 1.18%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 2        | 0.78%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 2        | 0.78%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 2        | 0.78%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 0.78%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 0.78%   |
| Nvidia GM107 [GeForce GTX 745]                                                           | 2        | 0.78%   |
| Nvidia GK107GL [Quadro K2000]                                                            | 2        | 0.78%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 2        | 0.78%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 0.78%   |
| Intel DG2 [Arc A770]                                                                     | 2        | 0.78%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2        | 0.78%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2        | 0.78%   |
| AMD RS880 [Radeon HD 4250]                                                               | 2        | 0.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2        | 0.78%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 2        | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 79       | 34.65%  |
| 1 x Nvidia     | 77       | 33.77%  |
| 1 x AMD        | 54       | 23.68%  |
| 2 x AMD        | 5        | 2.19%   |
| Intel + Nvidia | 5        | 2.19%   |
| AMD + Nvidia   | 4        | 1.75%   |
| Intel + AMD    | 3        | 1.32%   |
| 2 x Nvidia     | 1        | 0.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 165      | 71.74%  |
| Proprietary | 55       | 23.91%  |
| Unknown     | 10       | 4.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 136      | 59.13%  |
| 1.01-2.0   | 24       | 10.43%  |
| 0.51-1.0   | 22       | 9.57%   |
| 0.01-0.5   | 15       | 6.52%   |
| 3.01-4.0   | 12       | 5.22%   |
| 7.01-8.0   | 8        | 3.48%   |
| 8.01-16.0  | 6        | 2.61%   |
| 5.01-6.0   | 5        | 2.17%   |
| 2.01-3.0   | 2        | 0.87%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 35       | 14.64%  |
| Dell                 | 35       | 14.64%  |
| Hewlett-Packard      | 23       | 9.62%   |
| Goldstar             | 21       | 8.79%   |
| AOC                  | 18       | 7.53%   |
| Acer                 | 13       | 5.44%   |
| Ancor Communications | 11       | 4.6%    |
| BenQ                 | 10       | 4.18%   |
| Philips              | 9        | 3.77%   |
| Iiyama               | 8        | 3.35%   |
| ViewSonic            | 6        | 2.51%   |
| Fujitsu Siemens      | 4        | 1.67%   |
| Lenovo               | 3        | 1.26%   |
| ASUSTek Computer     | 3        | 1.26%   |
| Unknown              | 2        | 0.84%   |
| RTK                  | 2        | 0.84%   |
| HannStar             | 2        | 0.84%   |
| Eizo                 | 2        | 0.84%   |
| Denver               | 2        | 0.84%   |
| Unknown              | 2        | 0.84%   |
| ___                  | 1        | 0.42%   |
| Vestel Elektronik    | 1        | 0.42%   |
| Unknown (AAA)        | 1        | 0.42%   |
| UGD                  | 1        | 0.42%   |
| Toshiba              | 1        | 0.42%   |
| TEO                  | 1        | 0.42%   |
| Tech Concepts        | 1        | 0.42%   |
| TCL                  | 1        | 0.42%   |
| Sony                 | 1        | 0.42%   |
| SNC                  | 1        | 0.42%   |
| Sceptre Tech         | 1        | 0.42%   |
| RGT                  | 1        | 0.42%   |
| Packard Bell         | 1        | 0.42%   |
| NEC Computers        | 1        | 0.42%   |
| Mi                   | 1        | 0.42%   |
| MAG                  | 1        | 0.42%   |
| LG Electronics       | 1        | 0.42%   |
| JRY                  | 1        | 0.42%   |
| JINGLITAI            | 1        | 0.42%   |
| IBM                  | 1        | 0.42%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 3        | 1.18%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch             | 3        | 1.18%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch               | 2        | 0.78%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch               | 2        | 0.78%   |
| Philips 170S PHL082B 1280x1024 338x270mm 17.0-inch                   | 2        | 0.78%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                  | 2        | 0.78%   |
| Hewlett-Packard 2309 HWP2821 1920x1080 510x287mm 23.0-inch           | 2        | 0.78%   |
| HannStar HL205DPB HSD62E0 1600x900 432x240mm 19.5-inch               | 2        | 0.78%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 2        | 0.78%   |
| Dell U3011 DEL4065 2560x1600 641x401mm 29.8-inch                     | 2        | 0.78%   |
| Dell 2001FP DELA008 1600x1200 367x275mm 18.1-inch                    | 2        | 0.78%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                   | 2        | 0.78%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                      | 2        | 0.78%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 2        | 0.78%   |
| Unknown                                                              | 2        | 0.78%   |
| ___ LCD Monitor ___1BBC 1920x540 140x90mm 6.6-inch                   | 1        | 0.39%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch        | 1        | 0.39%   |
| ViewSonic VX3276-UHD VSC5138 3840x2160 697x392mm 31.5-inch           | 1        | 0.39%   |
| ViewSonic VP2365 SERIES VSC7C28 1920x1080 509x286mm 23.0-inch        | 1        | 0.39%   |
| ViewSonic VA1948 SERIES VSCE827 1440x900 408x255mm 18.9-inch         | 1        | 0.39%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch   | 1        | 0.39%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                | 1        | 0.39%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1        | 0.39%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch             | 1        | 0.39%   |
| UGD CD220F (H) UGD2210 1920x1080 527x296mm 23.8-inch                 | 1        | 0.39%   |
| Toshiba TV TSB0109 1920x1080                                         | 1        | 0.39%   |
| TEO TL765 TEO6700 1280x1024 338x270mm 17.0-inch                      | 1        | 0.39%   |
| Tech Concepts LCD Monitor 32S327 1280x720                            | 1        | 0.39%   |
| TCL TCL TCL0030 1600x1200 708x398mm 32.0-inch                        | 1        | 0.39%   |
| Sony TV SNYAB03 1920x1080                                            | 1        | 0.39%   |
| SNC SKP_E20-27 SNC2700 2560x1440 597x336mm 27.0-inch                 | 1        | 0.39%   |
| Sceptre Tech Sceptre Y27 SPT0AB9 2560x1440 597x336mm 27.0-inch       | 1        | 0.39%   |
| Samsung Electronics SyncMaster SAM0653 1920x1080                     | 1        | 0.39%   |
| Samsung Electronics SyncMaster SAM05C4 1920x1080 510x287mm 23.0-inch | 1        | 0.39%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch  | 1        | 0.39%   |
| Samsung Electronics SyncMaster SAM0577 1920x1080 476x268mm 21.5-inch | 1        | 0.39%   |
| Samsung Electronics SyncMaster SAM03E3 1680x1050 433x271mm 20.1-inch | 1        | 0.39%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch  | 1        | 0.39%   |
| Samsung Electronics SyncMaster SAM0273 1440x900 410x257mm 19.1-inch  | 1        | 0.39%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 408x306mm 20.1-inch | 1        | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 105      | 44.12%  |
| 1280x1024 (SXGA)   | 17       | 7.14%   |
| 2560x1440 (QHD)    | 16       | 6.72%   |
| 1366x768 (WXGA)    | 16       | 6.72%   |
| 3840x2160 (4K)     | 12       | 5.04%   |
| 1600x900 (HD+)     | 12       | 5.04%   |
| 1440x900 (WXGA+)   | 12       | 5.04%   |
| 1680x1050 (WSXGA+) | 9        | 3.78%   |
| 1024x768 (XGA)     | 6        | 2.52%   |
| 1600x1200          | 5        | 2.1%    |
| 2560x1600          | 4        | 1.68%   |
| 1920x1200 (WUXGA)  | 4        | 1.68%   |
| 1360x768           | 4        | 1.68%   |
| 3840x1080          | 3        | 1.26%   |
| 3440x1440          | 3        | 1.26%   |
| 2560x1080          | 3        | 1.26%   |
| 3840x1600          | 2        | 0.84%   |
| Unknown            | 2        | 0.84%   |
| 2288x1287          | 1        | 0.42%   |
| 1920x540           | 1        | 0.42%   |
| 1280x720 (HD)      | 1        | 0.42%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 35       | 14.34%  |
| 23      | 33       | 13.52%  |
| 27      | 26       | 10.66%  |
| 21      | 21       | 8.61%   |
| 19      | 21       | 8.61%   |
| 18      | 18       | 7.38%   |
| 20      | 14       | 5.74%   |
| Unknown | 12       | 4.92%   |
| 17      | 9        | 3.69%   |
| 15      | 7        | 2.87%   |
| 34      | 6        | 2.46%   |
| 31      | 6        | 2.46%   |
| 22      | 6        | 2.46%   |
| 40      | 5        | 2.05%   |
| 29      | 3        | 1.23%   |
| 25      | 3        | 1.23%   |
| 72      | 2        | 0.82%   |
| 49      | 2        | 0.82%   |
| 37      | 2        | 0.82%   |
| 32      | 2        | 0.82%   |
| 26      | 2        | 0.82%   |
| 14      | 2        | 0.82%   |
| 142     | 1        | 0.41%   |
| 84      | 1        | 0.41%   |
| 54      | 1        | 0.41%   |
| 48      | 1        | 0.41%   |
| 30      | 1        | 0.41%   |
| 28      | 1        | 0.41%   |
| 6       | 1        | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 90       | 38.14%  |
| 401-500        | 74       | 31.36%  |
| 301-350        | 17       | 7.2%    |
| 601-700        | 13       | 5.51%   |
| Unknown        | 12       | 5.08%   |
| 701-800        | 8        | 3.39%   |
| 801-900        | 7        | 2.97%   |
| 351-400        | 5        | 2.12%   |
| 1001-1500      | 4        | 1.69%   |
| 1501-2000      | 3        | 1.27%   |
| More than 2000 | 1        | 0.42%   |
| 201-300        | 1        | 0.42%   |
| 101-200        | 1        | 0.42%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 147      | 65.63%  |
| 16/10   | 31       | 13.84%  |
| 5/4     | 13       | 5.8%    |
| 4/3     | 10       | 4.46%   |
| Unknown | 10       | 4.46%   |
| 21/9    | 8        | 3.57%   |
| 32/9    | 2        | 0.89%   |
| 6/5     | 1        | 0.45%   |
| 3/2     | 1        | 0.45%   |
| 1.00    | 1        | 0.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 76       | 31.67%  |
| 151-200        | 45       | 18.75%  |
| 301-350        | 27       | 11.25%  |
| 141-150        | 26       | 10.83%  |
| 351-500        | 19       | 7.92%   |
| Unknown        | 12       | 5%      |
| 251-300        | 11       | 4.58%   |
| 101-110        | 8        | 3.33%   |
| 501-1000       | 8        | 3.33%   |
| More than 1000 | 6        | 2.5%    |
| 81-90          | 1        | 0.42%   |
| 1-40           | 1        | 0.42%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 151      | 67.71%  |
| 101-120       | 43       | 19.28%  |
| Unknown       | 12       | 5.38%   |
| 121-160       | 8        | 3.59%   |
| 1-50          | 7        | 3.14%   |
| More than 240 | 1        | 0.45%   |
| 161-240       | 1        | 0.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 175      | 76.42%  |
| 2     | 34       | 14.85%  |
| 0     | 13       | 5.68%   |
| 3     | 7        | 3.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 155      | 47.84%  |
| Intel                           | 96       | 29.63%  |
| Qualcomm Atheros                | 20       | 6.17%   |
| Ralink Technology               | 9        | 2.78%   |
| TP-Link                         | 4        | 1.23%   |
| Nvidia                          | 4        | 1.23%   |
| Broadcom Limited                | 4        | 1.23%   |
| Broadcom                        | 4        | 1.23%   |
| Samsung Electronics             | 2        | 0.62%   |
| Ralink                          | 2        | 0.62%   |
| NetGear                         | 2        | 0.62%   |
| MediaTek                        | 2        | 0.62%   |
| Marvell Technology Group        | 2        | 0.62%   |
| D-Link System                   | 2        | 0.62%   |
| ASIX Electronics                | 2        | 0.62%   |
| ZyDAS                           | 1        | 0.31%   |
| Zoom Telephonics                | 1        | 0.31%   |
| TRENDnet                        | 1        | 0.31%   |
| Qualcomm Atheros Communications | 1        | 0.31%   |
| OPPO Electronics                | 1        | 0.31%   |
| MicroPython                     | 1        | 0.31%   |
| Microchip Technology            | 1        | 0.31%   |
| Mellanox Technologies           | 1        | 0.31%   |
| Linksys                         | 1        | 0.31%   |
| Dell                            | 1        | 0.31%   |
| D-Link                          | 1        | 0.31%   |
| Belkin Components               | 1        | 0.31%   |
| ASUSTek Computer                | 1        | 0.31%   |
| Aquantia                        | 1        | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 118      | 32.24%  |
| Realtek RTL8125 2.5GbE Controller                                 | 19       | 5.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12       | 3.28%   |
| Intel I211 Gigabit Network Connection                             | 11       | 3.01%   |
| Intel Ethernet Connection (2) I219-V                              | 9        | 2.46%   |
| Intel Wi-Fi 6 AX200                                               | 8        | 2.19%   |
| Intel Ethernet Controller I225-V                                  | 7        | 1.91%   |
| Intel Ethernet Connection I217-LM                                 | 7        | 1.91%   |
| Ralink MT7601U Wireless Adapter                                   | 6        | 1.64%   |
| Intel Ethernet Connection I217-V                                  | 6        | 1.64%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 1.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4        | 1.09%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4        | 1.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 1.09%   |
| Realtek 802.11ac NIC                                              | 4        | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4        | 1.09%   |
| Nvidia MCP61 Ethernet                                             | 4        | 1.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4        | 1.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 0.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3        | 0.82%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.82%   |
| Intel Wireless 7260                                               | 3        | 0.82%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3        | 0.82%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 0.82%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 0.82%   |
| Intel Ethernet Connection (14) I219-V                             | 3        | 0.82%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 2        | 0.55%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.55%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.55%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2        | 0.55%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 2        | 0.55%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.55%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2        | 0.55%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2        | 0.55%   |
| Intel Wireless 3160                                               | 2        | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.55%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 0.55%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 29       | 29%     |
| Intel                           | 27       | 27%     |
| Qualcomm Atheros                | 15       | 15%     |
| Ralink Technology               | 9        | 9%      |
| TP-Link                         | 4        | 4%      |
| Ralink                          | 2        | 2%      |
| NetGear                         | 2        | 2%      |
| MediaTek                        | 2        | 2%      |
| ZyDAS                           | 1        | 1%      |
| TRENDnet                        | 1        | 1%      |
| Qualcomm Atheros Communications | 1        | 1%      |
| Dell                            | 1        | 1%      |
| D-Link System                   | 1        | 1%      |
| D-Link                          | 1        | 1%      |
| Broadcom Limited                | 1        | 1%      |
| Broadcom                        | 1        | 1%      |
| Belkin Components               | 1        | 1%      |
| ASUSTek Computer                | 1        | 1%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 8        | 8%      |
| Ralink MT7601U Wireless Adapter                                            | 6        | 6%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 4        | 4%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 4        | 4%      |
| Realtek 802.11ac NIC                                                       | 4        | 4%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 4        | 4%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 4        | 4%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 3        | 3%      |
| Intel Wireless 7260                                                        | 3        | 3%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 3        | 3%      |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                | 2        | 2%      |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                   | 2        | 2%      |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 2        | 2%      |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 2        | 2%      |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                      | 2        | 2%      |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 2        | 2%      |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 2        | 2%      |
| Intel Wireless 3160                                                        | 2        | 2%      |
| Intel Alder Lake-S PCH CNVi WiFi                                           | 2        | 2%      |
| Intel 700 Series Chipset Family Wi-Fi                                      | 2        | 2%      |
| ZyDAS ZD1211B 802.11g                                                      | 1        | 1%      |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU] | 1        | 1%      |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                        | 1        | 1%      |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                               | 1        | 1%      |
| TP-Link Archer T4U ver.3                                                   | 1        | 1%      |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 1        | 1%      |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                    | 1        | 1%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1        | 1%      |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                 | 1        | 1%      |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 1        | 1%      |
| Realtek RTL8188EE Wireless Network Adapter                                 | 1        | 1%      |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                    | 1        | 1%      |
| Realtek RTL8187 Wireless Adapter                                           | 1        | 1%      |
| Ralink RT5572 Wireless Adapter                                             | 1        | 1%      |
| Ralink RT2770 Wireless Adapter                                             | 1        | 1%      |
| Ralink RT2501/RT2573 Wireless Adapter                                      | 1        | 1%      |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                     | 1        | 1%      |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                  | 1        | 1%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 1        | 1%      |
| Qualcomm Atheros AR9271 802.11n                                            | 1        | 1%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 144      | 57.14%  |
| Intel                    | 83       | 32.94%  |
| Qualcomm Atheros         | 6        | 2.38%   |
| Nvidia                   | 4        | 1.59%   |
| Broadcom Limited         | 3        | 1.19%   |
| Broadcom                 | 3        | 1.19%   |
| Marvell Technology Group | 2        | 0.79%   |
| ASIX Electronics         | 2        | 0.79%   |
| Samsung Electronics      | 1        | 0.4%    |
| OPPO Electronics         | 1        | 0.4%    |
| Linksys                  | 1        | 0.4%    |
| D-Link System            | 1        | 0.4%    |
| Aquantia                 | 1        | 0.4%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 118      | 45.21%  |
| Realtek RTL8125 2.5GbE Controller                                 | 19       | 7.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12       | 4.6%    |
| Intel I211 Gigabit Network Connection                             | 11       | 4.21%   |
| Intel Ethernet Connection (2) I219-V                              | 9        | 3.45%   |
| Intel Ethernet Controller I225-V                                  | 7        | 2.68%   |
| Intel Ethernet Connection I217-LM                                 | 7        | 2.68%   |
| Intel Ethernet Connection I217-V                                  | 6        | 2.3%    |
| Intel 82579V Gigabit Network Connection                           | 5        | 1.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 1.53%   |
| Nvidia MCP61 Ethernet                                             | 4        | 1.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 1.15%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 1.15%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 1.15%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.15%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.15%   |
| Intel Ethernet Connection (14) I219-V                             | 3        | 1.15%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.77%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.77%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 0.77%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 0.77%   |
| Intel 82578DC Gigabit Network Connection                          | 2        | 0.77%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 0.77%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 2        | 0.77%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2        | 0.77%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.38%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 0.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.38%   |
| OPPO RMX3623                                                      | 1        | 0.38%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.38%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.38%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.38%   |
| Linksys Gigabit Ethernet Adapter                                  | 1        | 0.38%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.38%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.38%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 0.38%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.38%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 0.38%   |
| Intel 82541GI Gigabit Ethernet Controller                         | 1        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 226      | 69.33%  |
| WiFi     | 95       | 29.14%  |
| Modem    | 4        | 1.23%   |
| Unknown  | 1        | 0.31%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 183      | 75.31%  |
| WiFi     | 60       | 24.69%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 148      | 64.35%  |
| 2     | 69       | 30%     |
| 3     | 9        | 3.91%   |
| 4     | 2        | 0.87%   |
| 0     | 2        | 0.87%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 153      | 65.95%  |
| Yes  | 79       | 34.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 25       | 35.71%  |
| Cambridge Silicon Radio         | 19       | 27.14%  |
| Realtek Semiconductor           | 8        | 11.43%  |
| Qualcomm Atheros Communications | 4        | 5.71%   |
| Broadcom                        | 4        | 5.71%   |
| IMC Networks                    | 3        | 4.29%   |
| TP-Link                         | 2        | 2.86%   |
| MediaTek                        | 2        | 2.86%   |
| Lite-On Technology              | 1        | 1.43%   |
| Fujitsu                         | 1        | 1.43%   |
| ASUSTek Computer                | 1        | 1.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 19       | 27.14%  |
| Intel AX200 Bluetooth                               | 8        | 11.43%  |
| Realtek Bluetooth Radio                             | 6        | 8.57%   |
| Intel Bluetooth wireless interface                  | 6        | 8.57%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4        | 5.71%   |
| IMC Networks Bluetooth Radio                        | 3        | 4.29%   |
| TP-Link TP-Cdj+ UB5A Adapter                        | 2        | 2.86%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 2.86%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2        | 2.86%   |
| MediaTek Wireless_Device                            | 2        | 2.86%   |
| Intel Bluetooth Device                              | 2        | 2.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 2.86%   |
| Intel AX201 Bluetooth                               | 2        | 2.86%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 2.86%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 1.43%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 1.43%   |
| Lite-On Bluetooth Device                            | 1        | 1.43%   |
| Intel AX210 Bluetooth                               | 1        | 1.43%   |
| Fujitsu Bluetooth Device                            | 1        | 1.43%   |
| Broadcom BCM2210 Bluetooth                          | 1        | 1.43%   |
| Broadcom BCM20702A0                                 | 1        | 1.43%   |
| ASUS ASUS USB-BT500                                 | 1        | 1.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 152      | 42.46%  |
| AMD                                          | 83       | 23.18%  |
| Nvidia                                       | 76       | 21.23%  |
| Creative Labs                                | 8        | 2.23%   |
| C-Media Electronics                          | 5        | 1.4%    |
| Texas Instruments                            | 2        | 0.56%   |
| Tenx Technology                              | 2        | 0.56%   |
| SAVITECH                                     | 2        | 0.56%   |
| Medeli Electronics                           | 2        | 0.56%   |
| Logitech                                     | 2        | 0.56%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.28%   |
| VIA Technologies                             | 1        | 0.28%   |
| STMicroelectronics                           | 1        | 0.28%   |
| Sennheiser Communications                    | 1        | 0.28%   |
| Samson Technologies                          | 1        | 0.28%   |
| Roland                                       | 1        | 0.28%   |
| Reloop                                       | 1        | 0.28%   |
| Razer USA                                    | 1        | 0.28%   |
| PreSonus Audio Electronics                   | 1        | 0.28%   |
| Micro Star International                     | 1        | 0.28%   |
| MAG Technology                               | 1        | 0.28%   |
| M-Audio                                      | 1        | 0.28%   |
| Lenovo                                       | 1        | 0.28%   |
| Kingston Technology                          | 1        | 0.28%   |
| JMTek                                        | 1        | 0.28%   |
| Hewlett-Packard                              | 1        | 0.28%   |
| GN Netcom                                    | 1        | 0.28%   |
| FiiO Electronics Technology                  | 1        | 0.28%   |
| DSEA A/S                                     | 1        | 0.28%   |
| Creative Technology                          | 1        | 0.28%   |
| Corsair                                      | 1        | 0.28%   |
| BR25                                         | 1        | 0.28%   |
| BEHRINGER International                      | 1        | 0.28%   |
| ASUSTek Computer                             | 1        | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 23       | 5.5%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 18       | 4.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 17       | 4.07%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17       | 4.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 17       | 4.07%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 15       | 3.59%   |
| AMD FCH Azalia Controller                                                                         | 14       | 3.35%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 14       | 3.35%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 13       | 3.11%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 10       | 2.39%   |
| Intel 200 Series PCH HD Audio                                                                     | 10       | 2.39%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 9        | 2.15%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8        | 1.91%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8        | 1.91%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 8        | 1.91%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7        | 1.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7        | 1.67%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 7        | 1.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6        | 1.44%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6        | 1.44%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 6        | 1.44%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 5        | 1.2%    |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 5        | 1.2%    |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 5        | 1.2%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 5        | 1.2%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5        | 1.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5        | 1.2%    |
| AMD Kabini HDMI/DP Audio                                                                          | 5        | 1.2%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 4        | 0.96%   |
| Nvidia MCP61 High Definition Audio                                                                | 4        | 0.96%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 4        | 0.96%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4        | 0.96%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 4        | 0.96%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4        | 0.96%   |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 4        | 0.96%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3        | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3        | 0.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3        | 0.72%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1                                  | 3        | 0.72%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 35       | 18.42%  |
| Unknown             | 27       | 14.21%  |
| Samsung Electronics | 23       | 12.11%  |
| SK hynix            | 21       | 11.05%  |
| Corsair             | 19       | 10%     |
| Crucial             | 18       | 9.47%   |
| G.Skill             | 12       | 6.32%   |
| Nanya Technology    | 6        | 3.16%   |
| Ramaxel Technology  | 5        | 2.63%   |
| Micron Technology   | 3        | 1.58%   |
| Elpida              | 3        | 1.58%   |
| A-DATA Technology   | 3        | 1.58%   |
| Unknown             | 3        | 1.58%   |
| Unknown (ABCD)      | 2        | 1.05%   |
| V-Color             | 1        | 0.53%   |
| Unknown (AB)        | 1        | 0.53%   |
| Unknown (0x0B15)    | 1        | 0.53%   |
| Transcend           | 1        | 0.53%   |
| Timetec             | 1        | 0.53%   |
| Silicon Power       | 1        | 0.53%   |
| Qumo                | 1        | 0.53%   |
| GLOWAY              | 1        | 0.53%   |
| GIGA-BYTE           | 1        | 0.53%   |
| ASint Technology    | 1        | 0.53%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 3        | 1.48%   |
| Unknown RAM Module 2GB DIMM SDRAM                                 | 3        | 1.48%   |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s                | 3        | 1.48%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s             | 3        | 1.48%   |
| Unknown                                                           | 3        | 1.48%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                         | 2        | 0.99%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                              | 2        | 0.99%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 2        | 0.99%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s              | 2        | 0.99%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 2000MT/s              | 2        | 0.99%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s              | 2        | 0.99%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s               | 2        | 0.99%   |
| Ramaxel RAM RMUA5120ME86H9F-2666 4GB DIMM DDR4 2667MT/s           | 2        | 0.99%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                 | 2        | 0.99%   |
| Kingston RAM 9905713-026.A00G 4GB DIMM DDR4 2667MT/s              | 2        | 0.99%   |
| V-Color RAM TN4G8C11-H11 4GB DIMM DDR3 1600MT/s                   | 1        | 0.49%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                         | 1        | 0.49%   |
| Unknown RAM Module 4GB DIMM SDRAM                                 | 1        | 0.49%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                              | 1        | 0.49%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 1        | 0.49%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                              | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                          | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                         | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR2 400MT/s                          | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                         | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR2                                  | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM 5354MT/s                              | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                              | 1        | 0.49%   |
| Unknown RAM Module 1GB DIMM DDR2                                  | 1        | 0.49%   |
| Unknown RAM Module 1GB DIMM 800MT/s                               | 1        | 0.49%   |
| Unknown RAM Module 1GB DIMM 667MT/s                               | 1        | 0.49%   |
| Unknown RAM CL17-17-17 D4-2400 16384MB DIMM DDR4 2400MT/s         | 1        | 0.49%   |
| Unknown RAM 2400 C16 Series 8192MB DIMM DDR4 1200MT/s             | 1        | 0.49%   |
| Unknown RAM 1600 CL9 Series 8192MB DIMM DDR3 1066MT/s             | 1        | 0.49%   |
| Unknown (AB) RAM Module 2GB DIMM LPDDR3 1333MT/s                  | 1        | 0.49%   |
| Unknown (0x0B15) RAM JAD3200U1816 16GB DIMM DDR4 2667MT/s         | 1        | 0.49%   |
| Transcend RAM Module 2GB DIMM DDR3 1333MT/s                       | 1        | 0.49%   |
| Timetec RAM UD3-1333 4GB DIMM DDR3 1333MT/s                       | 1        | 0.49%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1        | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 70       | 43.75%  |
| DDR4    | 62       | 38.75%  |
| Unknown | 9        | 5.63%   |
| SDRAM   | 7        | 4.38%   |
| DDR2    | 5        | 3.13%   |
| DDR5    | 4        | 2.5%    |
| LPDDR4  | 2        | 1.25%   |
| LPDDR3  | 1        | 0.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 147      | 93.63%  |
| SODIMM | 10       | 6.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 55       | 32.35%  |
| 4096  | 54       | 31.76%  |
| 16384 | 30       | 17.65%  |
| 2048  | 22       | 12.94%  |
| 32768 | 5        | 2.94%   |
| 1024  | 4        | 2.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 43       | 24.16%  |
| 1333    | 23       | 12.92%  |
| 3200    | 15       | 8.43%   |
| 2400    | 13       | 7.3%    |
| 2667    | 12       | 6.74%   |
| 3600    | 6        | 3.37%   |
| Unknown | 6        | 3.37%   |
| 2133    | 5        | 2.81%   |
| 3000    | 4        | 2.25%   |
| 2666    | 4        | 2.25%   |
| 1866    | 4        | 2.25%   |
| 3466    | 3        | 1.69%   |
| 2000    | 3        | 1.69%   |
| 1867    | 3        | 1.69%   |
| 1800    | 3        | 1.69%   |
| 1066    | 3        | 1.69%   |
| 800     | 3        | 1.69%   |
| 4800    | 2        | 1.12%   |
| 3733    | 2        | 1.12%   |
| 3400    | 2        | 1.12%   |
| 1067    | 2        | 1.12%   |
| 52217   | 1        | 0.56%   |
| 6000    | 1        | 0.56%   |
| 5600    | 1        | 0.56%   |
| 5354    | 1        | 0.56%   |
| 4000    | 1        | 0.56%   |
| 3866    | 1        | 0.56%   |
| 3800    | 1        | 0.56%   |
| 3333    | 1        | 0.56%   |
| 3020    | 1        | 0.56%   |
| 2800    | 1        | 0.56%   |
| 2200    | 1        | 0.56%   |
| 2134    | 1        | 0.56%   |
| 1648    | 1        | 0.56%   |
| 1639    | 1        | 0.56%   |
| 1334    | 1        | 0.56%   |
| 667     | 1        | 0.56%   |
| 400     | 1        | 0.56%   |

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
| Logitech                    | 10       | 28.57%  |
| Microdia                    | 4        | 11.43%  |
| Realtek Semiconductor       | 2        | 5.71%   |
| Microsoft                   | 2        | 5.71%   |
| KYE Systems (Mouse Systems) | 2        | 5.71%   |
| Jieli Technology            | 2        | 5.71%   |
| Xiaomi                      | 1        | 2.86%   |
| Silicon Motion              | 1        | 2.86%   |
| Samsung Electronics         | 1        | 2.86%   |
| Ruision                     | 1        | 2.86%   |
| Quanta                      | 1        | 2.86%   |
| MacroSilicon                | 1        | 2.86%   |
| IMC Networks                | 1        | 2.86%   |
| Guillemot                   | 1        | 2.86%   |
| Generalplus Technology      | 1        | 2.86%   |
| Creative Technology         | 1        | 2.86%   |
| Chicony Electronics         | 1        | 2.86%   |
| Apple                       | 1        | 2.86%   |
| AME Optimedia Technology    | 1        | 2.86%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Realtek FULL HD 1080P Webcam                   | 2        | 5.71%   |
| Logitech HD Webcam C525                        | 2        | 5.71%   |
| Logitech HD Pro Webcam C920                    | 2        | 5.71%   |
| Logitech C922 Pro Stream Webcam                | 2        | 5.71%   |
| Logitech BRIO Ultra HD Webcam                  | 2        | 5.71%   |
| Xiaomi Mi/Redmi series (PTP)                   | 1        | 2.86%   |
| Silicon Motion 300k Pixel Camera               | 1        | 2.86%   |
| Samsung Galaxy series, misc. (MTP mode)        | 1        | 2.86%   |
| Ruision UVC Camera                             | 1        | 2.86%   |
| Quanta HP HD Camera                            | 1        | 2.86%   |
| Microsoft MicrosoftÂ LifeCam Studio           | 1        | 2.86%   |
| Microsoft LifeCam VX-2000                      | 1        | 2.86%   |
| Microdia Webcam Vitade AF                      | 1        | 2.86%   |
| Microdia USB 2.0 Camera                        | 1        | 2.86%   |
| Microdia Sonix USB 2.0 Camera                  | 1        | 2.86%   |
| Microdia Camera                                | 1        | 2.86%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]  | 1        | 2.86%   |
| Logitech Webcam C300                           | 1        | 2.86%   |
| Logitech Webcam C110                           | 1        | 2.86%   |
| KYE Systems (Mouse Systems) iSlim 2020AF       | 1        | 2.86%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320 | 1        | 2.86%   |
| Jieli USB PHY 2.0                              | 1        | 2.86%   |
| Jieli USB Composite Device                     | 1        | 2.86%   |
| IMC Networks USB2.0 UVC HD Webcam              | 1        | 2.86%   |
| Guillemot Hercules Dualpix Exchange            | 1        | 2.86%   |
| Generalplus GENERAL WEBCAM                     | 1        | 2.86%   |
| Creative Live! Cam Sync 1080p                  | 1        | 2.86%   |
| Chicony HP High Definition 1MP Webcam          | 1        | 2.86%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR             | 1        | 2.86%   |
| AME Optimedia P35U Camera Capture              | 1        | 2.86%   |

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
| 0     | 195      | 84.05%  |
| 1     | 31       | 13.36%  |
| 2     | 4        | 1.72%   |
| 3     | 2        | 0.86%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 20       | 47.62%  |
| Net/wireless             | 4        | 9.52%   |
| Unassigned class         | 3        | 7.14%   |
| Sound                    | 2        | 4.76%   |
| Network                  | 2        | 4.76%   |
| Net/ethernet             | 2        | 4.76%   |
| Multimedia controller    | 2        | 4.76%   |
| Chipcard                 | 2        | 4.76%   |
| Camera                   | 2        | 4.76%   |
| Dvb card                 | 1        | 2.38%   |
| Communication controller | 1        | 2.38%   |
| Bluetooth                | 1        | 2.38%   |

